---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 185WS_ZzobA
  parent_uid: eedc53b8b601a077105646ab1d74fc0f
  title: Video-YouTube-Stream
  type: Video
  uid: 788191afd29e0b37a8640c6d51898229
- id: 3Play-3Play YouTube id-Stream
  media_location: 185WS_ZzobA
  parent_uid: eedc53b8b601a077105646ab1d74fc0f
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 40c55eb27e77728d8f951fcf8ca1fdb2
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/185WS_ZzobA/default.jpg
  parent_uid: eedc53b8b601a077105646ab1d74fc0f
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 0ab9fac6d3b4aabae5b46ef7a75a00b8
- id: 185WS_ZzobA.srt
  parent_uid: eedc53b8b601a077105646ab1d74fc0f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v6/constant-operands-5-29-/185WS_ZzobA.srt
  title: 3play caption file
  type: null
  uid: 7b0102a0308cba6b032c559c8f4cae91
- id: 185WS_ZzobA.pdf
  parent_uid: eedc53b8b601a077105646ab1d74fc0f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v6/constant-operands-5-29-/185WS_ZzobA.pdf
  title: 3play pdf file
  type: null
  uid: 11c1c6e656b35cceef0a9fa91ca1e2e9
- id: Caption-3Play YouTube id-SRT
  parent_uid: eedc53b8b601a077105646ab1d74fc0f
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 9280023c93049e74ee5f5cb1c3533bab
- id: Transcript-3Play YouTube id-PDF
  parent_uid: eedc53b8b601a077105646ab1d74fc0f
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 40da5b0146e2fa26b70500c35491c939
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_09-02-06_300k.mp4
  parent_uid: eedc53b8b601a077105646ab1d74fc0f
  title: Video-Internet Archive-MP4
  type: Video
  uid: f22588a34f99b38c5a3f3a204c5f36c0
