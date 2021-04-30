---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: YEZUywtDJQ4
  parent_uid: 37b8487938efd25f0fb947d9332e20b9
  title: Video-YouTube-Stream
  type: Video
  uid: eb336ecdcc4890ce3050af49b30310bb
- id: 3Play-3Play YouTube id-Stream
  media_location: YEZUywtDJQ4
  parent_uid: 37b8487938efd25f0fb947d9332e20b9
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 5ba5f7d22c5704a766416bc3e9818e58
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/YEZUywtDJQ4/default.jpg
  parent_uid: 37b8487938efd25f0fb947d9332e20b9
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 5207649247d28cbb77186a16c9ccf075
- id: YEZUywtDJQ4.srt
  parent_uid: 37b8487938efd25f0fb947d9332e20b9
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v6/procedures-and-stacks/YEZUywtDJQ4.srt
  title: 3play caption file
  type: null
  uid: 8bf697eb710ec4e04faf5d232716579a
- id: YEZUywtDJQ4.pdf
  parent_uid: 37b8487938efd25f0fb947d9332e20b9
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v6/procedures-and-stacks/YEZUywtDJQ4.pdf
  title: 3play pdf file
  type: null
  uid: e721ed9aaf5156cf04a9bf124564f4a0
- id: Caption-3Play YouTube id-SRT
  parent_uid: 37b8487938efd25f0fb947d9332e20b9
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 2f69afadeed13b797169a3df1e7dcc21
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 37b8487938efd25f0fb947d9332e20b9
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 073ccc0f4a6287ea61fce238116a044a
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_12-02-06-01_300k.mp4
  parent_uid: 37b8487938efd25f0fb947d9332e20b9
  title: Video-Internet Archive-MP4
  type: Video
  uid: f7147fa2c844b841bafc27dd46c4b29e
