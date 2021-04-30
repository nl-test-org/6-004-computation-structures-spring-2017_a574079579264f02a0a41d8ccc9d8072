---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 2IQxigpPMns
  parent_uid: f5fb1cb99b63bc84ca0d402d2a2ccf09
  title: Video-YouTube-Stream
  type: Video
  uid: 3b8cdbbeb925509e9f577a2e33eaf007
- id: 3Play-3Play YouTube id-Stream
  media_location: 2IQxigpPMns
  parent_uid: f5fb1cb99b63bc84ca0d402d2a2ccf09
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 34b6e8fcb921dec150e60289af6db69f
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/2IQxigpPMns/default.jpg
  parent_uid: f5fb1cb99b63bc84ca0d402d2a2ccf09
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: db97bcc2ff9e5ba7841771b095b87559
- id: 2IQxigpPMns.srt
  parent_uid: f5fb1cb99b63bc84ca0d402d2a2ccf09
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v12/worked-example-error-correction/2IQxigpPMns.srt
  title: 3play caption file
  type: null
  uid: f0ea81fc21d5d4e8b2ecf91992b5ade1
- id: 2IQxigpPMns.pdf
  parent_uid: f5fb1cb99b63bc84ca0d402d2a2ccf09
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v12/worked-example-error-correction/2IQxigpPMns.pdf
  title: 3play pdf file
  type: null
  uid: 9f73ae0d0d71fb4c2146806c438bb641
- id: Caption-3Play YouTube id-SRT
  parent_uid: f5fb1cb99b63bc84ca0d402d2a2ccf09
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: d86698624e106311c90bd7410539b8fd
- id: Transcript-3Play YouTube id-PDF
  parent_uid: f5fb1cb99b63bc84ca0d402d2a2ccf09
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 3873c7e971cafa64aa1788bef5e5a283
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_01-02-12-05_300k.mp4
  parent_uid: f5fb1cb99b63bc84ca0d402d2a2ccf09
  title: Video-Internet Archive-MP4
  type: Video
  uid: b7b6d6014bcd13395d91a97701a6cefe
