---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: RbJV-g9Lob8
  parent_uid: 0bba8cc146e2463f649b2e8260850aba
  title: Video-YouTube-Stream
  type: Video
  uid: 119a5b78e7ab30ae18eb573a3b10232c
- id: 3Play-3Play YouTube id-Stream
  media_location: RbJV-g9Lob8
  parent_uid: 0bba8cc146e2463f649b2e8260850aba
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 7777233ef337189178469f1710595274
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/RbJV-g9Lob8/default.jpg
  parent_uid: 0bba8cc146e2463f649b2e8260850aba
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e4b293b9d3ae9ef960b53a907fc69f4d
- id: RbJV-g9Lob8.srt
  parent_uid: 0bba8cc146e2463f649b2e8260850aba
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v6/signed-integers-2-s-complement-4-34-/RbJV-g9Lob8.srt
  title: 3play caption file
  type: null
  uid: d0adfd41ee6ff4fcb1097fa8ad8a6c79
- id: RbJV-g9Lob8.pdf
  parent_uid: 0bba8cc146e2463f649b2e8260850aba
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v6/signed-integers-2-s-complement-4-34-/RbJV-g9Lob8.pdf
  title: 3play pdf file
  type: null
  uid: 8091a65bb6a2ff326046748e18c68cf4
- id: Caption-3Play YouTube id-SRT
  parent_uid: 0bba8cc146e2463f649b2e8260850aba
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 5acf4913926d0e9203442f60d28aa043
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 0bba8cc146e2463f649b2e8260850aba
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: f1e97af927d215d8d64c504869c0af25
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_01-02-06_300k.mp4
  parent_uid: 0bba8cc146e2463f649b2e8260850aba
  title: Video-Internet Archive-MP4
  type: Video
  uid: eb38204ab14bbfc2c28d1ef782e567b8
