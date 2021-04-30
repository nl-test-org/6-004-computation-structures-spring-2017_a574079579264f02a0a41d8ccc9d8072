---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: v2X-sTKCVMs
  parent_uid: fab1783eebc56acbb15298984c18f0ec
  title: Video-YouTube-Stream
  type: Video
  uid: 63b4ce62a95b7240413d543846934568
- id: 3Play-3Play YouTube id-Stream
  media_location: v2X-sTKCVMs
  parent_uid: fab1783eebc56acbb15298984c18f0ec
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 115bfb7d60e159246ed1328a00d5c0fe
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/v2X-sTKCVMs/default.jpg
  parent_uid: fab1783eebc56acbb15298984c18f0ec
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 1e447a77290bbb66ac9cb66325a2ddcd
- id: v2X-sTKCVMs.srt
  parent_uid: fab1783eebc56acbb15298984c18f0ec
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v11/caches/v2X-sTKCVMs.srt
  title: 3play caption file
  type: null
  uid: c9d253407dea5b808a76f2cd26ee1d1f
- id: v2X-sTKCVMs.pdf
  parent_uid: fab1783eebc56acbb15298984c18f0ec
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v11/caches/v2X-sTKCVMs.pdf
  title: 3play pdf file
  type: null
  uid: 97832fceb16de4cf0fdc46ac34f34161
- id: Caption-3Play YouTube id-SRT
  parent_uid: fab1783eebc56acbb15298984c18f0ec
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 2c226d28a4d4469fe6a6200fa52b04d3
- id: Transcript-3Play YouTube id-PDF
  parent_uid: fab1783eebc56acbb15298984c18f0ec
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: a7b1b7a31d5c69070609def7f32f06e4
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_14-02-11-02_300k.mp4
  parent_uid: fab1783eebc56acbb15298984c18f0ec
  title: Video-Internet Archive-MP4
  type: Video
  uid: 4c122a6bf5f73e5e26ca6e8a0f22ac88
