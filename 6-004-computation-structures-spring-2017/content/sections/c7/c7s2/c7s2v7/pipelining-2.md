---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: hmPiuS0PqCs
  parent_uid: 6360085229b22f818010302844282491
  title: Video-YouTube-Stream
  type: Video
  uid: 484791052d127061e122756147945d53
- id: 3Play-3Play YouTube id-Stream
  media_location: hmPiuS0PqCs
  parent_uid: 6360085229b22f818010302844282491
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 2b9ab3078ff27eb6b0e593404016f756
- id: Video--MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_07-02-07-02_300k.mp4
  parent_uid: 6360085229b22f818010302844282491
  title: Video--MP4
  type: Video
  uid: ada47122c9eefe7b3e5289ead864a4ed
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/hmPiuS0PqCs/default.jpg
  parent_uid: 6360085229b22f818010302844282491
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e853e3d6baf5972799394bccc39a126d
- id: hmPiuS0PqCs.srt
  parent_uid: 6360085229b22f818010302844282491
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v7/pipelining-2/hmPiuS0PqCs.srt
  title: 3play caption file
  type: null
  uid: 706da7a3684c06dbf1ef885da94cb30d
- id: hmPiuS0PqCs.pdf
  parent_uid: 6360085229b22f818010302844282491
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v7/pipelining-2/hmPiuS0PqCs.pdf
  title: 3play pdf file
  type: null
  uid: d7b919076d0ca1491468da48ade81aed
