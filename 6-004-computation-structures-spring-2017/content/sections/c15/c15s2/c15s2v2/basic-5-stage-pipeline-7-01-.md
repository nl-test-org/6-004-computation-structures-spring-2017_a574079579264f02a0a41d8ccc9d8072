---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: yauQ7o1ZAAw
  parent_uid: f44d20ea52f0568d64796e02ce928e78
  title: Video-YouTube-Stream
  type: Video
  uid: 558919b0f0881fc0b1a67b202eeb2716
- id: 3Play-3Play YouTube id-Stream
  media_location: yauQ7o1ZAAw
  parent_uid: f44d20ea52f0568d64796e02ce928e78
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 2f3e9524c3d233c256ceadfd2891b4fc
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/yauQ7o1ZAAw/default.jpg
  parent_uid: f44d20ea52f0568d64796e02ce928e78
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: abbb66b1459f7310b4c6893b364cc347
- id: yauQ7o1ZAAw.srt
  parent_uid: f44d20ea52f0568d64796e02ce928e78
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v2/basic-5-stage-pipeline-7-01-/yauQ7o1ZAAw.srt
  title: 3play caption file
  type: null
  uid: 913f0f69960fe26b524d0c18c706d9e8
- id: yauQ7o1ZAAw.pdf
  parent_uid: f44d20ea52f0568d64796e02ce928e78
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v2/basic-5-stage-pipeline-7-01-/yauQ7o1ZAAw.pdf
  title: 3play pdf file
  type: null
  uid: 0c6688b0ab5c763828424c94f67873ae
- id: Caption-3Play YouTube id-SRT
  parent_uid: f44d20ea52f0568d64796e02ce928e78
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 24dd5debed8a220ca0fa142b5096d376
- id: Transcript-3Play YouTube id-PDF
  parent_uid: f44d20ea52f0568d64796e02ce928e78
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 2fa9b8935ed25fbd84de0f97b69f33cb
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_15-02-02_300k.mp4
  parent_uid: f44d20ea52f0568d64796e02ce928e78
  title: Video-Internet Archive-MP4
  type: Video
  uid: 85b3ff71bb366fbe15549ea9e36b9362
