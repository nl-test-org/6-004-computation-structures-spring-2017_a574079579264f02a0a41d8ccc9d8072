---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: i1tUBZLWD3o
  parent_uid: 3f451966890d485a063c100320b02b54
  title: Video-YouTube-Stream
  type: Video
  uid: 81fa740e6e6e2216599e237437a3f77c
- id: 3Play-3Play YouTube id-Stream
  media_location: i1tUBZLWD3o
  parent_uid: 3f451966890d485a063c100320b02b54
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 1a2f6e39d0a87099500a0cd8fa261324
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/i1tUBZLWD3o/default.jpg
  parent_uid: 3f451966890d485a063c100320b02b54
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 332a16f40d2b52e49c99bb60cfe90e0d
- id: i1tUBZLWD3o.srt
  parent_uid: 3f451966890d485a063c100320b02b54
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c8/c8s2/c8s2v3/carry-lookahead-adders-5-19-/i1tUBZLWD3o.srt
  title: 3play caption file
  type: null
  uid: 2e01d66871649f067d39dc76069bd4a9
- id: i1tUBZLWD3o.pdf
  parent_uid: 3f451966890d485a063c100320b02b54
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c8/c8s2/c8s2v3/carry-lookahead-adders-5-19-/i1tUBZLWD3o.pdf
  title: 3play pdf file
  type: null
  uid: 5ce748b04db04e59c66ac2c32c7b95f9
- id: Caption-3Play YouTube id-SRT
  parent_uid: 3f451966890d485a063c100320b02b54
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: d877142c46e63c1fab0ac0cccc985017
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 3f451966890d485a063c100320b02b54
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 52813a1d6e767f2b00bf75e37a530145
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_08-02-03_300k.mp4
  parent_uid: 3f451966890d485a063c100320b02b54
  title: Video-Internet Archive-MP4
  type: Video
  uid: 2a293cd6d64cf59a45ca1455fc6054a9
