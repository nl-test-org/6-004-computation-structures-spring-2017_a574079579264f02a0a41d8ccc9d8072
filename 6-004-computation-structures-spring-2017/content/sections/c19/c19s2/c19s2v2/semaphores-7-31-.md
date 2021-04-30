---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 70auqrv84y8
  parent_uid: 97d0ffb4e1940932c7b31dd6beaac394
  title: Video-YouTube-Stream
  type: Video
  uid: c8c12803eca70d2683befa2e97a0f3a7
- id: 3Play-3Play YouTube id-Stream
  media_location: 70auqrv84y8
  parent_uid: 97d0ffb4e1940932c7b31dd6beaac394
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 07857d19d84a93627f20906dc46b4058
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/70auqrv84y8/default.jpg
  parent_uid: 97d0ffb4e1940932c7b31dd6beaac394
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 2133446e1a2b7835fae4823d0fbce89f
- id: 70auqrv84y8.srt
  parent_uid: 97d0ffb4e1940932c7b31dd6beaac394
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v2/semaphores-7-31-/70auqrv84y8.srt
  title: 3play caption file
  type: null
  uid: bf4d9311c16df53291fd3a8185553476
- id: 70auqrv84y8.pdf
  parent_uid: 97d0ffb4e1940932c7b31dd6beaac394
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v2/semaphores-7-31-/70auqrv84y8.pdf
  title: 3play pdf file
  type: null
  uid: 033e37eccf00a4e83093cdc6025a38e8
- id: Caption-3Play YouTube id-SRT
  parent_uid: 97d0ffb4e1940932c7b31dd6beaac394
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 8a466e758acad1d04f940ca82090c4f7
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 97d0ffb4e1940932c7b31dd6beaac394
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: d020af8e2c06ddfd305affdec52a6389
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_19-02-02_300k.mp4
  parent_uid: 97d0ffb4e1940932c7b31dd6beaac394
  title: Video-Internet Archive-MP4
  type: Video
  uid: f1e124365805e9b3ba400d330b6406cf
