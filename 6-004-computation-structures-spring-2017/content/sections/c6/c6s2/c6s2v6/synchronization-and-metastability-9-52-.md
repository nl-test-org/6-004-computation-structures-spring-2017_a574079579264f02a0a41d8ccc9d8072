---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: ZPpuDMk9BOU
  parent_uid: 9f41afa6ab3ae04b2255a039a6f01a3b
  title: Video-YouTube-Stream
  type: Video
  uid: d952687b4c74f6c8b06c6fd10c3966e7
- id: 3Play-3Play YouTube id-Stream
  media_location: ZPpuDMk9BOU
  parent_uid: 9f41afa6ab3ae04b2255a039a6f01a3b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: cbdb1ce8c58c188508685447ce181e25
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/ZPpuDMk9BOU/default.jpg
  parent_uid: 9f41afa6ab3ae04b2255a039a6f01a3b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: a1f9d6e88b65f60094dd4b2616b9af8c
- id: ZPpuDMk9BOU.srt
  parent_uid: 9f41afa6ab3ae04b2255a039a6f01a3b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v6/synchronization-and-metastability-9-52-/ZPpuDMk9BOU.srt
  title: 3play caption file
  type: null
  uid: 78abcebe5c234ba83b73f482784b13c2
- id: ZPpuDMk9BOU.pdf
  parent_uid: 9f41afa6ab3ae04b2255a039a6f01a3b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v6/synchronization-and-metastability-9-52-/ZPpuDMk9BOU.pdf
  title: 3play pdf file
  type: null
  uid: 38298e68f47dd015b36bfd5e40ffbabf
- id: Caption-3Play YouTube id-SRT
  parent_uid: 9f41afa6ab3ae04b2255a039a6f01a3b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 5e80f84942058b0edf85d8f2fd095f51
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 9f41afa6ab3ae04b2255a039a6f01a3b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: ef5192c406bec3789780b4fe1064bfaf
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_06-02-06_300k.mp4
  parent_uid: 9f41afa6ab3ae04b2255a039a6f01a3b
  title: Video-Internet Archive-MP4
  type: Video
  uid: c50324017c989f275e9c5ffc47df89ad
