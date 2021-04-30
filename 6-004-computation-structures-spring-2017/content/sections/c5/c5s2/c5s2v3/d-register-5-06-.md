---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: CcInkh1mKZA
  parent_uid: 39c95bb76022dfc482e17f25cc95bcfa
  title: Video-YouTube-Stream
  type: Video
  uid: 08994c15a007ffa74f0e0526384a4d94
- id: 3Play-3Play YouTube id-Stream
  media_location: CcInkh1mKZA
  parent_uid: 39c95bb76022dfc482e17f25cc95bcfa
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 5ab6d521bc7148c178b7a0f63aa2ae2e
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/CcInkh1mKZA/default.jpg
  parent_uid: 39c95bb76022dfc482e17f25cc95bcfa
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: aaf4404e96e40c9718bfae88d493fb47
- id: CcInkh1mKZA.srt
  parent_uid: 39c95bb76022dfc482e17f25cc95bcfa
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c5/c5s2/c5s2v3/d-register-5-06-/CcInkh1mKZA.srt
  title: 3play caption file
  type: null
  uid: 345110f9c2bd1028a92c6aae47396412
- id: CcInkh1mKZA.pdf
  parent_uid: 39c95bb76022dfc482e17f25cc95bcfa
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c5/c5s2/c5s2v3/d-register-5-06-/CcInkh1mKZA.pdf
  title: 3play pdf file
  type: null
  uid: 6729f06bddf8e4a56e88a929504dd595
- id: Caption-3Play YouTube id-SRT
  parent_uid: 39c95bb76022dfc482e17f25cc95bcfa
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: edd4e560a6f17dc0481f7b997a406fd1
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 39c95bb76022dfc482e17f25cc95bcfa
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 475b406f28bb31ecd0f39ab9b8d2fcc2
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_05-02-03_300k.mp4
  parent_uid: 39c95bb76022dfc482e17f25cc95bcfa
  title: Video-Internet Archive-MP4
  type: Video
  uid: ce48fee90ebb5e1ed27d7fcda7688902
