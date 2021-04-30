---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: RrZ8-1w7iok
  parent_uid: 502171c8b3174031b76bc8a712f568e4
  title: Video-YouTube-Stream
  type: Video
  uid: 7c2f1688a669d80102b20fc38c374d39
- id: 3Play-3Play YouTube id-Stream
  media_location: RrZ8-1w7iok
  parent_uid: 502171c8b3174031b76bc8a712f568e4
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: bc5826dd24f7d857b542bbf4171adcfb
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/RrZ8-1w7iok/default.jpg
  parent_uid: 502171c8b3174031b76bc8a712f568e4
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 8b8a5d1415a55ba0d6cdd3060c7d95df
- id: RrZ8-1w7iok.srt
  parent_uid: 502171c8b3174031b76bc8a712f568e4
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v3/page-faults-6-47-/RrZ8-1w7iok.srt
  title: 3play caption file
  type: null
  uid: b03c196553e3bf99b0ac13e2cef9e78a
- id: RrZ8-1w7iok.pdf
  parent_uid: 502171c8b3174031b76bc8a712f568e4
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v3/page-faults-6-47-/RrZ8-1w7iok.pdf
  title: 3play pdf file
  type: null
  uid: 24222b53ff1c3f7b3076d1417318b6bc
- id: Caption-3Play YouTube id-SRT
  parent_uid: 502171c8b3174031b76bc8a712f568e4
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: e8e5fefcc55087f4f9e6821d45854c17
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 502171c8b3174031b76bc8a712f568e4
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 1ac20db544b86712a6be100d92d8012f
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_16-02-03_300k.mp4
  parent_uid: 502171c8b3174031b76bc8a712f568e4
  title: Video-Internet Archive-MP4
  type: Video
  uid: 17a1c4a09571f10d25464aada4c5c554
