---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: IE9cFQ9b33U
  parent_uid: 9cd7f91ab6f2ac99302f82e398d37bff
  title: Video-YouTube-Stream
  type: Video
  uid: a3b38ab42225d5e680ec6518405a4c0d
- id: 3Play-3Play YouTube id-Stream
  media_location: IE9cFQ9b33U
  parent_uid: 9cd7f91ab6f2ac99302f82e398d37bff
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 07aa4782db027ad895bf832d15e663a1
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/IE9cFQ9b33U/default.jpg
  parent_uid: 9cd7f91ab6f2ac99302f82e398d37bff
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: bb23f99135ea4f852bb81a7e85071c83
- id: IE9cFQ9b33U.srt
  parent_uid: 9cd7f91ab6f2ac99302f82e398d37bff
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/improving-beta-performance-9-50-/IE9cFQ9b33U.srt
  title: 3play caption file
  type: null
  uid: e065f8a98577f11e09f2f3f3e288aa6a
- id: IE9cFQ9b33U.pdf
  parent_uid: 9cd7f91ab6f2ac99302f82e398d37bff
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/improving-beta-performance-9-50-/IE9cFQ9b33U.pdf
  title: 3play pdf file
  type: null
  uid: 7e3cf23c8eff1f556aff9ed11c96b438
- id: Caption-3Play YouTube id-SRT
  parent_uid: 9cd7f91ab6f2ac99302f82e398d37bff
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b2801d0cffac8d55d1aca198a66ed760
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 9cd7f91ab6f2ac99302f82e398d37bff
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 613c7d2672dd9ab48e3f6206d24cfbf5
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_15-02-01_300k.mp4
  parent_uid: 9cd7f91ab6f2ac99302f82e398d37bff
  title: Video-Internet Archive-MP4
  type: Video
  uid: 3e813bf0cb8e99c10bc1b0459241d0b0
