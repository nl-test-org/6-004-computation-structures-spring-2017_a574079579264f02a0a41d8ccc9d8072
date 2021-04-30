---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: p2DReFbW35c
  parent_uid: 5f4f60a17884722a5dab1a177b70df5b
  title: Video-YouTube-Stream
  type: Video
  uid: 25d787c2690b63974b99fe3bbb31842d
- id: 3Play-3Play YouTube id-Stream
  media_location: p2DReFbW35c
  parent_uid: 5f4f60a17884722a5dab1a177b70df5b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: c346c42882f4fc96b2729c8c804b15cd
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/p2DReFbW35c/default.jpg
  parent_uid: 5f4f60a17884722a5dab1a177b70df5b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 5f86a8c02d476fcc503c8d1f42538430
- id: p2DReFbW35c.srt
  parent_uid: 5f4f60a17884722a5dab1a177b70df5b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v7/direct-mapped-caches-7-09-/p2DReFbW35c.srt
  title: 3play caption file
  type: null
  uid: d34ee97207fe633f950383afaa3c32dc
- id: p2DReFbW35c.pdf
  parent_uid: 5f4f60a17884722a5dab1a177b70df5b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v7/direct-mapped-caches-7-09-/p2DReFbW35c.pdf
  title: 3play pdf file
  type: null
  uid: 46cb5d6a5871a03327867402a1c197f0
- id: Caption-3Play YouTube id-SRT
  parent_uid: 5f4f60a17884722a5dab1a177b70df5b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 789ecd4aab90835077ae997ac1b4b55a
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 5f4f60a17884722a5dab1a177b70df5b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: d7ed159e83437e1a2bec19b258d86016
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_14-02-07_300k.mp4
  parent_uid: 5f4f60a17884722a5dab1a177b70df5b
  title: Video-Internet Archive-MP4
  type: Video
  uid: 4798049b735e809b2466752a5fe304dc
