---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: gxU2Eo3oBPg
  parent_uid: accb5c4acc6b10ac6cc887fd35462aef
  title: Video-YouTube-Stream
  type: Video
  uid: 8050c3c7e75e6e02cd20fc6168211cca
- id: 3Play-3Play YouTube id-Stream
  media_location: gxU2Eo3oBPg
  parent_uid: accb5c4acc6b10ac6cc887fd35462aef
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: fa7fa02fcd2106fc2c2c5b215b707f19
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/gxU2Eo3oBPg/default.jpg
  parent_uid: accb5c4acc6b10ac6cc887fd35462aef
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 3d4b9bc04f740fe357cd8b6ad31be057
- id: gxU2Eo3oBPg.srt
  parent_uid: accb5c4acc6b10ac6cc887fd35462aef
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v11/cache-benefits/gxU2Eo3oBPg.srt
  title: 3play caption file
  type: null
  uid: 3343f76c14a06af22acc66b6b6300f1a
- id: gxU2Eo3oBPg.pdf
  parent_uid: accb5c4acc6b10ac6cc887fd35462aef
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v11/cache-benefits/gxU2Eo3oBPg.pdf
  title: 3play pdf file
  type: null
  uid: 258e26cb8214f56977933a9a74f74739
- id: Caption-3Play YouTube id-SRT
  parent_uid: accb5c4acc6b10ac6cc887fd35462aef
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 411ac2ff8ffb25a356da5c2b48fd89cd
- id: Transcript-3Play YouTube id-PDF
  parent_uid: accb5c4acc6b10ac6cc887fd35462aef
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: f9caef842c4accc6cbb1fe6dd39a056f
- id: Video-iTunesU-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_14-02-11-01_300k.mp4
  parent_uid: accb5c4acc6b10ac6cc887fd35462aef
  title: Video-iTunes U-MP4
  type: Video
  uid: ad9b65cfadc18501bf0ec0ab450e8578
