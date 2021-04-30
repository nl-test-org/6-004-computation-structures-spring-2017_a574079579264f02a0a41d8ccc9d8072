---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: aR6X3OUAKkI
  parent_uid: 285358a1a7d1edd254363c1b22da8cf8
  title: Video-YouTube-Stream
  type: Video
  uid: 5bd77a801ab6795ce663e177208c97f3
- id: 3Play-3Play YouTube id-Stream
  media_location: aR6X3OUAKkI
  parent_uid: 285358a1a7d1edd254363c1b22da8cf8
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 7c309cc580038b43739ed6cb993f0b9c
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/aR6X3OUAKkI/default.jpg
  parent_uid: 285358a1a7d1edd254363c1b22da8cf8
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: a07c51a69b7270c9b7a3fc40e08e5a7d
- id: aR6X3OUAKkI.srt
  parent_uid: 285358a1a7d1edd254363c1b22da8cf8
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v7/example-priorities-in-action-6-52-/aR6X3OUAKkI.srt
  title: 3play caption file
  type: null
  uid: 0a64cca00dd8f7e083294cb004d09c61
- id: aR6X3OUAKkI.pdf
  parent_uid: 285358a1a7d1edd254363c1b22da8cf8
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v7/example-priorities-in-action-6-52-/aR6X3OUAKkI.pdf
  title: 3play pdf file
  type: null
  uid: e478adf5a133deae8547c708f2c3c1c3
- id: Caption-3Play YouTube id-SRT
  parent_uid: 285358a1a7d1edd254363c1b22da8cf8
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: fdcf6982c6c2cbb0c2fbbd673ddb2867
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 285358a1a7d1edd254363c1b22da8cf8
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 4dd7da5e402d5474bf28b10600ddf4b6
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_18-02-07_300k.mp4
  parent_uid: 285358a1a7d1edd254363c1b22da8cf8
  title: Video-Internet Archive-MP4
  type: Video
  uid: 77c2782b2e4db43155fbac98800ae2e6
