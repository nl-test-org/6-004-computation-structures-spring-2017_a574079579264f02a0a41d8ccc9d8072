---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: -OduZBd1aHw
  parent_uid: 6563325959821a3d70422beeb53a1e4e
  title: Video-YouTube-Stream
  type: Video
  uid: b01ac483ce545d15cd0ad8dbd0e70902
- id: 3Play-3Play YouTube id-Stream
  media_location: -OduZBd1aHw
  parent_uid: 6563325959821a3d70422beeb53a1e4e
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: cd6a23da6436e349d2d80733f66af3d2
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/-OduZBd1aHw/default.jpg
  parent_uid: 6563325959821a3d70422beeb53a1e4e
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: d37a122525a00b69c63aea10cd7fa801
- id: -OduZBd1aHw.srt
  parent_uid: 6563325959821a3d70422beeb53a1e4e
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v6/mmu-improvements-7-33-/-OduZBd1aHw.srt
  title: 3play caption file
  type: null
  uid: 73362680b38d373f55bfe8911066fe27
- id: -OduZBd1aHw.pdf
  parent_uid: 6563325959821a3d70422beeb53a1e4e
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v6/mmu-improvements-7-33-/-OduZBd1aHw.pdf
  title: 3play pdf file
  type: null
  uid: a2b98149252733722f23ce56e53a6616
- id: Caption-3Play YouTube id-SRT
  parent_uid: 6563325959821a3d70422beeb53a1e4e
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: fea2073532277fc4c293e7b8641f2beb
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 6563325959821a3d70422beeb53a1e4e
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: ad99bd08c62bda20b09d89660df663f8
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_16-02-06_300k.mp4
  parent_uid: 6563325959821a3d70422beeb53a1e4e
  title: Video-Internet Archive-MP4
  type: Video
  uid: 9c21e6f335901658cd0258c1ca7abb79
