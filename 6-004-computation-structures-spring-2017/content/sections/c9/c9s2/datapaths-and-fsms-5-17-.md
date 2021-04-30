---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: oi1Jb-dGsWU
  parent_uid: a7d2318fb25219b6544f2cfffca6a69f
  title: Video-YouTube-Stream
  type: Video
  uid: 8bddc0ec49d1b2035e5b0ad98b9bf796
- id: 3Play-3Play YouTube id-Stream
  media_location: oi1Jb-dGsWU
  parent_uid: a7d2318fb25219b6544f2cfffca6a69f
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: c4e6e604b41ef0ccfe05e8cc798e0d2c
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/oi1Jb-dGsWU/default.jpg
  parent_uid: a7d2318fb25219b6544f2cfffca6a69f
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 4d7035d9ef19abdde6653e38b76dd87c
- id: oi1Jb-dGsWU.srt
  parent_uid: a7d2318fb25219b6544f2cfffca6a69f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/datapaths-and-fsms-5-17-/oi1Jb-dGsWU.srt
  title: 3play caption file
  type: null
  uid: c2d8b58e1b44d87c4e4fafbb168526f7
- id: oi1Jb-dGsWU.pdf
  parent_uid: a7d2318fb25219b6544f2cfffca6a69f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/datapaths-and-fsms-5-17-/oi1Jb-dGsWU.pdf
  title: 3play pdf file
  type: null
  uid: 29f8737be30539ace4762d3d8de93d80
- id: Caption-3Play YouTube id-SRT
  parent_uid: a7d2318fb25219b6544f2cfffca6a69f
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 392f85e52de09f9de6a6391ac520bde6
- id: Transcript-3Play YouTube id-PDF
  parent_uid: a7d2318fb25219b6544f2cfffca6a69f
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 329da96a88a560c7b9eb397e580ed7d4
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_09-02-01_300k.mp4
  parent_uid: a7d2318fb25219b6544f2cfffca6a69f
  title: Video-Internet Archive-MP4
  type: Video
  uid: b16d39fc0e81c5dc28b18c5368ef3915
