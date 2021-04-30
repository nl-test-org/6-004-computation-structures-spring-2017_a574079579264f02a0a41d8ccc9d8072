---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: dLeI7A7VezQ
  parent_uid: 9eb850a92f36fcb8755db8bfd040099f
  title: Video-YouTube-Stream
  type: Video
  uid: 544366bf3521a46d503db8cf535d4267
- id: 3Play-3Play YouTube id-Stream
  media_location: dLeI7A7VezQ
  parent_uid: 9eb850a92f36fcb8755db8bfd040099f
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 4bd08b886921f080e045c796b7122588
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/dLeI7A7VezQ/default.jpg
  parent_uid: 9eb850a92f36fcb8755db8bfd040099f
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 44f4404ab9ccd70d655771274b078067
- id: dLeI7A7VezQ.srt
  parent_uid: 9eb850a92f36fcb8755db8bfd040099f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v5/weak-priorities-5-10-/dLeI7A7VezQ.srt
  title: 3play caption file
  type: null
  uid: ccf76b3b8507be82fb79d3ed6018b96f
- id: dLeI7A7VezQ.pdf
  parent_uid: 9eb850a92f36fcb8755db8bfd040099f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v5/weak-priorities-5-10-/dLeI7A7VezQ.pdf
  title: 3play pdf file
  type: null
  uid: 9698e12eee1889bbfa15ed95b6ea903f
- id: Caption-3Play YouTube id-SRT
  parent_uid: 9eb850a92f36fcb8755db8bfd040099f
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 03835449bb3dd4f1aaa28e8c0dcd1e15
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 9eb850a92f36fcb8755db8bfd040099f
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 0e10fa64e8ec86e72d20a00da12beb5c
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_18-02-05_300k.mp4
  parent_uid: 9eb850a92f36fcb8755db8bfd040099f
  title: Video-Internet Archive-MP4
  type: Video
  uid: 93efd4a53516970b8777bdb6145e89c5
