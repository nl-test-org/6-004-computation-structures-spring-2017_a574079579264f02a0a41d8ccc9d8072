---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: sz4kq_ltDrM
  parent_uid: 466d7b408925a425dc225be2f33ba665
  title: Video-YouTube-Stream
  type: Video
  uid: f9963f0047559318340a1031d2c1e191
- id: 3Play-3Play YouTube id-Stream
  media_location: sz4kq_ltDrM
  parent_uid: 466d7b408925a425dc225be2f33ba665
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 57b3a721eb5163b6a533221bc3a2f8a1
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/sz4kq_ltDrM/default.jpg
  parent_uid: 466d7b408925a425dc225be2f33ba665
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 8e114ab3db4e177f61754378a180aa22
- id: sz4kq_ltDrM.srt
  parent_uid: 466d7b408925a425dc225be2f33ba665
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v4/building-the-mmu-10-16-/sz4kq_ltDrM.srt
  title: 3play caption file
  type: null
  uid: 6486cfd21df4abfc85094098dbc15f2e
- id: sz4kq_ltDrM.pdf
  parent_uid: 466d7b408925a425dc225be2f33ba665
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v4/building-the-mmu-10-16-/sz4kq_ltDrM.pdf
  title: 3play pdf file
  type: null
  uid: e1894523428e5551740afcb64f47a619
- id: Caption-3Play YouTube id-SRT
  parent_uid: 466d7b408925a425dc225be2f33ba665
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 1b391e5d659d7501d38405493f500acb
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 466d7b408925a425dc225be2f33ba665
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 41ebf7a345beaccf32b1055ee042a0ce
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_16-02-04_300k.mp4
  parent_uid: 466d7b408925a425dc225be2f33ba665
  title: Video-Internet Archive-MP4
  type: Video
  uid: 9c35684a5c5cbd3a241ebb6ee8540062
