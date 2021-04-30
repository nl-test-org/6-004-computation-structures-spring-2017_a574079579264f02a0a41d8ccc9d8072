---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: UDow47-q5KI
  parent_uid: 577a89897a9e913a0eb1c611a826ec55
  title: Video-YouTube-Stream
  type: Video
  uid: cfdc06cebf9cf6056215a088fa47c11d
- id: 3Play-3Play YouTube id-Stream
  media_location: UDow47-q5KI
  parent_uid: 577a89897a9e913a0eb1c611a826ec55
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 19518bc3a53d5c66880b58dace8cb8fd
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/UDow47-q5KI/default.jpg
  parent_uid: 577a89897a9e913a0eb1c611a826ec55
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: d7d85f5935ea9cdb3285801630348dac
- id: UDow47-q5KI.srt
  parent_uid: 577a89897a9e913a0eb1c611a826ec55
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v2/state-transition-diagrams-11-18-/UDow47-q5KI.srt
  title: 3play caption file
  type: null
  uid: dd32b4468404e94d103e38af86e32736
- id: UDow47-q5KI.pdf
  parent_uid: 577a89897a9e913a0eb1c611a826ec55
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v2/state-transition-diagrams-11-18-/UDow47-q5KI.pdf
  title: 3play pdf file
  type: null
  uid: 5e562857713f86fcfd953ef842812ff7
- id: Caption-3Play YouTube id-SRT
  parent_uid: 577a89897a9e913a0eb1c611a826ec55
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 0642623bc462aaaad3b1e11b3b15f20e
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 577a89897a9e913a0eb1c611a826ec55
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 3f7c58305f5ea125768b258c44264cc6
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_06-02-02_300k.mp4
  parent_uid: 577a89897a9e913a0eb1c611a826ec55
  title: Video-Internet Archive-MP4
  type: Video
  uid: 9769f2c98470b2012b20fd2f8737855e
