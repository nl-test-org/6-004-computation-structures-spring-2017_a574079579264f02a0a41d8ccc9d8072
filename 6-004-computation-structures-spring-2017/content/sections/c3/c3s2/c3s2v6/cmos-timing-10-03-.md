---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: br3mu-IK9N8
  parent_uid: 2f62f1c167e6628a2ac9f07689d2bf9f
  title: Video-YouTube-Stream
  type: Video
  uid: 546a5759a07ed47879bbd687b7b3f90a
- id: 3Play-3Play YouTube id-Stream
  media_location: br3mu-IK9N8
  parent_uid: 2f62f1c167e6628a2ac9f07689d2bf9f
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 004efd299203b163609f665aeb888461
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/br3mu-IK9N8/default.jpg
  parent_uid: 2f62f1c167e6628a2ac9f07689d2bf9f
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 2d16500302d9b9dc479c4f3685f3d2b0
- id: br3mu-IK9N8.srt
  parent_uid: 2f62f1c167e6628a2ac9f07689d2bf9f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c3/c3s2/c3s2v6/cmos-timing-10-03-/br3mu-IK9N8.srt
  title: 3play caption file
  type: null
  uid: 94df736128cbdf7a6c17f7f44bb091e1
- id: br3mu-IK9N8.pdf
  parent_uid: 2f62f1c167e6628a2ac9f07689d2bf9f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c3/c3s2/c3s2v6/cmos-timing-10-03-/br3mu-IK9N8.pdf
  title: 3play pdf file
  type: null
  uid: 9a58d3b0f6645baea83f34174a064b12
- id: Caption-3Play YouTube id-SRT
  parent_uid: 2f62f1c167e6628a2ac9f07689d2bf9f
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: e5f48e51e0c9c2d4697096deb0379994
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 2f62f1c167e6628a2ac9f07689d2bf9f
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 3d8248b9bc4c8976d1280b8fd7025eab
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_03-02-06_300k.mp4
  parent_uid: 2f62f1c167e6628a2ac9f07689d2bf9f
  title: Video-Internet Archive-MP4
  type: Video
  uid: 834cf55e04a4cba0873c5216aab3a82d
