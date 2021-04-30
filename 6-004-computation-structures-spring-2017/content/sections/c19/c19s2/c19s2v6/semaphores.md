---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 3KJeK-UUADA
  parent_uid: be6b6d09f2fd2f6de776402b88478d1c
  title: Video-YouTube-Stream
  type: Video
  uid: cb1caa75a9ed09eec45a2541fcf7f3ba
- id: 3Play-3Play YouTube id-Stream
  media_location: 3KJeK-UUADA
  parent_uid: be6b6d09f2fd2f6de776402b88478d1c
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: c72a5c022b40a9121519bedfb33dc555
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/3KJeK-UUADA/default.jpg
  parent_uid: be6b6d09f2fd2f6de776402b88478d1c
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: aa3aed7eca86abc4ba03d5fff0f30f16
- id: 3KJeK-UUADA.srt
  parent_uid: be6b6d09f2fd2f6de776402b88478d1c
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v6/semaphores/3KJeK-UUADA.srt
  title: 3play caption file
  type: null
  uid: fdf22e9d12c2a95862ea5f0a00a018a3
- id: 3KJeK-UUADA.pdf
  parent_uid: be6b6d09f2fd2f6de776402b88478d1c
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v6/semaphores/3KJeK-UUADA.pdf
  title: 3play pdf file
  type: null
  uid: 3d7749df556d00bc58141d08da564d85
- id: Caption-3Play YouTube id-SRT
  parent_uid: be6b6d09f2fd2f6de776402b88478d1c
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 458ae501b974e155b4cd4b212db54b92
- id: Transcript-3Play YouTube id-PDF
  parent_uid: be6b6d09f2fd2f6de776402b88478d1c
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: d0110358b01acc31df5643c729179734
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_19-02-06-01_300k.mp4
  parent_uid: be6b6d09f2fd2f6de776402b88478d1c
  title: Video-Internet Archive-MP4
  type: Video
  uid: e3f8eb87abef2d8796db274206048b36
