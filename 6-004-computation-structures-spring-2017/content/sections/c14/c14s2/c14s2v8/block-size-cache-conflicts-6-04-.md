---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: YOABS3tTHVc
  parent_uid: d5f9acf8b2954cfb222b4b85d525146e
  title: Video-YouTube-Stream
  type: Video
  uid: 25efa924752fe3306cc622c5c29589fb
- id: 3Play-3Play YouTube id-Stream
  media_location: YOABS3tTHVc
  parent_uid: d5f9acf8b2954cfb222b4b85d525146e
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: e613ddaacfa59fc339f4494479fe50dc
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/YOABS3tTHVc/default.jpg
  parent_uid: d5f9acf8b2954cfb222b4b85d525146e
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 18220f6ef46a712cbe5698b01c27e9e8
- id: YOABS3tTHVc.srt
  parent_uid: d5f9acf8b2954cfb222b4b85d525146e
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v8/block-size-cache-conflicts-6-04-/YOABS3tTHVc.srt
  title: 3play caption file
  type: null
  uid: 8bec6f232139e85da461210593a5bcbe
- id: YOABS3tTHVc.pdf
  parent_uid: d5f9acf8b2954cfb222b4b85d525146e
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v8/block-size-cache-conflicts-6-04-/YOABS3tTHVc.pdf
  title: 3play pdf file
  type: null
  uid: be4f169087179265ee0e4110a6f6ee0a
- id: Caption-3Play YouTube id-SRT
  parent_uid: d5f9acf8b2954cfb222b4b85d525146e
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 4d046103de40263c5a910d7c5c2b7e7c
- id: Transcript-3Play YouTube id-PDF
  parent_uid: d5f9acf8b2954cfb222b4b85d525146e
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 6c89e27b7e645e17c01f9ce16928b2c5
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_14-02-08_300k.mp4
  parent_uid: d5f9acf8b2954cfb222b4b85d525146e
  title: Video-Internet Archive-MP4
  type: Video
  uid: 3e4a6d1a789d83e19516ebdcc28c3f2b
