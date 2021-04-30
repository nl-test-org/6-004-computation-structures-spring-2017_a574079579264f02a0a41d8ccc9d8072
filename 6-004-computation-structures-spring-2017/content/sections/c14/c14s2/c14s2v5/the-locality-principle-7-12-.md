---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: M-ZgVhzvh24
  parent_uid: daef0d0ecf55da5d45b3d7557119137b
  title: Video-YouTube-Stream
  type: Video
  uid: 93d3b400125b3ab0f48ffe65ef2479b8
- id: 3Play-3Play YouTube id-Stream
  media_location: M-ZgVhzvh24
  parent_uid: daef0d0ecf55da5d45b3d7557119137b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 33c3b09bb67b288d6fc09c9d8b212fbf
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/M-ZgVhzvh24/default.jpg
  parent_uid: daef0d0ecf55da5d45b3d7557119137b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: cae457600e5352a6549ce90a772b27ea
- id: M-ZgVhzvh24.srt
  parent_uid: daef0d0ecf55da5d45b3d7557119137b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v5/the-locality-principle-7-12-/M-ZgVhzvh24.srt
  title: 3play caption file
  type: null
  uid: decc8c3b476f18af517d1c0975f34640
- id: M-ZgVhzvh24.pdf
  parent_uid: daef0d0ecf55da5d45b3d7557119137b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v5/the-locality-principle-7-12-/M-ZgVhzvh24.pdf
  title: 3play pdf file
  type: null
  uid: 748ca0f50a7a76a026455bff792f94f6
- id: Caption-3Play YouTube id-SRT
  parent_uid: daef0d0ecf55da5d45b3d7557119137b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: c8f647b4496a98bc061670e5580c740f
- id: Transcript-3Play YouTube id-PDF
  parent_uid: daef0d0ecf55da5d45b3d7557119137b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 198ea1a59642e8eb8a009b22f9b03def
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_14-02-05_300k.mp4
  parent_uid: daef0d0ecf55da5d45b3d7557119137b
  title: Video-Internet Archive-MP4
  type: Video
  uid: 41f770eca1a5cd0b052d78c14c7b938c
