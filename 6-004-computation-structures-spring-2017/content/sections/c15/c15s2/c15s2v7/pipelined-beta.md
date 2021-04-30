---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 6mS1BHgm4u8
  parent_uid: eb0bf58cc7682b2ada861bf65ef15415
  title: Video-YouTube-Stream
  type: Video
  uid: de8b45cf73285574ff7032ca04843ab7
- id: 3Play-3Play YouTube id-Stream
  media_location: 6mS1BHgm4u8
  parent_uid: eb0bf58cc7682b2ada861bf65ef15415
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 48522645f7711b835f4abebe1c6575b7
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/6mS1BHgm4u8/default.jpg
  parent_uid: eb0bf58cc7682b2ada861bf65ef15415
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 5f063a19fce33318bf57957efaf19df4
- id: 6mS1BHgm4u8.srt
  parent_uid: eb0bf58cc7682b2ada861bf65ef15415
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v7/pipelined-beta/6mS1BHgm4u8.srt
  title: 3play caption file
  type: null
  uid: 7b7719e2ccbc963788bf32d25a5b8998
- id: 6mS1BHgm4u8.pdf
  parent_uid: eb0bf58cc7682b2ada861bf65ef15415
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v7/pipelined-beta/6mS1BHgm4u8.pdf
  title: 3play pdf file
  type: null
  uid: 5ae4e56187e5a517573d800cc2dc4ede
- id: Caption-3Play YouTube id-SRT
  parent_uid: eb0bf58cc7682b2ada861bf65ef15415
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ab910279354dd92a32851f0ca1be49e4
- id: Transcript-3Play YouTube id-PDF
  parent_uid: eb0bf58cc7682b2ada861bf65ef15415
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 9568d280246770f39fe7767181a17ef7
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_15-02-07-01_300k.mp4
  parent_uid: eb0bf58cc7682b2ada861bf65ef15415
  title: Video-Internet Archive-MP4
  type: Video
  uid: cfabca15c91a8076aba17a8b303c1d27
