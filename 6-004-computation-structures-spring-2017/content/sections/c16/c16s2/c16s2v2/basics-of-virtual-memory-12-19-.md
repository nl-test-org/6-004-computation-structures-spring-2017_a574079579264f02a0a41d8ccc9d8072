---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 8yO2FBBfaB0
  parent_uid: 1b47d2851e468b81e08b8ec073bb5554
  title: Video-YouTube-Stream
  type: Video
  uid: 6cf635778af1e258f6979109a7673e20
- id: 3Play-3Play YouTube id-Stream
  media_location: 8yO2FBBfaB0
  parent_uid: 1b47d2851e468b81e08b8ec073bb5554
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 964b76958d0374340f3d20a36a35ee30
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/8yO2FBBfaB0/default.jpg
  parent_uid: 1b47d2851e468b81e08b8ec073bb5554
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: cc55c79a6056bdec4ac35cc74be58e2c
- id: 8yO2FBBfaB0.srt
  parent_uid: 1b47d2851e468b81e08b8ec073bb5554
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v2/basics-of-virtual-memory-12-19-/8yO2FBBfaB0.srt
  title: 3play caption file
  type: null
  uid: cab8bbcdc1cd51b9b1edd4a8adc698fa
- id: 8yO2FBBfaB0.pdf
  parent_uid: 1b47d2851e468b81e08b8ec073bb5554
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v2/basics-of-virtual-memory-12-19-/8yO2FBBfaB0.pdf
  title: 3play pdf file
  type: null
  uid: 940dd9428fdbf7553de63d6e38cd8100
- id: Caption-3Play YouTube id-SRT
  parent_uid: 1b47d2851e468b81e08b8ec073bb5554
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b4da44f2b616515dc4bd750c0ae337c3
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 1b47d2851e468b81e08b8ec073bb5554
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 3c62fe262431800e05b05d9545b9c2c8
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_16-02-02_300k.mp4
  parent_uid: 1b47d2851e468b81e08b8ec073bb5554
  title: Video-Internet Archive-MP4
  type: Video
  uid: e26b8abcaa37b8f37a6c1edce8b24f03
