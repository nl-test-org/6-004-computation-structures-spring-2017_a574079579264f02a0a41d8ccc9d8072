---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: M278hILkZlE
  parent_uid: 4f9c7b659420d7101e0f99b7c0436be3
  title: Video-YouTube-Stream
  type: Video
  uid: 80d5fd05ed5406584042d8b6c19d4353
- id: 3Play-3Play YouTube id-Stream
  media_location: M278hILkZlE
  parent_uid: 4f9c7b659420d7101e0f99b7c0436be3
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: c07e4b93866e1143bc51e6a1673a6125
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/M278hILkZlE/default.jpg
  parent_uid: 4f9c7b659420d7101e0f99b7c0436be3
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 68b003d3dbf05f53619c52ea0f54b8f8
- id: M278hILkZlE.srt
  parent_uid: 4f9c7b659420d7101e0f99b7c0436be3
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c10/c10s2/c10s2v8/beta-assembly/M278hILkZlE.srt
  title: 3play caption file
  type: null
  uid: 52d95712bf0f6388f07b8b04a35c21b3
- id: M278hILkZlE.pdf
  parent_uid: 4f9c7b659420d7101e0f99b7c0436be3
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c10/c10s2/c10s2v8/beta-assembly/M278hILkZlE.pdf
  title: 3play pdf file
  type: null
  uid: 381a56848f2c1a2138f52bb4630ca4bc
- id: Caption-3Play YouTube id-SRT
  parent_uid: 4f9c7b659420d7101e0f99b7c0436be3
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 3064b32b88a6c2507acc364955b5532a
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 4f9c7b659420d7101e0f99b7c0436be3
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 02c3df8a06a2c38043838eb322d7ebbd
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_10-02-08-01_300k.mp4
  parent_uid: 4f9c7b659420d7101e0f99b7c0436be3
  title: Video-Internet Archive-MP4
  type: Video
  uid: f0c67f55ebc2893057c61d55c76944c4
