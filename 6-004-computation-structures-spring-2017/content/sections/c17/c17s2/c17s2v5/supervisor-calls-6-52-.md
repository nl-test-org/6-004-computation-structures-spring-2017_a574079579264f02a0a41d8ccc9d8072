---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: Ykep0YaxgYw
  parent_uid: 7412dbd42c7dce016bb43260a32974cb
  title: Video-YouTube-Stream
  type: Video
  uid: 7bedda4ce95fff1a59fa12334ddde20e
- id: 3Play-3Play YouTube id-Stream
  media_location: Ykep0YaxgYw
  parent_uid: 7412dbd42c7dce016bb43260a32974cb
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 0bdb55d342170f2103d83c41fe9d3bce
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/Ykep0YaxgYw/default.jpg
  parent_uid: 7412dbd42c7dce016bb43260a32974cb
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 2d72df6c2f32c9793445ee9c496502c0
- id: Ykep0YaxgYw.srt
  parent_uid: 7412dbd42c7dce016bb43260a32974cb
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v5/supervisor-calls-6-52-/Ykep0YaxgYw.srt
  title: 3play caption file
  type: null
  uid: 185f28da29ebc9e7d0c7aa1863ac193d
- id: Ykep0YaxgYw.pdf
  parent_uid: 7412dbd42c7dce016bb43260a32974cb
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v5/supervisor-calls-6-52-/Ykep0YaxgYw.pdf
  title: 3play pdf file
  type: null
  uid: be1541dfc16190f5c99ed30473d39ccf
- id: Caption-3Play YouTube id-SRT
  parent_uid: 7412dbd42c7dce016bb43260a32974cb
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 16009d969cbc140201320fa3c3d9a453
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 7412dbd42c7dce016bb43260a32974cb
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: ce523d8ec75c02645fff172096e0c40a
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_17-02-05_300k.mp4
  parent_uid: 7412dbd42c7dce016bb43260a32974cb
  title: Video-Internet Archive-MP4
  type: Video
  uid: 4f9e6961a21513f370dd4ffc4b73631f
