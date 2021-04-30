---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: swdDzsfFflo
  parent_uid: fad136acb2d65f1c4c76730fb25ff313
  title: Video-YouTube-Stream
  type: Video
  uid: 61ef9a1f1169f5318a37aeb80a900acf
- id: 3Play-3Play YouTube id-Stream
  media_location: swdDzsfFflo
  parent_uid: fad136acb2d65f1c4c76730fb25ff313
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 5b2de0da793b71d6ae44024a592d1e95
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/swdDzsfFflo/default.jpg
  parent_uid: fad136acb2d65f1c4c76730fb25ff313
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 285244960748b15f0fb1f23ecd14e8fe
- id: swdDzsfFflo.srt
  parent_uid: fad136acb2d65f1c4c76730fb25ff313
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v7/virtual-memory/swdDzsfFflo.srt
  title: 3play caption file
  type: null
  uid: 7323ac9b085683237f4c557d955712af
- id: swdDzsfFflo.pdf
  parent_uid: fad136acb2d65f1c4c76730fb25ff313
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v7/virtual-memory/swdDzsfFflo.pdf
  title: 3play pdf file
  type: null
  uid: 91673ede8363fe7c9e399bc3fdb87117
- id: Caption-3Play YouTube id-SRT
  parent_uid: fad136acb2d65f1c4c76730fb25ff313
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: e7d3027f681ec184ebd463ff9efb5d69
- id: Transcript-3Play YouTube id-PDF
  parent_uid: fad136acb2d65f1c4c76730fb25ff313
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 98119c0ae62fe4eba6caa72fae79277c
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_16-02-07-01_300k.mp4
  parent_uid: fad136acb2d65f1c4c76730fb25ff313
  title: Video-Internet Archive-MP4
  type: Video
  uid: f7d28896f56db1f962f59d58d11c3bc6
