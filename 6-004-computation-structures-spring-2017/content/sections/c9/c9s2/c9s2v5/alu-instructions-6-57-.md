---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: yRvgtY49eXE
  parent_uid: 86e4aef41c3396c858d72ed37e31f45e
  title: Video-YouTube-Stream
  type: Video
  uid: e0b91e8d7847238cbe1295e90a4b6d33
- id: 3Play-3Play YouTube id-Stream
  media_location: yRvgtY49eXE
  parent_uid: 86e4aef41c3396c858d72ed37e31f45e
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: d6f7b51d125be3101873f014a8866892
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/yRvgtY49eXE/default.jpg
  parent_uid: 86e4aef41c3396c858d72ed37e31f45e
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e3dd99c6550765492998d24d0dfd891a
- id: yRvgtY49eXE.srt
  parent_uid: 86e4aef41c3396c858d72ed37e31f45e
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v5/alu-instructions-6-57-/yRvgtY49eXE.srt
  title: 3play caption file
  type: null
  uid: 42ec876c52639e4c984b25f257dada16
- id: yRvgtY49eXE.pdf
  parent_uid: 86e4aef41c3396c858d72ed37e31f45e
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v5/alu-instructions-6-57-/yRvgtY49eXE.pdf
  title: 3play pdf file
  type: null
  uid: 843a56df49226f93f9ff65b93e87f7b2
- id: Caption-3Play YouTube id-SRT
  parent_uid: 86e4aef41c3396c858d72ed37e31f45e
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 4dae1f673f3ac8556821774f4af732c8
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 86e4aef41c3396c858d72ed37e31f45e
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 0dba51c2156429ce109c7ef457ac239b
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_09-02-05_300k.mp4
  parent_uid: 86e4aef41c3396c858d72ed37e31f45e
  title: Video-Internet Archive-MP4
  type: Video
  uid: aeedf770689bb1dd80b76b7a3ce1a266
