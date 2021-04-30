---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: VkVe_wNU6RI
  parent_uid: f93c4596226366f9e30f10f756afa8ce
  title: Video-YouTube-Stream
  type: Video
  uid: 194b614268b8e936f4241951d441edeb
- id: 3Play-3Play YouTube id-Stream
  media_location: VkVe_wNU6RI
  parent_uid: f93c4596226366f9e30f10f756afa8ce
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 36f9dce74e4ac8c0ec85cbe9107a34b3
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/VkVe_wNU6RI/default.jpg
  parent_uid: f93c4596226366f9e30f10f756afa8ce
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e48a00bdd6a95e717895bd2fcb17ad1b
- id: VkVe_wNU6RI.srt
  parent_uid: f93c4596226366f9e30f10f756afa8ce
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c5/c5s2/c5s2v4/d-register-timing-5-46-/VkVe_wNU6RI.srt
  title: 3play caption file
  type: null
  uid: ed48324d6edb80c041d1195277bac267
- id: VkVe_wNU6RI.pdf
  parent_uid: f93c4596226366f9e30f10f756afa8ce
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c5/c5s2/c5s2v4/d-register-timing-5-46-/VkVe_wNU6RI.pdf
  title: 3play pdf file
  type: null
  uid: 853561da66ba5e0683cf18d3874988f4
- id: Caption-3Play YouTube id-SRT
  parent_uid: f93c4596226366f9e30f10f756afa8ce
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: c6f54d8a5d95b6b3a06a148aad84d5e2
- id: Transcript-3Play YouTube id-PDF
  parent_uid: f93c4596226366f9e30f10f756afa8ce
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: c4232ce22437b39f29f30e23d782acec
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_05-02-04_300k.mp4
  parent_uid: f93c4596226366f9e30f10f756afa8ce
  title: Video-Internet Archive-MP4
  type: Video
  uid: be07b263bfebab7e1082d67263c2b59f
