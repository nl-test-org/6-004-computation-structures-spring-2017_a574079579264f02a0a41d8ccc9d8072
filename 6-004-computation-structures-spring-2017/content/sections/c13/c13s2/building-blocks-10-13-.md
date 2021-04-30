---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: Um6UH_PRJ4k
  parent_uid: 4103de9aaf941f17da0c74faf56a0390
  title: Video-YouTube-Stream
  type: Video
  uid: 92c8e46b9d2709613ff9ef26312ae3f9
- id: 3Play-3Play YouTube id-Stream
  media_location: Um6UH_PRJ4k
  parent_uid: 4103de9aaf941f17da0c74faf56a0390
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: b072f8833dd2f7b425c04b79a373362a
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/Um6UH_PRJ4k/default.jpg
  parent_uid: 4103de9aaf941f17da0c74faf56a0390
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 05c92e8d620e2350ed047b87fdd9d21e
- id: Um6UH_PRJ4k.srt
  parent_uid: 4103de9aaf941f17da0c74faf56a0390
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/building-blocks-10-13-/Um6UH_PRJ4k.srt
  title: 3play caption file
  type: null
  uid: d1b230af273df9bc42ace412a3d05a46
- id: Um6UH_PRJ4k.pdf
  parent_uid: 4103de9aaf941f17da0c74faf56a0390
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/building-blocks-10-13-/Um6UH_PRJ4k.pdf
  title: 3play pdf file
  type: null
  uid: 145494c2925aa7d158c2c2edf022ea6d
- id: Caption-3Play YouTube id-SRT
  parent_uid: 4103de9aaf941f17da0c74faf56a0390
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 87cef296304eb8e5410fadbd62919b02
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 4103de9aaf941f17da0c74faf56a0390
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: dd7a51ec708a4f0f70b3a447910b52c4
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_13-02-01_300k.mp4
  parent_uid: 4103de9aaf941f17da0c74faf56a0390
  title: Video-Internet Archive-MP4
  type: Video
  uid: cd35032457e7d3b8a651c09d4531d7c3
