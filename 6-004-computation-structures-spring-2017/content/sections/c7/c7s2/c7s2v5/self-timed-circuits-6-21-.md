---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 63QXdU9pliI
  parent_uid: 2c3bdc7af23d63b7f4c66f6a19e126bd
  title: Video-YouTube-Stream
  type: Video
  uid: 3ffc4987c66874b7902cb9f741b065d9
- id: 3Play-3Play YouTube id-Stream
  media_location: 63QXdU9pliI
  parent_uid: 2c3bdc7af23d63b7f4c66f6a19e126bd
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: f41a29366f1176b55e6fea9adc925438
- id: 63QXdU9pliI.srt
  parent_uid: 2c3bdc7af23d63b7f4c66f6a19e126bd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v5/self-timed-circuits-6-21-/63QXdU9pliI.srt
  title: 3play caption file
  type: null
  uid: 299a02536b7ce45c5ee9e45d759a93d6
- id: 63QXdU9pliI.pdf
  parent_uid: 2c3bdc7af23d63b7f4c66f6a19e126bd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v5/self-timed-circuits-6-21-/63QXdU9pliI.pdf
  title: 3play pdf file
  type: null
  uid: 5114190e2cbb4e1653a41194a6714bbf
- id: Caption-3Play YouTube id-SRT
  parent_uid: 2c3bdc7af23d63b7f4c66f6a19e126bd
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 81023596a2a4e33fb452e10437fb01d2
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 2c3bdc7af23d63b7f4c66f6a19e126bd
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 57ac622d929caf0d59938fc92dab5d1f
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/63QXdU9pliI/default.jpg
  parent_uid: 2c3bdc7af23d63b7f4c66f6a19e126bd
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: ab2cbc84136db3c438bfab66eda86dfb
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_07-02-05_300k.mp4
  parent_uid: 2c3bdc7af23d63b7f4c66f6a19e126bd
  title: Video-Internet Archive-MP4
  type: Video
  uid: d89e99b6634d80ac954fbfa1455f56c8
