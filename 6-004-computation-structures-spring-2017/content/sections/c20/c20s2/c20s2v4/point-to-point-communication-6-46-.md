---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: B7F6vh_plHw
  parent_uid: 42d699f37ed53bc7a722031bc07a88bc
  title: Video-YouTube-Stream
  type: Video
  uid: 377bdb114600e625ed5ea0ad9fc38267
- id: 3Play-3Play YouTube id-Stream
  media_location: B7F6vh_plHw
  parent_uid: 42d699f37ed53bc7a722031bc07a88bc
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 1dfb9ccba5f134b3e24de22c1479627f
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/B7F6vh_plHw/default.jpg
  parent_uid: 42d699f37ed53bc7a722031bc07a88bc
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: d49aa27edbd7737507a21b86126eca6d
- id: B7F6vh_plHw.srt
  parent_uid: 42d699f37ed53bc7a722031bc07a88bc
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c20/c20s2/c20s2v4/point-to-point-communication-6-46-/B7F6vh_plHw.srt
  title: 3play caption file
  type: null
  uid: 2a744b62687a233b2b0a9f87ed309623
- id: B7F6vh_plHw.pdf
  parent_uid: 42d699f37ed53bc7a722031bc07a88bc
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c20/c20s2/c20s2v4/point-to-point-communication-6-46-/B7F6vh_plHw.pdf
  title: 3play pdf file
  type: null
  uid: c315b9998c28905c4e4dfe0f767b2bff
- id: Caption-3Play YouTube id-SRT
  parent_uid: 42d699f37ed53bc7a722031bc07a88bc
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: f1c53d12ce0e46e54f40067845937f23
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 42d699f37ed53bc7a722031bc07a88bc
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 041da71c17dce7af59df7a646cd1579c
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_20-02-04_300k.mp4
  parent_uid: 42d699f37ed53bc7a722031bc07a88bc
  title: Video-Internet Archive-MP4
  type: Video
  uid: b0067ee6c7f9314f8adc3f12a576386e
