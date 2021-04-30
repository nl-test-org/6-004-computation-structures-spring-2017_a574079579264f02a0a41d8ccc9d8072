---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: S2c7pAFdP84
  parent_uid: b67a6f489699baa4feb63bd4ff9cd23c
  title: Video-YouTube-Stream
  type: Video
  uid: 5a3f04d65dfe418a14eba9a9cadad057
- id: 3Play-3Play YouTube id-Stream
  media_location: S2c7pAFdP84
  parent_uid: b67a6f489699baa4feb63bd4ff9cd23c
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 4b653fd163d92d136cd4eb17ca558c16
- id: S2c7pAFdP84.srt
  parent_uid: b67a6f489699baa4feb63bd4ff9cd23c
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c8/c8s2/c8s2v2/carry-select-adders-5-40-/S2c7pAFdP84.srt
  title: 3play caption file
  type: null
  uid: 59fcf076384c6ee5fd280409bb456283
- id: S2c7pAFdP84.pdf
  parent_uid: b67a6f489699baa4feb63bd4ff9cd23c
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c8/c8s2/c8s2v2/carry-select-adders-5-40-/S2c7pAFdP84.pdf
  title: 3play pdf file
  type: null
  uid: 73f1ba6e2017f2567b9997a4858b514c
- id: Caption-3Play YouTube id-SRT
  parent_uid: b67a6f489699baa4feb63bd4ff9cd23c
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: fc13c3339b413e8ea1329d24a8cc79d9
- id: Transcript-3Play YouTube id-PDF
  parent_uid: b67a6f489699baa4feb63bd4ff9cd23c
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 07b0963842d796970688ef23207b603e
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/S2c7pAFdP84/default.jpg
  parent_uid: b67a6f489699baa4feb63bd4ff9cd23c
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 2d5b0b303d6ad6f02c0c7717377ee623
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_08-02-02_300k.mp4
  parent_uid: b67a6f489699baa4feb63bd4ff9cd23c
  title: Video-Internet Archive-MP4
  type: Video
  uid: 5d7e3208b6d12fd02151f3dd27566dd4
