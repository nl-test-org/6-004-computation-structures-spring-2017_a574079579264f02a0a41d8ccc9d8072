---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: RiD2xxcrsxg
  parent_uid: a8a026eb120074fd232cf587074ea9d3
  title: Video-YouTube-Stream
  type: Video
  uid: efef992572e4881beeff3a254ac53900
- id: 3Play-3Play YouTube id-Stream
  media_location: RiD2xxcrsxg
  parent_uid: a8a026eb120074fd232cf587074ea9d3
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 831ce3dbb616beca56e03bfe5123b1bb
- id: RiD2xxcrsxg.srt
  parent_uid: a8a026eb120074fd232cf587074ea9d3
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v6/control-structures-2-16-/RiD2xxcrsxg.srt
  title: 3play caption file
  type: null
  uid: 93eff7fdc8e8a1303dbb065dba45058f
- id: RiD2xxcrsxg.pdf
  parent_uid: a8a026eb120074fd232cf587074ea9d3
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v6/control-structures-2-16-/RiD2xxcrsxg.pdf
  title: 3play pdf file
  type: null
  uid: 35a08fa4ca59f158eebb41d97cb01949
- id: Caption-3Play YouTube id-SRT
  parent_uid: a8a026eb120074fd232cf587074ea9d3
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: aaedd343abfd67797d93453c188f27f2
- id: Transcript-3Play YouTube id-PDF
  parent_uid: a8a026eb120074fd232cf587074ea9d3
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 003372b0ab2c7305c8bdad92c49b6865
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/RiD2xxcrsxg/default.jpg
  parent_uid: a8a026eb120074fd232cf587074ea9d3
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 252f50e3afa1ac545d127b91814ea4a7
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_07-02-06_300k.mp4
  parent_uid: a8a026eb120074fd232cf587074ea9d3
  title: Video-Internet Archive-MP4
  type: Video
  uid: d8963d3f7e3eafc04ce058ba7d6428f9