inline_embed_id: 52938656thelocalityprinciple71275046206
layout: video
order_index: null
parent_uid: 2d5bf7d8a0828451dd766bbaf498e88e
related_resources_text: ''
short_url: the-locality-principle-7-12-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v5/the-locality-principle-7-12-
template_type: Embed
title: The Locality Principle (7:12)
transcript: "<p><span m='400'>So,</span> <span m='1250'>how</span> <span m='1600'>can</span>\
  \ <span m='1760'>the</span> <span m='1830'>memory</span> <span m='2190'>system</span>\
  \ <span m='2570'>arrange</span> <span m='3010'>for</span> <span m='3130'>the</span>\
  \ <span m='3220'>right</span> <span m='3550'>data</span> <span m='3930'>to</span>\
  \ <span m='4110'>be</span> <span m='4320'>in</span> <span m='4400'>the</span> <span\
  \ m='4470'>right</span> <span m='4770'>place</span> <span m='5240'>at</span> <span\
  \ m='5350'>the</span> <span m='5430'>right</span> <span m='5670'>time?</span> </p><p><span\
  \ m='7060'>Our</span> <span m='7180'>goal</span> <span m='7510'>is</span> <span\
  \ m='7600'>to</span> <span m='7700'>have</span> <span m='7940'>the</span> <span\
  \ m='8039'>frequently-used</span> <span m='8890'>data</span> <span m='9560'>in</span>\
  \ <span m='9970'>some</span> <span m='10340'>fast</span> <span m='10790'>SRAM.</span>\
  \ </p><p><span m='12030'>That</span> <span m='12230'>means</span> <span m='12580'>the</span>\
  \ <span m='12690'>memory</span> <span m='13150'>system</span> <span m='13510'>will</span>\
  \ <span m='13630'>have</span> <span m='13820'>to</span> <span m='13920'>be</span>\
  \ <span m='14130'>able</span> <span m='14270'>to</span> <span m='14390'>predict</span>\
  \ <span m='14950'>which</span> <span m='15330'>memory</span> <span m='15660'>locations</span>\
  \ <span m='16250'>will</span> <span m='16340'>be</span> <span m='16510'>accessed.</span>\
  \ </p><p><span m='17770'>And</span> <span m='17870'>to</span> <span m='17930'>keep</span>\
  \ <span m='18140'>the</span> <span m='18250'>overhead</span> <span m='18640'>of</span>\
  \ <span m='18730'>moving</span> <span m='19000'>data</span> <span m='19290'>into</span>\
  \ <span m='19820'>and</span> <span m='20050'>out</span> <span m='20270'>of</span>\
  \ <span m='20390'>SRAM</span> <span m='20810'>manageable,</span> <span m='21660'>we\u2019\
  d</span> <span m='22030'>like</span> <span m='22260'>to</span> <span m='22390'>amortize</span>\
  \ <span m='23010'>the</span> <span m='23090'>cost</span> <span m='23530'>of</span>\
  \ <span m='23590'>the</span> <span m='23670'>move</span> <span m='24040'>over</span>\
  \ <span m='24290'>many</span> <span m='24610'>accesses.</span> </p><p><span m='25610'>In</span>\
  \ <span m='25670'>other</span> <span m='25790'>words</span> <span m='26100'>we</span>\
  \ <span m='26210'>want</span> <span m='26510'>any</span> <span m='26760'>block</span>\
  \ <span m='27130'>of</span> <span m='27250'>data</span> <span m='27520'>we</span>\
  \ <span m='27710'>move</span> <span m='27920'>into</span> <span m='28230'>SRAM</span>\
  \ <span m='28800'>to</span> <span m='28950'>be</span> <span m='29140'>accessed</span>\
  \ <span m='29740'>many</span> <span m='30030'>times.</span> </p><p><span m='31920'>When</span>\
  \ <span m='32060'>not</span> <span m='32490'>in</span> <span m='32750'>SRAM,</span>\
  \ <span m='33340'>data</span> <span m='33760'>would</span> <span m='34170'>live</span>\
  \ <span m='34560'>in</span> <span m='34920'>the</span> <span m='35020'>larger,</span>\
  \ <span m='35570'>slower</span> <span m='36150'>DRAM</span> <span m='36770'>that</span>\
  \ <span m='36880'>serves</span> <span m='37220'>as</span> <span m='37340'>main</span>\
  \ <span m='37650'>memory.</span> </p><p><span m='38580'>If</span> <span m='38680'>the</span>\
  \ <span m='38760'>system</span> <span m='39130'>is</span> <span m='39230'>working</span>\
  \ <span m='39550'>as</span> <span m='39730'>planned,</span> <span m='40310'>DRAM</span>\
  \ <span m='40820'>accesses</span> <span m='41370'>would</span> <span m='41530'>happen</span>\
  \ <span m='41920'>infrequently,</span> <span m='42830'>e.g.,</span> <span m='43280'>only</span>\
  \ <span m='43740'>when</span> <span m='43950'>it\u2019s</span> <span m='44110'>time</span>\
  \ <span m='44340'>to</span> <span m='44440'>bring</span> <span m='44650'>another</span>\
  \ <span m='44970'>block</span> <span m='45330'>of</span> <span m='45440'>data</span>\
  \ <span m='45710'>into</span> <span m='45930'>SRAM.</span> </p><p><span m='48240'>If</span>\
  \ <span m='48380'>we</span> <span m='48540'>look</span> <span m='48760'>at</span>\
  \ <span m='48840'>how</span> <span m='49020'>programs</span> <span m='49700'>access</span>\
  \ <span m='50250'>memory,</span> <span m='50720'>it</span> <span m='50890'>turns</span>\
  \ <span m='51210'>out</span> <span m='51340'>we</span> <span m='51560'>*can*</span>\
  \ <span m='52130'>make</span> <span m='52390'>accurate</span> <span m='52880'>predictions</span>\
  \ <span m='53840'>about</span> <span m='54500'>which</span> <span m='54840'>memory</span>\
  \ <span m='55150'>locations</span> <span m='55800'>will</span> <span m='55890'>be</span>\
  \ <span m='56060'>accessed.</span> </p><p><span m='58040'>The</span> <span m='58140'>guiding</span>\
  \ <span m='58530'>principle</span> <span m='59120'>is</span> <span m='59350'>\u201C\
  locality</span> <span m='60160'>of</span> <span m='60400'>reference\u201D</span>\
  \ <span m='61250'>which</span> <span m='61790'>tells</span> <span m='62140'>us</span>\
  \ <span m='62290'>that</span> <span m='62500'>if</span> <span m='62710'>there\u2019\
  s</span> <span m='62970'>an</span> <span m='63090'>access</span> <span m='63680'>to</span>\
  \ <span m='63840'>address</span> <span m='64379'>X</span> <span m='64860'>at</span>\
  \ <span m='65019'>time</span> <span m='65430'>t,</span> <span m='66090'>it\u2019\
  s</span> <span m='66550'>very</span> <span m='66870'>probable</span> <span m='67440'>that</span>\
  \ <span m='67580'>the</span> <span m='67640'>program</span> <span m='68160'>will</span>\
  \ <span m='68310'>access</span> <span m='68750'>a</span> <span m='68810'>nearby</span>\
  \ <span m='69310'>location</span> <span m='70020'>in</span> <span m='70200'>the</span>\
  \ <span m='70310'>near</span> <span m='70540'>future.</span> </p><p><span m='71830'>To</span>\
  \ <span m='71950'>understand</span> <span m='72580'>why</span> <span m='72940'>programs</span>\
  \ <span m='73560'>exhibit</span> <span m='74080'>locality</span> <span m='74670'>of</span>\
  \ <span m='74800'>reference,</span> <span m='75380'>let\u2019s</span> <span m='75720'>look</span>\
  \ <span m='75940'>at</span> <span m='76010'>how</span> <span m='76320'>a</span>\
  \ <span m='76380'>running</span> <span m='76690'>program</span> <span m='77300'>accesses</span>\
  \ <span m='77850'>memory.</span> </p><p><span m='79790'>Instruction</span> <span\
  \ m='80380'>fetches</span> <span m='80800'>are</span> <span m='80880'>quite</span>\
  \ <span m='81190'>predictable.</span> </p><p><span m='82290'>Execution</span> <span\
  \ m='83170'>usually</span> <span m='83610'>proceeds</span> <span m='84060'>sequentially</span>\
  \ <span m='84770'>since</span> <span m='85080'>most</span> <span m='85410'>of</span>\
  \ <span m='85470'>the</span> <span m='85560'>time</span> <span m='85960'>the</span>\
  \ <span m='86070'>next</span> <span m='86430'>instruction</span> <span m='87020'>is</span>\
  \ <span m='87250'>fetched</span> <span m='87510'>from</span> <span m='87650'>the</span>\
  \ <span m='87730'>location</span> <span m='88380'>after</span> <span m='88750'>that</span>\
  \ <span m='89050'>of</span> <span m='89160'>the</span> <span m='89240'>current</span>\
  \ <span m='89600'>instruction.</span> </p><p><span m='91430'>Code</span> <span m='91750'>that</span>\
  \ <span m='91920'>loops</span> <span m='92350'>will</span> <span m='92550'>repeatedly</span>\
  \ <span m='93200'>fetch</span> <span m='93500'>the</span> <span m='93590'>same</span>\
  \ <span m='93900'>sequence</span> <span m='94370'>of</span> <span m='94450'>instructions,</span>\
  \ <span m='95350'>as</span> <span m='95650'>shown</span> <span m='96020'>here</span>\
  \ <span m='96350'>on</span> <span m='96450'>the</span> <span m='96540'>left</span>\
  \ <span m='96910'>of</span> <span m='96980'>the</span> <span m='97070'>time</span>\
  \ <span m='97400'>line.</span> </p><p><span m='99030'>There</span> <span m='99160'>will</span>\
  \ <span m='99310'>of</span> <span m='99400'>course</span> <span m='99750'>be</span>\
  \ <span m='99890'>branches</span> <span m='100460'>and</span> <span m='100590'>subroutine</span>\
  \ <span m='101060'>calls</span> <span m='101440'>that</span> <span m='101590'>interrupt</span>\
  \ <span m='102040'>sequential</span> <span m='102540'>execution,</span> <span m='103400'>but</span>\
  \ <span m='103800'>then</span> <span m='104020'>we\u2019re</span> <span m='104140'>back</span>\
  \ <span m='104480'>to</span> <span m='104580'>fetching</span> <span m='104970'>instructions</span>\
  \ <span m='105580'>from</span> <span m='105700'>consecutive</span> <span m='106320'>locations.</span>\
  \ </p><p><span m='107720'>Some</span> <span m='108070'>programming</span> <span\
  \ m='108570'>constructs,</span> <span m='109500'>e.g.,</span> <span m='109950'>method</span>\
  \ <span m='110390'>dispatch</span> <span m='110980'>in</span> <span m='111100'>object-oriented</span>\
  \ <span m='111990'>languages,</span> <span m='112800'>can</span> <span m='113230'>produce</span>\
  \ <span m='113690'>scattered</span> <span m='114080'>references</span> <span m='114610'>to</span>\
  \ <span m='114720'>very</span> <span m='115000'>short</span> <span m='115350'>code</span>\
  \ <span m='115590'>sequences</span> <span m='116370'>(as</span> <span m='116570'>shown</span>\
  \ <span m='117050'>on</span> <span m='117230'>the</span> <span m='117290'>right</span>\
  \ <span m='117620'>of</span> <span m='117680'>the</span> <span m='117770'>time</span>\
  \ <span m='118060'>line)</span> <span m='118570'>but</span> <span m='119020'>order</span>\
  \ <span m='119460'>is</span> <span m='119660'>quickly</span> <span m='120060'>restored.</span>\
  \ </p><p><span m='121690'>This</span> <span m='121880'>agrees</span> <span m='122250'>with</span>\
  \ <span m='122420'>our</span> <span m='122550'>intuition</span> <span m='123170'>about</span>\
  \ <span m='123420'>program</span> <span m='123900'>execution.</span> </p><p><span\
  \ m='125150'>For</span> <span m='125320'>example,</span> <span m='125840'>once</span>\
  \ <span m='126120'>we</span> <span m='126280'>execute</span> <span m='126700'>the</span>\
  \ <span m='126830'>first</span> <span m='127190'>instruction</span> <span m='127680'>of</span>\
  \ <span m='127810'>a</span> <span m='127870'>procedure,</span> <span m='128470'>we\u2019\
  ll</span> <span m='128610'>almost</span> <span m='128990'>certainly</span> <span\
  \ m='129370'>execute</span> <span m='129820'>the</span> <span m='129919'>remaining</span>\
  \ <span m='130410'>instructions</span> <span m='131080'>in</span> <span m='131150'>the</span>\
  \ <span m='131220'>procedure.</span> </p><p><span m='132500'>So</span> <span m='133000'>if</span>\
  \ <span m='133330'>we</span> <span m='133460'>arranged</span> <span m='133800'>for</span>\
  \ <span m='133990'>all</span> <span m='134240'>the</span> <span m='134330'>code</span>\
  \ <span m='134650'>of</span> <span m='134740'>a</span> <span m='134800'>procedure</span>\
  \ <span m='135360'>to</span> <span m='135530'>moved</span> <span m='135890'>to</span>\
  \ <span m='136060'>SRAM</span> <span m='136620'>when</span> <span m='136880'>the</span>\
  \ <span m='136950'>procedure\u2019s</span> <span m='137520'>first</span> <span m='137920'>instruction</span>\
  \ <span m='138430'>was</span> <span m='138630'>fetched,</span> <span m='139300'>we\u2019\
  d</span> <span m='139710'>expect</span> <span m='140150'>that</span> <span m='140310'>many</span>\
  \ <span m='140580'>subsequent</span> <span m='141260'>instruction</span> <span m='141810'>fetches</span>\
  \ <span m='142270'>could</span> <span m='142420'>be</span> <span m='142550'>satisfied</span>\
  \ <span m='143290'>by</span> <span m='143400'>the</span> <span m='143640'>SRAM.</span>\
  \ </p><p><span m='144830'>And</span> <span m='145180'>although</span> <span m='145580'>fetching</span>\
  \ <span m='146080'>the</span> <span m='146160'>first</span> <span m='146500'>word</span>\
  \ <span m='146720'>of</span> <span m='146810'>a</span> <span m='146880'>block</span>\
  \ <span m='147240'>from</span> <span m='147410'>DRAM</span> <span m='147910'>has</span>\
  \ <span m='148160'>relatively</span> <span m='148720'>long</span> <span m='149130'>latency,</span>\
  \ <span m='149900'>the</span> <span m='150180'>DRAM\u2019s</span> <span m='150790'>fast</span>\
  \ <span m='151180'>column</span> <span m='151560'>accesses</span> <span m='152170'>will</span>\
  \ <span m='152500'>quickly</span> <span m='152910'>stream</span> <span m='153290'>the</span>\
  \ <span m='153380'>remaining</span> <span m='153840'>words</span> <span m='154160'>from</span>\
  \ <span m='154330'>sequential</span> <span m='154950'>addresses.</span> </p><p><span\
  \ m='156690'>This</span> <span m='156930'>will</span> <span m='157140'>amortize</span>\
  \ <span m='157860'>the</span> <span m='157950'>cost</span> <span m='158350'>of</span>\
  \ <span m='158440'>the</span> <span m='158550'>initial</span> <span m='159030'>access</span>\
  \ <span m='159810'>over</span> <span m='160200'>the</span> <span m='160340'>whole</span>\
  \ <span m='160670'>sequence</span> <span m='161140'>of</span> <span m='161230'>transfers.</span>\
  \ </p><p><span m='163900'>The</span> <span m='163990'>story</span> <span m='164470'>is</span>\
  \ <span m='164530'>similar</span> <span m='165020'>for</span> <span m='165230'>accesses</span>\
  \ <span m='165790'>by</span> <span m='165990'>a</span> <span m='166030'>procedure</span>\
  \ <span m='166530'>to</span> <span m='166700'>its</span> <span m='166840'>arguments</span>\
  \ <span m='167390'>and</span> <span m='167500'>local</span> <span m='167790'>variables</span>\
  \ <span m='168360'>in</span> <span m='168420'>the</span> <span m='168490'>current</span>\
  \ <span m='168780'>stack</span> <span m='169180'>frame.</span> </p><p><span m='170320'>Again</span>\
  \ <span m='171010'>there</span> <span m='171290'>will</span> <span m='171390'>be</span>\
  \ <span m='171530'>many</span> <span m='171870'>accesses</span> <span m='172410'>to</span>\
  \ <span m='172620'>a</span> <span m='172710'>small</span> <span m='173150'>region</span>\
  \ <span m='173460'>of</span> <span m='173560'>memory</span> <span m='174040'>during</span>\
  \ <span m='174310'>the</span> <span m='174370'>span</span> <span m='174730'>of</span>\
  \ <span m='174830'>time</span> <span m='175210'>we\u2019re</span> <span m='175380'>executing</span>\
  \ <span m='175970'>the</span> <span m='176030'>procedure\u2019s</span> <span m='176590'>code.</span>\
  \ </p><p><span m='179090'>Data</span> <span m='179300'>accesses</span> <span m='180000'>generated</span>\
  \ <span m='180530'>by</span> <span m='180720'>LD</span> <span m='181120'>and</span>\
  \ <span m='181230'>ST</span> <span m='181540'>instructions</span> <span m='182240'>also</span>\
  \ <span m='182760'>exhibit</span> <span m='183120'>locality.</span> </p><p><span\
  \ m='184410'>The</span> <span m='184490'>program</span> <span m='185030'>may</span>\
  \ <span m='185160'>be</span> <span m='185380'>accessing</span> <span m='185850'>the</span>\
  \ <span m='185920'>components</span> <span m='186510'>of</span> <span m='186600'>an</span>\
  \ <span m='186880'>object</span> <span m='187490'>or</span> <span m='187580'>struct.</span>\
  \ </p><p><span m='188730'>Or</span> <span m='188860'>it</span> <span m='188920'>may</span>\
  \ <span m='189080'>be</span> <span m='189210'>stepping</span> <span m='189650'>through</span>\
  \ <span m='189810'>the</span> <span m='190000'>elements</span> <span m='190410'>of</span>\
  \ <span m='190500'>an</span> <span m='190560'>array.</span> </p><p><span m='192080'>Sometimes</span>\
  \ <span m='192710'>information</span> <span m='193390'>is</span> <span m='193600'>moved</span>\
  \ <span m='193860'>from</span> <span m='194080'>one</span> <span m='194290'>array</span>\
  \ <span m='194770'>or</span> <span m='194890'>data</span> <span m='195150'>object</span>\
  \ <span m='195570'>to</span> <span m='195770'>another,</span> <span m='196420'>as</span>\
  \ <span m='196730'>shown</span> <span m='197090'>by</span> <span m='197240'>the</span>\
  \ <span m='197340'>data</span> <span m='197600'>accesses</span> <span m='198180'>on</span>\
  \ <span m='198290'>the</span> <span m='198350'>right</span> <span m='198610'>of</span>\
  \ <span m='198670'>the</span> <span m='198740'>timeline.</span> </p><p><span m='201110'>Using</span>\
  \ <span m='201390'>simulations</span> <span m='202300'>we</span> <span m='202420'>can</span>\
  \ <span m='202610'>estimate</span> <span m='203210'>the</span> <span m='203320'>number</span>\
  \ <span m='203800'>of</span> <span m='203980'>different</span> <span m='204430'>locations</span>\
  \ <span m='205140'>that</span> <span m='205280'>will</span> <span m='205390'>be</span>\
  \ <span m='205590'>accessed</span> <span m='206210'>over</span> <span m='206470'>a</span>\
  \ <span m='206500'>particular</span> <span m='207050'>span</span> <span m='207390'>of</span>\
  \ <span m='207480'>time.</span> </p><p><span m='208210'>What</span> <span m='208340'>we</span>\
  \ <span m='208450'>discover</span> <span m='208950'>when</span> <span m='209100'>we</span>\
  \ <span m='209190'>do</span> <span m='209400'>this</span> <span m='209760'>is</span>\
  \ <span m='209920'>the</span> <span m='210010'>notion</span> <span m='210340'>of</span>\
  \ <span m='210460'>a</span> <span m='210500'>\u201Cworking</span> <span m='210930'>set\u201D\
  </span> <span m='211200'>of</span> <span m='211320'>locations</span> <span m='212010'>that</span>\
  \ <span m='212210'>are</span> <span m='212350'>accessed</span> <span m='212880'>repeatedly.</span>\
  \ </p><p><span m='214690'>If</span> <span m='214830'>we</span> <span m='214940'>plot</span>\
  \ <span m='215360'>the</span> <span m='215450'>size</span> <span m='216060'>of</span>\
  \ <span m='216180'>the</span> <span m='216250'>working</span> <span m='216580'>set</span>\
  \ <span m='216860'>as</span> <span m='217030'>a</span> <span m='217070'>function</span>\
  \ <span m='217440'>of</span> <span m='217550'>the</span> <span m='217630'>size</span>\
  \ <span m='218100'>of</span> <span m='218170'>the</span> <span m='218270'>time</span>\
  \ <span m='218630'>interval,</span> <span m='219230'>we</span> <span m='219610'>see</span>\
  \ <span m='219830'>that</span> <span m='220010'>the</span> <span m='220100'>size</span>\
  \ <span m='220600'>of</span> <span m='220680'>the</span> <span m='220750'>working</span>\
  \ <span m='221110'>set</span> <span m='221440'>levels</span> <span m='221830'>off.</span>\
  \ </p><p><span m='222930'>In</span> <span m='223030'>other</span> <span m='223170'>words</span>\
  \ <span m='223690'>once</span> <span m='224300'>the</span> <span m='224390'>time</span>\
  \ <span m='224780'>interval</span> <span m='225100'>reaches</span> <span m='225470'>a</span>\
  \ <span m='225510'>certain</span> <span m='225820'>size</span> <span m='226490'>the</span>\
  \ <span m='226680'>number</span> <span m='227200'>of</span> <span m='227310'>locations</span>\
  \ <span m='227930'>accessed</span> <span m='228560'>is</span> <span m='228710'>approximately</span>\
  \ <span m='229380'>the</span> <span m='229470'>same</span> <span m='230120'>independent</span>\
  \ <span m='231200'>of</span> <span m='231490'>when</span> <span m='231960'>in</span>\
  \ <span m='232180'>time</span> <span m='232720'>the</span> <span m='232930'>interval</span>\
  \ <span m='233340'>occurs.</span> </p><p><span m='235420'>As</span> <span m='235600'>we</span>\
  \ <span m='235720'>see</span> <span m='236120'>in</span> <span m='236190'>our</span>\
  \ <span m='236300'>plot</span> <span m='236730'>to</span> <span m='236840'>the</span>\
  \ <span m='236940'>left,</span> <span m='237520'>the</span> <span m='237940'>actual</span>\
  \ <span m='238600'>addresses</span> <span m='239250'>accessed</span> <span m='239830'>will</span>\
  \ <span m='239940'>change,</span> <span m='240620'>but</span> <span m='240920'>the</span>\
  \ <span m='240990'>number</span> <span m='241370'>of</span> <span m='241590'>*different*</span>\
  \ <span m='242110'>addresses</span> <span m='242700'>during</span> <span m='243020'>the</span>\
  \ <span m='243090'>time</span> <span m='243430'>interval</span> <span m='243750'>will,</span>\
  \ <span m='244210'>on</span> <span m='244390'>the</span> <span m='244510'>average,</span>\
  \ <span m='244890'>remain</span> <span m='245350'>relatively</span> <span m='245840'>constant</span>\
  \ <span m='246620'>and,</span> <span m='247000'>surprisingly,</span> <span m='247880'>not</span>\
  \ <span m='248140'>all</span> <span m='248280'>that</span> <span m='248420'>large!</span>\
  \ </p><p><span m='250050'>This</span> <span m='250300'>means</span> <span m='250610'>that</span>\
  \ <span m='250740'>if</span> <span m='250860'>we</span> <span m='250950'>can</span>\
  \ <span m='251100'>arrange</span> <span m='251530'>for</span> <span m='251940'>our</span>\
  \ <span m='252080'>SRAM</span> <span m='252470'>to</span> <span m='252550'>be</span>\
  \ <span m='252710'>large</span> <span m='253050'>enough</span> <span m='253330'>to</span>\
  \ <span m='253450'>hold</span> <span m='253730'>the</span> <span m='253800'>working</span>\
  \ <span m='254220'>set</span> <span m='254480'>of</span> <span m='254620'>the</span>\
  \ <span m='254710'>program,</span> <span m='255560'>most</span> <span m='256310'>accesses</span>\
  \ <span m='256959'>will</span> <span m='257089'>be</span> <span m='257269'>able</span>\
  \ <span m='257410'>to</span> <span m='257500'>be</span> <span m='257640'>satisfied</span>\
  \ <span m='258529'>by</span> <span m='258670'>the</span> <span m='258880'>SRAM.</span>\
  \ </p><p><span m='260370'>We\u2019ll</span> <span m='260550'>occasionally</span>\
  \ <span m='261070'>have</span> <span m='261339'>to</span> <span m='261450'>move</span>\
  \ <span m='261760'>new</span> <span m='262029'>data</span> <span m='262400'>into</span>\
  \ <span m='262740'>the</span> <span m='262920'>SRAM</span> <span m='263470'>and</span>\
  \ <span m='263650'>old</span> <span m='263850'>data</span> <span m='264120'>back</span>\
  \ <span m='264490'>to</span> <span m='264620'>DRAM,</span> <span m='265500'>but</span>\
  \ <span m='265950'>the</span> <span m='266110'>DRAM</span> <span m='266630'>access</span>\
  \ <span m='267170'>will</span> <span m='267400'>occur</span> <span m='267760'>less</span>\
  \ <span m='268090'>frequently</span> <span m='268640'>than</span> <span m='268830'>SRAM</span>\
  \ <span m='269350'>accesses.</span> </p><p><span m='270960'>We\u2019ll</span> <span\
  \ m='271130'>work</span> <span m='271340'>out</span> <span m='271500'>the</span>\
  \ <span m='271590'>mathematics</span> <span m='272310'>in</span> <span m='272390'>a</span>\
  \ <span m='272430'>slide</span> <span m='272820'>or</span> <span m='272920'>two,</span>\
  \ <span m='273420'>but</span> <span m='273810'>you</span> <span m='273990'>can</span>\
  \ <span m='274120'>see</span> <span m='274370'>that</span> <span m='274540'>thanks</span>\
  \ <span m='274890'>to</span> <span m='275020'>locality</span> <span m='275600'>of</span>\
  \ <span m='275700'>reference</span> <span m='276390'>we\u2019re</span> <span m='276750'>on</span>\
  \ <span m='276880'>track</span> <span m='277340'>to</span> <span m='277440'>build</span>\
  \ <span m='277680'>a</span> <span m='277730'>memory</span> <span m='278200'>out</span>\
  \ <span m='278380'>of</span> <span m='278460'>a</span> <span m='278510'>combination</span>\
  \ <span m='279190'>of</span> <span m='279350'>SRAM</span> <span m='280020'>and</span>\
  \ <span m='280220'>DRAM</span> <span m='280970'>that</span> <span m='281270'>performs</span>\
  \ <span m='281780'>like</span> <span m='282010'>an</span> <span m='282200'>SRAM</span>\
  \ <span m='282770'>but</span> <span m='283050'>has</span> <span m='283310'>the</span>\
  \ <span m='283380'>capacity</span> <span m='284190'>of</span> <span m='284290'>the</span>\
  \ <span m='284360'>DRAM.</span> </p><p><span m='285790'>The</span> <span m='285940'>SRAM</span>\
  \ <span m='286370'>component</span> <span m='286930'>of</span> <span m='287170'>our</span>\
  \ <span m='287410'>hierarchical</span> <span m='288210'>memory</span> <span m='288600'>system</span>\
  \ <span m='289050'>is</span> <span m='289240'>called</span> <span m='289540'>a</span>\
  \ <span m='289590'>\u201Ccache\u201D.</span> </p><p><span m='291090'>It</span> <span\
  \ m='291190'>provides</span> <span m='291660'>low-latency</span> <span m='292490'>access</span>\
  \ <span m='293160'>to</span> <span m='293300'>recently-accessed</span> <span m='294340'>blocks</span>\
  \ <span m='294670'>of</span> <span m='294770'>data.</span> </p><p><span m='296130'>If</span>\
  \ <span m='296270'>the</span> <span m='296380'>requested</span> <span m='296970'>data</span>\
  \ <span m='297310'>is</span> <span m='297510'>in</span> <span m='297680'>the</span>\
  \ <span m='297750'>cache,</span> <span m='298360'>we</span> <span m='298650'>have</span>\
  \ <span m='298780'>a</span> <span m='298820'>\u201Ccache</span> <span m='299300'>hit\u201D\
  </span> <span m='299780'>and</span> <span m='300080'>the</span> <span m='300150'>data</span>\
  \ <span m='300540'>is</span> <span m='300680'>supplied</span> <span m='301260'>by</span>\
  \ <span m='301390'>the</span> <span m='301580'>SRAM.</span> </p><p><span m='303350'>If</span>\
  \ <span m='303460'>the</span> <span m='303540'>requested</span> <span m='304080'>data</span>\
  \ <span m='304390'>is</span> <span m='304640'>not</span> <span m='305020'>in</span>\
  \ <span m='305140'>the</span> <span m='305240'>cache,</span> <span m='305780'>we</span>\
  \ <span m='305990'>have</span> <span m='306140'>a</span> <span m='306180'>\u201C\
  cache</span> <span m='306630'>miss\u201D</span> <span m='307440'>and</span> <span\
  \ m='307810'>a</span> <span m='307850'>block</span> <span m='308210'>of</span> <span\
  \ m='308340'>data</span> <span m='308600'>containing</span> <span m='309110'>the</span>\
  \ <span m='309230'>requested</span> <span m='309720'>location</span> <span m='310230'>will</span>\
  \ <span m='310330'>have</span> <span m='310510'>to</span> <span m='310610'>be</span>\
  \ <span m='310750'>moved</span> <span m='311120'>from</span> <span m='311340'>DRAM</span>\
  \ <span m='311940'>into</span> <span m='312230'>the</span> <span m='312320'>cache.</span>\
  \ </p><p><span m='313980'>The</span> <span m='314060'>locality</span> <span m='314600'>principle</span>\
  \ <span m='315130'>tells</span> <span m='315490'>us</span> <span m='315680'>that</span>\
  \ <span m='315850'>we</span> <span m='315980'>should</span> <span m='316170'>expect</span>\
  \ <span m='316610'>cache</span> <span m='317020'>hits</span> <span m='317400'>to</span>\
  \ <span m='317570'>occur</span> <span m='317890'>much</span> <span m='318170'>more</span>\
  \ <span m='318330'>frequently</span> <span m='318940'>than</span> <span m='319160'>cache</span>\
  \ <span m='319600'>misses.</span> </p><p><span m='321820'>Modern</span> <span m='322150'>computer</span>\
  \ <span m='322520'>systems</span> <span m='322970'>often</span> <span m='323290'>use</span>\
  \ <span m='323510'>multiple</span> <span m='324080'>levels</span> <span m='324500'>of</span>\
  \ <span m='324600'>SRAM</span> <span m='325030'>caches.</span> </p><p><span m='326740'>The</span>\
  \ <span m='326850'>levels</span> <span m='327280'>closest</span> <span m='327820'>to</span>\
  \ <span m='328000'>the</span> <span m='328180'>CPU</span> <span m='328530'>are</span>\
  \ <span m='328640'>smaller</span> <span m='329180'>but</span> <span m='329350'>very</span>\
  \ <span m='329640'>fast,</span> <span m='330190'>while</span> <span m='330380'>the</span>\
  \ <span m='330470'>levels</span> <span m='330950'>further</span> <span m='331370'>away</span>\
  \ <span m='331540'>from</span> <span m='331830'>the</span> <span m='332010'>CPU</span>\
  \ <span m='332350'>are</span> <span m='332560'>larger</span> <span m='333070'>and</span>\
  \ <span m='333260'>hence</span> <span m='333560'>slower.</span> </p><p><span m='335330'>A</span>\
  \ <span m='335380'>miss</span> <span m='335690'>at</span> <span m='335780'>one</span>\
  \ <span m='336050'>level</span> <span m='336360'>of</span> <span m='336440'>the</span>\
  \ <span m='336500'>cache</span> <span m='336950'>generates</span> <span m='337420'>an</span>\
  \ <span m='337520'>access</span> <span m='338030'>to</span> <span m='338150'>the</span>\
  \ <span m='338250'>next</span> <span m='338550'>level,</span> <span m='339110'>and</span>\
  \ <span m='339470'>so</span> <span m='339720'>on</span> <span m='340100'>until</span>\
  \ <span m='340490'>a</span> <span m='340520'>DRAM</span> <span m='341080'>access</span>\
  \ <span m='341640'>is</span> <span m='341840'>needed</span> <span m='342130'>to</span>\
  \ <span m='342240'>satisfy</span> <span m='342870'>the</span> <span m='342980'>initial</span>\
  \ <span m='343310'>request.</span> </p><p><span m='345580'>Caching</span> <span\
  \ m='345990'>is</span> <span m='346160'>used</span> <span m='346550'>in</span> <span\
  \ m='346690'>many</span> <span m='346950'>applications</span> <span m='347780'>to</span>\
  \ <span m='347890'>speed</span> <span m='348200'>up</span> <span m='348380'>accesses</span>\
  \ <span m='349040'>to</span> <span m='349160'>frequently-accessed</span> <span m='350350'>data.</span>\
  \ </p><p><span m='351990'>For</span> <span m='352130'>example,</span> <span m='352660'>your</span>\
  \ <span m='352910'>browser</span> <span m='353350'>maintains</span> <span m='353880'>a</span>\
  \ <span m='353920'>cache</span> <span m='354360'>of</span> <span m='354420'>frequently-accessed</span>\
  \ <span m='355300'>web</span> <span m='355540'>pages</span> <span m='356210'>and</span>\
  \ <span m='356470'>uses</span> <span m='356860'>its</span> <span m='357020'>local</span>\
  \ <span m='357360'>copy</span> <span m='357750'>of</span> <span m='357820'>the</span>\
  \ <span m='357900'>web</span> <span m='358130'>page</span> <span m='358610'>if</span>\
  \ <span m='358790'>it</span> <span m='358880'>determines</span> <span m='359440'>the</span>\
  \ <span m='359600'>data</span> <span m='359910'>is</span> <span m='360040'>still</span>\
  \ <span m='360260'>valid,</span> <span m='361040'>avoiding</span> <span m='361840'>the</span>\
  \ <span m='361930'>delay</span> <span m='362370'>of</span> <span m='362490'>transferring</span>\
  \ <span m='363120'>the</span> <span m='363190'>data</span> <span m='363610'>over</span>\
  \ <span m='363880'>the</span> <span m='364000'>Internet.</span> </p><p><span m='365220'>Here\u2019\
  s</span> <span m='365450'>an</span> <span m='365530'>example</span> <span m='366040'>memory</span>\
  \ <span m='366410'>hierarchy</span> <span m='366960'>that</span> <span m='367120'>might</span>\
  \ <span m='367360'>be</span> <span m='367480'>found</span> <span m='367830'>on</span>\
  \ <span m='367930'>a</span> <span m='367990'>modern</span> <span m='368340'>computer.</span>\
  \ </p><p><span m='369430'>There</span> <span m='369560'>are</span> <span m='369700'>three</span>\
  \ <span m='370010'>levels</span> <span m='370530'>on-chip</span> <span m='371190'>SRAM</span>\
  \ <span m='371620'>caches,</span> <span m='372190'>followed</span> <span m='372510'>by</span>\
  \ <span m='372780'>DRAM</span> <span m='373420'>main</span> <span m='373660'>memory</span>\
  \ <span m='374310'>and</span> <span m='374620'>a</span> <span m='374670'>flash-memory</span>\
  \ <span m='375680'>cache</span> <span m='376240'>for</span> <span m='376360'>the</span>\
  \ <span m='376460'>hard</span> <span m='376730'>disk</span> <span m='377060'>drive.</span>\
  \ </p><p><span m='378430'>The</span> <span m='378490'>compiler</span> <span m='379140'>is</span>\
  \ <span m='379230'>responsible</span> <span m='379880'>for</span> <span m='380050'>deciding</span>\
  \ <span m='380460'>which</span> <span m='380700'>data</span> <span m='380920'>values</span>\
  \ <span m='381350'>are</span> <span m='381440'>kept</span> <span m='381770'>in</span>\
  \ <span m='382010'>the</span> <span m='382200'>CPU</span> <span m='382480'>registers</span>\
  \ <span m='383060'>and</span> <span m='383160'>which</span> <span m='383370'>values</span>\
  \ <span m='383750'>require</span> <span m='384170'>the</span> <span m='384250'>use</span>\
  \ <span m='384600'>of</span> <span m='384710'>LDs</span> <span m='385140'>and</span>\
  \ <span m='385270'>STs.</span> </p><p><span m='387220'>The</span> <span m='387380'>3-level</span>\
  \ <span m='387680'>cache</span> <span m='388170'>and</span> <span m='388270'>accesses</span>\
  \ <span m='388750'>to</span> <span m='388880'>DRAM</span> <span m='389370'>are</span>\
  \ <span m='389530'>managed</span> <span m='389880'>by</span> <span m='390000'>circuity</span>\
  \ <span m='390970'>in</span> <span m='391520'>the</span> <span m='391650'>memory</span>\
  \ <span m='392070'>system.</span> </p><p><span m='393190'>After</span> <span m='393480'>that</span>\
  \ <span m='393910'>the</span> <span m='394180'>access</span> <span m='394610'>times</span>\
  \ <span m='394950'>are</span> <span m='395080'>long</span> <span m='395340'>enough</span>\
  \ <span m='395810'>(many</span> <span m='396180'>hundreds</span> <span m='396580'>of</span>\
  \ <span m='396690'>instruction</span> <span m='397200'>times)</span> <span m='397840'>that</span>\
  \ <span m='398190'>the</span> <span m='398290'>job</span> <span m='398720'>of</span>\
  \ <span m='398800'>managing</span> <span m='399330'>the</span> <span m='399480'>movement</span>\
  \ <span m='399840'>of</span> <span m='399930'>data</span> <span m='400260'>between</span>\
  \ <span m='400760'>the</span> <span m='400840'>lower</span> <span m='401180'>levels</span>\
  \ <span m='401590'>of</span> <span m='401680'>the</span> <span m='401790'>hierarchy</span>\
  \ <span m='402380'>is</span> <span m='402560'>turned</span> <span m='402830'>over</span>\
  \ <span m='403070'>to</span> <span m='403170'>software.</span> </p><p><span m='405370'>Today</span>\
  \ <span m='405820'>we\u2019re</span> <span m='405970'>discussing</span> <span m='406590'>how</span>\
  \ <span m='406930'>the</span> <span m='407140'>on-chip</span> <span m='407640'>caches</span>\
  \ <span m='408140'>work.</span> </p><p><span m='409370'>In</span> <span m='409510'>Part</span>\
  \ <span m='409840'>3</span> <span m='410020'>of</span> <span m='410240'>the</span>\
  \ <span m='410300'>course,</span> <span m='410910'>we\u2019ll</span> <span m='411160'>discuss</span>\
  \ <span m='411690'>how</span> <span m='411930'>the</span> <span m='412020'>software</span>\
  \ <span m='412590'>manages</span> <span m='413130'>main</span> <span m='413430'>memory</span>\
  \ <span m='413940'>and</span> <span m='414080'>non-volatile</span> <span m='414900'>storage</span>\
  \ <span m='415300'>devices.</span> </p><p><span m='417240'>Whether</span> <span\
  \ m='417460'>managed</span> <span m='417890'>by</span> <span m='418030'>hardware</span>\
  \ <span m='418750'>or</span> <span m='418870'>software,</span> <span m='419480'>each</span>\
  \ <span m='419780'>layer</span> <span m='420040'>of</span> <span m='420120'>the</span>\
  \ <span m='420190'>memory</span> <span m='420520'>system</span> <span m='420880'>is</span>\
  \ <span m='420990'>designed</span> <span m='421530'>to</span> <span m='421590'>provide</span>\
  \ <span m='422200'>lower-latency</span> <span m='423240'>access</span> <span m='423810'>to</span>\
  \ <span m='423900'>frequently-accessed</span> <span m='424770'>locations</span>\
  \ <span m='425490'>in</span> <span m='425610'>the</span> <span m='425690'>next,</span>\
  \ <span m='426130'>slower</span> <span m='426680'>layer.</span> </p><p><span m='427570'>But,</span>\
  \ <span m='427880'>as</span> <span m='428140'>we\u2019ll</span> <span m='428270'>see,</span>\
  \ <span m='428610'>the</span> <span m='428790'>implementation</span> <span m='429410'>strategies</span>\
  \ <span m='429960'>will</span> <span m='430070'>be</span> <span m='430180'>quite</span>\
  \ <span m='430500'>different</span> <span m='430900'>in</span> <span m='431060'>the</span>\
  \ <span m='431130'>slower</span> <span m='431610'>layers</span> <span m='431920'>of</span>\
  \ <span m='432010'>the</span> <span m='432100'>hierarchy.</span> </p>"
type: course
uid: daef0d0ecf55da5d45b3d7557119137b

---
None