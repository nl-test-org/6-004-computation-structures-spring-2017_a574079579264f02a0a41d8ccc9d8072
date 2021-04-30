---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 5oOdsbRPb2Y
  parent_uid: b4e8eac3c3fd0494925cbce70ad51eed
  title: Video-YouTube-Stream
  type: Video
  uid: 7ec0d2a23e7be33ef8d504e3acfabab3
- id: 3Play-3Play YouTube id-Stream
  media_location: 5oOdsbRPb2Y
  parent_uid: b4e8eac3c3fd0494925cbce70ad51eed
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 92c9a20194e11e8d84ed2d1919b8d4ad
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/5oOdsbRPb2Y/default.jpg
  parent_uid: b4e8eac3c3fd0494925cbce70ad51eed
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 923ec19598bf687eb8ec9b69f051b11c
- id: 5oOdsbRPb2Y.srt
  parent_uid: b4e8eac3c3fd0494925cbce70ad51eed
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/even-more-memory-hierarchy-7-09-/5oOdsbRPb2Y.srt
  title: 3play caption file
  type: null
  uid: 9e806a2f0d147dc858c8f76b442ecc7f
- id: 5oOdsbRPb2Y.pdf
  parent_uid: b4e8eac3c3fd0494925cbce70ad51eed
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/even-more-memory-hierarchy-7-09-/5oOdsbRPb2Y.pdf
  title: 3play pdf file
  type: null
  uid: 319ebf9c86f8e263b036fae39b15069a
- id: Caption-3Play YouTube id-SRT
  parent_uid: b4e8eac3c3fd0494925cbce70ad51eed
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: c16044dfac161a6c40aa50d3afd9e007
- id: Transcript-3Play YouTube id-PDF
  parent_uid: b4e8eac3c3fd0494925cbce70ad51eed
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: ec68e78df3fdc22838d532a11de73c7a
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_16-02-01_300k.mp4
  parent_uid: b4e8eac3c3fd0494925cbce70ad51eed
  title: Video-Internet Archive-MP4
  type: Video
  uid: b4b23326461fa0abc32826003eb3a88e
