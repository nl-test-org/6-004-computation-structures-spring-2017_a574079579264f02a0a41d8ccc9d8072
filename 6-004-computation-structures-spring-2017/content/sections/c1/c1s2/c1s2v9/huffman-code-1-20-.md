---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: JuvrTQapI_k
  parent_uid: 1fa379c46d74cfea11603f5c725bba11
  title: Video-YouTube-Stream
  type: Video
  uid: f898c4360de98fce22cc582b020ddd85
- id: 3Play-3Play YouTube id-Stream
  media_location: JuvrTQapI_k
  parent_uid: 1fa379c46d74cfea11603f5c725bba11
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: abf5230c7cf722f76b81c045a578dcab
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/JuvrTQapI_k/default.jpg
  parent_uid: 1fa379c46d74cfea11603f5c725bba11
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: d7748e0f8c85cd7d2b057e71a93fc45b
- id: JuvrTQapI_k.srt
  parent_uid: 1fa379c46d74cfea11603f5c725bba11
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v9/huffman-code-1-20-/JuvrTQapI_k.srt
  title: 3play caption file
  type: null
  uid: bf23a7e954851f732e17f9aa45ecf975
- id: JuvrTQapI_k.pdf
  parent_uid: 1fa379c46d74cfea11603f5c725bba11
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v9/huffman-code-1-20-/JuvrTQapI_k.pdf
  title: 3play pdf file
  type: null
  uid: 98d67d21c1c38047dc07d2935bf358f0
- id: Caption-3Play YouTube id-SRT
  parent_uid: 1fa379c46d74cfea11603f5c725bba11
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 70de842441041fdfd61d27586351aa00
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 1fa379c46d74cfea11603f5c725bba11
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 703ece7accb94da76e5179dd06509c05
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_01-02-09_300k.mp4
  parent_uid: 1fa379c46d74cfea11603f5c725bba11
  title: Video-Internet Archive-MP4
  type: Video
  uid: 1577c90c7764f227ae6079c75fb6da9d
