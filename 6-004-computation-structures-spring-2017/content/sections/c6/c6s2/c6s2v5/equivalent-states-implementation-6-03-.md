---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: Ht_tyuAWmpM
  parent_uid: 4f2b76f260986193c8a02221bbcbcddf
  title: Video-YouTube-Stream
  type: Video
  uid: a967d66cc901fbbd48b3ae9dd361eeb1
- id: 3Play-3Play YouTube id-Stream
  media_location: Ht_tyuAWmpM
  parent_uid: 4f2b76f260986193c8a02221bbcbcddf
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: f0e99893d25cac9c8406bccfa3c8faea
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/Ht_tyuAWmpM/default.jpg
  parent_uid: 4f2b76f260986193c8a02221bbcbcddf
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: bf0084e9791f3e200494b27f8f33b1de
- id: Ht_tyuAWmpM.srt
  parent_uid: 4f2b76f260986193c8a02221bbcbcddf
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v5/equivalent-states-implementation-6-03-/Ht_tyuAWmpM.srt
  title: 3play caption file
  type: null
  uid: 815ea6249da40acdc6cb51d561782c2d
- id: Ht_tyuAWmpM.pdf
  parent_uid: 4f2b76f260986193c8a02221bbcbcddf
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v5/equivalent-states-implementation-6-03-/Ht_tyuAWmpM.pdf
  title: 3play pdf file
  type: null
  uid: e4a869c0838a0cb4f6e240a20d9ac3d7
- id: Caption-3Play YouTube id-SRT
  parent_uid: 4f2b76f260986193c8a02221bbcbcddf
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 4af65c7f8196d4643e5eb185b78e8728
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 4f2b76f260986193c8a02221bbcbcddf
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 04f661921b2b440bce880a3e50da0fbf
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_06-02-05_300k.mp4
  parent_uid: 4f2b76f260986193c8a02221bbcbcddf
  title: Video-Internet Archive-MP4
  type: Video
  uid: 6a3d8817e24f758ab933c5f94fcb651f
