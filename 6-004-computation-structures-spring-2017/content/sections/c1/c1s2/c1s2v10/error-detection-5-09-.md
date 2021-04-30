---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 4fTOrb1yBFU
  parent_uid: 4a5d17e82ee6dd1b7fac837f2034361b
  title: Video-YouTube-Stream
  type: Video
  uid: 1f45fbf6664b50225d8bea27bd37d00b
- id: 3Play-3Play YouTube id-Stream
  media_location: 4fTOrb1yBFU
  parent_uid: 4a5d17e82ee6dd1b7fac837f2034361b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 8a25f713e896652b7945dfcfdafd9cd0
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/4fTOrb1yBFU/default.jpg
  parent_uid: 4a5d17e82ee6dd1b7fac837f2034361b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 2b88107ba5c168350a3c173f49697841
- id: 4fTOrb1yBFU.srt
  parent_uid: 4a5d17e82ee6dd1b7fac837f2034361b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v10/error-detection-5-09-/4fTOrb1yBFU.srt
  title: 3play caption file
  type: null
  uid: 65f31570c247f800635ea016c7d6acca
- id: 4fTOrb1yBFU.pdf
  parent_uid: 4a5d17e82ee6dd1b7fac837f2034361b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v10/error-detection-5-09-/4fTOrb1yBFU.pdf
  title: 3play pdf file
  type: null
  uid: a56ae7e030b9574293d34936246e86c5
- id: Caption-3Play YouTube id-SRT
  parent_uid: 4a5d17e82ee6dd1b7fac837f2034361b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 9897f745350a1e34524c496c6433692d
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 4a5d17e82ee6dd1b7fac837f2034361b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 6671f05e25ecc0b361d127b06656b9f5
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_01-02-10_300k.mp4
  parent_uid: 4a5d17e82ee6dd1b7fac837f2034361b
  title: Video-Internet Archive-MP4
  type: Video
  uid: 4b9b9c5192d9a571465bfb2d55707d61
