---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: zZfr7Zqfqm4
  parent_uid: 225249ead89b40786dc401911b5be0c7
  title: Video-YouTube-Stream
  type: Video
  uid: eaea1194b7df7143ddfbaac49a498b54
- id: 3Play-3Play YouTube id-Stream
  media_location: zZfr7Zqfqm4
  parent_uid: 225249ead89b40786dc401911b5be0c7
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 2e399c3519a54b814def5562906acac1
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/zZfr7Zqfqm4/default.jpg
  parent_uid: 225249ead89b40786dc401911b5be0c7
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 3859cca6192bbc34eb340761c4adbcb6
- id: zZfr7Zqfqm4.srt
  parent_uid: 225249ead89b40786dc401911b5be0c7
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c4/c4s2/c4s2v8/gates-and-boolean-logic/zZfr7Zqfqm4.srt
  title: 3play caption file
  type: null
  uid: bc0b5a9ffe464834d109b5276a46b0df
- id: zZfr7Zqfqm4.pdf
  parent_uid: 225249ead89b40786dc401911b5be0c7
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c4/c4s2/c4s2v8/gates-and-boolean-logic/zZfr7Zqfqm4.pdf
  title: 3play pdf file
  type: null
  uid: 751a93a52d942582f0d5efdee0882c90
- id: Caption-3Play YouTube id-SRT
  parent_uid: 225249ead89b40786dc401911b5be0c7
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 93ae6292cdd5656c3286a5b355df9014
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 225249ead89b40786dc401911b5be0c7
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: fa6e579e89ec97d78117099048819741
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_04-02-08-02_300k.mp4
  parent_uid: 225249ead89b40786dc401911b5be0c7
  title: Video-Internet Archive-MP4
  type: Video
  uid: 07df7b4f0d876220b3f31bb88c25fa50