inline_embed_id: 65438023exampleprioritiesinaction65217010300
layout: video
order_index: null
parent_uid: 922f69a02bd14a3b04a52fd2f37e6e95
related_resources_text: ''
short_url: example-priorities-in-action-6-52-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v7/example-priorities-in-action-6-52-
template_type: Embed
title: 'Example: Priorities in Action!'
transcript: <p><span m="339">Let's</span> <span m="768">finish</span> <span m="1197">up</span>
  <span m="1626">by</span> <span m="2055">looking</span> <span m="2484">at</span>
  <span m="2913">two</span> <span m="3342">extended</span> <span m="3771">examples.</span></p><p><span
  m="4200">The</span> <span m="4550">scenario</span> <span m="4901">for</span> <span
  m="5252">both</span> <span m="5602">examples</span> <span m="5953">is</span> <span
  m="6304">the</span> <span m="6655">control</span> <span m="7005">system</span> <span
  m="7356">for</span> <span m="7707">the</span> <span m="8057">International</span>
  <span m="8408">Space</span> <span m="8759">Station,</span> <span m="9110">which</span>
  <span m="9625">has</span> <span m="10140">to</span> <span m="10656">handle</span>
  <span m="11171">three</span> <span m="11686">recurring</span> <span m="12202">tasks:</span>
  <span m="12717">supply</span> <span m="13233">ship</span> <span m="13748">guidance</span>
  <span m="14263">(SSG),</span> <span m="14779">gyroscope</span> <span m="15294">control</span>
  <span m="15810">(G),</span> <span m="16488">and</span> <span m="17166">cabin</span>
  <span m="17844">pressure</span> <span m="18522">(CP).</span></p><p><span m="19200">For</span>
  <span m="19549">each</span> <span m="19898">device,</span> <span m="20247">the</span>
  <span m="20597">table</span> <span m="20946">shows</span> <span m="21295">us</span>
  <span m="21645">the</span> <span m="21994">time</span> <span m="22343">between</span>
  <span m="22692">successive</span> <span m="23042">requests</span> <span m="23391">(the</span>
  <span m="23740">period),</span> <span m="24090">the</span> <span m="24490">service</span>
  <span m="24891">time</span> <span m="25292">for</span> <span m="25693">each</span>
  <span m="26093">request,</span> <span m="26494">and</span> <span m="26895">the</span>
  <span m="27296">service</span> <span m="27696">deadline</span> <span m="28097">for</span>
  <span m="28498">each</span> <span m="28899">request.</span></p><p><span m="29300">We'll</span>
  <span m="29700">first</span> <span m="30101">analyze</span> <span m="30502">the</span>
  <span m="30903">system</span> <span m="31303">assuming</span> <span m="31704">that</span>
  <span m="32105">it's</span> <span m="32506">using</span> <span m="32906">a</span>
  <span m="33307">weak</span> <span m="33708">priority</span> <span m="34109">system.</span></p><p><span
  m="34510">First</span> <span m="34843">question:</span> <span m="35176">What</span>
  <span m="35510">is</span> <span m="35843">the</span> <span m="36176">maximum</span>
  <span m="36510">service</span> <span m="36843">time</span> <span m="37176">for</span>
  <span m="37510">the</span> <span m="37843">cabin</span> <span m="38176">pressure</span>
  <span m="38510">task</span> <span m="38843">that</span> <span m="39176">still</span>
  <span m="39510">allows</span> <span m="39968">all</span> <span m="40426">constraints</span>
  <span m="40885">to</span> <span m="41343">be</span> <span m="41801">met?</span></p><p><span
  m="42260">Well,</span> <span m="42676">the</span> <span m="43093">SSG</span> <span
  m="43510">task</span> <span m="43927">has</span> <span m="44344">a</span> <span
  m="44761">maximum</span> <span m="45178">allowable</span> <span m="45595">latency</span>
  <span m="46011">of</span> <span m="46428">20</span> <span m="46845">ms,</span> <span
  m="47262">i.e.,</span> <span m="47679">it's</span> <span m="48096">service</span>
  <span m="48513">routine</span> <span m="48930">must</span> <span m="49409">start</span>
  <span m="49888">execution</span> <span m="50368">within</span> <span m="50847">20</span>
  <span m="51326">ms</span> <span m="51806">if</span> <span m="52285">it</span> <span
  m="52764">is</span> <span m="53244">to</span> <span m="53723">meet</span> <span
  m="54202">its</span> <span m="54682">25</span> <span m="55161">ms</span> <span m="55640">deadline.</span></p><p><span
  m="56120">The</span> <span m="56504">G</span> <span m="56889">task</span> <span
  m="57274">has</span> <span m="57658">a</span> <span m="58043">maximum</span> <span
  m="58428">allowable</span> <span m="58812">latency</span> <span m="59197">of</span>
  <span m="59582">10</span> <span m="59967">ms</span> <span m="60351">if</span> <span
  m="60736">it's</span> <span m="61121">to</span> <span m="61505">meet</span> <span
  m="61890">its</span> <span m="62275">deadline.</span></p><p><span m="62660">So</span>
  <span m="63033">no</span> <span m="63407">other</span> <span m="63781">handler</span>
  <span m="64155">can</span> <span m="64529">take</span> <span m="64903">longer</span>
  <span m="65277">than</span> <span m="65651">10</span> <span m="66025">ms</span>
  <span m="66399">to</span> <span m="66773">run</span> <span m="67147">or</span> <span
  m="67521">the</span> <span m="67895">G</span> <span m="68269">task</span> <span
  m="68643">will</span> <span m="69017">miss</span> <span m="69391">its</span> <span
  m="69765">deadline.</span></p><p><span m="70139">2.</span></p><p><span m="71579">Give</span>
  <span m="72112">a</span> <span m="72645">weak</span> <span m="73179">priority</span>
  <span m="73712">ordering</span> <span m="74246">that</span> <span m="74779">meets</span>
  <span m="75313">the</span> <span m="75846">constraints.</span></p><p><span m="76380">Using</span>
  <span m="76696">the</span> <span m="77012">earliest</span> <span m="77329">deadline</span>
  <span m="77645">strategy</span> <span m="77962">discussed</span> <span m="78278">earlier,</span>
  <span m="78595">the</span> <span m="78911">priority</span> <span m="79227">would</span>
  <span m="79544">be</span> <span m="79860">G</span> <span m="80177">with</span> <span
  m="80493">the</span> <span m="80810">highest</span> <span m="81316">priority,</span>
  <span m="81823">SSG</span> <span m="82330">with</span> <span m="82837">the</span>
  <span m="83344">middle</span> <span m="83851">priority,</span> <span m="84357">and</span>
  <span m="84864">CP</span> <span m="85371">with</span> <span m="85878">the</span>
  <span m="86385">lowest</span> <span m="86892">priority.</span></p><p><span m="87399">3.</span></p><p><span
  m="88499">What</span> <span m="88962">fraction</span> <span m="89425">of</span>
  <span m="89889">time</span> <span m="90352">will</span> <span m="90815">the</span>
  <span m="91279">processor</span> <span m="91742">spend</span> <span m="92205">idle?</span></p><p><span
  m="92669">We</span> <span m="92967">need</span> <span m="93266">to</span> <span
  m="93565">compute</span> <span m="93864">the</span> <span m="94163">fraction</span>
  <span m="94461">of</span> <span m="94760">CPU</span> <span m="95059">cycles</span>
  <span m="95358">needed</span> <span m="95657">to</span> <span m="95955">service</span>
  <span m="96254">the</span> <span m="96553">recurring</span> <span m="96852">requests</span>
  <span m="97151">for</span> <span m="97450">each</span> <span m="98169">task.</span></p><p><span
  m="98889">SSG</span> <span m="99673">takes</span> <span m="100458">5/30</span> <span
  m="101242">=</span> <span m="102027">16.67%</span> <span m="102811">of</span> <span
  m="103596">the</span> <span m="104380">CPU</span> <span m="105165">cycles.</span></p><p><span
  m="105950">G</span> <span m="106451">takes</span> <span m="106952">10/40</span>
  <span m="107453">=</span> <span m="107954">25%</span> <span m="108455">of</span>
  <span m="108956">the</span> <span m="109457">CPU</span> <span m="109958">cycles.</span></p><p><span
  m="110459">And</span> <span m="110925">CP</span> <span m="111391">takes</span> <span
  m="111857">10/100</span> <span m="112323">=</span> <span m="112789">10%</span> <span
  m="113255">of</span> <span m="113721">the</span> <span m="114187">CPU</span> <span
  m="114653">cycles.</span></p><p><span m="115119">So</span> <span m="115590">servicing</span>
  <span m="116061">the</span> <span m="116533">task</span> <span m="117004">requests</span>
  <span m="117475">takes</span> <span m="117947">51.67%</span> <span m="118418">of</span>
  <span m="118889">the</span> <span m="119361">cycles,</span> <span m="119832">leaving</span>
  <span m="120303">48.33%</span> <span m="120775">of</span> <span m="121246">the</span>
  <span m="121717">cycles</span> <span m="122189">unused.</span></p><p><span m="123679">So</span>
  <span m="123901">the</span> <span m="124123">astronauts</span> <span m="124345">will</span>
  <span m="124567">be</span> <span m="124789">able</span> <span m="125011">to</span>
  <span m="125234">play</span> <span m="125456">Minecraft</span> <span m="125678">in</span>
  <span m="125900">their</span> <span m="126122">spare</span> <span m="126344">time</span>
  <span m="126566">:)</span> <span m="126789">4.</span></p><p><span m="128560">What</span>
  <span m="128985">is</span> <span m="129410">the</span> <span m="129835">worst-case</span>
  <span m="130260">delay</span> <span m="130685">for</span> <span m="131110">each</span>
  <span m="131535">task</span> <span m="131960">until</span> <span m="132385">completion</span>
  <span m="132810">of</span> <span m="133235">its</span> <span m="133660">service</span>
  <span m="134085">routine?</span></p><p><span m="134510">Each</span> <span m="134871">task</span>
  <span m="135232">might</span> <span m="135594">have</span> <span m="135955">to</span>
  <span m="136316">wait</span> <span m="136678">for</span> <span m="137039">the</span>
  <span m="137400">longest-running</span> <span m="137762">lower-priority</span> <span
  m="138123">handler</span> <span m="138484">to</span> <span m="138846">complete</span>
  <span m="139207">plus</span> <span m="139568">the</span> <span m="139930">service</span>
  <span m="140378">times</span> <span m="140827">of</span> <span m="141275">any</span>
  <span m="141724">other</span> <span m="142172">higher-priority</span> <span m="142621">tasks</span>
  <span m="143069">plus,</span> <span m="143518">of</span> <span m="143966">course,</span>
  <span m="144415">its</span> <span m="144863">own</span> <span m="145312">service</span>
  <span m="145760">time.</span></p><p><span m="146209">SSG</span> <span m="146552">has</span>
  <span m="146896">the</span> <span m="147240">lowest</span> <span m="147583">priority,</span>
  <span m="147927">so</span> <span m="148271">it</span> <span m="148614">might</span>
  <span m="148958">have</span> <span m="149302">to</span> <span m="149645">wait</span>
  <span m="149989">for</span> <span m="150333">CP</span> <span m="150676">and</span>
  <span m="151020">G</span> <span m="151364">to</span> <span m="151707">complete</span>
  <span m="152051">(a</span> <span m="152395">total</span> <span m="152739">of</span>
  <span m="153180">20</span> <span m="153622">ms),</span> <span m="154064">then</span>
  <span m="154506">add</span> <span m="154948">its</span> <span m="155389">own</span>
  <span m="155831">service</span> <span m="156273">time</span> <span m="156715">(5</span>
  <span m="157157">ms).</span></p><p><span m="157599">So</span> <span m="158100">it's</span>
  <span m="158602">worst-case</span> <span m="159104">completion</span> <span m="159606">time</span>
  <span m="160108">is</span> <span m="160610">25</span> <span m="161112">ms</span>
  <span m="161614">after</span> <span m="162116">the</span> <span m="162618">request.</span></p><p><span
  m="163120">G</span> <span m="163452">might</span> <span m="163785">to</span> <span
  m="164117">wait</span> <span m="164450">for</span> <span m="164782">CP</span> <span
  m="165115">to</span> <span m="165448">complete</span> <span m="165780">(10</span>
  <span m="166113">ms),</span> <span m="166445">then</span> <span m="166778">add</span>
  <span m="167110">its</span> <span m="167443">own</span> <span m="167776">service</span>
  <span m="168108">time</span> <span m="168441">(10</span> <span m="168773">ms)</span>
  <span m="169106">for</span> <span m="169439">a</span> <span m="169625">worst-case</span>
  <span m="169811">completion</span> <span m="169997">time</span> <span m="170183">of</span>
  <span m="170369">20</span> <span m="170555">ms.</span></p><p><span m="170741">CP</span>
  <span m="171224">might</span> <span m="171708">have</span> <span m="172191">to</span>
  <span m="172675">wait</span> <span m="173158">for</span> <span m="173642">SSG</span>
  <span m="174125">to</span> <span m="174609">finish</span> <span m="175092">(5</span>
  <span m="175576">ms),</span> <span m="176059">then</span> <span m="176543">wait</span>
  <span m="177026">for</span> <span m="177510">G</span> <span m="177993">to</span>
  <span m="178477">run</span> <span m="178960">(10</span> <span m="179444">ms),</span>
  <span m="179927">then</span> <span m="180411">add</span> <span m="180915">its</span>
  <span m="181420">own</span> <span m="181924">service</span> <span m="182429">time</span>
  <span m="182934">(10</span> <span m="183438">ms)</span> <span m="183943">for</span>
  <span m="184447">a</span> <span m="184952">worst-case</span> <span m="185457">completion</span>
  <span m="185961">time</span> <span m="186466">of</span> <span m="186970">25</span>
  <span m="187475">ms.</span></p><p><span m="187980">Let's</span> <span m="188313">redo</span>
  <span m="188647">the</span> <span m="188980">problem,</span> <span m="189314">this</span>
  <span m="189647">timing</span> <span m="189981">assuming</span> <span m="190315">a</span>
  <span m="190648">strong</span> <span m="190982">priority</span> <span m="191315">system</span>
  <span m="191649">where,</span> <span m="191982">as</span> <span m="192316">before,</span>
  <span m="192650">G</span> <span m="193167">has</span> <span m="193684">the</span>
  <span m="194201">highest</span> <span m="194718">priority,</span> <span m="195235">SSG</span>
  <span m="195752">the</span> <span m="196270">middle</span> <span m="196787">priority,</span>
  <span m="197304">and</span> <span m="197821">CP</span> <span m="198338">the</span>
  <span m="198855">lowest</span> <span m="199372">priority.</span></p><p><span m="199890">What</span>
  <span m="200265">is</span> <span m="200641">the</span> <span m="201016">maximum</span>
  <span m="201392">service</span> <span m="201768">time</span> <span m="202143">for</span>
  <span m="202519">CP</span> <span m="202895">that</span> <span m="203270">still</span>
  <span m="203646">allows</span> <span m="204021">all</span> <span m="204397">constraints</span>
  <span m="204773">to</span> <span m="205148">be</span> <span m="205524">met?</span></p><p><span
  m="205900">This</span> <span m="206189">calculation</span> <span m="206479">is</span>
  <span m="206769">different</span> <span m="207059">in</span> <span m="207349">a</span>
  <span m="207639">strong</span> <span m="207929">priority</span> <span m="208219">system,</span>
  <span m="208509">since</span> <span m="208799">the</span> <span m="209089">service</span>
  <span m="209379">time</span> <span m="209669">of</span> <span m="209959">CP</span>
  <span m="210328">is</span> <span m="210697">no</span> <span m="211066">longer</span>
  <span m="211436">constrained</span> <span m="211805">by</span> <span m="212174">the</span>
  <span m="212544">maximum</span> <span m="212913">allowable</span> <span m="213282">latency</span>
  <span m="213651">of</span> <span m="214021">the</span> <span m="214390">higher-priority</span>
  <span m="214759">tasks</span> <span m="215129">-</span> <span m="215425">they'll</span>
  <span m="215722">simply</span> <span m="216019">preempt</span> <span m="216316">CP</span>
  <span m="216612">when</span> <span m="216909">they</span> <span m="217206">need</span>
  <span m="217503">to</span> <span m="217800">run!</span></p><p><span m="219510">Instead</span>
  <span m="219801">we</span> <span m="220093">need</span> <span m="220384">to</span>
  <span m="220676">think</span> <span m="220967">about</span> <span m="221259">how</span>
  <span m="221550">much</span> <span m="221842">CPU</span> <span m="222133">time</span>
  <span m="222425">will</span> <span m="222716">be</span> <span m="223008">used</span>
  <span m="223299">by</span> <span m="223591">the</span> <span m="223882">SSG</span>
  <span m="224174">and</span> <span m="224465">G</span> <span m="224757">tasks</span>
  <span m="225048">in</span> <span m="225340">the</span> <span m="225879">100</span>
  <span m="226418">ms</span> <span m="226957">interval</span> <span m="227496">between</span>
  <span m="228035">the</span> <span m="228574">CP</span> <span m="229113">request</span>
  <span m="229652">and</span> <span m="230191">its</span> <span m="230730">deadline.</span></p><p><span
  m="231269">In</span> <span m="231706">a</span> <span m="232144">100</span> <span
  m="232582">ms</span> <span m="233020">interval,</span> <span m="233458">there</span>
  <span m="233896">might</span> <span m="234333">be</span> <span m="234771">four</span>
  <span m="235209">SSG</span> <span m="235647">requests</span> <span m="236085">(at</span>
  <span m="236523">times</span> <span m="236960">0,</span> <span m="237398">30,</span>
  <span m="237836">60,</span> <span m="238274">and</span> <span m="238712">90)</span>
  <span m="239150">and</span> <span m="239556">three</span> <span m="239963">G</span>
  <span m="240370">requests</span> <span m="240777">(at</span> <span m="241184">times</span>
  <span m="241591">0,</span> <span m="241998">40,</span> <span m="242405">and</span>
  <span m="242812">80).</span></p><p><span m="243219">Together</span> <span m="243714">these</span>
  <span m="244210">requests</span> <span m="244705">require</span> <span m="245201">a</span>
  <span m="245696">total</span> <span m="246192">of</span> <span m="246687">50</span>
  <span m="247183">ms</span> <span m="247678">to</span> <span m="248174">service.</span></p><p><span
  m="248670">So</span> <span m="249057">the</span> <span m="249444">service</span>
  <span m="249831">time</span> <span m="250218">for</span> <span m="250605">CP</span>
  <span m="250993">can</span> <span m="251380">be</span> <span m="251767">up</span>
  <span m="252154">50</span> <span m="252541">ms</span> <span m="252928">and</span>
  <span m="253316">still</span> <span m="253703">meet</span> <span m="254090">the</span>
  <span m="254477">100</span> <span m="254864">ms</span> <span m="255251">deadline.</span></p><p><span
  m="255639">2.</span></p><p><span m="256639">What</span> <span m="257078">fraction</span>
  <span m="257517">of</span> <span m="257956">the</span> <span m="258395">time</span>
  <span m="258834">will</span> <span m="259273">the</span> <span m="259712">processor</span>
  <span m="260151">spend</span> <span m="260590">idle?</span></p><p><span m="261029">Assuming</span>
  <span m="261416">a</span> <span m="261803">50</span> <span m="262191">ms</span>
  <span m="262578">service</span> <span m="262966">time</span> <span m="263353">for</span>
  <span m="263740">CP,</span> <span m="264128">it</span> <span m="264515">now</span>
  <span m="264903">consumes</span> <span m="265290">50%</span> <span m="265677">of</span>
  <span m="266065">the</span> <span m="266452">CPU.</span></p><p><span m="266840">The</span>
  <span m="267232">other</span> <span m="267625">request</span> <span m="268018">loads</span>
  <span m="268411">are</span> <span m="268804">as</span> <span m="269197">before,</span>
  <span m="269590">so</span> <span m="269983">91.67%</span> <span m="270376">of</span>
  <span m="270769">the</span> <span m="271162">CPU</span> <span m="271555">cycles</span>
  <span m="271948">will</span> <span m="272341">be</span> <span m="272734">spent</span>
  <span m="273127">servicing</span> <span m="273520">requests,</span> <span m="274151">leaving</span>
  <span m="274783">8.33%</span> <span m="275415">of</span> <span m="276046">idle</span>
  <span m="276678">time.</span></p><p><span m="277310">3.</span></p><p><span m="278310">What</span>
  <span m="278746">is</span> <span m="279183">the</span> <span m="279620">worst-case</span>
  <span m="280056">completion</span> <span m="280493">time</span> <span m="280930">for</span>
  <span m="281366">each</span> <span m="281803">task?</span></p><p><span m="282240">The</span>
  <span m="282554">G</span> <span m="282869">task</span> <span m="283184">has</span>
  <span m="283498">the</span> <span m="283813">highest</span> <span m="284128">priority,</span>
  <span m="284442">so</span> <span m="284757">its</span> <span m="285072">service</span>
  <span m="285386">routine</span> <span m="285701">runs</span> <span m="286016">immediately</span>
  <span m="286330">after</span> <span m="286645">the</span> <span m="286960">request</span>
  <span m="287407">is</span> <span m="287855">received</span> <span m="288303">and</span>
  <span m="288750">its</span> <span m="289198">worst-case</span> <span m="289646">completion</span>
  <span m="290093">time</span> <span m="290541">is</span> <span m="290989">exactly</span>
  <span m="291436">its</span> <span m="291884">service</span> <span m="292332">time.</span></p><p><span
  m="292780">In</span> <span m="293091">the</span> <span m="293403">25</span> <span
  m="293714">ms</span> <span m="294026">interval</span> <span m="294338">between</span>
  <span m="294649">an</span> <span m="294961">SSG</span> <span m="295272">request</span>
  <span m="295584">and</span> <span m="295896">its</span> <span m="296207">deadline,</span>
  <span m="296519">there</span> <span m="296830">might</span> <span m="297142">be</span>
  <span m="297454">at</span> <span m="297765">most</span> <span m="298077">one</span>
  <span m="298389">G</span> <span m="298889">request</span> <span m="299389">that</span>
  <span m="299889">will</span> <span m="300389">preempt</span> <span m="300889">execution.</span></p><p><span
  m="301389">So</span> <span m="301803">the</span> <span m="302217">worst-case</span>
  <span m="302632">completion</span> <span m="303046">time</span> <span m="303461">is</span>
  <span m="303875">one</span> <span m="304290">G</span> <span m="304704">service</span>
  <span m="305118">time</span> <span m="305533">(10</span> <span m="305947">ms)</span>
  <span m="306362">plus</span> <span m="306776">the</span> <span m="307191">SSG</span>
  <span m="307605">service</span> <span m="308020">time</span> <span m="308903">(5</span>
  <span m="309786">ms).</span></p><p><span m="310669">Finally,</span> <span m="311006">from</span>
  <span m="311344">the</span> <span m="311681">calculation</span> <span m="312019">for</span>
  <span m="312357">problem</span> <span m="312694">1,</span> <span m="313032">we</span>
  <span m="313370">chose</span> <span m="313707">the</span> <span m="314045">service</span>
  <span m="314382">time</span> <span m="314720">for</span> <span m="315058">the</span>
  <span m="315395">CP</span> <span m="315733">task</span> <span m="316071">so</span>
  <span m="316465">that</span> <span m="316860">it</span> <span m="317255">will</span>
  <span m="317650">complete</span> <span m="318045">just</span> <span m="318440">at</span>
  <span m="318835">its</span> <span m="319230">deadline</span> <span m="319625">of</span>
  <span m="320020">100</span> <span m="320415">ms,</span> <span m="320810">taking</span>
  <span m="321323">into</span> <span m="321836">account</span> <span m="322349">the</span>
  <span m="322862">service</span> <span m="323375">time</span> <span m="323888">for</span>
  <span m="324401">multiple</span> <span m="324914">higher-priority</span> <span m="325427">requests.</span></p><p><span
  m="325940">We</span> <span m="326251">covered</span> <span m="326562">a</span> <span
  m="326873">lot</span> <span m="327184">of</span> <span m="327495">ground</span>
  <span m="327806">in</span> <span m="328117">this</span> <span m="328428">lecture!</span></p><p><span
  m="328740">We</span> <span m="329082">saw</span> <span m="329425">that</span> <span
  m="329768">the</span> <span m="330111">computation</span> <span m="330453">needed</span>
  <span m="330796">for</span> <span m="331139">user-mode</span> <span m="331482">programs</span>
  <span m="331825">to</span> <span m="332167">interact</span> <span m="332510">with</span>
  <span m="332853">external</span> <span m="333196">devices</span> <span m="333539">was</span>
  <span m="333947">split</span> <span m="334355">into</span> <span m="334763">two</span>
  <span m="335171">parts.</span></p><p><span m="335580">On</span> <span m="335900">the</span>
  <span m="336221">device-side,</span> <span m="336542">the</span> <span m="336862">OS</span>
  <span m="337183">handles</span> <span m="337504">device</span> <span m="337825">interrupts</span>
  <span m="338145">and</span> <span m="338466">performs</span> <span m="338787">the</span>
  <span m="339107">task</span> <span m="339428">of</span> <span m="339749">moving</span>
  <span m="340070">data</span> <span m="340515">between</span> <span m="340961">kernel</span>
  <span m="341407">buffers</span> <span m="341852">and</span> <span m="342298">the</span>
  <span m="342744">device.</span></p><p><span m="343190">On</span> <span m="343637">the</span>
  <span m="344085">application</span> <span m="344533">side,</span> <span m="344981">user-mode</span>
  <span m="345429">programs</span> <span m="345877">access</span> <span m="346325">the</span>
  <span m="346772">information</span> <span m="347220">via</span> <span m="347668">SVC</span>
  <span m="348116">calls</span> <span m="348564">to</span> <span m="349012">the</span>
  <span m="349460">OS.</span></p><p><span m="351400">We</span> <span m="351688">worried</span>
  <span m="351977">about</span> <span m="352266">how</span> <span m="352555">to</span>
  <span m="352844">handle</span> <span m="353132">SVC</span> <span m="353421">requests</span>
  <span m="353710">that</span> <span m="353999">needed</span> <span m="354288">to</span>
  <span m="354577">wait</span> <span m="354865">for</span> <span m="355154">an</span>
  <span m="355443">I/O</span> <span m="355732">event</span> <span m="356021">before</span>
  <span m="356310">the</span> <span m="356748">request</span> <span m="357186">could</span>
  <span m="357624">be</span> <span m="358062">satisfied.</span></p><p><span m="358500">Ultimately</span>
  <span m="358884">we</span> <span m="359268">came</span> <span m="359652">up</span>
  <span m="360036">with</span> <span m="360421">a</span> <span m="360805">sleep/wakeup</span>
  <span m="361189">mechanism</span> <span m="361573">that</span> <span m="361957">suspends</span>
  <span m="362342">execution</span> <span m="362726">of</span> <span m="363110">the</span>
  <span m="363494">process</span> <span m="363879">until</span> <span m="364315">the</span>
  <span m="364752">some</span> <span m="365189">interrupt</span> <span m="365626">routine</span>
  <span m="366062">signals</span> <span m="366499">that</span> <span m="366936">the</span>
  <span m="367373">needed</span> <span m="367809">information</span> <span m="368246">has</span>
  <span m="368683">arrived,</span> <span m="369120">causing</span> <span m="369618">the</span>
  <span m="370117">sleeping</span> <span m="370616">process</span> <span m="371115">to</span>
  <span m="371613">marked</span> <span m="372112">as</span> <span m="372611">active.</span></p><p><span
  m="373110">Then</span> <span m="373554">the</span> <span m="373999">SVC</span> <span
  m="374444">is</span> <span m="374889">retried</span> <span m="375334">the</span>
  <span m="375779">next</span> <span m="376224">time</span> <span m="376669">the</span>
  <span m="377114">now</span> <span m="377559">active</span> <span m="378004">process</span>
  <span m="378449">is</span> <span m="378894">scheduled</span> <span m="379339">for</span>
  <span m="379784">execution.</span></p><p><span m="380229">We</span> <span m="380687">discussed</span>
  <span m="381145">hard</span> <span m="381604">real-time</span> <span m="382062">constraints</span>
  <span m="382520">with</span> <span m="382979">their</span> <span m="383437">latencies,</span>
  <span m="383895">service</span> <span m="384354">times</span> <span m="384812">and</span>
  <span m="385270">deadlines.</span></p><p><span m="385729">Then</span> <span m="386199">we</span>
  <span m="386669">explored</span> <span m="387139">the</span> <span m="387609">implementation</span>
  <span m="388079">of</span> <span m="388549">interrupt</span> <span m="389019">systems</span>
  <span m="389489">using</span> <span m="389959">both</span> <span m="390429">weak</span>
  <span m="390899">and</span> <span m="391369">strong</span> <span m="391839">priorities.</span></p><p><span
  m="392310">Real-life</span> <span m="392695">computer</span> <span m="393081">systems</span>
  <span m="393467">usually</span> <span m="393853">implement</span> <span m="394239">strong</span>
  <span m="394625">priorities</span> <span m="395010">and</span> <span m="395396">support</span>
  <span m="395782">a</span> <span m="396168">modest</span> <span m="396554">number</span>
  <span m="396940">of</span> <span m="397206">priority</span> <span m="397472">levels,</span>
  <span m="397739">using</span> <span m="398005">a</span> <span m="398271">weak</span>
  <span m="398538">priority</span> <span m="398804">system</span> <span m="399070">to</span>
  <span m="399337">deal</span> <span m="399603">with</span> <span m="399870">multiple</span>
  <span m="400387">devices</span> <span m="400905">assigned</span> <span m="401423">to</span>
  <span m="401941">the</span> <span m="402458">same</span> <span m="402976">strong</span>
  <span m="403494">priority</span> <span m="404012">level.</span></p><p><span m="404530">This</span>
  <span m="404779">seems</span> <span m="405028">to</span> <span m="405278">work</span>
  <span m="405527">quite</span> <span m="405776">well</span> <span m="406026">in</span>
  <span m="406275">practice,</span> <span m="406525">allowing</span> <span m="406774">the</span>
  <span m="407023">systems</span> <span m="407273">to</span> <span m="407522">meet</span>
  <span m="407771">the</span> <span m="408021">variety</span> <span m="408270">of</span>
  <span m="408520">real-time</span> <span m="408928">constraints</span> <span m="409337">imposed</span>
  <span m="409745">by</span> <span m="410154">their</span> <span m="410562">I/O</span>
  <span m="410971">devices.</span></p>
type: course
uid: 285358a1a7d1edd254363c1b22da8cf8

---
None