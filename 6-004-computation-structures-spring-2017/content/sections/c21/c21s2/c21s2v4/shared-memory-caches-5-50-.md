---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: IbKCGrVGpco
  parent_uid: 8aef388b173b3709a0913862e2984222
  title: Video-YouTube-Stream
  type: Video
  uid: 78f396c4ec84a8b7e13260e069c2c727
- id: 3Play-3Play YouTube id-Stream
  media_location: IbKCGrVGpco
  parent_uid: 8aef388b173b3709a0913862e2984222
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 7788b162fbfe8186eb7e7d25b9110a7e
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/IbKCGrVGpco/default.jpg
  parent_uid: 8aef388b173b3709a0913862e2984222
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 5377442e7d10c17058cf998d31b2a049
- id: IbKCGrVGpco.srt
  parent_uid: 8aef388b173b3709a0913862e2984222
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/c21s2v4/shared-memory-caches-5-50-/IbKCGrVGpco.srt
  title: 3play caption file
  type: null
  uid: 2948c7e73e28146fae5e8324122aafb0
- id: IbKCGrVGpco.pdf
  parent_uid: 8aef388b173b3709a0913862e2984222
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/c21s2v4/shared-memory-caches-5-50-/IbKCGrVGpco.pdf
  title: 3play pdf file
  type: null
  uid: 76bf4a70064d382fc1eea542543aecd2
- id: Caption-3Play YouTube id-SRT
  parent_uid: 8aef388b173b3709a0913862e2984222
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 089b677b046f0d63c33950feb0dd4c13
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 8aef388b173b3709a0913862e2984222
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 274050ebcfef7e48b301d6d571dfe862
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_21-02-04_300k.mp4
  parent_uid: 8aef388b173b3709a0913862e2984222
  title: Video-Internet Archive-MP4
  type: Video
  uid: c979dd4a04e6322a7a771cd8d0ef514f