inline_embed_id: 83375341statetransitiondiagrams111810581378
layout: video
order_index: null
parent_uid: efe80b7f2a8a4e61d67cde18b07eef0f
related_resources_text: ''
short_url: state-transition-diagrams-11-18-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v2/state-transition-diagrams-11-18-
template_type: Embed
title: State Transition Diagrams (11:18)
transcript: <p><span m='1449'>We'll</span> <span m='1787'>describe</span> <span m='2126'>the</span>
  <span m='2465'>operation</span> <span m='2803'>of</span> <span m='3142'>the</span>
  <span m='3481'>FSM</span> <span m='3819'>for</span> <span m='4158'>our</span> <span
  m='4497'>combination</span> <span m='4835'>lock</span> <span m='5174'>using</span>
  <span m='5513'>a</span> <span m='5851'>state</span> <span m='6190'>transition</span>
  <span m='6529'>diagram.</span> </p><p><span m='7540'>Initially,</span> <span m='7982'>the</span>
  <span m='8424'>FSM</span> <span m='8866'>has</span> <span m='9308'>received</span>
  <span m='9750'>no</span> <span m='10192'>bits</span> <span m='10634'>of</span> <span
  m='11076'>the</span> <span m='11518'>combination,</span> <span m='11960'>a</span>
  <span m='12402'>state</span> <span m='12844'>we'll</span> <span m='13286'>call</span>
  <span m='13728'>SX.</span> </p><p><span m='14170'>In</span> <span m='14500'>the</span>
  <span m='14831'>state</span> <span m='15162'>transition</span> <span m='15492'>diagram,</span>
  <span m='15823'>states</span> <span m='16154'>are</span> <span m='16485'>represented</span>
  <span m='16815'>as</span> <span m='17146'>circles,</span> <span m='17477'>each</span>
  <span m='17807'>labeled</span> <span m='18138'>for</span> <span m='18469'>now</span>
  <span m='18800'>with</span> <span m='19169'>a</span> <span m='19538'>symbolic</span>
  <span m='19907'>name</span> <span m='20276'>chosen</span> <span m='20646'>to</span>
  <span m='21015'>remind</span> <span m='21384'>us</span> <span m='21753'>of</span>
  <span m='22123'>what</span> <span m='22492'>history</span> <span m='22861'>it</span>
  <span m='23230'>represents.</span> </p><p><span m='23600'>For</span> <span m='23995'>this</span>
  <span m='24390'>FSM,</span> <span m='24786'>the</span> <span m='25181'>unlock</span>
  <span m='25576'>output</span> <span m='25972'>U</span> <span m='26367'>will</span>
  <span m='26762'>be</span> <span m='27158'>a</span> <span m='27553'>function</span>
  <span m='27948'>of</span> <span m='28344'>the</span> <span m='28739'>current</span>
  <span m='29134'>state,</span> <span m='29530'>so</span> <span m='29925'>we'll</span>
  <span m='30321'>indicate</span> <span m='30747'>the</span> <span m='31173'>value</span>
  <span m='31599'>of</span> <span m='32025'>U</span> <span m='32451'>inside</span>
  <span m='32877'>the</span> <span m='33303'>circle.</span> </p><p><span m='33730'>Since</span>
  <span m='34038'>in</span> <span m='34347'>state</span> <span m='34656'>SX</span>
  <span m='34965'>we</span> <span m='35274'>know</span> <span m='35582'>nothing</span>
  <span m='35891'>about</span> <span m='36200'>past</span> <span m='36509'>input</span>
  <span m='36818'>bits,</span> <span m='37127'>the</span> <span m='37435'>lock</span>
  <span m='37744'>should</span> <span m='38053'>stay</span> <span m='38362'>locked</span>
  <span m='38671'>and</span> <span m='38980'>so</span> <span m='39640'>U</span> <span
  m='40300'>=</span> <span m='40960'>0.</span> </p><p><span m='41620'>We'll</span>
  <span m='42062'>indicate</span> <span m='42505'>the</span> <span m='42947'>initial</span>
  <span m='43390'>state</span> <span m='43832'>with</span> <span m='44275'>a</span>
  <span m='44717'>wide</span> <span m='45160'>border</span> <span m='45602'>on</span>
  <span m='46045'>the</span> <span m='46487'>circle.</span> </p><p><span m='46930'>We'll</span>
  <span m='47268'>use</span> <span m='47607'>the</span> <span m='47946'>successive</span>
  <span m='48285'>states</span> <span m='48623'>to</span> <span m='48962'>remember</span>
  <span m='49301'>what</span> <span m='49640'>we've</span> <span m='49978'>seen</span>
  <span m='50317'>so</span> <span m='50656'>far</span> <span m='50995'>of</span> <span
  m='51333'>the</span> <span m='51672'>input</span> <span m='52011'>combination.</span>
  </p><p><span m='52350'>So</span> <span m='52698'>if</span> <span m='53047'>the</span>
  <span m='53395'>FSM</span> <span m='53744'>is</span> <span m='54092'>in</span> <span
  m='54441'>state</span> <span m='54789'>SX</span> <span m='55138'>and</span> <span
  m='55486'>it</span> <span m='55835'>receives</span> <span m='56183'>a</span> <span
  m='56532'>0</span> <span m='56880'>input,</span> <span m='57229'>it</span> <span
  m='57577'>should</span> <span m='57926'>transition</span> <span m='58274'>to</span>
  <span m='58623'>state</span> <span m='58971'>S0</span> <span m='59320'>to</span>
  <span m='59743'>remind</span> <span m='60167'>us</span> <span m='60590'>that</span>
  <span m='61014'>we've</span> <span m='61437'>seen</span> <span m='61861'>the</span>
  <span m='62285'>first</span> <span m='62708'>bit</span> <span m='63132'>of</span>
  <span m='63555'>the</span> <span m='63979'>combination</span> <span m='64402'>of</span>
  <span m='64826'>0-1-1-0.</span> </p><p><span m='65250'>We</span> <span m='65558'>use</span>
  <span m='65867'>arrows</span> <span m='66176'>to</span> <span m='66484'>indicate</span>
  <span m='66793'>transitions</span> <span m='67102'>between</span> <span m='67410'>states</span>
  <span m='67719'>and</span> <span m='68028'>each</span> <span m='68336'>arrow</span>
  <span m='68645'>has</span> <span m='68954'>a</span> <span m='69262'>label</span>
  <span m='69571'>telling</span> <span m='69880'>us</span> <span m='70241'>when</span>
  <span m='70603'>that</span> <span m='70964'>transition</span> <span m='71326'>should</span>
  <span m='71687'>occur.</span> </p><p><span m='72049'>So</span> <span m='72377'>this</span>
  <span m='72705'>particular</span> <span m='73034'>arrow</span> <span m='73362'>is</span>
  <span m='73691'>telling</span> <span m='74019'>us</span> <span m='74347'>that</span>
  <span m='74676'>when</span> <span m='75004'>the</span> <span m='75333'>FSM</span>
  <span m='75661'>is</span> <span m='75990'>in</span> <span m='76318'>state</span>
  <span m='76646'>SX</span> <span m='76975'>and</span> <span m='77303'>the</span>
  <span m='77632'>next</span> <span m='77960'>input</span> <span m='78289'>is</span>
  <span m='78850'>a</span> <span m='79412'>0,</span> <span m='79974'>the</span> <span
  m='80536'>FSM</span> <span m='81098'>should</span> <span m='81660'>transition</span>
  <span m='82222'>to</span> <span m='82784'>state</span> <span m='83346'>S0.</span>
  </p><p><span m='83908'>Transitions</span> <span m='84286'>are</span> <span m='84665'>triggered</span>
  <span m='85043'>by</span> <span m='85422'>the</span> <span m='85800'>rising</span>
  <span m='86179'>edge</span> <span m='86557'>of</span> <span m='86936'>the</span>
  <span m='87314'>FSM's</span> <span m='87693'>clock</span> <span m='88071'>input.</span>
  </p><p><span m='88450'>Let's</span> <span m='88800'>add</span> <span m='89151'>the</span>
  <span m='89502'>states</span> <span m='89853'>for</span> <span m='90204'>the</span>
  <span m='90555'>remainder</span> <span m='90906'>of</span> <span m='91257'>the</span>
  <span m='91608'>specified</span> <span m='91959'>combination.</span> </p><p><span
  m='92310'>The</span> <span m='92746'>rightmost</span> <span m='93182'>state,</span>
  <span m='93618'>S0110,</span> <span m='94054'>represents</span> <span m='94490'>the</span>
  <span m='94926'>point</span> <span m='95362'>at</span> <span m='95798'>which</span>
  <span m='96234'>the</span> <span m='96670'>FSM</span> <span m='97106'>has</span>
  <span m='97542'>detected</span> <span m='97978'>the</span> <span m='98414'>specified</span>
  <span m='98850'>sequence</span> <span m='99291'>of</span> <span m='99733'>inputs,</span>
  <span m='100174'>so</span> <span m='100616'>the</span> <span m='101057'>unlock</span>
  <span m='101499'>signal</span> <span m='101941'>is</span> <span m='102382'>1</span>
  <span m='102824'>in</span> <span m='103265'>this</span> <span m='103707'>state.</span>
  </p><p><span m='104149'>Looking</span> <span m='104524'>at</span> <span m='104899'>the</span>
  <span m='105274'>state</span> <span m='105650'>transition</span> <span m='106025'>diagram,</span>
  <span m='106400'>we</span> <span m='106776'>see</span> <span m='107151'>that</span>
  <span m='107526'>if</span> <span m='107901'>the</span> <span m='108277'>FSM</span>
  <span m='108652'>starts</span> <span m='109027'>in</span> <span m='109403'>state</span>
  <span m='109778'>SX,</span> <span m='110153'>the</span> <span m='110529'>input</span>
  <span m='111210'>sequence</span> <span m='111892'>0-1-1-0</span> <span m='112574'>will</span>
  <span m='113256'>leave</span> <span m='113938'>the</span> <span m='114620'>FSM</span>
  <span m='115302'>in</span> <span m='115984'>state</span> <span m='116666'>S0110.</span>
  </p><p><span m='117348'>So</span> <span m='117793'>far,</span> <span m='118239'>so</span>
  <span m='118684'>good.</span> </p><p><span m='119130'>What</span> <span m='119399'>should</span>
  <span m='119669'>the</span> <span m='119939'>FSM</span> <span m='120209'>do</span>
  <span m='120479'>if</span> <span m='120749'>an</span> <span m='121019'>input</span>
  <span m='121289'>bit</span> <span m='121559'>is</span> <span m='121829'>not</span>
  <span m='122099'>the</span> <span m='122369'>next</span> <span m='122639'>bit</span>
  <span m='122909'>in</span> <span m='123179'>the</span> <span m='123449'>combination?</span>
  </p><p><span m='123719'>For</span> <span m='124017'>example,</span> <span m='124315'>if</span>
  <span m='124613'>the</span> <span m='124911'>FSM</span> <span m='125209'>is</span>
  <span m='125507'>in</span> <span m='125805'>state</span> <span m='126103'>SX</span>
  <span m='126401'>and</span> <span m='126699'>the</span> <span m='126997'>input</span>
  <span m='127295'>bit</span> <span m='127593'>is</span> <span m='127891'>a</span>
  <span m='128189'>1,</span> <span m='128487'>it</span> <span m='128785'>still</span>
  <span m='129083'>has</span> <span m='129381'>not</span> <span m='129679'>received</span>
  <span m='129978'>any</span> <span m='130491'>correct</span> <span m='131005'>combination</span>
  <span m='131519'>bits,</span> <span m='132032'>so</span> <span m='132546'>the</span>
  <span m='133060'>next</span> <span m='133574'>state</span> <span m='134087'>is</span>
  <span m='134601'>SX</span> <span m='135115'>again.</span> </p><p><span m='135629'>Here</span>
  <span m='136090'>are</span> <span m='136551'>the</span> <span m='137012'>appropriate</span>
  <span m='137473'>non-combination</span> <span m='137934'>transitions</span> <span
  m='138395'>for</span> <span m='138856'>the</span> <span m='139317'>other</span>
  <span m='139778'>states.</span> </p><p><span m='140239'>Note</span> <span m='140703'>that</span>
  <span m='141167'>an</span> <span m='141631'>incorrect</span> <span m='142096'>combination</span>
  <span m='142560'>entry</span> <span m='143024'>doesn't</span> <span m='143489'>necessarily</span>
  <span m='143953'>take</span> <span m='144417'>the</span> <span m='144881'>FSM</span>
  <span m='145346'>to</span> <span m='145810'>state</span> <span m='146274'>SX.</span>
  </p><p><span m='146739'>For</span> <span m='147295'>example,</span> <span m='147852'>if</span>
  <span m='148408'>the</span> <span m='148965'>FSM</span> <span m='149521'>is</span>
  <span m='150078'>in</span> <span m='150634'>state</span> <span m='151191'>S0110,</span>
  <span m='151747'>the</span> <span m='152304'>last</span> <span m='152860'>four</span>
  <span m='153417'>input</span> <span m='153973'>bits</span> <span m='154530'>have</span>
  <span m='155086'>been</span> <span m='155643'>0-1-1-0.</span> </p><p><span m='156200'>If</span>
  <span m='156551'>the</span> <span m='156902'>next</span> <span m='157253'>input</span>
  <span m='157604'>is</span> <span m='157955'>a</span> <span m='158306'>1,</span>
  <span m='158657'>then</span> <span m='159008'>the</span> <span m='159359'>last</span>
  <span m='159710'>four</span> <span m='160061'>inputs</span> <span m='160412'>bits</span>
  <span m='160763'>are</span> <span m='161114'>now</span> <span m='161465'>1-1-0-1,</span>
  <span m='161816'>which</span> <span m='162167'>won't</span> <span m='162518'>lead</span>
  <span m='162870'>to</span> <span m='163364'>an</span> <span m='163859'>open</span>
  <span m='164354'>lock.</span> </p><p><span m='164849'>But</span> <span m='165173'>the</span>
  <span m='165497'>last</span> <span m='165822'>two</span> <span m='166146'>bits</span>
  <span m='166471'>might</span> <span m='166795'>be</span> <span m='167120'>the</span>
  <span m='167444'>first</span> <span m='167769'>two</span> <span m='168093'>bits</span>
  <span m='168417'>of</span> <span m='168742'>a</span> <span m='169066'>valid</span>
  <span m='169391'>combination</span> <span m='169715'>sequence</span> <span m='170040'>and</span>
  <span m='170364'>so</span> <span m='170689'>the</span> <span m='171084'>FSM</span>
  <span m='171479'>transitions</span> <span m='171874'>to</span> <span m='172269'>S01,</span>
  <span m='172664'>indicating</span> <span m='173059'>that</span> <span m='173454'>a</span>
  <span m='173849'>sequence</span> <span m='174244'>of</span> <span m='174639'>0-1</span>
  <span m='175034'>has</span> <span m='175429'>been</span> <span m='175824'>entered</span>
  <span m='176219'>over</span> <span m='176614'>the</span> <span m='177010'>last</span>
  <span m='177803'>two</span> <span m='178596'>bits.</span> </p><p><span m='179390'>We've</span>
  <span m='179672'>been</span> <span m='179954'>working</span> <span m='180237'>with</span>
  <span m='180519'>an</span> <span m='180802'>FSM</span> <span m='181084'>where</span>
  <span m='181367'>the</span> <span m='181649'>outputs</span> <span m='181931'>are</span>
  <span m='182214'>function</span> <span m='182496'>of</span> <span m='182779'>the</span>
  <span m='183061'>current</span> <span m='183344'>state,</span> <span m='183626'>called</span>
  <span m='183909'>a</span> <span m='184482'>Moore</span> <span m='185055'>machine.</span>
  </p><p><span m='185629'>Here</span> <span m='186052'>the</span> <span m='186475'>outputs</span>
  <span m='186899'>are</span> <span m='187322'>written</span> <span m='187745'>inside</span>
  <span m='188169'>the</span> <span m='188592'>state</span> <span m='189015'>circle.</span>
  </p><p><span m='189439'>If</span> <span m='189686'>the</span> <span m='189934'>outputs</span>
  <span m='190181'>are</span> <span m='190429'>a</span> <span m='190676'>function</span>
  <span m='190924'>of</span> <span m='191171'>both</span> <span m='191419'>the</span>
  <span m='191667'>current</span> <span m='191914'>state</span> <span m='192162'>and</span>
  <span m='192409'>the</span> <span m='192657'>current</span> <span m='192904'>inputs,</span>
  <span m='193152'>it's</span> <span m='193400'>called</span> <span m='193772'>a</span>
  <span m='194145'>Mealy</span> <span m='194517'>machine.</span> </p><p><span m='194890'>Since</span>
  <span m='195222'>the</span> <span m='195555'>transitions</span> <span m='195888'>are</span>
  <span m='196220'>also</span> <span m='196553'>a</span> <span m='196886'>function</span>
  <span m='197218'>of</span> <span m='197551'>the</span> <span m='197884'>current</span>
  <span m='198216'>state</span> <span m='198549'>and</span> <span m='198882'>current</span>
  <span m='199214'>inputs,</span> <span m='199547'>we'll</span> <span m='199880'>label</span>
  <span m='200279'>each</span> <span m='200678'>transition</span> <span m='201077'>with</span>
  <span m='201476'>appropriate</span> <span m='201876'>output</span> <span m='202275'>values</span>
  <span m='202674'>using</span> <span m='203073'>a</span> <span m='203472'>slash</span>
  <span m='203872'>to</span> <span m='204271'>separate</span> <span m='204670'>input</span>
  <span m='205069'>values</span> <span m='205469'>from</span> <span m='206009'>output</span>
  <span m='206549'>values.</span> </p><p><span m='207090'>So,</span> <span m='207460'>looking</span>
  <span m='207831'>at</span> <span m='208201'>the</span> <span m='208572'>state</span>
  <span m='208942'>transition</span> <span m='209313'>diagram</span> <span m='209683'>on</span>
  <span m='210054'>the</span> <span m='210425'>right,</span> <span m='210795'>suppose</span>
  <span m='211166'>the</span> <span m='211536'>FSM</span> <span m='211907'>is</span>
  <span m='212277'>in</span> <span m='212648'>state</span> <span m='213019'>S3.</span>
  </p><p><span m='215040'>If</span> <span m='215332'>the</span> <span m='215624'>input</span>
  <span m='215916'>is</span> <span m='216208'>a</span> <span m='216500'>0,</span>
  <span m='216792'>look</span> <span m='217085'>for</span> <span m='217377'>the</span>
  <span m='217669'>arrow</span> <span m='217961'>leaving</span> <span m='218253'>S3</span>
  <span m='218545'>labeled</span> <span m='218837'>"0/".</span> </p><p><span m='219130'>The</span>
  <span m='219574'>value</span> <span m='220019'>after</span> <span m='220464'>the</span>
  <span m='220909'>slash</span> <span m='221354'>tells</span> <span m='221799'>us</span>
  <span m='222244'>the</span> <span m='222689'>output</span> <span m='223134'>value,</span>
  <span m='223579'>in</span> <span m='224024'>this</span> <span m='224469'>case</span>
  <span m='224914'>1.</span> </p><p><span m='225359'>If</span> <span m='225802'>the</span>
  <span m='226245'>input</span> <span m='226688'>had</span> <span m='227131'>been</span>
  <span m='227574'>a</span> <span m='228017'>1,</span> <span m='228461'>the</span>
  <span m='228904'>output</span> <span m='229347'>value</span> <span m='229790'>would</span>
  <span m='230233'>be</span> <span m='230676'>0.</span> </p><p><span m='231120'>There</span>
  <span m='231368'>are</span> <span m='231617'>some</span> <span m='231866'>simple</span>
  <span m='232115'>rules</span> <span m='232363'>we</span> <span m='232612'>can</span>
  <span m='232861'>use</span> <span m='233110'>to</span> <span m='233358'>check</span>
  <span m='233607'>that</span> <span m='233856'>a</span> <span m='234105'>state</span>
  <span m='234353'>transition</span> <span m='234602'>diagram</span> <span m='234851'>is</span>
  <span m='235100'>well</span> <span m='235349'>formed.</span> </p><p><span m='236700'>The</span>
  <span m='237076'>transitions</span> <span m='237453'>from</span> <span m='237829'>a</span>
  <span m='238206'>particular</span> <span m='238583'>state</span> <span m='238959'>must</span>
  <span m='239336'>be</span> <span m='239712'>mutually</span> <span m='240089'>exclusive,</span>
  <span m='240466'>i.e.,</span> <span m='240842'>for</span> <span m='241219'>a</span>
  <span m='241595'>each</span> <span m='241972'>state,</span> <span m='242349'>there</span>
  <span m='242699'>can't</span> <span m='243049'>be</span> <span m='243399'>more</span>
  <span m='243749'>than</span> <span m='244099'>one</span> <span m='244449'>transition</span>
  <span m='244799'>with</span> <span m='245149'>the</span> <span m='245499'>same</span>
  <span m='245849'>input</span> <span m='246199'>label.</span> </p><p><span m='246549'>This</span>
  <span m='246883'>makes</span> <span m='247217'>sense:</span> <span m='247551'>if</span>
  <span m='247885'>the</span> <span m='248219'>FSM</span> <span m='248553'>is</span>
  <span m='248887'>to</span> <span m='249221'>operate</span> <span m='249555'>consistently</span>
  <span m='249889'>there</span> <span m='250223'>can't</span> <span m='250557'>be</span>
  <span m='250891'>any</span> <span m='251225'>ambiguity</span> <span m='251560'>about</span>
  <span m='251888'>the</span> <span m='252216'>next</span> <span m='252544'>state</span>
  <span m='252872'>for</span> <span m='253200'>a</span> <span m='253529'>given</span>
  <span m='253857'>current</span> <span m='254185'>state</span> <span m='254513'>and</span>
  <span m='254841'>input.</span> </p><p><span m='255170'>By</span> <span m='255538'>"consistently"</span>
  <span m='255907'>we</span> <span m='256276'>mean</span> <span m='256644'>that</span>
  <span m='257013'>the</span> <span m='257382'>FSM</span> <span m='257750'>should</span>
  <span m='258119'>make</span> <span m='258488'>the</span> <span m='258856'>same</span>
  <span m='259225'>transitions</span> <span m='259594'>if</span> <span m='259962'>it's</span>
  <span m='260331'>restarted</span> <span m='260700'>at</span> <span m='261086'>the</span>
  <span m='261472'>same</span> <span m='261859'>starting</span> <span m='262245'>state</span>
  <span m='262631'>and</span> <span m='263018'>given</span> <span m='263404'>the</span>
  <span m='263790'>same</span> <span m='264177'>input</span> <span m='264563'>sequences.</span>
  </p><p><span m='264950'>Moreover,</span> <span m='265513'>the</span> <span m='266076'>transitions</span>
  <span m='266640'>leaving</span> <span m='267203'>each</span> <span m='267767'>state</span>
  <span m='268330'>should</span> <span m='268893'>be</span> <span m='269457'>collectively</span>
  <span m='270020'>exhaustive,</span> <span m='270584'>i.e.,</span> <span m='271147'>there</span>
  <span m='271711'>should</span> <span m='272268'>a</span> <span m='272826'>transition</span>
  <span m='273384'>specified</span> <span m='273941'>for</span> <span m='274499'>each</span>
  <span m='275057'>possible</span> <span m='275614'>input</span> <span m='276172'>value.</span>
  </p><p><span m='276730'>If</span> <span m='277004'>we</span> <span m='277278'>wish</span>
  <span m='277552'>the</span> <span m='277826'>FSM</span> <span m='278100'>to</span>
  <span m='278374'>stay</span> <span m='278648'>in</span> <span m='278922'>it's</span>
  <span m='279197'>current</span> <span m='279471'>state</span> <span m='279745'>for</span>
  <span m='280019'>that</span> <span m='280293'>particular</span> <span m='280567'>input</span>
  <span m='280841'>value,</span> <span m='281115'>we</span> <span m='281390'>need</span>
  <span m='281793'>to</span> <span m='282196'>show</span> <span m='282600'>a</span>
  <span m='283003'>transition</span> <span m='283406'>from</span> <span m='283810'>the</span>
  <span m='284213'>current</span> <span m='284616'>state</span> <span m='285020'>back</span>
  <span m='285423'>to</span> <span m='285826'>itself.</span> </p><p><span m='286230'>With</span>
  <span m='286563'>these</span> <span m='286896'>rules</span> <span m='287229'>there</span>
  <span m='287562'>will</span> <span m='287895'>be</span> <span m='288228'>exactly</span>
  <span m='288561'>one</span> <span m='288894'>transition</span> <span m='289227'>selected</span>
  <span m='289560'>for</span> <span m='289893'>every</span> <span m='290226'>combination</span>
  <span m='290560'>of</span> <span m='291271'>current</span> <span m='291983'>state</span>
  <span m='292695'>and</span> <span m='293406'>input</span> <span m='294118'>value.</span>
  </p><p><span m='294830'>All</span> <span m='295160'>the</span> <span m='295490'>information</span>
  <span m='295820'>in</span> <span m='296150'>a</span> <span m='296480'>state</span>
  <span m='296810'>transition</span> <span m='297140'>diagram</span> <span m='297470'>can</span>
  <span m='297800'>be</span> <span m='298130'>represented</span> <span m='298460'>in</span>
  <span m='298790'>tabular</span> <span m='299120'>form</span> <span m='299450'>as</span>
  <span m='299927'>a</span> <span m='300405'>truth</span> <span m='300882'>table.</span>
  </p><p><span m='301360'>The</span> <span m='301670'>rows</span> <span m='301981'>of</span>
  <span m='302291'>the</span> <span m='302602'>truth</span> <span m='302913'>table</span>
  <span m='303223'>list</span> <span m='303534'>all</span> <span m='303845'>the</span>
  <span m='304155'>possible</span> <span m='304466'>combinations</span> <span m='304776'>of</span>
  <span m='305087'>current</span> <span m='305398'>state</span> <span m='305708'>and</span>
  <span m='306019'>inputs.</span> </p><p><span m='306330'>And</span> <span m='306631'>the</span>
  <span m='306932'>output</span> <span m='307233'>columns</span> <span m='307534'>of</span>
  <span m='307835'>the</span> <span m='308137'>truth</span> <span m='308438'>table</span>
  <span m='308739'>tell</span> <span m='309040'>us</span> <span m='309341'>the</span>
  <span m='309642'>next</span> <span m='309944'>state</span> <span m='310245'>and</span>
  <span m='310546'>output</span> <span m='310847'>value</span> <span m='311148'>associated</span>
  <span m='311450'>with</span> <span m='312296'>each</span> <span m='313143'>row.</span>
  </p><p><span m='313990'>If</span> <span m='314293'>we</span> <span m='314597'>substitute</span>
  <span m='314900'>binary</span> <span m='315204'>values</span> <span m='315507'>for</span>
  <span m='315811'>the</span> <span m='316114'>symbolic</span> <span m='316418'>state</span>
  <span m='316721'>names,</span> <span m='317025'>we</span> <span m='317328'>end</span>
  <span m='317632'>up</span> <span m='317935'>with</span> <span m='318239'>a</span>
  <span m='318542'>truth</span> <span m='318846'>table</span> <span m='319150'>just</span>
  <span m='319508'>like</span> <span m='319867'>the</span> <span m='320226'>ones</span>
  <span m='320585'>we</span> <span m='320944'>saw</span> <span m='321303'>in</span>
  <span m='321662'>Chapter</span> <span m='322021'>4.</span> </p><p><span m='322380'>If</span>
  <span m='322773'>we</span> <span m='323167'>have</span> <span m='323561'>K</span>
  <span m='323955'>states</span> <span m='324348'>in</span> <span m='324742'>our</span>
  <span m='325136'>state</span> <span m='325530'>transition</span> <span m='325923'>diagram</span>
  <span m='326317'>we'll</span> <span m='326711'>need</span> <span m='327105'>log_2(K)</span>
  <span m='327498'>state</span> <span m='327892'>bits,</span> <span m='328286'>rounded</span>
  <span m='328680'>up</span> <span m='328977'>to</span> <span m='329274'>the</span>
  <span m='329571'>next</span> <span m='329869'>integer</span> <span m='330166'>since</span>
  <span m='330463'>we</span> <span m='330760'>don't</span> <span m='331058'>have</span>
  <span m='331355'>fractional</span> <span m='331652'>bits!</span> </p><p><span m='331950'>In</span>
  <span m='332435'>our</span> <span m='332920'>example,</span> <span m='333405'>we</span>
  <span m='333890'>have</span> <span m='334375'>a</span> <span m='334860'>5-state</span>
  <span m='335345'>FSM,</span> <span m='335830'>so</span> <span m='336315'>we'll</span>
  <span m='336800'>need</span> <span m='337285'>3</span> <span m='337770'>state</span>
  <span m='338255'>bits.</span> </p><p><span m='338740'>We</span> <span m='339118'>can</span>
  <span m='339497'>assign</span> <span m='339876'>the</span> <span m='340255'>state</span>
  <span m='340634'>encodings</span> <span m='341013'>in</span> <span m='341392'>any</span>
  <span m='341771'>convenient</span> <span m='342150'>way,</span> <span m='342528'>e.g.,</span>
  <span m='342907'>000</span> <span m='343286'>for</span> <span m='343665'>the</span>
  <span m='344044'>first</span> <span m='344423'>state,</span> <span m='344802'>001</span>
  <span m='345181'>for</span> <span m='345560'>the</span> <span m='346031'>second</span>
  <span m='346503'>state,</span> <span m='346975'>and</span> <span m='347446'>so</span>
  <span m='347918'>on.</span> </p><p><span m='348390'>But</span> <span m='348623'>the</span>
  <span m='348857'>choice</span> <span m='349090'>of</span> <span m='349324'>state</span>
  <span m='349557'>encodings</span> <span m='349791'>can</span> <span m='350024'>have</span>
  <span m='350258'>a</span> <span m='350491'>big</span> <span m='350725'>effect</span>
  <span m='350958'>on</span> <span m='351192'>the</span> <span m='351425'>logic</span>
  <span m='351659'>needed</span> <span m='351892'>to</span> <span m='352126'>implement</span>
  <span m='352360'>the</span> <span m='352700'>truth</span> <span m='353040'>table.</span>
  </p><p><span m='353380'>It's</span> <span m='353713'>actually</span> <span m='354047'>fun</span>
  <span m='354380'>to</span> <span m='354714'>figure</span> <span m='355047'>out</span>
  <span m='355381'>the</span> <span m='355715'>state</span> <span m='356048'>encoding</span>
  <span m='356382'>that</span> <span m='356715'>produces</span> <span m='357049'>the</span>
  <span m='357382'>simplest</span> <span m='357716'>possible</span> <span m='358050'>logic.</span>
  </p><p><span m='360170'>With</span> <span m='360444'>a</span> <span m='360718'>truth</span>
  <span m='360992'>table</span> <span m='361266'>in</span> <span m='361540'>hand,</span>
  <span m='361814'>we</span> <span m='362088'>can</span> <span m='362362'>use</span>
  <span m='362637'>the</span> <span m='362911'>techniques</span> <span m='363185'>from</span>
  <span m='363459'>Chapter</span> <span m='363733'>4</span> <span m='364007'>to</span>
  <span m='364281'>design</span> <span m='364555'>logic</span> <span m='364830'>circuits</span>
  <span m='365192'>that</span> <span m='365554'>implement</span> <span m='365916'>the</span>
  <span m='366278'>combinational</span> <span m='366641'>logic</span> <span m='367003'>for</span>
  <span m='367365'>the</span> <span m='367727'>FSM.</span> </p><p><span m='368090'>Of</span>
  <span m='368458'>course,</span> <span m='368827'>we</span> <span m='369196'>can</span>
  <span m='369565'>take</span> <span m='369934'>the</span> <span m='370303'>easy</span>
  <span m='370672'>way</span> <span m='371041'>out</span> <span m='371410'>and</span>
  <span m='371779'>simply</span> <span m='372148'>use</span> <span m='372517'>a</span>
  <span m='372886'>read-only</span> <span m='373255'>memory</span> <span m='373624'>to</span>
  <span m='373993'>do</span> <span m='374362'>the</span> <span m='374731'>job!</span>
  </p><p><span m='375100'>In</span> <span m='375363'>this</span> <span m='375626'>circuit,</span>
  <span m='375889'>a</span> <span m='376152'>read-only</span> <span m='376415'>memory</span>
  <span m='376678'>is</span> <span m='376941'>used</span> <span m='377205'>to</span>
  <span m='377468'>compute</span> <span m='377731'>the</span> <span m='377994'>next</span>
  <span m='378257'>state</span> <span m='378520'>and</span> <span m='378783'>outputs</span>
  <span m='379046'>from</span> <span m='379310'>the</span> <span m='379850'>current</span>
  <span m='380390'>state</span> <span m='380930'>and</span> <span m='381470'>inputs.</span>
  </p><p><span m='382010'>We're</span> <span m='382310'>encoding</span> <span m='382611'>the</span>
  <span m='382911'>5</span> <span m='383212'>states</span> <span m='383512'>of</span>
  <span m='383813'>the</span> <span m='384113'>FSM</span> <span m='384414'>using</span>
  <span m='384714'>a</span> <span m='385015'>3-bit</span> <span m='385315'>binary</span>
  <span m='385616'>value,</span> <span m='385916'>so</span> <span m='386217'>we</span>
  <span m='386517'>have</span> <span m='386818'>a</span> <span m='387118'>3-bit</span>
  <span m='387419'>state</span> <span m='387720'>register.</span> </p><p><span m='388720'>The</span>
  <span m='389190'>rectangle</span> <span m='389661'>with</span> <span m='390132'>the</span>
  <span m='390603'>edge-triggered</span> <span m='391073'>input</span> <span m='391544'>is</span>
  <span m='392015'>schematic</span> <span m='392486'>shorthand</span> <span m='392956'>for</span>
  <span m='393427'>a</span> <span m='393898'>multi-bit</span> <span m='394369'>register.</span>
  </p><p><span m='394840'>If</span> <span m='395145'>a</span> <span m='395451'>wire</span>
  <span m='395756'>in</span> <span m='396062'>the</span> <span m='396367'>diagram</span>
  <span m='396673'>represents</span> <span m='396978'>a</span> <span m='397284'>multi-bit</span>
  <span m='397590'>signal,</span> <span m='397895'>we</span> <span m='398201'>use</span>
  <span m='398506'>a</span> <span m='398812'>little</span> <span m='399117'>slash</span>
  <span m='399423'>across</span> <span m='399728'>the</span> <span m='400034'>wire</span>
  <span m='400340'>with</span> <span m='400681'>a</span> <span m='401023'>number</span>
  <span m='401365'>to</span> <span m='401706'>indicate</span> <span m='402048'>how</span>
  <span m='402390'>many</span> <span m='402731'>bits</span> <span m='403073'>are</span>
  <span m='403415'>in</span> <span m='403756'>the</span> <span m='404098'>signal.</span>
  </p><p><span m='404440'>In</span> <span m='404746'>this</span> <span m='405052'>example,</span>
  <span m='405358'>both</span> <span m='405664'>current_state</span> <span m='405970'>and</span>
  <span m='406276'>next_state</span> <span m='406582'>are</span> <span m='406888'>3-bit</span>
  <span m='407194'>signals.</span> </p><p><span m='407500'>The</span> <span m='407891'>read-only</span>
  <span m='408282'>memory</span> <span m='408673'>has</span> <span m='409064'>a</span>
  <span m='409455'>total</span> <span m='409846'>of</span> <span m='410237'>4</span>
  <span m='410628'>input</span> <span m='411019'>signals</span> <span m='411410'>-</span>
  <span m='411801'>3</span> <span m='412192'>for</span> <span m='412583'>the</span>
  <span m='412974'>current</span> <span m='413365'>state</span> <span m='413756'>and</span>
  <span m='414147'>1</span> <span m='414538'>for</span> <span m='414930'>the</span>
  <span m='415356'>input</span> <span m='415782'>value</span> <span m='416208'>-</span>
  <span m='416634'>so</span> <span m='417060'>the</span> <span m='417486'>read-only</span>
  <span m='417913'>memory</span> <span m='418339'>has</span> <span m='418765'>2^4</span>
  <span m='419191'>or</span> <span m='419617'>16</span> <span m='420043'>locations,</span>
  <span m='420470'>which</span> <span m='420891'>correspond</span> <span m='421312'>to</span>
  <span m='421733'>the</span> <span m='422154'>16</span> <span m='422575'>rows</span>
  <span m='422996'>in</span> <span m='423417'>the</span> <span m='423838'>truth</span>
  <span m='424259'>table.</span> </p><p><span m='424680'>Each</span> <span m='425038'>location</span>
  <span m='425396'>in</span> <span m='425754'>the</span> <span m='426112'>ROM</span>
  <span m='426471'>supplies</span> <span m='426829'>the</span> <span m='427187'>output</span>
  <span m='427545'>values</span> <span m='427904'>for</span> <span m='428262'>a</span>
  <span m='428620'>particular</span> <span m='428978'>row</span> <span m='429337'>of</span>
  <span m='429695'>the</span> <span m='430053'>truth</span> <span m='430411'>table.</span>
  </p><p><span m='430770'>Since</span> <span m='431037'>we</span> <span m='431305'>have</span>
  <span m='431572'>4</span> <span m='431840'>output</span> <span m='432107'>signals</span>
  <span m='432375'>-</span> <span m='432642'>3</span> <span m='432910'>for</span>
  <span m='433177'>the</span> <span m='433445'>next</span> <span m='433712'>state</span>
  <span m='433980'>and</span> <span m='434247'>1</span> <span m='434515'>for</span>
  <span m='434782'>the</span> <span m='435050'>output</span> <span m='435317'>value</span>
  <span m='435585'>-</span> <span m='435852'>each</span> <span m='436120'>location</span>
  <span m='436851'>supplies</span> <span m='437583'>4</span> <span m='438315'>bits</span>
  <span m='439046'>of</span> <span m='439778'>information.</span> </p><p><span m='440510'>Memories</span>
  <span m='440791'>are</span> <span m='441073'>often</span> <span m='441355'>annotated</span>
  <span m='441637'>with</span> <span m='441919'>their</span> <span m='442201'>number</span>
  <span m='442483'>of</span> <span m='442765'>locations</span> <span m='443046'>and</span>
  <span m='443328'>the</span> <span m='443610'>number</span> <span m='443892'>of</span>
  <span m='444174'>bits</span> <span m='444456'>in</span> <span m='444738'>each</span>
  <span m='445020'>location.</span> </p><p><span m='446500'>So</span> <span m='447016'>our</span>
  <span m='447533'>memory</span> <span m='448050'>is</span> <span m='448566'>a</span>
  <span m='449083'>16-by-4</span> <span m='449600'>ROM:</span> <span m='450116'>16</span>
  <span m='450633'>locations</span> <span m='451150'>of</span> <span m='451666'>4-bits</span>
  <span m='452183'>each.</span> </p><p><span m='452700'>Of</span> <span m='453038'>course,</span>
  <span m='453376'>in</span> <span m='453714'>order</span> <span m='454052'>for</span>
  <span m='454390'>the</span> <span m='454728'>state</span> <span m='455066'>registers</span>
  <span m='455405'>to</span> <span m='455743'>work</span> <span m='456081'>correctly,</span>
  <span m='456419'>we</span> <span m='456757'>need</span> <span m='457095'>to</span>
  <span m='457433'>ensure</span> <span m='457771'>that</span> <span m='458110'>the</span>
  <span m='458732'>dynamic</span> <span m='459354'>discipline</span> <span m='459976'>is</span>
  <span m='460598'>obeyed.</span> </p><p><span m='461220'>We</span> <span m='461489'>can</span>
  <span m='461758'>use</span> <span m='462028'>the</span> <span m='462297'>timing</span>
  <span m='462566'>analysis</span> <span m='462836'>techniques</span> <span m='463105'>described</span>
  <span m='463375'>at</span> <span m='463644'>the</span> <span m='463913'>end</span>
  <span m='464183'>of</span> <span m='464452'>Chapter</span> <span m='464721'>5</span>
  <span m='464991'>to</span> <span m='465260'>check</span> <span m='465530'>that</span>
  <span m='466057'>this</span> <span m='466585'>is</span> <span m='467112'>so.</span>
  </p><p><span m='467640'>For</span> <span m='467921'>now,</span> <span m='468203'>we'll</span>
  <span m='468485'>assume</span> <span m='468767'>that</span> <span m='469049'>the</span>
  <span m='469331'>timing</span> <span m='469613'>of</span> <span m='469895'>transitions</span>
  <span m='470176'>on</span> <span m='470458'>the</span> <span m='470740'>inputs</span>
  <span m='471022'>are</span> <span m='471304'>properly</span> <span m='471586'>synchronized</span>
  <span m='471868'>with</span> <span m='472150'>the</span> <span m='472436'>rising</span>
  <span m='472723'>edges</span> <span m='473010'>of</span> <span m='473296'>the</span>
  <span m='473583'>clock.</span> </p><p><span m='473870'>So</span> <span m='474228'>now</span>
  <span m='474586'>we</span> <span m='474944'>have</span> <span m='475302'>the</span>
  <span m='475660'>FSM</span> <span m='476018'>abstraction</span> <span m='476376'>to</span>
  <span m='476735'>use</span> <span m='477093'>when</span> <span m='477451'>designing</span>
  <span m='477809'>the</span> <span m='478167'>functionality</span> <span m='478525'>of</span>
  <span m='478883'>a</span> <span m='479241'>sequential</span> <span m='479600'>logic</span>
  <span m='480004'>system,</span> <span m='480408'>and</span> <span m='480812'>a</span>
  <span m='481217'>general-purpose</span> <span m='481621'>circuit</span> <span m='482025'>implementation</span>
  <span m='482430'>of</span> <span m='482834'>the</span> <span m='483238'>FSM</span>
  <span m='483642'>using</span> <span m='484047'>a</span> <span m='484451'>ROM</span>
  <span m='484855'>and</span> <span m='485260'>a</span> <span m='485755'>multi-bit</span>
  <span m='486250'>state</span> <span m='486745'>register.</span> </p><p><span m='487240'>Recapping</span>
  <span m='487582'>our</span> <span m='487924'>design</span> <span m='488266'>choices:</span>
  <span m='488608'>the</span> <span m='488950'>output</span> <span m='489292'>bits</span>
  <span m='489634'>can</span> <span m='489976'>be</span> <span m='490318'>strictly</span>
  <span m='490660'>a</span> <span m='491002'>function</span> <span m='491344'>of</span>
  <span m='491686'>the</span> <span m='492028'>current</span> <span m='492370'>state</span>
  <span m='492758'>(the</span> <span m='493146'>FSM</span> <span m='493534'>would</span>
  <span m='493922'>then</span> <span m='494310'>be</span> <span m='494698'>called</span>
  <span m='495086'>a</span> <span m='495474'>Moore</span> <span m='495862'>machine),</span>
  <span m='496250'>or</span> <span m='496491'>they</span> <span m='496733'>can</span>
  <span m='496975'>be</span> <span m='497216'>a</span> <span m='497458'>function</span>
  <span m='497700'>of</span> <span m='497941'>both</span> <span m='498183'>the</span>
  <span m='498425'>current</span> <span m='498666'>state</span> <span m='498908'>and</span>
  <span m='499150'>current</span> <span m='499391'>inputs,</span> <span m='499633'>in</span>
  <span m='499875'>which</span> <span m='500116'>case</span> <span m='500358'>the</span>
  <span m='500600'>FSM</span> <span m='501120'>is</span> <span m='501640'>called</span>
  <span m='502160'>a</span> <span m='502680'>Mealy</span> <span m='503200'>machine.</span>
  </p><p><span m='503720'>We</span> <span m='503972'>can</span> <span m='504225'>choose</span>
  <span m='504477'>the</span> <span m='504730'>number</span> <span m='504983'>of</span>
  <span m='505235'>state</span> <span m='505488'>bits</span> <span m='505741'>-</span>
  <span m='505993'>S</span> <span m='506246'>state</span> <span m='506498'>bits</span>
  <span m='506751'>will</span> <span m='507004'>give</span> <span m='507256'>us</span>
  <span m='507509'>the</span> <span m='507762'>ability</span> <span m='508014'>to</span>
  <span m='508267'>encode</span> <span m='508520'>2^S</span> <span m='509520'>possible</span>
  <span m='510520'>states.</span> </p><p><span m='511520'>Note</span> <span m='511885'>that</span>
  <span m='512250'>each</span> <span m='512615'>extra</span> <span m='512980'>state</span>
  <span m='513345'>bit</span> <span m='513710'>DOUBLES</span> <span m='514075'>the</span>
  <span m='514440'>number</span> <span m='514805'>of</span> <span m='515170'>locations</span>
  <span m='515535'>in</span> <span m='515900'>the</span> <span m='516265'>ROM!</span>
  </p><p><span m='516630'>So</span> <span m='516974'>when</span> <span m='517318'>using</span>
  <span m='517662'>ROMs</span> <span m='518007'>to</span> <span m='518351'>implement</span>
  <span m='518695'>the</span> <span m='519040'>necessary</span> <span m='519384'>logic,</span>
  <span m='519728'>we're</span> <span m='520072'>very</span> <span m='520417'>interested</span>
  <span m='520761'>in</span> <span m='521105'>minimizing</span> <span m='521450'>the</span>
  <span m='522144'>number</span> <span m='522838'>of</span> <span m='523532'>state</span>
  <span m='524226'>bits.</span> </p><p><span m='524920'>The</span> <span m='525353'>waveforms</span>
  <span m='525787'>for</span> <span m='526221'>our</span> <span m='526655'>circuitry</span>
  <span m='527088'>are</span> <span m='527522'>pretty</span> <span m='527956'>straightforward.</span>
  </p><p><span m='528390'>The</span> <span m='528802'>rising</span> <span m='529215'>edge</span>
  <span m='529628'>of</span> <span m='530041'>the</span> <span m='530454'>clock</span>
  <span m='530867'>triggers</span> <span m='531280'>a</span> <span m='531692'>transition</span>
  <span m='532105'>in</span> <span m='532518'>the</span> <span m='532931'>state</span>
  <span m='533344'>register</span> <span m='533757'>outputs.</span> </p><p><span m='534170'>The</span>
  <span m='534457'>ROM</span> <span m='534745'>then</span> <span m='535032'>does</span>
  <span m='535320'>its</span> <span m='535607'>thing,</span> <span m='535895'>calculating</span>
  <span m='536182'>the</span> <span m='536470'>next</span> <span m='536757'>state,</span>
  <span m='537045'>which</span> <span m='537332'>becomes</span> <span m='537620'>valid</span>
  <span m='537907'>at</span> <span m='538195'>some</span> <span m='538482'>point</span>
  <span m='538770'>in</span> <span m='539300'>the</span> <span m='539830'>clock</span>
  <span m='540360'>cycle.</span> </p><p><span m='540890'>This</span> <span m='541227'>is</span>
  <span m='541564'>the</span> <span m='541901'>value</span> <span m='542238'>that</span>
  <span m='542575'>gets</span> <span m='542912'>loaded</span> <span m='543249'>into</span>
  <span m='543586'>the</span> <span m='543923'>state</span> <span m='544260'>registers</span>
  <span m='544597'>at</span> <span m='544934'>the</span> <span m='545271'>next</span>
  <span m='545608'>rising</span> <span m='545945'>clock</span> <span m='546282'>edge.</span>
  </p><p><span m='546620'>This</span> <span m='547015'>process</span> <span m='547411'>repeats</span>
  <span m='547807'>over-and-over</span> <span m='548203'>as</span> <span m='548599'>the</span>
  <span m='548995'>FSM</span> <span m='549390'>follows</span> <span m='549786'>the</span>
  <span m='550182'>state</span> <span m='550578'>transitions</span> <span m='550974'>dictated</span>
  <span m='551370'>by</span> <span m='552006'>the</span> <span m='552642'>state</span>
  <span m='553278'>transition</span> <span m='553914'>diagram.</span> </p><p><span
  m='554550'>There</span> <span m='554964'>are</span> <span m='555378'>a</span> <span
  m='555792'>few</span> <span m='556206'>housekeeping</span> <span m='556620'>details</span>
  <span m='557034'>that</span> <span m='557448'>need</span> <span m='557862'>our</span>
  <span m='558276'>attention.</span> </p><p><span m='558690'>On</span> <span m='558943'>start-up</span>
  <span m='559196'>we</span> <span m='559450'>need</span> <span m='559703'>some</span>
  <span m='559956'>way</span> <span m='560210'>to</span> <span m='560463'>set</span>
  <span m='560716'>the</span> <span m='560970'>initial</span> <span m='561223'>contents</span>
  <span m='561476'>of</span> <span m='561730'>the</span> <span m='561983'>state</span>
  <span m='562236'>register</span> <span m='562490'>to</span> <span m='562743'>the</span>
  <span m='562996'>correct</span> <span m='563250'>encoding</span> <span m='563860'>for</span>
  <span m='564470'>the</span> <span m='565080'>initial</span> <span m='565690'>state.</span>
  </p><p><span m='566300'>Many</span> <span m='566575'>designs</span> <span m='566851'>use</span>
  <span m='567127'>a</span> <span m='567403'>RESET</span> <span m='567679'>signal</span>
  <span m='567955'>that's</span> <span m='568231'>set</span> <span m='568507'>to</span>
  <span m='568782'>1</span> <span m='569058'>to</span> <span m='569334'>force</span>
  <span m='569610'>some</span> <span m='569886'>initial</span> <span m='570162'>state</span>
  <span m='570438'>and</span> <span m='570714'>then</span> <span m='570990'>set</span>
  <span m='571535'>to</span> <span m='572080'>0</span> <span m='572625'>to</span>
  <span m='573170'>start</span> <span m='573715'>execution.</span> </p><p><span m='574260'>We</span>
  <span m='574577'>could</span> <span m='574895'>adopt</span> <span m='575212'>that</span>
  <span m='575530'>approach</span> <span m='575847'>here,</span> <span m='576165'>using</span>
  <span m='576482'>the</span> <span m='576800'>RESET</span> <span m='577117'>signal</span>
  <span m='577435'>to</span> <span m='577752'>select</span> <span m='578070'>an</span>
  <span m='578387'>initial</span> <span m='578705'>value</span> <span m='579022'>to</span>
  <span m='579340'>be</span> <span m='580010'>loaded</span> <span m='580680'>into</span>
  <span m='581350'>the</span> <span m='582020'>state</span> <span m='582690'>register.</span>
  </p><p><span m='583360'>In</span> <span m='583651'>our</span> <span m='583943'>example,</span>
  <span m='584235'>we</span> <span m='584526'>used</span> <span m='584818'>a</span>
  <span m='585110'>3-bit</span> <span m='585401'>state</span> <span m='585693'>encoding</span>
  <span m='585985'>which</span> <span m='586276'>would</span> <span m='586568'>allow</span>
  <span m='586860'>us</span> <span m='587151'>to</span> <span m='587443'>implement</span>
  <span m='587735'>an</span> <span m='588026'>FSM</span> <span m='588318'>with</span>
  <span m='588610'>up</span> <span m='589205'>to</span> <span m='589800'>2^3</span>
  <span m='590395'>=</span> <span m='590990'>8</span> <span m='591585'>states.</span>
  </p><p><span m='592180'>We're</span> <span m='592433'>only</span> <span m='592687'>using</span>
  <span m='592941'>5</span> <span m='593195'>of</span> <span m='593448'>these</span>
  <span m='593702'>encodings,</span> <span m='593956'>which</span> <span m='594210'>means</span>
  <span m='594463'>there</span> <span m='594717'>are</span> <span m='594971'>locations</span>
  <span m='595225'>in</span> <span m='595478'>the</span> <span m='595732'>ROM</span>
  <span m='595986'>we'll</span> <span m='596240'>never</span> <span m='596740'>access.</span>
  </p><p><span m='597240'>If</span> <span m='597604'>that's</span> <span m='597968'>a</span>
  <span m='598332'>concern,</span> <span m='598696'>we</span> <span m='599060'>can</span>
  <span m='599424'>always</span> <span m='599788'>use</span> <span m='600152'>logic</span>
  <span m='600516'>gates</span> <span m='600880'>to</span> <span m='601244'>implement</span>
  <span m='601608'>the</span> <span m='601972'>necessary</span> <span m='602336'>combinational</span>
  <span m='602700'>logic</span> <span m='603640'>instead</span> <span m='604580'>of</span>
  <span m='605520'>ROMs.</span> </p><p><span m='606460'>Suppose</span> <span m='606821'>the</span>
  <span m='607183'>state</span> <span m='607544'>register</span> <span m='607906'>somehow</span>
  <span m='608267'>got</span> <span m='608629'>loaded</span> <span m='608990'>with</span>
  <span m='609352'>one</span> <span m='609713'>of</span> <span m='610075'>the</span>
  <span m='610436'>unused</span> <span m='610798'>encodings?</span> </p><p><span m='611160'>Well,</span>
  <span m='611423'>that</span> <span m='611686'>would</span> <span m='611949'>be</span>
  <span m='612212'>like</span> <span m='612475'>being</span> <span m='612738'>in</span>
  <span m='613001'>a</span> <span m='613265'>state</span> <span m='613528'>that's</span>
  <span m='613791'>not</span> <span m='614054'>listed</span> <span m='614317'>in</span>
  <span m='614580'>our</span> <span m='614843'>state</span> <span m='615106'>transition</span>
  <span m='615370'>diagram.</span> </p><p><span m='616860'>One</span> <span m='617181'>way</span>
  <span m='617503'>to</span> <span m='617825'>defend</span> <span m='618147'>against</span>
  <span m='618469'>this</span> <span m='618791'>problem</span> <span m='619113'>is</span>
  <span m='619435'>design</span> <span m='619756'>the</span> <span m='620078'>ROM</span>
  <span m='620400'>contents</span> <span m='620722'>so</span> <span m='621044'>that</span>
  <span m='621366'>unused</span> <span m='621688'>states</span> <span m='622010'>always</span>
  <span m='622648'>point</span> <span m='623286'>to</span> <span m='623925'>the</span>
  <span m='624563'>initial</span> <span m='625201'>state.</span> </p><p><span m='625840'>In</span>
  <span m='626084'>theory</span> <span m='626329'>the</span> <span m='626574'>problem</span>
  <span m='626818'>should</span> <span m='627063'>never</span> <span m='627308'>arise,</span>
  <span m='627552'>but</span> <span m='627797'>with</span> <span m='628042'>this</span>
  <span m='628287'>fix</span> <span m='628531'>at</span> <span m='628776'>least</span>
  <span m='629021'>it</span> <span m='629265'>won't</span> <span m='629510'>lead</span>
  <span m='629755'>to</span> <span m='630000'>unknown</span> <span m='631025'>behavior.</span>
  </p><p><span m='632050'>We</span> <span m='632485'>mentioned</span> <span m='632920'>earlier</span>
  <span m='633356'>the</span> <span m='633791'>interesting</span> <span m='634226'>problem</span>
  <span m='634662'>of</span> <span m='635097'>finding</span> <span m='635533'>a</span>
  <span m='635968'>state</span> <span m='636403'>encoding</span> <span m='636839'>that</span>
  <span m='637274'>minimized</span> <span m='637710'>the</span> <span m='638716'>combinational</span>
  <span m='639723'>logic.</span> </p><p><span m='640730'>There</span> <span m='641041'>are</span>
  <span m='641352'>computer-aided</span> <span m='641663'>design</span> <span m='641974'>tools</span>
  <span m='642285'>to</span> <span m='642597'>help</span> <span m='642908'>do</span>
  <span m='643219'>this</span> <span m='643530'>as</span> <span m='643841'>part</span>
  <span m='644152'>of</span> <span m='644464'>the</span> <span m='644775'>larger</span>
  <span m='645086'>problem</span> <span m='645397'>of</span> <span m='645708'>finding</span>
  <span m='646020'>minimal</span> <span m='646810'>logic</span> <span m='647600'>implementations</span>
  <span m='648390'>for</span> <span m='649180'>Boolean</span> <span m='649970'>functions.</span>
  </p><p><span m='650760'>Mr.</span> <span m='651026'>Blue</span> <span m='651293'>is</span>
  <span m='651560'>showing</span> <span m='651826'>us</span> <span m='652093'>another</span>
  <span m='652360'>approach</span> <span m='652626'>to</span> <span m='652893'>building</span>
  <span m='653160'>the</span> <span m='653426'>state</span> <span m='653693'>register</span>
  <span m='653960'>for</span> <span m='654226'>the</span> <span m='654493'>combination</span>
  <span m='654760'>lock:</span> <span m='655119'>use</span> <span m='655478'>a</span>
  <span m='655837'>shift</span> <span m='656196'>register</span> <span m='656555'>to</span>
  <span m='656914'>capture</span> <span m='657273'>the</span> <span m='657632'>last</span>
  <span m='657991'>four</span> <span m='658350'>input</span> <span m='658749'>bits,</span>
  <span m='659148'>then</span> <span m='659548'>simply</span> <span m='659947'>look</span>
  <span m='660346'>at</span> <span m='660746'>the</span> <span m='661145'>recorded</span>
  <span m='661545'>history</span> <span m='661944'>to</span> <span m='662343'>determine</span>
  <span m='662743'>if</span> <span m='663142'>it</span> <span m='663541'>matches</span>
  <span m='663941'>the</span> <span m='664340'>combination.</span> </p><p><span m='664740'>No</span>
  <span m='665238'>fancy</span> <span m='665736'>next0state</span> <span m='666234'>logic</span>
  <span m='666732'>here!</span> </p><p><span m='667230'>Finally,</span> <span m='667562'>we</span>
  <span m='667895'>still</span> <span m='668228'>have</span> <span m='668560'>to</span>
  <span m='668893'>address</span> <span m='669226'>the</span> <span m='669558'>problem</span>
  <span m='669891'>of</span> <span m='670224'>ensuring</span> <span m='670556'>that</span>
  <span m='670889'>input</span> <span m='671222'>transitions</span> <span m='671554'>don't</span>
  <span m='671887'>violate</span> <span m='672220'>the</span> <span m='672677'>dynamic</span>
  <span m='673134'>discipline</span> <span m='673591'>for</span> <span m='674048'>the</span>
  <span m='674505'>state</span> <span m='674962'>register.</span> </p><p><span m='675420'>We'll</span>
  <span m='675628'>get</span> <span m='675836'>to</span> <span m='676044'>this</span>
  <span m='676252'>in</span> <span m='676460'>the</span> <span m='676668'>last</span>
  <span m='676876'>section</span> <span m='677084'>of</span> <span m='677292'>this</span>
  <span m='677500'>chapter.</span> </p>
type: course
uid: 577a89897a9e913a0eb1c611a826ec55

---
None