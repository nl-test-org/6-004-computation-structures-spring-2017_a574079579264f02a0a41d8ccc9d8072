---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 0LqS5QtpSVE
  parent_uid: 224ab9265fbf09c00c9e08e0e19df436
  title: Video-YouTube-Stream
  type: Video
  uid: 16bd54e0e4896cf2d9f5e2795b0b2e1e
- id: 3Play-3Play YouTube id-Stream
  media_location: 0LqS5QtpSVE
  parent_uid: 224ab9265fbf09c00c9e08e0e19df436
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 80d928997a27307d302d24b9ad580430
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/0LqS5QtpSVE/default.jpg
  parent_uid: 224ab9265fbf09c00c9e08e0e19df436
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 4a10e40be9f2760f2107e73ab649d65b
- id: 0LqS5QtpSVE.srt
  parent_uid: 224ab9265fbf09c00c9e08e0e19df436
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v4/control-hazards-11-25-/0LqS5QtpSVE.srt
  title: 3play caption file
  type: null
  uid: 2bb7e532d44092386d4f7f3403039541
- id: 0LqS5QtpSVE.pdf
  parent_uid: 224ab9265fbf09c00c9e08e0e19df436
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v4/control-hazards-11-25-/0LqS5QtpSVE.pdf
  title: 3play pdf file
  type: null
  uid: eafdd0c0193acd59393ef526f037ff37
- id: Caption-3Play YouTube id-SRT
  parent_uid: 224ab9265fbf09c00c9e08e0e19df436
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ac9c7aa2d96c53b47b57ad0008aad0b4
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 224ab9265fbf09c00c9e08e0e19df436
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 57fff6c0bc4a96817c9139424211959f
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_15-02-04_300k.mp4
  parent_uid: 224ab9265fbf09c00c9e08e0e19df436
  title: Video-Internet Archive-MP4
  type: Video
  uid: 8aff95b73260c3b678ae5552e866749a
