---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: S1PUUyVdC9M
  parent_uid: ff9486a26cc854378285d6116fa12db0
  title: Video-YouTube-Stream
  type: Video
  uid: d65260f7ce8ea0d7d56fdbc792d9d36c
- id: 3Play-3Play YouTube id-Stream
  media_location: S1PUUyVdC9M
  parent_uid: ff9486a26cc854378285d6116fa12db0
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 82e55ec64e838f0e86cc980e8e408851
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/S1PUUyVdC9M/default.jpg
  parent_uid: ff9486a26cc854378285d6116fa12db0
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 7552ed0c7102cab3bf3a880339714068
- id: S1PUUyVdC9M.srt
  parent_uid: ff9486a26cc854378285d6116fa12db0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v7/memory-access-2-56-/S1PUUyVdC9M.srt
  title: 3play caption file
  type: null
  uid: 61b841cfe663df29f3cbd312edfcc631
- id: S1PUUyVdC9M.pdf
  parent_uid: ff9486a26cc854378285d6116fa12db0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v7/memory-access-2-56-/S1PUUyVdC9M.pdf
  title: 3play pdf file
  type: null
  uid: 404d037b1649e863255af50f38a2302b
- id: Caption-3Play YouTube id-SRT
  parent_uid: ff9486a26cc854378285d6116fa12db0
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b4db549d5db6f29095f012bae3af397e
- id: Transcript-3Play YouTube id-PDF
  parent_uid: ff9486a26cc854378285d6116fa12db0
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 1a55dbd2af861319afc144b57de4fc71
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_09-02-07_300k.mp4
  parent_uid: ff9486a26cc854378285d6116fa12db0
  title: Video-Internet Archive-MP4
  type: Video
  uid: 144589ba184d8f05bc1a8f490951cd03
