---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: q30W7ApRqjI
  parent_uid: 9e13d2d0eb83a0ec08f66213de883474
  title: Video-YouTube-Stream
  type: Video
  uid: 7ed4dba59bc25ff16474b5e91f6c489b
- id: 3Play-3Play YouTube id-Stream
  media_location: q30W7ApRqjI
  parent_uid: 9e13d2d0eb83a0ec08f66213de883474
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: ae70f78c1226e131dc4cca108137b08a
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/q30W7ApRqjI/default.jpg
  parent_uid: 9e13d2d0eb83a0ec08f66213de883474
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 05e8ed551f2cca83697eaba556990807
- id: q30W7ApRqjI.srt
  parent_uid: 9e13d2d0eb83a0ec08f66213de883474
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v9/associative-caches-9-32-/q30W7ApRqjI.srt
  title: 3play caption file
  type: null
  uid: cd6949908d1d8ae15a2f24df81eecb5f
- id: q30W7ApRqjI.pdf
  parent_uid: 9e13d2d0eb83a0ec08f66213de883474
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v9/associative-caches-9-32-/q30W7ApRqjI.pdf
  title: 3play pdf file
  type: null
  uid: b446e9efb531001a10452f580bb90dbf
- id: Caption-3Play YouTube id-SRT
  parent_uid: 9e13d2d0eb83a0ec08f66213de883474
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 3f57f6c219710593b273a5e7a1d3e45f
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 9e13d2d0eb83a0ec08f66213de883474
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: db439d1eb2f83cc04d15ccdb09f36e99
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_14-02-09_300k.mp4
  parent_uid: 9e13d2d0eb83a0ec08f66213de883474
  title: Video-Internet Archive-MP4
  type: Video
  uid: 13cf4f2cfc66ca2a9215cd9457468c3a
