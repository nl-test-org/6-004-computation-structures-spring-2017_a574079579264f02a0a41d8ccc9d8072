---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 0h3SCozKaR4
  parent_uid: 0632cda3d83d54ac8618f871bfa0f94a
  title: Video-YouTube-Stream
  type: Video
  uid: e859e0f7d3437c497a0d79fa7f3da666
- id: 3Play-3Play YouTube id-Stream
  media_location: 0h3SCozKaR4
  parent_uid: 0632cda3d83d54ac8618f871bfa0f94a
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 68f54a9b8929806defa5501e5299a9b9
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/0h3SCozKaR4/default.jpg
  parent_uid: 0632cda3d83d54ac8618f871bfa0f94a
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e53e98283966a8ea5959eb3bab221eca
- id: 0h3SCozKaR4.srt
  parent_uid: 0632cda3d83d54ac8618f871bfa0f94a
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v7/a-better-beta/0h3SCozKaR4.srt
  title: 3play caption file
  type: null
  uid: a19645b4e7b5058643cb96ab6090b614
- id: 0h3SCozKaR4.pdf
  parent_uid: 0632cda3d83d54ac8618f871bfa0f94a
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v7/a-better-beta/0h3SCozKaR4.pdf
  title: 3play pdf file
  type: null
  uid: 634bc0bd376f3503c191e4e2f200152e
- id: Caption-3Play YouTube id-SRT
  parent_uid: 0632cda3d83d54ac8618f871bfa0f94a
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b0a461da2a76744c63d6ab85d6ab21e7
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 0632cda3d83d54ac8618f871bfa0f94a
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: f4811545a0a9ea00e588d77122447b22
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_13-02-07-01_300k.mp4
  parent_uid: 0632cda3d83d54ac8618f871bfa0f94a
  title: Video-Internet Archive-MP4
  type: Video
  uid: 0e11af9b3d5826361bb37cbb49f786c9
