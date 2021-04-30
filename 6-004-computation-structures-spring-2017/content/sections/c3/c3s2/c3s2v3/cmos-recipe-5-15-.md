---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 2JxUXSG9rKo
  parent_uid: 6511917b53241ec56bfd42dafbd8dbe2
  title: Video-YouTube-Stream
  type: Video
  uid: 8e25d58c13125d2af4fbd90bf592386d
- id: 3Play-3Play YouTube id-Stream
  media_location: 2JxUXSG9rKo
  parent_uid: 6511917b53241ec56bfd42dafbd8dbe2
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: fab1bc62efddb1b20f70355f8d6a0ba3
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/2JxUXSG9rKo/default.jpg
  parent_uid: 6511917b53241ec56bfd42dafbd8dbe2
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 2ea9c6e99dad55014cc3aae374e8dd0e
- id: 2JxUXSG9rKo.srt
  parent_uid: 6511917b53241ec56bfd42dafbd8dbe2
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c3/c3s2/c3s2v3/cmos-recipe-5-15-/2JxUXSG9rKo.srt
  title: 3play caption file
  type: null
  uid: b493961cda3195614f5bbebb3a86b261
- id: 2JxUXSG9rKo.pdf
  parent_uid: 6511917b53241ec56bfd42dafbd8dbe2
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c3/c3s2/c3s2v3/cmos-recipe-5-15-/2JxUXSG9rKo.pdf
  title: 3play pdf file
  type: null
  uid: 301932242a28f5e138c831576d57fd8f
- id: Caption-3Play YouTube id-SRT
  parent_uid: 6511917b53241ec56bfd42dafbd8dbe2
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 6a63de21b196dc0403739129c8714437
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 6511917b53241ec56bfd42dafbd8dbe2
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 0f0fad8d939f841fdf986aa5bf5fe844
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_03-02-03_300k.mp4
  parent_uid: 6511917b53241ec56bfd42dafbd8dbe2
  title: Video-Internet Archive-MP4
  type: Video
  uid: 52d5c5a9e13609fd27dc11195b0cf637
