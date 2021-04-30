---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: v-5w8ZDIa4w
  parent_uid: fd76e0b5b812ba61ea8755563396a941
  title: Video-YouTube-Stream
  type: Video
  uid: 0cb965ed005aa1dc19c5b9ba723cf34e
- id: 3Play-3Play YouTube id-Stream
  media_location: v-5w8ZDIa4w
  parent_uid: fd76e0b5b812ba61ea8755563396a941
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 88d491c4fc717ddda9a9689268add11c
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/v-5w8ZDIa4w/default.jpg
  parent_uid: fd76e0b5b812ba61ea8755563396a941
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: fdb0af6fb4d0a66e69770cd17a179d47
- id: v-5w8ZDIa4w.srt
  parent_uid: fd76e0b5b812ba61ea8755563396a941
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v4/jumps-and-branches-7-46-/v-5w8ZDIa4w.srt
  title: 3play caption file
  type: null
  uid: f58af5b8fe0127ae480b5d70a8b4fe38
- id: v-5w8ZDIa4w.pdf
  parent_uid: fd76e0b5b812ba61ea8755563396a941
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v4/jumps-and-branches-7-46-/v-5w8ZDIa4w.pdf
  title: 3play pdf file
  type: null
  uid: ff6da1952ab1d202d06be481722e6af4
- id: Caption-3Play YouTube id-SRT
  parent_uid: fd76e0b5b812ba61ea8755563396a941
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b859b76927e93532ffbbaefac7d0c9b3
- id: Transcript-3Play YouTube id-PDF
  parent_uid: fd76e0b5b812ba61ea8755563396a941
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: edd24a6e7550129bf01597fc6ecda45b
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_13-02-04_300k.mp4
  parent_uid: fd76e0b5b812ba61ea8755563396a941
  title: Video-Internet Archive-MP4
  type: Video
  uid: 651664425f96b34397426fe6ec435a3a
