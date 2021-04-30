---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: wPwWtFMkxLo
  parent_uid: 2ffa1ad80a8a4ec1625ba9e1e848a7e0
  title: Video-YouTube-Stream
  type: Video
  uid: 63309064a77e35bcb75c18adc26fc5cf
- id: 3Play-3Play YouTube id-Stream
  media_location: wPwWtFMkxLo
  parent_uid: 2ffa1ad80a8a4ec1625ba9e1e848a7e0
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: ffa3304b8caa3289fe4d3bd5132afc4b
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/wPwWtFMkxLo/default.jpg
  parent_uid: 2ffa1ad80a8a4ec1625ba9e1e848a7e0
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: cca1cb437a68e28651b9c96df8347925
- id: wPwWtFMkxLo.srt
  parent_uid: 2ffa1ad80a8a4ec1625ba9e1e848a7e0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v7/variable-length-encoding-3-40-/wPwWtFMkxLo.srt
  title: 3play caption file
  type: null
  uid: 6167e9743eed6419f5688fc5a7342c6a
- id: wPwWtFMkxLo.pdf
  parent_uid: 2ffa1ad80a8a4ec1625ba9e1e848a7e0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v7/variable-length-encoding-3-40-/wPwWtFMkxLo.pdf
  title: 3play pdf file
  type: null
  uid: 13a1aae555502bb21d8ff28b1e0eae06
- id: Caption-3Play YouTube id-SRT
  parent_uid: 2ffa1ad80a8a4ec1625ba9e1e848a7e0
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: a02c06be5107ea1addc39069476013ae
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 2ffa1ad80a8a4ec1625ba9e1e848a7e0
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 1c21453f0cc206c712085706edbeae18
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_01-02-07_300k.mp4
  parent_uid: 2ffa1ad80a8a4ec1625ba9e1e848a7e0
  title: Video-Internet Archive-MP4
  type: Video
  uid: 9a5021f1df00d64522901fa2f3017e82
