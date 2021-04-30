---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 3VGZANOQXAM
  parent_uid: e31fa8344a997f1511d38dfa12c2327b
  title: Video-YouTube-Stream
  type: Video
  uid: 435275c6065953291ee71a321fdf2e95
- id: 3Play-3Play YouTube id-Stream
  media_location: 3VGZANOQXAM
  parent_uid: e31fa8344a997f1511d38dfa12c2327b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 98d5fe25424e09774ff3ed9d9be75e4c
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/3VGZANOQXAM/default.jpg
  parent_uid: e31fa8344a997f1511d38dfa12c2327b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: c299e72ab5c529fa34e2224fee7c4dd2
- id: 3VGZANOQXAM.srt
  parent_uid: e31fa8344a997f1511d38dfa12c2327b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v9/jumps-3-24-/3VGZANOQXAM.srt
  title: 3play caption file
  type: null
  uid: 131df993b16ef24932461d2bdc0c2817
- id: 3VGZANOQXAM.pdf
  parent_uid: e31fa8344a997f1511d38dfa12c2327b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v9/jumps-3-24-/3VGZANOQXAM.pdf
  title: 3play pdf file
  type: null
  uid: f4d244197b4887680130c91b55dc02fd
- id: Caption-3Play YouTube id-SRT
  parent_uid: e31fa8344a997f1511d38dfa12c2327b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 4c477930815a942bb068bdd460a053ed
- id: Transcript-3Play YouTube id-PDF
  parent_uid: e31fa8344a997f1511d38dfa12c2327b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 071474c516b81ebca0cea3e1df282a82
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_09-02-09_300k.mp4
  parent_uid: e31fa8344a997f1511d38dfa12c2327b
  title: Video-Internet Archive-MP4
  type: Video
  uid: ff44cded45f0bcd5fcc7a87ebc917440