inline_embed_id: 98597013pagefaults64776690835
layout: video
order_index: null
parent_uid: 9fb6446111ce9f3461e980cf96845187
related_resources_text: ''
short_url: page-faults-6-47-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v3/page-faults-6-47-
template_type: Embed
title: Page Faults
transcript: <p><span m="1490">Let's</span> <span m="1908">review</span> <span m="2327">what</span>
  <span m="2745">happens</span> <span m="3164">when</span> <span m="3583">the</span>
  <span m="4001">CPU</span> <span m="4420">accesses</span> <span m="4838">a</span>
  <span m="5257">non-resident</span> <span m="5676">virtual</span> <span m="6094">page,</span>
  <span m="6513">i.e.,</span> <span m="6931">a</span> <span m="7350">page</span> <span
  m="7769">with</span> <span m="8226">its</span> <span m="8683">resident</span> <span
  m="9140">bit</span> <span m="9598">set</span> <span m="10055">to</span> <span m="10512">0.</span></p><p><span
  m="10970">In</span> <span m="11334">the</span> <span m="11699">example</span> <span
  m="12064">shown</span> <span m="12429">here,</span> <span m="12794">the</span> <span
  m="13159">CPU</span> <span m="13524">is</span> <span m="13889">trying</span> <span
  m="14254">to</span> <span m="14619">access</span> <span m="14984">virtual</span>
  <span m="15349">page</span> <span m="15714">5.</span></p><p><span m="16079">In</span>
  <span m="16465">this</span> <span m="16851">case,</span> <span m="17237">the</span>
  <span m="17624">MMU</span> <span m="18010">signals</span> <span m="18396">a</span>
  <span m="18783">page</span> <span m="19169">fault</span> <span m="19555">exception,</span>
  <span m="19942">causing</span> <span m="20328">the</span> <span m="20714">CPU</span>
  <span m="21101">to</span> <span m="21487">suspend</span> <span m="21873">execution</span>
  <span m="22260">of</span> <span m="22545">the</span> <span m="22831">program</span>
  <span m="23117">and</span> <span m="23403">switch</span> <span m="23689">to</span>
  <span m="23975">the</span> <span m="24261">page</span> <span m="24547">fault</span>
  <span m="24832">handler,</span> <span m="25118">which</span> <span m="25404">is</span>
  <span m="25690">code</span> <span m="25976">that</span> <span m="26262">deals</span>
  <span m="26548">with</span> <span m="26834">the</span> <span m="27120">page</span>
  <span m="28065">fault.</span></p><p><span m="29010">The</span> <span m="29404">handler</span>
  <span m="29799">starts</span> <span m="30194">by</span> <span m="30588">either</span>
  <span m="30983">finding</span> <span m="31378">an</span> <span m="31772">unused</span>
  <span m="32167">physical</span> <span m="32562">page</span> <span m="32956">or,</span>
  <span m="33351">if</span> <span m="33746">necessary,</span> <span m="34140">creating</span>
  <span m="34535">an</span> <span m="34930">unused</span> <span m="35407">page</span>
  <span m="35884">by</span> <span m="36361">selecting</span> <span m="36839">an</span>
  <span m="37316">in-use</span> <span m="37793">page</span> <span m="38270">and</span>
  <span m="38748">making</span> <span m="39225">it</span> <span m="39702">available.</span></p><p><span
  m="40180">In</span> <span m="40584">our</span> <span m="40988">example,</span> <span
  m="41392">the</span> <span m="41796">handler</span> <span m="42200">has</span> <span
  m="42605">chosen</span> <span m="43009">virtual</span> <span m="43413">page</span>
  <span m="43817">1</span> <span m="44221">for</span> <span m="44625">reuse.</span></p><p><span
  m="45030">If</span> <span m="45355">the</span> <span m="45681">selected</span> <span
  m="46007">page</span> <span m="46333">is</span> <span m="46659">dirty,</span> <span
  m="46985">i.e.,</span> <span m="47311">its</span> <span m="47637">D</span> <span
  m="47962">bit</span> <span m="48288">is</span> <span m="48614">1</span> <span m="48940">indicating</span>
  <span m="49266">that</span> <span m="49592">its</span> <span m="49918">contents</span>
  <span m="50244">have</span> <span m="50570">changed</span> <span m="51014">since</span>
  <span m="51459">being</span> <span m="51903">read</span> <span m="52348">from</span>
  <span m="52793">secondary</span> <span m="53237">storage,</span> <span m="53682">write</span>
  <span m="54126">it</span> <span m="54571">back</span> <span m="55016">to</span>
  <span m="55460">secondary</span> <span m="55905">storage.</span></p><p><span m="56350">Finally,</span>
  <span m="56919">mark</span> <span m="57488">the</span> <span m="58057">selected</span>
  <span m="58626">virtual</span> <span m="59195">page</span> <span m="59764">as</span>
  <span m="60333">no</span> <span m="60902">longer</span> <span m="61471">resident.</span></p><p><span
  m="62040">In</span> <span m="62362">the</span> <span m="62685">&quot;after&quot;</span>
  <span m="63007">figure,</span> <span m="63330">we</span> <span m="63653">see</span>
  <span m="63975">that</span> <span m="64298">the</span> <span m="64621">R</span>
  <span m="64943">bit</span> <span m="65266">for</span> <span m="65588">virtual</span>
  <span m="65911">page</span> <span m="66234">1</span> <span m="66556">has</span>
  <span m="66879">been</span> <span m="67202">set</span> <span m="67524">to</span>
  <span m="67847">0.</span></p><p><span m="68170">Now</span> <span m="68748">physical</span>
  <span m="69327">page</span> <span m="69905">4</span> <span m="70484">is</span> <span
  m="71063">available</span> <span m="71641">for</span> <span m="72220">re-use.</span></p><p><span
  m="72799">Are</span> <span m="73194">there</span> <span m="73589">any</span> <span
  m="73984">restrictions</span> <span m="74379">on</span> <span m="74774">which</span>
  <span m="75169">page</span> <span m="75564">we</span> <span m="75959">can</span>
  <span m="76354">select?</span></p><p><span m="76749">Obviously,</span> <span m="77080">we</span>
  <span m="77411">can't</span> <span m="77743">select</span> <span m="78074">the</span>
  <span m="78405">page</span> <span m="78737">that</span> <span m="79068">holds</span>
  <span m="79399">the</span> <span m="79731">code</span> <span m="80062">for</span>
  <span m="80393">the</span> <span m="80725">page</span> <span m="81056">fault</span>
  <span m="81387">handler.</span></p><p><span m="81719">Pages</span> <span m="82241">immune</span>
  <span m="82764">from</span> <span m="83286">selection</span> <span m="83809">are</span>
  <span m="84331">called</span> <span m="84854">&quot;wired&quot;</span> <span m="85376">pages.</span></p><p><span
  m="85899">And</span> <span m="86145">it</span> <span m="86392">would</span> <span
  m="86638">very</span> <span m="86885">inefficient</span> <span m="87131">to</span>
  <span m="87378">choose</span> <span m="87624">the</span> <span m="87871">page</span>
  <span m="88117">that</span> <span m="88364">holds</span> <span m="88610">the</span>
  <span m="88857">code</span> <span m="89103">that</span> <span m="89350">made</span>
  <span m="89596">the</span> <span m="89843">initial</span> <span m="90090">memory</span>
  <span m="90402">access,</span> <span m="90714">since</span> <span m="91026">we</span>
  <span m="91339">expect</span> <span m="91651">to</span> <span m="91963">start</span>
  <span m="92276">executing</span> <span m="92588">that</span> <span m="92900">code</span>
  <span m="93212">as</span> <span m="93525">soon</span> <span m="93837">as</span>
  <span m="94149">we</span> <span m="94462">finish</span> <span m="94774">handling</span>
  <span m="95086">the</span> <span m="95399">page</span> <span m="96189">fault.</span></p><p><span
  m="96979">The</span> <span m="97262">optimal</span> <span m="97546">strategy</span>
  <span m="97830">would</span> <span m="98114">be</span> <span m="98398">to</span>
  <span m="98681">choose</span> <span m="98965">the</span> <span m="99249">page</span>
  <span m="99533">whose</span> <span m="99817">next</span> <span m="100100">use</span>
  <span m="100384">will</span> <span m="100668">occur</span> <span m="100952">farthest</span>
  <span m="101236">in</span> <span m="101520">the</span> <span m="102020">future.</span></p><p><span
  m="102520">But,</span> <span m="102928">of</span> <span m="103337">course,</span>
  <span m="103745">this</span> <span m="104154">involves</span> <span m="104563">knowledge</span>
  <span m="104971">of</span> <span m="105380">future</span> <span m="105788">execution</span>
  <span m="106197">paths</span> <span m="106606">and</span> <span m="107014">so</span>
  <span m="107423">isn't</span> <span m="107831">a</span> <span m="108240">realizable</span>
  <span m="108649">strategy.</span></p><p><span m="110229">Wikipedia</span> <span
  m="110581">provides</span> <span m="110933">a</span> <span m="111286">nice</span>
  <span m="111638">description</span> <span m="111990">of</span> <span m="112343">the</span>
  <span m="112695">many</span> <span m="113048">strategies</span> <span m="113400">for</span>
  <span m="113752">choosing</span> <span m="114105">a</span> <span m="114457">replacement</span>
  <span m="114810">page,</span> <span m="115178">with</span> <span m="115547">their</span>
  <span m="115915">various</span> <span m="116284">tradeoffs</span> <span m="116652">between</span>
  <span m="117021">ease</span> <span m="117389">of</span> <span m="117758">implementation</span>
  <span m="118126">and</span> <span m="118495">impact</span> <span m="118863">on</span>
  <span m="119232">the</span> <span m="119600">rate</span> <span m="119969">of</span>
  <span m="120331">page</span> <span m="120694">faults</span> <span m="121057">-</span>
  <span m="121420">see</span> <span m="121783">the</span> <span m="122146">URL</span>
  <span m="122509">given</span> <span m="122871">at</span> <span m="123234">the</span>
  <span m="123597">bottom</span> <span m="123960">of</span> <span m="124323">the</span>
  <span m="124686">slide.</span></p><p><span m="125049">The</span> <span m="125458">aging</span>
  <span m="125867">algorithm</span> <span m="126277">they</span> <span m="126686">describe</span>
  <span m="127095">is</span> <span m="127505">frequently</span> <span m="127914">used</span>
  <span m="128323">since</span> <span m="128733">it</span> <span m="129142">offers</span>
  <span m="129551">near</span> <span m="129961">optimal</span> <span m="130370">performance</span>
  <span m="130780">at</span> <span m="131468">a</span> <span m="132156">moderate</span>
  <span m="132844">implementation</span> <span m="133532">cost.</span></p><p><span
  m="134220">Next,</span> <span m="134658">the</span> <span m="135097">desired</span>
  <span m="135535">virtual</span> <span m="135974">page</span> <span m="136412">is</span>
  <span m="136851">read</span> <span m="137290">from</span> <span m="137728">secondary</span>
  <span m="138167">storage</span> <span m="138605">into</span> <span m="139044">the</span>
  <span m="139482">selected</span> <span m="139921">physical</span> <span m="140360">page.</span></p><p><span
  m="141360">In</span> <span m="141749">our</span> <span m="142138">example,</span>
  <span m="142527">virtual</span> <span m="142916">page</span> <span m="143306">5</span>
  <span m="143695">is</span> <span m="144084">now</span> <span m="144473">loaded</span>
  <span m="144863">into</span> <span m="145252">physical</span> <span m="145641">page</span>
  <span m="146030">4.</span></p><p><span m="146420">Then</span> <span m="146723">the</span>
  <span m="147027">R</span> <span m="147331">bit</span> <span m="147635">and</span>
  <span m="147939">PPN</span> <span m="148243">fields</span> <span m="148547">in</span>
  <span m="148851">the</span> <span m="149155">page</span> <span m="149458">table</span>
  <span m="149762">entry</span> <span m="150066">for</span> <span m="150370">virtual</span>
  <span m="150674">page</span> <span m="150978">5</span> <span m="151282">are</span>
  <span m="151586">updated</span> <span m="151890">to</span> <span m="152308">indicate</span>
  <span m="152727">that</span> <span m="153146">the</span> <span m="153564">contents</span>
  <span m="153983">of</span> <span m="154402">that</span> <span m="154820">virtual</span>
  <span m="155239">page</span> <span m="155658">now</span> <span m="156076">reside</span>
  <span m="156495">in</span> <span m="156914">physical</span> <span m="157332">page</span>
  <span m="157751">4.</span></p><p><span m="158170">Finally</span> <span m="158588">the</span>
  <span m="159007">handler</span> <span m="159425">is</span> <span m="159844">finished</span>
  <span m="160262">and</span> <span m="160681">execution</span> <span m="161100">of</span>
  <span m="161518">the</span> <span m="161937">original</span> <span m="162355">program</span>
  <span m="162774">is</span> <span m="163192">resumed,</span> <span m="163611">re-executing</span>
  <span m="164030">the</span> <span m="164492">instruction</span> <span m="164955">that</span>
  <span m="165418">caused</span> <span m="165881">the</span> <span m="166344">page</span>
  <span m="166807">fault.</span></p><p><span m="167270">Since</span> <span m="167722">the</span>
  <span m="168174">page</span> <span m="168626">map</span> <span m="169078">has</span>
  <span m="169530">been</span> <span m="169982">updated,</span> <span m="170434">this</span>
  <span m="170886">time</span> <span m="171338">the</span> <span m="171790">access</span>
  <span m="172242">succeeds</span> <span m="172694">and</span> <span m="173146">execution</span>
  <span m="173598">continues.</span></p><p><span m="174050">To</span> <span m="174466">double-check</span>
  <span m="174883">our</span> <span m="175300">understanding</span> <span m="175716">of</span>
  <span m="176133">page</span> <span m="176550">faults,</span> <span m="176966">let's</span>
  <span m="177383">run</span> <span m="177800">through</span> <span m="178216">an</span>
  <span m="178633">example.</span></p><p><span m="179050">Here's</span> <span m="179380">the</span>
  <span m="179710">same</span> <span m="180040">setup</span> <span m="180370">as</span>
  <span m="180700">in</span> <span m="181030">our</span> <span m="181360">previous</span>
  <span m="181690">example,</span> <span m="182020">but</span> <span m="182350">this</span>
  <span m="182680">time</span> <span m="183010">consider</span> <span m="183340">a</span>
  <span m="183670">store</span> <span m="184000">instruction</span> <span m="184330">that's</span>
  <span m="184901">making</span> <span m="185472">an</span> <span m="186044">access</span>
  <span m="186615">to</span> <span m="187186">virtual</span> <span m="187758">address</span>
  <span m="188329">0x600,</span> <span m="188900">which</span> <span m="189472">is</span>
  <span m="190043">located</span> <span m="190614">on</span> <span m="191186">virtual</span>
  <span m="191757">page</span> <span m="192328">6.</span></p><p><span m="192900">Checking</span>
  <span m="193205">the</span> <span m="193511">page</span> <span m="193817">table</span>
  <span m="194123">entry</span> <span m="194428">for</span> <span m="194734">VPN</span>
  <span m="195040">6,</span> <span m="195346">we</span> <span m="195652">see</span>
  <span m="195957">that</span> <span m="196263">its</span> <span m="196569">R</span>
  <span m="196875">bit</span> <span m="197181">0</span> <span m="197486">indicating</span>
  <span m="197792">that</span> <span m="198098">it</span> <span m="198404">is</span>
  <span m="198710">NOT</span> <span m="199141">resident</span> <span m="199573">in</span>
  <span m="200005">main</span> <span m="200437">memory,</span> <span m="200869">which</span>
  <span m="201300">causes</span> <span m="201732">a</span> <span m="202164">page</span>
  <span m="202596">fault</span> <span m="203028">exception.</span></p><p><span m="203460">The</span>
  <span m="203746">page</span> <span m="204033">fault</span> <span m="204320">handler</span>
  <span m="204607">selects</span> <span m="204894">VPN</span> <span m="205181">0xE</span>
  <span m="205468">for</span> <span m="205755">replacement</span> <span m="206041">since</span>
  <span m="206328">we've</span> <span m="206615">been</span> <span m="206902">told</span>
  <span m="207189">in</span> <span m="207476">the</span> <span m="207763">setup</span>
  <span m="208050">that</span> <span m="208764">it's</span> <span m="209478">the</span>
  <span m="210192">least-recently-used</span> <span m="210906">page.</span></p><p><span
  m="211620">The</span> <span m="212010">page</span> <span m="212400">table</span>
  <span m="212790">entry</span> <span m="213180">for</span> <span m="213570">VPN</span>
  <span m="213960">0xE</span> <span m="214350">has</span> <span m="214740">D=1</span>
  <span m="215130">so</span> <span m="215520">the</span> <span m="215910">handler</span>
  <span m="216300">writes</span> <span m="216690">the</span> <span m="217080">contents</span>
  <span m="217470">of</span> <span m="217860">VPN</span> <span m="218250">0xE,</span>
  <span m="218640">which</span> <span m="219136">is</span> <span m="219633">found</span>
  <span m="220130">in</span> <span m="220626">PPN</span> <span m="221123">0x5,</span>
  <span m="221620">to</span> <span m="222116">secondary</span> <span m="222613">storage.</span></p><p><span
  m="223110">Then</span> <span m="223479">it</span> <span m="223848">updates</span>
  <span m="224218">the</span> <span m="224587">page</span> <span m="224956">table</span>
  <span m="225326">to</span> <span m="225695">indicate</span> <span m="226064">that</span>
  <span m="226434">VPN</span> <span m="226803">0xE</span> <span m="227172">is</span>
  <span m="227542">no</span> <span m="227911">longer</span> <span m="228280">resident.</span></p><p><span
  m="228650">Next,</span> <span m="229106">the</span> <span m="229563">contents</span>
  <span m="230020">of</span> <span m="230477">VPN</span> <span m="230934">0x6</span>
  <span m="231391">are</span> <span m="231848">read</span> <span m="232305">from</span>
  <span m="232761">secondary</span> <span m="233218">storage</span> <span m="233675">into</span>
  <span m="234132">the</span> <span m="234589">now</span> <span m="235046">available</span>
  <span m="235503">PPN</span> <span m="235960">0x5.</span></p><p><span m="237230">Now</span>
  <span m="237532">the</span> <span m="237835">handler</span> <span m="238137">updates</span>
  <span m="238440">the</span> <span m="238742">page</span> <span m="239045">table</span>
  <span m="239347">entry</span> <span m="239650">for</span> <span m="239952">VPN</span>
  <span m="240255">0x6</span> <span m="240557">to</span> <span m="240860">indicate</span>
  <span m="241162">that</span> <span m="241465">it's</span> <span m="241767">resident</span>
  <span m="242070">in</span> <span m="243143">PPN</span> <span m="244216">0x5.</span></p><p><span
  m="245290">The</span> <span m="245628">page</span> <span m="245967">fault</span>
  <span m="246306">handler</span> <span m="246645">has</span> <span m="246983">completed</span>
  <span m="247322">its</span> <span m="247661">work,</span> <span m="248000">so</span>
  <span m="248338">program</span> <span m="248677">execution</span> <span m="249016">resumes</span>
  <span m="249355">and</span> <span m="249693">the</span> <span m="250032">ST</span>
  <span m="250371">instruction</span> <span m="250710">is</span> <span m="251720">re-executed.</span></p><p><span
  m="252730">This</span> <span m="253261">time</span> <span m="253793">the</span>
  <span m="254325">MMU</span> <span m="254857">is</span> <span m="255389">able</span>
  <span m="255921">to</span> <span m="256453">translate</span> <span m="256985">virtual</span>
  <span m="257517">address</span> <span m="258049">0x600</span> <span m="258581">to</span>
  <span m="259113">physical</span> <span m="259645">address</span> <span m="260177">0x500.</span></p><p><span
  m="260709">And</span> <span m="261099">since</span> <span m="261490">the</span>
  <span m="261880">ST</span> <span m="262271">instruction</span> <span m="262662">modifies</span>
  <span m="263052">the</span> <span m="263443">contents</span> <span m="263833">of</span>
  <span m="264224">VPN</span> <span m="264615">0x6,</span> <span m="265005">its</span>
  <span m="265396">D</span> <span m="265786">bit</span> <span m="266177">is</span>
  <span m="266568">set</span> <span m="266958">to</span> <span m="267349">1.</span></p><p><span
  m="267740">Whew!</span></p><p><span m="268740">We're</span> <span m="268980">done</span>
  <span m="269221">:)</span> <span m="269462">We</span> <span m="269702">can</span>
  <span m="269943">think</span> <span m="270184">of</span> <span m="270425">the</span>
  <span m="270665">work</span> <span m="270906">of</span> <span m="271147">the</span>
  <span m="271387">MMU</span> <span m="271628">as</span> <span m="271869">being</span>
  <span m="272110">divided</span> <span m="272565">into</span> <span m="273021">two</span>
  <span m="273477">tasks,</span> <span m="273933">which</span> <span m="274389">as</span>
  <span m="274845">computer</span> <span m="275301">scientists,</span> <span m="275757">we</span>
  <span m="276213">would</span> <span m="276669">think</span> <span m="277125">of</span>
  <span m="277581">as</span> <span m="278037">two</span> <span m="278493">procedures.</span></p><p><span
  m="278949">In</span> <span m="279246">this</span> <span m="279544">formulation</span>
  <span m="279841">the</span> <span m="280139">information</span> <span m="280436">in</span>
  <span m="280734">the</span> <span m="281031">page</span> <span m="281329">map</span>
  <span m="281627">is</span> <span m="281924">held</span> <span m="282222">in</span>
  <span m="282519">several</span> <span m="282817">arrays:</span> <span m="283114">the</span>
  <span m="283412">R</span> <span m="283710">array</span> <span m="284057">holds</span>
  <span m="284405">the</span> <span m="284753">resident</span> <span m="285101">bits,</span>
  <span m="285449">the</span> <span m="285797">D</span> <span m="286145">array</span>
  <span m="286492">holds</span> <span m="286840">the</span> <span m="287188">dirty</span>
  <span m="287536">bits,</span> <span m="287884">the</span> <span m="288232">PPN</span>
  <span m="288580">array</span> <span m="289002">holds</span> <span m="289424">the</span>
  <span m="289846">physical</span> <span m="290268">page</span> <span m="290690">numbers,</span>
  <span m="291112">and</span> <span m="291535">the</span> <span m="291957">DiskAdr</span>
  <span m="292379">array</span> <span m="292801">holds</span> <span m="293223">the</span>
  <span m="293645">location</span> <span m="294067">in</span> <span m="294490">secondary</span>
  <span m="295226">storage</span> <span m="295963">for</span> <span m="296699">each</span>
  <span m="297436">virtual</span> <span m="298172">page.</span></p><p><span m="298909">The</span>
  <span m="299251">VtoP</span> <span m="299594">procedure</span> <span m="299937">is</span>
  <span m="300279">invoked</span> <span m="300622">on</span> <span m="300965">each</span>
  <span m="301308">memory</span> <span m="301650">access</span> <span m="301993">to</span>
  <span m="302336">translate</span> <span m="302679">the</span> <span m="303021">virtual</span>
  <span m="303364">address</span> <span m="303707">into</span> <span m="304050">a</span>
  <span m="304770">physical</span> <span m="305490">address.</span></p><p><span m="306210">If</span>
  <span m="306503">the</span> <span m="306796">requested</span> <span m="307090">virtual</span>
  <span m="307383">page</span> <span m="307676">is</span> <span m="307970">not</span>
  <span m="308263">resident,</span> <span m="308556">the</span> <span m="308850">PageFault</span>
  <span m="309143">procedure</span> <span m="309436">is</span> <span m="309730">invoked</span>
  <span m="310023">to</span> <span m="310316">make</span> <span m="310610">the</span>
  <span m="311026">page</span> <span m="311443">resident.</span></p><p><span m="311860">Once</span>
  <span m="312187">the</span> <span m="312515">requested</span> <span m="312842">page</span>
  <span m="313170">is</span> <span m="313498">resident,</span> <span m="313825">the</span>
  <span m="314153">VPN</span> <span m="314481">is</span> <span m="314808">used</span>
  <span m="315136">as</span> <span m="315464">an</span> <span m="315791">index</span>
  <span m="316119">to</span> <span m="316447">lookup</span> <span m="316774">the</span>
  <span m="317102">corresponding</span> <span m="317430">PPN,</span> <span m="317890">which</span>
  <span m="318350">is</span> <span m="318810">then</span> <span m="319270">concatenated</span>
  <span m="319730">with</span> <span m="320190">the</span> <span m="320650">page</span>
  <span m="321110">offset</span> <span m="321570">to</span> <span m="322030">form</span>
  <span m="322490">the</span> <span m="322950">physical</span> <span m="323410">address.</span></p><p><span
  m="323870">The</span> <span m="324220">PageFault</span> <span m="324571">routine</span>
  <span m="324921">starts</span> <span m="325272">by</span> <span m="325623">selecting</span>
  <span m="325973">a</span> <span m="326324">virtual</span> <span m="326675">page</span>
  <span m="327025">to</span> <span m="327376">be</span> <span m="327727">replaced,</span>
  <span m="328077">writing</span> <span m="328428">out</span> <span m="328779">its</span>
  <span m="329239">contents</span> <span m="329699">if</span> <span m="330159">it's</span>
  <span m="330619">dirty.</span></p><p><span m="331080">The</span> <span m="331566">selected</span>
  <span m="332053">page</span> <span m="332540">is</span> <span m="333026">then</span>
  <span m="333513">marked</span> <span m="334000">as</span> <span m="334486">not</span>
  <span m="334973">resident.</span></p><p><span m="335460">Finally</span> <span m="335800">the</span>
  <span m="336141">desired</span> <span m="336481">virtual</span> <span m="336822">page</span>
  <span m="337163">is</span> <span m="337503">read</span> <span m="337844">from</span>
  <span m="338184">secondary</span> <span m="338525">storage</span> <span m="338866">and</span>
  <span m="339206">the</span> <span m="339547">page</span> <span m="339887">map</span>
  <span m="340228">information</span> <span m="340569">updated</span> <span m="340990">to</span>
  <span m="341412">reflect</span> <span m="341833">that</span> <span m="342255">it's</span>
  <span m="342677">now</span> <span m="343098">resident</span> <span m="343520">in</span>
  <span m="343941">the</span> <span m="344363">newly</span> <span m="344785">filled</span>
  <span m="345206">physical</span> <span m="345628">page.</span></p><p><span m="346050">We'll</span>
  <span m="346528">use</span> <span m="347006">hardware</span> <span m="347484">to</span>
  <span m="347962">implement</span> <span m="348440">the</span> <span m="348918">VtoP</span>
  <span m="349396">functionality</span> <span m="349874">since</span> <span m="350352">it's</span>
  <span m="350830">needed</span> <span m="351308">for</span> <span m="351786">every</span>
  <span m="352264">memory</span> <span m="352742">access.</span></p><p><span m="353220">The</span>
  <span m="353576">call</span> <span m="353933">to</span> <span m="354289">the</span>
  <span m="354646">PageFault</span> <span m="355003">procedure</span> <span m="355359">is</span>
  <span m="355716">accomplished</span> <span m="356072">via</span> <span m="356429">a</span>
  <span m="356786">page</span> <span m="357142">fault</span> <span m="357499">exception,</span>
  <span m="357855">which</span> <span m="358212">directs</span> <span m="358569">the</span>
  <span m="359047">CPU</span> <span m="359525">to</span> <span m="360004">execute</span>
  <span m="360482">the</span> <span m="360961">appropriate</span> <span m="361439">handler</span>
  <span m="361918">software</span> <span m="362396">that</span> <span m="362875">contains</span>
  <span m="363353">the</span> <span m="363832">PageFault</span> <span m="364310">procedure.</span></p><p><span
  m="364789">This</span> <span m="365113">is</span> <span m="365437">a</span> <span
  m="365762">good</span> <span m="366086">strategy</span> <span m="366410">to</span>
  <span m="366735">pursue</span> <span m="367059">in</span> <span m="367384">all</span>
  <span m="367708">our</span> <span m="368032">implementation</span> <span m="368357">choices:</span>
  <span m="368681">use</span> <span m="369005">hardware</span> <span m="369330">for</span>
  <span m="369654">the</span> <span m="369979">operations</span> <span m="370397">that</span>
  <span m="370815">need</span> <span m="371233">to</span> <span m="371651">be</span>
  <span m="372069">fast,</span> <span m="372487">but</span> <span m="372905">use</span>
  <span m="373323">exceptions</span> <span m="373741">to</span> <span m="374159">handle</span>
  <span m="374577">the</span> <span m="374995">(hopefully</span> <span m="375413">infrequent)</span>
  <span m="375831">exceptional</span> <span m="376250">cases</span> <span m="377280">in</span>
  <span m="378310">software.</span></p><p><span m="379340">Since</span> <span m="379633">the</span>
  <span m="379926">software</span> <span m="380219">is</span> <span m="380512">executed</span>
  <span m="380805">by</span> <span m="381098">the</span> <span m="381391">CPU,</span>
  <span m="381685">which</span> <span m="381978">is</span> <span m="382271">itself</span>
  <span m="382564">a</span> <span m="382857">piece</span> <span m="383150">of</span>
  <span m="383443">hardware,</span> <span m="383736">what</span> <span m="384030">we're</span>
  <span m="384440">really</span> <span m="384851">doing</span> <span m="385262">is</span>
  <span m="385673">making</span> <span m="386084">the</span> <span m="386495">tradeoff</span>
  <span m="386905">between</span> <span m="387316">using</span> <span m="387727">special-purpose</span>
  <span m="388138">hardware</span> <span m="388549">(e.g.,</span> <span m="388960">the</span>
  <span m="389553">MMU)</span> <span m="390146">or</span> <span m="390740">using</span>
  <span m="391333">general-purpose</span> <span m="391926">hardware</span> <span m="392520">(e.g.,</span>
  <span m="393113">the</span> <span m="393706">CPU).</span></p><p><span m="394300">In</span>
  <span m="394723">general,</span> <span m="395147">one</span> <span m="395571">should</span>
  <span m="395994">be</span> <span m="396418">skeptical</span> <span m="396842">of</span>
  <span m="397265">proposals</span> <span m="397689">to</span> <span m="398113">use</span>
  <span m="398536">special-purpose</span> <span m="398960">hardware,</span> <span
  m="399384">reserving</span> <span m="399808">that</span> <span m="400215">choice</span>
  <span m="400622">for</span> <span m="401029">operations</span> <span m="401436">that</span>
  <span m="401843">truly</span> <span m="402250">are</span> <span m="402657">commonplace</span>
  <span m="403064">and</span> <span m="403471">whose</span> <span m="403878">performance</span>
  <span m="404285">is</span> <span m="404692">critical</span> <span m="405099">to</span>
  <span m="405393">the</span> <span m="405687">overall</span> <span m="405981">performance</span>
  <span m="406276">of</span> <span m="406570">the</span> <span m="406864">system.</span></p>
type: course
uid: 502171c8b3174031b76bc8a712f568e4

---
None