inline_embed_id: 77850139variablelengthencoding34094832250
layout: video
order_index: null
parent_uid: 02f114a4839df45db96af4472b4b7d2f
related_resources_text: ''
short_url: variable-length-encoding-3-40-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v7/variable-length-encoding-3-40-
template_type: Embed
title: Variable-length Encoding (3:40)
transcript: <p><span m='979'>Fixed-length</span> <span m='1319'>encodings</span> <span
  m='1659'>work</span> <span m='1999'>well</span> <span m='2339'>when</span> <span
  m='2679'>all</span> <span m='3019'>the</span> <span m='3359'>possible</span> <span
  m='3699'>choices</span> <span m='4039'>have</span> <span m='4379'>the</span> <span
  m='4719'>same</span> <span m='5059'>information</span> <span m='5400'>content,</span>
  <span m='5858'>i.e.,</span> <span m='6316'>all</span> <span m='6774'>the</span>
  <span m='7232'>choices</span> <span m='7690'>have</span> <span m='8149'>an</span>
  <span m='8607'>equal</span> <span m='9065'>probability</span> <span m='9523'>of</span>
  <span m='9981'>occurring.</span> </p><p><span m='10440'>If</span> <span m='10768'>those</span>
  <span m='11096'>choices</span> <span m='11425'>don't</span> <span m='11753'>have</span>
  <span m='12081'>the</span> <span m='12410'>same</span> <span m='12738'>information</span>
  <span m='13067'>content,</span> <span m='13395'>we</span> <span m='13723'>can</span>
  <span m='14052'>do</span> <span m='14380'>better.</span> </p><p><span m='14709'>To</span>
  <span m='15056'>see</span> <span m='15403'>how,</span> <span m='15750'>consider</span>
  <span m='16097'>the</span> <span m='16445'>expected</span> <span m='16792'>length</span>
  <span m='17139'>of</span> <span m='17486'>an</span> <span m='17833'>encoding,</span>
  <span m='18181'>computed</span> <span m='18528'>by</span> <span m='18875'>considering</span>
  <span m='19222'>each</span> <span m='19570'>x_i</span> <span m='19938'>to</span>
  <span m='20306'>be</span> <span m='20674'>encoded,</span> <span m='21042'>and</span>
  <span m='21410'>weighting</span> <span m='21778'>the</span> <span m='22146'>length</span>
  <span m='22515'>of</span> <span m='22883'>its</span> <span m='23251'>encoding</span>
  <span m='23619'>by</span> <span m='23987'>p_i,</span> <span m='24355'>the</span>
  <span m='24723'>probability</span> <span m='25091'>of</span> <span m='25460'>its</span>
  <span m='26350'>occurrence.</span> </p><p><span m='27240'>By</span> <span m='27540'>"doing</span>
  <span m='27840'>better"</span> <span m='28140'>we</span> <span m='28440'>mean</span>
  <span m='28740'>that</span> <span m='29040'>we</span> <span m='29340'>can</span>
  <span m='29640'>find</span> <span m='29940'>encodings</span> <span m='30240'>that</span>
  <span m='30540'>have</span> <span m='30840'>a</span> <span m='31140'>shorter</span>
  <span m='31440'>expected</span> <span m='31740'>length</span> <span m='32040'>than</span>
  <span m='32530'>a</span> <span m='33020'>fixed-length</span> <span m='33510'>encoding.</span>
  </p><p><span m='34000'>Ideally</span> <span m='34311'>we'd</span> <span m='34622'>like</span>
  <span m='34933'>the</span> <span m='35245'>expected</span> <span m='35556'>length</span>
  <span m='35867'>of</span> <span m='36178'>the</span> <span m='36490'>encoding</span>
  <span m='36801'>for</span> <span m='37112'>the</span> <span m='37423'>x_i</span>
  <span m='37735'>to</span> <span m='38046'>match</span> <span m='38357'>the</span>
  <span m='38668'>entropy</span> <span m='38980'>H(X),</span> <span m='39847'>which</span>
  <span m='40714'>is</span> <span m='41581'>the</span> <span m='42448'>expected</span>
  <span m='43315'>information</span> <span m='44182'>content.</span> </p><p><span
  m='45050'>We</span> <span m='45417'>know</span> <span m='45785'>that</span> <span
  m='46153'>if</span> <span m='46521'>x_i</span> <span m='46888'>has</span> <span
  m='47256'>a</span> <span m='47624'>higher</span> <span m='47992'>probability</span>
  <span m='48360'>(i.e.,</span> <span m='48727'>a</span> <span m='49095'>larger</span>
  <span m='49463'>p_i),</span> <span m='49831'>that</span> <span m='50198'>is</span>
  <span m='50566'>has</span> <span m='50934'>a</span> <span m='51302'>smaller</span>
  <span m='51670'>information</span> <span m='52105'>content,</span> <span m='52541'>so</span>
  <span m='52976'>we'd</span> <span m='53412'>like</span> <span m='53847'>to</span>
  <span m='54283'>use</span> <span m='54718'>shorter</span> <span m='55154'>encodings.</span>
  </p><p><span m='55590'>If</span> <span m='56073'>x_i</span> <span m='56556'>has</span>
  <span m='57040'>a</span> <span m='57523'>lower</span> <span m='58006'>probability,</span>
  <span m='58490'>then</span> <span m='58973'>we'd</span> <span m='59456'>use</span>
  <span m='59940'>a</span> <span m='60423'>longer</span> <span m='60906'>encoding.</span>
  </p><p><span m='61390'>So</span> <span m='61734'>we'll</span> <span m='62078'>be</span>
  <span m='62422'>constructing</span> <span m='62766'>encodings</span> <span m='63110'>where</span>
  <span m='63454'>the</span> <span m='63798'>x_i</span> <span m='64142'>may</span>
  <span m='64486'>have</span> <span m='64830'>different</span> <span m='65174'>length</span>
  <span m='65518'>codes</span> <span m='65862'>-</span> <span m='66206'>we'll</span>
  <span m='66550'>call</span> <span m='67582'>these</span> <span m='68615'>variable-length</span>
  <span m='69647'>encodings.</span> </p><p><span m='70680'>Here's</span> <span m='70981'>an</span>
  <span m='71283'>example</span> <span m='71585'>we've</span> <span m='71886'>seen</span>
  <span m='72188'>before.</span> </p><p><span m='72490'>There</span> <span m='72851'>are</span>
  <span m='73212'>four</span> <span m='73573'>possible</span> <span m='73935'>choices</span>
  <span m='74296'>to</span> <span m='74657'>encode</span> <span m='75018'>(A,</span>
  <span m='75380'>B,</span> <span m='75741'>C,</span> <span m='76102'>and</span> <span
  m='76463'>D),</span> <span m='76825'>each</span> <span m='77186'>with</span> <span
  m='77547'>the</span> <span m='77908'>specified</span> <span m='78270'>probability.</span>
  </p><p><span m='79660'>The</span> <span m='79937'>table</span> <span m='80214'>shows</span>
  <span m='80491'>a</span> <span m='80768'>suggested</span> <span m='81045'>encoding</span>
  <span m='81322'>where</span> <span m='81599'>we've</span> <span m='81876'>followed</span>
  <span m='82153'>the</span> <span m='82430'>advice</span> <span m='82707'>from</span>
  <span m='82984'>the</span> <span m='83261'>previous</span> <span m='83539'>slide:</span>
  <span m='84054'>high-probability</span> <span m='84569'>choices</span> <span m='85084'>that</span>
  <span m='85599'>convey</span> <span m='86114'>little</span> <span m='86629'>information</span>
  <span m='87144'>(e.g.,</span> <span m='87659'>B)</span> <span m='88174'>are</span>
  <span m='88689'>given</span> <span m='89204'>shorter</span> <span m='89720'>encodings,</span>
  <span m='90076'>while</span> <span m='90433'>low-probability</span> <span m='90790'>choices</span>
  <span m='91146'>that</span> <span m='91503'>convey</span> <span m='91860'>more</span>
  <span m='92363'>information</span> <span m='92866'>(e.g.,</span> <span m='93369'>C</span>
  <span m='93872'>or</span> <span m='94375'>D)</span> <span m='94878'>are</span> <span
  m='95381'>given</span> <span m='95884'>longer</span> <span m='96387'>encodings.</span>
  </p><p><span m='96890'>Let's</span> <span m='97270'>diagram</span> <span m='97650'>this</span>
  <span m='98030'>encoding</span> <span m='98410'>as</span> <span m='98790'>a</span>
  <span m='99170'>binary</span> <span m='99550'>tree.</span> </p><p><span m='99930'>Since</span>
  <span m='100162'>the</span> <span m='100394'>symbols</span> <span m='100627'>all</span>
  <span m='100859'>appear</span> <span m='101091'>as</span> <span m='101324'>the</span>
  <span m='101556'>leaves</span> <span m='101788'>of</span> <span m='102021'>the</span>
  <span m='102253'>tree,</span> <span m='102485'>we</span> <span m='102718'>can</span>
  <span m='102950'>see</span> <span m='103182'>that</span> <span m='103415'>the</span>
  <span m='103647'>encoding</span> <span m='103880'>is</span> <span m='104834'>unambiguous.</span>
  </p><p><span m='105789'>Let's</span> <span m='106224'>try</span> <span m='106660'>decoding</span>
  <span m='107096'>the</span> <span m='107532'>following</span> <span m='107968'>encoded</span>
  <span m='108404'>data.</span> </p><p><span m='108840'>We'll</span> <span m='109103'>use</span>
  <span m='109366'>the</span> <span m='109629'>tree</span> <span m='109892'>as</span>
  <span m='110155'>follows:</span> <span m='110418'>start</span> <span m='110682'>at</span>
  <span m='110945'>the</span> <span m='111208'>root</span> <span m='111471'>of</span>
  <span m='111734'>the</span> <span m='111997'>tree</span> <span m='112261'>and</span>
  <span m='112524'>use</span> <span m='112787'>bits</span> <span m='113050'>from</span>
  <span m='113313'>the</span> <span m='113576'>encoded</span> <span m='113840'>data</span>
  <span m='114224'>to</span> <span m='114609'>traverse</span> <span m='114993'>the</span>
  <span m='115378'>tree</span> <span m='115763'>as</span> <span m='116147'>directed,</span>
  <span m='116532'>stopping</span> <span m='116916'>when</span> <span m='117301'>we</span>
  <span m='117686'>reach</span> <span m='118070'>a</span> <span m='118455'>leaf.</span>
  </p><p><span m='118840'>Starting</span> <span m='119080'>at</span> <span m='119320'>the</span>
  <span m='119560'>root,</span> <span m='119800'>the</span> <span m='120040'>first</span>
  <span m='120280'>encoded</span> <span m='120520'>bit</span> <span m='120760'>is</span>
  <span m='121000'>0,</span> <span m='121240'>which</span> <span m='121480'>takes</span>
  <span m='121720'>us</span> <span m='121960'>down</span> <span m='122200'>the</span>
  <span m='122440'>left</span> <span m='122680'>branch</span> <span m='122920'>to</span>
  <span m='123275'>the</span> <span m='123630'>leaf</span> <span m='123985'>B.</span>
  <span m='124340'>So</span> <span m='124695'>B</span> <span m='125050'>is</span>
  <span m='125405'>the</span> <span m='125760'>first</span> <span m='126115'>symbol</span>
  <span m='126470'>of</span> <span m='126825'>the</span> <span m='127180'>decoded</span>
  <span m='127535'>data.</span> </p><p><span m='127890'>Starting</span> <span m='128174'>at</span>
  <span m='128458'>the</span> <span m='128743'>root</span> <span m='129027'>again,</span>
  <span m='129312'>1</span> <span m='129596'>takes</span> <span m='129881'>us</span>
  <span m='130165'>down</span> <span m='130450'>the</span> <span m='130734'>right</span>
  <span m='131018'>branch,</span> <span m='131303'>0</span> <span m='131587'>the</span>
  <span m='131872'>left</span> <span m='132156'>branch</span> <span m='132441'>from</span>
  <span m='132725'>there,</span> <span m='133010'>and</span> <span m='133327'>0</span>
  <span m='133644'>the</span> <span m='133961'>left</span> <span m='134278'>branch</span>
  <span m='134595'>below</span> <span m='134913'>that,</span> <span m='135230'>arriving</span>
  <span m='135547'>at</span> <span m='135864'>the</span> <span m='136181'>leaf</span>
  <span m='136498'>C,</span> <span m='136816'>the</span> <span m='137133'>second</span>
  <span m='137450'>symbol</span> <span m='137767'>of</span> <span m='138084'>the</span>
  <span m='138401'>decoded</span> <span m='138719'>data.</span> </p><p><span m='140319'>Continuing</span>
  <span m='140781'>on:</span> <span m='141244'>11</span> <span m='141707'>gives</span>
  <span m='142170'>us</span> <span m='142633'>A,</span> <span m='143096'>0</span>
  <span m='143558'>decodes</span> <span m='144021'>as</span> <span m='144484'>B,</span>
  <span m='144947'>11</span> <span m='145410'>gives</span> <span m='145873'>us</span>
  <span m='146335'>A</span> <span m='146798'>again,</span> <span m='147261'>and,</span>
  <span m='147724'>finally,</span> <span m='148187'>101</span> <span m='148650'>gives</span>
  <span m='149291'>us</span> <span m='149932'>D.</span> <span m='150573'>The</span>
  <span m='151214'>entire</span> <span m='151855'>decoded</span> <span m='152496'>message</span>
  <span m='153137'>is</span> <span m='153778'>"BCABAD".</span> </p><p><span m='154420'>The</span>
  <span m='154704'>expected</span> <span m='154988'>length</span> <span m='155272'>of</span>
  <span m='155557'>this</span> <span m='155841'>encoding</span> <span m='156125'>is</span>
  <span m='156410'>easy</span> <span m='156694'>to</span> <span m='156978'>compute:</span>
  <span m='157263'>the</span> <span m='157547'>length</span> <span m='157831'>of</span>
  <span m='158116'>A's</span> <span m='158400'>encoding</span> <span m='158684'>(2</span>
  <span m='158969'>bits)</span> <span m='159327'>times</span> <span m='159686'>its</span>
  <span m='160045'>probability,</span> <span m='160404'>plus</span> <span m='160762'>the</span>
  <span m='161121'>length</span> <span m='161480'>of</span> <span m='161839'>B's</span>
  <span m='162197'>encoding</span> <span m='162556'>(1</span> <span m='162915'>bit)</span>
  <span m='163274'>times</span> <span m='163632'>1/2,</span> <span m='163991'>plus</span>
  <span m='164350'>the</span> <span m='164709'>contributions</span> <span m='165208'>for</span>
  <span m='165707'>C</span> <span m='166206'>and</span> <span m='166705'>D,</span>
  <span m='167204'>each</span> <span m='167703'>3</span> <span m='168202'>times</span>
  <span m='168701'>1/12.</span> </p><p><span m='169200'>This</span> <span m='169606'>adds</span>
  <span m='170012'>up</span> <span m='170418'>to</span> <span m='170825'>1</span>
  <span m='171231'>and</span> <span m='171637'>2/3</span> <span m='172043'>bits.</span>
  </p><p><span m='172450'>How</span> <span m='172852'>did</span> <span m='173255'>we</span>
  <span m='173657'>do?</span> </p><p><span m='174060'>If</span> <span m='174375'>we</span>
  <span m='174690'>had</span> <span m='175006'>used</span> <span m='175321'>a</span>
  <span m='175636'>fixed-length</span> <span m='175952'>encoding</span> <span m='176267'>for</span>
  <span m='176582'>our</span> <span m='176898'>four</span> <span m='177213'>possible</span>
  <span m='177528'>symbols,</span> <span m='177844'>we'd</span> <span m='178159'>have</span>
  <span m='178474'>needed</span> <span m='178790'>2</span> <span m='179284'>bits</span>
  <span m='179778'>each,</span> <span m='180272'>so</span> <span m='180766'>we'd</span>
  <span m='181260'>need</span> <span m='181755'>2000</span> <span m='182249'>bits</span>
  <span m='182743'>to</span> <span m='183237'>encode</span> <span m='183731'>1000</span>
  <span m='184225'>symbols.</span> </p><p><span m='184720'>Using</span> <span m='185293'>our</span>
  <span m='185867'>variable-length</span> <span m='186441'>encoding,</span> <span
  m='187015'>the</span> <span m='187589'>expected</span> <span m='188163'>length</span>
  <span m='188736'>for</span> <span m='189310'>1000</span> <span m='189884'>symbols</span>
  <span m='190458'>would</span> <span m='191032'>be</span> <span m='191606'>1667.</span>
  </p><p><span m='192180'>The</span> <span m='192461'>lower</span> <span m='192743'>bound</span>
  <span m='193025'>on</span> <span m='193306'>the</span> <span m='193588'>number</span>
  <span m='193870'>of</span> <span m='194151'>bits</span> <span m='194433'>needed</span>
  <span m='194715'>to</span> <span m='194996'>encode</span> <span m='195278'>1000</span>
  <span m='195560'>symbols</span> <span m='195841'>is</span> <span m='196123'>1000</span>
  <span m='196405'>times</span> <span m='196686'>the</span> <span m='196968'>entropy</span>
  <span m='197250'>H(X),</span> <span m='197704'>which</span> <span m='198158'>is</span>
  <span m='198613'>1626</span> <span m='199067'>bits,</span> <span m='199522'>so</span>
  <span m='199976'>the</span> <span m='200431'>variable-length</span> <span m='200885'>code</span>
  <span m='201340'>got</span> <span m='201794'>us</span> <span m='202248'>closer</span>
  <span m='202703'>to</span> <span m='203157'>our</span> <span m='203612'>goal,</span>
  <span m='204066'>but</span> <span m='204521'>not</span> <span m='204975'>quite</span>
  <span m='205430'>all</span> <span m='206034'>the</span> <span m='206639'>way</span>
  <span m='207244'>there.</span> </p><p><span m='207849'>Could</span> <span m='208216'>another</span>
  <span m='208583'>variable-length</span> <span m='208950'>encoding</span> <span m='209318'>have</span>
  <span m='209685'>done</span> <span m='210052'>better?</span> </p><p><span m='210420'>In</span>
  <span m='210761'>general,</span> <span m='211102'>it</span> <span m='211443'>would</span>
  <span m='211784'>be</span> <span m='212125'>nice</span> <span m='212467'>to</span>
  <span m='212808'>have</span> <span m='213149'>a</span> <span m='213490'>systematic</span>
  <span m='213831'>way</span> <span m='214173'>to</span> <span m='214514'>generate</span>
  <span m='214855'>the</span> <span m='215196'>best-possible</span> <span m='215537'>variable-length</span>
  <span m='215879'>code,</span> <span m='216161'>and</span> <span m='216443'>that's</span>
  <span m='216725'>the</span> <span m='217007'>subject</span> <span m='217289'>of</span>
  <span m='217571'>the</span> <span m='217853'>next</span> <span m='218135'>video.</span>
  </p>
type: course
uid: 2ffa1ad80a8a4ec1625ba9e1e848a7e0

---
None