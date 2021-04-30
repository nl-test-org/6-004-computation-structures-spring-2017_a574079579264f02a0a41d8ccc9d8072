---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: b-jgbeTojrk
  parent_uid: 9032d8207e61be9aa3c2256c68ea3856
  title: Video-YouTube-Stream
  type: Video
  uid: a1555e119ce0bcb080354ca45aa95500
- id: 3Play-3Play YouTube id-Stream
  media_location: b-jgbeTojrk
  parent_uid: 9032d8207e61be9aa3c2256c68ea3856
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 331b27235e00dbd62cb9626279698667
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/b-jgbeTojrk/default.jpg
  parent_uid: 9032d8207e61be9aa3c2256c68ea3856
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 0e1fd31b1f6cb2b87f9cf53bc7031304
- id: b-jgbeTojrk.srt
  parent_uid: 9032d8207e61be9aa3c2256c68ea3856
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v7/beta-control-signals/b-jgbeTojrk.srt
  title: 3play caption file
  type: null
  uid: c77cf8579a348d2291b4e31120b7366d
- id: b-jgbeTojrk.pdf
  parent_uid: 9032d8207e61be9aa3c2256c68ea3856
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v7/beta-control-signals/b-jgbeTojrk.pdf
  title: 3play pdf file
  type: null
  uid: e661ae7add9421d0867cb720c56dae98
- id: Caption-3Play YouTube id-SRT_1
  parent_uid: 9032d8207e61be9aa3c2256c68ea3856
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: f6d04e67a65631fdc0d8b84347142ca0
- id: Transcript-3Play YouTube id-PDF_1
  parent_uid: 9032d8207e61be9aa3c2256c68ea3856
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: a5170da230d3e9c6af279db56524590e
- id: Video-iTunesU-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_13-02-07-02_300k.mp4
  parent_uid: 9032d8207e61be9aa3c2256c68ea3856
  title: Video-iTunes U-MP4
  type: Video
  uid: d14a07cf6134a0887c16fabb14249edd
