---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: xd35dftjRrc
  parent_uid: 8a43c6c048fe30831bfc0919fd23d87a
  title: Video-YouTube-Stream
  type: Video
  uid: 04db7ad01bb85044a79d1c8b12bb2f36
- id: 3Play-3Play YouTube id-Stream
  media_location: xd35dftjRrc
  parent_uid: 8a43c6c048fe30831bfc0919fd23d87a
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: bb502d0946fb15b9d5ddaf20565b8228
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/xd35dftjRrc/default.jpg
  parent_uid: 8a43c6c048fe30831bfc0919fd23d87a
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 406844c53e1e098e964f734be81f7e2c
- id: xd35dftjRrc.srt
  parent_uid: 8a43c6c048fe30831bfc0919fd23d87a
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v5/stack-detective-5-57-/xd35dftjRrc.srt
  title: 3play caption file
  type: null
  uid: 196935168c8d4d63bed0d77b9050eab0
- id: xd35dftjRrc.pdf
  parent_uid: 8a43c6c048fe30831bfc0919fd23d87a
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v5/stack-detective-5-57-/xd35dftjRrc.pdf
  title: 3play pdf file
  type: null
  uid: d5d5c5a7885ac9ef8e8052a5fd51df3e
- id: Caption-3Play YouTube id-SRT
  parent_uid: 8a43c6c048fe30831bfc0919fd23d87a
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: c55a70ee01d56c92830e6a6351f189f1
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 8a43c6c048fe30831bfc0919fd23d87a
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 69464c9305b67eaad8c3e284fa7523d8
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_12-02-05_300k.mp4
  parent_uid: 8a43c6c048fe30831bfc0919fd23d87a
  title: Video-Internet Archive-MP4
  type: Video
  uid: e46673dd35045475e5c7d05daa968aaa
