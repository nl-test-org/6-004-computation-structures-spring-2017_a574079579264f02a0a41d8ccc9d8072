---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: e8eEyYmLx98
  parent_uid: fc4b99996a40954dbb7c6ae8091fcb71
  title: Video-YouTube-Stream
  type: Video
  uid: ef79c035b75e88bd34d27c1a2efb6e10
- id: 3Play-3Play YouTube id-Stream
  media_location: e8eEyYmLx98
  parent_uid: fc4b99996a40954dbb7c6ae8091fcb71
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 6229e0b6281ac2e6735f1c0587e471a5
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/e8eEyYmLx98/default.jpg
  parent_uid: fc4b99996a40954dbb7c6ae8091fcb71
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 1d2fb3a5dddaa6114e227e1d701fd59e
- id: e8eEyYmLx98.srt
  parent_uid: fc4b99996a40954dbb7c6ae8091fcb71
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/c11s2v5/optimization-and-code-generation-8-23-/e8eEyYmLx98.srt
  title: 3play caption file
  type: null
  uid: adcc5ffcc38742fdf246a2f53451a4f3
- id: e8eEyYmLx98.pdf
  parent_uid: fc4b99996a40954dbb7c6ae8091fcb71
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/c11s2v5/optimization-and-code-generation-8-23-/e8eEyYmLx98.pdf
  title: 3play pdf file
  type: null
  uid: 72621bfac6f9ede38bc4baad914dc1e5
- id: Caption-3Play YouTube id-SRT
  parent_uid: fc4b99996a40954dbb7c6ae8091fcb71
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: cda26abc864c95b82b4bc7a387be1486
- id: Transcript-3Play YouTube id-PDF
  parent_uid: fc4b99996a40954dbb7c6ae8091fcb71
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: f78147fa63fee1dc061284ad24a41403
- id: Video--MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_11-02-05_300k.mp4
  parent_uid: fc4b99996a40954dbb7c6ae8091fcb71
  title: Video--MP4
  type: Video
  uid: e7579ec61653eae5f23b298d5390a3cb
