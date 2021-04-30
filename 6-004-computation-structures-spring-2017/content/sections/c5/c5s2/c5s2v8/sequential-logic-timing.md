---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: LN0k-boDvOk
  parent_uid: f6b9a641aaf3ee9a913e586949a3d637
  title: Video-YouTube-Stream
  type: Video
  uid: b2c3fd6c27c7f4215bdb16b6adbc941b
- id: 3Play-3Play YouTube id-Stream
  media_location: LN0k-boDvOk
  parent_uid: f6b9a641aaf3ee9a913e586949a3d637
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 9f472ce593eae0d772bdb9bd17df6b87
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/LN0k-boDvOk/default.jpg
  parent_uid: f6b9a641aaf3ee9a913e586949a3d637
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e3bc21c80523ff20e6738eb58a0be721
- id: LN0k-boDvOk.srt
  parent_uid: f6b9a641aaf3ee9a913e586949a3d637
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c5/c5s2/c5s2v8/sequential-logic-timing/LN0k-boDvOk.srt
  title: 3play caption file
  type: null
  uid: 520af8c077a84d3560a904bc176caf44
- id: LN0k-boDvOk.pdf
  parent_uid: f6b9a641aaf3ee9a913e586949a3d637
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c5/c5s2/c5s2v8/sequential-logic-timing/LN0k-boDvOk.pdf
  title: 3play pdf file
  type: null
  uid: 7c25e0e9b7bc2fede017c642df40680c
- id: Caption-3Play YouTube id-SRT
  parent_uid: f6b9a641aaf3ee9a913e586949a3d637
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: f8ecba103615b5b58f31d85731dc3ad8
- id: Transcript-3Play YouTube id-PDF
  parent_uid: f6b9a641aaf3ee9a913e586949a3d637
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 625fd27daf2c7a61e8661ac121fdbf67
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_05-02-08-01_300k.mp4
  parent_uid: f6b9a641aaf3ee9a913e586949a3d637
  title: Video-Internet Archive-MP4
  type: Video
  uid: 4ce8ea78d168ff4aeaec277a2fa4b329
