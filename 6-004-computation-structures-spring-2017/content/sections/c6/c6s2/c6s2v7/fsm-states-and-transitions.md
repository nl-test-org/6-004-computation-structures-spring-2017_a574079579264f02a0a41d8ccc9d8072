---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: Sj18t7hdbt8
  parent_uid: 6e52f4cb5157b249280d2c8dc77638e0
  title: Video-YouTube-Stream
  type: Video
  uid: 883b9bb34e7ccf13ab9acf0d4fbd5f03
- id: 3Play-3Play YouTube id-Stream
  media_location: Sj18t7hdbt8
  parent_uid: 6e52f4cb5157b249280d2c8dc77638e0
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 15f20c03299f5c53584dbde03bb35fb4
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/Sj18t7hdbt8/default.jpg
  parent_uid: 6e52f4cb5157b249280d2c8dc77638e0
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e5ab14f006d276d19eed64d7317938d5
- id: Sj18t7hdbt8.srt
  parent_uid: 6e52f4cb5157b249280d2c8dc77638e0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v7/fsm-states-and-transitions/Sj18t7hdbt8.srt
  title: 3play caption file
  type: null
  uid: 877d6b722f7250f9f85d90b6ad3841b9
- id: Sj18t7hdbt8.pdf
  parent_uid: 6e52f4cb5157b249280d2c8dc77638e0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v7/fsm-states-and-transitions/Sj18t7hdbt8.pdf
  title: 3play pdf file
  type: null
  uid: f8d5e9b17067d6285b299ba3bae5f257
- id: Caption-3Play YouTube id-SRT
  parent_uid: 6e52f4cb5157b249280d2c8dc77638e0
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 7d65cc8effc319e116cdddc74d0ad2f7
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 6e52f4cb5157b249280d2c8dc77638e0
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: dfd3e756aa31b4024b497d1ee10e8929
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_06-02-07-01_300k.mp4
  parent_uid: 6e52f4cb5157b249280d2c8dc77638e0
  title: Video-Internet Archive-MP4
  type: Video
  uid: 833e37cf5cc5e27ca94d3eb161b7ac84