inline_embed_id: 79020449basic5stagepipeline70133753625
layout: video
order_index: null
parent_uid: cdc9d63331eee25d2831044c32aff746
related_resources_text: ''
short_url: basic-5-stage-pipeline-7-01-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v2/basic-5-stage-pipeline-7-01-
template_type: Embed
title: Basic 5-Stage Pipeline
transcript: <p><span m="500">Let's</span> <span m="787">start</span> <span m="1075">by</span>
  <span m="1362">redrawing</span> <span m="1650">and</span> <span m="1938">simplifying</span>
  <span m="2225">the</span> <span m="2513">Beta</span> <span m="2801">data</span>
  <span m="3088">path</span> <span m="3376">so</span> <span m="3664">that</span> <span
  m="3951">it</span> <span m="4239">will</span> <span m="4527">be</span> <span m="4814">easier</span>
  <span m="5102">to</span> <span m="5390">reason</span> <span m="5881">about</span>
  <span m="6373">when</span> <span m="6865">we</span> <span m="7356">add</span> <span
  m="7848">pipelining.</span></p><p><span m="8340">The</span> <span m="8674">first</span>
  <span m="9008">simplification</span> <span m="9343">is</span> <span m="9677">to</span>
  <span m="10011">focus</span> <span m="10346">on</span> <span m="10680">sequential</span>
  <span m="11015">execution</span> <span m="11349">and</span> <span m="11683">so</span>
  <span m="12018">leave</span> <span m="12352">out</span> <span m="12686">the</span>
  <span m="13021">branch</span> <span m="13355">addressing</span> <span m="13690">and</span>
  <span m="14182">PC</span> <span m="14675">mux</span> <span m="15167">logic.</span></p><p><span
  m="15660">Our</span> <span m="16150">simplified</span> <span m="16640">Beta</span>
  <span m="17130">always</span> <span m="17620">executes</span> <span m="18110">the</span>
  <span m="18600">next</span> <span m="19090">instruction</span> <span m="19580">from</span>
  <span m="20070">PC+4.</span></p><p><span m="20560">We'll</span> <span m="20975">add</span>
  <span m="21390">back</span> <span m="21806">the</span> <span m="22221">branch</span>
  <span m="22636">and</span> <span m="23052">jump</span> <span m="23467">logic</span>
  <span m="23883">when</span> <span m="24298">we</span> <span m="24713">discuss</span>
  <span m="25129">control</span> <span m="25544">hazards.</span></p><p><span m="25960">The</span>
  <span m="26267">second</span> <span m="26574">simplification</span> <span m="26881">is</span>
  <span m="27188">to</span> <span m="27495">have</span> <span m="27802">the</span>
  <span m="28109">register</span> <span m="28416">file</span> <span m="28723">appear</span>
  <span m="29030">twice</span> <span m="29337">in</span> <span m="29644">the</span>
  <span m="29951">diagram</span> <span m="30258">so</span> <span m="30565">that</span>
  <span m="30872">we</span> <span m="31180">can</span> <span m="31488">tease</span>
  <span m="31796">apart</span> <span m="32104">the</span> <span m="32412">read</span>
  <span m="32720">and</span> <span m="33028">write</span> <span m="33336">operations</span>
  <span m="33644">that</span> <span m="33952">occur</span> <span m="34260">at</span>
  <span m="34568">different</span> <span m="34876">stages</span> <span m="35184">of</span>
  <span m="35492">instruction</span> <span m="35800">execution.</span></p><p><span
  m="37710">The</span> <span m="38051">top</span> <span m="38392">Register</span>
  <span m="38734">File</span> <span m="39075">shows</span> <span m="39416">the</span>
  <span m="39758">combinational</span> <span m="40099">read</span> <span m="40440">ports,</span>
  <span m="40782">used</span> <span m="41123">to</span> <span m="41464">when</span>
  <span m="41806">reading</span> <span m="42147">the</span> <span m="42488">register</span>
  <span m="42830">operands</span> <span m="43311">in</span> <span m="43793">the</span>
  <span m="44275">RF</span> <span m="44757">stage.</span></p><p><span m="45239">The</span>
  <span m="45519">bottom</span> <span m="45799">Register</span> <span m="46079">File</span>
  <span m="46359">shows</span> <span m="46639">the</span> <span m="46919">clocked</span>
  <span m="47199">write</span> <span m="47479">port,</span> <span m="47759">used</span>
  <span m="48039">to</span> <span m="48319">write</span> <span m="48599">the</span>
  <span m="48879">result</span> <span m="49159">into</span> <span m="49440">the</span>
  <span m="49824">destination</span> <span m="50208">register</span> <span m="50592">at</span>
  <span m="50976">the</span> <span m="51360">end</span> <span m="51744">of</span>
  <span m="52128">the</span> <span m="52512">WB</span> <span m="52896">stage.</span></p><p><span
  m="53280">Physically,</span> <span m="53619">there's</span> <span m="53959">only</span>
  <span m="54299">one</span> <span m="54639">set</span> <span m="54979">of</span>
  <span m="55319">32</span> <span m="55659">registers,</span> <span m="55999">we've</span>
  <span m="56339">just</span> <span m="56679">drawn</span> <span m="57019">the</span>
  <span m="57359">read</span> <span m="57699">and</span> <span m="58039">write</span>
  <span m="58379">circuity</span> <span m="58719">as</span> <span m="59170">separate</span>
  <span m="59622">components</span> <span m="60074">in</span> <span m="60526">the</span>
  <span m="60978">diagram.</span></p><p><span m="61430">If</span> <span m="61787">we</span>
  <span m="62144">add</span> <span m="62502">pipeline</span> <span m="62859">registers</span>
  <span m="63216">to</span> <span m="63574">the</span> <span m="63931">simplified</span>
  <span m="64288">diagram,</span> <span m="64646">we</span> <span m="65003">see</span>
  <span m="65360">that</span> <span m="65718">execution</span> <span m="66075">proceeds</span>
  <span m="66432">through</span> <span m="66790">the</span> <span m="67212">five</span>
  <span m="67635">stages</span> <span m="68058">from</span> <span m="68481">top</span>
  <span m="68904">to</span> <span m="69327">bottom.</span></p><p><span m="69750">If</span>
  <span m="70125">we</span> <span m="70500">consider</span> <span m="70875">execution</span>
  <span m="71250">of</span> <span m="71625">instruction</span> <span m="72000">sequences</span>
  <span m="72375">with</span> <span m="72750">no</span> <span m="73125">data</span>
  <span m="73500">hazards,</span> <span m="73875">information</span> <span m="74250">is</span>
  <span m="74625">flowing</span> <span m="75000">down</span> <span m="75350">the</span>
  <span m="75700">pipeline</span> <span m="76050">and</span> <span m="76400">the</span>
  <span m="76750">pipeline</span> <span m="77100">will</span> <span m="77450">correctly</span>
  <span m="77800">overlap</span> <span m="78150">the</span> <span m="78500">execution</span>
  <span m="78850">of</span> <span m="79200">all</span> <span m="79550">the</span>
  <span m="79900">instructions</span> <span m="80250">in</span> <span m="80906">the</span>
  <span m="81563">pipeline.</span></p><p><span m="82220">The</span> <span m="82623">diagram</span>
  <span m="83027">shows</span> <span m="83431">the</span> <span m="83835">components</span>
  <span m="84239">needed</span> <span m="84643">to</span> <span m="85046">implement</span>
  <span m="85450">each</span> <span m="85854">of</span> <span m="86258">the</span>
  <span m="86662">five</span> <span m="87066">stages.</span></p><p><span m="87470">The</span>
  <span m="87812">IF</span> <span m="88155">stage</span> <span m="88498">contains</span>
  <span m="88841">the</span> <span m="89184">program</span> <span m="89527">counter</span>
  <span m="89870">and</span> <span m="90212">the</span> <span m="90555">main</span>
  <span m="90898">memory</span> <span m="91241">interface</span> <span m="91584">for</span>
  <span m="91927">fetching</span> <span m="92270">instructions.</span></p><p><span
  m="93270">The</span> <span m="93704">RF</span> <span m="94138">stage</span> <span
  m="94572">has</span> <span m="95006">the</span> <span m="95440">register</span>
  <span m="95874">file</span> <span m="96308">and</span> <span m="96742">operand</span>
  <span m="97176">multiplexers.</span></p><p><span m="97610">The</span> <span m="98055">ALU</span>
  <span m="98500">stage</span> <span m="98945">uses</span> <span m="99390">the</span>
  <span m="99835">operands</span> <span m="100280">and</span> <span m="100725">computes</span>
  <span m="101170">the</span> <span m="101615">result.</span></p><p><span m="102060">The</span>
  <span m="102481">MEM</span> <span m="102903">stage</span> <span m="103324">handles</span>
  <span m="103746">the</span> <span m="104167">memory</span> <span m="104589">access</span>
  <span m="105011">for</span> <span m="105432">load</span> <span m="105854">and</span>
  <span m="106275">store</span> <span m="106697">operations.</span></p><p><span m="107119">And</span>
  <span m="107610">the</span> <span m="108101">WB</span> <span m="108592">stage</span>
  <span m="109083">writes</span> <span m="109574">the</span> <span m="110065">result</span>
  <span m="110556">into</span> <span m="111047">the</span> <span m="111538">destination</span>
  <span m="112029">register.</span></p><p><span m="112520">In</span> <span m="112811">each</span>
  <span m="113103">clock</span> <span m="113395">cycle,</span> <span m="113687">each</span>
  <span m="113979">stage</span> <span m="114270">does</span> <span m="114562">its</span>
  <span m="114854">part</span> <span m="115146">in</span> <span m="115438">the</span>
  <span m="115729">execution</span> <span m="116021">of</span> <span m="116313">a</span>
  <span m="116605">particular</span> <span m="116897">instruction.</span></p><p><span
  m="117189">In</span> <span m="117629">a</span> <span m="118069">given</span> <span
  m="118509">clock</span> <span m="118949">cycle,</span> <span m="119389">there</span>
  <span m="119829">are</span> <span m="120269">five</span> <span m="120709">instructions</span>
  <span m="121149">in</span> <span m="121589">the</span> <span m="122029">pipeline.</span></p><p><span
  m="122469">Note</span> <span m="122814">that</span> <span m="123159">data</span>
  <span m="123504">accesses</span> <span m="123849">to</span> <span m="124194">main</span>
  <span m="124539">memory</span> <span m="124884">span</span> <span m="125229">almost</span>
  <span m="125574">two</span> <span m="125919">clock</span> <span m="126264">cycles.</span></p><p><span
  m="126610">Data</span> <span m="126908">accesses</span> <span m="127207">are</span>
  <span m="127506">initiated</span> <span m="127805">at</span> <span m="128103">the</span>
  <span m="128402">beginning</span> <span m="128701">of</span> <span m="129000">the</span>
  <span m="129298">MEM</span> <span m="129597">stage</span> <span m="129896">and</span>
  <span m="130195">returning</span> <span m="130493">data</span> <span m="130792">is</span>
  <span m="131091">only</span> <span m="131390">needed</span> <span m="131761">just</span>
  <span m="132132">before</span> <span m="132503">the</span> <span m="132874">end</span>
  <span m="133245">of</span> <span m="133616">the</span> <span m="133987">WB</span>
  <span m="134358">stage.</span></p><p><span m="134730">The</span> <span m="135116">memory</span>
  <span m="135503">is</span> <span m="135890">itself</span> <span m="136276">pipelined</span>
  <span m="136663">and</span> <span m="137050">can</span> <span m="137436">simultaneously</span>
  <span m="137823">finish</span> <span m="138210">the</span> <span m="138596">access</span>
  <span m="138983">from</span> <span m="139370">an</span> <span m="139756">earlier</span>
  <span m="140143">instruction</span> <span m="140530">while</span> <span m="141027">starting</span>
  <span m="141525">an</span> <span m="142022">access</span> <span m="142520">for</span>
  <span m="143017">the</span> <span m="143515">next</span> <span m="144012">instruction.</span></p><p><span
  m="144510">This</span> <span m="144805">simplified</span> <span m="145100">diagram</span>
  <span m="145395">isn't</span> <span m="145690">showing</span> <span m="145985">how</span>
  <span m="146280">the</span> <span m="146575">control</span> <span m="146870">logic</span>
  <span m="147165">is</span> <span m="147460">split</span> <span m="147755">across</span>
  <span m="148050">the</span> <span m="148345">pipeline</span> <span m="148640">stages.</span></p><p><span
  m="149730">How</span> <span m="150097">does</span> <span m="150465">that</span>
  <span m="150832">work?</span></p><p><span m="151200">Note</span> <span m="151522">that</span>
  <span m="151845">we've</span> <span m="152168">included</span> <span m="152490">instruction</span>
  <span m="152813">registers</span> <span m="153136">as</span> <span m="153458">part</span>
  <span m="153781">of</span> <span m="154104">each</span> <span m="154426">pipeline</span>
  <span m="154749">stage,</span> <span m="155072">so</span> <span m="155394">that</span>
  <span m="155717">each</span> <span m="156040">stage</span> <span m="156435">can</span>
  <span m="156831">compute</span> <span m="157227">the</span> <span m="157623">control</span>
  <span m="158019">signals</span> <span m="158415">it</span> <span m="158810">needs</span>
  <span m="159206">from</span> <span m="159602">its</span> <span m="159998">instruction</span>
  <span m="160394">register.</span></p><p><span m="160790">The</span> <span m="161111">encoded</span>
  <span m="161433">instruction</span> <span m="161755">is</span> <span m="162077">simply</span>
  <span m="162399">passed</span> <span m="162721">from</span> <span m="163043">one</span>
  <span m="163365">stage</span> <span m="163686">to</span> <span m="164008">the</span>
  <span m="164330">next</span> <span m="164652">as</span> <span m="164974">the</span>
  <span m="165296">instruction</span> <span m="165618">flows</span> <span m="165940">through</span>
  <span m="166700">the</span> <span m="167460">pipeline..</span></p><p><span m="168220">Each</span>
  <span m="168549">stage</span> <span m="168878">computes</span> <span m="169207">its</span>
  <span m="169536">control</span> <span m="169866">signals</span> <span m="170195">from</span>
  <span m="170524">the</span> <span m="170853">opcode</span> <span m="171182">field</span>
  <span m="171512">of</span> <span m="171841">its</span> <span m="172170">instruction</span>
  <span m="172499">register.</span></p><p><span m="172829">The</span> <span m="173172">RF</span>
  <span m="173516">stage</span> <span m="173859">needs</span> <span m="174203">the</span>
  <span m="174547">RA,</span> <span m="174890">RB,</span> <span m="175234">and</span>
  <span m="175578">literal</span> <span m="175921">fields</span> <span m="176265">from</span>
  <span m="176609">its</span> <span m="176952">instruction</span> <span m="177296">register.</span></p><p><span
  m="177640">And</span> <span m="178087">the</span> <span m="178535">WB</span> <span
  m="178982">stage</span> <span m="179430">needs</span> <span m="179877">the</span>
  <span m="180325">RC</span> <span m="180772">field</span> <span m="181220">from</span>
  <span m="181667">its</span> <span m="182115">instruction</span> <span m="182562">register.</span></p><p><span
  m="183010">The</span> <span m="183352">required</span> <span m="183694">logic</span>
  <span m="184036">is</span> <span m="184378">very</span> <span m="184721">similar</span>
  <span m="185063">to</span> <span m="185405">the</span> <span m="185747">unpipelined</span>
  <span m="186090">implementation,</span> <span m="186432">it's</span> <span m="186774">just</span>
  <span m="187116">been</span> <span m="187459">split</span> <span m="187911">up</span>
  <span m="188363">and</span> <span m="188816">moved</span> <span m="189268">to</span>
  <span m="189720">the</span> <span m="190173">appropriate</span> <span m="190625">pipeline</span>
  <span m="191077">stage.</span></p><p><span m="191530">We'll</span> <span m="191814">see</span>
  <span m="192099">that</span> <span m="192384">we</span> <span m="192668">will</span>
  <span m="192953">have</span> <span m="193238">to</span> <span m="193522">add</span>
  <span m="193807">some</span> <span m="194092">additional</span> <span m="194377">control</span>
  <span m="194661">logic</span> <span m="194946">to</span> <span m="195231">deal</span>
  <span m="195515">correctly</span> <span m="195800">with</span> <span m="196085">pipeline</span>
  <span m="196370">hazards.</span></p><p><span m="198459">Our</span> <span m="198829">simplified</span>
  <span m="199199">diagram</span> <span m="199569">isn't</span> <span m="199939">so</span>
  <span m="200309">simple</span> <span m="200679">anymore!</span></p><p><span m="201050">To</span>
  <span m="201393">see</span> <span m="201736">how</span> <span m="202079">the</span>
  <span m="202422">pipeline</span> <span m="202765">works,</span> <span m="203108">let's</span>
  <span m="203451">follow</span> <span m="203795">along</span> <span m="204138">as</span>
  <span m="204481">it</span> <span m="204824">executes</span> <span m="205167">this</span>
  <span m="205510">sequence</span> <span m="205853">of</span> <span m="206196">six</span>
  <span m="206540">instructions.</span></p><p><span m="207540">Note</span> <span m="207830">that</span>
  <span m="208121">the</span> <span m="208412">instructions</span> <span m="208703">are</span>
  <span m="208993">reading</span> <span m="209284">and</span> <span m="209575">writing</span>
  <span m="209866">from</span> <span m="210156">different</span> <span m="210447">registers,</span>
  <span m="210738">so</span> <span m="211029">there</span> <span m="211320">are</span>
  <span m="211860">no</span> <span m="212400">potential</span> <span m="212940">data</span>
  <span m="213480">hazards.</span></p><p><span m="214020">And</span> <span m="214412">there</span>
  <span m="214805">are</span> <span m="215198">no</span> <span m="215591">branches</span>
  <span m="215983">and</span> <span m="216376">jumps,</span> <span m="216769">so</span>
  <span m="217162">there</span> <span m="217555">are</span> <span m="217947">no</span>
  <span m="218340">potential</span> <span m="218733">control</span> <span m="219126">hazards.</span></p><p><span
  m="219519">Since</span> <span m="219873">there</span> <span m="220228">are</span>
  <span m="220582">no</span> <span m="220937">potential</span> <span m="221292">hazards,</span>
  <span m="221646">the</span> <span m="222001">instruction</span> <span m="222355">executions</span>
  <span m="222710">can</span> <span m="223065">be</span> <span m="223419">overlapped</span>
  <span m="223774">and</span> <span m="224129">their</span> <span m="224521">overlapped</span>
  <span m="224913">execution</span> <span m="225305">in</span> <span m="225697">the</span>
  <span m="226090">pipeline</span> <span m="226482">will</span> <span m="226874">work</span>
  <span m="227266">correctly.</span></p><p><span m="227659">Okay,</span> <span m="228229">here</span>
  <span m="228799">we</span> <span m="229369">go!</span></p><p><span m="229940">During</span>
  <span m="230274">cycle</span> <span m="230608">1,</span> <span m="230942">the</span>
  <span m="231276">IF</span> <span m="231610">stage</span> <span m="231944">sends</span>
  <span m="232278">the</span> <span m="232612">value</span> <span m="232947">from</span>
  <span m="233281">the</span> <span m="233615">program</span> <span m="233949">counter</span>
  <span m="234283">to</span> <span m="234617">main</span> <span m="234951">memory</span>
  <span m="235285">to</span> <span m="235620">fetch</span> <span m="235944">the</span>
  <span m="236268">first</span> <span m="236592">instruction</span> <span m="236917">(the</span>
  <span m="237241">green</span> <span m="237565">LD</span> <span m="237890">instruction),</span>
  <span m="238214">which</span> <span m="238538">will</span> <span m="238862">be</span>
  <span m="239187">stored</span> <span m="239511">in</span> <span m="239835">the</span>
  <span m="240160">RF-stage</span> <span m="240594">instruction</span> <span m="241028">register</span>
  <span m="241463">at</span> <span m="241897">the</span> <span m="242332">end</span>
  <span m="242766">of</span> <span m="243201">the</span> <span m="243635">cycle.</span></p><p><span
  m="244070">Meanwhile,</span> <span m="244516">it's</span> <span m="244963">also</span>
  <span m="245409">computing</span> <span m="245856">PC+4,</span> <span m="246303">which</span>
  <span m="246749">will</span> <span m="247196">be</span> <span m="247642">the</span>
  <span m="248089">next</span> <span m="248536">value</span> <span m="248982">of</span>
  <span m="249429">the</span> <span m="249875">program</span> <span m="250322">counter.</span></p><p><span
  m="250769">We've</span> <span m="251097">colored</span> <span m="251425">the</span>
  <span m="251753">next</span> <span m="252081">value</span> <span m="252409">blue</span>
  <span m="252737">to</span> <span m="253065">indicate</span> <span m="253394">that</span>
  <span m="253722">it's</span> <span m="254050">the</span> <span m="254378">address</span>
  <span m="254706">of</span> <span m="255034">the</span> <span m="255362">blue</span>
  <span m="255690">instruction</span> <span m="256019">in</span> <span m="256566">the</span>
  <span m="257113">sequence.</span></p><p><span m="257660">We'll</span> <span m="257938">add</span>
  <span m="258217">the</span> <span m="258495">appropriately</span> <span m="258774">colored</span>
  <span m="259053">label</span> <span m="259331">on</span> <span m="259610">the</span>
  <span m="259888">right</span> <span m="260167">of</span> <span m="260446">each</span>
  <span m="260724">pipeline</span> <span m="261003">stage</span> <span m="261281">to</span>
  <span m="261560">indicate</span> <span m="261839">which</span> <span m="262449">instruction</span>
  <span m="263059">the</span> <span m="263669">stage</span> <span m="264279">is</span>
  <span m="264889">processing.</span></p><p><span m="265500">At</span> <span m="265835">the</span>
  <span m="266170">start</span> <span m="266505">of</span> <span m="266840">cycle</span>
  <span m="267175">2,</span> <span m="267510">we</span> <span m="267845">see</span>
  <span m="268180">that</span> <span m="268515">values</span> <span m="268850">in</span>
  <span m="269185">the</span> <span m="269520">PC</span> <span m="269855">and</span>
  <span m="270190">instruction</span> <span m="270525">registers</span> <span m="270860">for</span>
  <span m="271195">the</span> <span m="271530">RF</span> <span m="272045">stage</span>
  <span m="272560">now</span> <span m="273075">correspond</span> <span m="273590">to</span>
  <span m="274105">the</span> <span m="274620">green</span> <span m="275135">instruction.</span></p><p><span
  m="275650">During</span> <span m="275946">the</span> <span m="276242">cycle</span>
  <span m="276538">the</span> <span m="276834">register</span> <span m="277130">file</span>
  <span m="277426">will</span> <span m="277722">be</span> <span m="278018">reading</span>
  <span m="278314">the</span> <span m="278610">register</span> <span m="278906">operands,</span>
  <span m="279202">in</span> <span m="279498">this</span> <span m="279794">case</span>
  <span m="280090">R1,</span> <span m="280447">which</span> <span m="280805">is</span>
  <span m="281162">needed</span> <span m="281520">for</span> <span m="281877">the</span>
  <span m="282235">green</span> <span m="282592">instruction.</span></p><p><span m="282950">Since</span>
  <span m="283318">the</span> <span m="283686">green</span> <span m="284054">instruction</span>
  <span m="284422">is</span> <span m="284791">a</span> <span m="285159">LD,</span>
  <span m="285527">ASEL</span> <span m="285895">is</span> <span m="286264">0</span>
  <span m="286632">and</span> <span m="287000">BSEL</span> <span m="287368">is</span>
  <span m="287737">1,</span> <span m="288105">selecting</span> <span m="288473">the</span>
  <span m="288841">appropriate</span> <span m="289210">values</span> <span m="289533">to</span>
  <span m="289857">be</span> <span m="290180">written</span> <span m="290504">into</span>
  <span m="290827">the</span> <span m="291151">A</span> <span m="291474">and</span>
  <span m="291798">B</span> <span m="292121">operand</span> <span m="292445">registers</span>
  <span m="292768">at</span> <span m="293092">the</span> <span m="293415">end</span>
  <span m="293739">of</span> <span m="294062">the</span> <span m="294386">cycle.</span></p><p><span
  m="294710">Concurrently,</span> <span m="295119">the</span> <span m="295528">IF</span>
  <span m="295937">stage</span> <span m="296347">is</span> <span m="296756">fetching</span>
  <span m="297165">the</span> <span m="297575">blue</span> <span m="297984">instruction</span>
  <span m="298393">from</span> <span m="298802">main</span> <span m="299212">memory</span>
  <span m="299621">and</span> <span m="300030">computing</span> <span m="300440">an</span>
  <span m="300983">updated</span> <span m="301527">PC</span> <span m="302070">value</span>
  <span m="302614">for</span> <span m="303158">the</span> <span m="303701">next</span>
  <span m="304245">cycle.</span></p><p><span m="304789">In</span> <span m="305120">cycle</span>
  <span m="305452">3,</span> <span m="305784">the</span> <span m="306115">green</span>
  <span m="306447">instruction</span> <span m="306779">is</span> <span m="307111">now</span>
  <span m="307442">in</span> <span m="307774">the</span> <span m="308106">ALU</span>
  <span m="308437">stage,</span> <span m="308769">where</span> <span m="309101">the</span>
  <span m="309433">ALU</span> <span m="309764">is</span> <span m="310096">adding</span>
  <span m="310428">the</span> <span m="310760">values</span> <span m="311073">in</span>
  <span m="311387">its</span> <span m="311701">operand</span> <span m="312015">registers</span>
  <span m="312329">(in</span> <span m="312643">this</span> <span m="312957">case</span>
  <span m="313271">the</span> <span m="313585">value</span> <span m="313898">of</span>
  <span m="314212">R1</span> <span m="314526">and</span> <span m="314840">the</span>
  <span m="315154">constant</span> <span m="315468">4)</span> <span m="315782">and</span>
  <span m="316096">the</span> <span m="316410">result</span> <span m="316820">will</span>
  <span m="317230">be</span> <span m="317640">stored</span> <span m="318050">in</span>
  <span m="318460">Y_MEM</span> <span m="318870">register</span> <span m="319280">at</span>
  <span m="319690">the</span> <span m="320100">end</span> <span m="320510">of</span>
  <span m="320920">the</span> <span m="321330">cycle.</span></p><p><span m="321740">In</span>
  <span m="322300">cycle</span> <span m="322860">4,</span> <span m="323420">we're</span>
  <span m="323980">overlapping</span> <span m="324540">execution</span> <span m="325100">of</span>
  <span m="325660">four</span> <span m="326220">instructions.</span></p><p><span m="326780">The</span>
  <span m="327169">MEM</span> <span m="327558">stage</span> <span m="327947">initiates</span>
  <span m="328336">a</span> <span m="328725">memory</span> <span m="329114">read</span>
  <span m="329503">for</span> <span m="329892">the</span> <span m="330281">green</span>
  <span m="330670">LD</span> <span m="331059">instruction.</span></p><p><span m="331449">Note</span>
  <span m="331736">that</span> <span m="332023">the</span> <span m="332310">read</span>
  <span m="332597">data</span> <span m="332884">will</span> <span m="333171">first</span>
  <span m="333458">become</span> <span m="333745">available</span> <span m="334033">in</span>
  <span m="334320">the</span> <span m="334607">WB</span> <span m="334894">stage</span>
  <span m="335181">-</span> <span m="335468">it's</span> <span m="335755">not</span>
  <span m="336042">available</span> <span m="336330">to</span> <span m="336898">CPU</span>
  <span m="337467">in</span> <span m="338035">the</span> <span m="338604">current</span>
  <span m="339172">clock</span> <span m="339741">cycle.</span></p><p><span m="340310">In</span>
  <span m="340598">cycle</span> <span m="340886">5,</span> <span m="341174">the</span>
  <span m="341462">results</span> <span m="341751">of</span> <span m="342039">the</span>
  <span m="342327">main</span> <span m="342615">memory</span> <span m="342904">read</span>
  <span m="343192">initiated</span> <span m="343480">in</span> <span m="343768">cycle</span>
  <span m="344057">4</span> <span m="344345">are</span> <span m="344633">available</span>
  <span m="344921">for</span> <span m="345210">writing</span> <span m="345651">to</span>
  <span m="346092">the</span> <span m="346533">register</span> <span m="346974">file</span>
  <span m="347415">in</span> <span m="347856">the</span> <span m="348297">WB</span>
  <span m="348738">stage.</span></p><p><span m="349180">So</span> <span m="349490">execution</span>
  <span m="349801">of</span> <span m="350111">the</span> <span m="350422">green</span>
  <span m="350733">LD</span> <span m="351043">instruction</span> <span m="351354">will</span>
  <span m="351665">be</span> <span m="351975">complete</span> <span m="352286">when</span>
  <span m="352596">the</span> <span m="352907">memory</span> <span m="353218">data</span>
  <span m="353528">is</span> <span m="353839">written</span> <span m="354150">to</span>
  <span m="354501">R2</span> <span m="354852">at</span> <span m="355203">the</span>
  <span m="355555">end</span> <span m="355906">of</span> <span m="356257">cycle</span>
  <span m="356608">5.</span></p><p><span m="356960">Meanwhile,</span> <span m="357360">the</span>
  <span m="357761">MEM</span> <span m="358161">stage</span> <span m="358562">is</span>
  <span m="358963">initiating</span> <span m="359363">a</span> <span m="359764">memory</span>
  <span m="360165">read</span> <span m="360565">for</span> <span m="360966">the</span>
  <span m="361367">blue</span> <span m="361767">LD</span> <span m="362168">instruction.</span></p><p><span
  m="362569">The</span> <span m="363048">pipeline</span> <span m="363527">continues</span>
  <span m="364006">to</span> <span m="364485">complete</span> <span m="364964">successive</span>
  <span m="365444">instructions</span> <span m="365923">in</span> <span m="366402">successive</span>
  <span m="366881">clock</span> <span m="367360">cycles.</span></p><p><span m="367840">The</span>
  <span m="368211">latency</span> <span m="368582">for</span> <span m="368953">a</span>
  <span m="369324">particular</span> <span m="369695">instruction</span> <span m="370066">is</span>
  <span m="370437">5</span> <span m="370808">clock</span> <span m="371179">cycles.</span></p><p><span
  m="371550">The</span> <span m="372052">throughput</span> <span m="372554">of</span>
  <span m="373056">the</span> <span m="373558">pipelined</span> <span m="374061">CPU</span>
  <span m="374563">is</span> <span m="375065">1</span> <span m="375567">instruction/cycle.</span></p><p><span
  m="376070">This</span> <span m="376415">is</span> <span m="376761">the</span> <span
  m="377106">same</span> <span m="377452">as</span> <span m="377798">the</span> <span
  m="378143">unpipelined</span> <span m="378489">implementation,</span> <span m="378835">except</span>
  <span m="379180">that</span> <span m="379526">the</span> <span m="379871">clock</span>
  <span m="380217">period</span> <span m="380563">is</span> <span m="380908">shorter</span>
  <span m="381254">because</span> <span m="381600">each</span> <span m="382285">pipeline</span>
  <span m="382970">stage</span> <span m="383655">has</span> <span m="384340">fewer</span>
  <span m="385025">components.</span></p><p><span m="385710">Note</span> <span m="386033">that</span>
  <span m="386357">the</span> <span m="386680">effects</span> <span m="387004">of</span>
  <span m="387327">the</span> <span m="387651">green</span> <span m="387974">LD,</span>
  <span m="388298">i.e.,</span> <span m="388621">filling</span> <span m="388945">R2</span>
  <span m="389268">with</span> <span m="389592">a</span> <span m="389915">new</span>
  <span m="390239">value,</span> <span m="390562">don't</span> <span m="390886">happen</span>
  <span m="391210">until</span> <span m="391523">the</span> <span m="391836">rising</span>
  <span m="392149">edge</span> <span m="392462">of</span> <span m="392775">the</span>
  <span m="393088">clock</span> <span m="393401">at</span> <span m="393714">the</span>
  <span m="394027">end</span> <span m="394340">of</span> <span m="394653">cycle</span>
  <span m="394966">5.</span></p><p><span m="395280">In</span> <span m="395616">other</span>
  <span m="395953">words,</span> <span m="396290">the</span> <span m="396626">results</span>
  <span m="396963">of</span> <span m="397300">the</span> <span m="397636">green</span>
  <span m="397973">LD</span> <span m="398310">aren't</span> <span m="398646">available</span>
  <span m="398983">to</span> <span m="399320">other</span> <span m="399656">instructions</span>
  <span m="399993">until</span> <span m="400330">cycle</span> <span m="401455">6.</span></p><p><span
  m="402580">If</span> <span m="402888">there</span> <span m="403197">were</span>
  <span m="403506">instructions</span> <span m="403815">in</span> <span m="404123">the</span>
  <span m="404432">pipeline</span> <span m="404741">that</span> <span m="405050">read</span>
  <span m="405358">R2</span> <span m="405667">before</span> <span m="405976">cycle</span>
  <span m="406285">6,</span> <span m="406593">they</span> <span m="406902">would</span>
  <span m="407211">have</span> <span m="407520">gotten</span> <span m="408207">an</span>
  <span m="408895">old</span> <span m="409582">value!</span></p><p><span m="410270">This</span>
  <span m="410463">is</span> <span m="410657">an</span> <span m="410851">example</span>
  <span m="411045">of</span> <span m="411238">a</span> <span m="411432">data</span>
  <span m="411626">hazard.</span></p><p><span m="411820">Not</span> <span m="412262">a</span>
  <span m="412704">problem</span> <span m="413146">for</span> <span m="413588">us,</span>
  <span m="414030">since</span> <span m="414472">our</span> <span m="414914">instruction</span>
  <span m="415356">sequence</span> <span m="415798">didn't</span> <span m="416240">trigger</span>
  <span m="416682">this</span> <span m="417124">data</span> <span m="417566">hazard.</span></p><p><span
  m="418009">Tackling</span> <span m="418376">data</span> <span m="418743">hazards</span>
  <span m="419110">is</span> <span m="419478">our</span> <span m="419845">next</span>
  <span m="420212">task.</span></p>
type: course
uid: f44d20ea52f0568d64796e02ce928e78

---
None