inline_embed_id: 23973566supervisorcalls6526653689
layout: video
order_index: null
parent_uid: e2779d0c65f030e58e102fd53b952601
related_resources_text: ''
short_url: supervisor-calls-6-52-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v5/supervisor-calls-6-52-
template_type: Embed
title: Supervisor Calls
transcript: <p><span m="500">User-mode</span> <span m="800">programs</span> <span
  m="1100">need</span> <span m="1400">to</span> <span m="1700">communicate</span>
  <span m="2000">with</span> <span m="2300">the</span> <span m="2600">OS</span> <span
  m="2900">to</span> <span m="3200">request</span> <span m="3500">service</span> <span
  m="3800">or</span> <span m="4100">get</span> <span m="4400">access</span> <span
  m="4700">to</span> <span m="5000">useful</span> <span m="5421">OS</span> <span m="5842">data</span>
  <span m="6263">like</span> <span m="6685">the</span> <span m="7106">time</span>
  <span m="7527">of</span> <span m="7948">day.</span></p><p><span m="8370">But</span>
  <span m="8652">if</span> <span m="8934">they're</span> <span m="9217">running</span>
  <span m="9499">in</span> <span m="9782">a</span> <span m="10064">different</span>
  <span m="10347">MMU</span> <span m="10629">context</span> <span m="10911">than</span>
  <span m="11194">the</span> <span m="11476">OS,</span> <span m="11759">they</span>
  <span m="12041">don't</span> <span m="12324">have</span> <span m="12606">direct</span>
  <span m="12889">access</span> <span m="13274">to</span> <span m="13659">OS</span>
  <span m="14044">code</span> <span m="14429">and</span> <span m="14814">data.</span></p><p><span
  m="15200">And</span> <span m="15556">that</span> <span m="15913">might</span> <span
  m="16270">be</span> <span m="16627">bad</span> <span m="16984">idea</span> <span
  m="17341">in</span> <span m="17698">any</span> <span m="18055">case:</span> <span
  m="18411">the</span> <span m="18768">OS</span> <span m="19125">is</span> <span m="19482">usually</span>
  <span m="19839">responsible</span> <span m="20196">for</span> <span m="20553">implementing</span>
  <span m="20910">security</span> <span m="21246">and</span> <span m="21583">access</span>
  <span m="21920">policies</span> <span m="22257">and</span> <span m="22594">other</span>
  <span m="22931">users</span> <span m="23268">of</span> <span m="23605">the</span>
  <span m="23941">system</span> <span m="24278">would</span> <span m="24615">be</span>
  <span m="24952">upset</span> <span m="25289">if</span> <span m="25626">any</span>
  <span m="25963">random</span> <span m="26300">user</span> <span m="27095">program</span>
  <span m="27890">could</span> <span m="28685">circumvent</span> <span m="29480">those</span>
  <span m="30275">protections.</span></p><p><span m="31070">What's</span> <span m="31420">needed</span>
  <span m="31771">is</span> <span m="32122">the</span> <span m="32472">ability</span>
  <span m="32823">for</span> <span m="33174">user-mode</span> <span m="33524">programs</span>
  <span m="33875">to</span> <span m="34226">call</span> <span m="34576">OS</span>
  <span m="34927">code</span> <span m="35278">at</span> <span m="35628">specific</span>
  <span m="35979">entry</span> <span m="36330">points,</span> <span m="36866">using</span>
  <span m="37402">registers</span> <span m="37938">or</span> <span m="38474">the</span>
  <span m="39010">user-mode</span> <span m="39546">virtual</span> <span m="40083">memory</span>
  <span m="40619">to</span> <span m="41155">send</span> <span m="41691">or</span>
  <span m="42227">receive</span> <span m="42763">information.</span></p><p><span m="43300">We'd</span>
  <span m="43750">use</span> <span m="44201">these</span> <span m="44652">&quot;supervisor</span>
  <span m="45103">calls&quot;</span> <span m="45553">to</span> <span m="46004">access</span>
  <span m="46455">a</span> <span m="46906">well-documented</span> <span m="47356">and</span>
  <span m="47807">secure</span> <span m="48258">OS</span> <span m="48709">application</span>
  <span m="49160">programming</span> <span m="49556">interface</span> <span m="49953">(API).</span></p><p><span
  m="50350">An</span> <span m="50781">example</span> <span m="51213">of</span> <span
  m="51645">such</span> <span m="52077">an</span> <span m="52509">interface</span>
  <span m="52941">is</span> <span m="53373">POSIX</span> <span m="53805">(https://en.wikipedia.org/wiki/POSIX),</span>
  <span m="54236">a</span> <span m="54668">standard</span> <span m="55100">interface</span>
  <span m="55532">implemented</span> <span m="55964">by</span> <span m="56396">many</span>
  <span m="56828">Unix-like</span> <span m="57260">operating</span> <span m="58715">systems.</span></p><p><span
  m="60170">As</span> <span m="60473">it</span> <span m="60776">turns</span> <span
  m="61080">out,</span> <span m="61383">we</span> <span m="61686">have</span> <span
  m="61990">a</span> <span m="62293">way</span> <span m="62596">of</span> <span m="62900">transferring</span>
  <span m="63203">control</span> <span m="63506">from</span> <span m="63810">a</span>
  <span m="64113">user-mode</span> <span m="64416">program</span> <span m="64720">to</span>
  <span m="65023">a</span> <span m="65326">specific</span> <span m="65630">OS</span>
  <span m="66245">handler</span> <span m="66860">-</span> <span m="67475">just</span>
  <span m="68090">execute</span> <span m="68705">an</span> <span m="69320">illegal</span>
  <span m="69935">instruction!</span></p><p><span m="70550">We'll</span> <span m="70873">adopt</span>
  <span m="71196">the</span> <span m="71520">convention</span> <span m="71843">of</span>
  <span m="72166">using</span> <span m="72490">illegal</span> <span m="72813">instructions</span>
  <span m="73136">with</span> <span m="73460">an</span> <span m="73783">opcode</span>
  <span m="74106">field</span> <span m="74430">of</span> <span m="74753">1</span>
  <span m="75076">to</span> <span m="75400">serve</span> <span m="76010">as</span>
  <span m="76620">supervisor</span> <span m="77230">calls.</span></p><p><span m="77840">The</span>
  <span m="78229">low</span> <span m="78618">order</span> <span m="79008">bits</span>
  <span m="79397">of</span> <span m="79786">these</span> <span m="80176">SVC</span>
  <span m="80565">instructions</span> <span m="80954">will</span> <span m="81344">contain</span>
  <span m="81733">an</span> <span m="82122">index</span> <span m="82512">indicating</span>
  <span m="82901">which</span> <span m="83290">SVC</span> <span m="83680">service</span>
  <span m="83990">we're</span> <span m="84300">trying</span> <span m="84610">to</span>
  <span m="84920">access.</span></p><p><span m="85230">Let's</span> <span m="85893">see</span>
  <span m="86556">how</span> <span m="87220">this</span> <span m="87883">would</span>
  <span m="88546">work.</span></p><p><span m="89210">Here's</span> <span m="89872">our</span>
  <span m="90534">user-mode/kernel-mode</span> <span m="91196">diagram</span> <span
  m="91858">again.</span></p><p><span m="92520">Note</span> <span m="92910">that</span>
  <span m="93301">the</span> <span m="93692">user-mode</span> <span m="94082">programs</span>
  <span m="94473">contain</span> <span m="94864">supervisor</span> <span m="95255">calls</span>
  <span m="95645">with</span> <span m="96036">different</span> <span m="96427">indices,</span>
  <span m="96817">which</span> <span m="97208">when</span> <span m="97599">executed</span>
  <span m="97990">are</span> <span m="98595">intended</span> <span m="99201">to</span>
  <span m="99807">serve</span> <span m="100413">as</span> <span m="101019">requests</span>
  <span m="101625">for</span> <span m="102231">different</span> <span m="102837">OS</span>
  <span m="103443">services.</span></p><p><span m="104049">When</span> <span m="104420">an</span>
  <span m="104791">SVC</span> <span m="105162">instruction</span> <span m="105533">is</span>
  <span m="105905">executed,</span> <span m="106276">the</span> <span m="106647">hardware</span>
  <span m="107018">detects</span> <span m="107390">the</span> <span m="107761">opcode</span>
  <span m="108132">field</span> <span m="108503">of</span> <span m="108875">1</span>
  <span m="109246">as</span> <span m="109617">an</span> <span m="109988">illegal</span>
  <span m="110360">instruction</span> <span m="110654">and</span> <span m="110949">triggers</span>
  <span m="111244">an</span> <span m="111539">exception</span> <span m="111834">that</span>
  <span m="112129">runs</span> <span m="112424">the</span> <span m="112719">OS</span>
  <span m="113014">IllOp</span> <span m="113309">handler,</span> <span m="113604">as</span>
  <span m="113899">we</span> <span m="114194">saw</span> <span m="114489">in</span>
  <span m="114784">the</span> <span m="115079">previous</span> <span m="116174">segment.</span></p><p><span
  m="117270">The</span> <span m="117630">handler</span> <span m="117990">saves</span>
  <span m="118350">the</span> <span m="118710">process</span> <span m="119070">state</span>
  <span m="119430">in</span> <span m="119790">the</span> <span m="120150">temporary</span>
  <span m="120510">storage</span> <span m="120870">area,</span> <span m="121230">then</span>
  <span m="121590">dispatches</span> <span m="121950">to</span> <span m="122310">the</span>
  <span m="122840">appropriate</span> <span m="123370">handler</span> <span m="123900">based</span>
  <span m="124430">on</span> <span m="124960">the</span> <span m="125490">opcode</span>
  <span m="126020">field.</span></p><p><span m="126550">This</span> <span m="126926">handler</span>
  <span m="127303">can</span> <span m="127680">access</span> <span m="128056">the</span>
  <span m="128433">user's</span> <span m="128810">registers</span> <span m="129186">in</span>
  <span m="129563">the</span> <span m="129940">temporary</span> <span m="130316">storage</span>
  <span m="130693">area,</span> <span m="131070">or</span> <span m="131446">using</span>
  <span m="131823">the</span> <span m="132200">appropriate</span> <span m="132733">OS</span>
  <span m="133266">subroutines</span> <span m="133800">can</span> <span m="134333">access</span>
  <span m="134866">the</span> <span m="135400">contents</span> <span m="135933">of</span>
  <span m="136466">any</span> <span m="137000">user-mode</span> <span m="137533">virtual</span>
  <span m="138066">address.</span></p><p><span m="138600">If</span> <span m="138858">information</span>
  <span m="139116">is</span> <span m="139375">to</span> <span m="139633">be</span>
  <span m="139891">returned</span> <span m="140150">to</span> <span m="140408">the</span>
  <span m="140666">user,</span> <span m="140925">the</span> <span m="141183">return</span>
  <span m="141441">values</span> <span m="141700">can</span> <span m="141958">be</span>
  <span m="142216">stored</span> <span m="142475">in</span> <span m="142733">the</span>
  <span m="142991">temporary</span> <span m="143250">storage</span> <span m="143753">area,</span>
  <span m="144256">overwriting,</span> <span m="144760">say,</span> <span m="145263">the</span>
  <span m="145766">saved</span> <span m="146270">contents</span> <span m="146773">of</span>
  <span m="147276">the</span> <span m="147780">user's</span> <span m="148283">R0</span>
  <span m="148786">register.</span></p><p><span m="149290">Then,</span> <span m="149747">when</span>
  <span m="150204">the</span> <span m="150661">handler</span> <span m="151118">completes,</span>
  <span m="151575">the</span> <span m="152032">potentially-updated</span> <span m="152490">saved</span>
  <span m="152947">register</span> <span m="153404">values</span> <span m="153861">are</span>
  <span m="154318">reloaded</span> <span m="154775">into</span> <span m="155232">the</span>
  <span m="155690">CPU</span> <span m="156194">registers</span> <span m="156698">and</span>
  <span m="157203">execution</span> <span m="157707">of</span> <span m="158212">the</span>
  <span m="158716">user-mode</span> <span m="159221">program</span> <span m="159725">resumes</span>
  <span m="160230">at</span> <span m="160738">the</span> <span m="161247">instruction</span>
  <span m="161755">following</span> <span m="162264">the</span> <span m="162772">supervisor</span>
  <span m="163281">call.</span></p><p><span m="163790">In</span> <span m="164160">the</span>
  <span m="164531">previous</span> <span m="164901">segment</span> <span m="165272">we</span>
  <span m="165643">saw</span> <span m="166013">how</span> <span m="166384">the</span>
  <span m="166754">illegal</span> <span m="167125">instruction</span> <span m="167496">handler</span>
  <span m="167866">uses</span> <span m="168237">a</span> <span m="168607">dispatch</span>
  <span m="168978">table</span> <span m="169349">to</span> <span m="169776">choose</span>
  <span m="170203">the</span> <span m="170630">appropriate</span> <span m="171057">sub-handler</span>
  <span m="171484">depending</span> <span m="171911">on</span> <span m="172339">the</span>
  <span m="172766">opcode</span> <span m="173193">field</span> <span m="173620">of</span>
  <span m="174047">the</span> <span m="174474">illegal</span> <span m="174901">instruction.</span></p><p><span
  m="175329">In</span> <span m="175713">this</span> <span m="176097">slide</span>
  <span m="176482">we</span> <span m="176866">see</span> <span m="177251">the</span>
  <span m="177635">sub-handler</span> <span m="178020">for</span> <span m="178404">SVC</span>
  <span m="178788">instructions,</span> <span m="179173">i.e.,</span> <span m="179557">those</span>
  <span m="179942">with</span> <span m="180326">an</span> <span m="180711">opcode</span>
  <span m="181095">field</span> <span m="181480">of</span> <span m="182275">1.</span></p><p><span
  m="183070">This</span> <span m="183376">code</span> <span m="183683">uses</span>
  <span m="183990">the</span> <span m="184297">low-order</span> <span m="184604">bits</span>
  <span m="184911">of</span> <span m="185218">the</span> <span m="185525">instruction</span>
  <span m="185831">to</span> <span m="186138">access</span> <span m="186445">another</span>
  <span m="186752">dispatch</span> <span m="187059">table</span> <span m="187366">to</span>
  <span m="187673">select</span> <span m="187980">the</span> <span m="188472">appropriate</span>
  <span m="188965">code</span> <span m="189458">for</span> <span m="189951">each</span>
  <span m="190444">of</span> <span m="190937">the</span> <span m="191430">eight</span>
  <span m="191923">possible</span> <span m="192416">SVCs.</span></p><p><span m="192909">Our</span>
  <span m="193300">Tiny</span> <span m="193692">OS</span> <span m="194084">only</span>
  <span m="194476">has</span> <span m="194868">a</span> <span m="195260">meagre</span>
  <span m="195652">selection</span> <span m="196044">of</span> <span m="196436">simple</span>
  <span m="196828">services.</span></p><p><span m="197220">A</span> <span m="197673">real</span>
  <span m="198127">OS</span> <span m="198580">would</span> <span m="199034">have</span>
  <span m="199487">SVCs</span> <span m="199941">for</span> <span m="200394">accessing</span>
  <span m="200848">files,</span> <span m="201301">dealing</span> <span m="201755">with</span>
  <span m="202208">network</span> <span m="202662">connections,</span> <span m="203115">managing</span>
  <span m="203569">virtual</span> <span m="204071">memory,</span> <span m="204574">spawning</span>
  <span m="205076">new</span> <span m="205579">processes,</span> <span m="206082">and</span>
  <span m="206584">so</span> <span m="207087">on.</span></p><p><span m="207590">Here's</span>
  <span m="207974">the</span> <span m="208358">code</span> <span m="208742">for</span>
  <span m="209127">resuming</span> <span m="209511">execution</span> <span m="209895">of</span>
  <span m="210280">the</span> <span m="210664">user-mode</span> <span m="211048">process</span>
  <span m="211432">when</span> <span m="211817">the</span> <span m="212201">SVC</span>
  <span m="212585">handler</span> <span m="212970">is</span> <span m="213382">done:</span>
  <span m="213795">simply</span> <span m="214208">restore</span> <span m="214621">the</span>
  <span m="215034">saved</span> <span m="215447">values</span> <span m="215860">for</span>
  <span m="216273">the</span> <span m="216686">registers</span> <span m="217099">and</span>
  <span m="217661">JMP</span> <span m="218224">to</span> <span m="218786">resume</span>
  <span m="219349">execution</span> <span m="219911">at</span> <span m="220474">the</span>
  <span m="221036">instruction</span> <span m="221599">following</span> <span m="222161">the</span>
  <span m="222724">SVC</span> <span m="223286">instruction.</span></p><p><span m="223849">There</span>
  <span m="224190">are</span> <span m="224531">times</span> <span m="224872">when</span>
  <span m="225214">for</span> <span m="225555">some</span> <span m="225896">reason</span>
  <span m="226238">the</span> <span m="226579">SVC</span> <span m="226920">request</span>
  <span m="227262">cannot</span> <span m="227603">be</span> <span m="227944">completed</span>
  <span m="228286">and</span> <span m="228627">the</span> <span m="228968">request</span>
  <span m="229310">should</span> <span m="229708">be</span> <span m="230106">retried</span>
  <span m="230505">in</span> <span m="230903">the</span> <span m="231301">future.</span></p><p><span
  m="231700">For</span> <span m="232092">example,</span> <span m="232484">the</span>
  <span m="232877">ReadCh</span> <span m="233269">SVC</span> <span m="233661">returns</span>
  <span m="234054">the</span> <span m="234446">next</span> <span m="234838">character</span>
  <span m="235231">typed</span> <span m="235623">by</span> <span m="236015">the</span>
  <span m="236408">user,</span> <span m="236800">but</span> <span m="237192">if</span>
  <span m="237585">no</span> <span m="237977">character</span> <span m="238370">has</span>
  <span m="238730">yet</span> <span m="239090">been</span> <span m="239450">typed,</span>
  <span m="239810">the</span> <span m="240170">OS</span> <span m="240530">cannot</span>
  <span m="240890">complete</span> <span m="241250">the</span> <span m="241610">request</span>
  <span m="241970">at</span> <span m="242330">this</span> <span m="242690">time.</span></p><p><span
  m="243050">In</span> <span m="243481">this</span> <span m="243912">case,</span>
  <span m="244343">the</span> <span m="244775">SVC</span> <span m="245206">handler</span>
  <span m="245637">should</span> <span m="246069">branch</span> <span m="246500">to</span>
  <span m="246931">I_Wait,</span> <span m="247363">which</span> <span m="247794">arranges</span>
  <span m="248225">for</span> <span m="248657">the</span> <span m="249088">SVC</span>
  <span m="249519">instruction</span> <span m="249951">to</span> <span m="250319">be</span>
  <span m="250688">re-executed</span> <span m="251056">next</span> <span m="251425">time</span>
  <span m="251794">this</span> <span m="252162">process</span> <span m="252531">runs</span>
  <span m="252900">and</span> <span m="253268">then</span> <span m="253637">calls</span>
  <span m="254005">Scheduler()</span> <span m="254374">to</span> <span m="254743">run</span>
  <span m="255111">the</span> <span m="255480">next</span> <span m="255849">process.</span></p><p><span
  m="257279">This</span> <span m="257578">gives</span> <span m="257877">all</span>
  <span m="258177">the</span> <span m="258476">other</span> <span m="258776">processes</span>
  <span m="259075">a</span> <span m="259375">chance</span> <span m="259674">to</span>
  <span m="259974">run</span> <span m="260273">before</span> <span m="260573">the</span>
  <span m="260872">SVC</span> <span m="261172">is</span> <span m="261471">tried</span>
  <span m="261771">again,</span> <span m="262070">hopefully</span> <span m="262370">this</span>
  <span m="263423">time</span> <span m="264476">successfully.</span></p><p><span m="265530">You</span>
  <span m="265859">can</span> <span m="266188">see</span> <span m="266518">that</span>
  <span m="266847">this</span> <span m="267176">code</span> <span m="267506">also</span>
  <span m="267835">serves</span> <span m="268164">as</span> <span m="268494">the</span>
  <span m="268823">implementation</span> <span m="269152">for</span> <span m="269482">two</span>
  <span m="269811">different</span> <span m="270140">SVCs!</span></p><p><span m="270470">A</span>
  <span m="270828">process</span> <span m="271187">can</span> <span m="271546">give</span>
  <span m="271905">up</span> <span m="272263">the</span> <span m="272622">remainder</span>
  <span m="272981">of</span> <span m="273340">its</span> <span m="273698">current</span>
  <span m="274057">execution</span> <span m="274416">time</span> <span m="274775">slice</span>
  <span m="275133">by</span> <span m="275492">calling</span> <span m="275851">the</span>
  <span m="276210">Yield()</span> <span m="277530">SVC.</span></p><p><span m="278850">This</span>
  <span m="279245">simply</span> <span m="279640">causes</span> <span m="280035">the</span>
  <span m="280430">OS</span> <span m="280825">to</span> <span m="281220">call</span>
  <span m="281615">Scheduler(),</span> <span m="282010">suspending</span> <span m="282405">execution</span>
  <span m="282800">of</span> <span m="283195">the</span> <span m="283590">current</span>
  <span m="283985">process</span> <span m="284380">until</span> <span m="285001">its</span>
  <span m="285622">next</span> <span m="286243">turn</span> <span m="286864">in</span>
  <span m="287485">the</span> <span m="288106">round-robin</span> <span m="288727">scheduling</span>
  <span m="289348">process.</span></p><p><span m="289970">And</span> <span m="290390">to</span>
  <span m="290810">stop</span> <span m="291230">execution,</span> <span m="291650">a</span>
  <span m="292070">process</span> <span m="292490">can</span> <span m="292910">call</span>
  <span m="293330">the</span> <span m="293750">Halt()</span> <span m="294170">SVC.</span></p><p><span
  m="294590">Looking</span> <span m="294909">at</span> <span m="295228">the</span>
  <span m="295547">implementation,</span> <span m="295867">we</span> <span m="296186">can</span>
  <span m="296505">see</span> <span m="296825">that</span> <span m="297144">&quot;halt&quot;</span>
  <span m="297463">is</span> <span m="297782">a</span> <span m="298102">bit</span>
  <span m="298421">of</span> <span m="298740">misnomer.</span></p><p><span m="299060">What</span>
  <span m="299415">really</span> <span m="299771">happens</span> <span m="300126">is</span>
  <span m="300482">that</span> <span m="300838">the</span> <span m="301193">system</span>
  <span m="301549">arranges</span> <span m="301905">to</span> <span m="302260">re-execute</span>
  <span m="302616">the</span> <span m="302971">Halt()</span> <span m="303327">SVC</span>
  <span m="303683">each</span> <span m="304038">time</span> <span m="304394">the</span>
  <span m="304750">process</span> <span m="305168">is</span> <span m="305587">scheduled,</span>
  <span m="306006">which</span> <span m="306424">then</span> <span m="306843">causes</span>
  <span m="307262">the</span> <span m="307680">OS</span> <span m="308099">to</span>
  <span m="308518">schedule</span> <span m="308936">the</span> <span m="309355">next</span>
  <span m="309774">process</span> <span m="310192">for</span> <span m="310611">execution.</span></p><p><span
  m="311030">The</span> <span m="311444">process</span> <span m="311859">appears</span>
  <span m="312274">to</span> <span m="312688">halt</span> <span m="313103">since</span>
  <span m="313518">the</span> <span m="313932">instruction</span> <span m="314347">following</span>
  <span m="314762">the</span> <span m="315176">Halt()</span> <span m="315591">SVC</span>
  <span m="316006">is</span> <span m="316420">never</span> <span m="316835">executed.</span></p><p><span
  m="317250">Adding</span> <span m="317846">new</span> <span m="318443">SVC</span>
  <span m="319040">handlers</span> <span m="319636">is</span> <span m="320233">straightforward.</span></p><p><span
  m="320830">First</span> <span m="321223">we</span> <span m="321616">need</span>
  <span m="322009">to</span> <span m="322402">define</span> <span m="322795">new</span>
  <span m="323188">SVC</span> <span m="323581">macros</span> <span m="323974">for</span>
  <span m="324367">use</span> <span m="324760">in</span> <span m="325153">user-mode</span>
  <span m="325546">programs.</span></p><p><span m="325940">In</span> <span m="326380">this</span>
  <span m="326821">example,</span> <span m="327262">we're</span> <span m="327702">defining</span>
  <span m="328143">SVCs</span> <span m="328584">for</span> <span m="329025">getting</span>
  <span m="329465">and</span> <span m="329906">setting</span> <span m="330347">the</span>
  <span m="330787">time</span> <span m="331228">of</span> <span m="331669">day.</span></p><p><span
  m="332110">Since</span> <span m="332391">these</span> <span m="332673">are</span>
  <span m="332955">the</span> <span m="333237">eighth</span> <span m="333518">and</span>
  <span m="333800">ninth</span> <span m="334082">SVCs,</span> <span m="334364">we</span>
  <span m="334645">need</span> <span m="334927">to</span> <span m="335209">make</span>
  <span m="335491">a</span> <span m="335772">small</span> <span m="336054">adjustment</span>
  <span m="336336">to</span> <span m="336618">the</span> <span m="336900">SVC</span>
  <span m="337261">dispatch</span> <span m="337623">code</span> <span m="337985">and</span>
  <span m="338347">then</span> <span m="338709">add</span> <span m="339071">the</span>
  <span m="339433">appropriate</span> <span m="339795">entries</span> <span m="340156">to</span>
  <span m="340518">the</span> <span m="340880">end</span> <span m="341242">of</span>
  <span m="341604">the</span> <span m="341966">dispatch</span> <span m="342328">table.</span></p><p><span
  m="342690">The</span> <span m="343155">code</span> <span m="343621">for</span> <span
  m="344086">the</span> <span m="344552">new</span> <span m="345017">handlers</span>
  <span m="345483">is</span> <span m="345948">equally</span> <span m="346414">straightforward.</span></p><p><span
  m="346880">The</span> <span m="347181">handler</span> <span m="347482">can</span>
  <span m="347783">access</span> <span m="348084">the</span> <span m="348385">value</span>
  <span m="348686">of</span> <span m="348987">the</span> <span m="349288">program's</span>
  <span m="349590">R0</span> <span m="349891">by</span> <span m="350192">looking</span>
  <span m="350493">at</span> <span m="350794">the</span> <span m="351095">correct</span>
  <span m="351396">entry</span> <span m="351697">in</span> <span m="351998">the</span>
  <span m="352300">UserMState</span> <span m="353152">temporary</span> <span m="354005">holding</span>
  <span m="354857">area.</span></p><p><span m="355710">It</span> <span m="356250">just</span>
  <span m="356791">takes</span> <span m="357332">a</span> <span m="357873">few</span>
  <span m="358414">instructions</span> <span m="358955">to</span> <span m="359496">implement</span>
  <span m="360037">the</span> <span m="360578">desired</span> <span m="361119">operations.</span></p><p><span
  m="361660">The</span> <span m="362154">SVC</span> <span m="362649">mechanism</span>
  <span m="363143">provides</span> <span m="363638">controlled</span> <span m="364132">access</span>
  <span m="364627">to</span> <span m="365121">OS</span> <span m="365616">services</span>
  <span m="366110">and</span> <span m="366605">data.</span></p><p><span m="367100">As</span>
  <span m="367432">we'll</span> <span m="367765">see</span> <span m="368098">in</span>
  <span m="368431">a</span> <span m="368764">few</span> <span m="369097">lectures,</span>
  <span m="369430">it'll</span> <span m="369763">be</span> <span m="370095">useful</span>
  <span m="370428">that</span> <span m="370761">SVC</span> <span m="371094">handlers</span>
  <span m="371427">can't</span> <span m="371760">be</span> <span m="372093">interrupted</span>
  <span m="372426">since</span> <span m="372759">they</span> <span m="373194">are</span>
  <span m="373629">running</span> <span m="374064">in</span> <span m="374499">supervisor</span>
  <span m="374934">mode</span> <span m="375369">where</span> <span m="375804">interrupts</span>
  <span m="376239">are</span> <span m="376674">disabled.</span></p><p><span m="377110">So,</span>
  <span m="377530">for</span> <span m="377951">example,</span> <span m="378371">if</span>
  <span m="378792">we</span> <span m="379212">need</span> <span m="379633">to</span>
  <span m="380053">increment</span> <span m="380474">a</span> <span m="380894">value</span>
  <span m="381315">in</span> <span m="381735">main</span> <span m="382156">memory,</span>
  <span m="382576">using</span> <span m="382997">a</span> <span m="383417">LD/ADDC/ST</span>
  <span m="383838">sequence,</span> <span m="384259">but</span> <span m="384601">we</span>
  <span m="384944">want</span> <span m="385286">to</span> <span m="385629">ensure</span>
  <span m="385971">no</span> <span m="386314">other</span> <span m="386656">process</span>
  <span m="386999">execution</span> <span m="387342">intervenes</span> <span m="387684">between</span>
  <span m="388027">the</span> <span m="388369">LD</span> <span m="388712">and</span>
  <span m="389054">the</span> <span m="389397">ST,</span> <span m="389740">we</span>
  <span m="390266">can</span> <span m="390793">encapsulate</span> <span m="391320">the</span>
  <span m="391846">required</span> <span m="392373">functionality</span> <span m="392900">as</span>
  <span m="393426">an</span> <span m="393953">SVC,</span> <span m="394480">which</span>
  <span m="395006">is</span> <span m="395533">guaranteed</span> <span m="396060">to</span>
  <span m="396586">be</span> <span m="397113">uninterruptible.</span></p><p><span
  m="397640">We've</span> <span m="397986">made</span> <span m="398332">an</span>
  <span m="398678">excellent</span> <span m="399024">start</span> <span m="399370">at</span>
  <span m="399716">exploring</span> <span m="400062">the</span> <span m="400408">implementation</span>
  <span m="400754">of</span> <span m="401100">a</span> <span m="401446">simple</span>
  <span m="401792">time-shared</span> <span m="402139">operating</span> <span m="402954">system.</span></p><p><span
  m="403770">We'll</span> <span m="404078">continue</span> <span m="404386">the</span>
  <span m="404694">exploration</span> <span m="405002">in</span> <span m="405310">the</span>
  <span m="405618">next</span> <span m="405926">lecture</span> <span m="406234">when</span>
  <span m="406542">we</span> <span m="406850">see</span> <span m="407158">how</span>
  <span m="407466">the</span> <span m="407774">OS</span> <span m="408082">deals</span>
  <span m="408390">with</span> <span m="408699">external</span> <span m="409419">input/output</span>
  <span m="410139">devices.</span></p>
type: course
uid: 7412dbd42c7dce016bb43260a32974cb

---
None