inline_embed_id: 65617679jumpsandbranches74635408697
layout: video
order_index: null
parent_uid: fca5d0f5a2802f79893c889a2c05a7b3
related_resources_text: ''
short_url: jumps-and-branches-7-46-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v4/jumps-and-branches-7-46-
template_type: Embed
title: Jumps and Branches (7:46)
transcript: <p><span m='390'>We're</span> <span m='713'>on</span> <span m='1036'>the</span>
  <span m='1360'>home</span> <span m='1683'>stretch</span> <span m='2006'>now.</span>
  </p><p><span m='2330'>For</span> <span m='2618'>all</span> <span m='2907'>the</span>
  <span m='3196'>instructions</span> <span m='3484'>up</span> <span m='3773'>until</span>
  <span m='4062'>now,</span> <span m='4350'>the</span> <span m='4639'>next</span>
  <span m='4928'>instruction</span> <span m='5216'>has</span> <span m='5505'>come</span>
  <span m='5794'>from</span> <span m='6082'>the</span> <span m='6371'>location</span>
  <span m='6660'>following</span> <span m='7208'>the</span> <span m='7757'>current</span>
  <span m='8306'>instruction</span> <span m='8855'>-</span> <span m='9404'>hence</span>
  <span m='9953'>the</span> <span m='10502'>"PC+4"</span> <span m='11051'>logic.</span>
  </p><p><span m='11600'>Branches</span> <span m='12021'>and</span> <span m='12443'>JMPs</span>
  <span m='12865'>change</span> <span m='13286'>that</span> <span m='13708'>by</span>
  <span m='14130'>altering</span> <span m='14551'>the</span> <span m='14973'>value</span>
  <span m='15395'>in</span> <span m='15816'>the</span> <span m='16238'>PC.</span>
  </p><p><span m='16660'>The</span> <span m='16944'>JMP</span> <span m='17228'>instruction</span>
  <span m='17512'>simply</span> <span m='17796'>takes</span> <span m='18080'>the</span>
  <span m='18364'>value</span> <span m='18648'>in</span> <span m='18932'>the</span>
  <span m='19217'>RA</span> <span m='19501'>register</span> <span m='19785'>and</span>
  <span m='20069'>makes</span> <span m='20353'>it</span> <span m='20637'>the</span>
  <span m='20921'>next</span> <span m='21205'>PC</span> <span m='21490'>value.</span>
  </p><p><span m='23039'>The</span> <span m='23360'>PCSEL</span> <span m='23681'>MUX</span>
  <span m='24002'>in</span> <span m='24324'>the</span> <span m='24645'>upper</span>
  <span m='24966'>left-hand</span> <span m='25287'>corner</span> <span m='25609'>lets</span>
  <span m='25930'>the</span> <span m='26251'>control</span> <span m='26572'>logic</span>
  <span m='26894'>select</span> <span m='27215'>the</span> <span m='27536'>source</span>
  <span m='27857'>of</span> <span m='28179'>the</span> <span m='28704'>next</span>
  <span m='29229'>PC</span> <span m='29754'>value.</span> </p><p><span m='30279'>When</span>
  <span m='30755'>PCSEL</span> <span m='31231'>is</span> <span m='31707'>0,</span>
  <span m='32183'>the</span> <span m='32659'>incremented</span> <span m='33135'>PC</span>
  <span m='33611'>value</span> <span m='34087'>is</span> <span m='34563'>chosen.</span>
  </p><p><span m='35039'>When</span> <span m='35438'>PCSEL</span> <span m='35837'>is</span>
  <span m='36236'>2,</span> <span m='36635'>the</span> <span m='37034'>value</span>
  <span m='37434'>of</span> <span m='37833'>the</span> <span m='38232'>RA</span> <span
  m='38631'>register</span> <span m='39030'>is</span> <span m='39429'>chosen.</span>
  </p><p><span m='39829'>We'll</span> <span m='40119'>see</span> <span m='40409'>how</span>
  <span m='40699'>the</span> <span m='40989'>other</span> <span m='41279'>inputs</span>
  <span m='41569'>to</span> <span m='41859'>the</span> <span m='42149'>PCSEL</span>
  <span m='42439'>MUX</span> <span m='42729'>are</span> <span m='43019'>used</span>
  <span m='43309'>in</span> <span m='43599'>just</span> <span m='43889'>a</span> <span
  m='44179'>moment.</span> </p><p><span m='44469'>The</span> <span m='44805'>JMP</span>
  <span m='45141'>and</span> <span m='45477'>branch</span> <span m='45813'>instructions</span>
  <span m='46150'>also</span> <span m='46486'>cause</span> <span m='46822'>the</span>
  <span m='47158'>address</span> <span m='47495'>of</span> <span m='47831'>the</span>
  <span m='48167'>following</span> <span m='48503'>instruction,</span> <span m='48840'>i.e.,</span>
  <span m='49325'>the</span> <span m='49810'>PC+4</span> <span m='50296'>value,</span>
  <span m='50781'>to</span> <span m='51267'>be</span> <span m='51752'>written</span>
  <span m='52238'>to</span> <span m='52723'>the</span> <span m='53209'>RC</span> <span
  m='53694'>register.</span> </p><p><span m='54180'>When</span> <span m='54549'>WDSEL</span>
  <span m='54919'>is</span> <span m='55288'>0,</span> <span m='55658'>the</span> <span
  m='56027'>"0"</span> <span m='56397'>input</span> <span m='56766'>of</span> <span
  m='57136'>the</span> <span m='57505'>WDSEL</span> <span m='57875'>MUX</span> <span
  m='58244'>is</span> <span m='58614'>used</span> <span m='58983'>to</span> <span
  m='59353'>select</span> <span m='59722'>the</span> <span m='60092'>PC+4</span> <span
  m='60461'>value</span> <span m='60831'>as</span> <span m='61200'>the</span> <span
  m='61570'>write-back</span> <span m='62959'>data.</span> </p><p><span m='64349'>Here's</span>
  <span m='64742'>how</span> <span m='65136'>the</span> <span m='65529'>data</span>
  <span m='65923'>flow</span> <span m='66316'>works.</span> </p><p><span m='66710'>The</span>
  <span m='67056'>output</span> <span m='67402'>of</span> <span m='67748'>the</span>
  <span m='68095'>PC+4</span> <span m='68441'>adder</span> <span m='68787'>is</span>
  <span m='69133'>is</span> <span m='69480'>routed</span> <span m='69826'>to</span>
  <span m='70172'>the</span> <span m='70518'>register</span> <span m='70865'>file</span>
  <span m='71211'>and</span> <span m='71557'>WERF</span> <span m='71903'>is</span>
  <span m='72250'>set</span> <span m='72596'>to</span> <span m='72942'>1</span> <span
  m='73289'>to</span> <span m='73567'>enable</span> <span m='73846'>that</span> <span
  m='74124'>value</span> <span m='74403'>to</span> <span m='74681'>be</span> <span
  m='74960'>written</span> <span m='75238'>at</span> <span m='75517'>the</span> <span
  m='75795'>end</span> <span m='76074'>of</span> <span m='76352'>the</span> <span
  m='76631'>cycle.</span> </p><p><span m='76910'>Meanwhile,</span> <span m='77304'>the</span>
  <span m='77699'>value</span> <span m='78094'>of</span> <span m='78489'>RA</span>
  <span m='78884'>register</span> <span m='79279'>coming</span> <span m='79674'>out</span>
  <span m='80069'>of</span> <span m='80464'>the</span> <span m='80859'>register</span>
  <span m='81254'>file</span> <span m='81649'>is</span> <span m='82044'>connected</span>
  <span m='82439'>to</span> <span m='82834'>the</span> <span m='83229'>"2"</span>
  <span m='83579'>input</span> <span m='83929'>of</span> <span m='84279'>the</span>
  <span m='84629'>PCSEL</span> <span m='84979'>MUX.</span> </p><p><span m='85330'>So</span>
  <span m='85621'>setting</span> <span m='85912'>PCSEL</span> <span m='86203'>to</span>
  <span m='86494'>2</span> <span m='86785'>will</span> <span m='87076'>select</span>
  <span m='87367'>the</span> <span m='87658'>value</span> <span m='87949'>in</span>
  <span m='88240'>the</span> <span m='88531'>RA</span> <span m='88822'>register</span>
  <span m='89113'>as</span> <span m='89404'>the</span> <span m='89695'>next</span>
  <span m='89986'>value</span> <span m='90277'>for</span> <span m='90568'>the</span>
  <span m='90860'>PC.</span> </p><p><span m='91960'>The</span> <span m='92225'>rest</span>
  <span m='92491'>of</span> <span m='92756'>the</span> <span m='93022'>control</span>
  <span m='93288'>signals</span> <span m='93553'>are</span> <span m='93819'>"don't</span>
  <span m='94085'>cares",</span> <span m='94350'>except,</span> <span m='94616'>of</span>
  <span m='94881'>course</span> <span m='95147'>for</span> <span m='95413'>the</span>
  <span m='95678'>memory</span> <span m='95944'>write</span> <span m='96210'>enable</span>
  <span m='96513'>(MWR),</span> <span m='96817'>which</span> <span m='97121'>can</span>
  <span m='97425'>never</span> <span m='97728'>be</span> <span m='98032'>"don't</span>
  <span m='98336'>care"</span> <span m='98640'>lest</span> <span m='98943'>we</span>
  <span m='99247'>cause</span> <span m='99551'>an</span> <span m='99855'>accidental</span>
  <span m='100158'>write</span> <span m='100462'>to</span> <span m='100766'>some</span>
  <span m='101070'>memory</span> <span m='102190'>location.</span> </p><p><span m='103310'>The</span>
  <span m='103654'>branch</span> <span m='103998'>instruction</span> <span m='104342'>requires</span>
  <span m='104687'>an</span> <span m='105031'>additional</span> <span m='105375'>adder</span>
  <span m='105720'>to</span> <span m='106064'>compute</span> <span m='106408'>the</span>
  <span m='106752'>target</span> <span m='107097'>address</span> <span m='107441'>by</span>
  <span m='107785'>adding</span> <span m='108130'>the</span> <span m='108606'>scaled</span>
  <span m='109083'>offset</span> <span m='109560'>from</span> <span m='110037'>the</span>
  <span m='110514'>instruction's</span> <span m='110991'>literal</span> <span m='111467'>field</span>
  <span m='111944'>to</span> <span m='112421'>the</span> <span m='112898'>current</span>
  <span m='113375'>PC+4</span> <span m='113852'>value.</span> </p><p><span m='114329'>Remember</span>
  <span m='114618'>that</span> <span m='114907'>we</span> <span m='115197'>scale</span>
  <span m='115486'>the</span> <span m='115776'>offset</span> <span m='116065'>by</span>
  <span m='116355'>a</span> <span m='116644'>factor</span> <span m='116934'>of</span>
  <span m='117223'>4</span> <span m='117513'>to</span> <span m='117802'>convert</span>
  <span m='118092'>it</span> <span m='118381'>from</span> <span m='118671'>the</span>
  <span m='118960'>word</span> <span m='119250'>offset</span> <span m='119539'>stored</span>
  <span m='119829'>in</span> <span m='120247'>the</span> <span m='120665'>literal</span>
  <span m='121083'>to</span> <span m='121502'>the</span> <span m='121920'>byte</span>
  <span m='122338'>offset</span> <span m='122756'>required</span> <span m='123175'>for</span>
  <span m='123593'>the</span> <span m='124011'>PC.</span> </p><p><span m='124430'>The</span>
  <span m='124735'>output</span> <span m='125040'>of</span> <span m='125345'>the</span>
  <span m='125650'>offset</span> <span m='125956'>adder</span> <span m='126261'>becomes</span>
  <span m='126566'>the</span> <span m='126871'>"1"</span> <span m='127177'>input</span>
  <span m='127482'>to</span> <span m='127787'>the</span> <span m='128092'>PCSEL</span>
  <span m='128398'>MUX,</span> <span m='128703'>where,</span> <span m='129008'>if</span>
  <span m='129313'>the</span> <span m='129619'>branch</span> <span m='130019'>is</span>
  <span m='130419'>taken,</span> <span m='130819'>it</span> <span m='131219'>will</span>
  <span m='131619'>become</span> <span m='132019'>the</span> <span m='132419'>next</span>
  <span m='132819'>value</span> <span m='133219'>of</span> <span m='133619'>the</span>
  <span m='134019'>PC.</span> </p><p><span m='134420'>Note</span> <span m='134789'>that</span>
  <span m='135159'>multiplying</span> <span m='135529'>by</span> <span m='135899'>4</span>
  <span m='136269'>is</span> <span m='136639'>easily</span> <span m='137009'>accomplished</span>
  <span m='137379'>by</span> <span m='137749'>shifting</span> <span m='138119'>the</span>
  <span m='138489'>literal</span> <span m='138859'>two</span> <span m='139229'>bits</span>
  <span m='139599'>to</span> <span m='139969'>the</span> <span m='140339'>left,</span>
  <span m='140709'>which</span> <span m='141021'>inserts</span> <span m='141334'>two</span>
  <span m='141647'>0-bits</span> <span m='141960'>at</span> <span m='142273'>the</span>
  <span m='142585'>low-order</span> <span m='142898'>end</span> <span m='143211'>of</span>
  <span m='143524'>the</span> <span m='143837'>value.</span> </p><p><span m='144150'>And,</span>
  <span m='144680'>like</span> <span m='145210'>before,</span> <span m='145740'>the</span>
  <span m='146270'>sign-extension</span> <span m='146800'>just</span> <span m='147330'>requires</span>
  <span m='147860'>replicating</span> <span m='148390'>bit</span> <span m='148920'>ID[15],</span>
  <span m='149450'>in</span> <span m='149980'>this</span> <span m='150510'>case</span>
  <span m='151040'>fourteen</span> <span m='152084'>times.</span> </p><p><span m='153129'>So</span>
  <span m='153524'>implementing</span> <span m='153920'>this</span> <span m='154316'>complicated-looking</span>
  <span m='154712'>expression</span> <span m='155107'>requires</span> <span m='155503'>care</span>
  <span m='155899'>in</span> <span m='156295'>wiring</span> <span m='156691'>up</span>
  <span m='157086'>the</span> <span m='157482'>input</span> <span m='157878'>to</span>
  <span m='158274'>the</span> <span m='158670'>offset</span> <span m='159406'>adder,</span>
  <span m='160143'>but</span> <span m='160880'>no</span> <span m='161616'>additional</span>
  <span m='162353'>logic!</span> </p><p><span m='163090'>We</span> <span m='163383'>do</span>
  <span m='163677'>need</span> <span m='163971'>some</span> <span m='164265'>logic</span>
  <span m='164559'>to</span> <span m='164853'>determine</span> <span m='165146'>if</span>
  <span m='165440'>we</span> <span m='165734'>should</span> <span m='166028'>branch</span>
  <span m='166322'>or</span> <span m='166616'>not.</span> </p><p><span m='166910'>The</span>
  <span m='167263'>32-bit</span> <span m='167617'>NOR</span> <span m='167970'>gate</span>
  <span m='168324'>connected</span> <span m='168677'>to</span> <span m='169031'>the</span>
  <span m='169384'>first</span> <span m='169738'>read</span> <span m='170091'>port</span>
  <span m='170445'>of</span> <span m='170798'>the</span> <span m='171152'>register</span>
  <span m='171505'>file</span> <span m='171859'>tests</span> <span m='172212'>the</span>
  <span m='172566'>value</span> <span m='172920'>of</span> <span m='173170'>the</span>
  <span m='173420'>RA</span> <span m='173670'>register.</span> </p><p><span m='173920'>The</span>
  <span m='174295'>NOR's</span> <span m='174670'>output</span> <span m='175045'>Z</span>
  <span m='175420'>will</span> <span m='175795'>be</span> <span m='176171'>1</span>
  <span m='176546'>if</span> <span m='176921'>all</span> <span m='177296'>the</span>
  <span m='177671'>bits</span> <span m='178047'>of</span> <span m='178422'>the</span>
  <span m='178797'>RA</span> <span m='179172'>register</span> <span m='179547'>value</span>
  <span m='179923'>are</span> <span m='180298'>0,</span> <span m='180673'>and</span>
  <span m='181048'>0</span> <span m='181423'>otherwise.</span> </p><p><span m='181799'>The</span>
  <span m='182287'>Z</span> <span m='182776'>value</span> <span m='183265'>can</span>
  <span m='183754'>be</span> <span m='184243'>used</span> <span m='184732'>by</span>
  <span m='185221'>the</span> <span m='185710'>control</span> <span m='186198'>logic</span>
  <span m='186687'>to</span> <span m='187176'>determine</span> <span m='187665'>the</span>
  <span m='188154'>correct</span> <span m='188643'>value</span> <span m='189132'>for</span>
  <span m='189621'>PCSEL.</span> </p><p><span m='190110'>If</span> <span m='190479'>Z</span>
  <span m='190849'>indicates</span> <span m='191219'>the</span> <span m='191589'>branch</span>
  <span m='191959'>is</span> <span m='192329'>taken,</span> <span m='192699'>PCSEL</span>
  <span m='193069'>will</span> <span m='193439'>be</span> <span m='193809'>1</span>
  <span m='194179'>and</span> <span m='194549'>the</span> <span m='194919'>output</span>
  <span m='195289'>of</span> <span m='195659'>the</span> <span m='196029'>offset</span>
  <span m='196399'>adder</span> <span m='196769'>becomes</span> <span m='197262'>the</span>
  <span m='197755'>next</span> <span m='198248'>value</span> <span m='198741'>of</span>
  <span m='199234'>the</span> <span m='199727'>PC.</span> </p><p><span m='200220'>If</span>
  <span m='200560'>the</span> <span m='200901'>branch</span> <span m='201241'>is</span>
  <span m='201582'>not</span> <span m='201922'>taken,</span> <span m='202263'>PCSEL</span>
  <span m='202604'>will</span> <span m='202944'>be</span> <span m='203285'>0</span>
  <span m='203625'>and</span> <span m='203966'>execution</span> <span m='204307'>will</span>
  <span m='204647'>continue</span> <span m='204988'>with</span> <span m='205328'>the</span>
  <span m='205669'>next</span> <span m='206010'>instruction</span> <span m='207510'>at</span>
  <span m='209010'>PC+4.</span> </p><p><span m='210510'>As</span> <span m='210828'>in</span>
  <span m='211147'>the</span> <span m='211466'>JMP</span> <span m='211785'>instruction,</span>
  <span m='212104'>the</span> <span m='212422'>PC+4</span> <span m='212741'>value</span>
  <span m='213060'>is</span> <span m='213379'>routed</span> <span m='213698'>to</span>
  <span m='214017'>the</span> <span m='214335'>register</span> <span m='214654'>file</span>
  <span m='214973'>to</span> <span m='215292'>be</span> <span m='215611'>written</span>
  <span m='215930'>into</span> <span m='216300'>the</span> <span m='216670'>RC</span>
  <span m='217040'>register</span> <span m='217410'>at</span> <span m='217780'>end</span>
  <span m='218150'>of</span> <span m='218520'>the</span> <span m='218890'>cycle.</span>
  </p><p><span m='219260'>Meanwhile,</span> <span m='219636'>the</span> <span m='220012'>value</span>
  <span m='220389'>of</span> <span m='220765'>Z</span> <span m='221142'>is</span>
  <span m='221518'>computed</span> <span m='221894'>from</span> <span m='222271'>the</span>
  <span m='222647'>value</span> <span m='223024'>of</span> <span m='223400'>the</span>
  <span m='223776'>RA</span> <span m='224153'>register</span> <span m='224529'>while</span>
  <span m='224906'>the</span> <span m='225282'>branch</span> <span m='225659'>offset</span>
  <span m='226139'>adder</span> <span m='226619'>computes</span> <span m='227099'>the</span>
  <span m='227579'>address</span> <span m='228059'>of</span> <span m='228539'>the</span>
  <span m='229019'>branch</span> <span m='229499'>target.</span> </p><p><span m='229980'>The</span>
  <span m='230272'>output</span> <span m='230565'>of</span> <span m='230858'>the</span>
  <span m='231151'>offset</span> <span m='231443'>adder</span> <span m='231736'>is</span>
  <span m='232029'>routed</span> <span m='232322'>to</span> <span m='232615'>the</span>
  <span m='232907'>PCSEL</span> <span m='233200'>MUX</span> <span m='233493'>where</span>
  <span m='233786'>the</span> <span m='234078'>value</span> <span m='234371'>of</span>
  <span m='234664'>the</span> <span m='234957'>3-bit</span> <span m='235250'>PCSEL</span>
  <span m='235688'>control</span> <span m='236127'>signal,</span> <span m='236566'>computed</span>
  <span m='237004'>by</span> <span m='237443'>the</span> <span m='237882'>control</span>
  <span m='238320'>logic</span> <span m='238759'>based</span> <span m='239198'>on</span>
  <span m='239636'>Z,</span> <span m='240075'>determines</span> <span m='240514'>whether</span>
  <span m='240952'>the</span> <span m='241391'>next</span> <span m='241830'>PC</span>
  <span m='242332'>value</span> <span m='242834'>is</span> <span m='243336'>the</span>
  <span m='243838'>branch</span> <span m='244340'>target</span> <span m='244842'>or</span>
  <span m='245344'>the</span> <span m='245846'>PC+4</span> <span m='246348'>value.</span>
  </p><p><span m='246850'>The</span> <span m='247299'>remaining</span> <span m='247748'>control</span>
  <span m='248197'>signals</span> <span m='248647'>are</span> <span m='249096'>unused</span>
  <span m='249545'>and</span> <span m='249995'>set</span> <span m='250444'>to</span>
  <span m='250893'>their</span> <span m='251342'>default</span> <span m='251792'>"don't</span>
  <span m='252241'>care"</span> <span m='252690'>values.</span> </p><p><span m='253140'>We</span>
  <span m='253624'>have</span> <span m='254108'>one</span> <span m='254592'>last</span>
  <span m='255076'>instruction</span> <span m='255560'>to</span> <span m='256045'>introduce:</span>
  <span m='256529'>the</span> <span m='257013'>LDR</span> <span m='257497'>or</span>
  <span m='257981'>load-relative</span> <span m='258465'>instruction.</span> </p><p><span
  m='258950'>LDR</span> <span m='259274'>behaves</span> <span m='259598'>like</span>
  <span m='259923'>a</span> <span m='260247'>normal</span> <span m='260571'>LD</span>
  <span m='260896'>instruction</span> <span m='261220'>except</span> <span m='261545'>that</span>
  <span m='261869'>the</span> <span m='262193'>memory</span> <span m='262518'>address</span>
  <span m='262842'>is</span> <span m='263166'>taken</span> <span m='263491'>from</span>
  <span m='263815'>the</span> <span m='264140'>branch</span> <span m='264970'>offset</span>
  <span m='265800'>adder.</span> </p><p><span m='266630'>Why</span> <span m='266981'>would</span>
  <span m='267333'>it</span> <span m='267685'>be</span> <span m='268037'>useful</span>
  <span m='268389'>to</span> <span m='268741'>load</span> <span m='269093'>a</span>
  <span m='269445'>value</span> <span m='269796'>from</span> <span m='270148'>a</span>
  <span m='270500'>location</span> <span m='270852'>near</span> <span m='271204'>the</span>
  <span m='271556'>LDR</span> <span m='271908'>instruction?</span> </p><p><span m='272260'>Normally</span>
  <span m='272584'>such</span> <span m='272909'>addresses</span> <span m='273233'>would</span>
  <span m='273558'>refer</span> <span m='273883'>to</span> <span m='274207'>the</span>
  <span m='274532'>neighboring</span> <span m='274856'>instructions,</span> <span
  m='275181'>so</span> <span m='275506'>why</span> <span m='275830'>would</span> <span
  m='276155'>we</span> <span m='276480'>want</span> <span m='276865'>to</span> <span
  m='277251'>load</span> <span m='277637'>the</span> <span m='278023'>binary</span>
  <span m='278409'>encoding</span> <span m='278795'>of</span> <span m='279181'>an</span>
  <span m='279567'>instruction</span> <span m='279952'>into</span> <span m='280338'>a</span>
  <span m='280724'>register</span> <span m='281110'>to</span> <span m='281496'>be</span>
  <span m='281882'>used</span> <span m='282268'>as</span> <span m='282654'>data?</span>
  </p><p><span m='283040'>The</span> <span m='283359'>use</span> <span m='283678'>case</span>
  <span m='283998'>for</span> <span m='284317'>LDR</span> <span m='284637'>is</span>
  <span m='284956'>accessing</span> <span m='285276'>large</span> <span m='285595'>constants</span>
  <span m='285915'>that</span> <span m='286234'>have</span> <span m='286553'>to</span>
  <span m='286873'>be</span> <span m='287192'>stored</span> <span m='287512'>in</span>
  <span m='287831'>main</span> <span m='288151'>memory</span> <span m='288470'>because</span>
  <span m='288790'>they</span> <span m='289180'>are</span> <span m='289571'>too</span>
  <span m='289962'>large</span> <span m='290352'>to</span> <span m='290743'>fit</span>
  <span m='291134'>into</span> <span m='291525'>the</span> <span m='291915'>16-bit</span>
  <span m='292306'>literal</span> <span m='292697'>field</span> <span m='293087'>of</span>
  <span m='293478'>an</span> <span m='293869'>instruction.</span> </p><p><span m='294260'>In</span>
  <span m='294753'>the</span> <span m='295247'>example</span> <span m='295740'>shown</span>
  <span m='296234'>here,</span> <span m='296727'>the</span> <span m='297221'>compiled</span>
  <span m='297715'>code</span> <span m='298208'>needs</span> <span m='298702'>to</span>
  <span m='299195'>load</span> <span m='299689'>the</span> <span m='300182'>constant</span>
  <span m='300676'>123456.</span> </p><p><span m='301170'>So</span> <span m='301603'>it</span>
  <span m='302037'>uses</span> <span m='302470'>an</span> <span m='302904'>LDR</span>
  <span m='303337'>instruction</span> <span m='303771'>that</span> <span m='304204'>refers</span>
  <span m='304638'>to</span> <span m='305071'>a</span> <span m='305505'>nearby</span>
  <span m='305938'>location</span> <span m='306372'>C1:</span> <span m='306805'>that</span>
  <span m='307239'>has</span> <span m='307672'>been</span> <span m='308106'>initialized</span>
  <span m='308540'>with</span> <span m='309285'>the</span> <span m='310030'>required</span>
  <span m='310775'>value.</span> </p><p><span m='311520'>Since</span> <span m='311807'>this</span>
  <span m='312095'>read-only</span> <span m='312382'>constant</span> <span m='312670'>is</span>
  <span m='312958'>part</span> <span m='313245'>of</span> <span m='313533'>the</span>
  <span m='313821'>program,</span> <span m='314108'>it</span> <span m='314396'>makes</span>
  <span m='314684'>sense</span> <span m='314971'>to</span> <span m='315259'>store</span>
  <span m='315547'>it</span> <span m='315834'>with</span> <span m='316122'>the</span>
  <span m='316410'>instructions</span> <span m='316885'>for</span> <span m='317360'>the</span>
  <span m='317835'>program,</span> <span m='318310'>usually</span> <span m='318785'>just</span>
  <span m='319260'>after</span> <span m='319735'>the</span> <span m='320210'>code</span>
  <span m='320685'>for</span> <span m='321160'>a</span> <span m='321635'>procedure.</span>
  </p><p><span m='322110'>Note</span> <span m='322369'>that</span> <span m='322628'>we</span>
  <span m='322888'>have</span> <span m='323147'>to</span> <span m='323407'>be</span>
  <span m='323666'>careful</span> <span m='323926'>to</span> <span m='324185'>place</span>
  <span m='324445'>the</span> <span m='324704'>storage</span> <span m='324963'>location</span>
  <span m='325223'>so</span> <span m='325482'>that</span> <span m='325742'>it</span>
  <span m='326001'>won't</span> <span m='326261'>be</span> <span m='326520'>executed</span>
  <span m='326780'>as</span> <span m='327630'>an</span> <span m='328480'>instruction!</span>
  </p><p><span m='329330'>To</span> <span m='329647'>route</span> <span m='329965'>the</span>
  <span m='330282'>output</span> <span m='330600'>of</span> <span m='330918'>the</span>
  <span m='331235'>offset</span> <span m='331553'>adder</span> <span m='331871'>to</span>
  <span m='332188'>the</span> <span m='332506'>main</span> <span m='332824'>memory</span>
  <span m='333141'>address</span> <span m='333459'>port,</span> <span m='333777'>we'll</span>
  <span m='334094'>add</span> <span m='334412'>ASEL</span> <span m='334730'>MUX</span>
  <span m='335110'>so</span> <span m='335491'>we</span> <span m='335871'>can</span>
  <span m='336252'>select</span> <span m='336632'>either</span> <span m='337013'>the</span>
  <span m='337393'>RA</span> <span m='337774'>register</span> <span m='338155'>value</span>
  <span m='338535'>(when</span> <span m='338916'>ASEL=0)</span> <span m='339296'>or</span>
  <span m='339677'>the</span> <span m='340057'>output</span> <span m='340438'>of</span>
  <span m='340818'>the</span> <span m='341199'>offset</span> <span m='341580'>adder</span>
  <span m='342281'>(when</span> <span m='342982'>ASEL=1)</span> <span m='343683'>as</span>
  <span m='344385'>the</span> <span m='345086'>first</span> <span m='345787'>ALU</span>
  <span m='346488'>operand.</span> </p><p><span m='347190'>For</span> <span m='347595'>LDR,</span>
  <span m='348001'>ASEL</span> <span m='348407'>will</span> <span m='348813'>be</span>
  <span m='349219'>1,</span> <span m='349625'>and</span> <span m='350031'>we'll</span>
  <span m='350437'>then</span> <span m='350842'>ask</span> <span m='351248'>the</span>
  <span m='351654'>ALU</span> <span m='352060'>compute</span> <span m='352466'>the</span>
  <span m='352872'>Boolean</span> <span m='353278'>operation</span> <span m='353684'>"A",</span>
  <span m='354090'>i.e.,</span> <span m='354539'>the</span> <span m='354988'>boolean</span>
  <span m='355437'>function</span> <span m='355887'>whose</span> <span m='356336'>output</span>
  <span m='356785'>is</span> <span m='357235'>just</span> <span m='357684'>the</span>
  <span m='358133'>value</span> <span m='358582'>of</span> <span m='359032'>the</span>
  <span m='359481'>first</span> <span m='359930'>operand.</span> </p><p><span m='360380'>This</span>
  <span m='360656'>value</span> <span m='360933'>then</span> <span m='361210'>appears</span>
  <span m='361487'>on</span> <span m='361764'>the</span> <span m='362041'>ALU</span>
  <span m='362318'>output,</span> <span m='362595'>which</span> <span m='362871'>is</span>
  <span m='363148'>connected</span> <span m='363425'>to</span> <span m='363702'>the</span>
  <span m='363979'>main</span> <span m='364256'>memory</span> <span m='364533'>address</span>
  <span m='364810'>port</span> <span m='365227'>and</span> <span m='365644'>the</span>
  <span m='366061'>remainder</span> <span m='366478'>of</span> <span m='366895'>the</span>
  <span m='367312'>execution</span> <span m='367730'>proceeds</span> <span m='368147'>just</span>
  <span m='368564'>like</span> <span m='368981'>it</span> <span m='369398'>did</span>
  <span m='369815'>for</span> <span m='370232'>LD.</span> </p><p><span m='370650'>This</span>
  <span m='371114'>seems</span> <span m='371578'>a</span> <span m='372042'>bit</span>
  <span m='372506'>complicated!</span> </p><p><span m='372970'>Mr.</span> <span m='373274'>Blue</span>
  <span m='373578'>has</span> <span m='373883'>a</span> <span m='374187'>good</span>
  <span m='374491'>question:</span> <span m='374796'>why</span> <span m='375100'>not</span>
  <span m='375405'>just</span> <span m='375709'>put</span> <span m='376013'>the</span>
  <span m='376318'>ASEL</span> <span m='376622'>MUX</span> <span m='376926'>on</span>
  <span m='377231'>the</span> <span m='377535'>wire</span> <span m='377840'>leading</span>
  <span m='378372'>to</span> <span m='378905'>the</span> <span m='379437'>main</span>
  <span m='379970'>memory</span> <span m='380502'>address</span> <span m='381035'>port</span>
  <span m='381567'>and</span> <span m='382100'>bypass</span> <span m='382632'>the</span>
  <span m='383165'>ALU</span> <span m='383697'>altogether?</span> </p><p><span m='384230'>The</span>
  <span m='384555'>answer</span> <span m='384881'>has</span> <span m='385206'>to</span>
  <span m='385532'>do</span> <span m='385858'>with</span> <span m='386183'>the</span>
  <span m='386509'>amount</span> <span m='386835'>of</span> <span m='387160'>time</span>
  <span m='387486'>needed</span> <span m='387811'>to</span> <span m='388137'>compute</span>
  <span m='388463'>the</span> <span m='388788'>memory</span> <span m='389114'>address.</span>
  </p><p><span m='389440'>If</span> <span m='389801'>we</span> <span m='390163'>moved</span>
  <span m='390524'>the</span> <span m='390886'>ASEL</span> <span m='391247'>MUX</span>
  <span m='391609'>here,</span> <span m='391971'>the</span> <span m='392332'>data</span>
  <span m='392694'>flow</span> <span m='393055'>for</span> <span m='393417'>LD</span>
  <span m='393778'>and</span> <span m='394140'>ST</span> <span m='394502'>addresses</span>
  <span m='394863'>would</span> <span m='395225'>then</span> <span m='395586'>pass</span>
  <span m='395948'>through</span> <span m='396310'>two</span> <span m='396708'>MUXes,</span>
  <span m='397107'>the</span> <span m='397506'>BSEL</span> <span m='397905'>MUX</span>
  <span m='398304'>and</span> <span m='398702'>the</span> <span m='399101'>ASEL</span>
  <span m='399500'>MUX,</span> <span m='399899'>slowing</span> <span m='400298'>down</span>
  <span m='400697'>the</span> <span m='401095'>arrival</span> <span m='401494'>of</span>
  <span m='401893'>the</span> <span m='402292'>address</span> <span m='402691'>by</span>
  <span m='403090'>a</span> <span m='403840'>small</span> <span m='404590'>amount.</span>
  </p><p><span m='405340'>This</span> <span m='405606'>may</span> <span m='405873'>not</span>
  <span m='406140'>seem</span> <span m='406406'>like</span> <span m='406673'>a</span>
  <span m='406940'>big</span> <span m='407206'>deal,</span> <span m='407473'>but</span>
  <span m='407740'>the</span> <span m='408006'>additional</span> <span m='408273'>time</span>
  <span m='408540'>would</span> <span m='408806'>have</span> <span m='409073'>to</span>
  <span m='409340'>be</span> <span m='409606'>added</span> <span m='409873'>the</span>
  <span m='410140'>clock</span> <span m='410639'>period,</span> <span m='411138'>thus</span>
  <span m='411637'>slowing</span> <span m='412136'>down</span> <span m='412635'>every</span>
  <span m='413134'>instruction</span> <span m='413633'>by</span> <span m='414132'>a</span>
  <span m='414631'>little</span> <span m='415130'>bit.</span> </p><p><span m='415630'>When</span>
  <span m='416030'>executing</span> <span m='416430'>billions</span> <span m='416830'>of</span>
  <span m='417230'>instructions,</span> <span m='417630'>a</span> <span m='418030'>little</span>
  <span m='418430'>extra</span> <span m='418830'>time</span> <span m='419230'>on</span>
  <span m='419630'>each</span> <span m='420030'>instruction</span> <span m='420430'>really</span>
  <span m='420830'>impacts</span> <span m='421532'>the</span> <span m='422235'>overall</span>
  <span m='422938'>performance</span> <span m='423641'>of</span> <span m='424344'>the</span>
  <span m='425047'>processor.</span> </p><p><span m='425750'>By</span> <span m='426086'>placing</span>
  <span m='426422'>the</span> <span m='426758'>ASEL</span> <span m='427095'>MUX</span>
  <span m='427431'>where</span> <span m='427767'>we</span> <span m='428103'>did,</span>
  <span m='428440'>its</span> <span m='428776'>propagation</span> <span m='429112'>delay</span>
  <span m='429448'>overlaps</span> <span m='429785'>that</span> <span m='430121'>of</span>
  <span m='430457'>the</span> <span m='430793'>BSEL</span> <span m='431130'>MUX,</span>
  <span m='431686'>so</span> <span m='432242'>the</span> <span m='432798'>increased</span>
  <span m='433354'>functionality</span> <span m='433910'>it</span> <span m='434466'>provides</span>
  <span m='435023'>comes</span> <span m='435579'>with</span> <span m='436135'>no</span>
  <span m='436691'>cost</span> <span m='437247'>in</span> <span m='437803'>performance.</span>
  </p><p><span m='438360'>Here's</span> <span m='438721'>the</span> <span m='439082'>data</span>
  <span m='439443'>flow</span> <span m='439805'>for</span> <span m='440166'>the</span>
  <span m='440527'>LDR</span> <span m='440888'>instruction.</span> </p><p><span m='441250'>The</span>
  <span m='441610'>output</span> <span m='441970'>of</span> <span m='442330'>the</span>
  <span m='442690'>offset</span> <span m='443050'>adder</span> <span m='443410'>is</span>
  <span m='443770'>routed</span> <span m='444130'>through</span> <span m='444490'>the</span>
  <span m='444850'>ASEL</span> <span m='445210'>MUX</span> <span m='445570'>to</span>
  <span m='445930'>the</span> <span m='446290'>ALU.</span> </p><p><span m='446650'>The</span>
  <span m='447033'>ALU</span> <span m='447416'>performs</span> <span m='447800'>the</span>
  <span m='448183'>Boolean</span> <span m='448566'>computation</span> <span m='448950'>"A"</span>
  <span m='449333'>and</span> <span m='449716'>the</span> <span m='450100'>result</span>
  <span m='450483'>becomes</span> <span m='450866'>the</span> <span m='451250'>address</span>
  <span m='451633'>for</span> <span m='452016'>main</span> <span m='452400'>memory.</span>
  </p><p><span m='453780'>The</span> <span m='454115'>returning</span> <span m='454450'>data</span>
  <span m='454785'>is</span> <span m='455120'>routed</span> <span m='455455'>through</span>
  <span m='455790'>the</span> <span m='456125'>WDSEL</span> <span m='456460'>MUX</span>
  <span m='456795'>so</span> <span m='457130'>it</span> <span m='457465'>can</span>
  <span m='457800'>be</span> <span m='458135'>written</span> <span m='458470'>into</span>
  <span m='458805'>the</span> <span m='459140'>RC</span> <span m='459475'>register</span>
  <span m='459810'>at</span> <span m='460226'>the</span> <span m='460643'>end</span>
  <span m='461060'>of</span> <span m='461476'>the</span> <span m='461893'>cycle.</span>
  </p><p><span m='462310'>The</span> <span m='462685'>remaining</span> <span m='463060'>control</span>
  <span m='463435'>values</span> <span m='463810'>are</span> <span m='464185'>given</span>
  <span m='464560'>their</span> <span m='464935'>usual</span> <span m='465310'>default</span>
  <span m='465685'>values.</span> </p>
type: course
uid: fd76e0b5b812ba61ea8755563396a941

---
None