inline_embed_id: 91872864mmuimprovements73313803563
layout: video
order_index: null
parent_uid: 78f1c3af5f797058ac49df9a9242da20
related_resources_text: ''
short_url: mmu-improvements-7-33-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c16/c16s2/c16s2v6/mmu-improvements-7-33-
template_type: Embed
title: MMU Improvements
transcript: <p><span m="510">There</span> <span m="975">are</span> <span m="1440">a</span>
  <span m="1906">few</span> <span m="2371">MMU</span> <span m="2836">implementation</span>
  <span m="3302">details</span> <span m="3767">we</span> <span m="4232">can</span>
  <span m="4698">tweak</span> <span m="5163">for</span> <span m="5628">more</span>
  <span m="6094">efficiency</span> <span m="6559">or</span> <span m="7024">functionality.</span></p><p><span
  m="7490">In</span> <span m="7872">our</span> <span m="8254">simple</span> <span
  m="8636">page-map</span> <span m="9018">implementation,</span> <span m="9400">the</span>
  <span m="9782">full</span> <span m="10165">page</span> <span m="10547">map</span>
  <span m="10929">occupies</span> <span m="11311">some</span> <span m="11693">number</span>
  <span m="12075">of</span> <span m="12457">physical</span> <span m="12840">pages.</span></p><p><span
  m="14350">Using</span> <span m="14654">the</span> <span m="14958">numbers</span>
  <span m="15263">shown</span> <span m="15567">here,</span> <span m="15871">if</span>
  <span m="16176">each</span> <span m="16480">page</span> <span m="16785">map</span>
  <span m="17089">entry</span> <span m="17393">occupies</span> <span m="17698">one</span>
  <span m="18002">word</span> <span m="18306">of</span> <span m="18611">main</span>
  <span m="18915">memory,</span> <span m="19220">we'd</span> <span m="19700">need</span>
  <span m="20181">2^20</span> <span m="20662">words</span> <span m="21143">(or</span>
  <span m="21624">2^10</span> <span m="22105">pages)</span> <span m="22585">to</span>
  <span m="23066">hold</span> <span m="23547">the</span> <span m="24028">page</span>
  <span m="24509">table.</span></p><p><span m="24990">If</span> <span m="25324">we</span>
  <span m="25658">have</span> <span m="25993">multiple</span> <span m="26327">contexts,</span>
  <span m="26661">we</span> <span m="26996">would</span> <span m="27330">need</span>
  <span m="27665">multiple</span> <span m="27999">page</span> <span m="28333">tables,</span>
  <span m="28668">and</span> <span m="29002">the</span> <span m="29336">demands</span>
  <span m="29671">on</span> <span m="30005">our</span> <span m="30340">physical</span>
  <span m="30935">memory</span> <span m="31530">resources</span> <span m="32125">would</span>
  <span m="32720">start</span> <span m="33315">to</span> <span m="33910">get</span>
  <span m="34505">large.</span></p><p><span m="35100">The</span> <span m="35572">MMU</span>
  <span m="36045">implementation</span> <span m="36518">shown</span> <span m="36991">here</span>
  <span m="37464">uses</span> <span m="37937">a</span> <span m="38410">hierarchical</span>
  <span m="38883">page</span> <span m="39356">map.</span></p><p><span m="39829">The</span>
  <span m="40197">top</span> <span m="40566">10</span> <span m="40935">bits</span>
  <span m="41304">of</span> <span m="41673">virtual</span> <span m="42041">address</span>
  <span m="42410">are</span> <span m="42779">used</span> <span m="43148">to</span>
  <span m="43517">access</span> <span m="43885">a</span> <span m="44254">&quot;page</span>
  <span m="44623">directory&quot;,</span> <span m="44992">which</span> <span m="45361">indicates</span>
  <span m="45730">the</span> <span m="46135">physical</span> <span m="46541">page</span>
  <span m="46946">that</span> <span m="47352">holds</span> <span m="47757">the</span>
  <span m="48163">page</span> <span m="48568">map</span> <span m="48974">for</span>
  <span m="49380">that</span> <span m="49785">segment</span> <span m="50191">of</span>
  <span m="50596">the</span> <span m="51002">virtual</span> <span m="51407">address</span>
  <span m="51813">space.</span></p><p><span m="52219">The</span> <span m="52502">key</span>
  <span m="52785">idea</span> <span m="53068">is</span> <span m="53351">that</span>
  <span m="53634">the</span> <span m="53917">page</span> <span m="54200">map</span>
  <span m="54483">segments</span> <span m="54766">are</span> <span m="55049">in</span>
  <span m="55332">virtual</span> <span m="55615">memory,</span> <span m="55898">i.e.,</span>
  <span m="56181">they</span> <span m="56464">don't</span> <span m="56747">all</span>
  <span m="57030">have</span> <span m="57471">to</span> <span m="57912">be</span>
  <span m="58353">resident</span> <span m="58794">at</span> <span m="59235">any</span>
  <span m="59676">given</span> <span m="60117">time.</span></p><p><span m="60559">If</span>
  <span m="60879">the</span> <span m="61200">running</span> <span m="61521">application</span>
  <span m="61841">is</span> <span m="62162">only</span> <span m="62483">actively</span>
  <span m="62804">using</span> <span m="63124">a</span> <span m="63445">small</span>
  <span m="63766">portion</span> <span m="64087">of</span> <span m="64407">its</span>
  <span m="64728">virtual</span> <span m="65049">address</span> <span m="65370">space,</span>
  <span m="65703">we</span> <span m="66036">may</span> <span m="66370">only</span>
  <span m="66703">need</span> <span m="67037">a</span> <span m="67370">handful</span>
  <span m="67704">of</span> <span m="68037">pages</span> <span m="68371">to</span>
  <span m="68704">hold</span> <span m="69038">the</span> <span m="69371">page</span>
  <span m="69705">directory</span> <span m="70038">and</span> <span m="70372">the</span>
  <span m="70705">necessary</span> <span m="71039">page</span> <span m="71786">map</span>
  <span m="72533">segments.</span></p><p><span m="73280">The</span> <span m="73634">resultant</span>
  <span m="73989">savings</span> <span m="74344">really</span> <span m="74698">add</span>
  <span m="75053">up</span> <span m="75408">when</span> <span m="75762">there</span>
  <span m="76117">are</span> <span m="76472">many</span> <span m="76826">applications,</span>
  <span m="77181">each</span> <span m="77536">with</span> <span m="77890">their</span>
  <span m="78245">own</span> <span m="78600">context.</span></p><p><span m="80430">In</span>
  <span m="80831">this</span> <span m="81233">example,</span> <span m="81635">note</span>
  <span m="82037">that</span> <span m="82439">the</span> <span m="82841">middle</span>
  <span m="83243">entries</span> <span m="83645">in</span> <span m="84046">the</span>
  <span m="84448">page</span> <span m="84850">directory,</span> <span m="85252">i.e.,</span>
  <span m="85654">the</span> <span m="86056">entries</span> <span m="86458">corresponding</span>
  <span m="86860">to</span> <span m="87238">the</span> <span m="87616">as-yet</span>
  <span m="87994">unallocated</span> <span m="88372">virtual</span> <span m="88750">memory</span>
  <span m="89128">between</span> <span m="89506">the</span> <span m="89885">stack</span>
  <span m="90263">and</span> <span m="90641">heap,</span> <span m="91019">are</span>
  <span m="91397">all</span> <span m="91775">marked</span> <span m="92153">as</span>
  <span m="92531">not</span> <span m="92910">resident.</span></p><p><span m="93910">.133</span>
  <span m="94208">So</span> <span m="94506">no</span> <span m="94804">page</span>
  <span m="95102">map</span> <span m="95400">resources</span> <span m="95699">need</span>
  <span m="95997">be</span> <span m="96295">devoted</span> <span m="96593">to</span>
  <span m="96891">holding</span> <span m="97189">a</span> <span m="97488">zillion</span>
  <span m="97786">page</span> <span m="98084">map</span> <span m="98382">entries</span>
  <span m="98680">all</span> <span m="98979">marked</span> <span m="100042">&quot;not</span>
  <span m="101106">resident&quot;.</span></p><p><span m="102170">Accessing</span>
  <span m="102511">the</span> <span m="102853">page</span> <span m="103195">map</span>
  <span m="103537">now</span> <span m="103879">requires</span> <span m="104221">two</span>
  <span m="104563">access</span> <span m="104905">to</span> <span m="105246">main</span>
  <span m="105588">memory</span> <span m="105930">(first</span> <span m="106272">to</span>
  <span m="106614">the</span> <span m="106956">page</span> <span m="107298">directory,</span>
  <span m="107640">then</span> <span m="107898">to</span> <span m="108157">the</span>
  <span m="108416">appropriate</span> <span m="108675">segment</span> <span m="108934">of</span>
  <span m="109193">the</span> <span m="109452">page</span> <span m="109711">map),</span>
  <span m="109970">but</span> <span m="110549">the</span> <span m="111128">TLB</span>
  <span m="111707">makes</span> <span m="112286">the</span> <span m="112865">impact</span>
  <span m="113444">of</span> <span m="114023">that</span> <span m="114602">additional</span>
  <span m="115181">access</span> <span m="115760">negligible.</span></p><p><span m="116340">Normally</span>
  <span m="116708">when</span> <span m="117077">changing</span> <span m="117445">contexts,</span>
  <span m="117814">the</span> <span m="118182">OS</span> <span m="118551">would</span>
  <span m="118920">reload</span> <span m="119288">the</span> <span m="119657">page-table</span>
  <span m="120025">pointer</span> <span m="120394">to</span> <span m="120762">point</span>
  <span m="121131">to</span> <span m="121500">the</span> <span m="121820">appropriate</span>
  <span m="122141">page</span> <span m="122462">table</span> <span m="122782">(or</span>
  <span m="123103">page</span> <span m="123424">table</span> <span m="123744">directory</span>
  <span m="124065">if</span> <span m="124386">we</span> <span m="124706">adopt</span>
  <span m="125027">the</span> <span m="125348">scheme</span> <span m="125668">from</span>
  <span m="125989">the</span> <span m="126310">previous</span> <span m="127280">slide).</span></p><p><span
  m="128250">Since</span> <span m="128558">this</span> <span m="128867">context</span>
  <span m="129176">switch</span> <span m="129484">in</span> <span m="129793">effect</span>
  <span m="130102">changes</span> <span m="130410">all</span> <span m="130719">the</span>
  <span m="131028">entries</span> <span m="131336">in</span> <span m="131645">the</span>
  <span m="131954">page</span> <span m="132262">table,</span> <span m="132571">the</span>
  <span m="132880">OS</span> <span m="133189">would</span> <span m="133611">also</span>
  <span m="134034">have</span> <span m="134456">to</span> <span m="134879">invalidate</span>
  <span m="135301">all</span> <span m="135724">the</span> <span m="136147">entries</span>
  <span m="136569">in</span> <span m="136992">the</span> <span m="137414">TLB</span>
  <span m="137837">cache.</span></p><p><span m="138260">This</span> <span m="138587">naturally</span>
  <span m="138914">has</span> <span m="139241">a</span> <span m="139568">huge</span>
  <span m="139895">impact</span> <span m="140222">on</span> <span m="140549">the</span>
  <span m="140876">TLB</span> <span m="141203">hit</span> <span m="141530">ratio</span>
  <span m="141857">and</span> <span m="142184">the</span> <span m="142511">average</span>
  <span m="142838">memory</span> <span m="143165">access</span> <span m="143492">time</span>
  <span m="143819">takes</span> <span m="144130">a</span> <span m="144441">huge</span>
  <span m="144752">hit</span> <span m="145063">because</span> <span m="145375">of</span>
  <span m="145686">the</span> <span m="145997">all</span> <span m="146308">page</span>
  <span m="146620">map</span> <span m="146931">accesses</span> <span m="147242">that</span>
  <span m="147553">are</span> <span m="147865">now</span> <span m="148176">necessary</span>
  <span m="148487">until</span> <span m="148798">the</span> <span m="149110">TLB</span>
  <span m="150003">is</span> <span m="150896">refilled.</span></p><p><span m="151790">To</span>
  <span m="152233">reduce</span> <span m="152676">the</span> <span m="153119">impact</span>
  <span m="153562">of</span> <span m="154005">context</span> <span m="154448">switches,</span>
  <span m="154891">some</span> <span m="155334">MMUs</span> <span m="155777">include</span>
  <span m="156220">a</span> <span m="156663">context-number</span> <span m="157106">register</span>
  <span m="157549">whose</span> <span m="157992">contents</span> <span m="158435">are</span>
  <span m="158878">concatenated</span> <span m="159321">with</span> <span m="159764">the</span>
  <span m="160207">virtual</span> <span m="160650">page</span> <span m="161094">number</span>
  <span m="161537">to</span> <span m="161980">form</span> <span m="162423">the</span>
  <span m="162866">query</span> <span m="163309">to</span> <span m="163752">the</span>
  <span m="164195">TLB.</span></p><p><span m="164639">Essentially</span> <span m="164964">this</span>
  <span m="165289">means</span> <span m="165614">that</span> <span m="165939">the</span>
  <span m="166264">tag</span> <span m="166589">field</span> <span m="166914">in</span>
  <span m="167239">the</span> <span m="167564">TLB</span> <span m="167889">cache</span>
  <span m="168214">entries</span> <span m="168539">will</span> <span m="168864">expand</span>
  <span m="169189">to</span> <span m="169514">include</span> <span m="169840">the</span>
  <span m="170276">context</span> <span m="170713">number</span> <span m="171149">provided</span>
  <span m="171586">at</span> <span m="172022">the</span> <span m="172459">time</span>
  <span m="172896">the</span> <span m="173332">TLB</span> <span m="173769">entry</span>
  <span m="174205">was</span> <span m="174642">filled.</span></p><p><span m="175079">To</span>
  <span m="175463">switch</span> <span m="175848">contexts,</span> <span m="176233">the</span>
  <span m="176617">OS</span> <span m="177002">would</span> <span m="177387">now</span>
  <span m="177771">reload</span> <span m="178156">both</span> <span m="178541">the</span>
  <span m="178925">context-number</span> <span m="179310">register</span> <span m="179695">and</span>
  <span m="180079">the</span> <span m="180464">page-table</span> <span m="180849">pointer.</span></p><p><span
  m="182069">With</span> <span m="182432">a</span> <span m="182795">new</span> <span
  m="183158">context</span> <span m="183521">number,</span> <span m="183884">entries</span>
  <span m="184247">in</span> <span m="184610">the</span> <span m="184974">TLB</span>
  <span m="185337">for</span> <span m="185700">other</span> <span m="186063">contexts</span>
  <span m="186426">would</span> <span m="186789">no</span> <span m="187152">longer</span>
  <span m="187515">match,</span> <span m="187879">so</span> <span m="188243">no</span>
  <span m="188608">need</span> <span m="188972">to</span> <span m="189337">flush</span>
  <span m="189702">the</span> <span m="190066">TLB</span> <span m="190431">on</span>
  <span m="190796">a</span> <span m="191160">context</span> <span m="191525">switch.</span></p><p><span
  m="191890">If</span> <span m="192425">the</span> <span m="192961">TLB</span> <span
  m="193497">has</span> <span m="194032">sufficient</span> <span m="194568">capacity</span>
  <span m="195104">to</span> <span m="195640">cache</span> <span m="196175">the</span>
  <span m="196711">VPN-to-PPN</span> <span m="197247">mappings</span> <span m="197782">for</span>
  <span m="198318">several</span> <span m="198854">contexts,</span> <span m="199390">context</span>
  <span m="199790">switches</span> <span m="200191">would</span> <span m="200591">no</span>
  <span m="200992">longer</span> <span m="201393">have</span> <span m="201793">a</span>
  <span m="202194">substantial</span> <span m="202595">impact</span> <span m="202995">on</span>
  <span m="203396">average</span> <span m="203797">memory</span> <span m="204197">access</span>
  <span m="204598">time.</span></p><p><span m="204999">Finally,</span> <span m="205355">let's</span>
  <span m="205711">return</span> <span m="206067">to</span> <span m="206424">the</span>
  <span m="206780">question</span> <span m="207136">about</span> <span m="207493">how</span>
  <span m="207849">to</span> <span m="208205">incorporate</span> <span m="208562">both</span>
  <span m="208918">a</span> <span m="209274">cache</span> <span m="209631">and</span>
  <span m="209987">an</span> <span m="210343">MMU</span> <span m="210700">into</span>
  <span m="211349">our</span> <span m="211999">memory</span> <span m="212649">system.</span></p><p><span
  m="213299">The</span> <span m="213579">first</span> <span m="213860">choice</span>
  <span m="214140">is</span> <span m="214421">to</span> <span m="214701">place</span>
  <span m="214982">the</span> <span m="215262">cache</span> <span m="215543">between</span>
  <span m="215824">the</span> <span m="216104">CPU</span> <span m="216385">and</span>
  <span m="216665">the</span> <span m="216946">MMU,</span> <span m="217226">i.e.,</span>
  <span m="217507">the</span> <span m="217787">cache</span> <span m="218068">would</span>
  <span m="218349">work</span> <span m="218879">on</span> <span m="219409">virtual</span>
  <span m="219939">addresses.</span></p><p><span m="220470">This</span> <span m="220893">seems</span>
  <span m="221317">good:</span> <span m="221741">the</span> <span m="222165">cost</span>
  <span m="222588">of</span> <span m="223012">the</span> <span m="223436">VPN-to-PPN</span>
  <span m="223860">translation</span> <span m="224283">is</span> <span m="224707">only</span>
  <span m="225131">incurred</span> <span m="225555">on</span> <span m="225978">a</span>
  <span m="226402">cache</span> <span m="226826">miss.</span></p><p><span m="227250">The</span>
  <span m="227726">difficulty</span> <span m="228202">comes</span> <span m="228678">when</span>
  <span m="229154">there's</span> <span m="229630">a</span> <span m="230106">context</span>
  <span m="230582">switch,</span> <span m="231058">which</span> <span m="231534">changes</span>
  <span m="232010">the</span> <span m="232486">effective</span> <span m="232962">contents</span>
  <span m="233439">of</span> <span m="233962">virtual</span> <span m="234486">memory.</span></p><p><span
  m="235010">After</span> <span m="235294">all</span> <span m="235579">that</span>
  <span m="235864">was</span> <span m="236149">the</span> <span m="236434">point</span>
  <span m="236719">of</span> <span m="237004">the</span> <span m="237289">context</span>
  <span m="237574">switch,</span> <span m="237859">since</span> <span m="238144">we</span>
  <span m="238429">want</span> <span m="238714">to</span> <span m="238999">switch</span>
  <span m="239284">execution</span> <span m="239569">to</span> <span m="239942">another</span>
  <span m="240315">program.</span></p><p><span m="240689">But</span> <span m="241042">that</span>
  <span m="241396">means</span> <span m="241749">the</span> <span m="242103">OS</span>
  <span m="242456">would</span> <span m="242810">have</span> <span m="243164">to</span>
  <span m="243517">invalidate</span> <span m="243871">all</span> <span m="244224">the</span>
  <span m="244578">entries</span> <span m="244932">in</span> <span m="245285">the</span>
  <span m="245639">cache</span> <span m="245992">when</span> <span m="246346">performing</span>
  <span m="246700">a</span> <span m="247155">context</span> <span m="247611">switch,</span>
  <span m="248066">which</span> <span m="248522">makes</span> <span m="248977">the</span>
  <span m="249433">cache</span> <span m="249888">miss</span> <span m="250344">ratio</span>
  <span m="250800">quite</span> <span m="251255">large</span> <span m="251711">until</span>
  <span m="252166">the</span> <span m="252622">cache</span> <span m="253077">is</span>
  <span m="253533">refilled.</span></p><p><span m="253989">So</span> <span m="254435">once</span>
  <span m="254882">again</span> <span m="255328">the</span> <span m="255775">performance</span>
  <span m="256221">impact</span> <span m="256668">of</span> <span m="257114">a</span>
  <span m="257561">context</span> <span m="258007">switch</span> <span m="258454">would</span>
  <span m="258900">be</span> <span m="259347">quite</span> <span m="259793">high.</span></p><p><span
  m="260240">We</span> <span m="260598">can</span> <span m="260957">solve</span> <span
  m="261315">this</span> <span m="261674">problem</span> <span m="262032">by</span>
  <span m="262391">caching</span> <span m="262750">physical</span> <span m="263108">addresses,</span>
  <span m="263467">i.e.,</span> <span m="263825">placing</span> <span m="264184">the</span>
  <span m="264542">cache</span> <span m="264901">between</span> <span m="265260">the</span>
  <span m="265688">MMU</span> <span m="266116">and</span> <span m="266544">main</span>
  <span m="266972">memory.</span></p><p><span m="267400">Thus</span> <span m="267777">the</span>
  <span m="268155">contents</span> <span m="268532">of</span> <span m="268910">the</span>
  <span m="269287">cache</span> <span m="269665">are</span> <span m="270042">unaffected</span>
  <span m="270420">by</span> <span m="270797">context</span> <span m="271175">switches</span>
  <span m="271552">-</span> <span m="271930">the</span> <span m="272320">requested</span>
  <span m="272710">physical</span> <span m="273100">addresses</span> <span m="273490">will</span>
  <span m="273880">be</span> <span m="274270">different,</span> <span m="274660">but</span>
  <span m="275050">the</span> <span m="275440">cache</span> <span m="275830">handles</span>
  <span m="276220">that</span> <span m="276610">in</span> <span m="277000">due</span>
  <span m="277390">course.</span></p><p><span m="277780">The</span> <span m="278050">downside</span>
  <span m="278321">of</span> <span m="278591">this</span> <span m="278862">approach</span>
  <span m="279132">is</span> <span m="279403">that</span> <span m="279673">we</span>
  <span m="279944">have</span> <span m="280215">to</span> <span m="280485">incur</span>
  <span m="280756">the</span> <span m="281026">cost</span> <span m="281297">of</span>
  <span m="281567">the</span> <span m="281838">MMU</span> <span m="282108">translation</span>
  <span m="282379">before</span> <span m="282650">we</span> <span m="283220">can</span>
  <span m="283790">start</span> <span m="284360">the</span> <span m="284930">cache</span>
  <span m="285500">access,</span> <span m="286070">slightly</span> <span m="286640">increasing</span>
  <span m="287210">the</span> <span m="287780">average</span> <span m="288350">memory</span>
  <span m="288920">access</span> <span m="289490">time.</span></p><p><span m="290060">But</span>
  <span m="290301">if</span> <span m="290543">we're</span> <span m="290785">clever</span>
  <span m="291027">we</span> <span m="291268">don't</span> <span m="291510">have</span>
  <span m="291752">to</span> <span m="291994">wait</span> <span m="292235">for</span>
  <span m="292477">the</span> <span m="292719">MMU</span> <span m="292961">to</span>
  <span m="293202">finish</span> <span m="293444">before</span> <span m="293686">starting</span>
  <span m="293928">the</span> <span m="294170">access</span> <span m="294720">to</span>
  <span m="295270">the</span> <span m="295820">cache.</span></p><p><span m="296370">To</span>
  <span m="296633">get</span> <span m="296897">started,</span> <span m="297160">the</span>
  <span m="297424">cache</span> <span m="297687">needs</span> <span m="297951">the</span>
  <span m="298214">line</span> <span m="298478">number</span> <span m="298741">from</span>
  <span m="299005">the</span> <span m="299268">virtual</span> <span m="299532">address</span>
  <span m="299795">in</span> <span m="300059">order</span> <span m="300322">to</span>
  <span m="300586">fetch</span> <span m="300850">the</span> <span m="301555">appropriate</span>
  <span m="302260">cache</span> <span m="302965">line.</span></p><p><span m="303670">If</span>
  <span m="303978">the</span> <span m="304286">address</span> <span m="304594">bits</span>
  <span m="304902">used</span> <span m="305210">for</span> <span m="305518">the</span>
  <span m="305826">line</span> <span m="306135">number</span> <span m="306443">are</span>
  <span m="306751">completely</span> <span m="307059">contained</span> <span m="307367">in</span>
  <span m="307675">the</span> <span m="307983">page</span> <span m="308291">offset</span>
  <span m="308600">of</span> <span m="309056">the</span> <span m="309513">virtual</span>
  <span m="309970">address,</span> <span m="310426">these</span> <span m="310883">bits</span>
  <span m="311340">are</span> <span m="311796">unaffected</span> <span m="312253">by</span>
  <span m="312710">the</span> <span m="313166">MMU</span> <span m="313623">translation,</span>
  <span m="314080">and</span> <span m="314553">so</span> <span m="315026">the</span>
  <span m="315499">cache</span> <span m="315972">lookup</span> <span m="316445">can</span>
  <span m="316918">happen</span> <span m="317391">in</span> <span m="317864">parallel</span>
  <span m="318337">with</span> <span m="318810">the</span> <span m="319283">MMU</span>
  <span m="319756">operation.</span></p><p><span m="320230">Once</span> <span m="320482">the</span>
  <span m="320735">cache</span> <span m="320988">lookup</span> <span m="321241">is</span>
  <span m="321494">complete,</span> <span m="321747">the</span> <span m="322000">tag</span>
  <span m="322253">field</span> <span m="322506">of</span> <span m="322759">the</span>
  <span m="323012">cache</span> <span m="323265">line</span> <span m="323518">can</span>
  <span m="323771">be</span> <span m="324024">compared</span> <span m="324277">with</span>
  <span m="324530">the</span> <span m="324990">appropriate</span> <span m="325450">bits</span>
  <span m="325910">of</span> <span m="326370">the</span> <span m="326830">physical</span>
  <span m="327290">address</span> <span m="327750">produced</span> <span m="328210">by</span>
  <span m="328670">the</span> <span m="329130">MMU.</span></p><p><span m="329590">If</span>
  <span m="329866">there</span> <span m="330142">was</span> <span m="330418">a</span>
  <span m="330695">TLB</span> <span m="330971">hit</span> <span m="331247">in</span>
  <span m="331524">the</span> <span m="331800">MMU,</span> <span m="332076">the</span>
  <span m="332353">physical</span> <span m="332629">address</span> <span m="332905">should</span>
  <span m="333182">be</span> <span m="333458">available</span> <span m="333734">at</span>
  <span m="334011">about</span> <span m="334287">the</span> <span m="334563">same</span>
  <span m="334840">time</span> <span m="335305">as</span> <span m="335770">the</span>
  <span m="336235">tag</span> <span m="336700">field</span> <span m="337165">produced</span>
  <span m="337630">by</span> <span m="338095">the</span> <span m="338560">cache</span>
  <span m="339025">lookup.</span></p><p><span m="339490">By</span> <span m="339857">performing</span>
  <span m="340225">the</span> <span m="340593">MMU</span> <span m="340961">translation</span>
  <span m="341329">and</span> <span m="341697">cache</span> <span m="342065">lookup</span>
  <span m="342432">in</span> <span m="342800">parallel,</span> <span m="343168">there's</span>
  <span m="343536">usually</span> <span m="343904">no</span> <span m="344272">impact</span>
  <span m="344640">on</span> <span m="345061">the</span> <span m="345483">average</span>
  <span m="345905">memory</span> <span m="346326">access</span> <span m="346748">time!</span></p><p><span
  m="347170">Voila,</span> <span m="347554">the</span> <span m="347939">best</span>
  <span m="348324">of</span> <span m="348708">both</span> <span m="349093">worlds:</span>
  <span m="349478">a</span> <span m="349862">physically</span> <span m="350247">addressed</span>
  <span m="350632">cache</span> <span m="351016">that</span> <span m="351401">incurs</span>
  <span m="351786">no</span> <span m="352170">time</span> <span m="352555">penalty</span>
  <span m="352940">for</span> <span m="353986">MMU</span> <span m="355033">translation.</span></p><p><span
  m="356080">One</span> <span m="356396">final</span> <span m="356712">detail:</span>
  <span m="357029">one</span> <span m="357345">way</span> <span m="357662">to</span>
  <span m="357978">increase</span> <span m="358295">the</span> <span m="358611">capacity</span>
  <span m="358928">of</span> <span m="359244">the</span> <span m="359561">cache</span>
  <span m="359877">is</span> <span m="360194">to</span> <span m="360510">increase</span>
  <span m="360827">the</span> <span m="361143">number</span> <span m="361460">of</span>
  <span m="361841">cache</span> <span m="362222">lines</span> <span m="362603">and</span>
  <span m="362985">hence</span> <span m="363366">the</span> <span m="363747">number</span>
  <span m="364128">of</span> <span m="364510">bits</span> <span m="364891">of</span>
  <span m="365272">address</span> <span m="365653">used</span> <span m="366035">as</span>
  <span m="366416">the</span> <span m="366797">line</span> <span m="367178">number.</span></p><p><span
  m="367560">Since</span> <span m="367817">we</span> <span m="368075">want</span>
  <span m="368332">the</span> <span m="368590">line</span> <span m="368848">number</span>
  <span m="369105">to</span> <span m="369363">fit</span> <span m="369621">into</span>
  <span m="369878">the</span> <span m="370136">page</span> <span m="370394">offset</span>
  <span m="370651">field</span> <span m="370909">of</span> <span m="371167">the</span>
  <span m="371424">virtual</span> <span m="371682">address,</span> <span m="371940">we're</span>
  <span m="372252">limited</span> <span m="372564">in</span> <span m="372876">how</span>
  <span m="373188">many</span> <span m="373500">cache</span> <span m="373812">lines</span>
  <span m="374124">we</span> <span m="374436">can</span> <span m="374748">have.</span></p><p><span
  m="375060">The</span> <span m="375574">same</span> <span m="376088">argument</span>
  <span m="376603">applies</span> <span m="377117">to</span> <span m="377632">increasing</span>
  <span m="378146">the</span> <span m="378661">block</span> <span m="379175">size.</span></p><p><span
  m="379690">So</span> <span m="380084">to</span> <span m="380478">increase</span>
  <span m="380872">the</span> <span m="381266">capacity</span> <span m="381660">of</span>
  <span m="382054">the</span> <span m="382448">cache</span> <span m="382842">our</span>
  <span m="383237">only</span> <span m="383631">option</span> <span m="384025">is</span>
  <span m="384419">to</span> <span m="384813">increase</span> <span m="385207">the</span>
  <span m="385601">cache</span> <span m="385995">associativity,</span> <span m="386390">which</span>
  <span m="386916">adds</span> <span m="387443">capacity</span> <span m="387970">without</span>
  <span m="388497">affecting</span> <span m="389024">the</span> <span m="389551">address</span>
  <span m="390078">bits</span> <span m="390605">used</span> <span m="391132">for</span>
  <span m="391659">the</span> <span m="392186">line</span> <span m="392713">number.</span></p><p><span
  m="393240">That's</span> <span m="393626">it</span> <span m="394012">for</span>
  <span m="394398">our</span> <span m="394785">discussion</span> <span m="395171">of</span>
  <span m="395557">virtual</span> <span m="395943">memory.</span></p><p><span m="396330">We</span>
  <span m="396726">use</span> <span m="397122">the</span> <span m="397518">MMU</span>
  <span m="397914">to</span> <span m="398310">provide</span> <span m="398706">the</span>
  <span m="399102">context</span> <span m="399498">for</span> <span m="399894">mapping</span>
  <span m="400290">virtual</span> <span m="400686">addresses</span> <span m="401082">to</span>
  <span m="401478">physical</span> <span m="401874">addresses.</span></p><p><span
  m="402270">By</span> <span m="402668">switching</span> <span m="403066">contexts</span>
  <span m="403464">we</span> <span m="403862">can</span> <span m="404260">create</span>
  <span m="404658">the</span> <span m="405056">illusion</span> <span m="405455">of</span>
  <span m="405853">many</span> <span m="406251">virtual</span> <span m="406649">address</span>
  <span m="407047">spaces,</span> <span m="407445">so</span> <span m="407843">many</span>
  <span m="408241">programs</span> <span m="408640">can</span> <span m="409102">share</span>
  <span m="409564">a</span> <span m="410026">single</span> <span m="410489">CPU</span>
  <span m="410951">and</span> <span m="411413">physical</span> <span m="411876">memory</span>
  <span m="412338">without</span> <span m="412800">interfering</span> <span m="413263">with</span>
  <span m="413725">each</span> <span m="414187">other.</span></p><p><span m="414650">We</span>
  <span m="415039">discussed</span> <span m="415428">using</span> <span m="415818">a</span>
  <span m="416207">page</span> <span m="416596">map</span> <span m="416986">to</span>
  <span m="417375">translate</span> <span m="417764">virtual</span> <span m="418154">page</span>
  <span m="418543">numbers</span> <span m="418932">to</span> <span m="419322">physical</span>
  <span m="419711">page</span> <span m="420100">numbers.</span></p><p><span m="420490">To</span>
  <span m="420850">save</span> <span m="421210">costs,</span> <span m="421570">we</span>
  <span m="421930">located</span> <span m="422290">the</span> <span m="422650">page</span>
  <span m="423010">map</span> <span m="423370">in</span> <span m="423730">physical</span>
  <span m="424090">memory</span> <span m="424450">and</span> <span m="424810">used</span>
  <span m="425170">a</span> <span m="425530">TLB</span> <span m="425890">to</span>
  <span m="426250">eliminate</span> <span m="426610">the</span> <span m="427187">cost</span>
  <span m="427765">of</span> <span m="428342">accessing</span> <span m="428920">the</span>
  <span m="429497">page</span> <span m="430075">map</span> <span m="430652">for</span>
  <span m="431230">most</span> <span m="431807">virtual</span> <span m="432385">memory</span>
  <span m="432962">accesses.</span></p><p><span m="433540">Access</span> <span m="433869">to</span>
  <span m="434198">a</span> <span m="434528">non-resident</span> <span m="434857">page</span>
  <span m="435186">causes</span> <span m="435516">a</span> <span m="435845">page</span>
  <span m="436174">fault</span> <span m="436504">exception,</span> <span m="436833">allowing</span>
  <span m="437162">the</span> <span m="437492">OS</span> <span m="437821">to</span>
  <span m="438150">manage</span> <span m="438480">the</span> <span m="439156">complexities</span>
  <span m="439832">of</span> <span m="440508">equitably</span> <span m="441184">sharing</span>
  <span m="441860">physical</span> <span m="442536">memory</span> <span m="443212">across</span>
  <span m="443888">many</span> <span m="444564">applications.</span></p><p><span m="445240">We</span>
  <span m="445617">saw</span> <span m="445994">that</span> <span m="446371">providing</span>
  <span m="446748">contexts</span> <span m="447125">was</span> <span m="447502">the</span>
  <span m="447880">first</span> <span m="448257">step</span> <span m="448634">towards</span>
  <span m="449011">creating</span> <span m="449388">virtual</span> <span m="449765">machines,</span>
  <span m="450142">which</span> <span m="450520">is</span> <span m="450785">the</span>
  <span m="451051">topic</span> <span m="451317">of</span> <span m="451582">our</span>
  <span m="451848">next</span> <span m="452114">lecture.</span></p>
type: course
uid: 6563325959821a3d70422beeb53a1e4e

---
None