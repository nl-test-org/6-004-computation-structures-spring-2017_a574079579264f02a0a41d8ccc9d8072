---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 8MWU1PxvaDY
  parent_uid: e367ce3b283c0587a97ad45a8d892130
  title: Video-YouTube-Stream
  type: Video
  uid: 2504a6e1b221e534aa68838e30f30bf0
- id: 3Play-3Play YouTube id-Stream
  media_location: 8MWU1PxvaDY
  parent_uid: e367ce3b283c0587a97ad45a8d892130
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 0586f5fb33b507de31eb21c0b1f3cabd
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/8MWU1PxvaDY/default.jpg
  parent_uid: e367ce3b283c0587a97ad45a8d892130
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: c9529f220c5eaa0bfd5ae8142308697d
- id: 8MWU1PxvaDY.srt
  parent_uid: e367ce3b283c0587a97ad45a8d892130
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/os-device-handlers-6-07-/8MWU1PxvaDY.srt
  title: 3play caption file
  type: null
  uid: 1a0bfcb8730920e259fa5da5adbced2d
- id: 8MWU1PxvaDY.pdf
  parent_uid: e367ce3b283c0587a97ad45a8d892130
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/os-device-handlers-6-07-/8MWU1PxvaDY.pdf
  title: 3play pdf file
  type: null
  uid: 3bc8835c066da014a1e0d7cec02cc664
- id: Caption-3Play YouTube id-SRT
  parent_uid: e367ce3b283c0587a97ad45a8d892130
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 346366153fc931b2c3fb8a95a7045040
- id: Transcript-3Play YouTube id-PDF
  parent_uid: e367ce3b283c0587a97ad45a8d892130
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 0e0c1bf349063723a3bff5f375585ac2
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_18-02-01_300k.mp4
  parent_uid: e367ce3b283c0587a97ad45a8d892130
  title: Video-Internet Archive-MP4
  type: Video
  uid: fde7382430c66afb554cad2e0b499a93
