---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: F5-87RM_zHA
  parent_uid: cfa842e7cfd6e679333fea2f43a733d5
  title: Video-YouTube-Stream
  type: Video
  uid: d628751e23b9c9699d0aa42749839c09
- id: 3Play-3Play YouTube id-Stream
  media_location: F5-87RM_zHA
  parent_uid: cfa842e7cfd6e679333fea2f43a733d5
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 878d63626566d3de25dbf98825f795df
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/F5-87RM_zHA/default.jpg
  parent_uid: cfa842e7cfd6e679333fea2f43a733d5
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 33456e28da4b11492ba03db30669d380
- id: F5-87RM_zHA.srt
  parent_uid: cfa842e7cfd6e679333fea2f43a733d5
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/intepretation-and-compilation-9-36-/F5-87RM_zHA.srt
  title: 3play caption file
  type: null
  uid: 95b85f40685c1ac9c094365769d28fc1
- id: F5-87RM_zHA.pdf
  parent_uid: cfa842e7cfd6e679333fea2f43a733d5
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/intepretation-and-compilation-9-36-/F5-87RM_zHA.pdf
  title: 3play pdf file
  type: null
  uid: ba169fc69a7bc4da427df6d701fbda5d
- id: Caption-3Play YouTube id-SRT
  parent_uid: cfa842e7cfd6e679333fea2f43a733d5
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: a63d790564690e1c3055db152188664c
- id: Transcript-3Play YouTube id-PDF
  parent_uid: cfa842e7cfd6e679333fea2f43a733d5
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 9bdfc699b631d396c761f5e0fad4002a
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_11-02-01_300k.mp4
  parent_uid: cfa842e7cfd6e679333fea2f43a733d5
  title: Video-Internet Archive-MP4
  type: Video
  uid: d9bde67343b7d4c6d0ce18c0844bdd8b