- id: Caption-3Play YouTube id-SRT
  parent_uid: 6360085229b22f818010302844282491
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: a1ff4c42a07dabcae4776a908dc03982
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 6360085229b22f818010302844282491
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 0615aa871e2d83e3a1b4b278565bce13
inline_embed_id: 68932974pipelining241618471
layout: video
order_index: null
parent_uid: 1566994e2ac1dc389beafb70f2edc786
related_resources_text: ''
short_url: pipelining-2
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c7/c7s2/c7s2v7/pipelining-2
template_type: Embed
title: 'Worked Example: Pipelining 2'
transcript: <p><span m="959">We</span> <span m="1366">are</span> <span m="1773">given</span>
  <span m="2180">this</span> <span m="2587">circuit</span> <span m="2995">which</span>
  <span m="3402">consists</span> <span m="3809">of</span> <span m="4216">nine</span>
  <span m="4623">combinational</span> <span m="5031">modules</span> <span m="5438">connected</span>
  <span m="5845">as</span> <span m="6252">shown.</span></p><p><span m="6660">The</span>
  <span m="7045">number</span> <span m="7431">in</span> <span m="7816">each</span>
  <span m="8202">block</span> <span m="8588">corresponds</span> <span m="8973">to</span>
  <span m="9359">the</span> <span m="9745">propagation</span> <span m="10130">delay</span>
  <span m="10516">(in</span> <span m="10902">microseconds)</span> <span m="11287">of</span>
  <span m="11673">that</span> <span m="12059">block.</span></p><p><span m="13349">The</span>
  <span m="13636">first</span> <span m="13924">question</span> <span m="14211">we</span>
  <span m="14499">want</span> <span m="14786">to</span> <span m="15074">ask</span>
  <span m="15361">ourselves</span> <span m="15649">is</span> <span m="15936">what</span>
  <span m="16224">are</span> <span m="16511">the</span> <span m="16799">latency</span>
  <span m="17086">and</span> <span m="17374">throughput</span> <span m="17661">of</span>
  <span m="17949">this</span> <span m="18862">combinational</span> <span m="19775">circuit?</span></p><p><span
  m="20689">The</span> <span m="21106">longest</span> <span m="21523">path</span>
  <span m="21941">through</span> <span m="22358">this</span> <span m="22776">circuit</span>
  <span m="23193">passes</span> <span m="23610">through</span> <span m="24028">two</span>
  <span m="24445">3</span> <span m="24863">microsecond</span> <span m="25280">modules,</span>
  <span m="25697">one</span> <span m="26115">2</span> <span m="26532">microsecond</span>
  <span m="26950">module,</span> <span m="27559">and</span> <span m="28169">two</span>
  <span m="28779">1</span> <span m="29389">microsecond</span> <span m="29999">modules.</span></p><p><span
  m="30609">Therefore</span> <span m="31414">the</span> <span m="32219">latency</span>
  <span m="33024">=</span> <span m="33829">2(3)</span> <span m="34634">+</span> <span
  m="35439">1(2)</span> <span m="36244">+</span> <span m="37049">2(1)</span> <span
  m="37854">=</span> <span m="38659">10</span> <span m="39464">microseconds.</span></p><p><span
  m="40270">The</span> <span m="41377">throughput</span> <span m="42484">is</span>
  <span m="43591">1/Latency</span> <span m="44698">=</span> <span m="45805">1/(10</span>
  <span m="46912">microseconds).</span></p><p><span m="48019">Now</span> <span m="48450">we</span>
  <span m="48881">want</span> <span m="49312">to</span> <span m="49743">pipeline</span>
  <span m="50174">this</span> <span m="50605">circuit</span> <span m="51036">for</span>
  <span m="51467">maximum</span> <span m="51898">throughput.</span></p><p><span m="52329">Recall</span>
  <span m="52696">that</span> <span m="53064">the</span> <span m="53431">clock</span>
  <span m="53799">period</span> <span m="54166">must</span> <span m="54534">allow</span>
  <span m="54901">enough</span> <span m="55269">time</span> <span m="55637">for</span>
  <span m="56004">the</span> <span m="56372">propagation</span> <span m="56739">delay</span>
  <span m="57107">of</span> <span m="57474">the</span> <span m="57842">pipeline</span>
  <span m="58210">register,</span> <span m="58749">plus</span> <span m="59288">the</span>
  <span m="59827">propagation</span> <span m="60366">delay</span> <span m="60906">of</span>
  <span m="61445">any</span> <span m="61984">combinational</span> <span m="62523">logic</span>
  <span m="63063">between</span> <span m="63602">the</span> <span m="64141">pipeline</span>
  <span m="64680">registers,</span> <span m="65220">plus</span> <span m="65648">the</span>
  <span m="66077">setup</span> <span m="66505">time</span> <span m="66934">of</span>
  <span m="67363">the</span> <span m="67791">pipeline</span> <span m="68220">register.</span></p><p><span
  m="68649">Since</span> <span m="69011">our</span> <span m="69374">pipeline</span>
  <span m="69737">registers</span> <span m="70099">are</span> <span m="70462">ideal,</span>
  <span m="70825">the</span> <span m="71188">propagation</span> <span m="71550">delay</span>
  <span m="71913">and</span> <span m="72276">setup</span> <span m="72639">time</span>
  <span m="73001">of</span> <span m="73364">the</span> <span m="73727">pipeline</span>
  <span m="74090">registers</span> <span m="74541">is</span> <span m="74992">0,</span>
  <span m="75443">so</span> <span m="75895">our</span> <span m="76346">clock</span>
  <span m="76797">period</span> <span m="77248">will</span> <span m="77700">be</span>
  <span m="78151">equal</span> <span m="78602">to</span> <span m="79053">the</span>
  <span m="79505">longest</span> <span m="79956">combinational</span> <span m="80407">logic</span>
  <span m="80858">delay</span> <span m="81310">between</span> <span m="81848">any</span>
  <span m="82386">pair</span> <span m="82924">of</span> <span m="83462">pipeline</span>
  <span m="84000">registers.</span></p><p><span m="84539">To</span> <span m="84896">minimize</span>
  <span m="85254">the</span> <span m="85611">clock</span> <span m="85969">period,</span>
  <span m="86326">we</span> <span m="86684">want</span> <span m="87041">to</span>
  <span m="87399">add</span> <span m="87756">pipeline</span> <span m="88114">contours</span>
  <span m="88471">so</span> <span m="88829">that</span> <span m="89186">each</span>
  <span m="89544">pipeline</span> <span m="89901">stage</span> <span m="90259">can</span>
  <span m="90679">be</span> <span m="91100">clocked</span> <span m="91521">at</span>
  <span m="91941">the</span> <span m="92362">rate</span> <span m="92783">of</span>
  <span m="93204">our</span> <span m="93624">slowest</span> <span m="94045">component</span>
  <span m="94466">which</span> <span m="94886">is</span> <span m="95307">3</span>
  <span m="95728">microseconds.</span></p><p><span m="96149">This</span> <span m="96561">means</span>
  <span m="96974">that</span> <span m="97387">within</span> <span m="97799">a</span>
  <span m="98212">single</span> <span m="98625">pipeline</span> <span m="99038">stage</span>
  <span m="99450">all</span> <span m="99863">combinational</span> <span m="100276">paths</span>
  <span m="100689">must</span> <span m="101101">have</span> <span m="101514">at</span>
  <span m="101927">most</span> <span m="102340">a</span> <span m="102806">propagation</span>
  <span m="103273">delay</span> <span m="103740">of</span> <span m="104206">3</span>
  <span m="104673">microseconds.</span></p><p><span m="105140">Recall,</span> <span
  m="105545">that</span> <span m="105950">when</span> <span m="106356">pipelining</span>
  <span m="106761">a</span> <span m="107166">circuit,</span> <span m="107572">all</span>
  <span m="107977">outputs</span> <span m="108382">must</span> <span m="108788">have</span>
  <span m="109193">a</span> <span m="109598">pipeline</span> <span m="110004">register</span>
  <span m="110409">on</span> <span m="110814">them,</span> <span m="111220">so</span>
  <span m="111640">our</span> <span m="112060">first</span> <span m="112480">contour</span>
  <span m="112900">is</span> <span m="113320">drawn</span> <span m="113740">so</span>
  <span m="114160">as</span> <span m="114580">to</span> <span m="115000">cross</span>
  <span m="115420">the</span> <span m="115840">single</span> <span m="116260">output</span>
  <span m="116680">C(X).</span></p><p><span m="117100">Each</span> <span m="117483">pipeline</span>
  <span m="117866">stage</span> <span m="118250">should</span> <span m="118633">have</span>
  <span m="119016">at</span> <span m="119400">most</span> <span m="119783">a</span>
  <span m="120166">latency</span> <span m="120550">of</span> <span m="120933">3</span>
  <span m="121316">microseconds.</span></p><p><span m="121700">This</span> <span m="122060">means</span>
  <span m="122420">that</span> <span m="122780">the</span> <span m="123140">bottom</span>
  <span m="123500">right</span> <span m="123860">1</span> <span m="124220">microsecond</span>
  <span m="124580">module</span> <span m="124940">and</span> <span m="125300">the</span>
  <span m="125660">3</span> <span m="126020">microsecond</span> <span m="126380">module</span>
  <span m="126740">above</span> <span m="127100">it</span> <span m="127523">must</span>
  <span m="127947">be</span> <span m="128370">in</span> <span m="128794">separate</span>
  <span m="129217">pipeline</span> <span m="129641">stages</span> <span m="130065">so</span>
  <span m="130488">our</span> <span m="130912">next</span> <span m="131335">contour</span>
  <span m="131759">crosses</span> <span m="132182">between</span> <span m="132606">them.</span></p><p><span
  m="133030">We</span> <span m="133321">then</span> <span m="133612">complete</span>
  <span m="133903">that</span> <span m="134194">contour</span> <span m="134485">by</span>
  <span m="134776">joining</span> <span m="135067">each</span> <span m="135358">end</span>
  <span m="135650">of</span> <span m="135941">the</span> <span m="136232">contour</span>
  <span m="136523">to</span> <span m="136814">one</span> <span m="137105">of</span>
  <span m="137396">the</span> <span m="137687">two</span> <span m="137978">ends</span>
  <span m="138270">of</span> <span m="138804">our</span> <span m="139338">original</span>
  <span m="139872">output</span> <span m="140406">contour.</span></p><p><span m="140940">Every</span>
  <span m="141271">time</span> <span m="141602">a</span> <span m="141934">wire</span>
  <span m="142265">is</span> <span m="142596">crossed,</span> <span m="142928">that</span>
  <span m="143259">indicates</span> <span m="143590">that</span> <span m="143922">we</span>
  <span m="144253">are</span> <span m="144584">adding</span> <span m="144916">a</span>
  <span m="145247">pipeline</span> <span m="145578">register.</span></p><p><span m="145910">There</span>
  <span m="146281">is</span> <span m="146652">more</span> <span m="147023">than</span>
  <span m="147394">one</span> <span m="147765">way</span> <span m="148136">of</span>
  <span m="148507">doing</span> <span m="148878">this</span> <span m="149250">because</span>
  <span m="149621">for</span> <span m="149992">example,</span> <span m="150363">the</span>
  <span m="150734">bottom</span> <span m="151105">three</span> <span m="151476">1</span>
  <span m="151847">units</span> <span m="152218">could</span> <span m="152590">all</span>
  <span m="152966">be</span> <span m="153342">in</span> <span m="153718">the</span>
  <span m="154095">same</span> <span m="154471">pipeline</span> <span m="154847">stage,</span>
  <span m="155223">or</span> <span m="155600">just</span> <span m="155976">the</span>
  <span m="156352">two</span> <span m="156728">rightmost</span> <span m="157105">bottom</span>
  <span m="157481">1</span> <span m="157857">unit</span> <span m="158233">components,</span>
  <span m="158610">or</span> <span m="158993">just</span> <span m="159376">the</span>
  <span m="159760">single</span> <span m="160143">bottom</span> <span m="160526">right</span>
  <span m="160910">1</span> <span m="161293">unit</span> <span m="161676">component.</span></p><p><span
  m="162060">Let's</span> <span m="162292">try</span> <span m="162525">to</span> <span
  m="162758">pipeline</span> <span m="162991">this</span> <span m="163224">circuit</span>
  <span m="163457">in</span> <span m="163690">two</span> <span m="163923">different</span>
  <span m="164156">ways</span> <span m="164389">to</span> <span m="164622">make</span>
  <span m="164855">sure</span> <span m="165088">that</span> <span m="165321">we</span>
  <span m="165554">end</span> <span m="165787">up</span> <span m="166020">with</span>
  <span m="166470">the</span> <span m="166920">same</span> <span m="167370">latency</span>
  <span m="167820">and</span> <span m="168270">throughput</span> <span m="168720">results.</span></p><p><span
  m="169170">For</span> <span m="169621">our</span> <span m="170073">first</span>
  <span m="170525">implementation,</span> <span m="170977">let's</span> <span m="171429">put</span>
  <span m="171881">the</span> <span m="172333">bottom</span> <span m="172785">right</span>
  <span m="173236">1</span> <span m="173688">unit</span> <span m="174140">in</span>
  <span m="174592">its</span> <span m="175044">own</span> <span m="175496">pipeline</span>
  <span m="175948">stage.</span></p><p><span m="176400">Next</span> <span m="176833">we</span>
  <span m="177267">have</span> <span m="177701">a</span> <span m="178135">pipeline</span>
  <span m="178569">stage</span> <span m="179003">that</span> <span m="179436">includes</span>
  <span m="179870">our</span> <span m="180304">second</span> <span m="180738">row</span>
  <span m="181172">3</span> <span m="181606">unit.</span></p><p><span m="182040">We</span>
  <span m="182340">can</span> <span m="182640">include</span> <span m="182940">the</span>
  <span m="183240">middle</span> <span m="183540">bottom</span> <span m="183840">1</span>
  <span m="184140">unit</span> <span m="184440">in</span> <span m="184740">this</span>
  <span m="185040">same</span> <span m="185340">pipeline</span> <span m="185640">stage</span>
  <span m="185940">because</span> <span m="186240">those</span> <span m="186540">two</span>
  <span m="186840">units</span> <span m="187286">are</span> <span m="187733">independent</span>
  <span m="188180">of</span> <span m="188626">each</span> <span m="189073">other</span>
  <span m="189520">and</span> <span m="189966">can</span> <span m="190413">be</span>
  <span m="190860">executed</span> <span m="191306">in</span> <span m="191753">parallel.</span></p><p><span
  m="192200">Now</span> <span m="192495">we</span> <span m="192791">see</span> <span
  m="193087">that</span> <span m="193382">we</span> <span m="193678">have</span> <span
  m="193974">a</span> <span m="194270">bunch</span> <span m="194565">of</span> <span
  m="194861">2</span> <span m="195157">and</span> <span m="195452">1</span> <span
  m="195748">unit</span> <span m="196044">components.</span></p><p><span m="196340">We</span>
  <span m="196661">want</span> <span m="196982">to</span> <span m="197303">isolate</span>
  <span m="197624">these</span> <span m="197945">from</span> <span m="198266">the</span>
  <span m="198587">top</span> <span m="198908">left</span> <span m="199230">3</span>
  <span m="199551">unit</span> <span m="199872">component,</span> <span m="200193">so</span>
  <span m="200514">we</span> <span m="200835">draw</span> <span m="201156">our</span>
  <span m="201477">final</span> <span m="201798">contour</span> <span m="202120">to</span>
  <span m="202658">isolate</span> <span m="203196">that</span> <span m="203734">3</span>
  <span m="204272">unit.</span></p><p><span m="204810">Note</span> <span m="205111">that</span>
  <span m="205413">at</span> <span m="205714">this</span> <span m="206016">point</span>
  <span m="206317">all</span> <span m="206619">the</span> <span m="206920">remaining</span>
  <span m="207222">2</span> <span m="207523">and</span> <span m="207825">1</span>
  <span m="208126">unit</span> <span m="208428">modules</span> <span m="208729">add</span>
  <span m="209031">up</span> <span m="209332">to</span> <span m="209634">at</span>
  <span m="209935">most</span> <span m="210237">3</span> <span m="210538">microseconds</span>
  <span m="210840">along</span> <span m="211271">any</span> <span m="211702">path</span>
  <span m="212133">in</span> <span m="212565">the</span> <span m="212996">second</span>
  <span m="213427">pipeline</span> <span m="213858">stage.</span></p><p><span m="214290">This</span>
  <span m="214620">means</span> <span m="214950">that</span> <span m="215280">we</span>
  <span m="215610">are</span> <span m="215940">done</span> <span m="216270">and</span>
  <span m="216600">we</span> <span m="216930">do</span> <span m="217260">not</span>
  <span m="217590">need</span> <span m="217920">to</span> <span m="218250">add</span>
  <span m="218580">any</span> <span m="218910">further</span> <span m="219240">pipeline</span>
  <span m="219570">stages.</span></p><p><span m="219900">So</span> <span m="220439">our</span>
  <span m="220979">pipelined</span> <span m="221519">circuit</span> <span m="222059">ended</span>
  <span m="222599">up</span> <span m="223139">with</span> <span m="223679">4</span>
  <span m="224219">pipeline</span> <span m="224759">stages</span> <span m="225299">and</span>
  <span m="225839">our</span> <span m="226379">clock</span> <span m="226919">period</span>
  <span m="227459">=</span> <span m="227999">3</span> <span m="228539">microseconds.</span></p><p><span
  m="229079">This</span> <span m="229679">means</span> <span m="230279">that</span>
  <span m="230879">our</span> <span m="231479">pipelined</span> <span m="232079">latency</span>
  <span m="232679">is</span> <span m="233279">4</span> <span m="233879">*</span> <span
  m="234479">T</span> <span m="235079">=</span> <span m="235679">4</span> <span m="236279">*</span>
  <span m="236879">3</span> <span m="237479">=</span> <span m="238079">12</span> <span
  m="238679">microseconds.</span></p><p><span m="239280">Our</span> <span m="240124">throughput</span>
  <span m="240969">for</span> <span m="241813">the</span> <span m="242658">pipelined</span>
  <span m="243502">circuit</span> <span m="244347">is</span> <span m="245191">1/T</span>
  <span m="246036">=</span> <span m="246880">1/(3</span> <span m="247725">microseconds).</span></p><p><span
  m="248570">Note</span> <span m="248907">that</span> <span m="249244">the</span>
  <span m="249581">latency</span> <span m="249918">of</span> <span m="250255">the</span>
  <span m="250592">pipelined</span> <span m="250930">circuit</span> <span m="251267">is</span>
  <span m="251604">actually</span> <span m="251941">slower</span> <span m="252278">than</span>
  <span m="252615">the</span> <span m="252952">combinational</span> <span m="253290">latency.</span></p><p><span
  m="254480">This</span> <span m="254880">occurs</span> <span m="255281">because</span>
  <span m="255681">our</span> <span m="256082">pipelined</span> <span m="256483">implementation</span>
  <span m="256883">has</span> <span m="257284">some</span> <span m="257685">unused</span>
  <span m="258085">cycles</span> <span m="258486">in</span> <span m="258887">the</span>
  <span m="259287">last</span> <span m="259688">pipeline</span> <span m="260089">stage.</span></p><p><span
  m="261089">However,</span> <span m="261396">our</span> <span m="261704">throughput</span>
  <span m="262011">is</span> <span m="262319">significantly</span> <span m="262626">better</span>
  <span m="262934">as</span> <span m="263241">a</span> <span m="263549">result</span>
  <span m="263856">of</span> <span m="264164">being</span> <span m="264471">able</span>
  <span m="264779">to</span> <span m="265086">now</span> <span m="265394">have</span>
  <span m="265701">our</span> <span m="266009">clock</span> <span m="266575">period</span>
  <span m="267141">equal</span> <span m="267707">to</span> <span m="268273">the</span>
  <span m="268839">length</span> <span m="269405">of</span> <span m="269971">the</span>
  <span m="270537">slowest</span> <span m="271103">component.</span></p><p><span m="271669">Recall</span>
  <span m="271959">that</span> <span m="272250">we</span> <span m="272540">said</span>
  <span m="272831">that</span> <span m="273122">this</span> <span m="273412">was</span>
  <span m="273703">not</span> <span m="273994">the</span> <span m="274284">only</span>
  <span m="274575">way</span> <span m="274866">that</span> <span m="275156">we</span>
  <span m="275447">could</span> <span m="275738">draw</span> <span m="276028">our</span>
  <span m="276319">contours.</span></p><p><span m="276610">Let's</span> <span m="276956">try</span>
  <span m="277302">an</span> <span m="277648">alternate</span> <span m="277994">solution.</span></p><p><span
  m="278340">For</span> <span m="278730">our</span> <span m="279121">second</span>
  <span m="279511">solution,</span> <span m="279902">let's</span> <span m="280293">try</span>
  <span m="280683">to</span> <span m="281074">merge</span> <span m="281465">the</span>
  <span m="281855">bottom</span> <span m="282246">three</span> <span m="282636">1</span>
  <span m="283027">units</span> <span m="283418">into</span> <span m="283808">one</span>
  <span m="284199">pipeline</span> <span m="284590">stage.</span></p><p><span m="286240">Next</span>
  <span m="286621">we</span> <span m="287002">need</span> <span m="287383">to</span>
  <span m="287764">isolate</span> <span m="288145">our</span> <span m="288526">middle</span>
  <span m="288907">3.</span></p><p><span m="289289">The</span> <span m="289635">remaining</span>
  <span m="289981">2</span> <span m="290327">and</span> <span m="290673">1</span>
  <span m="291019">unit</span> <span m="291365">components</span> <span m="291711">can</span>
  <span m="292057">all</span> <span m="292403">be</span> <span m="292749">merged</span>
  <span m="293095">into</span> <span m="293441">another</span> <span m="293787">pipeline</span>
  <span m="294133">stage.</span></p><p><span m="294479">Finally,</span> <span m="294946">the</span>
  <span m="295414">top</span> <span m="295881">left</span> <span m="296349">3</span>
  <span m="296816">ends</span> <span m="297284">up</span> <span m="297752">in</span>
  <span m="298219">its</span> <span m="298687">own</span> <span m="299154">pipeline</span>
  <span m="299622">stage.</span></p><p><span m="300090">As</span> <span m="300394">before</span>
  <span m="300699">we</span> <span m="301004">end</span> <span m="301309">up</span>
  <span m="301614">with</span> <span m="301919">4</span> <span m="302224">pipeline</span>
  <span m="302529">stages</span> <span m="302834">that</span> <span m="303139">can</span>
  <span m="303444">be</span> <span m="303749">clocked</span> <span m="304054">with</span>
  <span m="304359">a</span> <span m="304664">period</span> <span m="304969">of</span>
  <span m="305274">T</span> <span m="305579">=</span> <span m="305884">3</span> <span
  m="306189">microseconds.</span></p><p><span m="307439">This</span> <span m="307848">demonstrates</span>
  <span m="308257">that</span> <span m="308667">both</span> <span m="309076">component</span>
  <span m="309486">divisions</span> <span m="309895">end</span> <span m="310304">up</span>
  <span m="310714">with</span> <span m="311123">a</span> <span m="311533">latency</span>
  <span m="311942">of</span> <span m="312351">12</span> <span m="312761">microseconds</span>
  <span m="313170">and</span> <span m="313580">a</span> <span m="314776">throughput</span>
  <span m="315972">of</span> <span m="317168">1/(3</span> <span m="318364">microseconds).</span></p><p><span
  m="319560">Now</span> <span m="319943">suppose</span> <span m="320326">you</span>
  <span m="320710">found</span> <span m="321093">pipelined</span> <span m="321476">replacements</span>
  <span m="321860">for</span> <span m="322243">the</span> <span m="322626">components</span>
  <span m="323010">marked</span> <span m="323393">3</span> <span m="323776">and</span>
  <span m="324160">2</span> <span m="324543">that</span> <span m="324926">had</span>
  <span m="325310">3</span> <span m="325753">and</span> <span m="326197">2</span>
  <span m="326640">stages,</span> <span m="327084">respectively,</span> <span m="327527">and</span>
  <span m="327971">could</span> <span m="328415">be</span> <span m="328858">clocked</span>
  <span m="329302">at</span> <span m="329745">a</span> <span m="330189">1</span> <span
  m="330632">microsecond</span> <span m="331076">period.</span></p><p><span m="331520">Using</span>
  <span m="331919">these</span> <span m="332318">replacements</span> <span m="332717">and</span>
  <span m="333116">pipelining</span> <span m="333516">for</span> <span m="333915">maximum</span>
  <span m="334314">throughput,</span> <span m="334713">what</span> <span m="335113">is</span>
  <span m="335512">the</span> <span m="335911">best</span> <span m="336310">achievable</span>
  <span m="336710">performance?</span></p><p><span m="338880">With</span> <span m="339171">these</span>
  <span m="339463">new</span> <span m="339755">components</span> <span m="340047">that</span>
  <span m="340339">can</span> <span m="340631">each</span> <span m="340923">be</span>
  <span m="341215">clocked</span> <span m="341507">with</span> <span m="341799">a</span>
  <span m="342091">period</span> <span m="342383">of</span> <span m="342675">1</span>
  <span m="342967">microsecond,</span> <span m="343259">our</span> <span m="343551">clock</span>
  <span m="344030">period</span> <span m="344510">T</span> <span m="344990">goes</span>
  <span m="345470">down</span> <span m="345949">to</span> <span m="346429">1</span>
  <span m="346909">microsecond.</span></p><p><span m="347389">The</span> <span m="347749">number</span>
  <span m="348109">of</span> <span m="348469">stages</span> <span m="348829">in</span>
  <span m="349189">our</span> <span m="349549">pipeline,</span> <span m="349909">however,</span>
  <span m="350269">now</span> <span m="350629">rises</span> <span m="350989">to</span>
  <span m="351349">10</span> <span m="351709">stages</span> <span m="352069">because</span>
  <span m="352429">these</span> <span m="352789">new</span> <span m="353149">components</span>
  <span m="353509">each</span> <span m="354017">have</span> <span m="354526">multiple</span>
  <span m="355035">pipeline</span> <span m="355543">stages</span> <span m="356052">in</span>
  <span m="356561">them.</span></p><p><span m="357070">So</span> <span m="357646">our</span>
  <span m="358222">new</span> <span m="358798">latency</span> <span m="359374">is</span>
  <span m="359950">L</span> <span m="360526">=</span> <span m="361102">10</span> <span
  m="361678">*</span> <span m="362254">T</span> <span m="362830">=</span> <span m="363406">10(1)</span>
  <span m="363982">=</span> <span m="364558">10</span> <span m="365134">microseconds.</span></p><p><span
  m="365710">The</span> <span m="366577">throughput</span> <span m="367444">is</span>
  <span m="368311">1/T</span> <span m="369178">=</span> <span m="370045">1/(1</span>
  <span m="370912">microsecond).</span></p>
type: course
uid: 6360085229b22f818010302844282491

---
None