inline_embed_id: 71475720improvingbetaperformance9503980238
layout: video
order_index: null
parent_uid: f0d50dc2904ee419c2e4019c29c19532
related_resources_text: ''
short_url: improving-beta-performance-9-50-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/improving-beta-performance-9-50-
template_type: Embed
title: Improving Beta Performance
transcript: <p><span m="1280">In</span> <span m="1546">this</span> <span m="1812">lecture,</span>
  <span m="2078">we're</span> <span m="2345">going</span> <span m="2611">to</span>
  <span m="2877">use</span> <span m="3143">the</span> <span m="3410">circuit</span>
  <span m="3676">pipelining</span> <span m="3942">techniques</span> <span m="4208">we</span>
  <span m="4475">learned</span> <span m="4741">in</span> <span m="5007">Part</span>
  <span m="5273">1</span> <span m="5540">of</span> <span m="5860">the</span> <span
  m="6180">course</span> <span m="6500">to</span> <span m="6820">improve</span> <span
  m="7140">the</span> <span m="7460">performance</span> <span m="7780">of</span> <span
  m="8100">the</span> <span m="8420">32-bit</span> <span m="8740">Beta</span> <span
  m="9060">CPU</span> <span m="9380">design</span> <span m="9700">we</span> <span
  m="10020">developed</span> <span m="10340">in</span> <span m="10660">Part</span>
  <span m="10927">2</span> <span m="11195">of</span> <span m="11463">the</span> <span
  m="11731">course.</span></p><p><span m="11999">This</span> <span m="12455">CPU</span>
  <span m="12911">design</span> <span m="13367">executes</span> <span m="13823">one</span>
  <span m="14279">Beta</span> <span m="14735">instruction</span> <span m="15191">per</span>
  <span m="15647">clock</span> <span m="16103">cycle.</span></p><p><span m="16560">Hopefully</span>
  <span m="16962">you</span> <span m="17364">remember</span> <span m="17766">the</span>
  <span m="18168">design!</span></p><p><span m="18570">If</span> <span m="18965">not,</span>
  <span m="19360">you</span> <span m="19755">might</span> <span m="20151">find</span>
  <span m="20546">it</span> <span m="20941">worthwhile</span> <span m="21337">to</span>
  <span m="21732">review</span> <span m="22127">Lecture</span> <span m="22522">13,</span>
  <span m="22918">Building</span> <span m="23313">the</span> <span m="23708">Beta,</span>
  <span m="24104">from</span> <span m="24499">Part</span> <span m="24894">2.</span></p><p><span
  m="25290">At</span> <span m="25518">the</span> <span m="25747">beginning</span>
  <span m="25976">of</span> <span m="26205">the</span> <span m="26433">clock</span>
  <span m="26662">cycle,</span> <span m="26891">this</span> <span m="27120">circuit</span>
  <span m="27348">loads</span> <span m="27577">a</span> <span m="27806">new</span>
  <span m="28035">value</span> <span m="28263">into</span> <span m="28492">the</span>
  <span m="28721">program</span> <span m="28950">counter,</span> <span m="29245">which</span>
  <span m="29540">is</span> <span m="29835">then</span> <span m="30130">sent</span>
  <span m="30426">to</span> <span m="30721">main</span> <span m="31016">memory</span>
  <span m="31311">as</span> <span m="31607">the</span> <span m="31902">address</span>
  <span m="32197">of</span> <span m="32492">the</span> <span m="32788">instruction</span>
  <span m="33083">to</span> <span m="33378">be</span> <span m="33673">executed</span>
  <span m="33969">this</span> <span m="34849">cycle.</span></p><p><span m="35730">When</span>
  <span m="36015">the</span> <span m="36301">32-bit</span> <span m="36587">word</span>
  <span m="36872">containing</span> <span m="37158">the</span> <span m="37444">binary</span>
  <span m="37730">encoding</span> <span m="38015">of</span> <span m="38301">the</span>
  <span m="38587">instruction</span> <span m="38872">is</span> <span m="39158">returned</span>
  <span m="39444">by</span> <span m="39730">the</span> <span m="40063">memory,</span>
  <span m="40397">the</span> <span m="40731">opcode</span> <span m="41065">field</span>
  <span m="41399">is</span> <span m="41733">decoded</span> <span m="42067">by</span>
  <span m="42401">the</span> <span m="42735">control</span> <span m="43069">logic</span>
  <span m="43403">to</span> <span m="43737">determine</span> <span m="44071">the</span>
  <span m="44405">control</span> <span m="44739">signals</span> <span m="45119">for</span>
  <span m="45499">the</span> <span m="45879">rest</span> <span m="46259">of</span>
  <span m="46639">the</span> <span m="47019">data</span> <span m="47399">path.</span></p><p><span
  m="47780">The</span> <span m="48061">operands</span> <span m="48343">are</span>
  <span m="48625">read</span> <span m="48907">from</span> <span m="49188">the</span>
  <span m="49470">register</span> <span m="49752">file</span> <span m="50034">and</span>
  <span m="50315">routed</span> <span m="50597">to</span> <span m="50879">the</span>
  <span m="51161">ALU</span> <span m="51442">to</span> <span m="51724">perform</span>
  <span m="52006">the</span> <span m="52288">desired</span> <span m="52570">operation.</span></p><p><span
  m="53839">For</span> <span m="54101">memory</span> <span m="54363">operations,</span>
  <span m="54626">the</span> <span m="54888">output</span> <span m="55151">of</span>
  <span m="55413">the</span> <span m="55675">ALU</span> <span m="55938">serves</span>
  <span m="56200">as</span> <span m="56463">the</span> <span m="56725">memory</span>
  <span m="56987">address</span> <span m="57250">and,</span> <span m="57512">in</span>
  <span m="57775">the</span> <span m="58037">case</span> <span m="58300">of</span>
  <span m="58578">load</span> <span m="58856">instructions,</span> <span m="59134">the</span>
  <span m="59412">main</span> <span m="59690">memory</span> <span m="59968">supplies</span>
  <span m="60246">the</span> <span m="60524">data</span> <span m="60802">to</span>
  <span m="61080">be</span> <span m="61358">written</span> <span m="61636">into</span>
  <span m="61914">the</span> <span m="62192">register</span> <span m="62470">file</span>
  <span m="62749">at</span> <span m="63025">the</span> <span m="63302">end</span>
  <span m="63579">of</span> <span m="63855">the</span> <span m="64132">cycle.</span></p><p><span
  m="64409">PC+4</span> <span m="64844">and</span> <span m="65280">ALU</span> <span
  m="65716">values</span> <span m="66152">can</span> <span m="66588">also</span> <span
  m="67024">be</span> <span m="67460">written</span> <span m="67896">to</span> <span
  m="68332">the</span> <span m="68768">register</span> <span m="69204">file.</span></p><p><span
  m="69640">The</span> <span m="69936">clock</span> <span m="70233">period</span>
  <span m="70530">of</span> <span m="70827">the</span> <span m="71124">Beta</span>
  <span m="71421">is</span> <span m="71718">determined</span> <span m="72015">by</span>
  <span m="72311">the</span> <span m="72608">cumulative</span> <span m="72905">delay</span>
  <span m="73202">through</span> <span m="73499">all</span> <span m="73796">the</span>
  <span m="74093">components</span> <span m="74390">involved</span> <span m="74874">in</span>
  <span m="75359">instruction</span> <span m="75844">execution.</span></p><p><span
  m="76329">Today's</span> <span m="76760">question</span> <span m="77191">is:</span>
  <span m="77622">how</span> <span m="78053">can</span> <span m="78485">we</span>
  <span m="78916">make</span> <span m="79347">this</span> <span m="79778">faster?</span></p><p><span
  m="80210">We</span> <span m="80553">can</span> <span m="80896">characterize</span>
  <span m="81240">the</span> <span m="81583">time</span> <span m="81926">spent</span>
  <span m="82270">executing</span> <span m="82613">a</span> <span m="82956">program</span>
  <span m="83300">as</span> <span m="83643">the</span> <span m="83986">product</span>
  <span m="84330">of</span> <span m="84673">three</span> <span m="85016">terms.</span></p><p><span
  m="85360">The</span> <span m="85652">first</span> <span m="85944">term</span> <span
  m="86236">is</span> <span m="86528">the</span> <span m="86820">total</span> <span
  m="87112">number</span> <span m="87404">of</span> <span m="87696">instructions</span>
  <span m="87988">executed.</span></p><p><span m="88280">Since</span> <span m="88680">the</span>
  <span m="89081">program</span> <span m="89482">usually</span> <span m="89882">contains</span>
  <span m="90283">loops</span> <span m="90684">and</span> <span m="91085">procedure</span>
  <span m="91485">calls,</span> <span m="91886">many</span> <span m="92287">of</span>
  <span m="92687">the</span> <span m="93088">encoded</span> <span m="93489">instructions</span>
  <span m="93890">will</span> <span m="94390">be</span> <span m="94890">executed</span>
  <span m="95390">many</span> <span m="95890">times.</span></p><p><span m="96390">We</span>
  <span m="96674">want</span> <span m="96959">the</span> <span m="97243">total</span>
  <span m="97528">count</span> <span m="97813">of</span> <span m="98097">instructions</span>
  <span m="98382">executed,</span> <span m="98667">not</span> <span m="98951">the</span>
  <span m="99236">static</span> <span m="99521">size</span> <span m="99805">of</span>
  <span m="100090">the</span> <span m="100375">program</span> <span m="100659">as</span>
  <span m="100944">measured</span> <span m="101229">by</span> <span m="101649">the</span>
  <span m="102069">number</span> <span m="102489">of</span> <span m="102909">encoded</span>
  <span m="103329">instructions</span> <span m="103749">in</span> <span m="104169">memory.</span></p><p><span
  m="104590">The</span> <span m="104921">second</span> <span m="105253">term</span>
  <span m="105585">is</span> <span m="105916">the</span> <span m="106248">average</span>
  <span m="106580">number</span> <span m="106911">of</span> <span m="107243">clock</span>
  <span m="107575">cycles</span> <span m="107907">it</span> <span m="108238">takes</span>
  <span m="108570">to</span> <span m="108902">execute</span> <span m="109233">a</span>
  <span m="109565">single</span> <span m="109897">instruction.</span></p><p><span
  m="110229">And</span> <span m="110637">the</span> <span m="111045">third</span>
  <span m="111454">term</span> <span m="111862">is</span> <span m="112271">the</span>
  <span m="112679">duration</span> <span m="113087">of</span> <span m="113496">a</span>
  <span m="113904">single</span> <span m="114313">clock</span> <span m="114721">cycle.</span></p><p><span
  m="115130">As</span> <span m="115481">CPU</span> <span m="115833">designers</span>
  <span m="116185">it's</span> <span m="116536">the</span> <span m="116888">last</span>
  <span m="117240">two</span> <span m="117591">terms</span> <span m="117943">which</span>
  <span m="118295">are</span> <span m="118647">under</span> <span m="118998">our</span>
  <span m="119350">control:</span> <span m="119702">the</span> <span m="120053">cycles</span>
  <span m="120405">per</span> <span m="120757">instruction</span> <span m="121109">(CPI)</span>
  <span m="121584">and</span> <span m="122059">the</span> <span m="122534">clock</span>
  <span m="123009">period</span> <span m="123484">(t_CLK).</span></p><p><span m="123960">To</span>
  <span m="124330">affect</span> <span m="124700">the</span> <span m="125070">first</span>
  <span m="125440">term,</span> <span m="125810">we</span> <span m="126180">would</span>
  <span m="126550">need</span> <span m="126920">to</span> <span m="127290">change</span>
  <span m="127660">the</span> <span m="128030">ISA</span> <span m="128400">or</span>
  <span m="128770">write</span> <span m="129140">a</span> <span m="129510">better</span>
  <span m="129880">compiler!</span></p><p><span m="130250">Our</span> <span m="130573">design</span>
  <span m="130896">for</span> <span m="131219">the</span> <span m="131542">Beta</span>
  <span m="131865">was</span> <span m="132188">able</span> <span m="132511">to</span>
  <span m="132835">execute</span> <span m="133158">every</span> <span m="133481">instruction</span>
  <span m="133804">in</span> <span m="134127">a</span> <span m="134450">single</span>
  <span m="134773">clock</span> <span m="135096">cycle,</span> <span m="135420">so</span>
  <span m="135926">our</span> <span m="136432">CPI</span> <span m="136938">is</span>
  <span m="137444">1.</span></p><p><span m="137950">As</span> <span m="138228">we</span>
  <span m="138507">discussed</span> <span m="138785">in</span> <span m="139064">the</span>
  <span m="139343">previous</span> <span m="139621">slide,</span> <span m="139900">t_CLK</span>
  <span m="140178">is</span> <span m="140457">determined</span> <span m="140736">by</span>
  <span m="141014">the</span> <span m="141293">longest</span> <span m="141571">path</span>
  <span m="141850">through</span> <span m="142129">the</span> <span m="142579">Beta</span>
  <span m="143029">circuitry.</span></p><p><span m="143480">For</span> <span m="143900">example,</span>
  <span m="144320">consider</span> <span m="144740">the</span> <span m="145160">execution</span>
  <span m="145580">of</span> <span m="146000">an</span> <span m="146420">OP-class</span>
  <span m="146840">instruction,</span> <span m="147260">which</span> <span m="147680">involves</span>
  <span m="148100">two</span> <span m="148520">register</span> <span m="148940">operands</span>
  <span m="149550">and</span> <span m="150160">an</span> <span m="150770">ALU</span>
  <span m="151380">operation.</span></p><p><span m="151990">The</span> <span m="152327">arrow</span>
  <span m="152664">shows</span> <span m="153001">all</span> <span m="153339">the</span>
  <span m="153676">components</span> <span m="154013">that</span> <span m="154350">are</span>
  <span m="154688">involved</span> <span m="155025">in</span> <span m="155362">the</span>
  <span m="155699">execution</span> <span m="156037">of</span> <span m="156374">the</span>
  <span m="156711">instruction.</span></p><p><span m="157049">Aside</span> <span m="157463">from</span>
  <span m="157877">a</span> <span m="158291">few</span> <span m="158706">muxes,</span>
  <span m="159120">the</span> <span m="159534">main</span> <span m="159948">memory,</span>
  <span m="160363">register</span> <span m="160777">file,</span> <span m="161191">and</span>
  <span m="161605">ALU</span> <span m="162020">must</span> <span m="162434">all</span>
  <span m="162848">have</span> <span m="163262">time</span> <span m="163677">to</span>
  <span m="164091">do</span> <span m="164505">their</span> <span m="164920">thing.</span></p><p><span
  m="165920">The</span> <span m="166385">worst-case</span> <span m="166851">execution</span>
  <span m="167316">time</span> <span m="167782">is</span> <span m="168247">for</span>
  <span m="168713">the</span> <span m="169178">LD</span> <span m="169644">instruction.</span></p><p><span
  m="170110">In</span> <span m="170414">one</span> <span m="170718">clock</span> <span
  m="171022">cycle</span> <span m="171327">we</span> <span m="171631">need</span>
  <span m="171935">to</span> <span m="172240">fetch</span> <span m="172544">the</span>
  <span m="172848">instruction</span> <span m="173152">from</span> <span m="173457">main</span>
  <span m="173761">memory</span> <span m="174065">(t_IFETCH),</span> <span m="174370">read</span>
  <span m="174701">the</span> <span m="175033">operands</span> <span m="175365">from</span>
  <span m="175697">the</span> <span m="176029">register</span> <span m="176361">file</span>
  <span m="176693">(t_RF),</span> <span m="177025">perform</span> <span m="177356">the</span>
  <span m="177688">address</span> <span m="178020">addition</span> <span m="178352">in</span>
  <span m="178684">the</span> <span m="179016">ALU</span> <span m="179348">(t_ALU),</span>
  <span m="179680">read</span> <span m="180027">the</span> <span m="180374">requested</span>
  <span m="180722">location</span> <span m="181069">from</span> <span m="181416">main</span>
  <span m="181764">memory</span> <span m="182111">(t_MEM),</span> <span m="182459">and</span>
  <span m="182926">finally</span> <span m="183393">write</span> <span m="183860">the</span>
  <span m="184328">memory</span> <span m="184795">data</span> <span m="185262">to</span>
  <span m="185729">the</span> <span m="186197">destination</span> <span m="186664">register</span>
  <span m="187131">(t_WB).</span></p><p><span m="187599">The</span> <span m="187909">component</span>
  <span m="188219">delays</span> <span m="188529">add</span> <span m="188839">up</span>
  <span m="189149">and</span> <span m="189459">the</span> <span m="189769">result</span>
  <span m="190079">is</span> <span m="190389">a</span> <span m="190699">fairly</span>
  <span m="191009">long</span> <span m="191319">clock</span> <span m="191629">period</span>
  <span m="191939">and</span> <span m="192249">hence</span> <span m="192559">it</span>
  <span m="192870">will</span> <span m="193222">take</span> <span m="193574">a</span>
  <span m="193926">long</span> <span m="194278">time</span> <span m="194631">to</span>
  <span m="194983">run</span> <span m="195335">the</span> <span m="195687">program.</span></p><p><span
  m="196040">And</span> <span m="196450">our</span> <span m="196860">two</span> <span
  m="197270">example</span> <span m="197680">execution</span> <span m="198090">paths</span>
  <span m="198500">illustrate</span> <span m="198910">another</span> <span m="199320">issue:</span>
  <span m="199730">we're</span> <span m="200119">forced</span> <span m="200509">to</span>
  <span m="200899">choose</span> <span m="201289">the</span> <span m="201679">clock</span>
  <span m="202069">period</span> <span m="202459">to</span> <span m="202849">accommodate</span>
  <span m="203239">the</span> <span m="203629">worst-case</span> <span m="204019">execution</span>
  <span m="204409">time,</span> <span m="204799">even</span> <span m="205146">though</span>
  <span m="205493">we</span> <span m="205840">may</span> <span m="206187">be</span>
  <span m="206534">able</span> <span m="206881">to</span> <span m="207229">execute</span>
  <span m="207576">some</span> <span m="207923">instructions</span> <span m="208270">faster</span>
  <span m="208617">since</span> <span m="208964">their</span> <span m="209311">execution</span>
  <span m="209659">path</span> <span m="210212">through</span> <span m="210766">the</span>
  <span m="211319">circuitry</span> <span m="211873">is</span> <span m="212426">shorter.</span></p><p><span
  m="212980">We're</span> <span m="213258">making</span> <span m="213537">all</span>
  <span m="213815">the</span> <span m="214094">instructions</span> <span m="214372">slower</span>
  <span m="214651">just</span> <span m="214929">because</span> <span m="215208">there's</span>
  <span m="215486">one</span> <span m="215765">instruction</span> <span m="216043">that</span>
  <span m="216322">has</span> <span m="216600">a</span> <span m="216879">long</span>
  <span m="217479">critical</span> <span m="218079">path.</span></p><p><span m="218680">So</span>
  <span m="219078">why</span> <span m="219477">not</span> <span m="219875">have</span>
  <span m="220274">simple</span> <span m="220673">instructions</span> <span m="221071">execute</span>
  <span m="221470">in</span> <span m="221868">one</span> <span m="222267">clock</span>
  <span m="222666">cycle</span> <span m="223064">and</span> <span m="223463">more</span>
  <span m="223861">complex</span> <span m="224260">instructions</span> <span m="224659">take</span>
  <span m="225008">multiple</span> <span m="225357">cycles</span> <span m="225707">instead</span>
  <span m="226056">of</span> <span m="226405">forcing</span> <span m="226755">all</span>
  <span m="227104">instructions</span> <span m="227453">to</span> <span m="227803">execute</span>
  <span m="228152">in</span> <span m="228501">a</span> <span m="228851">single,</span>
  <span m="229200">long</span> <span m="229550">clock</span> <span m="230199">cycle?</span></p><p><span
  m="230849">As</span> <span m="231089">we'll</span> <span m="231330">see</span> <span
  m="231570">in</span> <span m="231811">the</span> <span m="232051">next</span> <span
  m="232292">few</span> <span m="232533">slides,</span> <span m="232773">we</span>
  <span m="233014">have</span> <span m="233254">a</span> <span m="233495">good</span>
  <span m="233735">answer</span> <span m="233976">to</span> <span m="234217">this</span>
  <span m="234457">question,</span> <span m="234698">one</span> <span m="234938">that</span>
  <span m="235179">will</span> <span m="235420">allow</span> <span m="235808">us</span>
  <span m="236196">to</span> <span m="236584">execute</span> <span m="236972">*all*</span>
  <span m="237360">instructions</span> <span m="237748">with</span> <span m="238136">a</span>
  <span m="238524">short</span> <span m="238912">clock</span> <span m="239300">period.</span></p><p><span
  m="239689">We're</span> <span m="240031">going</span> <span m="240373">to</span>
  <span m="240715">use</span> <span m="241057">pipelining</span> <span m="241400">to</span>
  <span m="241742">address</span> <span m="242084">these</span> <span m="242426">issues.</span></p><p><span
  m="242769">We're</span> <span m="243049">going</span> <span m="243330">to</span>
  <span m="243611">divide</span> <span m="243891">the</span> <span m="244172">execution</span>
  <span m="244453">of</span> <span m="244734">an</span> <span m="245014">instruction</span>
  <span m="245295">into</span> <span m="245576">a</span> <span m="245857">sequence</span>
  <span m="246137">of</span> <span m="246418">steps,</span> <span m="246699">where</span>
  <span m="246980">each</span> <span m="247369">step</span> <span m="247758">is</span>
  <span m="248147">performed</span> <span m="248536">in</span> <span m="248925">successive</span>
  <span m="249314">stages</span> <span m="249703">of</span> <span m="250092">the</span>
  <span m="250481">pipeline.</span></p><p><span m="250870">So</span> <span m="251151">it</span>
  <span m="251433">will</span> <span m="251715">take</span> <span m="251996">multiple</span>
  <span m="252278">clock</span> <span m="252560">cycles</span> <span m="252841">to</span>
  <span m="253123">execute</span> <span m="253405">an</span> <span m="253687">instruction</span>
  <span m="253968">as</span> <span m="254250">it</span> <span m="254532">travels</span>
  <span m="254813">through</span> <span m="255095">the</span> <span m="255377">stages</span>
  <span m="255659">of</span> <span m="256216">the</span> <span m="256774">execution</span>
  <span m="257332">pipeline.</span></p><p><span m="257890">But</span> <span m="258156">since</span>
  <span m="258423">there</span> <span m="258690">are</span> <span m="258956">only</span>
  <span m="259223">one</span> <span m="259490">or</span> <span m="259756">two</span>
  <span m="260023">components</span> <span m="260290">in</span> <span m="260556">each</span>
  <span m="260823">stage</span> <span m="261090">of</span> <span m="261356">the</span>
  <span m="261623">pipeline,</span> <span m="261890">the</span> <span m="262156">clock</span>
  <span m="262423">period</span> <span m="262690">can</span> <span m="263048">be</span>
  <span m="263407">much</span> <span m="263765">shorter</span> <span m="264124">and</span>
  <span m="264482">the</span> <span m="264841">throughput</span> <span m="265200">of</span>
  <span m="265558">the</span> <span m="265917">CPU</span> <span m="266275">can</span>
  <span m="266634">be</span> <span m="266992">much</span> <span m="267351">higher.</span></p><p><span
  m="267710">The</span> <span m="268210">increased</span> <span m="268711">throughput</span>
  <span m="269212">is</span> <span m="269713">the</span> <span m="270213">result</span>
  <span m="270714">of</span> <span m="271215">overlapping</span> <span m="271716">the</span>
  <span m="272216">execution</span> <span m="272717">of</span> <span m="273218">consecutive</span>
  <span m="273719">instructions.</span></p><p><span m="274220">At</span> <span m="274481">any</span>
  <span m="274742">given</span> <span m="275003">time,</span> <span m="275265">there</span>
  <span m="275526">will</span> <span m="275787">be</span> <span m="276048">multiple</span>
  <span m="276310">instructions</span> <span m="276571">in</span> <span m="276832">the</span>
  <span m="277093">CPU,</span> <span m="277355">each</span> <span m="277616">at</span>
  <span m="277877">a</span> <span m="278138">different</span> <span m="278400">stage</span>
  <span m="279037">of</span> <span m="279675">its</span> <span m="280312">execution.</span></p><p><span
  m="280950">The</span> <span m="281362">time</span> <span m="281774">to</span> <span
  m="282186">execute</span> <span m="282598">all</span> <span m="283010">the</span>
  <span m="283422">steps</span> <span m="283834">for</span> <span m="284246">a</span>
  <span m="284658">particular</span> <span m="285070">instruction</span> <span m="285482">(i.e.,</span>
  <span m="285894">the</span> <span m="286306">instruction</span> <span m="286718">latency)</span>
  <span m="287130">may</span> <span m="287529">be</span> <span m="287929">somewhat</span>
  <span m="288329">higher</span> <span m="288729">than</span> <span m="289129">in</span>
  <span m="289529">our</span> <span m="289929">unpipelined</span> <span m="290329">implementation.</span></p><p><span
  m="290729">But</span> <span m="291037">we</span> <span m="291346">will</span> <span
  m="291655">finish</span> <span m="291964">the</span> <span m="292273">last</span>
  <span m="292581">step</span> <span m="292890">of</span> <span m="293199">executing</span>
  <span m="293508">some</span> <span m="293817">instruction</span> <span m="294126">in</span>
  <span m="294434">each</span> <span m="294743">clock</span> <span m="295052">cycle,</span>
  <span m="295361">so</span> <span m="295670">the</span> <span m="295979">instruction</span>
  <span m="296422">throughput</span> <span m="296865">is</span> <span m="297308">1</span>
  <span m="297751">per</span> <span m="298194">clock</span> <span m="298637">cycle.</span></p><p><span
  m="299080">And</span> <span m="299339">since</span> <span m="299598">the</span>
  <span m="299858">clock</span> <span m="300117">cycle</span> <span m="300376">of</span>
  <span m="300636">our</span> <span m="300895">pipelined</span> <span m="301155">CPU</span>
  <span m="301414">is</span> <span m="301673">quite</span> <span m="301933">a</span>
  <span m="302192">bit</span> <span m="302451">shorter,</span> <span m="302711">the</span>
  <span m="302970">instruction</span> <span m="303230">throughput</span> <span m="303724">is</span>
  <span m="304219">quite</span> <span m="304714">a</span> <span m="305209">bit</span>
  <span m="305704">higher.</span></p><p><span m="306199">All</span> <span m="306528">this</span>
  <span m="306857">sounds</span> <span m="307187">great,</span> <span m="307516">but,</span>
  <span m="307846">not</span> <span m="308175">surprisingly,</span> <span m="308505">there</span>
  <span m="308834">are</span> <span m="309163">few</span> <span m="309493">issues</span>
  <span m="309822">we'll</span> <span m="310152">have</span> <span m="310481">to</span>
  <span m="310811">deal</span> <span m="311140">with.</span></p><p><span m="311470">There</span>
  <span m="311843">are</span> <span m="312217">many</span> <span m="312590">ways</span>
  <span m="312964">to</span> <span m="313338">pipeline</span> <span m="313711">the</span>
  <span m="314085">execution</span> <span m="314459">of</span> <span m="314832">an</span>
  <span m="315206">instruction.</span></p><p><span m="315580">We're</span> <span m="315922">going</span>
  <span m="316264">to</span> <span m="316606">look</span> <span m="316948">at</span>
  <span m="317290">the</span> <span m="317632">design</span> <span m="317974">of</span>
  <span m="318316">the</span> <span m="318658">classic</span> <span m="319000">5-stage</span>
  <span m="319342">instruction</span> <span m="319684">execution</span> <span m="320026">pipeline,</span>
  <span m="320368">which</span> <span m="320710">was</span> <span m="321197">widely</span>
  <span m="321685">used</span> <span m="322172">in</span> <span m="322660">the</span>
  <span m="323147">integrated</span> <span m="323635">circuit</span> <span m="324122">CPU</span>
  <span m="324610">designs</span> <span m="325097">of</span> <span m="325585">the</span>
  <span m="326072">1980's.</span></p><p><span m="326560">The</span> <span m="326913">5</span>
  <span m="327266">pipeline</span> <span m="327620">stages</span> <span m="327973">correspond</span>
  <span m="328326">to</span> <span m="328680">the</span> <span m="329033">steps</span>
  <span m="329386">of</span> <span m="329740">executing</span> <span m="330093">an</span>
  <span m="330446">instruction</span> <span m="330800">in</span> <span m="331153">a</span>
  <span m="331506">von-Neumann</span> <span m="331860">stored-program</span> <span
  m="332945">architecture.</span></p><p><span m="334030">The</span> <span m="334377">first</span>
  <span m="334724">stage</span> <span m="335071">(IF)</span> <span m="335418">is</span>
  <span m="335765">responsible</span> <span m="336112">for</span> <span m="336460">fetching</span>
  <span m="336807">the</span> <span m="337154">binary-encoded</span> <span m="337501">instruction</span>
  <span m="337848">from</span> <span m="338195">the</span> <span m="338542">main</span>
  <span m="338890">memory</span> <span m="339382">location</span> <span m="339875">indicated</span>
  <span m="340368">by</span> <span m="340861">the</span> <span m="341354">program</span>
  <span m="341847">counter.</span></p><p><span m="342340">The</span> <span m="342719">32-bit</span>
  <span m="343098">instruction</span> <span m="343478">is</span> <span m="343857">passed</span>
  <span m="344236">to</span> <span m="344616">the</span> <span m="344995">register</span>
  <span m="345374">file</span> <span m="345754">stage</span> <span m="346133">(RF)</span>
  <span m="346512">where</span> <span m="346892">the</span> <span m="347271">required</span>
  <span m="347650">register</span> <span m="348030">operands</span> <span m="348495">are</span>
  <span m="348961">read</span> <span m="349426">from</span> <span m="349892">the</span>
  <span m="350357">register</span> <span m="350823">file.</span></p><p><span m="351289">The</span>
  <span m="351841">operand</span> <span m="352394">values</span> <span m="352947">are</span>
  <span m="353499">passed</span> <span m="354052">to</span> <span m="354605">the</span>
  <span m="355158">ALU</span> <span m="355710">stage</span> <span m="356263">(ALU),</span>
  <span m="356816">which</span> <span m="357369">performs</span> <span m="357921">the</span>
  <span m="358474">requested</span> <span m="359027">operation.</span></p><p><span
  m="359580">The</span> <span m="359952">memory</span> <span m="360324">stage</span>
  <span m="360697">(MEM)</span> <span m="361069">performs</span> <span m="361442">the</span>
  <span m="361814">second</span> <span m="362187">access</span> <span m="362559">to</span>
  <span m="362931">main</span> <span m="363304">memory</span> <span m="363676">to</span>
  <span m="364049">read</span> <span m="364421">or</span> <span m="364794">write</span>
  <span m="365166">the</span> <span m="365539">data</span> <span m="365889">for</span>
  <span m="366239">LD,</span> <span m="366589">LDR,</span> <span m="366939">or</span>
  <span m="367289">ST</span> <span m="367639">instructions,</span> <span m="367989">using</span>
  <span m="368339">the</span> <span m="368689">value</span> <span m="369039">from</span>
  <span m="369389">the</span> <span m="369739">ALU</span> <span m="370089">stage</span>
  <span m="370439">as</span> <span m="370789">the</span> <span m="371139">memory</span>
  <span m="371490">address.</span></p><p><span m="373240">For</span> <span m="373581">load</span>
  <span m="373923">instructions,</span> <span m="374265">the</span> <span m="374607">output</span>
  <span m="374949">of</span> <span m="375291">the</span> <span m="375633">MEM</span>
  <span m="375975">stage</span> <span m="376316">is</span> <span m="376658">the</span>
  <span m="377000">read</span> <span m="377342">data</span> <span m="377684">from</span>
  <span m="378026">main</span> <span m="378368">memory.</span></p><p><span m="378710">For</span>
  <span m="378950">all</span> <span m="379190">other</span> <span m="379430">instructions,</span>
  <span m="379670">the</span> <span m="379910">output</span> <span m="380150">of</span>
  <span m="380390">the</span> <span m="380630">MEM</span> <span m="380870">stage</span>
  <span m="381110">is</span> <span m="381350">simply</span> <span m="381590">the</span>
  <span m="381830">value</span> <span m="382070">from</span> <span m="382310">the</span>
  <span m="382550">ALU</span> <span m="383590">stage.</span></p><p><span m="384630">In</span>
  <span m="384955">the</span> <span m="385280">final</span> <span m="385605">write-back</span>
  <span m="385930">stage</span> <span m="386255">(WB),</span> <span m="386580">the</span>
  <span m="386905">result</span> <span m="387230">from</span> <span m="387555">the</span>
  <span m="387880">earlier</span> <span m="388205">stages</span> <span m="388530">is</span>
  <span m="388855">written</span> <span m="389180">to</span> <span m="389505">the</span>
  <span m="389830">destination</span> <span m="390363">register</span> <span m="390896">in</span>
  <span m="391430">the</span> <span m="391963">register</span> <span m="392496">file.</span></p><p><span
  m="393030">Looking</span> <span m="393277">at</span> <span m="393525">the</span>
  <span m="393772">execution</span> <span m="394020">path</span> <span m="394268">from</span>
  <span m="394515">the</span> <span m="394763">previous</span> <span m="395011">slide,</span>
  <span m="395258">we</span> <span m="395506">see</span> <span m="395754">that</span>
  <span m="396001">each</span> <span m="396249">of</span> <span m="396497">the</span>
  <span m="396744">main</span> <span m="396992">components</span> <span m="397240">of</span>
  <span m="397654">the</span> <span m="398069">unpipelined</span> <span m="398483">design</span>
  <span m="398898">is</span> <span m="399312">now</span> <span m="399727">in</span>
  <span m="400141">its</span> <span m="400556">own</span> <span m="400970">pipeline</span>
  <span m="401385">stage.</span></p><p><span m="401800">So</span> <span m="402232">the</span>
  <span m="402664">clock</span> <span m="403096">period</span> <span m="403528">will</span>
  <span m="403960">now</span> <span m="404392">be</span> <span m="404824">determined</span>
  <span m="405256">by</span> <span m="405688">the</span> <span m="406120">slowest</span>
  <span m="406552">of</span> <span m="406984">these</span> <span m="407416">components.</span></p><p><span
  m="407849">Having</span> <span m="408236">divided</span> <span m="408624">instruction</span>
  <span m="409012">execution</span> <span m="409399">into</span> <span m="409787">five</span>
  <span m="410175">stages,</span> <span m="410562">would</span> <span m="410950">we</span>
  <span m="411338">expect</span> <span m="411725">the</span> <span m="412113">clock</span>
  <span m="412501">period</span> <span m="412889">to</span> <span m="413256">be</span>
  <span m="413624">one</span> <span m="413991">fifth</span> <span m="414359">of</span>
  <span m="414727">its</span> <span m="415094">original</span> <span m="415462">value?</span></p><p><span
  m="415830">Well,</span> <span m="416101">that</span> <span m="416372">would</span>
  <span m="416643">only</span> <span m="416914">happen</span> <span m="417185">if</span>
  <span m="417457">we</span> <span m="417728">were</span> <span m="417999">able</span>
  <span m="418270">to</span> <span m="418541">divide</span> <span m="418812">the</span>
  <span m="419084">execution</span> <span m="419355">so</span> <span m="419626">that</span>
  <span m="419897">each</span> <span m="420168">stage</span> <span m="420440">performed</span>
  <span m="420850">exactly</span> <span m="421260">one</span> <span m="421670">fifth</span>
  <span m="422080">of</span> <span m="422490">the</span> <span m="422900">total</span>
  <span m="423310">work.</span></p><p><span m="423720">In</span> <span m="424033">real</span>
  <span m="424347">life,</span> <span m="424660">the</span> <span m="424974">major</span>
  <span m="425287">components</span> <span m="425601">have</span> <span m="425915">somewhat</span>
  <span m="426228">different</span> <span m="426542">latencies,</span> <span m="426855">so</span>
  <span m="427169">the</span> <span m="427482">improvement</span> <span m="427796">in</span>
  <span m="428110">instruction</span> <span m="428433">throughput</span> <span m="428757">will</span>
  <span m="429081">be</span> <span m="429404">a</span> <span m="429728">little</span>
  <span m="430052">less</span> <span m="430375">than</span> <span m="430699">the</span>
  <span m="431023">factor</span> <span m="431346">of</span> <span m="431670">5</span>
  <span m="431994">a</span> <span m="432317">perfect</span> <span m="432641">5-stage</span>
  <span m="432965">pipeline</span> <span m="433289">could</span> <span m="434389">achieve.</span></p><p><span
  m="435490">If</span> <span m="435855">we</span> <span m="436221">have</span> <span
  m="436586">a</span> <span m="436952">slow</span> <span m="437318">component,</span>
  <span m="437683">e.g.,</span> <span m="438049">the</span> <span m="438415">ALU,</span>
  <span m="438780">we</span> <span m="439146">might</span> <span m="439511">choose</span>
  <span m="439877">to</span> <span m="440243">pipeline</span> <span m="440608">that</span>
  <span m="440974">component</span> <span m="441340">into</span> <span m="441800">further</span>
  <span m="442261">stages,</span> <span m="442722">or,</span> <span m="443183">interleave</span>
  <span m="443644">multiple</span> <span m="444105">ALUs</span> <span m="444565">to</span>
  <span m="445026">achieve</span> <span m="445487">the</span> <span m="445948">same</span>
  <span m="446409">effect.</span></p><p><span m="446870">But</span> <span m="447281">for</span>
  <span m="447693">this</span> <span m="448105">lecture,</span> <span m="448516">we'll</span>
  <span m="448928">go</span> <span m="449340">with</span> <span m="449751">the</span>
  <span m="450163">5-stage</span> <span m="450575">pipeline</span> <span m="450986">described</span>
  <span m="451398">above.</span></p><p><span m="451810">So</span> <span m="452222">why</span>
  <span m="452635">isn't</span> <span m="453048">this</span> <span m="453460">a</span>
  <span m="453873">20-minute</span> <span m="454286">lecture?</span></p><p><span m="454699">After</span>
  <span m="455067">all</span> <span m="455436">we</span> <span m="455805">know</span>
  <span m="456174">how</span> <span m="456543">pipeline</span> <span m="456912">combinational</span>
  <span m="457281">circuits:</span> <span m="457650">We</span> <span m="458006">can</span>
  <span m="458362">build</span> <span m="458718">a</span> <span m="459075">valid</span>
  <span m="459431">k-stage</span> <span m="459787">pipeline</span> <span m="460143">by</span>
  <span m="460500">drawing</span> <span m="460856">k</span> <span m="461212">contours</span>
  <span m="461568">across</span> <span m="461925">the</span> <span m="462281">circuit</span>
  <span m="462637">diagram</span> <span m="462993">and</span> <span m="463350">adding</span>
  <span m="463742">a</span> <span m="464134">pipeline</span> <span m="464526">register</span>
  <span m="464918">wherever</span> <span m="465310">a</span> <span m="465702">contour</span>
  <span m="466094">crosses</span> <span m="466486">a</span> <span m="466878">signal.</span></p><p><span
  m="467270">What's</span> <span m="467670">the</span> <span m="468070">big</span>
  <span m="468470">deal</span> <span m="468870">here?</span></p><p><span m="469270">Well,</span>
  <span m="469716">is</span> <span m="470162">this</span> <span m="470608">circuit</span>
  <span m="471054">combinational?</span></p><p><span m="471500">No!</span></p><p><span
  m="472500">There's</span> <span m="472895">state</span> <span m="473291">in</span>
  <span m="473687">the</span> <span m="474082">registers</span> <span m="474478">and</span>
  <span m="474874">memories.</span></p><p><span m="475270">This</span> <span m="475539">means</span>
  <span m="475809">that</span> <span m="476079">the</span> <span m="476349">result</span>
  <span m="476619">of</span> <span m="476889">executing</span> <span m="477159">a</span>
  <span m="477429">given</span> <span m="477699">instruction</span> <span m="477969">may</span>
  <span m="478239">depend</span> <span m="478509">on</span> <span m="478779">the</span>
  <span m="479049">results</span> <span m="479319">from</span> <span m="480082">earlier</span>
  <span m="480846">instructions.</span></p><p><span m="481610">There</span> <span
  m="481915">are</span> <span m="482220">loops</span> <span m="482526">in</span> <span
  m="482831">the</span> <span m="483136">circuit</span> <span m="483442">where</span>
  <span m="483747">data</span> <span m="484052">from</span> <span m="484358">later</span>
  <span m="484663">pipeline</span> <span m="484968">stages</span> <span m="485274">affects</span>
  <span m="485579">the</span> <span m="485884">execution</span> <span m="486190">of</span>
  <span m="486739">earlier</span> <span m="487289">pipeline</span> <span m="487839">stages.</span></p><p><span
  m="488389">For</span> <span m="488680">example,</span> <span m="488971">the</span>
  <span m="489262">write</span> <span m="489553">to</span> <span m="489844">the</span>
  <span m="490135">register</span> <span m="490426">file</span> <span m="490717">at</span>
  <span m="491009">the</span> <span m="491300">end</span> <span m="491591">of</span>
  <span m="491882">the</span> <span m="492173">WB</span> <span m="492464">stage</span>
  <span m="492755">will</span> <span m="493046">change</span> <span m="493337">values</span>
  <span m="493629">read</span> <span m="493919">from</span> <span m="494209">the</span>
  <span m="494499">register</span> <span m="494789">file</span> <span m="495079">in</span>
  <span m="495369">the</span> <span m="495659">RF</span> <span m="495949">stage.</span></p><p><span
  m="496240">In</span> <span m="496718">other</span> <span m="497196">words,</span>
  <span m="497674">there</span> <span m="498153">are</span> <span m="498631">execution</span>
  <span m="499109">dependencies</span> <span m="499587">between</span> <span m="500066">instructions</span>
  <span m="500544">and</span> <span m="501022">these</span> <span m="501500">dependencies</span>
  <span m="501979">will</span> <span m="502367">need</span> <span m="502756">to</span>
  <span m="503144">be</span> <span m="503533">taken</span> <span m="503921">into</span>
  <span m="504310">account</span> <span m="504699">when</span> <span m="505087">we're</span>
  <span m="505476">trying</span> <span m="505864">to</span> <span m="506253">pipeline</span>
  <span m="506641">instruction</span> <span m="507030">execution.</span></p><p><span
  m="507419">We'll</span> <span m="507867">be</span> <span m="508316">addressing</span>
  <span m="508764">these</span> <span m="509213">issues</span> <span m="509662">as</span>
  <span m="510110">we</span> <span m="510559">examine</span> <span m="511008">the</span>
  <span m="511456">operation</span> <span m="511905">of</span> <span m="512354">our</span>
  <span m="512802">execution</span> <span m="513251">pipeline.</span></p><p><span
  m="513700">Sometimes</span> <span m="513986">execution</span> <span m="514272">of</span>
  <span m="514559">a</span> <span m="514845">given</span> <span m="515132">instruction</span>
  <span m="515418">will</span> <span m="515705">depend</span> <span m="515991">on</span>
  <span m="516277">the</span> <span m="516564">results</span> <span m="516850">of</span>
  <span m="517137">executing</span> <span m="517423">a</span> <span m="517710">previous</span>
  <span m="518360">instruction.</span></p><p><span m="519010">Two</span> <span m="519581">are</span>
  <span m="520152">two</span> <span m="520724">types</span> <span m="521295">of</span>
  <span m="521867">problematic</span> <span m="522438">dependencies.</span></p><p><span
  m="523010">The</span> <span m="523340">first,</span> <span m="523671">termed</span>
  <span m="524002">a</span> <span m="524332">data</span> <span m="524663">hazard,</span>
  <span m="524994">occurs</span> <span m="525324">when</span> <span m="525655">the</span>
  <span m="525986">execution</span> <span m="526316">of</span> <span m="526647">the</span>
  <span m="526978">current</span> <span m="527308">instruction</span> <span m="527639">depends</span>
  <span m="527970">on</span> <span m="528300">data</span> <span m="528630">produced</span>
  <span m="528960">by</span> <span m="529290">an</span> <span m="529620">earlier</span>
  <span m="529950">instruction.</span></p><p><span m="530280">For</span> <span m="530676">example,</span>
  <span m="531073">an</span> <span m="531470">instruction</span> <span m="531866">that</span>
  <span m="532263">reads</span> <span m="532660">R0</span> <span m="533056">will</span>
  <span m="533453">depend</span> <span m="533850">on</span> <span m="534246">the</span>
  <span m="534643">execution</span> <span m="535040">of</span> <span m="535436">an</span>
  <span m="535833">earlier</span> <span m="536230">instruction</span> <span m="536735">that</span>
  <span m="537240">wrote</span> <span m="537745">R0.</span></p><p><span m="538250">The</span>
  <span m="538583">second,</span> <span m="538917">termed</span> <span m="539250">a</span>
  <span m="539584">control</span> <span m="539917">hazard,</span> <span m="540251">occurs</span>
  <span m="540585">when</span> <span m="540918">a</span> <span m="541252">branch,</span>
  <span m="541585">jump,</span> <span m="541919">or</span> <span m="542252">exception</span>
  <span m="542586">changes</span> <span m="542920">the</span> <span m="543402">order</span>
  <span m="543885">of</span> <span m="544367">execution.</span></p><p><span m="544850">For</span>
  <span m="545167">example,</span> <span m="545484">the</span> <span m="545802">choice</span>
  <span m="546119">of</span> <span m="546436">which</span> <span m="546754">instruction</span>
  <span m="547071">to</span> <span m="547388">execute</span> <span m="547706">after</span>
  <span m="548023">a</span> <span m="548340">BNE</span> <span m="548658">depends</span>
  <span m="548975">on</span> <span m="549292">whether</span> <span m="549610">the</span>
  <span m="550243">branch</span> <span m="550876">is</span> <span m="551510">taken</span>
  <span m="552143">or</span> <span m="552776">not.</span></p><p><span m="553410">Instruction</span>
  <span m="553773">execution</span> <span m="554137">triggers</span> <span m="554500">a</span>
  <span m="554864">hazard</span> <span m="555227">when</span> <span m="555591">the</span>
  <span m="555955">instruction</span> <span m="556318">on</span> <span m="556682">which</span>
  <span m="557045">it</span> <span m="557409">depends</span> <span m="557772">is</span>
  <span m="558136">also</span> <span m="558500">in</span> <span m="559018">the</span>
  <span m="559536">pipeline,</span> <span m="560054">i.e.,</span> <span m="560572">the</span>
  <span m="561090">earlier</span> <span m="561608">instruction</span> <span m="562126">hasn't</span>
  <span m="562644">finished</span> <span m="563162">execution!</span></p><p><span
  m="563680">We'll</span> <span m="564116">need</span> <span m="564553">to</span>
  <span m="564990">adjust</span> <span m="565426">execution</span> <span m="565863">in</span>
  <span m="566300">our</span> <span m="566736">pipeline</span> <span m="567173">to</span>
  <span m="567610">avoid</span> <span m="568046">these</span> <span m="568483">hazards.</span></p><p><span
  m="568920">Here's</span> <span m="569273">our</span> <span m="569626">plan</span>
  <span m="569980">of</span> <span m="570333">attack:</span> <span m="570686">We'll</span>
  <span m="571040">start</span> <span m="571393">by</span> <span m="571746">designing</span>
  <span m="572100">a</span> <span m="572453">5-stage</span> <span m="572806">pipeline</span>
  <span m="573160">that</span> <span m="573566">works</span> <span m="573972">with</span>
  <span m="574378">sequences</span> <span m="574784">of</span> <span m="575190">instructions</span>
  <span m="575596">that</span> <span m="576003">don't</span> <span m="576409">trigger</span>
  <span m="576815">hazards,</span> <span m="577221">i.e.,</span> <span m="577627">where</span>
  <span m="578033">instruction</span> <span m="578440">execution</span> <span m="578930">doesn't</span>
  <span m="579420">depend</span> <span m="579910">on</span> <span m="580400">earlier</span>
  <span m="580890">instructions</span> <span m="581380">still</span> <span m="581870">in</span>
  <span m="582360">the</span> <span m="582850">pipeline.</span></p><p><span m="583340">Then</span>
  <span m="583692">we'll</span> <span m="584045">fix</span> <span m="584398">our</span>
  <span m="584750">pipeline</span> <span m="585103">to</span> <span m="585456">deal</span>
  <span m="585809">correctly</span> <span m="586161">with</span> <span m="586514">data</span>
  <span m="586867">hazards.</span></p><p><span m="587220">And</span> <span m="587558">finally,</span>
  <span m="587896">we'll</span> <span m="588235">address</span> <span m="588573">control</span>
  <span m="588911">hazards.</span></p>
type: course
uid: 9cd7f91ab6f2ac99302f82e398d37bff

---
None