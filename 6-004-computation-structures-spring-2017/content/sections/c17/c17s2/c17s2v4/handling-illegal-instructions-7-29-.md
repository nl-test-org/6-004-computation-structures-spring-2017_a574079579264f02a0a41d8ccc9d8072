---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: usMPXTDOIn0
  parent_uid: 37ff46e3dcc2a1a902e33a18523bc264
  title: Video-YouTube-Stream
  type: Video
  uid: 9e878ea7a99aecd5fe9a1c86a6991f8e
- id: 3Play-3Play YouTube id-Stream
  media_location: usMPXTDOIn0
  parent_uid: 37ff46e3dcc2a1a902e33a18523bc264
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: ba0951d48dab8c50456d5fde2f542f50
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/usMPXTDOIn0/default.jpg
  parent_uid: 37ff46e3dcc2a1a902e33a18523bc264
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: b86030986c1090d475d9c44b9078b725
- id: usMPXTDOIn0.srt
  parent_uid: 37ff46e3dcc2a1a902e33a18523bc264
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v4/handling-illegal-instructions-7-29-/usMPXTDOIn0.srt
  title: 3play caption file
  type: null
  uid: 507b33a02296e3b8815350343980b7ce
- id: usMPXTDOIn0.pdf
  parent_uid: 37ff46e3dcc2a1a902e33a18523bc264
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v4/handling-illegal-instructions-7-29-/usMPXTDOIn0.pdf
  title: 3play pdf file
  type: null
  uid: 0baf35eb560701888b6ed9b1d3bf06ab
- id: Caption-3Play YouTube id-SRT
  parent_uid: 37ff46e3dcc2a1a902e33a18523bc264
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ccd3be83f1501b1dea5fe383a3dd4a65
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 37ff46e3dcc2a1a902e33a18523bc264
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 74cdac4c84ff63a9a6b77030dfbb3c2e
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_17-02-04_300k.mp4
  parent_uid: 37ff46e3dcc2a1a902e33a18523bc264
  title: Video-Internet Archive-MP4
  type: Video
  uid: 3dd5707af0391ea00aa31eb910485c95
