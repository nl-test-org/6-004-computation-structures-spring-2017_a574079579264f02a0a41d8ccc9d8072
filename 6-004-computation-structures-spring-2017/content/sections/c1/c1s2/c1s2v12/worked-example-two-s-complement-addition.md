---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: ydboHy_yNts
  parent_uid: de13a99e81fbecdd34fbc62dd7fa2252
  title: Video-YouTube-Stream
  type: Video
  uid: c75a14462664d2abb9abae872623da6b
- id: 3Play-3Play YouTube id-Stream
  media_location: ydboHy_yNts
  parent_uid: de13a99e81fbecdd34fbc62dd7fa2252
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 84a4abc979751dfe6d809095a2f3bb8c
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/ydboHy_yNts/default.jpg
  parent_uid: de13a99e81fbecdd34fbc62dd7fa2252
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 6d32d271cb185bcb33569aec8808ae1d
- id: ydboHy_yNts.srt
  parent_uid: de13a99e81fbecdd34fbc62dd7fa2252
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v12/worked-example-two-s-complement-addition/ydboHy_yNts.srt
  title: 3play caption file
  type: null
  uid: d0701ef040ee44e146e600c335f3ba64
- id: ydboHy_yNts.pdf
  parent_uid: de13a99e81fbecdd34fbc62dd7fa2252
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v12/worked-example-two-s-complement-addition/ydboHy_yNts.pdf
  title: 3play pdf file
  type: null
  uid: b2e1e03d3161bdd4cf303aa5401e4a54
- id: Caption-3Play YouTube id-SRT
  parent_uid: de13a99e81fbecdd34fbc62dd7fa2252
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b4eeeed2e8a3ede0f9eef050baaff705
- id: Transcript-3Play YouTube id-PDF
  parent_uid: de13a99e81fbecdd34fbc62dd7fa2252
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 6c621674258e0ee3be8582fc6153a21f
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_01-02-12-03_300k.mp4
  parent_uid: de13a99e81fbecdd34fbc62dd7fa2252
  title: Video-Internet Archive-MP4
  type: Video
  uid: 5bc9dc1d40e4500df595a8ab28d51f80