inline_embed_id: 83290041selftimedcircuits62165872432
layout: video
order_index: null
parent_uid: b9ee3bbec859798f8121a333957c243e
related_resources_text: ''
short_url: self-timed-circuits-6-21-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v5/self-timed-circuits-6-21-
template_type: Embed
title: Self-timed Circuits (6:21)
transcript: <p><span m='1099'>We've</span> <span m='1461'>been</span> <span m='1824'>designing</span>
  <span m='2187'>our</span> <span m='2549'>processing</span> <span m='2912'>pipelines</span>
  <span m='3275'>to</span> <span m='3638'>have</span> <span m='4000'>all</span> <span
  m='4363'>the</span> <span m='4726'>stages</span> <span m='5089'>operate</span> <span
  m='5451'>in</span> <span m='5814'>lock</span> <span m='6177'>step,</span> <span
  m='6540'>choosing</span> <span m='6940'>the</span> <span m='7341'>clock</span> <span
  m='7742'>period</span> <span m='8142'>to</span> <span m='8543'>accommodate</span>
  <span m='8944'>the</span> <span m='9345'>worst-case</span> <span m='9745'>processing</span>
  <span m='10146'>time</span> <span m='10547'>over</span> <span m='10947'>all</span>
  <span m='11348'>the</span> <span m='11749'>stages.</span> </p><p><span m='12150'>This</span>
  <span m='12618'>is</span> <span m='13086'>what</span> <span m='13554'>we'd</span>
  <span m='14022'>call</span> <span m='14490'>a</span> <span m='14958'>synchronous,</span>
  <span m='15426'>globally</span> <span m='15894'>timed</span> <span m='16362'>system.</span>
  </p><p><span m='16830'>But</span> <span m='17101'>what</span> <span m='17373'>if</span>
  <span m='17645'>there</span> <span m='17917'>are</span> <span m='18189'>data</span>
  <span m='18461'>dependencies</span> <span m='18733'>in</span> <span m='19005'>the</span>
  <span m='19276'>processing</span> <span m='19548'>time,</span> <span m='19820'>i.e.,</span>
  <span m='20092'>if</span> <span m='20364'>for</span> <span m='20636'>some</span>
  <span m='20908'>data</span> <span m='21180'>inputs</span> <span m='21500'>a</span>
  <span m='21820'>particular</span> <span m='22140'>processing</span> <span m='22460'>stage</span>
  <span m='22780'>might</span> <span m='23100'>be</span> <span m='23420'>able</span>
  <span m='23740'>to</span> <span m='24060'>produce</span> <span m='24380'>its</span>
  <span m='24700'>output</span> <span m='25020'>in</span> <span m='25340'>a</span>
  <span m='25660'>shorter</span> <span m='25980'>time?</span> </p><p><span m='27170'>Can</span>
  <span m='27523'>we</span> <span m='27877'>design</span> <span m='28231'>a</span>
  <span m='28585'>system</span> <span m='28939'>that</span> <span m='29293'>could</span>
  <span m='29647'>take</span> <span m='30001'>advantage</span> <span m='30355'>of</span>
  <span m='30709'>that</span> <span m='31063'>opportunity</span> <span m='31417'>to</span>
  <span m='31771'>increase</span> <span m='32125'>throughput?</span> </p><p><span
  m='32479'>One</span> <span m='32754'>alternative</span> <span m='33029'>is</span>
  <span m='33304'>to</span> <span m='33580'>continue</span> <span m='33855'>to</span>
  <span m='34130'>use</span> <span m='34406'>a</span> <span m='34681'>single</span>
  <span m='34956'>system</span> <span m='35231'>clock,</span> <span m='35507'>but</span>
  <span m='35782'>for</span> <span m='36057'>each</span> <span m='36333'>stage</span>
  <span m='36608'>to</span> <span m='36883'>signal</span> <span m='37159'>when</span>
  <span m='37463'>it's</span> <span m='37768'>ready</span> <span m='38073'>for</span>
  <span m='38378'>a</span> <span m='38682'>new</span> <span m='38987'>input</span>
  <span m='39292'>and</span> <span m='39597'>when</span> <span m='39902'>it</span>
  <span m='40206'>has</span> <span m='40511'>a</span> <span m='40816'>new</span> <span
  m='41121'>output</span> <span m='41426'>ready</span> <span m='41730'>for</span>
  <span m='42035'>the</span> <span m='42340'>next</span> <span m='42645'>stage.</span>
  </p><p><span m='42950'>It's</span> <span m='43292'>fun</span> <span m='43635'>to</span>
  <span m='43977'>design</span> <span m='44320'>a</span> <span m='44663'>simple</span>
  <span m='45005'>2-signal</span> <span m='45348'>handshake</span> <span m='45690'>protocol</span>
  <span m='46033'>to</span> <span m='46376'>reliably</span> <span m='46718'>transfer</span>
  <span m='47061'>data</span> <span m='47403'>from</span> <span m='47746'>one</span>
  <span m='48089'>stage</span> <span m='48621'>to</span> <span m='49154'>the</span>
  <span m='49686'>next.</span> </p><p><span m='50219'>The</span> <span m='50558'>upstream</span>
  <span m='50897'>stage</span> <span m='51237'>produces</span> <span m='51576'>a</span>
  <span m='51915'>signal</span> <span m='52255'>called</span> <span m='52594'>HERE-IS-X</span>
  <span m='52933'>to</span> <span m='53273'>indicate</span> <span m='53612'>that</span>
  <span m='53951'>is</span> <span m='54291'>has</span> <span m='54630'>new</span>
  <span m='54969'>data</span> <span m='55309'>for</span> <span m='55776'>the</span>
  <span m='56244'>downstream</span> <span m='56712'>stage.</span> </p><p><span m='57180'>And</span>
  <span m='57471'>the</span> <span m='57763'>downstream</span> <span m='58055'>stage</span>
  <span m='58347'>produces</span> <span m='58639'>a</span> <span m='58931'>signal</span>
  <span m='59223'>called</span> <span m='59515'>GOT-X</span> <span m='59807'>to</span>
  <span m='60099'>indicate</span> <span m='60391'>when</span> <span m='60683'>it</span>
  <span m='60975'>is</span> <span m='61267'>willing</span> <span m='61559'>to</span>
  <span m='61969'>consume</span> <span m='62379'>data.</span> </p><p><span m='62789'>It's</span>
  <span m='63112'>a</span> <span m='63435'>synchronous</span> <span m='63758'>system</span>
  <span m='64081'>so</span> <span m='64404'>the</span> <span m='64727'>signal</span>
  <span m='65050'>values</span> <span m='65373'>are</span> <span m='65696'>only</span>
  <span m='66019'>examined</span> <span m='66342'>on</span> <span m='66665'>the</span>
  <span m='66988'>rising</span> <span m='67311'>edge</span> <span m='67634'>of</span>
  <span m='67957'>the</span> <span m='68280'>clock.</span> </p><p><span m='70539'>The</span>
  <span m='70976'>handshake</span> <span m='71413'>protocol</span> <span m='71850'>works</span>
  <span m='72287'>as</span> <span m='72724'>follows:</span> <span m='73161'>the</span>
  <span m='73598'>upstream</span> <span m='74035'>stage</span> <span m='74472'>asserts</span>
  <span m='74909'>HERE-IS-X</span> <span m='75346'>if</span> <span m='75783'>it</span>
  <span m='76220'>will</span> <span m='76566'>have</span> <span m='76913'>a</span>
  <span m='77260'>new</span> <span m='77606'>output</span> <span m='77953'>value</span>
  <span m='78300'>available</span> <span m='78646'>at</span> <span m='78993'>the</span>
  <span m='79340'>next</span> <span m='79686'>rising</span> <span m='80033'>edge</span>
  <span m='80380'>of</span> <span m='80726'>the</span> <span m='81073'>clock.</span>
  </p><p><span m='81420'>The</span> <span m='81714'>downstream</span> <span m='82008'>stage</span>
  <span m='82302'>asserts</span> <span m='82596'>GOT-X</span> <span m='82890'>if</span>
  <span m='83184'>it</span> <span m='83478'>will</span> <span m='83772'>grab</span>
  <span m='84067'>the</span> <span m='84361'>next</span> <span m='84655'>output</span>
  <span m='84949'>at</span> <span m='85243'>the</span> <span m='85537'>rising</span>
  <span m='85831'>edge</span> <span m='86125'>of</span> <span m='86420'>the</span>
  <span m='87130'>clock.</span> </p><p><span m='87840'>Both</span> <span m='88103'>stages</span>
  <span m='88366'>look</span> <span m='88629'>at</span> <span m='88892'>the</span>
  <span m='89155'>signals</span> <span m='89418'>on</span> <span m='89682'>the</span>
  <span m='89945'>rising</span> <span m='90208'>edge</span> <span m='90471'>of</span>
  <span m='90734'>the</span> <span m='90997'>clock</span> <span m='91261'>to</span>
  <span m='91524'>decide</span> <span m='91787'>what</span> <span m='92050'>to</span>
  <span m='92313'>do</span> <span m='92576'>next.</span> </p><p><span m='92840'>If</span>
  <span m='93200'>both</span> <span m='93561'>stages</span> <span m='93921'>see</span>
  <span m='94282'>that</span> <span m='94642'>HERE-IS-X</span> <span m='95003'>and</span>
  <span m='95364'>GOT-X</span> <span m='95724'>are</span> <span m='96085'>asserted</span>
  <span m='96445'>at</span> <span m='96806'>the</span> <span m='97167'>same</span>
  <span m='97527'>clock</span> <span m='97888'>edge,</span> <span m='98248'>the</span>
  <span m='98609'>handshake</span> <span m='98970'>is</span> <span m='99430'>complete</span>
  <span m='99890'>and</span> <span m='100350'>the</span> <span m='100810'>data</span>
  <span m='101270'>transfer</span> <span m='101730'>happens</span> <span m='102190'>at</span>
  <span m='102650'>that</span> <span m='103110'>clock</span> <span m='103570'>edge.</span>
  </p><p><span m='104030'>Either</span> <span m='104296'>stage</span> <span m='104562'>can</span>
  <span m='104828'>delay</span> <span m='105094'>a</span> <span m='105360'>transfer</span>
  <span m='105627'>if</span> <span m='105893'>they</span> <span m='106159'>are</span>
  <span m='106425'>still</span> <span m='106691'>working</span> <span m='106958'>on</span>
  <span m='107224'>producing</span> <span m='107490'>the</span> <span m='107756'>next</span>
  <span m='108022'>output</span> <span m='108289'>or</span> <span m='108762'>consuming</span>
  <span m='109236'>the</span> <span m='109710'>previous</span> <span m='110184'>input.</span>
  </p><p><span m='110658'>It's</span> <span m='111193'>possible,</span> <span m='111729'>although</span>
  <span m='112264'>considerably</span> <span m='112800'>more</span> <span m='113335'>difficult,</span>
  <span m='113871'>to</span> <span m='114406'>build</span> <span m='114942'>a</span>
  <span m='115477'>clock-free</span> <span m='116013'>asynchronous</span> <span m='116549'>self-timed</span>
  <span m='117101'>system</span> <span m='117654'>that</span> <span m='118206'>uses</span>
  <span m='118759'>a</span> <span m='119311'>similar</span> <span m='119864'>handshake</span>
  <span m='120416'>protocol.</span> </p><p><span m='120969'>The</span> <span m='121521'>handshake</span>
  <span m='122073'>involves</span> <span m='122625'>four</span> <span m='123177'>phases.</span>
  </p><p><span m='123729'>In</span> <span m='124094'>phase</span> <span m='124459'>1,</span>
  <span m='124825'>when</span> <span m='125190'>the</span> <span m='125555'>upstream</span>
  <span m='125921'>stage</span> <span m='126286'>has</span> <span m='126651'>a</span>
  <span m='127017'>new</span> <span m='127382'>output</span> <span m='127747'>and</span>
  <span m='128113'>GOT-X</span> <span m='128478'>is</span> <span m='128843'>deasserted,</span>
  <span m='129209'>it</span> <span m='129574'>asserts</span> <span m='129940'>its</span>
  <span m='130332'>HERE-IS-X</span> <span m='130724'>signal</span> <span m='131116'>and</span>
  <span m='131508'>then</span> <span m='131900'>waits</span> <span m='132292'>to</span>
  <span m='132684'>see</span> <span m='133076'>the</span> <span m='133468'>downstream</span>
  <span m='133860'>stage's</span> <span m='134252'>reply</span> <span m='134644'>on</span>
  <span m='135036'>the</span> <span m='135428'>GOT-X</span> <span m='135820'>signal.</span>
  </p><p><span m='137840'>In</span> <span m='138323'>phase</span> <span m='138807'>2,</span>
  <span m='139290'>the</span> <span m='139774'>downstream</span> <span m='140257'>stage,</span>
  <span m='140741'>seeing</span> <span m='141225'>that</span> <span m='141708'>HERE-IS-X</span>
  <span m='142192'>is</span> <span m='142675'>asserted,</span> <span m='143159'>asserts</span>
  <span m='143642'>GOT-X</span> <span m='144126'>when</span> <span m='144610'>it</span>
  <span m='144981'>has</span> <span m='145353'>consumed</span> <span m='145725'>the</span>
  <span m='146096'>available</span> <span m='146468'>input.</span> </p><p><span m='146840'>In</span>
  <span m='147291'>phase</span> <span m='147742'>3,</span> <span m='148194'>the</span>
  <span m='148645'>downstream</span> <span m='149096'>stage</span> <span m='149548'>waits</span>
  <span m='149999'>to</span> <span m='150450'>see</span> <span m='150902'>the</span>
  <span m='151353'>HERE-IS-X</span> <span m='151804'>go</span> <span m='152256'>low,</span>
  <span m='152707'>indicating</span> <span m='153158'>that</span> <span m='153610'>the</span>
  <span m='154163'>upstream</span> <span m='154716'>stage</span> <span m='155270'>has</span>
  <span m='155823'>successfully</span> <span m='156376'>received</span> <span m='156930'>the</span>
  <span m='157483'>GOT-X</span> <span m='158036'>signal.</span> </p><p><span m='158590'>In</span>
  <span m='159037'>phase</span> <span m='159485'>4,</span> <span m='159933'>once</span>
  <span m='160381'>HERE-IS-X</span> <span m='160829'>is</span> <span m='161277'>deasserted,</span>
  <span m='161725'>the</span> <span m='162172'>downstream</span> <span m='162620'>stage</span>
  <span m='163068'>deasserts</span> <span m='163516'>GOT-X</span> <span m='163964'>and</span>
  <span m='164412'>the</span> <span m='164860'>transfer</span> <span m='165404'>handshake</span>
  <span m='165948'>is</span> <span m='166492'>ready</span> <span m='167037'>to</span>
  <span m='167581'>begin</span> <span m='168125'>again.</span> </p><p><span m='168670'>Note</span>
  <span m='168995'>that</span> <span m='169321'>the</span> <span m='169647'>upstream</span>
  <span m='169972'>stage</span> <span m='170298'>waits</span> <span m='170624'>until</span>
  <span m='170950'>it</span> <span m='171275'>sees</span> <span m='171601'>the</span>
  <span m='171927'>GOT-X</span> <span m='172252'>deasserted</span> <span m='172578'>before</span>
  <span m='172904'>starting</span> <span m='173230'>the</span> <span m='173756'>next</span>
  <span m='174283'>handshake.</span> </p><p><span m='174810'>The</span> <span m='175082'>timing</span>
  <span m='175354'>of</span> <span m='175627'>the</span> <span m='175899'>system</span>
  <span m='176171'>is</span> <span m='176444'>based</span> <span m='176716'>on</span>
  <span m='176988'>the</span> <span m='177261'>transitions</span> <span m='177533'>of</span>
  <span m='177805'>the</span> <span m='178078'>handshake</span> <span m='178350'>signals,</span>
  <span m='178622'>which</span> <span m='178895'>can</span> <span m='179167'>happen</span>
  <span m='179440'>at</span> <span m='179877'>any</span> <span m='180314'>time</span>
  <span m='180751'>the</span> <span m='181189'>conditions</span> <span m='181626'>required</span>
  <span m='182063'>by</span> <span m='182500'>the</span> <span m='182938'>protocol</span>
  <span m='183375'>are</span> <span m='183812'>satisfied.</span> </p><p><span m='184250'>No</span>
  <span m='184685'>need</span> <span m='185121'>for</span> <span m='185557'>a</span>
  <span m='185992'>global</span> <span m='186428'>clock</span> <span m='186864'>here!</span>
  </p><p><span m='187300'>It's</span> <span m='187568'>fun</span> <span m='187837'>to</span>
  <span m='188106'>think</span> <span m='188374'>about</span> <span m='188643'>how</span>
  <span m='188912'>this</span> <span m='189180'>self-timed</span> <span m='189449'>protocol</span>
  <span m='189718'>might</span> <span m='189986'>work</span> <span m='190255'>when</span>
  <span m='190524'>there</span> <span m='190792'>are</span> <span m='191061'>multiple</span>
  <span m='191330'>downstream</span> <span m='191768'>modules,</span> <span m='192207'>each</span>
  <span m='192646'>with</span> <span m='193085'>their</span> <span m='193523'>own</span>
  <span m='193962'>internal</span> <span m='194401'>timing.</span> </p><p><span m='194840'>In</span>
  <span m='195235'>this</span> <span m='195630'>example,</span> <span m='196025'>A's</span>
  <span m='196420'>output</span> <span m='196815'>is</span> <span m='197210'>consumed</span>
  <span m='197605'>by</span> <span m='198000'>both</span> <span m='198395'>the</span>
  <span m='198790'>B</span> <span m='199185'>and</span> <span m='199580'>C</span>
  <span m='199975'>stages.</span> </p><p><span m='200370'>We</span> <span m='200651'>need</span>
  <span m='200933'>a</span> <span m='201215'>special</span> <span m='201496'>circuit,</span>
  <span m='201778'>shown</span> <span m='202060'>as</span> <span m='202341'>a</span>
  <span m='202623'>yellow</span> <span m='202905'>box</span> <span m='203186'>in</span>
  <span m='203468'>the</span> <span m='203750'>diagram,</span> <span m='204031'>to</span>
  <span m='204313'>combine</span> <span m='204595'>the</span> <span m='204876'>GOT-X</span>
  <span m='205158'>signals</span> <span m='205440'>from</span> <span m='205817'>the</span>
  <span m='206194'>B</span> <span m='206572'>and</span> <span m='206949'>C</span>
  <span m='207326'>stages</span> <span m='207704'>and</span> <span m='208081'>produce</span>
  <span m='208458'>a</span> <span m='208836'>summary</span> <span m='209213'>signal</span>
  <span m='209590'>for</span> <span m='209968'>the</span> <span m='210345'>A</span>
  <span m='210722'>stage.</span> </p><p><span m='211100'>Let's</span> <span m='211419'>take</span>
  <span m='211738'>a</span> <span m='212057'>quick</span> <span m='212376'>look</span>
  <span m='212695'>at</span> <span m='213014'>the</span> <span m='213333'>timing</span>
  <span m='213652'>diagram</span> <span m='213971'>shown</span> <span m='214290'>here.</span>
  </p><p><span m='214610'>After</span> <span m='214959'>A</span> <span m='215308'>has</span>
  <span m='215658'>asserted</span> <span m='216007'>HERE-IS-X,</span> <span m='216357'>the</span>
  <span m='216706'>circuit</span> <span m='217055'>in</span> <span m='217405'>the</span>
  <span m='217754'>yellow</span> <span m='218104'>box</span> <span m='218453'>waits</span>
  <span m='218802'>until</span> <span m='219152'>both</span> <span m='219501'>the</span>
  <span m='219851'>B</span> <span m='220200'>and</span> <span m='220550'>the</span>
  <span m='220956'>C</span> <span m='221362'>stage</span> <span m='221768'>have</span>
  <span m='222174'>asserted</span> <span m='222580'>their</span> <span m='222986'>GOT-X</span>
  <span m='223392'>signals</span> <span m='223798'>before</span> <span m='224204'>asserting</span>
  <span m='224610'>GOT-X</span> <span m='225016'>to</span> <span m='225422'>the</span>
  <span m='225828'>A</span> <span m='226234'>stage.</span> </p><p><span m='226640'>At</span>
  <span m='226970'>this</span> <span m='227301'>point</span> <span m='227631'>the</span>
  <span m='227962'>A</span> <span m='228292'>stage</span> <span m='228623'>deasserts</span>
  <span m='228954'>HERE-IS-X,</span> <span m='229284'>then</span> <span m='229615'>the</span>
  <span m='229945'>yellow</span> <span m='230276'>box</span> <span m='230607'>waits</span>
  <span m='230937'>until</span> <span m='231268'>both</span> <span m='231598'>the</span>
  <span m='231929'>B</span> <span m='232260'>and</span> <span m='232734'>C</span>
  <span m='233208'>stages</span> <span m='233682'>have</span> <span m='234156'>deasserted</span>
  <span m='234630'>their</span> <span m='235104'>GOT-X</span> <span m='235578'>signals,</span>
  <span m='236052'>before</span> <span m='236526'>deasserting</span> <span m='237000'>GOT-X</span>
  <span m='237474'>to</span> <span m='237948'>the</span> <span m='238422'>A</span>
  <span m='238896'>stage.</span> </p><p><span m='239370'>Let's</span> <span m='239691'>watch</span>
  <span m='240013'>the</span> <span m='240335'>system</span> <span m='240656'>in</span>
  <span m='240978'>action!</span> </p><p><span m='241300'>When</span> <span m='241610'>a</span>
  <span m='241921'>signal</span> <span m='242232'>is</span> <span m='242542'>asserted</span>
  <span m='242853'>we'll</span> <span m='243164'>show</span> <span m='243474'>it</span>
  <span m='243785'>in</span> <span m='244096'>red,</span> <span m='244406'>otherwise</span>
  <span m='244717'>it's</span> <span m='245028'>shown</span> <span m='245338'>in</span>
  <span m='245649'>black.</span> </p><p><span m='245960'>A</span> <span m='246246'>new</span>
  <span m='246533'>value</span> <span m='246820'>for</span> <span m='247106'>the</span>
  <span m='247393'>A</span> <span m='247680'>stage</span> <span m='247966'>arrives</span>
  <span m='248253'>on</span> <span m='248540'>A's</span> <span m='248826'>data</span>
  <span m='249113'>input</span> <span m='249400'>and</span> <span m='249686'>the</span>
  <span m='249973'>module</span> <span m='250260'>supplying</span> <span m='250546'>the</span>
  <span m='250833'>value</span> <span m='251120'>then</span> <span m='251510'>asserts</span>
  <span m='251901'>its</span> <span m='252291'>HERE-IS-X</span> <span m='252682'>signal</span>
  <span m='253073'>to</span> <span m='253463'>let</span> <span m='253854'>A</span>
  <span m='254245'>know</span> <span m='254635'>it</span> <span m='255026'>has</span>
  <span m='255417'>a</span> <span m='255807'>new</span> <span m='256198'>input.</span>
  </p><p><span m='256589'>At</span> <span m='256985'>some</span> <span m='257382'>point</span>
  <span m='257779'>later,</span> <span m='258175'>A</span> <span m='258572'>signals</span>
  <span m='258969'>GOT-X</span> <span m='259366'>back</span> <span m='259762'>upstream</span>
  <span m='260159'>to</span> <span m='260556'>indicate</span> <span m='260953'>that</span>
  <span m='261349'>it</span> <span m='261746'>has</span> <span m='262143'>consumed</span>
  <span m='262540'>the</span> <span m='263015'>value,</span> <span m='263491'>then</span>
  <span m='263967'>the</span> <span m='264442'>upstream</span> <span m='264918'>stage</span>
  <span m='265394'>deasserts</span> <span m='265870'>HERE-IS-X,</span> <span m='266345'>followed</span>
  <span m='266821'>by</span> <span m='267297'>A</span> <span m='267772'>deasserting</span>
  <span m='268248'>its</span> <span m='268724'>GOT-X</span> <span m='269200'>signal.</span>
  </p><p><span m='270200'>This</span> <span m='270556'>completes</span> <span m='270912'>the</span>
  <span m='271269'>transfer</span> <span m='271625'>of</span> <span m='271981'>the</span>
  <span m='272338'>data</span> <span m='272694'>to</span> <span m='273050'>the</span>
  <span m='273407'>A</span> <span m='273763'>stage.</span> </p><p><span m='274120'>When</span>
  <span m='274389'>A</span> <span m='274659'>is</span> <span m='274928'>ready</span>
  <span m='275198'>to</span> <span m='275467'>send</span> <span m='275737'>a</span>
  <span m='276007'>new</span> <span m='276276'>output</span> <span m='276546'>to</span>
  <span m='276815'>the</span> <span m='277085'>B</span> <span m='277354'>and</span>
  <span m='277624'>C</span> <span m='277894'>stages,</span> <span m='278163'>it</span>
  <span m='278433'>checks</span> <span m='278702'>that</span> <span m='278972'>its</span>
  <span m='279241'>GOT-X</span> <span m='279511'>input</span> <span m='279781'>is</span>
  <span m='280147'>deasserted</span> <span m='280513'>(which</span> <span m='280879'>it</span>
  <span m='281246'>is),</span> <span m='281612'>so</span> <span m='281978'>it</span>
  <span m='282345'>asserts</span> <span m='282711'>the</span> <span m='283077'>new</span>
  <span m='283443'>output</span> <span m='283810'>value</span> <span m='284176'>and</span>
  <span m='284542'>signals</span> <span m='284909'>HERE-IS-X</span> <span m='285292'>to</span>
  <span m='285676'>the</span> <span m='286060'>yellow</span> <span m='286444'>box</span>
  <span m='286828'>which</span> <span m='287212'>forwards</span> <span m='287596'>the</span>
  <span m='287980'>signal</span> <span m='288364'>to</span> <span m='288748'>the</span>
  <span m='289132'>downstream</span> <span m='289516'>stages.</span> </p><p><span
  m='289900'>B</span> <span m='290299'>is</span> <span m='290698'>ready</span> <span
  m='291097'>to</span> <span m='291497'>consume</span> <span m='291896'>the</span>
  <span m='292295'>new</span> <span m='292695'>input</span> <span m='293094'>and</span>
  <span m='293493'>so</span> <span m='293892'>asserts</span> <span m='294292'>its</span>
  <span m='294691'>GOT-X</span> <span m='295090'>output.</span> </p><p><span m='295490'>Note</span>
  <span m='295822'>that</span> <span m='296154'>C</span> <span m='296486'>is</span>
  <span m='296818'>still</span> <span m='297151'>waiting</span> <span m='297483'>for</span>
  <span m='297815'>its</span> <span m='298147'>second</span> <span m='298480'>input</span>
  <span m='298812'>and</span> <span m='299144'>has</span> <span m='299476'>yet</span>
  <span m='299808'>to</span> <span m='300141'>assert</span> <span m='300473'>its</span>
  <span m='300805'>GOT-X</span> <span m='301137'>output.</span> </p><p><span m='301470'>After</span>
  <span m='301861'>B</span> <span m='302253'>finishes</span> <span m='302645'>its</span>
  <span m='303037'>computation,</span> <span m='303429'>it</span> <span m='303821'>supplies</span>
  <span m='304213'>a</span> <span m='304605'>new</span> <span m='304996'>value</span>
  <span m='305388'>to</span> <span m='305780'>C</span> <span m='306172'>and</span>
  <span m='306564'>asserts</span> <span m='306956'>its</span> <span m='307348'>HERE-IS-X</span>
  <span m='307740'>output</span> <span m='308203'>to</span> <span m='308666'>let</span>
  <span m='309129'>C</span> <span m='309592'>know</span> <span m='310055'>its</span>
  <span m='310518'>second</span> <span m='310981'>input</span> <span m='311444'>is</span>
  <span m='311907'>ready.</span> </p><p><span m='312370'>Now</span> <span m='312766'>C</span>
  <span m='313163'>is</span> <span m='313560'>happy</span> <span m='313957'>and</span>
  <span m='314354'>signals</span> <span m='314751'>both</span> <span m='315148'>upstream</span>
  <span m='315545'>stages</span> <span m='315941'>that</span> <span m='316338'>it</span>
  <span m='316735'>has</span> <span m='317132'>consumed</span> <span m='317529'>its</span>
  <span m='317926'>two</span> <span m='318323'>inputs.</span> </p><p><span m='318720'>Now</span>
  <span m='319121'>that</span> <span m='319523'>both</span> <span m='319925'>GOT-X</span>
  <span m='320327'>inputs</span> <span m='320729'>are</span> <span m='321131'>asserted,</span>
  <span m='321533'>the</span> <span m='321935'>yellow</span> <span m='322336'>box</span>
  <span m='322738'>asserts</span> <span m='323140'>A's</span> <span m='323542'>GOT-X</span>
  <span m='323944'>input</span> <span m='324346'>to</span> <span m='324748'>let</span>
  <span m='325150'>it</span> <span m='325583'>know</span> <span m='326017'>that</span>
  <span m='326451'>the</span> <span m='326885'>data</span> <span m='327318'>has</span>
  <span m='327752'>been</span> <span m='328186'>transferred.</span> </p><p><span m='328620'>Meanwhile</span>
  <span m='329001'>B</span> <span m='329383'>completes</span> <span m='329765'>its</span>
  <span m='330147'>part</span> <span m='330529'>of</span> <span m='330911'>the</span>
  <span m='331293'>handshake,</span> <span m='331675'>and</span> <span m='332056'>C</span>
  <span m='332438'>completes</span> <span m='332820'>its</span> <span m='333202'>transaction</span>
  <span m='333584'>with</span> <span m='333966'>B</span> <span m='334348'>and</span>
  <span m='334730'>A</span> <span m='335213'>deasserts</span> <span m='335696'>HERE-IS-X</span>
  <span m='336180'>to</span> <span m='336663'>indicate</span> <span m='337146'>that</span>
  <span m='337630'>it</span> <span m='338113'>has</span> <span m='338596'>seen</span>
  <span m='339080'>its</span> <span m='339563'>GOT-X</span> <span m='340046'>input.</span>
  </p><p><span m='340530'>When</span> <span m='340897'>the</span> <span m='341265'>B</span>
  <span m='341632'>and</span> <span m='342000'>C</span> <span m='342368'>stages</span>
  <span m='342735'>see</span> <span m='343103'>their</span> <span m='343471'>HERE-IS-X</span>
  <span m='343838'>inputs</span> <span m='344206'>go</span> <span m='344574'>low,</span>
  <span m='344941'>they</span> <span m='345309'>their</span> <span m='345677'>finish</span>
  <span m='346044'>their</span> <span m='346412'>handshakes</span> <span m='346780'>by</span>
  <span m='347116'>deasserting</span> <span m='347453'>their</span> <span m='347790'>GOT-X</span>
  <span m='348127'>outputs,</span> <span m='348464'>and</span> <span m='348801'>when</span>
  <span m='349137'>they're</span> <span m='349474'>both</span> <span m='349811'>low,</span>
  <span m='350148'>the</span> <span m='350485'>yellow</span> <span m='350822'>box</span>
  <span m='351159'>lets</span> <span m='351603'>A</span> <span m='352047'>know</span>
  <span m='352491'>the</span> <span m='352936'>handshake</span> <span m='353380'>is</span>
  <span m='353824'>complete</span> <span m='354268'>by</span> <span m='354713'>deserting</span>
  <span m='355157'>A's</span> <span m='355601'>GOT-X</span> <span m='356045'>input.</span>
  </p><p><span m='356490'>Whew!</span> </p><p><span m='357490'>The</span> <span m='357761'>system</span>
  <span m='358032'>has</span> <span m='358303'>returned</span> <span m='358574'>to</span>
  <span m='358845'>the</span> <span m='359117'>initial</span> <span m='359388'>state</span>
  <span m='359659'>where</span> <span m='359930'>A</span> <span m='360201'>is</span>
  <span m='360472'>now</span> <span m='360744'>ready</span> <span m='361015'>to</span>
  <span m='361286'>accept</span> <span m='361557'>some</span> <span m='361828'>future</span>
  <span m='362100'>input</span> <span m='363300'>value.</span> </p><p><span m='364500'>This</span>
  <span m='364970'>an</span> <span m='365440'>elegant</span> <span m='365910'>design</span>
  <span m='366380'>based</span> <span m='366850'>entirely</span> <span m='367320'>on</span>
  <span m='367790'>transition</span> <span m='368260'>signaling.</span> </p><p><span
  m='368730'>Each</span> <span m='369081'>module</span> <span m='369432'>is</span>
  <span m='369784'>in</span> <span m='370135'>complete</span> <span m='370486'>control</span>
  <span m='370838'>of</span> <span m='371189'>when</span> <span m='371540'>it</span>
  <span m='371892'>consumes</span> <span m='372243'>inputs</span> <span m='372594'>and</span>
  <span m='372946'>produces</span> <span m='373297'>outputs,</span> <span m='373648'>and</span>
  <span m='374000'>so</span> <span m='374313'>the</span> <span m='374627'>system</span>
  <span m='374941'>can</span> <span m='375255'>process</span> <span m='375568'>data</span>
  <span m='375882'>at</span> <span m='376196'>the</span> <span m='376510'>fastest</span>
  <span m='376823'>possible</span> <span m='377137'>speed,</span> <span m='377451'>rather</span>
  <span m='377765'>than</span> <span m='378078'>waiting</span> <span m='378392'>for</span>
  <span m='378706'>the</span> <span m='379020'>worst-case</span> <span m='379583'>processing</span>
  <span m='380146'>delay.</span> </p>
type: course
uid: 2c3bdc7af23d63b7f4c66f6a19e126bd

---
None