inline_embed_id: 1652128proceduresandstacks71889182
layout: video
order_index: null
parent_uid: db025749465e168b6cb5223f596aae59
related_resources_text: ''
short_url: procedures-and-stacks
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v6/procedures-and-stacks
template_type: Embed
title: 'Worked Example: Procedures and Stacks'
transcript: <p><span m="1350">In</span> <span m="1642">order</span> <span m="1934">to</span>
  <span m="2227">understand</span> <span m="2519">how</span> <span m="2812">procedures</span>
  <span m="3104">are</span> <span m="3397">implemented</span> <span m="3689">on</span>
  <span m="3981">the</span> <span m="4274">beta,</span> <span m="4566">we</span> <span
  m="4859">will</span> <span m="5151">take</span> <span m="5444">a</span> <span m="5736">look</span>
  <span m="6029">at</span> <span m="6550">a</span> <span m="7072">mystery</span> <span
  m="7594">function</span> <span m="8116">and</span> <span m="8638">its</span> <span
  m="9160">translation</span> <span m="9682">into</span> <span m="10204">beta</span>
  <span m="10726">assembly</span> <span m="11248">code.</span></p><p><span m="11770">The</span>
  <span m="12177">mystery</span> <span m="12585">function</span> <span m="12992">is</span>
  <span m="13400">shown</span> <span m="13807">here:</span> <span m="14215">The</span>
  <span m="14622">function</span> <span m="15030">f</span> <span m="15437">takes</span>
  <span m="15845">an</span> <span m="16252">argument</span> <span m="16660">x</span>
  <span m="17067">as</span> <span m="17475">an</span> <span m="17882">input.</span></p><p><span
  m="18290">It</span> <span m="18631">then</span> <span m="18972">performs</span>
  <span m="19313">a</span> <span m="19654">logical</span> <span m="19995">AND</span>
  <span m="20337">operation</span> <span m="20678">on</span> <span m="21019">the</span>
  <span m="21360">input</span> <span m="21701">x</span> <span m="22042">and</span>
  <span m="22384">the</span> <span m="22725">constant</span> <span m="23066">5</span>
  <span m="23407">to</span> <span m="23748">produce</span> <span m="24090">the</span>
  <span m="24455">variable</span> <span m="24820">a.</span> <span m="25186">After</span>
  <span m="25551">that,</span> <span m="25916">it</span> <span m="26282">checks</span>
  <span m="26647">if</span> <span m="27013">the</span> <span m="27378">input</span>
  <span m="27743">x</span> <span m="28109">is</span> <span m="28474">equal</span>
  <span m="28840">to</span> <span m="29215">0,</span> <span m="29591">and</span> <span
  m="29966">if</span> <span m="30342">so</span> <span m="30717">returns</span> <span
  m="31093">the</span> <span m="31468">value</span> <span m="31844">0,</span> <span
  m="32220">otherwise</span> <span m="32595">it</span> <span m="32971">returns</span>
  <span m="33346">an</span> <span m="33722">unknown</span> <span m="34097">value</span>
  <span m="34473">which</span> <span m="34848">we</span> <span m="35224">need</span>
  <span m="35600">to</span> <span m="35995">determine.</span> <span m="36390">We</span>
  <span m="36785">are</span> <span m="37180">provided</span> <span m="37575">with</span>
  <span m="37970">the</span> <span m="38365">translation</span> <span m="38760">of</span>
  <span m="39155">this</span> <span m="39550">C</span> <span m="39873">code</span>
  <span m="40197">into</span> <span m="40520">beta</span> <span m="40844">assembly</span>
  <span m="41167">as</span> <span m="41491">shown</span> <span m="41814">here.</span>
  <span m="42138">We</span> <span m="42461">take</span> <span m="42785">a</span> <span
  m="43108">closer</span> <span m="43432">look</span> <span m="43755">at</span> <span
  m="44079">the</span> <span m="44402">various</span> <span m="44726">parts</span>
  <span m="45050">of</span> <span m="45394">this</span> <span m="45738">code</span>
  <span m="46082">to</span> <span m="46426">understand</span> <span m="46770">how</span>
  <span m="47114">this</span> <span m="47458">function</span> <span m="47802">as</span>
  <span m="48146">well</span> <span m="48490">as</span> <span m="48834">procedures</span>
  <span m="49178">in</span> <span m="49522">general</span> <span m="49866">work</span>
  <span m="50210">on</span> <span m="50554">the</span> <span m="50899">beta.</span>
  <span m="51466">The</span> <span m="52034">code</span> <span m="52602">that</span>
  <span m="53170">calls</span> <span m="53738">the</span> <span m="54306">procedure</span>
  <span m="54874">is</span> <span m="55442">responsible</span> <span m="56010">for</span>
  <span m="56319">pushing</span> <span m="56629">any</span> <span m="56939">arguments</span>
  <span m="57249">onto</span> <span m="57559">the</span> <span m="57869">stack.</span>
  <span m="58179">This</span> <span m="58489">is</span> <span m="58799">shown</span>
  <span m="59109">in</span> <span m="59419">pink</span> <span m="59729">in</span>
  <span m="60039">the</span> <span m="60349">code</span> <span m="60659">and</span>
  <span m="60969">on</span> <span m="61279">the</span> <span m="61589">stack.</span>
  <span m="62037">If</span> <span m="62486">there</span> <span m="62935">are</span>
  <span m="63384">multiple</span> <span m="63833">arguments</span> <span m="64282">then</span>
  <span m="64731">they</span> <span m="65180">are</span> <span m="65556">pushed</span>
  <span m="65932">in</span> <span m="66309">reverse</span> <span m="66685">order</span>
  <span m="67062">so</span> <span m="67438">that</span> <span m="67815">the</span>
  <span m="68191">first</span> <span m="68568">argument</span> <span m="68944">is</span>
  <span m="69321">always</span> <span m="69697">in</span> <span m="70074">the</span>
  <span m="70450">same</span> <span m="70827">location</span> <span m="71203">relative</span>
  <span m="71580">to</span> <span m="71987">the</span> <span m="72394">BP,</span>
  <span m="72801">or</span> <span m="73208">base</span> <span m="73615">pointer,</span>
  <span m="74022">register</span> <span m="74430">which</span> <span m="74837">we</span>
  <span m="75244">will</span> <span m="75651">see</span> <span m="76058">in</span>
  <span m="76465">a</span> <span m="76872">moment.</span></p><p><span m="77280">The</span>
  <span m="77696">BR</span> <span m="78112">instruction</span> <span m="78528">branches</span>
  <span m="78944">to</span> <span m="79360">label</span> <span m="79777">f</span>
  <span m="80193">after</span> <span m="80609">storing</span> <span m="81025">the</span>
  <span m="81441">return</span> <span m="81858">address,</span> <span m="82274">which</span>
  <span m="82690">is</span> <span m="83106">b,</span> <span m="83522">into</span>
  <span m="83939">the</span> <span m="84407">LP,</span> <span m="84875">or</span>
  <span m="85343">linkage</span> <span m="85811">pointer,</span> <span m="86279">register.</span>
  <span m="86747">In</span> <span m="87215">yellow,</span> <span m="87683">we</span>
  <span m="88151">see</span> <span m="88619">the</span> <span m="89087">entry</span>
  <span m="89555">sequence</span> <span m="90023">for</span> <span m="90491">the</span>
  <span m="90960">procedure.</span> <span m="91408">The</span> <span m="91857">structure</span>
  <span m="92306">of</span> <span m="92755">this</span> <span m="93204">entry</span>
  <span m="93653">sequence</span> <span m="94102">is</span> <span m="94551">identical</span>
  <span m="95000">for</span> <span m="95468">all</span> <span m="95937">procedures.</span>
  <span m="96406">The</span> <span m="96875">first</span> <span m="97344">thing</span>
  <span m="97813">it</span> <span m="98282">does</span> <span m="98751">is</span>
  <span m="99220">PUSH(LP)</span> <span m="99689">which</span> <span m="100158">pushes</span>
  <span m="100525">the</span> <span m="100892">LP</span> <span m="101260">register</span>
  <span m="101627">onto</span> <span m="101995">the</span> <span m="102362">stack</span>
  <span m="102730">immediately</span> <span m="103097">after</span> <span m="103465">the</span>
  <span m="103832">arguments</span> <span m="104200">that</span> <span m="104567">were</span>
  <span m="104935">pushed</span> <span m="105302">onto</span> <span m="105670">the</span>
  <span m="106056">stack</span> <span m="106443">by</span> <span m="106829">the</span>
  <span m="107216">caller.</span> <span m="107603">Next</span> <span m="107989">it</span>
  <span m="108376">pushes</span> <span m="108762">the</span> <span m="109149">BP</span>
  <span m="109536">onto</span> <span m="109922">the</span> <span m="110309">stack</span>
  <span m="110695">in</span> <span m="111082">order</span> <span m="111469">to</span>
  <span m="111875">save</span> <span m="112281">the</span> <span m="112687">most</span>
  <span m="113093">recent</span> <span m="113499">value</span> <span m="113905">of</span>
  <span m="114312">the</span> <span m="114718">BP</span> <span m="115124">register</span>
  <span m="115530">before</span> <span m="115936">updating</span> <span m="116342">it.</span></p><p><span
  m="116749">Now,</span> <span m="117286">a</span> <span m="117823">MOVE(SP,</span>
  <span m="118360">BP)</span> <span m="118897">is</span> <span m="119435">performed.</span>
  <span m="119972">SP</span> <span m="120509">is</span> <span m="121046">the</span>
  <span m="121583">stack</span> <span m="122121">pointer</span> <span m="122658">which</span>
  <span m="123195">always</span> <span m="123732">points</span> <span m="124270">to</span>
  <span m="124652">the</span> <span m="125035">next</span> <span m="125418">empty</span>
  <span m="125801">location</span> <span m="126184">on</span> <span m="126567">the</span>
  <span m="126950">stack.</span> <span m="127333">At</span> <span m="127716">the</span>
  <span m="128099">time</span> <span m="128482">that</span> <span m="128865">this</span>
  <span m="129248">MOVE</span> <span m="129631">operation</span> <span m="130014">is</span>
  <span m="130397">executed,</span> <span m="130780">the</span> <span m="131250">SP,</span>
  <span m="131720">points</span> <span m="132190">to</span> <span m="132660">the</span>
  <span m="133130">location</span> <span m="133600">immediately</span> <span m="134070">following</span>
  <span m="134540">the</span> <span m="135010">saved</span> <span m="135480">BP.</span></p><p><span
  m="135950">This</span> <span m="136281">move</span> <span m="136613">instruction</span>
  <span m="136945">makes</span> <span m="137277">the</span> <span m="137609">BP</span>
  <span m="137941">point</span> <span m="138273">to</span> <span m="138605">the</span>
  <span m="138936">same</span> <span m="139268">location</span> <span m="139600">that</span>
  <span m="139932">the</span> <span m="140264">SP</span> <span m="140596">is</span>
  <span m="140928">currently</span> <span m="141260">pointing</span> <span m="141726">to,</span>
  <span m="142192">which</span> <span m="142658">is</span> <span m="143124">the</span>
  <span m="143590">location</span> <span m="144056">that</span> <span m="144523">is</span>
  <span m="144989">immediately</span> <span m="145455">following</span> <span m="145921">the</span>
  <span m="146387">saved</span> <span m="146853">BP.</span></p><p><span m="147320">Note,</span>
  <span m="147675">that</span> <span m="148030">once</span> <span m="148385">the</span>
  <span m="148741">BP</span> <span m="149096">register</span> <span m="149451">is</span>
  <span m="149807">set</span> <span m="150162">up,</span> <span m="150517">one</span>
  <span m="150872">can</span> <span m="151228">always</span> <span m="151583">find</span>
  <span m="151938">the</span> <span m="152294">first</span> <span m="152649">argument</span>
  <span m="153004">at</span> <span m="153360">location</span> <span m="153876">BP</span>
  <span m="154392">&ndash;</span> <span m="154908">12</span> <span m="155424">(or</span>
  <span m="155940">in</span> <span m="156456">other</span> <span m="156972">words,</span>
  <span m="157488">3</span> <span m="158004">words</span> <span m="158520">before</span>
  <span m="159036">the</span> <span m="159552">current</span> <span m="160068">BP</span>
  <span m="160584">register).</span></p><p><span m="161100">If</span> <span m="161510">there</span>
  <span m="161920">was</span> <span m="162330">a</span> <span m="162740">second</span>
  <span m="163150">argument,</span> <span m="163560">it</span> <span m="163970">could</span>
  <span m="164380">be</span> <span m="164790">found</span> <span m="165200">in</span>
  <span m="165610">location</span> <span m="166020">BP</span> <span m="166430">&ndash;</span>
  <span m="166840">16,</span> <span m="167250">and</span> <span m="167660">so</span>
  <span m="168070">on.</span></p><p><span m="168480">Next,</span> <span m="168968">we</span>
  <span m="169456">allocate</span> <span m="169944">space</span> <span m="170432">on</span>
  <span m="170920">the</span> <span m="171409">stack</span> <span m="171897">for</span>
  <span m="172385">any</span> <span m="172873">local</span> <span m="173361">variables.</span></p><p><span
  m="173850">This</span> <span m="174317">procedure</span> <span m="174785">allocates</span>
  <span m="175252">space</span> <span m="175720">for</span> <span m="176187">one</span>
  <span m="176655">local</span> <span m="177122">variable.</span></p><p><span m="177590">Finally,</span>
  <span m="177965">we</span> <span m="178341">push</span> <span m="178717">all</span>
  <span m="179093">registers</span> <span m="179469">that</span> <span m="179845">are</span>
  <span m="180221">going</span> <span m="180597">to</span> <span m="180972">be</span>
  <span m="181348">modified</span> <span m="181724">by</span> <span m="182100">our</span>
  <span m="182476">procedure</span> <span m="182852">onto</span> <span m="183228">the</span>
  <span m="183604">stack.</span></p><p><span m="183980">Doing</span> <span m="184325">this</span>
  <span m="184670">makes</span> <span m="185015">it</span> <span m="185360">possible</span>
  <span m="185705">to</span> <span m="186050">recover</span> <span m="186395">the</span>
  <span m="186740">registers'</span> <span m="187085">original</span> <span m="187430">values</span>
  <span m="187775">once</span> <span m="188120">the</span> <span m="188465">procedure</span>
  <span m="188810">completes</span> <span m="189325">execution.</span> <span m="189840">In</span>
  <span m="190355">this</span> <span m="190870">example,</span> <span m="191385">register</span>
  <span m="191900">R1</span> <span m="192415">is</span> <span m="192930">saved</span>
  <span m="193445">onto</span> <span m="193960">the</span> <span m="194473">stack.</span>
  <span m="194986">Once</span> <span m="195499">the</span> <span m="196012">entry</span>
  <span m="196525">sequence</span> <span m="197038">is</span> <span m="197551">complete,</span>
  <span m="198064">the</span> <span m="198577">BP</span> <span m="199090">register</span>
  <span m="199484">still</span> <span m="199879">points</span> <span m="200273">to</span>
  <span m="200668">the</span> <span m="201062">location</span> <span m="201457">immediately</span>
  <span m="201851">following</span> <span m="202246">the</span> <span m="202640">saved</span>
  <span m="203035">BP.</span></p><p><span m="203430">The</span> <span m="204010">SP,</span>
  <span m="204591">however,</span> <span m="205172">now</span> <span m="205752">points</span>
  <span m="206333">to</span> <span m="206914">the</span> <span m="207495">location</span>
  <span m="208075">immediately</span> <span m="208656">following</span> <span m="209237">the</span>
  <span m="209817">saved</span> <span m="210398">R1</span> <span m="210979">register.</span></p><p><span
  m="211560">So</span> <span m="211932">for</span> <span m="212305">this</span> <span
  m="212678">procedure,</span> <span m="213051">after</span> <span m="213424">executing</span>
  <span m="213797">the</span> <span m="214170">entry</span> <span m="214542">sequence,</span>
  <span m="214915">the</span> <span m="215288">stack</span> <span m="215661">has</span>
  <span m="216034">been</span> <span m="216407">modified</span> <span m="216780">as</span>
  <span m="217228">shown</span> <span m="217676">here.</span> <span m="218124">The</span>
  <span m="218572">procedure</span> <span m="219020">return,</span> <span m="219468">or</span>
  <span m="219916">exit,</span> <span m="220364">sequence</span> <span m="220812">for</span>
  <span m="221260">all</span> <span m="221628">beta</span> <span m="221996">procedures</span>
  <span m="222364">follows</span> <span m="222732">the</span> <span m="223100">same</span>
  <span m="223468">structure.</span> <span m="223836">It</span> <span m="224205">is</span>
  <span m="224573">assumed</span> <span m="224941">that</span> <span m="225309">the</span>
  <span m="225677">return</span> <span m="226045">value</span> <span m="226413">for</span>
  <span m="226781">the</span> <span m="227150">procedure</span> <span m="227678">has</span>
  <span m="228207">already</span> <span m="228736">been</span> <span m="229265">placed</span>
  <span m="229793">into</span> <span m="230322">register</span> <span m="230851">R0.</span></p><p><span
  m="231380">Next,</span> <span m="231782">all</span> <span m="232185">registers</span>
  <span m="232588">that</span> <span m="232990">were</span> <span m="233393">used</span>
  <span m="233796">in</span> <span m="234198">the</span> <span m="234601">procedure</span>
  <span m="235004">body,</span> <span m="235406">are</span> <span m="235809">restored</span>
  <span m="236212">to</span> <span m="236614">their</span> <span m="237017">original</span>
  <span m="237420">values.</span> <span m="237783">This</span> <span m="238146">is</span>
  <span m="238510">followed</span> <span m="238873">by</span> <span m="239236">deallocating</span>
  <span m="239600">all</span> <span m="239963">of</span> <span m="240326">the</span>
  <span m="240690">local</span> <span m="241090">variables</span> <span m="241491">from</span>
  <span m="241892">the</span> <span m="242292">stack.</span> <span m="242693">We</span>
  <span m="243094">then</span> <span m="243495">restore</span> <span m="243895">the</span>
  <span m="244296">BP,</span> <span m="244697">followed</span> <span m="245097">by</span>
  <span m="245498">the</span> <span m="245899">LP</span> <span m="246300">register.</span>
  <span m="246773">Finally,</span> <span m="247246">we</span> <span m="247720">jump</span>
  <span m="248193">to</span> <span m="248666">LP</span> <span m="249140">which</span>
  <span m="249613">contains</span> <span m="250086">the</span> <span m="250560">return</span>
  <span m="250975">address</span> <span m="251391">of</span> <span m="251807">our</span>
  <span m="252222">procedure.</span> <span m="252638">In</span> <span m="253054">this</span>
  <span m="253470">case,</span> <span m="253885">LP</span> <span m="254301">contains</span>
  <span m="254717">the</span> <span m="255132">address</span> <span m="255548">b</span>
  <span m="255964">which</span> <span m="256380">is</span> <span m="256739">the</span>
  <span m="257098">address</span> <span m="257457">of</span> <span m="257817">the</span>
  <span m="258176">next</span> <span m="258535">instruction</span> <span m="258895">that</span>
  <span m="259254">should</span> <span m="259613">be</span> <span m="259972">executed</span>
  <span m="260332">following</span> <span m="260691">the</span> <span m="261050">execution</span>
  <span m="261410">of</span> <span m="261829">the</span> <span m="262248">f</span>
  <span m="262667">procedure.</span> <span m="263086">Taking</span> <span m="263506">a</span>
  <span m="263925">closer</span> <span m="264344">look</span> <span m="264763">at</span>
  <span m="265183">the</span> <span m="265602">details</span> <span m="266021">for</span>
  <span m="266440">our</span> <span m="266860">example,</span> <span m="267214">we</span>
  <span m="267568">see</span> <span m="267922">that</span> <span m="268276">we</span>
  <span m="268630">begin</span> <span m="268984">our</span> <span m="269338">exit</span>
  <span m="269692">sequence</span> <span m="270047">with</span> <span m="270401">POP(R1)</span>
  <span m="270755">in</span> <span m="271109">order</span> <span m="271463">to</span>
  <span m="271817">restore</span> <span m="272171">the</span> <span m="272525">original</span>
  <span m="272880">value</span> <span m="273255">of</span> <span m="273631">register</span>
  <span m="274007">R1.</span> <span m="274383">Note</span> <span m="274759">that</span>
  <span m="275135">this</span> <span m="275510">also</span> <span m="275886">frees</span>
  <span m="276262">up</span> <span m="276638">the</span> <span m="277014">location</span>
  <span m="277390">on</span> <span m="277714">the</span> <span m="278038">stack</span>
  <span m="278362">that</span> <span m="278686">was</span> <span m="279010">used</span>
  <span m="279335">to</span> <span m="279659">store</span> <span m="279983">the</span>
  <span m="280307">value</span> <span m="280631">of</span> <span m="280955">R1.</span></p><p><span
  m="281280">Next,</span> <span m="281657">we</span> <span m="282035">get</span> <span
  m="282413">rid</span> <span m="282790">of</span> <span m="283168">the</span> <span
  m="283546">local</span> <span m="283923">variables</span> <span m="284301">we</span>
  <span m="284679">stored</span> <span m="285056">on</span> <span m="285434">the</span>
  <span m="285812">stack.</span></p><p><span m="286190">This</span> <span m="286597">is</span>
  <span m="287004">achieved</span> <span m="287411">using</span> <span m="287818">the</span>
  <span m="288225">MOVE(BP,</span> <span m="288632">SP)</span> <span m="289039">instruction</span>
  <span m="289446">which</span> <span m="289853">makes</span> <span m="290260">the</span>
  <span m="290667">SP</span> <span m="291074">point</span> <span m="291481">to</span>
  <span m="291888">the</span> <span m="292295">same</span> <span m="292702">location</span>
  <span m="293110">as</span> <span m="293601">the</span> <span m="294092">BP</span>
  <span m="294583">thus</span> <span m="295075">specifying</span> <span m="295566">that</span>
  <span m="296057">all</span> <span m="296548">the</span> <span m="297040">locations</span>
  <span m="297531">following</span> <span m="298022">the</span> <span m="298513">updated</span>
  <span m="299005">SP</span> <span m="299496">are</span> <span m="299987">now</span>
  <span m="300478">considered</span> <span m="300970">unused.</span> <span m="301547">Next,</span>
  <span m="302124">we</span> <span m="302701">restore</span> <span m="303278">the</span>
  <span m="303855">BP</span> <span m="304432">register.</span></p><p><span m="305010">Restoring</span>
  <span m="305508">the</span> <span m="306006">BP</span> <span m="306504">register</span>
  <span m="307002">is</span> <span m="307500">particularly</span> <span m="307999">important</span>
  <span m="308497">for</span> <span m="308995">nested</span> <span m="309493">procedure</span>
  <span m="309991">calls.</span></p><p><span m="310490">If</span> <span m="310814">we</span>
  <span m="311138">did</span> <span m="311463">not</span> <span m="311787">restore</span>
  <span m="312111">the</span> <span m="312436">BP</span> <span m="312760">register,</span>
  <span m="313085">then</span> <span m="313409">upon</span> <span m="313733">return</span>
  <span m="314058">to</span> <span m="314382">the</span> <span m="314706">calling</span>
  <span m="315031">procedure,</span> <span m="315355">the</span> <span m="315680">calling</span>
  <span m="315987">procedure</span> <span m="316295">would</span> <span m="316603">no</span>
  <span m="316911">longer</span> <span m="317219">have</span> <span m="317527">a</span>
  <span m="317835">correct</span> <span m="318143">BP,</span> <span m="318451">so</span>
  <span m="318758">it</span> <span m="319066">would</span> <span m="319374">not</span>
  <span m="319682">be</span> <span m="319990">able</span> <span m="320298">to</span>
  <span m="320606">rely</span> <span m="320914">on</span> <span m="321222">the</span>
  <span m="321530">fact</span> <span m="322032">that</span> <span m="322535">it's</span>
  <span m="323037">first</span> <span m="323540">argument</span> <span m="324042">is</span>
  <span m="324545">located</span> <span m="325047">at</span> <span m="325550">location</span>
  <span m="326052">BP-12,</span> <span m="326555">for</span> <span m="327057">example.</span></p><p><span
  m="327560">Finally,</span> <span m="327996">we</span> <span m="328433">restore</span>
  <span m="328870">the</span> <span m="329307">LP</span> <span m="329744">register</span>
  <span m="330181">and</span> <span m="330618">JMP</span> <span m="331055">to</span>
  <span m="331491">the</span> <span m="331928">location</span> <span m="332365">of</span>
  <span m="332802">the</span> <span m="333239">restored</span> <span m="333676">LP</span>
  <span m="334113">register.</span></p><p><span m="334550">This</span> <span m="334875">is</span>
  <span m="335200">the</span> <span m="335525">return</span> <span m="335851">address,</span>
  <span m="336176">so</span> <span m="336501">by</span> <span m="336827">jumping</span>
  <span m="337152">to</span> <span m="337477">LP,</span> <span m="337802">we</span>
  <span m="338128">return</span> <span m="338453">from</span> <span m="338778">our</span>
  <span m="339104">procedure</span> <span m="339429">call</span> <span m="339754">and</span>
  <span m="340080">are</span> <span m="340432">now</span> <span m="340785">ready</span>
  <span m="341138">to</span> <span m="341490">execute</span> <span m="341843">the</span>
  <span m="342196">next</span> <span m="342549">instruction</span> <span m="342901">at</span>
  <span m="343254">label</span> <span m="343607">b.</span></p><p><span m="343960">Now</span>
  <span m="344337">let's</span> <span m="344715">get</span> <span m="345093">back</span>
  <span m="345471">to</span> <span m="345849">our</span> <span m="346227">original</span>
  <span m="346605">procedure</span> <span m="346982">and</span> <span m="347360">its</span>
  <span m="347738">translation</span> <span m="348116">to</span> <span m="348494">beta</span>
  <span m="348872">assembly.</span></p><p><span m="349250">We</span> <span m="349570">will</span>
  <span m="349891">now</span> <span m="350211">try</span> <span m="350532">to</span>
  <span m="350853">understand</span> <span m="351173">what</span> <span m="351494">this</span>
  <span m="351815">mystery</span> <span m="352135">function</span> <span m="352456">is</span>
  <span m="352776">actually</span> <span m="353097">doing</span> <span m="353418">by</span>
  <span m="353738">examining</span> <span m="354059">the</span> <span m="354380">remaining</span>
  <span m="355051">sections</span> <span m="355722">of</span> <span m="356393">our</span>
  <span m="357065">assembly</span> <span m="357736">code</span> <span m="358407">highlighted</span>
  <span m="359078">here.</span></p><p><span m="359750">Let's</span> <span m="360204">zoom</span>
  <span m="360659">into</span> <span m="361113">the</span> <span m="361568">highlighted</span>
  <span m="362023">code.</span> <span m="362477">The</span> <span m="362932">LD</span>
  <span m="363386">instruction</span> <span m="363841">loads</span> <span m="364296">the</span>
  <span m="364750">first</span> <span m="365205">argument</span> <span m="365660">into</span>
  <span m="366100">register</span> <span m="366540">R0.</span> <span m="366980">Recall</span>
  <span m="367420">that</span> <span m="367860">the</span> <span m="368300">first</span>
  <span m="368740">argument</span> <span m="369180">can</span> <span m="369620">always</span>
  <span m="370060">be</span> <span m="370478">found</span> <span m="370896">at</span>
  <span m="371315">location</span> <span m="371733">BP</span> <span m="372151">&ndash;</span>
  <span m="372570">12,</span> <span m="372988">or</span> <span m="373406">in</span>
  <span m="373825">other</span> <span m="374243">words,</span> <span m="374661">3</span>
  <span m="375080">words</span> <span m="375498">before</span> <span m="375916">the</span>
  <span m="376335">current</span> <span m="376753">BP</span> <span m="377171">register.</span></p><p><span
  m="377590">This</span> <span m="378127">means</span> <span m="378664">that</span>
  <span m="379201">the</span> <span m="379738">value</span> <span m="380275">x</span>
  <span m="380812">is</span> <span m="381349">loaded</span> <span m="381886">into</span>
  <span m="382423">R0.</span></p><p><span m="382960">Next</span> <span m="383316">we</span>
  <span m="383672">perform</span> <span m="384029">a</span> <span m="384385">binary</span>
  <span m="384742">AND</span> <span m="385098">operation</span> <span m="385455">between</span>
  <span m="385811">R0</span> <span m="386168">and</span> <span m="386524">the</span>
  <span m="386881">constant</span> <span m="387237">5,</span> <span m="387594">and</span>
  <span m="387950">store</span> <span m="388307">the</span> <span m="388663">result</span>
  <span m="389020">of</span> <span m="389470">that</span> <span m="389921">operation</span>
  <span m="390372">into</span> <span m="390822">register</span> <span m="391273">R1.</span>
  <span m="391724">Note</span> <span m="392175">that</span> <span m="392625">its</span>
  <span m="393076">okay</span> <span m="393527">to</span> <span m="393977">overwrite</span>
  <span m="394428">R1</span> <span m="394879">because</span> <span m="395330">the</span>
  <span m="395705">entry</span> <span m="396080">sequence</span> <span m="396455">already</span>
  <span m="396830">saved</span> <span m="397205">a</span> <span m="397580">copy</span>
  <span m="397955">of</span> <span m="398330">the</span> <span m="398705">original</span>
  <span m="399080">R1</span> <span m="399455">onto</span> <span m="399830">the</span>
  <span m="400205">stack.</span></p><p><span m="400580">Also,</span> <span m="401023">note</span>
  <span m="401467">that</span> <span m="401910">overwriting</span> <span m="402354">R0</span>
  <span m="402797">is</span> <span m="403241">considered</span> <span m="403685">fine</span>
  <span m="404128">because</span> <span m="404572">we</span> <span m="405015">ultimately</span>
  <span m="405459">expect</span> <span m="405902">the</span> <span m="406346">result</span>
  <span m="406790">to</span> <span m="407304">be</span> <span m="407819">returned</span>
  <span m="408334">in</span> <span m="408848">R0,</span> <span m="409363">so</span>
  <span m="409878">there</span> <span m="410392">is</span> <span m="410907">no</span>
  <span m="411422">expectation</span> <span m="411937">of</span> <span m="412451">maintaining</span>
  <span m="412966">the</span> <span m="413481">original</span> <span m="413995">value</span>
  <span m="414510">of</span> <span m="415025">R0.</span></p><p><span m="415540">Looking</span>
  <span m="415811">back</span> <span m="416082">at</span> <span m="416353">the</span>
  <span m="416624">c</span> <span m="416895">code</span> <span m="417166">of</span>
  <span m="417437">our</span> <span m="417708">function,</span> <span m="417979">we</span>
  <span m="418250">see</span> <span m="418521">that</span> <span m="418792">the</span>
  <span m="419063">bitwise</span> <span m="419334">AND</span> <span m="419605">of</span>
  <span m="419876">x</span> <span m="420147">and</span> <span m="420418">5</span>
  <span m="420689">is</span> <span m="420960">stored</span> <span m="421454">into</span>
  <span m="421949">a</span> <span m="422444">local</span> <span m="422938">variable</span>
  <span m="423433">named</span> <span m="423928">a.</span> <span m="424423">In</span>
  <span m="424917">our</span> <span m="425412">entry</span> <span m="425907">sequence,</span>
  <span m="426402">we</span> <span m="426896">allocated</span> <span m="427391">1</span>
  <span m="427886">word</span> <span m="428381">on</span> <span m="428694">the</span>
  <span m="429007">stack</span> <span m="429320">for</span> <span m="429633">our</span>
  <span m="429946">local</span> <span m="430259">variables.</span> <span m="430572">That</span>
  <span m="430885">is</span> <span m="431198">where</span> <span m="431511">we</span>
  <span m="431824">want</span> <span m="432137">to</span> <span m="432450">store</span>
  <span m="432763">this</span> <span m="433076">intermediate</span> <span m="433390">result.</span>
  <span m="433736">The</span> <span m="434082">address</span> <span m="434428">of</span>
  <span m="434774">this</span> <span m="435120">location</span> <span m="435466">is</span>
  <span m="435812">equal</span> <span m="436158">to</span> <span m="436504">the</span>
  <span m="436850">contents</span> <span m="437390">of</span> <span m="437930">the</span>
  <span m="438470">BP</span> <span m="439010">register.</span> <span m="439550">Since</span>
  <span m="440090">the</span> <span m="440630">destination</span> <span m="441170">of</span>
  <span m="441710">a</span> <span m="442250">store</span> <span m="442790">operation</span>
  <span m="443330">is</span> <span m="443693">determined</span> <span m="444057">by</span>
  <span m="444421">adding</span> <span m="444785">the</span> <span m="445148">contents</span>
  <span m="445512">of</span> <span m="445876">the</span> <span m="446240">last</span>
  <span m="446603">register</span> <span m="446967">in</span> <span m="447331">the</span>
  <span m="447695">instruction</span> <span m="448058">to</span> <span m="448422">the</span>
  <span m="448786">constant,</span> <span m="449150">the</span> <span m="449568">destination</span>
  <span m="449986">of</span> <span m="450405">this</span> <span m="450823">store</span>
  <span m="451242">operation</span> <span m="451660">is</span> <span m="452079">the</span>
  <span m="452497">value</span> <span m="452916">of</span> <span m="453334">BP</span>
  <span m="453753">+</span> <span m="454171">0.</span></p><p><span m="454590">So</span>
  <span m="455040">as</span> <span m="455491">expected,</span> <span m="455941">variable</span>
  <span m="456392">a</span> <span m="456843">is</span> <span m="457293">stored</span>
  <span m="457744">at</span> <span m="458195">the</span> <span m="458645">location</span>
  <span m="459096">pointed</span> <span m="459546">to</span> <span m="459997">by</span>
  <span m="460448">the</span> <span m="460898">BP</span> <span m="461349">register.</span></p><p><span
  m="461800">Now</span> <span m="462127">we</span> <span m="462454">check</span> <span
  m="462781">if</span> <span m="463108">x</span> <span m="463435">equals</span> <span
  m="463762">0</span> <span m="464089">and</span> <span m="464416">if</span> <span
  m="464743">so</span> <span m="465070">we</span> <span m="465397">want</span> <span
  m="465724">to</span> <span m="466051">return</span> <span m="466378">the</span>
  <span m="466705">value</span> <span m="467032">0.</span></p><p><span m="467360">This</span>
  <span m="467701">is</span> <span m="468042">achieved</span> <span m="468383">in</span>
  <span m="468724">beta</span> <span m="469065">assembly</span> <span m="469406">by</span>
  <span m="469747">checking</span> <span m="470088">if</span> <span m="470429">R0</span>
  <span m="470770">is</span> <span m="471111">equal</span> <span m="471452">to</span>
  <span m="471793">0</span> <span m="472134">since</span> <span m="472475">R0</span>
  <span m="472816">was</span> <span m="473157">loaded</span> <span m="473498">with</span>
  <span m="473840">the</span> <span m="474231">value</span> <span m="474623">of</span>
  <span m="475015">x</span> <span m="475407">by</span> <span m="475799">the</span>
  <span m="476191">LD</span> <span m="476583">operation.</span> <span m="476975">The</span>
  <span m="477366">BEQ</span> <span m="477758">operation</span> <span m="478150">checks</span>
  <span m="478542">whether</span> <span m="478934">or</span> <span m="479326">not</span>
  <span m="479718">this</span> <span m="480110">condition</span> <span m="480520">holds</span>
  <span m="480931">and</span> <span m="481342">if</span> <span m="481752">so,</span>
  <span m="482163">it</span> <span m="482574">branches</span> <span m="482984">to</span>
  <span m="483395">label</span> <span m="483806">bye</span> <span m="484216">which</span>
  <span m="484627">is</span> <span m="485038">our</span> <span m="485448">exit</span>
  <span m="485859">sequence.</span></p><p><span m="486270">In</span> <span m="486660">that</span>
  <span m="487050">situation,</span> <span m="487440">we</span> <span m="487830">just</span>
  <span m="488220">saw</span> <span m="488610">that</span> <span m="489000">R0</span>
  <span m="489390">=</span> <span m="489780">0,</span> <span m="490170">so</span>
  <span m="490560">R0</span> <span m="490950">already</span> <span m="491340">contains</span>
  <span m="491730">the</span> <span m="492120">correct</span> <span m="492510">return</span>
  <span m="492900">value</span> <span m="493456">and</span> <span m="494012">we</span>
  <span m="494568">are</span> <span m="495124">ready</span> <span m="495680">to</span>
  <span m="496236">execute</span> <span m="496792">our</span> <span m="497348">return</span>
  <span m="497904">sequence.</span></p><p><span m="498460">If</span> <span m="498814">x</span>
  <span m="499169">is</span> <span m="499524">not</span> <span m="499878">equal</span>
  <span m="500233">to</span> <span m="500588">0,</span> <span m="500942">then</span>
  <span m="501297">we</span> <span m="501652">perform</span> <span m="502006">the</span>
  <span m="502361">instructions</span> <span m="502716">after</span> <span m="503070">label</span>
  <span m="503425">xx.</span></p><p><span m="503780">By</span> <span m="504175">figuring</span>
  <span m="504570">out</span> <span m="504965">what</span> <span m="505360">these</span>
  <span m="505755">instructions</span> <span m="506150">do,</span> <span m="506545">we</span>
  <span m="506940">can</span> <span m="507335">identify</span> <span m="507730">the</span>
  <span m="508125">value</span> <span m="508520">of</span> <span m="508915">our</span>
  <span m="509310">mystery</span> <span m="509705">function</span> <span m="510100">labeled</span>
  <span m="510856">?????.</span> <span m="511613">We</span> <span m="512369">begin</span>
  <span m="513126">by</span> <span m="513882">decrementing</span> <span m="514639">R0</span>
  <span m="515395">by</span> <span m="516152">1.</span></p><p><span m="516909">This</span>
  <span m="517339">means</span> <span m="517769">that</span> <span m="518199">R0</span>
  <span m="518629">will</span> <span m="519059">be</span> <span m="519489">updated</span>
  <span m="519919">to</span> <span m="520349">hold</span> <span m="520779">x-1.</span></p><p><span
  m="521209">We</span> <span m="521520">then</span> <span m="521832">push</span> <span
  m="522144">this</span> <span m="522456">value</span> <span m="522768">onto</span>
  <span m="523080">the</span> <span m="523392">stack</span> <span m="523704">and</span>
  <span m="524015">make</span> <span m="524327">a</span> <span m="524639">recursive</span>
  <span m="524951">call</span> <span m="525263">to</span> <span m="525575">procedure</span>
  <span m="525887">f.</span></p><p><span m="526199">In</span> <span m="526554">other</span>
  <span m="526909">words,</span> <span m="527264">we</span> <span m="527619">call</span>
  <span m="527974">f</span> <span m="528329">again</span> <span m="528684">with</span>
  <span m="529039">a</span> <span m="529394">new</span> <span m="529749">argument</span>
  <span m="530104">which</span> <span m="530459">is</span> <span m="530814">equal</span>
  <span m="531169">to</span> <span m="531524">x-1.</span></p><p><span m="531879">So</span>
  <span m="532356">far</span> <span m="532834">we</span> <span m="533312">know</span>
  <span m="533789">that</span> <span m="534267">our</span> <span m="534745">mystery</span>
  <span m="535222">function</span> <span m="535700">will</span> <span m="536178">contain</span>
  <span m="536655">the</span> <span m="537133">term</span> <span m="537611">f(x-1).</span></p><p><span
  m="538089">We</span> <span m="538540">also</span> <span m="538992">see</span> <span
  m="539444">that</span> <span m="539896">LP</span> <span m="540347">gets</span> <span
  m="540799">updated</span> <span m="541251">with</span> <span m="541703">the</span>
  <span m="542154">new</span> <span m="542606">return</span> <span m="543058">address</span>
  <span m="543510">which</span> <span m="543961">is</span> <span m="544413">yy</span>
  <span m="544865">+</span> <span m="545317">4.</span></p><p><span m="545769">So</span>
  <span m="546116">just</span> <span m="546464">before</span> <span m="546812">our</span>
  <span m="547159">recursive</span> <span m="547507">call</span> <span m="547855">to</span>
  <span m="548202">f</span> <span m="548550">with</span> <span m="548898">the</span>
  <span m="549246">new</span> <span m="549593">argument</span> <span m="549941">x-1,</span>
  <span m="550289">our</span> <span m="550636">stack</span> <span m="550984">looks</span>
  <span m="551332">like</span> <span m="551680">this.</span> <span m="552451">After</span>
  <span m="553222">the</span> <span m="553993">procedure</span> <span m="554765">entry</span>
  <span m="555536">sequence</span> <span m="556307">is</span> <span m="557078">executed</span>
  <span m="557850">in</span> <span m="558256">the</span> <span m="558662">first</span>
  <span m="559068">recursive</span> <span m="559474">call,</span> <span m="559880">our</span>
  <span m="560286">stack</span> <span m="560692">looks</span> <span m="561098">like</span>
  <span m="561504">this.</span></p><p><span m="561910">Note</span> <span m="562213">that</span>
  <span m="562516">this</span> <span m="562819">time</span> <span m="563122">the</span>
  <span m="563425">saved</span> <span m="563728">LP</span> <span m="564032">is</span>
  <span m="564335">yy</span> <span m="564638">+</span> <span m="564941">4</span> <span
  m="565244">because</span> <span m="565547">that</span> <span m="565851">is</span>
  <span m="566154">our</span> <span m="566457">return</span> <span m="566760">address</span>
  <span m="567063">for</span> <span m="567366">the</span> <span m="567670">recursive</span>
  <span m="568115">procedure</span> <span m="568561">call.</span> <span m="569007">The</span>
  <span m="569453">previous</span> <span m="569898">BP</span> <span m="570344">points</span>
  <span m="570790">to</span> <span m="571236">where</span> <span m="571681">the</span>
  <span m="572127">BP</span> <span m="572573">was</span> <span m="573019">pointing</span>
  <span m="573382">to</span> <span m="573745">in</span> <span m="574108">the</span>
  <span m="574471">original</span> <span m="574834">call</span> <span m="575197">to</span>
  <span m="575560">f.</span> <span m="575924">Another</span> <span m="576287">term</span>
  <span m="576650">for</span> <span m="577013">this</span> <span m="577376">group</span>
  <span m="577739">of</span> <span m="578102">stack</span> <span m="578465">elements</span>
  <span m="578829">is</span> <span m="579290">the</span> <span m="579752">activation</span>
  <span m="580214">record.</span> <span m="580676">In</span> <span m="581138">this</span>
  <span m="581600">example,</span> <span m="582062">each</span> <span m="582524">activation</span>
  <span m="582986">record</span> <span m="583448">consists</span> <span m="583910">of</span>
  <span m="584350">5</span> <span m="584791">elements.</span> <span m="585232">These</span>
  <span m="585673">are</span> <span m="586113">the</span> <span m="586554">argument</span>
  <span m="586995">to</span> <span m="587436">f,</span> <span m="587876">the</span>
  <span m="588317">saved</span> <span m="588758">LP,</span> <span m="589199">the</span>
  <span m="589713">saved</span> <span m="590227">BP,</span> <span m="590741">the</span>
  <span m="591255">local</span> <span m="591769">variable,</span> <span m="592283">and</span>
  <span m="592797">the</span> <span m="593311">saved</span> <span m="593825">R1.</span></p><p><span
  m="594339">Each</span> <span m="594769">time</span> <span m="595200">that</span>
  <span m="595631">f</span> <span m="596061">is</span> <span m="596492">called</span>
  <span m="596923">recursively</span> <span m="597353">another</span> <span m="597784">activation</span>
  <span m="598215">record</span> <span m="598645">will</span> <span m="599076">be</span>
  <span m="599507">added</span> <span m="599937">to</span> <span m="600368">the</span>
  <span m="600799">stack.</span></p><p><span m="601230">When</span> <span m="601482">we</span>
  <span m="601734">finally</span> <span m="601986">return</span> <span m="602238">from</span>
  <span m="602490">all</span> <span m="602742">of</span> <span m="602994">these</span>
  <span m="603246">recursive</span> <span m="603498">calls,</span> <span m="603750">we</span>
  <span m="604002">are</span> <span m="604254">back</span> <span m="604506">to</span>
  <span m="604758">a</span> <span m="605010">stack</span> <span m="605262">that</span>
  <span m="605514">looks</span> <span m="605766">like</span> <span m="606019">this</span>
  <span m="606374">with</span> <span m="606729">a</span> <span m="607085">single</span>
  <span m="607440">activation</span> <span m="607796">record</span> <span m="608151">left</span>
  <span m="608506">on</span> <span m="608862">the</span> <span m="609217">stack</span>
  <span m="609573">plus</span> <span m="609928">the</span> <span m="610283">first</span>
  <span m="610639">argument</span> <span m="610994">with</span> <span m="611350">which</span>
  <span m="611822">the</span> <span m="612295">recursive</span> <span m="612768">call</span>
  <span m="613240">was</span> <span m="613713">made.</span> <span m="614186">The</span>
  <span m="614659">DEALLOCATE(1)</span> <span m="615131">instruction</span> <span
  m="615604">then</span> <span m="616077">removes</span> <span m="616550">this</span>
  <span m="617020">argument</span> <span m="617490">from</span> <span m="617960">the</span>
  <span m="618430">stack.</span> <span m="618900">So</span> <span m="619370">the</span>
  <span m="619840">SP</span> <span m="620310">is</span> <span m="620780">now</span>
  <span m="621250">pointing</span> <span m="621720">to</span> <span m="622190">the</span>
  <span m="622660">location</span> <span m="623130">where</span> <span m="623618">we</span>
  <span m="624107">previously</span> <span m="624595">pushed</span> <span m="625084">the</span>
  <span m="625573">argument</span> <span m="626061">x-1.</span> <span m="626550">R0</span>
  <span m="627038">holds</span> <span m="627527">the</span> <span m="628016">return</span>
  <span m="628504">value</span> <span m="628993">from</span> <span m="629481">the</span>
  <span m="629970">recursive</span> <span m="630459">call</span> <span m="630904">to</span>
  <span m="631349">f</span> <span m="631794">which</span> <span m="632240">is</span>
  <span m="632685">the</span> <span m="633130">value</span> <span m="633576">of</span>
  <span m="634021">f(x-1).</span> <span m="634466">Now,</span> <span m="634912">we</span>
  <span m="635357">execute</span> <span m="635802">a</span> <span m="636248">LD</span>
  <span m="636693">into</span> <span m="637138">register</span> <span m="637584">R1</span>
  <span m="638029">of</span> <span m="638474">the</span> <span m="638920">address</span>
  <span m="639345">that</span> <span m="639771">is</span> <span m="640197">the</span>
  <span m="640623">contents</span> <span m="641049">of</span> <span m="641475">register</span>
  <span m="641901">BP</span> <span m="642327">+</span> <span m="642753">0.</span></p><p><span
  m="643179">This</span> <span m="643531">value</span> <span m="643883">is</span>
  <span m="644235">a.</span> <span m="644587">We</span> <span m="644940">then</span>
  <span m="645292">ADD</span> <span m="645644">R1</span> <span m="645996">to</span>
  <span m="646348">R0</span> <span m="646701">to</span> <span m="647053">produce</span>
  <span m="647405">our</span> <span m="647757">final</span> <span m="648110">result</span>
  <span m="648632">in</span> <span m="649155">R0.</span> <span m="649678">R0</span>
  <span m="650201">is</span> <span m="650723">now</span> <span m="651246">equal</span>
  <span m="651769">to</span> <span m="652292">a</span> <span m="652815">+</span> <span
  m="653337">f(x-1),</span> <span m="653860">so</span> <span m="654383">we</span>
  <span m="654906">have</span> <span m="655429">discovered</span> <span m="656139">that</span>
  <span m="656849">our</span> <span m="657559">mystery</span> <span m="658269">function</span>
  <span m="658979">is</span> <span m="659689">a</span> <span m="660399">+</span> <span
  m="661109">f(x-1).</span></p><p><span m="661819">Before</span> <span m="662117">we</span>
  <span m="662416">continue</span> <span m="662715">with</span> <span m="663013">analyzing</span>
  <span m="663312">a</span> <span m="663611">stack</span> <span m="663910">trace</span>
  <span m="664208">from</span> <span m="664507">this</span> <span m="664806">problem,</span>
  <span m="665105">let's</span> <span m="665403">answer</span> <span m="665702">a</span>
  <span m="666001">few</span> <span m="666300">simpler</span> <span m="666709">questions.</span>
  <span m="667119">The</span> <span m="667529">first</span> <span m="667939">question</span>
  <span m="668349">is</span> <span m="668759">whether</span> <span m="669169">or</span>
  <span m="669579">not</span> <span m="669989">variable</span> <span m="670399">a,</span>
  <span m="670702">from</span> <span m="671006">the</span> <span m="671310">statement</span>
  <span m="671614">a</span> <span m="671918">=</span> <span m="672221">x</span> <span
  m="672525">&amp;</span> <span m="672829">5,</span> <span m="673133">is</span> <span
  m="673437">stored</span> <span m="673740">on</span> <span m="674044">the</span>
  <span m="674348">stack</span> <span m="674652">and</span> <span m="674956">if</span>
  <span m="675259">so</span> <span m="675563">where</span> <span m="675867">is</span>
  <span m="676171">it</span> <span m="676475">stored</span> <span m="676779">relative</span>
  <span m="677232">to</span> <span m="677685">the</span> <span m="678138">BP</span>
  <span m="678591">register.</span> <span m="679044">Earlier</span> <span m="679497">we</span>
  <span m="679951">saw</span> <span m="680404">that</span> <span m="680857">our</span>
  <span m="681310">assembly</span> <span m="681763">program</span> <span m="682216">allocates</span>
  <span m="682670">space</span> <span m="683020">for</span> <span m="683371">one</span>
  <span m="683721">local</span> <span m="684072">variable</span> <span m="684422">on</span>
  <span m="684773">the</span> <span m="685123">stack.</span> <span m="685474">It</span>
  <span m="685825">then</span> <span m="686175">stores</span> <span m="686526">R1,</span>
  <span m="686876">which</span> <span m="687227">holds</span> <span m="687577">the</span>
  <span m="687928">result</span> <span m="688279">of</span> <span m="688713">performing</span>
  <span m="689148">a</span> <span m="689583">binary</span> <span m="690017">ANDC</span>
  <span m="690452">between</span> <span m="690887">x</span> <span m="691322">and</span>
  <span m="691756">the</span> <span m="692191">constant</span> <span m="692626">5,</span>
  <span m="693061">into</span> <span m="693495">the</span> <span m="693930">location</span>
  <span m="694365">pointed</span> <span m="694800">to</span> <span m="695265">by</span>
  <span m="695730">the</span> <span m="696195">BP</span> <span m="696661">register,</span>
  <span m="697126">as</span> <span m="697591">shown</span> <span m="698056">here.</span>
  <span m="698522">Next,</span> <span m="698987">we</span> <span m="699452">want</span>
  <span m="699917">to</span> <span m="700383">translate</span> <span m="700848">the</span>
  <span m="701313">instruction</span> <span m="701779">at</span> <span m="702497">label</span>
  <span m="703216">yy</span> <span m="703935">into</span> <span m="704653">its</span>
  <span m="705372">binary</span> <span m="706091">representation.</span> <span m="706809">The</span>
  <span m="707528">instruction</span> <span m="708247">at</span> <span m="708965">label</span>
  <span m="709684">yy</span> <span m="710403">is</span> <span m="711121">BR(f,</span>
  <span m="711840">LP).</span></p><p><span m="712559">This</span> <span m="713225">instruction</span>
  <span m="713891">is</span> <span m="714557">actually</span> <span m="715223">a</span>
  <span m="715890">macro</span> <span m="716556">that</span> <span m="717222">translates</span>
  <span m="717888">to</span> <span m="718555">a</span> <span m="719221">BEQ(R31,</span>
  <span m="719887">f,</span> <span m="720553">LP).</span></p><p><span m="721220">Note</span>
  <span m="721765">that</span> <span m="722310">because</span> <span m="722855">R31</span>
  <span m="723400">always</span> <span m="723945">equals</span> <span m="724490">0,</span>
  <span m="725035">this</span> <span m="725580">branch</span> <span m="726125">is</span>
  <span m="726670">always</span> <span m="727215">taken.</span></p><p><span m="727760">The</span>
  <span m="728225">format</span> <span m="728691">of</span> <span m="729156">the</span>
  <span m="729622">binary</span> <span m="730088">representation</span> <span m="730553">for</span>
  <span m="731019">this</span> <span m="731485">instruction</span> <span m="731950">is</span>
  <span m="732416">a</span> <span m="732882">6-bit</span> <span m="733347">opcode,</span>
  <span m="733813">followed</span> <span m="734279">by</span> <span m="734696">a</span>
  <span m="735114">5</span> <span m="735531">bit</span> <span m="735949">Rc</span>
  <span m="736367">identifier,</span> <span m="736784">followed</span> <span m="737202">by</span>
  <span m="737620">another</span> <span m="738037">5</span> <span m="738455">bits</span>
  <span m="738873">which</span> <span m="739290">specify</span> <span m="739708">Ra,</span>
  <span m="740126">and</span> <span m="740543">then</span> <span m="740961">followed</span>
  <span m="741379">by</span> <span m="741977">a</span> <span m="742575">16</span>
  <span m="743173">bit</span> <span m="743771">literal.</span> <span m="744369">The</span>
  <span m="744968">opcode</span> <span m="745566">for</span> <span m="746164">BEQ</span>
  <span m="746762">is</span> <span m="747360">011100.</span></p><p><span m="747959">Rc</span>
  <span m="748669">=</span> <span m="749380">LP</span> <span m="750091">which</span>
  <span m="750802">is</span> <span m="751512">register</span> <span m="752223">R28.</span>
  <span m="752934">The</span> <span m="753645">5-bit</span> <span m="754356">encoding</span>
  <span m="755066">of</span> <span m="755777">28</span> <span m="756488">is</span>
  <span m="757199">11100.</span></p><p><span m="757910">Ra</span> <span m="758483">is</span>
  <span m="759056">R31</span> <span m="759629">whose</span> <span m="760202">encoding</span>
  <span m="760775">is</span> <span m="761348">11111.</span> <span m="761921">Now,</span>
  <span m="762494">we</span> <span m="763067">need</span> <span m="763640">to</span>
  <span m="764213">determine</span> <span m="764786">the</span> <span m="765359">value</span>
  <span m="765932">of</span> <span m="766505">the</span> <span m="767079">literal</span>
  <span m="767514">in</span> <span m="767949">this</span> <span m="768385">instruction.</span>
  <span m="768820">The</span> <span m="769256">literal</span> <span m="769691">in</span>
  <span m="770127">a</span> <span m="770562">branch</span> <span m="770998">instruction</span>
  <span m="771433">stores</span> <span m="771869">the</span> <span m="772275">offset</span>
  <span m="772681">measured</span> <span m="773087">in</span> <span m="773493">words</span>
  <span m="773899">from</span> <span m="774305">the</span> <span m="774711">instruction</span>
  <span m="775117">immediately</span> <span m="775523">following</span> <span m="775929">the</span>
  <span m="776335">branch,</span> <span m="776741">to</span> <span m="777147">the</span>
  <span m="777553">destination</span> <span m="777959">address.</span> <span m="778436">Looking</span>
  <span m="778914">at</span> <span m="779392">our</span> <span m="779870">assembly</span>
  <span m="780347">code</span> <span m="780825">for</span> <span m="781303">this</span>
  <span m="781781">function,</span> <span m="782259">we</span> <span m="782569">see</span>
  <span m="782879">that</span> <span m="783189">we</span> <span m="783499">want</span>
  <span m="783809">to</span> <span m="784119">count</span> <span m="784429">the</span>
  <span m="784739">number</span> <span m="785049">of</span> <span m="785359">words</span>
  <span m="785669">from</span> <span m="785979">the</span> <span m="786289">DEALLOCATE(1)</span>
  <span m="786599">instruction</span> <span m="786909">back</span> <span m="787220">to</span>
  <span m="787667">label</span> <span m="788114">f.</span> <span m="788562">Recall</span>
  <span m="789009">that</span> <span m="789457">the</span> <span m="789904">PUSH</span>
  <span m="790351">and</span> <span m="790799">POP</span> <span m="791246">macros</span>
  <span m="791694">are</span> <span m="792141">actually</span> <span m="792589">each</span>
  <span m="793010">made</span> <span m="793432">of</span> <span m="793853">up</span>
  <span m="794275">two</span> <span m="794696">instructions</span> <span m="795118">so</span>
  <span m="795539">each</span> <span m="795961">of</span> <span m="796382">those</span>
  <span m="796804">counts</span> <span m="797225">as</span> <span m="797647">2</span>
  <span m="798068">words.</span></p><p><span m="798490">Counting</span> <span m="798813">back,</span>
  <span m="799136">and</span> <span m="799459">accounting</span> <span m="799783">for</span>
  <span m="800106">the</span> <span m="800429">two</span> <span m="800752">instructions</span>
  <span m="801076">per</span> <span m="801399">push</span> <span m="801722">and</span>
  <span m="802045">pop,</span> <span m="802369">we</span> <span m="802692">see</span>
  <span m="803015">that</span> <span m="803339">we</span> <span m="803811">have</span>
  <span m="804283">to</span> <span m="804755">go</span> <span m="805227">back</span>
  <span m="805700">16</span> <span m="806172">instructions,</span> <span m="806644">so</span>
  <span m="807116">our</span> <span m="807589">literal</span> <span m="808061">is</span>
  <span m="808533">-16</span> <span m="809005">expressed</span> <span m="809477">as</span>
  <span m="809950">a</span> <span m="810422">16</span> <span m="810894">bit</span>
  <span m="811366">binary</span> <span m="811839">number.</span> <span m="812840">Positive</span>
  <span m="813841">16</span> <span m="814842">is</span> <span m="815843">0000</span>
  <span m="816844">0000</span> <span m="817845">0001</span> <span m="818846">0000,</span>
  <span m="819847">so</span> <span m="820848">-16</span> <span m="821850">is</span>
  <span m="822679">1111</span> <span m="823508">1111</span> <span m="824337">1111</span>
  <span m="825166">0000.</span> <span m="825995">Now,</span> <span m="826824">suppose</span>
  <span m="827654">that</span> <span m="828483">the</span> <span m="829312">function</span>
  <span m="830141">f</span> <span m="830970">is</span> <span m="831799">called</span>
  <span m="832629">from</span> <span m="832940">an</span> <span m="833251">external</span>
  <span m="833562">main</span> <span m="833873">program,</span> <span m="834184">and</span>
  <span m="834496">the</span> <span m="834807">machine</span> <span m="835118">is</span>
  <span m="835429">halted</span> <span m="835740">when</span> <span m="836051">a</span>
  <span m="836363">recursive</span> <span m="836674">call</span> <span m="836985">to</span>
  <span m="837296">f</span> <span m="837607">is</span> <span m="837918">about</span>
  <span m="838230">to</span> <span m="838806">execute</span> <span m="839382">the</span>
  <span m="839958">BEQ</span> <span m="840534">instruction</span> <span m="841110">tagged</span>
  <span m="841686">xx.</span> <span m="842262">The</span> <span m="842838">BP</span>
  <span m="843414">register</span> <span m="843990">of</span> <span m="844566">the</span>
  <span m="845142">halted</span> <span m="845718">machine</span> <span m="846294">contains</span>
  <span m="846870">0x174,</span> <span m="847426">and</span> <span m="847982">the</span>
  <span m="848538">hex</span> <span m="849094">contents</span> <span m="849650">of</span>
  <span m="850206">a</span> <span m="850763">region</span> <span m="851319">of</span>
  <span m="851875">memory</span> <span m="852431">are</span> <span m="852987">shown</span>
  <span m="853543">here.</span></p><p><span m="854100">The</span> <span m="854409">values</span>
  <span m="854718">on</span> <span m="855028">the</span> <span m="855337">left</span>
  <span m="855647">of</span> <span m="855956">the</span> <span m="856265">stack</span>
  <span m="856575">are</span> <span m="856884">the</span> <span m="857194">addresses</span>
  <span m="857503">of</span> <span m="857812">each</span> <span m="858122">location</span>
  <span m="858431">on</span> <span m="858741">the</span> <span m="859050">stack.</span></p><p><span
  m="859360">We</span> <span m="859815">first</span> <span m="860271">want</span>
  <span m="860727">to</span> <span m="861183">determine</span> <span m="861639">the</span>
  <span m="862095">current</span> <span m="862551">value</span> <span m="863007">of</span>
  <span m="863463">the</span> <span m="863919">SP,</span> <span m="864375">or</span>
  <span m="864831">stack</span> <span m="865287">pointer,</span> <span m="865743">register.</span></p><p><span
  m="866199">We</span> <span m="866489">were</span> <span m="866780">told</span> <span
  m="867070">that</span> <span m="867361">the</span> <span m="867652">machine</span>
  <span m="867942">is</span> <span m="868233">halted</span> <span m="868523">when</span>
  <span m="868814">a</span> <span m="869105">recursive</span> <span m="869395">call</span>
  <span m="869686">to</span> <span m="869976">f</span> <span m="870267">is</span>
  <span m="870558">about</span> <span m="870848">to</span> <span m="871139">execute</span>
  <span m="871430">the</span> <span m="872135">BEQ</span> <span m="872841">instruction</span>
  <span m="873546">tagged</span> <span m="874252">xx.</span> <span m="874958">And</span>
  <span m="875663">that</span> <span m="876369">the</span> <span m="877075">BP</span>
  <span m="877780">register</span> <span m="878486">was</span> <span m="879192">0x174</span>
  <span m="879897">at</span> <span m="880603">that</span> <span m="881309">point.</span>
  <span m="881693">We</span> <span m="882078">see</span> <span m="882462">that</span>
  <span m="882847">after</span> <span m="883232">the</span> <span m="883616">BP</span>
  <span m="884001">was</span> <span m="884386">updated</span> <span m="884770">to</span>
  <span m="885155">be</span> <span m="885540">equal</span> <span m="885944">to</span>
  <span m="886349">the</span> <span m="886754">SP</span> <span m="887159">in</span>
  <span m="887564">the</span> <span m="887969">MOVE</span> <span m="888374">operation,</span>
  <span m="888779">two</span> <span m="889184">additional</span> <span m="889589">entries</span>
  <span m="889994">were</span> <span m="890399">made</span> <span m="890804">on</span>
  <span m="891209">the</span> <span m="891614">stack.</span></p><p><span m="892019">The</span>
  <span m="892427">first</span> <span m="892836">was</span> <span m="893244">an</span>
  <span m="893653">ALLOCATE</span> <span m="894061">instruction</span> <span m="894470">which</span>
  <span m="894879">allocated</span> <span m="895287">space</span> <span m="895696">for</span>
  <span m="896104">one</span> <span m="896513">local</span> <span m="896921">variable,</span>
  <span m="897330">thus</span> <span m="897739">making</span> <span m="898267">the</span>
  <span m="898795">SP</span> <span m="899324">point</span> <span m="899852">to</span>
  <span m="900380">location</span> <span m="900909">0x178,</span> <span m="901437">and</span>
  <span m="901965">then</span> <span m="902494">PUSH(R1),</span> <span m="903022">which</span>
  <span m="903550">saves</span> <span m="904079">a</span> <span m="904607">copy</span>
  <span m="905135">of</span> <span m="905664">R1</span> <span m="906192">on</span>
  <span m="906721">the</span> <span m="907414">stack,</span> <span m="908108">thus</span>
  <span m="908802">moving</span> <span m="909495">the</span> <span m="910189">SP</span>
  <span m="910883">register</span> <span m="911576">one</span> <span m="912270">further</span>
  <span m="912964">location</span> <span m="913657">down</span> <span m="914351">to</span>
  <span m="915045">0x17C.</span></p><p><span m="915739">We</span> <span m="916073">now</span>
  <span m="916407">want</span> <span m="916741">to</span> <span m="917075">answer</span>
  <span m="917409">some</span> <span m="917744">questions</span> <span m="918078">about</span>
  <span m="918412">the</span> <span m="918746">stack</span> <span m="919080">trace</span>
  <span m="919414">itself</span> <span m="919749">to</span> <span m="920083">help</span>
  <span m="920417">us</span> <span m="920751">better</span> <span m="921085">understand</span>
  <span m="921420">its</span> <span m="921834">structure.</span> <span m="922249">We</span>
  <span m="922663">first</span> <span m="923078">want</span> <span m="923492">to</span>
  <span m="923907">determine</span> <span m="924321">the</span> <span m="924736">value</span>
  <span m="925150">of</span> <span m="925565">local</span> <span m="925980">variable</span>
  <span m="926430">a</span> <span m="926881">in</span> <span m="927331">the</span>
  <span m="927782">current</span> <span m="928232">stack</span> <span m="928683">frame.</span>
  <span m="929133">We</span> <span m="929584">know</span> <span m="930034">that</span>
  <span m="930485">a</span> <span m="930935">is</span> <span m="931386">stored</span>
  <span m="931836">at</span> <span m="932287">location</span> <span m="932737">BP</span>
  <span m="933188">+</span> <span m="933639">0.</span> <span m="934179">So</span>
  <span m="934719">a</span> <span m="935259">is</span> <span m="935799">the</span>
  <span m="936339">variable</span> <span m="936879">stored</span> <span m="937419">at</span>
  <span m="937959">address</span> <span m="938499">0x174,</span> <span m="939040">and</span>
  <span m="939408">that</span> <span m="939777">value</span> <span m="940145">is</span>
  <span m="940514">5.</span> <span m="940882">From</span> <span m="941251">here,</span>
  <span m="941619">we</span> <span m="941988">can</span> <span m="942356">label</span>
  <span m="942725">all</span> <span m="943093">the</span> <span m="943462">entries</span>
  <span m="943830">in</span> <span m="944199">the</span> <span m="944682">stack</span>
  <span m="945165">trace</span> <span m="945649">as</span> <span m="946132">follows.</span>
  <span m="946615">We</span> <span m="947099">saw</span> <span m="947582">earlier,</span>
  <span m="948065">that</span> <span m="948549">each</span> <span m="949032">activation</span>
  <span m="949515">record</span> <span m="949999">consists</span> <span m="950421">of</span>
  <span m="950843">5</span> <span m="951265">words,</span> <span m="951688">the</span>
  <span m="952110">argument</span> <span m="952532">x</span> <span m="952954">followed</span>
  <span m="953377">by</span> <span m="953799">the</span> <span m="954221">saved</span>
  <span m="954644">LP,</span> <span m="955066">the</span> <span m="955488">saved</span>
  <span m="955910">BP,</span> <span m="956333">the</span> <span m="956755">local</span>
  <span m="957177">variable,</span> <span m="957600">and</span> <span m="957973">the</span>
  <span m="958347">saved</span> <span m="958720">register</span> <span m="959094">R1.</span>
  <span m="959467">We</span> <span m="959841">can</span> <span m="960214">apply</span>
  <span m="960588">this</span> <span m="960961">structure</span> <span m="961335">to</span>
  <span m="961708">label</span> <span m="962082">our</span> <span m="962455">stack</span>
  <span m="962829">trace.</span> <span m="963267">Now</span> <span m="963706">that</span>
  <span m="964145">our</span> <span m="964584">stack</span> <span m="965023">trace</span>
  <span m="965462">is</span> <span m="965901">fully</span> <span m="966340">labeled</span>
  <span m="966779">we</span> <span m="967135">can</span> <span m="967492">take</span>
  <span m="967849">a</span> <span m="968205">closer</span> <span m="968562">look</span>
  <span m="968919">at</span> <span m="969276">the</span> <span m="969632">details</span>
  <span m="969989">of</span> <span m="970346">implementing</span> <span m="970703">procedures</span>
  <span m="971059">on</span> <span m="971416">the</span> <span m="971773">beta.</span></p><p><span
  m="972130">We</span> <span m="972457">begin</span> <span m="972785">by</span> <span
  m="973113">looking</span> <span m="973441">at</span> <span m="973769">the</span>
  <span m="974097">multiple</span> <span m="974425">LP</span> <span m="974753">values</span>
  <span m="975081">that</span> <span m="975409">were</span> <span m="975737">stored</span>
  <span m="976065">on</span> <span m="976393">the</span> <span m="976721">stack.</span></p><p><span
  m="977049">Note</span> <span m="977534">that</span> <span m="978020">the</span>
  <span m="978506">first</span> <span m="978992">one</span> <span m="979478">at</span>
  <span m="979964">address</span> <span m="980450">0x144</span> <span m="980936">has</span>
  <span m="981421">a</span> <span m="981907">value</span> <span m="982393">of</span>
  <span m="982879">0x5C</span> <span m="983365">whereas</span> <span m="983851">the</span>
  <span m="984337">following</span> <span m="984823">two</span> <span m="985309">have</span>
  <span m="985731">a</span> <span m="986153">value</span> <span m="986575">of</span>
  <span m="986998">0xA4.</span> <span m="987420">This</span> <span m="987842">occurs</span>
  <span m="988265">because</span> <span m="988687">the</span> <span m="989109">LP</span>
  <span m="989532">value</span> <span m="989954">stored</span> <span m="990376">at</span>
  <span m="990799">address</span> <span m="991296">0x144</span> <span m="991793">is</span>
  <span m="992290">the</span> <span m="992787">return</span> <span m="993284">address</span>
  <span m="993781">from</span> <span m="994279">the</span> <span m="994776">main</span>
  <span m="995273">procedure</span> <span m="995770">that</span> <span m="996267">originally</span>
  <span m="996764">called</span> <span m="997261">procedure</span> <span m="997759">f,</span>
  <span m="998155">whereas</span> <span m="998552">the</span> <span m="998948">following</span>
  <span m="999345">two</span> <span m="999741">LP</span> <span m="1000138">values</span>
  <span m="1000534">are</span> <span m="1000931">the</span> <span m="1001327">return</span>
  <span m="1001724">addresses</span> <span m="1002120">from</span> <span m="1002517">recursive</span>
  <span m="1002913">calls</span> <span m="1003310">to</span> <span m="1003705">f</span>
  <span m="1004101">made</span> <span m="1004496">from</span> <span m="1004892">within</span>
  <span m="1005287">the</span> <span m="1005683">f</span> <span m="1006078">function</span>
  <span m="1006474">itself.</span> <span m="1006870">Using</span> <span m="1007265">this</span>
  <span m="1007661">information</span> <span m="1008056">you</span> <span m="1008452">can</span>
  <span m="1008847">now</span> <span m="1009243">answer</span> <span m="1009639">the</span>
  <span m="1009999">question:</span> <span m="1010359">What</span> <span m="1010719">is</span>
  <span m="1011079">the</span> <span m="1011439">address</span> <span m="1011799">of</span>
  <span m="1012159">the</span> <span m="1012519">BR</span> <span m="1012879">instruction</span>
  <span m="1013239">that</span> <span m="1013599">made</span> <span m="1013959">the</span>
  <span m="1014319">original</span> <span m="1014679">call</span> <span m="1015039">to</span>
  <span m="1015399">f</span> <span m="1015777">from</span> <span m="1016155">the</span>
  <span m="1016533">external</span> <span m="1016911">main</span> <span m="1017289">program?</span>
  <span m="1017667">Recall</span> <span m="1018045">that</span> <span m="1018423">the</span>
  <span m="1018801">value</span> <span m="1019179">stored</span> <span m="1019557">in</span>
  <span m="1019935">the</span> <span m="1020313">LP</span> <span m="1020691">register</span>
  <span m="1021069">is</span> <span m="1021409">actually</span> <span m="1021750">the</span>
  <span m="1022091">return</span> <span m="1022431">address</span> <span m="1022772">which</span>
  <span m="1023113">is</span> <span m="1023454">the</span> <span m="1023794">address</span>
  <span m="1024135">of</span> <span m="1024476">the</span> <span m="1024816">instruction</span>
  <span m="1025157">immediately</span> <span m="1025498">following</span> <span m="1025839">the</span>
  <span m="1026435">branch</span> <span m="1027032">instruction.</span> <span m="1027629">So</span>
  <span m="1028226">if</span> <span m="1028822">the</span> <span m="1029419">original</span>
  <span m="1030016">LP</span> <span m="1030613">value</span> <span m="1031209">was</span>
  <span m="1031806">0x5C,</span> <span m="1032403">that</span> <span m="1033000">means</span>
  <span m="1033590">that</span> <span m="1034181">the</span> <span m="1034772">address</span>
  <span m="1035363">of</span> <span m="1035954">the</span> <span m="1036545">branch</span>
  <span m="1037136">instruction</span> <span m="1037727">was</span> <span m="1038318">0x58.</span></p><p><span
  m="1038909">We</span> <span m="1039245">can</span> <span m="1039582">also</span>
  <span m="1039919">answer</span> <span m="1040255">the</span> <span m="1040592">question,</span>
  <span m="1040929">what</span> <span m="1041266">is</span> <span m="1041602">the</span>
  <span m="1041939">value</span> <span m="1042276">of</span> <span m="1042612">the</span>
  <span m="1042949">PC</span> <span m="1043286">when</span> <span m="1043623">the</span>
  <span m="1043959">program</span> <span m="1044296">is</span> <span m="1044633">halted.</span></p><p><span
  m="1044970">We</span> <span m="1045361">know</span> <span m="1045752">that</span>
  <span m="1046144">the</span> <span m="1046535">program</span> <span m="1046926">was</span>
  <span m="1047318">halted</span> <span m="1047709">just</span> <span m="1048100">before</span>
  <span m="1048492">executing</span> <span m="1048883">the</span> <span m="1049274">instruction</span>
  <span m="1049666">at</span> <span m="1050057">label</span> <span m="1050448">xx.</span></p><p><span
  m="1050840">We</span> <span m="1051218">also</span> <span m="1051597">know,</span>
  <span m="1051975">that</span> <span m="1052354">the</span> <span m="1052733">instruction</span>
  <span m="1053111">at</span> <span m="1053490">label</span> <span m="1053868">yy</span>
  <span m="1054247">makes</span> <span m="1054626">a</span> <span m="1055004">recursive</span>
  <span m="1055383">call</span> <span m="1055761">to</span> <span m="1056140">f.</span></p><p><span
  m="1056519">We</span> <span m="1057033">know</span> <span m="1057547">that</span>
  <span m="1058061">the</span> <span m="1058576">LP</span> <span m="1059090">value</span>
  <span m="1059604">from</span> <span m="1060118">the</span> <span m="1060633">recursive</span>
  <span m="1061147">calls</span> <span m="1061661">is</span> <span m="1062175">0xA4.</span></p><p><span
  m="1062690">This</span> <span m="1063284">means</span> <span m="1063879">that</span>
  <span m="1064473">the</span> <span m="1065068">address</span> <span m="1065662">of</span>
  <span m="1066257">the</span> <span m="1066851">DEALLOCATE(1)</span> <span m="1067446">instruction</span>
  <span m="1068040">is</span> <span m="1068635">0xA4.</span></p><p><span m="1069230">Counting</span>
  <span m="1069583">backwards</span> <span m="1069937">by</span> <span m="1070291">4</span>
  <span m="1070645">bytes,</span> <span m="1070999">and</span> <span m="1071353">accounting</span>
  <span m="1071707">for</span> <span m="1072061">the</span> <span m="1072415">fact</span>
  <span m="1072769">that</span> <span m="1073123">a</span> <span m="1073477">PUSH</span>
  <span m="1073831">operation</span> <span m="1074185">consists</span> <span m="1074539">of</span>
  <span m="1075005">two</span> <span m="1075471">instructions,</span> <span m="1075938">we</span>
  <span m="1076404">see</span> <span m="1076870">that</span> <span m="1077337">label</span>
  <span m="1077803">xx</span> <span m="1078269">=</span> <span m="1078736">0x90</span>
  <span m="1079202">and</span> <span m="1079669">that</span> <span m="1080135">is</span>
  <span m="1080601">the</span> <span m="1081068">value</span> <span m="1081534">of</span>
  <span m="1082000">the</span> <span m="1082467">PC</span> <span m="1082933">when</span>
  <span m="1083400">the</span> <span m="1083885">program</span> <span m="1084371">is</span>
  <span m="1084857">halted.</span> <span m="1085343">As</span> <span m="1085829">our</span>
  <span m="1086315">last</span> <span m="1086800">question,</span> <span m="1087286">we</span>
  <span m="1087772">want</span> <span m="1088258">to</span> <span m="1088744">consider</span>
  <span m="1089230">the</span> <span m="1089548">following:</span> <span m="1089867">Suppose</span>
  <span m="1090186">that</span> <span m="1090504">you</span> <span m="1090823">are</span>
  <span m="1091142">told</span> <span m="1091460">that</span> <span m="1091779">you</span>
  <span m="1092098">could</span> <span m="1092416">delete</span> <span m="1092735">4</span>
  <span m="1093054">instructions</span> <span m="1093372">from</span> <span m="1093691">your</span>
  <span m="1094010">program</span> <span m="1094546">without</span> <span m="1095082">affecting</span>
  <span m="1095618">the</span> <span m="1096154">behavior</span> <span m="1096690">of</span>
  <span m="1097226">the</span> <span m="1097762">program.</span></p><p><span m="1098299">The</span>
  <span m="1098707">4</span> <span m="1099115">instructions</span> <span m="1099523">to</span>
  <span m="1099932">be</span> <span m="1100340">removed</span> <span m="1100748">are</span>
  <span m="1101157">a</span> <span m="1101565">LD,</span> <span m="1101973">a</span>
  <span m="1102381">ST,</span> <span m="1102790">an</span> <span m="1103198">ALLOCATE,</span>
  <span m="1103606">and</span> <span m="1104015">a</span> <span m="1104423">MOVE</span>
  <span m="1104831">instruction.</span></p><p><span m="1105240">Removing</span> <span
  m="1105617">these</span> <span m="1105994">instructions</span> <span m="1106371">would</span>
  <span m="1106748">make</span> <span m="1107125">our</span> <span m="1107502">program</span>
  <span m="1107879">shorter</span> <span m="1108256">and</span> <span m="1108633">faster.</span></p><p><span
  m="1109010">So,</span> <span m="1109336">our</span> <span m="1109663">goal</span>
  <span m="1109990">is</span> <span m="1110317">to</span> <span m="1110644">determine</span>
  <span m="1110971">whether</span> <span m="1111298">or</span> <span m="1111625">not</span>
  <span m="1111951">this</span> <span m="1112278">is</span> <span m="1112605">possible</span>
  <span m="1112932">without</span> <span m="1113259">affecting</span> <span m="1113586">the</span>
  <span m="1113913">behavior</span> <span m="1114240">of</span> <span m="1114692">the</span>
  <span m="1115144">program.</span> <span m="1115596">Let's</span> <span m="1116048">first</span>
  <span m="1116501">consider</span> <span m="1116953">removing</span> <span m="1117405">the</span>
  <span m="1117857">ALLOCATE</span> <span m="1118310">instruction.</span> <span m="1118778">If</span>
  <span m="1119247">this</span> <span m="1119715">instruction</span> <span m="1120184">is</span>
  <span m="1120653">removed,</span> <span m="1121121">that</span> <span m="1121590">means</span>
  <span m="1122059">that</span> <span m="1122323">we</span> <span m="1122587">will</span>
  <span m="1122852">not</span> <span m="1123116">be</span> <span m="1123380">saving</span>
  <span m="1123645">space</span> <span m="1123909">on</span> <span m="1124173">the</span>
  <span m="1124438">stack</span> <span m="1124702">for</span> <span m="1124966">local</span>
  <span m="1125231">variable</span> <span m="1125495">a.</span></p><p><span m="1125760">However,</span>
  <span m="1126104">if</span> <span m="1126448">we</span> <span m="1126793">take</span>
  <span m="1127137">a</span> <span m="1127482">closer</span> <span m="1127826">look</span>
  <span m="1128171">at</span> <span m="1128515">the</span> <span m="1128860">3</span>
  <span m="1129204">lines</span> <span m="1129548">of</span> <span m="1129893">code</span>
  <span m="1130237">highlighted</span> <span m="1130582">in</span> <span m="1130926">yellow,</span>
  <span m="1131271">we</span> <span m="1131615">see</span> <span m="1131960">that</span>
  <span m="1132293">the</span> <span m="1132627">actual</span> <span m="1132960">value</span>
  <span m="1133294">of</span> <span m="1133627">a</span> <span m="1133961">is</span>
  <span m="1134294">first</span> <span m="1134628">computed</span> <span m="1134961">in</span>
  <span m="1135295">R1</span> <span m="1135628">before</span> <span m="1135962">storing</span>
  <span m="1136295">it</span> <span m="1136629">in</span> <span m="1136962">local</span>
  <span m="1137296">variable</span> <span m="1137630">a.</span> <span m="1137937">Since</span>
  <span m="1138244">R1</span> <span m="1138551">is</span> <span m="1138859">going</span>
  <span m="1139166">to</span> <span m="1139473">be</span> <span m="1139780">saved</span>
  <span m="1140088">on</span> <span m="1140395">the</span> <span m="1140702">stack</span>
  <span m="1141010">during</span> <span m="1141348">each</span> <span m="1141687">recursive</span>
  <span m="1142026">call,</span> <span m="1142365">we</span> <span m="1142703">could</span>
  <span m="1143042">get</span> <span m="1143381">away</span> <span m="1143720">without</span>
  <span m="1144058">saving</span> <span m="1144397">a</span> <span m="1144736">on</span>
  <span m="1145075">the</span> <span m="1145413">stack</span> <span m="1145752">because</span>
  <span m="1146091">we</span> <span m="1146430">can</span> <span m="1146769">find</span>
  <span m="1147114">its</span> <span m="1147459">value</span> <span m="1147804">in</span>
  <span m="1148150">the</span> <span m="1148495">stored</span> <span m="1148840">R1</span>
  <span m="1149186">of</span> <span m="1149531">the</span> <span m="1149876">next</span>
  <span m="1150221">activation</span> <span m="1150567">record</span> <span m="1150912">as</span>
  <span m="1151257">shown</span> <span m="1151603">in</span> <span m="1151948">the</span>
  <span m="1152293">highlighted</span> <span m="1152639">pairs</span> <span m="1152996">of</span>
  <span m="1153354">a</span> <span m="1153711">and</span> <span m="1154069">R1</span>
  <span m="1154426">on</span> <span m="1154784">the</span> <span m="1155141">stack.</span>
  <span m="1155499">This</span> <span m="1155857">means</span> <span m="1156214">that</span>
  <span m="1156572">we</span> <span m="1156929">could</span> <span m="1157287">safely</span>
  <span m="1157644">remove</span> <span m="1158002">the</span> <span m="1158360">ALLOCATE</span>
  <span m="1158864">instruction.</span> <span m="1159368">As</span> <span m="1159873">a</span>
  <span m="1160377">result,</span> <span m="1160882">this</span> <span m="1161386">also</span>
  <span m="1161891">means</span> <span m="1162395">that</span> <span m="1162900">we</span>
  <span m="1163404">don't</span> <span m="1163909">need</span> <span m="1164242">the</span>
  <span m="1164575">ST</span> <span m="1164909">operation</span> <span m="1165242">that</span>
  <span m="1165575">stores</span> <span m="1165909">a</span> <span m="1166242">on</span>
  <span m="1166576">the</span> <span m="1166909">stack</span> <span m="1167242">or</span>
  <span m="1167576">the</span> <span m="1167909">LD</span> <span m="1168243">operation</span>
  <span m="1168576">that</span> <span m="1168909">reloads</span> <span m="1169243">a</span>
  <span m="1169576">into</span> <span m="1169910">register</span> <span m="1170447">R1.</span>
  <span m="1170985">Finally,</span> <span m="1171523">because</span> <span m="1172061">there</span>
  <span m="1172599">are</span> <span m="1173137">no</span> <span m="1173675">longer</span>
  <span m="1174213">any</span> <span m="1174751">local</span> <span m="1175289">variables</span>
  <span m="1175748">stored</span> <span m="1176207">on</span> <span m="1176667">the</span>
  <span m="1177126">stack,</span> <span m="1177586">then</span> <span m="1178045">the</span>
  <span m="1178504">instruction</span> <span m="1178964">MOVE(BP,SP)</span> <span
  m="1179423">which</span> <span m="1179883">is</span> <span m="1180342">normally</span>
  <span m="1180801">used</span> <span m="1181261">to</span> <span m="1181720">deallocate</span>
  <span m="1182180">all</span> <span m="1182630">local</span> <span m="1183081">variables,</span>
  <span m="1183532">can</span> <span m="1183982">be</span> <span m="1184433">skipped</span>
  <span m="1184884">because</span> <span m="1185334">after</span> <span m="1185785">popping</span>
  <span m="1186236">R1,</span> <span m="1186686">the</span> <span m="1187137">BP</span>
  <span m="1187588">and</span> <span m="1188038">SP</span> <span m="1188489">registers</span>
  <span m="1188940">will</span> <span m="1189345">already</span> <span m="1189750">point</span>
  <span m="1190155">to</span> <span m="1190561">the</span> <span m="1190966">same</span>
  <span m="1191371">location.</span> <span m="1191776">So,</span> <span m="1192182">in</span>
  <span m="1192587">conclusion</span> <span m="1192992">the</span> <span m="1193397">4</span>
  <span m="1193803">operations</span> <span m="1194208">can</span> <span m="1194613">be</span>
  <span m="1195019">removed</span> <span m="1195387">from</span> <span m="1195755">the</span>
  <span m="1196123">program</span> <span m="1196492">without</span> <span m="1196860">changing</span>
  <span m="1197228">the</span> <span m="1197596">behavior</span> <span m="1197965">of</span>
  <span m="1198333">the</span> <span m="1198701">code.</span></p>
type: course
uid: 37b8487938efd25f0fb947d9332e20b9

---
None