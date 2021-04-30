---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 781P9Ixmi0g
  parent_uid: 421ee09a248a669cfe5f1d9d654ecc7f
  title: Video-YouTube-Stream
  type: Video
  uid: 332bb786a00f6426dcd460d700bee4d6
- id: 3Play-3Play YouTube id-Stream
  media_location: 781P9Ixmi0g
  parent_uid: 421ee09a248a669cfe5f1d9d654ecc7f
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: c243d5f0c309a25296a46bd6829ead0b
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/781P9Ixmi0g/default.jpg
  parent_uid: 421ee09a248a669cfe5f1d9d654ecc7f
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 5910981f86184d649040937c92d58142
- id: 781P9Ixmi0g.srt
  parent_uid: 421ee09a248a669cfe5f1d9d654ecc7f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v2/programmable-datapaths-4-50-/781P9Ixmi0g.srt
  title: 3play caption file
  type: null
  uid: 0c9a7235e6dee2aa4a974dff57eb3375
- id: 781P9Ixmi0g.pdf
  parent_uid: 421ee09a248a669cfe5f1d9d654ecc7f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v2/programmable-datapaths-4-50-/781P9Ixmi0g.pdf
  title: 3play pdf file
  type: null
  uid: 388014e02cb015cb5542414525b94496
- id: Caption-3Play YouTube id-SRT
  parent_uid: 421ee09a248a669cfe5f1d9d654ecc7f
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 58addc5ec104c33967b63c0d90c235a3
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 421ee09a248a669cfe5f1d9d654ecc7f
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: a68af12783f9a6a60df49efa53963518
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_09-02-02_300k.mp4
  parent_uid: 421ee09a248a669cfe5f1d9d654ecc7f
  title: Video-Internet Archive-MP4
  type: Video
  uid: 8a9274840aa798310a473f037c6512b0