inline_embed_id: 3259460aluinstructions65717383461
layout: video
order_index: null
parent_uid: 56f3db97d9fcbdaff0ac31291b4b24b8
related_resources_text: ''
short_url: alu-instructions-6-57-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v5/alu-instructions-6-57-
template_type: Embed
title: ALU Instructions (6:57)
transcript: <p><span m='989'>Having</span> <span m='1349'>talked</span> <span m='1709'>about</span>
  <span m='2069'>the</span> <span m='2429'>storage</span> <span m='2789'>resources</span>
  <span m='3149'>provided</span> <span m='3509'>by</span> <span m='3869'>the</span>
  <span m='4229'>Beta</span> <span m='4589'>ISA,</span> <span m='4949'>let's</span>
  <span m='5309'>design</span> <span m='5669'>the</span> <span m='6029'>Beta</span>
  <span m='6879'>instructions</span> <span m='7729'>themselves.</span> </p><p><span
  m='8580'>This</span> <span m='8814'>might</span> <span m='9049'>be</span> <span
  m='9284'>a</span> <span m='9519'>good</span> <span m='9754'>time</span> <span m='9989'>to</span>
  <span m='10224'>print</span> <span m='10459'>a</span> <span m='10694'>copy</span>
  <span m='10929'>of</span> <span m='11164'>the</span> <span m='11399'>handout</span>
  <span m='11634'>called</span> <span m='11869'>the</span> <span m='12104'>"Summary</span>
  <span m='12339'>of</span> <span m='12574'>Beta</span> <span m='12809'>Instruction</span>
  <span m='13328'>Formats"</span> <span m='13847'>so</span> <span m='14366'>you'll</span>
  <span m='14885'>have</span> <span m='15404'>it</span> <span m='15923'>for</span>
  <span m='16442'>handy</span> <span m='16961'>reference.</span> </p><p><span m='17480'>The</span>
  <span m='17822'>Beta</span> <span m='18165'>has</span> <span m='18507'>three</span>
  <span m='18850'>types</span> <span m='19192'>of</span> <span m='19535'>instructions:</span>
  <span m='19877'>compute</span> <span m='20220'>instructions</span> <span m='20562'>that</span>
  <span m='20905'>perform</span> <span m='21247'>arithmetic</span> <span m='21590'>and</span>
  <span m='22003'>logic</span> <span m='22416'>operations</span> <span m='22829'>on</span>
  <span m='23242'>register</span> <span m='23655'>values,</span> <span m='24068'>load</span>
  <span m='24481'>and</span> <span m='24894'>store</span> <span m='25307'>instructions</span>
  <span m='25720'>that</span> <span m='26133'>access</span> <span m='26546'>values</span>
  <span m='26960'>in</span> <span m='27379'>main</span> <span m='27798'>memory,</span>
  <span m='28217'>and</span> <span m='28637'>branch</span> <span m='29056'>instructions</span>
  <span m='29475'>that</span> <span m='29895'>change</span> <span m='30314'>the</span>
  <span m='30733'>value</span> <span m='31152'>of</span> <span m='31572'>the</span>
  <span m='31991'>program</span> <span m='32410'>counter.</span> </p><p><span m='32830'>We'll</span>
  <span m='33391'>discuss</span> <span m='33952'>each</span> <span m='34513'>class</span>
  <span m='35075'>of</span> <span m='35636'>instructions</span> <span m='36197'>in</span>
  <span m='36758'>turn.</span> </p><p><span m='37320'>In</span> <span m='37715'>the</span>
  <span m='38110'>Beta</span> <span m='38505'>ISA,</span> <span m='38900'>all</span>
  <span m='39295'>the</span> <span m='39690'>instruction</span> <span m='40085'>encodings</span>
  <span m='40480'>are</span> <span m='40875'>the</span> <span m='41270'>same</span>
  <span m='41665'>size:</span> <span m='42060'>each</span> <span m='42455'>instruction</span>
  <span m='42850'>is</span> <span m='43245'>encoded</span> <span m='43640'>in</span>
  <span m='44076'>32</span> <span m='44513'>bits</span> <span m='44950'>and</span>
  <span m='45387'>hence</span> <span m='45824'>occupies</span> <span m='46261'>exactly</span>
  <span m='46698'>one</span> <span m='47135'>32-bit</span> <span m='47572'>word</span>
  <span m='48009'>in</span> <span m='48446'>main</span> <span m='48883'>memory.</span>
  </p><p><span m='49320'>This</span> <span m='49801'>instruction</span> <span m='50283'>encoding</span>
  <span m='50765'>leads</span> <span m='51247'>to</span> <span m='51729'>simpler</span>
  <span m='52210'>control-unit</span> <span m='52692'>logic</span> <span m='53174'>for</span>
  <span m='53656'>decoding</span> <span m='54138'>instructions.</span> </p><p><span
  m='54620'>And</span> <span m='54923'>computing</span> <span m='55226'>the</span>
  <span m='55530'>next</span> <span m='55833'>value</span> <span m='56136'>of</span>
  <span m='56440'>the</span> <span m='56743'>program</span> <span m='57046'>counter</span>
  <span m='57350'>is</span> <span m='57653'>very</span> <span m='57956'>simple:</span>
  <span m='58260'>for</span> <span m='58635'>most</span> <span m='59010'>instructions,</span>
  <span m='59385'>the</span> <span m='59760'>next</span> <span m='60135'>instruction</span>
  <span m='60510'>can</span> <span m='60885'>be</span> <span m='61260'>found</span>
  <span m='61635'>in</span> <span m='62010'>the</span> <span m='62385'>following</span>
  <span m='62760'>memory</span> <span m='63135'>location.</span> </p><p><span m='63510'>We</span>
  <span m='63746'>just</span> <span m='63983'>need</span> <span m='64220'>to</span>
  <span m='64456'>add</span> <span m='64693'>4</span> <span m='64930'>to</span> <span
  m='65166'>the</span> <span m='65403'>current</span> <span m='65640'>value</span>
  <span m='65876'>of</span> <span m='66113'>program</span> <span m='66350'>counter</span>
  <span m='66586'>to</span> <span m='66823'>advance</span> <span m='67060'>to</span>
  <span m='67296'>the</span> <span m='67533'>next</span> <span m='67770'>instruction.</span>
  </p><p><span m='69280'>As</span> <span m='69557'>we</span> <span m='69835'>saw</span>
  <span m='70112'>in</span> <span m='70390'>Part</span> <span m='70668'>1</span> <span
  m='70945'>of</span> <span m='71223'>the</span> <span m='71501'>course,</span> <span
  m='71778'>fixed-length</span> <span m='72056'>encodings</span> <span m='72334'>are</span>
  <span m='72611'>often</span> <span m='72889'>inefficient</span> <span m='73167'>in</span>
  <span m='73444'>the</span> <span m='73722'>sense</span> <span m='74000'>that</span>
  <span m='74400'>the</span> <span m='74801'>same</span> <span m='75201'>information</span>
  <span m='75602'>content</span> <span m='76003'>(in</span> <span m='76403'>this</span>
  <span m='76804'>case,</span> <span m='77205'>the</span> <span m='77605'>encoded</span>
  <span m='78006'>program)</span> <span m='78407'>can</span> <span m='78807'>be</span>
  <span m='79208'>encoded</span> <span m='79609'>using</span> <span m='80329'>fewer</span>
  <span m='81049'>bits.</span> </p><p><span m='81770'>To</span> <span m='82126'>do</span>
  <span m='82483'>better</span> <span m='82840'>we</span> <span m='83197'>would</span>
  <span m='83553'>need</span> <span m='83910'>a</span> <span m='84267'>variable-length</span>
  <span m='84624'>encoding</span> <span m='84980'>for</span> <span m='85337'>instructions,</span>
  <span m='85694'>where</span> <span m='86051'>frequently-occurring</span> <span m='86408'>instructions</span>
  <span m='86976'>would</span> <span m='87545'>use</span> <span m='88113'>a</span>
  <span m='88682'>shorter</span> <span m='89250'>encoding.</span> </p><p><span m='89819'>But</span>
  <span m='90195'>hardware</span> <span m='90572'>to</span> <span m='90948'>decode</span>
  <span m='91325'>variable-length</span> <span m='91701'>instructions</span> <span
  m='92078'>is</span> <span m='92454'>complex</span> <span m='92831'>since</span>
  <span m='93207'>there</span> <span m='93584'>may</span> <span m='93960'>be</span>
  <span m='94337'>several</span> <span m='94713'>instructions</span> <span m='95090'>packed</span>
  <span m='95489'>into</span> <span m='95888'>one</span> <span m='96287'>memory</span>
  <span m='96686'>word,</span> <span m='97086'>while</span> <span m='97485'>other</span>
  <span m='97884'>instructions</span> <span m='98283'>might</span> <span m='98682'>require</span>
  <span m='99082'>loading</span> <span m='99481'>several</span> <span m='99880'>memory</span>
  <span m='100279'>words.</span> </p><p><span m='100679'>The</span> <span m='100959'>details</span>
  <span m='101239'>can</span> <span m='101519'>be</span> <span m='101799'>worked</span>
  <span m='102079'>out,</span> <span m='102359'>but</span> <span m='102639'>there's</span>
  <span m='102919'>a</span> <span m='103199'>performance</span> <span m='103479'>and</span>
  <span m='103759'>energy</span> <span m='104039'>cost</span> <span m='104319'>associated</span>
  <span m='104599'>with</span> <span m='104880'>the</span> <span m='105467'>more</span>
  <span m='106054'>efficient</span> <span m='106641'>encoding.</span> </p><p><span
  m='107229'>Nowadays,</span> <span m='107581'>advances</span> <span m='107934'>in</span>
  <span m='108287'>memory</span> <span m='108639'>technology</span> <span m='108992'>have</span>
  <span m='109345'>made</span> <span m='109698'>memory</span> <span m='110050'>size</span>
  <span m='110403'>less</span> <span m='110756'>of</span> <span m='111109'>an</span>
  <span m='111461'>issue</span> <span m='111814'>and</span> <span m='112167'>the</span>
  <span m='112520'>focus</span> <span m='113095'>is</span> <span m='113671'>on</span>
  <span m='114246'>the</span> <span m='114822'>higher-performance</span> <span m='115397'>needed</span>
  <span m='115973'>by</span> <span m='116548'>today's</span> <span m='117124'>applications.</span>
  </p><p><span m='117700'>Our</span> <span m='118026'>choice</span> <span m='118352'>of</span>
  <span m='118678'>a</span> <span m='119004'>fixed-length</span> <span m='119330'>encoding</span>
  <span m='119656'>leads</span> <span m='119982'>to</span> <span m='120308'>larger</span>
  <span m='120634'>code</span> <span m='120960'>size,</span> <span m='121286'>but</span>
  <span m='121612'>keeps</span> <span m='121938'>the</span> <span m='122264'>hardware</span>
  <span m='122590'>execution</span> <span m='123278'>engine</span> <span m='123966'>small</span>
  <span m='124654'>and</span> <span m='125342'>fast.</span> </p><p><span m='126030'>The</span>
  <span m='126453'>computation</span> <span m='126877'>performed</span> <span m='127301'>by</span>
  <span m='127725'>the</span> <span m='128149'>Beta</span> <span m='128573'>datapath</span>
  <span m='128996'>happens</span> <span m='129420'>in</span> <span m='129844'>the</span>
  <span m='130268'>arithmetic-and-logic</span> <span m='130692'>unit</span> <span
  m='131116'>(ALU).</span> </p><p><span m='131540'>We'll</span> <span m='131935'>be</span>
  <span m='132331'>using</span> <span m='132727'>the</span> <span m='133123'>ALU</span>
  <span m='133519'>designed</span> <span m='133915'>in</span> <span m='134310'>Part</span>
  <span m='134706'>1</span> <span m='135102'>of</span> <span m='135498'>the</span>
  <span m='135894'>course.</span> </p><p><span m='136290'>The</span> <span m='136747'>Beta</span>
  <span m='137205'>ALU</span> <span m='137662'>instructions</span> <span m='138120'>have</span>
  <span m='138577'>4</span> <span m='139035'>instruction</span> <span m='139492'>fields.</span>
  </p><p><span m='139950'>There's</span> <span m='140302'>a</span> <span m='140654'>6-bit</span>
  <span m='141007'>field</span> <span m='141359'>specifying</span> <span m='141711'>the</span>
  <span m='142064'>ALU</span> <span m='142416'>operation</span> <span m='142768'>to</span>
  <span m='143121'>be</span> <span m='143473'>performed</span> <span m='143825'>-</span>
  <span m='144178'>this</span> <span m='144530'>field</span> <span m='144882'>is</span>
  <span m='145235'>called</span> <span m='145587'>the</span> <span m='145940'>opcode.</span>
  </p><p><span m='147110'>The</span> <span m='147457'>two</span> <span m='147805'>source</span>
  <span m='148153'>operands</span> <span m='148501'>come</span> <span m='148849'>from</span>
  <span m='149197'>registers</span> <span m='149545'>whose</span> <span m='149893'>numbers</span>
  <span m='150241'>are</span> <span m='150589'>specified</span> <span m='150937'>by</span>
  <span m='151285'>the</span> <span m='151633'>5-bit</span> <span m='151981'>"ra"</span>
  <span m='152329'>and</span> <span m='152786'>"rb"</span> <span m='153243'>fields.</span>
  </p><p><span m='153700'>So</span> <span m='154080'>we</span> <span m='154461'>can</span>
  <span m='154842'>specify</span> <span m='155222'>any</span> <span m='155603'>register</span>
  <span m='155984'>from</span> <span m='156365'>R0</span> <span m='156745'>to</span>
  <span m='157126'>R31</span> <span m='157507'>as</span> <span m='157887'>a</span>
  <span m='158268'>source</span> <span m='158649'>operand.</span> </p><p><span m='159030'>The</span>
  <span m='159529'>destination</span> <span m='160028'>register</span> <span m='160527'>is</span>
  <span m='161026'>specified</span> <span m='161525'>by</span> <span m='162024'>the</span>
  <span m='162523'>5-bit</span> <span m='163022'>"rc"</span> <span m='163521'>field.</span>
  </p><p><span m='164020'>This</span> <span m='164360'>instruction</span> <span m='164700'>format</span>
  <span m='165040'>uses</span> <span m='165380'>21</span> <span m='165720'>bits</span>
  <span m='166060'>of</span> <span m='166400'>the</span> <span m='166740'>32-bit</span>
  <span m='167080'>word,</span> <span m='167420'>the</span> <span m='167760'>remaining</span>
  <span m='168100'>bits</span> <span m='168440'>are</span> <span m='168780'>unused</span>
  <span m='169120'>and</span> <span m='169523'>should</span> <span m='169926'>be</span>
  <span m='170330'>set</span> <span m='170733'>to</span> <span m='171136'>0.</span>
  </p><p><span m='171540'>The</span> <span m='171870'>diagram</span> <span m='172201'>shows</span>
  <span m='172532'>how</span> <span m='172863'>the</span> <span m='173194'>fields</span>
  <span m='173525'>are</span> <span m='173855'>positioned</span> <span m='174186'>in</span>
  <span m='174517'>the</span> <span m='174848'>32-bit</span> <span m='175179'>word.</span>
  </p><p><span m='175510'>The</span> <span m='175813'>choice</span> <span m='176116'>of</span>
  <span m='176419'>position</span> <span m='176722'>for</span> <span m='177025'>each</span>
  <span m='177328'>field</span> <span m='177631'>is</span> <span m='177935'>somewhat</span>
  <span m='178238'>arbitrary,</span> <span m='178541'>but</span> <span m='178844'>to</span>
  <span m='179147'>keep</span> <span m='179450'>the</span> <span m='179753'>hardware</span>
  <span m='180056'>simple,</span> <span m='180360'>when</span> <span m='180690'>we</span>
  <span m='181021'>can</span> <span m='181351'>we'll</span> <span m='181682'>want</span>
  <span m='182012'>to</span> <span m='182343'>use</span> <span m='182674'>the</span>
  <span m='183004'>same</span> <span m='183335'>field</span> <span m='183665'>positions</span>
  <span m='183996'>for</span> <span m='184327'>similar</span> <span m='184657'>fields</span>
  <span m='184988'>in</span> <span m='185318'>the</span> <span m='185649'>other</span>
  <span m='185980'>instruction</span> <span m='186670'>encodings.</span> </p><p><span
  m='187360'>For</span> <span m='187867'>example,</span> <span m='188375'>the</span>
  <span m='188883'>opcode</span> <span m='189391'>will</span> <span m='189899'>always</span>
  <span m='190407'>be</span> <span m='190915'>found</span> <span m='191422'>in</span>
  <span m='191930'>bits</span> <span m='192438'>[31:26]</span> <span m='192946'>of</span>
  <span m='193454'>the</span> <span m='193962'>instruction.</span> </p><p><span m='194470'>Here's</span>
  <span m='194836'>the</span> <span m='195202'>binary</span> <span m='195568'>encoding</span>
  <span m='195935'>of</span> <span m='196301'>an</span> <span m='196667'>ADD</span>
  <span m='197033'>instruction.</span> </p><p><span m='197400'>The</span> <span m='197818'>opcode</span>
  <span m='198237'>for</span> <span m='198656'>ADD</span> <span m='199075'>is</span>
  <span m='199494'>the</span> <span m='199913'>6-bit</span> <span m='200332'>binary</span>
  <span m='200751'>value</span> <span m='201170'>0b100000</span> <span m='201588'>-</span>
  <span m='202007'>you</span> <span m='202426'>can</span> <span m='202845'>find</span>
  <span m='203264'>the</span> <span m='203683'>binary</span> <span m='204102'>for</span>
  <span m='204521'>each</span> <span m='204940'>opcode</span> <span m='205333'>in</span>
  <span m='205726'>the</span> <span m='206119'>Opcode</span> <span m='206512'>Table</span>
  <span m='206905'>in</span> <span m='207298'>the</span> <span m='207691'>handout</span>
  <span m='208084'>mentioned</span> <span m='208477'>before.</span> </p><p><span m='208870'>The</span>
  <span m='209264'>"rc"</span> <span m='209659'>field</span> <span m='210054'>specifies</span>
  <span m='210448'>that</span> <span m='210843'>the</span> <span m='211238'>result</span>
  <span m='211632'>of</span> <span m='212027'>the</span> <span m='212422'>ADD</span>
  <span m='212816'>will</span> <span m='213211'>be</span> <span m='213606'>written</span>
  <span m='214000'>into</span> <span m='214395'>R3.</span> </p><p><span m='214790'>And</span>
  <span m='215131'>the</span> <span m='215473'>"ra"</span> <span m='215815'>and</span>
  <span m='216157'>"rb"</span> <span m='216499'>fields</span> <span m='216841'>specify</span>
  <span m='217183'>that</span> <span m='217525'>the</span> <span m='217866'>first</span>
  <span m='218208'>and</span> <span m='218550'>second</span> <span m='218892'>source</span>
  <span m='219234'>operands</span> <span m='219576'>are</span> <span m='219918'>R1</span>
  <span m='220260'>and</span> <span m='221046'>R2</span> <span m='221833'>respectively.</span>
  </p><p><span m='222620'>So</span> <span m='222997'>this</span> <span m='223375'>instruction</span>
  <span m='223752'>adds</span> <span m='224130'>the</span> <span m='224507'>32-bit</span>
  <span m='224885'>values</span> <span m='225262'>found</span> <span m='225640'>in</span>
  <span m='226017'>R1</span> <span m='226395'>and</span> <span m='226772'>R2,</span>
  <span m='227150'>writing</span> <span m='227527'>the</span> <span m='227905'>32-bit</span>
  <span m='228282'>sum</span> <span m='228660'>into</span> <span m='229965'>R3.</span>
  </p><p><span m='231270'>Note</span> <span m='231585'>that</span> <span m='231901'>it's</span>
  <span m='232216'>permissible</span> <span m='232532'>to</span> <span m='232848'>refer</span>
  <span m='233163'>to</span> <span m='233479'>a</span> <span m='233795'>particular</span>
  <span m='234110'>register</span> <span m='234426'>several</span> <span m='234741'>times</span>
  <span m='235057'>in</span> <span m='235373'>the</span> <span m='235688'>same</span>
  <span m='236004'>instruction.</span> </p><p><span m='236320'>So,</span> <span m='236680'>for</span>
  <span m='237041'>example,</span> <span m='237401'>we</span> <span m='237762'>could</span>
  <span m='238123'>specify</span> <span m='238483'>R1</span> <span m='238844'>as</span>
  <span m='239205'>the</span> <span m='239565'>register</span> <span m='239926'>for</span>
  <span m='240286'>both</span> <span m='240647'>source</span> <span m='241008'>operands</span>
  <span m='241368'>AND</span> <span m='241729'>also</span> <span m='242090'>as</span>
  <span m='242685'>the</span> <span m='243280'>destination</span> <span m='243875'>register.</span>
  </p><p><span m='244470'>If</span> <span m='244781'>we</span> <span m='245092'>did,</span>
  <span m='245403'>we'd</span> <span m='245714'>be</span> <span m='246025'>adding</span>
  <span m='246336'>R1</span> <span m='246647'>to</span> <span m='246958'>R1</span>
  <span m='247269'>and</span> <span m='247580'>writing</span> <span m='247891'>the</span>
  <span m='248202'>result</span> <span m='248513'>back</span> <span m='248824'>into</span>
  <span m='249135'>R1,</span> <span m='249446'>which</span> <span m='249757'>would</span>
  <span m='250068'>effectively</span> <span m='250380'>multiply</span> <span m='251020'>the</span>
  <span m='251660'>value</span> <span m='252300'>in</span> <span m='252940'>R1</span>
  <span m='253580'>by</span> <span m='254220'>2.</span> </p><p><span m='254860'>Since</span>
  <span m='255296'>it's</span> <span m='255732'>tedious</span> <span m='256169'>and</span>
  <span m='256605'>error-prone</span> <span m='257041'>to</span> <span m='257478'>transcribe</span>
  <span m='257914'>32-bit</span> <span m='258350'>binary</span> <span m='258787'>values,</span>
  <span m='259223'>we'll</span> <span m='259659'>often</span> <span m='260096'>use</span>
  <span m='260532'>hexadecimal</span> <span m='260969'>notation</span> <span m='261576'>for</span>
  <span m='262184'>the</span> <span m='262791'>binary</span> <span m='263399'>representation</span>
  <span m='264007'>of</span> <span m='264614'>an</span> <span m='265222'>instruction.</span>
  </p><p><span m='265830'>In</span> <span m='266364'>this</span> <span m='266898'>example,</span>
  <span m='267432'>the</span> <span m='267966'>hexadecimal</span> <span m='268500'>notation</span>
  <span m='269035'>for</span> <span m='269569'>the</span> <span m='270103'>encoded</span>
  <span m='270637'>instruction</span> <span m='271171'>is</span> <span m='271705'>0x80611000.</span>
  </p><p><span m='272240'>However,</span> <span m='272860'>it's</span> <span m='273480'>*much*</span>
  <span m='274100'>easier</span> <span m='274720'>if</span> <span m='275340'>we</span>
  <span m='275960'>describe</span> <span m='276580'>the</span> <span m='277200'>instructions</span>
  <span m='277820'>using</span> <span m='278440'>a</span> <span m='279060'>functional</span>
  <span m='279680'>notation,</span> <span m='280300'>e.g.,</span> <span m='282190'>"ADD(r1,r2,r3)".</span>
  </p><p><span m='284080'>Here</span> <span m='284370'>we</span> <span m='284660'>use</span>
  <span m='284950'>a</span> <span m='285240'>symbolic</span> <span m='285530'>name</span>
  <span m='285820'>for</span> <span m='286110'>each</span> <span m='286400'>operation,</span>
  <span m='286690'>called</span> <span m='286980'>a</span> <span m='287270'>mnemonic.</span>
  </p><p><span m='287560'>For</span> <span m='287930'>this</span> <span m='288301'>instruction</span>
  <span m='288671'>the</span> <span m='289042'>mnemonic</span> <span m='289413'>is</span>
  <span m='289783'>"ADD",</span> <span m='290154'>followed</span> <span m='290525'>by</span>
  <span m='290895'>a</span> <span m='291266'>parenthesized</span> <span m='291637'>list</span>
  <span m='292007'>of</span> <span m='292378'>operands,</span> <span m='292749'>in</span>
  <span m='293228'>this</span> <span m='293707'>case</span> <span m='294187'>the</span>
  <span m='294666'>two</span> <span m='295145'>source</span> <span m='295625'>operands</span>
  <span m='296104'>(r1</span> <span m='296583'>and</span> <span m='297063'>r2),</span>
  <span m='297542'>then</span> <span m='298021'>the</span> <span m='298501'>destination</span>
  <span m='298980'>(r3).</span> </p><p><span m='299460'>So</span> <span m='299869'>we'll</span>
  <span m='300279'>understand</span> <span m='300689'>that</span> <span m='301099'>ADD(ra,rb,rc)</span>
  <span m='301509'>is</span> <span m='301919'>shorthand</span> <span m='302329'>for</span>
  <span m='302739'>asking</span> <span m='303149'>the</span> <span m='303559'>Beta</span>
  <span m='303969'>to</span> <span m='304379'>compute</span> <span m='304789'>the</span>
  <span m='305199'>sum</span> <span m='305500'>of</span> <span m='305802'>the</span>
  <span m='306104'>values</span> <span m='306405'>in</span> <span m='306707'>registers</span>
  <span m='307009'>ra</span> <span m='307310'>and</span> <span m='307612'>rb,</span>
  <span m='307914'>writing</span> <span m='308215'>the</span> <span m='308517'>result</span>
  <span m='308819'>as</span> <span m='309120'>the</span> <span m='309422'>new</span>
  <span m='309724'>value</span> <span m='310025'>of</span> <span m='310327'>register</span>
  <span m='310629'>rc.</span> </p><p><span m='312569'>Here's</span> <span m='312888'>the</span>
  <span m='313207'>list</span> <span m='313526'>of</span> <span m='313846'>the</span>
  <span m='314165'>mnemonics</span> <span m='314484'>for</span> <span m='314804'>all</span>
  <span m='315123'>the</span> <span m='315442'>operations</span> <span m='315761'>supported</span>
  <span m='316081'>by</span> <span m='316400'>the</span> <span m='316719'>Beta.</span>
  </p><p><span m='317039'>There</span> <span m='317368'>is</span> <span m='317697'>a</span>
  <span m='318027'>detailed</span> <span m='318356'>description</span> <span m='318685'>of</span>
  <span m='319015'>what</span> <span m='319344'>each</span> <span m='319673'>instruction</span>
  <span m='320003'>does</span> <span m='320332'>in</span> <span m='320661'>the</span>
  <span m='320991'>Beta</span> <span m='321320'>Documentation</span> <span m='321650'>handout.</span>
  </p><p><span m='322810'>Note</span> <span m='323130'>that</span> <span m='323451'>all</span>
  <span m='323772'>these</span> <span m='324093'>instructions</span> <span m='324413'>use</span>
  <span m='324734'>same</span> <span m='325055'>4-field</span> <span m='325376'>template,</span>
  <span m='325697'>differing</span> <span m='326017'>only</span> <span m='326338'>in</span>
  <span m='326659'>the</span> <span m='326980'>value</span> <span m='327301'>of</span>
  <span m='327905'>the</span> <span m='328510'>opcode</span> <span m='329114'>field.</span>
  </p><p><span m='329719'>This</span> <span m='330046'>first</span> <span m='330374'>step</span>
  <span m='330701'>was</span> <span m='331029'>pretty</span> <span m='331356'>straightforward</span>
  <span m='331684'>-</span> <span m='332012'>we</span> <span m='332339'>simply</span>
  <span m='332667'>provided</span> <span m='332994'>instruction</span> <span m='333322'>encodings</span>
  <span m='333650'>for</span> <span m='334213'>the</span> <span m='334777'>basic</span>
  <span m='335340'>operations</span> <span m='335904'>provided</span> <span m='336468'>by</span>
  <span m='337031'>the</span> <span m='337595'>ALU.</span> </p><p><span m='338159'>Now</span>
  <span m='338449'>that</span> <span m='338739'>we</span> <span m='339029'>have</span>
  <span m='339319'>our</span> <span m='339609'>first</span> <span m='339899'>group</span>
  <span m='340189'>of</span> <span m='340479'>instructions,</span> <span m='340769'>we</span>
  <span m='341059'>can</span> <span m='341349'>create</span> <span m='341639'>a</span>
  <span m='341929'>more</span> <span m='342219'>concrete</span> <span m='342509'>implementation</span>
  <span m='342800'>sketch.</span> </p><p><span m='344319'>Here</span> <span m='344670'>we</span>
  <span m='345022'>see</span> <span m='345374'>our</span> <span m='345726'>proposed</span>
  <span m='346078'>datapath.</span> </p><p><span m='346430'>The</span> <span m='346719'>5-bit</span>
  <span m='347008'>"ra"</span> <span m='347298'>and</span> <span m='347587'>"rb"</span>
  <span m='347876'>fields</span> <span m='348166'>from</span> <span m='348455'>the</span>
  <span m='348745'>instruction</span> <span m='349034'>are</span> <span m='349323'>used</span>
  <span m='349613'>to</span> <span m='349902'>select</span> <span m='350192'>which</span>
  <span m='350481'>of</span> <span m='350770'>the</span> <span m='351060'>32</span>
  <span m='351349'>registers</span> <span m='351639'>will</span> <span m='352127'>be</span>
  <span m='352616'>used</span> <span m='353105'>for</span> <span m='353593'>the</span>
  <span m='354082'>two</span> <span m='354571'>operands.</span> </p><p><span m='355060'>Note</span>
  <span m='355499'>that</span> <span m='355938'>register</span> <span m='356378'>31</span>
  <span m='356817'>isn't</span> <span m='357256'>actually</span> <span m='357696'>a</span>
  <span m='358135'>read/write</span> <span m='358574'>register,</span> <span m='359014'>it's</span>
  <span m='359453'>just</span> <span m='359892'>the</span> <span m='360332'>32-bit</span>
  <span m='360771'>constant</span> <span m='361210'>0,</span> <span m='361650'>so</span>
  <span m='362046'>that</span> <span m='362442'>selecting</span> <span m='362838'>R31</span>
  <span m='363234'>as</span> <span m='363630'>an</span> <span m='364026'>operand</span>
  <span m='364423'>results</span> <span m='364819'>in</span> <span m='365215'>using</span>
  <span m='365611'>the</span> <span m='366007'>value</span> <span m='366403'>0.</span>
  </p><p><span m='366800'>The</span> <span m='367115'>5-bit</span> <span m='367431'>"rc"</span>
  <span m='367746'>field</span> <span m='368062'>from</span> <span m='368378'>the</span>
  <span m='368693'>instruction</span> <span m='369009'>selects</span> <span m='369325'>which</span>
  <span m='369640'>register</span> <span m='369956'>will</span> <span m='370272'>be</span>
  <span m='370587'>written</span> <span m='370903'>with</span> <span m='371219'>the</span>
  <span m='371789'>result</span> <span m='372359'>from</span> <span m='372929'>the</span>
  <span m='373499'>ALU.</span> </p><p><span m='374069'>Not</span> <span m='374422'>shown</span>
  <span m='374776'>is</span> <span m='375129'>the</span> <span m='375483'>hardware</span>
  <span m='375837'>needed</span> <span m='376190'>to</span> <span m='376544'>translate</span>
  <span m='376898'>the</span> <span m='377251'>instruction</span> <span m='377605'>opcode</span>
  <span m='377959'>to</span> <span m='378312'>the</span> <span m='378666'>appropriate</span>
  <span m='379020'>ALU</span> <span m='379370'>function</span> <span m='379720'>code</span>
  <span m='380070'>-</span> <span m='380420'>perhaps</span> <span m='380770'>a</span>
  <span m='381120'>64-location</span> <span m='381470'>ROM</span> <span m='381820'>could</span>
  <span m='382170'>be</span> <span m='382520'>used</span> <span m='382870'>to</span>
  <span m='383220'>perform</span> <span m='383570'>the</span> <span m='383920'>translation</span>
  <span m='384270'>by</span> <span m='384839'>table</span> <span m='385409'>lookup.</span>
  </p><p><span m='385979'>The</span> <span m='386424'>program</span> <span m='386869'>counter</span>
  <span m='387314'>logic</span> <span m='387759'>supports</span> <span m='388204'>simple</span>
  <span m='388649'>sequential</span> <span m='389094'>execution</span> <span m='389539'>of</span>
  <span m='389984'>instructions.</span> </p><p><span m='390430'>It's</span> <span
  m='390741'>a</span> <span m='391053'>32-bit</span> <span m='391365'>register</span>
  <span m='391676'>whose</span> <span m='391988'>value</span> <span m='392300'>is</span>
  <span m='392611'>updated</span> <span m='392923'>at</span> <span m='393235'>the</span>
  <span m='393547'>end</span> <span m='393858'>of</span> <span m='394170'>each</span>
  <span m='394482'>instruction</span> <span m='394793'>by</span> <span m='395105'>adding</span>
  <span m='395417'>4</span> <span m='395729'>to</span> <span m='396149'>its</span>
  <span m='396569'>current</span> <span m='396989'>value.</span> </p><p><span m='397409'>This</span>
  <span m='397655'>means</span> <span m='397902'>the</span> <span m='398148'>next</span>
  <span m='398395'>instruction</span> <span m='398641'>will</span> <span m='398888'>come</span>
  <span m='399134'>from</span> <span m='399381'>the</span> <span m='399627'>memory</span>
  <span m='399874'>location</span> <span m='400120'>following</span> <span m='400367'>the</span>
  <span m='400613'>one</span> <span m='400860'>that</span> <span m='401445'>holds</span>
  <span m='402031'>the</span> <span m='402617'>current</span> <span m='403203'>instruction.</span>
  </p><p><span m='403789'>In</span> <span m='404041'>this</span> <span m='404293'>diagram</span>
  <span m='404545'>we</span> <span m='404798'>see</span> <span m='405050'>one</span>
  <span m='405302'>of</span> <span m='405555'>the</span> <span m='405807'>benefits</span>
  <span m='406059'>of</span> <span m='406312'>a</span> <span m='406564'>RISC</span>
  <span m='406816'>architecture:</span> <span m='407069'>there's</span> <span m='407373'>not</span>
  <span m='407677'>much</span> <span m='407982'>logic</span> <span m='408286'>needed</span>
  <span m='408590'>to</span> <span m='408895'>decode</span> <span m='409199'>the</span>
  <span m='409503'>instruction</span> <span m='409808'>to</span> <span m='410112'>produce</span>
  <span m='410416'>the</span> <span m='410721'>signals</span> <span m='411025'>needed</span>
  <span m='411330'>to</span> <span m='411685'>control</span> <span m='412040'>the</span>
  <span m='412395'>datapath.</span> </p><p><span m='412750'>In</span> <span m='413113'>fact,</span>
  <span m='413477'>many</span> <span m='413841'>of</span> <span m='414205'>the</span>
  <span m='414569'>instruction</span> <span m='414933'>fields</span> <span m='415297'>are</span>
  <span m='415661'>used</span> <span m='416025'>as-is!</span> </p>
type: course
uid: 86e4aef41c3396c858d72ed37e31f45e

---
None