inline_embed_id: 8588971sharedmemoryampcaches55052517049
layout: video
order_index: null
parent_uid: 46b3f31a0191fc66d43ebe3782359c3e
related_resources_text: ''
short_url: shared-memory-caches-5-50-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/c21s2v4/shared-memory-caches-5-50-
template_type: Embed
title: Shared Memory &amp; Caches
transcript: <p><span m="610">A</span> <span m="1049">conceptual</span> <span m="1488">schematic</span>
  <span m="1927">for</span> <span m="2366">a</span> <span m="2805">multicore</span>
  <span m="3244">processor</span> <span m="3683">is</span> <span m="4122">shown</span>
  <span m="4561">below.</span></p><p><span m="5000">To</span> <span m="5311">reduce</span>
  <span m="5623">the</span> <span m="5935">average</span> <span m="6247">memory</span>
  <span m="6559">access</span> <span m="6871">time,</span> <span m="7183">each</span>
  <span m="7495">of</span> <span m="7806">the</span> <span m="8118">four</span> <span
  m="8430">cores</span> <span m="8742">has</span> <span m="9054">its</span> <span
  m="9366">own</span> <span m="9678">cache,</span> <span m="9990">which</span> <span
  m="10596">will</span> <span m="11203">satisfy</span> <span m="11810">most</span>
  <span m="12416">memory</span> <span m="13023">requests.</span></p><p><span m="13630">If</span>
  <span m="13875">there's</span> <span m="14120">a</span> <span m="14365">cache</span>
  <span m="14610">miss,</span> <span m="14855">a</span> <span m="15100">request</span>
  <span m="15345">is</span> <span m="15590">sent</span> <span m="15835">to</span>
  <span m="16080">the</span> <span m="16325">shared</span> <span m="16570">main</span>
  <span m="16815">memory.</span></p><p><span m="17060">With</span> <span m="17383">a</span>
  <span m="17707">modest</span> <span m="18031">number</span> <span m="18355">of</span>
  <span m="18679">cores</span> <span m="19003">and</span> <span m="19327">a</span>
  <span m="19651">good</span> <span m="19975">cache</span> <span m="20298">hit</span>
  <span m="20622">ratio,</span> <span m="20946">the</span> <span m="21270">number</span>
  <span m="21594">of</span> <span m="21918">memory</span> <span m="22242">requests</span>
  <span m="22566">that</span> <span m="22890">must</span> <span m="23341">access</span>
  <span m="23793">main</span> <span m="24245">memory</span> <span m="24697">during</span>
  <span m="25149">normal</span> <span m="25600">operation</span> <span m="26052">should</span>
  <span m="26504">be</span> <span m="26956">pretty</span> <span m="27408">small.</span></p><p><span
  m="27860">To</span> <span m="28224">keep</span> <span m="28588">the</span> <span
  m="28952">number</span> <span m="29316">of</span> <span m="29680">memory</span>
  <span m="30044">accesses</span> <span m="30408">to</span> <span m="30772">a</span>
  <span m="31136">minimum,</span> <span m="31500">the</span> <span m="31864">caches</span>
  <span m="32228">implement</span> <span m="32592">a</span> <span m="32956">write-back</span>
  <span m="33320">strategy,</span> <span m="33773">where</span> <span m="34227">ST</span>
  <span m="34681">instructions</span> <span m="35135">update</span> <span m="35588">the</span>
  <span m="36042">cache,</span> <span m="36496">but</span> <span m="36950">main</span>
  <span m="37390">memory</span> <span m="37831">is</span> <span m="38272">only</span>
  <span m="38713">updated</span> <span m="39154">when</span> <span m="39595">a</span>
  <span m="40035">dirty</span> <span m="40476">cache</span> <span m="40917">line</span>
  <span m="41358">is</span> <span m="41799">replaced.</span></p><p><span m="42240">Our</span>
  <span m="42536">goal</span> <span m="42833">is</span> <span m="43130">that</span>
  <span m="43427">each</span> <span m="43724">core</span> <span m="44020">should</span>
  <span m="44317">share</span> <span m="44614">the</span> <span m="44911">contents</span>
  <span m="45208">of</span> <span m="45504">main</span> <span m="45801">memory,</span>
  <span m="46098">i.e.,</span> <span m="46395">changes</span> <span m="46692">made</span>
  <span m="46989">by</span> <span m="47421">one</span> <span m="47853">core</span>
  <span m="48285">should</span> <span m="48717">visible</span> <span m="49149">to</span>
  <span m="49581">all</span> <span m="50013">the</span> <span m="50445">other</span>
  <span m="50877">cores.</span></p><p><span m="51310">In</span> <span m="51699">the</span>
  <span m="52089">example</span> <span m="52479">shown</span> <span m="52869">here,</span>
  <span m="53259">core</span> <span m="53649">0</span> <span m="54039">is</span> <span
  m="54429">running</span> <span m="54819">Thread</span> <span m="55209">A</span>
  <span m="55599">and</span> <span m="55989">core</span> <span m="56379">1</span>
  <span m="56769">is</span> <span m="57159">running</span> <span m="57549">Thread</span>
  <span m="57939">B.</span></p><p><span m="58329">Both</span> <span m="58680">threads</span>
  <span m="59031">reference</span> <span m="59383">two</span> <span m="59734">shared</span>
  <span m="60086">memory</span> <span m="60437">locations</span> <span m="60788">holding</span>
  <span m="61140">the</span> <span m="61491">values</span> <span m="61843">for</span>
  <span m="62194">the</span> <span m="62545">variables</span> <span m="62897">X</span>
  <span m="63248">and</span> <span m="63600">Y.</span></p><p><span m="65510">The</span>
  <span m="65875">current</span> <span m="66240">values</span> <span m="66605">of</span>
  <span m="66970">X</span> <span m="67335">and</span> <span m="67700">Y</span> <span
  m="68065">are</span> <span m="68430">1</span> <span m="68795">and</span> <span m="69160">2,</span>
  <span m="69525">respectively.</span></p><p><span m="69890">Those</span> <span m="70238">values</span>
  <span m="70587">are</span> <span m="70936">held</span> <span m="71284">in</span>
  <span m="71633">main</span> <span m="71982">memory</span> <span m="72330">as</span>
  <span m="72679">well</span> <span m="73028">as</span> <span m="73376">being</span>
  <span m="73725">cached</span> <span m="74074">by</span> <span m="74422">each</span>
  <span m="74771">core.</span></p><p><span m="75120">What</span> <span m="75544">happens</span>
  <span m="75968">when</span> <span m="76392">the</span> <span m="76817">threads</span>
  <span m="77241">are</span> <span m="77665">executed?</span></p><p><span m="78090">Each</span>
  <span m="78506">thread</span> <span m="78922">executes</span> <span m="79338">independently,</span>
  <span m="79754">updating</span> <span m="80170">its</span> <span m="80586">cache</span>
  <span m="81003">during</span> <span m="81419">stores</span> <span m="81835">to</span>
  <span m="82251">X</span> <span m="82667">and</span> <span m="83083">Y.</span></p><p><span
  m="83500">For</span> <span m="83882">any</span> <span m="84265">possible</span>
  <span m="84648">execution</span> <span m="85030">order,</span> <span m="85413">either</span>
  <span m="85796">concurrent</span> <span m="86179">or</span> <span m="86561">sequential,</span>
  <span m="86944">the</span> <span m="87327">result</span> <span m="87710">is</span>
  <span m="88092">the</span> <span m="88475">same:</span> <span m="88858">Thread</span>
  <span m="89241">A</span> <span m="89785">prints</span> <span m="90329">&quot;2&quot;,</span>
  <span m="90873">Thread</span> <span m="91417">B</span> <span m="91961">prints</span>
  <span m="92505">&quot;1&quot;.</span></p><p><span m="93050">Hardware</span> <span
  m="93510">engineers</span> <span m="93971">would</span> <span m="94432">point</span>
  <span m="94893">to</span> <span m="95354">the</span> <span m="95815">consistent</span>
  <span m="96276">outcomes</span> <span m="96737">and</span> <span m="97198">declare</span>
  <span m="97659">victory!</span></p><p><span m="98120">But</span> <span m="98549">closer</span>
  <span m="98978">examination</span> <span m="99407">of</span> <span m="99836">the</span>
  <span m="100265">final</span> <span m="100694">system</span> <span m="101123">state</span>
  <span m="101552">reveals</span> <span m="101981">some</span> <span m="102410">problems.</span></p><p><span
  m="102840">After</span> <span m="103156">execution</span> <span m="103473">is</span>
  <span m="103790">complete,</span> <span m="104106">the</span> <span m="104423">two</span>
  <span m="104740">cores</span> <span m="105056">disagree</span> <span m="105373">on</span>
  <span m="105690">the</span> <span m="106006">values</span> <span m="106323">of</span>
  <span m="106640">X</span> <span m="106956">and</span> <span m="107273">Y.</span></p><p><span
  m="107590">Threads</span> <span m="108055">running</span> <span m="108520">on</span>
  <span m="108985">core</span> <span m="109450">0</span> <span m="109915">will</span>
  <span m="110380">see</span> <span m="110845">X=3</span> <span m="111310">and</span>
  <span m="111775">Y=2.</span></p><p><span m="112240">Threads</span> <span m="112750">running</span>
  <span m="113260">on</span> <span m="113770">core</span> <span m="114280">1</span>
  <span m="114790">will</span> <span m="115300">see</span> <span m="115810">X=1</span>
  <span m="116320">and</span> <span m="116830">Y=4.</span></p><p><span m="117340">Because</span>
  <span m="117690">of</span> <span m="118040">the</span> <span m="118390">caches,</span>
  <span m="118740">the</span> <span m="119090">system</span> <span m="119440">isn't</span>
  <span m="119790">behaving</span> <span m="120140">as</span> <span m="120490">if</span>
  <span m="120840">there's</span> <span m="121190">a</span> <span m="121540">single</span>
  <span m="121890">shared</span> <span m="122240">memory.</span></p><p><span m="122590">On</span>
  <span m="122845">the</span> <span m="123100">other</span> <span m="123356">hand,</span>
  <span m="123611">we</span> <span m="123866">can't</span> <span m="124122">eliminate</span>
  <span m="124377">the</span> <span m="124632">caches</span> <span m="124888">since</span>
  <span m="125143">that</span> <span m="125398">would</span> <span m="125654">cause</span>
  <span m="125909">the</span> <span m="126164">average</span> <span m="126420">memory</span>
  <span m="126880">access</span> <span m="127340">time</span> <span m="127800">to</span>
  <span m="128260">skyrocket,</span> <span m="128720">ruining</span> <span m="129180">any</span>
  <span m="129640">hoped-for</span> <span m="130100">performance</span> <span m="130560">improvement</span>
  <span m="131020">from</span> <span m="131480">using</span> <span m="131940">multiple</span>
  <span m="132894">cores.</span></p><p><span m="133849">What</span> <span m="134341">outcome</span>
  <span m="134833">should</span> <span m="135325">we</span> <span m="135817">expect?</span></p><p><span
  m="136310">One</span> <span m="136599">plausible</span> <span m="136888">standard</span>
  <span m="137178">of</span> <span m="137467">correctness</span> <span m="137756">is</span>
  <span m="138046">the</span> <span m="138335">outcome</span> <span m="138624">when</span>
  <span m="138914">the</span> <span m="139203">threads</span> <span m="139492">are</span>
  <span m="139782">run</span> <span m="140071">a</span> <span m="140360">single</span>
  <span m="140650">timeshared</span> <span m="141825">core.</span></p><p><span m="143000">The</span>
  <span m="143341">argument</span> <span m="143682">would</span> <span m="144023">be</span>
  <span m="144365">that</span> <span m="144706">a</span> <span m="145047">multicore</span>
  <span m="145388">implementation</span> <span m="145730">should</span> <span m="146071">produce</span>
  <span m="146412">the</span> <span m="146753">same</span> <span m="147095">outcome</span>
  <span m="147436">but</span> <span m="147777">more</span> <span m="148118">quickly,</span>
  <span m="148460">with</span> <span m="149070">parallel</span> <span m="149680">execution</span>
  <span m="150290">replacing</span> <span m="150900">timesharing.</span></p><p><span
  m="151510">The</span> <span m="151899">table</span> <span m="152288">shows</span>
  <span m="152677">the</span> <span m="153066">possible</span> <span m="153455">results</span>
  <span m="153844">of</span> <span m="154234">the</span> <span m="154623">timesharing</span>
  <span m="155012">experiment,</span> <span m="155401">where</span> <span m="155790">the</span>
  <span m="156179">outcome</span> <span m="156569">depends</span> <span m="156946">on</span>
  <span m="157323">the</span> <span m="157700">order</span> <span m="158077">in</span>
  <span m="158454">which</span> <span m="158831">the</span> <span m="159208">statements</span>
  <span m="159585">are</span> <span m="159962">executed.</span></p><p><span m="160340">Programmers</span>
  <span m="160689">will</span> <span m="161038">understand</span> <span m="161387">that</span>
  <span m="161737">there</span> <span m="162086">is</span> <span m="162435">more</span>
  <span m="162785">than</span> <span m="163134">one</span> <span m="163483">possible</span>
  <span m="163832">outcome</span> <span m="164182">and</span> <span m="164531">know</span>
  <span m="164880">that</span> <span m="165230">they</span> <span m="165646">would</span>
  <span m="166062">have</span> <span m="166478">to</span> <span m="166894">impose</span>
  <span m="167310">additional</span> <span m="167726">constraints</span> <span m="168143">on</span>
  <span m="168559">execution</span> <span m="168975">order,</span> <span m="169391">say,</span>
  <span m="169807">using</span> <span m="170223">semaphores,</span> <span m="170640">if</span>
  <span m="171185">they</span> <span m="171730">wanted</span> <span m="172275">a</span>
  <span m="172820">specific</span> <span m="173365">outcome.</span></p><p><span m="173910">Notice</span>
  <span m="174305">that</span> <span m="174701">the</span> <span m="175096">multicore</span>
  <span m="175492">outcome</span> <span m="175887">of</span> <span m="176283">2,1</span>
  <span m="176678">doesn't</span> <span m="177074">appear</span> <span m="177470">anywhere</span>
  <span m="177865">on</span> <span m="178261">the</span> <span m="178656">list</span>
  <span m="179052">of</span> <span m="179447">possible</span> <span m="179843">outcomes</span>
  <span m="180239">from</span> <span m="180976">sequential</span> <span m="181714">timeshared</span>
  <span m="182452">execution.</span></p><p><span m="183190">The</span> <span m="183557">notion</span>
  <span m="183924">that</span> <span m="184291">executing</span> <span m="184658">N</span>
  <span m="185025">threads</span> <span m="185392">in</span> <span m="185760">parallel</span>
  <span m="186127">should</span> <span m="186494">correspond</span> <span m="186861">to</span>
  <span m="187228">some</span> <span m="187595">interleaved</span> <span m="187962">execution</span>
  <span m="188330">of</span> <span m="188761">those</span> <span m="189193">threads</span>
  <span m="189625">on</span> <span m="190057">a</span> <span m="190489">single</span>
  <span m="190920">core</span> <span m="191352">is</span> <span m="191784">called</span>
  <span m="192216">&quot;sequential</span> <span m="192648">consistency&quot;.</span></p><p><span
  m="193080">If</span> <span m="193519">multicore</span> <span m="193958">systems</span>
  <span m="194397">implement</span> <span m="194836">sequential</span> <span m="195275">consistency,</span>
  <span m="195714">then</span> <span m="196153">programmers</span> <span m="196592">can</span>
  <span m="197031">think</span> <span m="197470">of</span> <span m="197910">the</span>
  <span m="198463">systems</span> <span m="199016">as</span> <span m="199570">providing</span>
  <span m="200123">hardware-accelerated</span> <span m="200676">timesharing.</span></p><p><span
  m="201230">So,</span> <span m="201634">our</span> <span m="202038">simple</span>
  <span m="202443">multicore</span> <span m="202847">system</span> <span m="203252">fails</span>
  <span m="203656">on</span> <span m="204061">two</span> <span m="204465">accounts.</span></p><p><span
  m="204870">First,</span> <span m="205200">it</span> <span m="205531">doesn't</span>
  <span m="205862">correctly</span> <span m="206192">implement</span> <span m="206523">a</span>
  <span m="206854">shared</span> <span m="207185">memory</span> <span m="207515">since,</span>
  <span m="207846">as</span> <span m="208177">we've</span> <span m="208507">seen,</span>
  <span m="208838">it's</span> <span m="209169">possible</span> <span m="209500">for</span>
  <span m="209805">the</span> <span m="210111">two</span> <span m="210417">cores</span>
  <span m="210722">to</span> <span m="211028">disagree</span> <span m="211334">about</span>
  <span m="211640">the</span> <span m="211945">current</span> <span m="212251">value</span>
  <span m="212557">of</span> <span m="212862">a</span> <span m="213168">shared</span>
  <span m="213474">variable.</span></p><p><span m="213780">Second,</span> <span m="214220">as</span>
  <span m="214660">a</span> <span m="215100">consequence</span> <span m="215540">of</span>
  <span m="215980">the</span> <span m="216420">first</span> <span m="216860">problem,</span>
  <span m="217300">the</span> <span m="217740">system</span> <span m="218180">doesn't</span>
  <span m="218620">implement</span> <span m="219060">sequential</span> <span m="219500">consistency.</span></p><p><span
  m="219940">Clearly,</span> <span m="220336">we'll</span> <span m="220732">need</span>
  <span m="221128">to</span> <span m="221525">figure</span> <span m="221921">out</span>
  <span m="222317">a</span> <span m="222713">fix!</span></p><p><span m="223110">One</span>
  <span m="223488">possible</span> <span m="223866">fix</span> <span m="224244">is</span>
  <span m="224622">to</span> <span m="225000">give</span> <span m="225378">up</span>
  <span m="225756">on</span> <span m="226134">sequential</span> <span m="226512">consistency.</span></p><p><span
  m="226890">An</span> <span m="227265">alternative</span> <span m="227641">memory</span>
  <span m="228017">semantics</span> <span m="228392">is</span> <span m="228768">&quot;weak</span>
  <span m="229144">consistency&quot;,</span> <span m="229520">which</span> <span m="229895">only</span>
  <span m="230271">requires</span> <span m="230647">that</span> <span m="231022">the</span>
  <span m="231398">memory</span> <span m="231774">operations</span> <span m="232150">from</span>
  <span m="232442">each</span> <span m="232734">thread</span> <span m="233026">appear</span>
  <span m="233318">to</span> <span m="233610">be</span> <span m="233902">performed</span>
  <span m="234194">in</span> <span m="234486">the</span> <span m="234778">order</span>
  <span m="235070">issued</span> <span m="235362">by</span> <span m="235654">that</span>
  <span m="235946">thread.</span></p><p><span m="236239">In</span> <span m="236572">other</span>
  <span m="236906">words,</span> <span m="237239">in</span> <span m="237573">a</span>
  <span m="237906">weakly</span> <span m="238240">consistent</span> <span m="238573">system,</span>
  <span m="238907">if</span> <span m="239240">a</span> <span m="239574">particular</span>
  <span m="239907">thread</span> <span m="240241">writes</span> <span m="240574">to</span>
  <span m="240908">X</span> <span m="241241">and</span> <span m="241575">then</span>
  <span m="241909">writes</span> <span m="242223">to</span> <span m="242537">Y,</span>
  <span m="242851">the</span> <span m="243165">possible</span> <span m="243480">outcomes</span>
  <span m="243794">from</span> <span m="244108">reads</span> <span m="244422">of</span>
  <span m="244736">X</span> <span m="245051">and</span> <span m="245365">Y</span>
  <span m="245679">by</span> <span m="245993">any</span> <span m="246307">thread</span>
  <span m="246622">would</span> <span m="246936">be</span> <span m="247250">one</span>
  <span m="247564">of</span> <span m="247879">(unchanged</span> <span m="248544">X,</span>
  <span m="249210">unchanged</span> <span m="249876">Y),</span> <span m="250541">or</span>
  <span m="251207">(changed</span> <span m="251873">X,</span> <span m="252538">unchanged</span>
  <span m="253204">Y),</span> <span m="253870">or</span> <span m="254632">(changed</span>
  <span m="255394">X,</span> <span m="256156">changed</span> <span m="256918">Y).</span></p><p><span
  m="257680">But</span> <span m="258170">no</span> <span m="258660">thread</span>
  <span m="259150">would</span> <span m="259640">see</span> <span m="260130">changed</span>
  <span m="260620">Y</span> <span m="261110">but</span> <span m="261600">unchanged</span>
  <span m="262090">X.</span></p><p><span m="262580">In</span> <span m="262892">a</span>
  <span m="263204">weakly</span> <span m="263516">consistent</span> <span m="263828">system,</span>
  <span m="264140">memory</span> <span m="264452">operations</span> <span m="264764">from</span>
  <span m="265076">other</span> <span m="265388">threads</span> <span m="265700">may</span>
  <span m="266012">overlap</span> <span m="266324">in</span> <span m="266636">arbitrary</span>
  <span m="266949">ways</span> <span m="267639">(not</span> <span m="268329">necessarily</span>
  <span m="269019">consistent</span> <span m="269709">with</span> <span m="270399">any</span>
  <span m="271089">sequential</span> <span m="271779">interleaving).</span></p><p><span
  m="272470">Note</span> <span m="272915">that</span> <span m="273361">our</span>
  <span m="273807">multicore</span> <span m="274253">cache</span> <span m="274698">system</span>
  <span m="275144">doesn't</span> <span m="275590">itself</span> <span m="276036">guarantee</span>
  <span m="276481">even</span> <span m="276927">weak</span> <span m="277373">consistency.</span></p><p><span
  m="277819">A</span> <span m="278149">thread</span> <span m="278480">that</span>
  <span m="278811">executes</span> <span m="279141">&quot;write</span> <span m="279472">X;</span>
  <span m="279803">write</span> <span m="280133">Y&quot;</span> <span m="280464">will</span>
  <span m="280795">update</span> <span m="281125">its</span> <span m="281456">local</span>
  <span m="281787">cache,</span> <span m="282117">but</span> <span m="282448">later</span>
  <span m="282779">cache</span> <span m="283110">replacements</span> <span m="283424">may</span>
  <span m="283738">cause</span> <span m="284052">the</span> <span m="284367">updated</span>
  <span m="284681">Y</span> <span m="284995">value</span> <span m="285310">to</span>
  <span m="285624">be</span> <span m="285938">written</span> <span m="286253">to</span>
  <span m="286567">main</span> <span m="286881">memory</span> <span m="287196">before</span>
  <span m="287510">the</span> <span m="287824">updated</span> <span m="288139">X</span>
  <span m="289089">value.</span></p><p><span m="290039">To</span> <span m="290456">implement</span>
  <span m="290873">weak</span> <span m="291290">consistency,</span> <span m="291707">the</span>
  <span m="292124">thread</span> <span m="292541">should</span> <span m="292958">be</span>
  <span m="293375">modified</span> <span m="293792">to</span> <span m="294209">&quot;write</span>
  <span m="294626">X;</span> <span m="295043">communicate</span> <span m="295460">changes</span>
  <span m="296004">to</span> <span m="296548">all</span> <span m="297092">other</span>
  <span m="297637">processors;</span> <span m="298181">write</span> <span m="298725">Y&quot;.</span></p><p><span
  m="299270">In</span> <span m="299528">the</span> <span m="299787">next</span> <span
  m="300045">section,</span> <span m="300304">we'll</span> <span m="300563">discuss</span>
  <span m="300821">how</span> <span m="301080">to</span> <span m="301338">modify</span>
  <span m="301597">the</span> <span m="301856">caches</span> <span m="302114">to</span>
  <span m="302373">perform</span> <span m="302631">the</span> <span m="302890">required</span>
  <span m="303149">communication</span> <span m="304974">automatically.</span></p><p><span
  m="306800">Out-of-order</span> <span m="307151">cores</span> <span m="307503">have</span>
  <span m="307855">an</span> <span m="308206">extra</span> <span m="308558">complication</span>
  <span m="308910">since</span> <span m="309261">there's</span> <span m="309613">no</span>
  <span m="309965">guarantee</span> <span m="310316">that</span> <span m="310668">successive</span>
  <span m="311020">ST</span> <span m="311456">instructions</span> <span m="311893">will</span>
  <span m="312329">complete</span> <span m="312766">in</span> <span m="313202">the</span>
  <span m="313639">order</span> <span m="314076">they</span> <span m="314512">appeared</span>
  <span m="314949">in</span> <span m="315385">the</span> <span m="315822">program.</span></p><p><span
  m="316259">These</span> <span m="316623">architectures</span> <span m="316987">provide</span>
  <span m="317351">a</span> <span m="317715">BARRIER</span> <span m="318079">instruction</span>
  <span m="318444">that</span> <span m="318808">guarantees</span> <span m="319172">that</span>
  <span m="319536">memory</span> <span m="319900">operations</span> <span m="320264">before</span>
  <span m="320629">the</span> <span m="321097">BARRIER</span> <span m="321565">are</span>
  <span m="322033">completed</span> <span m="322501">before</span> <span m="322969">memory</span>
  <span m="323438">operation</span> <span m="323906">executed</span> <span m="324374">after</span>
  <span m="324842">the</span> <span m="325310">BARRIER.</span></p><p><span m="325779">There</span>
  <span m="326267">are</span> <span m="326755">many</span> <span m="327244">types</span>
  <span m="327732">of</span> <span m="328220">memory</span> <span m="328709">consistency</span>
  <span m="329197">-</span> <span m="329685">each</span> <span m="330174">commercially-available</span>
  <span m="330662">multicore</span> <span m="331150">system</span> <span m="331639">has</span>
  <span m="332057">its</span> <span m="332476">own</span> <span m="332895">particular</span>
  <span m="333314">guarantees</span> <span m="333733">about</span> <span m="334152">what</span>
  <span m="334571">happens</span> <span m="334990">when.</span></p><p><span m="335409">So</span>
  <span m="335859">the</span> <span m="336309">prudent</span> <span m="336759">programmer</span>
  <span m="337209">needs</span> <span m="337659">to</span> <span m="338109">read</span>
  <span m="338559">the</span> <span m="339009">ISA</span> <span m="339459">manual</span>
  <span m="339909">carefully</span> <span m="340359">to</span> <span m="340809">ensure</span>
  <span m="341259">that</span> <span m="341709">her</span> <span m="342159">program</span>
  <span m="342610">will</span> <span m="342931">do</span> <span m="343253">what</span>
  <span m="343575">she</span> <span m="343897">wants.</span></p><p><span m="344219">See</span>
  <span m="344619">the</span> <span m="345020">referenced</span> <span m="345421">PDF</span>
  <span m="345821">file</span> <span m="346222">for</span> <span m="346623">a</span>
  <span m="347023">very</span> <span m="347424">readable</span> <span m="347825">discussion</span>
  <span m="348225">about</span> <span m="348626">memory</span> <span m="349027">semantics</span>
  <span m="349427">in</span> <span m="349828">multicore</span> <span m="350229">systems.</span></p>
type: course
uid: 8aef388b173b3709a0913862e2984222

---
None