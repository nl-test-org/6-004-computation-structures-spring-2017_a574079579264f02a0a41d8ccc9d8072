---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: Y_PNOmL_yqY
  parent_uid: ab59526cc23163073379ef25ce4685a1
  title: Video-YouTube-Stream
  type: Video
  uid: ef062e8273c2c85ef37a57b2b0d02156
- id: 3Play-3Play YouTube id-Stream
  media_location: Y_PNOmL_yqY
  parent_uid: ab59526cc23163073379ef25ce4685a1
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 2454cd4f0643d39895ac160d272b20a2
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/Y_PNOmL_yqY/default.jpg
  parent_uid: ab59526cc23163073379ef25ce4685a1
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 2b3048ddf2369dd3603dd8c9f1c36875
- id: Y_PNOmL_yqY.srt
  parent_uid: ab59526cc23163073379ef25ce4685a1
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/interprocess-communication-9-00-/Y_PNOmL_yqY.srt
  title: 3play caption file
  type: null
  uid: 559bb41be48c5051ee92cd089db74429
- id: Y_PNOmL_yqY.pdf
  parent_uid: ab59526cc23163073379ef25ce4685a1
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/interprocess-communication-9-00-/Y_PNOmL_yqY.pdf
  title: 3play pdf file
  type: null
  uid: f57f50d79ef7f0e5b6bd89030ace873a
- id: Caption-3Play YouTube id-SRT
  parent_uid: ab59526cc23163073379ef25ce4685a1
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 918aa6e425628fcadf0214263685bd55
- id: Transcript-3Play YouTube id-PDF
  parent_uid: ab59526cc23163073379ef25ce4685a1
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: ea43e0398196792c452f1219eeec1c3e
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_19-02-01_300k.mp4
  parent_uid: ab59526cc23163073379ef25ce4685a1
  title: Video-Internet Archive-MP4
  type: Video
  uid: 00e0a598ad19a70ce25164ec15b69cd8