inline_embed_id: 28485737carryselectadders54079116833
layout: video
order_index: null
parent_uid: 8848841d47e55b57284ec968ec5d34c6
related_resources_text: ''
short_url: carry-select-adders-5-40-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c8/c8s2/c8s2v2/carry-select-adders-5-40-
template_type: Embed
title: Carry-select Adders (5:40)
transcript: "<p><span m='390'>The</span> <span m='840'>most</span> <span m='1070'>straightforward</span>\
  \ <span m='1700'>way</span> <span m='1940'>to</span> <span m='2070'>improve</span>\
  \ <span m='2440'>performance</span> <span m='3100'>is</span> <span m='3270'>to</span>\
  \ <span m='3370'>reduce</span> <span m='3880'>the</span> <span m='3950'>propagation</span>\
  \ <span m='4680'>delay</span> <span m='4970'>of</span> <span m='5070'>a</span> <span\
  \ m='5110'>circuit.</span> </p><p><span m='6070'>Let\u2019s</span> <span m='6280'>look</span>\
  \ <span m='6460'>at</span> <span m='6530'>a</span> <span m='6600'>perennial</span>\
  \ <span m='7280'>performance</span> <span m='7810'>bottleneck:</span> <span m='8500'>the</span>\
  \ <span m='8740'>ripple-carry</span> <span m='9570'>adder.</span> </p><p><span m='10910'>To</span>\
  \ <span m='10990'>fix</span> <span m='11290'>it,</span> <span m='11440'>we</span>\
  \ <span m='11610'>first</span> <span m='11920'>have</span> <span m='12090'>to</span>\
  \ <span m='12190'>figure</span> <span m='12570'>out</span> <span m='12770'>the</span>\
  \ <span m='12850'>path</span> <span m='13310'>from</span> <span m='13540'>inputs</span>\
  \ <span m='14040'>to</span> <span m='14190'>outputs</span> <span m='14820'>that</span>\
  \ <span m='14980'>has</span> <span m='15300'>the</span> <span m='15370'>largest</span>\
  \ <span m='15930'>propagation</span> <span m='16560'>delay,</span> <span m='17150'>i.e.,</span>\
  \ <span m='17470'>the</span> <span m='17840'>path</span> <span m='18430'>that\u2019\
  s</span> <span m='18740'>determining</span> <span m='19370'>the</span> <span m='19550'>overall</span>\
  \ <span m='20100'>t_PD.</span> </p><p><span m='21880'>In</span> <span m='22010'>this</span>\
  \ <span m='22190'>case</span> <span m='22550'>that</span> <span m='22810'>path</span>\
  \ <span m='23220'>is</span> <span m='23400'>the</span> <span m='23470'>long</span>\
  \ <span m='23860'>carry</span> <span m='24240'>chain</span> <span m='24770'>following</span>\
  \ <span m='25320'>the</span> <span m='25380'>carry-in</span> <span m='26050'>to</span>\
  \ <span m='26140'>carry-out</span> <span m='26800'>path</span> <span m='27440'>through</span>\
  \ <span m='27910'>each</span> <span m='28270'>full</span> <span m='28550'>adder</span>\
  \ <span m='28810'>module.</span> </p><p><span m='30310'>To</span> <span m='30430'>trigger</span>\
  \ <span m='30850'>the</span> <span m='30970'>path</span> <span m='31560'>add</span>\
  \ <span m='32250'>-1</span> <span m='32780'>and</span> <span m='33390'>1</span>\
  \ <span m='33710'>by</span> <span m='34020'>setting</span> <span m='34390'>the</span>\
  \ <span m='34560'>A</span> <span m='34770'>inputs</span> <span m='35320'>to</span>\
  \ <span m='35470'>all</span> <span m='35940'>1\u2019s</span> <span m='36300'>and</span>\
  \ <span m='36500'>the</span> <span m='36580'>B</span> <span m='36880'>input</span>\
  \ <span m='37140'>to</span> <span m='37240'>all</span> <span m='37550'>0\u2019s</span>\
  \ <span m='37980'>except</span> <span m='38300'>for</span> <span m='38380'>the</span>\
  \ <span m='38480'>low-order</span> <span m='38970'>bit</span> <span m='39260'>which</span>\
  \ <span m='39530'>is</span> <span m='39770'>1.</span> </p><p><span m='41660'>The</span>\
  \ <span m='41750'>final</span> <span m='42180'>answer</span> <span m='42590'>is</span>\
  \ <span m='43010'>0,</span> <span m='43360'>but</span> <span m='43640'>notice</span>\
  \ <span m='44010'>that</span> <span m='44200'>each</span> <span m='44530'>full</span>\
  \ <span m='44820'>adder</span> <span m='45110'>has</span> <span m='45370'>to</span>\
  \ <span m='45460'>wait</span> <span m='45760'>for</span> <span m='45880'>the</span>\
  \ <span m='45960'>carry-in</span> <span m='46590'>from</span> <span m='46780'>the</span>\
  \ <span m='46860'>previous</span> <span m='47420'>stage</span> <span m='47960'>before</span>\
  \ <span m='48460'>it</span> <span m='48520'>produces</span> <span m='49230'>0</span>\
  \ <span m='49300'>on</span> <span m='49700'>its</span> <span m='50010'>sum</span>\
  \ <span m='50280'>output</span> <span m='50740'>and</span> <span m='50930'>generates</span>\
  \ <span m='51430'>a</span> <span m='51470'>carry-out</span> <span m='52120'>for</span>\
  \ <span m='52270'>the</span> <span m='52360'>next</span> <span m='52720'>full</span>\
  \ <span m='52990'>adder.</span> </p><p><span m='54150'>The</span> <span m='54210'>carry</span>\
  \ <span m='54660'>really</span> <span m='54970'>does</span> <span m='55470'>ripple</span>\
  \ <span m='55790'>through</span> <span m='56390'>the</span> <span m='56640'>circuit</span>\
  \ <span m='57100'>as</span> <span m='57340'>each</span> <span m='57600'>full</span>\
  \ <span m='57860'>adder</span> <span m='58210'>in</span> <span m='58370'>turn</span>\
  \ <span m='58910'>does</span> <span m='59240'>its</span> <span m='59450'>thing.</span>\
  \ </p><p><span m='61330'>To</span> <span m='61420'>total</span> <span m='61720'>propagation</span>\
  \ <span m='62370'>delay</span> <span m='62710'>along</span> <span m='63100'>this</span>\
  \ <span m='63310'>path</span> <span m='63690'>is</span> <span m='63900'>N-1</span>\
  \ <span m='64140'>times</span> <span m='64720'>the</span> <span m='65209'>carry-in</span>\
  \ <span m='65850'>to</span> <span m='65930'>carry-out</span> <span m='66480'>delay</span>\
  \ <span m='66840'>of</span> <span m='66930'>each</span> <span m='67130'>full</span>\
  \ <span m='67400'>adder,</span> <span m='67980'>plus</span> <span m='68650'>the</span>\
  \ <span m='68750'>delay</span> <span m='69180'>to</span> <span m='69290'>produce</span>\
  \ <span m='69730'>the</span> <span m='69810'>final</span> <span m='70200'>bit</span>\
  \ <span m='70430'>of</span> <span m='70530'>the</span> <span m='70630'>sum.</span>\
  \ </p><p><span m='72560'>How</span> <span m='72750'>would</span> <span m='72920'>the</span>\
  \ <span m='73090'>overall</span> <span m='73700'>latency</span> <span m='74160'>change</span>\
  \ <span m='74660'>if</span> <span m='74820'>we,</span> <span m='75210'>say,</span>\
  \ <span m='75640'>doubled</span> <span m='76170'>the</span> <span m='76240'>size</span>\
  \ <span m='76620'>of</span> <span m='76680'>the</span> <span m='76810'>operands,</span>\
  \ <span m='77630'>i.e.,</span> <span m='77970'>made</span> <span m='78270'>N</span>\
  \ <span m='78470'>twice</span> <span m='78810'>as</span> <span m='78930'>large?</span>\
  \ </p><p><span m='81080'>It\u2019s</span> <span m='81250'>useful</span> <span m='81620'>to</span>\
  \ <span m='81710'>summarize</span> <span m='82380'>the</span> <span m='82470'>dependency</span>\
  \ <span m='83170'>of</span> <span m='83250'>the</span> <span m='83340'>latency</span>\
  \ <span m='83830'>on</span> <span m='84000'>N</span> <span m='84580'>using</span>\
  \ <span m='85210'>the</span> <span m='85380'>\u201Corder-of\u201D</span> <span m='85880'>notation</span>\
  \ <span m='86450'>to</span> <span m='86550'>give</span> <span m='86750'>us</span>\
  \ <span m='86910'>the</span> <span m='86980'>big</span> <span m='87170'>picture.</span>\
  \ </p><p><span m='88430'>Clearly</span> <span m='88830'>as</span> <span m='89010'>N</span>\
  \ <span m='89250'>gets</span> <span m='89500'>larger</span> <span m='90060'>the</span>\
  \ <span m='90240'>delay</span> <span m='90560'>of</span> <span m='90640'>the</span>\
  \ <span m='90780'>XOR</span> <span m='91180'>gate</span> <span m='91380'>at</span>\
  \ <span m='91450'>the</span> <span m='91630'>end</span> <span m='91910'>becomes</span>\
  \ <span m='92270'>less</span> <span m='92440'>significant,</span> <span m='93110'>so</span>\
  \ <span m='93350'>the</span> <span m='93540'>order-of</span> <span m='93980'>notation</span>\
  \ <span m='94510'>ignores</span> <span m='95060'>terms</span> <span m='95500'>that</span>\
  \ <span m='95650'>are</span> <span m='95760'>relatively</span> <span m='96440'>less</span>\
  \ <span m='96730'>important</span> <span m='97250'>as</span> <span m='97500'>N</span>\
  \ <span m='97720'>grows.</span> </p><p><span m='99160'>In</span> <span m='99240'>this</span>\
  \ <span m='99400'>example,</span> <span m='99890'>the</span> <span m='99990'>latency</span>\
  \ <span m='100470'>is</span> <span m='100630'>order</span> <span m='100990'>N,</span>\
  \ <span m='101590'>which</span> <span m='102030'>tells</span> <span m='102360'>us</span>\
  \ <span m='102580'>that</span> <span m='102710'>the</span> <span m='102810'>latency</span>\
  \ <span m='103330'>would</span> <span m='103500'>be</span> <span m='103630'>expected</span>\
  \ <span m='104140'>to</span> <span m='104250'>essentially</span> <span m='104780'>double</span>\
  \ <span m='105410'>if</span> <span m='105760'>we</span> <span m='105890'>made</span>\
  \ <span m='106130'>N</span> <span m='106590'>twice</span> <span m='106960'>as</span>\
  \ <span m='107090'>large.</span> </p><p><span m='108320'>The</span> <span m='108480'>order-of</span>\
  \ <span m='109000'>notation,</span> <span m='109640'>which</span> <span m='110010'>theoreticians</span>\
  \ <span m='110770'>call</span> <span m='111060'>asymptotic</span> <span m='111780'>analysis,</span>\
  \ <span m='112610'>tells</span> <span m='113110'>us</span> <span m='113320'>the</span>\
  \ <span m='113410'>term</span> <span m='113830'>that</span> <span m='113960'>would</span>\
  \ <span m='114080'>dominate</span> <span m='114660'>the</span> <span m='114770'>result</span>\
  \ <span m='115290'>as</span> <span m='115560'>N</span> <span m='115760'>grows.</span>\
  \ </p><p><span m='117060'>The</span> <span m='117140'>yellow</span> <span m='117380'>box</span>\
  \ <span m='117730'>contains</span> <span m='118160'>the</span> <span m='118300'>official</span>\
  \ <span m='118660'>definition,</span> <span m='119570'>but</span> <span m='119960'>an</span>\
  \ <span m='120090'>example</span> <span m='120660'>might</span> <span m='120920'>make</span>\
  \ <span m='121120'>it</span> <span m='121250'>easier</span> <span m='121700'>to</span>\
  \ <span m='121820'>understand</span> <span m='122330'>what\u2019s</span> <span m='122570'>happening.</span>\
  \ </p><p><span m='123860'>Suppose</span> <span m='124240'>we</span> <span m='124310'>want</span>\
  \ <span m='124550'>to</span> <span m='124650'>characterize</span> <span m='125330'>the</span>\
  \ <span m='125450'>growth</span> <span m='125780'>in</span> <span m='125880'>the</span>\
  \ <span m='125960'>value</span> <span m='126330'>of</span> <span m='126410'>the</span>\
  \ <span m='126510'>equation</span> <span m='127120'>n^2</span> <span m='127490'>+</span>\
  \ <span m='128039'>2n</span> <span m='128750'>+</span> <span m='129000'>3</span>\
  \ <span m='129280'>as</span> <span m='129600'>n</span> <span m='129830'>gets</span>\
  \ <span m='130090'>larger.</span> </p><p><span m='131170'>The</span> <span m='131240'>dominant</span>\
  \ <span m='131760'>term</span> <span m='132090'>is</span> <span m='132210'>clearly</span>\
  \ <span m='132650'>n^2</span> <span m='132890'>and</span> <span m='133530'>the</span>\
  \ <span m='133900'>value</span> <span m='134340'>of</span> <span m='134440'>our</span>\
  \ <span m='134660'>equation</span> <span m='135060'>is</span> <span m='135210'>bounded</span>\
  \ <span m='135600'>above</span> <span m='136100'>and</span> <span m='136430'>below</span>\
  \ <span m='136970'>by</span> <span m='137140'>simple</span> <span m='137560'>multiples</span>\
  \ <span m='138180'>of</span> <span m='138280'>n^2,</span> <span m='138920'>except</span>\
  \ <span m='139810'>for</span> <span m='139950'>finitely</span> <span m='140550'>many</span>\
  \ <span m='140860'>values</span> <span m='141340'>of</span> <span m='141450'>n.</span>\
  \ </p><p><span m='143250'>The</span> <span m='143330'>lower</span> <span m='143580'>bound</span>\
  \ <span m='143920'>is</span> <span m='144050'>always</span> <span m='144360'>true</span>\
  \ <span m='144620'>for</span> <span m='144830'>n</span> <span m='145180'>greater</span>\
  \ <span m='145540'>than</span> <span m='145660'>or</span> <span m='145740'>equal</span>\
  \ <span m='145990'>to</span> <span m='146360'>0.</span> </p><p><span m='147530'>And</span>\
  \ <span m='147710'>in</span> <span m='147830'>this</span> <span m='148020'>case,</span>\
  \ <span m='148340'>the</span> <span m='148460'>upper</span> <span m='148690'>bound</span>\
  \ <span m='149020'>doesn\u2019t</span> <span m='149340'>hold</span> <span m='149610'>only</span>\
  \ <span m='150080'>for</span> <span m='150320'>n</span> <span m='150540'>equal</span>\
  \ <span m='150880'>to</span> <span m='151760'>0,</span> <span m='152070'>1,</span>\
  \ <span m='152120'>2,</span> <span m='152210'>or</span> <span m='152450'>3.</span>\
  \ </p><p><span m='152510'>For</span> <span m='152930'>all</span> <span m='153560'>other</span>\
  \ <span m='153790'>positive</span> <span m='154260'>values</span> <span m='154670'>of</span>\
  \ <span m='154790'>n</span> <span m='155020'>the</span> <span m='155190'>upper</span>\
  \ <span m='155510'>inequality</span> <span m='156140'>is</span> <span m='156360'>true.</span>\
  \ </p><p><span m='157430'>So</span> <span m='157640'>we\u2019d</span> <span m='157800'>say</span>\
  \ <span m='158160'>this</span> <span m='158410'>equation</span> <span m='159060'>was</span>\
  \ <span m='159520'>\u201Corder</span> <span m='159970'>N^2\u201D.</span> </p><p><span\
  \ m='160460'>There</span> <span m='161490'>are</span> <span m='162550'>actually</span>\
  \ <span m='163030'>two</span> <span m='163290'>variants</span> <span m='163840'>for</span>\
  \ <span m='163990'>the</span> <span m='164140'>order-of</span> <span m='164590'>notation.</span>\
  \ </p><p><span m='165500'>We</span> <span m='165610'>use</span> <span m='165820'>the</span>\
  \ <span m='165900'>Theta</span> <span m='166270'>notation</span> <span m='166830'>to</span>\
  \ <span m='167170'>indicate</span> <span m='167840'>that</span> <span m='168040'>g(n)</span>\
  \ <span m='168070'>is</span> <span m='168250'>bounded</span> <span m='168670'>above</span>\
  \ <span m='169110'>AND</span> <span m='169490'>below</span> <span m='169930'>by</span>\
  \ <span m='170120'>multiples</span> <span m='170640'>of</span> <span m='170780'>f(n).</span>\
  \ </p><p><span m='170970'>The</span> <span m='171620'>\u201Cbig</span> <span m='172370'>O\u201D\
  </span> <span m='172540'>notation</span> <span m='173200'>is</span> <span m='173550'>used</span>\
  \ <span m='173910'>when</span> <span m='174120'>g(n)</span> <span m='174150'>is</span>\
  \ <span m='174310'>only</span> <span m='174600'>bounded</span> <span m='174980'>above</span>\
  \ <span m='175550'>by</span> <span m='175800'>a</span> <span m='175850'>multiple</span>\
  \ <span m='176470'>of</span> <span m='176690'>f(n).</span> </p><p><span m='177750'>Here\u2019\
  s</span> <span m='177960'>a</span> <span m='178020'>first</span> <span m='178370'>attempt</span>\
  \ <span m='178830'>at</span> <span m='178920'>improving</span> <span m='179430'>the</span>\
  \ <span m='179510'>latency</span> <span m='180140'>of</span> <span m='180230'>our</span>\
  \ <span m='180440'>addition</span> <span m='180780'>circuit.</span> </p><p><span\
  \ m='182070'>The</span> <span m='182160'>trouble</span> <span m='182560'>with</span>\
  \ <span m='182710'>the</span> <span m='182880'>ripple-carry</span> <span m='183640'>adder</span>\
  \ <span m='184030'>is</span> <span m='184250'>that</span> <span m='184470'>the</span>\
  \ <span m='184640'>high-order</span> <span m='185180'>bits</span> <span m='185520'>have</span>\
  \ <span m='185740'>to</span> <span m='185850'>wait</span> <span m='186190'>for</span>\
  \ <span m='186360'>the</span> <span m='186440'>carry-in</span> <span m='187070'>from</span>\
  \ <span m='187260'>the</span> <span m='187330'>low-order</span> <span m='187810'>bits.</span>\
  \ </p><p><span m='189010'>Is</span> <span m='189190'>there</span> <span m='189420'>a</span>\
  \ <span m='189450'>way</span> <span m='189780'>in</span> <span m='189850'>which</span>\
  \ <span m='190120'>we</span> <span m='190220'>can</span> <span m='190390'>get</span>\
  \ <span m='190740'>high</span> <span m='191170'>half</span> <span m='191500'>the</span>\
  \ <span m='191720'>adder</span> <span m='191980'>working</span> <span m='192460'>in</span>\
  \ <span m='192640'>parallel</span> <span m='193240'>with</span> <span m='193360'>the</span>\
  \ <span m='193420'>low</span> <span m='193620'>half?</span> </p><p><span m='195090'>Suppose</span>\
  \ <span m='195540'>we</span> <span m='195660'>wanted</span> <span m='196010'>to</span>\
  \ <span m='196070'>build</span> <span m='196350'>a</span> <span m='196690'>32-bit</span>\
  \ <span m='197170'>adder.</span> </p><p><span m='198520'>Let\u2019s</span> <span\
  \ m='198770'>make</span> <span m='198960'>two</span> <span m='199140'>copies</span>\
  \ <span m='199710'>of</span> <span m='199800'>the</span> <span m='199900'>high</span>\
  \ <span m='200210'>16</span> <span m='200420'>bits</span> <span m='200840'>of</span>\
  \ <span m='200910'>the</span> <span m='201100'>adder,</span> <span m='201500'>one</span>\
  \ <span m='201860'>assuming</span> <span m='202260'>the</span> <span m='202330'>carry-in</span>\
  \ <span m='202850'>from</span> <span m='203010'>the</span> <span m='203070'>low</span>\
  \ <span m='203280'>bits</span> <span m='203610'>is</span> <span m='204010'>0,</span>\
  \ <span m='204360'>and</span> <span m='204560'>the</span> <span m='204680'>other</span>\
  \ <span m='204960'>assuming</span> <span m='205360'>the</span> <span m='205450'>carry-in</span>\
  \ <span m='206020'>is</span> <span m='206350'>1.</span> </p><p><span m='207530'>So</span>\
  \ <span m='207640'>now</span> <span m='207880'>we</span> <span m='208020'>have</span>\
  \ <span m='208280'>three</span> <span m='208900'>16-bit</span> <span m='209350'>adders,</span>\
  \ <span m='209840'>all</span> <span m='210060'>of</span> <span m='210190'>which</span>\
  \ <span m='210420'>can</span> <span m='210610'>operate</span> <span m='211100'>in</span>\
  \ <span m='211310'>parallel</span> <span m='212180'>on</span> <span m='212560'>newly</span>\
  \ <span m='212880'>arriving</span> <span m='213370'>A</span> <span m='213590'>and</span>\
  \ <span m='213710'>B</span> <span m='213960'>inputs.</span> </p><p><span m='215550'>Once</span>\
  \ <span m='216070'>the</span> <span m='216400'>16-bit</span> <span m='216570'>additions</span>\
  \ <span m='217030'>are</span> <span m='217140'>complete,</span> <span m='217660'>we</span>\
  \ <span m='217790'>can</span> <span m='217950'>use</span> <span m='218240'>the</span>\
  \ <span m='218420'>actual</span> <span m='218870'>carry-out</span> <span m='219420'>from</span>\
  \ <span m='219580'>the</span> <span m='219640'>low-half</span> <span m='220320'>to</span>\
  \ <span m='220460'>select</span> <span m='220900'>the</span> <span m='221080'>answer</span>\
  \ <span m='221440'>from</span> <span m='221630'>the</span> <span m='221700'>particular</span>\
  \ <span m='222360'>high-half</span> <span m='222860'>adder</span> <span m='223340'>that</span>\
  \ <span m='223670'>used</span> <span m='223970'>the</span> <span m='224060'>matching</span>\
  \ <span m='224600'>carry-in</span> <span m='225130'>value.</span> </p><p><span m='225890'>This</span>\
  \ <span m='226090'>type</span> <span m='226320'>of</span> <span m='226450'>adder</span>\
  \ <span m='226860'>is</span> <span m='227030'>appropriately</span> <span m='227650'>named</span>\
  \ <span m='228070'>the</span> <span m='228210'>carry-select</span> <span m='228990'>adder.</span>\
  \ </p><p><span m='230410'>The</span> <span m='230480'>latency</span> <span m='230990'>of</span>\
  \ <span m='231060'>this</span> <span m='231260'>carry-select</span> <span m='231890'>adder</span>\
  \ <span m='232180'>is</span> <span m='232240'>just</span> <span m='232500'>a</span>\
  \ <span m='232580'>little</span> <span m='232820'>more</span> <span m='233120'>than</span>\
  \ <span m='233270'>the</span> <span m='233370'>latency</span> <span m='233900'>of</span>\
  \ <span m='233990'>a</span> <span m='234310'>16-bit</span> <span m='234840'>ripple-carry</span>\
  \ <span m='235530'>addition.</span> </p><p><span m='236670'>This</span> <span m='236870'>is</span>\
  \ <span m='237010'>approximately</span> <span m='237730'>half</span> <span m='238100'>the</span>\
  \ <span m='238190'>latency</span> <span m='238710'>of</span> <span m='238780'>the</span>\
  \ <span m='238980'>original</span> <span m='239670'>32-bit</span> <span m='240160'>ripple-carry</span>\
  \ <span m='240830'>adder.</span> </p><p><span m='241910'>So</span> <span m='242140'>at</span>\
  \ <span m='242230'>a</span> <span m='242280'>cost</span> <span m='242780'>of</span>\
  \ <span m='242930'>about</span> <span m='243570'>50%</span> <span m='243880'>more</span>\
  \ <span m='244090'>circuitry,</span> <span m='244810'>we\u2019ve</span> <span m='245160'>halved</span>\
  \ <span m='245530'>the</span> <span m='245670'>latency!</span> </p><p><span m='247620'>As</span>\
  \ <span m='247750'>a</span> <span m='247780'>next</span> <span m='247990'>step,</span>\
  \ <span m='248410'>we</span> <span m='248510'>could</span> <span m='248650'>apply</span>\
  \ <span m='248970'>the</span> <span m='249070'>same</span> <span m='249400'>strategy</span>\
  \ <span m='249980'>to</span> <span m='250080'>halve</span> <span m='250420'>the</span>\
  \ <span m='250500'>latency</span> <span m='250990'>of</span> <span m='251310'>the</span>\
  \ <span m='251650'>16-bit</span> <span m='251830'>adders.</span> </p><p><span m='252820'>And</span>\
  \ <span m='252940'>then</span> <span m='253120'>again</span> <span m='253480'>to</span>\
  \ <span m='253600'>halve</span> <span m='253910'>the</span> <span m='254000'>latency</span>\
  \ <span m='254460'>of</span> <span m='254650'>the</span> <span m='254910'>8-bit</span>\
  \ <span m='255100'>adders</span> <span m='255500'>used</span> <span m='255790'>in</span>\
  \ <span m='255880'>the</span> <span m='255950'>previous</span> <span m='256459'>step.</span>\
  \ </p><p><span m='257640'>At</span> <span m='257730'>each</span> <span m='258010'>step</span>\
  \ <span m='258360'>we</span> <span m='258510'>halve</span> <span m='258850'>the</span>\
  \ <span m='259050'>adder</span> <span m='259300'>latency</span> <span m='259980'>and</span>\
  \ <span m='260250'>add</span> <span m='260459'>a</span> <span m='260519'>MUX</span>\
  \ <span m='260890'>delay.</span> </p><p><span m='262100'>After</span> <span m='262600'>log2(N)</span>\
  \ <span m='263250'>steps,</span> <span m='264430'>N</span> <span m='264810'>will</span>\
  \ <span m='264940'>be</span> <span m='265180'>1</span> <span m='265310'>and</span>\
  \ <span m='265630'>we\u2019re</span> <span m='265980'>done.</span> </p><p><span\
  \ m='268190'>At</span> <span m='268300'>this</span> <span m='268520'>point</span>\
  \ <span m='268810'>the</span> <span m='268920'>latency</span> <span m='269380'>would</span>\
  \ <span m='269580'>be</span> <span m='269800'>some</span> <span m='270060'>constant</span>\
  \ <span m='270500'>cost</span> <span m='270860'>to</span> <span m='271130'>do</span>\
  \ <span m='271280'>a</span> <span m='271320'>1-bit</span> <span m='271530'>addition,</span>\
  \ <span m='272260'>plus</span> <span m='272780'>log2(N)</span> <span m='273380'>times</span>\
  \ <span m='274290'>the</span> <span m='274370'>MUX</span> <span m='274740'>latency</span>\
  \ <span m='275200'>to</span> <span m='275300'>select</span> <span m='275800'>the</span>\
  \ <span m='275920'>right</span> <span m='276170'>answers.</span> </p><p><span m='277500'>So</span>\
  \ <span m='277650'>the</span> <span m='277830'>overall</span> <span m='278330'>latency</span>\
  \ <span m='278830'>of</span> <span m='278910'>the</span> <span m='278990'>carry-select</span>\
  \ <span m='279740'>adder</span> <span m='280070'>is</span> <span m='280380'>order</span>\
  \ <span m='281450'>log(N).</span> </p><p><span m='282200'>Note</span> <span m='282420'>that</span>\
  \ <span m='282760'>log2(N)</span> <span m='282920'>and</span> <span m='283270'>log(N)</span>\
  \ <span m='283700'>only</span> <span m='284320'>differ</span> <span m='284600'>by</span>\
  \ <span m='284810'>a</span> <span m='284840'>constant</span> <span m='285400'>factor,</span>\
  \ <span m='286000'>so</span> <span m='286280'>we</span> <span m='286430'>ignore</span>\
  \ <span m='286880'>the</span> <span m='286980'>base</span> <span m='287280'>of</span>\
  \ <span m='287350'>the</span> <span m='287460'>log</span> <span m='287930'>in</span>\
  \ <span m='288110'>order-of</span> <span m='288570'>notation.</span> </p><p><span\
  \ m='290420'>The</span> <span m='290480'>carry-select</span> <span m='291230'>adder</span>\
  \ <span m='291500'>shows</span> <span m='291790'>a</span> <span m='291900'>clear</span>\
  \ <span m='292340'>performance-size</span> <span m='293500'>tradeoff</span> <span\
  \ m='294090'>available</span> <span m='294670'>to</span> <span m='294860'>the</span>\
  \ <span m='294970'>designer.</span> </p><p><span m='296370'>Since</span> <span m='296650'>adders</span>\
  \ <span m='297110'>play</span> <span m='297350'>a</span> <span m='297400'>big</span>\
  \ <span m='297700'>role</span> <span m='298070'>in</span> <span m='298130'>many</span>\
  \ <span m='298410'>digital</span> <span m='298790'>systems,</span> <span m='299550'>here\u2019\
  s</span> <span m='299980'>a</span> <span m='300020'>more</span> <span m='300200'>carefully</span>\
  \ <span m='300750'>engineered</span> <span m='301210'>version</span> <span m='301570'>of</span>\
  \ <span m='301910'>a</span> <span m='302220'>32-bit</span> <span m='302440'>carry-select</span>\
  \ <span m='303140'>adder.</span> </p><p><span m='303810'>You</span> <span m='303940'>could</span>\
  \ <span m='304090'>try</span> <span m='304300'>this</span> <span m='304720'>in</span>\
  \ <span m='304870'>your</span> <span m='305100'>ALU</span> <span m='305390'>design!</span>\
  \ </p><p><span m='307190'>The</span> <span m='307270'>size</span> <span m='307700'>of</span>\
  \ <span m='307800'>the</span> <span m='307970'>adder</span> <span m='308240'>blocks</span>\
  \ <span m='308660'>has</span> <span m='308810'>been</span> <span m='308960'>chosen</span>\
  \ <span m='309460'>so</span> <span m='309650'>that</span> <span m='309780'>the</span>\
  \ <span m='309850'>trial</span> <span m='310270'>sums</span> <span m='310810'>and</span>\
  \ <span m='310950'>the</span> <span m='311010'>carry-in</span> <span m='311950'>from</span>\
  \ <span m='312350'>the</span> <span m='312420'>previous</span> <span m='312890'>stage</span>\
  \ <span m='313330'>arrive</span> <span m='313730'>at</span> <span m='313850'>the</span>\
  \ <span m='313930'>carry-select</span> <span m='314700'>MUX</span> <span m='315100'>at</span>\
  \ <span m='315210'>approximately</span> <span m='315880'>the</span> <span m='315960'>same</span>\
  \ <span m='316300'>time.</span> </p><p><span m='317680'>Note</span> <span m='317910'>that</span>\
  \ <span m='318050'>since</span> <span m='318340'>the</span> <span m='318410'>select</span>\
  \ <span m='318840'>signal</span> <span m='319280'>for</span> <span m='319460'>the</span>\
  \ <span m='319550'>MUXes</span> <span m='320070'>is</span> <span m='320250'>heavily</span>\
  \ <span m='320590'>loaded</span> <span m='321190'>we\u2019ve</span> <span m='321520'>included</span>\
  \ <span m='321970'>a</span> <span m='322020'>buffer</span> <span m='322600'>to</span>\
  \ <span m='322820'>make</span> <span m='323070'>the</span> <span m='323130'>select</span>\
  \ <span m='323510'>signal</span> <span m='323920'>transitions</span> <span m='324640'>faster.</span>\
  \ </p><p><span m='326540'>This</span> <span m='326740'>carry-select</span> <span\
  \ m='327380'>adder</span> <span m='327680'>is</span> <span m='327780'>about</span>\
  \ <span m='328080'>two-and-a-half</span> <span m='328710'>times</span> <span m='329140'>faster</span>\
  \ <span m='329690'>than</span> <span m='330000'>a</span> <span m='330330'>32-bit</span>\
  \ <span m='330630'>ripple-carry</span> <span m='331280'>adder</span> <span m='331860'>at</span>\
  \ <span m='332310'>the</span> <span m='332390'>cost</span> <span m='332780'>of</span>\
  \ <span m='332890'>about</span> <span m='333250'>twice</span> <span m='333530'>as</span>\
  \ <span m='333640'>much</span> <span m='333930'>circuitry.</span> </p><p><span m='335770'>A</span>\
  \ <span m='335830'>great</span> <span m='336120'>design</span> <span m='336490'>to</span>\
  \ <span m='336560'>remember</span> <span m='337110'>when</span> <span m='337260'>you\u2019\
  re</span> <span m='337400'>looking</span> <span m='337660'>to</span> <span m='337760'>double</span>\
  \ <span m='338150'>the</span> <span m='338230'>speed</span> <span m='338690'>of</span>\
  \ <span m='338780'>your</span> <span m='339030'>ALU!</span> </p>"
type: course
uid: b67a6f489699baa4feb63bd4ff9cd23c

---
None