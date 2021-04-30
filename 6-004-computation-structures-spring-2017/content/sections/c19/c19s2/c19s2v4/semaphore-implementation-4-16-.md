---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: VxVF6QzwtwI
  parent_uid: 5b2f7aac29791c027bf5ae0799455976
  title: Video-YouTube-Stream
  type: Video
  uid: ec56250fed4650cffe6ad4686eba3a6f
- id: 3Play-3Play YouTube id-Stream
  media_location: VxVF6QzwtwI
  parent_uid: 5b2f7aac29791c027bf5ae0799455976
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 27521e5d7aa4d40ef5ef201964cedf37
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/VxVF6QzwtwI/default.jpg
  parent_uid: 5b2f7aac29791c027bf5ae0799455976
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 42a3400921debd29e57b8f5059c2490f
- id: VxVF6QzwtwI.srt
  parent_uid: 5b2f7aac29791c027bf5ae0799455976
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v4/semaphore-implementation-4-16-/VxVF6QzwtwI.srt
  title: 3play caption file
  type: null
  uid: bfab61c8d823f415b4f9c0d40b567808
- id: VxVF6QzwtwI.pdf
  parent_uid: 5b2f7aac29791c027bf5ae0799455976
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v4/semaphore-implementation-4-16-/VxVF6QzwtwI.pdf
  title: 3play pdf file
  type: null
  uid: 2bc6c3065a466d004aaab148ea39dafe
- id: Caption-3Play YouTube id-SRT
  parent_uid: 5b2f7aac29791c027bf5ae0799455976
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b8e575d4b8ef64d9443eae096efa53d5
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 5b2f7aac29791c027bf5ae0799455976
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 397f3c21afe456809039ad552572b23f
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_19-02-04_300k.mp4
  parent_uid: 5b2f7aac29791c027bf5ae0799455976
  title: Video-Internet Archive-MP4
  type: Video
  uid: 3e23433585378bb39f6f76ca8705d7ed
