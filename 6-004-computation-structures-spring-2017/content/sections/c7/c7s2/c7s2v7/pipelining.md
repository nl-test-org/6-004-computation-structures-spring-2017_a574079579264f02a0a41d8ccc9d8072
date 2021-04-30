---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: VdLJMPppocU
  parent_uid: 9587a81a6d5cb3db056cbc02ddc3c20b
  title: Video-YouTube-Stream
  type: Video
  uid: 07b1568bca1189fd6dbe9cb3807e1e48
- id: 3Play-3Play YouTube id-Stream
  media_location: VdLJMPppocU
  parent_uid: 9587a81a6d5cb3db056cbc02ddc3c20b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: a121ee2d516ebefb9037aeaec1588472
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/VdLJMPppocU/default.jpg
  parent_uid: 9587a81a6d5cb3db056cbc02ddc3c20b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 93e6197028c72ff8d5635cf5eabb0142
- id: VdLJMPppocU.srt
  parent_uid: 9587a81a6d5cb3db056cbc02ddc3c20b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v7/pipelining/VdLJMPppocU.srt
  title: 3play caption file
  type: null
  uid: 4582f877a6b63c091521040553328837
- id: VdLJMPppocU.pdf
  parent_uid: 9587a81a6d5cb3db056cbc02ddc3c20b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v7/pipelining/VdLJMPppocU.pdf
  title: 3play pdf file
  type: null
  uid: 2786fb036c5f825a71d4d8c75723fb1d
- id: Caption-3Play YouTube id-SRT
  parent_uid: 9587a81a6d5cb3db056cbc02ddc3c20b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 16ca973df25e48134c674ff5007563a6
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 9587a81a6d5cb3db056cbc02ddc3c20b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: ec0d0b98470d5dcab9ba862e70bb80b1
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_07-02-07-01_300k.mp4
  parent_uid: 9587a81a6d5cb3db056cbc02ddc3c20b
  title: Video-Internet Archive-MP4
  type: Video
  uid: 552c6b7cf1ecdb12d076d265b4753a0b
