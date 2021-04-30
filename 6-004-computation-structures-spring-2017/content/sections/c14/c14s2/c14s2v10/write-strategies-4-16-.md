---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: nlKV2hX1AZs
  parent_uid: 5116a90cab3f9e26e120fdf0efc7eb33
  title: Video-YouTube-Stream
  type: Video
  uid: edf7f06f9d7a332002b7cbadd273fb1d
- id: 3Play-3Play YouTube id-Stream
  media_location: nlKV2hX1AZs
  parent_uid: 5116a90cab3f9e26e120fdf0efc7eb33
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: d047d88ba1aadeca69cb4c42e3230172
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/nlKV2hX1AZs/default.jpg
  parent_uid: 5116a90cab3f9e26e120fdf0efc7eb33
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: a62bf4b499c71b952b3ccacae4f8a8b3
- id: nlKV2hX1AZs.srt
  parent_uid: 5116a90cab3f9e26e120fdf0efc7eb33
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v10/write-strategies-4-16-/nlKV2hX1AZs.srt
  title: 3play caption file
  type: null
  uid: 71943092ba0b31d0bfef91330aa75662
- id: nlKV2hX1AZs.pdf
  parent_uid: 5116a90cab3f9e26e120fdf0efc7eb33
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v10/write-strategies-4-16-/nlKV2hX1AZs.pdf
  title: 3play pdf file
  type: null
  uid: 87fda39356055165d235a6bb874e143d
- id: Caption-3Play YouTube id-SRT
  parent_uid: 5116a90cab3f9e26e120fdf0efc7eb33
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: c777845b5ffc368d87513a2e8bba5bdf
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 5116a90cab3f9e26e120fdf0efc7eb33
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 118edf51cdc6aaa41f72bc48fa314714
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_14-02-10_300k.mp4
  parent_uid: 5116a90cab3f9e26e120fdf0efc7eb33
  title: Video-Internet Archive-MP4
  type: Video
  uid: ae9c3a1c40924cb84552a9ae51808a45
