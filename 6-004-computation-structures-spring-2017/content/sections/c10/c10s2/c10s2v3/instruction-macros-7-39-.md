---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: ffgPLOLPCYU
  parent_uid: 2edba4bf9e58c9ba0c870a7934b68dcd
  title: Video-YouTube-Stream
  type: Video
  uid: f41c19ef677a24e7d55d0721ac1e7fc4
- id: 3Play-3Play YouTube id-Stream
  media_location: ffgPLOLPCYU
  parent_uid: 2edba4bf9e58c9ba0c870a7934b68dcd
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: b871df8cee4dc151fcb17cf1157beda9
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/ffgPLOLPCYU/default.jpg
  parent_uid: 2edba4bf9e58c9ba0c870a7934b68dcd
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 28dbcb59bc7cb216b7fda1b267c95e1b
- id: ffgPLOLPCYU.srt
  parent_uid: 2edba4bf9e58c9ba0c870a7934b68dcd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c10/c10s2/c10s2v3/instruction-macros-7-39-/ffgPLOLPCYU.srt
  title: 3play caption file
  type: null
  uid: 472f428c9c6e7b714ab6d058d18a1e36
- id: ffgPLOLPCYU.pdf
  parent_uid: 2edba4bf9e58c9ba0c870a7934b68dcd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c10/c10s2/c10s2v3/instruction-macros-7-39-/ffgPLOLPCYU.pdf
  title: 3play pdf file
  type: null
  uid: 896c52301a6d2241697e30d86a05dbe8
- id: Caption-3Play YouTube id-SRT
  parent_uid: 2edba4bf9e58c9ba0c870a7934b68dcd
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 9e8641bf3b2d59b7b10ad86ca949050f
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 2edba4bf9e58c9ba0c870a7934b68dcd
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 1b8a07323d565683f77c08e46073b0cb
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_10-02-03_300k.mp4
  parent_uid: 2edba4bf9e58c9ba0c870a7934b68dcd
  title: Video-Internet Archive-MP4
  type: Video
  uid: 1e178cae14efd89129cad1f201d3cade
