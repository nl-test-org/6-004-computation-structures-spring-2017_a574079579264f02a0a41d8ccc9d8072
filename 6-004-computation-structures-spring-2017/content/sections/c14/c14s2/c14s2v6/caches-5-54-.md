---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: TV6AtNbmLBE
  parent_uid: bd374d9d7e02e9684951e23c051ec3ba
  title: Video-YouTube-Stream
  type: Video
  uid: 932699ae64bb08aceb46709b95048281
- id: 3Play-3Play YouTube id-Stream
  media_location: TV6AtNbmLBE
  parent_uid: bd374d9d7e02e9684951e23c051ec3ba
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 0be8c605d0e429c7ac6b01150cc856d2
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/TV6AtNbmLBE/default.jpg
  parent_uid: bd374d9d7e02e9684951e23c051ec3ba
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: f489a422c293c2bce5be87476abde5dc
- id: TV6AtNbmLBE.srt
  parent_uid: bd374d9d7e02e9684951e23c051ec3ba
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v6/caches-5-54-/TV6AtNbmLBE.srt
  title: 3play caption file
  type: null
  uid: edf8765053d713826b6fd459a1e6eec9
- id: TV6AtNbmLBE.pdf
  parent_uid: bd374d9d7e02e9684951e23c051ec3ba
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v6/caches-5-54-/TV6AtNbmLBE.pdf
  title: 3play pdf file
  type: null
  uid: 875750bfd13cc3315504e9935e98f11c
- id: Caption-3Play YouTube id-SRT
  parent_uid: bd374d9d7e02e9684951e23c051ec3ba
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: d4b3f2d8cf542a9ad4807f648d8510e4
- id: Transcript-3Play YouTube id-PDF
  parent_uid: bd374d9d7e02e9684951e23c051ec3ba
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 317513768c4daaaabc34cec835108cc3
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_14-02-06_300k.mp4
  parent_uid: bd374d9d7e02e9684951e23c051ec3ba
  title: Video-Internet Archive-MP4
  type: Video
  uid: 1f1f35743f0c2cd66f12abc342db59f6
