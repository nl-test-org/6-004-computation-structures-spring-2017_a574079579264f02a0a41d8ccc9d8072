---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 3eQh_W8YF_g
  parent_uid: cc2609802a51f685313aba4a613d7e55
  title: Video-YouTube-Stream
  type: Video
  uid: fd6227bc0450284543952cb52f3547f5
- id: 3Play-3Play YouTube id-Stream
  media_location: 3eQh_W8YF_g
  parent_uid: cc2609802a51f685313aba4a613d7e55
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 3927ec302302b97c926737e32a3ce26f
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/3eQh_W8YF_g/default.jpg
  parent_uid: cc2609802a51f685313aba4a613d7e55
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 014464e21082411f1285edd1f049a681
- id: 3eQh_W8YF_g.srt
  parent_uid: cc2609802a51f685313aba4a613d7e55
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v2/activation-records-and-stacks-8-41-/3eQh_W8YF_g.srt
  title: 3play caption file
  type: null
  uid: bcb68300918f4a88347b31dd5e2c9156
- id: 3eQh_W8YF_g.pdf
  parent_uid: cc2609802a51f685313aba4a613d7e55
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v2/activation-records-and-stacks-8-41-/3eQh_W8YF_g.pdf
  title: 3play pdf file
  type: null
  uid: d4311b49999d02e15f7727eabe895ebd
- id: Caption-3Play YouTube id-SRT
  parent_uid: cc2609802a51f685313aba4a613d7e55
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: d084e5dc807f9f5a1edbb482a1cb5d77
- id: Transcript-3Play YouTube id-PDF
  parent_uid: cc2609802a51f685313aba4a613d7e55
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 45c453d7a8e7c92f4d410b7f366827bd
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_12-02-02_300k.mp4
  parent_uid: cc2609802a51f685313aba4a613d7e55
  title: Video-Internet Archive-MP4
  type: Video
  uid: 7e295377c4573ce30c56ef35a12d31f8
