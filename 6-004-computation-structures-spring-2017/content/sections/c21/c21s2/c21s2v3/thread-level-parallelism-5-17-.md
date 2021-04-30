---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: y5gPFB6uiYA
  parent_uid: 82131814a7e4ac5e0e0c8982fc05bf92
  title: Video-YouTube-Stream
  type: Video
  uid: 00c9e4686bfda3acd3d6bc73037a61b3
- id: 3Play-3Play YouTube id-Stream
  media_location: y5gPFB6uiYA
  parent_uid: 82131814a7e4ac5e0e0c8982fc05bf92
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 35b17d81507055127a545f62de4e2b24
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/y5gPFB6uiYA/default.jpg
  parent_uid: 82131814a7e4ac5e0e0c8982fc05bf92
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 96b68c09dd66bce63a8b33ae48c7cdf0
- id: y5gPFB6uiYA.srt
  parent_uid: 82131814a7e4ac5e0e0c8982fc05bf92
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/c21s2v3/thread-level-parallelism-5-17-/y5gPFB6uiYA.srt
  title: 3play caption file
  type: null
  uid: 672d0758b6f205469ce5aaa53a8c378e
- id: y5gPFB6uiYA.pdf
  parent_uid: 82131814a7e4ac5e0e0c8982fc05bf92
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/c21s2v3/thread-level-parallelism-5-17-/y5gPFB6uiYA.pdf
  title: 3play pdf file
  type: null
  uid: ee34514d580ef8b5474b5212d14e4008
- id: Caption-3Play YouTube id-SRT
  parent_uid: 82131814a7e4ac5e0e0c8982fc05bf92
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 9d7a492a8e282ba76e5ba0d100e444cf
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 82131814a7e4ac5e0e0c8982fc05bf92
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 89491ecf52a17d105681e7812901bb8f
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_21-02-03_300k.mp4
  parent_uid: 82131814a7e4ac5e0e0c8982fc05bf92
  title: Video-Internet Archive-MP4
  type: Video
  uid: 3291e4c0aaaa9efdc48e94a983de38df
