---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 56QUjMD3xoI
  parent_uid: 3593e58d9545fb3db7d90961e3d584bf
  title: Video-YouTube-Stream
  type: Video
  uid: 0af156831602b1f2686ca97e68fa6bfe
- id: 3Play-3Play YouTube id-Stream
  media_location: 56QUjMD3xoI
  parent_uid: 3593e58d9545fb3db7d90961e3d584bf
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: dd4127837597ac5a2369fadce3a437c6
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/56QUjMD3xoI/default.jpg
  parent_uid: 3593e58d9545fb3db7d90961e3d584bf
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 17ac983b6a9631cdc613bc127a8bbb83
- id: 56QUjMD3xoI.srt
  parent_uid: 3593e58d9545fb3db7d90961e3d584bf
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v2/pipelined-circuits-6-11-/56QUjMD3xoI.srt
  title: 3play caption file
  type: null
  uid: 3ae5a2a54f712c71d1e089ed9104a4c3
- id: 56QUjMD3xoI.pdf
  parent_uid: 3593e58d9545fb3db7d90961e3d584bf
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v2/pipelined-circuits-6-11-/56QUjMD3xoI.pdf
  title: 3play pdf file
  type: null
  uid: 8b8d920345835709faf76ec95ccc2f84
- id: Caption-3Play YouTube id-SRT
  parent_uid: 3593e58d9545fb3db7d90961e3d584bf
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 1dbee0c95125f2f5ad6ad1f5a6412b09
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 3593e58d9545fb3db7d90961e3d584bf
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 643c4ddf12c151051d4d72e46eae0257
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_07-02-02_300k.mp4
  parent_uid: 3593e58d9545fb3db7d90961e3d584bf
  title: Video-Internet Archive-MP4
  type: Video
  uid: 39624669cb7e428bd20da6b485a1c27c