inline_embed_id: 57813340cmostiming100347664279
layout: video
order_index: null
parent_uid: 9d32f855cfa88a03c098513a5550ac7c
related_resources_text: ''
short_url: cmos-timing-10-03-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c3/c3s2/c3s2v6/cmos-timing-10-03-
template_type: Embed
title: CMOS Timing (10:03)
transcript: <p><span m='1310'>Okay,</span> <span m='1652'>now</span> <span m='1994'>that</span>
  <span m='2336'>we</span> <span m='2678'>understand</span> <span m='3020'>how</span>
  <span m='3362'>to</span> <span m='3705'>build</span> <span m='4047'>combinational</span>
  <span m='4389'>logic</span> <span m='4731'>gates</span> <span m='5073'>using</span>
  <span m='5415'>CMOS,</span> <span m='5757'>let's</span> <span m='6100'>turn</span>
  <span m='6541'>our</span> <span m='6982'>attention</span> <span m='7423'>to</span>
  <span m='7864'>the</span> <span m='8305'>timing</span> <span m='8746'>specifications</span>
  <span m='9187'>for</span> <span m='9628'>the</span> <span m='10069'>gates.</span>
  </p><p><span m='10510'>Here's</span> <span m='10889'>a</span> <span m='11268'>simple</span>
  <span m='11647'>circuit</span> <span m='12026'>consisting</span> <span m='12406'>of</span>
  <span m='12785'>two</span> <span m='13164'>CMOS</span> <span m='13543'>inverters</span>
  <span m='13923'>connected</span> <span m='14302'>in</span> <span m='14681'>series,</span>
  <span m='15060'>which</span> <span m='15440'>we'll</span> <span m='15766'>use</span>
  <span m='16093'>to</span> <span m='16420'>understand</span> <span m='16746'>how</span>
  <span m='17073'>to</span> <span m='17400'>characterize</span> <span m='17726'>the</span>
  <span m='18053'>timing</span> <span m='18380'>of</span> <span m='18706'>the</span>
  <span m='19033'>inverter</span> <span m='19360'>on</span> <span m='19686'>the</span>
  <span m='20013'>left.</span> </p><p><span m='20340'>It</span> <span m='20624'>will</span>
  <span m='20908'>be</span> <span m='21193'>helpful</span> <span m='21477'>to</span>
  <span m='21761'>build</span> <span m='22046'>an</span> <span m='22330'>electrical</span>
  <span m='22615'>model</span> <span m='22899'>of</span> <span m='23183'>what</span>
  <span m='23468'>happens</span> <span m='23752'>when</span> <span m='24036'>we</span>
  <span m='24321'>change</span> <span m='24605'>V_IN,</span> <span m='24890'>the</span>
  <span m='25352'>voltage</span> <span m='25814'>on</span> <span m='26276'>the</span>
  <span m='26738'>input</span> <span m='27201'>to</span> <span m='27663'>the</span>
  <span m='28125'>left</span> <span m='28587'>inverter.</span> </p><p><span m='29050'>If</span>
  <span m='29337'>V_IN</span> <span m='29625'>makes</span> <span m='29913'>a</span>
  <span m='30201'>transition</span> <span m='30489'>from</span> <span m='30777'>a</span>
  <span m='31065'>digital</span> <span m='31353'>0</span> <span m='31641'>to</span>
  <span m='31928'>a</span> <span m='32216'>digital</span> <span m='32504'>1,</span>
  <span m='32792'>the</span> <span m='33080'>PFET</span> <span m='33368'>switch</span>
  <span m='33656'>in</span> <span m='33944'>the</span> <span m='34232'>pullup</span>
  <span m='34520'>turns</span> <span m='34873'>off</span> <span m='35227'>and</span>
  <span m='35581'>the</span> <span m='35935'>NFET</span> <span m='36288'>switch</span>
  <span m='36642'>in</span> <span m='36996'>pulldown</span> <span m='37350'>turns</span>
  <span m='37703'>on,</span> <span m='38057'>connecting</span> <span m='38411'>the</span>
  <span m='38765'>output</span> <span m='39118'>node</span> <span m='39472'>of</span>
  <span m='39826'>the</span> <span m='40180'>left</span> <span m='40960'>inverter</span>
  <span m='41740'>to</span> <span m='42520'>GROUND.</span> </p><p><span m='43300'>The</span>
  <span m='43656'>electrical</span> <span m='44013'>model</span> <span m='44370'>for</span>
  <span m='44726'>this</span> <span m='45083'>node</span> <span m='45440'>includes</span>
  <span m='45796'>the</span> <span m='46153'>distributed</span> <span m='46510'>resistance</span>
  <span m='46866'>and</span> <span m='47223'>capacitance</span> <span m='47580'>of</span>
  <span m='47850'>the</span> <span m='48120'>physical</span> <span m='48390'>wire</span>
  <span m='48660'>connecting</span> <span m='48930'>the</span> <span m='49200'>output</span>
  <span m='49470'>of</span> <span m='49740'>the</span> <span m='50010'>left</span>
  <span m='50280'>inverter</span> <span m='50550'>to</span> <span m='50820'>the</span>
  <span m='51090'>input</span> <span m='51360'>of</span> <span m='51630'>the</span>
  <span m='51900'>right</span> <span m='52170'>inverter.</span> </p><p><span m='53450'>And</span>
  <span m='53731'>there</span> <span m='54013'>is</span> <span m='54295'>also</span>
  <span m='54577'>capacitance</span> <span m='54859'>associated</span> <span m='55141'>with</span>
  <span m='55423'>the</span> <span m='55705'>gate</span> <span m='55986'>terminals</span>
  <span m='56268'>of</span> <span m='56550'>the</span> <span m='56832'>MOSFETs</span>
  <span m='57114'>in</span> <span m='57396'>the</span> <span m='57678'>right</span>
  <span m='57960'>inverter.</span> </p><p><span m='59960'>When</span> <span m='60272'>the</span>
  <span m='60584'>output</span> <span m='60897'>node</span> <span m='61209'>is</span>
  <span m='61522'>connected</span> <span m='61834'>to</span> <span m='62147'>GROUND,</span>
  <span m='62459'>the</span> <span m='62771'>charge</span> <span m='63084'>on</span>
  <span m='63396'>this</span> <span m='63709'>capacitance</span> <span m='64021'>will</span>
  <span m='64334'>flow</span> <span m='64646'>towards</span> <span m='64959'>the</span>
  <span m='65254'>GROUND</span> <span m='65549'>connection</span> <span m='65845'>through</span>
  <span m='66140'>the</span> <span m='66436'>resistance</span> <span m='66731'>of</span>
  <span m='67026'>the</span> <span m='67322'>wire</span> <span m='67617'>and</span>
  <span m='67913'>the</span> <span m='68208'>resistance</span> <span m='68503'>of</span>
  <span m='68799'>the</span> <span m='69094'>conducting</span> <span m='69390'>channel</span>
  <span m='69940'>of</span> <span m='70490'>the</span> <span m='71040'>NFET</span>
  <span m='71590'>pulldown</span> <span m='72140'>switch.</span> </p><p><span m='72690'>Eventually</span>
  <span m='73078'>the</span> <span m='73467'>voltage</span> <span m='73856'>on</span>
  <span m='74244'>the</span> <span m='74633'>wire</span> <span m='75022'>will</span>
  <span m='75410'>reach</span> <span m='75799'>the</span> <span m='76188'>potential</span>
  <span m='76576'>of</span> <span m='76965'>the</span> <span m='77354'>GROUND</span>
  <span m='77742'>connection,</span> <span m='78131'>0V.</span> </p><p><span m='78520'>The</span>
  <span m='78814'>process</span> <span m='79108'>is</span> <span m='79403'>much</span>
  <span m='79697'>the</span> <span m='79991'>same</span> <span m='80286'>for</span>
  <span m='80580'>falling</span> <span m='80875'>transitions</span> <span m='81169'>on</span>
  <span m='81463'>V_IN,</span> <span m='81758'>which</span> <span m='82052'>cause</span>
  <span m='82347'>the</span> <span m='82641'>output</span> <span m='82935'>node</span>
  <span m='83230'>to</span> <span m='83524'>charge</span> <span m='83819'>up</span>
  <span m='84819'>to</span> <span m='85819'>V_DD.</span> </p><p><span m='86820'>Now</span>
  <span m='87132'>let's</span> <span m='87444'>look</span> <span m='87757'>at</span>
  <span m='88069'>the</span> <span m='88382'>voltage</span> <span m='88694'>waveforms</span>
  <span m='89006'>as</span> <span m='89319'>a</span> <span m='89631'>function</span>
  <span m='89944'>of</span> <span m='90256'>time.</span> </p><p><span m='90569'>The</span>
  <span m='91055'>top</span> <span m='91542'>plot</span> <span m='92028'>shows</span>
  <span m='92515'>both</span> <span m='93001'>a</span> <span m='93488'>rising</span>
  <span m='93974'>and,</span> <span m='94461'>later,</span> <span m='94947'>a</span>
  <span m='95434'>falling</span> <span m='95920'>transition</span> <span m='96407'>for</span>
  <span m='96893'>V_IN.</span> </p><p><span m='97380'>We</span> <span m='97714'>see</span>
  <span m='98048'>that</span> <span m='98382'>the</span> <span m='98716'>output</span>
  <span m='99050'>waveform</span> <span m='99384'>has</span> <span m='99718'>the</span>
  <span m='100052'>characteristic</span> <span m='100387'>exponential</span> <span
  m='100721'>shape</span> <span m='101055'>for</span> <span m='101389'>the</span>
  <span m='101723'>voltage</span> <span m='102057'>of</span> <span m='102391'>a</span>
  <span m='102725'>capacitor</span> <span m='103060'>being</span> <span m='103609'>discharged</span>
  <span m='104159'>or</span> <span m='104709'>charged</span> <span m='105258'>though</span>
  <span m='105808'>a</span> <span m='106358'>resistor.</span> </p><p><span m='106908'>The</span>
  <span m='107290'>exponential</span> <span m='107673'>is</span> <span m='108056'>characterized</span>
  <span m='108438'>by</span> <span m='108821'>its</span> <span m='109204'>associated</span>
  <span m='109587'>R-C</span> <span m='109969'>time</span> <span m='110352'>constant,</span>
  <span m='110735'>where,</span> <span m='111118'>in</span> <span m='111500'>this</span>
  <span m='111883'>case,</span> <span m='112266'>the</span> <span m='112649'>R</span>
  <span m='112984'>is</span> <span m='113320'>the</span> <span m='113655'>net</span>
  <span m='113991'>resistance</span> <span m='114326'>of</span> <span m='114662'>the</span>
  <span m='114997'>wire</span> <span m='115333'>and</span> <span m='115669'>MOSFET</span>
  <span m='116004'>channel,</span> <span m='116340'>and</span> <span m='116675'>the</span>
  <span m='117011'>C</span> <span m='117346'>is</span> <span m='117682'>the</span>
  <span m='118017'>net</span> <span m='118353'>capacitance</span> <span m='118689'>of</span>
  <span m='119266'>the</span> <span m='119843'>wire</span> <span m='120420'>and</span>
  <span m='120997'>MOSFET</span> <span m='121574'>gate</span> <span m='122151'>terminals.</span>
  </p><p><span m='122729'>Since</span> <span m='123081'>neither</span> <span m='123434'>the</span>
  <span m='123787'>input</span> <span m='124140'>nor</span> <span m='124493'>output</span>
  <span m='124846'>transition</span> <span m='125199'>is</span> <span m='125552'>instantaneous,</span>
  <span m='125905'>we</span> <span m='126258'>have</span> <span m='126611'>some</span>
  <span m='126964'>choices</span> <span m='127317'>to</span> <span m='127670'>make</span>
  <span m='128055'>about</span> <span m='128441'>how</span> <span m='128826'>to</span>
  <span m='129212'>measure</span> <span m='129597'>the</span> <span m='129983'>inverter's</span>
  <span m='130368'>propagation</span> <span m='130754'>delay.</span> </p><p><span
  m='131140'>Happily,</span> <span m='131670'>we</span> <span m='132201'>have</span>
  <span m='132732'>just</span> <span m='133263'>the</span> <span m='133794'>guidance</span>
  <span m='134325'>we</span> <span m='134855'>need</span> <span m='135386'>from</span>
  <span m='135917'>our</span> <span m='136448'>signaling</span> <span m='136979'>thresholds!</span>
  </p><p><span m='137510'>The</span> <span m='137774'>propagation</span> <span m='138038'>delay</span>
  <span m='138302'>of</span> <span m='138566'>a</span> <span m='138830'>combinational</span>
  <span m='139094'>logic</span> <span m='139358'>gate</span> <span m='139622'>is</span>
  <span m='139887'>defined</span> <span m='140151'>to</span> <span m='140415'>be</span>
  <span m='140679'>an</span> <span m='140943'>upper</span> <span m='141207'>bound</span>
  <span m='141471'>on</span> <span m='141735'>the</span> <span m='142000'>delay</span>
  <span m='142545'>from</span> <span m='143091'>valid</span> <span m='143637'>inputs</span>
  <span m='144182'>to</span> <span m='144728'>valid</span> <span m='145274'>outputs.</span>
  </p><p><span m='145820'>Valid</span> <span m='146208'>input</span> <span m='146597'>voltages</span>
  <span m='146986'>are</span> <span m='147374'>defined</span> <span m='147763'>by</span>
  <span m='148152'>the</span> <span m='148540'>V_IL</span> <span m='148929'>and</span>
  <span m='149318'>V_IH</span> <span m='149706'>signaling</span> <span m='150095'>thresholds,</span>
  <span m='150484'>and</span> <span m='150872'>valid</span> <span m='151261'>output</span>
  <span m='151650'>voltages</span> <span m='152116'>are</span> <span m='152582'>defined</span>
  <span m='153048'>by</span> <span m='153514'>the</span> <span m='153980'>V_OL</span>
  <span m='154446'>and</span> <span m='154912'>V_OH</span> <span m='155378'>signaling</span>
  <span m='155844'>thresholds.</span> </p><p><span m='156310'>We've</span> <span m='156807'>shown</span>
  <span m='157305'>these</span> <span m='157802'>thresholds</span> <span m='158300'>on</span>
  <span m='158797'>the</span> <span m='159295'>waveform</span> <span m='159792'>plots.</span>
  </p><p><span m='160290'>To</span> <span m='160609'>measure</span> <span m='160928'>the</span>
  <span m='161247'>delay</span> <span m='161567'>associated</span> <span m='161886'>with</span>
  <span m='162205'>the</span> <span m='162524'>rising</span> <span m='162844'>transition</span>
  <span m='163163'>on</span> <span m='163482'>V_IN,</span> <span m='163801'>first</span>
  <span m='164121'>identify</span> <span m='164440'>the</span> <span m='164759'>time</span>
  <span m='165079'>when</span> <span m='165481'>the</span> <span m='165883'>input</span>
  <span m='166286'>becomes</span> <span m='166688'>a</span> <span m='167091'>valid</span>
  <span m='167493'>digital</span> <span m='167895'>1,</span> <span m='168298'>i.e.,</span>
  <span m='168700'>the</span> <span m='169103'>time</span> <span m='169505'>at</span>
  <span m='169907'>which</span> <span m='170310'>V_IN</span> <span m='170712'>crosses</span>
  <span m='171115'>the</span> <span m='171517'>V_IH</span> <span m='171920'>threshold.</span>
  </p><p><span m='173190'>Next</span> <span m='173542'>identify</span> <span m='173894'>the</span>
  <span m='174247'>time</span> <span m='174599'>when</span> <span m='174951'>the</span>
  <span m='175304'>output</span> <span m='175656'>becomes</span> <span m='176008'>a</span>
  <span m='176361'>valid</span> <span m='176713'>digital</span> <span m='177065'>0,</span>
  <span m='177418'>i.e.,</span> <span m='177770'>the</span> <span m='178122'>time</span>
  <span m='178475'>at</span> <span m='178827'>which</span> <span m='179180'>V_OUT</span>
  <span m='179806'>crosses</span> <span m='180432'>the</span> <span m='181058'>V_OL</span>
  <span m='181684'>threshold.</span> </p><p><span m='182310'>The</span> <span m='182592'>interval</span>
  <span m='182874'>between</span> <span m='183157'>these</span> <span m='183439'>two</span>
  <span m='183722'>time</span> <span m='184004'>points</span> <span m='184287'>is</span>
  <span m='184569'>the</span> <span m='184851'>delay</span> <span m='185134'>for</span>
  <span m='185416'>this</span> <span m='185699'>particular</span> <span m='185981'>set</span>
  <span m='186264'>of</span> <span m='186546'>input</span> <span m='186829'>and</span>
  <span m='187779'>output</span> <span m='188729'>transitions.</span> </p><p><span
  m='189680'>We</span> <span m='189936'>can</span> <span m='190193'>go</span> <span
  m='190450'>through</span> <span m='190707'>the</span> <span m='190964'>same</span>
  <span m='191221'>process</span> <span m='191478'>to</span> <span m='191735'>measure</span>
  <span m='191991'>the</span> <span m='192248'>delay</span> <span m='192505'>associated</span>
  <span m='192762'>with</span> <span m='193019'>a</span> <span m='193276'>falling</span>
  <span m='193533'>input</span> <span m='193790'>transition.</span> </p><p><span m='194790'>First,</span>
  <span m='195255'>identify</span> <span m='195720'>the</span> <span m='196186'>time</span>
  <span m='196651'>at</span> <span m='197117'>which</span> <span m='197582'>V_IN</span>
  <span m='198048'>cross</span> <span m='198513'>the</span> <span m='198979'>V_IL</span>
  <span m='199444'>threshold.</span> </p><p><span m='199910'>Then</span> <span m='200336'>find</span>
  <span m='200762'>the</span> <span m='201188'>time</span> <span m='201615'>at</span>
  <span m='202041'>which</span> <span m='202467'>V_OUT</span> <span m='202893'>crosses</span>
  <span m='203320'>the</span> <span m='203746'>V_OH</span> <span m='204172'>threshold.</span>
  </p><p><span m='204599'>The</span> <span m='204945'>resulting</span> <span m='205291'>interval</span>
  <span m='205637'>is</span> <span m='205983'>the</span> <span m='206329'>delay</span>
  <span m='206675'>we</span> <span m='207021'>wanted</span> <span m='207367'>to</span>
  <span m='207713'>measure.</span> </p><p><span m='208060'>Since</span> <span m='208501'>the</span>
  <span m='208943'>propagation</span> <span m='209385'>delay,</span> <span m='209827'>t_PD,</span>
  <span m='210269'>is</span> <span m='210710'>an</span> <span m='211152'>upper</span>
  <span m='211594'>bound</span> <span m='212036'>on</span> <span m='212478'>the</span>
  <span m='212919'>delay</span> <span m='213361'>associated</span> <span m='213803'>with</span>
  <span m='214245'>*any*</span> <span m='214687'>input</span> <span m='215129'>transition,</span>
  <span m='215452'>we'll</span> <span m='215775'>choose</span> <span m='216099'>a</span>
  <span m='216422'>value</span> <span m='216746'>for</span> <span m='217069'>t_PD</span>
  <span m='217392'>that's</span> <span m='217716'>greater</span> <span m='218039'>than</span>
  <span m='218363'>or</span> <span m='218686'>equal</span> <span m='219009'>to</span>
  <span m='219333'>the</span> <span m='219656'>measurements</span> <span m='219980'>we</span>
  <span m='220633'>just</span> <span m='221286'>made.</span> </p><p><span m='221939'>When</span>
  <span m='222343'>a</span> <span m='222747'>manufacturer</span> <span m='223152'>selects</span>
  <span m='223556'>the</span> <span m='223960'>t_PD</span> <span m='224365'>specification</span>
  <span m='224769'>for</span> <span m='225174'>a</span> <span m='225578'>gate,</span>
  <span m='225982'>it</span> <span m='226387'>must</span> <span m='226791'>take</span>
  <span m='227195'>into</span> <span m='227600'>account</span> <span m='228004'>manufacturing</span>
  <span m='228409'>variations,</span> <span m='228843'>the</span> <span m='229277'>effects</span>
  <span m='229711'>of</span> <span m='230146'>different</span> <span m='230580'>environmental</span>
  <span m='231014'>conditions</span> <span m='231448'>such</span> <span m='231883'>as</span>
  <span m='232317'>temperature</span> <span m='232751'>and</span> <span m='233185'>power-supply</span>
  <span m='233620'>voltage,</span> <span m='234109'>and</span> <span m='234599'>so</span>
  <span m='235089'>on.</span> </p><p><span m='235579'>It</span> <span m='235882'>should</span>
  <span m='236186'>choose</span> <span m='236489'>a</span> <span m='236793'>t_PD</span>
  <span m='237096'>that</span> <span m='237400'>will</span> <span m='237703'>be</span>
  <span m='238007'>an</span> <span m='238310'>upper</span> <span m='238614'>bound</span>
  <span m='238917'>on</span> <span m='239221'>any</span> <span m='239524'>delay</span>
  <span m='239828'>measurements</span> <span m='240131'>their</span> <span m='240435'>customers</span>
  <span m='240739'>might</span> <span m='241515'>make</span> <span m='242291'>on</span>
  <span m='243067'>actual</span> <span m='243843'>devices.</span> </p><p><span m='244620'>From</span>
  <span m='244850'>the</span> <span m='245081'>designer's</span> <span m='245311'>point</span>
  <span m='245542'>of</span> <span m='245773'>view,</span> <span m='246003'>we</span>
  <span m='246234'>can</span> <span m='246465'>rely</span> <span m='246695'>on</span>
  <span m='246926'>this</span> <span m='247156'>upper</span> <span m='247387'>bound</span>
  <span m='247618'>for</span> <span m='247848'>each</span> <span m='248079'>component</span>
  <span m='248310'>of</span> <span m='248641'>a</span> <span m='248973'>larger</span>
  <span m='249305'>digital</span> <span m='249637'>system</span> <span m='249968'>and</span>
  <span m='250300'>use</span> <span m='250632'>it</span> <span m='250964'>to</span>
  <span m='251295'>calculate</span> <span m='251627'>the</span> <span m='251959'>system's</span>
  <span m='252291'>t_PD</span> <span m='252622'>without</span> <span m='252954'>having</span>
  <span m='253286'>to</span> <span m='253618'>repeat</span> <span m='253950'>all</span>
  <span m='254885'>the</span> <span m='255820'>manufacturer's</span> <span m='256755'>measurements.</span>
  </p><p><span m='257690'>If</span> <span m='257951'>our</span> <span m='258212'>goal</span>
  <span m='258473'>is</span> <span m='258734'>to</span> <span m='258995'>minimize</span>
  <span m='259257'>the</span> <span m='259518'>propagation</span> <span m='259779'>delay</span>
  <span m='260040'>of</span> <span m='260301'>our</span> <span m='260562'>system,</span>
  <span m='260824'>then</span> <span m='261085'>we'll</span> <span m='261346'>want</span>
  <span m='261607'>to</span> <span m='261868'>keep</span> <span m='262130'>the</span>
  <span m='262667'>capacitances</span> <span m='263205'>and</span> <span m='263742'>resistances</span>
  <span m='264280'>as</span> <span m='264817'>small</span> <span m='265355'>as</span>
  <span m='265892'>possible.</span> </p><p><span m='266430'>There's</span> <span m='266765'>an</span>
  <span m='267100'>interesting</span> <span m='267435'>tension</span> <span m='267770'>here:</span>
  <span m='268105'>to</span> <span m='268440'>make</span> <span m='268775'>the</span>
  <span m='269110'>effective</span> <span m='269445'>resistance</span> <span m='269780'>of</span>
  <span m='270115'>a</span> <span m='270450'>MOSFET</span> <span m='270785'>switch</span>
  <span m='271120'>smaller,</span> <span m='271723'>we</span> <span m='272326'>would</span>
  <span m='272930'>increase</span> <span m='273533'>its</span> <span m='274136'>width.</span>
  </p><p><span m='274740'>But</span> <span m='275088'>that</span> <span m='275436'>would</span>
  <span m='275785'>add</span> <span m='276133'>additional</span> <span m='276482'>capacitance</span>
  <span m='276830'>to</span> <span m='277179'>the</span> <span m='277527'>switch's</span>
  <span m='277876'>gate</span> <span m='278224'>terminal,</span> <span m='278573'>slowing</span>
  <span m='278921'>down</span> <span m='279270'>transitions</span> <span m='279655'>on</span>
  <span m='280040'>the</span> <span m='280425'>input</span> <span m='280810'>node</span>
  <span m='281195'>that</span> <span m='281580'>connects</span> <span m='281965'>to</span>
  <span m='282350'>the</span> <span m='282735'>gate!</span> </p><p><span m='283120'>It's</span>
  <span m='283459'>a</span> <span m='283798'>fun</span> <span m='284137'>optimization</span>
  <span m='284477'>problem</span> <span m='284816'>to</span> <span m='285155'>figure</span>
  <span m='285495'>out</span> <span m='285834'>transistor</span> <span m='286173'>sizing</span>
  <span m='286512'>that</span> <span m='286852'>minimizes</span> <span m='287191'>the</span>
  <span m='287530'>overall</span> <span m='287870'>propagation</span> <span m='289400'>delay.</span>
  </p><p><span m='290930'>Although</span> <span m='291243'>not</span> <span m='291556'>strictly</span>
  <span m='291870'>required</span> <span m='292183'>by</span> <span m='292496'>the</span>
  <span m='292810'>static</span> <span m='293123'>discipline,</span> <span m='293436'>it</span>
  <span m='293750'>will</span> <span m='294063'>be</span> <span m='294376'>useful</span>
  <span m='294690'>to</span> <span m='295003'>define</span> <span m='295316'>another</span>
  <span m='295630'>timing</span> <span m='296323'>specification,</span> <span m='297016'>called</span>
  <span m='297709'>the</span> <span m='298402'>"contamination</span> <span m='299095'>delay".</span>
  </p><p><span m='299789'>It</span> <span m='300117'>measures</span> <span m='300446'>how</span>
  <span m='300775'>long</span> <span m='301103'>a</span> <span m='301432'>gate's</span>
  <span m='301761'>previous</span> <span m='302090'>output</span> <span m='302418'>value</span>
  <span m='302747'>remains</span> <span m='303076'>valid</span> <span m='303405'>after</span>
  <span m='303733'>the</span> <span m='304062'>gate's</span> <span m='304391'>inputs</span>
  <span m='304720'>start</span> <span m='305188'>to</span> <span m='305656'>change</span>
  <span m='306125'>and</span> <span m='306593'>become</span> <span m='307061'>invalid.</span>
  </p><p><span m='307530'>Technically,</span> <span m='307874'>the</span> <span m='308218'>contamination</span>
  <span m='308562'>delay</span> <span m='308906'>will</span> <span m='309250'>be</span>
  <span m='309594'>a</span> <span m='309938'>lower</span> <span m='310282'>bound</span>
  <span m='310626'>on</span> <span m='310970'>the</span> <span m='311314'>delay</span>
  <span m='311658'>from</span> <span m='312002'>an</span> <span m='312346'>invalid</span>
  <span m='312690'>input</span> <span m='313336'>to</span> <span m='313982'>an</span>
  <span m='314628'>invalid</span> <span m='315274'>output.</span> </p><p><span m='315920'>We'll</span>
  <span m='316204'>make</span> <span m='316489'>the</span> <span m='316773'>delay</span>
  <span m='317058'>measurements</span> <span m='317343'>much</span> <span m='317627'>as</span>
  <span m='317912'>we</span> <span m='318196'>did</span> <span m='318481'>for</span>
  <span m='318766'>the</span> <span m='319050'>propagation</span> <span m='319335'>delay.</span>
  </p><p><span m='319620'>On</span> <span m='319947'>a</span> <span m='320274'>rising</span>
  <span m='320601'>input</span> <span m='320928'>transition,</span> <span m='321255'>the</span>
  <span m='321582'>delay</span> <span m='321909'>starts</span> <span m='322236'>when</span>
  <span m='322563'>the</span> <span m='322890'>input</span> <span m='323217'>is</span>
  <span m='323544'>no</span> <span m='323871'>longer</span> <span m='324198'>a</span>
  <span m='324525'>valid</span> <span m='324852'>digital</span> <span m='325180'>0,</span>
  <span m='325732'>i.e.,</span> <span m='326285'>when</span> <span m='326837'>V_IN</span>
  <span m='327390'>crosses</span> <span m='327942'>the</span> <span m='328495'>V_IL</span>
  <span m='329047'>threshold.</span> </p><p><span m='329600'>And</span> <span m='330050'>the</span>
  <span m='330501'>delay</span> <span m='330952'>ends</span> <span m='331402'>when</span>
  <span m='331853'>the</span> <span m='332304'>output</span> <span m='332754'>becomes</span>
  <span m='333205'>invalid,</span> <span m='333656'>i.e.,</span> <span m='334106'>when</span>
  <span m='334557'>V_OUT</span> <span m='335008'>crosses</span> <span m='335458'>the</span>
  <span m='335909'>V_OH</span> <span m='336360'>threshold.</span> </p><p><span m='337360'>We</span>
  <span m='337808'>can</span> <span m='338256'>make</span> <span m='338705'>a</span>
  <span m='339153'>similar</span> <span m='339601'>delay</span> <span m='340050'>measurement</span>
  <span m='340498'>for</span> <span m='340946'>the</span> <span m='341395'>falling</span>
  <span m='341843'>input</span> <span m='342291'>transition.</span> </p><p><span m='342740'>Since</span>
  <span m='343064'>the</span> <span m='343389'>contamination</span> <span m='343714'>delay,</span>
  <span m='344038'>t_CD,</span> <span m='344363'>is</span> <span m='344688'>a</span>
  <span m='345012'>lower</span> <span m='345337'>bound</span> <span m='345662'>on</span>
  <span m='345986'>the</span> <span m='346311'>delay</span> <span m='346636'>associated</span>
  <span m='346960'>with</span> <span m='347285'>*any*</span> <span m='347610'>input</span>
  <span m='347945'>transition,</span> <span m='348281'>we'll</span> <span m='348616'>choose</span>
  <span m='348952'>a</span> <span m='349287'>value</span> <span m='349623'>for</span>
  <span m='349958'>t_CD</span> <span m='350294'>that's</span> <span m='350630'>less</span>
  <span m='350965'>than</span> <span m='351301'>or</span> <span m='351636'>equal</span>
  <span m='351972'>to</span> <span m='352307'>the</span> <span m='352643'>measurements</span>
  <span m='352979'>we</span> <span m='353939'>just</span> <span m='354899'>made.</span>
  </p><p><span m='355860'>Do</span> <span m='356310'>we</span> <span m='356760'>really</span>
  <span m='357210'>need</span> <span m='357660'>the</span> <span m='358110'>contamination</span>
  <span m='358560'>delay</span> <span m='359010'>specification?</span> </p><p><span
  m='359460'>Usually</span> <span m='360215'>not.</span> </p><p><span m='360970'>And</span>
  <span m='361318'>if</span> <span m='361667'>not's</span> <span m='362016'>specified,</span>
  <span m='362364'>designers</span> <span m='362713'>should</span> <span m='363062'>assume</span>
  <span m='363410'>that</span> <span m='363759'>the</span> <span m='364108'>t_CD</span>
  <span m='364456'>for</span> <span m='364805'>a</span> <span m='365154'>combinational</span>
  <span m='365502'>device</span> <span m='365851'>is</span> <span m='366200'>0.</span>
  </p><p><span m='367830'>In</span> <span m='368093'>other</span> <span m='368356'>words</span>
  <span m='368619'>a</span> <span m='368882'>conservative</span> <span m='369145'>assumption</span>
  <span m='369408'>is</span> <span m='369671'>that</span> <span m='369934'>the</span>
  <span m='370197'>outputs</span> <span m='370460'>go</span> <span m='370723'>invalid</span>
  <span m='370986'>as</span> <span m='371249'>soon</span> <span m='371512'>as</span>
  <span m='371775'>the</span> <span m='372039'>inputs</span> <span m='372609'>go</span>
  <span m='373179'>invalid.</span> </p><p><span m='373750'>By</span> <span m='374155'>the</span>
  <span m='374560'>way,</span> <span m='374966'>manufacturers</span> <span m='375371'>often</span>
  <span m='375776'>use</span> <span m='376182'>the</span> <span m='376587'>term</span>
  <span m='376992'>"minimum</span> <span m='377398'>propagation</span> <span m='377803'>delay"</span>
  <span m='378208'>to</span> <span m='378614'>refer</span> <span m='379019'>to</span>
  <span m='379424'>a</span> <span m='379830'>device's</span> <span m='380810'>contamination</span>
  <span m='381790'>delay.</span> </p><p><span m='382770'>That</span> <span m='382980'>terminology</span>
  <span m='383190'>is</span> <span m='383400'>a</span> <span m='383610'>bit</span>
  <span m='383820'>confusing,</span> <span m='384030'>but</span> <span m='384240'>now</span>
  <span m='384450'>you</span> <span m='384660'>know</span> <span m='384870'>what</span>
  <span m='385080'>it</span> <span m='385290'>is</span> <span m='385500'>they're</span>
  <span m='385710'>trying</span> <span m='385920'>to</span> <span m='386130'>tell</span>
  <span m='386340'>you.</span> </p><p><span m='388520'>So</span> <span m='388933'>here's</span>
  <span m='389346'>a</span> <span m='389759'>quick</span> <span m='390173'>summary</span>
  <span m='390586'>of</span> <span m='390999'>the</span> <span m='391412'>timing</span>
  <span m='391826'>specifications</span> <span m='392239'>for</span> <span m='392652'>combinational</span>
  <span m='393065'>logic.</span> </p><p><span m='393479'>These</span> <span m='393837'>specifications</span>
  <span m='394196'>tell</span> <span m='394554'>us</span> <span m='394913'>how</span>
  <span m='395272'>the</span> <span m='395630'>timing</span> <span m='395989'>of</span>
  <span m='396348'>changes</span> <span m='396706'>in</span> <span m='397065'>the</span>
  <span m='397424'>output</span> <span m='397782'>waveform</span> <span m='398141'>(labeled</span>
  <span m='398500'>B</span> <span m='398792'>in</span> <span m='399085'>this</span>
  <span m='399377'>example)</span> <span m='399670'>are</span> <span m='399962'>related</span>
  <span m='400255'>to</span> <span m='400547'>the</span> <span m='400840'>timing</span>
  <span m='401132'>of</span> <span m='401425'>changes</span> <span m='401717'>in</span>
  <span m='402010'>the</span> <span m='402302'>input</span> <span m='402595'>waveform</span>
  <span m='402887'>(labeled</span> <span m='403180'>A).</span> </p><p><span m='404180'>A</span>
  <span m='404559'>combinational</span> <span m='404938'>device</span> <span m='405318'>may</span>
  <span m='405697'>retain</span> <span m='406076'>its</span> <span m='406456'>previous</span>
  <span m='406835'>output</span> <span m='407214'>value</span> <span m='407594'>for</span>
  <span m='407973'>some</span> <span m='408352'>interval</span> <span m='408732'>of</span>
  <span m='409111'>time</span> <span m='409490'>after</span> <span m='409870'>an</span>
  <span m='410506'>input</span> <span m='411143'>transition.</span> </p><p><span m='411780'>The</span>
  <span m='412081'>contamination</span> <span m='412383'>delay</span> <span m='412685'>of</span>
  <span m='412987'>the</span> <span m='413289'>device</span> <span m='413591'>is</span>
  <span m='413893'>a</span> <span m='414195'>guarantee</span> <span m='414496'>on</span>
  <span m='414798'>the</span> <span m='415100'>minimum</span> <span m='415402'>size</span>
  <span m='415704'>of</span> <span m='416006'>that</span> <span m='416308'>interval,</span>
  <span m='416610'>i.e.,</span> <span m='417038'>t_CD</span> <span m='417466'>is</span>
  <span m='417894'>a</span> <span m='418322'>lower</span> <span m='418750'>bound</span>
  <span m='419178'>on</span> <span m='419606'>how</span> <span m='420034'>long</span>
  <span m='420462'>the</span> <span m='420890'>old</span> <span m='421318'>output</span>
  <span m='421746'>value</span> <span m='422174'>stays</span> <span m='422602'>valid.</span>
  </p><p><span m='423030'>As</span> <span m='423346'>stated</span> <span m='423662'>in</span>
  <span m='423978'>Note</span> <span m='424295'>2,</span> <span m='424611'>a</span>
  <span m='424927'>conservative</span> <span m='425243'>assumption</span> <span m='425560'>is</span>
  <span m='425876'>that</span> <span m='426192'>the</span> <span m='426508'>contamination</span>
  <span m='426825'>delay</span> <span m='427141'>of</span> <span m='427457'>a</span>
  <span m='427773'>device</span> <span m='428090'>is</span> <span m='428520'>0,</span>
  <span m='428950'>meaning</span> <span m='429380'>the</span> <span m='429810'>device's</span>
  <span m='430240'>output</span> <span m='430670'>may</span> <span m='431100'>change</span>
  <span m='431530'>immediately</span> <span m='431960'>after</span> <span m='432390'>an</span>
  <span m='432820'>input</span> <span m='433250'>transition.</span> </p><p><span m='433680'>So</span>
  <span m='434195'>t_CD</span> <span m='434710'>gives</span> <span m='435225'>us</span>
  <span m='435740'>information</span> <span m='436255'>on</span> <span m='436770'>when</span>
  <span m='437285'>B</span> <span m='437800'>will</span> <span m='438315'>start</span>
  <span m='438830'>to</span> <span m='439345'>change.</span> </p><p><span m='439860'>Similarly,</span>
  <span m='440148'>it</span> <span m='440436'>would</span> <span m='440724'>be</span>
  <span m='441012'>good</span> <span m='441300'>to</span> <span m='441589'>know</span>
  <span m='441877'>when</span> <span m='442165'>B</span> <span m='442453'>is</span>
  <span m='442741'>guaranteed</span> <span m='443029'>to</span> <span m='443318'>be</span>
  <span m='443606'>done</span> <span m='443894'>changing</span> <span m='444182'>after</span>
  <span m='444470'>an</span> <span m='444759'>input</span> <span m='445709'>transition.</span>
  </p><p><span m='446660'>In</span> <span m='446882'>other</span> <span m='447104'>words,</span>
  <span m='447326'>how</span> <span m='447548'>long</span> <span m='447770'>do</span>
  <span m='447992'>we</span> <span m='448214'>have</span> <span m='448436'>to</span>
  <span m='448658'>wait</span> <span m='448881'>for</span> <span m='449103'>a</span>
  <span m='449325'>change</span> <span m='449547'>in</span> <span m='449769'>the</span>
  <span m='449991'>inputs</span> <span m='450213'>to</span> <span m='450435'>reflected</span>
  <span m='450657'>in</span> <span m='450880'>an</span> <span m='451413'>updated</span>
  <span m='451946'>value</span> <span m='452480'>on</span> <span m='453013'>the</span>
  <span m='453546'>outputs?</span> </p><p><span m='454080'>This</span> <span m='454332'>is</span>
  <span m='454584'>what</span> <span m='454837'>t_PD</span> <span m='455089'>tells</span>
  <span m='455341'>us</span> <span m='455594'>since</span> <span m='455846'>it</span>
  <span m='456098'>is</span> <span m='456351'>a</span> <span m='456603'>upper</span>
  <span m='456855'>bound</span> <span m='457108'>on</span> <span m='457360'>the</span>
  <span m='457612'>time</span> <span m='457865'>it</span> <span m='458117'>takes</span>
  <span m='458369'>for</span> <span m='458622'>B</span> <span m='458874'>to</span>
  <span m='459126'>become</span> <span m='459379'>valid</span> <span m='459954'>and</span>
  <span m='460530'>stable</span> <span m='461106'>after</span> <span m='461681'>an</span>
  <span m='462257'>input</span> <span m='462833'>transition.</span> </p><p><span m='463409'>As</span>
  <span m='463715'>Note</span> <span m='464021'>1</span> <span m='464327'>points</span>
  <span m='464633'>out,</span> <span m='464939'>in</span> <span m='465245'>general</span>
  <span m='465551'>there</span> <span m='465857'>are</span> <span m='466163'>no</span>
  <span m='466469'>guarantees</span> <span m='466775'>on</span> <span m='467081'>the</span>
  <span m='467387'>behavior</span> <span m='467693'>of</span> <span m='467999'>the</span>
  <span m='468305'>output</span> <span m='468611'>in</span> <span m='469062'>the</span>
  <span m='469513'>interval</span> <span m='469965'>after</span> <span m='470416'>t_CD</span>
  <span m='470867'>and</span> <span m='471319'>before</span> <span m='471770'>t_PD,</span>
  <span m='472221'>as</span> <span m='472673'>measured</span> <span m='473124'>from</span>
  <span m='473575'>the</span> <span m='474027'>input</span> <span m='474478'>transition.</span>
  </p><p><span m='474930'>It</span> <span m='475205'>would</span> <span m='475480'>legal</span>
  <span m='475755'>for</span> <span m='476031'>the</span> <span m='476306'>B</span>
  <span m='476581'>output</span> <span m='476857'>to</span> <span m='477132'>change</span>
  <span m='477407'>several</span> <span m='477682'>times</span> <span m='477958'>in</span>
  <span m='478233'>that</span> <span m='478508'>interval,</span> <span m='478784'>or</span>
  <span m='479059'>even</span> <span m='479334'>have</span> <span m='479610'>a</span>
  <span m='479974'>non-digital</span> <span m='480338'>voltage</span> <span m='480703'>for</span>
  <span m='481067'>any</span> <span m='481431'>part</span> <span m='481796'>of</span>
  <span m='482160'>the</span> <span m='482524'>interval.</span> </p><p><span m='482889'>As</span>
  <span m='483211'>we'll</span> <span m='483534'>see</span> <span m='483857'>in</span>
  <span m='484180'>the</span> <span m='484502'>last</span> <span m='484825'>video</span>
  <span m='485148'>of</span> <span m='485471'>this</span> <span m='485794'>chapter,</span>
  <span m='486116'>we'll</span> <span m='486439'>be</span> <span m='486762'>able</span>
  <span m='487085'>to</span> <span m='487407'>offer</span> <span m='487730'>more</span>
  <span m='488053'>insights</span> <span m='488376'>into</span> <span m='488699'>B's</span>
  <span m='489098'>behavior</span> <span m='489497'>in</span> <span m='489896'>this</span>
  <span m='490295'>interval</span> <span m='490694'>for</span> <span m='491094'>a</span>
  <span m='491493'>subclass</span> <span m='491892'>of</span> <span m='492291'>combinational</span>
  <span m='492690'>devices.</span> </p><p><span m='493090'>But</span> <span m='493371'>in</span>
  <span m='493653'>general,</span> <span m='493935'>a</span> <span m='494217'>designer</span>
  <span m='494499'>should</span> <span m='494781'>make</span> <span m='495063'>no</span>
  <span m='495345'>assumptions</span> <span m='495627'>about</span> <span m='495909'>B's</span>
  <span m='496191'>value</span> <span m='496473'>in</span> <span m='496755'>the</span>
  <span m='497037'>interval</span> <span m='497319'>between</span> <span m='498301'>t_CD</span>
  <span m='499284'>and</span> <span m='500267'>t_PD.</span> </p><p><span m='501250'>How</span>
  <span m='501593'>do</span> <span m='501936'>we</span> <span m='502280'>calculate</span>
  <span m='502623'>the</span> <span m='502966'>propagation</span> <span m='503310'>and</span>
  <span m='503653'>contamination</span> <span m='503996'>delays</span> <span m='504340'>of</span>
  <span m='504683'>a</span> <span m='505026'>larger</span> <span m='505370'>combinational</span>
  <span m='505713'>circuit</span> <span m='506056'>from</span> <span m='506400'>the</span>
  <span m='506876'>timing</span> <span m='507353'>specifications</span> <span m='507830'>of</span>
  <span m='508306'>its</span> <span m='508783'>components?</span> </p><p><span m='509260'>Our</span>
  <span m='509682'>example</span> <span m='510104'>is</span> <span m='510526'>a</span>
  <span m='510948'>circuit</span> <span m='511370'>of</span> <span m='511792'>four</span>
  <span m='512214'>NAND</span> <span m='512636'>gates</span> <span m='513058'>where</span>
  <span m='513480'>each</span> <span m='513902'>NAND</span> <span m='514324'>has</span>
  <span m='514746'>a</span> <span m='515168'>t_PD</span> <span m='515590'>of</span>
  <span m='516012'>4</span> <span m='516434'>ns</span> <span m='516856'>and</span>
  <span m='517278'>t_CD</span> <span m='517700'>of</span> <span m='518149'>1</span>
  <span m='518599'>ns.</span> </p><p><span m='519049'>To</span> <span m='519330'>find</span>
  <span m='519611'>the</span> <span m='519892'>propagation</span> <span m='520174'>delay</span>
  <span m='520455'>for</span> <span m='520736'>the</span> <span m='521017'>larger</span>
  <span m='521299'>circuit,</span> <span m='521580'>we</span> <span m='521861'>need</span>
  <span m='522142'>to</span> <span m='522424'>find</span> <span m='522705'>the</span>
  <span m='522986'>maximum</span> <span m='523267'>delay</span> <span m='523549'>from</span>
  <span m='523861'>an</span> <span m='524173'>input</span> <span m='524485'>transition</span>
  <span m='524797'>on</span> <span m='525110'>nodes</span> <span m='525422'>A,</span>
  <span m='525734'>B,</span> <span m='526046'>or</span> <span m='526358'>C</span>
  <span m='526671'>to</span> <span m='526983'>a</span> <span m='527295'>valid</span>
  <span m='527607'>and</span> <span m='527919'>stable</span> <span m='528232'>value</span>
  <span m='528544'>on</span> <span m='528856'>the</span> <span m='529168'>output</span>
  <span m='529481'>Y.</span> </p><p><span m='531220'>To</span> <span m='531554'>do</span>
  <span m='531888'>this,</span> <span m='532223'>consider</span> <span m='532557'>each</span>
  <span m='532892'>possible</span> <span m='533226'>path</span> <span m='533561'>from</span>
  <span m='533895'>one</span> <span m='534230'>of</span> <span m='534564'>the</span>
  <span m='534898'>inputs</span> <span m='535233'>to</span> <span m='535567'>Y</span>
  <span m='535902'>and</span> <span m='536236'>compute</span> <span m='536571'>the</span>
  <span m='536905'>path</span> <span m='537240'>delay</span> <span m='537679'>by</span>
  <span m='538118'>summing</span> <span m='538557'>the</span> <span m='538996'>t_PDs</span>
  <span m='539435'>of</span> <span m='539874'>the</span> <span m='540313'>components</span>
  <span m='540752'>along</span> <span m='541191'>the</span> <span m='541630'>path.</span>
  </p><p><span m='542070'>Choose</span> <span m='542419'>the</span> <span m='542768'>largest</span>
  <span m='543117'>such</span> <span m='543466'>path</span> <span m='543816'>delay</span>
  <span m='544165'>as</span> <span m='544514'>the</span> <span m='544863'>t_PD</span>
  <span m='545213'>of</span> <span m='545562'>the</span> <span m='545911'>overall</span>
  <span m='546260'>circuit.</span> </p><p><span m='546610'>In</span> <span m='546963'>our</span>
  <span m='547317'>example,</span> <span m='547670'>the</span> <span m='548024'>largest</span>
  <span m='548377'>delay</span> <span m='548731'>is</span> <span m='549084'>a</span>
  <span m='549438'>path</span> <span m='549791'>that</span> <span m='550145'>includes</span>
  <span m='550498'>three</span> <span m='550852'>NAND</span> <span m='551205'>gates,</span>
  <span m='551559'>with</span> <span m='551912'>a</span> <span m='552266'>cumulative</span>
  <span m='552620'>propagation</span> <span m='553274'>delay</span> <span m='553928'>of</span>
  <span m='554582'>12</span> <span m='555236'>ns.</span> </p><p><span m='555890'>In</span>
  <span m='556216'>other</span> <span m='556542'>words,</span> <span m='556868'>the</span>
  <span m='557194'>output</span> <span m='557520'>Y</span> <span m='557846'>is</span>
  <span m='558172'>guaranteed</span> <span m='558498'>be</span> <span m='558825'>stable</span>
  <span m='559151'>and</span> <span m='559477'>valid</span> <span m='559803'>within</span>
  <span m='560129'>12</span> <span m='560455'>ns</span> <span m='560781'>of</span>
  <span m='561107'>a</span> <span m='561433'>transition</span> <span m='561760'>on</span>
  <span m='562224'>A,</span> <span m='562689'>B,</span> <span m='563153'>or</span>
  <span m='563618'>C.</span> <span m='564083'>To</span> <span m='564547'>find</span>
  <span m='565012'>the</span> <span m='565476'>contamination</span> <span m='565941'>delay</span>
  <span m='566406'>for</span> <span m='566870'>the</span> <span m='567335'>larger</span>
  <span m='567800'>circuit,</span> <span m='568116'>we</span> <span m='568433'>again</span>
  <span m='568750'>investigate</span> <span m='569066'>all</span> <span m='569383'>paths</span>
  <span m='569700'>from</span> <span m='570016'>inputs</span> <span m='570333'>to</span>
  <span m='570650'>outputs,</span> <span m='570966'>but</span> <span m='571283'>this</span>
  <span m='571600'>time</span> <span m='571916'>we're</span> <span m='572233'>looking</span>
  <span m='572550'>for</span> <span m='572945'>the</span> <span m='573341'>shortest</span>
  <span m='573737'>path</span> <span m='574133'>from</span> <span m='574529'>an</span>
  <span m='574925'>invalid</span> <span m='575320'>input</span> <span m='575716'>to</span>
  <span m='576112'>an</span> <span m='576508'>invalid</span> <span m='576904'>output.</span>
  </p><p><span m='577300'>So</span> <span m='577601'>we</span> <span m='577903'>sum</span>
  <span m='578205'>the</span> <span m='578507'>t_CDs</span> <span m='578808'>of</span>
  <span m='579110'>the</span> <span m='579412'>components</span> <span m='579714'>along</span>
  <span m='580015'>each</span> <span m='580317'>path</span> <span m='580619'>and</span>
  <span m='580921'>choose</span> <span m='581222'>the</span> <span m='581524'>smallest</span>
  <span m='581826'>such</span> <span m='582128'>path</span> <span m='582430'>delay</span>
  <span m='582922'>as</span> <span m='583415'>the</span> <span m='583907'>t_CD</span>
  <span m='584400'>of</span> <span m='584892'>the</span> <span m='585385'>overall</span>
  <span m='585877'>circuit.</span> </p><p><span m='586370'>In</span> <span m='586690'>our</span>
  <span m='587010'>example,</span> <span m='587330'>the</span> <span m='587650'>smallest</span>
  <span m='587970'>delay</span> <span m='588290'>is</span> <span m='588610'>a</span>
  <span m='588930'>path</span> <span m='589250'>that</span> <span m='589570'>includes</span>
  <span m='589890'>two</span> <span m='590210'>NAND</span> <span m='590530'>gates</span>
  <span m='590850'>with</span> <span m='591170'>a</span> <span m='591490'>cumulative</span>
  <span m='591810'>contamination</span> <span m='592486'>delay</span> <span m='593162'>of</span>
  <span m='593838'>2</span> <span m='594514'>ns.</span> </p><p><span m='595190'>In</span>
  <span m='595498'>other</span> <span m='595806'>words,</span> <span m='596115'>the</span>
  <span m='596423'>output</span> <span m='596731'>Y</span> <span m='597040'>will</span>
  <span m='597348'>retain</span> <span m='597656'>its</span> <span m='597965'>previous</span>
  <span m='598273'>value</span> <span m='598581'>for</span> <span m='598890'>at</span>
  <span m='599198'>least</span> <span m='599506'>2</span> <span m='599815'>ns</span>
  <span m='600123'>after</span> <span m='600431'>one</span> <span m='600740'>of</span>
  <span m='601086'>the</span> <span m='601432'>inputs</span> <span m='601778'>goes</span>
  <span m='602124'>invalid.</span> </p>
type: course
uid: 2f62f1c167e6628a2ac9f07689d2bf9f

---
None