inline_embed_id: 46415667cmosrecipe51572569422
layout: video
order_index: null
parent_uid: 4b31a7f2a3c844a25b79428b941b731c
related_resources_text: ''
short_url: cmos-recipe-5-15-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c3/c3s2/c3s2v3/cmos-recipe-5-15-
template_type: Embed
title: CMOS Recipe (5:15)
transcript: <p><span m='1069'>Now</span> <span m='1365'>that</span> <span m='1662'>we</span>
  <span m='1959'>have</span> <span m='2256'>some</span> <span m='2553'>sense</span>
  <span m='2850'>about</span> <span m='3147'>how</span> <span m='3444'>MOSFETs</span>
  <span m='3740'>function,</span> <span m='4037'>let's</span> <span m='4334'>use</span>
  <span m='4631'>them</span> <span m='4928'>to</span> <span m='5225'>build</span>
  <span m='5522'>circuits</span> <span m='5819'>to</span> <span m='6394'>process</span>
  <span m='6969'>our</span> <span m='7544'>digitally</span> <span m='8119'>encoded</span>
  <span m='8694'>information.</span> </p><p><span m='9270'>We</span> <span m='9601'>have</span>
  <span m='9933'>two</span> <span m='10265'>simple</span> <span m='10597'>rules</span>
  <span m='10929'>we'll</span> <span m='11261'>use</span> <span m='11593'>when</span>
  <span m='11925'>building</span> <span m='12257'>the</span> <span m='12589'>circuits,</span>
  <span m='12921'>which,</span> <span m='13253'>if</span> <span m='13585'>they're</span>
  <span m='13917'>followed,</span> <span m='14249'>will</span> <span m='14610'>allow</span>
  <span m='14972'>us</span> <span m='15333'>to</span> <span m='15695'>abstract</span>
  <span m='16056'>the</span> <span m='16418'>behavior</span> <span m='16779'>of</span>
  <span m='17141'>the</span> <span m='17502'>MOSFET</span> <span m='17864'>as</span>
  <span m='18225'>a</span> <span m='18587'>simple</span> <span m='18948'>voltage-controlled</span>
  <span m='19310'>switch.</span> </p><p><span m='20900'>The</span> <span m='21282'>first</span>
  <span m='21665'>rule</span> <span m='22047'>is</span> <span m='22430'>that</span>
  <span m='22812'>we'll</span> <span m='23195'>only</span> <span m='23577'>use</span>
  <span m='23960'>n-channel</span> <span m='24342'>MOSFETs,</span> <span m='24725'>which</span>
  <span m='25107'>we'll</span> <span m='25490'>call</span> <span m='25872'>NFETs</span>
  <span m='26255'>for</span> <span m='26637'>short,</span> <span m='27020'>when</span>
  <span m='27302'>building</span> <span m='27585'>pulldown</span> <span m='27867'>circuits</span>
  <span m='28150'>that</span> <span m='28433'>connect</span> <span m='28715'>a</span>
  <span m='28998'>signaling</span> <span m='29280'>node</span> <span m='29563'>to</span>
  <span m='29846'>the</span> <span m='30128'>GROUND</span> <span m='30411'>rail</span>
  <span m='30693'>of</span> <span m='30976'>the</span> <span m='31259'>power</span>
  <span m='32199'>supply.</span> </p><p><span m='33140'>When</span> <span m='33477'>the</span>
  <span m='33815'>pulldown</span> <span m='34152'>circuit</span> <span m='34490'>is</span>
  <span m='34827'>conducting,</span> <span m='35165'>the</span> <span m='35502'>signaling</span>
  <span m='35840'>node</span> <span m='36177'>will</span> <span m='36515'>be</span>
  <span m='36852'>at</span> <span m='37190'>0V</span> <span m='37527'>and</span> <span
  m='37865'>qualify</span> <span m='38202'>as</span> <span m='38540'>the</span> <span
  m='39305'>digital</span> <span m='40070'>value</span> <span m='40835'>"0".</span>
  </p><p><span m='41600'>If</span> <span m='41963'>we</span> <span m='42327'>obey</span>
  <span m='42691'>this</span> <span m='43055'>rule,</span> <span m='43419'>NFETs</span>
  <span m='43783'>will</span> <span m='44147'>act</span> <span m='44511'>switches</span>
  <span m='44875'>controlled</span> <span m='45239'>by</span> <span m='45603'>V_GS,</span>
  <span m='45967'>the</span> <span m='46331'>difference</span> <span m='46695'>between</span>
  <span m='47059'>the</span> <span m='47332'>voltage</span> <span m='47606'>of</span>
  <span m='47880'>the</span> <span m='48154'>gate</span> <span m='48428'>terminal</span>
  <span m='48702'>and</span> <span m='48976'>the</span> <span m='49250'>voltage</span>
  <span m='49524'>of</span> <span m='49798'>the</span> <span m='50072'>source</span>
  <span m='50346'>terminal.</span> </p><p><span m='50620'>When</span> <span m='50998'>V_GS</span>
  <span m='51376'>is</span> <span m='51754'>lower</span> <span m='52132'>than</span>
  <span m='52510'>the</span> <span m='52888'>MOSFET's</span> <span m='53266'>threshold</span>
  <span m='53645'>voltage,</span> <span m='54023'>the</span> <span m='54401'>switch</span>
  <span m='54779'>is</span> <span m='55157'>"open"</span> <span m='55535'>or</span>
  <span m='55913'>not</span> <span m='56291'>conducting</span> <span m='56670'>and</span>
  <span m='57101'>there</span> <span m='57533'>is</span> <span m='57965'>no</span>
  <span m='58396'>connection</span> <span m='58828'>between</span> <span m='59260'>the</span>
  <span m='59691'>MOSFET's</span> <span m='60123'>source</span> <span m='60555'>and</span>
  <span m='60986'>drain</span> <span m='61418'>terminals.</span> </p><p><span m='61850'>If</span>
  <span m='62172'>V_GS</span> <span m='62495'>is</span> <span m='62817'>greater</span>
  <span m='63140'>than</span> <span m='63462'>the</span> <span m='63785'>threshold</span>
  <span m='64107'>voltage,</span> <span m='64430'>the</span> <span m='64752'>switch</span>
  <span m='65075'>is</span> <span m='65397'>"on"</span> <span m='65720'>or</span>
  <span m='66042'>conducting</span> <span m='66365'>and</span> <span m='66687'>there</span>
  <span m='67010'>is</span> <span m='67373'>a</span> <span m='67736'>connection</span>
  <span m='68100'>between</span> <span m='68463'>the</span> <span m='68826'>source</span>
  <span m='69190'>and</span> <span m='69553'>drain</span> <span m='69916'>terminals.</span>
  </p><p><span m='70280'>That</span> <span m='70664'>path</span> <span m='71049'>has</span>
  <span m='71433'>a</span> <span m='71818'>resistance</span> <span m='72202'>determined</span>
  <span m='72587'>by</span> <span m='72971'>the</span> <span m='73356'>magnitude</span>
  <span m='73740'>of</span> <span m='74125'>V_GS.</span> </p><p><span m='74510'>The</span>
  <span m='74771'>larger</span> <span m='75032'>V_GS,</span> <span m='75293'>the</span>
  <span m='75554'>lower</span> <span m='75815'>the</span> <span m='76077'>effective</span>
  <span m='76338'>resistance</span> <span m='76599'>of</span> <span m='76860'>the</span>
  <span m='77121'>switch</span> <span m='77382'>and</span> <span m='77644'>the</span>
  <span m='77905'>more</span> <span m='78166'>current</span> <span m='78427'>that</span>
  <span m='78688'>will</span> <span m='78950'>flow</span> <span m='79491'>from</span>
  <span m='80033'>drain</span> <span m='80574'>to</span> <span m='81116'>source.</span>
  </p><p><span m='81658'>When</span> <span m='81996'>designing</span> <span m='82334'>pulldown</span>
  <span m='82672'>circuits</span> <span m='83010'>of</span> <span m='83348'>NFET</span>
  <span m='83686'>switches,</span> <span m='84024'>we</span> <span m='84362'>can</span>
  <span m='84700'>use</span> <span m='85038'>the</span> <span m='85376'>following</span>
  <span m='85714'>simple</span> <span m='86052'>mental</span> <span m='86390'>model</span>
  <span m='86729'>for</span> <span m='87076'>each</span> <span m='87423'>NFET</span>
  <span m='87770'>switch:</span> <span m='88117'>if</span> <span m='88465'>the</span>
  <span m='88812'>gate</span> <span m='89159'>voltage</span> <span m='89506'>is</span>
  <span m='89853'>a</span> <span m='90201'>digital</span> <span m='90548'>0,</span>
  <span m='90895'>the</span> <span m='91242'>switch</span> <span m='91590'>will</span>
  <span m='91969'>be</span> <span m='92348'>off;</span> <span m='92727'>if</span>
  <span m='93107'>the</span> <span m='93486'>gate</span> <span m='93865'>voltage</span>
  <span m='94244'>is</span> <span m='94624'>a</span> <span m='95003'>digital</span>
  <span m='95382'>1,</span> <span m='95761'>the</span> <span m='96141'>switch</span>
  <span m='96520'>will</span> <span m='96899'>be</span> <span m='97278'>on.</span>
  </p><p><span m='97658'>The</span> <span m='98116'>situation</span> <span m='98575'>with</span>
  <span m='99033'>PFET</span> <span m='99492'>switches</span> <span m='99950'>is</span>
  <span m='100409'>analogous,</span> <span m='100867'>except</span> <span m='101326'>that</span>
  <span m='101784'>the</span> <span m='102243'>potentials</span> <span m='102701'>are</span>
  <span m='103160'>reversed.</span> </p><p><span m='103619'>Our</span> <span m='103960'>rule</span>
  <span m='104301'>is</span> <span m='104642'>that</span> <span m='104983'>PFETs</span>
  <span m='105325'>can</span> <span m='105666'>only</span> <span m='106007'>be</span>
  <span m='106348'>used</span> <span m='106690'>in</span> <span m='107031'>pullup</span>
  <span m='107372'>circuits,</span> <span m='107713'>used</span> <span m='108055'>to</span>
  <span m='108396'>connect</span> <span m='108737'>a</span> <span m='109078'>signaling</span>
  <span m='109420'>node</span> <span m='109846'>to</span> <span m='110273'>the</span>
  <span m='110700'>power</span> <span m='111127'>supply</span> <span m='111554'>voltage,</span>
  <span m='111981'>which</span> <span m='112408'>we'll</span> <span m='112835'>call</span>
  <span m='113262'>V_DD.</span> </p><p><span m='113689'>When</span> <span m='113970'>the</span>
  <span m='114251'>pullup</span> <span m='114532'>circuit</span> <span m='114814'>is</span>
  <span m='115095'>conducting,</span> <span m='115376'>the</span> <span m='115657'>signaling</span>
  <span m='115939'>node</span> <span m='116220'>will</span> <span m='116501'>be</span>
  <span m='116782'>at</span> <span m='117064'>V_DD</span> <span m='117345'>volts</span>
  <span m='117626'>and</span> <span m='117907'>qualify</span> <span m='118189'>as</span>
  <span m='119033'>the</span> <span m='119877'>digital</span> <span m='120721'>value</span>
  <span m='121565'>"1".</span> </p><p><span m='122409'>PFETs</span> <span m='122702'>have</span>
  <span m='122995'>a</span> <span m='123288'>negative</span> <span m='123581'>threshold</span>
  <span m='123874'>voltage</span> <span m='124168'>and</span> <span m='124461'>V_GS</span>
  <span m='124754'>has</span> <span m='125047'>to</span> <span m='125340'>be</span>
  <span m='125634'>less</span> <span m='125927'>than</span> <span m='126220'>the</span>
  <span m='126513'>threshold</span> <span m='126806'>voltage</span> <span m='127100'>in</span>
  <span m='127422'>order</span> <span m='127744'>for</span> <span m='128066'>the</span>
  <span m='128388'>PFET</span> <span m='128711'>switch</span> <span m='129033'>to</span>
  <span m='129355'>be</span> <span m='129677'>conducting.</span> </p><p><span m='130000'>All</span>
  <span m='130303'>these</span> <span m='130606'>negatives</span> <span m='130910'>can</span>
  <span m='131213'>be</span> <span m='131516'>a</span> <span m='131820'>bit</span>
  <span m='132123'>confusing,</span> <span m='132426'>but,</span> <span m='132730'>happily</span>
  <span m='133033'>there's</span> <span m='133336'>a</span> <span m='133640'>simple</span>
  <span m='133943'>mental</span> <span m='134246'>model</span> <span m='134550'>we</span>
  <span m='134873'>can</span> <span m='135197'>use</span> <span m='135520'>for</span>
  <span m='135844'>each</span> <span m='136168'>PFET</span> <span m='136491'>switch</span>
  <span m='136815'>in</span> <span m='137139'>the</span> <span m='137462'>pullup</span>
  <span m='137786'>circuit:</span> <span m='138110'>if</span> <span m='138378'>the</span>
  <span m='138647'>gate</span> <span m='138915'>voltage</span> <span m='139184'>is</span>
  <span m='139452'>a</span> <span m='139721'>digital</span> <span m='139989'>0,</span>
  <span m='140258'>the</span> <span m='140526'>switch</span> <span m='140795'>will</span>
  <span m='141063'>be</span> <span m='141332'>on;</span> <span m='141600'>if</span>
  <span m='141869'>the</span> <span m='142137'>gate</span> <span m='142406'>voltage</span>
  <span m='142674'>is</span> <span m='142943'>a</span> <span m='143211'>digital</span>
  <span m='143480'>1,</span> <span m='143932'>the</span> <span m='144385'>switch</span>
  <span m='144838'>will</span> <span m='145290'>be</span> <span m='145743'>off</span>
  <span m='146196'>-</span> <span m='146648'>basically</span> <span m='147101'>the</span>
  <span m='147554'>opposite</span> <span m='148006'>behavior</span> <span m='148459'>of</span>
  <span m='148912'>the</span> <span m='149364'>NFET</span> <span m='149817'>switch.</span>
  </p><p><span m='150270'>You</span> <span m='150645'>may</span> <span m='151021'>be</span>
  <span m='151397'>wondering</span> <span m='151773'>why</span> <span m='152149'>we</span>
  <span m='152525'>can't</span> <span m='152901'>use</span> <span m='153277'>NFETs</span>
  <span m='153652'>in</span> <span m='154028'>pullup</span> <span m='154404'>circuits</span>
  <span m='154780'>or</span> <span m='155156'>PFETs</span> <span m='155532'>in</span>
  <span m='155908'>pulldown</span> <span m='156284'>circuits.</span> </p><p><span
  m='156660'>You'll</span> <span m='156970'>get</span> <span m='157280'>to</span>
  <span m='157590'>explore</span> <span m='157900'>the</span> <span m='158210'>answer</span>
  <span m='158520'>to</span> <span m='158830'>this</span> <span m='159140'>question</span>
  <span m='159450'>in</span> <span m='159760'>the</span> <span m='160070'>first</span>
  <span m='160380'>lab</span> <span m='160690'>of</span> <span m='161000'>Assignment</span>
  <span m='161310'>2.</span> </p><p><span m='161620'>Meanwhile,</span> <span m='162052'>the</span>
  <span m='162484'>short</span> <span m='162916'>answer</span> <span m='163348'>is</span>
  <span m='163780'>that</span> <span m='164212'>the</span> <span m='164645'>signaling</span>
  <span m='165077'>node</span> <span m='165509'>will</span> <span m='165941'>experience</span>
  <span m='166373'>degraded</span> <span m='166805'>signaling</span> <span m='167237'>levels</span>
  <span m='167670'>and</span> <span m='168061'>we'll</span> <span m='168453'>loose</span>
  <span m='168845'>the</span> <span m='169236'>noise</span> <span m='169628'>margins</span>
  <span m='170020'>we've</span> <span m='170411'>worked</span> <span m='170803'>so</span>
  <span m='171195'>hard</span> <span m='171586'>to</span> <span m='171978'>create!</span>
  </p><p><span m='172370'>Now</span> <span m='172888'>consider</span> <span m='173407'>the</span>
  <span m='173926'>CMOS</span> <span m='174445'>implementation</span> <span m='174964'>of</span>
  <span m='175483'>a</span> <span m='176002'>combinational</span> <span m='176521'>inverter.</span>
  </p><p><span m='177040'>If</span> <span m='177411'>the</span> <span m='177783'>inverter's</span>
  <span m='178155'>input</span> <span m='178527'>is</span> <span m='178898'>a</span>
  <span m='179270'>digital</span> <span m='179642'>0,</span> <span m='180014'>its</span>
  <span m='180385'>output</span> <span m='180757'>is</span> <span m='181129'>a</span>
  <span m='181501'>digital</span> <span m='181872'>1,</span> <span m='182244'>and</span>
  <span m='182616'>vice</span> <span m='182988'>versa.</span> </p><p><span m='183360'>The</span>
  <span m='183717'>inverter</span> <span m='184075'>circuit</span> <span m='184433'>consists</span>
  <span m='184791'>of</span> <span m='185149'>a</span> <span m='185507'>single</span>
  <span m='185865'>NFET</span> <span m='186222'>switch</span> <span m='186580'>for</span>
  <span m='186938'>the</span> <span m='187296'>pulldown</span> <span m='187654'>circuit,</span>
  <span m='188012'>connecting</span> <span m='188370'>the</span> <span m='188738'>output</span>
  <span m='189106'>node</span> <span m='189474'>to</span> <span m='189842'>GROUND</span>
  <span m='190210'>and</span> <span m='190578'>a</span> <span m='190946'>single</span>
  <span m='191314'>PFET</span> <span m='191682'>switch</span> <span m='192050'>for</span>
  <span m='192418'>the</span> <span m='192786'>pullup</span> <span m='193154'>circuit,</span>
  <span m='193522'>connecting</span> <span m='193890'>the</span> <span m='194487'>output</span>
  <span m='195085'>to</span> <span m='195682'>V_DD.</span> </p><p><span m='196280'>The</span>
  <span m='196659'>gate</span> <span m='197038'>terminals</span> <span m='197417'>of</span>
  <span m='197796'>both</span> <span m='198176'>switches</span> <span m='198555'>are</span>
  <span m='198934'>connected</span> <span m='199313'>to</span> <span m='199693'>the</span>
  <span m='200072'>inverter's</span> <span m='200451'>input</span> <span m='200830'>node.</span>
  </p><p><span m='201210'>The</span> <span m='201574'>inverter's</span> <span m='201938'>voltage</span>
  <span m='202302'>transfer</span> <span m='202666'>characteristic</span> <span m='203030'>is</span>
  <span m='203394'>shown</span> <span m='203758'>in</span> <span m='204122'>the</span>
  <span m='204486'>figure.</span> </p><p><span m='204850'>When</span> <span m='205220'>V_IN</span>
  <span m='205591'>is</span> <span m='205961'>a</span> <span m='206332'>digital</span>
  <span m='206702'>0</span> <span m='207073'>input,</span> <span m='207443'>we</span>
  <span m='207814'>see</span> <span m='208184'>that</span> <span m='208555'>V_OUT</span>
  <span m='208925'>is</span> <span m='209296'>greater</span> <span m='209666'>than</span>
  <span m='210037'>or</span> <span m='210407'>equal</span> <span m='210778'>to</span>
  <span m='211148'>V_OH,</span> <span m='211519'>representing</span> <span m='211890'>a</span>
  <span m='212495'>digital</span> <span m='213100'>1</span> <span m='213705'>output.</span>
  </p><p><span m='214310'>Let's</span> <span m='214572'>look</span> <span m='214834'>at</span>
  <span m='215097'>the</span> <span m='215359'>state</span> <span m='215621'>of</span>
  <span m='215884'>the</span> <span m='216146'>pullup</span> <span m='216408'>and</span>
  <span m='216671'>pulldown</span> <span m='216933'>switches</span> <span m='217195'>when</span>
  <span m='217458'>the</span> <span m='217720'>input</span> <span m='217982'>is</span>
  <span m='218245'>a</span> <span m='218507'>digital</span> <span m='218770'>0.</span>
  </p><p><span m='219770'>Recalling</span> <span m='220162'>the</span> <span m='220554'>simple</span>
  <span m='220946'>mental</span> <span m='221338'>model</span> <span m='221730'>for</span>
  <span m='222122'>the</span> <span m='222514'>NFET</span> <span m='222906'>and</span>
  <span m='223298'>PFET</span> <span m='223690'>switches,</span> <span m='224082'>a</span>
  <span m='224474'>0-input</span> <span m='224866'>means</span> <span m='225258'>the</span>
  <span m='225650'>NFET</span> <span m='225966'>switch</span> <span m='226283'>is</span>
  <span m='226600'>off,</span> <span m='226917'>so</span> <span m='227234'>there's</span>
  <span m='227551'>no</span> <span m='227868'>connection</span> <span m='228185'>between</span>
  <span m='228501'>the</span> <span m='228818'>output</span> <span m='229135'>node</span>
  <span m='229452'>and</span> <span m='229769'>ground,</span> <span m='230086'>and</span>
  <span m='230403'>the</span> <span m='230720'>PFET</span> <span m='231165'>switch</span>
  <span m='231610'>is</span> <span m='232056'>on,</span> <span m='232501'>making</span>
  <span m='232946'>a</span> <span m='233392'>connection</span> <span m='233837'>between</span>
  <span m='234283'>the</span> <span m='234728'>output</span> <span m='235173'>node</span>
  <span m='235619'>and</span> <span m='236064'>V_DD.</span> </p><p><span m='236510'>Current</span>
  <span m='236778'>will</span> <span m='237047'>flow</span> <span m='237315'>through</span>
  <span m='237584'>the</span> <span m='237852'>pullup</span> <span m='238121'>switch,</span>
  <span m='238390'>charging</span> <span m='238658'>the</span> <span m='238927'>output</span>
  <span m='239195'>node</span> <span m='239464'>until</span> <span m='239732'>its</span>
  <span m='240001'>voltage</span> <span m='240270'>reaches</span> <span m='241370'>V_DD.</span>
  </p><p><span m='242470'>Once</span> <span m='242780'>both</span> <span m='243090'>the</span>
  <span m='243400'>source</span> <span m='243710'>and</span> <span m='244020'>drain</span>
  <span m='244330'>terminals</span> <span m='244640'>are</span> <span m='244950'>at</span>
  <span m='245260'>V_DD,</span> <span m='245570'>there's</span> <span m='245880'>no</span>
  <span m='246190'>voltage</span> <span m='246500'>difference</span> <span m='246810'>across</span>
  <span m='247120'>the</span> <span m='247480'>switch</span> <span m='247840'>and</span>
  <span m='248200'>hence</span> <span m='248560'>no</span> <span m='248920'>more</span>
  <span m='249280'>current</span> <span m='249640'>will</span> <span m='250000'>flow</span>
  <span m='250360'>through</span> <span m='250720'>the</span> <span m='251080'>switch.</span>
  </p><p><span m='251440'>Similarly,</span> <span m='251798'>when</span> <span m='252157'>V_IN</span>
  <span m='252516'>is</span> <span m='252875'>a</span> <span m='253234'>digital</span>
  <span m='253593'>1,</span> <span m='253952'>the</span> <span m='254311'>NFET</span>
  <span m='254670'>switch</span> <span m='255029'>is</span> <span m='255388'>on</span>
  <span m='255747'>and</span> <span m='256106'>PFET</span> <span m='256465'>switch</span>
  <span m='256824'>is</span> <span m='257183'>off,</span> <span m='257542'>so</span>
  <span m='257901'>the</span> <span m='258260'>output</span> <span m='258638'>is</span>
  <span m='259016'>connected</span> <span m='259395'>to</span> <span m='259773'>ground</span>
  <span m='260151'>and</span> <span m='260530'>eventually</span> <span m='260908'>reaches</span>
  <span m='261286'>a</span> <span m='261665'>voltage</span> <span m='262043'>of</span>
  <span m='262421'>0V.</span> </p><p><span m='262800'>Again,</span> <span m='263271'>current</span>
  <span m='263742'>flow</span> <span m='264214'>through</span> <span m='264685'>pulldown</span>
  <span m='265157'>switch</span> <span m='265628'>will</span> <span m='266100'>cease</span>
  <span m='266571'>once</span> <span m='267042'>the</span> <span m='267514'>output</span>
  <span m='267985'>node</span> <span m='268457'>reaches</span> <span m='268928'>0V.</span>
  </p><p><span m='269400'>When</span> <span m='269675'>the</span> <span m='269951'>input</span>
  <span m='270226'>voltage</span> <span m='270502'>is</span> <span m='270778'>in</span>
  <span m='271053'>the</span> <span m='271329'>middle</span> <span m='271605'>of</span>
  <span m='271880'>its</span> <span m='272156'>range,</span> <span m='272431'>it's</span>
  <span m='272707'>possible,</span> <span m='272983'>depending</span> <span m='273258'>on</span>
  <span m='273534'>the</span> <span m='273810'>particular</span> <span m='274169'>power</span>
  <span m='274528'>supply</span> <span m='274887'>voltage</span> <span m='275247'>used</span>
  <span m='275606'>and</span> <span m='275965'>the</span> <span m='276325'>threshold</span>
  <span m='276684'>voltage</span> <span m='277043'>of</span> <span m='277402'>the</span>
  <span m='277762'>MOSFETs,</span> <span m='278121'>that</span> <span m='278480'>both</span>
  <span m='278840'>the</span> <span m='279147'>pullup</span> <span m='279454'>and</span>
  <span m='279761'>pulldown</span> <span m='280068'>circuits</span> <span m='280375'>will</span>
  <span m='280682'>be</span> <span m='280990'>conducting</span> <span m='281297'>for</span>
  <span m='281604'>a</span> <span m='281911'>short</span> <span m='282218'>period</span>
  <span m='282525'>of</span> <span m='282832'>time.</span> </p><p><span m='283140'>That's</span>
  <span m='283640'>okay.</span> </p><p><span m='284140'>In</span> <span m='284484'>fact,</span>
  <span m='284829'>with</span> <span m='285174'>both</span> <span m='285518'>MOSFET</span>
  <span m='285863'>switches</span> <span m='286208'>on,</span> <span m='286552'>small</span>
  <span m='286897'>changes</span> <span m='287242'>in</span> <span m='287586'>the</span>
  <span m='287931'>input</span> <span m='288276'>voltage</span> <span m='288620'>will</span>
  <span m='288965'>produce</span> <span m='289310'>large</span> <span m='289772'>changes</span>
  <span m='290235'>in</span> <span m='290697'>the</span> <span m='291160'>output</span>
  <span m='291622'>voltage,</span> <span m='292085'>leading</span> <span m='292547'>to</span>
  <span m='293010'>the</span> <span m='293472'>very</span> <span m='293935'>high</span>
  <span m='294397'>gain</span> <span m='294860'>exhibited</span> <span m='295322'>by</span>
  <span m='295785'>CMOS</span> <span m='296247'>devices.</span> </p><p><span m='296710'>This</span>
  <span m='296998'>in</span> <span m='297287'>turn</span> <span m='297575'>will</span>
  <span m='297864'>mean</span> <span m='298152'>we</span> <span m='298441'>can</span>
  <span m='298730'>pick</span> <span m='299018'>signaling</span> <span m='299307'>thresholds</span>
  <span m='299595'>that</span> <span m='299884'>incorporate</span> <span m='300172'>generous</span>
  <span m='300461'>noise</span> <span m='300750'>margins,</span> <span m='301317'>allowing</span>
  <span m='301885'>CMOS</span> <span m='302452'>devices</span> <span m='303020'>to</span>
  <span m='303587'>work</span> <span m='304155'>reliably</span> <span m='304722'>in</span>
  <span m='305290'>many</span> <span m='305857'>different</span> <span m='306425'>operating</span>
  <span m='306992'>environments.</span> </p><p><span m='307560'>This</span> <span
  m='307983'>is</span> <span m='308407'>our</span> <span m='308831'>first</span> <span
  m='309255'>CMOS</span> <span m='309678'>combinational</span> <span m='310102'>logic</span>
  <span m='310526'>gate.</span> </p><p><span m='310950'>In</span> <span m='311247'>the</span>
  <span m='311545'>next</span> <span m='311843'>video,</span> <span m='312141'>we'll</span>
  <span m='312439'>explore</span> <span m='312737'>how</span> <span m='313035'>to</span>
  <span m='313332'>build</span> <span m='313630'>other,</span> <span m='313928'>more</span>
  <span m='314226'>interesting</span> <span m='314524'>logic</span> <span m='314822'>functions.</span>
  </p>
type: course
uid: 6511917b53241ec56bfd42dafbd8dbe2

---
None