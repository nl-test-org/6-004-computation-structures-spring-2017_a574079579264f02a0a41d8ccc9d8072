---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 6XV3uLfKzog
  parent_uid: 7f470568b98ce58d9414dfd7e605a765
  title: Video-YouTube-Stream
  type: Video
  uid: dbdfcb0d5dbf22413c46a6ae95de84e8
- id: 3Play-3Play YouTube id-Stream
  media_location: 6XV3uLfKzog
  parent_uid: 7f470568b98ce58d9414dfd7e605a765
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 9bc622cce6055e5e2a3411ce31b870ab
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_15-02-03_300k.mp4
  parent_uid: 7f470568b98ce58d9414dfd7e605a765
  title: Video-Internet Archive-MP4
  type: Video
  uid: ab81a3af5bdea282cd17a6492aaa77ec
- id: 6XV3uLfKzog.srt
  parent_uid: 7f470568b98ce58d9414dfd7e605a765
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v3/data-hazards-14-37-/6XV3uLfKzog.srt
  title: 3play caption file
  type: null
  uid: 0cd046916f57187f16a244c2fb67599f
- id: 6XV3uLfKzog.pdf
  parent_uid: 7f470568b98ce58d9414dfd7e605a765
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v3/data-hazards-14-37-/6XV3uLfKzog.pdf
  title: 3play pdf file
  type: null
  uid: e8d0d9b8305f1e03aa58c21e91260438