inline_embed_id: 3475318evenmorememoryhierarchy70923038070
layout: video
order_index: null
parent_uid: 3b281e42db108f1ff6e471fa803f6cdf
related_resources_text: ''
short_url: even-more-memory-hierarchy-7-09-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/even-more-memory-hierarchy-7-09-
template_type: Embed
title: Even More Memory Hierarchy
transcript: <p><span m="320">In</span> <span m="602">this</span> <span m="884">lecture</span>
  <span m="1166">we</span> <span m="1448">return</span> <span m="1731">to</span> <span
  m="2013">the</span> <span m="2295">memory</span> <span m="2577">system</span> <span
  m="2860">that</span> <span m="3142">we</span> <span m="3424">last</span> <span m="3706">discussed</span>
  <span m="3988">in</span> <span m="4271">Lecture</span> <span m="4553">14</span>
  <span m="4835">of</span> <span m="5117">Part</span> <span m="5400">2.</span></p><p><span
  m="6760">There</span> <span m="7097">we</span> <span m="7434">learned</span> <span
  m="7771">about</span> <span m="8108">the</span> <span m="8445">fundamental</span>
  <span m="8782">tradeoff</span> <span m="9120">in</span> <span m="9457">current</span>
  <span m="9794">memory</span> <span m="10131">technologies:</span> <span m="10468">as</span>
  <span m="10805">the</span> <span m="11142">memory's</span> <span m="11480">capacity</span>
  <span m="12065">increases,</span> <span m="12651">so</span> <span m="13237">does</span>
  <span m="13822">it</span> <span m="14408">access</span> <span m="14994">time.</span></p><p><span
  m="15580">It</span> <span m="15856">takes</span> <span m="16132">some</span> <span
  m="16408">architectural</span> <span m="16684">cleverness</span> <span m="16960">to</span>
  <span m="17236">build</span> <span m="17512">a</span> <span m="17788">memory</span>
  <span m="18064">system</span> <span m="18340">that</span> <span m="18616">has</span>
  <span m="18892">a</span> <span m="19168">large</span> <span m="19444">capacity</span>
  <span m="19720">and</span> <span m="20260">a</span> <span m="20800">small</span>
  <span m="21340">average</span> <span m="21880">access</span> <span m="22420">time.</span></p><p><span
  m="22960">The</span> <span m="23289">cleverness</span> <span m="23618">is</span>
  <span m="23947">embodied</span> <span m="24277">in</span> <span m="24606">the</span>
  <span m="24935">cache,</span> <span m="25265">a</span> <span m="25594">hardware</span>
  <span m="25923">subsystem</span> <span m="26252">that</span> <span m="26582">lives</span>
  <span m="26911">between</span> <span m="27240">the</span> <span m="27570">CPU</span>
  <span m="28147">and</span> <span m="28725">main</span> <span m="29302">memory.</span></p><p><span
  m="29880">Modern</span> <span m="30332">CPUs</span> <span m="30784">have</span>
  <span m="31236">several</span> <span m="31689">levels</span> <span m="32141">of</span>
  <span m="32593">cache,</span> <span m="33046">where</span> <span m="33498">the</span>
  <span m="33950">modest-capacity</span> <span m="34403">first</span> <span m="34855">level</span>
  <span m="35307">has</span> <span m="35760">an</span> <span m="36068">access</span>
  <span m="36377">time</span> <span m="36686">close</span> <span m="36995">to</span>
  <span m="37304">that</span> <span m="37612">of</span> <span m="37921">the</span>
  <span m="38230">CPU,</span> <span m="38539">and</span> <span m="38848">higher</span>
  <span m="39157">levels</span> <span m="39465">of</span> <span m="39774">cache</span>
  <span m="40083">have</span> <span m="40392">slower</span> <span m="40701">access</span>
  <span m="41010">times</span> <span m="41955">but</span> <span m="42900">larger</span>
  <span m="43845">capacities.</span></p><p><span m="44790">Caches</span> <span m="45176">give</span>
  <span m="45562">fast</span> <span m="45949">access</span> <span m="46335">to</span>
  <span m="46721">a</span> <span m="47108">small</span> <span m="47494">number</span>
  <span m="47880">of</span> <span m="48267">memory</span> <span m="48653">locations,</span>
  <span m="49039">using</span> <span m="49426">associative</span> <span m="49812">addressing</span>
  <span m="50199">so</span> <span m="50500">that</span> <span m="50801">the</span>
  <span m="51102">cache</span> <span m="51403">has</span> <span m="51705">the</span>
  <span m="52006">ability</span> <span m="52307">to</span> <span m="52608">hold</span>
  <span m="52910">the</span> <span m="53211">contents</span> <span m="53512">of</span>
  <span m="53813">the</span> <span m="54115">memory</span> <span m="54416">locations</span>
  <span m="54717">the</span> <span m="55018">CPU</span> <span m="55320">is</span>
  <span m="55980">accessing</span> <span m="56640">most</span> <span m="57300">frequently.</span></p><p><span
  m="57960">The</span> <span m="58360">current</span> <span m="58761">contents</span>
  <span m="59162">of</span> <span m="59563">the</span> <span m="59964">cache</span>
  <span m="60365">are</span> <span m="60765">managed</span> <span m="61166">automatically</span>
  <span m="61567">by</span> <span m="61968">the</span> <span m="62369">hardware.</span></p><p><span
  m="62770">Caches</span> <span m="63140">work</span> <span m="63511">well</span>
  <span m="63882">because</span> <span m="64252">of</span> <span m="64623">the</span>
  <span m="64994">principle</span> <span m="65365">of</span> <span m="65735">locality:</span>
  <span m="66106">if</span> <span m="66477">the</span> <span m="66847">CPU</span>
  <span m="67218">accesses</span> <span m="67589">location</span> <span m="67960">X</span>
  <span m="68452">at</span> <span m="68944">time</span> <span m="69436">T,</span>
  <span m="69928">it's</span> <span m="70420">likely</span> <span m="70912">to</span>
  <span m="71405">access</span> <span m="71897">nearby</span> <span m="72389">locations</span>
  <span m="72881">in</span> <span m="73373">the</span> <span m="73865">not-too-distant</span>
  <span m="74357">future.</span></p><p><span m="74850">The</span> <span m="75230">cache</span>
  <span m="75611">is</span> <span m="75992">organized</span> <span m="76372">so</span>
  <span m="76753">that</span> <span m="77134">nearby</span> <span m="77514">locations</span>
  <span m="77895">can</span> <span m="78276">all</span> <span m="78656">reside</span>
  <span m="79037">in</span> <span m="79418">the</span> <span m="79798">cache</span>
  <span m="80179">simultaneously,</span> <span m="80560">using</span> <span m="80890">a</span>
  <span m="81221">simple</span> <span m="81551">indexing</span> <span m="81882">scheme</span>
  <span m="82213">to</span> <span m="82543">choose</span> <span m="82874">which</span>
  <span m="83205">cache</span> <span m="83535">location</span> <span m="83866">should</span>
  <span m="84196">be</span> <span m="84527">checked</span> <span m="84858">for</span>
  <span m="85188">a</span> <span m="85519">matching</span> <span m="85850">address.</span></p><p><span
  m="87380">If</span> <span m="87795">the</span> <span m="88210">address</span> <span
  m="88625">requested</span> <span m="89040">by</span> <span m="89455">the</span>
  <span m="89870">CPU</span> <span m="90285">resides</span> <span m="90700">in</span>
  <span m="91115">the</span> <span m="91530">cache,</span> <span m="91945">access</span>
  <span m="92360">time</span> <span m="92775">is</span> <span m="93190">quite</span>
  <span m="93605">fast.</span></p><p><span m="94020">In</span> <span m="94381">order</span>
  <span m="94742">to</span> <span m="95104">increase</span> <span m="95465">the</span>
  <span m="95827">probability</span> <span m="96188">that</span> <span m="96550">requested</span>
  <span m="96911">addresses</span> <span m="97272">reside</span> <span m="97634">in</span>
  <span m="97995">the</span> <span m="98357">cache,</span> <span m="98718">we</span>
  <span m="99080">introduced</span> <span m="99487">the</span> <span m="99894">notion</span>
  <span m="100302">of</span> <span m="100709">&quot;associativity&quot;,</span> <span
  m="101117">which</span> <span m="101524">increased</span> <span m="101931">the</span>
  <span m="102339">number</span> <span m="102746">of</span> <span m="103154">cache</span>
  <span m="103561">locations</span> <span m="103969">checked</span> <span m="104359">on</span>
  <span m="104750">each</span> <span m="105141">access</span> <span m="105532">and</span>
  <span m="105922">solved</span> <span m="106313">the</span> <span m="106704">problem</span>
  <span m="107095">of</span> <span m="107485">having,</span> <span m="107876">say,</span>
  <span m="108267">instructions</span> <span m="108658">and</span> <span m="109128">data</span>
  <span m="109598">compete</span> <span m="110068">for</span> <span m="110539">the</span>
  <span m="111009">same</span> <span m="111479">cache</span> <span m="111949">locations..</span></p><p><span
  m="112420">We</span> <span m="112826">also</span> <span m="113233">discussed</span>
  <span m="113640">appropriate</span> <span m="114046">choices</span> <span m="114453">for</span>
  <span m="114860">block</span> <span m="115266">size</span> <span m="115673">(the</span>
  <span m="116080">number</span> <span m="116486">of</span> <span m="116893">words</span>
  <span m="117300">in</span> <span m="117706">a</span> <span m="118113">cache</span>
  <span m="118520">line),</span> <span m="119001">replacement</span> <span m="119482">policy</span>
  <span m="119963">(how</span> <span m="120444">to</span> <span m="120925">choose</span>
  <span m="121406">which</span> <span m="121887">cache</span> <span m="122369">line</span>
  <span m="122748">to</span> <span m="123127">reuse</span> <span m="123507">on</span>
  <span m="123886">a</span> <span m="124266">cache</span> <span m="124645">miss),</span>
  <span m="125024">and</span> <span m="125404">write</span> <span m="125783">policy</span>
  <span m="126163">(deciding</span> <span m="126542">when</span> <span m="126921">to</span>
  <span m="127301">write</span> <span m="127680">changed</span> <span m="128060">data</span>
  <span m="128418">back</span> <span m="128776">to</span> <span m="129134">main</span>
  <span m="129492">memory).</span></p><p><span m="129850">We'll</span> <span m="130212">see</span>
  <span m="130574">these</span> <span m="130937">same</span> <span m="131299">choices</span>
  <span m="131661">again</span> <span m="132024">in</span> <span m="132386">this</span>
  <span m="132748">lecture</span> <span m="133111">as</span> <span m="133473">we</span>
  <span m="133835">work</span> <span m="134198">to</span> <span m="134560">expand</span>
  <span m="134922">the</span> <span m="135285">memory</span> <span m="135647">hierarchy</span>
  <span m="136010">beyond</span> <span m="136896">main</span> <span m="137783">memory.</span></p><p><span
  m="138670">We</span> <span m="138978">never</span> <span m="139286">discussed</span>
  <span m="139594">where</span> <span m="139902">the</span> <span m="140211">data</span>
  <span m="140519">in</span> <span m="140827">main</span> <span m="141135">memory</span>
  <span m="141444">comes</span> <span m="141752">from</span> <span m="142060">and</span>
  <span m="142368">how</span> <span m="142677">the</span> <span m="142985">process</span>
  <span m="143293">of</span> <span m="143601">filling</span> <span m="143910">main</span>
  <span m="144425">memory</span> <span m="144940">is</span> <span m="145455">managed.</span></p><p><span
  m="145970">That's</span> <span m="146456">the</span> <span m="146943">topic</span>
  <span m="147430">of</span> <span m="147916">today's</span> <span m="148403">lecture..</span></p><p><span
  m="148890">Flash</span> <span m="149251">drives</span> <span m="149612">and</span>
  <span m="149974">hard</span> <span m="150335">disks</span> <span m="150697">provide</span>
  <span m="151058">storage</span> <span m="151420">options</span> <span m="151781">that</span>
  <span m="152142">have</span> <span m="152504">more</span> <span m="152865">capacity</span>
  <span m="153227">than</span> <span m="153588">main</span> <span m="153950">memory,</span>
  <span m="154364">with</span> <span m="154778">the</span> <span m="155192">added</span>
  <span m="155607">benefit</span> <span m="156021">of</span> <span m="156435">being</span>
  <span m="156850">non-volatile,</span> <span m="157264">i.e.,</span> <span m="157678">they</span>
  <span m="158093">continue</span> <span m="158507">to</span> <span m="158921">store</span>
  <span m="159336">data</span> <span m="159750">even</span> <span m="160164">when</span>
  <span m="160579">turned</span> <span m="161469">off.</span></p><p><span m="162360">The</span>
  <span m="162715">generic</span> <span m="163071">name</span> <span m="163427">for</span>
  <span m="163782">these</span> <span m="164138">new</span> <span m="164494">devices</span>
  <span m="164850">is</span> <span m="165205">&quot;secondary</span> <span m="165561">storage&quot;,</span>
  <span m="165917">where</span> <span m="166272">data</span> <span m="166628">will</span>
  <span m="166984">reside</span> <span m="167340">until</span> <span m="167882">it's</span>
  <span m="168425">moved</span> <span m="168968">to</span> <span m="169510">&quot;primary</span>
  <span m="170053">storage&quot;,</span> <span m="170596">i.e.,</span> <span m="171139">main</span>
  <span m="171681">memory,</span> <span m="172224">for</span> <span m="172767">use.</span></p><p><span
  m="173310">So</span> <span m="173568">when</span> <span m="173827">we</span> <span
  m="174086">first</span> <span m="174345">turn</span> <span m="174604">on</span>
  <span m="174863">a</span> <span m="175122">computer</span> <span m="175381">system,</span>
  <span m="175640">all</span> <span m="175898">of</span> <span m="176157">its</span>
  <span m="176416">data</span> <span m="176675">will</span> <span m="176934">be</span>
  <span m="177193">found</span> <span m="177452">in</span> <span m="177711">secondary</span>
  <span m="177970">storage,</span> <span m="178383">which</span> <span m="178796">we'll</span>
  <span m="179209">think</span> <span m="179622">of</span> <span m="180035">as</span>
  <span m="180448">the</span> <span m="180861">final</span> <span m="181274">level</span>
  <span m="181687">of</span> <span m="182100">our</span> <span m="182513">memory</span>
  <span m="182926">hierarchy.</span></p><p><span m="183340">As</span> <span m="183619">we</span>
  <span m="183898">think</span> <span m="184178">about</span> <span m="184457">the</span>
  <span m="184736">right</span> <span m="185016">memory</span> <span m="185295">architecture,</span>
  <span m="185575">we'll</span> <span m="185854">build</span> <span m="186133">on</span>
  <span m="186413">the</span> <span m="186692">ideas</span> <span m="186971">from</span>
  <span m="187251">our</span> <span m="187530">previous</span> <span m="187810">discussion</span>
  <span m="188208">of</span> <span m="188607">caches,</span> <span m="189006">and,</span>
  <span m="189404">indeed,</span> <span m="189803">think</span> <span m="190202">of</span>
  <span m="190600">main</span> <span m="190999">memory</span> <span m="191398">as</span>
  <span m="191796">another</span> <span m="192195">level</span> <span m="192594">of</span>
  <span m="192992">cache</span> <span m="193391">for</span> <span m="193790">the</span>
  <span m="194362">permanent,</span> <span m="194934">high-capacity</span> <span m="195506">secondary</span>
  <span m="196078">storage.</span></p><p><span m="196650">We'll</span> <span m="197062">be</span>
  <span m="197475">building</span> <span m="197888">what</span> <span m="198300">we</span>
  <span m="198713">call</span> <span m="199126">a</span> <span m="199538">virtual</span>
  <span m="199951">memory</span> <span m="200364">system,</span> <span m="200776">which,</span>
  <span m="201189">like</span> <span m="201602">caches,</span> <span m="202014">will</span>
  <span m="202427">automatically</span> <span m="202840">move</span> <span m="203321">data</span>
  <span m="203802">from</span> <span m="204283">secondary</span> <span m="204764">storage</span>
  <span m="205245">into</span> <span m="205726">main</span> <span m="206207">memory</span>
  <span m="206688">as</span> <span m="207169">needed.</span></p><p><span m="207650">The</span>
  <span m="207962">virtual</span> <span m="208275">memory</span> <span m="208588">system</span>
  <span m="208901">will</span> <span m="209214">also</span> <span m="209527">let</span>
  <span m="209840">us</span> <span m="210153">control</span> <span m="210466">what</span>
  <span m="210779">data</span> <span m="211092">can</span> <span m="211405">be</span>
  <span m="211718">accessed</span> <span m="212031">by</span> <span m="212344">the</span>
  <span m="212657">program,</span> <span m="212970">serving</span> <span m="213314">as</span>
  <span m="213658">a</span> <span m="214002">stepping</span> <span m="214346">stone</span>
  <span m="214690">to</span> <span m="215034">building</span> <span m="215378">a</span>
  <span m="215722">system</span> <span m="216066">that</span> <span m="216410">can</span>
  <span m="216754">securely</span> <span m="217098">run</span> <span m="217442">many</span>
  <span m="217786">programs</span> <span m="218130">on</span> <span m="218550">a</span>
  <span m="218970">single</span> <span m="219390">CPU.</span></p><p><span m="219810">Let's</span>
  <span m="220856">get</span> <span m="221903">started!</span></p><p><span m="222950">Here</span>
  <span m="223224">we</span> <span m="223499">see</span> <span m="223774">the</span>
  <span m="224048">cache</span> <span m="224323">and</span> <span m="224598">main</span>
  <span m="224872">memory,</span> <span m="225147">the</span> <span m="225422">two</span>
  <span m="225697">components</span> <span m="225971">of</span> <span m="226246">our</span>
  <span m="226521">memory</span> <span m="226795">system</span> <span m="227070">as</span>
  <span m="227345">developed</span> <span m="227620">in</span> <span m="228296">Lecture</span>
  <span m="228973">14.</span></p><p><span m="229650">And</span> <span m="230057">here's</span>
  <span m="230464">our</span> <span m="230871">new</span> <span m="231278">secondary</span>
  <span m="231685">storage</span> <span m="232092">layer.</span></p><p><span m="232500">The</span>
  <span m="232962">good</span> <span m="233424">news:</span> <span m="233886">the</span>
  <span m="234348">capacity</span> <span m="234810">of</span> <span m="235272">secondary</span>
  <span m="235734">storage</span> <span m="236196">is</span> <span m="236658">huge!</span></p><p><span
  m="237120">Even</span> <span m="237417">the</span> <span m="237714">most</span>
  <span m="238011">modest</span> <span m="238308">modern</span> <span m="238605">computer</span>
  <span m="238902">system</span> <span m="239200">will</span> <span m="239497">have</span>
  <span m="239794">100's</span> <span m="240091">of</span> <span m="240388">gigabytes</span>
  <span m="240685">of</span> <span m="240982">secondary</span> <span m="241280">storage</span>
  <span m="241769">and</span> <span m="242258">having</span> <span m="242747">a</span>
  <span m="243237">terabyte</span> <span m="243726">or</span> <span m="244215">two</span>
  <span m="244705">is</span> <span m="245194">not</span> <span m="245683">uncommon</span>
  <span m="246172">on</span> <span m="246662">medium-size</span> <span m="247151">desktop</span>
  <span m="247640">computers.</span></p><p><span m="248130">Secondary</span> <span
  m="248510">storage</span> <span m="248890">for</span> <span m="249270">the</span>
  <span m="249650">cloud</span> <span m="250030">can</span> <span m="250410">grow</span>
  <span m="250790">to</span> <span m="251170">many</span> <span m="251550">petabytes</span>
  <span m="251930">(a</span> <span m="252310">petabyte</span> <span m="252690">is</span>
  <span m="253070">10^15</span> <span m="253450">bytes</span> <span m="253830">or</span>
  <span m="254509">a</span> <span m="255189">million</span> <span m="255868">gigabytes).</span></p><p><span
  m="256548">The</span> <span m="257027">bad</span> <span m="257506">news:</span>
  <span m="257986">disk</span> <span m="258465">access</span> <span m="258945">times</span>
  <span m="259424">are</span> <span m="259904">100,000</span> <span m="260383">times</span>
  <span m="260862">longer</span> <span m="261342">that</span> <span m="261821">those</span>
  <span m="262301">of</span> <span m="262780">DRAM.</span></p><p><span m="263260">So</span>
  <span m="263564">the</span> <span m="263868">change</span> <span m="264172">in</span>
  <span m="264476">access</span> <span m="264780">time</span> <span m="265084">from</span>
  <span m="265388">DRAM</span> <span m="265692">to</span> <span m="265997">disk</span>
  <span m="266301">is</span> <span m="266605">much,</span> <span m="266909">much</span>
  <span m="267213">larger</span> <span m="267517">than</span> <span m="267821">the</span>
  <span m="268125">change</span> <span m="268430">from</span> <span m="269267">caches</span>
  <span m="270105">to</span> <span m="270942">DRAM.</span></p><p><span m="271780">When</span>
  <span m="272086">looking</span> <span m="272392">at</span> <span m="272699">DRAM</span>
  <span m="273005">timing,</span> <span m="273312">we</span> <span m="273618">discovered</span>
  <span m="273925">that</span> <span m="274231">the</span> <span m="274537">additional</span>
  <span m="274844">access</span> <span m="275150">time</span> <span m="275457">for</span>
  <span m="275763">retrieving</span> <span m="276070">a</span> <span m="276413">contiguous</span>
  <span m="276756">block</span> <span m="277099">of</span> <span m="277442">words</span>
  <span m="277785">was</span> <span m="278128">small</span> <span m="278471">compared</span>
  <span m="278815">to</span> <span m="279158">the</span> <span m="279501">access</span>
  <span m="279844">time</span> <span m="280187">for</span> <span m="280530">the</span>
  <span m="280873">first</span> <span m="281216">word,</span> <span m="281560">so</span>
  <span m="281943">fetching</span> <span m="282326">a</span> <span m="282710">block</span>
  <span m="283093">was</span> <span m="283476">the</span> <span m="283860">right</span>
  <span m="284243">plan</span> <span m="284626">assuming</span> <span m="285010">we'd</span>
  <span m="285393">eventually</span> <span m="285776">access</span> <span m="286160">the</span>
  <span m="286543">additional</span> <span m="286926">words.</span></p><p><span m="287310">For</span>
  <span m="287645">disks,</span> <span m="287980">the</span> <span m="288316">access</span>
  <span m="288651">time</span> <span m="288986">difference</span> <span m="289322">between</span>
  <span m="289657">the</span> <span m="289992">first</span> <span m="290328">word</span>
  <span m="290663">and</span> <span m="290998">successive</span> <span m="291334">words</span>
  <span m="291669">is</span> <span m="292004">even</span> <span m="292340">more</span>
  <span m="293005">dramatic.</span></p><p><span m="293670">So,</span> <span m="294138">not</span>
  <span m="294606">surprisingly,</span> <span m="295075">we'll</span> <span m="295543">be</span>
  <span m="296012">reading</span> <span m="296480">fairly</span> <span m="296949">large</span>
  <span m="297417">blocks</span> <span m="297886">of</span> <span m="298354">data</span>
  <span m="298823">from</span> <span m="299291">disk.</span></p><p><span m="299760">The</span>
  <span m="300128">consequence</span> <span m="300497">of</span> <span m="300866">the</span>
  <span m="301235">much,</span> <span m="301604">much</span> <span m="301973">larger</span>
  <span m="302342">secondary-storage</span> <span m="302711">access</span> <span m="303080">time</span>
  <span m="303448">is</span> <span m="303817">that</span> <span m="304186">it</span>
  <span m="304555">will</span> <span m="304924">be</span> <span m="305293">very</span>
  <span m="305662">time</span> <span m="306031">consuming</span> <span m="306400">to</span>
  <span m="306737">access</span> <span m="307075">disk</span> <span m="307413">if</span>
  <span m="307750">the</span> <span m="308088">data</span> <span m="308426">we</span>
  <span m="308763">need</span> <span m="309101">is</span> <span m="309439">not</span>
  <span m="309776">in</span> <span m="310114">main</span> <span m="310452">memory.</span></p><p><span
  m="310790">So</span> <span m="311175">we</span> <span m="311561">need</span> <span
  m="311946">to</span> <span m="312332">design</span> <span m="312718">our</span>
  <span m="313103">virtual</span> <span m="313489">memory</span> <span m="313875">system</span>
  <span m="314260">to</span> <span m="314646">minimize</span> <span m="315031">misses</span>
  <span m="315417">when</span> <span m="315803">accessing</span> <span m="316188">main</span>
  <span m="316574">memory.</span></p><p><span m="316960">A</span> <span m="317357">miss,</span>
  <span m="317754">and</span> <span m="318151">the</span> <span m="318548">subsequent</span>
  <span m="318945">disk</span> <span m="319342">access,</span> <span m="319739">will</span>
  <span m="320136">have</span> <span m="320533">a</span> <span m="320930">huge</span>
  <span m="321327">impact</span> <span m="321724">on</span> <span m="322121">the</span>
  <span m="322518">average</span> <span m="322915">memory</span> <span m="323312">access</span>
  <span m="323710">time,</span> <span m="324016">so</span> <span m="324322">the</span>
  <span m="324628">miss</span> <span m="324935">rate</span> <span m="325241">will</span>
  <span m="325547">need</span> <span m="325854">to</span> <span m="326160">be</span>
  <span m="326466">very,</span> <span m="326773">very</span> <span m="327079">small</span>
  <span m="327385">compared</span> <span m="327692">to,</span> <span m="327998">say,</span>
  <span m="328304">the</span> <span m="328611">rate</span> <span m="328917">of</span>
  <span m="329223">executing</span> <span m="329530">instructions.</span></p><p><span
  m="331620">Given</span> <span m="331950">the</span> <span m="332281">enormous</span>
  <span m="332612">miss</span> <span m="332942">penalties</span> <span m="333273">of</span>
  <span m="333604">secondary</span> <span m="333934">storage,</span> <span m="334265">what</span>
  <span m="334596">does</span> <span m="334926">that</span> <span m="335257">tell</span>
  <span m="335588">us</span> <span m="335918">about</span> <span m="336249">how</span>
  <span m="336580">it</span> <span m="336886">should</span> <span m="337192">be</span>
  <span m="337498">used</span> <span m="337804">as</span> <span m="338110">part</span>
  <span m="338416">of</span> <span m="338722">our</span> <span m="339028">memory</span>
  <span m="339334">hierarchy?</span></p><p><span m="339640">We</span> <span m="339940">will</span>
  <span m="340241">need</span> <span m="340541">high</span> <span m="340842">associativity,</span>
  <span m="341143">i.e.,</span> <span m="341443">we</span> <span m="341744">need</span>
  <span m="342045">a</span> <span m="342345">great</span> <span m="342646">deal</span>
  <span m="342946">of</span> <span m="343247">flexibility</span> <span m="343548">on</span>
  <span m="343848">how</span> <span m="344149">data</span> <span m="344450">from</span>
  <span m="344865">disk</span> <span m="345280">can</span> <span m="345695">be</span>
  <span m="346110">located</span> <span m="346525">in</span> <span m="346940">main</span>
  <span m="347355">memory.</span></p><p><span m="347770">In</span> <span m="348077">other</span>
  <span m="348384">words,</span> <span m="348691">if</span> <span m="348998">our</span>
  <span m="349305">working</span> <span m="349612">set</span> <span m="349919">of</span>
  <span m="350226">memory</span> <span m="350533">accesses</span> <span m="350840">fit</span>
  <span m="351147">in</span> <span m="351454">main</span> <span m="351761">memory,</span>
  <span m="352068">our</span> <span m="352375">virtual</span> <span m="352682">memory</span>
  <span m="352990">system</span> <span m="353539">should</span> <span m="354088">make</span>
  <span m="354637">that</span> <span m="355186">possible,</span> <span m="355735">avoiding</span>
  <span m="356284">unnecessary</span> <span m="356833">collisions</span> <span m="357382">between</span>
  <span m="357931">accesses</span> <span m="358480">to</span> <span m="359030">one</span>
  <span m="359551">block</span> <span m="360073">of</span> <span m="360595">data</span>
  <span m="361116">and</span> <span m="361638">another.</span></p><p><span m="362160">We'll</span>
  <span m="362400">want</span> <span m="362641">to</span> <span m="362881">use</span>
  <span m="363122">a</span> <span m="363362">large</span> <span m="363603">block</span>
  <span m="363843">size</span> <span m="364084">to</span> <span m="364325">take</span>
  <span m="364565">advantage</span> <span m="364806">of</span> <span m="365046">the</span>
  <span m="365287">low</span> <span m="365527">incremental</span> <span m="365768">cost</span>
  <span m="366008">of</span> <span m="366249">reading</span> <span m="366490">successive</span>
  <span m="367020">words</span> <span m="367550">from</span> <span m="368080">disk.</span></p><p><span
  m="368610">And,</span> <span m="368925">given</span> <span m="369240">the</span>
  <span m="369556">principle</span> <span m="369871">of</span> <span m="370186">locality,</span>
  <span m="370502">we'd</span> <span m="370817">expect</span> <span m="371132">to</span>
  <span m="371448">be</span> <span m="371763">accessing</span> <span m="372078">other</span>
  <span m="372394">words</span> <span m="372709">of</span> <span m="373024">the</span>
  <span m="373340">block,</span> <span m="373793">thus</span> <span m="374246">amortizing</span>
  <span m="374700">the</span> <span m="375153">cost</span> <span m="375606">of</span>
  <span m="376060">the</span> <span m="376513">miss</span> <span m="376966">over</span>
  <span m="377420">many</span> <span m="377873">future</span> <span m="378326">hits.</span></p><p><span
  m="378780">Finally,</span> <span m="379180">we'll</span> <span m="379581">want</span>
  <span m="379981">to</span> <span m="380382">use</span> <span m="380783">a</span>
  <span m="381183">write-back</span> <span m="381584">strategy</span> <span m="381985">where</span>
  <span m="382385">we'll</span> <span m="382786">only</span> <span m="383186">update</span>
  <span m="383587">the</span> <span m="383988">contents</span> <span m="384388">of</span>
  <span m="384789">disk</span> <span m="385190">when</span> <span m="385524">data</span>
  <span m="385859">that's</span> <span m="386194">changed</span> <span m="386528">in</span>
  <span m="386863">main</span> <span m="387198">memory</span> <span m="387532">needs</span>
  <span m="387867">to</span> <span m="388202">be</span> <span m="388537">replaced</span>
  <span m="388871">by</span> <span m="389206">data</span> <span m="389541">from</span>
  <span m="389875">other</span> <span m="390210">blocks</span> <span m="390545">of</span>
  <span m="390880">secondary</span> <span m="391515">storage.</span></p><p><span m="392150">There</span>
  <span m="392580">is</span> <span m="393010">upside</span> <span m="393440">to</span>
  <span m="393870">misses</span> <span m="394300">having</span> <span m="394730">such</span>
  <span m="395160">long</span> <span m="395590">latencies.</span></p><p><span m="396020">We</span>
  <span m="396523">can</span> <span m="397026">manage</span> <span m="397529">the</span>
  <span m="398032">organization</span> <span m="398535">of</span> <span m="399038">main</span>
  <span m="399541">memory</span> <span m="400045">and</span> <span m="400548">the</span>
  <span m="401051">accesses</span> <span m="401554">to</span> <span m="402057">secondary</span>
  <span m="402560">storage</span> <span m="403063">in</span> <span m="403566">software.</span></p><p><span
  m="404070">Even</span> <span m="404386">it</span> <span m="404703">takes</span>
  <span m="405020">1000's</span> <span m="405336">of</span> <span m="405653">instructions</span>
  <span m="405970">to</span> <span m="406286">deal</span> <span m="406603">with</span>
  <span m="406920">the</span> <span m="407236">consequences</span> <span m="407553">of</span>
  <span m="407870">a</span> <span m="408186">miss,</span> <span m="408503">executing</span>
  <span m="408820">those</span> <span m="409165">instructions</span> <span m="409511">is</span>
  <span m="409857">quick</span> <span m="410203">compared</span> <span m="410549">to</span>
  <span m="410895">the</span> <span m="411240">access</span> <span m="411586">time</span>
  <span m="411932">of</span> <span m="412278">a</span> <span m="412624">disk.</span></p><p><span
  m="412970">So</span> <span m="413374">our</span> <span m="413779">strategy</span>
  <span m="414184">will</span> <span m="414589">be</span> <span m="414994">to</span>
  <span m="415399">handle</span> <span m="415804">hits</span> <span m="416209">in</span>
  <span m="416614">hardware</span> <span m="417019">and</span> <span m="417424">misses</span>
  <span m="417829">in</span> <span m="418234">software.</span></p><p><span m="418639">This</span>
  <span m="418965">will</span> <span m="419292">lead</span> <span m="419618">to</span>
  <span m="419945">simple</span> <span m="420271">memory</span> <span m="420598">management</span>
  <span m="420924">hardware</span> <span m="421251">and</span> <span m="421577">the</span>
  <span m="421904">possibility</span> <span m="422230">of</span> <span m="422557">using</span>
  <span m="422883">very</span> <span m="423210">clever</span> <span m="423567">strategies</span>
  <span m="423925">implemented</span> <span m="424283">in</span> <span m="424640">software</span>
  <span m="424998">to</span> <span m="425356">figure</span> <span m="425713">out</span>
  <span m="426071">what</span> <span m="426429">to</span> <span m="426786">do</span>
  <span m="427144">on</span> <span m="427502">misses.</span></p>
type: course
uid: b4e8eac3c3fd0494925cbce70ad51eed

---
None