inline_embed_id: 78629481osdevicehandlers60744285459
layout: video
order_index: null
parent_uid: fa697aed8dfd8206d150e1218c118201
related_resources_text: ''
short_url: os-device-handlers-6-07-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/os-device-handlers-6-07-
template_type: Embed
title: OS Device Handlers
transcript: <p><span m="290">Let's</span> <span m="694">turn</span> <span m="1098">our</span>
  <span m="1502">attention</span> <span m="1907">to</span> <span m="2311">how</span>
  <span m="2715">the</span> <span m="3120">operating</span> <span m="3524">system</span>
  <span m="3928">(OS)</span> <span m="4332">deals</span> <span m="4737">with</span>
  <span m="5141">input/output</span> <span m="5545">devices.</span></p><p><span m="5950">There</span>
  <span m="6252">are</span> <span m="6555">actually</span> <span m="6857">two</span>
  <span m="7160">parts</span> <span m="7462">to</span> <span m="7765">the</span> <span
  m="8067">discussion.</span></p><p><span m="8370">First,</span> <span m="8848">we'll</span>
  <span m="9326">talk</span> <span m="9805">about</span> <span m="10283">how</span>
  <span m="10761">the</span> <span m="11240">OS</span> <span m="11718">interacts</span>
  <span m="12196">with</span> <span m="12675">the</span> <span m="13153">devices</span>
  <span m="13631">themselves.</span></p><p><span m="14110">This</span> <span m="14479">will</span>
  <span m="14848">involve</span> <span m="15217">a</span> <span m="15586">combination</span>
  <span m="15955">of</span> <span m="16324">interrupt</span> <span m="16693">handlers</span>
  <span m="17062">and</span> <span m="17431">kernel</span> <span m="17800">buffers.</span></p><p><span
  m="18170">Then</span> <span m="18568">we'll</span> <span m="18967">discuss</span>
  <span m="19365">how</span> <span m="19764">supervisor</span> <span m="20162">calls</span>
  <span m="20561">access</span> <span m="20960">the</span> <span m="21358">kernel</span>
  <span m="21757">buffers</span> <span m="22155">in</span> <span m="22554">response</span>
  <span m="22952">to</span> <span m="23351">requests</span> <span m="23750">from</span>
  <span m="24543">user-mode</span> <span m="25336">processes.</span></p><p><span m="26130">As</span>
  <span m="26405">we'll</span> <span m="26680">see,</span> <span m="26955">this</span>
  <span m="27230">can</span> <span m="27505">get</span> <span m="27780">a</span> <span
  m="28055">bit</span> <span m="28330">tricky</span> <span m="28605">when</span> <span
  m="28880">the</span> <span m="29155">OS</span> <span m="29430">cannot</span> <span
  m="29705">complete</span> <span m="29980">the</span> <span m="30255">request</span>
  <span m="30530">at</span> <span m="30805">the</span> <span m="31080">time</span>
  <span m="31722">the</span> <span m="32364">SVC</span> <span m="33006">was</span>
  <span m="33648">executed.</span></p><p><span m="34290">Here's</span> <span m="34640">the</span>
  <span m="34990">plan!</span></p><p><span m="35340">When</span> <span m="35613">the</span>
  <span m="35886">user</span> <span m="36160">types</span> <span m="36433">a</span>
  <span m="36706">key</span> <span m="36980">on</span> <span m="37253">the</span>
  <span m="37526">keyboard,</span> <span m="37800">the</span> <span m="38073">keyboard</span>
  <span m="38346">triggers</span> <span m="38620">an</span> <span m="38893">interrupt</span>
  <span m="39166">request</span> <span m="39440">to</span> <span m="39933">the</span>
  <span m="40426">CPU.</span></p><p><span m="40920">The</span> <span m="41331">interrupt</span>
  <span m="41742">suspends</span> <span m="42154">execution</span> <span m="42565">of</span>
  <span m="42977">the</span> <span m="43388">currently-running</span> <span m="43800">process</span>
  <span m="44211">and</span> <span m="44622">executes</span> <span m="45034">the</span>
  <span m="45445">handler</span> <span m="45857">whose</span> <span m="46268">job</span>
  <span m="46680">it</span> <span m="47018">is</span> <span m="47357">to</span> <span
  m="47696">deal</span> <span m="48035">with</span> <span m="48374">this</span> <span
  m="48713">particular</span> <span m="49052">I/O</span> <span m="49391">event.</span></p><p><span
  m="49730">In</span> <span m="49994">this</span> <span m="50258">case,</span> <span
  m="50523">the</span> <span m="50787">keyboard</span> <span m="51051">handler</span>
  <span m="51316">reads</span> <span m="51580">the</span> <span m="51845">character</span>
  <span m="52109">from</span> <span m="52373">the</span> <span m="52638">keyboard</span>
  <span m="52902">and</span> <span m="53166">saves</span> <span m="53431">it</span>
  <span m="53695">in</span> <span m="53960">a</span> <span m="54402">kernel</span>
  <span m="54845">buffer</span> <span m="55288">associated</span> <span m="55730">with</span>
  <span m="56173">the</span> <span m="56616">process</span> <span m="57058">that</span>
  <span m="57501">has</span> <span m="57944">been</span> <span m="58386">chosen</span>
  <span m="58829">to</span> <span m="59272">receive</span> <span m="59714">incoming</span>
  <span m="60157">keystrokes.</span></p><p><span m="60600">In</span> <span m="60986">the</span>
  <span m="61372">language</span> <span m="61758">of</span> <span m="62144">OSes,</span>
  <span m="62530">we'd</span> <span m="62916">say</span> <span m="63303">that</span>
  <span m="63689">process</span> <span m="64075">has</span> <span m="64461">the</span>
  <span m="64847">keyboard</span> <span m="65233">focus.</span></p><p><span m="65620">This</span>
  <span m="65964">transfer</span> <span m="66308">takes</span> <span m="66653">just</span>
  <span m="66997">a</span> <span m="67341">handful</span> <span m="67686">of</span>
  <span m="68030">instructions</span> <span m="68375">and</span> <span m="68719">when</span>
  <span m="69063">the</span> <span m="69408">handler</span> <span m="69752">exits,</span>
  <span m="70096">we</span> <span m="70441">resume</span> <span m="70785">running</span>
  <span m="71130">the</span> <span m="72170">interrupted</span> <span m="73210">process.</span></p><p><span
  m="74250">Assuming</span> <span m="74582">the</span> <span m="74914">interrupt</span>
  <span m="75246">request</span> <span m="75578">is</span> <span m="75910">serviced</span>
  <span m="76242">promptly,</span> <span m="76575">the</span> <span m="76907">CPU</span>
  <span m="77239">can</span> <span m="77571">easily</span> <span m="77903">keep</span>
  <span m="78235">up</span> <span m="78567">with</span> <span m="78900">the</span>
  <span m="79358">arrival</span> <span m="79816">of</span> <span m="80274">typed</span>
  <span m="80732">characters.</span></p><p><span m="81190">Humans</span> <span m="81597">are</span>
  <span m="82004">pretty</span> <span m="82411">slow</span> <span m="82819">compared</span>
  <span m="83226">to</span> <span m="83633">the</span> <span m="84040">rate</span>
  <span m="84448">of</span> <span m="84855">executing</span> <span m="85262">instructions!</span></p><p><span
  m="85670">But</span> <span m="85943">the</span> <span m="86217">buffer</span> <span
  m="86491">in</span> <span m="86764">the</span> <span m="87038">kernel</span> <span
  m="87312">can</span> <span m="87585">hold</span> <span m="87859">only</span> <span
  m="88133">so</span> <span m="88406">many</span> <span m="88680">characters</span>
  <span m="88954">before</span> <span m="89227">it</span> <span m="89501">fills</span>
  <span m="89775">up.</span></p><p><span m="90049">What</span> <span m="90426">happens</span>
  <span m="90803">then?</span></p><p><span m="91180">Well,</span> <span m="91634">there</span>
  <span m="92088">are</span> <span m="92542">a</span> <span m="92997">couple</span>
  <span m="93451">of</span> <span m="93905">choices.</span></p><p><span m="94360">Overwriting</span>
  <span m="94772">characters</span> <span m="95185">received</span> <span m="95597">earlier</span>
  <span m="96010">doesn't</span> <span m="96422">make</span> <span m="96835">much</span>
  <span m="97247">sense:</span> <span m="97660">why</span> <span m="98072">keep</span>
  <span m="98485">later</span> <span m="98897">characters</span> <span m="99310">if</span>
  <span m="99602">the</span> <span m="99895">earlier</span> <span m="100188">ones</span>
  <span m="100481">have</span> <span m="100774">been</span> <span m="101067">discarded.</span></p><p><span
  m="101360">Better</span> <span m="101756">that</span> <span m="102153">the</span>
  <span m="102550">CPU</span> <span m="102946">discard</span> <span m="103343">any</span>
  <span m="103740">characters</span> <span m="104136">received</span> <span m="104533">after</span>
  <span m="104930">the</span> <span m="105326">buffer</span> <span m="105723">was</span>
  <span m="106120">full,</span> <span m="106516">but</span> <span m="106913">it</span>
  <span m="107310">should</span> <span m="107645">give</span> <span m="107980">some</span>
  <span m="108315">indication</span> <span m="108650">that</span> <span m="108985">it's</span>
  <span m="109320">doing</span> <span m="109655">so.</span></p><p><span m="109990">And,</span>
  <span m="110320">in</span> <span m="110651">fact,</span> <span m="110981">many</span>
  <span m="111312">systems</span> <span m="111643">beep</span> <span m="111973">at</span>
  <span m="112304">the</span> <span m="112635">user</span> <span m="112965">to</span>
  <span m="113296">signal</span> <span m="113626">that</span> <span m="113957">the</span>
  <span m="114288">character</span> <span m="114618">they've</span> <span m="114949">just</span>
  <span m="115280">typed</span> <span m="116110">is</span> <span m="116940">being</span>
  <span m="117770">ignored.</span></p><p><span m="118600">At</span> <span m="119005">some</span>
  <span m="119411">later</span> <span m="119817">time,</span> <span m="120222">a</span>
  <span m="120628">user-mode</span> <span m="121034">program</span> <span m="121440">executes</span>
  <span m="121845">a</span> <span m="122251">ReadKey()</span> <span m="122657">supervisor</span>
  <span m="123062">call,</span> <span m="123468">requesting</span> <span m="123874">that</span>
  <span m="124280">the</span> <span m="124803">OS</span> <span m="125327">return</span>
  <span m="125851">the</span> <span m="126375">next</span> <span m="126898">character</span>
  <span m="127422">in</span> <span m="127946">R0.</span></p><p><span m="128470">In</span>
  <span m="128858">the</span> <span m="129246">OS,</span> <span m="129634">the</span>
  <span m="130022">ReadKey</span> <span m="130410">SVC</span> <span m="130798">handler</span>
  <span m="131186">grabs</span> <span m="131575">the</span> <span m="131963">next</span>
  <span m="132351">character</span> <span m="132739">from</span> <span m="133127">the</span>
  <span m="133515">buffer,</span> <span m="133903">places</span> <span m="134291">it</span>
  <span m="134680">in</span> <span m="135183">the</span> <span m="135687">user's</span>
  <span m="136191">R0,</span> <span m="136695">and</span> <span m="137199">resumes</span>
  <span m="137703">execution</span> <span m="138206">at</span> <span m="138710">the</span>
  <span m="139214">instruction</span> <span m="139718">following</span> <span m="140222">the</span>
  <span m="140726">SVC.</span></p><p><span m="141230">There</span> <span m="141530">are</span>
  <span m="141830">few</span> <span m="142130">tricky</span> <span m="142430">bits</span>
  <span m="142730">we</span> <span m="143030">need</span> <span m="143330">to</span>
  <span m="143630">figure</span> <span m="143930">out.</span></p><p><span m="144230">The</span>
  <span m="144664">ReadKey()</span> <span m="145099">SVC</span> <span m="145534">is</span>
  <span m="145969">what</span> <span m="146404">we</span> <span m="146839">call</span>
  <span m="147274">a</span> <span m="147709">&quot;blocking</span> <span m="148144">I/O&quot;</span>
  <span m="148579">request,</span> <span m="149014">i.e.,</span> <span m="149449">the</span>
  <span m="149884">program</span> <span m="150319">assumes</span> <span m="150754">that</span>
  <span m="151189">when</span> <span m="151664">the</span> <span m="152139">SVC</span>
  <span m="152614">returns,</span> <span m="153089">the</span> <span m="153564">next</span>
  <span m="154039">character</span> <span m="154514">is</span> <span m="154989">in</span>
  <span m="155464">R0.</span></p><p><span m="155939">If</span> <span m="156353">there</span>
  <span m="156767">isn't</span> <span m="157181">(yet)</span> <span m="157595">a</span>
  <span m="158009">character</span> <span m="158423">to</span> <span m="158837">be</span>
  <span m="159251">returned,</span> <span m="159665">execution</span> <span m="160079">should</span>
  <span m="160493">be</span> <span m="160907">&quot;blocked&quot;,</span> <span m="161321">i.e.,</span>
  <span m="161735">suspended,</span> <span m="162150">until</span> <span m="162625">such</span>
  <span m="163100">time</span> <span m="163575">that</span> <span m="164050">a</span>
  <span m="164525">character</span> <span m="165000">is</span> <span m="165475">available.</span></p><p><span
  m="165950">Many</span> <span m="166395">OSes</span> <span m="166840">also</span>
  <span m="167285">provide</span> <span m="167730">for</span> <span m="168175">non-blocking</span>
  <span m="168620">I/O</span> <span m="169065">requests,</span> <span m="169510">which</span>
  <span m="169955">always</span> <span m="170400">return</span> <span m="170845">immediately</span>
  <span m="171290">with</span> <span m="171705">both</span> <span m="172120">a</span>
  <span m="172535">status</span> <span m="172950">flag</span> <span m="173365">and</span>
  <span m="173780">a</span> <span m="174195">result.</span></p><p><span m="174610">The</span>
  <span m="174822">program</span> <span m="175034">can</span> <span m="175246">check</span>
  <span m="175458">the</span> <span m="175671">status</span> <span m="175883">flag</span>
  <span m="176095">to</span> <span m="176307">see</span> <span m="176520">if</span>
  <span m="176732">there</span> <span m="176944">was</span> <span m="177156">a</span>
  <span m="177368">character</span> <span m="177581">and</span> <span m="177793">do</span>
  <span m="178005">the</span> <span m="178217">right</span> <span m="178430">thing</span>
  <span m="178873">if</span> <span m="179316">there</span> <span m="179759">wasn't,</span>
  <span m="180203">e.g.,</span> <span m="180646">reissue</span> <span m="181089">the</span>
  <span m="181532">request</span> <span m="181976">at</span> <span m="182419">a</span>
  <span m="182862">later</span> <span m="183305">time.</span></p><p><span m="183749">Note</span>
  <span m="184063">that</span> <span m="184378">the</span> <span m="184693">user-mode</span>
  <span m="185007">program</span> <span m="185322">didn't</span> <span m="185637">have</span>
  <span m="185951">any</span> <span m="186266">direct</span> <span m="186581">interaction</span>
  <span m="186895">with</span> <span m="187210">the</span> <span m="187525">keyboard,</span>
  <span m="187840">i.e.,</span> <span m="188188">it's</span> <span m="188536">not</span>
  <span m="188884">constantly</span> <span m="189232">polling</span> <span m="189580">the</span>
  <span m="189928">device</span> <span m="190276">to</span> <span m="190624">see</span>
  <span m="190972">if</span> <span m="191320">there's</span> <span m="191668">a</span>
  <span m="192016">keystroke</span> <span m="192364">to</span> <span m="192712">be</span>
  <span m="193060">processed.</span></p><p><span m="193409">Instead,</span> <span
  m="193838">we're</span> <span m="194267">using</span> <span m="194697">an</span>
  <span m="195126">&quot;event-driven&quot;</span> <span m="195555">approach,</span>
  <span m="195985">where</span> <span m="196414">the</span> <span m="196843">device</span>
  <span m="197273">signals</span> <span m="197702">the</span> <span m="198131">OS,</span>
  <span m="198561">via</span> <span m="198990">an</span> <span m="199419">interrupt,</span>
  <span m="199849">when</span> <span m="200344">it</span> <span m="200839">needs</span>
  <span m="201334">attention.</span></p><p><span m="201829">This</span> <span m="202269">is</span>
  <span m="202709">an</span> <span m="203149">elegant</span> <span m="203589">separation</span>
  <span m="204029">of</span> <span m="204469">responsibilities.</span></p><p><span
  m="204909">Imagine</span> <span m="205236">how</span> <span m="205564">cumbersome</span>
  <span m="205891">it</span> <span m="206219">would</span> <span m="206546">be</span>
  <span m="206874">if</span> <span m="207201">every</span> <span m="207529">program</span>
  <span m="207857">had</span> <span m="208184">to</span> <span m="208512">check</span>
  <span m="208839">constantly</span> <span m="209167">to</span> <span m="209494">see</span>
  <span m="209822">if</span> <span m="210150">there</span> <span m="210585">were</span>
  <span m="211021">pending</span> <span m="211457">I/O</span> <span m="211893">operations.</span></p><p><span
  m="212329">Our</span> <span m="212868">event-driven</span> <span m="213407">organization</span>
  <span m="213946">provides</span> <span m="214485">for</span> <span m="215024">on-demand</span>
  <span m="215564">servicing</span> <span m="216103">of</span> <span m="216642">devices,</span>
  <span m="217181">but</span> <span m="217720">doesn't</span> <span m="218260">devote</span>
  <span m="218700">CPU</span> <span m="219141">resources</span> <span m="219582">to</span>
  <span m="220022">the</span> <span m="220463">I/O</span> <span m="220904">subsystem</span>
  <span m="221345">until</span> <span m="221785">there's</span> <span m="222226">actually</span>
  <span m="222667">work</span> <span m="223107">to</span> <span m="223548">be</span>
  <span m="223989">done.</span></p><p><span m="224430">The</span> <span m="224874">interrupt-driven</span>
  <span m="225318">OS</span> <span m="225763">interactions</span> <span m="226207">with</span>
  <span m="226652">I/O</span> <span m="227096">devices</span> <span m="227541">are</span>
  <span m="227985">completely</span> <span m="228430">transparent</span> <span m="228874">to</span>
  <span m="229319">user</span> <span m="230614">programs.</span></p><p><span m="231909">Here's</span>
  <span m="232309">sketch</span> <span m="232710">of</span> <span m="233111">what</span>
  <span m="233512">the</span> <span m="233913">OS</span> <span m="234314">keyboard</span>
  <span m="234714">handler</span> <span m="235115">code</span> <span m="235516">might</span>
  <span m="235917">actually</span> <span m="236318">look</span> <span m="236719">like.</span></p><p><span
  m="237120">Depending</span> <span m="237523">on</span> <span m="237926">the</span>
  <span m="238329">hardware,</span> <span m="238732">the</span> <span m="239135">CPU</span>
  <span m="239538">might</span> <span m="239941">access</span> <span m="240344">device</span>
  <span m="240747">status</span> <span m="241150">and</span> <span m="241553">data</span>
  <span m="241956">using</span> <span m="242359">special</span> <span m="242762">I/O</span>
  <span m="243165">instructions</span> <span m="243569">in</span> <span m="244145">the</span>
  <span m="244722">ISA.</span></p><p><span m="245299">For</span> <span m="245716">example,</span>
  <span m="246134">in</span> <span m="246552">the</span> <span m="246970">simulated</span>
  <span m="247388">Beta</span> <span m="247806">used</span> <span m="248224">for</span>
  <span m="248642">lab</span> <span m="249060">assignments,</span> <span m="249478">there's</span>
  <span m="249896">a</span> <span m="250314">RDCHAR()</span> <span m="250732">instruction</span>
  <span m="251150">for</span> <span m="251479">reading</span> <span m="251808">keyboard</span>
  <span m="252137">characters</span> <span m="252466">and</span> <span m="252796">a</span>
  <span m="253125">CLICK()</span> <span m="253454">instruction</span> <span m="253783">for</span>
  <span m="254113">reading</span> <span m="254442">the</span> <span m="254771">coordinates</span>
  <span m="255100">of</span> <span m="255430">a</span> <span m="256153">mouse</span>
  <span m="256876">click.</span></p><p><span m="257600">Another</span> <span m="257971">common</span>
  <span m="258342">approach</span> <span m="258714">is</span> <span m="259085">to</span>
  <span m="259456">use</span> <span m="259828">&quot;memory-mapped</span> <span m="260199">I/O&quot;,</span>
  <span m="260570">where</span> <span m="260942">a</span> <span m="261313">portion</span>
  <span m="261684">of</span> <span m="262056">the</span> <span m="262427">kernel</span>
  <span m="262798">address</span> <span m="263170">space</span> <span m="263708">is</span>
  <span m="264247">devoted</span> <span m="264785">to</span> <span m="265324">servicing</span>
  <span m="265862">I/O</span> <span m="266401">devices.</span></p><p><span m="266940">In</span>
  <span m="267359">this</span> <span m="267778">scheme,</span> <span m="268198">ordinary</span>
  <span m="268617">LD</span> <span m="269036">and</span> <span m="269456">ST</span>
  <span m="269875">store</span> <span m="270295">instructions</span> <span m="270714">are</span>
  <span m="271133">used</span> <span m="271553">to</span> <span m="271972">access</span>
  <span m="272391">specific</span> <span m="272811">addresses,</span> <span m="273230">which</span>
  <span m="273650">the</span> <span m="274153">CPU</span> <span m="274656">recognizes</span>
  <span m="275160">as</span> <span m="275663">accesses</span> <span m="276166">to</span>
  <span m="276670">the</span> <span m="277173">keyboard</span> <span m="277676">or</span>
  <span m="278180">mouse</span> <span m="278683">device</span> <span m="279186">interfaces.</span></p><p><span
  m="279690">This</span> <span m="279978">is</span> <span m="280267">the</span> <span
  m="280556">scheme</span> <span m="280845">shown</span> <span m="281134">in</span>
  <span m="281423">the</span> <span m="281712">code</span> <span m="282001">here.</span></p><p><span
  m="282290">The</span> <span m="282652">C</span> <span m="283014">data</span> <span
  m="283376">structure</span> <span m="283738">represents</span> <span m="284100">the</span>
  <span m="284462">two</span> <span m="284824">I/O</span> <span m="285186">locations</span>
  <span m="285548">devoted</span> <span m="285910">to</span> <span m="286272">the</span>
  <span m="286634">keyboard:</span> <span m="286996">one</span> <span m="287358">for</span>
  <span m="287720">status</span> <span m="288392">and</span> <span m="289065">one</span>
  <span m="289737">for</span> <span m="290410">the</span> <span m="291082">actual</span>
  <span m="291755">keyboard</span> <span m="292427">data.</span></p><p><span m="293100">The</span>
  <span m="293455">keyboard</span> <span m="293810">interrupt</span> <span m="294166">handler</span>
  <span m="294521">reads</span> <span m="294876">the</span> <span m="295232">keystroke</span>
  <span m="295587">data</span> <span m="295942">from</span> <span m="296298">the</span>
  <span m="296653">keyboard</span> <span m="297008">and</span> <span m="297364">places</span>
  <span m="297719">the</span> <span m="298074">character</span> <span m="298430">into</span>
  <span m="298940">the</span> <span m="299451">next</span> <span m="299962">location</span>
  <span m="300473">in</span> <span m="300984">the</span> <span m="301495">circular</span>
  <span m="302005">character</span> <span m="302516">buffer</span> <span m="303027">in</span>
  <span m="303538">the</span> <span m="304049">kernel.</span></p><p><span m="304560">In</span>
  <span m="305027">real</span> <span m="305494">life</span> <span m="305961">keyboard</span>
  <span m="306429">processing</span> <span m="306896">is</span> <span m="307363">usually</span>
  <span m="307830">a</span> <span m="308298">bit</span> <span m="308765">more</span>
  <span m="309232">complicated.</span></p><p><span m="309700">What</span> <span m="309990">one</span>
  <span m="310281">actually</span> <span m="310571">reads</span> <span m="310862">from</span>
  <span m="311153">a</span> <span m="311443">keyboard</span> <span m="311734">is</span>
  <span m="312025">a</span> <span m="312315">key</span> <span m="312606">number</span>
  <span m="312896">and</span> <span m="313187">a</span> <span m="313478">flag</span>
  <span m="313768">indicating</span> <span m="314059">whether</span> <span m="314350">the</span>
  <span m="314713">event</span> <span m="315076">is</span> <span m="315439">a</span>
  <span m="315802">key</span> <span m="316165">press</span> <span m="316528">or</span>
  <span m="316891">a</span> <span m="317254">key</span> <span m="317617">release.</span></p><p><span
  m="317980">Knowing</span> <span m="318360">the</span> <span m="318741">keyboard</span>
  <span m="319122">layout,</span> <span m="319502">the</span> <span m="319883">OS</span>
  <span m="320264">translates</span> <span m="320645">the</span> <span m="321025">key</span>
  <span m="321406">number</span> <span m="321787">into</span> <span m="322167">the</span>
  <span m="322548">appropriate</span> <span m="322929">ASCII</span> <span m="323310">character,</span>
  <span m="323731">dealing</span> <span m="324152">with</span> <span m="324574">complications</span>
  <span m="324995">like</span> <span m="325417">holding</span> <span m="325838">down</span>
  <span m="326260">the</span> <span m="326662">shift</span> <span m="327065">key</span>
  <span m="327468">or</span> <span m="327870">control</span> <span m="328273">key</span>
  <span m="328676">to</span> <span m="329078">indicate</span> <span m="329481">a</span>
  <span m="329884">capital</span> <span m="330286">character</span> <span m="330689">or</span>
  <span m="331092">a</span> <span m="331494">control</span> <span m="331897">character.</span></p><p><span
  m="332300">And</span> <span m="332796">certain</span> <span m="333293">combination</span>
  <span m="333790">of</span> <span m="334287">keystrokes,</span> <span m="334784">e.g.,</span>
  <span m="335281">CTRL-ALT-DEL</span> <span m="335778">on</span> <span m="336275">a</span>
  <span m="336772">Windows</span> <span m="337269">system,</span> <span m="337766">are</span>
  <span m="338263">interpreted</span> <span m="338760">as</span> <span m="339171">special</span>
  <span m="339583">user</span> <span m="339994">commands</span> <span m="340406">to</span>
  <span m="340817">start</span> <span m="341229">running</span> <span m="341640">particular</span>
  <span m="342052">applications</span> <span m="342463">like</span> <span m="342875">the</span>
  <span m="343286">Task</span> <span m="343698">Manager.</span></p><p><span m="344110">Many</span>
  <span m="344512">OSes</span> <span m="344915">let</span> <span m="345317">the</span>
  <span m="345720">user</span> <span m="346122">specify</span> <span m="346525">whether</span>
  <span m="346927">they</span> <span m="347330">want</span> <span m="347732">&quot;raw&quot;</span>
  <span m="348135">keyboard</span> <span m="348537">input</span> <span m="348940">(i.e.,</span>
  <span m="349342">the</span> <span m="349745">key</span> <span m="350147">numbers</span>
  <span m="350550">and</span> <span m="351193">status)</span> <span m="351837">or</span>
  <span m="352481">&quot;digested&quot;</span> <span m="353125">input</span> <span
  m="353768">(i.e.,</span> <span m="354412">ASCII</span> <span m="355056">characters).</span></p><p><span
  m="355700">Whew!</span></p><p><span m="356700">Who</span> <span m="357117">knew</span>
  <span m="357535">that</span> <span m="357953">processing</span> <span m="358371">keystrokes</span>
  <span m="358788">could</span> <span m="359206">be</span> <span m="359624">so</span>
  <span m="360042">complicated!</span></p><p><span m="360460">Next,</span> <span m="360865">we'll</span>
  <span m="361271">figure</span> <span m="361676">out</span> <span m="362082">how</span>
  <span m="362488">to</span> <span m="362893">code</span> <span m="363299">the</span>
  <span m="363705">associated</span> <span m="364110">supervisor</span> <span m="364516">call</span>
  <span m="364921">that</span> <span m="365327">lets</span> <span m="365733">user</span>
  <span m="366138">programs</span> <span m="366544">read</span> <span m="366950">characters.</span></p>
type: course
uid: e367ce3b283c0587a97ad45a8d892130

---
None