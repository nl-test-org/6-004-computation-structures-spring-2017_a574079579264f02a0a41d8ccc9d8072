---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: Z3-WzUhl9nQ
  parent_uid: ba2cbd598e2a79d1fa77463c28a86317
  title: Video-YouTube-Stream
  type: Video
  uid: 0e479fafc8b9f843addbdf0433e1d501
- id: 3Play-3Play YouTube id-Stream
  media_location: Z3-WzUhl9nQ
  parent_uid: ba2cbd598e2a79d1fa77463c28a86317
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 5463b49425b9e768fce058bb5b8cfbbc
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/Z3-WzUhl9nQ/default.jpg
  parent_uid: ba2cbd598e2a79d1fa77463c28a86317
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 32040f887e18d72ab866657be52ad408
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_06-02-07-02_300k.mp4
  parent_uid: ba2cbd598e2a79d1fa77463c28a86317
  title: Video-Internet Archive-MP4
  type: Video
  uid: 422be03507382456252c68d56e4637bb
- id: Z3-WzUhl9nQ.srt
  parent_uid: ba2cbd598e2a79d1fa77463c28a86317
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v7/fsm-implementation/Z3-WzUhl9nQ.srt
  title: 3play caption file
  type: null
  uid: 038e87ce9010d750a1293e20ebeca93f
- id: Z3-WzUhl9nQ.pdf
  parent_uid: ba2cbd598e2a79d1fa77463c28a86317
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v7/fsm-implementation/Z3-WzUhl9nQ.pdf
  title: 3play pdf file
  type: null
  uid: 9115d40527f58703dadfcb923e65ad36