inline_embed_id: 19985019semaphoreimplementation41692899391
layout: video
order_index: null
parent_uid: 0904a50e5702f723762e438868012759
related_resources_text: ''
short_url: semaphore-implementation-4-16-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v4/semaphore-implementation-4-16-
template_type: Embed
title: Semaphore Implementation (4:16)
transcript: <p><span m='900'>Now</span> <span m='1315'>let's</span> <span m='1730'>figure</span>
  <span m='2145'>out</span> <span m='2560'>how</span> <span m='2975'>to</span> <span
  m='3390'>implement</span> <span m='3805'>semaphores.</span> </p><p><span m='4220'>They</span>
  <span m='4650'>are</span> <span m='5080'>themselves</span> <span m='5510'>shared</span>
  <span m='5940'>data</span> <span m='6370'>and</span> <span m='6800'>implementing</span>
  <span m='7230'>the</span> <span m='7660'>WAIT</span> <span m='8090'>and</span> <span
  m='8520'>SIGNAL</span> <span m='8950'>operations</span> <span m='9380'>will</span>
  <span m='9810'>require</span> <span m='10240'>read/modify/write</span> <span m='10812'>sequences</span>
  <span m='11384'>that</span> <span m='11956'>must</span> <span m='12528'>be</span>
  <span m='13100'>executed</span> <span m='13672'>as</span> <span m='14244'>critical</span>
  <span m='14816'>sections.</span> </p><p><span m='15389'>Normally</span> <span m='15709'>we'd</span>
  <span m='16029'>use</span> <span m='16349'>a</span> <span m='16669'>lock</span>
  <span m='16989'>semaphore</span> <span m='17309'>to</span> <span m='17629'>implement</span>
  <span m='17949'>the</span> <span m='18269'>mutual</span> <span m='18589'>exclusion</span>
  <span m='18909'>constraint</span> <span m='19229'>for</span> <span m='19549'>critical</span>
  <span m='19869'>sections.</span> </p><p><span m='20869'>But</span> <span m='21356'>obviously</span>
  <span m='21844'>we</span> <span m='22332'>can't</span> <span m='22820'>use</span>
  <span m='23307'>semaphores</span> <span m='23795'>to</span> <span m='24283'>implement</span>
  <span m='24771'>semaphores!</span> </p><p><span m='25259'>We</span> <span m='25596'>have</span>
  <span m='25933'>what's</span> <span m='26270'>called</span> <span m='26607'>a</span>
  <span m='26945'>bootstrapping</span> <span m='27282'>problem:</span> <span m='27619'>we</span>
  <span m='27956'>need</span> <span m='28293'>to</span> <span m='28631'>implement</span>
  <span m='28968'>the</span> <span m='29305'>required</span> <span m='29642'>functionality</span>
  <span m='29980'>from</span> <span m='30845'>scratch.</span> </p><p><span m='31710'>Happily,</span>
  <span m='32180'>if</span> <span m='32650'>we're</span> <span m='33120'>running</span>
  <span m='33590'>on</span> <span m='34060'>a</span> <span m='34530'>timeshared</span>
  <span m='35000'>processor</span> <span m='35470'>with</span> <span m='35940'>an</span>
  <span m='36410'>uninterruptible</span> <span m='36880'>OS</span> <span m='37350'>kernel,</span>
  <span m='37820'>we</span> <span m='38187'>can</span> <span m='38555'>use</span>
  <span m='38923'>the</span> <span m='39290'>supervisor</span> <span m='39658'>call</span>
  <span m='40026'>(SVC)</span> <span m='40393'>mechanism</span> <span m='40761'>to</span>
  <span m='41129'>implement</span> <span m='41496'>the</span> <span m='41864'>required</span>
  <span m='42232'>functionality.</span> </p><p><span m='42600'>We</span> <span m='42928'>can</span>
  <span m='43257'>also</span> <span m='43586'>extend</span> <span m='43915'>the</span>
  <span m='44243'>ISA</span> <span m='44572'>to</span> <span m='44901'>include</span>
  <span m='45230'>a</span> <span m='45558'>special</span> <span m='45887'>test-and-set</span>
  <span m='46216'>instruction</span> <span m='46545'>that</span> <span m='46873'>will</span>
  <span m='47202'>let</span> <span m='47531'>us</span> <span m='47860'>implement</span>
  <span m='48210'>a</span> <span m='48561'>simple</span> <span m='48912'>lock</span>
  <span m='49263'>semaphore,</span> <span m='49613'>which</span> <span m='49964'>can</span>
  <span m='50315'>then</span> <span m='50666'>be</span> <span m='51016'>used</span>
  <span m='51367'>to</span> <span m='51718'>protect</span> <span m='52069'>critical</span>
  <span m='52420'>sections</span> <span m='53082'>that</span> <span m='53745'>implement</span>
  <span m='54408'>more</span> <span m='55071'>complex</span> <span m='55734'>semaphore</span>
  <span m='56397'>semantics.</span> </p><p><span m='57060'>Single</span> <span m='57451'>instructions</span>
  <span m='57843'>are</span> <span m='58234'>inherently</span> <span m='58626'>atomic</span>
  <span m='59017'>and,</span> <span m='59409'>in</span> <span m='59800'>a</span> <span
  m='60192'>multi-core</span> <span m='60583'>processor,</span> <span m='60975'>will</span>
  <span m='61366'>do</span> <span m='61758'>what</span> <span m='62150'>we</span>
  <span m='62433'>want</span> <span m='62717'>if</span> <span m='63000'>the</span>
  <span m='63284'>shared</span> <span m='63567'>main</span> <span m='63851'>memory</span>
  <span m='64134'>supports</span> <span m='64418'>reading</span> <span m='64701'>the</span>
  <span m='64985'>old</span> <span m='65268'>value</span> <span m='65552'>and</span>
  <span m='65835'>writing</span> <span m='66119'>a</span> <span m='66402'>new</span>
  <span m='66686'>value</span> <span m='66970'>to</span> <span m='67504'>a</span>
  <span m='68038'>specific</span> <span m='68572'>memory</span> <span m='69106'>location</span>
  <span m='69640'>as</span> <span m='70174'>a</span> <span m='70708'>single</span>
  <span m='71242'>memory</span> <span m='71776'>access.</span> </p><p><span m='72310'>There</span>
  <span m='72679'>are</span> <span m='73048'>other,</span> <span m='73417'>more</span>
  <span m='73786'>complex,</span> <span m='74156'>software-only</span> <span m='74525'>solutions</span>
  <span m='74894'>that</span> <span m='75263'>rely</span> <span m='75633'>only</span>
  <span m='76002'>on</span> <span m='76371'>the</span> <span m='76740'>atomicity</span>
  <span m='77110'>of</span> <span m='77436'>individual</span> <span m='77762'>reads</span>
  <span m='78088'>and</span> <span m='78414'>writes</span> <span m='78740'>to</span>
  <span m='79066'>implement</span> <span m='79392'>a</span> <span m='79718'>simple</span>
  <span m='80044'>lock.</span> </p><p><span m='80370'>For</span> <span m='80831'>example,</span>
  <span m='81292'>see</span> <span m='81754'>"Dekker's</span> <span m='82215'>Algorithm"</span>
  <span m='82677'>on</span> <span m='83138'>Wikipedia.</span> </p><p><span m='83600'>We'll</span>
  <span m='83905'>look</span> <span m='84210'>in</span> <span m='84515'>more</span>
  <span m='84820'>detail</span> <span m='85125'>at</span> <span m='85430'>the</span>
  <span m='85735'>first</span> <span m='86040'>two</span> <span m='86345'>approaches.</span>
  </p><p><span m='86650'>Here</span> <span m='87070'>are</span> <span m='87491'>the</span>
  <span m='87912'>OS</span> <span m='88333'>handlers</span> <span m='88754'>for</span>
  <span m='89175'>the</span> <span m='89595'>WAIT</span> <span m='90016'>and</span>
  <span m='90437'>SIGNAL</span> <span m='90858'>supervisor</span> <span m='91279'>calls.</span>
  </p><p><span m='91700'>Since</span> <span m='92096'>SVCs</span> <span m='92492'>are</span>
  <span m='92888'>run</span> <span m='93284'>kernel</span> <span m='93680'>mode,</span>
  <span m='94077'>they</span> <span m='94473'>can't</span> <span m='94869'>be</span>
  <span m='95265'>interrupted,</span> <span m='95661'>so</span> <span m='96058'>the</span>
  <span m='96454'>handler</span> <span m='96850'>code</span> <span m='97246'>is</span>
  <span m='97642'>naturally</span> <span m='98039'>executed</span> <span m='98707'>as</span>
  <span m='99375'>a</span> <span m='100043'>critical</span> <span m='100711'>section.</span>
  </p><p><span m='101380'>Both</span> <span m='101675'>handlers</span> <span m='101971'>expect</span>
  <span m='102267'>the</span> <span m='102563'>address</span> <span m='102858'>of</span>
  <span m='103154'>the</span> <span m='103450'>semaphore</span> <span m='103746'>location</span>
  <span m='104041'>to</span> <span m='104337'>be</span> <span m='104633'>passed</span>
  <span m='104929'>as</span> <span m='105224'>an</span> <span m='105520'>argument</span>
  <span m='105816'>in</span> <span m='106112'>the</span> <span m='106408'>user's</span>
  <span m='107749'>R0.</span> </p><p><span m='109090'>The</span> <span m='109416'>WAIT</span>
  <span m='109743'>handler</span> <span m='110070'>checks</span> <span m='110396'>the</span>
  <span m='110723'>semaphore's</span> <span m='111050'>value</span> <span m='111376'>and</span>
  <span m='111703'>if</span> <span m='112030'>it's</span> <span m='112356'>non-zero,</span>
  <span m='112683'>the</span> <span m='113010'>value</span> <span m='113336'>is</span>
  <span m='113663'>decremented</span> <span m='113990'>and</span> <span m='114320'>the</span>
  <span m='114650'>handler</span> <span m='114980'>resumes</span> <span m='115310'>execution</span>
  <span m='115640'>of</span> <span m='115970'>the</span> <span m='116300'>user's</span>
  <span m='116630'>program</span> <span m='116960'>at</span> <span m='117290'>the</span>
  <span m='117620'>instruction</span> <span m='117950'>following</span> <span m='118280'>the</span>
  <span m='118610'>WAIT</span> <span m='118940'>SVC.</span> </p><p><span m='119940'>If</span>
  <span m='120275'>the</span> <span m='120611'>semaphore</span> <span m='120947'>is</span>
  <span m='121283'>0,</span> <span m='121619'>the</span> <span m='121955'>code</span>
  <span m='122291'>arranges</span> <span m='122627'>to</span> <span m='122962'>re-execute</span>
  <span m='123298'>the</span> <span m='123634'>WAIT</span> <span m='123970'>SVC</span>
  <span m='124306'>when</span> <span m='124642'>the</span> <span m='124978'>user</span>
  <span m='125314'>program</span> <span m='125650'>resumes</span> <span m='126111'>execution</span>
  <span m='126572'>and</span> <span m='127033'>then</span> <span m='127495'>calls</span>
  <span m='127956'>SLEEP</span> <span m='128417'>to</span> <span m='128878'>mark</span>
  <span m='129340'>the</span> <span m='129801'>process</span> <span m='130262'>as</span>
  <span m='130723'>inactive</span> <span m='131185'>until</span> <span m='131646'>the</span>
  <span m='132107'>corresponding</span> <span m='132569'>WAKEUP</span> <span m='133341'>call</span>
  <span m='134114'>is</span> <span m='134887'>made.</span> </p><p><span m='135660'>The</span>
  <span m='135985'>SIGNAL</span> <span m='136311'>handler</span> <span m='136637'>is</span>
  <span m='136963'>simpler:</span> <span m='137289'>it</span> <span m='137615'>increments</span>
  <span m='137941'>the</span> <span m='138267'>semaphore</span> <span m='138593'>value</span>
  <span m='138919'>and</span> <span m='139245'>calls</span> <span m='139571'>WAKEUP</span>
  <span m='139897'>to</span> <span m='140223'>mark</span> <span m='140549'>as</span>
  <span m='141119'>active</span> <span m='141690'>any</span> <span m='142261'>processes</span>
  <span m='142832'>that</span> <span m='143403'>were</span> <span m='143974'>WAITing</span>
  <span m='144545'>for</span> <span m='145116'>this</span> <span m='145687'>particular</span>
  <span m='146258'>semaphore.</span> </p><p><span m='146829'>Eventually</span> <span
  m='147105'>the</span> <span m='147382'>round-robin</span> <span m='147658'>scheduler</span>
  <span m='147935'>will</span> <span m='148211'>select</span> <span m='148488'>a</span>
  <span m='148764'>process</span> <span m='149041'>that</span> <span m='149317'>was</span>
  <span m='149594'>WAITing</span> <span m='149870'>and</span> <span m='150147'>it</span>
  <span m='150423'>will</span> <span m='150700'>be</span> <span m='151149'>able</span>
  <span m='151599'>to</span> <span m='152049'>decrement</span> <span m='152499'>the</span>
  <span m='152949'>semaphore</span> <span m='153399'>and</span> <span m='153849'>proceed.</span>
  </p><p><span m='154299'>Note</span> <span m='154636'>that</span> <span m='154974'>the</span>
  <span m='155312'>code</span> <span m='155650'>makes</span> <span m='155988'>no</span>
  <span m='156326'>provision</span> <span m='156664'>for</span> <span m='157002'>fairness,</span>
  <span m='157340'>i.e.,</span> <span m='157678'>there's</span> <span m='158016'>no</span>
  <span m='158354'>guarantee</span> <span m='158692'>that</span> <span m='159030'>a</span>
  <span m='159518'>WAITing</span> <span m='160006'>process</span> <span m='160494'>will</span>
  <span m='160982'>eventually</span> <span m='161470'>succeed</span> <span m='161959'>in</span>
  <span m='162447'>finding</span> <span m='162935'>the</span> <span m='163423'>semaphore</span>
  <span m='163911'>non-zero.</span> </p><p><span m='164400'>The</span> <span m='164759'>scheduler</span>
  <span m='165118'>has</span> <span m='165477'>a</span> <span m='165837'>specific</span>
  <span m='166196'>order</span> <span m='166555'>in</span> <span m='166915'>which</span>
  <span m='167274'>it</span> <span m='167633'>runs</span> <span m='167992'>processes,</span>
  <span m='168352'>so</span> <span m='168711'>the</span> <span m='169070'>next-in-sequence</span>
  <span m='169430'>WAITing</span> <span m='169840'>process</span> <span m='170251'>will</span>
  <span m='170662'>always</span> <span m='171072'>get</span> <span m='171483'>the</span>
  <span m='171894'>semaphore</span> <span m='172304'>even</span> <span m='172715'>if</span>
  <span m='173126'>there</span> <span m='173536'>are</span> <span m='173947'>later-in-sequence</span>
  <span m='174358'>processes</span> <span m='174769'>that</span> <span m='175389'>have</span>
  <span m='176009'>been</span> <span m='176629'>WAITing</span> <span m='177249'>longer.</span>
  </p><p><span m='177870'>If</span> <span m='178129'>fairness</span> <span m='178389'>is</span>
  <span m='178649'>desired,</span> <span m='178909'>WAIT</span> <span m='179169'>could</span>
  <span m='179429'>maintain</span> <span m='179689'>a</span> <span m='179949'>queue</span>
  <span m='180209'>of</span> <span m='180469'>waiting</span> <span m='180729'>processes</span>
  <span m='180989'>and</span> <span m='181249'>use</span> <span m='181509'>the</span>
  <span m='181769'>queue</span> <span m='182029'>to</span> <span m='182513'>determine</span>
  <span m='182997'>which</span> <span m='183481'>process</span> <span m='183966'>is</span>
  <span m='184450'>next</span> <span m='184934'>in</span> <span m='185418'>line,</span>
  <span m='185903'>independent</span> <span m='186387'>of</span> <span m='186871'>scheduling</span>
  <span m='187355'>order.</span> </p><p><span m='187840'>Many</span> <span m='188347'>ISAs</span>
  <span m='188854'>support</span> <span m='189361'>an</span> <span m='189869'>instruction</span>
  <span m='190376'>like</span> <span m='190883'>the</span> <span m='191390'>TEST-and-CLEAR</span>
  <span m='191898'>instruction</span> <span m='192405'>shown</span> <span m='192912'>here.</span>
  </p><p><span m='193420'>The</span> <span m='193748'>TCLR</span> <span m='194076'>instruction</span>
  <span m='194404'>reads</span> <span m='194732'>the</span> <span m='195060'>current</span>
  <span m='195389'>value</span> <span m='195717'>of</span> <span m='196045'>a</span>
  <span m='196373'>memory</span> <span m='196701'>location</span> <span m='197029'>and</span>
  <span m='197358'>then</span> <span m='197686'>sets</span> <span m='198014'>it</span>
  <span m='198342'>to</span> <span m='198670'>zero,</span> <span m='198999'>all</span>
  <span m='199463'>as</span> <span m='199927'>a</span> <span m='200391'>single</span>
  <span m='200855'>operation.</span> </p><p><span m='201319'>It's</span> <span m='201682'>like</span>
  <span m='202045'>a</span> <span m='202409'>LD</span> <span m='202772'>except</span>
  <span m='203135'>that</span> <span m='203499'>it</span> <span m='203862'>zeros</span>
  <span m='204225'>the</span> <span m='204589'>memory</span> <span m='204952'>location</span>
  <span m='205315'>after</span> <span m='205679'>reading</span> <span m='206042'>its</span>
  <span m='206405'>value.</span> </p><p><span m='206769'>To</span> <span m='207123'>implement</span>
  <span m='207477'>TCLR,</span> <span m='207832'>the</span> <span m='208186'>memory</span>
  <span m='208540'>needs</span> <span m='208895'>to</span> <span m='209249'>support</span>
  <span m='209603'>read-and-clear</span> <span m='209958'>operations,</span> <span
  m='210312'>as</span> <span m='210666'>well</span> <span m='211021'>as</span> <span
  m='211375'>normal</span> <span m='211730'>reads</span> <span m='212380'>and</span>
  <span m='213030'>writes.</span> </p><p><span m='213680'>The</span> <span m='213907'>assembly</span>
  <span m='214135'>code</span> <span m='214363'>at</span> <span m='214590'>the</span>
  <span m='214818'>bottom</span> <span m='215046'>of</span> <span m='215274'>the</span>
  <span m='215501'>slide</span> <span m='215729'>shows</span> <span m='215957'>how</span>
  <span m='216184'>to</span> <span m='216412'>use</span> <span m='216640'>TCLR</span>
  <span m='216868'>to</span> <span m='217095'>implement</span> <span m='217323'>a</span>
  <span m='217551'>simple</span> <span m='217779'>lock.</span> </p><p><span m='219540'>The</span>
  <span m='219909'>program</span> <span m='220278'>uses</span> <span m='220647'>TCLR</span>
  <span m='221016'>to</span> <span m='221385'>access</span> <span m='221754'>the</span>
  <span m='222123'>value</span> <span m='222492'>of</span> <span m='222861'>the</span>
  <span m='223230'>lock</span> <span m='223599'>semaphore.</span> </p><p><span m='223969'>If</span>
  <span m='224281'>the</span> <span m='224593'>returned</span> <span m='224905'>value</span>
  <span m='225218'>in</span> <span m='225530'>RC</span> <span m='225842'>is</span>
  <span m='226154'>zero,</span> <span m='226467'>then</span> <span m='226779'>some</span>
  <span m='227091'>other</span> <span m='227404'>process</span> <span m='227716'>has</span>
  <span m='228028'>the</span> <span m='228340'>lock</span> <span m='228653'>and</span>
  <span m='228965'>the</span> <span m='229277'>program</span> <span m='229590'>loops</span>
  <span m='230258'>to</span> <span m='230926'>try</span> <span m='231594'>TCLR</span>
  <span m='232262'>again.</span> </p><p><span m='232930'>If</span> <span m='233243'>the</span>
  <span m='233556'>returned</span> <span m='233869'>value</span> <span m='234182'>is</span>
  <span m='234495'>non-zero,</span> <span m='234808'>the</span> <span m='235121'>lock</span>
  <span m='235434'>has</span> <span m='235747'>been</span> <span m='236060'>acquired</span>
  <span m='236373'>and</span> <span m='236686'>execution</span> <span m='236999'>of</span>
  <span m='237312'>the</span> <span m='237625'>critical</span> <span m='237939'>section</span>
  <span m='238725'>can</span> <span m='239512'>proceed.</span> </p><p><span m='240299'>In</span>
  <span m='240603'>this</span> <span m='240907'>case,</span> <span m='241212'>TCLR</span>
  <span m='241516'>has</span> <span m='241821'>also</span> <span m='242125'>set</span>
  <span m='242430'>the</span> <span m='242734'>lock</span> <span m='243039'>to</span>
  <span m='243343'>zero,</span> <span m='243647'>so</span> <span m='243952'>that</span>
  <span m='244256'>other</span> <span m='244561'>processes</span> <span m='244865'>will</span>
  <span m='245170'>be</span> <span m='245474'>prevented</span> <span m='245779'>from</span>
  <span m='246379'>entering</span> <span m='246979'>the</span> <span m='247579'>critical</span>
  <span m='248179'>section.</span> </p><p><span m='248779'>When</span> <span m='249098'>the</span>
  <span m='249417'>critical</span> <span m='249737'>section</span> <span m='250056'>has</span>
  <span m='250376'>finished</span> <span m='250695'>executing,</span> <span m='251015'>a</span>
  <span m='251334'>ST</span> <span m='251653'>instruction</span> <span m='251973'>is</span>
  <span m='252292'>used</span> <span m='252612'>to</span> <span m='252931'>set</span>
  <span m='253251'>the</span> <span m='253570'>semaphore</span> <span m='253890'>to</span>
  <span m='254272'>a</span> <span m='254655'>non-zero</span> <span m='255037'>value.</span>
  </p>
type: course
uid: 5b2f7aac29791c027bf5ae0799455976

---
None