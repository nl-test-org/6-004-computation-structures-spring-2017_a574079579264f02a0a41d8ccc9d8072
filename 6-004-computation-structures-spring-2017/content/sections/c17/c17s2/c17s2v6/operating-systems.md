---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: jsJ0nR38zvo
  parent_uid: 79f7230eace3d57ab4d7cee4dababbc1
  title: Video-YouTube-Stream
  type: Video
  uid: 62b62268755e0f04901c6068206b7844
- id: 3Play-3Play YouTube id-Stream
  media_location: jsJ0nR38zvo
  parent_uid: 79f7230eace3d57ab4d7cee4dababbc1
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: d590a173729ccf3178f8f850f188d375
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/jsJ0nR38zvo/default.jpg
  parent_uid: 79f7230eace3d57ab4d7cee4dababbc1
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e6a3097e7fd47c5dbf764da37f166ba0
- id: jsJ0nR38zvo.srt
  parent_uid: 79f7230eace3d57ab4d7cee4dababbc1
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v6/operating-systems/jsJ0nR38zvo.srt
  title: 3play caption file
  type: null
  uid: 120796b61673117852eccbbbdd6cf282
- id: jsJ0nR38zvo.pdf
  parent_uid: 79f7230eace3d57ab4d7cee4dababbc1
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v6/operating-systems/jsJ0nR38zvo.pdf
  title: 3play pdf file
  type: null
  uid: d17c5638ee2a1c8d1be4d87b924da3f9
- id: Caption-3Play YouTube id-SRT
  parent_uid: 79f7230eace3d57ab4d7cee4dababbc1
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 13e65e7cdbce5e0c595b7bb92c865b9c
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 79f7230eace3d57ab4d7cee4dababbc1
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 2ee8977dc374d67a68981e8c1f76dca0
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_17-02-06-01_300k.mp4
  parent_uid: 79f7230eace3d57ab4d7cee4dababbc1
  title: Video-Internet Archive-MP4
  type: Video
  uid: 80078f67ffbdd74b7ad8374e335f87ce
