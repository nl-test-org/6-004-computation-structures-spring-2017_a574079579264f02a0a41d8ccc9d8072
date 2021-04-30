---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: CbcJFO6VtsY
  parent_uid: f39caf8c1906426eaaad3ff06ff9d0ab
  title: Video-YouTube-Stream
  type: Video
  uid: 470aa93088b0547855994ab423afcec5
- id: 3Play-3PlayVideoid-MP4
  media_location: '3636264'
  parent_uid: f39caf8c1906426eaaad3ff06ff9d0ab
  title: 3Play-3Play Video id
  type: 3Play
  uid: 90049383a44d829e344bc64e25154d41
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/CbcJFO6VtsY/default.jpg
  parent_uid: f39caf8c1906426eaaad3ff06ff9d0ab
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 5eaef233d1e7440b207e8522fd53341c
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_10-02-02_300k.mp4
  parent_uid: f39caf8c1906426eaaad3ff06ff9d0ab
  title: Video-Internet Archive-MP4
  type: Video
  uid: f534d7fef8b10b6173854f2559537d50
- id: 3636264.srt
  parent_uid: f39caf8c1906426eaaad3ff06ff9d0ab
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c10/c10s2/c10s2v2/symbols-and-labels-4-24-/3636264.srt
  title: 3play caption file
  type: null
  uid: 30981e0016fcc498614a3a504a8d9d73
- id: 3636264.pdf
  parent_uid: f39caf8c1906426eaaad3ff06ff9d0ab
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c10/c10s2/c10s2v2/symbols-and-labels-4-24-/3636264.pdf
  title: 3play pdf file
  type: null
  uid: 0ca3e1fd12fa3b034ed1eb4e0bb691b0
- id: Caption-3Play Video id-SRT
  parent_uid: f39caf8c1906426eaaad3ff06ff9d0ab
  title: Caption-3Play Video id-SRT-English - US
  type: Caption
  uid: 7b26f2354be644ddbea1529f5e32319d
- id: Transcript-3Play Video id-PDF
  parent_uid: f39caf8c1906426eaaad3ff06ff9d0ab
  title: Transcript-3Play Video id-PDF-English - US
  type: Transcript
  uid: 7849eb798b3dd7a91c2cc40483024897
