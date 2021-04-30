---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: f866lUTRXE4
  parent_uid: 34121c6b337216127520d407827bc3dd
  title: Video-YouTube-Stream
  type: Video
  uid: bb4807188d9bb9c1eda7ecf6ffef1a42
- id: 3Play-3Play YouTube id-Stream
  media_location: f866lUTRXE4
  parent_uid: 34121c6b337216127520d407827bc3dd
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: eb7b1654fdaabc5c6ee3fadef1214c78
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/f866lUTRXE4/default.jpg
  parent_uid: 34121c6b337216127520d407827bc3dd
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: bbdaf5ea28a3fdc3d9cc1ece29379422
- id: f866lUTRXE4.srt
  parent_uid: 34121c6b337216127520d407827bc3dd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v8/huffman-s-algorithm-2-09-/f866lUTRXE4.srt
  title: 3play caption file
  type: null
  uid: 14cf00dafc3b748d010a4af0932b5582
- id: f866lUTRXE4.pdf
  parent_uid: 34121c6b337216127520d407827bc3dd
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v8/huffman-s-algorithm-2-09-/f866lUTRXE4.pdf
  title: 3play pdf file
  type: null
  uid: 8e1c04ad09b9c7d07621a6f76973c188
- id: Caption-3Play YouTube id-SRT
  parent_uid: 34121c6b337216127520d407827bc3dd
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ec313554fd9c6deafe365d8c5359532a
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 34121c6b337216127520d407827bc3dd
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: b5f64daedff1cbb7f487a93d518699c5
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_01-02-08_300k.mp4
  parent_uid: 34121c6b337216127520d407827bc3dd
  title: Video-Internet Archive-MP4
  type: Video
  uid: 2a5006fdee7bf625998113895aa4ccc8
