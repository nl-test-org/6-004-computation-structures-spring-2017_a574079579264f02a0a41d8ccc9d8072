---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: RFu2N_6lkmw
  parent_uid: d7e387fb0a448c6c66993258266da25e
  title: Video-YouTube-Stream
  type: Video
  uid: efe99caeebda44b62b4e29a78faa6684
- id: 3Play-3Play YouTube id-Stream
  media_location: RFu2N_6lkmw
  parent_uid: d7e387fb0a448c6c66993258266da25e
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: ac5eba2e22db7f4bd81184f4a13cde6a
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/RFu2N_6lkmw/default.jpg
  parent_uid: d7e387fb0a448c6c66993258266da25e
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 720e7c3058f402c90dd0aa6594cc0745
- id: RFu2N_6lkmw.srt
  parent_uid: d7e387fb0a448c6c66993258266da25e
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v3/load-and-store-4-34-/RFu2N_6lkmw.srt
  title: 3play caption file
  type: null
  uid: 3a9f4a8a7bc711ae06fc193ae694be08
- id: RFu2N_6lkmw.pdf
  parent_uid: d7e387fb0a448c6c66993258266da25e
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v3/load-and-store-4-34-/RFu2N_6lkmw.pdf
  title: 3play pdf file
  type: null
  uid: 8db7be4db524908f16ad08250a0ac3c6
- id: Caption-3Play YouTube id-SRT
  parent_uid: d7e387fb0a448c6c66993258266da25e
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: fa2216a8238f30bf66ecc7a41cef1d6c
- id: Transcript-3Play YouTube id-PDF
  parent_uid: d7e387fb0a448c6c66993258266da25e
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 744305843d06cada7f0812beeda8821b
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_13-02-03_300k.mp4
  parent_uid: d7e387fb0a448c6c66993258266da25e
  title: Video-Internet Archive-MP4
  type: Video
  uid: 7db32a61eea49a55487d8ff15315c3a9