inline_embed_id: 28016599caches55429559402
layout: video
order_index: null
parent_uid: 0c00d76e9cc047e4d4368aafc7c9e6ae
related_resources_text: ''
short_url: caches-5-54-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v6/caches-5-54-
template_type: Embed
title: Caches (5:54)
transcript: <p><span m='960'>Okay,</span> <span m='1486'>let's</span> <span m='2012'>review</span>
  <span m='2538'>our</span> <span m='3064'>plan.</span> </p><p><span m='3590'>The</span>
  <span m='3935'>processor</span> <span m='4280'>starts</span> <span m='4625'>an</span>
  <span m='4970'>access</span> <span m='5315'>by</span> <span m='5660'>sending</span>
  <span m='6005'>an</span> <span m='6350'>address</span> <span m='6695'>to</span>
  <span m='7040'>the</span> <span m='7385'>cache.</span> </p><p><span m='7730'>If</span>
  <span m='8041'>data</span> <span m='8353'>for</span> <span m='8665'>the</span> <span
  m='8977'>requested</span> <span m='9289'>address</span> <span m='9600'>is</span>
  <span m='9912'>held</span> <span m='10224'>in</span> <span m='10536'>the</span>
  <span m='10848'>cache,</span> <span m='11159'>it's</span> <span m='11471'>quickly</span>
  <span m='11783'>returned</span> <span m='12095'>to</span> <span m='12407'>the</span>
  <span m='12719'>CPU.</span> </p><p><span m='13830'>If</span> <span m='14085'>the</span>
  <span m='14340'>data</span> <span m='14595'>we</span> <span m='14850'>request</span>
  <span m='15105'>is</span> <span m='15360'>not</span> <span m='15615'>in</span> <span
  m='15870'>the</span> <span m='16125'>cache,</span> <span m='16380'>we</span> <span
  m='16635'>have</span> <span m='16890'>a</span> <span m='17145'>cache</span> <span
  m='17400'>miss,</span> <span m='17655'>so</span> <span m='17910'>the</span> <span
  m='18165'>cache</span> <span m='18420'>has</span> <span m='18675'>to</span> <span
  m='18930'>make</span> <span m='19294'>a</span> <span m='19658'>request</span> <span
  m='20022'>to</span> <span m='20387'>main</span> <span m='20751'>memory</span> <span
  m='21115'>to</span> <span m='21480'>get</span> <span m='21844'>the</span> <span
  m='22208'>data,</span> <span m='22573'>which</span> <span m='22937'>it</span> <span
  m='23301'>then</span> <span m='23666'>returns</span> <span m='24030'>to</span> <span
  m='24394'>processor.</span> </p><p><span m='24759'>Typically</span> <span m='25107'>the</span>
  <span m='25455'>cache</span> <span m='25804'>will</span> <span m='26152'>remember</span>
  <span m='26501'>the</span> <span m='26849'>newly</span> <span m='27198'>fetched</span>
  <span m='27546'>data,</span> <span m='27895'>possibly</span> <span m='28243'>replacing</span>
  <span m='28592'>some</span> <span m='28940'>older</span> <span m='29289'>data</span>
  <span m='29706'>in</span> <span m='30124'>the</span> <span m='30542'>cache.</span>
  </p><p><span m='30960'>Suppose</span> <span m='31324'>a</span> <span m='31689'>cache</span>
  <span m='32053'>access</span> <span m='32418'>takes</span> <span m='32783'>4</span>
  <span m='33147'>ns</span> <span m='33512'>and</span> <span m='33876'>a</span> <span
  m='34241'>main</span> <span m='34606'>memory</span> <span m='34970'>access</span>
  <span m='35335'>takes</span> <span m='35699'>40</span> <span m='36064'>ns.</span>
  </p><p><span m='36429'>Then</span> <span m='36744'>an</span> <span m='37060'>access</span>
  <span m='37376'>that</span> <span m='37692'>hits</span> <span m='38007'>in</span>
  <span m='38323'>the</span> <span m='38639'>cache</span> <span m='38955'>has</span>
  <span m='39271'>a</span> <span m='39586'>latency</span> <span m='39902'>of</span>
  <span m='40218'>4</span> <span m='40534'>ns,</span> <span m='40850'>but</span> <span
  m='41165'>an</span> <span m='41481'>access</span> <span m='41797'>that</span> <span
  m='42113'>misses</span> <span m='42429'>in</span> <span m='42916'>the</span> <span
  m='43404'>cache</span> <span m='43892'>has</span> <span m='44380'>a</span> <span
  m='44868'>latency</span> <span m='45356'>of</span> <span m='45844'>44</span> <span
  m='46332'>ns.</span> </p><p><span m='46820'>The</span> <span m='47167'>processor</span>
  <span m='47515'>has</span> <span m='47863'>to</span> <span m='48211'>deal</span>
  <span m='48559'>with</span> <span m='48907'>the</span> <span m='49255'>variable</span>
  <span m='49603'>memory</span> <span m='49951'>access</span> <span m='50299'>time,</span>
  <span m='50647'>perhaps</span> <span m='50995'>by</span> <span m='51343'>simply</span>
  <span m='51691'>waiting</span> <span m='52039'>for</span> <span m='52421'>the</span>
  <span m='52803'>access</span> <span m='53186'>to</span> <span m='53568'>complete,</span>
  <span m='53950'>or,</span> <span m='54333'>in</span> <span m='54715'>modern</span>
  <span m='55098'>hyper-threaded</span> <span m='55480'>processors,</span> <span m='55862'>it</span>
  <span m='56245'>might</span> <span m='56627'>execute</span> <span m='57010'>an</span>
  <span m='57451'>instruction</span> <span m='57892'>or</span> <span m='58333'>two</span>
  <span m='58774'>from</span> <span m='59215'>another</span> <span m='59656'>programming</span>
  <span m='60097'>thread.</span> </p><p><span m='60539'>The</span> <span m='60817'>hit</span>
  <span m='61095'>and</span> <span m='61374'>miss</span> <span m='61652'>ratios</span>
  <span m='61930'>tell</span> <span m='62209'>us</span> <span m='62487'>the</span>
  <span m='62766'>fraction</span> <span m='63044'>of</span> <span m='63322'>accesses</span>
  <span m='63601'>which</span> <span m='63879'>are</span> <span m='64158'>cache</span>
  <span m='64436'>hits</span> <span m='64714'>and</span> <span m='64993'>the</span>
  <span m='65271'>fraction</span> <span m='65550'>of</span> <span m='65915'>accesses</span>
  <span m='66280'>which</span> <span m='66645'>are</span> <span m='67010'>cache</span>
  <span m='67375'>misses.</span> </p><p><span m='67740'>Of</span> <span m='68285'>course,</span>
  <span m='68830'>the</span> <span m='69375'>ratios</span> <span m='69920'>will</span>
  <span m='70465'>sum</span> <span m='71010'>to</span> <span m='71555'>1.</span> </p><p><span
  m='72100'>Using</span> <span m='72414'>these</span> <span m='72728'>metrics</span>
  <span m='73042'>we</span> <span m='73356'>can</span> <span m='73670'>compute</span>
  <span m='73984'>the</span> <span m='74298'>average</span> <span m='74612'>memory</span>
  <span m='74926'>access</span> <span m='75240'>time</span> <span m='75554'>(AMAT).</span>
  </p><p><span m='75869'>Since</span> <span m='76153'>we</span> <span m='76438'>always</span>
  <span m='76723'>check</span> <span m='77007'>in</span> <span m='77292'>the</span>
  <span m='77577'>cache</span> <span m='77862'>first,</span> <span m='78146'>every</span>
  <span m='78431'>access</span> <span m='78716'>includes</span> <span m='79001'>the</span>
  <span m='79285'>cache</span> <span m='79570'>access</span> <span m='79855'>time</span>
  <span m='80140'>(called</span> <span m='80567'>the</span> <span m='80995'>hit</span>
  <span m='81422'>time).</span> </p><p><span m='81850'>If</span> <span m='82122'>we</span>
  <span m='82394'>miss</span> <span m='82666'>in</span> <span m='82938'>the</span>
  <span m='83211'>cache,</span> <span m='83483'>we</span> <span m='83755'>have</span>
  <span m='84027'>to</span> <span m='84300'>take</span> <span m='84572'>the</span>
  <span m='84844'>additional</span> <span m='85116'>time</span> <span m='85388'>needed</span>
  <span m='85661'>to</span> <span m='85933'>access</span> <span m='86205'>main</span>
  <span m='86477'>memory</span> <span m='86750'>(called</span> <span m='87362'>the</span>
  <span m='87975'>miss</span> <span m='88587'>penalty).</span> </p><p><span m='89200'>But</span>
  <span m='89503'>the</span> <span m='89806'>main</span> <span m='90109'>memory</span>
  <span m='90412'>access</span> <span m='90715'>only</span> <span m='91018'>happens</span>
  <span m='91321'>on</span> <span m='91624'>some</span> <span m='91927'>fraction</span>
  <span m='92230'>of</span> <span m='92533'>the</span> <span m='92836'>accesses:</span>
  <span m='93139'>the</span> <span m='93442'>miss</span> <span m='93745'>ratio</span>
  <span m='94049'>tells</span> <span m='94580'>us</span> <span m='95112'>how</span>
  <span m='95644'>often</span> <span m='96176'>that</span> <span m='96708'>occurs.</span>
  </p><p><span m='97240'>So</span> <span m='97742'>the</span> <span m='98245'>AMAT</span>
  <span m='98748'>can</span> <span m='99250'>be</span> <span m='99753'>computed</span>
  <span m='100256'>using</span> <span m='100759'>the</span> <span m='101261'>formula</span>
  <span m='101764'>shown</span> <span m='102267'>here.</span> </p><p><span m='102770'>The</span>
  <span m='103104'>lower</span> <span m='103438'>the</span> <span m='103772'>miss</span>
  <span m='104106'>ratio</span> <span m='104440'>(or,</span> <span m='104774'>equivalently,</span>
  <span m='105108'>the</span> <span m='105442'>higher</span> <span m='105776'>the</span>
  <span m='106110'>hit</span> <span m='106444'>ratio),</span> <span m='106778'>the</span>
  <span m='107112'>smaller</span> <span m='107446'>the</span> <span m='107780'>average</span>
  <span m='108489'>access</span> <span m='109198'>time.</span> </p><p><span m='109908'>Our</span>
  <span m='110234'>design</span> <span m='110561'>goal</span> <span m='110888'>for</span>
  <span m='111215'>the</span> <span m='111542'>cache</span> <span m='111869'>is</span>
  <span m='112196'>to</span> <span m='112523'>achieve</span> <span m='112850'>a</span>
  <span m='113177'>high</span> <span m='113504'>hit</span> <span m='113831'>ratio.</span>
  </p><p><span m='114158'>If</span> <span m='114442'>we</span> <span m='114726'>have</span>
  <span m='115010'>multiple</span> <span m='115294'>levels</span> <span m='115578'>of</span>
  <span m='115862'>cache,</span> <span m='116146'>we</span> <span m='116431'>can</span>
  <span m='116715'>apply</span> <span m='116999'>the</span> <span m='117283'>formula</span>
  <span m='117567'>recursively</span> <span m='117851'>to</span> <span m='118135'>calculate</span>
  <span m='118420'>the</span> <span m='118995'>AMAT</span> <span m='119570'>at</span>
  <span m='120145'>each</span> <span m='120720'>level</span> <span m='121295'>of</span>
  <span m='121870'>the</span> <span m='122445'>memory.</span> </p><p><span m='123020'>Each</span>
  <span m='123386'>successive</span> <span m='123752'>level</span> <span m='124119'>of</span>
  <span m='124485'>the</span> <span m='124852'>cache</span> <span m='125218'>is</span>
  <span m='125585'>slower,</span> <span m='125951'>i.e.,</span> <span m='126318'>has</span>
  <span m='126684'>a</span> <span m='127051'>longer</span> <span m='127417'>hit</span>
  <span m='127784'>time,</span> <span m='128150'>which</span> <span m='128517'>is</span>
  <span m='128883'>offset</span> <span m='129250'>by</span> <span m='129780'>lower</span>
  <span m='130310'>miss</span> <span m='130840'>ratio</span> <span m='131370'>because</span>
  <span m='131900'>of</span> <span m='132430'>its</span> <span m='132960'>increased</span>
  <span m='133490'>size.</span> </p><p><span m='134020'>Let's</span> <span m='134370'>try</span>
  <span m='134720'>out</span> <span m='135070'>some</span> <span m='135420'>numbers.</span>
  </p><p><span m='135770'>Suppose</span> <span m='136190'>the</span> <span m='136611'>cache</span>
  <span m='137031'>takes</span> <span m='137452'>4</span> <span m='137873'>processor</span>
  <span m='138293'>cycles</span> <span m='138714'>to</span> <span m='139134'>respond,</span>
  <span m='139555'>and</span> <span m='139976'>main</span> <span m='140396'>memory</span>
  <span m='140817'>takes</span> <span m='141237'>100</span> <span m='141658'>cycles.</span>
  </p><p><span m='142079'>Without</span> <span m='142518'>the</span> <span m='142957'>cache,</span>
  <span m='143396'>each</span> <span m='143835'>memory</span> <span m='144274'>access</span>
  <span m='144713'>would</span> <span m='145152'>take</span> <span m='145591'>100</span>
  <span m='146030'>cycles.</span> </p><p><span m='146470'>With</span> <span m='146932'>the</span>
  <span m='147395'>cache,</span> <span m='147857'>a</span> <span m='148320'>cache</span>
  <span m='148782'>hit</span> <span m='149245'>takes</span> <span m='149707'>4</span>
  <span m='150170'>cycles,</span> <span m='150632'>and</span> <span m='151095'>a</span>
  <span m='151557'>cache</span> <span m='152020'>miss</span> <span m='152482'>takes</span>
  <span m='152945'>104</span> <span m='153407'>cycles.</span> </p><p><span m='153870'>What</span>
  <span m='154262'>hit</span> <span m='154655'>ratio</span> <span m='155048'>is</span>
  <span m='155441'>needed</span> <span m='155833'>to</span> <span m='156226'>so</span>
  <span m='156619'>that</span> <span m='157012'>the</span> <span m='157405'>AMAT</span>
  <span m='157797'>with</span> <span m='158190'>the</span> <span m='158583'>cache</span>
  <span m='158976'>is</span> <span m='159368'>100</span> <span m='159761'>cycles,</span>
  <span m='160154'>the</span> <span m='160547'>break-even</span> <span m='160940'>point?</span>
  </p><p><span m='163050'>Using</span> <span m='163362'>the</span> <span m='163675'>AMAT</span>
  <span m='163988'>formula</span> <span m='164301'>from</span> <span m='164614'>the</span>
  <span m='164927'>previously</span> <span m='165240'>slide,</span> <span m='165553'>we</span>
  <span m='165866'>see</span> <span m='166179'>that</span> <span m='166492'>we</span>
  <span m='166805'>only</span> <span m='167118'>need</span> <span m='167431'>a</span>
  <span m='167744'>hit</span> <span m='168057'>ratio</span> <span m='168370'>of</span>
  <span m='168692'>4%</span> <span m='169014'>in</span> <span m='169336'>order</span>
  <span m='169658'>for</span> <span m='169980'>memory</span> <span m='170302'>system</span>
  <span m='170624'>of</span> <span m='170946'>the</span> <span m='171268'>Cache</span>
  <span m='171590'>+</span> <span m='171912'>Main</span> <span m='172234'>Memory</span>
  <span m='172556'>to</span> <span m='172878'>perform</span> <span m='173200'>as</span>
  <span m='173522'>well</span> <span m='173844'>as</span> <span m='174166'>Main</span>
  <span m='174488'>Memory</span> <span m='174810'>alone.</span> </p><p><span m='176310'>The</span>
  <span m='176618'>idea,</span> <span m='176927'>of</span> <span m='177236'>course,</span>
  <span m='177544'>is</span> <span m='177853'>that</span> <span m='178162'>we'll</span>
  <span m='178470'>be</span> <span m='178779'>able</span> <span m='179088'>to</span>
  <span m='179396'>do</span> <span m='179705'>much</span> <span m='180014'>better</span>
  <span m='180322'>than</span> <span m='180631'>that.</span> </p><p><span m='180940'>Suppose</span>
  <span m='181553'>we</span> <span m='182167'>wanted</span> <span m='182781'>an</span>
  <span m='183395'>AMAT</span> <span m='184008'>of</span> <span m='184622'>5</span>
  <span m='185236'>cycles.</span> </p><p><span m='185850'>Clearly</span> <span m='186202'>most</span>
  <span m='186555'>of</span> <span m='186908'>the</span> <span m='187260'>accesses</span>
  <span m='187613'>would</span> <span m='187966'>have</span> <span m='188319'>to</span>
  <span m='188671'>be</span> <span m='189024'>cache</span> <span m='189377'>hits.</span>
  </p><p><span m='189730'>We</span> <span m='190197'>can</span> <span m='190665'>use</span>
  <span m='191132'>the</span> <span m='191600'>AMAT</span> <span m='192067'>formula</span>
  <span m='192535'>to</span> <span m='193002'>compute</span> <span m='193470'>the</span>
  <span m='193937'>necessary</span> <span m='194405'>hit</span> <span m='194872'>ratio.</span>
  </p><p><span m='195340'>Working</span> <span m='195642'>through</span> <span m='195945'>the</span>
  <span m='196247'>arithmetic</span> <span m='196550'>we</span> <span m='196852'>see</span>
  <span m='197155'>that</span> <span m='197457'>99%</span> <span m='197760'>of</span>
  <span m='198062'>the</span> <span m='198365'>accesses</span> <span m='198667'>must</span>
  <span m='198970'>be</span> <span m='199272'>cache</span> <span m='199575'>hits</span>
  <span m='199877'>in</span> <span m='200180'>order</span> <span m='200665'>to</span>
  <span m='201150'>achieve</span> <span m='201635'>an</span> <span m='202120'>average</span>
  <span m='202605'>access</span> <span m='203090'>time</span> <span m='203575'>of</span>
  <span m='204060'>5</span> <span m='204545'>cycles.</span> </p><p><span m='205030'>Could</span>
  <span m='205376'>we</span> <span m='205722'>expect</span> <span m='206069'>to</span>
  <span m='206415'>do</span> <span m='206761'>that</span> <span m='207108'>well</span>
  <span m='207454'>when</span> <span m='207800'>running</span> <span m='208147'>actual</span>
  <span m='208493'>programs?</span> </p><p><span m='208840'>Happily,</span> <span
  m='209356'>we</span> <span m='209872'>can</span> <span m='210388'>come</span> <span
  m='210904'>close.</span> </p><p><span m='211420'>In</span> <span m='211835'>a</span>
  <span m='212250'>simulation</span> <span m='212665'>of</span> <span m='213080'>the</span>
  <span m='213495'>Spec</span> <span m='213910'>CPU2000</span> <span m='214325'>Benchmark,</span>
  <span m='214740'>the</span> <span m='215155'>hit</span> <span m='215570'>ratio</span>
  <span m='215985'>for</span> <span m='216400'>a</span> <span m='216815'>standard-size</span>
  <span m='217230'>level</span> <span m='217645'>1</span> <span m='218060'>cache</span>
  <span m='218551'>was</span> <span m='219043'>measured</span> <span m='219535'>to</span>
  <span m='220027'>be</span> <span m='220519'>97.5%</span> <span m='221010'>over</span>
  <span m='221502'>some</span> <span m='221994'>~10</span> <span m='222486'>trillion</span>
  <span m='222978'>accesses.</span> </p><p><span m='223470'>[See</span> <span m='223627'>the</span>
  <span m='223785'>"All</span> <span m='223942'>benchmarks"</span> <span m='224100'>arithmetic-mean</span>
  <span m='224257'>table</span> <span m='224415'>at</span> <span m='224572'>http://research.cs.wisc.edu/multifacet/misc/spec2000cache-data/]</span>
  <span m='224730'>Here's</span> <span m='225035'>a</span> <span m='225341'>start</span>
  <span m='225647'>at</span> <span m='225952'>building</span> <span m='226258'>a</span>
  <span m='226564'>cache.</span> </p><p><span m='226870'>The</span> <span m='227260'>cache</span>
  <span m='227650'>will</span> <span m='228040'>hold</span> <span m='228430'>many</span>
  <span m='228820'>different</span> <span m='229210'>blocks</span> <span m='229600'>of</span>
  <span m='229990'>data.</span> </p><p><span m='230380'>For</span> <span m='230772'>now</span>
  <span m='231165'>let's</span> <span m='231558'>assume</span> <span m='231950'>each</span>
  <span m='232343'>block</span> <span m='232736'>is</span> <span m='233129'>an</span>
  <span m='233521'>individual</span> <span m='233914'>memory</span> <span m='234307'>location.</span>
  </p><p><span m='234700'>Each</span> <span m='235113'>data</span> <span m='235527'>block</span>
  <span m='235941'>is</span> <span m='236355'>"tagged"</span> <span m='236768'>with</span>
  <span m='237182'>its</span> <span m='237596'>address.</span> </p><p><span m='238010'>A</span>
  <span m='238417'>combination</span> <span m='238825'>of</span> <span m='239232'>a</span>
  <span m='239640'>data</span> <span m='240047'>block</span> <span m='240455'>and</span>
  <span m='240862'>its</span> <span m='241270'>associated</span> <span m='241677'>address</span>
  <span m='242085'>tag</span> <span m='242492'>is</span> <span m='242900'>called</span>
  <span m='243307'>a</span> <span m='243715'>cache</span> <span m='244122'>line.</span>
  </p><p><span m='244530'>When</span> <span m='244839'>an</span> <span m='245148'>address</span>
  <span m='245458'>is</span> <span m='245767'>received</span> <span m='246076'>from</span>
  <span m='246386'>the</span> <span m='246695'>CPU,</span> <span m='247005'>we'll</span>
  <span m='247314'>search</span> <span m='247623'>the</span> <span m='247933'>cache</span>
  <span m='248242'>looking</span> <span m='248551'>for</span> <span m='248861'>a</span>
  <span m='249170'>block</span> <span m='249480'>with</span> <span m='250030'>a</span>
  <span m='250580'>matching</span> <span m='251130'>address</span> <span m='251680'>tag.</span>
  </p><p><span m='252230'>If</span> <span m='252583'>we</span> <span m='252936'>find</span>
  <span m='253290'>a</span> <span m='253643'>matching</span> <span m='253996'>address</span>
  <span m='254350'>tag,</span> <span m='254703'>we</span> <span m='255056'>have</span>
  <span m='255410'>a</span> <span m='255763'>cache</span> <span m='256116'>hit.</span>
  </p><p><span m='256470'>On</span> <span m='256781'>a</span> <span m='257092'>read</span>
  <span m='257404'>access,</span> <span m='257715'>we'll</span> <span m='258027'>return</span>
  <span m='258338'>the</span> <span m='258650'>data</span> <span m='258961'>from</span>
  <span m='259273'>the</span> <span m='259584'>matching</span> <span m='259896'>cache</span>
  <span m='260207'>line.</span> </p><p><span m='260519'>On</span> <span m='260811'>a</span>
  <span m='261104'>write</span> <span m='261397'>access,</span> <span m='261690'>we'll</span>
  <span m='261983'>update</span> <span m='262276'>the</span> <span m='262569'>data</span>
  <span m='262862'>stored</span> <span m='263155'>in</span> <span m='263447'>the</span>
  <span m='263740'>cache</span> <span m='264033'>line</span> <span m='264326'>and,</span>
  <span m='264619'>at</span> <span m='264912'>some</span> <span m='265205'>point,</span>
  <span m='265498'>update</span> <span m='265791'>the</span> <span m='266472'>corresponding</span>
  <span m='267153'>location</span> <span m='267835'>in</span> <span m='268516'>main</span>
  <span m='269197'>memory.</span> </p><p><span m='269879'>If</span> <span m='270267'>no</span>
  <span m='270655'>matching</span> <span m='271043'>tag</span> <span m='271432'>is</span>
  <span m='271820'>found,</span> <span m='272208'>we</span> <span m='272596'>have</span>
  <span m='272985'>a</span> <span m='273373'>cache</span> <span m='273761'>miss.</span>
  </p><p><span m='274150'>So</span> <span m='274398'>we'll</span> <span m='274647'>have</span>
  <span m='274896'>to</span> <span m='275145'>choose</span> <span m='275394'>a</span>
  <span m='275643'>cache</span> <span m='275892'>line</span> <span m='276141'>to</span>
  <span m='276390'>use</span> <span m='276638'>to</span> <span m='276887'>hold</span>
  <span m='277136'>the</span> <span m='277385'>requested</span> <span m='277634'>data,</span>
  <span m='277883'>which</span> <span m='278132'>means</span> <span m='278381'>that</span>
  <span m='278630'>some</span> <span m='279124'>previously</span> <span m='279619'>cached</span>
  <span m='280114'>location</span> <span m='280609'>will</span> <span m='281104'>no</span>
  <span m='281599'>longer</span> <span m='282094'>be</span> <span m='282589'>found</span>
  <span m='283084'>in</span> <span m='283579'>the</span> <span m='284074'>cache.</span>
  </p><p><span m='284569'>For</span> <span m='284866'>a</span> <span m='285164'>read</span>
  <span m='285461'>operation,</span> <span m='285759'>we'll</span> <span m='286057'>fetch</span>
  <span m='286354'>the</span> <span m='286652'>requested</span> <span m='286950'>data</span>
  <span m='287247'>from</span> <span m='287545'>main</span> <span m='287843'>memory,</span>
  <span m='288140'>add</span> <span m='288438'>it</span> <span m='288736'>to</span>
  <span m='289033'>the</span> <span m='289331'>cache</span> <span m='289629'>(updating</span>
  <span m='289934'>the</span> <span m='290240'>tag</span> <span m='290545'>and</span>
  <span m='290851'>data</span> <span m='291157'>fields</span> <span m='291462'>of</span>
  <span m='291768'>the</span> <span m='292073'>cache</span> <span m='292379'>line)</span>
  <span m='292685'>and,</span> <span m='292990'>of</span> <span m='293296'>course,</span>
  <span m='293601'>return</span> <span m='293907'>the</span> <span m='294213'>data</span>
  <span m='294518'>to</span> <span m='294824'>the</span> <span m='295130'>CPU.</span>
  </p><p><span m='297000'>On</span> <span m='297298'>a</span> <span m='297597'>write,</span>
  <span m='297896'>we'll</span> <span m='298195'>update</span> <span m='298494'>the</span>
  <span m='298793'>tag</span> <span m='299091'>and</span> <span m='299390'>data</span>
  <span m='299689'>in</span> <span m='299988'>the</span> <span m='300287'>selected</span>
  <span m='300586'>cache</span> <span m='300884'>line</span> <span m='301183'>and,</span>
  <span m='301482'>at</span> <span m='301781'>some</span> <span m='302080'>point,</span>
  <span m='302379'>update</span> <span m='302860'>the</span> <span m='303341'>corresponding</span>
  <span m='303823'>location</span> <span m='304304'>in</span> <span m='304786'>main</span>
  <span m='305267'>memory.</span> </p><p><span m='305749'>So</span> <span m='306094'>the</span>
  <span m='306440'>contents</span> <span m='306786'>of</span> <span m='307131'>the</span>
  <span m='307477'>cache</span> <span m='307823'>is</span> <span m='308168'>determined</span>
  <span m='308514'>by</span> <span m='308860'>the</span> <span m='309205'>memory</span>
  <span m='309551'>requests</span> <span m='309897'>made</span> <span m='310242'>by</span>
  <span m='310588'>the</span> <span m='310934'>CPU.</span> </p><p><span m='311280'>If</span>
  <span m='311643'>the</span> <span m='312006'>CPU</span> <span m='312369'>requests</span>
  <span m='312732'>a</span> <span m='313095'>recently-used</span> <span m='313458'>address,</span>
  <span m='313821'>chances</span> <span m='314185'>are</span> <span m='314548'>good</span>
  <span m='314911'>the</span> <span m='315274'>data</span> <span m='315637'>will</span>
  <span m='316000'>still</span> <span m='316363'>be</span> <span m='316726'>in</span>
  <span m='317090'>the</span> <span m='317556'>cache</span> <span m='318023'>from</span>
  <span m='318490'>the</span> <span m='318957'>previous</span> <span m='319424'>access</span>
  <span m='319891'>to</span> <span m='320358'>the</span> <span m='320825'>same</span>
  <span m='321292'>location.</span> </p><p><span m='321759'>As</span> <span m='322171'>the</span>
  <span m='322584'>working</span> <span m='322997'>set</span> <span m='323410'>slowly</span>
  <span m='323823'>changes,</span> <span m='324236'>the</span> <span m='324649'>cache</span>
  <span m='325061'>contents</span> <span m='325474'>will</span> <span m='325887'>be</span>
  <span m='326300'>updated</span> <span m='326713'>as</span> <span m='327126'>needed.</span>
  </p><p><span m='327539'>If</span> <span m='327842'>the</span> <span m='328145'>entire</span>
  <span m='328449'>working</span> <span m='328752'>set</span> <span m='329055'>can</span>
  <span m='329359'>fit</span> <span m='329662'>into</span> <span m='329965'>the</span>
  <span m='330269'>cache,</span> <span m='330572'>most</span> <span m='330875'>of</span>
  <span m='331179'>the</span> <span m='331482'>requests</span> <span m='331785'>will</span>
  <span m='332089'>be</span> <span m='332392'>hits</span> <span m='332695'>and</span>
  <span m='332999'>the</span> <span m='333463'>AMAT</span> <span m='333927'>will</span>
  <span m='334391'>be</span> <span m='334855'>close</span> <span m='335319'>to</span>
  <span m='335783'>the</span> <span m='336247'>cache</span> <span m='336711'>access</span>
  <span m='337175'>time.</span> </p><p><span m='337639'>So</span> <span m='338351'>far,</span>
  <span m='339064'>so</span> <span m='339777'>good!</span> </p><p><span m='340490'>Of</span>
  <span m='340825'>course,</span> <span m='341160'>we'll</span> <span m='341495'>need</span>
  <span m='341830'>to</span> <span m='342166'>figure</span> <span m='342501'>how</span>
  <span m='342836'>to</span> <span m='343171'>quickly</span> <span m='343507'>search</span>
  <span m='343842'>the</span> <span m='344177'>cache,</span> <span m='344512'>i.e.,</span>
  <span m='344848'>we'll</span> <span m='345183'>a</span> <span m='345518'>need</span>
  <span m='345853'>fast</span> <span m='346189'>way</span> <span m='346534'>to</span>
  <span m='346880'>answer</span> <span m='347225'>the</span> <span m='347571'>question</span>
  <span m='347916'>of</span> <span m='348262'>whether</span> <span m='348607'>a</span>
  <span m='348953'>particular</span> <span m='349299'>address</span> <span m='349644'>tag</span>
  <span m='349990'>can</span> <span m='350335'>be</span> <span m='350681'>found</span>
  <span m='351026'>in</span> <span m='351372'>some</span> <span m='351717'>cache</span>
  <span m='352063'>line.</span> </p><p><span m='352409'>That's</span> <span m='352679'>our</span>
  <span m='352949'>next</span> <span m='353219'>topic.</span> </p>
type: course
uid: bd374d9d7e02e9684951e23c051ec3ba

---
None