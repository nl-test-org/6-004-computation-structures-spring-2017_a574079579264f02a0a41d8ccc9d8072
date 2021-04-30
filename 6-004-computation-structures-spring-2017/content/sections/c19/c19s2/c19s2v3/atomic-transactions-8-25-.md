---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 776ZuSOo6hg
  parent_uid: 4e953b6237a0d849df8554e08e30848b
  title: Video-YouTube-Stream
  type: Video
  uid: 1d993f29e9a1cc9012d02112f65415f4
- id: 3Play-3Play YouTube id-Stream
  media_location: 776ZuSOo6hg
  parent_uid: 4e953b6237a0d849df8554e08e30848b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 6284ed79f43cb77043f30e2456b07289
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/776ZuSOo6hg/default.jpg
  parent_uid: 4e953b6237a0d849df8554e08e30848b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 74debcd111bb0290ea5949082bb6e9e4
- id: 776ZuSOo6hg.srt
  parent_uid: 4e953b6237a0d849df8554e08e30848b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v3/atomic-transactions-8-25-/776ZuSOo6hg.srt
  title: 3play caption file
  type: null
  uid: b96272893cf42e411d3e1a0446f28e37
- id: 776ZuSOo6hg.pdf
  parent_uid: 4e953b6237a0d849df8554e08e30848b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v3/atomic-transactions-8-25-/776ZuSOo6hg.pdf
  title: 3play pdf file
  type: null
  uid: 563442b91ed5f3c4de5cb4934247a32b
- id: Caption-3Play YouTube id-SRT
  parent_uid: 4e953b6237a0d849df8554e08e30848b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 40743081e6c711937208ac62b93d9528
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 4e953b6237a0d849df8554e08e30848b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 0cd671ca0c8f95015c3b7ec322a28399
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_19-02-03_300k.mp4
  parent_uid: 4e953b6237a0d849df8554e08e30848b
  title: Video-Internet Archive-MP4
  type: Video
  uid: 54cb5b7f73ed970268df09e24383aebc