inline_embed_id: 81078024dregister50649158110
layout: video
order_index: null
parent_uid: 42af276ee4cedc6340cb530fe8a8cd71
related_resources_text: ''
short_url: d-register-5-06-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c5/c5s2/c5s2v3/d-register-5-06-
template_type: Embed
title: D Register (5:06)
transcript: "<p><span m='350'>Let\u2019s</span> <span m='970'>try</span> <span m='1220'>using</span>\
  \ <span m='1600'>the</span> <span m='1670'>latch</span> <span m='2120'>as</span>\
  \ <span m='2290'>the</span> <span m='2370'>memory</span> <span m='2760'>component</span>\
  \ <span m='3350'>in</span> <span m='3510'>our</span> <span m='3610'>sequential</span>\
  \ <span m='4210'>logic</span> <span m='4550'>system.</span> </p><p><span m='6170'>To</span>\
  \ <span m='6280'>load</span> <span m='6590'>the</span> <span m='6730'>encoding</span>\
  \ <span m='7230'>of</span> <span m='7310'>the</span> <span m='7400'>new</span> <span\
  \ m='7630'>state</span> <span m='7990'>into</span> <span m='8280'>the</span> <span\
  \ m='8380'>latch,</span> <span m='8790'>we</span> <span m='8980'>open</span> <span\
  \ m='9270'>the</span> <span m='9340'>latch</span> <span m='9720'>by</span> <span\
  \ m='9860'>setting</span> <span m='10210'>the</span> <span m='10280'>latch\u2019\
  s</span> <span m='10760'>gate</span> <span m='11020'>input</span> <span m='11400'>HIGH,</span>\
  \ </p><p><span m='12350'>letting</span> <span m='12630'>the</span> <span m='12710'>new</span>\
  \ <span m='12950'>value</span> <span m='13290'>propagate</span> <span m='13870'>to</span>\
  \ <span m='13960'>the</span> <span m='14070'>latch\u2019s</span> <span m='14500'>Q</span>\
  \ <span m='14790'>output,</span> <span m='15480'>which</span> <span m='15750'>represents</span>\
  \ <span m='16309'>the</span> <span m='16379'>current</span> <span m='16670'>state.</span>\
  \ </p><p><span m='18010'>This</span> <span m='18210'>updated</span> <span m='18670'>value</span>\
  \ <span m='18990'>propagates</span> <span m='19660'>through</span> <span m='19810'>the</span>\
  \ <span m='19900'>combinational</span> <span m='20580'>logic,</span> <span m='21160'>updating</span>\
  \ <span m='21810'>the</span> <span m='21880'>new</span> <span m='22030'>state</span>\
  \ <span m='22340'>information.</span> </p><p><span m='23740'>Oops,</span> <span\
  \ m='24350'>if</span> <span m='24640'>the</span> <span m='24730'>gate</span> <span\
  \ m='24940'>stays</span> <span m='25250'>HIGH</span> <span m='25460'>too</span>\
  \ <span m='25770'>long,</span> <span m='26300'>we\u2019ve</span> <span m='26550'>created</span>\
  \ <span m='27000'>a</span> <span m='27050'>loop</span> <span m='27370'>in</span>\
  \ <span m='27440'>our</span> <span m='27580'>system</span> <span m='28120'>and</span>\
  \ <span m='28350'>our</span> <span m='28450'>plan</span> <span m='28820'>to</span>\
  \ <span m='28960'>load</span> <span m='29210'>the</span> <span m='29330'>latch</span>\
  \ <span m='29710'>with</span> <span m='29930'>new</span> <span m='30120'>state</span>\
  \ <span m='30790'>goes</span> <span m='31280'>awry</span> <span m='31870'>as</span>\
  \ <span m='32229'>the</span> <span m='32330'>new</span> <span m='32509'>state</span>\
  \ <span m='32800'>value</span> <span m='33100'>starts</span> <span m='33480'>to</span>\
  \ <span m='33570'>change</span> <span m='33950'>rapidly</span> <span m='34700'>as</span>\
  \ <span m='34910'>information</span> <span m='35500'>propagates</span> <span m='36170'>around</span>\
  \ <span m='36770'>and</span> <span m='36910'>around</span> <span m='37220'>the</span>\
  \ <span m='37300'>loop.</span> </p><p><span m='38810'>So</span> <span m='38960'>to</span>\
  \ <span m='39040'>make</span> <span m='39270'>this</span> <span m='39460'>work,</span>\
  \ <span m='39840'>we</span> <span m='39990'>need</span> <span m='40170'>to</span>\
  \ <span m='40260'>carefully</span> <span m='40780'>time</span> <span m='41180'>the</span>\
  \ <span m='41330'>interval</span> <span m='41780'>when</span> <span m='41990'>G</span>\
  \ <span m='42240'>is</span> <span m='42390'>HIGH.</span> </p><p><span m='43870'>It</span>\
  \ <span m='43930'>has</span> <span m='44120'>to</span> <span m='44190'>be</span>\
  \ <span m='44380'>long</span> <span m='44700'>enough</span> <span m='45080'>to</span>\
  \ <span m='45220'>satisfy</span> <span m='45760'>the</span> <span m='45860'>constraints</span>\
  \ <span m='46590'>of</span> <span m='46690'>the</span> <span m='46770'>dynamic</span>\
  \ <span m='47220'>discipline,</span> </p><p><span m='48090'>but</span> <span m='48200'>it</span>\
  \ <span m='48260'>has</span> <span m='48410'>to</span> <span m='48490'>be</span>\
  \ <span m='48600'>short</span> <span m='48980'>enough</span> <span m='49470'>that</span>\
  \ <span m='49760'>the</span> <span m='49850'>latch</span> <span m='50250'>closes</span>\
  \ <span m='50730'>again</span> <span m='51070'>before</span> <span m='51370'>the</span>\
  \ <span m='51470'>new</span> <span m='51690'>state</span> <span m='51970'>information</span>\
  \ <span m='52520'>has</span> <span m='52760'>a</span> <span m='52810'>chance</span>\
  \ <span m='53250'>to</span> <span m='53330'>propagate</span> <span m='54040'>all</span>\
  \ <span m='54220'>the</span> <span m='54280'>way</span> <span m='54440'>around</span>\
  \ <span m='54760'>the</span> <span m='54830'>loop.</span> </p><p><span m='56120'>Hmm.</span>\
  \ </p><p><span m='57360'>I</span> <span m='57400'>think</span> <span m='57570'>Mr.</span>\
  \ <span m='57850'>Blue</span> <span m='58170'>is</span> <span m='58250'>right:</span>\
  \ <span m='58710'>this</span> <span m='59010'>sort</span> <span m='59200'>of</span>\
  \ <span m='59300'>tricky</span> <span m='59690'>system</span> <span m='60090'>timing</span>\
  \ <span m='60670'>would</span> <span m='61030'>likely</span> <span m='61590'>be</span>\
  \ <span m='61870'>error-prone</span> <span m='62530'>since</span> <span m='62880'>the</span>\
  \ <span m='63020'>exact</span> <span m='63630'>timing</span> <span m='64010'>of</span>\
  \ <span m='64099'>signals</span> <span m='64580'>is</span> <span m='64690'>almost</span>\
  \ <span m='65080'>impossible</span> <span m='65810'>to</span> <span m='65920'>guarantee.</span>\
  \ </p><p><span m='67450'>We</span> <span m='67590'>have</span> <span m='67820'>upper</span>\
  \ <span m='68270'>and</span> <span m='68400'>lower</span> <span m='68750'>bounds</span>\
  \ <span m='69160'>on</span> <span m='69250'>the</span> <span m='69320'>timing</span>\
  \ <span m='69720'>of</span> <span m='69790'>signal</span> <span m='70110'>transitions</span>\
  \ <span m='70820'>but</span> <span m='71000'>no</span> <span m='71210'>guarantees</span>\
  \ <span m='71920'>of</span> <span m='72010'>exact</span> <span m='72520'>intervals.</span>\
  \ </p><p><span m='73470'>To</span> <span m='73560'>make</span> <span m='73760'>this</span>\
  \ <span m='74000'>work,</span> <span m='74380'>we</span> <span m='74490'>want</span>\
  \ <span m='74720'>to</span> <span m='74780'>a</span> <span m='74810'>load</span>\
  \ <span m='75090'>signal</span> <span m='75510'>that</span> <span m='75640'>marks</span>\
  \ <span m='75950'>an</span> <span m='76080'>instant</span> <span m='76470'>in</span>\
  \ <span m='76620'>time,</span> <span m='77160'>not</span> <span m='77660'>an</span>\
  \ <span m='77830'>interval.</span> </p><p><span m='80160'>Here\u2019s</span> <span\
  \ m='80420'>an</span> <span m='80500'>analogy</span> <span m='81110'>that</span>\
  \ <span m='81260'>will</span> <span m='81360'>help</span> <span m='81580'>us</span>\
  \ <span m='81710'>understand</span> <span m='82350'>what\u2019s</span> <span m='82550'>happening</span>\
  \ <span m='83190'>and</span> <span m='83340'>what</span> <span m='83650'>we</span>\
  \ <span m='83750'>can</span> <span m='83900'>do</span> <span m='84050'>about</span>\
  \ <span m='84320'>it.</span> </p><p><span m='85190'>Imagine</span> <span m='85700'>a</span>\
  \ <span m='85730'>line</span> <span m='86100'>cars</span> <span m='86570'>waiting</span>\
  \ <span m='86980'>at</span> <span m='87070'>a</span> <span m='87140'>toll</span>\
  \ <span m='87460'>booth</span> <span m='87750'>gate.</span> </p><p><span m='88720'>The</span>\
  \ <span m='88790'>sequence</span> <span m='89240'>of</span> <span m='89330'>cars</span>\
  \ <span m='89720'>represents</span> <span m='90290'>the</span> <span m='90350'>sequence</span>\
  \ <span m='90780'>of</span> <span m='90850'>states</span> <span m='91290'>in</span>\
  \ <span m='91390'>our</span> <span m='91470'>sequential</span> <span m='92000'>logic</span>\
  \ <span m='92710'>and</span> <span m='93110'>the</span> <span m='93170'>gated</span>\
  \ <span m='93580'>toll</span> <span m='93900'>both</span> <span m='94170'>represents</span>\
  \ <span m='94830'>the</span> <span m='94920'>latch.</span> </p><p><span m='96560'>Initially</span>\
  \ <span m='97040'>the</span> <span m='97140'>gate</span> <span m='97360'>is</span>\
  \ <span m='97510'>closed</span> <span m='97950'>and</span> <span m='98040'>the</span>\
  \ <span m='98100'>cars</span> <span m='98470'>are</span> <span m='98620'>waiting</span>\
  \ <span m='98900'>patiently</span> <span m='99460'>to</span> <span m='99570'>go</span>\
  \ <span m='99750'>through</span> <span m='100010'>the</span> <span m='100100'>toll</span>\
  \ <span m='100360'>booth.</span> </p><p><span m='101620'>When</span> <span m='101780'>the</span>\
  \ <span m='101880'>gate</span> <span m='102190'>opens,</span> <span m='102690'>the</span>\
  \ <span m='102780'>first</span> <span m='103070'>car</span> <span m='103290'>proceeds</span>\
  \ <span m='103750'>out</span> <span m='103930'>of</span> <span m='104010'>the</span>\
  \ <span m='104090'>toll</span> <span m='104350'>both.</span> </p><p><span m='105710'>But</span>\
  \ <span m='105850'>you</span> <span m='105990'>can</span> <span m='106180'>see</span>\
  \ <span m='106610'>that</span> <span m='106800'>the</span> <span m='106880'>timing</span>\
  \ <span m='107470'>of</span> <span m='107650'>when</span> <span m='107960'>to</span>\
  \ <span m='108050'>close</span> <span m='108420'>the</span> <span m='108530'>gate</span>\
  \ <span m='108770'>is</span> <span m='108940'>going</span> <span m='109140'>to</span>\
  \ <span m='109230'>be</span> <span m='109360'>tricky.</span> </p><p><span m='110280'>It</span>\
  \ <span m='110430'>has</span> <span m='110690'>to</span> <span m='110780'>be</span>\
  \ <span m='110950'>open</span> <span m='111250'>long</span> <span m='111500'>enough</span>\
  \ <span m='111730'>for</span> <span m='111850'>the</span> <span m='111950'>first</span>\
  \ <span m='112280'>car</span> <span m='112470'>to</span> <span m='112540'>make</span>\
  \ <span m='112750'>it</span> <span m='112870'>through,</span> <span m='113500'>but</span>\
  \ <span m='113880'>not</span> <span m='114150'>too</span> <span m='114390'>long</span>\
  \ <span m='114790'>lest</span> <span m='115160'>the</span> <span m='115310'>other</span>\
  \ <span m='115520'>cars</span> <span m='115930'>also</span> <span m='116280'>make</span>\
  \ <span m='116510'>it</span> <span m='116610'>through.</span> </p><p><span m='117910'>This</span>\
  \ <span m='118110'>is</span> <span m='118240'>exactly</span> <span m='118830'>the</span>\
  \ <span m='119020'>issue</span> <span m='119260'>we</span> <span m='119420'>faced</span>\
  \ <span m='119940'>with</span> <span m='120240'>using</span> <span m='120580'>the</span>\
  \ <span m='120650'>latch</span> <span m='121110'>as</span> <span m='121200'>our</span>\
  \ <span m='121300'>memory</span> <span m='121640'>component</span> <span m='122190'>in</span>\
  \ <span m='122320'>our</span> <span m='122430'>sequential</span> <span m='123000'>logic.</span>\
  \ </p><p><span m='124570'>So</span> <span m='125140'>how</span> <span m='125570'>do</span>\
  \ <span m='125670'>we</span> <span m='125820'>ensure</span> <span m='126250'>only</span>\
  \ <span m='126510'>one</span> <span m='126880'>car</span> <span m='127220'>makes</span>\
  \ <span m='127520'>it</span> <span m='127610'>through</span> <span m='127820'>the</span>\
  \ <span m='127920'>open</span> <span m='128060'>gate?</span> </p><p><span m='129580'>One</span>\
  \ <span m='129870'>solution</span> <span m='130410'>is</span> <span m='130550'>to</span>\
  \ <span m='130669'>use</span> <span m='130919'>TWO</span> <span m='131140'>gates!</span>\
  \ </p><p><span m='132110'>Here\u2019s</span> <span m='132400'>the</span> <span m='132470'>plan:</span>\
  \ <span m='133260'>Initially</span> <span m='134100'>Gate</span> <span m='134500'>1</span>\
  \ <span m='134650'>is</span> <span m='134930'>open</span> <span m='135380'>allowing</span>\
  \ <span m='135810'>exactly</span> <span m='136240'>one</span> <span m='136550'>car</span>\
  \ <span m='136890'>to</span> <span m='137030'>enter</span> <span m='137260'>the</span>\
  \ <span m='137340'>toll</span> <span m='137630'>booth</span> <span m='138180'>and</span>\
  \ <span m='138550'>Gate</span> <span m='138940'>2</span> <span m='139000'>is</span>\
  \ <span m='139200'>closed.</span> </p><p><span m='140640'>Then</span> <span m='141070'>at</span>\
  \ <span m='141240'>a</span> <span m='141290'>particular</span> <span m='141680'>point</span>\
  \ <span m='142100'>in</span> <span m='142160'>time,</span> <span m='142530'>we</span>\
  \ <span m='142780'>close</span> <span m='143240'>Gate</span> <span m='143450'>1</span>\
  \ <span m='143490'>while</span> <span m='143860'>opening</span> <span m='144570'>Gate</span>\
  \ <span m='145180'>2.</span> </p><p><span m='145820'>This</span> <span m='146060'>lets</span>\
  \ <span m='146330'>the</span> <span m='146420'>car</span> <span m='146830'>in</span>\
  \ <span m='146900'>the</span> <span m='146960'>toll</span> <span m='147250'>booth</span>\
  \ <span m='147520'>proceed</span> <span m='147930'>on,</span> <span m='148350'>but</span>\
  \ <span m='148600'>prevents</span> <span m='149060'>any</span> <span m='149300'>other</span>\
  \ <span m='149530'>car</span> <span m='149790'>from</span> <span m='149960'>passing</span>\
  \ <span m='150360'>through.</span> </p><p><span m='151600'>We</span> <span m='151670'>can</span>\
  \ <span m='151840'>repeat</span> <span m='152300'>this</span> <span m='152520'>two-step</span>\
  \ <span m='153020'>process</span> <span m='153620'>to</span> <span m='153720'>deal</span>\
  \ <span m='153980'>with</span> <span m='154240'>each</span> <span m='154530'>car</span>\
  \ <span m='154990'>one-at-time.</span> </p><p><span m='156640'>The</span> <span\
  \ m='156740'>key</span> <span m='157060'>is</span> <span m='157280'>that</span>\
  \ <span m='157460'>at</span> <span m='157580'>no</span> <span m='157890'>time</span>\
  \ <span m='158330'>is</span> <span m='158560'>there</span> <span m='158750'>a</span>\
  \ <span m='158780'>path</span> <span m='159210'>through</span> <span m='159520'>both</span>\
  \ <span m='159930'>gates.</span> </p><p><span m='162060'>This</span> <span m='162260'>is</span>\
  \ <span m='162390'>the</span> <span m='162450'>same</span> <span m='162730'>arrangement</span>\
  \ <span m='163270'>as</span> <span m='163470'>the</span> <span m='163610'>escapement</span>\
  \ <span m='164310'>mechanism</span> <span m='164900'>in</span> <span m='165010'>a</span>\
  \ <span m='165040'>mechanical</span> <span m='165630'>clock.</span> </p><p><span\
  \ m='166910'>The</span> <span m='167020'>escapement</span> <span m='167640'>ensures</span>\
  \ <span m='168190'>that</span> <span m='168440'>the</span> <span m='168620'>gear</span>\
  \ <span m='168950'>attached</span> <span m='169330'>to</span> <span m='169390'>the</span>\
  \ <span m='169500'>clock\u2019s</span> <span m='169850'>spring</span> <span m='170330'>only</span>\
  \ <span m='170590'>advances</span> <span m='171070'>one</span> <span m='171360'>tooth</span>\
  \ <span m='171670'>at</span> <span m='171770'>a</span> <span m='171820'>time,</span>\
  \ <span m='172450'>preventing</span> <span m='173170'>the</span> <span m='173260'>spring</span>\
  \ <span m='173620'>from</span> <span m='173800'>spinning</span> <span m='174300'>the</span>\
  \ <span m='174410'>gear</span> <span m='174640'>wildly</span> <span m='175470'>causing</span>\
  \ <span m='175920'>a</span> <span m='176010'>whole</span> <span m='176260'>day</span>\
  \ <span m='176540'>to</span> <span m='176640'>pass</span> <span m='176930'>at</span>\
  \ <span m='176990'>once!</span> </p><p><span m='179100'>If</span> <span m='179240'>we</span>\
  \ <span m='179370'>observed</span> <span m='179940'>the</span> <span m='180070'>toll</span>\
  \ <span m='180380'>booth\u2019s</span> <span m='180720'>output,</span> <span m='181510'>we</span>\
  \ <span m='181930'>would</span> <span m='182090'>see</span> <span m='182340'>a</span>\
  \ <span m='182370'>car</span> <span m='182840'>emerge</span> <span m='183350'>shortly</span>\
  \ <span m='183880'>after</span> <span m='184160'>the</span> <span m='184320'>instant</span>\
  \ <span m='184680'>in</span> <span m='184780'>time</span> <span m='185170'>when</span>\
  \ <span m='185320'>Gate</span> <span m='185690'>2</span> <span m='185770'>opens.</span>\
  \ </p><p><span m='187360'>The</span> <span m='187450'>next</span> <span m='187790'>car</span>\
  \ <span m='188090'>would</span> <span m='188280'>emerge</span> <span m='188670'>shortly</span>\
  \ <span m='189100'>after</span> <span m='189330'>the</span> <span m='189430'>next</span>\
  \ <span m='189780'>time</span> <span m='190280'>Gate</span> <span m='190750'>2</span>\
  \ <span m='190840'>opens,</span> <span m='191380'>and</span> <span m='191550'>so</span>\
  \ <span m='191740'>on.</span> </p><p><span m='192900'>Cars</span> <span m='193250'>would</span>\
  \ <span m='193390'>proceed</span> <span m='193850'>through</span> <span m='193950'>the</span>\
  \ <span m='194070'>toll</span> <span m='194380'>booth</span> <span m='194750'>at</span>\
  \ <span m='194900'>a</span> <span m='194940'>rate</span> <span m='195320'>set</span>\
  \ <span m='195560'>by</span> <span m='195690'>the</span> <span m='195890'>interval</span>\
  \ <span m='196400'>between</span> <span m='196800'>Gate</span> <span m='197280'>2</span>\
  \ <span m='197420'>openings.</span> </p><p><span m='199180'>Let\u2019s</span> <span\
  \ m='199390'>apply</span> <span m='199730'>this</span> <span m='199990'>solution</span>\
  \ <span m='200470'>to</span> <span m='200590'>design</span> <span m='201000'>a</span>\
  \ <span m='201050'>memory</span> <span m='201470'>component</span> <span m='201980'>for</span>\
  \ <span m='202090'>our</span> <span m='202230'>sequential</span> <span m='202770'>logic.</span>\
  \ </p><p><span m='204410'>Taking</span> <span m='204780'>our</span> <span m='204920'>cue</span>\
  \ <span m='205300'>from</span> <span m='205500'>the</span> <span m='205730'>2-gate</span>\
  \ <span m='206160'>toll</span> <span m='206480'>both,</span> <span m='206940'>we\u2019\
  ll</span> <span m='207260'>design</span> <span m='207600'>a</span> <span m='207660'>new</span>\
  \ <span m='207900'>component,</span> <span m='208490'>called</span> <span m='208740'>a</span>\
  \ <span m='208790'>D</span> <span m='209010'>register,</span> <span m='209750'>using</span>\
  \ <span m='210260'>two</span> <span m='210620'>back-to-back</span> <span m='211300'>latches.</span>\
  \ </p><p><span m='212560'>The</span> <span m='212650'>load</span> <span m='212960'>signal</span>\
  \ <span m='213290'>for</span> <span m='213530'>a</span> <span m='213560'>D</span>\
  \ <span m='213740'>register</span> <span m='214280'>is</span> <span m='214370'>typically</span>\
  \ <span m='214730'>called</span> <span m='215030'>the</span> <span m='215130'>register\u2019\
  s</span> <span m='215690'>\u201Cclock\u201D,</span> <span m='216410'>but</span>\
  \ <span m='216860'>the</span> <span m='216940'>register\u2019s</span> <span m='217530'>D</span>\
  \ <span m='217740'>input</span> <span m='218110'>and</span> <span m='218300'>Q</span>\
  \ <span m='218580'>output</span> <span m='218970'>play</span> <span m='219140'>the</span>\
  \ <span m='219240'>same</span> <span m='219580'>roles</span> <span m='219910'>as</span>\
  \ <span m='220020'>they</span> <span m='220140'>did</span> <span m='220360'>for</span>\
  \ <span m='220460'>the</span> <span m='220560'>latch.</span> </p><p><span m='222200'>First</span>\
  \ <span m='222530'>we\u2019ll</span> <span m='222660'>describe</span> <span m='223120'>the</span>\
  \ <span m='223210'>internal</span> <span m='223620'>structure</span> <span m='224150'>of</span>\
  \ <span m='224210'>the</span> <span m='224290'>D</span> <span m='224480'>register,</span>\
  \ <span m='225220'>then</span> <span m='225640'>we\u2019ll</span> <span m='225790'>describe</span>\
  \ <span m='226310'>what</span> <span m='226480'>it</span> <span m='226590'>does</span>\
  \ <span m='227180'>and</span> <span m='227440'>look</span> <span m='227610'>in</span>\
  \ <span m='227720'>detail</span> <span m='228250'>at</span> <span m='228400'>how</span>\
  \ <span m='228630'>it</span> <span m='228780'>does</span> <span m='229050'>it.</span>\
  \ </p><p><span m='230470'>The</span> <span m='230560'>D</span> <span m='230840'>input</span>\
  \ <span m='231130'>is</span> <span m='231250'>connected</span> <span m='231700'>to</span>\
  \ <span m='231800'>what</span> <span m='231970'>we</span> <span m='232100'>call</span>\
  \ <span m='232320'>the</span> <span m='232390'>master</span> <span m='232850'>latch</span>\
  \ <span m='233330'>and</span> <span m='233480'>the</span> <span m='233550'>Q</span>\
  \ <span m='233880'>output</span> <span m='234370'>is</span> <span m='234550'>connected</span>\
  \ <span m='235040'>to</span> <span m='235120'>the</span> <span m='235220'>slave</span>\
  \ <span m='235640'>latch.</span> </p><p><span m='237670'>Note</span> <span m='237940'>that</span>\
  \ <span m='238070'>the</span> <span m='238130'>clock</span> <span m='238530'>signal</span>\
  \ <span m='239000'>is</span> <span m='239160'>inverted</span> <span m='239680'>before</span>\
  \ <span m='240090'>it\u2019s</span> <span m='240210'>connected</span> <span m='240720'>to</span>\
  \ <span m='240820'>the</span> <span m='240960'>gate</span> <span m='241310'>input</span>\
  \ <span m='241730'>of</span> <span m='241860'>the</span> <span m='241940'>master</span>\
  \ <span m='242350'>latch.</span> </p><p><span m='243580'>So</span> <span m='243790'>when</span>\
  \ <span m='243970'>the</span> <span m='244050'>master</span> <span m='244570'>latch</span>\
  \ <span m='244890'>is</span> <span m='245040'>open,</span> <span m='245580'>the</span>\
  \ <span m='245720'>slave</span> <span m='246410'>is</span> <span m='246810'>closed,</span>\
  \ <span m='247470'>and</span> <span m='247660'>vice</span> <span m='247940'>versa.</span>\
  \ </p><p><span m='248710'>This</span> <span m='248900'>achieves</span> <span m='249350'>the</span>\
  \ <span m='249550'>escapement</span> <span m='250070'>behavior</span> <span m='250610'>we</span>\
  \ <span m='250730'>saw</span> <span m='251000'>on</span> <span m='251060'>the</span>\
  \ <span m='251140'>previous</span> <span m='251620'>slide:</span> <span m='252220'>at</span>\
  \ <span m='252620'>no</span> <span m='252880'>time</span> <span m='253410'>is</span>\
  \ <span m='253630'>there</span> <span m='253830'>active</span> <span m='254300'>path</span>\
  \ <span m='254670'>from</span> <span m='254870'>the</span> <span m='254950'>register\u2019\
  s</span> <span m='255540'>D</span> <span m='255880'>input</span> <span m='256310'>to</span>\
  \ <span m='256459'>the</span> <span m='256589'>register\u2019s</span> <span m='257170'>Q</span>\
  \ <span m='257440'>output.</span> </p><p><span m='258680'>The</span> <span m='258779'>delay</span>\
  \ <span m='259110'>introduced</span> <span m='259620'>by</span> <span m='259769'>the</span>\
  \ <span m='259890'>inverter</span> <span m='260320'>on</span> <span m='260390'>the</span>\
  \ <span m='260459'>clock</span> <span m='260820'>signal</span> <span m='261160'>might</span>\
  \ <span m='261380'>give</span> <span m='261550'>us</span> <span m='261680'>cause</span>\
  \ <span m='262019'>for</span> <span m='262140'>concern.</span> </p><p><span m='263430'>When</span>\
  \ <span m='263590'>there\u2019s</span> <span m='263770'>a</span> <span m='263800'>rising</span>\
  \ <span m='264330'>0-to-1</span> <span m='264820'>transition</span> <span m='265520'>on</span>\
  \ <span m='265620'>the</span> <span m='265710'>clock</span> <span m='266050'>signal,</span>\
  \ <span m='266720'>might</span> <span m='267210'>there</span> <span m='267360'>be</span>\
  \ <span m='267570'>a</span> <span m='267610'>brief</span> <span m='267970'>interval</span>\
  \ <span m='268430'>when</span> <span m='268690'>the</span> <span m='268820'>gate</span>\
  \ <span m='269110'>signal</span> <span m='269480'>is</span> <span m='269590'>HIGH</span>\
  \ <span m='269920'>for</span> <span m='270060'>both</span> <span m='270320'>latches</span>\
  \ <span m='271050'>since</span> <span m='271450'>there</span> <span m='271560'>will</span>\
  \ <span m='271650'>be</span> <span m='271820'>a</span> <span m='271850'>small</span>\
  \ <span m='272250'>delay</span> <span m='272760'>before</span> <span m='273210'>the</span>\
  \ <span m='273350'>inverter\u2019s</span> <span m='273770'>output</span> <span m='274160'>transitions</span>\
  \ <span m='274850'>from</span> <span m='275150'>1</span> <span m='275250'>to</span>\
  \ <span m='276040'>0?</span> </p><p><span m='276490'>Actually</span> <span m='276940'>the</span>\
  \ <span m='277090'>inverter</span> <span m='277510'>isn\u2019t</span> <span m='277850'>necessary:</span>\
  \ </p><p><span m='279070'>Mr</span> <span m='279390'>Blue</span> <span m='279790'>is</span>\
  \ <span m='279910'>looking</span> <span m='280220'>at</span> <span m='280280'>a</span>\
  \ <span m='280320'>slightly</span> <span m='280750'>different</span> <span m='281160'>latch</span>\
  \ <span m='281490'>schematic</span> <span m='282150'>where</span> <span m='282420'>the</span>\
  \ <span m='282510'>latch</span> <span m='282860'>is</span> <span m='282990'>open</span>\
  \ <span m='283340'>when</span> <span m='283470'>G</span> <span m='283700'>is</span>\
  \ <span m='283870'>LOW</span> <span m='284280'>and</span> <span m='284480'>closed</span>\
  \ <span m='285010'>when</span> <span m='285150'>G</span> <span m='285350'>is</span>\
  \ <span m='285490'>high.</span> </p><p><span m='286520'>Just</span> <span m='286830'>what</span>\
  \ <span m='287000'>we</span> <span m='287130'>need</span> <span m='287390'>for</span>\
  \ <span m='287500'>the</span> <span m='287600'>master</span> <span m='288020'>latch!</span>\
  \ </p><p><span m='289920'>By</span> <span m='290050'>the</span> <span m='290150'>way,</span>\
  \ <span m='290620'>you\u2019ll</span> <span m='290960'>sometimes</span> <span m='291430'>hear</span>\
  \ <span m='291710'>a</span> <span m='291740'>register</span> <span m='292180'>called</span>\
  \ <span m='292440'>a</span> <span m='292490'>flip-flop</span> <span m='293300'>because</span>\
  \ <span m='293740'>of</span> <span m='293820'>the</span> <span m='293910'>bistable</span>\
  \ <span m='294610'>nature</span> <span m='294950'>of</span> <span m='295030'>the</span>\
  \ <span m='295100'>positive</span> <span m='295620'>feedback</span> <span m='296120'>loops</span>\
  \ <span m='296410'>in</span> <span m='296480'>the</span> <span m='296540'>latches.</span>\
  \ </p><p><span m='298710'>That\u2019s</span> <span m='298990'>the</span> <span m='299130'>internal</span>\
  \ <span m='299570'>structure</span> <span m='300000'>of</span> <span m='300060'>the</span>\
  \ <span m='300140'>D</span> <span m='300320'>register.</span> </p><p><span m='301200'>In</span>\
  \ <span m='301290'>the</span> <span m='301360'>next</span> <span m='301640'>section</span>\
  \ <span m='302240'>we\u2019ll</span> <span m='302460'>take</span> <span m='302630'>a</span>\
  \ <span m='302670'>step-by-step</span> <span m='303630'>tour</span> <span m='304160'>of</span>\
  \ <span m='304370'>the</span> <span m='304490'>register</span> <span m='305010'>in</span>\
  \ <span m='305080'>operation.</span> </p>"
type: course
uid: 39c95bb76022dfc482e17f25cc95bcfa

---
None