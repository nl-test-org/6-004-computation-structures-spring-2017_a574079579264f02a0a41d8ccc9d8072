---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 5BRcFgMJLCs
  parent_uid: c1b50830748cc9951d800120d9ec547b
  title: Video-YouTube-Stream
  type: Video
  uid: e0fffe316ffb62fdfdb4b73c6b8482aa
- id: 3Play-3Play YouTube id-Stream
  media_location: 5BRcFgMJLCs
  parent_uid: c1b50830748cc9951d800120d9ec547b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: c19364ad205ffb1936458eff281a6cbd
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/5BRcFgMJLCs/default.jpg
  parent_uid: c1b50830748cc9951d800120d9ec547b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 8cecf04b10cb30b82a2acb518763b7bc
- id: 5BRcFgMJLCs.srt
  parent_uid: c1b50830748cc9951d800120d9ec547b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/c11s2v6/compilers/5BRcFgMJLCs.srt
  title: 3play caption file
  type: null
  uid: 0e3fe0cf5a0bba2cf5f934b18f648f5f
- id: 5BRcFgMJLCs.pdf
  parent_uid: c1b50830748cc9951d800120d9ec547b
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/c11s2v6/compilers/5BRcFgMJLCs.pdf
  title: 3play pdf file
  type: null
  uid: 50898ab1837986bf42eb3377c19075ab
- id: Caption-3Play YouTube id-SRT
  parent_uid: c1b50830748cc9951d800120d9ec547b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 96b5a64348d982c11b21ff6ba4dc4637
- id: Transcript-3Play YouTube id-PDF
  parent_uid: c1b50830748cc9951d800120d9ec547b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 1a362785fc02b0170fbae3c9b23a2522
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_11-02-06-01_300k.mp4
  parent_uid: c1b50830748cc9951d800120d9ec547b
  title: Video-Internet Archive-MP4
  type: Video
  uid: 7f20533927f5f802bbe205a6ef07707e