inline_embed_id: 81963740errorcorrection68729234
layout: video
order_index: null
parent_uid: 4405e1adee4c3bf77a4cc2b35d6760ff
related_resources_text: ''
short_url: worked-example-error-correction
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c1/c1s2/c1s2v12/worked-example-error-correction
template_type: Embed
title: 'Worked Example: Error Correction'
transcript: <p><span m="700">We</span> <span m="1540">will</span> <span m="1690">now</span>
  <span m="1980">review</span> <span m="2360">a</span> <span m="2400">problem</span>
  <span m="2960">on</span> <span m="3190">error</span> <span m="3500">correction</span>
  <span m="4150">and</span> <span m="4340">detection</span> <span m="5220">in</span>
  <span m="5560">order</span> <span m="5890">to</span> <span m="5990">better</span>
  <span m="6340">understand</span> <span m="7100">how</span> <span m="7310">the</span>
  <span m="7390">selected</span> <span m="8010">encoding</span> <span m="8540">of</span>
  <span m="8690">a</span> <span m="8730">message</span> <span m="9480">can</span>
  <span m="9810">help</span> <span m="10100">both</span> <span m="10360">detect</span>
  <span m="10920">and</span> <span m="11110">correct</span> <span m="11670">transmission</span>
  <span m="12470">errors.</span></p><p><span m="14440">In</span> <span m="14610">this</span>
  <span m="14850">problem</span> <span m="15440">messages</span> <span m="16010">consist</span>
  <span m="16560">of</span> <span m="16770">9</span> <span m="16960">data</span> <span
  m="17360">bits</span> <span m="17810">and</span> <span m="18010">7</span> <span
  m="18210">parity</span> <span m="18890">bits.</span></p><p><span m="20130">Each</span>
  <span m="20390">Dij</span> <span m="20960">represents</span> <span m="21870">a</span>
  <span m="21920">data</span> <span m="22290">bit</span> <span m="22560">which</span>
  <span m="22800">belongs</span> <span m="23300">to</span> <span m="23510">row</span>
  <span m="23760">i</span> <span m="24100">and</span> <span m="24310">column</span>
  <span m="24750">j.</span></p><p><span m="26200">The</span> <span m="26360">Pij</span>
  <span m="26760">bits</span> <span m="27440">are</span> <span m="27630">used</span>
  <span m="28000">to</span> <span m="28070">make</span> <span m="28320">the</span>
  <span m="28410">parity</span> <span m="29000">of</span> <span m="29160">each</span>
  <span m="29500">row</span> <span m="29880">and</span> <span m="30020">column</span>
  <span m="30530">be</span> <span m="30770">odd.</span></p><p><span m="32189">The</span>
  <span m="32439">Pxx</span> <span m="32860">box,</span> <span m="33610">which</span>
  <span m="33860">is</span> <span m="34030">in</span> <span m="34140">the</span> <span
  m="34220">bottom</span> <span m="34700">right</span> <span m="34910">corner,</span>
  <span m="35660">is</span> <span m="36050">used</span> <span m="36350">to</span>
  <span m="36430">make</span> <span m="36650">the</span> <span m="36750">parity</span>
  <span m="37310">of</span> <span m="37390">the</span> <span m="37490">entire</span>
  <span m="38080">message</span> <span m="38570">odd.</span></p><p><span m="39400">In</span>
  <span m="39540">other</span> <span m="39770">words,</span> <span m="40170">it</span>
  <span m="40310">makes</span> <span m="40560">the</span> <span m="40630">total</span>
  <span m="41070">number</span> <span m="41440">of</span> <span m="41560">ones</span>
  <span m="42120">be</span> <span m="42360">odd.</span></p><p><span m="44640">The</span>
  <span m="44730">first</span> <span m="45130">question</span> <span m="45520">we</span>
  <span m="45630">want</span> <span m="45900">to</span> <span m="46000">ask</span>
  <span m="46360">ourselves</span> <span m="47160">is</span> <span m="47470">what</span>
  <span m="47650">is</span> <span m="47790">the</span> <span m="47880">minimum</span>
  <span m="48340">Hamming</span> <span m="48750">Distance</span> <span m="49310">between</span>
  <span m="49770">valid</span> <span m="50180">code</span> <span m="50520">words</span>
  <span m="50930">using</span> <span m="51290">this</span> <span m="51520">encoding?</span></p><p><span
  m="52910">In</span> <span m="53060">order</span> <span m="53340">to</span> <span
  m="53420">figure</span> <span m="53800">that</span> <span m="54010">out,</span>
  <span m="54550">we</span> <span m="54850">need</span> <span m="55030">to</span>
  <span m="55140">think</span> <span m="55420">about</span> <span m="55750">how</span>
  <span m="55960">many</span> <span m="56220">bits</span> <span m="56530">of</span>
  <span m="56620">the</span> <span m="56710">encoding</span> <span m="57250">are</span>
  <span m="57390">changed</span> <span m="58120">if</span> <span m="58350">I</span>
  <span m="58430">want</span> <span m="58690">to</span> <span m="58790">change</span>
  <span m="59190">one</span> <span m="59400">of</span> <span m="59510">the</span>
  <span m="59590">data</span> <span m="59920">bits.</span></p><p><span m="61320">The</span>
  <span m="61480">easiest</span> <span m="61810">way</span> <span m="61960">to</span>
  <span m="62050">see</span> <span m="62340">this</span> <span m="62670">is</span>
  <span m="62860">through</span> <span m="63100">an</span> <span m="63190">example.</span></p><p><span
  m="64480">Suppose</span> <span m="64890">that</span> <span m="65000">I</span> <span
  m="65069">want</span> <span m="65310">to</span> <span m="65370">change</span> <span
  m="65890">D01</span> <span m="66500">from</span> <span m="67220">a</span> <span
  m="67450">0</span> <span m="67560">to</span> <span m="67860">a</span> <span m="67960">1.</span></p><p><span
  m="67990">The</span> <span m="68580">first</span> <span m="69370">thing</span> <span
  m="69520">changing</span> <span m="70150">is</span> <span m="70330">my</span> <span
  m="70500">data</span> <span m="70820">bit</span> <span m="71020">itself.</span></p><p><span
  m="72280">Then</span> <span m="72820">P0x</span> <span m="73340">would</span> <span
  m="73980">get</span> <span m="74200">flipped</span> <span m="74720">because</span>
  <span m="75040">I</span> <span m="75140">just</span> <span m="75450">added</span>
  <span m="75830">another</span> <span m="76310">1</span> <span m="76420">to</span>
  <span m="76630">my</span> <span m="76850">row</span> <span m="77380">which</span>
  <span m="77760">means</span> <span m="78020">that</span> <span m="78120">I</span>
  <span m="78220">need</span> <span m="78410">to</span> <span m="78520">flip</span>
  <span m="78850">the</span> <span m="78950">parity</span> <span m="79460">bit</span>
  <span m="79780">in</span> <span m="79970">order</span> <span m="80260">for</span>
  <span m="80440">the</span> <span m="80540">total</span> <span m="80960">number</span>
  <span m="81320">of</span> <span m="81500">1's</span> <span m="81800">in</span> <span
  m="81900">my</span> <span m="82120">row</span> <span m="82360">to</span> <span m="82530">remain</span>
  <span m="83040">odd.</span></p><p><span m="84560">The</span> <span m="84660">next</span>
  <span m="85060">change</span> <span m="85720">is</span> <span m="86180">that</span>
  <span m="86640">Px1</span> <span m="86840">needs</span> <span m="87240">to</span>
  <span m="87350">get</span> <span m="87560">flipped</span> <span m="88090">in</span>
  <span m="88270">order</span> <span m="88540">to</span> <span m="88690">maintain</span>
  <span m="89180">an</span> <span m="89340">odd</span> <span m="89590">parity</span>
  <span m="90170">in</span> <span m="90320">my</span> <span m="90490">column.</span></p><p><span
  m="91910">So</span> <span m="92150">far,</span> <span m="92630">3</span> <span m="92770">entries</span>
  <span m="93390">have</span> <span m="93580">changed</span> <span m="94130">which</span>
  <span m="94330">implies</span> <span m="94810">that</span> <span m="94950">the</span>
  <span m="95040">parity</span> <span m="95580">of</span> <span m="95640">the</span>
  <span m="95710">entire</span> <span m="96210">message</span> <span m="96690">flipped.</span></p><p><span
  m="97710">In</span> <span m="97840">order</span> <span m="98130">to</span> <span
  m="98230">keep</span> <span m="98520">the</span> <span m="98620">parity</span> <span
  m="99170">of</span> <span m="99250">the</span> <span m="99320">entire</span> <span
  m="99760">message</span> <span m="100230">odd,</span> <span m="101010">Pxx</span>
  <span m="101820">needs</span> <span m="102330">to</span> <span m="102420">be</span>
  <span m="102580">flipped</span> <span m="102950">as</span> <span m="103130">well</span>
  <span m="103660">so</span> <span m="103980">that</span> <span m="104170">there</span>
  <span m="104420">are</span> <span m="104500">a</span> <span m="104530">total</span>
  <span m="105040">of</span> <span m="105160">4</span> <span m="105380">entries</span>
  <span m="106060">being</span> <span m="106380">flipped</span> <span m="107020">which</span>
  <span m="107350">will</span> <span m="107470">cause</span> <span m="107800">the</span>
  <span m="107940">odd</span> <span m="108230">parity</span> <span m="108750">of</span>
  <span m="108830">the</span> <span m="108910">entire</span> <span m="109380">message</span>
  <span m="109960">to</span> <span m="110080">remain</span> <span m="110640">unchanged.</span></p><p><span
  m="112830">This</span> <span m="113080">means</span> <span m="113450">that</span>
  <span m="113580">our</span> <span m="113660">minimum</span> <span m="114140">hamming</span>
  <span m="114500">distance</span> <span m="114990">for</span> <span m="115120">this</span>
  <span m="115350">encoding</span> <span m="116220">equals</span> <span m="116860">4</span>
  <span m="117270">because</span> <span m="118020">any</span> <span m="118260">time</span>
  <span m="118590">we</span> <span m="118690">flip</span> <span m="119050">a</span>
  <span m="119100">data</span> <span m="119450">bit,</span> <span m="119870">a</span>
  <span m="120020">total</span> <span m="120440">of</span> <span m="120620">4</span>
  <span m="120810">entries</span> <span m="121540">need</span> <span m="121720">to</span>
  <span m="121850">change</span> <span m="122590">to</span> <span m="122850">maintain</span>
  <span m="123440">our</span> <span m="123640">encoding.</span></p><p><span m="125080">We</span>
  <span m="125210">know</span> <span m="125450">that</span> <span m="125770">to</span>
  <span m="125910">detect</span> <span m="126420">an</span> <span m="126580">E-bit</span>
  <span m="127010">error,</span> <span m="127580">the</span> <span m="127870">hamming</span>
  <span m="128280">distance</span> <span m="128690">(HD)</span> <span m="128820">has</span>
  <span m="129000">to</span> <span m="129090">be</span> <span m="129229">greater</span>
  <span m="129660">than</span> <span m="129889">E,</span> <span m="130410">or</span>
  <span m="130770">in</span> <span m="130900">other</span> <span m="131150">words,</span>
  <span m="131830">the</span> <span m="132780">HD</span> <span m="134100">&gt;=</span>
  <span m="134350">E</span> <span m="134790">+</span> <span m="135140">1.</span></p><p><span
  m="135910">So</span> <span m="136090">to</span> <span m="136260">detect</span> <span
  m="136770">a</span> <span m="136930">1-bit</span> <span m="137300">error,</span>
  <span m="137800">one</span> <span m="138410">needs</span> <span m="139180">a</span>
  <span m="139380">HD</span> <span m="140420">&gt;=</span> <span m="140710">2.</span></p><p><span
  m="141770">We</span> <span m="141930">also</span> <span m="142370">know</span> <span
  m="142680">that</span> <span m="142850">to</span> <span m="142980">correct</span>
  <span m="143560">an</span> <span m="143720">E-bit</span> <span m="144140">error,</span>
  <span m="145310">the</span> <span m="146350">HD</span> <span m="146900">&gt;</span>
  <span m="147090">2E,</span> <span m="147810">or</span> <span m="149060">the</span>
  <span m="149910">HD</span> <span m="151050">&gt;=</span> <span m="151990">2E</span>
  <span m="152360">+</span> <span m="152520">1.</span></p><p><span m="153460">So</span>
  <span m="153620">to</span> <span m="153770">correct</span> <span m="154300">a</span>
  <span m="154510">1-bit</span> <span m="154850">error,</span> <span m="155350">one</span>
  <span m="155590">needs</span> <span m="155820">to</span> <span m="156080">have</span>
  <span m="156740">a</span> <span m="157140">HD</span> <span m="158110">&gt;=</span>
  <span m="158320">3.</span></p><p><span m="158350">For</span> <span m="159050">this</span>
  <span m="159880">encoding,</span> <span m="160680">since</span> <span m="161110">our</span>
  <span m="161210">hamming</span> <span m="161630">distance</span> <span m="162090">equals</span>
  <span m="162510">4,</span> <span m="162910">that</span> <span m="163460">means</span>
  <span m="163760">we</span> <span m="163850">should</span> <span m="164050">be</span>
  <span m="164270">able</span> <span m="164680">to</span> <span m="164880">both</span>
  <span m="165210">detect</span> <span m="165880">and</span> <span m="166160">correct</span>
  <span m="166920">1-bit</span> <span m="167620">errors.</span></p><p><span m="171820">Taking</span>
  <span m="172210">a</span> <span m="172280">look</span> <span m="172560">at</span>
  <span m="172680">this</span> <span m="172900">message,</span> <span m="173600">if</span>
  <span m="173830">we</span> <span m="173930">check</span> <span m="174240">the</span>
  <span m="174350">parity</span> <span m="174980">of</span> <span m="175100">each</span>
  <span m="175520">row,</span> <span m="176160">column,</span> <span m="177120">and</span>
  <span m="177400">full</span> <span m="177730">message,</span> <span m="178520">we</span>
  <span m="178790">see</span> <span m="179050">that</span> <span m="179260">in</span>
  <span m="179410">all</span> <span m="179670">cases</span> <span m="180320">our</span>
  <span m="180460">parity</span> <span m="181020">is</span> <span m="181180">odd.</span></p><p><span
  m="182230">Since</span> <span m="182500">odd</span> <span m="182740">parity</span>
  <span m="183320">indicates</span> <span m="183910">a</span> <span m="183950">valid</span>
  <span m="184360">message,</span> <span m="185130">there</span> <span m="185480">are</span>
  <span m="185510">no</span> <span m="185860">errors</span> <span m="186510">in</span>
  <span m="186740">this</span> <span m="186950">message.</span></p><p><span m="189730">Looking</span>
  <span m="190040">at</span> <span m="190190">this</span> <span m="190470">message</span>
  <span m="191260">we</span> <span m="191580">see</span> <span m="191820">that</span>
  <span m="192050">all</span> <span m="192320">the</span> <span m="192460">row</span>
  <span m="192720">parities</span> <span m="193340">are</span> <span m="193500">odd,</span>
  <span m="194100">but</span> <span m="194450">the</span> <span m="194510">parity</span>
  <span m="195100">of</span> <span m="195200">column</span> <span m="195800">1</span>
  <span m="196010">is</span> <span m="196330">even.</span></p><p><span m="197300">This</span>
  <span m="197550">means</span> <span m="197880">that</span> <span m="198040">there</span>
  <span m="198250">is</span> <span m="198390">an</span> <span m="198500">error</span>
  <span m="198950">in</span> <span m="199080">column</span> <span m="199850">1.</span></p><p><span
  m="200390">However,</span> <span m="201010">since</span> <span m="201400">there</span>
  <span m="201540">were</span> <span m="201700">no</span> <span m="202010">errors</span>
  <span m="202530">in</span> <span m="202610">the</span> <span m="202690">parity</span>
  <span m="203270">of</span> <span m="203380">the</span> <span m="203500">rows,</span>
  <span m="204180">this</span> <span m="204530">means</span> <span m="204830">that</span>
  <span m="205000">the</span> <span m="205080">bit</span> <span m="205330">in</span>
  <span m="205510">error</span> <span m="206010">is</span> <span m="206200">the</span>
  <span m="206280">parity</span> <span m="206790">bit</span> <span m="207070">itself.</span></p><p><span
  m="208180">If</span> <span m="208390">we</span> <span m="208530">flip</span> <span
  m="208990">Px1</span> <span m="209480">from</span> <span m="210200">a</span> <span
  m="210460">0</span> <span m="210530">to</span> <span m="210850">a</span> <span m="211030">1</span>
  <span m="211430">we</span> <span m="211800">now</span> <span m="212060">have</span>
  <span m="212320">a</span> <span m="212370">valid</span> <span m="212810">message</span>
  <span m="213290">again.</span></p><p><span m="215610">Looking</span> <span m="215940">at</span>
  <span m="216090">the</span> <span m="216160">parity</span> <span m="216810">of</span>
  <span m="216980">each</span> <span m="217350">row</span> <span m="217630">and</span>
  <span m="217760">column</span> <span m="218260">in</span> <span m="218380">this</span>
  <span m="218650">message,</span> <span m="219420">we</span> <span m="219710">see</span>
  <span m="219950">that</span> <span m="220500">row</span> <span m="221070">0</span>
  <span m="221120">has</span> <span m="221330">an</span> <span m="221460">even</span>
  <span m="221820">parity,</span> <span m="222720">and</span> <span m="223120">column</span>
  <span m="223760">0</span> <span m="224000">has</span> <span m="224280">an</span>
  <span m="224400">even</span> <span m="224700">parity.</span></p><p><span m="225800">This</span>
  <span m="226020">means</span> <span m="226430">that</span> <span m="226570">the</span>
  <span m="226670">data</span> <span m="227040">bit</span> <span m="227410">at</span>
  <span m="227640">row</span> <span m="228060">0,</span> <span m="228310">column</span>
  <span m="229010">0</span> <span m="229320">is</span> <span m="229630">wrong.</span></p><p><span
  m="230770">If</span> <span m="230930">we</span> <span m="231020">flip</span> <span
  m="231390">this</span> <span m="231660">bit,</span> <span m="232160">we</span> <span
  m="232490">now</span> <span m="232750">see</span> <span m="233070">that</span> <span
  m="233290">all</span> <span m="233590">of</span> <span m="233700">our</span> <span
  m="233900">row</span> <span m="234270">and</span> <span m="234390">column</span>
  <span m="234800">parities</span> <span m="235400">are</span> <span m="235540">correct,</span>
  <span m="236440">and</span> <span m="236830">our</span> <span m="236950">total</span>
  <span m="237390">message</span> <span m="237800">parity</span> <span m="238370">is</span>
  <span m="238510">correct</span> <span m="238920">as</span> <span m="239080">well,</span>
  <span m="239670">so</span> <span m="240280">we</span> <span m="240410">have</span>
  <span m="240590">restored</span> <span m="241120">our</span> <span m="241220">message</span>
  <span m="241810">by</span> <span m="242000">identifying</span> <span m="242910">the</span>
  <span m="243060">bit</span> <span m="243350">in</span> <span m="243560">error.</span></p><p><span
  m="246480">In</span> <span m="246640">this</span> <span m="246850">example,</span>
  <span m="247740">all</span> <span m="248150">of</span> <span m="248260">the</span>
  <span m="248410">row</span> <span m="248620">parities</span> <span m="249330">and</span>
  <span m="249470">column</span> <span m="249920">parities</span> <span m="250510">are</span>
  <span m="250690">odd.</span></p><p><span m="251330">However,</span> <span m="251960">the</span>
  <span m="252080">parity</span> <span m="252560">of</span> <span m="252650">the</span>
  <span m="252720">entire</span> <span m="253180">message</span> <span m="253750">is</span>
  <span m="253950">even.</span></p><p><span m="254950">This</span> <span m="255170">means</span>
  <span m="255490">that</span> <span m="255650">the</span> <span m="255740">bit</span>
  <span m="255970">in</span> <span m="256120">error</span> <span m="256529">in</span>
  <span m="256709">this</span> <span m="256940">message</span> <span m="257579">is</span>
  <span m="257950">the</span> <span m="258260">Pxx</span> <span m="258730">bit</span>
  <span m="259180">itself.</span></p><p><span m="260430">Flipping</span> <span m="260800">that</span>
  <span m="261000">bottom</span> <span m="261390">right</span> <span m="261649">bit</span>
  <span m="262000">results</span> <span m="262540">in</span> <span m="262640">a</span>
  <span m="262670">valid</span> <span m="263100">message</span> <span m="263580">once</span>
  <span m="263910">again.</span></p><p><span m="266220">Now</span> <span m="266400">let's</span>
  <span m="266620">go</span> <span m="266780">back</span> <span m="267030">to</span>
  <span m="267140">our</span> <span m="267430">original</span> <span m="267860">valid</span>
  <span m="268230">message</span> <span m="268840">and</span> <span m="269050">see</span>
  <span m="269260">if</span> <span m="269390">we</span> <span m="269510">can</span>
  <span m="269690">correct</span> <span m="270490">2-bit</span> <span m="270780">errors.</span></p><p><span
  m="271840">Suppose</span> <span m="272280">we</span> <span m="272390">flip</span>
  <span m="272750">D11</span> <span m="273260">to</span> <span m="274160">0</span>
  <span m="274490">and</span> <span m="274790">D22</span> <span m="275040">to</span>
  <span m="275410">1</span> <span m="275580">to</span> <span m="276310">create</span>
  <span m="277500">a</span> <span m="277580">2-bit</span> <span m="277840">error.</span></p><p><span
  m="278970">Now</span> <span m="279320">when</span> <span m="279500">we</span> <span
  m="279670">look</span> <span m="279900">at</span> <span m="279990">the</span> <span
  m="280080">parity</span> <span m="280580">of</span> <span m="280680">each</span>
  <span m="280980">row,</span> <span m="281560">we</span> <span m="281850">find</span>
  <span m="282190">that</span> <span m="282390">both</span> <span m="283100">row</span>
  <span m="283750">1</span> <span m="284150">and</span> <span m="284650">2</span>
  <span m="285190">have</span> <span m="285740">a</span> <span m="285800">parity</span>
  <span m="286350">error.</span></p><p><span m="287030">Similarly,</span> <span m="287900">columns</span>
  <span m="288550">1</span> <span m="288580">and</span> <span m="288980">2</span>
  <span m="289140">have</span> <span m="289490">a</span> <span m="289530">parity</span>
  <span m="290090">error.</span></p><p><span m="290910">The</span> <span m="290990">total</span>
  <span m="291380">message</span> <span m="291820">parity</span> <span m="292440">remains</span>
  <span m="292930">correct.</span></p><p><span m="294220">Given</span> <span m="294540">this</span>
  <span m="294730">information,</span> <span m="295730">we</span> <span m="296110">know</span>
  <span m="296310">that</span> <span m="296460">an</span> <span m="296640">error</span>
  <span m="297100">occurred</span> <span m="297430">in</span> <span m="297510">the</span>
  <span m="297610">transmission</span> <span m="298360">of</span> <span m="298490">this</span>
  <span m="298700">message,</span> <span m="299300">but</span> <span m="299450">we</span>
  <span m="299550">cannot</span> <span m="299890">identify</span> <span m="300820">exactly</span>
  <span m="301430">which</span> <span m="301720">bits</span> <span m="302010">are</span>
  <span m="302210">in</span> <span m="302330">error</span> <span m="302870">because</span>
  <span m="303370">there</span> <span m="303510">is</span> <span m="303630">more</span>
  <span m="303890">than</span> <span m="304010">one</span> <span m="304240">possible</span>
  <span m="304810">way</span> <span m="305090">to</span> <span m="305320">alter</span>
  <span m="305740">two</span> <span m="306000">bits</span> <span m="306450">and</span>
  <span m="306660">arrive</span> <span m="306940">at</span> <span m="307010">a</span>
  <span m="307050">valid</span> <span m="307450">message.</span></p><p><span m="309510">This</span>
  <span m="309700">demonstrates</span> <span m="310730">that</span> <span m="311030">we</span>
  <span m="311140">can</span> <span m="311320">detect</span> <span m="311900">a</span>
  <span m="312100">2-bit</span> <span m="312440">error,</span> <span m="312940">but</span>
  <span m="313240">we</span> <span m="313330">can't</span> <span m="313640">correct</span>
  <span m="314470">a</span> <span m="314530">2-bit</span> <span m="314740">error.</span></p><p><span
  m="315720">Going</span> <span m="316010">back</span> <span m="316280">to</span>
  <span m="316420">our</span> <span m="316660">original</span> <span m="317080">claims</span>
  <span m="317620">about</span> <span m="317940">hamming</span> <span m="318310">distances,</span>
  <span m="319230">this</span> <span m="319580">is</span> <span m="319750">in</span>
  <span m="319890">line</span> <span m="320250">with</span> <span m="320440">our</span>
  <span m="320590">expectations.</span></p><p><span m="322340">If</span> <span m="322660">E=2,</span>
  <span m="323390">meaning</span> <span m="324190">that</span> <span m="324330">we</span>
  <span m="324450">want</span> <span m="324740">to</span> <span m="324810">detect</span>
  <span m="325530">a</span> <span m="325630">2-bit</span> <span m="325870">error,</span>
  <span m="326690">then</span> <span m="327820">the</span> <span m="328380">HD</span>
  <span m="329290">&gt;=</span> <span m="329570">E+1</span> <span m="330170">which</span>
  <span m="330830">equals</span> <span m="331170">3.</span></p><p><span m="331200">To</span>
  <span m="331920">correct</span> <span m="333130">a</span> <span m="333210">2-bit</span>
  <span m="333400">error,</span> <span m="334210">the</span> <span m="335250">HD</span>
  <span m="336460">&gt;=</span> <span m="336820">2E+1</span> <span m="337700">which</span>
  <span m="338440">equals</span> <span m="338940">5.</span></p><p><span m="340040">Since</span>
  <span m="340290">our</span> <span m="340370">hamming</span> <span m="340730">distance</span>
  <span m="341210">in</span> <span m="341330">this</span> <span m="341530">problem</span>
  <span m="341940">is</span> <span m="342110">4,</span> <span m="342560">we</span>
  <span m="343070">can</span> <span m="343250">only</span> <span m="343630">detect</span>
  <span m="344320">2-bit</span> <span m="344560">errors,</span> <span m="345140">but</span>
  <span m="345370">not</span> <span m="345660">correct</span> <span m="346110">them.</span></p>
type: course
uid: f5fb1cb99b63bc84ca0d402d2a2ccf09

---
None