inline_embed_id: 30728814weakpriorities51097444557
layout: video
order_index: null
parent_uid: 96e9fddf483a9da267e99faf20fea3c7
related_resources_text: ''
short_url: weak-priorities-5-10-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v5/weak-priorities-5-10-
template_type: Embed
title: Weak Priorities (5:10)
transcript: <p><span m='410'>Suppose</span> <span m='742'>we</span> <span m='1074'>have</span>
  <span m='1406'>a</span> <span m='1738'>real-time</span> <span m='2071'>system</span>
  <span m='2403'>supporting</span> <span m='2735'>three</span> <span m='3067'>devices:</span>
  <span m='3400'>a</span> <span m='3775'>keyboard</span> <span m='4151'>whose</span>
  <span m='4527'>interrupt</span> <span m='4903'>handler</span> <span m='5279'>has</span>
  <span m='5655'>a</span> <span m='6030'>service</span> <span m='6406'>time</span>
  <span m='6782'>of</span> <span m='7158'>800</span> <span m='7534'>us,</span> <span
  m='7910'>a</span> <span m='8303'>disk</span> <span m='8697'>with</span> <span m='9090'>a</span>
  <span m='9484'>service</span> <span m='9878'>time</span> <span m='10271'>of</span>
  <span m='10665'>500</span> <span m='11059'>us,</span> <span m='11452'>and</span>
  <span m='11846'>a</span> <span m='12239'>printer</span> <span m='12633'>with</span>
  <span m='13027'>a</span> <span m='13420'>service</span> <span m='13814'>time</span>
  <span m='14208'>of</span> <span m='14601'>400</span> <span m='14995'>us.</span>
  </p><p><span m='15389'>What</span> <span m='15784'>is</span> <span m='16180'>the</span>
  <span m='16575'>worst-case</span> <span m='16971'>latency</span> <span m='17366'>seen</span>
  <span m='17762'>by</span> <span m='18157'>each</span> <span m='18553'>device?</span>
  </p><p><span m='18949'>For</span> <span m='19295'>now</span> <span m='19641'>we'll</span>
  <span m='19987'>assume</span> <span m='20333'>that</span> <span m='20679'>requests</span>
  <span m='21025'>are</span> <span m='21371'>infrequent,</span> <span m='21717'>i.e.,</span>
  <span m='22063'>that</span> <span m='22409'>each</span> <span m='22755'>request</span>
  <span m='23101'>only</span> <span m='23447'>happens</span> <span m='23793'>once</span>
  <span m='24140'>in</span> <span m='24843'>each</span> <span m='25546'>scenario.</span>
  </p><p><span m='26250'>Requests</span> <span m='26581'>can</span> <span m='26912'>arrive</span>
  <span m='27243'>at</span> <span m='27574'>any</span> <span m='27905'>time</span>
  <span m='28236'>and</span> <span m='28567'>in</span> <span m='28898'>any</span>
  <span m='29229'>order.</span> </p><p><span m='29560'>If</span> <span m='29904'>we</span>
  <span m='30249'>serve</span> <span m='30594'>the</span> <span m='30938'>requests</span>
  <span m='31283'>in</span> <span m='31628'>first-come-first-served</span> <span m='31972'>order,</span>
  <span m='32317'>each</span> <span m='32662'>device</span> <span m='33006'>might</span>
  <span m='33351'>be</span> <span m='33696'>delayed</span> <span m='34040'>by</span>
  <span m='34385'>the</span> <span m='34730'>service</span> <span m='35218'>of</span>
  <span m='35706'>all</span> <span m='36194'>other</span> <span m='36682'>devices.</span>
  </p><p><span m='37170'>So</span> <span m='37411'>the</span> <span m='37653'>start</span>
  <span m='37895'>of</span> <span m='38137'>the</span> <span m='38378'>keyboard</span>
  <span m='38620'>handler</span> <span m='38862'>might</span> <span m='39104'>be</span>
  <span m='39345'>delayed</span> <span m='39587'>by</span> <span m='39829'>the</span>
  <span m='40071'>execution</span> <span m='40312'>of</span> <span m='40554'>the</span>
  <span m='40796'>disk</span> <span m='41038'>and</span> <span m='41280'>printer</span>
  <span m='41958'>handlers,</span> <span m='42637'>a</span> <span m='43316'>worst-case</span>
  <span m='43995'>latency</span> <span m='44673'>of</span> <span m='45352'>900</span>
  <span m='46031'>us.</span> </p><p><span m='46710'>The</span> <span m='46996'>start</span>
  <span m='47282'>of</span> <span m='47569'>the</span> <span m='47855'>disk</span>
  <span m='48142'>handler</span> <span m='48428'>might</span> <span m='48714'>be</span>
  <span m='49001'>delayed</span> <span m='49287'>by</span> <span m='49574'>the</span>
  <span m='49860'>keyboard</span> <span m='50146'>and</span> <span m='50433'>printer</span>
  <span m='50719'>handlers,</span> <span m='51006'>a</span> <span m='51292'>worst-case</span>
  <span m='51579'>latency</span> <span m='52296'>of</span> <span m='53014'>1200</span>
  <span m='53731'>us.</span> </p><p><span m='54449'>And</span> <span m='54731'>the</span>
  <span m='55013'>printer</span> <span m='55295'>handler</span> <span m='55577'>might</span>
  <span m='55859'>be</span> <span m='56141'>delayed</span> <span m='56423'>by</span>
  <span m='56705'>the</span> <span m='56987'>keyboard</span> <span m='57269'>and</span>
  <span m='57551'>disk</span> <span m='57833'>handlers,</span> <span m='58115'>a</span>
  <span m='58397'>worst-case</span> <span m='58680'>latency</span> <span m='59532'>of</span>
  <span m='60385'>1300</span> <span m='61237'>us.</span> </p><p><span m='62090'>In</span>
  <span m='62380'>this</span> <span m='62671'>scenario</span> <span m='62962'>we</span>
  <span m='63252'>see</span> <span m='63543'>that</span> <span m='63834'>long-running</span>
  <span m='64124'>handlers</span> <span m='64415'>have</span> <span m='64706'>a</span>
  <span m='64996'>huge</span> <span m='65287'>impact</span> <span m='65578'>on</span>
  <span m='65868'>the</span> <span m='66159'>worst-case</span> <span m='66450'>latency</span>
  <span m='67006'>seen</span> <span m='67563'>by</span> <span m='68119'>the</span>
  <span m='68676'>other</span> <span m='69232'>devices.</span> </p><p><span m='69789'>What</span>
  <span m='70201'>are</span> <span m='70613'>the</span> <span m='71026'>possibilities</span>
  <span m='71438'>for</span> <span m='71850'>reducing</span> <span m='72263'>the</span>
  <span m='72675'>worst-case</span> <span m='73087'>latencies?</span> </p><p><span
  m='73500'>Is</span> <span m='74236'>there</span> <span m='74972'>a</span> <span
  m='75708'>better</span> <span m='76445'>scheduling</span> <span m='77181'>algorithm</span>
  <span m='77917'>than</span> <span m='78653'>first-come-first-served?</span> </p><p><span
  m='79390'>One</span> <span m='79699'>strategy</span> <span m='80008'>is</span> <span
  m='80318'>to</span> <span m='80627'>assign</span> <span m='80936'>priorities</span>
  <span m='81246'>to</span> <span m='81555'>the</span> <span m='81864'>pending</span>
  <span m='82174'>requests</span> <span m='82483'>and</span> <span m='82792'>to</span>
  <span m='83102'>serve</span> <span m='83411'>the</span> <span m='83720'>requests</span>
  <span m='84030'>in</span> <span m='84636'>priority</span> <span m='85243'>order.</span>
  </p><p><span m='85850'>If</span> <span m='86118'>the</span> <span m='86386'>handlers</span>
  <span m='86654'>are</span> <span m='86922'>uninterruptible,</span> <span m='87190'>the</span>
  <span m='87458'>priorities</span> <span m='87726'>will</span> <span m='87995'>be</span>
  <span m='88263'>used</span> <span m='88531'>to</span> <span m='88799'>select</span>
  <span m='89067'>the</span> <span m='89335'>*next*</span> <span m='89603'>task</span>
  <span m='89871'>to</span> <span m='90140'>be</span> <span m='90510'>run</span> <span
  m='90880'>at</span> <span m='91250'>the</span> <span m='91620'>completion</span>
  <span m='91990'>of</span> <span m='92360'>the</span> <span m='92730'>current</span>
  <span m='93100'>task.</span> </p><p><span m='93470'>Note</span> <span m='93801'>that</span>
  <span m='94133'>under</span> <span m='94465'>this</span> <span m='94797'>strategy,</span>
  <span m='95129'>the</span> <span m='95461'>current</span> <span m='95793'>task</span>
  <span m='96125'>always</span> <span m='96456'>runs</span> <span m='96788'>to</span>
  <span m='97120'>completion</span> <span m='97452'>even</span> <span m='97784'>if</span>
  <span m='98116'>a</span> <span m='98448'>higher-priority</span> <span m='98780'>request</span>
  <span m='99278'>arrives</span> <span m='99776'>while</span> <span m='100274'>it's</span>
  <span m='100772'>executing.</span> </p><p><span m='101270'>This</span> <span m='101775'>is</span>
  <span m='102281'>called</span> <span m='102786'>a</span> <span m='103292'>"nonpreemptive"</span>
  <span m='103797'>or</span> <span m='104303'>"weak"</span> <span m='104808'>priority</span>
  <span m='105314'>system.</span> </p><p><span m='105820'>Using</span> <span m='106160'>a</span>
  <span m='106500'>weak</span> <span m='106840'>priority</span> <span m='107180'>system,</span>
  <span m='107520'>the</span> <span m='107860'>worst-case</span> <span m='108200'>latency</span>
  <span m='108540'>seen</span> <span m='108880'>by</span> <span m='109220'>each</span>
  <span m='109560'>device</span> <span m='109900'>is</span> <span m='110240'>the</span>
  <span m='110580'>worst-case</span> <span m='110920'>service</span> <span m='111235'>time</span>
  <span m='111551'>of</span> <span m='111867'>all</span> <span m='112182'>the</span>
  <span m='112498'>other</span> <span m='112814'>devices</span> <span m='113130'>(since</span>
  <span m='113445'>that</span> <span m='113761'>handler</span> <span m='114077'>may</span>
  <span m='114392'>have</span> <span m='114708'>just</span> <span m='115024'>started</span>
  <span m='115340'>running</span> <span m='115736'>when</span> <span m='116133'>the</span>
  <span m='116530'>new</span> <span m='116927'>request</span> <span m='117324'>arrives),</span>
  <span m='117721'>plus</span> <span m='118118'>the</span> <span m='118515'>service</span>
  <span m='118912'>time</span> <span m='119309'>of</span> <span m='119706'>all</span>
  <span m='120103'>higher-priority</span> <span m='120500'>devices</span> <span m='120883'>(since</span>
  <span m='121266'>they'll</span> <span m='121650'>be</span> <span m='122033'>run</span>
  <span m='122416'>first).</span> </p><p><span m='122800'>In</span> <span m='123115'>our</span>
  <span m='123430'>example,</span> <span m='123745'>suppose</span> <span m='124060'>we</span>
  <span m='124375'>assigned</span> <span m='124690'>the</span> <span m='125005'>highest</span>
  <span m='125320'>priority</span> <span m='125635'>to</span> <span m='125950'>the</span>
  <span m='126265'>disk,</span> <span m='126580'>the</span> <span m='126895'>next</span>
  <span m='127210'>priority</span> <span m='127525'>to</span> <span m='127840'>the</span>
  <span m='128265'>printer,</span> <span m='128691'>and</span> <span m='129116'>the</span>
  <span m='129542'>lowest</span> <span m='129967'>priority</span> <span m='130393'>to</span>
  <span m='130818'>the</span> <span m='131244'>keyboard.</span> </p><p><span m='131670'>The</span>
  <span m='131951'>worst-case</span> <span m='132232'>latency</span> <span m='132514'>of</span>
  <span m='132795'>the</span> <span m='133077'>keyboard</span> <span m='133358'>is</span>
  <span m='133640'>unchanged</span> <span m='133921'>since</span> <span m='134202'>it</span>
  <span m='134484'>has</span> <span m='134765'>the</span> <span m='135047'>lowest</span>
  <span m='135328'>priority</span> <span m='135610'>and</span> <span m='136025'>hence</span>
  <span m='136440'>can</span> <span m='136855'>be</span> <span m='137270'>delayed</span>
  <span m='137685'>by</span> <span m='138100'>the</span> <span m='138515'>higher-priority</span>
  <span m='138930'>disk</span> <span m='139345'>and</span> <span m='139760'>printer</span>
  <span m='140175'>handlers.</span> </p><p><span m='140590'>The</span> <span m='140874'>disk</span>
  <span m='141158'>handler</span> <span m='141442'>has</span> <span m='141726'>the</span>
  <span m='142010'>highest</span> <span m='142294'>priority</span> <span m='142578'>and</span>
  <span m='142862'>so</span> <span m='143146'>will</span> <span m='143430'>always</span>
  <span m='143714'>be</span> <span m='143998'>selected</span> <span m='144282'>for</span>
  <span m='144566'>execution</span> <span m='144850'>after</span> <span m='145456'>the</span>
  <span m='146062'>current</span> <span m='146668'>handler</span> <span m='147274'>completes.</span>
  </p><p><span m='147880'>So</span> <span m='148266'>its</span> <span m='148653'>worst-case</span>
  <span m='149040'>latency</span> <span m='149427'>is</span> <span m='149814'>the</span>
  <span m='150201'>worst-case</span> <span m='150588'>service</span> <span m='150975'>time</span>
  <span m='151362'>for</span> <span m='151749'>the</span> <span m='152136'>currently-running</span>
  <span m='152523'>handler,</span> <span m='152910'>which</span> <span m='153185'>in</span>
  <span m='153461'>this</span> <span m='153737'>case</span> <span m='154012'>is</span>
  <span m='154288'>the</span> <span m='154564'>keyboard.</span> </p><p><span m='154840'>So</span>
  <span m='155270'>the</span> <span m='155700'>worst-case</span> <span m='156130'>latency</span>
  <span m='156560'>for</span> <span m='156990'>the</span> <span m='157420'>disk</span>
  <span m='157850'>is</span> <span m='158280'>800</span> <span m='158710'>us.</span>
  </p><p><span m='159140'>This</span> <span m='159720'>is</span> <span m='160300'>a</span>
  <span m='160880'>considerable</span> <span m='161460'>improvement</span> <span m='162040'>over</span>
  <span m='162620'>the</span> <span m='163200'>first-come-first-served</span> <span
  m='163780'>scenario.</span> </p><p><span m='164360'>Finally</span> <span m='164664'>the</span>
  <span m='164968'>worst-case</span> <span m='165273'>scenario</span> <span m='165577'>for</span>
  <span m='165882'>the</span> <span m='166186'>printer</span> <span m='166491'>is</span>
  <span m='166795'>1300</span> <span m='167100'>us</span> <span m='167404'>since</span>
  <span m='167708'>it</span> <span m='168013'>may</span> <span m='168317'>have</span>
  <span m='168622'>to</span> <span m='168926'>wait</span> <span m='169231'>for</span>
  <span m='169535'>the</span> <span m='169840'>keyboard</span> <span m='170211'>handler</span>
  <span m='170583'>to</span> <span m='170955'>finish</span> <span m='171327'>(which</span>
  <span m='171699'>can</span> <span m='172070'>take</span> <span m='172442'>up</span>
  <span m='172814'>to</span> <span m='173186'>800</span> <span m='173558'>us)</span>
  <span m='173930'>and</span> <span m='174422'>then</span> <span m='174915'>for</span>
  <span m='175408'>a</span> <span m='175901'>higher-priority</span> <span m='176394'>disk</span>
  <span m='176887'>request</span> <span m='177380'>to</span> <span m='177872'>be</span>
  <span m='178365'>serviced</span> <span m='178858'>(which</span> <span m='179351'>takes</span>
  <span m='179844'>500</span> <span m='180337'>us).</span> </p><p><span m='180830'>How</span>
  <span m='181350'>should</span> <span m='181870'>priorities</span> <span m='182390'>be</span>
  <span m='182910'>assigned</span> <span m='183430'>given</span> <span m='183950'>hard</span>
  <span m='184470'>real-time</span> <span m='184990'>constraints?</span> </p><p><span
  m='185510'>We'll</span> <span m='185930'>assume</span> <span m='186351'>each</span>
  <span m='186771'>device</span> <span m='187192'>has</span> <span m='187613'>a</span>
  <span m='188033'>service</span> <span m='188454'>deadline</span> <span m='188875'>D</span>
  <span m='189295'>after</span> <span m='189716'>the</span> <span m='190136'>arrival</span>
  <span m='190557'>of</span> <span m='190978'>its</span> <span m='191398'>service</span>
  <span m='191819'>request.</span> </p><p><span m='192240'>If</span> <span m='192577'>not</span>
  <span m='192915'>otherwise</span> <span m='193252'>specified,</span> <span m='193590'>assume</span>
  <span m='193927'>D</span> <span m='194265'>is</span> <span m='194602'>the</span>
  <span m='194940'>time</span> <span m='195277'>until</span> <span m='195615'>the</span>
  <span m='195952'>*next*</span> <span m='196290'>request</span> <span m='196627'>for</span>
  <span m='196965'>the</span> <span m='197302'>same</span> <span m='197640'>device.</span>
  </p><p><span m='198640'>This</span> <span m='198933'>is</span> <span m='199227'>a</span>
  <span m='199521'>reasonably</span> <span m='199815'>conservative</span> <span m='200109'>assumption</span>
  <span m='200403'>that</span> <span m='200696'>prevents</span> <span m='200990'>the</span>
  <span m='201284'>system</span> <span m='201578'>from</span> <span m='201872'>falling</span>
  <span m='202166'>further</span> <span m='202460'>and</span> <span m='203176'>further</span>
  <span m='203893'>behind.</span> </p><p><span m='204610'>For</span> <span m='204980'>example,</span>
  <span m='205350'>it</span> <span m='205720'>makes</span> <span m='206090'>sense</span>
  <span m='206460'>that</span> <span m='206830'>the</span> <span m='207200'>keyboard</span>
  <span m='207570'>handler</span> <span m='207940'>should</span> <span m='208310'>finish</span>
  <span m='208680'>processing</span> <span m='209050'>one</span> <span m='209420'>character</span>
  <span m='209790'>before</span> <span m='210282'>the</span> <span m='210775'>next</span>
  <span m='211267'>arrives.</span> </p><p><span m='211760'>"Earliest</span> <span
  m='212113'>Deadline"</span> <span m='212467'>is</span> <span m='212820'>a</span>
  <span m='213174'>strategy</span> <span m='213527'>for</span> <span m='213881'>assigning</span>
  <span m='214234'>priorities</span> <span m='214588'>that</span> <span m='214941'>is</span>
  <span m='215295'>guaranteed</span> <span m='215648'>to</span> <span m='216002'>meet</span>
  <span m='216355'>the</span> <span m='216709'>deadlines</span> <span m='217209'>if</span>
  <span m='217709'>any</span> <span m='218209'>priority</span> <span m='218709'>assignment</span>
  <span m='219209'>can</span> <span m='219709'>meet</span> <span m='220209'>the</span>
  <span m='220709'>deadlines.</span> </p><p><span m='221209'>It's</span> <span m='221590'>very</span>
  <span m='221971'>simple:</span> <span m='222352'>Sort</span> <span m='222733'>the</span>
  <span m='223115'>requests</span> <span m='223496'>by</span> <span m='223877'>their</span>
  <span m='224258'>deadlines.</span> </p><p><span m='224640'>Assign</span> <span m='224984'>the</span>
  <span m='225328'>highest</span> <span m='225672'>priority</span> <span m='226016'>to</span>
  <span m='226361'>the</span> <span m='226705'>earliest</span> <span m='227049'>deadline,</span>
  <span m='227393'>second</span> <span m='227737'>priority</span> <span m='228082'>to</span>
  <span m='228426'>the</span> <span m='228770'>next</span> <span m='229114'>deadline,</span>
  <span m='229459'>and</span> <span m='230069'>so</span> <span m='230679'>on.</span>
  </p><p><span m='231290'>A</span> <span m='231647'>weak</span> <span m='232004'>priority</span>
  <span m='232362'>system</span> <span m='232719'>will</span> <span m='233076'>choose</span>
  <span m='233434'>the</span> <span m='233791'>pending</span> <span m='234148'>request</span>
  <span m='234506'>with</span> <span m='234863'>the</span> <span m='235220'>highest</span>
  <span m='235578'>priority,</span> <span m='235935'>i.e.,</span> <span m='236292'>the</span>
  <span m='236650'>request</span> <span m='237253'>that</span> <span m='237856'>has</span>
  <span m='238460'>the</span> <span m='239063'>earliest</span> <span m='239666'>deadline.</span>
  </p><p><span m='240270'>Earliest</span> <span m='240621'>Deadline</span> <span m='240973'>has</span>
  <span m='241325'>an</span> <span m='241676'>intuitive</span> <span m='242028'>appeal.</span>
  </p><p><span m='242380'>Imagine</span> <span m='242693'>standing</span> <span m='243006'>in</span>
  <span m='243319'>a</span> <span m='243632'>long</span> <span m='243945'>security</span>
  <span m='244258'>line</span> <span m='244571'>at</span> <span m='244884'>the</span>
  <span m='245197'>airport.</span> </p><p><span m='245510'>It</span> <span m='245857'>would</span>
  <span m='246204'>make</span> <span m='246552'>sense</span> <span m='246899'>to</span>
  <span m='247246'>prioritize</span> <span m='247594'>the</span> <span m='247941'>processing</span>
  <span m='248288'>of</span> <span m='248636'>passengers</span> <span m='248983'>who</span>
  <span m='249330'>have</span> <span m='249678'>the</span> <span m='250025'>earliest</span>
  <span m='250372'>flights</span> <span m='250720'>assuming</span> <span m='251221'>that</span>
  <span m='251723'>there's</span> <span m='252224'>enough</span> <span m='252726'>time</span>
  <span m='253227'>to</span> <span m='253729'>process</span> <span m='254230'>everyone</span>
  <span m='254732'>before</span> <span m='255233'>their</span> <span m='255735'>flight</span>
  <span m='256236'>leaves.</span> </p><p><span m='256738'>Processing</span> <span
  m='257006'>10</span> <span m='257275'>people</span> <span m='257544'>whose</span>
  <span m='257812'>flights</span> <span m='258081'>leave</span> <span m='258350'>in</span>
  <span m='258619'>30</span> <span m='258887'>minutes</span> <span m='259156'>before</span>
  <span m='259425'>someone</span> <span m='259693'>whose</span> <span m='259962'>flight</span>
  <span m='260231'>leaves</span> <span m='260500'>in</span> <span m='260891'>5</span>
  <span m='261283'>min</span> <span m='261675'>will</span> <span m='262066'>cause</span>
  <span m='262458'>that</span> <span m='262850'>last</span> <span m='263241'>person</span>
  <span m='263633'>to</span> <span m='264025'>miss</span> <span m='264416'>their</span>
  <span m='264808'>flight.</span> </p><p><span m='265200'>But</span> <span m='265524'>if</span>
  <span m='265848'>that</span> <span m='266172'>person</span> <span m='266496'>is</span>
  <span m='266820'>processed</span> <span m='267144'>first,</span> <span m='267468'>the</span>
  <span m='267792'>other</span> <span m='268116'>passengers</span> <span m='268440'>may</span>
  <span m='268764'>be</span> <span m='269088'>slightly</span> <span m='269412'>delayed</span>
  <span m='269736'>but</span> <span m='270060'>everyone</span> <span m='270550'>will</span>
  <span m='271040'>make</span> <span m='271530'>their</span> <span m='272020'>flight.</span>
  </p><p><span m='272510'>This</span> <span m='272814'>is</span> <span m='273118'>the</span>
  <span m='273422'>sort</span> <span m='273726'>of</span> <span m='274030'>scheduling</span>
  <span m='274334'>problem</span> <span m='274638'>that</span> <span m='274942'>Earliest</span>
  <span m='275246'>Deadline</span> <span m='275550'>and</span> <span m='275854'>a</span>
  <span m='276158'>weak</span> <span m='276462'>priority</span> <span m='276766'>system</span>
  <span m='277070'>can</span> <span m='278215'>solve.</span> </p><p><span m='279360'>It's</span>
  <span m='279611'>outside</span> <span m='279862'>the</span> <span m='280114'>scope</span>
  <span m='280365'>of</span> <span m='280616'>our</span> <span m='280868'>discussion,</span>
  <span m='281119'>but</span> <span m='281370'>it's</span> <span m='281622'>interesting</span>
  <span m='281873'>to</span> <span m='282124'>think</span> <span m='282376'>about</span>
  <span m='282627'>what</span> <span m='282878'>should</span> <span m='283130'>happen</span>
  <span m='283570'>if</span> <span m='284010'>some</span> <span m='284450'>flights</span>
  <span m='284890'>are</span> <span m='285330'>going</span> <span m='285770'>to</span>
  <span m='286210'>be</span> <span m='286650'>missed.</span> </p><p><span m='287090'>If</span>
  <span m='287452'>the</span> <span m='287814'>system</span> <span m='288176'>is</span>
  <span m='288539'>overloaded,</span> <span m='288901'>prioritizing</span> <span m='289263'>by</span>
  <span m='289626'>earliest</span> <span m='289988'>deadline</span> <span m='290350'>may</span>
  <span m='290713'>mean</span> <span m='291075'>that</span> <span m='291437'>everyone</span>
  <span m='291800'>will</span> <span m='292230'>miss</span> <span m='292660'>their</span>
  <span m='293090'>flights!</span> </p><p><span m='293520'>In</span> <span m='293798'>this</span>
  <span m='294076'>scenario</span> <span m='294354'>it</span> <span m='294632'>might</span>
  <span m='294910'>be</span> <span m='295188'>better</span> <span m='295466'>to</span>
  <span m='295745'>assign</span> <span m='296023'>priorities</span> <span m='296301'>to</span>
  <span m='296579'>the</span> <span m='296857'>minimize</span> <span m='297135'>the</span>
  <span m='297413'>total</span> <span m='297691'>number</span> <span m='297970'>of</span>
  <span m='298530'>missed</span> <span m='299090'>flights.</span> </p><p><span m='299650'>This</span>
  <span m='299956'>gets</span> <span m='300263'>complicated</span> <span m='300570'>in</span>
  <span m='300876'>a</span> <span m='301183'>hurry</span> <span m='301490'>since</span>
  <span m='301796'>the</span> <span m='302103'>assignment</span> <span m='302410'>of</span>
  <span m='302716'>priorities</span> <span m='303023'>now</span> <span m='303330'>depends</span>
  <span m='303636'>on</span> <span m='303943'>exactly</span> <span m='304250'>what</span>
  <span m='304528'>requests</span> <span m='304807'>are</span> <span m='305085'>pending</span>
  <span m='305364'>and</span> <span m='305642'>how</span> <span m='305921'>long</span>
  <span m='306200'>it</span> <span m='306478'>will</span> <span m='306757'>take</span>
  <span m='307035'>them</span> <span m='307314'>to</span> <span m='307592'>be</span>
  <span m='307871'>serviced.</span> </p><p><span m='308150'>An</span> <span m='308478'>intriguing</span>
  <span m='308806'>problem</span> <span m='309135'>to</span> <span m='309463'>think</span>
  <span m='309791'>about!</span> </p>
type: course
uid: 9eb850a92f36fcb8755db8bfd040099f

---
None