inline_embed_id: 22341539instructionmacros73961983228
layout: video
order_index: null
parent_uid: 01cfd93ce038a119a16e50953f352e29
related_resources_text: ''
short_url: instruction-macros-7-39-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c10/c10s2/c10s2v3/instruction-macros-7-39-
template_type: Embed
title: Instruction Macros (7:39)
transcript: <p><span m='1180'>Let's</span> <span m='1571'>take</span> <span m='1963'>a</span>
  <span m='2355'>closer</span> <span m='2747'>look</span> <span m='3139'>at</span>
  <span m='3530'>how</span> <span m='3922'>macros</span> <span m='4314'>work</span>
  <span m='4706'>in</span> <span m='5098'>UASM.</span> </p><p><span m='5490'>Here</span>
  <span m='5858'>we</span> <span m='6227'>see</span> <span m='6596'>the</span> <span
  m='6964'>definition</span> <span m='7333'>of</span> <span m='7702'>the</span> <span
  m='8070'>macro</span> <span m='8439'>"consec"</span> <span m='8808'>which</span>
  <span m='9176'>has</span> <span m='9545'>a</span> <span m='9914'>single</span> <span
  m='10282'>parameter</span> <span m='10651'>"n".</span> </p><p><span m='11020'>The</span>
  <span m='11385'>body</span> <span m='11750'>of</span> <span m='12116'>the</span>
  <span m='12481'>macro</span> <span m='12847'>is</span> <span m='13212'>a</span>
  <span m='13578'>sequence</span> <span m='13943'>of</span> <span m='14309'>four</span>
  <span m='14674'>expressions.</span> </p><p><span m='15040'>When</span> <span m='15382'>there's</span>
  <span m='15725'>an</span> <span m='16068'>invocation</span> <span m='16410'>of</span>
  <span m='16753'>the</span> <span m='17096'>"consec"</span> <span m='17438'>macro,</span>
  <span m='17781'>in</span> <span m='18124'>this</span> <span m='18466'>example</span>
  <span m='18809'>with</span> <span m='19152'>the</span> <span m='19494'>argument</span>
  <span m='19837'>37,</span> <span m='20180'>the</span> <span m='20615'>body</span>
  <span m='21051'>of</span> <span m='21486'>the</span> <span m='21922'>macro</span>
  <span m='22358'>is</span> <span m='22793'>expanded</span> <span m='23229'>replacing</span>
  <span m='23665'>all</span> <span m='24100'>occurrences</span> <span m='24536'>of</span>
  <span m='24971'>"n"</span> <span m='25407'>with</span> <span m='25843'>the</span>
  <span m='26278'>argument</span> <span m='26714'>37.</span> </p><p><span m='27150'>The</span>
  <span m='27522'>resulting</span> <span m='27894'>text</span> <span m='28267'>is</span>
  <span m='28639'>then</span> <span m='29011'>processed</span> <span m='29384'>as</span>
  <span m='29756'>if</span> <span m='30128'>it</span> <span m='30501'>had</span> <span
  m='30873'>appeared</span> <span m='31245'>in</span> <span m='31618'>place</span>
  <span m='31990'>of</span> <span m='32362'>the</span> <span m='32735'>macro</span>
  <span m='33107'>invocation.</span> </p><p><span m='33480'>In</span> <span m='33780'>this</span>
  <span m='34080'>example,</span> <span m='34380'>the</span> <span m='34680'>four</span>
  <span m='34980'>expressions</span> <span m='35280'>are</span> <span m='35580'>evaluated</span>
  <span m='35880'>to</span> <span m='36180'>give</span> <span m='36480'>a</span> <span
  m='36780'>sequence</span> <span m='37080'>of</span> <span m='37380'>four</span>
  <span m='37680'>values</span> <span m='37980'>that</span> <span m='38369'>will</span>
  <span m='38758'>be</span> <span m='39147'>placed</span> <span m='39536'>in</span>
  <span m='39926'>the</span> <span m='40315'>next</span> <span m='40704'>four</span>
  <span m='41093'>bytes</span> <span m='41483'>of</span> <span m='41872'>the</span>
  <span m='42261'>output</span> <span m='42650'>array.</span> </p><p><span m='43040'>Macro</span>
  <span m='43499'>expansions</span> <span m='43958'>may</span> <span m='44417'>contain</span>
  <span m='44876'>other</span> <span m='45336'>macro</span> <span m='45795'>invocations,</span>
  <span m='46254'>which</span> <span m='46713'>themselves</span> <span m='47173'>will</span>
  <span m='47632'>be</span> <span m='48091'>expanded,</span> <span m='48550'>continuing</span>
  <span m='49010'>until</span> <span m='49430'>all</span> <span m='49850'>that's</span>
  <span m='50270'>left</span> <span m='50690'>are</span> <span m='51110'>expressions</span>
  <span m='51530'>to</span> <span m='51950'>be</span> <span m='52370'>evaluated.</span>
  </p><p><span m='52790'>Here</span> <span m='53130'>we</span> <span m='53471'>see</span>
  <span m='53811'>the</span> <span m='54152'>macro</span> <span m='54493'>definition</span>
  <span m='54833'>for</span> <span m='55174'>WORD,</span> <span m='55514'>which</span>
  <span m='55855'>assembles</span> <span m='56196'>its</span> <span m='56536'>argument</span>
  <span m='56877'>into</span> <span m='57217'>two</span> <span m='57558'>consecutive</span>
  <span m='57899'>bytes.</span> </p><p><span m='59170'>And</span> <span m='59545'>for</span>
  <span m='59921'>the</span> <span m='60297'>macro</span> <span m='60672'>LONG,</span>
  <span m='61048'>which</span> <span m='61424'>assembles</span> <span m='61800'>its</span>
  <span m='62175'>argument</span> <span m='62551'>into</span> <span m='62927'>four</span>
  <span m='63302'>consecutive</span> <span m='63678'>bytes,</span> <span m='64054'>using</span>
  <span m='64430'>the</span> <span m='64723'>WORD</span> <span m='65016'>macro</span>
  <span m='65309'>to</span> <span m='65602'>process</span> <span m='65895'>the</span>
  <span m='66188'>low</span> <span m='66482'>16</span> <span m='66775'>bits</span>
  <span m='67068'>of</span> <span m='67361'>the</span> <span m='67654'>value,</span>
  <span m='67947'>then</span> <span m='68241'>the</span> <span m='68534'>high</span>
  <span m='68827'>16</span> <span m='69120'>bits</span> <span m='69413'>of</span>
  <span m='69706'>the</span> <span m='70000'>value.</span> </p><p><span m='71000'>These</span>
  <span m='71467'>two</span> <span m='71934'>UASM</span> <span m='72401'>statements</span>
  <span m='72868'>cause</span> <span m='73335'>the</span> <span m='73802'>constant</span>
  <span m='74269'>0xDEADBEEF</span> <span m='74736'>to</span> <span m='75203'>converted</span>
  <span m='75670'>to</span> <span m='76137'>4</span> <span m='76604'>bytes,</span>
  <span m='77071'>which</span> <span m='77539'>are</span> <span m='78052'>then</span>
  <span m='78566'>deposited</span> <span m='79080'>in</span> <span m='79593'>the</span>
  <span m='80107'>output</span> <span m='80621'>array</span> <span m='81135'>starting</span>
  <span m='81648'>at</span> <span m='82162'>index</span> <span m='82676'>0x100.</span>
  </p><p><span m='83190'>Note</span> <span m='83465'>that</span> <span m='83741'>the</span>
  <span m='84016'>Beta</span> <span m='84292'>expects</span> <span m='84568'>the</span>
  <span m='84843'>least-significant</span> <span m='85119'>byte</span> <span m='85395'>of</span>
  <span m='85670'>a</span> <span m='85946'>multi-byte</span> <span m='86221'>value</span>
  <span m='86497'>to</span> <span m='86773'>be</span> <span m='87048'>stored</span>
  <span m='87324'>at</span> <span m='87600'>the</span> <span m='88162'>lowest</span>
  <span m='88725'>byte</span> <span m='89287'>address.</span> </p><p><span m='89850'>So</span>
  <span m='90326'>the</span> <span m='90803'>least-significant</span> <span m='91280'>byte</span>
  <span m='91757'>0xEF</span> <span m='92234'>is</span> <span m='92711'>placed</span>
  <span m='93187'>at</span> <span m='93664'>address</span> <span m='94141'>0x100</span>
  <span m='94618'>and</span> <span m='95095'>the</span> <span m='95572'>most-significant</span>
  <span m='96049'>byte</span> <span m='96803'>0xDE</span> <span m='97557'>is</span>
  <span m='98312'>placed</span> <span m='99066'>at</span> <span m='99821'>address</span>
  <span m='100575'>0x103.</span> </p><p><span m='101330'>This</span> <span m='101736'>is</span>
  <span m='102142'>the</span> <span m='102548'>"little-endian"</span> <span m='102955'>convention</span>
  <span m='103361'>for</span> <span m='103767'>multi-byte</span> <span m='104173'>values:</span>
  <span m='104580'>the</span> <span m='104986'>least-significant</span> <span m='105392'>byte</span>
  <span m='105799'>comes</span> <span m='106734'>first.</span> </p><p><span m='107670'>Intel's</span>
  <span m='108433'>x86</span> <span m='109196'>architecture</span> <span m='109960'>is</span>
  <span m='110723'>also</span> <span m='111486'>little-endian.</span> </p><p><span
  m='112250'>There</span> <span m='112738'>is</span> <span m='113226'>a</span> <span
  m='113715'>symmetrical</span> <span m='114203'>"big-endian"</span> <span m='114691'>convention</span>
  <span m='115180'>where</span> <span m='115668'>the</span> <span m='116156'>most-significant</span>
  <span m='116645'>byte</span> <span m='117133'>comes</span> <span m='117621'>first.</span>
  </p><p><span m='118110'>Both</span> <span m='118474'>conventions</span> <span m='118838'>are</span>
  <span m='119202'>in</span> <span m='119566'>active</span> <span m='119930'>use</span>
  <span m='120294'>and,</span> <span m='120658'>in</span> <span m='121022'>fact,</span>
  <span m='121386'>some</span> <span m='121750'>ISAs</span> <span m='122114'>can</span>
  <span m='122478'>be</span> <span m='122842'>configured</span> <span m='123206'>to</span>
  <span m='123570'>use</span> <span m='123934'>either</span> <span m='124299'>convention!</span>
  </p><p><span m='125409'>There</span> <span m='125672'>is</span> <span m='125936'>no</span>
  <span m='126199'>right</span> <span m='126463'>answer</span> <span m='126726'>for</span>
  <span m='126990'>which</span> <span m='127253'>convention</span> <span m='127517'>to</span>
  <span m='127780'>use,</span> <span m='128044'>but</span> <span m='128307'>the</span>
  <span m='128571'>fact</span> <span m='128834'>that</span> <span m='129098'>there</span>
  <span m='129361'>two</span> <span m='129625'>conventions</span> <span m='129889'>means</span>
  <span m='130220'>that</span> <span m='130551'>we</span> <span m='130882'>have</span>
  <span m='131214'>to</span> <span m='131545'>be</span> <span m='131876'>alert</span>
  <span m='132207'>for</span> <span m='132539'>the</span> <span m='132870'>need</span>
  <span m='133201'>to</span> <span m='133532'>convert</span> <span m='133864'>the</span>
  <span m='134195'>representation</span> <span m='134526'>of</span> <span m='134857'>multi-byte</span>
  <span m='135189'>values</span> <span m='135614'>when</span> <span m='136040'>moving</span>
  <span m='136465'>values</span> <span m='136891'>between</span> <span m='137317'>one</span>
  <span m='137742'>ISA</span> <span m='138168'>and</span> <span m='138594'>another,</span>
  <span m='139019'>e.g.,</span> <span m='139445'>when</span> <span m='139870'>we</span>
  <span m='140296'>send</span> <span m='140722'>a</span> <span m='141147'>data</span>
  <span m='141573'>file</span> <span m='141999'>to</span> <span m='142855'>another</span>
  <span m='143712'>user.</span> </p><p><span m='144569'>As</span> <span m='144824'>you</span>
  <span m='145079'>can</span> <span m='145334'>imagine</span> <span m='145590'>there</span>
  <span m='145845'>are</span> <span m='146100'>strong</span> <span m='146356'>advocates</span>
  <span m='146611'>for</span> <span m='146866'>both</span> <span m='147121'>schemes</span>
  <span m='147377'>who</span> <span m='147632'>are</span> <span m='147887'>happy</span>
  <span m='148143'>to</span> <span m='148398'>defend</span> <span m='148653'>their</span>
  <span m='148909'>point</span> <span m='149230'>of</span> <span m='149552'>view</span>
  <span m='149874'>at</span> <span m='150196'>great</span> <span m='150518'>length.</span>
  </p><p><span m='150840'>Given</span> <span m='151187'>the</span> <span m='151535'>heat</span>
  <span m='151882'>of</span> <span m='152230'>the</span> <span m='152577'>discussion,</span>
  <span m='152925'>it's</span> <span m='153272'>appropriate</span> <span m='153620'>that</span>
  <span m='153967'>the</span> <span m='154315'>names</span> <span m='154662'>for</span>
  <span m='155010'>the</span> <span m='155357'>conventions</span> <span m='155705'>were</span>
  <span m='156052'>drawn</span> <span m='156400'>from</span> <span m='156792'>Jonathan</span>
  <span m='157185'>Swift's</span> <span m='157578'>"Gulliver's</span> <span m='157971'>Travels"</span>
  <span m='158364'>in</span> <span m='158757'>which</span> <span m='159150'>a</span>
  <span m='159542'>civil</span> <span m='159935'>war</span> <span m='160328'>is</span>
  <span m='160721'>fought</span> <span m='161114'>over</span> <span m='161507'>whether</span>
  <span m='161900'>to</span> <span m='162313'>open</span> <span m='162726'>a</span>
  <span m='163139'>soft-boiled</span> <span m='163552'>egg</span> <span m='163965'>at</span>
  <span m='164378'>its</span> <span m='164791'>big</span> <span m='165204'>end</span>
  <span m='165617'>or</span> <span m='166030'>its</span> <span m='166443'>little</span>
  <span m='166856'>end.</span> </p><p><span m='167269'>Let's</span> <span m='167725'>look</span>
  <span m='168181'>at</span> <span m='168637'>the</span> <span m='169093'>macros</span>
  <span m='169549'>used</span> <span m='170005'>to</span> <span m='170461'>assemble</span>
  <span m='170917'>Beta</span> <span m='171373'>instructions.</span> </p><p><span
  m='171829'>The</span> <span m='172269'>BETAOP</span> <span m='172710'>helper</span>
  <span m='173151'>macro</span> <span m='173592'>supports</span> <span m='174032'>the</span>
  <span m='174473'>3-register</span> <span m='174914'>instruction</span> <span m='175355'>format,</span>
  <span m='175795'>taking</span> <span m='176236'>as</span> <span m='176677'>arguments</span>
  <span m='177118'>the</span> <span m='177559'>values</span> <span m='178104'>to</span>
  <span m='178650'>be</span> <span m='179196'>placed</span> <span m='179742'>in</span>
  <span m='180288'>the</span> <span m='180834'>OPCODE,</span> <span m='181379'>Ra,</span>
  <span m='181925'>Rb,</span> <span m='182471'>and</span> <span m='183017'>Rc</span>
  <span m='183563'>fields.</span> </p><p><span m='184109'>The</span> <span m='184436'>".align</span>
  <span m='184763'>4"</span> <span m='185091'>directive</span> <span m='185418'>is</span>
  <span m='185745'>a</span> <span m='186073'>bit</span> <span m='186400'>of</span>
  <span m='186727'>administrative</span> <span m='187055'>bookkeeping</span> <span
  m='187382'>to</span> <span m='187709'>ensure</span> <span m='188037'>that</span>
  <span m='188364'>instructions</span> <span m='188691'>will</span> <span m='189019'>have</span>
  <span m='189410'>a</span> <span m='189801'>byte</span> <span m='190192'>address</span>
  <span m='190583'>that's</span> <span m='190975'>a</span> <span m='191366'>multiple</span>
  <span m='191757'>of</span> <span m='192148'>4,</span> <span m='192540'>i.e.,</span>
  <span m='192931'>that</span> <span m='193322'>they</span> <span m='193713'>span</span>
  <span m='194105'>exactly</span> <span m='194496'>one</span> <span m='194887'>32-bit</span>
  <span m='195278'>word</span> <span m='195670'>in</span> <span m='196655'>memory.</span>
  </p><p><span m='197640'>That's</span> <span m='197944'>followed</span> <span m='198249'>by</span>
  <span m='198553'>an</span> <span m='198858'>invocation</span> <span m='199163'>of</span>
  <span m='199467'>the</span> <span m='199772'>LONG</span> <span m='200077'>macro</span>
  <span m='200381'>to</span> <span m='200686'>generate</span> <span m='200991'>the</span>
  <span m='201295'>4</span> <span m='201600'>bytes</span> <span m='201905'>of</span>
  <span m='202209'>binary</span> <span m='202514'>data</span> <span m='202819'>representing</span>
  <span m='203311'>the</span> <span m='203804'>value</span> <span m='204296'>of</span>
  <span m='204789'>the</span> <span m='205282'>expression</span> <span m='205774'>shown</span>
  <span m='206267'>here.</span> </p><p><span m='206760'>The</span> <span m='207135'>expression</span>
  <span m='207511'>is</span> <span m='207887'>where</span> <span m='208263'>the</span>
  <span m='208638'>actual</span> <span m='209014'>assembly</span> <span m='209390'>of</span>
  <span m='209766'>the</span> <span m='210141'>fields</span> <span m='210517'>takes</span>
  <span m='210893'>place.</span> </p><p><span m='211269'>Each</span> <span m='211601'>field</span>
  <span m='211934'>is</span> <span m='212267'>limited</span> <span m='212599'>to</span>
  <span m='212932'>requisite</span> <span m='213265'>number</span> <span m='213598'>of</span>
  <span m='213930'>bits</span> <span m='214263'>using</span> <span m='214596'>the</span>
  <span m='214929'>modulo</span> <span m='215261'>operator</span> <span m='215594'>(%),</span>
  <span m='215927'>then</span> <span m='216260'>shifted</span> <span m='216721'>left</span>
  <span m='217183'>(&lt;</span> <span m='217645'>to</span> <span m='218107'>the</span>
  <span m='218569'>correct</span> <span m='219030'>position</span> <span m='219492'>in</span>
  <span m='219954'>the</span> <span m='220416'>32-bit</span> <span m='220878'>word.</span>
  </p><p><span m='221340'>And</span> <span m='221726'>here</span> <span m='222112'>are</span>
  <span m='222498'>the</span> <span m='222884'>helper</span> <span m='223270'>macros</span>
  <span m='223656'>for</span> <span m='224042'>the</span> <span m='224428'>instructions</span>
  <span m='224815'>that</span> <span m='225201'>use</span> <span m='225587'>a</span>
  <span m='225973'>16-bit</span> <span m='226359'>constant</span> <span m='226745'>as</span>
  <span m='227131'>the</span> <span m='227517'>second</span> <span m='227903'>operand.</span>
  </p><p><span m='228290'>Let's</span> <span m='228629'>follow</span> <span m='228968'>the</span>
  <span m='229307'>assembly</span> <span m='229646'>of</span> <span m='229985'>an</span>
  <span m='230324'>ADDC</span> <span m='230664'>instruction</span> <span m='231003'>to</span>
  <span m='231342'>see</span> <span m='231681'>how</span> <span m='232020'>this</span>
  <span m='232359'>works.</span> </p><p><span m='232699'>The</span> <span m='233126'>ADDC</span>
  <span m='233554'>macro</span> <span m='233982'>expands</span> <span m='234410'>into</span>
  <span m='234838'>an</span> <span m='235266'>invocation</span> <span m='235694'>of</span>
  <span m='236121'>the</span> <span m='236549'>BETAOPC</span> <span m='236977'>helper</span>
  <span m='237405'>macro,</span> <span m='237833'>passing</span> <span m='238261'>along</span>
  <span m='238689'>the</span> <span m='239198'>correct</span> <span m='239707'>value</span>
  <span m='240216'>for</span> <span m='240725'>the</span> <span m='241234'>ADDC</span>
  <span m='241744'>opcode,</span> <span m='242253'>along</span> <span m='242762'>with</span>
  <span m='243271'>the</span> <span m='243780'>three</span> <span m='244289'>operands.</span>
  </p><p><span m='244799'>The</span> <span m='245214'>BETAOPC</span> <span m='245629'>macro</span>
  <span m='246044'>does</span> <span m='246459'>the</span> <span m='246874'>following</span>
  <span m='247289'>arithmetic:</span> <span m='247704'>the</span> <span m='248119'>OP</span>
  <span m='248534'>argument,</span> <span m='248949'>in</span> <span m='249364'>this</span>
  <span m='249779'>case</span> <span m='250194'>the</span> <span m='250609'>value</span>
  <span m='251024'>0x30,</span> <span m='251439'>is</span> <span m='251850'>shifted</span>
  <span m='252262'>left</span> <span m='252674'>to</span> <span m='253086'>occupy</span>
  <span m='253497'>the</span> <span m='253909'>high-order</span> <span m='254321'>6</span>
  <span m='254733'>bits</span> <span m='255144'>of</span> <span m='255556'>the</span>
  <span m='255968'>instruction.</span> </p><p><span m='256380'>Then</span> <span m='256807'>the</span>
  <span m='257235'>RA</span> <span m='257663'>argument,</span> <span m='258091'>in</span>
  <span m='258519'>this</span> <span m='258947'>case</span> <span m='259375'>15,</span>
  <span m='259802'>is</span> <span m='260230'>placed</span> <span m='260658'>in</span>
  <span m='261086'>its</span> <span m='261514'>proper</span> <span m='261942'>location.</span>
  </p><p><span m='262370'>The</span> <span m='262877'>16-bit</span> <span m='263384'>constant</span>
  <span m='263891'>-32768</span> <span m='264398'>is</span> <span m='264905'>positioned</span>
  <span m='265412'>in</span> <span m='265920'>the</span> <span m='266427'>low</span>
  <span m='266934'>16</span> <span m='267441'>bits</span> <span m='267948'>of</span>
  <span m='268455'>the</span> <span m='268962'>instruction.</span> </p><p><span m='269470'>And,</span>
  <span m='269948'>finally,</span> <span m='270426'>the</span> <span m='270905'>Rc</span>
  <span m='271383'>argument,</span> <span m='271861'>in</span> <span m='272340'>this</span>
  <span m='272818'>case</span> <span m='273296'>0,</span> <span m='273775'>is</span>
  <span m='274253'>positioned</span> <span m='274731'>in</span> <span m='275210'>the</span>
  <span m='275688'>Rc</span> <span m='276166'>field</span> <span m='276645'>of</span>
  <span m='277123'>the</span> <span m='277601'>instruction.</span> </p><p><span m='278080'>You</span>
  <span m='278460'>can</span> <span m='278841'>see</span> <span m='279222'>why</span>
  <span m='279603'>we</span> <span m='279984'>call</span> <span m='280365'>this</span>
  <span m='280746'>processing</span> <span m='281127'>"assembling</span> <span m='281508'>an</span>
  <span m='281889'>instruction".</span> </p><p><span m='282270'>The</span> <span m='282594'>binary</span>
  <span m='282918'>representation</span> <span m='283242'>of</span> <span m='283567'>an</span>
  <span m='283891'>instruction</span> <span m='284215'>is</span> <span m='284540'>assembled</span>
  <span m='284864'>from</span> <span m='285188'>the</span> <span m='285512'>binary</span>
  <span m='285837'>values</span> <span m='286161'>for</span> <span m='286485'>each</span>
  <span m='286810'>of</span> <span m='287412'>the</span> <span m='288015'>instruction</span>
  <span m='288617'>fields.</span> </p><p><span m='289220'>It's</span> <span m='289577'>not</span>
  <span m='289935'>a</span> <span m='290292'>complicated</span> <span m='290650'>process,</span>
  <span m='291007'>but</span> <span m='291365'>it</span> <span m='291722'>requires</span>
  <span m='292080'>a</span> <span m='292437'>lot</span> <span m='292795'>of</span>
  <span m='293152'>shifting</span> <span m='293510'>and</span> <span m='293867'>masking,</span>
  <span m='294225'>tasks</span> <span m='294582'>that</span> <span m='294940'>we're</span>
  <span m='295368'>happy</span> <span m='295796'>to</span> <span m='296225'>let</span>
  <span m='296653'>a</span> <span m='297082'>computer</span> <span m='297510'>handle.</span>
  </p><p><span m='297939'>Here's</span> <span m='298376'>the</span> <span m='298814'>entire</span>
  <span m='299252'>sequence</span> <span m='299690'>of</span> <span m='300128'>macro</span>
  <span m='300566'>expansions</span> <span m='301004'>that</span> <span m='301441'>assemble</span>
  <span m='301879'>this</span> <span m='302317'>ADDC</span> <span m='302755'>instruction</span>
  <span m='303193'>into</span> <span m='303631'>an</span> <span m='304069'>appropriate</span>
  <span m='304696'>32-bit</span> <span m='305323'>binary</span> <span m='305950'>value</span>
  <span m='306578'>in</span> <span m='307205'>main</span> <span m='307832'>memory.</span>
  </p><p><span m='308460'>You</span> <span m='308745'>can</span> <span m='309030'>see</span>
  <span m='309315'>that</span> <span m='309601'>the</span> <span m='309886'>knowledge</span>
  <span m='310171'>of</span> <span m='310457'>Beta</span> <span m='310742'>instruction</span>
  <span m='311027'>formats</span> <span m='311312'>and</span> <span m='311598'>opcode</span>
  <span m='311883'>values</span> <span m='312168'>is</span> <span m='312454'>built</span>
  <span m='312739'>into</span> <span m='313024'>the</span> <span m='313310'>bodies</span>
  <span m='313784'>of</span> <span m='314258'>the</span> <span m='314732'>macro</span>
  <span m='315206'>definitions.</span> </p><p><span m='315680'>The</span> <span m='316194'>UASM</span>
  <span m='316708'>processing</span> <span m='317222'>is</span> <span m='317737'>actually</span>
  <span m='318251'>quite</span> <span m='318765'>general.</span> </p><p><span m='319280'>With</span>
  <span m='319590'>a</span> <span m='319900'>different</span> <span m='320210'>set</span>
  <span m='320520'>of</span> <span m='320830'>macro</span> <span m='321140'>definitions</span>
  <span m='321450'>it</span> <span m='321760'>could</span> <span m='322070'>process</span>
  <span m='322380'>assembly</span> <span m='322690'>language</span> <span m='323000'>programs</span>
  <span m='323310'>for</span> <span m='324252'>almost</span> <span m='325195'>any</span>
  <span m='326137'>ISA!</span> </p><p><span m='327080'>All</span> <span m='327447'>the</span>
  <span m='327814'>macro</span> <span m='328182'>definitions</span> <span m='328549'>for</span>
  <span m='328916'>the</span> <span m='329284'>Beta</span> <span m='329651'>ISA</span>
  <span m='330018'>are</span> <span m='330386'>provided</span> <span m='330753'>in</span>
  <span m='331120'>the</span> <span m='331488'>beta.uasm</span> <span m='331855'>file,</span>
  <span m='332222'>which</span> <span m='332590'>is</span> <span m='333062'>included</span>
  <span m='333535'>in</span> <span m='334008'>each</span> <span m='334481'>of</span>
  <span m='334954'>the</span> <span m='335427'>assembly</span> <span m='335900'>language</span>
  <span m='336373'>lab</span> <span m='336846'>assignments.</span> </p><p><span m='337319'>Note</span>
  <span m='337686'>that</span> <span m='338054'>we</span> <span m='338422'>include</span>
  <span m='338789'>some</span> <span m='339157'>convenience</span> <span m='339525'>macros</span>
  <span m='339892'>to</span> <span m='340260'>define</span> <span m='340628'>shorthand</span>
  <span m='340995'>representations</span> <span m='341363'>that</span> <span m='341731'>provide</span>
  <span m='342099'>common</span> <span m='342637'>default</span> <span m='343176'>values</span>
  <span m='343714'>for</span> <span m='344253'>certain</span> <span m='344791'>operands.</span>
  </p><p><span m='345330'>For</span> <span m='345691'>example,</span> <span m='346052'>except</span>
  <span m='346413'>for</span> <span m='346775'>procedure</span> <span m='347136'>calls,</span>
  <span m='347497'>we</span> <span m='347858'>don't</span> <span m='348220'>care</span>
  <span m='348581'>about</span> <span m='348942'>the</span> <span m='349303'>PC+4</span>
  <span m='349665'>value</span> <span m='350026'>saved</span> <span m='350387'>in</span>
  <span m='350748'>the</span> <span m='351110'>destination</span> <span m='351646'>register</span>
  <span m='352183'>by</span> <span m='352720'>branch</span> <span m='353257'>instructions,</span>
  <span m='353794'>so</span> <span m='354331'>almost</span> <span m='354868'>always</span>
  <span m='355405'>would</span> <span m='355942'>specify</span> <span m='356479'>R31</span>
  <span m='357016'>as</span> <span m='357553'>the</span> <span m='358090'>Rc</span>
  <span m='358719'>register,</span> <span m='359349'>effectively</span> <span m='359979'>discarding</span>
  <span m='360609'>the</span> <span m='361239'>PC+4</span> <span m='361869'>value</span>
  <span m='362499'>saved</span> <span m='363129'>by</span> <span m='363759'>branches.</span>
  </p><p><span m='364389'>So</span> <span m='364803'>we</span> <span m='365218'>define</span>
  <span m='365633'>two-argument</span> <span m='366047'>branch</span> <span m='366462'>macros</span>
  <span m='366877'>that</span> <span m='367291'>automatically</span> <span m='367706'>provide</span>
  <span m='368121'>R31</span> <span m='368535'>as</span> <span m='368950'>the</span>
  <span m='369365'>destination</span> <span m='369780'>register.</span> </p><p><span
  m='370780'>Saves</span> <span m='371157'>some</span> <span m='371534'>typing,</span>
  <span m='371911'>and,</span> <span m='372288'>more</span> <span m='372665'>importantly,</span>
  <span m='373042'>it</span> <span m='373420'>makes</span> <span m='373797'>it</span>
  <span m='374174'>easier</span> <span m='374551'>to</span> <span m='374928'>understand</span>
  <span m='375305'>the</span> <span m='375682'>assembly</span> <span m='376060'>language</span>
  <span m='377254'>program.</span> </p><p><span m='378449'>Here</span> <span m='378795'>are</span>
  <span m='379142'>a</span> <span m='379488'>whole</span> <span m='379835'>set</span>
  <span m='380181'>of</span> <span m='380528'>convenience</span> <span m='380874'>macros</span>
  <span m='381221'>intended</span> <span m='381567'>to</span> <span m='381914'>make</span>
  <span m='382260'>programs</span> <span m='382607'>more</span> <span m='382953'>readable.</span>
  </p><p><span m='383300'>For</span> <span m='383660'>example,</span> <span m='384020'>unconditional</span>
  <span m='384380'>branches</span> <span m='384740'>can</span> <span m='385100'>be</span>
  <span m='385460'>written</span> <span m='385820'>using</span> <span m='386180'>the</span>
  <span m='386540'>BR()</span> <span m='386900'>macro</span> <span m='387260'>rather</span>
  <span m='387620'>than</span> <span m='387980'>the</span> <span m='388340'>more</span>
  <span m='389709'>cumbersome</span> <span m='391079'>BEQ(R31,...).</span> </p><p><span
  m='392449'>And</span> <span m='392769'>it's</span> <span m='393089'>more</span>
  <span m='393409'>readable</span> <span m='393729'>to</span> <span m='394049'>use</span>
  <span m='394369'>branch-false</span> <span m='394689'>(BF)</span> <span m='395009'>and</span>
  <span m='395329'>branch-true</span> <span m='395649'>(BT)</span> <span m='395969'>macros</span>
  <span m='396289'>when</span> <span m='396609'>testing</span> <span m='396930'>the</span>
  <span m='397461'>results</span> <span m='397993'>of</span> <span m='398525'>a</span>
  <span m='399056'>compare</span> <span m='399588'>instruction.</span> </p><p><span
  m='400120'>And</span> <span m='400415'>note</span> <span m='400711'>the</span> <span
  m='401007'>PUSH</span> <span m='401303'>and</span> <span m='401598'>POP</span> <span
  m='401894'>macros</span> <span m='402190'>at</span> <span m='402486'>the</span>
  <span m='402781'>bottom</span> <span m='403077'>of</span> <span m='403373'>page.</span>
  </p><p><span m='403669'>These</span> <span m='404048'>expand</span> <span m='404427'>into</span>
  <span m='404806'>multi-instruction</span> <span m='405186'>sequences,</span> <span
  m='405565'>in</span> <span m='405944'>this</span> <span m='406324'>case</span> <span
  m='406703'>to</span> <span m='407082'>add</span> <span m='407461'>and</span> <span
  m='407841'>remove</span> <span m='408220'>values</span> <span m='408599'>from</span>
  <span m='408979'>a</span> <span m='409483'>stack</span> <span m='409987'>data</span>
  <span m='410491'>structure</span> <span m='410995'>pointed</span> <span m='411499'>to</span>
  <span m='412003'>by</span> <span m='412507'>the</span> <span m='413011'>SP</span>
  <span m='413515'>register.</span> </p><p><span m='414020'>We</span> <span m='414344'>call</span>
  <span m='414668'>these</span> <span m='414992'>macros</span> <span m='415317'>"pseudo</span>
  <span m='415641'>instructions"</span> <span m='415965'>since</span> <span m='416290'>they</span>
  <span m='416614'>let</span> <span m='416938'>us</span> <span m='417262'>provide</span>
  <span m='417587'>the</span> <span m='417911'>programmer</span> <span m='418235'>with</span>
  <span m='418560'>what</span> <span m='418950'>appears</span> <span m='419341'>a</span>
  <span m='419732'>larger</span> <span m='420123'>instruction</span> <span m='420513'>set,</span>
  <span m='420904'>although</span> <span m='421295'>underneath</span> <span m='421686'>the</span>
  <span m='422076'>covers</span> <span m='422467'>we've</span> <span m='422858'>just</span>
  <span m='423249'>using</span> <span m='423792'>the</span> <span m='424335'>same</span>
  <span m='424878'>small</span> <span m='425421'>instruction</span> <span m='425964'>repertoire</span>
  <span m='426507'>developed</span> <span m='427050'>in</span> <span m='427593'>Lecture</span>
  <span m='428136'>9.</span> </p><p><span m='428680'>In</span> <span m='429057'>this</span>
  <span m='429434'>example</span> <span m='429811'>we've</span> <span m='430188'>rewritten</span>
  <span m='430565'>the</span> <span m='430942'>original</span> <span m='431320'>code</span>
  <span m='431697'>we</span> <span m='432074'>had</span> <span m='432451'>for</span>
  <span m='432828'>the</span> <span m='433205'>factorial</span> <span m='433582'>computation</span>
  <span m='433960'>using</span> <span m='434626'>pseudo</span> <span m='435293'>instructions.</span>
  </p><p><span m='435960'>For</span> <span m='436392'>example,</span> <span m='436824'>CMOVE</span>
  <span m='437256'>is</span> <span m='437688'>a</span> <span m='438120'>pseudo</span>
  <span m='438552'>instruction</span> <span m='438984'>for</span> <span m='439416'>moving</span>
  <span m='439848'>small</span> <span m='440280'>constants</span> <span m='440712'>into</span>
  <span m='441144'>a</span> <span m='441576'>register.</span> </p><p><span m='442009'>It's</span>
  <span m='442347'>easier</span> <span m='442685'>for</span> <span m='443023'>us</span>
  <span m='443361'>to</span> <span m='443699'>read</span> <span m='444037'>and</span>
  <span m='444375'>understand</span> <span m='444713'>the</span> <span m='445051'>intent</span>
  <span m='445389'>of</span> <span m='445727'>a</span> <span m='446065'>"constant</span>
  <span m='446403'>move"</span> <span m='446741'>operation</span> <span m='447080'>than</span>
  <span m='447514'>an</span> <span m='447949'>"add</span> <span m='448383'>a</span>
  <span m='448818'>value</span> <span m='449253'>to</span> <span m='449687'>0"</span>
  <span m='450122'>operation</span> <span m='450556'>provided</span> <span m='450991'>by</span>
  <span m='451426'>the</span> <span m='451860'>ADDC</span> <span m='452295'>expansion</span>
  <span m='452729'>of</span> <span m='453164'>CMOVE.</span> </p><p><span m='453599'>Anything</span>
  <span m='453877'>we</span> <span m='454156'>can</span> <span m='454435'>do</span>
  <span m='454714'>to</span> <span m='454993'>remove</span> <span m='455271'>the</span>
  <span m='455550'>cognitive</span> <span m='455829'>clutter</span> <span m='456108'>will</span>
  <span m='456387'>be</span> <span m='456665'>very</span> <span m='456944'>beneficial</span>
  <span m='457223'>in</span> <span m='457502'>the</span> <span m='457781'>long</span>
  <span m='458060'>run.</span> </p>
type: course
uid: 2edba4bf9e58c9ba0c870a7934b68dcd

---
None