inline_embed_id: 34115646threadlevelparallelism51718849135
layout: video
order_index: null
parent_uid: 3ed7c3b5469279b4a812c092a082a255
related_resources_text: ''
short_url: thread-level-parallelism-5-17-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/c21s2v3/thread-level-parallelism-5-17-
template_type: Embed
title: Thread-level Parallelism
transcript: <p><span m="880">In</span> <span m="1326">discussing</span> <span m="1773">out-of-order</span>
  <span m="2220">superscalar</span> <span m="2667">pipelined</span> <span m="3114">CPUs</span>
  <span m="3561">we</span> <span m="4008">commented</span> <span m="4455">that</span>
  <span m="4902">the</span> <span m="5349">costs</span> <span m="5796">grow</span>
  <span m="6243">very</span> <span m="6690">quickly</span> <span m="7088">relative</span>
  <span m="7486">to</span> <span m="7885">the</span> <span m="8283">performance</span>
  <span m="8681">gains,</span> <span m="9080">leading</span> <span m="9478">to</span>
  <span m="9876">the</span> <span m="10275">cost-performance</span> <span m="10673">curve</span>
  <span m="11071">shown</span> <span m="11470">here.</span></p><p><span m="12820">If</span>
  <span m="13088">we</span> <span m="13356">move</span> <span m="13624">down</span>
  <span m="13892">the</span> <span m="14160">curve,</span> <span m="14428">we</span>
  <span m="14696">can</span> <span m="14964">arrive</span> <span m="15232">at</span>
  <span m="15500">more</span> <span m="15768">efficient</span> <span m="16036">architectures</span>
  <span m="16304">that</span> <span m="16572">give,</span> <span m="16840">say,</span>
  <span m="17109">1/2</span> <span m="17451">the</span> <span m="17793">performance</span>
  <span m="18135">at</span> <span m="18477">a</span> <span m="18820">1/4</span> <span
  m="19162">of</span> <span m="19504">the</span> <span m="19846">cost.</span></p><p><span
  m="20189">When</span> <span m="20557">our</span> <span m="20926">applications</span>
  <span m="21294">involve</span> <span m="21663">independent</span> <span m="22031">computations</span>
  <span m="22400">that</span> <span m="22768">can</span> <span m="23137">be</span>
  <span m="23505">performed</span> <span m="23874">in</span> <span m="24242">a</span>
  <span m="24611">parallel,</span> <span m="24980">it</span> <span m="25236">may</span>
  <span m="25493">be</span> <span m="25750">that</span> <span m="26007">we</span>
  <span m="26263">would</span> <span m="26520">be</span> <span m="26777">able</span>
  <span m="27034">to</span> <span m="27291">use</span> <span m="27547">two</span>
  <span m="27804">cores</span> <span m="28061">to</span> <span m="28318">provide</span>
  <span m="28575">the</span> <span m="28831">same</span> <span m="29088">performance</span>
  <span m="29345">as</span> <span m="29602">the</span> <span m="29859">original</span>
  <span m="30363">expensive</span> <span m="30868">core,</span> <span m="31372">but</span>
  <span m="31877">a</span> <span m="32381">fraction</span> <span m="32886">of</span>
  <span m="33390">the</span> <span m="33895">cost.</span></p><p><span m="34400">If</span>
  <span m="34746">the</span> <span m="35092">available</span> <span m="35438">parallelism</span>
  <span m="35784">allows</span> <span m="36130">us</span> <span m="36476">to</span>
  <span m="36822">use</span> <span m="37168">additional</span> <span m="37514">cores,</span>
  <span m="37860">we'll</span> <span m="38206">see</span> <span m="38552">a</span>
  <span m="38898">linear</span> <span m="39244">relationship</span> <span m="39590">between</span>
  <span m="40281">increased</span> <span m="40973">performance</span> <span m="41665">vs.</span>
  <span m="42356">increased</span> <span m="43048">cost.</span></p><p><span m="43740">The</span>
  <span m="44024">key,</span> <span m="44308">of</span> <span m="44593">course,</span>
  <span m="44877">is</span> <span m="45161">that</span> <span m="45446">desired</span>
  <span m="45730">computations</span> <span m="46015">can</span> <span m="46299">be</span>
  <span m="46583">divided</span> <span m="46868">into</span> <span m="47152">multiple</span>
  <span m="47436">tasks</span> <span m="47721">that</span> <span m="48005">can</span>
  <span m="48290">run</span> <span m="48688">independently,</span> <span m="49086">with</span>
  <span m="49485">little</span> <span m="49883">or</span> <span m="50281">no</span>
  <span m="50680">need</span> <span m="51078">for</span> <span m="51476">communication</span>
  <span m="51875">or</span> <span m="52273">coordination</span> <span m="52671">between</span>
  <span m="53070">the</span> <span m="54155">tasks.</span></p><p><span m="55240">What</span>
  <span m="55618">is</span> <span m="55996">the</span> <span m="56375">optimal</span>
  <span m="56753">tradeoff</span> <span m="57132">between</span> <span m="57510">core</span>
  <span m="57889">cost</span> <span m="58267">and</span> <span m="58646">the</span>
  <span m="59024">number</span> <span m="59403">of</span> <span m="59781">cores?</span></p><p><span
  m="60160">If</span> <span m="60620">our</span> <span m="61080">computation</span>
  <span m="61540">is</span> <span m="62000">arbitrarily</span> <span m="62460">divisible</span>
  <span m="62920">without</span> <span m="63380">incurring</span> <span m="63840">additional</span>
  <span m="64300">overhead,</span> <span m="64760">then</span> <span m="65042">we</span>
  <span m="65325">would</span> <span m="65608">continue</span> <span m="65890">to</span>
  <span m="66173">move</span> <span m="66456">down</span> <span m="66738">the</span>
  <span m="67021">curve</span> <span m="67304">until</span> <span m="67586">we</span>
  <span m="67869">found</span> <span m="68152">the</span> <span m="68434">cost-performance</span>
  <span m="68717">point</span> <span m="69000">that</span> <span m="69338">gave</span>
  <span m="69676">us</span> <span m="70014">the</span> <span m="70352">desired</span>
  <span m="70690">performance</span> <span m="71028">at</span> <span m="71366">the</span>
  <span m="71704">least</span> <span m="72042">cost.</span></p><p><span m="72380">In</span>
  <span m="72832">reality,</span> <span m="73284">dividing</span> <span m="73736">the</span>
  <span m="74189">computation</span> <span m="74641">across</span> <span m="75093">many</span>
  <span m="75546">cores</span> <span m="75998">does</span> <span m="76450">involve</span>
  <span m="76903">some</span> <span m="77355">overhead,</span> <span m="77807">e.g.,</span>
  <span m="78260">distributing</span> <span m="78634">the</span> <span m="79008">data</span>
  <span m="79382">and</span> <span m="79756">code,</span> <span m="80131">then</span>
  <span m="80505">collecting</span> <span m="80879">and</span> <span m="81253">aggregating</span>
  <span m="81627">the</span> <span m="82002">results,</span> <span m="82376">so</span>
  <span m="82750">the</span> <span m="83124">optimal</span> <span m="83499">tradeoff</span>
  <span m="83945">is</span> <span m="84391">harder</span> <span m="84837">to</span>
  <span m="85283">find.</span></p><p><span m="85729">Still,</span> <span m="86157">the</span>
  <span m="86586">idea</span> <span m="87014">of</span> <span m="87443">using</span>
  <span m="87872">a</span> <span m="88300">larger</span> <span m="88729">number</span>
  <span m="89157">of</span> <span m="89586">smaller,</span> <span m="90015">more</span>
  <span m="90443">efficient</span> <span m="90872">cores</span> <span m="91300">seems</span>
  <span m="91729">attractive.</span></p><p><span m="92158">Many</span> <span m="92487">applications</span>
  <span m="92816">have</span> <span m="93146">some</span> <span m="93475">computations</span>
  <span m="93805">that</span> <span m="94134">can</span> <span m="94464">be</span>
  <span m="94793">performed</span> <span m="95122">in</span> <span m="95452">parallel,</span>
  <span m="95781">but</span> <span m="96111">also</span> <span m="96440">have</span>
  <span m="96770">computations</span> <span m="97373">that</span> <span m="97976">won't</span>
  <span m="98580">benefit</span> <span m="99183">from</span> <span m="99786">parallelism.</span></p><p><span
  m="100390">To</span> <span m="100708">understand</span> <span m="101026">the</span>
  <span m="101345">speedup</span> <span m="101663">we</span> <span m="101982">might</span>
  <span m="102300">expect</span> <span m="102619">from</span> <span m="102937">exploiting</span>
  <span m="103256">parallelism,</span> <span m="103574">it's</span> <span m="103893">useful</span>
  <span m="104211">to</span> <span m="104530">perform</span> <span m="104984">the</span>
  <span m="105439">calculation</span> <span m="105894">proposed</span> <span m="106349">by</span>
  <span m="106804">computer</span> <span m="107259">scientist</span> <span m="107714">Gene</span>
  <span m="108169">Amdahl</span> <span m="108624">in</span> <span m="109079">1967,</span>
  <span m="109534">now</span> <span m="109989">known</span> <span m="110444">as</span>
  <span m="110899">Amdahl's</span> <span m="112009">Law.</span></p><p><span m="113119">Suppose</span>
  <span m="113388">we're</span> <span m="113657">considering</span> <span m="113927">an</span>
  <span m="114196">enhancement</span> <span m="114465">that</span> <span m="114735">speeds</span>
  <span m="115004">up</span> <span m="115274">some</span> <span m="115543">fraction</span>
  <span m="115812">F</span> <span m="116082">of</span> <span m="116351">the</span>
  <span m="116620">task</span> <span m="116890">at</span> <span m="117159">hand</span>
  <span m="117429">by</span> <span m="117748">a</span> <span m="118067">factor</span>
  <span m="118386">of</span> <span m="118706">S.</span> <span m="119025">As</span>
  <span m="119344">shown</span> <span m="119664">in</span> <span m="119983">the</span>
  <span m="120302">figure,</span> <span m="120621">the</span> <span m="120941">gray</span>
  <span m="121260">portion</span> <span m="121579">of</span> <span m="121899">the</span>
  <span m="122314">task</span> <span m="122729">now</span> <span m="123145">takes</span>
  <span m="123560">F/S</span> <span m="123975">of</span> <span m="124391">the</span>
  <span m="124806">time</span> <span m="125222">that</span> <span m="125637">it</span>
  <span m="126052">used</span> <span m="126468">to</span> <span m="126883">require.</span></p><p><span
  m="127299">Some</span> <span m="127749">simple</span> <span m="128200">arithmetic</span>
  <span m="128651">lets</span> <span m="129101">us</span> <span m="129552">calculate</span>
  <span m="130003">the</span> <span m="130454">overall</span> <span m="130904">speedup</span>
  <span m="131355">we</span> <span m="131806">get</span> <span m="132257">from</span>
  <span m="132707">using</span> <span m="133158">the</span> <span m="133609">enhancement.</span></p><p><span
  m="134060">One</span> <span m="134345">conclusion</span> <span m="134631">we</span>
  <span m="134917">can</span> <span m="135203">draw</span> <span m="135489">is</span>
  <span m="135775">that</span> <span m="136061">we'll</span> <span m="136347">benefit</span>
  <span m="136632">the</span> <span m="136918">most</span> <span m="137204">from</span>
  <span m="137490">enhancements</span> <span m="137776">that</span> <span m="138062">affect</span>
  <span m="138348">a</span> <span m="138634">large</span> <span m="138920">portion</span>
  <span m="139363">of</span> <span m="139807">the</span> <span m="140251">required</span>
  <span m="140695">computations,</span> <span m="141139">i.e.,</span> <span m="141583">we</span>
  <span m="142027">want</span> <span m="142471">to</span> <span m="142915">make</span>
  <span m="143359">F</span> <span m="143803">as</span> <span m="144247">large</span>
  <span m="144691">a</span> <span m="145135">possible.</span></p><p><span m="145579">What's</span>
  <span m="145810">the</span> <span m="146042">best</span> <span m="146273">speedup</span>
  <span m="146505">we</span> <span m="146737">can</span> <span m="146968">hope</span>
  <span m="147200">for</span> <span m="147432">if</span> <span m="147663">we</span>
  <span m="147895">have</span> <span m="148126">many</span> <span m="148358">cores</span>
  <span m="148590">that</span> <span m="148821">can</span> <span m="149053">be</span>
  <span m="149285">used</span> <span m="149516">to</span> <span m="149748">speed</span>
  <span m="149980">up</span> <span m="150368">the</span> <span m="150757">parallel</span>
  <span m="151145">part</span> <span m="151534">of</span> <span m="151922">the</span>
  <span m="152311">task?</span></p><p><span m="152700">Here's</span> <span m="153033">the</span>
  <span m="153366">speedup</span> <span m="153700">formula</span> <span m="154033">based</span>
  <span m="154366">on</span> <span m="154700">F</span> <span m="155033">and</span>
  <span m="155366">S,</span> <span m="155700">where</span> <span m="156033">in</span>
  <span m="156366">this</span> <span m="156700">case</span> <span m="157033">F</span>
  <span m="157366">is</span> <span m="157700">the</span> <span m="158033">parallel</span>
  <span m="158366">fraction</span> <span m="158700">of</span> <span m="159326">the</span>
  <span m="159952">task.</span></p><p><span m="160579">If</span> <span m="160816">we</span>
  <span m="161053">assume</span> <span m="161290">that</span> <span m="161527">the</span>
  <span m="161764">parallel</span> <span m="162001">fraction</span> <span m="162238">of</span>
  <span m="162475">the</span> <span m="162713">task</span> <span m="162950">can</span>
  <span m="163187">be</span> <span m="163424">speed</span> <span m="163661">up</span>
  <span m="163898">arbitrarily</span> <span m="164135">by</span> <span m="164372">using</span>
  <span m="164610">more</span> <span m="164917">and</span> <span m="165224">more</span>
  <span m="165532">cores,</span> <span m="165839">we</span> <span m="166146">see</span>
  <span m="166454">that</span> <span m="166761">the</span> <span m="167068">best</span>
  <span m="167376">possible</span> <span m="167683">overall</span> <span m="167990">speed</span>
  <span m="168298">up</span> <span m="168605">is</span> <span m="168912">1/(1-F).</span></p><p><span
  m="169220">For</span> <span m="169653">example,</span> <span m="170086">you</span>
  <span m="170520">write</span> <span m="170953">a</span> <span m="171386">program</span>
  <span m="171820">that</span> <span m="172253">can</span> <span m="172686">do</span>
  <span m="173120">90%</span> <span m="173553">of</span> <span m="173986">its</span>
  <span m="174420">work</span> <span m="174853">in</span> <span m="175286">parallel,</span>
  <span m="175720">but</span> <span m="176153">the</span> <span m="176586">other</span>
  <span m="177020">10%</span> <span m="177662">must</span> <span m="178304">be</span>
  <span m="178946">done</span> <span m="179588">sequentially.</span></p><p><span m="180230">The</span>
  <span m="180512">best</span> <span m="180795">overall</span> <span m="181078">speedup</span>
  <span m="181361">that</span> <span m="181643">can</span> <span m="181926">be</span>
  <span m="182209">achieved</span> <span m="182492">is</span> <span m="182775">a</span>
  <span m="183057">factor</span> <span m="183340">of</span> <span m="183623">10,</span>
  <span m="183906">no</span> <span m="184188">matter</span> <span m="184471">how</span>
  <span m="184754">many</span> <span m="185037">cores</span> <span m="185320">you</span>
  <span m="185906">have</span> <span m="186492">at</span> <span m="187078">your</span>
  <span m="187664">disposal.</span></p><p><span m="188250">Turning</span> <span m="188498">the</span>
  <span m="188747">question</span> <span m="188996">around,</span> <span m="189245">suppose</span>
  <span m="189493">you</span> <span m="189742">have</span> <span m="189991">a</span>
  <span m="190240">1000-core</span> <span m="190488">machine</span> <span m="190737">which</span>
  <span m="190986">you</span> <span m="191235">hope</span> <span m="191483">to</span>
  <span m="191732">be</span> <span m="191981">able</span> <span m="192230">to</span>
  <span m="192624">use</span> <span m="193018">to</span> <span m="193412">achieve</span>
  <span m="193806">a</span> <span m="194200">speedup</span> <span m="194595">of</span>
  <span m="194989">500</span> <span m="195383">on</span> <span m="195777">your</span>
  <span m="196171">target</span> <span m="196565">application.</span></p><p><span
  m="196960">You</span> <span m="197335">would</span> <span m="197711">need</span>
  <span m="198086">to</span> <span m="198462">be</span> <span m="198838">able</span>
  <span m="199213">parallelize</span> <span m="199589">99.8%</span> <span m="199965">of</span>
  <span m="200340">the</span> <span m="200716">computation</span> <span m="201091">in</span>
  <span m="201467">order</span> <span m="201843">to</span> <span m="202218">reach</span>
  <span m="202594">your</span> <span m="202970">goal!</span></p><p><span m="204290">Clearly</span>
  <span m="204815">multicore</span> <span m="205340">machines</span> <span m="205866">are</span>
  <span m="206391">most</span> <span m="206916">useful</span> <span m="207442">when</span>
  <span m="207967">the</span> <span m="208492">target</span> <span m="209018">task</span>
  <span m="209543">has</span> <span m="210068">lots</span> <span m="210594">of</span>
  <span m="211119">natural</span> <span m="211644">parallelism.</span></p><p><span
  m="212170">Using</span> <span m="212575">multiple</span> <span m="212980">independent</span>
  <span m="213386">cores</span> <span m="213791">to</span> <span m="214196">execute</span>
  <span m="214602">a</span> <span m="215007">parallel</span> <span m="215413">task</span>
  <span m="215818">is</span> <span m="216223">called</span> <span m="216629">thread-level</span>
  <span m="217034">parallelism</span> <span m="217440">(TLP),</span> <span m="217966">where</span>
  <span m="218493">each</span> <span m="219020">core</span> <span m="219546">executes</span>
  <span m="220073">a</span> <span m="220600">separate</span> <span m="221126">computation</span>
  <span m="221653">&quot;thread&quot;.</span></p><p><span m="222180">The</span> <span
  m="222550">threads</span> <span m="222921">are</span> <span m="223292">independent</span>
  <span m="223663">programs,</span> <span m="224033">so</span> <span m="224404">the</span>
  <span m="224775">execution</span> <span m="225146">model</span> <span m="225516">is</span>
  <span m="225887">potentially</span> <span m="226258">more</span> <span m="226629">flexible</span>
  <span m="227000">than</span> <span m="227640">the</span> <span m="228280">lock-step</span>
  <span m="228920">execution</span> <span m="229560">provided</span> <span m="230200">by</span>
  <span m="230840">vector</span> <span m="231480">machines.</span></p><p><span m="232120">When</span>
  <span m="232365">there</span> <span m="232611">are</span> <span m="232857">a</span>
  <span m="233103">small</span> <span m="233349">number</span> <span m="233595">of</span>
  <span m="233841">threads,</span> <span m="234087">you</span> <span m="234332">often</span>
  <span m="234578">see</span> <span m="234824">the</span> <span m="235070">cores</span>
  <span m="235316">sharing</span> <span m="235562">a</span> <span m="235808">common</span>
  <span m="236054">main</span> <span m="236300">memory,</span> <span m="236663">allowing</span>
  <span m="237027">the</span> <span m="237391">threads</span> <span m="237755">to</span>
  <span m="238119">communicate</span> <span m="238483">and</span> <span m="238846">synchronize</span>
  <span m="239210">by</span> <span m="239574">sharing</span> <span m="239938">a</span>
  <span m="240302">common</span> <span m="240666">address</span> <span m="241030">space.</span></p><p><span
  m="242030">We'll</span> <span m="242430">discuss</span> <span m="242830">this</span>
  <span m="243230">further</span> <span m="243630">in</span> <span m="244030">the</span>
  <span m="244430">next</span> <span m="244830">section.</span></p><p><span m="245230">This</span>
  <span m="245683">is</span> <span m="246137">the</span> <span m="246591">approach</span>
  <span m="247045">used</span> <span m="247498">in</span> <span m="247952">current</span>
  <span m="248406">multicore</span> <span m="248860">processors,</span> <span m="249313">which</span>
  <span m="249767">have</span> <span m="250221">between</span> <span m="250675">2</span>
  <span m="251128">and</span> <span m="251582">12</span> <span m="252036">cores.</span></p><p><span
  m="252490">Shared</span> <span m="252816">memory</span> <span m="253142">becomes</span>
  <span m="253468">a</span> <span m="253794">real</span> <span m="254120">bottleneck</span>
  <span m="254446">when</span> <span m="254772">there</span> <span m="255098">10's</span>
  <span m="255424">or</span> <span m="255750">100's</span> <span m="256076">of</span>
  <span m="256402">cores,</span> <span m="256728">since</span> <span m="257054">collectively</span>
  <span m="257380">they</span> <span m="257824">quickly</span> <span m="258268">overwhelm</span>
  <span m="258712">the</span> <span m="259157">available</span> <span m="259601">memory</span>
  <span m="260045">bandwidth.</span></p><p><span m="260490">In</span> <span m="260970">these</span>
  <span m="261450">architectures,</span> <span m="261930">threads</span> <span m="262410">communicate</span>
  <span m="262890">using</span> <span m="263370">a</span> <span m="263850">communication</span>
  <span m="264330">network</span> <span m="264810">to</span> <span m="265290">pass</span>
  <span m="265770">messages</span> <span m="266250">back</span> <span m="266903">and</span>
  <span m="267556">forth.</span></p><p><span m="268210">We</span> <span m="268683">discussed</span>
  <span m="269156">possible</span> <span m="269630">network</span> <span m="270103">topologies</span>
  <span m="270576">in</span> <span m="271050">an</span> <span m="271523">earlier</span>
  <span m="271996">lecture.</span></p><p><span m="272470">A</span> <span m="272908">cost-effective</span>
  <span m="273346">on-chip</span> <span m="273785">approach</span> <span m="274223">is</span>
  <span m="274662">to</span> <span m="275100">use</span> <span m="275539">a</span>
  <span m="275977">nearest-neighbor</span> <span m="276416">mesh</span> <span m="276854">network,</span>
  <span m="277293">which</span> <span m="277731">supports</span> <span m="278170">many</span>
  <span m="278794">parallel</span> <span m="279418">point-to-point</span> <span m="280043">communications,</span>
  <span m="280667">while</span> <span m="281292">still</span> <span m="281916">allowing</span>
  <span m="282541">multi-hop</span> <span m="283165">communication</span> <span m="283790">between</span>
  <span m="284560">any</span> <span m="285330">two</span> <span m="286100">cores.</span></p><p><span
  m="286870">Message</span> <span m="287300">passing</span> <span m="287730">is</span>
  <span m="288160">also</span> <span m="288590">used</span> <span m="289020">in</span>
  <span m="289450">computing</span> <span m="289880">clusters,</span> <span m="290310">where</span>
  <span m="290740">many</span> <span m="291170">ordinary</span> <span m="291600">CPUs</span>
  <span m="292030">collaborate</span> <span m="292460">on</span> <span m="293160">large</span>
  <span m="293860">tasks.</span></p><p><span m="294560">There's</span> <span m="295063">a</span>
  <span m="295567">standardized</span> <span m="296071">message</span> <span m="296575">passing</span>
  <span m="297078">interface</span> <span m="297582">(MPI)</span> <span m="298086">and</span>
  <span m="298590">specialized,</span> <span m="299206">very</span> <span m="299822">high</span>
  <span m="300438">throughput,</span> <span m="301054">low</span> <span m="301670">latency</span>
  <span m="302286">message-passing</span> <span m="302902">communication</span> <span
  m="303518">networks</span> <span m="304134">(e.g.,</span> <span m="304750">Infiniband)</span>
  <span m="305206">that</span> <span m="305662">make</span> <span m="306118">it</span>
  <span m="306574">easy</span> <span m="307030">to</span> <span m="307486">build</span>
  <span m="307942">high-performance</span> <span m="308398">computing</span> <span
  m="308854">clusters.</span></p><p><span m="309310">In</span> <span m="309601">the</span>
  <span m="309892">next</span> <span m="310183">couple</span> <span m="310475">of</span>
  <span m="310766">sections</span> <span m="311057">we'll</span> <span m="311348">look</span>
  <span m="311640">more</span> <span m="311931">closely</span> <span m="312222">at</span>
  <span m="312513">some</span> <span m="312805">of</span> <span m="313096">the</span>
  <span m="313387">issues</span> <span m="313678">involved</span> <span m="313970">in</span>
  <span m="314506">building</span> <span m="315042">shared-memory</span> <span m="315578">multicore</span>
  <span m="316114">processors.</span></p>
type: course
uid: 82131814a7e4ac5e0e0c8982fc05bf92

---
None