inline_embed_id: 82634956symbolsandlabels42456525080
layout: video
order_index: null
parent_uid: f2e8a07a817f69282d1cbc28bac1771a
related_resources_text: ''
short_url: symbols-and-labels-4-24-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c10/c10s2/c10s2v2/symbols-and-labels-4-24-
template_type: Embed
title: Symbols and Labels (4:24)
transcript: <p><span m='550'>Let's</span> <span m='969'>follow</span> <span m='1388'>along</span>
  <span m='1807'>as</span> <span m='2226'>the</span> <span m='2645'>assembler</span>
  <span m='3064'>processes</span> <span m='3483'>our</span> <span m='3902'>source</span>
  <span m='4321'>file.</span> </p><p><span m='4740'>The</span> <span m='5133'>assembler</span>
  <span m='5527'>maintains</span> <span m='5920'>a</span> <span m='6314'>symbol</span>
  <span m='6707'>table</span> <span m='7101'>that</span> <span m='7495'>maps</span>
  <span m='7888'>symbols</span> <span m='8282'>names</span> <span m='8675'>to</span>
  <span m='9069'>their</span> <span m='9462'>numeric</span> <span m='9856'>values.</span>
  </p><p><span m='10250'>Initially</span> <span m='10635'>the</span> <span m='11020'>symbol</span>
  <span m='11406'>table</span> <span m='11791'>is</span> <span m='12176'>loaded</span>
  <span m='12562'>with</span> <span m='12947'>mappings</span> <span m='13333'>for</span>
  <span m='13718'>all</span> <span m='14103'>the</span> <span m='14489'>register</span>
  <span m='14874'>symbols.</span> </p><p><span m='15260'>The</span> <span m='15713'>assembler</span>
  <span m='16166'>reads</span> <span m='16619'>the</span> <span m='17072'>source</span>
  <span m='17525'>file</span> <span m='17978'>line-by-line,</span> <span m='18431'>defining</span>
  <span m='18884'>symbols</span> <span m='19337'>and</span> <span m='19790'>labels,</span>
  <span m='20243'>expanding</span> <span m='20696'>macros,</span> <span m='21150'>or</span>
  <span m='21581'>evaluating</span> <span m='22012'>expressions</span> <span m='22443'>to</span>
  <span m='22874'>generate</span> <span m='23305'>bytes</span> <span m='23736'>for</span>
  <span m='24167'>the</span> <span m='24598'>output</span> <span m='25029'>array.</span>
  </p><p><span m='25460'>Whenever</span> <span m='25781'>the</span> <span m='26102'>assembler</span>
  <span m='26423'>encounters</span> <span m='26744'>a</span> <span m='27065'>use</span>
  <span m='27387'>of</span> <span m='27708'>a</span> <span m='28029'>symbol</span>
  <span m='28350'>or</span> <span m='28671'>label,</span> <span m='28993'>it's</span>
  <span m='29314'>replaced</span> <span m='29635'>by</span> <span m='29956'>the</span>
  <span m='30277'>corresponding</span> <span m='30599'>numeric</span> <span m='31096'>value</span>
  <span m='31593'>found</span> <span m='32090'>in</span> <span m='32588'>the</span>
  <span m='33085'>symbol</span> <span m='33582'>table.</span> </p><p><span m='34080'>The</span>
  <span m='34403'>first</span> <span m='34726'>line,</span> <span m='35049'>N</span>
  <span m='35372'>=</span> <span m='35695'>12,</span> <span m='36018'>defines</span>
  <span m='36341'>the</span> <span m='36664'>value</span> <span m='36987'>of</span>
  <span m='37311'>the</span> <span m='37634'>symbol</span> <span m='37957'>N</span>
  <span m='38280'>to</span> <span m='38603'>be</span> <span m='38926'>12,</span> <span
  m='39249'>so</span> <span m='39572'>the</span> <span m='39895'>appropriate</span>
  <span m='40219'>entry</span> <span m='40613'>is</span> <span m='41007'>made</span>
  <span m='41402'>in</span> <span m='41796'>the</span> <span m='42191'>symbol</span>
  <span m='42585'>table.</span> </p><p><span m='42980'>Advancing</span> <span m='43337'>to</span>
  <span m='43694'>the</span> <span m='44051'>next</span> <span m='44408'>line,</span>
  <span m='44765'>the</span> <span m='45122'>assembler</span> <span m='45480'>encounters</span>
  <span m='45837'>an</span> <span m='46194'>invocation</span> <span m='46551'>of</span>
  <span m='46908'>the</span> <span m='47265'>ADDC</span> <span m='47622'>macro</span>
  <span m='47980'>with</span> <span m='48601'>the</span> <span m='49222'>arguments</span>
  <span m='49843'>"r31",</span> <span m='50465'>"N",</span> <span m='51086'>and</span>
  <span m='51707'>"r1".</span> </p><p><span m='52329'>As</span> <span m='52636'>we'll</span>
  <span m='52943'>see</span> <span m='53250'>in</span> <span m='53557'>a</span> <span
  m='53865'>couple</span> <span m='54172'>of</span> <span m='54479'>slides,</span>
  <span m='54786'>this</span> <span m='55094'>triggers</span> <span m='55401'>a</span>
  <span m='55708'>series</span> <span m='56015'>of</span> <span m='56322'>nested</span>
  <span m='56630'>macro</span> <span m='56937'>expansions</span> <span m='57244'>that</span>
  <span m='57551'>eventually</span> <span m='57859'>lead</span> <span m='58286'>to</span>
  <span m='58713'>generating</span> <span m='59140'>a</span> <span m='59567'>32-bit</span>
  <span m='59995'>binary</span> <span m='60422'>value</span> <span m='60849'>to</span>
  <span m='61276'>be</span> <span m='61703'>placed</span> <span m='62131'>in</span>
  <span m='62558'>memory</span> <span m='62985'>location</span> <span m='63412'>0.</span>
  </p><p><span m='63840'>The</span> <span m='64182'>32-bit</span> <span m='64525'>value</span>
  <span m='64868'>is</span> <span m='65211'>formatted</span> <span m='65554'>here</span>
  <span m='65897'>to</span> <span m='66240'>show</span> <span m='66582'>the</span>
  <span m='66925'>instruction</span> <span m='67268'>fields</span> <span m='67611'>and</span>
  <span m='67954'>the</span> <span m='68297'>destination</span> <span m='68640'>address</span>
  <span m='69274'>is</span> <span m='69908'>shown</span> <span m='70542'>in</span>
  <span m='71176'>brackets.</span> </p><p><span m='71810'>The</span> <span m='72224'>next</span>
  <span m='72638'>instruction</span> <span m='73052'>is</span> <span m='73467'>processed</span>
  <span m='73881'>in</span> <span m='74295'>the</span> <span m='74710'>same</span>
  <span m='75124'>way,</span> <span m='75538'>generating</span> <span m='75952'>a</span>
  <span m='76367'>second</span> <span m='76781'>32-bit</span> <span m='77195'>word.</span>
  </p><p><span m='77610'>On</span> <span m='77863'>the</span> <span m='78117'>fourth</span>
  <span m='78371'>line,</span> <span m='78625'>the</span> <span m='78879'>label</span>
  <span m='79133'>loop</span> <span m='79387'>is</span> <span m='79641'>defined</span>
  <span m='79895'>to</span> <span m='80148'>have</span> <span m='80402'>the</span>
  <span m='80656'>value</span> <span m='80910'>of</span> <span m='81164'>the</span>
  <span m='81418'>location</span> <span m='81672'>in</span> <span m='81926'>memory</span>
  <span m='82180'>that's</span> <span m='82671'>about</span> <span m='83162'>to</span>
  <span m='83653'>filled,</span> <span m='84144'>in</span> <span m='84635'>this</span>
  <span m='85126'>case,</span> <span m='85617'>location</span> <span m='86108'>8.</span>
  </p><p><span m='86600'>So</span> <span m='86887'>the</span> <span m='87175'>appropriate</span>
  <span m='87463'>entry</span> <span m='87751'>is</span> <span m='88038'>made</span>
  <span m='88326'>in</span> <span m='88614'>the</span> <span m='88902'>symbol</span>
  <span m='89190'>table</span> <span m='89477'>and</span> <span m='89765'>the</span>
  <span m='90053'>MUL</span> <span m='90341'>macro</span> <span m='90628'>is</span>
  <span m='90916'>expanded</span> <span m='91204'>into</span> <span m='91492'>the</span>
  <span m='91780'>32-bit</span> <span m='92252'>word</span> <span m='92725'>to</span>
  <span m='93197'>be</span> <span m='93670'>placed</span> <span m='94142'>in</span>
  <span m='94615'>location</span> <span m='95087'>8.</span> </p><p><span m='95560'>The</span>
  <span m='95974'>assembler</span> <span m='96388'>processes</span> <span m='96802'>the</span>
  <span m='97217'>file</span> <span m='97631'>line-by-line</span> <span m='98045'>until</span>
  <span m='98460'>it</span> <span m='98874'>reaches</span> <span m='99288'>the</span>
  <span m='99702'>end</span> <span m='100117'>of</span> <span m='100531'>the</span>
  <span m='100945'>file.</span> </p><p><span m='101360'>Actually</span> <span m='101622'>the</span>
  <span m='101884'>assembler</span> <span m='102146'>makes</span> <span m='102408'>two</span>
  <span m='102671'>passes</span> <span m='102933'>through</span> <span m='103195'>the</span>
  <span m='103457'>file.</span> </p><p><span m='103720'>On</span> <span m='103953'>the</span>
  <span m='104187'>first</span> <span m='104421'>pass</span> <span m='104655'>it</span>
  <span m='104889'>loads</span> <span m='105123'>the</span> <span m='105357'>symbol</span>
  <span m='105591'>table</span> <span m='105825'>with</span> <span m='106058'>the</span>
  <span m='106292'>values</span> <span m='106526'>from</span> <span m='106760'>all</span>
  <span m='106994'>the</span> <span m='107228'>symbol</span> <span m='107462'>and</span>
  <span m='107696'>label</span> <span m='107930'>definitions.</span> </p><p><span
  m='108930'>Then,</span> <span m='109323'>on</span> <span m='109716'>the</span> <span
  m='110109'>second</span> <span m='110502'>pass,</span> <span m='110895'>it</span>
  <span m='111288'>generates</span> <span m='111681'>the</span> <span m='112074'>binary</span>
  <span m='112467'>output.</span> </p><p><span m='113199'>The</span> <span m='113538'>two-pass</span>
  <span m='113877'>approach</span> <span m='114217'>allows</span> <span m='114556'>a</span>
  <span m='114895'>statement</span> <span m='115235'>to</span> <span m='115574'>refer</span>
  <span m='115913'>to</span> <span m='116253'>symbol</span> <span m='116592'>or</span>
  <span m='116931'>label</span> <span m='117271'>that</span> <span m='117610'>is</span>
  <span m='117949'>defined</span> <span m='118289'>later</span> <span m='118603'>in</span>
  <span m='118918'>the</span> <span m='119232'>file,</span> <span m='119547'>e.g.,</span>
  <span m='119861'>a</span> <span m='120176'>forward</span> <span m='120490'>branch</span>
  <span m='120805'>instruction</span> <span m='121119'>could</span> <span m='121434'>refer</span>
  <span m='121748'>to</span> <span m='122063'>the</span> <span m='122377'>label</span>
  <span m='122692'>for</span> <span m='123006'>an</span> <span m='123321'>instruction</span>
  <span m='123820'>later</span> <span m='124320'>in</span> <span m='124820'>the</span>
  <span m='125320'>program.</span> </p><p><span m='125820'>As</span> <span m='126120'>we</span>
  <span m='126421'>saw</span> <span m='126722'>in</span> <span m='127022'>the</span>
  <span m='127323'>previous</span> <span m='127624'>slide,</span> <span m='127925'>there's</span>
  <span m='128225'>nothing</span> <span m='128526'>magic</span> <span m='128827'>about</span>
  <span m='129127'>the</span> <span m='129428'>register</span> <span m='129729'>symbols.</span>
  </p><p><span m='130030'>They</span> <span m='130442'>are</span> <span m='130855'>just</span>
  <span m='131268'>symbolic</span> <span m='131680'>names</span> <span m='132093'>for</span>
  <span m='132506'>the</span> <span m='132919'>values</span> <span m='133331'>0</span>
  <span m='133744'>through</span> <span m='134157'>31.</span> </p><p><span m='134570'>So</span>
  <span m='135150'>when</span> <span m='135731'>processing</span> <span m='136312'>ADDC(r31,N,r1),</span>
  <span m='136893'>UASM</span> <span m='137473'>replaces</span> <span m='138054'>the</span>
  <span m='138635'>symbols</span> <span m='139216'>with</span> <span m='139796'>their</span>
  <span m='140377'>values</span> <span m='140958'>and</span> <span m='141539'>actually</span>
  <span m='142120'>expands</span> <span m='143295'>ADDC(31,12,1).</span> </p><p><span
  m='144470'>UASM</span> <span m='145575'>is</span> <span m='146680'>very</span> <span
  m='147785'>simple.</span> </p><p><span m='148890'>It</span> <span m='149365'>simply</span>
  <span m='149840'>replaces</span> <span m='150315'>symbols</span> <span m='150790'>with</span>
  <span m='151265'>their</span> <span m='151740'>values,</span> <span m='152215'>expands</span>
  <span m='152690'>macros</span> <span m='153165'>and</span> <span m='153640'>evaluates</span>
  <span m='154115'>expressions.</span> </p><p><span m='154590'>So</span> <span m='154855'>if</span>
  <span m='155120'>you</span> <span m='155385'>use</span> <span m='155650'>a</span>
  <span m='155915'>register</span> <span m='156180'>symbol</span> <span m='156445'>where</span>
  <span m='156710'>a</span> <span m='156975'>numeric</span> <span m='157240'>value</span>
  <span m='157505'>is</span> <span m='157770'>expected,</span> <span m='158035'>the</span>
  <span m='158300'>value</span> <span m='158565'>of</span> <span m='158830'>the</span>
  <span m='159095'>symbol</span> <span m='159361'>is</span> <span m='159804'>used</span>
  <span m='160247'>as</span> <span m='160690'>the</span> <span m='161133'>numeric</span>
  <span m='161576'>constant.</span> </p><p><span m='162020'>Probably</span> <span
  m='162426'>not</span> <span m='162833'>what</span> <span m='163240'>the</span> <span
  m='163646'>programmer</span> <span m='164053'>intended.</span> </p><p><span m='164460'>Similarly,</span>
  <span m='164824'>if</span> <span m='165188'>you</span> <span m='165553'>use</span>
  <span m='165917'>a</span> <span m='166281'>symbol</span> <span m='166646'>or</span>
  <span m='167010'>expression</span> <span m='167375'>where</span> <span m='167739'>a</span>
  <span m='168103'>register</span> <span m='168468'>number</span> <span m='168832'>is</span>
  <span m='169196'>expected,</span> <span m='169561'>the</span> <span m='169925'>low-order</span>
  <span m='170290'>5</span> <span m='170608'>bits</span> <span m='170927'>of</span>
  <span m='171246'>the</span> <span m='171565'>value</span> <span m='171884'>is</span>
  <span m='172203'>used</span> <span m='172522'>as</span> <span m='172841'>the</span>
  <span m='173160'>register</span> <span m='173478'>number,</span> <span m='173797'>in</span>
  <span m='174116'>this</span> <span m='174435'>example,</span> <span m='174754'>as</span>
  <span m='175073'>the</span> <span m='175392'>Rb</span> <span m='175711'>register</span>
  <span m='176030'>number.</span> </p><p><span m='177030'>Again</span> <span m='177560'>probably</span>
  <span m='178090'>not</span> <span m='178620'>what</span> <span m='179150'>the</span>
  <span m='179680'>programmer</span> <span m='180210'>intended.</span> </p><p><span
  m='180740'>The</span> <span m='181044'>moral</span> <span m='181348'>of</span> <span
  m='181652'>the</span> <span m='181956'>story</span> <span m='182260'>is</span> <span
  m='182564'>that</span> <span m='182868'>when</span> <span m='183172'>writing</span>
  <span m='183476'>UASM</span> <span m='183780'>assembly</span> <span m='184084'>language</span>
  <span m='184388'>programs,</span> <span m='184692'>you</span> <span m='184996'>have</span>
  <span m='185300'>to</span> <span m='185605'>keep</span> <span m='185910'>your</span>
  <span m='186215'>wits</span> <span m='186520'>about</span> <span m='186825'>you</span>
  <span m='187130'>and</span> <span m='187435'>recognize</span> <span m='187740'>that</span>
  <span m='188045'>the</span> <span m='188350'>interpretation</span> <span m='188655'>of</span>
  <span m='188960'>an</span> <span m='189265'>operand</span> <span m='189570'>is</span>
  <span m='189875'>determined</span> <span m='190180'>by</span> <span m='190612'>the</span>
  <span m='191045'>opcode</span> <span m='191477'>macro,</span> <span m='191910'>not</span>
  <span m='192342'>by</span> <span m='192775'>the</span> <span m='193207'>way</span>
  <span m='193640'>you</span> <span m='194072'>wrote</span> <span m='194505'>the</span>
  <span m='194937'>operand.</span> </p><p><span m='195370'>Recall</span> <span m='195755'>from</span>
  <span m='196140'>Lecture</span> <span m='196526'>9</span> <span m='196911'>that</span>
  <span m='197296'>branch</span> <span m='197682'>instructions</span> <span m='198067'>use</span>
  <span m='198452'>the</span> <span m='198838'>16-bit</span> <span m='199223'>constant</span>
  <span m='199608'>field</span> <span m='199994'>of</span> <span m='200379'>the</span>
  <span m='200764'>instruction</span> <span m='201150'>to</span> <span m='201430'>encode</span>
  <span m='201711'>the</span> <span m='201991'>address</span> <span m='202272'>of</span>
  <span m='202552'>the</span> <span m='202833'>branch</span> <span m='203114'>target</span>
  <span m='203394'>as</span> <span m='203675'>a</span> <span m='203955'>word</span>
  <span m='204236'>offset</span> <span m='204517'>from</span> <span m='204797'>the</span>
  <span m='205078'>location</span> <span m='205358'>of</span> <span m='205639'>the</span>
  <span m='205920'>branch</span> <span m='206800'>instruction.</span> </p><p><span
  m='207680'>Well,</span> <span m='208126'>actually</span> <span m='208573'>the</span>
  <span m='209020'>offset</span> <span m='209466'>is</span> <span m='209913'>calculated</span>
  <span m='210360'>from</span> <span m='210806'>the</span> <span m='211253'>instruction</span>
  <span m='211700'>immediately</span> <span m='212146'>following</span> <span m='212593'>the</span>
  <span m='213040'>branch,</span> <span m='213474'>so</span> <span m='213908'>an</span>
  <span m='214342'>offset</span> <span m='214776'>of</span> <span m='215210'>-1</span>
  <span m='215645'>would</span> <span m='216079'>refer</span> <span m='216513'>to</span>
  <span m='216947'>the</span> <span m='217381'>branch</span> <span m='217815'>itself.</span>
  </p><p><span m='218250'>The</span> <span m='218519'>calculation</span> <span m='218788'>of</span>
  <span m='219058'>the</span> <span m='219327'>offset</span> <span m='219597'>is</span>
  <span m='219866'>a</span> <span m='220136'>bit</span> <span m='220405'>tedious</span>
  <span m='220675'>to</span> <span m='220944'>do</span> <span m='221213'>by</span>
  <span m='221483'>hand</span> <span m='221752'>and</span> <span m='222022'>would,</span>
  <span m='222291'>of</span> <span m='222561'>course,</span> <span m='222830'>change</span>
  <span m='223100'>if</span> <span m='223497'>we</span> <span m='223895'>added</span>
  <span m='224293'>or</span> <span m='224690'>removed</span> <span m='225088'>instructions</span>
  <span m='225486'>between</span> <span m='225883'>the</span> <span m='226281'>branch</span>
  <span m='226679'>instruction</span> <span m='227076'>and</span> <span m='227474'>branch</span>
  <span m='227872'>target.</span> </p><p><span m='228270'>Happily</span> <span m='228682'>macros</span>
  <span m='229095'>for</span> <span m='229507'>the</span> <span m='229920'>branch</span>
  <span m='230332'>instructions</span> <span m='230745'>incorporate</span> <span m='231157'>the</span>
  <span m='231570'>necessary</span> <span m='231982'>formula</span> <span m='232395'>to</span>
  <span m='232807'>compute</span> <span m='233220'>the</span> <span m='233560'>offset</span>
  <span m='233901'>from</span> <span m='234241'>the</span> <span m='234582'>address</span>
  <span m='234923'>of</span> <span m='235263'>the</span> <span m='235604'>branch</span>
  <span m='235944'>and</span> <span m='236285'>the</span> <span m='236626'>address</span>
  <span m='236966'>of</span> <span m='237307'>the</span> <span m='237647'>branch</span>
  <span m='237988'>target.</span> </p><p><span m='238329'>So</span> <span m='238630'>we</span>
  <span m='238931'>just</span> <span m='239232'>specify</span> <span m='239533'>the</span>
  <span m='239835'>address</span> <span m='240136'>of</span> <span m='240437'>the</span>
  <span m='240738'>branch</span> <span m='241040'>target,</span> <span m='241341'>usually</span>
  <span m='241642'>with</span> <span m='241943'>a</span> <span m='242245'>label,</span>
  <span m='242546'>and</span> <span m='242847'>let</span> <span m='243148'>UASM</span>
  <span m='243450'>do</span> <span m='244095'>the</span> <span m='244740'>heavy</span>
  <span m='245385'>lifting.</span> </p><p><span m='246030'>Here</span> <span m='246392'>we</span>
  <span m='246754'>see</span> <span m='247116'>that</span> <span m='247478'>BNE</span>
  <span m='247840'>branches</span> <span m='248202'>backwards</span> <span m='248564'>by</span>
  <span m='248926'>three</span> <span m='249288'>instructions</span> <span m='249650'>(remember</span>
  <span m='250012'>to</span> <span m='250374'>count</span> <span m='250736'>from</span>
  <span m='251099'>the</span> <span m='251661'>instruction</span> <span m='252224'>following</span>
  <span m='252787'>the</span> <span m='253350'>branch)</span> <span m='253913'>so</span>
  <span m='254476'>the</span> <span m='255039'>offset</span> <span m='255602'>is</span>
  <span m='256165'>-3.</span> </p><p><span m='256728'>The</span> <span m='257078'>16-bit</span>
  <span m='257428'>two's</span> <span m='257778'>complement</span> <span m='258128'>representation</span>
  <span m='258478'>of</span> <span m='258828'>-3</span> <span m='259178'>is</span>
  <span m='259528'>the</span> <span m='259878'>value</span> <span m='260228'>placed</span>
  <span m='260578'>in</span> <span m='260928'>the</span> <span m='261278'>constant</span>
  <span m='261629'>field</span> <span m='261969'>of</span> <span m='262309'>the</span>
  <span m='262649'>BNE</span> <span m='262989'>instruction.</span> </p>
type: course
uid: f39caf8c1906426eaaad3ff06ff9d0ab

---
None