inline_embed_id: 5021681semaphores73174557410
layout: video
order_index: null
parent_uid: 724b09ab49487a9aa935442144ab22d1
related_resources_text: ''
short_url: semaphores-7-31-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v2/semaphores-7-31-
template_type: Embed
title: Semaphores (7:31)
transcript: <p><span m='1010'>What</span> <span m='1243'>we'd</span> <span m='1476'>like</span>
  <span m='1710'>to</span> <span m='1943'>do</span> <span m='2176'>is</span> <span
  m='2410'>to</span> <span m='2643'>create</span> <span m='2876'>a</span> <span m='3110'>single</span>
  <span m='3343'>abstraction</span> <span m='3576'>that</span> <span m='3810'>can</span>
  <span m='4043'>be</span> <span m='4276'>used</span> <span m='4510'>to</span> <span
  m='4743'>address</span> <span m='4976'>all</span> <span m='5210'>our</span> <span
  m='6013'>synchronization</span> <span m='6816'>needs.</span> </p><p><span m='7620'>In</span>
  <span m='8029'>the</span> <span m='8438'>early</span> <span m='8848'>1960's,</span>
  <span m='9257'>the</span> <span m='9666'>Dutch</span> <span m='10076'>computer</span>
  <span m='10485'>scientist</span> <span m='10894'>Edsger</span> <span m='11304'>Dijkstra</span>
  <span m='11713'>proposed</span> <span m='12122'>a</span> <span m='12532'>new</span>
  <span m='12941'>abstract</span> <span m='13350'>data</span> <span m='13760'>type</span>
  <span m='14140'>called</span> <span m='14521'>the</span> <span m='14902'>semaphore,</span>
  <span m='15282'>which</span> <span m='15663'>has</span> <span m='16044'>an</span>
  <span m='16424'>integer</span> <span m='16805'>value</span> <span m='17186'>greater</span>
  <span m='17566'>than</span> <span m='17947'>or</span> <span m='18328'>equal</span>
  <span m='18708'>to</span> <span m='19089'>0.</span> </p><p><span m='19470'>A</span>
  <span m='19917'>programmer</span> <span m='20365'>can</span> <span m='20812'>declare</span>
  <span m='21260'>a</span> <span m='21708'>semaphore</span> <span m='22155'>as</span>
  <span m='22603'>shown</span> <span m='23050'>here,</span> <span m='23498'>specifying</span>
  <span m='23946'>its</span> <span m='24393'>initial</span> <span m='24841'>value.</span>
  </p><p><span m='25289'>The</span> <span m='25574'>semaphore</span> <span m='25860'>lives</span>
  <span m='26146'>in</span> <span m='26431'>a</span> <span m='26717'>memory</span>
  <span m='27003'>location</span> <span m='27288'>shared</span> <span m='27574'>by</span>
  <span m='27860'>all</span> <span m='28145'>the</span> <span m='28431'>processes</span>
  <span m='28717'>that</span> <span m='29002'>need</span> <span m='29288'>to</span>
  <span m='29574'>synchronize</span> <span m='29860'>their</span> <span m='31134'>operation.</span>
  </p><p><span m='32409'>The</span> <span m='32897'>semaphore</span> <span m='33385'>is</span>
  <span m='33873'>accessed</span> <span m='34361'>with</span> <span m='34849'>two</span>
  <span m='35337'>operations:</span> <span m='35825'>WAIT</span> <span m='36313'>and</span>
  <span m='36801'>SIGNAL.</span> </p><p><span m='37289'>The</span> <span m='37580'>WAIT</span>
  <span m='37872'>operation</span> <span m='38164'>will</span> <span m='38456'>wait</span>
  <span m='38748'>until</span> <span m='39040'>the</span> <span m='39332'>specified</span>
  <span m='39624'>semaphore</span> <span m='39916'>has</span> <span m='40208'>a</span>
  <span m='40500'>value</span> <span m='40792'>greater</span> <span m='41084'>than</span>
  <span m='41376'>0,</span> <span m='41668'>then</span> <span m='41960'>it</span>
  <span m='42321'>will</span> <span m='42683'>decrement</span> <span m='43044'>the</span>
  <span m='43406'>semaphore</span> <span m='43767'>value</span> <span m='44129'>and</span>
  <span m='44491'>return</span> <span m='44852'>to</span> <span m='45214'>the</span>
  <span m='45575'>calling</span> <span m='45937'>program.</span> </p><p><span m='46299'>If</span>
  <span m='46701'>the</span> <span m='47104'>semaphore</span> <span m='47507'>value</span>
  <span m='47909'>is</span> <span m='48312'>0</span> <span m='48715'>when</span> <span
  m='49118'>WAIT</span> <span m='49520'>is</span> <span m='49923'>called,</span> <span
  m='50326'>conceptually</span> <span m='50729'>execution</span> <span m='51131'>is</span>
  <span m='51534'>suspended</span> <span m='51937'>until</span> <span m='52340'>the</span>
  <span m='52992'>semaphore</span> <span m='53644'>value</span> <span m='54296'>is</span>
  <span m='54948'>non-zero.</span> </p><p><span m='55600'>In</span> <span m='56052'>a</span>
  <span m='56505'>simple</span> <span m='56957'>(inefficient)</span> <span m='57410'>implementation,</span>
  <span m='57863'>the</span> <span m='58315'>WAIT</span> <span m='58768'>routine</span>
  <span m='59221'>loops,</span> <span m='59673'>periodically</span> <span m='60126'>testing</span>
  <span m='60579'>the</span> <span m='60922'>value</span> <span m='61266'>of</span>
  <span m='61610'>the</span> <span m='61953'>semaphore,</span> <span m='62297'>proceeding</span>
  <span m='62641'>when</span> <span m='62985'>its</span> <span m='63328'>value</span>
  <span m='63672'>is</span> <span m='64016'>non-zero.</span> </p><p><span m='64360'>The</span>
  <span m='64807'>SIGNAL</span> <span m='65254'>operation</span> <span m='65701'>increments</span>
  <span m='66148'>the</span> <span m='66595'>value</span> <span m='67042'>of</span>
  <span m='67489'>the</span> <span m='67936'>specified</span> <span m='68383'>semaphore.</span>
  </p><p><span m='68830'>If</span> <span m='69246'>there</span> <span m='69662'>any</span>
  <span m='70078'>processes</span> <span m='70494'>WAITing</span> <span m='70910'>on</span>
  <span m='71326'>that</span> <span m='71742'>semaphore,</span> <span m='72158'>exactly</span>
  <span m='72574'>one</span> <span m='72990'>of</span> <span m='73406'>them</span>
  <span m='73822'>may</span> <span m='74238'>now</span> <span m='74654'>proceed.</span>
  </p><p><span m='75070'>We'll</span> <span m='75353'>have</span> <span m='75637'>to</span>
  <span m='75920'>be</span> <span m='76204'>careful</span> <span m='76487'>with</span>
  <span m='76771'>the</span> <span m='77054'>implementation</span> <span m='77338'>of</span>
  <span m='77621'>SIGNAL</span> <span m='77905'>and</span> <span m='78188'>WAIT</span>
  <span m='78472'>to</span> <span m='78755'>ensure</span> <span m='79039'>that</span>
  <span m='79322'>the</span> <span m='79606'>"exactly</span> <span m='79890'>one"</span>
  <span m='80268'>constraint</span> <span m='80646'>is</span> <span m='81025'>satisfied,</span>
  <span m='81403'>i.e.,</span> <span m='81781'>that</span> <span m='82160'>two</span>
  <span m='82538'>processes</span> <span m='82916'>both</span> <span m='83295'>WAITing</span>
  <span m='83673'>on</span> <span m='84051'>the</span> <span m='84430'>same</span>
  <span m='84830'>semaphore</span> <span m='85231'>won't</span> <span m='85631'>both</span>
  <span m='86032'>think</span> <span m='86433'>they</span> <span m='86833'>can</span>
  <span m='87234'>decrement</span> <span m='87635'>it</span> <span m='88035'>and</span>
  <span m='88436'>proceed</span> <span m='88837'>after</span> <span m='89237'>a</span>
  <span m='89638'>SIGNAL.</span> </p><p><span m='90039'>A</span> <span m='90402'>semaphore</span>
  <span m='90766'>initialized</span> <span m='91130'>with</span> <span m='91494'>the</span>
  <span m='91858'>value</span> <span m='92221'>K</span> <span m='92585'>guarantees</span>
  <span m='92949'>that</span> <span m='93313'>the</span> <span m='93677'>i_th</span>
  <span m='94040'>call</span> <span m='94404'>to</span> <span m='94768'>SIGNAL</span>
  <span m='95132'>will</span> <span m='95496'>precede</span> <span m='95860'>(i+K)_th</span>
  <span m='96730'>call</span> <span m='97600'>to</span> <span m='98470'>WAIT.</span>
  </p><p><span m='99340'>In</span> <span m='99641'>a</span> <span m='99942'>moment,</span>
  <span m='100244'>we'll</span> <span m='100545'>see</span> <span m='100847'>some</span>
  <span m='101148'>concrete</span> <span m='101450'>examples</span> <span m='101751'>that</span>
  <span m='102053'>will</span> <span m='102354'>make</span> <span m='102656'>this</span>
  <span m='102957'>clear.</span> </p><p><span m='103259'>Note</span> <span m='103671'>that</span>
  <span m='104084'>in</span> <span m='104497'>6.004,</span> <span m='104910'>we're</span>
  <span m='105323'>ruling</span> <span m='105735'>out</span> <span m='106148'>semaphores</span>
  <span m='106561'>with</span> <span m='106974'>negative</span> <span m='107387'>values.</span>
  </p><p><span m='107800'>In</span> <span m='108221'>the</span> <span m='108642'>literature,</span>
  <span m='109063'>you</span> <span m='109484'>may</span> <span m='109905'>see</span>
  <span m='110326'>P(s)</span> <span m='110747'>used</span> <span m='111168'>in</span>
  <span m='111590'>place</span> <span m='112011'>of</span> <span m='112432'>WAIT(s)</span>
  <span m='112853'>and</span> <span m='113274'>V(s)</span> <span m='113695'>used</span>
  <span m='114116'>in</span> <span m='114537'>place</span> <span m='114958'>of</span>
  <span m='115380'>SIGNAL(s).</span> </p><p><span m='117030'>These</span> <span m='117413'>operation</span>
  <span m='117796'>names</span> <span m='118179'>are</span> <span m='118562'>derived</span>
  <span m='118945'>from</span> <span m='119328'>the</span> <span m='119711'>Dutch</span>
  <span m='120094'>words</span> <span m='120477'>for</span> <span m='120860'>"test"</span>
  <span m='121243'>and</span> <span m='121626'>"increase".</span> </p><p><span m='122010'>Let's</span>
  <span m='122442'>see</span> <span m='122874'>how</span> <span m='123306'>to</span>
  <span m='123738'>use</span> <span m='124170'>semaphores</span> <span m='124602'>to</span>
  <span m='125034'>implement</span> <span m='125466'>precedence</span> <span m='125898'>constraints.</span>
  </p><p><span m='126330'>Here</span> <span m='126793'>are</span> <span m='127257'>two</span>
  <span m='127720'>processes,</span> <span m='128184'>each</span> <span m='128648'>running</span>
  <span m='129111'>a</span> <span m='129575'>program</span> <span m='130039'>with</span>
  <span m='130502'>5</span> <span m='130966'>statements.</span> </p><p><span m='131430'>Execution</span>
  <span m='131803'>proceeds</span> <span m='132176'>sequentially</span> <span m='132549'>within</span>
  <span m='132922'>each</span> <span m='133295'>process,</span> <span m='133668'>so</span>
  <span m='134041'>A1</span> <span m='134414'>executes</span> <span m='134787'>before</span>
  <span m='135160'>A2,</span> <span m='135533'>and</span> <span m='135906'>so</span>
  <span m='136280'>on.</span> </p><p><span m='137380'>But</span> <span m='137726'>there</span>
  <span m='138073'>are</span> <span m='138419'>no</span> <span m='138766'>constraints</span>
  <span m='139113'>on</span> <span m='139459'>the</span> <span m='139806'>order</span>
  <span m='140152'>of</span> <span m='140499'>execution</span> <span m='140846'>between</span>
  <span m='141192'>the</span> <span m='141539'>processes,</span> <span m='141885'>so</span>
  <span m='142232'>statement</span> <span m='142579'>B1</span> <span m='142986'>in</span>
  <span m='143394'>Process</span> <span m='143802'>B</span> <span m='144209'>might</span>
  <span m='144617'>be</span> <span m='145025'>executed</span> <span m='145432'>before</span>
  <span m='145840'>or</span> <span m='146248'>after</span> <span m='146656'>any</span>
  <span m='147063'>of</span> <span m='147471'>the</span> <span m='147879'>statements</span>
  <span m='148286'>in</span> <span m='148694'>Process</span> <span m='149102'>A.</span>
  </p><p><span m='149510'>Even</span> <span m='149847'>if</span> <span m='150185'>A</span>
  <span m='150522'>and</span> <span m='150860'>B</span> <span m='151197'>are</span>
  <span m='151535'>running</span> <span m='151872'>in</span> <span m='152210'>a</span>
  <span m='152547'>timeshared</span> <span m='152885'>environment</span> <span m='153222'>on</span>
  <span m='153560'>a</span> <span m='153897'>single</span> <span m='154235'>physical</span>
  <span m='154572'>processor,</span> <span m='154910'>execution</span> <span m='155330'>may</span>
  <span m='155751'>switch</span> <span m='156172'>at</span> <span m='156593'>any</span>
  <span m='157014'>time</span> <span m='157435'>between</span> <span m='157856'>processes</span>
  <span m='158277'>A</span> <span m='158698'>and</span> <span m='159119'>B.</span>
  </p><p><span m='159540'>Suppose</span> <span m='159912'>we</span> <span m='160284'>wish</span>
  <span m='160656'>to</span> <span m='161028'>impose</span> <span m='161400'>the</span>
  <span m='161772'>constraint</span> <span m='162144'>that</span> <span m='162516'>the</span>
  <span m='162888'>execution</span> <span m='163260'>of</span> <span m='163632'>statement</span>
  <span m='164004'>A2</span> <span m='164376'>completes</span> <span m='164748'>before</span>
  <span m='165120'>execution</span> <span m='165804'>of</span> <span m='166488'>statement</span>
  <span m='167172'>B4</span> <span m='167856'>begins.</span> </p><p><span m='168540'>The</span>
  <span m='168966'>red</span> <span m='169392'>arrow</span> <span m='169818'>shows</span>
  <span m='170245'>the</span> <span m='170671'>constraint</span> <span m='171097'>we</span>
  <span m='171523'>want.</span> </p><p><span m='171950'>Here's</span> <span m='172352'>the</span>
  <span m='172754'>recipe</span> <span m='173156'>for</span> <span m='173559'>implementing</span>
  <span m='173961'>this</span> <span m='174363'>sort</span> <span m='174766'>of</span>
  <span m='175168'>simple</span> <span m='175570'>precedence</span> <span m='175973'>constraint</span>
  <span m='176375'>using</span> <span m='176777'>semaphores.</span> </p><p><span m='177180'>First,</span>
  <span m='177684'>declare</span> <span m='178188'>a</span> <span m='178692'>semaphore</span>
  <span m='179196'>(called</span> <span m='179701'>"s"</span> <span m='180205'>in</span>
  <span m='180709'>this</span> <span m='181213'>example)</span> <span m='181717'>and</span>
  <span m='182222'>initialize</span> <span m='182726'>its</span> <span m='183230'>value</span>
  <span m='183734'>to</span> <span m='184239'>0.</span> </p><p><span m='185870'>Place</span>
  <span m='186152'>a</span> <span m='186435'>call</span> <span m='186718'>to</span>
  <span m='187000'>signal(s)</span> <span m='187283'>at</span> <span m='187566'>the</span>
  <span m='187849'>start</span> <span m='188131'>of</span> <span m='188414'>the</span>
  <span m='188697'>arrow.</span> </p><p><span m='188980'>In</span> <span m='189392'>this</span>
  <span m='189804'>example,</span> <span m='190216'>signal(s)</span> <span m='190629'>is</span>
  <span m='191041'>placed</span> <span m='191453'>after</span> <span m='191866'>the</span>
  <span m='192278'>statement</span> <span m='192690'>A2</span> <span m='193103'>in</span>
  <span m='193515'>process</span> <span m='193927'>A.</span> </p><p><span m='194340'>Then</span>
  <span m='194648'>place</span> <span m='194956'>a</span> <span m='195265'>call</span>
  <span m='195573'>to</span> <span m='195881'>wait(s)</span> <span m='196190'>at</span>
  <span m='196498'>the</span> <span m='196806'>end</span> <span m='197115'>of</span>
  <span m='197423'>the</span> <span m='197731'>arrow.</span> </p><p><span m='198040'>In</span>
  <span m='198477'>this</span> <span m='198915'>example,</span> <span m='199353'>wait(s)</span>
  <span m='199790'>is</span> <span m='200228'>placed</span> <span m='200666'>before</span>
  <span m='201103'>the</span> <span m='201541'>statement</span> <span m='201979'>B4</span>
  <span m='202416'>in</span> <span m='202854'>process</span> <span m='203292'>B.</span>
  </p><p><span m='203730'>With</span> <span m='204081'>these</span> <span m='204432'>modifications,</span>
  <span m='204784'>process</span> <span m='205135'>A</span> <span m='205487'>executes</span>
  <span m='205838'>as</span> <span m='206190'>before,</span> <span m='206541'>with</span>
  <span m='206892'>the</span> <span m='207244'>signal</span> <span m='207595'>to</span>
  <span m='207947'>semaphore</span> <span m='208298'>s</span> <span m='208650'>happening</span>
  <span m='209201'>after</span> <span m='209753'>statement</span> <span m='210304'>A2</span>
  <span m='210856'>is</span> <span m='211407'>executed.</span> </p><p><span m='211959'>Statements</span>
  <span m='212458'>B1</span> <span m='212957'>through</span> <span m='213457'>B3</span>
  <span m='213956'>also</span> <span m='214456'>execute</span> <span m='214955'>as</span>
  <span m='215455'>before,</span> <span m='215954'>but</span> <span m='216454'>when</span>
  <span m='216953'>the</span> <span m='217453'>wait(s)</span> <span m='217952'>is</span>
  <span m='218452'>executed,</span> <span m='218951'>execution</span> <span m='219451'>of</span>
  <span m='219969'>process</span> <span m='220487'>B</span> <span m='221005'>is</span>
  <span m='221523'>suspended</span> <span m='222041'>until</span> <span m='222559'>the</span>
  <span m='223077'>signal(s)</span> <span m='223595'>statement</span> <span m='224113'>has</span>
  <span m='224631'>finished</span> <span m='225149'>execution.</span> </p><p><span
  m='225668'>This</span> <span m='226176'>guarantees</span> <span m='226685'>that</span>
  <span m='227194'>execution</span> <span m='227702'>of</span> <span m='228211'>B4</span>
  <span m='228720'>will</span> <span m='229229'>start</span> <span m='229737'>only</span>
  <span m='230246'>after</span> <span m='230755'>execution</span> <span m='231264'>of</span>
  <span m='231772'>A2</span> <span m='232281'>has</span> <span m='232790'>completed.</span>
  </p><p><span m='233299'>By</span> <span m='233670'>initializing</span> <span m='234041'>the</span>
  <span m='234412'>semaphore</span> <span m='234783'>s</span> <span m='235154'>to</span>
  <span m='235526'>0,</span> <span m='235897'>we</span> <span m='236268'>enforced</span>
  <span m='236639'>the</span> <span m='237010'>constraint</span> <span m='237381'>that</span>
  <span m='237753'>the</span> <span m='238124'>first</span> <span m='238495'>call</span>
  <span m='238866'>to</span> <span m='239237'>signal(s)</span> <span m='239609'>had</span>
  <span m='240090'>to</span> <span m='240571'>complete</span> <span m='241052'>before</span>
  <span m='241533'>the</span> <span m='242014'>first</span> <span m='242495'>call</span>
  <span m='242976'>to</span> <span m='243457'>wait(s)</span> <span m='243938'>would</span>
  <span m='244419'>succeed.</span> </p><p><span m='244900'>Another</span> <span m='245204'>way</span>
  <span m='245508'>to</span> <span m='245813'>think</span> <span m='246117'>about</span>
  <span m='246421'>semaphores</span> <span m='246726'>is</span> <span m='247030'>as</span>
  <span m='247335'>a</span> <span m='247639'>management</span> <span m='247943'>tool</span>
  <span m='248248'>for</span> <span m='248552'>a</span> <span m='248857'>shared</span>
  <span m='249161'>pool</span> <span m='249465'>of</span> <span m='249770'>K</span>
  <span m='250074'>resources,</span> <span m='250379'>where</span> <span m='250773'>K</span>
  <span m='251168'>is</span> <span m='251562'>the</span> <span m='251957'>initial</span>
  <span m='252351'>value</span> <span m='252746'>of</span> <span m='253140'>the</span>
  <span m='253535'>semaphore.</span> </p><p><span m='253930'>You</span> <span m='254219'>use</span>
  <span m='254508'>the</span> <span m='254797'>SIGNAL</span> <span m='255087'>operation</span>
  <span m='255376'>to</span> <span m='255665'>add</span> <span m='255955'>or</span>
  <span m='256244'>return</span> <span m='256533'>resources</span> <span m='256822'>to</span>
  <span m='257112'>the</span> <span m='257401'>shared</span> <span m='257690'>pool.</span>
  </p><p><span m='257980'>And</span> <span m='258342'>you</span> <span m='258705'>use</span>
  <span m='259068'>the</span> <span m='259431'>WAIT</span> <span m='259794'>operation</span>
  <span m='260157'>to</span> <span m='260520'>allocate</span> <span m='260882'>a</span>
  <span m='261245'>resource</span> <span m='261608'>for</span> <span m='261971'>your</span>
  <span m='262334'>exclusive</span> <span m='262697'>use.</span> </p><p><span m='263060'>At</span>
  <span m='263429'>any</span> <span m='263798'>given</span> <span m='264168'>time,</span>
  <span m='264537'>the</span> <span m='264906'>value</span> <span m='265276'>of</span>
  <span m='265645'>the</span> <span m='266014'>semaphore</span> <span m='266384'>gives</span>
  <span m='266753'>the</span> <span m='267122'>number</span> <span m='267492'>of</span>
  <span m='267861'>unallocated</span> <span m='268230'>resources</span> <span m='268600'>still</span>
  <span m='269095'>available</span> <span m='269590'>in</span> <span m='270085'>the</span>
  <span m='270580'>shared</span> <span m='271075'>pool.</span> </p><p><span m='271570'>Note</span>
  <span m='271840'>that</span> <span m='272111'>the</span> <span m='272381'>WAIT</span>
  <span m='272652'>and</span> <span m='272922'>SIGNAL</span> <span m='273193'>operations</span>
  <span m='273463'>can</span> <span m='273734'>be</span> <span m='274005'>in</span>
  <span m='274275'>the</span> <span m='274546'>same</span> <span m='274816'>process,</span>
  <span m='275087'>or</span> <span m='275357'>they</span> <span m='275628'>may</span>
  <span m='275898'>be</span> <span m='276169'>in</span> <span m='276440'>different</span>
  <span m='276959'>processes,</span> <span m='277478'>depending</span> <span m='277997'>on</span>
  <span m='278516'>when</span> <span m='279035'>the</span> <span m='279554'>resource</span>
  <span m='280073'>is</span> <span m='280592'>allocated</span> <span m='281111'>and</span>
  <span m='281630'>returned.</span> </p><p><span m='282150'>We</span> <span m='282535'>can</span>
  <span m='282920'>use</span> <span m='283305'>semaphores</span> <span m='283690'>to</span>
  <span m='284075'>manage</span> <span m='284460'>our</span> <span m='284845'>N-character</span>
  <span m='285230'>FIFO</span> <span m='285615'>buffer.</span> </p><p><span m='286000'>Here</span>
  <span m='286350'>we've</span> <span m='286700'>defined</span> <span m='287050'>a</span>
  <span m='287400'>semaphore</span> <span m='287750'>CHARS</span> <span m='288100'>and</span>
  <span m='288450'>initialized</span> <span m='288800'>it</span> <span m='289150'>to</span>
  <span m='289500'>0.</span> </p><p><span m='289850'>The</span> <span m='290169'>value</span>
  <span m='290488'>of</span> <span m='290807'>CHARS</span> <span m='291127'>will</span>
  <span m='291446'>tell</span> <span m='291765'>us</span> <span m='292085'>how</span>
  <span m='292404'>many</span> <span m='292723'>characters</span> <span m='293042'>are</span>
  <span m='293362'>in</span> <span m='293681'>the</span> <span m='294000'>buffer.</span>
  </p><p><span m='294320'>So</span> <span m='294622'>SEND</span> <span m='294925'>does</span>
  <span m='295228'>a</span> <span m='295530'>signal(CHARS)</span> <span m='295833'>after</span>
  <span m='296136'>it</span> <span m='296438'>has</span> <span m='296741'>added</span>
  <span m='297044'>a</span> <span m='297346'>character</span> <span m='297649'>to</span>
  <span m='297952'>the</span> <span m='298254'>buffer,</span> <span m='298557'>indicating</span>
  <span m='298860'>the</span> <span m='299275'>buffer</span> <span m='299691'>now</span>
  <span m='300107'>contains</span> <span m='300522'>an</span> <span m='300938'>additional</span>
  <span m='301354'>character.</span> </p><p><span m='301770'>And</span> <span m='302128'>RCV</span>
  <span m='302487'>does</span> <span m='302846'>a</span> <span m='303205'>wait(CHARS)</span>
  <span m='303563'>to</span> <span m='303922'>ensure</span> <span m='304281'>the</span>
  <span m='304640'>buffer</span> <span m='304998'>has</span> <span m='305357'>at</span>
  <span m='305716'>least</span> <span m='306075'>one</span> <span m='306433'>character</span>
  <span m='306792'>before</span> <span m='307151'>reading</span> <span m='307510'>from</span>
  <span m='308270'>the</span> <span m='309030'>buffer.</span> </p><p><span m='309790'>Since</span>
  <span m='310088'>CHARS</span> <span m='310386'>was</span> <span m='310684'>initialized</span>
  <span m='310982'>to</span> <span m='311280'>0,</span> <span m='311578'>we've</span>
  <span m='311876'>enforced</span> <span m='312175'>the</span> <span m='312473'>constraint</span>
  <span m='312771'>that</span> <span m='313069'>the</span> <span m='313367'>i_th</span>
  <span m='313665'>call</span> <span m='313963'>to</span> <span m='314261'>signal(CHARS)</span>
  <span m='314560'>precedes</span> <span m='314877'>the</span> <span m='315195'>completion</span>
  <span m='315513'>of</span> <span m='315831'>the</span> <span m='316148'>i_th</span>
  <span m='316466'>call</span> <span m='316784'>to</span> <span m='317102'>wait(CHARS).</span>
  </p><p><span m='317420'>In</span> <span m='317750'>other</span> <span m='318080'>words,</span>
  <span m='318410'>RCV</span> <span m='318740'>can't</span> <span m='319070'>consume</span>
  <span m='319400'>a</span> <span m='319730'>character</span> <span m='320060'>until</span>
  <span m='320390'>it</span> <span m='320720'>has</span> <span m='321050'>been</span>
  <span m='321380'>placed</span> <span m='321710'>in</span> <span m='322040'>the</span>
  <span m='322370'>buffer</span> <span m='322700'>by</span> <span m='323030'>SEND.</span>
  </p><p><span m='324040'>Does</span> <span m='324505'>this</span> <span m='324970'>mean</span>
  <span m='325436'>our</span> <span m='325901'>producer</span> <span m='326367'>and</span>
  <span m='326832'>consumer</span> <span m='327298'>are</span> <span m='327763'>now</span>
  <span m='328229'>properly</span> <span m='328694'>synchronized?</span> </p><p><span
  m='329160'>Using</span> <span m='329440'>the</span> <span m='329720'>CHARS</span>
  <span m='330000'>semaphore,</span> <span m='330280'>we</span> <span m='330560'>implemented</span>
  <span m='330840'>*one*</span> <span m='331120'>of</span> <span m='331400'>the</span>
  <span m='331680'>two</span> <span m='331960'>precedence</span> <span m='332240'>constraints</span>
  <span m='332520'>we</span> <span m='332800'>identified</span> <span m='333370'>as</span>
  <span m='333940'>being</span> <span m='334510'>necessary</span> <span m='335080'>for</span>
  <span m='335650'>correct</span> <span m='336220'>operation.</span> </p><p><span
  m='336790'>Next</span> <span m='337189'>we'll</span> <span m='337588'>see</span>
  <span m='337987'>how</span> <span m='338386'>to</span> <span m='338785'>implement</span>
  <span m='339184'>the</span> <span m='339583'>other</span> <span m='339982'>precedence</span>
  <span m='340381'>constraint.</span> </p><p><span m='340780'>What</span> <span m='341185'>keeps</span>
  <span m='341591'>the</span> <span m='341997'>producer</span> <span m='342402'>from</span>
  <span m='342808'>putting</span> <span m='343214'>more</span> <span m='343620'>than</span>
  <span m='344025'>N</span> <span m='344431'>characters</span> <span m='344837'>into</span>
  <span m='345242'>the</span> <span m='345648'>N-character</span> <span m='346054'>buffer?</span>
  </p><p><span m='346460'>Nothing.</span> </p><p><span m='347620'>Oops,</span> <span
  m='348022'>the</span> <span m='348424'>producer</span> <span m='348826'>can</span>
  <span m='349228'>start</span> <span m='349630'>to</span> <span m='350032'>overwrite</span>
  <span m='350435'>characters</span> <span m='350837'>placed</span> <span m='351239'>in</span>
  <span m='351641'>the</span> <span m='352043'>buffer</span> <span m='352445'>earlier</span>
  <span m='352847'>even</span> <span m='353250'>though</span> <span m='353616'>they</span>
  <span m='353983'>haven't</span> <span m='354350'>yet</span> <span m='354716'>been</span>
  <span m='355083'>read</span> <span m='355450'>by</span> <span m='355816'>the</span>
  <span m='356183'>consumer.</span> </p><p><span m='356550'>This</span> <span m='356870'>is</span>
  <span m='357190'>called</span> <span m='357510'>buffer</span> <span m='357830'>overflow</span>
  <span m='358150'>and</span> <span m='358470'>the</span> <span m='358790'>sequence</span>
  <span m='359110'>of</span> <span m='359430'>characters</span> <span m='359750'>transmitted</span>
  <span m='360070'>from</span> <span m='360390'>producer</span> <span m='360710'>to</span>
  <span m='361030'>consumer</span> <span m='361987'>becomes</span> <span m='362945'>hopelessly</span>
  <span m='363902'>corrupted.</span> </p><p><span m='364860'>What</span> <span m='365127'>we've</span>
  <span m='365394'>guaranteed</span> <span m='365661'>so</span> <span m='365928'>far</span>
  <span m='366195'>is</span> <span m='366462'>that</span> <span m='366729'>the</span>
  <span m='366996'>consumer</span> <span m='367263'>can</span> <span m='367530'>read</span>
  <span m='367797'>a</span> <span m='368064'>character</span> <span m='368331'>only</span>
  <span m='368598'>after</span> <span m='368865'>the</span> <span m='369132'>producer</span>
  <span m='369400'>has</span> <span m='369790'>placed</span> <span m='370180'>it</span>
  <span m='370570'>in</span> <span m='370960'>the</span> <span m='371350'>buffer,</span>
  <span m='371740'>i.e.,</span> <span m='372130'>the</span> <span m='372520'>consumer</span>
  <span m='372910'>can't</span> <span m='373300'>read</span> <span m='373690'>from</span>
  <span m='374080'>an</span> <span m='374470'>empty</span> <span m='374860'>buffer.</span>
  </p><p><span m='375250'>What</span> <span m='375557'>we</span> <span m='375864'>still</span>
  <span m='376171'>need</span> <span m='376478'>to</span> <span m='376786'>guarantee</span>
  <span m='377093'>is</span> <span m='377400'>that</span> <span m='377707'>the</span>
  <span m='378015'>producer</span> <span m='378322'>can't</span> <span m='378629'>get</span>
  <span m='378936'>too</span> <span m='379243'>far</span> <span m='379551'>ahead</span>
  <span m='379858'>of</span> <span m='380165'>the</span> <span m='380472'>consumer.</span>
  </p><p><span m='380780'>Since</span> <span m='381179'>the</span> <span m='381578'>buffer</span>
  <span m='381978'>holds</span> <span m='382377'>at</span> <span m='382776'>most</span>
  <span m='383176'>N</span> <span m='383575'>characters,</span> <span m='383974'>the</span>
  <span m='384374'>producer</span> <span m='384773'>can't</span> <span m='385172'>send</span>
  <span m='385572'>the</span> <span m='385971'>(i+N)th</span> <span m='386370'>character</span>
  <span m='386770'>until</span> <span m='387332'>the</span> <span m='387895'>consumer</span>
  <span m='388457'>has</span> <span m='389020'>read</span> <span m='389582'>the</span>
  <span m='390145'>i_th</span> <span m='390707'>character.</span> </p><p><span m='391270'>Here</span>
  <span m='391635'>we've</span> <span m='392000'>added</span> <span m='392365'>a</span>
  <span m='392730'>second</span> <span m='393095'>semaphore,</span> <span m='393460'>SPACES,</span>
  <span m='393825'>to</span> <span m='394190'>manage</span> <span m='394555'>the</span>
  <span m='394920'>number</span> <span m='395285'>of</span> <span m='395650'>spaces</span>
  <span m='396015'>in</span> <span m='396380'>the</span> <span m='396745'>buffer.</span>
  </p><p><span m='397110'>Initially</span> <span m='397439'>the</span> <span m='397768'>buffer</span>
  <span m='398097'>is</span> <span m='398426'>empty,</span> <span m='398755'>so</span>
  <span m='399084'>it</span> <span m='399413'>has</span> <span m='399742'>N</span>
  <span m='400071'>spaces.</span> </p><p><span m='400400'>The</span> <span m='400727'>producer</span>
  <span m='401054'>must</span> <span m='401381'>WAIT</span> <span m='401708'>for</span>
  <span m='402035'>a</span> <span m='402362'>space</span> <span m='402689'>to</span>
  <span m='403016'>be</span> <span m='403343'>available.</span> </p><p><span m='403670'>When</span>
  <span m='404064'>SPACES</span> <span m='404459'>in</span> <span m='404853'>non-zero,</span>
  <span m='405248'>the</span> <span m='405643'>WAIT</span> <span m='406037'>succeeds,</span>
  <span m='406432'>decrementing</span> <span m='406826'>the</span> <span m='407221'>number</span>
  <span m='407616'>of</span> <span m='408010'>available</span> <span m='408405'>spaces</span>
  <span m='408800'>by</span> <span m='409233'>one</span> <span m='409667'>and</span>
  <span m='410101'>then</span> <span m='410535'>the</span> <span m='410969'>producer</span>
  <span m='411403'>fills</span> <span m='411836'>that</span> <span m='412270'>space</span>
  <span m='412704'>with</span> <span m='413138'>the</span> <span m='413572'>next</span>
  <span m='414006'>character.</span> </p><p><span m='414440'>The</span> <span m='414725'>consumer</span>
  <span m='415010'>signals</span> <span m='415296'>the</span> <span m='415581'>availability</span>
  <span m='415866'>of</span> <span m='416152'>another</span> <span m='416437'>space</span>
  <span m='416722'>after</span> <span m='417008'>it</span> <span m='417293'>reads</span>
  <span m='417578'>a</span> <span m='417864'>character</span> <span m='418149'>from</span>
  <span m='418434'>the</span> <span m='418720'>buffer.</span> </p><p><span m='420230'>There's</span>
  <span m='420598'>a</span> <span m='420966'>nice</span> <span m='421334'>symmetry</span>
  <span m='421702'>here.</span> </p><p><span m='422070'>The</span> <span m='422677'>producer</span>
  <span m='423284'>consumes</span> <span m='423891'>spaces</span> <span m='424498'>and</span>
  <span m='425105'>produces</span> <span m='425712'>characters.</span> </p><p><span
  m='426320'>The</span> <span m='427045'>consumer</span> <span m='427771'>consumes</span>
  <span m='428497'>characters</span> <span m='429222'>and</span> <span m='429948'>produces</span>
  <span m='430674'>spaces.</span> </p><p><span m='431400'>Semaphores</span> <span
  m='431826'>are</span> <span m='432252'>used</span> <span m='432679'>to</span> <span
  m='433105'>track</span> <span m='433532'>the</span> <span m='433958'>availability</span>
  <span m='434385'>of</span> <span m='434811'>both</span> <span m='435237'>resources</span>
  <span m='435664'>(i.e.,</span> <span m='436090'>characters</span> <span m='436517'>and</span>
  <span m='436943'>spaces),</span> <span m='437370'>synchronizing</span> <span m='437780'>the</span>
  <span m='438190'>execution</span> <span m='438600'>of</span> <span m='439010'>the</span>
  <span m='439420'>producer</span> <span m='439830'>and</span> <span m='440240'>consumer.</span>
  </p><p><span m='440650'>This</span> <span m='441004'>works</span> <span m='441358'>great</span>
  <span m='441712'>when</span> <span m='442066'>there</span> <span m='442420'>is</span>
  <span m='442774'>a</span> <span m='443128'>single</span> <span m='443482'>producer</span>
  <span m='443836'>process</span> <span m='444190'>and</span> <span m='444544'>a</span>
  <span m='444898'>single</span> <span m='445252'>consumer</span> <span m='445606'>process.</span>
  </p><p><span m='445960'>Next</span> <span m='446264'>we'll</span> <span m='446569'>think</span>
  <span m='446874'>about</span> <span m='447178'>what</span> <span m='447483'>will</span>
  <span m='447788'>happen</span> <span m='448092'>if</span> <span m='448397'>we</span>
  <span m='448702'>have</span> <span m='449006'>multiple</span> <span m='449311'>producers</span>
  <span m='449616'>and</span> <span m='449920'>multiple</span> <span m='450225'>consumers.</span>
  </p>
type: course
uid: 97d0ffb4e1940932c7b31dd6beaac394

---
None