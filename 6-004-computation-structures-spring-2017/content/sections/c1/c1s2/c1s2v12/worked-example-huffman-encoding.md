---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: cTU43KgGLFw
  parent_uid: 35c84ae9b6cc3db9299f5d2d1e9c93f0
  title: Video-YouTube-Stream
  type: Video
  uid: 8eb8567b6027a3e2b707a4e18c5b01ca
- id: 3Play-3Play YouTube id-Stream
  media_location: cTU43KgGLFw
  parent_uid: 35c84ae9b6cc3db9299f5d2d1e9c93f0
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 852eface4dfead89e7aff8f3ece894e4
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/cTU43KgGLFw/default.jpg
  parent_uid: 35c84ae9b6cc3db9299f5d2d1e9c93f0
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: c28b7eb1f34a3ca0a0dd629fb673e122
- id: cTU43KgGLFw.srt
  parent_uid: 35c84ae9b6cc3db9299f5d2d1e9c93f0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v12/worked-example-huffman-encoding/cTU43KgGLFw.srt
  title: 3play caption file
  type: null
  uid: 03f13e6de5302b27071ea4fb27801f13
- id: cTU43KgGLFw.pdf
  parent_uid: 35c84ae9b6cc3db9299f5d2d1e9c93f0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v12/worked-example-huffman-encoding/cTU43KgGLFw.pdf
  title: 3play pdf file
  type: null
  uid: 7ef8f9b00b4069e308fff26f5de2c529
- id: Caption-3Play YouTube id-SRT
  parent_uid: 35c84ae9b6cc3db9299f5d2d1e9c93f0
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 2d3682c7b3c7b834a28a5a0984efd8e8
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 35c84ae9b6cc3db9299f5d2d1e9c93f0
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: fabb591702fa410693180d6591678bbf
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_01-02-12-04_300k.mp4
  parent_uid: 35c84ae9b6cc3db9299f5d2d1e9c93f0
  title: Video-Internet Archive-MP4
  type: Video
  uid: d2d1fd24db1b83a156f0903178755f8e
