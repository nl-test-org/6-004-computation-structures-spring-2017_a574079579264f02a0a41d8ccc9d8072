---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: uh5zxZCp70c
  parent_uid: 9be8fedeb1e714c3391be2f17d7fe330
  title: Video-YouTube-Stream
  type: Video
  uid: 1ccf4884bfa8d590e75b93724f094bde
- id: 3Play-3Play YouTube id-Stream
  media_location: uh5zxZCp70c
  parent_uid: 9be8fedeb1e714c3391be2f17d7fe330
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: a40a8ec5a0a5d8bdcd4063f554e90c00
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/uh5zxZCp70c/default.jpg
  parent_uid: 9be8fedeb1e714c3391be2f17d7fe330
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 75a7128c554d40dbd26e6168933ba85b
- id: uh5zxZCp70c.srt
  parent_uid: 9be8fedeb1e714c3391be2f17d7fe330
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v4/encoding-3-49-/uh5zxZCp70c.srt
  title: 3play caption file
  type: null
  uid: 023bc485185472c41667f52588136a05
- id: uh5zxZCp70c.pdf
  parent_uid: 9be8fedeb1e714c3391be2f17d7fe330
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v4/encoding-3-49-/uh5zxZCp70c.pdf
  title: 3play pdf file
  type: null
  uid: 99f40be327a59783b42b9b2c2d0641ec
- id: Caption-3Play YouTube id-SRT
  parent_uid: 9be8fedeb1e714c3391be2f17d7fe330
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 94b4135cabd5e7a833e433bbbea3316f
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 9be8fedeb1e714c3391be2f17d7fe330
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 406b6d160df3a6e065581420abb01b73
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_01-02-04_300k.mp4
  parent_uid: 9be8fedeb1e714c3391be2f17d7fe330
  title: Video-Internet Archive-MP4
  type: Video
  uid: f7585cf783cfed62674aec0027b4dc69