- id: Caption-3Play YouTube id-SRT
  parent_uid: 7f470568b98ce58d9414dfd7e605a765
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: dfc8bc12d6a869a3dcdad2b302987faf
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 7f470568b98ce58d9414dfd7e605a765
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 28bf2ff88aa3f3ebdd4f649b6d77a373
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/6XV3uLfKzog/default.jpg
  parent_uid: 7f470568b98ce58d9414dfd7e605a765
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 6d28fc171118369f50263ebd835c470f
inline_embed_id: 8753961datahazards14374251827
layout: video
order_index: null
parent_uid: 809fa8983963a8c14f3aff6d5c931c56
related_resources_text: ''
short_url: data-hazards-14-37-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v3/data-hazards-14-37-
template_type: Embed
title: Data Hazards
transcript: <p><span m="170">The</span> <span m="528">data</span> <span m="887">path</span>
  <span m="1245">diagram</span> <span m="1604">isn't</span> <span m="1962">all</span>
  <span m="2321">that</span> <span m="2680">useful</span> <span m="3038">in</span>
  <span m="3397">diagramming</span> <span m="3755">the</span> <span m="4114">pipelined</span>
  <span m="4472">execution</span> <span m="4831">of</span> <span m="5190">an</span>
  <span m="5524">instruction</span> <span m="5858">sequence</span> <span m="6193">since</span>
  <span m="6527">we</span> <span m="6861">need</span> <span m="7196">a</span> <span
  m="7530">new</span> <span m="7865">copy</span> <span m="8199">of</span> <span m="8533">the</span>
  <span m="8868">diagram</span> <span m="9202">for</span> <span m="9536">each</span>
  <span m="9871">clock</span> <span m="10205">cycle.</span></p><p><span m="10540">A</span>
  <span m="11010">more</span> <span m="11480">compact</span> <span m="11950">and</span>
  <span m="12420">easier-to-read</span> <span m="12890">diagram</span> <span m="13360">of</span>
  <span m="13830">pipelined</span> <span m="14300">execution</span> <span m="14770">is</span>
  <span m="15240">provided</span> <span m="15710">by</span> <span m="16180">the</span>
  <span m="16650">pipeline</span> <span m="17029">diagrams</span> <span m="17408">we</span>
  <span m="17787">met</span> <span m="18166">back</span> <span m="18545">in</span>
  <span m="18924">Part</span> <span m="19303">1</span> <span m="19682">of</span> <span
  m="20061">the</span> <span m="20440">course.</span></p><p><span m="20820">There's</span>
  <span m="21252">one</span> <span m="21684">row</span> <span m="22116">in</span>
  <span m="22548">the</span> <span m="22981">diagram</span> <span m="23413">for</span>
  <span m="23845">each</span> <span m="24277">pipeline</span> <span m="24710">stage</span>
  <span m="25142">and</span> <span m="25574">one</span> <span m="26006">column</span>
  <span m="26438">for</span> <span m="26871">each</span> <span m="27303">cycle</span>
  <span m="27735">of</span> <span m="28167">execution.</span></p><p><span m="28600">Entries</span>
  <span m="28991">in</span> <span m="29383">the</span> <span m="29775">table</span>
  <span m="30167">show</span> <span m="30559">which</span> <span m="30951">instruction</span>
  <span m="31343">is</span> <span m="31735">in</span> <span m="32127">each</span>
  <span m="32519">pipeline</span> <span m="32911">stage</span> <span m="33303">at</span>
  <span m="33695">each</span> <span m="34087">cycle.</span></p><p><span m="34479">In</span>
  <span m="34812">normal</span> <span m="35146">operation,</span> <span m="35480">a</span>
  <span m="35814">particular</span> <span m="36148">instruction</span> <span m="36482">moves</span>
  <span m="36815">diagonally</span> <span m="37149">through</span> <span m="37483">the</span>
  <span m="37817">diagram</span> <span m="38151">as</span> <span m="38485">it</span>
  <span m="38819">proceeds</span> <span m="39499">through</span> <span m="40179">the</span>
  <span m="40859">five</span> <span m="41539">pipeline</span> <span m="42219">stages.</span></p><p><span
  m="42899">To</span> <span m="43214">understand</span> <span m="43529">data</span>
  <span m="43845">hazards,</span> <span m="44160">let's</span> <span m="44475">first</span>
  <span m="44791">remind</span> <span m="45106">ourselves</span> <span m="45421">of</span>
  <span m="45737">when</span> <span m="46052">the</span> <span m="46367">register</span>
  <span m="46683">file</span> <span m="46998">is</span> <span m="47313">read</span>
  <span m="47629">and</span> <span m="48122">written</span> <span m="48615">for</span>
  <span m="49109">a</span> <span m="49602">particular</span> <span m="50095">instruction.</span></p><p><span
  m="50589">Register</span> <span m="50893">reads</span> <span m="51198">happen</span>
  <span m="51503">when</span> <span m="51807">the</span> <span m="52112">instruction</span>
  <span m="52417">is</span> <span m="52722">in</span> <span m="53026">the</span> <span
  m="53331">RF</span> <span m="53636">stage,</span> <span m="53941">i.e.,</span> <span
  m="54245">when</span> <span m="54550">we're</span> <span m="54855">reading</span>
  <span m="55160">the</span> <span m="56222">instruction's</span> <span m="57284">register</span>
  <span m="58346">operands.</span></p><p><span m="59409">Register</span> <span m="59699">writes</span>
  <span m="59990">happen</span> <span m="60280">at</span> <span m="60571">the</span>
  <span m="60861">end</span> <span m="61152">of</span> <span m="61443">the</span>
  <span m="61733">cycle</span> <span m="62024">when</span> <span m="62314">the</span>
  <span m="62605">instruction</span> <span m="62896">is</span> <span m="63186">in</span>
  <span m="63477">the</span> <span m="63767">WB</span> <span m="64058">stage.</span></p><p><span
  m="64349">For</span> <span m="64737">example,</span> <span m="65126">for</span>
  <span m="65515">the</span> <span m="65904">first</span> <span m="66293">LD</span>
  <span m="66682">instruction,</span> <span m="67071">we</span> <span m="67460">read</span>
  <span m="67848">R1</span> <span m="68237">during</span> <span m="68626">cycle</span>
  <span m="69015">2</span> <span m="69404">and</span> <span m="69793">write</span>
  <span m="70182">R2</span> <span m="70571">at</span> <span m="70960">the</span> <span
  m="71561">end</span> <span m="72163">of</span> <span m="72765">cycle</span> <span
  m="73367">5.</span></p><p><span m="73969">Or</span> <span m="74414">consider</span>
  <span m="74860">the</span> <span m="75305">register</span> <span m="75751">file</span>
  <span m="76196">operations</span> <span m="76642">in</span> <span m="77087">cycle</span>
  <span m="77533">6:</span> <span m="77979">we're</span> <span m="78338">reading</span>
  <span m="78698">R12</span> <span m="79057">and</span> <span m="79417">R13</span>
  <span m="79776">for</span> <span m="80136">the</span> <span m="80495">MUL</span>
  <span m="80855">instruction</span> <span m="81214">in</span> <span m="81574">the</span>
  <span m="81933">RF</span> <span m="82293">stage,</span> <span m="82652">and</span>
  <span m="83012">writing</span> <span m="83371">R4</span> <span m="83731">at</span>
  <span m="84090">the</span> <span m="84450">end</span> <span m="84810">of</span>
  <span m="85202">the</span> <span m="85595">cycle</span> <span m="85988">for</span>
  <span m="86380">the</span> <span m="86773">LD</span> <span m="87166">instruction</span>
  <span m="87559">in</span> <span m="87951">the</span> <span m="88344">WB</span> <span
  m="88737">stage.</span></p><p><span m="89130">Okay,</span> <span m="89469">now</span>
  <span m="89809">let's</span> <span m="90149">see</span> <span m="90489">what</span>
  <span m="90829">happens</span> <span m="91169">when</span> <span m="91509">there</span>
  <span m="91849">are</span> <span m="92189">data</span> <span m="92529">hazards.</span></p><p><span
  m="92869">In</span> <span m="93235">this</span> <span m="93602">instruction</span>
  <span m="93969">sequence,</span> <span m="94335">the</span> <span m="94702">ADDC</span>
  <span m="95069">instruction</span> <span m="95435">writes</span> <span m="95802">its</span>
  <span m="96169">result</span> <span m="96535">in</span> <span m="96902">R2,</span>
  <span m="97269">which</span> <span m="97635">is</span> <span m="98002">immediately</span>
  <span m="98369">read</span> <span m="98922">by</span> <span m="99475">the</span>
  <span m="100029">following</span> <span m="100582">SUBC</span> <span m="101135">instruction.</span></p><p><span
  m="101689">Correct</span> <span m="101991">execution</span> <span m="102294">of</span>
  <span m="102597">the</span> <span m="102900">SUBC</span> <span m="103203">instruction</span>
  <span m="103506">clearly</span> <span m="103809">depends</span> <span m="104111">on</span>
  <span m="104414">the</span> <span m="104717">results</span> <span m="105020">of</span>
  <span m="105323">the</span> <span m="105626">ADDC</span> <span m="105929">instruction.</span></p><p><span
  m="107280">This</span> <span m="107885">what</span> <span m="108491">we'd</span>
  <span m="109097">call</span> <span m="109702">a</span> <span m="110308">read-after-write</span>
  <span m="110914">dependency.</span></p><p><span m="111520">This</span> <span m="111939">pipeline</span>
  <span m="112358">diagram</span> <span m="112777">shows</span> <span m="113196">the</span>
  <span m="113615">cycle-by-cycle</span> <span m="114034">execution</span> <span m="114454">where</span>
  <span m="114873">we've</span> <span m="115292">circled</span> <span m="115711">the</span>
  <span m="116130">cycles</span> <span m="116549">during</span> <span m="116969">which</span>
  <span m="117476">ADDC</span> <span m="117984">writes</span> <span m="118491">R2</span>
  <span m="118999">and</span> <span m="119507">SUBC</span> <span m="120014">reads</span>
  <span m="120522">R2.</span></p><p><span m="121030">Oops!</span></p><p><span m="122030">ADDC</span>
  <span m="122349">doesn't</span> <span m="122668">write</span> <span m="122988">R2</span>
  <span m="123307">until</span> <span m="123627">the</span> <span m="123946">end</span>
  <span m="124266">of</span> <span m="124585">cycle</span> <span m="124905">5,</span>
  <span m="125224">but</span> <span m="125544">SUBC</span> <span m="125863">is</span>
  <span m="126183">trying</span> <span m="126502">to</span> <span m="126822">read</span>
  <span m="127141">the</span> <span m="127461">R2</span> <span m="127780">value</span>
  <span m="128100">in</span> <span m="128543">cycle</span> <span m="128986">3.</span></p><p><span
  m="129430">The</span> <span m="129799">value</span> <span m="130168">in</span> <span
  m="130538">R2</span> <span m="130907">in</span> <span m="131276">the</span> <span
  m="131646">register</span> <span m="132015">file</span> <span m="132385">in</span>
  <span m="132754">cycle</span> <span m="133123">3</span> <span m="133493">doesn't</span>
  <span m="133862">yet</span> <span m="134232">reflect</span> <span m="134601">the</span>
  <span m="134970">execution</span> <span m="135340">of</span> <span m="135709">the</span>
  <span m="136079">ADDC</span> <span m="137034">instruction.</span></p><p><span m="137989">So</span>
  <span m="138466">as</span> <span m="138943">things</span> <span m="139420">stand</span>
  <span m="139897">the</span> <span m="140374">pipeline</span> <span m="140851">would</span>
  <span m="141328">*not*</span> <span m="141805">correctly</span> <span m="142282">execute</span>
  <span m="142759">this</span> <span m="143236">instruction</span> <span m="143713">sequence.</span></p><p><span
  m="144190">This</span> <span m="144734">instruction</span> <span m="145279">sequence</span>
  <span m="145824">has</span> <span m="146369">triggered</span> <span m="146914">a</span>
  <span m="147459">data</span> <span m="148004">hazard.</span></p><p><span m="148549">We</span>
  <span m="148917">want</span> <span m="149285">the</span> <span m="149653">pipelined</span>
  <span m="150021">CPU</span> <span m="150389">to</span> <span m="150757">generate</span>
  <span m="151125">the</span> <span m="151493">same</span> <span m="151861">program</span>
  <span m="152229">results</span> <span m="152597">as</span> <span m="152965">the</span>
  <span m="153333">unpipelined</span> <span m="153701">CPU,</span> <span m="154070">so</span>
  <span m="154406">we'll</span> <span m="154742">need</span> <span m="155078">to</span>
  <span m="155415">figure</span> <span m="155751">out</span> <span m="156087">a</span>
  <span m="156423">fix.</span></p><p><span m="156760">There</span> <span m="157149">are</span>
  <span m="157538">three</span> <span m="157927">general</span> <span m="158316">strategies</span>
  <span m="158705">we</span> <span m="159095">can</span> <span m="159484">pursue</span>
  <span m="159873">to</span> <span m="160262">fix</span> <span m="160651">pipeline</span>
  <span m="161040">hazards.</span></p><p><span m="161430">Any</span> <span m="161732">of</span>
  <span m="162034">the</span> <span m="162337">techniques</span> <span m="162639">will</span>
  <span m="162942">work,</span> <span m="163244">but</span> <span m="163547">as</span>
  <span m="163849">we'll</span> <span m="164151">see</span> <span m="164454">they</span>
  <span m="164756">have</span> <span m="165059">different</span> <span m="165361">tradeoffs</span>
  <span m="165664">for</span> <span m="165966">instruction</span> <span m="166269">throughput</span>
  <span m="166989">and</span> <span m="167709">circuit</span> <span m="168429">complexity.</span></p><p><span
  m="169150">The</span> <span m="169435">first</span> <span m="169721">strategy</span>
  <span m="170006">is</span> <span m="170292">to</span> <span m="170578">stall</span>
  <span m="170863">instructions</span> <span m="171149">in</span> <span m="171435">the</span>
  <span m="171720">RF</span> <span m="172006">stage</span> <span m="172291">until</span>
  <span m="172577">the</span> <span m="172863">result</span> <span m="173148">they</span>
  <span m="173434">need</span> <span m="173720">has</span> <span m="174071">been</span>
  <span m="174422">written</span> <span m="174774">to</span> <span m="175125">the</span>
  <span m="175477">register</span> <span m="175828">file.</span></p><p><span m="176180">&quot;Stall&quot;</span>
  <span m="176490">means</span> <span m="176800">that</span> <span m="177110">we</span>
  <span m="177420">don't</span> <span m="177730">reload</span> <span m="178040">the</span>
  <span m="178350">instruction</span> <span m="178660">register</span> <span m="178970">at</span>
  <span m="179280">the</span> <span m="179590">end</span> <span m="179900">of</span>
  <span m="180210">the</span> <span m="180520">cycle,</span> <span m="180830">so</span>
  <span m="181140">we'll</span> <span m="181450">try</span> <span m="181815">to</span>
  <span m="182180">execute</span> <span m="182545">the</span> <span m="182910">same</span>
  <span m="183275">instruction</span> <span m="183640">in</span> <span m="184005">the</span>
  <span m="184370">next</span> <span m="184735">cycle.</span></p><p><span m="185100">If</span>
  <span m="185358">we</span> <span m="185617">stall</span> <span m="185876">one</span>
  <span m="186134">pipeline</span> <span m="186393">stage,</span> <span m="186652">all</span>
  <span m="186910">earlier</span> <span m="187169">stages</span> <span m="187428">must</span>
  <span m="187686">also</span> <span m="187945">be</span> <span m="188204">stalled</span>
  <span m="188462">since</span> <span m="188721">they</span> <span m="188980">are</span>
  <span m="189239">blocked</span> <span m="189967">by</span> <span m="190695">the</span>
  <span m="191423">stalled</span> <span m="192151">instruction.</span></p><p><span
  m="192879">If</span> <span m="193254">an</span> <span m="193629">instruction</span>
  <span m="194004">is</span> <span m="194379">stalled</span> <span m="194754">in</span>
  <span m="195129">the</span> <span m="195504">RF</span> <span m="195879">stage,</span>
  <span m="196254">then</span> <span m="196629">the</span> <span m="197004">IF</span>
  <span m="197379">stage</span> <span m="197754">is</span> <span m="198129">also</span>
  <span m="198504">stalled.</span></p><p><span m="198879">Stalling</span> <span m="199312">will</span>
  <span m="199745">always</span> <span m="200179">work,</span> <span m="200612">but</span>
  <span m="201045">has</span> <span m="201479">a</span> <span m="201912">negative</span>
  <span m="202345">impact</span> <span m="202779">on</span> <span m="203212">instruction</span>
  <span m="203645">throughput.</span></p><p><span m="204079">Stall</span> <span m="204554">for</span>
  <span m="205030">too</span> <span m="205506">many</span> <span m="205981">cycles</span>
  <span m="206457">and</span> <span m="206933">you'll</span> <span m="207409">loose</span>
  <span m="207884">the</span> <span m="208360">performance</span> <span m="208836">advantages</span>
  <span m="209311">of</span> <span m="209787">pipelined</span> <span m="210263">execution!</span></p><p><span
  m="210739">The</span> <span m="211048">second</span> <span m="211357">strategy</span>
  <span m="211667">is</span> <span m="211976">to</span> <span m="212285">route</span>
  <span m="212595">the</span> <span m="212904">needed</span> <span m="213214">value</span>
  <span m="213523">to</span> <span m="213832">earlier</span> <span m="214142">pipeline</span>
  <span m="214451">stages</span> <span m="214760">as</span> <span m="215070">soon</span>
  <span m="215379">as</span> <span m="215689">its</span> <span m="216299">computed.</span></p><p><span
  m="216909">This</span> <span m="217513">called</span> <span m="218117">bypassing</span>
  <span m="218721">or</span> <span m="219325">forwarding.</span></p><p><span m="219930">As</span>
  <span m="220197">it</span> <span m="220464">turns</span> <span m="220731">out,</span>
  <span m="220998">the</span> <span m="221265">value</span> <span m="221533">we</span>
  <span m="221800">need</span> <span m="222067">often</span> <span m="222334">exists</span>
  <span m="222601">somewhere</span> <span m="222868">in</span> <span m="223136">the</span>
  <span m="223403">pipelined</span> <span m="223670">data</span> <span m="223937">path,</span>
  <span m="224204">it</span> <span m="224471">just</span> <span m="224739">hasn't</span>
  <span m="225184">been</span> <span m="225629">written</span> <span m="226074">yet</span>
  <span m="226519">to</span> <span m="226964">the</span> <span m="227409">register</span>
  <span m="227854">file.</span></p><p><span m="228299">If</span> <span m="228577">the</span>
  <span m="228856">value</span> <span m="229135">exists</span> <span m="229414">and</span>
  <span m="229693">can</span> <span m="229972">be</span> <span m="230251">forwarded</span>
  <span m="230530">to</span> <span m="230808">where</span> <span m="231087">it's</span>
  <span m="231366">needed,</span> <span m="231645">we</span> <span m="231924">won't</span>
  <span m="232203">need</span> <span m="232482">to</span> <span m="232761">stall.</span></p><p><span
  m="233040">We'll</span> <span m="233473">be</span> <span m="233906">able</span>
  <span m="234339">to</span> <span m="234772">use</span> <span m="235205">this</span>
  <span m="235638">strategy</span> <span m="236071">to</span> <span m="236505">avoid</span>
  <span m="236938">stalling</span> <span m="237371">on</span> <span m="237804">most</span>
  <span m="238237">types</span> <span m="238670">of</span> <span m="239103">data</span>
  <span m="239536">hazards.</span></p><p><span m="239970">The</span> <span m="240491">third</span>
  <span m="241013">strategy</span> <span m="241535">is</span> <span m="242056">called</span>
  <span m="242578">speculation.</span></p><p><span m="243100">We'll</span> <span m="243492">make</span>
  <span m="243885">an</span> <span m="244277">intelligent</span> <span m="244670">guess</span>
  <span m="245062">for</span> <span m="245455">the</span> <span m="245847">needed</span>
  <span m="246240">value</span> <span m="246632">and</span> <span m="247025">continue</span>
  <span m="247417">execution.</span></p><p><span m="247810">Once</span> <span m="248193">the</span>
  <span m="248577">actual</span> <span m="248961">value</span> <span m="249345">is</span>
  <span m="249728">determined,</span> <span m="250112">if</span> <span m="250496">we</span>
  <span m="250880">guessed</span> <span m="251263">correctly,</span> <span m="251647">we're</span>
  <span m="252031">all</span> <span m="252415">set.</span></p><p><span m="252799">If</span>
  <span m="253137">we</span> <span m="253476">guessed</span> <span m="253815">incorrectly,</span>
  <span m="254153">we</span> <span m="254492">have</span> <span m="254831">to</span>
  <span m="255170">back</span> <span m="255508">up</span> <span m="255847">execution</span>
  <span m="256186">and</span> <span m="256525">restart</span> <span m="256863">with</span>
  <span m="257202">the</span> <span m="257541">correct</span> <span m="257880">value.</span></p><p><span
  m="259170">Obviously</span> <span m="259573">speculation</span> <span m="259976">only</span>
  <span m="260380">makes</span> <span m="260783">sense</span> <span m="261186">if</span>
  <span m="261590">it's</span> <span m="261993">possible</span> <span m="262396">to</span>
  <span m="262800">make</span> <span m="263203">accurate</span> <span m="263606">guesses.</span></p><p><span
  m="264010">We'll</span> <span m="264383">be</span> <span m="264756">able</span>
  <span m="265129">to</span> <span m="265502">use</span> <span m="265875">this</span>
  <span m="266248">strategy</span> <span m="266621">to</span> <span m="266994">avoid</span>
  <span m="267367">stalling</span> <span m="267740">on</span> <span m="268113">control</span>
  <span m="268486">hazards.</span></p><p><span m="268860">Let's</span> <span m="269210">see</span>
  <span m="269561">how</span> <span m="269912">the</span> <span m="270262">first</span>
  <span m="270613">two</span> <span m="270964">strategies</span> <span m="271315">work</span>
  <span m="271665">when</span> <span m="272016">dealing</span> <span m="272367">with</span>
  <span m="272717">our</span> <span m="273068">data</span> <span m="273419">hazard.</span></p><p><span
  m="273770">Applying</span> <span m="274103">the</span> <span m="274437">stall</span>
  <span m="274770">strategy</span> <span m="275104">to</span> <span m="275437">our</span>
  <span m="275771">data</span> <span m="276104">hazard,</span> <span m="276438">we</span>
  <span m="276771">need</span> <span m="277105">to</span> <span m="277438">stall</span>
  <span m="277772">the</span> <span m="278105">SUBC</span> <span m="278439">instruction</span>
  <span m="278772">in</span> <span m="279106">the</span> <span m="279440">RF</span>
  <span m="279920">stage</span> <span m="280400">until</span> <span m="280880">the</span>
  <span m="281360">ADDC</span> <span m="281840">instruction</span> <span m="282320">writes</span>
  <span m="282800">its</span> <span m="283280">result</span> <span m="283760">in</span>
  <span m="284240">R2.</span></p><p><span m="284720">So</span> <span m="285036">in</span>
  <span m="285353">the</span> <span m="285670">pipeline</span> <span m="285986">diagram,</span>
  <span m="286303">SUBC</span> <span m="286620">is</span> <span m="286936">stalled</span>
  <span m="287253">three</span> <span m="287570">times</span> <span m="287886">in</span>
  <span m="288203">the</span> <span m="288520">RF</span> <span m="288836">stage</span>
  <span m="289153">until</span> <span m="289470">it</span> <span m="289786">can</span>
  <span m="290103">finally</span> <span m="290420">access</span> <span m="290927">the</span>
  <span m="291434">R2</span> <span m="291941">value</span> <span m="292449">from</span>
  <span m="292956">the</span> <span m="293463">register</span> <span m="293970">file</span>
  <span m="294478">in</span> <span m="294985">cycle</span> <span m="295492">6.</span></p><p><span
  m="296000">Whenever</span> <span m="296350">the</span> <span m="296700">RF</span>
  <span m="297050">stage</span> <span m="297400">is</span> <span m="297750">stalled,</span>
  <span m="298100">the</span> <span m="298450">IF</span> <span m="298800">stage</span>
  <span m="299150">is</span> <span m="299500">also</span> <span m="299850">stalled.</span></p><p><span
  m="300200">You</span> <span m="300497">can</span> <span m="300795">see</span> <span
  m="301092">that</span> <span m="301390">in</span> <span m="301687">the</span> <span
  m="301985">diagram</span> <span m="302282">too.</span></p><p><span m="302580">But</span>
  <span m="302943">when</span> <span m="303306">RF</span> <span m="303670">is</span>
  <span m="304033">stalled,</span> <span m="304396">what</span> <span m="304760">should</span>
  <span m="305123">the</span> <span m="305486">ALU</span> <span m="305850">stage</span>
  <span m="306213">do</span> <span m="306576">in</span> <span m="306940">the</span>
  <span m="307303">next</span> <span m="307666">cycle?</span></p><p><span m="308030">The</span>
  <span m="308527">RF</span> <span m="309025">stage</span> <span m="309523">hasn't</span>
  <span m="310021">finished</span> <span m="310519">its</span> <span m="311017">job</span>
  <span m="311515">and</span> <span m="312012">so</span> <span m="312510">can't</span>
  <span m="313008">pass</span> <span m="313506">along</span> <span m="314004">its</span>
  <span m="314502">instruction!</span></p><p><span m="315000">The</span> <span m="315298">solution</span>
  <span m="315596">is</span> <span m="315894">for</span> <span m="316192">the</span>
  <span m="316490">RF</span> <span m="316788">stage</span> <span m="317086">to</span>
  <span m="317385">make-up</span> <span m="317683">an</span> <span m="317981">innocuous</span>
  <span m="318279">instruction</span> <span m="318577">for</span> <span m="318875">the</span>
  <span m="319173">ALU</span> <span m="319471">stage,</span> <span m="319770">what's</span>
  <span m="320252">called</span> <span m="320734">a</span> <span m="321216">NOP</span>
  <span m="321698">instruction,</span> <span m="322181">short</span> <span m="322663">for</span>
  <span m="323145">&quot;no</span> <span m="323627">operation&quot;.</span></p><p><span
  m="324110">A</span> <span m="324446">NOP</span> <span m="324782">instruction</span>
  <span m="325118">has</span> <span m="325455">no</span> <span m="325791">effect</span>
  <span m="326127">on</span> <span m="326463">the</span> <span m="326800">CPU</span>
  <span m="327136">state,</span> <span m="327472">i.e.,</span> <span m="327808">it</span>
  <span m="328145">doesn't</span> <span m="328481">change</span> <span m="328817">the</span>
  <span m="329153">contents</span> <span m="329490">of</span> <span m="329888">the</span>
  <span m="330287">register</span> <span m="330685">file</span> <span m="331084">or</span>
  <span m="331482">main</span> <span m="331881">memory.</span></p><p><span m="332280">For</span>
  <span m="332738">example</span> <span m="333196">any</span> <span m="333654">OP-class</span>
  <span m="334112">or</span> <span m="334570">OPC-class</span> <span m="335028">instruction</span>
  <span m="335486">that</span> <span m="335944">has</span> <span m="336402">R31</span>
  <span m="336860">as</span> <span m="337318">its</span> <span m="337776">destination</span>
  <span m="338234">register</span> <span m="338692">is</span> <span m="339150">a</span>
  <span m="339745">NOP.</span></p><p><span m="340340">The</span> <span m="340736">NOPs</span>
  <span m="341132">introduced</span> <span m="341528">into</span> <span m="341924">the</span>
  <span m="342320">pipeline</span> <span m="342716">by</span> <span m="343112">the</span>
  <span m="343508">stalled</span> <span m="343904">RF</span> <span m="344300">stage</span>
  <span m="344696">are</span> <span m="345092">shown</span> <span m="345488">in</span>
  <span m="345884">red.</span></p><p><span m="346280">Since</span> <span m="346628">the</span>
  <span m="346976">SUBC</span> <span m="347324">is</span> <span m="347672">stalled</span>
  <span m="348020">in</span> <span m="348368">the</span> <span m="348716">RF</span>
  <span m="349065">stage</span> <span m="349413">for</span> <span m="349761">three</span>
  <span m="350109">cycles,</span> <span m="350457">three</span> <span m="350805">NOPs</span>
  <span m="351153">are</span> <span m="351501">introduced</span> <span m="351850">into</span>
  <span m="352350">the</span> <span m="352850">pipeline.</span></p><p><span m="353350">We</span>
  <span m="353695">sometimes</span> <span m="354040">refer</span> <span m="354386">to</span>
  <span m="354731">these</span> <span m="355077">NOPs</span> <span m="355422">as</span>
  <span m="355768">&quot;bubbles&quot;</span> <span m="356113">in</span> <span m="356459">the</span>
  <span m="356804">pipeline.</span></p><p><span m="357150">How</span> <span m="357565">does</span>
  <span m="357980">the</span> <span m="358395">pipeline</span> <span m="358810">know</span>
  <span m="359225">when</span> <span m="359640">to</span> <span m="360055">stall?</span></p><p><span
  m="360470">It</span> <span m="360780">can</span> <span m="361091">compare</span>
  <span m="361401">the</span> <span m="361712">register</span> <span m="362022">numbers</span>
  <span m="362333">in</span> <span m="362644">the</span> <span m="362954">RA</span>
  <span m="363265">and</span> <span m="363575">RB</span> <span m="363886">fields</span>
  <span m="364197">of</span> <span m="364507">the</span> <span m="364818">instruction</span>
  <span m="365128">in</span> <span m="365439">the</span> <span m="365750">RF</span>
  <span m="366171">stage</span> <span m="366592">with</span> <span m="367013">the</span>
  <span m="367435">register</span> <span m="367856">numbers</span> <span m="368277">in</span>
  <span m="368698">the</span> <span m="369120">RC</span> <span m="369541">field</span>
  <span m="369962">of</span> <span m="370383">instructions</span> <span m="370805">in</span>
  <span m="371226">the</span> <span m="371647">ALU,</span> <span m="372068">MEM,</span>
  <span m="372490">and</span> <span m="373300">WB</span> <span m="374110">stage.</span></p><p><span
  m="374920">If</span> <span m="375260">there's</span> <span m="375601">a</span> <span
  m="375942">match,</span> <span m="376282">there's</span> <span m="376623">a</span>
  <span m="376964">data</span> <span m="377304">hazard</span> <span m="377645">and</span>
  <span m="377986">the</span> <span m="378326">RF</span> <span m="378667">stage</span>
  <span m="379008">should</span> <span m="379348">be</span> <span m="379689">stalled.</span></p><p><span
  m="380030">The</span> <span m="380540">stall</span> <span m="381050">will</span>
  <span m="381560">continue</span> <span m="382070">until</span> <span m="382580">there's</span>
  <span m="383090">no</span> <span m="383600">hazard</span> <span m="384110">detected.</span></p><p><span
  m="384620">There</span> <span m="384990">are</span> <span m="385361">a</span> <span
  m="385732">few</span> <span m="386102">details</span> <span m="386473">to</span>
  <span m="386844">take</span> <span m="387214">care</span> <span m="387585">of:</span>
  <span m="387956">some</span> <span m="388326">instructions</span> <span m="388697">don't</span>
  <span m="389068">read</span> <span m="389438">both</span> <span m="389809">registers,</span>
  <span m="390180">the</span> <span m="390517">ST</span> <span m="390854">instruction</span>
  <span m="391191">doesn't</span> <span m="391528">use</span> <span m="391865">its</span>
  <span m="392202">RC</span> <span m="392539">field,</span> <span m="392876">and</span>
  <span m="393213">we</span> <span m="393550">don't</span> <span m="393887">want</span>
  <span m="394224">R31</span> <span m="394561">to</span> <span m="394898">match</span>
  <span m="395235">since</span> <span m="395572">it's</span> <span m="395909">always</span>
  <span m="396488">okay</span> <span m="397067">to</span> <span m="397646">read</span>
  <span m="398225">R31</span> <span m="398804">from</span> <span m="399383">the</span>
  <span m="399962">register</span> <span m="400541">file.</span></p><p><span m="401120">Stalling</span>
  <span m="401606">will</span> <span m="402092">ensure</span> <span m="402578">correct</span>
  <span m="403064">pipelined</span> <span m="403550">execution,</span> <span m="404036">but</span>
  <span m="404523">it</span> <span m="405009">does</span> <span m="405495">increase</span>
  <span m="405981">the</span> <span m="406467">effective</span> <span m="406953">CPI.</span></p><p><span
  m="407440">This</span> <span m="407787">will</span> <span m="408134">lead</span>
  <span m="408481">to</span> <span m="408828">longer</span> <span m="409175">execution</span>
  <span m="409522">times</span> <span m="409869">if</span> <span m="410216">the</span>
  <span m="410563">increase</span> <span m="410910">in</span> <span m="411257">CPI</span>
  <span m="411604">is</span> <span m="411951">larger</span> <span m="412298">than</span>
  <span m="412645">the</span> <span m="412992">decrease</span> <span m="413340">in</span>
  <span m="413803">cycle</span> <span m="414266">time</span> <span m="414730">afforded</span>
  <span m="415193">by</span> <span m="415656">pipelining.</span></p><p><span m="416120">To</span>
  <span m="416465">implement</span> <span m="416811">stalling,</span> <span m="417156">we</span>
  <span m="417502">only</span> <span m="417848">need</span> <span m="418193">to</span>
  <span m="418539">make</span> <span m="418885">two</span> <span m="419230">simple</span>
  <span m="419576">changes</span> <span m="419921">to</span> <span m="420267">our</span>
  <span m="420613">pipelined</span> <span m="420958">data</span> <span m="421304">path.</span></p><p><span
  m="421650">We</span> <span m="421986">generate</span> <span m="422322">a</span>
  <span m="422658">new</span> <span m="422994">control</span> <span m="423330">signal,</span>
  <span m="423666">STALL,</span> <span m="424002">which,</span> <span m="424338">when</span>
  <span m="424674">asserted,</span> <span m="425010">disables</span> <span m="425346">the</span>
  <span m="425682">loading</span> <span m="426018">of</span> <span m="426354">the</span>
  <span m="426690">three</span> <span m="427013">pipeline</span> <span m="427336">registers</span>
  <span m="427659">at</span> <span m="427982">the</span> <span m="428305">input</span>
  <span m="428628">of</span> <span m="428951">the</span> <span m="429275">IF</span>
  <span m="429598">and</span> <span m="429921">RF</span> <span m="430244">stages,</span>
  <span m="430567">which</span> <span m="430890">means</span> <span m="431213">they'll</span>
  <span m="431536">have</span> <span m="431860">the</span> <span m="432245">same</span>
  <span m="432630">value</span> <span m="433015">next</span> <span m="433400">cycle</span>
  <span m="433785">as</span> <span m="434170">they</span> <span m="434555">do</span>
  <span m="434940">this</span> <span m="435325">cycle.</span></p><p><span m="435710">We</span>
  <span m="436033">also</span> <span m="436357">introduce</span> <span m="436680">a</span>
  <span m="437004">mux</span> <span m="437327">to</span> <span m="437651">choose</span>
  <span m="437974">the</span> <span m="438298">instruction</span> <span m="438621">to</span>
  <span m="438945">be</span> <span m="439268">sent</span> <span m="439592">along</span>
  <span m="439915">to</span> <span m="440239">the</span> <span m="440562">ALU</span>
  <span m="440886">stage.</span></p><p><span m="441210">If</span> <span m="441620">STALL</span>
  <span m="442031">is</span> <span m="442441">1,</span> <span m="442852">we</span>
  <span m="443262">choose</span> <span m="443673">a</span> <span m="444084">NOP</span>
  <span m="444494">instruction,</span> <span m="444905">e.g.,</span> <span m="445315">an</span>
  <span m="445726">ADD</span> <span m="446137">with</span> <span m="446547">R31</span>
  <span m="446958">as</span> <span m="447368">its</span> <span m="447779">destination.</span></p><p><span
  m="448190">If</span> <span m="448500">STALL</span> <span m="448811">is</span> <span
  m="449121">0,</span> <span m="449432">the</span> <span m="449742">RF</span> <span
  m="450053">stage</span> <span m="450363">is</span> <span m="450674">not</span> <span
  m="450985">stalled,</span> <span m="451295">so</span> <span m="451606">we</span>
  <span m="451916">pass</span> <span m="452227">its</span> <span m="452537">current</span>
  <span m="452848">instruction</span> <span m="453158">to</span> <span m="453469">the</span>
  <span m="453780">ALU.</span></p><p><span m="454780">And</span> <span m="455097">here</span>
  <span m="455415">we</span> <span m="455733">see</span> <span m="456051">how</span>
  <span m="456369">to</span> <span m="456687">compute</span> <span m="457005">STALL</span>
  <span m="457322">as</span> <span m="457640">described</span> <span m="457958">in</span>
  <span m="458276">the</span> <span m="458594">previous</span> <span m="458912">slide.</span></p><p><span
  m="459230">The</span> <span m="459562">additional</span> <span m="459895">logic</span>
  <span m="460228">needed</span> <span m="460560">to</span> <span m="460893">implement</span>
  <span m="461226">stalling</span> <span m="461558">is</span> <span m="461891">pretty</span>
  <span m="462224">modest,</span> <span m="462556">so</span> <span m="462889">the</span>
  <span m="463222">real</span> <span m="463554">design</span> <span m="463887">tradeoff</span>
  <span m="464220">is</span> <span m="464670">about</span> <span m="465120">increased</span>
  <span m="465570">CPI</span> <span m="466020">due</span> <span m="466470">to</span>
  <span m="466920">stalling</span> <span m="467370">vs.</span> <span m="467820">decreased</span>
  <span m="468270">cycle</span> <span m="468720">time</span> <span m="469170">due</span>
  <span m="469620">to</span> <span m="470070">pipelining.</span></p><p><span m="470520">So</span>
  <span m="470960">we</span> <span m="471400">have</span> <span m="471840">a</span>
  <span m="472280">solution,</span> <span m="472720">although</span> <span m="473160">it</span>
  <span m="473600">carries</span> <span m="474040">some</span> <span m="474480">potential</span>
  <span m="474920">performance</span> <span m="475360">costs.</span></p><p><span m="475800">Now</span>
  <span m="476170">let's</span> <span m="476541">consider</span> <span m="476912">our</span>
  <span m="477283">second</span> <span m="477653">strategy:</span> <span m="478024">bypassing,</span>
  <span m="478395">which</span> <span m="478766">is</span> <span m="479136">applicable</span>
  <span m="479507">if</span> <span m="479878">the</span> <span m="480249">data</span>
  <span m="480620">we</span> <span m="480942">need</span> <span m="481264">in</span>
  <span m="481586">the</span> <span m="481909">RF</span> <span m="482231">stage</span>
  <span m="482553">is</span> <span m="482876">somewhere</span> <span m="483198">in</span>
  <span m="483520">the</span> <span m="483843">pipelined</span> <span m="484165">data</span>
  <span m="484487">path.</span></p><p><span m="484810">In</span> <span m="485141">our</span>
  <span m="485473">example,</span> <span m="485805">even</span> <span m="486136">though</span>
  <span m="486468">ADDC</span> <span m="486800">doesn't</span> <span m="487131">write</span>
  <span m="487463">R2</span> <span m="487795">until</span> <span m="488126">the</span>
  <span m="488458">end</span> <span m="488790">of</span> <span m="489121">cycle</span>
  <span m="489453">5,</span> <span m="489785">the</span> <span m="490116">value</span>
  <span m="490448">that</span> <span m="490780">will</span> <span m="491173">be</span>
  <span m="491567">written</span> <span m="491961">is</span> <span m="492355">computed</span>
  <span m="492748">during</span> <span m="493142">cycle</span> <span m="493536">3</span>
  <span m="493930">when</span> <span m="494323">the</span> <span m="494717">ADDC</span>
  <span m="495111">is</span> <span m="495505">in</span> <span m="495898">the</span>
  <span m="496292">ALU</span> <span m="496686">stage.</span></p><p><span m="497080">In</span>
  <span m="497373">cycle</span> <span m="497667">3,</span> <span m="497960">the</span>
  <span m="498254">output</span> <span m="498547">of</span> <span m="498841">the</span>
  <span m="499134">ALU</span> <span m="499428">is</span> <span m="499721">the</span>
  <span m="500015">value</span> <span m="500308">needed</span> <span m="500602">by</span>
  <span m="500895">the</span> <span m="501189">SUBC</span> <span m="501482">that's</span>
  <span m="501776">in</span> <span m="502069">the</span> <span m="502363">RF</span>
  <span m="502656">stage</span> <span m="502950">in</span> <span m="503415">the</span>
  <span m="503880">same</span> <span m="504345">cycle.</span></p><p><span m="504810">So,</span>
  <span m="505143">if</span> <span m="505477">we</span> <span m="505811">detect</span>
  <span m="506144">that</span> <span m="506478">the</span> <span m="506812">RA</span>
  <span m="507145">field</span> <span m="507479">of</span> <span m="507813">the</span>
  <span m="508146">instruction</span> <span m="508480">in</span> <span m="508814">the</span>
  <span m="509147">RF</span> <span m="509481">stage</span> <span m="509815">is</span>
  <span m="510148">the</span> <span m="510482">same</span> <span m="510816">as</span>
  <span m="511150">the</span> <span m="511453">RC</span> <span m="511757">field</span>
  <span m="512060">of</span> <span m="512364">the</span> <span m="512668">instruction</span>
  <span m="512971">in</span> <span m="513275">the</span> <span m="513579">ALU</span>
  <span m="513882">stage,</span> <span m="514186">we</span> <span m="514489">can</span>
  <span m="514793">use</span> <span m="515097">the</span> <span m="515400">output</span>
  <span m="515704">of</span> <span m="516008">the</span> <span m="516311">ALU</span>
  <span m="516615">in</span> <span m="516919">place</span> <span m="517292">of</span>
  <span m="517665">the</span> <span m="518039">(stale)</span> <span m="518412">RA</span>
  <span m="518785">value</span> <span m="519159">being</span> <span m="519532">read</span>
  <span m="519905">from</span> <span m="520279">the</span> <span m="520652">register</span>
  <span m="521025">file.</span></p><p><span m="521399">No</span> <span m="522322">stalling</span>
  <span m="523245">necessary!</span></p><p><span m="524169">In</span> <span m="524415">our</span>
  <span m="524661">example,</span> <span m="524907">in</span> <span m="525153">cycle</span>
  <span m="525399">3</span> <span m="525646">we</span> <span m="525892">want</span>
  <span m="526138">to</span> <span m="526384">route</span> <span m="526630">the</span>
  <span m="526877">output</span> <span m="527123">of</span> <span m="527369">the</span>
  <span m="527615">ALU</span> <span m="527861">to</span> <span m="528108">the</span>
  <span m="528354">RF</span> <span m="528600">stage</span> <span m="528846">to</span>
  <span m="529092">be</span> <span m="529339">used</span> <span m="529902">as</span>
  <span m="530466">the</span> <span m="531029">value</span> <span m="531593">for</span>
  <span m="532156">R2.</span></p><p><span m="532720">We</span> <span m="533052">show</span>
  <span m="533385">this</span> <span m="533718">with</span> <span m="534050">a</span>
  <span m="534383">red</span> <span m="534716">&quot;bypass</span> <span m="535049">arrow&quot;</span>
  <span m="535381">showing</span> <span m="535714">data</span> <span m="536047">being</span>
  <span m="536379">routed</span> <span m="536712">from</span> <span m="537045">the</span>
  <span m="537378">ALU</span> <span m="537710">stage</span> <span m="538043">to</span>
  <span m="538376">the</span> <span m="538709">RF</span> <span m="539404">stage.</span></p><p><span
  m="540100">To</span> <span m="540418">implement</span> <span m="540736">bypassing,</span>
  <span m="541054">we'll</span> <span m="541372">add</span> <span m="541690">a</span>
  <span m="542008">many-input</span> <span m="542326">multiplexer</span> <span m="542644">to</span>
  <span m="542962">the</span> <span m="543280">read</span> <span m="543598">ports</span>
  <span m="543916">of</span> <span m="544234">the</span> <span m="544552">register</span>
  <span m="544870">file</span> <span m="545311">so</span> <span m="545753">we</span>
  <span m="546195">can</span> <span m="546636">select</span> <span m="547078">the</span>
  <span m="547520">appropriate</span> <span m="547961">value</span> <span m="548403">from</span>
  <span m="548845">other</span> <span m="549286">pipeline</span> <span m="549728">stages.</span></p><p><span
  m="550170">Here</span> <span m="550616">we</span> <span m="551062">show</span> <span
  m="551509">the</span> <span m="551955">combinational</span> <span m="552402">bypass</span>
  <span m="552848">paths</span> <span m="553295">from</span> <span m="553741">the</span>
  <span m="554187">ALU,</span> <span m="554634">MEM,</span> <span m="555080">and</span>
  <span m="555527">WB</span> <span m="555973">stages.</span></p><p><span m="556420">For</span>
  <span m="556740">the</span> <span m="557060">bypassing</span> <span m="557380">example</span>
  <span m="557700">of</span> <span m="558020">the</span> <span m="558340">previous</span>
  <span m="558660">slides,</span> <span m="558980">we</span> <span m="559300">use</span>
  <span m="559620">the</span> <span m="559940">blue</span> <span m="560260">bypass</span>
  <span m="560580">path</span> <span m="560900">during</span> <span m="561220">cycle</span>
  <span m="561741">3</span> <span m="562262">to</span> <span m="562783">get</span>
  <span m="563304">the</span> <span m="563825">correct</span> <span m="564346">value</span>
  <span m="564867">for</span> <span m="565388">R2.</span></p><p><span m="565910">The</span>
  <span m="566201">bypass</span> <span m="566492">muxes</span> <span m="566783">are</span>
  <span m="567075">controlled</span> <span m="567366">by</span> <span m="567657">logic</span>
  <span m="567948">that's</span> <span m="568240">matching</span> <span m="568531">the</span>
  <span m="568822">number</span> <span m="569113">of</span> <span m="569405">the</span>
  <span m="569696">source</span> <span m="569987">register</span> <span m="570279">to</span>
  <span m="570650">the</span> <span m="571022">number</span> <span m="571394">of</span>
  <span m="571766">the</span> <span m="572138">destination</span> <span m="572509">registers</span>
  <span m="572881">in</span> <span m="573253">the</span> <span m="573625">ALU,</span>
  <span m="573997">MEM,</span> <span m="574369">and</span> <span m="574740">WB</span>
  <span m="575112">stages,</span> <span m="575484">with</span> <span m="575856">the</span>
  <span m="576228">usual</span> <span m="576600">complications</span> <span m="577466">of</span>
  <span m="578332">dealing</span> <span m="579198">with</span> <span m="580064">R31.</span></p><p><span
  m="580930">What</span> <span m="581185">if</span> <span m="581441">there</span>
  <span m="581697">are</span> <span m="581953">multiple</span> <span m="582209">matches,</span>
  <span m="582465">i.e.,</span> <span m="582721">if</span> <span m="582977">the</span>
  <span m="583232">RF</span> <span m="583488">stage</span> <span m="583744">is</span>
  <span m="584000">trying</span> <span m="584256">to</span> <span m="584512">read</span>
  <span m="584768">a</span> <span m="585024">register</span> <span m="585280">that's</span>
  <span m="585724">the</span> <span m="586169">destination</span> <span m="586614">for,</span>
  <span m="587059">say,</span> <span m="587504">the</span> <span m="587949">instructions</span>
  <span m="588394">in</span> <span m="588839">both</span> <span m="589284">the</span>
  <span m="589729">ALU</span> <span m="590174">and</span> <span m="590619">MEM</span>
  <span m="591064">stages?</span></p><p><span m="591509">No</span> <span m="592309">problem!</span></p><p><span
  m="593110">We</span> <span m="593426">want</span> <span m="593743">to</span> <span
  m="594060">select</span> <span m="594377">the</span> <span m="594694">result</span>
  <span m="595011">from</span> <span m="595328">the</span> <span m="595645">most</span>
  <span m="595961">recent</span> <span m="596278">instruction,</span> <span m="596595">so</span>
  <span m="596912">we'd</span> <span m="597229">chose</span> <span m="597546">the</span>
  <span m="597863">ALU</span> <span m="598180">match</span> <span m="598527">if</span>
  <span m="598875">there</span> <span m="599222">is</span> <span m="599570">one,</span>
  <span m="599917">then</span> <span m="600265">the</span> <span m="600613">MEM</span>
  <span m="600960">match,</span> <span m="601308">then</span> <span m="601655">the</span>
  <span m="602003">WB</span> <span m="602351">match,</span> <span m="602698">then,</span>
  <span m="603046">finally,</span> <span m="603393">the</span> <span m="603741">output</span>
  <span m="604089">of</span> <span m="604631">the</span> <span m="605174">register</span>
  <span m="605717">file.</span></p><p><span m="606260">Here's</span> <span m="606682">diagram</span>
  <span m="607104">showing</span> <span m="607526">all</span> <span m="607948">the</span>
  <span m="608371">bypass</span> <span m="608793">paths</span> <span m="609215">we'll</span>
  <span m="609637">need.</span></p><p><span m="610060">Note</span> <span m="610345">that</span>
  <span m="610631">branches</span> <span m="610916">and</span> <span m="611202">jumps</span>
  <span m="611488">write</span> <span m="611773">their</span> <span m="612059">PC+4</span>
  <span m="612345">value</span> <span m="612630">into</span> <span m="612916">the</span>
  <span m="613201">register</span> <span m="613487">file,</span> <span m="613773">so</span>
  <span m="614058">we'll</span> <span m="614344">need</span> <span m="614630">to</span>
  <span m="615060">bypass</span> <span m="615491">from</span> <span m="615921">the</span>
  <span m="616352">PC+4</span> <span m="616782">values</span> <span m="617213">in</span>
  <span m="617643">the</span> <span m="618074">various</span> <span m="618505">stages</span>
  <span m="618935">as</span> <span m="619366">well</span> <span m="619796">as</span>
  <span m="620227">the</span> <span m="620657">ALU</span> <span m="621088">values.</span></p><p><span
  m="621519">Note</span> <span m="621831">that</span> <span m="622144">the</span>
  <span m="622457">bypassing</span> <span m="622770">is</span> <span m="623083">happening</span>
  <span m="623396">at</span> <span m="623709">the</span> <span m="624022">end</span>
  <span m="624335">of</span> <span m="624648">the</span> <span m="624961">cycle,</span>
  <span m="625274">e.g.,</span> <span m="625587">after</span> <span m="625900">the</span>
  <span m="626213">ALU</span> <span m="626526">has</span> <span m="626839">computed</span>
  <span m="627252">its</span> <span m="627666">answer.</span></p><p><span m="628080">To</span>
  <span m="628396">accommodate</span> <span m="628713">the</span> <span m="629030">extra</span>
  <span m="629347">t_PD</span> <span m="629664">of</span> <span m="629980">the</span>
  <span m="630297">bypass</span> <span m="630614">mux,</span> <span m="630931">we'll</span>
  <span m="631248">have</span> <span m="631564">to</span> <span m="631881">extend</span>
  <span m="632198">the</span> <span m="632515">clock</span> <span m="632832">period</span>
  <span m="633149">by</span> <span m="633681">a</span> <span m="634214">small</span>
  <span m="634746">amount.</span></p><p><span m="635279">So</span> <span m="635654">once</span>
  <span m="636030">again</span> <span m="636406">there's</span> <span m="636781">a</span>
  <span m="637157">design</span> <span m="637533">tradeoff</span> <span m="637908">-</span>
  <span m="638284">the</span> <span m="638660">increased</span> <span m="639035">CPI</span>
  <span m="639411">of</span> <span m="639787">stalling</span> <span m="640162">vs</span>
  <span m="640538">the</span> <span m="640914">slightly</span> <span m="641290">increased</span>
  <span m="641764">cycle</span> <span m="642238">time</span> <span m="642712">of</span>
  <span m="643186">bypassing.</span></p><p><span m="643660">And,</span> <span m="643984">of</span>
  <span m="644308">course,</span> <span m="644632">in</span> <span m="644956">the</span>
  <span m="645280">case</span> <span m="645604">of</span> <span m="645928">bypassing</span>
  <span m="646252">there's</span> <span m="646577">the</span> <span m="646901">extra</span>
  <span m="647225">area</span> <span m="647549">needed</span> <span m="647873">for</span>
  <span m="648197">the</span> <span m="648521">necessary</span> <span m="648845">wiring</span>
  <span m="649170">and</span> <span m="650360">muxes.</span></p><p><span m="651550">We</span>
  <span m="651874">can</span> <span m="652199">cut</span> <span m="652524">back</span>
  <span m="652848">on</span> <span m="653173">the</span> <span m="653498">costs</span>
  <span m="653822">by</span> <span m="654147">reducing</span> <span m="654472">the</span>
  <span m="654797">amount</span> <span m="655121">of</span> <span m="655446">bypassing,</span>
  <span m="655771">say,</span> <span m="656095">to</span> <span m="656420">only</span>
  <span m="656745">bypassing</span> <span m="657070">ALU</span> <span m="657462">results</span>
  <span m="657854">from</span> <span m="658247">the</span> <span m="658639">ALU</span>
  <span m="659031">stage</span> <span m="659424">and</span> <span m="659816">use</span>
  <span m="660208">stalling</span> <span m="660601">to</span> <span m="660993">deal</span>
  <span m="661385">with</span> <span m="661778">all</span> <span m="662170">the</span>
  <span m="662562">other</span> <span m="662955">data</span> <span m="663347">hazards.</span></p><p><span
  m="663740">If</span> <span m="664120">we</span> <span m="664501">implement</span>
  <span m="664882">full</span> <span m="665263">bypassing,</span> <span m="665644">do</span>
  <span m="666025">we</span> <span m="666405">still</span> <span m="666786">need</span>
  <span m="667167">the</span> <span m="667548">STALL</span> <span m="667929">logic?</span></p><p><span
  m="668310">As</span> <span m="668624">it</span> <span m="668939">turns</span> <span
  m="669254">out,</span> <span m="669569">we</span> <span m="669884">do!</span></p><p><span
  m="670199">There's</span> <span m="670707">one</span> <span m="671216">data</span>
  <span m="671725">hazard</span> <span m="672234">that</span> <span m="672743">bypassing</span>
  <span m="673252">doesn't</span> <span m="673761">completely</span> <span m="674270">address.</span></p><p><span
  m="674779">Consider</span> <span m="675103">trying</span> <span m="675427">to</span>
  <span m="675751">immediately</span> <span m="676076">the</span> <span m="676400">use</span>
  <span m="676724">the</span> <span m="677048">result</span> <span m="677373">of</span>
  <span m="677697">a</span> <span m="678021">LD</span> <span m="678345">instruction.</span></p><p><span
  m="678670">In</span> <span m="679001">the</span> <span m="679332">example</span>
  <span m="679663">shown</span> <span m="679995">here,</span> <span m="680326">the</span>
  <span m="680657">SUBC</span> <span m="680988">is</span> <span m="681320">trying</span>
  <span m="681651">to</span> <span m="681982">use</span> <span m="682313">the</span>
  <span m="682645">value</span> <span m="682976">the</span> <span m="683307">immediately</span>
  <span m="683638">preceding</span> <span m="683970">LD</span> <span m="684425">is</span>
  <span m="684881">writing</span> <span m="685337">to</span> <span m="685793">R2.</span></p><p><span
  m="686249">This</span> <span m="686830">is</span> <span m="687412">called</span>
  <span m="687994">a</span> <span m="688576">load-to-use</span> <span m="689158">hazard.</span></p><p><span
  m="689740">Recalling</span> <span m="690029">that</span> <span m="690319">LD</span>
  <span m="690609">data</span> <span m="690899">isn't</span> <span m="691189">available</span>
  <span m="691479">in</span> <span m="691769">the</span> <span m="692059">data</span>
  <span m="692349">path</span> <span m="692639">until</span> <span m="692929">the</span>
  <span m="693219">cycle</span> <span m="693509">when</span> <span m="693799">LD</span>
  <span m="694089">reaches</span> <span m="694379">the</span> <span m="694759">WB</span>
  <span m="695139">stage,</span> <span m="695519">even</span> <span m="695899">with</span>
  <span m="696279">full</span> <span m="696659">bypassing</span> <span m="697039">we'll</span>
  <span m="697419">need</span> <span m="697799">to</span> <span m="698179">stall</span>
  <span m="698559">SUBC</span> <span m="698939">in</span> <span m="699319">the</span>
  <span m="699699">RF</span> <span m="700079">stage</span> <span m="700459">until</span>
  <span m="700839">cycle</span> <span m="701220">5,</span> <span m="701858">introducing</span>
  <span m="702496">two</span> <span m="703135">NOPs</span> <span m="703773">into</span>
  <span m="704412">the</span> <span m="705050">pipeline.</span></p><p><span m="705689">Without</span>
  <span m="706112">bypassing</span> <span m="706536">from</span> <span m="706960">the</span>
  <span m="707384">WB</span> <span m="707808">stage,</span> <span m="708232">we</span>
  <span m="708655">need</span> <span m="709079">to</span> <span m="709503">stall</span>
  <span m="709927">until</span> <span m="710351">cycle</span> <span m="710775">6.</span></p><p><span
  m="711199">In</span> <span m="711678">summary,</span> <span m="712157">we</span>
  <span m="712636">have</span> <span m="713115">two</span> <span m="713594">strategies</span>
  <span m="714074">for</span> <span m="714553">dealing</span> <span m="715032">with</span>
  <span m="715511">data</span> <span m="715990">hazards.</span></p><p><span m="716470">We</span>
  <span m="716786">can</span> <span m="717102">stall</span> <span m="717418">the</span>
  <span m="717734">IF</span> <span m="718050">and</span> <span m="718367">RF</span>
  <span m="718683">stages</span> <span m="718999">until</span> <span m="719315">the</span>
  <span m="719631">register</span> <span m="719948">values</span> <span m="720264">needed</span>
  <span m="720580">by</span> <span m="720896">the</span> <span m="721212">instruction</span>
  <span m="721529">in</span> <span m="721902">the</span> <span m="722275">RF</span>
  <span m="722648">stage</span> <span m="723021">are</span> <span m="723394">available</span>
  <span m="723767">in</span> <span m="724140">the</span> <span m="724513">register</span>
  <span m="724886">file.</span></p><p><span m="725259">The</span> <span m="725661">required</span>
  <span m="726064">hardware</span> <span m="726467">is</span> <span m="726869">simple,</span>
  <span m="727272">but</span> <span m="727675">the</span> <span m="728078">NOPs</span>
  <span m="728480">introduced</span> <span m="728883">into</span> <span m="729286">the</span>
  <span m="729689">pipeline</span> <span m="730091">waste</span> <span m="730494">CPU</span>
  <span m="730897">cycles</span> <span m="731300">and</span> <span m="731767">result</span>
  <span m="732234">in</span> <span m="732701">an</span> <span m="733168">higher</span>
  <span m="733635">effective</span> <span m="734102">CPI.</span></p><p><span m="734570">Or</span>
  <span m="734916">we</span> <span m="735262">can</span> <span m="735608">use</span>
  <span m="735954">bypass</span> <span m="736300">paths</span> <span m="736646">to</span>
  <span m="736992">route</span> <span m="737338">the</span> <span m="737685">required</span>
  <span m="738031">values</span> <span m="738377">to</span> <span m="738723">the</span>
  <span m="739069">RF</span> <span m="739415">stage</span> <span m="739761">assuming</span>
  <span m="740107">they</span> <span m="740453">exist</span> <span m="740800">somewhere</span>
  <span m="741340">in</span> <span m="741880">the</span> <span m="742420">pipelined</span>
  <span m="742960">data</span> <span m="743500">path.</span></p><p><span m="744040">This</span>
  <span m="744399">approach</span> <span m="744758">requires</span> <span m="745117">more</span>
  <span m="745476">hardware</span> <span m="745835">than</span> <span m="746195">stalling,</span>
  <span m="746554">but</span> <span m="746913">doesn't</span> <span m="747272">reduce</span>
  <span m="747631">the</span> <span m="747990">effective</span> <span m="748350">CPI.</span></p><p><span
  m="749750">Even</span> <span m="750174">if</span> <span m="750598">we</span> <span
  m="751022">implement</span> <span m="751446">bypassing,</span> <span m="751871">we'll</span>
  <span m="752295">still</span> <span m="752719">need</span> <span m="753143">stalls</span>
  <span m="753567">to</span> <span m="753992">deal</span> <span m="754416">with</span>
  <span m="754840">load-to-use</span> <span m="755264">hazards.</span></p><p><span
  m="755689">Can</span> <span m="755998">we</span> <span m="756307">keep</span> <span
  m="756617">adding</span> <span m="756926">pipeline</span> <span m="757235">stages</span>
  <span m="757545">in</span> <span m="757854">the</span> <span m="758163">hopes</span>
  <span m="758473">of</span> <span m="758782">further</span> <span m="759091">reducing</span>
  <span m="759401">the</span> <span m="759710">clock</span> <span m="760019">period?</span></p><p><span
  m="760329">More</span> <span m="760669">pipeline</span> <span m="761010">stages</span>
  <span m="761351">mean</span> <span m="761691">more</span> <span m="762032">instructions</span>
  <span m="762373">in</span> <span m="762713">the</span> <span m="763054">pipeline</span>
  <span m="763395">at</span> <span m="763735">the</span> <span m="764076">same</span>
  <span m="764417">time,</span> <span m="764757">which</span> <span m="765098">in</span>
  <span m="765439">turn</span> <span m="765793">increases</span> <span m="766148">the</span>
  <span m="766503">chance</span> <span m="766857">of</span> <span m="767212">a</span>
  <span m="767567">data</span> <span m="767922">hazard</span> <span m="768276">and</span>
  <span m="768631">the</span> <span m="768986">necessity</span> <span m="769341">of</span>
  <span m="769695">stalling,</span> <span m="770050">thus</span> <span m="770405">increasing</span>
  <span m="770760">CPI.</span></p><p><span m="773189">Compilers</span> <span m="773530">can</span>
  <span m="773872">help</span> <span m="774214">reduce</span> <span m="774556">dependencies</span>
  <span m="774897">by</span> <span m="775239">reorganizing</span> <span m="775581">the</span>
  <span m="775923">assembly</span> <span m="776264">language</span> <span m="776606">code</span>
  <span m="776948">they</span> <span m="777290">produce.</span></p><p><span m="778339">Here's</span>
  <span m="778797">the</span> <span m="779256">load-to-use</span> <span m="779715">hazard</span>
  <span m="780174">example</span> <span m="780632">we</span> <span m="781091">saw</span>
  <span m="781550">earlier.</span></p><p><span m="782009">Even</span> <span m="782426">with</span>
  <span m="782843">full</span> <span m="783261">bypassing,</span> <span m="783678">we'd</span>
  <span m="784095">need</span> <span m="784513">to</span> <span m="784930">stall</span>
  <span m="785347">for</span> <span m="785765">2</span> <span m="786182">cycles.</span></p><p><span
  m="786600">But</span> <span m="786945">if</span> <span m="787290">the</span> <span
  m="787635">compiler</span> <span m="787980">(or</span> <span m="788325">assembly</span>
  <span m="788670">language</span> <span m="789015">programmer!)</span> <span m="789360">notices</span>
  <span m="789705">that</span> <span m="790050">the</span> <span m="790395">MUL</span>
  <span m="790740">and</span> <span m="791085">XOR</span> <span m="791430">instructions</span>
  <span m="791787">are</span> <span m="792144">independent</span> <span m="792502">of</span>
  <span m="792859">the</span> <span m="793216">SUBC</span> <span m="793574">instruction</span>
  <span m="793931">and</span> <span m="794288">hence</span> <span m="794646">can</span>
  <span m="795003">be</span> <span m="795360">moved</span> <span m="795718">before</span>
  <span m="796075">the</span> <span m="796432">SUBC,</span> <span m="796790">the</span>
  <span m="797121">dependency</span> <span m="797453">is</span> <span m="797784">now</span>
  <span m="798116">such</span> <span m="798448">that</span> <span m="798779">the</span>
  <span m="799111">LD</span> <span m="799442">is</span> <span m="799774">naturally</span>
  <span m="800106">in</span> <span m="800437">the</span> <span m="800769">WB</span>
  <span m="801100">stage</span> <span m="801432">when</span> <span m="801764">the</span>
  <span m="802095">SUBC</span> <span m="802427">is</span> <span m="802759">in</span>
  <span m="803239">the</span> <span m="803719">RF</span> <span m="804199">stage,</span>
  <span m="804679">so</span> <span m="805159">no</span> <span m="805639">stalls</span>
  <span m="806119">are</span> <span m="806599">needed.</span></p><p><span m="807079">This</span>
  <span m="807404">optimization</span> <span m="807729">only</span> <span m="808055">works</span>
  <span m="808380">when</span> <span m="808705">the</span> <span m="809031">compiler</span>
  <span m="809356">can</span> <span m="809682">find</span> <span m="810007">independent</span>
  <span m="810332">instructions</span> <span m="810658">to</span> <span m="810983">move</span>
  <span m="811309">around.</span></p><p><span m="812910">Unfortunately</span> <span
  m="813400">there</span> <span m="813891">are</span> <span m="814382">plenty</span>
  <span m="814873">of</span> <span m="815363">programs</span> <span m="815854">where</span>
  <span m="816345">such</span> <span m="816836">instructions</span> <span m="817326">are</span>
  <span m="817817">hard</span> <span m="818308">to</span> <span m="818799">find.</span></p><p><span
  m="819290">Then</span> <span m="819576">there's</span> <span m="819863">one</span>
  <span m="820149">final</span> <span m="820436">approach</span> <span m="820722">we</span>
  <span m="821009">could</span> <span m="821295">take</span> <span m="821582">-</span>
  <span m="821869">change</span> <span m="822338">the</span> <span m="822807">ISA</span>
  <span m="823277">so</span> <span m="823746">that</span> <span m="824216">data</span>
  <span m="824685">hazards</span> <span m="825155">are</span> <span m="825624">part</span>
  <span m="826094">of</span> <span m="826563">the</span> <span m="827033">ISA,</span>
  <span m="827502">i.e.,</span> <span m="827972">just</span> <span m="828441">explain</span>
  <span m="828911">that</span> <span m="829380">writes</span> <span m="829850">to</span>
  <span m="830413">the</span> <span m="830976">destination</span> <span m="831540">register</span>
  <span m="832103">happen</span> <span m="832666">with</span> <span m="833230">a</span>
  <span m="833793">3-instruction</span> <span m="834356">delay!</span></p><p><span
  m="834920">If</span> <span m="835268">NOPs</span> <span m="835616">are</span> <span
  m="835965">needed,</span> <span m="836313">make</span> <span m="836661">the</span>
  <span m="837010">programmer</span> <span m="837358">add</span> <span m="837706">them</span>
  <span m="838055">to</span> <span m="838403">the</span> <span m="838751">program.</span></p><p><span
  m="839100">Simplify</span> <span m="839500">the</span> <span m="839901">hardware</span>
  <span m="840302">at</span> <span m="840702">the</span> <span m="841103">&quot;small&quot;</span>
  <span m="841504">cost</span> <span m="841904">of</span> <span m="842305">making</span>
  <span m="842706">the</span> <span m="843106">compilers</span> <span m="843507">work</span>
  <span m="843908">harder.</span></p><p><span m="844309">You</span> <span m="844665">can</span>
  <span m="845021">imagine</span> <span m="845377">exactly</span> <span m="845733">how</span>
  <span m="846089">much</span> <span m="846445">the</span> <span m="846802">compiler</span>
  <span m="847158">writers</span> <span m="847514">will</span> <span m="847870">like</span>
  <span m="848226">this</span> <span m="848582">suggestion.</span></p><p><span m="848939">Not</span>
  <span m="849442">to</span> <span m="849945">mention</span> <span m="850449">assembly</span>
  <span m="850952">language</span> <span m="851455">programmers!</span></p><p><span
  m="851959">And</span> <span m="852405">you</span> <span m="852852">can</span> <span
  m="853299">change</span> <span m="853746">the</span> <span m="854193">ISA</span>
  <span m="854640">again</span> <span m="855087">when</span> <span m="855534">you</span>
  <span m="855981">add</span> <span m="856428">more</span> <span m="856875">pipeline</span>
  <span m="857322">stages!</span></p><p><span m="857769">This</span> <span m="858122">is</span>
  <span m="858476">how</span> <span m="858829">a</span> <span m="859183">compiler</span>
  <span m="859536">writer</span> <span m="859890">views</span> <span m="860243">CPU</span>
  <span m="860597">architects</span> <span m="860950">who</span> <span m="861304">unilaterally</span>
  <span m="861657">change</span> <span m="862011">the</span> <span m="862364">ISA</span>
  <span m="862718">to</span> <span m="863071">save</span> <span m="863425">a</span>
  <span m="863779">few</span> <span m="864165">logic</span> <span m="864552">gates</span>
  <span m="864939">:)</span> <span m="865326">The</span> <span m="865712">bottom</span>
  <span m="866099">line</span> <span m="866486">is</span> <span m="866873">that</span>
  <span m="867259">successful</span> <span m="867646">ISAs</span> <span m="868033">have</span>
  <span m="868420">very</span> <span m="868902">long</span> <span m="869384">lifetimes</span>
  <span m="869867">and</span> <span m="870349">so</span> <span m="870832">shouldn't</span>
  <span m="871314">include</span> <span m="871796">tradeoffs</span> <span m="872279">driven</span>
  <span m="872761">by</span> <span m="873244">short-term</span> <span m="873726">implementation</span>
  <span m="874209">considerations.</span></p><p><span m="875209">Best</span> <span
  m="875483">not</span> <span m="875757">to</span> <span m="876031">go</span> <span
  m="876305">there.</span></p>
type: course
uid: 7f470568b98ce58d9414dfd7e605a765

---
None