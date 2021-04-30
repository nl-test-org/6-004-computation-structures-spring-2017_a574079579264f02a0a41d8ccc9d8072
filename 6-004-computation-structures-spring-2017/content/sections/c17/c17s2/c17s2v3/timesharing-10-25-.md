---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: R7U0Xezxo_0
  parent_uid: e3a74e70ae786399be705c445e9bd040
  title: Video-YouTube-Stream
  type: Video
  uid: 810fdcd48c07484c8aff2222ced30f6b
- id: 3Play-3Play YouTube id-Stream
  media_location: R7U0Xezxo_0
  parent_uid: e3a74e70ae786399be705c445e9bd040
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: c379f4854890ffaad3b7a93430c4147b
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/R7U0Xezxo_0/default.jpg
  parent_uid: e3a74e70ae786399be705c445e9bd040
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: f526a47794b1fc4254b78f9a8d2531f3
- id: R7U0Xezxo_0.srt
  parent_uid: e3a74e70ae786399be705c445e9bd040
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v3/timesharing-10-25-/R7U0Xezxo_0.srt
  title: 3play caption file
  type: null
  uid: c42e9e4d5e8607a9a81ebeeaeee0c1e4
- id: R7U0Xezxo_0.pdf
  parent_uid: e3a74e70ae786399be705c445e9bd040
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v3/timesharing-10-25-/R7U0Xezxo_0.pdf
  title: 3play pdf file
  type: null
  uid: f99f9fc9ec233bda6e714bd2961ef1e1
- id: Caption-3Play YouTube id-SRT
  parent_uid: e3a74e70ae786399be705c445e9bd040
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 42d73cafa23e36c2d32cc156f529170d
- id: Transcript-3Play YouTube id-PDF
  parent_uid: e3a74e70ae786399be705c445e9bd040
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 473eba4312e7aa934843025d691ea830
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_17-02-03_300k.mp4
  parent_uid: e3a74e70ae786399be705c445e9bd040
  title: Video-Internet Archive-MP4
  type: Video
  uid: f1adead0b729867e972c3ef3d88f79a9