inline_embed_id: 70770418jumps32497340226
layout: video
order_index: null
parent_uid: 5edf62c3bd7e7fbabac1e3feaffc724e
related_resources_text: ''
short_url: jumps-3-24-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v9/jumps-3-24-
template_type: Embed
title: Jumps (3:24)
transcript: "<p><span m='840'>Finally,</span> <span m='1587'>our</span> <span m='2335'>last</span>\
  \ <span m='3082'>instruction!</span> </p><p><span m='3830'>Branches</span> <span\
  \ m='4298'>conditionally</span> <span m='4767'>transfer</span> <span m='5236'>control</span>\
  \ <span m='5705'>to</span> <span m='6174'>a</span> <span m='6643'>specific</span>\
  \ <span m='7112'>target</span> <span m='7581'>instruction.</span> </p><p><span m='8050'>But</span>\
  \ <span m='8335'>we'll</span> <span m='8620'>also</span> <span m='8905'>need</span>\
  \ <span m='9190'>the</span> <span m='9475'>ability</span> <span m='9760'>to</span>\
  \ <span m='10045'>compute</span> <span m='10330'>the</span> <span m='10615'>address</span>\
  \ <span m='10900'>of</span> <span m='11185'>the</span> <span m='11470'>target</span>\
  \ <span m='11755'>instruction</span> <span m='12040'>-</span> <span m='12325'>that</span>\
  \ <span m='12610'>ability</span> <span m='12914'>is</span> <span m='13219'>provided</span>\
  \ <span m='13524'>by</span> <span m='13828'>the</span> <span m='14133'>JMP</span>\
  \ <span m='14438'>instruction</span> <span m='14742'>which</span> <span m='15047'>simply</span>\
  \ <span m='15352'>sets</span> <span m='15656'>the</span> <span m='15961'>program</span>\
  \ <span m='16266'>counter</span> <span m='16570'>to</span> <span m='16875'>value</span>\
  \ <span m='17180'>from</span> <span m='17796'>register</span> <span m='18413'>\"\
  ra\".</span> </p><p><span m='19030'>Like</span> <span m='19544'>branches,</span>\
  \ <span m='20058'>JMP</span> <span m='20572'>will</span> <span m='21087'>write</span>\
  \ <span m='21601'>the</span> <span m='22115'>PC+4</span> <span m='22630'>value</span>\
  \ <span m='23144'>into</span> <span m='23658'>to</span> <span m='24172'>the</span>\
  \ <span m='24687'>specified</span> <span m='25201'>destination</span> <span m='25715'>register.</span>\
  \ </p><p><span m='26230'>This</span> <span m='26598'>capability</span> <span m='26966'>is</span>\
  \ <span m='27334'>very</span> <span m='27702'>useful</span> <span m='28070'>for</span>\
  \ <span m='28438'>implementing</span> <span m='28806'>procedures</span> <span m='29174'>in</span>\
  \ <span m='29542'>Beta</span> <span m='29910'>code.</span> </p><p><span m='30279'>Suppose</span>\
  \ <span m='30582'>we</span> <span m='30886'>have</span> <span m='31190'>a</span>\
  \ <span m='31494'>procedure</span> <span m='31798'>\"sqrt\"</span> <span m='32101'>that</span>\
  \ <span m='32405'>computes</span> <span m='32709'>the</span> <span m='33013'>square</span>\
  \ <span m='33317'>root</span> <span m='33620'>of</span> <span m='33924'>its</span>\
  \ <span m='34228'>argument,</span> <span m='34532'>which</span> <span m='34836'>is</span>\
  \ <span m='35140'>passed</span> <span m='35817'>in,</span> <span m='36495'>say,</span>\
  \ <span m='37172'>R0.</span> </p><p><span m='37850'>We</span> <span m='38078'>don't</span>\
  \ <span m='38306'>show</span> <span m='38534'>the</span> <span m='38762'>code</span>\
  \ <span m='38991'>for</span> <span m='39219'>sqrt</span> <span m='39447'>on</span>\
  \ <span m='39675'>the</span> <span m='39904'>right,</span> <span m='40132'>except</span>\
  \ <span m='40360'>for</span> <span m='40588'>the</span> <span m='40817'>last</span>\
  \ <span m='41045'>instruction,</span> <span m='41273'>which</span> <span m='41501'>is</span>\
  \ <span m='41730'>a</span> <span m='42560'>JMP.</span> </p><p><span m='43390'>On</span>\
  \ <span m='43646'>the</span> <span m='43902'>left</span> <span m='44159'>we</span>\
  \ <span m='44415'>see</span> <span m='44672'>that</span> <span m='44928'>the</span>\
  \ <span m='45185'>programmer</span> <span m='45441'>wants</span> <span m='45698'>to</span>\
  \ <span m='45954'>call</span> <span m='46211'>the</span> <span m='46467'>sqrt</span>\
  \ <span m='46724'>procedure</span> <span m='46980'>from</span> <span m='47237'>two</span>\
  \ <span m='47493'>different</span> <span m='47750'>places</span> <span m='48220'>in</span>\
  \ <span m='48690'>his</span> <span m='49160'>program.</span> </p><p><span m='49630'>Let's</span>\
  \ <span m='50197'>watch</span> <span m='50764'>what</span> <span m='51331'>happens\u2026\
  </span> <span m='51899'>The</span> <span m='52276'>first</span> <span m='52654'>call</span>\
  \ <span m='53031'>to</span> <span m='53409'>the</span> <span m='53786'>sqrt</span>\
  \ <span m='54164'>procedure</span> <span m='54541'>is</span> <span m='54919'>implemented</span>\
  \ <span m='55297'>by</span> <span m='55674'>the</span> <span m='56052'>unconditional</span>\
  \ <span m='56429'>branch</span> <span m='56807'>at</span> <span m='57184'>location</span>\
  \ <span m='57562'>0x100</span> <span m='57940'>in</span> <span m='58483'>main</span>\
  \ <span m='59026'>memory.</span> </p><p><span m='59570'>The</span> <span m='59882'>branch</span>\
  \ <span m='60195'>target</span> <span m='60508'>is</span> <span m='60821'>the</span>\
  \ <span m='61134'>first</span> <span m='61447'>instruction</span> <span m='61760'>of</span>\
  \ <span m='62072'>the</span> <span m='62385'>sqrt</span> <span m='62698'>procedure,</span>\
  \ <span m='63011'>so</span> <span m='63324'>execution</span> <span m='63637'>continues</span>\
  \ <span m='63950'>there.</span> </p><p><span m='65299'>The</span> <span m='65861'>BEQ</span>\
  \ <span m='66423'>also</span> <span m='66985'>writes</span> <span m='67547'>the</span>\
  \ <span m='68109'>address</span> <span m='68671'>of</span> <span m='69233'>the</span>\
  \ <span m='69795'>following</span> <span m='70357'>instruction</span> <span m='70919'>(0x104)</span>\
  \ <span m='71481'>into</span> <span m='72043'>its</span> <span m='72605'>destination</span>\
  \ <span m='73167'>register,</span> <span m='73729'>R28.</span> </p><p><span m='74810'>When</span>\
  \ <span m='75119'>we</span> <span m='75428'>reach</span> <span m='75738'>the</span>\
  \ <span m='76047'>end</span> <span m='76357'>of</span> <span m='76666'>first</span>\
  \ <span m='76975'>procedure</span> <span m='77285'>call,</span> <span m='77594'>the</span>\
  \ <span m='77904'>JMP</span> <span m='78213'>instruction</span> <span m='78522'>loads</span>\
  \ <span m='78832'>the</span> <span m='79141'>value</span> <span m='79451'>in</span>\
  \ <span m='79760'>R28,</span> <span m='80070'>which</span> <span m='80509'>is</span>\
  \ <span m='80949'>0x104,</span> <span m='81389'>into</span> <span m='81829'>the</span>\
  \ <span m='82269'>PC,</span> <span m='82709'>so</span> <span m='83149'>execution</span>\
  \ <span m='83589'>continues</span> <span m='84029'>with</span> <span m='84469'>the</span>\
  \ <span m='84909'>instruction</span> <span m='85349'>following</span> <span m='85789'>the</span>\
  \ <span m='86229'>first</span> <span m='87199'>BEQ.</span> </p><p><span m='88170'>So</span>\
  \ <span m='88466'>we've</span> <span m='88763'>managed</span> <span m='89060'>to</span>\
  \ <span m='89357'>return</span> <span m='89654'>from</span> <span m='89951'>the</span>\
  \ <span m='90248'>procedure</span> <span m='90545'>and</span> <span m='90841'>continue</span>\
  \ <span m='91138'>execution</span> <span m='91435'>where</span> <span m='91732'>we</span>\
  \ <span m='92029'>left</span> <span m='92326'>off</span> <span m='92623'>in</span>\
  \ <span m='92920'>the</span> <span m='93686'>main</span> <span m='94452'>program.</span>\
  \ </p><p><span m='95219'>When</span> <span m='95466'>we</span> <span m='95713'>get</span>\
  \ <span m='95960'>to</span> <span m='96207'>the</span> <span m='96455'>second</span>\
  \ <span m='96702'>call</span> <span m='96949'>to</span> <span m='97196'>the</span>\
  \ <span m='97444'>sqrt</span> <span m='97691'>procedure,</span> <span m='97938'>the</span>\
  \ <span m='98185'>sequence</span> <span m='98432'>of</span> <span m='98680'>events</span>\
  \ <span m='98927'>is</span> <span m='99174'>the</span> <span m='99421'>same</span>\
  \ <span m='99669'>as</span> <span m='100187'>before</span> <span m='100705'>except</span>\
  \ <span m='101223'>that</span> <span m='101741'>this</span> <span m='102259'>time</span>\
  \ <span m='102777'>R28</span> <span m='103295'>contains</span> <span m='103813'>0x67C,</span>\
  \ <span m='104331'>the</span> <span m='104849'>address</span> <span m='105367'>of</span>\
  \ <span m='105885'>the</span> <span m='106403'>instruction</span> <span m='106921'>following</span>\
  \ <span m='107439'>the</span> <span m='108169'>second</span> <span m='108899'>BEQ.</span>\
  \ </p><p><span m='109630'>So</span> <span m='109952'>the</span> <span m='110275'>second</span>\
  \ <span m='110597'>time</span> <span m='110920'>we</span> <span m='111242'>reach</span>\
  \ <span m='111565'>the</span> <span m='111888'>end</span> <span m='112210'>of</span>\
  \ <span m='112533'>the</span> <span m='112855'>sqrt</span> <span m='113178'>procedure,</span>\
  \ <span m='113500'>the</span> <span m='113823'>JMP</span> <span m='114146'>sets</span>\
  \ <span m='114468'>the</span> <span m='114791'>PC</span> <span m='115113'>to</span>\
  \ <span m='115436'>0x67C</span> <span m='115759'>and</span> <span m='116242'>execution</span>\
  \ <span m='116726'>resumes</span> <span m='117209'>with</span> <span m='117693'>the</span>\
  \ <span m='118177'>instruction</span> <span m='118660'>following</span> <span m='119144'>the</span>\
  \ <span m='119628'>second</span> <span m='120111'>procedure</span> <span m='120595'>call.</span>\
  \ </p><p><span m='121079'>Neat!</span> </p><p><span m='122299'>The</span> <span\
  \ m='122617'>BEQs</span> <span m='122935'>and</span> <span m='123254'>JMP</span>\
  \ <span m='123572'>have</span> <span m='123891'>worked</span> <span m='124209'>together</span>\
  \ <span m='124528'>to</span> <span m='124846'>implement</span> <span m='125165'>procedure</span>\
  \ <span m='125483'>call</span> <span m='125802'>and</span> <span m='126120'>return.</span>\
  \ </p><p><span m='126439'>We'll</span> <span m='126931'>discuss</span> <span m='127424'>the</span>\
  \ <span m='127916'>implementation</span> <span m='128409'>of</span> <span m='128901'>procedures</span>\
  \ <span m='129394'>in</span> <span m='129886'>detail</span> <span m='130379'>in</span>\
  \ <span m='130871'>an</span> <span m='131364'>upcoming</span> <span m='131856'>lecture.</span>\
  \ </p><p><span m='132349'>That</span> <span m='132639'>wraps</span> <span m='132930'>up</span>\
  \ <span m='133221'>the</span> <span m='133512'>design</span> <span m='133803'>of</span>\
  \ <span m='134094'>the</span> <span m='134385'>Beta</span> <span m='134676'>instruction</span>\
  \ <span m='134967'>set</span> <span m='135258'>architecture.</span> </p><p><span\
  \ m='135549'>In</span> <span m='135851'>summary,</span> <span m='136154'>the</span>\
  \ <span m='136457'>Beta</span> <span m='136760'>has</span> <span m='137063'>32</span>\
  \ <span m='137366'>registers</span> <span m='137668'>to</span> <span m='137971'>hold</span>\
  \ <span m='138274'>values</span> <span m='138577'>that</span> <span m='138880'>can</span>\
  \ <span m='139183'>be</span> <span m='139485'>used</span> <span m='139788'>as</span>\
  \ <span m='140091'>operands</span> <span m='140394'>for</span> <span m='140697'>the</span>\
  \ <span m='141000'>ALU.</span> </p><p><span m='142390'>All</span> <span m='142702'>other</span>\
  \ <span m='143015'>values,</span> <span m='143327'>along</span> <span m='143640'>with</span>\
  \ <span m='143952'>the</span> <span m='144265'>binary</span> <span m='144577'>representation</span>\
  \ <span m='144890'>of</span> <span m='145202'>the</span> <span m='145515'>program</span>\
  \ <span m='145827'>itself,</span> <span m='146140'>are</span> <span m='146452'>stored</span>\
  \ <span m='146765'>in</span> <span m='147077'>main</span> <span m='147390'>memory.</span>\
  \ </p><p><span m='148960'>The</span> <span m='149413'>Beta</span> <span m='149867'>supports</span>\
  \ <span m='150321'>32-bit</span> <span m='150775'>memory</span> <span m='151229'>addresses</span>\
  \ <span m='151683'>and</span> <span m='152137'>can</span> <span m='152591'>access</span>\
  \ <span m='153045'>values</span> <span m='153499'>in</span> <span m='153953'>2^32</span>\
  \ <span m='154407'>=</span> <span m='154861'>4</span> <span m='155315'>gigabytes</span>\
  \ <span m='155769'>of</span> <span m='156476'>main</span> <span m='157183'>memory.</span>\
  \ </p><p><span m='157890'>All</span> <span m='158201'>Beta</span> <span m='158512'>memory</span>\
  \ <span m='158823'>access</span> <span m='159134'>refer</span> <span m='159445'>to</span>\
  \ <span m='159756'>32-bit</span> <span m='160067'>words,</span> <span m='160378'>so</span>\
  \ <span m='160689'>all</span> <span m='161000'>addresses</span> <span m='161311'>will</span>\
  \ <span m='161622'>be</span> <span m='161933'>a</span> <span m='162244'>multiple</span>\
  \ <span m='162555'>of</span> <span m='162866'>4</span> <span m='163177'>since</span>\
  \ <span m='163489'>there</span> <span m='163751'>are</span> <span m='164014'>4</span>\
  \ <span m='164277'>bytes/word.</span> </p><p><span m='164540'>The</span> <span m='165410'>are</span>\
  \ <span m='166280'>two</span> <span m='167150'>instruction</span> <span m='168020'>formats.</span>\
  \ </p><p><span m='168890'>The</span> <span m='169309'>first</span> <span m='169728'>specifies</span>\
  \ <span m='170147'>an</span> <span m='170566'>opcode,</span> <span m='170985'>two</span>\
  \ <span m='171405'>source</span> <span m='171824'>registers</span> <span m='172243'>and</span>\
  \ <span m='172662'>a</span> <span m='173081'>destination</span> <span m='173500'>register.</span>\
  \ </p><p><span m='173920'>The</span> <span m='174360'>second</span> <span m='174801'>replaces</span>\
  \ <span m='175242'>the</span> <span m='175682'>second</span> <span m='176123'>source</span>\
  \ <span m='176564'>register</span> <span m='177005'>with</span> <span m='177445'>a</span>\
  \ <span m='177886'>32-bit</span> <span m='178327'>constant,</span> <span m='178767'>derived</span>\
  \ <span m='179208'>by</span> <span m='179649'>sign-extending</span> <span m='180090'>a</span>\
  \ <span m='180608'>16-bit</span> <span m='181127'>constant</span> <span m='181645'>stored</span>\
  \ <span m='182164'>in</span> <span m='182683'>the</span> <span m='183201'>instruction</span>\
  \ <span m='183720'>itself.</span> </p><p><span m='184239'>There</span> <span m='184587'>are</span>\
  \ <span m='184936'>three</span> <span m='185284'>classes</span> <span m='185633'>of</span>\
  \ <span m='185982'>instructions:</span> <span m='186330'>ALU</span> <span m='186679'>operations,</span>\
  \ <span m='187028'>LD</span> <span m='187376'>and</span> <span m='187725'>ST</span>\
  \ <span m='188074'>for</span> <span m='188422'>accessing</span> <span m='188771'>main</span>\
  \ <span m='189120'>memory,</span> <span m='189549'>and</span> <span m='189978'>branches</span>\
  \ <span m='190407'>and</span> <span m='190836'>JMPs</span> <span m='191265'>that</span>\
  \ <span m='191694'>change</span> <span m='192123'>the</span> <span m='192552'>order</span>\
  \ <span m='192981'>of</span> <span m='193410'>execution.</span> </p><p><span m='193840'>And</span>\
  \ <span m='194259'>that's</span> <span m='194679'>it!</span> </p><p><span m='195099'>As</span>\
  \ <span m='195393'>we'll</span> <span m='195687'>see</span> <span m='195981'>in</span>\
  \ <span m='196275'>the</span> <span m='196569'>next</span> <span m='196863'>lecture,</span>\
  \ <span m='197157'>we'll</span> <span m='197451'>be</span> <span m='197745'>able</span>\
  \ <span m='198039'>parlay</span> <span m='198333'>this</span> <span m='198627'>relatively</span>\
  \ <span m='198921'>simple</span> <span m='199215'>repertoire</span> <span m='199510'>of</span>\
  \ <span m='199871'>operations</span> <span m='200232'>into</span> <span m='200594'>a</span>\
  \ <span m='200955'>system</span> <span m='201317'>that</span> <span m='201678'>can</span>\
  \ <span m='202040'>execute</span> <span m='202401'>any</span> <span m='202763'>computation</span>\
  \ <span m='203124'>we</span> <span m='203486'>can</span> <span m='203847'>specify.</span>\
  \ </p>"
type: course
uid: e31fa8344a997f1511d38dfa12c2327b

---
None