inline_embed_id: 40306241fsmstatesandtransitions64380451
layout: video
order_index: null
parent_uid: bbf08387222da03d382e8d79c93d9090
related_resources_text: ''
short_url: fsm-states-and-transitions
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v7/fsm-states-and-transitions
template_type: Embed
title: 'Worked Example: FSM States and Transitions'
transcript: <p><span m="1270">PROFESSOR:</span> <span m="1420">This</span> <span m="1570">truth</span>
  <span m="1960">table</span> <span m="2560">represents</span> <span m="3190">a</span>
  <span m="3250">five-state</span> <span m="4090">finite</span> <span m="4630">state</span>
  <span m="4930">machine,</span> <span m="5890">or</span> <span m="6070">FSM,</span>
  <span m="7240">with</span> <span m="7450">a</span> <span m="7540">one-bit</span>
  <span m="8050">input,</span> <span m="8610">IN,</span> <span m="8960">and</span>
  <span m="9250">a</span> <span m="9310">two-bit</span> <span m="9820">output,</span>
  <span m="10350">OUT.</span> <span m="11530">This</span> <span m="11770">FSM</span>
  <span m="12430">is</span> <span m="12640">a</span> <span m="12670">Mealy</span>
  <span m="13090">machine.</span> <span m="14210">That</span> <span m="14320">means</span>
  <span m="14620">that</span> <span m="14770">its</span> <span m="14980">outputs</span>
  <span m="15550">are</span> <span m="15670">a</span> <span m="15700">function</span>
  <span m="16210">of</span> <span m="16329">both</span> <span m="16660">the</span>
  <span m="16750">current</span> <span m="17170">state</span> <span m="17800">and</span>
  <span m="18040">the</span> <span m="18160">current</span> <span m="18610">input.</span></p><p><span
  m="20040">When</span> <span m="20190">this</span> <span m="20400">FSM</span> <span
  m="20880">is</span> <span m="21000">initialized,</span> <span m="21900">its</span>
  <span m="22050">starting</span> <span m="22530">state</span> <span m="23040">is</span>
  <span m="23160">state</span> <span m="23520">B.</span> <span m="24960">We</span>
  <span m="25080">are</span> <span m="25200">given</span> <span m="25620">a</span>
  <span m="25680">partially</span> <span m="26310">filled</span> <span m="26730">state</span>
  <span m="27060">transition</span> <span m="27750">diagram</span> <span m="28380">shown</span>
  <span m="28740">here.</span> <span m="29820">Our</span> <span m="29910">job</span>
  <span m="30480">is</span> <span m="30660">to</span> <span m="30750">fill</span>
  <span m="31020">in</span> <span m="31140">the</span> <span m="31230">missing</span>
  <span m="31650">state</span> <span m="32070">and</span> <span m="32220">transition</span>
  <span m="32880">labels.</span> <span m="33930">In</span> <span m="34110">other</span>
  <span m="34350">words,</span> <span m="34980">S1</span> <span m="35520">through</span>
  <span m="35960">S4</span> <span m="36840">should</span> <span m="37080">be</span>
  <span m="37200">replaced</span> <span m="37740">with</span> <span m="37910">the</span>
  <span m="37980">states</span> <span m="38490">A</span> <span m="38700">through</span>
  <span m="39030">E.</span> <span m="39466">And</span> <span m="39902">T1</span> <span
  m="40620">through</span> <span m="40890">T7</span> <span m="41850">should</span>
  <span m="42090">be</span> <span m="42210">replaced</span> <span m="42840">with</span>
  <span m="43050">a</span> <span m="43190">IN/OUT</span> <span m="44220">transition</span>
  <span m="45000">corresponding</span> <span m="45780">to</span> <span m="45990">that</span>
  <span m="46230">arrow.</span></p><p><span m="49420">In</span> <span m="49570">order</span>
  <span m="49870">to</span> <span m="49990">do</span> <span m="50230">this,</span>
  <span m="51050">we</span> <span m="51070">begin</span> <span m="51430">by</span>
  <span m="51580">looking</span> <span m="51970">at</span> <span m="52090">the</span>
  <span m="52180">truth</span> <span m="52510">table,</span> <span m="53320">beginning</span>
  <span m="53740">with</span> <span m="53900">the</span> <span m="53980">starting</span>
  <span m="54430">state</span> <span m="54820">B.</span> <span m="56260">The</span>
  <span m="56350">truth</span> <span m="56680">table</span> <span m="57070">shows</span>
  <span m="57490">us</span> <span m="57790">that</span> <span m="57940">when</span>
  <span m="58150">IN</span> <span m="58390">equals</span> <span m="58720">0,</span>
  <span m="59560">our</span> <span m="59710">next</span> <span m="60010">state</span>
  <span m="60400">is</span> <span m="60520">state</span> <span m="60880">C.</span>
  <span m="62080">Since</span> <span m="62410">the</span> <span m="62500">0</span>
  <span m="62950">input</span> <span m="63250">transition</span> <span m="64180">out</span>
  <span m="64480">of state</span> <span m="64780">B</span> <span m="65290">is</span>
  <span m="65500">already</span> <span m="65920">labeled</span> <span m="66310">for</span>
  <span m="66550">us,</span> <span m="67300">we</span> <span m="67450">know</span>
  <span m="67690">that</span> <span m="67960">state</span> <span m="68380">S2</span>
  <span m="69130">equals</span> <span m="69490">C.</span> <span m="71410">This</span>
  <span m="71770">also</span> <span m="72130">tells</span> <span m="72520">us</span>
  <span m="73120">that</span> <span m="73420">T2</span> <span m="74170">corresponds</span>
  <span m="74920">to</span> <span m="75070">IN</span> <span m="75340">equals</span>
  <span m="75790">1.</span> <span m="77150">So</span> <span m="77350">S4</span> <span
  m="78400">is</span> <span m="78580">equal</span> <span m="78940">to</span> <span
  m="79120">D.</span> <span m="80380">And</span> <span m="80990">T2</span> <span m="81910">is</span>
  <span m="82120">equal</span> <span m="82480">to</span> <span m="82720">1/00.</span></p><p><span
  m="86110">From</span> <span m="86360">state</span> <span m="86740">D,</span> <span
  m="88150">we</span> <span m="88330">have</span> <span m="88570">the</span> <span
  m="88690">one</span> <span m="89020">input</span> <span m="89380">transition</span>
  <span m="90190">already</span> <span m="90670">labeled.</span> <span m="91840">So</span>
  <span m="92080">T3</span> <span m="93190">corresponds</span> <span m="94030">to</span>
  <span m="94270">IN</span> <span m="94570">equals</span> <span m="94960">0.</span>
  <span m="96400">Looking</span> <span m="96760">at</span> <span m="96880">the</span>
  <span m="96970">truth</span> <span m="97360">table,</span> <span m="98350">that</span>
  <span m="98590">means</span> <span m="98950">that</span> <span m="99490">S3</span>
  <span m="100360">equals</span> <span m="100930">E</span> <span m="101770">and</span>
  <span m="102190">T3</span> <span m="103300">equals</span> <span m="104260">0/01.</span>
  <span m="107330">The</span> <span m="107450">truth</span> <span m="107810">table</span>
  <span m="108680">then</span> <span m="108950">shows</span> <span m="109400">us</span>
  <span m="109590">that</span> <span m="109790">from</span> <span m="110000">state</span>
  <span m="110480">E,</span> <span m="111260">a</span> <span m="111350">1</span> <span
  m="111740">input</span> <span m="112340">takes</span> <span m="112670">you</span>
  <span m="112760">back</span> <span m="113120">to</span> <span m="113270">state</span>
  <span m="113660">B.</span> <span m="114730">So</span> <span m="114980">T4</span>
  <span m="116030">equals</span> <span m="116480">1/01,</span> <span m="118700">which</span>
  <span m="118940">in</span> <span m="119030">turn</span> <span m="119360">means</span>
  <span m="119690">that</span> <span m="119870">T5</span> <span m="121100">equals</span>
  <span m="121760">0/10.</span> <span m="124130">And</span> <span m="124280">state</span>
  <span m="124700">S1</span> <span m="125720">equals</span> <span m="126260">A.</span></p><p><span
  m="127520">From</span> <span m="127730">state</span> <span m="128180">A,</span>
  <span m="129000">the</span> <span m="129199">0</span> <span m="129680">input</span>
  <span m="130070">transition</span> <span m="131030">is</span> <span m="131240">already</span>
  <span m="131690">filled</span> <span m="132080">in.</span> <span m="133250">So</span>
  <span m="133520">T1</span> <span m="134300">equals</span> <span m="135050">1/11.</span>
  <span m="137750">From</span> <span m="137960">state</span> <span m="138350">C,</span>
  <span m="139340">a</span> <span m="139430">1</span> <span m="139790">input</span>
  <span m="140360">goes</span> <span m="140690">to</span> <span m="140810">state</span>
  <span m="141290">B.</span> <span m="142490">So</span> <span m="142730">T6</span>
  <span m="143900">equals</span> <span m="144650">1/01,</span> <span m="146750">which</span>
  <span m="146960">in</span> <span m="147080">turn</span> <span m="147410">means</span>
  <span m="147920">that</span> <span m="148160">T7</span> <span m="149480">equals</span>
  <span m="150230">0/10.</span></p><p><span m="154860">Now</span> <span m="154940">that</span>
  <span m="155090">we</span> <span m="155210">have</span> <span m="155450">a</span>
  <span m="155510">complete</span> <span m="155960">state</span> <span m="156320">diagram</span>
  <span m="156920">for</span> <span m="157230">our</span> <span m="157340">FSM,</span>
  <span m="158600">the</span> <span m="158720">next</span> <span m="159050">thing</span>
  <span m="159260">we</span> <span m="159380">want</span> <span m="159620">to</span>
  <span m="159710">figure</span> <span m="160100">out</span> <span m="160580">is</span>
  <span m="160790">what</span> <span m="161030">sequence</span> <span m="161480">of</span>
  <span m="161660">outputs</span> <span m="162230">is</span> <span m="162410">produced</span>
  <span m="163130">if</span> <span m="163310">we</span> <span m="163460">begin</span>
  <span m="163820">in</span> <span m="163940">state</span> <span m="164330">B</span>
  <span m="165140">and</span> <span m="165260">receive</span> <span m="165710">inputs</span>
  <span m="166220">1,</span> <span m="166580">0,</span> <span m="167050">0.</span>
  <span m="168620">Since</span> <span m="168950">our</span> <span m="169070">state</span>
  <span m="169400">transition</span> <span m="170000">diagram</span> <span m="170600">is</span>
  <span m="170720">now</span> <span m="170960">filled,</span> <span m="171860">we</span>
  <span m="172010">see</span> <span m="172250">that</span> <span m="172490">from</span>
  <span m="172730">state</span> <span m="173090">B,</span> <span m="173720">a</span>
  <span m="173810">1</span> <span m="174140">input</span> <span m="174710">takes</span>
  <span m="175070">us</span> <span m="175220">to</span> <span m="175310">state</span>
  <span m="175730">D</span> <span m="176450">and</span> <span m="176600">produces</span>
  <span m="177200">a</span> <span m="177260">00</span> <span m="178160">output.</span>
  <span m="180600">From</span> <span m="180840">state</span> <span m="181190">D,</span>
  <span m="181850">a</span> <span m="182000">0</span> <span m="182460">input</span>
  <span m="183090">moves</span> <span m="183390">us</span> <span m="183690">to</span>
  <span m="183840">state</span> <span m="184350">E</span> <span m="184830">and</span>
  <span m="184980">outputs</span> <span m="185460">01.</span> <span m="186970">Finally,</span>
  <span m="187470">from</span> <span m="187740">state</span> <span m="188160">E,</span>
  <span m="188840">a</span> <span m="188960">0</span> <span m="189420">input</span>
  <span m="190110">moves</span> <span m="190470">us</span> <span m="190650">to</span>
  <span m="190770">state</span> <span m="191220">A</span> <span m="191505">and</span>
  <span m="191790">produces</span> <span m="192540">a</span> <span m="192690">10</span>
  <span m="193440">output.</span></p><p><span m="195030">OK.</span> <span m="195900">Now</span>
  <span m="196320">let's</span> <span m="196530">try</span> <span m="196740">to</span>
  <span m="196830">find</span> <span m="197160">a</span> <span m="197220">sequence</span>
  <span m="197700">of</span> <span m="197850">inputs</span> <span m="198420">that</span>
  <span m="198600">is</span> <span m="198750">guaranteed</span> <span m="199710">to</span>
  <span m="199890">leave</span> <span m="200190">the</span> <span m="200340">FSM</span>
  <span m="200940">in</span> <span m="201030">state</span> <span m="201490">E,</span>
  <span m="202260">regardless</span> <span m="202920">of</span> <span m="203010">the</span>
  <span m="203130">state</span> <span m="203480">it is</span> <span m="203850">in</span>
  <span m="204150">before</span> <span m="204660">the</span> <span m="204780">sequence</span>
  <span m="205300">is</span> <span m="205440">processed.</span> <span m="207000">To</span>
  <span m="207150">answer</span> <span m="207510">this</span> <span m="207810">question,</span>
  <span m="208890">we</span> <span m="209010">take</span> <span m="209310">a</span>
  <span m="209370">look</span> <span m="209670">at</span> <span m="209760">our</span>
  <span m="209850">filled-in</span> <span m="210390">state</span> <span m="210750">diagram</span>
  <span m="211830">and</span> <span m="211980">determine</span> <span m="212580">what</span>
  <span m="212850">sequence</span> <span m="213330">of</span> <span m="213480">inputs</span>
  <span m="213990">takes</span> <span m="214380">us</span> <span m="214530">from</span>
  <span m="214830">each</span> <span m="215100">state</span> <span m="215520">X</span>
  <span m="215880">to</span> <span m="216030">state</span> <span m="216500">E.</span></p><p><span
  m="217530">We</span> <span m="217650">begin</span> <span m="218130">with</span>
  <span m="218280">state</span> <span m="218730">A.</span> <span m="219810">From</span>
  <span m="220020">state</span> <span m="220410">A,</span> <span m="221230">the</span>
  <span m="221370">shortest</span> <span m="221740">sequence</span> <span m="222240">of</span>
  <span m="222390">inputs</span> <span m="222900">required</span> <span m="223410">to</span>
  <span m="223560">get</span> <span m="223800">to</span> <span m="223920">state</span>
  <span m="224370">E</span> <span m="225300">is</span> <span m="225510">1,</span>
  <span m="226080">1,</span> <span m="226440">0.</span> <span m="227760">This</span>
  <span m="227970">takes</span> <span m="228330">you</span> <span m="228510">from</span>
  <span m="228870">A</span> <span m="229350">to</span> <span m="229530">B</span> <span
  m="230160">to</span> <span m="230340">D</span> <span m="230910">to</span> <span
  m="231120">E.</span> <span m="232570">Next,</span> <span m="232960">we</span> <span
  m="233110">examine</span> <span m="233590">state</span> <span m="233980">B.</span>
  <span m="235180">We</span> <span m="235300">see</span> <span m="235480">that</span>
  <span m="235660">the</span> <span m="235780">sequence</span> <span m="236380">1,</span>
  <span m="236680">0</span> <span m="237370">will</span> <span m="237580">take</span>
  <span m="237910">us</span> <span m="238090">from</span> <span m="238360">B</span>
  <span m="238720">to</span> <span m="238900">D</span> <span m="239260">to</span>
  <span m="239500">E.</span> <span m="240790">Since</span> <span m="241120">we</span>
  <span m="241240">are</span> <span m="241330">looking</span> <span m="241690">for</span>
  <span m="241870">a</span> <span m="241930">single</span> <span m="242380">sequence</span>
  <span m="243040">that</span> <span m="243250">will</span> <span m="243400">work</span>
  <span m="243700">from</span> <span m="244030">all</span> <span m="244270">states,</span>
  <span m="244930">we</span> <span m="245110">want</span> <span m="245350">to</span>
  <span m="245440">see</span> <span m="245740">if</span> <span m="245920">1,</span>
  <span m="246220">1,</span> <span m="246490">0</span> <span m="247120">would</span>
  <span m="247330">also</span> <span m="247750">work.</span></p><p><span m="248830">Taking</span>
  <span m="249190">a</span> <span m="249250">closer</span> <span m="249730">look</span>
  <span m="250120">at</span> <span m="250210">state</span> <span m="250570">D</span>
  <span m="251510">shows</span> <span m="252010">us</span> <span m="252190">that</span>
  <span m="252340">the</span> <span m="252460">sequence</span> <span m="253030">1,</span>
  <span m="253300">1,</span> <span m="253570">0</span> <span m="254170">will</span>
  <span m="254380">also</span> <span m="254890">get</span> <span m="255130">us</span>
  <span m="255340">from</span> <span m="255580">B</span> <span m="255820">to</span>
  <span m="256029">E</span> <span m="256720">because</span> <span m="257110">the</span>
  <span m="257230">extra</span> <span m="257649">1</span> <span m="258130">just</span>
  <span m="258399">keeps</span> <span m="258760">you</span> <span m="258880">in</span>
  <span m="259000">state</span> <span m="259390">D</span> <span m="259779">for</span>
  <span m="259990">one</span> <span m="260320">extra</span> <span m="260769">iteration.</span>
  <span m="261940">And</span> <span m="262089">then</span> <span m="262570">the</span>
  <span m="262720">0</span> <span m="263290">takes</span> <span m="263680">you</span>
  <span m="263740">to</span> <span m="263890">state</span> <span m="264340">E.</span>
  <span m="265700">Similarly,</span> <span m="266840">if</span> <span m="267050">you</span>
  <span m="267170">begin</span> <span m="267560">at</span> <span m="267680">state</span>
  <span m="268010">D,</span> <span m="268850">the</span> <span m="268970">sequence</span>
  <span m="269540">1,</span> <span m="269840">1,</span> <span m="270110">0</span>
  <span m="270980">leaves</span> <span m="271370">you</span> <span m="271490">at</span>
  <span m="271610">state</span> <span m="272000">D</span> <span m="272240">for</span>
  <span m="272450">two</span> <span m="272750">iterations.</span> <span m="273890">And</span>
  <span m="274010">then</span> <span m="274190">on</span> <span m="274310">the</span>
  <span m="274430">third,</span> <span m="275210">the</span> <span m="275390">0</span>
  <span m="275810">takes</span> <span m="276170">you</span> <span m="276260">to</span>
  <span m="276380">state</span> <span m="276860">E.</span></p><p><span m="278520">Beginning</span>
  <span m="279030">at</span> <span m="279150">state</span> <span m="279560">E</span>
  <span m="279760">itself,</span> <span m="280790">the</span> <span m="280950">sequence</span>
  <span m="281520">1,</span> <span m="281790">1,</span> <span m="282060">0</span>
  <span m="282720">takes</span> <span m="283110">you</span> <span m="283200">to</span>
  <span m="283290">state</span> <span m="283680">B,</span> <span m="284490">then</span>
  <span m="284820">D,</span> <span m="285480">then</span> <span m="285840">E.</span>
  <span m="287160">So</span> <span m="287340">we</span> <span m="287460">have</span>
  <span m="287640">one</span> <span m="287940">state</span> <span m="288270">left</span>
  <span m="288540">to</span> <span m="288690">check,</span> <span m="289200">and</span>
  <span m="289320">that</span> <span m="289530">is</span> <span m="289620">state</span>
  <span m="290010">C.</span> <span m="291120">From</span> <span m="291390">state</span>
  <span m="291770">C,</span> <span m="292500">the</span> <span m="292650">sequence</span>
  <span m="293190">1,</span> <span m="293400">1,</span> <span m="293640">0</span>
  <span m="294270">takes</span> <span m="294660">us</span> <span m="294780">to</span>
  <span m="294930">state</span> <span m="295320">B,</span> <span m="296040">then</span>
  <span m="296370">D,</span> <span m="296970">then</span> <span m="297390">E.</span>
  <span m="298350">So</span> <span m="298530">once</span> <span m="298830">again,</span>
  <span m="299370">the</span> <span m="299490">sequence</span> <span m="300060">1,</span>
  <span m="300300">1,</span> <span m="300570">0</span> <span m="300960">works.</span>
  <span m="301990">This</span> <span m="302160">means</span> <span m="302550">that</span>
  <span m="302730">regardless</span> <span m="303450">of</span> <span m="303570">what</span>
  <span m="303810">state</span> <span m="304080">you</span> <span m="304230">start</span>
  <span m="304650">in,</span> <span m="305160">the</span> <span m="305250">sequence</span>
  <span m="305820">1,</span> <span m="306090">1,</span> <span m="306360">0</span>
  <span m="307140">will</span> <span m="307290">have</span> <span m="307530">you</span>
  <span m="307680">end</span> <span m="307930">at</span> <span m="308130">state</span>
  <span m="308710">E.</span></p><p><span m="310570">The</span> <span m="310660">last</span>
  <span m="310960">question</span> <span m="311320">we</span> <span m="311470">want</span>
  <span m="311680">to</span> <span m="311830">answer</span> <span m="312340">about</span>
  <span m="312640">the</span> <span m="312820">finite</span> <span m="313300">state</span>
  <span m="313600">machine</span> <span m="314500">is</span> <span m="314680">whether</span>
  <span m="315100">or</span> <span m="315130">not</span> <span m="315460">there</span>
  <span m="315730">exists</span> <span m="316240">an</span> <span m="316360">equivalent</span>
  <span m="317140">FSM</span> <span m="318130">that</span> <span m="318280">has</span>
  <span m="318520">only</span> <span m="318790">four</span> <span m="319180">states</span>
  <span m="319720">instead</span> <span m="320140">of</span> <span m="320200">five.</span>
  <span m="321610">In</span> <span m="321790">other</span> <span m="322000">words,</span>
  <span m="322580">are</span> <span m="322600">there</span> <span m="322750">two</span>
  <span m="323080">states</span> <span m="323590">that</span> <span m="323710">can</span>
  <span m="323920">be</span> <span m="324070">merged</span> <span m="324610">into</span>
  <span m="324940">one</span> <span m="325660">to</span> <span m="325810">reduce</span>
  <span m="326290">the</span> <span m="326440">FSM</span> <span m="327010">to</span>
  <span m="327160">an</span> <span m="327280">equivalent</span> <span m="327940">FSM</span>
  <span m="328990">with</span> <span m="329170">one</span> <span m="329470">fewer</span>
  <span m="329860">state?</span></p><p><span m="331300">Recall</span> <span m="331870">that</span>
  <span m="332050">in</span> <span m="332170">a</span> <span m="332470">Mealy</span>
  <span m="332680">FSM,</span> <span m="333670">two</span> <span m="333910">states</span>
  <span m="334300">are</span> <span m="334450">equivalent</span> <span m="335380">if</span>
  <span m="335530">they</span> <span m="335710">have</span> <span m="335980">the</span>
  <span m="336100">same</span> <span m="336730">input/output</span> <span m="337930">transitions</span>
  <span m="338890">as</span> <span m="339130">each</span> <span m="339340">other.</span>
  <span m="340780">If</span> <span m="340990">it</span> <span m="341080">were</span>
  <span m="341320">a</span> <span m="341380">Moore</span> <span m="341740">FSM,</span>
  <span m="342730">then</span> <span m="342880">the</span> <span m="342970">two</span>
  <span m="343240">states</span> <span m="343690">would</span> <span m="343810">be</span>
  <span m="343960">equivalent</span> <span m="344680">if</span> <span m="344860">they</span>
  <span m="344980">produced</span> <span m="345520">the</span> <span m="345610">same</span>
  <span m="346060">output</span> <span m="346750">and</span> <span m="347140">have</span>
  <span m="347380">the</span> <span m="347500">same</span> <span m="347830">transitions.</span></p><p><span
  m="349780">Taking</span> <span m="350140">a</span> <span m="350230">closer</span>
  <span m="350680">look</span> <span m="350950">at</span> <span m="351040">the</span>
  <span m="351130">states</span> <span m="351550">in</span> <span m="351670">this</span>
  <span m="351880">FSM,</span> <span m="353020">we</span> <span m="353140">see</span>
  <span m="353350">that</span> <span m="353530">both</span> <span m="353920">states</span>
  <span m="354370">C</span> <span m="354790">and</span> <span m="355240">E</span>
  <span m="355630">transition</span> <span m="356290">to</span> <span m="356440">state</span>
  <span m="356800">B</span> <span m="357250">on</span> <span m="357420">a</span> <span
  m="357490">1</span> <span m="357730">input</span> <span m="358510">and</span> <span
  m="358630">produce</span> <span m="358895">a</span> <span m="359160">01</span> <span
  m="359890">output.</span> <span m="361090">On</span> <span m="361270">a</span> <span
  m="361330">0</span> <span m="361810">input,</span> <span m="362410">they</span>
  <span m="362590">both</span> <span m="362860">transition</span> <span m="363490">to</span>
  <span m="363610">state</span> <span m="364060">A</span> <span m="364480">and</span>
  <span m="364690">produce</span> <span m="365260">a</span> <span m="365380">10</span>
  <span m="366100">output.</span> <span m="367180">So</span> <span m="367480">states</span>
  <span m="367850">C</span> <span m="368150">and</span> <span m="368350">E</span>
  <span m="369010">are</span> <span m="369130">equivalent</span> <span m="369850">and</span>
  <span m="369970">can</span> <span m="370180">be</span> <span m="370300">merged</span>
  <span m="370750">into</span> <span m="371020">a</span> <span m="371080">single</span>
  <span m="371500">state,</span> <span m="372280">thus</span> <span m="372520">reducing</span>
  <span m="373090">the</span> <span m="373210">total</span> <span m="373600">number</span>
  <span m="373960">of</span> <span m="374050">states</span> <span m="374530">in</span>
  <span m="374710">our</span> <span m="374860">FSM</span> <span m="375870">to</span>
  <span m="376030">four.</span></p>
type: course
uid: 6e52f4cb5157b249280d2c8dc77638e0

---
None