inline_embed_id: 17724899writestrategies41676896466
layout: video
order_index: null
parent_uid: 6bd4958a931f4153acc017417c7ab9e2
related_resources_text: ''
short_url: write-strategies-4-16-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v10/write-strategies-4-16-
template_type: Embed
title: Write Strategies (4:16)
transcript: <p><span m='770'>Okay,</span> <span m='1209'>one</span> <span m='1648'>more</span>
  <span m='2087'>cache</span> <span m='2526'>design</span> <span m='2965'>decision</span>
  <span m='3404'>to</span> <span m='3843'>make,</span> <span m='4282'>then</span>
  <span m='4721'>we're</span> <span m='5160'>done!</span> </p><p><span m='5600'>How</span>
  <span m='5992'>should</span> <span m='6384'>we</span> <span m='6776'>handle</span>
  <span m='7168'>memory</span> <span m='7561'>writes</span> <span m='7953'>in</span>
  <span m='8345'>the</span> <span m='8737'>cache?</span> </p><p><span m='9130'>Ultimately</span>
  <span m='9564'>we'll</span> <span m='9998'>need</span> <span m='10432'>update</span>
  <span m='10866'>main</span> <span m='11300'>memory</span> <span m='11734'>with</span>
  <span m='12168'>the</span> <span m='12602'>new</span> <span m='13036'>data,</span>
  <span m='13470'>but</span> <span m='13904'>when</span> <span m='14338'>should</span>
  <span m='14772'>that</span> <span m='15206'>happen?</span> </p><p><span m='15640'>The</span>
  <span m='15905'>most</span> <span m='16170'>obvious</span> <span m='16435'>choice</span>
  <span m='16700'>is</span> <span m='16965'>to</span> <span m='17230'>perform</span>
  <span m='17495'>the</span> <span m='17760'>write</span> <span m='18025'>immediately.</span>
  </p><p><span m='18290'>In</span> <span m='18660'>other</span> <span m='19031'>words,</span>
  <span m='19401'>whenever</span> <span m='19772'>the</span> <span m='20142'>CPU</span>
  <span m='20513'>sends</span> <span m='20884'>a</span> <span m='21254'>write</span>
  <span m='21625'>request</span> <span m='21995'>to</span> <span m='22366'>the</span>
  <span m='22737'>cache,</span> <span m='23107'>the</span> <span m='23478'>cache</span>
  <span m='23848'>then</span> <span m='24219'>performs</span> <span m='24590'>the</span>
  <span m='25038'>same</span> <span m='25486'>write</span> <span m='25935'>to</span>
  <span m='26383'>main</span> <span m='26831'>memory.</span> </p><p><span m='27280'>This</span>
  <span m='27972'>is</span> <span m='28665'>called</span> <span m='29357'>"write-through".</span>
  </p><p><span m='30050'>That</span> <span m='30403'>way</span> <span m='30756'>main</span>
  <span m='31109'>memory</span> <span m='31462'>always</span> <span m='31815'>has</span>
  <span m='32168'>the</span> <span m='32521'>most</span> <span m='32874'>up-to-date</span>
  <span m='33227'>value</span> <span m='33580'>for</span> <span m='33933'>all</span>
  <span m='34286'>locations.</span> </p><p><span m='34640'>But</span> <span m='34915'>this</span>
  <span m='35190'>can</span> <span m='35465'>be</span> <span m='35740'>slow</span>
  <span m='36015'>if</span> <span m='36290'>the</span> <span m='36565'>CPU</span>
  <span m='36840'>has</span> <span m='37115'>to</span> <span m='37390'>wait</span>
  <span m='37665'>for</span> <span m='37940'>a</span> <span m='38215'>DRAM</span>
  <span m='38490'>write</span> <span m='38765'>access</span> <span m='39040'>-</span>
  <span m='39315'>writes</span> <span m='39590'>could</span> <span m='39865'>become</span>
  <span m='40140'>a</span> <span m='40906'>real</span> <span m='41673'>bottleneck!</span>
  </p><p><span m='42440'>And</span> <span m='42845'>what</span> <span m='43251'>if</span>
  <span m='43657'>the</span> <span m='44062'>program</span> <span m='44468'>is</span>
  <span m='44874'>constantly</span> <span m='45280'>writing</span> <span m='45685'>a</span>
  <span m='46091'>particular</span> <span m='46497'>memory</span> <span m='46902'>location,</span>
  <span m='47308'>e.g.,</span> <span m='47714'>updating</span> <span m='48120'>the</span>
  <span m='48496'>value</span> <span m='48872'>of</span> <span m='49249'>a</span>
  <span m='49625'>local</span> <span m='50001'>variable</span> <span m='50378'>in</span>
  <span m='50754'>the</span> <span m='51130'>current</span> <span m='51507'>stack</span>
  <span m='51883'>frame?</span> </p><p><span m='52260'>In</span> <span m='52590'>the</span>
  <span m='52920'>end</span> <span m='53250'>we</span> <span m='53580'>only</span>
  <span m='53910'>need</span> <span m='54240'>to</span> <span m='54570'>write</span>
  <span m='54900'>the</span> <span m='55230'>last</span> <span m='55560'>value</span>
  <span m='55890'>to</span> <span m='56220'>main</span> <span m='56550'>memory.</span>
  </p><p><span m='56880'>Writing</span> <span m='57288'>all</span> <span m='57696'>the</span>
  <span m='58104'>earlier</span> <span m='58512'>values</span> <span m='58920'>is</span>
  <span m='59328'>waste</span> <span m='59736'>of</span> <span m='60144'>memory</span>
  <span m='60552'>bandwidth.</span> </p><p><span m='60960'>Suppose</span> <span m='61253'>we</span>
  <span m='61546'>let</span> <span m='61839'>the</span> <span m='62132'>CPU</span>
  <span m='62425'>continue</span> <span m='62718'>execution</span> <span m='63011'>while</span>
  <span m='63304'>the</span> <span m='63597'>cache</span> <span m='63890'>waits</span>
  <span m='64183'>for</span> <span m='64476'>the</span> <span m='64769'>write</span>
  <span m='65062'>to</span> <span m='65355'>main</span> <span m='65649'>memory</span>
  <span m='66159'>to</span> <span m='66669'>complete</span> <span m='67179'>-</span>
  <span m='67689'>this</span> <span m='68199'>is</span> <span m='68709'>called</span>
  <span m='69219'>"write-behind".</span> </p><p><span m='69729'>This</span> <span
  m='70046'>will</span> <span m='70364'>overlap</span> <span m='70682'>execution</span>
  <span m='71000'>of</span> <span m='71318'>the</span> <span m='71636'>program</span>
  <span m='71954'>with</span> <span m='72271'>the</span> <span m='72589'>slow</span>
  <span m='72907'>writes</span> <span m='73225'>to</span> <span m='73543'>main</span>
  <span m='73861'>memory.</span> </p><p><span m='74179'>Of</span> <span m='74537'>course,</span>
  <span m='74895'>if</span> <span m='75253'>there's</span> <span m='75611'>another</span>
  <span m='75969'>cache</span> <span m='76327'>miss</span> <span m='76685'>while</span>
  <span m='77043'>the</span> <span m='77401'>write</span> <span m='77759'>is</span>
  <span m='78117'>still</span> <span m='78475'>pending,</span> <span m='78833'>everything</span>
  <span m='79191'>will</span> <span m='79549'>have</span> <span m='79832'>to</span>
  <span m='80116'>wait</span> <span m='80400'>at</span> <span m='80684'>that</span>
  <span m='80968'>point</span> <span m='81251'>until</span> <span m='81535'>both</span>
  <span m='81819'>the</span> <span m='82103'>write</span> <span m='82387'>and</span>
  <span m='82670'>subsequent</span> <span m='82954'>refill</span> <span m='83238'>read</span>
  <span m='83522'>finish,</span> <span m='83806'>since</span> <span m='84090'>the</span>
  <span m='84673'>CPU</span> <span m='85257'>can't</span> <span m='85841'>proceed</span>
  <span m='86425'>until</span> <span m='87009'>the</span> <span m='87593'>cache</span>
  <span m='88177'>miss</span> <span m='88761'>is</span> <span m='89345'>resolved.</span>
  </p><p><span m='89929'>The</span> <span m='90232'>best</span> <span m='90535'>strategy</span>
  <span m='90839'>is</span> <span m='91142'>called</span> <span m='91445'>"write-back"</span>
  <span m='91749'>where</span> <span m='92052'>the</span> <span m='92355'>contents</span>
  <span m='92659'>of</span> <span m='92962'>the</span> <span m='93265'>cache</span>
  <span m='93569'>are</span> <span m='93872'>updated</span> <span m='94175'>and</span>
  <span m='94479'>the</span> <span m='94895'>CPU</span> <span m='95311'>continues</span>
  <span m='95728'>execution</span> <span m='96144'>immediately.</span> </p><p><span
  m='96561'>The</span> <span m='96967'>updated</span> <span m='97373'>cache</span>
  <span m='97779'>value</span> <span m='98185'>is</span> <span m='98591'>only</span>
  <span m='98998'>written</span> <span m='99404'>to</span> <span m='99810'>main</span>
  <span m='100216'>memory</span> <span m='100622'>when</span> <span m='101029'>the</span>
  <span m='101435'>cache</span> <span m='101841'>line</span> <span m='102247'>is</span>
  <span m='102653'>chosen</span> <span m='103060'>as</span> <span m='103556'>the</span>
  <span m='104052'>replacement</span> <span m='104548'>line</span> <span m='105044'>for</span>
  <span m='105540'>a</span> <span m='106036'>cache</span> <span m='106532'>miss.</span>
  </p><p><span m='107029'>This</span> <span m='107397'>strategy</span> <span m='107766'>minimizes</span>
  <span m='108134'>the</span> <span m='108503'>number</span> <span m='108871'>of</span>
  <span m='109240'>accesses</span> <span m='109609'>to</span> <span m='109977'>main</span>
  <span m='110346'>memory,</span> <span m='110714'>preserving</span> <span m='111083'>the</span>
  <span m='111451'>memory</span> <span m='111820'>bandwidth</span> <span m='112189'>for</span>
  <span m='112975'>other</span> <span m='113762'>operations.</span> </p><p><span m='114549'>This</span>
  <span m='115022'>is</span> <span m='115495'>the</span> <span m='115969'>strategy</span>
  <span m='116442'>used</span> <span m='116916'>by</span> <span m='117389'>most</span>
  <span m='117863'>modern</span> <span m='118336'>processors.</span> </p><p><span
  m='118810'>Write-back</span> <span m='119138'>is</span> <span m='119466'>easy</span>
  <span m='119794'>to</span> <span m='120122'>implement.</span> </p><p><span m='120450'>Returning</span>
  <span m='120772'>to</span> <span m='121095'>our</span> <span m='121417'>original</span>
  <span m='121740'>cache</span> <span m='122063'>recipe,</span> <span m='122385'>we</span>
  <span m='122708'>simply</span> <span m='123030'>eliminate</span> <span m='123353'>the</span>
  <span m='123676'>start</span> <span m='123998'>of</span> <span m='124321'>the</span>
  <span m='124643'>write</span> <span m='124966'>to</span> <span m='125289'>main</span>
  <span m='125594'>memory</span> <span m='125900'>when</span> <span m='126206'>there's</span>
  <span m='126512'>a</span> <span m='126818'>write</span> <span m='127124'>request</span>
  <span m='127430'>to</span> <span m='127736'>the</span> <span m='128042'>cache.</span>
  </p><p><span m='128348'>We</span> <span m='128700'>just</span> <span m='129052'>update</span>
  <span m='129404'>the</span> <span m='129756'>cache</span> <span m='130108'>contents</span>
  <span m='130460'>and</span> <span m='130812'>leave</span> <span m='131164'>it</span>
  <span m='131516'>at</span> <span m='131868'>that.</span> </p><p><span m='132220'>However,</span>
  <span m='132617'>replacing</span> <span m='133015'>a</span> <span m='133413'>cache</span>
  <span m='133811'>line</span> <span m='134209'>becomes</span> <span m='134607'>a</span>
  <span m='135005'>more</span> <span m='135402'>complex</span> <span m='135800'>operation,</span>
  <span m='136198'>since</span> <span m='136596'>we</span> <span m='136994'>can't</span>
  <span m='137392'>reuse</span> <span m='137790'>the</span> <span m='138083'>cache</span>
  <span m='138377'>line</span> <span m='138670'>without</span> <span m='138964'>first</span>
  <span m='139257'>writing</span> <span m='139551'>its</span> <span m='139844'>contents</span>
  <span m='140138'>back</span> <span m='140431'>to</span> <span m='140725'>main</span>
  <span m='141018'>memory</span> <span m='141312'>in</span> <span m='141605'>case</span>
  <span m='141899'>they</span> <span m='142192'>had</span> <span m='142486'>been</span>
  <span m='142780'>modified</span> <span m='143346'>by</span> <span m='143913'>an</span>
  <span m='144480'>earlier</span> <span m='145046'>write</span> <span m='145613'>access.</span>
  </p><p><span m='146180'>Hmm.</span> </p><p><span m='147450'>Seems</span> <span m='147711'>like</span>
  <span m='147972'>this</span> <span m='148233'>does</span> <span m='148494'>a</span>
  <span m='148755'>write-back</span> <span m='149017'>of</span> <span m='149278'>all</span>
  <span m='149539'>replaced</span> <span m='149800'>cache</span> <span m='150061'>lines</span>
  <span m='150322'>whether</span> <span m='150584'>or</span> <span m='150845'>not</span>
  <span m='151106'>they've</span> <span m='151367'>been</span> <span m='151628'>written</span>
  <span m='151890'>to.</span> </p><p><span m='154470'>We</span> <span m='154805'>can</span>
  <span m='155140'>avoid</span> <span m='155476'>unnecessary</span> <span m='155811'>write-backs</span>
  <span m='156146'>by</span> <span m='156482'>adding</span> <span m='156817'>another</span>
  <span m='157152'>state</span> <span m='157488'>bit</span> <span m='157823'>to</span>
  <span m='158158'>each</span> <span m='158494'>cache</span> <span m='158829'>line:</span>
  <span m='159164'>the</span> <span m='159500'>"dirty"</span> <span m='160414'>bit.</span>
  </p><p><span m='161329'>The</span> <span m='161690'>dirty</span> <span m='162052'>bit</span>
  <span m='162414'>is</span> <span m='162776'>set</span> <span m='163138'>to</span>
  <span m='163499'>0</span> <span m='163861'>when</span> <span m='164223'>a</span>
  <span m='164585'>cache</span> <span m='164947'>line</span> <span m='165309'>is</span>
  <span m='165670'>filled</span> <span m='166032'>during</span> <span m='166394'>a</span>
  <span m='166756'>cache</span> <span m='167118'>miss.</span> </p><p><span m='167480'>If</span>
  <span m='167768'>a</span> <span m='168056'>subsequent</span> <span m='168344'>write</span>
  <span m='168632'>operation</span> <span m='168921'>changes</span> <span m='169209'>the</span>
  <span m='169497'>data</span> <span m='169785'>in</span> <span m='170074'>a</span>
  <span m='170362'>cache</span> <span m='170650'>line,</span> <span m='170938'>the</span>
  <span m='171227'>dirty</span> <span m='171515'>bit</span> <span m='171803'>is</span>
  <span m='172091'>set</span> <span m='172380'>to</span> <span m='172755'>1,</span>
  <span m='173130'>indicating</span> <span m='173505'>that</span> <span m='173880'>value</span>
  <span m='174255'>in</span> <span m='174630'>the</span> <span m='175005'>cache</span>
  <span m='175380'>now</span> <span m='175755'>differs</span> <span m='176130'>from</span>
  <span m='176505'>the</span> <span m='176880'>value</span> <span m='177255'>in</span>
  <span m='177630'>main</span> <span m='178005'>memory.</span> </p><p><span m='178380'>When</span>
  <span m='178641'>a</span> <span m='178902'>cache</span> <span m='179163'>line</span>
  <span m='179424'>is</span> <span m='179685'>selected</span> <span m='179946'>for</span>
  <span m='180207'>replacement,</span> <span m='180468'>we</span> <span m='180730'>only</span>
  <span m='180991'>need</span> <span m='181252'>to</span> <span m='181513'>write</span>
  <span m='181774'>its</span> <span m='182035'>data</span> <span m='182296'>back</span>
  <span m='182557'>to</span> <span m='182818'>main</span> <span m='183080'>memory</span>
  <span m='183528'>if</span> <span m='183977'>its</span> <span m='184425'>dirty</span>
  <span m='184874'>bit</span> <span m='185322'>is</span> <span m='185771'>1.</span>
  </p><p><span m='186220'>So</span> <span m='186548'>a</span> <span m='186877'>write-back</span>
  <span m='187206'>strategy</span> <span m='187534'>with</span> <span m='187863'>a</span>
  <span m='188192'>dirty</span> <span m='188520'>bit</span> <span m='188849'>gives</span>
  <span m='189178'>an</span> <span m='189506'>elegant</span> <span m='189835'>solution</span>
  <span m='190164'>that</span> <span m='190492'>minimizes</span> <span m='190821'>the</span>
  <span m='191150'>number</span> <span m='191460'>of</span> <span m='191771'>writes</span>
  <span m='192081'>to</span> <span m='192392'>main</span> <span m='192702'>memory</span>
  <span m='193013'>and</span> <span m='193323'>only</span> <span m='193634'>delays</span>
  <span m='193944'>the</span> <span m='194255'>CPU</span> <span m='194565'>on</span>
  <span m='194876'>a</span> <span m='195186'>cache</span> <span m='195497'>miss</span>
  <span m='195807'>if</span> <span m='196118'>a</span> <span m='196428'>dirty</span>
  <span m='196739'>cache</span> <span m='197049'>line</span> <span m='197360'>needs</span>
  <span m='197860'>to</span> <span m='198360'>be</span> <span m='198860'>written</span>
  <span m='199360'>back</span> <span m='199860'>to</span> <span m='200360'>memory.</span>
  </p><p><span m='200860'>That</span> <span m='201188'>concludes</span> <span m='201516'>our</span>
  <span m='201844'>discussion</span> <span m='202172'>of</span> <span m='202500'>caches,</span>
  <span m='202828'>which</span> <span m='203156'>was</span> <span m='203484'>motivated</span>
  <span m='203812'>by</span> <span m='204140'>our</span> <span m='204468'>desire</span>
  <span m='204796'>to</span> <span m='205124'>minimize</span> <span m='205452'>the</span>
  <span m='205780'>average</span> <span m='206167'>memory</span> <span m='206555'>access</span>
  <span m='206942'>time</span> <span m='207330'>by</span> <span m='207717'>building</span>
  <span m='208105'>a</span> <span m='208492'>hierarchical</span> <span m='208880'>memory</span>
  <span m='209267'>system</span> <span m='209655'>that</span> <span m='210042'>had</span>
  <span m='210430'>both</span> <span m='210817'>low</span> <span m='211205'>latency</span>
  <span m='211592'>and</span> <span m='211980'>high</span> <span m='213245'>capacity.</span>
  </p><p><span m='214510'>There</span> <span m='214884'>were</span> <span m='215258'>a</span>
  <span m='215632'>number</span> <span m='216006'>of</span> <span m='216380'>strategies</span>
  <span m='216755'>we</span> <span m='217129'>employed</span> <span m='217503'>to</span>
  <span m='217877'>achieve</span> <span m='218251'>our</span> <span m='218625'>goal.</span>
  </p><p><span m='219000'>Increasing</span> <span m='219532'>the</span> <span m='220064'>number</span>
  <span m='220596'>of</span> <span m='221129'>cache</span> <span m='221661'>lines</span>
  <span m='222193'>decreases</span> <span m='222726'>AMAT</span> <span m='223258'>by</span>
  <span m='223790'>decreasing</span> <span m='224323'>the</span> <span m='224855'>miss</span>
  <span m='225387'>ratio.</span> </p><p><span m='225920'>Increasing</span> <span m='226215'>the</span>
  <span m='226511'>block</span> <span m='226806'>size</span> <span m='227102'>of</span>
  <span m='227398'>the</span> <span m='227693'>cache</span> <span m='227989'>let</span>
  <span m='228285'>us</span> <span m='228580'>take</span> <span m='228876'>advantage</span>
  <span m='229171'>of</span> <span m='229467'>the</span> <span m='229763'>fast</span>
  <span m='230058'>column</span> <span m='230354'>accesses</span> <span m='230650'>in</span>
  <span m='231033'>a</span> <span m='231416'>DRAM</span> <span m='231800'>to</span>
  <span m='232183'>efficiently</span> <span m='232566'>load</span> <span m='232950'>a</span>
  <span m='233333'>whole</span> <span m='233716'>block</span> <span m='234100'>of</span>
  <span m='234483'>data</span> <span m='234866'>on</span> <span m='235250'>a</span>
  <span m='235633'>cache</span> <span m='236016'>miss.</span> </p><p><span m='236400'>The</span>
  <span m='236743'>expectation</span> <span m='237086'>was</span> <span m='237429'>that</span>
  <span m='237772'>this</span> <span m='238115'>would</span> <span m='238458'>improve</span>
  <span m='238801'>AMAT</span> <span m='239145'>by</span> <span m='239488'>increasing</span>
  <span m='239831'>the</span> <span m='240174'>number</span> <span m='240517'>of</span>
  <span m='240860'>hits</span> <span m='241203'>in</span> <span m='241546'>the</span>
  <span m='241890'>future</span> <span m='242566'>as</span> <span m='243242'>accesses</span>
  <span m='243918'>were</span> <span m='244595'>made</span> <span m='245271'>to</span>
  <span m='245947'>nearby</span> <span m='246623'>locations.</span> </p><p><span m='247300'>Increasing</span>
  <span m='247626'>the</span> <span m='247952'>number</span> <span m='248278'>of</span>
  <span m='248604'>ways</span> <span m='248930'>in</span> <span m='249256'>the</span>
  <span m='249582'>cache</span> <span m='249908'>reduced</span> <span m='250234'>the</span>
  <span m='250560'>possibility</span> <span m='250886'>of</span> <span m='251212'>cache</span>
  <span m='251538'>line</span> <span m='251864'>conflicts,</span> <span m='252190'>lowering</span>
  <span m='252767'>the</span> <span m='253345'>miss</span> <span m='253922'>ratio.</span>
  </p><p><span m='254500'>Choosing</span> <span m='254888'>the</span> <span m='255276'>least-recently</span>
  <span m='255664'>used</span> <span m='256053'>cache</span> <span m='256441'>line</span>
  <span m='256829'>for</span> <span m='257218'>replacement</span> <span m='257606'>minimized</span>
  <span m='257994'>the</span> <span m='258383'>impact</span> <span m='258771'>of</span>
  <span m='259159'>replacement</span> <span m='259548'>on</span> <span m='259913'>the</span>
  <span m='260278'>hit</span> <span m='260643'>ratio.</span> </p><p><span m='261009'>And,</span>
  <span m='261467'>finally,</span> <span m='261926'>we</span> <span m='262384'>chose</span>
  <span m='262843'>to</span> <span m='263302'>handle</span> <span m='263760'>writes</span>
  <span m='264219'>using</span> <span m='264678'>a</span> <span m='265136'>write-back</span>
  <span m='265595'>strategy</span> <span m='266054'>with</span> <span m='266512'>dirty</span>
  <span m='266971'>bits.</span> </p><p><span m='267430'>How</span> <span m='267760'>do</span>
  <span m='268091'>we</span> <span m='268422'>make</span> <span m='268753'>the</span>
  <span m='269084'>tradeoffs</span> <span m='269414'>among</span> <span m='269745'>all</span>
  <span m='270076'>these</span> <span m='270407'>architectural</span> <span m='270738'>choices?</span>
  </p><p><span m='271069'>As</span> <span m='271564'>usual,</span> <span m='272060'>we'll</span>
  <span m='272556'>simulate</span> <span m='273051'>different</span> <span m='273547'>cache</span>
  <span m='274043'>organizations</span> <span m='274539'>and</span> <span m='275034'>chose</span>
  <span m='275530'>the</span> <span m='276026'>architectural</span> <span m='276521'>mix</span>
  <span m='277017'>that</span> <span m='277513'>provides</span> <span m='278009'>the</span>
  <span m='278383'>best</span> <span m='278757'>performance</span> <span m='279131'>on</span>
  <span m='279506'>our</span> <span m='279880'>benchmark</span> <span m='280254'>programs.</span>
  </p>
type: course
uid: 5116a90cab3f9e26e120fdf0efc7eb33

---
None