inline_embed_id: 92615746virtualmemory55888215
layout: video
order_index: null
parent_uid: d232a38da0796a68e79365ca68027d49
related_resources_text: ''
short_url: virtual-memory
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v7/virtual-memory
template_type: Embed
title: 'Worked Example: Virtual Memory'
transcript: <p><span m="570">Virtual</span> <span m="899">memory</span> <span m="1228">allows</span>
  <span m="1558">programs</span> <span m="1887">to</span> <span m="2216">behave</span>
  <span m="2546">as</span> <span m="2875">if</span> <span m="3205">they</span> <span
  m="3534">have</span> <span m="3863">a</span> <span m="4193">larger</span> <span
  m="4522">memory</span> <span m="4851">than</span> <span m="5181">they</span> <span
  m="5510">actually</span> <span m="5840">do.</span></p><p><span m="6900">The</span>
  <span m="7297">way</span> <span m="7694">this</span> <span m="8091">works</span>
  <span m="8488">is</span> <span m="8885">by</span> <span m="9283">using</span> <span
  m="9680">virtual</span> <span m="10077">addresses,</span> <span m="10474">which</span>
  <span m="10871">refer</span> <span m="11268">to</span> <span m="11666">addresses</span>
  <span m="12063">on</span> <span m="12460">disk,</span> <span m="12857">in</span>
  <span m="13254">our</span> <span m="13651">programs.</span></p><p><span m="14049">The</span>
  <span m="14422">virtual</span> <span m="14796">addresses</span> <span m="15170">are</span>
  <span m="15544">translated</span> <span m="15918">into</span> <span m="16292">physical</span>
  <span m="16666">addresses</span> <span m="17040">using</span> <span m="17414">the</span>
  <span m="17788">page</span> <span m="18162">map</span> <span m="18536">which</span>
  <span m="18910">is</span> <span m="19335">a</span> <span m="19760">lookup</span>
  <span m="20186">table</span> <span m="20611">that</span> <span m="21036">has</span>
  <span m="21462">one</span> <span m="21887">entry</span> <span m="22312">per</span>
  <span m="22738">virtual</span> <span m="23163">page.</span></p><p><span m="23589">The</span>
  <span m="23913">page</span> <span m="24237">map</span> <span m="24561">knows</span>
  <span m="24885">whether</span> <span m="25209">the</span> <span m="25533">virtual</span>
  <span m="25857">page</span> <span m="26181">is</span> <span m="26506">in</span>
  <span m="26830">physical</span> <span m="27154">memory</span> <span m="27478">and</span>
  <span m="27802">if</span> <span m="28126">so</span> <span m="28450">it</span> <span
  m="28774">immediately</span> <span m="29099">returns</span> <span m="29667">the</span>
  <span m="30235">physical</span> <span m="30803">page</span> <span m="31371">number.</span></p><p><span
  m="31939">If</span> <span m="32216">the</span> <span m="32494">page</span> <span
  m="32772">is</span> <span m="33050">not</span> <span m="33328">in</span> <span m="33606">physical</span>
  <span m="33883">memory,</span> <span m="34161">then</span> <span m="34439">this</span>
  <span m="34717">causes</span> <span m="34995">a</span> <span m="35273">fault</span>
  <span m="35550">which</span> <span m="35828">means</span> <span m="36106">that</span>
  <span m="36384">the</span> <span m="36662">virtual</span> <span m="36940">page</span>
  <span m="37302">must</span> <span m="37664">be</span> <span m="38026">brought</span>
  <span m="38388">in</span> <span m="38750">from</span> <span m="39112">disk</span>
  <span m="39474">to</span> <span m="39836">physical</span> <span m="40198">memory</span>
  <span m="40560">before</span> <span m="40922">it</span> <span m="41284">can</span>
  <span m="41646">be</span> <span m="42008">accessed.</span></p><p><span m="42370">To</span>
  <span m="42730">do</span> <span m="43091">this</span> <span m="43451">the</span>
  <span m="43812">least</span> <span m="44172">recently</span> <span m="44533">used</span>
  <span m="44894">(LRU)</span> <span m="45254">page</span> <span m="45615">in</span>
  <span m="45975">the</span> <span m="46336">physical</span> <span m="46697">memory</span>
  <span m="47057">is</span> <span m="47418">removed</span> <span m="47778">to</span>
  <span m="48139">make</span> <span m="48500">room</span> <span m="48953">for</span>
  <span m="49406">the</span> <span m="49859">address</span> <span m="50312">that</span>
  <span m="50766">is</span> <span m="51219">currently</span> <span m="51672">being</span>
  <span m="52125">requested.</span></p><p><span m="52579">The</span> <span m="52947">page</span>
  <span m="53316">map</span> <span m="53685">is</span> <span m="54053">also</span>
  <span m="54422">updated</span> <span m="54791">with</span> <span m="55160">the</span>
  <span m="55528">new</span> <span m="55897">mapping</span> <span m="56266">of</span>
  <span m="56635">virtual</span> <span m="57003">to</span> <span m="57372">physical</span>
  <span m="57741">pages.</span></p><p><span m="58110">Since</span> <span m="58441">bringing</span>
  <span m="58773">data</span> <span m="59105">to</span> <span m="59437">and</span>
  <span m="59769">from</span> <span m="60101">disk</span> <span m="60433">is</span>
  <span m="60765">an</span> <span m="61096">expensive</span> <span m="61428">operation,</span>
  <span m="61760">data</span> <span m="62092">is</span> <span m="62424">moved</span>
  <span m="62756">in</span> <span m="63088">chunks.</span></p><p><span m="63420">This</span>
  <span m="63760">makes</span> <span m="64101">sense</span> <span m="64441">because</span>
  <span m="64782">of</span> <span m="65122">the</span> <span m="65463">concept</span>
  <span m="65804">of</span> <span m="66144">locality</span> <span m="66485">which</span>
  <span m="66825">we</span> <span m="67166">studied</span> <span m="67507">as</span>
  <span m="67847">part</span> <span m="68188">of</span> <span m="68528">our</span>
  <span m="68869">Caches</span> <span m="69210">unit.</span></p><p><span m="70210">The</span>
  <span m="70532">idea</span> <span m="70855">is</span> <span m="71177">that</span>
  <span m="71500">instructions,</span> <span m="71822">or</span> <span m="72145">data,</span>
  <span m="72467">that</span> <span m="72790">are</span> <span m="73112">close</span>
  <span m="73435">to</span> <span m="73757">the</span> <span m="74080">current</span>
  <span m="74402">address</span> <span m="74725">are</span> <span m="75047">likely</span>
  <span m="75370">to</span> <span m="75703">be</span> <span m="76036">accessed</span>
  <span m="76369">as</span> <span m="76702">well,</span> <span m="77035">so</span>
  <span m="77368">it</span> <span m="77701">makes</span> <span m="78034">sense</span>
  <span m="78367">to</span> <span m="78700">fetch</span> <span m="79033">more</span>
  <span m="79366">than</span> <span m="79699">one</span> <span m="80032">word</span>
  <span m="80365">of</span> <span m="80698">data</span> <span m="81031">at</span>
  <span m="81364">a</span> <span m="81697">time.</span></p><p><span m="82030">This</span>
  <span m="82301">is</span> <span m="82573">especially</span> <span m="82845">true</span>
  <span m="83117">if</span> <span m="83389">the</span> <span m="83661">cost</span>
  <span m="83933">of</span> <span m="84205">fetching</span> <span m="84476">the</span>
  <span m="84748">first</span> <span m="85020">word</span> <span m="85292">is</span>
  <span m="85564">significantly</span> <span m="85836">higher</span> <span m="86108">than</span>
  <span m="86380">the</span> <span m="86828">cost</span> <span m="87277">of</span>
  <span m="87726">fetching</span> <span m="88174">adjacent</span> <span m="88623">memory</span>
  <span m="89072">locations</span> <span m="89520">as</span> <span m="89969">is</span>
  <span m="90418">the</span> <span m="90866">case</span> <span m="91315">with</span>
  <span m="91764">accesses</span> <span m="92212">to</span> <span m="92661">disk.</span></p><p><span
  m="93110">So</span> <span m="93481">data</span> <span m="93853">is</span> <span
  m="94225">moved</span> <span m="94597">back</span> <span m="94969">and</span> <span
  m="95340">forth</span> <span m="95712">from</span> <span m="96084">disk</span> <span
  m="96456">in</span> <span m="96828">pages.</span></p><p><span m="97200">The</span>
  <span m="97539">size</span> <span m="97878">of</span> <span m="98217">a</span> <span
  m="98557">page</span> <span m="98896">is</span> <span m="99235">the</span> <span
  m="99575">same</span> <span m="99914">in</span> <span m="100253">both</span> <span
  m="100592">virtual</span> <span m="100932">and</span> <span m="101271">physical</span>
  <span m="101610">memory.</span></p><p><span m="101950">Lets</span> <span m="102329">look</span>
  <span m="102708">at</span> <span m="103087">an</span> <span m="103466">example</span>
  <span m="103845">of</span> <span m="104224">how</span> <span m="104603">virtual</span>
  <span m="104982">memory</span> <span m="105361">is</span> <span m="105740">used.</span></p><p><span
  m="106119">While</span> <span m="106415">it</span> <span m="106711">is</span> <span
  m="107007">usually</span> <span m="107304">the</span> <span m="107600">case</span>
  <span m="107896">that</span> <span m="108193">the</span> <span m="108489">virtual</span>
  <span m="108785">address</span> <span m="109082">space</span> <span m="109378">is</span>
  <span m="109674">larger</span> <span m="109971">than</span> <span m="110267">the</span>
  <span m="110563">physical</span> <span m="110860">address</span> <span m="111166">space,</span>
  <span m="111473">this</span> <span m="111780">is</span> <span m="112086">not</span>
  <span m="112393">a</span> <span m="112700">requirement</span> <span m="113006">and</span>
  <span m="113313">in</span> <span m="113620">this</span> <span m="113926">problem</span>
  <span m="114233">the</span> <span m="114540">virtual</span> <span m="114846">address</span>
  <span m="115153">space</span> <span m="115460">happens</span> <span m="115933">to</span>
  <span m="116406">be</span> <span m="116880">smaller</span> <span m="117353">than</span>
  <span m="117826">the</span> <span m="118300">physical</span> <span m="118773">address</span>
  <span m="119246">space.</span></p><p><span m="119720">Specifically,</span> <span
  m="120301">virtual</span> <span m="120883">addresses</span> <span m="121464">are</span>
  <span m="122046">16</span> <span m="122627">bits</span> <span m="123209">long</span>
  <span m="123790">so</span> <span m="124372">they</span> <span m="124953">can</span>
  <span m="125535">address</span> <span m="126116">2^16</span> <span m="126698">bytes.</span></p><p><span
  m="127280">Physical</span> <span m="127581">addresses</span> <span m="127883">are</span>
  <span m="128185">20</span> <span m="128487">bits</span> <span m="128789">long</span>
  <span m="129091">so</span> <span m="129393">that</span> <span m="129695">means</span>
  <span m="129996">that</span> <span m="130298">our</span> <span m="130600">physical</span>
  <span m="130902">memory</span> <span m="131204">is</span> <span m="131506">of</span>
  <span m="131808">size</span> <span m="132110">2^20</span> <span m="133510">bytes.</span></p><p><span
  m="134910">Our</span> <span m="135444">page</span> <span m="135979">size</span>
  <span m="136513">is</span> <span m="137048">2^8</span> <span m="137582">bytes</span>
  <span m="138117">or</span> <span m="138651">256</span> <span m="139186">bytes</span>
  <span m="139720">per</span> <span m="140255">page.</span></p><p><span m="140790">This</span>
  <span m="141139">means</span> <span m="141488">that</span> <span m="141838">the</span>
  <span m="142187">16</span> <span m="142537">bit</span> <span m="142886">virtual</span>
  <span m="143235">address</span> <span m="143585">consists</span> <span m="143934">of</span>
  <span m="144284">8</span> <span m="144633">bits</span> <span m="144982">of</span>
  <span m="145332">page</span> <span m="145681">offset</span> <span m="146031">and</span>
  <span m="146380">another</span> <span m="146730">8</span> <span m="147017">bits</span>
  <span m="147305">for</span> <span m="147593">the</span> <span m="147881">virtual</span>
  <span m="148168">page</span> <span m="148456">number</span> <span m="148744">(or</span>
  <span m="149032">VPN).</span></p><p><span m="149320">The</span> <span m="149755">20</span>
  <span m="150191">bit</span> <span m="150627">physical</span> <span m="151063">address</span>
  <span m="151499">consists</span> <span m="151935">of</span> <span m="152371">the</span>
  <span m="152807">same</span> <span m="153242">8</span> <span m="153678">bit</span>
  <span m="154114">page</span> <span m="154550">offset</span> <span m="154986">and</span>
  <span m="155422">another</span> <span m="155858">12</span> <span m="156294">bits</span>
  <span m="156730">for</span> <span m="157054">the</span> <span m="157378">physical</span>
  <span m="157702">page</span> <span m="158027">number</span> <span m="158351">(or</span>
  <span m="158675">PPN).</span></p><p><span m="159000">The</span> <span m="159392">first</span>
  <span m="159784">question</span> <span m="160176">we</span> <span m="160568">want</span>
  <span m="160960">to</span> <span m="161352">consider</span> <span m="161744">is</span>
  <span m="162136">what</span> <span m="162528">is</span> <span m="162921">the</span>
  <span m="163313">size</span> <span m="163705">of</span> <span m="164097">the</span>
  <span m="164489">page</span> <span m="164881">map</span> <span m="165273">in</span>
  <span m="165665">this</span> <span m="166057">example?</span></p><p><span m="166450">Recall</span>
  <span m="166742">that</span> <span m="167034">a</span> <span m="167326">page</span>
  <span m="167618">map</span> <span m="167910">has</span> <span m="168202">1</span>
  <span m="168494">entry</span> <span m="168786">per</span> <span m="169078">virtual</span>
  <span m="169371">page</span> <span m="169663">in</span> <span m="169955">order</span>
  <span m="170247">to</span> <span m="170539">map</span> <span m="170831">each</span>
  <span m="171123">virtual</span> <span m="171415">page</span> <span m="171707">to</span>
  <span m="172000">a</span> <span m="172740">physical</span> <span m="173480">page.</span></p><p><span
  m="174220">This</span> <span m="174534">means</span> <span m="174848">that</span>
  <span m="175162">the</span> <span m="175476">number</span> <span m="175790">of</span>
  <span m="176104">entries</span> <span m="176418">in</span> <span m="176732">the</span>
  <span m="177046">page</span> <span m="177360">map</span> <span m="177674">is</span>
  <span m="177988">2^8</span> <span m="178302">where</span> <span m="178616">8</span>
  <span m="178930">is</span> <span m="179244">the</span> <span m="179558">number</span>
  <span m="179872">of</span> <span m="180186">bits</span> <span m="180500">in</span>
  <span m="181076">the</span> <span m="181653">VPN.</span></p><p><span m="182230">The</span>
  <span m="182602">size</span> <span m="182975">of</span> <span m="183348">each</span>
  <span m="183721">page</span> <span m="184094">map</span> <span m="184467">entry</span>
  <span m="184840">is</span> <span m="185212">14</span> <span m="185585">bits,</span>
  <span m="185958">12</span> <span m="186331">for</span> <span m="186704">the</span>
  <span m="187077">PPN,</span> <span m="187450">1</span> <span m="187822">for</span>
  <span m="188195">the</span> <span m="188568">dirty</span> <span m="188941">bit</span>
  <span m="189314">and</span> <span m="189687">1</span> <span m="190060">for</span>
  <span m="190530">the</span> <span m="191000">resident</span> <span m="191470">bit.</span></p><p><span
  m="191940">Suppose</span> <span m="192203">that</span> <span m="192467">you</span>
  <span m="192731">are</span> <span m="192994">told</span> <span m="193258">that</span>
  <span m="193522">the</span> <span m="193785">page</span> <span m="194049">size</span>
  <span m="194313">is</span> <span m="194576">doubled</span> <span m="194840">in</span>
  <span m="195104">size</span> <span m="195367">so</span> <span m="195631">that</span>
  <span m="195895">there</span> <span m="196158">are</span> <span m="196422">now</span>
  <span m="196686">2^9</span> <span m="196950">bytes</span> <span m="197351">per</span>
  <span m="197752">page,</span> <span m="198154">but</span> <span m="198555">the</span>
  <span m="198956">size</span> <span m="199358">of</span> <span m="199759">your</span>
  <span m="200160">physical</span> <span m="200562">and</span> <span m="200963">virtual</span>
  <span m="201364">addresses</span> <span m="201766">remain</span> <span m="202167">the</span>
  <span m="202568">same.</span></p><p><span m="202970">We</span> <span m="203192">would</span>
  <span m="203414">like</span> <span m="203637">to</span> <span m="203859">determine</span>
  <span m="204081">what</span> <span m="204304">effect</span> <span m="204526">this</span>
  <span m="204748">change</span> <span m="204971">would</span> <span m="205193">have</span>
  <span m="205415">on</span> <span m="205638">some</span> <span m="205860">of</span>
  <span m="206082">the</span> <span m="206305">page</span> <span m="206527">map</span>
  <span m="206750">attributes.</span></p><p><span m="208450">The</span> <span m="208783">first</span>
  <span m="209117">question</span> <span m="209451">is</span> <span m="209785">how</span>
  <span m="210118">does</span> <span m="210452">the</span> <span m="210786">size</span>
  <span m="211120">of</span> <span m="211453">each</span> <span m="211787">page</span>
  <span m="212121">map</span> <span m="212455">entry</span> <span m="212788">in</span>
  <span m="213122">bits</span> <span m="213456">change?</span></p><p><span m="213790">Since</span>
  <span m="214098">the</span> <span m="214406">size</span> <span m="214715">of</span>
  <span m="215023">a</span> <span m="215331">physical</span> <span m="215640">address</span>
  <span m="215948">continues</span> <span m="216256">to</span> <span m="216565">be</span>
  <span m="216873">20</span> <span m="217181">bits</span> <span m="217490">long,</span>
  <span m="217798">then</span> <span m="218106">the</span> <span m="218415">change</span>
  <span m="218723">in</span> <span m="219031">page</span> <span m="219340">offset</span>
  <span m="219682">size</span> <span m="220024">from</span> <span m="220366">8</span>
  <span m="220708">to</span> <span m="221050">9</span> <span m="221392">bits</span>
  <span m="221734">implies</span> <span m="222076">that</span> <span m="222418">the</span>
  <span m="222761">size</span> <span m="223103">of</span> <span m="223445">the</span>
  <span m="223787">PPN</span> <span m="224129">decreased</span> <span m="224471">by</span>
  <span m="224813">1</span> <span m="225155">bit</span> <span m="225497">from</span>
  <span m="225840">12</span> <span m="226573">to</span> <span m="227306">11.</span></p><p><span
  m="228040">This</span> <span m="228421">implies</span> <span m="228802">that</span>
  <span m="229184">the</span> <span m="229565">size</span> <span m="229946">of</span>
  <span m="230328">each</span> <span m="230709">page</span> <span m="231090">map</span>
  <span m="231472">entry</span> <span m="231853">also</span> <span m="232234">decreases</span>
  <span m="232616">by</span> <span m="232997">1</span> <span m="233378">bit.</span></p><p><span
  m="233760">How</span> <span m="234098">are</span> <span m="234437">the</span> <span
  m="234776">number</span> <span m="235115">of</span> <span m="235454">entries</span>
  <span m="235792">in</span> <span m="236131">the</span> <span m="236470">page</span>
  <span m="236809">map</span> <span m="237148">affected</span> <span m="237487">by</span>
  <span m="237825">the</span> <span m="238164">change</span> <span m="238503">in</span>
  <span m="238842">page</span> <span m="239181">size?</span></p><p><span m="239520">Since</span>
  <span m="239793">the</span> <span m="240067">number</span> <span m="240341">of</span>
  <span m="240615">entries</span> <span m="240889">in</span> <span m="241163">a</span>
  <span m="241437">page</span> <span m="241711">map</span> <span m="241985">is</span>
  <span m="242258">equal</span> <span m="242532">to</span> <span m="242806">the</span>
  <span m="243080">number</span> <span m="243354">of</span> <span m="243628">virtual</span>
  <span m="243902">pages,</span> <span m="244176">that</span> <span m="244450">means</span>
  <span m="244771">that</span> <span m="245093">if</span> <span m="245415">the</span>
  <span m="245737">size</span> <span m="246058">of</span> <span m="246380">each</span>
  <span m="246702">page</span> <span m="247024">doubled,</span> <span m="247345">then</span>
  <span m="247667">we</span> <span m="247989">have</span> <span m="248311">half</span>
  <span m="248632">as</span> <span m="248954">many</span> <span m="249276">virtual</span>
  <span m="249598">pages.</span></p><p><span m="249920">This</span> <span m="250258">is</span>
  <span m="250596">shown</span> <span m="250934">in</span> <span m="251272">the</span>
  <span m="251611">size</span> <span m="251949">of</span> <span m="252287">the</span>
  <span m="252625">VPN</span> <span m="252964">which</span> <span m="253302">has</span>
  <span m="253640">decreased</span> <span m="253978">from</span> <span m="254317">8</span>
  <span m="254655">to</span> <span m="254993">7</span> <span m="255331">bits.</span></p><p><span
  m="255670">This</span> <span m="255989">also</span> <span m="256308">means</span>
  <span m="256628">that</span> <span m="256947">the</span> <span m="257267">number</span>
  <span m="257586">of</span> <span m="257906">entries</span> <span m="258225">in</span>
  <span m="258545">the</span> <span m="258864">page</span> <span m="259183">map</span>
  <span m="259503">have</span> <span m="259822">halved</span> <span m="260142">in</span>
  <span m="260461">size</span> <span m="260781">from</span> <span m="261100">2^8</span>
  <span m="261420">entries</span> <span m="262132">down</span> <span m="262844">to</span>
  <span m="263556">2^7</span> <span m="264268">entries.</span></p><p><span m="264980">How</span>
  <span m="265291">about</span> <span m="265603">the</span> <span m="265915">number</span>
  <span m="266227">of</span> <span m="266538">accesses</span> <span m="266850">of</span>
  <span m="267162">the</span> <span m="267474">page</span> <span m="267785">map</span>
  <span m="268097">that</span> <span m="268409">are</span> <span m="268721">required</span>
  <span m="269032">to</span> <span m="269344">translate</span> <span m="269656">a</span>
  <span m="269968">single</span> <span m="270280">virtual</span> <span m="271344">address?</span></p><p><span
  m="272409">This</span> <span m="272804">parameter</span> <span m="273200">does</span>
  <span m="273596">not</span> <span m="273992">change</span> <span m="274387">as</span>
  <span m="274783">a</span> <span m="275179">result</span> <span m="275575">of</span>
  <span m="275971">the</span> <span m="276366">pages</span> <span m="276762">doubling</span>
  <span m="277158">in</span> <span m="277554">size.</span></p><p><span m="277950">Suppose</span>
  <span m="278374">we</span> <span m="278799">return</span> <span m="279223">to</span>
  <span m="279648">our</span> <span m="280073">original</span> <span m="280497">page</span>
  <span m="280922">size</span> <span m="281346">of</span> <span m="281771">256</span>
  <span m="282196">bytes</span> <span m="282620">per</span> <span m="283045">page.</span></p><p><span
  m="283470">We</span> <span m="283847">now</span> <span m="284224">execute</span>
  <span m="284602">these</span> <span m="284979">two</span> <span m="285356">lines</span>
  <span m="285734">of</span> <span m="286111">code,</span> <span m="286488">a</span>
  <span m="286866">load</span> <span m="287243">followed</span> <span m="287620">by</span>
  <span m="287998">a</span> <span m="288375">store</span> <span m="288752">operation.</span></p><p><span
  m="289130">The</span> <span m="289422">comment</span> <span m="289714">after</span>
  <span m="290007">each</span> <span m="290299">instruction</span> <span m="290591">shows</span>
  <span m="290884">us</span> <span m="291176">the</span> <span m="291468">value</span>
  <span m="291761">of</span> <span m="292053">the</span> <span m="292345">PC</span>
  <span m="292638">when</span> <span m="292930">each</span> <span m="293222">of</span>
  <span m="293515">the</span> <span m="293807">instructions</span> <span m="294100">is</span>
  <span m="294505">executed,</span> <span m="294911">so</span> <span m="295317">it</span>
  <span m="295723">is</span> <span m="296129">telling</span> <span m="296535">us</span>
  <span m="296941">that</span> <span m="297347">the</span> <span m="297752">load</span>
  <span m="298158">instruction</span> <span m="298564">is</span> <span m="298970">at</span>
  <span m="299376">address</span> <span m="299782">0x1FC</span> <span m="300188">and</span>
  <span m="300594">the</span> <span m="301000">store</span> <span m="301563">instruction</span>
  <span m="302126">is</span> <span m="302690">at</span> <span m="303253">address</span>
  <span m="303816">0x200.</span></p><p><span m="304380">To</span> <span m="304756">execute</span>
  <span m="305133">these</span> <span m="305510">two</span> <span m="305887">lines</span>
  <span m="306264">of</span> <span m="306641">code,</span> <span m="307018">we</span>
  <span m="307395">must</span> <span m="307771">first</span> <span m="308148">fetch</span>
  <span m="308525">each</span> <span m="308902">instruction</span> <span m="309279">and</span>
  <span m="309656">then</span> <span m="310033">perform</span> <span m="310410">the</span>
  <span m="310932">data</span> <span m="311455">access</span> <span m="311978">required</span>
  <span m="312501">by</span> <span m="313024">that</span> <span m="313547">instruction.</span></p><p><span
  m="314070">Since</span> <span m="314375">our</span> <span m="314680">pages</span>
  <span m="314985">are</span> <span m="315290">2^8</span> <span m="315595">bytes</span>
  <span m="315900">long,</span> <span m="316205">that</span> <span m="316510">means</span>
  <span m="316815">that</span> <span m="317120">the</span> <span m="317425">bottom</span>
  <span m="317730">8</span> <span m="318035">bits</span> <span m="318340">of</span>
  <span m="318645">our</span> <span m="318950">address</span> <span m="319255">correspond</span>
  <span m="319560">to</span> <span m="320100">the</span> <span m="320640">page</span>
  <span m="321180">offset.</span></p><p><span m="321720">Notice</span> <span m="322030">that</span>
  <span m="322341">our</span> <span m="322652">instruction</span> <span m="322962">addresses</span>
  <span m="323273">are</span> <span m="323584">specified</span> <span m="323894">in</span>
  <span m="324205">hex</span> <span m="324516">so</span> <span m="324826">8</span>
  <span m="325137">bits</span> <span m="325448">correspond</span> <span m="325758">to</span>
  <span m="326069">the</span> <span m="326380">bottom</span> <span m="327115">2</span>
  <span m="327850">hex</span> <span m="328585">characters.</span></p><p><span m="329320">This</span>
  <span m="329678">means</span> <span m="330037">that</span> <span m="330396">when</span>
  <span m="330755">accessing</span> <span m="331114">the</span> <span m="331473">LD</span>
  <span m="331832">instruction,</span> <span m="332191">the</span> <span m="332550">VPN</span>
  <span m="332908">=</span> <span m="333267">1</span> <span m="333626">(which</span>
  <span m="333985">is</span> <span m="334344">what</span> <span m="334703">remains</span>
  <span m="335062">of</span> <span m="335421">our</span> <span m="335780">virtual</span>
  <span m="336365">address</span> <span m="336950">after</span> <span m="337535">removing</span>
  <span m="338120">the</span> <span m="338705">bottom</span> <span m="339290">8</span>
  <span m="339875">bits.)</span> <span m="340460">The</span> <span m="340946">data</span>
  <span m="341432">accessed</span> <span m="341919">by</span> <span m="342405">the</span>
  <span m="342891">LD</span> <span m="343378">instruction</span> <span m="343864">comes</span>
  <span m="344350">from</span> <span m="344837">VPN</span> <span m="345323">3.</span></p><p><span
  m="345810">Next</span> <span m="346182">we</span> <span m="346555">fetch</span>
  <span m="346928">the</span> <span m="347301">store</span> <span m="347674">instruction</span>
  <span m="348047">from</span> <span m="348420">VPN</span> <span m="348793">2,</span>
  <span m="349166">and</span> <span m="349539">finally</span> <span m="349912">we</span>
  <span m="350285">store</span> <span m="350658">an</span> <span m="351031">updated</span>
  <span m="351404">value</span> <span m="351777">to</span> <span m="352150">VPN</span>
  <span m="353350">6.</span></p><p><span m="354550">Given</span> <span m="354908">the</span>
  <span m="355267">page</span> <span m="355626">map</span> <span m="355984">shown</span>
  <span m="356343">here,</span> <span m="356702">we</span> <span m="357060">would</span>
  <span m="357419">like</span> <span m="357778">to</span> <span m="358136">determine</span>
  <span m="358495">the</span> <span m="358854">unique</span> <span m="359212">physical</span>
  <span m="359571">addresses</span> <span m="359930">that</span> <span m="360395">are</span>
  <span m="360861">accessed</span> <span m="361327">by</span> <span m="361792">this</span>
  <span m="362258">code</span> <span m="362724">segment.</span></p><p><span m="363190">Recall</span>
  <span m="363636">that</span> <span m="364082">the</span> <span m="364529">four</span>
  <span m="364975">virtual</span> <span m="365421">addresses</span> <span m="365868">that</span>
  <span m="366314">will</span> <span m="366760">be</span> <span m="367207">accessed</span>
  <span m="367653">are:</span> <span m="368100">0x1FC</span> <span m="368825">which</span>
  <span m="369551">is</span> <span m="370277">in</span> <span m="371003">VPN</span>
  <span m="371729">1</span> <span m="372455">0x34C</span> <span m="373180">which</span>
  <span m="373906">is</span> <span m="374632">in</span> <span m="375358">VPN</span>
  <span m="376084">3</span> <span m="376810">0x200</span> <span m="377490">which</span>
  <span m="378171">is</span> <span m="378852">in</span> <span m="379533">VPN</span>
  <span m="380213">2</span> <span m="380894">and</span> <span m="381575">0x604</span>
  <span m="382256">which</span> <span m="382936">is</span> <span m="383617">in</span>
  <span m="384298">VPN</span> <span m="384979">6.</span></p><p><span m="385660">Assume</span>
  <span m="386004">that</span> <span m="386348">all</span> <span m="386693">the</span>
  <span m="387037">code</span> <span m="387381">and</span> <span m="387726">data</span>
  <span m="388070">required</span> <span m="388415">to</span> <span m="388759">handle</span>
  <span m="389103">page</span> <span m="389448">faults</span> <span m="389792">is</span>
  <span m="390136">located</span> <span m="390481">at</span> <span m="390825">physical</span>
  <span m="391170">page</span> <span m="391554">0,</span> <span m="391938">your</span>
  <span m="392322">goal</span> <span m="392706">is</span> <span m="393090">to</span>
  <span m="393474">determine</span> <span m="393858">the</span> <span m="394242">5</span>
  <span m="394627">different</span> <span m="395011">physical</span> <span m="395395">pages</span>
  <span m="395779">that</span> <span m="396163">will</span> <span m="396547">get</span>
  <span m="396931">accessed</span> <span m="397315">and</span> <span m="397700">the</span>
  <span m="398041">order</span> <span m="398383">in</span> <span m="398725">which</span>
  <span m="399066">they</span> <span m="399408">will</span> <span m="399750">get</span>
  <span m="400091">accessed</span> <span m="400433">by</span> <span m="400775">this</span>
  <span m="401116">code</span> <span m="401458">segment.</span></p><p><span m="401800">We</span>
  <span m="402185">begin</span> <span m="402570">by</span> <span m="402956">looking</span>
  <span m="403341">up</span> <span m="403727">VPN</span> <span m="404112">1</span>
  <span m="404498">in</span> <span m="404883">our</span> <span m="405269">page</span>
  <span m="405654">map.</span></p><p><span m="406040">We</span> <span m="406412">see</span>
  <span m="406784">that</span> <span m="407156">its</span> <span m="407528">resident</span>
  <span m="407900">bit</span> <span m="408272">is</span> <span m="408644">set</span>
  <span m="409016">to</span> <span m="409388">1.</span></p><p><span m="409760">This</span>
  <span m="410153">means</span> <span m="410547">that</span> <span m="410941">the</span>
  <span m="411335">virtual</span> <span m="411729">page</span> <span m="412123">is</span>
  <span m="412517">in</span> <span m="412911">physical</span> <span m="413305">memory</span>
  <span m="413699">and</span> <span m="414093">its</span> <span m="414487">PPN</span>
  <span m="414881">is</span> <span m="415275">0x007.</span></p><p><span m="415669">Thus</span>
  <span m="416146">the</span> <span m="416624">first</span> <span m="417101">physical</span>
  <span m="417579">page</span> <span m="418057">that</span> <span m="418534">we</span>
  <span m="419012">access</span> <span m="419490">is</span> <span m="419967">page</span>
  <span m="420445">0x7,</span> <span m="420922">and</span> <span m="421400">the</span>
  <span m="421878">first</span> <span m="422355">physical</span> <span m="422833">address</span>
  <span m="423311">is</span> <span m="423749">determined</span> <span m="424188">by</span>
  <span m="424627">concatenating</span> <span m="425066">the</span> <span m="425505">PPN</span>
  <span m="425944">to</span> <span m="426383">the</span> <span m="426822">page</span>
  <span m="427261">offset.</span></p><p><span m="427700">This</span> <span m="428198">results</span>
  <span m="428697">in</span> <span m="429196">a</span> <span m="429695">physical</span>
  <span m="430193">address</span> <span m="430692">of</span> <span m="431191">0x7FC.</span></p><p><span
  m="431690">Next,</span> <span m="432251">we</span> <span m="432813">want</span>
  <span m="433375">to</span> <span m="433937">load</span> <span m="434499">the</span>
  <span m="435061">data</span> <span m="435623">at</span> <span m="436185">virtual</span>
  <span m="436746">address</span> <span m="437308">0x34C</span> <span m="437870">which</span>
  <span m="438432">is</span> <span m="438994">in</span> <span m="439556">VPN</span>
  <span m="440118">3.</span></p><p><span m="440680">Looking</span> <span m="441044">up</span>
  <span m="441408">VPN</span> <span m="441773">3</span> <span m="442137">in</span>
  <span m="442502">our</span> <span m="442866">page</span> <span m="443231">map,</span>
  <span m="443595">we</span> <span m="443960">find</span> <span m="444324">out</span>
  <span m="444688">that</span> <span m="445053">its</span> <span m="445417">not</span>
  <span m="445782">resident</span> <span m="446146">in</span> <span m="446511">physical</span>
  <span m="446875">memory.</span></p><p><span m="447240">This</span> <span m="447482">means</span>
  <span m="447725">that</span> <span m="447968">we</span> <span m="448211">need</span>
  <span m="448453">to</span> <span m="448696">make</span> <span m="448939">room</span>
  <span m="449182">for</span> <span m="449425">it</span> <span m="449667">by</span>
  <span m="449910">removing</span> <span m="450153">the</span> <span m="450396">least</span>
  <span m="450638">recently</span> <span m="450881">used</span> <span m="451124">page</span>
  <span m="451367">from</span> <span m="451610">physical</span> <span m="452505">memory.</span></p><p><span
  m="453400">The</span> <span m="453983">least</span> <span m="454567">recently</span>
  <span m="455151">used</span> <span m="455735">page</span> <span m="456319">is</span>
  <span m="456903">VPN</span> <span m="457486">2</span> <span m="458070">which</span>
  <span m="458654">maps</span> <span m="459238">to</span> <span m="459822">PPN</span>
  <span m="460406">0x602.</span></p><p><span m="460990">Since</span> <span m="461268">the</span>
  <span m="461547">dirty</span> <span m="461826">bit</span> <span m="462105">of</span>
  <span m="462384">our</span> <span m="462663">LRU</span> <span m="462942">page</span>
  <span m="463221">is</span> <span m="463500">0,</span> <span m="463779">that</span>
  <span m="464058">means</span> <span m="464337">that</span> <span m="464616">we</span>
  <span m="464895">have</span> <span m="465174">not</span> <span m="465453">done</span>
  <span m="465732">any</span> <span m="466011">writes</span> <span m="466290">to</span>
  <span m="466586">this</span> <span m="466882">page</span> <span m="467178">while</span>
  <span m="467474">it</span> <span m="467770">was</span> <span m="468066">in</span>
  <span m="468362">physical</span> <span m="468658">memory</span> <span m="468955">so</span>
  <span m="469251">the</span> <span m="469547">version</span> <span m="469843">in</span>
  <span m="470139">physical</span> <span m="470435">memory</span> <span m="470731">and</span>
  <span m="471027">on</span> <span m="471323">disk</span> <span m="471620">are</span>
  <span m="472465">identical.</span></p><p><span m="473310">So</span> <span m="473648">to</span>
  <span m="473986">free</span> <span m="474325">up</span> <span m="474663">physical</span>
  <span m="475002">page</span> <span m="475340">0x602,</span> <span m="475678">all</span>
  <span m="476017">we</span> <span m="476355">need</span> <span m="476694">to</span>
  <span m="477032">do</span> <span m="477371">is</span> <span m="477709">change</span>
  <span m="478047">the</span> <span m="478386">resident</span> <span m="478724">bit</span>
  <span m="479063">of</span> <span m="479401">VPN</span> <span m="479740">2</span>
  <span m="480268">to</span> <span m="480797">0</span> <span m="481325">and</span>
  <span m="481854">now</span> <span m="482382">we</span> <span m="482911">can</span>
  <span m="483439">bring</span> <span m="483968">VPN</span> <span m="484496">3</span>
  <span m="485025">into</span> <span m="485553">physical</span> <span m="486082">page</span>
  <span m="486610">0x602.</span></p><p><span m="487139">Recall</span> <span m="487434">that</span>
  <span m="487730">the</span> <span m="488026">code</span> <span m="488322">for</span>
  <span m="488618">handling</span> <span m="488914">the</span> <span m="489210">page</span>
  <span m="489506">fault</span> <span m="489801">is</span> <span m="490097">in</span>
  <span m="490393">physical</span> <span m="490689">page</span> <span m="490985">0</span>
  <span m="491281">so</span> <span m="491577">the</span> <span m="491873">second</span>
  <span m="492169">physical</span> <span m="492610">page</span> <span m="493051">that</span>
  <span m="493493">we</span> <span m="493934">access</span> <span m="494375">is</span>
  <span m="494817">page</span> <span m="495258">0.</span></p><p><span m="495700">The</span>
  <span m="496068">updated</span> <span m="496437">page</span> <span m="496806">map,</span>
  <span m="497174">after</span> <span m="497543">handling</span> <span m="497912">the</span>
  <span m="498280">page</span> <span m="498649">fault,</span> <span m="499018">looks</span>
  <span m="499386">like</span> <span m="499755">this,</span> <span m="500124">where</span>
  <span m="500492">the</span> <span m="500861">resident</span> <span m="501230">bit</span>
  <span m="501741">for</span> <span m="502252">VPN</span> <span m="502763">2</span>
  <span m="503274">has</span> <span m="503785">been</span> <span m="504296">set</span>
  <span m="504807">to</span> <span m="505318">0,</span> <span m="505830">and</span>
  <span m="506341">PPN</span> <span m="506852">0x602</span> <span m="507363">is</span>
  <span m="507874">now</span> <span m="508385">used</span> <span m="508896">for</span>
  <span m="509407">VPN</span> <span m="509918">3.</span></p><p><span m="510430">Since</span>
  <span m="510784">this</span> <span m="511139">is</span> <span m="511493">a</span>
  <span m="511848">LD</span> <span m="512202">operation,</span> <span m="512557">we</span>
  <span m="512911">are</span> <span m="513266">not</span> <span m="513620">modifying</span>
  <span m="513975">the</span> <span m="514329">page</span> <span m="514684">so</span>
  <span m="515038">the</span> <span m="515393">dirty</span> <span m="515747">bit</span>
  <span m="516102">is</span> <span m="516456">set</span> <span m="516811">to</span>
  <span m="517165">0.</span></p><p><span m="517520">The</span> <span m="518351">physical</span>
  <span m="519183">address</span> <span m="520015">for</span> <span m="520847">virtual</span>
  <span m="521679">address</span> <span m="522511">0x34C</span> <span m="523343">is</span>
  <span m="524175">now</span> <span m="525006">0x6024C</span> <span m="525838">which</span>
  <span m="526670">is</span> <span m="527502">now</span> <span m="528334">in</span>
  <span m="529166">VPN</span> <span m="529998">0x602.</span></p><p><span m="530830">Next</span>
  <span m="531151">we</span> <span m="531473">need</span> <span m="531795">to</span>
  <span m="532117">fetch</span> <span m="532439">the</span> <span m="532761">store</span>
  <span m="533083">instruction</span> <span m="533405">from</span> <span m="533726">virtual</span>
  <span m="534048">address</span> <span m="534370">0x200</span> <span m="534692">which</span>
  <span m="535014">is</span> <span m="535336">in</span> <span m="535658">VPN</span>
  <span m="535980">2.</span></p><p><span m="537620">Since</span> <span m="538023">we</span>
  <span m="538427">just</span> <span m="538830">removed</span> <span m="539234">VPN</span>
  <span m="539637">2</span> <span m="540041">from</span> <span m="540445">physical</span>
  <span m="540848">memory</span> <span m="541252">we</span> <span m="541655">get</span>
  <span m="542059">another</span> <span m="542462">page</span> <span m="542866">fault.</span></p><p><span
  m="543270">This</span> <span m="543554">time</span> <span m="543839">we</span> <span
  m="544124">will</span> <span m="544408">remove</span> <span m="544693">the</span>
  <span m="544978">next</span> <span m="545262">LRU</span> <span m="545547">page</span>
  <span m="545832">from</span> <span m="546117">physical</span> <span m="546401">memory</span>
  <span m="546686">in</span> <span m="546971">order</span> <span m="547255">to</span>
  <span m="547540">make</span> <span m="547825">room</span> <span m="548110">for</span>
  <span m="548652">VPN</span> <span m="549194">2</span> <span m="549736">once</span>
  <span m="550278">again.</span></p><p><span m="550820">In</span> <span m="551206">this</span>
  <span m="551592">case,</span> <span m="551978">the</span> <span m="552364">dirty</span>
  <span m="552750">bit</span> <span m="553136">is</span> <span m="553522">set</span>
  <span m="553908">to</span> <span m="554294">1</span> <span m="554680">which</span>
  <span m="555066">means</span> <span m="555452">that</span> <span m="555838">we</span>
  <span m="556224">have</span> <span m="556610">written</span> <span m="556996">to</span>
  <span m="557382">PPN</span> <span m="557768">0x097</span> <span m="558154">after</span>
  <span m="558541">it</span> <span m="558948">was</span> <span m="559356">fetched</span>
  <span m="559764">from</span> <span m="560172">disk.</span></p><p><span m="560580">This</span>
  <span m="560988">means</span> <span m="561397">that</span> <span m="561806">the</span>
  <span m="562215">page</span> <span m="562623">fault</span> <span m="563032">handler</span>
  <span m="563441">will</span> <span m="563850">need</span> <span m="564258">to</span>
  <span m="564667">first</span> <span m="565076">write</span> <span m="565485">physical</span>
  <span m="565893">page</span> <span m="566302">0x097</span> <span m="566711">back</span>
  <span m="567120">to</span> <span m="567732">virtual</span> <span m="568344">page</span>
  <span m="568956">5</span> <span m="569568">before</span> <span m="570180">we</span>
  <span m="570792">can</span> <span m="571405">use</span> <span m="572017">physical</span>
  <span m="572629">page</span> <span m="573241">0x097</span> <span m="573853">for</span>
  <span m="574465">VPN</span> <span m="575077">2.</span></p><p><span m="575690">After</span>
  <span m="576040">handling</span> <span m="576390">the</span> <span m="576740">page</span>
  <span m="577090">fault,</span> <span m="577440">our</span> <span m="577790">updated</span>
  <span m="578140">page</span> <span m="578490">map</span> <span m="578840">looks</span>
  <span m="579190">like</span> <span m="579540">this.</span></p><p><span m="579890">VPN</span>
  <span m="580516">5</span> <span m="581143">is</span> <span m="581770">no</span>
  <span m="582397">longer</span> <span m="583024">resident,</span> <span m="583651">and</span>
  <span m="584278">instead</span> <span m="584905">VPN</span> <span m="585531">2</span>
  <span m="586158">is</span> <span m="586785">resident</span> <span m="587412">in</span>
  <span m="588039">physical</span> <span m="588666">page</span> <span m="589293">0x097.</span></p><p><span
  m="589920">In</span> <span m="590227">addition,</span> <span m="590534">we</span>
  <span m="590842">set</span> <span m="591149">the</span> <span m="591456">dirty</span>
  <span m="591764">bit</span> <span m="592071">to</span> <span m="592378">0</span>
  <span m="592686">because</span> <span m="592993">we</span> <span m="593301">have</span>
  <span m="593608">not</span> <span m="593915">made</span> <span m="594223">any</span>
  <span m="594530">changes</span> <span m="594837">to</span> <span m="595145">this</span>
  <span m="595452">virtual</span> <span m="595760">page.</span></p><p><span m="597480">We</span>
  <span m="598124">now</span> <span m="598769">know</span> <span m="599413">that</span>
  <span m="600058">virtual</span> <span m="600703">address</span> <span m="601347">0x200</span>
  <span m="601992">maps</span> <span m="602636">to</span> <span m="603281">physical</span>
  <span m="603926">address</span> <span m="604570">0x09700</span> <span m="605215">after</span>
  <span m="605859">the</span> <span m="606504">handling</span> <span m="607149">of</span>
  <span m="607564">the</span> <span m="607979">page</span> <span m="608394">fault.</span></p><p><span
  m="608810">Finally,</span> <span m="609298">we</span> <span m="609786">need</span>
  <span m="610274">to</span> <span m="610762">perform</span> <span m="611250">the</span>
  <span m="611738">store</span> <span m="612226">to</span> <span m="612715">virtual</span>
  <span m="613203">address</span> <span m="613691">0x604</span> <span m="614179">which</span>
  <span m="614667">is</span> <span m="615155">in</span> <span m="615643">VPN</span>
  <span m="616131">6.</span></p><p><span m="616620">Since</span> <span m="617027">VPN</span>
  <span m="617434">6</span> <span m="617841">is</span> <span m="618248">resident</span>
  <span m="618655">in</span> <span m="619062">physical</span> <span m="619469">memory,</span>
  <span m="619876">we</span> <span m="620283">can</span> <span m="620690">access</span>
  <span m="621097">it</span> <span m="621504">at</span> <span m="621911">physical</span>
  <span m="622318">page</span> <span m="622725">0x790</span> <span m="623132">as</span>
  <span m="623540">shown</span> <span m="623996">in</span> <span m="624452">the</span>
  <span m="624908">page</span> <span m="625364">map.</span></p><p><span m="625820">This</span>
  <span m="626729">means</span> <span m="627638">that</span> <span m="628547">virtual</span>
  <span m="629456">address</span> <span m="630365">0x604</span> <span m="631274">maps</span>
  <span m="632183">to</span> <span m="633092">physical</span> <span m="634001">address</span>
  <span m="634910">0x79004.</span></p><p><span m="635820">Note</span> <span m="636098">that</span>
  <span m="636377">because</span> <span m="636656">the</span> <span m="636935">dirty</span>
  <span m="637214">bit</span> <span m="637493">of</span> <span m="637772">VPN</span>
  <span m="638051">6</span> <span m="638330">was</span> <span m="638609">already</span>
  <span m="638888">a</span> <span m="639167">1,</span> <span m="639446">we</span>
  <span m="639725">don't</span> <span m="640004">need</span> <span m="640283">to</span>
  <span m="640562">make</span> <span m="640841">any</span> <span m="641120">further</span>
  <span m="641399">modifications</span> <span m="641778">to</span> <span m="642157">the</span>
  <span m="642536">page</span> <span m="642916">map</span> <span m="643295">as</span>
  <span m="643674">a</span> <span m="644054">result</span> <span m="644433">of</span>
  <span m="644812">executing</span> <span m="645192">the</span> <span m="645571">store</span>
  <span m="645950">operation.</span></p><p><span m="646330">If</span> <span m="646695">the</span>
  <span m="647060">dirty</span> <span m="647425">bit</span> <span m="647790">had</span>
  <span m="648155">been</span> <span m="648520">a</span> <span m="648885">0,</span>
  <span m="649250">then</span> <span m="649615">we</span> <span m="649980">would</span>
  <span m="650345">have</span> <span m="650710">set</span> <span m="651075">it</span>
  <span m="651440">to</span> <span m="651805">1.</span></p><p><span m="652170">So</span>
  <span m="652595">the</span> <span m="653021">five</span> <span m="653447">physical</span>
  <span m="653873">pages</span> <span m="654299">that</span> <span m="654725">were</span>
  <span m="655151">accessed</span> <span m="655577">by</span> <span m="656002">this</span>
  <span m="656428">program</span> <span m="656854">are:</span> <span m="657280">page</span>
  <span m="657706">0x7,</span> <span m="658132">page</span> <span m="658558">0</span>
  <span m="658984">for</span> <span m="659410">the</span> <span m="660332">page</span>
  <span m="661255">faults,</span> <span m="662178">page</span> <span m="663101">0x602,</span>
  <span m="664024">page</span> <span m="664947">0x097,</span> <span m="665870">and</span>
  <span m="666793">page</span> <span m="667716">0x790.</span></p>
type: course
uid: fad136acb2d65f1c4c76730fb25ff313

---
None