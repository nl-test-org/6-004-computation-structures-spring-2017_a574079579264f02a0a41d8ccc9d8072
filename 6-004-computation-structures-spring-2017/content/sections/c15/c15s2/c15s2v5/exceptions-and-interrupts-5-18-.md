---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: iQR_6f5Jdns
  parent_uid: 1b5df9fc3987868d1b050cee018b6744
  title: Video-YouTube-Stream
  type: Video
  uid: 20622905f95a9c9685f93a0d9680ea5b
- id: 3Play-3Play YouTube id-Stream
  media_location: iQR_6f5Jdns
  parent_uid: 1b5df9fc3987868d1b050cee018b6744
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: fbac7f0612f50a3e2c0e97a4191f8bba
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/iQR_6f5Jdns/default.jpg
  parent_uid: 1b5df9fc3987868d1b050cee018b6744
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: b63cfde103bc07650c19bdab5f5fdb1b
- id: iQR_6f5Jdns.srt
  parent_uid: 1b5df9fc3987868d1b050cee018b6744
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v5/exceptions-and-interrupts-5-18-/iQR_6f5Jdns.srt
  title: 3play caption file
  type: null
  uid: 86b08e0396ece173e92eb74b78f82357
- id: iQR_6f5Jdns.pdf
  parent_uid: 1b5df9fc3987868d1b050cee018b6744
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v5/exceptions-and-interrupts-5-18-/iQR_6f5Jdns.pdf
  title: 3play pdf file
  type: null
  uid: 51fdb516a887cfba91f726575983bece
- id: Caption-3Play YouTube id-SRT
  parent_uid: 1b5df9fc3987868d1b050cee018b6744
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 0762562017601983efbf1323c29cfa7f
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 1b5df9fc3987868d1b050cee018b6744
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: c41f989b335a215ec1a841be46165e5d
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_15-02-05_300k.mp4
  parent_uid: 1b5df9fc3987868d1b050cee018b6744
  title: Video-Internet Archive-MP4
  type: Video
  uid: d32f9bc1c41b1c75e3ecde65a77f97c4