inline_embed_id: 42363597carrylookaheadadders51974509290
layout: video
order_index: null
parent_uid: 9baf13b93eeebb2f59c56b6cb6b176cb
related_resources_text: ''
short_url: carry-lookahead-adders-5-19-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c8/c8s2/c8s2v3/carry-lookahead-adders-5-19-
template_type: Embed
title: Carry-lookahead Adders (5:19)
transcript: <p><span m='1030'>Here's</span> <span m='1336'>another</span> <span m='1643'>approach</span>
  <span m='1950'>to</span> <span m='2257'>improving</span> <span m='2564'>the</span>
  <span m='2870'>latency</span> <span m='3177'>of</span> <span m='3484'>our</span>
  <span m='3791'>adder,</span> <span m='4098'>this</span> <span m='4404'>time</span>
  <span m='4711'>focusing</span> <span m='5018'>just</span> <span m='5325'>on</span>
  <span m='5632'>the</span> <span m='5939'>carry</span> <span m='6564'>logic.</span>
  </p><p><span m='7190'>Early</span> <span m='7447'>on</span> <span m='7705'>in</span>
  <span m='7963'>the</span> <span m='8221'>course,</span> <span m='8479'>we</span>
  <span m='8737'>learned</span> <span m='8994'>that</span> <span m='9252'>by</span>
  <span m='9510'>going</span> <span m='9768'>from</span> <span m='10026'>a</span>
  <span m='10284'>chain</span> <span m='10541'>of</span> <span m='10799'>logic</span>
  <span m='11057'>gates</span> <span m='11315'>to</span> <span m='11573'>a</span>
  <span m='11831'>tree</span> <span m='12089'>of</span> <span m='12475'>logic</span>
  <span m='12862'>gates,</span> <span m='13248'>we</span> <span m='13635'>could</span>
  <span m='14021'>go</span> <span m='14408'>from</span> <span m='14794'>a</span> <span
  m='15181'>linear</span> <span m='15567'>latency</span> <span m='15954'>to</span>
  <span m='16340'>a</span> <span m='16727'>logarithmic</span> <span m='17113'>latency.</span>
  </p><p><span m='17500'>Let's</span> <span m='17931'>try</span> <span m='18363'>to</span>
  <span m='18795'>do</span> <span m='19226'>that</span> <span m='19658'>here.</span>
  </p><p><span m='20090'>We'll</span> <span m='20417'>start</span> <span m='20745'>by</span>
  <span m='21073'>rewriting</span> <span m='21401'>the</span> <span m='21729'>equations</span>
  <span m='22057'>for</span> <span m='22385'>the</span> <span m='22712'>carry-out</span>
  <span m='23040'>from</span> <span m='23368'>the</span> <span m='23696'>full</span>
  <span m='24024'>adder</span> <span m='24352'>module.</span> </p><p><span m='24680'>The</span>
  <span m='25048'>final</span> <span m='25416'>form</span> <span m='25784'>of</span>
  <span m='26152'>the</span> <span m='26520'>rewritten</span> <span m='26888'>equation</span>
  <span m='27256'>has</span> <span m='27624'>two</span> <span m='27992'>terms.</span>
  </p><p><span m='28360'>The</span> <span m='28654'>G,</span> <span m='28949'>or</span>
  <span m='29244'>generate,</span> <span m='29538'>term</span> <span m='29833'>is</span>
  <span m='30128'>true</span> <span m='30422'>when</span> <span m='30717'>the</span>
  <span m='31012'>inputs</span> <span m='31307'>will</span> <span m='31601'>cause</span>
  <span m='31896'>the</span> <span m='32191'>module</span> <span m='32485'>to</span>
  <span m='32780'>generate</span> <span m='33075'>a</span> <span m='33370'>carry-out</span>
  <span m='33790'>right</span> <span m='34210'>away,</span> <span m='34630'>without</span>
  <span m='35050'>having</span> <span m='35470'>to</span> <span m='35890'>wait</span>
  <span m='36310'>for</span> <span m='36730'>the</span> <span m='37150'>carry-in</span>
  <span m='37570'>to</span> <span m='37990'>arrive.</span> </p><p><span m='38410'>The</span>
  <span m='38684'>P,</span> <span m='38958'>or</span> <span m='39232'>propagate,</span>
  <span m='39506'>term</span> <span m='39780'>is</span> <span m='40054'>true</span>
  <span m='40328'>if</span> <span m='40602'>the</span> <span m='40877'>module</span>
  <span m='41151'>will</span> <span m='41425'>generate</span> <span m='41699'>a</span>
  <span m='41973'>carry-out</span> <span m='42247'>only</span> <span m='42521'>if</span>
  <span m='42795'>there's</span> <span m='43070'>a</span> <span m='44319'>carry-in.</span>
  </p><p><span m='45569'>So</span> <span m='45867'>there</span> <span m='46166'>only</span>
  <span m='46465'>two</span> <span m='46764'>ways</span> <span m='47063'>to</span>
  <span m='47361'>get</span> <span m='47660'>a</span> <span m='47959'>carry-out</span>
  <span m='48258'>from</span> <span m='48557'>the</span> <span m='48855'>module:</span>
  <span m='49154'>it's</span> <span m='49453'>either</span> <span m='49752'>generated</span>
  <span m='50051'>by</span> <span m='50350'>the</span> <span m='50764'>current</span>
  <span m='51179'>module</span> <span m='51594'>or</span> <span m='52009'>the</span>
  <span m='52424'>carry-in</span> <span m='52839'>is</span> <span m='53254'>propagated</span>
  <span m='53669'>from</span> <span m='54084'>the</span> <span m='54499'>previous</span>
  <span m='54914'>module.</span> </p><p><span m='55329'>Actually,</span> <span m='55675'>it's</span>
  <span m='56021'>usual</span> <span m='56367'>to</span> <span m='56714'>change</span>
  <span m='57060'>the</span> <span m='57406'>logic</span> <span m='57753'>for</span>
  <span m='58099'>the</span> <span m='58445'>P</span> <span m='58792'>term</span>
  <span m='59138'>from</span> <span m='59484'>"A</span> <span m='59831'>OR</span>
  <span m='60177'>B"</span> <span m='60523'>to</span> <span m='60870'>"A</span> <span
  m='61216'>XOR</span> <span m='61562'>B".</span> </p><p><span m='61909'>This</span>
  <span m='62161'>doesn't</span> <span m='62414'>change</span> <span m='62666'>the</span>
  <span m='62919'>truth</span> <span m='63171'>table</span> <span m='63424'>for</span>
  <span m='63676'>the</span> <span m='63929'>carry-out</span> <span m='64182'>but</span>
  <span m='64434'>will</span> <span m='64687'>allow</span> <span m='64939'>us</span>
  <span m='65192'>to</span> <span m='65444'>express</span> <span m='65697'>the</span>
  <span m='65950'>sum</span> <span m='66589'>output</span> <span m='67229'>as</span>
  <span m='67869'>"P</span> <span m='68509'>XOR</span> <span m='69149'>carry-in".</span>
  </p><p><span m='69789'>Here's</span> <span m='70195'>the</span> <span m='70602'>schematic</span>
  <span m='71009'>for</span> <span m='71416'>the</span> <span m='71822'>reorganized</span>
  <span m='72229'>full</span> <span m='72636'>adder</span> <span m='73043'>module.</span>
  </p><p><span m='73450'>The</span> <span m='73815'>little</span> <span m='74180'>sum-of-products</span>
  <span m='74546'>circuit</span> <span m='74911'>for</span> <span m='75277'>the</span>
  <span m='75642'>carry-out</span> <span m='76008'>can</span> <span m='76373'>be</span>
  <span m='76739'>implemented</span> <span m='77104'>using</span> <span m='77470'>3</span>
  <span m='77835'>2-input</span> <span m='78201'>NAND</span> <span m='78509'>gates,</span>
  <span m='78817'>which</span> <span m='79125'>is</span> <span m='79433'>a</span>
  <span m='79741'>bit</span> <span m='80049'>more</span> <span m='80357'>compact</span>
  <span m='80665'>than</span> <span m='80973'>the</span> <span m='81281'>implementation</span>
  <span m='81589'>for</span> <span m='81897'>the</span> <span m='82205'>three</span>
  <span m='82513'>product</span> <span m='82821'>terms</span> <span m='83130'>we</span>
  <span m='83588'>suggested</span> <span m='84046'>in</span> <span m='84504'>Lab</span>
  <span m='84962'>2.</span> </p><p><span m='85420'>Time</span> <span m='85875'>to</span>
  <span m='86331'>update</span> <span m='86787'>your</span> <span m='87242'>full</span>
  <span m='87698'>adder</span> <span m='88154'>circuit!</span> </p><p><span m='88610'>Now</span>
  <span m='89011'>consider</span> <span m='89413'>two</span> <span m='89815'>adjacent</span>
  <span m='90217'>adder</span> <span m='90619'>modules</span> <span m='91020'>in</span>
  <span m='91422'>a</span> <span m='91824'>larger</span> <span m='92226'>adder</span>
  <span m='92628'>circuit:</span> <span m='93030'>we'll</span> <span m='93328'>use</span>
  <span m='93627'>the</span> <span m='93925'>label</span> <span m='94224'>H</span>
  <span m='94522'>to</span> <span m='94821'>refer</span> <span m='95119'>to</span>
  <span m='95418'>the</span> <span m='95716'>high-order</span> <span m='96015'>module</span>
  <span m='96313'>and</span> <span m='96612'>the</span> <span m='96910'>label</span>
  <span m='97209'>L</span> <span m='97507'>to</span> <span m='97806'>refer</span>
  <span m='98104'>to</span> <span m='98403'>the</span> <span m='98701'>low-order</span>
  <span m='99000'>module.</span> </p><p><span m='100070'>We</span> <span m='100356'>can</span>
  <span m='100642'>use</span> <span m='100928'>the</span> <span m='101214'>generate</span>
  <span m='101500'>and</span> <span m='101787'>propagate</span> <span m='102073'>information</span>
  <span m='102359'>from</span> <span m='102645'>each</span> <span m='102931'>of</span>
  <span m='103218'>the</span> <span m='103504'>modules</span> <span m='103790'>to</span>
  <span m='104076'>develop</span> <span m='104362'>equations</span> <span m='104649'>for</span>
  <span m='104984'>the</span> <span m='105319'>carry-out</span> <span m='105655'>from</span>
  <span m='105990'>the</span> <span m='106325'>pair</span> <span m='106661'>of</span>
  <span m='106996'>modules</span> <span m='107332'>treated</span> <span m='107667'>as</span>
  <span m='108002'>a</span> <span m='108338'>single</span> <span m='108673'>block.</span>
  </p><p><span m='109009'>We'll</span> <span m='109380'>generate</span> <span m='109751'>a</span>
  <span m='110122'>carry-out</span> <span m='110494'>from</span> <span m='110865'>the</span>
  <span m='111236'>block</span> <span m='111608'>when</span> <span m='111979'>a</span>
  <span m='112350'>carry-out</span> <span m='112722'>is</span> <span m='113093'>generated</span>
  <span m='113464'>by</span> <span m='113836'>the</span> <span m='114207'>H</span>
  <span m='114578'>module,</span> <span m='114950'>or</span> <span m='115356'>when</span>
  <span m='115763'>a</span> <span m='116170'>carry-out</span> <span m='116577'>is</span>
  <span m='116984'>generated</span> <span m='117391'>by</span> <span m='117798'>the</span>
  <span m='118205'>L</span> <span m='118611'>module</span> <span m='119018'>and</span>
  <span m='119425'>propagated</span> <span m='119832'>by</span> <span m='120239'>the</span>
  <span m='120646'>H</span> <span m='121053'>module.</span> </p><p><span m='121460'>And</span>
  <span m='121789'>we'll</span> <span m='122118'>propagate</span> <span m='122447'>the</span>
  <span m='122777'>carry-in</span> <span m='123106'>through</span> <span m='123435'>the</span>
  <span m='123764'>block</span> <span m='124094'>only</span> <span m='124423'>if</span>
  <span m='124752'>the</span> <span m='125081'>L</span> <span m='125411'>module</span>
  <span m='125740'>propagates</span> <span m='126069'>its</span> <span m='126399'>carry-in</span>
  <span m='126868'>to</span> <span m='127337'>the</span> <span m='127807'>intermediate</span>
  <span m='128276'>carry-out</span> <span m='128745'>and</span> <span m='129215'>H</span>
  <span m='129684'>module</span> <span m='130153'>propagates</span> <span m='130623'>that</span>
  <span m='131092'>to</span> <span m='131561'>the</span> <span m='132031'>final</span>
  <span m='132500'>carry-out.</span> </p><p><span m='132970'>So</span> <span m='133430'>we</span>
  <span m='133890'>have</span> <span m='134350'>two</span> <span m='134810'>simple</span>
  <span m='135270'>equations</span> <span m='135730'>requiring</span> <span m='136190'>only</span>
  <span m='136650'>a</span> <span m='137110'>couple</span> <span m='137570'>of</span>
  <span m='138030'>logic</span> <span m='138490'>gates</span> <span m='138950'>to</span>
  <span m='139410'>implement.</span> </p><p><span m='139870'>Let's</span> <span m='140216'>use</span>
  <span m='140562'>these</span> <span m='140908'>equations</span> <span m='141255'>to</span>
  <span m='141601'>build</span> <span m='141947'>a</span> <span m='142294'>generate-propagate</span>
  <span m='142640'>(GP)</span> <span m='142986'>module</span> <span m='143333'>and</span>
  <span m='143679'>hook</span> <span m='144025'>it</span> <span m='144372'>to</span>
  <span m='144718'>the</span> <span m='145064'>H</span> <span m='145411'>and</span>
  <span m='145757'>L</span> <span m='146103'>modules</span> <span m='146450'>as</span>
  <span m='147215'>shown.</span> </p><p><span m='147980'>The</span> <span m='148247'>G</span>
  <span m='148514'>and</span> <span m='148781'>P</span> <span m='149048'>outputs</span>
  <span m='149316'>of</span> <span m='149583'>the</span> <span m='149850'>GP</span>
  <span m='150117'>module</span> <span m='150385'>tell</span> <span m='150652'>us</span>
  <span m='150919'>under</span> <span m='151186'>what</span> <span m='151453'>conditions</span>
  <span m='151721'>we'll</span> <span m='151988'>get</span> <span m='152255'>a</span>
  <span m='152522'>carry-out</span> <span m='152790'>from</span> <span m='153319'>the</span>
  <span m='153848'>two</span> <span m='154377'>individual</span> <span m='154906'>modules</span>
  <span m='155435'>treated</span> <span m='155964'>as</span> <span m='156493'>a</span>
  <span m='157022'>single,</span> <span m='157551'>larger</span> <span m='158080'>block.</span>
  </p><p><span m='158610'>We</span> <span m='158875'>can</span> <span m='159140'>use</span>
  <span m='159405'>additional</span> <span m='159671'>layers</span> <span m='159936'>of</span>
  <span m='160201'>GP</span> <span m='160467'>modules</span> <span m='160732'>to</span>
  <span m='160997'>build</span> <span m='161262'>a</span> <span m='161528'>tree</span>
  <span m='161793'>of</span> <span m='162058'>logic</span> <span m='162324'>that</span>
  <span m='162589'>computes</span> <span m='162854'>the</span> <span m='163120'>generate</span>
  <span m='163572'>and</span> <span m='164025'>propagate</span> <span m='164477'>logic</span>
  <span m='164930'>for</span> <span m='165383'>adders</span> <span m='165835'>with</span>
  <span m='166288'>any</span> <span m='166741'>number</span> <span m='167193'>of</span>
  <span m='167646'>inputs.</span> </p><p><span m='168099'>For</span> <span m='168414'>an</span>
  <span m='168730'>adder</span> <span m='169045'>with</span> <span m='169361'>N</span>
  <span m='169677'>inputs,</span> <span m='169992'>the</span> <span m='170308'>tree</span>
  <span m='170623'>will</span> <span m='170939'>contain</span> <span m='171255'>a</span>
  <span m='171570'>total</span> <span m='171886'>of</span> <span m='172201'>N-1</span>
  <span m='172517'>GP</span> <span m='172833'>modules</span> <span m='173148'>and</span>
  <span m='173464'>have</span> <span m='173780'>a</span> <span m='174405'>latency</span>
  <span m='175031'>that's</span> <span m='175657'>order</span> <span m='176283'>log(N).</span>
  </p><p><span m='176909'>In</span> <span m='177143'>the</span> <span m='177377'>next</span>
  <span m='177612'>step,</span> <span m='177846'>we'll</span> <span m='178080'>see</span>
  <span m='178315'>how</span> <span m='178549'>to</span> <span m='178784'>use</span>
  <span m='179018'>the</span> <span m='179252'>generate</span> <span m='179487'>and</span>
  <span m='179721'>propagate</span> <span m='179955'>information</span> <span m='180190'>to</span>
  <span m='180424'>quickly</span> <span m='180659'>compute</span> <span m='181196'>the</span>
  <span m='181733'>carry-in</span> <span m='182270'>for</span> <span m='182808'>each</span>
  <span m='183345'>of</span> <span m='183882'>the</span> <span m='184419'>original</span>
  <span m='184957'>full</span> <span m='185494'>adder</span> <span m='186031'>modules.</span>
  </p><p><span m='186569'>Once</span> <span m='186912'>we're</span> <span m='187256'>given</span>
  <span m='187599'>the</span> <span m='187943'>carry-in</span> <span m='188286'>C_0</span>
  <span m='188630'>for</span> <span m='188974'>the</span> <span m='189317'>low-order</span>
  <span m='189661'>bit,</span> <span m='190004'>we</span> <span m='190348'>can</span>
  <span m='190691'>hierarchically</span> <span m='191035'>compute</span> <span m='191379'>the</span>
  <span m='191870'>carry-in</span> <span m='192361'>for</span> <span m='192853'>each</span>
  <span m='193344'>full</span> <span m='193836'>adder</span> <span m='194327'>module.</span>
  </p><p><span m='194819'>Given</span> <span m='195074'>the</span> <span m='195329'>carry-in</span>
  <span m='195584'>to</span> <span m='195839'>a</span> <span m='196094'>block</span>
  <span m='196349'>of</span> <span m='196604'>adders,</span> <span m='196859'>we</span>
  <span m='197114'>simply</span> <span m='197369'>pass</span> <span m='197624'>it</span>
  <span m='197879'>along</span> <span m='198134'>as</span> <span m='198389'>the</span>
  <span m='198644'>carry-in</span> <span m='198899'>to</span> <span m='199154'>the</span>
  <span m='199410'>low-half</span> <span m='199857'>of</span> <span m='200305'>the</span>
  <span m='200752'>block.</span> </p><p><span m='201200'>The</span> <span m='201452'>carry-in</span>
  <span m='201704'>for</span> <span m='201957'>the</span> <span m='202209'>high-half</span>
  <span m='202462'>of</span> <span m='202714'>the</span> <span m='202967'>block</span>
  <span m='203219'>is</span> <span m='203471'>computed</span> <span m='203724'>the</span>
  <span m='203976'>using</span> <span m='204229'>the</span> <span m='204481'>generate</span>
  <span m='204734'>and</span> <span m='204986'>propagate</span> <span m='205239'>information</span>
  <span m='205673'>from</span> <span m='206107'>the</span> <span m='206542'>low-half</span>
  <span m='206976'>of</span> <span m='207411'>the</span> <span m='207845'>block.</span>
  </p><p><span m='208280'>We</span> <span m='208561'>can</span> <span m='208842'>use</span>
  <span m='209123'>these</span> <span m='209404'>equations</span> <span m='209685'>to</span>
  <span m='209966'>build</span> <span m='210247'>a</span> <span m='210528'>C</span>
  <span m='210809'>module</span> <span m='211090'>and</span> <span m='211371'>arrange</span>
  <span m='211652'>the</span> <span m='211933'>C</span> <span m='212214'>modules</span>
  <span m='212495'>in</span> <span m='212776'>a</span> <span m='213057'>tree</span>
  <span m='213338'>as</span> <span m='213619'>shown</span> <span m='213900'>to</span>
  <span m='214316'>use</span> <span m='214732'>the</span> <span m='215148'>C_0</span>
  <span m='215564'>carry-in</span> <span m='215980'>to</span> <span m='216396'>hierarchically</span>
  <span m='216812'>compute</span> <span m='217228'>the</span> <span m='217644'>carry-in</span>
  <span m='218060'>to</span> <span m='218476'>each</span> <span m='218892'>layer</span>
  <span m='219308'>of</span> <span m='219724'>successively</span> <span m='220140'>smaller</span>
  <span m='220624'>blocks,</span> <span m='221108'>until</span> <span m='221592'>we</span>
  <span m='222076'>finally</span> <span m='222560'>reach</span> <span m='223044'>the</span>
  <span m='223528'>full</span> <span m='224012'>adder</span> <span m='224496'>modules.</span>
  </p><p><span m='224980'>For</span> <span m='225367'>example,</span> <span m='225755'>these</span>
  <span m='226142'>equations</span> <span m='226530'>show</span> <span m='226917'>how</span>
  <span m='227305'>C4</span> <span m='227692'>is</span> <span m='228080'>computed</span>
  <span m='228467'>from</span> <span m='228855'>C0,</span> <span m='229242'>and</span>
  <span m='229630'>C6</span> <span m='230017'>is</span> <span m='230405'>computed</span>
  <span m='230792'>from</span> <span m='231180'>C4.</span> </p><p><span m='233280'>Again</span>
  <span m='233612'>the</span> <span m='233945'>total</span> <span m='234277'>propagation</span>
  <span m='234610'>delay</span> <span m='234943'>from</span> <span m='235275'>the</span>
  <span m='235608'>arrival</span> <span m='235940'>of</span> <span m='236273'>the</span>
  <span m='236606'>C_0</span> <span m='236938'>input</span> <span m='237271'>to</span>
  <span m='237603'>the</span> <span m='237936'>carry-ins</span> <span m='238269'>for</span>
  <span m='238856'>each</span> <span m='239443'>full</span> <span m='240030'>adder</span>
  <span m='240617'>is</span> <span m='241204'>order</span> <span m='241791'>log(N).</span>
  </p><p><span m='242379'>Notice</span> <span m='242720'>that</span> <span m='243062'>the</span>
  <span m='243403'>G_L</span> <span m='243745'>and</span> <span m='244086'>P_L</span>
  <span m='244428'>inputs</span> <span m='244769'>to</span> <span m='245111'>a</span>
  <span m='245452'>particular</span> <span m='245794'>C</span> <span m='246135'>module</span>
  <span m='246477'>are</span> <span m='246818'>the</span> <span m='247160'>same</span>
  <span m='247501'>as</span> <span m='247843'>two</span> <span m='248184'>of</span>
  <span m='248526'>the</span> <span m='248867'>inputs</span> <span m='249209'>to</span>
  <span m='249534'>the</span> <span m='249859'>GP</span> <span m='250184'>module</span>
  <span m='250509'>in</span> <span m='250834'>the</span> <span m='251159'>same</span>
  <span m='251484'>position</span> <span m='251809'>in</span> <span m='252134'>the</span>
  <span m='252459'>GP</span> <span m='252784'>tree.</span> </p><p><span m='253110'>We</span>
  <span m='253457'>can</span> <span m='253804'>combine</span> <span m='254152'>the</span>
  <span m='254499'>GP</span> <span m='254846'>module</span> <span m='255194'>and</span>
  <span m='255541'>C</span> <span m='255889'>module</span> <span m='256236'>to</span>
  <span m='256583'>form</span> <span m='256931'>a</span> <span m='257278'>single</span>
  <span m='257625'>carry-lookahead</span> <span m='257973'>module</span> <span m='258320'>that</span>
  <span m='258668'>passes</span> <span m='259107'>generate</span> <span m='259546'>and</span>
  <span m='259986'>propagate</span> <span m='260425'>information</span> <span m='260864'>up</span>
  <span m='261304'>the</span> <span m='261743'>tree</span> <span m='262182'>and</span>
  <span m='262622'>carry-in</span> <span m='263061'>information</span> <span m='263500'>down</span>
  <span m='263940'>the</span> <span m='264535'>tree.</span> </p><p><span m='265130'>The</span>
  <span m='265483'>schematic</span> <span m='265836'>at</span> <span m='266190'>the</span>
  <span m='266543'>top</span> <span m='266896'>shows</span> <span m='267250'>how</span>
  <span m='267603'>to</span> <span m='267956'>wire</span> <span m='268310'>up</span>
  <span m='268663'>the</span> <span m='269016'>tree</span> <span m='269370'>of</span>
  <span m='269723'>carry-lookahead</span> <span m='270076'>modules.</span> </p><p><span
  m='270430'>And</span> <span m='270725'>now</span> <span m='271020'>we</span> <span
  m='271315'>get</span> <span m='271610'>to</span> <span m='271905'>the</span> <span
  m='272200'>payoff</span> <span m='272495'>for</span> <span m='272790'>all</span>
  <span m='273085'>this</span> <span m='273380'>hard</span> <span m='273675'>work!</span>
  </p><p><span m='273970'>The</span> <span m='274394'>combined</span> <span m='274818'>propagation</span>
  <span m='275242'>delay</span> <span m='275666'>to</span> <span m='276090'>hierarchically</span>
  <span m='276515'>compute</span> <span m='276939'>the</span> <span m='277363'>generate</span>
  <span m='277787'>and</span> <span m='278211'>propagate</span> <span m='278635'>information</span>
  <span m='279060'>on</span> <span m='279480'>the</span> <span m='279901'>way</span>
  <span m='280322'>up</span> <span m='280742'>and</span> <span m='281163'>the</span>
  <span m='281584'>carry-in</span> <span m='282004'>information</span> <span m='282425'>on</span>
  <span m='282846'>the</span> <span m='283266'>way</span> <span m='283687'>down</span>
  <span m='284108'>is</span> <span m='284528'>order</span> <span m='284949'>log(N),</span>
  <span m='285370'>which</span> <span m='285702'>is</span> <span m='286035'>then</span>
  <span m='286367'>the</span> <span m='286700'>latency</span> <span m='287032'>for</span>
  <span m='287365'>the</span> <span m='287697'>entire</span> <span m='288030'>adder</span>
  <span m='288362'>since</span> <span m='288695'>computing</span> <span m='289027'>the</span>
  <span m='289360'>sum</span> <span m='289692'>outputs</span> <span m='290025'>only</span>
  <span m='290357'>takes</span> <span m='290690'>one</span> <span m='291437'>additional</span>
  <span m='292185'>XOR</span> <span m='292932'>delay.</span> </p><p><span m='293680'>This</span>
  <span m='294061'>is</span> <span m='294442'>a</span> <span m='294824'>considerable</span>
  <span m='295205'>improvement</span> <span m='295587'>over</span> <span m='295968'>the</span>
  <span m='296350'>order</span> <span m='296731'>N</span> <span m='297112'>latency</span>
  <span m='297494'>of</span> <span m='297875'>the</span> <span m='298257'>ripple-carry</span>
  <span m='298638'>adder.</span> </p><p><span m='299020'>A</span> <span m='299371'>final</span>
  <span m='299722'>design</span> <span m='300073'>note:</span> <span m='300424'>we</span>
  <span m='300775'>no</span> <span m='301127'>longer</span> <span m='301478'>need</span>
  <span m='301829'>the</span> <span m='302180'>carry-out</span> <span m='302531'>circuitry</span>
  <span m='302883'>in</span> <span m='303234'>the</span> <span m='303585'>full</span>
  <span m='303936'>adder</span> <span m='304287'>module,</span> <span m='304639'>so</span>
  <span m='305145'>it</span> <span m='305651'>can</span> <span m='306157'>be</span>
  <span m='306663'>removed.</span> </p><p><span m='307169'>Variations</span> <span
  m='307633'>on</span> <span m='308097'>this</span> <span m='308561'>generate-propagate</span>
  <span m='309026'>strategy</span> <span m='309490'>form</span> <span m='309954'>the</span>
  <span m='310418'>basis</span> <span m='310883'>for</span> <span m='311347'>the</span>
  <span m='311811'>fastest-known</span> <span m='312275'>adder</span> <span m='312740'>circuits.</span>
  </p><p><span m='313870'>If</span> <span m='314214'>you'd</span> <span m='314558'>like</span>
  <span m='314902'>to</span> <span m='315246'>learn</span> <span m='315590'>more,</span>
  <span m='315935'>look</span> <span m='316279'>up</span> <span m='316623'>"Kogge-Stone</span>
  <span m='316967'>adders"</span> <span m='317311'>on</span> <span m='317655'>Wikipedia.</span>
  </p>
type: course
uid: 3f451966890d485a063c100320b02b54

---
None