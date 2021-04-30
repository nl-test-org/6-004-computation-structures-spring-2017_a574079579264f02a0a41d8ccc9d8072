---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 7ufoYYj15cU
  parent_uid: 114bb62d560da35adb38e947c605c36f
  title: Video-YouTube-Stream
  type: Video
  uid: 01eeb0a9263c1d6a976a1fba3e1df697
- id: 3Play-3PlayVideoid-MP4
  media_location: '3683025'
  parent_uid: 114bb62d560da35adb38e947c605c36f
  title: 3Play-3Play Video id
  type: 3Play
  uid: 4e1ef2ffce7d728d2ce23943ac8e861d
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/7ufoYYj15cU/default.jpg
  parent_uid: 114bb62d560da35adb38e947c605c36f
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 4fe4408f2a1e2e97e51c67b200231974
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_01-02-03_300k.mp4
  parent_uid: 114bb62d560da35adb38e947c605c36f
  title: Video-Internet Archive-MP4
  type: Video
  uid: 74d37dec95401299125b6d77a9610e1d
- id: 3683025.srt
  parent_uid: 114bb62d560da35adb38e947c605c36f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v3/entropy-2-49-/3683025.srt
  title: 3play caption file
  type: null
  uid: 148aed0dae620bbcb0f4c8f394c265d3
- id: 3683025.pdf
  parent_uid: 114bb62d560da35adb38e947c605c36f
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v3/entropy-2-49-/3683025.pdf
  title: 3play pdf file
  type: null
  uid: e290dfc3ce10df8f2d8f8027f033a72a
- id: Caption-3Play Video id-SRT
  parent_uid: 114bb62d560da35adb38e947c605c36f
  title: Caption-3Play Video id-SRT-English - US
  type: Caption
  uid: 13fb7a9028ee6356c53862dbcf9d0531
- id: Transcript-3Play Video id-PDF
  parent_uid: 114bb62d560da35adb38e947c605c36f
  title: Transcript-3Play Video id-PDF-English - US
  type: Transcript
  uid: d6ba5ef1084d8e2a385caa90a34c479e
