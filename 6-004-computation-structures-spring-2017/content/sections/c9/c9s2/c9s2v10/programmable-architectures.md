---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: O6yw1qkECig
  parent_uid: 29db23928611d1e84c3f58ddd6cbfb40
  title: Video-YouTube-Stream
  type: Video
  uid: c7beb8d8f8841b637c975994a2cd98c7
- id: 3Play-3Play YouTube id-Stream
  media_location: O6yw1qkECig
  parent_uid: 29db23928611d1e84c3f58ddd6cbfb40
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: f775c78f052bffd50fc54012603f3499
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/O6yw1qkECig/default.jpg
  parent_uid: 29db23928611d1e84c3f58ddd6cbfb40
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 3eea36a036740149a21ad14cc77e864f
- id: O6yw1qkECig.srt
  parent_uid: 29db23928611d1e84c3f58ddd6cbfb40
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v10/programmable-architectures/O6yw1qkECig.srt
  title: 3play caption file
  type: null
  uid: e38f5a27fd21f582385e636af6fc5cc6
- id: O6yw1qkECig.pdf
  parent_uid: 29db23928611d1e84c3f58ddd6cbfb40
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v10/programmable-architectures/O6yw1qkECig.pdf
  title: 3play pdf file
  type: null
  uid: d759eb431c7f87c9b0468da795ccdb8d
- id: Caption-3Play YouTube id-SRT
  parent_uid: 29db23928611d1e84c3f58ddd6cbfb40
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b50866ac25ca32d6cb64ba96d03b37f9
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 29db23928611d1e84c3f58ddd6cbfb40
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: f9090e34e0dee955764d7b76a55f7a1e
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_09-02-10-01_300k.mp4
  parent_uid: 29db23928611d1e84c3f58ddd6cbfb40
  title: Video-Internet Archive-MP4
  type: Video
  uid: bf1e9c791e9be9a84032e90755eb5a2c