inline_embed_id: 148726directmappedcaches70910209100
layout: video
order_index: null
parent_uid: 8179fd8f45e785f81c3487d98155bf64
related_resources_text: ''
short_url: direct-mapped-caches-7-09-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v7/direct-mapped-caches-7-09-
template_type: Embed
title: Direct-mapped Caches (7:09)
transcript: <p><span m='1300'>The</span> <span m='1693'>simplest</span> <span m='2086'>cache</span>
  <span m='2480'>hardware</span> <span m='2873'>consists</span> <span m='3266'>of</span>
  <span m='3660'>an</span> <span m='4053'>SRAM</span> <span m='4446'>with</span> <span
  m='4840'>a</span> <span m='5233'>few</span> <span m='5626'>additional</span> <span
  m='6020'>pieces</span> <span m='6413'>of</span> <span m='6806'>logic.</span> </p><p><span
  m='7200'>The</span> <span m='7528'>cache</span> <span m='7857'>hardware</span> <span
  m='8186'>is</span> <span m='8514'>designed</span> <span m='8843'>so</span> <span
  m='9172'>that</span> <span m='9500'>each</span> <span m='9829'>memory</span> <span
  m='10158'>location</span> <span m='10486'>in</span> <span m='10815'>the</span> <span
  m='11144'>CPU's</span> <span m='11472'>address</span> <span m='11801'>space</span>
  <span m='12130'>maps</span> <span m='12639'>to</span> <span m='13149'>a</span> <span
  m='13659'>particular</span> <span m='14169'>cache</span> <span m='14679'>line,</span>
  <span m='15189'>hence</span> <span m='15699'>the</span> <span m='16209'>name</span>
  <span m='16719'>"direct-mapped</span> <span m='17229'>(DM)</span> <span m='17739'>cache".</span>
  </p><p><span m='18249'>There</span> <span m='18550'>are,</span> <span m='18852'>of</span>
  <span m='19154'>course,</span> <span m='19456'>many</span> <span m='19758'>more</span>
  <span m='20060'>memory</span> <span m='20362'>locations</span> <span m='20664'>then</span>
  <span m='20965'>there</span> <span m='21267'>are</span> <span m='21569'>cache</span>
  <span m='21871'>lines,</span> <span m='22173'>so</span> <span m='22475'>many</span>
  <span m='22777'>addresses</span> <span m='23079'>are</span> <span m='23319'>mapped</span>
  <span m='23560'>to</span> <span m='23800'>the</span> <span m='24041'>same</span>
  <span m='24281'>cache</span> <span m='24522'>line</span> <span m='24763'>and</span>
  <span m='25003'>the</span> <span m='25244'>cache</span> <span m='25484'>will</span>
  <span m='25725'>only</span> <span m='25965'>be</span> <span m='26206'>able</span>
  <span m='26447'>to</span> <span m='26687'>hold</span> <span m='26928'>the</span>
  <span m='27168'>data</span> <span m='27409'>for</span> <span m='27650'>one</span>
  <span m='28152'>of</span> <span m='28655'>those</span> <span m='29158'>addresses</span>
  <span m='29660'>at</span> <span m='30163'>a</span> <span m='30666'>time.</span>
  </p><p><span m='31169'>The</span> <span m='31554'>operation</span> <span m='31939'>of</span>
  <span m='32324'>a</span> <span m='32709'>DM</span> <span m='33094'>cache</span>
  <span m='33479'>is</span> <span m='33864'>straightforward.</span> </p><p><span m='34250'>We'll</span>
  <span m='34543'>use</span> <span m='34837'>part</span> <span m='35130'>of</span>
  <span m='35424'>the</span> <span m='35717'>incoming</span> <span m='36011'>address</span>
  <span m='36304'>as</span> <span m='36598'>an</span> <span m='36891'>index</span>
  <span m='37185'>to</span> <span m='37478'>select</span> <span m='37772'>a</span>
  <span m='38065'>single</span> <span m='38359'>cache</span> <span m='38652'>line</span>
  <span m='38946'>to</span> <span m='39240'>be</span> <span m='40069'>searched.</span>
  </p><p><span m='40899'>The</span> <span m='41247'>"search"</span> <span m='41596'>consists</span>
  <span m='41945'>of</span> <span m='42293'>comparing</span> <span m='42642'>the</span>
  <span m='42991'>rest</span> <span m='43339'>of</span> <span m='43688'>the</span>
  <span m='44037'>incoming</span> <span m='44385'>address</span> <span m='44734'>with</span>
  <span m='45083'>the</span> <span m='45431'>address</span> <span m='45780'>tag</span>
  <span m='46129'>of</span> <span m='46623'>the</span> <span m='47117'>selected</span>
  <span m='47611'>cache</span> <span m='48105'>line.</span> </p><p><span m='48600'>If</span>
  <span m='48908'>the</span> <span m='49216'>tag</span> <span m='49524'>matches</span>
  <span m='49832'>the</span> <span m='50140'>address,</span> <span m='50449'>there's</span>
  <span m='50757'>a</span> <span m='51065'>cache</span> <span m='51373'>hit</span>
  <span m='51681'>and</span> <span m='51989'>we</span> <span m='52298'>can</span>
  <span m='52606'>immediately</span> <span m='52914'>use</span> <span m='53222'>the</span>
  <span m='53530'>data</span> <span m='53839'>in</span> <span m='54456'>the</span>
  <span m='55073'>cache</span> <span m='55690'>to</span> <span m='56308'>satisfy</span>
  <span m='56925'>the</span> <span m='57542'>request.</span> </p><p><span m='58160'>In</span>
  <span m='58478'>this</span> <span m='58796'>design,</span> <span m='59114'>we've</span>
  <span m='59432'>included</span> <span m='59751'>an</span> <span m='60069'>additional</span>
  <span m='60387'>"valid</span> <span m='60705'>bit"</span> <span m='61024'>which</span>
  <span m='61342'>is</span> <span m='61660'>1</span> <span m='61978'>when</span> <span
  m='62297'>the</span> <span m='62615'>tag</span> <span m='62933'>and</span> <span
  m='63251'>data</span> <span m='63570'>fields</span> <span m='64325'>hold</span>
  <span m='65080'>valid</span> <span m='65835'>information.</span> </p><p><span m='66590'>The</span>
  <span m='66896'>valid</span> <span m='67203'>bit</span> <span m='67510'>for</span>
  <span m='67816'>each</span> <span m='68123'>cache</span> <span m='68430'>line</span>
  <span m='68736'>is</span> <span m='69043'>initialized</span> <span m='69350'>to</span>
  <span m='69656'>0</span> <span m='69963'>when</span> <span m='70270'>the</span>
  <span m='70576'>cache</span> <span m='70883'>is</span> <span m='71190'>powered</span>
  <span m='71496'>on,</span> <span m='71803'>indicating</span> <span m='72110'>that</span>
  <span m='72730'>all</span> <span m='73350'>cache</span> <span m='73970'>lines</span>
  <span m='74590'>are</span> <span m='75210'>empty.</span> </p><p><span m='75830'>As</span>
  <span m='76105'>data</span> <span m='76381'>is</span> <span m='76657'>brought</span>
  <span m='76933'>into</span> <span m='77208'>the</span> <span m='77484'>cache,</span>
  <span m='77760'>the</span> <span m='78036'>valid</span> <span m='78312'>bit</span>
  <span m='78587'>is</span> <span m='78863'>set</span> <span m='79139'>to</span> <span
  m='79415'>1</span> <span m='79691'>when</span> <span m='79966'>the</span> <span
  m='80242'>cache</span> <span m='80518'>line's</span> <span m='80794'>tag</span>
  <span m='81070'>and</span> <span m='81678'>data</span> <span m='82286'>fields</span>
  <span m='82894'>are</span> <span m='83502'>filled.</span> </p><p><span m='84110'>The</span>
  <span m='84365'>CPU</span> <span m='84621'>can</span> <span m='84877'>request</span>
  <span m='85133'>that</span> <span m='85389'>the</span> <span m='85645'>valid</span>
  <span m='85901'>bit</span> <span m='86157'>be</span> <span m='86412'>cleared</span>
  <span m='86668'>for</span> <span m='86924'>a</span> <span m='87180'>particular</span>
  <span m='87436'>cache</span> <span m='87692'>line</span> <span m='87948'>-</span>
  <span m='88204'>this</span> <span m='88460'>is</span> <span m='88878'>called</span>
  <span m='89296'>"flushing</span> <span m='89714'>the</span> <span m='90132'>cache".</span>
  </p><p><span m='90550'>If,</span> <span m='90880'>for</span> <span m='91211'>example,</span>
  <span m='91541'>the</span> <span m='91872'>CPU</span> <span m='92203'>initiates</span>
  <span m='92533'>a</span> <span m='92864'>read</span> <span m='93195'>from</span>
  <span m='93525'>disk,</span> <span m='93856'>the</span> <span m='94186'>disk</span>
  <span m='94517'>hardware</span> <span m='94848'>will</span> <span m='95178'>read</span>
  <span m='95509'>its</span> <span m='95840'>data</span> <span m='96260'>into</span>
  <span m='96681'>a</span> <span m='97101'>block</span> <span m='97522'>of</span>
  <span m='97943'>main</span> <span m='98363'>memory,</span> <span m='98784'>so</span>
  <span m='99205'>any</span> <span m='99625'>cached</span> <span m='100046'>values</span>
  <span m='100466'>for</span> <span m='100887'>that</span> <span m='101308'>block</span>
  <span m='101728'>will</span> <span m='102149'>out-of-date.</span> </p><p><span m='102570'>So</span>
  <span m='102956'>the</span> <span m='103342'>CPU</span> <span m='103728'>will</span>
  <span m='104115'>flush</span> <span m='104501'>those</span> <span m='104887'>locations</span>
  <span m='105273'>from</span> <span m='105660'>the</span> <span m='106046'>cache</span>
  <span m='106432'>by</span> <span m='106818'>marking</span> <span m='107205'>any</span>
  <span m='107591'>matching</span> <span m='107977'>cache</span> <span m='108363'>lines</span>
  <span m='108750'>as</span> <span m='109680'>invalid.</span> </p><p><span m='110610'>Let's</span>
  <span m='110941'>see</span> <span m='111273'>how</span> <span m='111605'>this</span>
  <span m='111936'>works</span> <span m='112268'>using</span> <span m='112600'>a</span>
  <span m='112931'>small</span> <span m='113263'>DM</span> <span m='113595'>cache</span>
  <span m='113926'>with</span> <span m='114258'>8</span> <span m='114590'>lines</span>
  <span m='114921'>where</span> <span m='115253'>each</span> <span m='115585'>cache</span>
  <span m='115916'>line</span> <span m='116248'>contains</span> <span m='116580'>a</span>
  <span m='117097'>single</span> <span m='117614'>word</span> <span m='118131'>(4</span>
  <span m='118648'>bytes)</span> <span m='119165'>of</span> <span m='119682'>data.</span>
  </p><p><span m='120200'>Here's</span> <span m='120671'>a</span> <span m='121143'>CPU</span>
  <span m='121615'>request</span> <span m='122087'>for</span> <span m='122559'>the</span>
  <span m='123030'>location</span> <span m='123502'>at</span> <span m='123974'>byte</span>
  <span m='124446'>address</span> <span m='124918'>0xE8.</span> </p><p><span m='125390'>Since</span>
  <span m='125674'>there</span> <span m='125959'>4</span> <span m='126243'>bytes</span>
  <span m='126528'>of</span> <span m='126812'>data</span> <span m='127097'>in</span>
  <span m='127382'>each</span> <span m='127666'>cache</span> <span m='127951'>line,</span>
  <span m='128235'>the</span> <span m='128520'>bottom</span> <span m='128805'>2</span>
  <span m='129089'>address</span> <span m='129374'>bits</span> <span m='129658'>indicate</span>
  <span m='129943'>the</span> <span m='130228'>appropriate</span> <span m='130822'>byte</span>
  <span m='131417'>offset</span> <span m='132011'>into</span> <span m='132606'>the</span>
  <span m='133200'>cached</span> <span m='133795'>word.</span> </p><p><span m='134390'>Since</span>
  <span m='134802'>the</span> <span m='135214'>cache</span> <span m='135626'>deals</span>
  <span m='136038'>only</span> <span m='136450'>with</span> <span m='136862'>word</span>
  <span m='137275'>accesses,</span> <span m='137687'>the</span> <span m='138099'>byte</span>
  <span m='138511'>offset</span> <span m='138923'>bits</span> <span m='139335'>aren't</span>
  <span m='139747'>used.</span> </p><p><span m='140160'>Next,</span> <span m='140543'>we'll</span>
  <span m='140926'>need</span> <span m='141310'>to</span> <span m='141693'>use</span>
  <span m='142076'>3</span> <span m='142460'>address</span> <span m='142843'>bits</span>
  <span m='143226'>to</span> <span m='143610'>select</span> <span m='143993'>which</span>
  <span m='144376'>of</span> <span m='144760'>the</span> <span m='145143'>8</span>
  <span m='145526'>cache</span> <span m='145910'>lines</span> <span m='146293'>to</span>
  <span m='146676'>search.</span> </p><p><span m='147060'>We</span> <span m='147416'>choose</span>
  <span m='147773'>these</span> <span m='148130'>cache</span> <span m='148487'>index</span>
  <span m='148844'>bits</span> <span m='149201'>from</span> <span m='149558'>the</span>
  <span m='149915'>low-order</span> <span m='150272'>bits</span> <span m='150629'>of</span>
  <span m='150986'>the</span> <span m='151343'>address.</span> </p><p><span m='151700'>Why?</span>
  </p><p><span m='152750'>Well,</span> <span m='153420'>it's</span> <span m='154090'>because</span>
  <span m='154760'>of</span> <span m='155430'>locality.</span> </p><p><span m='156100'>The</span>
  <span m='156370'>principle</span> <span m='156641'>of</span> <span m='156911'>locality</span>
  <span m='157182'>tells</span> <span m='157453'>us</span> <span m='157723'>that</span>
  <span m='157994'>it's</span> <span m='158265'>likely</span> <span m='158535'>that</span>
  <span m='158806'>the</span> <span m='159076'>CPU</span> <span m='159347'>will</span>
  <span m='159618'>be</span> <span m='159888'>requesting</span> <span m='160159'>nearby</span>
  <span m='160430'>addresses</span> <span m='160800'>and</span> <span m='161170'>for</span>
  <span m='161540'>the</span> <span m='161910'>cache</span> <span m='162280'>to</span>
  <span m='162650'>perform</span> <span m='163020'>well,</span> <span m='163390'>we'd</span>
  <span m='163760'>like</span> <span m='164130'>to</span> <span m='164500'>arrange</span>
  <span m='164870'>for</span> <span m='165240'>nearby</span> <span m='165610'>locations</span>
  <span m='165980'>to</span> <span m='166320'>be</span> <span m='166660'>able</span>
  <span m='167000'>to</span> <span m='167340'>be</span> <span m='167680'>held</span>
  <span m='168020'>in</span> <span m='168360'>the</span> <span m='168700'>cache</span>
  <span m='169040'>at</span> <span m='169380'>the</span> <span m='169720'>same</span>
  <span m='170060'>time.</span> </p><p><span m='170400'>This</span> <span m='170817'>means</span>
  <span m='171235'>that</span> <span m='171653'>nearby</span> <span m='172071'>locations</span>
  <span m='172489'>will</span> <span m='172907'>have</span> <span m='173325'>to</span>
  <span m='173742'>be</span> <span m='174160'>mapped</span> <span m='174578'>to</span>
  <span m='174996'>different</span> <span m='175414'>cache</span> <span m='175832'>lines.</span>
  </p><p><span m='176250'>The</span> <span m='176609'>addresses</span> <span m='176968'>of</span>
  <span m='177327'>nearby</span> <span m='177687'>locations</span> <span m='178046'>differ</span>
  <span m='178405'>in</span> <span m='178765'>their</span> <span m='179124'>low-order</span>
  <span m='179483'>address</span> <span m='179842'>bits,</span> <span m='180202'>so</span>
  <span m='180561'>we'll</span> <span m='180920'>use</span> <span m='181280'>those</span>
  <span m='181627'>bits</span> <span m='181975'>as</span> <span m='182322'>the</span>
  <span m='182670'>cache</span> <span m='183017'>index</span> <span m='183365'>bits</span>
  <span m='183712'>-</span> <span m='184060'>that</span> <span m='184407'>way</span>
  <span m='184755'>nearby</span> <span m='185102'>locations</span> <span m='185450'>will</span>
  <span m='185797'>map</span> <span m='186145'>to</span> <span m='186492'>different</span>
  <span m='186840'>cache</span> <span m='188105'>lines.</span> </p><p><span m='189370'>The</span>
  <span m='189738'>data,</span> <span m='190106'>tag</span> <span m='190474'>and</span>
  <span m='190842'>valid</span> <span m='191211'>bits</span> <span m='191579'>selected</span>
  <span m='191947'>by</span> <span m='192315'>the</span> <span m='192684'>cache</span>
  <span m='193052'>line</span> <span m='193420'>index</span> <span m='193788'>are</span>
  <span m='194157'>read</span> <span m='194525'>from</span> <span m='194893'>the</span>
  <span m='195261'>SRAM.</span> </p><p><span m='195630'>To</span> <span m='195933'>complete</span>
  <span m='196237'>the</span> <span m='196541'>search,</span> <span m='196845'>we</span>
  <span m='197148'>check</span> <span m='197452'>the</span> <span m='197756'>remaining</span>
  <span m='198060'>address</span> <span m='198363'>against</span> <span m='198667'>the</span>
  <span m='198971'>tag</span> <span m='199275'>field</span> <span m='199578'>of</span>
  <span m='199882'>the</span> <span m='200186'>cache.</span> </p><p><span m='200490'>If</span>
  <span m='200762'>they're</span> <span m='201035'>equal</span> <span m='201307'>and</span>
  <span m='201580'>the</span> <span m='201852'>valid</span> <span m='202125'>bit</span>
  <span m='202397'>is</span> <span m='202670'>1,</span> <span m='202942'>we</span>
  <span m='203215'>have</span> <span m='203487'>a</span> <span m='203760'>cache</span>
  <span m='204032'>hit,</span> <span m='204305'>and</span> <span m='204577'>the</span>
  <span m='204850'>data</span> <span m='205122'>field</span> <span m='205395'>can</span>
  <span m='205667'>be</span> <span m='205940'>used</span> <span m='206700'>to</span>
  <span m='207460'>satisfy</span> <span m='208220'>the</span> <span m='208980'>request.</span>
  </p><p><span m='209740'>How</span> <span m='210134'>come</span> <span m='210528'>the</span>
  <span m='210922'>tag</span> <span m='211317'>field</span> <span m='211711'>isn't</span>
  <span m='212105'>32</span> <span m='212500'>bits,</span> <span m='212894'>since</span>
  <span m='213288'>we</span> <span m='213682'>have</span> <span m='214077'>a</span>
  <span m='214471'>32-bit</span> <span m='214865'>address?</span> </p><p><span m='215260'>We</span>
  <span m='215502'>could</span> <span m='215744'>have</span> <span m='215986'>done</span>
  <span m='216228'>that,</span> <span m='216471'>but</span> <span m='216713'>since</span>
  <span m='216955'>all</span> <span m='217197'>values</span> <span m='217440'>stored</span>
  <span m='217682'>in</span> <span m='217924'>cache</span> <span m='218166'>line</span>
  <span m='218408'>2</span> <span m='218651'>will</span> <span m='218893'>have</span>
  <span m='219135'>the</span> <span m='219377'>same</span> <span m='219620'>index</span>
  <span m='220022'>bits</span> <span m='220424'>(0b010),</span> <span m='220826'>we</span>
  <span m='221228'>saved</span> <span m='221631'>a</span> <span m='222033'>few</span>
  <span m='222435'>bits</span> <span m='222837'>of</span> <span m='223240'>SRAM</span>
  <span m='223642'>and</span> <span m='224044'>chose</span> <span m='224446'>not</span>
  <span m='224848'>save</span> <span m='225251'>those</span> <span m='225653'>bits</span>
  <span m='226055'>in</span> <span m='226457'>the</span> <span m='226860'>tag.</span>
  </p><p><span m='227860'>In</span> <span m='228140'>other</span> <span m='228420'>words,</span>
  <span m='228700'>there's</span> <span m='228980'>no</span> <span m='229260'>point</span>
  <span m='229540'>in</span> <span m='229820'>using</span> <span m='230100'>SRAM</span>
  <span m='230380'>to</span> <span m='230660'>save</span> <span m='230940'>bits</span>
  <span m='231220'>we</span> <span m='231500'>can</span> <span m='231780'>generate</span>
  <span m='232060'>from</span> <span m='232340'>the</span> <span m='232620'>incoming</span>
  <span m='233900'>address.</span> </p><p><span m='235180'>So</span> <span m='235580'>the</span>
  <span m='235980'>cache</span> <span m='236380'>hardware</span> <span m='236780'>in</span>
  <span m='237180'>this</span> <span m='237580'>example</span> <span m='237980'>is</span>
  <span m='238380'>an</span> <span m='238780'>8-location</span> <span m='239180'>by</span>
  <span m='239580'>60</span> <span m='239980'>bit</span> <span m='240380'>SRAM</span>
  <span m='240780'>plus</span> <span m='241180'>a</span> <span m='241580'>27-bit</span>
  <span m='241980'>comparator</span> <span m='242380'>and</span> <span m='242850'>a</span>
  <span m='243320'>single</span> <span m='243790'>AND</span> <span m='244260'>gate.</span>
  </p><p><span m='244730'>The</span> <span m='245052'>cache</span> <span m='245375'>access</span>
  <span m='245698'>time</span> <span m='246021'>is</span> <span m='246344'>the</span>
  <span m='246667'>access</span> <span m='246990'>time</span> <span m='247313'>of</span>
  <span m='247636'>the</span> <span m='247959'>SRAM</span> <span m='248282'>plus</span>
  <span m='248605'>the</span> <span m='248928'>propagation</span> <span m='249251'>delays</span>
  <span m='249574'>of</span> <span m='249897'>the</span> <span m='250220'>comparator</span>
  <span m='250779'>and</span> <span m='251339'>AND</span> <span m='251899'>gate.</span>
  </p><p><span m='252459'>About</span> <span m='252851'>as</span> <span m='253243'>simple</span>
  <span m='253635'>and</span> <span m='254027'>fast</span> <span m='254419'>as</span>
  <span m='254811'>we</span> <span m='255203'>could</span> <span m='255595'>hope</span>
  <span m='255987'>for.</span> </p><p><span m='256380'>The</span> <span m='256738'>downside</span>
  <span m='257097'>of</span> <span m='257456'>the</span> <span m='257815'>simplicity</span>
  <span m='258173'>is</span> <span m='258532'>that</span> <span m='258891'>for</span>
  <span m='259250'>each</span> <span m='259608'>CPU</span> <span m='259967'>request,</span>
  <span m='260326'>we're</span> <span m='260685'>only</span> <span m='261043'>looking</span>
  <span m='261402'>in</span> <span m='261761'>a</span> <span m='262120'>single</span>
  <span m='262576'>cache</span> <span m='263033'>location</span> <span m='263489'>to</span>
  <span m='263946'>see</span> <span m='264402'>if</span> <span m='264859'>the</span>
  <span m='265316'>cache</span> <span m='265772'>holds</span> <span m='266229'>the</span>
  <span m='266685'>desired</span> <span m='267142'>data.</span> </p><p><span m='267599'>Not</span>
  <span m='267969'>much</span> <span m='268339'>of</span> <span m='268709'>"search"</span>
  <span m='269079'>is</span> <span m='269449'>it?</span> </p><p><span m='269819'>But</span>
  <span m='270148'>the</span> <span m='270477'>mapping</span> <span m='270806'>of</span>
  <span m='271136'>addresses</span> <span m='271465'>to</span> <span m='271794'>cache</span>
  <span m='272123'>lines</span> <span m='272453'>helps</span> <span m='272782'>us</span>
  <span m='273111'>out</span> <span m='273440'>here.</span> </p><p><span m='273770'>Using</span>
  <span m='274085'>the</span> <span m='274400'>low-order</span> <span m='274715'>address</span>
  <span m='275030'>bit</span> <span m='275345'>as</span> <span m='275660'>the</span>
  <span m='275975'>cache</span> <span m='276290'>index,</span> <span m='276605'>we've</span>
  <span m='276920'>arranged</span> <span m='277235'>for</span> <span m='277550'>nearby</span>
  <span m='277865'>locations</span> <span m='278180'>to</span> <span m='278504'>be</span>
  <span m='278828'>mapped</span> <span m='279152'>to</span> <span m='279476'>different</span>
  <span m='279800'>cache</span> <span m='280124'>lines.</span> </p><p><span m='280449'>So,</span>
  <span m='280791'>for</span> <span m='281133'>example,</span> <span m='281475'>if</span>
  <span m='281817'>the</span> <span m='282160'>CPU</span> <span m='282502'>were</span>
  <span m='282844'>executing</span> <span m='283186'>an</span> <span m='283528'>8-instruction</span>
  <span m='283871'>loop,</span> <span m='284213'>all</span> <span m='284555'>8</span>
  <span m='284897'>instructions</span> <span m='285240'>can</span> <span m='285484'>be</span>
  <span m='285729'>held</span> <span m='285974'>in</span> <span m='286219'>the</span>
  <span m='286464'>cache</span> <span m='286709'>at</span> <span m='286954'>the</span>
  <span m='287199'>same</span> <span m='287444'>time.</span> </p><p><span m='287689'>A</span>
  <span m='288202'>more</span> <span m='288715'>complicated</span> <span m='289228'>search</span>
  <span m='289741'>mechanism</span> <span m='290255'>couldn't</span> <span m='290768'>improve</span>
  <span m='291281'>on</span> <span m='291794'>that.</span> </p><p><span m='292308'>The</span>
  <span m='292652'>bottom</span> <span m='292997'>line:</span> <span m='293342'>this</span>
  <span m='293686'>extremely</span> <span m='294031'>simple</span> <span m='294376'>"search"</span>
  <span m='294721'>is</span> <span m='295065'>sufficient</span> <span m='295410'>to</span>
  <span m='295755'>get</span> <span m='296100'>good</span> <span m='296444'>cache</span>
  <span m='296789'>hit</span> <span m='297134'>ratios</span> <span m='297479'>for</span>
  <span m='297957'>the</span> <span m='298435'>cases</span> <span m='298914'>we</span>
  <span m='299392'>care</span> <span m='299870'>about.</span> </p><p><span m='300349'>Let's</span>
  <span m='300721'>try</span> <span m='301094'>a</span> <span m='301466'>few</span>
  <span m='301839'>more</span> <span m='302211'>examples,</span> <span m='302584'>in</span>
  <span m='302956'>this</span> <span m='303329'>case</span> <span m='303702'>using</span>
  <span m='304074'>a</span> <span m='304447'>DM</span> <span m='304819'>cache</span>
  <span m='305192'>with</span> <span m='305564'>64</span> <span m='305937'>lines.</span>
  </p><p><span m='306310'>Suppose</span> <span m='306834'>the</span> <span m='307358'>cache</span>
  <span m='307882'>gets</span> <span m='308406'>a</span> <span m='308930'>read</span>
  <span m='309454'>request</span> <span m='309978'>for</span> <span m='310502'>location</span>
  <span m='311026'>0x400C.</span> </p><p><span m='311550'>To</span> <span m='311838'>see</span>
  <span m='312126'>how</span> <span m='312415'>the</span> <span m='312703'>request</span>
  <span m='312991'>is</span> <span m='313280'>processed,</span> <span m='313568'>we</span>
  <span m='313856'>first</span> <span m='314145'>write</span> <span m='314433'>the</span>
  <span m='314721'>address</span> <span m='315010'>in</span> <span m='315298'>binary</span>
  <span m='315586'>so</span> <span m='315875'>we</span> <span m='316163'>can</span>
  <span m='316451'>easily</span> <span m='316740'>divide</span> <span m='317247'>it</span>
  <span m='317755'>into</span> <span m='318263'>the</span> <span m='318771'>offset,</span>
  <span m='319278'>index</span> <span m='319786'>and</span> <span m='320294'>tag</span>
  <span m='320802'>fields.</span> </p><p><span m='321310'>For</span> <span m='321629'>this</span>
  <span m='321949'>address</span> <span m='322269'>the</span> <span m='322589'>offset</span>
  <span m='322909'>bits</span> <span m='323229'>have</span> <span m='323549'>the</span>
  <span m='323869'>value</span> <span m='324189'>0,</span> <span m='324509'>the</span>
  <span m='324829'>cache</span> <span m='325149'>line</span> <span m='325469'>index</span>
  <span m='325789'>bits</span> <span m='326109'>have</span> <span m='326429'>the</span>
  <span m='326749'>value</span> <span m='327275'>3,</span> <span m='327801'>and</span>
  <span m='328327'>the</span> <span m='328853'>tag</span> <span m='329379'>bits</span>
  <span m='329905'>have</span> <span m='330431'>the</span> <span m='330957'>value</span>
  <span m='331483'>0x40.</span> </p><p><span m='332009'>So</span> <span m='332333'>the</span>
  <span m='332657'>tag</span> <span m='332981'>field</span> <span m='333305'>of</span>
  <span m='333629'>cache</span> <span m='333954'>line</span> <span m='334278'>3</span>
  <span m='334602'>is</span> <span m='334926'>compared</span> <span m='335250'>with</span>
  <span m='335574'>the</span> <span m='335899'>tag</span> <span m='336223'>field</span>
  <span m='336547'>of</span> <span m='336871'>the</span> <span m='337195'>address.</span>
  </p><p><span m='337520'>Since</span> <span m='337768'>there's</span> <span m='338016'>a</span>
  <span m='338265'>match,</span> <span m='338513'>we</span> <span m='338762'>have</span>
  <span m='339010'>a</span> <span m='339258'>cache</span> <span m='339507'>hit</span>
  <span m='339755'>and</span> <span m='340004'>the</span> <span m='340252'>value</span>
  <span m='340501'>in</span> <span m='340749'>the</span> <span m='340997'>data</span>
  <span m='341246'>field</span> <span m='341494'>of</span> <span m='341743'>cache</span>
  <span m='341991'>line</span> <span m='342240'>can</span> <span m='342781'>be</span>
  <span m='343322'>used</span> <span m='343863'>to</span> <span m='344405'>satisfy</span>
  <span m='344946'>the</span> <span m='345487'>request.</span> </p><p><span m='346029'>Would</span>
  <span m='346516'>an</span> <span m='347003'>access</span> <span m='347490'>to</span>
  <span m='347977'>location</span> <span m='348464'>0x4008</span> <span m='348951'>be</span>
  <span m='349438'>a</span> <span m='349925'>cache</span> <span m='350412'>hit?</span>
  </p><p><span m='350900'>This</span> <span m='351163'>address</span> <span m='351426'>is</span>
  <span m='351690'>similar</span> <span m='351953'>to</span> <span m='352217'>that</span>
  <span m='352480'>in</span> <span m='352744'>our</span> <span m='353007'>first</span>
  <span m='353271'>example,</span> <span m='353534'>except</span> <span m='353798'>the</span>
  <span m='354061'>cache</span> <span m='354325'>line</span> <span m='354588'>index</span>
  <span m='354852'>is</span> <span m='355115'>now</span> <span m='355379'>2</span>
  <span m='356146'>instead</span> <span m='356914'>of</span> <span m='357681'>3.</span>
  </p><p><span m='358449'>Looking</span> <span m='358775'>in</span> <span m='359102'>cache</span>
  <span m='359429'>line</span> <span m='359755'>2,</span> <span m='360082'>we</span>
  <span m='360409'>that</span> <span m='360736'>its</span> <span m='361062'>tag</span>
  <span m='361389'>field</span> <span m='361716'>(0x58)</span> <span m='362042'>doesn't</span>
  <span m='362369'>match</span> <span m='362696'>the</span> <span m='363023'>tag</span>
  <span m='363349'>field</span> <span m='363676'>in</span> <span m='364003'>the</span>
  <span m='364330'>address</span> <span m='364712'>(0x40),</span> <span m='365095'>so</span>
  <span m='365478'>this</span> <span m='365861'>access</span> <span m='366244'>would</span>
  <span m='366627'>be</span> <span m='367010'>a</span> <span m='367393'>cache</span>
  <span m='367776'>miss.</span> </p><p><span m='368159'>What</span> <span m='368515'>are</span>
  <span m='368871'>the</span> <span m='369228'>addresses</span> <span m='369584'>of</span>
  <span m='369940'>the</span> <span m='370297'>words</span> <span m='370653'>held</span>
  <span m='371009'>by</span> <span m='371366'>cache</span> <span m='371722'>lines</span>
  <span m='372079'>0,</span> <span m='372435'>1,</span> <span m='372791'>and</span>
  <span m='373148'>2,</span> <span m='373504'>all</span> <span m='373860'>of</span>
  <span m='374217'>which</span> <span m='374573'>have</span> <span m='374930'>the</span>
  <span m='375410'>same</span> <span m='375890'>tag</span> <span m='376370'>field?</span>
  </p><p><span m='376850'>Well,</span> <span m='377434'>we</span> <span m='378018'>can</span>
  <span m='378603'>run</span> <span m='379187'>the</span> <span m='379772'>address</span>
  <span m='380356'>matching</span> <span m='380941'>process</span> <span m='381525'>backwards!</span>
  </p><p><span m='382110'>For</span> <span m='382351'>an</span> <span m='382593'>address</span>
  <span m='382835'>to</span> <span m='383076'>match</span> <span m='383318'>these</span>
  <span m='383560'>three</span> <span m='383801'>cache</span> <span m='384043'>lines</span>
  <span m='384285'>it</span> <span m='384527'>would</span> <span m='384768'>have</span>
  <span m='385010'>look</span> <span m='385252'>like</span> <span m='385493'>the</span>
  <span m='385735'>binary</span> <span m='385977'>shown</span> <span m='386219'>here,</span>
  <span m='386478'>where</span> <span m='386737'>we've</span> <span m='386997'>used</span>
  <span m='387256'>the</span> <span m='387516'>information</span> <span m='387775'>in</span>
  <span m='388035'>the</span> <span m='388294'>cache</span> <span m='388553'>tag</span>
  <span m='388813'>field</span> <span m='389072'>to</span> <span m='389332'>fill</span>
  <span m='389591'>in</span> <span m='389851'>the</span> <span m='390110'>high-order</span>
  <span m='390370'>address</span> <span m='390812'>bits</span> <span m='391255'>and</span>
  <span m='391697'>low-order</span> <span m='392140'>address</span> <span m='392582'>bits</span>
  <span m='393025'>will</span> <span m='393467'>come</span> <span m='393910'>from</span>
  <span m='394352'>the</span> <span m='394795'>index</span> <span m='395237'>value.</span>
  </p><p><span m='395680'>If</span> <span m='395967'>we</span> <span m='396255'>fill</span>
  <span m='396543'>in</span> <span m='396831'>the</span> <span m='397119'>indices</span>
  <span m='397407'>0,</span> <span m='397695'>1,</span> <span m='397983'>and</span>
  <span m='398271'>2,</span> <span m='398558'>then</span> <span m='398846'>convert</span>
  <span m='399134'>the</span> <span m='399422'>resulting</span> <span m='399710'>binary</span>
  <span m='399998'>to</span> <span m='400286'>hex</span> <span m='400574'>we</span>
  <span m='400862'>get</span> <span m='401150'>0x5800,</span> <span m='401591'>0x5804,</span>
  <span m='402032'>and</span> <span m='402473'>0x5808</span> <span m='402914'>as</span>
  <span m='403355'>the</span> <span m='403797'>addresses</span> <span m='404238'>for</span>
  <span m='404679'>the</span> <span m='405120'>data</span> <span m='405561'>held</span>
  <span m='406002'>in</span> <span m='406444'>cache</span> <span m='406885'>lines</span>
  <span m='407326'>0,</span> <span m='407767'>1,</span> <span m='408208'>and</span>
  <span m='408650'>2.</span> </p><p><span m='411150'>Note</span> <span m='411458'>that</span>
  <span m='411767'>the</span> <span m='412076'>complete</span> <span m='412384'>address</span>
  <span m='412693'>of</span> <span m='413002'>the</span> <span m='413310'>cached</span>
  <span m='413619'>locations</span> <span m='413928'>is</span> <span m='414236'>formed</span>
  <span m='414545'>by</span> <span m='414854'>combining</span> <span m='415162'>the</span>
  <span m='415471'>tag</span> <span m='415780'>field</span> <span m='416089'>of</span>
  <span m='416435'>the</span> <span m='416781'>cache</span> <span m='417128'>line</span>
  <span m='417474'>with</span> <span m='417820'>the</span> <span m='418167'>index</span>
  <span m='418513'>of</span> <span m='418859'>the</span> <span m='419206'>cache</span>
  <span m='419552'>line.</span> </p><p><span m='419899'>We</span> <span m='420158'>of</span>
  <span m='420417'>course</span> <span m='420677'>need</span> <span m='420936'>to</span>
  <span m='421196'>be</span> <span m='421455'>able</span> <span m='421715'>to</span>
  <span m='421974'>recover</span> <span m='422233'>the</span> <span m='422493'>complete</span>
  <span m='422752'>address</span> <span m='423012'>from</span> <span m='423271'>the</span>
  <span m='423531'>information</span> <span m='423790'>held</span> <span m='424050'>in</span>
  <span m='424391'>the</span> <span m='424733'>cache</span> <span m='425075'>so</span>
  <span m='425417'>it</span> <span m='425759'>can</span> <span m='426101'>be</span>
  <span m='426443'>correctly</span> <span m='426785'>compared</span> <span m='427127'>against</span>
  <span m='427469'>address</span> <span m='427811'>requests</span> <span m='428153'>from</span>
  <span m='428495'>the</span> <span m='428837'>CPU.</span> </p>
type: course
uid: 5f4f60a17884722a5dab1a177b70df5b

---
None