inline_embed_id: 22848513atomictransactions82583073558
layout: video
order_index: null
parent_uid: e37248abdfaee36d61583525d837351c
related_resources_text: ''
short_url: atomic-transactions-8-25-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v3/atomic-transactions-8-25-
template_type: Embed
title: Atomic Transactions
transcript: <p><span m="729">Let's</span> <span m="1001">take</span> <span m="1273">a</span>
  <span m="1545">moment</span> <span m="1817">to</span> <span m="2089">look</span>
  <span m="2361">at</span> <span m="2633">a</span> <span m="2905">different</span>
  <span m="3177">example.</span></p><p><span m="3450">Automated</span> <span m="3860">teller</span>
  <span m="4270">machines</span> <span m="4680">allow</span> <span m="5090">bank</span>
  <span m="5500">customers</span> <span m="5910">to</span> <span m="6320">perform</span>
  <span m="6730">a</span> <span m="7140">variety</span> <span m="7550">of</span> <span
  m="7960">transactions:</span> <span m="8370">deposits,</span> <span m="8780">withdrawals,</span>
  <span m="9566">transfers,</span> <span m="10352">etc.</span></p><p><span m="11139">Let's</span>
  <span m="11500">consider</span> <span m="11861">what</span> <span m="12223">happens</span>
  <span m="12584">when</span> <span m="12946">two</span> <span m="13307">customers</span>
  <span m="13668">try</span> <span m="14030">to</span> <span m="14391">withdraw</span>
  <span m="14753">$50</span> <span m="15114">from</span> <span m="15475">the</span>
  <span m="15837">same</span> <span m="16198">account</span> <span m="16560">at</span>
  <span m="16817">the</span> <span m="17074">same</span> <span m="17331">time.</span></p><p><span
  m="17589">A</span> <span m="17940">portion</span> <span m="18292">of</span> <span
  m="18644">the</span> <span m="18996">bank's</span> <span m="19348">code</span> <span
  m="19700">for</span> <span m="20052">a</span> <span m="20404">withdrawal</span>
  <span m="20756">transaction</span> <span m="21108">is</span> <span m="21460">shown</span>
  <span m="21812">in</span> <span m="22164">the</span> <span m="22516">upper</span>
  <span m="22868">right.</span></p><p><span m="23220">This</span> <span m="23573">code</span>
  <span m="23927">is</span> <span m="24281">responsible</span> <span m="24635">for</span>
  <span m="24989">adjusting</span> <span m="25343">the</span> <span m="25697">account</span>
  <span m="26051">balance</span> <span m="26405">to</span> <span m="26759">reflect</span>
  <span m="27113">the</span> <span m="27467">amount</span> <span m="27821">of</span>
  <span m="28175">the</span> <span m="28529">withdrawal.</span></p><p><span m="29529">Presumably</span>
  <span m="29799">the</span> <span m="30070">check</span> <span m="30341">to</span>
  <span m="30612">see</span> <span m="30883">if</span> <span m="31154">there</span>
  <span m="31424">is</span> <span m="31695">sufficient</span> <span m="31966">funds</span>
  <span m="32237">has</span> <span m="32508">already</span> <span m="32779">happened.</span></p><p><span
  m="33050">What's</span> <span m="33587">supposed</span> <span m="34125">to</span>
  <span m="34662">happen?</span></p><p><span m="35200">Let's</span> <span m="35530">assume</span>
  <span m="35861">that</span> <span m="36191">the</span> <span m="36522">bank</span>
  <span m="36852">is</span> <span m="37183">using</span> <span m="37513">a</span>
  <span m="37844">separate</span> <span m="38175">process</span> <span m="38505">to</span>
  <span m="38836">handle</span> <span m="39166">each</span> <span m="39497">transaction,</span>
  <span m="39827">so</span> <span m="40158">the</span> <span m="40489">two</span>
  <span m="40909">withdrawal</span> <span m="41329">transactions</span> <span m="41749">cause</span>
  <span m="42169">two</span> <span m="42589">different</span> <span m="43009">processes</span>
  <span m="43429">to</span> <span m="43849">be</span> <span m="44269">created,</span>
  <span m="44689">each</span> <span m="45109">of</span> <span m="45529">which</span>
  <span m="45949">will</span> <span m="46370">run</span> <span m="47024">the</span>
  <span m="47679">Debit</span> <span m="48334">code.</span></p><p><span m="48989">If</span>
  <span m="49345">each</span> <span m="49702">of</span> <span m="50058">the</span>
  <span m="50415">calls</span> <span m="50771">to</span> <span m="51128">Debit</span>
  <span m="51484">run</span> <span m="51841">to</span> <span m="52197">completion</span>
  <span m="52554">without</span> <span m="52910">interruption,</span> <span m="53267">we</span>
  <span m="53623">get</span> <span m="53980">the</span> <span m="54336">desired</span>
  <span m="54693">outcome:</span> <span m="55050">the</span> <span m="55395">first</span>
  <span m="55741">transaction</span> <span m="56087">debits</span> <span m="56432">the</span>
  <span m="56778">account</span> <span m="57124">by</span> <span m="57470">$50,</span>
  <span m="57815">then</span> <span m="58161">the</span> <span m="58507">second</span>
  <span m="58852">transaction</span> <span m="59198">does</span> <span m="59544">the</span>
  <span m="59890">same.</span></p><p><span m="61210">The</span> <span m="61551">net</span>
  <span m="61893">result</span> <span m="62235">is</span> <span m="62577">that</span>
  <span m="62918">you</span> <span m="63260">and</span> <span m="63602">your</span>
  <span m="63944">friend</span> <span m="64285">have</span> <span m="64627">$100</span>
  <span m="64969">and</span> <span m="65311">the</span> <span m="65652">balance</span>
  <span m="65994">is</span> <span m="66336">$100</span> <span m="66678">less.</span></p><p><span
  m="67020">So</span> <span m="67507">far,</span> <span m="67995">so</span> <span
  m="68482">good.</span></p><p><span m="68970">But</span> <span m="69358">what</span>
  <span m="69746">if</span> <span m="70134">the</span> <span m="70522">process</span>
  <span m="70911">for</span> <span m="71299">the</span> <span m="71687">first</span>
  <span m="72075">transaction</span> <span m="72464">is</span> <span m="72852">interrupted</span>
  <span m="73240">just</span> <span m="73628">after</span> <span m="74017">it's</span>
  <span m="74405">read</span> <span m="74793">the</span> <span m="75181">balance?</span></p><p><span
  m="75570">The</span> <span m="76009">second</span> <span m="76448">process</span>
  <span m="76887">subtracts</span> <span m="77326">$50</span> <span m="77765">from</span>
  <span m="78204">the</span> <span m="78643">balance,</span> <span m="79082">completing</span>
  <span m="79521">that</span> <span m="79960">transaction.</span></p><p><span m="80400">Now</span>
  <span m="80800">the</span> <span m="81200">first</span> <span m="81600">process</span>
  <span m="82000">resumes,</span> <span m="82400">using</span> <span m="82800">the</span>
  <span m="83200">now</span> <span m="83600">out-of-date</span> <span m="84000">balance</span>
  <span m="84400">it</span> <span m="84800">loaded</span> <span m="85200">just</span>
  <span m="85600">before</span> <span m="86000">being</span> <span m="86830">interrupted.</span></p><p><span
  m="87660">The</span> <span m="87930">net</span> <span m="88200">result</span> <span
  m="88470">is</span> <span m="88740">that</span> <span m="89010">you</span> <span
  m="89280">and</span> <span m="89550">your</span> <span m="89820">friend</span> <span
  m="90090">have</span> <span m="90360">$100,</span> <span m="90630">but</span> <span
  m="90900">the</span> <span m="91170">balance</span> <span m="91440">has</span> <span
  m="91710">only</span> <span m="91980">been</span> <span m="92250">debited</span>
  <span m="92520">by</span> <span m="93785">$50.</span></p><p><span m="95050">The</span>
  <span m="95252">moral</span> <span m="95454">of</span> <span m="95656">the</span>
  <span m="95858">story</span> <span m="96061">is</span> <span m="96263">that</span>
  <span m="96465">we</span> <span m="96667">need</span> <span m="96870">to</span>
  <span m="97072">be</span> <span m="97274">careful</span> <span m="97476">when</span>
  <span m="97678">writing</span> <span m="97881">code</span> <span m="98083">that</span>
  <span m="98285">reads</span> <span m="98487">and</span> <span m="98690">writes</span>
  <span m="99058">shared</span> <span m="99426">data</span> <span m="99794">since</span>
  <span m="100162">other</span> <span m="100530">processes</span> <span m="100898">might</span>
  <span m="101266">modify</span> <span m="101635">the</span> <span m="102003">data</span>
  <span m="102371">in</span> <span m="102739">the</span> <span m="103107">middle</span>
  <span m="103475">of</span> <span m="103843">our</span> <span m="104211">execution.</span></p><p><span
  m="104580">When,</span> <span m="105035">say,</span> <span m="105490">updating</span>
  <span m="105946">a</span> <span m="106401">shared</span> <span m="106856">memory</span>
  <span m="107312">location,</span> <span m="107767">we'll</span> <span m="108222">need</span>
  <span m="108678">to</span> <span m="109133">LD</span> <span m="109588">the</span>
  <span m="110044">current</span> <span m="110499">value,</span> <span m="110954">modify</span>
  <span m="111410">it,</span> <span m="111913">then</span> <span m="112416">ST</span>
  <span m="112920">the</span> <span m="113423">updated</span> <span m="113926">value.</span></p><p><span
  m="114430">We</span> <span m="114738">would</span> <span m="115046">like</span>
  <span m="115354">to</span> <span m="115662">ensure</span> <span m="115970">that</span>
  <span m="116278">no</span> <span m="116586">other</span> <span m="116895">processes</span>
  <span m="117203">access</span> <span m="117511">the</span> <span m="117819">shared</span>
  <span m="118127">location</span> <span m="118435">between</span> <span m="118743">the</span>
  <span m="119051">start</span> <span m="119360">of</span> <span m="119764">the</span>
  <span m="120168">LD</span> <span m="120573">and</span> <span m="120977">the</span>
  <span m="121382">completion</span> <span m="121786">of</span> <span m="122191">the</span>
  <span m="122595">ST.</span></p><p><span m="123000">The</span> <span m="123497">LD/modify/ST</span>
  <span m="123994">code</span> <span m="124491">sequence</span> <span m="124989">is</span>
  <span m="125486">what</span> <span m="125983">we</span> <span m="126480">call</span>
  <span m="126978">a</span> <span m="127475">&quot;critical</span> <span m="127972">section&quot;.</span></p><p><span
  m="128470">We</span> <span m="128766">need</span> <span m="129063">to</span> <span
  m="129360">arrange</span> <span m="129657">that</span> <span m="129954">other</span>
  <span m="130251">processes</span> <span m="130548">attempting</span> <span m="130845">to</span>
  <span m="131141">execute</span> <span m="131438">the</span> <span m="131735">same</span>
  <span m="132032">critical</span> <span m="132329">section</span> <span m="132626">are</span>
  <span m="132923">delayed</span> <span m="133220">until</span> <span m="133851">our</span>
  <span m="134483">execution</span> <span m="135115">is</span> <span m="135747">complete.</span></p><p><span
  m="136379">This</span> <span m="136762">constraint</span> <span m="137146">is</span>
  <span m="137530">called</span> <span m="137914">&quot;mutual</span> <span m="138297">exclusion&quot;,</span>
  <span m="138681">i.e.,</span> <span m="139065">only</span> <span m="139449">one</span>
  <span m="139832">process</span> <span m="140216">at</span> <span m="140600">a</span>
  <span m="140984">time</span> <span m="141367">can</span> <span m="141751">be</span>
  <span m="142135">executing</span> <span m="142519">code</span> <span m="143262">in</span>
  <span m="144006">the</span> <span m="144749">same</span> <span m="145493">critical</span>
  <span m="146236">section.</span></p><p><span m="146980">Once</span> <span m="147404">we've</span>
  <span m="147829">identified</span> <span m="148253">critical</span> <span m="148678">sections,</span>
  <span m="149103">we'll</span> <span m="149527">use</span> <span m="149952">semaphores</span>
  <span m="150376">to</span> <span m="150801">guarantee</span> <span m="151226">they</span>
  <span m="151650">execute</span> <span m="152075">atomically,</span> <span m="152500">i.e.,</span>
  <span m="152876">that</span> <span m="153252">once</span> <span m="153628">execution</span>
  <span m="154004">of</span> <span m="154380">the</span> <span m="154756">critical</span>
  <span m="155132">section</span> <span m="155508">begins,</span> <span m="155884">no</span>
  <span m="156260">other</span> <span m="156636">process</span> <span m="157012">will</span>
  <span m="157388">be</span> <span m="157764">able</span> <span m="158140">to</span>
  <span m="158591">enter</span> <span m="159042">the</span> <span m="159493">critical</span>
  <span m="159944">section</span> <span m="160395">until</span> <span m="160846">the</span>
  <span m="161297">execution</span> <span m="161748">is</span> <span m="162199">complete.</span></p><p><span
  m="162650">The</span> <span m="163019">combination</span> <span m="163388">of</span>
  <span m="163757">the</span> <span m="164126">semaphore</span> <span m="164496">to</span>
  <span m="164865">enforce</span> <span m="165234">the</span> <span m="165603">mutual</span>
  <span m="165972">exclusion</span> <span m="166342">constraint</span> <span m="166711">and</span>
  <span m="167080">the</span> <span m="167449">critical</span> <span m="167819">section</span>
  <span m="168265">of</span> <span m="168711">code</span> <span m="169158">implement</span>
  <span m="169604">what's</span> <span m="170050">called</span> <span m="170497">a</span>
  <span m="170943">&quot;transaction&quot;.</span></p><p><span m="171390">A</span>
  <span m="171722">transaction</span> <span m="172055">can</span> <span m="172387">perform</span>
  <span m="172720">multiple</span> <span m="173053">reads</span> <span m="173385">and</span>
  <span m="173718">writes</span> <span m="174050">of</span> <span m="174383">shared</span>
  <span m="174716">data</span> <span m="175048">with</span> <span m="175381">the</span>
  <span m="175713">guarantee</span> <span m="176046">that</span> <span m="176379">none</span>
  <span m="176704">of</span> <span m="177030">the</span> <span m="177356">data</span>
  <span m="177682">will</span> <span m="178008">be</span> <span m="178334">read</span>
  <span m="178660">or</span> <span m="178986">written</span> <span m="179312">by</span>
  <span m="179638">other</span> <span m="179964">processes</span> <span m="180290">while</span>
  <span m="180616">the</span> <span m="180942">transaction</span> <span m="181268">is</span>
  <span m="181594">in</span> <span m="181920">progress.</span></p><p><span m="182920">Here's</span>
  <span m="183225">the</span> <span m="183531">original</span> <span m="183837">code</span>
  <span m="184142">to</span> <span m="184448">Debit,</span> <span m="184754">which</span>
  <span m="185060">we'll</span> <span m="185365">modify</span> <span m="185671">by</span>
  <span m="185977">adding</span> <span m="186282">a</span> <span m="186588">LOCK</span>
  <span m="186894">semaphore.</span></p><p><span m="187200">In</span> <span m="187461">this</span>
  <span m="187723">case,</span> <span m="187985">the</span> <span m="188247">resource</span>
  <span m="188508">controlled</span> <span m="188770">by</span> <span m="189032">the</span>
  <span m="189294">semaphore</span> <span m="189555">is</span> <span m="189817">the</span>
  <span m="190079">right</span> <span m="190341">to</span> <span m="190602">run</span>
  <span m="190864">the</span> <span m="191126">code</span> <span m="191388">in</span>
  <span m="191650">the</span> <span m="192289">critical</span> <span m="192929">section.</span></p><p><span
  m="193569">By</span> <span m="193944">initializing</span> <span m="194319">LOCK</span>
  <span m="194694">to</span> <span m="195069">1,</span> <span m="195444">we're</span>
  <span m="195819">saying</span> <span m="196194">that</span> <span m="196569">at</span>
  <span m="196944">most</span> <span m="197319">one</span> <span m="197694">process</span>
  <span m="198069">can</span> <span m="198444">execute</span> <span m="198819">the</span>
  <span m="199194">critical</span> <span m="199569">section</span> <span m="199941">at</span>
  <span m="200314">a</span> <span m="200687">time.</span></p><p><span m="201060">A</span>
  <span m="201498">process</span> <span m="201936">running</span> <span m="202374">the</span>
  <span m="202812">Debit</span> <span m="203250">code</span> <span m="203688">WAITs</span>
  <span m="204126">on</span> <span m="204564">the</span> <span m="205002">LOCK</span>
  <span m="205440">semaphore.</span></p><p><span m="205879">If</span> <span m="206215">the</span>
  <span m="206552">value</span> <span m="206889">of</span> <span m="207225">LOCK</span>
  <span m="207562">is</span> <span m="207899">1,</span> <span m="208236">the</span>
  <span m="208572">WAIT</span> <span m="208909">will</span> <span m="209246">decrement</span>
  <span m="209582">value</span> <span m="209919">of</span> <span m="210256">LOCK</span>
  <span m="210593">to</span> <span m="210929">0</span> <span m="211266">and</span>
  <span m="211603">let</span> <span m="211939">the</span> <span m="212276">process</span>
  <span m="212613">enter</span> <span m="212950">the</span> <span m="213576">critical</span>
  <span m="214202">section.</span></p><p><span m="214829">This</span> <span m="215290">is</span>
  <span m="215752">called</span> <span m="216214">acquiring</span> <span m="216675">the</span>
  <span m="217137">lock.</span></p><p><span m="217599">If</span> <span m="217878">the</span>
  <span m="218157">value</span> <span m="218437">of</span> <span m="218716">LOCK</span>
  <span m="218996">is</span> <span m="219275">0,</span> <span m="219555">some</span>
  <span m="219834">other</span> <span m="220114">process</span> <span m="220393">has</span>
  <span m="220672">acquired</span> <span m="220952">the</span> <span m="221231">lock</span>
  <span m="221511">and</span> <span m="221790">is</span> <span m="222070">executing</span>
  <span m="222349">the</span> <span m="222629">critical</span> <span m="223102">section</span>
  <span m="223575">and</span> <span m="224048">our</span> <span m="224521">execution</span>
  <span m="224994">is</span> <span m="225467">suspended</span> <span m="225940">until</span>
  <span m="226413">the</span> <span m="226886">LOCK</span> <span m="227359">value</span>
  <span m="227832">is</span> <span m="228305">non-zero.</span></p><p><span m="228779">When</span>
  <span m="229115">the</span> <span m="229451">process</span> <span m="229788">completes</span>
  <span m="230124">execution</span> <span m="230461">of</span> <span m="230797">the</span>
  <span m="231134">critical</span> <span m="231470">section,</span> <span m="231806">it</span>
  <span m="232143">releases</span> <span m="232479">the</span> <span m="232816">LOCK</span>
  <span m="233152">with</span> <span m="233489">a</span> <span m="233867">call</span>
  <span m="234246">to</span> <span m="234624">SIGNAL,</span> <span m="235003">which</span>
  <span m="235382">will</span> <span m="235760">allow</span> <span m="236139">other</span>
  <span m="236518">processes</span> <span m="236896">to</span> <span m="237275">enter</span>
  <span m="237654">the</span> <span m="238032">critical</span> <span m="238411">section.</span></p><p><span
  m="238790">If</span> <span m="239078">there</span> <span m="239367">are</span> <span
  m="239656">multiple</span> <span m="239944">WAITing</span> <span m="240233">processes,</span>
  <span m="240522">only</span> <span m="240810">one</span> <span m="241099">will</span>
  <span m="241388">be</span> <span m="241676">able</span> <span m="241965">to</span>
  <span m="242254">acquire</span> <span m="242542">the</span> <span m="242831">lock,</span>
  <span m="243120">and</span> <span m="243409">the</span> <span m="243743">others</span>
  <span m="244077">will</span> <span m="244412">still</span> <span m="244746">have</span>
  <span m="245081">to</span> <span m="245415">wait</span> <span m="245750">their</span>
  <span m="246084">turn.</span></p><p><span m="246419">Used</span> <span m="246827">in</span>
  <span m="247236">this</span> <span m="247644">manner,</span> <span m="248053">semaphores</span>
  <span m="248461">are</span> <span m="248870">implementing</span> <span m="249278">a</span>
  <span m="249687">mutual</span> <span m="250095">exclusion</span> <span m="250504">constraint,</span>
  <span m="250912">i.e.,</span> <span m="251321">there's</span> <span m="251730">a</span>
  <span m="252178">guarantee</span> <span m="252626">that</span> <span m="253074">two</span>
  <span m="253522">executions</span> <span m="253970">of</span> <span m="254419">the</span>
  <span m="254867">critical</span> <span m="255315">section</span> <span m="255763">cannot</span>
  <span m="256211">overlap.</span></p><p><span m="256660">Note</span> <span m="256962">that</span>
  <span m="257265">if</span> <span m="257567">multiple</span> <span m="257870">processes</span>
  <span m="258172">need</span> <span m="258475">to</span> <span m="258777">execute</span>
  <span m="259080">the</span> <span m="259382">critical</span> <span m="259685">section,</span>
  <span m="259987">they</span> <span m="260290">may</span> <span m="260592">run</span>
  <span m="260895">in</span> <span m="261197">any</span> <span m="261500">order</span>
  <span m="261997">and</span> <span m="262495">the</span> <span m="262992">only</span>
  <span m="263490">guarantee</span> <span m="263987">is</span> <span m="264485">that</span>
  <span m="264982">their</span> <span m="265480">executions</span> <span m="265977">will</span>
  <span m="266475">not</span> <span m="266972">overlap.</span></p><p><span m="267470">There</span>
  <span m="267960">are</span> <span m="268450">some</span> <span m="268940">interesting</span>
  <span m="269430">engineering</span> <span m="269920">issues</span> <span m="270410">to</span>
  <span m="270900">consider.</span></p><p><span m="271390">There's</span> <span m="271710">the</span>
  <span m="272031">question</span> <span m="272352">of</span> <span m="272672">the</span>
  <span m="272993">granularity</span> <span m="273314">of</span> <span m="273634">the</span>
  <span m="273955">lock,</span> <span m="274276">i.e.,</span> <span m="274596">what</span>
  <span m="274917">shared</span> <span m="275238">data</span> <span m="275558">is</span>
  <span m="275879">controlled</span> <span m="276200">by</span> <span m="276653">the</span>
  <span m="277106">lock?</span></p><p><span m="277560">In</span> <span m="277887">our</span>
  <span m="278215">bank</span> <span m="278542">example,</span> <span m="278870">should</span>
  <span m="279197">there</span> <span m="279525">be</span> <span m="279852">one</span>
  <span m="280180">lock</span> <span m="280507">controlling</span> <span m="280835">access</span>
  <span m="281162">to</span> <span m="281490">the</span> <span m="281817">balance</span>
  <span m="282145">for</span> <span m="282472">all</span> <span m="282800">accounts?</span></p><p><span
  m="283890">That</span> <span m="284204">would</span> <span m="284518">mean</span>
  <span m="284833">that</span> <span m="285147">no</span> <span m="285461">one</span>
  <span m="285776">could</span> <span m="286090">access</span> <span m="286405">any</span>
  <span m="286719">balance</span> <span m="287033">while</span> <span m="287348">a</span>
  <span m="287662">transaction</span> <span m="287976">was</span> <span m="288291">in</span>
  <span m="288605">progress.</span></p><p><span m="288920">That</span> <span m="289221">would</span>
  <span m="289522">mean</span> <span m="289824">that</span> <span m="290125">transactions</span>
  <span m="290427">accessing</span> <span m="290728">different</span> <span m="291030">accounts</span>
  <span m="291331">would</span> <span m="291632">have</span> <span m="291934">to</span>
  <span m="292235">run</span> <span m="292537">one</span> <span m="292838">after</span>
  <span m="293140">the</span> <span m="293632">other</span> <span m="294125">even</span>
  <span m="294617">though</span> <span m="295110">they're</span> <span m="295602">accessing</span>
  <span m="296095">different</span> <span m="296587">data.</span></p><p><span m="297080">So</span>
  <span m="297463">one</span> <span m="297846">lock</span> <span m="298229">for</span>
  <span m="298612">all</span> <span m="298995">the</span> <span m="299378">balances</span>
  <span m="299761">would</span> <span m="300144">introduce</span> <span m="300527">unnecessary</span>
  <span m="300910">precedence</span> <span m="301293">constraints,</span> <span m="301676">greatly</span>
  <span m="302060">slowing</span> <span m="302594">the</span> <span m="303128">rate</span>
  <span m="303663">at</span> <span m="304197">which</span> <span m="304732">transactions</span>
  <span m="305266">could</span> <span m="305801">be</span> <span m="306335">processed.</span></p><p><span
  m="306870">Since</span> <span m="307218">the</span> <span m="307566">guarantee</span>
  <span m="307915">we</span> <span m="308263">need</span> <span m="308612">is</span>
  <span m="308960">that</span> <span m="309309">we</span> <span m="309657">shouldn't</span>
  <span m="310006">permit</span> <span m="310354">multiple</span> <span m="310703">simultaneous</span>
  <span m="311051">transactions</span> <span m="311400">on</span> <span m="311663">the</span>
  <span m="311926">same</span> <span m="312189">account,</span> <span m="312452">it</span>
  <span m="312715">would</span> <span m="312978">make</span> <span m="313241">more</span>
  <span m="313504">sense</span> <span m="313767">to</span> <span m="314030">have</span>
  <span m="314293">a</span> <span m="314556">separate</span> <span m="314820">lock</span>
  <span m="315146">for</span> <span m="315472">each</span> <span m="315798">account,</span>
  <span m="316124">and</span> <span m="316450">change</span> <span m="316776">the</span>
  <span m="317102">Debit</span> <span m="317428">code</span> <span m="317754">to</span>
  <span m="318080">acquire</span> <span m="318406">the</span> <span m="318732">account's</span>
  <span m="319058">lock</span> <span m="319384">before</span> <span m="319710">proceeding.</span></p><p><span
  m="321790">That</span> <span m="322215">will</span> <span m="322640">only</span>
  <span m="323065">delay</span> <span m="323490">transactions</span> <span m="323915">that</span>
  <span m="324340">truly</span> <span m="324765">overlap,</span> <span m="325190">an</span>
  <span m="325615">important</span> <span m="326040">efficiency</span> <span m="326465">consideration</span>
  <span m="326890">for</span> <span m="327349">a</span> <span m="327808">large</span>
  <span m="328267">system</span> <span m="328726">processing</span> <span m="329185">many</span>
  <span m="329645">thousands</span> <span m="330104">of</span> <span m="330563">mostly</span>
  <span m="331022">non-overlapping</span> <span m="331481">transactions</span> <span
  m="331940">each</span> <span m="332400">second.</span></p><p><span m="333400">Of</span>
  <span m="333860">course,</span> <span m="334321">having</span> <span m="334782">per-account</span>
  <span m="335243">locks</span> <span m="335704">would</span> <span m="336165">mean</span>
  <span m="336626">a</span> <span m="337087">lot</span> <span m="337548">of</span>
  <span m="338009">locks!</span></p><p><span m="338470">If</span> <span m="338753">that's</span>
  <span m="339036">a</span> <span m="339319">concern,</span> <span m="339602">we</span>
  <span m="339885">can</span> <span m="340168">adopt</span> <span m="340451">a</span>
  <span m="340735">compromise</span> <span m="341018">strategy</span> <span m="341301">of</span>
  <span m="341584">having</span> <span m="341867">locks</span> <span m="342150">that</span>
  <span m="342433">protect</span> <span m="342716">groups</span> <span m="343000">of</span>
  <span m="343429">accounts,</span> <span m="343858">e.g.,</span> <span m="344287">accounts</span>
  <span m="344716">with</span> <span m="345146">same</span> <span m="345575">last</span>
  <span m="346004">three</span> <span m="346433">digits</span> <span m="346863">in</span>
  <span m="347292">the</span> <span m="347721">account</span> <span m="348150">number.</span></p><p><span
  m="348580">That</span> <span m="348889">would</span> <span m="349198">mean</span>
  <span m="349508">we'd</span> <span m="349817">only</span> <span m="350126">need</span>
  <span m="350436">1000</span> <span m="350745">locks,</span> <span m="351054">which</span>
  <span m="351364">would</span> <span m="351673">allow</span> <span m="351982">up</span>
  <span m="352292">to</span> <span m="352601">1000</span> <span m="352910">transactions</span>
  <span m="353220">to</span> <span m="354136">happen</span> <span m="355053">simultaneously.</span></p><p><span
  m="355970">The</span> <span m="356228">notion</span> <span m="356487">of</span>
  <span m="356746">transactions</span> <span m="357005">on</span> <span m="357263">shared</span>
  <span m="357522">data</span> <span m="357781">is</span> <span m="358040">so</span>
  <span m="358298">useful</span> <span m="358557">that</span> <span m="358816">we</span>
  <span m="359075">often</span> <span m="359333">use</span> <span m="359592">a</span>
  <span m="359851">separate</span> <span m="360110">system</span> <span m="360551">called</span>
  <span m="360992">a</span> <span m="361433">database</span> <span m="361874">that</span>
  <span m="362315">provides</span> <span m="362756">the</span> <span m="363197">desired</span>
  <span m="363638">functionality.</span></p><p><span m="364080">Database</span> <span
  m="364543">systems</span> <span m="365006">are</span> <span m="365470">engineered</span>
  <span m="365933">to</span> <span m="366396">provide</span> <span m="366860">low-latency</span>
  <span m="367323">access</span> <span m="367786">to</span> <span m="368250">shared</span>
  <span m="368713">data,</span> <span m="369176">providing</span> <span m="369640">the</span>
  <span m="370517">appropriate</span> <span m="371395">transactional</span> <span
  m="372272">semantics.</span></p><p><span m="373150">The</span> <span m="373536">design</span>
  <span m="373922">and</span> <span m="374309">implementation</span> <span m="374695">of</span>
  <span m="375081">databases</span> <span m="375468">and</span> <span m="375854">transactions</span>
  <span m="376240">is</span> <span m="376627">pretty</span> <span m="377013">interesting.</span></p><p><span
  m="377400">To</span> <span m="377850">follow</span> <span m="378301">up,</span>
  <span m="378752">I</span> <span m="379203">recommend</span> <span m="379654">reading</span>
  <span m="380105">about</span> <span m="380556">databases</span> <span m="381007">on</span>
  <span m="381458">the</span> <span m="381909">web.</span></p><p><span m="382360">Returning</span>
  <span m="382746">to</span> <span m="383132">our</span> <span m="383518">producer/consumer</span>
  <span m="383904">example,</span> <span m="384290">we</span> <span m="384676">see</span>
  <span m="385063">that</span> <span m="385449">if</span> <span m="385835">multiple</span>
  <span m="386221">producers</span> <span m="386607">are</span> <span m="386993">trying</span>
  <span m="387380">to</span> <span m="387661">insert</span> <span m="387942">characters</span>
  <span m="388223">into</span> <span m="388504">the</span> <span m="388785">buffer</span>
  <span m="389066">at</span> <span m="389347">the</span> <span m="389628">same</span>
  <span m="389909">time,</span> <span m="390190">it's</span> <span m="390526">possible</span>
  <span m="390862">that</span> <span m="391198">their</span> <span m="391535">execution</span>
  <span m="391871">may</span> <span m="392207">overlap</span> <span m="392543">in</span>
  <span m="392880">a</span> <span m="393216">way</span> <span m="393552">that</span>
  <span m="393888">causes</span> <span m="394225">characters</span> <span m="394561">to</span>
  <span m="394897">be</span> <span m="395233">overwritten</span> <span m="395570">and/or</span>
  <span m="396272">the</span> <span m="396975">index</span> <span m="397678">to</span>
  <span m="398381">be</span> <span m="399084">improperly</span> <span m="399787">incremented.</span></p><p><span
  m="400490">We</span> <span m="400815">just</span> <span m="401140">saw</span> <span
  m="401465">this</span> <span m="401790">bug</span> <span m="402115">in</span> <span
  m="402440">the</span> <span m="402765">bank</span> <span m="403090">example:</span>
  <span m="403415">the</span> <span m="403740">producer</span> <span m="404065">code</span>
  <span m="404390">contains</span> <span m="404715">a</span> <span m="405040">critical</span>
  <span m="405365">section</span> <span m="405691">of</span> <span m="405984">code</span>
  <span m="406278">that</span> <span m="406572">accesses</span> <span m="406865">the</span>
  <span m="407159">FIFO</span> <span m="407453">buffer</span> <span m="407746">and</span>
  <span m="408040">we</span> <span m="408334">need</span> <span m="408627">to</span>
  <span m="408921">ensure</span> <span m="409215">that</span> <span m="409508">the</span>
  <span m="409802">critical</span> <span m="410096">section</span> <span m="410390">is</span>
  <span m="411260">executed</span> <span m="412130">atomically.</span></p><p><span
  m="413000">Here</span> <span m="413362">we've</span> <span m="413725">added</span>
  <span m="414088">a</span> <span m="414451">third</span> <span m="414814">semaphore,</span>
  <span m="415177">called</span> <span m="415540">LOCK,</span> <span m="415902">to</span>
  <span m="416265">implement</span> <span m="416628">the</span> <span m="416991">necessary</span>
  <span m="417354">mutual</span> <span m="417717">exclusion</span> <span m="418080">constraint</span>
  <span m="418531">for</span> <span m="418982">the</span> <span m="419434">critical</span>
  <span m="419885">section</span> <span m="420337">of</span> <span m="420788">code</span>
  <span m="421240">that</span> <span m="421691">inserts</span> <span m="422142">characters</span>
  <span m="422594">into</span> <span m="423045">the</span> <span m="423497">FIFO</span>
  <span m="423948">buffer.</span></p><p><span m="424400">With</span> <span m="424770">this</span>
  <span m="425140">modification,</span> <span m="425510">the</span> <span m="425880">system</span>
  <span m="426250">will</span> <span m="426620">now</span> <span m="426990">work</span>
  <span m="427360">correctly</span> <span m="427730">when</span> <span m="428100">there</span>
  <span m="428470">are</span> <span m="428840">multiple</span> <span m="429210">producer</span>
  <span m="429580">processes.</span></p><p><span m="430580">There's</span> <span m="430855">a</span>
  <span m="431131">similar</span> <span m="431406">issue</span> <span m="431682">with</span>
  <span m="431958">multiple</span> <span m="432233">consumers,</span> <span m="432509">so</span>
  <span m="432785">we've</span> <span m="433060">used</span> <span m="433336">the</span>
  <span m="433611">same</span> <span m="433887">LOCK</span> <span m="434163">to</span>
  <span m="434438">protect</span> <span m="434714">the</span> <span m="434990">critical</span>
  <span m="435419">section</span> <span m="435848">for</span> <span m="436277">reading</span>
  <span m="436706">from</span> <span m="437135">the</span> <span m="437564">buffer</span>
  <span m="437993">in</span> <span m="438422">the</span> <span m="438851">RCV</span>
  <span m="439280">code.</span></p><p><span m="439710">Using</span> <span m="440102">the</span>
  <span m="440495">same</span> <span m="440888">LOCK</span> <span m="441281">for</span>
  <span m="441674">producers</span> <span m="442067">and</span> <span m="442460">consumers</span>
  <span m="442852">will</span> <span m="443245">work,</span> <span m="443638">but</span>
  <span m="444031">does</span> <span m="444424">introduce</span> <span m="444817">unnecessary</span>
  <span m="445210">precedence</span> <span m="445754">constraints</span> <span m="446298">since</span>
  <span m="446843">producers</span> <span m="447387">and</span> <span m="447932">consumers</span>
  <span m="448476">use</span> <span m="449021">different</span> <span m="449565">indices,</span>
  <span m="450110">i.e.,</span> <span m="450672">IN</span> <span m="451235">for</span>
  <span m="451797">producers</span> <span m="452360">and</span> <span m="452922">OUT</span>
  <span m="453485">for</span> <span m="454047">consumers.</span></p><p><span m="454610">To</span>
  <span m="454993">solve</span> <span m="455377">this</span> <span m="455761">problem</span>
  <span m="456145">we</span> <span m="456528">could</span> <span m="456912">use</span>
  <span m="457296">two</span> <span m="457680">locks:</span> <span m="458063">one</span>
  <span m="458447">for</span> <span m="458831">producers</span> <span m="459215">and</span>
  <span m="459598">one</span> <span m="459982">for</span> <span m="460366">consumers.</span></p><p><span
  m="460750">Semaphores</span> <span m="461038">are</span> <span m="461327">a</span>
  <span m="461616">pretty</span> <span m="461904">handy</span> <span m="462193">swiss</span>
  <span m="462482">army</span> <span m="462770">knife</span> <span m="463059">when</span>
  <span m="463348">it</span> <span m="463636">comes</span> <span m="463925">to</span>
  <span m="464214">dealing</span> <span m="464502">with</span> <span m="464791">synchronization</span>
  <span m="465080">issues.</span></p><p><span m="466400">When</span> <span m="466763">WAIT</span>
  <span m="467127">and</span> <span m="467490">SIGNAL</span> <span m="467854">appear</span>
  <span m="468217">in</span> <span m="468581">different</span> <span m="468945">processes,</span>
  <span m="469308">the</span> <span m="469672">semaphore</span> <span m="470035">ensures</span>
  <span m="470399">the</span> <span m="470762">correct</span> <span m="471126">execution</span>
  <span m="471490">timing</span> <span m="472333">between</span> <span m="473176">processes.</span></p><p><span
  m="474020">In</span> <span m="474323">our</span> <span m="474626">example,</span>
  <span m="474929">we</span> <span m="475232">used</span> <span m="475535">two</span>
  <span m="475838">semaphores</span> <span m="476141">to</span> <span m="476445">ensure</span>
  <span m="476748">that</span> <span m="477051">consumers</span> <span m="477354">can't</span>
  <span m="477657">read</span> <span m="477960">from</span> <span m="478263">an</span>
  <span m="478566">empty</span> <span m="478870">buffer</span> <span m="479407">and</span>
  <span m="479944">that</span> <span m="480481">producers</span> <span m="481018">can't</span>
  <span m="481555">write</span> <span m="482092">into</span> <span m="482629">a</span>
  <span m="483166">full</span> <span m="483703">buffer.</span></p><p><span m="484240">We</span>
  <span m="484595">also</span> <span m="484951">used</span> <span m="485306">semaphores</span>
  <span m="485662">to</span> <span m="486018">ensure</span> <span m="486373">that</span>
  <span m="486729">execution</span> <span m="487085">of</span> <span m="487440">critical</span>
  <span m="487796">sections</span> <span m="488151">--</span> <span m="488507">in</span>
  <span m="488863">our</span> <span m="489218">example,</span> <span m="489574">updates</span>
  <span m="489930">of</span> <span m="490225">the</span> <span m="490521">indices</span>
  <span m="490817">IN</span> <span m="491113">and</span> <span m="491409">OUT</span>
  <span m="491705">--</span> <span m="492000">were</span> <span m="492296">guaranteed</span>
  <span m="492592">to</span> <span m="492888">be</span> <span m="493184">atomic.</span></p><p><span
  m="493480">In</span> <span m="493806">other</span> <span m="494133">words,</span>
  <span m="494460">that</span> <span m="494787">the</span> <span m="495114">sequence</span>
  <span m="495441">of</span> <span m="495768">reads</span> <span m="496095">and</span>
  <span m="496421">writes</span> <span m="496748">needed</span> <span m="497075">to</span>
  <span m="497402">increment</span> <span m="497729">a</span> <span m="498056">shared</span>
  <span m="498383">index</span> <span m="498710">would</span> <span m="499042">not</span>
  <span m="499375">be</span> <span m="499708">interrupted</span> <span m="500040">by</span>
  <span m="500373">another</span> <span m="500706">process</span> <span m="501038">between</span>
  <span m="501371">the</span> <span m="501704">initial</span> <span m="502036">read</span>
  <span m="502369">of</span> <span m="502702">the</span> <span m="503034">index</span>
  <span m="503367">and</span> <span m="503700">the</span> <span m="503963">final</span>
  <span m="504226">write.</span></p>
type: course
uid: 4e953b6237a0d849df8554e08e30848b

---
None