inline_embed_id: 96557817pipelinedcircuits61127914085
layout: video
order_index: null
parent_uid: d4506fedcfea4f0d5a148d79962565cb
related_resources_text: ''
short_url: pipelined-circuits-6-11-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v2/pipelined-circuits-6-11-
template_type: Embed
title: Pipelined Circuits (6:11)
transcript: <p><span m='380'>Okay,</span> <span m='780'>now</span> <span m='1180'>let's</span>
  <span m='1580'>apply</span> <span m='1980'>all</span> <span m='2380'>this</span>
  <span m='2780'>analysis</span> <span m='3180'>to</span> <span m='3580'>improving</span>
  <span m='3980'>the</span> <span m='4380'>performance</span> <span m='4780'>of</span>
  <span m='5180'>our</span> <span m='5580'>circuits.</span> </p><p><span m='5980'>The</span>
  <span m='6406'>latency</span> <span m='6832'>of</span> <span m='7258'>a</span> <span
  m='7684'>combinational</span> <span m='8110'>logic</span> <span m='8536'>circuit</span>
  <span m='8962'>is</span> <span m='9388'>simply</span> <span m='9814'>its</span>
  <span m='10240'>propagation</span> <span m='10666'>delay</span> <span m='11092'>t_PD.</span>
  </p><p><span m='11519'>And</span> <span m='11881'>the</span> <span m='12243'>throughput</span>
  <span m='12605'>is</span> <span m='12967'>just</span> <span m='13329'>1/t_PD</span>
  <span m='13691'>since</span> <span m='14053'>we</span> <span m='14415'>start</span>
  <span m='14777'>processing</span> <span m='15139'>the</span> <span m='15501'>next</span>
  <span m='15863'>input</span> <span m='16225'>only</span> <span m='16587'>after</span>
  <span m='16949'>finishing</span> <span m='17540'>the</span> <span m='18131'>computation</span>
  <span m='18723'>on</span> <span m='19314'>the</span> <span m='19906'>current</span>
  <span m='20497'>input.</span> </p><p><span m='21089'>Consider</span> <span m='21397'>a</span>
  <span m='21706'>combinational</span> <span m='22015'>system</span> <span m='22324'>with</span>
  <span m='22632'>three</span> <span m='22941'>components:</span> <span m='23250'>F,</span>
  <span m='23559'>G,</span> <span m='23867'>and</span> <span m='24176'>H,</span> <span
  m='24485'>where</span> <span m='24794'>F</span> <span m='25102'>and</span> <span
  m='25411'>G</span> <span m='25720'>work</span> <span m='26029'>in</span> <span m='26379'>parallel</span>
  <span m='26729'>to</span> <span m='27079'>produce</span> <span m='27429'>the</span>
  <span m='27779'>inputs</span> <span m='28129'>to</span> <span m='28479'>H.</span>
  <span m='28829'>Using</span> <span m='29179'>this</span> <span m='29529'>timing</span>
  <span m='29879'>diagram</span> <span m='30229'>we</span> <span m='30579'>can</span>
  <span m='30929'>follow</span> <span m='31279'>the</span> <span m='31630'>processing</span>
  <span m='32044'>of</span> <span m='32458'>a</span> <span m='32872'>particular</span>
  <span m='33286'>input</span> <span m='33700'>value</span> <span m='34114'>X.</span>
  <span m='34528'>Sometime</span> <span m='34942'>after</span> <span m='35356'>X</span>
  <span m='35770'>is</span> <span m='36184'>valid</span> <span m='36598'>and</span>
  <span m='37012'>stable,</span> <span m='37426'>the</span> <span m='37840'>F</span>
  <span m='38364'>and</span> <span m='38888'>G</span> <span m='39412'>modules</span>
  <span m='39936'>produce</span> <span m='40460'>their</span> <span m='40984'>outputs</span>
  <span m='41508'>F(X)</span> <span m='42032'>and</span> <span m='42556'>G(X).</span>
  </p><p><span m='43080'>Now</span> <span m='43348'>that</span> <span m='43616'>the</span>
  <span m='43885'>inputs</span> <span m='44153'>to</span> <span m='44421'>H</span>
  <span m='44690'>are</span> <span m='44958'>valid</span> <span m='45226'>and</span>
  <span m='45495'>stable,</span> <span m='45763'>the</span> <span m='46031'>H</span>
  <span m='46300'>module</span> <span m='46568'>will</span> <span m='46836'>produce</span>
  <span m='47105'>the</span> <span m='47373'>system</span> <span m='47641'>output</span>
  <span m='47910'>P(X)</span> <span m='48340'>after</span> <span m='48770'>a</span>
  <span m='49200'>delay</span> <span m='49630'>set</span> <span m='50060'>by</span>
  <span m='50490'>the</span> <span m='50920'>propagation</span> <span m='51350'>delay</span>
  <span m='51780'>of</span> <span m='52210'>H.</span> </p><p><span m='52640'>The</span>
  <span m='52960'>total</span> <span m='53281'>elapsed</span> <span m='53602'>time</span>
  <span m='53922'>from</span> <span m='54243'>valid</span> <span m='54564'>input</span>
  <span m='54884'>to</span> <span m='55205'>valid</span> <span m='55526'>output</span>
  <span m='55846'>is</span> <span m='56167'>determined</span> <span m='56488'>by</span>
  <span m='56808'>the</span> <span m='57129'>propagation</span> <span m='57450'>delays</span>
  <span m='57960'>of</span> <span m='58470'>the</span> <span m='58980'>component</span>
  <span m='59490'>modules.</span> </p><p><span m='60000'>Assuming</span> <span m='60338'>we</span>
  <span m='60677'>use</span> <span m='61015'>those</span> <span m='61354'>modules</span>
  <span m='61692'>as-is,</span> <span m='62031'>we</span> <span m='62369'>can't</span>
  <span m='62708'>make</span> <span m='63046'>any</span> <span m='63385'>improvements</span>
  <span m='63723'>on</span> <span m='64062'>this</span> <span m='64400'>latency.</span>
  </p><p><span m='64739'>But</span> <span m='65404'>what</span> <span m='66069'>about</span>
  <span m='66734'>the</span> <span m='67399'>system's</span> <span m='68064'>throughput?</span>
  </p><p><span m='68729'>Observe</span> <span m='69059'>that</span> <span m='69389'>after</span>
  <span m='69719'>producing</span> <span m='70049'>their</span> <span m='70379'>outputs,</span>
  <span m='70709'>the</span> <span m='71039'>F</span> <span m='71369'>and</span> <span
  m='71699'>G</span> <span m='72029'>modules</span> <span m='72359'>are</span> <span
  m='72689'>sitting</span> <span m='73019'>sitting</span> <span m='73349'>idle,</span>
  <span m='73679'>just</span> <span m='74149'>holding</span> <span m='74619'>their</span>
  <span m='75089'>outputs</span> <span m='75559'>stable</span> <span m='76029'>while</span>
  <span m='76499'>H</span> <span m='76969'>performs</span> <span m='77439'>its</span>
  <span m='77909'>computation.</span> </p><p><span m='78380'>Can</span> <span m='78626'>we</span>
  <span m='78873'>figure</span> <span m='79120'>out</span> <span m='79367'>a</span>
  <span m='79613'>way</span> <span m='79860'>for</span> <span m='80107'>F</span> <span
  m='80354'>and</span> <span m='80601'>G</span> <span m='80847'>to</span> <span m='81094'>get</span>
  <span m='81341'>started</span> <span m='81588'>processing</span> <span m='81835'>the</span>
  <span m='82081'>next</span> <span m='82328'>input</span> <span m='82575'>while</span>
  <span m='82822'>still</span> <span m='83069'>letting</span> <span m='83445'>H</span>
  <span m='83822'>do</span> <span m='84199'>its</span> <span m='84576'>job</span>
  <span m='84952'>on</span> <span m='85329'>the</span> <span m='85706'>first</span>
  <span m='86083'>input?</span> </p><p><span m='86460'>In</span> <span m='86767'>other</span>
  <span m='87074'>words,</span> <span m='87381'>can</span> <span m='87689'>we</span>
  <span m='87996'>divide</span> <span m='88303'>the</span> <span m='88610'>processing</span>
  <span m='88918'>of</span> <span m='89225'>the</span> <span m='89532'>combinational</span>
  <span m='89839'>circuit</span> <span m='90147'>into</span> <span m='90454'>two</span>
  <span m='90761'>stages</span> <span m='91069'>where</span> <span m='91545'>the</span>
  <span m='92022'>first</span> <span m='92498'>stage</span> <span m='92975'>computes</span>
  <span m='93451'>F(X)</span> <span m='93928'>and</span> <span m='94404'>G(X),</span>
  <span m='94881'>and</span> <span m='95357'>the</span> <span m='95834'>second</span>
  <span m='96310'>stage</span> <span m='96787'>computes</span> <span m='97263'>H(X)?</span>
  </p><p><span m='97740'>If</span> <span m='98116'>we</span> <span m='98493'>can,</span>
  <span m='98869'>then</span> <span m='99246'>we</span> <span m='99622'>can</span>
  <span m='99999'>increase</span> <span m='100376'>the</span> <span m='100752'>throughput</span>
  <span m='101129'>of</span> <span m='101505'>the</span> <span m='101882'>system.</span>
  </p><p><span m='102259'>Mr.</span> <span m='102603'>Blue's</span> <span m='102947'>inspiration</span>
  <span m='103291'>is</span> <span m='103635'>to</span> <span m='103979'>use</span>
  <span m='104323'>registers</span> <span m='104667'>to</span> <span m='105011'>hold</span>
  <span m='105356'>the</span> <span m='105700'>values</span> <span m='106044'>F(X)</span>
  <span m='106388'>and</span> <span m='106732'>G(X)</span> <span m='107076'>for</span>
  <span m='107420'>use</span> <span m='107764'>by</span> <span m='108109'>H,</span>
  <span m='108486'>while</span> <span m='108863'>the</span> <span m='109240'>F</span>
  <span m='109617'>and</span> <span m='109994'>G</span> <span m='110371'>modules</span>
  <span m='110749'>start</span> <span m='111126'>working</span> <span m='111503'>on</span>
  <span m='111880'>the</span> <span m='112257'>next</span> <span m='112634'>input</span>
  <span m='113011'>value.</span> </p><p><span m='113389'>To</span> <span m='113675'>make</span>
  <span m='113961'>our</span> <span m='114248'>timing</span> <span m='114534'>analysis</span>
  <span m='114821'>a</span> <span m='115107'>little</span> <span m='115394'>easier,</span>
  <span m='115680'>we'll</span> <span m='115966'>assume</span> <span m='116253'>that</span>
  <span m='116539'>our</span> <span m='116826'>pipelining</span> <span m='117112'>registers</span>
  <span m='117399'>have</span> <span m='117936'>a</span> <span m='118474'>zero</span>
  <span m='119011'>propagation</span> <span m='119549'>delay</span> <span m='120087'>and</span>
  <span m='120624'>setup</span> <span m='121162'>time.</span> </p><p><span m='121700'>The</span>
  <span m='121993'>appropriate</span> <span m='122287'>clock</span> <span m='122580'>period</span>
  <span m='122874'>for</span> <span m='123168'>this</span> <span m='123461'>sequential</span>
  <span m='123755'>circuit</span> <span m='124049'>is</span> <span m='124342'>determined</span>
  <span m='124636'>by</span> <span m='124930'>the</span> <span m='125223'>propagation</span>
  <span m='125517'>delay</span> <span m='125811'>of</span> <span m='126182'>the</span>
  <span m='126554'>slowest</span> <span m='126926'>processing</span> <span m='127298'>stage.</span>
  </p><p><span m='127670'>In</span> <span m='128057'>this</span> <span m='128445'>example,</span>
  <span m='128832'>the</span> <span m='129220'>stage</span> <span m='129608'>with</span>
  <span m='129995'>F</span> <span m='130383'>and</span> <span m='130770'>G</span>
  <span m='131158'>needs</span> <span m='131546'>a</span> <span m='131933'>clock</span>
  <span m='132321'>period</span> <span m='132709'>of</span> <span m='133096'>at</span>
  <span m='133484'>least</span> <span m='133871'>20</span> <span m='134259'>ns</span>
  <span m='134647'>to</span> <span m='135034'>work</span> <span m='135422'>correctly.</span>
  </p><p><span m='135810'>And</span> <span m='136145'>the</span> <span m='136480'>stage</span>
  <span m='136816'>with</span> <span m='137151'>H</span> <span m='137486'>needs</span>
  <span m='137822'>a</span> <span m='138157'>clock</span> <span m='138492'>period</span>
  <span m='138828'>of</span> <span m='139163'>25</span> <span m='139498'>ns</span>
  <span m='139834'>to</span> <span m='140169'>work</span> <span m='140504'>correctly.</span>
  </p><p><span m='140840'>So</span> <span m='141226'>the</span> <span m='141613'>second</span>
  <span m='142000'>stage</span> <span m='142387'>is</span> <span m='142774'>the</span>
  <span m='143161'>slowest</span> <span m='143548'>and</span> <span m='143935'>sets</span>
  <span m='144321'>the</span> <span m='144708'>system</span> <span m='145095'>clock</span>
  <span m='145482'>period</span> <span m='145869'>at</span> <span m='146256'>25</span>
  <span m='146643'>ns.</span> </p><p><span m='147030'>This</span> <span m='147330'>will</span>
  <span m='147631'>be</span> <span m='147932'>our</span> <span m='148233'>general</span>
  <span m='148533'>plan</span> <span m='148834'>for</span> <span m='149135'>increasing</span>
  <span m='149436'>the</span> <span m='149736'>throughput</span> <span m='150037'>of</span>
  <span m='150338'>combinational</span> <span m='150639'>logic:</span> <span m='150940'>we'll</span>
  <span m='151302'>use</span> <span m='151665'>registers</span> <span m='152028'>to</span>
  <span m='152390'>divide</span> <span m='152753'>the</span> <span m='153116'>processing</span>
  <span m='153478'>into</span> <span m='153841'>a</span> <span m='154204'>sequence</span>
  <span m='154566'>of</span> <span m='154929'>stages,</span> <span m='155292'>where</span>
  <span m='155654'>the</span> <span m='156017'>registers</span> <span m='156380'>capture</span>
  <span m='156713'>the</span> <span m='157047'>outputs</span> <span m='157381'>from</span>
  <span m='157715'>one</span> <span m='158048'>processing</span> <span m='158382'>stage</span>
  <span m='158716'>and</span> <span m='159050'>hold</span> <span m='159383'>them</span>
  <span m='159717'>as</span> <span m='160051'>inputs</span> <span m='160385'>for</span>
  <span m='160718'>the</span> <span m='161052'>next</span> <span m='161386'>processing</span>
  <span m='161720'>stage.</span> </p><p><span m='162920'>A</span> <span m='163208'>particular</span>
  <span m='163497'>input</span> <span m='163786'>will</span> <span m='164075'>progress</span>
  <span m='164363'>through</span> <span m='164652'>the</span> <span m='164941'>system</span>
  <span m='165230'>at</span> <span m='165518'>the</span> <span m='165807'>rate</span>
  <span m='166096'>of</span> <span m='166385'>one</span> <span m='166673'>stage</span>
  <span m='166962'>per</span> <span m='167251'>clock</span> <span m='167540'>cycle.</span>
  </p><p><span m='169320'>In</span> <span m='169571'>this</span> <span m='169822'>example,</span>
  <span m='170073'>there</span> <span m='170325'>are</span> <span m='170576'>two</span>
  <span m='170827'>stages</span> <span m='171078'>in</span> <span m='171330'>the</span>
  <span m='171581'>processing</span> <span m='171832'>pipeline</span> <span m='172083'>and</span>
  <span m='172335'>the</span> <span m='172586'>clock</span> <span m='172837'>period</span>
  <span m='173088'>is</span> <span m='173340'>25</span> <span m='173762'>ns,</span>
  <span m='174185'>so</span> <span m='174608'>the</span> <span m='175031'>latency</span>
  <span m='175453'>of</span> <span m='175876'>the</span> <span m='176299'>pipelined</span>
  <span m='176722'>system</span> <span m='177145'>is</span> <span m='177567'>50</span>
  <span m='177990'>ns,</span> <span m='178413'>i.e.,</span> <span m='178836'>the</span>
  <span m='179258'>number</span> <span m='179681'>of</span> <span m='180104'>stages</span>
  <span m='180527'>times</span> <span m='180950'>the</span> <span m='181565'>system's</span>
  <span m='182180'>clock</span> <span m='182795'>period.</span> </p><p><span m='183410'>The</span>
  <span m='183696'>latency</span> <span m='183982'>of</span> <span m='184268'>the</span>
  <span m='184555'>pipeline</span> <span m='184841'>system</span> <span m='185127'>is</span>
  <span m='185413'>a</span> <span m='185700'>little</span> <span m='185986'>longer</span>
  <span m='186272'>than</span> <span m='186558'>the</span> <span m='186845'>latency</span>
  <span m='187131'>of</span> <span m='187417'>the</span> <span m='187703'>unpipelined</span>
  <span m='187990'>system.</span> </p><p><span m='188990'>However,</span> <span m='189450'>the</span>
  <span m='189911'>pipeline</span> <span m='190372'>system</span> <span m='190833'>produces</span>
  <span m='191293'>1</span> <span m='191754'>output</span> <span m='192215'>every</span>
  <span m='192676'>clock</span> <span m='193136'>period,</span> <span m='193597'>or</span>
  <span m='194058'>25</span> <span m='194519'>ns.</span> </p><p><span m='194980'>The</span>
  <span m='195304'>pipeline</span> <span m='195628'>system</span> <span m='195952'>has</span>
  <span m='196277'>considerably</span> <span m='196601'>better</span> <span m='196925'>throughput</span>
  <span m='197250'>at</span> <span m='197574'>the</span> <span m='197898'>cost</span>
  <span m='198222'>of</span> <span m='198547'>a</span> <span m='198871'>small</span>
  <span m='199195'>increase</span> <span m='199520'>in</span> <span m='200735'>latency.</span>
  </p><p><span m='201950'>Pipeline</span> <span m='202374'>diagrams</span> <span m='202799'>help</span>
  <span m='203223'>us</span> <span m='203648'>visualize</span> <span m='204072'>the</span>
  <span m='204497'>operation</span> <span m='204921'>of</span> <span m='205346'>a</span>
  <span m='205770'>pipelined</span> <span m='206195'>system.</span> </p><p><span m='206620'>The</span>
  <span m='206952'>rows</span> <span m='207284'>of</span> <span m='207616'>the</span>
  <span m='207948'>pipeline</span> <span m='208280'>diagram</span> <span m='208612'>represent</span>
  <span m='208944'>the</span> <span m='209276'>pipeline</span> <span m='209608'>stages</span>
  <span m='209940'>and</span> <span m='210272'>the</span> <span m='210604'>columns</span>
  <span m='210936'>are</span> <span m='211268'>successive</span> <span m='211600'>clock</span>
  <span m='212630'>cycles.</span> </p><p><span m='213660'>At</span> <span m='214097'>the</span>
  <span m='214535'>beginning</span> <span m='214973'>of</span> <span m='215411'>clock</span>
  <span m='215849'>cycle</span> <span m='216287'>i</span> <span m='216725'>the</span>
  <span m='217162'>input</span> <span m='217600'>X_i</span> <span m='218038'>becomes</span>
  <span m='218476'>stable</span> <span m='218914'>and</span> <span m='219352'>valid.</span>
  </p><p><span m='219790'>Then</span> <span m='220038'>during</span> <span m='220287'>clock</span>
  <span m='220535'>cycle</span> <span m='220784'>i</span> <span m='221032'>the</span>
  <span m='221281'>F</span> <span m='221529'>and</span> <span m='221778'>G</span>
  <span m='222026'>modules</span> <span m='222275'>process</span> <span m='222523'>that</span>
  <span m='222772'>input</span> <span m='223020'>and</span> <span m='223269'>at</span>
  <span m='223517'>the</span> <span m='223766'>end</span> <span m='224014'>of</span>
  <span m='224263'>the</span> <span m='224511'>cycle</span> <span m='224760'>the</span>
  <span m='225207'>results</span> <span m='225654'>F(X_i)</span> <span m='226101'>and</span>
  <span m='226548'>G(X_i)</span> <span m='226995'>are</span> <span m='227442'>captured</span>
  <span m='227890'>by</span> <span m='228337'>the</span> <span m='228784'>pipeline</span>
  <span m='229231'>registers</span> <span m='229678'>between</span> <span m='230125'>the</span>
  <span m='230572'>first</span> <span m='231020'>and</span> <span m='231683'>second</span>
  <span m='232346'>stages.</span> </p><p><span m='233010'>Then</span> <span m='233378'>in</span>
  <span m='233746'>cycle</span> <span m='234114'>i+1,</span> <span m='234482'>H</span>
  <span m='234851'>uses</span> <span m='235219'>the</span> <span m='235587'>captured</span>
  <span m='235955'>values</span> <span m='236324'>do</span> <span m='236692'>its</span>
  <span m='237060'>share</span> <span m='237428'>of</span> <span m='237797'>the</span>
  <span m='238165'>processing</span> <span m='238533'>of</span> <span m='238901'>X_i.</span>
  </p><p><span m='239270'>And,</span> <span m='239837'>meanwhile,</span> <span m='240404'>the</span>
  <span m='240971'>F</span> <span m='241539'>and</span> <span m='242106'>G</span>
  <span m='242673'>modules</span> <span m='243240'>are</span> <span m='243808'>working</span>
  <span m='244375'>on</span> <span m='244942'>X_i+1.</span> </p><p><span m='245510'>You</span>
  <span m='245859'>can</span> <span m='246208'>see</span> <span m='246558'>that</span>
  <span m='246907'>the</span> <span m='247256'>processing</span> <span m='247606'>for</span>
  <span m='247955'>a</span> <span m='248305'>particular</span> <span m='248654'>input</span>
  <span m='249003'>value</span> <span m='249353'>moves</span> <span m='249702'>diagonally</span>
  <span m='250051'>through</span> <span m='250401'>the</span> <span m='250750'>diagram,</span>
  <span m='251100'>one</span> <span m='251678'>pipeline</span> <span m='252256'>stage</span>
  <span m='252835'>per</span> <span m='253413'>clock</span> <span m='253991'>cycle.</span>
  </p><p><span m='254570'>At</span> <span m='254844'>the</span> <span m='255118'>end</span>
  <span m='255393'>of</span> <span m='255667'>cycle</span> <span m='255942'>i+1,</span>
  <span m='256216'>the</span> <span m='256491'>output</span> <span m='256765'>of</span>
  <span m='257040'>H</span> <span m='257314'>is</span> <span m='257588'>captured</span>
  <span m='257863'>by</span> <span m='258137'>the</span> <span m='258412'>final</span>
  <span m='258686'>pipeline</span> <span m='258961'>register</span> <span m='259235'>and</span>
  <span m='259510'>is</span> <span m='259994'>available</span> <span m='260478'>for</span>
  <span m='260962'>use</span> <span m='261447'>during</span> <span m='261931'>cycle</span>
  <span m='262415'>i+2.</span> </p><p><span m='262900'>The</span> <span m='263210'>total</span>
  <span m='263521'>time</span> <span m='263831'>elapsed</span> <span m='264142'>between</span>
  <span m='264453'>the</span> <span m='264763'>arrival</span> <span m='265074'>of</span>
  <span m='265385'>an</span> <span m='265695'>input</span> <span m='266006'>and</span>
  <span m='266316'>the</span> <span m='266627'>availability</span> <span m='266938'>of</span>
  <span m='267248'>the</span> <span m='267559'>output</span> <span m='267870'>is</span>
  <span m='268716'>two</span> <span m='269563'>cycles.</span> </p><p><span m='270410'>The</span>
  <span m='270882'>processing</span> <span m='271354'>continues</span> <span m='271826'>cycle</span>
  <span m='272299'>after</span> <span m='272771'>cycle,</span> <span m='273243'>producing</span>
  <span m='273716'>a</span> <span m='274188'>new</span> <span m='274660'>output</span>
  <span m='275133'>every</span> <span m='275605'>clock</span> <span m='276077'>cycle.</span>
  </p><p><span m='276550'>Using</span> <span m='276802'>the</span> <span m='277055'>pipeline</span>
  <span m='277308'>diagram</span> <span m='277561'>we</span> <span m='277814'>can</span>
  <span m='278067'>track</span> <span m='278320'>how</span> <span m='278572'>a</span>
  <span m='278825'>particular</span> <span m='279078'>input</span> <span m='279331'>progresses</span>
  <span m='279584'>through</span> <span m='279837'>the</span> <span m='280090'>system</span>
  <span m='280450'>or</span> <span m='280811'>see</span> <span m='281172'>what</span>
  <span m='281533'>all</span> <span m='281893'>the</span> <span m='282254'>stages</span>
  <span m='282615'>are</span> <span m='282976'>doing</span> <span m='283336'>in</span>
  <span m='283697'>any</span> <span m='284058'>particular</span> <span m='284419'>cycle.</span>
  </p><p><span m='284780'>We'll</span> <span m='285265'>define</span> <span m='285750'>a</span>
  <span m='286236'>K-stage</span> <span m='286721'>pipeline</span> <span m='287206'>(or</span>
  <span m='287692'>K-pipeline</span> <span m='288177'>for</span> <span m='288662'>short)</span>
  <span m='289148'>as</span> <span m='289633'>an</span> <span m='290118'>acyclic</span>
  <span m='290604'>circuit</span> <span m='291089'>having</span> <span m='291574'>exactly</span>
  <span m='292060'>K</span> <span m='292511'>registers</span> <span m='292962'>on</span>
  <span m='293413'>every</span> <span m='293864'>path</span> <span m='294315'>from</span>
  <span m='294766'>input</span> <span m='295217'>to</span> <span m='295668'>output.</span>
  </p><p><span m='296120'>An</span> <span m='296653'>unpipelined</span> <span m='297186'>combinational</span>
  <span m='297720'>circuit</span> <span m='298253'>is</span> <span m='298786'>thus</span>
  <span m='299320'>a</span> <span m='299853'>0-stage</span> <span m='300386'>pipeline.</span>
  </p><p><span m='300920'>To</span> <span m='301235'>make</span> <span m='301551'>it</span>
  <span m='301867'>easy</span> <span m='302182'>to</span> <span m='302498'>build</span>
  <span m='302814'>larger</span> <span m='303130'>pipelined</span> <span m='303445'>systems</span>
  <span m='303761'>out</span> <span m='304077'>of</span> <span m='304392'>pipelined</span>
  <span m='304708'>components,</span> <span m='305024'>we'll</span> <span m='305340'>adopt</span>
  <span m='305775'>the</span> <span m='306210'>convention</span> <span m='306646'>that</span>
  <span m='307081'>every</span> <span m='307516'>pipeline</span> <span m='307952'>stage,</span>
  <span m='308387'>and</span> <span m='308822'>hence</span> <span m='309258'>every</span>
  <span m='309693'>K-stage</span> <span m='310128'>pipeline,</span> <span m='310564'>has</span>
  <span m='310999'>a</span> <span m='311434'>register</span> <span m='311870'>on</span>
  <span m='312220'>its</span> <span m='312570'>output.</span> </p><p><span m='312920'>We'll</span>
  <span m='313256'>use</span> <span m='313592'>the</span> <span m='313928'>techniques</span>
  <span m='314264'>we</span> <span m='314600'>learned</span> <span m='314936'>for</span>
  <span m='315272'>analyzing</span> <span m='315608'>the</span> <span m='315944'>timing</span>
  <span m='316280'>of</span> <span m='316616'>sequential</span> <span m='316952'>circuits</span>
  <span m='317288'>to</span> <span m='317624'>ensure</span> <span m='317960'>the</span>
  <span m='318318'>clock</span> <span m='318677'>signal</span> <span m='319036'>common</span>
  <span m='319394'>to</span> <span m='319753'>all</span> <span m='320112'>the</span>
  <span m='320470'>pipeline</span> <span m='320829'>registers</span> <span m='321188'>has</span>
  <span m='321546'>a</span> <span m='321905'>period</span> <span m='322264'>sufficient</span>
  <span m='322622'>to</span> <span m='322981'>ensure</span> <span m='323340'>correct</span>
  <span m='323946'>operation</span> <span m='324552'>of</span> <span m='325158'>each</span>
  <span m='325764'>stage.</span> </p><p><span m='326370'>So</span> <span m='326768'>for</span>
  <span m='327166'>every</span> <span m='327564'>register-to-register</span> <span
  m='327962'>and</span> <span m='328360'>input-to-register</span> <span m='328758'>path,</span>
  <span m='329156'>we</span> <span m='329555'>need</span> <span m='329953'>to</span>
  <span m='330351'>compute</span> <span m='330749'>the</span> <span m='331147'>sum</span>
  <span m='331545'>of</span> <span m='331943'>the</span> <span m='332341'>propagation</span>
  <span m='332740'>delay</span> <span m='333055'>of</span> <span m='333370'>the</span>
  <span m='333686'>input</span> <span m='334001'>register,</span> <span m='334316'>plus</span>
  <span m='334632'>the</span> <span m='334947'>propagation</span> <span m='335262'>delay</span>
  <span m='335578'>of</span> <span m='335893'>the</span> <span m='336208'>combinational</span>
  <span m='336524'>logic,</span> <span m='336839'>plus</span> <span m='337154'>the</span>
  <span m='337470'>setup</span> <span m='337900'>time</span> <span m='338330'>of</span>
  <span m='338760'>the</span> <span m='339190'>output</span> <span m='339620'>register.</span>
  </p><p><span m='340050'>Then</span> <span m='340301'>we'll</span> <span m='340553'>choose</span>
  <span m='340805'>the</span> <span m='341057'>system's</span> <span m='341309'>clock</span>
  <span m='341561'>period</span> <span m='341813'>to</span> <span m='342065'>be</span>
  <span m='342316'>greater</span> <span m='342568'>than</span> <span m='342820'>or</span>
  <span m='343072'>equal</span> <span m='343324'>to</span> <span m='343576'>the</span>
  <span m='343828'>largest</span> <span m='344080'>such</span> <span m='344840'>sum.</span>
  </p><p><span m='345600'>With</span> <span m='345935'>the</span> <span m='346270'>correct</span>
  <span m='346605'>clock</span> <span m='346940'>period</span> <span m='347275'>and</span>
  <span m='347610'>exactly</span> <span m='347945'>K-registers</span> <span m='348280'>along</span>
  <span m='348615'>each</span> <span m='348950'>path</span> <span m='349285'>from</span>
  <span m='349620'>system</span> <span m='349955'>input</span> <span m='350290'>to</span>
  <span m='350643'>system</span> <span m='350996'>output,</span> <span m='351350'>we</span>
  <span m='351703'>are</span> <span m='352056'>guaranteed</span> <span m='352410'>that</span>
  <span m='352763'>the</span> <span m='353116'>K-pipeline</span> <span m='353470'>will</span>
  <span m='353823'>compute</span> <span m='354176'>the</span> <span m='354530'>same</span>
  <span m='354883'>outputs</span> <span m='355236'>as</span> <span m='355590'>the</span>
  <span m='356422'>original</span> <span m='357254'>unpipelined</span> <span m='358086'>combinational</span>
  <span m='358918'>circuit.</span> </p><p><span m='359750'>The</span> <span m='360105'>latency</span>
  <span m='360460'>of</span> <span m='360815'>a</span> <span m='361170'>K-pipeline</span>
  <span m='361525'>is</span> <span m='361880'>K</span> <span m='362235'>times</span>
  <span m='362590'>the</span> <span m='362945'>period</span> <span m='363300'>of</span>
  <span m='363655'>the</span> <span m='364010'>system's</span> <span m='364365'>clock.</span>
  </p><p><span m='364720'>And</span> <span m='365048'>the</span> <span m='365376'>throughput</span>
  <span m='365704'>of</span> <span m='366032'>a</span> <span m='366360'>K-pipeline</span>
  <span m='366688'>is</span> <span m='367016'>the</span> <span m='367345'>frequency</span>
  <span m='367673'>of</span> <span m='368001'>the</span> <span m='368329'>system's</span>
  <span m='368657'>clock,</span> <span m='368985'>i.e.,</span> <span m='369313'>1</span>
  <span m='369641'>over</span> <span m='369970'>the</span> <span m='370243'>clock</span>
  <span m='370516'>period.</span> </p>
type: course
uid: 3593e58d9545fb3db7d90961e3d584bf

---
None