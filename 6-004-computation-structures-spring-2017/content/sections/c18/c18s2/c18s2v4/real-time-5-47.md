---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 7dhuZ6V9tcY
  parent_uid: 70e94cd77ca25c0ad0b061ad8ee56cab
  title: Video-YouTube-Stream
  type: Video
  uid: 519ceee34507cf592109347d14fbeeb5
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/7dhuZ6V9tcY/default.jpg
  parent_uid: 70e94cd77ca25c0ad0b061ad8ee56cab
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 585688cfb088577b3c7d6c3384ba7fd4
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 7dhuZ6V9tcY
  parent_uid: 70e94cd77ca25c0ad0b061ad8ee56cab
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 311925e1c96bf45448a4501a9996f6cc
- id: 7dhuZ6V9tcY.srt
  parent_uid: 70e94cd77ca25c0ad0b061ad8ee56cab
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v4/real-time-5-47/7dhuZ6V9tcY.srt
  title: 3play caption file
  type: null
  uid: 8c43a6e9a824edd4e78dc7647f1167f0
- id: 7dhuZ6V9tcY.pdf
  parent_uid: 70e94cd77ca25c0ad0b061ad8ee56cab
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v4/real-time-5-47/7dhuZ6V9tcY.pdf
  title: 3play pdf file
  type: null
  uid: d782552b3a60aead78eb10a927ec558d
- id: Caption-3Play YouTube id-SRT
  parent_uid: 70e94cd77ca25c0ad0b061ad8ee56cab
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 525a9ae51e4cb05be6c32e680803be44
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 70e94cd77ca25c0ad0b061ad8ee56cab
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 5147bfab541a11108718b55a26103b16
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_18-02-04_300k.mp4
  parent_uid: 70e94cd77ca25c0ad0b061ad8ee56cab
  title: Video-Internet Archive-MP4
  type: Video
  uid: 72c04f4f2c863d8dcdeef1eee4c54976
