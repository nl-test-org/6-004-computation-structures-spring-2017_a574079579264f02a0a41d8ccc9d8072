---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: ZUWb9HHXGHM
  parent_uid: 3dd2be06225ef8ed708bab00b7fa8432
  title: Video-YouTube-Stream
  type: Video
  uid: 8f613c44ebbdb3ff67a1e538c17cc750
- id: 3Play-3Play YouTube id-Stream
  media_location: ZUWb9HHXGHM
  parent_uid: 3dd2be06225ef8ed708bab00b7fa8432
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: d2ac02cf16befcda265c796e1d671f43
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/ZUWb9HHXGHM/default.jpg
  parent_uid: 3dd2be06225ef8ed708bab00b7fa8432
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: a2fbb01a84ca9e7d5d1deb9315f99dc0
- id: ZUWb9HHXGHM.srt
  parent_uid: 3dd2be06225ef8ed708bab00b7fa8432
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/procedures-10-04-/ZUWb9HHXGHM.srt
  title: 3play caption file
  type: null
  uid: 1728b2ae07a37744a40c7b5a039496e2
- id: ZUWb9HHXGHM.pdf
  parent_uid: 3dd2be06225ef8ed708bab00b7fa8432
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/procedures-10-04-/ZUWb9HHXGHM.pdf
  title: 3play pdf file
  type: null
  uid: 862b2401db5bc211559671702cd13d9c
- id: Caption-3Play YouTube id-SRT
  parent_uid: 3dd2be06225ef8ed708bab00b7fa8432
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 904bf427bb2d862edd7727f05d854cef
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 3dd2be06225ef8ed708bab00b7fa8432
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 4aaab7e5ab9484f33729896898f1bc78
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_12-02-01_300k.mp4
  parent_uid: 3dd2be06225ef8ed708bab00b7fa8432
  title: Video-Internet Archive-MP4
  type: Video
  uid: 842f95ce4520b6a8543aaafaed21bf06