inline_embed_id: 79981643operatingsystems67654305
layout: video
order_index: null
parent_uid: 3c2b441ccd8608b745cf14f13ade0704
related_resources_text: ''
short_url: operating-systems
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v6/operating-systems
template_type: Embed
title: 'Worked Example: Operating Systems'
transcript: <p><span m="1090">In</span> <span m="1396">order</span> <span m="1702">for</span>
  <span m="2009">multiple</span> <span m="2315">processes</span> <span m="2622">to</span>
  <span m="2928">be</span> <span m="3235">able</span> <span m="3541">to</span> <span
  m="3848">run</span> <span m="4154">on</span> <span m="4461">the</span> <span m="4767">same</span>
  <span m="5074">computer,</span> <span m="5380">using</span> <span m="5687">a</span>
  <span m="5993">shared</span> <span m="6300">address</span> <span m="6636">space,</span>
  <span m="6973">we</span> <span m="7310">need</span> <span m="7646">to</span> <span
  m="7983">have</span> <span m="8320">an</span> <span m="8656">operating</span> <span
  m="8993">system</span> <span m="9330">that</span> <span m="9666">controls</span>
  <span m="10003">which</span> <span m="10340">process</span> <span m="10676">gets</span>
  <span m="11013">to</span> <span m="11350">run</span> <span m="11644">at</span> <span
  m="11938">any</span> <span m="12232">given</span> <span m="12526">point</span> <span
  m="12820">in</span> <span m="13114">time</span> <span m="13408">and</span> <span
  m="13702">ensures</span> <span m="13997">that</span> <span m="14291">the</span>
  <span m="14585">state</span> <span m="14879">that</span> <span m="15173">is</span>
  <span m="15467">currently</span> <span m="15761">loaded</span> <span m="16055">into</span>
  <span m="16350">the</span> <span m="16776">system</span> <span m="17203">is</span>
  <span m="17630">the</span> <span m="18056">state</span> <span m="18483">of</span>
  <span m="18910">the</span> <span m="19336">current</span> <span m="19763">process.</span></p><p><span
  m="20190">Through</span> <span m="20488">the</span> <span m="20786">following</span>
  <span m="21084">example</span> <span m="21382">we</span> <span m="21680">will</span>
  <span m="21978">take</span> <span m="22276">a</span> <span m="22574">closer</span>
  <span m="22872">look</span> <span m="23170">at</span> <span m="23468">how</span>
  <span m="23766">the</span> <span m="24064">operating</span> <span m="24362">system</span>
  <span m="24660">for</span> <span m="25130">the</span> <span m="25600">beta</span>
  <span m="26070">works.</span></p><p><span m="26540">We</span> <span m="26941">begin</span>
  <span m="27343">by</span> <span m="27744">examining</span> <span m="28146">the</span>
  <span m="28547">code</span> <span m="28949">responsible</span> <span m="29350">for</span>
  <span m="29752">maintaining</span> <span m="30153">the</span> <span m="30555">current</span>
  <span m="30956">processor</span> <span m="31358">state</span> <span m="31760">as</span>
  <span m="32096">well</span> <span m="32432">as</span> <span m="32769">scheduling</span>
  <span m="33105">which</span> <span m="33442">process</span> <span m="33778">should</span>
  <span m="34115">run</span> <span m="34451">at</span> <span m="34787">any</span>
  <span m="35124">given</span> <span m="35460">point</span> <span m="35797">in</span>
  <span m="36133">time.</span></p><p><span m="36470">The</span> <span m="36819">operating</span>
  <span m="37168">system</span> <span m="37518">uses</span> <span m="37867">a</span>
  <span m="38217">structure</span> <span m="38566">called</span> <span m="38915">MState</span>
  <span m="39265">to</span> <span m="39614">keep</span> <span m="39964">track</span>
  <span m="40313">of</span> <span m="40662">the</span> <span m="41012">value</span>
  <span m="41361">of</span> <span m="41711">the</span> <span m="42060">32</span> <span
  m="42410">registers</span> <span m="42835">for</span> <span m="43261">each</span>
  <span m="43687">of</span> <span m="44112">the</span> <span m="44538">running</span>
  <span m="44964">processes.</span></p><p><span m="45390">The</span> <span m="45887">UserMState</span>
  <span m="46384">variable</span> <span m="46881">holds</span> <span m="47379">the</span>
  <span m="47876">state</span> <span m="48373">of</span> <span m="48870">the</span>
  <span m="49368">currently</span> <span m="49865">running</span> <span m="50362">process.</span></p><p><span
  m="50860">The</span> <span m="51218">ProcTbl</span> <span m="51577">or</span> <span
  m="51936">process</span> <span m="52294">table,</span> <span m="52653">holds</span>
  <span m="53012">all</span> <span m="53370">the</span> <span m="53729">necessary</span>
  <span m="54088">state</span> <span m="54446">for</span> <span m="54805">each</span>
  <span m="55164">of</span> <span m="55522">the</span> <span m="55881">processes</span>
  <span m="56240">that</span> <span m="56686">runs</span> <span m="57132">on</span>
  <span m="57578">the</span> <span m="58024">machine.</span></p><p><span m="58470">For</span>
  <span m="58934">each</span> <span m="59398">process,</span> <span m="59862">it</span>
  <span m="60327">stores</span> <span m="60791">the</span> <span m="61255">value</span>
  <span m="61720">of</span> <span m="62184">all</span> <span m="62648">of</span> <span
  m="63113">its</span> <span m="63577">registers</span> <span m="64041">in</span>
  <span m="64506">the</span> <span m="64970">State</span> <span m="65434">variable.</span></p><p><span
  m="65899">Additional</span> <span m="66303">state</span> <span m="66707">may</span>
  <span m="67111">be</span> <span m="67516">stored</span> <span m="67920">per</span>
  <span m="68324">process.</span></p><p><span m="68729">Examples</span> <span m="69029">of</span>
  <span m="69329">some</span> <span m="69629">additional</span> <span m="69929">state</span>
  <span m="70229">that</span> <span m="70529">would</span> <span m="70829">go</span>
  <span m="71129">in</span> <span m="71429">a</span> <span m="71729">process</span>
  <span m="72029">table</span> <span m="72329">are</span> <span m="72629">a</span>
  <span m="72929">page</span> <span m="73229">map</span> <span m="73529">per</span>
  <span m="73829">process</span> <span m="74130">if</span> <span m="74517">we</span>
  <span m="74904">want</span> <span m="75291">to</span> <span m="75678">use</span>
  <span m="76065">virtual</span> <span m="76452">memory.</span></p><p><span m="76840">Another</span>
  <span m="77288">example,</span> <span m="77736">is</span> <span m="78184">a</span>
  <span m="78633">keyboard</span> <span m="79081">identifier,</span> <span m="79529">that</span>
  <span m="79977">associates</span> <span m="80426">hardware</span> <span m="80874">with</span>
  <span m="81322">a</span> <span m="81770">particular</span> <span m="82219">process.</span></p><p><span
  m="83389">The</span> <span m="83832">Cur,</span> <span m="84276">or</span> <span
  m="84720">current</span> <span m="85164">variable,</span> <span m="85607">holds</span>
  <span m="86051">the</span> <span m="86495">index</span> <span m="86939">of</span>
  <span m="87382">the</span> <span m="87826">currently</span> <span m="88270">running</span>
  <span m="88714">process.</span></p><p><span m="89158">When</span> <span m="89512">we</span>
  <span m="89867">want</span> <span m="90222">to</span> <span m="90576">switch</span>
  <span m="90931">control</span> <span m="91286">from</span> <span m="91641">one</span>
  <span m="91995">process</span> <span m="92350">to</span> <span m="92705">another,</span>
  <span m="93060">we</span> <span m="93414">call</span> <span m="93769">the</span>
  <span m="94124">Scheduler.</span></p><p><span m="94479">The</span> <span m="94822">Scheduler</span>
  <span m="95166">first</span> <span m="95509">stores</span> <span m="95853">the</span>
  <span m="96196">state</span> <span m="96540">of</span> <span m="96884">the</span>
  <span m="97227">currently</span> <span m="97571">running</span> <span m="97914">process</span>
  <span m="98258">into</span> <span m="98601">the</span> <span m="98945">process</span>
  <span m="99289">table.</span></p><p><span m="100419">Next,</span> <span m="100972">it</span>
  <span m="101526">increments</span> <span m="102079">the</span> <span m="102633">current</span>
  <span m="103187">process</span> <span m="103740">by</span> <span m="104294">1.</span></p><p><span
  m="104848">If</span> <span m="105224">the</span> <span m="105600">current</span>
  <span m="105976">process</span> <span m="106353">was</span> <span m="106729">process</span>
  <span m="107105">N</span> <span m="107482">&ndash;</span> <span m="107858">1,</span>
  <span m="108234">then</span> <span m="108611">it</span> <span m="108987">goes</span>
  <span m="109363">back</span> <span m="109740">to</span> <span m="110116">process</span>
  <span m="110492">0.</span></p><p><span m="110869">Finally,</span> <span m="111301">it</span>
  <span m="111734">reloads</span> <span m="112167">the</span> <span m="112600">user</span>
  <span m="113033">variable</span> <span m="113466">with</span> <span m="113899">the</span>
  <span m="114331">state</span> <span m="114764">for</span> <span m="115197">the</span>
  <span m="115630">new</span> <span m="116063">current</span> <span m="116496">process.</span></p><p><span
  m="116929">In</span> <span m="117228">order</span> <span m="117527">to</span> <span
  m="117827">be</span> <span m="118126">able</span> <span m="118426">to</span> <span
  m="118725">run</span> <span m="119025">a</span> <span m="119324">diagnostic</span>
  <span m="119624">program</span> <span m="119923">on</span> <span m="120222">one</span>
  <span m="120522">process</span> <span m="120821">that</span> <span m="121121">samples</span>
  <span m="121420">the</span> <span m="121720">values</span> <span m="122019">in</span>
  <span m="122319">the</span> <span m="122854">PC</span> <span m="123389">of</span>
  <span m="123924">another</span> <span m="124459">process,</span> <span m="124994">a</span>
  <span m="125529">supervisor</span> <span m="126064">call</span> <span m="126599">named</span>
  <span m="127134">SamplePC</span> <span m="127669">is</span> <span m="128204">provided</span>
  <span m="128739">for</span> <span m="129274">you.</span></p><p><span m="129810">The</span>
  <span m="130320">C</span> <span m="130830">portion</span> <span m="131340">of</span>
  <span m="131850">the</span> <span m="132360">SVC</span> <span m="132870">handler</span>
  <span m="133380">is</span> <span m="133890">provided</span> <span m="134400">for</span>
  <span m="134910">you</span> <span m="135420">here.</span></p><p><span m="135930">It</span>
  <span m="136392">is</span> <span m="136854">incomplete,</span> <span m="137316">so</span>
  <span m="137778">our</span> <span m="138240">first</span> <span m="138702">goal</span>
  <span m="139164">is</span> <span m="139626">to</span> <span m="140088">determine</span>
  <span m="140550">what</span> <span m="141012">should</span> <span m="141474">replace</span>
  <span m="141936">the</span> <span m="142398">???.</span></p><p><span m="142860">We</span>
  <span m="143262">are</span> <span m="143665">told</span> <span m="144067">that</span>
  <span m="144470">the</span> <span m="144873">way</span> <span m="145275">SamplePC</span>
  <span m="145678">SVC</span> <span m="146081">works</span> <span m="146483">is</span>
  <span m="146886">that</span> <span m="147288">it</span> <span m="147691">takes</span>
  <span m="148094">a</span> <span m="148496">process</span> <span m="148899">number</span>
  <span m="149302">p</span> <span m="149704">in</span> <span m="150107">R0,</span>
  <span m="150510">and</span> <span m="150926">returns</span> <span m="151342">in</span>
  <span m="151759">R1</span> <span m="152175">the</span> <span m="152592">value</span>
  <span m="153008">currently</span> <span m="153425">in</span> <span m="153841">the</span>
  <span m="154257">program</span> <span m="154674">counter</span> <span m="155090">of</span>
  <span m="155507">process</span> <span m="155923">p.</span></p><p><span m="156340">The</span>
  <span m="156734">handler</span> <span m="157128">shown</span> <span m="157522">here</span>
  <span m="157916">reads</span> <span m="158310">register</span> <span m="158704">0</span>
  <span m="159098">from</span> <span m="159492">the</span> <span m="159886">UserMState</span>
  <span m="160280">data</span> <span m="160674">structure</span> <span m="161068">and</span>
  <span m="161462">stores</span> <span m="161856">the</span> <span m="162250">value</span>
  <span m="162982">into</span> <span m="163715">variable</span> <span m="164447">p.</span></p><p><span
  m="165180">This</span> <span m="165459">is</span> <span m="165738">the</span> <span
  m="166017">number</span> <span m="166296">of</span> <span m="166575">the</span>
  <span m="166855">process</span> <span m="167134">that</span> <span m="167413">is</span>
  <span m="167692">to</span> <span m="167971">be</span> <span m="168250">monitored.</span></p><p><span
  m="168530">In</span> <span m="168822">order</span> <span m="169114">to</span> <span
  m="169406">determine</span> <span m="169698">the</span> <span m="169990">value</span>
  <span m="170282">of</span> <span m="170574">the</span> <span m="170866">PC</span>
  <span m="171158">of</span> <span m="171450">process</span> <span m="171742">p,</span>
  <span m="172034">one</span> <span m="172326">can</span> <span m="172618">look</span>
  <span m="172910">up</span> <span m="173202">the</span> <span m="173494">value</span>
  <span m="173786">of</span> <span m="174079">the</span> <span m="174458">XP</span>
  <span m="174837">register</span> <span m="175217">that</span> <span m="175596">was</span>
  <span m="175976">saved</span> <span m="176355">for</span> <span m="176735">process</span>
  <span m="177114">p</span> <span m="177493">the</span> <span m="177873">last</span>
  <span m="178252">time</span> <span m="178632">process</span> <span m="179011">p</span>
  <span m="179391">was</span> <span m="179770">run.</span></p><p><span m="180150">The</span>
  <span m="180531">XP</span> <span m="180913">register</span> <span m="181295">holds</span>
  <span m="181676">the</span> <span m="182058">value</span> <span m="182440">of</span>
  <span m="182822">the</span> <span m="183203">next</span> <span m="183585">PC</span>
  <span m="183967">address.</span></p><p><span m="184349">So</span> <span m="184803">reading</span>
  <span m="185257">the</span> <span m="185711">XP</span> <span m="186165">register</span>
  <span m="186619">from</span> <span m="187073">ProcTbl[p]</span> <span m="187527">tells</span>
  <span m="187981">us</span> <span m="188436">the</span> <span m="188890">next</span>
  <span m="189344">value</span> <span m="189798">of</span> <span m="190252">the</span>
  <span m="190706">pc</span> <span m="191160">for</span> <span m="191614">process</span>
  <span m="192069">p.</span></p><p><span m="193420">The</span> <span m="193806">pc</span>
  <span m="194192">value</span> <span m="194579">is</span> <span m="194965">to</span>
  <span m="195351">be</span> <span m="195738">returned</span> <span m="196124">in</span>
  <span m="196510">register</span> <span m="196897">R1</span> <span m="197283">of</span>
  <span m="197669">the</span> <span m="198056">current</span> <span m="198442">program.</span></p><p><span
  m="198829">This</span> <span m="199309">means</span> <span m="199790">that</span>
  <span m="200270">the</span> <span m="200751">missing</span> <span m="201232">code</span>
  <span m="201712">is</span> <span m="202193">UserMState.Regs[1]</span> <span m="202674">and</span>
  <span m="203154">that</span> <span m="203635">should</span> <span m="204116">be</span>
  <span m="204596">assigned</span> <span m="205077">the</span> <span m="205558">value</span>
  <span m="206038">of</span> <span m="206519">pc.</span></p><p><span m="207000">Suppose</span>
  <span m="207452">you</span> <span m="207904">have</span> <span m="208356">a</span>
  <span m="208808">compute-bound</span> <span m="209261">process</span> <span m="209713">consisting</span>
  <span m="210165">of</span> <span m="210617">a</span> <span m="211070">single</span>
  <span m="211522">10,000</span> <span m="211974">instruction</span> <span m="212426">loop.</span></p><p><span
  m="212879">You</span> <span m="213325">use</span> <span m="213771">the</span> <span
  m="214218">SamplePC</span> <span m="214664">supervisor</span> <span m="215111">call</span>
  <span m="215557">to</span> <span m="216004">sample</span> <span m="216450">the</span>
  <span m="216896">PC</span> <span m="217343">while</span> <span m="217789">running</span>
  <span m="218236">this</span> <span m="218682">loop.</span></p><p><span m="219129">You</span>
  <span m="219525">notice</span> <span m="219922">many</span> <span m="220319">repeated</span>
  <span m="220715">values</span> <span m="221112">in</span> <span m="221509">the</span>
  <span m="221905">results</span> <span m="222302">of</span> <span m="222699">the</span>
  <span m="223095">SamplePC</span> <span m="223492">code.</span></p><p><span m="223889">You</span>
  <span m="224288">realize</span> <span m="224687">that</span> <span m="225087">the</span>
  <span m="225486">reason</span> <span m="225885">this</span> <span m="226285">is</span>
  <span m="226684">happening</span> <span m="227083">is</span> <span m="227483">because</span>
  <span m="227882">every</span> <span m="228281">time</span> <span m="228681">your</span>
  <span m="229080">profiling</span> <span m="229479">process</span> <span m="229879">gets</span>
  <span m="230296">scheduled</span> <span m="230713">to</span> <span m="231131">run,</span>
  <span m="231548">it</span> <span m="231966">makes</span> <span m="232383">many</span>
  <span m="232800">SamplePC</span> <span m="233218">calls</span> <span m="233635">but</span>
  <span m="234053">the</span> <span m="234470">other</span> <span m="234887">processes</span>
  <span m="235305">aren't</span> <span m="235722">running</span> <span m="236140">so</span>
  <span m="236596">you</span> <span m="237052">are</span> <span m="237508">getting</span>
  <span m="237964">the</span> <span m="238420">same</span> <span m="238876">sampled</span>
  <span m="239332">PC</span> <span m="239788">multiple</span> <span m="240244">times.</span></p><p><span
  m="240700">How</span> <span m="241102">can</span> <span m="241505">the</span> <span
  m="241908">repeated</span> <span m="242311">samples</span> <span m="242714">be</span>
  <span m="243117">avoided?</span></p><p><span m="243520">To</span> <span m="243940">avoid</span>
  <span m="244361">repeated</span> <span m="244781">samples,</span> <span m="245202">we</span>
  <span m="245623">add</span> <span m="246043">a</span> <span m="246464">call</span>
  <span m="246885">to</span> <span m="247305">Scheduler()</span> <span m="247726">in</span>
  <span m="248147">our</span> <span m="248567">SamplePC</span> <span m="248988">handler.</span></p><p><span
  m="249409">This</span> <span m="249750">ensures</span> <span m="250092">that</span>
  <span m="250434">every</span> <span m="250776">time</span> <span m="251118">that</span>
  <span m="251460">the</span> <span m="251802">profiler</span> <span m="252144">process</span>
  <span m="252485">is</span> <span m="252827">scheduled,</span> <span m="253169">it</span>
  <span m="253511">only</span> <span m="253853">samples</span> <span m="254195">a</span>
  <span m="254537">single</span> <span m="254879">PC</span> <span m="255381">value</span>
  <span m="255884">and</span> <span m="256386">then</span> <span m="256889">let's</span>
  <span m="257391">another</span> <span m="257894">process</span> <span m="258396">run.</span></p><p><span
  m="258899">Suppose</span> <span m="259248">that</span> <span m="259597">you</span>
  <span m="259947">continue</span> <span m="260296">using</span> <span m="260645">the</span>
  <span m="260995">original</span> <span m="261344">version</span> <span m="261693">of</span>
  <span m="262043">your</span> <span m="262392">SamplePC</span> <span m="262741">handler,</span>
  <span m="263091">which</span> <span m="263440">does</span> <span m="263790">not</span>
  <span m="264178">call</span> <span m="264566">Scheduler,</span> <span m="264954">and</span>
  <span m="265342">you</span> <span m="265730">use</span> <span m="266118">it</span>
  <span m="266506">to</span> <span m="266895">test</span> <span m="267283">this</span>
  <span m="267671">code</span> <span m="268059">which</span> <span m="268447">repeatedly</span>
  <span m="268835">calls</span> <span m="269223">the</span> <span m="269611">GetKey()</span>
  <span m="270000">supervisor</span> <span m="270408">call</span> <span m="270817">to</span>
  <span m="271226">read</span> <span m="271634">a</span> <span m="272043">character</span>
  <span m="272452">from</span> <span m="272860">the</span> <span m="273269">keyboard,</span>
  <span m="273678">and</span> <span m="274086">then</span> <span m="274495">calls</span>
  <span m="274904">the</span> <span m="275312">WrCh()</span> <span m="275721">supervisor</span>
  <span m="276130">call</span> <span m="276617">to</span> <span m="277105">write</span>
  <span m="277593">the</span> <span m="278081">character</span> <span m="278568">that</span>
  <span m="279056">was</span> <span m="279544">just</span> <span m="280032">read.</span></p><p><span
  m="280520">We</span> <span m="280887">want</span> <span m="281255">to</span> <span
  m="281623">answer</span> <span m="281990">the</span> <span m="282358">question</span>
  <span m="282726">of</span> <span m="283094">which</span> <span m="283461">PC</span>
  <span m="283829">value</span> <span m="284197">will</span> <span m="284564">be</span>
  <span m="284932">the</span> <span m="285300">one</span> <span m="285668">reported</span>
  <span m="286035">the</span> <span m="286403">most</span> <span m="286771">often.</span></p><p><span
  m="287139">Address</span> <span m="287551">0x100</span> <span m="287964">which</span>
  <span m="288376">is</span> <span m="288789">the</span> <span m="289201">address</span>
  <span m="289614">of</span> <span m="290026">the</span> <span m="290439">GetKey()</span>
  <span m="290852">call</span> <span m="291264">is</span> <span m="291677">reported</span>
  <span m="292089">the</span> <span m="292502">most</span> <span m="292914">often</span>
  <span m="293327">because</span> <span m="293740">most</span> <span m="294076">of</span>
  <span m="294412">the</span> <span m="294749">time</span> <span m="295085">when</span>
  <span m="295422">GetKey()</span> <span m="295758">is</span> <span m="296095">called,</span>
  <span m="296431">there</span> <span m="296768">is</span> <span m="297104">no</span>
  <span m="297441">key</span> <span m="297777">stroke</span> <span m="298114">waiting</span>
  <span m="298450">to</span> <span m="298787">be</span> <span m="299123">processed.</span></p><p><span
  m="299460">This</span> <span m="299754">means</span> <span m="300048">that</span>
  <span m="300342">the</span> <span m="300636">GetKey()</span> <span m="300930">call</span>
  <span m="301224">will</span> <span m="301518">get</span> <span m="301812">processed</span>
  <span m="302106">over</span> <span m="302400">and</span> <span m="302694">over</span>
  <span m="302988">again</span> <span m="303282">until</span> <span m="303576">there</span>
  <span m="303870">is</span> <span m="304228">finally</span> <span m="304586">a</span>
  <span m="304945">key</span> <span m="305303">to</span> <span m="305661">process.</span></p><p><span
  m="306020">The</span> <span m="306402">result</span> <span m="306784">of</span>
  <span m="307167">this</span> <span m="307549">is</span> <span m="307931">that</span>
  <span m="308314">the</span> <span m="308696">PC</span> <span m="309078">value</span>
  <span m="309461">that</span> <span m="309843">shows</span> <span m="310225">up</span>
  <span m="310608">the</span> <span m="310990">most</span> <span m="311372">often</span>
  <span m="311755">is</span> <span m="312137">0x100.</span></p><p><span m="312520">The</span>
  <span m="312800">last</span> <span m="313080">question</span> <span m="313360">we</span>
  <span m="313640">want</span> <span m="313920">to</span> <span m="314200">consider</span>
  <span m="314480">is</span> <span m="314760">what</span> <span m="315040">behavior</span>
  <span m="315320">is</span> <span m="315600">observed</span> <span m="315880">when</span>
  <span m="316160">the</span> <span m="316440">profiler</span> <span m="316720">which</span>
  <span m="317000">is</span> <span m="317501">running</span> <span m="318002">in</span>
  <span m="318503">process</span> <span m="319004">0</span> <span m="319505">profiles</span>
  <span m="320006">process</span> <span m="320507">0</span> <span m="321008">itself.</span></p><p><span
  m="321509">Assume</span> <span m="321875">that</span> <span m="322242">the</span>
  <span m="322608">profiler</span> <span m="322975">code</span> <span m="323341">consists</span>
  <span m="323708">primarily</span> <span m="324074">of</span> <span m="324441">one</span>
  <span m="324807">big</span> <span m="325174">loop</span> <span m="325540">which</span>
  <span m="325907">has</span> <span m="326273">a</span> <span m="326640">single</span>
  <span m="327006">call</span> <span m="327373">to</span> <span m="327740">the</span>
  <span m="328484">SamplePC</span> <span m="329228">supervisor</span> <span m="329972">call</span>
  <span m="330716">at</span> <span m="331460">instruction</span> <span m="332204">0x1000.</span></p><p><span
  m="332949">The</span> <span m="333305">rest</span> <span m="333662">of</span> <span
  m="334019">the</span> <span m="334375">loop</span> <span m="334732">processes</span>
  <span m="335089">the</span> <span m="335446">data</span> <span m="335802">that</span>
  <span m="336159">was</span> <span m="336516">collected</span> <span m="336873">by</span>
  <span m="337229">the</span> <span m="337586">SamplePC</span> <span m="337943">call.</span></p><p><span
  m="338300">The</span> <span m="338740">question</span> <span m="339181">we</span>
  <span m="339622">want</span> <span m="340062">to</span> <span m="340503">answer</span>
  <span m="340944">is</span> <span m="341385">what</span> <span m="341825">is</span>
  <span m="342266">observed</span> <span m="342707">in</span> <span m="343147">the</span>
  <span m="343588">SamplePC</span> <span m="344029">results.</span></p><p><span m="344470">We</span>
  <span m="344939">are</span> <span m="345409">given</span> <span m="345879">4</span>
  <span m="346349">choices</span> <span m="346819">to</span> <span m="347289">select</span>
  <span m="347759">from.</span></p><p><span m="348229">The</span> <span m="348546">first</span>
  <span m="348864">choice</span> <span m="349182">to</span> <span m="349499">consider</span>
  <span m="349817">is</span> <span m="350135">whether</span> <span m="350452">or</span>
  <span m="350770">not</span> <span m="351088">all</span> <span m="351406">the</span>
  <span m="351723">sampled</span> <span m="352041">PC</span> <span m="352359">values</span>
  <span m="352676">point</span> <span m="352994">to</span> <span m="353312">the</span>
  <span m="353630">kernel</span> <span m="354360">OS</span> <span m="355090">code.</span></p><p><span
  m="355820">This</span> <span m="356074">choice</span> <span m="356328">is</span>
  <span m="356582">false</span> <span m="356836">because</span> <span m="357090">if</span>
  <span m="357344">it</span> <span m="357598">were</span> <span m="357852">true</span>
  <span m="358106">it</span> <span m="358360">would</span> <span m="358614">mean</span>
  <span m="358868">that</span> <span m="359122">you</span> <span m="359376">somehow</span>
  <span m="359630">managed</span> <span m="359884">to</span> <span m="360139">interrupt</span>
  <span m="360708">kernel</span> <span m="361277">code</span> <span m="361846">which</span>
  <span m="362415">is</span> <span m="362984">not</span> <span m="363553">allowed</span>
  <span m="364122">by</span> <span m="364691">the</span> <span m="365260">beta.</span></p><p><span
  m="365830">The</span> <span m="366354">next</span> <span m="366879">choice</span>
  <span m="367403">to</span> <span m="367928">consider</span> <span m="368453">is</span>
  <span m="368977">whether</span> <span m="369502">the</span> <span m="370026">sampled</span>
  <span m="370551">PC</span> <span m="371076">is</span> <span m="371600">always</span>
  <span m="372125">0x1004.</span></p><p><span m="372650">This</span> <span m="372963">seems</span>
  <span m="373276">like</span> <span m="373589">it</span> <span m="373902">might</span>
  <span m="374215">be</span> <span m="374528">a</span> <span m="374841">correct</span>
  <span m="375154">choice</span> <span m="375467">because</span> <span m="375780">the</span>
  <span m="376093">SamplePC</span> <span m="376406">supervisor</span> <span m="376719">call</span>
  <span m="377032">is</span> <span m="377345">at</span> <span m="377659">address</span>
  <span m="378317">0x1000,</span> <span m="378976">so</span> <span m="379635">storing</span>
  <span m="380294">PC</span> <span m="380952">+</span> <span m="381611">4</span> <span
  m="382270">would</span> <span m="382929">result</span> <span m="383587">in</span>
  <span m="384246">0x1004</span> <span m="384905">being</span> <span m="385564">stored</span>
  <span m="386222">into</span> <span m="386881">the</span> <span m="387540">UserMState.Regs[XP].</span></p><p><span
  m="388199">However,</span> <span m="388606">if</span> <span m="389014">you</span>
  <span m="389421">look</span> <span m="389829">closely</span> <span m="390237">at</span>
  <span m="390644">the</span> <span m="391052">SamplePC</span> <span m="391460">handler</span>
  <span m="391867">you</span> <span m="392275">see</span> <span m="392683">that</span>
  <span m="393090">the</span> <span m="393498">XP</span> <span m="393906">register</span>
  <span m="394313">is</span> <span m="394721">read</span> <span m="395129">from</span>
  <span m="395512">the</span> <span m="395896">ProcTbl.</span></p><p><span m="396280">But</span>
  <span m="396715">the</span> <span m="397151">UserMState</span> <span m="397587">regs</span>
  <span m="398023">are</span> <span m="398459">only</span> <span m="398895">written</span>
  <span m="399331">to</span> <span m="399767">ProcTbl</span> <span m="400203">when</span>
  <span m="400639">Scheduler()</span> <span m="401075">is</span> <span m="401511">called,</span>
  <span m="401947">so</span> <span m="402383">reading</span> <span m="402819">the</span>
  <span m="403252">value</span> <span m="403685">from</span> <span m="404119">ProcTbl</span>
  <span m="404552">would</span> <span m="404985">provide</span> <span m="405419">the</span>
  <span m="405852">last</span> <span m="406286">value</span> <span m="406719">of</span>
  <span m="407152">the</span> <span m="407586">PC</span> <span m="408019">when</span>
  <span m="408453">process</span> <span m="408886">0</span> <span m="409319">was</span>
  <span m="409753">last</span> <span m="410186">interrupted.</span></p><p><span m="410620">To</span>
  <span m="411120">get</span> <span m="411620">the</span> <span m="412120">correct</span>
  <span m="412620">value,</span> <span m="413120">you</span> <span m="413620">would</span>
  <span m="414120">need</span> <span m="414620">to</span> <span m="415120">read</span>
  <span m="415620">UserMState.Regs[XP]</span> <span m="416120">instead.</span></p><p><span
  m="416620">The</span> <span m="417219">third</span> <span m="417818">choice</span>
  <span m="418417">is</span> <span m="419016">that</span> <span m="419615">the</span>
  <span m="420214">SamplePC</span> <span m="420813">call</span> <span m="421412">never</span>
  <span m="422011">returns.</span></p><p><span m="422610">There</span> <span m="422977">is</span>
  <span m="423345">no</span> <span m="423713">reason</span> <span m="424080">for</span>
  <span m="424448">this</span> <span m="424816">to</span> <span m="425183">be</span>
  <span m="425551">true.</span></p><p><span m="425919">Finally,</span> <span m="426376">the</span>
  <span m="426834">last</span> <span m="427292">choice</span> <span m="427750">is</span>
  <span m="428207">&quot;None</span> <span m="428665">of</span> <span m="429123">the</span>
  <span m="429581">above&quot;.</span></p><p><span m="430039">Since</span> <span m="430371">none</span>
  <span m="430703">of</span> <span m="431036">the</span> <span m="431368">other</span>
  <span m="431700">choices</span> <span m="432033">were</span> <span m="432365">correct,</span>
  <span m="432698">this</span> <span m="433030">is</span> <span m="433362">the</span>
  <span m="433695">correct</span> <span m="434027">answer.</span></p>
type: course
uid: 79f7230eace3d57ab4d7cee4dababbc1

---
None