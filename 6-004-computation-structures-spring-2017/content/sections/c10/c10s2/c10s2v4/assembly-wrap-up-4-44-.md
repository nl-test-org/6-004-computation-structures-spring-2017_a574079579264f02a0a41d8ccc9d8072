---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: Ouk7t7ViTfI
  parent_uid: e7006e24b55ea9f5c264610f1c24b47d
  title: Video-YouTube-Stream
  type: Video
  uid: c8786b11d576f4e732aa997982acb004
- id: 3Play-3Play YouTube id-Stream
  media_location: Ouk7t7ViTfI
  parent_uid: e7006e24b55ea9f5c264610f1c24b47d
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: e4d13cb8101eb9cd73db6b986e68044f
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/Ouk7t7ViTfI/default.jpg
  parent_uid: e7006e24b55ea9f5c264610f1c24b47d
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 34a2f1affec6fee0d1612c5cb11fcdc6
- id: Ouk7t7ViTfI.srt
  parent_uid: e7006e24b55ea9f5c264610f1c24b47d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c10/c10s2/c10s2v4/assembly-wrap-up-4-44-/Ouk7t7ViTfI.srt
  title: 3play caption file
  type: null
  uid: f758753c3cdf43b3eeee557ebf740c72
- id: Ouk7t7ViTfI.pdf
  parent_uid: e7006e24b55ea9f5c264610f1c24b47d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c10/c10s2/c10s2v4/assembly-wrap-up-4-44-/Ouk7t7ViTfI.pdf
  title: 3play pdf file
  type: null
  uid: f6fe8b5a2fe9b9ac1889b53ae4e1a132
- id: Caption-3Play YouTube id-SRT
  parent_uid: e7006e24b55ea9f5c264610f1c24b47d
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b30077a3365ed199ed4ed58ac10c2341
- id: Transcript-3Play YouTube id-PDF
  parent_uid: e7006e24b55ea9f5c264610f1c24b47d
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 45e62c1c8ff0f36a7d3364a6c3dabdbf
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_10-02-04_300k.mp4
  parent_uid: e7006e24b55ea9f5c264610f1c24b47d
  title: Video-Internet Archive-MP4
  type: Video
  uid: f0499c765e36991fe828015d060123b0
