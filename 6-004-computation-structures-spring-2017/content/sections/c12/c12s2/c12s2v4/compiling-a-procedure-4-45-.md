---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: -Zg3fxOmjVs
  parent_uid: 64a9f24a0cc188f72c055a3d4acdc0c8
  title: Video-YouTube-Stream
  type: Video
  uid: e5cb47589dfad42233707ea705ddecb8
- id: 3Play-3Play YouTube id-Stream
  media_location: -Zg3fxOmjVs
  parent_uid: 64a9f24a0cc188f72c055a3d4acdc0c8
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: e6f8e5cee9858994ce6cbbc6bc9a8929
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/-Zg3fxOmjVs/default.jpg
  parent_uid: 64a9f24a0cc188f72c055a3d4acdc0c8
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 0de5dc5b40d74088dcf4413801c626f9
- id: -Zg3fxOmjVs.srt
  parent_uid: 64a9f24a0cc188f72c055a3d4acdc0c8
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v4/compiling-a-procedure-4-45-/-Zg3fxOmjVs.srt
  title: 3play caption file
  type: null
  uid: 9d8ea437dd42e4d620c5566a59ca752f
- id: -Zg3fxOmjVs.pdf
  parent_uid: 64a9f24a0cc188f72c055a3d4acdc0c8
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v4/compiling-a-procedure-4-45-/-Zg3fxOmjVs.pdf
  title: 3play pdf file
  type: null
  uid: 16b22a4b7bebce282212926947cd6e75
- id: Caption-3Play YouTube id-SRT
  parent_uid: 64a9f24a0cc188f72c055a3d4acdc0c8
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 7bde4c5a59bc99dc29f6d85fdb5ada90
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 64a9f24a0cc188f72c055a3d4acdc0c8
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: fa435d0bbb7ad5f99ead0521834649ec
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_12-02-04_300k.mp4
  parent_uid: 64a9f24a0cc188f72c055a3d4acdc0c8
  title: Video-Internet Archive-MP4
  type: Video
  uid: b649022368acc2c7185878366af337b4