inline_embed_id: 21621971buildingblocks101361782088
layout: video
order_index: null
parent_uid: 0f5d07f62e947d88a1f1191b8a267539
related_resources_text: ''
short_url: building-blocks-10-13-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/building-blocks-10-13-
template_type: Embed
title: Building Blocks (10:13)
transcript: "<p><span m='270'>Today</span> <span m='900'>we\u2019re</span> <span m='1050'>going</span>\
  \ <span m='1290'>to</span> <span m='1380'>describe</span> <span m='1960'>the</span>\
  \ <span m='2040'>datapath</span> <span m='2750'>and</span> <span m='2900'>control</span>\
  \ <span m='3400'>logic</span> <span m='3770'>needed</span> <span m='4030'>to</span>\
  \ <span m='4150'>execute</span> <span m='4670'>Beta</span> <span m='4960'>instructions.</span>\
  \ </p><p><span m='6380'>In</span> <span m='6450'>an</span> <span m='6620'>upcoming</span>\
  \ <span m='7130'>lab</span> <span m='7410'>assignment,</span> <span m='8039'>we\u2019\
  ll</span> <span m='8340'>ask</span> <span m='8540'>you</span> <span m='8620'>to</span>\
  \ <span m='8730'>build</span> <span m='9050'>a</span> <span m='9150'>working</span>\
  \ <span m='9580'>implementation</span> <span m='10370'>using</span> <span m='10690'>our</span>\
  \ <span m='10820'>standard</span> <span m='11240'>cell</span> <span m='11440'>library.</span>\
  \ </p><p><span m='12560'>When</span> <span m='12720'>you\u2019re</span> <span m='12850'>done,</span>\
  \ <span m='13350'>you\u2019ll</span> <span m='13600'>have</span> <span m='13790'>designed</span>\
  \ <span m='14360'>and</span> <span m='14500'>debugged</span> <span m='15070'>a</span>\
  \ <span m='15410'>32-bit</span> <span m='15940'>reduced-instruction</span> <span\
  \ m='16910'>set</span> <span m='17160'>computer!</span> <span m='17940'>Not</span>\
  \ <span m='18350'>bad\u2026</span> </p><p><span m='20260'>Before</span> <span m='20630'>tackling</span>\
  \ <span m='21220'>a</span> <span m='21270'>design</span> <span m='21710'>task,</span>\
  \ <span m='22180'>it\u2019s</span> <span m='22410'>useful</span> <span m='22830'>to</span>\
  \ <span m='22920'>understand</span> <span m='23550'>the</span> <span m='23630'>goals</span>\
  \ <span m='24050'>for</span> <span m='24180'>the</span> <span m='24270'>design.</span>\
  \ </p><p><span m='25420'>Functionality,</span> <span m='26060'>of</span> <span m='26150'>course;</span>\
  \ <span m='26740'>in</span> <span m='27040'>our</span> <span m='27190'>case</span>\
  \ <span m='27580'>the</span> <span m='27670'>correct</span> <span m='28170'>execution</span>\
  \ <span m='28790'>of</span> <span m='28890'>instructions</span> <span m='29600'>from</span>\
  \ <span m='29770'>the</span> <span m='29870'>Beta</span> <span m='30220'>ISA.</span>\
  \ </p><p><span m='30780'>But</span> <span m='31040'>there</span> <span m='31370'>are</span>\
  \ <span m='31910'>other</span> <span m='32950'>goals</span> <span m='33440'>we</span>\
  \ <span m='33540'>should</span> <span m='33700'>think</span> <span m='33900'>about.</span>\
  \ </p><p><span m='35550'>An</span> <span m='35670'>obvious</span> <span m='36220'>goal</span>\
  \ <span m='36540'>is</span> <span m='36690'>to</span> <span m='36800'>maximize</span>\
  \ <span m='37450'>performance,</span> <span m='38280'>as</span> <span m='38580'>measured</span>\
  \ <span m='38930'>by</span> <span m='39060'>the</span> <span m='39160'>number</span>\
  \ <span m='39520'>of</span> <span m='39610'>instructions</span> <span m='40360'>executed</span>\
  \ <span m='40970'>per</span> <span m='41130'>second.</span> </p><p><span m='42540'>This</span>\
  \ <span m='42690'>is</span> <span m='42820'>usually</span> <span m='43280'>expressed</span>\
  \ <span m='43880'>in</span> <span m='44020'>MIPS,</span> <span m='44640'>an</span>\
  \ <span m='44950'>acronym</span> <span m='45510'>for</span> <span m='45740'>\u201C\
  Millions</span> <span m='46290'>of</span> <span m='46390'>Instructions</span> <span\
  \ m='47060'>Per</span> <span m='47200'>Second\u201D.</span> </p><p><span m='48140'>When</span>\
  \ <span m='48330'>the</span> <span m='48480'>Intel</span> <span m='49140'>8080</span>\
  \ <span m='49500'>was</span> <span m='49830'>introduced</span> <span m='50420'>in</span>\
  \ <span m='50950'>1974,</span> <span m='51530'>it</span> <span m='51960'>executed</span>\
  \ <span m='52540'>instructions</span> <span m='53190'>at</span> <span m='53810'>0.29</span>\
  \ <span m='54390'>MIPS</span> <span m='55200'>or</span> <span m='55650'>290,000</span>\
  \ <span m='55860'>instructions</span> <span m='57330'>per</span> <span m='57680'>second</span>\
  \ <span m='58290'>as</span> <span m='58680'>measured</span> <span m='59060'>by</span>\
  \ <span m='59180'>the</span> <span m='59290'>Dhrystone</span> <span m='59880'>benchmark.</span>\
  \ </p><p><span m='61520'>Modern</span> <span m='62060'>multi-core</span> <span m='62570'>processors</span>\
  \ <span m='63180'>are</span> <span m='63360'>rated</span> <span m='63630'>between</span>\
  \ <span m='64060'>10,000</span> <span m='64150'>and</span> <span m='64760'>100,000</span>\
  \ <span m='65480'>MIPS.</span> </p><p><span m='68290'>Another</span> <span m='68650'>goal</span>\
  \ <span m='68960'>might</span> <span m='69190'>be</span> <span m='69330'>to</span>\
  \ <span m='69400'>minimize</span> <span m='70090'>the</span> <span m='70180'>manufacturing</span>\
  \ <span m='70880'>cost,</span> <span m='71390'>which</span> <span m='71820'>in</span>\
  \ <span m='72000'>integrated</span> <span m='72500'>circuit</span> <span m='72840'>manufacturing</span>\
  \ <span m='73840'>is</span> <span m='74210'>proportional</span> <span m='74830'>to</span>\
  \ <span m='74950'>the</span> <span m='75030'>size</span> <span m='75460'>of</span>\
  \ <span m='75560'>the</span> <span m='75640'>circuit.</span> </p><p><span m='77820'>Or</span>\
  \ <span m='78050'>we</span> <span m='78230'>might</span> <span m='78510'>want</span>\
  \ <span m='78690'>have</span> <span m='78950'>the</span> <span m='79040'>best</span>\
  \ <span m='79410'>performance</span> <span m='79990'>for</span> <span m='80160'>a</span>\
  \ <span m='80190'>given</span> <span m='80480'>price.</span> </p><p><span m='82400'>In</span>\
  \ <span m='82510'>our</span> <span m='82700'>increasingly</span> <span m='83290'>mobile</span>\
  \ <span m='83690'>world,</span> <span m='84060'>the</span> <span m='84220'>best</span>\
  \ <span m='84490'>performance</span> <span m='84980'>per</span> <span m='85170'>watt</span>\
  \ <span m='85520'>might</span> <span m='85870'>be</span> <span m='86000'>an</span>\
  \ <span m='86070'>important</span> <span m='86490'>goal.</span> </p><p><span m='88570'>One</span>\
  \ <span m='88730'>of</span> <span m='88800'>the</span> <span m='88970'>interesting</span>\
  \ <span m='89450'>challenges</span> <span m='90160'>in</span> <span m='90290'>computer</span>\
  \ <span m='90720'>engineering</span> <span m='91330'>is</span> <span m='91460'>deciding</span>\
  \ <span m='91860'>exactly</span> <span m='92590'>how</span> <span m='92760'>to</span>\
  \ <span m='92850'>balance</span> <span m='93310'>performance</span> <span m='93920'>against</span>\
  \ <span m='94250'>cost</span> <span m='94660'>and</span> <span m='94750'>power</span>\
  \ <span m='95070'>efficiency.</span> </p><p><span m='96110'>Clearly</span> <span\
  \ m='96450'>the</span> <span m='96550'>designers</span> <span m='97050'>of</span>\
  \ <span m='97120'>the</span> <span m='97280'>Apple</span> <span m='97540'>Watch</span>\
  \ <span m='97940'>have</span> <span m='98140'>a</span> <span m='98170'>different</span>\
  \ <span m='98630'>set</span> <span m='98800'>of</span> <span m='98900'>design</span>\
  \ <span m='99310'>goals</span> <span m='99890'>then</span> <span m='100200'>the</span>\
  \ <span m='100290'>designers</span> <span m='100890'>of</span> <span m='101020'>high-end</span>\
  \ <span m='101550'>desktop</span> <span m='102080'>computers.</span> </p><p><span\
  \ m='104040'>The</span> <span m='104120'>performance</span> <span m='104700'>of</span>\
  \ <span m='104790'>a</span> <span m='104850'>processor</span> <span m='105530'>is</span>\
  \ <span m='105720'>inversely</span> <span m='106320'>proportional</span> <span m='106980'>to</span>\
  \ <span m='107080'>the</span> <span m='107210'>length</span> <span m='107490'>of</span>\
  \ <span m='107570'>time</span> <span m='107980'>it</span> <span m='108070'>takes</span>\
  \ <span m='108360'>to</span> <span m='108480'>run</span> <span m='108730'>a</span>\
  \ <span m='108780'>program.</span> </p><p><span m='110080'>The</span> <span m='110150'>shorter</span>\
  \ <span m='110500'>the</span> <span m='110680'>execution</span> <span m='111260'>time,</span>\
  \ <span m='111780'>the</span> <span m='112000'>higher</span> <span m='112380'>the</span>\
  \ <span m='112480'>performance.</span> </p><p><span m='113970'>The</span> <span\
  \ m='114130'>execution</span> <span m='114730'>time</span> <span m='115050'>is</span>\
  \ <span m='115150'>determined</span> <span m='115610'>by</span> <span m='115750'>three</span>\
  \ <span m='116070'>factors.</span> </p><p><span m='116960'>First,</span> <span m='117510'>the</span>\
  \ <span m='117760'>number</span> <span m='118060'>of</span> <span m='118120'>instructions</span>\
  \ <span m='118800'>in</span> <span m='118870'>the</span> <span m='118930'>program.</span>\
  \ </p><p><span m='120430'>Second,</span> <span m='121090'>the</span> <span m='121380'>number</span>\
  \ <span m='121710'>of</span> <span m='121780'>clock</span> <span m='122140'>cycles</span>\
  \ <span m='122600'>our</span> <span m='122670'>sequential</span> <span m='123210'>circuit</span>\
  \ <span m='123570'>requires</span> <span m='124240'>to</span> <span m='124340'>execute</span>\
  \ <span m='124860'>a</span> <span m='124920'>particular</span> <span m='125410'>instruction.</span>\
  \ </p><p><span m='126950'>Complex</span> <span m='127510'>instructions,</span> <span\
  \ m='128380'>e.g.,</span> <span m='128889'>adding</span> <span m='129270'>two</span>\
  \ <span m='129430'>values</span> <span m='129820'>from</span> <span m='130039'>main</span>\
  \ <span m='130250'>memory,</span> <span m='130960'>may</span> <span m='131340'>make</span>\
  \ <span m='131540'>a</span> <span m='131580'>program</span> <span m='132090'>shorter,</span>\
  \ <span m='132910'>but</span> <span m='133340'>may</span> <span m='133530'>also</span>\
  \ <span m='133850'>require</span> <span m='134340'>many</span> <span m='134570'>clock</span>\
  \ <span m='134980'>cycles</span> <span m='135370'>to</span> <span m='135470'>perform</span>\
  \ <span m='135850'>the</span> <span m='135920'>necessary</span> <span m='136570'>memory</span>\
  \ <span m='137090'>and</span> <span m='137310'>datapath</span> <span m='137780'>operations.</span>\
  \ </p><p><span m='139720'>Third,</span> <span m='140280'>the</span> <span m='140630'>amount</span>\
  \ <span m='140950'>of</span> <span m='141050'>time</span> <span m='141470'>needed</span>\
  \ <span m='141750'>for</span> <span m='141880'>each</span> <span m='142130'>clock</span>\
  \ <span m='142420'>cycle,</span> <span m='143000'>as</span> <span m='143300'>determined</span>\
  \ <span m='143760'>by</span> <span m='143890'>the</span> <span m='144010'>propagation</span>\
  \ <span m='144660'>delay</span> <span m='145070'>of</span> <span m='145210'>the</span>\
  \ <span m='145290'>digital</span> <span m='145780'>logic</span> <span m='146180'>in</span>\
  \ <span m='146240'>the</span> <span m='146350'>datapath.</span> </p><p><span m='148340'>So</span>\
  \ <span m='148730'>to</span> <span m='148890'>increase</span> <span m='149470'>the</span>\
  \ <span m='149560'>performance</span> <span m='150210'>we</span> <span m='150370'>could</span>\
  \ <span m='150570'>reduce</span> <span m='151050'>the</span> <span m='151110'>number</span>\
  \ <span m='151390'>of</span> <span m='151480'>instructions</span> <span m='152140'>to</span>\
  \ <span m='152220'>be</span> <span m='152370'>executed.</span> </p><p><span m='153620'>Or</span>\
  \ <span m='153880'>we</span> <span m='153990'>can</span> <span m='154160'>try</span>\
  \ <span m='154380'>to</span> <span m='154470'>minimize</span> <span m='155240'>the</span>\
  \ <span m='155330'>number</span> <span m='155660'>of</span> <span m='155760'>clock</span>\
  \ <span m='156100'>cycles</span> <span m='156550'>needed</span> <span m='156900'>on</span>\
  \ <span m='157090'>the</span> <span m='157240'>average</span> <span m='157900'>to</span>\
  \ <span m='158190'>execute</span> <span m='158640'>our</span> <span m='158790'>instructions.</span>\
  \ </p><p><span m='160210'>There\u2019s</span> <span m='160400'>obviously</span>\
  \ <span m='160850'>a</span> <span m='160900'>bit</span> <span m='161040'>of</span>\
  \ <span m='161130'>a</span> <span m='161190'>tradeoff</span> <span m='161910'>between</span>\
  \ <span m='162300'>these</span> <span m='162540'>first</span> <span m='162800'>two</span>\
  \ <span m='163020'>options:</span> </p><p><span m='164060'>more</span> <span m='164350'>computation</span>\
  \ <span m='165070'>per</span> <span m='165230'>instruction</span> <span m='166040'>usually</span>\
  \ <span m='166500'>means</span> <span m='166750'>it</span> <span m='166820'>will</span>\
  \ <span m='166910'>take</span> <span m='167140'>more</span> <span m='167410'>time</span>\
  \ <span m='167760'>to</span> <span m='167900'>execute</span> <span m='168430'>the</span>\
  \ <span m='168550'>instruction.</span> </p><p><span m='170060'>Or</span> <span m='170300'>we</span>\
  \ <span m='170400'>can</span> <span m='170540'>try</span> <span m='170740'>to</span>\
  \ <span m='170800'>keep</span> <span m='171050'>our</span> <span m='171160'>logic</span>\
  \ <span m='171540'>simple,</span> <span m='172120'>minimizing</span> <span m='173020'>its</span>\
  \ <span m='173160'>propagation</span> <span m='173810'>delay</span> <span m='174380'>in</span>\
  \ <span m='174620'>the</span> <span m='174710'>hopes</span> <span m='175130'>of</span>\
  \ <span m='175210'>having</span> <span m='175560'>a</span> <span m='175600'>short</span>\
  \ <span m='176060'>clock</span> <span m='176310'>period.</span> </p><p><span m='178350'>Today</span>\
  \ <span m='178780'>we\u2019ll</span> <span m='178960'>focus</span> <span m='179430'>on</span>\
  \ <span m='179570'>an</span> <span m='179680'>implementation</span> <span m='180430'>for</span>\
  \ <span m='180560'>the</span> <span m='180660'>Beta</span> <span m='181240'>ISA</span>\
  \ <span m='182210'>that</span> <span m='182990'>executes</span> <span m='183590'>one</span>\
  \ <span m='183830'>instruction</span> <span m='184470'>every</span> <span m='184730'>clock</span>\
  \ <span m='185030'>cycle.</span> </p><p><span m='186230'>The</span> <span m='186290'>combinational</span>\
  \ <span m='186960'>paths</span> <span m='187370'>in</span> <span m='187440'>our</span>\
  \ <span m='187540'>circuit</span> <span m='187920'>will</span> <span m='188010'>be</span>\
  \ <span m='188150'>fairly</span> <span m='188480'>long,</span> <span m='189000'>but,</span>\
  \ <span m='189450'>as</span> <span m='189750'>we</span> <span m='189880'>learned</span>\
  \ <span m='190170'>in</span> <span m='190250'>Part</span> <span m='190530'>1</span>\
  \ <span m='190630'>of</span> <span m='190780'>the</span> <span m='190850'>course,</span>\
  \ <span m='191450'>this</span> <span m='191880'>gives</span> <span m='192120'>us</span>\
  \ <span m='192320'>the</span> <span m='192450'>opportunity</span> <span m='193360'>to</span>\
  \ <span m='193620'>use</span> <span m='193880'>pipelining</span> <span m='194630'>to</span>\
  \ <span m='194790'>increase</span> <span m='195260'>our</span> <span m='195390'>implementation\u2019\
  s</span> <span m='196180'>throughput.</span> </p><p><span m='197620'>We\u2019ll</span>\
  \ <span m='197710'>talk</span> <span m='198010'>about</span> <span m='198370'>the</span>\
  \ <span m='198520'>implementation</span> <span m='199200'>of</span> <span m='199300'>a</span>\
  \ <span m='199360'>pipelined</span> <span m='199950'>processor</span> <span m='200660'>in</span>\
  \ <span m='200840'>some</span> <span m='201060'>upcoming</span> <span m='201480'>lectures.</span>\
  \ </p><p><span m='203040'>Here\u2019s</span> <span m='203250'>a</span> <span m='203280'>quick</span>\
  \ <span m='203520'>refresher</span> <span m='204210'>on</span> <span m='204400'>the</span>\
  \ <span m='204470'>Beta</span> <span m='204870'>ISA.</span> </p><p><span m='206090'>The</span>\
  \ <span m='206170'>Beta</span> <span m='206420'>has</span> <span m='206750'>thirty-two</span>\
  \ <span m='207430'>32-bit</span> <span m='207880'>registers</span> <span m='208600'>that</span>\
  \ <span m='208790'>hold</span> <span m='208990'>values</span> <span m='209440'>for</span>\
  \ <span m='209560'>use</span> <span m='209890'>by</span> <span m='210060'>the</span>\
  \ <span m='210160'>datapath.</span> </p><p><span m='211400'>The</span> <span m='211470'>first</span>\
  \ <span m='211760'>class</span> <span m='212130'>of</span> <span m='212250'>ALU</span>\
  \ <span m='212590'>instructions,</span> <span m='213340'>which</span> <span m='213610'>have</span>\
  \ <span m='214160'>0b10</span> <span m='214900'>as</span> <span m='215250'>the</span>\
  \ <span m='215370'>top</span> <span m='215880'>2</span> <span m='216000'>bits</span>\
  \ <span m='216460'>of</span> <span m='216540'>the</span> <span m='216650'>opcode</span>\
  \ <span m='217080'>field,</span> <span m='217560'>perform</span> <span m='218080'>an</span>\
  \ <span m='218160'>operation</span> <span m='218750'>on</span> <span m='218860'>two</span>\
  \ <span m='219080'>register</span> <span m='219570'>operands</span> <span m='220260'>(Ra</span>\
  \ <span m='220560'>and</span> <span m='220930'>Rb),</span> <span m='221610'>storing</span>\
  \ <span m='222130'>the</span> <span m='222220'>result</span> <span m='222570'>back</span>\
  \ <span m='222860'>into</span> <span m='223240'>a</span> <span m='223270'>specified</span>\
  \ <span m='223930'>destination</span> <span m='224460'>register</span> <span m='225020'>(Rc).</span>\
  \ </p><p><span m='226690'>There\u2019s</span> <span m='227130'>a</span> <span m='227240'>6-bit</span>\
  \ <span m='227470'>opcode</span> <span m='227940'>field</span> <span m='228280'>to</span>\
  \ <span m='228380'>specify</span> <span m='228950'>the</span> <span m='229110'>operation</span>\
  \ <span m='229920'>and</span> <span m='230270'>three</span> <span m='230820'>5-bit</span>\
  \ <span m='231180'>register</span> <span m='231660'>fields</span> <span m='232070'>to</span>\
  \ <span m='232190'>specify</span> <span m='232750'>the</span> <span m='232850'>registers</span>\
  \ <span m='233440'>to</span> <span m='233540'>use</span> <span m='233910'>as</span>\
  \ <span m='233980'>source</span> <span m='234530'>and</span> <span m='234670'>destination.</span>\
  \ </p><p><span m='236490'>The</span> <span m='236560'>second</span> <span m='236920'>class</span>\
  \ <span m='237350'>of</span> <span m='237520'>ALU</span> <span m='237880'>instructions,</span>\
  \ <span m='238540'>which</span> <span m='238780'>have</span> <span m='239220'>0b11</span>\
  \ <span m='239620'>in</span> <span m='240000'>the</span> <span m='240080'>top</span>\
  \ <span m='240480'>2</span> <span m='240520'>bits</span> <span m='240790'>of</span>\
  \ <span m='240860'>the</span> <span m='241000'>opcode,</span> <span m='241660'>perform</span>\
  \ <span m='242120'>the</span> <span m='242200'>same</span> <span m='242570'>set</span>\
  \ <span m='242780'>of</span> <span m='242870'>operations</span> <span m='243950'>where</span>\
  \ <span m='244420'>the</span> <span m='244510'>second</span> <span m='244920'>operand</span>\
  \ <span m='245390'>is</span> <span m='245530'>a</span> <span m='245560'>constant</span>\
  \ <span m='246160'>in</span> <span m='246240'>the</span> <span m='246310'>range</span>\
  \ <span m='246900'>-32768</span> <span m='247300'>to</span> <span m='248620'>+32767.</span>\
  \ </p><p><span m='249110'>The</span> <span m='252340'>operations</span> <span m='253010'>include</span>\
  \ <span m='253450'>arithmetic</span> <span m='254050'>operations,</span> <span m='254940'>comparisons,</span>\
  \ <span m='256269'>boolean</span> <span m='256940'>operations,</span> <span m='257850'>and</span>\
  \ <span m='258060'>shifts.</span> </p><p><span m='259260'>In</span> <span m='259360'>assembly</span>\
  \ <span m='259779'>language,</span> <span m='260240'>we</span> <span m='260420'>use</span>\
  \ <span m='260700'>a</span> <span m='260740'>\u201CC\u201D</span> <span m='261070'>suffix</span>\
  \ <span m='261700'>added</span> <span m='262010'>to</span> <span m='262089'>the</span>\
  \ <span m='262210'>mnemonics</span> <span m='262740'>shown</span> <span m='263030'>here</span>\
  \ <span m='263400'>to</span> <span m='263560'>indicate</span> <span m='264060'>that</span>\
  \ <span m='264270'>the</span> <span m='264350'>second</span> <span m='264720'>operand</span>\
  \ <span m='265270'>is</span> <span m='265400'>a</span> <span m='265430'>constant.</span>\
  \ </p><p><span m='267720'>This</span> <span m='267960'>second</span> <span m='268220'>instruction</span>\
  \ <span m='268830'>format</span> <span m='269330'>is</span> <span m='269520'>also</span>\
  \ <span m='269910'>used</span> <span m='270260'>by</span> <span m='270450'>the</span>\
  \ <span m='270570'>instructions</span> <span m='271240'>that</span> <span m='271370'>access</span>\
  \ <span m='271880'>memory</span> <span m='272360'>and</span> <span m='272580'>change</span>\
  \ <span m='273090'>the</span> <span m='273190'>normally</span> <span m='273700'>sequential</span>\
  \ <span m='274440'>execution</span> <span m='275020'>order.</span> </p><p><span\
  \ m='275990'>The</span> <span m='276060'>use</span> <span m='276370'>of</span> <span\
  \ m='276480'>just</span> <span m='276740'>two</span> <span m='276920'>instruction</span>\
  \ <span m='277440'>formats</span> <span m='278010'>will</span> <span m='278110'>make</span>\
  \ <span m='278320'>it</span> <span m='278420'>very</span> <span m='278820'>easy</span>\
  \ <span m='279160'>to</span> <span m='279270'>build</span> <span m='279560'>the</span>\
  \ <span m='279620'>logic</span> <span m='280100'>responsible</span> <span m='280810'>for</span>\
  \ <span m='281000'>translating</span> <span m='281720'>the</span> <span m='281850'>encoded</span>\
  \ <span m='282330'>instructions</span> <span m='283330'>into</span> <span m='283760'>the</span>\
  \ <span m='283860'>signals</span> <span m='284510'>needed</span> <span m='284840'>to</span>\
  \ <span m='284960'>control</span> <span m='285530'>the</span> <span m='285680'>operation</span>\
  \ <span m='286260'>of</span> <span m='286340'>the</span> <span m='286420'>datapath.</span>\
  \ </p><p><span m='287800'>In</span> <span m='287910'>fact,</span> <span m='288500'>we\u2019\
  ll</span> <span m='288780'>be</span> <span m='289020'>able</span> <span m='289200'>to</span>\
  \ <span m='289290'>use</span> <span m='289560'>many</span> <span m='289950'>of</span>\
  \ <span m='290030'>the</span> <span m='290140'>instruction</span> <span m='290720'>bits</span>\
  \ <span m='291180'>as-is!</span> </p><p><span m='292820'>We\u2019ll</span> <span\
  \ m='292940'>build</span> <span m='293240'>our</span> <span m='293350'>datapath</span>\
  \ <span m='293960'>incrementally,</span> <span m='294830'>starting</span> <span\
  \ m='295410'>with</span> <span m='295520'>the</span> <span m='295590'>logic</span>\
  \ <span m='296020'>needed</span> <span m='296310'>to</span> <span m='296390'>perform</span>\
  \ <span m='296890'>the</span> <span m='297140'>ALU</span> <span m='297460'>instructions,</span>\
  \ <span m='298310'>then</span> <span m='298740'>add</span> <span m='299030'>additional</span>\
  \ <span m='299600'>logic</span> <span m='300010'>to</span> <span m='300120'>execute</span>\
  \ <span m='300610'>the</span> <span m='300700'>memory</span> <span m='301260'>and</span>\
  \ <span m='301430'>branch</span> <span m='301770'>instructions.</span> </p><p><span\
  \ m='302990'>Finally,</span> <span m='303470'>we\u2019ll</span> <span m='303670'>need</span>\
  \ <span m='303870'>to</span> <span m='303940'>add</span> <span m='304200'>logic</span>\
  \ <span m='304580'>to</span> <span m='304700'>handle</span> <span m='305110'>what</span>\
  \ <span m='305350'>happens</span> <span m='306060'>when</span> <span m='306400'>an</span>\
  \ <span m='306510'>exception</span> <span m='307020'>occurs</span> <span m='307670'>and</span>\
  \ <span m='307920'>execution</span> <span m='308560'>has</span> <span m='308750'>to</span>\
  \ <span m='308840'>be</span> <span m='308970'>suspended</span> <span m='309740'>because</span>\
  \ <span m='310190'>the</span> <span m='310260'>current</span> <span m='310610'>instruction</span>\
  \ <span m='311200'>cannot</span> <span m='311630'>be</span> <span m='311840'>executed</span>\
  \ <span m='312360'>correctly.</span> </p><p><span m='314310'>We\u2019ll</span> <span\
  \ m='314470'>be</span> <span m='314600'>using</span> <span m='314910'>the</span>\
  \ <span m='315000'>digital</span> <span m='315470'>logic</span> <span m='315880'>gates</span>\
  \ <span m='316200'>we</span> <span m='316310'>learned</span> <span m='316540'>about</span>\
  \ <span m='316790'>in</span> <span m='316870'>Part</span> <span m='317220'>1</span>\
  \ <span m='317300'>of</span> <span m='317380'>the</span> <span m='317450'>course.</span>\
  \ </p><p><span m='318640'>In</span> <span m='318750'>particular,</span> <span m='319380'>we\u2019\
  ll</span> <span m='319600'>need</span> <span m='319780'>multi-bit</span> <span m='320340'>registers</span>\
  \ <span m='320940'>to</span> <span m='321070'>hold</span> <span m='321300'>state</span>\
  \ <span m='321630'>information</span> <span m='322220'>from</span> <span m='322450'>one</span>\
  \ <span m='322610'>instruction</span> <span m='323320'>to</span> <span m='323470'>the</span>\
  \ <span m='323570'>next.</span> </p><p><span m='325150'>Recall</span> <span m='325590'>that</span>\
  \ <span m='325720'>these</span> <span m='326050'>memory</span> <span m='326400'>elements</span>\
  \ <span m='326880'>load</span> <span m='327180'>new</span> <span m='327340'>values</span>\
  \ <span m='327790'>at</span> <span m='327870'>the</span> <span m='327950'>rising</span>\
  \ <span m='328370'>edge</span> <span m='328560'>of</span> <span m='328630'>the</span>\
  \ <span m='328700'>clock</span> <span m='329010'>signal,</span> <span m='329590'>then</span>\
  \ <span m='329980'>store</span> <span m='330440'>that</span> <span m='330670'>value</span>\
  \ <span m='331060'>until</span> <span m='331350'>the</span> <span m='331430'>next</span>\
  \ <span m='331750'>rising</span> <span m='332060'>clock</span> <span m='332400'>edge.</span>\
  \ </p><p><span m='333840'>We\u2019ll</span> <span m='334020'>use</span> <span m='334190'>a</span>\
  \ <span m='334230'>lot</span> <span m='334480'>of</span> <span m='334570'>multiplexers</span>\
  \ <span m='335370'>in</span> <span m='335460'>our</span> <span m='335580'>design</span>\
  \ <span m='336050'>to</span> <span m='336170'>select</span> <span m='336680'>between</span>\
  \ <span m='337100'>alternative</span> <span m='337840'>values</span> <span m='338350'>in</span>\
  \ <span m='338440'>the</span> <span m='338510'>datapath.</span> </p><p><span m='340720'>The</span>\
  \ <span m='340860'>actual</span> <span m='341240'>computations</span> <span m='342060'>will</span>\
  \ <span m='342170'>be</span> <span m='342320'>performed</span> <span m='342810'>by</span>\
  \ <span m='342970'>the</span> <span m='343110'>arithmetic</span> <span m='343690'>and</span>\
  \ <span m='343800'>logic</span> <span m='344240'>unit</span> <span m='344480'>(ALU)</span>\
  \ <span m='344570'>that</span> <span m='344720'>we</span> <span m='344870'>designed</span>\
  \ <span m='345350'>at</span> <span m='345420'>the</span> <span m='345560'>end</span>\
  \ <span m='345870'>of</span> <span m='345960'>Part</span> <span m='346520'>1.</span>\
  \ </p><p><span m='347530'>It</span> <span m='347630'>has</span> <span m='347860'>logic</span>\
  \ <span m='348270'>to</span> <span m='348370'>perform</span> <span m='348790'>the</span>\
  \ <span m='348920'>arithmetic,</span> <span m='349670'>comparison,</span> <span\
  \ m='350620'>boolean</span> <span m='351250'>and</span> <span m='351420'>shift</span>\
  \ <span m='351740'>operations</span> <span m='352480'>listed</span> <span m='352830'>on</span>\
  \ <span m='352950'>the</span> <span m='353020'>previous</span> <span m='353530'>slide.</span>\
  \ </p><p><span m='354640'>It</span> <span m='354730'>takes</span> <span m='355060'>in</span>\
  \ <span m='355380'>two</span> <span m='355910'>32-bit</span> <span m='356340'>operands</span>\
  \ <span m='357110'>and</span> <span m='357240'>produces</span> <span m='357920'>a</span>\
  \ <span m='358180'>32-bit</span> <span m='358460'>result.</span> </p><p><span m='360240'>And,</span>\
  \ <span m='360410'>finally,</span> <span m='361070'>we\u2019ll</span> <span m='361300'>use</span>\
  \ <span m='361460'>several</span> <span m='361850'>different</span> <span m='362190'>memory</span>\
  \ <span m='362540'>components</span> <span m='363080'>to</span> <span m='363200'>implement</span>\
  \ <span m='363610'>register</span> <span m='364060'>storage</span> <span m='364540'>in</span>\
  \ <span m='364620'>the</span> <span m='364680'>datapath</span> <span m='365630'>and</span>\
  \ <span m='366170'>also</span> <span m='366570'>for</span> <span m='366740'>main</span>\
  \ <span m='367040'>memory,</span> <span m='367500'>where</span> <span m='367730'>instructions</span>\
  \ <span m='368460'>and</span> <span m='368630'>data</span> <span m='368910'>are</span>\
  \ <span m='369070'>stored.</span> </p><p><span m='370570'>You</span> <span m='370650'>might</span>\
  \ <span m='370890'>find</span> <span m='371130'>it</span> <span m='371220'>useful</span>\
  \ <span m='371690'>to</span> <span m='371830'>review</span> <span m='372140'>the</span>\
  \ <span m='372240'>chapters</span> <span m='372790'>on</span> <span m='372920'>combinational</span>\
  \ <span m='373730'>and</span> <span m='373820'>sequential</span> <span m='374370'>logic</span>\
  \ <span m='374800'>in</span> <span m='374990'>Part</span> <span m='375310'>1</span>\
  \ <span m='375390'>of</span> <span m='375490'>the</span> <span m='375560'>course.</span>\
  \ </p><p><span m='376760'>The</span> <span m='376850'>Beta</span> <span m='377220'>ISA</span>\
  \ <span m='377830'>specifies</span> <span m='378540'>thirty-two</span> <span m='379270'>32-bit</span>\
  \ <span m='379740'>registers</span> <span m='380460'>as</span> <span m='380560'>part</span>\
  \ <span m='380810'>of</span> <span m='380870'>the</span> <span m='380960'>datapath.</span>\
  \ </p><p><span m='382420'>These</span> <span m='382680'>are</span> <span m='382770'>shown</span>\
  \ <span m='383140'>as</span> <span m='383280'>the</span> <span m='383360'>magenta</span>\
  \ <span m='383830'>rectangles</span> <span m='384570'>in</span> <span m='384630'>the</span>\
  \ <span m='384720'>diagram</span> <span m='385280'>below.</span> </p><p><span m='386810'>These</span>\
  \ <span m='386980'>are</span> <span m='387120'>implemented</span> <span m='387650'>as</span>\
  \ <span m='387830'>load-enabled</span> <span m='388640'>registers,</span> <span\
  \ m='389290'>which</span> <span m='389520'>have</span> <span m='389690'>an</span>\
  \ <span m='389900'>EN</span> <span m='390380'>signal</span> <span m='391060'>that</span>\
  \ <span m='391330'>controls</span> <span m='391980'>when</span> <span m='392180'>the</span>\
  \ <span m='392250'>register</span> <span m='392770'>is</span> <span m='392920'>loaded</span>\
  \ <span m='393310'>with</span> <span m='393480'>a</span> <span m='393520'>new</span>\
  \ <span m='393700'>value.</span> </p><p><span m='395030'>If</span> <span m='395240'>EN</span>\
  \ <span m='395540'>is</span> <span m='395690'>1,</span> <span m='395780'>the</span>\
  \ <span m='396200'>register</span> <span m='396820'>will</span> <span m='396980'>be</span>\
  \ <span m='397140'>loaded</span> <span m='397530'>from</span> <span m='397690'>the</span>\
  \ <span m='397750'>D</span> <span m='398080'>input</span> <span m='398440'>at</span>\
  \ <span m='398550'>the</span> <span m='398660'>next</span> <span m='399020'>rising</span>\
  \ <span m='399380'>clock</span> <span m='399730'>edge.</span> </p><p><span m='401020'>If</span>\
  \ <span m='401270'>EN</span> <span m='401560'>is</span> <span m='401860'>0,</span>\
  \ <span m='402220'>the</span> <span m='402630'>register</span> <span m='403150'>is</span>\
  \ <span m='403240'>reloaded</span> <span m='403800'>with</span> <span m='403990'>its</span>\
  \ <span m='404170'>current</span> <span m='404520'>value</span> <span m='405010'>and</span>\
  \ <span m='405220'>hence</span> <span m='405580'>its</span> <span m='405740'>value</span>\
  \ <span m='406080'>is</span> <span m='406220'>unchanged.</span> </p><p><span m='406880'>It</span>\
  \ <span m='407560'>might</span> <span m='408390'>seem</span> <span m='408630'>easier</span>\
  \ <span m='409050'>to</span> <span m='409180'>add</span> <span m='409410'>enabling</span>\
  \ <span m='409930'>logic</span> <span m='410260'>to</span> <span m='410410'>the</span>\
  \ <span m='410510'>clock</span> <span m='410870'>signal,</span> <span m='411560'>but</span>\
  \ <span m='411980'>this</span> <span m='412200'>is</span> <span m='412310'>almost</span>\
  \ <span m='412660'>never</span> <span m='413220'>a</span> <span m='413250'>good</span>\
  \ <span m='413430'>idea</span> <span m='413890'>since</span> <span m='414210'>any</span>\
  \ <span m='414410'>glitches</span> <span m='414890'>in</span> <span m='414980'>that</span>\
  \ <span m='415160'>logic</span> <span m='415620'>might</span> <span m='415890'>generate</span>\
  \ <span m='416380'>false</span> <span m='416750'>edges</span> <span m='417170'>that</span>\
  \ <span m='417320'>would</span> <span m='417500'>cause</span> <span m='417970'>the</span>\
  \ <span m='418060'>register</span> <span m='418550'>to</span> <span m='418680'>load</span>\
  \ <span m='418990'>a</span> <span m='419050'>new</span> <span m='419250'>value</span>\
  \ <span m='419670'>at</span> <span m='419750'>the</span> <span m='419850'>wrong</span>\
  \ <span m='420180'>time.</span> </p><p><span m='421400'>Always</span> <span m='421690'>remember</span>\
  \ <span m='422160'>the</span> <span m='422260'>mantra:</span> <span m='422920'>NO</span>\
  \ <span m='423520'>GATED</span> <span m='423920'>CLOCKS!</span> </p><p><span m='425400'>There</span>\
  \ <span m='425570'>are</span> <span m='425600'>multiplexers</span> <span m='426450'>(shown</span>\
  \ <span m='426820'>underneath</span> <span m='427200'>the</span> <span m='427270'>registers)</span>\
  \ <span m='427960'>that</span> <span m='428170'>let</span> <span m='428340'>us</span>\
  \ <span m='428560'>select</span> <span m='428960'>a</span> <span m='429030'>value</span>\
  \ <span m='429380'>from</span> <span m='429610'>any</span> <span m='429980'>of</span>\
  \ <span m='430190'>the</span> <span m='430420'>32</span> <span m='430500'>registers.</span>\
  \ </p><p><span m='432140'>Since</span> <span m='432500'>we</span> <span m='432630'>need</span>\
  \ <span m='432880'>two</span> <span m='433120'>operands</span> <span m='433730'>for</span>\
  \ <span m='433860'>the</span> <span m='433960'>datapath</span> <span m='434530'>logic,</span>\
  \ <span m='434930'>there</span> <span m='435160'>are</span> <span m='435220'>two</span>\
  \ <span m='435480'>such</span> <span m='435790'>multiplexers.</span> </p><p><span\
  \ m='437520'>Their</span> <span m='437650'>select</span> <span m='438080'>inputs</span>\
  \ <span m='438750'>(RA1</span> <span m='439470'>and</span> <span m='439730'>RA2)</span>\
  \ <span m='440460'>function</span> <span m='441240'>as</span> <span m='441730'>addresses,</span>\
  \ <span m='442610'>determining</span> <span m='443280'>which</span> <span m='443640'>register</span>\
  \ <span m='444070'>values</span> <span m='444490'>will</span> <span m='444600'>be</span>\
  \ <span m='444690'>selected</span> <span m='445250'>as</span> <span m='445460'>operands.</span>\
  \ </p><p><span m='447170'>And,</span> <span m='447330'>finally,</span> <span m='448160'>there\u2019\
  s</span> <span m='448630'>a</span> <span m='448680'>decoder</span> <span m='449330'>that</span>\
  \ <span m='449480'>determines</span> <span m='450020'>which</span> <span m='450400'>of</span>\
  \ <span m='450470'>the</span> <span m='450760'>32</span> <span m='450990'>register</span>\
  \ <span m='451620'>load</span> <span m='451860'>enables</span> <span m='452420'>will</span>\
  \ <span m='452570'>be</span> <span m='452880'>1</span> <span m='453280'>based</span>\
  \ <span m='453940'>on</span> <span m='454320'>the</span> <span m='454610'>5-bit</span>\
  \ <span m='454880'>WA</span> <span m='455000'>input.</span> </p><p><span m='457200'>For</span>\
  \ <span m='457320'>convenience,</span> <span m='457900'>we\u2019ll</span> <span\
  \ m='458050'>package</span> <span m='458560'>all</span> <span m='458860'>this</span>\
  \ <span m='459060'>functionality</span> <span m='459860'>up</span> <span m='459920'>into</span>\
  \ <span m='460160'>a</span> <span m='460190'>single</span> <span m='460630'>component</span>\
  \ <span m='461190'>called</span> <span m='461480'>a</span> <span m='461520'>\u201C\
  register</span> <span m='462010'>file\u201D.</span> </p><p><span m='463430'>The</span>\
  \ <span m='463510'>register</span> <span m='463990'>file</span> <span m='464420'>has</span>\
  \ <span m='464810'>two</span> <span m='465040'>read</span> <span m='465300'>ports,</span>\
  \ <span m='465730'>which,</span> <span m='466050'>given</span> <span m='466640'>a</span>\
  \ <span m='466900'>5-bit</span> <span m='467130'>address</span> <span m='467610'>input,</span>\
  \ <span m='468190'>deliver</span> <span m='468980'>the</span> <span m='469190'>selected</span>\
  \ <span m='469800'>register</span> <span m='470250'>value</span> <span m='470630'>on</span>\
  \ <span m='470810'>the</span> <span m='470980'>read-data</span> <span m='471540'>ports.</span>\
  \ </p><p><span m='473490'>The</span> <span m='473590'>two</span> <span m='473910'>read</span>\
  \ <span m='474220'>ports</span> <span m='474670'>operate</span> <span m='475140'>independently.</span>\
  \ </p><p><span m='476420'>They</span> <span m='476490'>can</span> <span m='476680'>read</span>\
  \ <span m='476870'>from</span> <span m='477050'>different</span> <span m='477390'>registers</span>\
  \ <span m='478000'>or,</span> <span m='478410'>if</span> <span m='478590'>the</span>\
  \ <span m='478760'>addresses</span> <span m='479260'>are</span> <span m='479360'>the</span>\
  \ <span m='479450'>same,</span> <span m='480040'>read</span> <span m='480400'>from</span>\
  \ <span m='480540'>the</span> <span m='480610'>same</span> <span m='480980'>register.</span>\
  \ </p><p><span m='483340'>The</span> <span m='483400'>signals</span> <span m='483800'>on</span>\
  \ <span m='483910'>the</span> <span m='484010'>left</span> <span m='484300'>of</span>\
  \ <span m='484370'>the</span> <span m='484440'>register</span> <span m='484880'>file</span>\
  \ <span m='485260'>include</span> <span m='485740'>a</span> <span m='485930'>5-bit</span>\
  \ <span m='486330'>value</span> <span m='486830'>(WA)</span> <span m='487100'>that</span>\
  \ <span m='487420'>selects</span> <span m='487830'>a</span> <span m='487860'>register</span>\
  \ <span m='488300'>to</span> <span m='488370'>be</span> <span m='488560'>written</span>\
  \ <span m='489100'>with</span> <span m='489440'>the</span> <span m='489500'>specified</span>\
  \ <span m='490260'>32-bit</span> <span m='490640'>write</span> <span m='491040'>data</span>\
  \ <span m='491500'>(WD).</span> </p><p><span m='492990'>If</span> <span m='493120'>the</span>\
  \ <span m='493200'>write</span> <span m='493440'>enable</span> <span m='493780'>signal</span>\
  \ <span m='494380'>(WE)</span> <span m='494870'>is</span> <span m='495190'>1</span>\
  \ <span m='495400'>at</span> <span m='495660'>the</span> <span m='495730'>rising</span>\
  \ <span m='496130'>edge</span> <span m='496300'>of</span> <span m='496360'>the</span>\
  \ <span m='496430'>clock</span> <span m='496700'>(CLK)</span> <span m='496770'>signal,</span>\
  \ <span m='497360'>the</span> <span m='497600'>selected</span> <span m='498140'>register</span>\
  \ <span m='498610'>will</span> <span m='498750'>be</span> <span m='498900'>loaded</span>\
  \ <span m='499360'>with</span> <span m='499490'>the</span> <span m='499550'>supplied</span>\
  \ <span m='500170'>write</span> <span m='500400'>data.</span> </p><p><span m='502140'>Note</span>\
  \ <span m='502340'>that</span> <span m='502500'>in</span> <span m='502640'>the</span>\
  \ <span m='502720'>BETA</span> <span m='503120'>ISA,</span> <span m='503870'>reading</span>\
  \ <span m='504400'>from</span> <span m='504650'>register</span> <span m='505110'>address</span>\
  \ <span m='505640'>31</span> <span m='505910'>should</span> <span m='506270'>always</span>\
  \ <span m='506560'>produce</span> <span m='506960'>a</span> <span m='507000'>zero</span>\
  \ <span m='507390'>value.</span> </p><p><span m='508360'>The</span> <span m='508480'>register</span>\
  \ <span m='508930'>file</span> <span m='509220'>has</span> <span m='509440'>internal</span>\
  \ <span m='509860'>logic</span> <span m='510270'>to</span> <span m='510500'>ensure</span>\
  \ <span m='510880'>that</span> <span m='511090'>happens.</span> </p><p><span m='512390'>Here\u2019\
  s</span> <span m='512590'>a</span> <span m='512640'>timing</span> <span m='513090'>diagram</span>\
  \ <span m='513659'>that</span> <span m='513760'>shows</span> <span m='514150'>the</span>\
  \ <span m='514280'>register</span> <span m='514730'>file</span> <span m='515049'>in</span>\
  \ <span m='515169'>operation.</span> </p><p><span m='516760'>To</span> <span m='516890'>read</span>\
  \ <span m='517110'>a</span> <span m='517169'>value</span> <span m='517530'>from</span>\
  \ <span m='517700'>the</span> <span m='517809'>register</span> <span m='518230'>file,</span>\
  \ <span m='518710'>supply</span> <span m='519309'>a</span> <span m='519340'>stable</span>\
  \ <span m='519850'>address</span> <span m='520220'>input</span> <span m='520750'>(RA)</span>\
  \ <span m='521360'>on</span> <span m='521720'>one</span> <span m='521929'>of</span>\
  \ <span m='522120'>read</span> <span m='522289'>ports.</span> </p><p><span m='523429'>After</span>\
  \ <span m='523710'>the</span> <span m='523799'>register</span> <span m='524300'>file\u2019\
  s</span> <span m='524790'>propagation</span> <span m='525460'>delay,</span> <span\
  \ m='526050'>the</span> <span m='526330'>value</span> <span m='526750'>of</span>\
  \ <span m='526830'>the</span> <span m='526920'>selected</span> <span m='527560'>register</span>\
  \ <span m='528020'>will</span> <span m='528250'>appear</span> <span m='528590'>on</span>\
  \ <span m='528690'>the</span> <span m='528750'>corresponding</span> <span m='529520'>read</span>\
  \ <span m='529680'>data</span> <span m='529960'>port</span> <span m='530460'>(RD).</span>\
  \ <span m='530760'>[CLICK]</span> </p><p><span m='531910'>Not</span> <span m='532090'>surprisingly,</span>\
  \ <span m='532840'>the</span> <span m='532960'>register</span> <span m='533440'>file</span>\
  \ <span m='533790'>write</span> <span m='534010'>operation</span> <span m='534620'>is</span>\
  \ <span m='534780'>very</span> <span m='535070'>similar</span> <span m='535500'>to</span>\
  \ <span m='535670'>writing</span> <span m='536000'>an</span> <span m='536090'>ordinary</span>\
  \ <span m='536660'>D-register.</span> </p><p><span m='537980'>The</span> <span m='538080'>write</span>\
  \ <span m='538360'>address</span> <span m='539040'>(WA),</span> <span m='539750'>write</span>\
  \ <span m='540220'>data</span> <span m='540780'>(WD)</span> <span m='541740'>and</span>\
  \ <span m='542020'>write</span> <span m='542260'>enable</span> <span m='543100'>(WE)</span>\
  \ <span m='543580'>signals</span> <span m='544120'>must</span> <span m='544390'>all</span>\
  \ <span m='544590'>be</span> <span m='544750'>valid</span> <span m='545150'>and</span>\
  \ <span m='545240'>stable</span> <span m='545750'>for</span> <span m='545900'>some</span>\
  \ <span m='546140'>specified</span> <span m='546890'>setup</span> <span m='547250'>time</span>\
  \ <span m='547590'>before</span> <span m='547990'>the</span> <span m='548100'>rising</span>\
  \ <span m='548530'>edge</span> <span m='548740'>of</span> <span m='548810'>the</span>\
  \ <span m='548890'>clock.</span> </p><p><span m='550310'>And</span> <span m='550400'>must</span>\
  \ <span m='550650'>remain</span> <span m='551060'>stable</span> <span m='551800'>and</span>\
  \ <span m='552160'>valid</span> <span m='552580'>for</span> <span m='552750'>the</span>\
  \ <span m='552850'>specified</span> <span m='553520'>hold</span> <span m='553760'>time</span>\
  \ <span m='554380'>after</span> <span m='554900'>the</span> <span m='555000'>rising</span>\
  \ <span m='555450'>clock</span> <span m='555850'>edge.</span> </p><p><span m='557410'>If</span>\
  \ <span m='557550'>those</span> <span m='557820'>timing</span> <span m='558120'>constraints</span>\
  \ <span m='558660'>are</span> <span m='558750'>met,</span> <span m='559130'>the</span>\
  \ <span m='559290'>register</span> <span m='559740'>file</span> <span m='560300'>will</span>\
  \ <span m='560390'>reliably</span> <span m='561040'>update</span> <span m='561410'>the</span>\
  \ <span m='561510'>value</span> <span m='561990'>of</span> <span m='562140'>the</span>\
  \ <span m='562200'>selected</span> <span m='562710'>register.</span> <span m='564080'>[CLICK]</span>\
  \ </p><p><span m='565120'>When</span> <span m='565290'>a</span> <span m='565340'>register</span>\
  \ <span m='565900'>value</span> <span m='566350'>is</span> <span m='566480'>written</span>\
  \ <span m='567000'>at</span> <span m='567180'>the</span> <span m='567280'>rising</span>\
  \ <span m='567660'>clock</span> <span m='568030'>edge,</span> <span m='568710'>if</span>\
  \ <span m='569190'>that</span> <span m='569440'>value</span> <span m='569750'>is</span>\
  \ <span m='569830'>selected</span> <span m='570260'>by</span> <span m='570400'>a</span>\
  \ <span m='570430'>read</span> <span m='570710'>address,</span> <span m='571200'>the</span>\
  \ <span m='571290'>new</span> <span m='571500'>data</span> <span m='571800'>will</span>\
  \ <span m='572030'>appear</span> <span m='572420'>after</span> <span m='572740'>the</span>\
  \ <span m='572810'>propagation</span> <span m='573470'>delay</span> <span m='574040'>on</span>\
  \ <span m='574340'>the</span> <span m='574410'>corresponding</span> <span m='575130'>data</span>\
  \ <span m='575380'>port.</span> </p><p><span m='576540'>In</span> <span m='576630'>other</span>\
  \ <span m='576780'>words,</span> <span m='577320'>the</span> <span m='577570'>read</span>\
  \ <span m='577890'>data</span> <span m='578140'>value</span> <span m='578480'>changes</span>\
  \ <span m='579130'>if</span> <span m='579320'>either</span> <span m='579640'>the</span>\
  \ <span m='579760'>read</span> <span m='580030'>address</span> <span m='580410'>changes</span>\
  \ <span m='581100'>or</span> <span m='581720'>the</span> <span m='581910'>value</span>\
  \ <span m='582320'>of</span> <span m='582410'>the</span> <span m='582490'>selected</span>\
  \ <span m='583040'>register</span> <span m='583580'>changes.</span> </p><p><span\
  \ m='586170'>Can</span> <span m='586380'>we</span> <span m='586540'>read</span>\
  \ <span m='586850'>and</span> <span m='586990'>write</span> <span m='587280'>the</span>\
  \ <span m='587370'>same</span> <span m='587720'>register</span> <span m='588250'>in</span>\
  \ <span m='588380'>a</span> <span m='588420'>single</span> <span m='588910'>clock</span>\
  \ <span m='589220'>cycle?</span> </p><p><span m='590480'>Yes!</span> <span m='591240'>If</span>\
  \ <span m='591700'>the</span> <span m='591810'>read</span> <span m='592030'>address</span>\
  \ <span m='592410'>becomes</span> <span m='592790'>valid</span> <span m='593150'>at</span>\
  \ <span m='593230'>the</span> <span m='593330'>beginning</span> <span m='593820'>of</span>\
  \ <span m='593900'>the</span> <span m='594140'>cycle,</span> <span m='594920'>the</span>\
  \ <span m='595250'>old</span> <span m='595500'>value</span> <span m='595880'>of</span>\
  \ <span m='595940'>the</span> <span m='596030'>register</span> <span m='596490'>will</span>\
  \ <span m='596750'>be</span> <span m='596830'>appear</span> <span m='597130'>on</span>\
  \ <span m='597330'>the</span> <span m='597440'>data</span> <span m='597740'>port</span>\
  \ <span m='598110'>for</span> <span m='598240'>the</span> <span m='598340'>rest</span>\
  \ <span m='598660'>of</span> <span m='598720'>the</span> <span m='598800'>cycle.</span>\
  \ </p><p><span m='600110'>Then,</span> <span m='600770'>the</span> <span m='601070'>write</span>\
  \ <span m='601320'>occurs</span> <span m='601790'>at</span> <span m='601890'>the</span>\
  \ <span m='602130'>*end*</span> <span m='602520'>of</span> <span m='602610'>the</span>\
  \ <span m='602690'>cycle</span> <span m='603400'>and</span> <span m='603780'>the</span>\
  \ <span m='603850'>new</span> <span m='604090'>register</span> <span m='604530'>value</span>\
  \ <span m='604870'>will</span> <span m='605030'>be</span> <span m='605200'>available</span>\
  \ <span m='605720'>in</span> <span m='605790'>the</span> <span m='605860'>next</span>\
  \ <span m='606170'>clock</span> <span m='606460'>cycle.</span> </p><p><span m='608120'>Okay,</span>\
  \ <span m='608640'>that\u2019s</span> <span m='609040'>a</span> <span m='609080'>brief</span>\
  \ <span m='609370'>run-though</span> <span m='609790'>of</span> <span m='609880'>the</span>\
  \ <span m='609970'>components</span> <span m='610540'>we\u2019ll</span> <span m='610640'>be</span>\
  \ <span m='610740'>using.</span> </p><p><span m='611470'>Let\u2019s</span> <span\
  \ m='611630'>get</span> <span m='611760'>started</span> <span m='612230'>on</span>\
  \ <span m='612360'>the</span> <span m='612420'>design!</span> </p>"
type: course
uid: 4103de9aaf941f17da0c74faf56a0390

---
None