inline_embed_id: 18748803pipelinedbeta21069147
layout: video
order_index: null
parent_uid: 4d52d6d8435902515638b0bdd4b13c32
related_resources_text: ''
short_url: pipelined-beta
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v7/pipelined-beta
template_type: Embed
title: Pipelined Beta
transcript: <p><span m='1709'>For</span> <span m='2111'>this</span> <span m='2513'>problem,</span>
  <span m='2915'>assume</span> <span m='3317'>that</span> <span m='3719'>you</span>
  <span m='4121'>have</span> <span m='4523'>a</span> <span m='4925'>fully</span> <span
  m='5327'>functioning</span> <span m='5729'>5-stage</span> <span m='6131'>pipelined</span>
  <span m='6533'>beta</span> <span m='6935'>with</span> <span m='7337'>full</span>
  <span m='7740'>bypassing</span> <span m='8263'>and</span> <span m='8787'>annulment</span>
  <span m='9310'>of</span> <span m='9834'>branch</span> <span m='10358'>delay</span>
  <span m='10881'>slots</span> <span m='11405'>as</span> <span m='11929'>presented</span>
  <span m='12452'>in</span> <span m='12976'>lecture.</span> </p><p><span m='13500'>This</span>
  <span m='13833'>beta</span> <span m='14166'>has</span> <span m='14500'>been</span>
  <span m='14833'>running</span> <span m='15166'>the</span> <span m='15500'>program</span>
  <span m='15833'>shown</span> <span m='16166'>here</span> <span m='16500'>for</span>
  <span m='16833'>a</span> <span m='17166'>while.</span> </p><p><span m='17500'>The</span>
  <span m='17835'>actual</span> <span m='18171'>functionality</span> <span m='18507'>of</span>
  <span m='18843'>this</span> <span m='19179'>program</span> <span m='19515'>is</span>
  <span m='19851'>not</span> <span m='20187'>so</span> <span m='20523'>important</span>
  <span m='20859'>for</span> <span m='21195'>this</span> <span m='21531'>problem,</span>
  <span m='21867'>but</span> <span m='22203'>lets</span> <span m='22539'>just</span>
  <span m='23141'>review</span> <span m='23744'>it</span> <span m='24346'>quickly.</span>
  </p><p><span m='24949'>This</span> <span m='25401'>program</span> <span m='25854'>begins</span>
  <span m='26306'>by</span> <span m='26759'>initializing</span> <span m='27211'>R1</span>
  <span m='27664'>to</span> <span m='28117'>0</span> <span m='28569'>before</span>
  <span m='29022'>entering</span> <span m='29474'>the</span> <span m='29927'>loop.</span>
  </p><p><span m='30380'>R1</span> <span m='30833'>represents</span> <span m='31287'>the</span>
  <span m='31740'>index</span> <span m='32194'>of</span> <span m='32648'>the</span>
  <span m='33101'>array</span> <span m='33555'>element</span> <span m='34009'>currently</span>
  <span m='34462'>being</span> <span m='34916'>accessed.</span> </p><p><span m='35370'>Within</span>
  <span m='35785'>the</span> <span m='36200'>loop,</span> <span m='36616'>the</span>
  <span m='37031'>value</span> <span m='37446'>of</span> <span m='37862'>that</span>
  <span m='38277'>array</span> <span m='38693'>element</span> <span m='39108'>is</span>
  <span m='39523'>loaded</span> <span m='39939'>into</span> <span m='40354'>R0.</span>
  </p><p><span m='40770'>R1</span> <span m='41146'>is</span> <span m='41522'>then</span>
  <span m='41899'>incremented</span> <span m='42275'>by</span> <span m='42652'>4</span>
  <span m='43028'>in</span> <span m='43405'>order</span> <span m='43781'>to</span>
  <span m='44158'>point</span> <span m='44534'>to</span> <span m='44911'>the</span>
  <span m='45287'>next</span> <span m='45664'>element</span> <span m='46040'>in</span>
  <span m='46417'>the</span> <span m='46793'>array.</span> </p><p><span m='47170'>We</span>
  <span m='47502'>then</span> <span m='47834'>compare</span> <span m='48167'>the</span>
  <span m='48499'>array</span> <span m='48832'>element</span> <span m='49164'>that</span>
  <span m='49497'>was</span> <span m='49829'>just</span> <span m='50161'>loaded</span>
  <span m='50494'>into</span> <span m='50826'>R0</span> <span m='51159'>with</span>
  <span m='51491'>the</span> <span m='51824'>updated</span> <span m='52156'>index</span>
  <span m='52489'>in</span> <span m='52865'>R1</span> <span m='53242'>and</span> <span
  m='53619'>if</span> <span m='53996'>they</span> <span m='54372'>are</span> <span
  m='54749'>equal,</span> <span m='55126'>then</span> <span m='55503'>we</span> <span
  m='55879'>repeat</span> <span m='56256'>the</span> <span m='56633'>loop.</span>
  </p><p><span m='57010'>If</span> <span m='57337'>they</span> <span m='57665'>are</span>
  <span m='57993'>not</span> <span m='58320'>equal,</span> <span m='58648'>then</span>
  <span m='58976'>we</span> <span m='59304'>store</span> <span m='59631'>the</span>
  <span m='59959'>current</span> <span m='60287'>value</span> <span m='60614'>of</span>
  <span m='60942'>R1</span> <span m='61270'>into</span> <span m='61598'>a</span> <span
  m='61925'>memory</span> <span m='62253'>location</span> <span m='62581'>called</span>
  <span m='62909'>index</span> <span m='63523'>to</span> <span m='64137'>remember</span>
  <span m='64751'>which</span> <span m='65365'>index</span> <span m='65979'>value</span>
  <span m='66593'>satisfied</span> <span m='67207'>the</span> <span m='67821'>compare</span>
  <span m='68435'>instruction.</span> </p><p><span m='69050'>We</span> <span m='69385'>want</span>
  <span m='69720'>to</span> <span m='70055'>understand</span> <span m='70390'>how</span>
  <span m='70725'>this</span> <span m='71060'>program</span> <span m='71395'>would</span>
  <span m='71730'>run</span> <span m='72065'>on</span> <span m='72400'>our</span>
  <span m='72735'>beta.</span> </p><p><span m='73070'>In</span> <span m='73472'>order</span>
  <span m='73874'>to</span> <span m='74277'>do</span> <span m='74679'>this,</span>
  <span m='75081'>we</span> <span m='75484'>will</span> <span m='75886'>create</span>
  <span m='76288'>a</span> <span m='76691'>pipeline</span> <span m='77093'>diagram</span>
  <span m='77495'>showing</span> <span m='77898'>the</span> <span m='78300'>execution</span>
  <span m='78702'>of</span> <span m='79105'>this</span> <span m='79507'>program.</span>
  </p><p><span m='79910'>A</span> <span m='80387'>pipeline</span> <span m='80865'>diagram</span>
  <span m='81343'>demonstrates</span> <span m='81821'>which</span> <span m='82299'>instruction</span>
  <span m='82777'>is</span> <span m='83255'>currently</span> <span m='83732'>being</span>
  <span m='84210'>executed</span> <span m='84688'>in</span> <span m='85166'>each</span>
  <span m='85644'>of</span> <span m='86122'>the</span> <span m='86600'>5</span> <span
  m='87426'>pipeline</span> <span m='88252'>stages.</span> </p><p><span m='89079'>Our</span>
  <span m='89489'>rows</span> <span m='89899'>indicate</span> <span m='90309'>the</span>
  <span m='90719'>pipeline</span> <span m='91129'>stage</span> <span m='91539'>that</span>
  <span m='91949'>the</span> <span m='92359'>instruction</span> <span m='92769'>is</span>
  <span m='93179'>in.</span> </p><p><span m='93590'>There</span> <span m='94078'>are</span>
  <span m='94566'>five</span> <span m='95054'>pipeline</span> <span m='95542'>stages.</span>
  </p><p><span m='96030'>The</span> <span m='96512'>first</span> <span m='96994'>is</span>
  <span m='97476'>IF,</span> <span m='97958'>or</span> <span m='98440'>instruction</span>
  <span m='98922'>fetch,</span> <span m='99405'>which</span> <span m='99887'>fetches</span>
  <span m='100369'>the</span> <span m='100851'>next</span> <span m='101333'>instruction</span>
  <span m='101815'>from</span> <span m='102297'>memory.</span> </p><p><span m='102780'>The</span>
  <span m='103315'>second</span> <span m='103850'>is</span> <span m='104385'>RF,</span>
  <span m='104920'>or</span> <span m='105455'>register</span> <span m='105990'>file</span>
  <span m='106525'>stage</span> <span m='107060'>which</span> <span m='107595'>reads</span>
  <span m='108130'>the</span> <span m='108665'>source</span> <span m='109200'>operands</span>
  <span m='109735'>of</span> <span m='110270'>the</span> <span m='110805'>instruction.</span>
  </p><p><span m='111340'>Next</span> <span m='111863'>comes</span> <span m='112386'>the</span>
  <span m='112910'>ALU</span> <span m='113433'>stage</span> <span m='113956'>where</span>
  <span m='114480'>all</span> <span m='115003'>required</span> <span m='115526'>arithmetic</span>
  <span m='116050'>and</span> <span m='116573'>logic</span> <span m='117096'>unit</span>
  <span m='117620'>operations</span> <span m='118143'>are</span> <span m='118666'>executed.</span>
  </p><p><span m='119190'>The</span> <span m='119461'>fourth</span> <span m='119732'>stage</span>
  <span m='120003'>is</span> <span m='120274'>the</span> <span m='120545'>MEM</span>
  <span m='120816'>stage</span> <span m='121087'>where</span> <span m='121358'>we</span>
  <span m='121630'>can</span> <span m='121901'>begin</span> <span m='122172'>accessing</span>
  <span m='122443'>memory</span> <span m='122714'>for</span> <span m='122985'>a</span>
  <span m='123256'>load</span> <span m='123527'>or</span> <span m='123798'>store</span>
  <span m='124070'>operation</span> <span m='124497'>because</span> <span m='124924'>the</span>
  <span m='125351'>address</span> <span m='125778'>of</span> <span m='126205'>the</span>
  <span m='126632'>memory</span> <span m='127060'>location</span> <span m='127487'>was</span>
  <span m='127914'>computed</span> <span m='128341'>in</span> <span m='128768'>the</span>
  <span m='129195'>ALU</span> <span m='129622'>stage.</span> </p><p><span m='130050'>Finally,</span>
  <span m='130472'>the</span> <span m='130894'>last</span> <span m='131317'>stage</span>
  <span m='131739'>is</span> <span m='132161'>WB,</span> <span m='132584'>or</span>
  <span m='133006'>the</span> <span m='133428'>write</span> <span m='133851'>back</span>
  <span m='134273'>stage</span> <span m='134695'>where</span> <span m='135118'>the</span>
  <span m='135540'>results</span> <span m='135962'>are</span> <span m='136385'>written</span>
  <span m='136807'>back</span> <span m='137230'>into</span> <span m='137887'>the</span>
  <span m='138545'>register</span> <span m='139202'>file.</span> </p><p><span m='139860'>The</span>
  <span m='140459'>columns</span> <span m='141058'>in</span> <span m='141657'>a</span>
  <span m='142256'>pipeline</span> <span m='142855'>diagram</span> <span m='143454'>represent</span>
  <span m='144053'>the</span> <span m='144652'>execution</span> <span m='145251'>cycles.</span>
  </p><p><span m='145850'>Our</span> <span m='146218'>loop</span> <span m='146587'>begins</span>
  <span m='146956'>with</span> <span m='147325'>a</span> <span m='147694'>LD</span>
  <span m='148063'>operation,</span> <span m='148432'>so</span> <span m='148801'>we</span>
  <span m='149170'>see</span> <span m='149538'>our</span> <span m='149907'>LD</span>
  <span m='150276'>instruction</span> <span m='150645'>in</span> <span m='151014'>the</span>
  <span m='151383'>IF</span> <span m='151752'>stage</span> <span m='152121'>in</span>
  <span m='152490'>cycle</span> <span m='153355'>1001.</span> </p><p><span m='154220'>The</span>
  <span m='154871'>LD</span> <span m='155523'>operation</span> <span m='156174'>then</span>
  <span m='156826'>proceeds</span> <span m='157477'>down</span> <span m='158129'>the</span>
  <span m='158780'>5</span> <span m='159432'>stages</span> <span m='160083'>of</span>
  <span m='160735'>the</span> <span m='161386'>pipelined</span> <span m='162038'>beta.</span>
  </p><p><span m='162690'>Next</span> <span m='163254'>comes</span> <span m='163818'>the</span>
  <span m='164382'>ADDC</span> <span m='164946'>instruction.</span> </p><p><span m='165510'>Since</span>
  <span m='165885'>there</span> <span m='166260'>is</span> <span m='166636'>no</span>
  <span m='167011'>dependency</span> <span m='167386'>between</span> <span m='167762'>the</span>
  <span m='168137'>LD</span> <span m='168512'>and</span> <span m='168888'>the</span>
  <span m='169263'>ADDC</span> <span m='169638'>instruction,</span> <span m='170014'>the</span>
  <span m='170389'>ADDC</span> <span m='170764'>instruction</span> <span m='171140'>begins</span>
  <span m='171664'>in</span> <span m='172189'>cycle</span> <span m='172714'>1002</span>
  <span m='173238'>and</span> <span m='173763'>proceeds</span> <span m='174288'>through</span>
  <span m='174812'>all</span> <span m='175337'>the</span> <span m='175862'>5</span>
  <span m='176387'>stages</span> <span m='176911'>of</span> <span m='177436'>the</span>
  <span m='177961'>beta</span> <span m='178485'>pipeline</span> <span m='179010'>as</span>
  <span m='179535'>well.</span> </p><p><span m='180060'>Next</span> <span m='180644'>comes</span>
  <span m='181228'>the</span> <span m='181812'>CMPEQ</span> <span m='182396'>instruction.</span>
  </p><p><span m='182980'>When</span> <span m='183287'>we</span> <span m='183594'>reach</span>
  <span m='183901'>the</span> <span m='184208'>CMPEQ</span> <span m='184515'>instruction,</span>
  <span m='184822'>we</span> <span m='185129'>are</span> <span m='185436'>met</span>
  <span m='185743'>with</span> <span m='186050'>our</span> <span m='186357'>first</span>
  <span m='186664'>data</span> <span m='186971'>hazard</span> <span m='187278'>caused</span>
  <span m='187585'>by</span> <span m='187892'>the</span> <span m='188200'>fact</span>
  <span m='188597'>that</span> <span m='188994'>the</span> <span m='189391'>LD</span>
  <span m='189788'>is</span> <span m='190186'>updating</span> <span m='190583'>R0,</span>
  <span m='190980'>and</span> <span m='191377'>the</span> <span m='191775'>CMPEQ</span>
  <span m='192172'>wants</span> <span m='192569'>to</span> <span m='192966'>read</span>
  <span m='193363'>this</span> <span m='193761'>new</span> <span m='194158'>value</span>
  <span m='194555'>of</span> <span m='194952'>R0.</span> </p><p><span m='195350'>Recall,</span>
  <span m='195773'>that</span> <span m='196196'>a</span> <span m='196619'>LD</span>
  <span m='197042'>does</span> <span m='197465'>not</span> <span m='197888'>produce</span>
  <span m='198311'>its</span> <span m='198735'>value</span> <span m='199158'>until</span>
  <span m='199581'>the</span> <span m='200004'>WB</span> <span m='200427'>stage</span>
  <span m='200850'>of</span> <span m='201273'>the</span> <span m='201696'>pipeline.</span>
  </p><p><span m='202120'>This</span> <span m='202562'>means</span> <span m='203004'>that</span>
  <span m='203446'>even</span> <span m='203888'>with</span> <span m='204330'>full</span>
  <span m='204772'>bypassing</span> <span m='205215'>logic,</span> <span m='205657'>the</span>
  <span m='206099'>CMPEQ</span> <span m='206541'>instruction</span> <span m='206983'>cannot</span>
  <span m='207425'>read</span> <span m='207867'>register</span> <span m='208310'>R0</span>
  <span m='208796'>until</span> <span m='209283'>the</span> <span m='209770'>LD</span>
  <span m='210256'>is</span> <span m='210743'>in</span> <span m='211230'>the</span>
  <span m='211716'>WB</span> <span m='212203'>stage.</span> </p><p><span m='212690'>So</span>
  <span m='213247'>we</span> <span m='213805'>must</span> <span m='214362'>initiate</span>
  <span m='214920'>a</span> <span m='215477'>stall</span> <span m='216035'>of</span>
  <span m='216592'>the</span> <span m='217150'>pipeline</span> <span m='217707'>in</span>
  <span m='218265'>cycle</span> <span m='218822'>1004.</span> </p><p><span m='219380'>The</span>
  <span m='219785'>stall</span> <span m='220190'>can</span> <span m='220595'>be</span>
  <span m='221001'>seen</span> <span m='221406'>in</span> <span m='221811'>our</span>
  <span m='222217'>pipeline</span> <span m='222622'>diagram</span> <span m='223027'>in</span>
  <span m='223432'>cycle</span> <span m='223838'>1005</span> <span m='224243'>where</span>
  <span m='224648'>the</span> <span m='225054'>CMPEQ</span> <span m='225459'>has</span>
  <span m='225864'>remained</span> <span m='226270'>in</span> <span m='226598'>the</span>
  <span m='226926'>RF</span> <span m='227255'>stage</span> <span m='227583'>and</span>
  <span m='227912'>we</span> <span m='228240'>have</span> <span m='228568'>inserted</span>
  <span m='228897'>a</span> <span m='229225'>NOP</span> <span m='229554'>in</span>
  <span m='229882'>place</span> <span m='230211'>of</span> <span m='230539'>the</span>
  <span m='230867'>CMPEQ</span> <span m='231196'>that</span> <span m='231524'>was</span>
  <span m='231853'>coming</span> <span m='232181'>down</span> <span m='232510'>the</span>
  <span m='233002'>pipe</span> <span m='233494'>one</span> <span m='233986'>cycle</span>
  <span m='234478'>earlier.</span> </p><p><span m='234970'>The</span> <span m='235483'>instruction</span>
  <span m='235996'>that</span> <span m='236510'>follows</span> <span m='237023'>the</span>
  <span m='237536'>CMPEQ</span> <span m='238050'>is</span> <span m='238563'>the</span>
  <span m='239076'>BNE.</span> </p><p><span m='239590'>Notice</span> <span m='239984'>that</span>
  <span m='240378'>it</span> <span m='240773'>entered</span> <span m='241167'>the</span>
  <span m='241562'>IF</span> <span m='241956'>stage</span> <span m='242351'>in</span>
  <span m='242745'>cycle</span> <span m='243140'>1004,</span> <span m='243534'>but</span>
  <span m='243928'>it</span> <span m='244323'>too</span> <span m='244717'>was</span>
  <span m='245112'>stalled</span> <span m='245506'>by</span> <span m='245901'>the</span>
  <span m='246295'>CMPEQ,</span> <span m='246690'>so</span> <span m='247180'>the</span>
  <span m='247670'>BNE</span> <span m='248160'>remains</span> <span m='248650'>in</span>
  <span m='249140'>the</span> <span m='249630'>IF</span> <span m='250120'>stage</span>
  <span m='250610'>while</span> <span m='251100'>the</span> <span m='251590'>CMPEQ</span>
  <span m='252080'>is</span> <span m='252570'>stuck</span> <span m='253060'>in</span>
  <span m='253550'>the</span> <span m='254040'>RF</span> <span m='254530'>stage.</span>
  </p><p><span m='255020'>In</span> <span m='255404'>cycle</span> <span m='255788'>1005,</span>
  <span m='256173'>the</span> <span m='256557'>CMPEQ</span> <span m='256941'>is</span>
  <span m='257326'>able</span> <span m='257710'>to</span> <span m='258095'>complete</span>
  <span m='258479'>the</span> <span m='258863'>read</span> <span m='259248'>of</span>
  <span m='259632'>its</span> <span m='260017'>operands</span> <span m='260401'>by</span>
  <span m='260785'>using</span> <span m='261170'>the</span> <span m='261554'>bypass</span>
  <span m='261939'>path</span> <span m='262315'>from</span> <span m='262691'>the</span>
  <span m='263067'>WB</span> <span m='263443'>stage</span> <span m='263819'>to</span>
  <span m='264196'>read</span> <span m='264572'>the</span> <span m='264948'>updated</span>
  <span m='265324'>value</span> <span m='265700'>of</span> <span m='266076'>R0,</span>
  <span m='266453'>and</span> <span m='266829'>by</span> <span m='267205'>using</span>
  <span m='267581'>the</span> <span m='267957'>bypass</span> <span m='268333'>path</span>
  <span m='268710'>from</span> <span m='269234'>the</span> <span m='269758'>MEM</span>
  <span m='270282'>stage</span> <span m='270807'>to</span> <span m='271331'>read</span>
  <span m='271855'>the</span> <span m='272380'>updated</span> <span m='272904'>value</span>
  <span m='273428'>of</span> <span m='273953'>R1</span> <span m='274477'>produced</span>
  <span m='275001'>by</span> <span m='275526'>the</span> <span m='276050'>ADDC</span>
  <span m='276574'>instruction.</span> </p><p><span m='277099'>In</span> <span m='277572'>cycle</span>
  <span m='278045'>1006,</span> <span m='278519'>the</span> <span m='278992'>CMPEQ</span>
  <span m='279465'>instruction</span> <span m='279939'>moves</span> <span m='280412'>on</span>
  <span m='280886'>to</span> <span m='281359'>the</span> <span m='281832'>ALU</span>
  <span m='282306'>stage</span> <span m='282779'>and</span> <span m='283253'>the</span>
  <span m='283726'>BNE</span> <span m='284199'>can</span> <span m='284673'>move</span>
  <span m='285146'>on</span> <span m='285620'>to</span> <span m='286165'>the</span>
  <span m='286710'>RF</span> <span m='287255'>stage.</span> </p><p><span m='287800'>Since</span>
  <span m='288108'>the</span> <span m='288417'>CMPEQ</span> <span m='288726'>is</span>
  <span m='289035'>going</span> <span m='289344'>to</span> <span m='289653'>update</span>
  <span m='289962'>the</span> <span m='290271'>value</span> <span m='290580'>of</span>
  <span m='290888'>R2</span> <span m='291197'>which</span> <span m='291506'>is</span>
  <span m='291815'>the</span> <span m='292124'>register</span> <span m='292433'>that</span>
  <span m='292742'>the</span> <span m='293051'>BNE</span> <span m='293360'>is</span>
  <span m='293669'>trying</span> <span m='294011'>to</span> <span m='294353'>read,</span>
  <span m='294695'>we</span> <span m='295037'>need</span> <span m='295379'>to</span>
  <span m='295721'>make</span> <span m='296063'>use</span> <span m='296405'>of</span>
  <span m='296747'>the</span> <span m='297089'>bypass</span> <span m='297431'>path</span>
  <span m='297773'>from</span> <span m='298115'>the</span> <span m='298457'>ALU</span>
  <span m='298799'>stage</span> <span m='299141'>to</span> <span m='299483'>the</span>
  <span m='299825'>RF</span> <span m='300167'>stage</span> <span m='300509'>in</span>
  <span m='300999'>order</span> <span m='301490'>to</span> <span m='301981'>provide</span>
  <span m='302471'>the</span> <span m='302962'>BNE</span> <span m='303453'>with</span>
  <span m='303943'>the</span> <span m='304434'>result</span> <span m='304925'>of</span>
  <span m='305415'>the</span> <span m='305906'>CMPEQ</span> <span m='306397'>instruction</span>
  <span m='306887'>in</span> <span m='307378'>cycle</span> <span m='307869'>1006.</span>
  </p><p><span m='308360'>The</span> <span m='308746'>RF</span> <span m='309132'>stage</span>
  <span m='309519'>is</span> <span m='309905'>also</span> <span m='310291'>the</span>
  <span m='310678'>stage</span> <span m='311064'>when</span> <span m='311450'>Z</span>
  <span m='311837'>is</span> <span m='312223'>generated.</span> </p><p><span m='312610'>The</span>
  <span m='312957'>Z</span> <span m='313304'>signal</span> <span m='313651'>tells</span>
  <span m='313999'>the</span> <span m='314346'>beta</span> <span m='314693'>whether</span>
  <span m='315040'>or</span> <span m='315388'>not</span> <span m='315735'>a</span>
  <span m='316082'>register</span> <span m='316429'>is</span> <span m='316777'>equal</span>
  <span m='317124'>to</span> <span m='317471'>zero.</span> </p><p><span m='317819'>This</span>
  <span m='318158'>means</span> <span m='318498'>that</span> <span m='318837'>by</span>
  <span m='319177'>the</span> <span m='319516'>end</span> <span m='319856'>of</span>
  <span m='320195'>the</span> <span m='320535'>RF</span> <span m='320874'>stage</span>
  <span m='321214'>in</span> <span m='321553'>cycle</span> <span m='321893'>1006,</span>
  <span m='322232'>the</span> <span m='322572'>BNE</span> <span m='322911'>will</span>
  <span m='323251'>know</span> <span m='323590'>whether</span> <span m='323930'>it</span>
  <span m='324270'>is</span> <span m='324689'>repeating</span> <span m='325109'>the</span>
  <span m='325529'>loop</span> <span m='325949'>or</span> <span m='326369'>not.</span>
  </p><p><span m='326789'>We</span> <span m='327171'>now</span> <span m='327554'>illustrate</span>
  <span m='327937'>what</span> <span m='328320'>happens</span> <span m='328703'>to</span>
  <span m='329086'>the</span> <span m='329469'>pipeline</span> <span m='329852'>diagram</span>
  <span m='330235'>if</span> <span m='330618'>the</span> <span m='331001'>loop</span>
  <span m='331384'>is</span> <span m='331767'>repeated.</span> </p><p><span m='332150'>In</span>
  <span m='332569'>cycle</span> <span m='332988'>1006,</span> <span m='333408'>the</span>
  <span m='333827'>ST</span> <span m='334246'>instruction</span> <span m='334666'>enters</span>
  <span m='335085'>the</span> <span m='335505'>IF</span> <span m='335924'>stage</span>
  <span m='336343'>of</span> <span m='336763'>the</span> <span m='337182'>pipeline</span>
  <span m='337601'>because</span> <span m='338021'>until</span> <span m='338440'>we</span>
  <span m='338860'>resolve</span> <span m='339202'>whether</span> <span m='339544'>a</span>
  <span m='339886'>branch</span> <span m='340228'>is</span> <span m='340570'>taken</span>
  <span m='340912'>or</span> <span m='341254'>not,</span> <span m='341596'>we</span>
  <span m='341938'>assume</span> <span m='342280'>that</span> <span m='342622'>we</span>
  <span m='342964'>should</span> <span m='343306'>continue</span> <span m='343648'>fetching</span>
  <span m='343990'>the</span> <span m='344726'>next</span> <span m='345462'>instruction.</span>
  </p><p><span m='346199'>If</span> <span m='346517'>the</span> <span m='346836'>BNE</span>
  <span m='347155'>determines</span> <span m='347474'>that</span> <span m='347793'>it</span>
  <span m='348111'>should</span> <span m='348430'>branch</span> <span m='348749'>back</span>
  <span m='349068'>to</span> <span m='349387'>LOOP,</span> <span m='349705'>then</span>
  <span m='350024'>this</span> <span m='350343'>ST</span> <span m='350662'>instruction</span>
  <span m='350981'>which</span> <span m='351300'>was</span> <span m='351778'>just</span>
  <span m='352256'>fetched</span> <span m='352735'>must</span> <span m='353213'>be</span>
  <span m='353692'>annulled</span> <span m='354170'>by</span> <span m='354649'>inserting</span>
  <span m='355127'>a</span> <span m='355606'>NOP</span> <span m='356084'>in</span>
  <span m='356563'>its</span> <span m='357041'>place.</span> </p><p><span m='357520'>The</span>
  <span m='357914'>annulment</span> <span m='358309'>is</span> <span m='358704'>initiated</span>
  <span m='359098'>in</span> <span m='359493'>cycle</span> <span m='359888'>1006</span>
  <span m='360283'>and</span> <span m='360677'>shows</span> <span m='361072'>up</span>
  <span m='361467'>as</span> <span m='361862'>a</span> <span m='362256'>NOP</span>
  <span m='362651'>in</span> <span m='363046'>the</span> <span m='363441'>RF</span>
  <span m='363835'>stage</span> <span m='364230'>in</span> <span m='364625'>cycle</span>
  <span m='365020'>1007.</span> </p><p><span m='367220'>In</span> <span m='367588'>cycle</span>
  <span m='367957'>1007,</span> <span m='368326'>we</span> <span m='368695'>also</span>
  <span m='369064'>see</span> <span m='369433'>that</span> <span m='369802'>we</span>
  <span m='370171'>now</span> <span m='370540'>fetch</span> <span m='370908'>the</span>
  <span m='371277'>first</span> <span m='371646'>instruction</span> <span m='372015'>of</span>
  <span m='372384'>the</span> <span m='372753'>loop</span> <span m='373122'>which</span>
  <span m='373491'>is</span> <span m='373860'>the</span> <span m='374535'>LD</span>
  <span m='375210'>instruction</span> <span m='375885'>so</span> <span m='376560'>that</span>
  <span m='377235'>we</span> <span m='377910'>can</span> <span m='378585'>repeat</span>
  <span m='379260'>the</span> <span m='379935'>loop.</span> </p><p><span m='380610'>Here</span>
  <span m='380944'>is</span> <span m='381278'>a</span> <span m='381612'>complete</span>
  <span m='381946'>pipeline</span> <span m='382280'>diagram</span> <span m='382614'>showing</span>
  <span m='382948'>repeated</span> <span m='383282'>execution</span> <span m='383616'>of</span>
  <span m='383950'>the</span> <span m='384284'>loop</span> <span m='384618'>in</span>
  <span m='384952'>our</span> <span m='385286'>sample</span> <span m='385620'>code</span>
  <span m='385972'>together</span> <span m='386325'>with</span> <span m='386677'>the</span>
  <span m='387030'>bypass</span> <span m='387382'>paths</span> <span m='387735'>being</span>
  <span m='388087'>used</span> <span m='388440'>as</span> <span m='388792'>well</span>
  <span m='389145'>as</span> <span m='389497'>the</span> <span m='389850'>initiation</span>
  <span m='390202'>of</span> <span m='390555'>stalls</span> <span m='390907'>and</span>
  <span m='391260'>annulment</span> <span m='391821'>of</span> <span m='392383'>branch</span>
  <span m='392945'>delay</span> <span m='393507'>slots.</span> </p><p><span m='394069'>We</span>
  <span m='394500'>are</span> <span m='394932'>now</span> <span m='395364'>ready</span>
  <span m='395795'>to</span> <span m='396227'>answer</span> <span m='396659'>a</span>
  <span m='397091'>few</span> <span m='397522'>questions</span> <span m='397954'>about</span>
  <span m='398386'>the</span> <span m='398817'>execution</span> <span m='399249'>of</span>
  <span m='399681'>this</span> <span m='400113'>loop</span> <span m='400544'>on</span>
  <span m='400976'>our</span> <span m='401408'>beta.</span> </p><p><span m='401840'>The</span>
  <span m='402271'>first</span> <span m='402702'>question</span> <span m='403133'>we</span>
  <span m='403564'>want</span> <span m='403995'>to</span> <span m='404426'>consider</span>
  <span m='404857'>is</span> <span m='405288'>which</span> <span m='405720'>of</span>
  <span m='406151'>the</span> <span m='406582'>registers</span> <span m='407013'>R0,</span>
  <span m='407444'>R1,</span> <span m='407875'>and/or</span> <span m='408306'>R2</span>
  <span m='408737'>were</span> <span m='409169'>read</span> <span m='409515'>at</span>
  <span m='409862'>least</span> <span m='410209'>once</span> <span m='410555'>directly</span>
  <span m='410902'>from</span> <span m='411249'>the</span> <span m='411596'>register</span>
  <span m='411942'>file</span> <span m='412289'>rather</span> <span m='412636'>than</span>
  <span m='412983'>through</span> <span m='413329'>a</span> <span m='413676'>bypass</span>
  <span m='414023'>path?</span> </p><p><span m='414370'>Looking</span> <span m='414769'>back</span>
  <span m='415168'>at</span> <span m='415567'>our</span> <span m='415967'>completed</span>
  <span m='416366'>pipeline</span> <span m='416765'>diagram,</span> <span m='417165'>we</span>
  <span m='417564'>see</span> <span m='417963'>that</span> <span m='418363'>the</span>
  <span m='418762'>LD</span> <span m='419161'>and</span> <span m='419561'>ADDC</span>
  <span m='419960'>instructions</span> <span m='420359'>did</span> <span m='420759'>not</span>
  <span m='421260'>get</span> <span m='421762'>their</span> <span m='422263'>operands</span>
  <span m='422765'>through</span> <span m='423266'>bypass</span> <span m='423768'>paths.</span>
  </p><p><span m='424270'>Since</span> <span m='424622'>both</span> <span m='424974'>of</span>
  <span m='425327'>those</span> <span m='425679'>instructions</span> <span m='426032'>read</span>
  <span m='426384'>R1,</span> <span m='426737'>that</span> <span m='427089'>means</span>
  <span m='427441'>that</span> <span m='427794'>register</span> <span m='428146'>R1</span>
  <span m='428499'>was</span> <span m='428851'>read</span> <span m='429204'>at</span>
  <span m='429556'>least</span> <span m='429909'>once</span> <span m='430399'>directly</span>
  <span m='430889'>from</span> <span m='431379'>the</span> <span m='431869'>register</span>
  <span m='432359'>file.</span> </p><p><span m='432849'>R0</span> <span m='433281'>which</span>
  <span m='433713'>is</span> <span m='434145'>only</span> <span m='434577'>read</span>
  <span m='435010'>by</span> <span m='435442'>the</span> <span m='435874'>CMPEQ</span>
  <span m='436306'>always</span> <span m='436738'>comes</span> <span m='437171'>from</span>
  <span m='437603'>a</span> <span m='438035'>bypass</span> <span m='438467'>path.</span>
  </p><p><span m='438900'>Similarly,</span> <span m='439288'>R2,</span> <span m='439677'>which</span>
  <span m='440066'>is</span> <span m='440455'>only</span> <span m='440843'>read</span>
  <span m='441232'>by</span> <span m='441621'>the</span> <span m='442010'>BNE,</span>
  <span m='442398'>always</span> <span m='442787'>comes</span> <span m='443176'>from</span>
  <span m='443565'>a</span> <span m='443953'>bypass</span> <span m='444342'>path</span>
  <span m='444731'>as</span> <span m='445120'>well.</span> </p><p><span m='445509'>Next,</span>
  <span m='445890'>we</span> <span m='446272'>want</span> <span m='446653'>to</span>
  <span m='447035'>identify</span> <span m='447416'>the</span> <span m='447798'>cycle</span>
  <span m='448180'>in</span> <span m='448561'>which</span> <span m='448943'>stall</span>
  <span m='449324'>was</span> <span m='449706'>set</span> <span m='450087'>to</span>
  <span m='450469'>1</span> <span m='450851'>in</span> <span m='451232'>the</span>
  <span m='451614'>pipelined</span> <span m='451995'>beta</span> <span m='452377'>hardware.</span>
  </p><p><span m='452759'>This</span> <span m='453151'>occurs</span> <span m='453543'>in</span>
  <span m='453935'>the</span> <span m='454327'>cycle</span> <span m='454719'>where</span>
  <span m='455111'>the</span> <span m='455503'>stall</span> <span m='455895'>is</span>
  <span m='456287'>initiated</span> <span m='456679'>which</span> <span m='457071'>was</span>
  <span m='457463'>in</span> <span m='457855'>cycle</span> <span m='458247'>1004.</span>
  </p><p><span m='458639'>At</span> <span m='458926'>the</span> <span m='459213'>end</span>
  <span m='459500'>of</span> <span m='459787'>that</span> <span m='460074'>cycle</span>
  <span m='460361'>the</span> <span m='460648'>instructions</span> <span m='460935'>that</span>
  <span m='461223'>are</span> <span m='461510'>currently</span> <span m='461797'>in</span>
  <span m='462084'>the</span> <span m='462371'>IF</span> <span m='462658'>and</span>
  <span m='462945'>RF</span> <span m='463232'>stage</span> <span m='463520'>are</span>
  <span m='463889'>stalled</span> <span m='464258'>by</span> <span m='464628'>not</span>
  <span m='464997'>allowing</span> <span m='465367'>a</span> <span m='465736'>load</span>
  <span m='466105'>of</span> <span m='466475'>a</span> <span m='466844'>new</span>
  <span m='467214'>value</span> <span m='467583'>into</span> <span m='467952'>the</span>
  <span m='468322'>instruction</span> <span m='468691'>registers</span> <span m='469061'>of</span>
  <span m='469430'>that</span> <span m='469800'>pipeline</span> <span m='470600'>stage.</span>
  </p><p><span m='471400'>Next,</span> <span m='471978'>we</span> <span m='472556'>want</span>
  <span m='473135'>to</span> <span m='473713'>determine</span> <span m='474291'>in</span>
  <span m='474870'>which</span> <span m='475448'>cycle</span> <span m='476026'>was</span>
  <span m='476605'>ANNUL_IF</span> <span m='477183'>!=</span> <span m='477761'>0?</span>
  </p><p><span m='478340'>Recall</span> <span m='478894'>that</span> <span m='479449'>the</span>
  <span m='480003'>ANNUL_STAGE</span> <span m='480558'>control</span> <span m='481113'>signals</span>
  <span m='481667'>specify</span> <span m='482222'>when</span> <span m='482776'>an</span>
  <span m='483331'>annulment</span> <span m='483886'>is</span> <span m='484440'>initiated</span>
  <span m='484995'>in</span> <span m='485550'>that</span> <span m='486306'>particular</span>
  <span m='487062'>stage.</span> </p><p><span m='487819'>In</span> <span m='488169'>order</span>
  <span m='488519'>to</span> <span m='488869'>initiate</span> <span m='489219'>an</span>
  <span m='489569'>annulment,</span> <span m='489919'>then</span> <span m='490269'>the</span>
  <span m='490619'>instruction</span> <span m='490969'>that</span> <span m='491319'>is</span>
  <span m='491669'>currently</span> <span m='492019'>in</span> <span m='492369'>the</span>
  <span m='492719'>IF</span> <span m='493069'>stage</span> <span m='493419'>is</span>
  <span m='493845'>replaced</span> <span m='494271'>with</span> <span m='494697'>a</span>
  <span m='495123'>NOP.</span> </p><p><span m='495550'>This</span> <span m='495928'>occurs</span>
  <span m='496307'>in</span> <span m='496685'>the</span> <span m='497064'>IF</span>
  <span m='497443'>stage</span> <span m='497821'>when</span> <span m='498200'>we</span>
  <span m='498578'>need</span> <span m='498957'>to</span> <span m='499336'>annul</span>
  <span m='499714'>a</span> <span m='500093'>branch</span> <span m='500471'>delay</span>
  <span m='500850'>slot.</span> </p><p><span m='501229'>In</span> <span m='501827'>our</span>
  <span m='502426'>example</span> <span m='503025'>this</span> <span m='503624'>occurs</span>
  <span m='504223'>in</span> <span m='504822'>cycle</span> <span m='505421'>1006.</span>
  </p><p><span m='506020'>In</span> <span m='506694'>which</span> <span m='507368'>cycle</span>
  <span m='508042'>was</span> <span m='508717'>ANNUL_RF</span> <span m='509391'>!=</span>
  <span m='510065'>0?</span> </p><p><span m='510740'>This</span> <span m='511190'>question</span>
  <span m='511640'>is</span> <span m='512090'>asking</span> <span m='512540'>when</span>
  <span m='512990'>an</span> <span m='513440'>annulment</span> <span m='513890'>was</span>
  <span m='514340'>initiated</span> <span m='514790'>in</span> <span m='515240'>the</span>
  <span m='515690'>RF</span> <span m='516140'>stage.</span> </p><p><span m='516590'>This</span>
  <span m='516979'>occurred</span> <span m='517368'>when</span> <span m='517757'>the</span>
  <span m='518146'>CMPEQ</span> <span m='518536'>instruction</span> <span m='518925'>needed</span>
  <span m='519314'>to</span> <span m='519703'>be</span> <span m='520092'>stalled</span>
  <span m='520482'>in</span> <span m='520871'>the</span> <span m='521260'>RF</span>
  <span m='521649'>stage.</span> </p><p><span m='522039'>In</span> <span m='522357'>order</span>
  <span m='522676'>to</span> <span m='522995'>fill</span> <span m='523314'>the</span>
  <span m='523633'>pipeline</span> <span m='523952'>bubbles,</span> <span m='524271'>a</span>
  <span m='524590'>NOP</span> <span m='524908'>is</span> <span m='525227'>inserted</span>
  <span m='525546'>into</span> <span m='525865'>the</span> <span m='526184'>pipeline</span>
  <span m='526503'>in</span> <span m='526822'>place</span> <span m='527141'>of</span>
  <span m='527460'>the</span> <span m='528015'>CMPEQ</span> <span m='528571'>instruction</span>
  <span m='529127'>that</span> <span m='529683'>was</span> <span m='530239'>in</span>
  <span m='530795'>the</span> <span m='531350'>RF</span> <span m='531906'>stage</span>
  <span m='532462'>in</span> <span m='533018'>cycle</span> <span m='533574'>1004.</span>
  </p><p><span m='534130'>The</span> <span m='534810'>stall</span> <span m='535491'>and</span>
  <span m='536172'>thus</span> <span m='536852'>the</span> <span m='537533'>setting</span>
  <span m='538214'>of</span> <span m='538895'>ANNUL_RF</span> <span m='539575'>!=</span>
  <span m='540256'>0</span> <span m='540937'>occurs</span> <span m='541617'>in</span>
  <span m='542298'>cycle</span> <span m='542979'>1004.</span> </p><p><span m='543660'>In</span>
  <span m='544158'>which</span> <span m='544657'>cycle</span> <span m='545155'>was</span>
  <span m='545654'>ANNUL_ALU</span> <span m='546152'>!=</span> <span m='546651'>0?</span>
  </p><p><span m='547150'>In</span> <span m='547460'>other</span> <span m='547771'>words,</span>
  <span m='548081'>in</span> <span m='548392'>which</span> <span m='548702'>cycle</span>
  <span m='549013'>did</span> <span m='549324'>we</span> <span m='549634'>initiate</span>
  <span m='549945'>the</span> <span m='550255'>replacement</span> <span m='550566'>of</span>
  <span m='550877'>an</span> <span m='551187'>instruction</span> <span m='551498'>in</span>
  <span m='551808'>the</span> <span m='552119'>ALU</span> <span m='552430'>stage</span>
  <span m='553117'>with</span> <span m='553805'>a</span> <span m='554492'>NOP?</span>
  </p><p><span m='555180'>This</span> <span m='555645'>does</span> <span m='556111'>not</span>
  <span m='556577'>occur</span> <span m='557042'>in</span> <span m='557508'>our</span>
  <span m='557974'>example.</span> </p><p><span m='558440'>Next,</span> <span m='559136'>we</span>
  <span m='559832'>want</span> <span m='560528'>to</span> <span m='561225'>consider</span>
  <span m='561921'>our</span> <span m='562617'>bypass</span> <span m='563313'>paths.</span>
  </p><p><span m='564010'>In</span> <span m='564626'>which</span> <span m='565242'>cycle</span>
  <span m='565859'>was</span> <span m='566475'>either</span> <span m='567091'>bypass</span>
  <span m='567708'>coming</span> <span m='568324'>from</span> <span m='568940'>the</span>
  <span m='569557'>ALU</span> <span m='570173'>stage?</span> </p><p><span m='570790'>In</span>
  <span m='571441'>cycle</span> <span m='572092'>1006,</span> <span m='572743'>the</span>
  <span m='573395'>BNE</span> <span m='574046'>reads</span> <span m='574697'>the</span>
  <span m='575348'>result</span> <span m='576000'>of</span> <span m='576651'>the</span>
  <span m='577302'>CMPEQ</span> <span m='577953'>instruction</span> <span m='578605'>from</span>
  <span m='579256'>the</span> <span m='579907'>ALU</span> <span m='580558'>stage.</span>
  </p><p><span m='581210'>In</span> <span m='581710'>which</span> <span m='582211'>cycle</span>
  <span m='582712'>was</span> <span m='583213'>either</span> <span m='583714'>bypass</span>
  <span m='584215'>coming</span> <span m='584716'>from</span> <span m='585217'>the</span>
  <span m='585718'>MEM</span> <span m='586219'>stage?</span> </p><p><span m='586720'>In</span>
  <span m='587220'>cycle</span> <span m='587720'>1005,</span> <span m='588220'>the</span>
  <span m='588720'>CMPEQ</span> <span m='589220'>reads</span> <span m='589720'>the</span>
  <span m='590220'>result</span> <span m='590720'>of</span> <span m='591220'>the</span>
  <span m='591720'>ADDC</span> <span m='592220'>instruction</span> <span m='592720'>from</span>
  <span m='593220'>the</span> <span m='593720'>MEM</span> <span m='594220'>stage.</span>
  </p><p><span m='594720'>Finally,</span> <span m='595290'>in</span> <span m='595861'>which</span>
  <span m='596432'>cycle</span> <span m='597003'>was</span> <span m='597574'>either</span>
  <span m='598145'>bypass</span> <span m='598715'>coming</span> <span m='599286'>from</span>
  <span m='599857'>the</span> <span m='600428'>WB</span> <span m='600999'>stage?</span>
  </p><p><span m='601570'>In</span> <span m='602018'>cycle</span> <span m='602467'>1005,</span>
  <span m='602916'>the</span> <span m='603365'>CMPEQ</span> <span m='603813'>reads</span>
  <span m='604262'>the</span> <span m='604711'>result</span> <span m='605160'>of</span>
  <span m='605608'>the</span> <span m='606057'>LD</span> <span m='606506'>instruction</span>
  <span m='606955'>from</span> <span m='607403'>the</span> <span m='607852'>WB</span>
  <span m='608301'>stage.</span> </p>
type: course
uid: eb0bf58cc7682b2ada861bf65ef15415

---
None