inline_embed_id: 50572214timesharing102554916677
layout: video
order_index: null
parent_uid: 3b6e4fa7ea1f4273ed12c8a6319809a9
related_resources_text: ''
short_url: timesharing-10-25-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v3/timesharing-10-25-
template_type: Embed
title: Timesharing
transcript: <p><span m="539">A</span> <span m="921">key</span> <span m="1303">technology</span>
  <span m="1685">for</span> <span m="2067">timesharing</span> <span m="2450">is</span>
  <span m="2832">the</span> <span m="3214">periodic</span> <span m="3596">interrupt</span>
  <span m="3978">from</span> <span m="4361">the</span> <span m="4743">external</span>
  <span m="5125">timer</span> <span m="5507">device.</span></p><p><span m="5890">Let's</span>
  <span m="6395">remind</span> <span m="6900">ourselves</span> <span m="7406">how</span>
  <span m="7911">the</span> <span m="8417">interrupt</span> <span m="8922">hardware</span>
  <span m="9428">in</span> <span m="9933">the</span> <span m="10439">Beta</span> <span
  m="10944">works.</span></p><p><span m="11450">External</span> <span m="11864">devices</span>
  <span m="12279">request</span> <span m="12693">an</span> <span m="13108">interrupt</span>
  <span m="13523">by</span> <span m="13937">asserting</span> <span m="14352">the</span>
  <span m="14766">Beta's</span> <span m="15181">interrupt</span> <span m="15596">request</span>
  <span m="16010">(IRQ)</span> <span m="16425">input.</span></p><p><span m="16840">If</span>
  <span m="17158">the</span> <span m="17476">Beta</span> <span m="17795">is</span>
  <span m="18113">running</span> <span m="18431">in</span> <span m="18750">user</span>
  <span m="19068">mode,</span> <span m="19386">i.e.,</span> <span m="19705">the</span>
  <span m="20023">supervisor</span> <span m="20341">bit</span> <span m="20660">stored</span>
  <span m="20978">in</span> <span m="21296">the</span> <span m="21615">PC</span> <span
  m="21933">is</span> <span m="22251">0,</span> <span m="22570">asserting</span> <span
  m="23037">IRQ</span> <span m="23504">will</span> <span m="23971">trigger</span>
  <span m="24439">the</span> <span m="24906">following</span> <span m="25373">actions</span>
  <span m="25840">on</span> <span m="26308">the</span> <span m="26775">clock</span>
  <span m="27242">cycle</span> <span m="27709">the</span> <span m="28177">interrupt</span>
  <span m="28644">is</span> <span m="29111">recognized.</span></p><p><span m="29579">The</span>
  <span m="29892">goal</span> <span m="30206">is</span> <span m="30520">to</span>
  <span m="30834">save</span> <span m="31148">the</span> <span m="31462">current</span>
  <span m="31776">PC+4</span> <span m="32090">value</span> <span m="32404">in</span>
  <span m="32718">the</span> <span m="33032">XP</span> <span m="33346">register</span>
  <span m="33660">and</span> <span m="33974">force</span> <span m="34288">the</span>
  <span m="34602">program</span> <span m="34916">counter</span> <span m="35230">(PC)</span>
  <span m="35609">to</span> <span m="35988">a</span> <span m="36367">particular</span>
  <span m="36746">kernel-mode</span> <span m="37126">instruction,</span> <span m="37505">which</span>
  <span m="37884">starts</span> <span m="38263">the</span> <span m="38643">execution</span>
  <span m="39022">of</span> <span m="39401">the</span> <span m="39780">interrupt</span>
  <span m="40160">handler</span> <span m="41120">code.</span></p><p><span m="42080">The</span>
  <span m="42415">normal</span> <span m="42751">process</span> <span m="43087">of</span>
  <span m="43422">generating</span> <span m="43758">control</span> <span m="44094">signals</span>
  <span m="44430">based</span> <span m="44765">on</span> <span m="45101">the</span>
  <span m="45437">current</span> <span m="45772">instruction</span> <span m="46108">is</span>
  <span m="46444">superseded</span> <span m="46780">by</span> <span m="47282">forcing</span>
  <span m="47784">particular</span> <span m="48286">values</span> <span m="48788">for</span>
  <span m="49290">some</span> <span m="49792">of</span> <span m="50294">the</span>
  <span m="50796">control</span> <span m="51298">signals.</span></p><p><span m="51800">PCSEL</span>
  <span m="52112">is</span> <span m="52424">set</span> <span m="52737">to</span> <span
  m="53049">4,</span> <span m="53361">which</span> <span m="53674">selects</span>
  <span m="53986">a</span> <span m="54298">specified</span> <span m="54611">kernel-mode</span>
  <span m="54923">address</span> <span m="55235">as</span> <span m="55548">the</span>
  <span m="55860">next</span> <span m="56172">value</span> <span m="56485">of</span>
  <span m="56797">the</span> <span m="57110">program</span> <span m="58070">counter.</span></p><p><span
  m="59030">The</span> <span m="59367">address</span> <span m="59704">chosen</span>
  <span m="60041">depends</span> <span m="60378">on</span> <span m="60715">the</span>
  <span m="61052">type</span> <span m="61389">of</span> <span m="61726">external</span>
  <span m="62063">interrupt.</span></p><p><span m="62400">In</span> <span m="63039">the</span>
  <span m="63678">case</span> <span m="64317">of</span> <span m="64956">the</span>
  <span m="65595">timer</span> <span m="66234">interrupt,</span> <span m="66873">the</span>
  <span m="67512">address</span> <span m="68151">is</span> <span m="68790">0x80000008.</span></p><p><span
  m="69430">Note</span> <span m="69743">that</span> <span m="70056">PC[31],</span>
  <span m="70370">the</span> <span m="70683">supervisor</span> <span m="70996">bit,</span>
  <span m="71310">is</span> <span m="71623">being</span> <span m="71936">set</span>
  <span m="72250">to</span> <span m="72563">1</span> <span m="72876">and</span> <span
  m="73190">the</span> <span m="73503">CPU</span> <span m="73816">will</span> <span
  m="74130">be</span> <span m="74443">in</span> <span m="74756">kernel-mode</span>
  <span m="75070">as</span> <span m="75531">it</span> <span m="75992">starts</span>
  <span m="76453">executing</span> <span m="76914">the</span> <span m="77375">code</span>
  <span m="77836">of</span> <span m="78297">the</span> <span m="78758">interrupt</span>
  <span m="79219">handler.</span></p><p><span m="79680">The</span> <span m="80063">WASEL,</span>
  <span m="80447">WDSEL,</span> <span m="80830">and</span> <span m="81214">WERF</span>
  <span m="81597">control</span> <span m="81981">signals</span> <span m="82364">are</span>
  <span m="82748">set</span> <span m="83131">so</span> <span m="83515">that</span>
  <span m="83898">PC+4</span> <span m="84282">is</span> <span m="84665">written</span>
  <span m="85049">into</span> <span m="85432">the</span> <span m="85816">XP</span>
  <span m="86200">register</span> <span m="86795">(i.e.,</span> <span m="87391">R30)</span>
  <span m="87987">in</span> <span m="88582">the</span> <span m="89178">register</span>
  <span m="89774">file.</span></p><p><span m="90370">And,</span> <span m="90757">finally,</span>
  <span m="91144">MWR</span> <span m="91531">is</span> <span m="91918">set</span>
  <span m="92305">to</span> <span m="92692">0</span> <span m="93079">to</span> <span
  m="93466">ensure</span> <span m="93853">that</span> <span m="94240">if</span> <span
  m="94627">we're</span> <span m="95014">interrupting</span> <span m="95401">a</span>
  <span m="95788">ST</span> <span m="96175">instruction</span> <span m="96562">that</span>
  <span m="96950">its</span> <span m="97460">execution</span> <span m="97970">is</span>
  <span m="98480">aborted</span> <span m="98990">correctly.</span></p><p><span m="99500">So</span>
  <span m="99852">in</span> <span m="100205">the</span> <span m="100557">next</span>
  <span m="100910">clock</span> <span m="101263">cycle,</span> <span m="101615">execution</span>
  <span m="101968">starts</span> <span m="102320">with</span> <span m="102673">the</span>
  <span m="103026">first</span> <span m="103378">instruction</span> <span m="103731">of</span>
  <span m="104083">the</span> <span m="104436">kernel-mode</span> <span m="104789">interrupt</span>
  <span m="105188">handler,</span> <span m="105587">which</span> <span m="105986">can</span>
  <span m="106385">find</span> <span m="106784">the</span> <span m="107183">PC+4</span>
  <span m="107582">of</span> <span m="107981">the</span> <span m="108380">interrupted</span>
  <span m="108780">instruction</span> <span m="109348">in</span> <span m="109917">the</span>
  <span m="110486">XP</span> <span m="111055">register</span> <span m="111623">of</span>
  <span m="112192">the</span> <span m="112761">CPU.</span></p><p><span m="113330">As</span>
  <span m="113683">we</span> <span m="114036">can</span> <span m="114389">see</span>
  <span m="114742">the</span> <span m="115095">interrupt</span> <span m="115448">hardware</span>
  <span m="115801">is</span> <span m="116154">pretty</span> <span m="116507">minimal:</span>
  <span m="116860">it</span> <span m="117211">saves</span> <span m="117562">the</span>
  <span m="117913">PC+4</span> <span m="118264">of</span> <span m="118615">the</span>
  <span m="118967">interrupted</span> <span m="119318">user-mode</span> <span m="119669">program</span>
  <span m="120020">in</span> <span m="120371">the</span> <span m="120722">XP</span>
  <span m="121074">register</span> <span m="121425">and</span> <span m="121776">sets</span>
  <span m="122127">the</span> <span m="122478">program</span> <span m="122830">counter</span>
  <span m="123374">to</span> <span m="123919">some</span> <span m="124464">predetermined</span>
  <span m="125009">value</span> <span m="125554">that</span> <span m="126099">depends</span>
  <span m="126644">on</span> <span m="127189">which</span> <span m="127734">external</span>
  <span m="128279">interrupt</span> <span m="128824">happened.</span></p><p><span
  m="129369">The</span> <span m="129669">remainder</span> <span m="129969">of</span>
  <span m="130269">the</span> <span m="130569">work</span> <span m="130869">to</span>
  <span m="131169">handle</span> <span m="131469">the</span> <span m="131769">interrupt</span>
  <span m="132069">request</span> <span m="132369">is</span> <span m="132669">performed</span>
  <span m="132969">in</span> <span m="133269">software.</span></p><p><span m="133569">The</span>
  <span m="133989">state</span> <span m="134409">of</span> <span m="134829">the</span>
  <span m="135249">interrupted</span> <span m="135669">process,</span> <span m="136089">e.g.,</span>
  <span m="136509">the</span> <span m="136929">values</span> <span m="137349">in</span>
  <span m="137769">the</span> <span m="138189">CPU</span> <span m="138609">registers</span>
  <span m="139029">R0</span> <span m="139449">through</span> <span m="139870">R30,</span>
  <span m="140251">is</span> <span m="140632">stored</span> <span m="141014">in</span>
  <span m="141395">main</span> <span m="141777">memory</span> <span m="142158">in</span>
  <span m="142540">an</span> <span m="142921">OS</span> <span m="143303">data</span>
  <span m="143684">structure</span> <span m="144066">called</span> <span m="144447">UserMState.</span></p><p><span
  m="144829">Then</span> <span m="145187">the</span> <span m="145546">appropriate</span>
  <span m="145905">handler</span> <span m="146263">code,</span> <span m="146622">usually</span>
  <span m="146981">a</span> <span m="147339">procedure</span> <span m="147698">written</span>
  <span m="148057">in</span> <span m="148415">C,</span> <span m="148774">is</span>
  <span m="149133">invoked</span> <span m="149491">to</span> <span m="149850">do</span>
  <span m="150209">the</span> <span m="150822">heavy</span> <span m="151435">lifting.</span></p><p><span
  m="152049">When</span> <span m="152485">that</span> <span m="152921">procedure</span>
  <span m="153358">returns,</span> <span m="153794">the</span> <span m="154230">process</span>
  <span m="154667">state</span> <span m="155103">is</span> <span m="155539">reloaded</span>
  <span m="155976">from</span> <span m="156412">UserMState.</span></p><p><span m="156849">The</span>
  <span m="157283">OS</span> <span m="157718">subtracts</span> <span m="158153">4</span>
  <span m="158587">from</span> <span m="159022">the</span> <span m="159457">value</span>
  <span m="159891">in</span> <span m="160326">XP,</span> <span m="160761">making</span>
  <span m="161196">it</span> <span m="161630">point</span> <span m="162065">to</span>
  <span m="162500">the</span> <span m="162934">interrupted</span> <span m="163369">instruction</span>
  <span m="163804">and</span> <span m="164239">then</span> <span m="164980">resumes</span>
  <span m="165722">user-mode</span> <span m="166463">execution</span> <span m="167205">with</span>
  <span m="167946">a</span> <span m="168688">JMP(XP).</span></p><p><span m="169430">Note</span>
  <span m="169763">that</span> <span m="170097">in</span> <span m="170430">our</span>
  <span m="170764">simple</span> <span m="171097">Beta</span> <span m="171431">implementation</span>
  <span m="171764">the</span> <span m="172098">first</span> <span m="172431">instructions</span>
  <span m="172765">for</span> <span m="173098">the</span> <span m="173432">various</span>
  <span m="173765">interrupt</span> <span m="174099">handlers</span> <span m="174646">occupy</span>
  <span m="175193">consecutive</span> <span m="175740">locations</span> <span m="176288">in</span>
  <span m="176835">main</span> <span m="177382">memory.</span></p><p><span m="177930">Since</span>
  <span m="178357">interrupt</span> <span m="178785">handlers</span> <span m="179212">are</span>
  <span m="179640">longer</span> <span m="180068">than</span> <span m="180495">one</span>
  <span m="180923">instruction,</span> <span m="181350">this</span> <span m="181778">first</span>
  <span m="182206">instruction</span> <span m="182633">is</span> <span m="183061">invariably</span>
  <span m="183489">a</span> <span m="183984">branch</span> <span m="184480">to</span>
  <span m="184976">the</span> <span m="185471">actual</span> <span m="185967">interrupt</span>
  <span m="186463">code.</span></p><p><span m="186959">Here</span> <span m="187324">we</span>
  <span m="187690">see</span> <span m="188055">that</span> <span m="188421">the</span>
  <span m="188787">reset</span> <span m="189152">interrupt</span> <span m="189518">(asserted</span>
  <span m="189884">when</span> <span m="190249">the</span> <span m="190615">CPU</span>
  <span m="190980">first</span> <span m="191346">starts</span> <span m="191712">running)</span>
  <span m="192077">sets</span> <span m="192443">the</span> <span m="192809">PC</span>
  <span m="193195">to</span> <span m="193582">0,</span> <span m="193969">the</span>
  <span m="194356">illegal</span> <span m="194743">instruction</span> <span m="195130">interrupt</span>
  <span m="195517">sets</span> <span m="195904">the</span> <span m="196290">PC</span>
  <span m="196677">to</span> <span m="197064">4,</span> <span m="197451">the</span>
  <span m="197838">timer</span> <span m="198225">interrupt</span> <span m="198612">sets</span>
  <span m="198999">the</span> <span m="199480">PC</span> <span m="199962">to</span>
  <span m="200443">8,</span> <span m="200925">and</span> <span m="201406">so</span>
  <span m="201888">on.</span></p><p><span m="202370">In</span> <span m="202748">all</span>
  <span m="203126">cases,</span> <span m="203505">bit</span> <span m="203883">31</span>
  <span m="204262">of</span> <span m="204640">the</span> <span m="205019">new</span>
  <span m="205397">PC</span> <span m="205776">value</span> <span m="206154">is</span>
  <span m="206532">set</span> <span m="206911">to</span> <span m="207289">1</span>
  <span m="207668">so</span> <span m="208046">that</span> <span m="208425">handlers</span>
  <span m="208803">execute</span> <span m="209182">in</span> <span m="209560">supervisor</span>
  <span m="209939">or</span> <span m="210469">kernel</span> <span m="210999">mode,</span>
  <span m="211529">giving</span> <span m="212059">them</span> <span m="212589">access</span>
  <span m="213119">to</span> <span m="213649">the</span> <span m="214179">kernel</span>
  <span m="214709">context.</span></p><p><span m="215239">A</span> <span m="215579">common</span>
  <span m="215919">alternative</span> <span m="216259">is</span> <span m="216599">provide</span>
  <span m="216939">a</span> <span m="217279">table</span> <span m="217619">of</span>
  <span m="217959">new</span> <span m="218299">PC</span> <span m="218639">values</span>
  <span m="218979">at</span> <span m="219319">a</span> <span m="219659">known</span>
  <span m="219999">location</span> <span m="220339">and</span> <span m="220679">have</span>
  <span m="221019">the</span> <span m="221410">interrupt</span> <span m="221801">hardware</span>
  <span m="222193">access</span> <span m="222584">that</span> <span m="222975">table</span>
  <span m="223367">to</span> <span m="223758">fetch</span> <span m="224149">the</span>
  <span m="224541">PC</span> <span m="224932">for</span> <span m="225323">the</span>
  <span m="225715">appropriate</span> <span m="226106">handler</span> <span m="226497">routine.</span></p><p><span
  m="226889">This</span> <span m="227315">provides</span> <span m="227741">the</span>
  <span m="228167">same</span> <span m="228593">functionality</span> <span m="229019">as</span>
  <span m="229445">our</span> <span m="229871">simple</span> <span m="230297">Beta</span>
  <span m="230723">implementation.</span></p><p><span m="231150">Since</span> <span
  m="231617">the</span> <span m="232084">process</span> <span m="232551">state</span>
  <span m="233018">is</span> <span m="233485">saved</span> <span m="233952">and</span>
  <span m="234419">restored</span> <span m="234886">during</span> <span m="235353">an</span>
  <span m="235820">interrupt,</span> <span m="236287">interrupts</span> <span m="236754">are</span>
  <span m="237221">transparent</span> <span m="237689">to</span> <span m="238199">the</span>
  <span m="238709">running</span> <span m="239219">user-mode</span> <span m="239729">program.</span></p><p><span
  m="240239">In</span> <span m="240545">essence,</span> <span m="240852">we</span>
  <span m="241158">borrow</span> <span m="241465">a</span> <span m="241771">few</span>
  <span m="242078">CPU</span> <span m="242384">cycles</span> <span m="242691">to</span>
  <span m="242997">deal</span> <span m="243304">with</span> <span m="243610">the</span>
  <span m="243917">interrupt,</span> <span m="244223">then</span> <span m="244530">it's</span>
  <span m="244836">back</span> <span m="245143">to</span> <span m="245450">normal</span>
  <span m="246403">program</span> <span m="247356">execution.</span></p><p><span m="248310">Here's</span>
  <span m="248673">how</span> <span m="249037">the</span> <span m="249400">timer</span>
  <span m="249764">interrupt</span> <span m="250128">handler</span> <span m="250491">would</span>
  <span m="250855">work.</span></p><p><span m="251219">Our</span> <span m="251476">initial</span>
  <span m="251733">goal</span> <span m="251990">is</span> <span m="252248">to</span>
  <span m="252505">use</span> <span m="252762">the</span> <span m="253020">timer</span>
  <span m="253277">interrupt</span> <span m="253534">to</span> <span m="253792">update</span>
  <span m="254049">a</span> <span m="254306">data</span> <span m="254564">value</span>
  <span m="254821">in</span> <span m="255078">the</span> <span m="255336">OS</span>
  <span m="255593">that</span> <span m="255850">records</span> <span m="256108">the</span>
  <span m="256465">current</span> <span m="256822">time</span> <span m="257179">of</span>
  <span m="257536">day</span> <span m="257893">(TOD).</span></p><p><span m="258250">Let's</span>
  <span m="258635">assume</span> <span m="259021">the</span> <span m="259407">timer</span>
  <span m="259793">interrupt</span> <span m="260179">is</span> <span m="260565">triggered</span>
  <span m="260950">every</span> <span m="261336">1/60th</span> <span m="261722">of</span>
  <span m="262108">a</span> <span m="262494">second.</span></p><p><span m="262880">A</span>
  <span m="263226">user-mode</span> <span m="263572">program</span> <span m="263919">executes</span>
  <span m="264265">normally,</span> <span m="264612">not</span> <span m="264958">needing</span>
  <span m="265305">to</span> <span m="265651">make</span> <span m="265997">any</span>
  <span m="266344">special</span> <span m="266690">provision</span> <span m="267037">to</span>
  <span m="267383">deal</span> <span m="267730">with</span> <span m="268573">timer</span>
  <span m="269416">interrupts.</span></p><p><span m="270260">Periodically</span> <span
  m="270589">the</span> <span m="270918">timer</span> <span m="271247">interrupts</span>
  <span m="271576">the</span> <span m="271906">user-mode</span> <span m="272235">program</span>
  <span m="272564">to</span> <span m="272893">run</span> <span m="273223">the</span>
  <span m="273552">clock</span> <span m="273881">interrupt</span> <span m="274210">handler</span>
  <span m="274540">code</span> <span m="274981">in</span> <span m="275423">the</span>
  <span m="275865">OS,</span> <span m="276307">then</span> <span m="276749">resumes</span>
  <span m="277190">execution</span> <span m="277632">of</span> <span m="278074">the</span>
  <span m="278516">user-mode</span> <span m="278958">program.</span></p><p><span m="279400">The</span>
  <span m="279750">program</span> <span m="280100">continues</span> <span m="280450">execution</span>
  <span m="280800">just</span> <span m="281150">as</span> <span m="281500">if</span>
  <span m="281850">the</span> <span m="282200">interrupt</span> <span m="282550">had</span>
  <span m="282900">not</span> <span m="283250">occurred.</span></p><p><span m="283600">If</span>
  <span m="283968">the</span> <span m="284337">program</span> <span m="284706">needs</span>
  <span m="285075">access</span> <span m="285443">to</span> <span m="285812">the</span>
  <span m="286181">TOD,</span> <span m="286550">it</span> <span m="286918">makes</span>
  <span m="287287">the</span> <span m="287656">appropriate</span> <span m="288025">service</span>
  <span m="288393">request</span> <span m="288762">to</span> <span m="289131">the</span>
  <span m="289500">OS.</span></p><p><span m="291880">The</span> <span m="292150">clock</span>
  <span m="292420">handler</span> <span m="292690">code</span> <span m="292960">in</span>
  <span m="293230">the</span> <span m="293500">OS</span> <span m="293770">starts</span>
  <span m="294040">and</span> <span m="294310">ends</span> <span m="294580">with</span>
  <span m="294850">a</span> <span m="295120">small</span> <span m="295390">amount</span>
  <span m="295660">of</span> <span m="295930">assembly-language</span> <span m="296200">code</span>
  <span m="296538">to</span> <span m="296877">save</span> <span m="297215">and</span>
  <span m="297554">restore</span> <span m="297892">the</span> <span m="298231">state.</span></p><p><span
  m="298570">In</span> <span m="299013">the</span> <span m="299456">middle,</span>
  <span m="299899">the</span> <span m="300342">assembly</span> <span m="300785">code</span>
  <span m="301228">makes</span> <span m="301671">a</span> <span m="302115">C</span>
  <span m="302558">procedure</span> <span m="303001">call</span> <span m="303444">to</span>
  <span m="303887">actually</span> <span m="304330">handle</span> <span m="304773">the</span>
  <span m="305216">interrupt.</span></p><p><span m="305660">Here's</span> <span m="305923">what</span>
  <span m="306187">the</span> <span m="306451">handler</span> <span m="306715">code</span>
  <span m="306978">might</span> <span m="307242">look</span> <span m="307506">like.</span></p><p><span
  m="307770">In</span> <span m="308197">C,</span> <span m="308625">we</span> <span
  m="309052">find</span> <span m="309480">the</span> <span m="309907">declarations</span>
  <span m="310335">for</span> <span m="310762">the</span> <span m="311190">TOD</span>
  <span m="311617">data</span> <span m="312045">value</span> <span m="312472">and</span>
  <span m="312900">the</span> <span m="313327">structure,</span> <span m="313755">called</span>
  <span m="314182">UserMState,</span> <span m="314610">that</span> <span m="315072">temporarily</span>
  <span m="315535">holds</span> <span m="315998">the</span> <span m="316461">saved</span>
  <span m="316924">process</span> <span m="317387">state.</span></p><p><span m="317850">There's</span>
  <span m="318355">also</span> <span m="318860">the</span> <span m="319365">C</span>
  <span m="319870">procedure</span> <span m="320375">for</span> <span m="320880">incrementing</span>
  <span m="321385">the</span> <span m="321890">TOD</span> <span m="322395">value.</span></p><p><span
  m="322900">A</span> <span m="323273">timer</span> <span m="323646">interrupt</span>
  <span m="324020">executes</span> <span m="324393">the</span> <span m="324766">BR()</span>
  <span m="325140">instruction</span> <span m="325513">at</span> <span m="325886">location</span>
  <span m="326260">8,</span> <span m="326633">which</span> <span m="327006">branches</span>
  <span m="327380">to</span> <span m="327753">the</span> <span m="328126">actual</span>
  <span m="328500">interrupt</span> <span m="329202">handler</span> <span m="329904">code</span>
  <span m="330606">at</span> <span m="331308">CLOCK_H.</span></p><p><span m="332010">The</span>
  <span m="332405">code</span> <span m="332800">first</span> <span m="333195">saves</span>
  <span m="333590">the</span> <span m="333985">values</span> <span m="334380">of</span>
  <span m="334775">all</span> <span m="335170">the</span> <span m="335565">CPU</span>
  <span m="335960">registers</span> <span m="336355">into</span> <span m="336750">the</span>
  <span m="337145">UserMState</span> <span m="337540">data</span> <span m="337935">structure.</span></p><p><span
  m="338330">Note</span> <span m="338680">that</span> <span m="339030">we</span> <span
  m="339380">don't</span> <span m="339730">save</span> <span m="340080">the</span>
  <span m="340430">value</span> <span m="340780">of</span> <span m="341130">R31</span>
  <span m="341480">since</span> <span m="341830">its</span> <span m="342180">value</span>
  <span m="342530">is</span> <span m="342880">always</span> <span m="343230">0.</span></p><p><span
  m="343580">After</span> <span m="343916">setting</span> <span m="344252">up</span>
  <span m="344588">the</span> <span m="344924">kernel-mode</span> <span m="345260">stack,</span>
  <span m="345596">the</span> <span m="345933">assembly-language</span> <span m="346269">stub</span>
  <span m="346605">calls</span> <span m="346941">the</span> <span m="347277">C</span>
  <span m="347613">procedure</span> <span m="347950">above</span> <span m="348370">to</span>
  <span m="348790">do</span> <span m="349210">the</span> <span m="349630">hard</span>
  <span m="350050">work.</span></p><p><span m="350470">When</span> <span m="350855">the</span>
  <span m="351241">procedure</span> <span m="351627">returns,</span> <span m="352012">the</span>
  <span m="352398">CPU</span> <span m="352784">registers</span> <span m="353170">are</span>
  <span m="353555">reloaded</span> <span m="353941">from</span> <span m="354327">the</span>
  <span m="354712">saved</span> <span m="355098">process</span> <span m="355484">state</span>
  <span m="355870">and</span> <span m="356211">the</span> <span m="356553">XP</span>
  <span m="356895">register</span> <span m="357237">value</span> <span m="357578">decremented</span>
  <span m="357920">by</span> <span m="358262">4</span> <span m="358604">so</span>
  <span m="358945">that</span> <span m="359287">it</span> <span m="359629">will</span>
  <span m="359971">point</span> <span m="360312">to</span> <span m="360654">the</span>
  <span m="360996">interrupted</span> <span m="361338">instruction.</span></p><p><span
  m="361680">Then</span> <span m="362451">a</span> <span m="363223">JMP(XP)</span>
  <span m="363995">resumes</span> <span m="364766">user-mode</span> <span m="365538">execution.</span></p><p><span
  m="366310">Okay,</span> <span m="366840">that</span> <span m="367370">was</span>
  <span m="367900">simple</span> <span m="368430">enough.</span></p><p><span m="368960">But</span>
  <span m="369314">what</span> <span m="369668">does</span> <span m="370022">this</span>
  <span m="370376">all</span> <span m="370730">have</span> <span m="371084">to</span>
  <span m="371438">do</span> <span m="371792">with</span> <span m="372146">timesharing?</span></p><p><span
  m="372500">Wasn't</span> <span m="372929">our</span> <span m="373358">goal</span>
  <span m="373787">to</span> <span m="374216">arrange</span> <span m="374645">to</span>
  <span m="375075">periodically</span> <span m="375504">switch</span> <span m="375933">which</span>
  <span m="376362">process</span> <span m="376791">was</span> <span m="377220">running?</span></p><p><span
  m="377650">Aha!</span></p><p><span m="378760">We</span> <span m="379058">have</span>
  <span m="379357">code</span> <span m="379656">that</span> <span m="379955">runs</span>
  <span m="380254">on</span> <span m="380553">every</span> <span m="380852">timer</span>
  <span m="381151">interrupt,</span> <span m="381450">so</span> <span m="381748">let's</span>
  <span m="382047">modify</span> <span m="382346">it</span> <span m="382645">so</span>
  <span m="382944">that</span> <span m="383243">every</span> <span m="383542">so</span>
  <span m="383841">often</span> <span m="384140">we</span> <span m="384657">arrange</span>
  <span m="385175">to</span> <span m="385692">call</span> <span m="386210">the</span>
  <span m="386727">OS'</span> <span m="387245">Scheduler()</span> <span m="387762">routine.</span></p><p><span
  m="388280">In</span> <span m="388582">this</span> <span m="388884">example,</span>
  <span m="389187">we'd</span> <span m="389489">set</span> <span m="389791">the</span>
  <span m="390094">constant</span> <span m="390396">QUANTUM</span> <span m="390698">to</span>
  <span m="391001">2</span> <span m="391303">if</span> <span m="391605">we</span>
  <span m="391908">wanted</span> <span m="392210">to</span> <span m="392512">call</span>
  <span m="392815">Scheduler()</span> <span m="393117">every</span> <span m="393420">second</span>
  <span m="394350">timer</span> <span m="395280">interrupt.</span></p><p><span m="396210">The</span>
  <span m="396751">Scheduler()</span> <span m="397292">subroutine</span> <span m="397833">is</span>
  <span m="398374">where</span> <span m="398915">the</span> <span m="399456">time</span>
  <span m="399997">sharing</span> <span m="400538">magic</span> <span m="401079">happens!</span></p><p><span
  m="401620">Here</span> <span m="401938">we</span> <span m="402257">see</span> <span
  m="402575">the</span> <span m="402894">UserMState</span> <span m="403212">data</span>
  <span m="403531">structure</span> <span m="403850">from</span> <span m="404168">the</span>
  <span m="404487">previous</span> <span m="404805">slide</span> <span m="405124">where</span>
  <span m="405442">the</span> <span m="405761">user-mode</span> <span m="406080">process</span>
  <span m="406661">state</span> <span m="407243">is</span> <span m="407825">stored</span>
  <span m="408406">during</span> <span m="408988">interrupts.</span></p><p><span m="409570">And</span>
  <span m="409917">here's</span> <span m="410264">an</span> <span m="410612">array</span>
  <span m="410959">of</span> <span m="411306">process</span> <span m="411654">control</span>
  <span m="412001">block</span> <span m="412348">(PCB)</span> <span m="412696">data</span>
  <span m="413043">structures,</span> <span m="413390">one</span> <span m="413738">for</span>
  <span m="414085">each</span> <span m="414432">process</span> <span m="414780">in</span>
  <span m="415399">the</span> <span m="416019">system.</span></p><p><span m="416639">The</span>
  <span m="416964">PCB</span> <span m="417289">holds</span> <span m="417614">the</span>
  <span m="417939">complete</span> <span m="418264">state</span> <span m="418589">of</span>
  <span m="418914">a</span> <span m="419239">process</span> <span m="419564">when</span>
  <span m="419889">some</span> <span m="420214">other</span> <span m="420539">process</span>
  <span m="420864">is</span> <span m="421189">currently</span> <span m="421514">executing</span>
  <span m="421840">-</span> <span m="422408">it's</span> <span m="422977">the</span>
  <span m="423545">long-term</span> <span m="424114">storage</span> <span m="424683">for</span>
  <span m="425251">processor</span> <span m="425820">state!</span></p><p><span m="426389">As</span>
  <span m="426717">you</span> <span m="427046">can</span> <span m="427375">see,</span>
  <span m="427704">it</span> <span m="428033">includes</span> <span m="428362">a</span>
  <span m="428691">copy</span> <span m="429020">of</span> <span m="429348">MState</span>
  <span m="429677">with</span> <span m="430006">the</span> <span m="430335">process'</span>
  <span m="430664">register</span> <span m="430993">values,</span> <span m="431322">the</span>
  <span m="431651">MMU</span> <span m="431980">state,</span> <span m="432528">and</span>
  <span m="433076">various</span> <span m="433624">state</span> <span m="434172">associated</span>
  <span m="434720">with</span> <span m="435268">the</span> <span m="435816">process'</span>
  <span m="436364">input/output</span> <span m="436912">activities,</span> <span m="437460">represented</span>
  <span m="437917">here</span> <span m="438375">by</span> <span m="438832">a</span>
  <span m="439290">number</span> <span m="439747">indicating</span> <span m="440205">which</span>
  <span m="440662">virtual</span> <span m="441120">user-interface</span> <span m="441577">console</span>
  <span m="442035">is</span> <span m="442492">attached</span> <span m="442950">to</span>
  <span m="443703">the</span> <span m="444456">process.</span></p><p><span m="445210">There</span>
  <span m="445724">are</span> <span m="446238">N</span> <span m="446752">processes</span>
  <span m="447266">altogether.</span></p><p><span m="447780">The</span> <span m="448366">variable</span>
  <span m="448952">CUR</span> <span m="449538">gives</span> <span m="450124">the</span>
  <span m="450710">index</span> <span m="451296">into</span> <span m="451883">ProcTable</span>
  <span m="452469">for</span> <span m="453055">the</span> <span m="453641">currently</span>
  <span m="454227">running</span> <span m="454813">process.</span></p><p><span m="455400">And</span>
  <span m="455920">here's</span> <span m="456440">the</span> <span m="456960">surprisingly</span>
  <span m="457480">simple</span> <span m="458000">code</span> <span m="458520">for</span>
  <span m="459040">implementing</span> <span m="459560">timesharing.</span></p><p><span
  m="460080">Whenever</span> <span m="460457">the</span> <span m="460834">Scheduler()</span>
  <span m="461211">routine</span> <span m="461588">is</span> <span m="461965">called,</span>
  <span m="462342">it</span> <span m="462720">starts</span> <span m="463097">by</span>
  <span m="463474">moving</span> <span m="463851">the</span> <span m="464228">temporary</span>
  <span m="464605">saved</span> <span m="464982">state</span> <span m="465360">into</span>
  <span m="465952">the</span> <span m="466545">PCB</span> <span m="467138">for</span>
  <span m="467731">the</span> <span m="468324">current</span> <span m="468917">process.</span></p><p><span
  m="469510">It</span> <span m="469825">then</span> <span m="470141">increments</span>
  <span m="470456">CUR</span> <span m="470772">to</span> <span m="471088">move</span>
  <span m="471403">to</span> <span m="471719">the</span> <span m="472035">next</span>
  <span m="472350">process,</span> <span m="472666">making</span> <span m="472981">sure</span>
  <span m="473297">it</span> <span m="473613">wraps</span> <span m="473928">back</span>
  <span m="474244">around</span> <span m="474560">to</span> <span m="474927">0</span>
  <span m="475295">when</span> <span m="475663">we've</span> <span m="476030">just</span>
  <span m="476398">finished</span> <span m="476766">running</span> <span m="477133">the</span>
  <span m="477501">last</span> <span m="477869">of</span> <span m="478236">the</span>
  <span m="478604">N</span> <span m="478972">processes.</span></p><p><span m="479340">It</span>
  <span m="479718">then</span> <span m="480096">loads</span> <span m="480474">reloads</span>
  <span m="480852">the</span> <span m="481231">temporary</span> <span m="481609">state</span>
  <span m="481987">from</span> <span m="482365">the</span> <span m="482744">PCB</span>
  <span m="483122">of</span> <span m="483500">the</span> <span m="483878">new</span>
  <span m="484257">process</span> <span m="484635">and</span> <span m="485013">sets</span>
  <span m="485391">up</span> <span m="485770">the</span> <span m="486756">MMU</span>
  <span m="487743">appropriately.</span></p><p><span m="488730">At</span> <span m="489055">this</span>
  <span m="489381">point</span> <span m="489707">Scheduler()</span> <span m="490032">returns</span>
  <span m="490358">and</span> <span m="490684">the</span> <span m="491010">clock</span>
  <span m="491335">interrupt</span> <span m="491661">handler</span> <span m="491987">reloads</span>
  <span m="492312">the</span> <span m="492638">CPU</span> <span m="492964">registers</span>
  <span m="493290">from</span> <span m="493838">the</span> <span m="494387">updated</span>
  <span m="494936">temporary</span> <span m="495485">saved</span> <span m="496034">state</span>
  <span m="496583">and</span> <span m="497132">resumes</span> <span m="497681">execution.</span></p><p><span
  m="498230">Voila!</span></p><p><span m="499600">We're</span> <span m="500160">now</span>
  <span m="500720">running</span> <span m="501280">a</span> <span m="501840">new</span>
  <span m="502400">process.</span></p><p><span m="502960">Let's</span> <span m="503261">use</span>
  <span m="503563">this</span> <span m="503864">diagram</span> <span m="504166">to</span>
  <span m="504467">once</span> <span m="504769">again</span> <span m="505070">walk</span>
  <span m="505372">through</span> <span m="505673">how</span> <span m="505975">time</span>
  <span m="506276">sharing</span> <span m="506578">works.</span></p><p><span m="506880">At</span>
  <span m="507185">the</span> <span m="507491">top</span> <span m="507797">of</span>
  <span m="508103">the</span> <span m="508409">diagram</span> <span m="508715">you'll</span>
  <span m="509021">see</span> <span m="509327">the</span> <span m="509632">code</span>
  <span m="509938">for</span> <span m="510244">the</span> <span m="510550">user-mode</span>
  <span m="510856">processes,</span> <span m="511162">and</span> <span m="511468">below</span>
  <span m="511774">the</span> <span m="512080">OS</span> <span m="512524">code</span>
  <span m="512968">along</span> <span m="513412">with</span> <span m="513857">its</span>
  <span m="514301">data</span> <span m="514745">structures.</span></p><p><span m="515190">The</span>
  <span m="515622">timer</span> <span m="516054">interrupts</span> <span m="516487">the</span>
  <span m="516919">currently</span> <span m="517352">running</span> <span m="517784">user-mode</span>
  <span m="518216">program</span> <span m="518649">and</span> <span m="519081">starts</span>
  <span m="519514">execution</span> <span m="519946">of</span> <span m="520379">the</span>
  <span m="520953">OS'</span> <span m="521527">clock</span> <span m="522101">handler</span>
  <span m="522675">code.</span></p><p><span m="523250">The</span> <span m="523666">first</span>
  <span m="524082">thing</span> <span m="524498">the</span> <span m="524915">handler</span>
  <span m="525331">does</span> <span m="525747">is</span> <span m="526163">save</span>
  <span m="526580">all</span> <span m="526996">the</span> <span m="527412">registers</span>
  <span m="527828">into</span> <span m="528245">the</span> <span m="528661">UserMState</span>
  <span m="529077">data</span> <span m="529493">structure.</span></p><p><span m="529910">If</span>
  <span m="530356">the</span> <span m="530803">Scheduler()</span> <span m="531250">routine</span>
  <span m="531696">is</span> <span m="532143">called,</span> <span m="532590">it</span>
  <span m="533036">moves</span> <span m="533483">the</span> <span m="533930">temporarily</span>
  <span m="534376">saved</span> <span m="534823">state</span> <span m="535270">into</span>
  <span m="535716">the</span> <span m="536163">PCB,</span> <span m="536610">which</span>
  <span m="537098">provides</span> <span m="537587">the</span> <span m="538076">long-term</span>
  <span m="538565">storage</span> <span m="539053">for</span> <span m="539542">a</span>
  <span m="540031">process'</span> <span m="540520">state.</span></p><p><span m="541009">Next,</span>
  <span m="541347">Scheduler()</span> <span m="541686">copies</span> <span m="542024">the</span>
  <span m="542363">saved</span> <span m="542701">state</span> <span m="543040">for</span>
  <span m="543379">the</span> <span m="543717">next</span> <span m="544056">process</span>
  <span m="544394">into</span> <span m="544733">the</span> <span m="545071">temporary</span>
  <span m="545410">holding</span> <span m="545749">area.</span></p><p><span m="546999">Then</span>
  <span m="547420">the</span> <span m="547841">clock</span> <span m="548263">handler</span>
  <span m="548684">reloads</span> <span m="549105">the</span> <span m="549527">updated</span>
  <span m="549948">state</span> <span m="550369">into</span> <span m="550791">the</span>
  <span m="551212">CPU</span> <span m="551633">registers</span> <span m="552055">and</span>
  <span m="552476">resumes</span> <span m="552897">execution,</span> <span m="553319">this</span>
  <span m="553782">time</span> <span m="554246">running</span> <span m="554710">code</span>
  <span m="555174">in</span> <span m="555637">the</span> <span m="556101">new</span>
  <span m="556565">process.</span></p><p><span m="557029">While</span> <span m="557291">we're</span>
  <span m="557554">looking</span> <span m="557817">at</span> <span m="558080">the</span>
  <span m="558343">OS,</span> <span m="558606">note</span> <span m="558869">that</span>
  <span m="559132">since</span> <span m="559395">its</span> <span m="559658">code</span>
  <span m="559921">runs</span> <span m="560184">with</span> <span m="560447">the</span>
  <span m="560710">supervisor</span> <span m="560973">mode</span> <span m="561236">bit</span>
  <span m="561499">set</span> <span m="562019">to</span> <span m="562539">1,</span>
  <span m="563059">interrupts</span> <span m="563579">are</span> <span m="564099">disabled</span>
  <span m="564619">while</span> <span m="565139">in</span> <span m="565659">the</span>
  <span m="566179">OS.</span></p><p><span m="566700">This</span> <span m="566977">prevents</span>
  <span m="567254">the</span> <span m="567532">awkward</span> <span m="567809">problem</span>
  <span m="568086">of</span> <span m="568364">getting</span> <span m="568641">a</span>
  <span m="568918">second</span> <span m="569196">interrupt</span> <span m="569473">while</span>
  <span m="569750">still</span> <span m="570028">in</span> <span m="570305">the</span>
  <span m="570582">middle</span> <span m="570860">of</span> <span m="571262">handling</span>
  <span m="571664">a</span> <span m="572066">first</span> <span m="572468">interrupt,</span>
  <span m="572871">a</span> <span m="573273">situation</span> <span m="573675">that</span>
  <span m="574077">might</span> <span m="574480">accidentally</span> <span m="574882">overwrite</span>
  <span m="575284">the</span> <span m="575686">state</span> <span m="576089">in</span>
  <span m="577269">UserMState.</span></p><p><span m="578449">But</span> <span m="578832">that</span>
  <span m="579216">means</span> <span m="579600">one</span> <span m="579984">has</span>
  <span m="580368">to</span> <span m="580752">be</span> <span m="581136">very</span>
  <span m="581520">careful</span> <span m="581904">when</span> <span m="582288">writing</span>
  <span m="582672">OS</span> <span m="583056">code.</span></p><p><span m="583440">Any</span>
  <span m="583847">sort</span> <span m="584255">of</span> <span m="584663">infinite</span>
  <span m="585071">loop</span> <span m="585478">can</span> <span m="585886">never</span>
  <span m="586294">be</span> <span m="586702">interrupted.</span></p><p><span m="587110">You</span>
  <span m="587424">may</span> <span m="587739">have</span> <span m="588053">experienced</span>
  <span m="588368">this</span> <span m="588683">when</span> <span m="588997">your</span>
  <span m="589312">machine</span> <span m="589626">appears</span> <span m="589941">to</span>
  <span m="590256">freeze,</span> <span m="590570">accepting</span> <span m="590885">no</span>
  <span m="591199">inputs</span> <span m="591514">and</span> <span m="591829">just</span>
  <span m="592254">sitting</span> <span m="592679">there</span> <span m="593104">like</span>
  <span m="593529">a</span> <span m="593954">lump.</span></p><p><span m="594379">At</span>
  <span m="594734">this</span> <span m="595089">point,</span> <span m="595445">your</span>
  <span m="595800">only</span> <span m="596155">choice</span> <span m="596511">is</span>
  <span m="596866">to</span> <span m="597221">power-cycle</span> <span m="597577">the</span>
  <span m="597932">hardware</span> <span m="598287">(the</span> <span m="598643">ultimate</span>
  <span m="598998">interrupt!)</span> <span m="599353">and</span> <span m="599709">start</span>
  <span m="600899">afresh.</span></p><p><span m="602089">Interrupts</span> <span m="602386">are</span>
  <span m="602684">allowed</span> <span m="602982">during</span> <span m="603280">execution</span>
  <span m="603578">of</span> <span m="603876">user-mode</span> <span m="604174">programs,</span>
  <span m="604472">so</span> <span m="604770">if</span> <span m="605068">they</span>
  <span m="605366">run</span> <span m="605664">amok</span> <span m="605962">and</span>
  <span m="606260">need</span> <span m="606575">to</span> <span m="606890">be</span>
  <span m="607206">interrupted,</span> <span m="607521">that's</span> <span m="607836">always</span>
  <span m="608152">possible</span> <span m="608467">since</span> <span m="608782">the</span>
  <span m="609098">OS</span> <span m="609413">is</span> <span m="609728">still</span>
  <span m="610044">responding</span> <span m="610359">to,</span> <span m="610674">say,</span>
  <span m="610990">keyboard</span> <span m="611939">interrupts.</span></p><p><span
  m="612889">Every</span> <span m="613190">OS</span> <span m="613491">has</span> <span
  m="613793">a</span> <span m="614094">magic</span> <span m="614396">combination</span>
  <span m="614697">of</span> <span m="614998">keystrokes</span> <span m="615300">that</span>
  <span m="615601">is</span> <span m="615903">guaranteed</span> <span m="616204">to</span>
  <span m="616505">suspend</span> <span m="616807">execution</span> <span m="617108">of</span>
  <span m="617410">the</span> <span m="617743">current</span> <span m="618076">process,</span>
  <span m="618410">sometimes</span> <span m="618743">arranging</span> <span m="619076">to</span>
  <span m="619410">make</span> <span m="619743">a</span> <span m="620076">copy</span>
  <span m="620410">of</span> <span m="620743">the</span> <span m="621076">process</span>
  <span m="621410">state</span> <span m="621743">for</span> <span m="622076">later</span>
  <span m="622410">debugging.</span></p><p><span m="623970">Very</span> <span m="624195">handy!</span></p>
type: course
uid: e3a74e70ae786399be705c445e9bd040

---
None