inline_embed_id: 41782392controlhazards112516633492
layout: video
order_index: null
parent_uid: 5e8e24b00e9b7f64ecb8b7eb7efe79b9
related_resources_text: ''
short_url: control-hazards-11-25-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v4/control-hazards-11-25-
template_type: Embed
title: Control Hazards
transcript: <p><span m="360">Now</span> <span m="990">let&rsquo;s</span> <span m="1190">turn</span>
  <span m="1400">our</span> <span m="1600">attention</span> <span m="2009">to</span>
  <span m="2120">control</span> <span m="2590">hazards,</span> <span m="3330">illustrated</span>
  <span m="4090">by</span> <span m="4210">the</span> <span m="4290">code</span> <span
  m="4640">fragment</span> <span m="5180">shown</span> <span m="5490">here.</span></p><p><span
  m="6710">Which</span> <span m="6870">instruction</span> <span m="7370">should</span>
  <span m="7540">be</span> <span m="7710">executed</span> <span m="8310">after</span>
  <span m="8620">the</span> <span m="8720">BNE?</span></p><p><span m="8800">If</span>
  <span m="8990">the</span> <span m="9750">value</span> <span m="10730">in</span>
  <span m="10840">R3</span> <span m="11110">is</span> <span m="11510">non-zero,</span>
  <span m="12450">ADDC</span> <span m="12960">should</span> <span m="13200">be</span>
  <span m="13350">executed.</span></p><p><span m="14520">If</span> <span m="14680">the</span>
  <span m="14760">value</span> <span m="15230">in</span> <span m="15320">R3</span>
  <span m="15610">is</span> <span m="15940">zero,</span> <span m="16560">the</span>
  <span m="16790">next</span> <span m="17120">instruction</span> <span m="17640">should</span>
  <span m="17880">be</span> <span m="17990">SUB.</span></p><p><span m="19780">If</span>
  <span m="19930">the</span> <span m="20030">current</span> <span m="20380">instruction</span>
  <span m="20980">is</span> <span m="21150">an</span> <span m="21260">explicit</span>
  <span m="21780">transfer</span> <span m="22340">of</span> <span m="22400">control</span>
  <span m="23090">(i.e.,</span> <span m="23360">JMPs</span> <span m="23520">or</span>
  <span m="24110">branches),</span> <span m="25480">the</span> <span m="25920">choice</span>
  <span m="26240">of</span> <span m="26310">the</span> <span m="26410">next</span>
  <span m="26740">instruction</span> <span m="27260">depends</span> <span m="27670">on</span>
  <span m="27750">the</span> <span m="27890">execution</span> <span m="28500">of</span>
  <span m="28600">the</span> <span m="28670">current</span> <span m="29030">instruction.</span></p><p><span
  m="30900">What</span> <span m="31040">are</span> <span m="31120">the</span> <span
  m="31290">implications</span> <span m="32080">of</span> <span m="32210">this</span>
  <span m="32420">dependency</span> <span m="33150">on</span> <span m="33370">our</span>
  <span m="33560">execution</span> <span m="34160">pipeline?</span></p><p><span m="36680">How</span>
  <span m="36820">does</span> <span m="37140">the</span> <span m="37340">unpipelined</span>
  <span m="38180">implementation</span> <span m="38840">determine</span> <span m="39230">the</span>
  <span m="39290">next</span> <span m="39590">instruction?</span></p><p><span m="41190">For</span>
  <span m="41270">branches</span> <span m="42050">(BEQ</span> <span m="42580">or</span>
  <span m="42830">BNE),</span> <span m="43150">the</span> <span m="43730">value</span>
  <span m="44310">to</span> <span m="44430">be</span> <span m="44600">loaded</span>
  <span m="45010">into</span> <span m="45260">the</span> <span m="45360">program</span>
  <span m="45860">counter</span> <span m="46210">depends</span> <span m="46750">on</span></p><p><span
  m="47760">(1)</span> <span m="47910">the</span> <span m="48170">opcode,</span> <span
  m="48830">i.e.,</span> <span m="49270">whether</span> <span m="49930">the</span>
  <span m="50110">instruction</span> <span m="50740">is</span> <span m="50910">a</span>
  <span m="50950">BEQ</span> <span m="51470">or</span> <span m="51680">a</span> <span
  m="51710">BNE,</span></p><p><span m="51920">(2)</span> <span m="51960">the</span>
  <span m="52960">current</span> <span m="54380">value</span> <span m="55090">of</span>
  <span m="55180">the</span> <span m="55260">program</span> <span m="55750">counter</span>
  <span m="56250">since</span> <span m="56650">that&rsquo;s</span> <span m="56990">used</span>
  <span m="57340">in</span> <span m="57410">the</span> <span m="57520">offset</span>
  <span m="57890">calculation,</span> <span m="58830">and</span></p><p><span m="59330">(3)</span>
  <span m="59380">the</span> <span m="59930">value</span> <span m="60530">stored</span>
  <span m="60930">in</span> <span m="61020">the</span> <span m="61090">register</span>
  <span m="61610">specified</span> <span m="62180">by</span> <span m="62340">the</span>
  <span m="62520">RA</span> <span m="62860">field</span> <span m="63230">of</span>
  <span m="63320">the</span> <span m="63450">instruction</span> <span m="64140">since</span>
  <span m="64610">that&rsquo;s</span> <span m="64920">the</span> <span m="65019">value</span>
  <span m="65370">tested</span> <span m="65810">by</span> <span m="65930">the</span>
  <span m="66030">branch.</span></p><p><span m="67990">For</span> <span m="68160">JMP</span>
  <span m="68440">instructions,</span> <span m="69470">the</span> <span m="69710">next</span>
  <span m="70010">value</span> <span m="70300">of</span> <span m="70360">the</span>
  <span m="70420">program</span> <span m="70860">counter</span> <span m="71180">depends</span>
  <span m="71590">once</span> <span m="71880">again</span> <span m="72210">on</span>
  <span m="72440">the</span> <span m="72580">opcode</span> <span m="73100">field</span>
  <span m="73640">and</span> <span m="73960">the</span> <span m="74050">value</span>
  <span m="74500">of</span> <span m="74630">the</span> <span m="74860">RA</span> <span
  m="75140">register.</span></p><p><span m="77030">For</span> <span m="77200">all</span>
  <span m="77440">other</span> <span m="77750">instructions,</span> <span m="78450">the</span>
  <span m="78550">next</span> <span m="78830">PC</span> <span m="79220">value</span>
  <span m="79560">depends</span> <span m="79970">only</span> <span m="80340">the</span>
  <span m="80560">opcode</span> <span m="81070">of</span> <span m="81170">the</span>
  <span m="81290">instruction</span> <span m="82120">and</span> <span m="82430">the</span>
  <span m="82500">value</span> <span m="82820">PC+4.</span></p><p><span m="85540">Exceptions</span>
  <span m="86370">also</span> <span m="86740">change</span> <span m="87060">the</span>
  <span m="87130">program</span> <span m="87570">counter.</span></p><p><span m="88560">We&rsquo;ll</span>
  <span m="88750">deal</span> <span m="88950">with</span> <span m="89200">them</span>
  <span m="89550">later</span> <span m="89930">in</span> <span m="89990">the</span>
  <span m="90050">lecture.</span></p><p><span m="92010">The</span> <span m="92080">control</span>
  <span m="92460">hazard</span> <span m="92840">is</span> <span m="92990">triggered</span>
  <span m="93370">by</span> <span m="93540">JMP</span> <span m="93910">and</span>
  <span m="94200">branches</span> <span m="94870">since</span> <span m="95270">their</span>
  <span m="95590">execution</span> <span m="96270">depends</span> <span m="96720">on</span>
  <span m="96810">the</span> <span m="96910">value</span> <span m="97370">in</span>
  <span m="97440">the</span> <span m="97600">RA</span> <span m="97850">register,</span>
  <span m="98610">i.e.,</span> <span m="99060">they</span> <span m="99400">need</span>
  <span m="99600">to</span> <span m="99660">read</span> <span m="100140">from</span>
  <span m="100300">the</span> <span m="100410">register</span> <span m="100810">file,</span>
  <span m="101390">which</span> <span m="101800">happens</span> <span m="102330">in</span>
  <span m="102430">the</span> <span m="102550">RF</span> <span m="102870">pipeline</span>
  <span m="103090">stage.</span></p><p><span m="104320">Our</span> <span m="104450">bypass</span>
  <span m="105050">mechanisms</span> <span m="105710">ensure</span> <span m="106100">that</span>
  <span m="106270">we&rsquo;ll</span> <span m="106430">use</span> <span m="106630">the</span>
  <span m="106710">correct</span> <span m="107090">value</span> <span m="107380">for</span>
  <span m="107540">the</span> <span m="107670">RA</span> <span m="108000">register</span>
  <span m="108770">even</span> <span m="109280">if</span> <span m="109440">it&rsquo;s</span>
  <span m="109580">not</span> <span m="109800">yet</span> <span m="110220">written</span>
  <span m="110540">into</span> <span m="110750">the</span> <span m="110860">register</span>
  <span m="111290">file.</span></p><p><span m="112580">What</span> <span m="112700">we&rsquo;re</span>
  <span m="112850">concerned</span> <span m="113300">about</span> <span m="113650">here</span>
  <span m="114350">is</span> <span m="114770">that</span> <span m="114950">the</span>
  <span m="115120">address</span> <span m="115690">of</span> <span m="115760">the</span>
  <span m="115860">instruction</span> <span m="116430">following</span> <span m="116830">the</span>
  <span m="116910">JMP</span> <span m="117190">or</span> <span m="117260">branch</span>
  <span m="117700">will</span> <span m="117820">be</span> <span m="117980">loaded</span>
  <span m="118380">into</span> <span m="118620">program</span> <span m="119160">counter</span>
  <span m="119560">at</span> <span m="119700">the</span> <span m="119880">end</span>
  <span m="120210">of</span> <span m="120290">the</span> <span m="120370">cycle</span>
  <span m="121080">when</span> <span m="121420">the</span> <span m="121500">JMP</span>
  <span m="121890">or</span> <span m="122000">branch</span> <span m="122470">is</span>
  <span m="122580">in</span> <span m="122820">the</span> <span m="122990">RF</span>
  <span m="123320">stage.</span></p><p><span m="125070">But</span> <span m="125220">what</span>
  <span m="125500">should</span> <span m="125720">the</span> <span m="125970">IF</span>
  <span m="126330">stage</span> <span m="126820">be</span> <span m="126950">doing</span>
  <span m="127350">while</span> <span m="127620">all</span> <span m="127870">this</span>
  <span m="128039">is</span> <span m="128130">going</span> <span m="128430">on</span>
  <span m="128729">in</span> <span m="128919">RF</span> <span m="129190">stage?</span></p><p><span
  m="131290">The</span> <span m="131500">answer</span> <span m="132010">is</span>
  <span m="132280">that</span> <span m="132510">in</span> <span m="132640">the</span>
  <span m="132710">case</span> <span m="133100">of</span> <span m="133220">JMPs</span>
  <span m="133720">and</span> <span m="133880">taken</span> <span m="134220">branches,</span>
  <span m="134770">we</span> <span m="134920">don&rsquo;t</span> <span m="135220">know</span>
  <span m="135450">what</span> <span m="135620">the</span> <span m="135840">IF</span>
  <span m="136110">stage</span> <span m="136470">should</span> <span m="136600">be</span>
  <span m="136740">doing</span> <span m="137150">until</span> <span m="137510">those</span>
  <span m="137810">instructions</span> <span m="138390">are</span> <span m="138500">able</span>
  <span m="138730">to</span> <span m="138850">access</span> <span m="139500">the</span>
  <span m="139610">value</span> <span m="140280">of</span> <span m="140590">the</span>
  <span m="140770">RA</span> <span m="141070">register</span> <span m="141690">in</span>
  <span m="141830">the</span> <span m="141940">RF</span> <span m="142250">stage.</span></p><p><span
  m="143890">One</span> <span m="144150">solution</span> <span m="144690">is</span>
  <span m="144850">to</span> <span m="144950">stall</span> <span m="145370">the</span>
  <span m="145560">IF</span> <span m="145790">stage</span> <span m="146180">until</span>
  <span m="146390">the</span> <span m="146520">RF</span> <span m="146840">stage</span>
  <span m="147200">can</span> <span m="147310">compute</span> <span m="147740">the</span>
  <span m="147850">necessary</span> <span m="148550">result.</span></p><p><span m="150200">This</span>
  <span m="150480">was</span> <span m="150680">the</span> <span m="150780">first</span>
  <span m="151150">of</span> <span m="151240">our</span> <span m="151360">general</span>
  <span m="151760">strategies</span> <span m="152410">for</span> <span m="152580">dealing</span>
  <span m="152860">with</span> <span m="152970">hazards.</span></p><p><span m="154280">How</span>
  <span m="154390">would</span> <span m="154530">this</span> <span m="154720">work?</span></p><p><span
  m="156610">If</span> <span m="156740">the</span> <span m="156910">opcode</span>
  <span m="157520">in</span> <span m="157630">the</span> <span m="157770">RF</span>
  <span m="158130">stage</span> <span m="158510">is</span> <span m="158680">JMP,</span>
  <span m="159120">BEQ,</span> <span m="159700">or</span> <span m="159900">BNE,</span>
  <span m="160510">stall</span> <span m="161190">the</span> <span m="161380">IF</span>
  <span m="161630">stage</span> <span m="161990">for</span> <span m="162150">one</span>
  <span m="162340">cycle.</span></p><p><span m="163790">In</span> <span m="163880">the</span>
  <span m="164040">example</span> <span m="164480">code</span> <span m="164760">shown</span>
  <span m="165060">here,</span> <span m="165570">assume</span> <span m="166060">that</span>
  <span m="166210">the</span> <span m="166310">value</span> <span m="166860">in</span>
  <span m="166920">R3</span> <span m="167460">is</span> <span m="167780">non-zero</span>
  <span m="168480">when</span> <span m="168780">the</span> <span m="169080">BNE</span>
  <span m="169150">is</span> <span m="169410">executed,</span> <span m="170290">i.e.,</span>
  <span m="170630">that</span> <span m="171000">the</span> <span m="171320">instruction</span>
  <span m="172130">following</span> <span m="172610">BNE</span> <span m="173290">should</span>
  <span m="173760">be</span> <span m="173920">the</span> <span m="174050">ADDC</span>
  <span m="174150">at</span> <span m="174480">the</span> <span m="174950">top</span>
  <span m="175470">of</span> <span m="175530">the</span> <span m="175620">loop.</span></p><p><span
  m="177380">The</span> <span m="177450">pipeline</span> <span m="177980">diagram</span>
  <span m="178520">shows</span> <span m="178930">the</span> <span m="179030">effect</span>
  <span m="179410">we&rsquo;re</span> <span m="179540">trying</span> <span m="179770">to</span>
  <span m="179930">achieve:</span> <span m="180750">a</span> <span m="181240">NOP</span>
  <span m="181800">is</span> <span m="181950">inserted</span> <span m="182440">into</span>
  <span m="182690">the</span> <span m="182790">pipeline</span> <span m="183290">in</span>
  <span m="183440">cycles</span> <span m="183940">4</span> <span m="184220">and</span>
  <span m="184710">8.</span></p><p><span m="185790">Then</span> <span m="185990">execution</span>
  <span m="186530">resumes</span> <span m="187190">in</span> <span m="187260">the</span>
  <span m="187340">next</span> <span m="187630">cycle</span> <span m="188310">after</span>
  <span m="188790">the</span> <span m="188940">RF</span> <span m="189270">stage</span>
  <span m="189610">determines</span> <span m="190130">what</span> <span m="190290">instruction</span>
  <span m="190750">comes</span> <span m="191080">next.</span></p><p><span m="192430">Note,</span>
  <span m="192620">by</span> <span m="192770">the</span> <span m="192850">way,</span>
  <span m="193080">that</span> <span m="193210">we&rsquo;re</span> <span m="193340">relying</span>
  <span m="193890">on</span> <span m="194020">our</span> <span m="194140">bypass</span>
  <span m="194760">logic</span> <span m="195140">to</span> <span m="195260">deliver</span>
  <span m="195620">the</span> <span m="195730">correct</span> <span m="196150">value</span>
  <span m="196520">for</span> <span m="196990">R3</span> <span m="197420">from</span>
  <span m="197810">the</span> <span m="197900">MEM</span> <span m="198150">stage</span>
  <span m="198830">since</span> <span m="199310">the</span> <span m="199560">ADDC</span>
  <span m="199880">instruction</span> <span m="200510">that</span> <span m="200720">wrote</span>
  <span m="201040">into</span> <span m="201330">R3</span> <span m="201660">is</span>
  <span m="202050">still</span> <span m="202480">in</span> <span m="202540">the</span>
  <span m="202640">pipeline,</span> <span m="203440">i.e.,</span> <span m="203750">we</span>
  <span m="204240">have</span> <span m="204660">a</span> <span m="204800">data</span>
  <span m="205130">hazard</span> <span m="205550">to</span> <span m="205630">deal</span>
  <span m="205820">with</span> <span m="206060">too!</span></p><p><span m="208170">Looking</span>
  <span m="208480">at,</span> <span m="208580">say,</span> <span m="208890">the</span>
  <span m="208970">WB</span> <span m="209510">stage</span> <span m="210240">in</span>
  <span m="210530">the</span> <span m="210600">pipeline</span> <span m="211130">diagram,</span>
  <span m="211930">we</span> <span m="212200">see</span> <span m="212380">it</span>
  <span m="212670">takes</span> <span m="212930">4</span> <span m="213130">cycles</span>
  <span m="213860">to</span> <span m="213970">execute</span> <span m="214530">one</span>
  <span m="214880">iteration</span> <span m="215560">of</span> <span m="215740">our</span>
  <span m="215980">3-instruction</span> <span m="216860">loop.</span></p><p><span
  m="218060">So</span> <span m="218210">the</span> <span m="218370">effective</span>
  <span m="218870">CPI</span> <span m="219660">is</span> <span m="219980">4/3,</span>
  <span m="220490">an</span> <span m="220930">increase</span> <span m="221680">of</span>
  <span m="222430">33%.</span></p><p><span m="224450">Using</span> <span m="224780">stall</span>
  <span m="225360">to</span> <span m="225480">deal</span> <span m="225740">with</span>
  <span m="225870">control</span> <span m="226280">hazards</span> <span m="226700">has</span>
  <span m="226880">had</span> <span m="227030">an</span> <span m="227220">impact</span>
  <span m="228010">on</span> <span m="228280">the</span> <span m="228400">instruction</span>
  <span m="229050">throughput</span> <span m="229520">of</span> <span m="229640">our</span>
  <span m="229780">execution</span> <span m="230330">pipeline.</span></p><p><span
  m="233350">We&rsquo;ve</span> <span m="233520">already</span> <span m="233760">seen</span>
  <span m="234100">the</span> <span m="234170">logic</span> <span m="234640">needed</span>
  <span m="234990">to</span> <span m="235200">introduce</span> <span m="235810">NOPs</span>
  <span m="236380">into</span> <span m="236560">the</span> <span m="236660">pipeline.</span></p><p><span
  m="237900">In</span> <span m="238010">this</span> <span m="238230">case,</span>
  <span m="238530">we</span> <span m="238700">add</span> <span m="238810">a</span>
  <span m="238870">mux</span> <span m="239290">to</span> <span m="239370">the</span>
  <span m="239510">instruction</span> <span m="240020">path</span> <span m="240430">in</span>
  <span m="240520">the</span> <span m="240690">IF</span> <span m="241010">stage,</span>
  <span m="241660">controlled</span> <span m="242360">by</span> <span m="242540">the</span>
  <span m="242810">IRSrc_IF</span> <span m="243810">signal.</span></p><p><span m="245380">We</span>
  <span m="245490">use</span> <span m="245710">the</span> <span m="245790">superscript</span>
  <span m="246570">on</span> <span m="246680">the</span> <span m="246750">control</span>
  <span m="247150">signals</span> <span m="247580">to</span> <span m="247670">indicate</span>
  <span m="248120">which</span> <span m="248430">pipeline</span> <span m="248940">stage</span>
  <span m="249390">holds</span> <span m="249710">the</span> <span m="249790">logic</span>
  <span m="250360">they</span> <span m="250550">control.</span></p><p><span m="253390">If</span>
  <span m="253530">the</span> <span m="253660">opcode</span> <span m="254320">in</span>
  <span m="254440">the</span> <span m="254570">RF</span> <span m="254900">stage</span>
  <span m="255330">is</span> <span m="255450">JMP,</span> <span m="255730">BEQ,</span>
  <span m="256250">or</span> <span m="256450">BNE</span> <span m="256769">we</span>
  <span m="257339">set</span> <span m="258130">IRSrc_IF</span> <span m="259070">to</span>
  <span m="259320">1,</span> <span m="259450">which</span> <span m="260180">causes</span>
  <span m="260870">a</span> <span m="260930">NOP</span> <span m="261450">to</span>
  <span m="261570">replace</span> <span m="262150">the</span> <span m="262300">instruction</span>
  <span m="262840">that</span> <span m="262950">was</span> <span m="263110">being</span>
  <span m="263410">read</span> <span m="263710">from</span> <span m="263880">main</span>
  <span m="264100">memory.</span></p><p><span m="265330">And,</span> <span m="265630">of</span>
  <span m="265700">course,</span> <span m="266030">we&rsquo;ll</span> <span m="266140">be</span>
  <span m="266270">setting</span> <span m="266590">the</span> <span m="266670">PCSEL</span>
  <span m="267070">control</span> <span m="267560">signals</span> <span m="268010">to</span>
  <span m="268130">select</span> <span m="268540">the</span> <span m="268600">correct</span>
  <span m="268990">next</span> <span m="269280">PC</span> <span m="269640">value,</span>
  <span m="270180">so</span> <span m="270490">the</span> <span m="270810">IF</span>
  <span m="270980">stage</span> <span m="271490">will</span> <span m="271640">fetch</span>
  <span m="272030">the</span> <span m="272150">desired</span> <span m="272730">follow-on</span>
  <span m="273310">instruction</span> <span m="274030">in</span> <span m="274230">the</span>
  <span m="274290">next</span> <span m="274580">cycle.</span></p><p><span m="276400">If</span>
  <span m="276550">we</span> <span m="276620">replace</span> <span m="277420">an</span>
  <span m="277600">instruction</span> <span m="278070">with</span> <span m="278260">NOP,</span>
  <span m="279070">we</span> <span m="279430">say</span> <span m="279690">we</span>
  <span m="279940">&ldquo;annulled&rdquo;</span> <span m="280560">the</span> <span
  m="280780">instruction.</span></p><p><span m="282880">The</span> <span m="282950">branch</span>
  <span m="283320">instructions</span> <span m="284010">in</span> <span m="284080">the</span>
  <span m="284180">Beta</span> <span m="284560">ISA</span> <span m="285100">make</span>
  <span m="285430">their</span> <span m="285530">branch</span> <span m="285820">decision</span>
  <span m="286360">in</span> <span m="286440">the</span> <span m="286580">RF</span>
  <span m="286930">stage</span> <span m="287480">since</span> <span m="287770">they</span>
  <span m="287930">only</span> <span m="288120">need</span> <span m="288340">the</span>
  <span m="288420">value</span> <span m="288920">in</span> <span m="289000">register</span>
  <span m="289560">RA.</span></p><p><span m="291180">But</span> <span m="291280">suppose</span>
  <span m="291770">the</span> <span m="291990">ISA</span> <span m="292500">had</span>
  <span m="292700">a</span> <span m="292750">branch</span> <span m="293180">where</span>
  <span m="293350">the</span> <span m="293440">branch</span> <span m="293750">decision</span>
  <span m="294200">was</span> <span m="294360">made</span> <span m="294570">in</span>
  <span m="294810">ALU</span> <span m="295280">stage.</span></p><p><span m="297480">When</span>
  <span m="297570">the</span> <span m="297640">branch</span> <span m="297930">decision</span>
  <span m="298360">is</span> <span m="298480">made</span> <span m="298700">in</span>
  <span m="298770">the</span> <span m="299070">ALU</span> <span m="299350">stage,</span>
  <span m="299890">we</span> <span m="300010">need</span> <span m="300190">to</span>
  <span m="300270">introduce</span> <span m="300800">two</span> <span m="301220">NOPs</span>
  <span m="301580">into</span> <span m="301750">the</span> <span m="301850">pipeline,</span>
  <span m="302570">replacing</span> <span m="303270">the</span> <span m="303360">now</span>
  <span m="303740">unwanted</span> <span m="304230">instructions</span> <span m="304970">in</span>
  <span m="305040">the</span> <span m="305190">RF</span> <span m="305730">and</span>
  <span m="305950">IF</span> <span m="306250">stages.</span></p><p><span m="307930">This</span>
  <span m="308150">would</span> <span m="308290">increase</span> <span m="308800">the</span>
  <span m="308920">effective</span> <span m="309370">CPI</span> <span m="310020">even</span>
  <span m="310340">further.</span></p><p><span m="312610">But</span> <span m="312780">the</span>
  <span m="312910">tradeoff</span> <span m="313610">is</span> <span m="313790">that</span>
  <span m="314020">the</span> <span m="314130">more</span> <span m="314490">complex</span>
  <span m="315090">branches</span> <span m="315860">may</span> <span m="316230">reduce</span>
  <span m="316810">the</span> <span m="316910">number</span> <span m="317320">of</span>
  <span m="317410">instructions</span> <span m="318090">in</span> <span m="318150">the</span>
  <span m="318220">program.</span></p><p><span m="320000">If</span> <span m="320110">we</span>
  <span m="320220">annul</span> <span m="320540">instructions</span> <span m="321190">in</span>
  <span m="321270">all</span> <span m="321570">the</span> <span m="321700">earlier</span>
  <span m="321990">pipeline</span> <span m="322430">stages,</span> <span m="322970">this</span>
  <span m="323190">is</span> <span m="323300">called</span> <span m="323570">&ldquo;flushing</span>
  <span m="324070">the</span> <span m="324150">pipeline&rdquo;.</span></p><p><span
  m="325650">Since</span> <span m="325900">flushing</span> <span m="326220">the</span>
  <span m="326300">pipeline</span> <span m="326740">has</span> <span m="326910">a</span>
  <span m="326950">big</span> <span m="327250">impact</span> <span m="327780">on</span>
  <span m="327890">the</span> <span m="328000">effective</span> <span m="328440">CPI,</span>
  <span m="329440">we</span> <span m="329920">do</span> <span m="330180">it</span>
  <span m="330270">when</span> <span m="330490">it&rsquo;s</span> <span m="330650">the</span>
  <span m="330820">only</span> <span m="331180">way</span> <span m="331540">to</span>
  <span m="331780">ensure</span> <span m="332500">the</span> <span m="332760">correct</span>
  <span m="333320">behavior</span> <span m="334220">of</span> <span m="334670">the</span>
  <span m="334790">execution</span> <span m="335410">pipeline.</span></p><p><span
  m="337850">We</span> <span m="337950">can</span> <span m="338060">be</span> <span
  m="338180">smarter</span> <span m="338720">about</span> <span m="339250">when</span>
  <span m="339690">we</span> <span m="339790">choose</span> <span m="340140">to</span>
  <span m="340230">flush</span> <span m="340540">the</span> <span m="340630">pipeline</span>
  <span m="341290">when</span> <span m="341470">executing</span> <span m="342000">branches.</span></p><p><span
  m="342880">If</span> <span m="343140">the</span> <span m="343430">branch</span>
  <span m="343790">is</span> <span m="343920">not</span> <span m="344250">taken,</span>
  <span m="344690">it</span> <span m="344800">turns</span> <span m="345180">out</span>
  <span m="345430">that</span> <span m="345620">the</span> <span m="345710">pipeline</span>
  <span m="346210">has</span> <span m="346400">been</span> <span m="346600">doing</span>
  <span m="346870">the</span> <span m="346950">right</span> <span m="347180">thing</span>
  <span m="347550">by</span> <span m="347710">fetching</span> <span m="348110">the</span>
  <span m="348220">instruction</span> <span m="348790">following</span> <span m="349260">the</span>
  <span m="349330">branch.</span></p><p><span m="351020">Starting</span> <span m="351490">execution</span>
  <span m="352090">of</span> <span m="352220">an</span> <span m="352290">instruction</span>
  <span m="353220">even</span> <span m="353690">when</span> <span m="353820">we&rsquo;re</span>
  <span m="354110">unsure</span> <span m="354620">whether</span> <span m="354880">we</span>
  <span m="355060">really</span> <span m="355330">want</span> <span m="355680">it</span>
  <span m="355760">executed</span> <span m="356500">is</span> <span m="356750">called</span>
  <span m="357030">&ldquo;speculation&rdquo;.</span></p><p><span m="359310">Speculative</span>
  <span m="359880">execution</span> <span m="360230">is</span> <span m="360290">okay</span>
  <span m="360850">if</span> <span m="360980">we&rsquo;re</span> <span m="361140">able</span>
  <span m="361420">to</span> <span m="361650">annul</span> <span m="361960">the</span>
  <span m="362070">instruction</span> <span m="362590">before</span> <span m="362910">it</span>
  <span m="362970">has</span> <span m="363180">an</span> <span m="363240">effect</span>
  <span m="363640">on</span> <span m="363850">the</span> <span m="364000">CPU</span>
  <span m="364260">state,</span> <span m="365050">e.g.,</span> <span m="365730">by</span>
  <span m="365880">writing</span> <span m="366320">into</span> <span m="366460">the</span>
  <span m="366550">register</span> <span m="366990">file</span> <span m="367300">or</span>
  <span m="367430">main</span> <span m="367600">memory.</span></p><p><span m="368830">Since</span>
  <span m="369130">these</span> <span m="369370">state</span> <span m="369650">changes</span>
  <span m="370260">(called</span> <span m="370580">&ldquo;side</span> <span m="370850">effects&rdquo;)</span>
  <span m="371440">happen</span> <span m="372010">in</span> <span m="372160">the</span>
  <span m="372240">later</span> <span m="372640">pipeline</span> <span m="373080">stages,</span>
  <span m="373860">an</span> <span m="374160">instruction</span> <span m="374840">can</span>
  <span m="375000">progress</span> <span m="375610">through</span> <span m="375790">the</span>
  <span m="376040">IF,</span> <span m="376540">RF,</span> <span m="377010">and</span>
  <span m="377160">ALU</span> <span m="377500">stages</span> <span m="378230">before</span>
  <span m="378690">we</span> <span m="378800">have</span> <span m="379150">to</span>
  <span m="379260">make</span> <span m="379470">a</span> <span m="379520">final</span>
  <span m="379900">decision</span> <span m="380380">about</span> <span m="380590">whether</span>
  <span m="380920">it</span> <span m="381000">should</span> <span m="381140">be</span>
  <span m="381310">annulled.</span></p><p><span m="383490">How</span> <span m="383660">does</span>
  <span m="383800">speculation</span> <span m="384420">help</span> <span m="384740">with</span>
  <span m="384870">control</span> <span m="385260">hazards?</span></p><p><span m="386350">Guessing</span>
  <span m="387040">that</span> <span m="387430">the</span> <span m="387560">next</span>
  <span m="387900">value</span> <span m="388250">of</span> <span m="388310">the</span>
  <span m="388370">program</span> <span m="388820">counter</span> <span m="389240">is</span>
  <span m="389380">PC+4</span> <span m="389810">is</span> <span m="390290">correct</span>
  <span m="390950">for</span> <span m="391110">all</span> <span m="391350">but</span>
  <span m="391550">JMPs</span> <span m="392080">and</span> <span m="392220">taken</span>
  <span m="392540">branches.</span></p><p><span m="394260">Here&rsquo;s</span> <span
  m="394500">our</span> <span m="394650">example</span> <span m="395050">again,</span>
  <span m="395500">but</span> <span m="395810">this</span> <span m="396050">time</span>
  <span m="396320">let&rsquo;s</span> <span m="396520">assume</span> <span m="396870">that</span>
  <span m="397120">the</span> <span m="397430">BNE</span> <span m="397500">is</span>
  <span m="397800">not</span> <span m="398110">taken,</span> <span m="398760">i.e.,</span>
  <span m="399030">that</span> <span m="399370">the</span> <span m="399680">value</span>
  <span m="400210">in</span> <span m="400510">R3</span> <span m="400800">is</span>
  <span m="401160">zero.</span></p><p><span m="402660">The</span> <span m="402740">SUB</span>
  <span m="403030">instruction</span> <span m="403650">enters</span> <span m="403940">the</span>
  <span m="404030">pipeline</span> <span m="404590">at</span> <span m="404660">the</span>
  <span m="404730">start</span> <span m="405130">of</span> <span m="405190">cycle</span>
  <span m="405610">4.</span></p><p><span m="406560">At</span> <span m="406680">the</span>
  <span m="406890">end</span> <span m="407200">of</span> <span m="407270">cycle</span>
  <span m="407690">4,</span> <span m="407880">we</span> <span m="408200">know</span>
  <span m="408380">whether</span> <span m="408690">or</span> <span m="408790">not</span>
  <span m="409040">to</span> <span m="409230">annul</span> <span m="409530">the</span>
  <span m="409590">SUB.</span></p><p><span m="410990">If</span> <span m="411070">the</span>
  <span m="411150">branch</span> <span m="411540">is</span> <span m="411670">not</span>
  <span m="411970">taken,</span> <span m="412750">we</span> <span m="413200">want</span>
  <span m="413660">to</span> <span m="413900">execute</span> <span m="414360">the</span>
  <span m="414430">SUB</span> <span m="414710">instruction,</span> <span m="415280">so</span>
  <span m="415520">we</span> <span m="415650">just</span> <span m="415870">let</span>
  <span m="416020">it</span> <span m="416100">continue</span> <span m="416690">down</span>
  <span m="416920">the</span> <span m="416990">pipeline.</span></p><p><span m="418510">In</span>
  <span m="418660">other</span> <span m="418840">words,</span> <span m="419230">instead</span>
  <span m="419570">of</span> <span m="419740">always</span> <span m="420160">annulling</span>
  <span m="420730">the</span> <span m="420870">instruction</span> <span m="421450">following</span>
  <span m="421880">branch,</span> <span m="422600">we</span> <span m="422990">only</span>
  <span m="423350">annul</span> <span m="423730">it</span> <span m="423860">if</span>
  <span m="424030">the</span> <span m="424150">branch</span> <span m="424520">was</span>
  <span m="424680">taken.</span></p><p><span m="425980">If</span> <span m="426050">the</span>
  <span m="426110">branch</span> <span m="426500">is</span> <span m="426650">not</span>
  <span m="426960">taken,</span> <span m="427410">the</span> <span m="427550">pipeline</span>
  <span m="427950">has</span> <span m="428060">speculated</span> <span m="428640">correctly</span>
  <span m="429440">and</span> <span m="429750">no</span> <span m="429990">instructions</span>
  <span m="430710">need</span> <span m="431040">to</span> <span m="431150">be</span>
  <span m="431390">annulled.</span></p><p><span m="433020">However</span> <span m="433520">if</span>
  <span m="433720">the</span> <span m="434240">BNE</span> <span m="434320">is</span>
  <span m="434550">taken,</span> <span m="435140">the</span> <span m="435350">SUB</span>
  <span m="435740">is</span> <span m="435950">annulled</span> <span m="436400">at</span>
  <span m="436500">the</span> <span m="436720">end</span> <span m="437050">of</span>
  <span m="437150">cycle</span> <span m="437530">4</span> <span m="437980">and</span>
  <span m="438530">a</span> <span m="438600">NOP</span> <span m="438940">is</span>
  <span m="439090">executed</span> <span m="439710">in</span> <span m="439790">cycle</span>
  <span m="440190">5.</span></p><p><span m="440230">So</span> <span m="441040">we</span>
  <span m="441770">only</span> <span m="442080">introduce</span> <span m="442480">a</span>
  <span m="442520">bubble</span> <span m="442930">in</span> <span m="443020">the</span>
  <span m="443100">pipeline</span> <span m="443820">when</span> <span m="443970">there&rsquo;s</span>
  <span m="444160">a</span> <span m="444300">taken</span> <span m="444700">branch.</span></p><p><span
  m="445780">Fewer</span> <span m="446090">bubbles</span> <span m="446550">will</span>
  <span m="446690">decrease</span> <span m="447240">the</span> <span m="447380">impact</span>
  <span m="447870">of</span> <span m="447980">annulment</span> <span m="448560">on</span>
  <span m="448780">the</span> <span m="448910">effective</span> <span m="449430">CPI.</span></p><p><span
  m="451620">We&rsquo;ll</span> <span m="451750">be</span> <span m="451870">using</span>
  <span m="452190">the</span> <span m="452250">same</span> <span m="452560">data</span>
  <span m="452840">path</span> <span m="453120">circuitry</span> <span m="453650">as</span>
  <span m="453780">before,</span> <span m="454420">we&rsquo;ll</span> <span m="454700">just</span>
  <span m="454970">be</span> <span m="455140">a</span> <span m="455180">bit</span>
  <span m="455370">more</span> <span m="455540">clever</span> <span m="456040">about</span>
  <span m="456380">when</span> <span m="456540">the</span> <span m="456620">value</span>
  <span m="457150">of</span> <span m="457350">the</span> <span m="457770">IRSrc_IF</span>
  <span m="458950">control</span> <span m="459380">signal</span> <span m="459800">is</span>
  <span m="459920">set</span> <span m="460190">to</span> <span m="460670">1.</span></p><p><span
  m="461560">Instead</span> <span m="462000">of</span> <span m="462080">setting</span>
  <span m="462440">it</span> <span m="462520">to</span> <span m="462730">1</span>
  <span m="462870">for</span> <span m="463100">all</span> <span m="463310">branches,</span>
  <span m="464050">we</span> <span m="464370">only</span> <span m="464650">set</span>
  <span m="464850">it</span> <span m="464970">to</span> <span m="465090">1</span>
  <span m="465120">when</span> <span m="465530">the</span> <span m="465730">branch</span>
  <span m="466230">is</span> <span m="466390">taken.</span></p><p><span m="469000">Our</span>
  <span m="469090">naive</span> <span m="469450">strategy</span> <span m="470000">of</span>
  <span m="470080">always</span> <span m="470400">speculating</span> <span m="471060">that</span>
  <span m="471150">the</span> <span m="471230">next</span> <span m="471580">instruction</span>
  <span m="472080">comes</span> <span m="472320">from</span> <span m="472440">PC+4</span>
  <span m="472810">is</span> <span m="473420">wrong</span> <span m="474270">for</span>
  <span m="474410">JMPs</span> <span m="474840">and</span> <span m="474970">taken</span>
  <span m="475210">branches.</span></p><p><span m="476840">Looking</span> <span m="477230">at</span>
  <span m="477570">simulated</span> <span m="478340">execution</span> <span m="478890">traces,</span>
  <span m="479580">we&rsquo;ll</span> <span m="479830">see</span> <span m="480060">that</span>
  <span m="480220">this</span> <span m="480470">error</span> <span m="480740">in</span>
  <span m="480800">speculation</span> <span m="481610">leads</span> <span m="481920">to</span>
  <span m="482290">about</span> <span m="482730">10%</span> <span m="483160">higher</span>
  <span m="484120">effective</span> <span m="484550">CPI.</span></p><p><span m="485940">Can</span>
  <span m="486090">we</span> <span m="486160">do</span> <span m="486300">better?</span></p><p><span
  m="488110">This</span> <span m="488300">is</span> <span m="488420">an</span> <span
  m="488480">important</span> <span m="488900">question</span> <span m="489350">for</span>
  <span m="489610">CPUs</span> <span m="490120">with</span> <span m="490290">deep</span>
  <span m="490530">pipelines.</span></p><p><span m="491890">For</span> <span m="492080">example,</span>
  <span m="492580">Intel&rsquo;s</span> <span m="493240">Nehalem</span> <span m="493560">processor</span>
  <span m="494390">from</span> <span m="495230">2009</span> <span m="495440">resolves</span>
  <span m="496100">the</span> <span m="496170">more</span> <span m="496370">complex</span>
  <span m="497070">x86</span> <span m="497750">branch</span> <span m="498120">instructions</span>
  <span m="498710">quite</span> <span m="498990">late</span> <span m="499190">in</span>
  <span m="499280">the</span> <span m="499340">pipeline.</span></p><p><span m="500940">Since</span>
  <span m="501160">Nehalem</span> <span m="501620">is</span> <span m="501740">capable</span>
  <span m="502170">of</span> <span m="502280">executing</span> <span m="502910">multiple</span>
  <span m="503400">instructions</span> <span m="503980">each</span> <span m="504080">cycle,</span>
  <span m="504880">flushing</span> <span m="505540">the</span> <span m="505620">pipeline</span>
  <span m="506320">in</span> <span m="506410">Nehalem</span> <span m="506750">actually</span>
  <span m="507200">annuls</span> <span m="507620">the</span> <span m="507720">execution</span>
  <span m="508220">of</span> <span m="508330">many</span> <span m="508800">instructions,</span>
  <span m="509700">resulting</span> <span m="510450">in</span> <span m="510590">a</span>
  <span m="510630">considerable</span> <span m="511400">hit</span> <span m="511650">on</span>
  <span m="511870">the</span> <span m="511930">CPI.</span></p><p><span m="514539">Like</span>
  <span m="514870">many</span> <span m="515309">modern</span> <span m="515720">processor</span>
  <span m="516240">implementations,</span> <span m="517250">Nehalem</span> <span m="518270">has</span>
  <span m="518690">a</span> <span m="518740">much</span> <span m="519090">more</span>
  <span m="519309">sophisticated</span> <span m="520490">speculation</span> <span
  m="521299">mechanism.</span></p><p><span m="523140">Rather</span> <span m="523380">than</span>
  <span m="523580">always</span> <span m="523980">guessing</span> <span m="524320">the</span>
  <span m="524400">next</span> <span m="524680">instruction</span> <span m="525170">is</span>
  <span m="525310">at</span> <span m="525390">PC+4,</span> <span m="526280">it</span>
  <span m="526910">only</span> <span m="527130">does</span> <span m="527370">that</span>
  <span m="527610">for</span> <span m="527760">non-branch</span> <span m="528340">instructions.</span></p><p><span
  m="529720">For</span> <span m="529820">branches,</span> <span m="530460">it</span>
  <span m="530560">predicts</span> <span m="530960">the</span> <span m="531050">behavior</span>
  <span m="531670">of</span> <span m="531770">each</span> <span m="532030">individual</span>
  <span m="532680">branch</span> <span m="533310">based</span> <span m="533810">on</span>
  <span m="533870">what</span> <span m="534110">the</span> <span m="534200">branch</span>
  <span m="534560">did</span> <span m="534750">last</span> <span m="535130">time</span>
  <span m="535330">it</span> <span m="535390">was</span> <span m="535580">executed</span>
  <span m="536370">and</span> <span m="536670">some</span> <span m="536890">knowledge</span>
  <span m="537420">of</span> <span m="537480">how</span> <span m="537700">the</span>
  <span m="537780">branch</span> <span m="538140">is</span> <span m="538260">being</span>
  <span m="538490">used.</span></p><p><span m="539630">For</span> <span m="539740">example,</span>
  <span m="540390">backward</span> <span m="541150">branches</span> <span m="541700">at</span>
  <span m="541790">the</span> <span m="541970">end</span> <span m="542220">of</span>
  <span m="542340">loops,</span> <span m="542910">which</span> <span m="543180">are</span>
  <span m="543450">taken</span> <span m="544120">for</span> <span m="544460">all</span>
  <span m="544690">but</span> <span m="544840">the</span> <span m="544920">final</span>
  <span m="545360">iteration</span> <span m="545800">of</span> <span m="545870">the</span>
  <span m="545950">loop,</span> <span m="546420">can</span> <span m="546780">be</span>
  <span m="546950">identified</span> <span m="547680">by</span> <span m="547870">their</span>
  <span m="548040">negative</span> <span m="548550">branch</span> <span m="548960">offset</span>
  <span m="549350">values.</span></p><p><span m="551120">Nehalem</span> <span m="551380">can</span>
  <span m="551540">even</span> <span m="551780">determine</span> <span m="552230">if</span>
  <span m="552360">there&rsquo;s</span> <span m="552600">correlation</span> <span
  m="553270">between</span> <span m="553740">branch</span> <span m="554070">instructions,</span>
  <span m="554940">using</span> <span m="555420">the</span> <span m="555480">results</span>
  <span m="555980">of</span> <span m="556100">an</span> <span m="556400">another,</span>
  <span m="557050">earlier</span> <span m="557530">branch</span> <span m="557840">to</span>
  <span m="557960">speculate</span> <span m="558610">on</span> <span m="558720">the</span>
  <span m="558790">branch</span> <span m="559060">decision</span> <span m="559550">of</span>
  <span m="559660">the</span> <span m="559730">current</span> <span m="560110">branch.</span></p><p><span
  m="561630">With</span> <span m="561800">these</span> <span m="562040">sophisticated</span>
  <span m="562840">strategies,</span> <span m="563710">Nehalem&rsquo;s</span> <span
  m="564400">speculation</span> <span m="565130">is</span> <span m="565270">correct</span>
  <span m="565720">95%</span> <span m="565830">to</span> <span m="566010">99%</span>
  <span m="566090">of</span> <span m="566400">the</span> <span m="566870">time,</span>
  <span m="567950">greatly</span> <span m="568940">reducing</span> <span m="569490">the</span>
  <span m="569610">impact</span> <span m="570100">of</span> <span m="570220">branches</span>
  <span m="570820">on</span> <span m="571000">the</span> <span m="571120">effective</span>
  <span m="571610">CPI.</span></p><p><span m="573890">There&rsquo;s</span> <span m="574090">also</span>
  <span m="574410">the</span> <span m="574510">lazy</span> <span m="574980">option</span>
  <span m="575340">of</span> <span m="575430">changing</span> <span m="575810">the</span>
  <span m="576020">ISA</span> <span m="576590">to</span> <span m="576750">deal</span>
  <span m="576950">with</span> <span m="577180">control</span> <span m="577620">hazards.</span></p><p><span
  m="578660">For</span> <span m="578770">example,</span> <span m="579200">we</span>
  <span m="579310">could</span> <span m="579440">change</span> <span m="579690">the</span>
  <span m="579900">ISA</span> <span m="580320">to</span> <span m="580420">specify</span>
  <span m="581430">that</span> <span m="581800">the</span> <span m="581950">instruction</span>
  <span m="582530">following</span> <span m="582990">a</span> <span m="583050">jump</span>
  <span m="583330">or</span> <span m="583400">branch</span> <span m="583840">is</span>
  <span m="583990">always</span> <span m="584260">executed.</span></p><p><span m="585610">In</span>
  <span m="585710">other</span> <span m="585870">words</span> <span m="586240">the</span>
  <span m="586320">transfer</span> <span m="586840">of</span> <span m="586900">control</span>
  <span m="587240">happens</span> <span m="587780">*after*</span> <span m="588250">the</span>
  <span m="588360">next</span> <span m="588660">instruction.</span></p><p><span m="590230">This</span>
  <span m="590420">change</span> <span m="590820">ensures</span> <span m="591230">that</span>
  <span m="591360">the</span> <span m="591460">guess</span> <span m="591760">of</span>
  <span m="591840">PC+4</span> <span m="592520">as</span> <span m="593010">the</span>
  <span m="593170">address</span> <span m="593620">of</span> <span m="593680">the</span>
  <span m="593760">next</span> <span m="593980">instruction</span> <span m="594510">is</span>
  <span m="594650">always</span> <span m="594910">correct!</span></p><p><span m="596840">In</span>
  <span m="596930">the</span> <span m="597060">example</span> <span m="597500">shown</span>
  <span m="597860">here,</span> <span m="598390">assuming</span> <span m="598910">we</span>
  <span m="599020">changed</span> <span m="599370">the</span> <span m="599590">ISA,</span>
  <span m="600280">we</span> <span m="600570">can</span> <span m="600710">reorganize</span>
  <span m="601500">the</span> <span m="601640">execution</span> <span m="602220">order</span>
  <span m="602580">of</span> <span m="602680">the</span> <span m="602750">loop</span>
  <span m="603060">to</span> <span m="603140">place</span> <span m="603450">the</span>
  <span m="603520">MUL</span> <span m="603840">instruction</span> <span m="604550">after</span>
  <span m="605040">the</span> <span m="605140">BNE</span> <span m="605260">instruction,</span>
  <span m="606320">in</span> <span m="606620">the</span> <span m="606690">so-called</span>
  <span m="607330">&ldquo;branch</span> <span m="607780">delay</span> <span m="608090">slot&rdquo;.</span></p><p><span
  m="609170">Since</span> <span m="609470">the</span> <span m="609600">instruction</span>
  <span m="610280">in</span> <span m="610350">the</span> <span m="610410">branch</span>
  <span m="610720">delay</span> <span m="611010">slot</span> <span m="611420">is</span>
  <span m="611600">always</span> <span m="611930">executed,</span> <span m="612710">the</span>
  <span m="612970">MUL</span> <span m="613250">instruction</span> <span m="613760">will</span>
  <span m="613880">be</span> <span m="614030">executed</span> <span m="614570">during</span>
  <span m="614870">each</span> <span m="615140">iteration</span> <span m="615580">of</span>
  <span m="615640">the</span> <span m="615710">loop.</span></p><p><span m="617320">The</span>
  <span m="617390">resulting</span> <span m="617890">execution</span> <span m="618650">is</span>
  <span m="618780">shown</span> <span m="619370">in</span> <span m="619520">this</span>
  <span m="619790">pipeline</span> <span m="620250">diagram.</span></p><p><span m="621470">Assuming</span>
  <span m="621870">we</span> <span m="621990">can</span> <span m="622130">find</span>
  <span m="622490">an</span> <span m="622570">appropriate</span> <span m="623150">instruction</span>
  <span m="623740">to</span> <span m="623820">place</span> <span m="624300">in</span>
  <span m="624390">the</span> <span m="624480">delay</span> <span m="624780">slot,</span>
  <span m="625400">the</span> <span m="625710">branch</span> <span m="626140">will</span>
  <span m="626240">have</span> <span m="626440">zero</span> <span m="626970">impact</span>
  <span m="627500">on</span> <span m="627670">the</span> <span m="627800">effective</span>
  <span m="628260">CPI.</span></p><p><span m="628720">Are</span> <span m="631110">branch</span>
  <span m="631450">delay</span> <span m="631710">slots</span> <span m="632150">a</span>
  <span m="632180">good</span> <span m="632380">idea?</span></p><p><span m="633700">Seems</span>
  <span m="634030">like</span> <span m="634230">they</span> <span m="634370">reduce</span>
  <span m="635010">the</span> <span m="635240">negative</span> <span m="635650">impact</span>
  <span m="636130">that</span> <span m="636260">branches</span> <span m="636710">might</span>
  <span m="636970">have</span> <span m="637270">on</span> <span m="637430">instruction</span>
  <span m="637940">throughput.</span></p><p><span m="640240">The</span> <span m="640320">downside</span>
  <span m="641000">is</span> <span m="641170">that</span> <span m="641300">only</span>
  <span m="641550">half</span> <span m="642000">the</span> <span m="642100">time</span>
  <span m="642420">can</span> <span m="642600">we</span> <span m="642720">find</span>
  <span m="642980">instructions</span> <span m="643570">to</span> <span m="643660">move</span>
  <span m="643910">to</span> <span m="644040">the</span> <span m="644120">branch</span>
  <span m="644420">delay</span> <span m="644680">slot.</span></p><p><span m="646030">The</span>
  <span m="646160">other</span> <span m="646390">half</span> <span m="646640">of</span>
  <span m="646700">the</span> <span m="646770">time</span> <span m="647110">we</span>
  <span m="647200">have</span> <span m="647350">to</span> <span m="647460">fill</span>
  <span m="647700">it</span> <span m="647760">with</span> <span m="647940">an</span>
  <span m="648040">explicit</span> <span m="648720">NOP</span> <span m="649140">instruction,</span>
  <span m="649930">increasing</span> <span m="650660">the</span> <span m="650720">size</span>
  <span m="651080">of</span> <span m="651170">the</span> <span m="651240">code.</span></p><p><span
  m="652580">And</span> <span m="652680">if</span> <span m="652770">we</span> <span
  m="652860">make</span> <span m="653110">the</span> <span m="653180">branch</span>
  <span m="653550">decision</span> <span m="654030">later</span> <span m="654420">in</span>
  <span m="654510">the</span> <span m="654580">pipeline,</span> <span m="655390">there</span>
  <span m="655720">are</span> <span m="655860">more</span> <span m="656260">branch</span>
  <span m="656550">delay</span> <span m="656810">slots,</span> <span m="657500">which</span>
  <span m="657910">would</span> <span m="658060">be</span> <span m="658280">even</span>
  <span m="658550">harder</span> <span m="659020">to</span> <span m="659110">fill.</span></p><p><span
  m="660410">In</span> <span m="660520">practice,</span> <span m="661260">it</span>
  <span m="661610">turns</span> <span m="661940">out</span> <span m="662160">that</span>
  <span m="662270">branch</span> <span m="662690">prediction</span> <span m="663120">works</span>
  <span m="663500">better</span> <span m="663880">than</span> <span m="664040">delay</span>
  <span m="664360">slots</span> <span m="664920">in</span> <span m="665030">reducing</span>
  <span m="665650">the</span> <span m="665790">impact</span> <span m="666280">of</span>
  <span m="666340">branches.</span></p><p><span m="667830">So,</span> <span m="668240">once</span>
  <span m="668630">again</span> <span m="668950">we</span> <span m="669090">see</span>
  <span m="669340">that</span> <span m="669480">it&rsquo;s</span> <span m="669720">problematic</span>
  <span m="670460">to</span> <span m="670590">alter</span> <span m="670910">the</span>
  <span m="671130">ISA</span> <span m="671650">to</span> <span m="671810">improve</span>
  <span m="672260">the</span> <span m="672350">throughput</span> <span m="672940">of</span>
  <span m="673170">pipelined</span> <span m="673760">execution.</span></p><p><span
  m="675930">ISAs</span> <span m="676550">outlive</span> <span m="677030">implementations,</span>
  <span m="677970">so</span> <span m="678140">it&rsquo;s</span> <span m="678270">best</span>
  <span m="678600">not</span> <span m="678930">to</span> <span m="679050">change</span>
  <span m="679520">the</span> <span m="679670">execution</span> <span m="680270">semantics</span>
  <span m="680820">to</span> <span m="680930">deal</span> <span m="681120">with</span>
  <span m="681300">performance</span> <span m="681890">issues</span> <span m="682430">created</span>
  <span m="683010">by</span> <span m="683230">a</span> <span m="683290">particular</span>
  <span m="684000">implementation.</span></p>
type: course
uid: 224ab9265fbf09c00c9e08e0e19df436

---
None