inline_embed_id: 13428130procedures100497130432
layout: video
order_index: null
parent_uid: fc44a356c643ef09949b723bc06e5623
related_resources_text: ''
short_url: procedures-10-04-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/procedures-10-04-
template_type: Embed
title: Procedures (10:04)
transcript: <p><span m='229'>One</span> <span m='556'>of</span> <span m='883'>the</span>
  <span m='1211'>most</span> <span m='1538'>useful</span> <span m='1866'>abstractions</span>
  <span m='2193'>provided</span> <span m='2520'>by</span> <span m='2848'>high-level</span>
  <span m='3175'>languages</span> <span m='3503'>is</span> <span m='3830'>the</span>
  <span m='4157'>notion</span> <span m='4485'>of</span> <span m='4812'>a</span> <span
  m='5140'>procedure</span> <span m='5499'>or</span> <span m='5858'>subroutine,</span>
  <span m='6217'>which</span> <span m='6576'>is</span> <span m='6936'>a</span> <span
  m='7295'>sequence</span> <span m='7654'>of</span> <span m='8013'>instructions</span>
  <span m='8372'>that</span> <span m='8732'>perform</span> <span m='9091'>a</span>
  <span m='9450'>specific</span> <span m='9809'>task.</span> </p><p><span m='10169'>A</span>
  <span m='10465'>procedure</span> <span m='10762'>has</span> <span m='11058'>a</span>
  <span m='11355'>single</span> <span m='11651'>named</span> <span m='11948'>entry</span>
  <span m='12244'>point,</span> <span m='12541'>which</span> <span m='12837'>can</span>
  <span m='13134'>be</span> <span m='13430'>used</span> <span m='13727'>to</span>
  <span m='14023'>refer</span> <span m='14320'>to</span> <span m='14616'>the</span>
  <span m='14913'>procedure</span> <span m='15210'>in</span> <span m='15540'>other</span>
  <span m='15870'>parts</span> <span m='16200'>of</span> <span m='16530'>the</span>
  <span m='16860'>program.</span> </p><p><span m='17190'>In</span> <span m='17531'>the</span>
  <span m='17872'>example</span> <span m='18213'>here,</span> <span m='18555'>this</span>
  <span m='18896'>code</span> <span m='19237'>is</span> <span m='19578'>defining</span>
  <span m='19920'>the</span> <span m='20261'>GCD</span> <span m='20602'>procedure,</span>
  <span m='20943'>which</span> <span m='21285'>is</span> <span m='21626'>declared</span>
  <span m='21967'>to</span> <span m='22308'>return</span> <span m='22650'>an</span>
  <span m='23703'>integer</span> <span m='24756'>value.</span> </p><p><span m='25810'>Procedures</span>
  <span m='26114'>have</span> <span m='26419'>zero</span> <span m='26724'>or</span>
  <span m='27029'>more</span> <span m='27334'>formal</span> <span m='27639'>parameters,</span>
  <span m='27944'>which</span> <span m='28249'>are</span> <span m='28554'>the</span>
  <span m='28859'>names</span> <span m='29164'>the</span> <span m='29469'>code</span>
  <span m='29774'>inside</span> <span m='30079'>the</span> <span m='30384'>procedure</span>
  <span m='30689'>will</span> <span m='30944'>use</span> <span m='31199'>to</span>
  <span m='31454'>refer</span> <span m='31709'>the</span> <span m='31964'>values</span>
  <span m='32220'>supplied</span> <span m='32475'>when</span> <span m='32730'>the</span>
  <span m='32985'>procedure</span> <span m='33240'>is</span> <span m='33496'>invoked</span>
  <span m='33751'>by</span> <span m='34006'>a</span> <span m='34261'>"procedure</span>
  <span m='34516'>call".</span> </p><p><span m='34772'>A</span> <span m='35161'>procedure</span>
  <span m='35550'>call</span> <span m='35939'>is</span> <span m='36329'>an</span>
  <span m='36718'>expression</span> <span m='37107'>that</span> <span m='37496'>has</span>
  <span m='37886'>the</span> <span m='38275'>name</span> <span m='38664'>of</span>
  <span m='39053'>the</span> <span m='39443'>procedure</span> <span m='39832'>followed</span>
  <span m='40221'>by</span> <span m='40610'>parenthesized</span> <span m='41000'>list</span>
  <span m='41414'>of</span> <span m='41829'>values</span> <span m='42244'>called</span>
  <span m='42659'>"arguments"</span> <span m='43074'>that</span> <span m='43489'>will</span>
  <span m='43904'>be</span> <span m='44319'>matched</span> <span m='44734'>up</span>
  <span m='45149'>with</span> <span m='45564'>the</span> <span m='45979'>formal</span>
  <span m='46394'>parameters.</span> </p><p><span m='46809'>For</span> <span m='47070'>example,</span>
  <span m='47331'>the</span> <span m='47592'>value</span> <span m='47854'>of</span>
  <span m='48115'>the</span> <span m='48376'>first</span> <span m='48638'>argument</span>
  <span m='48899'>will</span> <span m='49160'>become</span> <span m='49422'>the</span>
  <span m='49683'>value</span> <span m='49944'>of</span> <span m='50206'>the</span>
  <span m='50467'>first</span> <span m='50728'>formal</span> <span m='50990'>parameter</span>
  <span m='51411'>while</span> <span m='51833'>the</span> <span m='52254'>procedure</span>
  <span m='52676'>is</span> <span m='53097'>executing.</span> </p><p><span m='53519'>The</span>
  <span m='53851'>body</span> <span m='54183'>of</span> <span m='54516'>the</span>
  <span m='54848'>procedure</span> <span m='55180'>may</span> <span m='55513'>define</span>
  <span m='55845'>additional</span> <span m='56178'>variables,</span> <span m='56510'>called</span>
  <span m='56842'>"local</span> <span m='57175'>variables",</span> <span m='57507'>since</span>
  <span m='57840'>they</span> <span m='58219'>can</span> <span m='58599'>only</span>
  <span m='58979'>be</span> <span m='59359'>accessed</span> <span m='59739'>by</span>
  <span m='60119'>statements</span> <span m='60499'>in</span> <span m='60879'>the</span>
  <span m='61259'>procedure</span> <span m='61639'>body.</span> </p><p><span m='62019'>Conceptually,</span>
  <span m='62462'>the</span> <span m='62906'>storage</span> <span m='63350'>for</span>
  <span m='63794'>local</span> <span m='64238'>variables</span> <span m='64682'>only</span>
  <span m='65126'>exists</span> <span m='65570'>while</span> <span m='66014'>the</span>
  <span m='66458'>procedure</span> <span m='66902'>is</span> <span m='67346'>executing.</span>
  </p><p><span m='67790'>They</span> <span m='68154'>are</span> <span m='68518'>allocated</span>
  <span m='68882'>when</span> <span m='69247'>the</span> <span m='69611'>procedure</span>
  <span m='69975'>is</span> <span m='70340'>invoked</span> <span m='70704'>and</span>
  <span m='71068'>deallocated</span> <span m='71432'>when</span> <span m='71797'>the</span>
  <span m='72161'>procedure</span> <span m='72525'>returns.</span> </p><p><span m='72890'>The</span>
  <span m='73263'>procedure</span> <span m='73637'>may</span> <span m='74011'>return</span>
  <span m='74385'>a</span> <span m='74759'>value</span> <span m='75133'>that's</span>
  <span m='75506'>the</span> <span m='75880'>result</span> <span m='76254'>of</span>
  <span m='76628'>the</span> <span m='77002'>procedure's</span> <span m='77376'>computation.</span>
  </p><p><span m='77750'>It's</span> <span m='78029'>legal</span> <span m='78308'>to</span>
  <span m='78588'>have</span> <span m='78867'>procedures</span> <span m='79146'>that</span>
  <span m='79426'>do</span> <span m='79705'>not</span> <span m='79985'>return</span>
  <span m='80264'>a</span> <span m='80543'>value,</span> <span m='80823'>in</span>
  <span m='81102'>which</span> <span m='81381'>case</span> <span m='81661'>the</span>
  <span m='81940'>procedures</span> <span m='82220'>would</span> <span m='82572'>only</span>
  <span m='82924'>be</span> <span m='83276'>executed</span> <span m='83628'>for</span>
  <span m='83980'>their</span> <span m='84332'>"side</span> <span m='84684'>effects",</span>
  <span m='85036'>e.g.,</span> <span m='85388'>changes</span> <span m='85740'>they</span>
  <span m='86092'>make</span> <span m='86444'>to</span> <span m='86796'>shared</span>
  <span m='87148'>data.</span> </p><p><span m='87500'>Here</span> <span m='87857'>we</span>
  <span m='88214'>see</span> <span m='88572'>another</span> <span m='88929'>procedure,</span>
  <span m='89286'>COPRIMES,</span> <span m='89644'>that</span> <span m='90001'>invokes</span>
  <span m='90358'>the</span> <span m='90716'>GCD</span> <span m='91073'>procedure</span>
  <span m='91430'>to</span> <span m='91788'>compute</span> <span m='92145'>the</span>
  <span m='92502'>greatest</span> <span m='92860'>common</span> <span m='93514'>divisor</span>
  <span m='94168'>of</span> <span m='94822'>two</span> <span m='95476'>numbers.</span>
  </p><p><span m='96130'>To</span> <span m='96592'>use</span> <span m='97054'>GCD,</span>
  <span m='97516'>the</span> <span m='97978'>programmer</span> <span m='98440'>of</span>
  <span m='98902'>COPRIMES</span> <span m='99364'>only</span> <span m='99826'>needed</span>
  <span m='100288'>to</span> <span m='100750'>know</span> <span m='101212'>the</span>
  <span m='101674'>input/output</span> <span m='102136'>behavior</span> <span m='102598'>of</span>
  <span m='103060'>GCD,</span> <span m='103334'>i.e.,</span> <span m='103609'>the</span>
  <span m='103884'>number</span> <span m='104158'>and</span> <span m='104433'>types</span>
  <span m='104708'>of</span> <span m='104983'>the</span> <span m='105257'>arguments</span>
  <span m='105532'>and</span> <span m='105807'>what</span> <span m='106082'>type</span>
  <span m='106356'>of</span> <span m='106631'>value</span> <span m='106906'>is</span>
  <span m='107181'>returned</span> <span m='107455'>as</span> <span m='107730'>a</span>
  <span m='108005'>result.</span> </p><p><span m='108280'>The</span> <span m='108643'>procedural</span>
  <span m='109006'>abstraction</span> <span m='109370'>has</span> <span m='109733'>hidden</span>
  <span m='110096'>the</span> <span m='110460'>implementation</span> <span m='110823'>of</span>
  <span m='111186'>GCD,</span> <span m='111550'>while</span> <span m='111913'>still</span>
  <span m='112276'>making</span> <span m='112640'>its</span> <span m='113204'>functionality</span>
  <span m='113768'>available</span> <span m='114332'>as</span> <span m='114897'>a</span>
  <span m='115461'>"black</span> <span m='116025'>box".</span> </p><p><span m='116590'>This</span>
  <span m='116948'>is</span> <span m='117306'>a</span> <span m='117664'>very</span>
  <span m='118022'>powerful</span> <span m='118380'>idea:</span> <span m='118738'>encapsulating</span>
  <span m='119096'>a</span> <span m='119455'>complex</span> <span m='119813'>computation</span>
  <span m='120171'>so</span> <span m='120529'>that</span> <span m='120887'>it</span>
  <span m='121245'>can</span> <span m='121603'>be</span> <span m='121961'>used</span>
  <span m='122320'>by</span> <span m='123215'>others.</span> </p><p><span m='124110'>Every</span>
  <span m='124551'>high-level</span> <span m='124993'>language</span> <span m='125435'>comes</span>
  <span m='125876'>with</span> <span m='126318'>a</span> <span m='126760'>collection</span>
  <span m='127201'>of</span> <span m='127643'>pre-built</span> <span m='128085'>procedures,</span>
  <span m='128526'>called</span> <span m='128968'>"libraries",</span> <span m='129410'>which</span>
  <span m='129787'>can</span> <span m='130165'>be</span> <span m='130542'>used</span>
  <span m='130920'>to</span> <span m='131298'>perform</span> <span m='131675'>arithmetic</span>
  <span m='132053'>functions</span> <span m='132430'>(e.g.,</span> <span m='132808'>square</span>
  <span m='133186'>root</span> <span m='133563'>or</span> <span m='133941'>cosine),</span>
  <span m='134319'>manipulate</span> <span m='134871'>collections</span> <span m='135423'>of</span>
  <span m='135976'>data</span> <span m='136528'>(e.g.,</span> <span m='137080'>lists</span>
  <span m='137633'>or</span> <span m='138185'>dictionaries),</span> <span m='138738'>read</span>
  <span m='139290'>data</span> <span m='139842'>from</span> <span m='140395'>files,</span>
  <span m='140947'>and</span> <span m='141500'>so</span> <span m='141886'>on</span>
  <span m='142272'>-</span> <span m='142658'>the</span> <span m='143045'>list</span>
  <span m='143431'>is</span> <span m='143817'>nearly</span> <span m='144203'>endless!</span>
  </p><p><span m='144590'>Much</span> <span m='144930'>of</span> <span m='145271'>the</span>
  <span m='145612'>expressive</span> <span m='145952'>power</span> <span m='146293'>and</span>
  <span m='146634'>ease-of-use</span> <span m='146974'>provided</span> <span m='147315'>by</span>
  <span m='147656'>high-level</span> <span m='147996'>languages</span> <span m='148337'>comes</span>
  <span m='148678'>from</span> <span m='149019'>their</span> <span m='149737'>libraries</span>
  <span m='150455'>of</span> <span m='151173'>"black</span> <span m='151891'>boxes".</span>
  </p><p><span m='152609'>The</span> <span m='153019'>procedural</span> <span m='153430'>abstraction</span>
  <span m='153841'>is</span> <span m='154252'>at</span> <span m='154663'>the</span>
  <span m='155074'>heart</span> <span m='155485'>of</span> <span m='155896'>object-oriented</span>
  <span m='156307'>languages,</span> <span m='156718'>which</span> <span m='157129'>encapsulate</span>
  <span m='157540'>data</span> <span m='157959'>and</span> <span m='158379'>procedures</span>
  <span m='158799'>as</span> <span m='159219'>black</span> <span m='159639'>boxes</span>
  <span m='160059'>called</span> <span m='160479'>objects</span> <span m='160899'>that</span>
  <span m='161319'>support</span> <span m='161739'>specific</span> <span m='162159'>operations</span>
  <span m='162579'>on</span> <span m='162999'>their</span> <span m='163639'>internal</span>
  <span m='164279'>data.</span> </p><p><span m='164920'>For</span> <span m='165347'>example,</span>
  <span m='165775'>a</span> <span m='166203'>LIST</span> <span m='166631'>object</span>
  <span m='167058'>has</span> <span m='167486'>procedures</span> <span m='167914'>(called</span>
  <span m='168342'>"methods"</span> <span m='168770'>in</span> <span m='169197'>this</span>
  <span m='169625'>context)</span> <span m='170053'>for</span> <span m='170481'>indexing</span>
  <span m='170909'>into</span> <span m='171228'>the</span> <span m='171547'>list</span>
  <span m='171867'>to</span> <span m='172186'>read</span> <span m='172506'>or</span>
  <span m='172825'>change</span> <span m='173145'>a</span> <span m='173464'>value,</span>
  <span m='173784'>adding</span> <span m='174103'>new</span> <span m='174423'>elements</span>
  <span m='174742'>to</span> <span m='175062'>the</span> <span m='175381'>list,</span>
  <span m='175701'>inquiring</span> <span m='176020'>about</span> <span m='176340'>the</span>
  <span m='176661'>length</span> <span m='176982'>of</span> <span m='177303'>the</span>
  <span m='177624'>list,</span> <span m='177945'>and</span> <span m='178266'>so</span>
  <span m='178587'>on.</span> </p><p><span m='178909'>The</span> <span m='179241'>internal</span>
  <span m='179574'>representation</span> <span m='179907'>of</span> <span m='180240'>the</span>
  <span m='180573'>data</span> <span m='180906'>and</span> <span m='181239'>the</span>
  <span m='181571'>algorithms</span> <span m='181904'>used</span> <span m='182237'>to</span>
  <span m='182570'>implement</span> <span m='182903'>the</span> <span m='183236'>methods</span>
  <span m='183569'>are</span> <span m='184057'>hidden</span> <span m='184546'>by</span>
  <span m='185034'>the</span> <span m='185523'>object</span> <span m='186011'>abstraction.</span>
  </p><p><span m='186500'>Indeed,</span> <span m='186843'>there</span> <span m='187186'>may</span>
  <span m='187529'>be</span> <span m='187872'>several</span> <span m='188215'>different</span>
  <span m='188558'>LIST</span> <span m='188901'>implementations</span> <span m='189244'>to</span>
  <span m='189587'>choose</span> <span m='189930'>from</span> <span m='190273'>depending</span>
  <span m='190616'>on</span> <span m='190959'>which</span> <span m='191382'>operations</span>
  <span m='191806'>you</span> <span m='192230'>need</span> <span m='192654'>to</span>
  <span m='193077'>be</span> <span m='193501'>particularly</span> <span m='193925'>efficient.</span>
  </p><p><span m='194349'>Okay,</span> <span m='194855'>enough</span> <span m='195362'>about</span>
  <span m='195869'>the</span> <span m='196375'>virtues</span> <span m='196882'>of</span>
  <span m='197389'>the</span> <span m='197895'>procedural</span> <span m='198402'>abstraction!</span>
  </p><p><span m='198909'>Let's</span> <span m='199297'>turn</span> <span m='199685'>our</span>
  <span m='200074'>attention</span> <span m='200462'>to</span> <span m='200851'>how</span>
  <span m='201239'>to</span> <span m='201628'>implement</span> <span m='202016'>procedures</span>
  <span m='202405'>using</span> <span m='202793'>the</span> <span m='203182'>Beta</span>
  <span m='203570'>ISA.</span> </p><p><span m='203959'>A</span> <span m='204350'>possible</span>
  <span m='204742'>implementation</span> <span m='205133'>is</span> <span m='205525'>to</span>
  <span m='205916'>"inline"</span> <span m='206308'>the</span> <span m='206699'>procedure,</span>
  <span m='207091'>where</span> <span m='207482'>we</span> <span m='207874'>replace</span>
  <span m='208265'>the</span> <span m='208657'>procedure</span> <span m='209049'>call</span>
  <span m='209406'>with</span> <span m='209763'>a</span> <span m='210120'>copy</span>
  <span m='210477'>of</span> <span m='210834'>the</span> <span m='211191'>statements</span>
  <span m='211549'>in</span> <span m='211906'>the</span> <span m='212263'>procedure's</span>
  <span m='212620'>body,</span> <span m='212977'>substituting</span> <span m='213334'>argument</span>
  <span m='213691'>values</span> <span m='214049'>for</span> <span m='214510'>references</span>
  <span m='214972'>to</span> <span m='215434'>the</span> <span m='215895'>formal</span>
  <span m='216357'>parameters.</span> </p><p><span m='216819'>In</span> <span m='217216'>this</span>
  <span m='217613'>approach</span> <span m='218010'>we're</span> <span m='218407'>treating</span>
  <span m='218804'>procedures</span> <span m='219201'>very</span> <span m='219599'>much</span>
  <span m='219996'>like</span> <span m='220393'>UASM</span> <span m='220790'>macros,</span>
  <span m='221187'>i.e.,</span> <span m='221584'>a</span> <span m='221981'>simple</span>
  <span m='222379'>notational</span> <span m='222799'>shorthand</span> <span m='223219'>for</span>
  <span m='223639'>making</span> <span m='224059'>a</span> <span m='224479'>copy</span>
  <span m='224899'>of</span> <span m='225319'>the</span> <span m='225739'>procedure's</span>
  <span m='226159'>body.</span> </p><p><span m='226579'>Are</span> <span m='227047'>there</span>
  <span m='227516'>any</span> <span m='227985'>problems</span> <span m='228453'>with</span>
  <span m='228922'>this</span> <span m='229391'>approach?</span> </p><p><span m='229860'>One</span>
  <span m='230219'>obvious</span> <span m='230579'>issue</span> <span m='230939'>is</span>
  <span m='231299'>the</span> <span m='231659'>potential</span> <span m='232019'>increase</span>
  <span m='232379'>in</span> <span m='232739'>the</span> <span m='233099'>code</span>
  <span m='233459'>size.</span> </p><p><span m='233819'>For</span> <span m='234164'>example,</span>
  <span m='234510'>if</span> <span m='234855'>we</span> <span m='235201'>had</span>
  <span m='235547'>a</span> <span m='235892'>lengthy</span> <span m='236238'>procedure</span>
  <span m='236584'>that</span> <span m='236929'>was</span> <span m='237275'>called</span>
  <span m='237620'>many</span> <span m='237966'>times,</span> <span m='238312'>the</span>
  <span m='238657'>final</span> <span m='239003'>expanded</span> <span m='239349'>code</span>
  <span m='239914'>would</span> <span m='240479'>be</span> <span m='241044'>huge!</span>
  </p><p><span m='241609'>Enough</span> <span m='241953'>so</span> <span m='242297'>that</span>
  <span m='242641'>inlining</span> <span m='242985'>isn't</span> <span m='243329'>a</span>
  <span m='243673'>practical</span> <span m='244017'>solution</span> <span m='244361'>except</span>
  <span m='244705'>in</span> <span m='245049'>the</span> <span m='245393'>case</span>
  <span m='245737'>of</span> <span m='246081'>short</span> <span m='246425'>procedures</span>
  <span m='246769'>where</span> <span m='247246'>optimizing</span> <span m='247723'>compilers</span>
  <span m='248200'>do</span> <span m='248677'>sometimes</span> <span m='249154'>decide</span>
  <span m='249631'>to</span> <span m='250108'>inline</span> <span m='250585'>the</span>
  <span m='251062'>code.</span> </p><p><span m='251540'>A</span> <span m='251976'>bigger</span>
  <span m='252413'>difficulty</span> <span m='252849'>is</span> <span m='253286'>apparent</span>
  <span m='253723'>when</span> <span m='254159'>we</span> <span m='254596'>consider</span>
  <span m='255032'>a</span> <span m='255469'>recursive</span> <span m='255906'>procedure</span>
  <span m='256342'>where</span> <span m='256779'>there's</span> <span m='257215'>a</span>
  <span m='257652'>nested</span> <span m='258089'>call</span> <span m='258609'>to</span>
  <span m='259129'>the</span> <span m='259649'>procedure</span> <span m='260169'>itself.</span>
  </p><p><span m='260690'>During</span> <span m='261012'>execution</span> <span m='261335'>the</span>
  <span m='261658'>recursion</span> <span m='261980'>will</span> <span m='262303'>terminate</span>
  <span m='262626'>for</span> <span m='262948'>some</span> <span m='263271'>values</span>
  <span m='263594'>of</span> <span m='263916'>the</span> <span m='264239'>arguments</span>
  <span m='264562'>and</span> <span m='264884'>the</span> <span m='265207'>recursive</span>
  <span m='265530'>procedure</span> <span m='266058'>will</span> <span m='266586'>eventually</span>
  <span m='267114'>return</span> <span m='267642'>answer.</span> </p><p><span m='268170'>But</span>
  <span m='268603'>at</span> <span m='269036'>compile</span> <span m='269470'>time,</span>
  <span m='269903'>the</span> <span m='270336'>inlining</span> <span m='270770'>process</span>
  <span m='271203'>would</span> <span m='271636'>not</span> <span m='272070'>terminate</span>
  <span m='272503'>and</span> <span m='272936'>so</span> <span m='273370'>the</span>
  <span m='273803'>inlining</span> <span m='274236'>scheme</span> <span m='274670'>fails</span>
  <span m='275310'>if</span> <span m='275950'>the</span> <span m='276590'>language</span>
  <span m='277230'>allows</span> <span m='277870'>recursion.</span> </p><p><span m='278510'>The</span>
  <span m='278828'>second</span> <span m='279147'>option</span> <span m='279466'>is</span>
  <span m='279785'>to</span> <span m='280104'>"link"</span> <span m='280423'>to</span>
  <span m='280742'>the</span> <span m='281061'>procedure.</span> </p><p><span m='281380'>In</span>
  <span m='281606'>this</span> <span m='281832'>approach</span> <span m='282059'>there</span>
  <span m='282285'>is</span> <span m='282512'>a</span> <span m='282738'>single</span>
  <span m='282965'>copy</span> <span m='283191'>of</span> <span m='283418'>the</span>
  <span m='283644'>procedure</span> <span m='283871'>code</span> <span m='284097'>which</span>
  <span m='284324'>we</span> <span m='284550'>arrange</span> <span m='284777'>to</span>
  <span m='285003'>be</span> <span m='285230'>run</span> <span m='285635'>for</span>
  <span m='286041'>each</span> <span m='286446'>procedure</span> <span m='286852'>call</span>
  <span m='287257'>-</span> <span m='287663'>all</span> <span m='288068'>the</span>
  <span m='288474'>procedure</span> <span m='288880'>calls</span> <span m='289285'>are</span>
  <span m='289691'>said</span> <span m='290096'>to</span> <span m='290502'>link</span>
  <span m='290907'>to</span> <span m='291313'>the</span> <span m='291718'>procedure</span>
  <span m='292124'>code.</span> </p><p><span m='292530'>Here</span> <span m='292822'>the</span>
  <span m='293115'>body</span> <span m='293408'>of</span> <span m='293700'>the</span>
  <span m='293993'>procedure</span> <span m='294286'>is</span> <span m='294578'>translated</span>
  <span m='294871'>once</span> <span m='295164'>into</span> <span m='295456'>Beta</span>
  <span m='295749'>instructions</span> <span m='296042'>and</span> <span m='296334'>the</span>
  <span m='296627'>first</span> <span m='296920'>instruction</span> <span m='297356'>is</span>
  <span m='297792'>identified</span> <span m='298228'>as</span> <span m='298665'>the</span>
  <span m='299101'>procedure's</span> <span m='299537'>entry</span> <span m='299973'>point.</span>
  </p><p><span m='300410'>The</span> <span m='300680'>procedure</span> <span m='300950'>call</span>
  <span m='301220'>is</span> <span m='301490'>compiled</span> <span m='301760'>into</span>
  <span m='302030'>a</span> <span m='302300'>set</span> <span m='302570'>of</span>
  <span m='302840'>instructions</span> <span m='303110'>that</span> <span m='303380'>evaluate</span>
  <span m='303650'>the</span> <span m='303920'>argument</span> <span m='304190'>expressions</span>
  <span m='304693'>and</span> <span m='305196'>save</span> <span m='305700'>the</span>
  <span m='306203'>values</span> <span m='306706'>in</span> <span m='307210'>an</span>
  <span m='307713'>agreed-upon</span> <span m='308216'>location.</span> </p><p><span
  m='308720'>Then</span> <span m='309063'>we'll</span> <span m='309407'>use</span>
  <span m='309751'>a</span> <span m='310095'>BR</span> <span m='310438'>instruction</span>
  <span m='310782'>to</span> <span m='311126'>transfer</span> <span m='311470'>control</span>
  <span m='311813'>to</span> <span m='312157'>the</span> <span m='312501'>entry</span>
  <span m='312845'>point</span> <span m='313188'>of</span> <span m='313532'>the</span>
  <span m='313876'>procedure.</span> </p><p><span m='314220'>Recall</span> <span m='314569'>that</span>
  <span m='314918'>the</span> <span m='315268'>BR</span> <span m='315617'>instruction</span>
  <span m='315967'>not</span> <span m='316316'>only</span> <span m='316665'>changes</span>
  <span m='317015'>the</span> <span m='317364'>PC</span> <span m='317714'>but</span>
  <span m='318063'>saves</span> <span m='318412'>the</span> <span m='318762'>address</span>
  <span m='319111'>of</span> <span m='319461'>the</span> <span m='319810'>instruction</span>
  <span m='320160'>following</span> <span m='320664'>the</span> <span m='321168'>branch</span>
  <span m='321672'>in</span> <span m='322177'>a</span> <span m='322681'>specified</span>
  <span m='323185'>register.</span> </p><p><span m='323690'>This</span> <span m='324028'>saved</span>
  <span m='324366'>address</span> <span m='324704'>is</span> <span m='325042'>the</span>
  <span m='325380'>"return</span> <span m='325718'>address"</span> <span m='326056'>where</span>
  <span m='326394'>we</span> <span m='326732'>want</span> <span m='327070'>execution</span>
  <span m='327408'>to</span> <span m='327746'>resume</span> <span m='328084'>when</span>
  <span m='328422'>procedure</span> <span m='328760'>execution</span> <span m='329733'>is</span>
  <span m='330706'>complete.</span> </p><p><span m='331680'>After</span> <span m='331980'>branching</span>
  <span m='332281'>to</span> <span m='332581'>the</span> <span m='332882'>entry</span>
  <span m='333183'>point,</span> <span m='333483'>the</span> <span m='333784'>procedure</span>
  <span m='334085'>code</span> <span m='334385'>runs,</span> <span m='334686'>stores</span>
  <span m='334986'>the</span> <span m='335287'>result</span> <span m='335588'>in</span>
  <span m='335888'>an</span> <span m='336189'>agreed-upon</span> <span m='336490'>location</span>
  <span m='336840'>and</span> <span m='337190'>then</span> <span m='337540'>resumes</span>
  <span m='337890'>execution</span> <span m='338240'>of</span> <span m='338590'>the</span>
  <span m='338940'>calling</span> <span m='339290'>program</span> <span m='339640'>by</span>
  <span m='339990'>jumping</span> <span m='340340'>to</span> <span m='340690'>the</span>
  <span m='341040'>supplied</span> <span m='341390'>return</span> <span m='342695'>address.</span>
  </p><p><span m='344000'>To</span> <span m='344371'>complete</span> <span m='344743'>this</span>
  <span m='345114'>implementation</span> <span m='345486'>plan</span> <span m='345857'>we</span>
  <span m='346229'>need</span> <span m='346600'>a</span> <span m='346972'>"calling</span>
  <span m='347343'>convention"</span> <span m='347715'>that</span> <span m='348086'>specifies</span>
  <span m='348458'>where</span> <span m='348830'>to</span> <span m='349120'>store</span>
  <span m='349411'>the</span> <span m='349702'>argument</span> <span m='349992'>values</span>
  <span m='350283'>during</span> <span m='350574'>procedure</span> <span m='350865'>calls</span>
  <span m='351155'>and</span> <span m='351446'>where</span> <span m='351737'>the</span>
  <span m='352027'>procedure</span> <span m='352318'>should</span> <span m='352609'>store</span>
  <span m='352900'>the</span> <span m='353366'>return</span> <span m='353833'>value.</span>
  </p><p><span m='354300'>It's</span> <span m='354747'>tempting</span> <span m='355194'>to</span>
  <span m='355641'>simply</span> <span m='356089'>allocate</span> <span m='356536'>specific</span>
  <span m='356983'>memory</span> <span m='357430'>locations</span> <span m='357878'>for</span>
  <span m='358325'>the</span> <span m='358772'>job.</span> </p><p><span m='359220'>How</span>
  <span m='359755'>about</span> <span m='360290'>using</span> <span m='360825'>registers?</span>
  </p><p><span m='361360'>We</span> <span m='361764'>could</span> <span m='362168'>pass</span>
  <span m='362572'>the</span> <span m='362976'>argument</span> <span m='363380'>value</span>
  <span m='363785'>in</span> <span m='364189'>registers</span> <span m='364593'>starting,</span>
  <span m='364997'>say,</span> <span m='365401'>with</span> <span m='365805'>R1.</span>
  </p><p><span m='366210'>The</span> <span m='366596'>return</span> <span m='366982'>address</span>
  <span m='367369'>could</span> <span m='367755'>be</span> <span m='368141'>stored</span>
  <span m='368528'>in</span> <span m='368914'>another</span> <span m='369300'>register,</span>
  <span m='369687'>say</span> <span m='370073'>R28.</span> </p><p><span m='370460'>As</span>
  <span m='370721'>we</span> <span m='370982'>can</span> <span m='371243'>see,</span>
  <span m='371504'>with</span> <span m='371765'>this</span> <span m='372027'>convention</span>
  <span m='372288'>the</span> <span m='372549'>BR</span> <span m='372810'>and</span>
  <span m='373071'>JMP</span> <span m='373332'>instructions</span> <span m='373594'>are</span>
  <span m='373855'>just</span> <span m='374116'>what</span> <span m='374377'>we</span>
  <span m='374638'>need</span> <span m='374900'>to</span> <span m='375331'>implement</span>
  <span m='375763'>procedure</span> <span m='376195'>call</span> <span m='376626'>and</span>
  <span m='377058'>return.</span> </p><p><span m='377490'>It's</span> <span m='377841'>usual</span>
  <span m='378193'>to</span> <span m='378544'>call</span> <span m='378896'>the</span>
  <span m='379247'>register</span> <span m='379599'>holding</span> <span m='379950'>the</span>
  <span m='380302'>return</span> <span m='380653'>address</span> <span m='381005'>the</span>
  <span m='381356'>"linkage</span> <span m='381708'>pointer".</span> </p><p><span
  m='382060'>And</span> <span m='382453'>finally</span> <span m='382847'>the</span>
  <span m='383241'>procedure</span> <span m='383635'>can</span> <span m='384029'>use,</span>
  <span m='384423'>say,</span> <span m='384816'>R0</span> <span m='385210'>to</span>
  <span m='385604'>hold</span> <span m='385998'>the</span> <span m='386392'>return</span>
  <span m='386786'>value.</span> </p><p><span m='387180'>Let's</span> <span m='387460'>see</span>
  <span m='387741'>how</span> <span m='388022'>this</span> <span m='388303'>would</span>
  <span m='388584'>work</span> <span m='388865'>when</span> <span m='389145'>executing</span>
  <span m='389426'>the</span> <span m='389707'>procedure</span> <span m='389988'>call</span>
  <span m='390269'>fact(3).</span> </p><p><span m='390550'>As</span> <span m='390967'>shown</span>
  <span m='391384'>on</span> <span m='391802'>the</span> <span m='392219'>right,</span>
  <span m='392636'>fact(3)</span> <span m='393054'>requires</span> <span m='393471'>a</span>
  <span m='393888'>recursive</span> <span m='394306'>call</span> <span m='394723'>to</span>
  <span m='395140'>compute</span> <span m='395558'>fact(2),</span> <span m='395975'>and</span>
  <span m='396392'>so</span> <span m='396810'>on.</span> </p><p><span m='397810'>Our</span>
  <span m='398161'>goal</span> <span m='398513'>is</span> <span m='398865'>to</span>
  <span m='399217'>have</span> <span m='399569'>a</span> <span m='399921'>uniform</span>
  <span m='400273'>calling</span> <span m='400625'>convention</span> <span m='400976'>where</span>
  <span m='401328'>all</span> <span m='401680'>procedure</span> <span m='402032'>calls</span>
  <span m='402384'>and</span> <span m='402736'>procedure</span> <span m='403088'>bodies</span>
  <span m='403440'>use</span> <span m='403828'>the</span> <span m='404216'>same</span>
  <span m='404605'>convention</span> <span m='404993'>for</span> <span m='405381'>storing</span>
  <span m='405770'>arguments,</span> <span m='406158'>return</span> <span m='406546'>addresses</span>
  <span m='406935'>and</span> <span m='407323'>return</span> <span m='407711'>values.</span>
  </p><p><span m='408100'>In</span> <span m='408610'>particular,</span> <span m='409121'>we'll</span>
  <span m='409632'>use</span> <span m='410143'>the</span> <span m='410653'>same</span>
  <span m='411164'>convention</span> <span m='411675'>when</span> <span m='412186'>compiling</span>
  <span m='412696'>the</span> <span m='413207'>recursive</span> <span m='413718'>call</span>
  <span m='414229'>fact(n-1)</span> <span m='414740'>as</span> <span m='415077'>we</span>
  <span m='415415'>did</span> <span m='415753'>for</span> <span m='416091'>the</span>
  <span m='416428'>initial</span> <span m='416766'>call</span> <span m='417104'>to</span>
  <span m='417442'>fact(3).</span> </p><p><span m='417780'>Okay.</span> </p><p><span
  m='419220'>In</span> <span m='419488'>the</span> <span m='419756'>code</span> <span
  m='420024'>shown</span> <span m='420292'>on</span> <span m='420560'>the</span> <span
  m='420828'>right</span> <span m='421096'>we've</span> <span m='421364'>used</span>
  <span m='421632'>our</span> <span m='421900'>proposed</span> <span m='422168'>convention</span>
  <span m='422436'>when</span> <span m='422704'>compiling</span> <span m='422972'>the</span>
  <span m='423240'>Beta</span> <span m='423732'>code</span> <span m='424225'>for</span>
  <span m='424717'>fact().</span> </p><p><span m='425210'>Let's</span> <span m='425684'>take</span>
  <span m='426158'>a</span> <span m='426632'>quick</span> <span m='427106'>tour.</span>
  </p><p><span m='427580'>To</span> <span m='427944'>compile</span> <span m='428308'>the</span>
  <span m='428673'>initial</span> <span m='429037'>call</span> <span m='429401'>fact(3)</span>
  <span m='429766'>the</span> <span m='430130'>compiler</span> <span m='430495'>generated</span>
  <span m='430859'>a</span> <span m='431223'>CMOVE</span> <span m='431588'>instruction</span>
  <span m='431952'>to</span> <span m='432316'>put</span> <span m='432681'>the</span>
  <span m='433045'>argument</span> <span m='433410'>value</span> <span m='433766'>in</span>
  <span m='434122'>R1</span> <span m='434479'>and</span> <span m='434835'>then</span>
  <span m='435192'>a</span> <span m='435548'>BR</span> <span m='435905'>instruction</span>
  <span m='436261'>to</span> <span m='436618'>transfer</span> <span m='436974'>control</span>
  <span m='437331'>to</span> <span m='437687'>fact's</span> <span m='438044'>entry</span>
  <span m='438400'>point</span> <span m='438757'>while</span> <span m='439113'>remembering</span>
  <span m='439470'>the</span> <span m='440154'>return</span> <span m='440838'>address</span>
  <span m='441522'>in</span> <span m='442206'>R28.</span> </p><p><span m='442890'>The</span>
  <span m='443276'>first</span> <span m='443663'>statement</span> <span m='444049'>in</span>
  <span m='444436'>the</span> <span m='444822'>body</span> <span m='445209'>of</span>
  <span m='445595'>fact</span> <span m='445982'>tests</span> <span m='446368'>the</span>
  <span m='446755'>value</span> <span m='447141'>of</span> <span m='447528'>the</span>
  <span m='447914'>argument</span> <span m='448301'>using</span> <span m='448687'>CMPLEC</span>
  <span m='449074'>and</span> <span m='449461'>BT</span> <span m='450875'>instructions.</span>
  </p><p><span m='452290'>When</span> <span m='452599'>n</span> <span m='452908'>is</span>
  <span m='453218'>greater</span> <span m='453527'>than</span> <span m='453837'>0,</span>
  <span m='454146'>the</span> <span m='454455'>code</span> <span m='454765'>performs</span>
  <span m='455074'>a</span> <span m='455384'>recursive</span> <span m='455693'>call</span>
  <span m='456002'>to</span> <span m='456312'>fact,</span> <span m='456621'>saving</span>
  <span m='456931'>the</span> <span m='457240'>value</span> <span m='457550'>of</span>
  <span m='458132'>the</span> <span m='458715'>recursive</span> <span m='459298'>argument</span>
  <span m='459880'>n-1</span> <span m='460463'>in</span> <span m='461046'>R1</span>
  <span m='461629'>as</span> <span m='462211'>our</span> <span m='462794'>convention</span>
  <span m='463377'>requires.</span> </p><p><span m='463960'>Note</span> <span m='464178'>that</span>
  <span m='464397'>we</span> <span m='464616'>had</span> <span m='464835'>to</span>
  <span m='465054'>first</span> <span m='465272'>save</span> <span m='465491'>the</span>
  <span m='465710'>value</span> <span m='465929'>of</span> <span m='466148'>the</span>
  <span m='466367'>original</span> <span m='466585'>argument</span> <span m='466804'>n</span>
  <span m='467023'>because</span> <span m='467242'>we'll</span> <span m='467461'>need</span>
  <span m='467680'>it</span> <span m='468183'>for</span> <span m='468686'>the</span>
  <span m='469189'>multiplication</span> <span m='469692'>after</span> <span m='470195'>the</span>
  <span m='470698'>recursive</span> <span m='471201'>call</span> <span m='471704'>returns</span>
  <span m='472207'>its</span> <span m='472710'>value</span> <span m='473213'>in</span>
  <span m='473716'>R0.</span> </p><p><span m='474220'>If</span> <span m='474612'>n</span>
  <span m='475005'>is</span> <span m='475398'>not</span> <span m='475791'>greater</span>
  <span m='476184'>than</span> <span m='476577'>0,</span> <span m='476970'>the</span>
  <span m='477362'>value</span> <span m='477755'>1</span> <span m='478148'>is</span>
  <span m='478541'>placed</span> <span m='478934'>in</span> <span m='479327'>R0.</span>
  </p><p><span m='479720'>Then</span> <span m='480128'>the</span> <span m='480536'>two</span>
  <span m='480945'>possible</span> <span m='481353'>execution</span> <span m='481762'>paths</span>
  <span m='482170'>merge,</span> <span m='482579'>each</span> <span m='482987'>having</span>
  <span m='483396'>generated</span> <span m='483804'>the</span> <span m='484213'>appropriate</span>
  <span m='484621'>return</span> <span m='485030'>value</span> <span m='485440'>in</span>
  <span m='485850'>R0,</span> <span m='486260'>and</span> <span m='486670'>finally</span>
  <span m='487080'>there's</span> <span m='487490'>a</span> <span m='487900'>JMP</span>
  <span m='488310'>to</span> <span m='488720'>return</span> <span m='489130'>control</span>
  <span m='489540'>to</span> <span m='489950'>the</span> <span m='490360'>caller.</span>
  </p><p><span m='490770'>The</span> <span m='491060'>JMP</span> <span m='491350'>instruction</span>
  <span m='491640'>knows</span> <span m='491930'>to</span> <span m='492220'>find</span>
  <span m='492510'>the</span> <span m='492800'>return</span> <span m='493090'>address</span>
  <span m='493380'>in</span> <span m='493670'>R28,</span> <span m='493960'>just</span>
  <span m='494250'>where</span> <span m='494540'>the</span> <span m='494830'>BR</span>
  <span m='495120'>put</span> <span m='495410'>it</span> <span m='495700'>as</span>
  <span m='495990'>part</span> <span m='496735'>of</span> <span m='497480'>the</span>
  <span m='498225'>original</span> <span m='498970'>procedure</span> <span m='499715'>call.</span>
  </p><p><span m='500460'>Some</span> <span m='500818'>of</span> <span m='501176'>you</span>
  <span m='501534'>may</span> <span m='501892'>have</span> <span m='502250'>noticed</span>
  <span m='502608'>that</span> <span m='502966'>there</span> <span m='503324'>are</span>
  <span m='503682'>some</span> <span m='504040'>difficulties</span> <span m='504398'>with</span>
  <span m='504756'>this</span> <span m='505114'>particular</span> <span m='505472'>implementation.</span>
  </p><p><span m='505830'>The</span> <span m='506116'>code</span> <span m='506403'>is</span>
  <span m='506690'>correct</span> <span m='506977'>in</span> <span m='507264'>the</span>
  <span m='507551'>sense</span> <span m='507838'>that</span> <span m='508125'>it</span>
  <span m='508411'>faithfully</span> <span m='508698'>implements</span> <span m='508985'>procedure</span>
  <span m='509272'>call</span> <span m='509559'>and</span> <span m='509846'>return</span>
  <span m='510133'>using</span> <span m='510420'>our</span> <span m='511269'>proposed</span>
  <span m='512119'>convention.</span> </p><p><span m='512969'>The</span> <span m='513318'>problem</span>
  <span m='513667'>is</span> <span m='514017'>that</span> <span m='514366'>during</span>
  <span m='514715'>recursive</span> <span m='515065'>calls</span> <span m='515414'>we'll</span>
  <span m='515763'>be</span> <span m='516113'>overwriting</span> <span m='516462'>register</span>
  <span m='516811'>values</span> <span m='517161'>we</span> <span m='517510'>need</span>
  <span m='517860'>later.</span> </p><p><span m='519860'>For</span> <span m='520315'>example,</span>
  <span m='520770'>note</span> <span m='521225'>that</span> <span m='521680'>following</span>
  <span m='522135'>our</span> <span m='522590'>calling</span> <span m='523045'>convention,</span>
  <span m='523500'>the</span> <span m='523955'>recursive</span> <span m='524410'>call</span>
  <span m='524865'>also</span> <span m='525320'>uses</span> <span m='525775'>R28</span>
  <span m='526230'>to</span> <span m='526575'>store</span> <span m='526921'>the</span>
  <span m='527267'>return</span> <span m='527613'>address.</span> </p><p><span m='527959'>When</span>
  <span m='528273'>executed,</span> <span m='528587'>the</span> <span m='528901'>code</span>
  <span m='529215'>for</span> <span m='529529'>the</span> <span m='529843'>original</span>
  <span m='530157'>call</span> <span m='530471'>stored</span> <span m='530785'>the</span>
  <span m='531099'>address</span> <span m='531413'>of</span> <span m='531727'>the</span>
  <span m='532041'>HALT</span> <span m='532355'>instruction</span> <span m='532670'>in</span>
  <span m='533700'>R28.</span> </p><p><span m='534730'>Inside</span> <span m='535063'>the</span>
  <span m='535396'>procedure,</span> <span m='535730'>the</span> <span m='536063'>recursive</span>
  <span m='536396'>call</span> <span m='536730'>will</span> <span m='537063'>store</span>
  <span m='537396'>the</span> <span m='537730'>address</span> <span m='538063'>of</span>
  <span m='538396'>the</span> <span m='538730'>MUL</span> <span m='539063'>instruction</span>
  <span m='539396'>in</span> <span m='539730'>R28.</span> </p><p><span m='541060'>Unfortunately</span>
  <span m='541638'>that</span> <span m='542217'>overwrites</span> <span m='542795'>the</span>
  <span m='543374'>original</span> <span m='543952'>return</span> <span m='544531'>address.</span>
  </p><p><span m='545110'>Even</span> <span m='545399'>the</span> <span m='545688'>attempt</span>
  <span m='545978'>to</span> <span m='546267'>save</span> <span m='546557'>the</span>
  <span m='546846'>value</span> <span m='547136'>of</span> <span m='547425'>the</span>
  <span m='547715'>argument</span> <span m='548004'>N</span> <span m='548294'>in</span>
  <span m='548583'>R2</span> <span m='548873'>is</span> <span m='549162'>doomed</span>
  <span m='549452'>to</span> <span m='549741'>fail</span> <span m='550031'>since</span>
  <span m='550320'>during</span> <span m='550610'>the</span> <span m='551140'>execution</span>
  <span m='551670'>of</span> <span m='552200'>the</span> <span m='552730'>recursive</span>
  <span m='553260'>call</span> <span m='553790'>R2</span> <span m='554320'>will</span>
  <span m='554850'>be</span> <span m='555380'>overwritten.</span> </p><p><span m='555910'>The</span>
  <span m='556186'>crux</span> <span m='556462'>of</span> <span m='556738'>the</span>
  <span m='557014'>problem</span> <span m='557290'>is</span> <span m='557566'>that</span>
  <span m='557842'>each</span> <span m='558118'>recursive</span> <span m='558394'>call</span>
  <span m='558670'>needs</span> <span m='558946'>to</span> <span m='559222'>remember</span>
  <span m='559498'>the</span> <span m='559774'>value</span> <span m='560050'>of</span>
  <span m='560326'>its</span> <span m='560602'>argument</span> <span m='560879'>and</span>
  <span m='561341'>return</span> <span m='561803'>address,</span> <span m='562265'>i.e.,</span>
  <span m='562727'>we</span> <span m='563189'>need</span> <span m='563651'>two</span>
  <span m='564113'>storage</span> <span m='564575'>locations</span> <span m='565037'>for</span>
  <span m='565499'>each</span> <span m='565961'>active</span> <span m='566423'>call</span>
  <span m='566885'>to</span> <span m='567347'>fact().</span> </p><p><span m='567810'>And</span>
  <span m='568218'>while</span> <span m='568627'>executing</span> <span m='569035'>fact(3),</span>
  <span m='569444'>when</span> <span m='569853'>we</span> <span m='570261'>finally</span>
  <span m='570670'>get</span> <span m='571078'>to</span> <span m='571487'>calling</span>
  <span m='571896'>fact(0)</span> <span m='572304'>there</span> <span m='572713'>are</span>
  <span m='573121'>four</span> <span m='573530'>nested</span> <span m='573939'>active</span>
  <span m='574410'>calls,</span> <span m='574881'>so</span> <span m='575352'>we'll</span>
  <span m='575823'>need</span> <span m='576294'>4*2</span> <span m='576765'>=</span>
  <span m='577236'>8</span> <span m='577707'>storage</span> <span m='578178'>locations.</span>
  </p><p><span m='578649'>In</span> <span m='579092'>fact,</span> <span m='579536'>the</span>
  <span m='579979'>amount</span> <span m='580423'>of</span> <span m='580867'>storage</span>
  <span m='581310'>needed</span> <span m='581754'>varies</span> <span m='582198'>with</span>
  <span m='582641'>the</span> <span m='583085'>depth</span> <span m='583529'>of</span>
  <span m='583972'>the</span> <span m='584416'>recursion.</span> </p><p><span m='584860'>Obviously</span>
  <span m='585155'>we</span> <span m='585451'>can't</span> <span m='585747'>use</span>
  <span m='586043'>just</span> <span m='586339'>two</span> <span m='586634'>registers</span>
  <span m='586930'>(R2</span> <span m='587226'>and</span> <span m='587522'>R28)</span>
  <span m='587818'>to</span> <span m='588114'>hold</span> <span m='588409'>all</span>
  <span m='588705'>the</span> <span m='589001'>values</span> <span m='589297'>we</span>
  <span m='589593'>need</span> <span m='589889'>to</span> <span m='590919'>save.</span>
  </p><p><span m='591949'>One</span> <span m='592334'>fix</span> <span m='592719'>is</span>
  <span m='593104'>to</span> <span m='593489'>disallow</span> <span m='593874'>recursion!</span>
  </p><p><span m='594259'>And,</span> <span m='594645'>in</span> <span m='595031'>fact,</span>
  <span m='595417'>some</span> <span m='595803'>of</span> <span m='596189'>the</span>
  <span m='596575'>early</span> <span m='596961'>programming</span> <span m='597347'>languages</span>
  <span m='597733'>such</span> <span m='598119'>as</span> <span m='598505'>FORTRAN</span>
  <span m='598891'>did</span> <span m='599277'>just</span> <span m='599663'>that.</span>
  </p><p><span m='600050'>But</span> <span m='600266'>let's</span> <span m='600482'>see</span>
  <span m='600698'>if</span> <span m='600915'>we</span> <span m='601131'>can</span>
  <span m='601347'>solve</span> <span m='601563'>the</span> <span m='601780'>problem</span>
  <span m='601996'>another</span> <span m='602212'>way.</span> </p>
type: course
uid: 3dd2be06225ef8ed708bab00b7fa8432

---
None