inline_embed_id: 45580339basicsofvirtualmemory121973130350
layout: video
order_index: null
parent_uid: 1b18dff37f75886236c9fbc0722c8445
related_resources_text: ''
short_url: basics-of-virtual-memory-12-19-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v2/basics-of-virtual-memory-12-19-
template_type: Embed
title: Basics of Virtual Memory
transcript: <p><span m="870">Here's</span> <span m="1258">how</span> <span m="1647">our</span>
  <span m="2036">virtual</span> <span m="2425">memory</span> <span m="2813">system</span>
  <span m="3202">will</span> <span m="3591">work.</span></p><p><span m="3980">The</span>
  <span m="4341">memory</span> <span m="4703">addresses</span> <span m="5064">generated</span>
  <span m="5426">by</span> <span m="5787">the</span> <span m="6149">CPU</span> <span
  m="6510">are</span> <span m="6872">called</span> <span m="7233">virtual</span> <span
  m="7595">addresses</span> <span m="7956">to</span> <span m="8318">distinguish</span>
  <span m="8680">them</span> <span m="9082">from</span> <span m="9484">the</span>
  <span m="9886">physical</span> <span m="10288">addresses</span> <span m="10691">used</span>
  <span m="11093">by</span> <span m="11495">main</span> <span m="11897">memory.</span></p><p><span
  m="12300">In</span> <span m="12561">between</span> <span m="12823">the</span> <span
  m="13085">CPU</span> <span m="13347">and</span> <span m="13609">main</span> <span
  m="13871">memory</span> <span m="14133">there's</span> <span m="14395">a</span>
  <span m="14656">new</span> <span m="14918">piece</span> <span m="15180">of</span>
  <span m="15442">hardware</span> <span m="15704">called</span> <span m="15966">the</span>
  <span m="16228">memory</span> <span m="16490">management</span> <span m="17680">unit</span>
  <span m="18870">(MMU).</span></p><p><span m="20060">The</span> <span m="20507">MMU's</span>
  <span m="20954">job</span> <span m="21401">is</span> <span m="21849">to</span> <span
  m="22296">translate</span> <span m="22743">virtual</span> <span m="23190">addresses</span>
  <span m="23638">to</span> <span m="24085">physical</span> <span m="24532">addresses.</span></p><p><span
  m="24980">&quot;But</span> <span m="25480">wait!&quot;</span> <span m="25980">you</span>
  <span m="26480">say.</span></p><p><span m="26980">&quot;Doesn't</span> <span m="27389">the</span>
  <span m="27798">cache</span> <span m="28207">go</span> <span m="28616">between</span>
  <span m="29025">the</span> <span m="29434">CPU</span> <span m="29843">and</span>
  <span m="30252">main</span> <span m="30661">memory?&quot;</span> <span m="31070">You're</span>
  <span m="31320">right</span> <span m="31570">and</span> <span m="31820">at</span>
  <span m="32070">the</span> <span m="32320">end</span> <span m="32570">of</span>
  <span m="32820">this</span> <span m="33070">lecture</span> <span m="33320">we'll</span>
  <span m="33570">talk</span> <span m="33820">about</span> <span m="34070">how</span>
  <span m="34320">to</span> <span m="34570">use</span> <span m="34820">both</span>
  <span m="35070">an</span> <span m="35320">MMU</span> <span m="35570">and</span>
  <span m="35821">a</span> <span m="36400">cache.</span></p><p><span m="36980">But</span>
  <span m="37428">for</span> <span m="37876">now,</span> <span m="38324">let's</span>
  <span m="38773">assume</span> <span m="39221">there's</span> <span m="39669">only</span>
  <span m="40117">an</span> <span m="40566">MMU</span> <span m="41014">and</span>
  <span m="41462">no</span> <span m="41910">cache.</span></p><p><span m="42359">The</span>
  <span m="42762">MMU</span> <span m="43165">hardware</span> <span m="43568">translates</span>
  <span m="43971">virtual</span> <span m="44374">addresses</span> <span m="44777">to</span>
  <span m="45181">physical</span> <span m="45584">addresses</span> <span m="45987">using</span>
  <span m="46390">a</span> <span m="46793">simple</span> <span m="47196">table</span>
  <span m="47600">lookup.</span></p><p><span m="48890">This</span> <span m="49199">table</span>
  <span m="49509">is</span> <span m="49819">called</span> <span m="50129">the</span>
  <span m="50439">page</span> <span m="50749">map</span> <span m="51059">or</span>
  <span m="51369">page</span> <span m="51679">table.</span></p><p><span m="51989">Conceptually,</span>
  <span m="52332">the</span> <span m="52675">MMU</span> <span m="53018">uses</span>
  <span m="53361">the</span> <span m="53704">virtual</span> <span m="54048">address</span>
  <span m="54391">as</span> <span m="54734">index</span> <span m="55077">to</span>
  <span m="55420">select</span> <span m="55764">an</span> <span m="56107">entry</span>
  <span m="56450">in</span> <span m="56793">the</span> <span m="57136">table,</span>
  <span m="57480">which</span> <span m="58017">tells</span> <span m="58554">us</span>
  <span m="59091">the</span> <span m="59628">corresponding</span> <span m="60165">physical</span>
  <span m="60702">address.</span></p><p><span m="61239">The</span> <span m="61628">table</span>
  <span m="62017">allows</span> <span m="62407">a</span> <span m="62796">particular</span>
  <span m="63185">virtual</span> <span m="63575">address</span> <span m="63964">to</span>
  <span m="64353">be</span> <span m="64743">found</span> <span m="65132">anywhere</span>
  <span m="65521">in</span> <span m="65911">main</span> <span m="66300">memory.</span></p><p><span
  m="66690">In</span> <span m="66955">normal</span> <span m="67221">operation</span>
  <span m="67486">we'd</span> <span m="67752">want</span> <span m="68018">to</span>
  <span m="68283">ensure</span> <span m="68549">that</span> <span m="68815">two</span>
  <span m="69080">virtual</span> <span m="69346">addresses</span> <span m="69611">don't</span>
  <span m="69877">map</span> <span m="70143">to</span> <span m="70408">the</span>
  <span m="70674">same</span> <span m="70940">physical</span> <span m="72239">address.</span></p><p><span
  m="73539">But</span> <span m="73782">it</span> <span m="74025">would</span> <span
  m="74269">be</span> <span m="74512">okay</span> <span m="74755">if</span> <span
  m="74999">some</span> <span m="75242">of</span> <span m="75486">the</span> <span
  m="75729">virtual</span> <span m="75972">addresses</span> <span m="76216">did</span>
  <span m="76459">not</span> <span m="76703">have</span> <span m="76946">a</span>
  <span m="77189">translation</span> <span m="77433">to</span> <span m="77676">a</span>
  <span m="77920">physical</span> <span m="78865">address.</span></p><p><span m="79810">This</span>
  <span m="80094">would</span> <span m="80378">indicate</span> <span m="80662">that</span>
  <span m="80946">the</span> <span m="81231">contents</span> <span m="81515">of</span>
  <span m="81799">the</span> <span m="82083">requested</span> <span m="82367">virtual</span>
  <span m="82652">address</span> <span m="82936">haven't</span> <span m="83220">yet</span>
  <span m="83504">been</span> <span m="83789">loaded</span> <span m="84162">into</span>
  <span m="84536">main</span> <span m="84909">memory,</span> <span m="85283">so</span>
  <span m="85657">the</span> <span m="86030">MMU</span> <span m="86404">would</span>
  <span m="86778">signal</span> <span m="87151">a</span> <span m="87525">memory-management</span>
  <span m="87899">exception</span> <span m="88272">to</span> <span m="88646">the</span>
  <span m="89020">CPU,</span> <span m="89395">which</span> <span m="89770">could</span>
  <span m="90145">assign</span> <span m="90520">a</span> <span m="90895">location</span>
  <span m="91270">in</span> <span m="91645">physical</span> <span m="92020">memory</span>
  <span m="92443">and</span> <span m="92866">perform</span> <span m="93289">the</span>
  <span m="93712">required</span> <span m="94135">I/O</span> <span m="94558">operation</span>
  <span m="94981">to</span> <span m="95404">initialize</span> <span m="95827">that</span>
  <span m="96250">location</span> <span m="96673">from</span> <span m="97096">secondary</span>
  <span m="97520">storage.</span></p><p><span m="100140">The</span> <span m="100432">MMU</span>
  <span m="100725">table</span> <span m="101018">gives</span> <span m="101311">the</span>
  <span m="101603">system</span> <span m="101896">a</span> <span m="102189">lot</span>
  <span m="102482">of</span> <span m="102775">control</span> <span m="103067">over</span>
  <span m="103360">how</span> <span m="103653">physical</span> <span m="103946">memory</span>
  <span m="104238">is</span> <span m="104531">accessed</span> <span m="104824">by</span>
  <span m="105117">the</span> <span m="105410">program</span> <span m="105885">running</span>
  <span m="106361">on</span> <span m="106837">the</span> <span m="107313">CPU.</span></p><p><span
  m="107789">For</span> <span m="108167">example,</span> <span m="108546">we</span>
  <span m="108924">could</span> <span m="109303">arrange</span> <span m="109682">to</span>
  <span m="110060">run</span> <span m="110439">multiple</span> <span m="110818">programs</span>
  <span m="111196">in</span> <span m="111575">quick</span> <span m="111954">succession</span>
  <span m="112332">(a</span> <span m="112711">technique</span> <span m="113090">called</span>
  <span m="113598">time</span> <span m="114106">sharing)</span> <span m="114615">by</span>
  <span m="115123">changing</span> <span m="115631">the</span> <span m="116140">page</span>
  <span m="116648">map</span> <span m="117156">when</span> <span m="117665">we</span>
  <span m="118173">change</span> <span m="118681">programs.</span></p><p><span m="119190">Main</span>
  <span m="119535">memory</span> <span m="119880">locations</span> <span m="120225">accessible</span>
  <span m="120570">to</span> <span m="120915">one</span> <span m="121260">program</span>
  <span m="121605">could</span> <span m="121950">be</span> <span m="122295">made</span>
  <span m="122640">inaccessible</span> <span m="122985">to</span> <span m="123330">another</span>
  <span m="123675">program</span> <span m="124020">by</span> <span m="124425">proper</span>
  <span m="124830">management</span> <span m="125235">of</span> <span m="125640">their</span>
  <span m="126045">respective</span> <span m="126450">page</span> <span m="126855">maps.</span></p><p><span
  m="127260">And</span> <span m="127640">we</span> <span m="128020">could</span> <span
  m="128400">use</span> <span m="128780">memory-management</span> <span m="129160">exceptions</span>
  <span m="129540">to</span> <span m="129920">load</span> <span m="130300">program</span>
  <span m="130680">contents</span> <span m="131060">into</span> <span m="131440">main</span>
  <span m="131820">memory</span> <span m="132200">on</span> <span m="132628">demand</span>
  <span m="133056">instead</span> <span m="133485">of</span> <span m="133913">having</span>
  <span m="134341">to</span> <span m="134770">load</span> <span m="135198">the</span>
  <span m="135627">entire</span> <span m="136055">program</span> <span m="136483">before</span>
  <span m="136912">execution</span> <span m="137340">starts.</span></p><p><span m="137769">In</span>
  <span m="138106">fact,</span> <span m="138443">we</span> <span m="138780">only</span>
  <span m="139117">need</span> <span m="139454">to</span> <span m="139791">ensure</span>
  <span m="140128">the</span> <span m="140465">current</span> <span m="140802">working</span>
  <span m="141139">set</span> <span m="141476">of</span> <span m="141813">a</span>
  <span m="142150">program</span> <span m="142487">is</span> <span m="142824">actually</span>
  <span m="143161">resident</span> <span m="143499">in</span> <span m="144159">main</span>
  <span m="144819">memory.</span></p><p><span m="145480">Locations</span> <span m="145878">not</span>
  <span m="146276">currently</span> <span m="146675">being</span> <span m="147073">used</span>
  <span m="147471">could</span> <span m="147870">live</span> <span m="148268">in</span>
  <span m="148666">secondary</span> <span m="149065">storage</span> <span m="149463">until</span>
  <span m="149861">needed.</span></p><p><span m="150260">In</span> <span m="150544">this</span>
  <span m="150828">lecture</span> <span m="151113">and</span> <span m="151397">next,</span>
  <span m="151681">we'll</span> <span m="151966">see</span> <span m="152250">how</span>
  <span m="152535">the</span> <span m="152819">MMU</span> <span m="153103">plays</span>
  <span m="153388">a</span> <span m="153672">central</span> <span m="153957">role</span>
  <span m="154241">in</span> <span m="154525">the</span> <span m="154810">design</span>
  <span m="155094">of</span> <span m="155379">a</span> <span m="156213">modern</span>
  <span m="157047">timesharing</span> <span m="157881">computer</span> <span m="158715">system.</span></p><p><span
  m="159549">Of</span> <span m="159893">course,</span> <span m="160238">we'd</span>
  <span m="160583">need</span> <span m="160927">an</span> <span m="161272">impossibly</span>
  <span m="161617">large</span> <span m="161962">table</span> <span m="162306">to</span>
  <span m="162651">separately</span> <span m="162996">map</span> <span m="163341">each</span>
  <span m="163685">virtual</span> <span m="164030">address</span> <span m="164375">to</span>
  <span m="164720">a</span> <span m="165296">physical</span> <span m="165873">address.</span></p><p><span
  m="166450">So</span> <span m="166824">instead</span> <span m="167198">we</span>
  <span m="167572">divide</span> <span m="167947">both</span> <span m="168321">the</span>
  <span m="168695">virtual</span> <span m="169070">and</span> <span m="169444">physical</span>
  <span m="169818">address</span> <span m="170192">spaces</span> <span m="170567">into</span>
  <span m="170941">fixed-sized</span> <span m="171315">blocks,</span> <span m="171690">called</span>
  <span m="172765">pages.</span></p><p><span m="173840">Page</span> <span m="174236">sizes</span>
  <span m="174632">are</span> <span m="175028">always</span> <span m="175425">a</span>
  <span m="175821">power-of-2</span> <span m="176217">bytes,</span> <span m="176613">say</span>
  <span m="177010">2^p</span> <span m="177406">bytes,</span> <span m="177802">so</span>
  <span m="178198">p</span> <span m="178595">is</span> <span m="178991">the</span>
  <span m="179387">number</span> <span m="179783">address</span> <span m="180180">bits</span>
  <span m="180513">needed</span> <span m="180847">to</span> <span m="181181">select</span>
  <span m="181515">a</span> <span m="181849">particular</span> <span m="182183">location</span>
  <span m="182517">on</span> <span m="182851">the</span> <span m="183185">page.</span></p><p><span
  m="183519">We'll</span> <span m="183904">the</span> <span m="184289">use</span>
  <span m="184674">low-order</span> <span m="185059">p</span> <span m="185444">bits</span>
  <span m="185829">of</span> <span m="186214">the</span> <span m="186599">virtual</span>
  <span m="186984">or</span> <span m="187369">physical</span> <span m="187754">address</span>
  <span m="188139">as</span> <span m="188524">the</span> <span m="188909">page</span>
  <span m="189294">offset.</span></p><p><span m="189680">The</span> <span m="189969">remaining</span>
  <span m="190258">address</span> <span m="190548">bits</span> <span m="190837">tell</span>
  <span m="191126">us</span> <span m="191416">which</span> <span m="191705">page</span>
  <span m="191995">is</span> <span m="192284">being</span> <span m="192573">accessed</span>
  <span m="192863">and</span> <span m="193152">are</span> <span m="193441">called</span>
  <span m="193731">the</span> <span m="194020">page</span> <span m="194310">number.</span></p><p><span
  m="195310">A</span> <span m="195966">typical</span> <span m="196623">page</span>
  <span m="197279">size</span> <span m="197936">is</span> <span m="198593">4KB</span>
  <span m="199249">to</span> <span m="199906">16KB,</span> <span m="200562">which</span>
  <span m="201219">correspond</span> <span m="201876">to</span> <span m="202532">p=12</span>
  <span m="203189">and</span> <span m="203845">p=14</span> <span m="204502">respectively.</span></p><p><span
  m="205159">Suppose</span> <span m="205929">p=12.</span></p><p><span m="206700">If</span>
  <span m="207111">the</span> <span m="207522">CPU</span> <span m="207933">produces</span>
  <span m="208345">a</span> <span m="208756">32-bit</span> <span m="209167">virtual</span>
  <span m="209578">address,</span> <span m="209990">the</span> <span m="210401">low-order</span>
  <span m="210812">12</span> <span m="211223">bits</span> <span m="211635">of</span>
  <span m="212046">the</span> <span m="212457">virtual</span> <span m="212868">address</span>
  <span m="213280">are</span> <span m="213677">the</span> <span m="214074">page</span>
  <span m="214471">offset</span> <span m="214868">and</span> <span m="215265">the</span>
  <span m="215662">high-order</span> <span m="216060">20</span> <span m="216457">bits</span>
  <span m="216854">are</span> <span m="217251">the</span> <span m="217648">virtual</span>
  <span m="218045">page</span> <span m="218442">number.</span></p><p><span m="218840">Similarly,</span>
  <span m="219208">the</span> <span m="219577">low-order</span> <span m="219946">p</span>
  <span m="220314">bits</span> <span m="220683">of</span> <span m="221052">the</span>
  <span m="221420">physical</span> <span m="221789">address</span> <span m="222158">are</span>
  <span m="222526">the</span> <span m="222895">page</span> <span m="223264">offset</span>
  <span m="223632">and</span> <span m="224001">the</span> <span m="224370">remaining</span>
  <span m="224739">physical</span> <span m="225170">address</span> <span m="225601">bits</span>
  <span m="226032">are</span> <span m="226464">the</span> <span m="226895">physical</span>
  <span m="227326">page</span> <span m="227757">number.</span></p><p><span m="228189">The</span>
  <span m="228642">key</span> <span m="229096">idea</span> <span m="229550">is</span>
  <span m="230004">that</span> <span m="230458">the</span> <span m="230912">MMU</span>
  <span m="231366">will</span> <span m="231820">manage</span> <span m="232274">pages,</span>
  <span m="232728">not</span> <span m="233182">individual</span> <span m="233636">locations.</span></p><p><span
  m="234090">We'll</span> <span m="234497">move</span> <span m="234905">entire</span>
  <span m="235313">pages</span> <span m="235721">from</span> <span m="236129">secondary</span>
  <span m="236536">storage</span> <span m="236944">into</span> <span m="237352">main</span>
  <span m="237760">memory.</span></p><p><span m="238168">By</span> <span m="238537">the</span>
  <span m="238907">principal</span> <span m="239276">of</span> <span m="239646">locality,</span>
  <span m="240015">if</span> <span m="240385">a</span> <span m="240754">program</span>
  <span m="241124">access</span> <span m="241493">one</span> <span m="241863">location</span>
  <span m="242232">on</span> <span m="242602">a</span> <span m="242971">page,</span>
  <span m="243341">we</span> <span m="243710">expect</span> <span m="244080">it</span>
  <span m="244450">will</span> <span m="245104">soon</span> <span m="245759">access</span>
  <span m="246414">other</span> <span m="247069">nearby</span> <span m="247724">locations.</span></p><p><span
  m="248379">By</span> <span m="248740">choosing</span> <span m="249101">the</span>
  <span m="249463">page</span> <span m="249824">offset</span> <span m="250185">from</span>
  <span m="250547">the</span> <span m="250908">low-order</span> <span m="251269">address</span>
  <span m="251631">bits,</span> <span m="251992">we'll</span> <span m="252353">ensure</span>
  <span m="252715">that</span> <span m="253076">nearby</span> <span m="253437">locations</span>
  <span m="253799">live</span> <span m="254098">on</span> <span m="254398">the</span>
  <span m="254697">same</span> <span m="254997">page</span> <span m="255296">(unless</span>
  <span m="255596">of</span> <span m="255895">course</span> <span m="256195">we're</span>
  <span m="256494">near</span> <span m="256794">one</span> <span m="257093">end</span>
  <span m="257393">of</span> <span m="257692">the</span> <span m="257992">page</span>
  <span m="258291">or</span> <span m="258591">the</span> <span m="258890">other).</span></p><p><span
  m="259190">So</span> <span m="259653">pages</span> <span m="260117">naturally</span>
  <span m="260581">capture</span> <span m="261045">the</span> <span m="261508">notion</span>
  <span m="261972">of</span> <span m="262436">locality.</span></p><p><span m="262900">And</span>
  <span m="263274">since</span> <span m="263649">pages</span> <span m="264023">are</span>
  <span m="264398">large,</span> <span m="264773">by</span> <span m="265147">dealing</span>
  <span m="265522">with</span> <span m="265896">pages</span> <span m="266271">when</span>
  <span m="266646">accessing</span> <span m="267020">secondary</span> <span m="267395">storage,</span>
  <span m="267770">we'll</span> <span m="268127">take</span> <span m="268485">advantage</span>
  <span m="268843">that</span> <span m="269201">reading</span> <span m="269559">or</span>
  <span m="269917">writing</span> <span m="270275">many</span> <span m="270632">locations</span>
  <span m="270990">is</span> <span m="271348">only</span> <span m="271706">slightly</span>
  <span m="272064">more</span> <span m="272422">time</span> <span m="272780">consuming</span>
  <span m="273443">than</span> <span m="274106">accessing</span> <span m="274769">the</span>
  <span m="275432">first</span> <span m="276095">location.</span></p><p><span m="276759">The</span>
  <span m="277177">MMU</span> <span m="277595">will</span> <span m="278013">map</span>
  <span m="278432">virtual</span> <span m="278850">page</span> <span m="279268">numbers</span>
  <span m="279686">to</span> <span m="280105">physical</span> <span m="280523">page</span>
  <span m="280941">numbers.</span></p><p><span m="281360">It</span> <span m="281745">does</span>
  <span m="282131">this</span> <span m="282517">by</span> <span m="282903">using</span>
  <span m="283289">the</span> <span m="283674">virtual</span> <span m="284060">page</span>
  <span m="284446">number</span> <span m="284832">(VPN)</span> <span m="285218">as</span>
  <span m="285604">an</span> <span m="285989">index</span> <span m="286375">into</span>
  <span m="286761">the</span> <span m="287147">page</span> <span m="287533">table.</span></p><p><span
  m="287919">Each</span> <span m="288192">entry</span> <span m="288465">in</span>
  <span m="288738">the</span> <span m="289011">page</span> <span m="289284">table</span>
  <span m="289557">indicates</span> <span m="289830">if</span> <span m="290103">the</span>
  <span m="290376">page</span> <span m="290649">is</span> <span m="290922">resident</span>
  <span m="291195">in</span> <span m="291468">main</span> <span m="291741">memory</span>
  <span m="292014">and,</span> <span m="292287">if</span> <span m="292561">it</span>
  <span m="293045">is,</span> <span m="293529">provides</span> <span m="294013">the</span>
  <span m="294497">appropriate</span> <span m="294982">physical</span> <span m="295466">page</span>
  <span m="295950">number</span> <span m="296434">(PPN).</span></p><p><span m="296919">The</span>
  <span m="297359">PPN</span> <span m="297800">is</span> <span m="298241">combined</span>
  <span m="298681">with</span> <span m="299122">the</span> <span m="299563">page</span>
  <span m="300003">offset</span> <span m="300444">to</span> <span m="300885">form</span>
  <span m="301325">the</span> <span m="301766">physical</span> <span m="302207">address</span>
  <span m="302647">for</span> <span m="303088">main</span> <span m="303529">memory.</span></p><p><span
  m="303970">If</span> <span m="304381">the</span> <span m="304792">requested</span>
  <span m="305203">virtual</span> <span m="305615">page</span> <span m="306026">is</span>
  <span m="306437">NOT</span> <span m="306848">resident</span> <span m="307260">in</span>
  <span m="307671">main</span> <span m="308082">memory,</span> <span m="308493">the</span>
  <span m="308905">MMU</span> <span m="309316">signals</span> <span m="309727">a</span>
  <span m="310138">memory-management</span> <span m="310550">exception,</span> <span
  m="310867">called</span> <span m="311185">a</span> <span m="311502">page</span>
  <span m="311820">fault,</span> <span m="312137">to</span> <span m="312455">the</span>
  <span m="312773">CPU</span> <span m="313090">so</span> <span m="313408">it</span>
  <span m="313725">can</span> <span m="314043">load</span> <span m="314361">the</span>
  <span m="314678">appropriate</span> <span m="314996">page</span> <span m="315313">from</span>
  <span m="315631">secondary</span> <span m="315949">storage</span> <span m="316424">and</span>
  <span m="316899">set</span> <span m="317374">up</span> <span m="317849">the</span>
  <span m="318324">appropriate</span> <span m="318799">mapping</span> <span m="319274">in</span>
  <span m="319749">the</span> <span m="320224">MMU.</span></p><p><span m="320699">Our</span>
  <span m="321052">plan</span> <span m="321405">to</span> <span m="321758">use</span>
  <span m="322111">main</span> <span m="322464">memory</span> <span m="322817">as</span>
  <span m="323170">page</span> <span m="323524">cache</span> <span m="323877">is</span>
  <span m="324230">called</span> <span m="324583">&quot;paging&quot;</span> <span
  m="324936">or</span> <span m="325289">sometimes</span> <span m="325642">&quot;demand</span>
  <span m="325995">paging&quot;</span> <span m="326349">since</span> <span m="326675">movements</span>
  <span m="327002">of</span> <span m="327329">pages</span> <span m="327656">to</span>
  <span m="327983">and</span> <span m="328310">from</span> <span m="328637">secondary</span>
  <span m="328964">storage</span> <span m="329291">is</span> <span m="329618">determined</span>
  <span m="329945">by</span> <span m="330272">the</span> <span m="330599">demands</span>
  <span m="330926">of</span> <span m="331253">the</span> <span m="331580">program.</span></p><p><span
  m="333030">So</span> <span m="333570">here's</span> <span m="334110">the</span>
  <span m="334650">plan.</span></p><p><span m="335190">Initially</span> <span m="335541">all</span>
  <span m="335893">the</span> <span m="336245">virtual</span> <span m="336597">pages</span>
  <span m="336949">for</span> <span m="337300">a</span> <span m="337652">program</span>
  <span m="338004">reside</span> <span m="338356">in</span> <span m="338708">secondary</span>
  <span m="339059">storage</span> <span m="339411">and</span> <span m="339763">the</span>
  <span m="340115">MMU</span> <span m="340467">is</span> <span m="340819">empty,</span>
  <span m="341273">i.e.,</span> <span m="341727">there</span> <span m="342181">are</span>
  <span m="342635">no</span> <span m="343089">pages</span> <span m="343543">resident</span>
  <span m="343997">in</span> <span m="344451">physical</span> <span m="344905">memory.</span></p><p><span
  m="345360">The</span> <span m="345660">CPU</span> <span m="345960">starts</span>
  <span m="346260">running</span> <span m="346560">the</span> <span m="346860">program</span>
  <span m="347160">and</span> <span m="347460">each</span> <span m="347760">virtual</span>
  <span m="348060">address</span> <span m="348360">it</span> <span m="348660">generates,</span>
  <span m="348960">either</span> <span m="349260">for</span> <span m="349560">an</span>
  <span m="349860">instruction</span> <span m="350181">fetch</span> <span m="350502">or</span>
  <span m="350823">data</span> <span m="351144">access,</span> <span m="351465">is</span>
  <span m="351786">passed</span> <span m="352107">to</span> <span m="352428">the</span>
  <span m="352750">MMU</span> <span m="353071">to</span> <span m="353392">be</span>
  <span m="353713">mapped</span> <span m="354034">to</span> <span m="354355">a</span>
  <span m="354676">physical</span> <span m="354997">address</span> <span m="355319">in</span>
  <span m="356012">main</span> <span m="356706">memory.</span></p><p><span m="357400">If</span>
  <span m="357701">the</span> <span m="358002">virtual</span> <span m="358303">address</span>
  <span m="358605">is</span> <span m="358906">resident</span> <span m="359207">in</span>
  <span m="359508">physical</span> <span m="359810">memory,</span> <span m="360111">the</span>
  <span m="360412">main</span> <span m="360713">memory</span> <span m="361015">hardware</span>
  <span m="361316">can</span> <span m="361617">complete</span> <span m="361919">the</span>
  <span m="363114">access.</span></p><p><span m="364310">If</span> <span m="364665">the</span>
  <span m="365020">virtual</span> <span m="365375">address</span> <span m="365730">in</span>
  <span m="366085">NOT</span> <span m="366440">resident</span> <span m="366795">in</span>
  <span m="367150">physical</span> <span m="367505">memory,</span> <span m="367860">the</span>
  <span m="368215">MMU</span> <span m="368570">signals</span> <span m="368925">a</span>
  <span m="369280">page</span> <span m="369635">fault</span> <span m="369990">exception,</span>
  <span m="370422">forcing</span> <span m="370855">the</span> <span m="371287">CPU</span>
  <span m="371720">to</span> <span m="372153">switch</span> <span m="372585">execution</span>
  <span m="373018">to</span> <span m="373450">special</span> <span m="373883">code</span>
  <span m="374316">called</span> <span m="374748">the</span> <span m="375181">page</span>
  <span m="375613">fault</span> <span m="376046">handler.</span></p><p><span m="376479">The</span>
  <span m="376832">handler</span> <span m="377185">allocates</span> <span m="377538">a</span>
  <span m="377891">physical</span> <span m="378244">page</span> <span m="378597">to</span>
  <span m="378950">hold</span> <span m="379304">the</span> <span m="379657">requested</span>
  <span m="380010">virtual</span> <span m="380363">page</span> <span m="380716">and</span>
  <span m="381069">loads</span> <span m="381422">the</span> <span m="381775">virtual</span>
  <span m="382129">page</span> <span m="382772">from</span> <span m="383415">secondary</span>
  <span m="384058">storage</span> <span m="384701">into</span> <span m="385344">main</span>
  <span m="385987">memory.</span></p><p><span m="386630">It</span> <span m="386882">then</span>
  <span m="387135">adjusts</span> <span m="387388">the</span> <span m="387641">page</span>
  <span m="387894">map</span> <span m="388147">entry</span> <span m="388400">for</span>
  <span m="388653">the</span> <span m="388906">requested</span> <span m="389159">virtual</span>
  <span m="389412">page</span> <span m="389665">to</span> <span m="389918">show</span>
  <span m="390171">that</span> <span m="390424">it</span> <span m="390677">is</span>
  <span m="390930">now</span> <span m="391320">resident</span> <span m="391711">and</span>
  <span m="392101">to</span> <span m="392492">indicate</span> <span m="392883">the</span>
  <span m="393273">physical</span> <span m="393664">page</span> <span m="394054">number</span>
  <span m="394445">for</span> <span m="394836">the</span> <span m="395226">newly</span>
  <span m="395617">allocated</span> <span m="396007">and</span> <span m="396398">initialized</span>
  <span m="396789">physical</span> <span m="398164">page.</span></p><p><span m="399540">When</span>
  <span m="399842">trying</span> <span m="400145">to</span> <span m="400448">allocate</span>
  <span m="400750">a</span> <span m="401053">physical</span> <span m="401356">page,</span>
  <span m="401658">the</span> <span m="401961">handler</span> <span m="402264">may</span>
  <span m="402566">discover</span> <span m="402869">that</span> <span m="403172">all</span>
  <span m="403474">physical</span> <span m="403777">pages</span> <span m="404080">are</span>
  <span m="404510">currently</span> <span m="404940">in</span> <span m="405370">use.</span></p><p><span
  m="405800">In</span> <span m="406208">this</span> <span m="406617">case</span> <span
  m="407026">it</span> <span m="407435">chooses</span> <span m="407843">an</span>
  <span m="408252">existing</span> <span m="408661">page</span> <span m="409070">to</span>
  <span m="409478">replace,</span> <span m="409887">e.g.,</span> <span m="410296">a</span>
  <span m="410705">resident</span> <span m="411113">virtual</span> <span m="411522">page</span>
  <span m="411931">that</span> <span m="412340">hasn't</span> <span m="413037">been</span>
  <span m="413735">recently</span> <span m="414432">accessed.</span></p><p><span m="415130">It</span>
  <span m="415481">swaps</span> <span m="415833">the</span> <span m="416185">contents</span>
  <span m="416537">of</span> <span m="416889">the</span> <span m="417241">chosen</span>
  <span m="417593">virtual</span> <span m="417945">page</span> <span m="418297">out</span>
  <span m="418649">to</span> <span m="419001">secondary</span> <span m="419353">storage</span>
  <span m="419705">and</span> <span m="420057">updates</span> <span m="420409">the</span>
  <span m="420739">page</span> <span m="421069">map</span> <span m="421399">entry</span>
  <span m="421729">for</span> <span m="422059">the</span> <span m="422389">replaced</span>
  <span m="422719">virtual</span> <span m="423049">page</span> <span m="423379">to</span>
  <span m="423709">indicate</span> <span m="424039">it</span> <span m="424369">is</span>
  <span m="424699">no</span> <span m="425029">longer</span> <span m="425359">resident.</span></p><p><span
  m="425690">Now</span> <span m="425968">there's</span> <span m="426246">a</span>
  <span m="426524">free</span> <span m="426802">physical</span> <span m="427080">page</span>
  <span m="427359">to</span> <span m="427637">re-use</span> <span m="427915">to</span>
  <span m="428193">hold</span> <span m="428471">the</span> <span m="428749">contents</span>
  <span m="429028">of</span> <span m="429306">the</span> <span m="429584">virtual</span>
  <span m="429862">page</span> <span m="430140">that</span> <span m="430419">was</span>
  <span m="431824">missing.</span></p><p><span m="433229">The</span> <span m="433558">working</span>
  <span m="433887">set</span> <span m="434217">of</span> <span m="434546">the</span>
  <span m="434876">program,</span> <span m="435205">i.e.,</span> <span m="435535">the</span>
  <span m="435864">set</span> <span m="436193">of</span> <span m="436523">pages</span>
  <span m="436852">the</span> <span m="437182">program</span> <span m="437511">is</span>
  <span m="437841">currently</span> <span m="438170">accessing,</span> <span m="438500">is</span>
  <span m="438942">loaded</span> <span m="439385">into</span> <span m="439828">main</span>
  <span m="440270">memory</span> <span m="440713">through</span> <span m="441156">a</span>
  <span m="441599">series</span> <span m="442041">of</span> <span m="442484">page</span>
  <span m="442927">faults.</span></p><p><span m="443370">After</span> <span m="443725">a</span>
  <span m="444080">flurry</span> <span m="444435">of</span> <span m="444790">page</span>
  <span m="445145">faults</span> <span m="445500">when</span> <span m="445855">the</span>
  <span m="446210">program</span> <span m="446565">starts</span> <span m="446920">running,</span>
  <span m="447275">the</span> <span m="447630">working</span> <span m="447985">set</span>
  <span m="448340">changes</span> <span m="448695">slowly,</span> <span m="449050">so</span>
  <span m="449394">the</span> <span m="449739">frequency</span> <span m="450083">of</span>
  <span m="450428">page</span> <span m="450773">faults</span> <span m="451117">drops</span>
  <span m="451462">dramatically,</span> <span m="451807">perhaps</span> <span m="452151">close</span>
  <span m="452496">to</span> <span m="452841">zero</span> <span m="453185">if</span>
  <span m="453530">the</span> <span m="453875">program</span> <span m="454219">is</span>
  <span m="454564">small</span> <span m="454909">and</span> <span m="456094">well-behaved.</span></p><p><span
  m="457280">It</span> <span m="457624">is</span> <span m="457968">possible</span>
  <span m="458312">to</span> <span m="458656">write</span> <span m="459001">programs</span>
  <span m="459345">that</span> <span m="459689">consistently</span> <span m="460033">generate</span>
  <span m="460377">page</span> <span m="460722">faults,</span> <span m="461066">a</span>
  <span m="461410">phenomenon</span> <span m="461754">called</span> <span m="462099">thrashing.</span></p><p><span
  m="463919">Given</span> <span m="464335">the</span> <span m="464752">long</span>
  <span m="465169">access</span> <span m="465585">times</span> <span m="466002">of</span>
  <span m="466419">secondary</span> <span m="466836">storage,</span> <span m="467252">a</span>
  <span m="467669">program</span> <span m="468086">that's</span> <span m="468503">thrashing</span>
  <span m="468919">runs</span> <span m="469336">*very*</span> <span m="469753">slowly,</span>
  <span m="470170">usually</span> <span m="470655">so</span> <span m="471140">slowly</span>
  <span m="471625">that</span> <span m="472111">users</span> <span m="472596">give</span>
  <span m="473081">up</span> <span m="473566">and</span> <span m="474052">rewrite</span>
  <span m="474537">the</span> <span m="475022">program</span> <span m="475507">to</span>
  <span m="475993">behave</span> <span m="476478">more</span> <span m="476963">sensibly.</span></p><p><span
  m="477449">The</span> <span m="477809">design</span> <span m="478169">of</span>
  <span m="478529">the</span> <span m="478889">page</span> <span m="479249">map</span>
  <span m="479609">is</span> <span m="479969">straightforward.</span></p><p><span
  m="480330">There's</span> <span m="480652">one</span> <span m="480975">entry</span>
  <span m="481297">in</span> <span m="481620">the</span> <span m="481943">page</span>
  <span m="482265">map</span> <span m="482588">for</span> <span m="482911">each</span>
  <span m="483233">virtual</span> <span m="483556">page.</span></p><p><span m="483879">For</span>
  <span m="484237">example,</span> <span m="484596">if</span> <span m="484955">the</span>
  <span m="485314">CPU</span> <span m="485673">generates</span> <span m="486031">a</span>
  <span m="486390">32-bit</span> <span m="486749">virtual</span> <span m="487108">address</span>
  <span m="487467">and</span> <span m="487825">the</span> <span m="488184">page</span>
  <span m="488543">size</span> <span m="488902">is</span> <span m="489261">2^12</span>
  <span m="489620">bytes,</span> <span m="490160">the</span> <span m="490701">virtual</span>
  <span m="491241">page</span> <span m="491782">number</span> <span m="492322">has</span>
  <span m="492863">32-12</span> <span m="493403">=</span> <span m="493944">20</span>
  <span m="494484">bits</span> <span m="495025">and</span> <span m="495565">the</span>
  <span m="496106">page</span> <span m="496646">table</span> <span m="497187">will</span>
  <span m="497727">have</span> <span m="498268">2^20</span> <span m="498808">entries.</span></p><p><span
  m="499349">Each</span> <span m="499657">entry</span> <span m="499965">in</span>
  <span m="500274">the</span> <span m="500582">page</span> <span m="500891">table</span>
  <span m="501199">contains</span> <span m="501508">a</span> <span m="501816">&quot;resident</span>
  <span m="502125">bit&quot;</span> <span m="502433">(R)</span> <span m="502742">which</span>
  <span m="503050">is</span> <span m="503359">set</span> <span m="503667">to</span>
  <span m="503976">1</span> <span m="504284">when</span> <span m="504593">the</span>
  <span m="504901">virtual</span> <span m="505210">page</span> <span m="505623">is</span>
  <span m="506036">resident</span> <span m="506449">in</span> <span m="506862">physical</span>
  <span m="507275">memory.</span></p><p><span m="507689">If</span> <span m="508093">R</span>
  <span m="508497">is</span> <span m="508901">0,</span> <span m="509305">an</span>
  <span m="509709">access</span> <span m="510113">to</span> <span m="510517">that</span>
  <span m="510921">virtual</span> <span m="511325">page</span> <span m="511729">will</span>
  <span m="512133">cause</span> <span m="512537">a</span> <span m="512941">page</span>
  <span m="513345">fault.</span></p><p><span m="513750">If</span> <span m="514119">R</span>
  <span m="514488">is</span> <span m="514858">1,</span> <span m="515227">the</span>
  <span m="515596">entry</span> <span m="515966">also</span> <span m="516335">contains</span>
  <span m="516704">the</span> <span m="517074">PPN,</span> <span m="517443">indicating</span>
  <span m="517812">where</span> <span m="518182">to</span> <span m="518551">find</span>
  <span m="518920">the</span> <span m="519290">virtual</span> <span m="519659">page</span>
  <span m="520029">in</span> <span m="521139">main</span> <span m="522249">memory.</span></p><p><span
  m="523360">There's</span> <span m="523756">one</span> <span m="524152">additional</span>
  <span m="524548">state</span> <span m="524944">bit</span> <span m="525340">called</span>
  <span m="525736">the</span> <span m="526132">&quot;dirty</span> <span m="526528">bit&quot;</span>
  <span m="526924">(D).</span></p><p><span m="527320">When</span> <span m="527693">a</span>
  <span m="528067">page</span> <span m="528441">has</span> <span m="528815">just</span>
  <span m="529188">been</span> <span m="529562">loaded</span> <span m="529936">from</span>
  <span m="530310">secondary</span> <span m="530683">storage,</span> <span m="531057">it's</span>
  <span m="531431">&quot;clean&quot;,</span> <span m="531805">i.e,</span> <span m="532178">the</span>
  <span m="532552">contents</span> <span m="532926">of</span> <span m="533300">physical</span>
  <span m="533752">memory</span> <span m="534205">match</span> <span m="534657">the</span>
  <span m="535110">contents</span> <span m="535563">of</span> <span m="536015">the</span>
  <span m="536468">page</span> <span m="536921">in</span> <span m="537373">secondary</span>
  <span m="537826">storage.</span></p><p><span m="538279">So</span> <span m="538630">the</span>
  <span m="538981">D</span> <span m="539332">bit</span> <span m="539684">is</span>
  <span m="540035">set</span> <span m="540386">to</span> <span m="540737">0.</span></p><p><span
  m="541089">If</span> <span m="541382">subsequently</span> <span m="541675">the</span>
  <span m="541968">CPU</span> <span m="542261">stores</span> <span m="542555">into</span>
  <span m="542848">a</span> <span m="543141">location</span> <span m="543434">on</span>
  <span m="543727">the</span> <span m="544021">page,</span> <span m="544314">the</span>
  <span m="544607">D</span> <span m="544900">bit</span> <span m="545193">for</span>
  <span m="545487">the</span> <span m="545780">page</span> <span m="546073">is</span>
  <span m="546366">set</span> <span m="546660">to</span> <span m="547048">1,</span>
  <span m="547437">indicating</span> <span m="547826">the</span> <span m="548215">page</span>
  <span m="548603">is</span> <span m="548992">&quot;dirty&quot;,</span> <span m="549381">i.e.,</span>
  <span m="549770">the</span> <span m="550158">contents</span> <span m="550547">of</span>
  <span m="550936">memory</span> <span m="551325">now</span> <span m="551713">differ</span>
  <span m="552102">from</span> <span m="552491">the</span> <span m="552880">contents</span>
  <span m="553612">of</span> <span m="554345">secondary</span> <span m="555077">storage.</span></p><p><span
  m="555810">If</span> <span m="556123">a</span> <span m="556436">dirty</span> <span
  m="556749">page</span> <span m="557062">is</span> <span m="557375">ever</span> <span
  m="557688">chosen</span> <span m="558001">for</span> <span m="558315">replacement,</span>
  <span m="558628">its</span> <span m="558941">contents</span> <span m="559254">must</span>
  <span m="559567">be</span> <span m="559880">written</span> <span m="560193">to</span>
  <span m="560506">secondary</span> <span m="560820">storage</span> <span m="561311">in</span>
  <span m="561803">order</span> <span m="562295">to</span> <span m="562786">save</span>
  <span m="563278">the</span> <span m="563770">changes</span> <span m="564261">before</span>
  <span m="564753">the</span> <span m="565245">page</span> <span m="565736">gets</span>
  <span m="566228">reused.</span></p><p><span m="566720">Some</span> <span m="567053">MMUs</span>
  <span m="567387">have</span> <span m="567720">additional</span> <span m="568054">state</span>
  <span m="568387">bits</span> <span m="568721">in</span> <span m="569054">each</span>
  <span m="569388">page</span> <span m="569721">table</span> <span m="570055">entry.</span></p><p><span
  m="570389">For</span> <span m="570719">example,</span> <span m="571050">there</span>
  <span m="571381">could</span> <span m="571711">be</span> <span m="572042">a</span>
  <span m="572373">&quot;read-only&quot;</span> <span m="572704">bit</span> <span
  m="573034">which,</span> <span m="573365">when</span> <span m="573696">set,</span>
  <span m="574027">would</span> <span m="574357">generate</span> <span m="574688">an</span>
  <span m="575019">exception</span> <span m="575350">if</span> <span m="575655">the</span>
  <span m="575961">program</span> <span m="576266">attempts</span> <span m="576572">to</span>
  <span m="576877">store</span> <span m="577183">into</span> <span m="577488">the</span>
  <span m="577794">page.</span></p><p><span m="578100">This</span> <span m="578472">would</span>
  <span m="578844">be</span> <span m="579216">useful</span> <span m="579588">for</span>
  <span m="579960">protecting</span> <span m="580332">code</span> <span m="580705">pages</span>
  <span m="581077">from</span> <span m="581449">accidentally</span> <span m="581821">being</span>
  <span m="582193">corrupted</span> <span m="582565">by</span> <span m="582937">errant</span>
  <span m="583310">data</span> <span m="583948">accesses,</span> <span m="584586">a</span>
  <span m="585225">very</span> <span m="585863">handy</span> <span m="586502">debugging</span>
  <span m="587140">feature.</span></p><p><span m="587779">Here's</span> <span m="588084">an</span>
  <span m="588389">example</span> <span m="588694">of</span> <span m="588999">the</span>
  <span m="589304">MMU</span> <span m="589609">in</span> <span m="589914">action.</span></p><p><span
  m="590220">To</span> <span m="590595">make</span> <span m="590971">things</span>
  <span m="591346">simple,</span> <span m="591722">assume</span> <span m="592098">that</span>
  <span m="592473">the</span> <span m="592849">virtual</span> <span m="593225">address</span>
  <span m="593600">is</span> <span m="593976">12</span> <span m="594351">bits,</span>
  <span m="594727">consisting</span> <span m="595103">of</span> <span m="595478">an</span>
  <span m="595854">8-bit</span> <span m="596230">page</span> <span m="596661">offset</span>
  <span m="597092">and</span> <span m="597523">a</span> <span m="597955">4-bit</span>
  <span m="598386">virtual</span> <span m="598817">page</span> <span m="599248">number.</span></p><p><span
  m="599680">So</span> <span m="600200">there</span> <span m="600720">are</span> <span
  m="601240">2^4</span> <span m="601760">=</span> <span m="602280">16</span> <span
  m="602800">virtual</span> <span m="603320">pages.</span></p><p><span m="603840">The</span>
  <span m="604227">physical</span> <span m="604614">address</span> <span m="605001">is</span>
  <span m="605388">11</span> <span m="605775">bits,</span> <span m="606162">divided</span>
  <span m="606549">into</span> <span m="606936">the</span> <span m="607323">same</span>
  <span m="607710">8-bit</span> <span m="608097">page</span> <span m="608484">offset</span>
  <span m="608871">and</span> <span m="609258">a</span> <span m="609645">3-bit</span>
  <span m="610032">physical</span> <span m="610420">page</span> <span m="611080">number.</span></p><p><span
  m="611740">So</span> <span m="612296">there</span> <span m="612852">are</span> <span
  m="613408">2^3</span> <span m="613965">=</span> <span m="614521">8</span> <span
  m="615077">physical</span> <span m="615633">pages.</span></p><p><span m="616190">On</span>
  <span m="616477">the</span> <span m="616764">left</span> <span m="617051">we</span>
  <span m="617339">see</span> <span m="617626">a</span> <span m="617913">diagram</span>
  <span m="618201">showing</span> <span m="618488">the</span> <span m="618775">contents</span>
  <span m="619063">of</span> <span m="619350">the</span> <span m="619637">16-entry</span>
  <span m="619925">page</span> <span m="620212">map,</span> <span m="620499">i.e.,</span>
  <span m="620787">an</span> <span m="621074">entry</span> <span m="621361">for</span>
  <span m="621649">each</span> <span m="622499">virtual</span> <span m="623349">page.</span></p><p><span
  m="624200">Each</span> <span m="624558">page</span> <span m="624917">table</span>
  <span m="625276">entry</span> <span m="625635">includes</span> <span m="625994">a</span>
  <span m="626352">dirty</span> <span m="626711">bit</span> <span m="627070">(D),</span>
  <span m="627429">a</span> <span m="627788">resident</span> <span m="628147">bit</span>
  <span m="628505">(R)</span> <span m="628864">and</span> <span m="629223">a</span>
  <span m="629582">3-bit</span> <span m="629941">physical</span> <span m="630300">page</span>
  <span m="630732">number,</span> <span m="631165">for</span> <span m="631597">a</span>
  <span m="632030">total</span> <span m="632462">of</span> <span m="632895">5</span>
  <span m="633327">bits.</span></p><p><span m="633760">So</span> <span m="634181">the</span>
  <span m="634602">page</span> <span m="635023">map</span> <span m="635444">has</span>
  <span m="635865">16</span> <span m="636286">entries,</span> <span m="636707">each</span>
  <span m="637128">with</span> <span m="637550">5-bits,</span> <span m="637971">for</span>
  <span m="638392">a</span> <span m="638813">total</span> <span m="639234">of</span>
  <span m="639655">16*5</span> <span m="640076">=</span> <span m="640497">80</span>
  <span m="640918">bits.</span></p><p><span m="641340">The</span> <span m="641610">first</span>
  <span m="641881">entry</span> <span m="642151">in</span> <span m="642422">the</span>
  <span m="642693">table</span> <span m="642963">is</span> <span m="643234">for</span>
  <span m="643505">virtual</span> <span m="643775">page</span> <span m="644046">0,</span>
  <span m="644317">the</span> <span m="644587">second</span> <span m="644858">entry</span>
  <span m="645129">for</span> <span m="645399">virtual</span> <span m="645670">page</span>
  <span m="645941">1,</span> <span m="646785">and</span> <span m="647630">so</span>
  <span m="648475">on.</span></p><p><span m="649320">In</span> <span m="649591">the</span>
  <span m="649863">middle</span> <span m="650135">of</span> <span m="650407">the</span>
  <span m="650679">slide</span> <span m="650951">there's</span> <span m="651223">a</span>
  <span m="651495">diagram</span> <span m="651766">of</span> <span m="652038">physical</span>
  <span m="652310">memory</span> <span m="652582">showing</span> <span m="652854">the</span>
  <span m="653126">8</span> <span m="653398">physical</span> <span m="653670">pages.</span></p><p><span
  m="654980">The</span> <span m="655410">annotation</span> <span m="655841">for</span>
  <span m="656272">each</span> <span m="656702">physical</span> <span m="657133">page</span>
  <span m="657564">shows</span> <span m="657995">the</span> <span m="658425">virtual</span>
  <span m="658856">page</span> <span m="659287">number</span> <span m="659717">of</span>
  <span m="660148">its</span> <span m="660579">contents.</span></p><p><span m="661010">Note</span>
  <span m="661284">that</span> <span m="661559">there's</span> <span m="661833">no</span>
  <span m="662108">particular</span> <span m="662383">order</span> <span m="662657">to</span>
  <span m="662932">how</span> <span m="663206">virtual</span> <span m="663481">pages</span>
  <span m="663756">are</span> <span m="664030">stored</span> <span m="664305">in</span>
  <span m="664579">physical</span> <span m="664854">memory</span> <span m="665129">-</span>
  <span m="665481">which</span> <span m="665833">page</span> <span m="666186">holds</span>
  <span m="666538">what</span> <span m="666890">is</span> <span m="667243">determined</span>
  <span m="667595">by</span> <span m="667947">which</span> <span m="668300">pages</span>
  <span m="668633">are</span> <span m="668966">free</span> <span m="669299">at</span>
  <span m="669632">the</span> <span m="669965">time</span> <span m="670298">of</span>
  <span m="670631">a</span> <span m="670964">page</span> <span m="671297">fault.</span></p><p><span
  m="671630">In</span> <span m="671918">general,</span> <span m="672207">after</span>
  <span m="672496">the</span> <span m="672785">program</span> <span m="673074">has</span>
  <span m="673362">run</span> <span m="673651">for</span> <span m="673940">a</span>
  <span m="674229">while,</span> <span m="674518">we'd</span> <span m="674807">expected</span>
  <span m="675095">to</span> <span m="675384">find</span> <span m="675673">the</span>
  <span m="675962">sort</span> <span m="676251">of</span> <span m="676540">jumbled</span>
  <span m="677244">ordering</span> <span m="677948">we</span> <span m="678652">see</span>
  <span m="679356">here.</span></p><p><span m="680060">Let's</span> <span m="680487">follow</span>
  <span m="680915">along</span> <span m="681343">as</span> <span m="681771">the</span>
  <span m="682199">MMU</span> <span m="682627">handles</span> <span m="683055">the</span>
  <span m="683482">request</span> <span m="683910">for</span> <span m="684338">virtual</span>
  <span m="684766">address</span> <span m="685194">0x2C8,</span> <span m="685622">generated</span>
  <span m="686050">by</span> <span m="686517">the</span> <span m="686985">execution</span>
  <span m="687453">of</span> <span m="687921">the</span> <span m="688388">LD</span>
  <span m="688856">instruction</span> <span m="689324">shown</span> <span m="689792">here.</span></p><p><span
  m="690260">Splitting</span> <span m="690626">the</span> <span m="690992">virtual</span>
  <span m="691358">address</span> <span m="691724">into</span> <span m="692090">page</span>
  <span m="692456">number</span> <span m="692822">and</span> <span m="693188">offset,</span>
  <span m="693555">we</span> <span m="693921">see</span> <span m="694287">that</span>
  <span m="694653">the</span> <span m="695019">VPN</span> <span m="695385">is</span>
  <span m="695751">2</span> <span m="696117">and</span> <span m="696483">the</span>
  <span m="696850">offset</span> <span m="697930">is</span> <span m="699010">0xC8.</span></p><p><span
  m="700090">Looking</span> <span m="700410">at</span> <span m="700730">the</span>
  <span m="701050">page</span> <span m="701370">map</span> <span m="701690">entry</span>
  <span m="702010">with</span> <span m="702330">index</span> <span m="702650">2,</span>
  <span m="702970">we</span> <span m="703290">see</span> <span m="703610">that</span>
  <span m="703930">the</span> <span m="704250">R</span> <span m="704570">bit</span>
  <span m="704890">is</span> <span m="705210">1,</span> <span m="705530">indicating</span>
  <span m="705850">that</span> <span m="706170">virtual</span> <span m="706685">page</span>
  <span m="707200">2</span> <span m="707715">is</span> <span m="708230">resident</span>
  <span m="708745">in</span> <span m="709260">physical</span> <span m="709775">memory.</span></p><p><span
  m="710290">The</span> <span m="710726">PPN</span> <span m="711163">field</span>
  <span m="711599">of</span> <span m="712036">entry</span> <span m="712473">tells</span>
  <span m="712909">us</span> <span m="713346">that</span> <span m="713782">virtual</span>
  <span m="714219">page</span> <span m="714656">2</span> <span m="715092">can</span>
  <span m="715529">be</span> <span m="715965">found</span> <span m="716402">in</span>
  <span m="716839">physical</span> <span m="717275">page</span> <span m="717712">4.</span></p><p><span
  m="718149">Combining</span> <span m="718557">the</span> <span m="718965">PPN</span>
  <span m="719373">with</span> <span m="719781">the</span> <span m="720189">8-bit</span>
  <span m="720597">offset,</span> <span m="721005">we</span> <span m="721413">find</span>
  <span m="721821">that</span> <span m="722229">the</span> <span m="722637">contents</span>
  <span m="723045">of</span> <span m="723453">virtual</span> <span m="723861">address</span>
  <span m="724270">0x2C8</span> <span m="724897">can</span> <span m="725525">be</span>
  <span m="726153">found</span> <span m="726781">in</span> <span m="727408">main</span>
  <span m="728036">memory</span> <span m="728664">location</span> <span m="729292">0x4C8.</span></p><p><span
  m="729920">Note</span> <span m="730234">that</span> <span m="730549">the</span>
  <span m="730863">offset</span> <span m="731178">is</span> <span m="731492">unchanged</span>
  <span m="731807">by</span> <span m="732121">the</span> <span m="732436">translation</span>
  <span m="732750">process</span> <span m="733065">-</span> <span m="733380">the</span>
  <span m="733688">offset</span> <span m="733996">into</span> <span m="734304">the</span>
  <span m="734612">physical</span> <span m="734921">page</span> <span m="735229">is</span>
  <span m="735537">always</span> <span m="735845">the</span> <span m="736154">same</span>
  <span m="736462">as</span> <span m="736770">the</span> <span m="737078">offset</span>
  <span m="737387">into</span> <span m="737695">the</span> <span m="738003">virtual</span>
  <span m="738311">page.</span></p>
type: course
uid: 1b47d2851e468b81e08b8ec073bb5554

---
None