inline_embed_id: 9676406pipelining60296325
layout: video
order_index: null
parent_uid: 1566994e2ac1dc389beafb70f2edc786
related_resources_text: ''
short_url: pipelining
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v7/pipelining
template_type: Embed
title: 'Worked Example: Pipelining'
transcript: <p><span m="1079">We</span> <span m="1522">are</span> <span m="1966">given</span>
  <span m="2410">a</span> <span m="2854">CBit</span> <span m="3298">module</span>
  <span m="3742">shown</span> <span m="4186">here.</span></p><p><span m="4630">This</span>
  <span m="5062">module</span> <span m="5494">takes</span> <span m="5926">corresponding</span>
  <span m="6358">bits</span> <span m="6790">of</span> <span m="7222">two</span> <span
  m="7654">unsigned</span> <span m="8086">binary</span> <span m="8518">numbers,</span>
  <span m="8950">A</span> <span m="9382">and</span> <span m="9814">B,</span> <span
  m="10246">along</span> <span m="10678">with</span> <span m="11110">two</span> <span
  m="11808">Cin</span> <span m="12507">bits</span> <span m="13205">from</span> <span
  m="13904">higher-order</span> <span m="14602">CBit</span> <span m="15301">modules.</span></p><p><span
  m="16000">Its</span> <span m="16350">output</span> <span m="16701">bit</span> <span
  m="17052">R,</span> <span m="17402">is</span> <span m="17753">the</span> <span m="18104">appropriate</span>
  <span m="18454">bit</span> <span m="18805">of</span> <span m="19156">the</span>
  <span m="19506">larger</span> <span m="19857">among</span> <span m="20208">A</span>
  <span m="20558">and</span> <span m="20909">B.</span></p><p><span m="21260">It</span>
  <span m="21871">also</span> <span m="22483">has</span> <span m="23095">two</span>
  <span m="23707">additional</span> <span m="24319">output</span> <span m="24931">bits</span>
  <span m="25543">Cout</span> <span m="26155">which</span> <span m="26767">indicate</span>
  <span m="27379">respectively</span> <span m="27991">if</span> <span m="28603">A&gt;B</span>
  <span m="29215">or</span> <span m="29827">B&gt;A</span> <span m="30439">in</span>
  <span m="30927">the</span> <span m="31416">bits</span> <span m="31904">considered</span>
  <span m="32393">so</span> <span m="32881">far.</span></p><p><span m="33370">The</span>
  <span m="34027">propagation</span> <span m="34685">delay</span> <span m="35343">of</span>
  <span m="36001">each</span> <span m="36658">Cbit</span> <span m="37316">module</span>
  <span m="37974">is</span> <span m="38632">4ns.</span></p><p><span m="39290">The</span>
  <span m="39685">CBit</span> <span m="40081">module</span> <span m="40476">is</span>
  <span m="40872">used</span> <span m="41268">to</span> <span m="41663">create</span>
  <span m="42059">a</span> <span m="42455">product</span> <span m="42850">MAXC</span>
  <span m="43246">which</span> <span m="43641">is</span> <span m="44037">a</span>
  <span m="44433">combinational</span> <span m="44828">device</span> <span m="45224">that</span>
  <span m="45620">determines</span> <span m="46148">the</span> <span m="46677">maximum</span>
  <span m="47206">of</span> <span m="47735">its</span> <span m="48264">two</span>
  <span m="48793">4-bit</span> <span m="49322">unsigned</span> <span m="49851">binary</span>
  <span m="50380">inputs.</span></p><p><span m="50909">It</span> <span m="51450">is</span>
  <span m="51991">constructed</span> <span m="52532">using</span> <span m="53073">4</span>
  <span m="53614">CBit</span> <span m="54155">modules</span> <span m="54696">as</span>
  <span m="55237">shown</span> <span m="55778">here.</span></p><p><span m="56320">The</span>
  <span m="56649">first</span> <span m="56978">question</span> <span m="57308">we</span>
  <span m="57637">want</span> <span m="57966">to</span> <span m="58296">consider</span>
  <span m="58625">is</span> <span m="58954">what</span> <span m="59284">are</span>
  <span m="59613">the</span> <span m="59942">propagation</span> <span m="60272">delay</span>
  <span m="60601">and</span> <span m="60930">throughput</span> <span m="61260">of</span>
  <span m="61965">this</span> <span m="62670">combinational</span> <span m="63375">circuit?</span></p><p><span
  m="64080">The</span> <span m="64477">propagation</span> <span m="64874">delay</span>
  <span m="65271">of</span> <span m="65668">a</span> <span m="66065">combinational</span>
  <span m="66462">circuit</span> <span m="66860">is</span> <span m="67257">the</span>
  <span m="67654">propagation</span> <span m="68051">delay</span> <span m="68448">along</span>
  <span m="68845">its</span> <span m="69242">longest</span> <span m="69640">path</span>
  <span m="70178">from</span> <span m="70716">input</span> <span m="71254">to</span>
  <span m="71792">output.</span></p><p><span m="72330">In</span> <span m="72790">this</span>
  <span m="73251">case,</span> <span m="73712">the</span> <span m="74173">longest</span>
  <span m="74634">path</span> <span m="75095">is</span> <span m="75556">through</span>
  <span m="76017">4</span> <span m="76478">CBit</span> <span m="76939">modules.</span></p><p><span
  m="77400">Since</span> <span m="77825">each</span> <span m="78250">CBit</span> <span
  m="78675">module</span> <span m="79101">has</span> <span m="79526">a</span> <span
  m="79951">propagation</span> <span m="80377">delay</span> <span m="80802">of</span>
  <span m="81227">4</span> <span m="81652">ns,</span> <span m="82078">the</span> <span
  m="82503">propagation</span> <span m="82928">delay</span> <span m="83354">of</span>
  <span m="83779">this</span> <span m="84204">combinational</span> <span m="84630">circuit</span>
  <span m="85396">is</span> <span m="86163">4</span> <span m="86930">*</span> <span
  m="87696">4</span> <span m="88463">ns</span> <span m="89230">=</span> <span m="89996">16</span>
  <span m="90763">ns.</span></p><p><span m="91530">The</span> <span m="91954">throughput</span>
  <span m="92379">of</span> <span m="92804">a</span> <span m="93228">combinational</span>
  <span m="93653">circuit</span> <span m="94078">is</span> <span m="94502">1</span>
  <span m="94927">/</span> <span m="95352">Latency,</span> <span m="95776">so</span>
  <span m="96201">the</span> <span m="96626">throughput</span> <span m="97050">of</span>
  <span m="97475">this</span> <span m="97900">circuit</span> <span m="98839">is</span>
  <span m="99779">1</span> <span m="100719">/</span> <span m="101659">(16</span> <span
  m="102599">ns).</span></p><p><span m="103539">The</span> <span m="103863">next</span>
  <span m="104188">question</span> <span m="104512">we</span> <span m="104837">want</span>
  <span m="105161">to</span> <span m="105486">consider</span> <span m="105810">is</span>
  <span m="106135">what</span> <span m="106459">two</span> <span m="106784">bits</span>
  <span m="107108">would</span> <span m="107433">we</span> <span m="107757">expect</span>
  <span m="108082">to</span> <span m="108406">see</span> <span m="108731">coming</span>
  <span m="109055">out</span> <span m="109380">of</span> <span m="110145">the</span>
  <span m="110911">(unused)</span> <span m="111677">Cout</span> <span m="112443">outputs</span>
  <span m="113209">from</span> <span m="113975">the</span> <span m="114740">low-order</span>
  <span m="115506">CBit</span> <span m="116272">module</span> <span m="117038">if</span>
  <span m="117804">A3:0</span> <span m="118570">and</span> <span m="119300">B3:0</span>
  <span m="120030">are</span> <span m="120760">identical</span> <span m="121490">numbers.</span></p><p><span
  m="122220">The</span> <span m="123003">Cout[1]</span> <span m="123787">bit</span>
  <span m="124570">indicates</span> <span m="125354">whether</span> <span m="126138">A&gt;B</span>
  <span m="126921">and</span> <span m="127705">the</span> <span m="128489">Cout[0]</span>
  <span m="129272">bit</span> <span m="130056">indicates</span> <span m="130840">whether</span>
  <span m="131414">B&gt;A.</span> <span m="131988">Since</span> <span m="132563">the</span>
  <span m="133137">numbers</span> <span m="133712">are</span> <span m="134286">identical</span>
  <span m="134861">neither</span> <span m="135435">of</span> <span m="136010">these</span>
  <span m="136496">inequalities</span> <span m="136982">is</span> <span m="137468">true,</span>
  <span m="137954">so</span> <span m="138440">both</span> <span m="138926">Cout</span>
  <span m="139412">bits</span> <span m="139898">are</span> <span m="140384">0.</span></p><p><span
  m="140870">Next,</span> <span m="141342">we</span> <span m="141814">want</span>
  <span m="142286">to</span> <span m="142758">pipeline</span> <span m="143230">this</span>
  <span m="143702">circuit</span> <span m="144174">for</span> <span m="144646">maximum</span>
  <span m="145118">throughput.</span></p><p><span m="145590">We</span> <span m="146046">are</span>
  <span m="146503">given</span> <span m="146960">ideal</span> <span m="147416">pipeline</span>
  <span m="147873">registers</span> <span m="148330">for</span> <span m="148786">this</span>
  <span m="149243">step.</span></p><p><span m="149700">Recall</span> <span m="150133">that</span>
  <span m="150566">ideal</span> <span m="150999">registers</span> <span m="151432">have</span>
  <span m="151865">a</span> <span m="152298">0</span> <span m="152731">propagation</span>
  <span m="153164">delay</span> <span m="153597">and</span> <span m="154030">0</span>
  <span m="154463">setup</span> <span m="154896">time.</span></p><p><span m="155329">In</span>
  <span m="155691">order</span> <span m="156053">to</span> <span m="156415">pipeline</span>
  <span m="156777">this</span> <span m="157139">circuit</span> <span m="157501">for</span>
  <span m="157863">maximum</span> <span m="158225">throughput,</span> <span m="158587">we</span>
  <span m="158949">want</span> <span m="159311">to</span> <span m="159673">add</span>
  <span m="160035">pipeline</span> <span m="160397">registers</span> <span m="160760">that</span>
  <span m="161170">isolate</span> <span m="161581">each</span> <span m="161992">individual</span>
  <span m="162403">CBit</span> <span m="162814">to</span> <span m="163225">be</span>
  <span m="163635">in</span> <span m="164046">its</span> <span m="164457">own</span>
  <span m="164868">pipeline</span> <span m="165279">stage.</span></p><p><span m="165690">Recall,</span>
  <span m="166083">that</span> <span m="166477">when</span> <span m="166871">pipelining</span>
  <span m="167265">a</span> <span m="167659">circuit,</span> <span m="168053">we</span>
  <span m="168447">want</span> <span m="168841">to</span> <span m="169235">add</span>
  <span m="169629">pipeline</span> <span m="170023">registers</span> <span m="170417">to</span>
  <span m="170811">all</span> <span m="171205">the</span> <span m="171599">outputs,</span>
  <span m="172051">so</span> <span m="172503">we</span> <span m="172955">begin</span>
  <span m="173407">by</span> <span m="173860">adding</span> <span m="174312">a</span>
  <span m="174764">contour</span> <span m="175216">that</span> <span m="175668">goes</span>
  <span m="176121">across</span> <span m="176573">all</span> <span m="177025">4</span>
  <span m="177477">outputs.</span></p><p><span m="177930">We</span> <span m="178324">now</span>
  <span m="178718">want</span> <span m="179112">to</span> <span m="179506">isolate</span>
  <span m="179900">the</span> <span m="180294">low</span> <span m="180688">order</span>
  <span m="181082">CBit</span> <span m="181476">module.</span></p><p><span m="181870">To</span>
  <span m="182362">do</span> <span m="182855">this</span> <span m="183347">we</span>
  <span m="183840">draw</span> <span m="184332">an</span> <span m="184825">additional</span>
  <span m="185317">contour</span> <span m="185810">that</span> <span m="186302">crosses</span>
  <span m="186795">the</span> <span m="187287">outputs</span> <span m="187780">R3-R1,</span>
  <span m="188272">then</span> <span m="188765">passes</span> <span m="189257">between</span>
  <span m="189750">the</span> <span m="190276">two</span> <span m="190802">low</span>
  <span m="191329">order</span> <span m="191855">CBit</span> <span m="192382">modules</span>
  <span m="192908">and</span> <span m="193435">finally</span> <span m="193961">crosses</span>
  <span m="194487">the</span> <span m="195014">A0</span> <span m="195540">and</span>
  <span m="196067">B0</span> <span m="196593">inputs.</span></p><p><span m="197120">Remember</span>
  <span m="197460">that</span> <span m="197801">every</span> <span m="198141">time</span>
  <span m="198482">a</span> <span m="198822">contour</span> <span m="199163">crosses</span>
  <span m="199504">a</span> <span m="199844">wire,</span> <span m="200185">it</span>
  <span m="200525">means</span> <span m="200866">that</span> <span m="201207">we</span>
  <span m="201547">are</span> <span m="201888">adding</span> <span m="202228">a</span>
  <span m="202569">pipeline</span> <span m="202910">register.</span></p><p><span m="204210">So</span>
  <span m="204705">this</span> <span m="205200">first</span> <span m="205695">step</span>
  <span m="206190">added</span> <span m="206685">6</span> <span m="207180">pipeline</span>
  <span m="207675">registers,</span> <span m="208170">one</span> <span m="208665">for</span>
  <span m="209160">each</span> <span m="209655">of</span> <span m="210150">R3,</span>
  <span m="210645">R2,</span> <span m="211140">and</span> <span m="211635">R1,</span>
  <span m="212130">another</span> <span m="212625">between</span> <span m="213120">the</span>
  <span m="213602">two</span> <span m="214085">CBit</span> <span m="214568">modules</span>
  <span m="215051">and</span> <span m="215533">the</span> <span m="216016">last</span>
  <span m="216499">2</span> <span m="216982">on</span> <span m="217465">the</span>
  <span m="217947">A0</span> <span m="218430">and</span> <span m="218913">B0</span>
  <span m="219396">inputs.</span></p><p><span m="219879">Notice</span> <span m="220234">that</span>
  <span m="220590">regardless</span> <span m="220946">of</span> <span m="221302">which</span>
  <span m="221658">input</span> <span m="222014">to</span> <span m="222370">output</span>
  <span m="222726">path</span> <span m="223082">we</span> <span m="223438">look</span>
  <span m="223794">at</span> <span m="224150">the</span> <span m="224506">number</span>
  <span m="224862">of</span> <span m="225218">pipeline</span> <span m="225574">registers</span>
  <span m="225930">along</span> <span m="226431">the</span> <span m="226932">path</span>
  <span m="227434">so</span> <span m="227935">far</span> <span m="228437">is</span>
  <span m="228938">2.</span></p><p><span m="229440">We</span> <span m="230185">continue</span>
  <span m="230931">in</span> <span m="231677">this</span> <span m="232422">manner</span>
  <span m="233168">isolating</span> <span m="233914">each</span> <span m="234660">Cbit</span>
  <span m="235405">module</span> <span m="236151">into</span> <span m="236897">its</span>
  <span m="237642">own</span> <span m="238388">pipeline</span> <span m="239134">stage.</span></p><p><span
  m="239880">Now</span> <span m="240204">that</span> <span m="240528">each</span>
  <span m="240852">CBit</span> <span m="241177">module</span> <span m="241501">has</span>
  <span m="241825">been</span> <span m="242150">placed</span> <span m="242474">into</span>
  <span m="242798">its</span> <span m="243123">own</span> <span m="243447">pipeline</span>
  <span m="243771">stage,</span> <span m="244096">we</span> <span m="244420">can</span>
  <span m="244744">clock</span> <span m="245069">this</span> <span m="245647">circuit</span>
  <span m="246225">for</span> <span m="246803">maximum</span> <span m="247381">througput.</span></p><p><span
  m="247959">Our</span> <span m="248270">clock</span> <span m="248581">period</span>
  <span m="248893">must</span> <span m="249204">allow</span> <span m="249516">for</span>
  <span m="249827">enough</span> <span m="250138">time</span> <span m="250450">for</span>
  <span m="250761">the</span> <span m="251073">propagation</span> <span m="251384">delay</span>
  <span m="251695">of</span> <span m="252007">the</span> <span m="252318">pipeline</span>
  <span m="252630">register,</span> <span m="253027">plus</span> <span m="253424">the</span>
  <span m="253822">propagation</span> <span m="254219">delay</span> <span m="254616">of</span>
  <span m="255014">the</span> <span m="255411">Cbit</span> <span m="255809">module,</span>
  <span m="256206">plus</span> <span m="256603">the</span> <span m="257001">setup</span>
  <span m="257398">time</span> <span m="257795">of</span> <span m="258193">the</span>
  <span m="258590">next</span> <span m="258988">pipeline</span> <span m="259893">register.</span></p><p><span
  m="260798">Since</span> <span m="261127">our</span> <span m="261456">pipeline</span>
  <span m="261786">registers</span> <span m="262115">are</span> <span m="262445">ideal,</span>
  <span m="262774">the</span> <span m="263104">propagation</span> <span m="263433">delay</span>
  <span m="263763">and</span> <span m="264092">the</span> <span m="264422">setup</span>
  <span m="264751">time</span> <span m="265081">of</span> <span m="265410">the</span>
  <span m="265740">pipeline</span> <span m="266155">registers</span> <span m="266570">is</span>
  <span m="266985">0,</span> <span m="267401">so</span> <span m="267816">the</span>
  <span m="268231">clock</span> <span m="268647">period</span> <span m="269062">is</span>
  <span m="269477">equal</span> <span m="269892">to</span> <span m="270308">the</span>
  <span m="270723">propagation</span> <span m="271138">delay</span> <span m="271554">of</span>
  <span m="271969">1</span> <span m="272384">CBit</span> <span m="272800">module</span>
  <span m="273459">which</span> <span m="274119">is</span> <span m="274779">4</span>
  <span m="275439">ns.</span></p><p><span m="276099">The</span> <span m="276426">latency</span>
  <span m="276753">of</span> <span m="277080">this</span> <span m="277407">pipelined</span>
  <span m="277734">circuit</span> <span m="278061">is</span> <span m="278388">equal</span>
  <span m="278715">to</span> <span m="279042">the</span> <span m="279369">number</span>
  <span m="279696">of</span> <span m="280023">pipeline</span> <span m="280350">stages</span>
  <span m="280677">(4</span> <span m="281004">in</span> <span m="281331">this</span>
  <span m="281659">example)</span> <span m="282299">times</span> <span m="282940">the</span>
  <span m="283580">clock</span> <span m="284221">period</span> <span m="284862">time,</span>
  <span m="285502">so</span> <span m="286143">the</span> <span m="286784">latency</span>
  <span m="287424">is</span> <span m="288065">4</span> <span m="288706">*</span> <span
  m="289346">4</span> <span m="289987">ns</span> <span m="290628">=</span> <span m="291268">16</span>
  <span m="291909">ns.</span></p><p><span m="292550">The</span> <span m="292985">throughput</span>
  <span m="293420">of</span> <span m="293856">a</span> <span m="294291">pipelined</span>
  <span m="294726">circuit</span> <span m="295162">is</span> <span m="295597">1</span>
  <span m="296032">divided</span> <span m="296468">by</span> <span m="296903">the</span>
  <span m="297338">clock</span> <span m="297774">period,</span> <span m="298209">so</span>
  <span m="298644">throughput</span> <span m="299080">is</span> <span m="299719">1</span>
  <span m="300359">/</span> <span m="300999">(4</span> <span m="301639">ns).</span></p><p><span
  m="302279">Our</span> <span m="302722">Cbit</span> <span m="303166">module</span>
  <span m="303610">can</span> <span m="304054">be</span> <span m="304497">used</span>
  <span m="304941">to</span> <span m="305385">create</span> <span m="305829">the</span>
  <span m="306272">MAX4X4</span> <span m="306716">product</span> <span m="307160">which</span>
  <span m="307604">is</span> <span m="308047">a</span> <span m="308491">combinational</span>
  <span m="308935">circuit</span> <span m="309379">capable</span> <span m="309899">of</span>
  <span m="310419">determining</span> <span m="310939">the</span> <span m="311459">maximum</span>
  <span m="311979">of</span> <span m="312499">four</span> <span m="313019">4-bit</span>
  <span m="313539">binary</span> <span m="314059">inputs.</span></p><p><span m="314580">Our</span>
  <span m="314995">first</span> <span m="315411">task</span> <span m="315826">here</span>
  <span m="316242">is</span> <span m="316657">to</span> <span m="317073">determine</span>
  <span m="317488">the</span> <span m="317904">combinational</span> <span m="318320">latency</span>
  <span m="318735">and</span> <span m="319151">throughput</span> <span m="319566">of</span>
  <span m="319982">this</span> <span m="320397">new</span> <span m="320813">circuit.</span></p><p><span
  m="321229">Looking</span> <span m="321546">carefully</span> <span m="321864">at</span>
  <span m="322182">this</span> <span m="322500">circuit,</span> <span m="322818">we</span>
  <span m="323136">see</span> <span m="323454">that</span> <span m="323772">the</span>
  <span m="324090">longest</span> <span m="324408">path</span> <span m="324726">through</span>
  <span m="325044">the</span> <span m="325362">circuit</span> <span m="325680">begins</span>
  <span m="326037">at</span> <span m="326394">the</span> <span m="326751">upper</span>
  <span m="327109">left</span> <span m="327466">CBit</span> <span m="327823">module</span>
  <span m="328180">and</span> <span m="328538">ends</span> <span m="328895">at</span>
  <span m="329252">the</span> <span m="329609">bottom</span> <span m="329967">right</span>
  <span m="330324">CBit</span> <span m="330681">module.</span></p><p><span m="331039">Counting</span>
  <span m="331383">the</span> <span m="331727">number</span> <span m="332071">of</span>
  <span m="332415">CBit</span> <span m="332759">modules</span> <span m="333103">along</span>
  <span m="333447">this</span> <span m="333791">path,</span> <span m="334136">we</span>
  <span m="334480">see</span> <span m="334824">that</span> <span m="335168">we</span>
  <span m="335512">need</span> <span m="335856">to</span> <span m="336200">cross</span>
  <span m="336544">6</span> <span m="336889">CBit</span> <span m="337499">modules.</span></p><p><span
  m="338110">This</span> <span m="338482">means</span> <span m="338855">that</span>
  <span m="339227">the</span> <span m="339600">latency</span> <span m="339972">of</span>
  <span m="340345">this</span> <span m="340718">circuit</span> <span m="341090">is</span>
  <span m="341463">L</span> <span m="341835">=</span> <span m="342208">6</span> <span
  m="342580">*</span> <span m="342953">propagation</span> <span m="343326">delay</span>
  <span m="343698">of</span> <span m="344071">a</span> <span m="344443">single</span>
  <span m="344816">CBit</span> <span m="345189">module</span> <span m="345934">=</span>
  <span m="346680">6</span> <span m="347426">*</span> <span m="348171">4</span> <span
  m="348917">ns</span> <span m="349663">=</span> <span m="350408">24</span> <span
  m="351154">ns.</span></p><p><span m="351900">The</span> <span m="352429">throughput</span>
  <span m="352959">of</span> <span m="353489">a</span> <span m="354019">combinational</span>
  <span m="354549">circuit</span> <span m="355079">is</span> <span m="355609">equal</span>
  <span m="356139">to</span> <span m="356669">1</span> <span m="357199">/</span> <span
  m="357729">Latency</span> <span m="358259">=</span> <span m="358789">1</span> <span
  m="359319">/</span> <span m="359849">(24</span> <span m="360379">ns).</span></p><p><span
  m="360909">Out</span> <span m="361417">final</span> <span m="361925">task</span>
  <span m="362434">is</span> <span m="362942">to</span> <span m="363450">pipeline</span>
  <span m="363959">this</span> <span m="364467">new</span> <span m="364975">circuit</span>
  <span m="365484">for</span> <span m="365992">maximum</span> <span m="366500">througput.</span></p><p><span
  m="367009">We</span> <span m="367356">begin</span> <span m="367704">as</span> <span
  m="368051">we</span> <span m="368399">did</span> <span m="368747">before</span>
  <span m="369094">by</span> <span m="369442">adding</span> <span m="369790">a</span>
  <span m="370137">contour</span> <span m="370485">that</span> <span m="370833">goes</span>
  <span m="371180">across</span> <span m="371528">all</span> <span m="371876">of</span>
  <span m="372223">our</span> <span m="372571">outputs.</span></p><p><span m="372919">Next</span>
  <span m="373163">we</span> <span m="373407">want</span> <span m="373651">to</span>
  <span m="373895">figure</span> <span m="374139">out</span> <span m="374383">how</span>
  <span m="374627">to</span> <span m="374871">add</span> <span m="375116">the</span>
  <span m="375360">remaining</span> <span m="375604">contours</span> <span m="375848">so</span>
  <span m="376092">that</span> <span m="376336">the</span> <span m="376580">clock</span>
  <span m="376824">period</span> <span m="377069">of</span> <span m="377541">our</span>
  <span m="378014">pipelined</span> <span m="378487">circuit</span> <span m="378960">can</span>
  <span m="379433">be</span> <span m="379906">minimized.</span></p><p><span m="380379">The</span>
  <span m="380746">clock</span> <span m="381113">period</span> <span m="381481">must</span>
  <span m="381848">allow</span> <span m="382215">enough</span> <span m="382583">time</span>
  <span m="382950">for</span> <span m="383317">the</span> <span m="383685">propagation</span>
  <span m="384052">delay</span> <span m="384419">of</span> <span m="384787">the</span>
  <span m="385154">pipeline</span> <span m="385521">register,</span> <span m="385889">plus</span>
  <span m="386250">the</span> <span m="386612">propagation</span> <span m="386974">delay</span>
  <span m="387336">of</span> <span m="387698">any</span> <span m="388060">combinational</span>
  <span m="388422">logic,</span> <span m="388784">plus</span> <span m="389146">the</span>
  <span m="389508">setup</span> <span m="389870">time</span> <span m="390232">of</span>
  <span m="390594">the</span> <span m="390956">next</span> <span m="391318">pipeline</span>
  <span m="391680">register.</span></p><p><span m="393139">Since</span> <span m="393477">our</span>
  <span m="393815">pipeline</span> <span m="394153">registers</span> <span m="394491">are</span>
  <span m="394829">ideal,</span> <span m="395167">both</span> <span m="395505">the</span>
  <span m="395843">propagation</span> <span m="396181">delay</span> <span m="396519">and</span>
  <span m="396857">the</span> <span m="397195">setup</span> <span m="397533">time</span>
  <span m="397871">of</span> <span m="398210">the</span> <span m="398561">pipeline</span>
  <span m="398913">registers</span> <span m="399265">is</span> <span m="399617">0,</span>
  <span m="399969">so</span> <span m="400320">our</span> <span m="400672">clock</span>
  <span m="401024">period</span> <span m="401376">is</span> <span m="401728">equal</span>
  <span m="402079">to</span> <span m="402431">the</span> <span m="402783">propagation</span>
  <span m="403135">delay</span> <span m="403487">of</span> <span m="403839">the</span>
  <span m="404352">combinational</span> <span m="404865">logic</span> <span m="405379">between</span>
  <span m="405892">each</span> <span m="406406">pair</span> <span m="406919">of</span>
  <span m="407433">pipeline</span> <span m="407946">registers.</span></p><p><span
  m="408460">In</span> <span m="408747">order</span> <span m="409035">to</span> <span
  m="409322">minimize</span> <span m="409610">this,</span> <span m="409897">we</span>
  <span m="410185">would</span> <span m="410473">like</span> <span m="410760">the</span>
  <span m="411048">number</span> <span m="411335">of</span> <span m="411623">CBit</span>
  <span m="411911">modules</span> <span m="412198">between</span> <span m="412486">each</span>
  <span m="412773">pair</span> <span m="413061">of</span> <span m="413349">pipeline</span>
  <span m="413829">registers</span> <span m="414309">to</span> <span m="414789">be</span>
  <span m="415269">at</span> <span m="415749">most</span> <span m="416229">1.</span></p><p><span
  m="416710">This</span> <span m="417141">would</span> <span m="417572">make</span>
  <span m="418003">our</span> <span m="418434">period,</span> <span m="418865">T</span>
  <span m="419296">=</span> <span m="419727">4</span> <span m="420158">ns.</span></p><p><span
  m="420590">To</span> <span m="420994">achieve</span> <span m="421398">this,</span>
  <span m="421803">we</span> <span m="422207">can</span> <span m="422612">draw</span>
  <span m="423016">diagonal</span> <span m="423421">contours</span> <span m="423825">through</span>
  <span m="424230">our</span> <span m="424634">circuit.</span></p><p><span m="425039">Notice</span>
  <span m="425400">that</span> <span m="425762">these</span> <span m="426124">contours</span>
  <span m="426486">result</span> <span m="426848">in</span> <span m="427210">at</span>
  <span m="427572">most</span> <span m="427934">1</span> <span m="428296">CBit</span>
  <span m="428658">module</span> <span m="429020">appearing</span> <span m="429382">between</span>
  <span m="429744">any</span> <span m="430106">pair</span> <span m="430468">of</span>
  <span m="430830">pipeline</span> <span m="431233">registers</span> <span m="431636">while</span>
  <span m="432039">at</span> <span m="432443">the</span> <span m="432846">same</span>
  <span m="433249">time</span> <span m="433652">including</span> <span m="434056">as</span>
  <span m="434459">many</span> <span m="434862">CBit</span> <span m="435265">modules</span>
  <span m="435669">that</span> <span m="436072">can</span> <span m="436475">be</span>
  <span m="436879">executed</span> <span m="437392">in</span> <span m="437906">parallel</span>
  <span m="438420">in</span> <span m="438934">a</span> <span m="439448">single</span>
  <span m="439962">pipeline</span> <span m="440476">stage.</span></p><p><span m="440990">The</span>
  <span m="441592">latter</span> <span m="442194">constraint</span> <span m="442796">will</span>
  <span m="443398">minimize</span> <span m="444001">our</span> <span m="444603">latency</span>
  <span m="445205">in</span> <span m="445807">addition</span> <span m="446410">to</span>
  <span m="447012">maximizing</span> <span m="447614">our</span> <span m="448216">throughput.</span></p><p><span
  m="448819">Notice</span> <span m="449162">that</span> <span m="449506">regardless</span>
  <span m="449849">of</span> <span m="450193">which</span> <span m="450536">input</span>
  <span m="450880">to</span> <span m="451223">output</span> <span m="451567">path</span>
  <span m="451910">you</span> <span m="452254">follow,</span> <span m="452597">at</span>
  <span m="452941">this</span> <span m="453284">stage</span> <span m="453628">you</span>
  <span m="453971">are</span> <span m="454315">crossing</span> <span m="454659">3</span>
  <span m="455659">pipeline</span> <span m="456659">registers.</span></p><p><span
  m="457659">We</span> <span m="458004">continue</span> <span m="458350">pipelining</span>
  <span m="458696">our</span> <span m="459041">circuit</span> <span m="459387">in</span>
  <span m="459733">this</span> <span m="460079">manner</span> <span m="460424">until</span>
  <span m="460770">we</span> <span m="461116">have</span> <span m="461461">added</span>
  <span m="461807">enough</span> <span m="462153">pipeline</span> <span m="462499">stages</span>
  <span m="463064">so</span> <span m="463629">that</span> <span m="464195">each</span>
  <span m="464760">stage</span> <span m="465326">passes</span> <span m="465891">through</span>
  <span m="466457">a</span> <span m="467022">single</span> <span m="467588">CBit</span>
  <span m="468153">module.</span></p><p><span m="468719">We</span> <span m="469110">now</span>
  <span m="469502">see</span> <span m="469894">that</span> <span m="470286">any</span>
  <span m="470678">path</span> <span m="471070">from</span> <span m="471462">input</span>
  <span m="471854">to</span> <span m="472246">output</span> <span m="472638">passes</span>
  <span m="473030">through</span> <span m="473422">6</span> <span m="473814">pipeline</span>
  <span m="474206">registers</span> <span m="474598">because</span> <span m="474990">we</span>
  <span m="475319">have</span> <span m="475649">split</span> <span m="475979">our</span>
  <span m="476309">circuit</span> <span m="476639">into</span> <span m="476969">6</span>
  <span m="477299">pipeline</span> <span m="477629">stages</span> <span m="477959">in</span>
  <span m="478289">order</span> <span m="478619">to</span> <span m="478949">break</span>
  <span m="479279">up</span> <span m="479609">the</span> <span m="479939">longest</span>
  <span m="480269">path.</span></p><p><span m="480599">We</span> <span m="481029">can</span>
  <span m="481459">now</span> <span m="481889">clock</span> <span m="482319">this</span>
  <span m="482749">circuit</span> <span m="483179">with</span> <span m="483609">period</span>
  <span m="484039">T</span> <span m="484469">=</span> <span m="484899">4</span> <span
  m="485329">ns.</span></p><p><span m="485759">So</span> <span m="486156">the</span>
  <span m="486554">latency</span> <span m="486952">is</span> <span m="487350">the</span>
  <span m="487747">number</span> <span m="488145">of</span> <span m="488543">pipeline</span>
  <span m="488941">stages</span> <span m="489339">times</span> <span m="489736">the</span>
  <span m="490134">clock</span> <span m="490532">period</span> <span m="490930">which</span>
  <span m="491327">equals</span> <span m="491725">6</span> <span m="492123">*</span>
  <span m="492521">4</span> <span m="492919">ns</span> <span m="493671">=</span> <span
  m="494424">24</span> <span m="495176">ns.</span></p><p><span m="495929">The</span>
  <span m="496381">throughput</span> <span m="496834">of</span> <span m="497287">this</span>
  <span m="497739">circuit</span> <span m="498192">is</span> <span m="498645">1</span>
  <span m="499097">/</span> <span m="499550">clock</span> <span m="500003">period</span>
  <span m="500455">(T)</span> <span m="500908">=</span> <span m="501361">1</span>
  <span m="501813">/(4</span> <span m="502266">ns).</span></p>
type: course
uid: 9587a81a6d5cb3db056cbc02ddc3c20b

---
None