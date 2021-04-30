---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 4PkKI_S9TIQ
  parent_uid: 2d9a009055e3dd615f820ac8d0c76116
  title: Video-YouTube-Stream
  type: Video
  uid: 0d7cb7c32ef5a61e931334f9f06d96f1
- id: 3Play-3Play YouTube id-Stream
  media_location: 4PkKI_S9TIQ
  parent_uid: 2d9a009055e3dd615f820ac8d0c76116
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 204aee2b6da95ce93bc0761517f30fd8
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/4PkKI_S9TIQ/default.jpg
  parent_uid: 2d9a009055e3dd615f820ac8d0c76116
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: c86ec7d5cf11053694409035a890f721
- id: 4PkKI_S9TIQ.srt
  parent_uid: 2d9a009055e3dd615f820ac8d0c76116
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c20/c20s2/c20s2v6/communication-topologies-6-28-/4PkKI_S9TIQ.srt
  title: 3play caption file
  type: null
  uid: b29cd322c69d80edb35cc87a965ab98d
- id: 4PkKI_S9TIQ.pdf
  parent_uid: 2d9a009055e3dd615f820ac8d0c76116
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c20/c20s2/c20s2v6/communication-topologies-6-28-/4PkKI_S9TIQ.pdf
  title: 3play pdf file
  type: null
  uid: df44b2ec99aea7543139ed7c3a445063
- id: Caption-3Play YouTube id-SRT
  parent_uid: 2d9a009055e3dd615f820ac8d0c76116
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: bf7e37277aa71e37cd73ad92a9bbea0f
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 2d9a009055e3dd615f820ac8d0c76116
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 22bd9193a0ed0f44c2d4807d772cedea
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_20-02-06_300k.mp4
  parent_uid: 2d9a009055e3dd615f820ac8d0c76116
  title: Video-Internet Archive-MP4
  type: Video
  uid: 1d574d37e9b1433683a740b48b0bd3ef