inline_embed_id: 86768791programmablearchitectures40543393
layout: video
order_index: null
parent_uid: ed9174fdaa12e9dccd2676639a65be3b
related_resources_text: ''
short_url: programmable-architectures
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c9/c9s2/c9s2v10/programmable-architectures
template_type: Embed
title: 'Worked Example: Programmable Architectures'
transcript: <p><span m="760">For</span> <span m="1066">this</span> <span m="1372">problem,</span>
  <span m="1679">we</span> <span m="1985">are</span> <span m="2292">going</span> <span
  m="2598">to</span> <span m="2905">make</span> <span m="3211">use</span> <span m="3518">of</span>
  <span m="3824">this</span> <span m="4131">simple</span> <span m="4437">datapath</span>
  <span m="4744">that</span> <span m="5050">consists</span> <span m="5357">of</span>
  <span m="5663">a</span> <span m="5970">four</span> <span m="6433">register</span>
  <span m="6897">register</span> <span m="7361">file,</span> <span m="7825">a</span>
  <span m="8289">relatively</span> <span m="8753">simple</span> <span m="9216">arithmetic</span>
  <span m="9680">logic</span> <span m="10144">unit</span> <span m="10608">that</span>
  <span m="11072">can</span> <span m="11536">perform</span> <span m="12000">ADD,</span>
  <span m="12478">SUB,</span> <span m="12957">MUL,</span> <span m="13435">and</span>
  <span m="13914">NAND</span> <span m="14392">operations.</span> <span m="14871">In</span>
  <span m="15350">addition,</span> <span m="15828">it</span> <span m="16307">can</span>
  <span m="16785">compare</span> <span m="17264">two</span> <span m="17742">inputs</span>
  <span m="18221">and</span> <span m="18700">determine</span> <span m="19041">whether</span>
  <span m="19382">or</span> <span m="19724">not</span> <span m="20065">they</span>
  <span m="20406">are</span> <span m="20748">equal.</span> <span m="21089">The</span>
  <span m="21430">result</span> <span m="21772">of</span> <span m="22113">the</span>
  <span m="22454">comparison,</span> <span m="22796">Z,</span> <span m="23137">can</span>
  <span m="23478">then</span> <span m="23820">be</span> <span m="24215">used</span>
  <span m="24610">to</span> <span m="25005">control</span> <span m="25400">what</span>
  <span m="25795">happens</span> <span m="26190">next.</span> <span m="26585">There</span>
  <span m="26980">are</span> <span m="27375">multiple</span> <span m="27770">control</span>
  <span m="28165">signals</span> <span m="28560">in</span> <span m="28955">this</span>
  <span m="29350">datapath.</span> <span m="29875">The</span> <span m="30400">first</span>
  <span m="30925">two</span> <span m="31450">are</span> <span m="31975">Asel</span>
  <span m="32500">and</span> <span m="33025">Bsel.</span></p><p><span m="33550">These</span>
  <span m="33989">are</span> <span m="34429">used</span> <span m="34869">to</span>
  <span m="35309">select</span> <span m="35749">which</span> <span m="36189">register</span>
  <span m="36629">drives</span> <span m="37069">the</span> <span m="37509">corresponding</span>
  <span m="37949">multiplexer</span> <span m="38389">output.</span></p><p><span m="38829">The</span>
  <span m="39164">value</span> <span m="39500">stored</span> <span m="39835">in</span>
  <span m="40171">the</span> <span m="40507">register</span> <span m="40842">selected</span>
  <span m="41178">by</span> <span m="41514">Asel</span> <span m="41849">becomes</span>
  <span m="42185">the</span> <span m="42520">A</span> <span m="42856">input</span>
  <span m="43192">to</span> <span m="43527">the</span> <span m="43863">arithmetic</span>
  <span m="44199">operations</span> <span m="44635">and</span> <span m="45072">is</span>
  <span m="45509">passed</span> <span m="45946">to</span> <span m="46382">the</span>
  <span m="46819">arithmetic</span> <span m="47256">units</span> <span m="47693">along</span>
  <span m="48129">the</span> <span m="48566">red</span> <span m="49003">wire.</span></p><p><span
  m="49440">The</span> <span m="49768">value</span> <span m="50097">stored</span>
  <span m="50426">in</span> <span m="50754">the</span> <span m="51083">register</span>
  <span m="51412">selected</span> <span m="51740">by</span> <span m="52069">Bsel</span>
  <span m="52398">becomes</span> <span m="52726">the</span> <span m="53055">B</span>
  <span m="53384">input</span> <span m="53712">to</span> <span m="54041">the</span>
  <span m="54370">arithmetic</span> <span m="54699">operations</span> <span m="55146">and</span>
  <span m="55594">is</span> <span m="56041">passed</span> <span m="56489">to</span>
  <span m="56936">the</span> <span m="57384">arithmetic</span> <span m="57831">units</span>
  <span m="58279">along</span> <span m="58726">the</span> <span m="59174">blue</span>
  <span m="59621">wire.</span></p><p><span m="60069">The</span> <span m="60450">next</span>
  <span m="60832">control</span> <span m="61213">signal</span> <span m="61595">is</span>
  <span m="61976">Opsel.</span> <span m="62358">It</span> <span m="62739">selects</span>
  <span m="63121">which</span> <span m="63502">of</span> <span m="63884">the</span>
  <span m="64265">four</span> <span m="64647">operation</span> <span m="65028">outputs</span>
  <span m="65410">should</span> <span m="65856">be</span> <span m="66303">selected</span>
  <span m="66750">by</span> <span m="67197">the</span> <span m="67644">Opsel</span>
  <span m="68091">multiplexer</span> <span m="68538">as</span> <span m="68985">the</span>
  <span m="69432">result</span> <span m="69879">of</span> <span m="70326">our</span>
  <span m="70773">operation.</span></p><p><span m="71220">This</span> <span m="71593">result</span>
  <span m="71966">is</span> <span m="72339">fed</span> <span m="72712">back</span>
  <span m="73085">to</span> <span m="73458">the</span> <span m="73831">register</span>
  <span m="74204">file</span> <span m="74577">along</span> <span m="74950">the</span>
  <span m="75323">purple</span> <span m="75696">wire.</span></p><p><span m="76070">The</span>
  <span m="76475">Wen</span> <span m="76880">is</span> <span m="77285">a</span> <span
  m="77691">write</span> <span m="78096">enable</span> <span m="78501">for</span>
  <span m="78907">the</span> <span m="79312">register</span> <span m="79717">file</span>
  <span m="80122">which</span> <span m="80528">specifies</span> <span m="80933">whether</span>
  <span m="81338">or</span> <span m="81744">not</span> <span m="82149">the</span>
  <span m="82554">result</span> <span m="82960">of</span> <span m="83365">our</span>
  <span m="83770">operation</span> <span m="84176">should</span> <span m="84581">be</span>
  <span m="84987">written</span> <span m="85392">back</span> <span m="85798">into</span>
  <span m="86203">the</span> <span m="86609">register</span> <span m="87014">file.</span></p><p><span
  m="87420">If</span> <span m="87755">it</span> <span m="88091">is</span> <span m="88427">supposed</span>
  <span m="88763">to</span> <span m="89099">be</span> <span m="89435">written</span>
  <span m="89771">back</span> <span m="90107">to</span> <span m="90442">the</span>
  <span m="90778">register</span> <span m="91114">file,</span> <span m="91450">then</span>
  <span m="91786">the</span> <span m="92122">Wsel</span> <span m="92458">control</span>
  <span m="92794">signal</span> <span m="93130">selects</span> <span m="93548">to</span>
  <span m="93966">which</span> <span m="94384">of</span> <span m="94802">the</span>
  <span m="95220">registers</span> <span m="95638">the</span> <span m="96056">result</span>
  <span m="96474">should</span> <span m="96892">be</span> <span m="97310">written.</span></p><p><span
  m="97729">The</span> <span m="98115">yellow</span> <span m="98502">box</span> <span
  m="98889">is</span> <span m="99275">the</span> <span m="99662">control</span> <span
  m="100049">FSM.</span> <span m="100436">It</span> <span m="100822">generates</span>
  <span m="101209">the</span> <span m="101596">control</span> <span m="101983">signals</span>
  <span m="102369">for</span> <span m="102756">the</span> <span m="103143">rest</span>
  <span m="103530">of</span> <span m="103987">the</span> <span m="104445">datapath</span>
  <span m="104902">based</span> <span m="105360">on</span> <span m="105817">the</span>
  <span m="106275">operations</span> <span m="106732">that</span> <span m="107190">you</span>
  <span m="107647">want</span> <span m="108105">to</span> <span m="108562">perform.</span></p><p><span
  m="109020">Suppose</span> <span m="109366">the</span> <span m="109713">initial</span>
  <span m="110060">value</span> <span m="110406">of</span> <span m="110753">our</span>
  <span m="111100">4</span> <span m="111446">registers</span> <span m="111793">is:</span>
  <span m="112140">R0</span> <span m="112608">=</span> <span m="113077">1,</span>
  <span m="113545">R1</span> <span m="114014">=</span> <span m="114483">0,</span>
  <span m="114951">R2</span> <span m="115420">=</span> <span m="115889">-1,</span>
  <span m="116357">and</span> <span m="116826">R3</span> <span m="117295">=</span>
  <span m="117763">N.</span> <span m="118232">We</span> <span m="118700">want</span>
  <span m="119169">to</span> <span m="119638">evaluate</span> <span m="120106">the</span>
  <span m="120575">result</span> <span m="121044">of</span> <span m="121512">the</span>
  <span m="121981">function</span> <span m="122450">3</span> <span m="122875">*</span>
  <span m="123301">N</span> <span m="123727">&ndash;</span> <span m="124152">2</span>
  <span m="124578">and</span> <span m="125004">store</span> <span m="125429">the</span>
  <span m="125855">result</span> <span m="126281">into</span> <span m="126706">R3.</span>
  <span m="127132">Our</span> <span m="127558">job</span> <span m="127983">is</span>
  <span m="128409">to</span> <span m="128835">design</span> <span m="129260">the</span>
  <span m="129686">control</span> <span m="130112">FSM</span> <span m="130537">so</span>
  <span m="130963">that</span> <span m="131389">it</span> <span m="131793">produces</span>
  <span m="132197">the</span> <span m="132601">correct</span> <span m="133005">signals</span>
  <span m="133409">to</span> <span m="133813">achieve</span> <span m="134217">what</span>
  <span m="134621">we</span> <span m="135025">want.</span></p><p><span m="135430">To</span>
  <span m="135696">help</span> <span m="135962">us</span> <span m="136229">get</span>
  <span m="136495">started,</span> <span m="136762">here</span> <span m="137028">is</span>
  <span m="137294">an</span> <span m="137561">incomplete</span> <span m="137827">listing</span>
  <span m="138094">of</span> <span m="138360">the</span> <span m="138626">code</span>
  <span m="138893">that</span> <span m="139159">will</span> <span m="139426">achieve</span>
  <span m="139692">what</span> <span m="139959">we</span> <span m="140362">want.</span>
  <span m="140766">The</span> <span m="141170">Sx</span> <span m="141573">labels</span>
  <span m="141977">are</span> <span m="142381">the</span> <span m="142785">names</span>
  <span m="143188">of</span> <span m="143592">the</span> <span m="143996">states</span>
  <span m="144400">corresponding</span> <span m="144758">to</span> <span m="145116">each</span>
  <span m="145474">instruction</span> <span m="145832">in</span> <span m="146190">our</span>
  <span m="146548">program.</span> <span m="146906">Our</span> <span m="147264">first</span>
  <span m="147622">job</span> <span m="147980">is</span> <span m="148338">to</span>
  <span m="148696">figure</span> <span m="149054">out</span> <span m="149412">the</span>
  <span m="149770">values</span> <span m="150129">of</span> <span m="150626">RX,</span>
  <span m="151124">RY,</span> <span m="151621">and</span> <span m="152119">RZ</span>
  <span m="152616">so</span> <span m="153114">that</span> <span m="153611">our</span>
  <span m="154109">code</span> <span m="154606">behaves</span> <span m="155104">as</span>
  <span m="155601">expected.</span></p><p><span m="156099">Let's</span> <span m="156466">begin</span>
  <span m="156833">by</span> <span m="157200">looking</span> <span m="157567">at</span>
  <span m="157935">state</span> <span m="158302">S0.</span> <span m="158669">We</span>
  <span m="159036">want</span> <span m="159404">to</span> <span m="159771">end</span>
  <span m="160138">up</span> <span m="160505">with</span> <span m="160872">the</span>
  <span m="161240">value</span> <span m="161607">-2</span> <span m="161974">in</span>
  <span m="162341">R2</span> <span m="162709">by</span> <span m="163255">adding</span>
  <span m="163801">R2</span> <span m="164347">which</span> <span m="164893">currently</span>
  <span m="165439">holds</span> <span m="165985">-1</span> <span m="166531">to</span>
  <span m="167077">some</span> <span m="167623">register.</span></p><p><span m="168170">In</span>
  <span m="168624">order</span> <span m="169078">to</span> <span m="169532">produce</span>
  <span m="169987">-2,</span> <span m="170441">we</span> <span m="170895">need</span>
  <span m="171350">to</span> <span m="171804">add</span> <span m="172258">-1</span>
  <span m="172713">which</span> <span m="173167">means</span> <span m="173621">that</span>
  <span m="174076">RX</span> <span m="174530">=</span> <span m="174984">R2.</span></p><p><span
  m="175439">Next,</span> <span m="175879">we</span> <span m="176320">look</span>
  <span m="176761">at</span> <span m="177201">state</span> <span m="177642">S1.</span>
  <span m="178083">Here</span> <span m="178523">we</span> <span m="178964">want</span>
  <span m="179405">to</span> <span m="179846">end</span> <span m="180286">up</span>
  <span m="180727">with</span> <span m="181168">the</span> <span m="181608">value</span>
  <span m="182049">2</span> <span m="182490">in</span> <span m="182931">R1</span>
  <span m="183400">by</span> <span m="183870">adding</span> <span m="184340">Ry</span>
  <span m="184810">to</span> <span m="185280">R0</span> <span m="185749">which</span>
  <span m="186219">currently</span> <span m="186689">holds</span> <span m="187159">a</span>
  <span m="187629">1.</span></p><p><span m="188099">In</span> <span m="188690">order</span>
  <span m="189281">to</span> <span m="189873">produce</span> <span m="190464">2,</span>
  <span m="191055">we</span> <span m="191647">need</span> <span m="192238">to</span>
  <span m="192829">add</span> <span m="193421">1</span> <span m="194012">which</span>
  <span m="194603">means</span> <span m="195195">RY</span> <span m="195786">=</span>
  <span m="196377">R0.</span></p><p><span m="196969">State</span> <span m="197383">S2</span>
  <span m="197797">adds</span> <span m="198211">R0</span> <span m="198625">to</span>
  <span m="199039">R1</span> <span m="199454">and</span> <span m="199868">stores</span>
  <span m="200282">the</span> <span m="200696">result</span> <span m="201110">in</span>
  <span m="201524">R1.</span></p><p><span m="201939">Since</span> <span m="202356">R0</span>
  <span m="202773">still</span> <span m="203191">equals</span> <span m="203608">1</span>
  <span m="204026">and</span> <span m="204443">R1</span> <span m="204860">=</span>
  <span m="205278">2,</span> <span m="205695">then</span> <span m="206113">we</span>
  <span m="206530">produce</span> <span m="206947">R1</span> <span m="207365">=</span>
  <span m="207782">3.</span></p><p><span m="208200">Now,</span> <span m="208661">let's</span>
  <span m="209122">look</span> <span m="209584">at</span> <span m="210045">state</span>
  <span m="210506">S3.</span> <span m="210968">Our</span> <span m="211429">goal</span>
  <span m="211890">is</span> <span m="212352">to</span> <span m="212813">multiply</span>
  <span m="213274">3*N</span> <span m="213736">and</span> <span m="214197">store</span>
  <span m="214658">the</span> <span m="215120">result</span> <span m="215633">into</span>
  <span m="216146">R3.</span> <span m="216660">To</span> <span m="217173">achieve</span>
  <span m="217686">this,</span> <span m="218200">we</span> <span m="218713">multiply</span>
  <span m="219226">RZ</span> <span m="219740">by</span> <span m="220253">R3</span>
  <span m="220766">and</span> <span m="221280">store</span> <span m="221683">the</span>
  <span m="222087">result</span> <span m="222490">in</span> <span m="222894">R3.</span>
  <span m="223297">Since</span> <span m="223701">R3</span> <span m="224105">currently</span>
  <span m="224508">=</span> <span m="224912">N,</span> <span m="225315">that</span>
  <span m="225719">means</span> <span m="226122">that</span> <span m="226526">we</span>
  <span m="226930">want</span> <span m="227443">to</span> <span m="227956">multiply</span>
  <span m="228469">it</span> <span m="228982">by</span> <span m="229495">R1</span>
  <span m="230008">which</span> <span m="230521">equals</span> <span m="231034">3.</span>
  <span m="231547">So</span> <span m="232060">RZ</span> <span m="232573">=</span>
  <span m="233086">R1.</span></p><p><span m="233599">Finally,</span> <span m="234174">we</span>
  <span m="234750">add</span> <span m="235325">R3</span> <span m="235901">and</span>
  <span m="236477">R2</span> <span m="237052">to</span> <span m="237628">produce</span>
  <span m="238204">3*N-2</span> <span m="238779">and</span> <span m="239355">store</span>
  <span m="239930">that</span> <span m="240506">result</span> <span m="241082">back</span>
  <span m="241657">into</span> <span m="242233">R3.</span></p><p><span m="242809">S5</span>
  <span m="243294">just</span> <span m="243780">executes</span> <span m="244266">a</span>
  <span m="244752">HALT()</span> <span m="245238">instruction</span> <span m="245724">to</span>
  <span m="246209">indicate</span> <span m="246695">that</span> <span m="247181">we</span>
  <span m="247667">are</span> <span m="248153">done.</span></p><p><span m="248639">Now</span>
  <span m="248915">that</span> <span m="249192">we</span> <span m="249468">have</span>
  <span m="249745">working</span> <span m="250021">code,</span> <span m="250298">our</span>
  <span m="250574">next</span> <span m="250851">goal</span> <span m="251127">is</span>
  <span m="251404">to</span> <span m="251680">determine</span> <span m="251957">the</span>
  <span m="252233">settings</span> <span m="252510">for</span> <span m="252786">the</span>
  <span m="253063">control</span> <span m="253340">FSM</span> <span m="253825">that</span>
  <span m="254311">will</span> <span m="254797">make</span> <span m="255283">the</span>
  <span m="255769">correct</span> <span m="256255">operations</span> <span m="256740">be</span>
  <span m="257226">executed</span> <span m="257712">by</span> <span m="258198">our</span>
  <span m="258684">datapath.</span></p><p><span m="259170">Since</span> <span m="259441">we</span>
  <span m="259712">have</span> <span m="259983">6</span> <span m="260254">states,</span>
  <span m="260525">we</span> <span m="260796">will</span> <span m="261067">need</span>
  <span m="261338">3</span> <span m="261609">state</span> <span m="261880">bits</span>
  <span m="262151">to</span> <span m="262422">encode</span> <span m="262693">the</span>
  <span m="262964">value</span> <span m="263235">of</span> <span m="263506">the</span>
  <span m="263777">current</span> <span m="264048">and</span> <span m="264320">next</span>
  <span m="265134">state.</span> <span m="265948">We</span> <span m="266762">begin</span>
  <span m="267577">with</span> <span m="268391">state</span> <span m="269205">S0.</span></p><p><span
  m="270020">In</span> <span m="270446">order</span> <span m="270872">to</span> <span
  m="271298">encode</span> <span m="271725">that</span> <span m="272151">we</span>
  <span m="272577">are</span> <span m="273004">in</span> <span m="273430">state</span>
  <span m="273856">zero</span> <span m="274283">using</span> <span m="274709">3</span>
  <span m="275135">bits,</span> <span m="275562">we</span> <span m="275988">set</span>
  <span m="276414">our</span> <span m="276841">current</span> <span m="277267">state,</span>
  <span m="277693">S[2:0]</span> <span m="278120">to</span> <span m="278592">000.</span>
  <span m="279064">In</span> <span m="279536">this</span> <span m="280008">operation</span>
  <span m="280480">we</span> <span m="280952">don't</span> <span m="281424">care</span>
  <span m="281896">about</span> <span m="282368">the</span> <span m="282840">Z</span>
  <span m="283262">signal,</span> <span m="283684">so</span> <span m="284106">Z</span>
  <span m="284528">=</span> <span m="284951">X</span> <span m="285373">which</span>
  <span m="285795">means</span> <span m="286217">don't</span> <span m="286640">care.</span>
  <span m="287062">The</span> <span m="287484">instruction</span> <span m="287906">that</span>
  <span m="288328">we</span> <span m="288751">want</span> <span m="289173">to</span>
  <span m="289595">execute</span> <span m="290017">after</span> <span m="290440">this</span>
  <span m="290902">first</span> <span m="291364">ADD,</span> <span m="291826">is</span>
  <span m="292288">the</span> <span m="292751">next</span> <span m="293213">ADD</span>
  <span m="293675">in</span> <span m="294137">state</span> <span m="294600">S1.</span>
  <span m="295062">This</span> <span m="295524">means</span> <span m="295986">that</span>
  <span m="296448">our</span> <span m="296911">next</span> <span m="297373">state</span>
  <span m="297835">is</span> <span m="298297">001.</span></p><p><span m="298760">Note</span>
  <span m="299278">that</span> <span m="299796">the</span> <span m="300315">notation</span>
  <span m="300833">S'</span> <span m="301352">is</span> <span m="301870">often</span>
  <span m="302389">used</span> <span m="302907">to</span> <span m="303426">represent</span>
  <span m="303944">the</span> <span m="304463">next</span> <span m="304981">state.</span></p><p><span
  m="305500">Our</span> <span m="305881">register</span> <span m="306263">select</span>
  <span m="306645">signals</span> <span m="307026">each</span> <span m="307408">need</span>
  <span m="307790">to</span> <span m="308171">select</span> <span m="308553">one</span>
  <span m="308935">of</span> <span m="309316">4</span> <span m="309698">registers.</span></p><p><span
  m="310080">This</span> <span m="310443">means</span> <span m="310807">that</span>
  <span m="311170">these</span> <span m="311534">signals</span> <span m="311898">must</span>
  <span m="312261">each</span> <span m="312625">be</span> <span m="312989">2</span>
  <span m="313352">bits</span> <span m="313716">wide.</span></p><p><span m="314080">Our</span>
  <span m="314465">Asel</span> <span m="314851">control</span> <span m="315237">signal</span>
  <span m="315622">identifies</span> <span m="316008">the</span> <span m="316394">register</span>
  <span m="316780">that</span> <span m="317165">should</span> <span m="317551">be</span>
  <span m="317937">used</span> <span m="318322">as</span> <span m="318708">input</span>
  <span m="319094">A.</span></p><p><span m="319480">This</span> <span m="320140">register</span>
  <span m="320800">is</span> <span m="321460">R2,</span> <span m="322120">so</span>
  <span m="322780">Asel</span> <span m="323440">is</span> <span m="324100">10.</span>
  <span m="324760">Bsel</span> <span m="325420">identifies</span> <span m="326080">the</span>
  <span m="326740">second</span> <span m="327400">source</span> <span m="328060">operand.</span></p><p><span
  m="328720">In</span> <span m="329266">this</span> <span m="329813">case</span> <span
  m="330360">it</span> <span m="330907">is</span> <span m="331454">also</span> <span
  m="332001">R2,</span> <span m="332548">so</span> <span m="333095">Bsel</span> <span
  m="333642">=</span> <span m="334189">10</span> <span m="334736">as</span> <span
  m="335283">well.</span></p><p><span m="335830">The</span> <span m="336309">Opsel</span>
  <span m="336788">signal</span> <span m="337267">identifies</span> <span m="337746">which</span>
  <span m="338225">operation</span> <span m="338704">we</span> <span m="339183">want</span>
  <span m="339662">to</span> <span m="340141">perform.</span></p><p><span m="340620">Since</span>
  <span m="340963">we</span> <span m="341306">have</span> <span m="341650">4</span>
  <span m="341993">distinct</span> <span m="342336">operations,</span> <span m="342680">we</span>
  <span m="343023">would</span> <span m="343366">need</span> <span m="343710">two</span>
  <span m="344053">bits</span> <span m="344396">to</span> <span m="344740">distinguish</span>
  <span m="345083">amongst</span> <span m="345426">them</span> <span m="345770">and</span>
  <span m="346121">we</span> <span m="346472">would</span> <span m="346824">make</span>
  <span m="347175">each</span> <span m="347527">operation</span> <span m="347878">be</span>
  <span m="348230">associated</span> <span m="348581">with</span> <span m="348932">one</span>
  <span m="349284">of</span> <span m="349635">the</span> <span m="349987">4</span>
  <span m="350338">encodings.</span></p><p><span m="350690">For</span> <span m="351060">simplicity,</span>
  <span m="351431">let's</span> <span m="351802">just</span> <span m="352172">label</span>
  <span m="352543">Opsel</span> <span m="352914">as</span> <span m="353284">ADD</span>
  <span m="353655">to</span> <span m="354026">indicate</span> <span m="354396">that</span>
  <span m="354767">we</span> <span m="355138">selected</span> <span m="355508">the</span>
  <span m="355879">encoding</span> <span m="356250">for</span> <span m="356725">the</span>
  <span m="357201">ADD.</span> <span m="357677">The</span> <span m="358153">register</span>
  <span m="358629">we</span> <span m="359105">want</span> <span m="359580">to</span>
  <span m="360056">write</span> <span m="360532">our</span> <span m="361008">result</span>
  <span m="361484">to,</span> <span m="361960">also</span> <span m="362420">known</span>
  <span m="362881">as</span> <span m="363342">the</span> <span m="363803">destination</span>
  <span m="364264">register,</span> <span m="364725">is</span> <span m="365186">R2</span>
  <span m="365647">for</span> <span m="366108">this</span> <span m="366569">operation.</span></p><p><span
  m="367030">This</span> <span m="367511">means</span> <span m="367993">that</span>
  <span m="368474">Wsel</span> <span m="368956">=</span> <span m="369437">10</span>
  <span m="369919">and</span> <span m="370401">Wen</span> <span m="370882">=</span>
  <span m="371364">1.</span> <span m="371845">Wen</span> <span m="372327">is</span>
  <span m="372808">a</span> <span m="373290">signal</span> <span m="373772">that</span>
  <span m="374253">enables</span> <span m="374735">writing</span> <span m="375216">to</span>
  <span m="375698">the</span> <span m="376180">register</span> <span m="376539">file.</span>
  <span m="376898">If</span> <span m="377257">it</span> <span m="377616">is</span>
  <span m="377975">set</span> <span m="378335">to</span> <span m="378694">0,</span>
  <span m="379053">then</span> <span m="379412">regardless</span> <span m="379771">of</span>
  <span m="380130">the</span> <span m="380490">value</span> <span m="380990">of</span>
  <span m="381490">Wsel,</span> <span m="381990">no</span> <span m="382490">value</span>
  <span m="382990">will</span> <span m="383490">be</span> <span m="383990">written</span>
  <span m="384490">into</span> <span m="384990">the</span> <span m="385490">register</span>
  <span m="385990">file.</span></p><p><span m="386490">Now</span> <span m="386872">let's</span>
  <span m="387254">quickly</span> <span m="387636">run</span> <span m="388018">through</span>
  <span m="388400">the</span> <span m="388782">rest</span> <span m="389164">of</span>
  <span m="389546">our</span> <span m="389928">instructions.</span></p><p><span m="390310">Our</span>
  <span m="390730">current</span> <span m="391151">state</span> <span m="391572">is</span>
  <span m="391992">state</span> <span m="392413">S1,</span> <span m="392834">or</span>
  <span m="393254">001.</span> <span m="393675">Once</span> <span m="394096">again</span>
  <span m="394516">Z</span> <span m="394937">is</span> <span m="395358">a</span> <span
  m="395778">don't</span> <span m="396199">care.</span></p><p><span m="396620">Since</span>
  <span m="397023">the</span> <span m="397427">instruction</span> <span m="397831">that</span>
  <span m="398235">will</span> <span m="398639">be</span> <span m="399043">executed</span>
  <span m="399447">next</span> <span m="399851">is</span> <span m="400255">the</span>
  <span m="400658">one</span> <span m="401062">in</span> <span m="401466">S2,</span>
  <span m="401870">our</span> <span m="402274">next</span> <span m="402678">state</span>
  <span m="403082">is</span> <span m="403486">010.</span></p><p><span m="403890">Our</span>
  <span m="404653">Asel</span> <span m="405417">=</span> <span m="406181">00</span>
  <span m="406944">and</span> <span m="407708">Bsel</span> <span m="408472">=</span>
  <span m="409235">00.</span> <span m="409999">Opsel</span> <span m="410763">=</span>
  <span m="411526">ADD</span> <span m="412290">and</span> <span m="413054">Wsel</span>
  <span m="413817">=</span> <span m="414581">01</span> <span m="415345">and</span>
  <span m="416108">Wen</span> <span m="416872">=</span> <span m="417636">1.</span></p><p><span
  m="418400">State</span> <span m="418860">2</span> <span m="419320">follows</span>
  <span m="419780">the</span> <span m="420240">same</span> <span m="420700">model,</span>
  <span m="421160">so</span> <span m="421620">current</span> <span m="422080">state</span>
  <span m="422540">is</span> <span m="423000">010</span> <span m="423460">and</span>
  <span m="423920">next</span> <span m="424380">state</span> <span m="424840">is</span>
  <span m="425300">011.</span></p><p><span m="425760">Here</span> <span m="426433">Asel</span>
  <span m="427106">=</span> <span m="427780">00,</span> <span m="428453">Bsel</span>
  <span m="429126">=</span> <span m="429800">01</span> <span m="430473">and</span>
  <span m="431146">Wsel</span> <span m="431820">=</span> <span m="432493">01</span>
  <span m="433166">and</span> <span m="433840">Wen</span> <span m="434513">=</span>
  <span m="435186">1.</span></p><p><span m="435860">Once</span> <span m="436273">again</span>
  <span m="436687">our</span> <span m="437101">Opsel</span> <span m="437515">is</span>
  <span m="437928">an</span> <span m="438342">ADD.</span> <span m="438756">We</span>
  <span m="439170">move</span> <span m="439583">on</span> <span m="439997">to</span>
  <span m="440411">state</span> <span m="440825">3</span> <span m="441238">whose</span>
  <span m="441652">current</span> <span m="442066">state</span> <span m="442480">is</span>
  <span m="443207">011</span> <span m="443934">and</span> <span m="444661">next</span>
  <span m="445388">state</span> <span m="446115">is</span> <span m="446842">100.</span>
  <span m="447569">Asel</span> <span m="448296">=</span> <span m="449023">01,</span>
  <span m="449750">Bsel</span> <span m="450477">=</span> <span m="451204">11,</span>
  <span m="451931">Wsel</span> <span m="452658">=</span> <span m="453385">11,</span>
  <span m="454112">and</span> <span m="454839">Wen</span> <span m="455566">=</span>
  <span m="456293">1.</span></p><p><span m="457020">Here</span> <span m="457454">our</span>
  <span m="457889">Opsel</span> <span m="458323">is</span> <span m="458758">MUL</span>
  <span m="459193">to</span> <span m="459627">indicate</span> <span m="460062">that</span>
  <span m="460497">the</span> <span m="460931">operation</span> <span m="461366">to</span>
  <span m="461801">be</span> <span m="462235">executed</span> <span m="462670">here</span>
  <span m="463105">is</span> <span m="463539">a</span> <span m="463974">multiply.</span></p><p><span
  m="464409">For</span> <span m="464906">state</span> <span m="465403">four,</span>
  <span m="465901">we</span> <span m="466398">have</span> <span m="466896">current</span>
  <span m="467393">state</span> <span m="467890">set</span> <span m="468388">to</span>
  <span m="468885">100</span> <span m="469383">and</span> <span m="469880">next</span>
  <span m="470377">state</span> <span m="470875">to</span> <span m="471372">101.</span></p><p><span
  m="471870">Asel</span> <span m="472452">=</span> <span m="473034">11,</span> <span
  m="473616">Bsel</span> <span m="474198">=</span> <span m="474780">10,</span> <span
  m="475362">Wsel</span> <span m="475944">=</span> <span m="476526">11,</span> <span
  m="477108">and</span> <span m="477691">Wen</span> <span m="478273">=</span> <span
  m="478855">1.</span> <span m="479437">Our</span> <span m="480019">Opsel</span> <span
  m="480601">is</span> <span m="481183">once</span> <span m="481765">again</span>
  <span m="482347">ADD.</span></p><p><span m="482930">Finally,</span> <span m="483322">we</span>
  <span m="483714">reach</span> <span m="484106">state</span> <span m="484499">5.</span>
  <span m="484891">This</span> <span m="485283">state</span> <span m="485676">looks</span>
  <span m="486068">a</span> <span m="486460">little</span> <span m="486853">different</span>
  <span m="487245">from</span> <span m="487637">the</span> <span m="488030">previous</span>
  <span m="488389">states</span> <span m="488748">so</span> <span m="489107">lets</span>
  <span m="489466">examine</span> <span m="489825">it</span> <span m="490184">a</span>
  <span m="490543">little</span> <span m="490902">more</span> <span m="491261">closely.</span></p><p><span
  m="491620">The</span> <span m="491843">first</span> <span m="492067">thing</span>
  <span m="492290">to</span> <span m="492514">note,</span> <span m="492737">is</span>
  <span m="492961">that</span> <span m="493184">when</span> <span m="493408">we</span>
  <span m="493631">get</span> <span m="493855">to</span> <span m="494078">state</span>
  <span m="494302">5</span> <span m="494525">we</span> <span m="494749">want</span>
  <span m="494972">to</span> <span m="495196">stay</span> <span m="495419">there</span>
  <span m="495643">because</span> <span m="495866">we</span> <span m="496090">are</span>
  <span m="496531">done</span> <span m="496972">with</span> <span m="497413">our</span>
  <span m="497855">execution,</span> <span m="498296">so</span> <span m="498737">both</span>
  <span m="499178">the</span> <span m="499620">current</span> <span m="500061">state</span>
  <span m="500502">and</span> <span m="500943">the</span> <span m="501385">next</span>
  <span m="501826">state</span> <span m="502267">are</span> <span m="502708">101.</span></p><p><span
  m="503150">Most</span> <span m="503470">of</span> <span m="503790">the</span> <span
  m="504110">other</span> <span m="504430">control</span> <span m="504750">bits</span>
  <span m="505070">can</span> <span m="505390">be</span> <span m="505710">set</span>
  <span m="506030">to</span> <span m="506350">don't</span> <span m="506670">care</span>
  <span m="506990">because</span> <span m="507310">at</span> <span m="507630">this</span>
  <span m="507950">point</span> <span m="508270">we</span> <span m="508590">mostly</span>
  <span m="508910">don't</span> <span m="509229">care</span> <span m="509549">about</span>
  <span m="509869">what</span> <span m="510189">the</span> <span m="510509">rest</span>
  <span m="510829">of</span> <span m="511149">the</span> <span m="511469">datapath</span>
  <span m="511789">is</span> <span m="512109">doing.</span></p><p><span m="512429">The</span>
  <span m="512779">only</span> <span m="513130">other</span> <span m="513481">signal</span>
  <span m="513832">that</span> <span m="514183">we</span> <span m="514534">do</span>
  <span m="514884">need</span> <span m="515235">to</span> <span m="515586">worry</span>
  <span m="515937">about</span> <span m="516288">is</span> <span m="516639">Wen.</span></p><p><span
  m="516990">Since</span> <span m="517255">we</span> <span m="517521">are</span> <span
  m="517786">allowing</span> <span m="518052">the</span> <span m="518317">rest</span>
  <span m="518583">of</span> <span m="518848">our</span> <span m="519114">datapath</span>
  <span m="519380">to</span> <span m="519645">run</span> <span m="519911">in</span>
  <span m="520176">whatever</span> <span m="520442">way,</span> <span m="520707">we</span>
  <span m="520973">need</span> <span m="521238">to</span> <span m="521504">ensure</span>
  <span m="521770">that</span> <span m="522110">nothing</span> <span m="522450">produced</span>
  <span m="522790">on</span> <span m="523130">the</span> <span m="523470">datapath</span>
  <span m="523810">at</span> <span m="524150">this</span> <span m="524490">stage</span>
  <span m="524830">gets</span> <span m="525170">written</span> <span m="525510">back</span>
  <span m="525850">to</span> <span m="526190">any</span> <span m="526530">of</span>
  <span m="526870">the</span> <span m="527210">registers.</span></p><p><span m="527550">In</span>
  <span m="527970">order</span> <span m="528390">to</span> <span m="528810">guarantee</span>
  <span m="529230">that,</span> <span m="529650">we</span> <span m="530070">set</span>
  <span m="530490">Wen</span> <span m="530910">=</span> <span m="531330">0.</span>
  <span m="531750">Here</span> <span m="532170">is</span> <span m="532590">the</span>
  <span m="533010">complete</span> <span m="533430">control</span> <span m="533850">ROM</span>
  <span m="534270">that</span> <span m="534690">will</span> <span m="535110">execute</span>
  <span m="535713">the</span> <span m="536316">function</span> <span m="536919">3*N-2</span>
  <span m="537522">and</span> <span m="538125">store</span> <span m="538728">its</span>
  <span m="539331">result</span> <span m="539934">into</span> <span m="540537">R3.</span></p>
type: course
uid: 29db23928611d1e84c3f58ddd6cbfb40

---
None