inline_embed_id: 72935384huffmancode12054378669
layout: video
order_index: null
parent_uid: 66889e3c3ee3a40935d5ae63bee525a8
related_resources_text: ''
short_url: huffman-code-1-20-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v9/huffman-code-1-20-
template_type: Embed
title: Huffman Code (1:20)
transcript: <p><span m='1069'>"Optimal"</span> <span m='1499'>sounds</span> <span
  m='1929'>pretty</span> <span m='2359'>good!</span> </p><p><span m='2790'>Does</span>
  <span m='3087'>that</span> <span m='3385'>mean</span> <span m='3682'>we</span> <span
  m='3980'>can't</span> <span m='4277'>do</span> <span m='4575'>any</span> <span m='4872'>better?</span>
  </p><p><span m='5170'>Well,</span> <span m='5766'>not</span> <span m='6363'>by</span>
  <span m='6960'>encoding</span> <span m='7556'>symbols</span> <span m='8153'>one-at-a-time.</span>
  </p><p><span m='8750'>But</span> <span m='9034'>if</span> <span m='9319'>we</span>
  <span m='9604'>want</span> <span m='9889'>to</span> <span m='10174'>encode</span>
  <span m='10459'>long</span> <span m='10744'>sequences</span> <span m='11029'>of</span>
  <span m='11314'>symbols,</span> <span m='11599'>we</span> <span m='11884'>can</span>
  <span m='12169'>reduce</span> <span m='12454'>the</span> <span m='12739'>expected</span>
  <span m='13024'>length</span> <span m='13309'>of</span> <span m='13749'>the</span>
  <span m='14190'>encoding</span> <span m='14631'>by</span> <span m='15071'>working</span>
  <span m='15512'>with,</span> <span m='15953'>say,</span> <span m='16394'>pairs</span>
  <span m='16834'>of</span> <span m='17275'>symbols</span> <span m='17716'>instead</span>
  <span m='18157'>of</span> <span m='18597'>only</span> <span m='19038'>single</span>
  <span m='19479'>symbols.</span> </p><p><span m='19920'>The</span> <span m='20236'>table</span>
  <span m='20553'>below</span> <span m='20870'>shows</span> <span m='21187'>the</span>
  <span m='21504'>probability</span> <span m='21821'>of</span> <span m='22137'>pairs</span>
  <span m='22454'>of</span> <span m='22771'>symbols</span> <span m='23088'>from</span>
  <span m='23405'>our</span> <span m='23722'>example.</span> </p><p><span m='24039'>If</span>
  <span m='24428'>we</span> <span m='24817'>use</span> <span m='25207'>Huffman's</span>
  <span m='25596'>Algorithm</span> <span m='25985'>to</span> <span m='26375'>build</span>
  <span m='26764'>the</span> <span m='27153'>optimal</span> <span m='27543'>variable-length</span>
  <span m='27932'>code</span> <span m='28321'>using</span> <span m='28711'>these</span>
  <span m='29100'>probabilities,</span> <span m='29490'>it</span> <span m='30059'>turns</span>
  <span m='30628'>out</span> <span m='31197'>the</span> <span m='31766'>expected</span>
  <span m='32335'>length</span> <span m='32905'>when</span> <span m='33474'>encoding</span>
  <span m='34043'>pairs</span> <span m='34612'>is</span> <span m='35181'>1.646</span>
  <span m='35750'>bits/symbol.</span> </p><p><span m='36320'>This</span> <span m='36830'>is</span>
  <span m='37340'>a</span> <span m='37850'>small</span> <span m='38360'>improvement</span>
  <span m='38870'>on</span> <span m='39380'>the</span> <span m='39890'>1.667</span>
  <span m='40400'>bits/symbols</span> <span m='40910'>when</span> <span m='41420'>encoding</span>
  <span m='41930'>each</span> <span m='42440'>symbol</span> <span m='42950'>individually.</span>
  </p><p><span m='43460'>And</span> <span m='43807'>we'd</span> <span m='44154'>do</span>
  <span m='44502'>even</span> <span m='44849'>better</span> <span m='45196'>if</span>
  <span m='45544'>we</span> <span m='45891'>encoded</span> <span m='46238'>sequences</span>
  <span m='46586'>of</span> <span m='46933'>length</span> <span m='47280'>3,</span>
  <span m='47628'>and</span> <span m='47975'>so</span> <span m='48322'>on.</span>
  </p><p><span m='48670'>Modern</span> <span m='49075'>file</span> <span m='49480'>compression</span>
  <span m='49886'>algorithms</span> <span m='50291'>use</span> <span m='50696'>an</span>
  <span m='51102'>adaptive</span> <span m='51507'>algorithm</span> <span m='51912'>to</span>
  <span m='52318'>determine</span> <span m='52723'>on-the-fly</span> <span m='53129'>which</span>
  <span m='53550'>sequences</span> <span m='53971'>occur</span> <span m='54392'>frequently</span>
  <span m='54813'>and</span> <span m='55234'>hence</span> <span m='55655'>should</span>
  <span m='56076'>have</span> <span m='56497'>short</span> <span m='56918'>encodings.</span>
  </p><p><span m='57340'>They</span> <span m='57678'>work</span> <span m='58017'>quite</span>
  <span m='58355'>well</span> <span m='58694'>when</span> <span m='59032'>the</span>
  <span m='59371'>data</span> <span m='59709'>has</span> <span m='60048'>many</span>
  <span m='60386'>repeating</span> <span m='60725'>sequences,</span> <span m='61063'>for</span>
  <span m='61402'>example,</span> <span m='61740'>natural</span> <span m='62079'>language</span>
  <span m='62544'>data</span> <span m='63010'>where</span> <span m='63476'>some</span>
  <span m='63942'>letter</span> <span m='64407'>combinations</span> <span m='64873'>or</span>
  <span m='65339'>even</span> <span m='65805'>whole</span> <span m='66271'>words</span>
  <span m='66736'>occur</span> <span m='67202'>again</span> <span m='67668'>and</span>
  <span m='68134'>again.</span> </p><p><span m='68600'>Compression</span> <span m='69003'>can</span>
  <span m='69406'>achieve</span> <span m='69809'>dramatic</span> <span m='70212'>reductions</span>
  <span m='70615'>from</span> <span m='71018'>the</span> <span m='71421'>original</span>
  <span m='71824'>file</span> <span m='72227'>size.</span> </p><p><span m='72630'>If</span>
  <span m='72990'>you'd</span> <span m='73350'>like</span> <span m='73710'>to</span>
  <span m='74070'>learn</span> <span m='74430'>more,</span> <span m='74790'>look</span>
  <span m='75150'>up</span> <span m='75510'>"LZW"</span> <span m='75870'>on</span>
  <span m='76230'>Wikipedia</span> <span m='76590'>to</span> <span m='76950'>read</span>
  <span m='77310'>the</span> <span m='77670'>Lempel-Ziv-Welch</span> <span m='78030'>data</span>
  <span m='78406'>compression</span> <span m='78783'>algorithm.</span> </p>
type: course
uid: 1fa379c46d74cfea11603f5c725bba11

---
None