inline_embed_id: 18220975caches29876231
layout: video
order_index: null
parent_uid: 9f6575a722442cd9719b73804b20a778
related_resources_text: ''
short_url: caches
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v11/caches
template_type: Embed
title: 'Worked Example: Caches'
transcript: <p><span m="530">Consider</span> <span m="970">this</span> <span m="1411">2-way</span>
  <span m="1852">set</span> <span m="2293">associative</span> <span m="2733">cache</span>
  <span m="3174">to</span> <span m="3615">be</span> <span m="4056">used</span> <span
  m="4496">with</span> <span m="4937">our</span> <span m="5378">beta</span> <span
  m="5819">processor.</span></p><p><span m="6260">Each</span> <span m="6746">line</span>
  <span m="7232">holds</span> <span m="7719">a</span> <span m="8205">single</span>
  <span m="8692">32</span> <span m="9178">bit</span> <span m="9665">data</span> <span
  m="10151">word</span> <span m="10638">together</span> <span m="11124">with</span>
  <span m="11611">a</span> <span m="12097">valid</span> <span m="12584">bit</span>
  <span m="13070">and</span> <span m="13557">a</span> <span m="14043">tag.</span></p><p><span
  m="14530">Our</span> <span m="15040">beta</span> <span m="15550">uses</span> <span
  m="16060">32</span> <span m="16570">bit</span> <span m="17080">addresses.</span></p><p><span
  m="17590">We</span> <span m="17897">want</span> <span m="18204">to</span> <span
  m="18511">determine</span> <span m="18818">which</span> <span m="19125">address</span>
  <span m="19432">bits</span> <span m="19739">should</span> <span m="20046">be</span>
  <span m="20353">used</span> <span m="20660">for</span> <span m="20967">the</span>
  <span m="21274">cache</span> <span m="21581">index</span> <span m="21888">and</span>
  <span m="22195">which</span> <span m="22502">should</span> <span m="22810">be</span>
  <span m="23277">used</span> <span m="23745">for</span> <span m="24212">the</span>
  <span m="24680">tag</span> <span m="25147">so</span> <span m="25615">as</span> <span
  m="26082">to</span> <span m="26550">ensure</span> <span m="27017">best</span> <span
  m="27485">cache</span> <span m="27952">performance.</span></p><p><span m="28420">The</span>
  <span m="28753">bottom</span> <span m="29086">two</span> <span m="29420">bits</span>
  <span m="29753">of</span> <span m="30087">the</span> <span m="30420">address</span>
  <span m="30754">are</span> <span m="31087">always</span> <span m="31421">assumed</span>
  <span m="31754">to</span> <span m="32088">be</span> <span m="32421">00</span> <span
  m="32755">for</span> <span m="33088">word</span> <span m="33422">alignment</span>
  <span m="33755">since</span> <span m="34089">are</span> <span m="34500">addresses</span>
  <span m="34912">are</span> <span m="35324">in</span> <span m="35736">bytes</span>
  <span m="36147">but</span> <span m="36559">our</span> <span m="36971">data</span>
  <span m="37383">is</span> <span m="37794">in</span> <span m="38206">words</span>
  <span m="38618">of</span> <span m="39030">32</span> <span m="39441">bits</span>
  <span m="39853">or</span> <span m="40265">4</span> <span m="40677">bytes.</span></p><p><span
  m="41089">Our</span> <span m="41445">cache</span> <span m="41801">has</span> <span
  m="42157">8</span> <span m="42513">lines</span> <span m="42869">in</span> <span
  m="43225">it,</span> <span m="43581">so</span> <span m="43937">this</span> <span
  m="44294">means</span> <span m="44650">that</span> <span m="45006">our</span> <span
  m="45362">index</span> <span m="45718">must</span> <span m="46074">be</span> <span
  m="46430">3</span> <span m="46786">bits</span> <span m="47142">wide.</span></p><p><span
  m="47499">The</span> <span m="47763">bits</span> <span m="48027">that</span> <span
  m="48291">we</span> <span m="48555">want</span> <span m="48819">to</span> <span
  m="49083">use</span> <span m="49347">for</span> <span m="49611">the</span> <span
  m="49876">index</span> <span m="50140">are</span> <span m="50404">the</span> <span
  m="50668">next</span> <span m="50932">least</span> <span m="51196">significant</span>
  <span m="51460">bits</span> <span m="51724">which</span> <span m="51989">are</span>
  <span m="52806">address</span> <span m="53624">bits</span> <span m="54442">[4:2].</span></p><p><span
  m="55260">The</span> <span m="55526">reason</span> <span m="55793">that</span> <span
  m="56060">we</span> <span m="56327">want</span> <span m="56593">to</span> <span
  m="56860">make</span> <span m="57127">these</span> <span m="57394">bits</span> <span
  m="57661">be</span> <span m="57927">part</span> <span m="58194">of</span> <span
  m="58461">the</span> <span m="58728">index</span> <span m="58995">instead</span>
  <span m="59261">of</span> <span m="59528">the</span> <span m="59795">tag</span>
  <span m="60062">is</span> <span m="60329">because</span> <span m="60989">of</span>
  <span m="61649">locality.</span></p><p><span m="62309">The</span> <span m="62639">idea</span>
  <span m="62970">is</span> <span m="63300">that</span> <span m="63631">instructions</span>
  <span m="63962">or</span> <span m="64292">data</span> <span m="64623">that</span>
  <span m="64954">are</span> <span m="65284">near</span> <span m="65615">each</span>
  <span m="65946">other</span> <span m="66276">in</span> <span m="66607">memory</span>
  <span m="66938">are</span> <span m="67268">more</span> <span m="67599">likely</span>
  <span m="67930">to</span> <span m="68295">be</span> <span m="68660">accessed</span>
  <span m="69025">around</span> <span m="69390">the</span> <span m="69755">same</span>
  <span m="70120">time</span> <span m="70485">than</span> <span m="70850">instructions</span>
  <span m="71215">or</span> <span m="71580">data</span> <span m="71945">that</span>
  <span m="72310">reside</span> <span m="72675">in</span> <span m="73040">a</span>
  <span m="73405">different</span> <span m="73770">part</span> <span m="74135">of</span>
  <span m="74500">memory.</span></p><p><span m="75500">So</span> <span m="75905">if</span>
  <span m="76310">for</span> <span m="76715">example,</span> <span m="77120">our</span>
  <span m="77525">instruction</span> <span m="77930">comes</span> <span m="78335">from</span>
  <span m="78740">address</span> <span m="79145">0x1000,</span> <span m="79550">it</span>
  <span m="79955">is</span> <span m="80360">fairly</span> <span m="80765">likely</span>
  <span m="81170">that</span> <span m="81575">we</span> <span m="81980">will</span>
  <span m="82585">also</span> <span m="83190">access</span> <span m="83796">the</span>
  <span m="84401">next</span> <span m="85007">instruction</span> <span m="85612">which</span>
  <span m="86218">is</span> <span m="86823">at</span> <span m="87429">address</span>
  <span m="88034">0x1004.</span></p><p><span m="88640">With</span> <span m="88966">this</span>
  <span m="89293">scheme</span> <span m="89620">the</span> <span m="89947">index</span>
  <span m="90274">of</span> <span m="90601">the</span> <span m="90927">first</span>
  <span m="91254">instruction</span> <span m="91581">would</span> <span m="91908">map</span>
  <span m="92235">to</span> <span m="92562">line</span> <span m="92888">0</span> <span
  m="93215">of</span> <span m="93542">the</span> <span m="93869">cache</span> <span
  m="94196">while</span> <span m="94523">the</span> <span m="94850">next</span> <span
  m="95175">instruction</span> <span m="95500">would</span> <span m="95825">map</span>
  <span m="96151">to</span> <span m="96476">line</span> <span m="96801">1</span> <span
  m="97127">of</span> <span m="97452">the</span> <span m="97777">cache</span> <span
  m="98102">so</span> <span m="98428">they</span> <span m="98753">would</span> <span
  m="99078">not</span> <span m="99404">cause</span> <span m="99729">a</span> <span
  m="100054">collision</span> <span m="100380">or</span> <span m="100915">a</span>
  <span m="101450">miss</span> <span m="101985">in</span> <span m="102520">the</span>
  <span m="103055">cache.</span></p><p><span m="103590">This</span> <span m="103967">leaves</span>
  <span m="104345">the</span> <span m="104723">higher</span> <span m="105101">order</span>
  <span m="105478">bits</span> <span m="105856">for</span> <span m="106234">the</span>
  <span m="106612">tag.</span></p><p><span m="106990">We</span> <span m="107279">need</span>
  <span m="107569">to</span> <span m="107859">use</span> <span m="108149">all</span>
  <span m="108439">of</span> <span m="108729">the</span> <span m="109019">remaining</span>
  <span m="109309">bits</span> <span m="109599">for</span> <span m="109889">the</span>
  <span m="110179">tag</span> <span m="110469">in</span> <span m="110759">order</span>
  <span m="111049">to</span> <span m="111339">be</span> <span m="111629">able</span>
  <span m="111919">to</span> <span m="112209">uniquely</span> <span m="112499">identify</span>
  <span m="112789">each</span> <span m="113606">distinct</span> <span m="114423">address.</span></p><p><span
  m="115240">Since</span> <span m="115547">many</span> <span m="115854">addresses</span>
  <span m="116161">will</span> <span m="116468">map</span> <span m="116775">to</span>
  <span m="117082">the</span> <span m="117389">same</span> <span m="117696">line</span>
  <span m="118003">in</span> <span m="118310">the</span> <span m="118617">cache,</span>
  <span m="118924">we</span> <span m="119231">must</span> <span m="119538">compare</span>
  <span m="119845">the</span> <span m="120152">tag</span> <span m="120460">of</span>
  <span m="120706">the</span> <span m="120953">data</span> <span m="121199">in</span>
  <span m="121446">the</span> <span m="121692">cache</span> <span m="121939">to</span>
  <span m="122185">see</span> <span m="122432">if</span> <span m="122678">we</span>
  <span m="122925">have</span> <span m="123171">in</span> <span m="123418">fact</span>
  <span m="123664">found</span> <span m="123911">the</span> <span m="124157">data</span>
  <span m="124404">that</span> <span m="124650">we</span> <span m="124897">are</span>
  <span m="125143">looking</span> <span m="125390">for.</span></p><p><span m="126650">So</span>
  <span m="127310">we</span> <span m="127970">use</span> <span m="128630">address</span>
  <span m="129290">bits</span> <span m="129950">[31:5]</span> <span m="130610">for</span>
  <span m="131270">the</span> <span m="131930">tag.</span></p><p><span m="132590">Suppose</span>
  <span m="133243">our</span> <span m="133896">beta</span> <span m="134550">executes</span>
  <span m="135203">a</span> <span m="135856">read</span> <span m="136510">of</span>
  <span m="137163">address</span> <span m="137816">0x5678.</span></p><p><span m="138470">We</span>
  <span m="138772">would</span> <span m="139075">like</span> <span m="139378">to</span>
  <span m="139681">identify</span> <span m="139984">which</span> <span m="140287">locations</span>
  <span m="140590">in</span> <span m="140893">the</span> <span m="141196">cache</span>
  <span m="141499">will</span> <span m="141802">need</span> <span m="142105">to</span>
  <span m="142408">be</span> <span m="142711">checked</span> <span m="143014">to</span>
  <span m="143317">determine</span> <span m="143620">if</span> <span m="144005">our</span>
  <span m="144390">data</span> <span m="144776">is</span> <span m="145161">already</span>
  <span m="145547">present</span> <span m="145932">in</span> <span m="146318">the</span>
  <span m="146703">cache</span> <span m="147089">or</span> <span m="147474">not.</span></p><p><span
  m="147860">In</span> <span m="148194">order</span> <span m="148528">to</span> <span
  m="148863">determine</span> <span m="149197">this,</span> <span m="149531">we</span>
  <span m="149866">need</span> <span m="150200">to</span> <span m="150535">identify</span>
  <span m="150869">the</span> <span m="151203">portion</span> <span m="151538">of</span>
  <span m="151872">the</span> <span m="152206">address</span> <span m="152541">that</span>
  <span m="152875">corresponds</span> <span m="153210">to</span> <span m="153793">the</span>
  <span m="154376">index.</span></p><p><span m="154959">The</span> <span m="155546">index</span>
  <span m="156133">bits</span> <span m="156721">are</span> <span m="157308">bits</span>
  <span m="157895">[4:2]</span> <span m="158483">which</span> <span m="159070">correspond</span>
  <span m="159657">to</span> <span m="160245">110</span> <span m="160832">in</span>
  <span m="161419">binary</span> <span m="162007">for</span> <span m="162594">this</span>
  <span m="163181">address.</span></p><p><span m="163769">That</span> <span m="164146">means</span>
  <span m="164524">that</span> <span m="164902">this</span> <span m="165280">address</span>
  <span m="165658">would</span> <span m="166036">map</span> <span m="166414">to</span>
  <span m="166792">cache</span> <span m="167170">line</span> <span m="167548">6</span>
  <span m="167926">in</span> <span m="168304">our</span> <span m="168682">cache.</span></p><p><span
  m="169060">Since</span> <span m="169392">this</span> <span m="169724">is</span>
  <span m="170056">a</span> <span m="170388">2-way</span> <span m="170720">set</span>
  <span m="171052">associative</span> <span m="171384">cache,</span> <span m="171716">there</span>
  <span m="172048">are</span> <span m="172380">two</span> <span m="172712">possible</span>
  <span m="173044">locations</span> <span m="173376">that</span> <span m="173708">our</span>
  <span m="174040">data</span> <span m="174700">could</span> <span m="175360">be</span>
  <span m="176020">located,</span> <span m="176680">either</span> <span m="177340">in</span>
  <span m="178000">6A</span> <span m="178660">or</span> <span m="179320">6B.</span></p><p><span
  m="179980">So</span> <span m="180292">we</span> <span m="180605">would</span> <span
  m="180918">need</span> <span m="181231">to</span> <span m="181544">compare</span>
  <span m="181857">both</span> <span m="182170">tags</span> <span m="182483">to</span>
  <span m="182796">determine</span> <span m="183109">whether</span> <span m="183422">or</span>
  <span m="183735">not</span> <span m="184048">the</span> <span m="184361">data</span>
  <span m="184674">we</span> <span m="184987">are</span> <span m="185300">trying</span>
  <span m="185613">to</span> <span m="185926">read</span> <span m="186239">is</span>
  <span m="187479">already</span> <span m="188719">in</span> <span m="189959">the</span>
  <span m="191199">cache.</span></p><p><span m="192439">Assuming</span> <span m="192758">that</span>
  <span m="193077">checking</span> <span m="193397">the</span> <span m="193716">cache</span>
  <span m="194035">on</span> <span m="194355">a</span> <span m="194674">read</span>
  <span m="194994">takes</span> <span m="195313">1</span> <span m="195632">cycle,</span>
  <span m="195952">and</span> <span m="196271">that</span> <span m="196590">refilling</span>
  <span m="196910">the</span> <span m="197229">cache</span> <span m="197549">on</span>
  <span m="197872">a</span> <span m="198196">miss</span> <span m="198520">takes</span>
  <span m="198844">an</span> <span m="199168">additional</span> <span m="199492">8</span>
  <span m="199816">cycles,</span> <span m="200140">this</span> <span m="200464">means</span>
  <span m="200787">that</span> <span m="201111">the</span> <span m="201435">time</span>
  <span m="201759">it</span> <span m="202083">takes</span> <span m="202407">on</span>
  <span m="202731">a</span> <span m="203055">miss</span> <span m="203379">is</span>
  <span m="203682">9</span> <span m="203985">cycles,</span> <span m="204288">1</span>
  <span m="204591">to</span> <span m="204894">first</span> <span m="205197">check</span>
  <span m="205500">if</span> <span m="205803">the</span> <span m="206106">value</span>
  <span m="206409">is</span> <span m="206712">in</span> <span m="207015">the</span>
  <span m="207318">cache,</span> <span m="207621">plus</span> <span m="207924">another</span>
  <span m="208227">8</span> <span m="208530">to</span> <span m="208833">bring</span>
  <span m="209136">the</span> <span m="209439">value</span> <span m="209895">into</span>
  <span m="210352">the</span> <span m="210809">cache</span> <span m="211265">if</span>
  <span m="211722">it</span> <span m="212179">wasn't</span> <span m="212635">already</span>
  <span m="213092">there.</span></p><p><span m="213549">Now</span> <span m="214009">suppose</span>
  <span m="214469">that</span> <span m="214929">we</span> <span m="215389">want</span>
  <span m="215849">to</span> <span m="216309">achieve</span> <span m="216769">an</span>
  <span m="217229">average</span> <span m="217689">read</span> <span m="218149">access</span>
  <span m="218609">time</span> <span m="219069">of</span> <span m="219529">1.1</span>
  <span m="219989">cycles.</span></p><p><span m="220450">What</span> <span m="220825">is</span>
  <span m="221200">the</span> <span m="221575">minimum</span> <span m="221951">hit</span>
  <span m="222326">ratio</span> <span m="222701">required</span> <span m="223076">to</span>
  <span m="223452">achieve</span> <span m="223827">this</span> <span m="224202">average</span>
  <span m="224577">access</span> <span m="224953">time</span> <span m="225328">over</span>
  <span m="225703">many</span> <span m="226079">reads?</span></p><p><span m="227680">We</span>
  <span m="228122">know</span> <span m="228565">that</span> <span m="229008">average</span>
  <span m="229451">access</span> <span m="229893">time</span> <span m="230336">=</span>
  <span m="230779">(hit</span> <span m="231222">time</span> <span m="231665">*</span>
  <span m="232107">hit</span> <span m="232550">rate)</span> <span m="232993">+</span>
  <span m="233436">(miss</span> <span m="233878">time</span> <span m="234321">*</span>
  <span m="234764">miss</span> <span m="235207">rate).</span></p><p><span m="235650">If</span>
  <span m="236100">we</span> <span m="236550">call</span> <span m="237000">'a'</span>
  <span m="237450">our</span> <span m="237900">hit</span> <span m="238350">rate,</span>
  <span m="238800">then</span> <span m="239250">our</span> <span m="239700">miss</span>
  <span m="240150">rate</span> <span m="240600">is</span> <span m="241050">(1-a).</span></p><p><span
  m="241500">So</span> <span m="242078">our</span> <span m="242656">desired</span>
  <span m="243234">average</span> <span m="243812">access</span> <span m="244391">time</span>
  <span m="244969">of</span> <span m="245547">1.1</span> <span m="246125">must</span>
  <span m="246704">equal</span> <span m="247282">1</span> <span m="247860">*</span>
  <span m="248438">a</span> <span m="249017">plus</span> <span m="249595">9</span>
  <span m="250173">*</span> <span m="250751">(1-a).</span></p><p><span m="251330">This</span>
  <span m="252038">reduces</span> <span m="252747">to</span> <span m="253456">1.1</span>
  <span m="254165">=</span> <span m="254873">9-8a,</span> <span m="255582">which</span>
  <span m="256291">means</span> <span m="257000">that</span> <span m="257708">8a</span>
  <span m="258417">=</span> <span m="259126">7.9</span> <span m="259835">or</span>
  <span m="260543">a</span> <span m="261252">=</span> <span m="261961">7.9/8.</span></p><p><span
  m="262670">So</span> <span m="263335">to</span> <span m="264001">achieve</span>
  <span m="264667">a</span> <span m="265333">1.1</span> <span m="265999">cycle</span>
  <span m="266665">average</span> <span m="267331">access</span> <span m="267997">time</span>
  <span m="268662">our</span> <span m="269328">hit</span> <span m="269994">rate</span>
  <span m="270660">must</span> <span m="271326">be</span> <span m="271992">at</span>
  <span m="272658">least</span> <span m="273324">7.9/8.</span></p><p><span m="273990">We</span>
  <span m="274421">are</span> <span m="274852">provided</span> <span m="275284">with</span>
  <span m="275715">this</span> <span m="276147">benchmark</span> <span m="276578">program</span>
  <span m="277010">for</span> <span m="277441">testing</span> <span m="277872">our</span>
  <span m="278304">2-way</span> <span m="278735">set</span> <span m="279167">associative</span>
  <span m="279598">cache.</span></p><p><span m="280030">The</span> <span m="280537">cache</span>
  <span m="281045">is</span> <span m="281552">initially</span> <span m="282060">empty</span>
  <span m="282567">before</span> <span m="283075">execution</span> <span m="283582">begins.</span></p><p><span
  m="284090">In</span> <span m="284519">other</span> <span m="284948">words,</span>
  <span m="285377">all</span> <span m="285806">the</span> <span m="286235">valid</span>
  <span m="286665">bits</span> <span m="287094">of</span> <span m="287523">the</span>
  <span m="287952">cache</span> <span m="288381">are</span> <span m="288810">0.</span></p><p><span
  m="289240">Assuming</span> <span m="289638">that</span> <span m="290036">an</span>
  <span m="290434">LRU,</span> <span m="290832">or</span> <span m="291230">least</span>
  <span m="291628">recently</span> <span m="292026">used,</span> <span m="292424">replacement</span>
  <span m="292822">strategy</span> <span m="293220">is</span> <span m="293618">used,</span>
  <span m="294016">we</span> <span m="294414">would</span> <span m="294812">like</span>
  <span m="295210">to</span> <span m="295810">determine</span> <span m="296410">the</span>
  <span m="297010">approximate</span> <span m="297610">cache</span> <span m="298210">hit</span>
  <span m="298810">ratio</span> <span m="299410">for</span> <span m="300010">this</span>
  <span m="300610">program.</span></p><p><span m="301210">Let's</span> <span m="301725">begin</span>
  <span m="302240">by</span> <span m="302755">understanding</span> <span m="303270">what</span>
  <span m="303785">this</span> <span m="304300">benchmark</span> <span m="304815">does.</span></p><p><span
  m="305330">The</span> <span m="305680">program</span> <span m="306030">begins</span>
  <span m="306380">at</span> <span m="306730">address</span> <span m="307080">0.</span></p><p><span
  m="307430">It</span> <span m="308060">first</span> <span m="308691">performs</span>
  <span m="309322">some</span> <span m="309953">initialization</span> <span m="310584">of</span>
  <span m="311215">registers</span> <span m="311846">using</span> <span m="312477">three</span>
  <span m="313108">CMOVE</span> <span m="313739">operations.</span></p><p><span m="314370">The</span>
  <span m="314730">first,</span> <span m="315091">initializes</span> <span m="315451">R0</span>
  <span m="315812">to</span> <span m="316172">hold</span> <span m="316533">source</span>
  <span m="316894">which</span> <span m="317254">is</span> <span m="317615">the</span>
  <span m="317975">address</span> <span m="318336">in</span> <span m="318697">memory</span>
  <span m="319057">where</span> <span m="319418">our</span> <span m="319778">data</span>
  <span m="320139">will</span> <span m="320500">be</span> <span m="321470">stored.</span></p><p><span
  m="322440">The</span> <span m="322965">second</span> <span m="323491">initializes</span>
  <span m="324017">R1</span> <span m="324543">to</span> <span m="325069">0,</span>
  <span m="325595">and</span> <span m="326121">the</span> <span m="326647">third</span>
  <span m="327172">initializes</span> <span m="327698">R2</span> <span m="328224">to</span>
  <span m="328750">0x1000</span> <span m="329276">which</span> <span m="329802">is</span>
  <span m="330328">the</span> <span m="330854">number</span> <span m="331380">of</span>
  <span m="331851">words</span> <span m="332322">that</span> <span m="332793">this</span>
  <span m="333265">benchmark</span> <span m="333736">will</span> <span m="334207">work</span>
  <span m="334678">with.</span></p><p><span m="335150">We</span> <span m="335476">then</span>
  <span m="335803">enter</span> <span m="336130">the</span> <span m="336456">loop</span>
  <span m="336783">which</span> <span m="337110">is</span> <span m="337436">shown</span>
  <span m="337763">in</span> <span m="338090">the</span> <span m="338416">yellow</span>
  <span m="338743">rectangle.</span></p><p><span m="339070">The</span> <span m="339544">loop</span>
  <span m="340019">loads</span> <span m="340494">the</span> <span m="340968">first</span>
  <span m="341443">element</span> <span m="341918">of</span> <span m="342392">our</span>
  <span m="342867">data</span> <span m="343342">from</span> <span m="343817">location</span>
  <span m="344291">source</span> <span m="344766">+</span> <span m="345241">0</span>
  <span m="345715">into</span> <span m="346190">register</span> <span m="346665">R3.</span></p><p><span
  m="347140">It</span> <span m="347524">then</span> <span m="347909">increments</span>
  <span m="348294">R0</span> <span m="348679">to</span> <span m="349064">point</span>
  <span m="349449">to</span> <span m="349834">the</span> <span m="350219">next</span>
  <span m="350604">piece</span> <span m="350989">of</span> <span m="351374">data.</span></p><p><span
  m="351759">Since</span> <span m="352147">our</span> <span m="352535">data</span>
  <span m="352923">is</span> <span m="353311">32</span> <span m="353699">bits</span>
  <span m="354088">wide,</span> <span m="354476">this</span> <span m="354864">requires</span>
  <span m="355252">the</span> <span m="355640">addition</span> <span m="356029">of</span>
  <span m="356417">the</span> <span m="356805">constant</span> <span m="357193">4</span>
  <span m="357581">representing</span> <span m="357970">the</span> <span m="358408">number</span>
  <span m="358847">of</span> <span m="359285">bytes</span> <span m="359724">between</span>
  <span m="360163">consecutive</span> <span m="360601">data</span> <span m="361040">words.</span></p><p><span
  m="361479">It</span> <span m="361808">then</span> <span m="362138">takes</span>
  <span m="362467">the</span> <span m="362797">value</span> <span m="363126">that</span>
  <span m="363456">was</span> <span m="363785">just</span> <span m="364115">loaded</span>
  <span m="364444">and</span> <span m="364774">adds</span> <span m="365103">it</span>
  <span m="365433">to</span> <span m="365762">R1</span> <span m="366092">which</span>
  <span m="366421">holds</span> <span m="366751">a</span> <span m="367080">running</span>
  <span m="367410">sum</span> <span m="367740">of</span> <span m="368170">all</span>
  <span m="368600">the</span> <span m="369030">data</span> <span m="369460">seen</span>
  <span m="369890">so</span> <span m="370320">far.</span></p><p><span m="370750">R2</span>
  <span m="371166">is</span> <span m="371582">then</span> <span m="371998">decremented</span>
  <span m="372414">by</span> <span m="372830">1</span> <span m="373246">to</span>
  <span m="373662">indicate</span> <span m="374078">that</span> <span m="374495">we</span>
  <span m="374911">have</span> <span m="375327">one</span> <span m="375743">fewer</span>
  <span m="376159">piece</span> <span m="376575">of</span> <span m="376991">data</span>
  <span m="377407">to</span> <span m="377823">handle.</span></p><p><span m="378240">Finally,</span>
  <span m="378767">as</span> <span m="379295">long</span> <span m="379823">as</span>
  <span m="380351">R2</span> <span m="380879">is</span> <span m="381407">not</span>
  <span m="381935">equal</span> <span m="382462">to</span> <span m="382990">0</span>
  <span m="383518">it</span> <span m="384046">repeats</span> <span m="384574">the</span>
  <span m="385102">loop.</span></p><p><span m="385630">At</span> <span m="385967">the</span>
  <span m="386305">very</span> <span m="386643">end</span> <span m="386981">of</span>
  <span m="387318">the</span> <span m="387656">benchmark</span> <span m="387994">the</span>
  <span m="388332">final</span> <span m="388670">sum</span> <span m="389007">is</span>
  <span m="389345">stored</span> <span m="389683">at</span> <span m="390021">address</span>
  <span m="390358">source,</span> <span m="390696">and</span> <span m="391034">the</span>
  <span m="391372">program</span> <span m="391710">halts.</span></p><p><span m="394250">When</span>
  <span m="394623">trying</span> <span m="394997">to</span> <span m="395370">determine</span>
  <span m="395744">the</span> <span m="396117">approximate</span> <span m="396491">hit</span>
  <span m="396865">ratio,</span> <span m="397238">the</span> <span m="397612">instructions</span>
  <span m="397985">that</span> <span m="398359">occur</span> <span m="398732">only</span>
  <span m="399106">once</span> <span m="399480">because</span> <span m="400029">they</span>
  <span m="400578">live</span> <span m="401127">outside</span> <span m="401676">of</span>
  <span m="402225">the</span> <span m="402774">loop</span> <span m="403323">can</span>
  <span m="403872">basically</span> <span m="404421">be</span> <span m="404970">ignored.</span></p><p><span
  m="405520">So</span> <span m="405827">looking</span> <span m="406135">only</span>
  <span m="406443">at</span> <span m="406751">what</span> <span m="407058">happens</span>
  <span m="407366">over</span> <span m="407674">and</span> <span m="407982">over</span>
  <span m="408290">again</span> <span m="408597">in</span> <span m="408905">the</span>
  <span m="409213">loop,</span> <span m="409521">each</span> <span m="409828">time</span>
  <span m="410136">through</span> <span m="410444">the</span> <span m="410752">loop,</span>
  <span m="411060">we</span> <span m="411543">have</span> <span m="412026">5</span>
  <span m="412509">instruction</span> <span m="412992">fetches</span> <span m="413476">and</span>
  <span m="413959">one</span> <span m="414442">data</span> <span m="414925">fetch.</span></p><p><span
  m="415409">The</span> <span m="415685">first</span> <span m="415962">time</span>
  <span m="416239">through</span> <span m="416516">the</span> <span m="416793">loop,</span>
  <span m="417070">we</span> <span m="417347">miss</span> <span m="417624">on</span>
  <span m="417901">the</span> <span m="418178">instruction</span> <span m="418455">fetches</span>
  <span m="418732">and</span> <span m="419009">then</span> <span m="419286">bring</span>
  <span m="419563">them</span> <span m="419840">into</span> <span m="420476">the</span>
  <span m="421113">cache.</span></p><p><span m="421750">We</span> <span m="422072">also</span>
  <span m="422394">miss</span> <span m="422716">on</span> <span m="423038">the</span>
  <span m="423360">data</span> <span m="423682">load</span> <span m="424004">from</span>
  <span m="424326">address</span> <span m="424648">0x100.</span></p><p><span m="424970">When</span>
  <span m="425432">this</span> <span m="425894">data</span> <span m="426356">is</span>
  <span m="426818">brought</span> <span m="427280">into</span> <span m="427742">the</span>
  <span m="428204">cache,</span> <span m="428666">instead</span> <span m="429128">of</span>
  <span m="429590">replacing</span> <span m="430052">the</span> <span m="430514">recently</span>
  <span m="430976">loaded</span> <span m="431438">instructions,</span> <span m="431900">it</span>
  <span m="432309">loads</span> <span m="432718">the</span> <span m="433127">data</span>
  <span m="433536">into</span> <span m="433945">the</span> <span m="434354">2nd</span>
  <span m="434763">set</span> <span m="435172">of</span> <span m="435581">the</span>
  <span m="435990">cache.</span></p><p><span m="436400">The</span> <span m="436788">loop</span>
  <span m="437176">is</span> <span m="437564">then</span> <span m="437952">repeated.</span></p><p><span
  m="438340">This</span> <span m="438689">time</span> <span m="439039">through</span>
  <span m="439389">the</span> <span m="439739">loop,</span> <span m="440089">all</span>
  <span m="440439">the</span> <span m="440789">instruction</span> <span m="441139">fetches</span>
  <span m="441489">result</span> <span m="441839">in</span> <span m="442189">hits.</span></p><p><span
  m="442539">However,</span> <span m="442828">the</span> <span m="443117">data</span>
  <span m="443406">that</span> <span m="443695">we</span> <span m="443984">now</span>
  <span m="444273">need</span> <span m="444562">is</span> <span m="444851">a</span>
  <span m="445140">new</span> <span m="445429">piece</span> <span m="445718">of</span>
  <span m="446007">data</span> <span m="446296">so</span> <span m="446585">that</span>
  <span m="446874">will</span> <span m="447163">result</span> <span m="447452">in</span>
  <span m="447741">a</span> <span m="448030">cache</span> <span m="448319">miss</span>
  <span m="448733">and</span> <span m="449147">once</span> <span m="449562">again</span>
  <span m="449976">load</span> <span m="450390">the</span> <span m="450805">new</span>
  <span m="451219">data</span> <span m="451634">word</span> <span m="452048">into</span>
  <span m="452462">the</span> <span m="452877">2nd</span> <span m="453291">set</span>
  <span m="453705">of</span> <span m="454120">the</span> <span m="454534">cache.</span></p><p><span
  m="454949">This</span> <span m="455370">behavior</span> <span m="455791">then</span>
  <span m="456212">repeats</span> <span m="456633">itself</span> <span m="457054">every</span>
  <span m="457475">time</span> <span m="457896">through</span> <span m="458317">the</span>
  <span m="458738">loop.</span></p><p><span m="459159">Since</span> <span m="459504">the</span>
  <span m="459849">loop</span> <span m="460195">is</span> <span m="460540">executed</span>
  <span m="460886">many</span> <span m="461231">times,</span> <span m="461576">we</span>
  <span m="461922">can</span> <span m="462267">also</span> <span m="462613">ignore</span>
  <span m="462958">the</span> <span m="463303">initial</span> <span m="463649">instruction</span>
  <span m="463994">fetches</span> <span m="464340">on</span> <span m="464762">the</span>
  <span m="465185">first</span> <span m="465608">iteration</span> <span m="466031">of</span>
  <span m="466454">the</span> <span m="466877">loop.</span></p><p><span m="467300">So</span>
  <span m="467684">in</span> <span m="468069">steady</span> <span m="468454">state,</span>
  <span m="468839">we</span> <span m="469224">get</span> <span m="469609">5</span>
  <span m="469994">instruction</span> <span m="470379">cache</span> <span m="470764">hits,</span>
  <span m="471149">and</span> <span m="471534">1</span> <span m="471919">data</span>
  <span m="472304">cache</span> <span m="472689">miss</span> <span m="473074">every</span>
  <span m="473459">time</span> <span m="473844">through</span> <span m="474229">the</span>
  <span m="475454">loop.</span></p><p><span m="476680">This</span> <span m="477575">means</span>
  <span m="478471">that</span> <span m="479366">our</span> <span m="480262">approximate</span>
  <span m="481157">hit</span> <span m="482053">ratio</span> <span m="482948">is</span>
  <span m="483844">5/6.</span></p><p><span m="484740">The</span> <span m="485041">last</span>
  <span m="485343">question</span> <span m="485645">we</span> <span m="485947">want</span>
  <span m="486248">to</span> <span m="486550">consider</span> <span m="486852">is</span>
  <span m="487154">what</span> <span m="487455">is</span> <span m="487757">stored</span>
  <span m="488059">in</span> <span m="488361">the</span> <span m="488662">cache</span>
  <span m="488964">after</span> <span m="489266">execution</span> <span m="489568">of</span>
  <span m="489870">this</span> <span m="490602">benchmark</span> <span m="491335">is</span>
  <span m="492067">completed.</span></p><p><span m="492800">As</span> <span m="493168">we</span>
  <span m="493537">saw</span> <span m="493906">earlier,</span> <span m="494274">because</span>
  <span m="494643">we</span> <span m="495012">have</span> <span m="495380">a</span>
  <span m="495749">2-way</span> <span m="496118">set</span> <span m="496486">associative</span>
  <span m="496855">cache,</span> <span m="497224">the</span> <span m="497592">instructions</span>
  <span m="497961">and</span> <span m="498330">data</span> <span m="498710">don't</span>
  <span m="499091">conflict</span> <span m="499471">with</span> <span m="499852">each</span>
  <span m="500233">other</span> <span m="500613">because</span> <span m="500994">they</span>
  <span m="501374">can</span> <span m="501755">each</span> <span m="502136">go</span>
  <span m="502516">in</span> <span m="502897">a</span> <span m="503277">separate</span>
  <span m="503658">set.</span></p><p><span m="504039">We</span> <span m="504316">want</span>
  <span m="504593">to</span> <span m="504870">determine</span> <span m="505147">which</span>
  <span m="505424">instruction</span> <span m="505701">and</span> <span m="505978">which</span>
  <span m="506255">piece</span> <span m="506533">of</span> <span m="506810">data</span>
  <span m="507087">will</span> <span m="507364">end</span> <span m="507641">up</span>
  <span m="507918">in</span> <span m="508195">line</span> <span m="508472">4</span>
  <span m="508750">of</span> <span m="509407">the</span> <span m="510064">cache</span>
  <span m="510721">after</span> <span m="511378">execution</span> <span m="512035">is</span>
  <span m="512692">completed.</span></p><p><span m="513350">We'll</span> <span m="513826">begin</span>
  <span m="514302">by</span> <span m="514779">identifying</span> <span m="515255">the</span>
  <span m="515731">mapping</span> <span m="516208">of</span> <span m="516684">instructions</span>
  <span m="517160">to</span> <span m="517637">cache</span> <span m="518113">lines.</span></p><p><span
  m="518590">Since</span> <span m="518980">our</span> <span m="519370">program</span>
  <span m="519760">begins</span> <span m="520150">at</span> <span m="520540">address</span>
  <span m="520930">0,</span> <span m="521320">the</span> <span m="521710">first</span>
  <span m="522100">CMOVE</span> <span m="522490">instruction</span> <span m="522880">is</span>
  <span m="523270">at</span> <span m="523660">address</span> <span m="524050">0,</span>
  <span m="524440">and</span> <span m="524830">it's</span> <span m="525576">index</span>
  <span m="526322">is</span> <span m="527068">equal</span> <span m="527814">to</span>
  <span m="528560">0b000,</span> <span m="529306">or</span> <span m="530052">0</span>
  <span m="530798">in</span> <span m="531544">binary.</span></p><p><span m="532290">This</span>
  <span m="532615">means</span> <span m="532940">that</span> <span m="533265">it</span>
  <span m="533590">will</span> <span m="533915">map</span> <span m="534240">to</span>
  <span m="534565">cache</span> <span m="534890">line</span> <span m="535215">0.</span></p><p><span
  m="535540">Since</span> <span m="535866">at</span> <span m="536193">this</span>
  <span m="536520">point,</span> <span m="536847">nothing</span> <span m="537174">is</span>
  <span m="537501">in</span> <span m="537827">the</span> <span m="538154">cache,</span>
  <span m="538481">it</span> <span m="538808">will</span> <span m="539135">be</span>
  <span m="539462">loaded</span> <span m="539788">into</span> <span m="540115">line</span>
  <span m="540442">0</span> <span m="540769">of</span> <span m="541096">set</span>
  <span m="541423">A.</span></p><p><span m="541750">In</span> <span m="542111">a</span>
  <span m="542473">similar</span> <span m="542835">manner</span> <span m="543197">the</span>
  <span m="543558">next</span> <span m="543920">2</span> <span m="544282">CMOVE</span>
  <span m="544644">instructions</span> <span m="545005">and</span> <span m="545367">the</span>
  <span m="545729">LD</span> <span m="546091">instruction</span> <span m="546452">will</span>
  <span m="546814">be</span> <span m="547176">loaded</span> <span m="547538">into</span>
  <span m="547900">lines</span> <span m="548435">1-3</span> <span m="548970">of</span>
  <span m="549505">set</span> <span m="550040">A.</span> <span m="550575">At</span>
  <span m="551110">this</span> <span m="551645">point,</span> <span m="552180">we</span>
  <span m="552715">begin</span> <span m="553250">loading</span> <span m="553785">data.</span></p><p><span
  m="554320">Since</span> <span m="554642">the</span> <span m="554965">cache</span>
  <span m="555287">is</span> <span m="555610">2-way</span> <span m="555932">set</span>
  <span m="556255">associative,</span> <span m="556577">the</span> <span m="556900">data</span>
  <span m="557222">will</span> <span m="557545">be</span> <span m="557867">loaded</span>
  <span m="558190">into</span> <span m="558512">set</span> <span m="558835">B</span>
  <span m="559157">instead</span> <span m="559480">of</span> <span m="559911">removing</span>
  <span m="560342">the</span> <span m="560773">instructions</span> <span m="561204">that</span>
  <span m="561635">were</span> <span m="562066">loaded</span> <span m="562497">into</span>
  <span m="562928">set</span> <span m="563359">A.</span></p><p><span m="563790">The</span>
  <span m="564072">instructions</span> <span m="564355">that</span> <span m="564638">are</span>
  <span m="564921">outside</span> <span m="565204">the</span> <span m="565487">loop</span>
  <span m="565770">will</span> <span m="566053">end</span> <span m="566336">up</span>
  <span m="566619">getting</span> <span m="566902">taken</span> <span m="567185">out</span>
  <span m="567468">of</span> <span m="567751">set</span> <span m="568034">A</span>
  <span m="568317">in</span> <span m="568600">favor</span> <span m="568964">of</span>
  <span m="569328">loading</span> <span m="569692">a</span> <span m="570056">data</span>
  <span m="570420">item</span> <span m="570784">into</span> <span m="571148">those</span>
  <span m="571512">cache</span> <span m="571876">locations,</span> <span m="572240">but</span>
  <span m="572604">the</span> <span m="572968">instructions</span> <span m="573332">that</span>
  <span m="573696">make</span> <span m="574060">up</span> <span m="574486">the</span>
  <span m="574912">loop</span> <span m="575338">will</span> <span m="575765">not</span>
  <span m="576191">be</span> <span m="576617">displaced</span> <span m="577043">because</span>
  <span m="577470">every</span> <span m="577896">time</span> <span m="578322">something</span>
  <span m="578748">maps</span> <span m="579175">to</span> <span m="579601">cache</span>
  <span m="580027">lines</span> <span m="580453">3-7,</span> <span m="580880">the</span>
  <span m="581243">least</span> <span m="581606">recently</span> <span m="581969">used</span>
  <span m="582332">location</span> <span m="582695">will</span> <span m="583058">correspond</span>
  <span m="583421">to</span> <span m="583785">a</span> <span m="584148">data</span>
  <span m="584511">value</span> <span m="584874">not</span> <span m="585237">to</span>
  <span m="585600">the</span> <span m="585963">instructions</span> <span m="586326">which</span>
  <span m="586690">are</span> <span m="587185">used</span> <span m="587680">over</span>
  <span m="588175">and</span> <span m="588670">over</span> <span m="589165">again.</span></p><p><span
  m="589660">This</span> <span m="589928">means</span> <span m="590197">that</span>
  <span m="590466">at</span> <span m="590735">the</span> <span m="591003">end</span>
  <span m="591272">of</span> <span m="591541">execution</span> <span m="591810">of</span>
  <span m="592078">the</span> <span m="592347">benchmark,</span> <span m="592616">the</span>
  <span m="592885">instruction</span> <span m="593153">that</span> <span m="593422">will</span>
  <span m="593691">be</span> <span m="593960">in</span> <span m="594594">line</span>
  <span m="595228">4</span> <span m="595863">of</span> <span m="596497">the</span>
  <span m="597131">cache</span> <span m="597766">is</span> <span m="598400">the</span>
  <span m="599035">ADDC</span> <span m="599669">instruction</span> <span m="600303">from</span>
  <span m="600938">address</span> <span m="601572">0x10</span> <span m="602206">of</span>
  <span m="602841">the</span> <span m="603475">program.</span></p><p><span m="604110">The</span>
  <span m="604555">loop</span> <span m="605000">instructions</span> <span m="605445">which</span>
  <span m="605890">will</span> <span m="606335">remain</span> <span m="606780">in</span>
  <span m="607225">the</span> <span m="607670">cache</span> <span m="608115">are</span>
  <span m="608560">shown</span> <span m="609005">here.</span></p><p><span m="609450">Now</span>
  <span m="609787">let's</span> <span m="610125">consider</span> <span m="610462">what</span>
  <span m="610800">happens</span> <span m="611137">to</span> <span m="611475">the</span>
  <span m="611812">data</span> <span m="612150">used</span> <span m="612487">in</span>
  <span m="612825">this</span> <span m="613162">benchmark.</span></p><p><span m="613500">We</span>
  <span m="613869">expect</span> <span m="614238">the</span> <span m="614608">loop</span>
  <span m="614977">instructions</span> <span m="615346">to</span> <span m="615716">remain</span>
  <span m="616085">in</span> <span m="616455">lines</span> <span m="616824">3-7</span>
  <span m="617193">of</span> <span m="617563">set</span> <span m="617932">A</span>
  <span m="618301">of</span> <span m="618671">the</span> <span m="619040">cache.</span></p><p><span
  m="619410">The</span> <span m="619850">data</span> <span m="620291">will</span>
  <span m="620731">use</span> <span m="621172">all</span> <span m="621613">of</span>
  <span m="622053">set</span> <span m="622494">B</span> <span m="622935">plus</span>
  <span m="623375">locations</span> <span m="623816">0-2</span> <span m="624256">of</span>
  <span m="624697">set</span> <span m="625138">A</span> <span m="625578">as</span>
  <span m="626019">needed.</span></p><p><span m="626460">The</span> <span m="626921">data</span>
  <span m="627383">begins</span> <span m="627845">at</span> <span m="628306">address</span>
  <span m="628768">0x100.</span></p><p><span m="629230">The</span> <span m="629977">index</span>
  <span m="630725">portion</span> <span m="631472">of</span> <span m="632220">address</span>
  <span m="632968">0x100</span> <span m="633715">is</span> <span m="634463">0b000</span>
  <span m="635211">so</span> <span m="635958">this</span> <span m="636706">data</span>
  <span m="637454">element</span> <span m="638201">maps</span> <span m="638949">to</span>
  <span m="639697">cache</span> <span m="640444">line</span> <span m="641192">0.</span></p><p><span
  m="641940">Since</span> <span m="642263">the</span> <span m="642586">least</span>
  <span m="642909">recently</span> <span m="643232">used</span> <span m="643555">set</span>
  <span m="643878">for</span> <span m="644202">line</span> <span m="644525">0</span>
  <span m="644848">is</span> <span m="645171">set</span> <span m="645494">B,</span>
  <span m="645817">it</span> <span m="646141">will</span> <span m="646464">go</span>
  <span m="646787">into</span> <span m="647110">set</span> <span m="647433">B</span>
  <span m="647756">leaving</span> <span m="648080">the</span> <span m="648674">instructions</span>
  <span m="649269">in</span> <span m="649864">tact</span> <span m="650458">in</span>
  <span m="651053">set</span> <span m="651648">A.</span> <span m="652242">The</span>
  <span m="652837">next</span> <span m="653432">data</span> <span m="654026">element</span>
  <span m="654621">is</span> <span m="655216">at</span> <span m="655810">address</span>
  <span m="656405">0x104.</span></p><p><span m="657000">Since</span> <span m="657344">the</span>
  <span m="657688">bottom</span> <span m="658033">two</span> <span m="658377">bits</span>
  <span m="658721">are</span> <span m="659066">used</span> <span m="659410">for</span>
  <span m="659755">word</span> <span m="660099">alignment,</span> <span m="660443">the</span>
  <span m="660788">index</span> <span m="661132">portion</span> <span m="661476">of</span>
  <span m="661821">this</span> <span m="662165">address</span> <span m="662510">is</span>
  <span m="663133">0b001,</span> <span m="663756">so</span> <span m="664379">this</span>
  <span m="665002">data</span> <span m="665625">element</span> <span m="666248">maps</span>
  <span m="666872">to</span> <span m="667495">line</span> <span m="668118">1</span>
  <span m="668741">of</span> <span m="669364">set</span> <span m="669987">B,</span>
  <span m="670611">and</span> <span m="671234">so</span> <span m="671857">on</span>
  <span m="672480">through</span> <span m="673103">element</span> <span m="673726">0x7.</span></p><p><span
  m="674350">Data</span> <span m="675177">element</span> <span m="676004">0x8</span>
  <span m="676831">is</span> <span m="677658">at</span> <span m="678485">address</span>
  <span m="679312">0x120.</span></p><p><span m="680140">The</span> <span m="680697">index</span>
  <span m="681254">portion</span> <span m="681811">of</span> <span m="682368">this</span>
  <span m="682925">address</span> <span m="683482">is</span> <span m="684039">once</span>
  <span m="684596">again</span> <span m="685153">0b000.</span></p><p><span m="685710">So</span>
  <span m="686208">this</span> <span m="686706">element</span> <span m="687205">maps</span>
  <span m="687703">to</span> <span m="688202">cache</span> <span m="688700">line</span>
  <span m="689199">0</span> <span m="689697">just</span> <span m="690196">like</span>
  <span m="690694">element</span> <span m="691193">0x0</span> <span m="691691">did.</span></p><p><span
  m="692190">However,</span> <span m="692564">at</span> <span m="692938">this</span>
  <span m="693313">point</span> <span m="693687">line</span> <span m="694062">0</span>
  <span m="694436">of</span> <span m="694811">set</span> <span m="695185">B</span>
  <span m="695560">was</span> <span m="695934">accessed</span> <span m="696308">more</span>
  <span m="696683">recently</span> <span m="697057">than</span> <span m="697432">line</span>
  <span m="697806">0</span> <span m="698181">of</span> <span m="698555">set</span>
  <span m="698930">A,</span> <span m="699364">so</span> <span m="699798">the</span>
  <span m="700232">CMOVE</span> <span m="700666">instruction</span> <span m="701100">which</span>
  <span m="701534">is</span> <span m="701968">executed</span> <span m="702402">only</span>
  <span m="702837">once</span> <span m="703271">will</span> <span m="703705">get</span>
  <span m="704139">replaced</span> <span m="704573">by</span> <span m="705007">a</span>
  <span m="705441">data</span> <span m="705875">element</span> <span m="706310">that</span>
  <span m="707002">maps</span> <span m="707694">to</span> <span m="708386">line</span>
  <span m="709078">0.</span></p><p><span m="709770">As</span> <span m="710111">we</span>
  <span m="710452">mentioned</span> <span m="710794">earlier,</span> <span m="711135">all</span>
  <span m="711476">the</span> <span m="711818">instructions</span> <span m="712159">in</span>
  <span m="712500">the</span> <span m="712842">loop</span> <span m="713183">will</span>
  <span m="713524">not</span> <span m="713866">be</span> <span m="714207">displaced</span>
  <span m="714548">because</span> <span m="714890">they</span> <span m="715224">are</span>
  <span m="715558">accessed</span> <span m="715892">over</span> <span m="716226">and</span>
  <span m="716560">over</span> <span m="716894">again</span> <span m="717228">so</span>
  <span m="717562">they</span> <span m="717897">never</span> <span m="718231">end</span>
  <span m="718565">up</span> <span m="718899">being</span> <span m="719233">the</span>
  <span m="719567">least</span> <span m="719901">recently</span> <span m="720235">used</span>
  <span m="720570">item</span> <span m="721226">in</span> <span m="721882">a</span>
  <span m="722538">cache</span> <span m="723194">line.</span></p><p><span m="723850">After</span>
  <span m="724348">executing</span> <span m="724846">the</span> <span m="725344">loop</span>
  <span m="725842">16</span> <span m="726340">times</span> <span m="726838">meaning</span>
  <span m="727336">that</span> <span m="727834">data</span> <span m="728332">elements</span>
  <span m="728830">0</span> <span m="729328">through</span> <span m="729826">0xF</span>
  <span m="730324">have</span> <span m="730822">been</span> <span m="731320">accessed,</span>
  <span m="731744">the</span> <span m="732168">cache</span> <span m="732592">will</span>
  <span m="733017">look</span> <span m="733441">like</span> <span m="733865">this.</span></p><p><span
  m="734290">Note</span> <span m="734706">that</span> <span m="735122">the</span>
  <span m="735538">loop</span> <span m="735954">instructions</span> <span m="736370">continue</span>
  <span m="736786">in</span> <span m="737203">their</span> <span m="737619">original</span>
  <span m="738035">location</span> <span m="738451">in</span> <span m="738867">the</span>
  <span m="739283">cache.</span></p><p><span m="739700">The</span> <span m="740051">state</span>
  <span m="740403">of</span> <span m="740755">the</span> <span m="741107">cache</span>
  <span m="741459">continues</span> <span m="741811">to</span> <span m="742163">look</span>
  <span m="742515">like</span> <span m="742866">this</span> <span m="743218">with</span>
  <span m="743570">more</span> <span m="743922">recently</span> <span m="744274">accessed</span>
  <span m="744626">data</span> <span m="744978">elements</span> <span m="745330">replacing</span>
  <span m="745980">the</span> <span m="746630">earlier</span> <span m="747280">data</span>
  <span m="747930">elements.</span></p><p><span m="748580">Since</span> <span m="749166">there</span>
  <span m="749752">are</span> <span m="750339">0x1000</span> <span m="750925">elements</span>
  <span m="751512">of</span> <span m="752098">data,</span> <span m="752685">this</span>
  <span m="753271">continues</span> <span m="753857">until</span> <span m="754444">just</span>
  <span m="755030">before</span> <span m="755617">address</span> <span m="756203">0x4100.</span></p><p><span
  m="756790">The</span> <span m="757572">last</span> <span m="758354">element</span>
  <span m="759136">is</span> <span m="759919">actually</span> <span m="760701">located</span>
  <span m="761483">1</span> <span m="762266">word</span> <span m="763048">before</span>
  <span m="763830">that</span> <span m="764613">at</span> <span m="765395">address</span>
  <span m="766177">0x40FC.</span></p><p><span m="766960">The</span> <span m="767345">last</span>
  <span m="767731">8</span> <span m="768116">elements</span> <span m="768502">of</span>
  <span m="768888">the</span> <span m="769273">data</span> <span m="769659">and</span>
  <span m="770045">their</span> <span m="770430">mapping</span> <span m="770816">to</span>
  <span m="771201">cache</span> <span m="771587">lines</span> <span m="771973">is</span>
  <span m="772358">shown</span> <span m="772744">here.</span></p><p><span m="773130">The</span>
  <span m="773468">data</span> <span m="773807">element</span> <span m="774146">that</span>
  <span m="774485">ends</span> <span m="774824">up</span> <span m="775163">in</span>
  <span m="775502">line</span> <span m="775841">4</span> <span m="776180">of</span>
  <span m="776518">the</span> <span m="776857">cache,</span> <span m="777196">when</span>
  <span m="777535">the</span> <span m="777874">benchmark</span> <span m="778213">is</span>
  <span m="778552">done</span> <span m="778891">executing,</span> <span m="779230">is</span>
  <span m="780180">element</span> <span m="781130">0x0FFC</span> <span m="782080">of</span>
  <span m="783030">the</span> <span m="783980">data</span> <span m="784930">which</span>
  <span m="785880">comes</span> <span m="786830">from</span> <span m="787780">address</span>
  <span m="788730">0x40F0.</span></p>
type: course
uid: fab1783eebc56acbb15298984c18f0ec

---
None