inline_embed_id: 44282803dregistertiming54622122707
layout: video
order_index: null
parent_uid: 2ed69bb560e57e9a9a1113c91d822fca
related_resources_text: ''
short_url: d-register-timing-5-46-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c5/c5s2/c5s2v4/d-register-timing-5-46-
template_type: Embed
title: D Register Timing (5:46)
transcript: "<p><span m='430'>We\u2019ll</span> <span m='1060'>get</span> <span m='1220'>a</span>\
  \ <span m='1270'>good</span> <span m='1490'>understanding</span> <span m='2260'>of</span>\
  \ <span m='2360'>how</span> <span m='2540'>the</span> <span m='2670'>register</span>\
  \ <span m='3150'>operates</span> <span m='3770'>as</span> <span m='3970'>we</span>\
  \ <span m='4120'>follow</span> <span m='4500'>the</span> <span m='4590'>signals</span>\
  \ <span m='5210'>through</span> <span m='5420'>the</span> <span m='5510'>circuit.</span>\
  \ </p><p><span m='7030'>The</span> <span m='7160'>overall</span> <span m='7650'>operation</span>\
  \ <span m='8200'>of</span> <span m='8270'>the</span> <span m='8370'>register</span>\
  \ <span m='8860'>is</span> <span m='8950'>simple:</span> </p><p><span m='9930'>At</span>\
  \ <span m='10040'>the</span> <span m='10130'>rising</span> <span m='10670'>0-to-1</span>\
  \ <span m='11160'>transition</span> <span m='11930'>of</span> <span m='12020'>the</span>\
  \ <span m='12110'>clock</span> <span m='12490'>input,</span> <span m='13120'>the</span>\
  \ <span m='13400'>register</span> <span m='13920'>samples</span> <span m='14390'>the</span>\
  \ <span m='14490'>value</span> <span m='14870'>of</span> <span m='14940'>the</span>\
  \ <span m='15070'>D</span> <span m='15370'>input</span> <span m='15770'>and</span>\
  \ <span m='15920'>stores</span> <span m='16379'>that</span> <span m='16620'>value</span>\
  \ <span m='17120'>until</span> <span m='17510'>the</span> <span m='17620'>next</span>\
  \ <span m='18090'>rising</span> <span m='18490'>clock</span> <span m='18850'>edge.</span>\
  \ </p><p><span m='20180'>The</span> <span m='20280'>Q</span> <span m='20570'>output</span>\
  \ <span m='20990'>is</span> <span m='21070'>simply</span> <span m='21410'>the</span>\
  \ <span m='21510'>value</span> <span m='21830'>stored</span> <span m='22200'>in</span>\
  \ <span m='22290'>the</span> <span m='22370'>register.</span> <span m='23360'>Let\u2019\
  s</span> <span m='24120'>see</span> <span m='24290'>how</span> <span m='24370'>the</span>\
  \ <span m='24470'>register</span> <span m='24950'>implements</span> <span m='25520'>this</span>\
  \ <span m='25720'>functionality.</span> </p><p><span m='27890'>The</span> <span\
  \ m='27970'>clock</span> <span m='28340'>signal</span> <span m='28770'>is</span>\
  \ <span m='28910'>connected</span> <span m='29410'>to</span> <span m='29530'>the</span>\
  \ <span m='29670'>gate</span> <span m='29950'>inputs</span> <span m='30430'>of</span>\
  \ <span m='30510'>the</span> <span m='30600'>master</span> <span m='31100'>and</span>\
  \ <span m='31220'>slave</span> <span m='31570'>latches.</span> </p><p><span m='32790'>Since</span>\
  \ <span m='33050'>all</span> <span m='33330'>the</span> <span m='33500'>action</span>\
  \ <span m='33870'>happens</span> <span m='34330'>when</span> <span m='34450'>the</span>\
  \ <span m='34520'>clock</span> <span m='34930'>makes</span> <span m='35150'>a</span>\
  \ <span m='35200'>transition,</span> <span m='36060'>it\u2019s</span> <span m='36460'>those</span>\
  \ <span m='36760'>events</span> <span m='37100'>we\u2019ll</span> <span m='37240'>focus</span>\
  \ <span m='37630'>on.</span> </p><p><span m='39010'>The</span> <span m='39090'>clock</span>\
  \ <span m='39390'>transition</span> <span m='39930'>from</span> <span m='40220'>LOW</span>\
  \ <span m='40560'>to</span> <span m='40660'>HIGH</span> <span m='41440'>is</span>\
  \ <span m='41810'>called</span> <span m='42160'>the</span> <span m='42240'>rising</span>\
  \ <span m='42730'>edge</span> <span m='42910'>of</span> <span m='42970'>the</span>\
  \ <span m='43060'>clock.</span> </p><p><span m='43920'>And</span> <span m='44030'>its</span>\
  \ <span m='44170'>transition</span> <span m='44670'>from</span> <span m='44860'>HIGH</span>\
  \ <span m='45240'>to</span> <span m='45370'>LOW</span> <span m='45700'>is</span>\
  \ <span m='45800'>called</span> <span m='46030'>the</span> <span m='46110'>falling</span>\
  \ <span m='46550'>edge.</span> </p><p><span m='47780'>Let\u2019s</span> <span m='47980'>start</span>\
  \ <span m='48310'>by</span> <span m='48440'>looking</span> <span m='48830'>the</span>\
  \ <span m='48980'>operation</span> <span m='49570'>of</span> <span m='49660'>the</span>\
  \ <span m='49750'>master</span> <span m='50200'>latch</span> <span m='50610'>and</span>\
  \ <span m='50770'>its</span> <span m='50970'>output</span> <span m='51350'>signal,</span>\
  \ <span m='51890'>which</span> <span m='52180'>is</span> <span m='52310'>labeled</span>\
  \ <span m='52630'>STAR</span> <span m='53320'>in</span> <span m='53460'>the</span>\
  \ <span m='53530'>diagram.</span> </p><p><span m='55540'>On</span> <span m='55650'>the</span>\
  \ <span m='55730'>rising</span> <span m='56140'>edge</span> <span m='56270'>of</span>\
  \ <span m='56330'>the</span> <span m='56410'>clock,</span> <span m='56800'>the</span>\
  \ <span m='56870'>master</span> <span m='57280'>latch</span> <span m='57620'>goes</span>\
  \ <span m='57850'>from</span> <span m='58060'>open</span> <span m='58410'>to</span>\
  \ <span m='58560'>closed,</span> <span m='59260'>sampling</span> <span m='59860'>the</span>\
  \ <span m='59930'>value</span> <span m='60260'>on</span> <span m='60410'>its</span>\
  \ <span m='60570'>input</span> <span m='61000'>and</span> <span m='61190'>entering</span>\
  \ <span m='61620'>memory</span> <span m='61970'>mode.</span> </p><p><span m='63120'>The</span>\
  \ <span m='63200'>sampled</span> <span m='63650'>value</span> <span m='64030'>thus</span>\
  \ <span m='64310'>becomes</span> <span m='64780'>the</span> <span m='64890'>output</span>\
  \ <span m='65220'>of</span> <span m='65300'>the</span> <span m='65360'>latch</span>\
  \ <span m='65770'>as</span> <span m='65930'>long</span> <span m='66200'>as</span>\
  \ <span m='66340'>the</span> <span m='66400'>latch</span> <span m='66740'>stays</span>\
  \ <span m='67110'>closed.</span> </p><p><span m='68460'>You</span> <span m='68530'>can</span>\
  \ <span m='68670'>see</span> <span m='68930'>that</span> <span m='69100'>the</span>\
  \ <span m='69170'>STAR</span> <span m='69520'>signal</span> <span m='69830'>remains</span>\
  \ <span m='70270'>stable</span> <span m='71040'>whenever</span> <span m='71590'>the</span>\
  \ <span m='71690'>clock</span> <span m='72110'>signal</span> <span m='72550'>is</span>\
  \ <span m='72690'>high.</span> </p><p><span m='74880'>On</span> <span m='75000'>the</span>\
  \ <span m='75070'>falling</span> <span m='75520'>edge</span> <span m='75680'>of</span>\
  \ <span m='75750'>the</span> <span m='75820'>clock</span> <span m='76350'>the</span>\
  \ <span m='76490'>master</span> <span m='76880'>latch</span> <span m='77220'>opens</span>\
  \ <span m='77840'>and</span> <span m='77990'>its</span> <span m='78140'>output</span>\
  \ <span m='78640'>will</span> <span m='78750'>then</span> <span m='78970'>reflect</span>\
  \ <span m='79560'>any</span> <span m='79770'>changes</span> <span m='80300'>in</span>\
  \ <span m='80410'>the</span> <span m='80510'>D</span> <span m='80810'>input,</span>\
  \ <span m='81440'>delayed</span> <span m='82190'>by</span> <span m='82360'>the</span>\
  \ <span m='82490'>tPD</span> <span m='83100'>of</span> <span m='83190'>the</span>\
  \ <span m='83250'>latch.</span> </p><p><span m='85210'>Now</span> <span m='85440'>let\u2019\
  s</span> <span m='85750'>figure</span> <span m='86070'>out</span> <span m='86240'>what</span>\
  \ <span m='86400'>the</span> <span m='86470'>slave</span> <span m='86870'>is</span>\
  \ <span m='87010'>doing.</span> </p><p><span m='88150'>It\u2019s</span> <span m='88360'>output</span>\
  \ <span m='88710'>signal,</span> <span m='89110'>which</span> <span m='89320'>also</span>\
  \ <span m='89690'>serves</span> <span m='90210'>as</span> <span m='90340'>the</span>\
  \ <span m='90480'>output</span> <span m='90920'>of</span> <span m='91000'>D</span>\
  \ <span m='91190'>register,</span> <span m='91930'>is</span> <span m='92190'>shown</span>\
  \ <span m='92580'>as</span> <span m='92790'>the</span> <span m='92870'>bottom</span>\
  \ <span m='93280'>waveform.</span> </p><p><span m='94440'>On</span> <span m='94540'>the</span>\
  \ <span m='94610'>rising</span> <span m='95090'>edge</span> <span m='95270'>of</span>\
  \ <span m='95340'>the</span> <span m='95430'>clock</span> <span m='95840'>the</span>\
  \ <span m='95980'>slave</span> <span m='96400'>latch</span> <span m='96720'>opens</span>\
  \ <span m='97250'>and</span> <span m='97370'>its</span> <span m='97540'>output</span>\
  \ <span m='98040'>will</span> <span m='98200'>follow</span> <span m='98570'>the</span>\
  \ <span m='98650'>value</span> <span m='99040'>of</span> <span m='99110'>the</span>\
  \ <span m='99190'>STAR</span> <span m='99480'>signal.</span> </p><p><span m='100750'>Remember</span>\
  \ <span m='101150'>though</span> <span m='101430'>that</span> <span m='101590'>the</span>\
  \ <span m='101660'>STAR</span> <span m='101950'>signal</span> <span m='102290'>is</span>\
  \ <span m='102370'>stable</span> <span m='102920'>while</span> <span m='103070'>the</span>\
  \ <span m='103160'>clock</span> <span m='103490'>is</span> <span m='103660'>HIGH</span>\
  \ <span m='103870'>since</span> <span m='104150'>the</span> <span m='104230'>master</span>\
  \ <span m='104670'>latch</span> <span m='104980'>is</span> <span m='105130'>closed,</span>\
  \ </p><p><span m='106210'>so</span> <span m='106370'>the</span> <span m='106460'>Q</span>\
  \ <span m='106700'>signal</span> <span m='107100'>is</span> <span m='107200'>also</span>\
  \ <span m='107590'>stable</span> <span m='108060'>after</span> <span m='108380'>an</span>\
  \ <span m='108440'>initial</span> <span m='108760'>transition</span> <span m='109530'>if</span>\
  \ <span m='109780'>value</span> <span m='110130'>saved</span> <span m='110610'>in</span>\
  \ <span m='110680'>the</span> <span m='110750'>slave</span> <span m='111090'>latch</span>\
  \ <span m='111420'>is</span> <span m='111530'>changing.</span> </p><p><span m='114060'>At</span>\
  \ <span m='114200'>the</span> <span m='114270'>falling</span> <span m='114700'>clock</span>\
  \ <span m='115070'>edge</span> <span m='115350'>[CLICK],</span> <span m='115500'>the</span>\
  \ <span m='115560'>slave</span> <span m='115930'>goes</span> <span m='116210'>from</span>\
  \ <span m='116480'>open</span> <span m='116930'>to</span> <span m='117160'>closed,</span>\
  \ <span m='117900'>sampling</span> <span m='118630'>the</span> <span m='118710'>value</span>\
  \ <span m='119060'>on</span> <span m='119180'>its</span> <span m='119360'>input</span>\
  \ <span m='119780'>and</span> <span m='119890'>entering</span> <span m='120240'>memory</span>\
  \ <span m='120580'>mode.</span> </p><p><span m='121550'>The</span> <span m='121610'>sampled</span>\
  \ <span m='122030'>value</span> <span m='122390'>then</span> <span m='122640'>becomes</span>\
  \ <span m='123120'>the</span> <span m='123290'>output</span> <span m='123840'>of</span>\
  \ <span m='123930'>the</span> <span m='124010'>slave</span> <span m='124400'>latch</span>\
  \ <span m='124740'>as</span> <span m='124860'>long</span> <span m='125080'>as</span>\
  \ <span m='125190'>the</span> <span m='125260'>latch</span> <span m='125630'>stays</span>\
  \ <span m='125970'>closed.</span> </p><p><span m='127260'>You</span> <span m='127370'>can</span>\
  \ <span m='127500'>see</span> <span m='127760'>that</span> <span m='127850'>that</span>\
  \ <span m='128009'>the</span> <span m='128139'>Q</span> <span m='128460'>output</span>\
  \ <span m='128880'>remains</span> <span m='129229'>stable</span> <span m='129720'>whenever</span>\
  \ <span m='130090'>the</span> <span m='130220'>clock</span> <span m='130560'>signal</span>\
  \ <span m='130960'>is</span> <span m='131100'>LOW.</span> </p><p><span m='132540'>Now</span>\
  \ <span m='132950'>let\u2019s</span> <span m='133300'>just</span> <span m='133650'>look</span>\
  \ <span m='133860'>at</span> <span m='133930'>the</span> <span m='134020'>Q</span>\
  \ <span m='134230'>signal</span> <span m='134560'>by</span> <span m='134620'>itself</span>\
  \ <span m='135110'>for</span> <span m='135260'>a</span> <span m='135290'>moment.</span>\
  \ </p><p><span m='136530'>It</span> <span m='136640'>only</span> <span m='136920'>changes</span>\
  \ <span m='137530'>when</span> <span m='137700'>the</span> <span m='137760'>slave</span>\
  \ <span m='138200'>latch</span> <span m='138560'>opens</span> <span m='139030'>at</span>\
  \ <span m='139090'>the</span> <span m='139180'>rising</span> <span m='139640'>edge</span>\
  \ <span m='139840'>of</span> <span m='139910'>the</span> <span m='139990'>clock.</span>\
  \ </p><p><span m='141340'>The</span> <span m='141430'>rest</span> <span m='141820'>of</span>\
  \ <span m='141900'>the</span> <span m='142000'>time</span> <span m='142440'>either</span>\
  \ <span m='142750'>the</span> <span m='142990'>input</span> <span m='143480'>to</span>\
  \ <span m='143620'>slave</span> <span m='144000'>latch</span> <span m='144320'>is</span>\
  \ <span m='144390'>stable</span> <span m='145090'>or</span> <span m='145350'>the</span>\
  \ <span m='145440'>slave</span> <span m='145880'>latch</span> <span m='146220'>is</span>\
  \ <span m='146350'>closed.</span> </p><p><span m='147720'>The</span> <span m='147810'>change</span>\
  \ <span m='148290'>in</span> <span m='148360'>the</span> <span m='148460'>Q</span>\
  \ <span m='148750'>output</span> <span m='149190'>is</span> <span m='149340'>triggered</span>\
  \ <span m='149670'>by</span> <span m='149800'>the</span> <span m='149900'>rising</span>\
  \ <span m='150460'>edge</span> <span m='150790'>of</span> <span m='150880'>the</span>\
  \ <span m='150960'>clock,</span> <span m='151500'>hence</span> <span m='152040'>the</span>\
  \ <span m='152130'>name</span> <span m='152540'>\u201Cpositive-edge-triggered</span>\
  \ <span m='153970'>D</span> <span m='154220'>register\u201D.</span> </p><p><span\
  \ m='155340'>The</span> <span m='155410'>convention</span> <span m='155920'>for</span>\
  \ <span m='156110'>labeling</span> <span m='156480'>the</span> <span m='156550'>clock</span>\
  \ <span m='156940'>input</span> <span m='157350'>in</span> <span m='157480'>the</span>\
  \ <span m='157540'>schematic</span> <span m='158100'>icon</span> <span m='158570'>for</span>\
  \ <span m='158740'>an</span> <span m='158830'>edge-triggered</span> <span m='159370'>device</span>\
  \ <span m='159860'>is</span> <span m='160000'>to</span> <span m='160100'>use</span>\
  \ <span m='160400'>a</span> <span m='160480'>little</span> <span m='160700'>triangle.</span>\
  \ </p><p><span m='161780'>You</span> <span m='161840'>can</span> <span m='161930'>see</span>\
  \ <span m='162090'>that</span> <span m='162340'>here</span> <span m='162810'>in</span>\
  \ <span m='162920'>the</span> <span m='162980'>schematic</span> <span m='163490'>symbol</span>\
  \ <span m='163810'>for</span> <span m='163940'>the</span> <span m='164030'>D</span>\
  \ <span m='164230'>register.</span> </p><p><span m='165650'>There</span> <span m='165850'>is</span>\
  \ <span m='166120'>one</span> <span m='166420'>tricky</span> <span m='166770'>problem</span>\
  \ <span m='167160'>we</span> <span m='167300'>have</span> <span m='167490'>to</span>\
  \ <span m='167590'>solve</span> <span m='167980'>when</span> <span m='168140'>designing</span>\
  \ <span m='168630'>the</span> <span m='168700'>circuitry</span> <span m='169240'>for</span>\
  \ <span m='169370'>the</span> <span m='169490'>register.</span> </p><p><span m='170880'>On</span>\
  \ <span m='170990'>the</span> <span m='171080'>falling</span> <span m='171510'>clock</span>\
  \ <span m='171850'>edge,</span> <span m='172150'>the</span> <span m='172240'>slave</span>\
  \ <span m='172590'>latch</span> <span m='172860'>transitions</span> <span m='173440'>from</span>\
  \ <span m='173630'>open</span> <span m='173940'>to</span> <span m='174030'>closed</span>\
  \ <span m='174540'>and</span> <span m='174750'>so</span> <span m='175030'>its</span>\
  \ <span m='175200'>input</span> <span m='175720'>(the</span> <span m='175920'>STAR</span>\
  \ <span m='176190'>signal)</span> <span m='176760'>must</span> <span m='177090'>meet</span>\
  \ <span m='177240'>the</span> <span m='177310'>setup</span> <span m='177720'>and</span>\
  \ <span m='177850'>hold</span> <span m='178090'>times</span> <span m='178580'>of</span>\
  \ <span m='178660'>the</span> <span m='178740'>slave</span> <span m='179120'>latch</span>\
  \ <span m='179460'>in</span> <span m='179550'>order</span> <span m='179920'>to</span>\
  \ <span m='180180'>ensure</span> <span m='180550'>correct</span> <span m='180970'>operation.</span>\
  \ </p><p><span m='181990'>The</span> <span m='182050'>complication</span> <span\
  \ m='182800'>is</span> <span m='182930'>that</span> <span m='183070'>the</span>\
  \ <span m='183140'>master</span> <span m='183640'>latch</span> <span m='183910'>opens</span>\
  \ <span m='184340'>at</span> <span m='184400'>the</span> <span m='184490'>same</span>\
  \ <span m='184790'>time,</span> <span m='185310'>so</span> <span m='185680'>the</span>\
  \ <span m='185780'>STAR</span> <span m='186150'>signal</span> <span m='186510'>may</span>\
  \ <span m='186690'>change</span> <span m='187150'>shortly</span> <span m='187620'>after</span>\
  \ <span m='187840'>the</span> <span m='187930'>clock</span> <span m='188300'>edge.</span>\
  \ </p><p><span m='190110'>The</span> <span m='190180'>contamination</span> <span\
  \ m='190950'>delay</span> <span m='191250'>of</span> <span m='191330'>the</span>\
  \ <span m='191420'>master</span> <span m='191890'>latch</span> <span m='192200'>tells</span>\
  \ <span m='192460'>us</span> <span m='192600'>how</span> <span m='192760'>long</span>\
  \ <span m='193230'>the</span> <span m='193360'>old</span> <span m='193550'>value</span>\
  \ <span m='193900'>will</span> <span m='194220'>be</span> <span m='194350'>stable</span>\
  \ <span m='194850'>after</span> <span m='195300'>the</span> <span m='195390'>falling</span>\
  \ <span m='195660'>clock</span> <span m='196020'>edge.</span> </p><p><span m='197230'>And</span>\
  \ <span m='197330'>the</span> <span m='197440'>hold</span> <span m='197710'>time</span>\
  \ <span m='197970'>on</span> <span m='198060'>the</span> <span m='198120'>slave</span>\
  \ <span m='198520'>latch</span> <span m='198900'>tells</span> <span m='199220'>us</span>\
  \ <span m='199590'>how</span> <span m='199870'>long</span> <span m='200210'>it</span>\
  \ <span m='200280'>has</span> <span m='200600'>to</span> <span m='200680'>remain</span>\
  \ <span m='201090'>stable</span> <span m='201620'>after</span> <span m='201880'>the</span>\
  \ <span m='201980'>falling</span> <span m='202290'>clock</span> <span m='202600'>edge.</span>\
  \ </p><p><span m='204010'>So</span> <span m='204210'>to</span> <span m='204390'>ensure</span>\
  \ <span m='204790'>correct</span> <span m='205230'>operation</span> <span m='205820'>of</span>\
  \ <span m='205890'>the</span> <span m='205980'>slave</span> <span m='206480'>latch,</span>\
  \ <span m='207060'>the</span> <span m='207400'>contamination</span> <span m='208260'>delay</span>\
  \ <span m='208630'>of</span> <span m='208720'>the</span> <span m='208800'>master</span>\
  \ <span m='209260'>latch</span> <span m='209620'>has</span> <span m='209820'>to</span>\
  \ <span m='209920'>be</span> <span m='210100'>greater</span> <span m='210440'>than</span>\
  \ <span m='210650'>or</span> <span m='210760'>equal</span> <span m='211080'>to</span>\
  \ <span m='211250'>the</span> <span m='211380'>hold</span> <span m='211690'>time</span>\
  \ <span m='212110'>of</span> <span m='212190'>the</span> <span m='212270'>slave</span>\
  \ <span m='212640'>latch.</span> </p><p><span m='214260'>Doing</span> <span m='214500'>the</span>\
  \ <span m='214590'>necessary</span> <span m='215170'>analysis</span> <span m='215730'>can</span>\
  \ <span m='215840'>be</span> <span m='215980'>a</span> <span m='216010'>bit</span>\
  \ <span m='216220'>tricky</span> <span m='216640'>since</span> <span m='216870'>we</span>\
  \ <span m='217000'>have</span> <span m='217220'>to</span> <span m='217330'>consider</span>\
  \ <span m='217780'>manufacturing</span> <span m='218530'>variations</span> <span\
  \ m='219370'>as</span> <span m='219630'>well</span> <span m='219840'>as</span> <span\
  \ m='219960'>environmental</span> <span m='220670'>factors</span> <span m='221450'>such</span>\
  \ <span m='221870'>as</span> <span m='222020'>temperature</span> <span m='222510'>and</span>\
  \ <span m='222610'>power</span> <span m='222910'>supply</span> <span m='223250'>voltage.</span>\
  \ </p><p><span m='224800'>If</span> <span m='224940'>necessary,</span> <span m='225720'>extra</span>\
  \ <span m='226120'>gate</span> <span m='226340'>delays</span> <span m='227110'>(e.g.,</span>\
  \ <span m='227700'>pairs</span> <span m='228140'>of</span> <span m='228230'>inverters)</span>\
  \ <span m='229090'>can</span> <span m='229600'>be</span> <span m='229820'>added</span>\
  \ <span m='230160'>between</span> <span m='230560'>the</span> <span m='230660'>master</span>\
  \ <span m='231150'>and</span> <span m='231240'>slave</span> <span m='231620'>latches</span>\
  \ <span m='232050'>to</span> <span m='232220'>increase</span> <span m='232590'>the</span>\
  \ <span m='232680'>contamination</span> <span m='233510'>delay</span> <span m='233850'>on</span>\
  \ <span m='233960'>the</span> <span m='234020'>slave\u2019s</span> <span m='234440'>input</span>\
  \ <span m='234990'>relative</span> <span m='235560'>to</span> <span m='235670'>the</span>\
  \ <span m='235760'>falling</span> <span m='236090'>clock</span> <span m='236430'>edge.</span>\
  \ </p><p><span m='237090'>Note</span> <span m='237340'>that</span> <span m='237510'>we</span>\
  \ <span m='237580'>can</span> <span m='237760'>only</span> <span m='238090'>solve</span>\
  \ <span m='238430'>slave</span> <span m='238810'>latch</span> <span m='239150'>hold</span>\
  \ <span m='239420'>time</span> <span m='239650'>issues</span> <span m='239960'>by</span>\
  \ <span m='240140'>changing</span> <span m='240670'>the</span> <span m='240750'>design</span>\
  \ <span m='241230'>of</span> <span m='241310'>the</span> <span m='241390'>circuit.</span>\
  \ </p><p><span m='242720'>Here\u2019s</span> <span m='242960'>a</span> <span m='242990'>summary</span>\
  \ <span m='243520'>of</span> <span m='243640'>the</span> <span m='243730'>timing</span>\
  \ <span m='244120'>specifications</span> <span m='244940'>for</span> <span m='245190'>a</span>\
  \ <span m='245220'>D</span> <span m='245440'>register.</span> </p><p><span m='246780'>Changes</span>\
  \ <span m='247290'>in</span> <span m='247390'>the</span> <span m='247450'>Q</span>\
  \ <span m='247720'>signal</span> <span m='248200'>are</span> <span m='248310'>triggered</span>\
  \ <span m='248780'>by</span> <span m='248920'>a</span> <span m='248950'>rising</span>\
  \ <span m='249440'>edge</span> <span m='249700'>on</span> <span m='249780'>the</span>\
  \ <span m='249850'>clock</span> <span m='250240'>input.</span> </p><p><span m='251500'>The</span>\
  \ <span m='251580'>propagation</span> <span m='252260'>delay</span> <span m='252680'>t_PD</span>\
  \ <span m='253380'>of</span> <span m='253470'>the</span> <span m='253560'>register</span>\
  \ <span m='254090'>is</span> <span m='254210'>an</span> <span m='254350'>upper</span>\
  \ <span m='254630'>bound</span> <span m='255050'>on</span> <span m='255150'>the</span>\
  \ <span m='255220'>time</span> <span m='255540'>it</span> <span m='255620'>takes</span>\
  \ <span m='255910'>for</span> <span m='256120'>the</span> <span m='256250'>Q</span>\
  \ <span m='256570'>output</span> <span m='257060'>to</span> <span m='257180'>become</span>\
  \ <span m='257579'>valid</span> <span m='257990'>and</span> <span m='258120'>stable</span>\
  \ <span m='258930'>after</span> <span m='259550'>the</span> <span m='259630'>rising</span>\
  \ <span m='260000'>clock</span> <span m='260329'>edge.</span> </p><p><span m='261190'>The</span>\
  \ <span m='261260'>contamination</span> <span m='262029'>delay</span> <span m='262280'>of</span>\
  \ <span m='262350'>the</span> <span m='262450'>register</span> <span m='263180'>is</span>\
  \ <span m='263510'>a</span> <span m='263540'>lower</span> <span m='263880'>bound</span>\
  \ <span m='264220'>on</span> <span m='264320'>the</span> <span m='264390'>time</span>\
  \ <span m='264690'>the</span> <span m='264780'>previous</span> <span m='265340'>value</span>\
  \ <span m='265670'>of</span> <span m='265750'>Q</span> <span m='266040'>remains</span>\
  \ <span m='266440'>valid</span> <span m='266810'>after</span> <span m='267070'>the</span>\
  \ <span m='267150'>rising</span> <span m='267500'>clock</span> <span m='267810'>edge.</span>\
  \ </p><p><span m='269500'>Note</span> <span m='269740'>that</span> <span m='269930'>both</span>\
  \ <span m='270350'>t_CD</span> <span m='271110'>and</span> <span m='271340'>t_PD</span>\
  \ <span m='272110'>are</span> <span m='272260'>measured</span> <span m='272720'>relative</span>\
  \ <span m='273210'>to</span> <span m='273320'>the</span> <span m='273410'>rising</span>\
  \ <span m='273860'>edge</span> <span m='274010'>of</span> <span m='274090'>the</span>\
  \ <span m='274160'>clock.</span> </p><p><span m='275670'>Registers</span> <span\
  \ m='276210'>are</span> <span m='276300'>designed</span> <span m='276760'>to</span>\
  \ <span m='276830'>be</span> <span m='277010'>lenient</span> <span m='277520'>in</span>\
  \ <span m='277620'>the</span> <span m='277710'>sense</span> <span m='278100'>that</span>\
  \ <span m='278330'>if</span> <span m='278750'>the</span> <span m='278980'>previous</span>\
  \ <span m='279550'>value</span> <span m='279940'>of</span> <span m='280050'>Q</span>\
  \ <span m='280500'>and</span> <span m='280730'>the</span> <span m='280830'>new</span>\
  \ <span m='281100'>value</span> <span m='281530'>of</span> <span m='281630'>Q</span>\
  \ <span m='281900'>are</span> <span m='281990'>the</span> <span m='282080'>same,</span>\
  \ <span m='282890'>the</span> <span m='283310'>stability</span> <span m='283940'>of</span>\
  \ <span m='284020'>the</span> <span m='284100'>Q</span> <span m='284350'>signal</span>\
  \ <span m='284780'>is</span> <span m='284960'>guaranteed</span> <span m='285780'>during</span>\
  \ <span m='286160'>the</span> <span m='286220'>rising</span> <span m='286590'>clock</span>\
  \ <span m='286940'>edge.</span> </p><p><span m='287980'>In</span> <span m='288060'>other</span>\
  \ <span m='288230'>words,</span> <span m='288520'>the</span> <span m='288620'>t_CD</span>\
  \ <span m='289420'>and</span> <span m='289540'>t_PD</span> <span m='290150'>specifications</span>\
  \ <span m='291080'>only</span> <span m='291390'>apply</span> <span m='291930'>when</span>\
  \ <span m='292140'>the</span> <span m='292230'>Q</span> <span m='292560'>output</span>\
  \ <span m='293130'>actually</span> <span m='293640'>changes.</span> </p><p><span\
  \ m='295760'>In</span> <span m='295840'>order</span> <span m='296090'>to</span>\
  \ <span m='296280'>ensure</span> <span m='296680'>correct</span> <span m='297060'>operation</span>\
  \ <span m='297720'>of</span> <span m='297830'>the</span> <span m='297900'>master</span>\
  \ <span m='298340'>latch,</span> <span m='298960'>the</span> <span m='299260'>register\u2019\
  s</span> <span m='299860'>D</span> <span m='300190'>input</span> <span m='300570'>must</span>\
  \ <span m='300840'>meet</span> <span m='301040'>the</span> <span m='301140'>setup</span>\
  \ <span m='301560'>and</span> <span m='301670'>hold</span> <span m='301900'>time</span>\
  \ <span m='302140'>constraints</span> <span m='302720'>for</span> <span m='302830'>the</span>\
  \ <span m='302910'>master</span> <span m='303300'>latch.</span> </p><p><span m='304250'>So</span>\
  \ <span m='304660'>the</span> <span m='305110'>following</span> <span m='305690'>two</span>\
  \ <span m='306030'>specifications</span> <span m='306990'>are</span> <span m='307060'>determined</span>\
  \ <span m='307660'>by</span> <span m='307810'>the</span> <span m='307910'>timing</span>\
  \ <span m='308390'>of</span> <span m='308470'>the</span> <span m='308550'>master</span>\
  \ <span m='308910'>latch.</span> </p><p><span m='310270'>t_SETUP</span> <span m='310910'>is</span>\
  \ <span m='311110'>the</span> <span m='311260'>amount</span> <span m='311540'>of</span>\
  \ <span m='311650'>time</span> <span m='312010'>that</span> <span m='312140'>the</span>\
  \ <span m='312240'>D</span> <span m='312600'>input</span> <span m='312920'>must</span>\
  \ <span m='313170'>be</span> <span m='313320'>valid</span> <span m='313720'>and</span>\
  \ <span m='313820'>stable</span> <span m='314310'>before</span> <span m='314650'>the</span>\
  \ <span m='314760'>rising</span> <span m='315080'>clock</span> <span m='315400'>edge</span>\
  \ <span m='315900'>and</span> <span m='316320'>t_HOLD</span> <span m='316620'>is</span>\
  \ <span m='316740'>the</span> <span m='316860'>amount</span> <span m='317090'>of</span>\
  \ <span m='317190'>time</span> <span m='317480'>that</span> <span m='317600'>D</span>\
  \ <span m='317810'>must</span> <span m='318060'>be</span> <span m='318180'>valid</span>\
  \ <span m='318560'>and</span> <span m='318650'>stable</span> <span m='319120'>after</span>\
  \ <span m='319460'>the</span> <span m='319570'>rising</span> <span m='319880'>clock.</span>\
  \ </p><p><span m='321640'>This</span> <span m='321860'>region</span> <span m='322170'>of</span>\
  \ <span m='322240'>stability</span> <span m='322790'>surrounding</span> <span m='323350'>the</span>\
  \ <span m='323410'>clock</span> <span m='323840'>edge</span> <span m='324410'>ensures</span>\
  \ <span m='325290'>that</span> <span m='325430'>we\u2019re</span> <span m='325680'>obeying</span>\
  \ <span m='326150'>the</span> <span m='326300'>dynamic</span> <span m='326890'>discipline</span>\
  \ <span m='327420'>for</span> <span m='327550'>the</span> <span m='327650'>master</span>\
  \ <span m='328080'>latch.</span> </p><p><span m='329630'>So</span> <span m='330100'>when</span>\
  \ <span m='330490'>you</span> <span m='330580'>use</span> <span m='330960'>a</span>\
  \ <span m='331020'>D</span> <span m='331240'>register</span> <span m='331750'>component</span>\
  \ <span m='332230'>from</span> <span m='332420'>a</span> <span m='332470'>manufacturer\u2019\
  s</span> <span m='333280'>gate</span> <span m='333510'>library,</span> </p><p><span\
  \ m='334440'>you\u2019ll</span> <span m='334580'>need</span> <span m='334750'>to</span>\
  \ <span m='334810'>look</span> <span m='335090'>up</span> <span m='335260'>these</span>\
  \ <span m='335510'>four</span> <span m='335790'>timing</span> <span m='336190'>specifications</span>\
  \ <span m='337090'>in</span> <span m='337170'>the</span> <span m='337260'>register\u2019\
  s</span> <span m='337840'>data</span> <span m='338070'>sheet</span> <span m='338620'>in</span>\
  \ <span m='338980'>order</span> <span m='339270'>to</span> <span m='339480'>analyze</span>\
  \ <span m='340060'>the</span> <span m='340140'>timing</span> <span m='340660'>of</span>\
  \ <span m='340750'>your</span> <span m='340940'>overall</span> <span m='341350'>circuit.</span>\
  \ </p><p><span m='342590'>We\u2019ll</span> <span m='342700'>see</span> <span m='342880'>how</span>\
  \ <span m='343060'>this</span> <span m='343330'>analysis</span> <span m='343880'>is</span>\
  \ <span m='344050'>done</span> <span m='344470'>in</span> <span m='344650'>the</span>\
  \ <span m='344730'>next</span> <span m='344980'>section.</span> </p>"
type: course
uid: f93c4596226366f9e30f10f756afa8ce

---
None