inline_embed_id: 95648860entropy24922649100
layout: video
order_index: null
parent_uid: 87435062e6073a2280dd3df21e05cc53
related_resources_text: ''
short_url: entropy-2-49-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v3/entropy-2-49-
template_type: Embed
title: Entropy (2:49)
transcript: <p><span m='1069'>In</span> <span m='1317'>the</span> <span m='1566'>next</span>
  <span m='1815'>section</span> <span m='2064'>we're</span> <span m='2313'>going</span>
  <span m='2561'>to</span> <span m='2810'>start</span> <span m='3059'>our</span> <span
  m='3308'>discussion</span> <span m='3557'>on</span> <span m='3805'>how</span> <span
  m='4054'>to</span> <span m='4303'>actually</span> <span m='4552'>engineer</span>
  <span m='4801'>the</span> <span m='5050'>bit</span> <span m='5338'>encodings</span>
  <span m='5626'>we'll</span> <span m='5914'>use</span> <span m='6202'>in</span> <span
  m='6490'>our</span> <span m='6778'>circuitry,</span> <span m='7066'>but</span> <span
  m='7355'>first</span> <span m='7643'>we'll</span> <span m='7931'>need</span> <span
  m='8219'>a</span> <span m='8507'>way</span> <span m='8795'>to</span> <span m='9083'>evaluate</span>
  <span m='9371'>the</span> <span m='9660'>efficacy</span> <span m='10275'>of</span>
  <span m='10890'>an</span> <span m='11505'>encoding.</span> </p><p><span m='12120'>The</span>
  <span m='12467'>entropy</span> <span m='12814'>of</span> <span m='13161'>a</span>
  <span m='13508'>random</span> <span m='13855'>variable</span> <span m='14202'>is</span>
  <span m='14550'>average</span> <span m='14897'>amount</span> <span m='15244'>of</span>
  <span m='15591'>information</span> <span m='15938'>received</span> <span m='16285'>when</span>
  <span m='16632'>learning</span> <span m='16980'>the</span> <span m='17400'>value</span>
  <span m='17820'>of</span> <span m='18240'>the</span> <span m='18660'>random</span>
  <span m='19080'>variable.</span> </p><p><span m='19500'>The</span> <span m='19828'>mathematician's</span>
  <span m='20156'>name</span> <span m='20484'>for</span> <span m='20813'>"average"</span>
  <span m='21141'>is</span> <span m='21469'>"expected</span> <span m='21797'>value";</span>
  <span m='22126'>that's</span> <span m='22454'>what</span> <span m='22782'>the</span>
  <span m='23110'>capital</span> <span m='23439'>E</span> <span m='24244'>means.</span>
  </p><p><span m='25050'>We</span> <span m='25394'>compute</span> <span m='25738'>the</span>
  <span m='26083'>average</span> <span m='26427'>in</span> <span m='26771'>the</span>
  <span m='27116'>obvious</span> <span m='27460'>way:</span> <span m='27805'>we</span>
  <span m='28149'>take</span> <span m='28493'>the</span> <span m='28838'>weighted</span>
  <span m='29182'>sum,</span> <span m='29526'>where</span> <span m='29871'>the</span>
  <span m='30215'>amount</span> <span m='30560'>of</span> <span m='31011'>information</span>
  <span m='31462'>received</span> <span m='31913'>when</span> <span m='32365'>learning</span>
  <span m='32816'>of</span> <span m='33267'>particular</span> <span m='33718'>choice</span>
  <span m='34170'>i</span> <span m='34621'>--</span> <span m='35072'>that's</span>
  <span m='35523'>the</span> <span m='35975'>log-base-2</span> <span m='36426'>of</span>
  <span m='36877'>1/p_i</span> <span m='37329'>--</span> <span m='37677'>is</span>
  <span m='38025'>weighted</span> <span m='38373'>by</span> <span m='38722'>the</span>
  <span m='39070'>probability</span> <span m='39418'>of</span> <span m='39766'>that</span>
  <span m='40115'>choice</span> <span m='40463'>actually</span> <span m='40811'>happening.</span>
  </p><p><span m='41160'>Here's</span> <span m='41936'>an</span> <span m='42712'>example.</span>
  </p><p><span m='43489'>We</span> <span m='43803'>have</span> <span m='44117'>a</span>
  <span m='44432'>random</span> <span m='44746'>variable</span> <span m='45061'>that</span>
  <span m='45375'>can</span> <span m='45690'>take</span> <span m='46004'>on</span>
  <span m='46319'>one</span> <span m='46633'>of</span> <span m='46947'>four</span>
  <span m='47262'>values:</span> <span m='47576'>A,</span> <span m='47891'>B,</span>
  <span m='48205'>C</span> <span m='48520'>or</span> <span m='48834'>D.</span> </p><p><span
  m='49149'>The</span> <span m='49455'>probabilities</span> <span m='49761'>of</span>
  <span m='50067'>each</span> <span m='50373'>choice</span> <span m='50679'>are</span>
  <span m='50985'>shown</span> <span m='51291'>in</span> <span m='51597'>the</span>
  <span m='51903'>table,</span> <span m='52209'>along</span> <span m='52515'>with</span>
  <span m='52821'>the</span> <span m='53127'>associated</span> <span m='53433'>information</span>
  <span m='53739'>content.</span> </p><p><span m='56280'>Now</span> <span m='56704'>we'll</span>
  <span m='57128'>compute</span> <span m='57553'>the</span> <span m='57977'>entropy</span>
  <span m='58402'>using</span> <span m='58826'>the</span> <span m='59251'>probabilities</span>
  <span m='59675'>and</span> <span m='60100'>information</span> <span m='60524'>content.</span>
  </p><p><span m='60949'>So</span> <span m='61337'>we</span> <span m='61725'>have</span>
  <span m='62113'>the</span> <span m='62501'>probability</span> <span m='62889'>of</span>
  <span m='63277'>A</span> <span m='63665'>(1/3)</span> <span m='64053'>times</span>
  <span m='64441'>its</span> <span m='64829'>associated</span> <span m='65217'>information</span>
  <span m='65605'>content</span> <span m='65993'>(1.58</span> <span m='66381'>bits),</span>
  <span m='66770'>plus</span> <span m='67276'>the</span> <span m='67783'>probability</span>
  <span m='68290'>of</span> <span m='68797'>B</span> <span m='69304'>times</span>
  <span m='69811'>its</span> <span m='70318'>associated</span> <span m='70825'>information</span>
  <span m='71332'>content,</span> <span m='71839'>and</span> <span m='72346'>so</span>
  <span m='72853'>on.</span> </p><p><span m='73360'>The</span> <span m='74103'>result</span>
  <span m='74847'>is</span> <span m='75591'>1.626</span> <span m='76335'>bits.</span>
  </p><p><span m='77079'>This</span> <span m='77329'>is</span> <span m='77579'>telling</span>
  <span m='77829'>us</span> <span m='78079'>that</span> <span m='78329'>a</span> <span
  m='78579'>clever</span> <span m='78829'>encoding</span> <span m='79079'>scheme</span>
  <span m='79329'>should</span> <span m='79579'>be</span> <span m='79829'>able</span>
  <span m='80079'>to</span> <span m='80329'>do</span> <span m='80579'>better</span>
  <span m='80829'>than</span> <span m='81079'>simply</span> <span m='81330'>encoding</span>
  <span m='81690'>each</span> <span m='82051'>symbol</span> <span m='82411'>using</span>
  <span m='82772'>2</span> <span m='83133'>bits</span> <span m='83493'>to</span> <span
  m='83854'>represent</span> <span m='84215'>which</span> <span m='84575'>of</span>
  <span m='84936'>the</span> <span m='85296'>four</span> <span m='85657'>possible</span>
  <span m='86018'>values</span> <span m='86378'>is</span> <span m='86739'>next.</span>
  </p><p><span m='87100'>Food</span> <span m='87740'>for</span> <span m='88380'>thought!</span>
  </p><p><span m='89020'>We'll</span> <span m='89418'>discuss</span> <span m='89816'>this</span>
  <span m='90214'>further</span> <span m='90612'>in</span> <span m='91010'>the</span>
  <span m='91408'>third</span> <span m='91806'>section</span> <span m='92204'>of</span>
  <span m='92602'>this</span> <span m='93000'>chapter.</span> </p><p><span m='93399'>So,</span>
  <span m='94030'>what</span> <span m='94662'>is</span> <span m='95293'>the</span>
  <span m='95925'>entropy</span> <span m='96556'>telling</span> <span m='97188'>us?</span>
  </p><p><span m='97820'>Suppose</span> <span m='98111'>we</span> <span m='98403'>have</span>
  <span m='98695'>a</span> <span m='98987'>sequence</span> <span m='99279'>of</span>
  <span m='99571'>data</span> <span m='99863'>describing</span> <span m='100155'>a</span>
  <span m='100446'>sequence</span> <span m='100738'>of</span> <span m='101030'>values</span>
  <span m='101322'>of</span> <span m='101614'>the</span> <span m='101906'>random</span>
  <span m='102198'>variable</span> <span m='102490'>X.</span> </p><p><span m='103490'>If,</span>
  <span m='103888'>on</span> <span m='104286'>the</span> <span m='104684'>average,</span>
  <span m='105082'>we</span> <span m='105480'>use</span> <span m='105878'>less</span>
  <span m='106276'>than</span> <span m='106675'>H(X)</span> <span m='107073'>bits</span>
  <span m='107471'>to</span> <span m='107869'>transmit</span> <span m='108267'>each</span>
  <span m='108665'>piece</span> <span m='109063'>of</span> <span m='109461'>information</span>
  <span m='109860'>in</span> <span m='110158'>the</span> <span m='110457'>sequence,</span>
  <span m='110756'>we</span> <span m='111054'>will</span> <span m='111353'>not</span>
  <span m='111652'>be</span> <span m='111950'>sending</span> <span m='112249'>enough</span>
  <span m='112548'>information</span> <span m='112846'>to</span> <span m='113145'>resolve</span>
  <span m='113444'>the</span> <span m='113742'>uncertainty</span> <span m='114041'>about</span>
  <span m='114340'>the</span> <span m='115090'>values.</span> </p><p><span m='115840'>In</span>
  <span m='116162'>other</span> <span m='116485'>words,</span> <span m='116808'>the</span>
  <span m='117130'>entropy</span> <span m='117453'>is</span> <span m='117776'>a</span>
  <span m='118099'>lower</span> <span m='118421'>bound</span> <span m='118744'>on</span>
  <span m='119067'>the</span> <span m='119389'>number</span> <span m='119712'>of</span>
  <span m='120035'>bits</span> <span m='120358'>we</span> <span m='120680'>need</span>
  <span m='121003'>to</span> <span m='121326'>transmit.</span> </p><p><span m='121649'>Getting</span>
  <span m='121939'>less</span> <span m='122229'>than</span> <span m='122519'>this</span>
  <span m='122809'>number</span> <span m='123099'>of</span> <span m='123389'>bits</span>
  <span m='123679'>wouldn't</span> <span m='123969'>be</span> <span m='124259'>good</span>
  <span m='124549'>if</span> <span m='124839'>the</span> <span m='125129'>goal</span>
  <span m='125419'>was</span> <span m='125709'>to</span> <span m='125999'>unambiguously</span>
  <span m='126289'>describe</span> <span m='126579'>the</span> <span m='126978'>sequence</span>
  <span m='127377'>of</span> <span m='127776'>values</span> <span m='128175'>--</span>
  <span m='128574'>we'd</span> <span m='128974'>have</span> <span m='129373'>failed</span>
  <span m='129772'>at</span> <span m='130171'>our</span> <span m='130570'>job!</span>
  </p><p><span m='130970'>On</span> <span m='131257'>the</span> <span m='131544'>other</span>
  <span m='131831'>hand,</span> <span m='132118'>if</span> <span m='132406'>we</span>
  <span m='132693'>send,</span> <span m='132980'>on</span> <span m='133267'>the</span>
  <span m='133555'>average,</span> <span m='133842'>more</span> <span m='134129'>than</span>
  <span m='134416'>H(X)</span> <span m='134703'>bits</span> <span m='134991'>to</span>
  <span m='135278'>describe</span> <span m='135565'>the</span> <span m='135852'>sequence</span>
  <span m='136140'>of</span> <span m='136441'>values,</span> <span m='136743'>we</span>
  <span m='137045'>will</span> <span m='137347'>not</span> <span m='137649'>be</span>
  <span m='137951'>making</span> <span m='138253'>the</span> <span m='138555'>most</span>
  <span m='138856'>effective</span> <span m='139158'>use</span> <span m='139460'>of</span>
  <span m='139762'>our</span> <span m='140064'>resources,</span> <span m='140366'>since</span>
  <span m='140668'>the</span> <span m='140970'>same</span> <span m='141310'>information</span>
  <span m='141650'>might</span> <span m='141990'>have</span> <span m='142330'>been</span>
  <span m='142670'>able</span> <span m='143010'>to</span> <span m='143350'>be</span>
  <span m='143690'>represented</span> <span m='144030'>with</span> <span m='144370'>fewer</span>
  <span m='144710'>bits.</span> </p><p><span m='145050'>This</span> <span m='145425'>is</span>
  <span m='145801'>okay,</span> <span m='146177'>but</span> <span m='146553'>perhaps</span>
  <span m='146929'>with</span> <span m='147305'>some</span> <span m='147680'>insights</span>
  <span m='148056'>we</span> <span m='148432'>could</span> <span m='148808'>do</span>
  <span m='149184'>better.</span> </p><p><span m='149560'>Finally,</span> <span m='149960'>if</span>
  <span m='150361'>we</span> <span m='150761'>send,</span> <span m='151162'>on</span>
  <span m='151563'>the</span> <span m='151963'>average,</span> <span m='152364'>exactly</span>
  <span m='152765'>H(X)</span> <span m='153165'>bits,</span> <span m='153566'>then</span>
  <span m='153966'>we'd</span> <span m='154367'>have</span> <span m='154768'>the</span>
  <span m='155168'>perfect</span> <span m='155569'>encoding.</span> </p><p><span m='155970'>Alas,</span>
  <span m='156230'>perfection</span> <span m='156491'>is,</span> <span m='156751'>as</span>
  <span m='157012'>always,</span> <span m='157272'>a</span> <span m='157533'>tough</span>
  <span m='157793'>goal,</span> <span m='158054'>so</span> <span m='158315'>most</span>
  <span m='158575'>of</span> <span m='158836'>the</span> <span m='159096'>time</span>
  <span m='159357'>we'll</span> <span m='159617'>have</span> <span m='159878'>to</span>
  <span m='160138'>settle</span> <span m='160399'>for</span> <span m='160660'>getting</span>
  <span m='161350'>close.</span> </p><p><span m='162040'>In</span> <span m='162431'>the</span>
  <span m='162822'>final</span> <span m='163213'>set</span> <span m='163605'>of</span>
  <span m='163996'>exercises</span> <span m='164387'>for</span> <span m='164778'>this</span>
  <span m='165170'>section,</span> <span m='165561'>try</span> <span m='165952'>computing</span>
  <span m='166343'>the</span> <span m='166735'>entropy</span> <span m='167126'>for</span>
  <span m='167517'>various</span> <span m='167908'>scenarios.</span> </p>
type: course
uid: 114bb62d560da35adb38e947c605c36f

---
None