inline_embed_id: 70954769huffmansalgorithm20931504700
layout: video
order_index: null
parent_uid: 459baae15dc4793dd71eb5d0ff662a81
related_resources_text: ''
short_url: huffman-s-algorithm-2-09-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v8/huffman-s-algorithm-2-09-
template_type: Embed
title: Huffman's Algorithm (2:09)
transcript: "<p><span m='470'>Given</span> <span m='1280'>a</span> <span m='1310'>set</span>\
  \ <span m='1570'>of</span> <span m='1640'>symbols</span> <span m='2200'>and</span>\
  \ <span m='2290'>their</span> <span m='2390'>probabilities,</span> <span m='3370'>Huffman\u2019\
  s</span> <span m='4040'>Algorithm</span> <span m='4550'>tells</span> <span m='4890'>us</span>\
  \ <span m='5020'>how</span> <span m='5160'>to</span> <span m='5220'>construct</span>\
  \ <span m='6080'>an</span> <span m='6380'>optimal</span> <span m='6960'>variable-length</span>\
  \ <span m='7700'>encoding.</span> </p><p><span m='8750'>By</span> <span m='8890'>\u201C\
  optimal\u201D</span> <span m='9500'>we</span> <span m='9640'>mean</span> <span m='9910'>that,</span>\
  \ <span m='10230'>assuming</span> <span m='10720'>we\u2019re</span> <span m='10940'>encoding</span>\
  \ <span m='11380'>each</span> <span m='11570'>symbol</span> <span m='12010'>one-at-a-time,</span>\
  \ <span m='12930'>no</span> <span m='13320'>other</span> <span m='13620'>variable-length</span>\
  \ <span m='14340'>code</span> <span m='14660'>will</span> <span m='14790'>have</span>\
  \ <span m='15000'>a</span> <span m='15040'>shorter</span> <span m='15510'>expected</span>\
  \ <span m='16010'>length.</span> </p><p><span m='17370'>The</span> <span m='17560'>algorithm</span>\
  \ <span m='18090'>builds</span> <span m='18440'>the</span> <span m='18520'>binary</span>\
  \ <span m='18990'>tree</span> <span m='19270'>for</span> <span m='19430'>the</span>\
  \ <span m='19540'>encoding</span> <span m='20000'>from</span> <span m='20170'>the</span>\
  \ <span m='20240'>bottom</span> <span m='20570'>up.</span> </p><p><span m='21340'>Start</span>\
  \ <span m='21700'>by</span> <span m='21850'>choosing</span> <span m='22340'>the</span>\
  \ <span m='22410'>two</span> <span m='22640'>symbols</span> <span m='23160'>with</span>\
  \ <span m='23280'>the</span> <span m='23340'>smallest</span> <span m='23830'>probability</span>\
  \ <span m='24630'>(which</span> <span m='25000'>means</span> <span m='25230'>they</span>\
  \ <span m='25330'>have</span> <span m='25550'>highest</span> <span m='26050'>information</span>\
  \ <span m='26550'>content</span> <span m='27110'>and</span> <span m='27200'>should</span>\
  \ <span m='27330'>have</span> <span m='27490'>the</span> <span m='27560'>longest</span>\
  \ <span m='28010'>encoding).</span> </p><p><span m='29750'>If</span> <span m='29880'>anywhere</span>\
  \ <span m='30350'>along</span> <span m='30570'>the</span> <span m='30630'>way,</span>\
  \ <span m='30900'>two</span> <span m='31080'>symbols</span> <span m='31440'>have</span>\
  \ <span m='31560'>the</span> <span m='31630'>same</span> <span m='31930'>probability,</span>\
  \ <span m='32630'>simply</span> <span m='33030'>choose</span> <span m='33310'>one</span>\
  \ <span m='33490'>arbitrarily.</span> </p><p><span m='35010'>In</span> <span m='35120'>our</span>\
  \ <span m='35290'>running</span> <span m='35570'>example,</span> <span m='36130'>the</span>\
  \ <span m='36210'>two</span> <span m='36400'>symbols</span> <span m='36830'>with</span>\
  \ <span m='36930'>the</span> <span m='37000'>lowest</span> <span m='37340'>probability</span>\
  \ <span m='38020'>are</span> <span m='38190'>C</span> <span m='38730'>and</span>\
  \ <span m='38950'>D.</span> </p><p><span m='40310'>Combine</span> <span m='40740'>the</span>\
  \ <span m='40800'>symbols</span> <span m='41320'>as</span> <span m='41460'>a</span>\
  \ <span m='41510'>binary</span> <span m='41950'>subtree,</span> <span m='42580'>with</span>\
  \ <span m='42740'>one</span> <span m='43050'>branch</span> <span m='43460'>labeled</span>\
  \ <span m='43790'>\u201C0\u201D</span> <span m='43820'>and</span> <span m='44270'>the</span>\
  \ <span m='44380'>other</span> <span m='44670'>\u201C1\u201D.</span> </p><p><span\
  \ m='44770'>It</span> <span m='45170'>doesn\u2019t</span> <span m='45790'>matter</span>\
  \ <span m='46080'>which</span> <span m='46350'>labels</span> <span m='46750'>go</span>\
  \ <span m='46920'>with</span> <span m='47080'>which</span> <span m='47330'>branch.</span>\
  \ </p><p><span m='48530'>Remove</span> <span m='48950'>C</span> <span m='49280'>and</span>\
  \ <span m='49410'>D</span> <span m='49680'>from</span> <span m='49880'>our</span>\
  \ <span m='50020'>list</span> <span m='50290'>of</span> <span m='50350'>symbols,</span>\
  \ <span m='51050'>and</span> <span m='51360'>replace</span> <span m='51820'>them</span>\
  \ <span m='52020'>with</span> <span m='52130'>the</span> <span m='52210'>newly</span>\
  \ <span m='52550'>constructed</span> <span m='53220'>subtree,</span> <span m='54060'>whose</span>\
  \ <span m='54550'>root</span> <span m='54840'>has</span> <span m='55100'>the</span>\
  \ <span m='55230'>associated</span> <span m='55870'>probability</span> <span m='57230'>1/6,</span>\
  \ <span m='57660'>the</span> <span m='58050'>sum</span> <span m='58440'>of</span>\
  \ <span m='58520'>the</span> <span m='58590'>probabilities</span> <span m='59330'>of</span>\
  \ <span m='59460'>its</span> <span m='59620'>two</span> <span m='59770'>branches.</span>\
  \ </p><p><span m='61640'>Now</span> <span m='61820'>continue,</span> <span m='62490'>at</span>\
  \ <span m='62710'>each</span> <span m='63010'>step</span> <span m='63330'>choosing</span>\
  \ <span m='63770'>the</span> <span m='63870'>two</span> <span m='64090'>symbols</span>\
  \ <span m='64620'>and/or</span> <span m='64920'>subtrees</span> <span m='65580'>with</span>\
  \ <span m='65710'>the</span> <span m='65770'>lowest</span> <span m='66160'>probabilities,</span>\
  \ <span m='67050'>combining</span> <span m='67720'>the</span> <span m='67780'>choices</span>\
  \ <span m='68310'>into</span> <span m='68660'>a</span> <span m='68690'>new</span>\
  \ <span m='68860'>subtree.</span> </p><p><span m='70620'>At</span> <span m='70760'>this</span>\
  \ <span m='70930'>point</span> <span m='71170'>in</span> <span m='71240'>our</span>\
  \ <span m='71370'>example,</span> <span m='71850'>the</span> <span m='71950'>symbol</span>\
  \ <span m='72350'>A</span> <span m='72650'>has</span> <span m='72840'>the</span>\
  \ <span m='72910'>probability</span> <span m='73640'>1/3,</span> <span m='73810'>the</span>\
  \ <span m='74310'>symbol</span> <span m='74910'>B</span> <span m='75250'>the</span>\
  \ <span m='75330'>probability</span> <span m='76300'>1/2</span> <span m='76880'>and</span>\
  \ <span m='77590'>the</span> <span m='77660'>C/D</span> <span m='78120'>subtree</span>\
  \ <span m='78780'>probability</span> <span m='79380'>1/6.</span> </p><p><span m='79610'>So</span>\
  \ <span m='80300'>we\u2019ll</span> <span m='80970'>combine</span> <span m='81460'>A</span>\
  \ <span m='81930'>with</span> <span m='82150'>the</span> <span m='82210'>C/D</span>\
  \ <span m='82650'>subtree.</span> </p><p><span m='84290'>On</span> <span m='84430'>the</span>\
  \ <span m='84500'>final</span> <span m='84860'>step</span> <span m='85230'>we</span>\
  \ <span m='85480'>only</span> <span m='85720'>have</span> <span m='85910'>two</span>\
  \ <span m='86060'>choices</span> <span m='86480'>left:</span> <span m='86880'>B</span>\
  \ <span m='87300'>and</span> <span m='87420'>the</span> <span m='87690'>A/C/D</span>\
  \ <span m='88310'>subtree,</span> <span m='89210'>which</span> <span m='89710'>we</span>\
  \ <span m='89810'>combine</span> <span m='90340'>in</span> <span m='90450'>a</span>\
  \ <span m='90500'>new</span> <span m='90700'>subtree,</span> <span m='91270'>whose</span>\
  \ <span m='91440'>root</span> <span m='91710'>then</span> <span m='91920'>becomes</span>\
  \ <span m='92350'>the</span> <span m='92470'>root</span> <span m='92760'>of</span>\
  \ <span m='92890'>the</span> <span m='92970'>tree</span> <span m='93320'>representing</span>\
  \ <span m='93910'>the</span> <span m='94080'>optimal</span> <span m='94590'>variable-length</span>\
  \ <span m='95320'>code.</span> </p><p><span m='96440'>Happily,</span> <span m='96890'>this</span>\
  \ <span m='97110'>is</span> <span m='97200'>the</span> <span m='97280'>code</span>\
  \ <span m='97530'>we\u2019ve</span> <span m='97680'>been</span> <span m='97810'>using</span>\
  \ <span m='98120'>all</span> <span m='98400'>along!</span> </p><p><span m='100060'>As</span>\
  \ <span m='100210'>mentioned</span> <span m='100560'>above,</span> <span m='101140'>we</span>\
  \ <span m='101340'>can</span> <span m='101470'>produce</span> <span m='101820'>a</span>\
  \ <span m='101860'>number</span> <span m='102250'>of</span> <span m='102380'>different</span>\
  \ <span m='102730'>variable-length</span> <span m='103390'>codes</span> <span m='103780'>by</span>\
  \ <span m='103900'>swapping</span> <span m='104490'>the</span> <span m='104620'>\u201C\
  0\u201D</span> <span m='104680'>and</span> <span m='104840'>\u201C1\u201D</span>\
  \ <span m='104950'>labels</span> <span m='105890'>on</span> <span m='106080'>any</span>\
  \ <span m='106350'>of</span> <span m='106430'>the</span> <span m='106500'>subtree</span>\
  \ <span m='106940'>branches.</span> </p><p><span m='108290'>But</span> <span m='108410'>all</span>\
  \ <span m='108590'>those</span> <span m='108800'>encodings</span> <span m='109260'>would</span>\
  \ <span m='109380'>have</span> <span m='109640'>the</span> <span m='109750'>same</span>\
  \ <span m='110100'>expected</span> <span m='110660'>length,</span> <span m='111120'>which</span>\
  \ <span m='111540'>is</span> <span m='111670'>determined</span> <span m='112100'>by</span>\
  \ <span m='112230'>the</span> <span m='112340'>distance</span> <span m='112950'>of</span>\
  \ <span m='113120'>each</span> <span m='113410'>symbol</span> <span m='113770'>from</span>\
  \ <span m='113940'>the</span> <span m='114010'>root</span> <span m='114190'>of</span>\
  \ <span m='114250'>the</span> <span m='114320'>tree,</span> <span m='114850'>not</span>\
  \ <span m='115200'>the</span> <span m='115290'>labels</span> <span m='115740'>along</span>\
  \ <span m='116070'>the</span> <span m='116130'>path</span> <span m='116640'>from</span>\
  \ <span m='116880'>root</span> <span m='117190'>to</span> <span m='117400'>leaf.</span>\
  \ </p><p><span m='118560'>So</span> <span m='118710'>all</span> <span m='118900'>these</span>\
  \ <span m='119110'>different</span> <span m='119500'>encodings</span> <span m='120100'>are</span>\
  \ <span m='120250'>equivalent</span> <span m='120750'>in</span> <span m='120880'>terms</span>\
  \ <span m='121260'>of</span> <span m='121370'>their</span> <span m='121530'>efficiency.</span>\
  \ </p><p><span m='123110'>Now</span> <span m='123500'>try</span> <span m='123840'>your</span>\
  \ <span m='124090'>hand</span> <span m='124240'>at</span> <span m='124450'>using</span>\
  \ <span m='124610'>Huffman\u2019s</span> <span m='125010'>Algorithm</span> <span\
  \ m='125450'>to</span> <span m='125540'>construct</span> <span m='126120'>optimal</span>\
  \ <span m='126710'>variable-length</span> <span m='127410'>encodings.</span> </p>"
type: course
uid: 34121c6b337216127520d407827bc3dd

---
None