inline_embed_id: 45422272errordetection50928871617
layout: video
order_index: null
parent_uid: ae8510beb54f43cc31e74418bdbe9aea
related_resources_text: ''
short_url: error-detection-5-09-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v10/error-detection-5-09-
template_type: Embed
title: Error Detection (5:09)
transcript: <p><span m='459'>Now</span> <span m='705'>let's</span> <span m='951'>think</span>
  <span m='1198'>a</span> <span m='1444'>bit</span> <span m='1690'>about</span> <span
  m='1937'>what</span> <span m='2183'>happens</span> <span m='2429'>if</span> <span
  m='2676'>there's</span> <span m='2922'>an</span> <span m='3169'>error</span> <span
  m='3415'>and</span> <span m='3661'>one</span> <span m='3908'>or</span> <span m='4154'>more</span>
  <span m='4400'>of</span> <span m='4647'>the</span> <span m='4893'>bits</span> <span
  m='5140'>in</span> <span m='5568'>our</span> <span m='5996'>encoded</span> <span
  m='6425'>data</span> <span m='6853'>gets</span> <span m='7281'>corrupted.</span>
  </p><p><span m='7710'>We'll</span> <span m='8025'>focus</span> <span m='8341'>on</span>
  <span m='8656'>single-bit</span> <span m='8972'>errors,</span> <span m='9288'>but</span>
  <span m='9603'>much</span> <span m='9919'>of</span> <span m='10235'>what</span>
  <span m='10550'>we</span> <span m='10866'>discuss</span> <span m='11181'>can</span>
  <span m='11497'>be</span> <span m='11813'>generalized</span> <span m='12128'>to</span>
  <span m='12444'>multi-bit</span> <span m='12760'>errors.</span> </p><p><span m='13760'>For</span>
  <span m='14190'>example,</span> <span m='14621'>consider</span> <span m='15052'>encoding</span>
  <span m='15483'>the</span> <span m='15913'>results</span> <span m='16344'>of</span>
  <span m='16775'>some</span> <span m='17206'>unpredictable</span> <span m='17636'>event,</span>
  <span m='18067'>e.g.,</span> <span m='18498'>flipping</span> <span m='18929'>a</span>
  <span m='19262'>fair</span> <span m='19595'>coin.</span> </p><p><span m='19929'>There</span>
  <span m='20386'>are</span> <span m='20843'>two</span> <span m='21300'>outcomes:</span>
  <span m='21757'>"heads",</span> <span m='22214'>encoded</span> <span m='22671'>as,</span>
  <span m='23129'>say,</span> <span m='23586'>0,</span> <span m='24043'>and</span>
  <span m='24500'>"tails"</span> <span m='24957'>encoded</span> <span m='25414'>as</span>
  <span m='25871'>1.</span> </p><p><span m='26329'>Now</span> <span m='26647'>suppose</span>
  <span m='26966'>some</span> <span m='27285'>error</span> <span m='27603'>occurs</span>
  <span m='27922'>during</span> <span m='28241'>processing</span> <span m='28559'>-</span>
  <span m='28878'>for</span> <span m='29197'>example,</span> <span m='29515'>the</span>
  <span m='29834'>data</span> <span m='30153'>is</span> <span m='30471'>corrupted</span>
  <span m='30790'>while</span> <span m='31109'>being</span> <span m='31535'>transmitted</span>
  <span m='31961'>from</span> <span m='32387'>Bob</span> <span m='32813'>to</span>
  <span m='33240'>Alice:</span> <span m='33666'>Bob</span> <span m='34092'>intended</span>
  <span m='34518'>to</span> <span m='34945'>send</span> <span m='35371'>the</span>
  <span m='35797'>message</span> <span m='36223'>"heads",</span> <span m='36650'>but</span>
  <span m='36950'>the</span> <span m='37251'>0</span> <span m='37551'>was</span> <span
  m='37852'>corrupted</span> <span m='38152'>and</span> <span m='38453'>become</span>
  <span m='38754'>a</span> <span m='39054'>1</span> <span m='39355'>during</span>
  <span m='39655'>transmission,</span> <span m='39956'>so</span> <span m='40257'>Alice</span>
  <span m='40557'>receives</span> <span m='40858'>1,</span> <span m='41158'>which</span>
  <span m='41459'>she</span> <span m='41760'>interprets</span> <span m='42423'>as</span>
  <span m='43086'>"tails".</span> </p><p><span m='43750'>So</span> <span m='44079'>this</span>
  <span m='44408'>simple</span> <span m='44737'>encoding</span> <span m='45066'>doesn't</span>
  <span m='45396'>work</span> <span m='45725'>very</span> <span m='46054'>well</span>
  <span m='46383'>if</span> <span m='46712'>there's</span> <span m='47042'>the</span>
  <span m='47371'>possibility</span> <span m='47700'>of</span> <span m='48029'>single-bit</span>
  <span m='48359'>errors.</span> </p><p><span m='50160'>To</span> <span m='50449'>help</span>
  <span m='50738'>with</span> <span m='51027'>our</span> <span m='51316'>discussion,</span>
  <span m='51606'>we'll</span> <span m='51895'>introduce</span> <span m='52184'>the</span>
  <span m='52473'>notion</span> <span m='52763'>of</span> <span m='53052'>"Hamming</span>
  <span m='53341'>distance",</span> <span m='53630'>defined</span> <span m='53920'>as</span>
  <span m='54247'>the</span> <span m='54574'>number</span> <span m='54901'>of</span>
  <span m='55228'>positions</span> <span m='55555'>in</span> <span m='55882'>which</span>
  <span m='56209'>the</span> <span m='56536'>corresponding</span> <span m='56863'>digits</span>
  <span m='57190'>differ</span> <span m='57517'>in</span> <span m='57844'>two</span>
  <span m='58171'>encodings</span> <span m='58498'>of</span> <span m='58825'>the</span>
  <span m='59152'>same</span> <span m='59480'>length.</span> </p><p><span m='60480'>For</span>
  <span m='60866'>example,</span> <span m='61253'>here</span> <span m='61640'>are</span>
  <span m='62026'>two</span> <span m='62413'>7-bit</span> <span m='62800'>encodings,</span>
  <span m='63186'>which</span> <span m='63573'>differ</span> <span m='63960'>in</span>
  <span m='64346'>their</span> <span m='64733'>third</span> <span m='65120'>and</span>
  <span m='65506'>fifth</span> <span m='65893'>positions,</span> <span m='66280'>so</span>
  <span m='66685'>the</span> <span m='67091'>Hamming</span> <span m='67496'>distance</span>
  <span m='67902'>between</span> <span m='68307'>the</span> <span m='68713'>encodings</span>
  <span m='69118'>is</span> <span m='69524'>2.</span> </p><p><span m='69930'>If</span>
  <span m='70214'>someone</span> <span m='70498'>tells</span> <span m='70782'>us</span>
  <span m='71067'>the</span> <span m='71351'>Hamming</span> <span m='71635'>distance</span>
  <span m='71920'>of</span> <span m='72204'>two</span> <span m='72488'>encodings</span>
  <span m='72773'>is</span> <span m='73057'>0,</span> <span m='73341'>then</span>
  <span m='73626'>the</span> <span m='73910'>two</span> <span m='74194'>encodings</span>
  <span m='74479'>are</span> <span m='75364'>identical.</span> </p><p><span m='76250'>Hamming</span>
  <span m='76718'>distance</span> <span m='77186'>is</span> <span m='77654'>a</span>
  <span m='78122'>handy</span> <span m='78590'>tool</span> <span m='79059'>for</span>
  <span m='79527'>measuring</span> <span m='79995'>how</span> <span m='80463'>encodings</span>
  <span m='80931'>differ.</span> </p><p><span m='81400'>How</span> <span m='81696'>does</span>
  <span m='81993'>this</span> <span m='82290'>help</span> <span m='82586'>us</span>
  <span m='82883'>think</span> <span m='83180'>about</span> <span m='83476'>single-bit</span>
  <span m='83773'>errors?</span> </p><p><span m='84070'>A</span> <span m='84373'>single-bit</span>
  <span m='84677'>error</span> <span m='84981'>changes</span> <span m='85285'>exactly</span>
  <span m='85588'>one</span> <span m='85892'>of</span> <span m='86196'>the</span>
  <span m='86500'>bits</span> <span m='86803'>of</span> <span m='87107'>an</span>
  <span m='87411'>encoding,</span> <span m='87715'>so</span> <span m='88018'>the</span>
  <span m='88322'>Hamming</span> <span m='88626'>distance</span> <span m='88930'>between</span>
  <span m='89271'>a</span> <span m='89613'>valid</span> <span m='89955'>binary</span>
  <span m='90297'>code</span> <span m='90638'>word</span> <span m='90980'>and</span>
  <span m='91322'>the</span> <span m='91664'>same</span> <span m='92005'>code</span>
  <span m='92347'>word</span> <span m='92689'>with</span> <span m='93031'>a</span>
  <span m='93372'>single-bit</span> <span m='93714'>error</span> <span m='94056'>is</span>
  <span m='94398'>1.</span> </p><p><span m='94740'>The</span> <span m='95066'>difficulty</span>
  <span m='95393'>with</span> <span m='95720'>our</span> <span m='96047'>simple</span>
  <span m='96374'>encoding</span> <span m='96701'>is</span> <span m='97028'>that</span>
  <span m='97355'>the</span> <span m='97681'>two</span> <span m='98008'>valid</span>
  <span m='98335'>code</span> <span m='98662'>words</span> <span m='98989'>("0"</span>
  <span m='99316'>and</span> <span m='99643'>"1")</span> <span m='99970'>also</span>
  <span m='100298'>have</span> <span m='100627'>a</span> <span m='100955'>Hamming</span>
  <span m='101284'>distance</span> <span m='101612'>of</span> <span m='101941'>1.</span>
  </p><p><span m='102270'>So</span> <span m='102632'>a</span> <span m='102994'>single-bit</span>
  <span m='103356'>error</span> <span m='103718'>changes</span> <span m='104080'>one</span>
  <span m='104442'>valid</span> <span m='104805'>code</span> <span m='105167'>word</span>
  <span m='105529'>into</span> <span m='105891'>another</span> <span m='106253'>valid</span>
  <span m='106615'>code</span> <span m='106977'>word.</span> </p><p><span m='107340'>We'll</span>
  <span m='107644'>show</span> <span m='107949'>this</span> <span m='108253'>graphically,</span>
  <span m='108558'>using</span> <span m='108862'>an</span> <span m='109167'>arrow</span>
  <span m='109471'>to</span> <span m='109776'>indicate</span> <span m='110080'>that</span>
  <span m='110385'>two</span> <span m='110689'>encodings</span> <span m='110994'>differ</span>
  <span m='111298'>by</span> <span m='111603'>a</span> <span m='111908'>single</span>
  <span m='112323'>bit,</span> <span m='112739'>i.e.,</span> <span m='113155'>that</span>
  <span m='113571'>the</span> <span m='113987'>Hamming</span> <span m='114403'>distance</span>
  <span m='114819'>between</span> <span m='115235'>the</span> <span m='115651'>encodings</span>
  <span m='116067'>is</span> <span m='116483'>1.</span> </p><p><span m='116899'>The</span>
  <span m='117184'>real</span> <span m='117469'>issue</span> <span m='117755'>here</span>
  <span m='118040'>is</span> <span m='118325'>that</span> <span m='118611'>when</span>
  <span m='118896'>Alice</span> <span m='119181'>receives</span> <span m='119467'>a</span>
  <span m='119752'>1,</span> <span m='120037'>she</span> <span m='120323'>can't</span>
  <span m='120608'>distinguish</span> <span m='120893'>between</span> <span m='121179'>an</span>
  <span m='121464'>uncorrupted</span> <span m='121750'>encoding</span> <span m='122065'>of</span>
  <span m='122381'>tails</span> <span m='122696'>and</span> <span m='123012'>a</span>
  <span m='123327'>corrupted</span> <span m='123643'>encoding</span> <span m='123958'>of</span>
  <span m='124274'>heads</span> <span m='124590'>-</span> <span m='124905'>she</span>
  <span m='125221'>can't</span> <span m='125536'>detect</span> <span m='125852'>that</span>
  <span m='126167'>an</span> <span m='126483'>error</span> <span m='126799'>occurred.</span>
  </p><p><span m='128030'>Let's</span> <span m='128445'>figure</span> <span m='128861'>how</span>
  <span m='129277'>to</span> <span m='129692'>solve</span> <span m='130108'>her</span>
  <span m='130524'>problem!</span> </p><p><span m='130940'>The</span> <span m='131174'>insight</span>
  <span m='131408'>is</span> <span m='131642'>to</span> <span m='131876'>come</span>
  <span m='132111'>up</span> <span m='132345'>with</span> <span m='132579'>a</span>
  <span m='132813'>set</span> <span m='133047'>of</span> <span m='133282'>valid</span>
  <span m='133516'>code</span> <span m='133750'>words</span> <span m='133984'>such</span>
  <span m='134218'>that</span> <span m='134453'>a</span> <span m='134687'>single-bit</span>
  <span m='134921'>error</span> <span m='135155'>does</span> <span m='135390'>NOT</span>
  <span m='135898'>produce</span> <span m='136406'>another</span> <span m='136915'>valid</span>
  <span m='137423'>code</span> <span m='137931'>word.</span> </p><p><span m='138440'>What</span>
  <span m='138713'>we</span> <span m='138986'>need</span> <span m='139260'>are</span>
  <span m='139533'>code</span> <span m='139806'>words</span> <span m='140080'>that</span>
  <span m='140353'>differ</span> <span m='140626'>by</span> <span m='140900'>at</span>
  <span m='141173'>least</span> <span m='141446'>two</span> <span m='141720'>bits,</span>
  <span m='141993'>i.e.,</span> <span m='142266'>we</span> <span m='142540'>want</span>
  <span m='142813'>the</span> <span m='143086'>minimum</span> <span m='143360'>Hamming</span>
  <span m='143772'>distance</span> <span m='144185'>between</span> <span m='144597'>any</span>
  <span m='145010'>two</span> <span m='145422'>code</span> <span m='145835'>words</span>
  <span m='146247'>to</span> <span m='146660'>be</span> <span m='147072'>at</span>
  <span m='147485'>least</span> <span m='147897'>2.</span> </p><p><span m='148310'>If</span>
  <span m='148548'>we</span> <span m='148786'>have</span> <span m='149025'>a</span>
  <span m='149263'>set</span> <span m='149502'>of</span> <span m='149740'>code</span>
  <span m='149978'>words</span> <span m='150217'>where</span> <span m='150455'>the</span>
  <span m='150694'>minimum</span> <span m='150932'>Hamming</span> <span m='151171'>distance</span>
  <span m='151409'>is</span> <span m='151647'>1,</span> <span m='151886'>we</span>
  <span m='152124'>can</span> <span m='152363'>generate</span> <span m='152601'>the</span>
  <span m='152840'>set</span> <span m='153185'>we</span> <span m='153530'>want</span>
  <span m='153876'>by</span> <span m='154221'>adding</span> <span m='154566'>a</span>
  <span m='154912'>parity</span> <span m='155257'>bit</span> <span m='155602'>to</span>
  <span m='155948'>each</span> <span m='156293'>of</span> <span m='156638'>the</span>
  <span m='156984'>original</span> <span m='157329'>code</span> <span m='157674'>words.</span>
  </p><p><span m='158020'>There's</span> <span m='158453'>"even</span> <span m='158886'>parity"</span>
  <span m='159320'>and</span> <span m='159753'>"odd</span> <span m='160186'>parity."</span>
  <span m='160620'>Using</span> <span m='160905'>even</span> <span m='161191'>parity,</span>
  <span m='161477'>the</span> <span m='161763'>additional</span> <span m='162049'>parity</span>
  <span m='162335'>bit</span> <span m='162621'>is</span> <span m='162907'>chosen</span>
  <span m='163193'>so</span> <span m='163479'>that</span> <span m='163765'>the</span>
  <span m='164051'>total</span> <span m='164337'>number</span> <span m='164623'>of</span>
  <span m='164909'>1</span> <span m='165195'>bits</span> <span m='165481'>in</span>
  <span m='165890'>the</span> <span m='166300'>new</span> <span m='166710'>code</span>
  <span m='167120'>word</span> <span m='167530'>are</span> <span m='167940'>even.</span>
  </p><p><span m='168350'>For</span> <span m='168706'>example,</span> <span m='169063'>our</span>
  <span m='169420'>original</span> <span m='169777'>encoding</span> <span m='170134'>for</span>
  <span m='170491'>"heads"</span> <span m='170848'>was</span> <span m='171205'>0,</span>
  <span m='171561'>adding</span> <span m='171918'>an</span> <span m='172275'>even</span>
  <span m='172632'>parity</span> <span m='172989'>bit</span> <span m='173346'>gives</span>
  <span m='173703'>us</span> <span m='174060'>00.</span> </p><p><span m='175610'>Adding</span>
  <span m='175952'>an</span> <span m='176294'>even</span> <span m='176636'>parity</span>
  <span m='176978'>bit</span> <span m='177320'>to</span> <span m='177662'>our</span>
  <span m='178005'>original</span> <span m='178347'>encoding</span> <span m='178689'>for</span>
  <span m='179031'>"tails"</span> <span m='179373'>gives</span> <span m='179715'>us</span>
  <span m='180057'>11.</span> </p><p><span m='180400'>The</span> <span m='180805'>minimum</span>
  <span m='181210'>Hamming</span> <span m='181616'>distance</span> <span m='182021'>between</span>
  <span m='182426'>code</span> <span m='182832'>words</span> <span m='183237'>has</span>
  <span m='183643'>increased</span> <span m='184048'>from</span> <span m='184453'>1</span>
  <span m='184859'>to</span> <span m='185264'>2.</span> </p><p><span m='185670'>How</span>
  <span m='186267'>does</span> <span m='186865'>this</span> <span m='187462'>help?</span>
  </p><p><span m='188060'>Consider</span> <span m='188433'>what</span> <span m='188806'>happens</span>
  <span m='189179'>when</span> <span m='189552'>there's</span> <span m='189925'>a</span>
  <span m='190298'>single-bit</span> <span m='190671'>error:</span> <span m='191045'>00</span>
  <span m='191418'>would</span> <span m='191791'>be</span> <span m='192164'>corrupted</span>
  <span m='192537'>to</span> <span m='192910'>01</span> <span m='193283'>or</span>
  <span m='193656'>10,</span> <span m='194030'>neither</span> <span m='194340'>of</span>
  <span m='194650'>which</span> <span m='194960'>is</span> <span m='195270'>a</span>
  <span m='195580'>valid</span> <span m='195890'>code</span> <span m='196200'>word.</span>
  </p><p><span m='196510'>Aha!</span> </p><p><span m='197510'>We</span> <span m='197877'>can</span>
  <span m='198245'>detect</span> <span m='198613'>that</span> <span m='198981'>a</span>
  <span m='199348'>single-bit</span> <span m='199716'>error</span> <span m='200084'>has</span>
  <span m='200452'>occurred.</span> </p><p><span m='200820'>Similarly,</span> <span
  m='201375'>single-bit</span> <span m='201931'>errors</span> <span m='202486'>for</span>
  <span m='203042'>11</span> <span m='203597'>would</span> <span m='204153'>also</span>
  <span m='204708'>be</span> <span m='205264'>detected.</span> </p><p><span m='205820'>Note</span>
  <span m='206140'>that</span> <span m='206460'>the</span> <span m='206780'>valid</span>
  <span m='207100'>code</span> <span m='207420'>words</span> <span m='207740'>00</span>
  <span m='208060'>and</span> <span m='208380'>11</span> <span m='208700'>both</span>
  <span m='209020'>have</span> <span m='209340'>an</span> <span m='209660'>even</span>
  <span m='209980'>number</span> <span m='210300'>of</span> <span m='210620'>1-bits,</span>
  <span m='210940'>but</span> <span m='211260'>that</span> <span m='211580'>the</span>
  <span m='211900'>corrupted</span> <span m='212286'>code</span> <span m='212673'>words</span>
  <span m='213060'>01</span> <span m='213446'>or</span> <span m='213833'>10</span>
  <span m='214220'>have</span> <span m='214606'>an</span> <span m='214993'>odd</span>
  <span m='215380'>number</span> <span m='215766'>of</span> <span m='216153'>1-bits.</span>
  </p><p><span m='216540'>We</span> <span m='216937'>say</span> <span m='217334'>that</span>
  <span m='217731'>corrupted</span> <span m='218128'>code</span> <span m='218525'>words</span>
  <span m='218922'>have</span> <span m='219319'>a</span> <span m='219716'>"parity</span>
  <span m='220113'>error".</span> </p><p><span m='220510'>It's</span> <span m='220782'>easy</span>
  <span m='221055'>to</span> <span m='221328'>perform</span> <span m='221601'>a</span>
  <span m='221874'>parity</span> <span m='222147'>check:</span> <span m='222420'>simply</span>
  <span m='222693'>count</span> <span m='222966'>the</span> <span m='223239'>number</span>
  <span m='223512'>of</span> <span m='223785'>1s</span> <span m='224058'>in</span>
  <span m='224331'>the</span> <span m='224604'>code</span> <span m='224877'>word.</span>
  </p><p><span m='225150'>If</span> <span m='225509'>it's</span> <span m='225868'>even,</span>
  <span m='226228'>a</span> <span m='226587'>single-bit</span> <span m='226947'>error</span>
  <span m='227306'>has</span> <span m='227665'>NOT</span> <span m='228025'>occurred;</span>
  <span m='228384'>if</span> <span m='228744'>it's</span> <span m='229103'>odd,</span>
  <span m='229462'>a</span> <span m='229822'>single-bit</span> <span m='230181'>error</span>
  <span m='230541'>HAS</span> <span m='230900'>occurred.</span> </p><p><span m='231260'>We'll</span>
  <span m='231547'>see</span> <span m='231834'>in</span> <span m='232122'>a</span>
  <span m='232409'>couple</span> <span m='232696'>of</span> <span m='232984'>chapters</span>
  <span m='233271'>that</span> <span m='233558'>the</span> <span m='233846'>Boolean</span>
  <span m='234133'>function</span> <span m='234420'>exclusive-or</span> <span m='234708'>can</span>
  <span m='234995'>be</span> <span m='235282'>used</span> <span m='235570'>to</span>
  <span m='236215'>perform</span> <span m='236860'>parity</span> <span m='237505'>checks.</span>
  </p><p><span m='238150'>Note</span> <span m='238402'>that</span> <span m='238655'>parity</span>
  <span m='238908'>won't</span> <span m='239161'>help</span> <span m='239414'>us</span>
  <span m='239667'>if</span> <span m='239920'>there's</span> <span m='240173'>an</span>
  <span m='240426'>even</span> <span m='240679'>number</span> <span m='240932'>of</span>
  <span m='241185'>bit</span> <span m='241438'>errors,</span> <span m='241691'>where</span>
  <span m='241944'>a</span> <span m='242197'>corrupted</span> <span m='242450'>code</span>
  <span m='242795'>word</span> <span m='243140'>would</span> <span m='243486'>have</span>
  <span m='243831'>an</span> <span m='244176'>even</span> <span m='244522'>number</span>
  <span m='244867'>of</span> <span m='245212'>1-bits</span> <span m='245558'>and</span>
  <span m='245903'>hence</span> <span m='246248'>appear</span> <span m='246594'>to</span>
  <span m='246939'>be</span> <span m='247284'>okay.</span> </p><p><span m='247630'>Parity</span>
  <span m='247970'>is</span> <span m='248311'>useful</span> <span m='248652'>for</span>
  <span m='248993'>detecting</span> <span m='249333'>single-bit</span> <span m='249674'>errors;</span>
  <span m='250015'>we'll</span> <span m='250356'>need</span> <span m='250696'>a</span>
  <span m='251037'>more</span> <span m='251378'>sophisticated</span> <span m='251719'>encoding</span>
  <span m='252060'>to</span> <span m='252732'>detect</span> <span m='253405'>more</span>
  <span m='254077'>errors.</span> </p><p><span m='254750'>In</span> <span m='255086'>general,</span>
  <span m='255423'>to</span> <span m='255760'>detect</span> <span m='256097'>some</span>
  <span m='256434'>number</span> <span m='256771'>E</span> <span m='257108'>of</span>
  <span m='257445'>errors,</span> <span m='257782'>we</span> <span m='258119'>need</span>
  <span m='258456'>a</span> <span m='258793'>minimum</span> <span m='259130'>Hamming</span>
  <span m='259467'>distance</span> <span m='259804'>of</span> <span m='260141'>E+1</span>
  <span m='260478'>between</span> <span m='261041'>code</span> <span m='261605'>words.</span>
  </p><p><span m='262169'>We</span> <span m='262449'>can</span> <span m='262730'>see</span>
  <span m='263010'>this</span> <span m='263291'>graphically</span> <span m='263572'>below</span>
  <span m='263852'>which</span> <span m='264133'>shows</span> <span m='264414'>how</span>
  <span m='264694'>errors</span> <span m='264975'>can</span> <span m='265255'>corrupt</span>
  <span m='265536'>the</span> <span m='265817'>valid</span> <span m='266097'>code</span>
  <span m='266378'>words</span> <span m='266659'>000</span> <span m='267155'>and</span>
  <span m='267651'>111,</span> <span m='268147'>which</span> <span m='268643'>have</span>
  <span m='269139'>a</span> <span m='269635'>Hamming</span> <span m='270131'>distance</span>
  <span m='270627'>of</span> <span m='271123'>3.</span> </p><p><span m='271620'>In</span>
  <span m='272004'>theory</span> <span m='272388'>this</span> <span m='272772'>means</span>
  <span m='273157'>we</span> <span m='273541'>should</span> <span m='273925'>be</span>
  <span m='274310'>able</span> <span m='274694'>to</span> <span m='275078'>detect</span>
  <span m='275462'>up</span> <span m='275847'>to</span> <span m='276231'>2-bit</span>
  <span m='276615'>errors.</span> </p><p><span m='277000'>Each</span> <span m='277286'>arrow</span>
  <span m='277572'>represents</span> <span m='277858'>a</span> <span m='278144'>single-bit</span>
  <span m='278430'>error</span> <span m='278716'>and</span> <span m='279002'>we</span>
  <span m='279288'>can</span> <span m='279574'>see</span> <span m='279860'>from</span>
  <span m='280146'>the</span> <span m='280432'>diagram</span> <span m='280718'>that</span>
  <span m='281004'>following</span> <span m='281290'>any</span> <span m='281630'>path</span>
  <span m='281970'>of</span> <span m='282310'>length</span> <span m='282650'>2</span>
  <span m='282990'>from</span> <span m='283330'>either</span> <span m='283670'>000</span>
  <span m='284010'>or</span> <span m='284350'>111</span> <span m='284690'>doesn't</span>
  <span m='285030'>get</span> <span m='285370'>us</span> <span m='285710'>to</span>
  <span m='286050'>the</span> <span m='286390'>other</span> <span m='286730'>valid</span>
  <span m='287070'>code</span> <span m='287410'>word.</span> </p><p><span m='287750'>In</span>
  <span m='288128'>other</span> <span m='288507'>words,</span> <span m='288886'>assuming</span>
  <span m='289265'>we</span> <span m='289643'>start</span> <span m='290022'>with</span>
  <span m='290401'>either</span> <span m='290780'>000</span> <span m='291158'>or</span>
  <span m='291537'>111,</span> <span m='291916'>we</span> <span m='292295'>can</span>
  <span m='292673'>detect</span> <span m='293052'>the</span> <span m='293431'>occurrence</span>
  <span m='293810'>of</span> <span m='294189'>up</span> <span m='294771'>to</span>
  <span m='295354'>2</span> <span m='295937'>errors.</span> </p><p><span m='296520'>Basically</span>
  <span m='296838'>our</span> <span m='297157'>error</span> <span m='297475'>detection</span>
  <span m='297794'>scheme</span> <span m='298112'>relies</span> <span m='298431'>on</span>
  <span m='298749'>choosing</span> <span m='299068'>code</span> <span m='299386'>words</span>
  <span m='299705'>far</span> <span m='300023'>enough</span> <span m='300342'>apart,</span>
  <span m='300660'>as</span> <span m='300979'>measured</span> <span m='301288'>by</span>
  <span m='301597'>Hamming</span> <span m='301907'>distance,</span> <span m='302216'>so</span>
  <span m='302526'>that</span> <span m='302835'>E</span> <span m='303145'>errors</span>
  <span m='303454'>can't</span> <span m='303763'>corrupt</span> <span m='304073'>one</span>
  <span m='304382'>valid</span> <span m='304692'>code</span> <span m='305001'>word</span>
  <span m='305311'>so</span> <span m='305620'>that</span> <span m='305930'>it</span>
  <span m='306199'>looks</span> <span m='306469'>like</span> <span m='306739'>another</span>
  <span m='307009'>valid</span> <span m='307279'>code</span> <span m='307549'>word.</span>
  </p>
type: course
uid: 4a5d17e82ee6dd1b7fac837f2034361b

---
None