inline_embed_id: 95500070synchronizationandmetastability95213284581
layout: video
order_index: null
parent_uid: 8cd0fe8decaedc0ad2d63cae1581f555
related_resources_text: ''
short_url: synchronization-and-metastability-9-52-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v6/synchronization-and-metastability-9-52-
template_type: Embed
title: Synchronization and Metastability (9:52)
transcript: <p><span m='1050'>Okay,</span> <span m='1430'>it's</span> <span m='1810'>finally</span>
  <span m='2190'>time</span> <span m='2570'>to</span> <span m='2950'>investigate</span>
  <span m='3330'>issues</span> <span m='3710'>caused</span> <span m='4090'>by</span>
  <span m='4470'>asynchronous</span> <span m='4850'>inputs</span> <span m='5230'>to</span>
  <span m='5610'>a</span> <span m='5990'>sequential</span> <span m='6370'>logic</span>
  <span m='7270'>circuit.</span> </p><p><span m='8170'>By</span> <span m='8481'>"asynchronous"</span>
  <span m='8792'>we</span> <span m='9104'>mean</span> <span m='9415'>that</span> <span
  m='9727'>the</span> <span m='10038'>timing</span> <span m='10350'>of</span> <span
  m='10661'>transitions</span> <span m='10972'>on</span> <span m='11284'>the</span>
  <span m='11595'>input</span> <span m='11907'>is</span> <span m='12218'>completely</span>
  <span m='12530'>independent</span> <span m='12925'>of</span> <span m='13321'>the</span>
  <span m='13716'>timing</span> <span m='14112'>of</span> <span m='14507'>the</span>
  <span m='14903'>sequential</span> <span m='15298'>logic</span> <span m='15694'>clock.</span>
  </p><p><span m='16090'>This</span> <span m='16401'>situation</span> <span m='16712'>arises</span>
  <span m='17023'>when</span> <span m='17335'>the</span> <span m='17646'>inputs</span>
  <span m='17957'>arrive</span> <span m='18268'>from</span> <span m='18580'>the</span>
  <span m='18891'>outside</span> <span m='19202'>world</span> <span m='19513'>where</span>
  <span m='19825'>the</span> <span m='20136'>timing</span> <span m='20447'>of</span>
  <span m='20759'>events</span> <span m='21305'>is</span> <span m='21852'>not</span>
  <span m='22399'>under</span> <span m='22945'>our</span> <span m='23492'>control.</span>
  </p><p><span m='24039'>As</span> <span m='24354'>we</span> <span m='24669'>saw</span>
  <span m='24984'>at</span> <span m='25300'>the</span> <span m='25615'>end</span>
  <span m='25930'>of</span> <span m='26246'>Chapter</span> <span m='26561'>5,</span>
  <span m='26876'>to</span> <span m='27191'>ensure</span> <span m='27507'>reliable</span>
  <span m='27822'>operation</span> <span m='28137'>of</span> <span m='28453'>the</span>
  <span m='28768'>state</span> <span m='29083'>registers</span> <span m='29399'>inputs</span>
  <span m='29775'>to</span> <span m='30151'>a</span> <span m='30527'>sequential</span>
  <span m='30903'>logic</span> <span m='31279'>system</span> <span m='31655'>have</span>
  <span m='32031'>to</span> <span m='32407'>obey</span> <span m='32783'>setup</span>
  <span m='33159'>and</span> <span m='33535'>hold</span> <span m='33911'>time</span>
  <span m='34287'>constraints</span> <span m='34663'>relative</span> <span m='35039'>to</span>
  <span m='35387'>the</span> <span m='35736'>rising</span> <span m='36085'>edge</span>
  <span m='36434'>of</span> <span m='36782'>the</span> <span m='37131'>system</span>
  <span m='37480'>clock.</span> </p><p><span m='37829'>Clearly</span> <span m='38094'>if</span>
  <span m='38359'>the</span> <span m='38625'>input</span> <span m='38890'>can</span>
  <span m='39155'>change</span> <span m='39421'>at</span> <span m='39686'>anytime,</span>
  <span m='39951'>it</span> <span m='40217'>can</span> <span m='40482'>change</span>
  <span m='40747'>at</span> <span m='41013'>time</span> <span m='41278'>that</span>
  <span m='41543'>would</span> <span m='41809'>violate</span> <span m='42074'>the</span>
  <span m='42340'>setup</span> <span m='42770'>and</span> <span m='43200'>hold</span>
  <span m='43630'>times.</span> </p><p><span m='44060'>Maybe</span> <span m='44458'>we</span>
  <span m='44857'>can</span> <span m='45255'>come</span> <span m='45654'>up</span>
  <span m='46053'>with</span> <span m='46451'>a</span> <span m='46850'>synchronizer</span>
  <span m='47248'>circuit</span> <span m='47647'>that</span> <span m='48046'>takes</span>
  <span m='48444'>an</span> <span m='48843'>unsynchronized</span> <span m='49241'>input</span>
  <span m='49640'>signal</span> <span m='50039'>and</span> <span m='50356'>produces</span>
  <span m='50673'>a</span> <span m='50991'>synchronized</span> <span m='51308'>signal</span>
  <span m='51626'>that</span> <span m='51943'>only</span> <span m='52260'>changes</span>
  <span m='52578'>shortly</span> <span m='52895'>after</span> <span m='53213'>the</span>
  <span m='53530'>rising</span> <span m='53847'>edge</span> <span m='54165'>of</span>
  <span m='54482'>the</span> <span m='54800'>clock.</span> </p><p><span m='56399'>We'd</span>
  <span m='56789'>use</span> <span m='57180'>a</span> <span m='57571'>synchronizer</span>
  <span m='57961'>on</span> <span m='58352'>each</span> <span m='58743'>asynchronous</span>
  <span m='59134'>input</span> <span m='59524'>and</span> <span m='59915'>solve</span>
  <span m='60306'>our</span> <span m='60697'>timing</span> <span m='61087'>problems</span>
  <span m='61478'>that</span> <span m='61869'>way.</span> </p><p><span m='62260'>Here's</span>
  <span m='62764'>a</span> <span m='63268'>detailed</span> <span m='63772'>specification</span>
  <span m='64277'>for</span> <span m='64781'>our</span> <span m='65285'>synchronizer.</span>
  </p><p><span m='65790'>The</span> <span m='66220'>synchronizer</span> <span m='66651'>has</span>
  <span m='67081'>two</span> <span m='67512'>inputs,</span> <span m='67943'>IN</span>
  <span m='68373'>and</span> <span m='68804'>CLK,</span> <span m='69235'>which</span>
  <span m='69665'>have</span> <span m='70096'>transitions</span> <span m='70526'>at</span>
  <span m='70957'>time</span> <span m='71388'>t_IN</span> <span m='71818'>and</span>
  <span m='72249'>t_C</span> <span m='72680'>respectively.</span> </p><p><span m='74230'>If</span>
  <span m='74620'>IN's</span> <span m='75011'>transition</span> <span m='75402'>happens</span>
  <span m='75793'>sufficiently</span> <span m='76183'>before</span> <span m='76574'>C's</span>
  <span m='76965'>transition,</span> <span m='77356'>we</span> <span m='77746'>want</span>
  <span m='78137'>the</span> <span m='78528'>synchronizer</span> <span m='78919'>to</span>
  <span m='79310'>output</span> <span m='79847'>a</span> <span m='80384'>1</span>
  <span m='80921'>within</span> <span m='81459'>some</span> <span m='81996'>bounded</span>
  <span m='82533'>time</span> <span m='83070'>t_D</span> <span m='83608'>after</span>
  <span m='84145'>CLK's</span> <span m='84682'>transition.</span> </p><p><span m='85220'>And</span>
  <span m='85589'>if</span> <span m='85958'>CLK's</span> <span m='86327'>transition</span>
  <span m='86696'>happens</span> <span m='87066'>sufficient</span> <span m='87435'>before</span>
  <span m='87804'>IN's</span> <span m='88173'>transition,</span> <span m='88543'>we</span>
  <span m='88912'>want</span> <span m='89281'>the</span> <span m='89650'>synchronizer</span>
  <span m='90020'>to</span> <span m='90487'>output</span> <span m='90954'>a</span>
  <span m='91421'>0</span> <span m='91888'>within</span> <span m='92355'>time</span>
  <span m='92822'>t_D</span> <span m='93289'>after</span> <span m='93756'>CLK's</span>
  <span m='94223'>transition.</span> </p><p><span m='94690'>Finally,</span> <span
  m='95193'>if</span> <span m='95697'>the</span> <span m='96201'>two</span> <span
  m='96705'>transitions</span> <span m='97209'>are</span> <span m='97713'>closer</span>
  <span m='98216'>together</span> <span m='98720'>than</span> <span m='99224'>some</span>
  <span m='99728'>specified</span> <span m='100232'>interval</span> <span m='100736'>t_E,</span>
  <span m='101240'>the</span> <span m='101649'>synchronizer</span> <span m='102058'>can</span>
  <span m='102467'>output</span> <span m='102877'>either</span> <span m='103286'>a</span>
  <span m='103695'>0</span> <span m='104105'>or</span> <span m='104514'>a</span> <span
  m='104923'>1</span> <span m='105333'>within</span> <span m='105742'>time</span>
  <span m='106151'>t_D</span> <span m='106561'>of</span> <span m='106970'>CLK's</span>
  <span m='107379'>transition.</span> </p><p><span m='107789'>Either</span> <span
  m='108201'>answer</span> <span m='108613'>is</span> <span m='109025'>fine</span>
  <span m='109437'>so</span> <span m='109849'>long</span> <span m='110261'>as</span>
  <span m='110674'>it's</span> <span m='111086'>a</span> <span m='111498'>stable</span>
  <span m='111910'>digital</span> <span m='112322'>0</span> <span m='112734'>or</span>
  <span m='113147'>digital</span> <span m='113559'>1</span> <span m='113971'>by</span>
  <span m='114383'>the</span> <span m='114795'>specified</span> <span m='115207'>deadline.</span>
  </p><p><span m='115620'>This</span> <span m='115990'>turns</span> <span m='116360'>out</span>
  <span m='116730'>to</span> <span m='117100'>be</span> <span m='117470'>an</span>
  <span m='117840'>unsolvable</span> <span m='118210'>problem!</span> </p><p><span
  m='118580'>For</span> <span m='118959'>no</span> <span m='119338'>finite</span>
  <span m='119718'>values</span> <span m='120097'>of</span> <span m='120476'>t_E</span>
  <span m='120856'>and</span> <span m='121235'>t_D</span> <span m='121615'>can</span>
  <span m='121994'>we</span> <span m='122373'>build</span> <span m='122753'>a</span>
  <span m='123132'>synchronizer</span> <span m='123511'>that's</span> <span m='123891'>guaranteed</span>
  <span m='124270'>to</span> <span m='124650'>meet</span> <span m='125239'>this</span>
  <span m='125828'>specification</span> <span m='126417'>even</span> <span m='127006'>when</span>
  <span m='127595'>using</span> <span m='128184'>components</span> <span m='128773'>that</span>
  <span m='129362'>are</span> <span m='129951'>100%</span> <span m='130540'>reliable.</span>
  </p><p><span m='131130'>But</span> <span m='131408'>can't</span> <span m='131686'>we</span>
  <span m='131965'>just</span> <span m='132243'>use</span> <span m='132521'>a</span>
  <span m='132800'>D</span> <span m='133078'>register</span> <span m='133356'>to</span>
  <span m='133635'>solve</span> <span m='133913'>the</span> <span m='134191'>problem?</span>
  </p><p><span m='134470'>We'll</span> <span m='134860'>connect</span> <span m='135251'>IN</span>
  <span m='135641'>to</span> <span m='136032'>the</span> <span m='136423'>register's</span>
  <span m='136813'>data</span> <span m='137204'>input</span> <span m='137595'>and</span>
  <span m='137985'>connect</span> <span m='138376'>CLK</span> <span m='138766'>to</span>
  <span m='139157'>the</span> <span m='139548'>register's</span> <span m='139938'>clock</span>
  <span m='140329'>input.</span> </p><p><span m='140720'>We'll</span> <span m='141045'>set</span>
  <span m='141370'>the</span> <span m='141695'>decision</span> <span m='142021'>time</span>
  <span m='142346'>t_D</span> <span m='142671'>to</span> <span m='142997'>the</span>
  <span m='143322'>propagation</span> <span m='143647'>delay</span> <span m='143972'>of</span>
  <span m='144298'>the</span> <span m='144623'>register</span> <span m='144948'>and</span>
  <span m='145274'>the</span> <span m='145599'>allowable</span> <span m='145924'>error</span>
  <span m='146250'>interval</span> <span m='146765'>to</span> <span m='147280'>the</span>
  <span m='147796'>larger</span> <span m='148311'>of</span> <span m='148827'>the</span>
  <span m='149342'>register's</span> <span m='149858'>setup</span> <span m='150373'>and</span>
  <span m='150889'>hold</span> <span m='151404'>times.</span> </p><p><span m='151920'>Our</span>
  <span m='152213'>theory</span> <span m='152507'>is</span> <span m='152800'>that</span>
  <span m='153094'>if</span> <span m='153387'>the</span> <span m='153681'>rising</span>
  <span m='153974'>edge</span> <span m='154268'>of</span> <span m='154561'>IN</span>
  <span m='154855'>occurs</span> <span m='155148'>at</span> <span m='155442'>least</span>
  <span m='155735'>t_SETUP</span> <span m='156029'>before</span> <span m='156322'>the</span>
  <span m='156616'>rising</span> <span m='156910'>edge</span> <span m='157381'>of</span>
  <span m='157853'>CLK,</span> <span m='158325'>the</span> <span m='158797'>register</span>
  <span m='159269'>is</span> <span m='159740'>guaranteed</span> <span m='160212'>to</span>
  <span m='160684'>output</span> <span m='161156'>a</span> <span m='161628'>1.</span>
  </p><p><span m='162100'>And</span> <span m='162442'>if</span> <span m='162784'>IN</span>
  <span m='163127'>transitions</span> <span m='163469'>more</span> <span m='163811'>than</span>
  <span m='164154'>t_HOLD</span> <span m='164496'>after</span> <span m='164838'>the</span>
  <span m='165181'>rising</span> <span m='165523'>edge</span> <span m='165865'>of</span>
  <span m='166208'>CLK,</span> <span m='166550'>the</span> <span m='166892'>register</span>
  <span m='167235'>is</span> <span m='167577'>guaranteed</span> <span m='167920'>to</span>
  <span m='168227'>output</span> <span m='168535'>a</span> <span m='168842'>0.</span>
  </p><p><span m='169150'>So</span> <span m='169797'>far,</span> <span m='170445'>so</span>
  <span m='171092'>good.</span> </p><p><span m='171740'>If</span> <span m='172051'>IN</span>
  <span m='172363'>transitions</span> <span m='172675'>during</span> <span m='172987'>the</span>
  <span m='173298'>setup</span> <span m='173610'>and</span> <span m='173922'>hold</span>
  <span m='174234'>times</span> <span m='174545'>with</span> <span m='174857'>respect</span>
  <span m='175169'>to</span> <span m='175481'>the</span> <span m='175792'>rising</span>
  <span m='176104'>edge</span> <span m='176416'>on</span> <span m='176728'>CLK,</span>
  <span m='177040'>we</span> <span m='177347'>know</span> <span m='177654'>we've</span>
  <span m='177962'>violated</span> <span m='178269'>the</span> <span m='178576'>dynamic</span>
  <span m='178884'>discipline</span> <span m='179191'>and</span> <span m='179498'>we</span>
  <span m='179806'>can't</span> <span m='180113'>tell</span> <span m='180420'>whether</span>
  <span m='180728'>the</span> <span m='181035'>register</span> <span m='181342'>will</span>
  <span m='181650'>store</span> <span m='182100'>a</span> <span m='182550'>0</span>
  <span m='183000'>or</span> <span m='183450'>a</span> <span m='183900'>1.</span>
  </p><p><span m='184350'>But</span> <span m='184716'>in</span> <span m='185083'>this</span>
  <span m='185450'>case,</span> <span m='185817'>our</span> <span m='186184'>specification</span>
  <span m='186551'>lets</span> <span m='186918'>us</span> <span m='187285'>produce</span>
  <span m='187651'>either</span> <span m='188018'>answer,</span> <span m='188385'>so</span>
  <span m='188752'>we're</span> <span m='189119'>good</span> <span m='189486'>to</span>
  <span m='189853'>go,</span> <span m='190220'>right?</span> </p><p><span m='191220'>Sadly,</span>
  <span m='191666'>we're</span> <span m='192113'>not</span> <span m='192560'>good</span>
  <span m='193006'>to</span> <span m='193453'>go.</span> </p><p><span m='193900'>We're</span>
  <span m='194244'>lured</span> <span m='194588'>by</span> <span m='194932'>the</span>
  <span m='195276'>digital</span> <span m='195620'>abstraction</span> <span m='195964'>into</span>
  <span m='196308'>assuming</span> <span m='196652'>that</span> <span m='196996'>even</span>
  <span m='197340'>if</span> <span m='197684'>we</span> <span m='198028'>violate</span>
  <span m='198372'>the</span> <span m='198716'>dynamic</span> <span m='199060'>discipline</span>
  <span m='199467'>that</span> <span m='199875'>Q</span> <span m='200283'>must</span>
  <span m='200690'>be</span> <span m='201098'>either</span> <span m='201506'>1</span>
  <span m='201913'>or</span> <span m='202321'>0</span> <span m='202729'>after</span>
  <span m='203136'>the</span> <span m='203544'>propagation</span> <span m='203952'>delay.</span>
  </p><p><span m='204360'>But</span> <span m='204659'>that</span> <span m='204959'>isn't</span>
  <span m='205259'>a</span> <span m='205559'>valid</span> <span m='205859'>assumption</span>
  <span m='206159'>as</span> <span m='206459'>we'll</span> <span m='206759'>see</span>
  <span m='207059'>when</span> <span m='207359'>we</span> <span m='207659'>look</span>
  <span m='207959'>more</span> <span m='208259'>carefully</span> <span m='208559'>at</span>
  <span m='208859'>the</span> <span m='209159'>operation</span> <span m='209459'>of</span>
  <span m='209850'>the</span> <span m='210241'>register's</span> <span m='210633'>master</span>
  <span m='211024'>latch</span> <span m='211415'>when</span> <span m='211807'>B</span>
  <span m='212198'>and</span> <span m='212589'>C</span> <span m='212981'>change</span>
  <span m='213372'>at</span> <span m='213763'>about</span> <span m='214155'>the</span>
  <span m='214546'>same</span> <span m='214937'>time.</span> </p><p><span m='215329'>Recall</span>
  <span m='215586'>that</span> <span m='215844'>the</span> <span m='216102'>master</span>
  <span m='216359'>latch</span> <span m='216617'>is</span> <span m='216875'>really</span>
  <span m='217132'>just</span> <span m='217390'>a</span> <span m='217648'>lenient</span>
  <span m='217906'>MUX</span> <span m='218163'>that</span> <span m='218421'>can</span>
  <span m='218679'>be</span> <span m='218936'>configured</span> <span m='219194'>as</span>
  <span m='219452'>a</span> <span m='219710'>bi-stable</span> <span m='220287'>storage</span>
  <span m='220864'>element</span> <span m='221442'>using</span> <span m='222019'>a</span>
  <span m='222596'>positive</span> <span m='223174'>feedback</span> <span m='223751'>loop.</span>
  </p><p><span m='224329'>When</span> <span m='224635'>the</span> <span m='224941'>latch</span>
  <span m='225247'>is</span> <span m='225554'>in</span> <span m='225860'>memory</span>
  <span m='226166'>mode,</span> <span m='226473'>it's</span> <span m='226779'>essentially</span>
  <span m='227085'>a</span> <span m='227392'>two-gate</span> <span m='227698'>cyclic</span>
  <span m='228004'>circuit</span> <span m='228311'>whose</span> <span m='228617'>behavior</span>
  <span m='228923'>has</span> <span m='229230'>two</span> <span m='229688'>constraints:</span>
  <span m='230147'>the</span> <span m='230606'>voltage</span> <span m='231065'>transfer</span>
  <span m='231523'>characteristic</span> <span m='231982'>of</span> <span m='232441'>the</span>
  <span m='232900'>two-gate</span> <span m='233255'>circuit,</span> <span m='233611'>shown</span>
  <span m='233966'>in</span> <span m='234322'>green</span> <span m='234678'>on</span>
  <span m='235033'>the</span> <span m='235389'>graph,</span> <span m='235745'>and</span>
  <span m='236100'>that</span> <span m='236456'>V_IN</span> <span m='236811'>=</span>
  <span m='237167'>V_OUT,</span> <span m='237523'>a</span> <span m='237878'>constraint</span>
  <span m='238234'>that's</span> <span m='238590'>shown</span> <span m='239020'>in</span>
  <span m='239450'>red</span> <span m='239880'>on</span> <span m='240310'>the</span>
  <span m='240740'>graph.</span> </p><p><span m='241170'>These</span> <span m='241645'>two</span>
  <span m='242121'>curves</span> <span m='242597'>intersect</span> <span m='243072'>at</span>
  <span m='243548'>three</span> <span m='244024'>points.</span> </p><p><span m='244500'>Our</span>
  <span m='244897'>concern</span> <span m='245295'>is</span> <span m='245692'>the</span>
  <span m='246090'>middle</span> <span m='246487'>point</span> <span m='246885'>of</span>
  <span m='247282'>intersection.</span> </p><p><span m='247680'>If</span> <span m='247961'>IN</span>
  <span m='248243'>and</span> <span m='248524'>CLK</span> <span m='248806'>change</span>
  <span m='249087'>at</span> <span m='249369'>the</span> <span m='249650'>same</span>
  <span m='249932'>time,</span> <span m='250213'>the</span> <span m='250495'>voltage</span>
  <span m='250776'>on</span> <span m='251058'>Q</span> <span m='251339'>may</span>
  <span m='251621'>be</span> <span m='251902'>in</span> <span m='252184'>transition</span>
  <span m='252465'>at</span> <span m='252747'>the</span> <span m='253028'>time</span>
  <span m='253310'>the</span> <span m='253790'>MUX</span> <span m='254270'>closes</span>
  <span m='254750'>and</span> <span m='255230'>enables</span> <span m='255710'>the</span>
  <span m='256190'>positive</span> <span m='256670'>feedback</span> <span m='257150'>loop.</span>
  </p><p><span m='257630'>So</span> <span m='257896'>the</span> <span m='258162'>initial</span>
  <span m='258428'>voltage</span> <span m='258694'>in</span> <span m='258960'>the</span>
  <span m='259226'>feedback</span> <span m='259492'>loop</span> <span m='259758'>may</span>
  <span m='260024'>happen</span> <span m='260290'>to</span> <span m='260556'>be</span>
  <span m='260822'>at</span> <span m='261088'>or</span> <span m='261354'>very</span>
  <span m='261620'>near</span> <span m='261886'>the</span> <span m='262152'>voltage</span>
  <span m='262419'>of</span> <span m='263053'>the</span> <span m='263687'>middle</span>
  <span m='264321'>intersection</span> <span m='264955'>point.</span> </p><p><span
  m='265590'>When</span> <span m='265928'>Q</span> <span m='266266'>is</span> <span
  m='266604'>at</span> <span m='266942'>the</span> <span m='267280'>metastable</span>
  <span m='267618'>voltage,</span> <span m='267956'>the</span> <span m='268294'>storage</span>
  <span m='268632'>loop</span> <span m='268970'>is</span> <span m='269308'>in</span>
  <span m='269646'>an</span> <span m='269984'>unstable</span> <span m='270322'>equilibrium</span>
  <span m='270660'>called</span> <span m='270999'>the</span> <span m='271612'>metastable</span>
  <span m='272226'>state.</span> </p><p><span m='272840'>In</span> <span m='273124'>theory</span>
  <span m='273409'>the</span> <span m='273694'>system</span> <span m='273978'>could</span>
  <span m='274263'>balance</span> <span m='274548'>at</span> <span m='274832'>this</span>
  <span m='275117'>point</span> <span m='275402'>forever,</span> <span m='275687'>but</span>
  <span m='275971'>a</span> <span m='276256'>small</span> <span m='276541'>change</span>
  <span m='276825'>in</span> <span m='277110'>the</span> <span m='277395'>voltages</span>
  <span m='277680'>in</span> <span m='277971'>the</span> <span m='278262'>loop</span>
  <span m='278553'>will</span> <span m='278845'>move</span> <span m='279136'>the</span>
  <span m='279427'>system</span> <span m='279718'>away</span> <span m='280010'>from</span>
  <span m='280301'>the</span> <span m='280592'>metastable</span> <span m='280883'>equilibrium</span>
  <span m='281175'>point</span> <span m='281466'>and</span> <span m='281757'>set</span>
  <span m='282048'>it</span> <span m='282340'>irrevocably</span> <span m='282829'>in</span>
  <span m='283319'>motion</span> <span m='283809'>towards</span> <span m='284299'>the</span>
  <span m='284789'>stable</span> <span m='285279'>equilibrium</span> <span m='285769'>points.</span>
  </p><p><span m='286259'>Here's</span> <span m='286521'>the</span> <span m='286784'>issue</span>
  <span m='287047'>we</span> <span m='287310'>face:</span> <span m='287573'>we</span>
  <span m='287836'>can't</span> <span m='288098'>bound</span> <span m='288361'>the</span>
  <span m='288624'>amount</span> <span m='288887'>of</span> <span m='289150'>time</span>
  <span m='289413'>the</span> <span m='289675'>system</span> <span m='289938'>will</span>
  <span m='290201'>spend</span> <span m='290464'>in</span> <span m='290727'>the</span>
  <span m='290990'>metastable</span> <span m='291979'>state.</span> </p><p><span m='292969'>Here's</span>
  <span m='293301'>what</span> <span m='293634'>we</span> <span m='293966'>know</span>
  <span m='294299'>about</span> <span m='294631'>the</span> <span m='294964'>metastable</span>
  <span m='295296'>state.</span> </p><p><span m='295629'>It's</span> <span m='296033'>in</span>
  <span m='296438'>the</span> <span m='296842'>forbidden</span> <span m='297247'>zone</span>
  <span m='297652'>of</span> <span m='298056'>the</span> <span m='298461'>digital</span>
  <span m='298865'>signaling</span> <span m='299270'>specifications</span> <span m='299675'>and</span>
  <span m='300079'>so</span> <span m='300484'>corresponds</span> <span m='300889'>to</span>
  <span m='301495'>an</span> <span m='302101'>invalid</span> <span m='302707'>logic</span>
  <span m='303313'>level.</span> </p><p><span m='303919'>Violating</span> <span m='304211'>the</span>
  <span m='304504'>dynamic</span> <span m='304797'>discipline</span> <span m='305090'>means</span>
  <span m='305383'>that</span> <span m='305676'>our</span> <span m='305969'>register</span>
  <span m='306262'>is</span> <span m='306555'>no</span> <span m='306848'>longer</span>
  <span m='307141'>guaranteed</span> <span m='307434'>to</span> <span m='307727'>produce</span>
  <span m='308020'>a</span> <span m='308451'>digital</span> <span m='308883'>output</span>
  <span m='309315'>in</span> <span m='309746'>bounded</span> <span m='310178'>time.</span>
  </p><p><span m='310610'>A</span> <span m='311027'>persistent</span> <span m='311444'>invalid</span>
  <span m='311862'>logic</span> <span m='312279'>level</span> <span m='312696'>can</span>
  <span m='313114'>wreak</span> <span m='313531'>both</span> <span m='313948'>logical</span>
  <span m='314366'>and</span> <span m='314783'>electrical</span> <span m='315200'>havoc</span>
  <span m='315618'>in</span> <span m='316035'>our</span> <span m='316452'>sequential</span>
  <span m='316870'>logic</span> <span m='317935'>circuit.</span> </p><p><span m='319000'>Since</span>
  <span m='319460'>combinational</span> <span m='319921'>logic</span> <span m='320382'>gates</span>
  <span m='320843'>with</span> <span m='321303'>invalid</span> <span m='321764'>inputs</span>
  <span m='322225'>have</span> <span m='322686'>unpredictable</span> <span m='323146'>outputs,</span>
  <span m='323607'>an</span> <span m='324068'>invalid</span> <span m='324529'>signal</span>
  <span m='324979'>may</span> <span m='325429'>corrupt</span> <span m='325879'>the</span>
  <span m='326329'>state</span> <span m='326779'>and</span> <span m='327229'>output</span>
  <span m='327679'>values</span> <span m='328129'>in</span> <span m='328579'>our</span>
  <span m='329029'>sequential</span> <span m='329479'>system.</span> </p><p><span
  m='329930'>At</span> <span m='330251'>the</span> <span m='330573'>electrical</span>
  <span m='330895'>level,</span> <span m='331217'>if</span> <span m='331538'>an</span>
  <span m='331860'>input</span> <span m='332182'>to</span> <span m='332504'>a</span>
  <span m='332825'>CMOS</span> <span m='333147'>gate</span> <span m='333469'>is</span>
  <span m='333791'>at</span> <span m='334112'>the</span> <span m='334434'>metastable</span>
  <span m='334756'>voltage,</span> <span m='335078'>both</span> <span m='335400'>PFET</span>
  <span m='335731'>and</span> <span m='336063'>NFET</span> <span m='336395'>switches</span>
  <span m='336727'>controlled</span> <span m='337059'>by</span> <span m='337391'>that</span>
  <span m='337723'>input</span> <span m='338055'>would</span> <span m='338387'>be</span>
  <span m='338719'>conducting,</span> <span m='339051'>so</span> <span m='339383'>we'd</span>
  <span m='339715'>have</span> <span m='340047'>a</span> <span m='340379'>path</span>
  <span m='340932'>between</span> <span m='341486'>V_DD</span> <span m='342040'>and</span>
  <span m='342594'>GROUND,</span> <span m='343148'>causing</span> <span m='343702'>a</span>
  <span m='344256'>spike</span> <span m='344810'>in</span> <span m='345364'>the</span>
  <span m='345918'>system's</span> <span m='346472'>power</span> <span m='347026'>dissipation.</span>
  </p><p><span m='347580'>It's</span> <span m='347881'>an</span> <span m='348182'>unstable</span>
  <span m='348483'>equilibrium</span> <span m='348785'>and</span> <span m='349086'>will</span>
  <span m='349387'>eventually</span> <span m='349688'>be</span> <span m='349990'>resolved</span>
  <span m='350291'>by</span> <span m='350592'>a</span> <span m='350893'>transition</span>
  <span m='351195'>to</span> <span m='351496'>one</span> <span m='351797'>of</span>
  <span m='352098'>the</span> <span m='352400'>two</span> <span m='353097'>stable</span>
  <span m='353795'>equilibrium</span> <span m='354492'>points.</span> </p><p><span
  m='355190'>You</span> <span m='355431'>can</span> <span m='355672'>see</span> <span
  m='355913'>from</span> <span m='356154'>the</span> <span m='356395'>graph</span>
  <span m='356636'>that</span> <span m='356877'>the</span> <span m='357118'>metastable</span>
  <span m='357360'>voltage</span> <span m='357601'>is</span> <span m='357842'>in</span>
  <span m='358083'>the</span> <span m='358324'>high-gain</span> <span m='358565'>region</span>
  <span m='358806'>of</span> <span m='359047'>the</span> <span m='359289'>VTC,</span>
  <span m='359675'>so</span> <span m='360061'>a</span> <span m='360447'>small</span>
  <span m='360833'>change</span> <span m='361219'>in</span> <span m='361606'>V_IN</span>
  <span m='361992'>results</span> <span m='362378'>in</span> <span m='362764'>a</span>
  <span m='363150'>large</span> <span m='363536'>change</span> <span m='363923'>in</span>
  <span m='364309'>V_OUT,</span> <span m='364695'>and</span> <span m='365081'>once</span>
  <span m='365467'>away</span> <span m='365853'>from</span> <span m='366240'>the</span>
  <span m='366542'>metastable</span> <span m='366845'>point</span> <span m='367147'>the</span>
  <span m='367450'>loop</span> <span m='367752'>voltage</span> <span m='368055'>will</span>
  <span m='368357'>move</span> <span m='368660'>towards</span> <span m='368962'>0</span>
  <span m='369265'>or</span> <span m='369567'>V_DD.</span> </p><p><span m='369870'>The</span>
  <span m='370308'>time</span> <span m='370746'>it</span> <span m='371184'>takes</span>
  <span m='371622'>for</span> <span m='372060'>the</span> <span m='372499'>system</span>
  <span m='372937'>to</span> <span m='373375'>evolve</span> <span m='373813'>to</span>
  <span m='374251'>a</span> <span m='374689'>stable</span> <span m='375128'>equilibrium</span>
  <span m='375566'>is</span> <span m='376004'>related</span> <span m='376442'>to</span>
  <span m='376880'>how</span> <span m='377319'>close</span> <span m='377763'>Q's</span>
  <span m='378208'>voltage</span> <span m='378653'>was</span> <span m='379097'>to</span>
  <span m='379542'>the</span> <span m='379987'>metastable</span> <span m='380432'>point</span>
  <span m='380876'>when</span> <span m='381321'>the</span> <span m='381766'>positive</span>
  <span m='382211'>feedback</span> <span m='382655'>loop</span> <span m='383100'>was</span>
  <span m='383545'>enabled.</span> </p><p><span m='383990'>The</span> <span m='384292'>closer</span>
  <span m='384595'>Q's</span> <span m='384898'>initial</span> <span m='385201'>voltage</span>
  <span m='385503'>is</span> <span m='385806'>to</span> <span m='386109'>the</span>
  <span m='386412'>metastable</span> <span m='386715'>voltage,</span> <span m='387017'>the</span>
  <span m='387320'>longer</span> <span m='387623'>it</span> <span m='387926'>will</span>
  <span m='388228'>take</span> <span m='388531'>for</span> <span m='388834'>the</span>
  <span m='389137'>system</span> <span m='389440'>to</span> <span m='390177'>resolve</span>
  <span m='390914'>the</span> <span m='391651'>metastability.</span> </p><p><span
  m='392389'>But</span> <span m='392689'>since</span> <span m='392989'>there's</span>
  <span m='393289'>no</span> <span m='393589'>lower</span> <span m='393889'>bound</span>
  <span m='394189'>on</span> <span m='394489'>how</span> <span m='394789'>close</span>
  <span m='395089'>Q</span> <span m='395389'>is</span> <span m='395689'>to</span>
  <span m='395989'>the</span> <span m='396289'>metastable</span> <span m='396589'>voltage,</span>
  <span m='396889'>there's</span> <span m='397189'>no</span> <span m='397490'>upper</span>
  <span m='397838'>bound</span> <span m='398187'>on</span> <span m='398536'>the</span>
  <span m='398885'>time</span> <span m='399234'>it</span> <span m='399583'>will</span>
  <span m='399932'>take</span> <span m='400281'>for</span> <span m='400630'>resolution.</span>
  </p><p><span m='400979'>In</span> <span m='401384'>other</span> <span m='401789'>words,</span>
  <span m='402194'>if</span> <span m='402599'>you</span> <span m='403004'>specify</span>
  <span m='403409'>a</span> <span m='403814'>bound,</span> <span m='404219'>e.g.,</span>
  <span m='404624'>t_D,</span> <span m='405029'>on</span> <span m='405434'>the</span>
  <span m='405839'>time</span> <span m='406244'>available</span> <span m='406649'>for</span>
  <span m='407054'>resolution,</span> <span m='407460'>there's</span> <span m='407906'>a</span>
  <span m='408352'>range</span> <span m='408799'>of</span> <span m='409245'>initial</span>
  <span m='409692'>Q</span> <span m='410138'>voltages</span> <span m='410585'>that</span>
  <span m='411031'>won't</span> <span m='411477'>be</span> <span m='411924'>resolved</span>
  <span m='412370'>within</span> <span m='412817'>that</span> <span m='413263'>time.</span>
  </p><p><span m='413710'>If</span> <span m='414041'>the</span> <span m='414373'>system</span>
  <span m='414705'>goes</span> <span m='415037'>metastable</span> <span m='415369'>at</span>
  <span m='415701'>some</span> <span m='416033'>point</span> <span m='416365'>in</span>
  <span m='416697'>time,</span> <span m='417029'>then</span> <span m='417361'>there's</span>
  <span m='417693'>a</span> <span m='418025'>non-zero</span> <span m='418357'>probability</span>
  <span m='418689'>that</span> <span m='419034'>the</span> <span m='419380'>system</span>
  <span m='419725'>will</span> <span m='420071'>still</span> <span m='420417'>be</span>
  <span m='420762'>metastable</span> <span m='421108'>after</span> <span m='421454'>some</span>
  <span m='421799'>interval</span> <span m='422145'>T,</span> <span m='422490'>for</span>
  <span m='422836'>any</span> <span m='423182'>finite</span> <span m='423527'>choice</span>
  <span m='423873'>of</span> <span m='424219'>T.</span> <span m='424626'>The</span>
  <span m='425033'>good</span> <span m='425440'>news</span> <span m='425847'>is</span>
  <span m='426254'>that</span> <span m='426661'>the</span> <span m='427068'>probability</span>
  <span m='427475'>of</span> <span m='427882'>being</span> <span m='428289'>metastable</span>
  <span m='428783'>at</span> <span m='429277'>the</span> <span m='429771'>end</span>
  <span m='430265'>of</span> <span m='430759'>the</span> <span m='431254'>interval</span>
  <span m='431748'>decreases</span> <span m='432242'>exponentially</span> <span m='432736'>with</span>
  <span m='433230'>increasing</span> <span m='433724'>T.</span> </p><p><span m='434219'>Note</span>
  <span m='434584'>that</span> <span m='434950'>every</span> <span m='435315'>bistable</span>
  <span m='435681'>system</span> <span m='436046'>has</span> <span m='436412'>at</span>
  <span m='436777'>least</span> <span m='437143'>one</span> <span m='437508'>metastable</span>
  <span m='437874'>state.</span> </p><p><span m='438240'>So</span> <span m='438678'>metastability</span>
  <span m='439117'>is</span> <span m='439555'>the</span> <span m='439994'>price</span>
  <span m='440433'>we</span> <span m='440871'>pay</span> <span m='441310'>for</span>
  <span m='441748'>building</span> <span m='442187'>storage</span> <span m='442626'>elements</span>
  <span m='443064'>from</span> <span m='443503'>positive</span> <span m='443941'>feedback</span>
  <span m='444380'>loops.</span> </p><p><span m='444819'>If</span> <span m='445116'>you'd</span>
  <span m='445413'>like</span> <span m='445711'>to</span> <span m='446008'>read</span>
  <span m='446306'>a</span> <span m='446603'>more</span> <span m='446900'>thorough</span>
  <span m='447198'>discussion</span> <span m='447495'>of</span> <span m='447793'>synchronizers</span>
  <span m='448090'>and</span> <span m='448387'>related</span> <span m='448685'>problems</span>
  <span m='448982'>and</span> <span m='449280'>learn</span> <span m='449652'>about</span>
  <span m='450025'>the</span> <span m='450398'>mathematics</span> <span m='450771'>behind</span>
  <span m='451143'>the</span> <span m='451516'>exponential</span> <span m='451889'>probabilities,</span>
  <span m='452262'>please</span> <span m='452635'>see</span> <span m='453007'>Chapter</span>
  <span m='453380'>10</span> <span m='453753'>of</span> <span m='454126'>the</span>
  <span m='454499'>Course</span> <span m='455514'>Notes.</span> </p><p><span m='456530'>Our</span>
  <span m='456854'>approach</span> <span m='457179'>to</span> <span m='457503'>dealing</span>
  <span m='457828'>with</span> <span m='458152'>asynchronous</span> <span m='458477'>inputs</span>
  <span m='458801'>is</span> <span m='459126'>to</span> <span m='459450'>put</span>
  <span m='459775'>the</span> <span m='460099'>potentially</span> <span m='460424'>metastable</span>
  <span m='460749'>value</span> <span m='461174'>coming</span> <span m='461600'>out</span>
  <span m='462026'>of</span> <span m='462452'>our</span> <span m='462877'>D-register</span>
  <span m='463303'>synchronizer</span> <span m='463729'>into</span> <span m='464155'>"quarantine"</span>
  <span m='464581'>by</span> <span m='465006'>adding</span> <span m='465432'>a</span>
  <span m='465858'>second</span> <span m='466284'>register</span> <span m='466710'>hooked</span>
  <span m='467183'>to</span> <span m='467657'>the</span> <span m='468130'>output</span>
  <span m='468604'>of</span> <span m='469078'>the</span> <span m='469551'>first</span>
  <span m='470025'>register.</span> </p><p><span m='470499'>If</span> <span m='470819'>a</span>
  <span m='471140'>transition</span> <span m='471461'>on</span> <span m='471781'>the</span>
  <span m='472102'>input</span> <span m='472423'>violates</span> <span m='472744'>the</span>
  <span m='473064'>dynamic</span> <span m='473385'>discipline</span> <span m='473706'>and</span>
  <span m='474027'>causes</span> <span m='474347'>the</span> <span m='474668'>first</span>
  <span m='474989'>register</span> <span m='475310'>to</span> <span m='475704'>go</span>
  <span m='476099'>metastable,</span> <span m='476494'>it's</span> <span m='476889'>not</span>
  <span m='477284'>immediately</span> <span m='477679'>an</span> <span m='478074'>issue</span>
  <span m='478469'>since</span> <span m='478864'>the</span> <span m='479259'>metastable</span>
  <span m='479654'>value</span> <span m='480049'>is</span> <span m='480444'>stopped</span>
  <span m='480839'>from</span> <span m='481147'>entering</span> <span m='481456'>the</span>
  <span m='481765'>system</span> <span m='482074'>by</span> <span m='482383'>the</span>
  <span m='482692'>second</span> <span m='483001'>register.</span> </p><p><span m='483310'>In</span>
  <span m='483595'>fact,</span> <span m='483880'>during</span> <span m='484165'>the</span>
  <span m='484450'>first</span> <span m='484736'>half</span> <span m='485021'>of</span>
  <span m='485306'>the</span> <span m='485591'>clock</span> <span m='485877'>cycle,</span>
  <span m='486162'>the</span> <span m='486447'>master</span> <span m='486732'>latch</span>
  <span m='487018'>in</span> <span m='487303'>the</span> <span m='487588'>second</span>
  <span m='487873'>register</span> <span m='488159'>is</span> <span m='488707'>closed,</span>
  <span m='489255'>so</span> <span m='489803'>the</span> <span m='490351'>metastable</span>
  <span m='490899'>value</span> <span m='491447'>is</span> <span m='491995'>being</span>
  <span m='492543'>completely</span> <span m='493091'>ignored.</span> </p><p><span
  m='493639'>It's</span> <span m='493957'>only</span> <span m='494275'>at</span> <span
  m='494593'>the</span> <span m='494912'>next</span> <span m='495230'>clock</span>
  <span m='495548'>edge,</span> <span m='495867'>an</span> <span m='496185'>entire</span>
  <span m='496503'>clock</span> <span m='496821'>period</span> <span m='497140'>later,</span>
  <span m='497458'>that</span> <span m='497776'>the</span> <span m='498095'>second</span>
  <span m='498413'>D</span> <span m='498731'>register</span> <span m='499050'>will</span>
  <span m='499422'>need</span> <span m='499795'>a</span> <span m='500168'>valid</span>
  <span m='500540'>and</span> <span m='500913'>stable</span> <span m='501286'>input.</span>
  </p><p><span m='501659'>There's</span> <span m='501962'>still</span> <span m='502266'>some</span>
  <span m='502569'>probability</span> <span m='502873'>that</span> <span m='503176'>the</span>
  <span m='503480'>first</span> <span m='503784'>register</span> <span m='504087'>will</span>
  <span m='504391'>be</span> <span m='504694'>metastable</span> <span m='504998'>after</span>
  <span m='505301'>an</span> <span m='505605'>entire</span> <span m='505909'>clock</span>
  <span m='506234'>period,</span> <span m='506560'>but</span> <span m='506886'>we</span>
  <span m='507212'>can</span> <span m='507538'>make</span> <span m='507864'>that</span>
  <span m='508190'>probability</span> <span m='508516'>as</span> <span m='508841'>low</span>
  <span m='509167'>as</span> <span m='509493'>we</span> <span m='509819'>wish</span>
  <span m='510145'>by</span> <span m='510471'>choosing</span> <span m='510797'>a</span>
  <span m='511123'>sufficiently</span> <span m='511449'>long</span> <span m='512219'>clock</span>
  <span m='512989'>period.</span> </p><p><span m='513759'>In</span> <span m='514051'>other</span>
  <span m='514343'>words,</span> <span m='514636'>the</span> <span m='514928'>output</span>
  <span m='515220'>of</span> <span m='515513'>the</span> <span m='515805'>second</span>
  <span m='516097'>register,</span> <span m='516390'>which</span> <span m='516682'>provides</span>
  <span m='516974'>the</span> <span m='517267'>signal</span> <span m='517559'>used</span>
  <span m='517851'>by</span> <span m='518144'>the</span> <span m='518436'>internal</span>
  <span m='518729'>combinational</span> <span m='519176'>logic,</span> <span m='519624'>will</span>
  <span m='520072'>be</span> <span m='520520'>stable</span> <span m='520967'>and</span>
  <span m='521415'>valid</span> <span m='521863'>with</span> <span m='522311'>a</span>
  <span m='522758'>probability</span> <span m='523206'>of</span> <span m='523654'>our</span>
  <span m='524102'>choosing.</span> </p><p><span m='524550'>Validity</span> <span
  m='524970'>is</span> <span m='525391'>not</span> <span m='525811'>100%</span> <span
  m='526232'>guaranteed,</span> <span m='526653'>but</span> <span m='527073'>the</span>
  <span m='527494'>failure</span> <span m='527915'>times</span> <span m='528335'>are</span>
  <span m='528756'>measured</span> <span m='529176'>in</span> <span m='529597'>years</span>
  <span m='530018'>or</span> <span m='530438'>decades,</span> <span m='530859'>so</span>
  <span m='531280'>it's</span> <span m='531738'>not</span> <span m='532196'>an</span>
  <span m='532654'>issue</span> <span m='533112'>in</span> <span m='533570'>practice.</span>
  </p><p><span m='534029'>Without</span> <span m='534359'>the</span> <span m='534689'>second</span>
  <span m='535019'>register,</span> <span m='535349'>the</span> <span m='535679'>system</span>
  <span m='536009'>might</span> <span m='536339'>see</span> <span m='536669'>a</span>
  <span m='536999'>metastability</span> <span m='537329'>failure</span> <span m='537659'>every</span>
  <span m='537989'>handful</span> <span m='538320'>of</span> <span m='538666'>hours</span>
  <span m='539013'>-</span> <span m='539359'>the</span> <span m='539706'>exact</span>
  <span m='540053'>failure</span> <span m='540399'>rate</span> <span m='540746'>depends</span>
  <span m='541092'>on</span> <span m='541439'>the</span> <span m='541786'>transition</span>
  <span m='542132'>frequencies</span> <span m='542479'>and</span> <span m='542825'>gains</span>
  <span m='543172'>in</span> <span m='543519'>the</span> <span m='544754'>circuit.</span>
  </p><p><span m='545990'>What</span> <span m='546356'>happens</span> <span m='546722'>if</span>
  <span m='547088'>our</span> <span m='547454'>clock</span> <span m='547820'>period</span>
  <span m='548186'>is</span> <span m='548552'>short</span> <span m='548918'>but</span>
  <span m='549284'>we</span> <span m='549650'>want</span> <span m='550016'>a</span>
  <span m='550382'>long</span> <span m='550748'>quarantine</span> <span m='551114'>time?</span>
  </p><p><span m='551480'>We</span> <span m='551935'>can</span> <span m='552390'>use</span>
  <span m='552845'>multiple</span> <span m='553300'>quarantine</span> <span m='553755'>registers</span>
  <span m='554210'>in</span> <span m='554665'>series.</span> </p><p><span m='555120'>It's</span>
  <span m='555424'>the</span> <span m='555728'>total</span> <span m='556032'>delay</span>
  <span m='556336'>between</span> <span m='556640'>when</span> <span m='556944'>the</span>
  <span m='557248'>first</span> <span m='557552'>register</span> <span m='557856'>goes</span>
  <span m='558160'>metastable</span> <span m='558464'>and</span> <span m='558768'>when</span>
  <span m='559072'>the</span> <span m='559376'>synchronized</span> <span m='559680'>input</span>
  <span m='560162'>is</span> <span m='560645'>used</span> <span m='561127'>by</span>
  <span m='561610'>the</span> <span m='562092'>internal</span> <span m='562575'>logic</span>
  <span m='563057'>that</span> <span m='563540'>determines</span> <span m='564022'>the</span>
  <span m='564505'>failure</span> <span m='564987'>probability.</span> </p><p><span
  m='565470'>The</span> <span m='566016'>bottom</span> <span m='566563'>line?</span>
  </p><p><span m='567110'>We</span> <span m='567501'>can</span> <span m='567892'>use</span>
  <span m='568284'>synchronizing</span> <span m='568675'>registers</span> <span m='569067'>to</span>
  <span m='569458'>quarantine</span> <span m='569850'>potentially</span> <span m='570241'>metastable</span>
  <span m='570633'>signals</span> <span m='571024'>for</span> <span m='571416'>some</span>
  <span m='571807'>period</span> <span m='572199'>of</span> <span m='573149'>time.</span>
  </p><p><span m='574100'>Since</span> <span m='574508'>the</span> <span m='574916'>probability</span>
  <span m='575325'>of</span> <span m='575733'>still</span> <span m='576141'>being</span>
  <span m='576550'>metastable</span> <span m='576958'>decreases</span> <span m='577366'>exponentially</span>
  <span m='577775'>with</span> <span m='578183'>the</span> <span m='578591'>quarantine</span>
  <span m='579000'>time,</span> <span m='579484'>we</span> <span m='579968'>can</span>
  <span m='580453'>reduce</span> <span m='580937'>the</span> <span m='581422'>failure</span>
  <span m='581906'>probability</span> <span m='582391'>to</span> <span m='582875'>any</span>
  <span m='583360'>desired</span> <span m='583844'>level.</span> </p><p><span m='584329'>Not</span>
  <span m='584656'>a</span> <span m='584983'>100%</span> <span m='585311'>guaranteed,</span>
  <span m='585638'>but</span> <span m='585966'>close</span> <span m='586293'>enough</span>
  <span m='586620'>that</span> <span m='586948'>metastability</span> <span m='587275'>is</span>
  <span m='587603'>not</span> <span m='587930'>a</span> <span m='588257'>practical</span>
  <span m='588585'>issue</span> <span m='588912'>if</span> <span m='589240'>we</span>
  <span m='589602'>use</span> <span m='589964'>our</span> <span m='590326'>quarantine</span>
  <span m='590688'>strategy.</span> </p>
type: course
uid: 9f41afa6ab3ae04b2255a039a6f01a3b

---
None