inline_embed_id: 97653467associativecaches93267127728
layout: video
order_index: null
parent_uid: f9fddc34c321176b78633aac75474cd3
related_resources_text: ''
short_url: associative-caches-9-32-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v9/associative-caches-9-32-
template_type: Embed
title: Associative Caches (9:32)
transcript: "<p><span m='930'>A</span> <span m='1284'>fully-associative</span> <span\
  \ m='1638'>(FA)</span> <span m='1992'>cache</span> <span m='2346'>has</span> <span\
  \ m='2700'>a</span> <span m='3055'>tag</span> <span m='3409'>comparator</span> <span\
  \ m='3763'>for</span> <span m='4117'>each</span> <span m='4471'>cache</span> <span\
  \ m='4825'>line.</span> </p><p><span m='5180'>So</span> <span m='5446'>the</span>\
  \ <span m='5713'>tag</span> <span m='5980'>field</span> <span m='6246'>of</span>\
  \ <span m='6513'>*every*</span> <span m='6780'>cache</span> <span m='7046'>line</span>\
  \ <span m='7313'>in</span> <span m='7580'>a</span> <span m='7846'>FA</span> <span\
  \ m='8113'>cache</span> <span m='8380'>is</span> <span m='8646'>compared</span>\
  \ <span m='8913'>with</span> <span m='9180'>the</span> <span m='9446'>tag</span>\
  \ <span m='9713'>field</span> <span m='9980'>of</span> <span m='10670'>the</span>\
  \ <span m='11360'>incoming</span> <span m='12050'>address.</span> </p><p><span m='12740'>Since</span>\
  \ <span m='13066'>all</span> <span m='13392'>cache</span> <span m='13719'>lines</span>\
  \ <span m='14045'>are</span> <span m='14372'>searched,</span> <span m='14698'>a</span>\
  \ <span m='15025'>particular</span> <span m='15351'>memory</span> <span m='15678'>location</span>\
  \ <span m='16004'>can</span> <span m='16331'>be</span> <span m='16657'>held</span>\
  \ <span m='16984'>in</span> <span m='17310'>any</span> <span m='17637'>cache</span>\
  \ <span m='17963'>line,</span> <span m='18290'>which</span> <span m='18927'>eliminates</span>\
  \ <span m='19564'>the</span> <span m='20201'>problems</span> <span m='20838'>of</span>\
  \ <span m='21475'>address</span> <span m='22112'>conflicts</span> <span m='22749'>causing</span>\
  \ <span m='23386'>conflict</span> <span m='24023'>misses.</span> </p><p><span m='24660'>The</span>\
  \ <span m='25121'>cache</span> <span m='25582'>shown</span> <span m='26044'>here</span>\
  \ <span m='26505'>can</span> <span m='26966'>hold</span> <span m='27428'>4</span>\
  \ <span m='27889'>different</span> <span m='28350'>4-word</span> <span m='28812'>blocks,</span>\
  \ <span m='29273'>regardless</span> <span m='29734'>of</span> <span m='30196'>their</span>\
  \ <span m='30657'>address.</span> </p><p><span m='31119'>The</span> <span m='31397'>example</span>\
  \ <span m='31675'>from</span> <span m='31953'>the</span> <span m='32232'>end</span>\
  \ <span m='32510'>of</span> <span m='32788'>the</span> <span m='33067'>previous</span>\
  \ <span m='33345'>segment</span> <span m='33623'>required</span> <span m='33901'>a</span>\
  \ <span m='34180'>cache</span> <span m='34458'>that</span> <span m='34736'>could</span>\
  \ <span m='35015'>hold</span> <span m='35293'>two</span> <span m='35571'>3-word</span>\
  \ <span m='35850'>blocks,</span> <span m='36192'>one</span> <span m='36534'>for</span>\
  \ <span m='36876'>the</span> <span m='37218'>instructions</span> <span m='37560'>in</span>\
  \ <span m='37902'>the</span> <span m='38245'>loop,</span> <span m='38587'>and</span>\
  \ <span m='38929'>one</span> <span m='39271'>for</span> <span m='39613'>the</span>\
  \ <span m='39955'>data</span> <span m='40297'>words.</span> </p><p><span m='40640'>This</span>\
  \ <span m='41001'>FA</span> <span m='41363'>cache</span> <span m='41724'>would</span>\
  \ <span m='42086'>use</span> <span m='42447'>two</span> <span m='42809'>of</span>\
  \ <span m='43171'>its</span> <span m='43532'>cache</span> <span m='43894'>lines</span>\
  \ <span m='44255'>to</span> <span m='44617'>perform</span> <span m='44978'>that</span>\
  \ <span m='45340'>task</span> <span m='45702'>and</span> <span m='46063'>achieve</span>\
  \ <span m='46425'>a</span> <span m='46786'>100%</span> <span m='47148'>hit</span>\
  \ <span m='47510'>ratio</span> <span m='48019'>regardless</span> <span m='48528'>of</span>\
  \ <span m='49037'>the</span> <span m='49546'>addresses</span> <span m='50055'>of</span>\
  \ <span m='50564'>the</span> <span m='51073'>instruction</span> <span m='51582'>and</span>\
  \ <span m='52091'>data</span> <span m='52600'>blocks.</span> </p><p><span m='53110'>FA</span>\
  \ <span m='53627'>caches</span> <span m='54145'>are</span> <span m='54663'>very</span>\
  \ <span m='55180'>flexible</span> <span m='55698'>and</span> <span m='56216'>have</span>\
  \ <span m='56733'>high</span> <span m='57251'>hit</span> <span m='57769'>ratios</span>\
  \ <span m='58286'>for</span> <span m='58804'>most</span> <span m='59322'>applications.</span>\
  \ </p><p><span m='59840'>Their</span> <span m='60476'>only</span> <span m='61112'>downside</span>\
  \ <span m='61748'>is</span> <span m='62384'>cost.</span> </p><p><span m='63020'>The</span>\
  \ <span m='63332'>inclusion</span> <span m='63645'>of</span> <span m='63958'>a</span>\
  \ <span m='64270'>tag</span> <span m='64583'>comparator</span> <span m='64896'>for</span>\
  \ <span m='65208'>each</span> <span m='65521'>cache</span> <span m='65834'>line</span>\
  \ <span m='66146'>to</span> <span m='66459'>implement</span> <span m='66772'>the</span>\
  \ <span m='67084'>parallel</span> <span m='67397'>search</span> <span m='67710'>for</span>\
  \ <span m='68096'>a</span> <span m='68482'>tag</span> <span m='68868'>match</span>\
  \ <span m='69254'>adds</span> <span m='69640'>substantially</span> <span m='70026'>the</span>\
  \ <span m='70412'>amount</span> <span m='70798'>of</span> <span m='71184'>circuitry</span>\
  \ <span m='71570'>required</span> <span m='71956'>when</span> <span m='72342'>there</span>\
  \ <span m='72728'>are</span> <span m='73114'>many</span> <span m='73500'>cache</span>\
  \ <span m='74590'>lines.</span> </p><p><span m='75680'>Even</span> <span m='76214'>the</span>\
  \ <span m='76749'>use</span> <span m='77283'>of</span> <span m='77818'>hybrid</span>\
  \ <span m='78352'>storage/comparison</span> <span m='78887'>circuitry,</span> <span\
  \ m='79421'>called</span> <span m='79956'>a</span> <span m='80490'>content-addressable</span>\
  \ <span m='81025'>memory,</span> <span m='81560'>doesn't</span> <span m='81990'>make</span>\
  \ <span m='82421'>a</span> <span m='82852'>big</span> <span m='83283'>dent</span>\
  \ <span m='83713'>in</span> <span m='84144'>the</span> <span m='84575'>overall</span>\
  \ <span m='85006'>cost</span> <span m='85436'>of</span> <span m='85867'>a</span>\
  \ <span m='86298'>FA</span> <span m='86729'>cache.</span> </p><p><span m='87160'>DM</span>\
  \ <span m='87678'>caches</span> <span m='88197'>searched</span> <span m='88716'>only</span>\
  \ <span m='89235'>a</span> <span m='89753'>single</span> <span m='90272'>cache</span>\
  \ <span m='90791'>line.</span> </p><p><span m='91310'>FA</span> <span m='91886'>caches</span>\
  \ <span m='92463'>search</span> <span m='93040'>all</span> <span m='93616'>cache</span>\
  \ <span m='94193'>lines.</span> </p><p><span m='94770'>Is</span> <span m='95048'>there</span>\
  \ <span m='95327'>a</span> <span m='95606'>happy</span> <span m='95884'>middle</span>\
  \ <span m='96163'>ground</span> <span m='96442'>where</span> <span m='96720'>some</span>\
  \ <span m='96999'>small</span> <span m='97278'>number</span> <span m='97556'>of</span>\
  \ <span m='97835'>cache</span> <span m='98114'>lines</span> <span m='98392'>are</span>\
  \ <span m='98671'>searched</span> <span m='98950'>in</span> <span m='99229'>parallel?</span>\
  \ </p><p><span m='100229'>Yes!</span> </p><p><span m='101229'>If</span> <span m='101538'>you</span>\
  \ <span m='101847'>look</span> <span m='102157'>closely</span> <span m='102466'>at</span>\
  \ <span m='102776'>the</span> <span m='103085'>diagram</span> <span m='103395'>of</span>\
  \ <span m='103704'>the</span> <span m='104014'>FA</span> <span m='104323'>cache</span>\
  \ <span m='104632'>shown</span> <span m='104942'>here,</span> <span m='105251'>you'll</span>\
  \ <span m='105561'>see</span> <span m='105870'>it</span> <span m='106180'>looks</span>\
  \ <span m='106489'>like</span> <span m='106799'>four</span> <span m='107569'>1-line</span>\
  \ <span m='108339'>DM</span> <span m='109109'>caches</span> <span m='109879'>operating</span>\
  \ <span m='110649'>in</span> <span m='111419'>parallel.</span> </p><p><span m='112189'>What</span>\
  \ <span m='112602'>would</span> <span m='113016'>happen</span> <span m='113430'>if</span>\
  \ <span m='113844'>we</span> <span m='114258'>designed</span> <span m='114671'>a</span>\
  \ <span m='115085'>cache</span> <span m='115499'>with</span> <span m='115913'>four</span>\
  \ <span m='116327'>multi-line</span> <span m='116740'>DM</span> <span m='117154'>caches</span>\
  \ <span m='117568'>operating</span> <span m='117982'>in</span> <span m='118396'>parallel?</span>\
  \ </p><p><span m='118810'>The</span> <span m='119208'>result</span> <span m='119606'>would</span>\
  \ <span m='120005'>be</span> <span m='120403'>what</span> <span m='120801'>we</span>\
  \ <span m='121200'>call</span> <span m='121598'>an</span> <span m='121996'>4-way</span>\
  \ <span m='122395'>set-associative</span> <span m='122793'>(SA)</span> <span m='123191'>cache.</span>\
  \ </p><p><span m='123590'>An</span> <span m='124008'>N-way</span> <span m='124427'>SA</span>\
  \ <span m='124845'>cache</span> <span m='125264'>is</span> <span m='125683'>really</span>\
  \ <span m='126101'>just</span> <span m='126520'>N</span> <span m='126939'>DM</span>\
  \ <span m='127357'>caches</span> <span m='127776'>(let's</span> <span m='128194'>call</span>\
  \ <span m='128613'>them</span> <span m='129032'>sub-caches)</span> <span m='129450'>operating</span>\
  \ <span m='129869'>in</span> <span m='130288'>parallel.</span> </p><p><span m='131939'>Each</span>\
  \ <span m='132248'>of</span> <span m='132557'>the</span> <span m='132867'>N</span>\
  \ <span m='133176'>sub-caches</span> <span m='133485'>compares</span> <span m='133795'>the</span>\
  \ <span m='134104'>tag</span> <span m='134414'>field</span> <span m='134723'>of</span>\
  \ <span m='135032'>the</span> <span m='135342'>incoming</span> <span m='135651'>address</span>\
  \ <span m='135960'>with</span> <span m='136270'>the</span> <span m='136579'>tag</span>\
  \ <span m='136889'>field</span> <span m='137299'>of</span> <span m='137709'>the</span>\
  \ <span m='138119'>cache</span> <span m='138529'>line</span> <span m='138939'>selected</span>\
  \ <span m='139349'>by</span> <span m='139759'>the</span> <span m='140169'>index</span>\
  \ <span m='140579'>bits</span> <span m='140989'>of</span> <span m='141399'>the</span>\
  \ <span m='141809'>incoming</span> <span m='142219'>address.</span> </p><p><span\
  \ m='142629'>The</span> <span m='143012'>N</span> <span m='143396'>cache</span>\
  \ <span m='143780'>lines</span> <span m='144164'>searched</span> <span m='144547'>on</span>\
  \ <span m='144931'>a</span> <span m='145315'>particular</span> <span m='145699'>request</span>\
  \ <span m='146082'>form</span> <span m='146466'>a</span> <span m='146850'>search</span>\
  \ <span m='147234'>\"set\"</span> <span m='147617'>and</span> <span m='148001'>the</span>\
  \ <span m='148385'>desired</span> <span m='148769'>location</span> <span m='149205'>might</span>\
  \ <span m='149641'>be</span> <span m='150077'>held</span> <span m='150513'>in</span>\
  \ <span m='150949'>any</span> <span m='151385'>member</span> <span m='151821'>of</span>\
  \ <span m='152257'>the</span> <span m='152693'>set.</span> </p><p><span m='153129'>The</span>\
  \ <span m='153530'>4-way</span> <span m='153931'>SA</span> <span m='154332'>cache</span>\
  \ <span m='154733'>shown</span> <span m='155135'>here</span> <span m='155536'>has</span>\
  \ <span m='155937'>8</span> <span m='156338'>cache</span> <span m='156740'>lines</span>\
  \ <span m='157141'>in</span> <span m='157542'>each</span> <span m='157943'>sub-cache,</span>\
  \ <span m='158345'>so</span> <span m='158746'>each</span> <span m='159147'>set</span>\
  \ <span m='159548'>contains</span> <span m='159950'>4</span> <span m='160277'>cache</span>\
  \ <span m='160605'>lines</span> <span m='160933'>(one</span> <span m='161260'>from</span>\
  \ <span m='161588'>each</span> <span m='161916'>sub-cache)</span> <span m='162244'>and</span>\
  \ <span m='162571'>there</span> <span m='162899'>are</span> <span m='163227'>a</span>\
  \ <span m='163554'>total</span> <span m='163882'>of</span> <span m='164210'>8</span>\
  \ <span m='164538'>sets</span> <span m='164865'>(one</span> <span m='165193'>for</span>\
  \ <span m='165521'>each</span> <span m='165849'>line</span> <span m='166896'>of</span>\
  \ <span m='167944'>the</span> <span m='168992'>sub-caches).</span> </p><p><span\
  \ m='170040'>An</span> <span m='170365'>N-way</span> <span m='170690'>SA</span>\
  \ <span m='171015'>cache</span> <span m='171340'>can</span> <span m='171666'>accommodate</span>\
  \ <span m='171991'>up</span> <span m='172316'>to</span> <span m='172641'>N</span>\
  \ <span m='172967'>blocks</span> <span m='173292'>whose</span> <span m='173617'>addresses</span>\
  \ <span m='173942'>map</span> <span m='174268'>to</span> <span m='174593'>the</span>\
  \ <span m='174918'>same</span> <span m='175243'>cache</span> <span m='175569'>index.</span>\
  \ </p><p><span m='177709'>So</span> <span m='178045'>access</span> <span m='178381'>to</span>\
  \ <span m='178717'>up</span> <span m='179054'>to</span> <span m='179390'>N</span>\
  \ <span m='179726'>blocks</span> <span m='180062'>with</span> <span m='180399'>conflicting</span>\
  \ <span m='180735'>addresses</span> <span m='181071'>can</span> <span m='181407'>still</span>\
  \ <span m='181744'>be</span> <span m='182080'>accommodated</span> <span m='182416'>in</span>\
  \ <span m='182752'>this</span> <span m='183089'>cache</span> <span m='183979'>without</span>\
  \ <span m='184869'>misses.</span> </p><p><span m='185760'>This</span> <span m='186110'>a</span>\
  \ <span m='186461'>big</span> <span m='186811'>improvement</span> <span m='187162'>over</span>\
  \ <span m='187513'>a</span> <span m='187863'>DM</span> <span m='188214'>cache</span>\
  \ <span m='188565'>where</span> <span m='188915'>an</span> <span m='189266'>address</span>\
  \ <span m='189616'>conflict</span> <span m='189967'>will</span> <span m='190318'>cause</span>\
  \ <span m='190668'>the</span> <span m='191019'>current</span> <span m='191370'>resident</span>\
  \ <span m='191767'>of</span> <span m='192164'>a</span> <span m='192561'>cache</span>\
  \ <span m='192958'>line</span> <span m='193355'>to</span> <span m='193752'>be</span>\
  \ <span m='194150'>evicted</span> <span m='194547'>in</span> <span m='194944'>favor</span>\
  \ <span m='195341'>of</span> <span m='195738'>the</span> <span m='196135'>new</span>\
  \ <span m='196532'>request.</span> </p><p><span m='196930'>And</span> <span m='197247'>an</span>\
  \ <span m='197564'>N-way</span> <span m='197881'>SA</span> <span m='198198'>cache</span>\
  \ <span m='198515'>can</span> <span m='198833'>have</span> <span m='199150'>a</span>\
  \ <span m='199467'>very</span> <span m='199784'>large</span> <span m='200101'>number</span>\
  \ <span m='200418'>of</span> <span m='200736'>cache</span> <span m='201053'>lines</span>\
  \ <span m='201370'>but</span> <span m='201687'>still</span> <span m='202004'>only</span>\
  \ <span m='202321'>have</span> <span m='202639'>to</span> <span m='203126'>pay</span>\
  \ <span m='203614'>the</span> <span m='204101'>cost</span> <span m='204589'>of</span>\
  \ <span m='205077'>N</span> <span m='205564'>tag</span> <span m='206052'>comparators.</span>\
  \ </p><p><span m='206540'>This</span> <span m='206849'>is</span> <span m='207159'>a</span>\
  \ <span m='207469'>big</span> <span m='207779'>improvement</span> <span m='208089'>over</span>\
  \ <span m='208399'>a</span> <span m='208709'>FA</span> <span m='209019'>cache</span>\
  \ <span m='209329'>where</span> <span m='209639'>a</span> <span m='209949'>large</span>\
  \ <span m='210259'>number</span> <span m='210569'>of</span> <span m='210879'>cache</span>\
  \ <span m='211189'>lines</span> <span m='211499'>would</span> <span m='211809'>require</span>\
  \ <span m='212399'>a</span> <span m='212989'>large</span> <span m='213579'>number</span>\
  \ <span m='214169'>of</span> <span m='214759'>comparators.</span> </p><p><span m='215349'>So</span>\
  \ <span m='215828'>N-way</span> <span m='216307'>SA</span> <span m='216787'>caches</span>\
  \ <span m='217266'>are</span> <span m='217745'>a</span> <span m='218225'>good</span>\
  \ <span m='218704'>compromise</span> <span m='219184'>between</span> <span m='219663'>a</span>\
  \ <span m='220142'>conflict-prone</span> <span m='220622'>DM</span> <span m='221101'>cache</span>\
  \ <span m='221580'>and</span> <span m='222060'>the</span> <span m='222539'>flexible</span>\
  \ <span m='223019'>but</span> <span m='223833'>very</span> <span m='224647'>expensive</span>\
  \ <span m='225461'>FA</span> <span m='226275'>cache.</span> </p><p><span m='227089'>Here's</span>\
  \ <span m='227522'>a</span> <span m='227956'>slightly</span> <span m='228389'>more</span>\
  \ <span m='228823'>detailed</span> <span m='229256'>diagram,</span> <span m='229690'>in</span>\
  \ <span m='230124'>this</span> <span m='230557'>case</span> <span m='230991'>of</span>\
  \ <span m='231424'>a</span> <span m='231858'>3-way</span> <span m='232291'>8-set</span>\
  \ <span m='232725'>cache.</span> </p><p><span m='233159'>Note</span> <span m='233389'>that</span>\
  \ <span m='233619'>there's</span> <span m='233849'>no</span> <span m='234079'>constraint</span>\
  \ <span m='234309'>that</span> <span m='234539'>the</span> <span m='234769'>number</span>\
  \ <span m='234999'>of</span> <span m='235229'>ways</span> <span m='235459'>be</span>\
  \ <span m='235689'>a</span> <span m='235919'>power</span> <span m='236149'>of</span>\
  \ <span m='236379'>two</span> <span m='236609'>since</span> <span m='236839'>we</span>\
  \ <span m='237069'>aren't</span> <span m='237299'>using</span> <span m='237737'>any</span>\
  \ <span m='238176'>address</span> <span m='238615'>bits</span> <span m='239054'>to</span>\
  \ <span m='239493'>select</span> <span m='239932'>a</span> <span m='240371'>particular</span>\
  \ <span m='240810'>way.</span> </p><p><span m='241249'>This</span> <span m='241644'>means</span>\
  \ <span m='242039'>the</span> <span m='242434'>cache</span> <span m='242829'>designer</span>\
  \ <span m='243224'>can</span> <span m='243619'>fine</span> <span m='244014'>tune</span>\
  \ <span m='244409'>the</span> <span m='244804'>cache</span> <span m='245199'>capacity</span>\
  \ <span m='245594'>to</span> <span m='245989'>fit</span> <span m='246384'>her</span>\
  \ <span m='246779'>space</span> <span m='247174'>budget.</span> </p><p><span m='247569'>Just</span>\
  \ <span m='247865'>to</span> <span m='248161'>review</span> <span m='248457'>the</span>\
  \ <span m='248754'>terminology:</span> <span m='249050'>the</span> <span m='249346'>N</span>\
  \ <span m='249642'>cache</span> <span m='249939'>lines</span> <span m='250235'>that</span>\
  \ <span m='250531'>will</span> <span m='250827'>be</span> <span m='251124'>searched</span>\
  \ <span m='251420'>for</span> <span m='251716'>a</span> <span m='252012'>particular</span>\
  \ <span m='252309'>cache</span> <span m='252667'>index</span> <span m='253025'>are</span>\
  \ <span m='253384'>called</span> <span m='253742'>a</span> <span m='254100'>set.</span>\
  \ </p><p><span m='254459'>And</span> <span m='255055'>each</span> <span m='255652'>of</span>\
  \ <span m='256249'>N</span> <span m='256845'>sub-caches</span> <span m='257442'>is</span>\
  \ <span m='258039'>called</span> <span m='258635'>a</span> <span m='259232'>way.</span>\
  \ </p><p><span m='259829'>The</span> <span m='260163'>hit</span> <span m='260497'>logic</span>\
  \ <span m='260831'>in</span> <span m='261165'>each</span> <span m='261499'>\"way\"\
  </span> <span m='261833'>operates</span> <span m='262167'>in</span> <span m='262501'>parallel</span>\
  \ <span m='262835'>with</span> <span m='263169'>the</span> <span m='263503'>logic</span>\
  \ <span m='263837'>in</span> <span m='264171'>other</span> <span m='264505'>ways.</span>\
  \ </p><p><span m='264840'>Is</span> <span m='265194'>it</span> <span m='265549'>possible</span>\
  \ <span m='265904'>for</span> <span m='266258'>a</span> <span m='266613'>particular</span>\
  \ <span m='266968'>address</span> <span m='267322'>to</span> <span m='267677'>be</span>\
  \ <span m='268032'>matched</span> <span m='268386'>by</span> <span m='268741'>more</span>\
  \ <span m='269096'>than</span> <span m='269450'>one</span> <span m='269805'>way?</span>\
  \ </p><p><span m='270160'>That</span> <span m='270521'>possibility</span> <span\
  \ m='270882'>isn't</span> <span m='271243'>ruled</span> <span m='271604'>out</span>\
  \ <span m='271965'>by</span> <span m='272327'>the</span> <span m='272688'>hardware,</span>\
  \ <span m='273049'>but</span> <span m='273410'>the</span> <span m='273771'>SA</span>\
  \ <span m='274132'>cache</span> <span m='274494'>is</span> <span m='274855'>managed</span>\
  \ <span m='275216'>so</span> <span m='275577'>that</span> <span m='275938'>doesn't</span>\
  \ <span m='276300'>happen.</span> </p><p><span m='277530'>Assuming</span> <span\
  \ m='277846'>we</span> <span m='278162'>write</span> <span m='278478'>the</span>\
  \ <span m='278795'>data</span> <span m='279111'>fetched</span> <span m='279427'>from</span>\
  \ <span m='279743'>DRAM</span> <span m='280060'>during</span> <span m='280376'>a</span>\
  \ <span m='280692'>cache</span> <span m='281008'>miss</span> <span m='281325'>into</span>\
  \ <span m='281641'>a</span> <span m='281957'>single</span> <span m='282273'>sub-cache</span>\
  \ <span m='282590'>-</span> <span m='282886'>we'll</span> <span m='283182'>talk</span>\
  \ <span m='283478'>about</span> <span m='283774'>how</span> <span m='284070'>to</span>\
  \ <span m='284366'>choose</span> <span m='284662'>that</span> <span m='284958'>way</span>\
  \ <span m='285254'>in</span> <span m='285550'>a</span> <span m='285846'>minute</span>\
  \ <span m='286142'>-</span> <span m='286439'>there's</span> <span m='286886'>no</span>\
  \ <span m='287334'>possibility</span> <span m='287782'>that</span> <span m='288230'>more</span>\
  \ <span m='288678'>than</span> <span m='289126'>one</span> <span m='289574'>sub-cache</span>\
  \ <span m='290022'>will</span> <span m='290470'>ever</span> <span m='290918'>match</span>\
  \ <span m='291366'>an</span> <span m='291814'>incoming</span> <span m='292262'>address.</span>\
  \ </p><p><span m='292710'>How</span> <span m='292991'>many</span> <span m='293272'>ways</span>\
  \ <span m='293554'>to</span> <span m='293835'>do</span> <span m='294117'>we</span>\
  \ <span m='294398'>need?</span> </p><p><span m='294680'>We'd</span> <span m='295061'>like</span>\
  \ <span m='295442'>enough</span> <span m='295823'>ways</span> <span m='296205'>to</span>\
  \ <span m='296586'>avoid</span> <span m='296967'>the</span> <span m='297348'>cache</span>\
  \ <span m='297730'>line</span> <span m='298111'>conflicts</span> <span m='298492'>we</span>\
  \ <span m='298873'>experienced</span> <span m='299255'>with</span> <span m='299636'>the</span>\
  \ <span m='300017'>DM</span> <span m='300398'>cache.</span> </p><p><span m='300780'>Looking</span>\
  \ <span m='301089'>at</span> <span m='301398'>the</span> <span m='301708'>graph</span>\
  \ <span m='302017'>we</span> <span m='302326'>saw</span> <span m='302636'>earlier</span>\
  \ <span m='302945'>of</span> <span m='303255'>memory</span> <span m='303564'>accesses</span>\
  \ <span m='303873'>vs.</span> <span m='304183'>time,</span> <span m='304492'>we</span>\
  \ <span m='304802'>see</span> <span m='305111'>that</span> <span m='305420'>in</span>\
  \ <span m='305730'>any</span> <span m='306039'>time</span> <span m='306349'>interval</span>\
  \ <span m='306733'>there</span> <span m='307117'>are</span> <span m='307501'>only</span>\
  \ <span m='307885'>so</span> <span m='308269'>many</span> <span m='308653'>potential</span>\
  \ <span m='309037'>address</span> <span m='309421'>conflicts</span> <span m='309805'>that</span>\
  \ <span m='310189'>we</span> <span m='310573'>need</span> <span m='310957'>to</span>\
  \ <span m='311341'>worry</span> <span m='311725'>about.</span> </p><p><span m='312110'>The</span>\
  \ <span m='312443'>mapping</span> <span m='312777'>from</span> <span m='313110'>addresses</span>\
  \ <span m='313444'>to</span> <span m='313777'>cache</span> <span m='314111'>lines</span>\
  \ <span m='314445'>is</span> <span m='314778'>designed</span> <span m='315112'>to</span>\
  \ <span m='315445'>avoid</span> <span m='315779'>conflicts</span> <span m='316112'>between</span>\
  \ <span m='316446'>neighboring</span> <span m='316780'>locations.</span> </p><p><span\
  \ m='318460'>So</span> <span m='318878'>we</span> <span m='319296'>only</span> <span\
  \ m='319714'>need</span> <span m='320132'>to</span> <span m='320550'>worry</span>\
  \ <span m='320968'>about</span> <span m='321386'>conflicts</span> <span m='321805'>between</span>\
  \ <span m='322223'>the</span> <span m='322641'>different</span> <span m='323059'>regions:</span>\
  \ <span m='323477'>code,</span> <span m='323895'>stack</span> <span m='324313'>and</span>\
  \ <span m='324731'>data.</span> </p><p><span m='325150'>In</span> <span m='325432'>the</span>\
  \ <span m='325714'>examples</span> <span m='325996'>shown</span> <span m='326279'>here</span>\
  \ <span m='326561'>there</span> <span m='326843'>are</span> <span m='327126'>three</span>\
  \ <span m='327408'>such</span> <span m='327690'>regions,</span> <span m='327972'>maybe</span>\
  \ <span m='328255'>4</span> <span m='328537'>if</span> <span m='328819'>you</span>\
  \ <span m='329102'>need</span> <span m='329384'>two</span> <span m='329666'>data</span>\
  \ <span m='329949'>regions</span> <span m='330301'>to</span> <span m='330653'>support</span>\
  \ <span m='331005'>copying</span> <span m='331357'>from</span> <span m='331709'>one</span>\
  \ <span m='332061'>data</span> <span m='332413'>region</span> <span m='332765'>to</span>\
  \ <span m='333117'>another.</span> </p><p><span m='333470'>If</span> <span m='333753'>the</span>\
  \ <span m='334037'>time</span> <span m='334321'>interval</span> <span m='334605'>is</span>\
  \ <span m='334889'>particularly</span> <span m='335173'>large,</span> <span m='335457'>we</span>\
  \ <span m='335741'>might</span> <span m='336025'>need</span> <span m='336309'>double</span>\
  \ <span m='336593'>that</span> <span m='336877'>number</span> <span m='337161'>to</span>\
  \ <span m='337445'>avoid</span> <span m='337729'>conflicts</span> <span m='338111'>between</span>\
  \ <span m='338493'>accesses</span> <span m='338875'>early</span> <span m='339257'>in</span>\
  \ <span m='339639'>the</span> <span m='340021'>time</span> <span m='340403'>interval</span>\
  \ <span m='340785'>and</span> <span m='341167'>accesses</span> <span m='341549'>late</span>\
  \ <span m='341931'>in</span> <span m='342313'>the</span> <span m='342695'>time</span>\
  \ <span m='343077'>interval.</span> </p><p><span m='343460'>The</span> <span m='343766'>point</span>\
  \ <span m='344072'>is</span> <span m='344378'>that</span> <span m='344684'>a</span>\
  \ <span m='344990'>small</span> <span m='345296'>number</span> <span m='345602'>of</span>\
  \ <span m='345908'>ways</span> <span m='346214'>should</span> <span m='346520'>be</span>\
  \ <span m='346826'>sufficient</span> <span m='347132'>to</span> <span m='347438'>avoid</span>\
  \ <span m='347744'>most</span> <span m='348050'>cache</span> <span m='348356'>line</span>\
  \ <span m='348662'>conflicts</span> <span m='348969'>in</span> <span m='349809'>the</span>\
  \ <span m='350649'>cache.</span> </p><p><span m='351490'>As</span> <span m='351777'>with</span>\
  \ <span m='352065'>block</span> <span m='352352'>size,</span> <span m='352640'>it's</span>\
  \ <span m='352928'>possible</span> <span m='353215'>to</span> <span m='353503'>have</span>\
  \ <span m='353791'>too</span> <span m='354078'>much</span> <span m='354366'>of</span>\
  \ <span m='354654'>a</span> <span m='354941'>good</span> <span m='355229'>thing:</span>\
  \ <span m='355517'>there's</span> <span m='355804'>an</span> <span m='356092'>optimum</span>\
  \ <span m='356380'>number</span> <span m='357049'>of</span> <span m='357719'>ways</span>\
  \ <span m='358389'>that</span> <span m='359059'>minimizes</span> <span m='359729'>the</span>\
  \ <span m='360399'>AMAT.</span> </p><p><span m='361069'>Beyond</span> <span m='361332'>that</span>\
  \ <span m='361595'>point,</span> <span m='361859'>the</span> <span m='362122'>additional</span>\
  \ <span m='362386'>circuity</span> <span m='362649'>needed</span> <span m='362912'>to</span>\
  \ <span m='363176'>combine</span> <span m='363439'>the</span> <span m='363703'>hit</span>\
  \ <span m='363966'>signals</span> <span m='364229'>from</span> <span m='364493'>a</span>\
  \ <span m='364756'>large</span> <span m='365020'>number</span> <span m='365406'>of</span>\
  \ <span m='365793'>ways</span> <span m='366179'>will</span> <span m='366566'>start</span>\
  \ <span m='366953'>have</span> <span m='367339'>a</span> <span m='367726'>significant</span>\
  \ <span m='368112'>propagation</span> <span m='368499'>delay</span> <span m='368886'>of</span>\
  \ <span m='369272'>its</span> <span m='369659'>own,</span> <span m='370045'>adding</span>\
  \ <span m='370432'>directly</span> <span m='370819'>to</span> <span m='371342'>the</span>\
  \ <span m='371866'>cache</span> <span m='372390'>hit</span> <span m='372914'>time</span>\
  \ <span m='373437'>and</span> <span m='373961'>the</span> <span m='374485'>AMAT.</span>\
  \ </p><p><span m='375009'>More</span> <span m='375240'>to</span> <span m='375471'>the</span>\
  \ <span m='375702'>point,</span> <span m='375933'>the</span> <span m='376164'>chart</span>\
  \ <span m='376396'>on</span> <span m='376627'>the</span> <span m='376858'>left</span>\
  \ <span m='377089'>shows</span> <span m='377320'>that</span> <span m='377551'>there's</span>\
  \ <span m='377783'>little</span> <span m='378014'>additional</span> <span m='378245'>impact</span>\
  \ <span m='378476'>on</span> <span m='378707'>the</span> <span m='378939'>miss</span>\
  \ <span m='379414'>ratio</span> <span m='379890'>beyond</span> <span m='380366'>4</span>\
  \ <span m='380842'>to</span> <span m='381318'>8</span> <span m='381794'>ways.</span>\
  \ </p><p><span m='382270'>For</span> <span m='382620'>most</span> <span m='382971'>programs,</span>\
  \ <span m='383322'>an</span> <span m='383672'>8-way</span> <span m='384023'>set-associative</span>\
  \ <span m='384374'>cache</span> <span m='384724'>with</span> <span m='385075'>a</span>\
  \ <span m='385426'>large</span> <span m='385776'>number</span> <span m='386127'>of</span>\
  \ <span m='386478'>sets</span> <span m='386828'>will</span> <span m='387179'>perform</span>\
  \ <span m='387530'>on</span> <span m='388142'>a</span> <span m='388755'>par</span>\
  \ <span m='389367'>with</span> <span m='389980'>the</span> <span m='390592'>much</span>\
  \ <span m='391205'>more-expensive</span> <span m='391817'>FA</span> <span m='392430'>cache</span>\
  \ <span m='393042'>of</span> <span m='393655'>equivalent</span> <span m='394267'>capacity.</span>\
  \ </p><p><span m='394880'>There's</span> <span m='395361'>one</span> <span m='395843'>final</span>\
  \ <span m='396325'>issue</span> <span m='396807'>to</span> <span m='397289'>resolve</span>\
  \ <span m='397770'>with</span> <span m='398252'>SA</span> <span m='398734'>and</span>\
  \ <span m='399216'>FA</span> <span m='399698'>caches.</span> </p><p><span m='400180'>When</span>\
  \ <span m='400437'>there's</span> <span m='400694'>a</span> <span m='400951'>cache</span>\
  \ <span m='401208'>miss,</span> <span m='401465'>which</span> <span m='401722'>cache</span>\
  \ <span m='401979'>line</span> <span m='402236'>should</span> <span m='402493'>be</span>\
  \ <span m='402750'>chosen</span> <span m='403007'>to</span> <span m='403264'>hold</span>\
  \ <span m='403521'>the</span> <span m='403778'>data</span> <span m='404035'>that</span>\
  \ <span m='404292'>will</span> <span m='404550'>be</span> <span m='405208'>fetched</span>\
  \ <span m='405866'>from</span> <span m='406524'>main</span> <span m='407182'>memory?</span>\
  \ </p><p><span m='407840'>That's</span> <span m='408133'>not</span> <span m='408426'>an</span>\
  \ <span m='408720'>issue</span> <span m='409013'>with</span> <span m='409306'>DM</span>\
  \ <span m='409600'>caches,</span> <span m='409893'>since</span> <span m='410186'>each</span>\
  \ <span m='410480'>data</span> <span m='410773'>block</span> <span m='411066'>can</span>\
  \ <span m='411360'>only</span> <span m='411653'>be</span> <span m='411946'>held</span>\
  \ <span m='412240'>in</span> <span m='412533'>one</span> <span m='412826'>particular</span>\
  \ <span m='413120'>cache</span> <span m='413685'>line,</span> <span m='414250'>determined</span>\
  \ <span m='414815'>by</span> <span m='415380'>its</span> <span m='415945'>address.</span>\
  \ </p><p><span m='416510'>But</span> <span m='416833'>in</span> <span m='417157'>N-way</span>\
  \ <span m='417481'>SA</span> <span m='417805'>caches,</span> <span m='418129'>there</span>\
  \ <span m='418453'>are</span> <span m='418777'>N</span> <span m='419101'>possible</span>\
  \ <span m='419425'>cache</span> <span m='419748'>lines</span> <span m='420072'>to</span>\
  \ <span m='420396'>choose</span> <span m='420720'>from,</span> <span m='421044'>one</span>\
  \ <span m='421368'>in</span> <span m='421692'>each</span> <span m='422016'>of</span>\
  \ <span m='422340'>the</span> <span m='423010'>ways.</span> </p><p><span m='423680'>And</span>\
  \ <span m='424036'>in</span> <span m='424392'>a</span> <span m='424748'>FA</span>\
  \ <span m='425104'>cache,</span> <span m='425460'>any</span> <span m='425816'>of</span>\
  \ <span m='426173'>the</span> <span m='426529'>cache</span> <span m='426885'>lines</span>\
  \ <span m='427241'>can</span> <span m='427597'>be</span> <span m='427953'>chosen.</span>\
  \ </p><p><span m='428310'>So,</span> <span m='428762'>how</span> <span m='429215'>to</span>\
  \ <span m='429667'>choose?</span> </p><p><span m='430120'>Our</span> <span m='430421'>goal</span>\
  \ <span m='430722'>is</span> <span m='431023'>to</span> <span m='431324'>choose</span>\
  \ <span m='431625'>to</span> <span m='431927'>replace</span> <span m='432228'>the</span>\
  \ <span m='432529'>contents</span> <span m='432830'>of</span> <span m='433131'>the</span>\
  \ <span m='433432'>cache</span> <span m='433734'>line</span> <span m='434035'>which</span>\
  \ <span m='434336'>will</span> <span m='434637'>minimize</span> <span m='434938'>the</span>\
  \ <span m='435240'>impact</span> <span m='435701'>on</span> <span m='436162'>the</span>\
  \ <span m='436623'>hit</span> <span m='437085'>ratio</span> <span m='437546'>in</span>\
  \ <span m='438007'>the</span> <span m='438468'>future.</span> </p><p><span m='438930'>The</span>\
  \ <span m='439254'>optimal</span> <span m='439578'>choice</span> <span m='439903'>is</span>\
  \ <span m='440227'>to</span> <span m='440551'>replace</span> <span m='440876'>the</span>\
  \ <span m='441200'>block</span> <span m='441525'>that</span> <span m='441849'>is</span>\
  \ <span m='442173'>accessed</span> <span m='442498'>furthest</span> <span m='442822'>in</span>\
  \ <span m='443146'>the</span> <span m='443471'>future</span> <span m='443795'>(or</span>\
  \ <span m='444120'>perhaps</span> <span m='444512'>is</span> <span m='444904'>never</span>\
  \ <span m='445296'>accessed</span> <span m='445688'>again).</span> </p><p><span\
  \ m='446080'>But</span> <span m='446693'>that</span> <span m='447306'>requires</span>\
  \ <span m='447919'>knowing</span> <span m='448532'>the</span> <span m='449145'>future\u2026\
  </span> <span m='449759'>Here's</span> <span m='450134'>an</span> <span m='450509'>idea:</span>\
  \ <span m='450884'>let's</span> <span m='451259'>predict</span> <span m='451634'>future</span>\
  \ <span m='452009'>accesses</span> <span m='452384'>by</span> <span m='452759'>looking</span>\
  \ <span m='453134'>a</span> <span m='453509'>recent</span> <span m='453884'>accesses</span>\
  \ <span m='454259'>and</span> <span m='454634'>applying</span> <span m='455009'>the</span>\
  \ <span m='455414'>principle</span> <span m='455819'>of</span> <span m='456224'>locality.</span>\
  \ </p><p><span m='456629'>d7.36</span> <span m='456922'>If</span> <span m='457216'>a</span>\
  \ <span m='457510'>block</span> <span m='457804'>has</span> <span m='458098'>not</span>\
  \ <span m='458392'>been</span> <span m='458686'>recently</span> <span m='458980'>accessed,</span>\
  \ <span m='459274'>it's</span> <span m='459567'>less</span> <span m='459861'>likely</span>\
  \ <span m='460155'>to</span> <span m='460449'>be</span> <span m='460743'>accessed</span>\
  \ <span m='461037'>in</span> <span m='461331'>the</span> <span m='461625'>near</span>\
  \ <span m='461919'>future.</span> </p><p><span m='464039'>That</span> <span m='464589'>suggests</span>\
  \ <span m='465140'>the</span> <span m='465691'>least-recently-used</span> <span\
  \ m='466242'>replacement</span> <span m='466793'>strategy,</span> <span m='467344'>usually</span>\
  \ <span m='467895'>referred</span> <span m='468446'>to</span> <span m='468997'>as</span>\
  \ <span m='469548'>LRU:</span> <span m='470099'>replace</span> <span m='470650'>the</span>\
  \ <span m='471032'>block</span> <span m='471414'>that</span> <span m='471796'>was</span>\
  \ <span m='472178'>accessed</span> <span m='472561'>furthest</span> <span m='472943'>in</span>\
  \ <span m='473325'>the</span> <span m='473707'>past.</span> </p><p><span m='474090'>LRU</span>\
  \ <span m='474458'>works</span> <span m='474826'>well</span> <span m='475195'>in</span>\
  \ <span m='475563'>practice,</span> <span m='475931'>but</span> <span m='476300'>requires</span>\
  \ <span m='476668'>us</span> <span m='477036'>to</span> <span m='477405'>keep</span>\
  \ <span m='477773'>a</span> <span m='478141'>list</span> <span m='478510'>ordered</span>\
  \ <span m='478878'>by</span> <span m='479246'>last</span> <span m='479615'>use</span>\
  \ <span m='479983'>for</span> <span m='480351'>each</span> <span m='480720'>set</span>\
  \ <span m='481149'>of</span> <span m='481578'>cache</span> <span m='482007'>lines,</span>\
  \ <span m='482436'>which</span> <span m='482866'>would</span> <span m='483295'>need</span>\
  \ <span m='483724'>to</span> <span m='484153'>be</span> <span m='484582'>updated</span>\
  \ <span m='485012'>on</span> <span m='485441'>each</span> <span m='485870'>cache</span>\
  \ <span m='486299'>access.</span> </p><p><span m='486729'>When</span> <span m='486979'>we</span>\
  \ <span m='487229'>needed</span> <span m='487479'>to</span> <span m='487729'>choose</span>\
  \ <span m='487979'>which</span> <span m='488229'>member</span> <span m='488479'>of</span>\
  \ <span m='488729'>a</span> <span m='488979'>set</span> <span m='489229'>to</span>\
  \ <span m='489479'>replace,</span> <span m='489729'>we'd</span> <span m='489979'>choose</span>\
  \ <span m='490229'>the</span> <span m='490479'>last</span> <span m='490729'>cache</span>\
  \ <span m='490979'>line</span> <span m='491559'>on</span> <span m='492139'>this</span>\
  \ <span m='492719'>list.</span> </p><p><span m='493300'>For</span> <span m='493772'>an</span>\
  \ <span m='494244'>8-way</span> <span m='494717'>SA</span> <span m='495189'>cache</span>\
  \ <span m='495661'>there</span> <span m='496134'>are</span> <span m='496606'>8!</span>\
  \ <span m='497078'>possible</span> <span m='497551'>orderings,</span> <span m='498023'>so</span>\
  \ <span m='498495'>we'd</span> <span m='498968'>need</span> <span m='499440'>log2(8!)</span>\
  \ <span m='499912'>=</span> <span m='500385'>16</span> <span m='500857'>state</span>\
  \ <span m='501330'>bits</span> <span m='501889'>to</span> <span m='502449'>encode</span>\
  \ <span m='503009'>the</span> <span m='503569'>current</span> <span m='504129'>ordering.</span>\
  \ </p><p><span m='504689'>The</span> <span m='505010'>logic</span> <span m='505332'>to</span>\
  \ <span m='505654'>update</span> <span m='505976'>these</span> <span m='506297'>state</span>\
  \ <span m='506619'>bits</span> <span m='506941'>on</span> <span m='507263'>each</span>\
  \ <span m='507584'>access</span> <span m='507906'>isn't</span> <span m='508228'>cheap.</span>\
  \ </p><p><span m='508550'>Basically</span> <span m='508917'>you</span> <span m='509285'>need</span>\
  \ <span m='509652'>a</span> <span m='510020'>lookup</span> <span m='510387'>table</span>\
  \ <span m='510755'>to</span> <span m='511123'>map</span> <span m='511490'>the</span>\
  \ <span m='511858'>current</span> <span m='512225'>16-bit</span> <span m='512593'>value</span>\
  \ <span m='512961'>to</span> <span m='513328'>the</span> <span m='513696'>next</span>\
  \ <span m='514063'>16-bit</span> <span m='514431'>value.</span> </p><p><span m='514799'>So</span>\
  \ <span m='515119'>most</span> <span m='515440'>caches</span> <span m='515761'>implement</span>\
  \ <span m='516081'>an</span> <span m='516402'>approximation</span> <span m='516723'>to</span>\
  \ <span m='517044'>LRU</span> <span m='517364'>where</span> <span m='517685'>the</span>\
  \ <span m='518006'>update</span> <span m='518327'>function</span> <span m='518647'>is</span>\
  \ <span m='518968'>much</span> <span m='519289'>simpler</span> <span m='519610'>to</span>\
  \ <span m='521074'>compute.</span> </p><p><span m='522539'>There</span> <span m='522965'>are</span>\
  \ <span m='523392'>other</span> <span m='523819'>possible</span> <span m='524246'>replacement</span>\
  \ <span m='524672'>policies:</span> <span m='525099'>First-in,</span> <span m='525526'>first-out,</span>\
  \ <span m='525953'>where</span> <span m='526379'>the</span> <span m='526806'>oldest</span>\
  \ <span m='527233'>cache</span> <span m='527660'>line</span> <span m='527940'>is</span>\
  \ <span m='528220'>replaced</span> <span m='528500'>regardless</span> <span m='528780'>of</span>\
  \ <span m='529060'>when</span> <span m='529340'>it</span> <span m='529620'>was</span>\
  \ <span m='529900'>last</span> <span m='530180'>accessed.</span> </p><p><span m='530460'>And</span>\
  \ <span m='530940'>Random,</span> <span m='531421'>where</span> <span m='531902'>some</span>\
  \ <span m='532382'>sort</span> <span m='532863'>of</span> <span m='533344'>pseudo-random</span>\
  \ <span m='533824'>number</span> <span m='534305'>generator</span> <span m='534786'>is</span>\
  \ <span m='535266'>used</span> <span m='535747'>to</span> <span m='536228'>select</span>\
  \ <span m='536708'>the</span> <span m='537189'>replacement.</span> </p><p><span\
  \ m='537670'>All</span> <span m='538097'>replacement</span> <span m='538525'>strategies</span>\
  \ <span m='538953'>except</span> <span m='539381'>for</span> <span m='539808'>random</span>\
  \ <span m='540236'>can</span> <span m='540664'>be</span> <span m='541092'>defeated.</span>\
  \ </p><p><span m='541520'>If</span> <span m='541758'>you</span> <span m='541996'>know</span>\
  \ <span m='542234'>a</span> <span m='542472'>cache's</span> <span m='542710'>replacement</span>\
  \ <span m='542948'>strategy</span> <span m='543186'>you</span> <span m='543425'>can</span>\
  \ <span m='543663'>design</span> <span m='543901'>a</span> <span m='544139'>program</span>\
  \ <span m='544377'>that</span> <span m='544615'>will</span> <span m='544853'>have</span>\
  \ <span m='545091'>an</span> <span m='545330'>abysmal</span> <span m='545782'>hit</span>\
  \ <span m='546235'>rate</span> <span m='546687'>by</span> <span m='547140'>accessing</span>\
  \ <span m='547592'>addresses</span> <span m='548045'>you</span> <span m='548497'>know</span>\
  \ <span m='548950'>the</span> <span m='549402'>cache</span> <span m='549855'>just</span>\
  \ <span m='550307'>replaced.</span> </p><p><span m='550760'>I'm</span> <span m='551056'>not</span>\
  \ <span m='551352'>sure</span> <span m='551648'>I</span> <span m='551944'>care</span>\
  \ <span m='552240'>about</span> <span m='552536'>how</span> <span m='552832'>well</span>\
  \ <span m='553128'>a</span> <span m='553425'>program</span> <span m='553721'>designed</span>\
  \ <span m='554017'>to</span> <span m='554313'>get</span> <span m='554609'>bad</span>\
  \ <span m='554905'>performance</span> <span m='555201'>runs</span> <span m='555497'>on</span>\
  \ <span m='555793'>my</span> <span m='556090'>system,</span> <span m='556471'>but</span>\
  \ <span m='556852'>the</span> <span m='557234'>point</span> <span m='557615'>is</span>\
  \ <span m='557997'>that</span> <span m='558378'>most</span> <span m='558760'>replacement</span>\
  \ <span m='559141'>strategies</span> <span m='559522'>will</span> <span m='559904'>occasionally</span>\
  \ <span m='560285'>cause</span> <span m='560667'>a</span> <span m='561048'>particular</span>\
  \ <span m='561430'>program</span> <span m='561994'>to</span> <span m='562559'>execute</span>\
  \ <span m='563124'>much</span> <span m='563689'>more</span> <span m='564254'>slowly</span>\
  \ <span m='564819'>than</span> <span m='565384'>expected.</span> </p><p><span m='565949'>When</span>\
  \ <span m='566249'>all</span> <span m='566550'>is</span> <span m='566850'>said</span>\
  \ <span m='567151'>and</span> <span m='567452'>done,</span> <span m='567752'>an</span>\
  \ <span m='568053'>LRU</span> <span m='568354'>replacement</span> <span m='568654'>strategy</span>\
  \ <span m='568955'>or</span> <span m='569256'>a</span> <span m='569556'>close</span>\
  \ <span m='569857'>approximation</span> <span m='570158'>is</span> <span m='570458'>a</span>\
  \ <span m='570759'>reasonable</span> <span m='571060'>choice.</span> </p>"
type: course
uid: 9e13d2d0eb83a0ec08f66213de883474

---
None