inline_embed_id: 43976584exceptionsandinterrupts51842136594
layout: video
order_index: null
parent_uid: 566964bcf6d42a67c3e39241f06c1aca
related_resources_text: ''
short_url: exceptions-and-interrupts-5-18-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v5/exceptions-and-interrupts-5-18-
template_type: Embed
title: Exceptions and Interrupts
transcript: <p><span m="599">Now</span> <span m="1094">let's</span> <span m="1590">figure</span>
  <span m="2086">out</span> <span m="2581">how</span> <span m="3077">exceptions</span>
  <span m="3573">impact</span> <span m="4068">pipelined</span> <span m="4564">execution.</span></p><p><span
  m="5060">When</span> <span m="5382">an</span> <span m="5705">exception</span> <span
  m="6028">occurs</span> <span m="6350">because</span> <span m="6673">of</span> <span
  m="6996">an</span> <span m="7318">illegal</span> <span m="7641">instruction</span>
  <span m="7964">or</span> <span m="8286">an</span> <span m="8609">external</span>
  <span m="8932">interrupt,</span> <span m="9254">we</span> <span m="9577">need</span>
  <span m="9900">to</span> <span m="10207">store</span> <span m="10515">the</span>
  <span m="10822">current</span> <span m="11130">PC+4</span> <span m="11437">value</span>
  <span m="11745">in</span> <span m="12052">the</span> <span m="12360">XP</span> <span
  m="12667">register</span> <span m="12975">and</span> <span m="13282">load</span>
  <span m="13590">the</span> <span m="13897">program</span> <span m="14205">counter</span>
  <span m="14512">with</span> <span m="14820">the</span> <span m="15378">address</span>
  <span m="15937">of</span> <span m="16495">the</span> <span m="17054">appropriate</span>
  <span m="17612">exception</span> <span m="18171">handler.</span></p><p><span m="18730">Exceptions</span>
  <span m="19141">cause</span> <span m="19553">control</span> <span m="19965">flow</span>
  <span m="20377">hazards</span> <span m="20789">since</span> <span m="21200">they</span>
  <span m="21612">are</span> <span m="22024">effectively</span> <span m="22436">implicit</span>
  <span m="22848">branches.</span></p><p><span m="23260">In</span> <span m="23776">an</span>
  <span m="24293">unpipelined</span> <span m="24810">implementation,</span> <span
  m="25326">exceptions</span> <span m="25843">affect</span> <span m="26360">the</span>
  <span m="26876">execution</span> <span m="27393">of</span> <span m="27910">the</span>
  <span m="28426">current</span> <span m="28943">instruction.</span></p><p><span m="29460">We</span>
  <span m="29851">want</span> <span m="30243">to</span> <span m="30635">achieve</span>
  <span m="31026">exactly</span> <span m="31418">the</span> <span m="31810">same</span>
  <span m="32201">effect</span> <span m="32593">in</span> <span m="32985">our</span>
  <span m="33376">pipelined</span> <span m="33768">implementation.</span></p><p><span
  m="34160">So</span> <span m="34468">first</span> <span m="34777">we</span> <span
  m="35086">have</span> <span m="35395">to</span> <span m="35703">identify</span>
  <span m="36012">which</span> <span m="36321">one</span> <span m="36630">of</span>
  <span m="36938">the</span> <span m="37247">instructions</span> <span m="37556">in</span>
  <span m="37865">our</span> <span m="38173">pipeline</span> <span m="38482">is</span>
  <span m="38791">affected,</span> <span m="39100">then</span> <span m="39471">ensure</span>
  <span m="39842">that</span> <span m="40214">instructions</span> <span m="40585">that</span>
  <span m="40956">came</span> <span m="41328">earlier</span> <span m="41699">in</span>
  <span m="42070">the</span> <span m="42442">code</span> <span m="42813">complete</span>
  <span m="43184">correctly</span> <span m="43556">and</span> <span m="43927">that</span>
  <span m="44298">we</span> <span m="44670">annul</span> <span m="45063">the</span>
  <span m="45457">affected</span> <span m="45851">instruction</span> <span m="46245">and</span>
  <span m="46638">any</span> <span m="47032">following</span> <span m="47426">instructions</span>
  <span m="47820">that</span> <span m="48213">are</span> <span m="48607">in</span>
  <span m="49001">the</span> <span m="49395">pipeline.</span></p><p><span m="49789">Since</span>
  <span m="50000">there</span> <span m="50212">are</span> <span m="50424">multiple</span>
  <span m="50636">instructions</span> <span m="50848">in</span> <span m="51060">the</span>
  <span m="51272">pipeline,</span> <span m="51484">we</span> <span m="51695">have</span>
  <span m="51907">a</span> <span m="52119">bit</span> <span m="52331">of</span> <span
  m="52543">sorting</span> <span m="52755">out</span> <span m="52967">to</span> <span
  m="53179">do.</span></p><p><span m="54179">When,</span> <span m="54590">during</span>
  <span m="55002">pipelined</span> <span m="55413">execution,</span> <span m="55825">do</span>
  <span m="56236">we</span> <span m="56648">determine</span> <span m="57059">that</span>
  <span m="57471">an</span> <span m="57882">instruction</span> <span m="58294">will</span>
  <span m="58705">cause</span> <span m="59117">an</span> <span m="59528">exception?</span></p><p><span
  m="59940">An</span> <span m="60334">obvious</span> <span m="60729">example</span>
  <span m="61124">is</span> <span m="61518">detecting</span> <span m="61913">an</span>
  <span m="62308">illegal</span> <span m="62702">opcode</span> <span m="63097">when</span>
  <span m="63492">we</span> <span m="63886">decode</span> <span m="64281">the</span>
  <span m="64676">instruction</span> <span m="65070">in</span> <span m="65465">the</span>
  <span m="65860">RF</span> <span m="66730">stage.</span></p><p><span m="67600">But</span>
  <span m="67968">we</span> <span m="68336">can</span> <span m="68704">also</span>
  <span m="69072">generate</span> <span m="69440">exceptions</span> <span m="69808">in</span>
  <span m="70176">other</span> <span m="70544">pipeline</span> <span m="70912">stages.</span></p><p><span
  m="71280">For</span> <span m="71565">example,</span> <span m="71851">the</span>
  <span m="72137">ALU</span> <span m="72423">stage</span> <span m="72709">can</span>
  <span m="72995">generate</span> <span m="73281">an</span> <span m="73567">exception</span>
  <span m="73852">if</span> <span m="74138">the</span> <span m="74424">second</span>
  <span m="74710">operand</span> <span m="74996">of</span> <span m="75282">a</span>
  <span m="75568">DIV</span> <span m="75854">instruction</span> <span m="76140">is</span>
  <span m="76960">0.</span></p><p><span m="77780">Or</span> <span m="78092">the</span>
  <span m="78405">MEM</span> <span m="78718">stage</span> <span m="79031">may</span>
  <span m="79344">detect</span> <span m="79657">that</span> <span m="79970">the</span>
  <span m="80283">instruction</span> <span m="80596">is</span> <span m="80909">attempting</span>
  <span m="81222">to</span> <span m="81535">access</span> <span m="81848">memory</span>
  <span m="82161">with</span> <span m="82474">an</span> <span m="82787">illegal</span>
  <span m="83100">address.</span></p><p><span m="84299">Similarly</span> <span m="84636">the</span>
  <span m="84973">IF</span> <span m="85310">stage</span> <span m="85647">can</span>
  <span m="85985">generate</span> <span m="86322">a</span> <span m="86659">memory</span>
  <span m="86996">exception</span> <span m="87333">when</span> <span m="87671">fetching</span>
  <span m="88008">the</span> <span m="88345">next</span> <span m="88682">instruction.</span></p><p><span
  m="89020">In</span> <span m="89330">each</span> <span m="89641">case,</span> <span
  m="89951">instructions</span> <span m="90262">that</span> <span m="90573">follow</span>
  <span m="90883">the</span> <span m="91194">one</span> <span m="91505">that</span>
  <span m="91815">caused</span> <span m="92126">the</span> <span m="92437">exception</span>
  <span m="92747">may</span> <span m="93058">already</span> <span m="93369">be</span>
  <span m="93740">in</span> <span m="94111">the</span> <span m="94482">pipeline</span>
  <span m="94853">and</span> <span m="95224">will</span> <span m="95595">need</span>
  <span m="95966">to</span> <span m="96337">be</span> <span m="96708">annulled.</span></p><p><span
  m="97079">The</span> <span m="97435">good</span> <span m="97791">news</span> <span
  m="98147">is</span> <span m="98504">that</span> <span m="98860">since</span> <span
  m="99216">register</span> <span m="99573">values</span> <span m="99929">are</span>
  <span m="100285">only</span> <span m="100642">updated</span> <span m="100998">in</span>
  <span m="101354">the</span> <span m="101711">WB</span> <span m="102067">stage,</span>
  <span m="102423">annulling</span> <span m="102780">an</span> <span m="103062">instruction</span>
  <span m="103344">only</span> <span m="103626">requires</span> <span m="103908">replacing</span>
  <span m="104191">it</span> <span m="104473">with</span> <span m="104755">a</span>
  <span m="105037">NOP.</span></p><p><span m="105320">We</span> <span m="105740">won't</span>
  <span m="106161">have</span> <span m="106582">to</span> <span m="107002">restore</span>
  <span m="107423">any</span> <span m="107844">changed</span> <span m="108264">values</span>
  <span m="108685">in</span> <span m="109106">the</span> <span m="109526">register</span>
  <span m="109947">file</span> <span m="110368">or</span> <span m="110788">main</span>
  <span m="111209">memory.</span></p><p><span m="111630">Here's</span> <span m="112063">our</span>
  <span m="112496">plan.</span></p><p><span m="112929">If</span> <span m="113283">an</span>
  <span m="113638">instruction</span> <span m="113993">causes</span> <span m="114347">an</span>
  <span m="114702">exception</span> <span m="115057">in</span> <span m="115412">stage</span>
  <span m="115766">i,</span> <span m="116121">replace</span> <span m="116476">that</span>
  <span m="116831">instruction</span> <span m="117185">with</span> <span m="117540">this</span>
  <span m="117895">BNE</span> <span m="118250">instruction,</span> <span m="118785">whose</span>
  <span m="119321">only</span> <span m="119856">side</span> <span m="120392">effect</span>
  <span m="120928">is</span> <span m="121463">writing</span> <span m="121999">the</span>
  <span m="122535">PC+4</span> <span m="123070">value</span> <span m="123606">into</span>
  <span m="124142">the</span> <span m="124677">XP</span> <span m="125213">register.</span></p><p><span
  m="125749">Then</span> <span m="126142">flush</span> <span m="126536">the</span>
  <span m="126930">pipeline</span> <span m="127323">by</span> <span m="127717">annulling</span>
  <span m="128111">instructions</span> <span m="128505">in</span> <span m="128898">earlier</span>
  <span m="129292">pipeline</span> <span m="129686">stages.</span></p><p><span m="130080">And,</span>
  <span m="130573">finally,</span> <span m="131067">load</span> <span m="131561">the</span>
  <span m="132055">program</span> <span m="132549">counter</span> <span m="133043">with</span>
  <span m="133536">the</span> <span m="134030">address</span> <span m="134524">of</span>
  <span m="135018">the</span> <span m="135512">exception</span> <span m="136006">handler.</span></p><p><span
  m="136500">In</span> <span m="136826">this</span> <span m="137152">example,</span>
  <span m="137478">assume</span> <span m="137805">that</span> <span m="138131">LD</span>
  <span m="138457">will</span> <span m="138783">generate</span> <span m="139110">a</span>
  <span m="139436">memory</span> <span m="139762">exception</span> <span m="140088">in</span>
  <span m="140415">the</span> <span m="140741">MEM</span> <span m="141067">stage,</span>
  <span m="141393">which</span> <span m="141720">occurs</span> <span m="142312">in</span>
  <span m="142905">cycle</span> <span m="143497">4.</span></p><p><span m="144090">The</span>
  <span m="144400">arrows</span> <span m="144710">show</span> <span m="145020">how</span>
  <span m="145330">the</span> <span m="145640">instructions</span> <span m="145950">in</span>
  <span m="146260">the</span> <span m="146570">pipeline</span> <span m="146880">are</span>
  <span m="147190">rewritten</span> <span m="147500">for</span> <span m="147810">cycle</span>
  <span m="148120">5,</span> <span m="148430">at</span> <span m="148740">which</span>
  <span m="149050">point</span> <span m="149500">the</span> <span m="149951">IF</span>
  <span m="150402">stage</span> <span m="150852">is</span> <span m="151303">working</span>
  <span m="151754">on</span> <span m="152204">fetching</span> <span m="152655">the</span>
  <span m="153106">first</span> <span m="153556">instruction</span> <span m="154007">in</span>
  <span m="154458">the</span> <span m="154908">exception</span> <span m="155359">handler.</span></p><p><span
  m="155810">Here</span> <span m="156170">are</span> <span m="156530">the</span> <span
  m="156890">changes</span> <span m="157250">required</span> <span m="157610">to</span>
  <span m="157970">the</span> <span m="158330">execution</span> <span m="158690">pipeline.</span></p><p><span
  m="159050">We</span> <span m="159373">modify</span> <span m="159696">the</span>
  <span m="160019">muxes</span> <span m="160342">in</span> <span m="160665">the</span>
  <span m="160988">instruction</span> <span m="161311">path</span> <span m="161635">so</span>
  <span m="161958">that</span> <span m="162281">they</span> <span m="162604">can</span>
  <span m="162927">replace</span> <span m="163250">an</span> <span m="163573">actual</span>
  <span m="163896">instruction</span> <span m="164220">with</span> <span m="164586">either</span>
  <span m="164953">NOP</span> <span m="165320">if</span> <span m="165687">the</span>
  <span m="166054">instruction</span> <span m="166421">is</span> <span m="166788">to</span>
  <span m="167155">be</span> <span m="167521">annulled,</span> <span m="167888">or</span>
  <span m="168255">BNE</span> <span m="168622">if</span> <span m="168989">the</span>
  <span m="169356">instruction</span> <span m="169723">caused</span> <span m="170090">the</span>
  <span m="170895">exception.</span></p><p><span m="171700">Since</span> <span m="172000">the</span>
  <span m="172300">pipeline</span> <span m="172600">is</span> <span m="172900">executing</span>
  <span m="173200">multiple</span> <span m="173500">instructions</span> <span m="173800">at</span>
  <span m="174100">the</span> <span m="174400">same</span> <span m="174700">time,</span>
  <span m="175000">we</span> <span m="175300">have</span> <span m="175600">to</span>
  <span m="175900">worry</span> <span m="176200">about</span> <span m="176500">what</span>
  <span m="176800">happens</span> <span m="177391">if</span> <span m="177982">multiple</span>
  <span m="178573">exceptions</span> <span m="179165">are</span> <span m="179756">detected</span>
  <span m="180347">during</span> <span m="180938">execution.</span></p><p><span m="181530">In</span>
  <span m="181861">this</span> <span m="182193">example</span> <span m="182525">assume</span>
  <span m="182857">that</span> <span m="183188">LD</span> <span m="183520">will</span>
  <span m="183852">cause</span> <span m="184184">a</span> <span m="184515">memory</span>
  <span m="184847">exception</span> <span m="185179">in</span> <span m="185511">the</span>
  <span m="185842">MEM</span> <span m="186174">stage</span> <span m="186506">and</span>
  <span m="186838">note</span> <span m="187170">that</span> <span m="187659">it</span>
  <span m="188148">is</span> <span m="188637">followed</span> <span m="189126">by</span>
  <span m="189615">an</span> <span m="190104">instruction</span> <span m="190593">with</span>
  <span m="191082">an</span> <span m="191571">illegal</span> <span m="192060">opcode.</span></p><p><span
  m="192550">Looking</span> <span m="192973">at</span> <span m="193396">the</span>
  <span m="193820">pipeline</span> <span m="194243">diagram,</span> <span m="194666">the</span>
  <span m="195090">invalid</span> <span m="195513">opcode</span> <span m="195936">is</span>
  <span m="196360">detected</span> <span m="196783">in</span> <span m="197206">the</span>
  <span m="197630">RF</span> <span m="198053">stage</span> <span m="198476">during</span>
  <span m="198900">cycle</span> <span m="199409">3,</span> <span m="199918">causing</span>
  <span m="200427">the</span> <span m="200936">illegal</span> <span m="201446">instruction</span>
  <span m="201955">exception</span> <span m="202464">process</span> <span m="202973">to</span>
  <span m="203483">begin</span> <span m="203992">in</span> <span m="204501">cycle</span>
  <span m="205010">4.</span></p><p><span m="205520">But</span> <span m="205898">during</span>
  <span m="206276">that</span> <span m="206654">cycle,</span> <span m="207032">the</span>
  <span m="207410">MEM</span> <span m="207788">stage</span> <span m="208166">detects</span>
  <span m="208545">the</span> <span m="208923">illegal</span> <span m="209301">memory</span>
  <span m="209679">access</span> <span m="210057">from</span> <span m="210435">the</span>
  <span m="210813">LD</span> <span m="211191">instruction</span> <span m="211570">and</span>
  <span m="212067">so</span> <span m="212565">causes</span> <span m="213062">the</span>
  <span m="213560">memory</span> <span m="214057">exception</span> <span m="214555">process</span>
  <span m="215052">to</span> <span m="215550">begin</span> <span m="216047">in</span>
  <span m="216545">cycle</span> <span m="217042">5.</span></p><p><span m="217540">Note</span>
  <span m="217920">that</span> <span m="218301">the</span> <span m="218682">exception</span>
  <span m="219062">caused</span> <span m="219443">by</span> <span m="219824">the</span>
  <span m="220205">earlier</span> <span m="220585">instruction</span> <span m="220966">(LD)</span>
  <span m="221347">overrides</span> <span m="221727">the</span> <span m="222108">exception</span>
  <span m="222489">caused</span> <span m="222870">by</span> <span m="223296">the</span>
  <span m="223722">later</span> <span m="224149">illegal</span> <span m="224575">opcode</span>
  <span m="225002">even</span> <span m="225428">though</span> <span m="225855">the</span>
  <span m="226281">illegal</span> <span m="226707">opcode</span> <span m="227134">exception</span>
  <span m="227560">was</span> <span m="227987">detected</span> <span m="228413">first.</span></p><p><span
  m="228840">.348</span> <span m="229203">That's</span> <span m="229566">the</span>
  <span m="229930">correct</span> <span m="230293">behavior</span> <span m="230656">since</span>
  <span m="231020">once</span> <span m="231383">the</span> <span m="231746">execution</span>
  <span m="232110">of</span> <span m="232473">LD</span> <span m="232836">is</span>
  <span m="233200">abandoned,</span> <span m="233563">the</span> <span m="233926">pipeline</span>
  <span m="234290">should</span> <span m="234714">behave</span> <span m="235139">as</span>
  <span m="235564">if</span> <span m="235988">none</span> <span m="236413">of</span>
  <span m="236838">the</span> <span m="237262">instructions</span> <span m="237687">that</span>
  <span m="238112">come</span> <span m="238536">after</span> <span m="238961">the</span>
  <span m="239386">LD</span> <span m="239810">were</span> <span m="240235">executed.</span></p><p><span
  m="240660">If</span> <span m="240985">multiple</span> <span m="241310">exceptions</span>
  <span m="241635">are</span> <span m="241960">detected</span> <span m="242285">in</span>
  <span m="242610">the</span> <span m="242935">*same*</span> <span m="243260">cycle,</span>
  <span m="243585">the</span> <span m="243910">exception</span> <span m="244235">from</span>
  <span m="244560">the</span> <span m="244885">instruction</span> <span m="245210">furthest</span>
  <span m="245880">down</span> <span m="246550">the</span> <span m="247220">pipeline</span>
  <span m="247890">should</span> <span m="248560">be</span> <span m="249230">given</span>
  <span m="249900">precedence.</span></p><p><span m="250570">External</span> <span
  m="250875">interrupts</span> <span m="251180">also</span> <span m="251486">behave</span>
  <span m="251791">as</span> <span m="252096">implicit</span> <span m="252402">branches,</span>
  <span m="252707">but</span> <span m="253012">it</span> <span m="253318">turns</span>
  <span m="253623">out</span> <span m="253928">they</span> <span m="254234">are</span>
  <span m="254539">a</span> <span m="254844">bit</span> <span m="255150">easier</span>
  <span m="255651">to</span> <span m="256153">handle</span> <span m="256655">in</span>
  <span m="257156">our</span> <span m="257658">pipeline.</span></p><p><span m="258160">We'll</span>
  <span m="258535">treat</span> <span m="258910">external</span> <span m="259286">interrupts</span>
  <span m="259661">as</span> <span m="260036">if</span> <span m="260412">they</span>
  <span m="260787">were</span> <span m="261162">an</span> <span m="261538">exception</span>
  <span m="261913">that</span> <span m="262288">affected</span> <span m="262664">the</span>
  <span m="263039">IF</span> <span m="263414">stage.</span></p><p><span m="263790">Let's</span>
  <span m="264194">assume</span> <span m="264598">the</span> <span m="265003">external</span>
  <span m="265407">interrupt</span> <span m="265812">occurs</span> <span m="266216">in</span>
  <span m="266621">cycle</span> <span m="267025">2.</span></p><p><span m="267430">This</span>
  <span m="267731">means</span> <span m="268033">that</span> <span m="268335">the</span>
  <span m="268637">SUB</span> <span m="268938">instruction</span> <span m="269240">will</span>
  <span m="269542">be</span> <span m="269844">replaced</span> <span m="270145">by</span>
  <span m="270447">our</span> <span m="270749">magic</span> <span m="271051">BNE</span>
  <span m="271352">to</span> <span m="271654">capture</span> <span m="271956">the</span>
  <span m="272258">PC+4</span> <span m="272560">value</span> <span m="272947">and</span>
  <span m="273334">we'll</span> <span m="273722">force</span> <span m="274109">the</span>
  <span m="274496">next</span> <span m="274884">PC</span> <span m="275271">to</span>
  <span m="275658">be</span> <span m="276046">the</span> <span m="276433">address</span>
  <span m="276820">of</span> <span m="277208">the</span> <span m="277595">interrupt</span>
  <span m="277982">handler.</span></p><p><span m="278370">After</span> <span m="278690">the</span>
  <span m="279011">interrupt</span> <span m="279332">handler</span> <span m="279653">completes,</span>
  <span m="279973">we'll</span> <span m="280294">want</span> <span m="280615">to</span>
  <span m="280936">resume</span> <span m="281256">execution</span> <span m="281577">of</span>
  <span m="281898">the</span> <span m="282219">interrupted</span> <span m="282540">program</span>
  <span m="282856">at</span> <span m="283172">the</span> <span m="283489">SUB</span>
  <span m="283805">instruction,</span> <span m="284121">so</span> <span m="284438">we'll</span>
  <span m="284754">code</span> <span m="285071">the</span> <span m="285387">handler</span>
  <span m="285703">to</span> <span m="286020">correct</span> <span m="286336">the</span>
  <span m="286652">value</span> <span m="286969">saved</span> <span m="287285">in</span>
  <span m="287602">the</span> <span m="288086">XP</span> <span m="288570">register</span>
  <span m="289055">so</span> <span m="289539">that</span> <span m="290023">it</span>
  <span m="290508">points</span> <span m="290992">to</span> <span m="291476">the</span>
  <span m="291961">SUB</span> <span m="292445">instruction.</span></p><p><span m="292930">This</span>
  <span m="293286">is</span> <span m="293642">all</span> <span m="293998">shown</span>
  <span m="294355">in</span> <span m="294711">the</span> <span m="295067">pipeline</span>
  <span m="295423">diagram.</span></p><p><span m="295780">Note</span> <span m="296085">that</span>
  <span m="296391">the</span> <span m="296697">ADD,</span> <span m="297003">LD,</span>
  <span m="297309">and</span> <span m="297615">other</span> <span m="297921">instructions</span>
  <span m="298227">that</span> <span m="298532">came</span> <span m="298838">before</span>
  <span m="299144">SUB</span> <span m="299450">in</span> <span m="299756">the</span>
  <span m="300062">program</span> <span m="300368">are</span> <span m="300674">unaffected</span>
  <span m="300980">by</span> <span m="301866">the</span> <span m="302752">interrupt.</span></p><p><span
  m="303639">We</span> <span m="303981">can</span> <span m="304324">use</span> <span
  m="304667">the</span> <span m="305010">existing</span> <span m="305353">instruction-path</span>
  <span m="305696">muxes</span> <span m="306039">to</span> <span m="306382">deal</span>
  <span m="306725">with</span> <span m="307068">interrupts,</span> <span m="307411">since</span>
  <span m="307754">we're</span> <span m="308097">treating</span> <span m="308440">them</span>
  <span m="309132">as</span> <span m="309825">IF-stage</span> <span m="310517">exceptions.</span></p><p><span
  m="311210">We</span> <span m="311556">simply</span> <span m="311902">have</span>
  <span m="312248">to</span> <span m="312595">adjust</span> <span m="312941">the</span>
  <span m="313287">logic</span> <span m="313633">for</span> <span m="313980">IRSrc_IF</span>
  <span m="314326">to</span> <span m="314672">also</span> <span m="315018">make</span>
  <span m="315365">it</span> <span m="315711">1</span> <span m="316057">when</span>
  <span m="316403">an</span> <span m="316750">interrupt</span> <span m="317096">is</span>
  <span m="317442">requested.</span></p>
type: course
uid: 1b5df9fc3987868d1b050cee018b6744

---
None