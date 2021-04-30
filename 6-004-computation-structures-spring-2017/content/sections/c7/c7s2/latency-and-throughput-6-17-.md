---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 3HIV4MnLGCw
  parent_uid: 638fbd1751857f9367adb6c3256b4bea
  title: Video-YouTube-Stream
  type: Video
  uid: 84e9eafe0ad027ca198c1eb46b5dc226
- id: 3Play-3Play YouTube id-Stream
  media_location: 3HIV4MnLGCw
  parent_uid: 638fbd1751857f9367adb6c3256b4bea
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 97da8b2cd4a39c599f03df56999c1836
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/3HIV4MnLGCw/default.jpg
  parent_uid: 638fbd1751857f9367adb6c3256b4bea
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 4788c85c529a6b97510e9360c2eb4a7c
- id: 3HIV4MnLGCw.srt
  parent_uid: 638fbd1751857f9367adb6c3256b4bea
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/latency-and-throughput-6-17-/3HIV4MnLGCw.srt
  title: 3play caption file
  type: null
  uid: 3d94718be78680672e47c0c85ab35364
- id: 3HIV4MnLGCw.pdf
  parent_uid: 638fbd1751857f9367adb6c3256b4bea
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/latency-and-throughput-6-17-/3HIV4MnLGCw.pdf
  title: 3play pdf file
  type: null
  uid: 6625d290566fa0dd6ed14bedbf5984fd
- id: Caption-3Play YouTube id-SRT
  parent_uid: 638fbd1751857f9367adb6c3256b4bea
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 0341a7643d3fe55a9f34cd289ebcc1ad
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 638fbd1751857f9367adb6c3256b4bea
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: b7cdedf85564e1937ea21979f71b377c
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_07-02-01_300k.mp4
  parent_uid: 638fbd1751857f9367adb6c3256b4bea
  title: Video-Internet Archive-MP4
  type: Video
  uid: 101f271bf47f5dd40f1e0628ea3b3234
