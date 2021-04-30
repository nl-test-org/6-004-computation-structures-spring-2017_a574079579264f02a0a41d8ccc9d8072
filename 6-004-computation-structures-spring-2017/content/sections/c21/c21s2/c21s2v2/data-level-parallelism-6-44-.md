---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: QCo-RtfLzyc
  parent_uid: 1bbb5576cd5b73a77b891ecd42b3f5f8
  title: Video-YouTube-Stream
  type: Video
  uid: f0c763834334dfc4be063073dab70b56
- id: 3Play-3Play YouTube id-Stream
  media_location: QCo-RtfLzyc
  parent_uid: 1bbb5576cd5b73a77b891ecd42b3f5f8
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: bd7a779f2bebdaae01432b98059cf4a2
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/QCo-RtfLzyc/default.jpg
  parent_uid: 1bbb5576cd5b73a77b891ecd42b3f5f8
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: f34d020c946ded10a743fa7a7f442b73
- id: QCo-RtfLzyc.srt
  parent_uid: 1bbb5576cd5b73a77b891ecd42b3f5f8
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/c21s2v2/data-level-parallelism-6-44-/QCo-RtfLzyc.srt
  title: 3play caption file
  type: null
  uid: f5140dd87754f2c03b434ca9bf8a82e0
- id: QCo-RtfLzyc.pdf
  parent_uid: 1bbb5576cd5b73a77b891ecd42b3f5f8
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/c21s2v2/data-level-parallelism-6-44-/QCo-RtfLzyc.pdf
  title: 3play pdf file
  type: null
  uid: ff77908b50f36369a87c58113d73974c
- id: Caption-3Play YouTube id-SRT
  parent_uid: 1bbb5576cd5b73a77b891ecd42b3f5f8
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 7f1784c0f9e9d3a60f148eb3e6fdcfd9
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 1bbb5576cd5b73a77b891ecd42b3f5f8
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 914bd1f41841bafcb5d83cba4693a33e
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_21-02-02_300k.mp4
  parent_uid: 1bbb5576cd5b73a77b891ecd42b3f5f8
  title: Video-Internet Archive-MP4
  type: Video
  uid: a0fb9de7815330f78f94d9fc043af1c8
