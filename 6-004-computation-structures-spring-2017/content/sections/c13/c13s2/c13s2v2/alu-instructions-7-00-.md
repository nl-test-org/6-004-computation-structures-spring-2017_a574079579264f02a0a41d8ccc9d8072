---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 0Q6kYWnhaks
  parent_uid: b438f26843085100771e081aa5e6d2e0
  title: Video-YouTube-Stream
  type: Video
  uid: a6930f3e92602363d9fd8da05d080e64
- id: 3Play-3Play YouTube id-Stream
  media_location: 0Q6kYWnhaks
  parent_uid: b438f26843085100771e081aa5e6d2e0
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 5d0e6cb453dcad71fb68dc5a36e086ef
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/0Q6kYWnhaks/default.jpg
  parent_uid: b438f26843085100771e081aa5e6d2e0
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: cd4bd8a0e010f8ceec8df7266392d9aa
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_13-02-02_300k.mp4
  parent_uid: b438f26843085100771e081aa5e6d2e0
  title: Video-Internet Archive-MP4
  type: Video
  uid: d0655b44d88b2035bc244ab37152136d
- id: 0Q6kYWnhaks.srt
  parent_uid: b438f26843085100771e081aa5e6d2e0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v2/alu-instructions-7-00-/0Q6kYWnhaks.srt
  title: 3play caption file
  type: null
  uid: f81f266aa3a44c7ce4382113b9336c17
- id: 0Q6kYWnhaks.pdf
  parent_uid: b438f26843085100771e081aa5e6d2e0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v2/alu-instructions-7-00-/0Q6kYWnhaks.pdf
  title: 3play pdf file
  type: null
  uid: a3400963a6fd5e7c1737c08fd3af4623