inline_embed_id: 75238339optimizationandcodegeneration82339866453
layout: video
order_index: null
parent_uid: 8d370837a9d20baa3914e7ab501e5c34
related_resources_text: ''
short_url: optimization-and-code-generation-8-23-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/c11s2v5/optimization-and-code-generation-8-23-
template_type: Embed
title: Optimization and Code Generation (8:23)
transcript: <p><span m='1000'>The</span> <span m='1378'>syntax</span> <span m='1757'>tree</span>
  <span m='2136'>is</span> <span m='2515'>a</span> <span m='2893'>useful</span> <span
  m='3272'>intermediate</span> <span m='3651'>representation</span> <span m='4030'>(IR)</span>
  <span m='4408'>that</span> <span m='4787'>is</span> <span m='5166'>independent</span>
  <span m='5545'>of</span> <span m='5923'>both</span> <span m='6302'>the</span> <span
  m='6681'>source</span> <span m='7060'>language</span> <span m='7527'>and</span>
  <span m='7994'>the</span> <span m='8461'>target</span> <span m='8929'>ISA.</span>
  <span m='9396'>It</span> <span m='9863'>contains</span> <span m='10330'>information</span>
  <span m='10798'>about</span> <span m='11265'>the</span> <span m='11732'>sequencing</span>
  <span m='12200'>and</span> <span m='12685'>grouping</span> <span m='13170'>of</span>
  <span m='13655'>operations</span> <span m='14140'>that</span> <span m='14625'>isn't</span>
  <span m='15110'>apparent</span> <span m='15595'>in</span> <span m='16080'>individual</span>
  <span m='16565'>machine</span> <span m='17050'>language</span> <span m='17535'>instructions.</span>
  </p><p><span m='18020'>And</span> <span m='18356'>it</span> <span m='18692'>allows</span>
  <span m='19029'>frontends</span> <span m='19365'>for</span> <span m='19702'>different</span>
  <span m='20038'>source</span> <span m='20375'>languages</span> <span m='20711'>to</span>
  <span m='21047'>share</span> <span m='21384'>a</span> <span m='21720'>common</span>
  <span m='22057'>backend</span> <span m='22393'>targeting</span> <span m='22730'>a</span>
  <span m='23174'>specific</span> <span m='23618'>ISA.</span> <span m='24063'>As</span>
  <span m='24507'>we'll</span> <span m='24952'>see,</span> <span m='25396'>the</span>
  <span m='25841'>backend</span> <span m='26285'>processing</span> <span m='26730'>can</span>
  <span m='27174'>be</span> <span m='27619'>split</span> <span m='28298'>into</span>
  <span m='28977'>two</span> <span m='29656'>sub-phases.</span> <span m='30335'>The</span>
  <span m='31014'>first</span> <span m='31693'>performs</span> <span m='32372'>machine-independent</span>
  <span m='33051'>optimizations</span> <span m='33730'>on</span> <span m='34333'>the</span>
  <span m='34937'>IR.</span> <span m='35540'>The</span> <span m='36144'>optimized</span>
  <span m='36748'>IR</span> <span m='37351'>is</span> <span m='37955'>then</span>
  <span m='38559'>translated</span> <span m='39162'>by</span> <span m='39766'>the</span>
  <span m='40370'>code</span> <span m='40916'>generation</span> <span m='41462'>phase</span>
  <span m='42009'>into</span> <span m='42555'>sequences</span> <span m='43101'>of</span>
  <span m='43648'>instructions</span> <span m='44194'>for</span> <span m='44740'>the</span>
  <span m='45287'>target</span> <span m='45833'>ISA.</span> </p><p><span m='46380'>A</span>
  <span m='46799'>common</span> <span m='47218'>IR</span> <span m='47638'>is</span>
  <span m='48057'>to</span> <span m='48477'>reorganize</span> <span m='48896'>the</span>
  <span m='49315'>syntax</span> <span m='49735'>tree</span> <span m='50154'>into</span>
  <span m='50574'>what's</span> <span m='50993'>called</span> <span m='51412'>a</span>
  <span m='51832'>control</span> <span m='52251'>flow</span> <span m='52671'>graph</span>
  <span m='53090'>(CFG).</span> </p><p><span m='53510'>Each</span> <span m='53841'>node</span>
  <span m='54172'>in</span> <span m='54503'>the</span> <span m='54834'>graph</span>
  <span m='55165'>is</span> <span m='55497'>a</span> <span m='55828'>sequence</span>
  <span m='56159'>of</span> <span m='56490'>assignment</span> <span m='56821'>and</span>
  <span m='57153'>expression</span> <span m='57484'>evaluations</span> <span m='57815'>that</span>
  <span m='58146'>ends</span> <span m='58477'>with</span> <span m='58809'>a</span>
  <span m='59227'>branch.</span> <span m='59645'>The</span> <span m='60063'>nodes</span>
  <span m='60481'>are</span> <span m='60899'>called</span> <span m='61317'>"basic</span>
  <span m='61735'>blocks"</span> <span m='62153'>and</span> <span m='62571'>represent</span>
  <span m='62989'>sequences</span> <span m='63420'>of</span> <span m='63851'>operations</span>
  <span m='64282'>that</span> <span m='64713'>are</span> <span m='65145'>executed</span>
  <span m='65576'>as</span> <span m='66007'>a</span> <span m='66438'>unit.</span>
  </p><p><span m='66870'>Once</span> <span m='67198'>the</span> <span m='67527'>first</span>
  <span m='67855'>operation</span> <span m='68184'>in</span> <span m='68512'>a</span>
  <span m='68841'>basic</span> <span m='69170'>block</span> <span m='69498'>is</span>
  <span m='69827'>performed,</span> <span m='70155'>the</span> <span m='70484'>remaining</span>
  <span m='70812'>operations</span> <span m='71141'>will</span> <span m='71470'>also</span>
  <span m='72036'>be</span> <span m='72602'>performed</span> <span m='73168'>without</span>
  <span m='73735'>any</span> <span m='74301'>other</span> <span m='74867'>intervening</span>
  <span m='75433'>operations.</span> </p><p><span m='76000'>This</span> <span m='76472'>knowledge</span>
  <span m='76945'>lets</span> <span m='77417'>us</span> <span m='77890'>consider</span>
  <span m='78362'>many</span> <span m='78835'>optimizations,</span> <span m='79307'>e.g.,</span>
  <span m='79780'>temporarily</span> <span m='80252'>storing</span> <span m='80725'>variable</span>
  <span m='81197'>values</span> <span m='81670'>in</span> <span m='82067'>registers,</span>
  <span m='82465'>that</span> <span m='82863'>would</span> <span m='83261'>be</span>
  <span m='83659'>complicated</span> <span m='84057'>if</span> <span m='84455'>there</span>
  <span m='84852'>was</span> <span m='85250'>the</span> <span m='85648'>possibility</span>
  <span m='86046'>that</span> <span m='86444'>other</span> <span m='86842'>operations</span>
  <span m='87240'>outside</span> <span m='87516'>the</span> <span m='87792'>block</span>
  <span m='88069'>might</span> <span m='88345'>also</span> <span m='88622'>need</span>
  <span m='88898'>to</span> <span m='89175'>access</span> <span m='89451'>the</span>
  <span m='89728'>variable</span> <span m='90004'>values</span> <span m='90281'>while</span>
  <span m='90557'>we</span> <span m='90834'>were</span> <span m='91110'>in</span>
  <span m='91387'>the</span> <span m='91663'>middle</span> <span m='91940'>of</span>
  <span m='92388'>this</span> <span m='92836'>block.</span> <span m='93284'>The</span>
  <span m='93732'>edges</span> <span m='94180'>of</span> <span m='94628'>the</span>
  <span m='95076'>graph</span> <span m='95524'>indicate</span> <span m='95972'>the</span>
  <span m='96420'>branches</span> <span m='96869'>that</span> <span m='97390'>take</span>
  <span m='97912'>us</span> <span m='98433'>to</span> <span m='98955'>another</span>
  <span m='99476'>basic</span> <span m='99998'>block.</span> <span m='100519'>For</span>
  <span m='101041'>example,</span> <span m='101562'>here's</span> <span m='102084'>the</span>
  <span m='102605'>CFG</span> <span m='103127'>for</span> <span m='103648'>GCD.</span>
  </p><p><span m='104170'>If</span> <span m='104468'>a</span> <span m='104767'>basic</span>
  <span m='105066'>block</span> <span m='105365'>ends</span> <span m='105664'>with</span>
  <span m='105963'>a</span> <span m='106261'>conditional</span> <span m='106560'>branch,</span>
  <span m='106859'>there</span> <span m='107158'>are</span> <span m='107457'>two</span>
  <span m='107756'>edges,</span> <span m='108054'>labeled</span> <span m='108353'>"T"</span>
  <span m='108652'>and</span> <span m='108951'>"F"</span> <span m='109250'>leaving</span>
  <span m='109549'>the</span> <span m='109899'>block</span> <span m='110250'>that</span>
  <span m='110600'>indicate</span> <span m='110951'>the</span> <span m='111301'>next</span>
  <span m='111652'>block</span> <span m='112002'>to</span> <span m='112353'>execute</span>
  <span m='112704'>depending</span> <span m='113054'>on</span> <span m='113405'>the</span>
  <span m='113755'>outcome</span> <span m='114106'>of</span> <span m='114456'>the</span>
  <span m='114807'>test.</span> </p><p><span m='115158'>Other</span> <span m='115529'>blocks</span>
  <span m='115901'>have</span> <span m='116272'>only</span> <span m='116644'>a</span>
  <span m='117015'>single</span> <span m='117387'>departing</span> <span m='117759'>arrow,</span>
  <span m='118130'>indicating</span> <span m='118502'>that</span> <span m='118873'>the</span>
  <span m='119245'>block</span> <span m='119616'>always</span> <span m='119988'>transfers</span>
  <span m='120360'>control</span> <span m='120692'>to</span> <span m='121025'>the</span>
  <span m='121358'>block</span> <span m='121691'>indicated</span> <span m='122023'>by</span>
  <span m='122356'>the</span> <span m='122689'>arrow.</span> <span m='123022'>Note</span>
  <span m='123355'>that</span> <span m='123687'>if</span> <span m='124020'>we</span>
  <span m='124353'>can</span> <span m='124686'>arrive</span> <span m='125018'>at</span>
  <span m='125351'>a</span> <span m='125684'>block</span> <span m='126017'>from</span>
  <span m='126350'>only</span> <span m='126725'>a</span> <span m='127101'>single</span>
  <span m='127477'>predecessor</span> <span m='127852'>block,</span> <span m='128228'>then</span>
  <span m='128604'>any</span> <span m='128980'>knowledge</span> <span m='129355'>we</span>
  <span m='129731'>have</span> <span m='130107'>about</span> <span m='130482'>operations</span>
  <span m='130858'>and</span> <span m='131234'>variables</span> <span m='131610'>from</span>
  <span m='132044'>the</span> <span m='132478'>predecessor</span> <span m='132912'>block</span>
  <span m='133346'>can</span> <span m='133780'>be</span> <span m='134215'>carried</span>
  <span m='134649'>over</span> <span m='135083'>to</span> <span m='135517'>the</span>
  <span m='135951'>destination</span> <span m='136385'>block.</span> </p><p><span
  m='136820'>For</span> <span m='137171'>example,</span> <span m='137522'>if</span>
  <span m='137873'>the</span> <span m='138224'>"if</span> <span m='138575'>(x</span>
  <span m='138926'>&gt;</span> <span m='139277'>y)"</span> <span m='139628'>block</span>
  <span m='139979'>has</span> <span m='140330'>generated</span> <span m='140681'>code</span>
  <span m='141032'>to</span> <span m='141383'>load</span> <span m='141734'>the</span>
  <span m='142085'>values</span> <span m='142436'>of</span> <span m='142787'>x</span>
  <span m='143138'>and</span> <span m='143489'>y</span> <span m='143932'>into</span>
  <span m='144376'>registers,</span> <span m='144819'>both</span> <span m='145263'>destination</span>
  <span m='145707'>blocks</span> <span m='146150'>can</span> <span m='146594'>use</span>
  <span m='147038'>that</span> <span m='147481'>information</span> <span m='147925'>and</span>
  <span m='148369'>use</span> <span m='148812'>the</span> <span m='149256'>appropriate</span>
  <span m='149700'>registers</span> <span m='150176'>without</span> <span m='150652'>having</span>
  <span m='151128'>to</span> <span m='151605'>generate</span> <span m='152081'>their</span>
  <span m='152557'>own</span> <span m='153033'>LDs.</span> </p><p><span m='153510'>But</span>
  <span m='153963'>if</span> <span m='154416'>a</span> <span m='154870'>block</span>
  <span m='155323'>has</span> <span m='155776'>multiple</span> <span m='156230'>predecessors,</span>
  <span m='156683'>such</span> <span m='157136'>optimizations</span> <span m='157590'>are</span>
  <span m='158043'>more</span> <span m='158496'>constrained.</span> </p><p><span m='158950'>We</span>
  <span m='159313'>can</span> <span m='159677'>only</span> <span m='160041'>use</span>
  <span m='160405'>knowledge</span> <span m='160769'>that</span> <span m='161133'>is</span>
  <span m='161496'>common</span> <span m='161860'>to</span> <span m='162224'>*all*</span>
  <span m='162588'>the</span> <span m='162952'>predecessor</span> <span m='163316'>blocks.</span>
  </p><p><span m='163680'>The</span> <span m='164083'>CFG</span> <span m='164487'>looks</span>
  <span m='164890'>a</span> <span m='165294'>lot</span> <span m='165697'>like</span>
  <span m='166101'>the</span> <span m='166504'>state</span> <span m='166908'>transition</span>
  <span m='167311'>diagram</span> <span m='167715'>for</span> <span m='168118'>a</span>
  <span m='168522'>high-level</span> <span m='168925'>FSM!</span> </p><p><span m='169329'>We'll</span>
  <span m='169959'>optimize</span> <span m='170590'>the</span> <span m='171221'>IR</span>
  <span m='171852'>by</span> <span m='172483'>performing</span> <span m='173114'>multiple</span>
  <span m='173745'>passes</span> <span m='174376'>over</span> <span m='175007'>the</span>
  <span m='175638'>CFG.</span> </p><p><span m='176269'>Each</span> <span m='176796'>pass</span>
  <span m='177323'>performs</span> <span m='177850'>a</span> <span m='178377'>specific,</span>
  <span m='178904'>simple</span> <span m='179431'>optimization.</span> <span m='179958'>We'll</span>
  <span m='180485'>repeatedly</span> <span m='181012'>apply</span> <span m='181539'>the</span>
  <span m='182066'>simple</span> <span m='182593'>optimizations</span> <span m='183120'>in</span>
  <span m='183597'>multiple</span> <span m='184074'>passes,</span> <span m='184552'>until</span>
  <span m='185029'>we</span> <span m='185507'>can't</span> <span m='185984'>find</span>
  <span m='186461'>any</span> <span m='186939'>further</span> <span m='187416'>optimizations</span>
  <span m='187894'>to</span> <span m='188371'>perform.</span> </p><p><span m='188849'>Collectively,</span>
  <span m='189439'>the</span> <span m='190029'>simple</span> <span m='190619'>optimizations</span>
  <span m='191209'>can</span> <span m='191799'>combine</span> <span m='192389'>to</span>
  <span m='192979'>achieve</span> <span m='193569'>very</span> <span m='194159'>complex</span>
  <span m='194749'>optimizations.</span> </p><p><span m='195340'>Here</span> <span
  m='195758'>are</span> <span m='196176'>some</span> <span m='196594'>example</span>
  <span m='197012'>optimizations:</span> <span m='197430'>We</span> <span m='197849'>can</span>
  <span m='198267'>eliminate</span> <span m='198685'>assignments</span> <span m='199103'>to</span>
  <span m='199521'>variables</span> <span m='199940'>that</span> <span m='200239'>are</span>
  <span m='200538'>never</span> <span m='200837'>used</span> <span m='201136'>and</span>
  <span m='201435'>basic</span> <span m='201734'>blocks</span> <span m='202033'>that</span>
  <span m='202332'>are</span> <span m='202631'>never</span> <span m='202930'>reached.</span>
  </p><p><span m='203230'>This</span> <span m='203817'>is</span> <span m='204405'>called</span>
  <span m='204992'>"dead</span> <span m='205580'>code</span> <span m='206167'>elimination".</span>
  <span m='206755'>In</span> <span m='207342'>constant</span> <span m='207930'>propagation,</span>
  <span m='208517'>we</span> <span m='209105'>identify</span> <span m='209692'>variables</span>
  <span m='210280'>that</span> <span m='210582'>have</span> <span m='210884'>a</span>
  <span m='211186'>constant</span> <span m='211488'>value</span> <span m='211790'>and</span>
  <span m='212092'>substitute</span> <span m='212394'>that</span> <span m='212696'>constant</span>
  <span m='212998'>in</span> <span m='213300'>place</span> <span m='213602'>of</span>
  <span m='213904'>references</span> <span m='214206'>to</span> <span m='214508'>the</span>
  <span m='214810'>variable.</span> <span m='215163'>We</span> <span m='215516'>can</span>
  <span m='215869'>compute</span> <span m='216222'>the</span> <span m='216576'>value</span>
  <span m='216929'>of</span> <span m='217282'>expressions</span> <span m='217635'>that</span>
  <span m='217989'>have</span> <span m='218649'>constant</span> <span m='219309'>operands.</span>
  <span m='219969'>This</span> <span m='220629'>is</span> <span m='221289'>called</span>
  <span m='221949'>"constant</span> <span m='222609'>folding".</span> </p><p><span
  m='223269'>To</span> <span m='223684'>illustrate</span> <span m='224100'>how</span>
  <span m='224516'>these</span> <span m='224932'>optimizations</span> <span m='225348'>work,</span>
  <span m='225764'>consider</span> <span m='226180'>this</span> <span m='226596'>slightly</span>
  <span m='227012'>silly</span> <span m='227428'>source</span> <span m='227844'>program</span>
  <span m='228260'>and</span> <span m='228674'>its</span> <span m='229089'>CFG.</span>
  <span m='229504'>Note</span> <span m='229919'>that</span> <span m='230334'>we've</span>
  <span m='230749'>broken</span> <span m='231164'>down</span> <span m='231579'>complicated</span>
  <span m='231994'>expressions</span> <span m='232409'>into</span> <span m='232961'>simple</span>
  <span m='233514'>binary</span> <span m='234067'>operations,</span> <span m='234620'>using</span>
  <span m='235173'>temporary</span> <span m='235726'>variable</span> <span m='236279'>names</span>
  <span m='236832'>(e.g,</span> <span m='237385'>"_t1")</span> <span m='237938'>to</span>
  <span m='238491'>name</span> <span m='239044'>the</span> <span m='239597'>intermediate</span>
  <span m='240150'>results.</span> <span m='240859'>Let's</span> <span m='241569'>get</span>
  <span m='242279'>started!</span> </p><p><span m='242989'>The</span> <span m='243294'>dead</span>
  <span m='243600'>code</span> <span m='243905'>elimination</span> <span m='244211'>pass</span>
  <span m='244517'>can</span> <span m='244822'>remove</span> <span m='245128'>the</span>
  <span m='245434'>assignment</span> <span m='245739'>to</span> <span m='246045'>Z</span>
  <span m='246350'>in</span> <span m='246656'>the</span> <span m='246962'>first</span>
  <span m='247267'>basic</span> <span m='247573'>block</span> <span m='247879'>since</span>
  <span m='248244'>Z</span> <span m='248610'>is</span> <span m='248976'>reassigned</span>
  <span m='249342'>in</span> <span m='249707'>subsequent</span> <span m='250073'>blocks</span>
  <span m='250439'>and</span> <span m='250805'>the</span> <span m='251171'>intervening</span>
  <span m='251536'>code</span> <span m='251902'>makes</span> <span m='252268'>no</span>
  <span m='252634'>reference</span> <span m='253000'>to</span> <span m='253527'>Z.</span>
  <span m='254055'>Next</span> <span m='254583'>we</span> <span m='255111'>look</span>
  <span m='255639'>for</span> <span m='256167'>variables</span> <span m='256695'>with</span>
  <span m='257223'>constant</span> <span m='257751'>values.</span> </p><p><span m='258279'>Here</span>
  <span m='258576'>we</span> <span m='258874'>find</span> <span m='259172'>that</span>
  <span m='259470'>X</span> <span m='259768'>is</span> <span m='260066'>assigned</span>
  <span m='260364'>the</span> <span m='260662'>value</span> <span m='260960'>of</span>
  <span m='261258'>3</span> <span m='261556'>and</span> <span m='261854'>is</span>
  <span m='262152'>never</span> <span m='262450'>re-assigned,</span> <span m='262748'>so</span>
  <span m='263046'>we</span> <span m='263344'>can</span> <span m='263642'>replace</span>
  <span m='263940'>all</span> <span m='264405'>references</span> <span m='264871'>to</span>
  <span m='265337'>X</span> <span m='265802'>with</span> <span m='266268'>the</span>
  <span m='266734'>constant</span> <span m='267200'>3.</span> <span m='267665'>Now</span>
  <span m='268131'>perform</span> <span m='268597'>constant</span> <span m='269062'>folding</span>
  <span m='269528'>[CLICK],</span> <span m='269994'>evaluating</span> <span m='270460'>any</span>
  <span m='271082'>constant</span> <span m='271704'>expressions.</span> <span m='272326'>Here's</span>
  <span m='272948'>the</span> <span m='273570'>updated</span> <span m='274192'>CFG,</span>
  <span m='274814'>ready</span> <span m='275436'>for</span> <span m='276058'>another</span>
  <span m='276680'>round</span> <span m='277382'>of</span> <span m='278085'>optimizations.</span>
  <span m='278788'>First</span> <span m='279491'>dead</span> <span m='280194'>code</span>
  <span m='280897'>elimination.</span> </p><p><span m='281600'>Then</span> <span m='282510'>constant</span>
  <span m='283420'>propagation.</span> <span m='284330'>And,</span> <span m='285240'>finally,</span>
  <span m='286150'>constant</span> <span m='287060'>folding.</span> </p><p><span m='287970'>So</span>
  <span m='288318'>after</span> <span m='288666'>two</span> <span m='289014'>rounds</span>
  <span m='289362'>of</span> <span m='289710'>these</span> <span m='290058'>simple</span>
  <span m='290406'>operations,</span> <span m='290754'>we've</span> <span m='291102'>thinned</span>
  <span m='291450'>out</span> <span m='291798'>a</span> <span m='292146'>number</span>
  <span m='292494'>of</span> <span m='292842'>assignments.</span> </p><p><span m='293190'>On</span>
  <span m='293674'>to</span> <span m='294158'>round</span> <span m='294642'>three!</span>
  <span m='295127'>Dead</span> <span m='295611'>code</span> <span m='296095'>elimination.</span>
  </p><p><span m='296580'>And</span> <span m='296924'>here</span> <span m='297268'>we</span>
  <span m='297612'>can</span> <span m='297957'>determine</span> <span m='298301'>the</span>
  <span m='298645'>outcome</span> <span m='298990'>of</span> <span m='299334'>a</span>
  <span m='299678'>conditional</span> <span m='300022'>branch,</span> <span m='300367'>eliminating</span>
  <span m='300711'>entire</span> <span m='301055'>basic</span> <span m='301400'>blocks</span>
  <span m='301767'>from</span> <span m='302135'>the</span> <span m='302502'>IR,</span>
  <span m='302870'>either</span> <span m='303237'>because</span> <span m='303605'>they're</span>
  <span m='303972'>now</span> <span m='304340'>empty</span> <span m='304707'>or</span>
  <span m='305075'>because</span> <span m='305442'>they</span> <span m='305810'>can</span>
  <span m='306177'>no</span> <span m='306545'>longer</span> <span m='306912'>be</span>
  <span m='307280'>reached.</span> <span m='308116'>Wow,</span> <span m='308952'>the</span>
  <span m='309788'>IR</span> <span m='310625'>is</span> <span m='311461'>now</span>
  <span m='312297'>considerably</span> <span m='313133'>smaller.</span> </p><p><span
  m='313970'>Next</span> <span m='314570'>is</span> <span m='315170'>another</span>
  <span m='315770'>application</span> <span m='316370'>of</span> <span m='316970'>constant</span>
  <span m='317570'>propagation.</span> <span m='318170'>And</span> <span m='318770'>then</span>
  <span m='319370'>constant</span> <span m='319970'>folding.</span> </p><p><span m='320570'>Followed</span>
  <span m='321016'>by</span> <span m='321463'>more</span> <span m='321910'>dead</span>
  <span m='322357'>code</span> <span m='322804'>elimination.</span> <span m='323251'>The</span>
  <span m='323698'>passes</span> <span m='324145'>continue</span> <span m='324592'>until</span>
  <span m='325039'>we</span> <span m='325486'>discover</span> <span m='325933'>there</span>
  <span m='326380'>are</span> <span m='326915'>no</span> <span m='327451'>further</span>
  <span m='327986'>optimizations</span> <span m='328522'>to</span> <span m='329057'>perform,</span>
  <span m='329593'>so</span> <span m='330128'>we're</span> <span m='330664'>done!</span>
  </p><p><span m='331200'>Repeated</span> <span m='331575'>applications</span> <span
  m='331950'>of</span> <span m='332325'>these</span> <span m='332700'>simple</span>
  <span m='333075'>transformations</span> <span m='333450'>have</span> <span m='333825'>transformed</span>
  <span m='334200'>the</span> <span m='334575'>original</span> <span m='334950'>program</span>
  <span m='335325'>into</span> <span m='335700'>an</span> <span m='336174'>equivalent</span>
  <span m='336648'>program</span> <span m='337123'>that</span> <span m='337597'>computes</span>
  <span m='338072'>the</span> <span m='338546'>same</span> <span m='339021'>final</span>
  <span m='339495'>value</span> <span m='339970'>for</span> <span m='340444'>Z.</span>
  </p><p><span m='340919'>We</span> <span m='341361'>can</span> <span m='341803'>do</span>
  <span m='342245'>more</span> <span m='342688'>optimizations</span> <span m='343130'>by</span>
  <span m='343572'>adding</span> <span m='344015'>passes:</span> <span m='344457'>eliminating</span>
  <span m='344899'>redundant</span> <span m='345342'>computation</span> <span m='345784'>of</span>
  <span m='346226'>common</span> <span m='346669'>subexpressions,</span> <span m='347333'>moving</span>
  <span m='347997'>loop-independent</span> <span m='348662'>calculations</span> <span
  m='349326'>out</span> <span m='349991'>of</span> <span m='350655'>loops,</span>
  <span m='351320'>unrolling</span> <span m='351681'>short</span> <span m='352042'>loops</span>
  <span m='352403'>to</span> <span m='352765'>perform</span> <span m='353126'>the</span>
  <span m='353487'>effect</span> <span m='353848'>of,</span> <span m='354210'>say,</span>
  <span m='354571'>two</span> <span m='354932'>iterations</span> <span m='355293'>in</span>
  <span m='355655'>a</span> <span m='356016'>single</span> <span m='356377'>loop</span>
  <span m='356738'>execution,</span> <span m='357100'>saving</span> <span m='357534'>some</span>
  <span m='357969'>of</span> <span m='358404'>the</span> <span m='358839'>cost</span>
  <span m='359274'>of</span> <span m='359709'>increment</span> <span m='360144'>and</span>
  <span m='360579'>test</span> <span m='361014'>instructions.</span> </p><p><span
  m='361449'>Optimizing</span> <span m='361858'>compilers</span> <span m='362267'>have</span>
  <span m='362676'>a</span> <span m='363086'>sophisticated</span> <span m='363495'>set</span>
  <span m='363904'>of</span> <span m='364314'>optimizations</span> <span m='364723'>they</span>
  <span m='365132'>employ</span> <span m='365542'>to</span> <span m='365951'>make</span>
  <span m='366360'>smaller</span> <span m='366770'>and</span> <span m='367281'>more</span>
  <span m='367792'>efficient</span> <span m='368303'>code.</span> <span m='368814'>Okay,</span>
  <span m='369325'>we're</span> <span m='369836'>done</span> <span m='370347'>with</span>
  <span m='370858'>optimizations.</span> </p><p><span m='371370'>Now</span> <span
  m='371750'>it's</span> <span m='372130'>time</span> <span m='372510'>to</span> <span
  m='372890'>generate</span> <span m='373270'>instructions</span> <span m='373650'>for</span>
  <span m='374030'>the</span> <span m='374410'>target</span> <span m='374790'>ISA.</span>
  </p><p><span m='375170'>First</span> <span m='375618'>the</span> <span m='376066'>code</span>
  <span m='376514'>generator</span> <span m='376962'>assigns</span> <span m='377410'>each</span>
  <span m='377858'>variable</span> <span m='378306'>a</span> <span m='378754'>dedicated</span>
  <span m='379202'>register.</span> </p><p><span m='379650'>If</span> <span m='379927'>we</span>
  <span m='380204'>have</span> <span m='380482'>more</span> <span m='380759'>variables</span>
  <span m='381036'>than</span> <span m='381314'>registers,</span> <span m='381591'>some</span>
  <span m='381868'>variables</span> <span m='382146'>are</span> <span m='382423'>stored</span>
  <span m='382700'>in</span> <span m='382978'>memory</span> <span m='383255'>and</span>
  <span m='383532'>we'll</span> <span m='383810'>use</span> <span m='384208'>LD</span>
  <span m='384607'>and</span> <span m='385005'>ST</span> <span m='385404'>to</span>
  <span m='385802'>access</span> <span m='386201'>them</span> <span m='386599'>as</span>
  <span m='386998'>needed.</span> <span m='387396'>But</span> <span m='387795'>frequently-used</span>
  <span m='388193'>variables</span> <span m='388592'>will</span> <span m='388990'>almost</span>
  <span m='389389'>certainly</span> <span m='389772'>live</span> <span m='390155'>as</span>
  <span m='390539'>much</span> <span m='390922'>as</span> <span m='391305'>possible</span>
  <span m='391689'>in</span> <span m='392072'>registers.</span> <span m='392455'>Use</span>
  <span m='392839'>our</span> <span m='393222'>templates</span> <span m='393605'>from</span>
  <span m='393989'>before</span> <span m='394372'>to</span> <span m='394755'>translate</span>
  <span m='395139'>each</span> <span m='395631'>assignment</span> <span m='396123'>and</span>
  <span m='396615'>operation</span> <span m='397107'>into</span> <span m='397600'>one</span>
  <span m='398092'>or</span> <span m='398584'>more</span> <span m='399076'>instructions.</span>
  </p><p><span m='399569'>The</span> <span m='399970'>emit</span> <span m='400372'>the</span>
  <span m='400773'>code</span> <span m='401175'>for</span> <span m='401576'>each</span>
  <span m='401978'>block,</span> <span m='402379'>adding</span> <span m='402781'>the</span>
  <span m='403182'>appropriate</span> <span m='403584'>labels</span> <span m='403985'>and</span>
  <span m='404387'>branches.</span> </p><p><span m='404789'>Reorder</span> <span m='405266'>the</span>
  <span m='405743'>basic</span> <span m='406220'>block</span> <span m='406698'>code</span>
  <span m='407175'>to</span> <span m='407652'>eliminate</span> <span m='408129'>unconditional</span>
  <span m='408607'>branches</span> <span m='409084'>wherever</span> <span m='409561'>possible.</span>
  </p><p><span m='410039'>And</span> <span m='410849'>finally</span> <span m='411659'>perform</span>
  <span m='412469'>any</span> <span m='413279'>target-specific</span> <span m='414089'>peephole</span>
  <span m='414899'>optimizations.</span> </p><p><span m='415710'>Here's</span> <span
  m='416180'>the</span> <span m='416651'>original</span> <span m='417122'>CFG</span>
  <span m='417592'>for</span> <span m='418063'>the</span> <span m='418534'>GCD</span>
  <span m='419005'>code,</span> <span m='419475'>along</span> <span m='419946'>with</span>
  <span m='420417'>the</span> <span m='420887'>slightly</span> <span m='421358'>optimized</span>
  <span m='421829'>CFG.</span> </p><p><span m='422300'>GCD</span> <span m='422566'>isn't</span>
  <span m='422832'>as</span> <span m='423098'>trivial</span> <span m='423365'>as</span>
  <span m='423631'>the</span> <span m='423897'>previous</span> <span m='424164'>example,</span>
  <span m='424430'>so</span> <span m='424696'>we've</span> <span m='424963'>only</span>
  <span m='425229'>been</span> <span m='425495'>able</span> <span m='425762'>to</span>
  <span m='426028'>do</span> <span m='426294'>a</span> <span m='426561'>bit</span>
  <span m='426827'>of</span> <span m='427093'>constant</span> <span m='427360'>propagation</span>
  <span m='427803'>and</span> <span m='428247'>constant</span> <span m='428690'>folding.</span>
  <span m='429134'>Note</span> <span m='429578'>that</span> <span m='430021'>we</span>
  <span m='430465'>can't</span> <span m='430909'>propagate</span> <span m='431352'>knowledge</span>
  <span m='431796'>about</span> <span m='432240'>variable</span> <span m='432580'>values</span>
  <span m='432921'>from</span> <span m='433261'>the</span> <span m='433602'>top</span>
  <span m='433943'>basic</span> <span m='434283'>block</span> <span m='434624'>to</span>
  <span m='434965'>the</span> <span m='435305'>following</span> <span m='435646'>"if"</span>
  <span m='435986'>block</span> <span m='436327'>since</span> <span m='436668'>the</span>
  <span m='437008'>"if"</span> <span m='437349'>block</span> <span m='437690'>has</span>
  <span m='438190'>multiple</span> <span m='438690'>predecessors.</span> <span m='439190'>Here's</span>
  <span m='439690'>how</span> <span m='440190'>the</span> <span m='440690'>code</span>
  <span m='441190'>generator</span> <span m='441690'>will</span> <span m='442190'>process</span>
  <span m='442690'>the</span> <span m='443159'>optimized</span> <span m='443628'>CFG.</span>
  <span m='444097'>First,</span> <span m='444566'>it</span> <span m='445035'>dedicates</span>
  <span m='445504'>registers</span> <span m='445973'>to</span> <span m='446442'>hold</span>
  <span m='446911'>the</span> <span m='447380'>values</span> <span m='447693'>for</span>
  <span m='448006'>x</span> <span m='448320'>and</span> <span m='448633'>y.</span>
  <span m='448946'>Then,</span> <span m='449260'>it</span> <span m='449573'>emits</span>
  <span m='449886'>the</span> <span m='450200'>code</span> <span m='450513'>for</span>
  <span m='450826'>each</span> <span m='451140'>of</span> <span m='451453'>the</span>
  <span m='451766'>basic</span> <span m='452080'>blocks.</span> <span m='452462'>Next,</span>
  <span m='452844'>reorganize</span> <span m='453226'>the</span> <span m='453608'>order</span>
  <span m='453991'>of</span> <span m='454373'>the</span> <span m='454755'>basic</span>
  <span m='455137'>blocks</span> <span m='455520'>to</span> <span m='456196'>eliminate</span>
  <span m='456873'>unconditional</span> <span m='457550'>branches</span> <span m='458226'>wherever</span>
  <span m='458903'>possible.</span> </p><p><span m='459580'>The</span> <span m='459918'>resulting</span>
  <span m='460257'>code</span> <span m='460595'>is</span> <span m='460934'>pretty</span>
  <span m='461272'>good.</span> <span m='461611'>There</span> <span m='461950'>no</span>
  <span m='462288'>obvious</span> <span m='462627'>changes</span> <span m='462965'>that</span>
  <span m='463304'>a</span> <span m='463642'>human</span> <span m='463981'>programmer</span>
  <span m='464320'>might</span> <span m='464834'>make</span> <span m='465348'>to</span>
  <span m='465862'>make</span> <span m='466376'>the</span> <span m='466890'>code</span>
  <span m='467405'>faster</span> <span m='467919'>or</span> <span m='468433'>smaller.</span>
  <span m='468947'>Good</span> <span m='469461'>job,</span> <span m='469975'>compiler!</span>
  </p><p><span m='470490'>Here</span> <span m='470798'>are</span> <span m='471107'>all</span>
  <span m='471416'>the</span> <span m='471725'>compilation</span> <span m='472033'>steps</span>
  <span m='472342'>shown</span> <span m='472651'>in</span> <span m='472960'>order,</span>
  <span m='473268'>along</span> <span m='473577'>with</span> <span m='473886'>their</span>
  <span m='474195'>input</span> <span m='474503'>and</span> <span m='474812'>output</span>
  <span m='475121'>data</span> <span m='475430'>structures.</span> <span m='475945'>Collectively</span>
  <span m='476461'>they</span> <span m='476976'>transform</span> <span m='477492'>the</span>
  <span m='478007'>original</span> <span m='478523'>source</span> <span m='479039'>code</span>
  <span m='479606'>into</span> <span m='480173'>high-quality</span> <span m='480741'>assembly</span>
  <span m='481308'>code.</span> <span m='481875'>The</span> <span m='482443'>patient</span>
  <span m='483010'>application</span> <span m='483577'>of</span> <span m='484145'>optimization</span>
  <span m='484712'>passes</span> <span m='485280'>often</span> <span m='485784'>produces</span>
  <span m='486288'>code</span> <span m='486792'>that's</span> <span m='487296'>more</span>
  <span m='487800'>efficient</span> <span m='488305'>than</span> <span m='488809'>writing</span>
  <span m='489313'>assembly</span> <span m='489817'>language</span> <span m='490321'>by</span>
  <span m='490825'>hand.</span> </p><p><span m='491330'>Nowadays,</span> <span m='491664'>programmers</span>
  <span m='491999'>are</span> <span m='492334'>able</span> <span m='492668'>to</span>
  <span m='493003'>focus</span> <span m='493338'>on</span> <span m='493672'>getting</span>
  <span m='494007'>the</span> <span m='494342'>source</span> <span m='494676'>code</span>
  <span m='495011'>to</span> <span m='495346'>achieve</span> <span m='495680'>the</span>
  <span m='496015'>desired</span> <span m='496350'>functionality</span> <span m='496729'>and</span>
  <span m='497108'>leave</span> <span m='497487'>the</span> <span m='497867'>details</span>
  <span m='498246'>of</span> <span m='498625'>translation</span> <span m='499004'>to</span>
  <span m='499384'>instructions</span> <span m='499763'>in</span> <span m='500142'>the</span>
  <span m='500521'>hands</span> <span m='500901'>of</span> <span m='501280'>the</span>
  <span m='501659'>compiler.</span> </p>
type: course
uid: fc4b99996a40954dbb7c6ae8091fcb71

---
None