inline_embed_id: 69368745programmabledatapaths45037379057
layout: video
order_index: null
parent_uid: 1bd0c4a0df0c70e72352632832addb5f
related_resources_text: ''
short_url: programmable-datapaths-4-50-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v2/programmable-datapaths-4-50-
template_type: Embed
title: Programmable Datapaths (4:50)
transcript: "<p><span m='750'>Okay,</span> <span m='1142'>we've</span> <span m='1535'>figured</span>\
  \ <span m='1928'>out</span> <span m='2321'>a</span> <span m='2714'>way</span> <span\
  \ m='3107'>to</span> <span m='3500'>design</span> <span m='3892'>hardware</span>\
  \ <span m='4285'>to</span> <span m='4678'>perform</span> <span m='5071'>a</span>\
  \ <span m='5464'>particular</span> <span m='5857'>computation:</span> <span m='6250'>Draw</span>\
  \ <span m='6579'>the</span> <span m='6908'>state</span> <span m='7237'>transition</span>\
  \ <span m='7567'>diagram</span> <span m='7896'>for</span> <span m='8225'>an</span>\
  \ <span m='8555'>FSM</span> <span m='8884'>that</span> <span m='9213'>describes</span>\
  \ <span m='9542'>the</span> <span m='9872'>sequence</span> <span m='10201'>of</span>\
  \ <span m='10530'>operations</span> <span m='10860'>needed</span> <span m='11370'>to</span>\
  \ <span m='11880'>complete</span> <span m='12390'>the</span> <span m='12900'>computation.</span>\
  \ </p><p><span m='13410'>Then</span> <span m='13855'>construct</span> <span m='14301'>the</span>\
  \ <span m='14747'>appropriate</span> <span m='15193'>datapath,</span> <span m='15639'>using</span>\
  \ <span m='16085'>registers</span> <span m='16530'>to</span> <span m='16976'>store</span>\
  \ <span m='17422'>values</span> <span m='17868'>and</span> <span m='18314'>combinational</span>\
  \ <span m='18760'>logic</span> <span m='19293'>to</span> <span m='19826'>implement</span>\
  \ <span m='20360'>the</span> <span m='20893'>needed</span> <span m='21426'>operations.</span>\
  \ </p><p><span m='21960'>Finally</span> <span m='22396'>build</span> <span m='22832'>an</span>\
  \ <span m='23268'>FSM</span> <span m='23704'>to</span> <span m='24140'>generate</span>\
  \ <span m='24576'>the</span> <span m='25013'>control</span> <span m='25449'>signals</span>\
  \ <span m='25885'>required</span> <span m='26321'>by</span> <span m='26757'>the</span>\
  \ <span m='27193'>datapath.</span> </p><p><span m='27630'>Is</span> <span m='27993'>the</span>\
  \ <span m='28356'>datapath</span> <span m='28720'>plus</span> <span m='29083'>control</span>\
  \ <span m='29446'>logic</span> <span m='29810'>itself</span> <span m='30173'>an</span>\
  \ <span m='30536'>FSM?</span> </p><p><span m='30900'>Well,</span> <span m='31323'>it</span>\
  \ <span m='31747'>has</span> <span m='32170'>registers</span> <span m='32594'>and</span>\
  \ <span m='33017'>some</span> <span m='33441'>combinational</span> <span m='33864'>logic,</span>\
  \ <span m='34288'>so,</span> <span m='34711'>yes,</span> <span m='35135'>it</span>\
  \ <span m='35558'>is</span> <span m='35982'>an</span> <span m='36405'>FSM.</span>\
  \ </p><p><span m='36829'>Can</span> <span m='37199'>we</span> <span m='37569'>draw</span>\
  \ <span m='37939'>the</span> <span m='38309'>truth</span> <span m='38679'>table?</span>\
  \ </p><p><span m='39050'>In</span> <span m='39406'>theory,</span> <span m='39763'>yes.</span>\
  \ </p><p><span m='40120'>In</span> <span m='40484'>practice,</span> <span m='40848'>there</span>\
  \ <span m='41213'>are</span> <span m='41577'>66</span> <span m='41942'>bits</span>\
  \ <span m='42306'>of</span> <span m='42671'>registers</span> <span m='43035'>and</span>\
  \ <span m='43400'>hence</span> <span m='43764'>66</span> <span m='44128'>bits</span>\
  \ <span m='44493'>of</span> <span m='44857'>state,</span> <span m='45222'>so</span>\
  \ <span m='45586'>our</span> <span m='45951'>truth</span> <span m='46315'>table</span>\
  \ <span m='46680'>would</span> <span m='47375'>need</span> <span m='48070'>2^66</span>\
  \ <span m='48765'>rows!</span> </p><p><span m='49460'>Hmm,</span> <span m='49799'>not</span>\
  \ <span m='50138'>very</span> <span m='50477'>likely</span> <span m='50816'>that</span>\
  \ <span m='51156'>we'd</span> <span m='51495'>be</span> <span m='51834'>able</span>\
  \ <span m='52173'>to</span> <span m='52513'>draw</span> <span m='52852'>the</span>\
  \ <span m='53191'>truth</span> <span m='53530'>table!</span> </p><p><span m='53870'>The</span>\
  \ <span m='54109'>difficulty</span> <span m='54348'>comes</span> <span m='54587'>from</span>\
  \ <span m='54827'>thinking</span> <span m='55066'>of</span> <span m='55305'>the</span>\
  \ <span m='55545'>registers</span> <span m='55784'>in</span> <span m='56023'>the</span>\
  \ <span m='56263'>datapath</span> <span m='56502'>as</span> <span m='56741'>part</span>\
  \ <span m='56981'>of</span> <span m='57220'>the</span> <span m='57459'>state</span>\
  \ <span m='57699'>of</span> <span m='58335'>our</span> <span m='58972'>super-FSM.</span>\
  \ </p><p><span m='59609'>That's</span> <span m='59977'>why</span> <span m='60346'>we</span>\
  \ <span m='60714'>think</span> <span m='61083'>about</span> <span m='61451'>the</span>\
  \ <span m='61820'>datapath</span> <span m='62189'>as</span> <span m='62557'>being</span>\
  \ <span m='62926'>separate</span> <span m='63294'>from</span> <span m='63663'>the</span>\
  \ <span m='64031'>control</span> <span m='64400'>FSM.</span> </p><p><span m='64769'>So</span>\
  \ <span m='65069'>how</span> <span m='65370'>do</span> <span m='65670'>we</span>\
  \ <span m='65971'>generalize</span> <span m='66272'>this</span> <span m='66572'>approach</span>\
  \ <span m='66873'>so</span> <span m='67174'>we</span> <span m='67474'>can</span>\
  \ <span m='67775'>use</span> <span m='68076'>one</span> <span m='68376'>computer</span>\
  \ <span m='68677'>circuit</span> <span m='68978'>to</span> <span m='69278'>solve</span>\
  \ <span m='69579'>many</span> <span m='69880'>different</span> <span m='70675'>problems.</span>\
  \ </p><p><span m='71470'>Well,</span> <span m='72008'>most</span> <span m='72546'>problems</span>\
  \ <span m='73085'>would</span> <span m='73623'>probably</span> <span m='74161'>require</span>\
  \ <span m='74700'>more</span> <span m='75238'>storage</span> <span m='75776'>for</span>\
  \ <span m='76315'>operands</span> <span m='76853'>and</span> <span m='77391'>results.</span>\
  \ </p><p><span m='77930'>And</span> <span m='78318'>a</span> <span m='78706'>larger</span>\
  \ <span m='79094'>list</span> <span m='79482'>of</span> <span m='79870'>allowable</span>\
  \ <span m='80258'>operations</span> <span m='80646'>would</span> <span m='81034'>be</span>\
  \ <span m='81422'>handy.</span> </p><p><span m='81810'>This</span> <span m='82076'>is</span>\
  \ <span m='82342'>actually</span> <span m='82608'>a</span> <span m='82875'>bit</span>\
  \ <span m='83141'>tricky:</span> <span m='83407'>what's</span> <span m='83673'>the</span>\
  \ <span m='83940'>minimum</span> <span m='84206'>set</span> <span m='84472'>of</span>\
  \ <span m='84738'>operations</span> <span m='85005'>we</span> <span m='85271'>can</span>\
  \ <span m='85537'>get</span> <span m='85803'>away</span> <span m='86070'>with?</span>\
  \ </p><p><span m='87070'>As</span> <span m='87463'>we'll</span> <span m='87857'>see</span>\
  \ <span m='88250'>later,</span> <span m='88644'>surprisingly</span> <span m='89037'>simple</span>\
  \ <span m='89431'>hardware</span> <span m='89824'>is</span> <span m='90218'>sufficient</span>\
  \ <span m='90611'>to</span> <span m='91005'>perform</span> <span m='91398'>any</span>\
  \ <span m='91792'>realizable</span> <span m='92185'>computation.</span> </p><p><span\
  \ m='92579'>At</span> <span m='93064'>the</span> <span m='93549'>other</span> <span\
  \ m='94034'>extreme,</span> <span m='94519'>many</span> <span m='95004'>complex</span>\
  \ <span m='95489'>operations</span> <span m='95974'>(e.g.,</span> <span m='96459'>fast</span>\
  \ <span m='96944'>fourier</span> <span m='97429'>transform)</span> <span m='97914'>are</span>\
  \ <span m='98399'>best</span> <span m='98884'>implemented</span> <span m='99370'>as</span>\
  \ <span m='99760'>sequences</span> <span m='100151'>of</span> <span m='100542'>simpler</span>\
  \ <span m='100932'>operations</span> <span m='101323'>(e.g.,</span> <span m='101714'>add</span>\
  \ <span m='102105'>and</span> <span m='102495'>multiply)</span> <span m='102886'>rather</span>\
  \ <span m='103277'>than</span> <span m='103667'>as</span> <span m='104058'>a</span>\
  \ <span m='104449'>single</span> <span m='104840'>massive</span> <span m='105733'>combinational</span>\
  \ <span m='106626'>circuit.</span> </p><p><span m='107520'>These</span> <span m='107964'>sorts</span>\
  \ <span m='108408'>of</span> <span m='108853'>design</span> <span m='109297'>tradeoffs</span>\
  \ <span m='109741'>are</span> <span m='110186'>what</span> <span m='110630'>makes</span>\
  \ <span m='111074'>computer</span> <span m='111519'>architecture</span> <span m='111963'>fun!</span>\
  \ </p><p><span m='112408'>We'd</span> <span m='112686'>then</span> <span m='112964'>combine</span>\
  \ <span m='113242'>our</span> <span m='113520'>larger</span> <span m='113798'>storage</span>\
  \ <span m='114076'>with</span> <span m='114354'>logic</span> <span m='114632'>for</span>\
  \ <span m='114910'>our</span> <span m='115188'>chosen</span> <span m='115466'>set</span>\
  \ <span m='115744'>of</span> <span m='116022'>operations</span> <span m='116300'>into</span>\
  \ <span m='116579'>a</span> <span m='117042'>general</span> <span m='117506'>purpose</span>\
  \ <span m='117970'>datapath</span> <span m='118434'>that</span> <span m='118898'>could</span>\
  \ <span m='119362'>be</span> <span m='119826'>reused</span> <span m='120290'>to</span>\
  \ <span m='120754'>solve</span> <span m='121218'>many</span> <span m='121682'>different</span>\
  \ <span m='122146'>problems.</span> </p><p><span m='122610'>Let's</span> <span m='123034'>see</span>\
  \ <span m='123459'>how</span> <span m='123884'>that</span> <span m='124309'>would</span>\
  \ <span m='124734'>work\u2026</span> <span m='125159'>Here's</span> <span m='125530'>a</span>\
  \ <span m='125901'>datapath</span> <span m='126272'>with</span> <span m='126643'>4</span>\
  \ <span m='127014'>data</span> <span m='127385'>registers</span> <span m='127756'>to</span>\
  \ <span m='128127'>hold</span> <span m='128498'>results.</span> </p><p><span m='128869'>The</span>\
  \ <span m='129262'>ASEL</span> <span m='129656'>and</span> <span m='130050'>BSEL</span>\
  \ <span m='130444'>multiplexers</span> <span m='130838'>allow</span> <span m='131231'>any</span>\
  \ <span m='131625'>of</span> <span m='132019'>the</span> <span m='132413'>data</span>\
  \ <span m='132807'>registers</span> <span m='133200'>to</span> <span m='133594'>be</span>\
  \ <span m='133988'>selected</span> <span m='134382'>as</span> <span m='134776'>either</span>\
  \ <span m='135170'>operand</span> <span m='135697'>for</span> <span m='136225'>our</span>\
  \ <span m='136753'>repertoire</span> <span m='137281'>of</span> <span m='137808'>arithmetic</span>\
  \ <span m='138336'>and</span> <span m='138864'>boolean</span> <span m='139392'>operations.</span>\
  \ </p><p><span m='139920'>The</span> <span m='140148'>result</span> <span m='140376'>is</span>\
  \ <span m='140605'>selected</span> <span m='140833'>by</span> <span m='141062'>the</span>\
  \ <span m='141290'>OPSEL</span> <span m='141518'>MUX</span> <span m='141747'>and</span>\
  \ <span m='141975'>can</span> <span m='142204'>be</span> <span m='142432'>written</span>\
  \ <span m='142661'>back</span> <span m='142889'>into</span> <span m='143117'>any</span>\
  \ <span m='143346'>of</span> <span m='143574'>the</span> <span m='143803'>data</span>\
  \ <span m='144031'>registers</span> <span m='144260'>by</span> <span m='144583'>setting</span>\
  \ <span m='144907'>the</span> <span m='145230'>WEN</span> <span m='145554'>control</span>\
  \ <span m='145877'>signal</span> <span m='146201'>to</span> <span m='146524'>1</span>\
  \ <span m='146848'>and</span> <span m='147171'>using</span> <span m='147495'>the</span>\
  \ <span m='147818'>2-bit</span> <span m='148142'>WSEL</span> <span m='148465'>signal</span>\
  \ <span m='148789'>to</span> <span m='149112'>select</span> <span m='149436'>which</span>\
  \ <span m='149760'>data</span> <span m='150149'>register</span> <span m='150538'>will</span>\
  \ <span m='150927'>be</span> <span m='151316'>loaded</span> <span m='151705'>at</span>\
  \ <span m='152094'>the</span> <span m='152483'>next</span> <span m='152872'>rising</span>\
  \ <span m='153261'>clock</span> <span m='153650'>edge.</span> </p><p><span m='154040'>Note</span>\
  \ <span m='154417'>that</span> <span m='154794'>the</span> <span m='155171'>data</span>\
  \ <span m='155548'>registers</span> <span m='155925'>have</span> <span m='156302'>a</span>\
  \ <span m='156679'>load-enable</span> <span m='157056'>control</span> <span m='157433'>input.</span>\
  \ </p><p><span m='157810'>When</span> <span m='158076'>this</span> <span m='158343'>signal</span>\
  \ <span m='158610'>is</span> <span m='158876'>1,</span> <span m='159143'>the</span>\
  \ <span m='159410'>register</span> <span m='159676'>will</span> <span m='159943'>load</span>\
  \ <span m='160210'>a</span> <span m='160476'>new</span> <span m='160743'>value</span>\
  \ <span m='161010'>from</span> <span m='161276'>its</span> <span m='161543'>D</span>\
  \ <span m='161810'>input,</span> <span m='162076'>otherwise</span> <span m='162343'>it</span>\
  \ <span m='162610'>ignores</span> <span m='162977'>the</span> <span m='163344'>D</span>\
  \ <span m='163711'>input</span> <span m='164078'>and</span> <span m='164445'>simply</span>\
  \ <span m='164812'>reloads</span> <span m='165179'>its</span> <span m='165546'>previous</span>\
  \ <span m='165913'>value.</span> </p><p><span m='166280'>And,</span> <span m='166672'>of</span>\
  \ <span m='167065'>course,</span> <span m='167458'>we'll</span> <span m='167850'>add</span>\
  \ <span m='168243'>a</span> <span m='168636'>control</span> <span m='169028'>FSM</span>\
  \ <span m='169421'>to</span> <span m='169814'>generate</span> <span m='170206'>the</span>\
  \ <span m='170599'>appropriate</span> <span m='170992'>sequence</span> <span m='171384'>of</span>\
  \ <span m='171777'>control</span> <span m='172170'>signals</span> <span m='172657'>for</span>\
  \ <span m='173145'>the</span> <span m='173632'>datapath.</span> </p><p><span m='174120'>The</span>\
  \ <span m='174470'>Z</span> <span m='174821'>input</span> <span m='175172'>from</span>\
  \ <span m='175522'>the</span> <span m='175873'>datapath</span> <span m='176224'>allows</span>\
  \ <span m='176575'>the</span> <span m='176925'>system</span> <span m='177276'>to</span>\
  \ <span m='177627'>perform</span> <span m='177977'>data-dependent</span> <span m='178328'>operations,</span>\
  \ <span m='178679'>where</span> <span m='179030'>the</span> <span m='179460'>sequence</span>\
  \ <span m='179891'>of</span> <span m='180321'>operations</span> <span m='180752'>can</span>\
  \ <span m='181183'>be</span> <span m='181613'>influenced</span> <span m='182044'>by</span>\
  \ <span m='182474'>the</span> <span m='182905'>actual</span> <span m='183336'>values</span>\
  \ <span m='183766'>in</span> <span m='184197'>the</span> <span m='184627'>data</span>\
  \ <span m='185058'>registers.</span> </p><p><span m='185489'>Here's</span> <span\
  \ m='185755'>the</span> <span m='186021'>state</span> <span m='186288'>transition</span>\
  \ <span m='186554'>diagram</span> <span m='186821'>for</span> <span m='187087'>the</span>\
  \ <span m='187354'>control</span> <span m='187620'>FSM</span> <span m='187887'>we'd</span>\
  \ <span m='188153'>use</span> <span m='188420'>if</span> <span m='188686'>we</span>\
  \ <span m='188953'>wanted</span> <span m='189219'>to</span> <span m='189486'>use</span>\
  \ <span m='189752'>this</span> <span m='190019'>datapath</span> <span m='190431'>to</span>\
  \ <span m='190843'>compute</span> <span m='191255'>factorial</span> <span m='191668'>assuming</span>\
  \ <span m='192080'>the</span> <span m='192492'>initial</span> <span m='192905'>contents</span>\
  \ <span m='193317'>of</span> <span m='193729'>the</span> <span m='194142'>data</span>\
  \ <span m='194554'>registers</span> <span m='194966'>are</span> <span m='195379'>as</span>\
  \ <span m='196054'>shown.</span> </p><p><span m='196730'>We</span> <span m='196998'>need</span>\
  \ <span m='197266'>a</span> <span m='197534'>few</span> <span m='197802'>more</span>\
  \ <span m='198070'>states</span> <span m='198338'>than</span> <span m='198606'>in</span>\
  \ <span m='198874'>our</span> <span m='199142'>initial</span> <span m='199410'>implementation</span>\
  \ <span m='199678'>since</span> <span m='199946'>this</span> <span m='200214'>datapath</span>\
  \ <span m='200482'>can</span> <span m='200750'>only</span> <span m='201019'>perform</span>\
  \ <span m='201440'>one</span> <span m='201862'>operation</span> <span m='202284'>at</span>\
  \ <span m='202706'>each</span> <span m='203128'>step.</span> </p><p><span m='203550'>So</span>\
  \ <span m='203936'>we</span> <span m='204322'>need</span> <span m='204708'>three</span>\
  \ <span m='205095'>steps</span> <span m='205481'>for</span> <span m='205867'>each</span>\
  \ <span m='206253'>iteration:</span> <span m='206640'>one</span> <span m='207026'>for</span>\
  \ <span m='207412'>the</span> <span m='207798'>multiply,</span> <span m='208185'>one</span>\
  \ <span m='208571'>for</span> <span m='208957'>the</span> <span m='209343'>decrement,</span>\
  \ <span m='209730'>and</span> <span m='210022'>one</span> <span m='210314'>for</span>\
  \ <span m='210606'>the</span> <span m='210898'>test</span> <span m='211190'>to</span>\
  \ <span m='211482'>see</span> <span m='211774'>if</span> <span m='212066'>we're</span>\
  \ <span m='212358'>done.</span> </p><p><span m='212650'>As</span> <span m='212928'>seen</span>\
  \ <span m='213206'>here,</span> <span m='213484'>it's</span> <span m='213762'>often</span>\
  \ <span m='214040'>the</span> <span m='214318'>case</span> <span m='214596'>that</span>\
  \ <span m='214874'>general-purpose</span> <span m='215152'>computer</span> <span\
  \ m='215430'>hardware</span> <span m='215708'>will</span> <span m='215986'>need</span>\
  \ <span m='216264'>more</span> <span m='216542'>cycles</span> <span m='216820'>and</span>\
  \ <span m='217099'>perhaps</span> <span m='217779'>involve</span> <span m='218459'>more</span>\
  \ <span m='219139'>hardware</span> <span m='219819'>than</span> <span m='220499'>an</span>\
  \ <span m='221179'>optimized</span> <span m='221859'>single-purpose</span> <span\
  \ m='222539'>circuit.</span> </p><p><span m='223220'>You</span> <span m='223541'>can</span>\
  \ <span m='223862'>solve</span> <span m='224183'>many</span> <span m='224504'>different</span>\
  \ <span m='224825'>problems</span> <span m='225146'>with</span> <span m='225467'>this</span>\
  \ <span m='225788'>system:</span> <span m='226110'>exponentiation,</span> <span\
  \ m='226411'>division,</span> <span m='226712'>square</span> <span m='227013'>root,</span>\
  \ <span m='227315'>and</span> <span m='227616'>so</span> <span m='227917'>on,</span>\
  \ <span m='228218'>so</span> <span m='228520'>long</span> <span m='228821'>as</span>\
  \ <span m='229122'>you</span> <span m='229423'>don't</span> <span m='229725'>need</span>\
  \ <span m='230026'>more</span> <span m='230327'>than</span> <span m='230629'>four</span>\
  \ <span m='231044'>data</span> <span m='231459'>registers</span> <span m='231875'>to</span>\
  \ <span m='232290'>hold</span> <span m='232706'>input</span> <span m='233121'>data,</span>\
  \ <span m='233537'>intermediate</span> <span m='233952'>results,</span> <span m='234368'>or</span>\
  \ <span m='234783'>the</span> <span m='235199'>final</span> <span m='235614'>answer.</span>\
  \ </p><p><span m='236030'>By</span> <span m='236387'>designing</span> <span m='236744'>a</span>\
  \ <span m='237101'>control</span> <span m='237458'>FSM,</span> <span m='237815'>we</span>\
  \ <span m='238172'>are</span> <span m='238530'>in</span> <span m='238887'>effect</span>\
  \ <span m='239244'>\"programming\"</span> <span m='239601'>our</span> <span m='239958'>digital</span>\
  \ <span m='240315'>system,</span> <span m='240672'>specifying</span> <span m='241030'>the</span>\
  \ <span m='241502'>sequence</span> <span m='241975'>of</span> <span m='242448'>operations</span>\
  \ <span m='242921'>it</span> <span m='243394'>will</span> <span m='243867'>perform.</span>\
  \ </p><p><span m='244340'>This</span> <span m='244732'>is</span> <span m='245124'>exactly</span>\
  \ <span m='245516'>how</span> <span m='245908'>the</span> <span m='246301'>early</span>\
  \ <span m='246693'>digital</span> <span m='247085'>computers</span> <span m='247477'>worked!</span>\
  \ </p><p><span m='247870'>Here's</span> <span m='248302'>a</span> <span m='248734'>picture</span>\
  \ <span m='249166'>of</span> <span m='249598'>the</span> <span m='250030'>ENIAC</span>\
  \ <span m='250462'>computer</span> <span m='250894'>built</span> <span m='251326'>in</span>\
  \ <span m='251758'>1943</span> <span m='252190'>at</span> <span m='252622'>the</span>\
  \ <span m='253054'>University</span> <span m='253486'>of</span> <span m='253918'>Pennsylvania.</span>\
  \ </p><p><span m='254350'>The</span> <span m='254672'>Wikipedia</span> <span m='254995'>article</span>\
  \ <span m='255318'>on</span> <span m='255640'>the</span> <span m='255963'>ENIAC</span>\
  \ <span m='256286'>tells</span> <span m='256608'>us</span> <span m='256931'>that</span>\
  \ <span m='257254'>\"ENIAC</span> <span m='257576'>could</span> <span m='257899'>be</span>\
  \ <span m='258222'>programmed</span> <span m='258544'>to</span> <span m='258867'>perform</span>\
  \ <span m='259190'>complex</span> <span m='259747'>sequences</span> <span m='260305'>of</span>\
  \ <span m='260863'>operations,</span> <span m='261421'>including</span> <span m='261978'>loops,</span>\
  \ <span m='262536'>branches,</span> <span m='263094'>and</span> <span m='263652'>subroutines.</span>\
  \ </p><p><span m='264210'>The</span> <span m='264480'>task</span> <span m='264751'>of</span>\
  \ <span m='265021'>taking</span> <span m='265292'>a</span> <span m='265563'>problem</span>\
  \ <span m='265833'>and</span> <span m='266104'>mapping</span> <span m='266375'>it</span>\
  \ <span m='266645'>onto</span> <span m='266916'>the</span> <span m='267186'>machine</span>\
  \ <span m='267457'>was</span> <span m='267728'>complex,</span> <span m='267998'>and</span>\
  \ <span m='268269'>usually</span> <span m='268540'>took</span> <span m='269295'>weeks.</span>\
  \ </p><p><span m='270050'>After</span> <span m='270351'>the</span> <span m='270653'>program</span>\
  \ <span m='270955'>was</span> <span m='271257'>figured</span> <span m='271559'>out</span>\
  \ <span m='271861'>on</span> <span m='272163'>paper,</span> <span m='272465'>the</span>\
  \ <span m='272766'>process</span> <span m='273068'>of</span> <span m='273370'>getting</span>\
  \ <span m='273672'>the</span> <span m='273974'>program</span> <span m='274276'>into</span>\
  \ <span m='274578'>ENIAC</span> <span m='274880'>by</span> <span m='275217'>manipulating</span>\
  \ <span m='275555'>its</span> <span m='275893'>switches</span> <span m='276230'>and</span>\
  \ <span m='276568'>cables</span> <span m='276906'>could</span> <span m='277243'>take</span>\
  \ <span m='277581'>days.</span> </p><p><span m='277919'>This</span> <span m='278292'>was</span>\
  \ <span m='278665'>followed</span> <span m='279038'>by</span> <span m='279411'>a</span>\
  \ <span m='279784'>period</span> <span m='280157'>of</span> <span m='280530'>verification</span>\
  \ <span m='280904'>and</span> <span m='281277'>debugging,</span> <span m='281650'>aided</span>\
  \ <span m='282023'>by</span> <span m='282396'>the</span> <span m='282769'>ability</span>\
  \ <span m='283142'>to</span> <span m='283515'>execute</span> <span m='283889'>the</span>\
  \ <span m='284195'>program</span> <span m='284501'>step</span> <span m='284807'>by</span>\
  \ <span m='285113'>step.\"</span> <span m='285419'>It's</span> <span m='285764'>clear</span>\
  \ <span m='286109'>that</span> <span m='286455'>we</span> <span m='286800'>need</span>\
  \ <span m='287145'>a</span> <span m='287491'>less</span> <span m='287836'>cumbersome</span>\
  \ <span m='288182'>way</span> <span m='288527'>to</span> <span m='288872'>program</span>\
  \ <span m='289218'>our</span> <span m='289563'>computer!</span> </p>"
type: course
uid: 421ee09a248a669cfe5f1d9d654ecc7f

---
None