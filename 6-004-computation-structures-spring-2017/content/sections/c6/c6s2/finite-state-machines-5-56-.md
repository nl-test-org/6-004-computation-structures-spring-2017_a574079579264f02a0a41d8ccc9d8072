---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 5mJd--JCwBI
  parent_uid: 84502f44164a9ce08e5cbc115765560f
  title: Video-YouTube-Stream
  type: Video
  uid: 1bbb4835a53a4b491ac1ca6ff3ddc99e
- id: 3Play-3Play YouTube id-Stream
  media_location: 5mJd--JCwBI
  parent_uid: 84502f44164a9ce08e5cbc115765560f
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 2aedb7ef8a673105e2d47603118eb5bb
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/5mJd--JCwBI/default.jpg
  parent_uid: 84502f44164a9ce08e5cbc115765560f
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 33385f86403f6cce6abc389a2d9ecc5f
- id: 5mJd--JCwBI.srt
  parent_uid: 84502f44164a9ce08e5cbc115765560f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/finite-state-machines-5-56-/5mJd--JCwBI.srt
  title: 3play caption file
  type: null
  uid: f150d811d7eec3a0ef0c485ad9f932c0
- id: 5mJd--JCwBI.pdf
  parent_uid: 84502f44164a9ce08e5cbc115765560f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/finite-state-machines-5-56-/5mJd--JCwBI.pdf
  title: 3play pdf file
  type: null
  uid: 9de141eaa197ee38a3678587758df53e
- id: Caption-3Play YouTube id-SRT
  parent_uid: 84502f44164a9ce08e5cbc115765560f
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 0d08c6ce546655ceab48b1ce55a1a8f7
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 84502f44164a9ce08e5cbc115765560f
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: b60aca58ab06fde5b9b3d94be96ef43b
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_06-02-01_300k.mp4
  parent_uid: 84502f44164a9ce08e5cbc115765560f
  title: Video-Internet Archive-MP4
  type: Video
  uid: c2504fe539e9c83b2a3d2325fad939f2