inline_embed_id: 43221107datalevelparallelism64465306719
layout: video
order_index: null
parent_uid: 6b8e60cd8ae9825bf796f7971d32ae04
related_resources_text: ''
short_url: data-level-parallelism-6-44-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/c21s2v2/data-level-parallelism-6-44-
template_type: Embed
title: Data-level Parallelism
transcript: <p><span m="599">For</span> <span m="1024">some</span> <span m="1449">applications,</span>
  <span m="1875">data</span> <span m="2300">naturally</span> <span m="2726">comes</span>
  <span m="3151">in</span> <span m="3577">vector</span> <span m="4002">or</span> <span
  m="4428">matrix</span> <span m="4853">form.</span></p><p><span m="5279">For</span>
  <span m="5717">example,</span> <span m="6156">a</span> <span m="6594">vector</span>
  <span m="7033">of</span> <span m="7471">digitized</span> <span m="7910">samples</span>
  <span m="8348">representing</span> <span m="8787">an</span> <span m="9225">audio</span>
  <span m="9664">waveform</span> <span m="10102">over</span> <span m="10541">time,</span>
  <span m="10980">or</span> <span m="11361">a</span> <span m="11743">matrix</span>
  <span m="12124">of</span> <span m="12506">pixel</span> <span m="12887">colors</span>
  <span m="13269">in</span> <span m="13650">a</span> <span m="14032">2D</span> <span
  m="14413">image</span> <span m="14795">from</span> <span m="15176">a</span> <span
  m="15558">camera.</span></p><p><span m="15940">When</span> <span m="16220">processing</span>
  <span m="16500">that</span> <span m="16780">data,</span> <span m="17060">it's</span>
  <span m="17340">common</span> <span m="17620">to</span> <span m="17900">perform</span>
  <span m="18180">the</span> <span m="18460">same</span> <span m="18740">sequence</span>
  <span m="19020">of</span> <span m="19300">operations</span> <span m="19580">on</span>
  <span m="19860">each</span> <span m="20460">data</span> <span m="21060">element.</span></p><p><span
  m="21660">The</span> <span m="21978">example</span> <span m="22296">code</span>
  <span m="22614">shown</span> <span m="22932">here</span> <span m="23250">is</span>
  <span m="23568">computing</span> <span m="23886">a</span> <span m="24205">vector</span>
  <span m="24523">sum,</span> <span m="24841">where</span> <span m="25159">each</span>
  <span m="25477">component</span> <span m="25795">of</span> <span m="26113">one</span>
  <span m="26431">vector</span> <span m="26750">is</span> <span m="27231">added</span>
  <span m="27712">to</span> <span m="28193">the</span> <span m="28674">corresponding</span>
  <span m="29155">component</span> <span m="29636">of</span> <span m="30117">another</span>
  <span m="30598">vector.</span></p><p><span m="31080">By</span> <span m="31488">replicating</span>
  <span m="31896">the</span> <span m="32305">datapath</span> <span m="32713">portion</span>
  <span m="33122">of</span> <span m="33530">our</span> <span m="33939">CPU,</span>
  <span m="34347">we</span> <span m="34756">can</span> <span m="35164">design</span>
  <span m="35573">special-purpose</span> <span m="35981">vector</span> <span m="36390">processors</span>
  <span m="36793">capable</span> <span m="37197">of</span> <span m="37601">performing</span>
  <span m="38005">the</span> <span m="38409">same</span> <span m="38813">operation</span>
  <span m="39216">on</span> <span m="39620">many</span> <span m="40024">data</span>
  <span m="40428">elements</span> <span m="40832">in</span> <span m="41236">parallel.</span></p><p><span
  m="41640">Here</span> <span m="41940">we</span> <span m="42241">see</span> <span
  m="42541">that</span> <span m="42842">the</span> <span m="43142">register</span>
  <span m="43443">file</span> <span m="43743">and</span> <span m="44044">ALU</span>
  <span m="44345">have</span> <span m="44645">been</span> <span m="44946">replicated</span>
  <span m="45246">and</span> <span m="45547">the</span> <span m="45847">control</span>
  <span m="46148">signals</span> <span m="46449">from</span> <span m="46937">decoding</span>
  <span m="47425">the</span> <span m="47913">current</span> <span m="48401">instruction</span>
  <span m="48889">are</span> <span m="49378">shared</span> <span m="49866">by</span>
  <span m="50354">all</span> <span m="50842">the</span> <span m="51330">datapaths.</span></p><p><span
  m="51819">Data</span> <span m="52098">is</span> <span m="52377">fetched</span> <span
  m="52657">from</span> <span m="52936">memory</span> <span m="53216">in</span> <span
  m="53495">big</span> <span m="53775">blocks</span> <span m="54054">(very</span>
  <span m="54333">much</span> <span m="54613">like</span> <span m="54892">fetching</span>
  <span m="55172">a</span> <span m="55451">cache</span> <span m="55731">line)</span>
  <span m="56010">and</span> <span m="56290">the</span> <span m="56667">specified</span>
  <span m="57044">register</span> <span m="57422">in</span> <span m="57799">each</span>
  <span m="58177">datapath</span> <span m="58554">is</span> <span m="58932">loaded</span>
  <span m="59309">with</span> <span m="59686">one</span> <span m="60064">of</span>
  <span m="60441">the</span> <span m="60819">words</span> <span m="61196">from</span>
  <span m="61574">the</span> <span m="61951">block.</span></p><p><span m="62329">Similarly</span>
  <span m="62595">each</span> <span m="62862">datapath</span> <span m="63129">can</span>
  <span m="63396">contribute</span> <span m="63663">a</span> <span m="63930">word</span>
  <span m="64197">to</span> <span m="64464">be</span> <span m="64731">stored</span>
  <span m="64998">as</span> <span m="65265">a</span> <span m="65532">contiguous</span>
  <span m="65799">block</span> <span m="66066">in</span> <span m="66333">main</span>
  <span m="66600">memory.</span></p><p><span m="68369">In</span> <span m="68669">such</span>
  <span m="68969">machines,</span> <span m="69269">the</span> <span m="69569">width</span>
  <span m="69869">of</span> <span m="70169">the</span> <span m="70469">data</span>
  <span m="70769">buses</span> <span m="71069">to</span> <span m="71369">and</span>
  <span m="71669">from</span> <span m="71969">main</span> <span m="72269">memory</span>
  <span m="72569">is</span> <span m="72869">many</span> <span m="73169">words</span>
  <span m="73469">wide,</span> <span m="73770">so</span> <span m="74279">a</span>
  <span m="74788">single</span> <span m="75297">memory</span> <span m="75806">access</span>
  <span m="76316">provides</span> <span m="76825">data</span> <span m="77334">for</span>
  <span m="77843">all</span> <span m="78353">the</span> <span m="78862">datapaths</span>
  <span m="79371">in</span> <span m="79880">parallel.</span></p><p><span m="80390">Executing</span>
  <span m="80711">a</span> <span m="81032">single</span> <span m="81354">instruction</span>
  <span m="81675">on</span> <span m="81997">a</span> <span m="82318">machine</span>
  <span m="82640">with</span> <span m="82961">N</span> <span m="83282">datapaths</span>
  <span m="83604">is</span> <span m="83925">equivalent</span> <span m="84247">to</span>
  <span m="84568">executing</span> <span m="84890">N</span> <span m="85329">instructions</span>
  <span m="85769">on</span> <span m="86209">a</span> <span m="86649">conventional</span>
  <span m="87089">machine</span> <span m="87529">with</span> <span m="87969">a</span>
  <span m="88409">single</span> <span m="88849">datapath.</span></p><p><span m="89289">The</span>
  <span m="89760">result</span> <span m="90232">achieves</span> <span m="90703">a</span>
  <span m="91175">lot</span> <span m="91647">of</span> <span m="92118">parallelism</span>
  <span m="92590">without</span> <span m="93061">the</span> <span m="93533">complexities</span>
  <span m="94005">of</span> <span m="94476">out-of-order</span> <span m="94948">superscalar</span>
  <span m="95420">execution.</span></p><p><span m="96420">Suppose</span> <span m="96786">we</span>
  <span m="97153">had</span> <span m="97519">a</span> <span m="97886">vector</span>
  <span m="98252">processor</span> <span m="98619">with</span> <span m="98985">16</span>
  <span m="99352">datapaths.</span></p><p><span m="99719">Let's</span> <span m="100069">compare</span>
  <span m="100420">its</span> <span m="100771">performance</span> <span m="101122">on</span>
  <span m="101472">a</span> <span m="101823">vector-sum</span> <span m="102174">operation</span>
  <span m="102525">to</span> <span m="102876">that</span> <span m="103226">of</span>
  <span m="103577">a</span> <span m="103928">conventional</span> <span m="104279">pipelined</span>
  <span m="104630">Beta</span> <span m="105560">processor.</span></p><p><span m="106490">Here's</span>
  <span m="106887">the</span> <span m="107285">Beta</span> <span m="107682">code,</span>
  <span m="108080">carefully</span> <span m="108477">organized</span> <span m="108875">to</span>
  <span m="109272">avoid</span> <span m="109670">any</span> <span m="110067">data</span>
  <span m="110465">hazards</span> <span m="110862">during</span> <span m="111260">execution.</span></p><p><span
  m="111658">There</span> <span m="111936">are</span> <span m="112214">9</span> <span
  m="112493">instructions</span> <span m="112771">in</span> <span m="113050">the</span>
  <span m="113328">loop,</span> <span m="113607">taking</span> <span m="113885">10</span>
  <span m="114164">cycles</span> <span m="114442">to</span> <span m="114720">execute</span>
  <span m="114999">if</span> <span m="115277">we</span> <span m="115556">count</span>
  <span m="115834">the</span> <span m="116113">NOP</span> <span m="116391">introduced</span>
  <span m="116670">into</span> <span m="116978">the</span> <span m="117287">pipeline</span>
  <span m="117595">when</span> <span m="117904">the</span> <span m="118212">BNE</span>
  <span m="118521">at</span> <span m="118830">the</span> <span m="119138">end</span>
  <span m="119447">of</span> <span m="119755">the</span> <span m="120064">loop</span>
  <span m="120372">is</span> <span m="120681">taken.</span></p><p><span m="120990">It</span>
  <span m="121376">takes</span> <span m="121762">160</span> <span m="122148">cycles</span>
  <span m="122534">to</span> <span m="122920">sum</span> <span m="123306">all</span>
  <span m="123692">16</span> <span m="124078">elements</span> <span m="124464">assuming</span>
  <span m="124850">no</span> <span m="125236">additional</span> <span m="125622">cycles</span>
  <span m="126008">are</span> <span m="126394">required</span> <span m="126780">due</span>
  <span m="127362">to</span> <span m="127945">cache</span> <span m="128527">misses.</span></p><p><span
  m="129110">And</span> <span m="129486">here's</span> <span m="129863">the</span>
  <span m="130240">corresponding</span> <span m="130617">code</span> <span m="130994">for</span>
  <span m="131371">a</span> <span m="131748">vector</span> <span m="132125">processor</span>
  <span m="132502">where</span> <span m="132879">we've</span> <span m="133256">assumed</span>
  <span m="133633">constant-sized</span> <span m="134010">16-element</span> <span
  m="135110">vectors.</span></p><p><span m="136210">Note</span> <span m="136501">that</span>
  <span m="136792">&quot;V&quot;</span> <span m="137083">registers</span> <span m="137375">refer</span>
  <span m="137666">to</span> <span m="137957">a</span> <span m="138248">particular</span>
  <span m="138540">location</span> <span m="138831">in</span> <span m="139122">the</span>
  <span m="139413">register</span> <span m="139705">file</span> <span m="139996">associated</span>
  <span m="140287">with</span> <span m="140579">each</span> <span m="140958">datapath,</span>
  <span m="141337">while</span> <span m="141717">the</span> <span m="142096">&quot;R&quot;</span>
  <span m="142475">registers</span> <span m="142855">are</span> <span m="143234">the</span>
  <span m="143613">conventional</span> <span m="143993">Beta</span> <span m="144372">registers</span>
  <span m="144751">used</span> <span m="145131">for</span> <span m="145510">address</span>
  <span m="145890">computations,</span> <span m="146395">etc.</span></p><p><span m="146900">It</span>
  <span m="147253">would</span> <span m="147606">only</span> <span m="147960">take</span>
  <span m="148313">4</span> <span m="148666">cycles</span> <span m="149020">for</span>
  <span m="149373">the</span> <span m="149726">vector</span> <span m="150080">processor</span>
  <span m="150433">to</span> <span m="150786">complete</span> <span m="151140">the</span>
  <span m="151493">desired</span> <span m="151846">operations,</span> <span m="152200">a</span>
  <span m="152780">speed-up</span> <span m="153360">of</span> <span m="153940">40.</span></p><p><span
  m="154520">This</span> <span m="155029">example</span> <span m="155539">shows</span>
  <span m="156049">the</span> <span m="156559">best-possible</span> <span m="157069">speed-up.</span></p><p><span
  m="157579">The</span> <span m="157875">key</span> <span m="158172">to</span> <span
  m="158469">a</span> <span m="158766">good</span> <span m="159063">speed-up</span>
  <span m="159360">is</span> <span m="159657">our</span> <span m="159954">ability</span>
  <span m="160250">to</span> <span m="160547">&quot;vectorize&quot;</span> <span m="160844">the</span>
  <span m="161141">code</span> <span m="161438">and</span> <span m="161735">take</span>
  <span m="162032">advantage</span> <span m="162329">of</span> <span m="162832">all</span>
  <span m="163335">the</span> <span m="163838">datapaths</span> <span m="164341">operating</span>
  <span m="164844">in</span> <span m="165347">parallel.</span></p><p><span m="165850">This</span>
  <span m="166228">isn't</span> <span m="166607">possible</span> <span m="166985">for</span>
  <span m="167364">every</span> <span m="167742">application,</span> <span m="168121">but</span>
  <span m="168500">for</span> <span m="168878">tasks</span> <span m="169257">like</span>
  <span m="169635">audio</span> <span m="170014">or</span> <span m="170392">video</span>
  <span m="170771">encoding</span> <span m="171150">and</span> <span m="171691">decoding,</span>
  <span m="172233">and</span> <span m="172774">all</span> <span m="173316">sorts</span>
  <span m="173857">of</span> <span m="174399">digital</span> <span m="174940">signal</span>
  <span m="175482">processing,</span> <span m="176023">vectorization</span> <span
  m="176565">is</span> <span m="177106">very</span> <span m="177648">doable.</span></p><p><span
  m="178190">Memory</span> <span m="178622">operations</span> <span m="179054">enjoy</span>
  <span m="179486">a</span> <span m="179919">similar</span> <span m="180351">performance</span>
  <span m="180783">improvement</span> <span m="181216">since</span> <span m="181648">the</span>
  <span m="182080">access</span> <span m="182513">overhead</span> <span m="182945">is</span>
  <span m="183377">amortized</span> <span m="183810">over</span> <span m="184354">large</span>
  <span m="184898">blocks</span> <span m="185442">of</span> <span m="185986">data.</span></p><p><span
  m="186530">You</span> <span m="186865">might</span> <span m="187200">wonder</span>
  <span m="187535">if</span> <span m="187870">it's</span> <span m="188205">possible</span>
  <span m="188540">to</span> <span m="188875">efficiently</span> <span m="189210">perform</span>
  <span m="189545">data-dependent</span> <span m="189880">operations</span> <span
  m="190215">on</span> <span m="190550">a</span> <span m="190885">vector</span> <span
  m="191220">processor.</span></p><p><span m="193520">Data-dependent</span> <span
  m="193916">operations</span> <span m="194312">appear</span> <span m="194708">as</span>
  <span m="195104">conditional</span> <span m="195500">statements</span> <span m="195896">on</span>
  <span m="196292">conventional</span> <span m="196688">machines,</span> <span m="197084">where</span>
  <span m="197480">the</span> <span m="197832">body</span> <span m="198185">of</span>
  <span m="198537">the</span> <span m="198890">statement</span> <span m="199242">is</span>
  <span m="199595">executed</span> <span m="199947">if</span> <span m="200300">the</span>
  <span m="200652">condition</span> <span m="201005">is</span> <span m="201357">true.</span></p><p><span
  m="201710">If</span> <span m="202025">testing</span> <span m="202340">and</span>
  <span m="202656">branching</span> <span m="202971">is</span> <span m="203286">under</span>
  <span m="203602">the</span> <span m="203917">control</span> <span m="204233">of</span>
  <span m="204548">the</span> <span m="204863">single-instruction</span> <span m="205179">execution</span>
  <span m="205494">engine,</span> <span m="205810">how</span> <span m="206361">can</span>
  <span m="206912">we</span> <span m="207463">take</span> <span m="208014">advantage</span>
  <span m="208565">of</span> <span m="209116">the</span> <span m="209667">parallel</span>
  <span m="210218">datapaths?</span></p><p><span m="210770">The</span> <span m="211189">trick</span>
  <span m="211608">is</span> <span m="212027">provide</span> <span m="212446">each</span>
  <span m="212865">datapath</span> <span m="213284">with</span> <span m="213703">a</span>
  <span m="214122">local</span> <span m="214541">predicate</span> <span m="214960">flag.</span></p><p><span
  m="215380">Use</span> <span m="215817">a</span> <span m="216255">vectorized</span>
  <span m="216693">compare</span> <span m="217131">instruction</span> <span m="217569">(CMPLT.V)</span>
  <span m="218007">to</span> <span m="218445">perform</span> <span m="218882">the</span>
  <span m="219320">a[i]</span>  <span m="220196">b[i]</span> <span m="220634">comparisons</span>
  <span m="221072">in</span> <span m="221510">parallel</span> <span m="222000">and</span>
  <span m="222490">remember</span> <span m="222980">the</span> <span m="223470">result</span>
  <span m="223960">locally</span> <span m="224450">in</span> <span m="224940">each</span>
  <span m="225430">datapath's</span> <span m="225920">predicate</span> <span m="226410">flag.</span></p><p><span
  m="226900">Then</span> <span m="227356">extend</span> <span m="227812">the</span>
  <span m="228269">vector</span> <span m="228725">ISA</span> <span m="229182">to</span>
  <span m="229638">include</span> <span m="230095">&quot;predicated</span> <span m="230551">instructions&quot;</span>
  <span m="231007">which</span> <span m="231464">check</span> <span m="231920">the</span>
  <span m="232377">local</span> <span m="232833">predicate</span> <span m="233290">to</span>
  <span m="233650">see</span> <span m="234010">if</span> <span m="234370">they</span>
  <span m="234730">should</span> <span m="235090">execute</span> <span m="235450">or</span>
  <span m="235810">do</span> <span m="236170">nothing.</span></p><p><span m="236530">In</span>
  <span m="236983">this</span> <span m="237437">example,</span> <span m="237891">ADDC.V.iftrue</span>
  <span m="238345">only</span> <span m="238798">performs</span> <span m="239252">the</span>
  <span m="239706">ADDC</span> <span m="240160">on</span> <span m="240613">the</span>
  <span m="241067">local</span> <span m="241521">data</span> <span m="241975">if</span>
  <span m="242428">the</span> <span m="242882">local</span> <span m="243336">predicate</span>
  <span m="243790">flag</span> <span m="244583">is</span> <span m="245376">true.</span></p><p><span
  m="246170">Instruction</span> <span m="246549">predication</span> <span m="246928">is</span>
  <span m="247307">also</span> <span m="247686">used</span> <span m="248066">in</span>
  <span m="248445">many</span> <span m="248824">non-vector</span> <span m="249203">architectures</span>
  <span m="249583">to</span> <span m="249962">avoid</span> <span m="250341">the</span>
  <span m="250720">execution-time</span> <span m="251100">penalties</span> <span m="251668">associated</span>
  <span m="252236">with</span> <span m="252805">mis-predicted</span> <span m="253373">conditional</span>
  <span m="253941">branches.</span></p><p><span m="254510">They</span> <span m="254970">are</span>
  <span m="255431">particularly</span> <span m="255891">useful</span> <span m="256352">for</span>
  <span m="256813">simple</span> <span m="257273">arithmetic</span> <span m="257734">and</span>
  <span m="258195">boolean</span> <span m="258655">operations</span> <span m="259116">(i.e.,</span>
  <span m="259577">very</span> <span m="260037">short</span> <span m="260498">instruction</span>
  <span m="260959">sequences)</span> <span m="261383">that</span> <span m="261808">should</span>
  <span m="262232">be</span> <span m="262657">executed</span> <span m="263082">only</span>
  <span m="263506">if</span> <span m="263931">a</span> <span m="264356">condition</span>
  <span m="264780">is</span> <span m="265205">met.</span></p><p><span m="265630">The</span>
  <span m="266175">x86</span> <span m="266721">ISA</span> <span m="267267">includes</span>
  <span m="267813">a</span> <span m="268359">conditional</span> <span m="268904">move</span>
  <span m="269450">instruction,</span> <span m="269996">and</span> <span m="270542">in</span>
  <span m="271088">the</span> <span m="271634">32-bit</span> <span m="272179">ARM</span>
  <span m="272725">ISA</span> <span m="273271">almost</span> <span m="273817">all</span>
  <span m="274363">instructions</span> <span m="274909">can</span> <span m="275586">be</span>
  <span m="276264">conditionally</span> <span m="276942">executed.</span></p><p><span
  m="277620">The</span> <span m="278020">power</span> <span m="278420">of</span> <span
  m="278820">vector</span> <span m="279220">processors</span> <span m="279620">comes</span>
  <span m="280020">from</span> <span m="280420">having</span> <span m="280820">1</span>
  <span m="281220">instruction</span> <span m="281620">initiate</span> <span m="282020">N</span>
  <span m="282420">parallel</span> <span m="282820">operations</span> <span m="283220">on</span>
  <span m="283810">N</span> <span m="284400">pairs</span> <span m="284990">of</span>
  <span m="285580">operands.</span></p><p><span m="286170">Most</span> <span m="286595">modern</span>
  <span m="287020">CPUs</span> <span m="287446">incorporate</span> <span m="287871">vector</span>
  <span m="288296">extensions</span> <span m="288722">that</span> <span m="289147">operate</span>
  <span m="289572">in</span> <span m="289998">parallel</span> <span m="290423">on</span>
  <span m="290848">8-,</span> <span m="291274">16-,</span> <span m="291699">32-</span>
  <span m="292124">or</span> <span m="292550">64-bit</span> <span m="293169">operands</span>
  <span m="293788">organized</span> <span m="294407">as</span> <span m="295026">blocks</span>
  <span m="295645">of</span> <span m="296264">128-,</span> <span m="296883">256-,</span>
  <span m="297502">or</span> <span m="298121">512-bit</span> <span m="298740">data.</span></p><p><span
  m="299360">Often</span> <span m="299691">all</span> <span m="300022">that's</span>
  <span m="300353">needed</span> <span m="300685">is</span> <span m="301016">some</span>
  <span m="301347">simple</span> <span m="301678">additional</span> <span m="302010">logic</span>
  <span m="302341">on</span> <span m="302672">an</span> <span m="303003">ALU</span>
  <span m="303335">designed</span> <span m="303666">to</span> <span m="303997">process</span>
  <span m="304328">full-width</span> <span m="304660">operands.</span></p><p><span
  m="306130">The</span> <span m="306548">parallelism</span> <span m="306967">is</span>
  <span m="307385">baked</span> <span m="307804">into</span> <span m="308222">the</span>
  <span m="308641">vector</span> <span m="309060">program,</span> <span m="309478">not</span>
  <span m="309897">discovered</span> <span m="310315">on-the-fly</span> <span m="310734">by</span>
  <span m="311152">the</span> <span m="311571">instruction</span> <span m="311990">dispatch</span>
  <span m="312742">and</span> <span m="313495">execution</span> <span m="314247">machinery.</span></p><p><span
  m="315000">Writing</span> <span m="315350">the</span> <span m="315700">specialized</span>
  <span m="316050">vector</span> <span m="316400">programs</span> <span m="316750">is</span>
  <span m="317100">a</span> <span m="317450">worthwhile</span> <span m="317800">investment</span>
  <span m="318150">for</span> <span m="318500">certain</span> <span m="318850">library</span>
  <span m="319200">functions</span> <span m="319557">which</span> <span m="319915">see</span>
  <span m="320273">a</span> <span m="320631">lot</span> <span m="320989">use</span>
  <span m="321347">in</span> <span m="321705">processing</span> <span m="322062">today's</span>
  <span m="322420">information</span> <span m="322778">streams</span> <span m="323136">with</span>
  <span m="323494">their</span> <span m="323852">heavy</span> <span m="324210">use</span>
  <span m="324933">of</span> <span m="325656">images,</span> <span m="326380">and</span>
  <span m="327103">A/V</span> <span m="327826">material.</span></p><p><span m="328550">Perhaps</span>
  <span m="328945">the</span> <span m="329341">best</span> <span m="329737">example</span>
  <span m="330133">of</span> <span m="330529">architectures</span> <span m="330925">with</span>
  <span m="331320">many</span> <span m="331716">datapaths</span> <span m="332112">operating</span>
  <span m="332508">in</span> <span m="332904">parallel</span> <span m="333300">are</span>
  <span m="333780">the</span> <span m="334261">graphics</span> <span m="334742">processing</span>
  <span m="335223">units</span> <span m="335703">(GPUs)</span> <span m="336184">found</span>
  <span m="336665">in</span> <span m="337146">almost</span> <span m="337626">all</span>
  <span m="338107">computer</span> <span m="338588">graphics</span> <span m="339069">systems.</span></p><p><span
  m="339550">GPU</span> <span m="340074">datapaths</span> <span m="340599">are</span>
  <span m="341123">typically</span> <span m="341648">specialized</span> <span m="342173">for</span>
  <span m="342697">32-</span> <span m="343222">and</span> <span m="343746">64-bit</span>
  <span m="344271">floating</span> <span m="344796">point</span> <span m="345320">operations</span>
  <span m="345845">found</span> <span m="346370">in</span> <span m="346726">the</span>
  <span m="347083">algorithms</span> <span m="347440">needed</span> <span m="347797">to</span>
  <span m="348154">display</span> <span m="348511">in</span> <span m="348868">real-time</span>
  <span m="349225">a</span> <span m="349581">3D</span> <span m="349938">scene</span>
  <span m="350295">represented</span> <span m="350652">as</span> <span m="351009">billions</span>
  <span m="351366">of</span> <span m="351723">triangular</span> <span m="352080">patches</span>
  <span m="352488">as</span> <span m="352897">a</span> <span m="353306">2D</span>
  <span m="353715">image</span> <span m="354124">on</span> <span m="354533">the</span>
  <span m="354942">computer</span> <span m="355351">screen.</span></p><p><span m="355760">Coordinate</span>
  <span m="356292">transformation,</span> <span m="356825">pixel</span> <span m="357358">shading</span>
  <span m="357890">and</span> <span m="358423">antialiasing,</span> <span m="358956">texture</span>
  <span m="359489">mapping,</span> <span m="360021">etc.,</span> <span m="360554">are</span>
  <span m="361087">examples</span> <span m="361620">of</span> <span m="362034">&quot;embarrassingly</span>
  <span m="362449">parallel&quot;</span> <span m="362863">computations</span> <span
  m="363278">where</span> <span m="363692">the</span> <span m="364107">parallelism</span>
  <span m="364521">comes</span> <span m="364936">from</span> <span m="365350">having</span>
  <span m="365765">to</span> <span m="366180">perform</span> <span m="366728">the</span>
  <span m="367276">same</span> <span m="367824">computation</span> <span m="368372">independently</span>
  <span m="368920">on</span> <span m="369469">millions</span> <span m="370017">of</span>
  <span m="370565">different</span> <span m="371113">data</span> <span m="371661">objects.</span></p><p><span
  m="372210">Similar</span> <span m="372602">problems</span> <span m="372994">can</span>
  <span m="373386">be</span> <span m="373778">found</span> <span m="374170">in</span>
  <span m="374562">the</span> <span m="374955">fields</span> <span m="375347">of</span>
  <span m="375739">bioinformatics,</span> <span m="376131">big</span> <span m="376523">data</span>
  <span m="376915">processing,</span> <span m="377307">neural</span> <span m="377700">net</span>
  <span m="378064">emulation</span> <span m="378428">used</span> <span m="378792">in</span>
  <span m="379156">deep</span> <span m="379520">machine</span> <span m="379884">learning,</span>
  <span m="380248">and</span> <span m="380612">so</span> <span m="380976">on.</span></p><p><span
  m="381340">Increasingly,</span> <span m="381844">GPUs</span> <span m="382348">are</span>
  <span m="382852">used</span> <span m="383356">in</span> <span m="383860">many</span>
  <span m="384365">interesting</span> <span m="384869">scientific</span> <span m="385373">and</span>
  <span m="385877">engineering</span> <span m="386381">calculations</span> <span m="386885">and</span>
  <span m="387390">not</span> <span m="388100">just</span> <span m="388810">as</span>
  <span m="389520">graphics</span> <span m="390230">engines.</span></p><p><span m="390940">Data-level</span>
  <span m="391363">parallelism</span> <span m="391787">provides</span> <span m="392210">significant</span>
  <span m="392634">performance</span> <span m="393058">improvements</span> <span m="393481">in</span>
  <span m="393905">a</span> <span m="394329">variety</span> <span m="394752">of</span>
  <span m="395176">useful</span> <span m="395600">situations.</span></p><p><span m="397090">So</span>
  <span m="397557">current</span> <span m="398025">and</span> <span m="398493">future</span>
  <span m="398960">ISAs</span> <span m="399428">will</span> <span m="399896">almost</span>
  <span m="400363">certainly</span> <span m="400831">include</span> <span m="401299">support</span>
  <span m="401766">for</span> <span m="402234">vector</span> <span m="402702">operations.</span></p>
type: course
uid: 1bbb5576cd5b73a77b891ecd42b3f5f8

---
None