inline_embed_id: 57738878loadandstore43412425539
layout: video
order_index: null
parent_uid: 9119ba2daa1e42d9eb6b0a9cf4bb22fc
related_resources_text: ''
short_url: load-and-store-4-34-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v3/load-and-store-4-34-
template_type: Embed
title: Load and Store (4:34)
transcript: <p><span m='410'>The</span> <span m='827'>LD</span> <span m='1245'>and</span>
  <span m='1662'>ST</span> <span m='2080'>instructions</span> <span m='2497'>access</span>
  <span m='2915'>main</span> <span m='3332'>memory.</span> </p><p><span m='3750'>Note</span>
  <span m='4085'>that</span> <span m='4420'>its</span> <span m='4756'>the</span> <span
  m='5091'>same</span> <span m='5426'>main</span> <span m='5762'>memory</span> <span
  m='6097'>that</span> <span m='6432'>holds</span> <span m='6768'>the</span> <span
  m='7103'>instructions,</span> <span m='7438'>even</span> <span m='7774'>though</span>
  <span m='8109'>for</span> <span m='8444'>drafting</span> <span m='8780'>convenience</span>
  <span m='9242'>we</span> <span m='9705'>show</span> <span m='10167'>it</span> <span
  m='10630'>has</span> <span m='11092'>two</span> <span m='11555'>separate</span>
  <span m='12017'>boxes</span> <span m='12480'>in</span> <span m='12942'>our</span>
  <span m='13405'>datapath</span> <span m='13867'>diagram.</span> </p><p><span m='14330'>In</span>
  <span m='14649'>the</span> <span m='14968'>form</span> <span m='15287'>we</span>
  <span m='15606'>show</span> <span m='15925'>it</span> <span m='16245'>here,</span>
  <span m='16564'>main</span> <span m='16883'>memory</span> <span m='17202'>has</span>
  <span m='17521'>three</span> <span m='17840'>ports:</span> <span m='18160'>two</span>
  <span m='18498'>read</span> <span m='18836'>ports</span> <span m='19174'>for</span>
  <span m='19512'>fetching</span> <span m='19850'>instructions</span> <span m='20188'>and</span>
  <span m='20526'>reading</span> <span m='20864'>load</span> <span m='21202'>data,</span>
  <span m='21540'>and</span> <span m='21878'>one</span> <span m='22216'>write</span>
  <span m='22554'>port</span> <span m='22892'>used</span> <span m='23230'>by</span>
  <span m='23674'>the</span> <span m='24119'>ST</span> <span m='24564'>instruction</span>
  <span m='25009'>to</span> <span m='25454'>write</span> <span m='25899'>data</span>
  <span m='26344'>into</span> <span m='26789'>main</span> <span m='27234'>memory.</span>
  </p><p><span m='27679'>The</span> <span m='28101'>address</span> <span m='28523'>calculation</span>
  <span m='28945'>is</span> <span m='29367'>exactly</span> <span m='29790'>the</span>
  <span m='30212'>same</span> <span m='30634'>computation</span> <span m='31056'>as</span>
  <span m='31478'>performed</span> <span m='31901'>by</span> <span m='32323'>the</span>
  <span m='32745'>ADDC</span> <span m='33167'>instruction:</span> <span m='33590'>the</span>
  <span m='33955'>contents</span> <span m='34320'>of</span> <span m='34686'>the</span>
  <span m='35051'>RA</span> <span m='35416'>register</span> <span m='35782'>are</span>
  <span m='36147'>added</span> <span m='36512'>to</span> <span m='36878'>the</span>
  <span m='37243'>sign-extended</span> <span m='37608'>16-bit</span> <span m='37974'>literal</span>
  <span m='38339'>from</span> <span m='38704'>the</span> <span m='39070'>low-order</span>
  <span m='39628'>16</span> <span m='40186'>bits</span> <span m='40745'>of</span>
  <span m='41303'>the</span> <span m='41861'>instruction.</span> </p><p><span m='42420'>So</span>
  <span m='42950'>we'll</span> <span m='43480'>simply</span> <span m='44010'>reuse</span>
  <span m='44540'>the</span> <span m='45070'>existing</span> <span m='45600'>datapath</span>
  <span m='46130'>hardware</span> <span m='46660'>to</span> <span m='47190'>compute</span>
  <span m='47720'>the</span> <span m='48250'>address.</span> </p><p><span m='48780'>For</span>
  <span m='49057'>the</span> <span m='49335'>LD</span> <span m='49613'>instruction</span>
  <span m='49891'>the</span> <span m='50168'>output</span> <span m='50446'>of</span>
  <span m='50724'>the</span> <span m='51002'>ALU</span> <span m='51280'>is</span>
  <span m='51557'>routed</span> <span m='51835'>to</span> <span m='52113'>main</span>
  <span m='52391'>memory</span> <span m='52668'>as</span> <span m='52946'>the</span>
  <span m='53224'>address</span> <span m='53502'>of</span> <span m='53780'>the</span>
  <span m='54345'>location</span> <span m='54910'>we</span> <span m='55475'>wish</span>
  <span m='56040'>to</span> <span m='56605'>access.</span> </p><p><span m='57170'>After</span>
  <span m='57525'>the</span> <span m='57880'>memory's</span> <span m='58235'>propagation</span>
  <span m='58591'>delay,</span> <span m='58946'>the</span> <span m='59301'>contents</span>
  <span m='59657'>of</span> <span m='60012'>the</span> <span m='60367'>addressed</span>
  <span m='60723'>location</span> <span m='61078'>is</span> <span m='61433'>returned</span>
  <span m='61789'>by</span> <span m='62063'>the</span> <span m='62337'>memory</span>
  <span m='62611'>and</span> <span m='62886'>we</span> <span m='63160'>need</span>
  <span m='63434'>to</span> <span m='63708'>route</span> <span m='63983'>that</span>
  <span m='64257'>back</span> <span m='64531'>to</span> <span m='64805'>the</span>
  <span m='65080'>register</span> <span m='65354'>file</span> <span m='65628'>to</span>
  <span m='65902'>be</span> <span m='66177'>written</span> <span m='66451'>into</span>
  <span m='66725'>the</span> <span m='67000'>RC</span> <span m='68380'>register.</span>
  </p><p><span m='69760'>The</span> <span m='70131'>memory</span> <span m='70502'>has</span>
  <span m='70873'>two</span> <span m='71244'>control</span> <span m='71615'>signals:</span>
  <span m='71987'>MOE</span> <span m='72358'>(memory</span> <span m='72729'>output</span>
  <span m='73100'>enable),</span> <span m='73471'>which</span> <span m='73842'>we</span>
  <span m='74214'>set</span> <span m='74585'>to</span> <span m='74956'>1</span> <span
  m='75327'>when</span> <span m='75698'>we</span> <span m='76070'>want</span> <span
  m='76377'>to</span> <span m='76685'>read</span> <span m='76992'>a</span> <span m='77300'>value</span>
  <span m='77607'>from</span> <span m='77915'>the</span> <span m='78222'>memory.</span>
  </p><p><span m='78530'>And</span> <span m='78881'>MWE</span> <span m='79232'>(memory</span>
  <span m='79583'>write</span> <span m='79934'>enable)</span> <span m='80285'>which</span>
  <span m='80636'>is</span> <span m='80987'>set</span> <span m='81338'>to</span> <span
  m='81690'>1</span> <span m='82041'>when</span> <span m='82392'>we</span> <span m='82743'>want</span>
  <span m='83094'>main</span> <span m='83445'>memory</span> <span m='83796'>to</span>
  <span m='84147'>store</span> <span m='84498'>the</span> <span m='84850'>value</span>
  <span m='85415'>on</span> <span m='85980'>its</span> <span m='86545'>write</span>
  <span m='87110'>data</span> <span m='87675'>(WD)</span> <span m='88240'>port</span>
  <span m='88805'>into</span> <span m='89370'>the</span> <span m='89935'>addressed</span>
  <span m='90500'>memory</span> <span m='91065'>location.</span> </p><p><span m='91630'>We</span>
  <span m='91930'>need</span> <span m='92231'>to</span> <span m='92531'>add</span>
  <span m='92832'>another</span> <span m='93132'>MUX</span> <span m='93433'>to</span>
  <span m='93734'>select</span> <span m='94034'>which</span> <span m='94335'>value</span>
  <span m='94635'>to</span> <span m='94936'>write</span> <span m='95237'>back</span>
  <span m='95537'>to</span> <span m='95838'>the</span> <span m='96138'>register</span>
  <span m='96439'>file:</span> <span m='96740'>the</span> <span m='97095'>output</span>
  <span m='97450'>of</span> <span m='97805'>the</span> <span m='98160'>ALU</span>
  <span m='98515'>or</span> <span m='98870'>the</span> <span m='99225'>data</span>
  <span m='99580'>returning</span> <span m='99935'>from</span> <span m='100290'>main</span>
  <span m='100645'>memory.</span> </p><p><span m='101000'>We've</span> <span m='101227'>used</span>
  <span m='101455'>a</span> <span m='101683'>3-to-1</span> <span m='101911'>MUX</span>
  <span m='102139'>and</span> <span m='102367'>we'll</span> <span m='102595'>see</span>
  <span m='102823'>the</span> <span m='103051'>use</span> <span m='103278'>for</span>
  <span m='103506'>the</span> <span m='103734'>other</span> <span m='103962'>MUX</span>
  <span m='104190'>input</span> <span m='104418'>when</span> <span m='104646'>we</span>
  <span m='104874'>get</span> <span m='105102'>to</span> <span m='105330'>the</span>
  <span m='105921'>implementation</span> <span m='106513'>of</span> <span m='107105'>branches</span>
  <span m='107696'>and</span> <span m='108288'>jumps.</span> </p><p><span m='108880'>The</span>
  <span m='109323'>two-bit</span> <span m='109767'>WDSEL</span> <span m='110210'>signal</span>
  <span m='110654'>is</span> <span m='111097'>used</span> <span m='111541'>to</span>
  <span m='111985'>select</span> <span m='112428'>the</span> <span m='112872'>source</span>
  <span m='113315'>of</span> <span m='113759'>the</span> <span m='114202'>write-back</span>
  <span m='114646'>value.</span> </p><p><span m='115090'>Let's</span> <span m='115478'>follow</span>
  <span m='115866'>the</span> <span m='116254'>flow</span> <span m='116642'>of</span>
  <span m='117030'>data</span> <span m='117419'>when</span> <span m='117807'>executing</span>
  <span m='118195'>the</span> <span m='118583'>LD</span> <span m='118971'>instruction.</span>
  </p><p><span m='119360'>The</span> <span m='119718'>ALU</span> <span m='120076'>operands</span>
  <span m='120435'>are</span> <span m='120793'>chosen</span> <span m='121151'>just</span>
  <span m='121510'>as</span> <span m='121868'>they</span> <span m='122226'>are</span>
  <span m='122585'>for</span> <span m='122943'>the</span> <span m='123301'>ADDC</span>
  <span m='123660'>instruction</span> <span m='124018'>and</span> <span m='124376'>the</span>
  <span m='124735'>ALU</span> <span m='125093'>is</span> <span m='125451'>requested</span>
  <span m='125810'>to</span> <span m='126327'>perform</span> <span m='126845'>an</span>
  <span m='127363'>ADD</span> <span m='127881'>operation.</span> </p><p><span m='128399'>The</span>
  <span m='128754'>ALU</span> <span m='129109'>result</span> <span m='129465'>is</span>
  <span m='129820'>connected</span> <span m='130176'>to</span> <span m='130531'>the</span>
  <span m='130886'>address</span> <span m='131242'>port</span> <span m='131597'>of</span>
  <span m='131953'>main</span> <span m='132308'>memory,</span> <span m='132663'>who's</span>
  <span m='133019'>control</span> <span m='133374'>signals</span> <span m='133730'>are</span>
  <span m='134160'>set</span> <span m='134590'>for</span> <span m='135020'>a</span>
  <span m='135450'>read</span> <span m='135880'>operation.</span> </p><p><span m='136310'>The</span>
  <span m='136723'>WDSEL</span> <span m='137137'>control</span> <span m='137550'>signals</span>
  <span m='137964'>are</span> <span m='138377'>set</span> <span m='138791'>to</span>
  <span m='139204'>2</span> <span m='139618'>to</span> <span m='140031'>route</span>
  <span m='140445'>the</span> <span m='140858'>returning</span> <span m='141272'>data</span>
  <span m='141685'>to</span> <span m='142099'>the</span> <span m='142512'>register</span>
  <span m='142926'>file.</span> </p><p><span m='143340'>Execution</span> <span m='143615'>of</span>
  <span m='143891'>the</span> <span m='144166'>ST</span> <span m='144442'>instruction</span>
  <span m='144718'>is</span> <span m='144993'>very</span> <span m='145269'>similar</span>
  <span m='145545'>to</span> <span m='145820'>the</span> <span m='146096'>execution</span>
  <span m='146371'>of</span> <span m='146647'>the</span> <span m='146923'>LD</span>
  <span m='147198'>instruction,</span> <span m='147474'>with</span> <span m='147750'>one</span>
  <span m='148660'>extra</span> <span m='149570'>complication.</span> </p><p><span
  m='150480'>The</span> <span m='150790'>value</span> <span m='151101'>to</span> <span
  m='151411'>be</span> <span m='151722'>written</span> <span m='152032'>to</span>
  <span m='152343'>memory</span> <span m='152654'>comes</span> <span m='152964'>from</span>
  <span m='153275'>the</span> <span m='153585'>RC</span> <span m='153896'>register,</span>
  <span m='154207'>but</span> <span m='154517'>the</span> <span m='154828'>RC</span>
  <span m='155138'>instruction</span> <span m='155449'>field</span> <span m='155760'>is</span>
  <span m='156262'>not</span> <span m='156765'>connected</span> <span m='157267'>a</span>
  <span m='157770'>register</span> <span m='158272'>file</span> <span m='158775'>read</span>
  <span m='159277'>address.</span> </p><p><span m='159780'>Happily,</span> <span m='160145'>the</span>
  <span m='160510'>RB</span> <span m='160876'>register</span> <span m='161241'>address</span>
  <span m='161606'>isn't</span> <span m='161972'>being</span> <span m='162337'>used</span>
  <span m='162702'>by</span> <span m='163068'>the</span> <span m='163433'>ST</span>
  <span m='163798'>instruction</span> <span m='164164'>since</span> <span m='164529'>the</span>
  <span m='164894'>second</span> <span m='165260'>ALU</span> <span m='165707'>operand</span>
  <span m='166154'>comes</span> <span m='166601'>from</span> <span m='167048'>the</span>
  <span m='167495'>literal</span> <span m='167942'>field.</span> </p><p><span m='168390'>So</span>
  <span m='168707'>we'll</span> <span m='169024'>use</span> <span m='169342'>a</span>
  <span m='169659'>MUX</span> <span m='169976'>to</span> <span m='170294'>enable</span>
  <span m='170611'>the</span> <span m='170928'>RC</span> <span m='171246'>field</span>
  <span m='171563'>to</span> <span m='171881'>be</span> <span m='172198'>selected</span>
  <span m='172515'>as</span> <span m='172833'>the</span> <span m='173150'>address</span>
  <span m='173467'>for</span> <span m='173785'>the</span> <span m='174102'>register</span>
  <span m='174420'>file's</span> <span m='174897'>second</span> <span m='175374'>read</span>
  <span m='175851'>port.</span> </p><p><span m='176329'>When</span> <span m='176711'>the</span>
  <span m='177094'>RA2SEL</span> <span m='177477'>control</span> <span m='177859'>signal</span>
  <span m='178242'>is</span> <span m='178625'>0,</span> <span m='179007'>the</span>
  <span m='179390'>RB</span> <span m='179773'>field</span> <span m='180155'>is</span>
  <span m='180538'>selected</span> <span m='180921'>as</span> <span m='181303'>the</span>
  <span m='181686'>address.</span> </p><p><span m='182069'>When</span> <span m='182618'>RA2SEL</span>
  <span m='183167'>is</span> <span m='183716'>1,</span> <span m='184265'>the</span>
  <span m='184814'>RC</span> <span m='185363'>field</span> <span m='185912'>is</span>
  <span m='186461'>selected.</span> </p><p><span m='187010'>The</span> <span m='187263'>output</span>
  <span m='187517'>from</span> <span m='187770'>the</span> <span m='188024'>second</span>
  <span m='188277'>read</span> <span m='188531'>data</span> <span m='188784'>port</span>
  <span m='189038'>is</span> <span m='189291'>connected</span> <span m='189545'>to</span>
  <span m='189798'>the</span> <span m='190052'>write</span> <span m='190305'>data</span>
  <span m='190559'>port</span> <span m='190812'>of</span> <span m='191066'>main</span>
  <span m='191320'>memory.</span> </p><p><span m='193510'>The</span> <span m='193810'>ST</span>
  <span m='194111'>instruction</span> <span m='194411'>is</span> <span m='194712'>the</span>
  <span m='195013'>only</span> <span m='195313'>instruction</span> <span m='195614'>that</span>
  <span m='195915'>does</span> <span m='196215'>not</span> <span m='196516'>write</span>
  <span m='196816'>a</span> <span m='197117'>result</span> <span m='197418'>into</span>
  <span m='197718'>the</span> <span m='198019'>register</span> <span m='198320'>file.</span>
  </p><p><span m='199480'>So</span> <span m='199957'>the</span> <span m='200434'>WERF</span>
  <span m='200911'>control</span> <span m='201389'>signal</span> <span m='201866'>will</span>
  <span m='202343'>be</span> <span m='202820'>0</span> <span m='203298'>when</span>
  <span m='203775'>executing</span> <span m='204252'>ST.</span> </p><p><span m='204730'>Here's</span>
  <span m='205102'>the</span> <span m='205475'>flow</span> <span m='205847'>of</span>
  <span m='206220'>data</span> <span m='206592'>when</span> <span m='206965'>executing</span>
  <span m='207337'>ST.</span> </p><p><span m='207710'>The</span> <span m='208064'>operands</span>
  <span m='208419'>are</span> <span m='208774'>selected</span> <span m='209128'>as</span>
  <span m='209483'>for</span> <span m='209838'>LD</span> <span m='210192'>and</span>
  <span m='210547'>the</span> <span m='210902'>ALU</span> <span m='211256'>performs</span>
  <span m='211611'>the</span> <span m='211966'>address</span> <span m='212320'>computation</span>
  <span m='212675'>with</span> <span m='213030'>the</span> <span m='213468'>result</span>
  <span m='213907'>sent</span> <span m='214346'>to</span> <span m='214785'>main</span>
  <span m='215224'>memory</span> <span m='215663'>as</span> <span m='216102'>the</span>
  <span m='216541'>address.</span> </p><p><span m='216980'>Meanwhile</span> <span
  m='217302'>the</span> <span m='217624'>RC</span> <span m='217946'>field</span> <span
  m='218268'>is</span> <span m='218590'>selected</span> <span m='218912'>as</span>
  <span m='219234'>the</span> <span m='219556'>address</span> <span m='219878'>for</span>
  <span m='220200'>the</span> <span m='220522'>second</span> <span m='220844'>register</span>
  <span m='221166'>file</span> <span m='221488'>read</span> <span m='221810'>port</span>
  <span m='222225'>and</span> <span m='222640'>the</span> <span m='223056'>value</span>
  <span m='223471'>from</span> <span m='223886'>the</span> <span m='224302'>RC</span>
  <span m='224717'>register</span> <span m='225132'>becomes</span> <span m='225548'>the</span>
  <span m='225963'>write</span> <span m='226378'>data</span> <span m='226794'>for</span>
  <span m='227209'>main</span> <span m='227624'>memory.</span> </p><p><span m='228040'>By</span>
  <span m='228351'>setting</span> <span m='228662'>the</span> <span m='228973'>MWR</span>
  <span m='229284'>control</span> <span m='229595'>signal</span> <span m='229906'>to</span>
  <span m='230217'>1,</span> <span m='230528'>the</span> <span m='230840'>main</span>
  <span m='231151'>memory</span> <span m='231462'>will</span> <span m='231773'>write</span>
  <span m='232084'>the</span> <span m='232395'>WD</span> <span m='232706'>data</span>
  <span m='233017'>into</span> <span m='233328'>the</span> <span m='233640'>selected</span>
  <span m='234141'>memory</span> <span m='234642'>location</span> <span m='235143'>at</span>
  <span m='235644'>the</span> <span m='236145'>end</span> <span m='236646'>of</span>
  <span m='237147'>the</span> <span m='237648'>cycle.</span> </p><p><span m='238150'>The</span>
  <span m='238399'>WERF</span> <span m='238648'>control</span> <span m='238898'>signal</span>
  <span m='239147'>is</span> <span m='239397'>set</span> <span m='239646'>to</span>
  <span m='239896'>zero</span> <span m='240145'>since</span> <span m='240395'>we</span>
  <span m='240644'>won't</span> <span m='240893'>be</span> <span m='241143'>writing</span>
  <span m='241392'>a</span> <span m='241642'>value</span> <span m='241891'>into</span>
  <span m='242141'>the</span> <span m='242390'>register</span> <span m='242640'>file.</span>
  </p><p><span m='243640'>And,</span> <span m='243872'>since</span> <span m='244104'>we're</span>
  <span m='244337'>not</span> <span m='244569'>writing</span> <span m='244801'>to</span>
  <span m='245034'>the</span> <span m='245266'>register</span> <span m='245498'>file,</span>
  <span m='245731'>we</span> <span m='245963'>don't</span> <span m='246195'>care</span>
  <span m='246428'>about</span> <span m='246660'>the</span> <span m='246892'>value</span>
  <span m='247125'>for</span> <span m='247357'>the</span> <span m='247590'>WDSEL</span>
  <span m='248330'>signal.</span> </p><p><span m='249070'>Of</span> <span m='249400'>course,</span>
  <span m='249730'>the</span> <span m='250060'>logic</span> <span m='250390'>will</span>
  <span m='250720'>need</span> <span m='251050'>to</span> <span m='251380'>supply</span>
  <span m='251710'>some</span> <span m='252040'>value</span> <span m='252370'>for</span>
  <span m='252700'>WDSEL.</span> </p><p><span m='253030'>The</span> <span m='253404'>"don't</span>
  <span m='253778'>care"</span> <span m='254152'>annotation</span> <span m='254526'>is</span>
  <span m='254901'>telling</span> <span m='255275'>the</span> <span m='255649'>logic</span>
  <span m='256023'>designer</span> <span m='256397'>that</span> <span m='256772'>she's</span>
  <span m='257146'>welcome</span> <span m='257520'>to</span> <span m='257894'>supply</span>
  <span m='258269'>whatever</span> <span m='258879'>value</span> <span m='259489'>is</span>
  <span m='260099'>most</span> <span m='260709'>convenient.</span> </p><p><span m='261320'>This</span>
  <span m='261680'>is</span> <span m='262041'>particularly</span> <span m='262402'>useful</span>
  <span m='262762'>when</span> <span m='263123'>using</span> <span m='263484'>Karnaugh</span>
  <span m='263845'>maps</span> <span m='264205'>to</span> <span m='264566'>optimize</span>
  <span m='264927'>the</span> <span m='265287'>control</span> <span m='265648'>logic,</span>
  <span m='266009'>where</span> <span m='266370'>the</span> <span m='266740'>value</span>
  <span m='267110'>can</span> <span m='267480'>be</span> <span m='267850'>chosen</span>
  <span m='268220'>as</span> <span m='268590'>either</span> <span m='268960'>0</span>
  <span m='269330'>or</span> <span m='269700'>1,</span> <span m='270070'>whichever</span>
  <span m='270440'>results</span> <span m='270810'>in</span> <span m='271180'>the</span>
  <span m='271550'>best</span> <span m='271920'>minimization</span> <span m='272290'>of</span>
  <span m='272590'>the</span> <span m='272890'>logic</span> <span m='273190'>equations.</span>
  </p>
type: course
uid: d7e387fb0a448c6c66993258266da25e

---
None