inline_embed_id: 31965647pointtopointcommunication64678950396
layout: video
order_index: null
parent_uid: ac4ebd627466d313e4032b6eb0fa25ff
related_resources_text: ''
short_url: point-to-point-communication-6-46-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c20/c20s2/c20s2v4/point-to-point-communication-6-46-
template_type: Embed
title: Point-to-point Communication
transcript: <p><span m="1040">Network</span> <span m="1461">technologies</span> <span
  m="1883">were</span> <span m="2305">developed</span> <span m="2726">to</span> <span
  m="3148">connect</span> <span m="3570">components</span> <span m="3991">(in</span>
  <span m="4413">this</span> <span m="4835">case</span> <span m="5256">individual</span>
  <span m="5678">computer</span> <span m="6100">systems)</span> <span m="6689">separated</span>
  <span m="7279">by</span> <span m="7869">larger</span> <span m="8459">distances,</span>
  <span m="9049">i.e.,</span> <span m="9639">distances</span> <span m="10229">measured</span>
  <span m="10819">in</span> <span m="11409">meters</span> <span m="11999">instead</span>
  <span m="12589">of</span> <span m="13179">centimeters.</span></p><p><span m="13769">Communicating</span>
  <span m="14157">over</span> <span m="14545">these</span> <span m="14933">larger</span>
  <span m="15321">distances</span> <span m="15709">led</span> <span m="16097">to</span>
  <span m="16485">different</span> <span m="16873">design</span> <span m="17261">tradeoffs.</span></p><p><span
  m="17650">In</span> <span m="18008">early</span> <span m="18366">networks,</span>
  <span m="18724">information</span> <span m="19082">was</span> <span m="19440">sent</span>
  <span m="19798">as</span> <span m="20156">a</span> <span m="20514">sequence</span>
  <span m="20872">of</span> <span m="21230">bits</span> <span m="21588">over</span>
  <span m="21946">the</span> <span m="22304">shared</span> <span m="22662">communication</span>
  <span m="23020">medium.</span></p><p><span m="24020">The</span> <span m="24400">bits</span>
  <span m="24780">were</span> <span m="25160">organized</span> <span m="25540">into</span>
  <span m="25920">packets,</span> <span m="26300">each</span> <span m="26680">containing</span>
  <span m="27060">the</span> <span m="27440">address</span> <span m="27820">of</span>
  <span m="28200">the</span> <span m="28580">destination.</span></p><p><span m="28960">Packets</span>
  <span m="29330">also</span> <span m="29701">included</span> <span m="30072">a</span>
  <span m="30442">checksum</span> <span m="30813">used</span> <span m="31184">to</span>
  <span m="31554">detect</span> <span m="31925">errors</span> <span m="32296">in</span>
  <span m="32666">transmission</span> <span m="33037">and</span> <span m="33408">the</span>
  <span m="33778">protocol</span> <span m="34149">supported</span> <span m="34520">the</span>
  <span m="35075">ability</span> <span m="35631">to</span> <span m="36186">request</span>
  <span m="36742">the</span> <span m="37297">retransmission</span> <span m="37853">of</span>
  <span m="38408">corrupted</span> <span m="38964">packets.</span></p><p><span m="39520">The</span>
  <span m="39877">software</span> <span m="40234">controlling</span> <span m="40591">the</span>
  <span m="40948">network</span> <span m="41305">is</span> <span m="41662">divided</span>
  <span m="42020">into</span> <span m="42377">a</span> <span m="42734">&quot;stack&quot;</span>
  <span m="43091">of</span> <span m="43448">modules,</span> <span m="43805">each</span>
  <span m="44162">implementing</span> <span m="44520">a</span> <span m="45222">different</span>
  <span m="45925">communication</span> <span m="46627">abstraction.</span></p><p><span
  m="47330">The</span> <span m="47740">lowest-level</span> <span m="48150">physical</span>
  <span m="48560">layer</span> <span m="48970">is</span> <span m="49380">responsible</span>
  <span m="49790">for</span> <span m="50200">transmitting</span> <span m="50610">and</span>
  <span m="51020">receiving</span> <span m="51430">an</span> <span m="51840">individual</span>
  <span m="52250">packet</span> <span m="52966">of</span> <span m="53683">bits.</span></p><p><span
  m="54400">Bit</span> <span m="54840">errors</span> <span m="55281">are</span> <span
  m="55722">detected</span> <span m="56163">and</span> <span m="56603">corrected,</span>
  <span m="57044">and</span> <span m="57485">packets</span> <span m="57926">with</span>
  <span m="58366">uncorrectable</span> <span m="58807">errors</span> <span m="59248">are</span>
  <span m="59689">discarded.</span></p><p><span m="60130">There</span> <span m="60520">are</span>
  <span m="60911">different</span> <span m="61302">physical-layer</span> <span m="61693">modules</span>
  <span m="62083">available</span> <span m="62474">for</span> <span m="62865">the</span>
  <span m="63256">different</span> <span m="63646">types</span> <span m="64037">of</span>
  <span m="64428">physical</span> <span m="64819">networks.</span></p><p><span m="66350">The</span>
  <span m="66726">network</span> <span m="67102">layer</span> <span m="67479">deals</span>
  <span m="67855">with</span> <span m="68231">the</span> <span m="68608">addressing</span>
  <span m="68984">and</span> <span m="69360">routing</span> <span m="69737">of</span>
  <span m="70113">packets.</span></p><p><span m="70490">Clever</span> <span m="70889">routing</span>
  <span m="71288">algorithms</span> <span m="71687">find</span> <span m="72086">the</span>
  <span m="72485">shortest</span> <span m="72885">communication</span> <span m="73284">path</span>
  <span m="73683">through</span> <span m="74082">the</span> <span m="74481">multi-hop</span>
  <span m="74880">network</span> <span m="75280">and</span> <span m="75778">deal</span>
  <span m="76276">with</span> <span m="76774">momentary</span> <span m="77272">or</span>
  <span m="77770">long-term</span> <span m="78269">outages</span> <span m="78767">on</span>
  <span m="79265">particular</span> <span m="79763">network</span> <span m="80261">links.</span></p><p><span
  m="80760">The</span> <span m="81089">transport</span> <span m="81418">layer</span>
  <span m="81747">is</span> <span m="82077">responsible</span> <span m="82406">for</span>
  <span m="82735">providing</span> <span m="83065">the</span> <span m="83394">reliable</span>
  <span m="83723">communication</span> <span m="84052">of</span> <span m="84382">a</span>
  <span m="84711">stream</span> <span m="85040">of</span> <span m="85370">data,</span>
  <span m="85872">dealing</span> <span m="86374">with</span> <span m="86876">the</span>
  <span m="87378">issues</span> <span m="87880">of</span> <span m="88382">discarded</span>
  <span m="88884">or</span> <span m="89386">out-of-order</span> <span m="89888">packets.</span></p><p><span
  m="90390">In</span> <span m="90786">an</span> <span m="91182">effort</span> <span
  m="91578">to</span> <span m="91974">optimize</span> <span m="92370">network</span>
  <span m="92766">usage</span> <span m="93162">and</span> <span m="93558">limit</span>
  <span m="93954">packet</span> <span m="94350">loses</span> <span m="94746">due</span>
  <span m="95142">to</span> <span m="95538">network</span> <span m="95934">congestion,</span>
  <span m="96330">the</span> <span m="96708">transport</span> <span m="97086">layer</span>
  <span m="97464">deals</span> <span m="97842">with</span> <span m="98220">flow</span>
  <span m="98598">control,</span> <span m="98976">i.e.,</span> <span m="99354">the</span>
  <span m="99732">rate</span> <span m="100110">at</span> <span m="100488">which</span>
  <span m="100866">packets</span> <span m="101244">are</span> <span m="101622">sent.</span></p><p><span
  m="102000">A</span> <span m="102372">key</span> <span m="102745">idea</span> <span
  m="103118">in</span> <span m="103490">the</span> <span m="103863">networking</span>
  <span m="104236">community</span> <span m="104608">is</span> <span m="104981">the</span>
  <span m="105354">notion</span> <span m="105726">of</span> <span m="106099">building</span>
  <span m="106472">a</span> <span m="106844">reliable</span> <span m="107217">communication</span>
  <span m="107590">channel</span> <span m="108049">on</span> <span m="108509">top</span>
  <span m="108969">of</span> <span m="109429">a</span> <span m="109889">&quot;best</span>
  <span m="110349">efforts&quot;</span> <span m="110809">packet</span> <span m="111269">network.</span></p><p><span
  m="111729">Higher</span> <span m="112009">layers</span> <span m="112290">of</span>
  <span m="112571">the</span> <span m="112851">protocol</span> <span m="113132">are</span>
  <span m="113413">designed</span> <span m="113693">so</span> <span m="113974">that</span>
  <span m="114255">its</span> <span m="114535">possible</span> <span m="114816">to</span>
  <span m="115097">recover</span> <span m="115377">from</span> <span m="115658">errors</span>
  <span m="115939">in</span> <span m="116274">the</span> <span m="116609">lower</span>
  <span m="116944">layers.</span></p><p><span m="117280">This</span> <span m="117707">has</span>
  <span m="118134">proven</span> <span m="118562">to</span> <span m="118989">be</span>
  <span m="119417">much</span> <span m="119844">more</span> <span m="120272">cost-effective</span>
  <span m="120699">and</span> <span m="121126">robust</span> <span m="121554">than</span>
  <span m="121981">trying</span> <span m="122409">to</span> <span m="122836">achieve</span>
  <span m="123264">100%</span> <span m="123691">reliability</span> <span m="124119">at</span>
  <span m="124879">each</span> <span m="125639">layer.</span></p><p><span m="126400">As</span>
  <span m="126658">we</span> <span m="126917">saw</span> <span m="127176">in</span>
  <span m="127435">the</span> <span m="127693">previous</span> <span m="127952">section,</span>
  <span m="128211">there</span> <span m="128470">are</span> <span m="128728">a</span>
  <span m="128987">lot</span> <span m="129246">of</span> <span m="129505">electrical</span>
  <span m="129763">issues</span> <span m="130022">when</span> <span m="130281">trying</span>
  <span m="130540">to</span> <span m="130799">communicate</span> <span m="131295">over</span>
  <span m="131791">a</span> <span m="132287">shared</span> <span m="132783">wire</span>
  <span m="133279">with</span> <span m="133775">multiple</span> <span m="134271">drivers</span>
  <span m="134767">and</span> <span m="135263">receivers.</span></p><p><span m="135760">Slowing</span>
  <span m="136122">down</span> <span m="136485">the</span> <span m="136848">rate</span>
  <span m="137210">of</span> <span m="137573">communication</span> <span m="137936">helps</span>
  <span m="138298">to</span> <span m="138661">solve</span> <span m="139024">the</span>
  <span m="139386">problems,</span> <span m="139749">but</span> <span m="140112">&quot;slow&quot;</span>
  <span m="140474">isn't</span> <span m="140837">in</span> <span m="141200">the</span>
  <span m="141938">cards</span> <span m="142676">for</span> <span m="143414">today's</span>
  <span m="144152">high-performance</span> <span m="144890">systems.</span></p><p><span
  m="145629">Experience</span> <span m="145976">in</span> <span m="146323">the</span>
  <span m="146670">network</span> <span m="147017">world</span> <span m="147364">has</span>
  <span m="147711">shown</span> <span m="148059">that</span> <span m="148406">the</span>
  <span m="148753">fastest</span> <span m="149100">and</span> <span m="149447">least</span>
  <span m="149794">problematic</span> <span m="150141">communication</span> <span
  m="150489">channels</span> <span m="150923">have</span> <span m="151357">a</span>
  <span m="151791">single</span> <span m="152226">driver</span> <span m="152660">communicating</span>
  <span m="153094">with</span> <span m="153529">a</span> <span m="153963">single</span>
  <span m="154397">receiver,</span> <span m="154831">what's</span> <span m="155266">called</span>
  <span m="155700">a</span> <span m="156134">point-to-point</span> <span m="156569">link.</span></p><p><span
  m="157790">Using</span> <span m="158331">differential</span> <span m="158873">signaling</span>
  <span m="159415">is</span> <span m="159956">particularly</span> <span m="160498">robust.</span></p><p><span
  m="161040">With</span> <span m="161376">differential</span> <span m="161712">signaling,</span>
  <span m="162048">the</span> <span m="162385">receiver</span> <span m="162721">measures</span>
  <span m="163057">the</span> <span m="163393">voltage</span> <span m="163730">difference</span>
  <span m="164066">across</span> <span m="164402">the</span> <span m="164739">two</span>
  <span m="165496">signaling</span> <span m="166253">wires.</span></p><p><span m="167010">Electrical</span>
  <span m="167297">effects</span> <span m="167584">that</span> <span m="167871">might</span>
  <span m="168158">induce</span> <span m="168445">voltage</span> <span m="168732">noise</span>
  <span m="169019">on</span> <span m="169306">one</span> <span m="169593">signaling</span>
  <span m="169880">wire</span> <span m="170167">will</span> <span m="170454">affect</span>
  <span m="170741">the</span> <span m="171029">other</span> <span m="171490">in</span>
  <span m="171951">equal</span> <span m="172413">measure,</span> <span m="172874">so</span>
  <span m="173336">the</span> <span m="173797">voltage</span> <span m="174258">difference</span>
  <span m="174720">will</span> <span m="175181">be</span> <span m="175643">largely</span>
  <span m="176104">unaffected</span> <span m="176565">by</span> <span m="177027">most</span>
  <span m="177488">noise.</span></p><p><span m="177950">Almost</span> <span m="178533">all</span>
  <span m="179117">high-performance</span> <span m="179701">communication</span> <span
  m="180285">links</span> <span m="180868">use</span> <span m="181452">differential</span>
  <span m="182036">signaling.</span></p><p><span m="182620">If</span> <span m="182902">we're</span>
  <span m="183184">sending</span> <span m="183466">digital</span> <span m="183749">data,</span>
  <span m="184031">does</span> <span m="184313">that</span> <span m="184596">mean</span>
  <span m="184878">we</span> <span m="185160">also</span> <span m="185442">have</span>
  <span m="185725">to</span> <span m="186007">send</span> <span m="186289">a</span>
  <span m="186572">separate</span> <span m="186854">clock</span> <span m="187136">signal</span>
  <span m="187419">so</span> <span m="187795">the</span> <span m="188171">receiver</span>
  <span m="188548">knows</span> <span m="188924">when</span> <span m="189301">to</span>
  <span m="189677">sample</span> <span m="190054">the</span> <span m="190430">signal</span>
  <span m="190806">to</span> <span m="191183">determine</span> <span m="191559">the</span>
  <span m="191936">next</span> <span m="192312">bit?</span></p><p><span m="192689">With</span>
  <span m="192935">some</span> <span m="193181">cleverness,</span> <span m="193427">it</span>
  <span m="193673">turns</span> <span m="193919">out</span> <span m="194165">that</span>
  <span m="194411">we</span> <span m="194657">can</span> <span m="194903">recover</span>
  <span m="195149">the</span> <span m="195395">timing</span> <span m="195641">information</span>
  <span m="195887">from</span> <span m="196133">the</span> <span m="196379">received</span>
  <span m="196806">signal</span> <span m="197234">assuming</span> <span m="197661">we</span>
  <span m="198089">know</span> <span m="198516">the</span> <span m="198944">nominal</span>
  <span m="199372">clock</span> <span m="199799">period</span> <span m="200227">at</span>
  <span m="200654">the</span> <span m="201082">transmitter.</span></p><p><span m="201510">If</span>
  <span m="201783">the</span> <span m="202056">transmitter</span> <span m="202329">changes</span>
  <span m="202602">the</span> <span m="202875">bit</span> <span m="203148">its</span>
  <span m="203421">sending</span> <span m="203694">at</span> <span m="203967">the</span>
  <span m="204240">rising</span> <span m="204513">edge</span> <span m="204786">of</span>
  <span m="205059">the</span> <span m="205332">transmitter's</span> <span m="205605">clock,</span>
  <span m="205879">then</span> <span m="206205">the</span> <span m="206531">receiver</span>
  <span m="206857">can</span> <span m="207183">use</span> <span m="207509">the</span>
  <span m="207835">transitions</span> <span m="208161">in</span> <span m="208487">the</span>
  <span m="208813">received</span> <span m="209139">waveform</span> <span m="209465">to</span>
  <span m="209791">infer</span> <span m="210117">the</span> <span m="210443">timing</span>
  <span m="210769">for</span> <span m="211164">some</span> <span m="211559">of</span>
  <span m="211954">the</span> <span m="212349">clock</span> <span m="212744">edges.</span></p><p><span
  m="213139">Then</span> <span m="213413">the</span> <span m="213687">receiver</span>
  <span m="213962">can</span> <span m="214236">use</span> <span m="214510">its</span>
  <span m="214785">knowledge</span> <span m="215059">of</span> <span m="215333">the</span>
  <span m="215608">transmitter's</span> <span m="215882">nominal</span> <span m="216156">clock</span>
  <span m="216431">period</span> <span m="216705">to</span> <span m="216980">infer</span>
  <span m="217443">the</span> <span m="217907">location</span> <span m="218370">of</span>
  <span m="218834">the</span> <span m="219298">remaining</span> <span m="219761">clock</span>
  <span m="220225">edges.</span></p><p><span m="220689">It</span> <span m="221010">does</span>
  <span m="221331">this</span> <span m="221652">by</span> <span m="221974">using</span>
  <span m="222295">a</span> <span m="222616">phase-locked</span> <span m="222937">loop</span>
  <span m="223259">to</span> <span m="223580">generate</span> <span m="223901">a</span>
  <span m="224222">local</span> <span m="224544">facsimile</span> <span m="224865">of</span>
  <span m="225186">the</span> <span m="225507">transmitter's</span> <span m="225829">clock,</span>
  <span m="226265">using</span> <span m="226702">any</span> <span m="227139">received</span>
  <span m="227575">transitions</span> <span m="228012">to</span> <span m="228449">correct</span>
  <span m="228885">the</span> <span m="229322">phase</span> <span m="229759">and</span>
  <span m="230195">period</span> <span m="230632">of</span> <span m="231069">the</span>
  <span m="231505">local</span> <span m="231942">clock.</span></p><p><span m="232379">The</span>
  <span m="232644">transmitter</span> <span m="232910">adds</span> <span m="233175">a</span>
  <span m="233441">training</span> <span m="233707">sequence</span> <span m="233972">of</span>
  <span m="234238">bits</span> <span m="234504">at</span> <span m="234769">the</span>
  <span m="235035">front</span> <span m="235300">of</span> <span m="235566">packet</span>
  <span m="235832">to</span> <span m="236097">ensure</span> <span m="236363">that</span>
  <span m="236629">the</span> <span m="237044">receiver's</span> <span m="237460">phased-lock</span>
  <span m="237876">loop</span> <span m="238292">is</span> <span m="238708">properly</span>
  <span m="239124">synchronized</span> <span m="239540">before</span> <span m="239956">the</span>
  <span m="240372">packet</span> <span m="240788">data</span> <span m="241204">itself</span>
  <span m="241620">is</span> <span m="242330">transmitted.</span></p><p><span m="243040">A</span>
  <span m="243381">unique</span> <span m="243722">bit</span> <span m="244063">sequence</span>
  <span m="244404">is</span> <span m="244745">used</span> <span m="245087">to</span>
  <span m="245428">separate</span> <span m="245769">the</span> <span m="246110">training</span>
  <span m="246451">signal</span> <span m="246793">from</span> <span m="247134">the</span>
  <span m="247475">packet</span> <span m="247816">data</span> <span m="248157">so</span>
  <span m="248499">the</span> <span m="248866">receiver</span> <span m="249234">can</span>
  <span m="249602">tell</span> <span m="249970">exactly</span> <span m="250337">where</span>
  <span m="250705">the</span> <span m="251073">packet</span> <span m="251441">starts</span>
  <span m="251809">even</span> <span m="252111">if</span> <span m="252413">it</span>
  <span m="252715">missed</span> <span m="253017">a</span> <span m="253319">few</span>
  <span m="253621">training</span> <span m="253923">bits</span> <span m="254225">while</span>
  <span m="254527">the</span> <span m="254829">clocks</span> <span m="255131">were</span>
  <span m="255433">being</span> <span m="255735">properly</span> <span m="256037">synchronized.</span></p><p><span
  m="256339">Once</span> <span m="256624">the</span> <span m="256909">receiver</span>
  <span m="257194">knows</span> <span m="257479">the</span> <span m="257764">timing</span>
  <span m="258049">of</span> <span m="258334">the</span> <span m="258619">clock</span>
  <span m="258904">edges,</span> <span m="259189">it</span> <span m="259474">can</span>
  <span m="259759">then</span> <span m="260044">sample</span> <span m="260329">the</span>
  <span m="260614">incoming</span> <span m="260899">waveform</span> <span m="261371">towards</span>
  <span m="261843">the</span> <span m="262316">end</span> <span m="262788">of</span>
  <span m="263260">each</span> <span m="263733">clock</span> <span m="264205">period</span>
  <span m="264678">to</span> <span m="265150">determine</span> <span m="265622">the</span>
  <span m="266095">transmitted</span> <span m="266567">bit.</span></p><p><span m="267040">To</span>
  <span m="267311">keep</span> <span m="267582">the</span> <span m="267853">local</span>
  <span m="268124">clock</span> <span m="268395">in</span> <span m="268667">sync</span>
  <span m="268938">with</span> <span m="269209">the</span> <span m="269480">transmitter's</span>
  <span m="269751">clock,</span> <span m="270022">the</span> <span m="270294">incoming</span>
  <span m="270565">waveform</span> <span m="270836">needs</span> <span m="271107">to</span>
  <span m="271378">have</span> <span m="271650">reasonably</span> <span m="272476">frequent</span>
  <span m="273303">transitions.</span></p><p><span m="274130">But</span> <span m="274491">if</span>
  <span m="274852">the</span> <span m="275214">transmitter</span> <span m="275575">is</span>
  <span m="275937">sending</span> <span m="276298">say,</span> <span m="276660">all</span>
  <span m="277021">zeroes,</span> <span m="277382">how</span> <span m="277744">can</span>
  <span m="278105">we</span> <span m="278467">guarantee</span> <span m="278828">frequent-enough</span>
  <span m="279190">clock</span> <span m="280345">edges?</span></p><p><span m="281500">The</span>
  <span m="281833">trick,</span> <span m="282167">invented</span> <span m="282501">by</span>
  <span m="282835">IBM,</span> <span m="283169">is</span> <span m="283503">for</span>
  <span m="283837">the</span> <span m="284171">transmitter</span> <span m="284505">to</span>
  <span m="284838">take</span> <span m="285172">the</span> <span m="285506">stream</span>
  <span m="285840">of</span> <span m="286174">message</span> <span m="286508">bits</span>
  <span m="286842">and</span> <span m="287176">re-encode</span> <span m="287510">them</span>
  <span m="287824">into</span> <span m="288138">a</span> <span m="288453">bit</span>
  <span m="288767">stream</span> <span m="289081">that</span> <span m="289396">is</span>
  <span m="289710">guaranteed</span> <span m="290025">to</span> <span m="290339">have</span>
  <span m="290653">transitions</span> <span m="290968">no</span> <span m="291282">matter</span>
  <span m="291596">what</span> <span m="291911">the</span> <span m="292225">message</span>
  <span m="292540">bits</span> <span m="293415">are.</span></p><p><span m="294290">The</span>
  <span m="294721">most</span> <span m="295152">commonly</span> <span m="295583">used</span>
  <span m="296015">encoding</span> <span m="296446">is</span> <span m="296877">8b10b,</span>
  <span m="297308">where</span> <span m="297740">8</span> <span m="298171">message</span>
  <span m="298602">bits</span> <span m="299033">are</span> <span m="299465">encoded</span>
  <span m="299896">into</span> <span m="300327">10</span> <span m="300758">transmitted</span>
  <span m="301190">bits,</span> <span m="301650">where</span> <span m="302111">the</span>
  <span m="302572">encoding</span> <span m="303033">guarantees</span> <span m="303493">a</span>
  <span m="303954">transition</span> <span m="304415">at</span> <span m="304876">least</span>
  <span m="305336">every</span> <span m="305797">6</span> <span m="306258">bit</span>
  <span m="306719">times.</span></p><p><span m="307180">Of</span> <span m="307554">course,</span>
  <span m="307929">the</span> <span m="308304">receiver</span> <span m="308678">has</span>
  <span m="309053">to</span> <span m="309428">reverse</span> <span m="309802">the</span>
  <span m="310177">8b10b</span> <span m="310552">encoding</span> <span m="310926">to</span>
  <span m="311301">recover</span> <span m="311676">the</span> <span m="312050">actual</span>
  <span m="312425">message</span> <span m="312800">bits.</span></p><p><span m="314160">Pretty</span>
  <span m="315185">neat!</span></p><p><span m="316210">The</span> <span m="316498">benefit</span>
  <span m="316786">of</span> <span m="317075">this</span> <span m="317363">trick</span>
  <span m="317651">is</span> <span m="317940">that</span> <span m="318228">we</span>
  <span m="318516">truly</span> <span m="318805">only</span> <span m="319093">need</span>
  <span m="319381">to</span> <span m="319670">send</span> <span m="319958">a</span>
  <span m="320246">single</span> <span m="320535">stream</span> <span m="320823">of</span>
  <span m="321111">bits.</span></p><p><span m="321400">The</span> <span m="321700">receiver</span>
  <span m="322000">will</span> <span m="322300">be</span> <span m="322600">able</span>
  <span m="322900">to</span> <span m="323200">recover</span> <span m="323500">both</span>
  <span m="323800">the</span> <span m="324100">timing</span> <span m="324400">information</span>
  <span m="324700">and</span> <span m="325000">the</span> <span m="325300">data</span>
  <span m="325600">without</span> <span m="325900">also</span> <span m="326360">needing</span>
  <span m="326820">to</span> <span m="327280">transmit</span> <span m="327740">a</span>
  <span m="328200">separate</span> <span m="328660">clock</span> <span m="329120">signal.</span></p><p><span
  m="329580">Using</span> <span m="329927">these</span> <span m="330275">lessons,</span>
  <span m="330622">networks</span> <span m="330970">have</span> <span m="331317">evolved</span>
  <span m="331665">from</span> <span m="332012">using</span> <span m="332360">shared</span>
  <span m="332707">communication</span> <span m="333055">channels</span> <span m="333402">to</span>
  <span m="333750">using</span> <span m="334686">point-to-point</span> <span m="335623">links.</span></p><p><span
  m="336560">Today</span> <span m="337030">local-area</span> <span m="337500">networks</span>
  <span m="337970">use</span> <span m="338440">10,</span> <span m="338910">100,</span>
  <span m="339380">or</span> <span m="339850">1000</span> <span m="340320">BaseT</span>
  <span m="340790">wiring</span> <span m="341260">which</span> <span m="341730">includes</span>
  <span m="342200">separate</span> <span m="342670">differential</span> <span m="343116">pairs</span>
  <span m="343562">for</span> <span m="344008">sending</span> <span m="344454">and</span>
  <span m="344900">receiving,</span> <span m="345346">i.e.,</span> <span m="345793">each</span>
  <span m="346239">sending</span> <span m="346685">or</span> <span m="347131">receiving</span>
  <span m="347577">channel</span> <span m="348023">is</span> <span m="348470">unidirectional</span>
  <span m="349047">with</span> <span m="349625">a</span> <span m="350202">single</span>
  <span m="350780">driver</span> <span m="351357">and</span> <span m="351935">single</span>
  <span m="352512">receiver.</span></p><p><span m="353090">The</span> <span m="353417">network</span>
  <span m="353744">uses</span> <span m="354072">separate</span> <span m="354399">switches</span>
  <span m="354726">and</span> <span m="355054">routers</span> <span m="355381">to</span>
  <span m="355708">receive</span> <span m="356036">packets</span> <span m="356363">from</span>
  <span m="356690">a</span> <span m="357018">sender</span> <span m="357345">and</span>
  <span m="357672">then</span> <span m="358000">forward</span> <span m="358353">the</span>
  <span m="358707">packets</span> <span m="359060">over</span> <span m="359414">a</span>
  <span m="359768">point-to-point</span> <span m="360121">link</span> <span m="360475">to</span>
  <span m="360829">the</span> <span m="361182">next</span> <span m="361536">switch,</span>
  <span m="361890">and</span> <span m="362412">so</span> <span m="362935">on,</span>
  <span m="363458">across</span> <span m="363981">multiple</span> <span m="364504">point-to-point</span>
  <span m="365027">links</span> <span m="365550">until</span> <span m="366072">the</span>
  <span m="366595">packet</span> <span m="367118">arrives</span> <span m="367641">at</span>
  <span m="368164">its</span> <span m="368687">destination.</span></p><p><span m="369210">System-level</span>
  <span m="369698">connections</span> <span m="370186">have</span> <span m="370674">evolved</span>
  <span m="371162">to</span> <span m="371650">use</span> <span m="372139">the</span>
  <span m="372627">same</span> <span m="373115">communication</span> <span m="373603">strategy:</span>
  <span m="374091">point-to-point</span> <span m="374580">links</span> <span m="375036">with</span>
  <span m="375492">switches</span> <span m="375948">for</span> <span m="376404">routing</span>
  <span m="376860">packets</span> <span m="377316">to</span> <span m="377772">their</span>
  <span m="378228">intended</span> <span m="378684">destination.</span></p><p><span
  m="379140">Note</span> <span m="379495">that</span> <span m="379850">communication</span>
  <span m="380205">along</span> <span m="380560">each</span> <span m="380915">link</span>
  <span m="381270">is</span> <span m="381625">independent,</span> <span m="381980">so</span>
  <span m="382335">a</span> <span m="382690">network</span> <span m="383045">with</span>
  <span m="383400">many</span> <span m="383755">links</span> <span m="384110">can</span>
  <span m="384672">actually</span> <span m="385235">support</span> <span m="385797">a</span>
  <span m="386360">lot</span> <span m="386922">of</span> <span m="387485">communication</span>
  <span m="388047">bandwidth.</span></p><p><span m="388610">With</span> <span m="388904">a</span>
  <span m="389198">small</span> <span m="389492">amount</span> <span m="389786">of</span>
  <span m="390080">packet</span> <span m="390374">buffering</span> <span m="390668">in</span>
  <span m="390962">the</span> <span m="391256">switches</span> <span m="391550">to</span>
  <span m="391844">deal</span> <span m="392138">with</span> <span m="392432">momentary</span>
  <span m="392726">contention</span> <span m="393020">for</span> <span m="393359">a</span>
  <span m="393698">particular</span> <span m="394037">link,</span> <span m="394376">this</span>
  <span m="394715">is</span> <span m="395055">a</span> <span m="395394">very</span>
  <span m="395733">effective</span> <span m="396072">strategy</span> <span m="396411">for</span>
  <span m="396750">moving</span> <span m="397090">massive</span> <span m="397632">amounts</span>
  <span m="398174">of</span> <span m="398716">information</span> <span m="399258">from</span>
  <span m="399800">one</span> <span m="400342">component</span> <span m="400884">to</span>
  <span m="401426">the</span> <span m="401968">next.</span></p><p><span m="402510">In</span>
  <span m="402758">the</span> <span m="403006">next</span> <span m="403255">section,</span>
  <span m="403503">we'll</span> <span m="403752">look</span> <span m="404000">at</span>
  <span m="404249">some</span> <span m="404497">of</span> <span m="404746">the</span>
  <span m="404994">more</span> <span m="405243">interesting</span> <span m="405491">details.</span></p>
type: course
uid: 42d699f37ed53bc7a722031bc07a88bc

---
None