inline_embed_id: 75388787equivalentstatesimplementation60387844997
layout: video
order_index: null
parent_uid: f0b1607feccd43f3495a7ff9b0fbd1b9
related_resources_text: ''
short_url: equivalent-states-implementation-6-03-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v5/equivalent-states-implementation-6-03-
template_type: Embed
title: Equivalent States; Implementation (6:03)
transcript: "<p><span m='859'>Earlier</span> <span m='1314'>we</span> <span m='1770'>talked</span>\
  \ <span m='2225'>about</span> <span m='2681'>about</span> <span m='3136'>finding</span>\
  \ <span m='3592'>equivalent</span> <span m='4047'>FSMs</span> <span m='4503'>with</span>\
  \ <span m='4958'>fewer</span> <span m='5414'>states.</span> </p><p><span m='5870'>Now</span>\
  \ <span m='6185'>we'll</span> <span m='6500'>develop</span> <span m='6815'>an</span>\
  \ <span m='7130'>approach</span> <span m='7445'>for</span> <span m='7760'>finding</span>\
  \ <span m='8075'>such</span> <span m='8390'>FSMs</span> <span m='8705'>by</span>\
  \ <span m='9020'>looking</span> <span m='9335'>for</span> <span m='9650'>two</span>\
  \ <span m='9965'>states</span> <span m='10280'>that</span> <span m='10595'>that</span>\
  \ <span m='10910'>can</span> <span m='11245'>be</span> <span m='11580'>merged</span>\
  \ <span m='11915'>into</span> <span m='12251'>a</span> <span m='12586'>single</span>\
  \ <span m='12921'>state</span> <span m='13257'>without</span> <span m='13592'>changing</span>\
  \ <span m='13927'>the</span> <span m='14262'>behavior</span> <span m='14598'>of</span>\
  \ <span m='14933'>the</span> <span m='15268'>FSM</span> <span m='15604'>in</span>\
  \ <span m='15939'>any</span> <span m='16274'>externally</span> <span m='16610'>distinguishable</span>\
  \ <span m='18145'>manner.</span> </p><p><span m='19680'>Two</span> <span m='20026'>states</span>\
  \ <span m='20372'>are</span> <span m='20719'>equivalent</span> <span m='21065'>if</span>\
  \ <span m='21411'>they</span> <span m='21758'>meet</span> <span m='22104'>the</span>\
  \ <span m='22450'>following</span> <span m='22797'>two</span> <span m='23143'>criteria.</span>\
  \ </p><p><span m='23490'>First,</span> <span m='24105'>the</span> <span m='24721'>states</span>\
  \ <span m='25337'>must</span> <span m='25952'>have</span> <span m='26568'>identical</span>\
  \ <span m='27184'>outputs.</span> </p><p><span m='27800'>This</span> <span m='28127'>makes</span>\
  \ <span m='28454'>sense:</span> <span m='28782'>the</span> <span m='29109'>outputs</span>\
  \ <span m='29436'>are</span> <span m='29764'>visible</span> <span m='30091'>to</span>\
  \ <span m='30418'>the</span> <span m='30746'>outside,</span> <span m='31073'>so</span>\
  \ <span m='31400'>if</span> <span m='31728'>their</span> <span m='32055'>values</span>\
  \ <span m='32382'>differed</span> <span m='32710'>between</span> <span m='33193'>the</span>\
  \ <span m='33677'>two</span> <span m='34160'>states,</span> <span m='34644'>that</span>\
  \ <span m='35128'>difference</span> <span m='35611'>would</span> <span m='36095'>clearly</span>\
  \ <span m='36579'>be</span> <span m='37062'>externally</span> <span m='37546'>distinguishable!</span>\
  \ </p><p><span m='38030'>Second,</span> <span m='38642'>for</span> <span m='39254'>each</span>\
  \ <span m='39866'>combination</span> <span m='40478'>of</span> <span m='41090'>input</span>\
  \ <span m='41702'>values,</span> <span m='42315'>the</span> <span m='42927'>two</span>\
  \ <span m='43539'>states</span> <span m='44151'>transition</span> <span m='44763'>to</span>\
  \ <span m='45375'>equivalent</span> <span m='45987'>states.</span> </p><p><span\
  \ m='46600'>Our</span> <span m='46881'>strategy</span> <span m='47162'>for</span>\
  \ <span m='47443'>deriving</span> <span m='47725'>an</span> <span m='48006'>equivalent</span>\
  \ <span m='48287'>machine</span> <span m='48568'>with</span> <span m='48850'>fewer</span>\
  \ <span m='49131'>states</span> <span m='49412'>will</span> <span m='49693'>be</span>\
  \ <span m='49975'>to</span> <span m='50256'>start</span> <span m='50537'>with</span>\
  \ <span m='50818'>our</span> <span m='51100'>original</span> <span m='51645'>FSM,</span>\
  \ <span m='52190'>find</span> <span m='52736'>pairs</span> <span m='53281'>of</span>\
  \ <span m='53827'>equivalent</span> <span m='54372'>states</span> <span m='54918'>and</span>\
  \ <span m='55463'>merge</span> <span m='56009'>those</span> <span m='56554'>states.</span>\
  \ </p><p><span m='57100'>We'll</span> <span m='57550'>keep</span> <span m='58000'>repeating</span>\
  \ <span m='58450'>the</span> <span m='58900'>process</span> <span m='59350'>until</span>\
  \ <span m='59800'>we</span> <span m='60250'>can't</span> <span m='60700'>find</span>\
  \ <span m='61150'>any</span> <span m='61600'>more</span> <span m='62050'>equivalent</span>\
  \ <span m='62500'>states.</span> </p><p><span m='62950'>Let's</span> <span m='63334'>try</span>\
  \ <span m='63718'>this</span> <span m='64102'>on</span> <span m='64487'>our</span>\
  \ <span m='64871'>ant</span> <span m='65255'>FSM.</span> </p><p><span m='65640'>First</span>\
  \ <span m='65897'>we</span> <span m='66155'>need</span> <span m='66413'>to</span>\
  \ <span m='66671'>find</span> <span m='66929'>a</span> <span m='67187'>pair</span>\
  \ <span m='67445'>of</span> <span m='67702'>states</span> <span m='67960'>that</span>\
  \ <span m='68218'>have</span> <span m='68476'>the</span> <span m='68734'>same</span>\
  \ <span m='68992'>outputs.</span> </p><p><span m='69250'>As</span> <span m='69535'>it</span>\
  \ <span m='69821'>turns</span> <span m='70107'>out,</span> <span m='70393'>there's</span>\
  \ <span m='70679'>only</span> <span m='70965'>one</span> <span m='71251'>such</span>\
  \ <span m='71537'>pair:</span> <span m='71822'>WALL1</span> <span m='72108'>and</span>\
  \ <span m='72394'>CORNER,</span> <span m='72680'>both</span> <span m='72966'>of</span>\
  \ <span m='73252'>which</span> <span m='73538'>assert</span> <span m='73824'>the</span>\
  \ <span m='74110'>turn-right</span> <span m='74712'>and</span> <span m='75315'>forward</span>\
  \ <span m='75917'>outputs.</span> </p><p><span m='76520'>Okay,</span> <span m='76925'>so</span>\
  \ <span m='77330'>let's</span> <span m='77736'>assume</span> <span m='78141'>that</span>\
  \ <span m='78546'>WALL1</span> <span m='78952'>and</span> <span m='79357'>CORNER</span>\
  \ <span m='79762'>are</span> <span m='80168'>equivalent</span> <span m='80573'>and</span>\
  \ <span m='80978'>ask</span> <span m='81384'>if</span> <span m='81789'>they</span>\
  \ <span m='82194'>transition</span> <span m='82600'>to</span> <span m='83217'>equivalent</span>\
  \ <span m='83834'>states</span> <span m='84451'>for</span> <span m='85068'>each</span>\
  \ <span m='85685'>applicable</span> <span m='86302'>combination</span> <span m='86919'>of</span>\
  \ <span m='87536'>input</span> <span m='88153'>values.</span> </p><p><span m='88770'>For</span>\
  \ <span m='89086'>these</span> <span m='89403'>two</span> <span m='89720'>states,</span>\
  \ <span m='90037'>all</span> <span m='90354'>the</span> <span m='90671'>transitions</span>\
  \ <span m='90988'>depend</span> <span m='91305'>only</span> <span m='91622'>on</span>\
  \ <span m='91939'>the</span> <span m='92256'>value</span> <span m='92573'>of</span>\
  \ <span m='92890'>the</span> <span m='93207'>R</span> <span m='93524'>input,</span>\
  \ <span m='93841'>so</span> <span m='94158'>we</span> <span m='94578'>just</span>\
  \ <span m='94998'>have</span> <span m='95418'>to</span> <span m='95839'>check</span>\
  \ <span m='96259'>two</span> <span m='96679'>cases.</span> </p><p><span m='97100'>If</span>\
  \ <span m='97422'>R</span> <span m='97744'>is</span> <span m='98066'>0,</span> <span\
  \ m='98388'>both</span> <span m='98711'>states</span> <span m='99033'>transition</span>\
  \ <span m='99355'>to</span> <span m='99677'>CORNER.</span> </p><p><span m='100000'>If</span>\
  \ <span m='100547'>R</span> <span m='101095'>is</span> <span m='101643'>1,</span>\
  \ <span m='102191'>both</span> <span m='102738'>states</span> <span m='103286'>transition</span>\
  \ <span m='103834'>to</span> <span m='104382'>WALL2.</span> </p><p><span m='104930'>So</span>\
  \ <span m='105286'>both</span> <span m='105642'>equivalence</span> <span m='105998'>criteria</span>\
  \ <span m='106354'>are</span> <span m='106710'>satisfied</span> <span m='107066'>and</span>\
  \ <span m='107422'>we</span> <span m='107778'>can</span> <span m='108134'>conclude</span>\
  \ <span m='108490'>that</span> <span m='108846'>the</span> <span m='109202'>WALL1</span>\
  \ <span m='109558'>and</span> <span m='109914'>CORNER</span> <span m='110270'>states</span>\
  \ <span m='110775'>are</span> <span m='111281'>equivalent</span> <span m='111787'>and</span>\
  \ <span m='112292'>can</span> <span m='112798'>be</span> <span m='113304'>merged.</span>\
  \ </p><p><span m='113810'>This</span> <span m='114133'>gives</span> <span m='114456'>us</span>\
  \ <span m='114779'>the</span> <span m='115102'>four-state</span> <span m='115426'>FSM</span>\
  \ <span m='115749'>shown</span> <span m='116072'>here,</span> <span m='116395'>where</span>\
  \ <span m='116718'>we've</span> <span m='117042'>called</span> <span m='117365'>the</span>\
  \ <span m='117688'>single</span> <span m='118011'>merged</span> <span m='118334'>state</span>\
  \ <span m='118658'>WALL1.</span> </p><p><span m='120600'>This</span> <span m='121177'>smaller,</span>\
  \ <span m='121754'>equivalent</span> <span m='122331'>FSM</span> <span m='122909'>behaves</span>\
  \ <span m='123486'>exactly</span> <span m='124063'>as</span> <span m='124640'>the</span>\
  \ <span m='125218'>previous</span> <span m='125795'>5-state</span> <span m='126372'>FSM.</span>\
  \ </p><p><span m='126950'>The</span> <span m='127357'>implementation</span> <span\
  \ m='127765'>of</span> <span m='128172'>the</span> <span m='128580'>5-state</span>\
  \ <span m='128987'>machine</span> <span m='129395'>requires</span> <span m='129802'>3</span>\
  \ <span m='130210'>state</span> <span m='130617'>bits;</span> <span m='131025'>the</span>\
  \ <span m='131432'>implementation</span> <span m='131840'>of</span> <span m='132306'>the</span>\
  \ <span m='132773'>4-state</span> <span m='133240'>machine</span> <span m='133706'>only</span>\
  \ <span m='134173'>requires</span> <span m='134640'>2</span> <span m='135106'>state</span>\
  \ <span m='135573'>bits.</span> </p><p><span m='136040'>Reducing</span> <span m='136303'>the</span>\
  \ <span m='136566'>number</span> <span m='136830'>of</span> <span m='137093'>state</span>\
  \ <span m='137356'>bits</span> <span m='137620'>by</span> <span m='137883'>1</span>\
  \ <span m='138146'>is</span> <span m='138410'>huge</span> <span m='138673'>since</span>\
  \ <span m='138936'>it</span> <span m='139200'>reduces</span> <span m='139463'>the</span>\
  \ <span m='139726'>size</span> <span m='139990'>of</span> <span m='140253'>the</span>\
  \ <span m='140516'>required</span> <span m='140780'>ROM</span> <span m='141746'>by</span>\
  \ <span m='142713'>half!</span> </p><p><span m='143680'>Just</span> <span m='144072'>as</span>\
  \ <span m='144465'>we</span> <span m='144858'>were</span> <span m='145251'>able</span>\
  \ <span m='145644'>to</span> <span m='146037'>achieve</span> <span m='146430'>considerable</span>\
  \ <span m='146822'>hardware</span> <span m='147215'>savings</span> <span m='147608'>by</span>\
  \ <span m='148001'>minimizing</span> <span m='148394'>Boolean</span> <span m='148787'>equations,</span>\
  \ <span m='149180'>we</span> <span m='149630'>can</span> <span m='150081'>do</span>\
  \ <span m='150532'>the</span> <span m='150983'>same</span> <span m='151434'>in</span>\
  \ <span m='151885'>sequential</span> <span m='152335'>logic</span> <span m='152786'>by</span>\
  \ <span m='153237'>merging</span> <span m='153688'>equivalent</span> <span m='154139'>states.</span>\
  \ </p><p><span m='154590'>Roboant</span> <span m='155053'>customers</span> <span\
  \ m='155516'>are</span> <span m='155980'>looking</span> <span m='156443'>forward</span>\
  \ <span m='156906'>to</span> <span m='157370'>the</span> <span m='157833'>price</span>\
  \ <span m='158296'>cut!</span> </p><p><span m='158760'>Let's</span> <span m='159025'>look</span>\
  \ <span m='159291'>at</span> <span m='159557'>what</span> <span m='159823'>we'd</span>\
  \ <span m='160088'>need</span> <span m='160354'>to</span> <span m='160620'>do</span>\
  \ <span m='160886'>if</span> <span m='161152'>we</span> <span m='161417'>wanted</span>\
  \ <span m='161683'>to</span> <span m='161949'>implement</span> <span m='162215'>the</span>\
  \ <span m='162481'>FSM</span> <span m='162746'>using</span> <span m='163012'>logic</span>\
  \ <span m='163278'>gates</span> <span m='163544'>instead</span> <span m='163810'>a</span>\
  \ <span m='164423'>ROM</span> <span m='165036'>for</span> <span m='165650'>the</span>\
  \ <span m='166263'>combinational</span> <span m='166876'>logic.</span> </p><p><span\
  \ m='167490'>First</span> <span m='167793'>we</span> <span m='168097'>have</span>\
  \ <span m='168401'>to</span> <span m='168704'>build</span> <span m='169008'>the</span>\
  \ <span m='169312'>truth</span> <span m='169615'>table,</span> <span m='169919'>entering</span>\
  \ <span m='170223'>all</span> <span m='170526'>the</span> <span m='170830'>transitions</span>\
  \ <span m='171134'>in</span> <span m='171437'>the</span> <span m='171741'>state</span>\
  \ <span m='172045'>transition</span> <span m='172349'>diagram.</span> </p><p><span\
  \ m='173629'>We'll</span> <span m='173900'>start</span> <span m='174172'>with</span>\
  \ <span m='174444'>the</span> <span m='174716'>LOST</span> <span m='174988'>state.</span>\
  \ </p><p><span m='175260'>So</span> <span m='175592'>if</span> <span m='175924'>the</span>\
  \ <span m='176256'>FSM</span> <span m='176588'>is</span> <span m='176920'>in</span>\
  \ <span m='177252'>this</span> <span m='177585'>state,</span> <span m='177917'>the</span>\
  \ <span m='178249'>F</span> <span m='178581'>output</span> <span m='178913'>should</span>\
  \ <span m='179245'>be</span> <span m='179577'>1.</span> </p><p><span m='179910'>If</span>\
  \ <span m='180369'>both</span> <span m='180828'>antenna</span> <span m='181287'>inputs</span>\
  \ <span m='181746'>are</span> <span m='182205'>0,</span> <span m='182665'>the</span>\
  \ <span m='183124'>next</span> <span m='183583'>state</span> <span m='184042'>is</span>\
  \ <span m='184501'>also</span> <span m='184960'>LOST.</span> </p><p><span m='185420'>Assigning</span>\
  \ <span m='185743'>the</span> <span m='186067'>LOST</span> <span m='186390'>state</span>\
  \ <span m='186714'>the</span> <span m='187037'>encoding</span> <span m='187361'>00,</span>\
  \ <span m='187685'>we've</span> <span m='188008'>captured</span> <span m='188332'>this</span>\
  \ <span m='188655'>information</span> <span m='188979'>in</span> <span m='189302'>the</span>\
  \ <span m='189626'>first</span> <span m='189950'>row</span> <span m='190627'>of</span>\
  \ <span m='191305'>the</span> <span m='191982'>table.</span> </p><p><span m='192660'>If</span>\
  \ <span m='193117'>either</span> <span m='193575'>antenna</span> <span m='194033'>is</span>\
  \ <span m='194491'>touching,</span> <span m='194948'>the</span> <span m='195406'>FSM</span>\
  \ <span m='195864'>should</span> <span m='196322'>transition</span> <span m='196780'>from</span>\
  \ <span m='197237'>LOST</span> <span m='197695'>to</span> <span m='198153'>the</span>\
  \ <span m='198611'>rotate-counterclockwise</span> <span m='199069'>state.</span>\
  \ </p><p><span m='200069'>We've</span> <span m='200714'>given</span> <span m='201360'>this</span>\
  \ <span m='202006'>an</span> <span m='202652'>encoding</span> <span m='203298'>of</span>\
  \ <span m='203944'>01.</span> </p><p><span m='204590'>There</span> <span m='204915'>are</span>\
  \ <span m='205240'>three</span> <span m='205565'>combinations</span> <span m='205890'>of</span>\
  \ <span m='206215'>L</span> <span m='206540'>and</span> <span m='206865'>R</span>\
  \ <span m='207190'>values</span> <span m='207515'>that</span> <span m='207840'>match</span>\
  \ <span m='208165'>this</span> <span m='208490'>transition,</span> <span m='208815'>so</span>\
  \ <span m='209140'>we've</span> <span m='209465'>added</span> <span m='209790'>three</span>\
  \ <span m='210213'>rows</span> <span m='210636'>to</span> <span m='211059'>the</span>\
  \ <span m='211482'>truth</span> <span m='211905'>table.</span> </p><p><span m='212329'>This</span>\
  \ <span m='212722'>takes</span> <span m='213116'>care</span> <span m='213509'>of</span>\
  \ <span m='213903'>all</span> <span m='214297'>the</span> <span m='214690'>transitions</span>\
  \ <span m='215084'>from</span> <span m='215478'>the</span> <span m='215871'>LOST</span>\
  \ <span m='216265'>state.</span> </p><p><span m='216659'>Now</span> <span m='217146'>we</span>\
  \ <span m='217633'>can</span> <span m='218120'>tackle</span> <span m='218607'>the</span>\
  \ <span m='219094'>transitions</span> <span m='219581'>from</span> <span m='220068'>the</span>\
  \ <span m='220555'>rotate-counterclockwise</span> <span m='221042'>state.</span>\
  \ </p><p><span m='221530'>If</span> <span m='221984'>either</span> <span m='222439'>antenna</span>\
  \ <span m='222893'>is</span> <span m='223348'>touching,</span> <span m='223802'>the</span>\
  \ <span m='224257'>next</span> <span m='224711'>state</span> <span m='225166'>is</span>\
  \ <span m='225620'>again</span> <span m='226075'>rotate-counterclockwise.</span>\
  \ </p><p><span m='226530'>So</span> <span m='226836'>we've</span> <span m='227142'>identified</span>\
  \ <span m='227449'>the</span> <span m='227755'>matching</span> <span m='228061'>values</span>\
  \ <span m='228368'>for</span> <span m='228674'>the</span> <span m='228980'>inputs</span>\
  \ <span m='229287'>and</span> <span m='229593'>added</span> <span m='229899'>the</span>\
  \ <span m='230206'>appropriate</span> <span m='230512'>three</span> <span m='230819'>rows</span>\
  \ <span m='231367'>to</span> <span m='231915'>the</span> <span m='232463'>transition</span>\
  \ <span m='233011'>table.</span> </p><p><span m='233560'>We</span> <span m='234095'>can</span>\
  \ <span m='234630'>continue</span> <span m='235165'>in</span> <span m='235700'>a</span>\
  \ <span m='236235'>similar</span> <span m='236770'>manner</span> <span m='237305'>to</span>\
  \ <span m='237840'>encode</span> <span m='238375'>the</span> <span m='238910'>transitions</span>\
  \ <span m='239445'>one-by-one.</span> </p><p><span m='239980'>Here's</span> <span\
  \ m='240357'>the</span> <span m='240735'>final</span> <span m='241112'>table,</span>\
  \ <span m='241490'>where</span> <span m='241868'>we've</span> <span m='242245'>used</span>\
  \ <span m='242623'>don't</span> <span m='243001'>cares</span> <span m='243378'>to</span>\
  \ <span m='243756'>reduce</span> <span m='244134'>the</span> <span m='244511'>number</span>\
  \ <span m='244889'>of</span> <span m='245267'>rows</span> <span m='245644'>for</span>\
  \ <span m='246022'>presentation.</span> </p><p><span m='246400'>Next</span> <span\
  \ m='246642'>we</span> <span m='246885'>want</span> <span m='247128'>to</span> <span\
  \ m='247371'>come</span> <span m='247614'>up</span> <span m='247857'>with</span>\
  \ <span m='248100'>Boolean</span> <span m='248343'>equations</span> <span m='248586'>for</span>\
  \ <span m='248829'>each</span> <span m='249072'>of</span> <span m='249315'>the</span>\
  \ <span m='249558'>outputs</span> <span m='249801'>of</span> <span m='250044'>the</span>\
  \ <span m='250287'>combinational</span> <span m='250530'>logic,</span> <span m='251055'>i.e.,</span>\
  \ <span m='251580'>the</span> <span m='252106'>two</span> <span m='252631'>next-state</span>\
  \ <span m='253157'>bits</span> <span m='253682'>and</span> <span m='254208'>the</span>\
  \ <span m='254733'>three</span> <span m='255259'>motion-control</span> <span m='255784'>outputs.</span>\
  \ </p><p><span m='256310'>Here</span> <span m='256851'>are</span> <span m='257393'>the</span>\
  \ <span m='257935'>Karnaugh</span> <span m='258477'>maps</span> <span m='259019'>for</span>\
  \ <span m='259560'>the</span> <span m='260102'>two</span> <span m='260644'>next-state</span>\
  \ <span m='261186'>bits.</span> </p><p><span m='261728'>Using</span> <span m='262121'>our</span>\
  \ <span m='262514'>K-map</span> <span m='262907'>skills</span> <span m='263300'>from</span>\
  \ <span m='263693'>Chapter</span> <span m='264086'>4,</span> <span m='264479'>we'll</span>\
  \ <span m='264872'>find</span> <span m='265265'>a</span> <span m='265658'>cover</span>\
  \ <span m='266051'>of</span> <span m='266444'>the</span> <span m='266837'>prime</span>\
  \ <span m='267230'>implicants</span> <span m='267623'>for</span> <span m='268016'>S1-prime</span>\
  \ <span m='268409'>and</span> <span m='268874'>write</span> <span m='269339'>down</span>\
  \ <span m='269804'>the</span> <span m='270269'>corresponding</span> <span m='270734'>product</span>\
  \ <span m='271199'>terms</span> <span m='271664'>in</span> <span m='272129'>a</span>\
  \ <span m='272594'>minimal</span> <span m='273059'>sum-of-products</span> <span\
  \ m='273524'>equation.</span> </p><p><span m='273990'>And</span> <span m='274340'>then</span>\
  \ <span m='274690'>do</span> <span m='275040'>the</span> <span m='275390'>same</span>\
  \ <span m='275740'>for</span> <span m='276090'>the</span> <span m='276440'>other</span>\
  \ <span m='276790'>next-state</span> <span m='277140'>bit.</span> </p><p><span m='277490'>We</span>\
  \ <span m='277829'>can</span> <span m='278169'>follow</span> <span m='278509'>a</span>\
  \ <span m='278849'>similar</span> <span m='279189'>process</span> <span m='279529'>to</span>\
  \ <span m='279869'>derive</span> <span m='280209'>minimal</span> <span m='280549'>sum-of-products</span>\
  \ <span m='280889'>expressions</span> <span m='281229'>for</span> <span m='281569'>the</span>\
  \ <span m='281909'>motion-control</span> <span m='283279'>outputs.</span> </p><p><span\
  \ m='284650'>Implementing</span> <span m='284987'>each</span> <span m='285324'>sum-of-products</span>\
  \ <span m='285662'>in</span> <span m='285999'>a</span> <span m='286336'>straight-forward</span>\
  \ <span m='286674'>fashion</span> <span m='287011'>with</span> <span m='287348'>AND</span>\
  \ <span m='287686'>and</span> <span m='288023'>OR</span> <span m='288360'>gates,</span>\
  \ <span m='288698'>we</span> <span m='289035'>get</span> <span m='289372'>the</span>\
  \ <span m='289710'>following</span> <span m='290170'>schematic</span> <span m='290630'>for</span>\
  \ <span m='291090'>the</span> <span m='291550'>ant</span> <span m='292010'>brain.</span>\
  \ </p><p><span m='292470'>Pretty</span> <span m='293075'>neat!</span> </p><p><span\
  \ m='293680'>Who</span> <span m='294031'>knew</span> <span m='294382'>that</span>\
  \ <span m='294733'>maze</span> <span m='295085'>following</span> <span m='295436'>behavior</span>\
  \ <span m='295787'>could</span> <span m='296138'>be</span> <span m='296490'>implemented</span>\
  \ <span m='296841'>with</span> <span m='297192'>a</span> <span m='297543'>couple</span>\
  \ <span m='297895'>of</span> <span m='298246'>D</span> <span m='298597'>registers</span>\
  \ <span m='298949'>and</span> <span m='299609'>a</span> <span m='300269'>handful</span>\
  \ <span m='300929'>of</span> <span m='301589'>logic</span> <span m='302249'>gates?</span>\
  \ </p><p><span m='302910'>There</span> <span m='303303'>are</span> <span m='303697'>many</span>\
  \ <span m='304091'>complex</span> <span m='304485'>behaviors</span> <span m='304879'>that</span>\
  \ <span m='305273'>can</span> <span m='305666'>be</span> <span m='306060'>created</span>\
  \ <span m='306454'>with</span> <span m='306848'>surprisingly</span> <span m='307242'>simple</span>\
  \ <span m='307636'>FSMs.</span> </p><p><span m='308030'>Early</span> <span m='308497'>on,</span>\
  \ <span m='308965'>the</span> <span m='309433'>computer</span> <span m='309900'>graphics</span>\
  \ <span m='310368'>folks</span> <span m='310836'>learned</span> <span m='311303'>that</span>\
  \ <span m='311771'>group</span> <span m='312239'>behaviors</span> <span m='312706'>like</span>\
  \ <span m='313174'>swarming,</span> <span m='313642'>flocking</span> <span m='314110'>and</span>\
  \ <span m='314478'>schooling</span> <span m='314846'>can</span> <span m='315215'>be</span>\
  \ <span m='315583'>modeled</span> <span m='315951'>by</span> <span m='316320'>equipping</span>\
  \ <span m='316688'>each</span> <span m='317057'>participant</span> <span m='317425'>with</span>\
  \ <span m='317793'>a</span> <span m='318162'>simple</span> <span m='318530'>FSM.</span>\
  \ </p><p><span m='318899'>So</span> <span m='319186'>next</span> <span m='319473'>time</span>\
  \ <span m='319760'>you</span> <span m='320048'>see</span> <span m='320335'>the</span>\
  \ <span m='320622'>massive</span> <span m='320909'>battle</span> <span m='321197'>scene</span>\
  \ <span m='321484'>from</span> <span m='321771'>the</span> <span m='322059'>Lord</span>\
  \ <span m='322346'>of</span> <span m='322633'>the</span> <span m='322920'>Rings</span>\
  \ <span m='323208'>movie,</span> <span m='323495'>think</span> <span m='323782'>of</span>\
  \ <span m='324070'>many</span> <span m='324798'>FSMs</span> <span m='325526'>running</span>\
  \ <span m='326254'>in</span> <span m='326982'>parallel!</span> </p><p><span m='327710'>Physical</span>\
  \ <span m='328142'>behaviors</span> <span m='328575'>that</span> <span m='329007'>arise</span>\
  \ <span m='329440'>from</span> <span m='329873'>simple</span> <span m='330305'>interactions</span>\
  \ <span m='330738'>between</span> <span m='331171'>component</span> <span m='331603'>molecules</span>\
  \ <span m='332036'>can</span> <span m='332469'>sometimes</span> <span m='332964'>be</span>\
  \ <span m='333460'>more</span> <span m='333956'>easily</span> <span m='334451'>modeled</span>\
  \ <span m='334947'>using</span> <span m='335443'>cellular</span> <span m='335938'>automata</span>\
  \ <span m='336434'>-</span> <span m='336930'>arrays</span> <span m='337329'>of</span>\
  \ <span m='337728'>communicating</span> <span m='338127'>FSMS</span> <span m='338527'>-</span>\
  \ <span m='338926'>than</span> <span m='339325'>by</span> <span m='339725'>trying</span>\
  \ <span m='340124'>to</span> <span m='340523'>solve</span> <span m='340922'>the</span>\
  \ <span m='341322'>partial</span> <span m='341721'>differential</span> <span m='342120'>equations</span>\
  \ <span m='342520'>that</span> <span m='343043'>model</span> <span m='343567'>the</span>\
  \ <span m='344091'>constraints</span> <span m='344615'>on</span> <span m='345138'>the</span>\
  \ <span m='345662'>molecules'</span> <span m='346186'>behavior.</span> </p><p><span\
  \ m='346710'>And</span> <span m='347096'>here's</span> <span m='347483'>an</span>\
  \ <span m='347870'>idea:</span> <span m='348257'>what</span> <span m='348644'>if</span>\
  \ <span m='349031'>we</span> <span m='349418'>allowed</span> <span m='349805'>the</span>\
  \ <span m='350191'>FSM</span> <span m='350578'>to</span> <span m='350965'>modify</span>\
  \ <span m='351352'>its</span> <span m='351739'>own</span> <span m='352126'>transition</span>\
  \ <span m='352513'>table?</span> </p><p><span m='352900'>Hmm.</span> </p><p><span\
  \ m='354279'>Maybe</span> <span m='354766'>that's</span> <span m='355253'>a</span>\
  \ <span m='355740'>plausible</span> <span m='356227'>model</span> <span m='356714'>for</span>\
  \ <span m='357201'>evolution!</span> </p><p><span m='357689'>FSMs</span> <span m='358442'>are</span>\
  \ <span m='359195'>everywhere!</span> </p><p><span m='359949'>You'll</span> <span\
  \ m='360221'>see</span> <span m='360493'>FSMs</span> <span m='360766'>for</span>\
  \ <span m='361038'>the</span> <span m='361310'>rest</span> <span m='361583'>of</span>\
  \ <span m='361855'>your</span> <span m='362127'>life\u2026</span> </p>"
type: course
uid: 4f2b76f260986193c8a02221bbcbcddf

---
None