inline_embed_id: 67405107osdevicehandlers54771057813
layout: video
order_index: null
parent_uid: f40ad5076deb60a1533db7d6e42f6976
related_resources_text: ''
short_url: real-time-5-47
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v4/real-time-5-47
template_type: Embed
title: Real Time (5:47)
transcript: <p><span m="520">So</span> <span m="873">far</span> <span m="1226">in</span>
  <span m="1579">constructing</span> <span m="1933">our</span> <span m="2286">timesharing</span>
  <span m="2639">system,</span> <span m="2992">we've</span> <span m="3346">worked</span>
  <span m="3699">hard</span> <span m="4052">to</span> <span m="4405">build</span>
  <span m="4759">an</span> <span m="5112">execution</span> <span m="5465">environment</span>
  <span m="5819">that</span> <span m="6224">gives</span> <span m="6629">each</span>
  <span m="7034">process</span> <span m="7439">the</span> <span m="7844">illusion</span>
  <span m="8249">of</span> <span m="8654">running</span> <span m="9059">on</span>
  <span m="9464">its</span> <span m="9869">own</span> <span m="10274">independent</span>
  <span m="10679">virtual</span> <span m="11084">machine.</span></p><p><span m="11490">The</span>
  <span m="11843">processes</span> <span m="12196">appear</span> <span m="12549">to</span>
  <span m="12902">run</span> <span m="13255">concurrently</span> <span m="13608">although</span>
  <span m="13961">we're</span> <span m="14314">really</span> <span m="14667">quickly</span>
  <span m="15020">switching</span> <span m="15373">between</span> <span m="15726">running</span>
  <span m="16079">processes</span> <span m="16553">on</span> <span m="17028">a</span>
  <span m="17503">single</span> <span m="17977">hardware</span> <span m="18452">system.</span>
  <span m="18927">This</span> <span m="19401">often</span> <span m="19876">leads</span>
  <span m="20351">to</span> <span m="20825">better</span> <span m="21300">overall</span>
  <span m="21775">utilization</span> <span m="22250">since</span> <span m="22575">if</span>
  <span m="22900">a</span> <span m="23225">particular</span> <span m="23551">process</span>
  <span m="23876">is</span> <span m="24201">waiting</span> <span m="24527">for</span>
  <span m="24852">an</span> <span m="25177">I/O</span> <span m="25502">event,</span>
  <span m="25828">we</span> <span m="26153">can</span> <span m="26478">devote</span>
  <span m="26804">the</span> <span m="27129">unneeded</span> <span m="27454">cycles</span>
  <span m="27780">to</span> <span m="28230">running</span> <span m="28681">other</span>
  <span m="29132">processes.</span> <span m="29583">The</span> <span m="30034">downside</span>
  <span m="30485">of</span> <span m="30935">timesharing</span> <span m="31386">is</span>
  <span m="31837">that</span> <span m="32288">it</span> <span m="32739">can</span>
  <span m="33190">be</span> <span m="33529">hard</span> <span m="33868">to</span>
  <span m="34208">predict</span> <span m="34547">exactly</span> <span m="34887">how</span>
  <span m="35226">long</span> <span m="35566">a</span> <span m="35905">process</span>
  <span m="36245">will</span> <span m="36584">take</span> <span m="36923">to</span>
  <span m="37263">complete</span> <span m="37602">since</span> <span m="37942">the</span>
  <span m="38281">CPU</span> <span m="38621">time</span> <span m="38960">it</span>
  <span m="39300">will</span> <span m="39724">receive</span> <span m="40149">depends</span>
  <span m="40574">on</span> <span m="40999">how</span> <span m="41424">much</span>
  <span m="41849">time</span> <span m="42274">the</span> <span m="42699">other</span>
  <span m="43124">processes</span> <span m="43549">are</span> <span m="43974">using.</span></p><p><span
  m="44399">So</span> <span m="44670">we'd</span> <span m="44941">need</span> <span
  m="45212">to</span> <span m="45484">know</span> <span m="45755">how</span> <span
  m="46026">many</span> <span m="46297">other</span> <span m="46569">processes</span>
  <span m="46840">there</span> <span m="47111">are,</span> <span m="47382">whether</span>
  <span m="47654">they're</span> <span m="47925">waiting</span> <span m="48196">for</span>
  <span m="48467">I/O</span> <span m="48739">events,</span> <span m="49131">etc.</span>
  <span m="49523">In</span> <span m="49915">a</span> <span m="50307">timesharing</span>
  <span m="50699">system</span> <span m="51091">we</span> <span m="51483">can't</span>
  <span m="51875">make</span> <span m="52267">any</span> <span m="52660">guarantees</span>
  <span m="53105">on</span> <span m="53551">completion</span> <span m="53997">times.</span>
  <span m="54442">And</span> <span m="54888">we</span> <span m="55334">chose</span>
  <span m="55780">to</span> <span m="56225">have</span> <span m="56671">the</span>
  <span m="57117">OS</span> <span m="57562">play</span> <span m="58008">the</span>
  <span m="58454">intermediary</span> <span m="58900">between</span> <span m="59259">interrupt</span>
  <span m="59619">events</span> <span m="59979">triggered</span> <span m="60339">by</span>
  <span m="60699">the</span> <span m="61059">outside</span> <span m="61419">world</span>
  <span m="61779">and</span> <span m="62139">the</span> <span m="62499">user-mode</span>
  <span m="62859">programs</span> <span m="63219">where</span> <span m="63579">the</span>
  <span m="64054">event</span> <span m="64530">processing</span> <span m="65005">occurs.</span>
  <span m="65481">In</span> <span m="65956">other</span> <span m="66432">words,</span>
  <span m="66907">we've</span> <span m="67383">separated</span> <span m="67858">event</span>
  <span m="68334">handling</span> <span m="68810">(where</span> <span m="69149">the</span>
  <span m="69489">data</span> <span m="69829">is</span> <span m="70169">stored</span>
  <span m="70509">by</span> <span m="70849">the</span> <span m="71189">OS)</span>
  <span m="71529">and</span> <span m="71869">event</span> <span m="72209">processing</span>
  <span m="72549">(where</span> <span m="72889">the</span> <span m="73229">data</span>
  <span m="73569">is</span> <span m="73909">passed</span> <span m="74249">to</span>
  <span m="74797">user-mode</span> <span m="75345">programs</span> <span m="75894">via</span>
  <span m="76442">SVCs).</span> <span m="76990">This</span> <span m="77539">means</span>
  <span m="78087">that</span> <span m="78635">using</span> <span m="79184">a</span>
  <span m="79732">conventional</span> <span m="80280">timesharing</span> <span m="80829">system,</span>
  <span m="81231">it's</span> <span m="81634">hard</span> <span m="82036">to</span>
  <span m="82439">ensure</span> <span m="82841">that</span> <span m="83244">event</span>
  <span m="83646">processing</span> <span m="84049">will</span> <span m="84452">be</span>
  <span m="84854">complete</span> <span m="85257">by</span> <span m="85659">a</span>
  <span m="86062">specified</span> <span m="86464">event</span> <span m="86867">deadline,</span>
  <span m="87270">i.e.,</span> <span m="87726">before</span> <span m="88182">the</span>
  <span m="88638">end</span> <span m="89095">of</span> <span m="89551">a</span> <span
  m="90007">specified</span> <span m="90464">time</span> <span m="90920">period</span>
  <span m="91376">after</span> <span m="91832">the</span> <span m="92289">event</span>
  <span m="92745">was</span> <span m="93201">triggered.</span></p><p><span m="93658">Since</span>
  <span m="94215">modern</span> <span m="94773">CPU</span> <span m="95331">chips</span>
  <span m="95889">provide</span> <span m="96447">inexpensive,</span> <span m="97005">high-performance,</span>
  <span m="97563">general-purpose</span> <span m="98121">computing,</span> <span m="98679">they</span>
  <span m="99024">are</span> <span m="99369">often</span> <span m="99714">used</span>
  <span m="100060">as</span> <span m="100405">the</span> <span m="100750">&quot;brains&quot;</span>
  <span m="101096">of</span> <span m="101441">control</span> <span m="101786">systems</span>
  <span m="102131">where</span> <span m="102477">deadlines</span> <span m="102822">are</span>
  <span m="103167">a</span> <span m="103513">fact</span> <span m="103858">of</span>
  <span m="104203">life.</span></p><p><span m="104549">For</span> <span m="104995">example,</span>
  <span m="105442">consider</span> <span m="105888">the</span> <span m="106335">electronic</span>
  <span m="106781">stability</span> <span m="107228">control</span> <span m="107675">(ESC)</span>
  <span m="108121">system</span> <span m="108568">on</span> <span m="109014">modern</span>
  <span m="109461">cars.</span></p><p><span m="109908">This</span> <span m="110276">system</span>
  <span m="110645">helps</span> <span m="111013">drivers</span> <span m="111382">maintain</span>
  <span m="111751">control</span> <span m="112119">of</span> <span m="112488">their</span>
  <span m="112856">vehicle</span> <span m="113225">during</span> <span m="113594">steering</span>
  <span m="113962">and</span> <span m="114331">braking</span> <span m="114700">maneuvers</span>
  <span m="115220">by</span> <span m="115741">keeping</span> <span m="116262">the</span>
  <span m="116783">car</span> <span m="117304">headed</span> <span m="117824">in</span>
  <span m="118345">the</span> <span m="118866">driver's</span> <span m="119387">intended</span>
  <span m="119908">direction.</span></p><p><span m="120429">The</span> <span m="120678">computer</span>
  <span m="120928">at</span> <span m="121177">the</span> <span m="121427">heart</span>
  <span m="121676">of</span> <span m="121926">the</span> <span m="122175">system</span>
  <span m="122425">measures</span> <span m="122674">the</span> <span m="122924">forces</span>
  <span m="123173">on</span> <span m="123423">the</span> <span m="123672">car,</span>
  <span m="123922">the</span> <span m="124171">direction</span> <span m="124421">of</span>
  <span m="124670">steering,</span> <span m="124920">and</span> <span m="125162">the</span>
  <span m="125405">rotation</span> <span m="125648">of</span> <span m="125890">the</span>
  <span m="126133">wheels</span> <span m="126376">to</span> <span m="126618">determine</span>
  <span m="126861">if</span> <span m="127104">there's</span> <span m="127346">been</span>
  <span m="127589">a</span> <span m="127832">loss</span> <span m="128074">of</span>
  <span m="128317">control</span> <span m="128560">due</span> <span m="128981">to</span>
  <span m="129403">a</span> <span m="129825">loss</span> <span m="130246">of</span>
  <span m="130668">traction,</span> <span m="131090">i.e.,</span> <span m="131511">is</span>
  <span m="131933">the</span> <span m="132355">car</span> <span m="132776">&quot;spinning</span>
  <span m="133198">out&quot;?</span></p><p><span m="133620">If</span> <span m="134079">so,</span>
  <span m="134538">the</span> <span m="134998">ESC</span> <span m="135457">uses</span>
  <span m="135916">rapid</span> <span m="136376">automatic</span> <span m="136835">braking</span>
  <span m="137294">of</span> <span m="137754">individual</span> <span m="138213">wheels</span>
  <span m="138672">to</span> <span m="139132">prevent</span> <span m="139591">the</span>
  <span m="140050">car's</span> <span m="140510">heading</span> <span m="140985">from</span>
  <span m="141460">veering</span> <span m="141935">from</span> <span m="142410">the</span>
  <span m="142885">driver's</span> <span m="143360">intended</span> <span m="143835">heading.</span></p><p><span
  m="144310">With</span> <span m="144663">ESC</span> <span m="145016">you</span> <span
  m="145369">can</span> <span m="145722">slam</span> <span m="146075">on</span> <span
  m="146428">your</span> <span m="146782">brakes</span> <span m="147135">or</span>
  <span m="147488">swerve</span> <span m="147841">to</span> <span m="148194">avoid</span>
  <span m="148547">an</span> <span m="148901">obstacle</span> <span m="149254">and</span>
  <span m="149607">not</span> <span m="149960">worry</span> <span m="150313">that</span>
  <span m="150666">the</span> <span m="151020">car</span> <span m="151355">will</span>
  <span m="151690">suddenly</span> <span m="152025">fishtail</span> <span m="152360">out</span>
  <span m="152695">of</span> <span m="153030">control.</span> <span m="153365">You</span>
  <span m="153700">can</span> <span m="154035">feel</span> <span m="154370">the</span>
  <span m="154705">system</span> <span m="155040">working</span> <span m="155375">as</span>
  <span m="155710">a</span> <span m="156045">chatter</span> <span m="156380">in</span>
  <span m="156918">the</span> <span m="157456">brakes.</span> <span m="157995">To</span>
  <span m="158533">be</span> <span m="159071">effective,</span> <span m="159610">the</span>
  <span m="160148">ESC</span> <span m="160686">system</span> <span m="161225">has</span>
  <span m="161763">to</span> <span m="162301">guarantee</span> <span m="162840">the</span>
  <span m="163214">correct</span> <span m="163589">braking</span> <span m="163964">action</span>
  <span m="164338">at</span> <span m="164713">each</span> <span m="165088">wheel</span>
  <span m="165462">within</span> <span m="165837">a</span> <span m="166212">certain</span>
  <span m="166586">time</span> <span m="166961">of</span> <span m="167336">receiving</span>
  <span m="167710">dangerous</span> <span m="168085">sensor</span> <span m="168460">settings.</span>
  <span m="168767">This</span> <span m="169074">means</span> <span m="169381">that</span>
  <span m="169689">it</span> <span m="169996">has</span> <span m="170303">to</span>
  <span m="170610">be</span> <span m="170918">able</span> <span m="171225">to</span>
  <span m="171532">guarantee</span> <span m="171840">that</span> <span m="172205">certain</span>
  <span m="172571">subroutines</span> <span m="172937">will</span> <span m="173302">run</span>
  <span m="173668">to</span> <span m="174034">completion</span> <span m="174400">within</span>
  <span m="174765">some</span> <span m="175131">predetermined</span> <span m="175497">time</span>
  <span m="175862">of</span> <span m="176228">a</span> <span m="176594">sensor</span>
  <span m="176960">event.</span> <span m="177386">To</span> <span m="177813">be</span>
  <span m="178240">able</span> <span m="178666">to</span> <span m="179093">make</span>
  <span m="179520">these</span> <span m="179946">guarantees</span> <span m="180373">we'll</span>
  <span m="180800">have</span> <span m="181113">to</span> <span m="181426">come</span>
  <span m="181739">up</span> <span m="182052">with</span> <span m="182365">a</span>
  <span m="182678">better</span> <span m="182991">way</span> <span m="183304">to</span>
  <span m="183617">schedule</span> <span m="183930">process</span> <span m="184243">execution</span>
  <span m="184556">-</span> <span m="184870">round-robin</span> <span m="185277">scheduling</span>
  <span m="185684">won't</span> <span m="186091">get</span> <span m="186498">the</span>
  <span m="186905">job</span> <span m="187312">done!</span> <span m="187720">Systems</span>
  <span m="188127">that</span> <span m="188534">can</span> <span m="188941">make</span>
  <span m="189348">such</span> <span m="189755">guarantees</span> <span m="190162">are</span>
  <span m="190570">called</span> <span m="191033">&quot;real-time</span> <span m="191496">systems&quot;.</span>
  <span m="191959">One</span> <span m="192422">measure</span> <span m="192885">of</span>
  <span m="193348">performance</span> <span m="193811">in</span> <span m="194274">a</span>
  <span m="194737">real-time</span> <span m="195200">system</span> <span m="195518">is</span>
  <span m="195837">the</span> <span m="196156">interrupt</span> <span m="196475">latency</span>
  <span m="196793">L,</span> <span m="197112">the</span> <span m="197431">amount</span>
  <span m="197750">of</span> <span m="198068">time</span> <span m="198387">that</span>
  <span m="198706">elapses</span> <span m="199025">between</span> <span m="199343">a</span>
  <span m="199662">request</span> <span m="199981">to</span> <span m="200300">run</span>
  <span m="200726">some</span> <span m="201152">code</span> <span m="201578">and</span>
  <span m="202004">when</span> <span m="202430">that</span> <span m="202856">code</span>
  <span m="203282">actually</span> <span m="203708">starts</span> <span m="204134">executing.</span></p><p><span
  m="204560">If</span> <span m="204892">there's</span> <span m="205225">a</span> <span
  m="205557">deadline</span> <span m="205890">D</span> <span m="206222">associated</span>
  <span m="206555">with</span> <span m="206887">servicing</span> <span m="207220">the</span>
  <span m="207552">request,</span> <span m="207885">we</span> <span m="208217">can</span>
  <span m="208550">compute</span> <span m="208882">the</span> <span m="209215">maximum</span>
  <span m="209547">allowable</span> <span m="209880">latency</span> <span m="210283">that</span>
  <span m="210686">still</span> <span m="211090">permits</span> <span m="211493">the</span>
  <span m="211896">service</span> <span m="212300">routine</span> <span m="212703">to</span>
  <span m="213106">complete</span> <span m="213510">by</span> <span m="213913">the</span>
  <span m="214316">deadline.</span></p><p><span m="214720">In</span> <span m="215110">other</span>
  <span m="215501">words,</span> <span m="215892">what's</span> <span m="216283">the</span>
  <span m="216674">largest</span> <span m="217065">L</span> <span m="217455">such</span>
  <span m="217846">that</span> <span m="218237">L_max+S</span> <span m="218628">=</span>
  <span m="219019">D?</span></p><p><span m="219410">Bad</span> <span m="219769">things</span>
  <span m="220128">can</span> <span m="220488">happen</span> <span m="220847">if</span>
  <span m="221206">we</span> <span m="221566">miss</span> <span m="221925">certain</span>
  <span m="222285">deadlines.</span> <span m="222644">Maybe</span> <span m="223003">that's</span>
  <span m="223363">why</span> <span m="223722">we</span> <span m="224081">call</span>
  <span m="224441">them</span> <span m="224800">&quot;dead&quot;-lines</span> <span
  m="225160">:)</span> <span m="225475">In</span> <span m="225790">those</span> <span
  m="226105">cases</span> <span m="226420">we</span> <span m="226735">want</span>
  <span m="227050">our</span> <span m="227365">real</span> <span m="227680">time</span>
  <span m="227995">system</span> <span m="228310">to</span> <span m="228782">guarantee</span>
  <span m="229255">that</span> <span m="229728">the</span> <span m="230201">actual</span>
  <span m="230674">latency</span> <span m="231147">is</span> <span m="231620">always</span>
  <span m="232092">less</span> <span m="232565">than</span> <span m="233038">the</span>
  <span m="233511">maximum</span> <span m="233984">allowable</span> <span m="234457">latency.</span></p><p><span
  m="234930">These</span> <span m="235385">critical</span> <span m="235840">deadlines</span>
  <span m="236295">give</span> <span m="236750">rise</span> <span m="237205">to</span>
  <span m="237660">what</span> <span m="238115">we</span> <span m="238570">call</span>
  <span m="239025">&quot;hard</span> <span m="239480">real-time</span> <span m="239935">constraints&quot;.</span></p><p><span
  m="240390">What</span> <span m="240812">factors</span> <span m="241234">contribute</span>
  <span m="241656">to</span> <span m="242079">interrupt</span> <span m="242501">latency?</span>
  <span m="242923">Well,</span> <span m="243346">while</span> <span m="243768">handling</span>
  <span m="244190">an</span> <span m="244613">interrupt</span> <span m="245035">it</span>
  <span m="245457">takes</span> <span m="245880">times</span> <span m="246210">to</span>
  <span m="246540">save</span> <span m="246870">the</span> <span m="247200">process</span>
  <span m="247530">state,</span> <span m="247860">switch</span> <span m="248190">to</span>
  <span m="248520">the</span> <span m="248850">kernel</span> <span m="249180">context,</span>
  <span m="249510">and</span> <span m="249840">dispatch</span> <span m="250170">to</span>
  <span m="250500">the</span> <span m="250830">correct</span> <span m="251160">interrupt</span>
  <span m="251533">handler.</span> <span m="251907">When</span> <span m="252280">writing</span>
  <span m="252654">our</span> <span m="253028">OS,</span> <span m="253401">we</span>
  <span m="253775">can</span> <span m="254149">work</span> <span m="254522">to</span>
  <span m="254896">minimize</span> <span m="255270">the</span> <span m="255622">amount</span>
  <span m="255975">of</span> <span m="256328">code</span> <span m="256681">involved</span>
  <span m="257034">in</span> <span m="257387">the</span> <span m="257740">setup</span>
  <span m="258093">phase</span> <span m="258446">of</span> <span m="258799">an</span>
  <span m="259152">interrupt</span> <span m="259505">handler.</span></p><p><span m="259858">We</span>
  <span m="260152">also</span> <span m="260446">have</span> <span m="260740">to</span>
  <span m="261034">avoid</span> <span m="261328">long</span> <span m="261622">periods</span>
  <span m="261916">of</span> <span m="262211">time</span> <span m="262505">when</span>
  <span m="262799">the</span> <span m="263093">processor</span> <span m="263387">cannot</span>
  <span m="263681">be</span> <span m="263975">interrupted.</span></p><p><span m="264270">Some</span>
  <span m="264748">ISAs</span> <span m="265226">have</span> <span m="265705">complex</span>
  <span m="266183">multi-cycle</span> <span m="266662">instructions,</span> <span
  m="267140">e.g.,</span> <span m="267619">block</span> <span m="268097">move</span>
  <span m="268576">instructions</span> <span m="269054">where</span> <span m="269533">a</span>
  <span m="270011">single</span> <span m="270490">instruction</span> <span m="270848">makes</span>
  <span m="271207">many</span> <span m="271566">memory</span> <span m="271924">accesses</span>
  <span m="272283">as</span> <span m="272642">it</span> <span m="273000">moves</span>
  <span m="273359">a</span> <span m="273718">block</span> <span m="274076">of</span>
  <span m="274435">data</span> <span m="274794">from</span> <span m="275152">one</span>
  <span m="275511">location</span> <span m="275870">to</span> <span m="276179">another.</span>
  <span m="276488">In</span> <span m="276797">designing</span> <span m="277106">the</span>
  <span m="277415">ISA,</span> <span m="277724">we</span> <span m="278033">need</span>
  <span m="278342">to</span> <span m="278651">avoid</span> <span m="278960">such</span>
  <span m="279270">instructions</span> <span m="279624">or</span> <span m="279978">design</span>
  <span m="280332">them</span> <span m="280686">so</span> <span m="281040">that</span>
  <span m="281395">they</span> <span m="281749">can</span> <span m="282103">be</span>
  <span m="282457">interrupted</span> <span m="282811">and</span> <span m="283165">restarted.</span></p><p><span
  m="283520">The</span> <span m="283923">biggest</span> <span m="284326">problem</span>
  <span m="284729">comes</span> <span m="285132">when</span> <span m="285535">we're</span>
  <span m="285938">executing</span> <span m="286341">another</span> <span m="286744">interrupt</span>
  <span m="287147">handler</span> <span m="287550">in</span> <span m="287953">kernel</span>
  <span m="288356">mode.</span></p><p><span m="288759">In</span> <span m="289079">kernel</span>
  <span m="289399">mode,</span> <span m="289719">interrupts</span> <span m="290039">are</span>
  <span m="290359">disabled,</span> <span m="290679">so</span> <span m="290999">the</span>
  <span m="291319">actual</span> <span m="291639">latency</span> <span m="291959">will</span>
  <span m="292279">be</span> <span m="292599">determined</span> <span m="292919">by</span>
  <span m="293239">the</span> <span m="293560">time</span> <span m="293851">it</span>
  <span m="294143">takes</span> <span m="294435">to</span> <span m="294727">complete</span>
  <span m="295019">the</span> <span m="295311">current</span> <span m="295603">interrupt</span>
  <span m="295895">handler</span> <span m="296186">in</span> <span m="296478">addition</span>
  <span m="296770">to</span> <span m="297062">the</span> <span m="297354">other</span>
  <span m="297646">costs</span> <span m="297938">mentioned</span> <span m="298230">above.</span>
  <span m="298656">This</span> <span m="299082">latency</span> <span m="299508">is</span>
  <span m="299934">not</span> <span m="300360">under</span> <span m="300786">the</span>
  <span m="301212">control</span> <span m="301638">of</span> <span m="302064">the</span>
  <span m="302490">CPU</span> <span m="303044">designer</span> <span m="303598">and</span>
  <span m="304153">will</span> <span m="304707">depend</span> <span m="305261">on</span>
  <span m="305816">the</span> <span m="306370">particular</span> <span m="306924">application.</span></p><p><span
  m="307479">Writing</span> <span m="308060">programs</span> <span m="308641">with</span>
  <span m="309222">hard</span> <span m="309803">real-time</span> <span m="310385">constraints</span>
  <span m="310966">can</span> <span m="311547">get</span> <span m="312128">complicated!</span></p><p><span
  m="312710">Our</span> <span m="313071">goal</span> <span m="313432">is</span> <span
  m="313793">to</span> <span m="314154">bound</span> <span m="314515">and</span> <span
  m="314876">minimize</span> <span m="315237">interrupt</span> <span m="315598">latency.</span></p><p><span
  m="315960">We'll</span> <span m="316253">do</span> <span m="316546">this</span>
  <span m="316839">by</span> <span m="317132">optimizing</span> <span m="317425">the</span>
  <span m="317718">cost</span> <span m="318011">of</span> <span m="318305">taking</span>
  <span m="318598">an</span> <span m="318891">interrupt</span> <span m="319184">and</span>
  <span m="319477">dispatching</span> <span m="319770">to</span> <span m="320063">the</span>
  <span m="320356">correct</span> <span m="320650">handler</span> <span m="321159">code.</span>
  <span m="321669">We'll</span> <span m="322179">avoid</span> <span m="322689">instructions</span>
  <span m="323199">whose</span> <span m="323709">execution</span> <span m="324219">time</span>
  <span m="324729">is</span> <span m="325061">data</span> <span m="325394">dependent.</span>
  <span m="325727">And</span> <span m="326059">we'll</span> <span m="326392">work</span>
  <span m="326725">to</span> <span m="327058">minimize</span> <span m="327390">the</span>
  <span m="327723">time</span> <span m="328056">spent</span> <span m="328389">in</span>
  <span m="328761">kernel</span> <span m="329134">mode.</span> <span m="329507">But</span>
  <span m="329880">even</span> <span m="330253">with</span> <span m="330625">all</span>
  <span m="330998">these</span> <span m="331371">measures,</span> <span m="331744">we'll</span>
  <span m="332117">see</span> <span m="332490">that</span> <span m="332800">in</span>
  <span m="333111">some</span> <span m="333421">cases</span> <span m="333732">we'll</span>
  <span m="334043">have</span> <span m="334353">to</span> <span m="334664">modify</span>
  <span m="334975">our</span> <span m="335285">system</span> <span m="335596">to</span>
  <span m="335906">allow</span> <span m="336217">interrupts</span> <span m="336528">even</span>
  <span m="336838">in</span> <span m="337149">kernel</span> <span m="337460">mode.</span>
  <span m="337960">Next</span> <span m="338460">we'll</span> <span m="338960">look</span>
  <span m="339460">at</span> <span m="339960">some</span> <span m="340460">concrete</span>
  <span m="340960">examples</span> <span m="341460">and</span> <span m="341872">see</span>
  <span m="342284">what</span> <span m="342696">mechanisms</span> <span m="343108">are</span>
  <span m="343521">required</span> <span m="343933">to</span> <span m="344345">make</span>
  <span m="344757">guarantees</span> <span m="345170">about</span> <span m="345582">hard</span>
  <span m="345994">real-time</span> <span m="346406">constraints.</span></p>
type: course
uid: 70e94cd77ca25c0ad0b061ad8ee56cab

---
None