inline_embed_id: 49203539encoding34961229196
layout: video
order_index: null
parent_uid: 096a78999e1d74cd448c37f4cfd74ca6
related_resources_text: ''
short_url: encoding-3-49-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v4/encoding-3-49-
template_type: Embed
title: Encoding (3:49)
transcript: "<p><span m='1630'>Next</span> <span m='1973'>we</span> <span m='2317'>turn</span>\
  \ <span m='2661'>our</span> <span m='3005'>attention</span> <span m='3349'>to</span>\
  \ <span m='3693'>encoding</span> <span m='4037'>data</span> <span m='4381'>as</span>\
  \ <span m='4725'>sequences</span> <span m='5068'>of</span> <span m='5412'>0's</span>\
  \ <span m='5756'>and</span> <span m='6100'>1's,</span> <span m='6444'>a</span> <span\
  \ m='6788'>string</span> <span m='7132'>of</span> <span m='7476'>bits.</span> </p><p><span\
  \ m='7820'>An</span> <span m='8115'>encoding</span> <span m='8410'>is</span> <span\
  \ m='8705'>an</span> <span m='9000'>unambiguous</span> <span m='9295'>mapping</span>\
  \ <span m='9590'>between</span> <span m='9885'>bit</span> <span m='10180'>strings</span>\
  \ <span m='10475'>and</span> <span m='10770'>the</span> <span m='11065'>members</span>\
  \ <span m='11360'>of</span> <span m='11655'>the</span> <span m='11950'>set</span>\
  \ <span m='12245'>of</span> <span m='12540'>data</span> <span m='13007'>to</span>\
  \ <span m='13475'>be</span> <span m='13942'>encoded.</span> </p><p><span m='14410'>For</span>\
  \ <span m='14696'>example,</span> <span m='14983'>suppose</span> <span m='15269'>we</span>\
  \ <span m='15556'>have</span> <span m='15842'>a</span> <span m='16129'>set</span>\
  \ <span m='16415'>of</span> <span m='16702'>four</span> <span m='16988'>symbols</span>\
  \ <span m='17275'>--</span> <span m='17561'>A,</span> <span m='17848'>B,</span>\
  \ <span m='18134'>C,</span> <span m='18421'>and</span> <span m='18707'>D</span>\
  \ <span m='18994'>\u2013</span> <span m='19280'>and</span> <span m='19567'>we</span>\
  \ <span m='19853'>want</span> <span m='20140'>to</span> <span m='20609'>use</span>\
  \ <span m='21078'>bit</span> <span m='21547'>strings</span> <span m='22017'>to</span>\
  \ <span m='22486'>encode</span> <span m='22955'>messages</span> <span m='23425'>constructed</span>\
  \ <span m='23894'>of</span> <span m='24363'>these</span> <span m='24832'>symbols,</span>\
  \ <span m='25302'>for</span> <span m='25771'>example</span> <span m='26240'>\"ABBA\"\
  .</span> </p><p><span m='26710'>If</span> <span m='27014'>we</span> <span m='27318'>choose</span>\
  \ <span m='27623'>to</span> <span m='27927'>encode</span> <span m='28231'>the</span>\
  \ <span m='28536'>message</span> <span m='28840'>one</span> <span m='29145'>character</span>\
  \ <span m='29449'>at</span> <span m='29753'>a</span> <span m='30058'>time,</span>\
  \ <span m='30362'>our</span> <span m='30667'>encoding</span> <span m='30971'>would</span>\
  \ <span m='31275'>assign</span> <span m='31580'>a</span> <span m='31884'>unique</span>\
  \ <span m='32189'>bit</span> <span m='32711'>string</span> <span m='33233'>to</span>\
  \ <span m='33755'>each</span> <span m='34277'>symbol.</span> </p><p><span m='34800'>Since</span>\
  \ <span m='35063'>we</span> <span m='35326'>have</span> <span m='35589'>four</span>\
  \ <span m='35852'>symbols,</span> <span m='36115'>we</span> <span m='36378'>might</span>\
  \ <span m='36641'>choose</span> <span m='36905'>a</span> <span m='37168'>unique</span>\
  \ <span m='37431'>two-bit</span> <span m='37694'>string</span> <span m='37957'>for</span>\
  \ <span m='38220'>each:</span> <span m='38483'>\"A\"</span> <span m='38746'>could</span>\
  \ <span m='39010'>be</span> <span m='39583'>\"00\",</span> <span m='40156'>B</span>\
  \ <span m='40730'>=</span> <span m='41303'>\"01\",</span> <span m='41876'>C</span>\
  \ <span m='42450'>=</span> <span m='43023'>\"10\",</span> <span m='43596'>and</span>\
  \ <span m='44170'>D</span> <span m='44743'>=</span> <span m='45316'>\"11\".</span>\
  \ </p><p><span m='45890'>This</span> <span m='46194'>would</span> <span m='46499'>be</span>\
  \ <span m='46804'>called</span> <span m='47108'>a</span> <span m='47413'>\"fixed-length</span>\
  \ <span m='47718'>encoding\"</span> <span m='48022'>since</span> <span m='48327'>the</span>\
  \ <span m='48632'>bit</span> <span m='48936'>strings</span> <span m='49241'>used</span>\
  \ <span m='49546'>to</span> <span m='49850'>represent</span> <span m='50155'>the</span>\
  \ <span m='50460'>symbols</span> <span m='50871'>all</span> <span m='51283'>have</span>\
  \ <span m='51695'>the</span> <span m='52106'>same</span> <span m='52518'>length.</span>\
  \ </p><p><span m='52930'>The</span> <span m='53783'>encoding</span> <span m='54636'>for</span>\
  \ <span m='55490'>the</span> <span m='56343'>message</span> <span m='57196'>\"ABBA\"\
  </span> <span m='58050'>would</span> <span m='58903'>be</span> <span m='59756'>\"\
  00-01-01-00\".</span> </p><p><span m='60610'>And</span> <span m='60921'>we</span>\
  \ <span m='61232'>can</span> <span m='61543'>run</span> <span m='61854'>the</span>\
  \ <span m='62165'>process</span> <span m='62476'>backwards:</span> <span m='62787'>given</span>\
  \ <span m='63098'>a</span> <span m='63410'>bit</span> <span m='63721'>string</span>\
  \ <span m='64032'>and</span> <span m='64343'>the</span> <span m='64654'>encoding</span>\
  \ <span m='64965'>key,</span> <span m='65276'>we</span> <span m='65587'>can</span>\
  \ <span m='65899'>look</span> <span m='66252'>up</span> <span m='66606'>the</span>\
  \ <span m='66960'>next</span> <span m='67314'>bits</span> <span m='67668'>in</span>\
  \ <span m='68022'>the</span> <span m='68376'>bit</span> <span m='68730'>string,</span>\
  \ <span m='69084'>using</span> <span m='69438'>the</span> <span m='69792'>key</span>\
  \ <span m='70146'>to</span> <span m='70500'>determine</span> <span m='70854'>the</span>\
  \ <span m='71208'>symbol</span> <span m='71562'>they</span> <span m='71916'>represent.</span>\
  \ </p><p><span m='72270'>\"00\"</span> <span m='72775'>would</span> <span m='73281'>be</span>\
  \ <span m='73787'>decoded</span> <span m='74293'>as</span> <span m='74799'>\"A\"\
  ,</span> <span m='75305'>\"01\"</span> <span m='75810'>as</span> <span m='76316'>B</span>\
  \ <span m='76822'>and</span> <span m='77328'>so</span> <span m='77834'>on.</span>\
  \ </p><p><span m='78340'>We</span> <span m='78668'>can</span> <span m='78996'>also</span>\
  \ <span m='79324'>use</span> <span m='79653'>bit</span> <span m='79981'>strings</span>\
  \ <span m='80309'>of</span> <span m='80637'>different</span> <span m='80966'>lengths</span>\
  \ <span m='81294'>to</span> <span m='81622'>encode</span> <span m='81951'>symbols</span>\
  \ <span m='82279'>--</span> <span m='82607'>this</span> <span m='82935'>is</span>\
  \ <span m='83264'>called</span> <span m='83592'>a</span> <span m='83920'>variable-length</span>\
  \ <span m='84249'>encoding.</span> </p><p><span m='85759'>So</span> <span m='86201'>A</span>\
  \ <span m='86644'>could</span> <span m='87087'>be</span> <span m='87529'>\"01\"\
  ,</span> <span m='87972'>B</span> <span m='88415'>=</span> <span m='88857'>\"1\"\
  ,</span> <span m='89300'>C</span> <span m='89743'>=</span> <span m='90185'>\"000\"\
  </span> <span m='90628'>and</span> <span m='91071'>D</span> <span m='91513'>=</span>\
  \ <span m='91956'>\"001\".</span> </p><p><span m='92399'>\"ABBA\"</span> <span m='93547'>would</span>\
  \ <span m='94695'>be</span> <span m='95844'>encoded</span> <span m='96992'>as</span>\
  \ <span m='98140'>\"01-1-1-01\".</span> </p><p><span m='99289'>We'll</span> <span\
  \ m='99650'>see</span> <span m='100012'>that</span> <span m='100373'>carefully</span>\
  \ <span m='100735'>constructed</span> <span m='101097'>variable-length</span> <span\
  \ m='101458'>encodings</span> <span m='101820'>are</span> <span m='102181'>useful</span>\
  \ <span m='102543'>for</span> <span m='102905'>the</span> <span m='103266'>efficient</span>\
  \ <span m='103628'>encoding</span> <span m='103990'>of</span> <span m='104517'>messages</span>\
  \ <span m='105045'>where</span> <span m='105573'>the</span> <span m='106101'>symbols</span>\
  \ <span m='106628'>occur</span> <span m='107156'>with</span> <span m='107684'>different</span>\
  \ <span m='108212'>probabilities.</span> </p><p><span m='108740'>We</span> <span\
  \ m='109070'>have</span> <span m='109401'>to</span> <span m='109732'>be</span> <span\
  \ m='110063'>careful</span> <span m='110394'>that</span> <span m='110725'>the</span>\
  \ <span m='111056'>encoding</span> <span m='111387'>is</span> <span m='111718'>unambiguous!</span>\
  \ </p><p><span m='112049'>Suppose</span> <span m='112461'>we</span> <span m='112873'>had</span>\
  \ <span m='113285'>decided</span> <span m='113697'>to</span> <span m='114109'>encode</span>\
  \ <span m='114521'>A</span> <span m='114934'>as</span> <span m='115346'>\"0\",</span>\
  \ <span m='115758'>B</span> <span m='116170'>as</span> <span m='116582'>\"1\",</span>\
  \ <span m='116994'>C</span> <span m='117407'>as</span> <span m='117819'>\"10\"</span>\
  \ <span m='118231'>and</span> <span m='118643'>D</span> <span m='119055'>as</span>\
  \ <span m='119467'>\"11\".</span> </p><p><span m='119880'>The</span> <span m='120562'>encoding</span>\
  \ <span m='121245'>for</span> <span m='121928'>\"ABBA\"</span> <span m='122610'>would</span>\
  \ <span m='123293'>be</span> <span m='123976'>\"0-1-1-0\".</span> </p><p><span m='124659'>Looking</span>\
  \ <span m='125029'>good</span> <span m='125400'>since</span> <span m='125771'>that</span>\
  \ <span m='126142'>encoding</span> <span m='126512'>is</span> <span m='126883'>shorter</span>\
  \ <span m='127254'>than</span> <span m='127625'>either</span> <span m='127996'>of</span>\
  \ <span m='128366'>the</span> <span m='128737'>previous</span> <span m='129108'>two</span>\
  \ <span m='129479'>encodings.</span> </p><p><span m='129850'>Now</span> <span m='130247'>let's</span>\
  \ <span m='130644'>try</span> <span m='131041'>to</span> <span m='131438'>decode</span>\
  \ <span m='131835'>this</span> <span m='132232'>bit</span> <span m='132629'>string</span>\
  \ <span m='133026'>--</span> <span m='133423'>oops.</span> </p><p><span m='133820'>Using</span>\
  \ <span m='134197'>the</span> <span m='134574'>encoding</span> <span m='134951'>key,</span>\
  \ <span m='135328'>we</span> <span m='135705'>can</span> <span m='136082'>unfortunately</span>\
  \ <span m='136460'>arrive</span> <span m='136837'>at</span> <span m='137214'>several</span>\
  \ <span m='137591'>decodings:</span> <span m='137968'>\"ABBA\"</span> <span m='138345'>of</span>\
  \ <span m='138722'>course,</span> <span m='139100'>but</span> <span m='139540'>also</span>\
  \ <span m='139980'>\"ADA\"</span> <span m='140420'>or</span> <span m='140860'>\"\
  ABC\"</span> <span m='141300'>depending</span> <span m='141740'>on</span> <span\
  \ m='142180'>how</span> <span m='142620'>we</span> <span m='143060'>group</span>\
  \ <span m='143500'>the</span> <span m='143940'>bits.</span> </p><p><span m='144380'>This</span>\
  \ <span m='144691'>attempt</span> <span m='145002'>at</span> <span m='145314'>specifying</span>\
  \ <span m='145625'>an</span> <span m='145937'>encoding</span> <span m='146248'>has</span>\
  \ <span m='146560'>failed</span> <span m='146871'>since</span> <span m='147182'>the</span>\
  \ <span m='147494'>message</span> <span m='147805'>cannot</span> <span m='148117'>be</span>\
  \ <span m='148428'>interpreted</span> <span m='148740'>unambiguously.</span> </p><p><span\
  \ m='150390'>Graphically</span> <span m='150761'>we</span> <span m='151132'>can</span>\
  \ <span m='151504'>represent</span> <span m='151875'>an</span> <span m='152247'>unambiguous</span>\
  \ <span m='152618'>encoding</span> <span m='152990'>as</span> <span m='153361'>a</span>\
  \ <span m='153732'>binary</span> <span m='154104'>tree,</span> <span m='154475'>labeling</span>\
  \ <span m='154847'>the</span> <span m='155218'>branches</span> <span m='155590'>from</span>\
  \ <span m='155873'>each</span> <span m='156157'>tree</span> <span m='156441'>node</span>\
  \ <span m='156725'>with</span> <span m='157009'>\"0\"</span> <span m='157293'>and</span>\
  \ <span m='157577'>\"1\",</span> <span m='157861'>placing</span> <span m='158145'>the</span>\
  \ <span m='158428'>symbols</span> <span m='158712'>to</span> <span m='158996'>be</span>\
  \ <span m='159280'>encoded</span> <span m='159564'>as</span> <span m='159848'>the</span>\
  \ <span m='160132'>leaves</span> <span m='160416'>of</span> <span m='160700'>the</span>\
  \ <span m='161290'>tree.</span> </p><p><span m='161880'>If</span> <span m='162152'>you</span>\
  \ <span m='162424'>build</span> <span m='162697'>a</span> <span m='162969'>binary</span>\
  \ <span m='163241'>tree</span> <span m='163514'>for</span> <span m='163786'>a</span>\
  \ <span m='164058'>proposed</span> <span m='164331'>encoding</span> <span m='164603'>and</span>\
  \ <span m='164875'>find</span> <span m='165148'>that</span> <span m='165420'>there</span>\
  \ <span m='165692'>are</span> <span m='165965'>no</span> <span m='166237'>symbols</span>\
  \ <span m='166510'>labeling</span> <span m='166826'>interior</span> <span m='167143'>nodes</span>\
  \ <span m='167460'>and</span> <span m='167777'>exactly</span> <span m='168094'>one</span>\
  \ <span m='168410'>symbol</span> <span m='168727'>at</span> <span m='169044'>each</span>\
  \ <span m='169361'>leaf,</span> <span m='169678'>then</span> <span m='169994'>your</span>\
  \ <span m='170311'>encoding</span> <span m='170628'>is</span> <span m='170945'>good</span>\
  \ <span m='171262'>to</span> <span m='171579'>go!</span> </p><p><span m='172660'>For</span>\
  \ <span m='173024'>example,</span> <span m='173388'>consider</span> <span m='173753'>the</span>\
  \ <span m='174117'>encoding</span> <span m='174482'>shown</span> <span m='174846'>on</span>\
  \ <span m='175211'>the</span> <span m='175575'>left.</span> </p><p><span m='175940'>It</span>\
  \ <span m='176260'>takes</span> <span m='176580'>just</span> <span m='176900'>a</span>\
  \ <span m='177220'>second</span> <span m='177540'>to</span> <span m='177860'>draw</span>\
  \ <span m='178180'>the</span> <span m='178500'>corresponding</span> <span m='178820'>binary</span>\
  \ <span m='179140'>tree.</span> </p><p><span m='179460'>The</span> <span m='179728'>symbol</span>\
  \ <span m='179996'>B</span> <span m='180264'>is</span> <span m='180532'>distance</span>\
  \ <span m='180801'>1</span> <span m='181069'>from</span> <span m='181337'>the</span>\
  \ <span m='181605'>root</span> <span m='181874'>of</span> <span m='182142'>the</span>\
  \ <span m='182410'>tree,</span> <span m='182678'>along</span> <span m='182947'>an</span>\
  \ <span m='183215'>arc</span> <span m='183483'>labeled</span> <span m='183751'>\"\
  0\".</span> </p><p><span m='184020'>A</span> <span m='184476'>is</span> <span m='184932'>distance</span>\
  \ <span m='185389'>two,</span> <span m='185845'>and</span> <span m='186301'>C</span>\
  \ <span m='186758'>and</span> <span m='187214'>D</span> <span m='187670'>are</span>\
  \ <span m='188127'>distance</span> <span m='188583'>3.</span> </p><p><span m='189040'>If</span>\
  \ <span m='189498'>we</span> <span m='189956'>receive</span> <span m='190414'>an</span>\
  \ <span m='190872'>encoded</span> <span m='191330'>message,</span> <span m='191788'>for</span>\
  \ <span m='192246'>example</span> <span m='192704'>\"01111\",</span> <span m='193162'>we</span>\
  \ <span m='193620'>can</span> <span m='194078'>decode</span> <span m='194536'>it</span>\
  \ <span m='194994'>using</span> <span m='195452'>successive</span> <span m='195910'>bits</span>\
  \ <span m='196240'>of</span> <span m='196571'>the</span> <span m='196902'>encoding</span>\
  \ <span m='197232'>to</span> <span m='197563'>identify</span> <span m='197894'>a</span>\
  \ <span m='198224'>path</span> <span m='198555'>from</span> <span m='198886'>the</span>\
  \ <span m='199216'>root</span> <span m='199547'>of</span> <span m='199878'>tree,</span>\
  \ <span m='200208'>descending</span> <span m='200539'>step-by-step</span> <span\
  \ m='200870'>until</span> <span m='201205'>we</span> <span m='201540'>come</span>\
  \ <span m='201876'>to</span> <span m='202211'>leaf,</span> <span m='202546'>then</span>\
  \ <span m='202882'>repeating</span> <span m='203217'>the</span> <span m='203552'>process</span>\
  \ <span m='203888'>starting</span> <span m='204223'>at</span> <span m='204558'>the</span>\
  \ <span m='204894'>root</span> <span m='205229'>again,</span> <span m='205564'>until</span>\
  \ <span m='205900'>all</span> <span m='206264'>the</span> <span m='206628'>bits</span>\
  \ <span m='206992'>in</span> <span m='207356'>the</span> <span m='207720'>encoded</span>\
  \ <span m='208084'>message</span> <span m='208448'>have</span> <span m='208812'>been</span>\
  \ <span m='209176'>consumed.</span> </p><p><span m='209540'>So</span> <span m='209809'>the</span>\
  \ <span m='210079'>message</span> <span m='210348'>from</span> <span m='210618'>the</span>\
  \ <span m='210887'>sheep</span> <span m='211157'>is:</span> <span m='211426'>\"\
  0\"</span> <span m='211696'>takes</span> <span m='211965'>us</span> <span m='212235'>from</span>\
  \ <span m='212504'>the</span> <span m='212774'>root</span> <span m='213043'>to</span>\
  \ <span m='213313'>the</span> <span m='213582'>leaf</span> <span m='213852'>B,</span>\
  \ <span m='214121'>which</span> <span m='214391'>is</span> <span m='214660'>our</span>\
  \ <span m='214930'>first</span> <span m='215536'>decoded</span> <span m='216143'>symbol.</span>\
  \ </p><p><span m='216750'>Then</span> <span m='217054'>\"1-1\"</span> <span m='217359'>takes</span>\
  \ <span m='217664'>us</span> <span m='217968'>to</span> <span m='218273'>A</span>\
  \ <span m='218578'>and</span> <span m='218882'>the</span> <span m='219187'>next</span>\
  \ <span m='219492'>\"1-1\"</span> <span m='219796'>results</span> <span m='220101'>in</span>\
  \ <span m='220406'>a</span> <span m='220710'>second</span> <span m='221015'>A.</span>\
  \ </p><p><span m='221320'>The</span> <span m='221674'>final</span> <span m='222028'>decoded</span>\
  \ <span m='222383'>message</span> <span m='222737'>--</span> <span m='223091'>\"\
  BAA\"</span> <span m='223446'>--</span> <span m='223800'>is</span> <span m='224155'>not</span>\
  \ <span m='224509'>totally</span> <span m='224863'>unexpected,</span> <span m='225218'>at</span>\
  \ <span m='225572'>least</span> <span m='225926'>from</span> <span m='226281'>an</span>\
  \ <span m='226635'>American</span> <span m='226990'>sheep.</span> </p>"
type: course
uid: 9be8fedeb1e714c3391be2f17d7fe330

---
None