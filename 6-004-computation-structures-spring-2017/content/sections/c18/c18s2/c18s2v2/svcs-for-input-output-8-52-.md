---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: LWE5p2sCI6o
  parent_uid: 4dcc88e8907834b7c84e64f30d326373
  title: Video-YouTube-Stream
  type: Video
  uid: 09dcb9daefc03e6defb8c29b4fe1134a
- id: 3Play-3Play YouTube id-Stream
  media_location: LWE5p2sCI6o
  parent_uid: 4dcc88e8907834b7c84e64f30d326373
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 600502ec4c5e217aec945722ee2e6d5a
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/LWE5p2sCI6o/default.jpg
  parent_uid: 4dcc88e8907834b7c84e64f30d326373
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 5e274bf6e00ee3ba21f8318bc642908f
- id: LWE5p2sCI6o.srt
  parent_uid: 4dcc88e8907834b7c84e64f30d326373
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v2/svcs-for-input-output-8-52-/LWE5p2sCI6o.srt
  title: 3play caption file
  type: null
  uid: 3009aebc85df890b8248cf5ceabe40a6
- id: LWE5p2sCI6o.pdf
  parent_uid: 4dcc88e8907834b7c84e64f30d326373
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v2/svcs-for-input-output-8-52-/LWE5p2sCI6o.pdf
  title: 3play pdf file
  type: null
  uid: 6893772f02f39ae59409fa62d18e32b7
- id: Caption-3Play YouTube id-SRT
  parent_uid: 4dcc88e8907834b7c84e64f30d326373
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 044d85bf4d6969736349c6d8127499df
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 4dcc88e8907834b7c84e64f30d326373
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 95ad2d07413d4a4142be75aacbe799b4
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_18-02-02_300k.mp4
  parent_uid: 4dcc88e8907834b7c84e64f30d326373
  title: Video-Internet Archive-MP4
  type: Video
  uid: 16befd48c8d6a9dea46c97089fbfcce4