inline_embed_id: 89816544sequentiallogictiming37045307
layout: video
order_index: null
parent_uid: f9e5575658c645845b30a029dd2e3a6c
related_resources_text: ''
short_url: sequential-logic-timing
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c5/c5s2/c5s2v8/sequential-logic-timing
template_type: Embed
title: 'Worked Example: Sequential Logic Timing'
transcript: <p><span m="940">PROFESSOR In</span> <span m="1120">this</span> <span
  m="1390">problem,</span> <span m="2420">we</span> <span m="2470">are</span> <span
  m="2530">going</span> <span m="2860">to</span> <span m="2980">take</span> <span
  m="3280">a</span> <span m="3340">look</span> <span m="3670">at</span> <span m="3820">the</span>
  <span m="3940">timing</span> <span m="4420">constraints</span> <span m="5170">associated</span>
  <span m="5950">with</span> <span m="6160">sequential</span> <span m="6880">logic</span>
  <span m="7360">circuits.</span> <span m="8560">We</span> <span m="8680">are</span>
  <span m="8770">given</span> <span m="9130">a</span> <span m="9190">generic</span>
  <span m="9820">state</span> <span m="10120">machine</span> <span m="10510">diagram,</span>
  <span m="11260">which</span> <span m="11500">has</span> <span m="11770">two</span>
  <span m="12070">state</span> <span m="12460">bits.</span> <span m="13390">We</span>
  <span m="13510">are</span> <span m="13630">also</span> <span m="14050">given</span>
  <span m="14410">the</span> <span m="14530">timing</span> <span m="15010">parameters</span>
  <span m="15700">for</span> <span m="15850">the</span> <span m="15940">combinational</span>
  <span m="16750">logic</span> <span m="17380">and</span> <span m="17560">the</span>
  <span m="17650">state</span> <span m="18040">register.</span> <span m="19360">Using</span>
  <span m="19750">this</span> <span m="19930">data</span> <span m="20710">we</span>
  <span m="20860">want</span> <span m="21100">to</span> <span m="21190">determine</span>
  <span m="21730">the</span> <span m="21850">largest</span> <span m="22300">value</span>
  <span m="22690">for</span> <span m="22870">the</span> <span m="22990">register's</span>
  <span m="23650">whole</span> <span m="23950">time</span> <span m="24760">that</span>
  <span m="24910">allows</span> <span m="25360">the</span> <span m="25450">necessary</span>
  <span m="26140">timing</span> <span m="26590">specifications</span> <span m="27580">to</span>
  <span m="27700">be</span> <span m="27850">met.</span></p><p><span m="29280">In</span>
  <span m="29430">order</span> <span m="29700">to</span> <span m="29820">satisfy</span>
  <span m="30480">the</span> <span m="30600">whole</span> <span m="30930">time</span>
  <span m="31230">of</span> <span m="31350">the</span> <span m="31440">register,</span>
  <span m="32520">the</span> <span m="32670">input</span> <span m="33120">to</span>
  <span m="33270">the</span> <span m="33390">register</span> <span m="34020">must</span>
  <span m="34350">remain</span> <span m="34800">stable</span> <span m="35850">until</span>
  <span m="36240">tHOLD</span> <span m="37230">after</span> <span m="37650">the</span>
  <span m="37770">clock</span> <span m="38220">edge.</span> <span m="39510">The</span>
  <span m="39600">fastest</span> <span m="40200">that</span> <span m="40380">a</span>
  <span m="40440">new</span> <span m="40680">change</span> <span m="41130">can</span>
  <span m="41310">propagate</span> <span m="41970">to</span> <span m="42090">the</span>
  <span m="42270">input</span> <span m="42660">of</span> <span m="42780">the</span>
  <span m="42900">register</span> <span m="43950">is</span> <span m="44130">found</span>
  <span m="44460">by</span> <span m="44640">taking</span> <span m="45060">the</span>
  <span m="45150">sum</span> <span m="45510">of</span> <span m="45600">the</span>
  <span m="45690">contamination</span> <span m="46650">delays</span> <span m="47490">along</span>
  <span m="47790">the</span> <span m="47880">shortest</span> <span m="48420">path</span>
  <span m="48720">to</span> <span m="48840">that</span> <span m="49080">input.</span>
  <span m="50490">That</span> <span m="50730">is</span> <span m="51060">[? tCD ?]</span>
  <span m="51750">of</span> <span m="51840">the</span> <span m="51900">register</span>
  <span m="52980">plus</span> <span m="53250">tCD</span> <span m="53850">of</span>
  <span m="53970">the</span> <span m="54060">logic.</span> <span m="55120">So</span>
  <span m="55980">tHOLD</span> <span m="56790">must</span> <span m="57090">be</span>
  <span m="57210">less</span> <span m="57510">than</span> <span m="57690">or</span>
  <span m="57810">equal</span> <span m="58200">to</span> <span m="58970">tCD</span>
  <span m="59520">of</span> <span m="59640">the</span> <span m="59760">register</span>
  <span m="60570">plus</span> <span m="60990">tCD</span> <span m="61560">of</span>
  <span m="61650">the</span> <span m="61740">logic.</span></p><p><span m="63000">Plugging</span>
  <span m="63450">in</span> <span m="63570">the</span> <span m="63690">given</span>
  <span m="63990">contamination</span> <span m="64830">delays,</span> <span m="65820">we</span>
  <span m="65940">find</span> <span m="66300">that</span> <span m="66480">tHOLD</span>
  <span m="67230">must</span> <span m="67500">be</span> <span m="67620">less</span>
  <span m="67920">than</span> <span m="68070">or</span> <span m="68160">equal</span>
  <span m="68460">to</span> <span m="69150">0.1</span> <span m="70380">plus</span>
  <span m="70680">0.2,</span> <span m="72210">which</span> <span m="72450">equals</span>
  <span m="72960">0.3</span> <span m="74220">nanoseconds.</span> <span m="76890">What</span>
  <span m="77040">is</span> <span m="77160">the</span> <span m="77250">smallest</span>
  <span m="77790">value</span> <span m="78210">for</span> <span m="78390">the</span>
  <span m="78480">period</span> <span m="79020">of</span> <span m="79140">the</span>
  <span m="79230">clock</span> <span m="79680">that</span> <span m="79830">will</span>
  <span m="79980">meet</span> <span m="80250">the</span> <span m="80370">timing</span>
  <span m="80820">specifications?</span> <span m="82710">The</span> <span m="83100">clock</span>
  <span m="83460">period</span> <span m="83970">must</span> <span m="84210">be</span>
  <span m="84330">long</span> <span m="84600">enough</span> <span m="84930">for</span>
  <span m="85110">the</span> <span m="85260">data</span> <span m="85710">to</span>
  <span m="85860">pass</span> <span m="86220">through</span> <span m="86490">the</span>
  <span m="86610">entire</span> <span m="87060">circuit</span> <span m="87960">and</span>
  <span m="88080">be</span> <span m="88230">ready</span> <span m="88540">and</span>
  <span m="88640">stable</span> <span m="89250">for</span> <span m="89460">tSETUP</span>
  <span m="90360">before</span> <span m="90900">the</span> <span m="91020">next</span>
  <span m="91320">period</span> <span m="91740">begins.</span></p><p><span m="93210">The</span>
  <span m="93330">data</span> <span m="93720">in</span> <span m="93810">this</span>
  <span m="93990">circuit</span> <span m="94650">must</span> <span m="94890">propagate</span>
  <span m="95520">through</span> <span m="95730">the</span> <span m="95850">register</span>
  <span m="96660">and</span> <span m="96840">the</span> <span m="96930">combinational</span>
  <span m="97680">logic.</span> <span m="99040">So</span> <span m="99090">the</span>
  <span m="99210">constraint</span> <span m="99870">on</span> <span m="99990">the</span>
  <span m="100050">clock</span> <span m="100440">period</span> <span m="101430">is</span>
  <span m="101610">that</span> <span m="101820">tCLOCK</span> <span m="102810">has</span>
  <span m="103050">to</span> <span m="103140">be</span> <span m="103290">greater</span>
  <span m="103710">than</span> <span m="103890">or</span> <span m="104010">equal</span>
  <span m="104340">to</span> <span m="105210">tPD</span> <span m="105930">of</span>
  <span m="106050">the</span> <span m="106170">register</span> <span m="106980">plus</span>
  <span m="107310">tPD</span> <span m="108780">of</span> <span m="108900">the</span>
  <span m="109020">logic</span> <span m="109890">plus</span> <span m="110820">tSETUP</span>
  <span m="111720">of</span> <span m="111840">the</span> <span m="111960">register.</span>
  <span m="113400">Plugging</span> <span m="113940">in</span> <span m="114090">the</span>
  <span m="114210">given</span> <span m="114540">timing</span> <span m="114990">parameters,</span>
  <span m="116100">we</span> <span m="116220">find</span> <span m="116610">that</span>
  <span m="117030">tCLOCK</span> <span m="117900">must</span> <span m="118170">be</span>
  <span m="118320">greater</span> <span m="118710">than</span> <span m="118890">or</span>
  <span m="119010">equal</span> <span m="119310">to</span> <span m="120090">5</span>
  <span m="120660">plus</span> <span m="121020">3</span> <span m="121590">plus</span>
  <span m="122010">2,</span> <span m="122430">which</span> <span m="122700">equals</span>
  <span m="123120">10</span> <span m="123510">nanoseconds.</span></p><p><span m="126180">Next,</span>
  <span m="126900">we</span> <span m="127080">want</span> <span m="127320">to</span>
  <span m="127410">determine</span> <span m="128070">what</span> <span m="128310">are</span>
  <span m="128400">the</span> <span m="128520">smallest</span> <span m="129060">setup</span>
  <span m="129509">and</span> <span m="129600">whole</span> <span m="129840">time</span>
  <span m="130110">specifications</span> <span m="131340">on</span> <span m="131490">the</span>
  <span m="131610">input</span> <span m="132120">in</span> <span m="132960">with</span>
  <span m="133140">respect</span> <span m="133680">to</span> <span m="133830">the</span>
  <span m="134010">active</span> <span m="134580">edge</span> <span m="134850">of</span>
  <span m="134970">the</span> <span m="135060">clock</span> <span m="136170">so</span>
  <span m="136350">that</span> <span m="136530">we</span> <span m="136680">can</span>
  <span m="136860">ensure</span> <span m="137430">that</span> <span m="137610">the</span>
  <span m="137700">necessary</span> <span m="138390">timing</span> <span m="138840">specifications</span>
  <span m="139980">are</span> <span m="140160">met.</span> <span m="141760">The</span>
  <span m="141940">IN input</span> <span m="142950">must</span> <span m="143160">be</span>
  <span m="143280">stable</span> <span m="143760">and</span> <span m="143880">valid</span>
  <span m="144300">long</span> <span m="144600">enough</span> <span m="144930">before</span>
  <span m="145320">the</span> <span m="145440">rising</span> <span m="145860">clock</span>
  <span m="146280">edge</span> <span m="146580">for</span> <span m="146700">it</span>
  <span m="146760">to</span> <span m="146880">propagate</span> <span m="147570">through</span>
  <span m="147840">the</span> <span m="147960">combinational</span> <span m="148680">logic</span>
  <span m="149640">and</span> <span m="149880">arrive</span> <span m="150240">at</span>
  <span m="150330">the</span> <span m="150420">register</span> <span m="151230">in</span>
  <span m="151350">time</span> <span m="151650">for</span> <span m="151830">it</span>
  <span m="151890">to</span> <span m="152040">setup.</span> <span m="153360">So</span>
  <span m="153570">tSETUP</span> <span m="154440">of</span> <span m="154680">IN</span>
  <span m="155580">is</span> <span m="155820">greater</span> <span m="156210">than</span>
  <span m="156390">or</span> <span m="156480">equal</span> <span m="156840">to</span>
  <span m="157620">tPROPAGATION</span> <span m="158730">DELAY</span> <span m="159120">of</span>
  <span m="159210">the</span> <span m="159330">LOGIC</span> <span m="160230">plus</span>
  <span m="160740">tSETUP</span> <span m="161430">of</span> <span m="161520">the</span>
  <span m="161640">register.</span> <span m="162900">That</span> <span m="163140">equals</span>
  <span m="163830">3</span> <span m="164400">plus</span> <span m="164820">2,</span>
  <span m="165660">which</span> <span m="165900">equals</span> <span m="166260">5</span>
  <span m="166650">nanoseconds.</span></p><p><span m="168600">Once</span> <span m="168870">the</span>
  <span m="169000">IN input</span> <span m="169530">becomes</span> <span m="169980">invalid,</span>
  <span m="171000">the</span> <span m="171120">input</span> <span m="171460">to</span>
  <span m="171560">the</span> <span m="171660">register</span> <span m="172200">will</span>
  <span m="172350">become</span> <span m="172770">invalid</span> <span m="173370">after</span>
  <span m="173730">the</span> <span m="173880">contamination</span> <span m="174720">delay</span>
  <span m="175050">of</span> <span m="175140">the</span> <span m="175260">logic.</span>
  <span m="176610">IN</span> <span m="176880">must</span> <span m="177150">stay</span>
  <span m="177390">valid</span> <span m="177900">long</span> <span m="178230">enough</span>
  <span m="178530">to</span> <span m="178680">ensure</span> <span m="179010">that</span>
  <span m="179190">the</span> <span m="179340">input</span> <span m="179670">to</span>
  <span m="179820">the</span> <span m="179910">register</span> <span m="180570">does</span>
  <span m="180780">not</span> <span m="181020">become</span> <span m="181380">invalid</span>
  <span m="181920">before</span> <span m="182310">the</span> <span m="182430">registers</span>
  <span m="183030">hold</span> <span m="183300">time.</span> <span m="184560">So</span>
  <span m="185040">tHOLD</span> <span m="185760">of</span> <span m="185970">IN</span>
  <span m="186780">plus</span> <span m="187200">tCD</span> <span m="187740">of</span>
  <span m="187860">the</span> <span m="187950">LOGIC</span> <span m="189110">are</span>
  <span m="189180">greater</span> <span m="189570">than</span> <span m="189750">or</span>
  <span m="189870">equal</span> <span m="190230">to</span> <span m="190950">tHOLD</span>
  <span m="191880">of</span> <span m="192030">the</span> <span m="192120">register.</span>
  <span m="193170">This</span> <span m="193350">can</span> <span m="193530">be</span>
  <span m="193650">rewritten</span> <span m="194280">as</span> <span m="195300">tHOLD</span>
  <span m="195930">of</span> <span m="196140">IN</span> <span m="196620">must</span>
  <span m="196860">be</span> <span m="197010">greater</span> <span m="197370">than</span>
  <span m="197550">or</span> <span m="197670">equal</span> <span m="197970">to</span>
  <span m="198600">tHOLD</span> <span m="199230">of</span> <span m="199320">the</span>
  <span m="199440">register</span> <span m="200520">minus</span> <span m="201180">tCD</span>
  <span m="201900">of</span> <span m="202020">the</span> <span m="202110">LOGIC,</span>
  <span m="202980">which</span> <span m="203220">equals</span> <span m="203850">0.3</span>
  <span m="205470">minus</span> <span m="206070">0.2.</span> <span m="207660">And</span>
  <span m="207780">that</span> <span m="208020">equals</span> <span m="208290">0.1</span>
  <span m="209580">nanoseconds.</span></p>
type: course
uid: f6b9a641aaf3ee9a913e586949a3d637

---
None