inline_embed_id: 56045521betaassembly18393304
layout: video
order_index: null
parent_uid: a7b0f24d5a1d918f76d6d5d3e8d03a5e
related_resources_text: ''
short_url: beta-assembly
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c10/c10s2/c10s2v8/beta-assembly
template_type: Embed
title: 'Worked Example: Beta Assembly'
transcript: <p><span m="370">As</span> <span m="810">presented</span> <span m="1250">in</span>
  <span m="1690">lecture,</span> <span m="2130">in</span> <span m="2570">this</span>
  <span m="3010">course,</span> <span m="3450">we</span> <span m="3890">use</span>
  <span m="4330">a</span> <span m="4770">simple</span> <span m="5210">32-bit</span>
  <span m="5650">processor</span> <span m="6090">called</span> <span m="6530">the</span>
  <span m="6970">Beta.</span></p><p><span m="7410">The</span> <span m="7874">Beta</span>
  <span m="8338">works</span> <span m="8803">on</span> <span m="9267">32-bit</span>
  <span m="9732">instruction</span> <span m="10196">and</span> <span m="10661">data</span>
  <span m="11125">words.</span></p><p><span m="11590">However,</span> <span m="12024">the</span>
  <span m="12458">addresses</span> <span m="12893">in</span> <span m="13327">memory</span>
  <span m="13762">are</span> <span m="14196">specified</span> <span m="14631">in</span>
  <span m="15065">bytes.</span></p><p><span m="15500">A</span> <span m="15956">byte</span>
  <span m="16413">is</span> <span m="16870">made</span> <span m="17327">up</span>
  <span m="17784">of</span> <span m="18241">8</span> <span m="18698">bits,</span>
  <span m="19155">so</span> <span m="19611">each</span> <span m="20068">32-bit</span>
  <span m="20525">instruction</span> <span m="20982">consists</span> <span m="21439">of</span>
  <span m="21896">4</span> <span m="22353">bytes.</span></p><p><span m="22810">That</span>
  <span m="23170">means</span> <span m="23530">that</span> <span m="23890">if</span>
  <span m="24250">you</span> <span m="24610">have</span> <span m="24970">two</span>
  <span m="25330">instructions</span> <span m="25690">A</span> <span m="26050">and</span>
  <span m="26410">B</span> <span m="26770">in</span> <span m="27130">consecutive</span>
  <span m="27490">memory</span> <span m="27850">locations,</span> <span m="28210">if</span>
  <span m="28570">A</span> <span m="29213">is</span> <span m="29857">at</span> <span
  m="30500">address</span> <span m="31144">0x100,</span> <span m="31787">then</span>
  <span m="32431">B</span> <span m="33074">is</span> <span m="33718">at</span> <span
  m="34361">address</span> <span m="35005">0x104.</span></p><p><span m="35649">Now,</span>
  <span m="36260">suppose</span> <span m="36871">that</span> <span m="37482">you</span>
  <span m="38093">are</span> <span m="38704">given</span> <span m="39315">the</span>
  <span m="39926">following</span> <span m="40537">piece</span> <span m="41148">of</span>
  <span m="41759">code.</span></p><p><span m="42370">The</span> <span m="42702">.</span>
  <span m="43034">=</span> <span m="43366">0</span> <span m="43698">notation</span>
  <span m="44030">tells</span> <span m="44362">you</span> <span m="44694">that</span>
  <span m="45026">your</span> <span m="45358">program</span> <span m="45690">begins</span>
  <span m="46022">at</span> <span m="46354">address</span> <span m="46686">0.</span></p><p><span
  m="47019">You</span> <span m="47380">can</span> <span m="47742">assume</span> <span
  m="48104">that</span> <span m="48466">execution</span> <span m="48828">begins</span>
  <span m="49190">at</span> <span m="49552">this</span> <span m="49914">location</span>
  <span m="50275">0</span> <span m="50637">and</span> <span m="50999">halts</span>
  <span m="51361">when</span> <span m="51723">the</span> <span m="52085">HALT()</span>
  <span m="52447">instruction</span> <span m="52809">is</span> <span m="53337">about</span>
  <span m="53865">to</span> <span m="54393">be</span> <span m="54921">executed.</span></p><p><span
  m="55449">We</span> <span m="55762">want</span> <span m="56075">to</span> <span
  m="56388">determine</span> <span m="56701">what</span> <span m="57014">value</span>
  <span m="57328">ends</span> <span m="57641">up</span> <span m="57954">in</span>
  <span m="58267">R0</span> <span m="58580">after</span> <span m="58894">this</span>
  <span m="59207">instruction</span> <span m="59520">sequence</span> <span m="59833">has</span>
  <span m="60146">been</span> <span m="60460">executed.</span></p><p><span m="62290">Note</span>
  <span m="62573">that</span> <span m="62857">we</span> <span m="63141">are</span>
  <span m="63425">working</span> <span m="63708">with</span> <span m="63992">hexadecimal</span>
  <span m="64276">numbers</span> <span m="64560">in</span> <span m="64843">this</span>
  <span m="65127">code</span> <span m="65411">and</span> <span m="65695">we</span>
  <span m="65978">want</span> <span m="66262">our</span> <span m="66546">answer</span>
  <span m="66830">to</span> <span m="67444">also</span> <span m="68058">be</span>
  <span m="68672">in</span> <span m="69286">hexadecimal.</span></p><p><span m="69900">This</span>
  <span m="70378">code</span> <span m="70856">begins</span> <span m="71334">with</span>
  <span m="71812">a</span> <span m="72290">LD</span> <span m="72768">operation</span>
  <span m="73246">into</span> <span m="73724">register</span> <span m="74202">R0.</span></p><p><span
  m="74680">The</span> <span m="75082">load,</span> <span m="75485">uses</span> <span
  m="75887">the</span> <span m="76290">value</span> <span m="76692">of</span> <span
  m="77095">R31</span> <span m="77497">+</span> <span m="77900">c</span> <span m="78302">as</span>
  <span m="78705">the</span> <span m="79107">source</span> <span m="79510">address</span>
  <span m="79912">for</span> <span m="80315">the</span> <span m="80717">load.</span></p><p><span
  m="81120">Since</span> <span m="81570">R31</span> <span m="82020">=</span> <span
  m="82470">0,</span> <span m="82920">this</span> <span m="83370">means</span> <span
  m="83820">that</span> <span m="84270">the</span> <span m="84720">value</span> <span
  m="85170">stored</span> <span m="85620">at</span> <span m="86070">address</span>
  <span m="86520">c</span> <span m="86970">is</span> <span m="87420">being</span>
  <span m="87870">loaded</span> <span m="88320">into</span> <span m="88770">R0.</span></p><p><span
  m="89220">So</span> <span m="90111">after</span> <span m="91002">the</span> <span
  m="91894">LD,</span> <span m="92785">R0</span> <span m="93677">=</span> <span m="94568">0x300.</span></p><p><span
  m="95460">Next</span> <span m="95813">an</span> <span m="96167">ADDC</span> <span
  m="96521">of</span> <span m="96875">R0</span> <span m="97229">with</span> <span
  m="97583">the</span> <span m="97937">constant</span> <span m="98291">b</span> <span
  m="98645">is</span> <span m="98998">performed</span> <span m="99352">and</span>
  <span m="99706">that</span> <span m="100060">result</span> <span m="100414">is</span>
  <span m="100768">stored</span> <span m="101122">back</span> <span m="101476">into</span>
  <span m="101830">R0.</span></p><p><span m="104539">The</span> <span m="105133">.=0x200</span>
  <span m="105727">notation</span> <span m="106321">immediately</span> <span m="106915">preceding</span>
  <span m="107509">the</span> <span m="108103">&quot;a&quot;</span> <span m="108697">label,</span>
  <span m="109291">tells</span> <span m="109885">us</span> <span m="110479">that</span>
  <span m="111073">address</span> <span m="111667">a</span> <span m="112261">=</span>
  <span m="112855">0x200.</span></p><p><span m="113450">This</span> <span m="114241">means</span>
  <span m="115033">that</span> <span m="115825">address</span> <span m="116617">b</span>
  <span m="117409">=</span> <span m="118200">0x204,</span> <span m="118992">and</span>
  <span m="119784">c</span> <span m="120576">=</span> <span m="121368">0x208.</span></p><p><span
  m="122160">So</span> <span m="122968">if</span> <span m="123776">we</span> <span
  m="124584">are</span> <span m="125393">adding</span> <span m="126201">the</span>
  <span m="127009">constant</span> <span m="127817">b</span> <span m="128626">to</span>
  <span m="129434">R0,</span> <span m="130242">R0</span> <span m="131051">now</span>
  <span m="131859">becomes</span> <span m="132667">0x300</span> <span m="133475">+</span>
  <span m="134284">0x204</span> <span m="135092">=</span> <span m="135900">0x504.</span></p><p><span
  m="136709">Now</span> <span m="137016">lets</span> <span m="137323">take</span>
  <span m="137631">a</span> <span m="137938">look</span> <span m="138245">at</span>
  <span m="138553">this</span> <span m="138860">short</span> <span m="139167">piece</span>
  <span m="139475">of</span> <span m="139782">code.</span></p><p><span m="140090">Our</span>
  <span m="140661">goal</span> <span m="141233">is</span> <span m="141805">to</span>
  <span m="142376">determine</span> <span m="142948">the</span> <span m="143520">value</span>
  <span m="144091">left</span> <span m="144663">in</span> <span m="145235">R0</span>
  <span m="145806">in</span> <span m="146378">hexadecimal.</span></p><p><span m="146950">The</span>
  <span m="147275">.</span> <span m="147601">=</span> <span m="147926">0</span> <span
  m="148252">notation</span> <span m="148577">once</span> <span m="148903">again</span>
  <span m="149228">tells</span> <span m="149554">us</span> <span m="149880">that</span>
  <span m="150205">our</span> <span m="150531">first</span> <span m="150856">instruction</span>
  <span m="151182">(the</span> <span m="151507">branch)</span> <span m="151833">is</span>
  <span m="152158">at</span> <span m="152484">address</span> <span m="152810">0.</span></p><p><span
  m="154160">The</span> <span m="154742">branch</span> <span m="155325">instruction</span>
  <span m="155907">then</span> <span m="156490">branches</span> <span m="157072">to</span>
  <span m="157655">location</span> <span m="158237">.</span> <span m="158820">+</span>
  <span m="159402">4</span> <span m="159985">=</span> <span m="160567">0</span> <span
  m="161150">+</span> <span m="161732">4</span> <span m="162315">=</span> <span m="162897">4.</span></p><p><span
  m="163480">This</span> <span m="163868">is</span> <span m="164257">the</span> <span
  m="164646">address</span> <span m="165035">of</span> <span m="165423">the</span>
  <span m="165812">HALT()</span> <span m="166201">instruction.</span></p><p><span
  m="166590">In</span> <span m="166984">addition</span> <span m="167379">to</span>
  <span m="167774">branching</span> <span m="168168">to</span> <span m="168563">the</span>
  <span m="168958">HALT()</span> <span m="169352">instruction,</span> <span m="169747">a</span>
  <span m="170142">branch</span> <span m="170536">instruction</span> <span m="170931">also</span>
  <span m="171326">stores</span> <span m="171720">the</span> <span m="172115">address</span>
  <span m="172510">of</span> <span m="173025">the</span> <span m="173540">instruction</span>
  <span m="174055">immediately</span> <span m="174571">following</span> <span m="175086">it</span>
  <span m="175601">into</span> <span m="176117">the</span> <span m="176632">destination</span>
  <span m="177147">register,</span> <span m="177663">R0</span> <span m="178178">in</span>
  <span m="178693">this</span> <span m="179209">case.</span></p><p><span m="180209">The</span>
  <span m="180825">address</span> <span m="181442">of</span> <span m="182059">the</span>
  <span m="182676">next</span> <span m="183292">instruction</span> <span m="183909">is</span>
  <span m="184526">4,</span> <span m="185143">so</span> <span m="185759">R0</span>
  <span m="186376">=</span> <span m="186993">0x4.</span></p><p><span m="187610">Let's</span>
  <span m="188067">take</span> <span m="188524">a</span> <span m="188981">look</span>
  <span m="189438">at</span> <span m="189895">what</span> <span m="190352">this</span>
  <span m="190809">code</span> <span m="191266">is</span> <span m="191723">doing.</span></p><p><span
  m="192180">It</span> <span m="192992">first</span> <span m="193805">loads</span>
  <span m="194618">the</span> <span m="195431">contents</span> <span m="196243">of</span>
  <span m="197056">address</span> <span m="197869">x</span> <span m="198682">into</span>
  <span m="199495">R0,</span> <span m="200307">so</span> <span m="201120">R0</span>
  <span m="201933">=</span> <span m="202746">0x0FACE0FF</span> <span m="203558">or</span>
  <span m="204371">0xFACEOFF</span> <span m="205184">for</span> <span m="205997">short.</span></p><p><span
  m="206810">It</span> <span m="207335">then</span> <span m="207860">moves</span>
  <span m="208385">the</span> <span m="208910">constant</span> <span m="209435">0</span>
  <span m="209960">into</span> <span m="210485">R1,</span> <span m="211010">so</span>
  <span m="211535">R1</span> <span m="212060">=</span> <span m="212585">0.</span></p><p><span
  m="213110">It</span> <span m="213544">now</span> <span m="213978">enters</span>
  <span m="214412">the</span> <span m="214846">loop</span> <span m="215280">where</span>
  <span m="215714">the</span> <span m="216148">ANDC</span> <span m="216582">puts</span>
  <span m="217016">into</span> <span m="217450">R3</span> <span m="217884">the</span>
  <span m="218318">least</span> <span m="218752">significant</span> <span m="219186">bit</span>
  <span m="219620">of</span> <span m="220054">R0.</span></p><p><span m="220489">The</span>
  <span m="221085">ADD</span> <span m="221681">increments</span> <span m="222278">R1</span>
  <span m="222874">if</span> <span m="223470">R3</span> <span m="224067">equals</span>
  <span m="224663">1.</span></p><p><span m="225260">This</span> <span m="225601">means</span>
  <span m="225943">that</span> <span m="226284">if</span> <span m="226626">the</span>
  <span m="226967">least</span> <span m="227309">significant</span> <span m="227651">bit</span>
  <span m="227992">of</span> <span m="228334">R0</span> <span m="228675">was</span>
  <span m="229017">a</span> <span m="229358">1,</span> <span m="229700">then</span>
  <span m="230042">R1</span> <span m="230383">is</span> <span m="230725">incremented</span>
  <span m="231066">by</span> <span m="231408">1,</span> <span m="231750">otherwise</span>
  <span m="232358">R1</span> <span m="232966">stays</span> <span m="233574">the</span>
  <span m="234182">same.</span></p><p><span m="234790">The</span> <span m="235206">shift</span>
  <span m="235623">right</span> <span m="236040">constant</span> <span m="236456">then</span>
  <span m="236873">shifts</span> <span m="237290">R0</span> <span m="237706">to</span>
  <span m="238123">the</span> <span m="238540">right</span> <span m="238956">by</span>
  <span m="239373">1.</span></p><p><span m="239790">This</span> <span m="240145">makes</span>
  <span m="240501">R0</span> <span m="240857">have</span> <span m="241213">a</span>
  <span m="241569">0</span> <span m="241925">in</span> <span m="242281">the</span>
  <span m="242637">most</span> <span m="242993">significant</span> <span m="243349">bit,</span>
  <span m="243705">and</span> <span m="244061">the</span> <span m="244417">top</span>
  <span m="244773">31</span> <span m="245129">bits,</span> <span m="245485">of</span>
  <span m="245841">what</span> <span m="246197">R0</span> <span m="246553">used</span>
  <span m="246909">to</span> <span m="247319">be,</span> <span m="247729">are</span>
  <span m="248139">shifted</span> <span m="248549">over</span> <span m="248959">by</span>
  <span m="249369">one</span> <span m="249779">position</span> <span m="250189">to</span>
  <span m="250599">the</span> <span m="251009">right.</span></p><p><span m="251420">Note</span>
  <span m="251771">that</span> <span m="252123">this</span> <span m="252475">means</span>
  <span m="252826">that</span> <span m="253178">the</span> <span m="253530">least</span>
  <span m="253881">significant</span> <span m="254233">bit</span> <span m="254585">of</span>
  <span m="254937">the</span> <span m="255288">old</span> <span m="255640">R0</span>
  <span m="255992">is</span> <span m="256343">now</span> <span m="256695">completely</span>
  <span m="257047">gone.</span></p><p><span m="257399">That's</span> <span m="257796">okay</span>
  <span m="258193">though</span> <span m="258590">because</span> <span m="258987">we</span>
  <span m="259385">already</span> <span m="259782">incremented</span> <span m="260179">R1</span>
  <span m="260576">based</span> <span m="260973">on</span> <span m="261371">that</span>
  <span m="261768">original</span> <span m="262165">least</span> <span m="262562">significant</span>
  <span m="262960">bit</span> <span m="263826">of</span> <span m="264693">R0.</span></p><p><span
  m="265560">The</span> <span m="265886">BNE,</span> <span m="266213">or</span> <span
  m="266539">branch</span> <span m="266866">on</span> <span m="267192">not</span>
  <span m="267519">equal,</span> <span m="267845">then</span> <span m="268172">branches</span>
  <span m="268498">back</span> <span m="268825">to</span> <span m="269151">loop</span>
  <span m="269478">as</span> <span m="269804">long</span> <span m="270131">as</span>
  <span m="270457">R0</span> <span m="270784">is</span> <span m="271110">not</span>
  <span m="271437">equal</span> <span m="271763">to</span> <span m="272090">0.</span></p><p><span
  m="273570">This</span> <span m="273843">means</span> <span m="274116">that</span>
  <span m="274389">what</span> <span m="274662">this</span> <span m="274935">loop</span>
  <span m="275208">is</span> <span m="275481">doing</span> <span m="275755">is</span>
  <span m="276028">looking</span> <span m="276301">at</span> <span m="276574">the</span>
  <span m="276847">current</span> <span m="277120">least</span> <span m="277393">significant</span>
  <span m="277666">bit</span> <span m="277940">of</span> <span m="278431">R0,</span>
  <span m="278922">incrementing</span> <span m="279413">R1</span> <span m="279904">if</span>
  <span m="280395">that</span> <span m="280886">bit</span> <span m="281377">is</span>
  <span m="281868">1,</span> <span m="282360">and</span> <span m="282706">then</span>
  <span m="283052">shifting</span> <span m="283398">that</span> <span m="283744">bit</span>
  <span m="284090">out</span> <span m="284436">until</span> <span m="284783">all</span>
  <span m="285129">bits</span> <span m="285475">have</span> <span m="285821">been</span>
  <span m="286167">shifted</span> <span m="286513">out.</span></p><p><span m="286860">In</span>
  <span m="287162">other</span> <span m="287464">words,</span> <span m="287767">it's</span>
  <span m="288069">counting</span> <span m="288372">the</span> <span m="288674">total</span>
  <span m="288977">number</span> <span m="289279">of</span> <span m="289581">ones</span>
  <span m="289884">in</span> <span m="290186">the</span> <span m="290489">original</span>
  <span m="290791">value</span> <span m="291094">loaded</span> <span m="291396">from</span>
  <span m="291699">address</span> <span m="292629">x.</span></p><p><span m="293560">The</span>
  <span m="293890">loop</span> <span m="294220">ends</span> <span m="294551">when</span>
  <span m="294881">all</span> <span m="295212">the</span> <span m="295542">1's</span>
  <span m="295873">have</span> <span m="296203">been</span> <span m="296534">counted</span>
  <span m="296864">at</span> <span m="297195">which</span> <span m="297525">point</span>
  <span m="297855">R0</span> <span m="298186">is</span> <span m="298516">left</span>
  <span m="298847">with</span> <span m="299177">a</span> <span m="299508">0</span>
  <span m="299838">in</span> <span m="300169">it</span> <span m="300499">because</span>
  <span m="300830">all</span> <span m="301242">the</span> <span m="301655">1's</span>
  <span m="302068">have</span> <span m="302481">been</span> <span m="302894">shifted</span>
  <span m="303307">out.</span></p><p><span m="303720">R1</span> <span m="304666">is</span>
  <span m="305612">left</span> <span m="306558">with</span> <span m="307504">the</span>
  <span m="308450">number</span> <span m="309396">of</span> <span m="310342">1's</span>
  <span m="311288">in</span> <span m="312235">the</span> <span m="313181">data</span>
  <span m="314127">0x0FACE0FF</span> <span m="315073">equals</span> <span m="316019">in</span>
  <span m="316965">binary</span> <span m="317911">0000</span> <span m="318857">1111</span>
  <span m="319803">1010</span> <span m="320750">1100</span> <span m="322907">1110</span>
  <span m="325065">0000</span> <span m="327223">1111</span> <span m="329381">1111.</span></p><p><span
  m="331539">There</span> <span m="332390">are</span> <span m="333242">19</span> <span
  m="334093">ones</span> <span m="334945">in</span> <span m="335797">0x0FACE0FF,</span>
  <span m="336648">so</span> <span m="337500">R1</span> <span m="338352">=</span>
  <span m="339203">19</span> <span m="340055">=</span> <span m="340906">16</span>
  <span m="341758">+</span> <span m="342610">3</span> <span m="343461">which</span>
  <span m="344313">in</span> <span m="345165">hexadecimal</span> <span m="346016">=</span>
  <span m="346868">0x13.</span></p><p><span m="347720">In</span> <span m="348210">this</span>
  <span m="348701">piece</span> <span m="349192">of</span> <span m="349682">code,</span>
  <span m="350173">the</span> <span m="350664">CMOVE</span> <span m="351155">first</span>
  <span m="351645">sets</span> <span m="352136">the</span> <span m="352627">stack</span>
  <span m="353117">pointer</span> <span m="353608">to</span> <span m="354099">0x1000.</span></p><p><span
  m="354590">Then</span> <span m="355215">a</span> <span m="355840">PUSH(SP)</span>
  <span m="356465">operation</span> <span m="357090">is</span> <span m="357715">performed.</span></p><p><span
  m="358340">Lets</span> <span m="358736">first</span> <span m="359132">understand</span>
  <span m="359528">what</span> <span m="359925">a</span> <span m="360321">PUSH</span>
  <span m="360717">instruction</span> <span m="361113">does.</span></p><p><span m="361510">A</span>
  <span m="361926">PUSH</span> <span m="362342">instruction</span> <span m="362758">is</span>
  <span m="363174">actually</span> <span m="363590">a</span> <span m="364006">macro</span>
  <span m="364422">made</span> <span m="364838">up</span> <span m="365254">of</span>
  <span m="365670">two</span> <span m="366086">beta</span> <span m="366502">instructions.</span></p><p><span
  m="366919">To</span> <span m="367257">push</span> <span m="367596">a</span> <span
  m="367935">value</span> <span m="368274">onto</span> <span m="368613">the</span>
  <span m="368952">stack,</span> <span m="369291">the</span> <span m="369630">stack</span>
  <span m="369968">pointer</span> <span m="370307">is</span> <span m="370646">first</span>
  <span m="370985">incremented</span> <span m="371324">by</span> <span m="371663">4</span>
  <span m="372002">in</span> <span m="372341">order</span> <span m="372680">to</span>
  <span m="373067">point</span> <span m="373454">to</span> <span m="373841">the</span>
  <span m="374228">next</span> <span m="374615">empty</span> <span m="375002">location</span>
  <span m="375389">on</span> <span m="375776">the</span> <span m="376163">stack.</span></p><p><span
  m="376550">This</span> <span m="376814">sets</span> <span m="377078">SP</span> <span
  m="377342">=</span> <span m="377606">0x1004.</span></p><p><span m="377870">Then,</span>
  <span m="378447">the</span> <span m="379025">contents</span> <span m="379602">of</span>
  <span m="380180">register</span> <span m="380757">Ra,</span> <span m="381335">which</span>
  <span m="381912">is</span> <span m="382490">being</span> <span m="383067">pushed</span>
  <span m="383645">onto</span> <span m="384222">the</span> <span m="384800">stack,</span>
  <span m="385377">are</span> <span m="385955">stored</span> <span m="386532">at</span>
  <span m="387110">the</span> <span m="387861">memory</span> <span m="388613">location</span>
  <span m="389365">whose</span> <span m="390116">address</span> <span m="390868">is</span>
  <span m="391620">SP-4</span> <span m="392372">which</span> <span m="393123">is</span>
  <span m="393875">address</span> <span m="394627">0x1000.</span></p><p><span m="395379">Now</span>
  <span m="395797">looking</span> <span m="396216">at</span> <span m="396635">the</span>
  <span m="397054">actual</span> <span m="397473">PUSH</span> <span m="397892">operation</span>
  <span m="398311">performed</span> <span m="398730">here,</span> <span m="399148">we</span>
  <span m="399567">are</span> <span m="399986">performing</span> <span m="400405">a</span>
  <span m="400824">PUSH</span> <span m="401243">of</span> <span m="401662">stack</span>
  <span m="402081">pointer</span> <span m="402500">so</span> <span m="403018">the</span>
  <span m="403537">Ra</span> <span m="404056">register</span> <span m="404575">is</span>
  <span m="405093">also</span> <span m="405612">the</span> <span m="406131">stack</span>
  <span m="406650">pointer.</span></p><p><span m="407169">This</span> <span m="407603">means</span>
  <span m="408037">that</span> <span m="408471">the</span> <span m="408905">value</span>
  <span m="409339">stored</span> <span m="409774">at</span> <span m="410208">location</span>
  <span m="410642">0x1000</span> <span m="411076">is</span> <span m="411510">actually</span>
  <span m="411944">the</span> <span m="412379">value</span> <span m="412813">of</span>
  <span m="413247">SP</span> <span m="413681">which</span> <span m="414115">is</span>
  <span m="414550">0x1004.</span></p><p><span m="417710">So</span> <span m="418217">the</span>
  <span m="418724">value</span> <span m="419231">that</span> <span m="419738">got</span>
  <span m="420245">pushed</span> <span m="420753">onto</span> <span m="421260">the</span>
  <span m="421767">stack</span> <span m="422274">is</span> <span m="422781">0x1004.</span></p>
type: course
uid: 4f9c7b659420d7101e0f99b7c0436be3

---
None