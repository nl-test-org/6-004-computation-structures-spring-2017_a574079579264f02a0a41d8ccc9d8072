---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: P_YdbHBRzC4
  parent_uid: 1861426cb17105587df01a7fff7d5555
  title: Video-YouTube-Stream
  type: Video
  uid: f6f364f80af95bd117e3948bd544ac68
- id: 3Play-3Play YouTube id-Stream
  media_location: P_YdbHBRzC4
  parent_uid: 1861426cb17105587df01a7fff7d5555
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 6b7a071189055e0698f55d0eb63b6a6a
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/P_YdbHBRzC4/default.jpg
  parent_uid: 1861426cb17105587df01a7fff7d5555
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 3a7b2506722b18f6e1cf1fa7ab3b413a
- id: P_YdbHBRzC4.srt
  parent_uid: 1861426cb17105587df01a7fff7d5555
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/c11s2v3/compiling-statements-3.53-/P_YdbHBRzC4.srt
  title: 3play caption file
  type: null
  uid: cc9cd1447688e0708730451af54b757d
- id: P_YdbHBRzC4.pdf
  parent_uid: 1861426cb17105587df01a7fff7d5555
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/c11s2v3/compiling-statements-3.53-/P_YdbHBRzC4.pdf
  title: 3play pdf file
  type: null
  uid: b6d69e5bfe4e2e9e1a8c7ace6ce29691
- id: Caption-3Play YouTube id-SRT
  parent_uid: 1861426cb17105587df01a7fff7d5555
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: cacbbe62281e44dca785b4df9a1b6a2a
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 1861426cb17105587df01a7fff7d5555
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: e0ab71460128400feadbb7ab631151d8
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_11-02-03_300k.mp4
  parent_uid: 1861426cb17105587df01a7fff7d5555
  title: Video-Internet Archive-MP4
  type: Video
  uid: 7dcec1a20347dc0d79f2dc90631fa73a
