---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: cVEj5p9GiBA
  parent_uid: 3fc967c1261d8f4ffe0a7579a41afb50
  title: Video-YouTube-Stream
  type: Video
  uid: c65a3a7d5ed764128d8f81b0cc9c427f
- id: 3Play-3Play YouTube id-Stream
  media_location: cVEj5p9GiBA
  parent_uid: 3fc967c1261d8f4ffe0a7579a41afb50
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 8fefa9d782f2cc55dba9d4e086ca8830
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/cVEj5p9GiBA/default.jpg
  parent_uid: 3fc967c1261d8f4ffe0a7579a41afb50
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: a2640e5f77692dee2be4fa5fb89fefa4
- id: cVEj5p9GiBA.srt
  parent_uid: 3fc967c1261d8f4ffe0a7579a41afb50
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v5/fixed-length-encodings-5-51-/cVEj5p9GiBA.srt
  title: 3play caption file
  type: null
  uid: bc3bdac068da7b5f0f2f6e5d7e6ce5cf
- id: cVEj5p9GiBA.pdf
  parent_uid: 3fc967c1261d8f4ffe0a7579a41afb50
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v5/fixed-length-encodings-5-51-/cVEj5p9GiBA.pdf
  title: 3play pdf file
  type: null
  uid: 21ba89ac5f3dcdf03b388762a98c022c
- id: Caption-3Play YouTube id-SRT
  parent_uid: 3fc967c1261d8f4ffe0a7579a41afb50
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: d5f5e759f69a90166ffa14ec27ad2f91
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 3fc967c1261d8f4ffe0a7579a41afb50
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: aac87d36b0689bb277cf2e5cb93167dc
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_01-02-05_300k.mp4
  parent_uid: 3fc967c1261d8f4ffe0a7579a41afb50
  title: Video-Internet Archive-MP4
  type: Video
  uid: 2a7071746911a02fcca1c50510038e8d