inline_embed_id: 53200730cachebenefits13930057
layout: video
order_index: null
parent_uid: 9f6575a722442cd9719b73804b20a778
related_resources_text: ''
short_url: cache-benefits
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c14/c14s2/c14s2v11/cache-benefits
template_type: Embed
title: 'Worked Example: Cache Benefits'
transcript: <p><span m="350">We</span> <span m="725">are</span> <span m="1100">going</span>
  <span m="1475">to</span> <span m="1851">compare</span> <span m="2226">the</span>
  <span m="2601">behavior</span> <span m="2976">of</span> <span m="3352">3</span>
  <span m="3727">different</span> <span m="4102">cache</span> <span m="4477">configurations</span>
  <span m="4853">on</span> <span m="5228">a</span> <span m="5603">benchmark</span>
  <span m="5979">program</span> <span m="6399">to</span> <span m="6820">better</span>
  <span m="7241">understand</span> <span m="7662">the</span> <span m="8083">impact</span>
  <span m="8504">of</span> <span m="8924">the</span> <span m="9345">cache</span> <span
  m="9766">configuration</span> <span m="10187">on</span> <span m="10608">the</span>
  <span m="11029">performance</span> <span m="11450">of</span> <span m="12130">the</span>
  <span m="12810">benchmark.</span></p><p><span m="13490">The</span> <span m="13945">first</span>
  <span m="14400">cache</span> <span m="14855">we</span> <span m="15310">will</span>
  <span m="15765">consider</span> <span m="16220">is</span> <span m="16675">a</span>
  <span m="17130">64-line</span> <span m="17585">direct</span> <span m="18040">mapped</span>
  <span m="18495">cache.</span></p><p><span m="18950">The</span> <span m="19348">second</span>
  <span m="19746">is</span> <span m="20144">a</span> <span m="20542">2-way</span>
  <span m="20940">set</span> <span m="21338">associative</span> <span m="21736">cache</span>
  <span m="22135">that</span> <span m="22533">uses</span> <span m="22931">the</span>
  <span m="23329">LRU,</span> <span m="23727">or</span> <span m="24125">least</span>
  <span m="24523">recently</span> <span m="24921">used,</span> <span m="25320">replacement</span>
  <span m="25822">strategy,</span> <span m="26324">and</span> <span m="26826">has</span>
  <span m="27328">a</span> <span m="27831">total</span> <span m="28333">of</span>
  <span m="28835">64</span> <span m="29337">lines.</span></p><p><span m="29840">The</span>
  <span m="30269">third</span> <span m="30698">is</span> <span m="31128">a</span>
  <span m="31557">4-way</span> <span m="31986">set</span> <span m="32416">associative</span>
  <span m="32845">cache</span> <span m="33274">that</span> <span m="33704">uses</span>
  <span m="34133">the</span> <span m="34562">LRU</span> <span m="34992">replacement</span>
  <span m="35421">strategy,</span> <span m="35850">and</span> <span m="36280">also</span>
  <span m="36808">has</span> <span m="37336">a</span> <span m="37865">total</span>
  <span m="38393">of</span> <span m="38922">64</span> <span m="39450">lines.</span></p><p><span
  m="39979">Note</span> <span m="40291">that</span> <span m="40603">all</span> <span
  m="40915">three</span> <span m="41227">caches</span> <span m="41539">have</span>
  <span m="41851">the</span> <span m="42164">same</span> <span m="42476">capacity</span>
  <span m="42788">in</span> <span m="43100">that</span> <span m="43412">they</span>
  <span m="43724">can</span> <span m="44037">store</span> <span m="44349">a</span>
  <span m="44661">total</span> <span m="44973">of</span> <span m="45285">64</span>
  <span m="45597">words</span> <span m="45910">of</span> <span m="46755">data.</span></p><p><span
  m="47600">In</span> <span m="48021">a</span> <span m="48442">direct</span> <span
  m="48863">mapped</span> <span m="49284">cache</span> <span m="49705">any</span>
  <span m="50127">particular</span> <span m="50548">memory</span> <span m="50969">address</span>
  <span m="51390">maps</span> <span m="51811">to</span> <span m="52232">exactly</span>
  <span m="52654">one</span> <span m="53075">line</span> <span m="53496">in</span>
  <span m="53917">the</span> <span m="54338">cache.</span></p><p><span m="54760">Let's</span>
  <span m="55134">assume</span> <span m="55508">that</span> <span m="55882">our</span>
  <span m="56256">data</span> <span m="56630">is</span> <span m="57004">32</span>
  <span m="57378">bits,</span> <span m="57752">or</span> <span m="58126">4</span>
  <span m="58500">bytes</span> <span m="58874">wide.</span></p><p><span m="59249">This</span>
  <span m="59599">means</span> <span m="59949">that</span> <span m="60299">consecutive</span>
  <span m="60649">addresses</span> <span m="60999">are</span> <span m="61349">4</span>
  <span m="61699">bytes</span> <span m="62049">apart,</span> <span m="62399">so</span>
  <span m="62749">we</span> <span m="63099">treat</span> <span m="63449">the</span>
  <span m="63799">bottom</span> <span m="64149">two</span> <span m="64500">address</span>
  <span m="64930">bits</span> <span m="65361">as</span> <span m="65791">always</span>
  <span m="66222">being</span> <span m="66653">00</span> <span m="67083">so</span>
  <span m="67514">that</span> <span m="67945">our</span> <span m="68375">address</span>
  <span m="68806">is</span> <span m="69236">on</span> <span m="69667">a</span> <span
  m="70098">data</span> <span m="70528">word</span> <span m="70959">boundary.</span></p><p><span
  m="71390">Next,</span> <span m="71846">we</span> <span m="72302">want</span> <span
  m="72758">to</span> <span m="73214">determine</span> <span m="73670">which</span>
  <span m="74126">cache</span> <span m="74583">line</span> <span m="75039">this</span>
  <span m="75495">particular</span> <span m="75951">address</span> <span m="76407">maps</span>
  <span m="76863">to.</span></p><p><span m="77320">Since</span> <span m="77693">there</span>
  <span m="78066">are</span> <span m="78439">64</span> <span m="78812">lines</span>
  <span m="79185">in</span> <span m="79558">this</span> <span m="79931">cache,</span>
  <span m="80304">we</span> <span m="80677">need</span> <span m="81050">6</span> <span
  m="81423">bits</span> <span m="81796">to</span> <span m="82169">select</span> <span
  m="82542">one</span> <span m="82915">of</span> <span m="83288">the</span> <span
  m="83661">64</span> <span m="84034">lines.</span></p><p><span m="84408">These</span>
  <span m="84815">6</span> <span m="85222">bits</span> <span m="85630">are</span>
  <span m="86037">called</span> <span m="86445">the</span> <span m="86852">index.</span></p><p><span
  m="87260">In</span> <span m="87793">this</span> <span m="88326">example,</span>
  <span m="88860">the</span> <span m="89393">index</span> <span m="89926">is</span>
  <span m="90460">000011,</span> <span m="90993">so</span> <span m="91526">this</span>
  <span m="92060">particular</span> <span m="92593">address</span> <span m="93126">maps</span>
  <span m="93660">to</span> <span m="94193">line</span> <span m="94726">3</span> <span
  m="95260">of</span> <span m="95793">the</span> <span m="96326">cache.</span></p><p><span
  m="96860">The</span> <span m="97149">data</span> <span m="97438">that</span> <span
  m="97728">gets</span> <span m="98017">stored</span> <span m="98307">in</span> <span
  m="98596">the</span> <span m="98886">cache</span> <span m="99175">is</span> <span
  m="99465">the</span> <span m="99754">tag</span> <span m="100043">portion</span>
  <span m="100333">of</span> <span m="100622">the</span> <span m="100912">address</span>
  <span m="101201">of</span> <span m="101491">the</span> <span m="101780">line</span>
  <span m="102070">plus</span> <span m="102580">the</span> <span m="103090">32</span>
  <span m="103600">bits</span> <span m="104110">of</span> <span m="104620">data.</span></p><p><span
  m="105130">The</span> <span m="105442">tag</span> <span m="105755">is</span> <span
  m="106068">used</span> <span m="106381">for</span> <span m="106694">comparison</span>
  <span m="107007">when</span> <span m="107320">checking</span> <span m="107633">if</span>
  <span m="107946">a</span> <span m="108259">particular</span> <span m="108572">address</span>
  <span m="108885">is</span> <span m="109198">in</span> <span m="109511">the</span>
  <span m="109824">cache</span> <span m="110137">or</span> <span m="110450">not.</span></p><p><span
  m="111450">It</span> <span m="112058">uniquely</span> <span m="112667">identifies</span>
  <span m="113275">the</span> <span m="113884">particular</span> <span m="114492">memory</span>
  <span m="115101">address.</span></p><p><span m="115710">In</span> <span m="115978">addition,</span>
  <span m="116246">each</span> <span m="116515">cache</span> <span m="116783">line</span>
  <span m="117051">has</span> <span m="117320">a</span> <span m="117588">valid</span>
  <span m="117856">bit</span> <span m="118125">that</span> <span m="118393">lets</span>
  <span m="118661">you</span> <span m="118930">know</span> <span m="119198">whether</span>
  <span m="119466">the</span> <span m="119735">data</span> <span m="120003">in</span>
  <span m="120271">the</span> <span m="120540">cache</span> <span m="121056">is</span>
  <span m="121573">currently</span> <span m="122090">valid</span> <span m="122606">or</span>
  <span m="123123">not.</span></p><p><span m="123640">This</span> <span m="123933">is</span>
  <span m="124227">important</span> <span m="124520">upon</span> <span m="124814">startup</span>
  <span m="125107">because</span> <span m="125401">without</span> <span m="125694">this</span>
  <span m="125988">bit</span> <span m="126281">there</span> <span m="126575">is</span>
  <span m="126868">no</span> <span m="127162">way</span> <span m="127455">to</span>
  <span m="127749">know</span> <span m="128042">whether</span> <span m="128336">the</span>
  <span m="128630">data</span> <span m="129132">in</span> <span m="129634">the</span>
  <span m="130136">cache</span> <span m="130638">is</span> <span m="131141">garbage</span>
  <span m="131643">or</span> <span m="132145">real</span> <span m="132647">data.</span></p><p><span
  m="133150">In</span> <span m="133484">a</span> <span m="133818">2-way</span> <span
  m="134152">set</span> <span m="134486">associative</span> <span m="134820">cache,</span>
  <span m="135154">the</span> <span m="135488">cache</span> <span m="135822">is</span>
  <span m="136156">divided</span> <span m="136490">into</span> <span m="136824">2</span>
  <span m="137158">sets</span> <span m="137492">each</span> <span m="137826">with</span>
  <span m="138160">half</span> <span m="138494">the</span> <span m="138829">number</span>
  <span m="139486">of</span> <span m="140143">lines.</span></p><p><span m="140800">So</span>
  <span m="141195">we</span> <span m="141591">have</span> <span m="141986">two</span>
  <span m="142382">sets</span> <span m="142777">with</span> <span m="143173">32</span>
  <span m="143568">lines</span> <span m="143964">each.</span></p><p><span m="144360">Since</span>
  <span m="144691">there</span> <span m="145022">are</span> <span m="145353">only</span>
  <span m="145684">32</span> <span m="146015">lines,</span> <span m="146346">we</span>
  <span m="146677">now</span> <span m="147008">only</span> <span m="147340">need</span>
  <span m="147671">a</span> <span m="148002">5</span> <span m="148333">bit</span>
  <span m="148664">index</span> <span m="148995">to</span> <span m="149326">select</span>
  <span m="149657">the</span> <span m="149988">line.</span></p><p><span m="150320">However,</span>
  <span m="150772">any</span> <span m="151225">given</span> <span m="151678">index</span>
  <span m="152131">can</span> <span m="152584">map</span> <span m="153037">to</span>
  <span m="153490">two</span> <span m="153942">distinct</span> <span m="154395">locations,</span>
  <span m="154848">one</span> <span m="155301">in</span> <span m="155754">each</span>
  <span m="156207">set.</span></p><p><span m="156660">This</span> <span m="157027">also</span>
  <span m="157394">means</span> <span m="157762">that</span> <span m="158129">when</span>
  <span m="158496">the</span> <span m="158864">tag</span> <span m="159231">comparisons</span>
  <span m="159598">are</span> <span m="159966">done,</span> <span m="160333">two</span>
  <span m="160700">comparisons</span> <span m="161068">are</span> <span m="161435">required,</span>
  <span m="161802">one</span> <span m="162170">per</span> <span m="163025">set.</span></p><p><span
  m="163880">In</span> <span m="164268">a</span> <span m="164656">4-way</span> <span
  m="165044">set</span> <span m="165432">associative</span> <span m="165821">cache,</span>
  <span m="166209">the</span> <span m="166597">cache</span> <span m="166985">is</span>
  <span m="167374">divided</span> <span m="167762">into</span> <span m="168150">4</span>
  <span m="168538">sets</span> <span m="168927">each</span> <span m="169315">with</span>
  <span m="169703">16</span> <span m="170091">lines.</span></p><p><span m="170480">The</span>
  <span m="170783">width</span> <span m="171087">of</span> <span m="171390">the</span>
  <span m="171694">index</span> <span m="171997">is</span> <span m="172301">now</span>
  <span m="172605">4</span> <span m="172908">bits</span> <span m="173212">to</span>
  <span m="173515">select</span> <span m="173819">the</span> <span m="174122">cache</span>
  <span m="174426">line.</span></p><p><span m="174730">Here,</span> <span m="175130">selecting</span>
  <span m="175531">a</span> <span m="175932">line</span> <span m="176332">identifies</span>
  <span m="176733">one</span> <span m="177134">of</span> <span m="177534">4</span>
  <span m="177935">words</span> <span m="178336">as</span> <span m="178736">possible</span>
  <span m="179137">locations</span> <span m="179538">for</span> <span m="179938">reading</span>
  <span m="180339">or</span> <span m="180740">writing</span> <span m="181607">the</span>
  <span m="182475">associated</span> <span m="183342">data.</span></p><p><span m="184210">This</span>
  <span m="184524">also</span> <span m="184839">implies</span> <span m="185154">that</span>
  <span m="185468">4</span> <span m="185783">tags</span> <span m="186098">need</span>
  <span m="186413">to</span> <span m="186727">be</span> <span m="187042">compared</span>
  <span m="187357">when</span> <span m="187672">trying</span> <span m="187986">to</span>
  <span m="188301">read</span> <span m="188616">from</span> <span m="188931">the</span>
  <span m="189245">cache</span> <span m="189560">to</span> <span m="189875">determine</span>
  <span m="190190">if</span> <span m="190680">the</span> <span m="191171">desired</span>
  <span m="191662">address</span> <span m="192153">is</span> <span m="192644">stored</span>
  <span m="193135">in</span> <span m="193626">the</span> <span m="194117">cache</span>
  <span m="194608">or</span> <span m="195099">not.</span></p><p><span m="195590">The</span>
  <span m="196135">test</span> <span m="196681">program</span> <span m="197227">begins</span>
  <span m="197772">by</span> <span m="198318">defining</span> <span m="198864">a</span>
  <span m="199410">few</span> <span m="199955">constants,</span> <span m="200501">J,</span>
  <span m="201047">A,</span> <span m="201592">B,</span> <span m="202138">and</span>
  <span m="202684">N.</span></p><p><span m="203230">J</span> <span m="203687">specifies</span>
  <span m="204145">the</span> <span m="204602">address</span> <span m="205060">where</span>
  <span m="205517">the</span> <span m="205975">program</span> <span m="206432">lives.</span></p><p><span
  m="206890">A</span> <span m="207254">is</span> <span m="207618">the</span> <span
  m="207983">starting</span> <span m="208347">address</span> <span m="208712">of</span>
  <span m="209076">data</span> <span m="209441">region</span> <span m="209805">1,</span>
  <span m="210170">and</span> <span m="210534">B</span> <span m="210898">is</span>
  <span m="211263">the</span> <span m="211627">starting</span> <span m="211992">address</span>
  <span m="212356">of</span> <span m="212721">data</span> <span m="213085">region</span>
  <span m="213450">2.</span></p><p><span m="214450">Finally,</span> <span m="214956">N</span>
  <span m="215463">specifies</span> <span m="215970">the</span> <span m="216476">size</span>
  <span m="216983">of</span> <span m="217490">the</span> <span m="217996">data</span>
  <span m="218503">regions.</span></p><p><span m="219010">Since</span> <span m="219334">one</span>
  <span m="219658">word</span> <span m="219983">consists</span> <span m="220307">of</span>
  <span m="220632">4</span> <span m="220956">bytes,</span> <span m="221281">16</span>
  <span m="221605">bytes</span> <span m="221930">of</span> <span m="222254">data</span>
  <span m="222578">mean</span> <span m="222903">that</span> <span m="223227">there</span>
  <span m="223552">are</span> <span m="223876">4</span> <span m="224201">data</span>
  <span m="224525">elements</span> <span m="224850">per</span> <span m="226095">region.</span></p><p><span
  m="227340">Next</span> <span m="227871">the</span> <span m="228402">assembler</span>
  <span m="228934">is</span> <span m="229465">told</span> <span m="229996">that</span>
  <span m="230528">the</span> <span m="231059">beginning</span> <span m="231590">of</span>
  <span m="232122">the</span> <span m="232653">program</span> <span m="233184">is</span>
  <span m="233716">at</span> <span m="234247">address</span> <span m="234778">0x1000.</span></p><p><span
  m="235310">The</span> <span m="235695">green</span> <span m="236080">rectangle</span>
  <span m="236465">identifies</span> <span m="236850">the</span> <span m="237235">outer</span>
  <span m="237620">loop,</span> <span m="238005">and</span> <span m="238390">the</span>
  <span m="238775">yellow</span> <span m="239160">rectangle</span> <span m="239545">identifies</span>
  <span m="239930">the</span> <span m="240315">inner</span> <span m="240700">loop</span>
  <span m="241177">of</span> <span m="241655">the</span> <span m="242132">code.</span></p><p><span
  m="242610">Before</span> <span m="242983">entering</span> <span m="243357">the</span>
  <span m="243731">outer</span> <span m="244105">loop,</span> <span m="244478">a</span>
  <span m="244852">loop</span> <span m="245226">counter,</span> <span m="245600">which</span>
  <span m="245973">is</span> <span m="246347">stored</span> <span m="246721">in</span>
  <span m="247095">register</span> <span m="247468">R6</span> <span m="247842">is</span>
  <span m="248216">initialized</span> <span m="248590">to</span> <span m="249760">1,000.</span></p><p><span
  m="250930">Then</span> <span m="251260">each</span> <span m="251590">time</span>
  <span m="251920">through</span> <span m="252250">the</span> <span m="252580">outer</span>
  <span m="252910">loop,</span> <span m="253240">R6</span> <span m="253570">is</span>
  <span m="253900">decremented</span> <span m="254230">by</span> <span m="254560">1</span>
  <span m="254890">and</span> <span m="255220">the</span> <span m="255550">loop</span>
  <span m="255880">is</span> <span m="256210">repeated</span> <span m="256540">as</span>
  <span m="256856">long</span> <span m="257173">as</span> <span m="257490">R6</span>
  <span m="257806">is</span> <span m="258123">not</span> <span m="258440">equal</span>
  <span m="258756">to</span> <span m="259073">0.</span></p><p><span m="259390">The</span>
  <span m="259835">outer</span> <span m="260280">loop</span> <span m="260726">also</span>
  <span m="261171">resets</span> <span m="261616">R0</span> <span m="262062">to</span>
  <span m="262507">N</span> <span m="262953">each</span> <span m="263398">time</span>
  <span m="263843">through</span> <span m="264289">the</span> <span m="264734">loop.</span></p><p><span
  m="265180">R0</span> <span m="265680">is</span> <span m="266180">used</span> <span
  m="266680">to</span> <span m="267180">hold</span> <span m="267680">the</span> <span
  m="268180">desired</span> <span m="268680">array</span> <span m="269180">offset.</span></p><p><span
  m="269680">Since</span> <span m="269984">the</span> <span m="270288">last</span>
  <span m="270592">element</span> <span m="270896">of</span> <span m="271201">the</span>
  <span m="271505">array</span> <span m="271809">is</span> <span m="272113">stored</span>
  <span m="272417">at</span> <span m="272722">location</span> <span m="273026">N</span>
  <span m="273330">&ndash;</span> <span m="273634">4,</span> <span m="273938">the</span>
  <span m="274243">first</span> <span m="274547">step</span> <span m="274851">of</span>
  <span m="275155">the</span> <span m="275460">inner</span> <span m="275912">loop,</span>
  <span m="276365">is</span> <span m="276817">to</span> <span m="277270">decrement</span>
  <span m="277722">R0</span> <span m="278175">by</span> <span m="278627">4.</span></p><p><span
  m="279080">R1</span> <span m="279489">is</span> <span m="279899">then</span> <span
  m="280308">loaded</span> <span m="280718">with</span> <span m="281127">the</span>
  <span m="281537">value</span> <span m="281947">at</span> <span m="282356">address</span>
  <span m="282766">A</span> <span m="283175">+</span> <span m="283585">N</span> <span
  m="283994">&ndash;</span> <span m="284404">4</span> <span m="284814">which</span>
  <span m="285223">is</span> <span m="285633">the</span> <span m="286042">address</span>
  <span m="286452">of</span> <span m="286861">A[3]</span> <span m="287271">because</span>
  <span m="287681">array</span> <span m="288324">indeces</span> <span m="288968">begin</span>
  <span m="289612">at</span> <span m="290256">0.</span></p><p><span m="290900">R2</span>
  <span m="291650">is</span> <span m="292400">loaded</span> <span m="293150">with</span>
  <span m="293900">B[3].</span></p><p><span m="294650">As</span> <span m="295014">long</span>
  <span m="295378">as</span> <span m="295743">R0</span> <span m="296107">is</span>
  <span m="296472">not</span> <span m="296836">equal</span> <span m="297201">to</span>
  <span m="297565">0,</span> <span m="297930">the</span> <span m="298294">loop</span>
  <span m="298658">repeats</span> <span m="299023">itself,</span> <span m="299387">each</span>
  <span m="299752">time</span> <span m="300116">accessing</span> <span m="300481">the</span>
  <span m="300845">previous</span> <span m="301210">element</span> <span m="301742">of</span>
  <span m="302275">each</span> <span m="302807">array</span> <span m="303340">until</span>
  <span m="303872">the</span> <span m="304405">first</span> <span m="304937">element</span>
  <span m="305470">(index</span> <span m="306002">0)</span> <span m="306535">is</span>
  <span m="307067">loaded.</span></p><p><span m="307600">Then</span> <span m="308013">the</span>
  <span m="308427">outer</span> <span m="308841">loop</span> <span m="309255">decrements</span>
  <span m="309669">R6</span> <span m="310083">and</span> <span m="310496">repeats</span>
  <span m="310910">the</span> <span m="311324">entire</span> <span m="311738">thing</span>
  <span m="312152">1000</span> <span m="312566">times.</span></p><p><span m="312980">Now</span>
  <span m="313410">that</span> <span m="313841">we</span> <span m="314271">understand</span>
  <span m="314702">the</span> <span m="315133">configuration</span> <span m="315563">of</span>
  <span m="315994">our</span> <span m="316425">three</span> <span m="316855">caches</span>
  <span m="317286">and</span> <span m="317716">the</span> <span m="318147">behavior</span>
  <span m="318578">of</span> <span m="319008">our</span> <span m="319439">test</span>
  <span m="319870">benchmark,</span> <span m="320327">we</span> <span m="320785">can</span>
  <span m="321243">begin</span> <span m="321701">comparing</span> <span m="322159">the</span>
  <span m="322617">behavior</span> <span m="323075">of</span> <span m="323532">this</span>
  <span m="323990">benchmark</span> <span m="324448">on</span> <span m="324906">the</span>
  <span m="325364">three</span> <span m="325822">caches.</span></p><p><span m="326280">The</span>
  <span m="326601">first</span> <span m="326923">thing</span> <span m="327245">we</span>
  <span m="327567">want</span> <span m="327889">to</span> <span m="328211">ask</span>
  <span m="328533">ourselves</span> <span m="328855">is</span> <span m="329176">which</span>
  <span m="329498">of</span> <span m="329820">the</span> <span m="330142">three</span>
  <span m="330464">cache</span> <span m="330786">configurations</span> <span m="331108">gets</span>
  <span m="331430">the</span> <span m="332105">highest</span> <span m="332780">hit</span>
  <span m="333455">ratio.</span></p><p><span m="334130">Here</span> <span m="334490">we</span>
  <span m="334851">are</span> <span m="335211">not</span> <span m="335572">asked</span>
  <span m="335932">to</span> <span m="336293">calculate</span> <span m="336654">an</span>
  <span m="337014">actual</span> <span m="337375">hit</span> <span m="337735">ratio,</span>
  <span m="338096">instead</span> <span m="338457">we</span> <span m="338817">just</span>
  <span m="339178">need</span> <span m="339538">to</span> <span m="339899">realize</span>
  <span m="340260">that</span> <span m="340623">there</span> <span m="340987">are</span>
  <span m="341350">3</span> <span m="341714">distinct</span> <span m="342078">regions</span>
  <span m="342441">of</span> <span m="342805">data</span> <span m="343169">in</span>
  <span m="343532">this</span> <span m="343896">benchmark.</span></p><p><span m="344260">The</span>
  <span m="344738">first</span> <span m="345216">holds</span> <span m="345694">the</span>
  <span m="346172">instructions,</span> <span m="346650">the</span> <span m="347128">second</span>
  <span m="347606">holds</span> <span m="348084">array</span> <span m="348562">A,</span>
  <span m="349040">and</span> <span m="349518">the</span> <span m="349996">third</span>
  <span m="350474">holds</span> <span m="350952">array</span> <span m="351430">B.</span></p><p><span
  m="351909">If</span> <span m="352188">we</span> <span m="352468">think</span> <span
  m="352747">about</span> <span m="353027">the</span> <span m="353306">addresses</span>
  <span m="353586">of</span> <span m="353865">each</span> <span m="354145">of</span>
  <span m="354424">these</span> <span m="354704">regions</span> <span m="354983">in</span>
  <span m="355263">memory,</span> <span m="355542">we</span> <span m="355822">see</span>
  <span m="356101">that</span> <span m="356381">the</span> <span m="356660">first</span>
  <span m="356940">instruction</span> <span m="357756">is</span> <span m="358572">at</span>
  <span m="359388">address</span> <span m="360204">0x1000.</span></p><p><span m="361020">This</span>
  <span m="361373">will</span> <span m="361726">result</span> <span m="362080">in</span>
  <span m="362433">an</span> <span m="362786">index</span> <span m="363140">of</span>
  <span m="363493">0</span> <span m="363846">regardless</span> <span m="364200">of</span>
  <span m="364553">which</span> <span m="364906">cache</span> <span m="365260">you</span>
  <span m="365613">consider,</span> <span m="365966">so</span> <span m="366320">for</span>
  <span m="366673">all</span> <span m="367026">three</span> <span m="367380">caches</span>
  <span m="367813">the</span> <span m="368246">first</span> <span m="368679">instruction</span>
  <span m="369112">would</span> <span m="369545">map</span> <span m="369978">to</span>
  <span m="370411">the</span> <span m="370844">first</span> <span m="371277">line</span>
  <span m="371710">of</span> <span m="372143">the</span> <span m="372576">cache.</span></p><p><span
  m="373010">Similarly</span> <span m="373616">the</span> <span m="374222">first</span>
  <span m="374828">element</span> <span m="375434">of</span> <span m="376040">arrays</span>
  <span m="376646">A</span> <span m="377252">and</span> <span m="377858">B</span>
  <span m="378464">are</span> <span m="379070">at</span> <span m="379676">address</span>
  <span m="380282">0x2000</span> <span m="380888">and</span> <span m="381494">0x3000.</span></p><p><span
  m="382100">These</span> <span m="382412">addresses</span> <span m="382724">will</span>
  <span m="383037">also</span> <span m="383349">result</span> <span m="383661">in</span>
  <span m="383974">an</span> <span m="384286">index</span> <span m="384598">of</span>
  <span m="384911">0</span> <span m="385223">regardless</span> <span m="385535">of</span>
  <span m="385848">which</span> <span m="386160">of</span> <span m="386472">the</span>
  <span m="386785">three</span> <span m="387097">caches</span> <span m="387410">you</span>
  <span m="388430">consider.</span></p><p><span m="389450">So</span> <span m="389871">we</span>
  <span m="390292">see</span> <span m="390713">that</span> <span m="391134">the</span>
  <span m="391555">1st</span> <span m="391976">CMOVE,</span> <span m="392397">A[0],</span>
  <span m="392818">and</span> <span m="393239">B[0]</span> <span m="393660">would</span>
  <span m="394081">all</span> <span m="394502">map</span> <span m="394923">to</span>
  <span m="395344">line</span> <span m="395765">0</span> <span m="396186">of</span>
  <span m="396607">the</span> <span m="397028">cache.</span></p><p><span m="397450">Similarly,</span>
  <span m="397974">the</span> <span m="398498">2nd</span> <span m="399022">CMOVE</span>
  <span m="399546">whose</span> <span m="400070">address</span> <span m="400594">is</span>
  <span m="401118">0x1004</span> <span m="401642">would</span> <span m="402167">map</span>
  <span m="402691">to</span> <span m="403215">line</span> <span m="403739">1</span>
  <span m="404263">of</span> <span m="404787">the</span> <span m="405311">cache</span>
  <span m="405835">as</span> <span m="406360">would</span> <span m="407286">array</span>
  <span m="408213">elements</span> <span m="409139">A[1]</span> <span m="410066">and</span>
  <span m="410992">B[1].</span></p><p><span m="411919">This</span> <span m="412225">tells</span>
  <span m="412532">us</span> <span m="412839">that</span> <span m="413145">if</span>
  <span m="413452">we</span> <span m="413759">use</span> <span m="414066">the</span>
  <span m="414372">direct</span> <span m="414679">mapped</span> <span m="414986">cache,</span>
  <span m="415292">or</span> <span m="415599">a</span> <span m="415906">2-way</span>
  <span m="416213">set</span> <span m="416519">associative</span> <span m="416826">cache,</span>
  <span m="417133">then</span> <span m="417440">we</span> <span m="417873">will</span>
  <span m="418306">have</span> <span m="418739">cache</span> <span m="419173">collisions</span>
  <span m="419606">between</span> <span m="420039">the</span> <span m="420472">instructions,</span>
  <span m="420906">and</span> <span m="421339">the</span> <span m="421772">array</span>
  <span m="422205">elements.</span></p><p><span m="422639">Collisions</span> <span
  m="422960">in</span> <span m="423282">the</span> <span m="423604">cache</span> <span
  m="423926">imply</span> <span m="424248">cache</span> <span m="424570">misses</span>
  <span m="424892">as</span> <span m="425214">we</span> <span m="425536">replace</span>
  <span m="425858">one</span> <span m="426180">piece</span> <span m="426502">of</span>
  <span m="426824">data</span> <span m="427146">with</span> <span m="427468">another</span>
  <span m="427790">in</span> <span m="428303">the</span> <span m="428816">cache.</span></p><p><span
  m="429330">However,</span> <span m="429689">if</span> <span m="430049">we</span>
  <span m="430409">use</span> <span m="430769">a</span> <span m="431129">4-way</span>
  <span m="431489">set</span> <span m="431849">associative</span> <span m="432209">cache</span>
  <span m="432569">then</span> <span m="432929">each</span> <span m="433289">region</span>
  <span m="433649">of</span> <span m="434009">memory</span> <span m="434369">can</span>
  <span m="434729">go</span> <span m="435089">in</span> <span m="435449">a</span>
  <span m="435850">distinct</span> <span m="436251">set</span> <span m="436653">in</span>
  <span m="437054">the</span> <span m="437456">cache</span> <span m="437857">thus</span>
  <span m="438258">avoiding</span> <span m="438660">collisions</span> <span m="439061">and</span>
  <span m="439463">resulting</span> <span m="439864">in</span> <span m="440265">100%</span>
  <span m="440667">hit</span> <span m="441068">rate</span> <span m="441470">after</span>
  <span m="441918">the</span> <span m="442367">first</span> <span m="442815">time</span>
  <span m="443264">through</span> <span m="443712">the</span> <span m="444161">loop.</span></p><p><span
  m="444610">Note</span> <span m="444918">that</span> <span m="445226">the</span>
  <span m="445534">first</span> <span m="445842">time</span> <span m="446150">through</span>
  <span m="446458">the</span> <span m="446766">loop</span> <span m="447074">each</span>
  <span m="447382">instruction</span> <span m="447690">and</span> <span m="447998">data</span>
  <span m="448306">access</span> <span m="448614">will</span> <span m="448922">result</span>
  <span m="449230">in</span> <span m="449556">a</span> <span m="449883">cache</span>
  <span m="450210">miss</span> <span m="450536">because</span> <span m="450863">the</span>
  <span m="451190">data</span> <span m="451516">needs</span> <span m="451843">to</span>
  <span m="452170">initially</span> <span m="452496">be</span> <span m="452823">brought</span>
  <span m="453150">into</span> <span m="453476">the</span> <span m="453803">cache.</span></p><p><span
  m="454130">But</span> <span m="454590">when</span> <span m="455050">the</span> <span
  m="455510">loop</span> <span m="455970">is</span> <span m="456430">repeated,</span>
  <span m="456890">the</span> <span m="457350">data</span> <span m="457810">is</span>
  <span m="458270">already</span> <span m="458730">there</span> <span m="459190">and</span>
  <span m="459650">results</span> <span m="460110">in</span> <span m="460570">cache</span>
  <span m="461030">hits.</span></p><p><span m="461490">Now</span> <span m="461988">suppose</span>
  <span m="462486">that</span> <span m="462984">we</span> <span m="463482">make</span>
  <span m="463981">a</span> <span m="464479">minor</span> <span m="464977">modification</span>
  <span m="465475">to</span> <span m="465974">our</span> <span m="466472">test</span>
  <span m="466970">program</span> <span m="467468">by</span> <span m="467967">changing</span>
  <span m="468465">B</span> <span m="468963">from</span> <span m="469461">0x3000</span>
  <span m="469960">to</span> <span m="471245">0x2000.</span></p><p><span m="472530">This</span>
  <span m="472947">means</span> <span m="473364">that</span> <span m="473782">array</span>
  <span m="474199">A</span> <span m="474616">and</span> <span m="475034">array</span>
  <span m="475451">B</span> <span m="475868">now</span> <span m="476286">refer</span>
  <span m="476703">to</span> <span m="477120">same</span> <span m="477538">locations</span>
  <span m="477955">in</span> <span m="478372">memory.</span></p><p><span m="478790">We</span>
  <span m="479166">want</span> <span m="479542">to</span> <span m="479918">determine,</span>
  <span m="480294">which</span> <span m="480670">of</span> <span m="481046">the</span>
  <span m="481422">cache's</span> <span m="481798">hit</span> <span m="482174">rate</span>
  <span m="482550">will</span> <span m="482926">show</span> <span m="483302">a</span>
  <span m="483678">noticeable</span> <span m="484054">improvement</span> <span m="484430">as</span>
  <span m="484855">a</span> <span m="485280">result</span> <span m="485705">of</span>
  <span m="486130">this</span> <span m="486555">change.</span></p><p><span m="486980">The</span>
  <span m="487334">difference</span> <span m="487688">between</span> <span m="488042">our</span>
  <span m="488396">original</span> <span m="488750">benchmark</span> <span m="489104">and</span>
  <span m="489458">this</span> <span m="489812">modified</span> <span m="490166">one</span>
  <span m="490520">is</span> <span m="490874">that</span> <span m="491228">we</span>
  <span m="491582">now</span> <span m="491936">have</span> <span m="492290">two</span>
  <span m="492641">distinct</span> <span m="492992">regions</span> <span m="493344">of</span>
  <span m="493695">memory</span> <span m="494046">to</span> <span m="494398">access,</span>
  <span m="494749">one</span> <span m="495100">for</span> <span m="495452">the</span>
  <span m="495803">instructions,</span> <span m="496154">and</span> <span m="496506">one</span>
  <span m="496857">for</span> <span m="497208">the</span> <span m="497560">data.</span></p><p><span
  m="498930">This</span> <span m="499321">means</span> <span m="499713">that</span>
  <span m="500104">the</span> <span m="500496">2-way</span> <span m="500887">set</span>
  <span m="501279">associative</span> <span m="501670">cache</span> <span m="502062">will</span>
  <span m="502453">no</span> <span m="502845">longer</span> <span m="503236">experience</span>
  <span m="503628">collisions</span> <span m="504020">in</span> <span m="504483">its</span>
  <span m="504947">cache,</span> <span m="505411">so</span> <span m="505875">its</span>
  <span m="506338">hit</span> <span m="506802">rate</span> <span m="507266">will</span>
  <span m="507730">be</span> <span m="508193">significantly</span> <span m="508657">better</span>
  <span m="509121">than</span> <span m="509585">with</span> <span m="510048">the</span>
  <span m="510512">original</span> <span m="510976">benchmark.</span></p><p><span
  m="511440">Now</span> <span m="511797">suppose</span> <span m="512154">that</span>
  <span m="512511">we</span> <span m="512868">change</span> <span m="513226">our</span>
  <span m="513583">benchmark</span> <span m="513940">once</span> <span m="514297">again,</span>
  <span m="514655">this</span> <span m="515012">time</span> <span m="515369">making</span>
  <span m="515726">J,</span> <span m="516083">A</span> <span m="516441">and</span>
  <span m="516798">B</span> <span m="517155">all</span> <span m="517512">equal</span>
  <span m="517870">to</span> <span m="518412">0,</span> <span m="518954">and</span>
  <span m="519497">changing</span> <span m="520039">N</span> <span m="520581">to</span>
  <span m="521124">be</span> <span m="521666">64.</span></p><p><span m="522209">This</span>
  <span m="522597">means</span> <span m="522986">that</span> <span m="523374">we</span>
  <span m="523763">now</span> <span m="524151">have</span> <span m="524540">16</span>
  <span m="524929">elements</span> <span m="525317">in</span> <span m="525706">our</span>
  <span m="526094">arrays</span> <span m="526483">instead</span> <span m="526871">of</span>
  <span m="527260">4.</span></p><p><span m="527649">It</span> <span m="527957">also</span>
  <span m="528265">means</span> <span m="528574">that</span> <span m="528882">the</span>
  <span m="529190">array</span> <span m="529499">values</span> <span m="529807">that</span>
  <span m="530115">we</span> <span m="530424">are</span> <span m="530732">loading</span>
  <span m="531040">for</span> <span m="531349">arrays</span> <span m="531657">A</span>
  <span m="531965">and</span> <span m="532274">B</span> <span m="532582">are</span>
  <span m="532890">actually</span> <span m="533199">the</span> <span m="533669">same</span>
  <span m="534139">as</span> <span m="534609">the</span> <span m="535079">instructions</span>
  <span m="535549">of</span> <span m="536019">the</span> <span m="536489">program.</span></p><p><span
  m="536960">Another</span> <span m="537229">way</span> <span m="537498">of</span>
  <span m="537768">thinking</span> <span m="538037">about</span> <span m="538307">this</span>
  <span m="538576">is</span> <span m="538845">that</span> <span m="539115">we</span>
  <span m="539384">now</span> <span m="539654">only</span> <span m="539923">have</span>
  <span m="540192">one</span> <span m="540462">distinct</span> <span m="540731">region</span>
  <span m="541001">of</span> <span m="541270">memory</span> <span m="541540">being</span>
  <span m="542214">accessed.</span></p><p><span m="542889">What</span> <span m="543209">we</span>
  <span m="543530">want</span> <span m="543850">to</span> <span m="544171">determine</span>
  <span m="544491">now,</span> <span m="544812">is</span> <span m="545133">the</span>
  <span m="545453">total</span> <span m="545774">number</span> <span m="546094">of</span>
  <span m="546415">cache</span> <span m="546736">misses</span> <span m="547056">that</span>
  <span m="547377">will</span> <span m="547697">occur</span> <span m="548018">for</span>
  <span m="548339">each</span> <span m="549191">of</span> <span m="550043">the</span>
  <span m="550895">cache</span> <span m="551747">configurations.</span></p><p><span
  m="552600">Let's</span> <span m="553058">begin</span> <span m="553517">by</span>
  <span m="553975">considering</span> <span m="554434">the</span> <span m="554893">direct</span>
  <span m="555351">mapped</span> <span m="555810">cache.</span></p><p><span m="556269">In</span>
  <span m="556638">the</span> <span m="557007">direct</span> <span m="557377">mapped</span>
  <span m="557746">cache,</span> <span m="558115">we</span> <span m="558485">would</span>
  <span m="558854">want</span> <span m="559223">to</span> <span m="559593">first</span>
  <span m="559962">access</span> <span m="560331">the</span> <span m="560701">first</span>
  <span m="561070">CMOVE</span> <span m="561439">instruction.</span></p><p><span m="561809">Since</span>
  <span m="562186">this</span> <span m="562564">instruction</span> <span m="562941">is</span>
  <span m="563319">not</span> <span m="563696">yet</span> <span m="564074">in</span>
  <span m="564451">the</span> <span m="564829">cache,</span> <span m="565207">our</span>
  <span m="565584">first</span> <span m="565962">access</span> <span m="566339">is</span>
  <span m="566717">a</span> <span m="567094">cache</span> <span m="567472">miss.</span></p><p><span
  m="567850">We</span> <span m="568225">now</span> <span m="568600">bring</span> <span
  m="568976">the</span> <span m="569351">binary</span> <span m="569726">equivalent</span>
  <span m="570102">of</span> <span m="570477">this</span> <span m="570852">instruction</span>
  <span m="571228">into</span> <span m="571603">line</span> <span m="571978">0</span>
  <span m="572354">of</span> <span m="572729">our</span> <span m="573104">cache.</span></p><p><span
  m="573480">Next,</span> <span m="574075">we</span> <span m="574670">want</span>
  <span m="575266">to</span> <span m="575861">access</span> <span m="576457">the</span>
  <span m="577052">second</span> <span m="577648">CMOVE</span> <span m="578243">instruction.</span></p><p><span
  m="578839">Once</span> <span m="579242">again</span> <span m="579645">the</span>
  <span m="580049">instruction</span> <span m="580452">is</span> <span m="580855">not</span>
  <span m="581259">in</span> <span m="581662">our</span> <span m="582065">cache</span>
  <span m="582469">so</span> <span m="582872">we</span> <span m="583275">get</span>
  <span m="583679">another</span> <span m="584082">cache</span> <span m="584485">miss.</span></p><p><span
  m="584889">This</span> <span m="585301">results</span> <span m="585714">in</span>
  <span m="586127">our</span> <span m="586539">loading</span> <span m="586952">the</span>
  <span m="587365">2nd</span> <span m="587777">CMOVE</span> <span m="588190">instruction</span>
  <span m="588603">to</span> <span m="589015">line</span> <span m="589428">1</span>
  <span m="589841">of</span> <span m="590253">our</span> <span m="590666">cache.</span></p><p><span
  m="591079">We</span> <span m="591559">continue</span> <span m="592040">in</span>
  <span m="592521">the</span> <span m="593001">same</span> <span m="593482">manner</span>
  <span m="593963">with</span> <span m="594444">the</span> <span m="594924">SUBC</span>
  <span m="595405">instruction</span> <span m="595886">and</span> <span m="596367">the</span>
  <span m="596847">first</span> <span m="597328">LD</span> <span m="597809">instruction.</span></p><p><span
  m="598290">Again</span> <span m="598584">we</span> <span m="598879">get</span> <span
  m="599174">cache</span> <span m="599468">misses</span> <span m="599763">for</span>
  <span m="600058">each</span> <span m="600352">of</span> <span m="600647">those</span>
  <span m="600942">instructions</span> <span m="601237">and</span> <span m="601531">that</span>
  <span m="601826">in</span> <span m="602121">turn</span> <span m="602415">causes</span>
  <span m="602710">us</span> <span m="603005">to</span> <span m="603300">load</span>
  <span m="603790">those</span> <span m="604280">instructions</span> <span m="604770">into</span>
  <span m="605260">our</span> <span m="605750">cache.</span></p><p><span m="606240">Now,</span>
  <span m="606728">we</span> <span m="607217">are</span> <span m="607706">ready</span>
  <span m="608195">to</span> <span m="608684">execute</span> <span m="609173">our</span>
  <span m="609662">first</span> <span m="610151">load</span> <span m="610640">operation.</span></p><p><span
  m="611129">This</span> <span m="611731">operation</span> <span m="612334">wants</span>
  <span m="612936">to</span> <span m="613539">load</span> <span m="614141">A[15]</span>
  <span m="614744">into</span> <span m="615346">R1.</span></p><p><span m="615949">Because</span>
  <span m="616371">the</span> <span m="616794">beginning</span> <span m="617217">of</span>
  <span m="617639">array</span> <span m="618062">A</span> <span m="618485">is</span>
  <span m="618907">at</span> <span m="619330">address</span> <span m="619753">0,</span>
  <span m="620175">then</span> <span m="620598">A[15]</span> <span m="621021">maps</span>
  <span m="621443">to</span> <span m="621866">line</span> <span m="622289">15</span>
  <span m="622711">of</span> <span m="623134">our</span> <span m="623557">cache.</span></p><p><span
  m="623980">Since</span> <span m="624272">we</span> <span m="624564">have</span>
  <span m="624856">not</span> <span m="625149">yet</span> <span m="625441">loaded</span>
  <span m="625733">anything</span> <span m="626026">into</span> <span m="626318">line</span>
  <span m="626610">15</span> <span m="626902">of</span> <span m="627195">our</span>
  <span m="627487">cache,</span> <span m="627779">this</span> <span m="628072">means</span>
  <span m="628364">that</span> <span m="628656">our</span> <span m="628949">first</span>
  <span m="629520">data</span> <span m="630092">access</span> <span m="630664">is</span>
  <span m="631235">a</span> <span m="631807">miss.</span></p><p><span m="632379">We</span>
  <span m="632774">continue</span> <span m="633170">with</span> <span m="633566">the</span>
  <span m="633961">second</span> <span m="634357">load</span> <span m="634753">instruction.</span></p><p><span
  m="635149">This</span> <span m="635411">instruction</span> <span m="635674">is</span>
  <span m="635936">not</span> <span m="636199">yet</span> <span m="636462">in</span>
  <span m="636724">the</span> <span m="636987">cache,</span> <span m="637250">so</span>
  <span m="637512">we</span> <span m="637775">get</span> <span m="638037">a</span>
  <span m="638300">cache</span> <span m="638563">miss</span> <span m="638825">and</span>
  <span m="639088">then</span> <span m="639351">load</span> <span m="639613">it</span>
  <span m="639876">into</span> <span m="640139">line</span> <span m="640577">4</span>
  <span m="641015">of</span> <span m="641453">our</span> <span m="641891">cache.</span></p><p><span
  m="642330">We</span> <span m="642821">then</span> <span m="643313">try</span> <span
  m="643804">to</span> <span m="644296">access</span> <span m="644787">B[15].</span></p><p><span
  m="645279">B[15]</span> <span m="645716">corresponds</span> <span m="646153">to</span>
  <span m="646590">the</span> <span m="647027">same</span> <span m="647464">piece</span>
  <span m="647901">of</span> <span m="648338">data</span> <span m="648775">as</span>
  <span m="649212">A[15],</span> <span m="649649">so</span> <span m="650086">this</span>
  <span m="650523">data</span> <span m="650960">access</span> <span m="651397">is</span>
  <span m="651834">already</span> <span m="652271">in</span> <span m="652709">the</span>
  <span m="653233">cache</span> <span m="653757">thus</span> <span m="654281">resulting</span>
  <span m="654805">in</span> <span m="655329">a</span> <span m="655853">data</span>
  <span m="656377">hit</span> <span m="656901">for</span> <span m="657425">B[15].</span></p><p><span
  m="657950">So</span> <span m="658387">far</span> <span m="658825">we</span> <span
  m="659263">have</span> <span m="659701">gotten</span> <span m="660139">5</span>
  <span m="660577">instruction</span> <span m="661015">misses,</span> <span m="661453">1</span>
  <span m="661891">data</span> <span m="662329">miss</span> <span m="662767">and</span>
  <span m="663205">1</span> <span m="663643">data</span> <span m="664081">hit.</span></p><p><span
  m="664519">Next</span> <span m="665102">we</span> <span m="665686">need</span> <span
  m="666270">to</span> <span m="666854">access</span> <span m="667437">the</span>
  <span m="668021">BNE</span> <span m="668605">instruction.</span></p><p><span m="669189">Once</span>
  <span m="669540">again</span> <span m="669892">we</span> <span m="670244">get</span>
  <span m="670596">a</span> <span m="670948">cache</span> <span m="671299">miss</span>
  <span m="671651">which</span> <span m="672003">results</span> <span m="672355">in</span>
  <span m="672707">loading</span> <span m="673059">the</span> <span m="673410">BNE</span>
  <span m="673762">instruction</span> <span m="674114">into</span> <span m="674466">line</span>
  <span m="674818">5</span> <span m="675170">of</span> <span m="675786">our</span>
  <span m="676402">cache.</span></p><p><span m="677019">The</span> <span m="677586">inner</span>
  <span m="678153">loop</span> <span m="678720">is</span> <span m="679288">now</span>
  <span m="679855">repeated</span> <span m="680422">with</span> <span m="680989">R0</span>
  <span m="681557">=</span> <span m="682124">60</span> <span m="682691">which</span>
  <span m="683259">corresponds</span> <span m="683826">to</span> <span m="684393">element</span>
  <span m="684960">14</span> <span m="685528">of</span> <span m="686095">the</span>
  <span m="686662">arrays.</span></p><p><span m="687230">This</span> <span m="687552">time</span>
  <span m="687874">through</span> <span m="688196">the</span> <span m="688519">loop,</span>
  <span m="688841">all</span> <span m="689163">the</span> <span m="689486">instructions</span>
  <span m="689808">are</span> <span m="690130">already</span> <span m="690452">in</span>
  <span m="690775">the</span> <span m="691097">cache</span> <span m="691419">and</span>
  <span m="691742">result</span> <span m="692064">in</span> <span m="692386">instruction</span>
  <span m="692709">hits.</span></p><p><span m="694069">A[14]</span> <span m="694416">which</span>
  <span m="694763">maps</span> <span m="695110">to</span> <span m="695457">line</span>
  <span m="695804">14</span> <span m="696151">of</span> <span m="696498">our</span>
  <span m="696845">cache</span> <span m="697192">results</span> <span m="697539">in</span>
  <span m="697886">a</span> <span m="698233">data</span> <span m="698580">miss</span>
  <span m="698927">because</span> <span m="699274">it</span> <span m="699621">is</span>
  <span m="699968">not</span> <span m="700315">yet</span> <span m="700662">present</span>
  <span m="701010">in</span> <span m="701486">our</span> <span m="701963">cache.</span></p><p><span
  m="702440">So</span> <span m="703095">we</span> <span m="703751">bring</span> <span
  m="704406">A[14]</span> <span m="705062">into</span> <span m="705717">the</span>
  <span m="706373">cache.</span></p><p><span m="707029">Then</span> <span m="707386">as</span>
  <span m="707743">before,</span> <span m="708100">when</span> <span m="708457">we</span>
  <span m="708815">try</span> <span m="709172">to</span> <span m="709529">access</span>
  <span m="709886">B[14],</span> <span m="710244">we</span> <span m="710601">get</span>
  <span m="710958">a</span> <span m="711315">data</span> <span m="711672">hit</span>
  <span m="712030">because</span> <span m="712387">it</span> <span m="712744">corresponds</span>
  <span m="713101">to</span> <span m="713459">the</span> <span m="714069">same</span>
  <span m="714679">piece</span> <span m="715289">of</span> <span m="715899">data</span>
  <span m="716509">as</span> <span m="717119">A[14].</span></p><p><span m="717730">So</span>
  <span m="718109">in</span> <span m="718488">total,</span> <span m="718867">we</span>
  <span m="719247">have</span> <span m="719626">now</span> <span m="720005">seen</span>
  <span m="720385">6</span> <span m="720764">instruction</span> <span m="721143">misses</span>
  <span m="721522">and</span> <span m="721902">2</span> <span m="722281">data</span>
  <span m="722660">misses.</span></p><p><span m="723040">The</span> <span m="723677">rest</span>
  <span m="724315">of</span> <span m="724953">the</span> <span m="725590">accesses</span>
  <span m="726228">have</span> <span m="726866">all</span> <span m="727503">been</span>
  <span m="728141">hits.</span></p><p><span m="728779">This</span> <span m="729136">process</span>
  <span m="729493">repeats</span> <span m="729850">itself</span> <span m="730207">with</span>
  <span m="730564">a</span> <span m="730921">data</span> <span m="731278">miss</span>
  <span m="731635">for</span> <span m="731993">array</span> <span m="732350">element</span>
  <span m="732707">A[i],</span> <span m="733064">and</span> <span m="733421">a</span>
  <span m="733778">data</span> <span m="734135">hit</span> <span m="734492">for</span>
  <span m="734850">array</span> <span m="735282">element</span> <span m="735715">B[i]</span>
  <span m="736148">until</span> <span m="736581">we</span> <span m="737014">get</span>
  <span m="737447">to</span> <span m="737880">A[5]</span> <span m="738313">which</span>
  <span m="738745">actually</span> <span m="739178">results</span> <span m="739611">in</span>
  <span m="740044">a</span> <span m="740477">hit</span> <span m="740910">because</span>
  <span m="741343">it</span> <span m="741776">corresponds</span> <span m="742209">to</span>
  <span m="742608">the</span> <span m="743007">location</span> <span m="743407">in</span>
  <span m="743806">memory</span> <span m="744206">that</span> <span m="744605">holds</span>
  <span m="745005">the</span> <span m="745404">BNE(R0,</span> <span m="745804">R)</span>
  <span m="746203">instruction</span> <span m="746603">which</span> <span m="747002">is</span>
  <span m="747402">already</span> <span m="747801">in</span> <span m="748201">the</span>
  <span m="748600">cache</span> <span m="749000">at</span> <span m="749696">line</span>
  <span m="750392">5.</span></p><p><span m="751089">From</span> <span m="751580">then</span>
  <span m="752072">on</span> <span m="752564">the</span> <span m="753056">remaining</span>
  <span m="753548">data</span> <span m="754039">accesses</span> <span m="754531">all</span>
  <span m="755023">result</span> <span m="755515">in</span> <span m="756007">hits.</span></p><p><span
  m="756499">At</span> <span m="756813">this</span> <span m="757127">point</span>
  <span m="757441">we</span> <span m="757755">have</span> <span m="758069">completed</span>
  <span m="758383">the</span> <span m="758697">inner</span> <span m="759011">loop</span>
  <span m="759325">and</span> <span m="759639">proceed</span> <span m="759953">to</span>
  <span m="760267">the</span> <span m="760581">remaining</span> <span m="760895">instructions</span>
  <span m="761209">in</span> <span m="761699">the</span> <span m="762189">outer</span>
  <span m="762679">loop.</span></p><p><span m="763170">These</span> <span m="763670">instructions</span>
  <span m="764171">are</span> <span m="764672">the</span> <span m="765173">second</span>
  <span m="765674">SUBC</span> <span m="766174">and</span> <span m="766675">the</span>
  <span m="767176">second</span> <span m="767677">BNE</span> <span m="768178">instructions.</span></p><p><span
  m="768679">These</span> <span m="769047">correspond</span> <span m="769415">to</span>
  <span m="769784">the</span> <span m="770152">data</span> <span m="770521">that</span>
  <span m="770889">is</span> <span m="771257">in</span> <span m="771626">lines</span>
  <span m="771994">6</span> <span m="772363">and</span> <span m="772731">7</span>
  <span m="773100">of</span> <span m="773468">the</span> <span m="773836">cache</span>
  <span m="774205">thus</span> <span m="774573">resulting</span> <span m="774942">in</span>
  <span m="775310">hits.</span></p><p><span m="775679">The</span> <span m="776107">loop</span>
  <span m="776536">then</span> <span m="776965">repeats</span> <span m="777393">itself</span>
  <span m="777822">1000</span> <span m="778251">times</span> <span m="778680">but</span>
  <span m="779108">each</span> <span m="779537">time</span> <span m="779966">through</span>
  <span m="780395">all</span> <span m="780823">the</span> <span m="781252">instructions</span>
  <span m="781681">and</span> <span m="782110">all</span> <span m="782499">the</span>
  <span m="782888">data</span> <span m="783277">is</span> <span m="783666">in</span>
  <span m="784056">the</span> <span m="784445">cache</span> <span m="784834">so</span>
  <span m="785223">they</span> <span m="785613">all</span> <span m="786002">result</span>
  <span m="786391">in</span> <span m="786780">hits.</span></p><p><span m="787170">So</span>
  <span m="787458">the</span> <span m="787747">total</span> <span m="788036">number</span>
  <span m="788325">of</span> <span m="788613">misses</span> <span m="788902">that</span>
  <span m="789191">we</span> <span m="789480">get</span> <span m="789768">when</span>
  <span m="790057">executing</span> <span m="790346">this</span> <span m="790635">benchmark</span>
  <span m="790923">on</span> <span m="791212">a</span> <span m="791501">direct</span>
  <span m="791790">mapped</span> <span m="792579">cache</span> <span m="793369">is</span>
  <span m="794159">16.</span></p><p><span m="794949">These</span> <span m="795246">are</span>
  <span m="795544">known</span> <span m="795841">as</span> <span m="796139">compulsory</span>
  <span m="796436">misses</span> <span m="796734">which</span> <span m="797031">are</span>
  <span m="797329">misses</span> <span m="797626">that</span> <span m="797924">occur</span>
  <span m="798221">when</span> <span m="798519">you</span> <span m="798816">are</span>
  <span m="799114">first</span> <span m="799411">loading</span> <span m="799709">the</span>
  <span m="800287">data</span> <span m="800865">into</span> <span m="801443">your</span>
  <span m="802021">cache.</span></p><p><span m="802600">Recall</span> <span m="802992">that</span>
  <span m="803384">the</span> <span m="803776">direct</span> <span m="804168">mapped</span>
  <span m="804560">cache</span> <span m="804952">has</span> <span m="805344">one</span>
  <span m="805736">set</span> <span m="806128">of</span> <span m="806520">64</span>
  <span m="806912">lines</span> <span m="807304">in</span> <span m="807696">the</span>
  <span m="808088">cache.</span></p><p><span m="808480">The</span> <span m="808933">2-way</span>
  <span m="809386">set</span> <span m="809839">associative</span> <span m="810292">has</span>
  <span m="810745">2</span> <span m="811198">sets</span> <span m="811651">of</span>
  <span m="812105">32</span> <span m="812558">lines</span> <span m="813011">each,</span>
  <span m="813464">and</span> <span m="813917">the</span> <span m="814370">4-way</span>
  <span m="814823">set</span> <span m="815276">associative</span> <span m="815730">has</span>
  <span m="816285">4</span> <span m="816841">sets</span> <span m="817396">of</span>
  <span m="817952">16</span> <span m="818507">lines</span> <span m="819063">each.</span></p><p><span
  m="819619">Since</span> <span m="820021">only</span> <span m="820424">16</span>
  <span m="820827">lines</span> <span m="821229">are</span> <span m="821632">required</span>
  <span m="822035">to</span> <span m="822438">fit</span> <span m="822840">all</span>
  <span m="823243">the</span> <span m="823646">instructions</span> <span m="824049">and</span>
  <span m="824451">data</span> <span m="824854">associated</span> <span m="825257">with</span>
  <span m="825660">this</span> <span m="826073">benchmark,</span> <span m="826486">this</span>
  <span m="826899">means</span> <span m="827312">that</span> <span m="827725">effectively,</span>
  <span m="828138">only</span> <span m="828551">one</span> <span m="828964">set</span>
  <span m="829377">will</span> <span m="829790">be</span> <span m="830203">used</span>
  <span m="830616">in</span> <span m="831029">the</span> <span m="831442">set</span>
  <span m="831855">associative</span> <span m="832269">caches,</span> <span m="832747">and</span>
  <span m="833226">because</span> <span m="833705">even</span> <span m="834183">in</span>
  <span m="834662">the</span> <span m="835141">4-way</span> <span m="835619">set</span>
  <span m="836098">associative</span> <span m="836577">cache</span> <span m="837055">there</span>
  <span m="837534">are</span> <span m="838013">16</span> <span m="838491">lines,</span>
  <span m="838970">that</span> <span m="839449">means</span> <span m="839724">that</span>
  <span m="840000">once</span> <span m="840275">the</span> <span m="840551">data</span>
  <span m="840827">is</span> <span m="841102">loaded</span> <span m="841378">into</span>
  <span m="841653">the</span> <span m="841929">cache</span> <span m="842205">it</span>
  <span m="842480">does</span> <span m="842756">not</span> <span m="843031">need</span>
  <span m="843307">to</span> <span m="843583">be</span> <span m="843858">replaced</span>
  <span m="844134">with</span> <span m="844410">other</span> <span m="844821">data</span>
  <span m="845233">so</span> <span m="845645">after</span> <span m="846057">the</span>
  <span m="846469">first</span> <span m="846880">miss</span> <span m="847292">per</span>
  <span m="847704">line,</span> <span m="848116">the</span> <span m="848528">remaining</span>
  <span m="848939">accesses</span> <span m="849351">in</span> <span m="849763">the</span>
  <span m="850175">entire</span> <span m="850587">benchmark</span> <span m="850999">will</span>
  <span m="851616">be</span> <span m="852233">hits.</span></p><p><span m="852850">So</span>
  <span m="853271">the</span> <span m="853693">total</span> <span m="854115">number</span>
  <span m="854536">of</span> <span m="854958">misses</span> <span m="855380">in</span>
  <span m="855801">the</span> <span m="856223">2-way</span> <span m="856645">and</span>
  <span m="857067">4-way</span> <span m="857488">set</span> <span m="857910">associative</span>
  <span m="858332">caches</span> <span m="858753">is</span> <span m="859175">also</span>
  <span m="859597">16.</span></p>
type: course
uid: accb5c4acc6b10ac6cc887fd35462aef

---
None