inline_embed_id: 39650432buildingthemmu101651021851
layout: video
order_index: null
parent_uid: b7771cf86b5914541b7fdb601c53a897
related_resources_text: ''
short_url: building-the-mmu-10-16-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v4/building-the-mmu-10-16-
template_type: Embed
title: Building the MMU
transcript: <p><span m="989">There</span> <span m="1368">are</span> <span m="1747">three</span>
  <span m="2126">architectural</span> <span m="2505">parameters</span> <span m="2885">that</span>
  <span m="3264">characterize</span> <span m="3643">a</span> <span m="4022">virtual</span>
  <span m="4402">memory</span> <span m="4781">system</span> <span m="5160">and</span>
  <span m="5539">hence</span> <span m="5919">the</span> <span m="6519">architecture</span>
  <span m="7119">of</span> <span m="7719">the</span> <span m="8319">MMU.</span></p><p><span
  m="8920">P</span> <span m="9251">is</span> <span m="9583">the</span> <span m="9914">number</span>
  <span m="10246">of</span> <span m="10578">address</span> <span m="10909">bits</span>
  <span m="11241">used</span> <span m="11572">for</span> <span m="11904">the</span>
  <span m="12236">page</span> <span m="12567">offset</span> <span m="12899">in</span>
  <span m="13230">both</span> <span m="13562">virtual</span> <span m="13894">and</span>
  <span m="14225">physical</span> <span m="14557">addresses.</span></p><p><span m="14889">V</span>
  <span m="15257">is</span> <span m="15626">the</span> <span m="15994">number</span>
  <span m="16363">of</span> <span m="16731">address</span> <span m="17100">bits</span>
  <span m="17468">used</span> <span m="17837">for</span> <span m="18205">the</span>
  <span m="18574">virtual</span> <span m="18942">page</span> <span m="19311">number.</span></p><p><span
  m="19680">And</span> <span m="20059">M</span> <span m="20438">is</span> <span m="20817">the</span>
  <span m="21197">number</span> <span m="21576">of</span> <span m="21955">address</span>
  <span m="22335">bits</span> <span m="22714">used</span> <span m="23093">for</span>
  <span m="23472">the</span> <span m="23852">physical</span> <span m="24231">page</span>
  <span m="24610">number.</span></p><p><span m="24990">All</span> <span m="25329">the</span>
  <span m="25668">other</span> <span m="26007">parameters,</span> <span m="26347">listed</span>
  <span m="26686">on</span> <span m="27025">the</span> <span m="27365">right,</span>
  <span m="27704">are</span> <span m="28043">derived</span> <span m="28382">from</span>
  <span m="28722">these</span> <span m="29061">three</span> <span m="29400">parameters.</span></p><p><span
  m="29740">As</span> <span m="30133">mentioned</span> <span m="30527">earlier,</span>
  <span m="30921">the</span> <span m="31315">typical</span> <span m="31708">page</span>
  <span m="32102">size</span> <span m="32496">is</span> <span m="32890">between</span>
  <span m="33283">4KB</span> <span m="33677">and</span> <span m="34071">16KB,</span>
  <span m="34465">the</span> <span m="34858">sweet</span> <span m="35252">spot</span>
  <span m="35646">in</span> <span m="36040">the</span> <span m="36476">tradeoff</span>
  <span m="36913">between</span> <span m="37350">the</span> <span m="37787">downside</span>
  <span m="38224">of</span> <span m="38661">using</span> <span m="39098">physical</span>
  <span m="39535">memory</span> <span m="39972">to</span> <span m="40409">hold</span>
  <span m="40846">unwanted</span> <span m="41283">locations</span> <span m="41720">and</span>
  <span m="42048">the</span> <span m="42376">upside</span> <span m="42704">of</span>
  <span m="43032">reading</span> <span m="43361">as</span> <span m="43689">much</span>
  <span m="44017">as</span> <span m="44345">possible</span> <span m="44674">from</span>
  <span m="45002">secondary</span> <span m="45330">storage</span> <span m="45658">so</span>
  <span m="45987">as</span> <span m="46315">to</span> <span m="46643">amortize</span>
  <span m="46971">the</span> <span m="47300">high</span> <span m="47778">cost</span>
  <span m="48256">of</span> <span m="48735">accessing</span> <span m="49213">the</span>
  <span m="49692">initial</span> <span m="50170">word</span> <span m="50649">over</span>
  <span m="51127">as</span> <span m="51606">many</span> <span m="52084">words</span>
  <span m="52563">as</span> <span m="53041">possible.</span></p><p><span m="53520">The</span>
  <span m="53952">size</span> <span m="54385">of</span> <span m="54818">the</span>
  <span m="55250">virtual</span> <span m="55683">address</span> <span m="56116">is</span>
  <span m="56549">determined</span> <span m="56981">by</span> <span m="57414">the</span>
  <span m="57847">ISA.</span></p><p><span m="58280">We're</span> <span m="58636">now</span>
  <span m="58992">making</span> <span m="59348">the</span> <span m="59704">transition</span>
  <span m="60060">from</span> <span m="60416">32-bit</span> <span m="60773">architectures,</span>
  <span m="61129">which</span> <span m="61485">support</span> <span m="61841">a</span>
  <span m="62197">4</span> <span m="62553">gigabyte</span> <span m="62910">virtual</span>
  <span m="63456">address</span> <span m="64003">space,</span> <span m="64550">to</span>
  <span m="65097">64-bit</span> <span m="65644">architectures,</span> <span m="66191">which</span>
  <span m="66738">support</span> <span m="67285">a</span> <span m="67832">16</span>
  <span m="68379">exabyte</span> <span m="68926">virtual</span> <span m="69473">address</span>
  <span m="70020">space.</span></p><p><span m="71020">&quot;Exa&quot;</span> <span
  m="71541">is</span> <span m="72062">the</span> <span m="72583">SI</span> <span m="73104">prefix</span>
  <span m="73625">for</span> <span m="74147">10^18</span> <span m="74668">-</span>
  <span m="75189">a</span> <span m="75710">64-bit</span> <span m="76231">address</span>
  <span m="76752">can</span> <span m="77274">access</span> <span m="77795">a</span>
  <span m="78316">*lot*</span> <span m="78837">of</span> <span m="79358">memory!</span></p><p><span
  m="79880">The</span> <span m="80185">limitations</span> <span m="80491">of</span>
  <span m="80797">a</span> <span m="81103">small</span> <span m="81409">virtual</span>
  <span m="81715">address</span> <span m="82021">have</span> <span m="82327">been</span>
  <span m="82633">the</span> <span m="82939">main</span> <span m="83245">cause</span>
  <span m="83551">for</span> <span m="83857">the</span> <span m="84163">extinction</span>
  <span m="84469">of</span> <span m="84962">many</span> <span m="85456">ISAs.</span></p><p><span
  m="85950">Of</span> <span m="86330">course,</span> <span m="86710">each</span> <span
  m="87090">generation</span> <span m="87470">of</span> <span m="87850">engineers</span>
  <span m="88230">thinks</span> <span m="88610">that</span> <span m="88990">the</span>
  <span m="89370">transition</span> <span m="89750">they</span> <span m="90130">make</span>
  <span m="90510">will</span> <span m="90890">be</span> <span m="91270">the</span>
  <span m="91650">final</span> <span m="92239">one!</span></p><p><span m="92829">I</span>
  <span m="93181">can</span> <span m="93534">remember</span> <span m="93887">when</span>
  <span m="94239">we</span> <span m="94592">all</span> <span m="94945">thought</span>
  <span m="95297">that</span> <span m="95650">32</span> <span m="96003">bits</span>
  <span m="96355">was</span> <span m="96708">an</span> <span m="97061">unimaginably</span>
  <span m="97413">large</span> <span m="97766">address.</span></p><p><span m="98119">Back</span>
  <span m="98451">then</span> <span m="98783">we're</span> <span m="99116">buying</span>
  <span m="99448">memory</span> <span m="99781">by</span> <span m="100113">the</span>
  <span m="100445">megabyte</span> <span m="100778">and</span> <span m="101110">only</span>
  <span m="101443">in</span> <span m="101775">our</span> <span m="102107">fantasies</span>
  <span m="102440">did</span> <span m="102772">we</span> <span m="103105">think</span>
  <span m="103437">one</span> <span m="103770">could</span> <span m="104348">have</span>
  <span m="104927">a</span> <span m="105505">system</span> <span m="106084">with</span>
  <span m="106663">several</span> <span m="107241">thousand</span> <span m="107820">megabytes.</span></p><p><span
  m="108399">Today's</span> <span m="108732">CPU</span> <span m="109065">architects</span>
  <span m="109398">are</span> <span m="109731">feeling</span> <span m="110064">pretty</span>
  <span m="110397">smug</span> <span m="110730">about</span> <span m="111064">64</span>
  <span m="111397">bits</span> <span m="111730">-</span> <span m="112063">we'll</span>
  <span m="112396">see</span> <span m="112729">how</span> <span m="113062">they</span>
  <span m="113395">feel</span> <span m="113729">in</span> <span m="114227">a</span>
  <span m="114725">couple</span> <span m="115223">of</span> <span m="115721">decades!</span></p><p><span
  m="116219">The</span> <span m="116574">size</span> <span m="116930">of</span> <span
  m="117286">physical</span> <span m="117642">addresses</span> <span m="117997">is</span>
  <span m="118353">currently</span> <span m="118709">between</span> <span m="119065">30</span>
  <span m="119421">bits</span> <span m="119776">(for</span> <span m="120132">embedded</span>
  <span m="120488">processors</span> <span m="120844">with</span> <span m="121200">modest</span>
  <span m="121745">memory</span> <span m="122290">needs)</span> <span m="122835">and</span>
  <span m="123380">40+</span> <span m="123926">bits</span> <span m="124471">(for</span>
  <span m="125016">servers</span> <span m="125561">that</span> <span m="126107">handle</span>
  <span m="126652">large</span> <span m="127197">data</span> <span m="127742">sets).</span></p><p><span
  m="128288">Since</span> <span m="128588">CPU</span> <span m="128889">implementations</span>
  <span m="129190">are</span> <span m="129491">expected</span> <span m="129792">to</span>
  <span m="130093">change</span> <span m="130394">every</span> <span m="130694">couple</span>
  <span m="130995">of</span> <span m="131296">years,</span> <span m="131597">the</span>
  <span m="131898">choice</span> <span m="132199">of</span> <span m="132500">physical</span>
  <span m="133082">memory</span> <span m="133664">size</span> <span m="134246">can</span>
  <span m="134828">be</span> <span m="135410">adjusted</span> <span m="135992">to</span>
  <span m="136574">match</span> <span m="137156">current</span> <span m="137738">technologies.</span></p><p><span
  m="138320">Since</span> <span m="138831">programmers</span> <span m="139343">use</span>
  <span m="139855">virtual</span> <span m="140367">addresses,</span> <span m="140879">they're</span>
  <span m="141390">insulated</span> <span m="141902">from</span> <span m="142414">this</span>
  <span m="142926">implementation</span> <span m="143438">choice.</span></p><p><span
  m="143950">The</span> <span m="144296">MMU</span> <span m="144642">ensures</span>
  <span m="144988">that</span> <span m="145334">existing</span> <span m="145680">software</span>
  <span m="146026">will</span> <span m="146373">continue</span> <span m="146719">to</span>
  <span m="147065">function</span> <span m="147411">correctly</span> <span m="147757">with</span>
  <span m="148103">different</span> <span m="148450">sizes</span> <span m="149025">of</span>
  <span m="149600">physical</span> <span m="150175">memory.</span></p><p><span m="150750">The</span>
  <span m="151265">programmer</span> <span m="151781">may</span> <span m="152297">notice</span>
  <span m="152813">differences</span> <span m="153329">in</span> <span m="153845">performance,</span>
  <span m="154360">but</span> <span m="154876">not</span> <span m="155392">in</span>
  <span m="155908">basic</span> <span m="156424">functionality.</span></p><p><span
  m="156940">For</span> <span m="157376">example,</span> <span m="157812">suppose</span>
  <span m="158248">our</span> <span m="158684">system</span> <span m="159120">supported</span>
  <span m="159556">a</span> <span m="159993">32-bit</span> <span m="160429">virtual</span>
  <span m="160865">address,</span> <span m="161301">a</span> <span m="161737">30-bit</span>
  <span m="162173">physical</span> <span m="162610">address</span> <span m="163056">and</span>
  <span m="163503">a</span> <span m="163950">4KB</span> <span m="164396">page</span>
  <span m="164843">size.</span></p><p><span m="165290">So</span> <span m="165882">p</span>
  <span m="166475">=</span> <span m="167068">12,</span> <span m="167661">v</span>
  <span m="168254">=</span> <span m="168847">32-12</span> <span m="169440">=</span>
  <span m="170033">20,</span> <span m="170626">and</span> <span m="171219">m</span>
  <span m="171812">=</span> <span m="172405">30</span> <span m="172998">-</span> <span
  m="173591">12</span> <span m="174184">=</span> <span m="174777">18.</span></p><p><span
  m="175370">There</span> <span m="175880">are</span> <span m="176390">2^m</span>
  <span m="176900">physical</span> <span m="177410">pages,</span> <span m="177920">which</span>
  <span m="178430">is</span> <span m="178940">2^18</span> <span m="179450">in</span>
  <span m="179960">our</span> <span m="180470">example.</span></p><p><span m="180980">There</span>
  <span m="181489">are</span> <span m="181998">2^v</span> <span m="182507">virtual</span>
  <span m="183016">pages,</span> <span m="183525">which</span> <span m="184034">is</span>
  <span m="184543">2^20</span> <span m="185052">in</span> <span m="185561">our</span>
  <span m="186070">example.</span></p><p><span m="186580">And</span> <span m="186926">since</span>
  <span m="187273">there</span> <span m="187620">is</span> <span m="187966">one</span>
  <span m="188313">entry</span> <span m="188660">in</span> <span m="189006">the</span>
  <span m="189353">page</span> <span m="189700">map</span> <span m="190046">for</span>
  <span m="190393">each</span> <span m="190740">virtual</span> <span m="191086">page,</span>
  <span m="191433">there</span> <span m="191780">are</span> <span m="192126">2^20</span>
  <span m="192473">(approximately</span> <span m="192820">one</span> <span m="193571">million)</span>
  <span m="194323">page</span> <span m="195075">map</span> <span m="195827">entries.</span></p><p><span
  m="196579">Each</span> <span m="196955">page</span> <span m="197331">map</span>
  <span m="197707">entry</span> <span m="198084">contains</span> <span m="198460">a</span>
  <span m="198836">PPN,</span> <span m="199213">an</span> <span m="199589">R</span>
  <span m="199965">bit</span> <span m="200341">and</span> <span m="200718">a</span>
  <span m="201094">D</span> <span m="201470">bit,</span> <span m="201847">for</span>
  <span m="202223">a</span> <span m="202599">total</span> <span m="202975">of</span>
  <span m="203352">m+2</span> <span m="203728">bits,</span> <span m="204104">which</span>
  <span m="204481">is</span> <span m="204879">20</span> <span m="205277">bits</span>
  <span m="205675">in</span> <span m="206073">our</span> <span m="206471">example.</span></p><p><span
  m="206870">So</span> <span m="207305">there</span> <span m="207740">are</span> <span
  m="208176">approximately</span> <span m="208611">20</span> <span m="209047">million</span>
  <span m="209482">bits</span> <span m="209918">in</span> <span m="210353">the</span>
  <span m="210789">page</span> <span m="211224">map.</span></p><p><span m="211660">If</span>
  <span m="211938">we</span> <span m="212216">were</span> <span m="212495">thinking</span>
  <span m="212773">of</span> <span m="213051">using</span> <span m="213330">a</span>
  <span m="213608">large</span> <span m="213886">special-purpose</span> <span m="214165">static</span>
  <span m="214443">RAM</span> <span m="214721">to</span> <span m="215000">hold</span>
  <span m="215278">the</span> <span m="215556">page</span> <span m="215835">map,</span>
  <span m="216113">this</span> <span m="216391">would</span> <span m="216670">get</span>
  <span m="217563">pretty</span> <span m="218456">expensive!</span></p><p><span m="219350">But</span>
  <span m="219691">why</span> <span m="220032">use</span> <span m="220373">a</span>
  <span m="220714">special-purpose</span> <span m="221055">memory</span> <span m="221396">for</span>
  <span m="221737">the</span> <span m="222078">page</span> <span m="222419">map?</span></p><p><span
  m="222760">Why</span> <span m="222983">not</span> <span m="223207">use</span> <span
  m="223431">a</span> <span m="223654">portion</span> <span m="223878">of</span> <span
  m="224102">main</span> <span m="224325">memory,</span> <span m="224549">which</span>
  <span m="224773">we</span> <span m="224996">have</span> <span m="225220">a</span>
  <span m="225444">lot</span> <span m="225667">of</span> <span m="225891">and</span>
  <span m="226115">have</span> <span m="226338">already</span> <span m="226562">bought</span>
  <span m="226786">and</span> <span m="227010">paid</span> <span m="227840">for?</span></p><p><span
  m="228670">We</span> <span m="228905">could</span> <span m="229141">use</span> <span
  m="229376">a</span> <span m="229612">register,</span> <span m="229847">called</span>
  <span m="230083">the</span> <span m="230318">page</span> <span m="230554">map</span>
  <span m="230790">pointer,</span> <span m="231025">to</span> <span m="231261">hold</span>
  <span m="231496">the</span> <span m="231732">address</span> <span m="231967">of</span>
  <span m="232203">the</span> <span m="232438">page</span> <span m="232674">map</span>
  <span m="232910">array</span> <span m="233237">in</span> <span m="233565">main</span>
  <span m="233892">memory.</span></p><p><span m="234220">In</span> <span m="234647">other</span>
  <span m="235074">words,</span> <span m="235501">the</span> <span m="235928">page</span>
  <span m="236355">map</span> <span m="236782">would</span> <span m="237210">occupy</span>
  <span m="237637">some</span> <span m="238064">number</span> <span m="238491">of</span>
  <span m="238918">dedicated</span> <span m="239345">physical</span> <span m="239772">pages.</span></p><p><span
  m="240200">Using</span> <span m="240524">the</span> <span m="240848">desired</span>
  <span m="241172">virtual</span> <span m="241496">page</span> <span m="241820">number</span>
  <span m="242144">as</span> <span m="242468">an</span> <span m="242792">index,</span>
  <span m="243116">the</span> <span m="243440">hardware</span> <span m="243764">could</span>
  <span m="244088">perform</span> <span m="244412">the</span> <span m="244736">usual</span>
  <span m="245060">array</span> <span m="245560">access</span> <span m="246061">calculation</span>
  <span m="246562">to</span> <span m="247063">fetch</span> <span m="247563">the</span>
  <span m="248064">needed</span> <span m="248565">page</span> <span m="249066">map</span>
  <span m="249566">entry</span> <span m="250067">from</span> <span m="250568">main</span>
  <span m="251069">memory.</span></p><p><span m="251570">The</span> <span m="251886">downside</span>
  <span m="252202">of</span> <span m="252518">this</span> <span m="252834">proposed</span>
  <span m="253150">implementation</span> <span m="253466">is</span> <span m="253782">that</span>
  <span m="254098">it</span> <span m="254414">now</span> <span m="254730">takes</span>
  <span m="255046">two</span> <span m="255362">accesses</span> <span m="255678">to</span>
  <span m="255994">physical</span> <span m="256310">memory</span> <span m="256697">to</span>
  <span m="257084">perform</span> <span m="257471">one</span> <span m="257858">virtual</span>
  <span m="258245">access:</span> <span m="258632">the</span> <span m="259019">first</span>
  <span m="259406">to</span> <span m="259793">retrieve</span> <span m="260180">the</span>
  <span m="260567">page</span> <span m="260954">table</span> <span m="261341">entry</span>
  <span m="261728">needed</span> <span m="262188">for</span> <span m="262648">the</span>
  <span m="263108">virtual-to-physical</span> <span m="263568">address</span> <span
  m="264028">translation,</span> <span m="264488">and</span> <span m="264948">the</span>
  <span m="265408">second</span> <span m="265868">to</span> <span m="266328">actually</span>
  <span m="266788">access</span> <span m="267249">the</span> <span m="267769">requested</span>
  <span m="268289">location.</span></p><p><span m="268810">Once</span> <span m="269364">again,</span>
  <span m="269919">caches</span> <span m="270474">to</span> <span m="271029">the</span>
  <span m="271584">rescue.</span></p><p><span m="272139">Most</span> <span m="272554">systems</span>
  <span m="272970">incorporate</span> <span m="273385">a</span> <span m="273801">special-purpose</span>
  <span m="274216">cache,</span> <span m="274632">called</span> <span m="275047">a</span>
  <span m="275463">translation</span> <span m="275878">look-aside</span> <span m="276294">buffer</span>
  <span m="276710">(TLB),</span> <span m="277214">that</span> <span m="277719">maps</span>
  <span m="278224">virtual</span> <span m="278729">page</span> <span m="279234">numbers</span>
  <span m="279739">to</span> <span m="280244">physical</span> <span m="280749">page</span>
  <span m="281254">numbers.</span></p><p><span m="281759">The</span> <span m="282301">TLB</span>
  <span m="282844">is</span> <span m="283386">usually</span> <span m="283929">small</span>
  <span m="284472">and</span> <span m="285014">quite</span> <span m="285557">fast.</span></p><p><span
  m="286100">It's</span> <span m="286626">usually</span> <span m="287152">fully-associative</span>
  <span m="287678">to</span> <span m="288204">ensure</span> <span m="288730">the</span>
  <span m="289256">best</span> <span m="289782">possible</span> <span m="290308">hit</span>
  <span m="290834">ratio</span> <span m="291360">by</span> <span m="291886">avoiding</span>
  <span m="292412">collisions.</span></p><p><span m="292939">If</span> <span m="293212">the</span>
  <span m="293485">PPN</span> <span m="293758">is</span> <span m="294031">found</span>
  <span m="294304">by</span> <span m="294577">using</span> <span m="294851">the</span>
  <span m="295124">TLB,</span> <span m="295397">the</span> <span m="295670">access</span>
  <span m="295943">to</span> <span m="296216">main</span> <span m="296490">memory</span>
  <span m="296763">for</span> <span m="297036">the</span> <span m="297309">page</span>
  <span m="297582">table</span> <span m="297855">entry</span> <span m="298129">can</span>
  <span m="298590">be</span> <span m="299051">avoided,</span> <span m="299513">and</span>
  <span m="299974">we're</span> <span m="300436">back</span> <span m="300897">to</span>
  <span m="301358">a</span> <span m="301820">single</span> <span m="302281">physical</span>
  <span m="302743">access</span> <span m="303204">for</span> <span m="303665">each</span>
  <span m="304127">virtual</span> <span m="304588">access.</span></p><p><span m="305050">The</span>
  <span m="305440">hit</span> <span m="305831">ratio</span> <span m="306222">of</span>
  <span m="306612">a</span> <span m="307003">TLB</span> <span m="307394">is</span>
  <span m="307784">quite</span> <span m="308175">high,</span> <span m="308566">usually</span>
  <span m="308956">better</span> <span m="309347">than</span> <span m="309738">99%.</span></p><p><span
  m="310129">This</span> <span m="310415">isn't</span> <span m="310702">too</span>
  <span m="310989">surprising</span> <span m="311276">since</span> <span m="311563">locality</span>
  <span m="311850">and</span> <span m="312137">the</span> <span m="312424">notion</span>
  <span m="312711">of</span> <span m="312998">a</span> <span m="313285">working</span>
  <span m="313572">set</span> <span m="313859">suggest</span> <span m="314146">that</span>
  <span m="314433">only</span> <span m="314720">a</span> <span m="315130">small</span>
  <span m="315541">number</span> <span m="315952">of</span> <span m="316362">pages</span>
  <span m="316773">are</span> <span m="317184">in</span> <span m="317595">active</span>
  <span m="318005">use</span> <span m="318416">over</span> <span m="318827">short</span>
  <span m="319237">periods</span> <span m="319648">of</span> <span m="320059">time.</span></p><p><span
  m="320470">As</span> <span m="320887">we'll</span> <span m="321305">see</span> <span
  m="321722">in</span> <span m="322140">a</span> <span m="322557">few</span> <span
  m="322975">slides,</span> <span m="323392">there</span> <span m="323810">are</span>
  <span m="324227">interesting</span> <span m="324645">variations</span> <span m="325062">to</span>
  <span m="325480">this</span> <span m="325897">simple</span> <span m="326315">TLB</span>
  <span m="326732">page-map-in-main-memory</span> <span m="327150">architecture.</span></p><p><span
  m="328610">But</span> <span m="329138">the</span> <span m="329667">basic</span>
  <span m="330196">strategy</span> <span m="330725">will</span> <span m="331253">remain</span>
  <span m="331782">the</span> <span m="332311">same.</span></p><p><span m="332840">Putting</span>
  <span m="333200">it</span> <span m="333561">all</span> <span m="333922">together:</span>
  <span m="334283">the</span> <span m="334643">virtual</span> <span m="335004">address</span>
  <span m="335365">generated</span> <span m="335726">by</span> <span m="336086">the</span>
  <span m="336447">CPU</span> <span m="336808">is</span> <span m="337169">first</span>
  <span m="337559">processed</span> <span m="337950">by</span> <span m="338340">the</span>
  <span m="338731">TLB</span> <span m="339121">to</span> <span m="339512">see</span>
  <span m="339902">if</span> <span m="340293">the</span> <span m="340684">appropriate</span>
  <span m="341074">translation</span> <span m="341465">from</span> <span m="341855">VPN</span>
  <span m="342246">to</span> <span m="342636">PPN</span> <span m="343027">has</span>
  <span m="343417">been</span> <span m="343808">cached.</span></p><p><span m="344199">If</span>
  <span m="344707">so,</span> <span m="345216">the</span> <span m="345725">main</span>
  <span m="346234">memory</span> <span m="346743">access</span> <span m="347252">can</span>
  <span m="347761">proceed</span> <span m="348270">directly.</span></p><p><span m="348779">If</span>
  <span m="349080">the</span> <span m="349382">desired</span> <span m="349684">mapping</span>
  <span m="349985">is</span> <span m="350287">not</span> <span m="350589">in</span>
  <span m="350891">the</span> <span m="351192">TLB,</span> <span m="351494">the</span>
  <span m="351796">appropriate</span> <span m="352097">entry</span> <span m="352399">in</span>
  <span m="352701">the</span> <span m="353003">page</span> <span m="353304">map</span>
  <span m="353606">is</span> <span m="353908">accessed</span> <span m="354210">in</span>
  <span m="354853">main</span> <span m="355496">memory.</span></p><p><span m="356139">If</span>
  <span m="356411">the</span> <span m="356683">page</span> <span m="356955">is</span>
  <span m="357227">resident,</span> <span m="357500">the</span> <span m="357772">PPN</span>
  <span m="358044">field</span> <span m="358316">of</span> <span m="358589">the</span>
  <span m="358861">page</span> <span m="359133">map</span> <span m="359405">entry</span>
  <span m="359677">is</span> <span m="359950">used</span> <span m="360222">to</span>
  <span m="360494">complete</span> <span m="360766">the</span> <span m="361039">address</span>
  <span m="361664">translation.</span></p><p><span m="362289">And,</span> <span m="362695">of</span>
  <span m="363101">course,</span> <span m="363507">the</span> <span m="363913">translation</span>
  <span m="364319">is</span> <span m="364725">cached</span> <span m="365131">in</span>
  <span m="365537">the</span> <span m="365943">TLB</span> <span m="366349">so</span>
  <span m="366755">that</span> <span m="367161">subsequent</span> <span m="367567">accesses</span>
  <span m="367973">to</span> <span m="368379">this</span> <span m="368823">page</span>
  <span m="369267">can</span> <span m="369711">avoid</span> <span m="370155">the</span>
  <span m="370599">access</span> <span m="371043">to</span> <span m="371487">the</span>
  <span m="371931">page</span> <span m="372375">map.</span></p><p><span m="372819">If</span>
  <span m="373139">the</span> <span m="373460">desired</span> <span m="373780">page</span>
  <span m="374101">is</span> <span m="374422">not</span> <span m="374742">resident,</span>
  <span m="375063">the</span> <span m="375384">MMU</span> <span m="375704">triggers</span>
  <span m="376025">a</span> <span m="376346">page</span> <span m="376666">fault</span>
  <span m="376987">exception</span> <span m="377308">and</span> <span m="377628">the</span>
  <span m="377949">page</span> <span m="378270">fault</span> <span m="378616">handler</span>
  <span m="378962">code</span> <span m="379308">will</span> <span m="379654">deal</span>
  <span m="380000">with</span> <span m="380346">the</span> <span m="380692">problem.</span></p><p><span
  m="381039">Here's</span> <span m="381430">a</span> <span m="381821">final</span>
  <span m="382212">example</span> <span m="382603">showing</span> <span m="382994">all</span>
  <span m="383385">the</span> <span m="383776">pieces</span> <span m="384167">in</span>
  <span m="384558">action.</span></p><p><span m="384949">In</span> <span m="385500">this</span>
  <span m="386052">example,</span> <span m="386603">p</span> <span m="387155">=</span>
  <span m="387707">10,</span> <span m="388258">v</span> <span m="388810">=</span>
  <span m="389361">22,</span> <span m="389913">and</span> <span m="390465">m</span>
  <span m="391016">=</span> <span m="391568">14.</span></p><p><span m="392120">How</span>
  <span m="392498">many</span> <span m="392876">pages</span> <span m="393254">can</span>
  <span m="393632">reside</span> <span m="394010">in</span> <span m="394388">physical</span>
  <span m="394766">memory</span> <span m="395144">at</span> <span m="395522">one</span>
  <span m="395900">time?</span></p><p><span m="396279">There</span> <span m="397063">are</span>
  <span m="397847">2^m</span> <span m="398632">physical</span> <span m="399416">pages,</span>
  <span m="400201">so</span> <span m="400985">2^14.</span></p><p><span m="401770">How</span>
  <span m="402151">many</span> <span m="402532">entries</span> <span m="402913">are</span>
  <span m="403294">there</span> <span m="403675">in</span> <span m="404056">the</span>
  <span m="404437">page</span> <span m="404818">table?</span></p><p><span m="405199">There's</span>
  <span m="405519">one</span> <span m="405840">entry</span> <span m="406161">for</span>
  <span m="406481">each</span> <span m="406802">virtual</span> <span m="407123">page</span>
  <span m="407443">and</span> <span m="407764">there</span> <span m="408085">are</span>
  <span m="408405">2^v</span> <span m="408726">virtual</span> <span m="409047">pages,</span>
  <span m="409367">so</span> <span m="409688">there</span> <span m="410009">are</span>
  <span m="410330">2^22</span> <span m="411011">entries</span> <span m="411693">in</span>
  <span m="412374">the</span> <span m="413056">page</span> <span m="413737">table.</span></p><p><span
  m="414419">How</span> <span m="414711">many</span> <span m="415003">bits</span>
  <span m="415296">per</span> <span m="415588">entry</span> <span m="415880">in</span>
  <span m="416173">the</span> <span m="416465">page</span> <span m="416757">table?</span></p><p><span
  m="417050">Assume</span> <span m="417383">each</span> <span m="417717">entry</span>
  <span m="418051">holds</span> <span m="418385">the</span> <span m="418718">PPN,</span>
  <span m="419052">the</span> <span m="419386">resident</span> <span m="419720">bit,</span>
  <span m="420053">and</span> <span m="420387">the</span> <span m="420721">dirty</span>
  <span m="421055">bit.</span></p><p><span m="421389">Since</span> <span m="421815">the</span>
  <span m="422241">PPN</span> <span m="422667">is</span> <span m="423094">m</span>
  <span m="423520">bits,</span> <span m="423946">there</span> <span m="424373">are</span>
  <span m="424799">m+2</span> <span m="425225">bits</span> <span m="425652">in</span>
  <span m="426078">each</span> <span m="426504">entry,</span> <span m="426931">so</span>
  <span m="427357">16</span> <span m="427783">bits.</span></p><p><span m="428210">How</span>
  <span m="428703">many</span> <span m="429197">pages</span> <span m="429690">does</span>
  <span m="430184">the</span> <span m="430678">page</span> <span m="431171">table</span>
  <span m="431665">occupy?</span></p><p><span m="432159">There</span> <span m="432654">are</span>
  <span m="433150">2^v</span> <span m="433646">page</span> <span m="434142">table</span>
  <span m="434638">entries,</span> <span m="435134">each</span> <span m="435630">occupying</span>
  <span m="436126">(m+2)/8</span> <span m="436621">bytes,</span> <span m="437117">so</span>
  <span m="437613">the</span> <span m="438109">total</span> <span m="438605">size</span>
  <span m="439101">of</span> <span m="439597">the</span> <span m="440093">page</span>
  <span m="440589">table</span> <span m="441153">in</span> <span m="441717">this</span>
  <span m="442281">example</span> <span m="442846">is</span> <span m="443410">2^23</span>
  <span m="443974">bytes.</span></p><p><span m="444539">Each</span> <span m="445334">page</span>
  <span m="446129">holds</span> <span m="446924">2^p</span> <span m="447719">=</span>
  <span m="448514">2^10</span> <span m="449309">bytes,</span> <span m="450104">so</span>
  <span m="450899">the</span> <span m="451694">page</span> <span m="452489">table</span>
  <span m="453284">occupies</span> <span m="454079">2^23/2^10</span> <span m="454874">=</span>
  <span m="455669">2^13</span> <span m="456464">pages.</span></p><p><span m="457259">What</span>
  <span m="457693">fraction</span> <span m="458127">of</span> <span m="458561">virtual</span>
  <span m="458995">memory</span> <span m="459429">can</span> <span m="459864">be</span>
  <span m="460298">resident</span> <span m="460732">at</span> <span m="461166">any</span>
  <span m="461600">given</span> <span m="462034">time?</span></p><p><span m="462469">There</span>
  <span m="462887">are</span> <span m="463305">2^v</span> <span m="463723">virtual</span>
  <span m="464141">pages,</span> <span m="464559">of</span> <span m="464978">which</span>
  <span m="465396">2^m</span> <span m="465814">can</span> <span m="466232">be</span>
  <span m="466650">resident.</span></p><p><span m="467069">So</span> <span m="468069">the</span>
  <span m="469069">fraction</span> <span m="470069">of</span> <span m="471069">resident</span>
  <span m="472069">pages</span> <span m="473069">is</span> <span m="474069">2^m/2^v</span>
  <span m="475069">=</span> <span m="476069">2^14/2^22</span> <span m="477069">=</span>
  <span m="478069">1/2^8.</span></p><p><span m="479069">What</span> <span m="479645">is</span>
  <span m="480222">the</span> <span m="480799">physical</span> <span m="481375">address</span>
  <span m="481952">for</span> <span m="482529">virtual</span> <span m="483105">address</span>
  <span m="483682">0x1804?</span></p><p><span m="484259">Which</span> <span m="484872">MMU</span>
  <span m="485486">components</span> <span m="486100">are</span> <span m="486714">involved</span>
  <span m="487327">in</span> <span m="487941">the</span> <span m="488555">translation?</span></p><p><span
  m="489169">First</span> <span m="489524">we</span> <span m="489880">have</span>
  <span m="490236">to</span> <span m="490592">decompose</span> <span m="490948">the</span>
  <span m="491304">virtual</span> <span m="491659">address</span> <span m="492015">into</span>
  <span m="492371">VPN</span> <span m="492727">and</span> <span m="493083">offset.</span></p><p><span
  m="493439">The</span> <span m="493802">offset</span> <span m="494165">is</span>
  <span m="494528">the</span> <span m="494891">low-order</span> <span m="495254">10</span>
  <span m="495617">bits,</span> <span m="495980">so</span> <span m="496343">is</span>
  <span m="496706">0x004</span> <span m="497069">in</span> <span m="497432">this</span>
  <span m="497795">example.</span></p><p><span m="498159">The</span> <span m="498575">VPN</span>
  <span m="498992">is</span> <span m="499409">the</span> <span m="499825">remaining</span>
  <span m="500242">address</span> <span m="500659">bits,</span> <span m="501075">so</span>
  <span m="501492">the</span> <span m="501909">VPN</span> <span m="502325">is</span>
  <span m="502742">0x6.</span></p><p><span m="503159">Looking</span> <span m="503571">first</span>
  <span m="503983">in</span> <span m="504395">the</span> <span m="504807">TLB,</span>
  <span m="505219">we</span> <span m="505631">that</span> <span m="506043">the</span>
  <span m="506455">VPN-to-PPN</span> <span m="506867">mapping</span> <span m="507279">for</span>
  <span m="507691">VPN</span> <span m="508103">0x6</span> <span m="508515">is</span>
  <span m="508927">cached,</span> <span m="509340">so</span> <span m="509744">we</span>
  <span m="510149">can</span> <span m="510553">construct</span> <span m="510958">the</span>
  <span m="511363">physical</span> <span m="511767">address</span> <span m="512172">by</span>
  <span m="512576">concatenating</span> <span m="512981">the</span> <span m="513386">PPN</span>
  <span m="513790">(0x2)</span> <span m="514195">with</span> <span m="514599">the</span>
  <span m="515004">10-bit</span> <span m="515409">offset</span> <span m="515800">(0x4)</span>
  <span m="516191">to</span> <span m="516582">get</span> <span m="516973">a</span>
  <span m="517364">physical</span> <span m="517755">address</span> <span m="518146">of</span>
  <span m="518537">0x804.</span></p><p><span m="518929">You're</span> <span m="519434">right!</span></p><p><span
  m="519940">It's</span> <span m="520317">a</span> <span m="520694">bit</span> <span
  m="521072">of</span> <span m="521449">pain</span> <span m="521826">to</span> <span
  m="522204">do</span> <span m="522581">all</span> <span m="522958">the</span> <span
  m="523336">bit</span> <span m="523713">manipulations</span> <span m="524091">when</span>
  <span m="524468">p</span> <span m="524845">is</span> <span m="525223">not</span>
  <span m="525600">a</span> <span m="525977">multiple</span> <span m="526355">of</span>
  <span m="526732">4.</span></p><p><span m="527110">How</span> <span m="527986">about</span>
  <span m="528862">virtual</span> <span m="529738">address</span> <span m="530614">0x1080?</span></p><p><span
  m="531490">For</span> <span m="531877">this</span> <span m="532264">address</span>
  <span m="532652">the</span> <span m="533039">VPN</span> <span m="533427">is</span>
  <span m="533814">0x4</span> <span m="534201">and</span> <span m="534589">the</span>
  <span m="534976">offset</span> <span m="535364">is</span> <span m="535751">0x80.</span></p><p><span
  m="536139">The</span> <span m="536425">translation</span> <span m="536712">for</span>
  <span m="536999">VPN</span> <span m="537286">0x4</span> <span m="537573">is</span>
  <span m="537860">not</span> <span m="538146">cached</span> <span m="538433">in</span>
  <span m="538720">the</span> <span m="539007">TLB,</span> <span m="539294">so</span>
  <span m="539581">we</span> <span m="539867">have</span> <span m="540154">to</span>
  <span m="540441">check</span> <span m="540728">the</span> <span m="541015">page</span>
  <span m="541302">map,</span> <span m="541589">which</span> <span m="541923">tells</span>
  <span m="542257">us</span> <span m="542591">that</span> <span m="542926">the</span>
  <span m="543260">page</span> <span m="543594">is</span> <span m="543928">resident</span>
  <span m="544263">in</span> <span m="544597">physical</span> <span m="544931">page</span>
  <span m="545265">5.</span></p><p><span m="545600">Concatenating</span> <span m="546162">the</span>
  <span m="546725">PPN</span> <span m="547287">and</span> <span m="547850">offset,</span>
  <span m="548412">we</span> <span m="548975">get</span> <span m="549537">0x1480</span>
  <span m="550100">as</span> <span m="550662">the</span> <span m="551225">physical</span>
  <span m="551787">address.</span></p><p><span m="552350">Finally,</span> <span m="553228">how</span>
  <span m="554106">about</span> <span m="554985">virtual</span> <span m="555863">address</span>
  <span m="556741">0x0FC?</span></p><p><span m="557620">Here</span> <span m="558165">the</span>
  <span m="558710">VPN</span> <span m="559256">is</span> <span m="559801">0</span>
  <span m="560347">and</span> <span m="560892">the</span> <span m="561438">offset</span>
  <span m="561983">0xFC.</span></p><p><span m="562529">The</span> <span m="562815">mapping</span>
  <span m="563102">for</span> <span m="563389">VPN</span> <span m="563675">0</span>
  <span m="563962">is</span> <span m="564249">not</span> <span m="564536">found</span>
  <span m="564822">in</span> <span m="565109">the</span> <span m="565396">TLB</span>
  <span m="565682">and</span> <span m="565969">checking</span> <span m="566256">the</span>
  <span m="566543">page</span> <span m="566829">map</span> <span m="567116">reveals</span>
  <span m="567403">that</span> <span m="567690">VPN</span> <span m="568182">0</span>
  <span m="568675">is</span> <span m="569167">not</span> <span m="569660">resident</span>
  <span m="570153">in</span> <span m="570645">main</span> <span m="571138">memory,</span>
  <span m="571630">so</span> <span m="572123">a</span> <span m="572616">page</span>
  <span m="573108">fault</span> <span m="573601">exception</span> <span m="574093">is</span>
  <span m="574586">triggered.</span></p><p><span m="575079">There</span> <span m="575466">are</span>
  <span m="575853">a</span> <span m="576241">few</span> <span m="576628">things</span>
  <span m="577015">to</span> <span m="577403">note</span> <span m="577790">about</span>
  <span m="578177">the</span> <span m="578565">example</span> <span m="578952">TLB</span>
  <span m="579339">and</span> <span m="579727">page</span> <span m="580114">map</span>
  <span m="580501">contents.</span></p><p><span m="580889">Note</span> <span m="581223">that</span>
  <span m="581558">a</span> <span m="581893">TLB</span> <span m="582227">entry</span>
  <span m="582562">can</span> <span m="582897">be</span> <span m="583231">invalid</span>
  <span m="583566">(it's</span> <span m="583901">R</span> <span m="584235">bit</span>
  <span m="584570">is</span> <span m="584905">0).</span></p><p><span m="585240">This</span>
  <span m="585493">can</span> <span m="585746">happen</span> <span m="586000">when</span>
  <span m="586253">a</span> <span m="586506">virtual</span> <span m="586760">page</span>
  <span m="587013">is</span> <span m="587266">replaced,</span> <span m="587520">so</span>
  <span m="587773">when</span> <span m="588026">we</span> <span m="588280">change</span>
  <span m="588533">the</span> <span m="588786">R</span> <span m="589040">bit</span>
  <span m="589293">to</span> <span m="589546">0</span> <span m="589800">in</span>
  <span m="590053">the</span> <span m="590306">page</span> <span m="590560">map,</span>
  <span m="590921">we</span> <span m="591282">have</span> <span m="591643">to</span>
  <span m="592004">do</span> <span m="592365">the</span> <span m="592726">same</span>
  <span m="593087">in</span> <span m="593448">the</span> <span m="593809">TLB.</span></p><p><span
  m="594170">And</span> <span m="594561">should</span> <span m="594952">we</span>
  <span m="595344">be</span> <span m="595735">concerned</span> <span m="596126">that</span>
  <span m="596518">PPN</span> <span m="596909">0x5</span> <span m="597300">appears</span>
  <span m="597692">twice</span> <span m="598083">in</span> <span m="598474">the</span>
  <span m="598866">page</span> <span m="599257">table?</span></p><p><span m="599649">Note</span>
  <span m="600046">that</span> <span m="600443">the</span> <span m="600841">entry</span>
  <span m="601238">for</span> <span m="601636">VPN</span> <span m="602033">0x3</span>
  <span m="602430">doesn't</span> <span m="602828">matter</span> <span m="603225">since</span>
  <span m="603623">it's</span> <span m="604020">R</span> <span m="604417">bit</span>
  <span m="604815">is</span> <span m="605212">0.</span></p><p><span m="605610">Typically</span>
  <span m="605846">when</span> <span m="606083">marking</span> <span m="606320">a</span>
  <span m="606557">page</span> <span m="606794">not</span> <span m="607030">resident,</span>
  <span m="607267">we</span> <span m="607504">don't</span> <span m="607741">bother</span>
  <span m="607978">to</span> <span m="608214">clear</span> <span m="608451">out</span>
  <span m="608688">the</span> <span m="608925">other</span> <span m="609162">fields</span>
  <span m="609399">in</span> <span m="609752">the</span> <span m="610105">entry</span>
  <span m="610458">since</span> <span m="610811">they</span> <span m="611164">won't</span>
  <span m="611517">be</span> <span m="611870">used</span> <span m="612223">when</span>
  <span m="612576">R=0.</span></p><p><span m="612930">So</span> <span m="613248">there's</span>
  <span m="613567">only</span> <span m="613886">one</span> <span m="614205">*valid*</span>
  <span m="614524">mapping</span> <span m="614843">to</span> <span m="615162">PPN</span>
  <span m="615481">5.</span></p>
type: course
uid: 466d7b408925a425dc225be2f33ba665

---
None