inline_embed_id: 96718172latencyandthroughput61760464617
layout: video
order_index: null
parent_uid: 73b2c57f6d669b9c4894e14fae072f07
related_resources_text: ''
short_url: latency-and-throughput-6-17-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/latency-and-throughput-6-17-
template_type: Embed
title: Latency and Throughput (6:17)
transcript: "<p><span m='659'>In</span> <span m='920'>this</span> <span m='1181'>chapter</span>\
  \ <span m='1442'>our</span> <span m='1704'>goal</span> <span m='1965'>is</span>\
  \ <span m='2226'>to</span> <span m='2487'>introduce</span> <span m='2749'>some</span>\
  \ <span m='3010'>metrics</span> <span m='3271'>for</span> <span m='3532'>measuring</span>\
  \ <span m='3794'>the</span> <span m='4055'>performance</span> <span m='4316'>of</span>\
  \ <span m='4577'>a</span> <span m='4839'>circuit</span> <span m='5295'>and</span>\
  \ <span m='5752'>then</span> <span m='6209'>investigate</span> <span m='6666'>ways</span>\
  \ <span m='7122'>to</span> <span m='7579'>improve</span> <span m='8036'>that</span>\
  \ <span m='8493'>performance.</span> </p><p><span m='8950'>We'll</span> <span m='9210'>start</span>\
  \ <span m='9470'>by</span> <span m='9730'>putting</span> <span m='9990'>aside</span>\
  \ <span m='10250'>circuits</span> <span m='10510'>for</span> <span m='10770'>a</span>\
  \ <span m='11030'>moment</span> <span m='11290'>and</span> <span m='11550'>look</span>\
  \ <span m='11810'>at</span> <span m='12070'>an</span> <span m='12330'>everyday</span>\
  \ <span m='12590'>example</span> <span m='12850'>that</span> <span m='13110'>will</span>\
  \ <span m='13697'>help</span> <span m='14285'>us</span> <span m='14872'>understand</span>\
  \ <span m='15460'>the</span> <span m='16047'>proposed</span> <span m='16635'>performance</span>\
  \ <span m='17222'>metrics.</span> </p><p><span m='17810'>Laundry</span> <span m='18110'>is</span>\
  \ <span m='18411'>a</span> <span m='18712'>processing</span> <span m='19013'>task</span>\
  \ <span m='19313'>we</span> <span m='19614'>all</span> <span m='19915'>have</span>\
  \ <span m='20216'>to</span> <span m='20516'>face</span> <span m='20817'>at</span>\
  \ <span m='21118'>some</span> <span m='21419'>point!</span> </p><p><span m='21720'>The</span>\
  \ <span m='22001'>input</span> <span m='22283'>to</span> <span m='22565'>our</span>\
  \ <span m='22847'>laundry</span> <span m='23128'>\"system\"</span> <span m='23410'>is</span>\
  \ <span m='23692'>some</span> <span m='23974'>number</span> <span m='24255'>of</span>\
  \ <span m='24537'>loads</span> <span m='24819'>of</span> <span m='25101'>dirty</span>\
  \ <span m='25382'>laundry</span> <span m='25664'>and</span> <span m='25946'>the</span>\
  \ <span m='26228'>output</span> <span m='26510'>is</span> <span m='26955'>the</span>\
  \ <span m='27400'>same</span> <span m='27846'>loads,</span> <span m='28291'>but</span>\
  \ <span m='28737'>washed,</span> <span m='29182'>dried,</span> <span m='29628'>and</span>\
  \ <span m='30073'>folded.</span> </p><p><span m='30519'>There</span> <span m='30846'>two</span>\
  \ <span m='31174'>system</span> <span m='31501'>components:</span> <span m='31829'>a</span>\
  \ <span m='32156'>washer</span> <span m='32484'>that</span> <span m='32811'>washes</span>\
  \ <span m='33139'>a</span> <span m='33467'>load</span> <span m='33794'>of</span>\
  \ <span m='34122'>laundry</span> <span m='34449'>in</span> <span m='34777'>30</span>\
  \ <span m='35104'>minutes,</span> <span m='35432'>and</span> <span m='35760'>a</span>\
  \ <span m='36095'>dryer</span> <span m='36431'>that</span> <span m='36766'>dries</span>\
  \ <span m='37102'>a</span> <span m='37437'>load</span> <span m='37773'>in</span>\
  \ <span m='38108'>60</span> <span m='38444'>minutes.</span> </p><p><span m='38780'>You</span>\
  \ <span m='39083'>may</span> <span m='39387'>be</span> <span m='39690'>used</span>\
  \ <span m='39994'>to</span> <span m='40297'>laundry</span> <span m='40601'>system</span>\
  \ <span m='40905'>components</span> <span m='41208'>with</span> <span m='41512'>different</span>\
  \ <span m='41815'>propagation</span> <span m='42119'>delays,</span> <span m='42422'>but</span>\
  \ <span m='42726'>let's</span> <span m='43030'>go</span> <span m='43485'>with</span>\
  \ <span m='43941'>these</span> <span m='44396'>delays</span> <span m='44852'>for</span>\
  \ <span m='45307'>our</span> <span m='45763'>example.</span> </p><p><span m='46219'>Our</span>\
  \ <span m='46550'>laundry</span> <span m='46881'>follows</span> <span m='47212'>a</span>\
  \ <span m='47543'>simple</span> <span m='47875'>path</span> <span m='48206'>through</span>\
  \ <span m='48537'>the</span> <span m='48868'>system:</span> <span m='49200'>each</span>\
  \ <span m='49570'>load</span> <span m='49940'>is</span> <span m='50310'>first</span>\
  \ <span m='50680'>washed</span> <span m='51050'>in</span> <span m='51420'>the</span>\
  \ <span m='51790'>washer</span> <span m='52160'>and</span> <span m='52530'>afterwards</span>\
  \ <span m='52900'>moved</span> <span m='53270'>to</span> <span m='53640'>the</span>\
  \ <span m='54010'>dryer</span> <span m='54380'>for</span> <span m='54750'>drying.</span>\
  \ </p><p><span m='55120'>There</span> <span m='55399'>can,</span> <span m='55678'>of</span>\
  \ <span m='55958'>course,</span> <span m='56237'>be</span> <span m='56516'>delays</span>\
  \ <span m='56796'>between</span> <span m='57075'>the</span> <span m='57355'>steps</span>\
  \ <span m='57634'>of</span> <span m='57913'>loading</span> <span m='58193'>the</span>\
  \ <span m='58472'>washer,</span> <span m='58751'>or</span> <span m='59031'>moving</span>\
  \ <span m='59310'>wet,</span> <span m='59590'>washed</span> <span m='59946'>loads</span>\
  \ <span m='60302'>to</span> <span m='60659'>the</span> <span m='61015'>dryer,</span>\
  \ <span m='61372'>or</span> <span m='61728'>in</span> <span m='62085'>taking</span>\
  \ <span m='62441'>dried</span> <span m='62797'>loads</span> <span m='63154'>out</span>\
  \ <span m='63510'>of</span> <span m='63867'>the</span> <span m='64223'>dryer.</span>\
  \ </p><p><span m='64580'>Let's</span> <span m='64846'>assume</span> <span m='65112'>we</span>\
  \ <span m='65378'>move</span> <span m='65645'>the</span> <span m='65911'>laundry</span>\
  \ <span m='66177'>through</span> <span m='66443'>the</span> <span m='66710'>system</span>\
  \ <span m='66976'>as</span> <span m='67242'>fast</span> <span m='67508'>as</span>\
  \ <span m='67775'>possible,</span> <span m='68041'>moving</span> <span m='68307'>loads</span>\
  \ <span m='68573'>to</span> <span m='68840'>the</span> <span m='69275'>next</span>\
  \ <span m='69711'>processing</span> <span m='70146'>step</span> <span m='70582'>as</span>\
  \ <span m='71017'>soon</span> <span m='71453'>as</span> <span m='71888'>we</span>\
  \ <span m='72324'>can.</span> </p><p><span m='72760'>Most</span> <span m='73120'>of</span>\
  \ <span m='73481'>us</span> <span m='73842'>wait</span> <span m='74203'>to</span>\
  \ <span m='74564'>do</span> <span m='74925'>laundry</span> <span m='75285'>until</span>\
  \ <span m='75646'>we've</span> <span m='76007'>accumulated</span> <span m='76368'>several</span>\
  \ <span m='76729'>loads.</span> </p><p><span m='77090'>That</span> <span m='77333'>turns</span>\
  \ <span m='77577'>out</span> <span m='77820'>to</span> <span m='78064'>be</span>\
  \ <span m='78308'>a</span> <span m='78551'>good</span> <span m='78795'>strategy!</span>\
  \ </p><p><span m='79039'>Let's</span> <span m='79616'>see</span> <span m='80193'>why\u2026\
  </span> <span m='80770'>To</span> <span m='81049'>process</span> <span m='81328'>a</span>\
  \ <span m='81608'>single</span> <span m='81887'>load</span> <span m='82167'>of</span>\
  \ <span m='82446'>laundry,</span> <span m='82725'>we</span> <span m='83005'>first</span>\
  \ <span m='83284'>run</span> <span m='83564'>it</span> <span m='83843'>through</span>\
  \ <span m='84122'>the</span> <span m='84402'>washer,</span> <span m='84681'>which</span>\
  \ <span m='84961'>takes</span> <span m='85240'>30</span> <span m='85520'>minutes.</span>\
  \ </p><p><span m='86520'>Then</span> <span m='86781'>we</span> <span m='87043'>run</span>\
  \ <span m='87305'>it</span> <span m='87567'>through</span> <span m='87829'>the</span>\
  \ <span m='88090'>dryer,</span> <span m='88352'>which</span> <span m='88614'>takes</span>\
  \ <span m='88876'>60</span> <span m='89138'>minutes.</span> </p><p><span m='89400'>So</span>\
  \ <span m='89744'>the</span> <span m='90088'>total</span> <span m='90432'>amount</span>\
  \ <span m='90776'>of</span> <span m='91120'>time</span> <span m='91464'>from</span>\
  \ <span m='91808'>system</span> <span m='92152'>input</span> <span m='92496'>to</span>\
  \ <span m='92840'>system</span> <span m='93184'>output</span> <span m='93528'>is</span>\
  \ <span m='93872'>90</span> <span m='94216'>minutes.</span> </p><p><span m='94560'>If</span>\
  \ <span m='94866'>this</span> <span m='95172'>were</span> <span m='95479'>a</span>\
  \ <span m='95785'>combinational</span> <span m='96092'>logic</span> <span m='96398'>circuit,</span>\
  \ <span m='96705'>we'd</span> <span m='97011'>say</span> <span m='97317'>the</span>\
  \ <span m='97624'>circuit's</span> <span m='97930'>propagation</span> <span m='98237'>delay</span>\
  \ <span m='98543'>is</span> <span m='98850'>90</span> <span m='99341'>minutes</span>\
  \ <span m='99832'>from</span> <span m='100323'>valid</span> <span m='100815'>inputs</span>\
  \ <span m='101306'>to</span> <span m='101797'>valid</span> <span m='102288'>outputs.</span>\
  \ </p><p><span m='102780'>Okay,</span> <span m='103136'>that's</span> <span m='103492'>the</span>\
  \ <span m='103849'>performance</span> <span m='104205'>analysis</span> <span m='104561'>for</span>\
  \ <span m='104918'>a</span> <span m='105274'>single</span> <span m='105630'>load</span>\
  \ <span m='105987'>of</span> <span m='106343'>laundry.</span> </p><p><span m='106700'>Now</span>\
  \ <span m='107150'>let's</span> <span m='107600'>think</span> <span m='108050'>about</span>\
  \ <span m='108500'>doing</span> <span m='108950'>N</span> <span m='109400'>loads</span>\
  \ <span m='109850'>of</span> <span m='110300'>laundry.</span> </p><p><span m='110750'>Here</span>\
  \ <span m='111021'>at</span> <span m='111293'>MIT</span> <span m='111565'>we</span>\
  \ <span m='111837'>like</span> <span m='112109'>to</span> <span m='112381'>make</span>\
  \ <span m='112653'>gentle</span> <span m='112925'>fun</span> <span m='113196'>of</span>\
  \ <span m='113468'>our</span> <span m='113740'>colleagues</span> <span m='114012'>at</span>\
  \ <span m='114284'>the</span> <span m='114556'>prestigious</span> <span m='114828'>institution</span>\
  \ <span m='115100'>just</span> <span m='115441'>up</span> <span m='115783'>the</span>\
  \ <span m='116125'>river</span> <span m='116466'>from</span> <span m='116808'>us.</span>\
  \ </p><p><span m='117150'>So</span> <span m='117479'>here's</span> <span m='117809'>how</span>\
  \ <span m='118139'>we</span> <span m='118469'>imagine</span> <span m='118799'>they</span>\
  \ <span m='119129'>do</span> <span m='119459'>N</span> <span m='119789'>loads</span>\
  \ <span m='120119'>of</span> <span m='120449'>laundry</span> <span m='120779'>at</span>\
  \ <span m='121109'>Harvard.</span> </p><p><span m='121439'>They</span> <span m='121774'>follow</span>\
  \ <span m='122110'>the</span> <span m='122446'>combinational</span> <span m='122782'>recipe</span>\
  \ <span m='123117'>of</span> <span m='123453'>supplying</span> <span m='123789'>new</span>\
  \ <span m='124125'>system</span> <span m='124461'>inputs</span> <span m='124796'>after</span>\
  \ <span m='125132'>the</span> <span m='125468'>system</span> <span m='125804'>generates</span>\
  \ <span m='126140'>the</span> <span m='126523'>correct</span> <span m='126906'>output</span>\
  \ <span m='127290'>from</span> <span m='127673'>the</span> <span m='128056'>previous</span>\
  \ <span m='128440'>set</span> <span m='128823'>of</span> <span m='129206'>inputs.</span>\
  \ </p><p><span m='129590'>So</span> <span m='129874'>in</span> <span m='130159'>step</span>\
  \ <span m='130444'>1</span> <span m='130728'>the</span> <span m='131013'>first</span>\
  \ <span m='131298'>load</span> <span m='131583'>is</span> <span m='131867'>washed</span>\
  \ <span m='132152'>and</span> <span m='132437'>in</span> <span m='132722'>step</span>\
  \ <span m='133006'>2,</span> <span m='133291'>the</span> <span m='133576'>first</span>\
  \ <span m='133861'>load</span> <span m='134145'>is</span> <span m='134430'>dried,</span>\
  \ <span m='134715'>taking</span> <span m='135000'>a</span> <span m='135456'>total</span>\
  \ <span m='135912'>of</span> <span m='136368'>90</span> <span m='136824'>minutes.</span>\
  \ </p><p><span m='137280'>Once</span> <span m='137599'>those</span> <span m='137918'>steps</span>\
  \ <span m='138237'>complete,</span> <span m='138557'>Harvard</span> <span m='138876'>students</span>\
  \ <span m='139195'>move</span> <span m='139515'>on</span> <span m='139834'>to</span>\
  \ <span m='140153'>step</span> <span m='140472'>3,</span> <span m='140792'>starting</span>\
  \ <span m='141111'>the</span> <span m='141430'>processing</span> <span m='141750'>of</span>\
  \ <span m='141981'>the</span> <span m='142213'>second</span> <span m='142445'>load</span>\
  \ <span m='142676'>of</span> <span m='142908'>laundry.</span> </p><p><span m='143140'>And</span>\
  \ <span m='143690'>so</span> <span m='144240'>on\u2026</span> <span m='144790'>The</span>\
  \ <span m='145047'>total</span> <span m='145304'>time</span> <span m='145561'>for</span>\
  \ <span m='145818'>the</span> <span m='146076'>system</span> <span m='146333'>to</span>\
  \ <span m='146590'>process</span> <span m='146847'>N</span> <span m='147105'>laundry</span>\
  \ <span m='147362'>loads</span> <span m='147619'>is</span> <span m='147876'>just</span>\
  \ <span m='148133'>N</span> <span m='148391'>times</span> <span m='148648'>the</span>\
  \ <span m='148905'>time</span> <span m='149162'>it</span> <span m='149420'>takes</span>\
  \ <span m='149831'>to</span> <span m='150243'>process</span> <span m='150655'>a</span>\
  \ <span m='151066'>single</span> <span m='151478'>load.</span> </p><p><span m='151890'>So</span>\
  \ <span m='152311'>the</span> <span m='152732'>total</span> <span m='153154'>time</span>\
  \ <span m='153575'>is</span> <span m='153997'>N*90</span> <span m='154418'>minutes.</span>\
  \ </p><p><span m='154840'>Of</span> <span m='155325'>course,</span> <span m='155810'>we're</span>\
  \ <span m='156295'>being</span> <span m='156780'>silly</span> <span m='157265'>here!</span>\
  \ </p><p><span m='157750'>Harvard</span> <span m='158195'>students</span> <span\
  \ m='158640'>don't</span> <span m='159085'>actually</span> <span m='159530'>do</span>\
  \ <span m='159975'>laundry.</span> </p><p><span m='160420'>Mummy</span> <span m='160702'>sends</span>\
  \ <span m='160985'>the</span> <span m='161267'>family</span> <span m='161550'>butler</span>\
  \ <span m='161832'>over</span> <span m='162115'>on</span> <span m='162397'>Wednesday</span>\
  \ <span m='162680'>mornings</span> <span m='162962'>to</span> <span m='163245'>collect</span>\
  \ <span m='163527'>the</span> <span m='163810'>dirty</span> <span m='164092'>loads</span>\
  \ <span m='164375'>and</span> <span m='164657'>return</span> <span m='164940'>them</span>\
  \ <span m='165475'>starched</span> <span m='166011'>and</span> <span m='166546'>pressed</span>\
  \ <span m='167082'>in</span> <span m='167617'>time</span> <span m='168153'>for</span>\
  \ <span m='168688'>afternoon</span> <span m='169224'>tea.</span> </p><p><span m='169760'>But</span>\
  \ <span m='170008'>I</span> <span m='170256'>hope</span> <span m='170504'>you're</span>\
  \ <span m='170752'>seeing</span> <span m='171000'>the</span> <span m='171248'>analogy</span>\
  \ <span m='171496'>we're</span> <span m='171744'>making</span> <span m='171992'>between</span>\
  \ <span m='172240'>the</span> <span m='172488'>Harvard</span> <span m='172736'>approach</span>\
  \ <span m='172984'>to</span> <span m='173232'>laundry</span> <span m='173480'>and</span>\
  \ <span m='174166'>combinational</span> <span m='174853'>circuits.</span> </p><p><span\
  \ m='175540'>We</span> <span m='175821'>can</span> <span m='176103'>all</span> <span\
  \ m='176385'>see</span> <span m='176666'>that</span> <span m='176948'>the</span>\
  \ <span m='177230'>washer</span> <span m='177511'>is</span> <span m='177793'>sitting</span>\
  \ <span m='178075'>idle</span> <span m='178356'>while</span> <span m='178638'>the</span>\
  \ <span m='178920'>dryer</span> <span m='179201'>is</span> <span m='179483'>running</span>\
  \ <span m='179765'>and</span> <span m='180046'>that</span> <span m='180328'>inefficiency</span>\
  \ <span m='180610'>has</span> <span m='180915'>a</span> <span m='181220'>cost</span>\
  \ <span m='181525'>in</span> <span m='181831'>terms</span> <span m='182136'>of</span>\
  \ <span m='182441'>the</span> <span m='182746'>rate</span> <span m='183052'>at</span>\
  \ <span m='183357'>which</span> <span m='183662'>N</span> <span m='183967'>load</span>\
  \ <span m='184273'>of</span> <span m='184578'>laundry</span> <span m='184883'>can</span>\
  \ <span m='185188'>move</span> <span m='185494'>through</span> <span m='185799'>the</span>\
  \ <span m='186104'>system.</span> </p><p><span m='186410'>As</span> <span m='186768'>engineering</span>\
  \ <span m='187126'>students</span> <span m='187484'>here</span> <span m='187842'>in</span>\
  \ <span m='188200'>6.004,</span> <span m='188558'>we</span> <span m='188916'>see</span>\
  \ <span m='189274'>that</span> <span m='189632'>it</span> <span m='189990'>makes</span>\
  \ <span m='190348'>sense</span> <span m='190706'>to</span> <span m='191064'>overlap</span>\
  \ <span m='191422'>washing</span> <span m='191780'>and</span> <span m='192440'>drying.</span>\
  \ </p><p><span m='193100'>So</span> <span m='193388'>in</span> <span m='193677'>step</span>\
  \ <span m='193966'>1</span> <span m='194255'>we</span> <span m='194544'>wash</span>\
  \ <span m='194833'>the</span> <span m='195122'>first</span> <span m='195411'>load.</span>\
  \ </p><p><span m='195700'>And</span> <span m='195986'>in</span> <span m='196273'>step</span>\
  \ <span m='196560'>2,</span> <span m='196847'>we</span> <span m='197134'>dry</span>\
  \ <span m='197421'>the</span> <span m='197707'>first</span> <span m='197994'>load</span>\
  \ <span m='198281'>as</span> <span m='198568'>before,</span> <span m='198855'>but,</span>\
  \ <span m='199142'>in</span> <span m='199428'>addition,</span> <span m='199715'>we</span>\
  \ <span m='200002'>start</span> <span m='200289'>washing</span> <span m='200576'>the</span>\
  \ <span m='200863'>second</span> <span m='201150'>load</span> <span m='201606'>of</span>\
  \ <span m='202063'>laundry.</span> </p><p><span m='202520'>We</span> <span m='202828'>have</span>\
  \ <span m='203137'>to</span> <span m='203446'>allocate</span> <span m='203755'>60</span>\
  \ <span m='204064'>minutes</span> <span m='204373'>for</span> <span m='204681'>step</span>\
  \ <span m='204990'>2</span> <span m='205299'>in</span> <span m='205608'>order</span>\
  \ <span m='205917'>to</span> <span m='206226'>give</span> <span m='206534'>the</span>\
  \ <span m='206843'>dryer</span> <span m='207152'>time</span> <span m='207461'>to</span>\
  \ <span m='207770'>finish.</span> </p><p><span m='208079'>There's</span> <span m='208371'>a</span>\
  \ <span m='208663'>slight</span> <span m='208955'>inefficiency</span> <span m='209247'>in</span>\
  \ <span m='209539'>that</span> <span m='209831'>the</span> <span m='210123'>washer</span>\
  \ <span m='210415'>finishes</span> <span m='210707'>its</span> <span m='210999'>work</span>\
  \ <span m='211291'>early,</span> <span m='211583'>but</span> <span m='211875'>with</span>\
  \ <span m='212167'>only</span> <span m='212460'>one</span> <span m='212914'>dryer,</span>\
  \ <span m='213368'>it's</span> <span m='213822'>the</span> <span m='214276'>dryer</span>\
  \ <span m='214731'>that</span> <span m='215185'>determines</span> <span m='215639'>how</span>\
  \ <span m='216093'>quickly</span> <span m='216547'>laundry</span> <span m='217002'>moves</span>\
  \ <span m='217456'>through</span> <span m='217910'>the</span> <span m='218364'>system.</span>\
  \ </p><p><span m='218819'>Systems</span> <span m='219143'>that</span> <span m='219467'>overlap</span>\
  \ <span m='219791'>the</span> <span m='220115'>processing</span> <span m='220439'>of</span>\
  \ <span m='220763'>a</span> <span m='221087'>sequence</span> <span m='221411'>of</span>\
  \ <span m='221735'>inputs</span> <span m='222059'>are</span> <span m='222383'>called</span>\
  \ <span m='222707'>pipelined</span> <span m='223031'>systems</span> <span m='223355'>and</span>\
  \ <span m='223680'>each</span> <span m='224064'>of</span> <span m='224448'>the</span>\
  \ <span m='224832'>processing</span> <span m='225216'>steps</span> <span m='225600'>is</span>\
  \ <span m='225985'>called</span> <span m='226369'>a</span> <span m='226753'>stage</span>\
  \ <span m='227137'>of</span> <span m='227521'>the</span> <span m='227905'>pipeline.</span>\
  \ </p><p><span m='228290'>The</span> <span m='228584'>rate</span> <span m='228878'>at</span>\
  \ <span m='229172'>which</span> <span m='229466'>inputs</span> <span m='229760'>move</span>\
  \ <span m='230054'>through</span> <span m='230348'>the</span> <span m='230642'>pipeline</span>\
  \ <span m='230936'>is</span> <span m='231230'>determined</span> <span m='231524'>by</span>\
  \ <span m='231818'>the</span> <span m='232112'>slowest</span> <span m='232406'>pipeline</span>\
  \ <span m='232700'>stage.</span> </p><p><span m='233709'>Our</span> <span m='234136'>laundry</span>\
  \ <span m='234563'>system</span> <span m='234991'>is</span> <span m='235418'>a</span>\
  \ <span m='235846'>2-stage</span> <span m='236273'>pipeline</span> <span m='236700'>with</span>\
  \ <span m='237128'>a</span> <span m='237555'>60-minute</span> <span m='237983'>processing</span>\
  \ <span m='238410'>time</span> <span m='238837'>for</span> <span m='239265'>each</span>\
  \ <span m='239692'>stage.</span> </p><p><span m='240120'>We</span> <span m='240519'>repeat</span>\
  \ <span m='240918'>the</span> <span m='241318'>overlapped</span> <span m='241717'>wash/dry</span>\
  \ <span m='242116'>step</span> <span m='242516'>until</span> <span m='242915'>all</span>\
  \ <span m='243314'>N</span> <span m='243714'>loads</span> <span m='244113'>of</span>\
  \ <span m='244512'>laundry</span> <span m='244912'>have</span> <span m='245311'>been</span>\
  \ <span m='245710'>processed.</span> </p><p><span m='246110'>We're</span> <span\
  \ m='246360'>starting</span> <span m='246611'>a</span> <span m='246861'>new</span>\
  \ <span m='247112'>washer</span> <span m='247362'>load</span> <span m='247613'>every</span>\
  \ <span m='247864'>60</span> <span m='248114'>minutes</span> <span m='248365'>and</span>\
  \ <span m='248615'>getting</span> <span m='248866'>a</span> <span m='249117'>new</span>\
  \ <span m='249367'>load</span> <span m='249618'>of</span> <span m='249868'>dried</span>\
  \ <span m='250119'>laundry</span> <span m='250370'>from</span> <span m='250741'>the</span>\
  \ <span m='251113'>dryer</span> <span m='251484'>every</span> <span m='251856'>60</span>\
  \ <span m='252227'>minutes.</span> </p><p><span m='252599'>In</span> <span m='252927'>other</span>\
  \ <span m='253256'>words,</span> <span m='253585'>the</span> <span m='253913'>effective</span>\
  \ <span m='254242'>processing</span> <span m='254571'>rate</span> <span m='254899'>of</span>\
  \ <span m='255228'>our</span> <span m='255557'>overlapped</span> <span m='255885'>laundry</span>\
  \ <span m='256214'>system</span> <span m='256543'>is</span> <span m='256871'>one</span>\
  \ <span m='257200'>load</span> <span m='257529'>every</span> <span m='258192'>60</span>\
  \ <span m='258855'>minutes.</span> </p><p><span m='259519'>So</span> <span m='259941'>once</span>\
  \ <span m='260363'>the</span> <span m='260786'>process</span> <span m='261208'>is</span>\
  \ <span m='261630'>underway</span> <span m='262053'>N</span> <span m='262475'>loads</span>\
  \ <span m='262898'>of</span> <span m='263320'>laundry</span> <span m='263742'>takes</span>\
  \ <span m='264165'>N*60</span> <span m='264587'>minutes.</span> </p><p><span m='265010'>And</span>\
  \ <span m='265437'>a</span> <span m='265865'>particular</span> <span m='266292'>load</span>\
  \ <span m='266720'>of</span> <span m='267147'>laundry,</span> <span m='267575'>which</span>\
  \ <span m='268002'>requires</span> <span m='268430'>two</span> <span m='268857'>stages</span>\
  \ <span m='269285'>of</span> <span m='269712'>processing</span> <span m='270140'>time,</span>\
  \ <span m='270567'>takes</span> <span m='270995'>120</span> <span m='271422'>minutes.</span>\
  \ </p><p><span m='271850'>The</span> <span m='272077'>timing</span> <span m='272305'>for</span>\
  \ <span m='272532'>the</span> <span m='272760'>first</span> <span m='272988'>load</span>\
  \ <span m='273215'>of</span> <span m='273443'>laundry</span> <span m='273671'>is</span>\
  \ <span m='273898'>a</span> <span m='274126'>little</span> <span m='274354'>different</span>\
  \ <span m='274581'>since</span> <span m='274809'>the</span> <span m='275037'>timing</span>\
  \ <span m='275264'>of</span> <span m='275492'>Step</span> <span m='275720'>1</span>\
  \ <span m='276028'>can</span> <span m='276336'>be</span> <span m='276644'>shorter</span>\
  \ <span m='276952'>with</span> <span m='277260'>no</span> <span m='277568'>dryer</span>\
  \ <span m='277876'>to</span> <span m='278184'>wait</span> <span m='278492'>for.</span>\
  \ </p><p><span m='278800'>But</span> <span m='279133'>in</span> <span m='279467'>the</span>\
  \ <span m='279800'>performance</span> <span m='280134'>analysis</span> <span m='280467'>of</span>\
  \ <span m='280801'>pipelined</span> <span m='281135'>systems,</span> <span m='281468'>we're</span>\
  \ <span m='281802'>interested</span> <span m='282135'>in</span> <span m='282469'>the</span>\
  \ <span m='282802'>steady</span> <span m='283136'>state</span> <span m='283470'>where</span>\
  \ <span m='283819'>we're</span> <span m='284168'>assuming</span> <span m='284517'>that</span>\
  \ <span m='284866'>we</span> <span m='285215'>have</span> <span m='285564'>an</span>\
  \ <span m='285913'>infinite</span> <span m='286262'>supply</span> <span m='286611'>of</span>\
  \ <span m='286960'>inputs.</span> </p><p><span m='287310'>We</span> <span m='287706'>see</span>\
  \ <span m='288103'>that</span> <span m='288500'>there</span> <span m='288896'>are</span>\
  \ <span m='289293'>two</span> <span m='289690'>interesting</span> <span m='290086'>performance</span>\
  \ <span m='290483'>metrics.</span> </p><p><span m='290880'>The</span> <span m='291115'>first</span>\
  \ <span m='291351'>is</span> <span m='291586'>the</span> <span m='291822'>latency</span>\
  \ <span m='292057'>of</span> <span m='292293'>the</span> <span m='292528'>system,</span>\
  \ <span m='292764'>the</span> <span m='293000'>time</span> <span m='293235'>it</span>\
  \ <span m='293471'>takes</span> <span m='293706'>for</span> <span m='293942'>the</span>\
  \ <span m='294177'>system</span> <span m='294413'>to</span> <span m='294648'>process</span>\
  \ <span m='294884'>a</span> <span m='295120'>particular</span> <span m='295795'>input.</span>\
  \ </p><p><span m='296470'>In</span> <span m='296811'>the</span> <span m='297152'>Harvard</span>\
  \ <span m='297494'>laundry</span> <span m='297835'>system,</span> <span m='298176'>it</span>\
  \ <span m='298518'>takes</span> <span m='298859'>90</span> <span m='299200'>minutes</span>\
  \ <span m='299542'>to</span> <span m='299883'>wash</span> <span m='300224'>and</span>\
  \ <span m='300566'>dry</span> <span m='300907'>a</span> <span m='301248'>load.</span>\
  \ </p><p><span m='301590'>In</span> <span m='301908'>the</span> <span m='302226'>6.004</span>\
  \ <span m='302544'>laundry,</span> <span m='302862'>it</span> <span m='303181'>takes</span>\
  \ <span m='303499'>120</span> <span m='303817'>minutes</span> <span m='304135'>to</span>\
  \ <span m='304454'>wash</span> <span m='304772'>and</span> <span m='305090'>dry</span>\
  \ <span m='305408'>a</span> <span m='305727'>load,</span> <span m='306045'>assuming</span>\
  \ <span m='306363'>that</span> <span m='306681'>it's</span> <span m='307000'>not</span>\
  \ <span m='307470'>the</span> <span m='307940'>first</span> <span m='308410'>load.</span>\
  \ </p><p><span m='308880'>The</span> <span m='309268'>second</span> <span m='309657'>performance</span>\
  \ <span m='310045'>measure</span> <span m='310434'>is</span> <span m='310822'>throughput,</span>\
  \ <span m='311211'>the</span> <span m='311600'>rate</span> <span m='311988'>at</span>\
  \ <span m='312377'>which</span> <span m='312765'>the</span> <span m='313154'>system</span>\
  \ <span m='313542'>produces</span> <span m='313931'>outputs.</span> </p><p><span\
  \ m='314320'>In</span> <span m='314582'>many</span> <span m='314845'>systems,</span>\
  \ <span m='315108'>we</span> <span m='315371'>get</span> <span m='315633'>one</span>\
  \ <span m='315896'>set</span> <span m='316159'>of</span> <span m='316422'>outputs</span>\
  \ <span m='316685'>for</span> <span m='316947'>each</span> <span m='317210'>set</span>\
  \ <span m='317473'>of</span> <span m='317736'>inputs,</span> <span m='317998'>and</span>\
  \ <span m='318261'>in</span> <span m='318524'>such</span> <span m='318787'>systems,</span>\
  \ <span m='319050'>the</span> <span m='319453'>throughput</span> <span m='319857'>also</span>\
  \ <span m='320260'>tells</span> <span m='320664'>us</span> <span m='321068'>the</span>\
  \ <span m='321471'>rate</span> <span m='321875'>at</span> <span m='322279'>inputs</span>\
  \ <span m='322682'>are</span> <span m='323086'>consumed.</span> </p><p><span m='323490'>In</span>\
  \ <span m='323836'>the</span> <span m='324182'>Harvard</span> <span m='324528'>laundry</span>\
  \ <span m='324874'>system,</span> <span m='325220'>the</span> <span m='325566'>throughput</span>\
  \ <span m='325912'>is</span> <span m='326258'>1</span> <span m='326604'>load</span>\
  \ <span m='326950'>of</span> <span m='327296'>laundry</span> <span m='327642'>every</span>\
  \ <span m='327988'>90</span> <span m='328334'>minutes.</span> </p><p><span m='328680'>In</span>\
  \ <span m='329137'>the</span> <span m='329595'>6.004</span> <span m='330053'>laundry,</span>\
  \ <span m='330511'>the</span> <span m='330969'>throughput</span> <span m='331427'>is</span>\
  \ <span m='331885'>1</span> <span m='332342'>load</span> <span m='332800'>of</span>\
  \ <span m='333258'>laundry</span> <span m='333716'>every</span> <span m='334174'>60</span>\
  \ <span m='334632'>minutes.</span> </p><p><span m='335090'>The</span> <span m='335562'>Harvard</span>\
  \ <span m='336035'>laundry</span> <span m='336507'>has</span> <span m='336980'>lower</span>\
  \ <span m='337452'>latency,</span> <span m='337925'>the</span> <span m='338397'>6.004</span>\
  \ <span m='338870'>laundry</span> <span m='339342'>has</span> <span m='339815'>better</span>\
  \ <span m='340287'>throughput.</span> </p><p><span m='340760'>Which</span> <span\
  \ m='341244'>is</span> <span m='341728'>the</span> <span m='342212'>better</span>\
  \ <span m='342696'>system?</span> </p><p><span m='343180'>That</span> <span m='343586'>depends</span>\
  \ <span m='343992'>on</span> <span m='344398'>your</span> <span m='344804'>goals!</span>\
  \ </p><p><span m='345210'>If</span> <span m='345514'>you</span> <span m='345819'>need</span>\
  \ <span m='346123'>to</span> <span m='346428'>wash</span> <span m='346733'>100</span>\
  \ <span m='347037'>loads</span> <span m='347342'>of</span> <span m='347647'>laundry,</span>\
  \ <span m='347951'>you'd</span> <span m='348256'>prefer</span> <span m='348561'>to</span>\
  \ <span m='348865'>use</span> <span m='349170'>the</span> <span m='349475'>system</span>\
  \ <span m='349779'>with</span> <span m='350084'>higher</span> <span m='350389'>throughput.</span>\
  \ </p><p><span m='351389'>If,</span> <span m='351661'>on</span> <span m='351934'>the</span>\
  \ <span m='352207'>other</span> <span m='352480'>hand,</span> <span m='352753'>you</span>\
  \ <span m='353026'>want</span> <span m='353298'>clean</span> <span m='353571'>underwear</span>\
  \ <span m='353844'>for</span> <span m='354117'>your</span> <span m='354390'>date</span>\
  \ <span m='354663'>in</span> <span m='354935'>90</span> <span m='355208'>minutes,</span>\
  \ <span m='355481'>you're</span> <span m='355754'>much</span> <span m='356027'>more</span>\
  \ <span m='356300'>concerned</span> <span m='357080'>about</span> <span m='357860'>the</span>\
  \ <span m='358640'>latency.</span> </p><p><span m='359420'>The</span> <span m='359855'>laundry</span>\
  \ <span m='360290'>example</span> <span m='360725'>also</span> <span m='361160'>illustrates</span>\
  \ <span m='361595'>a</span> <span m='362030'>common</span> <span m='362465'>tradeoff</span>\
  \ <span m='362900'>between</span> <span m='363335'>latency</span> <span m='363770'>and</span>\
  \ <span m='364205'>throughput.</span> </p><p><span m='364640'>If</span> <span m='365052'>we</span>\
  \ <span m='365465'>increase</span> <span m='365877'>throughput</span> <span m='366290'>by</span>\
  \ <span m='366702'>using</span> <span m='367115'>pipelined</span> <span m='367527'>processing,</span>\
  \ <span m='367940'>the</span> <span m='368352'>latency</span> <span m='368765'>usually</span>\
  \ <span m='369177'>increases</span> <span m='369590'>since</span> <span m='369910'>all</span>\
  \ <span m='370231'>pipeline</span> <span m='370552'>stages</span> <span m='370872'>must</span>\
  \ <span m='371193'>operate</span> <span m='371514'>in</span> <span m='371834'>lock-step</span>\
  \ <span m='372155'>and</span> <span m='372476'>the</span> <span m='372796'>rate</span>\
  \ <span m='373117'>of</span> <span m='373438'>processing</span> <span m='373758'>is</span>\
  \ <span m='374079'>thus</span> <span m='374400'>determined</span> <span m='374756'>by</span>\
  \ <span m='375112'>the</span> <span m='375468'>slowest</span> <span m='375824'>stage.</span>\
  \ </p>"
type: course
uid: 638fbd1751857f9367adb6c3256b4bea

---
None