inline_embed_id: 96519846controlstructures21623220391
layout: video
order_index: null
parent_uid: 509729e9f9105996d75c4722c8709b99
related_resources_text: ''
short_url: control-structures-2-16-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v6/control-structures-2-16-
template_type: Embed
title: Control Structures (2:16)
transcript: "<p><span m='330'>Let\u2019s</span> <span m='790'>summarize</span> <span\
  \ m='1570'>what</span> <span m='1740'>we\u2019ve</span> <span m='1940'>learned</span>\
  \ <span m='2260'>about</span> <span m='2550'>controlling</span> <span m='3210'>pipelined</span>\
  \ <span m='3770'>systems.</span> </p><p><span m='5170'>The</span> <span m='5250'>most</span>\
  \ <span m='5490'>straightforward</span> <span m='6090'>approach</span> <span m='6490'>is</span>\
  \ <span m='6630'>to</span> <span m='6720'>use</span> <span m='6960'>a</span> <span\
  \ m='7040'>pipeline</span> <span m='7710'>with</span> <span m='7840'>the</span>\
  \ <span m='7910'>system</span> <span m='8320'>clock</span> <span m='8840'>chosen</span>\
  \ <span m='9310'>to</span> <span m='9470'>accommodate</span> <span m='10310'>the</span>\
  \ <span m='10530'>worst-case</span> <span m='11100'>processing</span> <span m='11670'>time.</span>\
  \ </p><p><span m='12970'>These</span> <span m='13210'>systems</span> <span m='13610'>are</span>\
  \ <span m='13740'>easy</span> <span m='14050'>to</span> <span m='14150'>design</span>\
  \ <span m='14950'>but</span> <span m='15290'>can\u2019t</span> <span m='15600'>produce</span>\
  \ <span m='16010'>higher</span> <span m='16300'>throughputs</span> <span m='17020'>if</span>\
  \ <span m='17260'>the</span> <span m='17360'>processing</span> <span m='17910'>stages</span>\
  \ <span m='18410'>might</span> <span m='18690'>run</span> <span m='18890'>more</span>\
  \ <span m='19120'>quickly</span> <span m='19590'>for</span> <span m='19780'>some</span>\
  \ <span m='20100'>data</span> <span m='20370'>values.</span> </p><p><span m='22190'>We</span>\
  \ <span m='22300'>saw</span> <span m='22570'>that</span> <span m='22720'>we</span>\
  \ <span m='22820'>could</span> <span m='23020'>use</span> <span m='23250'>a</span>\
  \ <span m='23300'>simple</span> <span m='23800'>handshake</span> <span m='24320'>protocol</span>\
  \ <span m='24830'>to</span> <span m='24900'>move</span> <span m='25150'>data</span>\
  \ <span m='25510'>through</span> <span m='25770'>the</span> <span m='25880'>system.</span>\
  \ </p><p><span m='27010'>All</span> <span m='27210'>communication</span> <span m='27860'>still</span>\
  \ <span m='28130'>happens</span> <span m='28440'>on</span> <span m='28510'>the</span>\
  \ <span m='28580'>rising</span> <span m='29020'>edge</span> <span m='29190'>of</span>\
  \ <span m='29260'>the</span> <span m='29340'>system</span> <span m='29730'>clock,</span>\
  \ <span m='30270'>but</span> <span m='30640'>the</span> <span m='30720'>specific</span>\
  \ <span m='31260'>clock</span> <span m='31620'>edge</span> <span m='31870'>used</span>\
  \ <span m='32140'>to</span> <span m='32220'>transfer</span> <span m='32680'>data</span>\
  \ <span m='33070'>is</span> <span m='33240'>determined</span> <span m='33720'>by</span>\
  \ <span m='33850'>the</span> <span m='33960'>stages</span> <span m='34550'>themselves.</span>\
  \ </p><p><span m='36690'>It\u2019s</span> <span m='36860'>tempting</span> <span\
  \ m='37290'>to</span> <span m='37360'>wonder</span> <span m='37850'>if</span> <span\
  \ m='37940'>we</span> <span m='38050'>can</span> <span m='38190'>might</span> <span\
  \ m='38330'>adjust</span> <span m='38710'>the</span> <span m='38770'>global</span>\
  \ <span m='39150'>clock</span> <span m='39480'>period</span> <span m='39830'>to</span>\
  \ <span m='39940'>take</span> <span m='40200'>advantage</span> <span m='40720'>of</span>\
  \ <span m='40840'>data-dependent</span> <span m='41600'>processing</span> <span\
  \ m='42100'>speedups.</span> </p><p><span m='43650'>But</span> <span m='43770'>the</span>\
  \ <span m='43860'>necessary</span> <span m='44530'>timing</span> <span m='44930'>generators</span>\
  \ <span m='45480'>can</span> <span m='45600'>be</span> <span m='45730'>very</span>\
  \ <span m='46060'>complicated</span> <span m='46810'>in</span> <span m='46890'>large</span>\
  \ <span m='47180'>systems.</span> </p><p><span m='48460'>It\u2019s</span> <span\
  \ m='48600'>usually</span> <span m='49030'>much</span> <span m='49370'>easier</span>\
  \ <span m='49780'>to</span> <span m='49890'>use</span> <span m='50200'>local</span>\
  \ <span m='50530'>communication</span> <span m='51220'>between</span> <span m='51620'>modules</span>\
  \ <span m='52220'>to</span> <span m='52340'>determine</span> <span m='52810'>system</span>\
  \ <span m='53220'>timing</span> <span m='53810'>than</span> <span m='54150'>trying</span>\
  \ <span m='54410'>to</span> <span m='54500'>figure</span> <span m='54820'>out</span>\
  \ <span m='55010'>all</span> <span m='55290'>the</span> <span m='55360'>constraints</span>\
  \ <span m='55930'>at</span> <span m='56010'>the</span> <span m='56080'>system</span>\
  \ <span m='56500'>level.</span> </p><p><span m='57370'>So</span> <span m='57460'>this</span>\
  \ <span m='57700'>approach</span> <span m='58190'>isn\u2019t</span> <span m='58480'>usually</span>\
  \ <span m='58850'>a</span> <span m='58910'>good</span> <span m='59090'>one.</span>\
  \ </p><p><span m='60800'>But</span> <span m='60940'>what</span> <span m='61240'>about</span>\
  \ <span m='61630'>locally-timed</span> <span m='62560'>asynchronous</span> <span\
  \ m='63230'>systems</span> <span m='63680'>like</span> <span m='63850'>the</span>\
  \ <span m='63980'>example</span> <span m='64540'>we</span> <span m='64720'>just</span>\
  \ <span m='64980'>saw?</span> </p><p><span m='66330'>Each</span> <span m='66620'>generation</span>\
  \ <span m='67200'>of</span> <span m='67320'>engineers</span> <span m='67980'>has</span>\
  \ <span m='68180'>heard</span> <span m='68470'>the</span> <span m='68530'>siren</span>\
  \ <span m='68980'>call</span> <span m='69330'>of</span> <span m='69450'>asynchronous</span>\
  \ <span m='70050'>logic.</span> </p><p><span m='71170'>Sadly,</span> <span m='71770'>it</span>\
  \ <span m='71930'>usually</span> <span m='72290'>proves</span> <span m='72630'>too</span>\
  \ <span m='72820'>hard</span> <span m='73170'>to</span> <span m='73250'>produce</span>\
  \ <span m='73660'>a</span> <span m='73700'>provably</span> <span m='74350'>reliable</span>\
  \ <span m='74940'>design</span> <span m='75430'>for</span> <span m='75640'>a</span>\
  \ <span m='75670'>large</span> <span m='75950'>system,</span> <span m='76510'>say,</span>\
  \ <span m='76980'>a</span> <span m='77020'>modern</span> <span m='77360'>computer.</span>\
  \ </p><p><span m='79190'>But</span> <span m='79290'>there</span> <span m='79490'>are</span>\
  \ <span m='79580'>special</span> <span m='79990'>cases,</span> <span m='80550'>such</span>\
  \ <span m='80880'>as</span> <span m='81080'>the</span> <span m='81220'>logic</span>\
  \ <span m='81620'>for</span> <span m='81780'>integer</span> <span m='82150'>division,</span>\
  \ <span m='83100'>where</span> <span m='83690'>the</span> <span m='83810'>data-dependent</span>\
  \ <span m='84630'>speed-ups</span> <span m='85220'>make</span> <span m='85430'>the</span>\
  \ <span m='85590'>extra</span> <span m='86010'>work</span> <span m='86370'>worthwhile.</span>\
  \ </p><p><span m='88420'>We</span> <span m='88570'>characterized</span> <span m='89390'>the</span>\
  \ <span m='89470'>performance</span> <span m='90050'>of</span> <span m='90140'>our</span>\
  \ <span m='90260'>systems</span> <span m='90840'>by</span> <span m='91020'>measuring</span>\
  \ <span m='91630'>their</span> <span m='91800'>latency</span> <span m='92440'>and</span>\
  \ <span m='92580'>throughput.</span> </p><p><span m='93680'>For</span> <span m='93780'>combinational</span>\
  \ <span m='94410'>circuits,</span> <span m='94880'>the</span> <span m='94970'>latency</span>\
  \ <span m='95550'>is</span> <span m='95650'>simply</span> <span m='96050'>the</span>\
  \ <span m='96150'>propagation</span> <span m='96830'>delay</span> <span m='97120'>of</span>\
  \ <span m='97220'>the</span> <span m='97280'>circuit</span> <span m='97920'>and</span>\
  \ <span m='98240'>its</span> <span m='98410'>throughput</span> <span m='98970'>is</span>\
  \ <span m='99190'>just</span> <span m='99690'>1/latency.</span> </p><p><span m='101800'>We</span>\
  \ <span m='101940'>introduced</span> <span m='102580'>a</span> <span m='102620'>systematic</span>\
  \ <span m='103280'>strategy</span> <span m='103780'>for</span> <span m='103950'>designing</span>\
  \ <span m='104390'>K-pipelines,</span> <span m='105890'>where</span> <span m='106630'>there\u2019\
  s</span> <span m='106900'>a</span> <span m='106960'>register</span> <span m='107580'>on</span>\
  \ <span m='107670'>the</span> <span m='107820'>outputs</span> <span m='108280'>of</span>\
  \ <span m='108370'>each</span> <span m='108580'>stage,</span> <span m='109250'>and</span>\
  \ <span m='109530'>there</span> <span m='109760'>are</span> <span m='109810'>exactly</span>\
  \ <span m='110310'>K</span> <span m='110580'>registers</span> <span m='111230'>on</span>\
  \ <span m='111390'>every</span> <span m='111660'>path</span> <span m='112110'>from</span>\
  \ <span m='112320'>input</span> <span m='112830'>to</span> <span m='113050'>output.</span>\
  \ </p><p><span m='114840'>The</span> <span m='114920'>period</span> <span m='115390'>of</span>\
  \ <span m='115480'>the</span> <span m='115560'>system</span> <span m='115970'>clock</span>\
  \ <span m='116420'>t_CLK</span> <span m='117050'>is</span> <span m='117510'>determined</span>\
  \ <span m='118080'>by</span> <span m='118310'>the</span> <span m='118500'>propagation</span>\
  \ <span m='119200'>delay</span> <span m='119610'>of</span> <span m='119690'>the</span>\
  \ <span m='119800'>slowest</span> <span m='120360'>pipeline</span> <span m='120850'>stage.</span>\
  \ </p><p><span m='122210'>The</span> <span m='122300'>throughput</span> <span m='122900'>of</span>\
  \ <span m='123030'>a</span> <span m='123080'>pipelined</span> <span m='123610'>system</span>\
  \ <span m='124030'>is</span> <span m='124380'>1/t_CLK</span> <span m='125230'>and</span>\
  \ <span m='125670'>its</span> <span m='125840'>latency</span> <span m='126500'>is</span>\
  \ <span m='126820'>K</span> <span m='127070'>times</span> <span m='127610'>t_CLK.</span>\
  \ </p><p><span m='129780'>Pipelining</span> <span m='130410'>is</span> <span m='130560'>the</span>\
  \ <span m='130639'>key</span> <span m='131110'>to</span> <span m='131290'>increasing</span>\
  \ <span m='131840'>the</span> <span m='131930'>throughput</span> <span m='132540'>of</span>\
  \ <span m='132750'>most</span> <span m='133170'>high-performance</span> <span m='133930'>digital</span>\
  \ <span m='134270'>systems.</span> </p>"
type: course
uid: a8a026eb120074fd232cf587074ea9d3

---
None