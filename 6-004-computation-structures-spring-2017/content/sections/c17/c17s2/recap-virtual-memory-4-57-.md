---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: muLn57VrGAA
  parent_uid: 21beb65c5b0da88cfe590c069d9b79ef
  title: Video-YouTube-Stream
  type: Video
  uid: 2471a2241d09f2df9a74fe42cc2bd367
- id: 3Play-3Play YouTube id-Stream
  media_location: muLn57VrGAA
  parent_uid: 21beb65c5b0da88cfe590c069d9b79ef
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 7c5e9884e20db9e215020e56205ec482
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/muLn57VrGAA/default.jpg
  parent_uid: 21beb65c5b0da88cfe590c069d9b79ef
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 60ae490138c01fb35b9fe7a68bcd0e3c
- id: muLn57VrGAA.srt
  parent_uid: 21beb65c5b0da88cfe590c069d9b79ef
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/recap-virtual-memory-4-57-/muLn57VrGAA.srt
  title: 3play caption file
  type: null
  uid: 2f91dde4e9a5d89ac2c754b13219dc3b
- id: muLn57VrGAA.pdf
  parent_uid: 21beb65c5b0da88cfe590c069d9b79ef
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/recap-virtual-memory-4-57-/muLn57VrGAA.pdf
  title: 3play pdf file
  type: null
  uid: 3b65d1fe754bcb9e2ecb3982b90f7285
- id: Caption-3Play YouTube id-SRT
  parent_uid: 21beb65c5b0da88cfe590c069d9b79ef
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 2554984f7752c961e40314ecbbd7ec71
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 21beb65c5b0da88cfe590c069d9b79ef
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 37805309980e966d626a16cb23abfdaa
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_17-02-01_300k.mp4
  parent_uid: 21beb65c5b0da88cfe590c069d9b79ef
  title: Video-Internet Archive-MP4
  type: Video
  uid: af91fbf841064e5c21c6368e5c98101b