inline_embed_id: 98562919svcsforinputoutput85241075664
layout: video
order_index: null
parent_uid: d6290c1315afd7b15a7e796116a1528e
related_resources_text: ''
short_url: svcs-for-input-output-8-52-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v2/svcs-for-input-output-8-52-
template_type: Embed
title: SVCs for Input/Output (8:52)
transcript: <p><span m='1120'>When</span> <span m='1557'>a</span> <span m='1995'>user-mode</span>
  <span m='2433'>program</span> <span m='2871'>wants</span> <span m='3309'>to</span>
  <span m='3747'>read</span> <span m='4185'>a</span> <span m='4623'>typed</span> <span
  m='5061'>character</span> <span m='5499'>it</span> <span m='5937'>executes</span>
  <span m='6375'>a</span> <span m='6813'>ReadKey()</span> <span m='7251'>SVC.</span>
  </p><p><span m='7689'>The</span> <span m='8106'>binary</span> <span m='8524'>representation</span>
  <span m='8941'>of</span> <span m='9359'>the</span> <span m='9776'>SVC</span> <span
  m='10194'>has</span> <span m='10611'>an</span> <span m='11029'>illegal</span> <span
  m='11447'>value</span> <span m='11864'>in</span> <span m='12282'>the</span> <span
  m='12699'>opcode</span> <span m='13117'>field,</span> <span m='13534'>so</span>
  <span m='13952'>the</span> <span m='14370'>CPU</span> <span m='14750'>hardware</span>
  <span m='15130'>causes</span> <span m='15510'>an</span> <span m='15890'>exception,</span>
  <span m='16270'>which</span> <span m='16650'>starts</span> <span m='17030'>executing</span>
  <span m='17410'>the</span> <span m='17790'>illegal</span> <span m='18170'>opcode</span>
  <span m='18550'>handler</span> <span m='18930'>in</span> <span m='19310'>the</span>
  <span m='19690'>OS.</span> </p><p><span m='21390'>The</span> <span m='21754'>OS</span>
  <span m='22118'>handler</span> <span m='22483'>recognizes</span> <span m='22847'>the</span>
  <span m='23211'>illegal</span> <span m='23576'>opcode</span> <span m='23940'>value</span>
  <span m='24305'>as</span> <span m='24669'>being</span> <span m='25033'>an</span>
  <span m='25398'>SVC</span> <span m='25762'>and</span> <span m='26126'>uses</span>
  <span m='26491'>the</span> <span m='26855'>low-order</span> <span m='27220'>bits</span>
  <span m='27783'>of</span> <span m='28347'>the</span> <span m='28910'>SVC</span>
  <span m='29474'>instruction</span> <span m='30038'>to</span> <span m='30601'>determine</span>
  <span m='31165'>which</span> <span m='31729'>sub-handler</span> <span m='32292'>to</span>
  <span m='32856'>call.</span> </p><p><span m='33420'>Here's</span> <span m='33789'>our</span>
  <span m='34158'>first</span> <span m='34527'>draft</span> <span m='34896'>for</span>
  <span m='35265'>the</span> <span m='35634'>ReadKey</span> <span m='36004'>sub-handler,</span>
  <span m='36373'>this</span> <span m='36742'>time</span> <span m='37111'>written</span>
  <span m='37480'>in</span> <span m='37849'>C.</span> </p><p><span m='38219'>The</span>
  <span m='38545'>handler</span> <span m='38871'>starts</span> <span m='39197'>by</span>
  <span m='39524'>looking</span> <span m='39850'>at</span> <span m='40176'>the</span>
  <span m='40503'>process</span> <span m='40829'>table</span> <span m='41155'>entry</span>
  <span m='41482'>for</span> <span m='41808'>the</span> <span m='42134'>current</span>
  <span m='42461'>process</span> <span m='42787'>to</span> <span m='43113'>determine</span>
  <span m='43440'>which</span> <span m='43937'>keyboard</span> <span m='44435'>buffer</span>
  <span m='44933'>holds</span> <span m='45431'>the</span> <span m='45928'>characters</span>
  <span m='46426'>for</span> <span m='46924'>the</span> <span m='47422'>process.</span>
  </p><p><span m='47920'>Let's</span> <span m='48199'>assume</span> <span m='48479'>for</span>
  <span m='48759'>the</span> <span m='49039'>moment</span> <span m='49319'>the</span>
  <span m='49599'>buffer</span> <span m='49879'>is</span> <span m='50159'>*not*</span>
  <span m='50439'>empty</span> <span m='50719'>and</span> <span m='50999'>skip</span>
  <span m='51279'>to</span> <span m='51559'>the</span> <span m='51839'>last</span>
  <span m='52119'>line,</span> <span m='52399'>which</span> <span m='52685'>reads</span>
  <span m='52971'>the</span> <span m='53257'>character</span> <span m='53544'>from</span>
  <span m='53830'>the</span> <span m='54116'>buffer</span> <span m='54403'>and</span>
  <span m='54689'>uses</span> <span m='54975'>it</span> <span m='55262'>to</span>
  <span m='55548'>replace</span> <span m='55834'>the</span> <span m='56121'>saved</span>
  <span m='56407'>value</span> <span m='56693'>for</span> <span m='56980'>the</span>
  <span m='57457'>user's</span> <span m='57934'>R0</span> <span m='58411'>in</span>
  <span m='58889'>the</span> <span m='59366'>array</span> <span m='59843'>holding</span>
  <span m='60320'>the</span> <span m='60798'>saved</span> <span m='61275'>register</span>
  <span m='61752'>values.</span> </p><p><span m='62230'>When</span> <span m='62620'>the</span>
  <span m='63010'>handler</span> <span m='63400'>exits,</span> <span m='63790'>the</span>
  <span m='64180'>OS</span> <span m='64570'>will</span> <span m='64960'>reload</span>
  <span m='65350'>the</span> <span m='65740'>saved</span> <span m='66130'>registers</span>
  <span m='66520'>and</span> <span m='66910'>resume</span> <span m='67300'>execution</span>
  <span m='67690'>of</span> <span m='68080'>the</span> <span m='68703'>user-mode</span>
  <span m='69326'>program</span> <span m='69950'>with</span> <span m='70573'>the</span>
  <span m='71196'>just-read</span> <span m='71820'>character</span> <span m='72443'>in</span>
  <span m='73066'>R0.</span> </p><p><span m='73690'>Now</span> <span m='74022'>let's</span>
  <span m='74355'>figure</span> <span m='74687'>what</span> <span m='75020'>to</span>
  <span m='75352'>do</span> <span m='75685'>when</span> <span m='76017'>the</span>
  <span m='76350'>keyboard</span> <span m='76682'>buffer</span> <span m='77015'>is</span>
  <span m='77347'>empty.</span> </p><p><span m='77680'>The</span> <span m='78053'>code</span>
  <span m='78426'>shown</span> <span m='78799'>here</span> <span m='79172'>simply</span>
  <span m='79545'>loops</span> <span m='79918'>until</span> <span m='80291'>the</span>
  <span m='80664'>buffer</span> <span m='81037'>is</span> <span m='81410'>no</span>
  <span m='81783'>longer</span> <span m='82156'>empty.</span> </p><p><span m='82530'>The</span>
  <span m='82882'>theory</span> <span m='83234'>is</span> <span m='83586'>that</span>
  <span m='83938'>eventually</span> <span m='84290'>the</span> <span m='84642'>user</span>
  <span m='84995'>will</span> <span m='85347'>type</span> <span m='85699'>a</span>
  <span m='86051'>character,</span> <span m='86403'>causing</span> <span m='86755'>an</span>
  <span m='87107'>interrupt,</span> <span m='87460'>which</span> <span m='87776'>will</span>
  <span m='88092'>run</span> <span m='88409'>the</span> <span m='88725'>keyboard</span>
  <span m='89042'>interrupt</span> <span m='89358'>handler</span> <span m='89675'>discussed</span>
  <span m='89991'>in</span> <span m='90307'>the</span> <span m='90624'>previous</span>
  <span m='90940'>section,</span> <span m='91257'>which</span> <span m='91573'>will</span>
  <span m='91890'>store</span> <span m='92404'>a</span> <span m='92918'>new</span>
  <span m='93432'>character</span> <span m='93947'>into</span> <span m='94461'>the</span>
  <span m='94975'>buffer.</span> </p><p><span m='95490'>This</span> <span m='95825'>all</span>
  <span m='96160'>sounds</span> <span m='96495'>good</span> <span m='96830'>until</span>
  <span m='97165'>we</span> <span m='97500'>remember</span> <span m='97835'>that</span>
  <span m='98170'>the</span> <span m='98505'>SVC</span> <span m='98840'>handler</span>
  <span m='99175'>is</span> <span m='99510'>running</span> <span m='99845'>with</span>
  <span m='100180'>the</span> <span m='100515'>supervisor</span> <span m='100850'>bit</span>
  <span m='101614'>(PC[31])</span> <span m='102378'>set</span> <span m='103142'>to</span>
  <span m='103907'>1,</span> <span m='104671'>disabling</span> <span m='105435'>interrupts.</span>
  </p><p><span m='106200'>Oops!</span> </p><p><span m='107729'>Since</span> <span
  m='108064'>the</span> <span m='108399'>keyboard</span> <span m='108734'>interrupt</span>
  <span m='109069'>will</span> <span m='109404'>never</span> <span m='109739'>happen,</span>
  <span m='110074'>the</span> <span m='110409'>while</span> <span m='110744'>loop</span>
  <span m='111079'>shown</span> <span m='111414'>here</span> <span m='111749'>is</span>
  <span m='112084'>actually</span> <span m='112419'>an</span> <span m='112754'>infinite</span>
  <span m='113090'>loop.</span> </p><p><span m='114130'>So</span> <span m='114434'>if</span>
  <span m='114738'>the</span> <span m='115043'>user-mode</span> <span m='115347'>program</span>
  <span m='115651'>tries</span> <span m='115956'>to</span> <span m='116260'>read</span>
  <span m='116565'>a</span> <span m='116869'>character</span> <span m='117173'>from</span>
  <span m='117478'>an</span> <span m='117782'>empty</span> <span m='118086'>buffer,</span>
  <span m='118391'>the</span> <span m='118695'>system</span> <span m='119000'>will</span>
  <span m='119487'>appear</span> <span m='119975'>to</span> <span m='120463'>hang,</span>
  <span m='120951'>not</span> <span m='121439'>responding</span> <span m='121927'>to</span>
  <span m='122415'>any</span> <span m='122902'>external</span> <span m='123390'>inputs</span>
  <span m='123878'>since</span> <span m='124366'>interrupts</span> <span m='124854'>are</span>
  <span m='125342'>disabled.</span> </p><p><span m='125830'>Time</span> <span m='126110'>to</span>
  <span m='126390'>reach</span> <span m='126670'>for</span> <span m='126950'>the</span>
  <span m='127230'>power</span> <span m='127510'>switch</span> <span m='127790'>:)</span>
  <span m='128070'>We'll</span> <span m='128350'>fix</span> <span m='128630'>the</span>
  <span m='128910'>looping</span> <span m='129190'>problem</span> <span m='129470'>by</span>
  <span m='129750'>adding</span> <span m='130030'>code</span> <span m='130310'>to</span>
  <span m='130702'>subtract</span> <span m='131094'>4</span> <span m='131486'>from</span>
  <span m='131879'>the</span> <span m='132271'>saved</span> <span m='132663'>value</span>
  <span m='133056'>of</span> <span m='133448'>the</span> <span m='133840'>XP</span>
  <span m='134233'>register</span> <span m='134625'>before</span> <span m='135017'>returning.</span>
  </p><p><span m='135410'>How</span> <span m='135830'>does</span> <span m='136250'>this</span>
  <span m='136670'>fix</span> <span m='137090'>the</span> <span m='137510'>problem?</span>
  </p><p><span m='137930'>Recall</span> <span m='138439'>that</span> <span m='138948'>when</span>
  <span m='139457'>the</span> <span m='139967'>SVC</span> <span m='140476'>illegal</span>
  <span m='140985'>instruction</span> <span m='141495'>exception</span> <span m='142004'>happened,</span>
  <span m='142513'>the</span> <span m='143022'>CPU</span> <span m='143532'>stored</span>
  <span m='144041'>the</span> <span m='144550'>PC+4</span> <span m='145060'>value</span>
  <span m='145497'>of</span> <span m='145935'>the</span> <span m='146373'>illegal</span>
  <span m='146811'>instruction</span> <span m='147249'>in</span> <span m='147687'>the</span>
  <span m='148125'>user's</span> <span m='148563'>XP</span> <span m='149001'>register.</span>
  </p><p><span m='149439'>When</span> <span m='149784'>the</span> <span m='150129'>handler</span>
  <span m='150475'>exits,</span> <span m='150820'>the</span> <span m='151166'>OS</span>
  <span m='151511'>will</span> <span m='151856'>resume</span> <span m='152202'>execution</span>
  <span m='152547'>of</span> <span m='152893'>the</span> <span m='153238'>user-mode</span>
  <span m='153583'>program</span> <span m='153929'>by</span> <span m='154274'>reloading</span>
  <span m='154620'>the</span> <span m='155052'>registers</span> <span m='155485'>and</span>
  <span m='155918'>then</span> <span m='156351'>executing</span> <span m='156784'>a</span>
  <span m='157217'>JMP(XP),</span> <span m='157650'>which</span> <span m='158082'>would</span>
  <span m='158515'>normally</span> <span m='158948'>then</span> <span m='159381'>execute</span>
  <span m='159814'>the</span> <span m='160247'>instruction</span> <span m='160680'>*following*</span>
  <span m='161460'>the</span> <span m='162240'>SVC</span> <span m='163020'>instruction.</span>
  </p><p><span m='163800'>By</span> <span m='164152'>subtracting</span> <span m='164504'>4</span>
  <span m='164857'>from</span> <span m='165209'>the</span> <span m='165561'>saved</span>
  <span m='165914'>XP</span> <span m='166266'>value,</span> <span m='166618'>it</span>
  <span m='166971'>will</span> <span m='167323'>be</span> <span m='167675'>the</span>
  <span m='168028'>SVC</span> <span m='168380'>itself</span> <span m='168732'>that</span>
  <span m='169085'>gets</span> <span m='169437'>re-executed.</span> </p><p><span m='169790'>That,</span>
  <span m='170203'>of</span> <span m='170616'>course,</span> <span m='171029'>means</span>
  <span m='171442'>we'll</span> <span m='171855'>go</span> <span m='172268'>through</span>
  <span m='172681'>the</span> <span m='173095'>same</span> <span m='173508'>set</span>
  <span m='173921'>of</span> <span m='174334'>steps</span> <span m='174747'>again,</span>
  <span m='175160'>repeating</span> <span m='175573'>the</span> <span m='175986'>cycle</span>
  <span m='176400'>until</span> <span m='176818'>the</span> <span m='177237'>keyboard</span>
  <span m='177655'>buffer</span> <span m='178074'>is</span> <span m='178493'>no</span>
  <span m='178911'>longer</span> <span m='179330'>empty.</span> </p><p><span m='179749'>It's</span>
  <span m='180285'>just</span> <span m='180822'>a</span> <span m='181359'>more</span>
  <span m='181895'>complicated</span> <span m='182432'>loop!</span> </p><p><span m='182969'>But</span>
  <span m='183315'>with</span> <span m='183662'>a</span> <span m='184009'>crucial</span>
  <span m='184356'>difference:</span> <span m='184703'>one</span> <span m='185050'>of</span>
  <span m='185397'>the</span> <span m='185744'>instructions</span> <span m='186090'>-</span>
  <span m='186437'>the</span> <span m='186784'>ReadKey()</span> <span m='187131'>SVC</span>
  <span m='187478'>-</span> <span m='187825'>is</span> <span m='188172'>executed</span>
  <span m='188519'>in</span> <span m='189102'>user-mode</span> <span m='189685'>with</span>
  <span m='190269'>PC[31]</span> <span m='190852'>=</span> <span m='191435'>0.</span>
  </p><p><span m='192019'>So</span> <span m='192371'>during</span> <span m='192724'>that</span>
  <span m='193077'>cycle,</span> <span m='193429'>if</span> <span m='193782'>there's</span>
  <span m='194135'>a</span> <span m='194488'>pending</span> <span m='194840'>interrupt</span>
  <span m='195193'>from</span> <span m='195546'>the</span> <span m='195899'>keyboard,</span>
  <span m='196251'>the</span> <span m='196604'>device</span> <span m='196957'>interrupt</span>
  <span m='197310'>will</span> <span m='197720'>supersede</span> <span m='198131'>the</span>
  <span m='198542'>execution</span> <span m='198952'>of</span> <span m='199363'>the</span>
  <span m='199774'>ReadKey()</span> <span m='200185'>and</span> <span m='200595'>the</span>
  <span m='201006'>keyboard</span> <span m='201417'>buffer</span> <span m='201827'>will</span>
  <span m='202238'>be</span> <span m='202649'>filled.</span> </p><p><span m='203060'>When</span>
  <span m='203521'>the</span> <span m='203983'>keyboard</span> <span m='204444'>interrupt</span>
  <span m='204906'>handler</span> <span m='205367'>finishes,</span> <span m='205829'>the</span>
  <span m='206290'>ReadKey()</span> <span m='206752'>SVC</span> <span m='207213'>will</span>
  <span m='207675'>be</span> <span m='208136'>executed</span> <span m='208598'>again,</span>
  <span m='209060'>this</span> <span m='209460'>time</span> <span m='209860'>finding</span>
  <span m='210260'>that</span> <span m='210660'>the</span> <span m='211060'>buffer</span>
  <span m='211460'>is</span> <span m='211860'>no</span> <span m='212260'>longer</span>
  <span m='212660'>empty.</span> </p><p><span m='213060'>Yah!</span> </p><p><span
  m='214650'>So</span> <span m='215071'>this</span> <span m='215493'>version</span>
  <span m='215914'>of</span> <span m='216336'>the</span> <span m='216757'>handler</span>
  <span m='217179'>actually</span> <span m='217601'>works,</span> <span m='218022'>with</span>
  <span m='218444'>one</span> <span m='218865'>small</span> <span m='219287'>caveat.</span>
  </p><p><span m='219709'>If</span> <span m='220160'>the</span> <span m='220612'>buffer</span>
  <span m='221063'>is</span> <span m='221515'>empty,</span> <span m='221966'>the</span>
  <span m='222418'>user-mode</span> <span m='222869'>program</span> <span m='223321'>will</span>
  <span m='223772'>continually</span> <span m='224224'>re-execute</span> <span m='224675'>the</span>
  <span m='225127'>complicated</span> <span m='225579'>user-mode/kernel-mode</span>
  <span m='226072'>loop</span> <span m='226565'>until</span> <span m='227058'>the</span>
  <span m='227551'>timer</span> <span m='228044'>interrupt</span> <span m='228537'>eventually</span>
  <span m='229030'>transfers</span> <span m='229523'>control</span> <span m='230016'>to</span>
  <span m='230510'>the</span> <span m='231270'>next</span> <span m='232030'>process.</span>
  </p><p><span m='232790'>This</span> <span m='233362'>seems</span> <span m='233934'>pretty</span>
  <span m='234506'>inefficient.</span> </p><p><span m='235079'>Once</span> <span m='235361'>we've</span>
  <span m='235644'>checked</span> <span m='235926'>and</span> <span m='236209'>found</span>
  <span m='236491'>the</span> <span m='236774'>buffer</span> <span m='237056'>empty,</span>
  <span m='237339'>it</span> <span m='237621'>would</span> <span m='237904'>be</span>
  <span m='238186'>better</span> <span m='238469'>to</span> <span m='238751'>give</span>
  <span m='239034'>other</span> <span m='239316'>processes</span> <span m='239599'>a</span>
  <span m='240000'>chance</span> <span m='240401'>to</span> <span m='240803'>run</span>
  <span m='241204'>before</span> <span m='241605'>we</span> <span m='242007'>try</span>
  <span m='242408'>again.</span> </p><p><span m='242810'>This</span> <span m='243084'>problem</span>
  <span m='243359'>is</span> <span m='243634'>easy</span> <span m='243909'>to</span>
  <span m='244184'>fix!</span> </p><p><span m='244459'>We'll</span> <span m='244814'>just</span>
  <span m='245170'>add</span> <span m='245526'>a</span> <span m='245881'>call</span>
  <span m='246237'>to</span> <span m='246593'>Scheduler()</span> <span m='246948'>right</span>
  <span m='247304'>after</span> <span m='247660'>arranging</span> <span m='248015'>for</span>
  <span m='248371'>the</span> <span m='248727'>ReadKey()</span> <span m='249082'>SVC</span>
  <span m='249438'>to</span> <span m='249794'>be</span> <span m='250150'>re-executed.</span>
  </p><p><span m='252169'>The</span> <span m='252500'>call</span> <span m='252832'>to</span>
  <span m='253163'>Scheduler()</span> <span m='253495'>suspends</span> <span m='253826'>execution</span>
  <span m='254158'>of</span> <span m='254489'>the</span> <span m='254821'>current</span>
  <span m='255152'>process</span> <span m='255484'>and</span> <span m='255815'>arranges</span>
  <span m='256147'>for</span> <span m='256478'>the</span> <span m='256810'>next</span>
  <span m='257337'>process</span> <span m='257864'>to</span> <span m='258392'>run</span>
  <span m='258919'>when</span> <span m='259446'>the</span> <span m='259974'>handler</span>
  <span m='260501'>exits.</span> </p><p><span m='261029'>Eventually</span> <span m='261353'>the</span>
  <span m='261677'>round-robin</span> <span m='262001'>scheduling</span> <span m='262326'>will</span>
  <span m='262650'>come</span> <span m='262974'>back</span> <span m='263299'>to</span>
  <span m='263623'>the</span> <span m='263947'>current</span> <span m='264271'>process</span>
  <span m='264596'>and</span> <span m='264920'>the</span> <span m='265244'>ReadKey()</span>
  <span m='265569'>SVC</span> <span m='266286'>will</span> <span m='267004'>try</span>
  <span m='267722'>again.</span> </p><p><span m='268440'>With</span> <span m='268804'>this</span>
  <span m='269169'>simple</span> <span m='269533'>one-line</span> <span m='269898'>fix</span>
  <span m='270263'>the</span> <span m='270627'>system</span> <span m='270992'>will</span>
  <span m='271356'>spend</span> <span m='271721'>much</span> <span m='272086'>less</span>
  <span m='272450'>time</span> <span m='272815'>wasting</span> <span m='273179'>cycles</span>
  <span m='273544'>checking</span> <span m='273909'>the</span> <span m='274366'>empty</span>
  <span m='274823'>buffer</span> <span m='275281'>and</span> <span m='275738'>instead</span>
  <span m='276196'>use</span> <span m='276653'>those</span> <span m='277110'>cycles</span>
  <span m='277568'>to</span> <span m='278025'>run</span> <span m='278483'>other,</span>
  <span m='278940'>hopefully</span> <span m='279397'>more</span> <span m='279855'>productive,</span>
  <span m='280312'>processes.</span> </p><p><span m='280770'>The</span> <span m='281093'>cost</span>
  <span m='281416'>is</span> <span m='281740'>a</span> <span m='282063'>small</span>
  <span m='282386'>delay</span> <span m='282710'>in</span> <span m='283033'>restarting</span>
  <span m='283356'>the</span> <span m='283680'>program</span> <span m='284003'>after</span>
  <span m='284326'>a</span> <span m='284650'>character</span> <span m='284973'>is</span>
  <span m='285296'>typed,</span> <span m='285620'>but</span> <span m='285967'>typically</span>
  <span m='286315'>the</span> <span m='286662'>time</span> <span m='287010'>slices</span>
  <span m='287357'>for</span> <span m='287705'>each</span> <span m='288052'>process</span>
  <span m='288400'>are</span> <span m='288747'>small</span> <span m='289095'>enough</span>
  <span m='289442'>that</span> <span m='289790'>one</span> <span m='290137'>round</span>
  <span m='290485'>of</span> <span m='290832'>process</span> <span m='291180'>execution</span>
  <span m='291557'>happens</span> <span m='291934'>more</span> <span m='292311'>quickly</span>
  <span m='292688'>than</span> <span m='293065'>the</span> <span m='293442'>time</span>
  <span m='293820'>between</span> <span m='294197'>two</span> <span m='294574'>typed</span>
  <span m='294951'>characters,</span> <span m='295328'>so</span> <span m='295705'>the</span>
  <span m='296082'>extra</span> <span m='296460'>delay</span> <span m='297206'>isn't</span>
  <span m='297952'>noticeable.</span> </p><p><span m='298699'>So</span> <span m='299150'>now</span>
  <span m='299602'>we</span> <span m='300053'>have</span> <span m='300505'>some</span>
  <span m='300956'>insights</span> <span m='301408'>into</span> <span m='301859'>one</span>
  <span m='302311'>of</span> <span m='302762'>the</span> <span m='303214'>traditional</span>
  <span m='303665'>arguments</span> <span m='304117'>against</span> <span m='304568'>timesharing.</span>
  </p><p><span m='305020'>The</span> <span m='305452'>argument</span> <span m='305884'>goes</span>
  <span m='306316'>as</span> <span m='306748'>follows.</span> </p><p><span m='307180'>Suppose</span>
  <span m='307622'>we</span> <span m='308065'>have</span> <span m='308508'>10</span>
  <span m='308950'>processes,</span> <span m='309393'>each</span> <span m='309836'>of</span>
  <span m='310278'>which</span> <span m='310721'>takes</span> <span m='311164'>1</span>
  <span m='311606'>second</span> <span m='312049'>to</span> <span m='312492'>complete</span>
  <span m='312934'>its</span> <span m='313377'>computation.</span> </p><p><span m='313820'>Without</span>
  <span m='314155'>timesharing,</span> <span m='314490'>the</span> <span m='314825'>first</span>
  <span m='315161'>process</span> <span m='315496'>would</span> <span m='315831'>be</span>
  <span m='316166'>done</span> <span m='316502'>after</span> <span m='316837'>1</span>
  <span m='317172'>second,</span> <span m='317507'>the</span> <span m='317843'>second</span>
  <span m='318178'>after</span> <span m='318513'>2</span> <span m='318849'>seconds,</span>
  <span m='319569'>and</span> <span m='320289'>so</span> <span m='321009'>on.</span>
  </p><p><span m='321730'>With</span> <span m='322152'>timesharing</span> <span m='322575'>using,</span>
  <span m='322998'>say,</span> <span m='323421'>a</span> <span m='323844'>1/10</span>
  <span m='324267'>second</span> <span m='324690'>time</span> <span m='325112'>slice,</span>
  <span m='325535'>all</span> <span m='325958'>the</span> <span m='326381'>processes</span>
  <span m='326804'>will</span> <span m='327227'>complete</span> <span m='327650'>sometime</span>
  <span m='328001'>after</span> <span m='328353'>10</span> <span m='328705'>seconds</span>
  <span m='329056'>since</span> <span m='329408'>there's</span> <span m='329760'>a</span>
  <span m='330111'>little</span> <span m='330463'>extra</span> <span m='330815'>time</span>
  <span m='331166'>needed</span> <span m='331518'>for</span> <span m='331870'>the</span>
  <span m='332312'>hundred</span> <span m='332755'>or</span> <span m='333198'>so</span>
  <span m='333640'>process</span> <span m='334083'>switches</span> <span m='334526'>that</span>
  <span m='334969'>would</span> <span m='335411'>happen</span> <span m='335854'>before</span>
  <span m='336297'>completion.</span> </p><p><span m='336740'>So</span> <span m='337137'>in</span>
  <span m='337534'>a</span> <span m='337931'>timesharing</span> <span m='338329'>system</span>
  <span m='338726'>the</span> <span m='339123'>time-to-completion</span> <span m='339520'>for</span>
  <span m='339918'>*all*</span> <span m='340315'>processes</span> <span m='340712'>is</span>
  <span m='341109'>as</span> <span m='341507'>long</span> <span m='341904'>the</span>
  <span m='342301'>worst-case</span> <span m='342699'>completion</span> <span m='343371'>time</span>
  <span m='344043'>without</span> <span m='344715'>time</span> <span m='345387'>sharing!</span>
  </p><p><span m='346060'>So</span> <span m='346602'>why</span> <span m='347144'>bother</span>
  <span m='347686'>with</span> <span m='348228'>timesharing?</span> </p><p><span m='348770'>We</span>
  <span m='349061'>saw</span> <span m='349353'>one</span> <span m='349645'>answer</span>
  <span m='349937'>to</span> <span m='350229'>this</span> <span m='350520'>question</span>
  <span m='350812'>earlier</span> <span m='351104'>in</span> <span m='351396'>this</span>
  <span m='351688'>slide.</span> </p><p><span m='351980'>If</span> <span m='352321'>a</span>
  <span m='352662'>process</span> <span m='353003'>can't</span> <span m='353344'>make</span>
  <span m='353685'>productive</span> <span m='354027'>use</span> <span m='354368'>of</span>
  <span m='354709'>its</span> <span m='355050'>time</span> <span m='355391'>slice,</span>
  <span m='355733'>it</span> <span m='356074'>can</span> <span m='356415'>donate</span>
  <span m='356756'>those</span> <span m='357097'>cycles</span> <span m='357439'>to</span>
  <span m='357894'>completion</span> <span m='358349'>of</span> <span m='358804'>some</span>
  <span m='359259'>other</span> <span m='359714'>task.</span> </p><p><span m='360169'>So</span>
  <span m='360475'>in</span> <span m='360782'>a</span> <span m='361088'>system</span>
  <span m='361395'>where</span> <span m='361701'>most</span> <span m='362008'>processes</span>
  <span m='362314'>are</span> <span m='362621'>waiting</span> <span m='362927'>for</span>
  <span m='363234'>some</span> <span m='363540'>sort</span> <span m='363847'>of</span>
  <span m='364153'>I/O,</span> <span m='364460'>timesharing</span> <span m='364766'>is</span>
  <span m='365073'>actually</span> <span m='365380'>a</span> <span m='365689'>great</span>
  <span m='365998'>way</span> <span m='366307'>of</span> <span m='366616'>spending</span>
  <span m='366925'>cycles</span> <span m='367235'>where</span> <span m='367544'>they'll</span>
  <span m='367853'>do</span> <span m='368162'>the</span> <span m='368471'>most</span>
  <span m='368780'>good.</span> </p><p><span m='369090'>If</span> <span m='369466'>you</span>
  <span m='369842'>open</span> <span m='370219'>the</span> <span m='370595'>Task</span>
  <span m='370972'>Manager</span> <span m='371348'>or</span> <span m='371725'>Activity</span>
  <span m='372101'>Monitor</span> <span m='372478'>on</span> <span m='372854'>the</span>
  <span m='373231'>system</span> <span m='373607'>you're</span> <span m='373984'>using</span>
  <span m='374360'>now,</span> <span m='374737'>you'll</span> <span m='375113'>see</span>
  <span m='375490'>there</span> <span m='375848'>are</span> <span m='376206'>hundreds</span>
  <span m='376564'>of</span> <span m='376922'>processes,</span> <span m='377280'>almost</span>
  <span m='377638'>all</span> <span m='377996'>of</span> <span m='378355'>which</span>
  <span m='378713'>are</span> <span m='379071'>in</span> <span m='379429'>some</span>
  <span m='379787'>sort</span> <span m='380145'>of</span> <span m='380503'>I/O</span>
  <span m='380861'>wait.</span> </p><p><span m='381220'>So</span> <span m='381633'>timesharing</span>
  <span m='382046'>does</span> <span m='382459'>extract</span> <span m='382872'>a</span>
  <span m='383285'>cost</span> <span m='383698'>when</span> <span m='384111'>running</span>
  <span m='384524'>compute-intensive</span> <span m='384937'>computations,</span>
  <span m='385350'>but</span> <span m='385763'>in</span> <span m='386176'>an</span>
  <span m='386590'>actual</span> <span m='386922'>system</span> <span m='387254'>where</span>
  <span m='387587'>there's</span> <span m='387919'>a</span> <span m='388251'>mix</span>
  <span m='388584'>of</span> <span m='388916'>I/O</span> <span m='389248'>and</span>
  <span m='389581'>compute</span> <span m='389913'>tasks,</span> <span m='390245'>time</span>
  <span m='390578'>sharing</span> <span m='390910'>is</span> <span m='391242'>the</span>
  <span m='391575'>way</span> <span m='391907'>to</span> <span m='392240'>go.</span>
  </p><p><span m='393240'>We</span> <span m='393527'>can</span> <span m='393815'>actually</span>
  <span m='394102'>go</span> <span m='394390'>one</span> <span m='394677'>step</span>
  <span m='394965'>further</span> <span m='395253'>to</span> <span m='395540'>ensure</span>
  <span m='395828'>we</span> <span m='396115'>don't</span> <span m='396403'>run</span>
  <span m='396691'>processes</span> <span m='396978'>waiting</span> <span m='397266'>for</span>
  <span m='397553'>an</span> <span m='397841'>I/O</span> <span m='398129'>event</span>
  <span m='398563'>that</span> <span m='398997'>hasn't</span> <span m='399431'>yet</span>
  <span m='399865'>happened.</span> </p><p><span m='400300'>We'll</span> <span m='400706'>add</span>
  <span m='401112'>a</span> <span m='401518'>status</span> <span m='401925'>field</span>
  <span m='402331'>to</span> <span m='402737'>the</span> <span m='403143'>process</span>
  <span m='403550'>state</span> <span m='403956'>indicating</span> <span m='404362'>whether</span>
  <span m='404768'>the</span> <span m='405175'>process</span> <span m='405581'>is</span>
  <span m='405987'>ACTIVE</span> <span m='406393'>(e.g.,</span> <span m='406800'>status</span>
  <span m='407333'>is</span> <span m='407866'>0)</span> <span m='408399'>or</span>
  <span m='408932'>WAITING</span> <span m='409466'>(e.g.,</span> <span m='409999'>status</span>
  <span m='410532'>is</span> <span m='411065'>non-zero).</span> </p><p><span m='411599'>We'll</span>
  <span m='412036'>use</span> <span m='412474'>different</span> <span m='412912'>non-zero</span>
  <span m='413350'>values</span> <span m='413788'>to</span> <span m='414226'>indicate</span>
  <span m='414664'>what</span> <span m='415101'>event</span> <span m='415539'>the</span>
  <span m='415977'>process</span> <span m='416415'>is</span> <span m='416853'>waiting</span>
  <span m='417291'>for.</span> </p><p><span m='417729'>Then</span> <span m='418146'>we'll</span>
  <span m='418563'>change</span> <span m='418980'>the</span> <span m='419397'>Scheduler()</span>
  <span m='419814'>to</span> <span m='420231'>only</span> <span m='420648'>run</span>
  <span m='421065'>ACTIVE</span> <span m='421482'>processes.</span> </p><p><span m='421900'>To</span>
  <span m='422211'>see</span> <span m='422523'>how</span> <span m='422834'>this</span>
  <span m='423146'>works,</span> <span m='423457'>it's</span> <span m='423769'>easiest</span>
  <span m='424081'>to</span> <span m='424392'>use</span> <span m='424704'>a</span>
  <span m='425015'>concrete</span> <span m='425327'>example.</span> </p><p><span m='425639'>The</span>
  <span m='426095'>UNIX</span> <span m='426551'>OS</span> <span m='427007'>has</span>
  <span m='427464'>two</span> <span m='427920'>kernel</span> <span m='428376'>subroutines,</span>
  <span m='428833'>sleep()</span> <span m='429289'>and</span> <span m='429745'>wakeup(),</span>
  <span m='430202'>both</span> <span m='430658'>of</span> <span m='431114'>which</span>
  <span m='431571'>require</span> <span m='432027'>a</span> <span m='432483'>non-zero</span>
  <span m='432940'>argument.</span> </p><p><span m='434099'>The</span> <span m='434438'>argument</span>
  <span m='434777'>will</span> <span m='435116'>be</span> <span m='435455'>used</span>
  <span m='435794'>as</span> <span m='436134'>the</span> <span m='436473'>value</span>
  <span m='436812'>of</span> <span m='437151'>the</span> <span m='437490'>status</span>
  <span m='437829'>field.</span> </p><p><span m='438169'>Let's</span> <span m='438523'>see</span>
  <span m='438877'>this</span> <span m='439231'>in</span> <span m='439585'>action.</span>
  </p><p><span m='439940'>When</span> <span m='440294'>the</span> <span m='440648'>ReadKey()</span>
  <span m='441002'>SVC</span> <span m='441356'>detects</span> <span m='441710'>the</span>
  <span m='442064'>buffer</span> <span m='442418'>is</span> <span m='442772'>empty,</span>
  <span m='443126'>it</span> <span m='443480'>calls</span> <span m='443834'>sleep()</span>
  <span m='444188'>with</span> <span m='444542'>an</span> <span m='444896'>argument</span>
  <span m='445250'>that</span> <span m='445576'>uniquely</span> <span m='445902'>identifies</span>
  <span m='446228'>the</span> <span m='446554'>I/O</span> <span m='446880'>event</span>
  <span m='447207'>it's</span> <span m='447533'>waiting</span> <span m='447859'>for,</span>
  <span m='448185'>in</span> <span m='448511'>this</span> <span m='448838'>case</span>
  <span m='449164'>the</span> <span m='449490'>arrival</span> <span m='449816'>of</span>
  <span m='450142'>a</span> <span m='450469'>character</span> <span m='450835'>in</span>
  <span m='451201'>a</span> <span m='451567'>particular</span> <span m='451933'>buffer.</span>
  </p><p><span m='452300'>sleep()</span> <span m='452764'>sets</span> <span m='453229'>the</span>
  <span m='453694'>process</span> <span m='454159'>status</span> <span m='454624'>to</span>
  <span m='455089'>this</span> <span m='455554'>unique</span> <span m='456019'>identifier,</span>
  <span m='456484'>then</span> <span m='456949'>calls</span> <span m='457414'>Scheduler().</span>
  </p><p><span m='457879'>Scheduler()</span> <span m='458352'>has</span> <span m='458826'>been</span>
  <span m='459299'>modified</span> <span m='459773'>to</span> <span m='460246'>skip</span>
  <span m='460720'>over</span> <span m='461194'>processes</span> <span m='461667'>with</span>
  <span m='462141'>a</span> <span m='462614'>non-zero</span> <span m='463088'>status,</span>
  <span m='463561'>not</span> <span m='464035'>giving</span> <span m='464509'>them</span>
  <span m='464825'>a</span> <span m='465141'>chance</span> <span m='465457'>to</span>
  <span m='465773'>run.</span> </p><p><span m='466090'>Meanwhile,</span> <span m='466462'>a</span>
  <span m='466834'>keyboard</span> <span m='467206'>interrupt</span> <span m='467578'>will</span>
  <span m='467950'>cause</span> <span m='468322'>the</span> <span m='468695'>interrupt</span>
  <span m='469067'>handler</span> <span m='469439'>to</span> <span m='469811'>add</span>
  <span m='470183'>a</span> <span m='470555'>character</span> <span m='470927'>to</span>
  <span m='471300'>the</span> <span m='471750'>keyboard</span> <span m='472200'>buffer</span>
  <span m='472650'>and</span> <span m='473100'>call</span> <span m='473550'>wakeup()</span>
  <span m='474000'>to</span> <span m='474450'>signal</span> <span m='474900'>any</span>
  <span m='475350'>process</span> <span m='475800'>waiting</span> <span m='476250'>on</span>
  <span m='476700'>that</span> <span m='477150'>buffer.</span> </p><p><span m='477600'>Watch</span>
  <span m='477923'>what</span> <span m='478246'>happens</span> <span m='478569'>when</span>
  <span m='478893'>the</span> <span m='479216'>kbdnum</span> <span m='479539'>in</span>
  <span m='479862'>the</span> <span m='480186'>interrupt</span> <span m='480509'>handler</span>
  <span m='480832'>matches</span> <span m='481155'>the</span> <span m='481479'>kbdnum</span>
  <span m='481802'>in</span> <span m='482125'>the</span> <span m='482449'>ReadKey()</span>
  <span m='483459'>handler.</span> </p><p><span m='484470'>wakeup()</span> <span m='484850'>loops</span>
  <span m='485231'>through</span> <span m='485612'>all</span> <span m='485992'>processes,</span>
  <span m='486373'>looking</span> <span m='486754'>for</span> <span m='487135'>ones</span>
  <span m='487515'>that</span> <span m='487896'>are</span> <span m='488277'>waiting</span>
  <span m='488657'>for</span> <span m='489038'>this</span> <span m='489419'>particular</span>
  <span m='489800'>I/O</span> <span m='490469'>event.</span> </p><p><span m='491139'>When</span>
  <span m='491524'>it</span> <span m='491909'>finds</span> <span m='492295'>one,</span>
  <span m='492680'>it</span> <span m='493065'>sets</span> <span m='493451'>the</span>
  <span m='493836'>status</span> <span m='494221'>for</span> <span m='494607'>the</span>
  <span m='494992'>process</span> <span m='495377'>to</span> <span m='495763'>zero,</span>
  <span m='496148'>marking</span> <span m='496533'>it</span> <span m='496919'>as</span>
  <span m='497304'>ACTIVE.</span> </p><p><span m='497690'>The</span> <span m='497990'>zero</span>
  <span m='498291'>status</span> <span m='498592'>will</span> <span m='498892'>cause</span>
  <span m='499193'>the</span> <span m='499494'>process</span> <span m='499794'>to</span>
  <span m='500095'>run</span> <span m='500396'>again</span> <span m='500696'>next</span>
  <span m='500997'>time</span> <span m='501298'>the</span> <span m='501598'>Scheduler()</span>
  <span m='501899'>reaches</span> <span m='502200'>it</span> <span m='502538'>in</span>
  <span m='502877'>its</span> <span m='503216'>round-robin</span> <span m='503555'>search</span>
  <span m='503894'>for</span> <span m='504233'>things</span> <span m='504572'>to</span>
  <span m='504911'>do.</span> </p><p><span m='505250'>The</span> <span m='505608'>effect</span>
  <span m='505966'>is</span> <span m='506324'>that</span> <span m='506682'>once</span>
  <span m='507041'>a</span> <span m='507399'>process</span> <span m='507757'>goes</span>
  <span m='508115'>to</span> <span m='508474'>sleep()</span> <span m='508832'>WAITING</span>
  <span m='509190'>for</span> <span m='509548'>an</span> <span m='509907'>event,</span>
  <span m='510265'>it's</span> <span m='510623'>not</span> <span m='510981'>considered</span>
  <span m='511340'>for</span> <span m='511798'>execution</span> <span m='512257'>again</span>
  <span m='512715'>until</span> <span m='513174'>the</span> <span m='513632'>event</span>
  <span m='514091'>occurs</span> <span m='514550'>and</span> <span m='515008'>wakeup()</span>
  <span m='515467'>marks</span> <span m='515925'>the</span> <span m='516384'>process</span>
  <span m='516842'>as</span> <span m='517301'>ACTIVE.</span> </p><p><span m='517760'>Pretty</span>
  <span m='518570'>neat!</span> </p><p><span m='519380'>Another</span> <span m='519783'>elegant</span>
  <span m='520187'>fix</span> <span m='520590'>to</span> <span m='520994'>ensure</span>
  <span m='521397'>that</span> <span m='521801'>no</span> <span m='522204'>CPU</span>
  <span m='522608'>cycles</span> <span m='523011'>are</span> <span m='523415'>wasted</span>
  <span m='523818'>on</span> <span m='524222'>useless</span> <span m='524625'>activity.</span>
  </p><p><span m='525029'>I</span> <span m='525335'>can</span> <span m='525641'>remember</span>
  <span m='525947'>how</span> <span m='526253'>impressed</span> <span m='526559'>I</span>
  <span m='526866'>was</span> <span m='527172'>when</span> <span m='527478'>I</span>
  <span m='527784'>first</span> <span m='528090'>saw</span> <span m='528396'>this</span>
  <span m='528703'>many</span> <span m='529009'>years</span> <span m='529315'>ago</span>
  <span m='529621'>in</span> <span m='529927'>a</span> <span m='530233'>(very)</span>
  <span m='530540'>early</span> <span m='530722'>version</span> <span m='530905'>of</span>
  <span m='531088'>the</span> <span m='531270'>UNIX</span> <span m='531453'>code</span>
  <span m='531636'>:)</span> </p>
type: course
uid: 4dcc88e8907834b7c84e64f30d326373

---
None