inline_embed_id: 80703760handlingillegalinstructions72916436523
layout: video
order_index: null
parent_uid: e031e25dcca2760fc063a5091f11b94b
related_resources_text: ''
short_url: handling-illegal-instructions-7-29-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v4/handling-illegal-instructions-7-29-
template_type: Embed
title: Handling Illegal Instructions
transcript: <p><span m="570">Another</span> <span m="949">service</span> <span m="1328">provided</span>
  <span m="1707">by</span> <span m="2087">operating</span> <span m="2466">system</span>
  <span m="2845">is</span> <span m="3225">dealing</span> <span m="3604">properly</span>
  <span m="3983">with</span> <span m="4362">the</span> <span m="4742">attempt</span>
  <span m="5121">to</span> <span m="5500">execute</span> <span m="5880">instructions</span>
  <span m="6765">with</span> <span m="7650">&quot;illegal&quot;</span> <span m="8535">opcodes.</span></p><p><span
  m="9420">Illegal</span> <span m="9780">is</span> <span m="10140">quotes</span> <span
  m="10500">because</span> <span m="10860">that</span> <span m="11220">just</span>
  <span m="11580">means</span> <span m="11940">opcodes</span> <span m="12300">whose</span>
  <span m="12660">operations</span> <span m="13020">aren't</span> <span m="13380">implemented</span>
  <span m="13740">directly</span> <span m="14077">by</span> <span m="14414">the</span>
  <span m="14751">hardware.</span></p><p><span m="15089">As</span> <span m="15610">we'll</span>
  <span m="16132">see,</span> <span m="16653">it's</span> <span m="17175">possible</span>
  <span m="17696">extend</span> <span m="18218">the</span> <span m="18739">functionality</span>
  <span m="19261">of</span> <span m="19782">the</span> <span m="20304">hardware</span>
  <span m="20825">via</span> <span m="21347">software</span> <span m="21868">emulation.</span></p><p><span
  m="22390">The</span> <span m="22728">action</span> <span m="23066">of</span> <span
  m="23405">the</span> <span m="23743">CPU</span> <span m="24081">upon</span> <span
  m="24420">encountering</span> <span m="24758">an</span> <span m="25097">illegal</span>
  <span m="25435">instruction</span> <span m="25773">(sometimes</span> <span m="26112">referred</span>
  <span m="26450">to</span> <span m="26789">as</span> <span m="27309">an</span> <span
  m="27829">unimplemented</span> <span m="28349">user</span> <span m="28869">operation</span>
  <span m="29389">or</span> <span m="29909">UUO)</span> <span m="30429">is</span>
  <span m="30949">very</span> <span m="31469">similar</span> <span m="31989">to</span>
  <span m="32509">how</span> <span m="33029">it</span> <span m="33549">processes</span>
  <span m="34069">interrupts.</span></p><p><span m="34590">Think</span> <span m="34988">of</span>
  <span m="35386">illegal</span> <span m="35785">instructions</span> <span m="36183">as</span>
  <span m="36581">an</span> <span m="36980">interrupt</span> <span m="37378">caused</span>
  <span m="37776">directly</span> <span m="38175">by</span> <span m="38573">the</span>
  <span m="38971">CPU!</span></p><p><span m="39370">As</span> <span m="39763">for</span>
  <span m="40156">interrupts,</span> <span m="40550">the</span> <span m="40943">execution</span>
  <span m="41336">of</span> <span m="41730">the</span> <span m="42123">current</span>
  <span m="42516">instruction</span> <span m="42910">is</span> <span m="43303">suspended</span>
  <span m="43696">and</span> <span m="44090">the</span> <span m="44483">control</span>
  <span m="44876">signals</span> <span m="45270">are</span> <span m="45692">set</span>
  <span m="46114">to</span> <span m="46536">values</span> <span m="46958">to</span>
  <span m="47380">capture</span> <span m="47802">PC+4</span> <span m="48224">in</span>
  <span m="48646">the</span> <span m="49068">XP</span> <span m="49490">register</span>
  <span m="49912">and</span> <span m="50334">set</span> <span m="50756">the</span>
  <span m="51178">PC</span> <span m="51600">to,</span> <span m="52022">in</span> <span
  m="52444">this</span> <span m="52866">case,</span> <span m="53289">0x80000004.</span></p><p><span
  m="55500">Note</span> <span m="55831">that</span> <span m="56163">bit</span> <span
  m="56495">31</span> <span m="56827">of</span> <span m="57159">the</span> <span m="57491">new</span>
  <span m="57823">PC,</span> <span m="58155">aka</span> <span m="58487">the</span>
  <span m="58819">supervisor</span> <span m="59150">bit,</span> <span m="59482">is</span>
  <span m="59814">set</span> <span m="60146">to</span> <span m="60478">1,</span> <span
  m="60810">meaning</span> <span m="61142">that</span> <span m="61474">the</span>
  <span m="61806">OS</span> <span m="62138">handler</span> <span m="62470">will</span>
  <span m="63002">have</span> <span m="63535">access</span> <span m="64068">to</span>
  <span m="64601">the</span> <span m="65134">kernel-mode</span> <span m="65667">context.</span></p><p><span
  m="66200">Here's</span> <span m="66445">some</span> <span m="66690">code</span>
  <span m="66935">similar</span> <span m="67180">to</span> <span m="67425">that</span>
  <span m="67670">found</span> <span m="67915">in</span> <span m="68160">the</span>
  <span m="68405">Tiny</span> <span m="68650">Operating</span> <span m="68895">System</span>
  <span m="69140">(TinyOS),</span> <span m="69385">which</span> <span m="69630">you'll</span>
  <span m="69920">be</span> <span m="70210">experimenting</span> <span m="70500">with</span>
  <span m="70790">in</span> <span m="71080">the</span> <span m="71370">final</span>
  <span m="71660">lab</span> <span m="71950">assignment.</span></p><p><span m="72240">Let's</span>
  <span m="72612">do</span> <span m="72985">a</span> <span m="73357">quick</span>
  <span m="73730">walk-through</span> <span m="74103">of</span> <span m="74475">the</span>
  <span m="74848">code</span> <span m="75220">executed</span> <span m="75593">when</span>
  <span m="75966">an</span> <span m="76338">illegal</span> <span m="76711">instruction</span>
  <span m="77083">is</span> <span m="77456">executed.</span></p><p><span m="77829">Starting</span>
  <span m="78088">at</span> <span m="78347">location</span> <span m="78607">0,</span>
  <span m="78866">we</span> <span m="79126">see</span> <span m="79385">the</span>
  <span m="79644">branches</span> <span m="79904">to</span> <span m="80163">the</span>
  <span m="80423">handlers</span> <span m="80682">for</span> <span m="80941">the</span>
  <span m="81201">various</span> <span m="81460">interrupts</span> <span m="81720">and</span>
  <span m="82259">exceptions.</span></p><p><span m="82799">In</span> <span m="83368">the</span>
  <span m="83937">case</span> <span m="84507">of</span> <span m="85076">an</span>
  <span m="85646">illegal</span> <span m="86215">instruction,</span> <span m="86784">the</span>
  <span m="87354">BR(I_IllOp)</span> <span m="87923">in</span> <span m="88493">location</span>
  <span m="89062">4</span> <span m="89631">will</span> <span m="90201">be</span> <span
  m="90770">executed.</span></p><p><span m="91340">Immediately</span> <span m="91749">following</span>
  <span m="92158">is</span> <span m="92567">where</span> <span m="92976">the</span>
  <span m="93385">OS</span> <span m="93794">data</span> <span m="94203">structures</span>
  <span m="94612">are</span> <span m="95021">allocated.</span></p><p><span m="95430">This</span>
  <span m="95826">includes</span> <span m="96222">space</span> <span m="96619">for</span>
  <span m="97015">the</span> <span m="97411">OS</span> <span m="97808">stack,</span>
  <span m="98204">UserMState</span> <span m="98600">where</span> <span m="98997">user-mode</span>
  <span m="99393">register</span> <span m="99789">values</span> <span m="100186">are</span>
  <span m="100582">stored</span> <span m="100979">during</span> <span m="101437">interrupts,</span>
  <span m="101895">and</span> <span m="102354">the</span> <span m="102812">process</span>
  <span m="103270">table,</span> <span m="103729">providing</span> <span m="104187">long-term</span>
  <span m="104645">storage</span> <span m="105104">for</span> <span m="105562">the</span>
  <span m="106020">complete</span> <span m="106479">state</span> <span m="106998">of</span>
  <span m="107518">each</span> <span m="108038">process</span> <span m="108558">while</span>
  <span m="109078">another</span> <span m="109598">process</span> <span m="110118">is</span>
  <span m="110638">executing.</span></p><p><span m="111158">When</span> <span m="111478">writing</span>
  <span m="111799">in</span> <span m="112120">assembly</span> <span m="112440">language,</span>
  <span m="112761">it's</span> <span m="113082">convenient</span> <span m="113403">to</span>
  <span m="113723">define</span> <span m="114044">macros</span> <span m="114365">for</span>
  <span m="114686">operations</span> <span m="115006">that</span> <span m="115327">are</span>
  <span m="115648">used</span> <span m="115969">repeatedly.</span></p><p><span m="117590">We</span>
  <span m="117878">can</span> <span m="118167">use</span> <span m="118456">a</span>
  <span m="118745">macro</span> <span m="119034">call</span> <span m="119322">whenever</span>
  <span m="119611">we</span> <span m="119900">want</span> <span m="120189">to</span>
  <span m="120478">perform</span> <span m="120767">the</span> <span m="121055">action</span>
  <span m="121344">and</span> <span m="121633">the</span> <span m="121922">assembler</span>
  <span m="122211">will</span> <span m="122500">insert</span> <span m="122825">the</span>
  <span m="123150">body</span> <span m="123475">of</span> <span m="123800">the</span>
  <span m="124125">macro</span> <span m="124450">in</span> <span m="124775">place</span>
  <span m="125100">of</span> <span m="125425">the</span> <span m="125750">macro</span>
  <span m="126075">call,</span> <span m="126400">performing</span> <span m="126725">a</span>
  <span m="127050">lexical</span> <span m="127375">substitution</span> <span m="127700">of</span>
  <span m="128394">the</span> <span m="129089">macro's</span> <span m="129784">arguments.</span></p><p><span
  m="130479">Here's</span> <span m="130779">a</span> <span m="131079">macro</span>
  <span m="131379">for</span> <span m="131679">a</span> <span m="131979">two-instruction</span>
  <span m="132279">sequence</span> <span m="132579">that</span> <span m="132879">extracts</span>
  <span m="133179">a</span> <span m="133479">particular</span> <span m="133779">field</span>
  <span m="134079">of</span> <span m="134379">bits</span> <span m="134679">from</span>
  <span m="134980">a</span> <span m="135570">32-bit</span> <span m="136160">value.</span></p><p><span
  m="136750">M</span> <span m="137074">is</span> <span m="137398">the</span> <span
  m="137723">bit</span> <span m="138047">number</span> <span m="138372">of</span>
  <span m="138696">the</span> <span m="139021">left-most</span> <span m="139345">bit,</span>
  <span m="139670">N</span> <span m="139994">is</span> <span m="140318">the</span>
  <span m="140643">bit</span> <span m="140967">number</span> <span m="141292">of</span>
  <span m="141616">the</span> <span m="141941">right-most</span> <span m="142265">bit.</span></p><p><span
  m="142590">Bits</span> <span m="142970">are</span> <span m="143350">numbered</span>
  <span m="143730">0</span> <span m="144110">through</span> <span m="144490">31,</span>
  <span m="144870">where</span> <span m="145250">bit</span> <span m="145630">31</span>
  <span m="146010">is</span> <span m="146390">the</span> <span m="146770">most-significant</span>
  <span m="147150">bit,</span> <span m="147530">i.e.,</span> <span m="147910">the</span>
  <span m="148290">one</span> <span m="148772">at</span> <span m="149254">the</span>
  <span m="149736">left</span> <span m="150218">end</span> <span m="150700">of</span>
  <span m="151182">the</span> <span m="151664">32-bit</span> <span m="152146">binary</span>
  <span m="152628">value.</span></p><p><span m="153110">And</span> <span m="153441">here</span>
  <span m="153772">are</span> <span m="154104">some</span> <span m="154435">macros</span>
  <span m="154767">that</span> <span m="155098">expand</span> <span m="155430">into</span>
  <span m="155761">instruction</span> <span m="156092">sequences</span> <span m="156424">that</span>
  <span m="156755">save</span> <span m="157087">and</span> <span m="157418">restore</span>
  <span m="157750">the</span> <span m="158300">CPU</span> <span m="158850">registers</span>
  <span m="159400">to</span> <span m="159950">or</span> <span m="160500">from</span>
  <span m="161050">the</span> <span m="161600">UserMState</span> <span m="162150">temporary</span>
  <span m="162700">storage</span> <span m="163250">area.</span></p><p><span m="163800">With</span>
  <span m="164196">those</span> <span m="164593">macros</span> <span m="164990">in</span>
  <span m="165386">hand,</span> <span m="165783">let's</span> <span m="166180">see</span>
  <span m="166576">how</span> <span m="166973">illegal</span> <span m="167370">opcodes</span>
  <span m="167766">are</span> <span m="168163">handled.</span></p><p><span m="168560">Like</span>
  <span m="168863">all</span> <span m="169166">interrupt</span> <span m="169470">handlers,</span>
  <span m="169773">the</span> <span m="170076">first</span> <span m="170380">action</span>
  <span m="170683">is</span> <span m="170986">to</span> <span m="171290">save</span>
  <span m="171593">the</span> <span m="171896">user-mode</span> <span m="172200">registers</span>
  <span m="172503">in</span> <span m="172806">the</span> <span m="173110">temporary</span>
  <span m="173662">storage</span> <span m="174215">area</span> <span m="174767">and</span>
  <span m="175320">initialize</span> <span m="175872">the</span> <span m="176425">OS</span>
  <span m="176977">stack.</span></p><p><span m="177530">Next,</span> <span m="178003">we</span>
  <span m="178476">fetch</span> <span m="178949">the</span> <span m="179422">illegal</span>
  <span m="179895">instruction</span> <span m="180368">from</span> <span m="180841">the</span>
  <span m="181314">user-mode</span> <span m="181787">program.</span></p><p><span m="182260">Note</span>
  <span m="182600">that</span> <span m="182941">the</span> <span m="183281">saved</span>
  <span m="183622">PC+4</span> <span m="183963">value</span> <span m="184303">is</span>
  <span m="184644">a</span> <span m="184985">virtual</span> <span m="185325">address</span>
  <span m="185666">in</span> <span m="186006">the</span> <span m="186347">context</span>
  <span m="186688">of</span> <span m="187028">the</span> <span m="187369">interrupted</span>
  <span m="187710">program.</span></p><p><span m="188950">So</span> <span m="189252">we'll</span>
  <span m="189554">need</span> <span m="189857">to</span> <span m="190159">use</span>
  <span m="190461">the</span> <span m="190764">MMU</span> <span m="191066">routines</span>
  <span m="191368">to</span> <span m="191671">compute</span> <span m="191973">the</span>
  <span m="192275">correct</span> <span m="192578">physical</span> <span m="192880">address</span>
  <span m="193182">-</span> <span m="193485">more</span> <span m="193787">about</span>
  <span m="194090">this</span> <span m="194654">on</span> <span m="195218">the</span>
  <span m="195782">next</span> <span m="196346">slide.</span></p><p><span m="196910">Then</span>
  <span m="197269">we'll</span> <span m="197628">use</span> <span m="197988">the</span>
  <span m="198347">opcode</span> <span m="198707">of</span> <span m="199066">the</span>
  <span m="199426">illegal</span> <span m="199785">instruction</span> <span m="200145">as</span>
  <span m="200504">an</span> <span m="200863">index</span> <span m="201223">into</span>
  <span m="201582">a</span> <span m="201942">table</span> <span m="202301">of</span>
  <span m="202661">subroutine</span> <span m="203020">addresses,</span> <span m="203380">one</span>
  <span m="203951">for</span> <span m="204522">each</span> <span m="205093">of</span>
  <span m="205665">the</span> <span m="206236">64</span> <span m="206807">possible</span>
  <span m="207378">opcodes.</span></p><p><span m="207950">Once</span> <span m="208269">we</span>
  <span m="208588">have</span> <span m="208908">the</span> <span m="209227">address</span>
  <span m="209547">of</span> <span m="209866">the</span> <span m="210186">handler</span>
  <span m="210505">for</span> <span m="210824">this</span> <span m="211144">particular</span>
  <span m="211463">illegal</span> <span m="211783">opcode,</span> <span m="212102">we</span>
  <span m="212422">JMP</span> <span m="212741">there</span> <span m="213061">to</span>
  <span m="213694">deal</span> <span m="214328">with</span> <span m="214962">the</span>
  <span m="215596">situation.</span></p><p><span m="216230">Selecting</span> <span
  m="216573">a</span> <span m="216917">destination</span> <span m="217261">from</span>
  <span m="217605">a</span> <span m="217948">table</span> <span m="218292">of</span>
  <span m="218636">addresses</span> <span m="218980">is</span> <span m="219323">called</span>
  <span m="219667">&quot;dispatching&quot;</span> <span m="220011">and</span> <span
  m="220355">the</span> <span m="220698">table</span> <span m="221042">is</span> <span
  m="221386">called</span> <span m="221730">the</span> <span m="222493">&quot;dispatch</span>
  <span m="223256">table&quot;.</span></p><p><span m="224020">If</span> <span m="224387">the</span>
  <span m="224755">dispatch</span> <span m="225123">table</span> <span m="225490">contains</span>
  <span m="225858">many</span> <span m="226226">different</span> <span m="226593">entries,</span>
  <span m="226961">dispatching</span> <span m="227329">is</span> <span m="227696">much</span>
  <span m="228064">more</span> <span m="228432">efficient</span> <span m="228800">in</span>
  <span m="229178">time</span> <span m="229556">and</span> <span m="229935">space</span>
  <span m="230313">than</span> <span m="230691">a</span> <span m="231070">long</span>
  <span m="231448">series</span> <span m="231826">of</span> <span m="232205">compares</span>
  <span m="232583">and</span> <span m="232961">branches.</span></p><p><span m="233340">In</span>
  <span m="233652">this</span> <span m="233965">case,</span> <span m="234277">the</span>
  <span m="234590">table</span> <span m="234902">is</span> <span m="235215">indicating</span>
  <span m="235527">that</span> <span m="235840">the</span> <span m="236152">handler</span>
  <span m="236465">for</span> <span m="236777">most</span> <span m="237090">illegal</span>
  <span m="237402">opcodes</span> <span m="237715">is</span> <span m="238027">the</span>
  <span m="238340">UUOError</span> <span m="238874">routine,</span> <span m="239408">so</span>
  <span m="239942">it</span> <span m="240476">might</span> <span m="241010">have</span>
  <span m="241544">smaller</span> <span m="242078">and</span> <span m="242612">faster</span>
  <span m="243146">simply</span> <span m="243680">to</span> <span m="244159">test</span>
  <span m="244638">for</span> <span m="245117">the</span> <span m="245596">two</span>
  <span m="246076">illegal</span> <span m="246555">opcodes</span> <span m="247034">the</span>
  <span m="247513">OS</span> <span m="247993">is</span> <span m="248472">going</span>
  <span m="248951">to</span> <span m="249430">emulate.</span></p><p><span m="249910">Illegal</span>
  <span m="250262">opcode</span> <span m="250615">1</span> <span m="250968">will</span>
  <span m="251320">be</span> <span m="251673">used</span> <span m="252026">to</span>
  <span m="252378">implement</span> <span m="252731">procedure</span> <span m="253084">calls</span>
  <span m="253436">from</span> <span m="253789">user-mode</span> <span m="254142">to</span>
  <span m="254494">the</span> <span m="254847">OS,</span> <span m="255200">which</span>
  <span m="255715">we</span> <span m="256231">call</span> <span m="256747">supervisor</span>
  <span m="257263">calls.</span></p><p><span m="257779">More</span> <span m="258224">on</span>
  <span m="258670">this</span> <span m="259116">in</span> <span m="259561">the</span>
  <span m="260007">next</span> <span m="260453">segment.</span></p><p><span m="260899">As</span>
  <span m="261225">an</span> <span m="261551">example</span> <span m="261877">of</span>
  <span m="262204">having</span> <span m="262530">the</span> <span m="262856">OS</span>
  <span m="263183">emulate</span> <span m="263509">an</span> <span m="263835">instruction,</span>
  <span m="264162">we'll</span> <span m="264488">use</span> <span m="264814">illegal</span>
  <span m="265141">opcode</span> <span m="265467">2</span> <span m="265793">as</span>
  <span m="266120">the</span> <span m="266548">opcode</span> <span m="266976">for</span>
  <span m="267404">the</span> <span m="267832">SWAPREG</span> <span m="268260">instruction,</span>
  <span m="268688">which</span> <span m="269116">we'll</span> <span m="269544">discuss</span>
  <span m="269972">now.</span></p><p><span m="270400">But</span> <span m="270729">first</span>
  <span m="271058">just</span> <span m="271388">a</span> <span m="271717">quick</span>
  <span m="272046">look</span> <span m="272376">at</span> <span m="272705">how</span>
  <span m="273034">the</span> <span m="273364">OS</span> <span m="273693">converts</span>
  <span m="274022">user-mode</span> <span m="274352">virtual</span> <span m="274681">addresses</span>
  <span m="275010">into</span> <span m="275340">physical</span> <span m="275910">addresses</span>
  <span m="276480">it</span> <span m="277050">can</span> <span m="277620">use.</span></p><p><span
  m="278190">We'll</span> <span m="278676">build</span> <span m="279163">on</span>
  <span m="279650">the</span> <span m="280136">MMU</span> <span m="280623">VtoP</span>
  <span m="281110">procedure,</span> <span m="281596">described</span> <span m="282083">in</span>
  <span m="282570">the</span> <span m="283056">previous</span> <span m="283543">lecture.</span></p><p><span
  m="284030">This</span> <span m="284336">procedure</span> <span m="284643">expects</span>
  <span m="284950">as</span> <span m="285256">its</span> <span m="285563">arguments</span>
  <span m="285870">the</span> <span m="286176">virtual</span> <span m="286483">page</span>
  <span m="286790">number</span> <span m="287096">and</span> <span m="287403">offset</span>
  <span m="287710">fields</span> <span m="288016">of</span> <span m="288323">the</span>
  <span m="288630">virtual</span> <span m="289153">address,</span> <span m="289676">so,</span>
  <span m="290200">following</span> <span m="290723">our</span> <span m="291246">convention</span>
  <span m="291770">for</span> <span m="292293">passing</span> <span m="292816">arguments</span>
  <span m="293340">to</span> <span m="293745">C</span> <span m="294151">procedures,</span>
  <span m="294557">these</span> <span m="294963">are</span> <span m="295369">pushed</span>
  <span m="295775">onto</span> <span m="296180">the</span> <span m="296586">stack</span>
  <span m="296992">in</span> <span m="297398">reverse</span> <span m="297804">order.</span></p><p><span
  m="298210">The</span> <span m="298786">corresponding</span> <span m="299362">physical</span>
  <span m="299938">address</span> <span m="300515">is</span> <span m="301091">returned</span>
  <span m="301667">in</span> <span m="302243">R0.</span></p><p><span m="302820">We</span>
  <span m="303182">can</span> <span m="303544">then</span> <span m="303906">use</span>
  <span m="304268">the</span> <span m="304630">calculated</span> <span m="304992">physical</span>
  <span m="305354">address</span> <span m="305716">to</span> <span m="306078">read</span>
  <span m="306440">the</span> <span m="306802">desired</span> <span m="307164">location</span>
  <span m="307526">from</span> <span m="307888">physical</span> <span m="308250">memory.</span></p><p><span
  m="309250">Okay,</span> <span m="309781">back</span> <span m="310312">to</span>
  <span m="310844">dealing</span> <span m="311375">with</span> <span m="311907">illegal</span>
  <span m="312438">opcodes.</span></p><p><span m="312970">Here's</span> <span m="313278">the</span>
  <span m="313587">handler</span> <span m="313896">for</span> <span m="314205">opcodes</span>
  <span m="314514">that</span> <span m="314823">are</span> <span m="315132">truly</span>
  <span m="315441">illegal.</span></p><p><span m="315750">In</span> <span m="316010">this</span>
  <span m="316271">case</span> <span m="316531">the</span> <span m="316792">OS</span>
  <span m="317052">uses</span> <span m="317313">various</span> <span m="317573">kernel</span>
  <span m="317834">routines</span> <span m="318095">to</span> <span m="318355">print</span>
  <span m="318616">out</span> <span m="318876">a</span> <span m="319137">helpful</span>
  <span m="319397">error</span> <span m="319658">message</span> <span m="319918">on</span>
  <span m="320179">the</span> <span m="320440">user's</span> <span m="321028">console,</span>
  <span m="321616">then</span> <span m="322205">crashes</span> <span m="322793">the</span>
  <span m="323381">system!</span></p><p><span m="323970">You</span> <span m="324238">may</span>
  <span m="324506">have</span> <span m="324774">seen</span> <span m="325042">these</span>
  <span m="325311">&quot;blue</span> <span m="325579">screens</span> <span m="325847">of</span>
  <span m="326115">death&quot;</span> <span m="326384">if</span> <span m="326652">you</span>
  <span m="326920">run</span> <span m="327188">the</span> <span m="327457">Windows</span>
  <span m="327725">operating</span> <span m="327993">system,</span> <span m="328261">full</span>
  <span m="328530">of</span> <span m="329105">cryptic</span> <span m="329680">hex</span>
  <span m="330255">numbers.</span></p><p><span m="330830">Actually,</span> <span m="331149">this</span>
  <span m="331468">wouldn't</span> <span m="331788">be</span> <span m="332107">the</span>
  <span m="332426">best</span> <span m="332746">approach</span> <span m="333065">to</span>
  <span m="333384">handling</span> <span m="333704">an</span> <span m="334023">illegal</span>
  <span m="334342">opcode</span> <span m="334662">in</span> <span m="334981">a</span>
  <span m="335300">user's</span> <span m="335620">program.</span></p><p><span m="336620">In</span>
  <span m="336871">a</span> <span m="337123">real</span> <span m="337374">operating</span>
  <span m="337626">system,</span> <span m="337877">it</span> <span m="338129">would</span>
  <span m="338381">be</span> <span m="338632">better</span> <span m="338884">to</span>
  <span m="339135">save</span> <span m="339387">the</span> <span m="339638">state</span>
  <span m="339890">of</span> <span m="340142">the</span> <span m="340393">process</span>
  <span m="340645">in</span> <span m="340896">a</span> <span m="341148">special</span>
  <span m="341400">debugging</span> <span m="341867">file</span> <span m="342335">historically</span>
  <span m="342803">referred</span> <span m="343271">to</span> <span m="343738">as</span>
  <span m="344206">a</span> <span m="344674">&quot;core</span> <span m="345142">dump&quot;</span>
  <span m="345610">and</span> <span m="345992">then</span> <span m="346374">terminate</span>
  <span m="346756">this</span> <span m="347139">particular</span> <span m="347521">process,</span>
  <span m="347903">perhaps</span> <span m="348286">printing</span> <span m="348668">a</span>
  <span m="349050">short</span> <span m="349433">error</span> <span m="349815">message</span>
  <span m="350197">on</span> <span m="350580">the</span> <span m="350941">user's</span>
  <span m="351302">console</span> <span m="351663">to</span> <span m="352024">let</span>
  <span m="352385">them</span> <span m="352746">know</span> <span m="353107">what</span>
  <span m="353468">happened.</span></p><p><span m="353830">Then</span> <span m="354133">later</span>
  <span m="354437">the</span> <span m="354740">user</span> <span m="355044">could</span>
  <span m="355347">start</span> <span m="355651">a</span> <span m="355954">debugging</span>
  <span m="356258">program</span> <span m="356561">to</span> <span m="356865">examine</span>
  <span m="357168">the</span> <span m="357472">dump</span> <span m="357775">file</span>
  <span m="358079">to</span> <span m="358382">see</span> <span m="358686">where</span>
  <span m="358990">their</span> <span m="359490">bug</span> <span m="359990">is.</span></p><p><span
  m="360490">Finally,</span> <span m="360885">here's</span> <span m="361280">the</span>
  <span m="361675">handler</span> <span m="362070">that</span> <span m="362465">will</span>
  <span m="362860">emulate</span> <span m="363255">the</span> <span m="363650">actions</span>
  <span m="364045">of</span> <span m="364440">the</span> <span m="364835">SWAPREG</span>
  <span m="365230">instruction,</span> <span m="365625">after</span> <span m="366020">which</span>
  <span m="366507">program</span> <span m="366994">execution</span> <span m="367481">will</span>
  <span m="367968">resume</span> <span m="368455">as</span> <span m="368942">if</span>
  <span m="369430">the</span> <span m="369917">instruction</span> <span m="370404">had</span>
  <span m="370891">been</span> <span m="371378">implemented</span> <span m="371865">in</span>
  <span m="372352">hardware.</span></p><p><span m="372840">SWAPREG</span> <span m="373258">is</span>
  <span m="373676">an</span> <span m="374095">instruction</span> <span m="374513">that</span>
  <span m="374932">swaps</span> <span m="375350">the</span> <span m="375769">values</span>
  <span m="376187">in</span> <span m="376606">the</span> <span m="377024">two</span>
  <span m="377443">specified</span> <span m="377861">registers.</span></p><p><span
  m="378280">To</span> <span m="378652">define</span> <span m="379024">a</span> <span
  m="379397">new</span> <span m="379769">instruction,</span> <span m="380141">we'd</span>
  <span m="380514">first</span> <span m="380886">have</span> <span m="381258">to</span>
  <span m="381631">let</span> <span m="382003">the</span> <span m="382375">assembler</span>
  <span m="382748">know</span> <span m="383120">to</span> <span m="383492">convert</span>
  <span m="383865">the</span> <span m="384237">swapreg(ra,rc)</span> <span m="384610">assembly</span>
  <span m="385204">language</span> <span m="385798">statement</span> <span m="386392">into</span>
  <span m="386986">binary.</span></p><p><span m="387580">In</span> <span m="387900">this</span>
  <span m="388220">case</span> <span m="388540">we'll</span> <span m="388860">use</span>
  <span m="389180">a</span> <span m="389500">binary</span> <span m="389820">format</span>
  <span m="390140">similar</span> <span m="390460">to</span> <span m="390780">the</span>
  <span m="391100">ADDC</span> <span m="391420">instruction,</span> <span m="391740">but</span>
  <span m="392060">setting</span> <span m="392380">the</span> <span m="392700">unused</span>
  <span m="393020">literal</span> <span m="393537">field</span> <span m="394055">to</span>
  <span m="394572">0.</span></p><p><span m="395090">The</span> <span m="395427">encoding</span>
  <span m="395765">for</span> <span m="396102">the</span> <span m="396440">RA</span>
  <span m="396778">and</span> <span m="397115">RC</span> <span m="397453">registers</span>
  <span m="397791">occur</span> <span m="398128">in</span> <span m="398466">their</span>
  <span m="398804">usual</span> <span m="399141">fields</span> <span m="399479">and</span>
  <span m="399817">the</span> <span m="400154">opcode</span> <span m="400492">field</span>
  <span m="400830">is</span> <span m="401687">set</span> <span m="402545">to</span>
  <span m="403402">2.</span></p><p><span m="404260">Emulation</span> <span m="404817">is</span>
  <span m="405375">surprisingly</span> <span m="405932">simple.</span></p><p><span
  m="406490">First</span> <span m="406820">we</span> <span m="407150">extract</span>
  <span m="407480">the</span> <span m="407810">RA</span> <span m="408140">and</span>
  <span m="408470">RC</span> <span m="408800">fields</span> <span m="409130">from</span>
  <span m="409460">the</span> <span m="409790">binary</span> <span m="410120">for</span>
  <span m="410450">the</span> <span m="410780">swapreg</span> <span m="411110">instruction</span>
  <span m="411440">and</span> <span m="411770">convert</span> <span m="412186">those</span>
  <span m="412602">values</span> <span m="413018">into</span> <span m="413434">the</span>
  <span m="413850">appropriate</span> <span m="414266">byte</span> <span m="414683">offsets</span>
  <span m="415099">for</span> <span m="415515">accessing</span> <span m="415931">the</span>
  <span m="416347">temporary</span> <span m="416763">array</span> <span m="417180">of</span>
  <span m="417767">saved</span> <span m="418355">register</span> <span m="418942">values.</span></p><p><span
  m="419530">Then</span> <span m="419840">we</span> <span m="420151">use</span> <span
  m="420461">RA</span> <span m="420772">and</span> <span m="421082">RC</span> <span
  m="421393">offsets</span> <span m="421704">to</span> <span m="422014">access</span>
  <span m="422325">the</span> <span m="422635">user-mode</span> <span m="422946">register</span>
  <span m="423257">values</span> <span m="423567">that</span> <span m="423878">have</span>
  <span m="424188">been</span> <span m="424499">saved</span> <span m="424810">in</span>
  <span m="425925">UserMState.</span></p><p><span m="427040">We'll</span> <span m="427475">make</span>
  <span m="427911">the</span> <span m="428347">appropriate</span> <span m="428783">interchange,</span>
  <span m="429219">leaving</span> <span m="429655">the</span> <span m="430090">updated</span>
  <span m="430526">register</span> <span m="430962">values</span> <span m="431398">in</span>
  <span m="431834">UserMState,</span> <span m="432270">where</span> <span m="432625">they'll</span>
  <span m="432980">be</span> <span m="433335">loaded</span> <span m="433690">into</span>
  <span m="434045">the</span> <span m="434400">CPU</span> <span m="434755">registers</span>
  <span m="435110">upon</span> <span m="435465">returning</span> <span m="435820">from</span>
  <span m="436175">the</span> <span m="436530">illegal</span> <span m="436885">instruction</span>
  <span m="437240">interrupt</span> <span m="438135">handler.</span></p><p><span m="439030">Finally,</span>
  <span m="439486">we'll</span> <span m="439942">branch</span> <span m="440398">to</span>
  <span m="440854">the</span> <span m="441310">kernel</span> <span m="441766">code</span>
  <span m="442222">that</span> <span m="442678">restores</span> <span m="443134">the</span>
  <span m="443590">process</span> <span m="444046">state</span> <span m="444502">and</span>
  <span m="444958">resumes</span> <span m="445414">execution.</span></p><p><span m="445870">We'll</span>
  <span m="446151">see</span> <span m="446432">this</span> <span m="446713">code</span>
  <span m="446995">in</span> <span m="447276">the</span> <span m="447557">next</span>
  <span m="447838">segment.</span></p>
type: course
uid: 37ff46e3dcc2a1a902e33a18523bc264

---
None