inline_embed_id: 27885987huffmanencoding23226569
layout: video
order_index: null
parent_uid: 4405e1adee4c3bf77a4cc2b35d6760ff
related_resources_text: ''
short_url: worked-example-huffman-encoding
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v12/worked-example-huffman-encoding
template_type: Embed
title: 'Worked Example: Huffman Encoding'
transcript: <p><span m="750">This</span> <span m="1740">problems</span> <span m="2200">presents</span>
  <span m="2790">Huffman</span> <span m="3190">Encoding</span> <span m="4059">which</span>
  <span m="4460">produces</span> <span m="5030">variable-length</span> <span m="5890">encodings</span>
  <span m="6620">based</span> <span m="6950">on</span> <span m="7070">the</span> <span
  m="7140">probabilities</span> <span m="8010">of</span> <span m="8090">the</span>
  <span m="8240">occurrence</span> <span m="8820">of</span> <span m="8960">each</span>
  <span m="9240">different</span> <span m="9590">choice.</span></p><p><span m="10710">More</span>
  <span m="10930">likely</span> <span m="11340">choices</span> <span m="11970">will</span>
  <span m="12190">end</span> <span m="12380">up</span> <span m="12530">with</span>
  <span m="12660">shorter</span> <span m="13150">encodings</span> <span m="13870">than</span>
  <span m="14040">less</span> <span m="14350">likely</span> <span m="14670">choices.</span></p><p><span
  m="20030">The</span> <span m="20110">goal</span> <span m="20480">of</span> <span
  m="20590">this</span> <span m="20820">problem</span> <span m="21370">is</span> <span
  m="21570">to</span> <span m="21660">produce</span> <span m="22160">a</span> <span
  m="22200">Huffman</span> <span m="22750">code</span> <span m="23220">to</span> <span
  m="23440">encode</span> <span m="23950">student</span> <span m="24480">choices</span>
  <span m="24960">of</span> <span m="25060">majors.</span></p><p><span m="26280">There</span>
  <span m="26560">are</span> <span m="26590">a</span> <span m="26630">total</span>
  <span m="27060">of</span> <span m="27180">4</span> <span m="27330">majors,</span>
  <span m="28270">and</span> <span m="28590">each</span> <span m="28870">has</span>
  <span m="29070">a</span> <span m="29100">probability</span> <span m="29930">associated</span>
  <span m="30680">with</span> <span m="30950">it.</span></p><p><span m="32049">To</span>
  <span m="32140">produce</span> <span m="32570">a</span> <span m="32610">Huffman</span>
  <span m="33050">encoding,</span> <span m="33920">one</span> <span m="34290">begins</span>
  <span m="34760">with</span> <span m="34900">the</span> <span m="34990">2</span>
  <span m="35160">choices</span> <span m="35790">with</span> <span m="35980">lowest</span>
  <span m="36340">probability.</span></p><p><span m="37950">In</span> <span m="38040">this</span>
  <span m="38250">example,</span> <span m="39120">major</span> <span m="39840">6-7,</span>
  <span m="40310">has</span> <span m="40840">a</span> <span m="40870">probability</span>
  <span m="42090">of</span> <span m="42830">0.06,</span> <span m="43560">and</span>
  <span m="44000">major</span> <span m="44360">6-1,</span> <span m="44430">has</span>
  <span m="45190">a</span> <span m="45700">probability</span> <span m="46790">of</span>
  <span m="46950">0.09.</span></p><p><span m="47080">Since</span> <span m="48310">these</span>
  <span m="49430">are</span> <span m="49530">the</span> <span m="49650">two</span>
  <span m="49890">lowest</span> <span m="50310">probabilities,</span> <span m="51350">these</span>
  <span m="51720">two</span> <span m="51900">choices</span> <span m="52450">are</span>
  <span m="52550">selected</span> <span m="53300">as</span> <span m="53490">the</span>
  <span m="53550">starting</span> <span m="54040">point</span> <span m="54350">for</span>
  <span m="54480">building</span> <span m="54910">our</span> <span m="55090">encoding</span>
  <span m="55620">tree.</span></p><p><span m="56900">The</span> <span m="57060">root</span>
  <span m="57350">node</span> <span m="57660">that</span> <span m="57790">combines</span>
  <span m="58430">the</span> <span m="58510">two</span> <span m="58730">choices,</span>
  <span m="59400">has</span> <span m="59620">a</span> <span m="59660">probability</span>
  <span m="60430">equal</span> <span m="60740">to</span> <span m="60880">the</span>
  <span m="60990">sum</span> <span m="61480">of</span> <span m="61640">the</span>
  <span m="61790">leaf</span> <span m="62090">nodes,</span> <span m="62750">or</span>
  <span m="63160">0.15</span> <span m="63210">in</span> <span m="63930">this</span>
  <span m="64920">example.</span></p><p><span m="66440">We</span> <span m="66610">then</span>
  <span m="66820">label</span> <span m="67250">one</span> <span m="67450">side</span>
  <span m="67730">of</span> <span m="67830">this</span> <span m="68040">tree</span>
  <span m="68290">with</span> <span m="68560">a</span> <span m="68840">0</span> <span
  m="69170">and</span> <span m="69530">the</span> <span m="69690">other</span> <span
  m="69930">with</span> <span m="70190">a</span> <span m="70260">1.</span></p><p><span
  m="70290">The</span> <span m="71060">next</span> <span m="71930">step</span> <span
  m="72350">is</span> <span m="72550">to</span> <span m="72650">find</span> <span
  m="72980">the</span> <span m="73060">next</span> <span m="73390">two</span> <span
  m="73560">smallest</span> <span m="74050">probabilities</span> <span m="74880">out</span>
  <span m="75080">of</span> <span m="75200">the</span> <span m="75300">remaining</span>
  <span m="75840">set</span> <span m="76150">of</span> <span m="76280">probabilities</span>
  <span m="77130">where</span> <span m="77270">majors</span> <span m="78030">6-1</span>
  <span m="78250">and</span> <span m="78560">6-7</span> <span m="78740">have</span>
  <span m="79330">been</span> <span m="79890">replaced</span> <span m="80520">by</span>
  <span m="80720">node</span> <span m="81090">A</span> <span m="81540">which</span>
  <span m="81730">has</span> <span m="81940">probability</span> <span m="83220">0.15.</span></p><p><span
  m="85450">In</span> <span m="85580">this</span> <span m="85820">case,</span> <span
  m="86500">our</span> <span m="86890">lowest</span> <span m="87220">probabilities</span>
  <span m="88180">are</span> <span m="88810">0.15</span> <span m="89580">(which</span>
  <span m="90160">is</span> <span m="90240">the</span> <span m="90330">probability</span>
  <span m="91010">of</span> <span m="91100">node</span> <span m="91450">A)</span>
  <span m="91940">and</span> <span m="92660">0.41</span> <span m="92790">(which</span>
  <span m="93560">is</span> <span m="94150">the</span> <span m="94230">probability</span>
  <span m="94970">of</span> <span m="95070">major</span> <span m="95780">6-3).</span></p><p><span
  m="96760">So</span> <span m="96920">we</span> <span m="97030">create</span> <span
  m="97420">a</span> <span m="97480">new</span> <span m="97690">node</span> <span
  m="98070">B</span> <span m="98610">that</span> <span m="98930">merges</span> <span
  m="99360">nodes</span> <span m="99860">A</span> <span m="100300">and</span> <span
  m="100590">6-3.</span></p><p><span m="101990">This</span> <span m="102190">new</span>
  <span m="102400">node</span> <span m="102740">has</span> <span m="102940">probability</span>
  <span m="104420">0.56.</span></p><p><span m="106100">Again</span> <span m="106480">we</span>
  <span m="106610">label</span> <span m="106920">the</span> <span m="107020">two</span>
  <span m="107270">branches,</span> <span m="107900">one</span> <span m="108120">with</span>
  <span m="108310">a</span> <span m="108540">0</span> <span m="108800">and</span>
  <span m="109050">the</span> <span m="109200">other</span> <span m="109370">with</span>
  <span m="109570">a</span> <span m="110070">1.</span></p><p><span m="110920">We</span>
  <span m="111020">now</span> <span m="111190">repeat</span> <span m="111590">this</span>
  <span m="111790">process</span> <span m="112300">one</span> <span m="112560">last</span>
  <span m="112860">time</span> <span m="113690">with</span> <span m="114290">the</span>
  <span m="114430">only</span> <span m="114750">two</span> <span m="114990">remaining</span>
  <span m="115480">choices</span> <span m="115970">which</span> <span m="116170">are</span>
  <span m="116290">now</span> <span m="116530">node</span> <span m="116810">B</span>
  <span m="117270">and</span> <span m="117480">major</span> <span m="118150">6-2.</span></p><p><span
  m="119290">This</span> <span m="119530">means</span> <span m="119940">that</span>
  <span m="120060">we</span> <span m="120200">should</span> <span m="120400">make</span>
  <span m="120650">a</span> <span m="120690">new</span> <span m="120900">node</span>
  <span m="121210">C</span> <span m="121730">that</span> <span m="121980">merges</span>
  <span m="122390">node</span> <span m="122630">B</span> <span m="122970">and</span>
  <span m="123170">major</span> <span m="123720">6-2.</span></p><p><span m="124990">Note</span>
  <span m="125260">that</span> <span m="125450">the</span> <span m="125530">probability</span>
  <span m="126270">of</span> <span m="126380">this</span> <span m="126590">node</span>
  <span m="127030">is</span> <span m="127620">1.0</span> <span m="128190">because</span>
  <span m="128740">we</span> <span m="128850">have</span> <span m="129020">reached</span>
  <span m="129419">the</span> <span m="129490">top</span> <span m="129870">of</span>
  <span m="130000">our</span> <span m="130150">tree.</span></p><p><span m="131550">Our</span>
  <span m="131620">final</span> <span m="132060">step</span> <span m="132530">is</span>
  <span m="132730">to</span> <span m="132840">label</span> <span m="133290">these</span>
  <span m="133500">last</span> <span m="133810">two</span> <span m="133980">branches.</span></p><p><span
  m="136290">Now</span> <span m="136490">that</span> <span m="136660">all</span> <span
  m="136820">the</span> <span m="136900">branches</span> <span m="137350">are</span>
  <span m="137490">labeled,</span> <span m="138120">we</span> <span m="138380">can</span>
  <span m="138560">traverse</span> <span m="139090">the</span> <span m="139180">tree</span>
  <span m="139500">from</span> <span m="139730">the</span> <span m="139900">root</span>
  <span m="140210">node</span> <span m="140580">to</span> <span m="140750">each</span>
  <span m="141080">leaf</span> <span m="141380">node</span> <span m="141750">in</span>
  <span m="141930">order</span> <span m="142210">to</span> <span m="142370">identify</span>
  <span m="143120">the</span> <span m="143240">encoding</span> <span m="144090">that</span>
  <span m="144390">has</span> <span m="144580">been</span> <span m="144740">assigned</span>
  <span m="145280">to</span> <span m="145390">the</span> <span m="145500">major</span>
  <span m="145960">associated</span> <span m="146770">with</span> <span m="147080">that</span>
  <span m="147320">leaf</span> <span m="147680">node.</span></p><p><span m="148750">We</span>
  <span m="148860">find</span> <span m="149230">that</span> <span m="149350">for</span>
  <span m="149540">major</span> <span m="149940">6-1</span> <span m="150440">the</span>
  <span m="151000">encoding</span> <span m="151880">is</span> <span m="152390">101.</span></p><p><span
  m="153950">For</span> <span m="154070">major</span> <span m="154690">6-2,</span>
  <span m="155330">we</span> <span m="155760">end</span> <span m="155950">up</span>
  <span m="156220">with</span> <span m="156630">a</span> <span m="156660">1-bit</span>
  <span m="156820">encoding</span> <span m="157380">of</span> <span m="157520">0.</span></p><p><span
  m="158770">Next</span> <span m="159160">we</span> <span m="159270">traverse</span>
  <span m="159770">the</span> <span m="159870">tree</span> <span m="160390">to</span>
  <span m="160540">identify</span> <span m="161200">the</span> <span m="161280">last</span>
  <span m="161690">two</span> <span m="161840">encodings</span> <span m="162570">and</span>
  <span m="162740">find</span> <span m="163140">that</span> <span m="163410">for</span>
  <span m="163590">major</span> <span m="164140">6-3</span> <span m="164410">the</span>
  <span m="165000">encoding</span> <span m="166130">11</span> <span m="166390">has</span>
  <span m="166730">been</span> <span m="166880">assigned,</span> <span m="167590">and</span>
  <span m="167890">for</span> <span m="168000">major</span> <span m="168550">6-7</span>
  <span m="169490">the</span> <span m="170370">encoding</span> <span m="170900">100</span>
  <span m="171090">has</span> <span m="171910">been</span> <span m="172350">assigned.</span></p><p><span
  m="173560">These</span> <span m="173770">encodings</span> <span m="174390">make</span>
  <span m="174640">sense</span> <span m="175080">because</span> <span m="175450">we</span>
  <span m="175560">expect</span> <span m="176010">the</span> <span m="176100">major</span>
  <span m="176470">with</span> <span m="176660">the</span> <span m="176720">highest</span>
  <span m="177190">probability,</span> <span m="178190">in</span> <span m="178540">this</span>
  <span m="178740">case</span> <span m="179110">major</span> <span m="179540">6-2</span>
  <span m="179750">to</span> <span m="180420">end</span> <span m="180970">up</span>
  <span m="181120">with</span> <span m="181240">the</span> <span m="181310">shortest</span>
  <span m="181900">encoding.</span></p><p><span m="183110">The</span> <span m="183210">next</span>
  <span m="183520">highest</span> <span m="183860">probability</span> <span m="184550">major</span>
  <span m="185070">is</span> <span m="185560">6-3</span> <span m="185920">so</span>
  <span m="186410">it</span> <span m="186570">ends</span> <span m="186840">up</span>
  <span m="187010">with</span> <span m="187120">the</span> <span m="187180">second</span>
  <span m="187590">shortest</span> <span m="188100">encoding,</span> <span m="188870">and</span>
  <span m="189300">so</span> <span m="189600">on.</span></p><p><span m="192990">We</span>
  <span m="193140">just</span> <span m="193460">saw</span> <span m="193810">that</span>
  <span m="194020">the</span> <span m="194110">encodings</span> <span m="194740">resulting</span>
  <span m="195280">from</span> <span m="195540">this</span> <span m="195800">Huffman</span>
  <span m="196180">encoding</span> <span m="196700">tree</span> <span m="197330">are:</span>
  <span m="197930">101</span> <span m="198090">for</span> <span m="198800">major</span>
  <span m="200130">6-1,</span> <span m="200880">a</span> <span m="201100">0</span>
  <span m="201250">for</span> <span m="201510">major</span> <span m="202140">6-2,</span>
  <span m="202440">11</span> <span m="202810">for</span> <span m="203680">major</span>
  <span m="204680">6-3,</span> <span m="205300">and</span> <span m="206230">100</span>
  <span m="206340">for</span> <span m="206870">major</span> <span m="207550">6-7.</span></p><p><span
  m="208930">Note</span> <span m="209190">that</span> <span m="209520">the</span>
  <span m="209620">Huffman</span> <span m="210010">encoding</span> <span m="210540">tree</span>
  <span m="210740">for</span> <span m="211040">this</span> <span m="211270">problem</span>
  <span m="211950">could</span> <span m="212230">have</span> <span m="212420">also</span>
  <span m="212960">been</span> <span m="213150">drawn</span> <span m="213540">like</span>
  <span m="213770">this.</span></p><p><span m="215460">These</span> <span m="215700">two</span>
  <span m="215890">trees</span> <span m="216270">are</span> <span m="216360">identical</span>
  <span m="216940">in</span> <span m="217030">structure</span> <span m="217730">and</span>
  <span m="217970">result</span> <span m="218390">in</span> <span m="218490">the</span>
  <span m="218550">same</span> <span m="218950">encodings</span> <span m="219660">for</span>
  <span m="219810">the</span> <span m="219900">four</span> <span m="220240">majors.</span></p><p><span
  m="224130">Furthermore,</span> <span m="224990">a</span> <span m="225260">Huffman</span>
  <span m="225690">tree</span> <span m="226000">can</span> <span m="226200">result</span>
  <span m="226650">in</span> <span m="226750">more</span> <span m="227020">than</span>
  <span m="227160">one</span> <span m="227420">valid</span> <span m="227830">encoding.</span></p><p><span
  m="228930">The</span> <span m="229040">only</span> <span m="229340">constraint</span>
  <span m="229970">in</span> <span m="230090">labeling</span> <span m="230680">the</span>
  <span m="230840">edges</span> <span m="231500">is</span> <span m="231780">that</span>
  <span m="231950">from</span> <span m="232200">each</span> <span m="232550">node,</span>
  <span m="232950">there</span> <span m="233200">is</span> <span m="233360">both</span>
  <span m="233720">a</span> <span m="233950">0</span> <span m="234030">branch</span>
  <span m="234560">and</span> <span m="234740">a</span> <span m="234890">1</span>
  <span m="235030">branch</span> <span m="235730">but</span> <span m="236000">there</span>
  <span m="236110">are</span> <span m="236180">no</span> <span m="236420">constraints</span>
  <span m="237030">about</span> <span m="237350">which</span> <span m="237620">side</span>
  <span m="237960">has</span> <span m="238230">to</span> <span m="238320">be</span>
  <span m="238480">labeled</span> <span m="238970">0</span> <span m="239390">and</span>
  <span m="239880">which</span> <span m="240100">side</span> <span m="240440">1.</span></p><p><span
  m="241390">So</span> <span m="241680">for</span> <span m="241930">example,</span>
  <span m="242660">we</span> <span m="242870">could</span> <span m="243090">have</span>
  <span m="243240">chosen</span> <span m="243800">to</span> <span m="243940">label</span>
  <span m="244340">the</span> <span m="244410">left</span> <span m="244750">side</span>
  <span m="245060">of</span> <span m="245160">the</span> <span m="245240">B</span>
  <span m="245470">node</span> <span m="246010">with</span> <span m="246370">a</span>
  <span m="246450">1</span> <span m="246510">and</span> <span m="246940">the</span>
  <span m="247180">right</span> <span m="247430">side</span> <span m="247770">with</span>
  <span m="248070">a</span> <span m="248440">0</span> <span m="248770">instead</span>
  <span m="249230">of</span> <span m="249350">the</span> <span m="249430">way</span>
  <span m="249650">we</span> <span m="249830">originally</span> <span m="250430">labeled</span>
  <span m="250850">them.</span></p><p><span m="251760">Note,</span> <span m="251980">however,</span>
  <span m="252750">that</span> <span m="253070">this</span> <span m="253280">would</span>
  <span m="253390">result</span> <span m="253880">in</span> <span m="253970">a</span>
  <span m="254020">different</span> <span m="254550">but</span> <span m="254800">also</span>
  <span m="255240">valid</span> <span m="255660">Huffman</span> <span m="256100">encoding.</span></p><p><span
  m="257209">In</span> <span m="257360">this</span> <span m="257600">case</span> <span
  m="258170">the</span> <span m="258350">encoding</span> <span m="258880">for</span>
  <span m="259040">major</span> <span m="259660">6-1</span> <span m="260230">is</span>
  <span m="260820">111,</span> <span m="261600">major</span> <span m="262810">6-2</span>
  <span m="263400">remains</span> <span m="264350">0,</span> <span m="264840">major</span>
  <span m="265680">6-3</span> <span m="266230">becomes</span> <span m="267100">10,</span>
  <span m="267150">and</span> <span m="267910">major</span> <span m="268820">6-7</span>
  <span m="269240">becomes</span> <span m="270190">110.</span></p><p><span m="270600">As</span>
  <span m="271590">long</span> <span m="272550">as</span> <span m="272690">one</span>
  <span m="272870">maintains</span> <span m="273430">consistency</span> <span m="274300">across</span>
  <span m="274740">the</span> <span m="274800">selected</span> <span m="275380">tree,</span>
  <span m="276000">a</span> <span m="276330">valid</span> <span m="276750">Huffman</span>
  <span m="277130">encoding</span> <span m="277860">is</span> <span m="278150">produced.</span></p><p><span
  m="280650">We</span> <span m="280780">now</span> <span m="281080">add</span> <span
  m="281340">one</span> <span m="281550">more</span> <span m="281790">column</span>
  <span m="282210">to</span> <span m="282380">our</span> <span m="282520">table</span>
  <span m="283140">which</span> <span m="283470">gives</span> <span m="283860">p</span>
  <span m="284260">*</span> <span m="284430">log2(1/p)</span> <span m="284610">for</span>
  <span m="284950">each</span> <span m="285690">of</span> <span m="286290">the</span>
  <span m="287150">majors.</span></p><p><span m="288850">Using</span> <span m="289180">this</span>
  <span m="289360">information</span> <span m="290220">we</span> <span m="290400">can</span>
  <span m="290580">calculate</span> <span m="291230">the</span> <span m="291380">entropy</span>
  <span m="292110">which</span> <span m="292390">is</span> <span m="292520">the</span>
  <span m="292650">average</span> <span m="293090">amount</span> <span m="293380">of</span>
  <span m="293500">information</span> <span m="294180">contained</span> <span m="294700">in</span>
  <span m="294820">each</span> <span m="295050">message.</span></p><p><span m="296360">This</span>
  <span m="296530">is</span> <span m="296670">calculated</span> <span m="297460">by</span>
  <span m="297640">taking</span> <span m="298060">the</span> <span m="298140">sum</span>
  <span m="298640">of</span> <span m="298860">p</span> <span m="299320">*</span> <span
  m="299730">log2(1/p)</span> <span m="300890">for</span> <span m="302150">all</span>
  <span m="302850">choices</span> <span m="303350">of</span> <span m="303440">majors.</span></p><p><span
  m="304750">For</span> <span m="304860">this</span> <span m="305130">problem,</span>
  <span m="305910">the</span> <span m="306120">entropy</span> <span m="306630">is</span>
  <span m="306870">1.6.</span></p><p><span m="307150">We</span> <span m="308050">can</span>
  <span m="308920">now</span> <span m="309100">also</span> <span m="309430">calculate</span>
  <span m="310070">the</span> <span m="310250">average</span> <span m="310750">bits</span>
  <span m="311020">per</span> <span m="311150">major</span> <span m="311600">of</span>
  <span m="311680">the</span> <span m="311820">encodings</span> <span m="312440">that</span>
  <span m="312560">we</span> <span m="312720">have</span> <span m="312930">identified.</span></p><p><span
  m="314430">This</span> <span m="314620">is</span> <span m="314750">calculated</span>
  <span m="315440">by</span> <span m="315580">multiplying</span> <span m="316210">the</span>
  <span m="316300">number</span> <span m="316700">of</span> <span m="316850">bits</span>
  <span m="317110">in</span> <span m="317230">each</span> <span m="317480">encoding</span>
  <span m="318320">times</span> <span m="318770">the</span> <span m="318840">probability</span>
  <span m="319580">of</span> <span m="319700">that</span> <span m="319890">major.</span></p><p><span
  m="320980">Recall</span> <span m="321460">that</span> <span m="321610">our</span>
  <span m="321750">encoding</span> <span m="322270">for</span> <span m="322410">major</span>
  <span m="323000">6-1</span> <span m="323310">was</span> <span m="323760">111,</span>
  <span m="324380">for</span> <span m="324950">major</span> <span m="325330">6-2</span>
  <span m="325410">it</span> <span m="326000">was</span> <span m="326540">0,</span>
  <span m="326570">for</span> <span m="327110">major</span> <span m="327840">6-3</span>
  <span m="328080">it</span> <span m="328710">was</span> <span m="329040">10,</span>
  <span m="329110">and</span> <span m="329780">finally</span> <span m="330660">for</span>
  <span m="330830">major</span> <span m="331360">6-7</span> <span m="331670">it</span>
  <span m="332380">was</span> <span m="333160">110.</span></p><p><span m="334190">This</span>
  <span m="334390">means</span> <span m="334680">that</span> <span m="334840">the</span>
  <span m="334930">average</span> <span m="335340">bits</span> <span m="335590">per</span>
  <span m="335730">major</span> <span m="336240">is</span> <span m="336750">3</span>
  <span m="336910">times</span> <span m="337600">0.09</span> <span m="337730">plus</span>
  <span m="338360">1</span> <span m="338520">times</span> <span m="339050">0.44</span>
  <span m="339270">plus</span> <span m="339810">2</span> <span m="339980">times</span>
  <span m="341020">0.41</span> <span m="342090">plus</span> <span m="342970">3</span>
  <span m="343130">times</span> <span m="343800">0.06</span> <span m="343990">=</span>
  <span m="344340">0.27</span> <span m="344530">plus</span> <span m="345280">0.44</span>
  <span m="345640">plus</span> <span m="346480">0.82</span> <span m="347350">plus</span>
  <span m="348490">0.18</span> <span m="348940">which</span> <span m="349510">equals</span>
  <span m="350050">1.71.</span></p><p><span m="350150">Note</span> <span m="350550">that</span>
  <span m="352930">this</span> <span m="353310">is</span> <span m="353760">slightly</span>
  <span m="355710">larger</span> <span m="356820">than</span> <span m="359350">the</span>
  <span m="360020">entropy</span> <span m="361200">which</span> <span m="361390">is</span>
  <span m="361980">1.6.</span></p><p><span m="363150">This</span> <span m="363350">occurs</span>
  <span m="363940">because</span> <span m="364390">while</span> <span m="364600">Huffman</span>
  <span m="364990">encoding</span> <span m="365590">is</span> <span m="365730">an</span>
  <span m="365830">efficient</span> <span m="366320">encoding</span> <span m="366800">which</span>
  <span m="367050">gets</span> <span m="367320">us</span> <span m="367520">most</span>
  <span m="367950">of</span> <span m="368070">the</span> <span m="368140">way</span>
  <span m="368380">there,</span> <span m="369030">there</span> <span m="369420">are</span>
  <span m="369460">still</span> <span m="369740">some</span> <span m="370110">inefficiencies</span>
  <span m="371070">present</span> <span m="371510">in</span> <span m="371620">Huffman</span>
  <span m="372040">encoding</span> <span m="372850">because</span> <span m="373500">it</span>
  <span m="373770">is</span> <span m="374010">only</span> <span m="374330">encoding</span>
  <span m="374950">one</span> <span m="375220">major</span> <span m="375550">at</span>
  <span m="375710">a</span> <span m="375800">time</span> <span m="376590">rather</span>
  <span m="377190">than</span> <span m="377440">also</span> <span m="377800">considering</span>
  <span m="378440">the</span> <span m="378510">probabilities</span> <span m="379330">associated</span>
  <span m="380140">with</span> <span m="380440">seeing</span> <span m="380760">a</span>
  <span m="380820">particular</span> <span m="381490">sequence</span> <span m="382140">of</span>
  <span m="382240">majors</span> <span m="383070">in</span> <span m="383390">a</span>
  <span m="383430">message</span> <span m="383880">that</span> <span m="384050">conveys</span>
  <span m="384670">the</span> <span m="384760">major</span> <span m="385180">selected</span>
  <span m="385790">for</span> <span m="386000">a</span> <span m="386030">large</span>
  <span m="386520">number</span> <span m="386930">of</span> <span m="387030">students.</span></p>
type: course
uid: 35c84ae9b6cc3db9299f5d2d1e9c93f0

---
None