inline_embed_id: 148751semaphores40717822
layout: video
order_index: null
parent_uid: 8769d338698faf01be117c40e642b06f
related_resources_text: ''
short_url: semaphores
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v6/semaphores
template_type: Embed
title: 'Worked Example: Semaphores'
transcript: <p><span m="280">In</span> <span m="589">this</span> <span m="898">exercise,</span>
  <span m="1208">we</span> <span m="1517">will</span> <span m="1826">learn</span>
  <span m="2136">how</span> <span m="2445">semaphores</span> <span m="2755">can</span>
  <span m="3064">be</span> <span m="3373">used</span> <span m="3683">to</span> <span
  m="3992">ensure</span> <span m="4301">that</span> <span m="4611">different</span>
  <span m="4920">precedence</span> <span m="5230">constraints</span> <span m="5782">in</span>
  <span m="6335">our</span> <span m="6888">programs</span> <span m="7440">can</span>
  <span m="7993">be</span> <span m="8546">satisfied.</span></p><p><span m="9099">Before</span>
  <span m="9456">diving</span> <span m="9814">into</span> <span m="10172">the</span>
  <span m="10530">use</span> <span m="10888">of</span> <span m="11246">semaphores</span>
  <span m="11603">to</span> <span m="11961">enforce</span> <span m="12319">our</span>
  <span m="12677">precedence</span> <span m="13035">requirements,</span> <span m="13393">let's</span>
  <span m="13751">review</span> <span m="14143">what</span> <span m="14535">tools</span>
  <span m="14928">we</span> <span m="15320">have</span> <span m="15712">available</span>
  <span m="16105">to</span> <span m="16497">us.</span></p><p><span m="16890">You</span>
  <span m="17203">can</span> <span m="17516">think</span> <span m="17830">of</span>
  <span m="18143">a</span> <span m="18456">semaphore</span> <span m="18770">as</span>
  <span m="19083">a</span> <span m="19396">shared</span> <span m="19710">resource</span>
  <span m="20023">that</span> <span m="20336">is</span> <span m="20650">limited</span>
  <span m="20963">in</span> <span m="21276">quantity.</span></p><p><span m="21590">If</span>
  <span m="21919">we</span> <span m="22248">have</span> <span m="22578">a</span> <span
  m="22907">semaphore</span> <span m="23237">S</span> <span m="23566">that</span>
  <span m="23896">is</span> <span m="24225">initialized</span> <span m="24555">to</span>
  <span m="24884">0</span> <span m="25213">then</span> <span m="25543">it</span> <span
  m="25872">represents</span> <span m="26202">the</span> <span m="26531">fact</span>
  <span m="26861">that</span> <span m="27190">currently</span> <span m="27520">resource</span>
  <span m="28048">S</span> <span m="28576">is</span> <span m="29104">not</span> <span
  m="29632">available.</span></p><p><span m="30160">If</span> <span m="30545">S</span>
  <span m="30931">equals</span> <span m="31316">1,</span> <span m="31702">then</span>
  <span m="32087">that</span> <span m="32473">means</span> <span m="32858">that</span>
  <span m="33244">exactly</span> <span m="33630">one</span> <span m="34015">S</span>
  <span m="34401">resource</span> <span m="34786">is</span> <span m="35172">available</span>
  <span m="35557">for</span> <span m="35943">use.</span></p><p><span m="36329">If</span>
  <span m="36727">S</span> <span m="37126">equals</span> <span m="37524">2,</span>
  <span m="37923">then</span> <span m="38322">there</span> <span m="38720">are</span>
  <span m="39119">2</span> <span m="39518">S</span> <span m="39916">resources</span>
  <span m="40315">available,</span> <span m="40714">and</span> <span m="41112">so</span>
  <span m="41511">on.</span></p><p><span m="41910">In</span> <span m="42258">order</span>
  <span m="42606">to</span> <span m="42954">make</span> <span m="43302">use</span>
  <span m="43650">of</span> <span m="43998">the</span> <span m="44346">shared</span>
  <span m="44695">resource,</span> <span m="45043">a</span> <span m="45391">process</span>
  <span m="45739">must</span> <span m="46087">first</span> <span m="46435">grab</span>
  <span m="46783">that</span> <span m="47131">resource.</span></p><p><span m="47480">This</span>
  <span m="47882">is</span> <span m="48285">achieved</span> <span m="48688">by</span>
  <span m="49090">adding</span> <span m="49493">a</span> <span m="49896">wait(S)</span>
  <span m="50298">call</span> <span m="50701">before</span> <span m="51104">the</span>
  <span m="51506">code</span> <span m="51909">that</span> <span m="52312">requires</span>
  <span m="52714">the</span> <span m="53117">resource.</span></p><p><span m="53520">As</span>
  <span m="53805">long</span> <span m="54090">as</span> <span m="54375">the</span>
  <span m="54661">value</span> <span m="54946">of</span> <span m="55231">S</span>
  <span m="55516">equals</span> <span m="55802">0,</span> <span m="56087">the</span>
  <span m="56372">code</span> <span m="56657">that</span> <span m="56943">is</span>
  <span m="57228">waiting</span> <span m="57513">for</span> <span m="57798">this</span>
  <span m="58084">resource</span> <span m="58369">is</span> <span m="58654">stalled</span>
  <span m="58940">meaning</span> <span m="59440">that</span> <span m="59940">it</span>
  <span m="60440">can't</span> <span m="60940">get</span> <span m="61440">past</span>
  <span m="61940">the</span> <span m="62440">wait(S)</span> <span m="62940">command.</span></p><p><span
  m="63440">To</span> <span m="63804">get</span> <span m="64169">past</span> <span
  m="64534">the</span> <span m="64898">wait(S)</span> <span m="65263">call,</span>
  <span m="65628">the</span> <span m="65992">value</span> <span m="66357">of</span>
  <span m="66722">semaphore</span> <span m="67087">S</span> <span m="67451">must</span>
  <span m="67816">be</span> <span m="68181">greater</span> <span m="68545">than</span>
  <span m="68910">0,</span> <span m="69275">indicating</span> <span m="69640">that</span>
  <span m="70199">the</span> <span m="70759">resource</span> <span m="71319">is</span>
  <span m="71879">available.</span></p><p><span m="72439">Grabbing</span> <span m="72839">the</span>
  <span m="73240">resource</span> <span m="73641">is</span> <span m="74041">achieved</span>
  <span m="74442">by</span> <span m="74843">decrementing</span> <span m="75244">the</span>
  <span m="75644">value</span> <span m="76045">of</span> <span m="76446">the</span>
  <span m="76846">semaphore</span> <span m="77247">by</span> <span m="77648">1.</span></p><p><span
  m="78049">Analogous</span> <span m="78470">to</span> <span m="78891">the</span>
  <span m="79312">wait(S)</span> <span m="79733">command,</span> <span m="80154">we</span>
  <span m="80575">have</span> <span m="80996">a</span> <span m="81417">signal(S)</span>
  <span m="81838">command.</span></p><p><span m="82259">A</span> <span m="82699">signal</span>
  <span m="83139">of</span> <span m="83579">semaphore</span> <span m="84019">S</span>
  <span m="84459">indicates</span> <span m="84899">that</span> <span m="85339">one</span>
  <span m="85779">additional</span> <span m="86219">S</span> <span m="86659">resource</span>
  <span m="87099">has</span> <span m="87539">become</span> <span m="87979">available.</span></p><p><span
  m="88420">The</span> <span m="88803">signal(S)</span> <span m="89187">command</span>
  <span m="89571">increments</span> <span m="89955">the</span> <span m="90339">value</span>
  <span m="90723">of</span> <span m="91107">S</span> <span m="91491">by</span> <span
  m="91875">1.</span></p><p><span m="92259">The</span> <span m="92541">result</span>
  <span m="92823">of</span> <span m="93105">this</span> <span m="93387">is</span>
  <span m="93669">that</span> <span m="93951">a</span> <span m="94233">process</span>
  <span m="94515">that</span> <span m="94797">is</span> <span m="95079">waiting</span>
  <span m="95361">on</span> <span m="95643">S</span> <span m="95925">will</span> <span
  m="96207">now</span> <span m="96489">be</span> <span m="96771">able</span> <span
  m="97053">to</span> <span m="97335">grab</span> <span m="97617">it</span> <span
  m="97899">and</span> <span m="98237">proceed</span> <span m="98576">with</span>
  <span m="98915">the</span> <span m="99254">next</span> <span m="99593">line</span>
  <span m="99932">of</span> <span m="100271">code.</span></p><p><span m="100610">Now,</span>
  <span m="101121">lets</span> <span m="101633">consider</span> <span m="102145">two</span>
  <span m="102657">processes,</span> <span m="103169">P1</span> <span m="103680">and</span>
  <span m="104192">P2,</span> <span m="104704">that</span> <span m="105216">run</span>
  <span m="105728">concurrently.</span></p><p><span m="106240">P1</span> <span m="106611">has</span>
  <span m="106982">two</span> <span m="107354">sections</span> <span m="107725">of</span>
  <span m="108096">code</span> <span m="108468">where</span> <span m="108839">section</span>
  <span m="109210">A</span> <span m="109582">is</span> <span m="109953">followed</span>
  <span m="110324">by</span> <span m="110696">section</span> <span m="111067">B.</span></p><p><span
  m="111439">Similarly,</span> <span m="112037">P2</span> <span m="112635">has</span>
  <span m="113233">two</span> <span m="113832">sections</span> <span m="114430">which</span>
  <span m="115028">are</span> <span m="115626">C</span> <span m="116225">followed</span>
  <span m="116823">by</span> <span m="117421">D.</span></p><p><span m="118020">Within</span>
  <span m="118415">each</span> <span m="118810">process</span> <span m="119206">execution</span>
  <span m="119601">proceeds</span> <span m="119996">sequentially,</span> <span m="120392">so</span>
  <span m="120787">we</span> <span m="121182">are</span> <span m="121578">guaranteed</span>
  <span m="121973">that</span> <span m="122368">A</span> <span m="122764">will</span>
  <span m="123159">always</span> <span m="123554">precede</span> <span m="123950">B,</span>
  <span m="124318">and</span> <span m="124687">C</span> <span m="125055">will</span>
  <span m="125424">always</span> <span m="125792">precede</span> <span m="126161">D.</span>
  <span m="126529">Let's</span> <span m="126898">also</span> <span m="127266">assume</span>
  <span m="127635">that</span> <span m="128003">there</span> <span m="128372">is</span>
  <span m="128740">no</span> <span m="129109">looping</span> <span m="129478">and</span>
  <span m="129962">that</span> <span m="130447">each</span> <span m="130931">process</span>
  <span m="131416">runs</span> <span m="131900">exactly</span> <span m="132385">once.</span></p><p><span
  m="132870">We</span> <span m="133168">want</span> <span m="133466">to</span> <span
  m="133764">consider</span> <span m="134062">how</span> <span m="134360">we</span>
  <span m="134658">can</span> <span m="134956">make</span> <span m="135255">use</span>
  <span m="135553">of</span> <span m="135851">different</span> <span m="136149">semaphores</span>
  <span m="136447">to</span> <span m="136745">ensure</span> <span m="137043">any</span>
  <span m="137341">necessary</span> <span m="137640">precedence</span> <span m="138165">constraints</span>
  <span m="138691">in</span> <span m="139217">the</span> <span m="139743">code.</span></p><p><span
  m="140269">Suppose</span> <span m="140607">that</span> <span m="140945">the</span>
  <span m="141283">constraint</span> <span m="141621">that</span> <span m="141959">we</span>
  <span m="142298">need</span> <span m="142636">to</span> <span m="142974">satisfy</span>
  <span m="143312">is</span> <span m="143650">that</span> <span m="143989">the</span>
  <span m="144327">section</span> <span m="144665">B</span> <span m="145003">code</span>
  <span m="145341">completes</span> <span m="145680">before</span> <span m="146278">the</span>
  <span m="146877">section</span> <span m="147475">C</span> <span m="148074">code</span>
  <span m="148672">begins</span> <span m="149271">execution.</span></p><p><span m="149870">We</span>
  <span m="150237">can</span> <span m="150605">achieve</span> <span m="150972">this</span>
  <span m="151340">using</span> <span m="151707">semaphore</span> <span m="152075">S</span>
  <span m="152442">by</span> <span m="152810">first</span> <span m="153177">initializing</span>
  <span m="153545">the</span> <span m="153912">semaphore</span> <span m="154280">to</span>
  <span m="154647">0</span> <span m="155015">in</span> <span m="155382">shared</span>
  <span m="155750">memory.</span></p><p><span m="156880">Next,</span> <span m="157257">in</span>
  <span m="157635">order</span> <span m="158013">to</span> <span m="158391">ensure</span>
  <span m="158768">that</span> <span m="159146">section</span> <span m="159524">C</span>
  <span m="159902">code</span> <span m="160280">does</span> <span m="160657">not</span>
  <span m="161035">begin</span> <span m="161413">running</span> <span m="161791">too</span>
  <span m="162168">early,</span> <span m="162546">we</span> <span m="162924">add</span>
  <span m="163302">a</span> <span m="163680">wait(S)</span> <span m="164281">call</span>
  <span m="164882">before</span> <span m="165484">the</span> <span m="166085">section</span>
  <span m="166687">C</span> <span m="167288">code.</span></p><p><span m="167890">As</span>
  <span m="168186">long</span> <span m="168483">as</span> <span m="168780">S</span>
  <span m="169077">=</span> <span m="169374">0,</span> <span m="169671">the</span>
  <span m="169968">code</span> <span m="170265">in</span> <span m="170561">process</span>
  <span m="170858">P2</span> <span m="171155">will</span> <span m="171452">not</span>
  <span m="171749">get</span> <span m="172046">to</span> <span m="172343">run.</span></p><p><span
  m="172640">P1</span> <span m="172983">on</span> <span m="173326">the</span> <span
  m="173669">other</span> <span m="174012">hand,</span> <span m="174355">will</span>
  <span m="174698">not</span> <span m="175042">be</span> <span m="175385">constrained</span>
  <span m="175728">in</span> <span m="176071">this</span> <span m="176414">way,</span>
  <span m="176757">so</span> <span m="177101">section</span> <span m="177444">A</span>
  <span m="177787">code</span> <span m="178130">can</span> <span m="178473">begin</span>
  <span m="178816">running</span> <span m="179160">right</span> <span m="179979">away.</span></p><p><span
  m="180799">Since</span> <span m="181149">section</span> <span m="181499">B</span>
  <span m="181849">follows</span> <span m="182199">section</span> <span m="182549">A,</span>
  <span m="182899">it</span> <span m="183249">will</span> <span m="183599">be</span>
  <span m="183949">executed</span> <span m="184299">after</span> <span m="184649">section</span>
  <span m="184999">A.</span></p><p><span m="185349">Once</span> <span m="185816">B</span>
  <span m="186284">completes,</span> <span m="186751">process</span> <span m="187219">P1</span>
  <span m="187687">needs</span> <span m="188154">to</span> <span m="188622">signal</span>
  <span m="189090">our</span> <span m="189557">semaphore</span> <span m="190025">to</span>
  <span m="190493">indicate</span> <span m="190960">that</span> <span m="191428">it</span>
  <span m="191896">is</span> <span m="192363">now</span> <span m="192831">okay</span>
  <span m="193299">for</span> <span m="193723">process</span> <span m="194147">P2</span>
  <span m="194571">to</span> <span m="194996">begin</span> <span m="195420">its</span>
  <span m="195844">execution.</span></p><p><span m="196269">The</span> <span m="196694">signal(S)</span>
  <span m="197120">call</span> <span m="197545">will</span> <span m="197971">set</span>
  <span m="198397">S</span> <span m="198822">=</span> <span m="199248">1,</span> <span
  m="199673">which</span> <span m="200099">will</span> <span m="200525">allow</span>
  <span m="200950">P2</span> <span m="201376">to</span> <span m="201801">finally</span>
  <span m="202227">move</span> <span m="202653">beyond</span> <span m="203078">the</span>
  <span m="203504">wait(S)</span> <span m="203930">command.</span></p><p><span m="205030">Next,</span>
  <span m="205456">lets</span> <span m="205883">consider</span> <span m="206310">a</span>
  <span m="206737">slightly</span> <span m="207164">more</span> <span m="207591">complicated</span>
  <span m="208017">constraint</span> <span m="208444">where</span> <span m="208871">section</span>
  <span m="209298">D</span> <span m="209725">precedes</span> <span m="210152">section</span>
  <span m="210579">A,</span> <span m="211194">OR</span> <span m="211809">section</span>
  <span m="212425">B</span> <span m="213040">precedes</span> <span m="213656">section</span>
  <span m="214271">C.</span> <span m="214886">In</span> <span m="215502">other</span>
  <span m="216117">words,</span> <span m="216733">P1</span> <span m="217348">and</span>
  <span m="217963">P2</span> <span m="218579">cannot</span> <span m="219194">overlap.</span></p><p><span
  m="219810">One</span> <span m="220125">has</span> <span m="220440">to</span> <span
  m="220755">run</span> <span m="221070">followed</span> <span m="221386">by</span>
  <span m="221701">the</span> <span m="222016">other</span> <span m="222331">but</span>
  <span m="222646">either</span> <span m="222962">of</span> <span m="223277">them</span>
  <span m="223592">can</span> <span m="223907">be</span> <span m="224222">the</span>
  <span m="224538">one</span> <span m="224853">to</span> <span m="225168">run</span>
  <span m="225483">first.</span></p><p><span m="225799">To</span> <span m="226157">achieve</span>
  <span m="226516">this</span> <span m="226875">we</span> <span m="227233">want</span>
  <span m="227592">to</span> <span m="227951">use</span> <span m="228310">our</span>
  <span m="228668">S</span> <span m="229027">semaphore</span> <span m="229386">as</span>
  <span m="229745">a</span> <span m="230103">mutual</span> <span m="230462">exclusion</span>
  <span m="230821">semaphore.</span></p><p><span m="231180">A</span> <span m="231579">mutual</span>
  <span m="231979">exclusion</span> <span m="232379">semaphore,</span> <span m="232779">or</span>
  <span m="233179">mutex,</span> <span m="233579">ensures</span> <span m="233979">that</span>
  <span m="234379">only</span> <span m="234779">one</span> <span m="235179">complete</span>
  <span m="235579">block</span> <span m="235979">of</span> <span m="236379">code</span>
  <span m="236779">can</span> <span m="237179">run</span> <span m="237579">at</span>
  <span m="238059">a</span> <span m="238539">time</span> <span m="239019">without</span>
  <span m="239499">getting</span> <span m="239979">interrupted.</span></p><p><span
  m="240459">This</span> <span m="240784">can</span> <span m="241110">be</span> <span
  m="241435">achieved</span> <span m="241761">by</span> <span m="242086">initializing</span>
  <span m="242412">our</span> <span m="242737">semaphore</span> <span m="243063">S</span>
  <span m="243389">to</span> <span m="243714">1</span> <span m="244040">and</span>
  <span m="244365">having</span> <span m="244691">a</span> <span m="245016">wait(S)</span>
  <span m="245342">statement</span> <span m="245667">at</span> <span m="245993">the</span>
  <span m="246319">top</span> <span m="246884">of</span> <span m="247449">both</span>
  <span m="248014">processes.</span></p><p><span m="248579">Since</span> <span m="248890">S</span>
  <span m="249201">is</span> <span m="249512">initialized</span> <span m="249823">to</span>
  <span m="250134">1,</span> <span m="250445">only</span> <span m="250756">one</span>
  <span m="251067">of</span> <span m="251378">the</span> <span m="251689">two</span>
  <span m="252000">processes</span> <span m="252311">will</span> <span m="252622">be</span>
  <span m="252933">able</span> <span m="253244">to</span> <span m="253555">grab</span>
  <span m="253866">the</span> <span m="254177">S</span> <span m="254488">semaphore.</span></p><p><span
  m="254799">Whichever</span> <span m="255106">process</span> <span m="255413">happens</span>
  <span m="255720">to</span> <span m="256027">grab</span> <span m="256335">it</span>
  <span m="256642">first</span> <span m="256949">is</span> <span m="257256">the</span>
  <span m="257563">one</span> <span m="257871">that</span> <span m="258178">will</span>
  <span m="258485">run</span> <span m="258792">first.</span></p><p><span m="259100">There</span>
  <span m="259328">is</span> <span m="259556">one</span> <span m="259784">last</span>
  <span m="260012">piece</span> <span m="260241">of</span> <span m="260469">code</span>
  <span m="260697">we</span> <span m="260925">need</span> <span m="261154">to</span>
  <span m="261382">add</span> <span m="261610">to</span> <span m="261838">complete</span>
  <span m="262067">our</span> <span m="262295">requirements</span> <span m="262523">which</span>
  <span m="262751">is</span> <span m="262980">that</span> <span m="263433">at</span>
  <span m="263887">the</span> <span m="264340">end</span> <span m="264794">of</span>
  <span m="265248">both</span> <span m="265701">processes'</span> <span m="266155">code,</span>
  <span m="266609">we</span> <span m="267062">must</span> <span m="267516">signal(S).</span></p><p><span
  m="267970">If</span> <span m="268325">we</span> <span m="268680">do</span> <span
  m="269035">not</span> <span m="269390">signal(S)</span> <span m="269746">then</span>
  <span m="270101">only</span> <span m="270456">the</span> <span m="270811">process</span>
  <span m="271167">that</span> <span m="271522">happened</span> <span m="271877">to</span>
  <span m="272232">grab</span> <span m="272588">the</span> <span m="272943">S</span>
  <span m="273298">semaphore</span> <span m="273653">first</span> <span m="274009">will</span>
  <span m="274334">get</span> <span m="274660">to</span> <span m="274986">run</span>
  <span m="275312">while</span> <span m="275637">the</span> <span m="275963">other</span>
  <span m="276289">is</span> <span m="276615">stuck</span> <span m="276941">waiting</span>
  <span m="277266">for</span> <span m="277592">the</span> <span m="277918">S</span>
  <span m="278244">semaphore.</span></p><p><span m="278570">If</span> <span m="278893">at</span>
  <span m="279217">the</span> <span m="279541">end</span> <span m="279864">of</span>
  <span m="280188">the</span> <span m="280512">process,</span> <span m="280835">we</span>
  <span m="281159">signal</span> <span m="281483">S,</span> <span m="281806">then</span>
  <span m="282130">S</span> <span m="282454">gets</span> <span m="282777">incremented</span>
  <span m="283101">back</span> <span m="283425">to</span> <span m="283748">1</span>
  <span m="284072">thus</span> <span m="284396">allowing</span> <span m="284720">the</span>
  <span m="285256">next</span> <span m="285792">process</span> <span m="286328">to</span>
  <span m="286864">execute.</span></p><p><span m="287400">Note</span> <span m="287653">that</span>
  <span m="287906">because</span> <span m="288159">this</span> <span m="288412">code</span>
  <span m="288665">does</span> <span m="288918">not</span> <span m="289171">loop,</span>
  <span m="289425">there</span> <span m="289678">is</span> <span m="289931">no</span>
  <span m="290184">concern</span> <span m="290437">about</span> <span m="290690">the</span>
  <span m="290943">first</span> <span m="291196">process</span> <span m="291450">grabbing</span>
  <span m="291956">the</span> <span m="292462">S</span> <span m="292968">semaphore</span>
  <span m="293474">again.</span></p><p><span m="293980">Finally,</span> <span m="294415">lets</span>
  <span m="294850">consider</span> <span m="295285">one</span> <span m="295720">last</span>
  <span m="296155">set</span> <span m="296590">of</span> <span m="297025">constraints.</span></p><p><span
  m="297460">In</span> <span m="297791">this</span> <span m="298122">case,</span>
  <span m="298453">we</span> <span m="298784">want</span> <span m="299115">to</span>
  <span m="299446">ensure</span> <span m="299777">that</span> <span m="300108">the</span>
  <span m="300439">first</span> <span m="300770">section</span> <span m="301101">of</span>
  <span m="301432">both</span> <span m="301763">processes</span> <span m="302094">P1</span>
  <span m="302425">and</span> <span m="302756">P2</span> <span m="303087">run</span>
  <span m="303418">before</span> <span m="303750">the</span> <span m="304223">second</span>
  <span m="304697">section</span> <span m="305170">of</span> <span m="305644">processes</span>
  <span m="306118">P1</span> <span m="306591">and</span> <span m="307065">P2.</span></p><p><span
  m="307539">In</span> <span m="307882">other</span> <span m="308225">words</span>
  <span m="308568">A</span> <span m="308911">must</span> <span m="309254">precede</span>
  <span m="309598">B</span> <span m="309941">and</span> <span m="310284">D,</span>
  <span m="310627">and</span> <span m="310970">C</span> <span m="311314">must</span>
  <span m="311657">precede</span> <span m="312000">B</span> <span m="312343">and</span>
  <span m="312686">D.</span></p><p><span m="313030">The</span> <span m="313375">constraint</span>
  <span m="313721">that</span> <span m="314067">A</span> <span m="314413">must</span>
  <span m="314759">precede</span> <span m="315105">B,</span> <span m="315451">and</span>
  <span m="315797">C</span> <span m="316142">must</span> <span m="316488">precede</span>
  <span m="316834">D</span> <span m="317180">is</span> <span m="317526">satisfied</span>
  <span m="317872">by</span> <span m="318218">default</span> <span m="318564">because</span>
  <span m="318910">the</span> <span m="319338">code</span> <span m="319767">is</span>
  <span m="320195">always</span> <span m="320624">executed</span> <span m="321052">in</span>
  <span m="321481">order.</span></p><p><span m="321910">This</span> <span m="322381">means</span>
  <span m="322852">that</span> <span m="323324">our</span> <span m="323795">constraint</span>
  <span m="324266">reduces</span> <span m="324738">to</span> <span m="325209">A</span>
  <span m="325680">preceding</span> <span m="326152">D,</span> <span m="326623">and</span>
  <span m="327094">C</span> <span m="327566">preceding</span> <span m="328037">B.</span></p><p><span
  m="328509">To</span> <span m="328985">achieve</span> <span m="329461">this,</span>
  <span m="329937">we</span> <span m="330413">need</span> <span m="330889">to</span>
  <span m="331366">use</span> <span m="331842">two</span> <span m="332318">semaphores,</span>
  <span m="332794">say</span> <span m="333270">S</span> <span m="333746">and</span>
  <span m="334223">T</span> <span m="334699">and</span> <span m="335175">initialize</span>
  <span m="335651">them</span> <span m="336127">to</span> <span m="336603">0.</span></p><p><span
  m="337080">After</span> <span m="337375">the</span> <span m="337671">first</span>
  <span m="337966">section</span> <span m="338262">of</span> <span m="338558">a</span>
  <span m="338853">process</span> <span m="339149">completes,</span> <span m="339445">it</span>
  <span m="339740">should</span> <span m="340036">signal</span> <span m="340331">to</span>
  <span m="340627">the</span> <span m="340923">other</span> <span m="341218">process</span>
  <span m="341514">that</span> <span m="341810">it</span> <span m="342129">may</span>
  <span m="342448">begin</span> <span m="342768">its</span> <span m="343087">second</span>
  <span m="343407">section</span> <span m="343726">of</span> <span m="344046">code</span>
  <span m="344365">provided</span> <span m="344685">that</span> <span m="345004">it</span>
  <span m="345324">has</span> <span m="345643">already</span> <span m="345963">completed</span>
  <span m="346282">its</span> <span m="346602">first</span> <span m="346921">section</span>
  <span m="347241">of</span> <span m="347741">code.</span></p><p><span m="348241">To</span>
  <span m="348549">ensure</span> <span m="348858">that</span> <span m="349167">it</span>
  <span m="349475">has</span> <span m="349784">already</span> <span m="350093">completed</span>
  <span m="350401">its</span> <span m="350710">first</span> <span m="351019">section</span>
  <span m="351327">of</span> <span m="351636">code,</span> <span m="351945">we</span>
  <span m="352253">place</span> <span m="352562">the</span> <span m="352871">signal</span>
  <span m="353180">calls</span> <span m="353621">between</span> <span m="354062">the</span>
  <span m="354503">two</span> <span m="354944">sections</span> <span m="355385">of</span>
  <span m="355826">code</span> <span m="356267">in</span> <span m="356708">each</span>
  <span m="357149">process.</span></p><p><span m="357590">In</span> <span m="357928">addition</span>
  <span m="358266">to</span> <span m="358604">signaling</span> <span m="358942">the</span>
  <span m="359280">other</span> <span m="359618">process</span> <span m="359956">that</span>
  <span m="360294">it</span> <span m="360632">may</span> <span m="360970">proceed,</span>
  <span m="361308">each</span> <span m="361646">of</span> <span m="361984">the</span>
  <span m="362322">processes</span> <span m="362660">needs</span> <span m="363017">to</span>
  <span m="363374">wait</span> <span m="363732">for</span> <span m="364089">the</span>
  <span m="364447">semaphore</span> <span m="364804">that</span> <span m="365161">the</span>
  <span m="365519">other</span> <span m="365876">process</span> <span m="366234">is</span>
  <span m="366591">signaling.</span></p><p><span m="366949">This</span> <span m="367261">combination</span>
  <span m="367573">of</span> <span m="367886">signal</span> <span m="368198">and</span>
  <span m="368510">wait</span> <span m="368823">ensures</span> <span m="369135">that</span>
  <span m="369447">sections</span> <span m="369760">A</span> <span m="370072">and</span>
  <span m="370384">C</span> <span m="370697">of</span> <span m="371009">the</span>
  <span m="371321">code</span> <span m="371634">will</span> <span m="371946">run</span>
  <span m="372259">before</span> <span m="372751">sections</span> <span m="373244">B</span>
  <span m="373736">and</span> <span m="374229">D.</span> <span m="374721">Since</span>
  <span m="375214">the</span> <span m="375706">semaphores</span> <span m="376199">are</span>
  <span m="376691">initialized</span> <span m="377184">to</span> <span m="377676">0,</span>
  <span m="378169">the</span> <span m="378537">wait(S)</span> <span m="378905">will</span>
  <span m="379273">not</span> <span m="379641">complete</span> <span m="380009">until</span>
  <span m="380378">P1</span> <span m="380746">calls</span> <span m="381114">signal(S)</span>
  <span m="381482">at</span> <span m="381850">which</span> <span m="382219">point</span>
  <span m="382587">it</span> <span m="382955">has</span> <span m="383323">already</span>
  <span m="383691">completed</span> <span m="384060">section</span> <span m="384676">A.</span>
  <span m="385293">Similarly,</span> <span m="385910">the</span> <span m="386526">wait(T)</span>
  <span m="387143">will</span> <span m="387760">not</span> <span m="388376">complete</span>
  <span m="388993">until</span> <span m="389610">P2</span> <span m="390138">calls</span>
  <span m="390666">signal(T)</span> <span m="391195">at</span> <span m="391723">which</span>
  <span m="392251">point</span> <span m="392780">it</span> <span m="393308">has</span>
  <span m="393836">already</span> <span m="394365">completed</span> <span m="394893">section</span>
  <span m="395421">C.</span></p><p><span m="395950">So</span> <span m="396266">once</span>
  <span m="396582">the</span> <span m="396898">processes</span> <span m="397214">can</span>
  <span m="397530">get</span> <span m="397847">past</span> <span m="398163">their</span>
  <span m="398479">wait</span> <span m="398795">commands,</span> <span m="399111">we</span>
  <span m="399428">are</span> <span m="399744">guaranteed</span> <span m="400060">that</span>
  <span m="400376">both</span> <span m="400692">first</span> <span m="401009">sections</span>
  <span m="401514">of</span> <span m="402019">code</span> <span m="402524">have</span>
  <span m="403029">already</span> <span m="403534">run.</span></p><p><span m="404040">We</span>
  <span m="404382">have</span> <span m="404724">also</span> <span m="405066">not</span>
  <span m="405408">forced</span> <span m="405750">any</span> <span m="406092">additional</span>
  <span m="406434">constraints</span> <span m="406776">by</span> <span m="407118">requiring</span>
  <span m="407460">A</span> <span m="407802">to</span> <span m="408144">run</span>
  <span m="408486">before</span> <span m="408828">C</span> <span m="409170">or</span>
  <span m="409512">C</span> <span m="409854">to</span> <span m="410196">run</span>
  <span m="410539">before</span> <span m="411335">A,</span> <span m="412131">and</span>
  <span m="412927">so</span> <span m="413723">on.</span></p><p><span m="414520">Of</span>
  <span m="414757">course</span> <span m="414994">we</span> <span m="415232">could</span>
  <span m="415469">have</span> <span m="415706">swapped</span> <span m="415944">our</span>
  <span m="416181">use</span> <span m="416418">of</span> <span m="416656">the</span>
  <span m="416893">S</span> <span m="417131">and</span> <span m="417368">T</span>
  <span m="417605">semaphores</span> <span m="417843">and</span> <span m="418080">ended</span>
  <span m="418317">up</span> <span m="418555">with</span> <span m="418792">exactly</span>
  <span m="419030">the</span> <span m="419510">same</span> <span m="419990">behavior.</span></p><p><span
  m="420470">Note,</span> <span m="420910">however,</span> <span m="421351">that</span>
  <span m="421792">we</span> <span m="422233">cannot</span> <span m="422673">swap</span>
  <span m="423114">the</span> <span m="423555">signal</span> <span m="423996">and</span>
  <span m="424436">wait</span> <span m="424877">commands</span> <span m="425318">around.</span></p><p><span
  m="425759">If</span> <span m="426118">we</span> <span m="426477">tried</span> <span
  m="426837">to</span> <span m="427196">call</span> <span m="427556">wait</span> <span
  m="427915">before</span> <span m="428274">signal,</span> <span m="428634">then</span>
  <span m="428993">both</span> <span m="429353">processes</span> <span m="429712">would</span>
  <span m="430071">get</span> <span m="430431">deadlocked</span> <span m="430790">waiting</span>
  <span m="431150">for</span> <span m="431551">a</span> <span m="431952">semaphore</span>
  <span m="432354">that</span> <span m="432755">never</span> <span m="433157">gets</span>
  <span m="433558">signaled.</span></p><p><span m="433960">This</span> <span m="434268">highlights</span>
  <span m="434576">the</span> <span m="434884">fact</span> <span m="435192">that</span>
  <span m="435501">when</span> <span m="435809">using</span> <span m="436117">semaphores</span>
  <span m="436425">you</span> <span m="436734">must</span> <span m="437042">always</span>
  <span m="437350">be</span> <span m="437658">very</span> <span m="437967">careful</span>
  <span m="438275">to</span> <span m="438583">not</span> <span m="438891">only</span>
  <span m="439200">worry</span> <span m="439622">about</span> <span m="440044">satisfying</span>
  <span m="440466">the</span> <span m="440888">desired</span> <span m="441310">requirements,</span>
  <span m="441732">but</span> <span m="442155">also</span> <span m="442577">ensuring</span>
  <span m="442999">that</span> <span m="443421">there</span> <span m="443843">is</span>
  <span m="444265">no</span> <span m="444687">possibility</span> <span m="445110">of</span>
  <span m="445472">ending</span> <span m="445835">up</span> <span m="446198">in</span>
  <span m="446561">a</span> <span m="446924">deadlock</span> <span m="447287">situation</span>
  <span m="447650">where</span> <span m="448013">one</span> <span m="448376">or</span>
  <span m="448739">more</span> <span m="449102">processes</span> <span m="449465">can</span>
  <span m="449828">never</span> <span m="450191">run</span> <span m="450554">to</span>
  <span m="450917">completion.</span></p>
type: course
uid: be6b6d09f2fd2f6de776402b88478d1c

---
None