inline_embed_id: 22590821constantoperands52972107173
layout: video
order_index: null
parent_uid: 661796f88e75fe3b7f278ec766de9a4e
related_resources_text: ''
short_url: constant-operands-5-29-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v6/constant-operands-5-29-
template_type: Embed
title: Constant Operands (5:29)
transcript: <p><span m='1300'>ISA</span> <span m='1680'>designers</span> <span m='2061'>receive</span>
  <span m='2442'>many</span> <span m='2822'>requests</span> <span m='3203'>for</span>
  <span m='3584'>what</span> <span m='3965'>are</span> <span m='4345'>affectionately</span>
  <span m='4726'>known</span> <span m='5107'>as</span> <span m='5487'>"features"</span>
  <span m='5868'>-</span> <span m='6249'>additional</span> <span m='6630'>instructions</span>
  <span m='6985'>that,</span> <span m='7340'>in</span> <span m='7695'>theory,</span>
  <span m='8050'>will</span> <span m='8405'>make</span> <span m='8760'>the</span>
  <span m='9115'>ISA</span> <span m='9470'>better</span> <span m='9825'>in</span>
  <span m='10180'>some</span> <span m='10535'>way.</span> </p><p><span m='10890'>Dealing</span>
  <span m='11203'>with</span> <span m='11517'>such</span> <span m='11831'>requests</span>
  <span m='12145'>is</span> <span m='12459'>the</span> <span m='12773'>moment</span>
  <span m='13087'>to</span> <span m='13401'>apply</span> <span m='13715'>our</span>
  <span m='14029'>quantitive</span> <span m='14343'>approach</span> <span m='14657'>in</span>
  <span m='14971'>order</span> <span m='15285'>to</span> <span m='15599'>be</span>
  <span m='16114'>able</span> <span m='16629'>to</span> <span m='17144'>judge</span>
  <span m='17659'>the</span> <span m='18174'>tradeoffs</span> <span m='18689'>between</span>
  <span m='19204'>cost</span> <span m='19719'>and</span> <span m='20234'>benefits.</span>
  </p><p><span m='20749'>Our</span> <span m='21170'>first</span> <span m='21591'>"feature</span>
  <span m='22012'>request"</span> <span m='22434'>is</span> <span m='22855'>to</span>
  <span m='23276'>allow</span> <span m='23697'>small</span> <span m='24119'>constants</span>
  <span m='24540'>as</span> <span m='24961'>the</span> <span m='25382'>second</span>
  <span m='25804'>operand</span> <span m='26225'>in</span> <span m='26646'>ALU</span>
  <span m='27067'>instructions.</span> </p><p><span m='27489'>So</span> <span m='27762'>if</span>
  <span m='28036'>we</span> <span m='28309'>replaced</span> <span m='28583'>the</span>
  <span m='28856'>5-bit</span> <span m='29130'>"rb"</span> <span m='29404'>field,</span>
  <span m='29677'>we</span> <span m='29951'>would</span> <span m='30224'>have</span>
  <span m='30498'>room</span> <span m='30772'>in</span> <span m='31045'>the</span>
  <span m='31319'>instruction</span> <span m='31592'>to</span> <span m='31866'>include</span>
  <span m='32140'>a</span> <span m='32778'>16-bit</span> <span m='33417'>constant</span>
  <span m='34056'>as</span> <span m='34695'>bits</span> <span m='35334'>[15:0]</span>
  <span m='35973'>of</span> <span m='36612'>the</span> <span m='37251'>instruction.</span>
  </p><p><span m='37890'>The</span> <span m='38192'>argument</span> <span m='38494'>in</span>
  <span m='38796'>favor</span> <span m='39098'>of</span> <span m='39400'>this</span>
  <span m='39702'>request</span> <span m='40004'>is</span> <span m='40306'>that</span>
  <span m='40608'>small</span> <span m='40910'>constants</span> <span m='41212'>appear</span>
  <span m='41514'>frequently</span> <span m='41816'>in</span> <span m='42118'>many</span>
  <span m='42420'>programs</span> <span m='42753'>and</span> <span m='43086'>it</span>
  <span m='43419'>would</span> <span m='43752'>make</span> <span m='44085'>programs</span>
  <span m='44418'>shorter</span> <span m='44751'>if</span> <span m='45085'>we</span>
  <span m='45418'>didn't</span> <span m='45751'>have</span> <span m='46084'>use</span>
  <span m='46417'>load</span> <span m='46750'>operations</span> <span m='47083'>to</span>
  <span m='47416'>read</span> <span m='47750'>constant</span> <span m='48307'>values</span>
  <span m='48865'>from</span> <span m='49423'>main</span> <span m='49981'>memory.</span>
  </p><p><span m='50539'>The</span> <span m='50815'>argument</span> <span m='51092'>against</span>
  <span m='51368'>the</span> <span m='51645'>request</span> <span m='51921'>is</span>
  <span m='52198'>that</span> <span m='52474'>we</span> <span m='52751'>would</span>
  <span m='53027'>need</span> <span m='53304'>additional</span> <span m='53580'>control</span>
  <span m='53857'>and</span> <span m='54133'>datapath</span> <span m='54410'>logic</span>
  <span m='54779'>to</span> <span m='55148'>implement</span> <span m='55517'>the</span>
  <span m='55886'>feature,</span> <span m='56255'>increasing</span> <span m='56624'>the</span>
  <span m='56993'>hardware</span> <span m='57362'>cost</span> <span m='57731'>and</span>
  <span m='58100'>probably</span> <span m='58469'>decreasing</span> <span m='58839'>the</span>
  <span m='59704'>performance.</span> </p><p><span m='60570'>So</span> <span m='60862'>our</span>
  <span m='61155'>strategy</span> <span m='61447'>is</span> <span m='61740'>to</span>
  <span m='62032'>modify</span> <span m='62325'>our</span> <span m='62617'>benchmark</span>
  <span m='62910'>programs</span> <span m='63202'>to</span> <span m='63495'>use</span>
  <span m='63787'>the</span> <span m='64080'>ISA</span> <span m='64372'>augmented</span>
  <span m='64665'>with</span> <span m='64957'>this</span> <span m='65250'>feature</span>
  <span m='65786'>and</span> <span m='66323'>measure</span> <span m='66860'>the</span>
  <span m='67396'>impact</span> <span m='67933'>on</span> <span m='68470'>a</span>
  <span m='69006'>simulated</span> <span m='69543'>execution.</span> </p><p><span
  m='70080'>Looking</span> <span m='70387'>at</span> <span m='70695'>the</span> <span
  m='71003'>results,</span> <span m='71311'>we</span> <span m='71619'>find</span>
  <span m='71927'>that</span> <span m='72235'>there</span> <span m='72542'>is</span>
  <span m='72850'>compelling</span> <span m='73158'>evidence</span> <span m='73466'>that</span>
  <span m='73774'>small</span> <span m='74082'>constants</span> <span m='74390'>are</span>
  <span m='74875'>indeed</span> <span m='75360'>very</span> <span m='75846'>common</span>
  <span m='76331'>as</span> <span m='76817'>the</span> <span m='77302'>second</span>
  <span m='77788'>operands</span> <span m='78273'>to</span> <span m='78759'>many</span>
  <span m='79244'>operations.</span> </p><p><span m='79730'>Note</span> <span m='79998'>that</span>
  <span m='80266'>we're</span> <span m='80535'>not</span> <span m='80803'>so</span>
  <span m='81072'>much</span> <span m='81340'>interested</span> <span m='81609'>in</span>
  <span m='81877'>simply</span> <span m='82146'>looking</span> <span m='82414'>at</span>
  <span m='82683'>the</span> <span m='82951'>code.</span> </p><p><span m='83220'>Instead</span>
  <span m='83508'>we</span> <span m='83797'>want</span> <span m='84086'>to</span>
  <span m='84374'>look</span> <span m='84663'>at</span> <span m='84952'>what</span>
  <span m='85240'>instructions</span> <span m='85529'>actually</span> <span m='85818'>get</span>
  <span m='86106'>executed</span> <span m='86395'>while</span> <span m='86684'>running</span>
  <span m='86972'>the</span> <span m='87261'>benchmark</span> <span m='87550'>programs.</span>
  </p><p><span m='88550'>This</span> <span m='88885'>will</span> <span m='89220'>take</span>
  <span m='89556'>into</span> <span m='89891'>account</span> <span m='90226'>that</span>
  <span m='90562'>instructions</span> <span m='90897'>executed</span> <span m='91232'>during</span>
  <span m='91568'>each</span> <span m='91903'>iteration</span> <span m='92238'>of</span>
  <span m='92574'>a</span> <span m='92909'>loop</span> <span m='93244'>might</span>
  <span m='93580'>get</span> <span m='94047'>executed</span> <span m='94515'>1000's</span>
  <span m='94983'>of</span> <span m='95451'>times</span> <span m='95919'>even</span>
  <span m='96387'>though</span> <span m='96855'>they</span> <span m='97322'>only</span>
  <span m='97790'>appear</span> <span m='98258'>in</span> <span m='98726'>the</span>
  <span m='99194'>program</span> <span m='99662'>once.</span> </p><p><span m='100130'>Looking</span>
  <span m='100426'>at</span> <span m='100723'>the</span> <span m='101020'>results,</span>
  <span m='101317'>we</span> <span m='101614'>see</span> <span m='101911'>that</span>
  <span m='102208'>over</span> <span m='102505'>half</span> <span m='102801'>of</span>
  <span m='103098'>the</span> <span m='103395'>arithmetic</span> <span m='103692'>instructions</span>
  <span m='103989'>have</span> <span m='104286'>a</span> <span m='104583'>small</span>
  <span m='104880'>constant</span> <span m='105476'>as</span> <span m='106072'>their</span>
  <span m='106668'>second</span> <span m='107264'>operand.</span> </p><p><span m='107860'>Comparisons</span>
  <span m='108278'>involve</span> <span m='108697'>small</span> <span m='109116'>constants</span>
  <span m='109535'>80%</span> <span m='109953'>of</span> <span m='110372'>the</span>
  <span m='110791'>time.</span> </p><p><span m='111210'>This</span> <span m='111546'>probably</span>
  <span m='111883'>reflects</span> <span m='112220'>the</span> <span m='112557'>fact</span>
  <span m='112894'>that</span> <span m='113231'>during</span> <span m='113568'>execution</span>
  <span m='113905'>comparisons</span> <span m='114242'>are</span> <span m='114579'>used</span>
  <span m='114916'>in</span> <span m='115253'>determining</span> <span m='115590'>whether</span>
  <span m='115910'>we've</span> <span m='116230'>reached</span> <span m='116550'>the</span>
  <span m='116870'>end</span> <span m='117190'>of</span> <span m='117510'>a</span>
  <span m='117830'>loop.</span> </p><p><span m='118150'>And</span> <span m='118575'>small</span>
  <span m='119000'>constants</span> <span m='119426'>are</span> <span m='119851'>often</span>
  <span m='120276'>found</span> <span m='120702'>in</span> <span m='121127'>address</span>
  <span m='121552'>calculations</span> <span m='121978'>done</span> <span m='122403'>by</span>
  <span m='122828'>load</span> <span m='123254'>and</span> <span m='123679'>store</span>
  <span m='124104'>operations.</span> </p><p><span m='124530'>Operations</span> <span
  m='124961'>involving</span> <span m='125392'>constant</span> <span m='125824'>operands</span>
  <span m='126255'>are</span> <span m='126687'>clearly</span> <span m='127118'>a</span>
  <span m='127550'>common</span> <span m='127981'>case,</span> <span m='128413'>one</span>
  <span m='128844'>well</span> <span m='129276'>worth</span> <span m='129707'>optimizing.</span>
  </p><p><span m='130139'>Adding</span> <span m='130468'>support</span> <span m='130797'>for</span>
  <span m='131127'>small</span> <span m='131456'>constant</span> <span m='131785'>operands</span>
  <span m='132115'>to</span> <span m='132444'>the</span> <span m='132773'>ISA</span>
  <span m='133103'>resulted</span> <span m='133432'>in</span> <span m='133761'>programs</span>
  <span m='134091'>that</span> <span m='134420'>were</span> <span m='134750'>measurably</span>
  <span m='135355'>smaller</span> <span m='135960'>and</span> <span m='136565'>faster.</span>
  </p><p><span m='137170'>So:</span> <span m='138152'>feature</span> <span m='139135'>request</span>
  <span m='140117'>approved!</span> </p><p><span m='141100'>Here</span> <span m='141440'>we</span>
  <span m='141781'>see</span> <span m='142122'>the</span> <span m='142463'>second</span>
  <span m='142804'>of</span> <span m='143145'>the</span> <span m='143486'>two</span>
  <span m='143827'>Beta</span> <span m='144168'>instruction</span> <span m='144509'>formats.</span>
  </p><p><span m='144850'>It's</span> <span m='145175'>a</span> <span m='145501'>modification</span>
  <span m='145826'>of</span> <span m='146152'>the</span> <span m='146478'>first</span>
  <span m='146803'>format</span> <span m='147129'>where</span> <span m='147455'>we've</span>
  <span m='147780'>replaced</span> <span m='148106'>the</span> <span m='148431'>5-bit</span>
  <span m='148757'>"rb"</span> <span m='149083'>field</span> <span m='149408'>with</span>
  <span m='149734'>a</span> <span m='150060'>16-bit</span> <span m='150533'>field</span>
  <span m='151006'>holding</span> <span m='151479'>a</span> <span m='151952'>constant</span>
  <span m='152426'>in</span> <span m='152899'>two's</span> <span m='153372'>complement</span>
  <span m='153845'>format.</span> </p><p><span m='154319'>This</span> <span m='154820'>will</span>
  <span m='155321'>allow</span> <span m='155822'>us</span> <span m='156324'>to</span>
  <span m='156825'>represent</span> <span m='157326'>constant</span> <span m='157828'>operands</span>
  <span m='158329'>in</span> <span m='158830'>the</span> <span m='159332'>range</span>
  <span m='159833'>of</span> <span m='160334'>0x8000</span> <span m='160836'>(decimal</span>
  <span m='161337'>-32768)</span> <span m='161838'>to</span> <span m='162340'>0x7FFF</span>
  <span m='165186'>(decimal</span> <span m='168033'>32767).</span> </p><p><span m='170880'>Here's</span>
  <span m='171252'>an</span> <span m='171624'>example</span> <span m='171996'>of</span>
  <span m='172368'>the</span> <span m='172740'>add-constant</span> <span m='173112'>(ADDC)</span>
  <span m='173485'>instruction</span> <span m='173857'>which</span> <span m='174229'>adds</span>
  <span m='174601'>the</span> <span m='174973'>contents</span> <span m='175345'>of</span>
  <span m='175717'>R1</span> <span m='176090'>and</span> <span m='176622'>the</span>
  <span m='177154'>constant</span> <span m='177686'>-3,</span> <span m='178218'>writing</span>
  <span m='178751'>the</span> <span m='179283'>result</span> <span m='179815'>into</span>
  <span m='180347'>R3.</span> </p><p><span m='180880'>We</span> <span m='181160'>can</span>
  <span m='181440'>see</span> <span m='181720'>that</span> <span m='182000'>the</span>
  <span m='182280'>second</span> <span m='182560'>operand</span> <span m='182840'>in</span>
  <span m='183120'>the</span> <span m='183400'>symbolic</span> <span m='183680'>representation</span>
  <span m='183960'>is</span> <span m='184240'>now</span> <span m='184520'>a</span>
  <span m='184800'>constant</span> <span m='185080'>(or,</span> <span m='185555'>more</span>
  <span m='186030'>generally,</span> <span m='186506'>an</span> <span m='186981'>expression</span>
  <span m='187456'>that</span> <span m='187932'>can</span> <span m='188407'>evaluated</span>
  <span m='188883'>to</span> <span m='189358'>get</span> <span m='189833'>a</span>
  <span m='190309'>constant</span> <span m='190784'>value).</span> </p><p><span m='191260'>One</span>
  <span m='191732'>technical</span> <span m='192205'>detail</span> <span m='192677'>needs</span>
  <span m='193150'>discussion:</span> <span m='193622'>the</span> <span m='194095'>instruction</span>
  <span m='194567'>contains</span> <span m='195040'>a</span> <span m='195512'>16-bit</span>
  <span m='195985'>constant,</span> <span m='196457'>but</span> <span m='196930'>the</span>
  <span m='197506'>datapath</span> <span m='198083'>requires</span> <span m='198660'>a</span>
  <span m='199236'>32-bit</span> <span m='199813'>operand.</span> </p><p><span m='200390'>How</span>
  <span m='200795'>does</span> <span m='201200'>the</span> <span m='201606'>datapath</span>
  <span m='202011'>hardware</span> <span m='202416'>go</span> <span m='202822'>about</span>
  <span m='203227'>converting</span> <span m='203632'>from,</span> <span m='204038'>say,</span>
  <span m='204443'>the</span> <span m='204848'>16-bit</span> <span m='205254'>representation</span>
  <span m='205659'>of</span> <span m='206064'>-3</span> <span m='206470'>to</span>
  <span m='207218'>the</span> <span m='207966'>32-bit</span> <span m='208714'>representation</span>
  <span m='209462'>of</span> <span m='210210'>-3?</span> </p><p><span m='210959'>Comparing</span>
  <span m='211353'>the</span> <span m='211747'>16-bit</span> <span m='212142'>and</span>
  <span m='212536'>32-bit</span> <span m='212930'>representations</span> <span m='213325'>for</span>
  <span m='213719'>various</span> <span m='214113'>constants,</span> <span m='214508'>we</span>
  <span m='214902'>see</span> <span m='215296'>that</span> <span m='215691'>if</span>
  <span m='216085'>the</span> <span m='216480'>16-bit</span> <span m='216967'>two's-complement</span>
  <span m='217455'>constant</span> <span m='217943'>is</span> <span m='218430'>negative</span>
  <span m='218918'>(i.e.,</span> <span m='219406'>its</span> <span m='219893'>high-order</span>
  <span m='220381'>bit</span> <span m='220869'>is</span> <span m='221356'>1),</span>
  <span m='221844'>the</span> <span m='222332'>high</span> <span m='222820'>sixteen</span>
  <span m='223344'>bits</span> <span m='223868'>of</span> <span m='224392'>the</span>
  <span m='224916'>equivalent</span> <span m='225440'>32-bit</span> <span m='225964'>constant</span>
  <span m='226488'>are</span> <span m='227012'>all</span> <span m='227536'>1's.</span>
  </p><p><span m='228060'>And</span> <span m='228431'>if</span> <span m='228802'>the</span>
  <span m='229174'>16-bit</span> <span m='229545'>constant</span> <span m='229916'>is</span>
  <span m='230288'>non-negative</span> <span m='230659'>(i.e.,</span> <span m='231030'>its</span>
  <span m='231402'>high-order</span> <span m='231773'>bit</span> <span m='232144'>is</span>
  <span m='232516'>0),</span> <span m='232887'>the</span> <span m='233258'>high</span>
  <span m='233630'>sixteen</span> <span m='234064'>bits</span> <span m='234498'>of</span>
  <span m='234933'>the</span> <span m='235367'>32-bit</span> <span m='235802'>constant</span>
  <span m='236236'>are</span> <span m='236671'>all</span> <span m='237105'>0's.</span>
  </p><p><span m='237540'>Thus</span> <span m='237939'>the</span> <span m='238338'>operation</span>
  <span m='238738'>the</span> <span m='239137'>hardware</span> <span m='239536'>needs</span>
  <span m='239936'>to</span> <span m='240335'>perform</span> <span m='240734'>is</span>
  <span m='241134'>"sign</span> <span m='241533'>extension"</span> <span m='241932'>where</span>
  <span m='242332'>the</span> <span m='242731'>sign-bit</span> <span m='243130'>of</span>
  <span m='243530'>the</span> <span m='243913'>16-bit</span> <span m='244296'>constant</span>
  <span m='244680'>is</span> <span m='245063'>replicated</span> <span m='245446'>sixteen</span>
  <span m='245830'>times</span> <span m='246213'>to</span> <span m='246596'>form</span>
  <span m='246980'>the</span> <span m='247363'>high</span> <span m='247746'>half</span>
  <span m='248130'>of</span> <span m='248513'>the</span> <span m='248896'>32-bit</span>
  <span m='249280'>constant.</span> </p><p><span m='250340'>The</span> <span m='250688'>low</span>
  <span m='251036'>half</span> <span m='251384'>of</span> <span m='251732'>the</span>
  <span m='252080'>32-bit</span> <span m='252428'>constant</span> <span m='252776'>is</span>
  <span m='253124'>simply</span> <span m='253472'>the</span> <span m='253820'>16-bit</span>
  <span m='254168'>constant</span> <span m='254516'>from</span> <span m='254864'>the</span>
  <span m='255212'>instruction.</span> </p><p><span m='255560'>No</span> <span m='255817'>additional</span>
  <span m='256075'>logic</span> <span m='256332'>gates</span> <span m='256590'>will</span>
  <span m='256848'>be</span> <span m='257105'>needed</span> <span m='257363'>to</span>
  <span m='257621'>implement</span> <span m='257878'>sign</span> <span m='258136'>extension</span>
  <span m='258394'>-</span> <span m='258651'>we</span> <span m='258909'>can</span>
  <span m='259167'>do</span> <span m='259424'>it</span> <span m='259682'>all</span>
  <span m='259940'>with</span> <span m='260830'>wiring.</span> </p><p><span m='261720'>Here</span>
  <span m='262081'>are</span> <span m='262442'>the</span> <span m='262804'>fourteen</span>
  <span m='263165'>ALU</span> <span m='263526'>instructions</span> <span m='263888'>in</span>
  <span m='264249'>their</span> <span m='264610'>"with</span> <span m='264972'>constant"</span>
  <span m='265333'>form,</span> <span m='265694'>showing</span> <span m='266056'>the</span>
  <span m='266417'>same</span> <span m='266779'>instruction</span> <span m='267244'>mnemonics</span>
  <span m='267710'>but</span> <span m='268176'>with</span> <span m='268642'>a</span>
  <span m='269107'>"C"</span> <span m='269573'>suffix</span> <span m='270039'>indicate</span>
  <span m='270505'>the</span> <span m='270971'>second</span> <span m='271436'>operand</span>
  <span m='271902'>is</span> <span m='272368'>a</span> <span m='272834'>constant.</span>
  </p><p><span m='273300'>Since</span> <span m='273723'>these</span> <span m='274147'>are</span>
  <span m='274571'>additional</span> <span m='274994'>instructions,</span> <span m='275418'>these</span>
  <span m='275842'>have</span> <span m='276265'>different</span> <span m='276689'>opcodes</span>
  <span m='277113'>than</span> <span m='277536'>the</span> <span m='277960'>original</span>
  <span m='278384'>ALU</span> <span m='278808'>instructions.</span> </p><p><span m='279808'>Finally,</span>
  <span m='280100'>note</span> <span m='280393'>that</span> <span m='280685'>if</span>
  <span m='280978'>we</span> <span m='281271'>need</span> <span m='281563'>a</span>
  <span m='281856'>constant</span> <span m='282149'>operand</span> <span m='282441'>whose</span>
  <span m='282734'>representation</span> <span m='283026'>does</span> <span m='283319'>NOT</span>
  <span m='283612'>fit</span> <span m='283904'>into</span> <span m='284197'>16</span>
  <span m='284490'>bits,</span> <span m='284770'>then</span> <span m='285051'>we</span>
  <span m='285331'>have</span> <span m='285612'>to</span> <span m='285892'>store</span>
  <span m='286173'>the</span> <span m='286453'>constant</span> <span m='286734'>as</span>
  <span m='287014'>a</span> <span m='287295'>32-bit</span> <span m='287575'>value</span>
  <span m='287856'>in</span> <span m='288136'>a</span> <span m='288417'>main</span>
  <span m='288697'>memory</span> <span m='288978'>location</span> <span m='289258'>and</span>
  <span m='289539'>load</span> <span m='289911'>it</span> <span m='290284'>into</span>
  <span m='290657'>a</span> <span m='291030'>register</span> <span m='291403'>for</span>
  <span m='291776'>use</span> <span m='292149'>just</span> <span m='292521'>like</span>
  <span m='292894'>we</span> <span m='293267'>would</span> <span m='293640'>any</span>
  <span m='294013'>variable</span> <span m='294386'>value.</span> </p><p><span m='294759'>To</span>
  <span m='295030'>give</span> <span m='295301'>some</span> <span m='295573'>sense</span>
  <span m='295844'>for</span> <span m='296116'>the</span> <span m='296387'>additional</span>
  <span m='296658'>datapath</span> <span m='296930'>hardware</span> <span m='297201'>that</span>
  <span m='297473'>will</span> <span m='297744'>be</span> <span m='298015'>needed,</span>
  <span m='298287'>let's</span> <span m='298558'>update</span> <span m='298830'>our</span>
  <span m='299234'>implementation</span> <span m='299639'>sketch</span> <span m='300043'>to</span>
  <span m='300448'>add</span> <span m='300852'>support</span> <span m='301257'>for</span>
  <span m='301661'>constants</span> <span m='302066'>as</span> <span m='302470'>the</span>
  <span m='302875'>second</span> <span m='303279'>ALU</span> <span m='303684'>operand.</span>
  </p><p><span m='304089'>We</span> <span m='304388'>don't</span> <span m='304687'>have</span>
  <span m='304986'>to</span> <span m='305286'>add</span> <span m='305585'>much</span>
  <span m='305884'>hardware:</span> <span m='306184'>just</span> <span m='306483'>a</span>
  <span m='306782'>multiplexer</span> <span m='307081'>which</span> <span m='307381'>selects</span>
  <span m='307680'>either</span> <span m='307979'>the</span> <span m='308279'>"rb"</span>
  <span m='308717'>register</span> <span m='309156'>value</span> <span m='309594'>or</span>
  <span m='310033'>the</span> <span m='310471'>sign-extended</span> <span m='310910'>constant</span>
  <span m='311349'>from</span> <span m='311787'>the</span> <span m='312226'>16-bit</span>
  <span m='312664'>field</span> <span m='313103'>in</span> <span m='313541'>the</span>
  <span m='313980'>instruction.</span> </p><p><span m='314419'>The</span> <span m='314814'>BSEL</span>
  <span m='315209'>control</span> <span m='315605'>signal</span> <span m='316000'>that</span>
  <span m='316396'>controls</span> <span m='316791'>the</span> <span m='317187'>multiplexer</span>
  <span m='317582'>is</span> <span m='317978'>1</span> <span m='318373'>for</span>
  <span m='318769'>the</span> <span m='319164'>ALU-with-constant</span> <span m='319560'>instructions</span>
  <span m='320026'>and</span> <span m='320492'>0</span> <span m='320958'>for</span>
  <span m='321424'>the</span> <span m='321890'>regular</span> <span m='322356'>ALU</span>
  <span m='322822'>instructions.</span> </p><p><span m='323289'>We'll</span> <span
  m='323629'>put</span> <span m='323970'>the</span> <span m='324310'>hardware</span>
  <span m='324651'>implementation</span> <span m='324992'>details</span> <span m='325332'>aside</span>
  <span m='325673'>for</span> <span m='326014'>now</span> <span m='326354'>and</span>
  <span m='326695'>revisit</span> <span m='327035'>them</span> <span m='327376'>in</span>
  <span m='327717'>a</span> <span m='328057'>few</span> <span m='328398'>lectures.</span>
  </p>
type: course
uid: eedc53b8b601a077105646ab1d74fc0f

---
None