inline_embed_id: 72103507recapvirtualmemory45797811088
layout: video
order_index: null
parent_uid: 4ee7d448d42f22acfa6cf0c41a85fe4f
related_resources_text: ''
short_url: recap-virtual-memory-4-57-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/recap-virtual-memory-4-57-
template_type: Embed
title: 'Recap: Virtual Memory'
transcript: <p><span m="320">In</span> <span m="740">the</span> <span m="820">last</span>
  <span m="1180">lecture</span> <span m="1590">we</span> <span m="1800">introduced</span>
  <span m="2340">the</span> <span m="2420">notion</span> <span m="2910">of</span>
  <span m="3040">virtual</span> <span m="3510">memory</span> <span m="4140">and</span>
  <span m="4470">added</span> <span m="4880">a</span> <span m="4960">Memory</span>
  <span m="5300">Management</span> <span m="5800">Unit</span> <span m="6210">(MMU)</span>
  <span m="7130">to</span> <span m="7450">translate</span> <span m="8039">the</span>
  <span m="8150">virtual</span> <span m="8670">addresses</span> <span m="9200">generated</span>
  <span m="9690">by</span> <span m="9810">the</span> <span m="9920">CPU</span> <span
  m="10140">to</span> <span m="10800">the</span> <span m="11110">physical</span> <span
  m="11640">addresses</span> <span m="12110">sent</span> <span m="12540">to</span>
  <span m="12750">main</span> <span m="13030">memory.</span></p><p><span m="14270">This</span>
  <span m="14500">gave</span> <span m="14710">us</span> <span m="14910">the</span>
  <span m="15040">ability</span> <span m="15520">to</span> <span m="15640">share</span>
  <span m="16040">physical</span> <span m="16460">memory</span> <span m="16810">between</span>
  <span m="17210">many</span> <span m="17480">running</span> <span m="17820">programs</span>
  <span m="18660">while</span> <span m="18970">still</span> <span m="19300">giving</span>
  <span m="19560">each</span> <span m="19800">program</span> <span m="20280">the</span>
  <span m="20440">illusion</span> <span m="20880">of</span> <span m="21000">having</span>
  <span m="21400">its</span> <span m="21600">own</span> <span m="22040">large</span>
  <span m="22450">address</span> <span m="22880">space.</span></p><p><span m="24580">Both</span>
  <span m="24880">the</span> <span m="24990">virtual</span> <span m="25540">and</span>
  <span m="25720">physical</span> <span m="26240">address</span> <span m="26680">spaces</span>
  <span m="27110">are</span> <span m="27240">divided</span> <span m="27750">into</span>
  <span m="28050">a</span> <span m="28080">sequence</span> <span m="28670">of</span>
  <span m="28730">pages,</span> <span m="29670">each</span> <span m="30170">holding</span>
  <span m="30490">some</span> <span m="30790">fixed</span> <span m="31130">number</span>
  <span m="31460">of</span> <span m="31530">locations.</span></p><p><span m="32810">For</span>
  <span m="32980">example</span> <span m="33660">if</span> <span m="34000">each</span>
  <span m="34270">page</span> <span m="34680">holds</span> <span m="35110">2^12</span>
  <span m="35540">bytes,</span> <span m="36510">a</span> <span m="36820">32-bit</span>
  <span m="37300">address</span> <span m="38280">would</span> <span m="38560">have</span>
  <span m="39080">2^32/2^12</span> <span m="39870">=</span> <span m="40660">2^20</span>
  <span m="42870">pages.</span></p><p><span m="44760">In</span> <span m="44940">this</span>
  <span m="45120">example</span> <span m="45880">the</span> <span m="46360">32-bit</span>
  <span m="46750">address</span> <span m="47270">can</span> <span m="47390">be</span>
  <span m="47480">thought</span> <span m="47720">of</span> <span m="47890">as</span>
  <span m="48040">having</span> <span m="48360">two</span> <span m="48570">fields:</span>
  <span m="49440">a</span> <span m="49900">20-bit</span> <span m="50100">page</span>
  <span m="50490">number</span> <span m="50810">formed</span> <span m="51170">from</span>
  <span m="51320">the</span> <span m="51440">high-order</span> <span m="52020">address</span>
  <span m="52420">bits</span> <span m="53030">and</span> <span m="53550">a</span>
  <span m="53810">12-bit</span> <span m="54090">page</span> <span m="54460">offset</span>
  <span m="55230">formed</span> <span m="55730">from</span> <span m="55890">the</span>
  <span m="55950">low-order</span> <span m="56550">address</span> <span m="57000">bits.</span></p><p><span
  m="58230">This</span> <span m="58410">arrangement</span> <span m="58920">ensures</span>
  <span m="59510">that</span> <span m="59670">nearby</span> <span m="60130">data</span>
  <span m="60420">will</span> <span m="60580">be</span> <span m="60730">located</span>
  <span m="61350">on</span> <span m="61470">the</span> <span m="61540">same</span>
  <span m="61850">page.</span></p><p><span m="64140">The</span> <span m="64400">MMU</span>
  <span m="64819">translates</span> <span m="65570">virtual</span> <span m="66010">page</span>
  <span m="66390">numbers</span> <span m="66860">into</span> <span m="67120">physical</span>
  <span m="67590">page</span> <span m="67920">numbers</span> <span m="68420">using</span>
  <span m="68820">a</span> <span m="68880">page</span> <span m="69300">map.</span></p><p><span
  m="70480">Conceptually</span> <span m="71110">the</span> <span m="71210">page</span>
  <span m="71520">map</span> <span m="71860">is</span> <span m="71990">an</span> <span
  m="72190">array</span> <span m="72680">where</span> <span m="73030">each</span>
  <span m="73410">entry</span> <span m="73830">in</span> <span m="73920">the</span>
  <span m="74080">array</span> <span m="74400">contains</span> <span m="74970">a</span>
  <span m="75120">physical</span> <span m="75590">page</span> <span m="75960">number</span>
  <span m="76500">along</span> <span m="77120">with</span> <span m="77260">a</span>
  <span m="77330">couple</span> <span m="77820">of</span> <span m="78020">bits</span>
  <span m="78420">indicating</span> <span m="79020">the</span> <span m="79120">page</span>
  <span m="79520">status.</span></p><p><span m="81470">The</span> <span m="81550">translation</span>
  <span m="82310">process</span> <span m="82900">is</span> <span m="82970">simple:</span>
  <span m="83710">the</span> <span m="84110">virtual</span> <span m="84570">page</span>
  <span m="84910">number</span> <span m="85270">is</span> <span m="85400">used</span>
  <span m="85670">as</span> <span m="85830">an</span> <span m="85960">index</span>
  <span m="86500">into</span> <span m="86730">the</span> <span m="86880">array</span>
  <span m="87280">to</span> <span m="87400">fetch</span> <span m="87730">the</span>
  <span m="87830">corresponding</span> <span m="88660">physical</span> <span m="89130">page</span>
  <span m="89440">number.</span></p><p><span m="90920">The</span> <span m="91010">physical</span>
  <span m="91480">page</span> <span m="91820">number</span> <span m="92140">is</span>
  <span m="92270">then</span> <span m="92460">combined</span> <span m="93090">with</span>
  <span m="93230">the</span> <span m="93290">page</span> <span m="93650">offset</span>
  <span m="94360">to</span> <span m="94650">form</span> <span m="95010">the</span>
  <span m="95100">complete</span> <span m="95750">physical</span> <span m="96300">address.</span></p><p><span
  m="98670">In</span> <span m="98750">the</span> <span m="98910">actual</span> <span
  m="99330">implementation</span> <span m="100030">the</span> <span m="100100">page</span>
  <span m="100410">map</span> <span m="100680">is</span> <span m="100780">usually</span>
  <span m="101120">organized</span> <span m="101810">into</span> <span m="102010">multiple</span>
  <span m="102510">levels,</span> <span m="103060">which</span> <span m="103400">permits</span>
  <span m="103820">us</span> <span m="104060">to</span> <span m="104160">have</span>
  <span m="104410">resident</span> <span m="105110">only</span> <span m="105500">the</span>
  <span m="105600">portion</span> <span m="106020">of</span> <span m="106100">the</span>
  <span m="106190">page</span> <span m="106650">map</span> <span m="107200">we&rsquo;re</span>
  <span m="107660">actively</span> <span m="108180">using.</span></p><p><span m="110060">And</span>
  <span m="110190">to</span> <span m="110310">avoid</span> <span m="110700">the</span>
  <span m="110780">costs</span> <span m="111200">of</span> <span m="111340">accessing</span>
  <span m="111880">the</span> <span m="111970">page</span> <span m="112260">map</span>
  <span m="112580">on</span> <span m="112780">each</span> <span m="113120">address</span>
  <span m="113720">translation,</span> <span m="114680">we</span> <span m="115060">use</span>
  <span m="115260">a</span> <span m="115300">cache</span> <span m="116080">(called</span>
  <span m="116640">the</span> <span m="116710">translation</span> <span m="117420">look-aside</span>
  <span m="117950">buffer)</span> <span m="118500">to</span> <span m="118870">remember</span>
  <span m="119300">the</span> <span m="119390">results</span> <span m="119960">of</span>
  <span m="120080">recent</span> <span m="120870">vpn-to-ppn</span> <span m="121910">translations.</span></p><p><span
  m="124460">All</span> <span m="124780">allocated</span> <span m="125340">locations</span>
  <span m="126030">of</span> <span m="126160">each</span> <span m="126470">virtual</span>
  <span m="126890">address</span> <span m="127260">space</span> <span m="127580">can</span>
  <span m="127720">be</span> <span m="127840">found</span> <span m="128169">on</span>
  <span m="128259">secondary</span> <span m="128759">storage.</span></p><p><span m="130340">Note</span>
  <span m="130600">that</span> <span m="130759">they</span> <span m="130930">may</span>
  <span m="131120">not</span> <span m="131480">necessarily</span> <span m="132270">be</span>
  <span m="132450">resident</span> <span m="132980">in</span> <span m="133090">main</span>
  <span m="133310">memory.</span></p><p><span m="134290">If</span> <span m="134510">the</span>
  <span m="134700">CPU</span> <span m="134980">attempts</span> <span m="135390">to</span>
  <span m="135490">access</span> <span m="136240">a</span> <span m="136320">virtual</span>
  <span m="136840">address</span> <span m="137370">that&rsquo;s</span> <span m="137560">not</span>
  <span m="137860">resident</span> <span m="138290">in</span> <span m="138350">main</span>
  <span m="138630">memory,</span> <span m="139300">a</span> <span m="139580">page</span>
  <span m="139970">fault</span> <span m="140250">is</span> <span m="140340">signaled</span>
  <span m="141000">and</span> <span m="141310">the</span> <span m="141430">operating</span>
  <span m="141910">system</span> <span m="142340">will</span> <span m="142460">arrange</span>
  <span m="142840">to</span> <span m="142930">move</span> <span m="143200">the</span>
  <span m="143300">desired</span> <span m="143870">page</span> <span m="144350">from</span>
  <span m="144660">secondary</span> <span m="145310">storage</span> <span m="146050">into</span>
  <span m="146450">main</span> <span m="146700">memory.</span></p><p><span m="148070">In</span>
  <span m="148190">practice,</span> <span m="149000">only</span> <span m="149390">the</span>
  <span m="149570">active</span> <span m="149950">pages</span> <span m="150410">for</span>
  <span m="150530">each</span> <span m="150740">program</span> <span m="151400">are</span>
  <span m="151650">resident</span> <span m="152220">in</span> <span m="152400">main</span>
  <span m="152700">memory</span> <span m="153190">at</span> <span m="153350">any</span>
  <span m="153580">given</span> <span m="153900">time.</span></p><p><span m="156540">Here&rsquo;s</span>
  <span m="156760">a</span> <span m="156820">diagram</span> <span m="157440">showing</span>
  <span m="157790">the</span> <span m="157880">translation</span> <span m="158550">process.</span></p><p><span
  m="159710">First</span> <span m="160000">we</span> <span m="160090">check</span>
  <span m="160360">to</span> <span m="160460">see</span> <span m="160700">if</span>
  <span m="160800">the</span> <span m="160880">required</span> <span m="161560">vpn-to-ppn</span>
  <span m="162400">mapping</span> <span m="163110">is</span> <span m="163230">cached</span>
  <span m="163750">in</span> <span m="163840">the</span> <span m="163900">TLB.</span></p><p><span
  m="165450">If</span> <span m="165630">not,</span> <span m="165880">we</span> <span
  m="166040">have</span> <span m="166270">to</span> <span m="166370">access</span>
  <span m="167000">the</span> <span m="167080">hierarchical</span> <span m="167790">page</span>
  <span m="168140">map</span> <span m="168450">to</span> <span m="168540">see</span>
  <span m="168740">if</span> <span m="168840">the</span> <span m="168920">page</span>
  <span m="169260">is</span> <span m="169360">resident</span> <span m="170000">and,</span>
  <span m="170550">if</span> <span m="170780">so,</span> <span m="171380">lookup</span>
  <span m="171890">its</span> <span m="172050">physical</span> <span m="172430">page</span>
  <span m="172760">number.</span></p><p><span m="173880">If</span> <span m="174010">we</span>
  <span m="174100">discover</span> <span m="174600">that</span> <span m="174750">the</span>
  <span m="174850">page</span> <span m="175180">is</span> <span m="175320">not</span>
  <span m="175630">resident,</span> <span m="176280">a</span> <span m="176490">page</span>
  <span m="176870">fault</span> <span m="177090">exception</span> <span m="177650">is</span>
  <span m="177750">signaled</span> <span m="178220">to</span> <span m="178390">the</span>
  <span m="178560">CPU</span> <span m="179060">so</span> <span m="179400">that</span>
  <span m="179540">it</span> <span m="179610">can</span> <span m="179720">run</span>
  <span m="179970">a</span> <span m="180010">handler</span> <span m="180650">to</span>
  <span m="180790">load</span> <span m="181060">the</span> <span m="181130">page</span>
  <span m="181540">from</span> <span m="181710">secondary</span> <span m="182280">storage.</span></p><p><span
  m="184290">Note</span> <span m="184600">that</span> <span m="184810">access</span>
  <span m="185440">to</span> <span m="185570">a</span> <span m="185600">particular</span>
  <span m="186170">mapping</span> <span m="186580">context</span> <span m="187280">is</span>
  <span m="187450">controlled</span> <span m="187930">by</span> <span m="188180">two</span>
  <span m="188540">registers.</span></p><p><span m="189650">The</span> <span m="189720">context-number</span>
  <span m="190540">register</span> <span m="191020">controls</span> <span m="191540">which</span>
  <span m="191740">mappings</span> <span m="192190">are</span> <span m="192340">accessible</span>
  <span m="192930">in</span> <span m="193010">the</span> <span m="193080">TLB.</span></p><p><span
  m="193500">And</span> <span m="194120">the</span> <span m="194650">page-directory</span>
  <span m="195580">register</span> <span m="196170">indicates</span> <span m="196770">which</span>
  <span m="197150">physical</span> <span m="197640">page</span> <span m="198250">holds</span>
  <span m="198670">the</span> <span m="198830">top</span> <span m="199240">tier</span>
  <span m="199690">of</span> <span m="199790">the</span> <span m="199890">hierarchical</span>
  <span m="200570">page</span> <span m="200890">map.</span></p><p><span m="202440">We</span>
  <span m="202520">can</span> <span m="202670">switch</span> <span m="203090">to</span>
  <span m="203300">another</span> <span m="203610">context</span> <span m="204340">by</span>
  <span m="204460">simply</span> <span m="204950">reloading</span> <span m="205570">these</span>
  <span m="205780">two</span> <span m="205950">registers.</span></p><p><span m="207540">To</span>
  <span m="207670">effectively</span> <span m="208310">accommodate</span> <span m="208890">multiple</span>
  <span m="209310">contexts</span> <span m="210070">we&rsquo;ll</span> <span m="210270">need</span>
  <span m="210550">to</span> <span m="210670">have</span> <span m="210980">sufficient</span>
  <span m="211710">TLB</span> <span m="212150">capacity</span> <span m="213070">to</span>
  <span m="213320">simultaneously</span> <span m="214270">cache</span> <span m="214670">the</span>
  <span m="214750">most</span> <span m="214980">frequent</span> <span m="215370">mappings</span>
  <span m="215840">for</span> <span m="216030">all</span> <span m="216230">the</span>
  <span m="216310">processes.</span></p><p><span m="217690">And</span> <span m="217960">we&rsquo;ll</span>
  <span m="218160">need</span> <span m="218380">some</span> <span m="218650">number</span>
  <span m="218970">of</span> <span m="219030">physical</span> <span m="219400">pages</span>
  <span m="219820">to</span> <span m="219930">hold</span> <span m="220130">the</span>
  <span m="220190">required</span> <span m="220800">page</span> <span m="221190">directories</span>
  <span m="222000">and</span> <span m="222250">segments</span> <span m="222800">of</span>
  <span m="222860">the</span> <span m="222950">page</span> <span m="223290">tables.</span></p><p><span
  m="224330">For</span> <span m="224500">example,</span> <span m="225060">for</span>
  <span m="225270">a</span> <span m="225300">particular</span> <span m="225780">process,</span>
  <span m="226510">three</span> <span m="226890">pages</span> <span m="227380">will</span>
  <span m="227530">suffice</span> <span m="228060">hold</span> <span m="228400">the</span>
  <span m="228530">resident</span> <span m="229040">two-level</span> <span m="229490">page</span>
  <span m="229830">map</span> <span m="230290">for</span> <span m="230630">1024</span>
  <span m="231060">pages</span> <span m="232090">at</span> <span m="232440">each</span>
  <span m="232800">end</span> <span m="233390">of</span> <span m="233720">the</span>
  <span m="233810">virtual</span> <span m="234350">address</span> <span m="234800">space,</span></p><p><span
  m="235690">providing</span> <span m="236180">access</span> <span m="236840">to</span>
  <span m="237000">up</span> <span m="237290">to</span> <span m="237610">8MB</span>
  <span m="237720">of</span> <span m="238180">code,</span> <span m="238910">stack,</span>
  <span m="239620">and</span> <span m="239810">heap,</span> <span m="240450">more</span>
  <span m="240950">than</span> <span m="241130">enough</span> <span m="241510">for</span>
  <span m="241740">many</span> <span m="241980">simple</span> <span m="242300">programs.</span></p><p><span
  m="243860">The</span> <span m="243940">page</span> <span m="244300">map</span> <span
  m="244570">creates</span> <span m="245100">the</span> <span m="245190">context</span>
  <span m="246010">needed</span> <span m="246310">to</span> <span m="246400">translate</span>
  <span m="247030">virtual</span> <span m="247450">addresses</span> <span m="247920">to</span>
  <span m="248000">physical</span> <span m="248440">addresses.</span></p><p><span
  m="249760">In</span> <span m="249830">a</span> <span m="249880">computer</span>
  <span m="250350">system</span> <span m="250740">that&rsquo;s</span> <span m="250980">working</span>
  <span m="251340">on</span> <span m="251470">multiple</span> <span m="251940">tasks</span>
  <span m="252360">at</span> <span m="252420">the</span> <span m="252510">same</span>
  <span m="252810">time,</span> <span m="253380">we</span> <span m="253640">would</span>
  <span m="253820">like</span> <span m="254120">to</span> <span m="254310">support</span>
  <span m="254890">multiple</span> <span m="255340">contexts</span> <span m="256200">and</span>
  <span m="256500">to</span> <span m="256630">be</span> <span m="256790">able</span>
  <span m="257010">to</span> <span m="257250">quickly</span> <span m="257720">switch</span>
  <span m="258149">from</span> <span m="258370">one</span> <span m="258600">context</span>
  <span m="259350">to</span> <span m="259430">another.</span></p><p><span m="261149">Multiple</span>
  <span m="261570">contexts</span> <span m="262240">would</span> <span m="262360">allow</span>
  <span m="262710">us</span> <span m="263080">to</span> <span m="263200">share</span>
  <span m="263910">physical</span> <span m="264450">memory</span> <span m="264840">between</span>
  <span m="265420">multiple</span> <span m="265900">programs.</span></p><p><span m="267580">Each</span>
  <span m="267810">program</span> <span m="268370">would</span> <span m="268490">have</span>
  <span m="268680">an</span> <span m="268780">independent</span> <span m="269500">virtual</span>
  <span m="269880">address</span> <span m="270250">space,</span> <span m="270940">e.g.,</span>
  <span m="271680">two</span> <span m="272070">programs</span> <span m="272620">could</span>
  <span m="272740">both</span> <span m="273040">access</span> <span m="273580">virtual</span>
  <span m="274030">address</span> <span m="274360">0</span> <span m="274410">as</span>
  <span m="274610">the</span> <span m="274730">address</span> <span m="275160">of</span>
  <span m="275260">their</span> <span m="275350">first</span> <span m="275640">instruction</span>
  <span m="276620">and</span> <span m="277220">would</span> <span m="277430">end</span>
  <span m="277730">up</span> <span m="277950">accessing</span> <span m="278660">different</span>
  <span m="279050">physical</span> <span m="279550">locations</span> <span m="280190">in</span>
  <span m="280300">main</span> <span m="280550">memory.</span></p><p><span m="282050">When</span>
  <span m="282250">switching</span> <span m="282700">between</span> <span m="283120">programs,</span>
  <span m="283850">we&rsquo;d</span> <span m="284060">perform</span> <span m="284450">a</span>
  <span m="284480">&ldquo;context</span> <span m="285240">switch&rdquo;</span> <span
  m="285570">to</span> <span m="285680">move</span> <span m="286010">to</span> <span
  m="286150">the</span> <span m="286360">appropriate</span> <span m="287180">MMU</span>
  <span m="287610">context.</span></p><p><span m="289600">The</span> <span m="289750">ability</span>
  <span m="290230">to</span> <span m="290340">share</span> <span m="290650">the</span>
  <span m="290750">CPU</span> <span m="291250">between</span> <span m="291620">many</span>
  <span m="291880">programs</span> <span m="292490">seems</span> <span m="292750">like</span>
  <span m="292910">a</span> <span m="292980">great</span> <span m="293240">idea!</span></p><p><span
  m="294440">Let&rsquo;s</span> <span m="294740">figure</span> <span m="295080">out</span>
  <span m="295210">the</span> <span m="295300">details</span> <span m="295930">of</span>
  <span m="296030">how</span> <span m="296250">that</span> <span m="296450">might</span>
  <span m="296670">work&hellip;</span></p>
type: course
uid: 21beb65c5b0da88cfe590c069d9b79ef

---
None