inline_embed_id: 91496716finitestatemachines55648080827
layout: video
order_index: null
parent_uid: 3ea8e9cb09c53d244c08c798e88363f8
related_resources_text: ''
short_url: finite-state-machines-5-56-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/finite-state-machines-5-56-
template_type: Embed
title: Finite State Machines (5:56)
transcript: "<p><span m='330'>In</span> <span m='740'>the</span> <span m='820'>last</span>\
  \ <span m='1160'>chapter</span> <span m='1620'>we</span> <span m='1760'>developed</span>\
  \ <span m='2270'>sequential</span> <span m='2800'>logic,</span> <span m='3440'>which</span>\
  \ <span m='3820'>contains</span> <span m='4300'>both</span> <span m='4520'>combinational</span>\
  \ <span m='5270'>logic</span> <span m='5680'>and</span> <span m='5880'>memory</span>\
  \ <span m='6170'>components.</span> </p><p><span m='8090'>The</span> <span m='8160'>combinational</span>\
  \ <span m='8880'>logic</span> <span m='9230'>cloud</span> <span m='9550'>is</span>\
  \ <span m='9690'>an</span> <span m='9800'>acyclic</span> <span m='10430'>graph</span>\
  \ <span m='10750'>of</span> <span m='10850'>components</span> <span m='11520'>that</span>\
  \ <span m='11670'>obeys</span> <span m='12040'>the</span> <span m='12100'>static</span>\
  \ <span m='12490'>discipline.</span> </p><p><span m='13940'>The</span> <span m='14020'>static</span>\
  \ <span m='14400'>discipline</span> <span m='14930'>guarantees</span> <span m='15580'>if</span>\
  \ <span m='15720'>we</span> <span m='15790'>supply</span> <span m='16250'>valid</span>\
  \ <span m='16730'>and</span> <span m='16840'>stable</span> <span m='17290'>digital</span>\
  \ <span m='17640'>inputs,</span> <span m='18020'>then</span> <span m='18400'>we</span>\
  \ <span m='18490'>will</span> <span m='18680'>get</span> <span m='18880'>valid</span>\
  \ <span m='19340'>and</span> <span m='19450'>stable</span> <span m='19900'>digital</span>\
  \ <span m='20340'>outputs</span> <span m='21000'>by</span> <span m='21180'>some</span>\
  \ <span m='21400'>specified</span> <span m='22030'>interval</span> <span m='22520'>after</span>\
  \ <span m='22830'>the</span> <span m='22930'>last</span> <span m='23260'>input</span>\
  \ <span m='23600'>transition.</span> </p><p><span m='25490'>There\u2019s</span>\
  \ <span m='25690'>also</span> <span m='26120'>a</span> <span m='26170'>functional</span>\
  \ <span m='26580'>specification</span> <span m='27350'>that</span> <span m='27480'>tells</span>\
  \ <span m='27780'>us</span> <span m='27940'>the</span> <span m='28070'>output</span>\
  \ <span m='28440'>values</span> <span m='28860'>for</span> <span m='29120'>every</span>\
  \ <span m='29300'>possible</span> <span m='29910'>combination</span> <span m='30410'>of</span>\
  \ <span m='30510'>input</span> <span m='30840'>values.</span> </p><p><span m='32259'>In</span>\
  \ <span m='32390'>this</span> <span m='32560'>diagram,</span> <span m='33270'>there</span>\
  \ <span m='33940'>are</span> <span m='34420'>k+m</span> <span m='34890'>inputs</span>\
  \ <span m='35570'>and</span> <span m='36280'>k+n</span> <span m='36840'>outputs,</span>\
  \ <span m='37800'>so</span> <span m='38260'>the</span> <span m='38360'>truth</span>\
  \ <span m='38630'>table</span> <span m='38940'>for</span> <span m='39060'>the</span>\
  \ <span m='39140'>combinational</span> <span m='39830'>logic</span> <span m='40260'>will</span>\
  \ <span m='40370'>have</span> <span m='41240'>2^(k+m)</span> <span m='42230'>rows</span>\
  \ <span m='43030'>and</span> <span m='43830'>k+n</span> <span m='44510'>output</span>\
  \ <span m='44920'>columns.</span> </p><p><span m='47390'>The</span> <span m='47480'>job</span>\
  \ <span m='47800'>of</span> <span m='47880'>the</span> <span m='47940'>state</span>\
  \ <span m='48320'>registers</span> <span m='48950'>is</span> <span m='49060'>to</span>\
  \ <span m='49160'>remember</span> <span m='49560'>the</span> <span m='49650'>current</span>\
  \ <span m='50030'>state</span> <span m='50380'>of</span> <span m='50480'>the</span>\
  \ <span m='50560'>sequential</span> <span m='51100'>logic.</span> </p><p><span m='52490'>The</span>\
  \ <span m='52560'>state</span> <span m='52860'>is</span> <span m='53010'>encoded</span>\
  \ <span m='53470'>as</span> <span m='53560'>some</span> <span m='53840'>number</span>\
  \ <span m='54160'>k</span> <span m='54640'>of</span> <span m='54750'>bits,</span>\
  \ <span m='55330'>which</span> <span m='55670'>will</span> <span m='55820'>allow</span>\
  \ <span m='56130'>us</span> <span m='56260'>to</span> <span m='56370'>represent</span>\
  \ <span m='57190'>2^k</span> <span m='57730'>unique</span> <span m='58120'>states.</span>\
  \ </p><p><span m='59650'>Recall</span> <span m='60200'>that</span> <span m='60420'>the</span>\
  \ <span m='60500'>state</span> <span m='60870'>is</span> <span m='61030'>used</span>\
  \ <span m='61270'>to</span> <span m='61330'>capture,</span> <span m='62000'>in</span>\
  \ <span m='62150'>some</span> <span m='62380'>appropriate</span> <span m='63020'>way,</span>\
  \ <span m='63480'>the</span> <span m='63720'>relevant</span> <span m='64230'>history</span>\
  \ <span m='64709'>of</span> <span m='64790'>the</span> <span m='64930'>input</span>\
  \ <span m='65250'>sequence.</span> </p><p><span m='66300'>To</span> <span m='66400'>the</span>\
  \ <span m='66550'>extent</span> <span m='66960'>that</span> <span m='67100'>previous</span>\
  \ <span m='67570'>input</span> <span m='67930'>values</span> <span m='68410'>influence</span>\
  \ <span m='68960'>the</span> <span m='69100'>operation</span> <span m='69640'>of</span>\
  \ <span m='69700'>the</span> <span m='69770'>sequential</span> <span m='70300'>logic,</span>\
  \ <span m='70930'>that</span> <span m='71320'>happens</span> <span m='71880'>through</span>\
  \ <span m='72030'>the</span> <span m='72130'>stored</span> <span m='72600'>state</span>\
  \ <span m='72910'>bits.</span> </p><p><span m='74460'>Typically</span> <span m='74980'>the</span>\
  \ <span m='75070'>LOAD</span> <span m='75370'>input</span> <span m='75720'>of</span>\
  \ <span m='75820'>the</span> <span m='75890'>state</span> <span m='76180'>registers</span>\
  \ <span m='76740'>is</span> <span m='76880'>triggered</span> <span m='77280'>by</span>\
  \ <span m='77420'>the</span> <span m='77530'>rising</span> <span m='77950'>edge</span>\
  \ <span m='78190'>of</span> <span m='78280'>a</span> <span m='78350'>periodic</span>\
  \ <span m='78960'>signal,</span> <span m='79730'>which</span> <span m='80310'>updates</span>\
  \ <span m='80830'>the</span> <span m='80910'>stored</span> <span m='81310'>state</span>\
  \ <span m='81730'>with</span> <span m='81920'>the</span> <span m='81990'>new</span>\
  \ <span m='82190'>state</span> <span m='82540'>calculated</span> <span m='83060'>by</span>\
  \ <span m='83200'>the</span> <span m='83310'>combinational</span> <span m='83980'>logic.</span>\
  \ </p><p><span m='86720'>As</span> <span m='86900'>designers</span> <span m='87840'>we</span>\
  \ <span m='88210'>have</span> <span m='88320'>several</span> <span m='88690'>tasks:</span>\
  \ </p><p><span m='89730'>first</span> <span m='90160'>we</span> <span m='90320'>must</span>\
  \ <span m='90590'>decide</span> <span m='91050'>what</span> <span m='91410'>output</span>\
  \ <span m='91790'>sequences</span> <span m='92350'>need</span> <span m='92560'>to</span>\
  \ <span m='92620'>be</span> <span m='92740'>generated</span> <span m='93390'>in</span>\
  \ <span m='93540'>response</span> <span m='94200'>to</span> <span m='94320'>the</span>\
  \ <span m='94450'>expected</span> <span m='94920'>input</span> <span m='95330'>sequences.</span>\
  \ </p><p><span m='97190'>A</span> <span m='97230'>particular</span> <span m='97720'>input</span>\
  \ <span m='98090'>may,</span> <span m='98480'>in</span> <span m='98610'>fact,</span>\
  \ <span m='99440'>generate</span> <span m='100220'>a</span> <span m='100260'>long</span>\
  \ <span m='100710'>sequence</span> <span m='101140'>of</span> <span m='101210'>output</span>\
  \ <span m='101560'>values.</span> </p><p><span m='103370'>Or</span> <span m='103430'>the</span>\
  \ <span m='103580'>output</span> <span m='103990'>may</span> <span m='104280'>remain</span>\
  \ <span m='104700'>unchanged</span> <span m='105360'>while</span> <span m='105510'>the</span>\
  \ <span m='105640'>input</span> <span m='105900'>sequence</span> <span m='106290'>is</span>\
  \ <span m='106390'>processed,</span> <span m='107110'>step-by-step,</span> <span\
  \ m='108250'>where</span> <span m='108600'>the</span> <span m='108760'>FSM</span>\
  \ <span m='109300'>is</span> <span m='109390'>remembering</span> <span m='109950'>the</span>\
  \ <span m='110020'>relevant</span> <span m='110500'>information</span> <span m='111070'>by</span>\
  \ <span m='111250'>updating</span> <span m='111740'>its</span> <span m='111890'>internal</span>\
  \ <span m='112330'>state.</span> </p><p><span m='114400'>Then</span> <span m='114570'>we</span>\
  \ <span m='114720'>have</span> <span m='114870'>to</span> <span m='114980'>develop</span>\
  \ <span m='115440'>the</span> <span m='115520'>functional</span> <span m='115980'>specification</span>\
  \ <span m='116790'>for</span> <span m='116890'>the</span> <span m='116990'>logic</span>\
  \ <span m='117460'>so</span> <span m='117670'>it</span> <span m='117830'>calculates</span>\
  \ <span m='118500'>the</span> <span m='118570'>correct</span> <span m='119130'>output</span>\
  \ <span m='119700'>and</span> <span m='119890'>next</span> <span m='120130'>state</span>\
  \ <span m='120370'>values.</span> </p><p><span m='121630'>Finally,</span> <span\
  \ m='122450'>we</span> <span m='122910'>need</span> <span m='123050'>to</span> <span\
  \ m='123120'>come</span> <span m='123360'>up</span> <span m='123560'>with</span>\
  \ <span m='123800'>an</span> <span m='123910'>actual</span> <span m='124320'>circuit</span>\
  \ <span m='124660'>diagram</span> <span m='125140'>for</span> <span m='125330'>sequential</span>\
  \ <span m='125920'>logic</span> <span m='126270'>system.</span> </p><p><span m='127780'>All</span>\
  \ <span m='127920'>the</span> <span m='128020'>tasks</span> <span m='128360'>are</span>\
  \ <span m='128400'>pretty</span> <span m='128650'>interesting,</span> <span m='129180'>so</span>\
  \ <span m='129370'>let\u2019s</span> <span m='129580'>get</span> <span m='129720'>started!</span>\
  \ </p><p><span m='131470'>As</span> <span m='131630'>an</span> <span m='131720'>example</span>\
  \ <span m='132230'>sequential</span> <span m='132760'>system,</span> <span m='133350'>let\u2019\
  s</span> <span m='133660'>make</span> <span m='133840'>a</span> <span m='133900'>combination</span>\
  \ <span m='134520'>lock.</span> </p><p><span m='135760'>The</span> <span m='135840'>lock</span>\
  \ <span m='136210'>has</span> <span m='136510'>a</span> <span m='136800'>1-bit</span>\
  \ <span m='137310'>input</span> <span m='137700'>signal,</span> <span m='138280'>where</span>\
  \ <span m='138520'>the</span> <span m='138630'>user</span> <span m='139010'>enters</span>\
  \ <span m='139370'>the</span> <span m='139440'>combination</span> <span m='140110'>as</span>\
  \ <span m='140280'>a</span> <span m='140310'>sequence</span> <span m='140830'>of</span>\
  \ <span m='140940'>bits.</span> </p><p><span m='142430'>There\u2019s</span> <span\
  \ m='142630'>one</span> <span m='142870'>output</span> <span m='143300'>signal,</span>\
  \ <span m='143870'>UNLOCK,</span> <span m='144780'>which</span> <span m='145180'>is</span>\
  \ <span m='145450'>1</span> <span m='145660'>if</span> <span m='145950'>and</span>\
  \ <span m='146050'>only</span> <span m='146420'>if</span> <span m='146560'>the</span>\
  \ <span m='146660'>correct</span> <span m='147040'>combination</span> <span m='147600'>has</span>\
  \ <span m='147790'>been</span> <span m='147960'>entered.</span> </p><p><span m='149490'>In</span>\
  \ <span m='149590'>this</span> <span m='149760'>example,</span> <span m='150450'>we</span>\
  \ <span m='150660'>want</span> <span m='150960'>to</span> <span m='151060'>assert</span>\
  \ <span m='151370'>UNLOCK,</span> <span m='152250'>i.e.,</span> <span m='152750'>set</span>\
  \ <span m='153100'>UNLOCK</span> <span m='153500'>to</span> <span m='153660'>1,</span>\
  \ <span m='153690'>when</span> <span m='154440'>the</span> <span m='154930'>last</span>\
  \ <span m='155340'>four</span> <span m='155590'>input</span> <span m='155940'>values</span>\
  \ <span m='156420'>are</span> <span m='156510'>the</span> <span m='156610'>sequence</span>\
  \ <span m='157390'>0-1-1-0.</span> </p><p><span m='158610'>Mr.</span> <span m='159460'>Blue</span>\
  \ <span m='160280'>is</span> <span m='160420'>asking</span> <span m='160770'>a</span>\
  \ <span m='160840'>good</span> <span m='161010'>question:</span> <span m='161830'>how</span>\
  \ <span m='162320'>many</span> <span m='162570'>state</span> <span m='163000'>bits</span>\
  \ <span m='163340'>do</span> <span m='163430'>we</span> <span m='163590'>need?</span>\
  \ </p><p><span m='164670'>Do</span> <span m='164760'>we</span> <span m='164940'>have</span>\
  \ <span m='165190'>to</span> <span m='165320'>remember</span> <span m='165700'>the</span>\
  \ <span m='165790'>last</span> <span m='166100'>four</span> <span m='166310'>input</span>\
  \ <span m='166650'>bits?</span> </p><p><span m='168040'>In</span> <span m='168170'>which</span>\
  \ <span m='168370'>case,</span> <span m='168720'>we\u2019d</span> <span m='168910'>need</span>\
  \ <span m='169120'>four</span> <span m='169380'>state</span> <span m='169710'>bits.</span>\
  \ </p><p><span m='170600'>Or</span> <span m='170900'>can</span> <span m='171220'>we</span>\
  \ <span m='171460'>remember</span> <span m='171960'>less</span> <span m='172260'>information</span>\
  \ <span m='172870'>and</span> <span m='173000'>still</span> <span m='173360'>do</span>\
  \ <span m='173540'>our</span> <span m='173690'>job?</span> </p><p><span m='174720'>Aha!</span>\
  \ <span m='175440'>We</span> <span m='176010'>don\u2019t</span> <span m='176230'>need</span>\
  \ <span m='176390'>the</span> <span m='176450'>complete</span> <span m='176930'>history</span>\
  \ <span m='177420'>of</span> <span m='177510'>the</span> <span m='177590'>last</span>\
  \ <span m='177920'>four</span> <span m='178140'>inputs,</span> <span m='178780'>we</span>\
  \ <span m='179080'>only</span> <span m='179340'>need</span> <span m='179530'>to</span>\
  \ <span m='179620'>know</span> <span m='179920'>if</span> <span m='180010'>the</span>\
  \ <span m='180090'>most</span> <span m='180360'>recent</span> <span m='180690'>entries</span>\
  \ <span m='181090'>represent</span> <span m='181640'>some</span> <span m='181860'>part</span>\
  \ <span m='182290'>of</span> <span m='182380'>a</span> <span m='182440'>partially-entered</span>\
  \ <span m='183310'>correct</span> <span m='183800'>combination.</span> </p><p><span\
  \ m='185380'>In</span> <span m='185460'>other</span> <span m='185620'>words</span>\
  \ <span m='186040'>if</span> <span m='186370'>the</span> <span m='186590'>input</span>\
  \ <span m='186930'>sequence</span> <span m='187400'>doesn\u2019t</span> <span m='187850'>represent</span>\
  \ <span m='188290'>a</span> <span m='188330'>correct</span> <span m='188690'>combination,</span>\
  \ <span m='189550'>we</span> <span m='189880'>don\u2019t</span> <span m='190110'>need</span>\
  \ <span m='190240'>to</span> <span m='190310'>keep</span> <span m='190590'>track</span>\
  \ <span m='190960'>of</span> <span m='191160'>exactly</span> <span m='191820'>how</span>\
  \ <span m='192000'>it\u2019s</span> <span m='192140'>incorrect,</span> <span m='192800'>we</span>\
  \ <span m='193020'>only</span> <span m='193190'>need</span> <span m='193410'>to</span>\
  \ <span m='193480'>know</span> <span m='193710'>that</span> <span m='193970'>is</span>\
  \ <span m='194410'>incorrect.</span> </p><p><span m='196850'>With</span> <span m='197000'>that</span>\
  \ <span m='197210'>observation</span> <span m='197880'>in</span> <span m='198020'>mind,</span>\
  \ <span m='198510'>let\u2019s</span> <span m='198850'>figure</span> <span m='199170'>out</span>\
  \ <span m='199360'>how</span> <span m='199560'>to</span> <span m='199700'>represent</span>\
  \ <span m='200230'>the</span> <span m='200320'>desired</span> <span m='200890'>behavior</span>\
  \ <span m='201560'>of</span> <span m='201700'>our</span> <span m='201820'>digital</span>\
  \ <span m='202230'>system.</span> </p><p><span m='203440'>We</span> <span m='203560'>can</span>\
  \ <span m='203740'>characterize</span> <span m='204500'>the</span> <span m='204600'>behavior</span>\
  \ <span m='205210'>of</span> <span m='205320'>a</span> <span m='205360'>sequential</span>\
  \ <span m='205890'>system</span> <span m='206410'>using</span> <span m='206750'>a</span>\
  \ <span m='206810'>new</span> <span m='207050'>abstraction</span> <span m='207810'>called</span>\
  \ <span m='208090'>a</span> <span m='208150'>finite</span> <span m='208660'>state</span>\
  \ <span m='208950'>machine,</span> <span m='209520'>or</span> <span m='209850'>FSM</span>\
  \ <span m='210410'>for</span> <span m='210540'>short.</span> </p><p><span m='211760'>The</span>\
  \ <span m='211830'>goal</span> <span m='212180'>of</span> <span m='212250'>the</span>\
  \ <span m='212440'>FSM</span> <span m='212930'>abstraction</span> <span m='213600'>is</span>\
  \ <span m='213770'>to</span> <span m='213860'>describe</span> <span m='214330'>the</span>\
  \ <span m='214490'>input/output</span> <span m='215320'>behavior</span> <span m='215890'>of</span>\
  \ <span m='216040'>the</span> <span m='216120'>sequential</span> <span m='216720'>logic,</span>\
  \ <span m='217230'>independent</span> <span m='218030'>of</span> <span m='218150'>its</span>\
  \ <span m='218320'>actual</span> <span m='218760'>implementation.</span> </p><p><span\
  \ m='221020'>A</span> <span m='221060'>finite</span> <span m='221460'>state</span>\
  \ <span m='221730'>machine</span> <span m='222140'>has</span> <span m='222340'>a</span>\
  \ <span m='222380'>periodic</span> <span m='222900'>CLOCK</span> <span m='223320'>input.</span>\
  \ </p><p><span m='224420'>A</span> <span m='224500'>rising</span> <span m='224900'>clock</span>\
  \ <span m='225290'>edge</span> <span m='225560'>will</span> <span m='225750'>trigger</span>\
  \ <span m='226080'>the</span> <span m='226160'>transition</span> <span m='226850'>from</span>\
  \ <span m='227120'>the</span> <span m='227210'>current</span> <span m='227580'>state</span>\
  \ <span m='227980'>to</span> <span m='228110'>the</span> <span m='228210'>next</span>\
  \ <span m='228480'>state.</span> </p><p><span m='229360'>The</span> <span m='229490'>FSM</span>\
  \ <span m='230030'>has</span> <span m='230200'>a</span> <span m='230230'>some</span>\
  \ <span m='230440'>fixed</span> <span m='230730'>number</span> <span m='230990'>of</span>\
  \ <span m='231070'>states,</span> <span m='231700'>with</span> <span m='232010'>a</span>\
  \ <span m='232050'>particular</span> <span m='232520'>state</span> <span m='232880'>designated</span>\
  \ <span m='233550'>as</span> <span m='233730'>the</span> <span m='233850'>initial</span>\
  \ <span m='234390'>or</span> <span m='234500'>starting</span> <span m='234950'>state</span>\
  \ <span m='235540'>when</span> <span m='235890'>the</span> <span m='236020'>FSM</span>\
  \ <span m='236580'>is</span> <span m='236750'>first</span> <span m='237080'>turned</span>\
  \ <span m='237270'>on.</span> </p><p><span m='238970'>One</span> <span m='239220'>of</span>\
  \ <span m='239330'>the</span> <span m='239490'>interesting</span> <span m='239970'>challenges</span>\
  \ <span m='240600'>in</span> <span m='240690'>designing</span> <span m='241130'>an</span>\
  \ <span m='241220'>FSM</span> <span m='241780'>is</span> <span m='241900'>to</span>\
  \ <span m='241980'>determine</span> <span m='242470'>the</span> <span m='242540'>required</span>\
  \ <span m='243140'>number</span> <span m='243530'>of</span> <span m='243600'>states</span>\
  \ <span m='244270'>since</span> <span m='244670'>there\u2019s</span> <span m='244870'>often</span>\
  \ <span m='245280'>a</span> <span m='245330'>tradeoff</span> <span m='245950'>between</span>\
  \ <span m='246280'>the</span> <span m='246350'>number</span> <span m='246750'>of</span>\
  \ <span m='246820'>state</span> <span m='247150'>bits</span> <span m='247690'>and</span>\
  \ <span m='247960'>the</span> <span m='248020'>complexity</span> <span m='248840'>of</span>\
  \ <span m='248920'>the</span> <span m='249090'>internal</span> <span m='249580'>combinational</span>\
  \ <span m='250280'>logic</span> <span m='250790'>required</span> <span m='251240'>to</span>\
  \ <span m='251300'>compute</span> <span m='251730'>the</span> <span m='251860'>next</span>\
  \ <span m='252130'>state</span> <span m='252440'>and</span> <span m='252550'>outputs.</span>\
  \ </p><p><span m='253780'>There</span> <span m='253950'>are</span> <span m='254050'>some</span>\
  \ <span m='254310'>number</span> <span m='254620'>of</span> <span m='254750'>inputs,</span>\
  \ <span m='255420'>used</span> <span m='255710'>to</span> <span m='255820'>convey</span>\
  \ <span m='256339'>all</span> <span m='256600'>the</span> <span m='256769'>external</span>\
  \ <span m='257339'>information</span> <span m='258000'>necessary</span> <span m='258670'>for</span>\
  \ <span m='258839'>the</span> <span m='259019'>FSM</span> <span m='259550'>to</span>\
  \ <span m='259690'>do</span> <span m='259890'>its</span> <span m='260079'>job.</span>\
  \ </p><p><span m='261370'>Again,</span> <span m='261890'>there</span> <span m='262230'>are</span>\
  \ <span m='262310'>interesting</span> <span m='262780'>design</span> <span m='263190'>tradeoffs.</span>\
  \ </p><p><span m='264430'>Suppose</span> <span m='264880'>the</span> <span m='265050'>FSM</span>\
  \ <span m='265520'>required</span> <span m='266090'>100</span> <span m='266300'>bits</span>\
  \ <span m='266760'>of</span> <span m='266840'>input.</span> </p><p><span m='268080'>Should</span>\
  \ <span m='268330'>we</span> <span m='268620'>have</span> <span m='269020'>100</span>\
  \ <span m='269250'>inputs</span> <span m='269940'>and</span> <span m='270060'>deliver</span>\
  \ <span m='270460'>the</span> <span m='270710'>information</span> <span m='271320'>all</span>\
  \ <span m='271380'>at</span> <span m='271440'>once?</span> </p><p><span m='272980'>Or</span>\
  \ <span m='273400'>should</span> <span m='273590'>we</span> <span m='273780'>have</span>\
  \ <span m='274030'>a</span> <span m='274080'>single</span> <span m='274560'>input</span>\
  \ <span m='274980'>and</span> <span m='275130'>deliver</span> <span m='275470'>the</span>\
  \ <span m='275590'>information</span> <span m='276260'>as</span> <span m='276450'>a</span>\
  \ <span m='276670'>100-cycle</span> <span m='277280'>sequence?</span> </p><p><span\
  \ m='279370'>In</span> <span m='279460'>many</span> <span m='279710'>real</span>\
  \ <span m='279950'>world</span> <span m='280290'>situations</span> <span m='281200'>where</span>\
  \ <span m='281440'>the</span> <span m='281540'>sequential</span> <span m='282100'>logic</span>\
  \ <span m='282530'>is</span> <span m='282650'>*much*</span> <span m='283010'>faster</span>\
  \ <span m='283500'>than</span> <span m='283720'>whatever</span> <span m='284050'>physical</span>\
  \ <span m='284530'>process</span> <span m='285140'>we\u2019re</span> <span m='285240'>trying</span>\
  \ <span m='285480'>to</span> <span m='285540'>control,</span> </p><p><span m='286510'>we\u2019\
  ll</span> <span m='286650'>often</span> <span m='286990'>see</span> <span m='287230'>the</span>\
  \ <span m='287350'>use</span> <span m='287770'>of</span> <span m='287910'>bit-serial</span>\
  \ <span m='288620'>inputs</span> <span m='289270'>where</span> <span m='289510'>the</span>\
  \ <span m='289630'>information</span> <span m='290150'>arrives</span> <span m='290550'>as</span>\
  \ <span m='290690'>a</span> <span m='290730'>sequence,</span> <span m='291440'>one</span>\
  \ <span m='291730'>bit</span> <span m='291920'>at</span> <span m='292020'>a</span>\
  \ <span m='292080'>time.</span> </p><p><span m='293050'>That</span> <span m='293210'>will</span>\
  \ <span m='293310'>allow</span> <span m='293720'>us</span> <span m='293930'>to</span>\
  \ <span m='294030'>use</span> <span m='294400'>much</span> <span m='294740'>less</span>\
  \ <span m='294990'>signaling</span> <span m='295520'>hardware,</span> <span m='296240'>at</span>\
  \ <span m='296510'>the</span> <span m='296600'>cost</span> <span m='297010'>of</span>\
  \ <span m='297070'>the</span> <span m='297150'>time</span> <span m='297480'>required</span>\
  \ <span m='298010'>to</span> <span m='298090'>transmit</span> <span m='298720'>the</span>\
  \ <span m='298870'>information</span> <span m='299390'>sequentially.</span> </p><p><span\
  \ m='301690'>The</span> <span m='301790'>FSM</span> <span m='302260'>has</span>\
  \ <span m='302430'>some</span> <span m='302690'>number</span> <span m='303080'>outputs</span>\
  \ <span m='303680'>to</span> <span m='303790'>convey</span> <span m='304140'>the</span>\
  \ <span m='304240'>results</span> <span m='304760'>of</span> <span m='304840'>the</span>\
  \ <span m='304930'>sequential</span> <span m='305480'>logic\u2019s</span> <span\
  \ m='305970'>computations.</span> </p><p><span m='308250'>The</span> <span m='308330'>comment</span>\
  \ <span m='308880'>before</span> <span m='309370'>about</span> <span m='309700'>serial</span>\
  \ <span m='310180'>vs.</span> <span m='310540'>parallel</span> <span m='311050'>inputs</span>\
  \ <span m='311580'>applies</span> <span m='312070'>equally</span> <span m='312470'>to</span>\
  \ <span m='312570'>choosing</span> <span m='312930'>how</span> <span m='313140'>information</span>\
  \ <span m='313750'>should</span> <span m='313930'>be</span> <span m='314070'>encoded</span>\
  \ <span m='314600'>on</span> <span m='314710'>the</span> <span m='314850'>outputs.</span>\
  \ </p><p><span m='317180'>There</span> <span m='317350'>are</span> <span m='317570'>a</span>\
  \ <span m='317600'>set</span> <span m='317840'>of</span> <span m='317940'>transition</span>\
  \ <span m='318530'>rules,</span> <span m='318880'>specifying</span> <span m='319660'>how</span>\
  \ <span m='319850'>the</span> <span m='319940'>next</span> <span m='320270'>state</span>\
  \ <span m='320670'>S-prime</span> <span m='321410'>is</span> <span m='321540'>determined</span>\
  \ <span m='322100'>from</span> <span m='322290'>the</span> <span m='322380'>current</span>\
  \ <span m='322720'>state</span> <span m='323060'>S</span> <span m='323530'>and</span>\
  \ <span m='323650'>the</span> <span m='323800'>inputs</span> <span m='324290'>I.</span>\
  \ </p><p><span m='324970'>The</span> <span m='325040'>specification</span> <span\
  \ m='325900'>must</span> <span m='326150'>be</span> <span m='326290'>complete,</span>\
  \ <span m='327110'>enumerating</span> <span m='328110'>S-prime</span> <span m='328770'>for</span>\
  \ <span m='328970'>every</span> <span m='329280'>possible</span> <span m='329910'>combination</span>\
  \ <span m='330620'>of</span> <span m='330800'>S</span> <span m='331140'>and</span>\
  \ <span m='331320'>I.</span> </p><p><span m='332210'>And,</span> <span m='332480'>finally,</span>\
  \ <span m='332980'>there\u2019s</span> <span m='333160'>the</span> <span m='333240'>specification</span>\
  \ <span m='334080'>for</span> <span m='334230'>how</span> <span m='334460'>the</span>\
  \ <span m='334670'>output</span> <span m='335070'>values</span> <span m='335600'>should</span>\
  \ <span m='335910'>be</span> <span m='336020'>determined.</span> </p><p><span m='337560'>The</span>\
  \ <span m='337670'>FSM</span> <span m='338120'>design</span> <span m='338580'>is</span>\
  \ <span m='338730'>often</span> <span m='339100'>a</span> <span m='339160'>bit</span>\
  \ <span m='339370'>simpler</span> <span m='339910'>if</span> <span m='340010'>the</span>\
  \ <span m='340150'>outputs</span> <span m='340540'>are</span> <span m='340630'>strictly</span>\
  \ <span m='341150'>a</span> <span m='341200'>function</span> <span m='341610'>of</span>\
  \ <span m='341670'>the</span> <span m='341770'>current</span> <span m='342110'>state</span>\
  \ <span m='342480'>S,</span> <span m='343300'>but,</span> <span m='343820'>in</span>\
  \ <span m='343980'>general,</span> <span m='344750'>the</span> <span m='345050'>outputs</span>\
  \ <span m='345460'>can</span> <span m='345590'>be</span> <span m='345740'>a</span>\
  \ <span m='345770'>function</span> <span m='346160'>of</span> <span m='346250'>both</span>\
  \ <span m='346560'>S</span> <span m='347100'>and</span> <span m='347440'>the</span>\
  \ <span m='347520'>current</span> <span m='347830'>inputs.</span> </p><p><span m='349960'>Now</span>\
  \ <span m='350120'>that</span> <span m='350260'>we</span> <span m='350390'>have</span>\
  \ <span m='350520'>our</span> <span m='350670'>abstraction</span> <span m='351270'>in</span>\
  \ <span m='351370'>place,</span> <span m='352050'>let\u2019s</span> <span m='352550'>see</span>\
  \ <span m='352680'>how</span> <span m='352810'>to</span> <span m='352900'>use</span>\
  \ <span m='353270'>it</span> <span m='353400'>to</span> <span m='353530'>design</span>\
  \ <span m='354150'>our</span> <span m='354280'>combinational</span> <span m='355030'>lock.</span>\
  \ </p>"
type: course
uid: 84502f44164a9ce08e5cbc115765560f

---
None