inline_embed_id: 93620683compilingstatements3.5384226008
layout: video
order_index: null
parent_uid: a1efec399a74efd3c2f2729f65630bcc
related_resources_text: ''
short_url: compiling-statements-3.53-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/c11s2v3/compiling-statements-3.53-
template_type: Embed
title: Compiling Statements (3.53)
transcript: <p><span m='380'>Now</span> <span m='817'>let's</span> <span m='1255'>turn</span>
  <span m='1692'>our</span> <span m='2130'>attention</span> <span m='2567'>to</span>
  <span m='3005'>compile</span> <span m='3442'>statement.</span> </p><p><span m='3880'>The</span>
  <span m='4194'>first</span> <span m='4508'>two</span> <span m='4822'>statement</span>
  <span m='5136'>types</span> <span m='5450'>are</span> <span m='5764'>pretty</span>
  <span m='6078'>easy</span> <span m='6392'>to</span> <span m='6706'>handle.</span>
  </p><p><span m='7020'>Unconditional</span> <span m='7551'>statements</span> <span
  m='8082'>are</span> <span m='8613'>usually</span> <span m='9144'>assignment</span>
  <span m='9675'>expressions</span> <span m='10206'>or</span> <span m='10737'>procedure</span>
  <span m='11268'>calls.</span> </p><p><span m='11800'>We'll</span> <span m='12373'>simply</span>
  <span m='12946'>ask</span> <span m='13520'>compile_expr</span> <span m='14093'>to</span>
  <span m='14666'>generate</span> <span m='15240'>the</span> <span m='15813'>appropriate</span>
  <span m='16386'>code.</span> </p><p><span m='16960'>Compound</span> <span m='17460'>statements</span>
  <span m='17960'>are</span> <span m='18460'>equally</span> <span m='18960'>easy.</span>
  </p><p><span m='19460'>We'll</span> <span m='19905'>recursively</span> <span m='20351'>call</span>
  <span m='20797'>compile_statement</span> <span m='21243'>to</span> <span m='21689'>generate</span>
  <span m='22135'>code</span> <span m='22580'>for</span> <span m='23026'>each</span>
  <span m='23472'>statement</span> <span m='23918'>in</span> <span m='24364'>turn.</span>
  </p><p><span m='24810'>The</span> <span m='25260'>code</span> <span m='25710'>for</span>
  <span m='26160'>statement_2</span> <span m='26610'>will</span> <span m='27060'>immediately</span>
  <span m='27510'>follow</span> <span m='27960'>the</span> <span m='28410'>code</span>
  <span m='28860'>generated</span> <span m='29310'>for</span> <span m='29760'>statement_1.</span>
  </p><p><span m='30210'>Execution</span> <span m='30594'>will</span> <span m='30978'>proceed</span>
  <span m='31362'>sequentially</span> <span m='31746'>through</span> <span m='32130'>the</span>
  <span m='32514'>code</span> <span m='32898'>for</span> <span m='33282'>each</span>
  <span m='33666'>statement.</span> </p><p><span m='34050'>Here</span> <span m='34373'>we</span>
  <span m='34696'>see</span> <span m='35020'>the</span> <span m='35343'>simplest</span>
  <span m='35666'>form</span> <span m='35990'>the</span> <span m='36313'>conditional</span>
  <span m='36636'>statement,</span> <span m='36960'>where</span> <span m='37283'>we</span>
  <span m='37606'>need</span> <span m='37930'>to</span> <span m='38253'>generate</span>
  <span m='38576'>code</span> <span m='38900'>to</span> <span m='39248'>evaluate</span>
  <span m='39596'>the</span> <span m='39944'>test</span> <span m='40292'>expression</span>
  <span m='40640'>and</span> <span m='40988'>then,</span> <span m='41336'>if</span>
  <span m='41685'>the</span> <span m='42033'>value</span> <span m='42381'>in</span>
  <span m='42729'>the</span> <span m='43077'>register</span> <span m='43425'>is</span>
  <span m='43773'>FALSE,</span> <span m='44121'>skip</span> <span m='44470'>over</span>
  <span m='44827'>the</span> <span m='45184'>code</span> <span m='45541'>that</span>
  <span m='45899'>executes</span> <span m='46256'>the</span> <span m='46613'>statement</span>
  <span m='46970'>in</span> <span m='47328'>the</span> <span m='47685'>THEN</span>
  <span m='48042'>clause.</span> </p><p><span m='48400'>The</span> <span m='48955'>simple</span>
  <span m='49510'>assembly-language</span> <span m='50066'>template</span> <span m='50621'>uses</span>
  <span m='51177'>recursive</span> <span m='51732'>calls</span> <span m='52288'>to</span>
  <span m='52843'>compile_expr</span> <span m='53399'>and</span> <span m='53954'>compile_statement</span>
  <span m='54510'>to</span> <span m='54960'>generate</span> <span m='55410'>code</span>
  <span m='55860'>for</span> <span m='56310'>the</span> <span m='56760'>various</span>
  <span m='57210'>parts</span> <span m='57660'>of</span> <span m='58110'>the</span>
  <span m='58560'>IF</span> <span m='59010'>statement.</span> </p><p><span m='59460'>The</span>
  <span m='59769'>full-blown</span> <span m='60078'>conditional</span> <span m='60387'>statement</span>
  <span m='60696'>includes</span> <span m='61006'>an</span> <span m='61315'>ELSE</span>
  <span m='61624'>clause,</span> <span m='61933'>which</span> <span m='62243'>should</span>
  <span m='62552'>be</span> <span m='62861'>executed</span> <span m='63170'>if</span>
  <span m='63480'>the</span> <span m='63883'>value</span> <span m='64287'>of</span>
  <span m='64691'>the</span> <span m='65095'>test</span> <span m='65498'>expression</span>
  <span m='65902'>is</span> <span m='66306'>FALSE.</span> </p><p><span m='66710'>The</span>
  <span m='67129'>template</span> <span m='67548'>uses</span> <span m='67968'>some</span>
  <span m='68387'>branches</span> <span m='68806'>and</span> <span m='69226'>labels</span>
  <span m='69645'>to</span> <span m='70065'>ensure</span> <span m='70484'>the</span>
  <span m='70903'>course</span> <span m='71323'>of</span> <span m='71742'>execution</span>
  <span m='72161'>is</span> <span m='72581'>as</span> <span m='73000'>intended.</span>
  </p><p><span m='73420'>You</span> <span m='73695'>can</span> <span m='73970'>see</span>
  <span m='74245'>that</span> <span m='74521'>the</span> <span m='74796'>compilation</span>
  <span m='75071'>process</span> <span m='75346'>is</span> <span m='75622'>really</span>
  <span m='75897'>just</span> <span m='76172'>the</span> <span m='76447'>application</span>
  <span m='76723'>of</span> <span m='76998'>many</span> <span m='77273'>small</span>
  <span m='77549'>templates</span> <span m='78016'>that</span> <span m='78483'>break</span>
  <span m='78950'>the</span> <span m='79417'>code</span> <span m='79884'>generation</span>
  <span m='80351'>task</span> <span m='80818'>down</span> <span m='81285'>step-by-step</span>
  <span m='81752'>into</span> <span m='82219'>smaller</span> <span m='82686'>and</span>
  <span m='83153'>smaller</span> <span m='83620'>tasks,</span> <span m='83967'>generating</span>
  <span m='84315'>the</span> <span m='84663'>necessary</span> <span m='85011'>code</span>
  <span m='85359'>to</span> <span m='85707'>glue</span> <span m='86055'>all</span>
  <span m='86402'>the</span> <span m='86750'>pieces</span> <span m='87098'>together</span>
  <span m='87446'>in</span> <span m='87794'>the</span> <span m='88142'>appropriate</span>
  <span m='88490'>fashion.</span> </p><p><span m='90210'>And</span> <span m='90440'>here's</span>
  <span m='90671'>the</span> <span m='90901'>template</span> <span m='91132'>for</span>
  <span m='91362'>the</span> <span m='91593'>WHILE</span> <span m='91824'>statement,</span>
  <span m='92054'>which</span> <span m='92285'>looks</span> <span m='92515'>a</span>
  <span m='92746'>lot</span> <span m='92977'>like</span> <span m='93207'>the</span>
  <span m='93438'>template</span> <span m='93668'>for</span> <span m='93899'>the</span>
  <span m='94130'>IF</span> <span m='94470'>statement</span> <span m='94811'>with</span>
  <span m='95151'>a</span> <span m='95492'>branch</span> <span m='95833'>at</span>
  <span m='96173'>the</span> <span m='96514'>end</span> <span m='96855'>that</span>
  <span m='97195'>causes</span> <span m='97536'>the</span> <span m='97876'>generated</span>
  <span m='98217'>code</span> <span m='98558'>to</span> <span m='98898'>be</span>
  <span m='99239'>re-executed</span> <span m='99580'>until</span> <span m='100014'>the</span>
  <span m='100448'>value</span> <span m='100883'>of</span> <span m='101317'>the</span>
  <span m='101752'>test</span> <span m='102186'>expression</span> <span m='102621'>is</span>
  <span m='103055'>FALSE.</span> </p><p><span m='103490'>With</span> <span m='103801'>a</span>
  <span m='104113'>bit</span> <span m='104424'>of</span> <span m='104736'>thought,</span>
  <span m='105047'>we</span> <span m='105359'>can</span> <span m='105671'>improve</span>
  <span m='105982'>on</span> <span m='106294'>this</span> <span m='106605'>template</span>
  <span m='106917'>slightly.</span> </p><p><span m='107229'>We've</span> <span m='107655'>reorganized</span>
  <span m='108082'>the</span> <span m='108508'>code</span> <span m='108935'>so</span>
  <span m='109361'>that</span> <span m='109788'>only</span> <span m='110214'>a</span>
  <span m='110641'>single</span> <span m='111067'>branch</span> <span m='111494'>instruction</span>
  <span m='111920'>(BT)</span> <span m='112347'>is</span> <span m='112773'>executed</span>
  <span m='113200'>each</span> <span m='113609'>iteration,</span> <span m='114019'>instead</span>
  <span m='114429'>of</span> <span m='114839'>the</span> <span m='115249'>two</span>
  <span m='115659'>branches</span> <span m='116069'>(BF,</span> <span m='116478'>BR)</span>
  <span m='116888'>per</span> <span m='117298'>iteration</span> <span m='117708'>in</span>
  <span m='118118'>the</span> <span m='118528'>original</span> <span m='118938'>template.</span>
  </p><p><span m='119348'>Not</span> <span m='119701'>a</span> <span m='120055'>big</span>
  <span m='120409'>deal,</span> <span m='120763'>but</span> <span m='121117'>little</span>
  <span m='121471'>optimizations</span> <span m='121825'>to</span> <span m='122179'>code</span>
  <span m='122533'>inside</span> <span m='122887'>a</span> <span m='123241'>loop</span>
  <span m='123595'>can</span> <span m='123949'>add</span> <span m='124303'>up</span>
  <span m='124657'>to</span> <span m='125011'>big</span> <span m='125365'>savings</span>
  <span m='125719'>in</span> <span m='126524'>a</span> <span m='127329'>long-running</span>
  <span m='128134'>program.</span> </p><p><span m='128940'>Just</span> <span m='129322'>a</span>
  <span m='129705'>quick</span> <span m='130087'>comment</span> <span m='130470'>about</span>
  <span m='130852'>another</span> <span m='131235'>common</span> <span m='131617'>iteration</span>
  <span m='132000'>statement,</span> <span m='132382'>the</span> <span m='132765'>FOR</span>
  <span m='133147'>loop.</span> </p><p><span m='133530'>The</span> <span m='133835'>FOR</span>
  <span m='134140'>loop</span> <span m='134445'>is</span> <span m='134751'>a</span>
  <span m='135056'>shorthand</span> <span m='135361'>way</span> <span m='135667'>of</span>
  <span m='135972'>expressing</span> <span m='136277'>iterations</span> <span m='136582'>where</span>
  <span m='136888'>the</span> <span m='137193'>loop</span> <span m='137498'>index</span>
  <span m='137804'>("i"</span> <span m='138109'>in</span> <span m='138414'>the</span>
  <span m='138720'>example</span> <span m='139036'>shown)</span> <span m='139353'>is</span>
  <span m='139670'>run</span> <span m='139986'>through</span> <span m='140303'>a</span>
  <span m='140620'>sequence</span> <span m='140936'>of</span> <span m='141253'>values</span>
  <span m='141570'>and</span> <span m='141886'>the</span> <span m='142203'>body</span>
  <span m='142520'>of</span> <span m='142836'>the</span> <span m='143153'>FOR</span>
  <span m='143470'>loop</span> <span m='143786'>is</span> <span m='144103'>executed</span>
  <span m='144420'>once</span> <span m='144822'>for</span> <span m='145225'>each</span>
  <span m='145627'>value</span> <span m='146030'>of</span> <span m='146432'>the</span>
  <span m='146835'>loop</span> <span m='147237'>index.</span> </p><p><span m='147640'>The</span>
  <span m='147948'>FOR</span> <span m='148257'>loop</span> <span m='148566'>can</span>
  <span m='148875'>be</span> <span m='149184'>transformed</span> <span m='149492'>into</span>
  <span m='149801'>the</span> <span m='150110'>WHILE</span> <span m='150419'>statement</span>
  <span m='150728'>shown</span> <span m='151037'>here,</span> <span m='151345'>which</span>
  <span m='151654'>can</span> <span m='151963'>then</span> <span m='152272'>be</span>
  <span m='152581'>compiled</span> <span m='152890'>using</span> <span m='153488'>the</span>
  <span m='154086'>templates</span> <span m='154684'>shown</span> <span m='155282'>above.</span>
  </p><p><span m='155880'>In</span> <span m='156242'>this</span> <span m='156604'>example,</span>
  <span m='156966'>we've</span> <span m='157328'>applied</span> <span m='157690'>our</span>
  <span m='158052'>templates</span> <span m='158415'>to</span> <span m='158777'>generate</span>
  <span m='159139'>code</span> <span m='159501'>for</span> <span m='159863'>the</span>
  <span m='160225'>iterative</span> <span m='160587'>implementation</span> <span m='160950'>of</span>
  <span m='161405'>the</span> <span m='161860'>factorial</span> <span m='162315'>function</span>
  <span m='162770'>that</span> <span m='163225'>we've</span> <span m='163680'>seen</span>
  <span m='164135'>before.</span> </p><p><span m='164590'>Look</span> <span m='164881'>through</span>
  <span m='165173'>the</span> <span m='165465'>generated</span> <span m='165757'>code</span>
  <span m='166049'>and</span> <span m='166341'>you'll</span> <span m='166633'>be</span>
  <span m='166925'>able</span> <span m='167216'>to</span> <span m='167508'>match</span>
  <span m='167800'>the</span> <span m='168092'>code</span> <span m='168384'>fragments</span>
  <span m='168676'>with</span> <span m='168968'>the</span> <span m='169260'>templates</span>
  <span m='169690'>from</span> <span m='170120'>last</span> <span m='170550'>couple</span>
  <span m='170980'>of</span> <span m='171410'>slides.</span> </p><p><span m='171840'>It's</span>
  <span m='172156'>not</span> <span m='172473'>the</span> <span m='172790'>most</span>
  <span m='173106'>efficient</span> <span m='173423'>code,</span> <span m='173740'>but</span>
  <span m='174056'>not</span> <span m='174373'>bad</span> <span m='174690'>given</span>
  <span m='175006'>the</span> <span m='175323'>simplicity</span> <span m='175640'>of</span>
  <span m='175956'>the</span> <span m='176273'>recursive-descent</span> <span m='176590'>approach</span>
  <span m='177266'>for</span> <span m='177942'>compiling</span> <span m='178618'>high-level</span>
  <span m='179294'>programs.</span> </p><p><span m='179970'>It's</span> <span m='180385'>a</span>
  <span m='180801'>simple</span> <span m='181217'>matter</span> <span m='181632'>to</span>
  <span m='182048'>modify</span> <span m='182464'>the</span> <span m='182880'>recursive-descent</span>
  <span m='183295'>process</span> <span m='183711'>to</span> <span m='184127'>accommodate</span>
  <span m='184542'>variable</span> <span m='184958'>values</span> <span m='185374'>that</span>
  <span m='185790'>are</span> <span m='186256'>stored</span> <span m='186722'>in</span>
  <span m='187188'>dedicated</span> <span m='187654'>registers</span> <span m='188120'>rather</span>
  <span m='188586'>than</span> <span m='189052'>in</span> <span m='189518'>main</span>
  <span m='189984'>memory.</span> </p><p><span m='190450'>Optimizing</span> <span
  m='190813'>compilers</span> <span m='191176'>are</span> <span m='191539'>quite</span>
  <span m='191902'>good</span> <span m='192265'>at</span> <span m='192628'>identifying</span>
  <span m='192991'>opportunities</span> <span m='193354'>to</span> <span m='193717'>keep</span>
  <span m='194080'>values</span> <span m='194443'>in</span> <span m='194806'>registers</span>
  <span m='195170'>and</span> <span m='195628'>hence</span> <span m='196086'>avoid</span>
  <span m='196544'>the</span> <span m='197002'>LD</span> <span m='197460'>and</span>
  <span m='197918'>ST</span> <span m='198376'>operations</span> <span m='198834'>needed</span>
  <span m='199292'>to</span> <span m='199750'>access</span> <span m='200208'>values</span>
  <span m='200666'>in</span> <span m='201124'>main</span> <span m='201582'>memory.</span>
  </p><p><span m='202040'>Using</span> <span m='202337'>this</span> <span m='202634'>simple</span>
  <span m='202931'>optimization,</span> <span m='203228'>the</span> <span m='203525'>number</span>
  <span m='203822'>of</span> <span m='204120'>instructions</span> <span m='204417'>in</span>
  <span m='204714'>the</span> <span m='205011'>loop</span> <span m='205308'>has</span>
  <span m='205605'>gone</span> <span m='205902'>from</span> <span m='206200'>10</span>
  <span m='206740'>down</span> <span m='207280'>to</span> <span m='207820'>4.</span>
  </p><p><span m='208360'>Now</span> <span m='208882'>the</span> <span m='209405'>generated</span>
  <span m='209927'>code</span> <span m='210450'>is</span> <span m='210972'>looking</span>
  <span m='211495'>pretty</span> <span m='212017'>good!</span> </p><p><span m='212540'>But</span>
  <span m='212940'>rather</span> <span m='213341'>than</span> <span m='213742'>keep</span>
  <span m='214143'>tweaking</span> <span m='214544'>the</span> <span m='214945'>recursive-descent</span>
  <span m='215346'>approach,</span> <span m='215747'>let's</span> <span m='216148'>stop</span>
  <span m='216549'>here.</span> </p><p><span m='216950'>In</span> <span m='217208'>the</span>
  <span m='217466'>next</span> <span m='217724'>segment,</span> <span m='217982'>we'll</span>
  <span m='218240'>see</span> <span m='218498'>how</span> <span m='218756'>modern</span>
  <span m='219014'>compilers</span> <span m='219272'>take</span> <span m='219530'>a</span>
  <span m='219788'>more</span> <span m='220046'>general</span> <span m='220304'>approach</span>
  <span m='220562'>to</span> <span m='220820'>generating</span> <span m='221520'>code.</span>
  </p><p><span m='222220'>Still</span> <span m='222537'>though,</span> <span m='222854'>the</span>
  <span m='223171'>first</span> <span m='223488'>time</span> <span m='223805'>I</span>
  <span m='224122'>learned</span> <span m='224439'>about</span> <span m='224756'>recursive</span>
  <span m='225073'>descent,</span> <span m='225390'>I</span> <span m='225707'>ran</span>
  <span m='226024'>home</span> <span m='226341'>to</span> <span m='226658'>write</span>
  <span m='226975'>a</span> <span m='227292'>simple</span> <span m='227610'>implementation</span>
  <span m='227999'>and</span> <span m='228388'>marveled</span> <span m='228777'>at</span>
  <span m='229166'>having</span> <span m='229555'>authored</span> <span m='229945'>my</span>
  <span m='230334'>own</span> <span m='230723'>compiler</span> <span m='231112'>in</span>
  <span m='231501'>an</span> <span m='231890'>afternoon!</span> </p>
type: course
uid: 1861426cb17105587df01a7fff7d5555

---
None