inline_embed_id: 69236562stackdetective55766507243
layout: video
order_index: null
parent_uid: bc79d91ca0167cfdbf8756db19f73c62
related_resources_text: ''
short_url: stack-detective-5-57-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v5/stack-detective-5-57-
template_type: Embed
title: Stack Detective (5:57)
transcript: "<p><span m='1040'>Let's</span> <span m='1360'>practice</span> <span m='1681'>our</span>\
  \ <span m='2002'>newfound</span> <span m='2322'>skill</span> <span m='2643'>and</span>\
  \ <span m='2964'>see</span> <span m='3284'>what</span> <span m='3605'>we</span>\
  \ <span m='3926'>can</span> <span m='4246'>determine</span> <span m='4567'>about</span>\
  \ <span m='4888'>a</span> <span m='5208'>running</span> <span m='5529'>program</span>\
  \ <span m='5850'>which</span> <span m='6236'>we've</span> <span m='6622'>stopped</span>\
  \ <span m='7008'>somewhere</span> <span m='7394'>in</span> <span m='7780'>the</span>\
  \ <span m='8166'>middle</span> <span m='8552'>of</span> <span m='8938'>its</span>\
  \ <span m='9324'>execution.</span> </p><p><span m='9710'>We're</span> <span m='10012'>told</span>\
  \ <span m='10315'>that</span> <span m='10618'>a</span> <span m='10921'>computation</span>\
  \ <span m='11223'>of</span> <span m='11526'>fact()</span> <span m='11829'>is</span>\
  \ <span m='12132'>in</span> <span m='12435'>progress</span> <span m='12737'>and</span>\
  \ <span m='13040'>that</span> <span m='13343'>the</span> <span m='13646'>PC</span>\
  \ <span m='13948'>of</span> <span m='14251'>the</span> <span m='14554'>next</span>\
  \ <span m='14857'>instruction</span> <span m='15160'>to</span> <span m='15722'>be</span>\
  \ <span m='16284'>executed</span> <span m='16846'>is</span> <span m='17408'>0x40.</span>\
  \ </p><p><span m='17970'>We're</span> <span m='18397'>also</span> <span m='18825'>given</span>\
  \ <span m='19253'>the</span> <span m='19681'>stack</span> <span m='20108'>dump</span>\
  \ <span m='20536'>shown</span> <span m='20964'>on</span> <span m='21392'>right.</span>\
  \ </p><p><span m='21820'>Since</span> <span m='22107'>we're</span> <span m='22394'>in</span>\
  \ <span m='22681'>the</span> <span m='22968'>middle</span> <span m='23255'>of</span>\
  \ <span m='23542'>a</span> <span m='23829'>fact</span> <span m='24116'>computation,</span>\
  \ <span m='24403'>we</span> <span m='24690'>know</span> <span m='24977'>that</span>\
  \ <span m='25264'>current</span> <span m='25551'>stack</span> <span m='25838'>frame</span>\
  \ <span m='26125'>(and</span> <span m='26412'>possibly</span> <span m='26700'>others)</span>\
  \ <span m='27131'>is</span> <span m='27562'>an</span> <span m='27993'>activation</span>\
  \ <span m='28424'>record</span> <span m='28855'>for</span> <span m='29286'>the</span>\
  \ <span m='29717'>fact</span> <span m='30148'>function.</span> </p><p><span m='30579'>Using</span>\
  \ <span m='30890'>the</span> <span m='31201'>code</span> <span m='31512'>on</span>\
  \ <span m='31823'>the</span> <span m='32135'>previous</span> <span m='32446'>slide</span>\
  \ <span m='32757'>we</span> <span m='33068'>can</span> <span m='33380'>determine</span>\
  \ <span m='33691'>the</span> <span m='34002'>layout</span> <span m='34313'>of</span>\
  \ <span m='34625'>the</span> <span m='34936'>stack</span> <span m='35247'>frame</span>\
  \ <span m='35558'>and</span> <span m='35870'>generate</span> <span m='36286'>the</span>\
  \ <span m='36702'>annotations</span> <span m='37119'>shown</span> <span m='37535'>on</span>\
  \ <span m='37951'>the</span> <span m='38368'>right</span> <span m='38784'>of</span>\
  \ <span m='39200'>the</span> <span m='39617'>stack</span> <span m='40033'>dump.</span>\
  \ </p><p><span m='40450'>With</span> <span m='40796'>the</span> <span m='41142'>annotations,</span>\
  \ <span m='41488'>it's</span> <span m='41835'>easy</span> <span m='42181'>to</span>\
  \ <span m='42527'>see</span> <span m='42873'>that</span> <span m='43220'>the</span>\
  \ <span m='43566'>argument</span> <span m='43912'>to</span> <span m='44258'>current</span>\
  \ <span m='44605'>active</span> <span m='44951'>call</span> <span m='45297'>is</span>\
  \ <span m='45643'>the</span> <span m='45990'>value</span> <span m='47430'>3.</span>\
  \ </p><p><span m='48870'>Now</span> <span m='49252'>we</span> <span m='49635'>want</span>\
  \ <span m='50017'>to</span> <span m='50400'>know</span> <span m='50782'>the</span>\
  \ <span m='51165'>argument</span> <span m='51547'>to</span> <span m='51930'>original</span>\
  \ <span m='52312'>call</span> <span m='52695'>to</span> <span m='53077'>fact.</span>\
  \ </p><p><span m='53460'>We'll</span> <span m='53806'>have</span> <span m='54152'>to</span>\
  \ <span m='54498'>label</span> <span m='54844'>the</span> <span m='55190'>other</span>\
  \ <span m='55536'>stack</span> <span m='55883'>frames</span> <span m='56229'>using</span>\
  \ <span m='56575'>the</span> <span m='56921'>saved</span> <span m='57267'>BP</span>\
  \ <span m='57613'>values.</span> </p><p><span m='57960'>Looking</span> <span m='58295'>at</span>\
  \ <span m='58631'>the</span> <span m='58966'>saved</span> <span m='59302'>LP</span>\
  \ <span m='59637'>values</span> <span m='59973'>for</span> <span m='60308'>each</span>\
  \ <span m='60644'>frame</span> <span m='60980'>(always</span> <span m='61315'>found</span>\
  \ <span m='61651'>at</span> <span m='61986'>an</span> <span m='62322'>offset</span>\
  \ <span m='62657'>of</span> <span m='62993'>-8</span> <span m='63328'>from</span>\
  \ <span m='63664'>the</span> <span m='64000'>frame's</span> <span m='64348'>BP),</span>\
  \ <span m='64697'>we</span> <span m='65046'>see</span> <span m='65395'>that</span>\
  \ <span m='65744'>many</span> <span m='66092'>of</span> <span m='66441'>the</span>\
  \ <span m='66790'>saved</span> <span m='67139'>values</span> <span m='67488'>are</span>\
  \ <span m='67837'>0x40,</span> <span m='68185'>which</span> <span m='68534'>must</span>\
  \ <span m='68883'>be</span> <span m='69232'>the</span> <span m='69581'>return</span>\
  \ <span m='69930'>address</span> <span m='70573'>for</span> <span m='71216'>the</span>\
  \ <span m='71859'>recursive</span> <span m='72502'>fact</span> <span m='73145'>calls.</span>\
  \ </p><p><span m='73789'>Looking</span> <span m='74139'>through</span> <span m='74490'>the</span>\
  \ <span m='74841'>stack</span> <span m='75191'>frames</span> <span m='75542'>we</span>\
  \ <span m='75893'>find</span> <span m='76244'>the</span> <span m='76594'>first</span>\
  \ <span m='76945'>return</span> <span m='77296'>address</span> <span m='77647'>that's</span>\
  \ <span m='77997'>*not*</span> <span m='78348'>0x40,</span> <span m='78699'>which</span>\
  \ <span m='79050'>must</span> <span m='79426'>an</span> <span m='79803'>return</span>\
  \ <span m='80180'>address</span> <span m='80557'>to</span> <span m='80934'>code</span>\
  \ <span m='81311'>that's</span> <span m='81688'>not</span> <span m='82065'>part</span>\
  \ <span m='82442'>of</span> <span m='82819'>the</span> <span m='83196'>fact</span>\
  \ <span m='83573'>procedure.</span> </p><p><span m='83950'>This</span> <span m='84243'>means</span>\
  \ <span m='84536'>we've</span> <span m='84829'>found</span> <span m='85123'>the</span>\
  \ <span m='85416'>stack</span> <span m='85709'>frame</span> <span m='86002'>created</span>\
  \ <span m='86296'>by</span> <span m='86589'>the</span> <span m='86882'>original</span>\
  \ <span m='87176'>call</span> <span m='87469'>to</span> <span m='87762'>fact</span>\
  \ <span m='88055'>and</span> <span m='88349'>can</span> <span m='88642'>see</span>\
  \ <span m='88935'>that</span> <span m='89229'>argument</span> <span m='89692'>to</span>\
  \ <span m='90155'>the</span> <span m='90618'>original</span> <span m='91081'>call</span>\
  \ <span m='91544'>is</span> <span m='92007'>6.</span> </p><p><span m='92470'>What's</span>\
  \ <span m='92902'>the</span> <span m='93335'>location</span> <span m='93767'>of</span>\
  \ <span m='94200'>the</span> <span m='94633'>BR</span> <span m='95065'>that</span>\
  \ <span m='95498'>made</span> <span m='95931'>the</span> <span m='96363'>original</span>\
  \ <span m='96796'>call?</span> </p><p><span m='97229'>Well,</span> <span m='97608'>the</span>\
  \ <span m='97987'>saved</span> <span m='98367'>LP</span> <span m='98746'>in</span>\
  \ <span m='99126'>the</span> <span m='99505'>stack</span> <span m='99885'>frame</span>\
  \ <span m='100264'>of</span> <span m='100643'>the</span> <span m='101023'>original</span>\
  \ <span m='101402'>call</span> <span m='101782'>to</span> <span m='102161'>fact</span>\
  \ <span m='102541'>is</span> <span m='102920'>0x80.</span> </p><p><span m='103300'>That's</span>\
  \ <span m='103681'>the</span> <span m='104062'>address</span> <span m='104443'>of</span>\
  \ <span m='104825'>the</span> <span m='105206'>instruction</span> <span m='105587'>following</span>\
  \ <span m='105968'>the</span> <span m='106350'>original</span> <span m='106731'>call,</span>\
  \ <span m='107112'>so</span> <span m='107493'>the</span> <span m='107875'>BR</span>\
  \ <span m='108256'>that</span> <span m='108637'>made</span> <span m='109018'>the</span>\
  \ <span m='109400'>original</span> <span m='110003'>call</span> <span m='110606'>is</span>\
  \ <span m='111210'>one</span> <span m='111813'>instruction</span> <span m='112416'>earlier,</span>\
  \ <span m='113020'>at</span> <span m='113623'>location</span> <span m='114226'>0x7C.</span>\
  \ </p><p><span m='114830'>To</span> <span m='115246'>answer</span> <span m='115663'>these</span>\
  \ <span m='116080'>questions</span> <span m='116496'>you</span> <span m='116913'>have</span>\
  \ <span m='117330'>to</span> <span m='117746'>be</span> <span m='118163'>good</span>\
  \ <span m='118580'>at</span> <span m='118996'>hex</span> <span m='119413'>arithmetic!</span>\
  \ </p><p><span m='119830'>What</span> <span m='120311'>instruction</span> <span\
  \ m='120792'>is</span> <span m='121274'>about</span> <span m='121755'>to</span>\
  \ <span m='122237'>be</span> <span m='122718'>executed?</span> </p><p><span m='123200'>We</span>\
  \ <span m='123533'>were</span> <span m='123866'>told</span> <span m='124199'>its</span>\
  \ <span m='124532'>address</span> <span m='124865'>is</span> <span m='125198'>0x40,</span>\
  \ <span m='125531'>which</span> <span m='125864'>we</span> <span m='126197'>notice</span>\
  \ <span m='126531'>is</span> <span m='126864'>the</span> <span m='127197'>saved</span>\
  \ <span m='127530'>LP</span> <span m='127863'>value</span> <span m='128196'>for</span>\
  \ <span m='128529'>all</span> <span m='128862'>the</span> <span m='129195'>recursive</span>\
  \ <span m='129529'>fact</span> <span m='130218'>calls.</span> </p><p><span m='130908'>So</span>\
  \ <span m='131316'>0x40</span> <span m='131724'>must</span> <span m='132132'>be</span>\
  \ <span m='132540'>the</span> <span m='132948'>address</span> <span m='133356'>of</span>\
  \ <span m='133764'>the</span> <span m='134172'>instruction</span> <span m='134580'>following</span>\
  \ <span m='134988'>the</span> <span m='135396'>BR(fact,LP)</span> <span m='135804'>instruction</span>\
  \ <span m='136212'>in</span> <span m='136620'>the</span> <span m='137029'>fact</span>\
  \ <span m='137789'>code.</span> </p><p><span m='138549'>Looking</span> <span m='139022'>back</span>\
  \ <span m='139495'>a</span> <span m='139969'>few</span> <span m='140442'>slides</span>\
  \ <span m='140916'>at</span> <span m='141389'>the</span> <span m='141862'>fact</span>\
  \ <span m='142336'>code,</span> <span m='142809'>we</span> <span m='143283'>see</span>\
  \ <span m='143756'>that's</span> <span m='144229'>a</span> <span m='144703'>DEALLOCATE(1)</span>\
  \ <span m='145176'>instruction.</span> </p><p><span m='145650'>What</span> <span\
  \ m='146073'>value</span> <span m='146497'>is</span> <span m='146921'>in</span>\
  \ <span m='147345'>BP?</span> </p><p><span m='147769'>Hmm.</span> </p><p><span m='149159'>We</span>\
  \ <span m='149482'>know</span> <span m='149806'>BP</span> <span m='150130'>is</span>\
  \ <span m='150454'>the</span> <span m='150778'>address</span> <span m='151102'>of</span>\
  \ <span m='151426'>the</span> <span m='151750'>stack</span> <span m='152074'>location</span>\
  \ <span m='152397'>containing</span> <span m='152721'>the</span> <span m='153045'>saved</span>\
  \ <span m='153369'>R1</span> <span m='153693'>value</span> <span m='154017'>in</span>\
  \ <span m='154341'>the</span> <span m='154665'>current</span> <span m='154989'>stack</span>\
  \ <span m='155953'>frame.</span> </p><p><span m='156918'>So</span> <span m='157212'>the</span>\
  \ <span m='157507'>saved</span> <span m='157801'>BP</span> <span m='158096'>value</span>\
  \ <span m='158390'>in</span> <span m='158685'>the</span> <span m='158979'>current</span>\
  \ <span m='159274'>stack</span> <span m='159568'>frame</span> <span m='159863'>is</span>\
  \ <span m='160157'>the</span> <span m='160452'>address</span> <span m='160746'>of</span>\
  \ <span m='161041'>the</span> <span m='161335'>saved</span> <span m='161630'>R1</span>\
  \ <span m='161924'>value</span> <span m='162219'>in</span> <span m='162761'>the</span>\
  \ <span m='163303'>*previous*</span> <span m='163845'>stack</span> <span m='164387'>frame.</span>\
  \ </p><p><span m='164930'>So</span> <span m='165244'>the</span> <span m='165559'>saved</span>\
  \ <span m='165874'>BP</span> <span m='166189'>value</span> <span m='166504'>gives</span>\
  \ <span m='166819'>us</span> <span m='167134'>the</span> <span m='167449'>address</span>\
  \ <span m='167764'>of</span> <span m='168079'>a</span> <span m='168394'>particular</span>\
  \ <span m='168709'>stack</span> <span m='169024'>location,</span> <span m='169339'>from</span>\
  \ <span m='169654'>which</span> <span m='169969'>we</span> <span m='170355'>can</span>\
  \ <span m='170741'>derive</span> <span m='171127'>the</span> <span m='171513'>address</span>\
  \ <span m='171899'>of</span> <span m='172285'>all</span> <span m='172671'>the</span>\
  \ <span m='173057'>other</span> <span m='173443'>locations!</span> </p><p><span\
  \ m='173829'>Counting</span> <span m='174400'>forward,</span> <span m='174972'>we</span>\
  \ <span m='175544'>find</span> <span m='176115'>that</span> <span m='176687'>the</span>\
  \ <span m='177259'>value</span> <span m='177830'>in</span> <span m='178402'>BP</span>\
  \ <span m='178974'>must</span> <span m='179545'>be</span> <span m='180117'>0x13C.</span>\
  \ </p><p><span m='180689'>What</span> <span m='181273'>value</span> <span m='181857'>is</span>\
  \ <span m='182441'>in</span> <span m='183025'>SP?</span> </p><p><span m='183610'>Since</span>\
  \ <span m='183894'>we're</span> <span m='184178'>about</span> <span m='184462'>to</span>\
  \ <span m='184746'>execute</span> <span m='185030'>the</span> <span m='185314'>DEALLOCATE</span>\
  \ <span m='185598'>to</span> <span m='185882'>remove</span> <span m='186166'>the</span>\
  \ <span m='186450'>argument</span> <span m='186734'>of</span> <span m='187018'>the</span>\
  \ <span m='187302'>nested</span> <span m='187586'>call</span> <span m='187870'>from</span>\
  \ <span m='188228'>the</span> <span m='188586'>stack,</span> <span m='188944'>that</span>\
  \ <span m='189302'>argument</span> <span m='189660'>must</span> <span m='190019'>still</span>\
  \ <span m='190377'>be</span> <span m='190735'>on</span> <span m='191093'>the</span>\
  \ <span m='191451'>stack</span> <span m='191809'>right</span> <span m='192168'>after</span>\
  \ <span m='192526'>the</span> <span m='192884'>saved</span> <span m='193242'>R1</span>\
  \ <span m='193600'>value.</span> </p><p><span m='193959'>Since</span> <span m='194323'>the</span>\
  \ <span m='194687'>SP</span> <span m='195051'>points</span> <span m='195415'>to</span>\
  \ <span m='195779'>first</span> <span m='196143'>unused</span> <span m='196507'>stack</span>\
  \ <span m='196871'>location,</span> <span m='197235'>it</span> <span m='197599'>points</span>\
  \ <span m='197963'>to</span> <span m='198327'>the</span> <span m='198691'>location</span>\
  \ <span m='199055'>after</span> <span m='199420'>that</span> <span m='199971'>word,</span>\
  \ <span m='200522'>so</span> <span m='201073'>it</span> <span m='201624'>has</span>\
  \ <span m='202175'>the</span> <span m='202726'>value</span> <span m='203277'>0x144.</span>\
  \ </p><p><span m='203829'>Finally,</span> <span m='204610'>what</span> <span m='205392'>value</span>\
  \ <span m='206174'>is</span> <span m='206955'>in</span> <span m='207737'>R0?</span>\
  \ </p><p><span m='208519'>Since</span> <span m='208828'>we've</span> <span m='209138'>just</span>\
  \ <span m='209447'>returned</span> <span m='209757'>from</span> <span m='210066'>a</span>\
  \ <span m='210376'>call</span> <span m='210685'>to</span> <span m='210995'>fact(2)</span>\
  \ <span m='211304'>the</span> <span m='211614'>value</span> <span m='211923'>in</span>\
  \ <span m='212233'>R0</span> <span m='212542'>must</span> <span m='212852'>the</span>\
  \ <span m='213161'>result</span> <span m='213471'>from</span> <span m='213780'>that</span>\
  \ <span m='214090'>recursive</span> <span m='214552'>call,</span> <span m='215014'>which</span>\
  \ <span m='215476'>is</span> <span m='215938'>2.</span> </p><p><span m='216400'>Wow!</span>\
  \ </p><p><span m='217400'>You</span> <span m='217814'>can</span> <span m='218228'>learn</span>\
  \ <span m='218642'>a</span> <span m='219057'>lot</span> <span m='219471'>from</span>\
  \ <span m='219885'>the</span> <span m='220300'>stacked</span> <span m='220714'>activation</span>\
  \ <span m='221128'>records</span> <span m='221542'>and</span> <span m='221957'>a</span>\
  \ <span m='222371'>little</span> <span m='222785'>deduction!</span> </p><p><span\
  \ m='223200'>Since</span> <span m='223537'>the</span> <span m='223875'>state</span>\
  \ <span m='224212'>of</span> <span m='224550'>the</span> <span m='224888'>computation</span>\
  \ <span m='225225'>is</span> <span m='225563'>represented</span> <span m='225901'>by</span>\
  \ <span m='226238'>the</span> <span m='226576'>values</span> <span m='226914'>of</span>\
  \ <span m='227251'>the</span> <span m='227589'>PC,</span> <span m='227927'>the</span>\
  \ <span m='228264'>registers,</span> <span m='228602'>and</span> <span m='228940'>main</span>\
  \ <span m='229279'>memory,</span> <span m='229619'>once</span> <span m='229959'>we're</span>\
  \ <span m='230299'>given</span> <span m='230639'>that</span> <span m='230979'>information</span>\
  \ <span m='231319'>we</span> <span m='231659'>can</span> <span m='231999'>tell</span>\
  \ <span m='232339'>exactly</span> <span m='232679'>what</span> <span m='233019'>the</span>\
  \ <span m='233359'>program</span> <span m='233699'>has</span> <span m='234039'>been</span>\
  \ <span m='234379'>up</span> <span m='235044'>to.</span> </p><p><span m='235709'>Pretty</span>\
  \ <span m='236754'>neat\u2026</span> <span m='237799'>Wrapping</span> <span m='238147'>up,</span>\
  \ <span m='238496'>we've</span> <span m='238844'>been</span> <span m='239193'>dedicating</span>\
  \ <span m='239542'>some</span> <span m='239890'>registers</span> <span m='240239'>to</span>\
  \ <span m='240588'>help</span> <span m='240936'>with</span> <span m='241285'>our</span>\
  \ <span m='241634'>various</span> <span m='241982'>software</span> <span m='242331'>conventions.</span>\
  \ </p><p><span m='242680'>To</span> <span m='243213'>summarize:</span> <span m='243747'>R31</span>\
  \ <span m='244280'>is</span> <span m='244814'>always</span> <span m='245347'>zero,</span>\
  \ <span m='245881'>as</span> <span m='246414'>defined</span> <span m='246948'>by</span>\
  \ <span m='247481'>the</span> <span m='248015'>ISA.</span> </p><p><span m='248549'>We'll</span>\
  \ <span m='248957'>also</span> <span m='249365'>dedicate</span> <span m='249773'>R30</span>\
  \ <span m='250181'>to</span> <span m='250589'>a</span> <span m='250997'>particular</span>\
  \ <span m='251405'>function</span> <span m='251814'>in</span> <span m='252222'>the</span>\
  \ <span m='252630'>ISA</span> <span m='253038'>when</span> <span m='253446'>we</span>\
  \ <span m='253854'>discuss</span> <span m='254262'>the</span> <span m='254670'>implementation</span>\
  \ <span m='255079'>of</span> <span m='255377'>the</span> <span m='255676'>Beta</span>\
  \ <span m='255975'>in</span> <span m='256273'>the</span> <span m='256572'>next</span>\
  \ <span m='256871'>lecture.</span> </p><p><span m='257170'>Meanwhile,</span> <span\
  \ m='257644'>don't</span> <span m='258118'>use</span> <span m='258592'>R30</span>\
  \ <span m='259066'>in</span> <span m='259540'>your</span> <span m='260014'>code!</span>\
  \ </p><p><span m='260488'>The</span> <span m='261059'>remaining</span> <span m='261630'>dedicated</span>\
  \ <span m='262201'>registers</span> <span m='262772'>are</span> <span m='263344'>connected</span>\
  \ <span m='263915'>with</span> <span m='264486'>our</span> <span m='265057'>software</span>\
  \ <span m='265628'>conventions:</span> <span m='266200'>R29</span> <span m='266735'>(SP)</span>\
  \ <span m='267271'>is</span> <span m='267807'>used</span> <span m='268343'>as</span>\
  \ <span m='268879'>the</span> <span m='269415'>stack</span> <span m='269951'>pointer,</span>\
  \ <span m='270487'>R28</span> <span m='271022'>(LP)</span> <span m='271558'>is</span>\
  \ <span m='272094'>used</span> <span m='272630'>as</span> <span m='273166'>the</span>\
  \ <span m='273702'>linkage</span> <span m='274238'>pointer,</span> <span m='274774'>and</span>\
  \ <span m='275310'>R27</span> <span m='275918'>(BP)</span> <span m='276527'>is</span>\
  \ <span m='277136'>used</span> <span m='277745'>as</span> <span m='278353'>the</span>\
  \ <span m='278962'>base</span> <span m='279571'>pointer.</span> </p><p><span m='280180'>As</span>\
  \ <span m='280470'>you</span> <span m='280760'>practice</span> <span m='281050'>reading</span>\
  \ <span m='281340'>and</span> <span m='281630'>writing</span> <span m='281920'>code,</span>\
  \ <span m='282210'>you'll</span> <span m='282500'>grow</span> <span m='282790'>familiar</span>\
  \ <span m='283080'>with</span> <span m='283370'>these</span> <span m='283660'>dedicated</span>\
  \ <span m='283950'>registers.</span> </p><p><span m='287380'>In</span> <span m='287738'>thinking</span>\
  \ <span m='288097'>about</span> <span m='288456'>how</span> <span m='288814'>to</span>\
  \ <span m='289173'>implement</span> <span m='289532'>procedures,</span> <span m='289890'>we</span>\
  \ <span m='290249'>discovered</span> <span m='290608'>the</span> <span m='290966'>need</span>\
  \ <span m='291325'>for</span> <span m='291684'>an</span> <span m='292042'>activation</span>\
  \ <span m='292401'>record</span> <span m='292760'>to</span> <span m='293219'>store</span>\
  \ <span m='293678'>the</span> <span m='294137'>information</span> <span m='294596'>needed</span>\
  \ <span m='295055'>by</span> <span m='295514'>any</span> <span m='295973'>active</span>\
  \ <span m='296432'>procedure</span> <span m='296891'>call.</span> </p><p><span m='297350'>An</span>\
  \ <span m='297691'>activation</span> <span m='298032'>record</span> <span m='298373'>is</span>\
  \ <span m='298714'>created</span> <span m='299055'>by</span> <span m='299397'>the</span>\
  \ <span m='299738'>caller</span> <span m='300079'>and</span> <span m='300420'>callee</span>\
  \ <span m='300761'>at</span> <span m='301102'>the</span> <span m='301444'>start</span>\
  \ <span m='301785'>of</span> <span m='302126'>a</span> <span m='302467'>procedure</span>\
  \ <span m='302808'>call.</span> </p><p><span m='303150'>And</span> <span m='303548'>the</span>\
  \ <span m='303946'>record</span> <span m='304344'>can</span> <span m='304742'>be</span>\
  \ <span m='305140'>discarded</span> <span m='305539'>when</span> <span m='305937'>the</span>\
  \ <span m='306335'>procedure</span> <span m='306733'>is</span> <span m='307131'>complete.</span>\
  \ </p><p><span m='307530'>The</span> <span m='307936'>activation</span> <span m='308342'>records</span>\
  \ <span m='308748'>hold</span> <span m='309154'>argument</span> <span m='309560'>values,</span>\
  \ <span m='309966'>saved</span> <span m='310372'>LP</span> <span m='310778'>and</span>\
  \ <span m='311184'>BP</span> <span m='311590'>values</span> <span m='311996'>along</span>\
  \ <span m='312402'>with</span> <span m='312808'>the</span> <span m='313214'>caller's</span>\
  \ <span m='313620'>values</span> <span m='314221'>in</span> <span m='314822'>any</span>\
  \ <span m='315424'>other</span> <span m='316025'>of</span> <span m='316627'>the</span>\
  \ <span m='317228'>registers.</span> </p><p><span m='317830'>Storage</span> <span\
  \ m='318281'>for</span> <span m='318733'>the</span> <span m='319184'>procedure's</span>\
  \ <span m='319636'>local</span> <span m='320087'>variables</span> <span m='320539'>is</span>\
  \ <span m='320990'>also</span> <span m='321442'>allocated</span> <span m='321893'>in</span>\
  \ <span m='322345'>the</span> <span m='322796'>activation</span> <span m='323248'>record.</span>\
  \ </p><p><span m='323700'>We</span> <span m='323998'>use</span> <span m='324297'>BP</span>\
  \ <span m='324596'>to</span> <span m='324895'>point</span> <span m='325194'>to</span>\
  \ <span m='325492'>the</span> <span m='325791'>current</span> <span m='326090'>activation</span>\
  \ <span m='326389'>record,</span> <span m='326688'>giving</span> <span m='326987'>easy</span>\
  \ <span m='327285'>access</span> <span m='327584'>the</span> <span m='327883'>values</span>\
  \ <span m='328182'>of</span> <span m='328481'>the</span> <span m='328780'>arguments</span>\
  \ <span m='329685'>and</span> <span m='330590'>local</span> <span m='331495'>variables.</span>\
  \ </p><p><span m='332400'>We</span> <span m='332795'>adopted</span> <span m='333191'>a</span>\
  \ <span m='333587'>\"callee</span> <span m='333982'>saves\"</span> <span m='334378'>convention</span>\
  \ <span m='334774'>where</span> <span m='335170'>the</span> <span m='335565'>called</span>\
  \ <span m='335961'>procedure</span> <span m='336357'>is</span> <span m='336752'>obligated</span>\
  \ <span m='337148'>to</span> <span m='337544'>preserve</span> <span m='337940'>the</span>\
  \ <span m='338512'>values</span> <span m='339085'>in</span> <span m='339657'>all</span>\
  \ <span m='340230'>registers</span> <span m='340802'>except</span> <span m='341375'>for</span>\
  \ <span m='341947'>R0.</span> </p><p><span m='342520'>Taken</span> <span m='342875'>together,</span>\
  \ <span m='343230'>these</span> <span m='343585'>conventions</span> <span m='343940'>allow</span>\
  \ <span m='344295'>us</span> <span m='344650'>to</span> <span m='345005'>have</span>\
  \ <span m='345360'>procedures</span> <span m='345715'>with</span> <span m='346070'>arbitrary</span>\
  \ <span m='346425'>numbers</span> <span m='346780'>of</span> <span m='347227'>arguments</span>\
  \ <span m='347674'>and</span> <span m='348121'>local</span> <span m='348569'>variables,</span>\
  \ <span m='349016'>with</span> <span m='349463'>nested</span> <span m='349910'>and</span>\
  \ <span m='350358'>recursive</span> <span m='350805'>procedure</span> <span m='351252'>calls.</span>\
  \ </p><p><span m='351700'>We're</span> <span m='352114'>now</span> <span m='352528'>ready</span>\
  \ <span m='352942'>to</span> <span m='353356'>compile</span> <span m='353770'>and</span>\
  \ <span m='354184'>execute</span> <span m='354598'>any</span> <span m='355012'>C</span>\
  \ <span m='355426'>program!</span> </p>"
type: course
uid: 8a43c6c048fe30831bfc0919fd23d87a

---
None