inline_embed_id: 51596730datapathsandfsms51787480413
layout: video
order_index: null
parent_uid: 5c4d3e65eb78c4a8ad529266007c5239
related_resources_text: ''
short_url: datapaths-and-fsms-5-17-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/datapaths-and-fsms-5-17-
template_type: Embed
title: Datapaths and FSMs (5:17)
transcript: <p><span m='470'>Welcome</span> <span m='1055'>to</span> <span m='1640'>Part</span>
  <span m='2225'>2</span> <span m='2810'>of</span> <span m='3395'>6.004x!</span> </p><p><span
  m='3980'>In</span> <span m='4232'>this</span> <span m='4485'>part</span> <span m='4738'>of</span>
  <span m='4991'>the</span> <span m='5244'>course,</span> <span m='5497'>we</span>
  <span m='5750'>turn</span> <span m='6003'>our</span> <span m='6256'>attention</span>
  <span m='6509'>to</span> <span m='6762'>the</span> <span m='7015'>design</span>
  <span m='7268'>and</span> <span m='7521'>implementation</span> <span m='7774'>of</span>
  <span m='8027'>digital</span> <span m='8280'>systems</span> <span m='8738'>that</span>
  <span m='9196'>can</span> <span m='9655'>perform</span> <span m='10113'>useful</span>
  <span m='10571'>computations</span> <span m='11030'>on</span> <span m='11488'>different</span>
  <span m='11946'>types</span> <span m='12405'>of</span> <span m='12863'>binary</span>
  <span m='13321'>data.</span> </p><p><span m='13780'>We'll</span> <span m='14038'>come</span>
  <span m='14297'>up</span> <span m='14556'>with</span> <span m='14814'>a</span> <span
  m='15073'>general-purpose</span> <span m='15332'>design</span> <span m='15590'>for</span>
  <span m='15849'>these</span> <span m='16108'>systems,</span> <span m='16366'>we</span>
  <span m='16625'>which</span> <span m='16884'>we</span> <span m='17142'>call</span>
  <span m='17401'>"computers",</span> <span m='17660'>so</span> <span m='18056'>that</span>
  <span m='18453'>they</span> <span m='18850'>can</span> <span m='19247'>serve</span>
  <span m='19644'>as</span> <span m='20041'>useful</span> <span m='20438'>tools</span>
  <span m='20835'>in</span> <span m='21232'>many</span> <span m='21629'>diverse</span>
  <span m='22026'>application</span> <span m='22423'>areas.</span> </p><p><span m='22820'>Computers</span>
  <span m='23136'>were</span> <span m='23452'>first</span> <span m='23768'>used</span>
  <span m='24084'>to</span> <span m='24400'>perform</span> <span m='24716'>numeric</span>
  <span m='25033'>calculations</span> <span m='25349'>in</span> <span m='25665'>science</span>
  <span m='25981'>and</span> <span m='26297'>engineering,</span> <span m='26613'>but</span>
  <span m='26930'>today</span> <span m='27278'>they</span> <span m='27627'>are</span>
  <span m='27975'>used</span> <span m='28324'>as</span> <span m='28673'>the</span>
  <span m='29021'>central</span> <span m='29370'>control</span> <span m='29718'>element</span>
  <span m='30067'>in</span> <span m='30416'>any</span> <span m='30764'>system</span>
  <span m='31113'>where</span> <span m='31461'>complex</span> <span m='31810'>behavior</span>
  <span m='32159'>is</span> <span m='33234'>required.</span> </p><p><span m='34310'>We</span>
  <span m='34551'>have</span> <span m='34793'>a</span> <span m='35034'>lot</span>
  <span m='35276'>to</span> <span m='35517'>do</span> <span m='35759'>in</span> <span
  m='36000'>this</span> <span m='36242'>chapter,</span> <span m='36483'>so</span>
  <span m='36725'>let's</span> <span m='36966'>get</span> <span m='37208'>started!</span>
  </p><p><span m='37450'>Suppose</span> <span m='37739'>we</span> <span m='38028'>want</span>
  <span m='38318'>to</span> <span m='38607'>design</span> <span m='38896'>a</span>
  <span m='39186'>system</span> <span m='39475'>to</span> <span m='39765'>compute</span>
  <span m='40054'>the</span> <span m='40343'>factorial</span> <span m='40633'>function</span>
  <span m='40922'>on</span> <span m='41211'>some</span> <span m='41501'>numeric</span>
  <span m='41790'>argument</span> <span m='42080'>N.</span> <span m='42530'>N!</span>
  <span m='42981'>is</span> <span m='43432'>defined</span> <span m='43883'>as</span>
  <span m='44334'>the</span> <span m='44785'>product</span> <span m='45236'>of</span>
  <span m='45687'>N</span> <span m='46138'>times</span> <span m='46589'>N-1</span>
  <span m='47040'>times</span> <span m='47493'>N-2,</span> <span m='47947'>and</span>
  <span m='48401'>so</span> <span m='48855'>on</span> <span m='49308'>down</span>
  <span m='49762'>to</span> <span m='50216'>1.</span> </p><p><span m='50670'>We</span>
  <span m='50968'>can</span> <span m='51267'>use</span> <span m='51566'>a</span> <span
  m='51864'>programming</span> <span m='52163'>language</span> <span m='52462'>like</span>
  <span m='52760'>C</span> <span m='53059'>to</span> <span m='53358'>describe</span>
  <span m='53656'>the</span> <span m='53955'>sequence</span> <span m='54254'>of</span>
  <span m='54552'>operations</span> <span m='54851'>necessary</span> <span m='55150'>to</span>
  <span m='55590'>perform</span> <span m='56030'>the</span> <span m='56470'>factorial</span>
  <span m='56910'>computation.</span> </p><p><span m='57350'>In</span> <span m='57636'>this</span>
  <span m='57922'>program</span> <span m='58208'>there</span> <span m='58494'>are</span>
  <span m='58780'>two</span> <span m='59066'>variables,</span> <span m='59352'>"a"</span>
  <span m='59638'>and</span> <span m='59924'>"b".</span> </p><p><span m='60210'>"a"</span>
  <span m='60511'>is</span> <span m='60813'>used</span> <span m='61115'>to</span>
  <span m='61416'>accumulate</span> <span m='61718'>the</span> <span m='62020'>answer</span>
  <span m='62321'>as</span> <span m='62623'>we</span> <span m='62925'>compute</span>
  <span m='63226'>it</span> <span m='63528'>step-by-step.</span> </p><p><span m='63830'>"b"</span>
  <span m='64180'>is</span> <span m='64530'>used</span> <span m='64880'>to</span>
  <span m='65230'>hold</span> <span m='65580'>the</span> <span m='65930'>next</span>
  <span m='66280'>value</span> <span m='66630'>we</span> <span m='66980'>need</span>
  <span m='67330'>to</span> <span m='67680'>multiply.</span> </p><p><span m='68030'>"b"</span>
  <span m='68380'>starts</span> <span m='68730'>with</span> <span m='69080'>the</span>
  <span m='69430'>value</span> <span m='69780'>of</span> <span m='70130'>the</span>
  <span m='70480'>numeric</span> <span m='70830'>argument</span> <span m='71180'>N.</span>
  </p><p><span m='71530'>The</span> <span m='71784'>DO</span> <span m='72038'>loop</span>
  <span m='72293'>is</span> <span m='72547'>where</span> <span m='72802'>the</span>
  <span m='73056'>work</span> <span m='73311'>gets</span> <span m='73565'>done:</span>
  <span m='73820'>on</span> <span m='74074'>each</span> <span m='74328'>loop</span>
  <span m='74583'>iteration</span> <span m='74837'>we</span> <span m='75092'>perform</span>
  <span m='75346'>one</span> <span m='75601'>of</span> <span m='75855'>the</span>
  <span m='76110'>multiplies</span> <span m='76458'>from</span> <span m='76807'>the</span>
  <span m='77155'>factorial</span> <span m='77504'>formula,</span> <span m='77852'>updating</span>
  <span m='78201'>the</span> <span m='78550'>value</span> <span m='78898'>of</span>
  <span m='79247'>the</span> <span m='79595'>accumulator</span> <span m='79944'>"a"</span>
  <span m='80292'>with</span> <span m='80641'>the</span> <span m='80990'>result,</span>
  <span m='81541'>then</span> <span m='82093'>decrementing</span> <span m='82645'>"b"</span>
  <span m='83197'>in</span> <span m='83749'>preparation</span> <span m='84300'>for</span>
  <span m='84852'>the</span> <span m='85404'>next</span> <span m='85956'>loop</span>
  <span m='86508'>iteration.</span> </p><p><span m='87060'>If</span> <span m='87324'>we</span>
  <span m='87589'>want</span> <span m='87854'>to</span> <span m='88119'>implement</span>
  <span m='88384'>a</span> <span m='88649'>digital</span> <span m='88914'>system</span>
  <span m='89179'>that</span> <span m='89444'>performs</span> <span m='89709'>this</span>
  <span m='89974'>sequence</span> <span m='90239'>of</span> <span m='90504'>operations,</span>
  <span m='90769'>it</span> <span m='91034'>makes</span> <span m='91299'>sense</span>
  <span m='91685'>to</span> <span m='92071'>use</span> <span m='92457'>sequential</span>
  <span m='92843'>logic!</span> </p><p><span m='93229'>Here's</span> <span m='93581'>the</span>
  <span m='93934'>state</span> <span m='94286'>transition</span> <span m='94639'>diagram</span>
  <span m='94991'>for</span> <span m='95344'>a</span> <span m='95697'>high-level</span>
  <span m='96049'>finite-state</span> <span m='96402'>machine</span> <span m='96754'>designed</span>
  <span m='97107'>to</span> <span m='97460'>perform</span> <span m='97971'>the</span>
  <span m='98482'>necessary</span> <span m='98993'>computations</span> <span m='99504'>in</span>
  <span m='100015'>the</span> <span m='100526'>desired</span> <span m='101037'>order.</span>
  </p><p><span m='101549'>We</span> <span m='101888'>call</span> <span m='102227'>this</span>
  <span m='102567'>a</span> <span m='102906'>high-level</span> <span m='103245'>FSM</span>
  <span m='103585'>since</span> <span m='103924'>the</span> <span m='104264'>"outputs"</span>
  <span m='104603'>of</span> <span m='104942'>each</span> <span m='105282'>state</span>
  <span m='105621'>are</span> <span m='105961'>more</span> <span m='106300'>than</span>
  <span m='106639'>simple</span> <span m='106979'>logic</span> <span m='107318'>levels.</span>
  </p><p><span m='107658'>They</span> <span m='108032'>are</span> <span m='108406'>formulas</span>
  <span m='108781'>indicating</span> <span m='109155'>operations</span> <span m='109529'>to</span>
  <span m='109904'>be</span> <span m='110278'>performed</span> <span m='110652'>on</span>
  <span m='111027'>source</span> <span m='111401'>variables,</span> <span m='111775'>storing</span>
  <span m='112150'>the</span> <span m='112720'>result</span> <span m='113290'>in</span>
  <span m='113860'>a</span> <span m='114430'>destination</span> <span m='115000'>variable.</span>
  </p><p><span m='115570'>The</span> <span m='115882'>sequence</span> <span m='116195'>of</span>
  <span m='116508'>states</span> <span m='116820'>visited</span> <span m='117133'>while</span>
  <span m='117446'>the</span> <span m='117758'>FSM</span> <span m='118071'>is</span>
  <span m='118384'>running</span> <span m='118696'>mirrors</span> <span m='119009'>the</span>
  <span m='119322'>steps</span> <span m='119634'>performed</span> <span m='119947'>by</span>
  <span m='120260'>the</span> <span m='120664'>execution</span> <span m='121069'>of</span>
  <span m='121474'>the</span> <span m='121879'>C</span> <span m='122284'>program.</span>
  </p><p><span m='122689'>The</span> <span m='122960'>FSM</span> <span m='123232'>repeats</span>
  <span m='123504'>the</span> <span m='123776'>LOOP</span> <span m='124048'>state</span>
  <span m='124320'>until</span> <span m='124592'>the</span> <span m='124864'>new</span>
  <span m='125136'>value</span> <span m='125408'>to</span> <span m='125680'>be</span>
  <span m='125952'>stored</span> <span m='126224'>in</span> <span m='126496'>"b"</span>
  <span m='126768'>is</span> <span m='127040'>equal</span> <span m='127312'>to</span>
  <span m='127584'>0,</span> <span m='127856'>at</span> <span m='128128'>which</span>
  <span m='128532'>point</span> <span m='128936'>the</span> <span m='129340'>FSM</span>
  <span m='129744'>transitions</span> <span m='130149'>into</span> <span m='130553'>the</span>
  <span m='130957'>final</span> <span m='131361'>DONE</span> <span m='131765'>state.</span>
  </p><p><span m='132170'>The</span> <span m='132536'>high-level</span> <span m='132902'>FSM</span>
  <span m='133269'>is</span> <span m='133635'>useful</span> <span m='134002'>when</span>
  <span m='134368'>designing</span> <span m='134735'>the</span> <span m='135101'>circuitry</span>
  <span m='135467'>necessary</span> <span m='135834'>to</span> <span m='136200'>implement</span>
  <span m='136567'>the</span> <span m='136933'>desired</span> <span m='137300'>computation</span>
  <span m='137589'>using</span> <span m='137879'>our</span> <span m='138169'>digital</span>
  <span m='138459'>logic</span> <span m='138749'>building</span> <span m='139039'>blocks.</span>
  </p><p><span m='139329'>We'll</span> <span m='139755'>use</span> <span m='140181'>32-bit</span>
  <span m='140608'>D-registers</span> <span m='141034'>to</span> <span m='141461'>hold</span>
  <span m='141887'>the</span> <span m='142314'>"a"</span> <span m='142740'>and</span>
  <span m='143167'>"b"</span> <span m='143593'>values.</span> </p><p><span m='144020'>And</span>
  <span m='144336'>we'll</span> <span m='144653'>need</span> <span m='144970'>a</span>
  <span m='145287'>2-bit</span> <span m='145604'>D-register</span> <span m='145921'>to</span>
  <span m='146238'>hold</span> <span m='146555'>the</span> <span m='146871'>2-bit</span>
  <span m='147188'>encoding</span> <span m='147505'>of</span> <span m='147822'>the</span>
  <span m='148139'>current</span> <span m='148456'>state,</span> <span m='148773'>i.e.,</span>
  <span m='149090'>the</span> <span m='149503'>encoding</span> <span m='149917'>for</span>
  <span m='150331'>either</span> <span m='150745'>START,</span> <span m='151158'>LOOP</span>
  <span m='151572'>or</span> <span m='151986'>DONE.</span> </p><p><span m='152400'>We'll</span>
  <span m='152828'>include</span> <span m='153257'>logic</span> <span m='153685'>to</span>
  <span m='154114'>compute</span> <span m='154542'>the</span> <span m='154971'>inputs</span>
  <span m='155400'>required</span> <span m='155828'>to</span> <span m='156257'>implement</span>
  <span m='156685'>the</span> <span m='157114'>correct</span> <span m='157542'>state</span>
  <span m='157971'>transitions.</span> </p><p><span m='158400'>In</span> <span m='158654'>this</span>
  <span m='158909'>case,</span> <span m='159164'>we</span> <span m='159418'>need</span>
  <span m='159673'>to</span> <span m='159928'>know</span> <span m='160182'>if</span>
  <span m='160437'>the</span> <span m='160692'>new</span> <span m='160947'>value</span>
  <span m='161201'>for</span> <span m='161456'>"b"</span> <span m='161711'>is</span>
  <span m='161965'>zero</span> <span m='162220'>or</span> <span m='162475'>not.</span>
  </p><p><span m='162730'>And,</span> <span m='163105'>finally,</span> <span m='163481'>we'll</span>
  <span m='163857'>need</span> <span m='164232'>logic</span> <span m='164608'>to</span>
  <span m='164984'>perform</span> <span m='165360'>multiply</span> <span m='165735'>and</span>
  <span m='166111'>decrement,</span> <span m='166487'>and</span> <span m='166862'>to</span>
  <span m='167238'>select</span> <span m='167614'>which</span> <span m='167990'>value</span>
  <span m='168296'>should</span> <span m='168602'>be</span> <span m='168909'>loaded</span>
  <span m='169215'>into</span> <span m='169522'>the</span> <span m='169828'>"a"</span>
  <span m='170135'>and</span> <span m='170441'>"b"</span> <span m='170748'>registers</span>
  <span m='171054'>at</span> <span m='171361'>the</span> <span m='171667'>end</span>
  <span m='171974'>of</span> <span m='172280'>each</span> <span m='172587'>FSM</span>
  <span m='172893'>cycle.</span> </p><p><span m='173200'>Let's</span> <span m='173497'>start</span>
  <span m='173794'>by</span> <span m='174092'>designing</span> <span m='174389'>the</span>
  <span m='174687'>logic</span> <span m='174984'>that</span> <span m='175282'>implements</span>
  <span m='175579'>the</span> <span m='175876'>desired</span> <span m='176174'>computations</span>
  <span m='176471'>-</span> <span m='176769'>we</span> <span m='177066'>call</span>
  <span m='177364'>this</span> <span m='177661'>part</span> <span m='177959'>of</span>
  <span m='178475'>the</span> <span m='178991'>logic</span> <span m='179507'>the</span>
  <span m='180023'>"datapath".</span> </p><p><span m='180540'>First</span> <span m='180874'>we'll</span>
  <span m='181209'>need</span> <span m='181543'>two</span> <span m='181878'>32-bit</span>
  <span m='182213'>D-registers</span> <span m='182547'>to</span> <span m='182882'>hold</span>
  <span m='183216'>the</span> <span m='183551'>"a"</span> <span m='183886'>and</span>
  <span m='184220'>"b"</span> <span m='184555'>values.</span> </p><p><span m='184890'>Then</span>
  <span m='185148'>we'll</span> <span m='185407'>draw</span> <span m='185666'>the</span>
  <span m='185924'>combinational</span> <span m='186183'>logic</span> <span m='186442'>blocks</span>
  <span m='186700'>needed</span> <span m='186959'>to</span> <span m='187218'>compute</span>
  <span m='187476'>the</span> <span m='187735'>values</span> <span m='187994'>to</span>
  <span m='188252'>be</span> <span m='188511'>stored</span> <span m='188770'>in</span>
  <span m='189190'>those</span> <span m='189610'>registers.</span> </p><p><span m='190030'>In</span>
  <span m='190312'>the</span> <span m='190594'>START</span> <span m='190876'>state</span>
  <span m='191158'>,</span> <span m='191440'>we</span> <span m='191722'>need</span>
  <span m='192004'>the</span> <span m='192286'>constant</span> <span m='192568'>1</span>
  <span m='192851'>to</span> <span m='193133'>load</span> <span m='193415'>into</span>
  <span m='193697'>the</span> <span m='193979'>"a"</span> <span m='194261'>register</span>
  <span m='194543'>and</span> <span m='194825'>the</span> <span m='195107'>constant</span>
  <span m='195390'>N</span> <span m='195722'>to</span> <span m='196055'>load</span>
  <span m='196388'>into</span> <span m='196721'>the</span> <span m='197054'>"b"</span>
  <span m='197387'>register.</span> </p><p><span m='197720'>In</span> <span m='198143'>the</span>
  <span m='198567'>LOOP</span> <span m='198991'>state,</span> <span m='199414'>we</span>
  <span m='199838'>need</span> <span m='200262'>to</span> <span m='200685'>compute</span>
  <span m='201109'>a*b</span> <span m='201533'>for</span> <span m='201956'>the</span>
  <span m='202380'>"a"</span> <span m='202804'>register</span> <span m='203227'>and</span>
  <span m='203651'>b-1</span> <span m='204075'>for</span> <span m='204498'>the</span>
  <span m='204922'>"b"</span> <span m='205346'>register.</span> </p><p><span m='205770'>Finally,</span>
  <span m='206016'>in</span> <span m='206263'>the</span> <span m='206510'>DONE</span>
  <span m='206756'>state</span> <span m='207003'>,</span> <span m='207250'>we</span>
  <span m='207496'>need</span> <span m='207743'>to</span> <span m='207990'>be</span>
  <span m='208236'>able</span> <span m='208483'>to</span> <span m='208730'>reload</span>
  <span m='208976'>each</span> <span m='209223'>register</span> <span m='209470'>with</span>
  <span m='209716'>its</span> <span m='209963'>current</span> <span m='210210'>value.</span>
  </p><p><span m='212190'>We'll</span> <span m='212493'>use</span> <span m='212797'>multiplexers</span>
  <span m='213101'>to</span> <span m='213405'>select</span> <span m='213708'>the</span>
  <span m='214012'>appropriate</span> <span m='214316'>value</span> <span m='214620'>to</span>
  <span m='214923'>load</span> <span m='215227'>into</span> <span m='215531'>each</span>
  <span m='215835'>of</span> <span m='216138'>the</span> <span m='216442'>data</span>
  <span m='216746'>registers.</span> </p><p><span m='217050'>These</span> <span m='217415'>multiplexers</span>
  <span m='217780'>are</span> <span m='218145'>controlled</span> <span m='218510'>by</span>
  <span m='218875'>2-bit</span> <span m='219240'>select</span> <span m='219605'>signals</span>
  <span m='219970'>that</span> <span m='220335'>choose</span> <span m='220700'>which</span>
  <span m='221065'>of</span> <span m='221430'>the</span> <span m='221795'>three</span>
  <span m='222160'>32-bit</span> <span m='222550'>input</span> <span m='222941'>values</span>
  <span m='223331'>will</span> <span m='223722'>be</span> <span m='224113'>the</span>
  <span m='224503'>32-bit</span> <span m='224894'>value</span> <span m='225285'>to</span>
  <span m='225675'>be</span> <span m='226066'>loaded</span> <span m='226457'>into</span>
  <span m='226847'>the</span> <span m='227238'>register.</span> </p><p><span m='227629'>So</span>
  <span m='227991'>by</span> <span m='228353'>choosing</span> <span m='228715'>the</span>
  <span m='229077'>appropriate</span> <span m='229439'>values</span> <span m='229801'>for</span>
  <span m='230163'>WASEL</span> <span m='230525'>and</span> <span m='230887'>WBSEL,</span>
  <span m='231249'>we</span> <span m='231611'>can</span> <span m='231973'>make</span>
  <span m='232335'>the</span> <span m='232697'>datapath</span> <span m='233060'>compute</span>
  <span m='233495'>the</span> <span m='233930'>desired</span> <span m='234366'>values</span>
  <span m='234801'>at</span> <span m='235236'>each</span> <span m='235672'>step</span>
  <span m='236107'>in</span> <span m='236542'>the</span> <span m='236978'>FSM's</span>
  <span m='237413'>operation.</span> </p><p><span m='237849'>Next</span> <span m='238233'>we'll</span>
  <span m='238618'>add</span> <span m='239002'>the</span> <span m='239387'>combinational</span>
  <span m='239772'>logic</span> <span m='240156'>needed</span> <span m='240541'>to</span>
  <span m='240925'>control</span> <span m='241310'>the</span> <span m='241695'>FSM's</span>
  <span m='242079'>state</span> <span m='242464'>transitions.</span> </p><p><span
  m='242849'>In</span> <span m='243107'>this</span> <span m='243366'>case,</span>
  <span m='243624'>we</span> <span m='243883'>need</span> <span m='244141'>to</span>
  <span m='244400'>test</span> <span m='244658'>if</span> <span m='244917'>the</span>
  <span m='245175'>new</span> <span m='245434'>value</span> <span m='245692'>to</span>
  <span m='245951'>be</span> <span m='246209'>loaded</span> <span m='246468'>into</span>
  <span m='246726'>the</span> <span m='246985'>"b"</span> <span m='247243'>register</span>
  <span m='247502'>is</span> <span m='247760'>zero.</span> </p><p><span m='248019'>The</span>
  <span m='248353'>Z</span> <span m='248687'>signal</span> <span m='249022'>from</span>
  <span m='249356'>the</span> <span m='249691'>datapath</span> <span m='250025'>will</span>
  <span m='250360'>be</span> <span m='250694'>1</span> <span m='251028'>if</span>
  <span m='251363'>that's</span> <span m='251697'>the</span> <span m='252032'>case</span>
  <span m='252366'>and</span> <span m='252701'>0</span> <span m='253035'>otherwise.</span>
  </p><p><span m='253370'>Now</span> <span m='253673'>we're</span> <span m='253977'>all</span>
  <span m='254281'>set</span> <span m='254585'>to</span> <span m='254889'>add</span>
  <span m='255193'>the</span> <span m='255496'>hardware</span> <span m='255800'>for</span>
  <span m='256104'>the</span> <span m='256408'>control</span> <span m='256712'>FSM,</span>
  <span m='257016'>which</span> <span m='257319'>has</span> <span m='257623'>one</span>
  <span m='257927'>input</span> <span m='258231'>(Z)</span> <span m='258535'>from</span>
  <span m='258839'>the</span> <span m='259370'>datapath</span> <span m='259902'>and</span>
  <span m='260433'>generates</span> <span m='260965'>two</span> <span m='261496'>2-bit</span>
  <span m='262028'>outputs</span> <span m='262559'>(WASEL</span> <span m='263091'>and</span>
  <span m='263622'>WBSEL)</span> <span m='264154'>to</span> <span m='264685'>control</span>
  <span m='265217'>the</span> <span m='265748'>datapath.</span> </p><p><span m='266280'>Here's</span>
  <span m='266687'>the</span> <span m='267095'>truth</span> <span m='267503'>table</span>
  <span m='267911'>for</span> <span m='268318'>the</span> <span m='268726'>FSM's</span>
  <span m='269134'>combinational</span> <span m='269542'>logic.</span> </p><p><span
  m='269950'>S</span> <span m='270319'>is</span> <span m='270688'>the</span> <span
  m='271058'>current</span> <span m='271427'>state,</span> <span m='271796'>encoded</span>
  <span m='272166'>as</span> <span m='272535'>a</span> <span m='272905'>2-bit</span>
  <span m='273274'>value,</span> <span m='273643'>and</span> <span m='274013'>S'</span>
  <span m='274382'>is</span> <span m='274751'>the</span> <span m='275121'>next</span>
  <span m='275490'>state.</span> </p><p><span m='275860'>Using</span> <span m='276128'>our</span>
  <span m='276397'>skills</span> <span m='276666'>from</span> <span m='276935'>Part</span>
  <span m='277204'>1</span> <span m='277473'>of</span> <span m='277742'>the</span>
  <span m='278011'>course,</span> <span m='278280'>we're</span> <span m='278548'>ready</span>
  <span m='278817'>to</span> <span m='279086'>draw</span> <span m='279355'>a</span>
  <span m='279624'>schematic</span> <span m='279893'>for</span> <span m='280162'>the</span>
  <span m='280431'>system!</span> </p><p><span m='280700'>We</span> <span m='281030'>know</span>
  <span m='281361'>how</span> <span m='281692'>to</span> <span m='282023'>design</span>
  <span m='282354'>the</span> <span m='282685'>appropriate</span> <span m='283016'>multiplier</span>
  <span m='283347'>and</span> <span m='283678'>decrement</span> <span m='284009'>circuitry.</span>
  </p><p><span m='284340'>And</span> <span m='284730'>we</span> <span m='285121'>can</span>
  <span m='285512'>use</span> <span m='285903'>our</span> <span m='286294'>standard</span>
  <span m='286685'>register-and-ROM</span> <span m='287075'>implementation</span>
  <span m='287466'>for</span> <span m='287857'>the</span> <span m='288248'>control</span>
  <span m='288639'>FSM.</span> </p><p><span m='289030'>The</span> <span m='289251'>Z</span>
  <span m='289472'>signal</span> <span m='289693'>from</span> <span m='289914'>the</span>
  <span m='290135'>datapath</span> <span m='290356'>is</span> <span m='290577'>combined</span>
  <span m='290798'>with</span> <span m='291020'>the</span> <span m='291241'>2</span>
  <span m='291462'>bits</span> <span m='291683'>of</span> <span m='291904'>current</span>
  <span m='292125'>state</span> <span m='292346'>to</span> <span m='292567'>form</span>
  <span m='292788'>the</span> <span m='293010'>3</span> <span m='293491'>inputs</span>
  <span m='293973'>to</span> <span m='294455'>the</span> <span m='294937'>combinational</span>
  <span m='295419'>logic,</span> <span m='295901'>in</span> <span m='296383'>this</span>
  <span m='296865'>case</span> <span m='297346'>realized</span> <span m='297828'>by</span>
  <span m='298310'>a</span> <span m='298792'>read-only</span> <span m='299274'>memory</span>
  <span m='299756'>with</span> <span m='300238'>2^3=8</span> <span m='300720'>locations.</span>
  </p><p><span m='302610'>Each</span> <span m='302985'>ROM</span> <span m='303361'>location</span>
  <span m='303737'>has</span> <span m='304113'>the</span> <span m='304489'>appropriate</span>
  <span m='304865'>values</span> <span m='305241'>for</span> <span m='305617'>the</span>
  <span m='305992'>6</span> <span m='306368'>output</span> <span m='306744'>bits:</span>
  <span m='307120'>2</span> <span m='307496'>bits</span> <span m='307872'>each</span>
  <span m='308248'>for</span> <span m='308624'>WASEL,</span> <span m='309000'>WBSEL,</span>
  <span m='309647'>and</span> <span m='310295'>next</span> <span m='310942'>state.</span>
  </p><p><span m='311590'>The</span> <span m='311856'>table</span> <span m='312123'>on</span>
  <span m='312390'>the</span> <span m='312657'>right</span> <span m='312924'>shows</span>
  <span m='313191'>the</span> <span m='313458'>ROM</span> <span m='313725'>contents,</span>
  <span m='313991'>which</span> <span m='314258'>are</span> <span m='314525'>easily</span>
  <span m='314792'>determined</span> <span m='315059'>from</span> <span m='315326'>the</span>
  <span m='315593'>table</span> <span m='315860'>on</span> <span m='316142'>the</span>
  <span m='316425'>previous</span> <span m='316707'>slide.</span> </p>
type: course
uid: a7d2318fb25219b6544f2cfffca6a69f

---
None