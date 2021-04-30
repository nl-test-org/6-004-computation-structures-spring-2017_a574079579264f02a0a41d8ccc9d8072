---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: r3c31nh_iOc
  parent_uid: b09860eabfa0ea570a854a02bb3b9b27
  title: Video-YouTube-Stream
  type: Video
  uid: ef2c58f3e42f12f37f310ffda8f0e6bf
- id: 3Play-3Play YouTube id-Stream
  media_location: r3c31nh_iOc
  parent_uid: b09860eabfa0ea570a854a02bb3b9b27
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 6327768c6f2eef6b10415f8f6b72d1d8
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/r3c31nh_iOc/default.jpg
  parent_uid: b09860eabfa0ea570a854a02bb3b9b27
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 5295827b71ce19604adcdcc5fe57cee4
- id: r3c31nh_iOc.srt
  parent_uid: b09860eabfa0ea570a854a02bb3b9b27
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c8/c8s2/c8s2v5/multiplier-tradeoffs-5-13-/r3c31nh_iOc.srt
  title: 3play caption file
  type: null
  uid: aae3fed01668f5406a2b62ed106318de
- id: r3c31nh_iOc.pdf
  parent_uid: b09860eabfa0ea570a854a02bb3b9b27
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c8/c8s2/c8s2v5/multiplier-tradeoffs-5-13-/r3c31nh_iOc.pdf
  title: 3play pdf file
  type: null
  uid: 4cf948a20451dc4d1373a47334a06e83
- id: Caption-3Play YouTube id-SRT
  parent_uid: b09860eabfa0ea570a854a02bb3b9b27
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: db12ae6c1f91122d9c1e62355bc925cb
- id: Transcript-3Play YouTube id-PDF
  parent_uid: b09860eabfa0ea570a854a02bb3b9b27
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: d8aa46ff861604a8adc5a68e7b5a8258
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_08-02-05_300k.mp4
  parent_uid: b09860eabfa0ea570a854a02bb3b9b27
  title: Video-Internet Archive-MP4
  type: Video
  uid: 86e1e5b028907b47cffc73b23609bd5a