inline_embed_id: 32270306activationrecordsandstacks84114395923
layout: video
order_index: null
parent_uid: 60a334f83601c57a5da59d19b7845c55
related_resources_text: ''
short_url: activation-records-and-stacks-8-41-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v2/activation-records-and-stacks-8-41-
template_type: Embed
title: Activation Records and Stacks (8:41)
transcript: "<p><span m='450'>The</span> <span m='784'>problem</span> <span m='1119'>we</span>\
  \ <span m='1454'>need</span> <span m='1788'>to</span> <span m='2123'>solve</span>\
  \ <span m='2458'>is</span> <span m='2792'>where</span> <span m='3127'>to</span>\
  \ <span m='3462'>store</span> <span m='3797'>the</span> <span m='4131'>values</span>\
  \ <span m='4466'>needed</span> <span m='4801'>by</span> <span m='5135'>procedure:</span>\
  \ <span m='5470'>its</span> <span m='5805'>arguments,</span> <span m='6140'>its</span>\
  \ <span m='6718'>return</span> <span m='7296'>address,</span> <span m='7875'>its</span>\
  \ <span m='8453'>return</span> <span m='9031'>value.</span> </p><p><span m='9610'>The</span>\
  \ <span m='9894'>procedure</span> <span m='10179'>may</span> <span m='10464'>also</span>\
  \ <span m='10749'>need</span> <span m='11034'>storage</span> <span m='11319'>for</span>\
  \ <span m='11604'>its</span> <span m='11889'>local</span> <span m='12174'>variables</span>\
  \ <span m='12459'>and</span> <span m='12744'>space</span> <span m='13029'>to</span>\
  \ <span m='13314'>save</span> <span m='13599'>the</span> <span m='13884'>values</span>\
  \ <span m='14169'>of</span> <span m='14571'>the</span> <span m='14974'>caller's</span>\
  \ <span m='15377'>registers</span> <span m='15780'>before</span> <span m='16183'>they</span>\
  \ <span m='16585'>get</span> <span m='16988'>overwritten</span> <span m='17391'>by</span>\
  \ <span m='17794'>the</span> <span m='18197'>procedure.</span> </p><p><span m='18600'>We'd</span>\
  \ <span m='18908'>like</span> <span m='19216'>to</span> <span m='19524'>avoid</span>\
  \ <span m='19832'>any</span> <span m='20140'>limitations</span> <span m='20448'>on</span>\
  \ <span m='20756'>the</span> <span m='21065'>number</span> <span m='21373'>of</span>\
  \ <span m='21681'>arguments,</span> <span m='21989'>the</span> <span m='22297'>number</span>\
  \ <span m='22605'>of</span> <span m='22913'>local</span> <span m='23221'>variables,</span>\
  \ <span m='23530'>etc.</span> </p><p><span m='24710'>So</span> <span m='25038'>we'll</span>\
  \ <span m='25366'>need</span> <span m='25694'>a</span> <span m='26022'>block</span>\
  \ <span m='26350'>of</span> <span m='26679'>storage</span> <span m='27007'>for</span>\
  \ <span m='27335'>each</span> <span m='27663'>active</span> <span m='27991'>procedure</span>\
  \ <span m='28320'>call,</span> <span m='28648'>what</span> <span m='28976'>we'll</span>\
  \ <span m='29304'>call</span> <span m='29632'>the</span> <span m='29961'>\"activation</span>\
  \ <span m='30545'>record\".</span> </p><p><span m='31130'>As</span> <span m='31466'>we</span>\
  \ <span m='31802'>saw</span> <span m='32138'>in</span> <span m='32475'>the</span>\
  \ <span m='32811'>factorial</span> <span m='33147'>example,</span> <span m='33483'>we</span>\
  \ <span m='33820'>can't</span> <span m='34156'>statically</span> <span m='34492'>allocate</span>\
  \ <span m='34828'>a</span> <span m='35165'>single</span> <span m='35501'>block</span>\
  \ <span m='35837'>of</span> <span m='36173'>storage</span> <span m='36510'>for</span>\
  \ <span m='36860'>a</span> <span m='37211'>particular</span> <span m='37562'>procedure</span>\
  \ <span m='37912'>since</span> <span m='38263'>recursive</span> <span m='38614'>calls</span>\
  \ <span m='38965'>mean</span> <span m='39315'>we'll</span> <span m='39666'>have</span>\
  \ <span m='40017'>many</span> <span m='40367'>active</span> <span m='40718'>calls</span>\
  \ <span m='41069'>to</span> <span m='41420'>that</span> <span m='41915'>procedure</span>\
  \ <span m='42411'>at</span> <span m='42907'>points</span> <span m='43402'>during</span>\
  \ <span m='43898'>the</span> <span m='44394'>execution.</span> </p><p><span m='44890'>What</span>\
  \ <span m='45177'>we</span> <span m='45465'>need</span> <span m='45752'>is</span>\
  \ <span m='46040'>a</span> <span m='46327'>way</span> <span m='46615'>to</span>\
  \ <span m='46902'>dynamically</span> <span m='47190'>allocate</span> <span m='47477'>storage</span>\
  \ <span m='47765'>for</span> <span m='48052'>an</span> <span m='48340'>activation</span>\
  \ <span m='48627'>record</span> <span m='48915'>when</span> <span m='49202'>the</span>\
  \ <span m='49490'>procedure</span> <span m='49962'>is</span> <span m='50435'>called,</span>\
  \ <span m='50907'>which</span> <span m='51380'>can</span> <span m='51852'>then</span>\
  \ <span m='52325'>be</span> <span m='52797'>reclaimed</span> <span m='53270'>when</span>\
  \ <span m='53742'>the</span> <span m='54215'>procedure</span> <span m='54687'>returns.</span>\
  \ </p><p><span m='55160'>Let's</span> <span m='55609'>see</span> <span m='56058'>how</span>\
  \ <span m='56507'>activation</span> <span m='56956'>records</span> <span m='57405'>come</span>\
  \ <span m='57854'>and</span> <span m='58303'>go</span> <span m='58752'>as</span>\
  \ <span m='59201'>execution</span> <span m='59650'>proceeds.</span> </p><p><span\
  \ m='60100'>The</span> <span m='60568'>first</span> <span m='61037'>activation</span>\
  \ <span m='61506'>record</span> <span m='61975'>is</span> <span m='62443'>for</span>\
  \ <span m='62912'>the</span> <span m='63381'>call</span> <span m='63850'>fact(3).</span>\
  \ </p><p><span m='64319'>It's</span> <span m='64609'>created</span> <span m='64899'>at</span>\
  \ <span m='65189'>the</span> <span m='65479'>beginning</span> <span m='65769'>of</span>\
  \ <span m='66059'>the</span> <span m='66349'>procedure</span> <span m='66639'>and</span>\
  \ <span m='66929'>holds,</span> <span m='67219'>among</span> <span m='67509'>other</span>\
  \ <span m='67799'>things,</span> <span m='68089'>the</span> <span m='68379'>value</span>\
  \ <span m='68669'>of</span> <span m='68960'>the</span> <span m='69319'>argument</span>\
  \ <span m='69679'>n</span> <span m='70039'>and</span> <span m='70399'>the</span>\
  \ <span m='70759'>return</span> <span m='71119'>address</span> <span m='71479'>where</span>\
  \ <span m='71839'>execution</span> <span m='72199'>should</span> <span m='72559'>resume</span>\
  \ <span m='72919'>after</span> <span m='73279'>the</span> <span m='73639'>fact(3)</span>\
  \ <span m='73999'>computation</span> <span m='75085'>is</span> <span m='76172'>complete.</span>\
  \ </p><p><span m='77259'>During</span> <span m='77618'>the</span> <span m='77977'>execution</span>\
  \ <span m='78337'>of</span> <span m='78696'>fact(3),</span> <span m='79055'>we</span>\
  \ <span m='79415'>need</span> <span m='79774'>to</span> <span m='80133'>make</span>\
  \ <span m='80493'>a</span> <span m='80852'>recursive</span> <span m='81211'>call</span>\
  \ <span m='81571'>to</span> <span m='81930'>compute</span> <span m='82289'>fact(2).</span>\
  \ </p><p><span m='82649'>So</span> <span m='82967'>that</span> <span m='83285'>procedure</span>\
  \ <span m='83603'>call</span> <span m='83921'>also</span> <span m='84239'>gets</span>\
  \ <span m='84557'>an</span> <span m='84875'>activation</span> <span m='85193'>record</span>\
  \ <span m='85511'>with</span> <span m='85829'>the</span> <span m='86147'>appropriate</span>\
  \ <span m='86465'>values</span> <span m='86783'>for</span> <span m='87101'>the</span>\
  \ <span m='87420'>argument</span> <span m='88139'>and</span> <span m='88859'>return</span>\
  \ <span m='89579'>address.</span> </p><p><span m='90299'>Note</span> <span m='90646'>that</span>\
  \ <span m='90993'>the</span> <span m='91340'>original</span> <span m='91687'>activation</span>\
  \ <span m='92034'>record</span> <span m='92381'>is</span> <span m='92728'>kept</span>\
  \ <span m='93075'>since</span> <span m='93422'>it</span> <span m='93769'>contains</span>\
  \ <span m='94116'>information</span> <span m='94463'>needed</span> <span m='94810'>to</span>\
  \ <span m='95241'>complete</span> <span m='95673'>the</span> <span m='96105'>computation</span>\
  \ <span m='96536'>of</span> <span m='96968'>fact(3)</span> <span m='97400'>after</span>\
  \ <span m='97831'>the</span> <span m='98263'>call</span> <span m='98695'>to</span>\
  \ <span m='99126'>fact(2)</span> <span m='99558'>returns.</span> </p><p><span m='99990'>So</span>\
  \ <span m='100456'>now</span> <span m='100923'>we</span> <span m='101390'>have</span>\
  \ <span m='101857'>two</span> <span m='102324'>active</span> <span m='102791'>procedure</span>\
  \ <span m='103258'>calls</span> <span m='103725'>and</span> <span m='104192'>hence</span>\
  \ <span m='104659'>two</span> <span m='105126'>activation</span> <span m='105593'>records.</span>\
  \ </p><p><span m='106060'>fact(2)</span> <span m='106778'>requires</span> <span\
  \ m='107496'>computing</span> <span m='108214'>fact(1),</span> <span m='108932'>which,</span>\
  \ <span m='109650'>in</span> <span m='110368'>turn,</span> <span m='111086'>requires</span>\
  \ <span m='111804'>computing</span> <span m='112522'>fact(0).</span> </p><p><span\
  \ m='113240'>At</span> <span m='113689'>this</span> <span m='114138'>point</span>\
  \ <span m='114587'>there</span> <span m='115036'>are</span> <span m='115486'>four</span>\
  \ <span m='115935'>active</span> <span m='116384'>procedure</span> <span m='116833'>calls</span>\
  \ <span m='117282'>and</span> <span m='117732'>hence</span> <span m='118181'>four</span>\
  \ <span m='118630'>activation</span> <span m='119079'>records.</span> </p><p><span\
  \ m='119529'>The</span> <span m='119942'>recursion</span> <span m='120355'>terminates</span>\
  \ <span m='120768'>with</span> <span m='121181'>fact(0),</span> <span m='121594'>which</span>\
  \ <span m='122007'>returns</span> <span m='122420'>the</span> <span m='122833'>value</span>\
  \ <span m='123246'>1</span> <span m='123659'>to</span> <span m='124072'>its</span>\
  \ <span m='124485'>caller.</span> </p><p><span m='124899'>At</span> <span m='125241'>this</span>\
  \ <span m='125583'>point</span> <span m='125925'>we've</span> <span m='126267'>finished</span>\
  \ <span m='126609'>execution</span> <span m='126951'>of</span> <span m='127293'>fact(0)</span>\
  \ <span m='127635'>and</span> <span m='127977'>so</span> <span m='128319'>its</span>\
  \ <span m='128661'>activation</span> <span m='129003'>record</span> <span m='129345'>is</span>\
  \ <span m='129687'>no</span> <span m='130030'>longer</span> <span m='130494'>needed</span>\
  \ <span m='130959'>and</span> <span m='131424'>can</span> <span m='131889'>be</span>\
  \ <span m='132354'>discarded.</span> </p><p><span m='132819'>fact(1)</span> <span\
  \ m='133313'>now</span> <span m='133807'>finishes</span> <span m='134301'>its</span>\
  \ <span m='134795'>computation</span> <span m='135289'>returning</span> <span m='135783'>1</span>\
  \ <span m='136277'>to</span> <span m='136771'>its</span> <span m='137265'>caller.</span>\
  \ </p><p><span m='137760'>We</span> <span m='138172'>no</span> <span m='138585'>longer</span>\
  \ <span m='138998'>need</span> <span m='139411'>its</span> <span m='139824'>activation</span>\
  \ <span m='140237'>record.</span> </p><p><span m='140650'>Then</span> <span m='141053'>fact(2)</span>\
  \ <span m='141457'>completes,</span> <span m='141861'>returning</span> <span m='142265'>2</span>\
  \ <span m='142669'>to</span> <span m='143073'>its</span> <span m='143477'>caller</span>\
  \ <span m='143881'>and</span> <span m='144285'>its</span> <span m='144689'>activation</span>\
  \ <span m='145093'>record</span> <span m='145497'>can</span> <span m='145901'>be</span>\
  \ <span m='146305'>discarded.</span> </p><p><span m='146709'>And</span> <span m='147336'>so</span>\
  \ <span m='147963'>on\u2026</span> <span m='148590'>Note</span> <span m='148922'>that</span>\
  \ <span m='149255'>the</span> <span m='149588'>activation</span> <span m='149921'>record</span>\
  \ <span m='150254'>of</span> <span m='150587'>a</span> <span m='150920'>nested</span>\
  \ <span m='151252'>procedure</span> <span m='151585'>call</span> <span m='151918'>is</span>\
  \ <span m='152251'>always</span> <span m='152584'>discarded</span> <span m='152917'>before</span>\
  \ <span m='153250'>the</span> <span m='153724'>activation</span> <span m='154199'>record</span>\
  \ <span m='154674'>of</span> <span m='155149'>the</span> <span m='155624'>caller.</span>\
  \ </p><p><span m='156099'>That</span> <span m='156459'>makes</span> <span m='156819'>sense:</span>\
  \ <span m='157179'>the</span> <span m='157539'>execution</span> <span m='157899'>of</span>\
  \ <span m='158259'>the</span> <span m='158619'>caller</span> <span m='158979'>can't</span>\
  \ <span m='159339'>complete</span> <span m='159699'>until</span> <span m='160059'>the</span>\
  \ <span m='160419'>nested</span> <span m='160779'>procedure</span> <span m='161140'>call</span>\
  \ <span m='162104'>returns.</span> </p><p><span m='163069'>What</span> <span m='163395'>we</span>\
  \ <span m='163721'>need</span> <span m='164047'>is</span> <span m='164373'>a</span>\
  \ <span m='164699'>storage</span> <span m='165025'>scheme</span> <span m='165351'>that</span>\
  \ <span m='165677'>efficiently</span> <span m='166003'>supports</span> <span m='166329'>the</span>\
  \ <span m='166655'>allocation</span> <span m='166981'>and</span> <span m='167307'>deallocation</span>\
  \ <span m='167633'>of</span> <span m='167959'>activation</span> <span m='168547'>records</span>\
  \ <span m='169135'>as</span> <span m='169723'>shown</span> <span m='170311'>here.</span>\
  \ </p><p><span m='170900'>Early</span> <span m='171366'>compiler</span> <span m='171832'>writers</span>\
  \ <span m='172298'>recognized</span> <span m='172764'>that</span> <span m='173230'>activation</span>\
  \ <span m='173696'>records</span> <span m='174162'>are</span> <span m='174628'>allocated</span>\
  \ <span m='175094'>and</span> <span m='175560'>deallocated</span> <span m='176026'>in</span>\
  \ <span m='176492'>last-in</span> <span m='176959'>first-out</span> <span m='177659'>(LIFO)</span>\
  \ <span m='178359'>order.</span> </p><p><span m='179060'>So</span> <span m='179331'>they</span>\
  \ <span m='179603'>invented</span> <span m='179875'>the</span> <span m='180147'>\"\
  stack\",</span> <span m='180419'>a</span> <span m='180690'>data</span> <span m='180962'>structure</span>\
  \ <span m='181234'>that</span> <span m='181506'>implements</span> <span m='181778'>a</span>\
  \ <span m='182049'>PUSH</span> <span m='182321'>operation</span> <span m='182593'>to</span>\
  \ <span m='182865'>add</span> <span m='183137'>a</span> <span m='183409'>record</span>\
  \ <span m='183741'>to</span> <span m='184074'>the</span> <span m='184406'>top</span>\
  \ <span m='184739'>of</span> <span m='185071'>the</span> <span m='185404'>stack</span>\
  \ <span m='185736'>and</span> <span m='186069'>a</span> <span m='186402'>POP</span>\
  \ <span m='186734'>operation</span> <span m='187067'>to</span> <span m='187399'>remove</span>\
  \ <span m='187732'>the</span> <span m='188064'>top</span> <span m='188397'>element.</span>\
  \ </p><p><span m='188730'>New</span> <span m='189110'>activation</span> <span m='189490'>records</span>\
  \ <span m='189870'>are</span> <span m='190250'>PUSHed</span> <span m='190630'>onto</span>\
  \ <span m='191010'>the</span> <span m='191390'>stack</span> <span m='191770'>during</span>\
  \ <span m='192150'>procedure</span> <span m='192530'>calls</span> <span m='192910'>and</span>\
  \ <span m='193290'>the</span> <span m='193670'>POPed</span> <span m='194050'>from</span>\
  \ <span m='194481'>the</span> <span m='194912'>stack</span> <span m='195343'>when</span>\
  \ <span m='195775'>the</span> <span m='196206'>procedure</span> <span m='196637'>call</span>\
  \ <span m='197068'>returns.</span> </p><p><span m='197500'>Note</span> <span m='197963'>that</span>\
  \ <span m='198427'>stack</span> <span m='198890'>operations</span> <span m='199354'>affect</span>\
  \ <span m='199817'>the</span> <span m='200281'>top</span> <span m='200744'>(i.e.,</span>\
  \ <span m='201208'>most</span> <span m='201671'>recent)</span> <span m='202135'>record</span>\
  \ <span m='202598'>on</span> <span m='203062'>the</span> <span m='203525'>stack.</span>\
  \ </p><p><span m='203989'>C</span> <span m='204319'>procedures</span> <span m='204650'>only</span>\
  \ <span m='204981'>need</span> <span m='205312'>to</span> <span m='205643'>access</span>\
  \ <span m='205974'>the</span> <span m='206304'>top</span> <span m='206635'>activation</span>\
  \ <span m='206966'>record</span> <span m='207297'>on</span> <span m='207628'>the</span>\
  \ <span m='207959'>stack.</span> </p><p><span m='208290'>Other</span> <span m='208739'>programming</span>\
  \ <span m='209188'>languages,</span> <span m='209637'>e.g.</span> <span m='210086'>Java,</span>\
  \ <span m='210535'>support</span> <span m='210985'>accesses</span> <span m='211434'>to</span>\
  \ <span m='211883'>other</span> <span m='212332'>active</span> <span m='212781'>activation</span>\
  \ <span m='213230'>records.</span> </p><p><span m='213680'>The</span> <span m='214371'>stack</span>\
  \ <span m='215062'>supports</span> <span m='215753'>both</span> <span m='216445'>modes</span>\
  \ <span m='217136'>of</span> <span m='217827'>operation.</span> </p><p><span m='218519'>One</span>\
  \ <span m='219083'>final</span> <span m='219648'>technical</span> <span m='220212'>note:</span>\
  \ <span m='220777'>some</span> <span m='221342'>programming</span> <span m='221906'>languages</span>\
  \ <span m='222471'>support</span> <span m='223036'>closures</span> <span m='223600'>(e.g.,</span>\
  \ <span m='224165'>Javascript)</span> <span m='224730'>or</span> <span m='225252'>continuations</span>\
  \ <span m='225774'>(e.g.,</span> <span m='226296'>Python's</span> <span m='226818'>yield</span>\
  \ <span m='227340'>statement),</span> <span m='227862'>where</span> <span m='228385'>the</span>\
  \ <span m='228907'>activation</span> <span m='229429'>records</span> <span m='229951'>need</span>\
  \ <span m='230473'>to</span> <span m='230995'>be</span> <span m='231517'>preserved</span>\
  \ <span m='232040'>even</span> <span m='232573'>after</span> <span m='233107'>the</span>\
  \ <span m='233641'>procedure</span> <span m='234175'>returns.</span> </p><p><span\
  \ m='234709'>In</span> <span m='235069'>these</span> <span m='235430'>cases,</span>\
  \ <span m='235791'>the</span> <span m='236151'>simple</span> <span m='236512'>LIFO</span>\
  \ <span m='236873'>behavior</span> <span m='237233'>of</span> <span m='237594'>the</span>\
  \ <span m='237955'>stack</span> <span m='238315'>is</span> <span m='238676'>no</span>\
  \ <span m='239037'>longer</span> <span m='239397'>sufficient</span> <span m='239758'>and</span>\
  \ <span m='240119'>we'll</span> <span m='240480'>need</span> <span m='240911'>another</span>\
  \ <span m='241342'>scheme</span> <span m='241773'>for</span> <span m='242204'>allocating</span>\
  \ <span m='242635'>and</span> <span m='243066'>deallocating</span> <span m='243497'>activation</span>\
  \ <span m='243928'>records.</span> </p><p><span m='244359'>But</span> <span m='244806'>that's</span>\
  \ <span m='245253'>a</span> <span m='245700'>topic</span> <span m='246147'>for</span>\
  \ <span m='246594'>another</span> <span m='247041'>course!</span> </p><p><span m='247489'>Here's</span>\
  \ <span m='247853'>how</span> <span m='248217'>we'll</span> <span m='248582'>implement</span>\
  \ <span m='248946'>the</span> <span m='249311'>stack</span> <span m='249675'>on</span>\
  \ <span m='250040'>the</span> <span m='250404'>Beta:</span> <span m='250769'>We'll</span>\
  \ <span m='251079'>dedicate</span> <span m='251389'>one</span> <span m='251699'>of</span>\
  \ <span m='252009'>the</span> <span m='252319'>Beta</span> <span m='252629'>registers,</span>\
  \ <span m='252939'>R29,</span> <span m='253249'>to</span> <span m='253559'>be</span>\
  \ <span m='253869'>the</span> <span m='254179'>\"stack</span> <span m='254489'>pointer\"\
  </span> <span m='254799'>that</span> <span m='255109'>will</span> <span m='255419'>be</span>\
  \ <span m='255730'>used</span> <span m='256380'>to</span> <span m='257030'>manage</span>\
  \ <span m='257680'>stack</span> <span m='258330'>operations.</span> </p><p><span\
  \ m='258980'>When</span> <span m='259267'>we</span> <span m='259555'>PUSH</span>\
  \ <span m='259843'>a</span> <span m='260130'>word</span> <span m='260418'>onto</span>\
  \ <span m='260706'>the</span> <span m='260993'>stack,</span> <span m='261281'>we'll</span>\
  \ <span m='261569'>increment</span> <span m='261856'>the</span> <span m='262144'>stack</span>\
  \ <span m='262432'>pointer.</span> </p><p><span m='262720'>So</span> <span m='263149'>the</span>\
  \ <span m='263578'>stack</span> <span m='264008'>grows</span> <span m='264437'>to</span>\
  \ <span m='264866'>successively</span> <span m='265296'>higher</span> <span m='265725'>addresses</span>\
  \ <span m='266154'>as</span> <span m='266584'>words</span> <span m='267013'>are</span>\
  \ <span m='267442'>PUSHed</span> <span m='267872'>onto</span> <span m='268301'>the</span>\
  \ <span m='268730'>stack.</span> </p><p><span m='269160'>We'll</span> <span m='269517'>adopt</span>\
  \ <span m='269875'>the</span> <span m='270232'>convention</span> <span m='270590'>that</span>\
  \ <span m='270947'>SP</span> <span m='271305'>points</span> <span m='271662'>to</span>\
  \ <span m='272020'>(i.e.,</span> <span m='272377'>its</span> <span m='272735'>value</span>\
  \ <span m='273092'>is</span> <span m='273450'>the</span> <span m='273807'>address</span>\
  \ <span m='274165'>of)</span> <span m='274522'>the</span> <span m='274880'>first</span>\
  \ <span m='275319'>unused</span> <span m='275758'>stack</span> <span m='276197'>location,</span>\
  \ <span m='276636'>the</span> <span m='277076'>location</span> <span m='277515'>that</span>\
  \ <span m='277954'>will</span> <span m='278393'>be</span> <span m='278833'>filled</span>\
  \ <span m='279272'>by</span> <span m='279711'>next</span> <span m='280150'>PUSH.</span>\
  \ </p><p><span m='280590'>So</span> <span m='280921'>locations</span> <span m='281252'>with</span>\
  \ <span m='281584'>addresses</span> <span m='281915'>lower</span> <span m='282246'>than</span>\
  \ <span m='282578'>the</span> <span m='282909'>value</span> <span m='283240'>in</span>\
  \ <span m='283572'>SP</span> <span m='283903'>correspond</span> <span m='284234'>to</span>\
  \ <span m='284566'>words</span> <span m='284897'>that</span> <span m='285228'>have</span>\
  \ <span m='285560'>been</span> <span m='286413'>previously</span> <span m='287266'>allocated.</span>\
  \ </p><p><span m='288120'>Words</span> <span m='288427'>can</span> <span m='288734'>be</span>\
  \ <span m='289041'>PUSHed</span> <span m='289348'>to</span> <span m='289656'>or</span>\
  \ <span m='289963'>POPed</span> <span m='290270'>from</span> <span m='290577'>the</span>\
  \ <span m='290885'>stack</span> <span m='291192'>at</span> <span m='291499'>any</span>\
  \ <span m='291806'>point</span> <span m='292113'>in</span> <span m='292421'>execution,</span>\
  \ <span m='292728'>but</span> <span m='293035'>we'll</span> <span m='293342'>impose</span>\
  \ <span m='293650'>the</span> <span m='293959'>rule</span> <span m='294268'>that</span>\
  \ <span m='294578'>code</span> <span m='294887'>sequences</span> <span m='295196'>that</span>\
  \ <span m='295506'>PUSH</span> <span m='295815'>words</span> <span m='296124'>onto</span>\
  \ <span m='296434'>the</span> <span m='296743'>stack</span> <span m='297052'>must</span>\
  \ <span m='297362'>POP</span> <span m='297671'>those</span> <span m='297980'>words</span>\
  \ <span m='298290'>at</span> <span m='298599'>the</span> <span m='298909'>end</span>\
  \ <span m='299599'>of</span> <span m='300289'>execution.</span> </p><p><span m='300980'>So</span>\
  \ <span m='301319'>when</span> <span m='301658'>a</span> <span m='301998'>code</span>\
  \ <span m='302337'>sequence</span> <span m='302677'>finishes</span> <span m='303016'>execution,</span>\
  \ <span m='303355'>SP</span> <span m='303695'>will</span> <span m='304034'>have</span>\
  \ <span m='304374'>the</span> <span m='304713'>same</span> <span m='305052'>value</span>\
  \ <span m='305392'>as</span> <span m='305731'>it</span> <span m='306071'>had</span>\
  \ <span m='306410'>before</span> <span m='306750'>the</span> <span m='307523'>sequence</span>\
  \ <span m='308296'>started.</span> </p><p><span m='309070'>This</span> <span m='309412'>is</span>\
  \ <span m='309754'>called</span> <span m='310096'>the</span> <span m='310438'>\"\
  stack</span> <span m='310780'>discipline\"</span> <span m='311122'>and</span> <span\
  \ m='311465'>ensures</span> <span m='311807'>that</span> <span m='312149'>intervening</span>\
  \ <span m='312491'>uses</span> <span m='312833'>of</span> <span m='313175'>the</span>\
  \ <span m='313517'>stack</span> <span m='313860'>don't</span> <span m='314476'>affect</span>\
  \ <span m='315092'>later</span> <span m='315708'>stack</span> <span m='316324'>references.</span>\
  \ </p><p><span m='316940'>We'll</span> <span m='317252'>allocate</span> <span m='317565'>a</span>\
  \ <span m='317878'>large</span> <span m='318191'>region</span> <span m='318504'>of</span>\
  \ <span m='318817'>memory</span> <span m='319130'>to</span> <span m='319443'>hold</span>\
  \ <span m='319756'>the</span> <span m='320069'>stack</span> <span m='320382'>located</span>\
  \ <span m='320695'>so</span> <span m='321008'>that</span> <span m='321321'>the</span>\
  \ <span m='321634'>stack</span> <span m='321947'>can</span> <span m='322260'>grow</span>\
  \ <span m='322933'>without</span> <span m='323606'>overwriting</span> <span m='324280'>other</span>\
  \ <span m='324953'>program</span> <span m='325626'>storage.</span> </p><p><span\
  \ m='326300'>Most</span> <span m='326605'>systems</span> <span m='326911'>require</span>\
  \ <span m='327216'>that</span> <span m='327522'>you</span> <span m='327828'>specify</span>\
  \ <span m='328133'>a</span> <span m='328439'>maximum</span> <span m='328745'>stack</span>\
  \ <span m='329050'>size</span> <span m='329356'>when</span> <span m='329661'>running</span>\
  \ <span m='329967'>a</span> <span m='330273'>program</span> <span m='330578'>and</span>\
  \ <span m='330884'>will</span> <span m='331190'>signal</span> <span m='331666'>an</span>\
  \ <span m='332143'>execution</span> <span m='332620'>error</span> <span m='333097'>if</span>\
  \ <span m='333574'>the</span> <span m='334051'>program</span> <span m='334528'>attempts</span>\
  \ <span m='335005'>to</span> <span m='335481'>PUSH</span> <span m='335958'>too</span>\
  \ <span m='336435'>many</span> <span m='336912'>items</span> <span m='337389'>onto</span>\
  \ <span m='337866'>the</span> <span m='338343'>stack.</span> </p><p><span m='338820'>For</span>\
  \ <span m='339252'>our</span> <span m='339684'>Beta</span> <span m='340116'>stack</span>\
  \ <span m='340549'>implementation,</span> <span m='340981'>we'll</span> <span m='341413'>use</span>\
  \ <span m='341846'>existing</span> <span m='342278'>instructions</span> <span m='342710'>to</span>\
  \ <span m='343143'>implement</span> <span m='343575'>stack</span> <span m='344007'>operations,</span>\
  \ <span m='344440'>so</span> <span m='344826'>for</span> <span m='345213'>us</span>\
  \ <span m='345600'>the</span> <span m='345986'>stack</span> <span m='346373'>is</span>\
  \ <span m='346760'>strictly</span> <span m='347146'>a</span> <span m='347533'>set</span>\
  \ <span m='347920'>of</span> <span m='348306'>software</span> <span m='348693'>conventions.</span>\
  \ </p><p><span m='349080'>Other</span> <span m='349861'>ISAs</span> <span m='350642'>provide</span>\
  \ <span m='351423'>instructions</span> <span m='352205'>specifically</span> <span\
  \ m='352986'>for</span> <span m='353767'>stack</span> <span m='354548'>operations.</span>\
  \ </p><p><span m='355330'>There</span> <span m='355598'>are</span> <span m='355866'>many</span>\
  \ <span m='356134'>other</span> <span m='356402'>sensible</span> <span m='356670'>stack</span>\
  \ <span m='356938'>conventions,</span> <span m='357206'>so</span> <span m='357475'>you'll</span>\
  \ <span m='357743'>need</span> <span m='358011'>to</span> <span m='358279'>read</span>\
  \ <span m='358547'>up</span> <span m='358815'>on</span> <span m='359083'>the</span>\
  \ <span m='359351'>conventions</span> <span m='359620'>adopted</span> <span m='360095'>by</span>\
  \ <span m='360570'>the</span> <span m='361046'>particular</span> <span m='361521'>ISA</span>\
  \ <span m='361997'>or</span> <span m='362472'>programming</span> <span m='362948'>language</span>\
  \ <span m='363423'>you'll</span> <span m='363899'>be</span> <span m='364374'>using.</span>\
  \ </p><p><span m='364850'>We've</span> <span m='365343'>added</span> <span m='365836'>some</span>\
  \ <span m='366329'>convenience</span> <span m='366822'>macros</span> <span m='367315'>to</span>\
  \ <span m='367808'>UASM</span> <span m='368301'>to</span> <span m='368794'>support</span>\
  \ <span m='369287'>stacks.</span> </p><p><span m='369780'>The</span> <span m='370287'>PUSH</span>\
  \ <span m='370794'>macro</span> <span m='371301'>expands</span> <span m='371808'>into</span>\
  \ <span m='372315'>two</span> <span m='372822'>instructions.</span> </p><p><span\
  \ m='373330'>The</span> <span m='373663'>ADDC</span> <span m='373997'>increments</span>\
  \ <span m='374331'>the</span> <span m='374665'>stack</span> <span m='374999'>pointer,</span>\
  \ <span m='375333'>allocating</span> <span m='375667'>a</span> <span m='376001'>new</span>\
  \ <span m='376335'>word</span> <span m='376668'>at</span> <span m='377002'>the</span>\
  \ <span m='377336'>top</span> <span m='377670'>of</span> <span m='378004'>stack,</span>\
  \ <span m='378338'>and</span> <span m='378672'>then</span> <span m='379006'>initializes</span>\
  \ <span m='379340'>the</span> <span m='379800'>new</span> <span m='380260'>top-of-stack</span>\
  \ <span m='380720'>from</span> <span m='381180'>a</span> <span m='381640'>specified</span>\
  \ <span m='382100'>register</span> <span m='382560'>value</span> <span m='383020'>with</span>\
  \ <span m='383480'>a</span> <span m='383940'>ST</span> <span m='384400'>instruction.</span>\
  \ </p><p><span m='384860'>The</span> <span m='385143'>POP</span> <span m='385427'>macro</span>\
  \ <span m='385710'>LDs</span> <span m='385994'>the</span> <span m='386277'>value</span>\
  \ <span m='386561'>at</span> <span m='386844'>the</span> <span m='387128'>top</span>\
  \ <span m='387411'>of</span> <span m='387695'>the</span> <span m='387978'>stack</span>\
  \ <span m='388262'>into</span> <span m='388545'>the</span> <span m='388829'>specified</span>\
  \ <span m='389112'>register,</span> <span m='389396'>then</span> <span m='389680'>uses</span>\
  \ <span m='390153'>a</span> <span m='390626'>SUBC</span> <span m='391100'>instruction</span>\
  \ <span m='391573'>to</span> <span m='392046'>decrement</span> <span m='392520'>the</span>\
  \ <span m='392993'>stack</span> <span m='393466'>pointer,</span> <span m='393940'>deallocating</span>\
  \ <span m='394413'>that</span> <span m='394886'>word</span> <span m='395360'>from</span>\
  \ <span m='395833'>the</span> <span m='396306'>stack.</span> </p><p><span m='396780'>Note</span>\
  \ <span m='397058'>that</span> <span m='397337'>the</span> <span m='397616'>order</span>\
  \ <span m='397895'>of</span> <span m='398173'>the</span> <span m='398452'>instructions</span>\
  \ <span m='398731'>in</span> <span m='399010'>the</span> <span m='399288'>PUSH</span>\
  \ <span m='399567'>and</span> <span m='399846'>POP</span> <span m='400125'>macro</span>\
  \ <span m='400403'>is</span> <span m='400682'>very</span> <span m='400961'>important.</span>\
  \ </p><p><span m='401240'>As</span> <span m='401570'>we'll</span> <span m='401900'>see</span>\
  \ <span m='402230'>in</span> <span m='402560'>the</span> <span m='402890'>next</span>\
  \ <span m='403220'>lecture,</span> <span m='403550'>interrupts</span> <span m='403880'>can</span>\
  \ <span m='404210'>cause</span> <span m='404540'>the</span> <span m='404870'>Beta</span>\
  \ <span m='405200'>hardware</span> <span m='405530'>to</span> <span m='405860'>stop</span>\
  \ <span m='406190'>executing</span> <span m='406520'>the</span> <span m='406865'>current</span>\
  \ <span m='407211'>program</span> <span m='407557'>between</span> <span m='407903'>any</span>\
  \ <span m='408249'>two</span> <span m='408595'>instructions,</span> <span m='408941'>so</span>\
  \ <span m='409287'>we</span> <span m='409632'>have</span> <span m='409978'>to</span>\
  \ <span m='410324'>be</span> <span m='410670'>careful</span> <span m='411016'>about</span>\
  \ <span m='411362'>the</span> <span m='411708'>order</span> <span m='412054'>of</span>\
  \ <span m='412400'>operations.</span> </p><p><span m='413560'>So</span> <span m='413943'>for</span>\
  \ <span m='414327'>PUSH,</span> <span m='414710'>we</span> <span m='415094'>first</span>\
  \ <span m='415477'>allocate</span> <span m='415861'>the</span> <span m='416245'>word</span>\
  \ <span m='416628'>on</span> <span m='417012'>the</span> <span m='417395'>stack,</span>\
  \ <span m='417779'>then</span> <span m='418162'>initialize</span> <span m='418546'>it.</span>\
  \ </p><p><span m='418930'>If</span> <span m='419263'>we</span> <span m='419596'>did</span>\
  \ <span m='419930'>it</span> <span m='420263'>the</span> <span m='420596'>other</span>\
  \ <span m='420930'>way</span> <span m='421263'>around</span> <span m='421596'>and</span>\
  \ <span m='421930'>execution</span> <span m='422263'>was</span> <span m='422596'>interrupted</span>\
  \ <span m='422930'>between</span> <span m='423263'>the</span> <span m='423596'>initialization</span>\
  \ <span m='423930'>and</span> <span m='424343'>allocation,</span> <span m='424757'>code</span>\
  \ <span m='425171'>run</span> <span m='425585'>during</span> <span m='425999'>the</span>\
  \ <span m='426413'>interrupt</span> <span m='426826'>which</span> <span m='427240'>uses</span>\
  \ <span m='427654'>the</span> <span m='428068'>stack</span> <span m='428482'>might</span>\
  \ <span m='428896'>unintentionally</span> <span m='429310'>overwrite</span> <span\
  \ m='429942'>the</span> <span m='430575'>initialized</span> <span m='431207'>value.</span>\
  \ </p><p><span m='431840'>But,</span> <span m='432346'>assuming</span> <span m='432853'>all</span>\
  \ <span m='433360'>code</span> <span m='433867'>follows</span> <span m='434374'>stack</span>\
  \ <span m='434881'>discipline,</span> <span m='435388'>allocation</span> <span m='435895'>followed</span>\
  \ <span m='436402'>by</span> <span m='436909'>initialization</span> <span m='437416'>is</span>\
  \ <span m='437923'>always</span> <span m='438430'>safe.</span> </p><p><span m='439460'>The</span>\
  \ <span m='439829'>same</span> <span m='440198'>reasoning</span> <span m='440567'>applies</span>\
  \ <span m='440936'>to</span> <span m='441305'>the</span> <span m='441674'>order</span>\
  \ <span m='442043'>of</span> <span m='442412'>the</span> <span m='442781'>POP</span>\
  \ <span m='443150'>instructions.</span> </p><p><span m='443520'>We</span> <span\
  \ m='443931'>first</span> <span m='444342'>access</span> <span m='444754'>the</span>\
  \ <span m='445165'>top-of-stack</span> <span m='445576'>one</span> <span m='445988'>last</span>\
  \ <span m='446399'>time</span> <span m='446810'>to</span> <span m='447222'>retrieve</span>\
  \ <span m='447633'>its</span> <span m='448044'>value,</span> <span m='448456'>then</span>\
  \ <span m='448867'>we</span> <span m='449278'>deallocate</span> <span m='449690'>that</span>\
  \ <span m='451049'>location.</span> </p><p><span m='452409'>We</span> <span m='452696'>can</span>\
  \ <span m='452984'>use</span> <span m='453271'>the</span> <span m='453559'>ALLOCATE</span>\
  \ <span m='453846'>macro</span> <span m='454134'>to</span> <span m='454421'>reserve</span>\
  \ <span m='454709'>a</span> <span m='454997'>number</span> <span m='455284'>of</span>\
  \ <span m='455572'>stack</span> <span m='455859'>locations</span> <span m='456147'>for</span>\
  \ <span m='456434'>later</span> <span m='456722'>use.</span> </p><p><span m='457010'>Sort</span>\
  \ <span m='457657'>of</span> <span m='458305'>like</span> <span m='458952'>PUSH</span>\
  \ <span m='459600'>but</span> <span m='460247'>without</span> <span m='460895'>the</span>\
  \ <span m='461542'>initialization.</span> </p><p><span m='462190'>DEALLOCATE</span>\
  \ <span m='462555'>performs</span> <span m='462920'>the</span> <span m='463286'>opposite</span>\
  \ <span m='463651'>operation,</span> <span m='464017'>removing</span> <span m='464382'>N</span>\
  \ <span m='464748'>words</span> <span m='465113'>from</span> <span m='465479'>the</span>\
  \ <span m='465844'>stack.</span> </p><p><span m='466210'>In</span> <span m='466519'>general,</span>\
  \ <span m='466828'>if</span> <span m='467138'>we</span> <span m='467447'>see</span>\
  \ <span m='467757'>a</span> <span m='468066'>PUSH</span> <span m='468375'>or</span>\
  \ <span m='468685'>ALLOCATE</span> <span m='468994'>in</span> <span m='469304'>an</span>\
  \ <span m='469613'>assembly</span> <span m='469922'>language</span> <span m='470232'>program,</span>\
  \ <span m='470541'>we</span> <span m='470851'>should</span> <span m='471160'>be</span>\
  \ <span m='471470'>able</span> <span m='471854'>to</span> <span m='472238'>find</span>\
  \ <span m='472622'>the</span> <span m='473007'>corresponding</span> <span m='473391'>POP</span>\
  \ <span m='473775'>or</span> <span m='474160'>DEALLOCATE,</span> <span m='474544'>which</span>\
  \ <span m='474928'>would</span> <span m='475312'>indicate</span> <span m='475697'>that</span>\
  \ <span m='476081'>stack</span> <span m='476465'>discipline</span> <span m='476850'>is</span>\
  \ <span m='477504'>maintained.</span> </p><p><span m='478159'>We'll</span> <span\
  \ m='478624'>use</span> <span m='479090'>stacks</span> <span m='479556'>to</span>\
  \ <span m='480021'>save</span> <span m='480487'>values</span> <span m='480953'>we'll</span>\
  \ <span m='481418'>need</span> <span m='481884'>later.</span> </p><p><span m='482350'>For</span>\
  \ <span m='482622'>example,</span> <span m='482895'>if</span> <span m='483168'>we</span>\
  \ <span m='483441'>need</span> <span m='483713'>to</span> <span m='483986'>use</span>\
  \ <span m='484259'>some</span> <span m='484532'>registers</span> <span m='484805'>for</span>\
  \ <span m='485077'>a</span> <span m='485350'>computation</span> <span m='485623'>but</span>\
  \ <span m='485896'>don't</span> <span m='486168'>know</span> <span m='486441'>if</span>\
  \ <span m='486714'>the</span> <span m='486987'>register's</span> <span m='487260'>current</span>\
  \ <span m='487563'>values</span> <span m='487867'>are</span> <span m='488171'>needed</span>\
  \ <span m='488475'>later</span> <span m='488778'>in</span> <span m='489082'>the</span>\
  \ <span m='489386'>program,</span> <span m='489690'>we</span> <span m='489993'>can</span>\
  \ <span m='490297'>PUSH</span> <span m='490601'>their</span> <span m='490905'>current</span>\
  \ <span m='491208'>values</span> <span m='491512'>onto</span> <span m='491816'>the</span>\
  \ <span m='492120'>stack</span> <span m='492485'>and</span> <span m='492850'>then</span>\
  \ <span m='493215'>are</span> <span m='493580'>free</span> <span m='493945'>to</span>\
  \ <span m='494310'>use</span> <span m='494675'>the</span> <span m='495040'>registers</span>\
  \ <span m='495405'>in</span> <span m='495770'>our</span> <span m='496135'>code.</span>\
  \ </p><p><span m='496500'>After</span> <span m='496913'>we're</span> <span m='497326'>done,</span>\
  \ <span m='497740'>we</span> <span m='498153'>can</span> <span m='498566'>use</span>\
  \ <span m='498980'>POP</span> <span m='499393'>to</span> <span m='499806'>restore</span>\
  \ <span m='500220'>the</span> <span m='500633'>saved</span> <span m='501046'>values.</span>\
  \ </p><p><span m='501460'>Note</span> <span m='501797'>that</span> <span m='502134'>we</span>\
  \ <span m='502471'>POP</span> <span m='502808'>data</span> <span m='503146'>off</span>\
  \ <span m='503483'>the</span> <span m='503820'>stack</span> <span m='504157'>in</span>\
  \ <span m='504495'>the</span> <span m='504832'>opposite</span> <span m='505169'>order</span>\
  \ <span m='505506'>that</span> <span m='505843'>the</span> <span m='506181'>data</span>\
  \ <span m='506518'>was</span> <span m='506855'>PUSHed,</span> <span m='507192'>i.e.,</span>\
  \ <span m='507530'>we</span> <span m='507970'>need</span> <span m='508410'>to</span>\
  \ <span m='508850'>follow</span> <span m='509290'>the</span> <span m='509730'>last-in</span>\
  \ <span m='510170'>first-out</span> <span m='510610'>discipline</span> <span m='511050'>imposed</span>\
  \ <span m='511490'>by</span> <span m='511930'>the</span> <span m='512370'>stack</span>\
  \ <span m='512810'>operations.</span> </p><p><span m='513250'>Now</span> <span m='513493'>that</span>\
  \ <span m='513737'>we</span> <span m='513980'>have</span> <span m='514224'>the</span>\
  \ <span m='514467'>stack</span> <span m='514711'>data</span> <span m='514954'>structure,</span>\
  \ <span m='515198'>we'll</span> <span m='515441'>use</span> <span m='515685'>it</span>\
  \ <span m='515928'>to</span> <span m='516172'>solve</span> <span m='516415'>our</span>\
  \ <span m='516659'>problems</span> <span m='516902'>with</span> <span m='517146'>allocating</span>\
  \ <span m='517390'>and</span> <span m='517828'>deallocating</span> <span m='518266'>activation</span>\
  \ <span m='518705'>records</span> <span m='519143'>during</span> <span m='519582'>procedure</span>\
  \ <span m='520020'>calls.</span> </p>"
type: course
uid: cc2609802a51f685313aba4a613d7e55

---
None