inline_embed_id: 31062451abetterbeta41139435
layout: video
order_index: null
parent_uid: 3d0d834e5b8172c647403cb4b646c9e8
related_resources_text: ''
short_url: a-better-beta
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v7/a-better-beta
template_type: Embed
title: 'Worked Example: A Better Beta'
transcript: <p><span m="729">In</span> <span m="1025">this</span> <span m="1321">problem,</span>
  <span m="1617">we</span> <span m="1914">are</span> <span m="2210">going</span> <span
  m="2506">to</span> <span m="2803">consider</span> <span m="3099">several</span>
  <span m="3395">instructions</span> <span m="3692">that</span> <span m="3988">we</span>
  <span m="4284">want</span> <span m="4581">to</span> <span m="4877">add</span> <span
  m="5173">to</span> <span m="5470">our</span> <span m="6170">beta.</span></p><p><span
  m="6870">For</span> <span m="7208">each</span> <span m="7547">of</span> <span m="7885">these</span>
  <span m="8224">instructions,</span> <span m="8563">we</span> <span m="8901">will</span>
  <span m="9240">need</span> <span m="9578">to</span> <span m="9917">decide</span>
  <span m="10256">what</span> <span m="10594">the</span> <span m="10933">minimum</span>
  <span m="11271">requirement</span> <span m="11610">is</span> <span m="11949">to</span>
  <span m="12596">add</span> <span m="13244">that</span> <span m="13891">instruction.</span></p><p><span
  m="14539">The</span> <span m="14919">simplest</span> <span m="15299">addition</span>
  <span m="15679">would</span> <span m="16059">be</span> <span m="16439">a</span>
  <span m="16819">macro</span> <span m="17199">that</span> <span m="17579">references</span>
  <span m="17959">a</span> <span m="18339">single</span> <span m="18719">already</span>
  <span m="19099">existing</span> <span m="19479">beta</span> <span m="19859">instruction.</span></p><p><span
  m="21789">If</span> <span m="22151">our</span> <span m="22514">new</span> <span
  m="22876">instruction</span> <span m="23239">cannot</span> <span m="23601">be</span>
  <span m="23964">implemented</span> <span m="24326">by</span> <span m="24689">simply</span>
  <span m="25051">defining</span> <span m="25414">a</span> <span m="25776">macro,</span>
  <span m="26139">then</span> <span m="26501">we</span> <span m="26864">want</span>
  <span m="27226">to</span> <span m="27589">consider</span> <span m="28026">whether</span>
  <span m="28463">adding</span> <span m="28900">a</span> <span m="29337">new</span>
  <span m="29774">opcode,</span> <span m="30211">and</span> <span m="30648">producing</span>
  <span m="31085">the</span> <span m="31522">appropriate</span> <span m="31959">control</span>
  <span m="32396">ROM</span> <span m="32833">signals</span> <span m="33270">for</span>
  <span m="33716">it,</span> <span m="34163">will</span> <span m="34609">enable</span>
  <span m="35056">the</span> <span m="35503">new</span> <span m="35949">operation</span>
  <span m="36396">to</span> <span m="36842">be</span> <span m="37289">executed</span>
  <span m="37736">on</span> <span m="38182">our</span> <span m="38629">existing</span>
  <span m="39075">Beta</span> <span m="39522">datapaths.</span></p><p><span m="39969">Finally,</span>
  <span m="40382">if</span> <span m="40796">neither</span> <span m="41210">the</span>
  <span m="41624">macro</span> <span m="42038">or</span> <span m="42451">Control</span>
  <span m="42865">ROM</span> <span m="43279">solutions</span> <span m="43693">work,</span>
  <span m="44107">then</span> <span m="44520">we</span> <span m="44934">need</span>
  <span m="45348">to</span> <span m="45762">specify</span> <span m="46176">that</span>
  <span m="46590">the</span> <span m="47386">instruction</span> <span m="48183">cannot</span>
  <span m="48980">be</span> <span m="49777">implemented</span> <span m="50574">without</span>
  <span m="51371">making</span> <span m="52167">actual</span> <span m="52964">hardware</span>
  <span m="53761">changes</span> <span m="54558">to</span> <span m="55355">the</span>
  <span m="56152">Beta.</span></p><p><span m="56949">The</span> <span m="57310">first</span>
  <span m="57671">instruction</span> <span m="58032">that</span> <span m="58394">we</span>
  <span m="58755">want</span> <span m="59116">to</span> <span m="59478">consider</span>
  <span m="59839">adding</span> <span m="60200">to</span> <span m="60562">our</span>
  <span m="60923">Beta</span> <span m="61284">is</span> <span m="61646">a</span> <span
  m="62007">SWAPR</span> <span m="62368">instruction</span> <span m="62730">which</span>
  <span m="63191">swaps</span> <span m="63652">the</span> <span m="64114">contents</span>
  <span m="64575">of</span> <span m="65037">registers</span> <span m="65498">Rx</span>
  <span m="65960">and</span> <span m="66421">Ry</span> <span m="66882">in</span> <span
  m="67344">a</span> <span m="67805">single</span> <span m="68267">clock</span> <span
  m="68728">cycle.</span></p><p><span m="69190">The</span> <span m="69450">constraint</span>
  <span m="69710">that</span> <span m="69970">this</span> <span m="70230">must</span>
  <span m="70490">be</span> <span m="70750">done</span> <span m="71010">in</span>
  <span m="71270">a</span> <span m="71530">single</span> <span m="71790">clock</span>
  <span m="72050">cycle</span> <span m="72310">points</span> <span m="72570">us</span>
  <span m="72830">to</span> <span m="73090">the</span> <span m="73350">fact</span>
  <span m="73610">that</span> <span m="73870">the</span> <span m="74190">Beta</span>
  <span m="74511">hardware</span> <span m="74831">does</span> <span m="75152">not</span>
  <span m="75473">have</span> <span m="75793">the</span> <span m="76114">ability</span>
  <span m="76435">to</span> <span m="76755">write</span> <span m="77076">to</span>
  <span m="77396">two</span> <span m="77717">different</span> <span m="78038">registers</span>
  <span m="78358">in</span> <span m="78679">the</span> <span m="79000">same</span>
  <span m="79513">clock</span> <span m="80026">cycle.</span></p><p><span m="80539">Thus,</span>
  <span m="81049">in</span> <span m="81560">order</span> <span m="82070">to</span>
  <span m="82581">add</span> <span m="83092">this</span> <span m="83602">instruction</span>
  <span m="84113">to</span> <span m="84624">the</span> <span m="85134">Beta,</span>
  <span m="85645">new</span> <span m="86156">hardware</span> <span m="86666">would</span>
  <span m="87177">need</span> <span m="87688">to</span> <span m="88198">be</span>
  <span m="88709">added.</span></p><p><span m="89220">The</span> <span m="89573">next</span>
  <span m="89927">instruction</span> <span m="90281">that</span> <span m="90635">we</span>
  <span m="90988">want</span> <span m="91342">to</span> <span m="91696">consider</span>
  <span m="92050">adding</span> <span m="92403">to</span> <span m="92757">our</span>
  <span m="93111">beta</span> <span m="93465">is</span> <span m="93818">a</span> <span
  m="94172">NEG</span> <span m="94526">instruction.</span></p><p><span m="94880">This</span>
  <span m="95278">instruction</span> <span m="95677">should</span> <span m="96076">take</span>
  <span m="96474">the</span> <span m="96873">two's</span> <span m="97272">complement</span>
  <span m="97670">negation</span> <span m="98069">of</span> <span m="98468">register</span>
  <span m="98866">Rx</span> <span m="99265">and</span> <span m="99664">store</span>
  <span m="100062">it</span> <span m="100461">into</span> <span m="100860">register</span>
  <span m="101824">Ry.</span></p><p><span m="102789">The</span> <span m="103065">first</span>
  <span m="103342">question</span> <span m="103619">we</span> <span m="103895">want</span>
  <span m="104172">to</span> <span m="104449">ask</span> <span m="104726">ourselves</span>
  <span m="105002">is</span> <span m="105279">whether</span> <span m="105556">or</span>
  <span m="105832">not</span> <span m="106109">we</span> <span m="106386">might</span>
  <span m="106663">be</span> <span m="106939">able</span> <span m="107216">to</span>
  <span m="107493">implement</span> <span m="107770">this</span> <span m="108745">using</span>
  <span m="109720">a</span> <span m="110695">macro.</span></p><p><span m="111670">Since</span>
  <span m="111913">all</span> <span m="112156">we</span> <span m="112399">are</span>
  <span m="112642">trying</span> <span m="112885">to</span> <span m="113128">do</span>
  <span m="113371">is</span> <span m="113614">produce</span> <span m="113857">the</span>
  <span m="114101">negative</span> <span m="114344">of</span> <span m="114587">a</span>
  <span m="114830">given</span> <span m="115073">value,</span> <span m="115316">we</span>
  <span m="115559">can</span> <span m="115802">write</span> <span m="116045">a</span>
  <span m="116289">macro</span> <span m="116799">for</span> <span m="117310">this</span>
  <span m="117821">instruction</span> <span m="118331">which</span> <span m="118842">subtracts</span>
  <span m="119353">Rx</span> <span m="119864">from</span> <span m="120374">R31</span>
  <span m="120885">and</span> <span m="121396">stores</span> <span m="121907">that</span>
  <span m="122417">result</span> <span m="122928">into</span> <span m="123439">Ry.</span></p><p><span
  m="123950">Note</span> <span m="124244">that</span> <span m="124539">this</span>
  <span m="124834">macro</span> <span m="125129">will</span> <span m="125424">not</span>
  <span m="125719">work</span> <span m="126014">for</span> <span m="126309">the</span>
  <span m="126604">corner</span> <span m="126899">case</span> <span m="127194">which</span>
  <span m="127489">is</span> <span m="127784">the</span> <span m="128079">largest</span>
  <span m="128374">representable</span> <span m="128669">negative</span> <span m="129082">number</span>
  <span m="129495">because</span> <span m="129908">the</span> <span m="130321">negation</span>
  <span m="130734">of</span> <span m="131147">that</span> <span m="131561">number</span>
  <span m="131974">cannot</span> <span m="132387">be</span> <span m="132800">represented</span>
  <span m="133213">using</span> <span m="133626">32-bit</span> <span m="134040">two's</span>
  <span m="134883">complement</span> <span m="135726">representation.</span></p><p><span
  m="136569">For</span> <span m="137280">all</span> <span m="137991">other</span>
  <span m="138702">cases,</span> <span m="139413">however,</span> <span m="140124">this</span>
  <span m="140835">macro</span> <span m="141546">works</span> <span m="142257">as</span>
  <span m="142968">expected.</span></p><p><span m="143680">The</span> <span m="144038">next</span>
  <span m="144397">instruction</span> <span m="144756">that</span> <span m="145115">we</span>
  <span m="145473">want</span> <span m="145832">to</span> <span m="146191">consider</span>
  <span m="146550">adding</span> <span m="146908">to</span> <span m="147267">our</span>
  <span m="147626">Beta</span> <span m="147985">is</span> <span m="148343">a</span>
  <span m="148702">PC-relative</span> <span m="149061">store</span> <span m="149420">instruction.</span></p><p><span
  m="150420">The</span> <span m="150719">way</span> <span m="151019">this</span> <span
  m="151319">instruction</span> <span m="151619">works</span> <span m="151919">is</span>
  <span m="152219">that</span> <span m="152519">it</span> <span m="152819">writes</span>
  <span m="153119">the</span> <span m="153419">contents</span> <span m="153719">of</span>
  <span m="154019">register</span> <span m="154319">Rx</span> <span m="154619">to</span>
  <span m="154919">a</span> <span m="155219">location</span> <span m="155519">in</span>
  <span m="156244">memory</span> <span m="156969">whose</span> <span m="157695">address</span>
  <span m="158420">is</span> <span m="159146">computed</span> <span m="159871">by</span>
  <span m="160597">adding</span> <span m="161322">PC</span> <span m="162048">+</span>
  <span m="162773">4</span> <span m="163499">+</span> <span m="164224">4*SEXT(C).</span></p><p><span
  m="164950">The</span> <span m="165262">only</span> <span m="165574">existing</span>
  <span m="165887">store</span> <span m="166199">operation</span> <span m="166511">in</span>
  <span m="166824">the</span> <span m="167136">beta</span> <span m="167448">is</span>
  <span m="167761">a</span> <span m="168073">store</span> <span m="168385">that</span>
  <span m="168698">writes</span> <span m="169010">to</span> <span m="169322">the</span>
  <span m="169635">address</span> <span m="169947">that</span> <span m="170260">is</span>
  <span m="170680">computed</span> <span m="171101">by</span> <span m="171521">adding</span>
  <span m="171942">the</span> <span m="172363">contents</span> <span m="172783">of</span>
  <span m="173204">register</span> <span m="173624">Ry</span> <span m="174045">and</span>
  <span m="174466">the</span> <span m="174886">sign</span> <span m="175307">extended</span>
  <span m="175727">literal</span> <span m="176148">C.</span></p><p><span m="176569">Since</span>
  <span m="176942">this</span> <span m="177315">is</span> <span m="177688">not</span>
  <span m="178061">equivalent</span> <span m="178434">to</span> <span m="178807">the</span>
  <span m="179181">store</span> <span m="179554">relative</span> <span m="179927">instruction's</span>
  <span m="180300">behavior</span> <span m="180673">that</span> <span m="181046">means</span>
  <span m="181420">that</span> <span m="181852">we</span> <span m="182284">cannot</span>
  <span m="182716">implement</span> <span m="183148">this</span> <span m="183581">instruction</span>
  <span m="184013">as</span> <span m="184445">a</span> <span m="184877">macro.</span></p><p><span
  m="185310">So</span> <span m="185618">next</span> <span m="185926">we</span> <span
  m="186234">consider</span> <span m="186542">whether</span> <span m="186850">or</span>
  <span m="187158">not</span> <span m="187466">we</span> <span m="187774">can</span>
  <span m="188082">implement</span> <span m="188390">this</span> <span m="188698">instruction</span>
  <span m="189006">using</span> <span m="189314">our</span> <span m="189622">existing</span>
  <span m="189930">Beta</span> <span m="191129">datapaths.</span></p><p><span m="192329">This</span>
  <span m="192805">beta</span> <span m="193282">diagram</span> <span m="193759">highlights</span>
  <span m="194235">in</span> <span m="194712">red</span> <span m="195189">the</span>
  <span m="195666">dataflow</span> <span m="196142">through</span> <span m="196619">the</span>
  <span m="197096">existing</span> <span m="197573">Beta</span> <span m="198049">datapaths</span>
  <span m="198526">that</span> <span m="199003">would</span> <span m="199480">perform</span>
  <span m="200048">the</span> <span m="200616">desired</span> <span m="201185">PC</span>
  <span m="201753">relative</span> <span m="202322">store</span> <span m="202890">instruction.</span></p><p><span
  m="203459">The</span> <span m="203801">way</span> <span m="204144">this</span> <span
  m="204487">instruction</span> <span m="204829">works</span> <span m="205172">is</span>
  <span m="205515">that</span> <span m="205857">the</span> <span m="206200">extra</span>
  <span m="206543">adder</span> <span m="206885">under</span> <span m="207228">the</span>
  <span m="207571">instruction</span> <span m="207913">memory</span> <span m="208256">is</span>
  <span m="208599">used</span> <span m="209069">to</span> <span m="209539">compute</span>
  <span m="210009">the</span> <span m="210479">value</span> <span m="210949">of</span>
  <span m="211419">the</span> <span m="211889">effective</span> <span m="212359">address</span>
  <span m="212829">which</span> <span m="213299">is</span> <span m="213769">PC</span>
  <span m="214239">+</span> <span m="214709">4</span> <span m="215179">+</span> <span
  m="215649">4*SEXT(C).</span></p><p><span m="216120">The</span> <span m="216518">ASEL,</span>
  <span m="216916">or</span> <span m="217314">A</span> <span m="217712">select</span>
  <span m="218110">signal</span> <span m="218508">is</span> <span m="218906">then</span>
  <span m="219305">set</span> <span m="219703">to</span> <span m="220101">1</span>
  <span m="220499">to</span> <span m="220897">pass</span> <span m="221295">that</span>
  <span m="221693">value</span> <span m="222092">to</span> <span m="222490">the</span>
  <span m="222888">ALU</span> <span m="223286">as</span> <span m="223684">the</span>
  <span m="224082">A</span> <span m="224480">operand.</span></p><p><span m="224879">The</span>
  <span m="225222">ALUFN</span> <span m="225566">is</span> <span m="225910">then</span>
  <span m="226253">set</span> <span m="226597">to</span> <span m="226941">A</span>
  <span m="227284">to</span> <span m="227628">continue</span> <span m="227972">passing</span>
  <span m="228315">that</span> <span m="228659">value</span> <span m="229003">through</span>
  <span m="229346">the</span> <span m="229690">ALU</span> <span m="230034">in</span>
  <span m="230377">order</span> <span m="230721">for</span> <span m="231065">it</span>
  <span m="231409">to</span> <span m="231758">be</span> <span m="232107">used</span>
  <span m="232456">as</span> <span m="232805">the</span> <span m="233154">address</span>
  <span m="233503">for</span> <span m="233852">the</span> <span m="234201">data</span>
  <span m="234550">memory.</span></p><p><span m="234900">This</span> <span m="235326">address</span>
  <span m="235753">is</span> <span m="236179">labeled</span> <span m="236606">MA,</span>
  <span m="237032">or</span> <span m="237459">memory</span> <span m="237886">address</span>
  <span m="238312">in</span> <span m="238739">the</span> <span m="239165">beta</span>
  <span m="239592">diagram.</span></p><p><span m="240019">The</span> <span m="240397">value</span>
  <span m="240775">that</span> <span m="241154">is</span> <span m="241532">written</span>
  <span m="241911">to</span> <span m="242289">memory</span> <span m="242668">is</span>
  <span m="243046">the</span> <span m="243425">value</span> <span m="243803">of</span>
  <span m="244182">register</span> <span m="244560">Rx.</span></p><p><span m="244939">In</span>
  <span m="245518">store</span> <span m="246097">operations,</span> <span m="246676">the</span>
  <span m="247255">first</span> <span m="247834">operand</span> <span m="248413">corresponds</span>
  <span m="248992">to</span> <span m="249571">register</span> <span m="250150">Rc.</span></p><p><span
  m="250730">So</span> <span m="251133">we</span> <span m="251536">set</span> <span
  m="251939">RA2SEL</span> <span m="252342">=</span> <span m="252745">1</span> <span
  m="253148">in</span> <span m="253551">order</span> <span m="253954">to</span> <span
  m="254357">select</span> <span m="254760">Rc,</span> <span m="255163">which</span>
  <span m="255566">is</span> <span m="255969">Rx</span> <span m="256372">in</span>
  <span m="256775">this</span> <span m="257178">case,</span> <span m="257581">as</span>
  <span m="257984">the</span> <span m="258387">register</span> <span m="258790">whose</span>
  <span m="259275">contents</span> <span m="259761">should</span> <span m="260247">be</span>
  <span m="260732">written</span> <span m="261218">to</span> <span m="261704">memory.</span></p><p><span
  m="262190">The</span> <span m="262556">value</span> <span m="262923">of</span> <span
  m="263290">this</span> <span m="263657">register</span> <span m="264024">is</span>
  <span m="264391">made</span> <span m="264758">available</span> <span m="265125">via</span>
  <span m="265491">the</span> <span m="265858">RD2</span> <span m="266225">register</span>
  <span m="266592">file</span> <span m="266959">port</span> <span m="267326">which</span>
  <span m="267693">then</span> <span m="268060">feeds</span> <span m="268567">the</span>
  <span m="269074">MWD,</span> <span m="269581">or</span> <span m="270089">memory</span>
  <span m="270596">write</span> <span m="271103">data</span> <span m="271610">signal</span>
  <span m="272118">for</span> <span m="272625">the</span> <span m="273132">memory.</span></p><p><span
  m="273640">There</span> <span m="273947">are</span> <span m="274254">a</span> <span
  m="274561">couple</span> <span m="274868">other</span> <span m="275175">memory</span>
  <span m="275482">related</span> <span m="275790">signals</span> <span m="276097">that</span>
  <span m="276404">we</span> <span m="276711">need</span> <span m="277018">to</span>
  <span m="277325">set</span> <span m="277632">appropriately.</span></p><p><span m="277940">They</span>
  <span m="278266">are</span> <span m="278593">MWR,</span> <span m="278920">which</span>
  <span m="279247">stands</span> <span m="279574">for</span> <span m="279901">memory</span>
  <span m="280228">write</span> <span m="280555">read,</span> <span m="280882">and</span>
  <span m="281209">controls</span> <span m="281536">the</span> <span m="281863">write</span>
  <span m="282190">enable</span> <span m="282517">of</span> <span m="282844">the</span>
  <span m="283171">data</span> <span m="283850">memory.</span></p><p><span m="284530">In</span>
  <span m="284814">order</span> <span m="285098">to</span> <span m="285383">be</span>
  <span m="285667">able</span> <span m="285952">to</span> <span m="286236">write</span>
  <span m="286521">to</span> <span m="286805">the</span> <span m="287090">memory,</span>
  <span m="287374">the</span> <span m="287658">write</span> <span m="287943">enable</span>
  <span m="288227">must</span> <span m="288512">be</span> <span m="288796">set</span>
  <span m="289081">to</span> <span m="289365">1.</span></p><p><span m="289650">MOE</span>
  <span m="290158">is</span> <span m="290666">the</span> <span m="291175">memory</span>
  <span m="291683">output</span> <span m="292191">enable.</span></p><p><span m="292700">We</span>
  <span m="293016">set</span> <span m="293333">this</span> <span m="293650">to</span>
  <span m="293967">0</span> <span m="294284">to</span> <span m="294601">specify</span>
  <span m="294918">that</span> <span m="295235">no</span> <span m="295551">output</span>
  <span m="295868">should</span> <span m="296185">be</span> <span m="296502">enabled</span>
  <span m="296819">from</span> <span m="297136">the</span> <span m="297453">memory.</span></p><p><span
  m="297770">Note</span> <span m="298041">that</span> <span m="298313">you</span>
  <span m="298585">may</span> <span m="298856">think</span> <span m="299128">that</span>
  <span m="299400">MOE</span> <span m="299671">should</span> <span m="299943">be</span>
  <span m="300215">a</span> <span m="300486">don't</span> <span m="300758">care</span>
  <span m="301030">since</span> <span m="301301">we</span> <span m="301573">are</span>
  <span m="301845">never</span> <span m="302116">making</span> <span m="302388">use</span>
  <span m="302660">of</span> <span m="303012">the</span> <span m="303365">MRD,</span>
  <span m="303718">or</span> <span m="304070">memory</span> <span m="304423">read</span>
  <span m="304776">data,</span> <span m="305129">signal</span> <span m="305481">in</span>
  <span m="305834">our</span> <span m="306187">datapath.</span></p><p><span m="306540">However,</span>
  <span m="306897">by</span> <span m="307254">setting</span> <span m="307611">it</span>
  <span m="307968">to</span> <span m="308325">0</span> <span m="308682">we</span>
  <span m="309039">allow</span> <span m="309396">ourselves</span> <span m="309753">to</span>
  <span m="310110">potentially</span> <span m="310467">use</span> <span m="310824">the</span>
  <span m="311181">same</span> <span m="311538">databus</span> <span m="311895">for</span>
  <span m="312252">the</span> <span m="312610">read</span> <span m="312988">and</span>
  <span m="313367">write</span> <span m="313745">data</span> <span m="314124">of</span>
  <span m="314502">the</span> <span m="314881">memory.</span></p><p><span m="315260">This</span>
  <span m="315566">is</span> <span m="315873">not</span> <span m="316180">explicitly</span>
  <span m="316486">shown</span> <span m="316793">in</span> <span m="317100">our</span>
  <span m="317406">beta</span> <span m="317713">diagram</span> <span m="318020">but</span>
  <span m="318326">is</span> <span m="318633">the</span> <span m="318940">reason</span>
  <span m="319246">that</span> <span m="319553">MOE</span> <span m="319860">is</span>
  <span m="320166">specified</span> <span m="320473">as</span> <span m="320780">0</span>
  <span m="321566">for</span> <span m="322353">us.</span></p><p><span m="323140">The</span>
  <span m="323413">other</span> <span m="323687">control</span> <span m="323960">signal</span>
  <span m="324234">that</span> <span m="324507">we</span> <span m="324781">must</span>
  <span m="325054">set</span> <span m="325328">to</span> <span m="325601">0</span>
  <span m="325875">is</span> <span m="326148">WERF,</span> <span m="326422">which</span>
  <span m="326695">stands</span> <span m="326969">for</span> <span m="327242">write</span>
  <span m="327516">enable</span> <span m="327790">register</span> <span m="328775">file.</span></p><p><span
  m="329760">Setting</span> <span m="330085">this</span> <span m="330410">signal</span>
  <span m="330735">to</span> <span m="331061">0</span> <span m="331386">ensures</span>
  <span m="331711">that</span> <span m="332037">no</span> <span m="332362">value</span>
  <span m="332687">will</span> <span m="333012">be</span> <span m="333338">written</span>
  <span m="333663">back</span> <span m="333988">into</span> <span m="334314">our</span>
  <span m="334639">register</span> <span m="334964">file.</span></p><p><span m="335290">This</span>
  <span m="335782">allows</span> <span m="336275">us</span> <span m="336767">to</span>
  <span m="337260">then</span> <span m="337752">set</span> <span m="338245">WDSEL</span>
  <span m="338737">and</span> <span m="339230">WASEL</span> <span m="339722">to</span>
  <span m="340215">don't</span> <span m="340707">cares.</span></p><p><span m="341200">The</span>
  <span m="341554">last</span> <span m="341908">control</span> <span m="342263">signal</span>
  <span m="342617">is</span> <span m="342972">BSEL</span> <span m="343326">which</span>
  <span m="343681">is</span> <span m="344035">also</span> <span m="344390">a</span>
  <span m="344744">don't</span> <span m="345098">care</span> <span m="345453">because</span>
  <span m="345807">the</span> <span m="346162">B</span> <span m="346516">operand</span>
  <span m="346871">is</span> <span m="347225">ignored</span> <span m="347580">by</span>
  <span m="348048">the</span> <span m="348516">ALU</span> <span m="348985">for</span>
  <span m="349453">this</span> <span m="349921">instruction.</span></p><p><span m="350390">Finally,</span>
  <span m="350786">the</span> <span m="351183">PCSEL</span> <span m="351580">=</span>
  <span m="351977">0</span> <span m="352374">in</span> <span m="352771">order</span>
  <span m="353167">to</span> <span m="353564">increment</span> <span m="353961">the</span>
  <span m="354358">PC</span> <span m="354755">by</span> <span m="355152">4</span>
  <span m="355548">so</span> <span m="355945">that</span> <span m="356342">the</span>
  <span m="356739">next</span> <span m="357136">instruction</span> <span m="357533">will</span>
  <span m="357930">be</span> <span m="359895">fetched.</span></p><p><span m="361860">So</span>
  <span m="362341">our</span> <span m="362823">completed</span> <span m="363305">Control</span>
  <span m="363786">ROM</span> <span m="364268">for</span> <span m="364750">the</span>
  <span m="365231">STR</span> <span m="365713">operation</span> <span m="366195">is</span>
  <span m="366676">shown</span> <span m="367158">here.</span></p><p><span m="367640">The</span>
  <span m="368094">last</span> <span m="368548">instruction</span> <span m="369003">we</span>
  <span m="369457">want</span> <span m="369911">to</span> <span m="370366">add</span>
  <span m="370820">to</span> <span m="371275">our</span> <span m="371729">beta</span>
  <span m="372183">is</span> <span m="372638">the</span> <span m="373092">BITCLR(Rx,</span>
  <span m="373546">Ry,</span> <span m="374001">Rz)</span> <span m="374455">instruction.</span></p><p><span
  m="374910">This</span> <span m="375286">instruction</span> <span m="375662">performs</span>
  <span m="376038">a</span> <span m="376414">bitwise</span> <span m="376790">AND</span>
  <span m="377166">of</span> <span m="377542">the</span> <span m="377918">contents</span>
  <span m="378294">of</span> <span m="378670">register</span> <span m="379046">Ry</span>
  <span m="379422">with</span> <span m="379798">the</span> <span m="380174">complement</span>
  <span m="380550">of</span> <span m="380938">the</span> <span m="381326">contents</span>
  <span m="381715">of</span> <span m="382103">register</span> <span m="382491">Rx.</span></p><p><span
  m="382880">There</span> <span m="383316">is</span> <span m="383752">no</span> <span
  m="384189">existing</span> <span m="384625">beta</span> <span m="385062">instruction</span>
  <span m="385498">that</span> <span m="385935">performs</span> <span m="386371">this</span>
  <span m="386807">functionality</span> <span m="387244">so</span> <span m="387680">using</span>
  <span m="388117">a</span> <span m="388553">macro</span> <span m="388990">is</span>
  <span m="389375">not</span> <span m="389760">an</span> <span m="390145">option.</span></p><p><span
  m="390530">Next,</span> <span m="390848">we</span> <span m="391167">want</span>
  <span m="391486">to</span> <span m="391804">consider</span> <span m="392123">whether</span>
  <span m="392442">or</span> <span m="392760">not</span> <span m="393079">we</span>
  <span m="393398">could</span> <span m="393716">implement</span> <span m="394035">this</span>
  <span m="394354">instruction</span> <span m="394672">using</span> <span m="394991">our</span>
  <span m="395310">existing</span> <span m="395830">datapaths</span> <span m="396350">with</span>
  <span m="396870">changes</span> <span m="397390">to</span> <span m="397910">our</span>
  <span m="398430">control</span> <span m="398950">ROM.</span></p><p><span m="399470">To</span>
  <span m="399784">answer</span> <span m="400098">this</span> <span m="400413">question,</span>
  <span m="400727">you</span> <span m="401041">need</span> <span m="401356">to</span>
  <span m="401670">realize</span> <span m="401985">that</span> <span m="402299">the</span>
  <span m="402613">operation</span> <span m="402928">that</span> <span m="403242">you</span>
  <span m="403556">are</span> <span m="403871">trying</span> <span m="404185">to</span>
  <span m="404500">perform</span> <span m="405343">here</span> <span m="406186">is</span>
  <span m="407030">a</span> <span m="407873">boolean</span> <span m="408716">operation.</span></p><p><span
  m="409560">In</span> <span m="409905">module</span> <span m="410251">1,</span> <span
  m="410597">when</span> <span m="410943">implementing</span> <span m="411289">the</span>
  <span m="411635">ALU</span> <span m="411981">lab,</span> <span m="412327">we</span>
  <span m="412672">learned</span> <span m="413018">that</span> <span m="413364">the</span>
  <span m="413710">way</span> <span m="414056">that</span> <span m="414402">the</span>
  <span m="414748">bool</span> <span m="415094">module</span> <span m="415440">works</span>
  <span m="415951">is</span> <span m="416462">that</span> <span m="416973">if</span>
  <span m="417484">you</span> <span m="417995">set</span> <span m="418506">the</span>
  <span m="419017">ALUFN</span> <span m="419528">to</span> <span m="420040">10abcd,</span>
  <span m="420551">then</span> <span m="421062">the</span> <span m="421573">ALU</span>
  <span m="422084">would</span> <span m="422595">produce</span> <span m="423106">the</span>
  <span m="423617">output</span> <span m="424128">defined</span> <span m="424640">by</span>
  <span m="425176">this</span> <span m="425713">truth</span> <span m="426250">table</span>
  <span m="426786">for</span> <span m="427323">every</span> <span m="427860">pair</span>
  <span m="428396">of</span> <span m="428933">bits</span> <span m="429470">Bi</span>
  <span m="430006">and</span> <span m="430543">Ai.</span></p><p><span m="431080">So</span>
  <span m="431485">for</span> <span m="431890">example,</span> <span m="432295">to</span>
  <span m="432700">implement</span> <span m="433105">the</span> <span m="433510">AND</span>
  <span m="433915">function,</span> <span m="434320">we</span> <span m="434725">simply</span>
  <span m="435130">set</span> <span m="435535">a</span> <span m="435940">=</span>
  <span m="436345">1,</span> <span m="436750">b</span> <span m="437155">=</span> <span
  m="437560">0,</span> <span m="437965">c</span> <span m="438370">=</span> <span m="438775">0,</span>
  <span m="439180">and</span> <span m="439585">d</span> <span m="439990">=</span>
  <span m="440395">0</span> <span m="440800">as</span> <span m="441154">shown</span>
  <span m="441509">in</span> <span m="441864">this</span> <span m="442218">truth</span>
  <span m="442573">table</span> <span m="442928">which</span> <span m="443282">is</span>
  <span m="443637">the</span> <span m="443992">truth</span> <span m="444346">table</span>
  <span m="444701">for</span> <span m="445056">an</span> <span m="445410">AND</span>
  <span m="445765">function.</span></p><p><span m="446120">The</span> <span m="446719">truth</span>
  <span m="447318">table</span> <span m="447917">for</span> <span m="448516">the</span>
  <span m="449115">BITCLR</span> <span m="449714">operation</span> <span m="450313">is</span>
  <span m="450912">shown</span> <span m="451511">here.</span></p><p><span m="452110">One</span>
  <span m="452560">additional</span> <span m="453011">column,</span> <span m="453462">NOT(Rx)[i]</span>
  <span m="453912">has</span> <span m="454363">been</span> <span m="454814">added</span>
  <span m="455265">to</span> <span m="455715">show</span> <span m="456166">the</span>
  <span m="456617">intermediate</span> <span m="457067">step</span> <span m="457518">of</span>
  <span m="457969">negating</span> <span m="458420">Rx[i].</span></p><p><span m="460220">Then</span>
  <span m="460611">if</span> <span m="461003">you</span> <span m="461395">take</span>
  <span m="461786">the</span> <span m="462178">AND</span> <span m="462570">of</span>
  <span m="462961">the</span> <span m="463353">Ry[i]</span> <span m="463745">column</span>
  <span m="464136">and</span> <span m="464528">the</span> <span m="464920">Not(Rx)[i]</span>
  <span m="465311">columns</span> <span m="465703">you</span> <span m="466095">get</span>
  <span m="466486">the</span> <span m="466878">result</span> <span m="467270">Rz[i].</span></p><p><span
  m="469550">This</span> <span m="470074">means</span> <span m="470598">that</span>
  <span m="471122">the</span> <span m="471647">ALUFN</span> <span m="472171">for</span>
  <span m="472695">the</span> <span m="473220">BITCLR</span> <span m="473744">operation</span>
  <span m="474268">is</span> <span m="474792">10</span> <span m="475317">followed</span>
  <span m="475841">by</span> <span m="476365">0100.</span></p><p><span m="476890">The</span>
  <span m="477373">rest</span> <span m="477856">of</span> <span m="478339">the</span>
  <span m="478822">control</span> <span m="479305">signals</span> <span m="479788">can</span>
  <span m="480271">be</span> <span m="480755">determined</span> <span m="481238">by</span>
  <span m="481721">looking</span> <span m="482204">at</span> <span m="482687">this</span>
  <span m="483170">highlighted</span> <span m="483653">beta</span> <span m="484136">diagram</span>
  <span m="484620">which</span> <span m="484911">shows</span> <span m="485203">in</span>
  <span m="485495">red</span> <span m="485787">the</span> <span m="486079">paths</span>
  <span m="486371">that</span> <span m="486663">must</span> <span m="486955">be</span>
  <span m="487246">followed</span> <span m="487538">in</span> <span m="487830">order</span>
  <span m="488122">to</span> <span m="488414">properly</span> <span m="488706">implement</span>
  <span m="488998">the</span> <span m="489290">BITCLR</span> <span m="490005">operation.</span></p><p><span
  m="490720">The</span> <span m="491123">instruction</span> <span m="491527">memory</span>
  <span m="491930">specifies</span> <span m="492334">the</span> <span m="492737">registers</span>
  <span m="493141">Ra</span> <span m="493544">and</span> <span m="493948">Rb,</span>
  <span m="494351">in</span> <span m="494755">our</span> <span m="495158">case</span>
  <span m="495562">Rx</span> <span m="495965">and</span> <span m="496369">Ry,</span>
  <span m="496772">that</span> <span m="497176">are</span> <span m="497580">to</span>
  <span m="498073">be</span> <span m="498566">used</span> <span m="499060">by</span>
  <span m="499553">this</span> <span m="500046">operation.</span></p><p><span m="500540">Setting</span>
  <span m="501026">RA2SEL</span> <span m="501512">to</span> <span m="501999">0</span>
  <span m="502485">tells</span> <span m="502972">the</span> <span m="503458">register</span>
  <span m="503945">file</span> <span m="504431">to</span> <span m="504918">read</span>
  <span m="505404">Rb,</span> <span m="505891">or</span> <span m="506377">Ry,</span>
  <span m="506864">as</span> <span m="507350">the</span> <span m="507837">second</span>
  <span m="508323">operand.</span></p><p><span m="508810">Then</span> <span m="509188">setting</span>
  <span m="509567">ASEL</span> <span m="509946">and</span> <span m="510325">BSEL</span>
  <span m="510703">to</span> <span m="511082">0</span> <span m="511461">passes</span>
  <span m="511840">the</span> <span m="512218">values</span> <span m="512597">of</span>
  <span m="512976">Rx</span> <span m="513355">and</span> <span m="513733">Ry</span>
  <span m="514112">to</span> <span m="514491">the</span> <span m="514870">ALU.</span></p><p><span
  m="515249">The</span> <span m="515777">ALUFN</span> <span m="516306">is</span> <span
  m="516834">used</span> <span m="517363">to</span> <span m="517891">specify</span>
  <span m="518420">the</span> <span m="518949">particular</span> <span m="519477">boolean</span>
  <span m="520006">operation</span> <span m="520534">that</span> <span m="521063">we</span>
  <span m="521591">are</span> <span m="522120">performing.</span></p><p><span m="522649">Then</span>
  <span m="523052">WDSEL</span> <span m="523456">=</span> <span m="523860">1</span>
  <span m="524264">in</span> <span m="524668">order</span> <span m="525072">to</span>
  <span m="525476">feed</span> <span m="525880">the</span> <span m="526284">results</span>
  <span m="526688">of</span> <span m="527092">the</span> <span m="527496">ALU</span>
  <span m="527900">back</span> <span m="528304">to</span> <span m="528708">the</span>
  <span m="529112">register</span> <span m="529516">file.</span></p><p><span m="529920">The</span>
  <span m="530264">Rc</span> <span m="530609">register</span> <span m="530953">is</span>
  <span m="531298">Rz</span> <span m="531643">and</span> <span m="531987">it</span>
  <span m="532332">is</span> <span m="532677">the</span> <span m="533021">register</span>
  <span m="533366">that</span> <span m="533711">the</span> <span m="534055">result</span>
  <span m="534400">should</span> <span m="534745">be</span> <span m="535089">written</span>
  <span m="535434">to.</span></p><p><span m="535779">To</span> <span m="536259">make</span>
  <span m="536739">that</span> <span m="537219">happen,</span> <span m="537699">we</span>
  <span m="538179">set</span> <span m="538659">WASEL</span> <span m="539139">=</span>
  <span m="539619">0,</span> <span m="540099">and</span> <span m="540579">WERF</span>
  <span m="541059">=</span> <span m="541539">1.</span></p><p><span m="542019">To</span>
  <span m="542426">avoid</span> <span m="542834">anything</span> <span m="543242">being</span>
  <span m="543650">written</span> <span m="544058">to</span> <span m="544466">the</span>
  <span m="544874">data</span> <span m="545282">memory,</span> <span m="545690">MWR</span>
  <span m="546098">is</span> <span m="546506">set</span> <span m="546914">to</span>
  <span m="547322">0.</span></p><p><span m="547730">MOE</span> <span m="548036">can</span>
  <span m="548342">be</span> <span m="548648">a</span> <span m="548954">don't</span>
  <span m="549260">care</span> <span m="549566">because</span> <span m="549872">we</span>
  <span m="550178">are</span> <span m="550485">not</span> <span m="550791">using</span>
  <span m="551097">the</span> <span m="551403">memory</span> <span m="551709">for</span>
  <span m="552015">reading</span> <span m="552321">or</span> <span m="552627">writing</span>
  <span m="552933">and</span> <span m="553240">setting</span> <span m="553737">WDSEL</span>
  <span m="554234">to</span> <span m="554732">1</span> <span m="555229">ignores</span>
  <span m="555727">anything</span> <span m="556224">that</span> <span m="556722">is</span>
  <span m="557219">on</span> <span m="557716">the</span> <span m="558214">MRD,</span>
  <span m="558711">or</span> <span m="559209">memory</span> <span m="559706">read</span>
  <span m="560204">data,</span> <span m="560701">line.</span></p><p><span m="561199">Finally,</span>
  <span m="561579">the</span> <span m="561959">PCSEL</span> <span m="562339">=</span>
  <span m="562719">0</span> <span m="563099">in</span> <span m="563479">order</span>
  <span m="563859">to</span> <span m="564239">increment</span> <span m="564619">the</span>
  <span m="564999">PC</span> <span m="565379">by</span> <span m="565759">4</span>
  <span m="566139">so</span> <span m="566519">that</span> <span m="566899">the</span>
  <span m="567279">next</span> <span m="567659">instruction</span> <span m="568039">will</span>
  <span m="568420">be</span> <span m="569730">fetched.</span></p><p><span m="571040">So</span>
  <span m="571451">our</span> <span m="571863">completed</span> <span m="572275">Control</span>
  <span m="572686">ROM</span> <span m="573098">for</span> <span m="573510">the</span>
  <span m="573921">BITCLR</span> <span m="574333">operation</span> <span m="574745">is</span>
  <span m="575156">shown</span> <span m="575568">here.</span></p>
type: course
uid: 0632cda3d83d54ac8618f871bfa0f94a

---
None