- id: Caption-3Play YouTube id-SRT
  parent_uid: b438f26843085100771e081aa5e6d2e0
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 396b7e3367e16297955080fe59b91d6e
- id: Transcript-3Play YouTube id-PDF
  parent_uid: b438f26843085100771e081aa5e6d2e0
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: a9eb39e943f048add307aa2e46675591
inline_embed_id: 19345734aluinstructions70039699583
layout: video
order_index: null
parent_uid: d217b8d081b2a45dd6469899f683800c
related_resources_text: ''
short_url: alu-instructions-7-00-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v2/alu-instructions-7-00-
template_type: Embed
title: ALU Instructions (7:00)
transcript: <p><span m='459'>Our</span> <span m='782'>first</span> <span m='1106'>task</span>
  <span m='1430'>is</span> <span m='1754'>to</span> <span m='2078'>work</span> <span
  m='2401'>on</span> <span m='2725'>the</span> <span m='3049'>datapath</span> <span
  m='3373'>logic</span> <span m='3697'>needed</span> <span m='4020'>to</span> <span
  m='4344'>execute</span> <span m='4668'>ALU</span> <span m='4992'>instructions</span>
  <span m='5316'>with</span> <span m='5640'>two</span> <span m='6436'>register</span>
  <span m='7232'>operands.</span> </p><p><span m='8029'>Each</span> <span m='8447'>instruction</span>
  <span m='8866'>requires</span> <span m='9285'>the</span> <span m='9703'>same</span>
  <span m='10122'>processing</span> <span m='10541'>steps:</span> <span m='10960'>Fetch,</span>
  <span m='11308'>where</span> <span m='11657'>the</span> <span m='12005'>32-bit</span>
  <span m='12354'>encoded</span> <span m='12702'>instruction</span> <span m='13051'>is</span>
  <span m='13400'>read</span> <span m='13748'>from</span> <span m='14097'>main</span>
  <span m='14445'>memory</span> <span m='14794'>from</span> <span m='15142'>the</span>
  <span m='15491'>location</span> <span m='15840'>specified</span> <span m='16286'>by</span>
  <span m='16733'>the</span> <span m='17179'>program</span> <span m='17626'>counter</span>
  <span m='18072'>(PC).</span> </p><p><span m='18519'>Decode,</span> <span m='19015'>where</span>
  <span m='19512'>the</span> <span m='20008'>opcode</span> <span m='20505'>field</span>
  <span m='21001'>(instruction</span> <span m='21498'>bits</span> <span m='21994'>[31:26])</span>
  <span m='22491'>is</span> <span m='22987'>used</span> <span m='23484'>to</span>
  <span m='23980'>determine</span> <span m='24477'>the</span> <span m='24973'>values</span>
  <span m='25470'>for</span> <span m='25961'>the</span> <span m='26453'>datapath</span>
  <span m='26945'>control</span> <span m='27437'>signals.</span> </p><p><span m='27929'>Read,</span>
  <span m='28345'>where</span> <span m='28762'>the</span> <span m='29179'>contents</span>
  <span m='29595'>of</span> <span m='30012'>the</span> <span m='30429'>registers</span>
  <span m='30846'>specified</span> <span m='31262'>by</span> <span m='31679'>the</span>
  <span m='32096'>RA</span> <span m='32513'>and</span> <span m='32929'>RB</span> <span
  m='33346'>fields</span> <span m='33763'>(instruction</span> <span m='34180'>bits</span>
  <span m='34694'>[20:16]</span> <span m='35209'>and</span> <span m='35724'>[15:11])</span>
  <span m='36239'>are</span> <span m='36754'>read</span> <span m='37269'>from</span>
  <span m='37784'>the</span> <span m='38299'>register</span> <span m='38814'>file.</span>
  </p><p><span m='39329'>Execute,</span> <span m='39726'>where</span> <span m='40124'>the</span>
  <span m='40521'>requested</span> <span m='40919'>operation</span> <span m='41316'>is</span>
  <span m='41714'>performed</span> <span m='42112'>on</span> <span m='42509'>the</span>
  <span m='42907'>two</span> <span m='43304'>operand</span> <span m='43702'>values.</span>
  </p><p><span m='44100'>We'll</span> <span m='44455'>also</span> <span m='44810'>need</span>
  <span m='45166'>to</span> <span m='45521'>compute</span> <span m='45877'>the</span>
  <span m='46232'>next</span> <span m='46588'>value</span> <span m='46943'>for</span>
  <span m='47299'>the</span> <span m='47654'>PC.</span> </p><p><span m='48010'>And</span>
  <span m='48317'>Write-back,</span> <span m='48625'>where</span> <span m='48932'>the</span>
  <span m='49240'>result</span> <span m='49548'>of</span> <span m='49855'>the</span>
  <span m='50163'>operation</span> <span m='50471'>is</span> <span m='50778'>written</span>
  <span m='51086'>to</span> <span m='51394'>the</span> <span m='51701'>register</span>
  <span m='52009'>file</span> <span m='52317'>in</span> <span m='52624'>the</span>
  <span m='52932'>register</span> <span m='53240'>specified</span> <span m='53947'>by</span>
  <span m='54655'>the</span> <span m='55362'>RC</span> <span m='56070'>field</span>
  <span m='56777'>(instruction</span> <span m='57485'>bits</span> <span m='58192'>[25:21]).</span>
  </p><p><span m='58900'>The</span> <span m='59231'>system's</span> <span m='59562'>clock</span>
  <span m='59894'>signal</span> <span m='60225'>is</span> <span m='60556'>connected</span>
  <span m='60888'>to</span> <span m='61219'>the</span> <span m='61550'>register</span>
  <span m='61882'>file</span> <span m='62213'>and</span> <span m='62544'>the</span>
  <span m='62876'>PC</span> <span m='63207'>register.</span> </p><p><span m='63539'>At</span>
  <span m='63853'>the</span> <span m='64168'>rising</span> <span m='64483'>edge</span>
  <span m='64798'>of</span> <span m='65112'>the</span> <span m='65427'>clock,</span>
  <span m='65742'>the</span> <span m='66057'>new</span> <span m='66371'>values</span>
  <span m='66686'>computed</span> <span m='67001'>during</span> <span m='67316'>the</span>
  <span m='67630'>Execute</span> <span m='67945'>phase</span> <span m='68260'>are</span>
  <span m='68575'>written</span> <span m='68890'>to</span> <span m='69630'>these</span>
  <span m='70370'>registers.</span> </p><p><span m='71110'>The</span> <span m='71443'>rising</span>
  <span m='71776'>clock</span> <span m='72110'>edge</span> <span m='72443'>thus</span>
  <span m='72776'>marks</span> <span m='73110'>the</span> <span m='73443'>end</span>
  <span m='73776'>of</span> <span m='74110'>execution</span> <span m='74443'>for</span>
  <span m='74776'>the</span> <span m='75110'>current</span> <span m='75443'>instruction</span>
  <span m='75776'>and</span> <span m='76110'>the</span> <span m='76502'>beginning</span>
  <span m='76895'>of</span> <span m='77287'>execution</span> <span m='77680'>for</span>
  <span m='78072'>the</span> <span m='78465'>next</span> <span m='78857'>instruction.</span>
  </p><p><span m='79250'>The</span> <span m='79534'>period</span> <span m='79819'>of</span>
  <span m='80104'>the</span> <span m='80388'>clock,</span> <span m='80673'>i.e.,</span>
  <span m='80958'>the</span> <span m='81242'>time</span> <span m='81527'>between</span>
  <span m='81812'>rising</span> <span m='82097'>clock</span> <span m='82381'>edges,</span>
  <span m='82666'>needs</span> <span m='82951'>to</span> <span m='83235'>be</span>
  <span m='83520'>long</span> <span m='83805'>enough</span> <span m='84090'>to</span>
  <span m='84507'>accommodate</span> <span m='84925'>the</span> <span m='85343'>cumulative</span>
  <span m='85761'>propagation</span> <span m='86178'>delay</span> <span m='86596'>of</span>
  <span m='87014'>the</span> <span m='87432'>logic</span> <span m='87850'>that</span>
  <span m='88267'>implements</span> <span m='88685'>the</span> <span m='89103'>5</span>
  <span m='89521'>steps</span> <span m='89939'>described</span> <span m='91109'>here.</span>
  </p><p><span m='92280'>Since</span> <span m='92584'>one</span> <span m='92889'>instruction</span>
  <span m='93194'>is</span> <span m='93498'>executed</span> <span m='93803'>each</span>
  <span m='94108'>clock</span> <span m='94412'>cycle,</span> <span m='94717'>the</span>
  <span m='95022'>frequency</span> <span m='95326'>of</span> <span m='95631'>the</span>
  <span m='95936'>clock</span> <span m='96240'>tells</span> <span m='96545'>us</span>
  <span m='96850'>the</span> <span m='97284'>rate</span> <span m='97718'>at</span>
  <span m='98152'>which</span> <span m='98587'>instructions</span> <span m='99021'>are</span>
  <span m='99455'>executed.</span> </p><p><span m='99890'>If</span> <span m='100259'>the</span>
  <span m='100628'>clock</span> <span m='100998'>period</span> <span m='101367'>was</span>
  <span m='101736'>10ns,</span> <span m='102106'>the</span> <span m='102475'>clock</span>
  <span m='102844'>frequency</span> <span m='103214'>would</span> <span m='103583'>be</span>
  <span m='103953'>100</span> <span m='104322'>MHz</span> <span m='104691'>and</span>
  <span m='105061'>our</span> <span m='105430'>Beta</span> <span m='105799'>would</span>
  <span m='106169'>be</span> <span m='106538'>executing</span> <span m='106908'>instructions</span>
  <span m='107753'>at</span> <span m='108598'>100</span> <span m='109443'>MIPS!</span>
  </p><p><span m='110289'>Here's</span> <span m='110637'>a</span> <span m='110986'>sketch</span>
  <span m='111334'>showing</span> <span m='111683'>the</span> <span m='112031'>hardware</span>
  <span m='112380'>needed</span> <span m='112728'>for</span> <span m='113077'>the</span>
  <span m='113425'>Fetch</span> <span m='113774'>and</span> <span m='114122'>Decode</span>
  <span m='114471'>steps.</span> </p><p><span m='114820'>The</span> <span m='115098'>current</span>
  <span m='115377'>value</span> <span m='115656'>of</span> <span m='115935'>the</span>
  <span m='116214'>PC</span> <span m='116493'>register</span> <span m='116772'>is</span>
  <span m='117051'>routed</span> <span m='117330'>to</span> <span m='117609'>main</span>
  <span m='117888'>memory</span> <span m='118167'>as</span> <span m='118446'>the</span>
  <span m='118725'>address</span> <span m='119004'>of</span> <span m='119283'>the</span>
  <span m='119562'>instruction</span> <span m='119841'>to</span> <span m='120557'>be</span>
  <span m='121273'>fetched.</span> </p><p><span m='121990'>For</span> <span m='122276'>ALU</span>
  <span m='122562'>instructions,</span> <span m='122848'>the</span> <span m='123135'>address</span>
  <span m='123421'>of</span> <span m='123707'>the</span> <span m='123993'>next</span>
  <span m='124280'>instruction</span> <span m='124566'>is</span> <span m='124852'>simply</span>
  <span m='125138'>the</span> <span m='125425'>address</span> <span m='125711'>of</span>
  <span m='125997'>the</span> <span m='126283'>current</span> <span m='126570'>instruction</span>
  <span m='127196'>plus</span> <span m='127822'>4.</span> </p><p><span m='128449'>There's</span>
  <span m='128853'>an</span> <span m='129257'>adder</span> <span m='129662'>dedicated</span>
  <span m='130066'>to</span> <span m='130470'>performing</span> <span m='130875'>the</span>
  <span m='131279'>"PC+4"</span> <span m='131683'>computation</span> <span m='132088'>and</span>
  <span m='132492'>that</span> <span m='132896'>value</span> <span m='133301'>is</span>
  <span m='133705'>routed</span> <span m='134110'>back</span> <span m='134473'>to</span>
  <span m='134837'>be</span> <span m='135200'>used</span> <span m='135564'>as</span>
  <span m='135928'>the</span> <span m='136291'>next</span> <span m='136655'>value</span>
  <span m='137019'>of</span> <span m='137382'>the</span> <span m='137746'>PC.</span>
  </p><p><span m='138110'>We've</span> <span m='138424'>also</span> <span m='138738'>included</span>
  <span m='139053'>a</span> <span m='139367'>MUX</span> <span m='139682'>used</span>
  <span m='139996'>to</span> <span m='140311'>select</span> <span m='140625'>the</span>
  <span m='140940'>initial</span> <span m='141254'>value</span> <span m='141568'>for</span>
  <span m='141883'>the</span> <span m='142197'>PC</span> <span m='142512'>when</span>
  <span m='142826'>the</span> <span m='143141'>RESET</span> <span m='143455'>signal</span>
  <span m='143770'>is</span> <span m='144650'>1.</span> </p><p><span m='145530'>After</span>
  <span m='145992'>the</span> <span m='146454'>memory</span> <span m='146916'>propagation</span>
  <span m='147378'>delay,</span> <span m='147840'>the</span> <span m='148302'>instruction</span>
  <span m='148765'>bits</span> <span m='149227'>(ID[31:0])</span> <span m='149689'>are</span>
  <span m='150151'>available</span> <span m='150613'>and</span> <span m='151075'>the</span>
  <span m='151537'>processing</span> <span m='152000'>steps</span> <span m='152766'>can</span>
  <span m='153533'>begin.</span> </p><p><span m='154300'>Some</span> <span m='154629'>of</span>
  <span m='154958'>the</span> <span m='155287'>instruction</span> <span m='155616'>fields</span>
  <span m='155945'>can</span> <span m='156274'>be</span> <span m='156603'>used</span>
  <span m='156932'>directly</span> <span m='157261'>as-is.</span> </p><p><span m='157590'>To</span>
  <span m='157885'>determine</span> <span m='158180'>the</span> <span m='158475'>values</span>
  <span m='158770'>for</span> <span m='159065'>other</span> <span m='159360'>control</span>
  <span m='159655'>signals,</span> <span m='159950'>we'll</span> <span m='160245'>need</span>
  <span m='160540'>some</span> <span m='160835'>logic</span> <span m='161130'>that</span>
  <span m='161425'>computes</span> <span m='161720'>their</span> <span m='162110'>values</span>
  <span m='162500'>from</span> <span m='162890'>the</span> <span m='163280'>bits</span>
  <span m='163670'>of</span> <span m='164060'>the</span> <span m='164450'>opcode</span>
  <span m='164840'>field.</span> </p><p><span m='165230'>Now</span> <span m='165588'>let's</span>
  <span m='165947'>fill</span> <span m='166306'>in</span> <span m='166664'>the</span>
  <span m='167023'>datapath</span> <span m='167382'>logic</span> <span m='167740'>needed</span>
  <span m='168099'>to</span> <span m='168458'>execute</span> <span m='168816'>ALU</span>
  <span m='169175'>instructions</span> <span m='169534'>with</span> <span m='169892'>two</span>
  <span m='170251'>register</span> <span m='170610'>operands.</span> </p><p><span
  m='171900'>The</span> <span m='172248'>instruction</span> <span m='172597'>bits</span>
  <span m='172946'>for</span> <span m='173295'>the</span> <span m='173643'>5-bit</span>
  <span m='173992'>RA,</span> <span m='174341'>RB</span> <span m='174690'>and</span>
  <span m='175038'>RC</span> <span m='175387'>fields</span> <span m='175736'>can</span>
  <span m='176085'>be</span> <span m='176433'>connected</span> <span m='176782'>directly</span>
  <span m='177131'>to</span> <span m='177480'>the</span> <span m='177917'>appropriate</span>
  <span m='178355'>address</span> <span m='178792'>inputs</span> <span m='179230'>of</span>
  <span m='179667'>the</span> <span m='180105'>register</span> <span m='180542'>file.</span>
  </p><p><span m='180980'>The</span> <span m='181297'>RA</span> <span m='181615'>and</span>
  <span m='181933'>RB</span> <span m='182251'>fields</span> <span m='182568'>supply</span>
  <span m='182886'>the</span> <span m='183204'>addresses</span> <span m='183522'>for</span>
  <span m='183840'>the</span> <span m='184157'>two</span> <span m='184475'>read</span>
  <span m='184793'>ports</span> <span m='185111'>and</span> <span m='185428'>the</span>
  <span m='185746'>RC</span> <span m='186064'>field</span> <span m='186382'>supplies</span>
  <span m='186700'>the</span> <span m='187093'>address</span> <span m='187486'>for</span>
  <span m='187880'>the</span> <span m='188273'>write</span> <span m='188666'>port.</span>
  </p><p><span m='189060'>The</span> <span m='189298'>outputs</span> <span m='189536'>of</span>
  <span m='189774'>the</span> <span m='190012'>read</span> <span m='190250'>data</span>
  <span m='190488'>ports</span> <span m='190726'>are</span> <span m='190964'>routed</span>
  <span m='191202'>to</span> <span m='191440'>the</span> <span m='191678'>inputs</span>
  <span m='191916'>of</span> <span m='192154'>the</span> <span m='192392'>ALU</span>
  <span m='192630'>to</span> <span m='192868'>serve</span> <span m='193106'>as</span>
  <span m='193344'>the</span> <span m='193582'>two</span> <span m='193820'>operands.</span>
  </p><p><span m='195360'>The</span> <span m='195780'>ALUFN</span> <span m='196200'>control</span>
  <span m='196620'>signals</span> <span m='197040'>tell</span> <span m='197460'>the</span>
  <span m='197880'>ALU</span> <span m='198300'>what</span> <span m='198720'>operation</span>
  <span m='199140'>to</span> <span m='199560'>perform.</span> </p><p><span m='199980'>These</span>
  <span m='200342'>control</span> <span m='200704'>signals</span> <span m='201066'>are</span>
  <span m='201428'>determined</span> <span m='201790'>by</span> <span m='202152'>the</span>
  <span m='202515'>control</span> <span m='202877'>logic</span> <span m='203239'>from</span>
  <span m='203601'>the</span> <span m='203963'>6-bit</span> <span m='204325'>opcode</span>
  <span m='204687'>field.</span> </p><p><span m='205050'>For</span> <span m='205475'>specificity,</span>
  <span m='205900'>let's</span> <span m='206325'>assume</span> <span m='206750'>that</span>
  <span m='207175'>the</span> <span m='207600'>control</span> <span m='208025'>logic</span>
  <span m='208450'>is</span> <span m='208875'>implemented</span> <span m='209300'>using</span>
  <span m='209725'>a</span> <span m='210150'>read-only</span> <span m='210575'>memory</span>
  <span m='211000'>(ROM),</span> <span m='211340'>where</span> <span m='211680'>the</span>
  <span m='212020'>opcode</span> <span m='212360'>bits</span> <span m='212700'>are</span>
  <span m='213040'>used</span> <span m='213380'>as</span> <span m='213720'>the</span>
  <span m='214060'>ROM's</span> <span m='214400'>address</span> <span m='214740'>and</span>
  <span m='215080'>the</span> <span m='215420'>ROM's</span> <span m='215760'>outputs</span>
  <span m='216100'>are</span> <span m='216440'>the</span> <span m='216780'>control</span>
  <span m='217615'>signals.</span> </p><p><span m='218450'>Since</span> <span m='218870'>there</span>
  <span m='219291'>are</span> <span m='219712'>6</span> <span m='220132'>opcode</span>
  <span m='220553'>bits,</span> <span m='220974'>we'll</span> <span m='221394'>need</span>
  <span m='221815'>2^6</span> <span m='222236'>=</span> <span m='222656'>64</span>
  <span m='223077'>locations</span> <span m='223498'>in</span> <span m='223918'>the</span>
  <span m='224339'>ROM.</span> </p><p><span m='224760'>We'll</span> <span m='225098'>program</span>
  <span m='225437'>the</span> <span m='225776'>contents</span> <span m='226115'>of</span>
  <span m='226453'>the</span> <span m='226792'>ROM</span> <span m='227131'>to</span>
  <span m='227470'>supply</span> <span m='227808'>the</span> <span m='228147'>correct</span>
  <span m='228486'>control</span> <span m='228825'>signal</span> <span m='229163'>values</span>
  <span m='229502'>for</span> <span m='229841'>each</span> <span m='230180'>of</span>
  <span m='230968'>the</span> <span m='231756'>64</span> <span m='232544'>possible</span>
  <span m='233332'>opcodes.</span> </p><p><span m='234120'>The</span> <span m='234379'>output</span>
  <span m='234638'>of</span> <span m='234898'>the</span> <span m='235157'>ALU</span>
  <span m='235417'>is</span> <span m='235676'>routed</span> <span m='235936'>back</span>
  <span m='236195'>to</span> <span m='236455'>the</span> <span m='236714'>write</span>
  <span m='236974'>data</span> <span m='237233'>port</span> <span m='237493'>of</span>
  <span m='237752'>the</span> <span m='238012'>register</span> <span m='238271'>file,</span>
  <span m='238531'>to</span> <span m='238790'>be</span> <span m='239050'>written</span>
  <span m='239399'>into</span> <span m='239748'>the</span> <span m='240097'>RC</span>
  <span m='240446'>register</span> <span m='240795'>at</span> <span m='241144'>the</span>
  <span m='241493'>end</span> <span m='241842'>of</span> <span m='242191'>the</span>
  <span m='242540'>cycle.</span> </p><p><span m='242890'>We'll</span> <span m='243309'>need</span>
  <span m='243728'>another</span> <span m='244147'>control</span> <span m='244567'>signal,</span>
  <span m='244986'>WERF</span> <span m='245405'>("write-enable</span> <span m='245825'>register</span>
  <span m='246244'>file"),</span> <span m='246663'>that</span> <span m='247082'>should</span>
  <span m='247502'>have</span> <span m='247921'>the</span> <span m='248340'>value</span>
  <span m='248760'>1</span> <span m='249112'>when</span> <span m='249464'>we</span>
  <span m='249816'>want</span> <span m='250168'>to</span> <span m='250520'>write</span>
  <span m='250872'>into</span> <span m='251224'>the</span> <span m='251576'>RC</span>
  <span m='251928'>register.</span> </p><p><span m='252280'>Let</span> <span m='252579'>me</span>
  <span m='252879'>introduce</span> <span m='253179'>you</span> <span m='253479'>to</span>
  <span m='253779'>Werf,</span> <span m='254079'>the</span> <span m='254379'>6.004</span>
  <span m='254679'>mascot,</span> <span m='254979'>who,</span> <span m='255279'>of</span>
  <span m='255579'>course,</span> <span m='255879'>is</span> <span m='256179'>named</span>
  <span m='256479'>after</span> <span m='256779'>her</span> <span m='257079'>favorite</span>
  <span m='257379'>control</span> <span m='257978'>signal,</span> <span m='258578'>which</span>
  <span m='259178'>she's</span> <span m='259778'>constantly</span> <span m='260378'>mentioning.</span>
  </p><p><span m='260978'>Let's</span> <span m='261389'>follow</span> <span m='261801'>the</span>
  <span m='262213'>flow</span> <span m='262625'>of</span> <span m='263036'>data</span>
  <span m='263448'>as</span> <span m='263860'>we</span> <span m='264272'>execute</span>
  <span m='264683'>the</span> <span m='265095'>ALU</span> <span m='265507'>instruction.</span>
  </p><p><span m='265919'>After</span> <span m='266275'>the</span> <span m='266631'>instruction</span>
  <span m='266987'>has</span> <span m='267344'>been</span> <span m='267700'>fetched,</span>
  <span m='268056'>supplying</span> <span m='268413'>the</span> <span m='268769'>RA</span>
  <span m='269125'>and</span> <span m='269482'>RB</span> <span m='269838'>instruction</span>
  <span m='270194'>fields,</span> <span m='270551'>the</span> <span m='270907'>RA</span>
  <span m='271263'>and</span> <span m='271620'>RB</span> <span m='272020'>register</span>
  <span m='272420'>values</span> <span m='272820'>appear</span> <span m='273220'>on</span>
  <span m='273620'>the</span> <span m='274020'>read</span> <span m='274420'>data</span>
  <span m='274820'>ports</span> <span m='275220'>of</span> <span m='275620'>the</span>
  <span m='276020'>register</span> <span m='276420'>file.</span> </p><p><span m='276820'>The</span>
  <span m='277182'>control</span> <span m='277545'>logic</span> <span m='277908'>has</span>
  <span m='278271'>decoded</span> <span m='278634'>the</span> <span m='278997'>opcode</span>
  <span m='279360'>bits</span> <span m='279722'>and</span> <span m='280085'>supplied</span>
  <span m='280448'>the</span> <span m='280811'>appropriate</span> <span m='281174'>ALU</span>
  <span m='281537'>function</span> <span m='281900'>code.</span> </p><p><span m='282930'>You</span>
  <span m='283220'>can</span> <span m='283510'>find</span> <span m='283800'>a</span>
  <span m='284090'>listing</span> <span m='284380'>of</span> <span m='284670'>the</span>
  <span m='284960'>possible</span> <span m='285250'>function</span> <span m='285540'>codes</span>
  <span m='285830'>in</span> <span m='286120'>the</span> <span m='286410'>upper</span>
  <span m='286700'>right-hand</span> <span m='286990'>corner</span> <span m='287280'>of</span>
  <span m='287570'>the</span> <span m='287860'>Beta</span> <span m='288530'>Diagram</span>
  <span m='289200'>handout.</span> </p><p><span m='289870'>The</span> <span m='290141'>result</span>
  <span m='290413'>of</span> <span m='290685'>the</span> <span m='290957'>ALU's</span>
  <span m='291228'>computation</span> <span m='291500'>is</span> <span m='291772'>sent</span>
  <span m='292044'>back</span> <span m='292315'>to</span> <span m='292587'>the</span>
  <span m='292859'>register</span> <span m='293131'>file</span> <span m='293402'>to</span>
  <span m='293674'>be</span> <span m='293946'>written</span> <span m='294218'>into</span>
  <span m='294490'>the</span> <span m='294936'>RC</span> <span m='295383'>register.</span>
  </p><p><span m='295830'>Of</span> <span m='296152'>course,</span> <span m='296474'>we'll</span>
  <span m='296796'>need</span> <span m='297119'>to</span> <span m='297441'>set</span>
  <span m='297763'>WERF</span> <span m='298086'>to</span> <span m='298408'>1</span>
  <span m='298730'>to</span> <span m='299053'>enable</span> <span m='299375'>the</span>
  <span m='299697'>write.</span> </p><p><span m='300020'>5.oo</span> <span m='300433'>Here</span>
  <span m='300847'>we</span> <span m='301261'>see</span> <span m='301675'>one</span>
  <span m='302089'>of</span> <span m='302503'>the</span> <span m='302917'>major</span>
  <span m='303331'>advantages</span> <span m='303745'>of</span> <span m='304159'>a</span>
  <span m='304573'>reduced-instruction</span> <span m='304987'>set</span> <span m='305401'>computer</span>
  <span m='305815'>architecture:</span> <span m='306229'>the</span> <span m='306746'>datapath</span>
  <span m='307264'>logic</span> <span m='307782'>required</span> <span m='308300'>for</span>
  <span m='308817'>execution</span> <span m='309335'>is</span> <span m='309853'>very</span>
  <span m='310371'>straightforward!</span> </p><p><span m='310889'>The</span> <span
  m='311271'>other</span> <span m='311653'>form</span> <span m='312035'>of</span>
  <span m='312417'>ALU</span> <span m='312800'>instructions</span> <span m='313182'>uses</span>
  <span m='313564'>a</span> <span m='313946'>constant</span> <span m='314328'>as</span>
  <span m='314711'>the</span> <span m='315093'>second</span> <span m='315475'>ALU</span>
  <span m='315857'>operand.</span> </p><p><span m='316240'>The</span> <span m='316664'>32-bit</span>
  <span m='317089'>operand</span> <span m='317513'>is</span> <span m='317938'>formed</span>
  <span m='318362'>by</span> <span m='318787'>sign-extending</span> <span m='319211'>the</span>
  <span m='319636'>16-bit</span> <span m='320060'>two's</span> <span m='320485'>complement</span>
  <span m='320909'>constant</span> <span m='321334'>stored</span> <span m='321759'>in</span>
  <span m='322324'>the</span> <span m='322890'>literal</span> <span m='323455'>field</span>
  <span m='324021'>(bits</span> <span m='324586'>[15:0])</span> <span m='325152'>of</span>
  <span m='325717'>the</span> <span m='326283'>instruction.</span> </p><p><span m='326849'>In</span>
  <span m='327149'>order</span> <span m='327449'>to</span> <span m='327749'>select</span>
  <span m='328049'>the</span> <span m='328349'>sign-extended</span> <span m='328649'>constant</span>
  <span m='328949'>as</span> <span m='329249'>the</span> <span m='329549'>second</span>
  <span m='329849'>operand,</span> <span m='330149'>we</span> <span m='330449'>added</span>
  <span m='330749'>a</span> <span m='331049'>MUX</span> <span m='331349'>to</span>
  <span m='331649'>the</span> <span m='331949'>datapath.</span> </p><p><span m='333539'>When</span>
  <span m='333860'>its</span> <span m='334181'>BSEL</span> <span m='334502'>control</span>
  <span m='334823'>signal</span> <span m='335144'>is</span> <span m='335466'>0,</span>
  <span m='335787'>the</span> <span m='336108'>output</span> <span m='336429'>of</span>
  <span m='336750'>the</span> <span m='337071'>register</span> <span m='337393'>file</span>
  <span m='337714'>is</span> <span m='338035'>selected</span> <span m='338356'>as</span>
  <span m='338677'>the</span> <span m='338998'>operand.</span> </p><p><span m='339320'>When</span>
  <span m='339780'>BSEL</span> <span m='340241'>is</span> <span m='340702'>1,</span>
  <span m='341163'>the</span> <span m='341623'>sign-extended</span> <span m='342084'>constant</span>
  <span m='342545'>is</span> <span m='343006'>selected</span> <span m='343466'>as</span>
  <span m='343927'>the</span> <span m='344388'>operand.</span> </p><p><span m='344849'>The</span>
  <span m='345221'>rest</span> <span m='345594'>of</span> <span m='345967'>the</span>
  <span m='346339'>datapath</span> <span m='346712'>logic</span> <span m='347085'>is</span>
  <span m='347458'>the</span> <span m='347830'>same</span> <span m='348203'>as</span>
  <span m='348576'>before.</span> </p><p><span m='348949'>Note</span> <span m='349318'>that</span>
  <span m='349687'>no</span> <span m='350057'>logic</span> <span m='350426'>gates</span>
  <span m='350796'>are</span> <span m='351165'>needed</span> <span m='351535'>to</span>
  <span m='351904'>perform</span> <span m='352273'>sign-extension</span> <span m='352643'>-</span>
  <span m='353012'>it's</span> <span m='353382'>all</span> <span m='353751'>done</span>
  <span m='354121'>with</span> <span m='354490'>wiring!</span> </p><p><span m='354860'>To</span>
  <span m='355225'>sign-extend</span> <span m='355590'>a</span> <span m='355956'>two's</span>
  <span m='356321'>complement</span> <span m='356686'>number,</span> <span m='357052'>we</span>
  <span m='357417'>just</span> <span m='357783'>need</span> <span m='358148'>to</span>
  <span m='358513'>replicate</span> <span m='358879'>the</span> <span m='359244'>high-order,</span>
  <span m='359610'>or</span> <span m='360069'>sign,</span> <span m='360529'>bit</span>
  <span m='360989'>as</span> <span m='361449'>many</span> <span m='361909'>times</span>
  <span m='362369'>as</span> <span m='362829'>necessary.</span> </p><p><span m='363289'>You</span>
  <span m='363545'>might</span> <span m='363802'>find</span> <span m='364059'>it</span>
  <span m='364315'>useful</span> <span m='364572'>to</span> <span m='364829'>review</span>
  <span m='365085'>the</span> <span m='365342'>discussion</span> <span m='365599'>of</span>
  <span m='365855'>two's</span> <span m='366112'>complement</span> <span m='366369'>in</span>
  <span m='366625'>Lecture</span> <span m='366882'>1</span> <span m='367139'>of</span>
  <span m='367395'>Part</span> <span m='367652'>1</span> <span m='367909'>of</span>
  <span m='368426'>the</span> <span m='368943'>course.</span> </p><p><span m='369460'>So</span>
  <span m='369849'>to</span> <span m='370238'>form</span> <span m='370628'>a</span>
  <span m='371017'>32-bit</span> <span m='371406'>operand</span> <span m='371796'>from</span>
  <span m='372185'>a</span> <span m='372574'>16-bit</span> <span m='372964'>constant,</span>
  <span m='373353'>we</span> <span m='373742'>just</span> <span m='374132'>replicate</span>
  <span m='374521'>it's</span> <span m='374910'>high-order</span> <span m='375300'>bit</span>
  <span m='375815'>(ID[15])</span> <span m='376330'>sixteen</span> <span m='376846'>times</span>
  <span m='377361'>as</span> <span m='377876'>we</span> <span m='378392'>make</span>
  <span m='378907'>the</span> <span m='379423'>connection</span> <span m='379938'>to</span>
  <span m='380453'>the</span> <span m='380969'>BSEL</span> <span m='381484'>MUX.</span>
  </p><p><span m='382000'>During</span> <span m='382412'>execution</span> <span m='382825'>of</span>
  <span m='383238'>ALU-with-constant</span> <span m='383650'>instructions,</span>
  <span m='384063'>the</span> <span m='384476'>flow</span> <span m='384888'>of</span>
  <span m='385301'>data</span> <span m='385714'>is</span> <span m='386126'>much</span>
  <span m='386539'>as</span> <span m='386952'>it</span> <span m='387364'>was</span>
  <span m='387777'>before.</span> </p><p><span m='388190'>The</span> <span m='388551'>one</span>
  <span m='388913'>difference</span> <span m='389275'>is</span> <span m='389637'>that</span>
  <span m='389999'>the</span> <span m='390360'>control</span> <span m='390722'>logic</span>
  <span m='391084'>sets</span> <span m='391446'>the</span> <span m='391808'>BSEL</span>
  <span m='392169'>control</span> <span m='392531'>signal</span> <span m='392893'>to</span>
  <span m='393255'>1,</span> <span m='393617'>selecting</span> <span m='393979'>the</span>
  <span m='394512'>sign-extended</span> <span m='395046'>constant</span> <span m='395580'>as</span>
  <span m='396114'>the</span> <span m='396648'>second</span> <span m='397182'>ALU</span>
  <span m='397716'>operand.</span> </p><p><span m='398250'>As</span> <span m='398614'>before,</span>
  <span m='398978'>the</span> <span m='399342'>control</span> <span m='399707'>logic</span>
  <span m='400071'>generates</span> <span m='400435'>the</span> <span m='400800'>appropriate</span>
  <span m='401164'>ALU</span> <span m='401528'>function</span> <span m='401892'>code</span>
  <span m='402257'>and</span> <span m='402621'>the</span> <span m='402985'>output</span>
  <span m='403350'>of</span> <span m='403686'>the</span> <span m='404022'>ALU</span>
  <span m='404359'>is</span> <span m='404695'>routed</span> <span m='405032'>to</span>
  <span m='405368'>the</span> <span m='405704'>register</span> <span m='406041'>file</span>
  <span m='406377'>to</span> <span m='406714'>be</span> <span m='407050'>written</span>
  <span m='407386'>back</span> <span m='407723'>to</span> <span m='408059'>the</span>
  <span m='408396'>RC</span> <span m='408732'>register.</span> </p><p><span m='409069'>Amazingly,</span>
  <span m='409431'>this</span> <span m='409793'>datapath</span> <span m='410155'>is</span>
  <span m='410517'>sufficient</span> <span m='410879'>to</span> <span m='411241'>execute</span>
  <span m='411604'>most</span> <span m='411966'>of</span> <span m='412328'>the</span>
  <span m='412690'>instructions</span> <span m='413052'>in</span> <span m='413414'>the</span>
  <span m='413776'>Beta</span> <span m='414139'>ISA!</span> </p><p><span m='415780'>We</span>
  <span m='416117'>just</span> <span m='416454'>have</span> <span m='416791'>the</span>
  <span m='417129'>memory</span> <span m='417466'>and</span> <span m='417803'>branch</span>
  <span m='418140'>instruction</span> <span m='418478'>left</span> <span m='418815'>to</span>
  <span m='419152'>implement.</span> </p><p><span m='419490'>That's</span> <span m='419725'>our</span>
  <span m='419960'>next</span> <span m='420195'>task.</span> </p>
type: course
uid: b438f26843085100771e081aa5e6d2e0

---
None