inline_embed_id: 88736103fixedlengthencodings5518771828
layout: video
order_index: null
parent_uid: 74e6e88cd0b9243b150c586a278014c3
related_resources_text: ''
short_url: fixed-length-encodings-5-51-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v5/fixed-length-encodings-5-51-
template_type: Embed
title: Fixed-length Encodings (5:51)
transcript: "<p><span m='1060'>If</span> <span m='1337'>the</span> <span m='1615'>symbols</span>\
  \ <span m='1893'>we</span> <span m='2171'>are</span> <span m='2448'>trying</span>\
  \ <span m='2726'>to</span> <span m='3004'>encode</span> <span m='3282'>occur</span>\
  \ <span m='3560'>with</span> <span m='3837'>equal</span> <span m='4115'>probability</span>\
  \ <span m='4393'>(or</span> <span m='4671'>if</span> <span m='4948'>we</span> <span\
  \ m='5226'>have</span> <span m='5504'>no</span> <span m='5782'>a</span> <span m='6060'>priori</span>\
  \ <span m='6470'>reason</span> <span m='6880'>to</span> <span m='7290'>believe</span>\
  \ <span m='7700'>otherwise),</span> <span m='8110'>then</span> <span m='8520'>we'll</span>\
  \ <span m='8930'>use</span> <span m='9340'>a</span> <span m='9750'>fixed-length</span>\
  \ <span m='10160'>encoding,</span> <span m='10570'>where</span> <span m='10980'>all</span>\
  \ <span m='11391'>leaves</span> <span m='11842'>in</span> <span m='12293'>the</span>\
  \ <span m='12745'>encoding's</span> <span m='13196'>binary</span> <span m='13647'>tree</span>\
  \ <span m='14099'>are</span> <span m='14550'>the</span> <span m='15002'>same</span>\
  \ <span m='15453'>distance</span> <span m='15904'>from</span> <span m='16356'>the</span>\
  \ <span m='16807'>root.</span> </p><p><span m='17259'>Fixed-length</span> <span\
  \ m='17554'>encodings</span> <span m='17850'>have</span> <span m='18146'>the</span>\
  \ <span m='18442'>advantage</span> <span m='18738'>of</span> <span m='19034'>supporting</span>\
  \ <span m='19330'>random</span> <span m='19626'>access,</span> <span m='19922'>where</span>\
  \ <span m='20218'>we</span> <span m='20514'>can</span> <span m='20810'>figure</span>\
  \ <span m='21118'>out</span> <span m='21427'>the</span> <span m='21736'>Nth</span>\
  \ <span m='22044'>symbol</span> <span m='22353'>of</span> <span m='22662'>the</span>\
  \ <span m='22970'>message</span> <span m='23279'>by</span> <span m='23588'>simply</span>\
  \ <span m='23896'>skipping</span> <span m='24205'>over</span> <span m='24514'>the</span>\
  \ <span m='24822'>required</span> <span m='25131'>number</span> <span m='25440'>of</span>\
  \ <span m='25749'>bits.</span> </p><p><span m='26890'>For</span> <span m='27240'>example,</span>\
  \ <span m='27591'>in</span> <span m='27942'>a</span> <span m='28292'>message</span>\
  \ <span m='28643'>encoded</span> <span m='28994'>using</span> <span m='29344'>the</span>\
  \ <span m='29695'>fixed-length</span> <span m='30046'>code</span> <span m='30396'>shown</span>\
  \ <span m='30747'>here,</span> <span m='31098'>if</span> <span m='31448'>we</span>\
  \ <span m='31799'>wanted</span> <span m='32150'>to</span> <span m='32425'>determine</span>\
  \ <span m='32701'>the</span> <span m='32977'>third</span> <span m='33253'>symbol</span>\
  \ <span m='33529'>in</span> <span m='33805'>the</span> <span m='34081'>encoded</span>\
  \ <span m='34357'>message,</span> <span m='34632'>we</span> <span m='34908'>would</span>\
  \ <span m='35184'>skip</span> <span m='35460'>the</span> <span m='35736'>4</span>\
  \ <span m='36012'>bits</span> <span m='36288'>used</span> <span m='36564'>to</span>\
  \ <span m='36840'>encode</span> <span m='37292'>the</span> <span m='37744'>first</span>\
  \ <span m='38196'>two</span> <span m='38648'>symbols</span> <span m='39100'>and</span>\
  \ <span m='39552'>start</span> <span m='40005'>decoding</span> <span m='40457'>with</span>\
  \ <span m='40909'>the</span> <span m='41361'>5th</span> <span m='41813'>bit</span>\
  \ <span m='42265'>of</span> <span m='42717'>message.</span> </p><p><span m='43170'>Mr.</span>\
  \ <span m='43535'>Blue</span> <span m='43900'>is</span> <span m='44266'>telling</span>\
  \ <span m='44631'>us</span> <span m='44996'>about</span> <span m='45362'>the</span>\
  \ <span m='45727'>entropy</span> <span m='46092'>for</span> <span m='46458'>random</span>\
  \ <span m='46823'>variables</span> <span m='47188'>that</span> <span m='47554'>have</span>\
  \ <span m='47919'>N</span> <span m='48284'>equally-probable</span> <span m='48650'>outcomes.</span>\
  \ </p><p><span m='49990'>In</span> <span m='50466'>this</span> <span m='50942'>case,</span>\
  \ <span m='51418'>each</span> <span m='51895'>element</span> <span m='52371'>of</span>\
  \ <span m='52847'>the</span> <span m='53323'>sum</span> <span m='53800'>in</span>\
  \ <span m='54276'>the</span> <span m='54752'>entropy</span> <span m='55228'>formula</span>\
  \ <span m='55705'>is</span> <span m='56181'>simply</span> <span m='56657'>(1/N)*log2(N),</span>\
  \ <span m='57133'>and,</span> <span m='57610'>since</span> <span m='58054'>there</span>\
  \ <span m='58498'>are</span> <span m='58942'>N</span> <span m='59387'>elements</span>\
  \ <span m='59831'>in</span> <span m='60275'>the</span> <span m='60720'>sequence,</span>\
  \ <span m='61164'>the</span> <span m='61608'>resulting</span> <span m='62052'>entropy</span>\
  \ <span m='62497'>is</span> <span m='62941'>just</span> <span m='63385'>log2(N).</span>\
  \ </p><p><span m='63830'>Let's</span> <span m='64198'>look</span> <span m='64566'>at</span>\
  \ <span m='64935'>some</span> <span m='65303'>simple</span> <span m='65671'>examples.</span>\
  \ </p><p><span m='66040'>In</span> <span m='66488'>binary-coded</span> <span m='66936'>decimal,</span>\
  \ <span m='67385'>each</span> <span m='67833'>digit</span> <span m='68281'>of</span>\
  \ <span m='68730'>a</span> <span m='69178'>decimal</span> <span m='69626'>number</span>\
  \ <span m='70075'>is</span> <span m='70523'>encoded</span> <span m='70971'>separately.</span>\
  \ </p><p><span m='71420'>Since</span> <span m='71712'>there</span> <span m='72005'>are</span>\
  \ <span m='72297'>10</span> <span m='72590'>different</span> <span m='72882'>decimal</span>\
  \ <span m='73175'>digits,</span> <span m='73467'>we'll</span> <span m='73760'>need</span>\
  \ <span m='74052'>to</span> <span m='74345'>use</span> <span m='74637'>a</span>\
  \ <span m='74930'>4-bit</span> <span m='75222'>code</span> <span m='75515'>to</span>\
  \ <span m='75807'>represent</span> <span m='76100'>the</span> <span m='76694'>10</span>\
  \ <span m='77289'>possible</span> <span m='77884'>choices.</span> </p><p><span m='78479'>The</span>\
  \ <span m='79191'>associated</span> <span m='79903'>entropy</span> <span m='80616'>is</span>\
  \ <span m='81328'>log2(10),</span> <span m='82040'>which</span> <span m='82753'>is</span>\
  \ <span m='83465'>3.322</span> <span m='84177'>bits.</span> </p><p><span m='84890'>We</span>\
  \ <span m='85160'>can</span> <span m='85430'>see</span> <span m='85700'>that</span>\
  \ <span m='85970'>our</span> <span m='86240'>chosen</span> <span m='86510'>encoding</span>\
  \ <span m='86780'>is</span> <span m='87050'>inefficient</span> <span m='87320'>in</span>\
  \ <span m='87590'>the</span> <span m='87860'>sense</span> <span m='88130'>that</span>\
  \ <span m='88400'>we'd</span> <span m='88670'>use</span> <span m='88940'>more</span>\
  \ <span m='89210'>than</span> <span m='89480'>the</span> <span m='89750'>minimum</span>\
  \ <span m='90020'>number</span> <span m='90394'>of</span> <span m='90769'>bits</span>\
  \ <span m='91144'>necessary</span> <span m='91518'>to</span> <span m='91893'>encode,</span>\
  \ <span m='92268'>say,</span> <span m='92642'>a</span> <span m='93017'>number</span>\
  \ <span m='93392'>with</span> <span m='93766'>1000</span> <span m='94141'>decimal</span>\
  \ <span m='94516'>digits:</span> <span m='94890'>our</span> <span m='95265'>encoding</span>\
  \ <span m='95640'>would</span> <span m='95959'>use</span> <span m='96278'>4000</span>\
  \ <span m='96597'>bits,</span> <span m='96917'>although</span> <span m='97236'>the</span>\
  \ <span m='97555'>entropy</span> <span m='97875'>suggests</span> <span m='98194'>we</span>\
  \ <span m='98513'>*might*</span> <span m='98833'>be</span> <span m='99152'>able</span>\
  \ <span m='99471'>to</span> <span m='99791'>find</span> <span m='100110'>a</span>\
  \ <span m='100429'>shorter</span> <span m='100749'>encoding,</span> <span m='101439'>say,</span>\
  \ <span m='102129'>3400</span> <span m='102819'>bits,</span> <span m='103509'>for</span>\
  \ <span m='104199'>messages</span> <span m='104889'>of</span> <span m='105579'>length</span>\
  \ <span m='106269'>1000.</span> </p><p><span m='106959'>Another</span> <span m='107309'>common</span>\
  \ <span m='107659'>encoding</span> <span m='108009'>is</span> <span m='108359'>ASCII,</span>\
  \ <span m='108709'>the</span> <span m='109059'>code</span> <span m='109409'>used</span>\
  \ <span m='109759'>to</span> <span m='110109'>represent</span> <span m='110459'>English</span>\
  \ <span m='110809'>text</span> <span m='111159'>in</span> <span m='111509'>computing</span>\
  \ <span m='111860'>and</span> <span m='112600'>communication.</span> </p><p><span\
  \ m='113340'>ASCII</span> <span m='113896'>has</span> <span m='114452'>94</span>\
  \ <span m='115009'>printing</span> <span m='115565'>characters,</span> <span m='116122'>so</span>\
  \ <span m='116678'>the</span> <span m='117234'>associated</span> <span m='117791'>entropy</span>\
  \ <span m='118347'>is</span> <span m='118904'>log2(94)</span> <span m='119460'>or</span>\
  \ <span m='120016'>6.555</span> <span m='120573'>bits,</span> <span m='121129'>so</span>\
  \ <span m='121686'>we</span> <span m='122242'>would</span> <span m='122799'>use</span>\
  \ <span m='123354'>7</span> <span m='123909'>bits</span> <span m='124464'>in</span>\
  \ <span m='125019'>our</span> <span m='125574'>fixed-length</span> <span m='126129'>encoding</span>\
  \ <span m='126684'>for</span> <span m='127239'>each</span> <span m='127794'>character.</span>\
  \ </p><p><span m='128350'>One</span> <span m='128652'>of</span> <span m='128955'>the</span>\
  \ <span m='129258'>most</span> <span m='129561'>important</span> <span m='129864'>encodings</span>\
  \ <span m='130167'>is</span> <span m='130470'>the</span> <span m='130772'>one</span>\
  \ <span m='131075'>we</span> <span m='131378'>use</span> <span m='131681'>to</span>\
  \ <span m='131984'>represent</span> <span m='132287'>numbers.</span> </p><p><span\
  \ m='132590'>Let's</span> <span m='132949'>start</span> <span m='133308'>by</span>\
  \ <span m='133667'>thinking</span> <span m='134026'>about</span> <span m='134386'>a</span>\
  \ <span m='134745'>representation</span> <span m='135104'>for</span> <span m='135463'>unsigned</span>\
  \ <span m='135823'>integers,</span> <span m='136182'>numbers</span> <span m='136541'>starting</span>\
  \ <span m='136900'>at</span> <span m='137260'>0</span> <span m='137680'>and</span>\
  \ <span m='138100'>counting</span> <span m='138520'>up</span> <span m='138940'>from</span>\
  \ <span m='139360'>there.</span> </p><p><span m='139780'>Drawing</span> <span m='140200'>on</span>\
  \ <span m='140621'>our</span> <span m='141042'>experience</span> <span m='141463'>with</span>\
  \ <span m='141884'>representing</span> <span m='142305'>decimal</span> <span m='142726'>numbers,</span>\
  \ <span m='143147'>i.e.,</span> <span m='143568'>representing</span> <span m='143989'>numbers</span>\
  \ <span m='144410'>in</span> <span m='144750'>\"base</span> <span m='145091'>10\"\
  </span> <span m='145432'>using</span> <span m='145772'>the</span> <span m='146113'>10</span>\
  \ <span m='146454'>decimal</span> <span m='146795'>digits,</span> <span m='147135'>our</span>\
  \ <span m='147476'>binary</span> <span m='147817'>representation</span> <span m='148157'>of</span>\
  \ <span m='148498'>numbers</span> <span m='148839'>will</span> <span m='149180'>use</span>\
  \ <span m='149694'>a</span> <span m='150209'>\"base</span> <span m='150724'>2\"\
  </span> <span m='151239'>representation</span> <span m='151754'>using</span> <span\
  \ m='152269'>the</span> <span m='152784'>two</span> <span m='153299'>binary</span>\
  \ <span m='153814'>digits.</span> </p><p><span m='154329'>The</span> <span m='154646'>formula</span>\
  \ <span m='154964'>for</span> <span m='155282'>converting</span> <span m='155600'>an</span>\
  \ <span m='155918'>N-bit</span> <span m='156236'>binary</span> <span m='156554'>representation</span>\
  \ <span m='156872'>of</span> <span m='157190'>a</span> <span m='157508'>numeric</span>\
  \ <span m='157826'>value</span> <span m='158144'>into</span> <span m='158462'>the</span>\
  \ <span m='158780'>corresponding</span> <span m='159185'>integer</span> <span m='159590'>is</span>\
  \ <span m='159995'>shown</span> <span m='160400'>below</span> <span m='160805'>\u2013\
  </span> <span m='161210'>just</span> <span m='161615'>multiply</span> <span m='162020'>each</span>\
  \ <span m='162425'>binary</span> <span m='162830'>digit</span> <span m='163235'>by</span>\
  \ <span m='163640'>its</span> <span m='164045'>corresponding</span> <span m='164450'>weight</span>\
  \ <span m='165016'>in</span> <span m='165582'>the</span> <span m='166148'>base-2</span>\
  \ <span m='166714'>representation.</span> </p><p><span m='167280'>For</span> <span\
  \ m='167620'>example,</span> <span m='167961'>here's</span> <span m='168302'>a</span>\
  \ <span m='168642'>12-bit</span> <span m='168983'>binary</span> <span m='169324'>number,</span>\
  \ <span m='169664'>with</span> <span m='170005'>the</span> <span m='170346'>weight</span>\
  \ <span m='170686'>of</span> <span m='171027'>each</span> <span m='171368'>binary</span>\
  \ <span m='171708'>digit</span> <span m='172049'>shown</span> <span m='172390'>above.</span>\
  \ </p><p><span m='173450'>We</span> <span m='174117'>can</span> <span m='174784'>compute</span>\
  \ <span m='175451'>its</span> <span m='176118'>value</span> <span m='176785'>as</span>\
  \ <span m='177452'>0*2^11</span> <span m='178120'>plus</span> <span m='178787'>1*2^10</span>\
  \ <span m='179454'>plus</span> <span m='180121'>1*2^9,</span> <span m='180788'>and</span>\
  \ <span m='181455'>so</span> <span m='182122'>on.</span> </p><p><span m='182790'>Keeping</span>\
  \ <span m='183195'>only</span> <span m='183600'>the</span> <span m='184006'>non-zero</span>\
  \ <span m='184411'>terms</span> <span m='184816'>and</span> <span m='185222'>expanding</span>\
  \ <span m='185627'>the</span> <span m='186032'>powers-of-two</span> <span m='186438'>gives</span>\
  \ <span m='186843'>us</span> <span m='187248'>the</span> <span m='187654'>sum</span>\
  \ <span m='188059'>1024</span> <span m='188464'>+</span> <span m='188870'>512</span>\
  \ <span m='189607'>+</span> <span m='190345'>256</span> <span m='191083'>+</span>\
  \ <span m='191821'>128</span> <span m='192558'>+</span> <span m='193296'>64</span>\
  \ <span m='194034'>+</span> <span m='194772'>16</span> <span m='195510'>which,</span>\
  \ <span m='196247'>expressed</span> <span m='196985'>in</span> <span m='197723'>base-10,</span>\
  \ <span m='198461'>sums</span> <span m='199198'>to</span> <span m='199936'>the</span>\
  \ <span m='200674'>number</span> <span m='201412'>2000.</span> </p><p><span m='202150'>With</span>\
  \ <span m='202506'>this</span> <span m='202862'>N-bit</span> <span m='203219'>representation,</span>\
  \ <span m='203575'>the</span> <span m='203932'>smallest</span> <span m='204288'>number</span>\
  \ <span m='204645'>that</span> <span m='205001'>can</span> <span m='205357'>be</span>\
  \ <span m='205714'>represented</span> <span m='206070'>is</span> <span m='206427'>0</span>\
  \ <span m='206783'>(when</span> <span m='207140'>all</span> <span m='207505'>the</span>\
  \ <span m='207871'>binary</span> <span m='208237'>digits</span> <span m='208603'>are</span>\
  \ <span m='208968'>0)</span> <span m='209334'>and</span> <span m='209700'>the</span>\
  \ <span m='210066'>largest</span> <span m='210432'>number</span> <span m='210797'>is</span>\
  \ <span m='211163'>2^N</span> <span m='211529'>\u2013</span> <span m='211895'>1</span>\
  \ <span m='212261'>(when</span> <span m='212626'>all</span> <span m='212992'>the</span>\
  \ <span m='213358'>binary</span> <span m='213724'>digits</span> <span m='214090'>are</span>\
  \ <span m='215094'>1).</span> </p><p><span m='216099'>Many</span> <span m='216476'>digital</span>\
  \ <span m='216853'>systems</span> <span m='217230'>are</span> <span m='217607'>designed</span>\
  \ <span m='217984'>to</span> <span m='218361'>support</span> <span m='218738'>operations</span>\
  \ <span m='219115'>on</span> <span m='219492'>binary-encoded</span> <span m='219869'>numbers</span>\
  \ <span m='220246'>of</span> <span m='220623'>some</span> <span m='221000'>fixed</span>\
  \ <span m='221425'>size,</span> <span m='221850'>e.g.,</span> <span m='222275'>choosing</span>\
  \ <span m='222701'>a</span> <span m='223126'>32-bit</span> <span m='223551'>or</span>\
  \ <span m='223976'>a</span> <span m='224402'>64-bit</span> <span m='224827'>representation,</span>\
  \ <span m='225252'>which</span> <span m='225677'>means</span> <span m='226103'>that</span>\
  \ <span m='226528'>they</span> <span m='226953'>would</span> <span m='227379'>need</span>\
  \ <span m='227718'>multiple</span> <span m='228057'>operations</span> <span m='228397'>when</span>\
  \ <span m='228736'>dealing</span> <span m='229075'>with</span> <span m='229415'>numbers</span>\
  \ <span m='229754'>too</span> <span m='230093'>large</span> <span m='230433'>to</span>\
  \ <span m='230772'>be</span> <span m='231111'>represented</span> <span m='231451'>as</span>\
  \ <span m='231790'>a</span> <span m='232129'>single</span> <span m='232469'>32-bit</span>\
  \ <span m='233211'>or</span> <span m='233953'>64-bit</span> <span m='234695'>binary</span>\
  \ <span m='235437'>string.</span> </p><p><span m='236180'>Long</span> <span m='236525'>strings</span>\
  \ <span m='236871'>of</span> <span m='237216'>binary</span> <span m='237562'>digits</span>\
  \ <span m='237908'>are</span> <span m='238253'>tedious</span> <span m='238599'>and</span>\
  \ <span m='238945'>error-prone</span> <span m='239290'>to</span> <span m='239636'>transcribe,</span>\
  \ <span m='239982'>so</span> <span m='240327'>let's</span> <span m='240673'>find</span>\
  \ <span m='241019'>a</span> <span m='241335'>more</span> <span m='241652'>convenient</span>\
  \ <span m='241969'>notation,</span> <span m='242286'>ideally</span> <span m='242603'>one</span>\
  \ <span m='242920'>where</span> <span m='243237'>it</span> <span m='243554'>will</span>\
  \ <span m='243871'>be</span> <span m='244188'>easy</span> <span m='244505'>to</span>\
  \ <span m='244822'>recover</span> <span m='245139'>the</span> <span m='245456'>original</span>\
  \ <span m='245773'>bit</span> <span m='246090'>string</span> <span m='246487'>without</span>\
  \ <span m='246885'>too</span> <span m='247283'>many</span> <span m='247681'>calculations.</span>\
  \ </p><p><span m='248079'>A</span> <span m='248431'>good</span> <span m='248783'>choice</span>\
  \ <span m='249135'>is</span> <span m='249488'>to</span> <span m='249840'>use</span>\
  \ <span m='250192'>a</span> <span m='250544'>representation</span> <span m='250897'>based</span>\
  \ <span m='251249'>on</span> <span m='251601'>a</span> <span m='251954'>radix</span>\
  \ <span m='252306'>that's</span> <span m='252658'>some</span> <span m='253010'>higher</span>\
  \ <span m='253363'>power</span> <span m='253715'>of</span> <span m='254067'>2,</span>\
  \ <span m='254420'>so</span> <span m='254780'>each</span> <span m='255141'>digit</span>\
  \ <span m='255502'>in</span> <span m='255862'>our</span> <span m='256223'>representation</span>\
  \ <span m='256584'>corresponds</span> <span m='256945'>to</span> <span m='257305'>some</span>\
  \ <span m='257666'>short</span> <span m='258027'>contiguous</span> <span m='258387'>string</span>\
  \ <span m='258748'>of</span> <span m='259109'>binary</span> <span m='259470'>bits.</span>\
  \ </p><p><span m='260589'>A</span> <span m='261024'>popular</span> <span m='261459'>choice</span>\
  \ <span m='261895'>these</span> <span m='262330'>days</span> <span m='262766'>is</span>\
  \ <span m='263201'>a</span> <span m='263637'>radix-16</span> <span m='264072'>representation,</span>\
  \ <span m='264508'>called</span> <span m='264943'>hexadecimal</span> <span m='265379'>or</span>\
  \ <span m='265814'>\"hex\"</span> <span m='266250'>for</span> <span m='266625'>short,</span>\
  \ <span m='267001'>where</span> <span m='267376'>each</span> <span m='267752'>group</span>\
  \ <span m='268127'>of</span> <span m='268503'>4</span> <span m='268878'>binary</span>\
  \ <span m='269254'>digits</span> <span m='269630'>is</span> <span m='270005'>represented</span>\
  \ <span m='270381'>using</span> <span m='270756'>a</span> <span m='271132'>single</span>\
  \ <span m='271507'>hex</span> <span m='271883'>digit.</span> </p><p><span m='272259'>Since</span>\
  \ <span m='272748'>there</span> <span m='273237'>are</span> <span m='273727'>16</span>\
  \ <span m='274216'>possible</span> <span m='274706'>combinations</span> <span m='275195'>of</span>\
  \ <span m='275684'>4</span> <span m='276174'>binary</span> <span m='276663'>bits,</span>\
  \ <span m='277153'>we'll</span> <span m='277642'>need</span> <span m='278131'>16</span>\
  \ <span m='278621'>hexadecimal</span> <span m='279110'>\"digits\":</span> <span\
  \ m='279600'>we'll</span> <span m='279937'>borrow</span> <span m='280275'>the</span>\
  \ <span m='280613'>ten</span> <span m='280951'>digits</span> <span m='281289'>\"\
  0\"</span> <span m='281627'>through</span> <span m='281965'>\"9\"</span> <span m='282302'>from</span>\
  \ <span m='282640'>the</span> <span m='282978'>decimal</span> <span m='283316'>representation,</span>\
  \ <span m='283654'>and</span> <span m='283992'>then</span> <span m='284330'>simply</span>\
  \ <span m='284705'>use</span> <span m='285081'>the</span> <span m='285456'>first</span>\
  \ <span m='285832'>six</span> <span m='286208'>letters</span> <span m='286583'>of</span>\
  \ <span m='286959'>the</span> <span m='287335'>alphabet,</span> <span m='287710'>\"\
  A\"</span> <span m='288086'>through</span> <span m='288461'>\"F\",</span> <span\
  \ m='288837'>for</span> <span m='289213'>the</span> <span m='289588'>remaining</span>\
  \ <span m='289964'>digits.</span> </p><p><span m='290340'>The</span> <span m='290765'>translation</span>\
  \ <span m='291191'>between</span> <span m='291616'>4-bit</span> <span m='292042'>binary</span>\
  \ <span m='292468'>and</span> <span m='292893'>hexadecimal</span> <span m='293319'>is</span>\
  \ <span m='293745'>shown</span> <span m='294170'>in</span> <span m='294596'>the</span>\
  \ <span m='295021'>table</span> <span m='295447'>to</span> <span m='295873'>the</span>\
  \ <span m='296298'>left</span> <span m='296724'>below.</span> </p><p><span m='297150'>To</span>\
  \ <span m='297505'>convert</span> <span m='297861'>a</span> <span m='298216'>binary</span>\
  \ <span m='298572'>number</span> <span m='298928'>to</span> <span m='299283'>\"\
  hex\",</span> <span m='299639'>group</span> <span m='299995'>the</span> <span m='300350'>binary</span>\
  \ <span m='300706'>digits</span> <span m='301061'>into</span> <span m='301417'>sets</span>\
  \ <span m='301773'>of</span> <span m='302128'>4,</span> <span m='302484'>starting</span>\
  \ <span m='302840'>with</span> <span m='303339'>the</span> <span m='303838'>least-significant</span>\
  \ <span m='304337'>bit</span> <span m='304836'>(that's</span> <span m='305335'>the</span>\
  \ <span m='305834'>bit</span> <span m='306333'>with</span> <span m='306832'>weight</span>\
  \ <span m='307331'>2^0).</span> </p><p><span m='307830'>Then</span> <span m='308233'>use</span>\
  \ <span m='308636'>the</span> <span m='309039'>table</span> <span m='309442'>to</span>\
  \ <span m='309845'>convert</span> <span m='310248'>each</span> <span m='310651'>4-bit</span>\
  \ <span m='311055'>pattern</span> <span m='311458'>into</span> <span m='311861'>the</span>\
  \ <span m='312264'>corresponding</span> <span m='312667'>hex</span> <span m='313070'>digit:</span>\
  \ <span m='313473'>\"0000\"</span> <span m='313876'>is</span> <span m='314280'>the</span>\
  \ <span m='314759'>hex</span> <span m='315238'>digit</span> <span m='315718'>\"\
  0\",</span> <span m='316197'>\"1101\"</span> <span m='316677'>is</span> <span m='317156'>the</span>\
  \ <span m='317635'>hex</span> <span m='318115'>digit</span> <span m='318594'>\"\
  D\",</span> <span m='319074'>and</span> <span m='319553'>\"0111\"</span> <span m='320032'>is</span>\
  \ <span m='320512'>the</span> <span m='320991'>hex</span> <span m='321471'>digit</span>\
  \ <span m='321950'>\"7\".</span> </p><p><span m='322430'>The</span> <span m='323165'>resulting</span>\
  \ <span m='323900'>hex</span> <span m='324635'>representation</span> <span m='325370'>is</span>\
  \ <span m='326105'>\"7D0\".</span> </p><p><span m='326840'>To</span> <span m='327153'>prevent</span>\
  \ <span m='327467'>any</span> <span m='327780'>confusion,</span> <span m='328094'>we'll</span>\
  \ <span m='328407'>use</span> <span m='328721'>a</span> <span m='329034'>special</span>\
  \ <span m='329348'>prefix</span> <span m='329661'>\"0x\"</span> <span m='329975'>to</span>\
  \ <span m='330288'>indicate</span> <span m='330602'>when</span> <span m='330915'>a</span>\
  \ <span m='331229'>number</span> <span m='331542'>is</span> <span m='331856'>being</span>\
  \ <span m='332170'>shown</span> <span m='332745'>in</span> <span m='333321'>hex,</span>\
  \ <span m='333896'>so</span> <span m='334472'>we'd</span> <span m='335048'>write</span>\
  \ <span m='335623'>\"0x7D0\"</span> <span m='336199'>as</span> <span m='336775'>the</span>\
  \ <span m='337350'>hex</span> <span m='337926'>representation</span> <span m='338501'>for</span>\
  \ <span m='339077'>the</span> <span m='339653'>binary</span> <span m='340228'>number</span>\
  \ <span m='340804'>\"0111</span> <span m='341380'>1101</span> <span m='343269'>0000\"\
  .</span> </p><p><span m='345159'>This</span> <span m='345527'>notation</span> <span\
  \ m='345896'>convention</span> <span m='346264'>is</span> <span m='346633'>used</span>\
  \ <span m='347002'>by</span> <span m='347370'>many</span> <span m='347739'>programming</span>\
  \ <span m='348108'>languages</span> <span m='348476'>for</span> <span m='348845'>entering</span>\
  \ <span m='349214'>binary</span> <span m='349582'>bit</span> <span m='349951'>strings.</span>\
  \ </p>"
type: course
uid: 3fc967c1261d8f4ffe0a7579a41afb50

---
None