inline_embed_id: 65131928gatesandbooleanlogic93296825
layout: video
order_index: null
parent_uid: 8f2c6bc38a024382dbe3d1ddde84d0f6
related_resources_text: ''
short_url: gates-and-boolean-logic
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c4/c4s2/c4s2v8/gates-and-boolean-logic
template_type: Embed
title: 'Worked Example: Gates and Boolean Logic'
transcript: <p><span m="2680">PROFESSOR:</span> <span m="2890">Instead</span> <span
  m="3100">of</span> <span m="3220">building</span> <span m="3790">all</span> <span
  m="4030">of</span> <span m="4180">our</span> <span m="4300">logic</span> <span m="4750">functions</span>
  <span m="5260">directly</span> <span m="5830">in</span> <span m="5980">CMOS,</span>
  <span m="7000">it</span> <span m="7150">is</span> <span m="7360">easier</span> <span
  m="7810">for</span> <span m="7990">us</span> <span m="8140">to</span> <span m="8260">create</span>
  <span m="8710">a</span> <span m="8770">higher</span> <span m="9130">level</span>
  <span m="9490">of</span> <span m="9610">abstraction</span> <span m="10780">known</span>
  <span m="11110">as</span> <span m="11290">Boolean</span> <span m="11800">gates,</span>
  <span m="12310">which</span> <span m="12550">represent</span> <span m="13180">CMOS</span>
  <span m="13750">gates.</span> <span m="14890">Each</span> <span m="15190">gate</span>
  <span m="15700">is</span> <span m="15850">assigned</span> <span m="16300">a</span>
  <span m="16329">symbol,</span> <span m="16990">which</span> <span m="17230">can</span>
  <span m="17380">then</span> <span m="17620">be</span> <span m="17770">used</span>
  <span m="18100">in</span> <span m="18190">schematic</span> <span m="18730">diagrams</span>
  <span m="19480">that</span> <span m="19630">combine</span> <span m="20110">multiple</span>
  <span m="20680">logic</span> <span m="21100">gates</span> <span m="21430">together.</span>
  <span m="22840">In</span> <span m="23050">order</span> <span m="23380">to</span>
  <span m="23530">be</span> <span m="23710">able</span> <span m="23920">to</span>
  <span m="24100">understand</span> <span m="24760">what</span> <span m="25000">function</span>
  <span m="25600">any</span> <span m="25840">combination</span> <span m="26200">of</span>
  <span m="26560">logic</span> <span m="27130">gates</span> <span m="27430">will</span>
  <span m="27550">produce,</span> <span m="28690">we</span> <span m="28840">will</span>
  <span m="28990">begin</span> <span m="29440">by</span> <span m="29620">reviewing</span>
  <span m="30160">the</span> <span m="30280">basic</span> <span m="30730">gates</span>
  <span m="31120">together</span> <span m="31600">with</span> <span m="31760">the</span>
  <span m="31840">truth</span> <span m="32170">tables</span> <span m="32680">that</span>
  <span m="32830">define</span> <span m="33310">their</span> <span m="33460">logic.</span></p><p><span
  m="34960">We</span> <span m="35110">begin</span> <span m="35470">with</span> <span
  m="35650">an</span> <span m="35740">inverter.</span> <span m="37090">An</span> <span
  m="37240">inverter</span> <span m="37750">is</span> <span m="37960">a</span> <span
  m="38020">gate</span> <span m="38320">that</span> <span m="38470">has</span> <span
  m="38680">a</span> <span m="38740">single</span> <span m="39130">input</span> <span
  m="39610">and</span> <span m="39760">a</span> <span m="39790">single</span> <span
  m="40240">output.</span> <span m="41260">The</span> <span m="41440">output</span>
  <span m="41860">is</span> <span m="41980">simply</span> <span m="42370">the</span>
  <span m="42550">inverse</span> <span m="43000">of</span> <span m="43120">the</span>
  <span m="43270">input.</span> <span m="44320">When</span> <span m="44530">A</span>
  <span m="44650">equals</span> <span m="44950">0,</span> <span m="45580">Y</span>
  <span m="45910">equals</span> <span m="46240">1.</span> <span m="47110">And</span>
  <span m="47230">when</span> <span m="47350">A</span> <span m="47450">equals</span>
  <span m="47800">1,</span> <span m="48205">Y</span> <span m="48610">equals</span>
  <span m="48910">0.</span> <span m="50530">Next,</span> <span m="50980">we</span>
  <span m="51130">examine</span> <span m="51670">AND</span> <span m="52090">and</span>
  <span m="52270">OR</span> <span m="52510">gates.</span> <span m="53520">The</span>
  <span m="53890">AND</span> <span m="54190">function</span> <span m="54880">expects</span>
  <span m="55480">all</span> <span m="55720">of</span> <span m="55810">its</span>
  <span m="55990">inputs</span> <span m="56470">to</span> <span m="56590">be</span>
  <span m="56740">true,</span> <span m="57760">or</span> <span m="57910">1,</span>
  <span m="58780">in</span> <span m="58960">order</span> <span m="59230">to</span>
  <span m="59350">produce</span> <span m="59830">a</span> <span m="59920">1</span>
  <span m="60370">as</span> <span m="60580">its</span> <span m="60790">output.</span>
  <span m="62320">So</span> <span m="62530">its</span> <span m="62800">truth</span>
  <span m="63100">table</span> <span m="64000">is</span> <span m="64239">for</span>
  <span m="64510">A,</span> <span m="64610">B</span> <span m="65019">equals</span>
  <span m="65379">0,</span> <span m="65770">0,</span> <span m="66700">Y</span> <span
  m="67000">equals</span> <span m="67300">0.</span> <span m="68230">For</span> <span
  m="68470">A,</span> <span m="68570">B</span> <span m="68890">equals</span> <span
  m="69220">0,</span> <span m="69610">1,</span> <span m="70240">Y</span> <span m="70570">equals</span>
  <span m="70900">0.</span> <span m="71740">For</span> <span m="71980">A,</span> <span
  m="72190">B</span> <span m="72430">equals</span> <span m="72850">1,</span> <span
  m="73210">0,</span> <span m="73930">y</span> <span m="74260">equals</span> <span
  m="74620">0.</span> <span m="75580">And</span> <span m="76060">for</span> <span
  m="76300">A,</span> <span m="76510">B</span> <span m="76720">equal</span> <span
  m="77080">1,</span> <span m="77380">1,</span> <span m="78160">Y</span> <span m="78520">equals</span>
  <span m="79000">1.</span></p><p><span m="80161">The</span> <span m="80550">OR</span>
  <span m="80820">function</span> <span m="81630">just</span> <span m="81930">expects</span>
  <span m="82500">at</span> <span m="82590">least</span> <span m="83010">one</span>
  <span m="83220">of</span> <span m="83340">its</span> <span m="83520">inputs</span>
  <span m="84000">to</span> <span m="84090">be</span> <span m="84270">true</span>
  <span m="85080">in</span> <span m="85230">order</span> <span m="85470">to</span>
  <span m="85620">produce</span> <span m="86030">a</span> <span m="86220">1</span>
  <span m="86580">as</span> <span m="86790">its</span> <span m="87000">output.</span>
  <span m="88270">So</span> <span m="88410">for</span> <span m="88680">A,</span> <span
  m="88890">B</span> <span m="89130">equals</span> <span m="89460">0,</span> <span
  m="89850">0,</span> <span m="90540">Y</span> <span m="90900">equals</span> <span
  m="91200">0.</span> <span m="92130">But</span> <span m="92250">for</span> <span
  m="92430">the</span> <span m="92580">other</span> <span m="92850">three</span> <span
  m="93090">combinations,</span> <span m="94260">Y</span> <span m="94590">equals</span>
  <span m="95040">1.</span> <span m="97040">NAND and</span> <span m="97160">NOR</span>
  <span m="97460">gates</span> <span m="97820">simply</span> <span m="98240">produce</span>
  <span m="98660">the</span> <span m="98810">inverse</span> <span m="99440">of</span>
  <span m="99650">AND</span> <span m="99980">and</span> <span m="100130">OR.</span>
  <span m="101180">The</span> <span m="101300">reason</span> <span m="101780">that</span>
  <span m="101930">we</span> <span m="102050">like</span> <span m="102290">to</span>
  <span m="102410">work</span> <span m="102710">with</span> <span m="102860">NAND</span>
  <span m="103280">and NOR</span> <span m="103610">gates</span> <span m="104390">is</span>
  <span m="104570">because</span> <span m="104960">they</span> <span m="105110">are</span>
  <span m="105260">inverting</span> <span m="105890">gates,</span> <span m="106520">and</span>
  <span m="106610">they</span> <span m="106730">can</span> <span m="106940">be</span>
  <span m="107090">implemented</span> <span m="107960">as</span> <span m="108140">a</span>
  <span m="108170">single</span> <span m="108620">CMOS</span> <span m="109190">gate,</span>
  <span m="110000">whereas</span> <span m="110360">the</span> <span m="110540">AND</span>
  <span m="110930">and</span> <span m="111080">OR</span> <span m="111320">gates</span>
  <span m="111830">cannot.</span></p><p><span m="113480">Finally,</span> <span m="114590">the</span>
  <span m="114710">last</span> <span m="115100">basic</span> <span m="115550">gate</span>
  <span m="116090">is</span> <span m="116240">an</span> <span m="116360">exclusive</span>
  <span m="117020">or.</span> <span m="117660">The</span> <span m="118010">exclusive</span>
  <span m="118610">or</span> <span m="118820">produces</span> <span m="119420">a</span>
  <span m="119540">1</span> <span m="119840">output</span> <span m="120380">if</span>
  <span m="120560">exactly</span> <span m="121190">one</span> <span m="121430">of</span>
  <span m="121550">its</span> <span m="121730">two</span> <span m="121940">inputs</span>
  <span m="122330">is</span> <span m="122510">a</span> <span m="122570">1</span> <span
  m="123350">and</span> <span m="123500">0</span> <span m="124010">otherwise.</span>
  <span m="125240">So</span> <span m="125450">for</span> <span m="125690">A,</span>
  <span m="125920">B</span> <span m="126170">equals</span> <span m="126530">0,</span>
  <span m="126920">0,</span> <span m="127620">Y</span> <span m="128120">equals</span>
  <span m="128419">0.</span> <span m="129410">For</span> <span m="129620">A,</span>
  <span m="129830">B</span> <span m="130039">equals</span> <span m="130370">0,</span>
  <span m="130759">1,</span> <span m="131510">Y</span> <span m="131810">equals</span>
  <span m="132230">1.</span> <span m="133100">For</span> <span m="133340">A,</span>
  <span m="133550">B</span> <span m="133760">equal</span> <span m="134090">to</span>
  <span m="134270">1,</span> <span m="134600">0,</span> <span m="135260">Y</span>
  <span m="135770">equals</span> <span m="136130">1.</span> <span m="137060">And</span>
  <span m="137240">for</span> <span m="137450">A,</span> <span m="137660">B</span>
  <span m="137870">equals</span> <span m="138230">to</span> <span m="138380">1,</span>
  <span m="138720">1,</span> <span m="139430">y</span> <span m="139760">equals</span>
  <span m="140180">0.</span></p><p><span m="143150">The</span> <span m="143330">output</span>
  <span m="143690">of</span> <span m="143810">one</span> <span m="144110">Boolean</span>
  <span m="144560">gate</span> <span m="145040">can</span> <span m="145250">be</span>
  <span m="145400">used</span> <span m="145730">as</span> <span m="145880">an</span>
  <span m="146030">input</span> <span m="146480">to</span> <span m="146720">another</span>
  <span m="147140">Boolean</span> <span m="147560">gate.</span> <span m="148430">So</span>
  <span m="148610">multiple</span> <span m="149120">gates</span> <span m="149510">can</span>
  <span m="149690">be</span> <span m="149840">used</span> <span m="150140">to</span>
  <span m="150260">generate</span> <span m="150800">more</span> <span m="151070">complex</span>
  <span m="151700">functions.</span> <span m="153120">For</span> <span m="153230">example,</span>
  <span m="154200">here</span> <span m="154310">we</span> <span m="154460">have</span>
  <span m="154670">a</span> <span m="154700">circuit</span> <span m="155240">that</span>
  <span m="155390">consists</span> <span m="155960">of</span> <span m="156080">two</span>
  <span m="156380">inputs</span> <span m="157370">and</span> <span m="157520">six</span>
  <span m="157940">gates,</span> <span m="158600">which</span> <span m="158870">are</span>
  <span m="159020">an</span> <span m="159140">inverter,</span> <span m="159950">an</span>
  <span m="160100">AND</span> <span m="160430">gate,</span> <span m="160850">and</span>
  <span m="161030">OR</span> <span m="161270">gate,</span> <span m="162110">two</span>
  <span m="162410">NOR</span> <span m="162710">gates,</span> <span m="163350">and</span>
  <span m="163400">1</span> <span m="163640">NAND</span> <span m="164000">gate.</span>
  <span m="165140">In</span> <span m="165290">order</span> <span m="165530">to</span>
  <span m="165650">figure</span> <span m="166070">out</span> <span m="166220">what</span>
  <span m="166400">this</span> <span m="166580">combination</span> <span m="167330">of</span>
  <span m="167450">gates</span> <span m="167780">produces</span> <span m="168500">as</span>
  <span m="168710">its</span> <span m="168920">output,</span> <span m="169880">we</span>
  <span m="170030">can</span> <span m="170210">work</span> <span m="170510">incrementally</span>
  <span m="171410">through</span> <span m="171710">the</span> <span m="171800">circuit.</span></p><p><span
  m="173120">We</span> <span m="173330">begin</span> <span m="174050">by</span> <span
  m="174290">enumerating</span> <span m="175190">all</span> <span m="175430">our</span>
  <span m="175550">choices</span> <span m="176150">of</span> <span m="176330">inputs</span>
  <span m="176750">for</span> <span m="176960">A and</span> <span m="177380">B.</span>
  <span m="178400">We</span> <span m="178520">know</span> <span m="178790">that</span>
  <span m="179360">the</span> <span m="179570">output</span> <span m="179990">of</span>
  <span m="180080">the</span> <span m="180200">inverter</span> <span m="180890">is</span>
  <span m="181070">the</span> <span m="181160">complement</span> <span m="181850">of</span>
  <span m="182030">B.</span> <span m="183440">The</span> <span m="183620">AND</span>
  <span m="183920">and</span> <span m="184100">OR</span> <span m="184310">gates</span>
  <span m="185150">use</span> <span m="185390">the</span> <span m="185540">A and</span>
  <span m="185900">B</span> <span m="186260">inputs</span> <span m="186620">directly.</span>
  <span m="187670">So</span> <span m="187880">since</span> <span m="188210">we</span>
  <span m="188360">just</span> <span m="188690">reviewed</span> <span m="189230">what</span>
  <span m="189470">AND</span> <span m="189790">and</span> <span m="189920">OR</span>
  <span m="190100">gates</span> <span m="190400">produce,</span> <span m="191420">we</span>
  <span m="191540">can</span> <span m="191720">fill</span> <span m="192050">in</span>
  <span m="192200">these</span> <span m="192440">columns,</span> <span m="192950">as</span>
  <span m="193100">well.</span></p><p><span m="197350">Next,</span> <span m="197790">we</span>
  <span m="197970">want</span> <span m="198210">to</span> <span m="198330">see</span>
  <span m="198600">what</span> <span m="198780">our</span> <span m="198870">first</span>
  <span m="199290">NOR</span> <span m="199560">gate</span> <span m="199830">produces.</span>
  <span m="201070">Its</span> <span m="201390">inputs</span> <span m="202110">are</span>
  <span m="202380">A</span> <span m="202830">and</span> <span m="203040">the</span>
  <span m="203130">complement</span> <span m="203790">of</span> <span m="203940">B.</span>
  <span m="204990">We</span> <span m="205140">walk</span> <span m="205470">through</span>
  <span m="205770">each</span> <span m="206070">of</span> <span m="206190">the</span>
  <span m="206310">input</span> <span m="206610">combinations</span> <span m="207840">and</span>
  <span m="207990">determine</span> <span m="208500">the</span> <span m="208620">corresponding</span>
  <span m="209460">output</span> <span m="209850">for</span> <span m="210150">that</span>
  <span m="210390">gate.</span> <span m="211590">For</span> <span m="211940">input</span>
  <span m="212340">0,</span> <span m="212760">1,</span> <span m="213460">the</span>
  <span m="213540">output</span> <span m="214170">is</span> <span m="214260">0.</span>
  <span m="215190">For</span> <span m="215370">0,</span> <span m="215790">0,</span>
  <span m="216490">the</span> <span m="216570">output</span> <span m="216960">is</span>
  <span m="217080">1.</span> <span m="218190">For</span> <span m="218400">inputs</span>
  <span m="218940">1,</span> <span m="219210">1,</span> <span m="219970">the</span>
  <span m="220080">output</span> <span m="220470">is</span> <span m="220530">0.</span>
  <span m="221550">And</span> <span m="221670">for</span> <span m="221850">input</span>
  <span m="222270">1,</span> <span m="222510">0,</span> <span m="223270">the</span>
  <span m="223350">output</span> <span m="223770">is</span> <span m="223830">0.</span></p><p><span
  m="225150">In</span> <span m="225240">the</span> <span m="225360">same</span> <span
  m="225660">manner,</span> <span m="226200">we</span> <span m="226410">evaluate</span>
  <span m="227010">the</span> <span m="227160">outputs</span> <span m="227580">for</span>
  <span m="227710">our</span> <span m="227820">second</span> <span m="228300">NOR</span>
  <span m="228570">gate.</span> <span m="229770">Its</span> <span m="230010">inputs</span>
  <span m="230610">are</span> <span m="230730">the</span> <span m="230910">outputs</span>
  <span m="231360">of</span> <span m="231450">the</span> <span m="231570">first</span>
  <span m="232050">NOR</span> <span m="232320">gate</span> <span m="233160">and</span>
  <span m="233670">the</span> <span m="233850">AND</span> <span m="234180">gate.</span>
  <span m="235230">Again,</span> <span m="235650">we</span> <span m="235800">simply</span>
  <span m="236190">walk</span> <span m="236460">through</span> <span m="236700">each</span>
  <span m="236940">combination</span> <span m="237660">of</span> <span m="237780">inputs</span>
  <span m="238410">and</span> <span m="238530">specify</span> <span m="239160">the</span>
  <span m="239310">outputs</span> <span m="239790">produced</span> <span m="240240">by</span>
  <span m="240420">the</span> <span m="240510">second</span> <span m="240930">NOR</span>
  <span m="241260">gate.</span> <span m="242250">When</span> <span m="242460">both</span>
  <span m="242820">inputs</span> <span m="243210">are</span> <span m="243360">0,</span>
  <span m="244210">the</span> <span m="244290">output</span> <span m="244650">is</span>
  <span m="244800">1.</span> <span m="245760">When</span> <span m="245970">one</span>
  <span m="246270">input</span> <span m="246690">is</span> <span m="246780">0</span>
  <span m="247290">and</span> <span m="247470">the</span> <span m="247620">other</span>
  <span m="247920">is</span> <span m="248100">a</span> <span m="248160">1,</span>
  <span m="248740">the</span> <span m="248850">output</span> <span m="249210">is a</span>
  <span m="249410">0.</span></p><p><span m="250990">Finally,</span> <span m="251580">we</span>
  <span m="251760">take</span> <span m="252060">those</span> <span m="252480">outputs,</span>
  <span m="252930">together</span> <span m="253380">with</span> <span m="253560">the</span>
  <span m="253680">outputs</span> <span m="254100">of</span> <span m="254190">the</span>
  <span m="254390">OR</span> <span m="254610">gate,</span> <span m="255360">and</span>
  <span m="255510">generate</span> <span m="256079">the</span> <span m="256200">final</span>
  <span m="256740">output</span> <span m="257160">of</span> <span m="257339">the</span>
  <span m="257459">circuit</span> <span m="258660">at</span> <span m="258810">the</span>
  <span m="258959">output</span> <span m="259470">of</span> <span m="259709">the</span>
  <span m="259829">NAND</span> <span m="260160">gate.</span> <span m="260959">Here,</span>
  <span m="261540">when</span> <span m="261779">both</span> <span m="262110">inputs</span>
  <span m="262500">are</span> <span m="262650">1,</span> <span m="263190">we</span>
  <span m="263370">get</span> <span m="263610">a</span> <span m="263680">0</span>
  <span m="264150">output.</span> <span m="265110">Otherwise,</span> <span m="265800">the</span>
  <span m="265950">output</span> <span m="266310">is</span> <span m="266490">a</span>
  <span m="266550">1.</span> <span m="267840">This</span> <span m="268080">NAND</span>
  <span m="268470">column</span> <span m="268950">of</span> <span m="269070">our</span>
  <span m="269220">truth</span> <span m="269580">table</span> <span m="270180">is</span>
  <span m="270330">the</span> <span m="270420">resulting</span> <span m="271110">output</span>
  <span m="271830">H.</span></p><p><span m="275440">Now</span> <span m="275680">that</span>
  <span m="275830">we</span> <span m="276010">have</span> <span m="276130">evaluated</span>
  <span m="276910">what</span> <span m="277120">our</span> <span m="277240">output</span>
  <span m="277720">H</span> <span m="278140">is</span> <span m="278350">equal</span>
  <span m="278710">to</span> <span m="279010">for</span> <span m="279220">each</span>
  <span m="279460">combination</span> <span m="280240">of</span> <span m="280450">A
  and</span> <span m="280780">B,</span> <span m="281650">we</span> <span m="281770">can</span>
  <span m="281950">represent</span> <span m="282520">the</span> <span m="282640">circuit</span>
  <span m="283240">as</span> <span m="283390">a</span> <span m="283450">single</span>
  <span m="283930">truth</span> <span m="284260">table</span> <span m="285040">whose</span>
  <span m="285310">inputs</span> <span m="285940">are</span> <span m="286150">A and</span>
  <span m="286510">B</span> <span m="287050">and</span> <span m="287170">whose</span>
  <span m="287410">output</span> <span m="287800">is</span> <span m="288010">H.</span>
  <span m="289240">At</span> <span m="289360">this</span> <span m="289600">point,</span>
  <span m="290110">we</span> <span m="290230">can</span> <span m="290410">express</span>
  <span m="290860">the</span> <span m="290950">function</span> <span m="291490">H</span>
  <span m="292030">as</span> <span m="292180">a</span> <span m="292240">combination</span>
  <span m="293110">of</span> <span m="293290">all</span> <span m="293470">the</span>
  <span m="293590">cases</span> <span m="294100">that</span> <span m="294280">make</span>
  <span m="294700">H</span> <span m="295000">equal</span> <span m="295300">to</span>
  <span m="295450">1.</span> <span m="296590">This</span> <span m="296830">occurs</span>
  <span m="297490">if</span> <span m="297760">A and</span> <span m="298120">B</span>
  <span m="298660">are</span> <span m="298780">both</span> <span m="299140">equal</span>
  <span m="299410">to</span> <span m="299560">0,</span> <span m="300700">or</span>
  <span m="301270">if</span> <span m="301510">A</span> <span m="301690">equals</span>
  <span m="302020">0</span> <span m="302560">and</span> <span m="302710">B</span>
  <span m="302980">equals</span> <span m="303340">1,</span> <span m="304576">or</span>
  <span m="304990">if</span> <span m="305290">A and</span> <span m="305710">B</span>
  <span m="306190">are</span> <span m="306280">both</span> <span m="306670">equal</span>
  <span m="306940">to</span> <span m="307120">1.</span></p><p><span m="308230">This</span>
  <span m="308410">can</span> <span m="308590">be</span> <span m="308710">expressed</span>
  <span m="309220">as</span> <span m="309370">a</span> <span m="309430">Boolean</span>
  <span m="309880">logic</span> <span m="310300">expression</span> <span m="311200">as</span>
  <span m="311410">follows.</span> <span m="312850">H</span> <span m="313450">equals</span>
  <span m="314170">not</span> <span m="314650">A</span> <span m="314980">not</span>
  <span m="315400">B,</span> <span m="316360">or</span> <span m="317140">not</span>
  <span m="317560">A</span> <span m="318400">B,</span> <span m="319420">or</span>
  <span m="320200">A</span> <span m="320470">B.</span> <span m="321330">This</span>
  <span m="321760">notation</span> <span m="322600">is</span> <span m="322780">called</span>
  <span m="323090">the</span> <span m="323170">sum</span> <span m="323470">of</span>
  <span m="323590">products</span> <span m="324160">notation.</span> <span m="326050">Any</span>
  <span m="326290">sum</span> <span m="326560">of</span> <span m="326680">products</span>
  <span m="327250">can</span> <span m="327430">be</span> <span m="327550">converted</span>
  <span m="328300">into</span> <span m="328570">a</span> <span m="328630">simple</span>
  <span m="329080">gate</span> <span m="329380">representation</span> <span m="330280">of</span>
  <span m="330400">the</span> <span m="330490">function</span> <span m="331540">using</span>
  <span m="331930">only</span> <span m="332320">inverters,</span> <span m="333130">AND,</span>
  <span m="333580">and</span> <span m="333760">OR</span> <span m="333970">gates</span>
  <span m="334840">by</span> <span m="334990">having</span> <span m="335320">one</span>
  <span m="335620">large</span> <span m="336070">OR</span> <span m="336280">gate</span>
  <span m="336760">that</span> <span m="336940">receives</span> <span m="337450">as</span>
  <span m="337630">input</span> <span m="338230">one</span> <span m="338530">AND</span>
  <span m="338860">gate</span> <span m="339130">per</span> <span m="339310">product</span>
  <span m="339820">term.</span> <span m="340840">Inverters</span> <span m="341650">are</span>
  <span m="341800">used</span> <span m="342190">as</span> <span m="342370">needed</span>
  <span m="342790">to</span> <span m="342940">complement</span> <span m="343600">the</span>
  <span m="343750">inputs</span> <span m="345220">to</span> <span m="345400">the</span>
  <span m="345580">AND</span> <span m="345850">gates.</span></p><p><span m="347950">One</span>
  <span m="348190">thing</span> <span m="348400">that's</span> <span m="348640">interesting</span>
  <span m="349150">to</span> <span m="349300">note</span> <span m="349630">about</span>
  <span m="349960">this</span> <span m="350110">combination</span> <span m="350800">of</span>
  <span m="350920">gates</span> <span m="351850">is</span> <span m="352060">that</span>
  <span m="352210">it</span> <span m="352270">can</span> <span m="352480">easily</span>
  <span m="352930">be</span> <span m="353080">converted</span> <span m="353680">into</span>
  <span m="353920">a</span> <span m="353980">circuit</span> <span m="354490">that</span>
  <span m="354640">consists</span> <span m="355150">purely</span> <span m="355660">of</span>
  <span m="355810">NAND</span> <span m="356170">gates.</span> <span m="357130">The</span>
  <span m="357250">way</span> <span m="357430">to</span> <span m="357580">do</span>
  <span m="357820">this</span> <span m="358210">is</span> <span m="358360">to</span>
  <span m="358450">realize</span> <span m="358990">that</span> <span m="359140">if</span>
  <span m="359290">you</span> <span m="359410">take</span> <span m="359710">the</span>
  <span m="359890">output</span> <span m="360310">of</span> <span m="360460">a</span>
  <span m="360520">gate</span> <span m="361000">and</span> <span m="361120">invert</span>
  <span m="361570">it</span> <span m="361660">twice,</span> <span m="362560">you've</span>
  <span m="362720">produced</span> <span m="363100">the</span> <span m="363220">original</span>
  <span m="363760">output.</span> <span m="364960">This</span> <span m="365200">means</span>
  <span m="365560">that</span> <span m="365710">we</span> <span m="365860">can</span>
  <span m="366100">add</span> <span m="366520">two</span> <span m="366820">inverters</span>
  <span m="367480">between</span> <span m="367990">each</span> <span m="368350">AND</span>
  <span m="368740">output</span> <span m="369580">and</span> <span m="369790">OR</span>
  <span m="370090">input.</span> <span m="371200">We</span> <span m="371350">can</span>
  <span m="371500">draw</span> <span m="371800">these</span> <span m="372040">inverters</span>
  <span m="372640">as</span> <span m="372850">bubbles,</span> <span m="373630">which</span>
  <span m="373840">represent</span> <span m="374380">inversion,</span> <span m="375460">where</span>
  <span m="375610">we</span> <span m="375880">place</span> <span m="376150">one</span>
  <span m="376450">bubble</span> <span m="376870">on</span> <span m="377020">the</span>
  <span m="377140">output</span> <span m="377620">of</span> <span m="377770">the</span>
  <span m="377920">AND</span> <span m="378190">gate</span> <span m="378970">and</span>
  <span m="379120">the</span> <span m="379270">other</span> <span m="379540">bubble</span>
  <span m="380020">at</span> <span m="380170">the</span> <span m="380320">input</span>
  <span m="380740">to</span> <span m="380860">the</span> <span m="381030">OR</span>
  <span m="381240">gate.</span></p><p><span m="382360">We</span> <span m="382510">know</span>
  <span m="382720">that</span> <span m="382930">an</span> <span m="383170">AND</span>
  <span m="383440">gate</span> <span m="383860">followed</span> <span m="384310">by</span>
  <span m="384520">an</span> <span m="384610">inversion</span> <span m="385630">is</span>
  <span m="385750">simply</span> <span m="386260">a</span> <span m="386380">NAND</span>
  <span m="386740">gate.</span> <span m="387880">We</span> <span m="388030">also</span>
  <span m="388450">know</span> <span m="388750">that</span> <span m="388930">an</span>
  <span m="389020">inverter</span> <span m="389830">is</span> <span m="390010">equivalent</span>
  <span m="390610">to</span> <span m="390820">a</span> <span m="390880">NAND</span>
  <span m="391240">gate</span> <span m="391570">with</span> <span m="391780">both</span>
  <span m="392110">of</span> <span m="392230">its</span> <span m="392410">inputs</span>
  <span m="392860">tied</span> <span m="393160">together.</span> <span m="395230">In</span>
  <span m="395440">addition,</span> <span m="396250">using</span> <span m="396700">De</span>
  <span m="396820">Morgan's</span> <span m="397390">law,</span> <span m="398140">we</span>
  <span m="398320">know</span> <span m="398560">that</span> <span m="398980">not</span>
  <span m="399370">A</span> <span m="400270">or</span> <span m="400840">not</span>
  <span m="401200">B</span> <span m="402010">is</span> <span m="402220">equivalent</span>
  <span m="402910">to</span> <span m="403120">not</span> <span m="404140">of</span>
  <span m="404380">A</span> <span m="404620">and</span> <span m="405010">B.</span>
  <span m="406420">This</span> <span m="406660">means</span> <span m="407140">that</span>
  <span m="407320">the</span> <span m="407440">bubbles</span> <span m="407950">followed</span>
  <span m="408490">by</span> <span m="408670">the</span> <span m="408850">OR</span>
  <span m="409090">gate</span> <span m="409810">can</span> <span m="410020">also</span>
  <span m="410620">be</span> <span m="410800">replaced</span> <span m="411340">with</span>
  <span m="411520">a</span> <span m="411580">NAND</span> <span m="411940">gate,</span>
  <span m="412880">thus</span> <span m="413140">arriving</span> <span m="413740">at</span>
  <span m="413860">our</span> <span m="413980">equivalent</span> <span m="414580">circuit</span>
  <span m="415000">representation</span> <span m="416350">consisting</span> <span
  m="417070">purely</span> <span m="417670">of</span> <span m="417880">NAND</span>
  <span m="418240">gates.</span></p><p><span m="419350">The</span> <span m="419470">advantage</span>
  <span m="420010">of</span> <span m="420130">using</span> <span m="420580">NAND</span>
  <span m="420910">gates</span> <span m="421240">to</span> <span m="421390">implement</span>
  <span m="421930">the</span> <span m="422020">circuit</span> <span m="422920">is</span>
  <span m="423070">that</span> <span m="423220">NAND</span> <span m="423550">gates</span>
  <span m="424000">are</span> <span m="425290">inverting</span> <span m="425890">logic,</span>
  <span m="426760">where</span> <span m="426970">each</span> <span m="427270">gate</span>
  <span m="427570">can</span> <span m="427780">be</span> <span m="427930">implemented</span>
  <span m="428680">as</span> <span m="428830">a</span> <span m="428890">single</span>
  <span m="429310">CMOS</span> <span m="429850">gate.</span> <span m="431080">All</span>
  <span m="431260">functions</span> <span m="432010">can</span> <span m="432190">be</span>
  <span m="432370">expressed</span> <span m="432940">as</span> <span m="433090">a</span>
  <span m="433150">combination</span> <span m="433930">of</span> <span m="434110">NAND</span>
  <span m="434470">gates.</span> <span m="435310">So</span> <span m="435550">a</span>
  <span m="435610">NAND</span> <span m="435940">gate</span> <span m="436300">is</span>
  <span m="436420">considered</span> <span m="437110">a</span> <span m="437230">universal</span>
  <span m="438130">gate.</span></p><p><span m="439660">NOR</span> <span m="439930">gates</span>
  <span m="440380">are</span> <span m="440530">also</span> <span m="440920">universal</span>
  <span m="441970">and</span> <span m="442090">can</span> <span m="442300">be</span>
  <span m="442420">used</span> <span m="442690">to</span> <span m="442840">express</span>
  <span m="443470">any</span> <span m="443710">function.</span> <span m="445210">Furthermore,</span>
  <span m="446140">any</span> <span m="446380">circuit</span> <span m="446920">that</span>
  <span m="447070">can</span> <span m="447280">be</span> <span m="447400">used</span>
  <span m="447730">to</span> <span m="447880">implement</span> <span m="448570">any</span>
  <span m="448870">other</span> <span m="449140">function</span> <span m="450040">is</span>
  <span m="450250">also</span> <span m="450670">considered</span> <span m="451270">universal.</span>
  <span m="453990">To</span> <span m="454140">determine</span> <span m="454710">if</span>
  <span m="454860">a</span> <span m="454920">gate</span> <span m="455220">G</span>
  <span m="455550">is</span> <span m="455700">universal,</span> <span m="457020">one</span>
  <span m="457200">needs</span> <span m="457440">to</span> <span m="457560">check</span>
  <span m="458010">if</span> <span m="458190">one</span> <span m="458370">can</span>
  <span m="458580">convert</span> <span m="459060">G</span> <span m="459870">into</span>
  <span m="460200">either</span> <span m="460620">a</span> <span m="460800">NAND</span>
  <span m="461790">or</span> <span m="461970">NOR</span> <span m="462270">gate</span>
  <span m="462690">by</span> <span m="462870">simply</span> <span m="463290">using</span>
  <span m="463710">one</span> <span m="463920">or</span> <span m="464010">more</span>
  <span m="464220">copies</span> <span m="464730">of</span> <span m="464850">G</span>
  <span m="465570">together</span> <span m="466140">with</span> <span m="466380">low</span>
  <span m="466800">and</span> <span m="466950">high</span> <span m="467370">constant</span>
  <span m="468030">inputs.</span></p>
type: course
uid: 225249ead89b40786dc401911b5be0c7

---
None