inline_embed_id: 68908981compilingaprocedure44593233770
layout: video
order_index: null
parent_uid: 44482b91529fd27535194813a492816b
related_resources_text: ''
short_url: compiling-a-procedure-4-45-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v4/compiling-a-procedure-4-45-
template_type: Embed
title: Compiling a Procedure (4:45)
transcript: <p><span m='919'>Okay,</span> <span m='1346'>here's</span> <span m='1773'>our</span>
  <span m='2201'>final</span> <span m='2628'>contract</span> <span m='3055'>for</span>
  <span m='3483'>how</span> <span m='3910'>procedure</span> <span m='4337'>calls</span>
  <span m='4765'>will</span> <span m='5192'>work:</span> <span m='5620'>The</span>
  <span m='5990'>calling</span> <span m='6361'>procedure</span> <span m='6732'>("caller")</span>
  <span m='7103'>will</span> <span m='7473'>PUSH</span> <span m='7844'>the</span>
  <span m='8215'>argument</span> <span m='8586'>values</span> <span m='8956'>onto</span>
  <span m='9327'>the</span> <span m='9698'>stack</span> <span m='10069'>in</span>
  <span m='10440'>reverse</span> <span m='10780'>order</span> <span m='11121'>Branch</span>
  <span m='11462'>to</span> <span m='11803'>the</span> <span m='12144'>entry</span>
  <span m='12485'>point</span> <span m='12826'>of</span> <span m='13167'>the</span>
  <span m='13508'>callee,</span> <span m='13849'>putting</span> <span m='14190'>the</span>
  <span m='14682'>return</span> <span m='15175'>address</span> <span m='15668'>into</span>
  <span m='16161'>the</span> <span m='16654'>linkage</span> <span m='17147'>pointer.</span>
  </p><p><span m='17640'>When</span> <span m='18129'>the</span> <span m='18619'>callee</span>
  <span m='19109'>returns,</span> <span m='19599'>remove</span> <span m='20089'>the</span>
  <span m='20579'>argument</span> <span m='21069'>values</span> <span m='21559'>from</span>
  <span m='22049'>the</span> <span m='22539'>stack.</span> </p><p><span m='23029'>The</span>
  <span m='23517'>called</span> <span m='24005'>procedure</span> <span m='24493'>("callee")</span>
  <span m='24981'>will</span> <span m='25469'>Perform</span> <span m='25957'>the</span>
  <span m='26445'>promised</span> <span m='26933'>computation,</span> <span m='27421'>leaving</span>
  <span m='27910'>the</span> <span m='28427'>result</span> <span m='28945'>in</span>
  <span m='29462'>R0.</span> </p><p><span m='29980'>Jump</span> <span m='30399'>to</span>
  <span m='30818'>the</span> <span m='31237'>return</span> <span m='31656'>address</span>
  <span m='32075'>when</span> <span m='32494'>the</span> <span m='32913'>computation</span>
  <span m='33332'>has</span> <span m='33751'>finished</span> <span m='34170'>Remove</span>
  <span m='34453'>any</span> <span m='34736'>items</span> <span m='35019'>it</span>
  <span m='35303'>has</span> <span m='35586'>placed</span> <span m='35869'>on</span>
  <span m='36152'>the</span> <span m='36436'>stack,</span> <span m='36719'>leaving</span>
  <span m='37002'>the</span> <span m='37286'>stack</span> <span m='37569'>as</span>
  <span m='37852'>it</span> <span m='38135'>was</span> <span m='38419'>when</span>
  <span m='38702'>the</span> <span m='38985'>procedure</span> <span m='39269'>was</span>
  <span m='40179'>entered.</span> </p><p><span m='41089'>Note</span> <span m='41335'>that</span>
  <span m='41582'>the</span> <span m='41829'>arguments</span> <span m='42076'>were</span>
  <span m='42323'>PUSHed</span> <span m='42570'>on</span> <span m='42817'>the</span>
  <span m='43064'>stack</span> <span m='43311'>by</span> <span m='43557'>the</span>
  <span m='43804'>caller,</span> <span m='44051'>so</span> <span m='44298'>it</span>
  <span m='44545'>will</span> <span m='44792'>be</span> <span m='45039'>up</span>
  <span m='45286'>to</span> <span m='45533'>the</span> <span m='45780'>caller</span>
  <span m='46344'>to</span> <span m='46909'>remove</span> <span m='47474'>them.</span>
  </p><p><span m='48039'>Preserve</span> <span m='48419'>the</span> <span m='48800'>values</span>
  <span m='49181'>in</span> <span m='49562'>all</span> <span m='49942'>registers</span>
  <span m='50323'>except</span> <span m='50704'>R0,</span> <span m='51085'>which</span>
  <span m='51465'>holds</span> <span m='51846'>the</span> <span m='52227'>return</span>
  <span m='52608'>value.</span> </p><p><span m='52989'>So</span> <span m='53305'>the</span>
  <span m='53621'>caller</span> <span m='53937'>can</span> <span m='54254'>assume</span>
  <span m='54570'>any</span> <span m='54886'>values</span> <span m='55203'>placed</span>
  <span m='55519'>in</span> <span m='55835'>registers</span> <span m='56152'>before</span>
  <span m='56468'>a</span> <span m='56784'>nested</span> <span m='57101'>call</span>
  <span m='57417'>will</span> <span m='57733'>be</span> <span m='58050'>there</span>
  <span m='58854'>when</span> <span m='59659'>the</span> <span m='60464'>nested</span>
  <span m='61269'>call</span> <span m='62074'>returns.</span> </p><p><span m='62879'>We</span>
  <span m='63272'>saw</span> <span m='63665'>the</span> <span m='64059'>code</span>
  <span m='64452'>template</span> <span m='64846'>for</span> <span m='65239'>procedure</span>
  <span m='65632'>calls</span> <span m='66026'>on</span> <span m='66419'>an</span>
  <span m='66813'>earlier</span> <span m='67206'>slide.</span> </p><p><span m='67600'>Here's</span>
  <span m='67928'>the</span> <span m='68256'>template</span> <span m='68584'>for</span>
  <span m='68912'>the</span> <span m='69240'>entry</span> <span m='69569'>point</span>
  <span m='69897'>to</span> <span m='70225'>a</span> <span m='70553'>procedure</span>
  <span m='70881'>F.</span> </p><p><span m='71210'>The</span> <span m='71636'>code</span>
  <span m='72062'>saves</span> <span m='72488'>the</span> <span m='72915'>caller's</span>
  <span m='73341'>LP</span> <span m='73767'>and</span> <span m='74193'>BP</span> <span
  m='74620'>values,</span> <span m='75046'>initializes</span> <span m='75472'>BP</span>
  <span m='75898'>for</span> <span m='76325'>the</span> <span m='76751'>current</span>
  <span m='77177'>stack</span> <span m='77603'>frame</span> <span m='78030'>and</span>
  <span m='78451'>allocates</span> <span m='78873'>words</span> <span m='79295'>on</span>
  <span m='79716'>the</span> <span m='80138'>stack</span> <span m='80560'>to</span>
  <span m='80981'>hold</span> <span m='81403'>any</span> <span m='81825'>local</span>
  <span m='82246'>variable</span> <span m='82668'>values.</span> </p><p><span m='83090'>The</span>
  <span m='83392'>final</span> <span m='83695'>step</span> <span m='83998'>is</span>
  <span m='84300'>to</span> <span m='84603'>PUSH</span> <span m='84906'>the</span>
  <span m='85209'>value</span> <span m='85511'>of</span> <span m='85814'>any</span>
  <span m='86117'>registers</span> <span m='86419'>(besides</span> <span m='86722'>R0)</span>
  <span m='87025'>that</span> <span m='87328'>will</span> <span m='87630'>be</span>
  <span m='87933'>used</span> <span m='88236'>by</span> <span m='88539'>the</span>
  <span m='89125'>remainder</span> <span m='89712'>of</span> <span m='90299'>the</span>
  <span m='90886'>procedure's</span> <span m='91473'>code.</span> </p><p><span m='92060'>The</span>
  <span m='92442'>template</span> <span m='92824'>for</span> <span m='93206'>the</span>
  <span m='93588'>exit</span> <span m='93970'>sequence</span> <span m='94352'>mirrors</span>
  <span m='94734'>the</span> <span m='95116'>actions</span> <span m='95498'>of</span>
  <span m='95880'>the</span> <span m='96262'>entry</span> <span m='96644'>sequence,</span>
  <span m='97026'>restoring</span> <span m='97408'>all</span> <span m='97742'>the</span>
  <span m='98076'>values</span> <span m='98410'>saved</span> <span m='98744'>by</span>
  <span m='99078'>the</span> <span m='99412'>entry</span> <span m='99746'>sequence,</span>
  <span m='100081'>performing</span> <span m='100415'>the</span> <span m='100749'>POP</span>
  <span m='101083'>operations</span> <span m='101417'>in</span> <span m='101751'>the</span>
  <span m='102085'>reverse</span> <span m='102420'>of</span> <span m='102868'>the</span>
  <span m='103316'>order</span> <span m='103764'>of</span> <span m='104212'>the</span>
  <span m='104660'>PUSH</span> <span m='105109'>operations</span> <span m='105557'>in</span>
  <span m='106005'>the</span> <span m='106453'>entry</span> <span m='106901'>sequence.</span>
  </p><p><span m='107350'>Note</span> <span m='107655'>that</span> <span m='107960'>in</span>
  <span m='108265'>moving</span> <span m='108570'>the</span> <span m='108876'>BP</span>
  <span m='109181'>value</span> <span m='109486'>into</span> <span m='109791'>SP</span>
  <span m='110096'>we've</span> <span m='110402'>reset</span> <span m='110707'>the</span>
  <span m='111012'>stack</span> <span m='111317'>to</span> <span m='111622'>its</span>
  <span m='111928'>state</span> <span m='112233'>at</span> <span m='112538'>the</span>
  <span m='112843'>point</span> <span m='113149'>of</span> <span m='113646'>the</span>
  <span m='114143'>MOVE(SP,BP)</span> <span m='114640'>in</span> <span m='115138'>the</span>
  <span m='115635'>entry</span> <span m='116132'>sequence.</span> </p><p><span m='116630'>This</span>
  <span m='116943'>implicitly</span> <span m='117256'>undoes</span> <span m='117569'>the</span>
  <span m='117882'>effect</span> <span m='118195'>of</span> <span m='118508'>the</span>
  <span m='118821'>ALLOCATE</span> <span m='119135'>statement</span> <span m='119448'>in</span>
  <span m='119761'>the</span> <span m='120074'>entry</span> <span m='120387'>sequence,</span>
  <span m='120700'>so</span> <span m='121013'>we</span> <span m='121326'>don't</span>
  <span m='121640'>need</span> <span m='122171'>a</span> <span m='122702'>matching</span>
  <span m='123233'>DEALLOCATE</span> <span m='123764'>in</span> <span m='124295'>the</span>
  <span m='124826'>exit</span> <span m='125357'>sequence.</span> </p><p><span m='125889'>The</span>
  <span m='126352'>last</span> <span m='126816'>instruction</span> <span m='127279'>in</span>
  <span m='127743'>the</span> <span m='128207'>exit</span> <span m='128670'>sequence</span>
  <span m='129134'>transfers</span> <span m='129598'>control</span> <span m='130061'>back</span>
  <span m='130525'>to</span> <span m='130989'>the</span> <span m='131452'>calling</span>
  <span m='131916'>procedure.</span> </p><p><span m='132380'>With</span> <span m='132696'>practice</span>
  <span m='133013'>you'll</span> <span m='133330'>become</span> <span m='133646'>familiar</span>
  <span m='133963'>with</span> <span m='134280'>these</span> <span m='134596'>code</span>
  <span m='134913'>templates.</span> </p><p><span m='135230'>Meanwhile,</span> <span
  m='135515'>you</span> <span m='135801'>can</span> <span m='136087'>refer</span>
  <span m='136373'>back</span> <span m='136659'>to</span> <span m='136945'>this</span>
  <span m='137231'>slide</span> <span m='137517'>whenever</span> <span m='137802'>you</span>
  <span m='138088'>need</span> <span m='138374'>to</span> <span m='138660'>generate</span>
  <span m='138946'>code</span> <span m='139232'>for</span> <span m='139518'>a</span>
  <span m='139804'>procedure</span> <span m='140090'>call.</span> </p><p><span m='141400'>Here's</span>
  <span m='141715'>the</span> <span m='142031'>code</span> <span m='142346'>our</span>
  <span m='142662'>compiler</span> <span m='142978'>would</span> <span m='143293'>generate</span>
  <span m='143609'>for</span> <span m='143925'>the</span> <span m='144240'>C</span>
  <span m='144556'>implementation</span> <span m='144872'>of</span> <span m='145187'>factorial</span>
  <span m='145503'>shown</span> <span m='145819'>on</span> <span m='146349'>the</span>
  <span m='146879'>left.</span> </p><p><span m='147410'>The</span> <span m='147792'>entry</span>
  <span m='148175'>sequence</span> <span m='148557'>saves</span> <span m='148940'>the</span>
  <span m='149322'>caller's</span> <span m='149705'>LP</span> <span m='150087'>and</span>
  <span m='150470'>BP,</span> <span m='150852'>then</span> <span m='151235'>initializes</span>
  <span m='151617'>BP</span> <span m='152000'>for</span> <span m='152382'>the</span>
  <span m='152765'>current</span> <span m='153147'>stack</span> <span m='153530'>frame.</span>
  </p><p><span m='154900'>The</span> <span m='155238'>value</span> <span m='155576'>of</span>
  <span m='155914'>R1</span> <span m='156252'>is</span> <span m='156590'>saved</span>
  <span m='156928'>so</span> <span m='157266'>we</span> <span m='157604'>can</span>
  <span m='157942'>use</span> <span m='158280'>R1</span> <span m='158618'>in</span>
  <span m='158956'>code</span> <span m='159294'>that</span> <span m='159632'>follows.</span>
  </p><p><span m='159970'>The</span> <span m='160373'>exit</span> <span m='160776'>sequence</span>
  <span m='161180'>restores</span> <span m='161583'>all</span> <span m='161986'>the</span>
  <span m='162390'>saved</span> <span m='162793'>values,</span> <span m='163196'>including</span>
  <span m='163600'>that</span> <span m='164003'>for</span> <span m='164406'>R1.</span>
  </p><p><span m='164810'>The</span> <span m='165102'>code</span> <span m='165394'>for</span>
  <span m='165687'>the</span> <span m='165979'>body</span> <span m='166271'>of</span>
  <span m='166564'>the</span> <span m='166856'>procedure</span> <span m='167148'>has</span>
  <span m='167441'>arranged</span> <span m='167733'>for</span> <span m='168025'>R0</span>
  <span m='168318'>to</span> <span m='168610'>contain</span> <span m='168902'>the</span>
  <span m='169195'>return</span> <span m='169487'>value</span> <span m='169780'>by</span>
  <span m='170286'>the</span> <span m='170792'>time</span> <span m='171298'>execution</span>
  <span m='171804'>reaches</span> <span m='172310'>the</span> <span m='172816'>exit</span>
  <span m='173322'>sequence.</span> </p><p><span m='173829'>The</span> <span m='174113'>nested</span>
  <span m='174397'>procedure</span> <span m='174682'>call</span> <span m='174966'>passes</span>
  <span m='175251'>the</span> <span m='175535'>argument</span> <span m='175820'>value</span>
  <span m='176104'>on</span> <span m='176388'>the</span> <span m='176673'>stack</span>
  <span m='176957'>and</span> <span m='177242'>removes</span> <span m='177526'>it</span>
  <span m='177811'>after</span> <span m='178095'>the</span> <span m='178380'>nested</span>
  <span m='179303'>call</span> <span m='180226'>returns.</span> </p><p><span m='181150'>The</span>
  <span m='181445'>remainder</span> <span m='181741'>of</span> <span m='182036'>the</span>
  <span m='182332'>code</span> <span m='182627'>is</span> <span m='182923'>generated</span>
  <span m='183218'>using</span> <span m='183514'>the</span> <span m='183810'>templates</span>
  <span m='184105'>we</span> <span m='184401'>saw</span> <span m='184696'>in</span>
  <span m='184992'>the</span> <span m='185287'>previous</span> <span m='185583'>lecture.</span>
  </p><p><span m='185879'>Aside</span> <span m='186263'>from</span> <span m='186648'>computing</span>
  <span m='187032'>and</span> <span m='187417'>pushing</span> <span m='187802'>the</span>
  <span m='188186'>values</span> <span m='188571'>of</span> <span m='188955'>the</span>
  <span m='189340'>arguments,</span> <span m='189725'>there</span> <span m='190109'>are</span>
  <span m='190494'>approximately</span> <span m='190879'>10</span> <span m='191299'>instructions</span>
  <span m='191719'>needed</span> <span m='192139'>to</span> <span m='192559'>implement</span>
  <span m='192979'>the</span> <span m='193399'>linking</span> <span m='193819'>approach</span>
  <span m='194239'>to</span> <span m='194659'>a</span> <span m='195079'>procedure</span>
  <span m='195499'>call.</span> </p><p><span m='195920'>That's</span> <span m='196253'>not</span>
  <span m='196587'>much</span> <span m='196920'>for</span> <span m='197254'>a</span>
  <span m='197587'>procedure</span> <span m='197921'>of</span> <span m='198254'>any</span>
  <span m='198588'>size,</span> <span m='198921'>but</span> <span m='199255'>might</span>
  <span m='199588'>be</span> <span m='199922'>significant</span> <span m='200255'>for</span>
  <span m='200589'>a</span> <span m='200922'>trivial</span> <span m='201256'>procedure.</span>
  </p><p><span m='201590'>As</span> <span m='202024'>mentioned</span> <span m='202458'>earlier,</span>
  <span m='202892'>some</span> <span m='203327'>optimizing</span> <span m='203761'>compilers</span>
  <span m='204195'>can</span> <span m='204630'>make</span> <span m='205064'>the</span>
  <span m='205498'>tradeoff</span> <span m='205932'>of</span> <span m='206367'>inlining</span>
  <span m='206801'>small</span> <span m='207235'>non-recursive</span> <span m='207670'>procedures</span>
  <span m='208352'>saving</span> <span m='209035'>this</span> <span m='209718'>small</span>
  <span m='210401'>amount</span> <span m='211084'>of</span> <span m='211767'>overhead.</span>
  </p><p><span m='212450'>So</span> <span m='212935'>have</span> <span m='213421'>we</span>
  <span m='213907'>solved</span> <span m='214393'>the</span> <span m='214879'>activation</span>
  <span m='215365'>record</span> <span m='215850'>storage</span> <span m='216336'>issue</span>
  <span m='216822'>for</span> <span m='217308'>recursive</span> <span m='217794'>procedures?</span>
  </p><p><span m='218280'>Yes!</span> </p><p><span m='219280'>A</span> <span m='219661'>new</span>
  <span m='220043'>stack</span> <span m='220425'>from</span> <span m='220807'>is</span>
  <span m='221189'>allocated</span> <span m='221571'>for</span> <span m='221953'>each</span>
  <span m='222335'>procedure</span> <span m='222717'>call.</span> </p><p><span m='223099'>In</span>
  <span m='223456'>each</span> <span m='223814'>frame</span> <span m='224172'>we</span>
  <span m='224530'>see</span> <span m='224887'>the</span> <span m='225245'>storage</span>
  <span m='225603'>for</span> <span m='225961'>the</span> <span m='226318'>argument</span>
  <span m='226676'>and</span> <span m='227034'>return</span> <span m='227392'>address.</span>
  </p><p><span m='227750'>And</span> <span m='228137'>as</span> <span m='228524'>the</span>
  <span m='228912'>nested</span> <span m='229299'>calls</span> <span m='229686'>return</span>
  <span m='230074'>the</span> <span m='230461'>stack</span> <span m='230848'>frames</span>
  <span m='231236'>will</span> <span m='231623'>be</span> <span m='232010'>deallocated</span>
  <span m='232398'>in</span> <span m='232785'>inverse</span> <span m='233172'>order.</span>
  </p><p><span m='233560'>Interestingly</span> <span m='233837'>we</span> <span m='234115'>can</span>
  <span m='234392'>learn</span> <span m='234670'>a</span> <span m='234947'>lot</span>
  <span m='235225'>about</span> <span m='235502'>the</span> <span m='235780'>current</span>
  <span m='236057'>state</span> <span m='236335'>of</span> <span m='236612'>execution</span>
  <span m='236890'>by</span> <span m='237167'>looking</span> <span m='237445'>at</span>
  <span m='237722'>the</span> <span m='238000'>active</span> <span m='238706'>stack</span>
  <span m='239413'>frames.</span> </p><p><span m='240120'>The</span> <span m='240498'>current</span>
  <span m='240876'>value</span> <span m='241254'>of</span> <span m='241632'>BP,</span>
  <span m='242010'>along</span> <span m='242388'>the</span> <span m='242766'>older</span>
  <span m='243145'>values</span> <span m='243523'>saved</span> <span m='243901'>in</span>
  <span m='244279'>the</span> <span m='244657'>activation</span> <span m='245035'>records,</span>
  <span m='245413'>allow</span> <span m='245791'>us</span> <span m='246170'>to</span>
  <span m='246541'>identify</span> <span m='246912'>the</span> <span m='247284'>active</span>
  <span m='247655'>procedure</span> <span m='248027'>calls</span> <span m='248398'>and</span>
  <span m='248770'>determine</span> <span m='249141'>their</span> <span m='249512'>arguments,</span>
  <span m='249884'>the</span> <span m='250255'>values</span> <span m='250627'>of</span>
  <span m='250998'>any</span> <span m='251370'>local</span> <span m='251817'>variables</span>
  <span m='252265'>for</span> <span m='252712'>active</span> <span m='253160'>calls,</span>
  <span m='253607'>and</span> <span m='254055'>so</span> <span m='254502'>on.</span>
  </p><p><span m='254950'>If</span> <span m='255267'>we</span> <span m='255584'>print</span>
  <span m='255901'>out</span> <span m='256218'>all</span> <span m='256536'>this</span>
  <span m='256853'>information</span> <span m='257170'>at</span> <span m='257487'>any</span>
  <span m='257805'>given</span> <span m='258122'>time</span> <span m='258439'>we</span>
  <span m='258756'>would</span> <span m='259073'>have</span> <span m='259391'>a</span>
  <span m='259708'>"stack</span> <span m='260025'>trace"</span> <span m='260342'>showing</span>
  <span m='260660'>the</span> <span m='260978'>progress</span> <span m='261296'>of</span>
  <span m='261614'>the</span> <span m='261932'>computation.</span> </p><p><span m='262250'>In</span>
  <span m='262685'>fact,</span> <span m='263121'>when</span> <span m='263556'>an</span>
  <span m='263992'>problem</span> <span m='264428'>occurs,</span> <span m='264863'>many</span>
  <span m='265299'>language</span> <span m='265735'>runtimes</span> <span m='266170'>will</span>
  <span m='266606'>print</span> <span m='267041'>out</span> <span m='267477'>that</span>
  <span m='267913'>stack</span> <span m='268348'>trace</span> <span m='268784'>to</span>
  <span m='269220'>help</span> <span m='269638'>the</span> <span m='270056'>programmer</span>
  <span m='270475'>determine</span> <span m='270893'>what</span> <span m='271311'>happened.</span>
  </p><p><span m='271730'>And,</span> <span m='272053'>of</span> <span m='272377'>course,</span>
  <span m='272701'>if</span> <span m='273025'>you</span> <span m='273349'>can</span>
  <span m='273673'>interpret</span> <span m='273997'>the</span> <span m='274321'>information</span>
  <span m='274645'>in</span> <span m='274968'>the</span> <span m='275292'>stack</span>
  <span m='275616'>frames,</span> <span m='275940'>you</span> <span m='276264'>can</span>
  <span m='276588'>show</span> <span m='276912'>you</span> <span m='277236'>understand</span>
  <span m='277560'>our</span> <span m='277972'>conventions</span> <span m='278385'>for</span>
  <span m='278798'>procedure</span> <span m='279211'>call</span> <span m='279624'>and</span>
  <span m='280037'>return.</span> </p><p><span m='280450'>Don't</span> <span m='280681'>be</span>
  <span m='280913'>surprised</span> <span m='281145'>to</span> <span m='281376'>find</span>
  <span m='281608'>such</span> <span m='281840'>a</span> <span m='282071'>question</span>
  <span m='282303'>on</span> <span m='282535'>a</span> <span m='282766'>quiz</span>
  <span m='282998'>:)</span> </p>
type: course
uid: 64a9f24a0cc188f72c055a3d4acdc0c8

---
None