- id: Caption-3Play YouTube id-SRT
  parent_uid: ba2cbd598e2a79d1fa77463c28a86317
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 51558c56fec42e0d4f94bb7eaeffc547
- id: Transcript-3Play YouTube id-PDF
  parent_uid: ba2cbd598e2a79d1fa77463c28a86317
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: f1bd2d52b4ed8b13ae18ed228aa25e30
inline_embed_id: 74631207fsmimplementation43202040
layout: video
order_index: null
parent_uid: bbf08387222da03d382e8d79c93d9090
related_resources_text: ''
short_url: fsm-implementation
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c6/c6s2/c6s2v7/fsm-implementation
template_type: Embed
title: 'Worked Example: FSM Implementation'
transcript: <p><span m="1380">In</span> <span m="1790">this</span> <span m="2200">problem,</span>
  <span m="2610">we</span> <span m="3020">are</span> <span m="3430">given</span> <span
  m="3840">a</span> <span m="4250">4</span> <span m="4660">state</span> <span m="5070">transition</span>
  <span m="5480">diagram.</span></p><p><span m="5890">We</span> <span m="6174">know</span>
  <span m="6458">that</span> <span m="6742">it</span> <span m="7026">represents</span>
  <span m="7310">a</span> <span m="7594">Moore</span> <span m="7878">machine</span>
  <span m="8162">because</span> <span m="8447">the</span> <span m="8731">output</span>
  <span m="9015">is</span> <span m="9299">a</span> <span m="9583">function</span>
  <span m="9867">of</span> <span m="10151">only</span> <span m="10435">the</span>
  <span m="10720">current</span> <span m="11122">state.</span> <span m="11525">We</span>
  <span m="11928">are</span> <span m="12330">also</span> <span m="12733">given</span>
  <span m="13136">a</span> <span m="13539">partially</span> <span m="13941">filled</span>
  <span m="14344">out</span> <span m="14747">truth</span> <span m="15150">table</span>
  <span m="15503">and</span> <span m="15856">our</span> <span m="16209">first</span>
  <span m="16562">job</span> <span m="16915">is</span> <span m="17268">to</span> <span
  m="17621">fill</span> <span m="17975">in</span> <span m="18328">the</span> <span
  m="18681">missing</span> <span m="19034">entries</span> <span m="19387">in</span>
  <span m="19740">the</span> <span m="20093">truth</span> <span m="20446">table.</span></p><p><span
  m="20800">In</span> <span m="21225">order</span> <span m="21650">to</span> <span
  m="22075">do</span> <span m="22500">this,</span> <span m="22925">we</span> <span
  m="23350">need</span> <span m="23775">to</span> <span m="24200">find</span> <span
  m="24625">the</span> <span m="25050">correlation</span> <span m="25475">between</span>
  <span m="25900">states</span> <span m="26325">A</span> <span m="26750">--</span>
  <span m="27175">D</span> <span m="27600">and</span> <span m="28025">their</span>
  <span m="28450">S1S0</span> <span m="28875">encoding.</span></p><p><span m="29300">We</span>
  <span m="29608">begin</span> <span m="29917">by</span> <span m="30226">looking</span>
  <span m="30535">at</span> <span m="30844">the</span> <span m="31153">output</span>
  <span m="31462">column.</span> <span m="31771">We</span> <span m="32080">know</span>
  <span m="32388">that</span> <span m="32697">only</span> <span m="33006">state</span>
  <span m="33315">A</span> <span m="33624">has</span> <span m="33933">an</span> <span
  m="34242">output</span> <span m="34551">of</span> <span m="34860">1,</span> <span
  m="35271">so</span> <span m="35682">state</span> <span m="36093">A's</span> <span
  m="36504">encoding</span> <span m="36915">must</span> <span m="37326">be</span>
  <span m="37737">00</span> <span m="38148">and</span> <span m="38559">OUT=1</span>
  <span m="38970">regardless</span> <span m="39381">of</span> <span m="39792">the</span>
  <span m="40203">input</span> <span m="40614">because</span> <span m="41025">it</span>
  <span m="41436">is</span> <span m="41847">a</span> <span m="42258">Moore</span>
  <span m="42670">machine.</span> <span m="43125">We</span> <span m="43580">also</span>
  <span m="44035">know</span> <span m="44490">that</span> <span m="44945">from</span>
  <span m="45400">state</span> <span m="45855">A</span> <span m="46310">on</span>
  <span m="46765">a</span> <span m="47220">1</span> <span m="47675">input,</span>
  <span m="48130">the</span> <span m="48526">FSM</span> <span m="48922">moves</span>
  <span m="49319">to</span> <span m="49715">state</span> <span m="50112">B.</span>
  <span m="50508">According</span> <span m="50905">to</span> <span m="51301">the</span>
  <span m="51697">truth</span> <span m="52094">table</span> <span m="52490">from</span>
  <span m="52887">state</span> <span m="53283">00</span> <span m="53680">(which</span>
  <span m="54131">is</span> <span m="54583">A),</span> <span m="55035">on</span> <span
  m="55486">a</span> <span m="55938">1</span> <span m="56390">input,</span> <span
  m="56841">we</span> <span m="57293">move</span> <span m="57745">to</span> <span
  m="58196">state</span> <span m="58648">01.</span></p><p><span m="59100">That</span>
  <span m="59560">means</span> <span m="60021">that</span> <span m="60481">state</span>
  <span m="60942">B's</span> <span m="61403">encoding</span> <span m="61863">is</span>
  <span m="62324">01.</span> <span m="62784">We</span> <span m="63245">continue</span>
  <span m="63706">in</span> <span m="64166">this</span> <span m="64627">manner,</span>
  <span m="65087">now</span> <span m="65548">following</span> <span m="66009">the</span>
  <span m="66434">transitions</span> <span m="66860">from</span> <span m="67286">state</span>
  <span m="67712">B.</span> <span m="68137">According</span> <span m="68563">to</span>
  <span m="68989">the</span> <span m="69415">diagram,</span> <span m="69841">when</span>
  <span m="70266">IN</span> <span m="70692">=</span> <span m="71118">0,</span> <span
  m="71544">we</span> <span m="71970">move</span> <span m="72331">to</span> <span
  m="72693">state</span> <span m="73055">D.</span> <span m="73416">So</span> <span
  m="73778">looking</span> <span m="74140">up</span> <span m="74501">that</span> <span
  m="74863">transition</span> <span m="75225">in</span> <span m="75586">our</span>
  <span m="75948">truth</span> <span m="76310">table,</span> <span m="76892">tells</span>
  <span m="77474">us</span> <span m="78056">that</span> <span m="78638">state</span>
  <span m="79220">D's</span> <span m="79802">encoding</span> <span m="80384">is</span>
  <span m="80966">10.</span></p><p><span m="81549">We</span> <span m="81962">also</span>
  <span m="82375">see</span> <span m="82788">in</span> <span m="83201">our</span>
  <span m="83614">state</span> <span m="84027">diagram</span> <span m="84441">that</span>
  <span m="84854">starting</span> <span m="85267">at</span> <span m="85680">state</span>
  <span m="86093">B</span> <span m="86506">when</span> <span m="86920">IN=1,</span>
  <span m="87333">we</span> <span m="87746">move</span> <span m="88159">back</span>
  <span m="88572">to</span> <span m="88985">state</span> <span m="89399">A</span>
  <span m="89747">which</span> <span m="90096">we</span> <span m="90445">now</span>
  <span m="90794">know</span> <span m="91143">to</span> <span m="91492">be</span>
  <span m="91841">00.</span> <span m="92190">So</span> <span m="92539">we</span> <span
  m="92888">can</span> <span m="93237">fill</span> <span m="93586">in</span> <span
  m="93935">the</span> <span m="94284">next</span> <span m="94633">missing</span>
  <span m="94982">entry</span> <span m="95331">in</span> <span m="95680">our</span>
  <span m="96104">truth</span> <span m="96529">table.</span> <span m="96953">Now</span>
  <span m="97378">that</span> <span m="97802">we</span> <span m="98227">have</span>
  <span m="98651">determined</span> <span m="99076">the</span> <span m="99500">encoding</span>
  <span m="99925">for</span> <span m="100350">states</span> <span m="100679">A,</span>
  <span m="101008">B,</span> <span m="101337">and</span> <span m="101666">D.</span>
  <span m="101996">We</span> <span m="102325">know</span> <span m="102654">that</span>
  <span m="102983">the</span> <span m="103313">remaining</span> <span m="103642">encoding</span>
  <span m="103971">is</span> <span m="104300">for</span> <span m="104630">state</span>
  <span m="105043">C</span> <span m="105457">and</span> <span m="105870">that</span>
  <span m="106284">is</span> <span m="106697">11.</span> <span m="107111">At</span>
  <span m="107525">this</span> <span m="107938">point,</span> <span m="108352">we</span>
  <span m="108765">have</span> <span m="109179">all</span> <span m="109592">the</span>
  <span m="110006">information</span> <span m="110420">we</span> <span m="110806">need</span>
  <span m="111193">to</span> <span m="111580">complete</span> <span m="111967">filling</span>
  <span m="112354">out</span> <span m="112741">the</span> <span m="113128">missing</span>
  <span m="113515">entries</span> <span m="113902">in</span> <span m="114289">the</span>
  <span m="114676">truth</span> <span m="115063">table.</span></p><p><span m="115450">Looking</span>
  <span m="115853">at</span> <span m="116256">the</span> <span m="116659">row</span>
  <span m="117062">where</span> <span m="117465">the</span> <span m="117868">current</span>
  <span m="118272">state</span> <span m="118675">is</span> <span m="119078">10</span>
  <span m="119481">(state</span> <span m="119884">D)</span> <span m="120287">and</span>
  <span m="120691">IN</span> <span m="121094">=</span> <span m="121497">1</span> <span
  m="121900">and</span> <span m="122303">the</span> <span m="122706">corresponding</span>
  <span m="123110">transition</span> <span m="123562">in</span> <span m="124014">the</span>
  <span m="124467">state</span> <span m="124919">diagram,</span> <span m="125371">shows</span>
  <span m="125824">us</span> <span m="126276">that</span> <span m="126728">in</span>
  <span m="127181">this</span> <span m="127633">case</span> <span m="128085">we</span>
  <span m="128538">go</span> <span m="128990">back</span> <span m="129442">to</span>
  <span m="129895">state</span> <span m="130347">D.</span></p><p><span m="130800">Since</span>
  <span m="131368">the</span> <span m="131936">encoding</span> <span m="132505">of</span>
  <span m="133073">state</span> <span m="133642">D</span> <span m="134210">is</span>
  <span m="134779">10,</span> <span m="135347">the</span> <span m="135916">S0'</span>
  <span m="136484">entry</span> <span m="137053">is</span> <span m="137621">0.</span></p><p><span
  m="138190">Because</span> <span m="138493">this</span> <span m="138796">is</span>
  <span m="139099">a</span> <span m="139402">Moore</span> <span m="139705">machine,</span>
  <span m="140008">we</span> <span m="140311">also</span> <span m="140615">know</span>
  <span m="140918">that</span> <span m="141221">the</span> <span m="141524">output</span>
  <span m="141827">associated</span> <span m="142130">with</span> <span m="142433">current</span>
  <span m="142736">state</span> <span m="143040">D,</span> <span m="143511">regardless</span>
  <span m="143982">of</span> <span m="144454">the</span> <span m="144925">input,</span>
  <span m="145397">is</span> <span m="145868">0,</span> <span m="146340">so</span>
  <span m="146811">the</span> <span m="147282">missing</span> <span m="147754">output</span>
  <span m="148225">entry</span> <span m="148697">is</span> <span m="149168">0.</span></p><p><span
  m="149640">Finally,</span> <span m="150101">from</span> <span m="150563">state</span>
  <span m="151025">11</span> <span m="151486">(which</span> <span m="151948">is</span>
  <span m="152410">state</span> <span m="152871">C),</span> <span m="153333">when</span>
  <span m="153795">IN</span> <span m="154256">=</span> <span m="154718">1,</span>
  <span m="155180">we</span> <span m="155641">see</span> <span m="156103">from</span>
  <span m="156565">the</span> <span m="157026">state</span> <span m="157488">diagram</span>
  <span m="157950">that</span> <span m="158435">we</span> <span m="158920">transition</span>
  <span m="159405">to</span> <span m="159891">state</span> <span m="160376">A</span>
  <span m="160861">which</span> <span m="161347">is</span> <span m="161832">state</span>
  <span m="162317">00,</span> <span m="162802">so</span> <span m="163288">the</span>
  <span m="163773">remaining</span> <span m="164258">missing</span> <span m="164744">S0'</span>
  <span m="165229">value</span> <span m="165714">is</span> <span m="166200">0.</span>
  <span m="166620">We</span> <span m="167040">now</span> <span m="167460">want</span>
  <span m="167880">to</span> <span m="168300">determine</span> <span m="168720">whether</span>
  <span m="169140">or</span> <span m="169560">not</span> <span m="169980">there</span>
  <span m="170400">are</span> <span m="170820">any</span> <span m="171241">equivalent</span>
  <span m="171662">states</span> <span m="172082">in</span> <span m="172503">this</span>
  <span m="172924">FSM.</span> <span m="173345">In</span> <span m="173765">a</span>
  <span m="174186">Moore</span> <span m="174607">machine,</span> <span m="175027">equivalent</span>
  <span m="175448">states</span> <span m="175869">have</span> <span m="176290">the</span>
  <span m="176663">same</span> <span m="177036">output,</span> <span m="177410">and</span>
  <span m="177783">the</span> <span m="178156">same</span> <span m="178530">input</span>
  <span m="178903">transitions.</span> <span m="179276">This</span> <span m="179650">rules</span>
  <span m="180023">out</span> <span m="180396">state</span> <span m="180770">A</span>
  <span m="181143">because</span> <span m="181516">it</span> <span m="181890">is</span>
  <span m="182263">the</span> <span m="182636">only</span> <span m="183010">one</span>
  <span m="183360">that</span> <span m="183711">has</span> <span m="184061">a</span>
  <span m="184412">1</span> <span m="184763">output.</span> <span m="185113">Taking</span>
  <span m="185464">a</span> <span m="185815">closer</span> <span m="186165">look</span>
  <span m="186516">at</span> <span m="186866">states</span> <span m="187217">B,</span>
  <span m="187568">C,</span> <span m="187918">and</span> <span m="188269">D,</span>
  <span m="188620">we</span> <span m="188951">can</span> <span m="189283">see</span>
  <span m="189615">that</span> <span m="189947">both</span> <span m="190279">states</span>
  <span m="190610">B</span> <span m="190942">and</span> <span m="191274">C</span>
  <span m="191606">transition</span> <span m="191938">to</span> <span m="192270">state</span>
  <span m="192601">D</span> <span m="192933">on</span> <span m="193265">a</span> <span
  m="193597">0</span> <span m="193929">input,</span> <span m="194260">and</span> <span
  m="194592">to</span> <span m="194924">state</span> <span m="195256">A</span> <span
  m="195588">on</span> <span m="195920">a</span> <span m="196328">1</span> <span m="196736">input.</span>
  <span m="197145">In</span> <span m="197553">addition,</span> <span m="197961">the</span>
  <span m="198370">output</span> <span m="198778">value</span> <span m="199186">is</span>
  <span m="199595">0</span> <span m="200003">for</span> <span m="200411">both</span>
  <span m="200820">of</span> <span m="201220">them.</span> <span m="201621">This</span>
  <span m="202022">means</span> <span m="202423">that</span> <span m="202824">states</span>
  <span m="203225">B</span> <span m="203626">and</span> <span m="204027">C</span>
  <span m="204428">are</span> <span m="204829">equivalent</span> <span m="205230">and</span>
  <span m="205553">can</span> <span m="205877">be</span> <span m="206200">merged</span>
  <span m="206524">into</span> <span m="206847">1</span> <span m="207171">to</span>
  <span m="207495">turn</span> <span m="207818">this</span> <span m="208142">into</span>
  <span m="208465">a</span> <span m="208789">3</span> <span m="209112">state</span>
  <span m="209436">FSM.</span></p>
type: course
uid: ba2cbd598e2a79d1fa77463c28a86317

---
None