inline_embed_id: 46658984signedintegers2scomplement43441849539
layout: video
order_index: null
parent_uid: 66a62b8c95e32d6f7927da1d414dfbbc
related_resources_text: ''
short_url: signed-integers-2-s-complement-4-34-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v6/signed-integers-2-s-complement-4-34-
template_type: Embed
title: 'Signed Integers: 2''s complement (4:34)'
transcript: "<p><span m='830'>Our</span> <span m='1111'>final</span> <span m='1392'>challenge</span>\
  \ <span m='1674'>is</span> <span m='1955'>figuring</span> <span m='2237'>out</span>\
  \ <span m='2518'>how</span> <span m='2800'>to</span> <span m='3081'>represent</span>\
  \ <span m='3362'>signed</span> <span m='3644'>integers,</span> <span m='3925'>for</span>\
  \ <span m='4207'>example,</span> <span m='4488'>what</span> <span m='4770'>should</span>\
  \ <span m='5273'>be</span> <span m='5777'>our</span> <span m='6281'>representation</span>\
  \ <span m='6785'>for</span> <span m='7288'>the</span> <span m='7792'>number</span>\
  \ <span m='8296'>-2000?</span> </p><p><span m='8800'>In</span> <span m='9108'>decimal</span>\
  \ <span m='9416'>notation,</span> <span m='9724'>the</span> <span m='10032'>convention</span>\
  \ <span m='10341'>is</span> <span m='10649'>to</span> <span m='10957'>precede</span>\
  \ <span m='11265'>the</span> <span m='11574'>number</span> <span m='11882'>with</span>\
  \ <span m='12190'>a</span> <span m='12498'>\"+\"</span> <span m='12807'>or</span>\
  \ <span m='13115'>\"-\"</span> <span m='13423'>to</span> <span m='13731'>indicate</span>\
  \ <span m='14040'>whether</span> <span m='14375'>it's</span> <span m='14710'>positive</span>\
  \ <span m='15046'>or</span> <span m='15381'>negative,</span> <span m='15716'>usually</span>\
  \ <span m='16052'>omitting</span> <span m='16387'>the</span> <span m='16723'>\"\
  +\"</span> <span m='17058'>to</span> <span m='17393'>simplify</span> <span m='17729'>the</span>\
  \ <span m='18064'>notation</span> <span m='18400'>for</span> <span m='18780'>positive</span>\
  \ <span m='19160'>numbers.</span> <span m='19540'>We</span> <span m='19920'>could</span>\
  \ <span m='20300'>adopt</span> <span m='20680'>a</span> <span m='21060'>similar</span>\
  \ <span m='21440'>notation</span> <span m='21820'>--</span> <span m='22200'>called</span>\
  \ <span m='22580'>\"signed</span> <span m='22945'>magnitude\"</span> <span m='23311'>--</span>\
  \ <span m='23676'>in</span> <span m='24042'>binary,</span> <span m='24408'>by</span>\
  \ <span m='24773'>allocating</span> <span m='25139'>a</span> <span m='25505'>separate</span>\
  \ <span m='25870'>bit</span> <span m='26236'>at</span> <span m='26601'>the</span>\
  \ <span m='26967'>front</span> <span m='27333'>of</span> <span m='27698'>the</span>\
  \ <span m='28064'>binary</span> <span m='28430'>string</span> <span m='28790'>to</span>\
  \ <span m='29150'>indicate</span> <span m='29510'>the</span> <span m='29870'>sign,</span>\
  \ <span m='30230'>say</span> <span m='30590'>\"0\"</span> <span m='30950'>for</span>\
  \ <span m='31310'>positive</span> <span m='31670'>numbers</span> <span m='32030'>and</span>\
  \ <span m='32390'>\"1\"</span> <span m='32750'>for</span> <span m='33110'>negative</span>\
  \ <span m='33470'>numbers.</span> </p><p><span m='33830'>So</span> <span m='34228'>the</span>\
  \ <span m='34626'>signed-magnitude</span> <span m='35025'>representation</span>\
  \ <span m='35423'>for</span> <span m='35822'>-2000</span> <span m='36220'>would</span>\
  \ <span m='36619'>be</span> <span m='37017'>an</span> <span m='37416'>initial</span>\
  \ <span m='37814'>\"1\"</span> <span m='38213'>to</span> <span m='38611'>indicate</span>\
  \ <span m='39010'>a</span> <span m='39314'>negative</span> <span m='39618'>number,</span>\
  \ <span m='39922'>followed</span> <span m='40226'>by</span> <span m='40530'>the</span>\
  \ <span m='40834'>representation</span> <span m='41138'>for</span> <span m='41442'>2000</span>\
  \ <span m='41746'>(as</span> <span m='42050'>described</span> <span m='42354'>on</span>\
  \ <span m='42658'>the</span> <span m='42962'>previous</span> <span m='43266'>two</span>\
  \ <span m='43570'>slides).</span> <span m='44066'>However</span> <span m='44562'>there</span>\
  \ <span m='45058'>are</span> <span m='45555'>some</span> <span m='46051'>complications</span>\
  \ <span m='46547'>in</span> <span m='47043'>using</span> <span m='47540'>a</span>\
  \ <span m='48033'>signed-magnitude</span> <span m='48526'>representation.</span>\
  \ <span m='49020'>There</span> <span m='49513'>are</span> <span m='50006'>two</span>\
  \ <span m='50500'>possible</span> <span m='50993'>binary</span> <span m='51486'>representations</span>\
  \ <span m='51980'>for</span> <span m='52449'>zero:</span> <span m='52918'>\"+0\"\
  </span> <span m='53387'>and</span> <span m='53856'>\"-0\".</span> <span m='54325'>This</span>\
  \ <span m='54794'>makes</span> <span m='55263'>the</span> <span m='55732'>encoding</span>\
  \ <span m='56201'>slightly</span> <span m='56670'>inefficient</span> <span m='57140'>but,</span>\
  \ <span m='57536'>more</span> <span m='57933'>importantly,</span> <span m='58330'>the</span>\
  \ <span m='58727'>circuitry</span> <span m='59124'>for</span> <span m='59521'>doing</span>\
  \ <span m='59918'>addition</span> <span m='60315'>of</span> <span m='60712'>signed-magnitude</span>\
  \ <span m='61109'>numbers</span> <span m='61506'>is</span> <span m='61903'>different</span>\
  \ <span m='62300'>than</span> <span m='62628'>the</span> <span m='62956'>circuitry</span>\
  \ <span m='63284'>for</span> <span m='63612'>doing</span> <span m='63940'>subtraction.</span>\
  \ <span m='64268'>Of</span> <span m='64596'>course,</span> <span m='64924'>we're</span>\
  \ <span m='65252'>used</span> <span m='65580'>to</span> <span m='65908'>that</span>\
  \ <span m='66236'>\u2013</span> <span m='66564'>in</span> <span m='66892'>elementary</span>\
  \ <span m='67220'>school</span> <span m='67684'>we</span> <span m='68149'>learned</span>\
  \ <span m='68613'>one</span> <span m='69078'>technique</span> <span m='69542'>for</span>\
  \ <span m='70007'>addition</span> <span m='70471'>and</span> <span m='70936'>another</span>\
  \ <span m='71400'>for</span> <span m='71865'>subtraction.</span> </p><p><span m='72330'>To</span>\
  \ <span m='72705'>keep</span> <span m='73080'>the</span> <span m='73455'>circuitry</span>\
  \ <span m='73830'>simple,</span> <span m='74205'>most</span> <span m='74580'>modern</span>\
  \ <span m='74955'>digital</span> <span m='75330'>systems</span> <span m='75705'>use</span>\
  \ <span m='76080'>the</span> <span m='76455'>two's</span> <span m='76830'>complement</span>\
  \ <span m='77205'>binary</span> <span m='77580'>representation</span> <span m='78061'>for</span>\
  \ <span m='78542'>signed</span> <span m='79023'>numbers.</span> <span m='79504'>In</span>\
  \ <span m='79985'>this</span> <span m='80466'>representation,</span> <span m='80947'>the</span>\
  \ <span m='81428'>high-order</span> <span m='81909'>bit</span> <span m='82390'>of</span>\
  \ <span m='82722'>an</span> <span m='83054'>N-bit</span> <span m='83386'>two's</span>\
  \ <span m='83718'>complement</span> <span m='84050'>number</span> <span m='84382'>has</span>\
  \ <span m='84714'>a</span> <span m='85046'>negative</span> <span m='85378'>weight,</span>\
  \ <span m='85710'>as</span> <span m='86042'>shown</span> <span m='86374'>in</span>\
  \ <span m='86706'>the</span> <span m='87038'>figure.</span> </p><p><span m='87370'>Thus</span>\
  \ <span m='87648'>all</span> <span m='87926'>negative</span> <span m='88204'>numbers</span>\
  \ <span m='88482'>have</span> <span m='88761'>a</span> <span m='89039'>1</span>\
  \ <span m='89317'>in</span> <span m='89595'>the</span> <span m='89874'>high-order</span>\
  \ <span m='90152'>bit</span> <span m='90430'>and,</span> <span m='90708'>in</span>\
  \ <span m='90987'>that</span> <span m='91265'>sense,</span> <span m='91543'>the</span>\
  \ <span m='91821'>high-order</span> <span m='92100'>bit</span> <span m='92446'>is</span>\
  \ <span m='92792'>serving</span> <span m='93138'>as</span> <span m='93485'>the</span>\
  \ <span m='93831'>\"sign</span> <span m='94177'>bit\"</span> <span m='94523'>\u2013\
  </span> <span m='94870'>if</span> <span m='95216'>it's</span> <span m='95562'>1,</span>\
  \ <span m='95908'>the</span> <span m='96255'>represented</span> <span m='96601'>number</span>\
  \ <span m='96947'>is</span> <span m='97293'>negative.</span> </p><p><span m='97640'>The</span>\
  \ <span m='97938'>most</span> <span m='98237'>negative</span> <span m='98535'>N-bit</span>\
  \ <span m='98834'>number</span> <span m='99132'>has</span> <span m='99431'>a</span>\
  \ <span m='99730'>1-bit</span> <span m='100028'>in</span> <span m='100327'>the</span>\
  \ <span m='100625'>high-order</span> <span m='100924'>position,</span> <span m='101222'>representing</span>\
  \ <span m='101521'>the</span> <span m='101820'>value</span> <span m='102392'>-2^(N-1).</span>\
  \ <span m='102965'>The</span> <span m='103538'>most</span> <span m='104110'>positive</span>\
  \ <span m='104683'>N-bit</span> <span m='105256'>number</span> <span m='105829'>has</span>\
  \ <span m='106401'>a</span> <span m='106974'>0</span> <span m='107547'>in</span>\
  \ <span m='108120'>the</span> <span m='108521'>negative-weight</span> <span m='108923'>high-order</span>\
  \ <span m='109325'>bit</span> <span m='109726'>and</span> <span m='110128'>1's</span>\
  \ <span m='110530'>for</span> <span m='110931'>all</span> <span m='111333'>the</span>\
  \ <span m='111735'>positive-weight</span> <span m='112136'>bits,</span> <span m='112538'>representing</span>\
  \ <span m='112940'>the</span> <span m='113584'>value</span> <span m='114229'>2^(N-1)-1.</span>\
  \ <span m='114873'>This</span> <span m='115518'>gives</span> <span m='116162'>us</span>\
  \ <span m='116807'>the</span> <span m='117451'>range</span> <span m='118096'>of</span>\
  \ <span m='118740'>possible</span> <span m='119385'>values</span> <span m='120030'>\u2013\
  </span> <span m='120543'>for</span> <span m='121057'>example,</span> <span m='121570'>in</span>\
  \ <span m='122084'>an</span> <span m='122597'>8-bit</span> <span m='123111'>two's</span>\
  \ <span m='123625'>complement</span> <span m='124138'>representation,</span> <span\
  \ m='124652'>the</span> <span m='125165'>most</span> <span m='125679'>negative</span>\
  \ <span m='126192'>number</span> <span m='126706'>is</span> <span m='127220'>-2^7</span>\
  \ <span m='127862'>=</span> <span m='128505'>-128</span> <span m='129148'>and</span>\
  \ <span m='129791'>the</span> <span m='130434'>most</span> <span m='131077'>positive</span>\
  \ <span m='131720'>number</span> <span m='132362'>is</span> <span m='133005'>2^7</span>\
  \ <span m='133648'>\u2013</span> <span m='134291'>1</span> <span m='134934'>=</span>\
  \ <span m='135577'>127.</span> </p><p><span m='136220'>If</span> <span m='136444'>all</span>\
  \ <span m='136668'>N</span> <span m='136892'>bits</span> <span m='137116'>are</span>\
  \ <span m='137340'>1,</span> <span m='137564'>think</span> <span m='137788'>of</span>\
  \ <span m='138012'>that</span> <span m='138236'>as</span> <span m='138460'>the</span>\
  \ <span m='138684'>sum</span> <span m='138908'>of</span> <span m='139132'>the</span>\
  \ <span m='139356'>most</span> <span m='139580'>negative</span> <span m='139804'>number</span>\
  \ <span m='140028'>with</span> <span m='140252'>the</span> <span m='140476'>most</span>\
  \ <span m='140700'>positive</span> <span m='141857'>number,</span> <span m='143015'>i.e.,</span>\
  \ <span m='144173'>-2^(N-1)</span> <span m='145331'>+</span> <span m='146488'>2^(N-1)-1,</span>\
  \ <span m='147646'>which</span> <span m='148804'>equals</span> <span m='149962'>-1.</span>\
  \ </p><p><span m='151120'>And,</span> <span m='151580'>of</span> <span m='152041'>course,</span>\
  \ <span m='152502'>if</span> <span m='152962'>all</span> <span m='153423'>N</span>\
  \ <span m='153884'>bits</span> <span m='154344'>are</span> <span m='154805'>0,</span>\
  \ <span m='155266'>that's</span> <span m='155726'>the</span> <span m='156187'>unique</span>\
  \ <span m='156648'>representation</span> <span m='157108'>of</span> <span m='157569'>0.</span>\
  \ </p><p><span m='158030'>Let's</span> <span m='158383'>see</span> <span m='158736'>what</span>\
  \ <span m='159090'>happens</span> <span m='159443'>when</span> <span m='159796'>we</span>\
  \ <span m='160150'>add</span> <span m='160503'>the</span> <span m='160856'>N-bit</span>\
  \ <span m='161210'>values</span> <span m='161563'>for</span> <span m='161916'>-1</span>\
  \ <span m='162270'>and</span> <span m='162623'>1,</span> <span m='162976'>keeping</span>\
  \ <span m='163330'>an</span> <span m='163683'>N-bit</span> <span m='164036'>answer.</span>\
  \ </p><p><span m='164390'>In</span> <span m='164797'>the</span> <span m='165205'>rightmost</span>\
  \ <span m='165612'>column,</span> <span m='166020'>1</span> <span m='166427'>plus</span>\
  \ <span m='166835'>1</span> <span m='167242'>is</span> <span m='167650'>0,</span>\
  \ <span m='168057'>carry</span> <span m='168465'>the</span> <span m='168872'>1.</span>\
  \ </p><p><span m='169280'>In</span> <span m='169574'>the</span> <span m='169868'>second</span>\
  \ <span m='170162'>column,</span> <span m='170456'>the</span> <span m='170750'>carry</span>\
  \ <span m='171044'>of</span> <span m='171338'>1</span> <span m='171632'>plus</span>\
  \ <span m='171927'>1</span> <span m='172221'>plus</span> <span m='172515'>0</span>\
  \ <span m='172809'>is</span> <span m='173103'>0,</span> <span m='173397'>carry</span>\
  \ <span m='173691'>the</span> <span m='173985'>1.</span> </p><p><span m='174280'>And</span>\
  \ <span m='174717'>so</span> <span m='175154'>on</span> <span m='175591'>\u2013\
  </span> <span m='176028'>the</span> <span m='176465'>result</span> <span m='176902'>is</span>\
  \ <span m='177340'>all</span> <span m='177777'>zero's,</span> <span m='178214'>the</span>\
  \ <span m='178651'>representation</span> <span m='179088'>for</span> <span m='179525'>0\u2026\
  </span> <span m='179962'>perfect!</span> </p><p><span m='180400'>Notice</span> <span\
  \ m='180748'>that</span> <span m='181096'>we</span> <span m='181444'>just</span>\
  \ <span m='181792'>used</span> <span m='182141'>ordinary</span> <span m='182489'>binary</span>\
  \ <span m='182837'>addition,</span> <span m='183185'>even</span> <span m='183534'>when</span>\
  \ <span m='183882'>one</span> <span m='184230'>or</span> <span m='184578'>both</span>\
  \ <span m='184927'>of</span> <span m='185275'>the</span> <span m='185623'>operands</span>\
  \ <span m='185971'>are</span> <span m='186320'>negative.</span> <span m='187025'>Two's</span>\
  \ <span m='187730'>complement</span> <span m='188435'>is</span> <span m='189140'>perfect</span>\
  \ <span m='189845'>for</span> <span m='190550'>N-bit</span> <span m='191255'>arithmetic!</span>\
  \ </p><p><span m='191960'>To</span> <span m='192343'>compute</span> <span m='192726'>B</span>\
  \ <span m='193110'>-</span> <span m='193493'>A,</span> <span m='193876'>we</span>\
  \ <span m='194260'>can</span> <span m='194643'>just</span> <span m='195026'>use</span>\
  \ <span m='195410'>addition</span> <span m='195793'>and</span> <span m='196176'>compute</span>\
  \ <span m='196560'>B</span> <span m='196943'>+</span> <span m='197326'>(-A).</span>\
  \ </p><p><span m='197710'>So</span> <span m='198011'>now</span> <span m='198313'>we</span>\
  \ <span m='198615'>just</span> <span m='198917'>need</span> <span m='199219'>to</span>\
  \ <span m='199521'>figure</span> <span m='199823'>out</span> <span m='200125'>the</span>\
  \ <span m='200427'>two's</span> <span m='200729'>complement</span> <span m='201031'>representation</span>\
  \ <span m='201333'>for</span> <span m='201635'>\u2013A,</span> <span m='201937'>given</span>\
  \ <span m='202239'>the</span> <span m='202686'>two's</span> <span m='203134'>complement</span>\
  \ <span m='203581'>representation</span> <span m='204029'>for</span> <span m='204477'>A.</span>\
  \ <span m='204924'>Well,</span> <span m='205372'>we</span> <span m='205820'>know</span>\
  \ <span m='206267'>that</span> <span m='206715'>A</span> <span m='207163'>+</span>\
  \ <span m='207610'>(-A)</span> <span m='208058'>=</span> <span m='208506'>0</span>\
  \ <span m='208953'>and</span> <span m='209401'>using</span> <span m='209849'>the</span>\
  \ <span m='210305'>example</span> <span m='210761'>above,</span> <span m='211218'>we</span>\
  \ <span m='211674'>can</span> <span m='212131'>rewrite</span> <span m='212587'>0</span>\
  \ <span m='213044'>as</span> <span m='213500'>1</span> <span m='213957'>+</span>\
  \ <span m='214413'>(-1).</span> </p><p><span m='214870'>Reorganizing</span> <span\
  \ m='215354'>terms,</span> <span m='215838'>we</span> <span m='216322'>see</span>\
  \ <span m='216807'>that</span> <span m='217291'>\u2013A</span> <span m='217775'>equals</span>\
  \ <span m='218260'>1</span> <span m='218744'>plus</span> <span m='219228'>the</span>\
  \ <span m='219712'>quantity</span> <span m='220197'>(-1)</span> <span m='220681'>\u2013\
  </span> <span m='221165'>A.</span> </p><p><span m='221650'>As</span> <span m='221968'>we</span>\
  \ <span m='222286'>saw</span> <span m='222605'>above,</span> <span m='222923'>the</span>\
  \ <span m='223241'>two's</span> <span m='223560'>complement</span> <span m='223878'>representation</span>\
  \ <span m='224196'>for</span> <span m='224515'>-1</span> <span m='224833'>is</span>\
  \ <span m='225151'>all</span> <span m='225470'>1-bits,</span> <span m='225788'>so</span>\
  \ <span m='226106'>we</span> <span m='226425'>can</span> <span m='226743'>write</span>\
  \ <span m='227061'>that</span> <span m='227380'>subtraction</span> <span m='227897'>as</span>\
  \ <span m='228415'>all</span> <span m='228932'>1's</span> <span m='229450'>minus</span>\
  \ <span m='229967'>the</span> <span m='230485'>individual</span> <span m='231002'>bits</span>\
  \ <span m='231520'>of</span> <span m='232037'>A:</span> <span m='232555'>A_0,</span>\
  \ <span m='233072'>A_1,</span> <span m='233590'>\u2026</span> <span m='234107'>up</span>\
  \ <span m='234625'>to</span> <span m='235142'>A_N-1.</span> </p><p><span m='235660'>If</span>\
  \ <span m='236141'>a</span> <span m='236623'>particular</span> <span m='237104'>bit</span>\
  \ <span m='237586'>A_i</span> <span m='238067'>is</span> <span m='238549'>0,</span>\
  \ <span m='239030'>then</span> <span m='239512'>1-A_i</span> <span m='239993'>=</span>\
  \ <span m='240475'>1</span> <span m='240956'>and</span> <span m='241438'>if</span>\
  \ <span m='241919'>A_i</span> <span m='242401'>is</span> <span m='242882'>1,</span>\
  \ <span m='243364'>then</span> <span m='243845'>1-A_i</span> <span m='244327'>=</span>\
  \ <span m='244808'>0.</span> </p><p><span m='245290'>So</span> <span m='245637'>in</span>\
  \ <span m='245985'>each</span> <span m='246332'>column,</span> <span m='246680'>the</span>\
  \ <span m='247027'>result</span> <span m='247375'>is</span> <span m='247722'>the</span>\
  \ <span m='248070'>bitwise</span> <span m='248417'>complement</span> <span m='248765'>of</span>\
  \ <span m='249112'>A_i,</span> <span m='249460'>which</span> <span m='249807'>we'll</span>\
  \ <span m='250155'>write</span> <span m='250502'>using</span> <span m='250850'>the</span>\
  \ <span m='251496'>C-language</span> <span m='252143'>bitwise</span> <span m='252790'>complement</span>\
  \ <span m='253436'>operator</span> <span m='254083'>tilde.</span> </p><p><span m='254730'>So</span>\
  \ <span m='255132'>we</span> <span m='255534'>see</span> <span m='255936'>that</span>\
  \ <span m='256338'>\u2013A</span> <span m='256741'>equals</span> <span m='257143'>the</span>\
  \ <span m='257545'>bitwise</span> <span m='257947'>complement</span> <span m='258350'>of</span>\
  \ <span m='258752'>A</span> <span m='259154'>plus</span> <span m='259556'>1.</span>\
  \ </p><p><span m='259959'>Ta-dah!</span> <span m='260436'>To</span> <span m='260914'>practice</span>\
  \ <span m='261391'>your</span> <span m='261869'>skill</span> <span m='262346'>with</span>\
  \ <span m='262824'>two's</span> <span m='263301'>complement,</span> <span m='263779'>try</span>\
  \ <span m='264051'>your</span> <span m='264324'>hand</span> <span m='264597'>at</span>\
  \ <span m='264870'>the</span> <span m='265143'>following</span> <span m='265416'>exercises.</span>\
  \ <span m='265689'>All</span> <span m='265962'>you</span> <span m='266235'>need</span>\
  \ <span m='266508'>to</span> <span m='266781'>remember</span> <span m='267054'>is</span>\
  \ <span m='267327'>how</span> <span m='267600'>to</span> <span m='267873'>do</span>\
  \ <span m='268146'>binary</span> <span m='268420'>addition</span> <span m='268841'>and</span>\
  \ <span m='269263'>two's</span> <span m='269685'>complement</span> <span m='270106'>negation</span>\
  \ <span m='270528'>(which</span> <span m='270950'>is</span> <span m='271371'>\"\
  bitwise</span> <span m='271793'>complement</span> <span m='272215'>and</span> <span\
  \ m='272636'>add</span> <span m='273058'>1\").</span> </p>"
type: course
uid: 0bba8cc146e2463f649b2e8260850aba

---
None