inline_embed_id: 67331639interprocesscommunication90049024499
layout: video
order_index: null
parent_uid: 4c59d53d717d751b14651b2fd8c38744
related_resources_text: ''
short_url: interprocess-communication-9-00-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/interprocess-communication-9-00-
template_type: Embed
title: Interprocess Communication
transcript: <p><span m="489">It's</span> <span m="931">not</span> <span m="1374">unusual</span>
  <span m="1817">to</span> <span m="2260">find</span> <span m="2703">that</span> <span
  m="3146">an</span> <span m="3589">application</span> <span m="4031">is</span> <span
  m="4474">organized</span> <span m="4917">as</span> <span m="5360">multiple</span>
  <span m="5803">communicating</span> <span m="6246">processes.</span></p><p><span
  m="6689">What's</span> <span m="7101">the</span> <span m="7513">advantage</span>
  <span m="7926">of</span> <span m="8338">using</span> <span m="8750">multiple</span>
  <span m="9163">processes</span> <span m="9575">instead</span> <span m="9988">of</span>
  <span m="10400">just</span> <span m="10812">a</span> <span m="11225">single</span>
  <span m="11637">process?</span></p><p><span m="12050">Many</span> <span m="12485">applications</span>
  <span m="12920">exhibit</span> <span m="13356">concurrency,</span> <span m="13791">i.e.,</span>
  <span m="14226">some</span> <span m="14662">of</span> <span m="15097">the</span>
  <span m="15533">required</span> <span m="15968">computations</span> <span m="16403">can</span>
  <span m="16839">be</span> <span m="17274">performed</span> <span m="17710">in</span>
  <span m="18385">parallel.</span></p><p><span m="19060">For</span> <span m="19457">example,</span>
  <span m="19855">video</span> <span m="20253">compression</span> <span m="20650">algorithms</span>
  <span m="21048">represent</span> <span m="21446">each</span> <span m="21843">video</span>
  <span m="22241">frame</span> <span m="22639">as</span> <span m="23036">an</span>
  <span m="23434">array</span> <span m="23832">of</span> <span m="24230">8-pixel</span>
  <span m="25007">by</span> <span m="25785">8-pixel</span> <span m="26562">macroblocks.</span></p><p><span
  m="27340">Each</span> <span m="27766">macroblock</span> <span m="28192">is</span>
  <span m="28618">individually</span> <span m="29044">compressed</span> <span m="29470">by</span>
  <span m="29896">converting</span> <span m="30323">the</span> <span m="30749">64</span>
  <span m="31175">intensity</span> <span m="31601">and</span> <span m="32027">color</span>
  <span m="32453">values</span> <span m="32880">from</span> <span m="33254">the</span>
  <span m="33629">spatial</span> <span m="34004">domain</span> <span m="34378">to</span>
  <span m="34753">the</span> <span m="35128">frequency</span> <span m="35502">domain</span>
  <span m="35877">and</span> <span m="36252">then</span> <span m="36626">quantizing</span>
  <span m="37001">and</span> <span m="37376">Huffman</span> <span m="37750">encoding</span>
  <span m="38125">the</span> <span m="38500">frequency</span> <span m="39475">coefficients.</span></p><p><span
  m="40450">If</span> <span m="40730">you're</span> <span m="41010">using</span> <span
  m="41290">a</span> <span m="41570">multi-core</span> <span m="41850">processor</span>
  <span m="42130">to</span> <span m="42410">do</span> <span m="42690">the</span> <span
  m="42970">compression,</span> <span m="43250">you</span> <span m="43530">can</span>
  <span m="43810">perform</span> <span m="44090">the</span> <span m="44370">macroblock</span>
  <span m="44650">compressions</span> <span m="46565">concurrently.</span></p><p><span
  m="48480">Applications</span> <span m="48895">like</span> <span m="49310">video</span>
  <span m="49725">games</span> <span m="50140">are</span> <span m="50555">naturally</span>
  <span m="50970">divided</span> <span m="51385">into</span> <span m="51800">the</span>
  <span m="52215">&quot;front-end&quot;</span> <span m="52630">user</span> <span m="53045">interface</span>
  <span m="53460">and</span> <span m="54186">&quot;back-end&quot;</span> <span m="54913">simulation</span>
  <span m="55640">and</span> <span m="56366">rendering</span> <span m="57093">engines.</span></p><p><span
  m="57820">Inputs</span> <span m="58176">from</span> <span m="58532">the</span> <span
  m="58889">user</span> <span m="59245">arrive</span> <span m="59602">asynchronously</span>
  <span m="59958">with</span> <span m="60315">respect</span> <span m="60671">to</span>
  <span m="61027">the</span> <span m="61384">simulation</span> <span m="61740">and</span>
  <span m="62097">it's</span> <span m="62453">easiest</span> <span m="62810">to</span>
  <span m="63353">organize</span> <span m="63896">the</span> <span m="64439">processing</span>
  <span m="64983">of</span> <span m="65526">user</span> <span m="66069">events</span>
  <span m="66612">separately</span> <span m="67156">from</span> <span m="67699">the</span>
  <span m="68242">backend</span> <span m="68785">processing.</span></p><p><span m="69329">Processes</span>
  <span m="69682">are</span> <span m="70035">an</span> <span m="70389">effective</span>
  <span m="70742">way</span> <span m="71096">to</span> <span m="71449">encapsulate</span>
  <span m="71802">the</span> <span m="72156">state</span> <span m="72509">and</span>
  <span m="72863">computation</span> <span m="73216">for</span> <span m="73569">what</span>
  <span m="73923">are</span> <span m="74276">logically</span> <span m="74630">independent</span>
  <span m="75060">components</span> <span m="75491">of</span> <span m="75922">an</span>
  <span m="76353">application,</span> <span m="76783">which</span> <span m="77214">communicate</span>
  <span m="77645">with</span> <span m="78076">one</span> <span m="78506">another</span>
  <span m="78937">when</span> <span m="79368">they</span> <span m="79799">need</span>
  <span m="80526">to</span> <span m="81254">share</span> <span m="81982">information.</span></p><p><span
  m="82710">These</span> <span m="83120">sorts</span> <span m="83531">of</span> <span
  m="83942">applications</span> <span m="84352">are</span> <span m="84763">often</span>
  <span m="85174">data-</span> <span m="85584">or</span> <span m="85995">event-driven,</span>
  <span m="86406">i.e.,</span> <span m="86816">the</span> <span m="87227">processing</span>
  <span m="87638">required</span> <span m="88049">is</span> <span m="88504">determined</span>
  <span m="88959">by</span> <span m="89414">the</span> <span m="89869">data</span>
  <span m="90324">to</span> <span m="90779">be</span> <span m="91234">processed</span>
  <span m="91689">or</span> <span m="92144">the</span> <span m="92599">arrival</span>
  <span m="93054">of</span> <span m="93509">external</span> <span m="93964">events.</span></p><p><span
  m="94420">How</span> <span m="94870">should</span> <span m="95320">the</span> <span
  m="95770">processes</span> <span m="96220">communicate</span> <span m="96670">with</span>
  <span m="97120">each</span> <span m="97570">other?</span></p><p><span m="98020">If</span>
  <span m="98322">the</span> <span m="98625">processes</span> <span m="98928">are</span>
  <span m="99231">running</span> <span m="99534">out</span> <span m="99837">of</span>
  <span m="100140">the</span> <span m="100443">same</span> <span m="100746">physical</span>
  <span m="101049">memory,</span> <span m="101352">it</span> <span m="101655">would</span>
  <span m="101958">be</span> <span m="102261">easy</span> <span m="102564">to</span>
  <span m="102867">arrange</span> <span m="103170">to</span> <span m="103557">share</span>
  <span m="103944">memory</span> <span m="104332">data</span> <span m="104719">by</span>
  <span m="105107">mapping</span> <span m="105494">the</span> <span m="105882">same</span>
  <span m="106269">physical</span> <span m="106656">page</span> <span m="107044">into</span>
  <span m="107431">the</span> <span m="107819">contexts</span> <span m="108206">for</span>
  <span m="108594">both</span> <span m="108981">processes.</span></p><p><span m="109369">Any</span>
  <span m="109711">data</span> <span m="110053">written</span> <span m="110395">to</span>
  <span m="110737">that</span> <span m="111079">page</span> <span m="111421">by</span>
  <span m="111763">one</span> <span m="112105">process</span> <span m="112447">will</span>
  <span m="112790">be</span> <span m="113132">able</span> <span m="113474">to</span>
  <span m="113816">be</span> <span m="114158">read</span> <span m="114500">by</span>
  <span m="114842">the</span> <span m="115184">other</span> <span m="115526">process.</span></p><p><span
  m="115869">To</span> <span m="116205">make</span> <span m="116541">it</span> <span
  m="116878">easier</span> <span m="117214">to</span> <span m="117551">coordinate</span>
  <span m="117887">the</span> <span m="118224">processes'</span> <span m="118560">communicating</span>
  <span m="118896">via</span> <span m="119233">shared</span> <span m="119569">memory,</span>
  <span m="119906">we'll</span> <span m="120242">see</span> <span m="120579">it's</span>
  <span m="121195">convenient</span> <span m="121812">to</span> <span m="122429">provide</span>
  <span m="123046">synchronization</span> <span m="123663">primitives.</span></p><p><span
  m="124280">Some</span> <span m="124749">ISAs</span> <span m="125219">include</span>
  <span m="125689">instructions</span> <span m="126159">that</span> <span m="126629">make</span>
  <span m="127099">it</span> <span m="127569">easy</span> <span m="128039">to</span>
  <span m="128509">do</span> <span m="128979">the</span> <span m="129449">required</span>
  <span m="129919">synchronization.</span></p><p><span m="130389">Another</span> <span
  m="130805">approach</span> <span m="131221">is</span> <span m="131637">to</span>
  <span m="132054">add</span> <span m="132470">OS</span> <span m="132886">supervisor</span>
  <span m="133303">calls</span> <span m="133719">to</span> <span m="134135">pass</span>
  <span m="134552">messages</span> <span m="134968">from</span> <span m="135384">one</span>
  <span m="135801">process</span> <span m="136217">to</span> <span m="136633">another.</span></p><p><span
  m="137050">Message</span> <span m="137543">passing</span> <span m="138036">involves</span>
  <span m="138529">more</span> <span m="139022">overhead</span> <span m="139515">than</span>
  <span m="140008">shared</span> <span m="140501">memory,</span> <span m="140994">but</span>
  <span m="141487">makes</span> <span m="141980">the</span> <span m="142473">application</span>
  <span m="142966">programming</span> <span m="143460">independent</span> <span m="143898">of</span>
  <span m="144336">whether</span> <span m="144775">the</span> <span m="145213">communicating</span>
  <span m="145652">processes</span> <span m="146090">are</span> <span m="146529">running</span>
  <span m="146967">on</span> <span m="147406">the</span> <span m="147844">same</span>
  <span m="148283">physical</span> <span m="148721">processor.</span></p><p><span
  m="149160">In</span> <span m="149521">this</span> <span m="149882">lecture,</span>
  <span m="150243">we'll</span> <span m="150605">use</span> <span m="150966">the</span>
  <span m="151327">classic</span> <span m="151688">producer-consumer</span> <span
  m="152050">problem</span> <span m="152411">as</span> <span m="152772">our</span>
  <span m="153133">example</span> <span m="153495">of</span> <span m="153856">concurrent</span>
  <span m="154217">processes</span> <span m="154579">that</span> <span m="154919">need</span>
  <span m="155259">to</span> <span m="155599">communicate</span> <span m="155939">and</span>
  <span m="156279">synchronize.</span></p><p><span m="156620">There</span> <span m="157208">are</span>
  <span m="157797">two</span> <span m="158386">processes:</span> <span m="158975">a</span>
  <span m="159564">producer</span> <span m="160153">and</span> <span m="160742">a</span>
  <span m="161331">consumer.</span></p><p><span m="161920">The</span> <span m="162325">producer</span>
  <span m="162730">is</span> <span m="163135">running</span> <span m="163540">in</span>
  <span m="163945">a</span> <span m="164350">loop,</span> <span m="164755">which</span>
  <span m="165160">performs</span> <span m="165565">some</span> <span m="165970">computation</span>
  <span m="166375">to</span> <span m="166780">generate</span> <span m="167185">information,</span>
  <span m="167590">in</span> <span m="167990">this</span> <span m="168390">case,</span>
  <span m="168790">a</span> <span m="169190">single</span> <span m="169590">character</span>
  <span m="169990">C.</span> <span m="170390">The</span> <span m="170790">consumer</span>
  <span m="171190">is</span> <span m="171590">also</span> <span m="171990">running</span>
  <span m="172390">a</span> <span m="172790">loop,</span> <span m="173190">which</span>
  <span m="173590">waits</span> <span m="173947">for</span> <span m="174304">the</span>
  <span m="174661">next</span> <span m="175018">character</span> <span m="175375">to</span>
  <span m="175732">arrive</span> <span m="176090">from</span> <span m="176447">the</span>
  <span m="176804">producer,</span> <span m="177161">then</span> <span m="177518">performs</span>
  <span m="177875">some</span> <span m="178232">computation</span> <span m="178590">.</span></p><p><span
  m="181120">The</span> <span m="181410">information</span> <span m="181701">passing</span>
  <span m="181992">between</span> <span m="182283">the</span> <span m="182573">producer</span>
  <span m="182864">and</span> <span m="183155">consumer</span> <span m="183446">could</span>
  <span m="183736">obviously</span> <span m="184027">be</span> <span m="184318">much</span>
  <span m="184609">more</span> <span m="184900">complicated</span> <span m="185446">than</span>
  <span m="185992">a</span> <span m="186538">single</span> <span m="187084">character.</span></p><p><span
  m="187630">For</span> <span m="187935">example,</span> <span m="188240">a</span>
  <span m="188546">compiler</span> <span m="188851">might</span> <span m="189156">produce</span>
  <span m="189462">a</span> <span m="189767">sequence</span> <span m="190072">of</span>
  <span m="190378">assembly</span> <span m="190683">language</span> <span m="190988">statements</span>
  <span m="191294">that</span> <span m="191599">are</span> <span m="191904">passed</span>
  <span m="192210">to</span> <span m="192679">the</span> <span m="193148">assembler</span>
  <span m="193617">to</span> <span m="194086">be</span> <span m="194555">converted</span>
  <span m="195024">into</span> <span m="195493">the</span> <span m="195962">appropriate</span>
  <span m="196431">binary</span> <span m="196900">representation.</span></p><p><span
  m="197370">The</span> <span m="197677">user</span> <span m="197985">interface</span>
  <span m="198292">front-end</span> <span m="198600">for</span> <span m="198907">a</span>
  <span m="199215">video</span> <span m="199522">game</span> <span m="199830">might</span>
  <span m="200137">pass</span> <span m="200445">a</span> <span m="200752">sequence</span>
  <span m="201060">of</span> <span m="201367">player</span> <span m="201675">actions</span>
  <span m="201982">to</span> <span m="202290">the</span> <span m="202684">simulation</span>
  <span m="203078">and</span> <span m="203472">rendering</span> <span m="203866">back-end.</span></p><p><span
  m="204260">In</span> <span m="204706">fact,</span> <span m="205153">the</span> <span
  m="205600">notion</span> <span m="206047">of</span> <span m="206494">hooking</span>
  <span m="206941">multiple</span> <span m="207388">processes</span> <span m="207835">together</span>
  <span m="208281">in</span> <span m="208728">a</span> <span m="209175">processing</span>
  <span m="209622">pipeline</span> <span m="210069">is</span> <span m="210516">so</span>
  <span m="210963">useful</span> <span m="211410">that</span> <span m="211757">the</span>
  <span m="212104">Unix</span> <span m="212451">and</span> <span m="212798">Linux</span>
  <span m="213145">operating</span> <span m="213492">systems</span> <span m="213840">provide</span>
  <span m="214187">a</span> <span m="214534">PIPE</span> <span m="214881">primitive</span>
  <span m="215228">in</span> <span m="215575">the</span> <span m="215922">operating</span>
  <span m="216270">system</span> <span m="216568">that</span> <span m="216867">connects</span>
  <span m="217166">the</span> <span m="217465">output</span> <span m="217764">channel</span>
  <span m="218063">of</span> <span m="218362">the</span> <span m="218661">upstream</span>
  <span m="218960">process</span> <span m="219475">to</span> <span m="219991">the</span>
  <span m="220506">input</span> <span m="221022">channel</span> <span m="221537">of</span>
  <span m="222053">the</span> <span m="222568">downstream</span> <span m="223084">process.</span></p><p><span
  m="223600">Let's</span> <span m="223965">look</span> <span m="224330">at</span>
  <span m="224695">a</span> <span m="225060">timing</span> <span m="225425">diagram</span>
  <span m="225790">for</span> <span m="226155">the</span> <span m="226520">actions</span>
  <span m="226885">of</span> <span m="227250">our</span> <span m="227615">simple</span>
  <span m="227980">producer/consumer</span> <span m="228345">example.</span></p><p><span
  m="228710">We'll</span> <span m="229151">use</span> <span m="229593">arrows</span>
  <span m="230035">to</span> <span m="230477">indicate</span> <span m="230919">when</span>
  <span m="231360">one</span> <span m="231802">action</span> <span m="232244">happens</span>
  <span m="232686">before</span> <span m="233128">another.</span></p><p><span m="233570">Inside</span>
  <span m="233945">a</span> <span m="234321">single</span> <span m="234696">process,</span>
  <span m="235072">e.g.,</span> <span m="235448">the</span> <span m="235823">producer,</span>
  <span m="236199">the</span> <span m="236575">order</span> <span m="236950">of</span>
  <span m="237326">execution</span> <span m="237702">implies</span> <span m="238077">a</span>
  <span m="238453">particular</span> <span m="238829">ordering</span> <span m="239268">in</span>
  <span m="239707">time:</span> <span m="240146">the</span> <span m="240585">first</span>
  <span m="241024">execution</span> <span m="241463">of</span> <span m="241902">is</span>
  <span m="242341">followed</span> <span m="242780">by</span> <span m="243220">the</span>
  <span m="243613">sending</span> <span m="244006">of</span> <span m="244400">the</span>
  <span m="244793">first</span> <span m="245186">character.</span></p><p><span m="245580">Then</span>
  <span m="245880">there's</span> <span m="246181">the</span> <span m="246482">second</span>
  <span m="246782">execution</span> <span m="247083">of</span> <span m="247384">,</span>
  <span m="247684">followed</span> <span m="247985">by</span> <span m="248286">the</span>
  <span m="248586">sending</span> <span m="248887">of</span> <span m="249188">the</span>
  <span m="249488">second</span> <span m="249789">character,</span> <span m="250090">and</span>
  <span m="250676">so</span> <span m="251263">on.</span></p><p><span m="251850">In</span>
  <span m="252137">later</span> <span m="252425">examples,</span> <span m="252713">we'll</span>
  <span m="253001">omit</span> <span m="253289">the</span> <span m="253577">timing</span>
  <span m="253865">arrows</span> <span m="254152">between</span> <span m="254440">successive</span>
  <span m="254728">statements</span> <span m="255016">in</span> <span m="255304">the</span>
  <span m="255592">same</span> <span m="255880">program.</span></p><p><span m="258149">We</span>
  <span m="258493">see</span> <span m="258838">a</span> <span m="259183">similar</span>
  <span m="259527">order</span> <span m="259872">of</span> <span m="260217">execution</span>
  <span m="260561">in</span> <span m="260906">the</span> <span m="261251">consumer:</span>
  <span m="261595">the</span> <span m="261940">first</span> <span m="262285">character</span>
  <span m="262629">is</span> <span m="262974">received,</span> <span m="263319">then</span>
  <span m="263786">the</span> <span m="264253">computation</span> <span m="264720">is</span>
  <span m="265187">performed</span> <span m="265654">for</span> <span m="266121">the</span>
  <span m="266588">first</span> <span m="267055">time,</span> <span m="267522">etc.</span></p><p><span
  m="267990">Inside</span> <span m="268320">of</span> <span m="268651">each</span>
  <span m="268982">process,</span> <span m="269312">the</span> <span m="269643">process'</span>
  <span m="269974">program</span> <span m="270305">counter</span> <span m="270635">is</span>
  <span m="270966">determining</span> <span m="271297">the</span> <span m="271627">order</span>
  <span m="271958">in</span> <span m="272289">which</span> <span m="272620">the</span>
  <span m="273249">computations</span> <span m="273879">are</span> <span m="274509">performed.</span></p><p><span
  m="275139">So</span> <span m="275501">far,</span> <span m="275864">so</span> <span
  m="276227">good</span> <span m="276589">-</span> <span m="276952">each</span> <span
  m="277315">process</span> <span m="277678">is</span> <span m="278040">running</span>
  <span m="278403">as</span> <span m="278766">expected.</span></p><p><span m="279129">However,</span>
  <span m="279474">for</span> <span m="279819">the</span> <span m="280165">producer/consumer</span>
  <span m="280510">system</span> <span m="280856">to</span> <span m="281201">function</span>
  <span m="281547">correctly</span> <span m="281892">as</span> <span m="282238">a</span>
  <span m="282583">whole,</span> <span m="282929">we'll</span> <span m="283274">need</span>
  <span m="283620">to</span> <span m="284096">introduce</span> <span m="284573">some</span>
  <span m="285050">additional</span> <span m="285527">constraints</span> <span m="286004">on</span>
  <span m="286481">the</span> <span m="286958">order</span> <span m="287435">of</span>
  <span m="287912">execution.</span></p><p><span m="288389">These</span> <span m="288771">are</span>
  <span m="289154">called</span> <span m="289536">&quot;precedence</span> <span m="289919">constraints&quot;</span>
  <span m="290301">and</span> <span m="290684">we'll</span> <span m="291066">use</span>
  <span m="291449">this</span> <span m="291831">stylized</span> <span m="292214">less-than</span>
  <span m="292596">sign</span> <span m="292979">to</span> <span m="293633">indicate</span>
  <span m="294287">that</span> <span m="294941">computation</span> <span m="295596">A</span>
  <span m="296250">must</span> <span m="296904">precede,</span> <span m="297558">i.e.,</span>
  <span m="298213">come</span> <span m="298867">before,</span> <span m="299521">computation</span>
  <span m="300175">B.</span></p><p><span m="300830">In</span> <span m="301203">the</span>
  <span m="301577">producer/consumer</span> <span m="301950">system</span> <span m="302324">we</span>
  <span m="302697">can't</span> <span m="303071">consume</span> <span m="303445">data</span>
  <span m="303818">before</span> <span m="304192">it's</span> <span m="304565">been</span>
  <span m="304939">produced,</span> <span m="305312">a</span> <span m="305686">constraint</span>
  <span m="306060">we</span> <span m="306453">can</span> <span m="306846">formalize</span>
  <span m="307239">as</span> <span m="307632">requiring</span> <span m="308025">that</span>
  <span m="308418">the</span> <span m="308811">i_th</span> <span m="309204">send</span>
  <span m="309597">operation</span> <span m="309990">has</span> <span m="310383">to</span>
  <span m="310776">precede</span> <span m="311169">the</span> <span m="311562">i_th</span>
  <span m="311955">receive</span> <span m="312349">operation.</span></p><p><span m="313680">This</span>
  <span m="314091">timing</span> <span m="314502">constraint</span> <span m="314914">is</span>
  <span m="315325">shown</span> <span m="315737">as</span> <span m="316148">the</span>
  <span m="316560">solid</span> <span m="316971">red</span> <span m="317382">arrow</span>
  <span m="317794">in</span> <span m="318205">the</span> <span m="318617">timing</span>
  <span m="319028">diagram.</span></p><p><span m="319440">Assuming</span> <span m="319759">we're</span>
  <span m="320078">using,</span> <span m="320397">say,</span> <span m="320717">a</span>
  <span m="321036">shared</span> <span m="321355">memory</span> <span m="321675">location</span>
  <span m="321994">to</span> <span m="322313">hold</span> <span m="322632">the</span>
  <span m="322952">character</span> <span m="323271">being</span> <span m="323590">transmitted</span>
  <span m="323910">from</span> <span m="324250">the</span> <span m="324591">producer</span>
  <span m="324932">to</span> <span m="325272">the</span> <span m="325613">consumer,</span>
  <span m="325954">we</span> <span m="326295">need</span> <span m="326635">to</span>
  <span m="326976">ensure</span> <span m="327317">that</span> <span m="327657">the</span>
  <span m="327998">producer</span> <span m="328339">doesn't</span> <span m="328680">overwrite</span>
  <span m="329010">the</span> <span m="329341">previous</span> <span m="329672">character</span>
  <span m="330003">before</span> <span m="330334">it's</span> <span m="330665">been</span>
  <span m="330996">read</span> <span m="331327">by</span> <span m="331658">the</span>
  <span m="331989">consumer.</span></p><p><span m="332320">In</span> <span m="332910">other</span>
  <span m="333500">words,</span> <span m="334090">we</span> <span m="334680">require</span>
  <span m="335270">the</span> <span m="335860">i_th</span> <span m="336450">receive</span>
  <span m="337040">to</span> <span m="337630">precede</span> <span m="338220">the</span>
  <span m="338810">i+1_st</span> <span m="339400">send.</span></p><p><span m="339990">These</span>
  <span m="340393">timing</span> <span m="340797">constraints</span> <span m="341200">are</span>
  <span m="341604">shown</span> <span m="342007">as</span> <span m="342411">the</span>
  <span m="342814">dotted</span> <span m="343218">red</span> <span m="343621">arrows</span>
  <span m="344025">in</span> <span m="344428">the</span> <span m="344832">timing</span>
  <span m="345235">diagram.</span></p><p><span m="345639">Together</span> <span m="345949">these</span>
  <span m="346260">precedence</span> <span m="346571">constraints</span> <span m="346882">mean</span>
  <span m="347193">that</span> <span m="347504">the</span> <span m="347815">producer</span>
  <span m="348126">and</span> <span m="348437">consumer</span> <span m="348748">are</span>
  <span m="349059">tightly</span> <span m="349370">coupled</span> <span m="349632">in</span>
  <span m="349895">the</span> <span m="350158">sense</span> <span m="350421">that</span>
  <span m="350684">a</span> <span m="350947">character</span> <span m="351210">has</span>
  <span m="351473">to</span> <span m="351736">be</span> <span m="351999">read</span>
  <span m="352262">by</span> <span m="352525">the</span> <span m="352788">consumer</span>
  <span m="353051">before</span> <span m="353314">the</span> <span m="353577">next</span>
  <span m="353840">character</span> <span m="354227">can</span> <span m="354615">be</span>
  <span m="355003">sent</span> <span m="355391">by</span> <span m="355779">the</span>
  <span m="356167">producer,</span> <span m="356555">which</span> <span m="356943">might</span>
  <span m="357331">be</span> <span m="357719">less</span> <span m="358107">than</span>
  <span m="358495">optimal</span> <span m="358883">if</span> <span m="359271">the</span>
  <span m="359659">and</span> <span m="360237">computations</span> <span m="360816">take</span>
  <span m="361395">a</span> <span m="361974">variable</span> <span m="362552">amount</span>
  <span m="363131">of</span> <span m="363710">time.</span></p><p><span m="364289">So</span>
  <span m="364654">let's</span> <span m="365020">see</span> <span m="365385">how</span>
  <span m="365751">we</span> <span m="366117">can</span> <span m="366482">relax</span>
  <span m="366848">the</span> <span m="367214">constraints</span> <span m="367579">to</span>
  <span m="367945">allow</span> <span m="368310">for</span> <span m="368676">more</span>
  <span m="369042">independence</span> <span m="369407">between</span> <span m="369773">the</span>
  <span m="370139">producer</span> <span m="370982">and</span> <span m="371825">consumer.</span></p><p><span
  m="372669">We</span> <span m="373011">can</span> <span m="373353">relax</span> <span
  m="373695">the</span> <span m="374037">execution</span> <span m="374379">constraints</span>
  <span m="374721">on</span> <span m="375063">the</span> <span m="375405">producer</span>
  <span m="375747">and</span> <span m="376089">consumer</span> <span m="376431">by</span>
  <span m="376773">having</span> <span m="377115">them</span> <span m="377457">communicate</span>
  <span m="377800">via</span> <span m="378953">N-character</span> <span m="380107">first-in-first-out</span>
  <span m="381261">(FIFO)</span> <span m="382415">buffer.</span></p><p><span m="383569">As</span>
  <span m="383956">the</span> <span m="384343">producer</span> <span m="384731">produces</span>
  <span m="385118">characters</span> <span m="385505">it</span> <span m="385893">inserts</span>
  <span m="386280">them</span> <span m="386667">into</span> <span m="387055">the</span>
  <span m="387442">buffer.</span></p><p><span m="387830">The</span> <span m="388137">consumer</span>
  <span m="388445">reads</span> <span m="388753">characters</span> <span m="389061">from</span>
  <span m="389369">the</span> <span m="389677">buffer</span> <span m="389985">in</span>
  <span m="390293">the</span> <span m="390601">same</span> <span m="390909">order</span>
  <span m="391217">as</span> <span m="391525">they</span> <span m="391833">were</span>
  <span m="392141">produced.</span></p><p><span m="392449">The</span> <span m="392866">buffer</span>
  <span m="393284">can</span> <span m="393702">hold</span> <span m="394120">between</span>
  <span m="394538">0</span> <span m="394956">and</span> <span m="395374">N</span>
  <span m="395792">characters.</span></p><p><span m="396210">If</span> <span m="396574">the</span>
  <span m="396939">buffer</span> <span m="397304">holds</span> <span m="397668">0</span>
  <span m="398033">characters,</span> <span m="398398">it's</span> <span m="398762">empty;</span>
  <span m="399127">if</span> <span m="399492">it</span> <span m="399856">holds</span>
  <span m="400221">N</span> <span m="400586">characters,</span> <span m="400950">it's</span>
  <span m="401315">full.</span></p><p><span m="401680">The</span> <span m="401965">producer</span>
  <span m="402250">should</span> <span m="402535">wait</span> <span m="402820">if</span>
  <span m="403105">the</span> <span m="403390">buffer</span> <span m="403675">is</span>
  <span m="403960">full,</span> <span m="404245">the</span> <span m="404530">consumer</span>
  <span m="404815">should</span> <span m="405100">wait</span> <span m="405385">if</span>
  <span m="405670">the</span> <span m="405955">buffer</span> <span m="406240">is</span>
  <span m="407374">empty.</span></p><p><span m="408509">Using</span> <span m="408889">the</span>
  <span m="409269">N-character</span> <span m="409649">FIFO</span> <span m="410029">buffer</span>
  <span m="410409">relaxes</span> <span m="410789">our</span> <span m="411169">second</span>
  <span m="411549">overwrite</span> <span m="411929">constraint</span> <span m="412309">to</span>
  <span m="412689">the</span> <span m="413069">requirement</span> <span m="413449">that</span>
  <span m="413985">the</span> <span m="414522">i_th</span> <span m="415059">receive</span>
  <span m="415595">must</span> <span m="416132">happen</span> <span m="416669">before</span>
  <span m="417205">i+N_th</span> <span m="417742">send.</span></p><p><span m="418279">In</span>
  <span m="418650">other</span> <span m="419021">words,</span> <span m="419393">the</span>
  <span m="419764">producer</span> <span m="420136">can</span> <span m="420507">get</span>
  <span m="420878">up</span> <span m="421250">to</span> <span m="421621">N</span>
  <span m="421993">characters</span> <span m="422364">ahead</span> <span m="422735">of</span>
  <span m="423107">the</span> <span m="423478">consumer.</span></p><p><span m="423850">FIFO</span>
  <span m="424292">buffers</span> <span m="424734">are</span> <span m="425177">implemented</span>
  <span m="425619">as</span> <span m="426062">an</span> <span m="426504">N-element</span>
  <span m="426946">character</span> <span m="427389">array</span> <span m="427831">with</span>
  <span m="428274">two</span> <span m="428716">indices:</span> <span m="429159">the</span>
  <span m="429510">read</span> <span m="429861">index</span> <span m="430213">indicates</span>
  <span m="430564">the</span> <span m="430916">next</span> <span m="431267">character</span>
  <span m="431618">to</span> <span m="431970">be</span> <span m="432321">read,</span>
  <span m="432673">the</span> <span m="433024">write</span> <span m="433375">index</span>
  <span m="433727">indicates</span> <span m="434078">the</span> <span m="434430">next</span>
  <span m="434736">character</span> <span m="435042">to</span> <span m="435348">be</span>
  <span m="435654">written.</span></p><p><span m="435960">We'll</span> <span m="436258">also</span>
  <span m="436557">need</span> <span m="436856">a</span> <span m="437155">counter</span>
  <span m="437453">to</span> <span m="437752">keep</span> <span m="438051">track</span>
  <span m="438350">of</span> <span m="438648">the</span> <span m="438947">number</span>
  <span m="439246">of</span> <span m="439545">characters</span> <span m="439843">held</span>
  <span m="440142">by</span> <span m="440441">the</span> <span m="440740">buffer,</span>
  <span m="441039">but</span> <span m="441356">that's</span> <span m="441673">been</span>
  <span m="441990">omitted</span> <span m="442307">from</span> <span m="442624">this</span>
  <span m="442941">diagram.</span></p><p><span m="443259">The</span> <span m="443677">indices</span>
  <span m="444095">are</span> <span m="444513">incremented</span> <span m="444931">modulo</span>
  <span m="445349">N,</span> <span m="445767">i.e.,</span> <span m="446185">the</span>
  <span m="446603">next</span> <span m="447021">element</span> <span m="447439">to</span>
  <span m="447857">be</span> <span m="448275">accessed</span> <span m="448693">after</span>
  <span m="449111">the</span> <span m="449529">N-1_st</span> <span m="450049">element</span>
  <span m="450569">is</span> <span m="451089">the</span> <span m="451609">0_th</span>
  <span m="452129">element,</span> <span m="452649">hence</span> <span m="453169">the</span>
  <span m="453689">name</span> <span m="454209">&quot;circular</span> <span m="454729">buffer&quot;.</span></p><p><span
  m="455249">Here's</span> <span m="455599">how</span> <span m="455949">it</span>
  <span m="456299">works.</span></p><p><span m="456650">The</span> <span m="457008">producer</span>
  <span m="457367">runs,</span> <span m="457725">using</span> <span m="458084">the</span>
  <span m="458443">write</span> <span m="458801">index</span> <span m="459160">to</span>
  <span m="459518">add</span> <span m="459877">the</span> <span m="460236">first</span>
  <span m="460594">character</span> <span m="460953">to</span> <span m="461311">the</span>
  <span m="461670">buffer.</span></p><p><span m="462029">The</span> <span m="462505">producer</span>
  <span m="462981">can</span> <span m="463458">produce</span> <span m="463934">additional</span>
  <span m="464411">characters,</span> <span m="464887">but</span> <span m="465364">must</span>
  <span m="465840">wait</span> <span m="466316">once</span> <span m="466793">the</span>
  <span m="467269">buffer</span> <span m="467746">is</span> <span m="468222">full.</span></p><p><span
  m="468699">The</span> <span m="469001">consumer</span> <span m="469304">can</span>
  <span m="469606">receive</span> <span m="469909">a</span> <span m="470211">character</span>
  <span m="470514">anytime</span> <span m="470816">the</span> <span m="471119">buffer</span>
  <span m="471421">is</span> <span m="471724">not</span> <span m="472026">empty,</span>
  <span m="472329">using</span> <span m="472631">the</span> <span m="472934">read</span>
  <span m="473236">index</span> <span m="473539">to</span> <span m="473949">keep</span>
  <span m="474359">track</span> <span m="474769">of</span> <span m="475179">the</span>
  <span m="475589">next</span> <span m="475999">character</span> <span m="476409">to</span>
  <span m="476819">be</span> <span m="477229">read.</span></p><p><span m="477639">Execution</span>
  <span m="477926">of</span> <span m="478214">the</span> <span m="478501">producer</span>
  <span m="478789">and</span> <span m="479076">consumer</span> <span m="479364">can</span>
  <span m="479651">proceed</span> <span m="479939">in</span> <span m="480227">any</span>
  <span m="480514">order</span> <span m="480802">so</span> <span m="481089">long</span>
  <span m="481377">as</span> <span m="481664">the</span> <span m="481952">producer</span>
  <span m="482240">doesn't</span> <span m="482612">write</span> <span m="482985">into</span>
  <span m="483358">a</span> <span m="483730">full</span> <span m="484103">buffer</span>
  <span m="484476">and</span> <span m="484848">the</span> <span m="485221">consumer</span>
  <span m="485594">doesn't</span> <span m="485966">read</span> <span m="486339">from</span>
  <span m="486712">an</span> <span m="487084">empty</span> <span m="487457">buffer.</span></p><p><span
  m="487830">Here's</span> <span m="488165">what</span> <span m="488501">the</span>
  <span m="488837">code</span> <span m="489173">for</span> <span m="489509">the</span>
  <span m="489845">producer</span> <span m="490180">and</span> <span m="490516">consumer</span>
  <span m="490852">might</span> <span m="491188">look</span> <span m="491524">like.</span></p><p><span
  m="491860">The</span> <span m="492127">array</span> <span m="492394">and</span>
  <span m="492661">indices</span> <span m="492928">for</span> <span m="493195">the</span>
  <span m="493462">circular</span> <span m="493729">buffer</span> <span m="493996">live</span>
  <span m="494263">in</span> <span m="494530">shared</span> <span m="494797">memory</span>
  <span m="495064">where</span> <span m="495331">they</span> <span m="495598">can</span>
  <span m="495865">be</span> <span m="496132">accessed</span> <span m="496400">by</span>
  <span m="497086">both</span> <span m="497773">processes.</span></p><p><span m="498460">The</span>
  <span m="498744">SEND</span> <span m="499029">routine</span> <span m="499314">in</span>
  <span m="499599">the</span> <span m="499884">producer</span> <span m="500169">uses</span>
  <span m="500454">the</span> <span m="500739">write</span> <span m="501024">index</span>
  <span m="501309">IN</span> <span m="501594">to</span> <span m="501879">keep</span>
  <span m="502164">track</span> <span m="502449">of</span> <span m="502734">where</span>
  <span m="503019">to</span> <span m="503304">write</span> <span m="503589">the</span>
  <span m="504135">next</span> <span m="504682">character.</span></p><p><span m="505229">Similarly</span>
  <span m="505526">the</span> <span m="505823">RCV</span> <span m="506120">routine</span>
  <span m="506417">in</span> <span m="506714">the</span> <span m="507011">consumer</span>
  <span m="507308">uses</span> <span m="507605">the</span> <span m="507902">read</span>
  <span m="508199">index</span> <span m="508496">OUT</span> <span m="508793">to</span>
  <span m="509090">keep</span> <span m="509387">track</span> <span m="509684">of</span>
  <span m="509981">the</span> <span m="510279">next</span> <span m="510671">character</span>
  <span m="511063">to</span> <span m="511455">be</span> <span m="511847">read.</span></p><p><span
  m="512240">After</span> <span m="512657">each</span> <span m="513075">use,</span>
  <span m="513493">each</span> <span m="513911">index</span> <span m="514328">is</span>
  <span m="514746">incremented</span> <span m="515164">modulo</span> <span m="515582">N.</span></p><p><span
  m="516000">The</span> <span m="516353">problem</span> <span m="516707">with</span>
  <span m="517061">this</span> <span m="517414">code</span> <span m="517768">is</span>
  <span m="518122">that,</span> <span m="518475">as</span> <span m="518829">currently</span>
  <span m="519183">written,</span> <span m="519536">neither</span> <span m="519890">of</span>
  <span m="520244">the</span> <span m="520597">two</span> <span m="520951">precedence</span>
  <span m="521305">constraints</span> <span m="521659">is</span> <span m="522269">enforced.</span></p><p><span
  m="522880">The</span> <span m="523186">consumer</span> <span m="523493">can</span>
  <span m="523800">read</span> <span m="524106">from</span> <span m="524413">an</span>
  <span m="524720">empty</span> <span m="525026">buffer</span> <span m="525333">and</span>
  <span m="525640">the</span> <span m="525946">producer</span> <span m="526253">can</span>
  <span m="526560">overwrite</span> <span m="526866">entries</span> <span m="527173">when</span>
  <span m="527480">the</span> <span m="527982">buffer</span> <span m="528485">is</span>
  <span m="528987">full.</span></p><p><span m="529490">We'll</span> <span m="529807">need</span>
  <span m="530124">to</span> <span m="530442">modify</span> <span m="530759">this</span>
  <span m="531076">code</span> <span m="531394">to</span> <span m="531711">enforce</span>
  <span m="532028">the</span> <span m="532346">constraints</span> <span m="532663">and</span>
  <span m="532980">for</span> <span m="533298">that</span> <span m="533615">we'll</span>
  <span m="533932">introduce</span> <span m="534250">a</span> <span m="534692">new</span>
  <span m="535134">programming</span> <span m="535576">construct</span> <span m="536019">that</span>
  <span m="536461">we'll</span> <span m="536903">use</span> <span m="537346">to</span>
  <span m="537788">provide</span> <span m="538230">the</span> <span m="538673">appropriate</span>
  <span m="539115">inter-process</span> <span m="539557">synchronization.</span></p>
type: course
uid: ab59526cc23163073379ef25ce4685a1

---
None