inline_embed_id: 56229110blocksizecacheconflicts60491136298
layout: video
order_index: null
parent_uid: e778a100db84c0a0740e6225dbe58ab4
related_resources_text: ''
short_url: block-size-cache-conflicts-6-04-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v8/block-size-cache-conflicts-6-04-
template_type: Embed
title: Block Size; Cache Conflicts (6:04)
transcript: <p><span m='459'>We</span> <span m='744'>can</span> <span m='1030'>tweak</span>
  <span m='1315'>the</span> <span m='1601'>design</span> <span m='1887'>of</span>
  <span m='2172'>the</span> <span m='2458'>DM</span> <span m='2743'>cache</span> <span
  m='3029'>a</span> <span m='3315'>little</span> <span m='3600'>to</span> <span m='3886'>take</span>
  <span m='4171'>advantage</span> <span m='4457'>of</span> <span m='4743'>locality</span>
  <span m='5028'>and</span> <span m='5314'>save</span> <span m='5600'>some</span>
  <span m='5968'>of</span> <span m='6336'>the</span> <span m='6704'>overhead</span>
  <span m='7072'>of</span> <span m='7440'>tag</span> <span m='7808'>fields</span>
  <span m='8176'>and</span> <span m='8544'>valid</span> <span m='8912'>bits.</span>
  </p><p><span m='9280'>We</span> <span m='9556'>can</span> <span m='9832'>increase</span>
  <span m='10108'>the</span> <span m='10384'>size</span> <span m='10660'>of</span>
  <span m='10937'>the</span> <span m='11213'>data</span> <span m='11489'>field</span>
  <span m='11765'>in</span> <span m='12041'>a</span> <span m='12318'>cache</span>
  <span m='12594'>from</span> <span m='12870'>1</span> <span m='13146'>word</span>
  <span m='13422'>to</span> <span m='13699'>2</span> <span m='13975'>words,</span>
  <span m='14251'>or</span> <span m='14527'>4</span> <span m='14803'>words,</span>
  <span m='15080'>etc.</span> </p><p><span m='16079'>The</span> <span m='16294'>number</span>
  <span m='16509'>of</span> <span m='16724'>data</span> <span m='16939'>words</span>
  <span m='17154'>in</span> <span m='17369'>each</span> <span m='17584'>cache</span>
  <span m='17799'>line</span> <span m='18014'>is</span> <span m='18229'>called</span>
  <span m='18444'>the</span> <span m='18659'>"block</span> <span m='18874'>size"</span>
  <span m='19089'>and</span> <span m='19304'>is</span> <span m='19519'>always</span>
  <span m='19734'>a</span> <span m='19949'>power</span> <span m='20682'>of</span>
  <span m='21416'>two.</span> </p><p><span m='22150'>Using</span> <span m='22511'>a</span>
  <span m='22872'>larger</span> <span m='23233'>block</span> <span m='23595'>size</span>
  <span m='23956'>makes</span> <span m='24317'>sense.</span> </p><p><span m='24679'>If</span>
  <span m='25023'>there's</span> <span m='25368'>a</span> <span m='25713'>high</span>
  <span m='26057'>probability</span> <span m='26402'>of</span> <span m='26747'>accessing</span>
  <span m='27091'>nearby</span> <span m='27436'>words,</span> <span m='27781'>why</span>
  <span m='28125'>not</span> <span m='28470'>fetch</span> <span m='28815'>a</span>
  <span m='29159'>larger</span> <span m='29504'>block</span> <span m='29849'>of</span>
  <span m='30210'>words</span> <span m='30572'>on</span> <span m='30934'>a</span>
  <span m='31296'>cache</span> <span m='31658'>miss,</span> <span m='32019'>trading</span>
  <span m='32381'>the</span> <span m='32743'>increased</span> <span m='33105'>cost</span>
  <span m='33467'>of</span> <span m='33829'>the</span> <span m='34190'>miss</span>
  <span m='34552'>against</span> <span m='34914'>the</span> <span m='35276'>increased</span>
  <span m='35638'>probability</span> <span m='36000'>of</span> <span m='36896'>future</span>
  <span m='37793'>hits.</span> </p><p><span m='38690'>Compare</span> <span m='39078'>the</span>
  <span m='39467'>16-word</span> <span m='39856'>DM</span> <span m='40245'>cache</span>
  <span m='40634'>shown</span> <span m='41022'>here</span> <span m='41411'>with</span>
  <span m='41800'>a</span> <span m='42189'>block</span> <span m='42578'>size</span>
  <span m='42967'>of</span> <span m='43355'>4</span> <span m='43744'>with</span> <span
  m='44133'>a</span> <span m='44522'>different</span> <span m='44911'>16-word</span>
  <span m='45300'>DM</span> <span m='45681'>cache</span> <span m='46062'>with</span>
  <span m='46443'>a</span> <span m='46825'>block</span> <span m='47206'>size</span>
  <span m='47587'>of</span> <span m='47968'>1.</span> </p><p><span m='48350'>In</span>
  <span m='48714'>this</span> <span m='49079'>cache</span> <span m='49443'>for</span>
  <span m='49808'>every</span> <span m='50172'>128</span> <span m='50537'>bits</span>
  <span m='50901'>of</span> <span m='51266'>data</span> <span m='51630'>there</span>
  <span m='51995'>are</span> <span m='52359'>27</span> <span m='52724'>bits</span>
  <span m='53088'>of</span> <span m='53453'>tags</span> <span m='53817'>and</span>
  <span m='54182'>valid</span> <span m='54546'>bit,</span> <span m='54911'>so</span>
  <span m='55275'>~17%</span> <span m='55640'>of</span> <span m='56055'>the</span>
  <span m='56471'>SRAM</span> <span m='56887'>bits</span> <span m='57303'>are</span>
  <span m='57719'>overhead</span> <span m='58135'>in</span> <span m='58551'>the</span>
  <span m='58967'>sense</span> <span m='59382'>that</span> <span m='59798'>they're</span>
  <span m='60214'>not</span> <span m='60630'>being</span> <span m='61046'>used</span>
  <span m='61462'>to</span> <span m='61878'>store</span> <span m='62294'>data.</span>
  </p><p><span m='62710'>In</span> <span m='62971'>the</span> <span m='63233'>cache</span>
  <span m='63494'>with</span> <span m='63756'>block</span> <span m='64017'>size</span>
  <span m='64279'>1,</span> <span m='64540'>for</span> <span m='64802'>every</span>
  <span m='65063'>32</span> <span m='65325'>bits</span> <span m='65586'>of</span>
  <span m='65848'>data</span> <span m='66109'>there</span> <span m='66371'>are</span>
  <span m='66632'>27</span> <span m='66894'>bits</span> <span m='67155'>of</span>
  <span m='67417'>tag</span> <span m='67678'>and</span> <span m='67940'>valid</span>
  <span m='68417'>bit,</span> <span m='68894'>so</span> <span m='69371'>~46%</span>
  <span m='69848'>of</span> <span m='70325'>the</span> <span m='70802'>SRAM</span>
  <span m='71279'>bits</span> <span m='71756'>are</span> <span m='72233'>overhead.</span>
  </p><p><span m='72710'>So</span> <span m='73188'>a</span> <span m='73666'>larger</span>
  <span m='74145'>block</span> <span m='74623'>size</span> <span m='75102'>means</span>
  <span m='75580'>we'll</span> <span m='76059'>be</span> <span m='76537'>using</span>
  <span m='77016'>the</span> <span m='77494'>SRAM</span> <span m='77973'>more</span>
  <span m='78451'>efficiently.</span> </p><p><span m='78930'>Since</span> <span m='79252'>there</span>
  <span m='79575'>are</span> <span m='79898'>16</span> <span m='80221'>bytes</span>
  <span m='80544'>of</span> <span m='80867'>data</span> <span m='81190'>in</span>
  <span m='81513'>each</span> <span m='81836'>cache</span> <span m='82159'>line,</span>
  <span m='82482'>there</span> <span m='82805'>are</span> <span m='83128'>now</span>
  <span m='83451'>4</span> <span m='83774'>offset</span> <span m='84097'>bits.</span>
  </p><p><span m='84420'>The</span> <span m='84680'>cache</span> <span m='84941'>uses</span>
  <span m='85201'>the</span> <span m='85462'>high-order</span> <span m='85722'>two</span>
  <span m='85983'>bits</span> <span m='86244'>of</span> <span m='86504'>the</span>
  <span m='86765'>offset</span> <span m='87025'>to</span> <span m='87286'>select</span>
  <span m='87547'>which</span> <span m='87807'>of</span> <span m='88068'>the</span>
  <span m='88328'>4</span> <span m='88589'>words</span> <span m='88850'>to</span>
  <span m='89344'>return</span> <span m='89838'>to</span> <span m='90333'>the</span>
  <span m='90827'>CPU</span> <span m='91321'>on</span> <span m='91816'>a</span> <span
  m='92310'>cache</span> <span m='92804'>hit.</span> </p><p><span m='93299'>There</span>
  <span m='93625'>are</span> <span m='93952'>4</span> <span m='94278'>cache</span>
  <span m='94605'>lines,</span> <span m='94931'>so</span> <span m='95258'>we'll</span>
  <span m='95584'>need</span> <span m='95911'>two</span> <span m='96237'>cache</span>
  <span m='96564'>line</span> <span m='96890'>index</span> <span m='97217'>bits</span>
  <span m='97543'>from</span> <span m='97870'>the</span> <span m='98196'>incoming</span>
  <span m='98523'>address.</span> </p><p><span m='98850'>And,</span> <span m='99410'>finally,</span>
  <span m='99970'>the</span> <span m='100530'>remaining</span> <span m='101090'>26</span>
  <span m='101650'>address</span> <span m='102210'>bits</span> <span m='102770'>are</span>
  <span m='103330'>used</span> <span m='103890'>as</span> <span m='104450'>the</span>
  <span m='105010'>tag</span> <span m='105570'>field.</span> </p><p><span m='106130'>Note</span>
  <span m='106427'>that</span> <span m='106725'>there's</span> <span m='107022'>only</span>
  <span m='107320'>a</span> <span m='107617'>single</span> <span m='107915'>valid</span>
  <span m='108212'>bit</span> <span m='108510'>for</span> <span m='108807'>each</span>
  <span m='109105'>cache</span> <span m='109402'>line,</span> <span m='109700'>so</span>
  <span m='109997'>either</span> <span m='110295'>the</span> <span m='110592'>entire</span>
  <span m='110890'>4-word</span> <span m='111229'>block</span> <span m='111569'>is</span>
  <span m='111909'>present</span> <span m='112249'>in</span> <span m='112589'>the</span>
  <span m='112929'>cache</span> <span m='113269'>or</span> <span m='113609'>it's</span>
  <span m='113949'>not.</span> </p><p><span m='114289'>Would</span> <span m='114701'>it</span>
  <span m='115114'>be</span> <span m='115526'>worth</span> <span m='115939'>the</span>
  <span m='116351'>extra</span> <span m='116764'>complication</span> <span m='117177'>to</span>
  <span m='117589'>support</span> <span m='118002'>caching</span> <span m='118414'>partial</span>
  <span m='118827'>blocks?</span> </p><p><span m='119240'>Probably</span> <span m='120065'>not.</span>
  </p><p><span m='120890'>Locality</span> <span m='121137'>tells</span> <span m='121385'>us</span>
  <span m='121632'>that</span> <span m='121880'>we'll</span> <span m='122127'>probably</span>
  <span m='122375'>want</span> <span m='122622'>those</span> <span m='122870'>other</span>
  <span m='123117'>words</span> <span m='123365'>in</span> <span m='123612'>the</span>
  <span m='123860'>near</span> <span m='124107'>future,</span> <span m='124355'>so</span>
  <span m='124602'>having</span> <span m='124850'>them</span> <span m='125225'>in</span>
  <span m='125600'>the</span> <span m='125975'>cache</span> <span m='126350'>will</span>
  <span m='126725'>likely</span> <span m='127100'>improve</span> <span m='127475'>the</span>
  <span m='127850'>hit</span> <span m='128225'>ratio.</span> </p><p><span m='128600'>What's</span>
  <span m='129083'>the</span> <span m='129567'>tradeoff</span> <span m='130051'>between</span>
  <span m='130535'>block</span> <span m='131018'>size</span> <span m='131502'>and</span>
  <span m='131986'>performance?</span> </p><p><span m='132470'>We've</span> <span
  m='132775'>argued</span> <span m='133080'>that</span> <span m='133386'>increasing</span>
  <span m='133691'>the</span> <span m='133996'>block</span> <span m='134302'>size</span>
  <span m='134607'>from</span> <span m='134913'>1</span> <span m='135218'>was</span>
  <span m='135523'>a</span> <span m='135829'>good</span> <span m='136134'>idea.</span>
  </p><p><span m='136440'>Is</span> <span m='136721'>there</span> <span m='137002'>a</span>
  <span m='137283'>limit</span> <span m='137564'>to</span> <span m='137845'>how</span>
  <span m='138126'>large</span> <span m='138407'>blocks</span> <span m='138688'>should</span>
  <span m='138969'>be?</span> </p><p><span m='139250'>Let's</span> <span m='139629'>look</span>
  <span m='140008'>at</span> <span m='140387'>the</span> <span m='140766'>costs</span>
  <span m='141145'>and</span> <span m='141525'>benefits</span> <span m='141904'>of</span>
  <span m='142283'>an</span> <span m='142662'>increased</span> <span m='143041'>block</span>
  <span m='143420'>size.</span> </p><p><span m='143800'>With</span> <span m='144095'>a</span>
  <span m='144390'>larger</span> <span m='144685'>block</span> <span m='144981'>size</span>
  <span m='145276'>we</span> <span m='145571'>have</span> <span m='145866'>to</span>
  <span m='146162'>fetch</span> <span m='146457'>more</span> <span m='146752'>words</span>
  <span m='147047'>on</span> <span m='147343'>a</span> <span m='147638'>cache</span>
  <span m='147933'>miss</span> <span m='148228'>and</span> <span m='148524'>the</span>
  <span m='148819'>miss</span> <span m='149114'>penalty</span> <span m='149410'>grows</span>
  <span m='150095'>linearly</span> <span m='150780'>with</span> <span m='151465'>increasing</span>
  <span m='152150'>block</span> <span m='152835'>size.</span> </p><p><span m='153520'>Note</span>
  <span m='153810'>that</span> <span m='154101'>since</span> <span m='154391'>the</span>
  <span m='154682'>access</span> <span m='154972'>time</span> <span m='155263'>for</span>
  <span m='155554'>the</span> <span m='155844'>first</span> <span m='156135'>word</span>
  <span m='156425'>from</span> <span m='156716'>DRAM</span> <span m='157007'>is</span>
  <span m='157297'>quite</span> <span m='157588'>high,</span> <span m='157878'>the</span>
  <span m='158169'>increased</span> <span m='158460'>miss</span> <span m='158962'>penalty</span>
  <span m='159464'>isn't</span> <span m='159966'>as</span> <span m='160468'>painful</span>
  <span m='160971'>as</span> <span m='161473'>it</span> <span m='161975'>might</span>
  <span m='162477'>be.</span> </p><p><span m='162980'>Increasing</span> <span m='163258'>the</span>
  <span m='163537'>block</span> <span m='163816'>size</span> <span m='164094'>past</span>
  <span m='164373'>1</span> <span m='164652'>reduces</span> <span m='164930'>the</span>
  <span m='165209'>miss</span> <span m='165488'>ratio</span> <span m='165766'>since</span>
  <span m='166045'>we're</span> <span m='166324'>bringing</span> <span m='166602'>words</span>
  <span m='166881'>into</span> <span m='167160'>the</span> <span m='167603'>cache</span>
  <span m='168047'>that</span> <span m='168490'>will</span> <span m='168934'>then</span>
  <span m='169378'>be</span> <span m='169821'>cache</span> <span m='170265'>hits</span>
  <span m='170709'>on</span> <span m='171152'>subsequent</span> <span m='171596'>accesses.</span>
  </p><p><span m='172040'>Assuming</span> <span m='172413'>we</span> <span m='172786'>don't</span>
  <span m='173159'>increase</span> <span m='173532'>the</span> <span m='173905'>overall</span>
  <span m='174278'>cache</span> <span m='174651'>capacity,</span> <span m='175024'>increasing</span>
  <span m='175397'>the</span> <span m='175770'>block</span> <span m='176143'>size</span>
  <span m='176516'>means</span> <span m='176890'>we'll</span> <span m='177374'>make</span>
  <span m='177859'>a</span> <span m='178343'>corresponding</span> <span m='178828'>reduction</span>
  <span m='179312'>in</span> <span m='179797'>the</span> <span m='180281'>number</span>
  <span m='180766'>of</span> <span m='181250'>cache</span> <span m='181735'>lines.</span>
  </p><p><span m='182220'>Reducing</span> <span m='182495'>the</span> <span m='182770'>number</span>
  <span m='183045'>of</span> <span m='183320'>lines</span> <span m='183595'>impacts</span>
  <span m='183870'>the</span> <span m='184145'>number</span> <span m='184420'>of</span>
  <span m='184695'>separate</span> <span m='184970'>address</span> <span m='185245'>blocks</span>
  <span m='185520'>that</span> <span m='185795'>can</span> <span m='186070'>be</span>
  <span m='186345'>accommodated</span> <span m='186620'>in</span> <span m='187210'>the</span>
  <span m='187800'>cache.</span> </p><p><span m='188390'>As</span> <span m='188631'>we</span>
  <span m='188872'>saw</span> <span m='189113'>in</span> <span m='189354'>the</span>
  <span m='189595'>discussion</span> <span m='189837'>on</span> <span m='190078'>the</span>
  <span m='190319'>size</span> <span m='190560'>of</span> <span m='190801'>the</span>
  <span m='191042'>working</span> <span m='191284'>set</span> <span m='191525'>of</span>
  <span m='191766'>a</span> <span m='192007'>running</span> <span m='192248'>program,</span>
  <span m='192489'>there</span> <span m='192731'>are</span> <span m='192980'>a</span>
  <span m='193230'>certain</span> <span m='193480'>number</span> <span m='193730'>of</span>
  <span m='193980'>separate</span> <span m='194230'>regions</span> <span m='194480'>we</span>
  <span m='194730'>need</span> <span m='194980'>to</span> <span m='195230'>accommodate</span>
  <span m='195480'>to</span> <span m='195730'>achieve</span> <span m='195980'>a</span>
  <span m='196230'>high</span> <span m='196480'>hit</span> <span m='196730'>ratio:</span>
  <span m='197482'>program,</span> <span m='198234'>stack,</span> <span m='198986'>data,</span>
  <span m='199738'>etc.</span> </p><p><span m='200490'>So</span> <span m='200762'>we</span>
  <span m='201035'>need</span> <span m='201308'>to</span> <span m='201581'>ensure</span>
  <span m='201854'>there</span> <span m='202127'>are</span> <span m='202400'>a</span>
  <span m='202673'>sufficient</span> <span m='202946'>number</span> <span m='203219'>of</span>
  <span m='203492'>blocks</span> <span m='203765'>to</span> <span m='204038'>hold</span>
  <span m='204311'>the</span> <span m='204584'>different</span> <span m='204857'>addresses</span>
  <span m='205130'>in</span> <span m='205710'>the</span> <span m='206290'>working</span>
  <span m='206870'>set.</span> </p><p><span m='207450'>The</span> <span m='207800'>bottom</span>
  <span m='208150'>line</span> <span m='208500'>is</span> <span m='208850'>that</span>
  <span m='209200'>there</span> <span m='209550'>is</span> <span m='209900'>an</span>
  <span m='210250'>optimum</span> <span m='210600'>block</span> <span m='210950'>size</span>
  <span m='211300'>that</span> <span m='211650'>minimizes</span> <span m='212000'>the</span>
  <span m='212350'>miss</span> <span m='212700'>ratio</span> <span m='213050'>and</span>
  <span m='213400'>increasing</span> <span m='213873'>the</span> <span m='214346'>block</span>
  <span m='214819'>size</span> <span m='215292'>past</span> <span m='215765'>that</span>
  <span m='216238'>point</span> <span m='216711'>will</span> <span m='217184'>be</span>
  <span m='217657'>counterproductive.</span> </p><p><span m='218130'>Combining</span>
  <span m='218504'>the</span> <span m='218878'>information</span> <span m='219253'>in</span>
  <span m='219627'>these</span> <span m='220001'>two</span> <span m='220376'>graphs,</span>
  <span m='220750'>we</span> <span m='221125'>can</span> <span m='221499'>use</span>
  <span m='221873'>the</span> <span m='222248'>formula</span> <span m='222622'>for</span>
  <span m='222996'>AMAT</span> <span m='223371'>to</span> <span m='223745'>choose</span>
  <span m='224120'>the</span> <span m='224654'>block</span> <span m='225188'>size</span>
  <span m='225722'>the</span> <span m='226256'>gives</span> <span m='226790'>us</span>
  <span m='227324'>the</span> <span m='227858'>best</span> <span m='228392'>possible</span>
  <span m='228926'>AMAT.</span> </p><p><span m='229460'>In</span> <span m='229957'>modern</span>
  <span m='230455'>processors,</span> <span m='230952'>a</span> <span m='231450'>common</span>
  <span m='231947'>block</span> <span m='232445'>size</span> <span m='232942'>is</span>
  <span m='233440'>64</span> <span m='233937'>bytes</span> <span m='234435'>(16</span>
  <span m='234932'>words).</span> </p><p><span m='235430'>DM</span> <span m='236021'>caches</span>
  <span m='236612'>do</span> <span m='237204'>have</span> <span m='237795'>an</span>
  <span m='238387'>Achilles</span> <span m='238978'>heel.</span> </p><p><span m='239570'>Consider</span>
  <span m='239975'>running</span> <span m='240381'>the</span> <span m='240787'>3-instruction</span>
  <span m='241193'>LOOPA</span> <span m='241599'>code</span> <span m='242005'>with</span>
  <span m='242410'>the</span> <span m='242816'>instructions</span> <span m='243222'>located</span>
  <span m='243628'>starting</span> <span m='244034'>at</span> <span m='244440'>word</span>
  <span m='244831'>address</span> <span m='245223'>1024</span> <span m='245615'>and</span>
  <span m='246007'>the</span> <span m='246399'>data</span> <span m='246791'>starting</span>
  <span m='247183'>at</span> <span m='247575'>word</span> <span m='247966'>address</span>
  <span m='248358'>37</span> <span m='248750'>where</span> <span m='249142'>the</span>
  <span m='249534'>program</span> <span m='249926'>is</span> <span m='250318'>making</span>
  <span m='250710'>alternating</span> <span m='251160'>accesses</span> <span m='251611'>to</span>
  <span m='252062'>instruction</span> <span m='252513'>and</span> <span m='252964'>data,</span>
  <span m='253415'>e.g.,</span> <span m='253865'>a</span> <span m='254316'>loop</span>
  <span m='254767'>of</span> <span m='255218'>LD</span> <span m='255669'>instructions.</span>
  </p><p><span m='256120'>Assuming</span> <span m='256490'>a</span> <span m='256861'>1024-line</span>
  <span m='257231'>DM</span> <span m='257602'>cache</span> <span m='257972'>with</span>
  <span m='258343'>a</span> <span m='258713'>block</span> <span m='259084'>size</span>
  <span m='259454'>of</span> <span m='259825'>1,</span> <span m='260195'>the</span>
  <span m='260566'>steady</span> <span m='260936'>state</span> <span m='261307'>hit</span>
  <span m='261677'>ratio</span> <span m='262048'>will</span> <span m='262419'>be</span>
  <span m='262783'>100%</span> <span m='263147'>once</span> <span m='263511'>all</span>
  <span m='263875'>six</span> <span m='264239'>locations</span> <span m='264604'>have</span>
  <span m='264968'>been</span> <span m='265332'>loaded</span> <span m='265696'>into</span>
  <span m='266060'>the</span> <span m='266424'>cache</span> <span m='266789'>since</span>
  <span m='267153'>each</span> <span m='267517'>location</span> <span m='267881'>is</span>
  <span m='268245'>mapped</span> <span m='268610'>to</span> <span m='269248'>a</span>
  <span m='269886'>different</span> <span m='270524'>cache</span> <span m='271162'>line.</span>
  </p><p><span m='271800'>Now</span> <span m='272126'>consider</span> <span m='272453'>the</span>
  <span m='272780'>execution</span> <span m='273107'>of</span> <span m='273434'>the</span>
  <span m='273761'>same</span> <span m='274088'>program,</span> <span m='274415'>but</span>
  <span m='274741'>this</span> <span m='275068'>time</span> <span m='275395'>the</span>
  <span m='275722'>data</span> <span m='276049'>has</span> <span m='276376'>been</span>
  <span m='276703'>relocated</span> <span m='277030'>to</span> <span m='277594'>start</span>
  <span m='278159'>at</span> <span m='278724'>word</span> <span m='279289'>address</span>
  <span m='279854'>2048.</span> </p><p><span m='280419'>Now</span> <span m='280782'>the</span>
  <span m='281146'>instructions</span> <span m='281509'>and</span> <span m='281873'>data</span>
  <span m='282236'>are</span> <span m='282600'>competing</span> <span m='282964'>for</span>
  <span m='283327'>use</span> <span m='283691'>of</span> <span m='284054'>the</span>
  <span m='284418'>same</span> <span m='284781'>cache</span> <span m='285145'>lines.</span>
  </p><p><span m='285509'>For</span> <span m='285881'>example,</span> <span m='286254'>the</span>
  <span m='286627'>first</span> <span m='286999'>instruction</span> <span m='287372'>(at</span>
  <span m='287745'>address</span> <span m='288117'>1024)</span> <span m='288490'>and</span>
  <span m='288863'>the</span> <span m='289235'>first</span> <span m='289608'>data</span>
  <span m='289981'>word</span> <span m='290353'>(at</span> <span m='290726'>address</span>
  <span m='291099'>2048)</span> <span m='291499'>both</span> <span m='291900'>map</span>
  <span m='292300'>to</span> <span m='292701'>cache</span> <span m='293101'>line</span>
  <span m='293502'>0,</span> <span m='293903'>so</span> <span m='294303'>only</span>
  <span m='294704'>one</span> <span m='295104'>them</span> <span m='295505'>can</span>
  <span m='295905'>be</span> <span m='296306'>in</span> <span m='296707'>the</span>
  <span m='297107'>cache</span> <span m='297508'>at</span> <span m='297908'>a</span>
  <span m='298309'>time.</span> </p><p><span m='298710'>So</span> <span m='299099'>fetching</span>
  <span m='299488'>the</span> <span m='299878'>first</span> <span m='300267'>instruction</span>
  <span m='300656'>fills</span> <span m='301046'>cache</span> <span m='301435'>line</span>
  <span m='301824'>0</span> <span m='302214'>with</span> <span m='302603'>the</span>
  <span m='302992'>contents</span> <span m='303382'>of</span> <span m='303771'>location</span>
  <span m='304160'>1024,</span> <span m='304550'>but</span> <span m='304891'>then</span>
  <span m='305233'>the</span> <span m='305575'>first</span> <span m='305917'>data</span>
  <span m='306259'>access</span> <span m='306601'>misses</span> <span m='306943'>and</span>
  <span m='307285'>then</span> <span m='307626'>refills</span> <span m='307968'>cache</span>
  <span m='308310'>line</span> <span m='308652'>0</span> <span m='308994'>with</span>
  <span m='309336'>the</span> <span m='309678'>contents</span> <span m='310020'>of</span>
  <span m='311073'>location</span> <span m='312126'>2048.</span> </p><p><span m='313180'>The</span>
  <span m='313595'>data</span> <span m='314010'>address</span> <span m='314426'>is</span>
  <span m='314841'>said</span> <span m='315256'>to</span> <span m='315672'>"conflict"</span>
  <span m='316087'>with</span> <span m='316502'>the</span> <span m='316918'>instruction</span>
  <span m='317333'>address.</span> </p><p><span m='317749'>The</span> <span m='317964'>next</span>
  <span m='318179'>time</span> <span m='318394'>through</span> <span m='318609'>the</span>
  <span m='318824'>loop,</span> <span m='319039'>the</span> <span m='319254'>first</span>
  <span m='319469'>instruction</span> <span m='319684'>will</span> <span m='319899'>no</span>
  <span m='320114'>longer</span> <span m='320329'>be</span> <span m='320544'>in</span>
  <span m='320759'>the</span> <span m='320974'>cache</span> <span m='321190'>and</span>
  <span m='321571'>it's</span> <span m='321953'>fetch</span> <span m='322335'>will</span>
  <span m='322716'>cause</span> <span m='323098'>a</span> <span m='323480'>cache</span>
  <span m='323861'>miss,</span> <span m='324243'>called</span> <span m='324625'>a</span>
  <span m='325006'>"conflict</span> <span m='325388'>miss".</span> </p><p><span m='325770'>So</span>
  <span m='326182'>in</span> <span m='326595'>the</span> <span m='327007'>steady</span>
  <span m='327420'>state,</span> <span m='327832'>the</span> <span m='328245'>cache</span>
  <span m='328657'>will</span> <span m='329070'>never</span> <span m='329482'>contain</span>
  <span m='329895'>the</span> <span m='330307'>word</span> <span m='330720'>requested</span>
  <span m='331132'>by</span> <span m='331545'>the</span> <span m='331957'>CPU.</span>
  </p><p><span m='332370'>This</span> <span m='332915'>is</span> <span m='333460'>very</span>
  <span m='334005'>unfortunate!</span> </p><p><span m='334550'>We</span> <span m='334825'>were</span>
  <span m='335101'>hoping</span> <span m='335376'>to</span> <span m='335652'>design</span>
  <span m='335928'>a</span> <span m='336203'>memory</span> <span m='336479'>system</span>
  <span m='336755'>that</span> <span m='337030'>offered</span> <span m='337306'>the</span>
  <span m='337581'>simple</span> <span m='337857'>abstraction</span> <span m='338133'>of</span>
  <span m='338408'>a</span> <span m='338684'>flat,</span> <span m='338960'>uniform</span>
  <span m='339713'>address</span> <span m='340466'>space.</span> </p><p><span m='341220'>But</span>
  <span m='341509'>in</span> <span m='341798'>this</span> <span m='342088'>example</span>
  <span m='342377'>we</span> <span m='342667'>see</span> <span m='342956'>that</span>
  <span m='343246'>simply</span> <span m='343535'>changing</span> <span m='343825'>a</span>
  <span m='344114'>few</span> <span m='344403'>addresses</span> <span m='344693'>results</span>
  <span m='344982'>in</span> <span m='345272'>the</span> <span m='345561'>cache</span>
  <span m='345851'>hit</span> <span m='346140'>ratio</span> <span m='346430'>dropping</span>
  <span m='347262'>from</span> <span m='348094'>100%</span> <span m='348926'>to</span>
  <span m='349758'>0%.</span> </p><p><span m='350590'>The</span> <span m='350989'>programmer</span>
  <span m='351388'>will</span> <span m='351787'>certainly</span> <span m='352186'>notice</span>
  <span m='352585'>her</span> <span m='352984'>program</span> <span m='353383'>running</span>
  <span m='353782'>10</span> <span m='354181'>times</span> <span m='354580'>slower!</span>
  </p><p><span m='354979'>So</span> <span m='355330'>while</span> <span m='355681'>we</span>
  <span m='356032'>like</span> <span m='356384'>the</span> <span m='356735'>simplicity</span>
  <span m='357086'>of</span> <span m='357437'>DM</span> <span m='357789'>caches,</span>
  <span m='358140'>we'll</span> <span m='358491'>need</span> <span m='358842'>to</span>
  <span m='359194'>make</span> <span m='359545'>some</span> <span m='359896'>architectural</span>
  <span m='360247'>changes</span> <span m='360599'>to</span> <span m='360966'>avoid</span>
  <span m='361334'>the</span> <span m='361702'>performance</span> <span m='362070'>problems</span>
  <span m='362437'>caused</span> <span m='362805'>by</span> <span m='363173'>conflict</span>
  <span m='363541'>misses.</span> </p>
type: course
uid: d5f9acf8b2954cfb222b4b85d525146e

---
None