inline_embed_id: 6369720memoryaccess25644409289
layout: video
order_index: null
parent_uid: 26dd20cb47d1eafab7639c5ebfa86c52
related_resources_text: ''
short_url: memory-access-2-56-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v7/memory-access-2-56-
template_type: Embed
title: Memory Access (2:56)
transcript: <p><span m='1520'>Now</span> <span m='1824'>let's</span> <span m='2128'>turn</span>
  <span m='2432'>our</span> <span m='2736'>attention</span> <span m='3040'>to</span>
  <span m='3344'>the</span> <span m='3648'>second</span> <span m='3952'>class</span>
  <span m='4256'>of</span> <span m='4560'>instructions:</span> <span m='4864'>load</span>
  <span m='5168'>(LD)</span> <span m='5472'>and</span> <span m='5776'>store</span>
  <span m='6080'>(ST),</span> <span m='6460'>which</span> <span m='6840'>allow</span>
  <span m='7220'>the</span> <span m='7600'>CPU</span> <span m='7980'>to</span> <span
  m='8360'>access</span> <span m='8740'>values</span> <span m='9120'>in</span> <span
  m='9500'>memory.</span> </p><p><span m='9880'>Note</span> <span m='10272'>that</span>
  <span m='10665'>since</span> <span m='11058'>the</span> <span m='11450'>Beta</span>
  <span m='11843'>is</span> <span m='12236'>a</span> <span m='12628'>load-store</span>
  <span m='13021'>architecture</span> <span m='13414'>these</span> <span m='13806'>instructions</span>
  <span m='14199'>are</span> <span m='14592'>the</span> <span m='14984'>*only*</span>
  <span m='15377'>mechanism</span> <span m='15770'>for</span> <span m='16460'>accessing</span>
  <span m='17150'>memory</span> <span m='17840'>values.</span> </p><p><span m='18530'>The</span>
  <span m='18964'>LD</span> <span m='19398'>and</span> <span m='19832'>ST</span> <span
  m='20267'>instructions</span> <span m='20701'>use</span> <span m='21135'>the</span>
  <span m='21570'>same</span> <span m='22004'>instruction</span> <span m='22438'>template</span>
  <span m='22872'>as</span> <span m='23307'>the</span> <span m='23741'>ALU-with-constant</span>
  <span m='24175'>instructions.</span> </p><p><span m='24610'>To</span> <span m='24908'>access</span>
  <span m='25206'>memory,</span> <span m='25504'>we'll</span> <span m='25802'>need</span>
  <span m='26101'>a</span> <span m='26399'>memory</span> <span m='26697'>address,</span>
  <span m='26995'>which</span> <span m='27294'>is</span> <span m='27592'>computed</span>
  <span m='27890'>by</span> <span m='28188'>adding</span> <span m='28487'>the</span>
  <span m='28785'>value</span> <span m='29083'>of</span> <span m='29381'>the</span>
  <span m='29680'>"ra"</span> <span m='30099'>register</span> <span m='30518'>to</span>
  <span m='30937'>the</span> <span m='31357'>sign-extended</span> <span m='31776'>16-bit</span>
  <span m='32195'>constant</span> <span m='32615'>from</span> <span m='33034'>the</span>
  <span m='33453'>low-order</span> <span m='33872'>16</span> <span m='34292'>bits</span>
  <span m='34711'>of</span> <span m='35130'>the</span> <span m='35550'>instruction.</span>
  </p><p><span m='37190'>This</span> <span m='37479'>computation</span> <span m='37769'>is</span>
  <span m='38059'>exactly</span> <span m='38349'>the</span> <span m='38639'>one</span>
  <span m='38929'>performed</span> <span m='39219'>by</span> <span m='39509'>the</span>
  <span m='39799'>ADDC</span> <span m='40089'>instruction</span> <span m='40379'>-</span>
  <span m='40669'>so</span> <span m='40959'>we'll</span> <span m='41249'>reuse</span>
  <span m='41539'>that</span> <span m='41829'>hardware</span> <span m='42142'>-</span>
  <span m='42456'>and</span> <span m='42770'>the</span> <span m='43083'>sum</span>
  <span m='43397'>is</span> <span m='43711'>sent</span> <span m='44025'>to</span>
  <span m='44338'>main</span> <span m='44652'>memory</span> <span m='44966'>as</span>
  <span m='45280'>the</span> <span m='45593'>byte</span> <span m='45907'>address</span>
  <span m='46221'>of</span> <span m='46535'>the</span> <span m='46848'>location</span>
  <span m='47162'>to</span> <span m='47476'>be</span> <span m='47790'>accessed.</span>
  </p><p><span m='48790'>For</span> <span m='49149'>the</span> <span m='49508'>LD</span>
  <span m='49868'>instruction,</span> <span m='50227'>the</span> <span m='50586'>data</span>
  <span m='50946'>returned</span> <span m='51305'>by</span> <span m='51665'>main</span>
  <span m='52024'>memory</span> <span m='52383'>is</span> <span m='52743'>written</span>
  <span m='53102'>to</span> <span m='53461'>the</span> <span m='53821'>"rc"</span>
  <span m='54180'>register.</span> </p><p><span m='54540'>The</span> <span m='54867'>store</span>
  <span m='55195'>instruction</span> <span m='55523'>(ST)</span> <span m='55851'>performs</span>
  <span m='56179'>the</span> <span m='56507'>same</span> <span m='56835'>address</span>
  <span m='57162'>calculation</span> <span m='57490'>as</span> <span m='57818'>LD,</span>
  <span m='58146'>then</span> <span m='58474'>reads</span> <span m='58802'>the</span>
  <span m='59130'>data</span> <span m='59600'>value</span> <span m='60071'>from</span>
  <span m='60542'>the</span> <span m='61013'>"rc"</span> <span m='61484'>register</span>
  <span m='61955'>and</span> <span m='62425'>sends</span> <span m='62896'>both</span>
  <span m='63367'>to</span> <span m='63838'>main</span> <span m='64309'>memory.</span>
  </p><p><span m='64780'>The</span> <span m='65086'>ST</span> <span m='65392'>instruction</span>
  <span m='65698'>is</span> <span m='66004'>special</span> <span m='66310'>in</span>
  <span m='66617'>several</span> <span m='66923'>ways:</span> <span m='67229'>it's</span>
  <span m='67535'>the</span> <span m='67841'>only</span> <span m='68148'>instruction</span>
  <span m='68454'>that</span> <span m='68760'>needs</span> <span m='69066'>to</span>
  <span m='69372'>read</span> <span m='69679'>the</span> <span m='69952'>value</span>
  <span m='70226'>of</span> <span m='70500'>the</span> <span m='70774'>"rc"</span>
  <span m='71048'>register,</span> <span m='71321'>so</span> <span m='71595'>we'll</span>
  <span m='71869'>need</span> <span m='72143'>to</span> <span m='72417'>adjust</span>
  <span m='72690'>the</span> <span m='72964'>datapath</span> <span m='73238'>hardware</span>
  <span m='73512'>slightly</span> <span m='73786'>to</span> <span m='74060'>accommodate</span>
  <span m='74456'>that</span> <span m='74853'>need.</span> </p><p><span m='75250'>And</span>
  <span m='75572'>since</span> <span m='75895'>"rc"</span> <span m='76218'>is</span>
  <span m='76541'>serving</span> <span m='76863'>as</span> <span m='77186'>a</span>
  <span m='77509'>source</span> <span m='77832'>operand,</span> <span m='78155'>it</span>
  <span m='78477'>appears</span> <span m='78800'>as</span> <span m='79123'>the</span>
  <span m='79446'>first</span> <span m='79768'>operand</span> <span m='80091'>in</span>
  <span m='80414'>the</span> <span m='80737'>symbolic</span> <span m='81060'>form</span>
  <span m='81430'>of</span> <span m='81801'>the</span> <span m='82171'>instruction,</span>
  <span m='82542'>followed</span> <span m='82913'>by</span> <span m='83283'>"const"</span>
  <span m='83654'>and</span> <span m='84025'>"ra"</span> <span m='84395'>which</span>
  <span m='84766'>are</span> <span m='85137'>specifying</span> <span m='85507'>the</span>
  <span m='85878'>destination</span> <span m='86249'>address.</span> </p><p><span
  m='87249'>ST</span> <span m='87548'>is</span> <span m='87848'>the</span> <span m='88148'>only</span>
  <span m='88448'>instruction</span> <span m='88748'>that</span> <span m='89048'>does</span>
  <span m='89348'>*not*</span> <span m='89648'>write</span> <span m='89948'>a</span>
  <span m='90248'>result</span> <span m='90548'>into</span> <span m='90848'>the</span>
  <span m='91148'>register</span> <span m='91448'>file</span> <span m='91748'>at</span>
  <span m='92048'>end</span> <span m='92348'>of</span> <span m='93095'>the</span>
  <span m='93842'>instruction.</span> </p><p><span m='94590'>Here's</span> <span m='94853'>the</span>
  <span m='95116'>example</span> <span m='95380'>we</span> <span m='95643'>saw</span>
  <span m='95907'>earlier,</span> <span m='96170'>where</span> <span m='96434'>we</span>
  <span m='96697'>needed</span> <span m='96961'>to</span> <span m='97224'>load</span>
  <span m='97488'>the</span> <span m='97751'>value</span> <span m='98015'>of</span>
  <span m='98278'>the</span> <span m='98542'>variable</span> <span m='98805'>x</span>
  <span m='99069'>from</span> <span m='99389'>memory,</span> <span m='99709'>multiply</span>
  <span m='100029'>it</span> <span m='100349'>by</span> <span m='100669'>37</span>
  <span m='100989'>and</span> <span m='101309'>write</span> <span m='101629'>the</span>
  <span m='101949'>result</span> <span m='102269'>back</span> <span m='102589'>to</span>
  <span m='102909'>the</span> <span m='103229'>memory</span> <span m='103549'>location</span>
  <span m='103869'>that</span> <span m='104189'>holds</span> <span m='104509'>the</span>
  <span m='104962'>value</span> <span m='105415'>of</span> <span m='105869'>the</span>
  <span m='106322'>variable</span> <span m='106775'>y.</span> </p><p><span m='107229'>Now</span>
  <span m='107536'>that</span> <span m='107843'>we</span> <span m='108150'>have</span>
  <span m='108457'>actual</span> <span m='108764'>Beta</span> <span m='109071'>instructions,</span>
  <span m='109379'>we've</span> <span m='109686'>expressed</span> <span m='109993'>the</span>
  <span m='110300'>computation</span> <span m='110607'>as</span> <span m='110914'>a</span>
  <span m='111221'>sequence</span> <span m='111529'>of</span> <span m='112122'>three</span>
  <span m='112716'>instructions.</span> </p><p><span m='113310'>To</span> <span m='113624'>access</span>
  <span m='113938'>the</span> <span m='114252'>value</span> <span m='114566'>of</span>
  <span m='114880'>variable</span> <span m='115194'>x,</span> <span m='115508'>the</span>
  <span m='115822'>LD</span> <span m='116136'>instruction</span> <span m='116450'>adds</span>
  <span m='116764'>the</span> <span m='117078'>contents</span> <span m='117392'>of</span>
  <span m='117706'>R31</span> <span m='118020'>to</span> <span m='118334'>the</span>
  <span m='118649'>constant</span> <span m='119179'>0x1008,</span> <span m='119710'>which</span>
  <span m='120241'>sums</span> <span m='120772'>to</span> <span m='121303'>0x1008,</span>
  <span m='121834'>the</span> <span m='122365'>address</span> <span m='122896'>we</span>
  <span m='123427'>need</span> <span m='123958'>to</span> <span m='124489'>access.</span>
  </p><p><span m='125020'>The</span> <span m='125340'>ST</span> <span m='125660'>instruction</span>
  <span m='125980'>specifies</span> <span m='126300'>a</span> <span m='126620'>similar</span>
  <span m='126940'>address</span> <span m='127260'>calculation</span> <span m='127580'>to</span>
  <span m='127900'>write</span> <span m='128220'>into</span> <span m='128540'>the</span>
  <span m='128860'>location</span> <span m='129180'>for</span> <span m='129500'>the</span>
  <span m='130526'>variable</span> <span m='131553'>y.</span> </p><p><span m='132580'>The</span>
  <span m='132844'>address</span> <span m='133108'>calculation</span> <span m='133373'>performed</span>
  <span m='133637'>by</span> <span m='133901'>LD</span> <span m='134166'>and</span>
  <span m='134430'>ST</span> <span m='134695'>works</span> <span m='134959'>well</span>
  <span m='135223'>when</span> <span m='135488'>the</span> <span m='135752'>locations</span>
  <span m='136016'>we</span> <span m='136281'>need</span> <span m='136545'>to</span>
  <span m='136810'>access</span> <span m='137321'>have</span> <span m='137832'>addresses</span>
  <span m='138343'>that</span> <span m='138854'>fit</span> <span m='139365'>into</span>
  <span m='139876'>the</span> <span m='140387'>16-bit</span> <span m='140898'>constant</span>
  <span m='141409'>field.</span> </p><p><span m='141920'>What</span> <span m='142400'>happens</span>
  <span m='142881'>when</span> <span m='143362'>we</span> <span m='143843'>need</span>
  <span m='144323'>to</span> <span m='144804'>access</span> <span m='145285'>locations</span>
  <span m='145766'>at</span> <span m='146246'>addresses</span> <span m='146727'>higher</span>
  <span m='147208'>than</span> <span m='147689'>0x7FFF?</span> </p><p><span m='148170'>Then</span>
  <span m='148433'>we</span> <span m='148696'>need</span> <span m='148959'>to</span>
  <span m='149222'>treat</span> <span m='149485'>those</span> <span m='149748'>addresses</span>
  <span m='150011'>as</span> <span m='150275'>we</span> <span m='150538'>would</span>
  <span m='150801'>any</span> <span m='151064'>large</span> <span m='151327'>constant,</span>
  <span m='151590'>and</span> <span m='151853'>store</span> <span m='152116'>those</span>
  <span m='152380'>large</span> <span m='152630'>addresses</span> <span m='152881'>in</span>
  <span m='153131'>main</span> <span m='153382'>memory</span> <span m='153632'>so</span>
  <span m='153883'>they</span> <span m='154133'>can</span> <span m='154384'>be</span>
  <span m='154635'>loaded</span> <span m='154885'>into</span> <span m='155136'>a</span>
  <span m='155386'>register</span> <span m='155637'>to</span> <span m='155887'>be</span>
  <span m='156138'>used</span> <span m='156388'>by</span> <span m='156639'>LD</span>
  <span m='156890'>and</span> <span m='157525'>ST.</span> </p><p><span m='158160'>Okay,</span>
  <span m='158442'>but</span> <span m='158725'>what</span> <span m='159008'>if</span>
  <span m='159291'>the</span> <span m='159573'>number</span> <span m='159856'>of</span>
  <span m='160139'>large</span> <span m='160422'>constants</span> <span m='160705'>we</span>
  <span m='160987'>need</span> <span m='161270'>to</span> <span m='161553'>store</span>
  <span m='161836'>is</span> <span m='162118'>greater</span> <span m='162401'>than</span>
  <span m='162684'>will</span> <span m='162967'>fit</span> <span m='163250'>in</span>
  <span m='163731'>low</span> <span m='164212'>memory,</span> <span m='164693'>i.e.,</span>
  <span m='165174'>the</span> <span m='165655'>addresses</span> <span m='166136'>we</span>
  <span m='166617'>can</span> <span m='167098'>access</span> <span m='167579'>directly?</span>
  </p><p><span m='168060'>To</span> <span m='168440'>solve</span> <span m='168821'>this</span>
  <span m='169202'>problem,</span> <span m='169582'>the</span> <span m='169963'>Beta</span>
  <span m='170344'>includes</span> <span m='170725'>a</span> <span m='171105'>"load</span>
  <span m='171486'>relative"</span> <span m='171867'>(LDR)</span> <span m='172247'>instruction,</span>
  <span m='172628'>which</span> <span m='173009'>we'll</span> <span m='173390'>see</span>
  <span m='173673'>in</span> <span m='173957'>the</span> <span m='174241'>lecture</span>
  <span m='174525'>on</span> <span m='174808'>the</span> <span m='175092'>Beta</span>
  <span m='175376'>implementation.</span> </p>
type: course
uid: ff9486a26cc854378285d6116fa12db0

---
None