inline_embed_id: 48228863communicationtopologies62868537924
layout: video
order_index: null
parent_uid: 80856658b8fe622c75e9b1c32b31c084
related_resources_text: ''
short_url: communication-topologies-6-28-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c20/c20s2/c20s2v6/communication-topologies-6-28-
template_type: Embed
title: Communication Topologies (6:28)
transcript: <p><span m='1020'>Let's</span> <span m='1398'>wrap</span> <span m='1777'>up</span>
  <span m='2155'>our</span> <span m='2534'>discussion</span> <span m='2912'>of</span>
  <span m='3291'>system-level</span> <span m='3669'>interconnect</span> <span m='4048'>by</span>
  <span m='4426'>considering</span> <span m='4805'>how</span> <span m='5183'>best</span>
  <span m='5562'>to</span> <span m='5940'>connect</span> <span m='6319'>N</span> <span
  m='6778'>components</span> <span m='7237'>that</span> <span m='7697'>need</span>
  <span m='8156'>to</span> <span m='8616'>send</span> <span m='9075'>messages</span>
  <span m='9535'>to</span> <span m='9994'>one</span> <span m='10453'>another,</span>
  <span m='10913'>e.g.,</span> <span m='11372'>CPUs</span> <span m='11832'>on</span>
  <span m='12291'>a</span> <span m='12751'>multicore</span> <span m='13210'>chip.</span>
  </p><p><span m='13670'>Today</span> <span m='13995'>such</span> <span m='14320'>chips</span>
  <span m='14645'>have</span> <span m='14970'>a</span> <span m='15295'>handful</span>
  <span m='15620'>of</span> <span m='15945'>cores,</span> <span m='16270'>but</span>
  <span m='16595'>soon</span> <span m='16920'>they</span> <span m='17245'>may</span>
  <span m='17570'>have</span> <span m='17895'>100s</span> <span m='18220'>or</span>
  <span m='18545'>1000s</span> <span m='18870'>of</span> <span m='19195'>cores.</span>
  </p><p><span m='19520'>We'll</span> <span m='20003'>build</span> <span m='20487'>our</span>
  <span m='20971'>communications</span> <span m='21455'>network</span> <span m='21938'>using</span>
  <span m='22422'>point-to-point</span> <span m='22906'>links.</span> </p><p><span
  m='23390'>In</span> <span m='23756'>our</span> <span m='24123'>analysis,</span>
  <span m='24490'>each</span> <span m='24856'>point-to-point</span> <span m='25223'>link</span>
  <span m='25590'>is</span> <span m='25956'>counted</span> <span m='26323'>at</span>
  <span m='26690'>a</span> <span m='27056'>cost</span> <span m='27423'>of</span> <span
  m='27790'>1</span> <span m='28156'>hardware</span> <span m='28523'>unit.</span>
  </p><p><span m='28890'>Sending</span> <span m='29297'>a</span> <span m='29704'>message</span>
  <span m='30111'>across</span> <span m='30518'>a</span> <span m='30925'>link</span>
  <span m='31332'>requires</span> <span m='31739'>one</span> <span m='32146'>time</span>
  <span m='32553'>unit.</span> </p><p><span m='32960'>And</span> <span m='33228'>we'll</span>
  <span m='33496'>assume</span> <span m='33764'>that</span> <span m='34032'>different</span>
  <span m='34300'>links</span> <span m='34568'>can</span> <span m='34836'>operate</span>
  <span m='35104'>in</span> <span m='35372'>parallel,</span> <span m='35640'>so</span>
  <span m='35908'>more</span> <span m='36176'>links</span> <span m='36444'>will</span>
  <span m='36712'>mean</span> <span m='36980'>more</span> <span m='37533'>message</span>
  <span m='38086'>traffic.</span> </p><p><span m='38640'>We'll</span> <span m='39168'>do</span>
  <span m='39697'>an</span> <span m='40226'>asymptotic</span> <span m='40754'>analysis</span>
  <span m='41283'>of</span> <span m='41812'>the</span> <span m='42340'>throughput</span>
  <span m='42869'>(total</span> <span m='43398'>messages</span> <span m='43926'>per</span>
  <span m='44455'>unit</span> <span m='44984'>time),</span> <span m='45512'>latency</span>
  <span m='46041'>(worst-case</span> <span m='46570'>time</span> <span m='46939'>to</span>
  <span m='47309'>deliver</span> <span m='47679'>a</span> <span m='48049'>single</span>
  <span m='48419'>message),</span> <span m='48789'>and</span> <span m='49159'>hardware</span>
  <span m='49529'>cost.</span> </p><p><span m='49899'>In</span> <span m='50391'>other</span>
  <span m='50884'>words,</span> <span m='51377'>we'll</span> <span m='51869'>make</span>
  <span m='52362'>a</span> <span m='52855'>rough</span> <span m='53348'>estimate</span>
  <span m='53840'>how</span> <span m='54333'>these</span> <span m='54826'>quantities</span>
  <span m='55319'>change</span> <span m='55811'>as</span> <span m='56304'>N</span>
  <span m='56797'>grows.</span> </p><p><span m='57290'>Note</span> <span m='57614'>that</span>
  <span m='57938'>in</span> <span m='58263'>general</span> <span m='58587'>the</span>
  <span m='58911'>throughput</span> <span m='59236'>and</span> <span m='59560'>hardware</span>
  <span m='59885'>cost</span> <span m='60209'>are</span> <span m='60533'>proportional</span>
  <span m='60858'>to</span> <span m='61182'>the</span> <span m='61506'>number</span>
  <span m='61831'>of</span> <span m='62155'>point-to-point</span> <span m='62480'>links.</span>
  </p><p><span m='63700'>Our</span> <span m='64024'>baseline</span> <span m='64348'>is</span>
  <span m='64672'>the</span> <span m='64997'>backplane</span> <span m='65321'>bus</span>
  <span m='65645'>discussed</span> <span m='65970'>earlier,</span> <span m='66294'>where</span>
  <span m='66618'>all</span> <span m='66942'>the</span> <span m='67267'>components</span>
  <span m='67591'>share</span> <span m='67915'>a</span> <span m='68240'>single</span>
  <span m='69076'>communication</span> <span m='69912'>channel.</span> </p><p><span
  m='70749'>With</span> <span m='71093'>only</span> <span m='71437'>a</span> <span
  m='71781'>single</span> <span m='72125'>channel,</span> <span m='72469'>bus</span>
  <span m='72814'>throughput</span> <span m='73158'>is</span> <span m='73502'>1</span>
  <span m='73846'>message</span> <span m='74190'>per</span> <span m='74534'>unit</span>
  <span m='74879'>time</span> <span m='75223'>and</span> <span m='75567'>a</span>
  <span m='75911'>message</span> <span m='76255'>can</span> <span m='76600'>travel</span>
  <span m='77000'>between</span> <span m='77400'>any</span> <span m='77800'>two</span>
  <span m='78200'>components</span> <span m='78600'>in</span> <span m='79000'>one</span>
  <span m='79400'>time</span> <span m='79800'>unit.</span> </p><p><span m='80200'>Since</span>
  <span m='80501'>each</span> <span m='80803'>component</span> <span m='81105'>has</span>
  <span m='81407'>to</span> <span m='81709'>have</span> <span m='82011'>an</span>
  <span m='82313'>interface</span> <span m='82615'>to</span> <span m='82917'>the</span>
  <span m='83219'>shared</span> <span m='83521'>channel,</span> <span m='83823'>the</span>
  <span m='84125'>total</span> <span m='84427'>hardware</span> <span m='84729'>cost</span>
  <span m='85542'>is</span> <span m='86356'>O(n).</span> </p><p><span m='87170'>In</span>
  <span m='87476'>a</span> <span m='87783'>ring</span> <span m='88090'>network</span>
  <span m='88397'>each</span> <span m='88704'>component</span> <span m='89010'>sends</span>
  <span m='89317'>its</span> <span m='89624'>messages</span> <span m='89931'>to</span>
  <span m='90238'>a</span> <span m='90544'>single</span> <span m='90851'>neighbor</span>
  <span m='91158'>and</span> <span m='91465'>the</span> <span m='91772'>links</span>
  <span m='92079'>are</span> <span m='92424'>arranged</span> <span m='92769'>so</span>
  <span m='93114'>that</span> <span m='93459'>its</span> <span m='93804'>possible</span>
  <span m='94149'>to</span> <span m='94494'>reach</span> <span m='94839'>all</span>
  <span m='95184'>components.</span> </p><p><span m='95529'>There</span> <span m='96023'>are</span>
  <span m='96517'>N</span> <span m='97012'>links</span> <span m='97506'>in</span>
  <span m='98000'>total,</span> <span m='98495'>so</span> <span m='98989'>the</span>
  <span m='99483'>throughput</span> <span m='99978'>and</span> <span m='100472'>cost</span>
  <span m='100966'>are</span> <span m='101461'>both</span> <span m='101955'>O(n).</span>
  </p><p><span m='102450'>The</span> <span m='102794'>worst</span> <span m='103138'>case</span>
  <span m='103482'>latency</span> <span m='103827'>is</span> <span m='104171'>also</span>
  <span m='104515'>O(n)</span> <span m='104860'>since</span> <span m='105204'>a</span>
  <span m='105548'>message</span> <span m='105893'>might</span> <span m='106237'>have</span>
  <span m='106581'>to</span> <span m='106926'>travel</span> <span m='107270'>across</span>
  <span m='107614'>N-1</span> <span m='107959'>links</span> <span m='108465'>to</span>
  <span m='108971'>reach</span> <span m='109477'>the</span> <span m='109984'>neighbor</span>
  <span m='110490'>that's</span> <span m='110996'>immediately</span> <span m='111502'>upstream.</span>
  </p><p><span m='112009'>Ring</span> <span m='112381'>topologies</span> <span m='112754'>are</span>
  <span m='113127'>useful</span> <span m='113500'>when</span> <span m='113873'>message</span>
  <span m='114246'>latency</span> <span m='114619'>isn't</span> <span m='114991'>important</span>
  <span m='115364'>or</span> <span m='115737'>when</span> <span m='116110'>most</span>
  <span m='116483'>messages</span> <span m='116856'>are</span> <span m='117229'>to</span>
  <span m='117709'>the</span> <span m='118190'>component</span> <span m='118671'>that's</span>
  <span m='119152'>immediately</span> <span m='119632'>downstream,</span> <span m='120113'>i.e.,</span>
  <span m='120594'>the</span> <span m='121075'>components</span> <span m='121555'>form</span>
  <span m='122036'>a</span> <span m='122517'>processing</span> <span m='122998'>pipeline.</span>
  </p><p><span m='123479'>The</span> <span m='123799'>most</span> <span m='124119'>general</span>
  <span m='124439'>network</span> <span m='124759'>topology</span> <span m='125079'>is</span>
  <span m='125399'>when</span> <span m='125719'>every</span> <span m='126039'>component</span>
  <span m='126359'>has</span> <span m='126679'>a</span> <span m='126999'>direct</span>
  <span m='127319'>link</span> <span m='127639'>to</span> <span m='127959'>every</span>
  <span m='128280'>other</span> <span m='129140'>component.</span> </p><p><span m='130000'>There</span>
  <span m='130440'>are</span> <span m='130880'>O(N**2)</span> <span m='131320'>links</span>
  <span m='131760'>so</span> <span m='132200'>the</span> <span m='132640'>throughput</span>
  <span m='133080'>and</span> <span m='133520'>cost</span> <span m='133960'>are</span>
  <span m='134400'>both</span> <span m='134840'>O(N**2).</span> </p><p><span m='135280'>And</span>
  <span m='135794'>the</span> <span m='136309'>latency</span> <span m='136823'>is</span>
  <span m='137338'>1</span> <span m='137853'>time</span> <span m='138367'>unit</span>
  <span m='138882'>since</span> <span m='139396'>each</span> <span m='139911'>destination</span>
  <span m='140426'>is</span> <span m='140940'>directly</span> <span m='141455'>accessible.</span>
  </p><p><span m='141970'>Although</span> <span m='142489'>expensive,</span> <span
  m='143008'>complete</span> <span m='143527'>graphs</span> <span m='144046'>offer</span>
  <span m='144565'>very</span> <span m='145085'>high</span> <span m='145604'>throughput</span>
  <span m='146123'>with</span> <span m='146642'>very</span> <span m='147161'>low</span>
  <span m='147680'>latencies.</span> </p><p><span m='148200'>A</span> <span m='148544'>variant</span>
  <span m='148888'>of</span> <span m='149232'>the</span> <span m='149576'>complete</span>
  <span m='149920'>graph</span> <span m='150264'>is</span> <span m='150608'>the</span>
  <span m='150952'>crossbar</span> <span m='151297'>switch</span> <span m='151641'>where</span>
  <span m='151985'>a</span> <span m='152329'>particular</span> <span m='152673'>row</span>
  <span m='153017'>and</span> <span m='153361'>column</span> <span m='153705'>can</span>
  <span m='154050'>be</span> <span m='154420'>connected</span> <span m='154790'>to</span>
  <span m='155160'>form</span> <span m='155530'>a</span> <span m='155900'>link</span>
  <span m='156270'>between</span> <span m='156640'>particular</span> <span m='157010'>A</span>
  <span m='157380'>and</span> <span m='157750'>B</span> <span m='158120'>components</span>
  <span m='158490'>with</span> <span m='158788'>the</span> <span m='159086'>restriction</span>
  <span m='159384'>that</span> <span m='159682'>each</span> <span m='159980'>row</span>
  <span m='160278'>and</span> <span m='160576'>each</span> <span m='160875'>column</span>
  <span m='161173'>can</span> <span m='161471'>only</span> <span m='161769'>carry</span>
  <span m='162067'>1</span> <span m='162365'>message</span> <span m='162663'>during</span>
  <span m='162961'>each</span> <span m='163260'>time</span> <span m='164095'>unit.</span>
  </p><p><span m='164930'>Assume</span> <span m='165204'>that</span> <span m='165479'>the</span>
  <span m='165754'>first</span> <span m='166029'>row</span> <span m='166304'>and</span>
  <span m='166579'>first</span> <span m='166854'>column</span> <span m='167129'>connect</span>
  <span m='167404'>to</span> <span m='167679'>the</span> <span m='167954'>same</span>
  <span m='168229'>component,</span> <span m='168504'>and</span> <span m='168779'>so</span>
  <span m='169054'>on,</span> <span m='169329'>i.e.,</span> <span m='169732'>that</span>
  <span m='170136'>the</span> <span m='170540'>example</span> <span m='170944'>crossbar</span>
  <span m='171348'>switch</span> <span m='171752'>is</span> <span m='172155'>being</span>
  <span m='172559'>used</span> <span m='172963'>to</span> <span m='173367'>connect</span>
  <span m='173771'>4</span> <span m='174175'>components.</span> </p><p><span m='174579'>Then</span>
  <span m='174996'>there</span> <span m='175414'>are</span> <span m='175832'>O(n)</span>
  <span m='176250'>messages</span> <span m='176668'>delivered</span> <span m='177086'>each</span>
  <span m='177504'>time</span> <span m='177922'>unit,</span> <span m='178340'>with</span>
  <span m='178758'>a</span> <span m='179176'>latency</span> <span m='179594'>of</span>
  <span m='180012'>1.</span> </p><p><span m='180430'>There</span> <span m='180756'>are</span>
  <span m='181083'>N**2</span> <span m='181410'>switches</span> <span m='181737'>in</span>
  <span m='182064'>the</span> <span m='182391'>crossbar,</span> <span m='182718'>so</span>
  <span m='183045'>the</span> <span m='183371'>cost</span> <span m='183698'>is</span>
  <span m='184025'>O(N**2)</span> <span m='184352'>even</span> <span m='184679'>though</span>
  <span m='185006'>there</span> <span m='185333'>are</span> <span m='185660'>only</span>
  <span m='186596'>O(n)</span> <span m='187533'>links.</span> </p><p><span m='188470'>In</span>
  <span m='188850'>mesh</span> <span m='189230'>networks,</span> <span m='189610'>components</span>
  <span m='189990'>are</span> <span m='190370'>connected</span> <span m='190750'>to</span>
  <span m='191130'>some</span> <span m='191510'>fixed</span> <span m='191890'>number</span>
  <span m='192270'>of</span> <span m='192650'>neighboring</span> <span m='193030'>components,</span>
  <span m='193410'>in</span> <span m='193868'>either</span> <span m='194326'>2</span>
  <span m='194785'>or</span> <span m='195243'>3</span> <span m='195701'>dimensions.</span>
  </p><p><span m='196160'>Hence</span> <span m='196495'>the</span> <span m='196831'>total</span>
  <span m='197166'>number</span> <span m='197502'>of</span> <span m='197838'>links</span>
  <span m='198173'>is</span> <span m='198509'>proportional</span> <span m='198845'>to</span>
  <span m='199180'>the</span> <span m='199516'>number</span> <span m='199851'>of</span>
  <span m='200187'>components,</span> <span m='200523'>so</span> <span m='200858'>both</span>
  <span m='201194'>throughput</span> <span m='201530'>and</span> <span m='202167'>cost</span>
  <span m='202804'>are</span> <span m='203441'>O(n).</span> </p><p><span m='204079'>The</span>
  <span m='204406'>worst-case</span> <span m='204734'>latencies</span> <span m='205062'>for</span>
  <span m='205390'>mesh</span> <span m='205718'>networks</span> <span m='206046'>are</span>
  <span m='206374'>proportional</span> <span m='206702'>to</span> <span m='207030'>length</span>
  <span m='207358'>of</span> <span m='207686'>the</span> <span m='208014'>sides,</span>
  <span m='208342'>so</span> <span m='208670'>the</span> <span m='209116'>latency</span>
  <span m='209562'>is</span> <span m='210008'>O(sqrt</span> <span m='210454'>n)</span>
  <span m='210900'>for</span> <span m='211346'>2D</span> <span m='211792'>meshes</span>
  <span m='212238'>and</span> <span m='212684'>O(cube</span> <span m='213130'>root</span>
  <span m='213576'>n)</span> <span m='214022'>for</span> <span m='214468'>3D</span>
  <span m='214914'>meshes.</span> </p><p><span m='215360'>The</span> <span m='215841'>orderly</span>
  <span m='216323'>layout,</span> <span m='216805'>constant</span> <span m='217286'>per-node</span>
  <span m='217768'>hardware</span> <span m='218250'>costs,</span> <span m='218731'>and</span>
  <span m='219213'>modest</span> <span m='219695'>worst-case</span> <span m='220176'>latency</span>
  <span m='220658'>make</span> <span m='221140'>2D</span> <span m='221606'>4-neighbor</span>
  <span m='222073'>meshes</span> <span m='222540'>a</span> <span m='223007'>popular</span>
  <span m='223474'>choice</span> <span m='223941'>for</span> <span m='224408'>the</span>
  <span m='224875'>current</span> <span m='225342'>generation</span> <span m='225809'>of</span>
  <span m='226276'>experimental</span> <span m='226743'>multi-core</span> <span m='227210'>processors.</span>
  </p><p><span m='228930'>Hypercube</span> <span m='229330'>and</span> <span m='229731'>tree</span>
  <span m='230132'>networks</span> <span m='230532'>offer</span> <span m='230933'>logarithmic</span>
  <span m='231334'>latencies,</span> <span m='231735'>which</span> <span m='232135'>for</span>
  <span m='232536'>large</span> <span m='232937'>N</span> <span m='233337'>may</span>
  <span m='233738'>be</span> <span m='234139'>faster</span> <span m='234540'>than</span>
  <span m='235253'>mesh</span> <span m='235966'>networks.</span> </p><p><span m='236680'>The</span>
  <span m='237058'>original</span> <span m='237436'>CM-1</span> <span m='237814'>Connection</span>
  <span m='238192'>Machine</span> <span m='238570'>designed</span> <span m='238948'>in</span>
  <span m='239326'>the</span> <span m='239704'>80's</span> <span m='240082'>used</span>
  <span m='240460'>a</span> <span m='240838'>hypercube</span> <span m='241216'>network</span>
  <span m='241594'>to</span> <span m='241972'>connect</span> <span m='242350'>up</span>
  <span m='243072'>to</span> <span m='243795'>65,536</span> <span m='244518'>very</span>
  <span m='245240'>simple</span> <span m='245963'>processors,</span> <span m='246686'>each</span>
  <span m='247409'>connected</span> <span m='248131'>to</span> <span m='248854'>16</span>
  <span m='249577'>neighbors.</span> </p><p><span m='250300'>Later</span> <span m='250781'>generations</span>
  <span m='251263'>incorporated</span> <span m='251745'>smaller</span> <span m='252227'>numbers</span>
  <span m='252709'>of</span> <span m='253190'>more</span> <span m='253672'>sophisticated</span>
  <span m='254154'>processors,</span> <span m='254636'>still</span> <span m='255118'>connected</span>
  <span m='255600'>by</span> <span m='256237'>a</span> <span m='256874'>hypercube</span>
  <span m='257511'>network.</span> </p><p><span m='258149'>In</span> <span m='258487'>the</span>
  <span m='258826'>early</span> <span m='259165'>90's</span> <span m='259504'>the</span>
  <span m='259843'>last</span> <span m='260182'>generation</span> <span m='260521'>of</span>
  <span m='260860'>Connection</span> <span m='261198'>Machines</span> <span m='261537'>used</span>
  <span m='261876'>a</span> <span m='262215'>tree</span> <span m='262554'>network,</span>
  <span m='262893'>with</span> <span m='263232'>the</span> <span m='263571'>clever</span>
  <span m='263910'>innovation</span> <span m='264283'>that</span> <span m='264656'>the</span>
  <span m='265029'>links</span> <span m='265403'>towards</span> <span m='265776'>the</span>
  <span m='266149'>root</span> <span m='266522'>of</span> <span m='266896'>the</span>
  <span m='267269'>tree</span> <span m='267642'>had</span> <span m='268015'>a</span>
  <span m='268389'>higher</span> <span m='268762'>message</span> <span m='269135'>capacity.</span>
  </p><p><span m='269509'>Here's</span> <span m='269929'>a</span> <span m='270349'>summary</span>
  <span m='270769'>of</span> <span m='271189'>the</span> <span m='271609'>theoretical</span>
  <span m='272029'>latencies</span> <span m='272449'>we</span> <span m='272869'>calculated</span>
  <span m='273289'>for</span> <span m='273709'>the</span> <span m='274129'>various</span>
  <span m='274549'>topologies.</span> </p><p><span m='274970'>As</span> <span m='275244'>a</span>
  <span m='275518'>reality</span> <span m='275793'>check,</span> <span m='276067'>it's</span>
  <span m='276341'>important</span> <span m='276616'>to</span> <span m='276890'>realize</span>
  <span m='277165'>that</span> <span m='277439'>the</span> <span m='277713'>lower</span>
  <span m='277988'>bound</span> <span m='278262'>on</span> <span m='278536'>the</span>
  <span m='278811'>worst-case</span> <span m='279085'>distance</span> <span m='279360'>between</span>
  <span m='279732'>components</span> <span m='280105'>in</span> <span m='280478'>our</span>
  <span m='280850'>3-dimensional</span> <span m='281223'>world</span> <span m='281596'>is</span>
  <span m='281969'>O(cube</span> <span m='282341'>root</span> <span m='282714'>of</span>
  <span m='283087'>N).</span> </p><p><span m='283460'>In</span> <span m='283922'>the</span>
  <span m='284384'>case</span> <span m='284846'>of</span> <span m='285309'>a</span>
  <span m='285771'>2D</span> <span m='286233'>layout,</span> <span m='286696'>the</span>
  <span m='287158'>worst-case</span> <span m='287620'>distance</span> <span m='288083'>is</span>
  <span m='288545'>O(sqrt</span> <span m='289007'>N).</span> </p><p><span m='289470'>Since</span>
  <span m='289766'>we</span> <span m='290062'>know</span> <span m='290358'>that</span>
  <span m='290655'>the</span> <span m='290951'>time</span> <span m='291247'>to</span>
  <span m='291543'>transmit</span> <span m='291840'>a</span> <span m='292136'>message</span>
  <span m='292432'>is</span> <span m='292728'>proportional</span> <span m='293025'>to</span>
  <span m='293321'>the</span> <span m='293617'>distance</span> <span m='293913'>traveled,</span>
  <span m='294210'>we</span> <span m='294757'>should</span> <span m='295304'>modify</span>
  <span m='295851'>our</span> <span m='296398'>latency</span> <span m='296945'>calculations</span>
  <span m='297493'>to</span> <span m='298040'>reflect</span> <span m='298587'>this</span>
  <span m='299134'>physical</span> <span m='299681'>constraint.</span> </p><p><span
  m='300229'>Note</span> <span m='300569'>that</span> <span m='300909'>the</span>
  <span m='301249'>bus</span> <span m='301589'>and</span> <span m='301929'>crossbar</span>
  <span m='302269'>involve</span> <span m='302609'>N</span> <span m='302949'>connections</span>
  <span m='303289'>to</span> <span m='303629'>a</span> <span m='303969'>single</span>
  <span m='304309'>link,</span> <span m='304649'>so</span> <span m='304989'>here</span>
  <span m='305329'>the</span> <span m='305669'>lower-bound</span> <span m='306009'>on</span>
  <span m='306446'>the</span> <span m='306884'>latency</span> <span m='307322'>needs</span>
  <span m='307759'>to</span> <span m='308197'>reflect</span> <span m='308635'>the</span>
  <span m='309072'>capacitive</span> <span m='309510'>load</span> <span m='309948'>added</span>
  <span m='310385'>by</span> <span m='310823'>each</span> <span m='311261'>connection.</span>
  </p><p><span m='311699'>The</span> <span m='312414'>winner?</span> </p><p><span
  m='313130'>Mesh</span> <span m='313473'>networks</span> <span m='313816'>avoid</span>
  <span m='314159'>the</span> <span m='314503'>need</span> <span m='314846'>for</span>
  <span m='315189'>longer</span> <span m='315532'>wires</span> <span m='315876'>as</span>
  <span m='316219'>the</span> <span m='316562'>number</span> <span m='316905'>of</span>
  <span m='317249'>connected</span> <span m='317592'>components</span> <span m='317935'>grows</span>
  <span m='318279'>and</span> <span m='318719'>appear</span> <span m='319160'>to</span>
  <span m='319601'>be</span> <span m='320042'>an</span> <span m='320483'>attractive</span>
  <span m='320924'>alternative</span> <span m='321364'>for</span> <span m='321805'>high-capacity</span>
  <span m='322246'>communication</span> <span m='322687'>networks</span> <span m='323128'>connecting</span>
  <span m='323569'>1000's</span> <span m='324512'>of</span> <span m='325456'>processors.</span>
  </p><p><span m='326400'>Summarizing</span> <span m='326785'>our</span> <span m='327171'>discussion:</span>
  <span m='327557'>point-to-point</span> <span m='327943'>links</span> <span m='328329'>are</span>
  <span m='328715'>in</span> <span m='329101'>common</span> <span m='329487'>use</span>
  <span m='329873'>today</span> <span m='330259'>for</span> <span m='330649'>system-level</span>
  <span m='331039'>interconnect,</span> <span m='331429'>and</span> <span m='331819'>as</span>
  <span m='332209'>a</span> <span m='332599'>result</span> <span m='332989'>our</span>
  <span m='333379'>systems</span> <span m='333769'>are</span> <span m='334159'>faster,</span>
  <span m='334549'>more</span> <span m='334939'>reliable,</span> <span m='335329'>more</span>
  <span m='335720'>energy-efficient</span> <span m='336298'>and</span> <span m='336876'>smaller</span>
  <span m='337454'>than</span> <span m='338032'>ever</span> <span m='338610'>before.</span>
  </p><p><span m='339189'>Multi-signal</span> <span m='339693'>parallel</span> <span
  m='340198'>buses</span> <span m='340702'>are</span> <span m='341207'>still</span>
  <span m='341712'>used</span> <span m='342216'>for</span> <span m='342721'>very-high-bandwidth</span>
  <span m='343226'>connections</span> <span m='343730'>to</span> <span m='344235'>memories,</span>
  <span m='344740'>with</span> <span m='345109'>a</span> <span m='345479'>lot</span>
  <span m='345849'>of</span> <span m='346219'>very</span> <span m='346589'>careful</span>
  <span m='346959'>engineering</span> <span m='347329'>to</span> <span m='347699'>avoid</span>
  <span m='348069'>the</span> <span m='348439'>electrical</span> <span m='348809'>problems</span>
  <span m='349179'>observed</span> <span m='349549'>in</span> <span m='349919'>earlier</span>
  <span m='351219'>bus</span> <span m='352519'>implementations.</span> </p><p><span
  m='353819'>Wireless</span> <span m='354177'>connections</span> <span m='354535'>are</span>
  <span m='354894'>in</span> <span m='355252'>common</span> <span m='355611'>use</span>
  <span m='355969'>to</span> <span m='356328'>connect</span> <span m='356686'>mobile</span>
  <span m='357045'>devices</span> <span m='357403'>to</span> <span m='357762'>nearby</span>
  <span m='358120'>components</span> <span m='358479'>and</span> <span m='358792'>there</span>
  <span m='359105'>has</span> <span m='359418'>been</span> <span m='359731'>interesting</span>
  <span m='360044'>work</span> <span m='360358'>on</span> <span m='360671'>how</span>
  <span m='360984'>to</span> <span m='361297'>allow</span> <span m='361610'>mobile</span>
  <span m='361924'>devices</span> <span m='362237'>to</span> <span m='362550'>discover</span>
  <span m='362863'>what</span> <span m='363176'>peripherals</span> <span m='363490'>are</span>
  <span m='364031'>nearby</span> <span m='364572'>and</span> <span m='365113'>enable</span>
  <span m='365654'>them</span> <span m='366195'>to</span> <span m='366736'>connect</span>
  <span m='367277'>automatically.</span> </p><p><span m='367819'>The</span> <span
  m='368149'>upcoming</span> <span m='368479'>generation</span> <span m='368809'>of</span>
  <span m='369139'>multi-core</span> <span m='369469'>chips</span> <span m='369799'>will</span>
  <span m='370129'>have</span> <span m='370459'>10's</span> <span m='370789'>to</span>
  <span m='371119'>100's</span> <span m='371449'>of</span> <span m='371779'>processing</span>
  <span m='372109'>cores.</span> </p><p><span m='372439'>There</span> <span m='372816'>is</span>
  <span m='373194'>a</span> <span m='373572'>lot</span> <span m='373950'>ongoing</span>
  <span m='374328'>research</span> <span m='374706'>to</span> <span m='375084'>determine</span>
  <span m='375461'>which</span> <span m='375839'>communication</span> <span m='376217'>topology</span>
  <span m='376595'>would</span> <span m='376973'>offer</span> <span m='377351'>the</span>
  <span m='377729'>best</span> <span m='378333'>combination</span> <span m='378937'>of</span>
  <span m='379542'>high</span> <span m='380146'>communication</span> <span m='380751'>bandwidth</span>
  <span m='381355'>and</span> <span m='381960'>low</span> <span m='382564'>latency.</span>
  </p><p><span m='383169'>The</span> <span m='383499'>next</span> <span m='383829'>ten</span>
  <span m='384159'>years</span> <span m='384489'>will</span> <span m='384819'>be</span>
  <span m='385149'>an</span> <span m='385479'>interesting</span> <span m='385809'>time</span>
  <span m='386139'>for</span> <span m='386469'>on-chip</span> <span m='386799'>network</span>
  <span m='387129'>engineers!</span> </p>
type: course
uid: 2d9a009055e3dd615f820ac8d0c76116

---
None