inline_embed_id: 38444230twoscomplementaddition59643049
layout: video
order_index: null
parent_uid: 4405e1adee4c3bf77a4cc2b35d6760ff
related_resources_text: ''
short_url: worked-example-two-s-complement-addition
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v12/worked-example-two-s-complement-addition
template_type: Embed
title: 'Worked Example: Two''s Complement Addition'
transcript: <p><span m="1829">The</span> <span m="2156">nice</span> <span m="2484">feature</span>
  <span m="2811">of</span> <span m="3139">two's</span> <span m="3466">complement</span>
  <span m="3794">representation</span> <span m="4121">is</span> <span m="4449">that</span>
  <span m="4776">it</span> <span m="5104">allows</span> <span m="5431">you</span>
  <span m="5759">to</span> <span m="6086">do</span> <span m="6414">both</span> <span
  m="6741">addition</span> <span m="7069">and</span> <span m="7554">subtraction</span>
  <span m="8039">as</span> <span m="8524">addition</span> <span m="9009">problems,</span>
  <span m="9494">by</span> <span m="9979">simply</span> <span m="10464">turning</span>
  <span m="10949">the</span> <span m="11434">subtraction</span> <span m="11919">problem</span>
  <span m="12404">A-B</span> <span m="12889">into</span> <span m="13374">an</span>
  <span m="13860">addition</span> <span m="14508">problem</span> <span m="15156">of</span>
  <span m="15805">A</span> <span m="16453">+</span> <span m="17101">(-B).</span></p><p><span
  m="17750">Since</span> <span m="18058">we</span> <span m="18366">now</span> <span
  m="18674">know</span> <span m="18982">how</span> <span m="19290">to</span> <span
  m="19598">easily</span> <span m="19906">negate</span> <span m="20215">values</span>
  <span m="20523">in</span> <span m="20831">two's</span> <span m="21139">complement,</span>
  <span m="21447">this</span> <span m="21755">is</span> <span m="22063">pretty</span>
  <span m="22371">straight</span> <span m="22680">forward.</span></p><p><span m="23820">For</span>
  <span m="24472">example,</span> <span m="25125">let's</span> <span m="25777">perform</span>
  <span m="26430">15</span> <span m="27082">-</span> <span m="27735">18</span> <span
  m="28387">using</span> <span m="29040">6-bit</span> <span m="29692">two's</span>
  <span m="30345">complement</span> <span m="30997">representation.</span></p><p><span
  m="31650">15-18</span> <span m="32990">=</span> <span m="34330">15</span> <span
  m="35670">+</span> <span m="37010">(-18)</span> <span m="38350">15</span> <span
  m="39690">=</span> <span m="41030">001111</span> <span m="42370">18</span> <span
  m="43361">=</span> <span m="44353">010010</span> <span m="45344">To</span> <span
  m="46336">convert</span> <span m="47327">18</span> <span m="48319">to</span> <span
  m="49310">-18,</span> <span m="50302">we</span> <span m="51293">flip</span> <span
  m="52285">all</span> <span m="53276">the</span> <span m="54268">bits</span> <span
  m="55260">and</span> <span m="55816">add</span> <span m="56373">one.</span></p><p><span
  m="56930">This</span> <span m="57881">results</span> <span m="58832">in</span> <span
  m="59783">101110</span> <span m="60735">which</span> <span m="61686">is</span> <span
  m="62637">=</span> <span m="63588">-18.</span></p><p><span m="64540">We</span> <span
  m="64908">can</span> <span m="65276">now</span> <span m="65644">take</span> <span
  m="66012">our</span> <span m="66380">two's</span> <span m="66748">complement</span>
  <span m="67116">representation</span> <span m="67485">of</span> <span m="67853">our</span>
  <span m="68221">two</span> <span m="68589">numbers</span> <span m="68957">and</span>
  <span m="69325">add</span> <span m="69693">them</span> <span m="70061">together.</span></p><p><span
  m="70430">Whenever</span> <span m="70795">we</span> <span m="71160">add</span> <span
  m="71525">1</span> <span m="71891">+</span> <span m="72256">1</span> <span m="72621">in</span>
  <span m="72987">binary</span> <span m="73352">that</span> <span m="73717">produces</span>
  <span m="74082">a</span> <span m="74448">0</span> <span m="74813">plus</span> <span
  m="75178">a</span> <span m="75544">carry</span> <span m="75909">of</span> <span
  m="76274">1.</span></p><p><span m="76640">So</span> <span m="77248">our</span> <span
  m="77856">final</span> <span m="78464">sum</span> <span m="79072">is</span> <span
  m="79680">111101.</span></p><p><span m="80289">To</span> <span m="80780">see</span>
  <span m="81271">what</span> <span m="81762">this</span> <span m="82254">number</span>
  <span m="82745">is</span> <span m="83236">equal</span> <span m="83728">to,</span>
  <span m="84219">we</span> <span m="84710">again</span> <span m="85202">flip</span>
  <span m="85693">the</span> <span m="86184">bits</span> <span m="86676">and</span>
  <span m="87167">add</span> <span m="87658">one.</span></p><p><span m="88150">Flipping</span>
  <span m="88785">the</span> <span m="89421">bits,</span> <span m="90057">we</span>
  <span m="90693">get</span> <span m="91329">000010,</span> <span m="91965">and</span>
  <span m="92601">adding</span> <span m="93237">one</span> <span m="93872">to</span>
  <span m="94508">that</span> <span m="95144">we</span> <span m="95780">get</span>
  <span m="96416">000011</span> <span m="97052">which</span> <span m="97688">equals</span>
  <span m="98324">3.</span></p><p><span m="98960">Which</span> <span m="99556">means</span>
  <span m="100152">that</span> <span m="100748">111101</span> <span m="101345">=</span>
  <span m="101941">-3</span> <span m="102537">which</span> <span m="103133">is</span>
  <span m="103730">the</span> <span m="104326">result</span> <span m="104922">we</span>
  <span m="105518">expected</span> <span m="106115">to</span> <span m="106711">get</span>
  <span m="107307">when</span> <span m="107903">performing</span> <span m="108500">15-18.</span></p><p><span
  m="115090">Let's</span> <span m="115760">try</span> <span m="116430">another</span>
  <span m="117100">example:</span> <span m="117770">27</span> <span m="118440">-</span>
  <span m="119110">6</span> <span m="119780">=</span> <span m="120450">27</span> <span
  m="121120">+</span> <span m="121790">(-6)</span> <span m="122460">27</span> <span
  m="122975">is</span> <span m="123491">equal</span> <span m="124006">to</span> <span
  m="124522">16</span> <span m="125037">+</span> <span m="125553">8</span> <span m="126068">+</span>
  <span m="126584">2</span> <span m="127099">+</span> <span m="127615">1</span> <span
  m="128130">which</span> <span m="128646">is</span> <span m="129161">equal</span>
  <span m="129677">to</span> <span m="130192">24</span> <span m="130708">+</span>
  <span m="131223">23</span> <span m="131739">+</span> <span m="132254">21</span>
  <span m="132770">+</span> <span m="133600">20.</span></p><p><span m="134430">So</span>
  <span m="134986">in</span> <span m="135543">two's</span> <span m="136100">complement</span>
  <span m="136656">representation</span> <span m="137213">this</span> <span m="137770">number</span>
  <span m="138326">is</span> <span m="138883">011011.</span></p><p><span m="139440">6</span>
  <span m="139988">is</span> <span m="140537">equal</span> <span m="141086">to</span>
  <span m="141635">4</span> <span m="142184">+</span> <span m="142733">2</span> <span
  m="143282">which</span> <span m="143831">is</span> <span m="144380">equal</span>
  <span m="144929">to</span> <span m="145478">22</span> <span m="146027">+</span>
  <span m="146576">21,</span> <span m="147125">so</span> <span m="147674">its</span>
  <span m="148223">6-bit</span> <span m="148772">binary</span> <span m="149321">representation</span>
  <span m="149870">is</span> <span m="151835">000110.</span></p><p><span m="153800">To</span>
  <span m="154170">find</span> <span m="154541">the</span> <span m="154911">representation</span>
  <span m="155282">of</span> <span m="155653">negative</span> <span m="156023">six,</span>
  <span m="156394">we</span> <span m="156765">flip</span> <span m="157135">all</span>
  <span m="157506">the</span> <span m="157876">bits</span> <span m="158247">and</span>
  <span m="158618">add</span> <span m="158988">one</span> <span m="159359">resulting</span>
  <span m="159730">in</span> <span m="161700">111010.</span></p><p><span m="163670">When</span>
  <span m="164052">we</span> <span m="164434">add</span> <span m="164817">these</span>
  <span m="165199">two</span> <span m="165582">numbers</span> <span m="165964">together,</span>
  <span m="166347">remembering</span> <span m="166729">that</span> <span m="167112">in</span>
  <span m="167494">binary</span> <span m="167876">1</span> <span m="168259">+</span>
  <span m="168641">1</span> <span m="169024">produces</span> <span m="169406">a</span>
  <span m="169789">0</span> <span m="170171">plus</span> <span m="170554">a</span>
  <span m="170936">carry</span> <span m="171319">of</span> <span m="171737">1,</span>
  <span m="172155">we</span> <span m="172574">find</span> <span m="172992">that</span>
  <span m="173411">our</span> <span m="173829">result</span> <span m="174247">ends</span>
  <span m="174666">up</span> <span m="175084">having</span> <span m="175503">7</span>
  <span m="175921">bits.</span></p><p><span m="176340">This</span> <span m="176684">most</span>
  <span m="177028">significant</span> <span m="177372">bit</span> <span m="177717">is</span>
  <span m="178061">dropped</span> <span m="178405">because</span> <span m="178750">we</span>
  <span m="179094">are</span> <span m="179438">working</span> <span m="179782">with</span>
  <span m="180127">6-bit</span> <span m="180471">representation</span> <span m="180815">in</span>
  <span m="181160">this</span> <span m="181830">case.</span></p><p><span m="182500">So</span>
  <span m="183196">our</span> <span m="183893">final</span> <span m="184590">result</span>
  <span m="185286">is</span> <span m="185983">010101</span> <span m="186680">which</span>
  <span m="187376">is</span> <span m="188073">equal</span> <span m="188770">to</span>
  <span m="189466">24</span> <span m="190163">+</span> <span m="190860">22</span>
  <span m="191556">+</span> <span m="192253">20</span> <span m="192950">which</span>
  <span m="194305">equal</span> <span m="195661">16</span> <span m="197016">+</span>
  <span m="198372">4</span> <span m="199727">+</span> <span m="201083">1</span> <span
  m="202438">or</span> <span m="203794">21.</span></p><p><span m="205150">If</span>
  <span m="205407">you</span> <span m="205665">try</span> <span m="205922">adding</span>
  <span m="206180">two</span> <span m="206438">numbers</span> <span m="206695">whose</span>
  <span m="206953">result</span> <span m="207211">is</span> <span m="207468">beyond</span>
  <span m="207726">the</span> <span m="207984">range</span> <span m="208241">of</span>
  <span m="208499">numbers</span> <span m="208757">that</span> <span m="209014">can</span>
  <span m="209272">be</span> <span m="209530">represented</span> <span m="210182">using</span>
  <span m="210835">your</span> <span m="211487">N-bit</span> <span m="212140">representation,</span>
  <span m="212793">then</span> <span m="213445">that</span> <span m="214098">means</span>
  <span m="214751">that</span> <span m="215403">overflow</span> <span m="216056">occurred.</span></p><p><span
  m="216709">Overflow</span> <span m="216980">can</span> <span m="217251">be</span>
  <span m="217522">detected</span> <span m="217793">by</span> <span m="218064">looking</span>
  <span m="218336">at</span> <span m="218607">the</span> <span m="218878">sign</span>
  <span m="219149">of</span> <span m="219420">the</span> <span m="219691">two</span>
  <span m="219963">numbers</span> <span m="220234">being</span> <span m="220505">added</span>
  <span m="220776">and</span> <span m="221047">the</span> <span m="221319">sign</span>
  <span m="221781">of</span> <span m="222243">the</span> <span m="222705">resulting</span>
  <span m="223167">number.</span></p><p><span m="223629">If</span> <span m="223947">you</span>
  <span m="224265">try</span> <span m="224583">adding</span> <span m="224902">two</span>
  <span m="225220">positive</span> <span m="225538">numbers</span> <span m="225857">(where</span>
  <span m="226175">the</span> <span m="226493">most</span> <span m="226811">significant</span>
  <span m="227130">bit</span> <span m="227448">is</span> <span m="227766">0)</span>
  <span m="228085">and</span> <span m="228403">your</span> <span m="228721">result</span>
  <span m="229040">ends</span> <span m="229497">up</span> <span m="229955">being</span>
  <span m="230413">negative</span> <span m="230871">(your</span> <span m="231329">most</span>
  <span m="231787">significant</span> <span m="232245">bit</span> <span m="232702">is</span>
  <span m="233160">a</span> <span m="233618">1),</span> <span m="234076">then</span>
  <span m="234534">overflow</span> <span m="234992">occurred.</span></p><p><span m="235450">Similarly</span>
  <span m="235798">if</span> <span m="236146">you</span> <span m="236494">try</span>
  <span m="236842">adding</span> <span m="237190">two</span> <span m="237538">negative</span>
  <span m="237886">numbers</span> <span m="238234">whose</span> <span m="238582">most</span>
  <span m="238930">significant</span> <span m="239278">bit</span> <span m="239626">is</span>
  <span m="239974">one,</span> <span m="240322">and</span> <span m="240670">you</span>
  <span m="241019">end</span> <span m="241370">up</span> <span m="241722">with</span>
  <span m="242074">a</span> <span m="242425">result</span> <span m="242777">that</span>
  <span m="243129">is</span> <span m="243480">positive</span> <span m="243832">(where</span>
  <span m="244184">the</span> <span m="244535">most</span> <span m="244887">significant</span>
  <span m="245239">bit</span> <span m="245590">is</span> <span m="245942">0)</span>
  <span m="246294">then</span> <span m="246645">once</span> <span m="246997">again</span>
  <span m="247349">overflow</span> <span m="248489">occurred.</span></p><p><span m="249629">Overflow</span>
  <span m="250051">cannot</span> <span m="250473">occur</span> <span m="250895">when</span>
  <span m="251317">you</span> <span m="251739">add</span> <span m="252161">a</span>
  <span m="252583">positive</span> <span m="253005">and</span> <span m="253427">negative</span>
  <span m="253849">number</span> <span m="254271">that</span> <span m="254693">are</span>
  <span m="255115">within</span> <span m="255537">range.</span></p><p><span m="255959">Let's</span>
  <span m="256232">take</span> <span m="256505">a</span> <span m="256779">look</span>
  <span m="257052">at</span> <span m="257326">an</span> <span m="257599">example</span>
  <span m="257873">of</span> <span m="258146">this.</span></p><p><span m="258420">Suppose</span>
  <span m="258985">we</span> <span m="259550">try</span> <span m="260116">adding</span>
  <span m="260681">31</span> <span m="261246">+</span> <span m="261812">12</span>
  <span m="262377">using</span> <span m="262942">6-bit</span> <span m="263508">two's</span>
  <span m="264073">complement.</span></p><p><span m="264639">This</span> <span m="265135">results</span>
  <span m="265631">in</span> <span m="266127">101011</span> <span m="266624">which</span>
  <span m="267120">has</span> <span m="267616">its</span> <span m="268113">most</span>
  <span m="268609">significant</span> <span m="269105">bit</span> <span m="269602">equal</span>
  <span m="270098">to</span> <span m="270594">1</span> <span m="271091">even</span>
  <span m="271587">though</span> <span m="272083">we</span> <span m="272580">were</span>
  <span m="273109">adding</span> <span m="273639">two</span> <span m="274169">positive</span>
  <span m="274699">numbers.</span></p><p><span m="275229">This</span> <span m="275855">means</span>
  <span m="276481">that</span> <span m="277107">overflow</span> <span m="277733">occurred.</span></p><p><span
  m="278360">Overflow</span> <span m="278755">occurred</span> <span m="279150">because</span>
  <span m="279545">the</span> <span m="279940">result</span> <span m="280335">of</span>
  <span m="280730">adding</span> <span m="281125">these</span> <span m="281520">two</span>
  <span m="281915">numbers</span> <span m="282310">is</span> <span m="282705">43</span>
  <span m="283100">which</span> <span m="283495">is</span> <span m="283890">larger</span>
  <span m="284285">than</span> <span m="284680">2</span> <span m="285067">to</span>
  <span m="285455">the</span> <span m="285843">5th</span> <span m="286231">minus</span>
  <span m="286619">1,</span> <span m="287007">or</span> <span m="287395">31,</span>
  <span m="287783">which</span> <span m="288171">is</span> <span m="288558">the</span>
  <span m="288946">largest</span> <span m="289334">positive</span> <span m="289722">number</span>
  <span m="290110">that</span> <span m="290498">can</span> <span m="290886">be</span>
  <span m="291274">represented</span> <span m="291662">using</span> <span m="292050">6-bits</span>
  <span m="292586">two's</span> <span m="293122">complement.</span></p>
type: course
uid: de13a99e81fbecdd34fbc62dd7fa2252

---
None