inline_embed_id: 28272146compilers71320565
layout: video
order_index: null
parent_uid: 34592e46daeaac57b6e403b2df0ceeeb
related_resources_text: ''
short_url: compilers
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/c11s2v6/compilers
template_type: Embed
title: 'Worked Example: Compilers'
transcript: <p><span m="1030">In</span> <span m="1452">this</span> <span m="1874">problem,</span>
  <span m="2296">we</span> <span m="2718">will</span> <span m="3141">examine</span>
  <span m="3563">how</span> <span m="3985">compilers</span> <span m="4407">translate</span>
  <span m="4830">high</span> <span m="5252">level</span> <span m="5674">language</span>
  <span m="6096">descriptions</span> <span m="6519">into</span> <span m="6930">assembly</span>
  <span m="7342">language.</span> <span m="7754">We</span> <span m="8166">will</span>
  <span m="8578">be</span> <span m="8989">given</span> <span m="9401">several</span>
  <span m="9813">code</span> <span m="10225">fragments</span> <span m="10637">and</span>
  <span m="11049">asked</span> <span m="11343">to</span> <span m="11637">help</span>
  <span m="11932">the</span> <span m="12226">compiler</span> <span m="12520">in</span>
  <span m="12815">figuring</span> <span m="13109">out</span> <span m="13404">the</span>
  <span m="13698">dependencies</span> <span m="13992">of</span> <span m="14287">the</span>
  <span m="14581">program</span> <span m="14875">so</span> <span m="15170">that</span>
  <span m="15464">it</span> <span m="15759">produces</span> <span m="16340">valid</span>
  <span m="16922">code.</span> <span m="17504">Let's</span> <span m="18086">begin</span>
  <span m="18667">with</span> <span m="19249">the</span> <span m="19831">code</span>
  <span m="20413">fragment:</span> <span m="20994">a</span> <span m="21576">=</span>
  <span m="22158">b</span> <span m="22740">+</span> <span m="23173">3*c.</span> <span
  m="23607">We</span> <span m="24040">can</span> <span m="24474">assume</span> <span
  m="24908">that</span> <span m="25341">our</span> <span m="25775">variables:</span>
  <span m="26209">a,</span> <span m="26642">b,</span> <span m="27076">and</span> <span
  m="27510">c</span> <span m="27862">are</span> <span m="28214">stored</span> <span
  m="28566">in</span> <span m="28918">memory.</span> <span m="29270">We</span> <span
  m="29622">can</span> <span m="29974">also</span> <span m="30326">assume</span> <span
  m="30678">that</span> <span m="31030">registers</span> <span m="31382">may</span>
  <span m="31734">be</span> <span m="32086">used</span> <span m="32439">to</span>
  <span m="32987">store</span> <span m="33535">intermediate</span> <span m="34083">results.</span>
  <span m="34631">Given</span> <span m="35179">the</span> <span m="35727">following</span>
  <span m="36275">partially</span> <span m="36823">completed</span> <span m="37371">assembly</span>
  <span m="37920">code,</span> <span m="38309">let's</span> <span m="38699">determine</span>
  <span m="39089">the</span> <span m="39479">missing</span> <span m="39869">values</span>
  <span m="40259">that</span> <span m="40649">the</span> <span m="41039">compiler</span>
  <span m="41429">would</span> <span m="41819">have</span> <span m="42209">had</span>
  <span m="42599">to</span> <span m="42989">determine.</span></p><p><span m="43379">We</span>
  <span m="43719">begin</span> <span m="44059">with</span> <span m="44399">XXX</span>
  <span m="44739">which</span> <span m="45079">is</span> <span m="45419">the</span>
  <span m="45759">first</span> <span m="46099">instruction.</span> <span m="46439">The</span>
  <span m="46779">first</span> <span m="47119">instruction</span> <span m="47459">is</span>
  <span m="47799">trying</span> <span m="48139">to</span> <span m="48479">put</span>
  <span m="48819">the</span> <span m="49160">value</span> <span m="49515">of</span>
  <span m="49870">c</span> <span m="50225">into</span> <span m="50580">register</span>
  <span m="50935">R1.</span> <span m="51290">Since</span> <span m="51645">c</span>
  <span m="52000">comes</span> <span m="52355">from</span> <span m="52710">memory,</span>
  <span m="53065">that</span> <span m="53420">means</span> <span m="53775">that</span>
  <span m="54130">instruction</span> <span m="54583">XXX</span> <span m="55037">must</span>
  <span m="55491">be</span> <span m="55945">a</span> <span m="56399">LD</span> <span
  m="56853">operation</span> <span m="57307">where</span> <span m="57761">c</span>
  <span m="58215">is</span> <span m="58668">the</span> <span m="59122">address</span>
  <span m="59576">of</span> <span m="60030">the</span> <span m="60484">variable</span>
  <span m="60938">to</span> <span m="61392">be</span> <span m="61846">loaded.</span></p><p><span
  m="62300">Note</span> <span m="63021">that</span> <span m="63742">LD(c,</span> <span
  m="64463">R1)</span> <span m="65185">is</span> <span m="65906">actually</span> <span
  m="66627">a</span> <span m="67348">macro</span> <span m="68070">instruction</span>
  <span m="68791">that</span> <span m="69512">is</span> <span m="70233">equal</span>
  <span m="70955">to</span> <span m="71676">LD(R31,</span> <span m="72397">c,</span>
  <span m="73118">R1).</span></p><p><span m="73840">The</span> <span m="74185">load</span>
  <span m="74530">operation</span> <span m="74875">would</span> <span m="75221">add</span>
  <span m="75566">the</span> <span m="75911">constant</span> <span m="76257">c</span>
  <span m="76602">to</span> <span m="76947">the</span> <span m="77292">value</span>
  <span m="77638">of</span> <span m="77983">register</span> <span m="78328">R31,</span>
  <span m="78674">which</span> <span m="79019">is</span> <span m="79364">always</span>
  <span m="79710">0,</span> <span m="80047">thus</span> <span m="80385">ending</span>
  <span m="80722">up</span> <span m="81060">with</span> <span m="81397">the</span>
  <span m="81735">address</span> <span m="82072">c</span> <span m="82410">as</span>
  <span m="82747">the</span> <span m="83085">source</span> <span m="83422">address</span>
  <span m="83760">of</span> <span m="84097">the</span> <span m="84435">load</span>
  <span m="84772">operation.</span></p><p><span m="85110">R1</span> <span m="85480">is</span>
  <span m="85851">a</span> <span m="86222">temporary</span> <span m="86593">register</span>
  <span m="86963">that</span> <span m="87334">will</span> <span m="87705">hold</span>
  <span m="88076">the</span> <span m="88446">value</span> <span m="88817">of</span>
  <span m="89188">variable</span> <span m="89559">c.</span></p><p><span m="89930">Next,</span>
  <span m="90546">we</span> <span m="91162">need</span> <span m="91779">to</span>
  <span m="92395">multiply</span> <span m="93012">c</span> <span m="93628">by</span>
  <span m="94245">3.</span> <span m="94861">Multiply</span> <span m="95477">operations</span>
  <span m="96094">are</span> <span m="96710">generally</span> <span m="97327">very</span>
  <span m="97943">expensive,</span> <span m="98560">so</span> <span m="98852">it</span>
  <span m="99145">is</span> <span m="99437">the</span> <span m="99730">compilers</span>
  <span m="100022">job</span> <span m="100315">to</span> <span m="100607">figure</span>
  <span m="100900">out</span> <span m="101192">that</span> <span m="101485">this</span>
  <span m="101777">operation</span> <span m="102070">could</span> <span m="102362">potentially</span>
  <span m="102655">be</span> <span m="102947">achieved</span> <span m="103240">by</span>
  <span m="103634">2</span> <span m="104029">simpler</span> <span m="104423">and</span>
  <span m="104818">faster</span> <span m="105212">operations.</span> <span m="105607">The</span>
  <span m="106001">comment</span> <span m="106396">tells</span> <span m="106790">us</span>
  <span m="107185">that</span> <span m="107579">it</span> <span m="107974">first</span>
  <span m="108368">tries</span> <span m="108763">to</span> <span m="109158">compute</span>
  <span m="109569">2</span> <span m="109981">*</span> <span m="110392">c</span> <span
  m="110804">and</span> <span m="111216">store</span> <span m="111627">that</span>
  <span m="112039">result</span> <span m="112450">into</span> <span m="112862">R0.</span>
  <span m="113274">Since</span> <span m="113685">R1</span> <span m="114097">=</span>
  <span m="114508">c,</span> <span m="114920">and</span> <span m="115332">the</span>
  <span m="115743">constant</span> <span m="116155">in</span> <span m="116566">this</span>
  <span m="116978">operation</span> <span m="117390">is</span> <span m="117712">a</span>
  <span m="118034">1,</span> <span m="118356">we</span> <span m="118679">need</span>
  <span m="119001">to</span> <span m="119323">realize</span> <span m="119646">that</span>
  <span m="119968">the</span> <span m="120290">inexpensive</span> <span m="120612">operation</span>
  <span m="120935">that</span> <span m="121257">the</span> <span m="121579">compiler</span>
  <span m="121902">would</span> <span m="122224">use</span> <span m="122546">for</span>
  <span m="122869">this</span> <span m="123294">is</span> <span m="123719">a</span>
  <span m="124145">logical</span> <span m="124570">shift</span> <span m="124996">to</span>
  <span m="125421">the</span> <span m="125847">left</span> <span m="126272">by</span>
  <span m="126698">one</span> <span m="127123">position.</span></p><p><span m="127549">In</span>
  <span m="127906">binary,</span> <span m="128263">this</span> <span m="128620">produces</span>
  <span m="128977">the</span> <span m="129334">same</span> <span m="129691">result</span>
  <span m="130048">as</span> <span m="130405">multiplying</span> <span m="130762">a</span>
  <span m="131119">number</span> <span m="131476">by</span> <span m="131833">2.</span></p><p><span
  m="132190">So</span> <span m="132887">YYY</span> <span m="133585">=</span> <span
  m="134283">SHLC.</span> <span m="134980">Note</span> <span m="135678">that</span>
  <span m="136376">we</span> <span m="137073">use</span> <span m="137771">the</span>
  <span m="138469">constant</span> <span m="139166">version</span> <span m="139864">of</span>
  <span m="140562">the</span> <span m="141260">SHL</span> <span m="141596">operation</span>
  <span m="141933">since</span> <span m="142270">the</span> <span m="142607">amount</span>
  <span m="142944">to</span> <span m="143281">shift</span> <span m="143618">is</span>
  <span m="143955">given</span> <span m="144291">by</span> <span m="144628">a</span>
  <span m="144965">constant</span> <span m="145302">in</span> <span m="145639">our</span>
  <span m="145976">instruction</span> <span m="146313">rather</span> <span m="146650">than</span>
  <span m="147047">being</span> <span m="147444">read</span> <span m="147841">from</span>
  <span m="148238">another</span> <span m="148635">register.</span> <span m="149032">The</span>
  <span m="149429">next</span> <span m="149826">instruction</span> <span m="150223">is</span>
  <span m="150620">provided</span> <span m="151017">for</span> <span m="151414">us</span>
  <span m="151811">and</span> <span m="152209">it</span> <span m="152784">adds</span>
  <span m="153360">R0</span> <span m="153936">which</span> <span m="154511">equals</span>
  <span m="155087">2*c</span> <span m="155663">to</span> <span m="156238">R1</span>
  <span m="156814">which</span> <span m="157390">equals</span> <span m="157965">c</span>
  <span m="158541">in</span> <span m="159117">order</span> <span m="159692">to</span>
  <span m="160268">produce</span> <span m="160844">3*c.</span></p><p><span m="161420">This</span>
  <span m="161993">intermediate</span> <span m="162566">result</span> <span m="163139">is</span>
  <span m="163712">then</span> <span m="164286">stored</span> <span m="164859">back</span>
  <span m="165432">into</span> <span m="166005">R0.</span></p><p><span m="166579">Next</span>
  <span m="166871">we</span> <span m="167164">want</span> <span m="167457">to</span>
  <span m="167750">once</span> <span m="168043">again</span> <span m="168336">get</span>
  <span m="168629">the</span> <span m="168922">value</span> <span m="169215">of</span>
  <span m="169508">a</span> <span m="169801">variable</span> <span m="170094">from</span>
  <span m="170387">memory.</span></p><p><span m="170680">As</span> <span m="171133">we</span>
  <span m="171587">saw</span> <span m="172040">before,</span> <span m="172494">XXX</span>
  <span m="172948">=</span> <span m="173401">LD</span> <span m="173855">in</span>
  <span m="174309">order</span> <span m="174762">to</span> <span m="175216">load</span>
  <span m="175669">the</span> <span m="176123">contents</span> <span m="176577">of</span>
  <span m="177030">address</span> <span m="177484">b</span> <span m="177938">into</span>
  <span m="178391">register</span> <span m="178845">R1.</span></p><p><span m="179299">We</span>
  <span m="179682">are</span> <span m="180065">almost</span> <span m="180448">done,</span>
  <span m="180831">we</span> <span m="181215">now</span> <span m="181598">just</span>
  <span m="181981">need</span> <span m="182364">to</span> <span m="182748">add</span>
  <span m="183131">R1</span> <span m="183514">=</span> <span m="183897">b</span> <span
  m="184280">to</span> <span m="184664">R0</span> <span m="185047">=</span> <span
  m="185430">3*c</span> <span m="185813">and</span> <span m="186197">then</span> <span
  m="186580">store</span> <span m="186963">the</span> <span m="187346">result</span>
  <span m="187730">back</span> <span m="188198">into</span> <span m="188666">memory</span>
  <span m="189135">variable</span> <span m="189603">a.</span> <span m="190072">Since</span>
  <span m="190540">the</span> <span m="191009">store</span> <span m="191477">instruction</span>
  <span m="191946">is</span> <span m="192414">using</span> <span m="192883">R0</span>
  <span m="193351">as</span> <span m="193820">its</span> <span m="194183">source,</span>
  <span m="194546">that</span> <span m="194910">means</span> <span m="195273">that</span>
  <span m="195636">ZZZ</span> <span m="196000">must</span> <span m="196363">also</span>
  <span m="196726">be</span> <span m="197090">R0</span> <span m="197453">so</span>
  <span m="197816">that</span> <span m="198180">the</span> <span m="198543">correct</span>
  <span m="198906">value</span> <span m="199270">ends</span> <span m="199633">up</span>
  <span m="199996">in</span> <span m="200360">variable</span> <span m="200759">a.</span>
  <span m="201159">Next,</span> <span m="201559">we</span> <span m="201959">will</span>
  <span m="202359">take</span> <span m="202759">a</span> <span m="203159">look</span>
  <span m="203559">at</span> <span m="203959">how</span> <span m="204359">a</span>
  <span m="204759">conditional</span> <span m="205159">statement</span> <span m="205704">would</span>
  <span m="206250">be</span> <span m="206796">compiled</span> <span m="207342">into</span>
  <span m="207888">assembly</span> <span m="208434">language.</span></p><p><span m="208980">The</span>
  <span m="209396">statement</span> <span m="209812">says</span> <span m="210228">that</span>
  <span m="210644">if</span> <span m="211060">a</span> <span m="211476">is</span>
  <span m="211892">greater</span> <span m="212308">than</span> <span m="212725">b</span>
  <span m="213141">then</span> <span m="213557">c</span> <span m="213973">should</span>
  <span m="214389">be</span> <span m="214805">assigned</span> <span m="215221">the</span>
  <span m="215637">value</span> <span m="216053">17.</span></p><p><span m="216470">Once</span>
  <span m="216800">again</span> <span m="217130">we</span> <span m="217460">are</span>
  <span m="217790">given</span> <span m="218120">the</span> <span m="218450">semi-complete</span>
  <span m="218780">translation</span> <span m="219110">of</span> <span m="219440">the</span>
  <span m="219770">high</span> <span m="220100">level</span> <span m="220430">language</span>
  <span m="220760">code</span> <span m="221090">into</span> <span m="221524">beta</span>
  <span m="221959">assembly.</span> <span m="222393">For</span> <span m="222828">this</span>
  <span m="223262">example,</span> <span m="223697">we</span> <span m="224131">first</span>
  <span m="224566">load</span> <span m="225000">the</span> <span m="225435">values</span>
  <span m="225870">of</span> <span m="226450">our</span> <span m="227031">variables</span>
  <span m="227612">a</span> <span m="228193">and</span> <span m="228774">b</span>
  <span m="229355">into</span> <span m="229935">temporary</span> <span m="230516">registers</span>
  <span m="231097">R0</span> <span m="231678">and</span> <span m="232259">R1.</span></p><p><span
  m="232840">Now</span> <span m="233151">we</span> <span m="233462">want</span> <span
  m="233773">to</span> <span m="234084">check</span> <span m="234395">if</span> <span
  m="234706">a</span> <span m="235017">is</span> <span m="235328">greater</span> <span
  m="235639">than</span> <span m="235950">b</span> <span m="236261">and</span> <span
  m="236572">if</span> <span m="236883">so</span> <span m="237194">set</span> <span
  m="237505">c</span> <span m="237816">=</span> <span m="238127">17.</span></p><p><span
  m="238439">We</span> <span m="238857">know</span> <span m="239275">that</span> <span
  m="239694">XXX</span> <span m="240112">must</span> <span m="240530">be</span> <span
  m="240949">some</span> <span m="241367">kind</span> <span m="241785">of</span> <span
  m="242204">beta</span> <span m="242622">comparison</span> <span m="243040">operation.</span></p><p><span
  m="243459">However,</span> <span m="243839">the</span> <span m="244219">beta</span>
  <span m="244599">does</span> <span m="244979">not</span> <span m="245359">provide</span>
  <span m="245739">a</span> <span m="246119">compare</span> <span m="246499">greater</span>
  <span m="246879">than</span> <span m="247259">operation,</span> <span m="247639">so</span>
  <span m="248019">instead</span> <span m="248399">we</span> <span m="248779">need</span>
  <span m="249160">to</span> <span m="249518">make</span> <span m="249876">use</span>
  <span m="250234">of</span> <span m="250592">the</span> <span m="250951">compare</span>
  <span m="251309">less</span> <span m="251667">than</span> <span m="252025">(CMPLT)</span>
  <span m="252384">or</span> <span m="252742">compare</span> <span m="253100">less</span>
  <span m="253458">than</span> <span m="253817">or</span> <span m="254175">equal</span>
  <span m="254533">(CMPLE)</span> <span m="254891">operations.</span></p><p><span
  m="255250">Since</span> <span m="255628">we</span> <span m="256006">see</span> <span
  m="256385">that</span> <span m="256763">the</span> <span m="257141">store</span>
  <span m="257520">into</span> <span m="257898">label</span> <span m="258276">c</span>
  <span m="258655">is</span> <span m="259033">skipped</span> <span m="259411">when</span>
  <span m="259790">the</span> <span m="260168">code</span> <span m="260546">branches</span>
  <span m="260925">to</span> <span m="261303">label</span> <span m="261681">_L2,</span>
  <span m="262060">we</span> <span m="262379">want</span> <span m="262698">to</span>
  <span m="263018">make</span> <span m="263337">sure</span> <span m="263657">that</span>
  <span m="263976">the</span> <span m="264295">branch</span> <span m="264615">is</span>
  <span m="264934">not</span> <span m="265254">taken</span> <span m="265573">when</span>
  <span m="265892">a</span> <span m="266212">is</span> <span m="266531">greater</span>
  <span m="266851">than</span> <span m="267170">b.</span></p><p><span m="267490">This</span>
  <span m="267778">is</span> <span m="268066">equivalent</span> <span m="268354">to</span>
  <span m="268642">the</span> <span m="268930">branch</span> <span m="269219">being</span>
  <span m="269507">taken</span> <span m="269795">when</span> <span m="270083">a</span>
  <span m="270371">is</span> <span m="270659">less</span> <span m="270948">than</span>
  <span m="271236">or</span> <span m="271524">equal</span> <span m="271812">to</span>
  <span m="272100">b.</span></p><p><span m="272389">So</span> <span m="272940">if</span>
  <span m="273492">we</span> <span m="274043">make</span> <span m="274595">XXX</span>
  <span m="275146">=</span> <span m="275698">CMPLE</span> <span m="276249">of</span>
  <span m="276801">R0,</span> <span m="277352">which</span> <span m="277904">equals</span>
  <span m="278456">a,</span> <span m="279007">and</span> <span m="279559">R1,</span>
  <span m="280110">which</span> <span m="280662">equals</span> <span m="281213">b,</span>
  <span m="281765">then</span> <span m="282316">the</span> <span m="282868">result</span>
  <span m="283420">stored</span> <span m="283911">into</span> <span m="284403">R0</span>
  <span m="284895">will</span> <span m="285387">be</span> <span m="285879">1</span>
  <span m="286371">if</span> <span m="286863">a</span> <span m="287355">&lt;=</span>
  <span m="287847">b.</span> <span m="288339">We</span> <span m="288830">then</span>
  <span m="289322">set</span> <span m="289814">YYY</span> <span m="290306">to</span>
  <span m="290798">R0</span> <span m="291290">to</span> <span m="291782">ensure</span>
  <span m="292274">that</span> <span m="292766">we</span> <span m="293258">take</span>
  <span m="293750">the</span> <span m="295110">branch</span> <span m="296470">when</span>
  <span m="297830">a</span> <span m="299190">b.</span></p><p><span m="300550">Finally,</span>
  <span m="301021">if</span> <span m="301493">we</span> <span m="301964">set</span>
  <span m="302436">ZZZ</span> <span m="302907">=</span> <span m="303379">17,</span>
  <span m="303850">then</span> <span m="304322">when</span> <span m="304793">the</span>
  <span m="305265">branch</span> <span m="305736">is</span> <span m="306208">not</span>
  <span m="306679">taken,</span> <span m="307151">we</span> <span m="307622">will</span>
  <span m="308094">move</span> <span m="308565">17</span> <span m="309037">into</span>
  <span m="309509">R0</span> <span m="309990">and</span> <span m="310472">then</span>
  <span m="310953">store</span> <span m="311435">that</span> <span m="311916">value</span>
  <span m="312398">into</span> <span m="312879">the</span> <span m="313361">location</span>
  <span m="313842">pointed</span> <span m="314324">to</span> <span m="314805">by</span>
  <span m="315287">address</span> <span m="315768">c.</span></p><p><span m="316250">So</span>
  <span m="316904">the</span> <span m="317559">complete</span> <span m="318214">translation</span>
  <span m="318869">of</span> <span m="319524">this</span> <span m="320179">conditional</span>
  <span m="320834">statement</span> <span m="321489">to</span> <span m="322144">beta</span>
  <span m="322799">assembly</span> <span m="323454">is</span> <span m="324109">shown</span>
  <span m="324764">here.</span></p><p><span m="325419">For</span> <span m="325646">this</span>
  <span m="325873">next</span> <span m="326100">code</span> <span m="326327">segment,</span>
  <span m="326555">we</span> <span m="326782">are</span> <span m="327009">going</span>
  <span m="327236">to</span> <span m="327464">take</span> <span m="327691">a</span>
  <span m="327918">look</span> <span m="328145">at</span> <span m="328372">how</span>
  <span m="328600">a</span> <span m="328827">compiler</span> <span m="329054">would</span>
  <span m="329281">convert</span> <span m="329509">array</span> <span m="329987">accesses</span>
  <span m="330465">into</span> <span m="330944">beta</span> <span m="331422">code.</span>
  <span m="331901">Once</span> <span m="332379">again</span> <span m="332857">we</span>
  <span m="333336">are</span> <span m="333814">given</span> <span m="334293">partially</span>
  <span m="334771">completed</span> <span m="335250">assembly</span> <span m="335612">code</span>
  <span m="335975">to</span> <span m="336338">help</span> <span m="336700">us</span>
  <span m="337063">understand</span> <span m="337426">how</span> <span m="337788">the</span>
  <span m="338151">compiler</span> <span m="338514">translates</span> <span m="338876">this</span>
  <span m="339239">high</span> <span m="339602">level</span> <span m="339964">code</span>
  <span m="340327">into</span> <span m="340690">beta</span> <span m="341034">assembly.</span>
  <span m="341378">We</span> <span m="341722">begin</span> <span m="342066">with</span>
  <span m="342410">a</span> <span m="342754">load</span> <span m="343098">of</span>
  <span m="343442">the</span> <span m="343786">value</span> <span m="344130">stored</span>
  <span m="344474">at</span> <span m="344819">location</span> <span m="345359">i</span>
  <span m="345899">into</span> <span m="346439">register</span> <span m="346979">R0.</span>
  <span m="347519">I</span> <span m="348059">is</span> <span m="348599">the</span>
  <span m="349139">index</span> <span m="349679">into</span> <span m="350219">our</span>
  <span m="350759">array.</span></p><p><span m="351300">However,</span> <span m="351658">since</span>
  <span m="352017">the</span> <span m="352376">beta</span> <span m="352734">is</span>
  <span m="353093">byte</span> <span m="353452">addressed,</span> <span m="353810">but</span>
  <span m="354169">it</span> <span m="354528">deals</span> <span m="354886">with</span>
  <span m="355245">32</span> <span m="355604">bit</span> <span m="355962">values,</span>
  <span m="356321">that</span> <span m="356680">means</span> <span m="357039">that</span>
  <span m="357492">each</span> <span m="357945">array</span> <span m="358399">element</span>
  <span m="358852">requires</span> <span m="359306">4</span> <span m="359759">bytes</span>
  <span m="360213">of</span> <span m="360666">storage.</span></p><p><span m="361120">So</span>
  <span m="361541">in</span> <span m="361963">order</span> <span m="362385">to</span>
  <span m="362806">point</span> <span m="363228">to</span> <span m="363650">the</span>
  <span m="364071">correct</span> <span m="364493">location</span> <span m="364915">in</span>
  <span m="365336">memory,</span> <span m="365758">we</span> <span m="366180">need</span>
  <span m="366601">to</span> <span m="367023">multiply</span> <span m="367445">i</span>
  <span m="367866">by</span> <span m="368288">4.</span></p><p><span m="368710">As</span>
  <span m="369030">we</span> <span m="369351">saw</span> <span m="369671">earlier,</span>
  <span m="369992">shifting</span> <span m="370313">to</span> <span m="370633">the</span>
  <span m="370954">left</span> <span m="371274">by</span> <span m="371595">1</span>
  <span m="371916">bit</span> <span m="372236">is</span> <span m="372557">equivalent</span>
  <span m="372877">to</span> <span m="373198">multiplying</span> <span m="373519">by</span>
  <span m="373839">2,</span> <span m="374160">so</span> <span m="374481">here</span>
  <span m="374828">we</span> <span m="375175">shift</span> <span m="375522">to</span>
  <span m="375870">the</span> <span m="376217">left</span> <span m="376564">by</span>
  <span m="376911">2</span> <span m="377259">bits</span> <span m="377606">in</span>
  <span m="377953">order</span> <span m="378300">to</span> <span m="378648">multiply</span>
  <span m="378995">by</span> <span m="379342">4.</span></p><p><span m="379690">So</span>
  <span m="380449">XXX</span> <span m="381208">=</span> <span m="381968">2.</span>
  <span m="382727">Now</span> <span m="383486">that</span> <span m="384246">R0</span>
  <span m="385005">=</span> <span m="385765">4</span> <span m="386524">*</span> <span
  m="387283">i,</span> <span m="388043">in</span> <span m="388802">order</span> <span
  m="389561">to</span> <span m="390321">load</span> <span m="391080">a[i],</span>
  <span m="391840">we</span> <span m="392283">would</span> <span m="392726">load</span>
  <span m="393169">the</span> <span m="393613">location</span> <span m="394056">a</span>
  <span m="394499">+</span> <span m="394942">4*i.</span> <span m="395386">In</span>
  <span m="395829">order</span> <span m="396272">to</span> <span m="396716">load</span>
  <span m="397159">a[i-1],</span> <span m="397602">we</span> <span m="398045">need</span>
  <span m="398489">to</span> <span m="398932">load</span> <span m="399375">the</span>
  <span m="399819">location</span> <span m="400399">that</span> <span m="400979">is</span>
  <span m="401559">4</span> <span m="402139">bytes</span> <span m="402719">before</span>
  <span m="403299">that,</span> <span m="403879">so</span> <span m="404459">location</span>
  <span m="405039">a</span> <span m="405619">+</span> <span m="406199">4*i</span>
  <span m="406779">&ndash;</span> <span m="407359">4.</span></p><p><span m="407940">This</span>
  <span m="408338">means</span> <span m="408736">that</span> <span m="409134">in</span>
  <span m="409532">this</span> <span m="409930">load</span> <span m="410328">operation</span>
  <span m="410726">which</span> <span m="411125">actually</span> <span m="411523">wants</span>
  <span m="411921">to</span> <span m="412319">load</span> <span m="412717">a[i-1],</span>
  <span m="413115">we</span> <span m="413513">need</span> <span m="413911">to</span>
  <span m="414310">set</span> <span m="415138">YYY</span> <span m="415966">=</span>
  <span m="416794">a-4.</span> <span m="417622">So</span> <span m="418450">this</span>
  <span m="419278">load</span> <span m="420106">operation</span> <span m="420934">places</span>
  <span m="421762">array</span> <span m="422590">element</span> <span m="423419">a[i-1]</span>
  <span m="424076">into</span> <span m="424734">R1.</span> <span m="425392">Now</span>
  <span m="426050">we</span> <span m="426707">want</span> <span m="427365">to</span>
  <span m="428023">store</span> <span m="428681">the</span> <span m="429338">contents</span>
  <span m="429996">of</span> <span m="430654">R1</span> <span m="431312">into</span>
  <span m="431970">array</span> <span m="432528">element</span> <span m="433086">a[i]</span>
  <span m="433644">which</span> <span m="434202">is</span> <span m="434760">located</span>
  <span m="435319">at</span> <span m="435877">address</span> <span m="436435">a</span>
  <span m="436993">+</span> <span m="437551">4*i.</span></p><p><span m="438110">Since</span>
  <span m="438533">R0</span> <span m="438957">already</span> <span m="439381">equals</span>
  <span m="439804">4*i,</span> <span m="440228">then</span> <span m="440652">adding</span>
  <span m="441075">a</span> <span m="441499">to</span> <span m="441923">R0</span>
  <span m="442346">will</span> <span m="442770">give</span> <span m="443194">us</span>
  <span m="443617">the</span> <span m="444041">desired</span> <span m="444465">destination</span>
  <span m="444889">address</span> <span m="445226">of</span> <span m="445563">our</span>
  <span m="445900">store.</span> <span m="446237">This</span> <span m="446575">means</span>
  <span m="446912">that</span> <span m="447249">we</span> <span m="447586">just</span>
  <span m="447923">need</span> <span m="448261">to</span> <span m="448598">set</span>
  <span m="448935">ZZZ</span> <span m="449272">to</span> <span m="449610">R1</span>
  <span m="450225">since</span> <span m="450840">that</span> <span m="451456">is</span>
  <span m="452071">the</span> <span m="452686">value</span> <span m="453302">that</span>
  <span m="453917">we</span> <span m="454533">want</span> <span m="455148">to</span>
  <span m="455763">store</span> <span m="456379">into</span> <span m="456994">a[i].</span></p><p><span
  m="457610">Let's</span> <span m="457963">take</span> <span m="458317">a</span> <span
  m="458670">look</span> <span m="459024">at</span> <span m="459377">one</span> <span
  m="459731">last</span> <span m="460084">example.</span> <span m="460438">Here</span>
  <span m="460791">we</span> <span m="461145">have</span> <span m="461498">a</span>
  <span m="461852">variable</span> <span m="462205">sum</span> <span m="462559">that</span>
  <span m="462912">is</span> <span m="463266">initialized</span> <span m="463620">to</span>
  <span m="463994">0,</span> <span m="464369">followed</span> <span m="464743">by</span>
  <span m="465118">a</span> <span m="465492">loop</span> <span m="465867">that</span>
  <span m="466241">increments</span> <span m="466616">the</span> <span m="466990">value</span>
  <span m="467365">of</span> <span m="467739">sum</span> <span m="468114">by</span>
  <span m="468488">i</span> <span m="468863">for</span> <span m="469237">every</span>
  <span m="469612">value</span> <span m="469986">of</span> <span m="470361">i</span>
  <span m="470735">between</span> <span m="471110">0</span> <span m="471699">and</span>
  <span m="472289">9.</span> <span m="472879">Our</span> <span m="473469">partial</span>
  <span m="474059">mostly</span> <span m="474649">completed</span> <span m="475239">compiled</span>
  <span m="475829">code</span> <span m="476419">is</span> <span m="476804">shown</span>
  <span m="477189">here.</span> <span m="477575">The</span> <span m="477960">first</span>
  <span m="478346">thing</span> <span m="478731">that</span> <span m="479117">the</span>
  <span m="479502">compiler</span> <span m="479888">does,</span> <span m="480273">is</span>
  <span m="480659">it</span> <span m="481103">initializes</span> <span m="481547">the</span>
  <span m="481991">two</span> <span m="482435">variables</span> <span m="482879">sum</span>
  <span m="483323">and</span> <span m="483767">i</span> <span m="484211">to</span>
  <span m="484655">0.</span></p><p><span m="485099">This</span> <span m="485460">is</span>
  <span m="485821">done</span> <span m="486182">by</span> <span m="486543">storing</span>
  <span m="486904">the</span> <span m="487265">value</span> <span m="487626">of</span>
  <span m="487987">register</span> <span m="488348">R31,</span> <span m="488710">which</span>
  <span m="489071">is</span> <span m="489432">always</span> <span m="489793">0</span>
  <span m="490154">in</span> <span m="490515">the</span> <span m="490876">beta,</span>
  <span m="491237">into</span> <span m="491598">the</span> <span m="491960">locations</span>
  <span m="492365">pointed</span> <span m="492771">to</span> <span m="493176">by</span>
  <span m="493582">sum</span> <span m="493987">and</span> <span m="494393">by</span>
  <span m="494798">i.</span> <span m="495204">_L7</span> <span m="495610">is</span>
  <span m="496015">a</span> <span m="496421">label</span> <span m="496826">that</span>
  <span m="497232">indicates</span> <span m="497637">the</span> <span m="498043">beginning</span>
  <span m="498449">of</span> <span m="498729">our</span> <span m="499009">loop.</span>
  <span m="499289">The</span> <span m="499569">first</span> <span m="499849">thing</span>
  <span m="500129">that</span> <span m="500409">needs</span> <span m="500689">to</span>
  <span m="500969">happen</span> <span m="501249">in</span> <span m="501529">the</span>
  <span m="501810">loop</span> <span m="502168">is</span> <span m="502526">to</span>
  <span m="502885">load</span> <span m="503243">the</span> <span m="503602">current</span>
  <span m="503960">values</span> <span m="504319">of</span> <span m="504677">sum</span>
  <span m="505036">and</span> <span m="505394">i</span> <span m="505753">from</span>
  <span m="506111">memory.</span></p><p><span m="506470">Next,</span> <span m="506933">sum</span>
  <span m="507397">should</span> <span m="507861">be</span> <span m="508325">incremented</span>
  <span m="508788">by</span> <span m="509252">i.</span> <span m="509716">Since</span>
  <span m="510180">R0</span> <span m="510643">is</span> <span m="511107">stored</span>
  <span m="511571">back</span> <span m="512035">into</span> <span m="512498">sum,</span>
  <span m="512962">we</span> <span m="513426">want</span> <span m="513890">XXX</span>
  <span m="514409">=</span> <span m="514928">R0</span> <span m="515447">to</span>
  <span m="515966">be</span> <span m="516485">the</span> <span m="517004">destination</span>
  <span m="517523">register</span> <span m="518042">of</span> <span m="518561">the</span>
  <span m="519080">ADD.</span></p><p><span m="519600">Now</span> <span m="519951">the</span>
  <span m="520302">loop</span> <span m="520653">index</span> <span m="521004">needs</span>
  <span m="521355">to</span> <span m="521706">be</span> <span m="522057">incremented.</span>
  <span m="522408">Since</span> <span m="522759">R1</span> <span m="523110">=</span>
  <span m="523461">i,</span> <span m="523812">that</span> <span m="524163">means</span>
  <span m="524514">that</span> <span m="524865">we</span> <span m="525216">want</span>
  <span m="525567">to</span> <span m="525918">increment</span> <span m="526270">R1</span>
  <span m="526803">by</span> <span m="527337">1,so</span> <span m="527871">YYY</span>
  <span m="528405">=</span> <span m="528939">R1.</span> <span m="529473">Finally,</span>
  <span m="530006">we</span> <span m="530540">need</span> <span m="531074">to</span>
  <span m="531608">determine</span> <span m="532142">whether</span> <span m="532676">the</span>
  <span m="533210">loop</span> <span m="533507">needs</span> <span m="533804">to</span>
  <span m="534101">be</span> <span m="534398">repeated</span> <span m="534696">or</span>
  <span m="534993">we</span> <span m="535290">are</span> <span m="535587">done.</span>
  <span m="535885">This</span> <span m="536182">is</span> <span m="536479">done</span>
  <span m="536776">by</span> <span m="537073">checking</span> <span m="537371">whether</span>
  <span m="537668">i</span> <span m="537965">is</span> <span m="538262">less</span>
  <span m="538560">than</span> <span m="539101">10.</span> <span m="539642">The</span>
  <span m="540183">beta</span> <span m="540724">provides</span> <span m="541265">the</span>
  <span m="541806">CMPLTC</span> <span m="542347">operation</span> <span m="542888">to</span>
  <span m="543430">do</span> <span m="543895">just</span> <span m="544360">that.</span>
  <span m="544825">Since</span> <span m="545290">R1</span> <span m="545755">holds</span>
  <span m="546220">the</span> <span m="546685">latest</span> <span m="547150">value</span>
  <span m="547615">of</span> <span m="548080">i,</span> <span m="548545">comparing</span>
  <span m="549010">R1</span> <span m="549383">to</span> <span m="549756">the</span>
  <span m="550129">constant</span> <span m="550502">10</span> <span m="550875">will</span>
  <span m="551248">produce</span> <span m="551621">the</span> <span m="551994">result</span>
  <span m="552367">we</span> <span m="552740">want</span> <span m="553113">in</span>
  <span m="553486">R0.</span></p><p><span m="553860">So</span> <span m="554392">ZZZ</span>
  <span m="554924">=</span> <span m="555456">10.</span> <span m="555989">If</span>
  <span m="556521">the</span> <span m="557053">comparison</span> <span m="557586">was</span>
  <span m="558118">true,</span> <span m="558650">then</span> <span m="559183">we</span>
  <span m="559715">need</span> <span m="560247">to</span> <span m="560780">repeat</span>
  <span m="561172">the</span> <span m="561565">loop</span> <span m="561958">so</span>
  <span m="562351">we</span> <span m="562744">branch</span> <span m="563137">back</span>
  <span m="563530">to</span> <span m="563923">_L7.</span> <span m="564316">If</span>
  <span m="564709">not,</span> <span m="565102">we</span> <span m="565495">proceed</span>
  <span m="565888">to</span> <span m="566281">the</span> <span m="566674">instruction</span>
  <span m="567067">after</span> <span m="567460">the</span> <span m="567860">branch.</span></p>
type: course
uid: c1b50830748cc9951d800120d9ec547b

---
None