inline_embed_id: 64393815multipliertradeoffs51387285119
layout: video
order_index: null
parent_uid: 21c7889fb56b995f90e5564285eb8975
related_resources_text: ''
short_url: multiplier-tradeoffs-5-13-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c8/c8s2/c8s2v5/multiplier-tradeoffs-5-13-
template_type: Embed
title: Multiplier Tradeoffs (5:13)
transcript: <p><span m='719'>Let's</span> <span m='1079'>see</span> <span m='1439'>if</span>
  <span m='1799'>we</span> <span m='2159'>can</span> <span m='2519'>improve</span>
  <span m='2879'>the</span> <span m='3239'>throughput</span> <span m='3599'>of</span>
  <span m='3959'>the</span> <span m='4319'>original</span> <span m='4679'>combinational</span>
  <span m='5039'>multiplier</span> <span m='5399'>design.</span> </p><p><span m='5759'>We'll</span>
  <span m='6094'>use</span> <span m='6429'>our</span> <span m='6765'>patented</span>
  <span m='7100'>pipelining</span> <span m='7436'>process</span> <span m='7771'>to</span>
  <span m='8107'>divide</span> <span m='8442'>the</span> <span m='8778'>processing</span>
  <span m='9113'>into</span> <span m='9449'>stages</span> <span m='9784'>with</span>
  <span m='10120'>the</span> <span m='10619'>expectation</span> <span m='11118'>of</span>
  <span m='11617'>achieving</span> <span m='12116'>a</span> <span m='12615'>smaller</span>
  <span m='13114'>clock</span> <span m='13613'>period</span> <span m='14112'>and</span>
  <span m='14611'>higher</span> <span m='15110'>throughput.</span> </p><p><span m='15610'>The</span>
  <span m='15918'>number</span> <span m='16226'>to</span> <span m='16534'>beat</span>
  <span m='16843'>is</span> <span m='17151'>approximately</span> <span m='17459'>1</span>
  <span m='17767'>output</span> <span m='18076'>every</span> <span m='18384'>2N,</span>
  <span m='18692'>where</span> <span m='19001'>N</span> <span m='19309'>is</span>
  <span m='19617'>the</span> <span m='19925'>number</span> <span m='20234'>of</span>
  <span m='20542'>bits</span> <span m='20850'>in</span> <span m='21159'>each</span>
  <span m='21866'>of</span> <span m='22574'>the</span> <span m='23281'>operands.</span>
  </p><p><span m='23989'>Our</span> <span m='24330'>first</span> <span m='24672'>step</span>
  <span m='25014'>is</span> <span m='25355'>to</span> <span m='25697'>draw</span>
  <span m='26039'>a</span> <span m='26380'>contour</span> <span m='26722'>across</span>
  <span m='27064'>all</span> <span m='27405'>the</span> <span m='27747'>outputs.</span>
  </p><p><span m='28089'>This</span> <span m='28505'>creates</span> <span m='28921'>a</span>
  <span m='29337'>1-pipeline,</span> <span m='29753'>which</span> <span m='30170'>gets</span>
  <span m='30586'>us</span> <span m='31002'>started</span> <span m='31418'>but</span>
  <span m='31835'>doesn't</span> <span m='32251'>improve</span> <span m='32667'>the</span>
  <span m='33083'>throughput.</span> </p><p><span m='33500'>Let's</span> <span m='33885'>add</span>
  <span m='34270'>another</span> <span m='34655'>contour,</span> <span m='35040'>dividing</span>
  <span m='35425'>the</span> <span m='35810'>computations</span> <span m='36195'>about</span>
  <span m='36580'>in</span> <span m='36965'>half.</span> </p><p><span m='37350'>If</span>
  <span m='37633'>we're</span> <span m='37916'>on</span> <span m='38200'>the</span>
  <span m='38483'>right</span> <span m='38766'>track,</span> <span m='39050'>we</span>
  <span m='39333'>hope</span> <span m='39616'>to</span> <span m='39900'>see</span>
  <span m='40183'>some</span> <span m='40466'>improvement</span> <span m='40750'>in</span>
  <span m='41033'>the</span> <span m='41316'>throughput.</span> </p><p><span m='41600'>And</span>
  <span m='41968'>indeed</span> <span m='42337'>we</span> <span m='42706'>do:</span>
  <span m='43075'>the</span> <span m='43443'>throughput</span> <span m='43812'>has</span>
  <span m='44181'>doubled.</span> </p><p><span m='44550'>Yet</span> <span m='44960'>both</span>
  <span m='45370'>the</span> <span m='45780'>before</span> <span m='46190'>and</span>
  <span m='46600'>after</span> <span m='47010'>throughputs</span> <span m='47420'>are</span>
  <span m='47830'>order</span> <span m='48240'>1/N.</span> </p><p><span m='48650'>Is</span>
  <span m='49068'>there</span> <span m='49487'>any</span> <span m='49906'>hope</span>
  <span m='50325'>of</span> <span m='50744'>a</span> <span m='51163'>dramatically</span>
  <span m='51582'>better</span> <span m='52001'>throughput?</span> </p><p><span m='52420'>The</span>
  <span m='52751'>necessary</span> <span m='53082'>insight</span> <span m='53413'>is</span>
  <span m='53744'>that</span> <span m='54075'>as</span> <span m='54407'>long</span>
  <span m='54738'>as</span> <span m='55069'>an</span> <span m='55400'>entire</span>
  <span m='55731'>row</span> <span m='56062'>is</span> <span m='56394'>inside</span>
  <span m='56725'>a</span> <span m='57056'>single</span> <span m='57387'>pipeline</span>
  <span m='57718'>stage,</span> <span m='58050'>the</span> <span m='58309'>latency</span>
  <span m='58568'>of</span> <span m='58828'>the</span> <span m='59087'>stage</span>
  <span m='59347'>will</span> <span m='59606'>be</span> <span m='59866'>order</span>
  <span m='60125'>N</span> <span m='60385'>since</span> <span m='60644'>we</span>
  <span m='60904'>have</span> <span m='61163'>to</span> <span m='61423'>leave</span>
  <span m='61682'>time</span> <span m='61942'>for</span> <span m='62201'>the</span>
  <span m='62461'>N-bit</span> <span m='62720'>ripple-carry</span> <span m='62980'>add</span>
  <span m='63916'>to</span> <span m='64853'>complete.</span> </p><p><span m='65790'>There</span>
  <span m='66111'>are</span> <span m='66432'>several</span> <span m='66753'>ways</span>
  <span m='67075'>to</span> <span m='67396'>tackle</span> <span m='67717'>this</span>
  <span m='68038'>problem.</span> </p><p><span m='68360'>The</span> <span m='68751'>technique</span>
  <span m='69143'>illustrated</span> <span m='69535'>here</span> <span m='69927'>will</span>
  <span m='70319'>be</span> <span m='70710'>useful</span> <span m='71102'>in</span>
  <span m='71494'>our</span> <span m='71886'>next</span> <span m='72278'>task.</span>
  </p><p><span m='72670'>In</span> <span m='73047'>this</span> <span m='73425'>schematic</span>
  <span m='73802'>we've</span> <span m='74180'>redrawn</span> <span m='74557'>the</span>
  <span m='74935'>carry</span> <span m='75312'>chains.</span> </p><p><span m='75690'>Carry-outs</span>
  <span m='75975'>are</span> <span m='76261'>still</span> <span m='76546'>connected</span>
  <span m='76832'>to</span> <span m='77118'>a</span> <span m='77403'>module</span>
  <span m='77689'>one</span> <span m='77975'>column</span> <span m='78260'>to</span>
  <span m='78546'>the</span> <span m='78831'>left,</span> <span m='79117'>but,</span>
  <span m='79403'>in</span> <span m='79688'>this</span> <span m='79974'>case,</span>
  <span m='80260'>a</span> <span m='80646'>module</span> <span m='81033'>that's</span>
  <span m='81420'>down</span> <span m='81806'>a</span> <span m='82193'>row.</span>
  </p><p><span m='82580'>So</span> <span m='82857'>all</span> <span m='83135'>the</span>
  <span m='83412'>additions</span> <span m='83690'>that</span> <span m='83968'>need</span>
  <span m='84245'>to</span> <span m='84523'>happen</span> <span m='84801'>in</span>
  <span m='85078'>a</span> <span m='85356'>specific</span> <span m='85634'>column</span>
  <span m='85911'>still</span> <span m='86189'>happen</span> <span m='86467'>in</span>
  <span m='86744'>that</span> <span m='87022'>column,</span> <span m='87300'>we've</span>
  <span m='87821'>just</span> <span m='88342'>reorganized</span> <span m='88863'>which</span>
  <span m='89385'>row</span> <span m='89906'>does</span> <span m='90427'>the</span>
  <span m='90948'>adding.</span> </p><p><span m='91470'>Let's</span> <span m='91902'>pipeline</span>
  <span m='92334'>this</span> <span m='92767'>revised</span> <span m='93199'>diagram,</span>
  <span m='93631'>creating</span> <span m='94064'>stages</span> <span m='94496'>with</span>
  <span m='94928'>approximately</span> <span m='95361'>two</span> <span m='95793'>module's</span>
  <span m='96225'>worth</span> <span m='96658'>of</span> <span m='97324'>propagation</span>
  <span m='97991'>delay.</span> </p><p><span m='98658'>The</span> <span m='98994'>horizontal</span>
  <span m='99331'>contours</span> <span m='99668'>now</span> <span m='100005'>break</span>
  <span m='100342'>the</span> <span m='100678'>long</span> <span m='101015'>carry</span>
  <span m='101352'>chains</span> <span m='101689'>and</span> <span m='102026'>the</span>
  <span m='102362'>latency</span> <span m='102699'>of</span> <span m='103036'>each</span>
  <span m='103373'>stage</span> <span m='103710'>is</span> <span m='104082'>now</span>
  <span m='104455'>constant,</span> <span m='104827'>independent</span> <span m='105200'>of</span>
  <span m='105572'>N.</span> <span m='105945'>Note</span> <span m='106317'>that</span>
  <span m='106690'>we</span> <span m='107062'>had</span> <span m='107435'>to</span>
  <span m='107807'>add</span> <span m='108180'>order</span> <span m='108552'>N</span>
  <span m='108925'>extra</span> <span m='109297'>rows</span> <span m='109670'>to</span>
  <span m='109923'>take</span> <span m='110177'>of</span> <span m='110431'>the</span>
  <span m='110685'>propagating</span> <span m='110939'>the</span> <span m='111193'>carries</span>
  <span m='111447'>all</span> <span m='111701'>the</span> <span m='111955'>way</span>
  <span m='112208'>to</span> <span m='112462'>the</span> <span m='112716'>end</span>
  <span m='112970'>-</span> <span m='113224'>the</span> <span m='113478'>extra</span>
  <span m='113732'>circuitry</span> <span m='113986'>is</span> <span m='114240'>shown</span>
  <span m='114818'>in</span> <span m='115396'>the</span> <span m='115974'>grey</span>
  <span m='116552'>box.</span> </p><p><span m='117130'>To</span> <span m='117514'>achieve</span>
  <span m='117898'>a</span> <span m='118283'>latency</span> <span m='118667'>that's</span>
  <span m='119051'>independent</span> <span m='119436'>of</span> <span m='119820'>N</span>
  <span m='120205'>in</span> <span m='120589'>each</span> <span m='120973'>stage,</span>
  <span m='121358'>we'll</span> <span m='121742'>need</span> <span m='122126'>order</span>
  <span m='122511'>N</span> <span m='122895'>contours.</span> </p><p><span m='123280'>This</span>
  <span m='123678'>means</span> <span m='124077'>the</span> <span m='124475'>latency</span>
  <span m='124874'>is</span> <span m='125273'>constant,</span> <span m='125671'>which</span>
  <span m='126070'>in</span> <span m='126468'>order-of</span> <span m='126867'>notation</span>
  <span m='127266'>we</span> <span m='127664'>write</span> <span m='128063'>as</span>
  <span m='128461'>"order</span> <span m='128860'>1".</span> </p><p><span m='129259'>But</span>
  <span m='129535'>this</span> <span m='129811'>means</span> <span m='130088'>the</span>
  <span m='130364'>clock</span> <span m='130640'>period</span> <span m='130917'>is</span>
  <span m='131193'>now</span> <span m='131469'>independent</span> <span m='131746'>of</span>
  <span m='132022'>N,</span> <span m='132299'>as</span> <span m='132575'>is</span>
  <span m='132851'>the</span> <span m='133128'>throughput</span> <span m='133404'>-</span>
  <span m='133680'>they</span> <span m='133957'>are</span> <span m='134233'>both</span>
  <span m='134510'>order</span> <span m='135480'>1.</span> </p><p><span m='136450'>With</span>
  <span m='136837'>order</span> <span m='137225'>N</span> <span m='137612'>contours,</span>
  <span m='138000'>there</span> <span m='138388'>are</span> <span m='138775'>order</span>
  <span m='139163'>N</span> <span m='139551'>pipeline</span> <span m='139938'>stages,</span>
  <span m='140326'>so</span> <span m='140714'>the</span> <span m='141101'>system</span>
  <span m='141489'>latency</span> <span m='141877'>is</span> <span m='142264'>order</span>
  <span m='142652'>N.</span> </p><p><span m='143040'>The</span> <span m='143670'>hardware</span>
  <span m='144300'>cost</span> <span m='144930'>is</span> <span m='145560'>still</span>
  <span m='146190'>order</span> <span m='146820'>N^2.</span> </p><p><span m='147450'>So</span>
  <span m='147843'>the</span> <span m='148236'>pipelined</span> <span m='148630'>carry-save</span>
  <span m='149023'>multiplier</span> <span m='149416'>has</span> <span m='149810'>dramatically</span>
  <span m='150203'>better</span> <span m='150596'>throughput</span> <span m='150990'>than</span>
  <span m='151383'>the</span> <span m='151776'>original</span> <span m='152170'>circuit,</span>
  <span m='152644'>another</span> <span m='153118'>design</span> <span m='153592'>tradeoff</span>
  <span m='154066'>we</span> <span m='154540'>can</span> <span m='155014'>remember</span>
  <span m='155488'>for</span> <span m='155962'>future</span> <span m='156436'>use.</span>
  </p><p><span m='156910'>We'll</span> <span m='157250'>use</span> <span m='157591'>the</span>
  <span m='157932'>carry-save</span> <span m='158272'>technique</span> <span m='158613'>in</span>
  <span m='158954'>our</span> <span m='159295'>next</span> <span m='159635'>optimization,</span>
  <span m='159976'>which</span> <span m='160317'>is</span> <span m='160657'>to</span>
  <span m='160998'>implement</span> <span m='161339'>the</span> <span m='161680'>multiplier</span>
  <span m='162300'>using</span> <span m='162920'>only</span> <span m='163540'>order</span>
  <span m='164160'>N</span> <span m='164780'>hardware.</span> </p><p><span m='165400'>This</span>
  <span m='165766'>sequential</span> <span m='166133'>multiplier</span> <span m='166500'>design</span>
  <span m='166867'>computes</span> <span m='167234'>a</span> <span m='167601'>single</span>
  <span m='167968'>partial</span> <span m='168335'>product</span> <span m='168702'>in</span>
  <span m='169069'>each</span> <span m='169436'>step</span> <span m='169803'>and</span>
  <span m='170170'>adds</span> <span m='170611'>it</span> <span m='171053'>to</span>
  <span m='171495'>the</span> <span m='171936'>accumulating</span> <span m='172378'>sum.</span>
  </p><p><span m='172820'>It</span> <span m='173200'>will</span> <span m='173580'>take</span>
  <span m='173960'>order</span> <span m='174340'>N</span> <span m='174720'>steps</span>
  <span m='175100'>to</span> <span m='175480'>perform</span> <span m='175860'>the</span>
  <span m='176240'>complete</span> <span m='176620'>multiplication.</span> </p><p><span
  m='177000'>In</span> <span m='177266'>each</span> <span m='177532'>step,</span>
  <span m='177798'>the</span> <span m='178064'>next</span> <span m='178330'>bit</span>
  <span m='178596'>of</span> <span m='178862'>the</span> <span m='179128'>multiplier,</span>
  <span m='179395'>found</span> <span m='179661'>in</span> <span m='179927'>the</span>
  <span m='180193'>low-order</span> <span m='180459'>bit</span> <span m='180725'>of</span>
  <span m='180991'>the</span> <span m='181257'>B</span> <span m='181523'>register,</span>
  <span m='181790'>is</span> <span m='182210'>ANDed</span> <span m='182630'>with</span>
  <span m='183050'>the</span> <span m='183470'>multiplicand</span> <span m='183890'>to</span>
  <span m='184310'>form</span> <span m='184730'>the</span> <span m='185150'>next</span>
  <span m='185570'>partial</span> <span m='185990'>product.</span> </p><p><span m='186410'>This</span>
  <span m='186659'>is</span> <span m='186908'>sent</span> <span m='187158'>to</span>
  <span m='187407'>the</span> <span m='187657'>N-bit</span> <span m='187906'>carry-save</span>
  <span m='188155'>adder</span> <span m='188405'>to</span> <span m='188654'>be</span>
  <span m='188904'>added</span> <span m='189153'>to</span> <span m='189402'>the</span>
  <span m='189652'>accumulating</span> <span m='189901'>sum</span> <span m='190151'>in</span>
  <span m='190400'>the</span> <span m='190650'>P</span> <span m='191710'>register.</span>
  </p><p><span m='192770'>The</span> <span m='193113'>value</span> <span m='193456'>in</span>
  <span m='193799'>the</span> <span m='194142'>P</span> <span m='194485'>register</span>
  <span m='194828'>and</span> <span m='195171'>the</span> <span m='195515'>output</span>
  <span m='195858'>of</span> <span m='196201'>the</span> <span m='196544'>adder</span>
  <span m='196887'>are</span> <span m='197230'>in</span> <span m='197573'>"carry-save</span>
  <span m='197916'>format".</span> </p><p><span m='198260'>This</span> <span m='198604'>means</span>
  <span m='198949'>there</span> <span m='199294'>are</span> <span m='199638'>32</span>
  <span m='199983'>data</span> <span m='200328'>bits,</span> <span m='200672'>but,</span>
  <span m='201017'>in</span> <span m='201362'>addition,</span> <span m='201707'>31</span>
  <span m='202051'>saved</span> <span m='202396'>carries,</span> <span m='202741'>to</span>
  <span m='203085'>be</span> <span m='203430'>added</span> <span m='203775'>to</span>
  <span m='204120'>the</span> <span m='204509'>appropriate</span> <span m='204899'>column</span>
  <span m='205289'>in</span> <span m='205679'>the</span> <span m='206069'>next</span>
  <span m='206459'>cycle.</span> </p><p><span m='206849'>The</span> <span m='207125'>output</span>
  <span m='207402'>of</span> <span m='207679'>the</span> <span m='207956'>carry-save</span>
  <span m='208233'>adder</span> <span m='208510'>is</span> <span m='208787'>saved</span>
  <span m='209064'>in</span> <span m='209341'>the</span> <span m='209618'>P</span>
  <span m='209895'>register,</span> <span m='210172'>then</span> <span m='210449'>in</span>
  <span m='210726'>preparation</span> <span m='211003'>for</span> <span m='211280'>the</span>
  <span m='211653'>next</span> <span m='212026'>step</span> <span m='212399'>both</span>
  <span m='212772'>P</span> <span m='213145'>and</span> <span m='213518'>B</span>
  <span m='213891'>are</span> <span m='214264'>shifted</span> <span m='214637'>right</span>
  <span m='215010'>by</span> <span m='215383'>1</span> <span m='215756'>bit.</span>
  </p><p><span m='216129'>So</span> <span m='216424'>each</span> <span m='216720'>cycle</span>
  <span m='217015'>one</span> <span m='217311'>bit</span> <span m='217607'>of</span>
  <span m='217902'>the</span> <span m='218198'>accumulated</span> <span m='218493'>sum</span>
  <span m='218789'>is</span> <span m='219085'>retired</span> <span m='219380'>to</span>
  <span m='219676'>the</span> <span m='219971'>B</span> <span m='220267'>register</span>
  <span m='220563'>since</span> <span m='220858'>it</span> <span m='221154'>can</span>
  <span m='221450'>no</span> <span m='221843'>longer</span> <span m='222236'>be</span>
  <span m='222630'>affected</span> <span m='223023'>by</span> <span m='223416'>the</span>
  <span m='223810'>remaining</span> <span m='224203'>partial</span> <span m='224596'>products.</span>
  </p><p><span m='224990'>Think</span> <span m='225297'>of</span> <span m='225605'>it</span>
  <span m='225912'>this</span> <span m='226220'>way:</span> <span m='226527'>instead</span>
  <span m='226835'>of</span> <span m='227142'>shifting</span> <span m='227450'>the</span>
  <span m='227757'>partial</span> <span m='228065'>products</span> <span m='228372'>left</span>
  <span m='228680'>to</span> <span m='228987'>account</span> <span m='229295'>for</span>
  <span m='229602'>the</span> <span m='229910'>weight</span> <span m='230463'>of</span>
  <span m='231016'>the</span> <span m='231570'>current</span> <span m='232123'>multiplier</span>
  <span m='232676'>bit,</span> <span m='233230'>we're</span> <span m='233783'>shifting</span>
  <span m='234336'>the</span> <span m='234890'>accumulated</span> <span m='235443'>sum</span>
  <span m='235996'>right!</span> </p><p><span m='236550'>The</span> <span m='236835'>clock</span>
  <span m='237120'>period</span> <span m='237405'>needed</span> <span m='237690'>for</span>
  <span m='237975'>the</span> <span m='238260'>sequential</span> <span m='238545'>logic</span>
  <span m='238830'>is</span> <span m='239115'>quite</span> <span m='239400'>small,</span>
  <span m='239685'>and,</span> <span m='239970'>more</span> <span m='240255'>importantly</span>
  <span m='240540'>is</span> <span m='241023'>independent</span> <span m='241507'>of</span>
  <span m='241990'>N.</span> <span m='242474'>Since</span> <span m='242958'>there's</span>
  <span m='243441'>no</span> <span m='243925'>carry</span> <span m='244409'>propagation,</span>
  <span m='244892'>the</span> <span m='245376'>latency</span> <span m='245860'>of</span>
  <span m='246245'>the</span> <span m='246631'>carry-save</span> <span m='247017'>adder</span>
  <span m='247403'>is</span> <span m='247789'>very</span> <span m='248175'>small,</span>
  <span m='248561'>i.e.,</span> <span m='248947'>only</span> <span m='249332'>enough</span>
  <span m='249718'>time</span> <span m='250104'>for</span> <span m='250490'>the</span>
  <span m='250876'>operation</span> <span m='251262'>of</span> <span m='251648'>a</span>
  <span m='252034'>single</span> <span m='252420'>full</span> <span m='253306'>adder</span>
  <span m='254193'>module.</span> </p><p><span m='255080'>After</span> <span m='255397'>order</span>
  <span m='255714'>N</span> <span m='256031'>steps,</span> <span m='256349'>we've</span>
  <span m='256666'>generated</span> <span m='256983'>the</span> <span m='257300'>necessary</span>
  <span m='257618'>partial</span> <span m='257935'>products,</span> <span m='258252'>but</span>
  <span m='258569'>will</span> <span m='258887'>need</span> <span m='259204'>to</span>
  <span m='259521'>continue</span> <span m='259839'>for</span> <span m='260269'>another</span>
  <span m='260699'>order</span> <span m='261129'>N</span> <span m='261559'>steps</span>
  <span m='261989'>to</span> <span m='262419'>finish</span> <span m='262849'>propagating</span>
  <span m='263279'>the</span> <span m='263709'>carries</span> <span m='264139'>through</span>
  <span m='264569'>the</span> <span m='264999'>carry-save</span> <span m='265429'>adder.</span>
  </p><p><span m='265860'>But</span> <span m='266201'>even</span> <span m='266542'>at</span>
  <span m='266883'>2N</span> <span m='267225'>steps,</span> <span m='267566'>the</span>
  <span m='267907'>overall</span> <span m='268248'>latency</span> <span m='268590'>of</span>
  <span m='268931'>the</span> <span m='269272'>multiplier</span> <span m='269613'>is</span>
  <span m='269955'>still</span> <span m='270296'>order</span> <span m='270637'>N.</span>
  </p><p><span m='270979'>And</span> <span m='271272'>at</span> <span m='271566'>the</span>
  <span m='271860'>end</span> <span m='272153'>of</span> <span m='272447'>the</span>
  <span m='272741'>2N</span> <span m='273035'>steps,</span> <span m='273328'>we</span>
  <span m='273622'>produce</span> <span m='273916'>the</span> <span m='274210'>answer</span>
  <span m='274503'>in</span> <span m='274797'>the</span> <span m='275091'>P</span>
  <span m='275385'>and</span> <span m='275678'>B</span> <span m='275972'>registers</span>
  <span m='276266'>combined,</span> <span m='276560'>so</span> <span m='276914'>the</span>
  <span m='277269'>throughput</span> <span m='277624'>is</span> <span m='277978'>order</span>
  <span m='278333'>1/N.</span> <span m='278688'>The</span> <span m='279042'>big</span>
  <span m='279397'>change</span> <span m='279752'>is</span> <span m='280106'>in</span>
  <span m='280461'>the</span> <span m='280816'>hardware</span> <span m='281170'>cost</span>
  <span m='281525'>at</span> <span m='281880'>order</span> <span m='282286'>N,</span>
  <span m='282692'>a</span> <span m='283098'>dramatic</span> <span m='283504'>improvement</span>
  <span m='283910'>over</span> <span m='284316'>the</span> <span m='284722'>order</span>
  <span m='285128'>N^2</span> <span m='285534'>hardware</span> <span m='285940'>cost</span>
  <span m='286346'>of</span> <span m='286752'>the</span> <span m='287158'>original</span>
  <span m='287564'>combinational</span> <span m='287970'>multiplier.</span> </p><p><span
  m='290430'>This</span> <span m='290858'>completes</span> <span m='291287'>our</span>
  <span m='291716'>little</span> <span m='292145'>foray</span> <span m='292573'>into</span>
  <span m='293002'>multiplier</span> <span m='293431'>designs.</span> </p><p><span
  m='293860'>We've</span> <span m='294158'>seen</span> <span m='294456'>that</span>
  <span m='294754'>with</span> <span m='295052'>a</span> <span m='295350'>little</span>
  <span m='295648'>cleverness</span> <span m='295946'>we</span> <span m='296244'>can</span>
  <span m='296542'>create</span> <span m='296840'>designs</span> <span m='297138'>with</span>
  <span m='297436'>order</span> <span m='297734'>1</span> <span m='298032'>throughput,</span>
  <span m='298330'>or</span> <span m='298785'>designs</span> <span m='299241'>with</span>
  <span m='299697'>only</span> <span m='300152'>order</span> <span m='300608'>N</span>
  <span m='301064'>hardware.</span> </p><p><span m='301520'>The</span> <span m='301864'>technique</span>
  <span m='302209'>of</span> <span m='302554'>carry-save</span> <span m='302898'>addition</span>
  <span m='303243'>is</span> <span m='303588'>useful</span> <span m='303932'>in</span>
  <span m='304277'>many</span> <span m='304622'>situations</span> <span m='304966'>and</span>
  <span m='305311'>its</span> <span m='305656'>use</span> <span m='306000'>can</span>
  <span m='306345'>improve</span> <span m='306690'>throughput</span> <span m='307115'>at</span>
  <span m='307541'>constant</span> <span m='307967'>hardware</span> <span m='308393'>cost,</span>
  <span m='308819'>or</span> <span m='309245'>save</span> <span m='309670'>hardware</span>
  <span m='310096'>at</span> <span m='310522'>a</span> <span m='310948'>constant</span>
  <span m='311374'>throughput.</span> </p>
type: course
uid: b09860eabfa0ea570a854a02bb3b9b27

---
None