inline_embed_id: 29712549betacontrolsignals61738753
layout: video
order_index: null
parent_uid: 3d0d834e5b8172c647403cb4b646c9e8
related_resources_text: ''
short_url: beta-control-signals
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c13/c13s2/c13s2v7/beta-control-signals
template_type: Embed
title: 'Worked Example: Beta Control Signals'
transcript: <p><span m="780">In</span> <span m="1075">order</span> <span m="1370">to</span>
  <span m="1665">better</span> <span m="1960">understand</span> <span m="2255">the</span>
  <span m="2550">role</span> <span m="2845">of</span> <span m="3140">each</span> <span
  m="3435">of</span> <span m="3730">the</span> <span m="4025">beta</span> <span m="4320">control</span>
  <span m="4615">signals,</span> <span m="4910">we</span> <span m="5205">will</span>
  <span m="5500">work</span> <span m="5834">through</span> <span m="6169">an</span>
  <span m="6503">example</span> <span m="6838">problem</span> <span m="7173">that</span>
  <span m="7507">provides</span> <span m="7842">us</span> <span m="8176">with</span>
  <span m="8511">a</span> <span m="8846">partially</span> <span m="9180">filled</span>
  <span m="9515">control</span> <span m="9849">table</span> <span m="10184">for</span>
  <span m="10519">5</span> <span m="11202">different</span> <span m="11886">instructions.</span></p><p><span
  m="12570">Two</span> <span m="12888">of</span> <span m="13206">these</span> <span
  m="13524">instructions</span> <span m="13842">are</span> <span m="14160">existing</span>
  <span m="14478">beta</span> <span m="14796">instructions</span> <span m="15114">that</span>
  <span m="15432">we</span> <span m="15750">must</span> <span m="16068">infer</span>
  <span m="16386">from</span> <span m="16704">the</span> <span m="17022">provided</span>
  <span m="17340">control</span> <span m="18250">signals.</span></p><p><span m="19160">The</span>
  <span m="19469">other</span> <span m="19778">three</span> <span m="20088">are</span>
  <span m="20397">three</span> <span m="20706">new</span> <span m="21016">instructions</span>
  <span m="21325">that</span> <span m="21635">we</span> <span m="21944">are</span>
  <span m="22253">adding</span> <span m="22563">to</span> <span m="22872">our</span>
  <span m="23181">beta</span> <span m="23491">by</span> <span m="23800">modifying</span>
  <span m="24110">the</span> <span m="24513">necessary</span> <span m="24917">control</span>
  <span m="25320">signals</span> <span m="25724">to</span> <span m="26127">produce</span>
  <span m="26531">the</span> <span m="26935">desired</span> <span m="27338">behavior</span>
  <span m="27742">of</span> <span m="28145">each</span> <span m="28549">of</span>
  <span m="28952">the</span> <span m="29356">operations.</span></p><p><span m="29760">The</span>
  <span m="30055">first</span> <span m="30350">instruction</span> <span m="30645">that</span>
  <span m="30941">we</span> <span m="31236">want</span> <span m="31531">to</span>
  <span m="31827">add</span> <span m="32122">to</span> <span m="32417">our</span>
  <span m="32712">beta</span> <span m="33008">is</span> <span m="33303">an</span>
  <span m="33598">LDX</span> <span m="33894">instruction</span> <span m="34189">which</span>
  <span m="34484">is</span> <span m="34780">a</span> <span m="35228">load</span> <span
  m="35676">that</span> <span m="36124">is</span> <span m="36572">double</span> <span
  m="37020">indexed.</span></p><p><span m="37469">What</span> <span m="37747">this</span>
  <span m="38026">means</span> <span m="38305">is</span> <span m="38584">that</span>
  <span m="38862">in</span> <span m="39141">order</span> <span m="39420">to</span>
  <span m="39699">produce</span> <span m="39977">the</span> <span m="40256">effective</span>
  <span m="40535">address</span> <span m="40814">of</span> <span m="41092">the</span>
  <span m="41371">load,</span> <span m="41650">instead</span> <span m="41929">of</span>
  <span m="42233">adding</span> <span m="42538">the</span> <span m="42843">contents</span>
  <span m="43147">of</span> <span m="43452">a</span> <span m="43757">register</span>
  <span m="44061">to</span> <span m="44366">a</span> <span m="44671">constant</span>
  <span m="44976">as</span> <span m="45280">is</span> <span m="45585">done</span>
  <span m="45890">in</span> <span m="46194">the</span> <span m="46499">LD</span> <span
  m="46804">instruction,</span> <span m="47109">we</span> <span m="47519">add</span>
  <span m="47929">the</span> <span m="48339">contents</span> <span m="48749">of</span>
  <span m="49159">two</span> <span m="49569">different</span> <span m="49979">registers.</span></p><p><span
  m="50390">So</span> <span m="50674">the</span> <span m="50959">address</span> <span
  m="51243">for</span> <span m="51528">this</span> <span m="51813">load</span> <span
  m="52097">operation</span> <span m="52382">is</span> <span m="52666">the</span>
  <span m="52951">result</span> <span m="53236">of</span> <span m="53520">adding</span>
  <span m="53805">together</span> <span m="54089">the</span> <span m="54374">contents</span>
  <span m="54659">of</span> <span m="55141">registers</span> <span m="55623">Ra</span>
  <span m="56105">and</span> <span m="56587">Rb.</span></p><p><span m="57069">The</span>
  <span m="57413">contents</span> <span m="57757">of</span> <span m="58101">the</span>
  <span m="58445">memory</span> <span m="58789">location</span> <span m="59133">pointed</span>
  <span m="59477">to</span> <span m="59821">by</span> <span m="60165">this</span>
  <span m="60509">effective</span> <span m="60853">address</span> <span m="61197">are</span>
  <span m="61541">loaded</span> <span m="61885">into</span> <span m="62229">register</span>
  <span m="63094">Rc.</span></p><p><span m="63960">Finally,</span> <span m="64398">the</span>
  <span m="64836">PC</span> <span m="65275">is</span> <span m="65713">incremented</span>
  <span m="66151">by</span> <span m="66590">4</span> <span m="67028">to</span> <span
  m="67467">point</span> <span m="67905">to</span> <span m="68343">the</span> <span
  m="68782">next</span> <span m="69220">instruction.</span></p><p><span m="69659">The</span>
  <span m="69970">second</span> <span m="70281">instruction</span> <span m="70592">that</span>
  <span m="70903">we</span> <span m="71215">want</span> <span m="71526">to</span>
  <span m="71837">add</span> <span m="72148">to</span> <span m="72460">our</span>
  <span m="72771">beta</span> <span m="73082">is</span> <span m="73393">a</span> <span
  m="73705">MVZC</span> <span m="74016">instruction</span> <span m="74327">which</span>
  <span m="74638">is</span> <span m="74950">a</span> <span m="75490">move</span> <span
  m="76030">constant</span> <span m="76570">if</span> <span m="77110">zero</span>
  <span m="77650">instruction.</span></p><p><span m="78190">The</span> <span m="78551">way</span>
  <span m="78912">this</span> <span m="79273">instruction</span> <span m="79635">works</span>
  <span m="79996">is</span> <span m="80357">that</span> <span m="80718">if</span>
  <span m="81080">the</span> <span m="81441">contents</span> <span m="81802">of</span>
  <span m="82163">register</span> <span m="82525">Ra</span> <span m="82886">equal</span>
  <span m="83247">zero,</span> <span m="83608">then</span> <span m="83970">the</span>
  <span m="84464">sign</span> <span m="84958">extended</span> <span m="85452">version</span>
  <span m="85947">of</span> <span m="86441">the</span> <span m="86935">literal</span>
  <span m="87430">constant</span> <span m="87924">will</span> <span m="88418">be</span>
  <span m="88912">loaded</span> <span m="89407">into</span> <span m="89901">register</span>
  <span m="90395">Rc.</span></p><p><span m="90890">This</span> <span m="91355">is</span>
  <span m="91820">followed</span> <span m="92285">by</span> <span m="92751">incrementing</span>
  <span m="93216">the</span> <span m="93681">PC</span> <span m="94147">to</span> <span
  m="94612">point</span> <span m="95077">to</span> <span m="95543">the</span> <span
  m="96008">next</span> <span m="96473">instruction.</span></p><p><span m="96939">The</span>
  <span m="97243">third</span> <span m="97547">instruction</span> <span m="97851">that</span>
  <span m="98155">we</span> <span m="98459">want</span> <span m="98764">to</span>
  <span m="99068">add</span> <span m="99372">to</span> <span m="99676">our</span>
  <span m="99980">beta</span> <span m="100284">is</span> <span m="100589">a</span>
  <span m="100893">STR</span> <span m="101197">instruction</span> <span m="101501">which</span>
  <span m="101805">is</span> <span m="102110">a</span> <span m="102747">store</span>
  <span m="103384">relative</span> <span m="104021">instruction.</span></p><p><span
  m="104658">For</span> <span m="105027">this</span> <span m="105396">instruction,</span>
  <span m="105766">the</span> <span m="106135">effective</span> <span m="106504">address</span>
  <span m="106874">is</span> <span m="107243">computed</span> <span m="107613">by</span>
  <span m="107982">sign</span> <span m="108351">extending</span> <span m="108721">the</span>
  <span m="109090">constant</span> <span m="109460">C,</span> <span m="109939">multiplying</span>
  <span m="110419">it</span> <span m="110899">by</span> <span m="111379">4</span>
  <span m="111859">and</span> <span m="112339">adding</span> <span m="112819">it</span>
  <span m="113299">to</span> <span m="113779">PC</span> <span m="114259">+</span>
  <span m="114739">4.</span></p><p><span m="115219">The</span> <span m="115552">contents</span>
  <span m="115886">of</span> <span m="116219">register</span> <span m="116553">Rc</span>
  <span m="116886">are</span> <span m="117220">then</span> <span m="117554">stored</span>
  <span m="117887">at</span> <span m="118221">the</span> <span m="118554">memory</span>
  <span m="118888">location</span> <span m="119222">pointed</span> <span m="119555">to</span>
  <span m="119889">by</span> <span m="120222">the</span> <span m="120556">effective</span>
  <span m="120890">address</span> <span m="121591">that</span> <span m="122293">was</span>
  <span m="122995">just</span> <span m="123697">computed.</span></p><p><span m="124399">As</span>
  <span m="124796">a</span> <span m="125194">final</span> <span m="125591">step,</span>
  <span m="125989">the</span> <span m="126386">PC</span> <span m="126784">is</span>
  <span m="127181">incremented</span> <span m="127579">by</span> <span m="127976">4</span>
  <span m="128374">to</span> <span m="128771">point</span> <span m="129169">to</span>
  <span m="129566">the</span> <span m="129964">next</span> <span m="130361">instruction.</span></p><p><span
  m="130759">We</span> <span m="131090">are</span> <span m="131421">given</span> <span
  m="131752">the</span> <span m="132083">partially</span> <span m="132414">filled</span>
  <span m="132745">control</span> <span m="133076">ROM</span> <span m="133407">shown</span>
  <span m="133738">here.</span></p><p><span m="134069">It</span> <span m="134449">is</span>
  <span m="134830">our</span> <span m="135211">job</span> <span m="135591">to</span>
  <span m="135972">fill</span> <span m="136353">in</span> <span m="136734">all</span>
  <span m="137114">the</span> <span m="137495">yellow</span> <span m="137876">boxes</span>
  <span m="138257">labeled</span> <span m="138637">with</span> <span m="139018">a</span>
  <span m="139399">?.</span></p><p><span m="139780">Let's</span> <span m="140044">begin</span>
  <span m="140309">by</span> <span m="140573">looking</span> <span m="140838">at</span>
  <span m="141102">the</span> <span m="141367">top</span> <span m="141631">row</span>
  <span m="141896">of</span> <span m="142160">this</span> <span m="142425">table.</span></p><p><span
  m="142690">The</span> <span m="143012">value</span> <span m="143334">that</span>
  <span m="143656">stands</span> <span m="143978">out</span> <span m="144300">as</span>
  <span m="144622">a</span> <span m="144944">bit</span> <span m="145266">different</span>
  <span m="145588">in</span> <span m="145911">this</span> <span m="146233">row</span>
  <span m="146555">is</span> <span m="146877">the</span> <span m="147199">PCSEL</span>
  <span m="147521">value</span> <span m="147843">which</span> <span m="148165">is</span>
  <span m="148487">equal</span> <span m="148810">to</span> <span m="149370">2.</span></p><p><span
  m="149930">For</span> <span m="150428">most</span> <span m="150927">instructions</span>
  <span m="151426">PCSEL</span> <span m="151924">equals</span> <span m="152423">0,</span>
  <span m="152922">for</span> <span m="153420">branch</span> <span m="153919">instructions</span>
  <span m="154418">it</span> <span m="154916">equals</span> <span m="155415">1,</span>
  <span m="155914">and</span> <span m="156412">for</span> <span m="156911">JMP</span>
  <span m="157410">instructions</span> <span m="157897">it</span> <span m="158385">equals</span>
  <span m="158872">2.</span></p><p><span m="159360">This</span> <span m="159735">means</span>
  <span m="160111">that</span> <span m="160487">the</span> <span m="160862">instruction</span>
  <span m="161238">described</span> <span m="161614">in</span> <span m="161990">this</span>
  <span m="162365">row</span> <span m="162741">must</span> <span m="163117">be</span>
  <span m="163492">a</span> <span m="163868">JMP</span> <span m="164244">instruction.</span></p><p><span
  m="164620">Zooming</span> <span m="165013">in</span> <span m="165406">on</span>
  <span m="165799">the</span> <span m="166192">PCSEL</span> <span m="166585">control</span>
  <span m="166978">logic</span> <span m="167371">from</span> <span m="167764">the</span>
  <span m="168157">beta</span> <span m="168550">diagram,</span> <span m="168943">we</span>
  <span m="169336">see</span> <span m="169729">that</span> <span m="170122">normally</span>
  <span m="170515">PCSEL</span> <span m="170909">=</span> <span m="171271">0</span>
  <span m="171634">to</span> <span m="171996">go</span> <span m="172359">to</span>
  <span m="172722">the</span> <span m="173084">next</span> <span m="173447">instruction.</span></p><p><span
  m="173810">PCSEL</span> <span m="174244">=</span> <span m="174679">1</span> <span
  m="175114">in</span> <span m="175548">order</span> <span m="175983">to</span> <span
  m="176418">perform</span> <span m="176853">a</span> <span m="177287">branch</span>
  <span m="177722">operation,</span> <span m="178157">and</span> <span m="178591">PCSEL</span>
  <span m="179026">=</span> <span m="179461">2</span> <span m="179896">in</span> <span
  m="180330">order</span> <span m="180765">to</span> <span m="181200">perform</span>
  <span m="181634">a</span> <span m="182069">jump</span> <span m="182504">operation</span>
  <span m="182939">where</span> <span m="183354">the</span> <span m="183770">target</span>
  <span m="184186">of</span> <span m="184602">the</span> <span m="185017">jump</span>
  <span m="185433">is</span> <span m="185849">specified</span> <span m="186265">by</span>
  <span m="186681">JT,</span> <span m="187096">or</span> <span m="187512">the</span>
  <span m="187928">jump</span> <span m="188344">target.</span></p><p><span m="188760">This</span>
  <span m="189116">means</span> <span m="189472">that</span> <span m="189829">the</span>
  <span m="190185">instruction</span> <span m="190542">described</span> <span m="190898">in</span>
  <span m="191255">this</span> <span m="191611">row</span> <span m="191967">must</span>
  <span m="192324">be</span> <span m="192680">a</span> <span m="193037">JMP</span>
  <span m="193393">instruction.</span></p><p><span m="193750">The</span> <span m="194164">behavior</span>
  <span m="194578">of</span> <span m="194993">a</span> <span m="195407">JMP</span>
  <span m="195822">instruction</span> <span m="196236">is</span> <span m="196651">shown</span>
  <span m="197065">here.</span></p><p><span m="197480">The</span> <span m="197868">effective</span>
  <span m="198257">address</span> <span m="198646">is</span> <span m="199034">calculated</span>
  <span m="199423">by</span> <span m="199812">taking</span> <span m="200200">the</span>
  <span m="200589">contents</span> <span m="200978">of</span> <span m="201366">RA</span>
  <span m="201755">and</span> <span m="202144">clearing</span> <span m="202532">the</span>
  <span m="202921">bottom</span> <span m="203310">2</span> <span m="203685">bits</span>
  <span m="204061">so</span> <span m="204436">that</span> <span m="204812">the</span>
  <span m="205187">value</span> <span m="205563">becomes</span> <span m="205938">word</span>
  <span m="206314">aligned.</span></p><p><span m="206690">The</span> <span m="207032">address</span>
  <span m="207374">of</span> <span m="207716">the</span> <span m="208058">next</span>
  <span m="208400">instruction,</span> <span m="208743">which</span> <span m="209085">is</span>
  <span m="209427">PC</span> <span m="209769">+</span> <span m="210111">4,</span>
  <span m="210453">is</span> <span m="210796">stored</span> <span m="211138">in</span>
  <span m="211480">register</span> <span m="211822">Rc</span> <span m="212164">in</span>
  <span m="212506">case</span> <span m="212849">we</span> <span m="213230">need</span>
  <span m="213611">to</span> <span m="213992">return</span> <span m="214373">to</span>
  <span m="214754">the</span> <span m="215135">next</span> <span m="215516">instruction</span>
  <span m="215897">in</span> <span m="216278">the</span> <span m="216659">program.</span></p><p><span
  m="217040">The</span> <span m="217415">PC</span> <span m="217790">is</span> <span
  m="218165">then</span> <span m="218540">updated</span> <span m="218915">with</span>
  <span m="219290">the</span> <span m="219665">new</span> <span m="220040">effective</span>
  <span m="220415">address</span> <span m="220790">in</span> <span m="221165">order</span>
  <span m="221540">to</span> <span m="221915">actually</span> <span m="222290">continue</span>
  <span m="222665">execution</span> <span m="223040">at</span> <span m="223544">the</span>
  <span m="224048">destination</span> <span m="224552">of</span> <span m="225056">the</span>
  <span m="225560">JMP</span> <span m="226064">instruction.</span></p><p><span m="226569">This</span>
  <span m="226929">dataflow</span> <span m="227290">diagram</span> <span m="227651">highlights</span>
  <span m="228012">the</span> <span m="228372">required</span> <span m="228733">dataflow</span>
  <span m="229094">through</span> <span m="229455">the</span> <span m="229816">beta</span>
  <span m="230176">in</span> <span m="230537">order</span> <span m="230898">to</span>
  <span m="231259">properly</span> <span m="231620">implement</span> <span m="232242">the</span>
  <span m="232865">JMP</span> <span m="233487">instruction.</span></p><p><span m="234110">Note</span>
  <span m="234404">that</span> <span m="234698">no</span> <span m="234993">red</span>
  <span m="235287">lines</span> <span m="235581">pass</span> <span m="235876">through</span>
  <span m="236170">the</span> <span m="236465">ALU</span> <span m="236759">or</span>
  <span m="237053">memory</span> <span m="237348">because</span> <span m="237642">the</span>
  <span m="237937">ALU</span> <span m="238231">and</span> <span m="238525">memory</span>
  <span m="238820">are</span> <span m="239114">not</span> <span m="239409">used</span>
  <span m="240021">for</span> <span m="240634">this</span> <span m="241247">instruction.</span></p><p><span
  m="241860">The</span> <span m="242179">control</span> <span m="242499">signals</span>
  <span m="242819">that</span> <span m="243139">must</span> <span m="243459">be</span>
  <span m="243779">set</span> <span m="244099">in</span> <span m="244419">order</span>
  <span m="244739">to</span> <span m="245059">follow</span> <span m="245379">this</span>
  <span m="245699">path</span> <span m="246019">in</span> <span m="246339">the</span>
  <span m="246659">beta</span> <span m="246979">are</span> <span m="247299">as</span>
  <span m="247619">follows:</span> <span m="247939">WDSEL,</span> <span m="248325">or</span>
  <span m="248711">write</span> <span m="249097">data</span> <span m="249483">select,</span>
  <span m="249869">must</span> <span m="250255">be</span> <span m="250642">set</span>
  <span m="251028">to</span> <span m="251414">0</span> <span m="251800">in</span>
  <span m="252186">order</span> <span m="252572">to</span> <span m="252958">pass</span>
  <span m="253345">the</span> <span m="253731">value</span> <span m="254117">of</span>
  <span m="254503">PC</span> <span m="254889">+</span> <span m="255275">4</span> <span
  m="255661">through</span> <span m="256048">the</span> <span m="256942">WDSEL</span>
  <span m="257836">mux.</span></p><p><span m="258730">WERF,</span> <span m="259117">or</span>
  <span m="259504">write</span> <span m="259891">enable</span> <span m="260278">register</span>
  <span m="260665">file,</span> <span m="261052">must</span> <span m="261439">be</span>
  <span m="261826">set</span> <span m="262213">to</span> <span m="262600">1</span>
  <span m="262987">in</span> <span m="263374">order</span> <span m="263761">to</span>
  <span m="264148">enable</span> <span m="264535">writing</span> <span m="264922">to</span>
  <span m="265310">the</span> <span m="266013">register</span> <span m="266716">file.</span></p><p><span
  m="267419">WASEL,</span> <span m="267815">or</span> <span m="268211">write</span>
  <span m="268607">address</span> <span m="269003">select,</span> <span m="269399">must</span>
  <span m="269796">be</span> <span m="270192">set</span> <span m="270588">to</span>
  <span m="270984">0</span> <span m="271380">in</span> <span m="271776">order</span>
  <span m="272173">to</span> <span m="272569">write</span> <span m="272965">to</span>
  <span m="273361">the</span> <span m="273757">Rc</span> <span m="274153">register</span>
  <span m="274550">and</span> <span m="274961">not</span> <span m="275373">to</span>
  <span m="275785">the</span> <span m="276196">XP</span> <span m="276608">register.</span></p><p><span
  m="277020">ASEL,</span> <span m="277561">BSEL,</span> <span m="278103">and</span>
  <span m="278645">ALUFN,</span> <span m="279186">are</span> <span m="279728">all</span>
  <span m="280270">don't</span> <span m="280811">cares</span> <span m="281353">for</span>
  <span m="281895">the</span> <span m="282436">JMP</span> <span m="282978">instruction.</span></p><p><span
  m="283520">In</span> <span m="283905">addition</span> <span m="284291">MOE,</span>
  <span m="284676">which</span> <span m="285062">stands</span> <span m="285448">for</span>
  <span m="285833">memory</span> <span m="286219">output</span> <span m="286605">enable,</span>
  <span m="286990">is</span> <span m="287376">also</span> <span m="287761">a</span>
  <span m="288147">don't</span> <span m="288533">care</span> <span m="288918">because</span>
  <span m="289304">this</span> <span m="289690">instruction</span> <span m="290198">does</span>
  <span m="290707">not</span> <span m="291215">use</span> <span m="291724">the</span>
  <span m="292232">memory</span> <span m="292741">data.</span></p><p><span m="293250">The</span>
  <span m="293568">one</span> <span m="293887">control</span> <span m="294206">signal</span>
  <span m="294525">related</span> <span m="294844">to</span> <span m="295163">the</span>
  <span m="295482">memory</span> <span m="295801">that</span> <span m="296120">we</span>
  <span m="296438">do</span> <span m="296757">need</span> <span m="297076">to</span>
  <span m="297395">worry</span> <span m="297714">about</span> <span m="298033">is</span>
  <span m="298352">the</span> <span m="298671">MWR,</span> <span m="298990">or</span>
  <span m="299292">memory</span> <span m="299595">write</span> <span m="299898">read,</span>
  <span m="300201">signal</span> <span m="300503">which</span> <span m="300806">must</span>
  <span m="301109">be</span> <span m="301412">set</span> <span m="301715">to</span>
  <span m="302017">0</span> <span m="302320">so</span> <span m="302623">that</span>
  <span m="302926">no</span> <span m="303228">value</span> <span m="303531">will</span>
  <span m="303834">be</span> <span m="304137">written</span> <span m="304440">to</span>
  <span m="305310">memory.</span></p><p><span m="306180">Going</span> <span m="306491">back</span>
  <span m="306802">to</span> <span m="307113">our</span> <span m="307424">control</span>
  <span m="307735">ROM</span> <span m="308046">and</span> <span m="308357">filling</span>
  <span m="308668">in</span> <span m="308980">the</span> <span m="309291">value</span>
  <span m="309602">of</span> <span m="309913">WERF,</span> <span m="310224">we</span>
  <span m="310535">see</span> <span m="310846">that</span> <span m="311157">the</span>
  <span m="311468">control</span> <span m="311780">signals</span> <span m="312098">for</span>
  <span m="312417">the</span> <span m="312736">JMP</span> <span m="313054">instruction</span>
  <span m="313373">correspond</span> <span m="313692">to</span> <span m="314010">the</span>
  <span m="314329">dataflow</span> <span m="314648">diagram</span> <span m="314966">of</span>
  <span m="315285">the</span> <span m="315604">beta</span> <span m="315922">that</span>
  <span m="316241">we</span> <span m="316560">just</span> <span m="317293">looked</span>
  <span m="318026">at.</span></p><p><span m="318759">Moving</span> <span m="319118">on</span>
  <span m="319477">to</span> <span m="319836">row</span> <span m="320195">two</span>
  <span m="320554">of</span> <span m="320913">our</span> <span m="321272">control</span>
  <span m="321631">ROM,</span> <span m="321990">we</span> <span m="322349">see</span>
  <span m="322709">that</span> <span m="323068">now</span> <span m="323427">we</span>
  <span m="323786">have</span> <span m="324145">PCSEL</span> <span m="324504">=</span>
  <span m="324863">Z</span> <span m="325222">in</span> <span m="325581">this</span>
  <span m="325940">row.</span></p><p><span m="326300">This</span> <span m="326685">suggests</span>
  <span m="327071">that</span> <span m="327456">the</span> <span m="327842">instruction</span>
  <span m="328228">corresponding</span> <span m="328613">to</span> <span m="328999">this</span>
  <span m="329385">row</span> <span m="329770">is</span> <span m="330156">some</span>
  <span m="330541">kind</span> <span m="330927">of</span> <span m="331313">a</span>
  <span m="331698">branch</span> <span m="332084">instruction.</span></p><p><span
  m="332470">Of</span> <span m="332859">our</span> <span m="333248">two</span> <span
  m="333638">branch</span> <span m="334027">instructions,</span> <span m="334416">the</span>
  <span m="334806">one</span> <span m="335195">that</span> <span m="335584">branches</span>
  <span m="335974">when</span> <span m="336363">Z</span> <span m="336752">=</span>
  <span m="337142">1</span> <span m="337531">is</span> <span m="337920">BEQ.</span></p><p><span
  m="338310">This</span> <span m="338766">means</span> <span m="339222">that</span>
  <span m="339678">this</span> <span m="340134">row</span> <span m="340590">corresponds</span>
  <span m="341046">to</span> <span m="341502">a</span> <span m="341958">BEQ</span>
  <span m="342414">operation.</span></p><p><span m="342870">The</span> <span m="343158">rest</span>
  <span m="343447">of</span> <span m="343736">the</span> <span m="344025">control</span>
  <span m="344314">signals</span> <span m="344602">for</span> <span m="344891">the</span>
  <span m="345180">BEQ</span> <span m="345469">operation</span> <span m="345758">look</span>
  <span m="346047">just</span> <span m="346335">like</span> <span m="346624">the</span>
  <span m="346913">ones</span> <span m="347202">for</span> <span m="347491">the</span>
  <span m="347780">JMP</span> <span m="348134">because</span> <span m="348488">here</span>
  <span m="348843">too,</span> <span m="349197">the</span> <span m="349551">ALU</span>
  <span m="349906">and</span> <span m="350260">memory</span> <span m="350615">are</span>
  <span m="350969">not</span> <span m="351323">used</span> <span m="351678">so</span>
  <span m="352032">the</span> <span m="352387">only</span> <span m="352741">ALU</span>
  <span m="353095">and</span> <span m="353450">memory</span> <span m="353804">related</span>
  <span m="354159">signal</span> <span m="354605">that</span> <span m="355051">must</span>
  <span m="355497">be</span> <span m="355943">set</span> <span m="356390">is</span>
  <span m="356836">MWR</span> <span m="357282">so</span> <span m="357728">we</span>
  <span m="358175">don't</span> <span m="358621">write</span> <span m="359067">to</span>
  <span m="359513">memory.</span></p><p><span m="359960">Furthermore,</span> <span
  m="360393">like</span> <span m="360826">the</span> <span m="361260">JMP</span> <span
  m="361693">instruction,</span> <span m="362126">the</span> <span m="362560">branch</span>
  <span m="362993">instructions</span> <span m="363426">also</span> <span m="363860">store</span>
  <span m="364293">the</span> <span m="364726">return</span> <span m="365160">address</span>
  <span m="365564">in</span> <span m="365968">register</span> <span m="366372">Rc,</span>
  <span m="366776">so</span> <span m="367180">the</span> <span m="367584">behavior</span>
  <span m="367988">of</span> <span m="368392">the</span> <span m="368796">control</span>
  <span m="369200">signals</span> <span m="369604">related</span> <span m="370008">to</span>
  <span m="370412">the</span> <span m="370816">register</span> <span m="371220">file</span>
  <span m="372039">are</span> <span m="372859">all</span> <span m="373679">the</span>
  <span m="374499">same.</span></p><p><span m="375319">We</span> <span m="375594">now</span>
  <span m="375869">take</span> <span m="376145">a</span> <span m="376420">look</span>
  <span m="376696">at</span> <span m="376971">the</span> <span m="377247">third</span>
  <span m="377522">row</span> <span m="377798">of</span> <span m="378073">the</span>
  <span m="378349">control</span> <span m="378624">ROM.</span></p><p><span m="378900">In</span>
  <span m="379217">this</span> <span m="379535">row,</span> <span m="379853">we</span>
  <span m="380171">are</span> <span m="380489">actually</span> <span m="380807">told</span>
  <span m="381125">that</span> <span m="381443">the</span> <span m="381761">corresponding</span>
  <span m="382079">instruction</span> <span m="382397">is</span> <span m="382715">the</span>
  <span m="383033">newly</span> <span m="383351">added</span> <span m="383669">LDX</span>
  <span m="384674">instruction.</span></p><p><span m="385680">So</span> <span m="385936">it</span>
  <span m="386192">is</span> <span m="386448">our</span> <span m="386705">job</span>
  <span m="386961">to</span> <span m="387217">determine</span> <span m="387474">how</span>
  <span m="387730">to</span> <span m="387986">set</span> <span m="388243">the</span>
  <span m="388499">missing</span> <span m="388755">control</span> <span m="389012">signals</span>
  <span m="389268">in</span> <span m="389524">order</span> <span m="389781">to</span>
  <span m="390037">get</span> <span m="390293">the</span> <span m="390550">desired</span>
  <span m="391217">behavior</span> <span m="391885">for</span> <span m="392553">this</span>
  <span m="393221">operation.</span></p><p><span m="393889">Recall</span> <span m="394251">that</span>
  <span m="394614">the</span> <span m="394977">expected</span> <span m="395340">behavior</span>
  <span m="395703">of</span> <span m="396066">this</span> <span m="396429">instruction</span>
  <span m="396792">is</span> <span m="397155">that</span> <span m="397518">the</span>
  <span m="397881">contents</span> <span m="398244">of</span> <span m="398607">register</span>
  <span m="398970">Ra</span> <span m="399335">and</span> <span m="399701">Rb</span>
  <span m="400067">will</span> <span m="400433">be</span> <span m="400799">added</span>
  <span m="401165">together</span> <span m="401531">in</span> <span m="401897">order</span>
  <span m="402262">to</span> <span m="402628">produce</span> <span m="402994">the</span>
  <span m="403360">effective</span> <span m="403726">address</span> <span m="404092">of</span>
  <span m="404458">the</span> <span m="404824">load.</span></p><p><span m="405190">This</span>
  <span m="405557">means</span> <span m="405924">that</span> <span m="406292">we</span>
  <span m="406659">need</span> <span m="407027">to</span> <span m="407394">perform</span>
  <span m="407761">an</span> <span m="408129">ADD</span> <span m="408496">as</span>
  <span m="408864">our</span> <span m="409231">ALUFN.</span></p><p><span m="409599">We</span>
  <span m="409937">also</span> <span m="410276">need</span> <span m="410615">ASEL</span>
  <span m="410954">and</span> <span m="411293">BSEL</span> <span m="411632">equal</span>
  <span m="411971">to</span> <span m="412310">zero</span> <span m="412649">in</span>
  <span m="412988">order</span> <span m="413327">to</span> <span m="413666">pass</span>
  <span m="414005">the</span> <span m="414344">values</span> <span m="414683">of</span>
  <span m="415022">registers</span> <span m="415361">Ra</span> <span m="415700">and</span>
  <span m="416039">Rb</span> <span m="416946">to</span> <span m="417854">the</span>
  <span m="418762">ALU.</span></p><p><span m="419670">The</span> <span m="420083">complete</span>
  <span m="420496">dataflow</span> <span m="420909">through</span> <span m="421322">the</span>
  <span m="421735">register</span> <span m="422148">file,</span> <span m="422561">ALU,</span>
  <span m="422974">and</span> <span m="423387">memory</span> <span m="423800">is</span>
  <span m="424213">shown</span> <span m="424626">here.</span></p><p><span m="425040">In</span>
  <span m="425524">order</span> <span m="426008">to</span> <span m="426492">read</span>
  <span m="426976">register</span> <span m="427460">Rb</span> <span m="427944">rather</span>
  <span m="428428">than</span> <span m="428912">Rc,</span> <span m="429396">RA2SEL</span>
  <span m="429880">must</span> <span m="430364">be</span> <span m="430848">set</span>
  <span m="431332">to</span> <span m="431816">0.</span></p><p><span m="432300">As</span>
  <span m="432694">we</span> <span m="433088">just</span> <span m="433482">mentioned,</span>
  <span m="433876">ASEL</span> <span m="434270">and</span> <span m="434664">BSEL</span>
  <span m="435058">are</span> <span m="435452">set</span> <span m="435847">to</span>
  <span m="436241">0</span> <span m="436635">and</span> <span m="437029">ALUFN</span>
  <span m="437423">is</span> <span m="437817">set</span> <span m="438211">to</span>
  <span m="438605">ADD.</span></p><p><span m="439000">The</span> <span m="439359">result</span>
  <span m="439718">of</span> <span m="440078">adding</span> <span m="440437">registers</span>
  <span m="440796">Ra</span> <span m="441156">and</span> <span m="441515">Rb</span>
  <span m="441875">is</span> <span m="442234">used</span> <span m="442593">as</span>
  <span m="442953">the</span> <span m="443312">address</span> <span m="443671">of</span>
  <span m="444031">the</span> <span m="444390">load.</span></p><p><span m="444750">This</span>
  <span m="445237">is</span> <span m="445724">called</span> <span m="446211">MA,</span>
  <span m="446699">or</span> <span m="447186">memory</span> <span m="447673">address</span>
  <span m="448160">in</span> <span m="448648">the</span> <span m="449135">beta</span>
  <span m="449622">diagram.</span></p><p><span m="450110">In</span> <span m="450558">order</span>
  <span m="451006">to</span> <span m="451454">enable</span> <span m="451902">reading</span>
  <span m="452350">from</span> <span m="452798">memory,</span> <span m="453246">we</span>
  <span m="453695">set</span> <span m="454143">MWR</span> <span m="454591">to</span>
  <span m="455039">0</span> <span m="455487">and</span> <span m="455935">MOE</span>
  <span m="456383">to</span> <span m="456831">1.</span></p><p><span m="457280">This</span>
  <span m="457607">sets</span> <span m="457934">the</span> <span m="458262">read/write</span>
  <span m="458589">functionality</span> <span m="458916">to</span> <span m="459244">read,</span>
  <span m="459571">and</span> <span m="459898">enables</span> <span m="460226">an</span>
  <span m="460553">output</span> <span m="460880">to</span> <span m="461208">be</span>
  <span m="461535">read</span> <span m="461862">from</span> <span m="462190">the</span>
  <span m="462546">read</span> <span m="462903">port</span> <span m="463260">of</span>
  <span m="463616">the</span> <span m="463973">memory.</span></p><p><span m="464330">On</span>
  <span m="464708">the</span> <span m="465087">beta</span> <span m="465465">diagram,</span>
  <span m="465844">the</span> <span m="466222">read</span> <span m="466601">data</span>
  <span m="466979">is</span> <span m="467358">labeled</span> <span m="467736">MRD,</span>
  <span m="468115">or</span> <span m="468493">memory</span> <span m="468872">read</span>
  <span m="469250">data.</span></p><p><span m="469629">The</span> <span m="469888">data</span>
  <span m="470148">that</span> <span m="470407">is</span> <span m="470667">read</span>
  <span m="470926">from</span> <span m="471186">the</span> <span m="471445">memory</span>
  <span m="471705">is</span> <span m="471964">then</span> <span m="472224">passed</span>
  <span m="472483">along</span> <span m="472743">to</span> <span m="473002">the</span>
  <span m="473262">register</span> <span m="473521">file</span> <span m="473781">by</span>
  <span m="474040">setting</span> <span m="474300">WDSEL</span> <span m="474983">=</span>
  <span m="475666">2.</span></p><p><span m="476349">In</span> <span m="476968">order</span>
  <span m="477587">to</span> <span m="478207">write</span> <span m="478826">this</span>
  <span m="479445">result</span> <span m="480065">to</span> <span m="480684">register</span>
  <span m="481304">Rc,</span> <span m="481923">WERF</span> <span m="482542">=</span>
  <span m="483162">1,</span> <span m="483781">and</span> <span m="484400">WASEL</span>
  <span m="485020">=</span> <span m="485639">0.</span></p><p><span m="486259">So</span>
  <span m="486810">the</span> <span m="487362">completed</span> <span m="487914">control</span>
  <span m="488465">ROM</span> <span m="489017">for</span> <span m="489569">the</span>
  <span m="490120">LDX</span> <span m="490672">operation</span> <span m="491224">is</span>
  <span m="491775">shown</span> <span m="492327">here.</span></p><p><span m="492879">We</span>
  <span m="493240">now</span> <span m="493601">move</span> <span m="493963">on</span>
  <span m="494324">to</span> <span m="494685">the</span> <span m="495047">fourth</span>
  <span m="495408">instruction.</span></p><p><span m="495770">Here</span> <span m="496170">we</span>
  <span m="496571">see</span> <span m="496972">that</span> <span m="497372">the</span>
  <span m="497773">ALUFN</span> <span m="498174">just</span> <span m="498575">passes</span>
  <span m="498975">operand</span> <span m="499376">B</span> <span m="499777">through</span>
  <span m="500177">the</span> <span m="500578">register</span> <span m="500979">file.</span></p><p><span
  m="501380">We</span> <span m="501732">also</span> <span m="502085">see</span> <span
  m="502437">that</span> <span m="502790">WERF</span> <span m="503142">is</span> <span
  m="503495">dependent</span> <span m="503847">on</span> <span m="504200">the</span>
  <span m="504552">value</span> <span m="504905">of</span> <span m="505257">Z.</span></p><p><span
  m="505610">This</span> <span m="506021">means</span> <span m="506433">that</span>
  <span m="506845">the</span> <span m="507257">instruction</span> <span m="507669">that</span>
  <span m="508081">corresponds</span> <span m="508493">to</span> <span m="508905">this</span>
  <span m="509316">row</span> <span m="509728">is</span> <span m="510140">MVZC</span>
  <span m="510552">which</span> <span m="510964">moves</span> <span m="511376">a</span>
  <span m="511788">constant</span> <span m="512200">into</span> <span m="512761">register</span>
  <span m="513323">Rc</span> <span m="513885">if</span> <span m="514447">the</span>
  <span m="515009">contents</span> <span m="515570">of</span> <span m="516132">register</span>
  <span m="516694">Ra</span> <span m="517256">=</span> <span m="517818">0.</span></p><p><span
  m="518380">The</span> <span m="518719">way</span> <span m="519058">this</span> <span
  m="519398">instruction</span> <span m="519737">works</span> <span m="520077">is</span>
  <span m="520416">that</span> <span m="520755">BSEL</span> <span m="521095">=</span>
  <span m="521434">1</span> <span m="521774">in</span> <span m="522113">order</span>
  <span m="522452">to</span> <span m="522792">pass</span> <span m="523131">the</span>
  <span m="523471">constant</span> <span m="523810">through</span> <span m="524150">as</span>
  <span m="524602">the</span> <span m="525055">B</span> <span m="525508">operand,</span>
  <span m="525960">and</span> <span m="526413">ALUFN</span> <span m="526866">=</span>
  <span m="527318">B</span> <span m="527771">to</span> <span m="528224">pass</span>
  <span m="528676">that</span> <span m="529129">constant</span> <span m="529582">through</span>
  <span m="530034">the</span> <span m="530487">ALU.</span></p><p><span m="530940">WDSEL</span>
  <span m="531291">=</span> <span m="531642">1</span> <span m="531993">so</span> <span
  m="532344">that</span> <span m="532695">the</span> <span m="533046">output</span>
  <span m="533397">of</span> <span m="533748">the</span> <span m="534099">ALU</span>
  <span m="534450">is</span> <span m="534801">fed</span> <span m="535152">back</span>
  <span m="535503">as</span> <span m="535854">the</span> <span m="536205">write</span>
  <span m="536556">value</span> <span m="536907">for</span> <span m="537258">the</span>
  <span m="537609">register</span> <span m="537960">file.</span></p><p><span m="539610">Because</span>
  <span m="539892">WDSEL</span> <span m="540174">=</span> <span m="540456">1</span>
  <span m="540738">and</span> <span m="541020">not</span> <span m="541302">2,</span>
  <span m="541584">we</span> <span m="541866">know</span> <span m="542148">that</span>
  <span m="542431">the</span> <span m="542713">data</span> <span m="542995">coming</span>
  <span m="543277">out</span> <span m="543559">of</span> <span m="543841">the</span>
  <span m="544123">memory</span> <span m="544405">will</span> <span m="544687">be</span>
  <span m="544970">ignored</span> <span m="545383">so</span> <span m="545797">MOE</span>
  <span m="546211">can</span> <span m="546625">be</span> <span m="547038">a</span>
  <span m="547452">don't</span> <span m="547866">care.</span></p><p><span m="548280">Of</span>
  <span m="548615">course,</span> <span m="548950">MWR</span> <span m="549285">still</span>
  <span m="549620">must</span> <span m="549955">be</span> <span m="550290">set</span>
  <span m="550625">to</span> <span m="550960">0</span> <span m="551295">in</span>
  <span m="551630">order</span> <span m="551965">to</span> <span m="552300">ensure</span>
  <span m="552635">that</span> <span m="552970">we</span> <span m="553305">don't</span>
  <span m="553640">write</span> <span m="553975">any</span> <span m="554310">random</span>
  <span m="554645">values</span> <span m="554980">into</span> <span m="555593">our</span>
  <span m="556206">memory.</span></p><p><span m="556820">RA2SEL</span> <span m="557236">is</span>
  <span m="557653">also</span> <span m="558069">a</span> <span m="558486">don't</span>
  <span m="558902">care</span> <span m="559319">because</span> <span m="559735">we</span>
  <span m="560152">don't</span> <span m="560568">care</span> <span m="560985">whether</span>
  <span m="561401">Register</span> <span m="561818">Rb</span> <span m="562234">or</span>
  <span m="562651">Register</span> <span m="563067">Rc</span> <span m="563484">are</span>
  <span m="563901">passed</span> <span m="564349">through</span> <span m="564797">as</span>
  <span m="565245">the</span> <span m="565694">second</span> <span m="566142">read</span>
  <span m="566590">argument</span> <span m="567038">of</span> <span m="567487">the</span>
  <span m="567935">register</span> <span m="568383">file,</span> <span m="568831">RD2.</span></p><p><span
  m="569280">The</span> <span m="569650">reason</span> <span m="570020">we</span>
  <span m="570390">don't</span> <span m="570760">care</span> <span m="571130">is</span>
  <span m="571500">because</span> <span m="571870">the</span> <span m="572240">BSEL</span>
  <span m="572610">=</span> <span m="572980">1</span> <span m="573350">will</span>
  <span m="573720">ignore</span> <span m="574090">the</span> <span m="574460">RD2</span>
  <span m="574830">value</span> <span m="575200">and</span> <span m="575570">pass</span>
  <span m="575940">through</span> <span m="576310">the</span> <span m="576770">constant</span>
  <span m="577231">that</span> <span m="577692">comes</span> <span m="578153">directly</span>
  <span m="578614">from</span> <span m="579075">the</span> <span m="579535">instruction</span>
  <span m="579996">after</span> <span m="580457">sign</span> <span m="580918">extending</span>
  <span m="581379">it.</span></p><p><span m="581840">ASEL</span> <span m="582318">is</span>
  <span m="582797">also</span> <span m="583276">a</span> <span m="583755">don't</span>
  <span m="584234">care</span> <span m="584713">because</span> <span m="585192">the</span>
  <span m="585671">ALU</span> <span m="586150">will</span> <span m="586628">ignore</span>
  <span m="587107">the</span> <span m="587586">A</span> <span m="588065">input</span>
  <span m="588544">when</span> <span m="589023">ALUFN</span> <span m="589502">=</span>
  <span m="589981">B.</span></p><p><span m="590460">WASEL</span> <span m="590915">must</span>
  <span m="591370">be</span> <span m="591825">0</span> <span m="592280">so</span>
  <span m="592735">that</span> <span m="593190">the</span> <span m="593645">result</span>
  <span m="594100">of</span> <span m="594555">the</span> <span m="595010">operation</span>
  <span m="595465">is</span> <span m="595920">written</span> <span m="596375">into</span>
  <span m="596830">register</span> <span m="597285">Rc.</span></p><p><span m="597740">Finally,</span>
  <span m="598190">PCSEL</span> <span m="598640">=</span> <span m="599090">0</span>
  <span m="599540">to</span> <span m="599990">load</span> <span m="600440">PC</span>
  <span m="600890">+</span> <span m="601340">4</span> <span m="601790">into</span>
  <span m="602240">the</span> <span m="602690">PC</span> <span m="603140">register</span>
  <span m="603590">so</span> <span m="604040">that</span> <span m="604490">the</span>
  <span m="604940">next</span> <span m="605390">instruction</span> <span m="605840">will</span>
  <span m="606290">get</span> <span m="606988">fetched</span> <span m="607686">after</span>
  <span m="608384">this</span> <span m="609082">one.</span></p><p><span m="609780">We</span>
  <span m="610061">are</span> <span m="610343">now</span> <span m="610625">on</span>
  <span m="610907">the</span> <span m="611189">last</span> <span m="611470">row</span>
  <span m="611752">of</span> <span m="612034">our</span> <span m="612316">control</span>
  <span m="612598">ROM.</span></p><p><span m="612880">We</span> <span m="613228">know</span>
  <span m="613577">that</span> <span m="613926">this</span> <span m="614275">row</span>
  <span m="614624">must</span> <span m="614972">correspond</span> <span m="615321">to</span>
  <span m="615670">our</span> <span m="616019">third</span> <span m="616368">added</span>
  <span m="616717">instruction</span> <span m="617065">which</span> <span m="617414">is</span>
  <span m="617763">STR,</span> <span m="618112">or</span> <span m="618461">store</span>
  <span m="618810">relative.</span></p><p><span m="620370">Recall</span> <span m="620759">that</span>
  <span m="621148">this</span> <span m="621538">instruction</span> <span m="621927">writes</span>
  <span m="622316">the</span> <span m="622706">contents</span> <span m="623095">of</span>
  <span m="623484">register</span> <span m="623874">Rc</span> <span m="624263">into</span>
  <span m="624652">memory</span> <span m="625042">at</span> <span m="625431">the</span>
  <span m="625820">address</span> <span m="626210">that</span> <span m="626552">is</span>
  <span m="626895">computed</span> <span m="627237">by</span> <span m="627580">the</span>
  <span m="627922">effective</span> <span m="628265">address</span> <span m="628607">line.</span></p><p><span
  m="628950">The</span> <span m="629352">effective</span> <span m="629754">address</span>
  <span m="630156">for</span> <span m="630558">this</span> <span m="630960">instruction</span>
  <span m="631362">is</span> <span m="631765">PC</span> <span m="632167">+</span>
  <span m="632569">4</span> <span m="632971">+</span> <span m="633373">4</span> <span
  m="633775">*</span> <span m="634177">SEXT(C).</span></p><p><span m="634580">The</span>
  <span m="635285">extra</span> <span m="635990">adder,</span> <span m="636695">just</span>
  <span m="637401">under</span> <span m="638106">the</span> <span m="638811">instruction</span>
  <span m="639516">memory,</span> <span m="640222">is</span> <span m="640927">used</span>
  <span m="641632">to</span> <span m="642337">calculate</span> <span m="643043">PC</span>
  <span m="643748">+</span> <span m="644453">4</span> <span m="645158">+</span> <span
  m="645864">4</span> <span m="646569">*</span> <span m="647274">SEXT(C).</span></p><p><span
  m="647980">This</span> <span m="648457">value</span> <span m="648934">is</span>
  <span m="649411">then</span> <span m="649888">fed</span> <span m="650365">to</span>
  <span m="650842">the</span> <span m="651319">ALU</span> <span m="651796">via</span>
  <span m="652273">the</span> <span m="652750">A</span> <span m="653227">operand</span>
  <span m="653704">by</span> <span m="654181">setting</span> <span m="654658">ASEL</span>
  <span m="655135">=</span> <span m="655612">1.</span></p><p><span m="656090">Setting</span>
  <span m="656421">ALUFN</span> <span m="656752">=</span> <span m="657083">A</span>
  <span m="657414">passes</span> <span m="657745">this</span> <span m="658076">value</span>
  <span m="658407">as</span> <span m="658738">the</span> <span m="659069">output</span>
  <span m="659400">of</span> <span m="659731">the</span> <span m="660062">ALU</span>
  <span m="660393">in</span> <span m="660724">order</span> <span m="661055">to</span>
  <span m="661386">be</span> <span m="661717">used</span> <span m="662048">as</span>
  <span m="662379">the</span> <span m="662710">memory</span> <span m="663505">address.</span></p><p><span
  m="664300">This</span> <span m="664609">is</span> <span m="664918">the</span> <span
  m="665227">address</span> <span m="665536">that</span> <span m="665845">the</span>
  <span m="666155">store</span> <span m="666464">will</span> <span m="666773">write</span>
  <span m="667082">to</span> <span m="667391">in</span> <span m="667700">memory.</span></p><p><span
  m="668010">The</span> <span m="668333">value</span> <span m="668657">that</span>
  <span m="668980">will</span> <span m="669304">be</span> <span m="669627">written</span>
  <span m="669951">to</span> <span m="670274">this</span> <span m="670598">address</span>
  <span m="670921">in</span> <span m="671245">memory</span> <span m="671568">is</span>
  <span m="671892">the</span> <span m="672215">contents</span> <span m="672539">of</span>
  <span m="672862">register</span> <span m="673186">Rc.</span></p><p><span m="673510">Register</span>
  <span m="674076">Rc</span> <span m="674642">is</span> <span m="675208">fed</span>
  <span m="675774">through</span> <span m="676340">the</span> <span m="676906">register</span>
  <span m="677473">file</span> <span m="678039">by</span> <span m="678605">setting</span>
  <span m="679171">RA2SEL</span> <span m="679737">=</span> <span m="680303">1.</span></p><p><span
  m="680870">This</span> <span m="681355">makes</span> <span m="681841">RD2</span>
  <span m="682326">have</span> <span m="682812">the</span> <span m="683297">contents</span>
  <span m="683783">of</span> <span m="684268">register</span> <span m="684754">Rc.</span></p><p><span
  m="685240">This</span> <span m="685582">value</span> <span m="685924">then</span>
  <span m="686267">becomes</span> <span m="686609">the</span> <span m="686951">MWD,</span>
  <span m="687294">or</span> <span m="687636">memory</span> <span m="687978">write</span>
  <span m="688321">data</span> <span m="688663">which</span> <span m="689005">is</span>
  <span m="689348">the</span> <span m="689690">data</span> <span m="690032">that</span>
  <span m="690375">will</span> <span m="690717">be</span> <span m="691060">stored</span>
  <span m="691475">in</span> <span m="691890">the</span> <span m="692306">memory</span>
  <span m="692721">address</span> <span m="693137">that</span> <span m="693552">was</span>
  <span m="693968">produced</span> <span m="694383">by</span> <span m="694799">the</span>
  <span m="695214">ALU.</span></p><p><span m="695630">In</span> <span m="696056">order</span>
  <span m="696482">to</span> <span m="696909">enable</span> <span m="697335">writing</span>
  <span m="697762">to</span> <span m="698188">the</span> <span m="698615">memory,</span>
  <span m="699041">MWR</span> <span m="699467">must</span> <span m="699894">be</span>
  <span m="700320">set</span> <span m="700747">to</span> <span m="701173">1.</span></p><p><span
  m="701600">Since</span> <span m="701951">WERF</span> <span m="702303">=</span> <span
  m="702655">0,</span> <span m="703006">nothing</span> <span m="703358">can</span>
  <span m="703710">be</span> <span m="704061">written</span> <span m="704413">to</span>
  <span m="704765">the</span> <span m="705116">register</span> <span m="705468">file.</span></p><p><span
  m="705820">This</span> <span m="706190">means</span> <span m="706561">that</span>
  <span m="706931">the</span> <span m="707302">value</span> <span m="707672">of</span>
  <span m="708043">WDSEL</span> <span m="708414">and</span> <span m="708784">WASEL</span>
  <span m="709155">are</span> <span m="709525">don't</span> <span m="709896">cares</span>
  <span m="710267">since</span> <span m="710637">the</span> <span m="711008">register</span>
  <span m="711378">file</span> <span m="711749">won't</span> <span m="712120">be</span>
  <span m="712610">affected</span> <span m="713100">regardless</span> <span m="713590">of</span>
  <span m="714080">their</span> <span m="714570">values.</span></p><p><span m="715060">Finally,</span>
  <span m="715611">the</span> <span m="716163">PC</span> <span m="716715">is</span>
  <span m="717266">incremented</span> <span m="717818">by</span> <span m="718370">4</span>
  <span m="718921">to</span> <span m="719473">fetch</span> <span m="720025">the</span>
  <span m="720576">next</span> <span m="721128">instruction.</span></p><p><span m="721680">So</span>
  <span m="722099">our</span> <span m="722518">completed</span> <span m="722937">Control</span>
  <span m="723356">ROM</span> <span m="723775">for</span> <span m="724195">the</span>
  <span m="724614">STR</span> <span m="725033">operation</span> <span m="725452">is</span>
  <span m="725871">shown</span> <span m="726290">here.</span></p>
type: course
uid: 9032d8207e61be9aa3c2256c68ea3856

---
None