inline_embed_id: 15148707intepretationandcompilation93625436760
layout: video
order_index: null
parent_uid: adbecd569a8c9341b3a33ba0d8d47ec7
related_resources_text: ''
short_url: intepretation-and-compilation-9-36-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/intepretation-and-compilation-9-36-
template_type: Embed
title: Intepretation and Compilation (9:36)
transcript: <p><span m='350'>Today</span> <span m='664'>we're</span> <span m='978'>going</span>
  <span m='1292'>to</span> <span m='1606'>talk</span> <span m='1920'>about</span>
  <span m='2234'>how</span> <span m='2548'>to</span> <span m='2862'>translate</span>
  <span m='3176'>high-level</span> <span m='3490'>languages</span> <span m='3804'>into</span>
  <span m='4118'>code</span> <span m='4432'>that</span> <span m='4746'>computers</span>
  <span m='5060'>can</span> <span m='5880'>execute.</span> </p><p><span m='6700'>So</span>
  <span m='7054'>far</span> <span m='7409'>we've</span> <span m='7764'>seen</span>
  <span m='8118'>the</span> <span m='8473'>Beta</span> <span m='8828'>ISA,</span>
  <span m='9182'>which</span> <span m='9537'>includes</span> <span m='9892'>instructions</span>
  <span m='10246'>that</span> <span m='10601'>control</span> <span m='10956'>the</span>
  <span m='11310'>datapath</span> <span m='11665'>operations</span> <span m='12020'>performed</span>
  <span m='12502'>on</span> <span m='12985'>32-bit</span> <span m='13467'>data</span>
  <span m='13950'>stored</span> <span m='14432'>in</span> <span m='14915'>the</span>
  <span m='15397'>registers.</span> </p><p><span m='15880'>There</span> <span m='16221'>are</span>
  <span m='16563'>also</span> <span m='16904'>instructions</span> <span m='17246'>for</span>
  <span m='17587'>accessing</span> <span m='17929'>main</span> <span m='18270'>memory</span>
  <span m='18612'>and</span> <span m='18953'>changing</span> <span m='19295'>the</span>
  <span m='19636'>program</span> <span m='19978'>counter.</span> </p><p><span m='20320'>The</span>
  <span m='20690'>instructions</span> <span m='21060'>are</span> <span m='21430'>formatted</span>
  <span m='21800'>as</span> <span m='22170'>opcode,</span> <span m='22540'>source,</span>
  <span m='22910'>and</span> <span m='23280'>destination</span> <span m='23650'>fields</span>
  <span m='24020'>that</span> <span m='24390'>form</span> <span m='24760'>32-bit</span>
  <span m='25130'>values</span> <span m='25800'>in</span> <span m='26470'>main</span>
  <span m='27140'>memory.</span> </p><p><span m='27810'>To</span> <span m='28128'>make</span>
  <span m='28447'>our</span> <span m='28766'>lives</span> <span m='29084'>easier,</span>
  <span m='29403'>we</span> <span m='29722'>developed</span> <span m='30040'>assembly</span>
  <span m='30359'>language</span> <span m='30678'>as</span> <span m='30996'>a</span>
  <span m='31315'>way</span> <span m='31634'>of</span> <span m='31952'>specifying</span>
  <span m='32271'>sequences</span> <span m='32590'>of</span> <span m='33490'>instructions.</span>
  </p><p><span m='34390'>Each</span> <span m='34855'>assembly</span> <span m='35320'>language</span>
  <span m='35786'>statement</span> <span m='36251'>corresponds</span> <span m='36717'>to</span>
  <span m='37182'>a</span> <span m='37648'>single</span> <span m='38113'>instruction.</span>
  </p><p><span m='38579'>As</span> <span m='38934'>assembly</span> <span m='39289'>language</span>
  <span m='39645'>programmers,</span> <span m='40000'>we're</span> <span m='40355'>responsible</span>
  <span m='40711'>for</span> <span m='41066'>managing</span> <span m='41422'>which</span>
  <span m='41777'>values</span> <span m='42132'>are</span> <span m='42488'>in</span>
  <span m='42843'>registers</span> <span m='43199'>and</span> <span m='43482'>which</span>
  <span m='43766'>are</span> <span m='44049'>in</span> <span m='44333'>main</span>
  <span m='44616'>memory,</span> <span m='44900'>and</span> <span m='45183'>we</span>
  <span m='45467'>need</span> <span m='45750'>to</span> <span m='46034'>figure</span>
  <span m='46317'>out</span> <span m='46601'>how</span> <span m='46884'>to</span>
  <span m='47168'>break</span> <span m='47451'>down</span> <span m='47735'>complicated</span>
  <span m='48019'>operations,</span> <span m='48463'>e.g.,</span> <span m='48907'>accessing</span>
  <span m='49352'>an</span> <span m='49796'>element</span> <span m='50241'>of</span>
  <span m='50685'>an</span> <span m='51130'>array,</span> <span m='51574'>into</span>
  <span m='52019'>the</span> <span m='52634'>right</span> <span m='53249'>sequence</span>
  <span m='53864'>of</span> <span m='54479'>Beta</span> <span m='55094'>operations.</span>
  </p><p><span m='55710'>We</span> <span m='56007'>can</span> <span m='56304'>go</span>
  <span m='56602'>one</span> <span m='56899'>step</span> <span m='57196'>further</span>
  <span m='57494'>and</span> <span m='57791'>use</span> <span m='58088'>high-level</span>
  <span m='58386'>languages</span> <span m='58683'>to</span> <span m='58980'>describe</span>
  <span m='59278'>the</span> <span m='59575'>computations</span> <span m='59872'>we</span>
  <span m='60170'>want</span> <span m='60773'>to</span> <span m='61376'>perform.</span>
  </p><p><span m='61979'>These</span> <span m='62326'>languages</span> <span m='62673'>use</span>
  <span m='63020'>variables</span> <span m='63367'>and</span> <span m='63715'>other</span>
  <span m='64062'>data</span> <span m='64409'>structures</span> <span m='64756'>to</span>
  <span m='65103'>abstract</span> <span m='65451'>away</span> <span m='65798'>the</span>
  <span m='66145'>details</span> <span m='66492'>of</span> <span m='66840'>storage</span>
  <span m='67243'>allocation</span> <span m='67646'>and</span> <span m='68050'>the</span>
  <span m='68453'>movement</span> <span m='68856'>of</span> <span m='69260'>data</span>
  <span m='69663'>to</span> <span m='70066'>and</span> <span m='70470'>from</span>
  <span m='70873'>main</span> <span m='71276'>memory.</span> </p><p><span m='71680'>We</span>
  <span m='71945'>can</span> <span m='72211'>just</span> <span m='72477'>refer</span>
  <span m='72743'>to</span> <span m='73009'>a</span> <span m='73275'>data</span> <span
  m='73541'>object</span> <span m='73807'>by</span> <span m='74072'>name</span> <span
  m='74338'>and</span> <span m='74604'>let</span> <span m='74870'>the</span> <span
  m='75136'>language</span> <span m='75402'>processor</span> <span m='75668'>handle</span>
  <span m='75934'>the</span> <span m='76200'>details.</span> </p><p><span m='77200'>Similarly,</span>
  <span m='77593'>we'll</span> <span m='77987'>write</span> <span m='78381'>expressions</span>
  <span m='78775'>and</span> <span m='79169'>other</span> <span m='79563'>operators</span>
  <span m='79956'>such</span> <span m='80350'>as</span> <span m='80744'>assignment</span>
  <span m='81138'>(=)</span> <span m='81532'>to</span> <span m='81926'>efficiently</span>
  <span m='82320'>describe</span> <span m='82875'>what</span> <span m='83431'>would</span>
  <span m='83986'>require</span> <span m='84542'>many</span> <span m='85097'>statements</span>
  <span m='85653'>in</span> <span m='86208'>assembly</span> <span m='86764'>language.</span>
  </p><p><span m='87320'>Today</span> <span m='87661'>we're</span> <span m='88002'>going</span>
  <span m='88343'>to</span> <span m='88685'>dive</span> <span m='89026'>into</span>
  <span m='89367'>how</span> <span m='89708'>to</span> <span m='90050'>translate</span>
  <span m='90391'>high-level</span> <span m='90732'>language</span> <span m='91073'>programs</span>
  <span m='91415'>into</span> <span m='91756'>code</span> <span m='92097'>that</span>
  <span m='92439'>will</span> <span m='92779'>run</span> <span m='93119'>on</span>
  <span m='93459'>the</span> <span m='93799'>Beta.</span> </p><p><span m='94140'>Here</span>
  <span m='94507'>we</span> <span m='94875'>see</span> <span m='95243'>Euclid's</span>
  <span m='95611'>algorithm</span> <span m='95978'>for</span> <span m='96346'>determining</span>
  <span m='96714'>the</span> <span m='97082'>greatest</span> <span m='97450'>common</span>
  <span m='97817'>divisor</span> <span m='98185'>of</span> <span m='98553'>two</span>
  <span m='98921'>numbers,</span> <span m='99289'>in</span> <span m='99633'>this</span>
  <span m='99977'>case</span> <span m='100321'>the</span> <span m='100666'>algorithm</span>
  <span m='101010'>is</span> <span m='101354'>written</span> <span m='101698'>in</span>
  <span m='102043'>the</span> <span m='102387'>C</span> <span m='102731'>programming</span>
  <span m='103075'>language.</span> </p><p><span m='103420'>We'll</span> <span m='103767'>be</span>
  <span m='104115'>using</span> <span m='104462'>a</span> <span m='104810'>simple</span>
  <span m='105158'>subset</span> <span m='105505'>of</span> <span m='105853'>C</span>
  <span m='106200'>as</span> <span m='106548'>our</span> <span m='106896'>example</span>
  <span m='107243'>high-level</span> <span m='107591'>language.</span> </p><p><span
  m='107939'>Please</span> <span m='108199'>see</span> <span m='108460'>the</span>
  <span m='108720'>brief</span> <span m='108981'>overview</span> <span m='109242'>of</span>
  <span m='109502'>C</span> <span m='109763'>in</span> <span m='110024'>the</span>
  <span m='110284'>Handouts</span> <span m='110545'>section</span> <span m='110805'>if</span>
  <span m='111066'>you'd</span> <span m='111327'>like</span> <span m='111587'>an</span>
  <span m='111848'>introduction</span> <span m='112109'>to</span> <span m='112773'>C</span>
  <span m='113437'>syntax</span> <span m='114101'>and</span> <span m='114765'>semantics.</span>
  </p><p><span m='115429'>C</span> <span m='115738'>was</span> <span m='116047'>developed</span>
  <span m='116357'>by</span> <span m='116666'>Dennis</span> <span m='116976'>Ritchie</span>
  <span m='117285'>at</span> <span m='117594'>AT&amp;T</span> <span m='117904'>Bell</span>
  <span m='118213'>Labs</span> <span m='118523'>in</span> <span m='118832'>the</span>
  <span m='119141'>late</span> <span m='119451'>60's</span> <span m='119760'>and</span>
  <span m='120070'>early</span> <span m='120379'>70's</span> <span m='120689'>to</span>
  <span m='121125'>use</span> <span m='121561'>when</span> <span m='121998'>implementing</span>
  <span m='122434'>the</span> <span m='122870'>Unix</span> <span m='123307'>operating</span>
  <span m='123743'>system.</span> </p><p><span m='124180'>Since</span> <span m='124524'>that</span>
  <span m='124869'>time</span> <span m='125213'>many</span> <span m='125558'>new</span>
  <span m='125903'>high-level</span> <span m='126247'>languages</span> <span m='126592'>have</span>
  <span m='126936'>been</span> <span m='127281'>introduced</span> <span m='127626'>providing</span>
  <span m='127970'>modern</span> <span m='128315'>abstractions</span> <span m='128660'>like</span>
  <span m='129340'>object-oriented</span> <span m='130021'>programming</span> <span
  m='130702'>along</span> <span m='131383'>with</span> <span m='132064'>useful</span>
  <span m='132745'>new</span> <span m='133426'>data</span> <span m='134107'>and</span>
  <span m='134788'>control</span> <span m='135469'>structures.</span> </p><p><span
  m='136150'>Using</span> <span m='136438'>C</span> <span m='136727'>allows</span>
  <span m='137016'>us</span> <span m='137305'>describe</span> <span m='137594'>a</span>
  <span m='137882'>computation</span> <span m='138171'>without</span> <span m='138460'>referring</span>
  <span m='138749'>to</span> <span m='139038'>any</span> <span m='139327'>of</span>
  <span m='139615'>the</span> <span m='139904'>details</span> <span m='140193'>of</span>
  <span m='140482'>the</span> <span m='140771'>Beta</span> <span m='141060'>ISA</span>
  <span m='141600'>like</span> <span m='142140'>registers,</span> <span m='142680'>specific</span>
  <span m='143220'>Beta</span> <span m='143760'>instructions,</span> <span m='144300'>and</span>
  <span m='144840'>so</span> <span m='145380'>on.</span> </p><p><span m='145920'>The</span>
  <span m='146233'>absence</span> <span m='146546'>of</span> <span m='146859'>such</span>
  <span m='147172'>details</span> <span m='147485'>means</span> <span m='147798'>there</span>
  <span m='148111'>is</span> <span m='148425'>less</span> <span m='148738'>work</span>
  <span m='149051'>required</span> <span m='149364'>to</span> <span m='149677'>create</span>
  <span m='149990'>the</span> <span m='150303'>program</span> <span m='150616'>and</span>
  <span m='150930'>makes</span> <span m='151366'>it</span> <span m='151802'>easier</span>
  <span m='152238'>for</span> <span m='152674'>others</span> <span m='153110'>to</span>
  <span m='153546'>read</span> <span m='153982'>and</span> <span m='154418'>understand</span>
  <span m='154854'>the</span> <span m='155290'>algorithm</span> <span m='155726'>implemented</span>
  <span m='156162'>by</span> <span m='156598'>the</span> <span m='157034'>program.</span>
  </p><p><span m='157470'>There</span> <span m='157834'>are</span> <span m='158198'>many</span>
  <span m='158563'>advantages</span> <span m='158927'>to</span> <span m='159292'>using</span>
  <span m='159656'>a</span> <span m='160021'>high-level</span> <span m='160385'>language.</span>
  </p><p><span m='160750'>They</span> <span m='161155'>enable</span> <span m='161561'>programmers</span>
  <span m='161967'>to</span> <span m='162372'>be</span> <span m='162778'>very</span>
  <span m='163184'>productive</span> <span m='163590'>since</span> <span m='163995'>the</span>
  <span m='164401'>programs</span> <span m='164807'>are</span> <span m='165212'>concise</span>
  <span m='165618'>and</span> <span m='166024'>readable.</span> </p><p><span m='166430'>These</span>
  <span m='166759'>attributes</span> <span m='167088'>also</span> <span m='167417'>make</span>
  <span m='167746'>it</span> <span m='168075'>easy</span> <span m='168404'>to</span>
  <span m='168733'>maintain</span> <span m='169062'>the</span> <span m='169391'>code.</span>
  </p><p><span m='169720'>Often</span> <span m='170047'>it</span> <span m='170374'>is</span>
  <span m='170701'>harder</span> <span m='171028'>to</span> <span m='171355'>make</span>
  <span m='171682'>certain</span> <span m='172009'>types</span> <span m='172336'>of</span>
  <span m='172663'>mistakes</span> <span m='172990'>since</span> <span m='173317'>the</span>
  <span m='173644'>language</span> <span m='173971'>allows</span> <span m='174298'>us</span>
  <span m='174625'>to</span> <span m='174952'>check</span> <span m='175280'>for</span>
  <span m='175704'>silly</span> <span m='176128'>errors</span> <span m='176552'>like</span>
  <span m='176976'>storing</span> <span m='177400'>a</span> <span m='177825'>string</span>
  <span m='178249'>value</span> <span m='178673'>into</span> <span m='179097'>a</span>
  <span m='179521'>numeric</span> <span m='179945'>variable.</span> </p><p><span m='180370'>And</span>
  <span m='180800'>more</span> <span m='181231'>complicated</span> <span m='181662'>tasks</span>
  <span m='182093'>like</span> <span m='182524'>dynamically</span> <span m='182955'>allocating</span>
  <span m='183385'>and</span> <span m='183816'>deallocating</span> <span m='184247'>storage</span>
  <span m='184678'>can</span> <span m='185109'>be</span> <span m='185540'>completely</span>
  <span m='186815'>automated.</span> </p><p><span m='188090'>The</span> <span m='188373'>result</span>
  <span m='188657'>is</span> <span m='188941'>that</span> <span m='189225'>it</span>
  <span m='189509'>can</span> <span m='189793'>take</span> <span m='190077'>much</span>
  <span m='190361'>less</span> <span m='190645'>time</span> <span m='190928'>to</span>
  <span m='191212'>create</span> <span m='191496'>a</span> <span m='191780'>correct</span>
  <span m='192064'>program</span> <span m='192348'>in</span> <span m='192632'>a</span>
  <span m='192916'>high-level</span> <span m='193200'>language</span> <span m='193652'>than</span>
  <span m='194104'>it</span> <span m='194556'>would</span> <span m='195008'>it</span>
  <span m='195460'>when</span> <span m='195912'>writing</span> <span m='196364'>in</span>
  <span m='196816'>assembly</span> <span m='197268'>language.</span> </p><p><span
  m='197720'>Since</span> <span m='198092'>the</span> <span m='198464'>high-level</span>
  <span m='198836'>language</span> <span m='199208'>has</span> <span m='199580'>abstracted</span>
  <span m='199952'>away</span> <span m='200325'>the</span> <span m='200697'>details</span>
  <span m='201069'>of</span> <span m='201441'>a</span> <span m='201813'>particular</span>
  <span m='202185'>ISA,</span> <span m='202557'>the</span> <span m='202930'>programs</span>
  <span m='203228'>are</span> <span m='203527'>portable</span> <span m='203826'>in</span>
  <span m='204125'>the</span> <span m='204424'>sense</span> <span m='204722'>that</span>
  <span m='205021'>we</span> <span m='205320'>can</span> <span m='205619'>expect</span>
  <span m='205918'>to</span> <span m='206217'>run</span> <span m='206515'>the</span>
  <span m='206814'>same</span> <span m='207113'>code</span> <span m='207412'>on</span>
  <span m='207711'>different</span> <span m='208010'>ISAs</span> <span m='208425'>without</span>
  <span m='208841'>having</span> <span m='209257'>to</span> <span m='209672'>rewrite</span>
  <span m='210088'>the</span> <span m='210504'>code.</span> </p><p><span m='210920'>What</span>
  <span m='211427'>do</span> <span m='211935'>we</span> <span m='212443'>lose</span>
  <span m='212951'>by</span> <span m='213458'>using</span> <span m='213966'>a</span>
  <span m='214474'>high-level</span> <span m='214982'>language?</span> </p><p><span
  m='215490'>Should</span> <span m='215745'>we</span> <span m='216001'>worry</span>
  <span m='216256'>that</span> <span m='216512'>we'll</span> <span m='216767'>pay</span>
  <span m='217023'>a</span> <span m='217278'>price</span> <span m='217534'>in</span>
  <span m='217790'>terms</span> <span m='218045'>of</span> <span m='218301'>the</span>
  <span m='218556'>efficiency</span> <span m='218812'>and</span> <span m='219067'>performance</span>
  <span m='219323'>we</span> <span m='219579'>might</span> <span m='220004'>get</span>
  <span m='220429'>by</span> <span m='220854'>crafting</span> <span m='221279'>each</span>
  <span m='221704'>instruction</span> <span m='222129'>by</span> <span m='222554'>hand?</span>
  </p><p><span m='222980'>The</span> <span m='223342'>answer</span> <span m='223704'>depends</span>
  <span m='224067'>on</span> <span m='224429'>how</span> <span m='224792'>we</span>
  <span m='225154'>choose</span> <span m='225516'>to</span> <span m='225879'>run</span>
  <span m='226241'>high-level</span> <span m='226604'>language</span> <span m='226966'>programs.</span>
  </p><p><span m='227329'>The</span> <span m='227964'>two</span> <span m='228600'>basic</span>
  <span m='229236'>execution</span> <span m='229871'>strategies</span> <span m='230507'>are</span>
  <span m='231143'>"interpretation"</span> <span m='231778'>and</span> <span m='232414'>"compilation".</span>
  </p><p><span m='233050'>To</span> <span m='233420'>interpret</span> <span m='233790'>a</span>
  <span m='234160'>high-level</span> <span m='234530'>language</span> <span m='234900'>program,</span>
  <span m='235270'>we'll</span> <span m='235640'>write</span> <span m='236010'>a</span>
  <span m='236380'>special</span> <span m='236750'>program</span> <span m='237120'>called</span>
  <span m='237490'>an</span> <span m='237860'>"interpreter"</span> <span m='238230'>that</span>
  <span m='238715'>runs</span> <span m='239201'>on</span> <span m='239687'>the</span>
  <span m='240172'>actual</span> <span m='240658'>computer,</span> <span m='241144'>M1.</span>
  </p><p><span m='241630'>The</span> <span m='242076'>interpreter</span> <span m='242522'>mimics</span>
  <span m='242968'>the</span> <span m='243414'>behavior</span> <span m='243861'>of</span>
  <span m='244307'>some</span> <span m='244753'>abstract</span> <span m='245199'>easy-to-program</span>
  <span m='245646'>machine</span> <span m='246092'>M2</span> <span m='246538'>and</span>
  <span m='246984'>for</span> <span m='247431'>each</span> <span m='247962'>M2</span>
  <span m='248493'>operation</span> <span m='249025'>executes</span> <span m='249556'>sequences</span>
  <span m='250088'>of</span> <span m='250619'>M1</span> <span m='251151'>instructions</span>
  <span m='251682'>to</span> <span m='252214'>achieve</span> <span m='252745'>the</span>
  <span m='253277'>desired</span> <span m='253808'>result.</span> </p><p><span m='254340'>We</span>
  <span m='254716'>can</span> <span m='255093'>think</span> <span m='255470'>of</span>
  <span m='255847'>the</span> <span m='256224'>interpreter</span> <span m='256601'>along</span>
  <span m='256978'>with</span> <span m='257355'>M1</span> <span m='257731'>as</span>
  <span m='258108'>an</span> <span m='258485'>implementation</span> <span m='258862'>of</span>
  <span m='259239'>M2,</span> <span m='259616'>i.e.,</span> <span m='259993'>given</span>
  <span m='260370'>a</span> <span m='260857'>program</span> <span m='261345'>written</span>
  <span m='261833'>for</span> <span m='262320'>M2,</span> <span m='262808'>the</span>
  <span m='263296'>interpreter</span> <span m='263783'>will,</span> <span m='264271'>step-by-step,</span>
  <span m='264759'>emulate</span> <span m='265246'>the</span> <span m='265734'>effect</span>
  <span m='266222'>of</span> <span m='266710'>M2</span> <span m='267665'>instructions.</span>
  </p><p><span m='268620'>We</span> <span m='269120'>often</span> <span m='269620'>use</span>
  <span m='270120'>several</span> <span m='270620'>layers</span> <span m='271120'>of</span>
  <span m='271620'>interpretation</span> <span m='272120'>when</span> <span m='272620'>tackling</span>
  <span m='273120'>computation</span> <span m='273620'>tasks.</span> </p><p><span
  m='274120'>For</span> <span m='274538'>example,</span> <span m='274957'>an</span>
  <span m='275376'>engineer</span> <span m='275795'>may</span> <span m='276214'>use</span>
  <span m='276632'>her</span> <span m='277051'>laptop</span> <span m='277470'>with</span>
  <span m='277889'>an</span> <span m='278308'>Intel</span> <span m='278727'>CPU</span>
  <span m='279145'>to</span> <span m='279564'>run</span> <span m='279983'>the</span>
  <span m='280402'>Python</span> <span m='280821'>interpreter.</span> </p><p><span
  m='281240'>In</span> <span m='281661'>Python,</span> <span m='282082'>she</span>
  <span m='282504'>loads</span> <span m='282925'>the</span> <span m='283347'>SciPy</span>
  <span m='283768'>toolkit,</span> <span m='284190'>which</span> <span m='284611'>provides</span>
  <span m='285032'>a</span> <span m='285454'>calculator-like</span> <span m='285875'>interface</span>
  <span m='286297'>for</span> <span m='286718'>numerical</span> <span m='287140'>analysis</span>
  <span m='287748'>for</span> <span m='288356'>matrices</span> <span m='288964'>and</span>
  <span m='289572'>data.</span> </p><p><span m='290180'>For</span> <span m='290560'>each</span>
  <span m='290941'>SciPy</span> <span m='291321'>command,</span> <span m='291702'>e.g.,</span>
  <span m='292082'>"find</span> <span m='292463'>the</span> <span m='292844'>maximum</span>
  <span m='293224'>value</span> <span m='293605'>of</span> <span m='293985'>a</span>
  <span m='294366'>dataset",</span> <span m='294747'>the</span> <span m='295127'>SciPy</span>
  <span m='295508'>tool</span> <span m='295888'>kit</span> <span m='296269'>executes</span>
  <span m='296650'>many</span> <span m='296988'>Python</span> <span m='297327'>statements,</span>
  <span m='297665'>e.g.,</span> <span m='298004'>to</span> <span m='298342'>loop</span>
  <span m='298681'>over</span> <span m='299019'>each</span> <span m='299358'>element</span>
  <span m='299696'>of</span> <span m='300035'>the</span> <span m='300373'>array,</span>
  <span m='300712'>remembering</span> <span m='301050'>the</span> <span m='301389'>largest</span>
  <span m='302494'>value.</span> </p><p><span m='303600'>For</span> <span m='304051'>each</span>
  <span m='304502'>Python</span> <span m='304954'>statement,</span> <span m='305405'>the</span>
  <span m='305857'>Python</span> <span m='306308'>interpreter</span> <span m='306760'>executes</span>
  <span m='307211'>many</span> <span m='307662'>x86</span> <span m='308114'>instructions,</span>
  <span m='308565'>e.g.,</span> <span m='309017'>to</span> <span m='309468'>increment</span>
  <span m='309920'>the</span> <span m='310468'>loop</span> <span m='311017'>index</span>
  <span m='311566'>and</span> <span m='312115'>check</span> <span m='312663'>for</span>
  <span m='313212'>loop</span> <span m='313761'>termination.</span> </p><p><span m='314310'>Executing</span>
  <span m='314716'>a</span> <span m='315122'>single</span> <span m='315529'>SciPy</span>
  <span m='315935'>command</span> <span m='316342'>may</span> <span m='316748'>require</span>
  <span m='317155'>executing</span> <span m='317561'>of</span> <span m='317967'>tens</span>
  <span m='318374'>of</span> <span m='318780'>Python</span> <span m='319187'>statements,</span>
  <span m='319593'>which</span> <span m='320000'>in</span> <span m='320400'>turn</span>
  <span m='320800'>each</span> <span m='321200'>may</span> <span m='321600'>require</span>
  <span m='322000'>executing</span> <span m='322400'>hundreds</span> <span m='322800'>of</span>
  <span m='323200'>x86</span> <span m='323600'>instructions.</span> </p><p><span m='324000'>The</span>
  <span m='324488'>engineer</span> <span m='324976'>is</span> <span m='325464'>very</span>
  <span m='325952'>happy</span> <span m='326440'>she</span> <span m='326928'>didn't</span>
  <span m='327416'>have</span> <span m='327904'>to</span> <span m='328392'>write</span>
  <span m='328880'>each</span> <span m='329368'>of</span> <span m='329856'>those</span>
  <span m='330344'>instructions</span> <span m='330832'>herself!</span> </p><p><span
  m='331320'>Interpretation</span> <span m='331729'>is</span> <span m='332138'>an</span>
  <span m='332547'>effective</span> <span m='332956'>implementation</span> <span m='333365'>strategy</span>
  <span m='333774'>when</span> <span m='334183'>performing</span> <span m='334592'>a</span>
  <span m='335001'>computation</span> <span m='335410'>once,</span> <span m='335820'>or</span>
  <span m='336191'>when</span> <span m='336562'>exploring</span> <span m='336934'>which</span>
  <span m='337305'>computational</span> <span m='337677'>approach</span> <span m='338048'>is</span>
  <span m='338420'>most</span> <span m='338791'>effective</span> <span m='339162'>before</span>
  <span m='339534'>making</span> <span m='339905'>a</span> <span m='340277'>more</span>
  <span m='340648'>substantial</span> <span m='341020'>investment</span> <span m='341512'>in</span>
  <span m='342005'>creating</span> <span m='342498'>a</span> <span m='342991'>more</span>
  <span m='343484'>efficient</span> <span m='343977'>implementation.</span> </p><p><span
  m='344470'>We'll</span> <span m='344884'>use</span> <span m='345298'>a</span> <span
  m='345712'>compilation</span> <span m='346127'>implementation</span> <span m='346541'>strategy</span>
  <span m='346955'>when</span> <span m='347370'>we</span> <span m='347784'>have</span>
  <span m='348198'>computational</span> <span m='348612'>tasks</span> <span m='349027'>that</span>
  <span m='349441'>we</span> <span m='349855'>need</span> <span m='350270'>to</span>
  <span m='350641'>execute</span> <span m='351012'>repeatedly</span> <span m='351383'>and</span>
  <span m='351755'>hence</span> <span m='352126'>we</span> <span m='352497'>are</span>
  <span m='352868'>willing</span> <span m='353240'>to</span> <span m='353611'>invest</span>
  <span m='353982'>more</span> <span m='354353'>time</span> <span m='354725'>up-front</span>
  <span m='355096'>for</span> <span m='355467'>more</span> <span m='355838'>efficiency</span>
  <span m='356210'>in</span> <span m='356776'>the</span> <span m='357342'>long-term.</span>
  </p><p><span m='357909'>In</span> <span m='358361'>compilation,</span> <span m='358813'>we</span>
  <span m='359265'>also</span> <span m='359717'>start</span> <span m='360169'>with</span>
  <span m='360621'>our</span> <span m='361073'>actual</span> <span m='361525'>computer</span>
  <span m='361977'>M1.</span> </p><p><span m='362430'>Then</span> <span m='362864'>we'll</span>
  <span m='363298'>take</span> <span m='363732'>our</span> <span m='364166'>high-level</span>
  <span m='364600'>language</span> <span m='365034'>program</span> <span m='365468'>P2</span>
  <span m='365902'>and</span> <span m='366336'>translate</span> <span m='366770'>it</span>
  <span m='367204'>statement-by-statement</span> <span m='367639'>into</span> <span
  m='368101'>a</span> <span m='368563'>program</span> <span m='369025'>for</span>
  <span m='369487'>M1.</span> </p><p><span m='369950'>Note</span> <span m='370325'>that</span>
  <span m='370701'>we're</span> <span m='371076'>not</span> <span m='371452'>actually</span>
  <span m='371827'>running</span> <span m='372203'>the</span> <span m='372578'>P2</span>
  <span m='372954'>program.</span> </p><p><span m='373330'>Instead</span> <span m='373658'>we're</span>
  <span m='373987'>using</span> <span m='374316'>it</span> <span m='374645'>as</span>
  <span m='374973'>a</span> <span m='375302'>template</span> <span m='375631'>to</span>
  <span m='375960'>create</span> <span m='376288'>an</span> <span m='376617'>equivalent</span>
  <span m='376946'>P1</span> <span m='377275'>program</span> <span m='377603'>that</span>
  <span m='377932'>can</span> <span m='378261'>execute</span> <span m='378590'>directly</span>
  <span m='379310'>on</span> <span m='380030'>M1.</span> </p><p><span m='380750'>The</span>
  <span m='381143'>translation</span> <span m='381537'>process</span> <span m='381931'>is</span>
  <span m='382325'>called</span> <span m='382719'>"compilation"</span> <span m='383113'>and</span>
  <span m='383506'>the</span> <span m='383900'>program</span> <span m='384294'>that</span>
  <span m='384688'>does</span> <span m='385082'>the</span> <span m='385476'>translation</span>
  <span m='385870'>is</span> <span m='386537'>called</span> <span m='387205'>a</span>
  <span m='387872'>"compiler".</span> </p><p><span m='388540'>We</span> <span m='388886'>compile</span>
  <span m='389233'>the</span> <span m='389580'>P2</span> <span m='389926'>program</span>
  <span m='390273'>once</span> <span m='390620'>to</span> <span m='390966'>get</span>
  <span m='391313'>the</span> <span m='391660'>translation</span> <span m='392006'>P1,</span>
  <span m='392353'>and</span> <span m='392700'>then</span> <span m='393046'>we'll</span>
  <span m='393393'>run</span> <span m='393740'>P1</span> <span m='394086'>on</span>
  <span m='394433'>M1</span> <span m='394780'>whenever</span> <span m='395200'>we</span>
  <span m='395620'>want</span> <span m='396040'>to</span> <span m='396460'>execute</span>
  <span m='396880'>P2.</span> </p><p><span m='397300'>Running</span> <span m='397663'>P1</span>
  <span m='398027'>avoids</span> <span m='398390'>the</span> <span m='398754'>overhead</span>
  <span m='399117'>of</span> <span m='399481'>having</span> <span m='399844'>to</span>
  <span m='400208'>process</span> <span m='400571'>the</span> <span m='400935'>P2</span>
  <span m='401298'>source</span> <span m='401662'>and</span> <span m='402025'>the</span>
  <span m='402389'>costs</span> <span m='402752'>of</span> <span m='403116'>executing</span>
  <span m='403480'>any</span> <span m='404065'>intervening</span> <span m='404651'>layers</span>
  <span m='405237'>of</span> <span m='405823'>interpretation.</span> </p><p><span
  m='406409'>Instead</span> <span m='406780'>of</span> <span m='407152'>dynamically</span>
  <span m='407523'>figuring</span> <span m='407895'>out</span> <span m='408267'>the</span>
  <span m='408638'>necessary</span> <span m='409010'>machine</span> <span m='409381'>instructions</span>
  <span m='409753'>for</span> <span m='410125'>each</span> <span m='410496'>P2</span>
  <span m='410868'>statement</span> <span m='411240'>as</span> <span m='411587'>it's</span>
  <span m='411934'>encountered,</span> <span m='412281'>in</span> <span m='412629'>effect</span>
  <span m='412976'>we've</span> <span m='413323'>arranged</span> <span m='413670'>to</span>
  <span m='414018'>capture</span> <span m='414365'>that</span> <span m='414712'>stream</span>
  <span m='415060'>of</span> <span m='415486'>machine</span> <span m='415912'>instructions</span>
  <span m='416338'>and</span> <span m='416764'>save</span> <span m='417190'>them</span>
  <span m='417616'>as</span> <span m='418043'>a</span> <span m='418469'>P1</span>
  <span m='418895'>program</span> <span m='419321'>for</span> <span m='419747'>later</span>
  <span m='420173'>execution.</span> </p><p><span m='420600'>If</span> <span m='420964'>we're</span>
  <span m='421329'>willing</span> <span m='421694'>to</span> <span m='422058'>pay</span>
  <span m='422423'>the</span> <span m='422788'>up-front</span> <span m='423152'>costs</span>
  <span m='423517'>of</span> <span m='423882'>compilation,</span> <span m='424246'>we'll</span>
  <span m='424611'>get</span> <span m='424976'>more</span> <span m='425340'>efficient</span>
  <span m='425705'>execution.</span> </p><p><span m='426070'>And,</span> <span m='426466'>with</span>
  <span m='426863'>different</span> <span m='427260'>compilers,</span> <span m='427657'>we</span>
  <span m='428054'>can</span> <span m='428451'>arrange</span> <span m='428848'>to</span>
  <span m='429245'>run</span> <span m='429641'>P2</span> <span m='430038'>on</span>
  <span m='430435'>many</span> <span m='430832'>different</span> <span m='431229'>machines</span>
  <span m='431626'>-</span> <span m='432023'>M2,</span> <span m='432420'>M3,</span>
  <span m='433125'>etc.</span> <span m='433831'>-</span> <span m='434537'>without</span>
  <span m='435242'>having</span> <span m='435948'>rewrite</span> <span m='436654'>P2.</span>
  </p><p><span m='437360'>So</span> <span m='437870'>we</span> <span m='438381'>now</span>
  <span m='438892'>have</span> <span m='439402'>two</span> <span m='439913'>ways</span>
  <span m='440424'>to</span> <span m='440934'>execute</span> <span m='441445'>a</span>
  <span m='441956'>high-level</span> <span m='442466'>language</span> <span m='442977'>program:</span>
  <span m='443488'>interpretation</span> <span m='443998'>and</span> <span m='444509'>compilation.</span>
  </p><p><span m='445020'>Both</span> <span m='445369'>allow</span> <span m='445719'>us</span>
  <span m='446069'>to</span> <span m='446419'>change</span> <span m='446769'>the</span>
  <span m='447119'>original</span> <span m='447469'>source</span> <span m='447819'>program.</span>
  </p><p><span m='448169'>Both</span> <span m='448426'>allow</span> <span m='448683'>us</span>
  <span m='448940'>to</span> <span m='449197'>abstract</span> <span m='449454'>away</span>
  <span m='449711'>the</span> <span m='449968'>details</span> <span m='450225'>of</span>
  <span m='450483'>the</span> <span m='450740'>actual</span> <span m='450997'>computer</span>
  <span m='451254'>we'll</span> <span m='451511'>use</span> <span m='451768'>to</span>
  <span m='452025'>run</span> <span m='452282'>the</span> <span m='452540'>program.</span>
  </p><p><span m='453540'>And</span> <span m='453994'>both</span> <span m='454448'>strategies</span>
  <span m='454902'>are</span> <span m='455356'>widely</span> <span m='455810'>used</span>
  <span m='456264'>in</span> <span m='456718'>modern</span> <span m='457172'>computer</span>
  <span m='457626'>systems!</span> </p><p><span m='458080'>Let's</span> <span m='458666'>summarize</span>
  <span m='459252'>the</span> <span m='459838'>differences</span> <span m='460425'>between</span>
  <span m='461011'>interpretation</span> <span m='461597'>and</span> <span m='462183'>compilation.</span>
  </p><p><span m='462770'>Suppose</span> <span m='463346'>the</span> <span m='463923'>statement</span>
  <span m='464500'>"x+2"</span> <span m='465076'>appears</span> <span m='465653'>in</span>
  <span m='466230'>the</span> <span m='466806'>high-level</span> <span m='467383'>program.</span>
  </p><p><span m='467960'>When</span> <span m='468298'>the</span> <span m='468637'>interpreter</span>
  <span m='468975'>processes</span> <span m='469314'>this</span> <span m='469652'>statement</span>
  <span m='469991'>it</span> <span m='470329'>immediately</span> <span m='470668'>fetches</span>
  <span m='471006'>the</span> <span m='471345'>value</span> <span m='471683'>of</span>
  <span m='472022'>the</span> <span m='472360'>variable</span> <span m='472699'>x</span>
  <span m='473042'>and</span> <span m='473386'>adds</span> <span m='473729'>2</span>
  <span m='474073'>to</span> <span m='474416'>it.</span> </p><p><span m='474760'>On</span>
  <span m='475039'>the</span> <span m='475318'>other</span> <span m='475597'>hand,</span>
  <span m='475877'>the</span> <span m='476156'>compiler</span> <span m='476435'>would</span>
  <span m='476714'>generate</span> <span m='476994'>Beta</span> <span m='477273'>instructions</span>
  <span m='477552'>that</span> <span m='477831'>would</span> <span m='478111'>LD</span>
  <span m='478390'>the</span> <span m='478669'>variable</span> <span m='478949'>x</span>
  <span m='479440'>into</span> <span m='479932'>a</span> <span m='480424'>register</span>
  <span m='480916'>and</span> <span m='481408'>then</span> <span m='481900'>ADD</span>
  <span m='482392'>2</span> <span m='482884'>to</span> <span m='483376'>that</span>
  <span m='483868'>value.</span> </p><p><span m='484360'>The</span> <span m='484745'>interpreter</span>
  <span m='485131'>is</span> <span m='485517'>executing</span> <span m='485902'>each</span>
  <span m='486288'>statement</span> <span m='486674'>as</span> <span m='487060'>it's</span>
  <span m='487445'>processed</span> <span m='487831'>and,</span> <span m='488217'>in</span>
  <span m='488602'>fact,</span> <span m='488988'>may</span> <span m='489374'>process</span>
  <span m='489760'>and</span> <span m='490120'>execute</span> <span m='490481'>the</span>
  <span m='490842'>same</span> <span m='491202'>statement</span> <span m='491563'>many</span>
  <span m='491924'>times</span> <span m='492285'>if,</span> <span m='492645'>e.g.,</span>
  <span m='493006'>it</span> <span m='493367'>was</span> <span m='493727'>in</span>
  <span m='494088'>a</span> <span m='494449'>loop.</span> </p><p><span m='494810'>The</span>
  <span m='495336'>compiler</span> <span m='495862'>is</span> <span m='496388'>just</span>
  <span m='496914'>generating</span> <span m='497440'>instructions</span> <span m='497966'>to</span>
  <span m='498493'>be</span> <span m='499019'>executed</span> <span m='499545'>at</span>
  <span m='500071'>some</span> <span m='500597'>later</span> <span m='501123'>time.</span>
  </p><p><span m='501650'>Interpreters</span> <span m='502061'>have</span> <span m='502473'>the</span>
  <span m='502885'>overhead</span> <span m='503296'>of</span> <span m='503708'>processing</span>
  <span m='504120'>the</span> <span m='504531'>high-level</span> <span m='504943'>source</span>
  <span m='505355'>code</span> <span m='505766'>during</span> <span m='506178'>execution</span>
  <span m='506590'>and</span> <span m='507096'>that</span> <span m='507602'>overhead</span>
  <span m='508108'>may</span> <span m='508614'>be</span> <span m='509120'>incurred</span>
  <span m='509626'>many</span> <span m='510132'>times</span> <span m='510638'>in</span>
  <span m='511144'>loops.</span> </p><p><span m='511650'>Compilers</span> <span m='512109'>incur</span>
  <span m='512569'>the</span> <span m='513029'>processing</span> <span m='513489'>overhead</span>
  <span m='513949'>once,</span> <span m='514409'>making</span> <span m='514869'>the</span>
  <span m='515329'>eventual</span> <span m='515789'>execution</span> <span m='516249'>more</span>
  <span m='516709'>efficient.</span> </p><p><span m='517169'>But</span> <span m='517527'>during</span>
  <span m='517886'>development,</span> <span m='518245'>the</span> <span m='518603'>programmer</span>
  <span m='518962'>may</span> <span m='519321'>have</span> <span m='519679'>to</span>
  <span m='520038'>compile</span> <span m='520397'>and</span> <span m='520755'>run</span>
  <span m='521114'>the</span> <span m='521473'>program</span> <span m='521831'>many</span>
  <span m='522190'>times,</span> <span m='522549'>often</span> <span m='522944'>incurring</span>
  <span m='523339'>the</span> <span m='523734'>cost</span> <span m='524129'>of</span>
  <span m='524524'>compilation</span> <span m='524919'>for</span> <span m='525314'>only</span>
  <span m='525709'>a</span> <span m='526104'>single</span> <span m='526499'>execution</span>
  <span m='526894'>of</span> <span m='527289'>the</span> <span m='527684'>program.</span>
  </p><p><span m='528079'>So</span> <span m='528667'>the</span> <span m='529256'>compile-run-debug</span>
  <span m='529845'>loop</span> <span m='530434'>can</span> <span m='531023'>take</span>
  <span m='531612'>more</span> <span m='532201'>time.</span> </p><p><span m='532790'>The</span>
  <span m='533097'>interpreter</span> <span m='533404'>is</span> <span m='533712'>making</span>
  <span m='534019'>decisions</span> <span m='534327'>about</span> <span m='534634'>the</span>
  <span m='534942'>data</span> <span m='535249'>type</span> <span m='535556'>of</span>
  <span m='535864'>x</span> <span m='536171'>and</span> <span m='536479'>the</span>
  <span m='536786'>type</span> <span m='537094'>of</span> <span m='537401'>operations</span>
  <span m='537709'>necessary</span> <span m='538187'>at</span> <span m='538665'>run</span>
  <span m='539143'>time,</span> <span m='539621'>i.e.,</span> <span m='540099'>while</span>
  <span m='540577'>the</span> <span m='541055'>program</span> <span m='541533'>is</span>
  <span m='542011'>running.</span> </p><p><span m='542490'>The</span> <span m='543029'>compiler</span>
  <span m='543568'>is</span> <span m='544107'>making</span> <span m='544646'>those</span>
  <span m='545185'>decisions</span> <span m='545724'>during</span> <span m='546263'>the</span>
  <span m='546802'>compilation</span> <span m='547341'>process.</span> </p><p><span
  m='547880'>Which</span> <span m='548259'>is</span> <span m='548639'>the</span> <span
  m='549019'>better</span> <span m='549399'>approach?</span> </p><p><span m='549779'>In</span>
  <span m='550162'>general,</span> <span m='550545'>executing</span> <span m='550928'>compiled</span>
  <span m='551311'>code</span> <span m='551694'>is</span> <span m='552077'>much</span>
  <span m='552460'>faster</span> <span m='552843'>than</span> <span m='553226'>running</span>
  <span m='553609'>the</span> <span m='553992'>code</span> <span m='554375'>interpretively.</span>
  </p><p><span m='554759'>But</span> <span m='555081'>since</span> <span m='555404'>the</span>
  <span m='555726'>interpreter</span> <span m='556049'>is</span> <span m='556371'>making</span>
  <span m='556694'>decisions</span> <span m='557016'>at</span> <span m='557339'>run</span>
  <span m='557662'>time,</span> <span m='557984'>it</span> <span m='558307'>can</span>
  <span m='558629'>change</span> <span m='558952'>its</span> <span m='559274'>behavior</span>
  <span m='559597'>depending,</span> <span m='559920'>say,</span> <span m='560308'>on</span>
  <span m='560696'>the</span> <span m='561084'>type</span> <span m='561472'>of</span>
  <span m='561860'>the</span> <span m='562248'>data</span> <span m='562636'>in</span>
  <span m='563024'>the</span> <span m='563412'>variable</span> <span m='563800'>X,</span>
  <span m='564188'>offering</span> <span m='564576'>considerable</span> <span m='564964'>flexibility</span>
  <span m='565352'>in</span> <span m='565740'>handling</span> <span m='566129'>different</span>
  <span m='566689'>types</span> <span m='567249'>of</span> <span m='567809'>data</span>
  <span m='568369'>with</span> <span m='568929'>the</span> <span m='569489'>same</span>
  <span m='570049'>algorithm.</span> </p><p><span m='570610'>Compilers</span> <span
  m='570996'>take</span> <span m='571382'>away</span> <span m='571768'>that</span>
  <span m='572154'>flexibility</span> <span m='572540'>in</span> <span m='572926'>exchange</span>
  <span m='573312'>for</span> <span m='573698'>fast</span> <span m='574084'>execution.</span>
  </p>
type: course
uid: cfa842e7cfd6e679333fea2f43a733d5

---
None