inline_embed_id: 3979733assemblywrapup44412656278
layout: video
order_index: null
parent_uid: bc4fcc448ee3ae41b1bc846b6a864d42
related_resources_text: ''
short_url: assembly-wrap-up-4-44-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c10/c10s2/c10s2v4/assembly-wrap-up-4-44-
template_type: Embed
title: Assembly Wrap-up (4:44)
transcript: <p><span m='630'>So</span> <span m='1091'>far</span> <span m='1552'>we've</span>
  <span m='2014'>talked</span> <span m='2475'>about</span> <span m='2937'>assembling</span>
  <span m='3398'>instructions.</span> </p><p><span m='3860'>What</span> <span m='4370'>about</span>
  <span m='4880'>data?</span> </p><p><span m='5390'>How</span> <span m='5720'>do</span>
  <span m='6050'>we</span> <span m='6380'>allocate</span> <span m='6710'>and</span>
  <span m='7040'>initialize</span> <span m='7370'>data</span> <span m='7700'>storage</span>
  <span m='8030'>and</span> <span m='8360'>how</span> <span m='8690'>do</span> <span
  m='9020'>we</span> <span m='9350'>get</span> <span m='9680'>those</span> <span m='10010'>values</span>
  <span m='10340'>into</span> <span m='10670'>registers</span> <span m='11000'>so</span>
  <span m='11314'>that</span> <span m='11629'>they</span> <span m='11944'>can</span>
  <span m='12259'>be</span> <span m='12574'>used</span> <span m='12889'>as</span>
  <span m='13204'>operands?</span> </p><p><span m='13519'>Here</span> <span m='13925'>we</span>
  <span m='14331'>see</span> <span m='14737'>a</span> <span m='15144'>program</span>
  <span m='15550'>that</span> <span m='15956'>allocates</span> <span m='16362'>and</span>
  <span m='16769'>initializes</span> <span m='17175'>two</span> <span m='17581'>memory</span>
  <span m='17987'>locations</span> <span m='18394'>using</span> <span m='18800'>the</span>
  <span m='19206'>LONG</span> <span m='19612'>macro.</span> </p><p><span m='20019'>We've</span>
  <span m='20535'>used</span> <span m='21052'>labels</span> <span m='21569'>to</span>
  <span m='22086'>remember</span> <span m='22603'>the</span> <span m='23120'>addresses</span>
  <span m='23637'>of</span> <span m='24154'>these</span> <span m='24671'>locations</span>
  <span m='25188'>for</span> <span m='25705'>later</span> <span m='26222'>reference.</span>
  </p><p><span m='26739'>When</span> <span m='27112'>the</span> <span m='27485'>program</span>
  <span m='27859'>is</span> <span m='28232'>assembled</span> <span m='28605'>the</span>
  <span m='28979'>values</span> <span m='29352'>of</span> <span m='29726'>the</span>
  <span m='30099'>label</span> <span m='30472'>N</span> <span m='30846'>and</span>
  <span m='31219'>factN</span> <span m='31593'>are</span> <span m='31966'>0</span>
  <span m='32339'>and</span> <span m='32713'>4</span> <span m='33086'>respectively,</span>
  <span m='33460'>the</span> <span m='33876'>addresses</span> <span m='34292'>of</span>
  <span m='34709'>the</span> <span m='35125'>memory</span> <span m='35541'>locations</span>
  <span m='35958'>holding</span> <span m='36374'>the</span> <span m='36790'>two</span>
  <span m='37207'>data</span> <span m='37623'>values.</span> </p><p><span m='38040'>To</span>
  <span m='38319'>access</span> <span m='38598'>the</span> <span m='38878'>first</span>
  <span m='39157'>data</span> <span m='39437'>value,</span> <span m='39716'>the</span>
  <span m='39995'>program</span> <span m='40275'>uses</span> <span m='40554'>a</span>
  <span m='40834'>LD</span> <span m='41113'>instruction,</span> <span m='41392'>in</span>
  <span m='41672'>this</span> <span m='41951'>case</span> <span m='42231'>one</span>
  <span m='42510'>of</span> <span m='42790'>convenience</span> <span m='43342'>macros</span>
  <span m='43894'>that</span> <span m='44446'>supplies</span> <span m='44999'>R31</span>
  <span m='45551'>as</span> <span m='46103'>the</span> <span m='46656'>default</span>
  <span m='47208'>value</span> <span m='47760'>of</span> <span m='48313'>the</span>
  <span m='48865'>Ra</span> <span m='49417'>field.</span> </p><p><span m='49970'>The</span>
  <span m='50324'>assembler</span> <span m='50678'>replaces</span> <span m='51032'>the</span>
  <span m='51386'>reference</span> <span m='51740'>to</span> <span m='52094'>the</span>
  <span m='52448'>label</span> <span m='52802'>N</span> <span m='53157'>with</span>
  <span m='53511'>its</span> <span m='53865'>value</span> <span m='54219'>0</span>
  <span m='54573'>from</span> <span m='54927'>the</span> <span m='55281'>symbol</span>
  <span m='55635'>table.</span> </p><p><span m='55990'>When</span> <span m='56322'>the</span>
  <span m='56654'>LD</span> <span m='56987'>is</span> <span m='57319'>executed,</span>
  <span m='57651'>it</span> <span m='57984'>computes</span> <span m='58316'>the</span>
  <span m='58648'>memory</span> <span m='58981'>address</span> <span m='59313'>by</span>
  <span m='59645'>adding</span> <span m='59978'>the</span> <span m='60310'>constant</span>
  <span m='60642'>(0)</span> <span m='60975'>to</span> <span m='61307'>the</span>
  <span m='61640'>value</span> <span m='61977'>of</span> <span m='62315'>the</span>
  <span m='62653'>Ra</span> <span m='62991'>register</span> <span m='63328'>(which</span>
  <span m='63666'>is</span> <span m='64004'>R31</span> <span m='64342'>and</span>
  <span m='64680'>hence</span> <span m='65017'>the</span> <span m='65355'>value</span>
  <span m='65693'>is</span> <span m='66031'>0)</span> <span m='66369'>to</span> <span
  m='66720'>get</span> <span m='67071'>the</span> <span m='67422'>address</span> <span
  m='67773'>(0)</span> <span m='68124'>of</span> <span m='68475'>the</span> <span
  m='68826'>memory</span> <span m='69177'>location</span> <span m='69529'>from</span>
  <span m='69880'>which</span> <span m='70231'>to</span> <span m='70582'>fetch</span>
  <span m='70933'>the</span> <span m='71284'>value</span> <span m='71635'>to</span>
  <span m='71986'>be</span> <span m='72337'>placed</span> <span m='72689'>in</span>
  <span m='73789'>R1.</span> </p><p><span m='74890'>The</span> <span m='75264'>constants</span>
  <span m='75638'>needed</span> <span m='76013'>as</span> <span m='76387'>values</span>
  <span m='76761'>for</span> <span m='77136'>data</span> <span m='77510'>words</span>
  <span m='77885'>and</span> <span m='78259'>instruction</span> <span m='78633'>fields</span>
  <span m='79008'>can</span> <span m='79382'>be</span> <span m='79756'>written</span>
  <span m='80131'>as</span> <span m='80505'>expressions.</span> </p><p><span m='80880'>These</span>
  <span m='81221'>expressions</span> <span m='81562'>are</span> <span m='81904'>evaluated</span>
  <span m='82245'>by</span> <span m='82586'>the</span> <span m='82928'>assembler</span>
  <span m='83269'>as</span> <span m='83610'>it</span> <span m='83952'>assembles</span>
  <span m='84293'>the</span> <span m='84634'>program</span> <span m='84976'>and</span>
  <span m='85317'>the</span> <span m='85658'>resulting</span> <span m='86000'>value</span>
  <span m='86568'>is</span> <span m='87136'>used</span> <span m='87704'>as</span>
  <span m='88272'>needed.</span> </p><p><span m='88840'>Note</span> <span m='89203'>that</span>
  <span m='89566'>the</span> <span m='89930'>expressions</span> <span m='90293'>are</span>
  <span m='90656'>evaluated</span> <span m='91020'>at</span> <span m='91383'>the</span>
  <span m='91746'>time</span> <span m='92110'>the</span> <span m='92473'>assembler</span>
  <span m='92836'>runs.</span> </p><p><span m='93200'>By</span> <span m='93548'>the</span>
  <span m='93897'>time</span> <span m='94245'>the</span> <span m='94594'>program</span>
  <span m='94942'>runs</span> <span m='95291'>on</span> <span m='95639'>the</span>
  <span m='95988'>Beta,</span> <span m='96336'>the</span> <span m='96685'>resulting</span>
  <span m='97033'>value</span> <span m='97382'>is</span> <span m='97730'>used.</span>
  </p><p><span m='98079'>The</span> <span m='98445'>assembler</span> <span m='98811'>does</span>
  <span m='99177'>NOT</span> <span m='99543'>generate</span> <span m='99909'>ADD</span>
  <span m='100275'>and</span> <span m='100641'>MUL</span> <span m='101007'>instructions</span>
  <span m='101373'>to</span> <span m='101739'>compute</span> <span m='102105'>the</span>
  <span m='102471'>value</span> <span m='102837'>during</span> <span m='103203'>program</span>
  <span m='103569'>execution.</span> </p><p><span m='104569'>If</span> <span m='104893'>a</span>
  <span m='105217'>value</span> <span m='105541'>is</span> <span m='105865'>needed</span>
  <span m='106189'>for</span> <span m='106513'>an</span> <span m='106837'>instruction</span>
  <span m='107161'>field</span> <span m='107486'>or</span> <span m='107810'>initial</span>
  <span m='108134'>data</span> <span m='108458'>value,</span> <span m='108782'>the</span>
  <span m='109106'>assembler</span> <span m='109430'>has</span> <span m='109754'>to</span>
  <span m='110079'>be</span> <span m='110564'>able</span> <span m='111050'>to</span>
  <span m='111536'>perform</span> <span m='112021'>the</span> <span m='112507'>arithmetic</span>
  <span m='112993'>itself.</span> </p><p><span m='113479'>If</span> <span m='113764'>you</span>
  <span m='114049'>need</span> <span m='114334'>the</span> <span m='114620'>program</span>
  <span m='114905'>to</span> <span m='115190'>compute</span> <span m='115476'>a</span>
  <span m='115761'>value</span> <span m='116046'>during</span> <span m='116331'>execution,</span>
  <span m='116617'>you</span> <span m='116902'>have</span> <span m='117187'>to</span>
  <span m='117473'>write</span> <span m='117758'>the</span> <span m='118043'>necessary</span>
  <span m='118329'>instructions</span> <span m='118855'>as</span> <span m='119382'>part</span>
  <span m='119909'>of</span> <span m='120436'>your</span> <span m='120963'>program.</span>
  </p><p><span m='121490'>One</span> <span m='121916'>last</span> <span m='122343'>UASM</span>
  <span m='122770'>feature:</span> <span m='123197'>there's</span> <span m='123623'>a</span>
  <span m='124050'>special</span> <span m='124477'>symbol</span> <span m='124904'>".",</span>
  <span m='125330'>called</span> <span m='125757'>"dot",</span> <span m='126184'>whose</span>
  <span m='126611'>value</span> <span m='127037'>is</span> <span m='127464'>the</span>
  <span m='127891'>address</span> <span m='128318'>of</span> <span m='128624'>the</span>
  <span m='128930'>next</span> <span m='129237'>main</span> <span m='129543'>memory</span>
  <span m='129849'>location</span> <span m='130156'>to</span> <span m='130462'>be</span>
  <span m='130769'>filled</span> <span m='131075'>by</span> <span m='131381'>the</span>
  <span m='131688'>assembler</span> <span m='131994'>when</span> <span m='132300'>it</span>
  <span m='132607'>generates</span> <span m='132913'>binary</span> <span m='133220'>data.</span>
  </p><p><span m='134610'>Initially</span> <span m='135042'>"."</span> <span m='135474'>is</span>
  <span m='135906'>0</span> <span m='136338'>and</span> <span m='136770'>it's</span>
  <span m='137202'>incremented</span> <span m='137634'>each</span> <span m='138066'>time</span>
  <span m='138498'>a</span> <span m='138930'>new</span> <span m='139362'>byte</span>
  <span m='139794'>value</span> <span m='140226'>is</span> <span m='140658'>generated.</span>
  </p><p><span m='141090'>We</span> <span m='141385'>can</span> <span m='141681'>set</span>
  <span m='141976'>the</span> <span m='142272'>value</span> <span m='142567'>of</span>
  <span m='142863'>"."</span> <span m='143158'>to</span> <span m='143454'>tell</span>
  <span m='143749'>the</span> <span m='144045'>assembler</span> <span m='144340'>where</span>
  <span m='144636'>in</span> <span m='144931'>memory</span> <span m='145227'>we</span>
  <span m='145522'>wish</span> <span m='145818'>to</span> <span m='146113'>place</span>
  <span m='146409'>a</span> <span m='146704'>value.</span> </p><p><span m='147000'>In</span>
  <span m='147569'>this</span> <span m='148138'>example,</span> <span m='148707'>the</span>
  <span m='149277'>constant</span> <span m='149846'>0xDEADBEEF</span> <span m='150415'>is</span>
  <span m='150985'>placed</span> <span m='151554'>into</span> <span m='152123'>location</span>
  <span m='152692'>0x100</span> <span m='153262'>of</span> <span m='153831'>main</span>
  <span m='154400'>memory.</span> </p><p><span m='154970'>And</span> <span m='155261'>we</span>
  <span m='155553'>can</span> <span m='155845'>use</span> <span m='156137'>"."</span>
  <span m='156428'>in</span> <span m='156720'>expressions</span> <span m='157012'>to</span>
  <span m='157304'>compute</span> <span m='157595'>the</span> <span m='157887'>values</span>
  <span m='158179'>for</span> <span m='158471'>other</span> <span m='158762'>symbols,</span>
  <span m='159054'>as</span> <span m='159346'>shown</span> <span m='159638'>here</span>
  <span m='159930'>when</span> <span m='160321'>defining</span> <span m='160712'>the</span>
  <span m='161103'>value</span> <span m='161495'>for</span> <span m='161886'>the</span>
  <span m='162277'>symbol</span> <span m='162668'>"k".</span> </p><p><span m='163060'>In</span>
  <span m='163506'>fact,</span> <span m='163952'>the</span> <span m='164398'>label</span>
  <span m='164845'>definition</span> <span m='165291'>"k:"</span> <span m='165737'>is</span>
  <span m='166183'>exactly</span> <span m='166630'>equivalent</span> <span m='167076'>to</span>
  <span m='167522'>the</span> <span m='167968'>UASM</span> <span m='168415'>statement</span>
  <span m='168861'>"k</span> <span m='169307'>=</span> <span m='169753'>."</span>
  <span m='170200'>We</span> <span m='170587'>can</span> <span m='170975'>even</span>
  <span m='171362'>increment</span> <span m='171750'>the</span> <span m='172138'>value</span>
  <span m='172525'>of</span> <span m='172913'>"."</span> <span m='173301'>to</span>
  <span m='173688'>skip</span> <span m='174076'>over</span> <span m='174464'>locations,</span>
  <span m='174851'>e.g.,</span> <span m='175239'>if</span> <span m='175627'>we</span>
  <span m='176014'>wanted</span> <span m='176402'>to</span> <span m='176790'>leave</span>
  <span m='177525'>space</span> <span m='178261'>for</span> <span m='178997'>an</span>
  <span m='179732'>un</span> <span m='180468'>initialized</span> <span m='181204'>array.</span>
  </p><p><span m='181940'>And</span> <span m='182457'>that's</span> <span m='182975'>assembly</span>
  <span m='183492'>language!</span> </p><p><span m='184010'>We</span> <span m='184354'>use</span>
  <span m='184698'>assembly</span> <span m='185042'>language</span> <span m='185386'>as</span>
  <span m='185730'>a</span> <span m='186074'>convenient</span> <span m='186418'>notation</span>
  <span m='186762'>for</span> <span m='187106'>generating</span> <span m='187450'>the</span>
  <span m='187794'>binary</span> <span m='188138'>encoding</span> <span m='188482'>for</span>
  <span m='188826'>instructions</span> <span m='189170'>and</span> <span m='189810'>data.</span>
  </p><p><span m='190450'>We</span> <span m='190761'>let</span> <span m='191073'>the</span>
  <span m='191385'>assembler</span> <span m='191697'>build</span> <span m='192008'>the</span>
  <span m='192320'>bit-level</span> <span m='192632'>representations</span> <span
  m='192944'>we</span> <span m='193255'>need</span> <span m='193567'>and</span> <span
  m='193879'>to</span> <span m='194191'>keep</span> <span m='194502'>track</span>
  <span m='194814'>of</span> <span m='195126'>the</span> <span m='195438'>addresses</span>
  <span m='195750'>where</span> <span m='196128'>these</span> <span m='196507'>values</span>
  <span m='196886'>are</span> <span m='197265'>stored</span> <span m='197643'>in</span>
  <span m='198022'>main</span> <span m='198401'>memory.</span> </p><p><span m='198780'>UASM</span>
  <span m='199465'>itself</span> <span m='200150'>provides</span> <span m='200835'>support</span>
  <span m='201520'>for</span> <span m='202205'>values,</span> <span m='202890'>symbols,</span>
  <span m='203575'>labels</span> <span m='204260'>and</span> <span m='204945'>macros.</span>
  </p><p><span m='205630'>Values</span> <span m='206087'>can</span> <span m='206544'>be</span>
  <span m='207001'>written</span> <span m='207458'>as</span> <span m='207915'>constants</span>
  <span m='208372'>or</span> <span m='208829'>expressions</span> <span m='209286'>involving</span>
  <span m='209743'>constants.</span> </p><p><span m='210200'>We</span> <span m='210507'>use</span>
  <span m='210815'>symbols</span> <span m='211122'>to</span> <span m='211430'>give</span>
  <span m='211738'>meaningful</span> <span m='212045'>names</span> <span m='212353'>to</span>
  <span m='212661'>values</span> <span m='212968'>so</span> <span m='213276'>that</span>
  <span m='213584'>our</span> <span m='213891'>programs</span> <span m='214199'>will</span>
  <span m='214507'>be</span> <span m='214814'>more</span> <span m='215122'>readable</span>
  <span m='215430'>and</span> <span m='215947'>more</span> <span m='216465'>easily</span>
  <span m='216982'>modified.</span> </p><p><span m='217500'>Similarly,</span> <span
  m='217891'>we</span> <span m='218282'>use</span> <span m='218674'>labels</span>
  <span m='219065'>to</span> <span m='219456'>give</span> <span m='219848'>meaningful</span>
  <span m='220239'>names</span> <span m='220630'>to</span> <span m='221022'>addresses</span>
  <span m='221413'>in</span> <span m='221804'>main</span> <span m='222196'>memory</span>
  <span m='222587'>and</span> <span m='222978'>then</span> <span m='223370'>use</span>
  <span m='223790'>the</span> <span m='224211'>labels</span> <span m='224631'>in</span>
  <span m='225052'>referring</span> <span m='225473'>to</span> <span m='225893'>data</span>
  <span m='226314'>locations</span> <span m='226735'>in</span> <span m='227155'>LD</span>
  <span m='227576'>or</span> <span m='227996'>ST</span> <span m='228417'>instructions,</span>
  <span m='228838'>or</span> <span m='229258'>to</span> <span m='229679'>instruction</span>
  <span m='230100'>locations</span> <span m='231112'>in</span> <span m='232125'>branch</span>
  <span m='233137'>instructions.</span> </p><p><span m='234150'>Macros</span> <span
  m='234512'>hide</span> <span m='234874'>the</span> <span m='235236'>details</span>
  <span m='235599'>of</span> <span m='235961'>how</span> <span m='236323'>instructions</span>
  <span m='236686'>are</span> <span m='237048'>assembled</span> <span m='237410'>from</span>
  <span m='237773'>their</span> <span m='238135'>component</span> <span m='238497'>fields.</span>
  </p><p><span m='238860'>And</span> <span m='239370'>we</span> <span m='239880'>can</span>
  <span m='240390'>use</span> <span m='240900'>"."</span> <span m='241410'>to</span>
  <span m='241920'>control</span> <span m='242430'>where</span> <span m='242940'>the</span>
  <span m='243450'>assembler</span> <span m='243960'>places</span> <span m='244470'>values</span>
  <span m='244980'>in</span> <span m='245490'>main</span> <span m='246000'>memory.</span>
  </p><p><span m='246510'>The</span> <span m='246838'>assembler</span> <span m='247166'>is</span>
  <span m='247494'>itself</span> <span m='247822'>a</span> <span m='248150'>program</span>
  <span m='248479'>that</span> <span m='248807'>runs</span> <span m='249135'>on</span>
  <span m='249463'>our</span> <span m='249791'>computer.</span> </p><p><span m='250120'>That</span>
  <span m='250586'>raises</span> <span m='251052'>an</span> <span m='251518'>interesting</span>
  <span m='251985'>"chicken</span> <span m='252451'>and</span> <span m='252917'>egg</span>
  <span m='253383'>problem":</span> <span m='253850'>how</span> <span m='254167'>did</span>
  <span m='254485'>the</span> <span m='254802'>first</span> <span m='255120'>assembler</span>
  <span m='255438'>program</span> <span m='255755'>get</span> <span m='256073'>assembled</span>
  <span m='256391'>into</span> <span m='256708'>binary</span> <span m='257026'>so</span>
  <span m='257344'>it</span> <span m='257661'>could</span> <span m='257979'>run</span>
  <span m='258297'>on</span> <span m='258614'>a</span> <span m='258932'>computer?</span>
  </p><p><span m='259250'>Well,</span> <span m='259716'>it</span> <span m='260183'>was</span>
  <span m='260650'>hand-assembled</span> <span m='261116'>into</span> <span m='261583'>binary.</span>
  </p><p><span m='262050'>I</span> <span m='262465'>suspect</span> <span m='262880'>it</span>
  <span m='263295'>processed</span> <span m='263710'>a</span> <span m='264125'>very</span>
  <span m='264540'>simple</span> <span m='264955'>language</span> <span m='265370'>indeed,</span>
  <span m='265785'>with</span> <span m='266200'>the</span> <span m='266615'>bells</span>
  <span m='267030'>and</span> <span m='267445'>whistles</span> <span m='267860'>of</span>
  <span m='268275'>symbols,</span> <span m='268690'>labels,</span> <span m='269147'>macros,</span>
  <span m='269604'>expression</span> <span m='270061'>evaluation,</span> <span m='270519'>etc.</span>
  <span m='270976'>added</span> <span m='271433'>only</span> <span m='271890'>after</span>
  <span m='272348'>basic</span> <span m='272805'>instructions</span> <span m='273262'>could</span>
  <span m='273720'>be</span> <span m='274052'>assembled</span> <span m='274384'>by</span>
  <span m='274716'>the</span> <span m='275048'>program.</span> </p><p><span m='275380'>And</span>
  <span m='275697'>I'm</span> <span m='276014'>sure</span> <span m='276331'>they</span>
  <span m='276648'>were</span> <span m='276966'>very</span> <span m='277283'>careful</span>
  <span m='277600'>not</span> <span m='277917'>loose</span> <span m='278235'>the</span>
  <span m='278552'>binary</span> <span m='278869'>so</span> <span m='279186'>they</span>
  <span m='279503'>wouldn't</span> <span m='279821'>have</span> <span m='280138'>to</span>
  <span m='280455'>do</span> <span m='280772'>the</span> <span m='281090'>hand-assembly</span>
  <span m='281552'>a</span> <span m='282015'>second</span> <span m='282477'>time!</span>
  </p>
type: course
uid: e7006e24b55ea9f5c264610f1c24b47d

---
None