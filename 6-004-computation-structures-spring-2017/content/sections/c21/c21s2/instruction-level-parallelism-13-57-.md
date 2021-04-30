---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: IK9OVbj_Ir0
  parent_uid: 190530374c1ed20b2fdfd66de12642d0
  title: Video-YouTube-Stream
  type: Video
  uid: eddb4a9f66729db517169181930d469c
- id: 3Play-3Play YouTube id-Stream
  media_location: IK9OVbj_Ir0
  parent_uid: 190530374c1ed20b2fdfd66de12642d0
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 709b12e886d7bd70b0d96bf8959431b1
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/IK9OVbj_Ir0/default.jpg
  parent_uid: 190530374c1ed20b2fdfd66de12642d0
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 021977c165c27a5a476d89da5c8941ed
- id: IK9OVbj_Ir0.srt
  parent_uid: 190530374c1ed20b2fdfd66de12642d0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/instruction-level-parallelism-13-57-/IK9OVbj_Ir0.srt
  title: 3play caption file
  type: null
  uid: d75671a39dd03f62a284e56da5aad4c1
- id: IK9OVbj_Ir0.pdf
  parent_uid: 190530374c1ed20b2fdfd66de12642d0
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/instruction-level-parallelism-13-57-/IK9OVbj_Ir0.pdf
  title: 3play pdf file
  type: null
  uid: 5376a680d627c1368566a30ba47fecc5
- id: Caption-3Play YouTube id-SRT
  parent_uid: 190530374c1ed20b2fdfd66de12642d0
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 9cf401766ad1fb9eb91ba0156ddaa7be
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 190530374c1ed20b2fdfd66de12642d0
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 5c8d3083e4fb71b32eddbb29056a18db
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_21-02-01_300k.mp4
  parent_uid: 190530374c1ed20b2fdfd66de12642d0
  title: Video-Internet Archive-MP4
  type: Video
  uid: d9f1c3a844225a87deaca1b1a737869a
inline_embed_id: 6072208instructionlevelparallelism135773443559
layout: video
order_index: null
parent_uid: fe5883b3ab229104916985cf37e78935
related_resources_text: ''
short_url: instruction-level-parallelism-13-57-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/instruction-level-parallelism-13-57-
template_type: Embed
title: Instruction-level Parallelism
transcript: <p><span m="740">The</span> <span m="1128">modern</span> <span m="1516">world</span>
  <span m="1905">has</span> <span m="2293">an</span> <span m="2682">insatiable</span>
  <span m="3070">appetite</span> <span m="3459">for</span> <span m="3847">computation,</span>
  <span m="4236">so</span> <span m="4624">system</span> <span m="5013">architects</span>
  <span m="5401">are</span> <span m="5790">always</span> <span m="6215">thinking</span>
  <span m="6641">about</span> <span m="7066">ways</span> <span m="7492">to</span>
  <span m="7917">make</span> <span m="8343">programs</span> <span m="8768">run</span>
  <span m="9194">faster.</span></p><p><span m="9620">The</span> <span m="9934">running</span>
  <span m="10248">time</span> <span m="10562">of</span> <span m="10876">a</span> <span
  m="11190">program</span> <span m="11504">is</span> <span m="11818">the</span> <span
  m="12132">product</span> <span m="12446">of</span> <span m="12760">three</span>
  <span m="13074">terms:</span> <span m="13389">The</span> <span m="13735">number</span>
  <span m="14082">of</span> <span m="14428">instructions</span> <span m="14775">in</span>
  <span m="15121">the</span> <span m="15468">program,</span> <span m="15814">multiplied</span>
  <span m="16161">by</span> <span m="16507">the</span> <span m="16854">average</span>
  <span m="17200">number</span> <span m="17547">of</span> <span m="17893">processor</span>
  <span m="18240">cycles</span> <span m="18666">required</span> <span m="19093">to</span>
  <span m="19520">execute</span> <span m="19947">each</span> <span m="20374">instruction</span>
  <span m="20801">(CPI),</span> <span m="21228">multiplied</span> <span m="21655">by</span>
  <span m="22082">the</span> <span m="22509">time</span> <span m="22936">required</span>
  <span m="23363">for</span> <span m="23790">each</span> <span m="24702">processor</span>
  <span m="25615">cycle</span> <span m="26527">(t_CLK).</span></p><p><span m="27440">To</span>
  <span m="27748">decrease</span> <span m="28057">the</span> <span m="28366">running</span>
  <span m="28674">time</span> <span m="28983">we</span> <span m="29292">need</span>
  <span m="29600">to</span> <span m="29909">decrease</span> <span m="30218">one</span>
  <span m="30526">or</span> <span m="30835">more</span> <span m="31144">of</span>
  <span m="31452">these</span> <span m="31761">terms.</span></p><p><span m="32070">The</span>
  <span m="32348">number</span> <span m="32627">of</span> <span m="32906">instructions</span>
  <span m="33184">per</span> <span m="33463">program</span> <span m="33742">is</span>
  <span m="34020">determined</span> <span m="34299">by</span> <span m="34578">the</span>
  <span m="34856">ISA</span> <span m="35135">and</span> <span m="35414">by</span>
  <span m="35692">the</span> <span m="35971">compiler</span> <span m="36250">that</span>
  <span m="36593">produced</span> <span m="36937">the</span> <span m="37280">sequence</span>
  <span m="37624">of</span> <span m="37968">assembly</span> <span m="38311">language</span>
  <span m="38655">instructions</span> <span m="38999">to</span> <span m="39342">be</span>
  <span m="39686">executed.</span></p><p><span m="40030">Both</span> <span m="40446">are</span>
  <span m="40863">fair</span> <span m="41280">game,</span> <span m="41697">but</span>
  <span m="42114">for</span> <span m="42531">this</span> <span m="42948">discussion,</span>
  <span m="43365">let's</span> <span m="43781">work</span> <span m="44198">on</span>
  <span m="44615">reducing</span> <span m="45032">the</span> <span m="45449">other</span>
  <span m="45866">two</span> <span m="46283">terms.</span></p><p><span m="46700">As</span>
  <span m="47066">we've</span> <span m="47432">seen,</span> <span m="47798">pipelining</span>
  <span m="48164">reduces</span> <span m="48530">t_CLK</span> <span m="48896">by</span>
  <span m="49263">dividing</span> <span m="49629">instruction</span> <span m="49995">execution</span>
  <span m="50361">into</span> <span m="50727">a</span> <span m="51093">sequence</span>
  <span m="51460">of</span> <span m="51834">steps,</span> <span m="52209">each</span>
  <span m="52583">of</span> <span m="52958">which</span> <span m="53333">can</span>
  <span m="53707">complete</span> <span m="54082">its</span> <span m="54456">task</span>
  <span m="54831">in</span> <span m="55206">a</span> <span m="55580">shorter</span>
  <span m="55955">t_CLK.</span></p><p><span m="56330">What</span> <span m="57102">about</span>
  <span m="57875">reducing</span> <span m="58647">CPI?</span></p><p><span m="59420">In</span>
  <span m="59767">our</span> <span m="60114">5-stage</span> <span m="60461">pipelined</span>
  <span m="60808">implementation</span> <span m="61155">of</span> <span m="61502">the</span>
  <span m="61850">Beta,</span> <span m="62197">we</span> <span m="62544">designed</span>
  <span m="62891">the</span> <span m="63238">hardware</span> <span m="63585">to</span>
  <span m="63932">complete</span> <span m="64280">the</span> <span m="64789">execution</span>
  <span m="65299">of</span> <span m="65809">one</span> <span m="66319">instruction</span>
  <span m="66829">every</span> <span m="67339">clock</span> <span m="67849">cycle,</span>
  <span m="68359">so</span> <span m="68869">CPI_ideal</span> <span m="69379">is</span>
  <span m="69889">1.</span></p><p><span m="70399">But</span> <span m="70747">sometimes</span>
  <span m="71095">the</span> <span m="71443">hardware</span> <span m="71791">has</span>
  <span m="72139">to</span> <span m="72487">introduce</span> <span m="72835">&quot;NOP</span>
  <span m="73183">bubbles&quot;</span> <span m="73531">into</span> <span m="73879">the</span>
  <span m="74227">pipeline</span> <span m="74575">to</span> <span m="74923">delay</span>
  <span m="75271">execution</span> <span m="75619">of</span> <span m="76122">a</span>
  <span m="76625">pipeline</span> <span m="77128">stage</span> <span m="77632">if</span>
  <span m="78135">the</span> <span m="78638">required</span> <span m="79141">operation</span>
  <span m="79645">couldn't</span> <span m="80148">(yet)</span> <span m="80651">be</span>
  <span m="81154">completed.</span></p><p><span m="81658">This</span> <span m="82026">happens</span>
  <span m="82395">on</span> <span m="82763">taken</span> <span m="83132">branch</span>
  <span m="83501">instructions,</span> <span m="83869">when</span> <span m="84238">attempting</span>
  <span m="84606">to</span> <span m="84975">immediately</span> <span m="85344">use</span>
  <span m="85712">a</span> <span m="86081">value</span> <span m="86450">loaded</span>
  <span m="86759">from</span> <span m="87068">memory</span> <span m="87378">by</span>
  <span m="87687">the</span> <span m="87997">LD</span> <span m="88306">instruction,</span>
  <span m="88615">and</span> <span m="88925">when</span> <span m="89234">waiting</span>
  <span m="89544">for</span> <span m="89853">a</span> <span m="90162">cache</span>
  <span m="90472">miss</span> <span m="90781">to</span> <span m="91091">be</span>
  <span m="91400">satisfied</span> <span m="91710">from</span> <span m="92393">main</span>
  <span m="93076">memory.</span></p><p><span m="93759">CPI_stall</span> <span m="94221">accounts</span>
  <span m="94683">for</span> <span m="95146">the</span> <span m="95608">cycles</span>
  <span m="96070">lost</span> <span m="96533">to</span> <span m="96995">the</span>
  <span m="97458">NOPs</span> <span m="97920">introduced</span> <span m="98382">into</span>
  <span m="98845">the</span> <span m="99307">pipeline.</span></p><p><span m="99770">Its</span>
  <span m="100120">value</span> <span m="100470">depends</span> <span m="100820">on</span>
  <span m="101170">the</span> <span m="101520">frequency</span> <span m="101870">of</span>
  <span m="102220">taken</span> <span m="102570">branches</span> <span m="102920">and</span>
  <span m="103270">immediate</span> <span m="103620">use</span> <span m="103970">of</span>
  <span m="104320">LD</span> <span m="104670">results.</span></p><p><span m="105020">Typically</span>
  <span m="105369">it's</span> <span m="105719">some</span> <span m="106069">fraction</span>
  <span m="106419">of</span> <span m="106769">a</span> <span m="107119">cycle.</span></p><p><span
  m="107469">For</span> <span m="107898">example,</span> <span m="108327">if</span>
  <span m="108756">a</span> <span m="109186">6-instruction</span> <span m="109615">loop</span>
  <span m="110044">with</span> <span m="110473">a</span> <span m="110903">LD</span>
  <span m="111332">takes</span> <span m="111761">8</span> <span m="112190">cycles</span>
  <span m="112620">to</span> <span m="113049">complete,</span> <span m="113478">CPI_stall</span>
  <span m="113908">for</span> <span m="114390">the</span> <span m="114872">loop</span>
  <span m="115354">would</span> <span m="115836">be</span> <span m="116319">2/6,</span>
  <span m="116801">i.e.,</span> <span m="117283">2</span> <span m="117765">extra</span>
  <span m="118247">cycles</span> <span m="118730">for</span> <span m="119212">every</span>
  <span m="119694">6</span> <span m="120176">instructions.</span></p><p><span m="120659">Our</span>
  <span m="121034">classic</span> <span m="121410">5-stage</span> <span m="121786">pipeline</span>
  <span m="122162">is</span> <span m="122537">an</span> <span m="122913">effective</span>
  <span m="123289">compromise</span> <span m="123665">that</span> <span m="124041">allows</span>
  <span m="124416">for</span> <span m="124792">a</span> <span m="125168">substantial</span>
  <span m="125544">reduction</span> <span m="125920">of</span> <span m="126442">t_CLK</span>
  <span m="126964">while</span> <span m="127486">keeping</span> <span m="128008">CPI_stall</span>
  <span m="128530">to</span> <span m="129052">a</span> <span m="129574">reasonably</span>
  <span m="130096">modest</span> <span m="130618">value.</span></p><p><span m="131140">There</span>
  <span m="131458">is</span> <span m="131776">room</span> <span m="132094">for</span>
  <span m="132412">improvement.</span></p><p><span m="132730">Since</span> <span m="133227">each</span>
  <span m="133724">stage</span> <span m="134221">is</span> <span m="134718">working</span>
  <span m="135215">on</span> <span m="135712">one</span> <span m="136210">instruction</span>
  <span m="136707">at</span> <span m="137204">a</span> <span m="137701">time,</span>
  <span m="138198">CPI_ideal</span> <span m="138695">is</span> <span m="139192">1.</span></p><p><span
  m="139690">Slow</span> <span m="140071">operations</span> <span m="140453">-</span>
  <span m="140835">e.g,</span> <span m="141217">completing</span> <span m="141599">a</span>
  <span m="141981">multiply</span> <span m="142363">in</span> <span m="142745">the</span>
  <span m="143126">ALU</span> <span m="143508">stage,</span> <span m="143890">or</span>
  <span m="144272">accessing</span> <span m="144654">a</span> <span m="145036">large</span>
  <span m="145418">cache</span> <span m="145800">in</span> <span m="146097">the</span>
  <span m="146394">IF</span> <span m="146692">or</span> <span m="146989">MEM</span>
  <span m="147286">stages</span> <span m="147584">-</span> <span m="147881">force</span>
  <span m="148178">t_CLK</span> <span m="148476">to</span> <span m="148773">be</span>
  <span m="149071">large</span> <span m="149368">to</span> <span m="149665">accommodate</span>
  <span m="149963">all</span> <span m="150260">the</span> <span m="150557">work</span>
  <span m="150855">that</span> <span m="151152">has</span> <span m="151450">to</span>
  <span m="151960">be</span> <span m="152470">done</span> <span m="152980">in</span>
  <span m="153490">one</span> <span m="154000">cycle.</span></p><p><span m="154510">The</span>
  <span m="154846">order</span> <span m="155182">of</span> <span m="155518">the</span>
  <span m="155854">instructions</span> <span m="156190">in</span> <span m="156526">the</span>
  <span m="156862">pipeline</span> <span m="157198">is</span> <span m="157534">fixed.</span></p><p><span
  m="157870">If,</span> <span m="158196">say,</span> <span m="158523">a</span> <span
  m="158850">LD</span> <span m="159176">instruction</span> <span m="159503">is</span>
  <span m="159830">delayed</span> <span m="160156">in</span> <span m="160483">the</span>
  <span m="160810">MEM</span> <span m="161136">stage</span> <span m="161463">because</span>
  <span m="161790">of</span> <span m="162116">a</span> <span m="162443">cache</span>
  <span m="162770">miss,</span> <span m="163096">all</span> <span m="163423">the</span>
  <span m="163750">instructions</span> <span m="164095">in</span> <span m="164441">earlier</span>
  <span m="164787">stages</span> <span m="165132">are</span> <span m="165478">also</span>
  <span m="165824">delayed</span> <span m="166170">even</span> <span m="166515">though</span>
  <span m="166861">their</span> <span m="167207">execution</span> <span m="167552">may</span>
  <span m="167898">not</span> <span m="168244">depend</span> <span m="168590">on</span>
  <span m="168957">the</span> <span m="169324">value</span> <span m="169691">produced</span>
  <span m="170058">by</span> <span m="170425">the</span> <span m="170792">LD.</span></p><p><span
  m="171160">The</span> <span m="171413">order</span> <span m="171666">of</span> <span
  m="171920">instructions</span> <span m="172173">in</span> <span m="172426">the</span>
  <span m="172680">pipeline</span> <span m="172933">always</span> <span m="173186">reflects</span>
  <span m="173440">the</span> <span m="173693">order</span> <span m="173946">in</span>
  <span m="174200">which</span> <span m="174453">they</span> <span m="174706">were</span>
  <span m="174960">fetched</span> <span m="175428">by</span> <span m="175896">the</span>
  <span m="176364">IF</span> <span m="176832">stage.</span></p><p><span m="177300">Let's</span>
  <span m="177623">look</span> <span m="177946">into</span> <span m="178270">what</span>
  <span m="178593">it</span> <span m="178916">would</span> <span m="179240">take</span>
  <span m="179563">to</span> <span m="179886">relax</span> <span m="180210">these</span>
  <span m="180533">constraints</span> <span m="180856">and</span> <span m="181180">hopefully</span>
  <span m="181503">improve</span> <span m="181826">program</span> <span m="182150">runtimes.</span></p><p><span
  m="184180">Increasing</span> <span m="184492">the</span> <span m="184804">number</span>
  <span m="185116">of</span> <span m="185428">pipeline</span> <span m="185740">stages</span>
  <span m="186052">should</span> <span m="186364">allow</span> <span m="186676">us</span>
  <span m="186988">to</span> <span m="187300">decrease</span> <span m="187612">the</span>
  <span m="187924">clock</span> <span m="188236">cycle</span> <span m="188548">time.</span></p><p><span
  m="188860">We'd</span> <span m="189323">add</span> <span m="189787">stages</span>
  <span m="190250">to</span> <span m="190714">break</span> <span m="191177">up</span>
  <span m="191641">performance</span> <span m="192105">bottlenecks,</span> <span m="192568">e.g.,</span>
  <span m="193032">adding</span> <span m="193495">additional</span> <span m="193959">pipeline</span>
  <span m="194422">stages</span> <span m="194886">(MEM1</span> <span m="195350">and</span>
  <span m="195840">MEM2)</span> <span m="196331">to</span> <span m="196822">allow</span>
  <span m="197313">a</span> <span m="197804">longer</span> <span m="198295">time</span>
  <span m="198785">for</span> <span m="199276">memory</span> <span m="199767">operations</span>
  <span m="200258">to</span> <span m="200749">complete.</span></p><p><span m="201240">This</span>
  <span m="201581">comes</span> <span m="201923">at</span> <span m="202265">cost</span>
  <span m="202607">to</span> <span m="202949">CPI_stall</span> <span m="203291">since</span>
  <span m="203633">each</span> <span m="203975">additional</span> <span m="204316">MEM</span>
  <span m="204658">stage</span> <span m="205000">means</span> <span m="205342">that</span>
  <span m="205684">more</span> <span m="206026">NOP</span> <span m="206368">bubbles</span>
  <span m="206710">have</span> <span m="207099">to</span> <span m="207488">be</span>
  <span m="207877">introduced</span> <span m="208266">when</span> <span m="208655">there's</span>
  <span m="209044">a</span> <span m="209433">LD</span> <span m="209822">data</span>
  <span m="210211">hazard.</span></p><p><span m="210600">Deeper</span> <span m="211030">pipelines</span>
  <span m="211461">mean</span> <span m="211892">that</span> <span m="212323">the</span>
  <span m="212753">processor</span> <span m="213184">will</span> <span m="213615">be</span>
  <span m="214046">executing</span> <span m="214476">more</span> <span m="214907">instructions</span>
  <span m="215338">in</span> <span m="215769">parallel.</span></p><p><span m="216200">Let's</span>
  <span m="216563">interrupt</span> <span m="216927">enumerating</span> <span m="217291">our</span>
  <span m="217655">performance</span> <span m="218019">shopping</span> <span m="218383">list</span>
  <span m="218746">to</span> <span m="219110">think</span> <span m="219474">about</span>
  <span m="219838">limits</span> <span m="220202">to</span> <span m="220566">pipeline</span>
  <span m="220930">depth.</span></p><p><span m="222120">Each</span> <span m="222507">additional</span>
  <span m="222895">pipeline</span> <span m="223283">stage</span> <span m="223670">includes</span>
  <span m="224058">some</span> <span m="224446">additional</span> <span m="224833">overhead</span>
  <span m="225221">costs</span> <span m="225609">to</span> <span m="225996">the</span>
  <span m="226384">time</span> <span m="226772">budget.</span></p><p><span m="227160">We</span>
  <span m="227508">have</span> <span m="227856">to</span> <span m="228204">account</span>
  <span m="228552">for</span> <span m="228900">the</span> <span m="229248">propagation,</span>
  <span m="229596">setup,</span> <span m="229944">and</span> <span m="230292">hold</span>
  <span m="230640">times</span> <span m="230988">for</span> <span m="231336">the</span>
  <span m="231684">pipeline</span> <span m="232032">registers.</span></p><p><span
  m="232380">And</span> <span m="232661">we</span> <span m="232942">usually</span>
  <span m="233223">have</span> <span m="233504">to</span> <span m="233785">allow</span>
  <span m="234066">a</span> <span m="234347">bit</span> <span m="234628">of</span>
  <span m="234910">extra</span> <span m="235191">time</span> <span m="235472">to</span>
  <span m="235753">account</span> <span m="236034">for</span> <span m="236315">clock</span>
  <span m="236596">skew,</span> <span m="236877">i.e.,</span> <span m="237158">the</span>
  <span m="237440">difference</span> <span m="237758">in</span> <span m="238076">arrival</span>
  <span m="238394">time</span> <span m="238712">of</span> <span m="239030">the</span>
  <span m="239349">clock</span> <span m="239667">edge</span> <span m="239985">at</span>
  <span m="240303">each</span> <span m="240621">register.</span></p><p><span m="240940">And,</span>
  <span m="241320">finally,</span> <span m="241701">since</span> <span m="242082">we</span>
  <span m="242462">can't</span> <span m="242843">always</span> <span m="243224">divide</span>
  <span m="243605">the</span> <span m="243985">work</span> <span m="244366">exactly</span>
  <span m="244747">evenly</span> <span m="245127">between</span> <span m="245508">the</span>
  <span m="245889">pipeline</span> <span m="246270">stages,</span> <span m="246609">there</span>
  <span m="246948">will</span> <span m="247287">be</span> <span m="247627">some</span>
  <span m="247966">wasted</span> <span m="248305">time</span> <span m="248645">in</span>
  <span m="248984">the</span> <span m="249323">stages</span> <span m="249662">that</span>
  <span m="250002">have</span> <span m="250341">less</span> <span m="250680">work.</span></p><p><span
  m="251020">We'll</span> <span m="251432">capture</span> <span m="251844">all</span>
  <span m="252256">of</span> <span m="252668">these</span> <span m="253080">effects</span>
  <span m="253492">as</span> <span m="253904">an</span> <span m="254316">additional</span>
  <span m="254728">per-stage</span> <span m="255140">time</span> <span m="255552">overhead</span>
  <span m="255964">of</span> <span m="256376">O.</span></p><p><span m="256789">If</span>
  <span m="257111">the</span> <span m="257433">original</span> <span m="257756">clock</span>
  <span m="258078">period</span> <span m="258401">was</span> <span m="258723">T,</span>
  <span m="259045">then</span> <span m="259368">with</span> <span m="259690">N</span>
  <span m="260013">pipeline</span> <span m="260335">stages,</span> <span m="260657">the</span>
  <span m="260980">clock</span> <span m="261302">period</span> <span m="261625">will</span>
  <span m="261947">be</span> <span m="262270">T/N</span> <span m="263089">+</span>
  <span m="263909">O.</span></p><p><span m="264729">At</span> <span m="265309">the</span>
  <span m="265889">limit,</span> <span m="266469">as</span> <span m="267049">N</span>
  <span m="267629">becomes</span> <span m="268209">large,</span> <span m="268789">the</span>
  <span m="269369">speedup</span> <span m="269949">approaches</span> <span m="270529">T/O.</span></p><p><span
  m="271110">In</span> <span m="271395">other</span> <span m="271680">words,</span>
  <span m="271965">the</span> <span m="272250">overhead</span> <span m="272535">starts</span>
  <span m="272820">to</span> <span m="273105">dominate</span> <span m="273390">as</span>
  <span m="273675">the</span> <span m="273960">time</span> <span m="274245">spent</span>
  <span m="274530">on</span> <span m="274815">work</span> <span m="275100">in</span>
  <span m="275385">each</span> <span m="275670">stage</span> <span m="275955">becomes</span>
  <span m="276240">smaller</span> <span m="277000">and</span> <span m="277760">smaller.</span></p><p><span
  m="278520">At</span> <span m="278859">some</span> <span m="279198">point</span>
  <span m="279538">adding</span> <span m="279877">additional</span> <span m="280216">pipeline</span>
  <span m="280556">stages</span> <span m="280895">has</span> <span m="281234">almost</span>
  <span m="281574">no</span> <span m="281913">impact</span> <span m="282252">on</span>
  <span m="282592">the</span> <span m="282931">clock</span> <span m="283270">period.</span></p><p><span
  m="283610">As</span> <span m="284136">a</span> <span m="284663">data</span> <span
  m="285189">point,</span> <span m="285716">the</span> <span m="286243">Intel</span>
  <span m="286769">Core-2</span> <span m="287296">x86</span> <span m="287822">chips</span>
  <span m="288349">(nicknamed</span> <span m="288876">&quot;Nehalem&quot;)</span>
  <span m="289402">have</span> <span m="289929">a</span> <span m="290455">14-stage</span>
  <span m="290982">execution</span> <span m="291509">pipeline.</span></p><p><span
  m="292509">Okay,</span> <span m="293006">back</span> <span m="293503">to</span>
  <span m="294000">our</span> <span m="294498">performance</span> <span m="294995">shopping</span>
  <span m="295492">list&hellip;</span> <span m="295990">There</span> <span m="296312">may</span>
  <span m="296635">be</span> <span m="296957">times</span> <span m="297280">we</span>
  <span m="297602">can</span> <span m="297925">arrange</span> <span m="298247">to</span>
  <span m="298570">execute</span> <span m="298892">two</span> <span m="299215">or</span>
  <span m="299537">more</span> <span m="299860">instructions</span> <span m="300182">in</span>
  <span m="300505">parallel,</span> <span m="300827">assuming</span> <span m="301150">that</span>
  <span m="301536">their</span> <span m="301922">executions</span> <span m="302308">are</span>
  <span m="302695">independent</span> <span m="303081">from</span> <span m="303467">each</span>
  <span m="303853">other.</span></p><p><span m="304240">This</span> <span m="304577">would</span>
  <span m="304914">increase</span> <span m="305251">CPI_ideal</span> <span m="305588">at</span>
  <span m="305925">the</span> <span m="306262">cost</span> <span m="306600">of</span>
  <span m="306937">increasing</span> <span m="307274">the</span> <span m="307611">complexity</span>
  <span m="307948">of</span> <span m="308285">each</span> <span m="308622">pipeline</span>
  <span m="308960">stage</span> <span m="309598">to</span> <span m="310237">deal</span>
  <span m="310876">with</span> <span m="311515">concurrent</span> <span m="312154">execution</span>
  <span m="312793">of</span> <span m="313432">multiple</span> <span m="314071">instructions.</span></p><p><span
  m="314710">If</span> <span m="315017">there's</span> <span m="315324">an</span>
  <span m="315631">instruction</span> <span m="315938">stalled</span> <span m="316245">in</span>
  <span m="316552">the</span> <span m="316859">pipeline</span> <span m="317166">by</span>
  <span m="317473">a</span> <span m="317780">data</span> <span m="318087">hazard,</span>
  <span m="318394">there</span> <span m="318701">may</span> <span m="319008">be</span>
  <span m="319315">following</span> <span m="319622">instructions</span> <span m="319930">whose</span>
  <span m="320560">execution</span> <span m="321190">could</span> <span m="321820">still</span>
  <span m="322450">proceed.</span></p><p><span m="323080">Allowing</span> <span m="323509">instructions</span>
  <span m="323939">to</span> <span m="324369">pass</span> <span m="324799">each</span>
  <span m="325229">other</span> <span m="325659">in</span> <span m="326089">the</span>
  <span m="326519">pipeline</span> <span m="326949">is</span> <span m="327379">called</span>
  <span m="327809">out-of-order</span> <span m="328239">execution.</span></p><p><span
  m="328669">We'd</span> <span m="328949">have</span> <span m="329230">to</span> <span
  m="329510">be</span> <span m="329791">careful</span> <span m="330072">to</span>
  <span m="330352">ensure</span> <span m="330633">that</span> <span m="330914">changing</span>
  <span m="331194">the</span> <span m="331475">execution</span> <span m="331755">order</span>
  <span m="332036">didn't</span> <span m="332317">affect</span> <span m="332597">the</span>
  <span m="332878">values</span> <span m="333159">produced</span> <span m="333964">by</span>
  <span m="334769">the</span> <span m="335574">program.</span></p><p><span m="336379">More</span>
  <span m="336666">pipeline</span> <span m="336954">stages</span> <span m="337241">and</span>
  <span m="337529">wider</span> <span m="337816">pipeline</span> <span m="338104">stages</span>
  <span m="338391">increase</span> <span m="338679">the</span> <span m="338966">amount</span>
  <span m="339254">of</span> <span m="339541">work</span> <span m="339829">that</span>
  <span m="340116">has</span> <span m="340404">to</span> <span m="340691">be</span>
  <span m="340979">discarded</span> <span m="341730">on</span> <span m="342482">control</span>
  <span m="343233">hazards,</span> <span m="343985">potentially</span> <span m="344736">increasing</span>
  <span m="345488">CPI_stall.</span></p><p><span m="346240">So</span> <span m="346580">it's</span>
  <span m="346921">important</span> <span m="347262">to</span> <span m="347602">minimize</span>
  <span m="347943">the</span> <span m="348284">number</span> <span m="348625">of</span>
  <span m="348965">control</span> <span m="349306">hazards</span> <span m="349647">by</span>
  <span m="349987">predicting</span> <span m="350328">the</span> <span m="350669">results</span>
  <span m="351010">of</span> <span m="351381">a</span> <span m="351752">branch</span>
  <span m="352123">(i.e.,</span> <span m="352494">taken</span> <span m="352865">or</span>
  <span m="353236">not</span> <span m="353607">taken)</span> <span m="353978">so</span>
  <span m="354350">that</span> <span m="354721">we</span> <span m="355092">increase</span>
  <span m="355463">the</span> <span m="355834">chances</span> <span m="356205">that</span>
  <span m="356576">the</span> <span m="356947">instructions</span> <span m="357319">in</span>
  <span m="357680">the</span> <span m="358041">pipeline</span> <span m="358402">are</span>
  <span m="358763">the</span> <span m="359124">ones</span> <span m="359485">we'll</span>
  <span m="359846">want</span> <span m="360207">to</span> <span m="360568">execute.</span></p><p><span
  m="360930">Our</span> <span m="361348">ability</span> <span m="361766">to</span>
  <span m="362184">exploit</span> <span m="362603">wider</span> <span m="363021">pipelines</span>
  <span m="363439">and</span> <span m="363857">out-of-order</span> <span m="364276">execution</span>
  <span m="364694">depends</span> <span m="365112">on</span> <span m="365530">finding</span>
  <span m="365949">instructions</span> <span m="366404">that</span> <span m="366860">can</span>
  <span m="367315">be</span> <span m="367771">executed</span> <span m="368226">in</span>
  <span m="368682">parallel</span> <span m="369137">or</span> <span m="369593">in</span>
  <span m="370048">different</span> <span m="370504">orders.</span></p><p><span m="370960">Collectively</span>
  <span m="371496">these</span> <span m="372032">properties</span> <span m="372568">are</span>
  <span m="373104">called</span> <span m="373640">&quot;instruction-level</span> <span
  m="374176">parallelism&quot;</span> <span m="374712">(ILP).</span></p><p><span m="375249">Here's</span>
  <span m="375657">an</span> <span m="376065">example</span> <span m="376473">that</span>
  <span m="376881">will</span> <span m="377289">let</span> <span m="377698">us</span>
  <span m="378106">explore</span> <span m="378514">the</span> <span m="378922">amount</span>
  <span m="379330">of</span> <span m="379739">ILP</span> <span m="380147">that</span>
  <span m="380555">might</span> <span m="380963">be</span> <span m="381371">available.</span></p><p><span
  m="381780">On</span> <span m="382106">the</span> <span m="382433">left</span> <span
  m="382760">is</span> <span m="383087">an</span> <span m="383414">unoptimized</span>
  <span m="383740">loop</span> <span m="384067">that</span> <span m="384394">computes</span>
  <span m="384721">the</span> <span m="385048">product</span> <span m="385374">of</span>
  <span m="385701">the</span> <span m="386028">first</span> <span m="386355">N</span>
  <span m="386682">integers.</span></p><p><span m="387009">On</span> <span m="387359">the</span>
  <span m="387709">right,</span> <span m="388059">we've</span> <span m="388409">rewritten</span>
  <span m="388759">the</span> <span m="389109">code,</span> <span m="389459">placing</span>
  <span m="389809">instructions</span> <span m="390159">that</span> <span m="390509">could</span>
  <span m="390859">be</span> <span m="391209">executed</span> <span m="391559">concurrently</span>
  <span m="391909">on</span> <span m="392469">the</span> <span m="393029">same</span>
  <span m="393589">line.</span></p><p><span m="394150">First</span> <span m="394617">notice</span>
  <span m="395085">the</span> <span m="395553">red</span> <span m="396021">line</span>
  <span m="396488">following</span> <span m="396956">the</span> <span m="397424">BF</span>
  <span m="397892">instruction.</span></p><p><span m="398360">Instructions</span>
  <span m="398703">below</span> <span m="399047">the</span> <span m="399390">line</span>
  <span m="399734">should</span> <span m="400077">only</span> <span m="400421">be</span>
  <span m="400764">executed</span> <span m="401108">if</span> <span m="401451">the</span>
  <span m="401795">BF</span> <span m="402138">is</span> <span m="402482">*not*</span>
  <span m="402825">taken.</span></p><p><span m="403169">That</span> <span m="403413">doesn't</span>
  <span m="403658">mean</span> <span m="403903">we</span> <span m="404147">couldn't</span>
  <span m="404392">start</span> <span m="404637">executing</span> <span m="404882">them</span>
  <span m="405126">before</span> <span m="405371">the</span> <span m="405616">results</span>
  <span m="405861">of</span> <span m="406105">the</span> <span m="406350">branch</span>
  <span m="406595">are</span> <span m="406840">known,</span> <span m="407137">but</span>
  <span m="407435">if</span> <span m="407733">we</span> <span m="408031">executed</span>
  <span m="408328">them</span> <span m="408626">before</span> <span m="408924">the</span>
  <span m="409222">branch,</span> <span m="409520">we</span> <span m="409850">would</span>
  <span m="410180">have</span> <span m="410510">to</span> <span m="410840">be</span>
  <span m="411170">prepared</span> <span m="411500">to</span> <span m="411830">throw</span>
  <span m="412160">away</span> <span m="412490">their</span> <span m="412820">results</span>
  <span m="413150">if</span> <span m="413480">the</span> <span m="413810">branch</span>
  <span m="414140">was</span> <span m="414470">taken.</span></p><p><span m="414800">The</span>
  <span m="415164">possible</span> <span m="415529">execution</span> <span m="415893">order</span>
  <span m="416258">is</span> <span m="416622">constrained</span> <span m="416987">by</span>
  <span m="417351">the</span> <span m="417716">read-after-write</span> <span m="418080">(RAW)</span>
  <span m="418445">dependencies</span> <span m="418810">shown</span> <span m="419164">by</span>
  <span m="419518">the</span> <span m="419872">red</span> <span m="420226">arrows.</span></p><p><span
  m="420580">We</span> <span m="420933">recognize</span> <span m="421286">these</span>
  <span m="421640">as</span> <span m="421993">the</span> <span m="422347">potential</span>
  <span m="422700">data</span> <span m="423054">hazards</span> <span m="423407">that</span>
  <span m="423761">occur</span> <span m="424114">when</span> <span m="424468">an</span>
  <span m="424821">operand</span> <span m="425175">value</span> <span m="425528">for</span>
  <span m="425882">one</span> <span m="426235">instruction</span> <span m="426589">depends</span>
  <span m="427029">on</span> <span m="427469">the</span> <span m="427909">result</span>
  <span m="428349">of</span> <span m="428789">an</span> <span m="429229">earlier</span>
  <span m="429669">instruction.</span></p><p><span m="430110">In</span> <span m="430415">our</span>
  <span m="430720">5-stage</span> <span m="431025">pipeline,</span> <span m="431330">we</span>
  <span m="431635">were</span> <span m="431940">able</span> <span m="432245">to</span>
  <span m="432550">resolve</span> <span m="432855">many</span> <span m="433160">of</span>
  <span m="433465">these</span> <span m="433770">hazards</span> <span m="434075">by</span>
  <span m="434380">bypassing</span> <span m="434685">values</span> <span m="434990">from</span>
  <span m="435403">the</span> <span m="435817">ALU,</span> <span m="436230">MEM,</span>
  <span m="436644">and</span> <span m="437057">WB</span> <span m="437471">stages</span>
  <span m="437884">back</span> <span m="438298">to</span> <span m="438711">the</span>
  <span m="439125">RF</span> <span m="439538">stage</span> <span m="439952">where</span>
  <span m="440365">operand</span> <span m="440779">values</span> <span m="441192">are</span>
  <span m="441606">determined.</span></p><p><span m="442020">Of</span> <span m="442404">course,</span>
  <span m="442789">bypassing</span> <span m="443173">will</span> <span m="443558">only</span>
  <span m="443943">work</span> <span m="444327">when</span> <span m="444712">the</span>
  <span m="445096">instruction</span> <span m="445481">has</span> <span m="445866">been</span>
  <span m="446250">executed</span> <span m="446635">so</span> <span m="447019">its</span>
  <span m="447404">result</span> <span m="447789">is</span> <span m="448234">available</span>
  <span m="448679">for</span> <span m="449124">bypassing!</span></p><p><span m="449570">So,</span>
  <span m="449913">in</span> <span m="450257">this</span> <span m="450601">case,</span>
  <span m="450944">the</span> <span m="451288">arrows</span> <span m="451632">are</span>
  <span m="451975">showing</span> <span m="452319">us</span> <span m="452663">the</span>
  <span m="453006">constraints</span> <span m="453350">on</span> <span m="453694">execution</span>
  <span m="454037">order</span> <span m="454381">that</span> <span m="454725">guarantee</span>
  <span m="455069">bypassing</span> <span m="455971">will</span> <span m="456874">be</span>
  <span m="457777">possible.</span></p><p><span m="458680">There</span> <span m="459078">are</span>
  <span m="459476">other</span> <span m="459875">constraints</span> <span m="460273">on</span>
  <span m="460672">execution</span> <span m="461070">order.</span></p><p><span m="461469">The</span>
  <span m="461889">green</span> <span m="462309">arrow</span> <span m="462729">identifies</span>
  <span m="463149">a</span> <span m="463569">write-after-write</span> <span m="463989">(WAW)</span>
  <span m="464409">constraint</span> <span m="464829">between</span> <span m="465249">two</span>
  <span m="465669">instructions</span> <span m="466089">with</span> <span m="466695">the</span>
  <span m="467301">same</span> <span m="467907">destination</span> <span m="468513">register.</span></p><p><span
  m="469120">In</span> <span m="469442">order</span> <span m="469764">to</span> <span
  m="470086">ensure</span> <span m="470408">the</span> <span m="470730">correct</span>
  <span m="471052">value</span> <span m="471375">is</span> <span m="471697">in</span>
  <span m="472019">R2</span> <span m="472341">at</span> <span m="472663">the</span>
  <span m="472985">end</span> <span m="473308">of</span> <span m="473630">the</span>
  <span m="473952">loop,</span> <span m="474274">the</span> <span m="474596">LD(r,R2)</span>
  <span m="474918">instruction</span> <span m="475241">has</span> <span m="475601">to</span>
  <span m="475961">store</span> <span m="476321">its</span> <span m="476681">result</span>
  <span m="477041">into</span> <span m="477401">the</span> <span m="477761">register</span>
  <span m="478121">file</span> <span m="478481">after</span> <span m="478841">the</span>
  <span m="479201">result</span> <span m="479561">of</span> <span m="479921">the</span>
  <span m="480281">CMPLT</span> <span m="480641">instruction</span> <span m="481001">is</span>
  <span m="481389">stored</span> <span m="481777">into</span> <span m="482165">the</span>
  <span m="482553">register</span> <span m="482941">file.</span></p><p><span m="483330">Similarly,</span>
  <span m="483757">the</span> <span m="484184">blue</span> <span m="484611">arrow</span>
  <span m="485038">shows</span> <span m="485465">a</span> <span m="485892">write-after-read</span>
  <span m="486319">(WAR)</span> <span m="486746">constraint</span> <span m="487173">that</span>
  <span m="487600">ensures</span> <span m="488027">that</span> <span m="488454">the</span>
  <span m="488881">correct</span> <span m="489309">values</span> <span m="489717">are</span>
  <span m="490126">used</span> <span m="490534">when</span> <span m="490943">accessing</span>
  <span m="491351">a</span> <span m="491760">register.</span></p><p><span m="492169">In</span>
  <span m="492539">this</span> <span m="492910">case,</span> <span m="493280">LD(r,R2)</span>
  <span m="493651">must</span> <span m="494021">store</span> <span m="494392">into</span>
  <span m="494762">R2</span> <span m="495133">after</span> <span m="495504">the</span>
  <span m="495874">Ra</span> <span m="496245">operand</span> <span m="496615">for</span>
  <span m="496986">the</span> <span m="497356">BF</span> <span m="497727">has</span>
  <span m="498097">been</span> <span m="498468">read</span> <span m="498839">from</span>
  <span m="499829">R2.</span></p><p><span m="500819">As</span> <span m="501180">it</span>
  <span m="501542">turns</span> <span m="501904">out,</span> <span m="502266">WAW</span>
  <span m="502628">and</span> <span m="502990">WAR</span> <span m="503352">constraints</span>
  <span m="503714">can</span> <span m="504076">be</span> <span m="504438">eliminated</span>
  <span m="504800">if</span> <span m="505162">we</span> <span m="505524">give</span>
  <span m="505886">each</span> <span m="506248">instruction</span> <span m="506610">result</span>
  <span m="507215">a</span> <span m="507821">unique</span> <span m="508427">register</span>
  <span m="509033">name.</span></p><p><span m="509639">This</span> <span m="509956">can</span>
  <span m="510273">actually</span> <span m="510591">be</span> <span m="510908">done</span>
  <span m="511225">relatively</span> <span m="511543">easily</span> <span m="511860">by</span>
  <span m="512177">the</span> <span m="512495">hardware</span> <span m="512812">by</span>
  <span m="513129">using</span> <span m="513447">a</span> <span m="513764">generous</span>
  <span m="514081">supply</span> <span m="514399">of</span> <span m="514776">temporary</span>
  <span m="515154">registers,</span> <span m="515532">but</span> <span m="515909">we</span>
  <span m="516287">won't</span> <span m="516665">go</span> <span m="517042">into</span>
  <span m="517420">the</span> <span m="517798">details</span> <span m="518175">of</span>
  <span m="518553">renaming</span> <span m="518931">here.</span></p><p><span m="519309">The</span>
  <span m="519633">use</span> <span m="519957">of</span> <span m="520281">temporary</span>
  <span m="520606">registers</span> <span m="520930">also</span> <span m="521254">makes</span>
  <span m="521579">it</span> <span m="521903">easy</span> <span m="522227">to</span>
  <span m="522551">discard</span> <span m="522876">results</span> <span m="523200">of</span>
  <span m="523524">instructions</span> <span m="523849">executed</span> <span m="524302">before</span>
  <span m="524756">we</span> <span m="525210">know</span> <span m="525664">the</span>
  <span m="526118">outcomes</span> <span m="526572">of</span> <span m="527026">branches.</span></p><p><span
  m="527480">In</span> <span m="527827">this</span> <span m="528174">example,</span>
  <span m="528522">we</span> <span m="528869">discovered</span> <span m="529216">that</span>
  <span m="529564">the</span> <span m="529911">potential</span> <span m="530258">concurrency</span>
  <span m="530606">was</span> <span m="530953">actually</span> <span m="531300">pretty</span>
  <span m="531648">good</span> <span m="531995">for</span> <span m="532342">the</span>
  <span m="532690">instructions</span> <span m="533250">following</span> <span m="533810">the</span>
  <span m="534370">BF.</span></p><p><span m="534930">To</span> <span m="535271">take</span>
  <span m="535612">advantage</span> <span m="535954">of</span> <span m="536295">this</span>
  <span m="536636">potential</span> <span m="536978">concurrency,</span> <span m="537319">we'll</span>
  <span m="537660">need</span> <span m="538002">to</span> <span m="538343">modify</span>
  <span m="538684">the</span> <span m="539026">pipeline</span> <span m="539367">to</span>
  <span m="539708">execute</span> <span m="540050">some</span> <span m="540494">number</span>
  <span m="540938">N</span> <span m="541382">of</span> <span m="541827">instructions</span>
  <span m="542271">in</span> <span m="542715">parallel.</span></p><p><span m="543160">If</span>
  <span m="543530">we</span> <span m="543901">can</span> <span m="544271">sustain</span>
  <span m="544642">that</span> <span m="545012">rate</span> <span m="545383">of</span>
  <span m="545753">execution,</span> <span m="546124">CPI_ideal</span> <span m="546495">would</span>
  <span m="546865">then</span> <span m="547236">be</span> <span m="547606">1/N</span>
  <span m="547977">since</span> <span m="548347">we'd</span> <span m="548718">complete</span>
  <span m="549089">the</span> <span m="549515">execution</span> <span m="549941">of</span>
  <span m="550367">N</span> <span m="550794">instructions</span> <span m="551220">in</span>
  <span m="551646">each</span> <span m="552073">clock</span> <span m="552499">cycle</span>
  <span m="552925">as</span> <span m="553352">they</span> <span m="553778">exited</span>
  <span m="554204">the</span> <span m="554631">final</span> <span m="555057">pipeline</span>
  <span m="555483">stage.</span></p><p><span m="555910">So</span> <span m="556320">what</span>
  <span m="556730">value</span> <span m="557140">should</span> <span m="557550">we</span>
  <span m="557960">choose</span> <span m="558370">for</span> <span m="558780">N?</span></p><p><span
  m="559190">Instructions</span> <span m="559509">that</span> <span m="559828">are</span>
  <span m="560147">executed</span> <span m="560467">by</span> <span m="560786">different</span>
  <span m="561105">ALU</span> <span m="561425">hardware</span> <span m="561744">are</span>
  <span m="562063">easy</span> <span m="562382">to</span> <span m="562702">execute</span>
  <span m="563021">in</span> <span m="563340">parallel,</span> <span m="563660">e.g.,</span>
  <span m="564192">ADDs</span> <span m="564724">and</span> <span m="565256">SHIFTs,</span>
  <span m="565788">or</span> <span m="566320">integer</span> <span m="566852">and</span>
  <span m="567384">floating-point</span> <span m="567916">operations.</span></p><p><span
  m="568449">Of</span> <span m="568812">course,</span> <span m="569175">if</span>
  <span m="569538">we</span> <span m="569901">provided</span> <span m="570264">multiple</span>
  <span m="570627">adders,</span> <span m="570991">we</span> <span m="571354">could</span>
  <span m="571717">execute</span> <span m="572080">multiple</span> <span m="572443">integer</span>
  <span m="572806">arithmetic</span> <span m="573170">instructions</span> <span m="574650">concurrently.</span></p><p><span
  m="576130">Having</span> <span m="576590">separate</span> <span m="577051">hardware</span>
  <span m="577512">for</span> <span m="577973">address</span> <span m="578434">arithmetic</span>
  <span m="578895">(called</span> <span m="579355">LD/ST</span> <span m="579816">units)</span>
  <span m="580277">would</span> <span m="580738">support</span> <span m="581199">concurrent</span>
  <span m="581660">execution</span> <span m="582293">of</span> <span m="582927">LD/ST</span>
  <span m="583561">instructions</span> <span m="584195">and</span> <span m="584828">integer</span>
  <span m="585462">arithmetic</span> <span m="586096">instructions.</span></p><p><span
  m="586730">This</span> <span m="587002">set</span> <span m="587275">of</span> <span
  m="587547">lecture</span> <span m="587820">slides</span> <span m="588092">from</span>
  <span m="588365">Duke</span> <span m="588637">gives</span> <span m="588910">a</span>
  <span m="589182">nice</span> <span m="589455">overview</span> <span m="589727">of</span>
  <span m="590000">techniques</span> <span m="590272">used</span> <span m="590545">in</span>
  <span m="590817">each</span> <span m="591090">pipeline</span> <span m="591785">stage</span>
  <span m="592480">to</span> <span m="593175">support</span> <span m="593870">concurrent</span>
  <span m="594565">execution.</span></p><p><span m="595260">Basically</span> <span
  m="595566">by</span> <span m="595873">increasing</span> <span m="596180">the</span>
  <span m="596487">number</span> <span m="596794">of</span> <span m="597101">functional</span>
  <span m="597408">units</span> <span m="597715">in</span> <span m="598021">the</span>
  <span m="598328">ALU</span> <span m="598635">and</span> <span m="598942">the</span>
  <span m="599249">number</span> <span m="599556">of</span> <span m="599863">memory</span>
  <span m="600170">ports</span> <span m="600453">on</span> <span m="600737">the</span>
  <span m="601020">register</span> <span m="601304">file</span> <span m="601587">and</span>
  <span m="601871">main</span> <span m="602154">memory,</span> <span m="602438">we</span>
  <span m="602721">would</span> <span m="603005">have</span> <span m="603288">what</span>
  <span m="603572">it</span> <span m="603855">takes</span> <span m="604139">to</span>
  <span m="604422">support</span> <span m="604706">concurrent</span> <span m="604990">execution</span>
  <span m="605632">of</span> <span m="606275">multiple</span> <span m="606917">instructions.</span></p><p><span
  m="607560">So,</span> <span m="608149">what's</span> <span m="608739">the</span>
  <span m="609329">right</span> <span m="609919">tradeoff</span> <span m="610509">between</span>
  <span m="611099">increased</span> <span m="611689">circuit</span> <span m="612279">costs</span>
  <span m="612869">and</span> <span m="613459">increased</span> <span m="614049">concurrency?</span></p><p><span
  m="614639">As</span> <span m="614980">a</span> <span m="615322">data</span> <span
  m="615664">point,</span> <span m="616006">the</span> <span m="616348">Intel</span>
  <span m="616690">Nehelam</span> <span m="617032">core</span> <span m="617374">can</span>
  <span m="617716">complete</span> <span m="618058">up</span> <span m="618400">to</span>
  <span m="618742">4</span> <span m="619084">micro-operations</span> <span m="619426">per</span>
  <span m="619768">cycle,</span> <span m="620110">where</span> <span m="620585">each</span>
  <span m="621060">micro-operation</span> <span m="621536">corresponds</span> <span
  m="622011">to</span> <span m="622487">one</span> <span m="622962">of</span> <span
  m="623438">our</span> <span m="623913">simple</span> <span m="624389">RISC</span>
  <span m="624864">instructions.</span></p><p><span m="625340">Here's</span> <span
  m="625969">a</span> <span m="626598">simplified</span> <span m="627227">diagram</span>
  <span m="627856">of</span> <span m="628485">a</span> <span m="629114">modern</span>
  <span m="629743">out-of-order</span> <span m="630372">superscalar</span> <span m="631001">processor.</span></p><p><span
  m="631630">Instruction</span> <span m="631970">fetch</span> <span m="632311">and</span>
  <span m="632652">decode</span> <span m="632993">handles,</span> <span m="633334">say,</span>
  <span m="633675">4</span> <span m="634016">instructions</span> <span m="634357">at</span>
  <span m="634698">a</span> <span m="635039">time.</span></p><p><span m="635380">The</span>
  <span m="635700">ability</span> <span m="636021">to</span> <span m="636342">sustain</span>
  <span m="636662">this</span> <span m="636983">execution</span> <span m="637304">rate</span>
  <span m="637625">depends</span> <span m="637945">heavily</span> <span m="638266">on</span>
  <span m="638587">the</span> <span m="638907">ability</span> <span m="639228">to</span>
  <span m="639549">predict</span> <span m="639870">the</span> <span m="640225">outcome</span>
  <span m="640580">of</span> <span m="640936">branch</span> <span m="641291">instructions,</span>
  <span m="641646">ensuring</span> <span m="642002">that</span> <span m="642357">the</span>
  <span m="642713">wide</span> <span m="643068">pipeline</span> <span m="643423">will</span>
  <span m="643779">be</span> <span m="644134">mostly</span> <span m="644490">filled</span>
  <span m="644956">with</span> <span m="645422">instructions</span> <span m="645888">we</span>
  <span m="646355">actually</span> <span m="646821">want</span> <span m="647287">to</span>
  <span m="647753">execute.</span></p><p><span m="648220">Good</span> <span m="648538">branch</span>
  <span m="648857">prediction</span> <span m="649175">requires</span> <span m="649494">the</span>
  <span m="649812">use</span> <span m="650131">of</span> <span m="650450">the</span>
  <span m="650768">history</span> <span m="651087">from</span> <span m="651405">previous</span>
  <span m="651724">branches</span> <span m="652042">and</span> <span m="652361">there's</span>
  <span m="652680">been</span> <span m="652962">a</span> <span m="653244">lot</span>
  <span m="653526">of</span> <span m="653808">cleverness</span> <span m="654090">devoted</span>
  <span m="654372">to</span> <span m="654654">getting</span> <span m="654936">good</span>
  <span m="655218">predictions</span> <span m="655500">from</span> <span m="655782">the</span>
  <span m="656064">least</span> <span m="656346">amount</span> <span m="656628">of</span>
  <span m="656910">hardware!</span></p><p><span m="658589">If</span> <span m="659034">you're</span>
  <span m="659479">interested</span> <span m="659924">in</span> <span m="660369">the</span>
  <span m="660814">details,</span> <span m="661259">search</span> <span m="661704">for</span>
  <span m="662149">&quot;branch</span> <span m="662594">predictor&quot;</span> <span
  m="663039">on</span> <span m="663484">Wikipedia.</span></p><p><span m="663930">The</span>
  <span m="664306">register</span> <span m="664682">renaming</span> <span m="665058">happens</span>
  <span m="665434">during</span> <span m="665810">instruction</span> <span m="666186">decode,</span>
  <span m="666562">after</span> <span m="666938">which</span> <span m="667314">the</span>
  <span m="667690">instructions</span> <span m="668066">are</span> <span m="668442">ready</span>
  <span m="668819">to</span> <span m="669407">be</span> <span m="669996">dispatched</span>
  <span m="670585">to</span> <span m="671173">the</span> <span m="671762">functional</span>
  <span m="672351">units.</span></p><p><span m="672940">If</span> <span m="673246">an</span>
  <span m="673553">instruction</span> <span m="673860">needs</span> <span m="674166">the</span>
  <span m="674473">result</span> <span m="674780">of</span> <span m="675086">an</span>
  <span m="675393">earlier</span> <span m="675700">instruction</span> <span m="676006">as</span>
  <span m="676313">an</span> <span m="676620">operand,</span> <span m="676926">the</span>
  <span m="677233">dispatcher</span> <span m="677540">has</span> <span m="678015">identified</span>
  <span m="678490">which</span> <span m="678965">functional</span> <span m="679440">unit</span>
  <span m="679915">will</span> <span m="680390">be</span> <span m="680865">producing</span>
  <span m="681340">the</span> <span m="681815">result.</span></p><p><span m="682290">The</span>
  <span m="682617">instruction</span> <span m="682944">waits</span> <span m="683271">in</span>
  <span m="683598">a</span> <span m="683925">queue</span> <span m="684252">until</span>
  <span m="684580">the</span> <span m="684907">indicated</span> <span m="685234">functional</span>
  <span m="685561">unit</span> <span m="685888">produces</span> <span m="686215">the</span>
  <span m="686542">result</span> <span m="686870">and</span> <span m="687164">when</span>
  <span m="687459">all</span> <span m="687754">the</span> <span m="688048">operand</span>
  <span m="688343">values</span> <span m="688638">are</span> <span m="688932">known,</span>
  <span m="689227">the</span> <span m="689522">instruction</span> <span m="689816">is</span>
  <span m="690111">finally</span> <span m="690406">taken</span> <span m="690700">from</span>
  <span m="690995">the</span> <span m="691290">queue</span> <span m="692100">and</span>
  <span m="692910">executed.</span></p><p><span m="693720">Since</span> <span m="694015">the</span>
  <span m="694310">instructions</span> <span m="694605">are</span> <span m="694900">executed</span>
  <span m="695195">by</span> <span m="695490">different</span> <span m="695785">functional</span>
  <span m="696080">units</span> <span m="696375">as</span> <span m="696670">soon</span>
  <span m="696965">as</span> <span m="697260">their</span> <span m="697555">operands</span>
  <span m="697850">are</span> <span m="698254">available,</span> <span m="698658">the</span>
  <span m="699063">order</span> <span m="699467">of</span> <span m="699871">execution</span>
  <span m="700276">may</span> <span m="700680">not</span> <span m="701085">be</span>
  <span m="701489">the</span> <span m="701893">same</span> <span m="702298">as</span>
  <span m="702702">in</span> <span m="703106">the</span> <span m="703511">original</span>
  <span m="703915">program.</span></p><p><span m="704320">After</span> <span m="704724">execution,</span>
  <span m="705128">the</span> <span m="705532">functional</span> <span m="705936">units</span>
  <span m="706340">broadcast</span> <span m="706745">their</span> <span m="707149">results</span>
  <span m="707553">so</span> <span m="707957">that</span> <span m="708361">waiting</span>
  <span m="708765">instructions</span> <span m="709170">know</span> <span m="709712">when</span>
  <span m="710255">to</span> <span m="710797">proceed.</span></p><p><span m="711340">The</span>
  <span m="711589">results</span> <span m="711839">are</span> <span m="712089">also</span>
  <span m="712339">collected</span> <span m="712589">in</span> <span m="712839">a</span>
  <span m="713089">large</span> <span m="713339">reorder</span> <span m="713589">buffer</span>
  <span m="713839">so</span> <span m="714089">that</span> <span m="714339">that</span>
  <span m="714589">they</span> <span m="714839">can</span> <span m="715089">be</span>
  <span m="715339">retired</span> <span m="715589">(i.e.,</span> <span m="716035">write</span>
  <span m="716482">their</span> <span m="716929">results</span> <span m="717375">in</span>
  <span m="717822">the</span> <span m="718269">register</span> <span m="718715">file)</span>
  <span m="719162">in</span> <span m="719609">the</span> <span m="720055">correct</span>
  <span m="720502">order.</span></p><p><span m="720949">Whew!</span></p><p><span m="722199">There's</span>
  <span m="722524">a</span> <span m="722850">lot</span> <span m="723176">of</span>
  <span m="723502">circuitry</span> <span m="723827">involved</span> <span m="724153">in</span>
  <span m="724479">keeping</span> <span m="724805">the</span> <span m="725131">functional</span>
  <span m="725456">units</span> <span m="725782">fed</span> <span m="726108">with</span>
  <span m="726434">instructions,</span> <span m="726760">knowing</span> <span m="727126">when</span>
  <span m="727493">instructions</span> <span m="727860">have</span> <span m="728227">all</span>
  <span m="728594">their</span> <span m="728961">operands,</span> <span m="729327">and</span>
  <span m="729694">organizing</span> <span m="730061">the</span> <span m="730428">execution</span>
  <span m="730795">results</span> <span m="731162">into</span> <span m="731529">the</span>
  <span m="732109">correct</span> <span m="732689">order.</span></p><p><span m="733269">So</span>
  <span m="733698">how</span> <span m="734127">much</span> <span m="734556">speed</span>
  <span m="734986">up</span> <span m="735415">should</span> <span m="735844">we</span>
  <span m="736273">expect</span> <span m="736703">from</span> <span m="737132">all</span>
  <span m="737561">this</span> <span m="737990">machinery?</span></p><p><span m="738420">The</span>
  <span m="738809">effective</span> <span m="739198">CPI</span> <span m="739587">is</span>
  <span m="739977">very</span> <span m="740366">program-specific,</span> <span m="740755">depending</span>
  <span m="741144">as</span> <span m="741534">it</span> <span m="741923">does</span>
  <span m="742312">on</span> <span m="742701">cache</span> <span m="743091">hit</span>
  <span m="743480">rates,</span> <span m="743869">successful</span> <span m="744259">branch</span>
  <span m="744999">prediction,</span> <span m="745739">available</span> <span m="746479">ILP,</span>
  <span m="747219">and</span> <span m="747959">so</span> <span m="748699">on.</span></p><p><span
  m="749440">Given</span> <span m="749701">the</span> <span m="749962">architecture</span>
  <span m="750223">described</span> <span m="750485">here</span> <span m="750746">the</span>
  <span m="751007">best</span> <span m="751268">speed</span> <span m="751530">up</span>
  <span m="751791">we</span> <span m="752052">could</span> <span m="752313">hope</span>
  <span m="752575">for</span> <span m="752836">is</span> <span m="753097">a</span>
  <span m="753358">factor</span> <span m="753620">of</span> <span m="754160">4.</span></p><p><span
  m="754700">Googling</span> <span m="755086">around,</span> <span m="755472">it</span>
  <span m="755858">seems</span> <span m="756244">that</span> <span m="756630">the</span>
  <span m="757016">reality</span> <span m="757402">is</span> <span m="757788">an</span>
  <span m="758174">average</span> <span m="758560">speed-up</span> <span m="758946">of</span>
  <span m="759332">2,</span> <span m="759718">maybe</span> <span m="760104">slightly</span>
  <span m="760490">less,</span> <span m="760999">over</span> <span m="761508">what</span>
  <span m="762017">would</span> <span m="762526">be</span> <span m="763035">achieved</span>
  <span m="763544">by</span> <span m="764053">an</span> <span m="764562">in-order,</span>
  <span m="765071">single-issue</span> <span m="765580">processor.</span></p><p><span
  m="766089">What</span> <span m="766434">can</span> <span m="766779">we</span> <span
  m="767125">expect</span> <span m="767470">for</span> <span m="767816">future</span>
  <span m="768161">performance</span> <span m="768507">improvements</span> <span m="768852">in</span>
  <span m="769198">out-of-order,</span> <span m="769543">superscalar</span> <span
  m="769889">pipelines?</span></p><p><span m="772379">Increases</span> <span m="772819">in</span>
  <span m="773260">pipeline</span> <span m="773701">depth</span> <span m="774142">can</span>
  <span m="774583">cause</span> <span m="775024">CPI_stall</span> <span m="775465">and</span>
  <span m="775906">timing</span> <span m="776347">overheads</span> <span m="776788">to</span>
  <span m="777229">rise.</span></p><p><span m="777670">At</span> <span m="777990">the</span>
  <span m="778311">current</span> <span m="778632">pipeline</span> <span m="778952">depths</span>
  <span m="779273">the</span> <span m="779594">increase</span> <span m="779914">in</span>
  <span m="780235">CPI_stall</span> <span m="780556">is</span> <span m="780876">larger</span>
  <span m="781197">than</span> <span m="781518">the</span> <span m="781838">gains</span>
  <span m="782159">from</span> <span m="782480">decreased</span> <span m="782913">t_CLK</span>
  <span m="783346">and</span> <span m="783779">so</span> <span m="784212">further</span>
  <span m="784645">increases</span> <span m="785078">in</span> <span m="785511">depth</span>
  <span m="785944">are</span> <span m="786377">unlikely.</span></p><p><span m="786810">A</span>
  <span m="787319">similar</span> <span m="787828">tradeoff</span> <span m="788337">exists</span>
  <span m="788846">between</span> <span m="789356">using</span> <span m="789865">more</span>
  <span m="790374">out-of-order</span> <span m="790883">execution</span> <span m="791393">to</span>
  <span m="791902">increase</span> <span m="792411">ILP</span> <span m="792920">and</span>
  <span m="793430">the</span> <span m="793833">increase</span> <span m="794237">in</span>
  <span m="794640">CPI_stall</span> <span m="795044">caused</span> <span m="795447">by</span>
  <span m="795851">the</span> <span m="796255">impact</span> <span m="796658">of</span>
  <span m="797062">mis-predicted</span> <span m="797465">branches</span> <span m="797869">and</span>
  <span m="798272">the</span> <span m="798676">inability</span> <span m="799080">to</span>
  <span m="799710">run</span> <span m="800340">main</span> <span m="800970">memories</span>
  <span m="801600">any</span> <span m="802230">faster.</span></p><p><span m="802860">Power</span>
  <span m="803249">consumption</span> <span m="803638">increases</span> <span m="804027">more</span>
  <span m="804416">quickly</span> <span m="804806">than</span> <span m="805195">the</span>
  <span m="805584">performance</span> <span m="805973">gains</span> <span m="806363">from</span>
  <span m="806752">lower</span> <span m="807141">t_CLK</span> <span m="807530">and</span>
  <span m="807920">additional</span> <span m="808602">out-of-order</span> <span m="809284">execution</span>
  <span m="809966">logic.</span></p><p><span m="810649">The</span> <span m="811025">additional</span>
  <span m="811401">complexity</span> <span m="811778">required</span> <span m="812154">to</span>
  <span m="812531">enable</span> <span m="812907">further</span> <span m="813284">improvements</span>
  <span m="813660">in</span> <span m="814037">branch</span> <span m="814413">prediction</span>
  <span m="814790">and</span> <span m="815251">concurrent</span> <span m="815713">execution</span>
  <span m="816175">seems</span> <span m="816636">very</span> <span m="817098">daunting.</span></p><p><span
  m="817560">All</span> <span m="817967">of</span> <span m="818375">these</span> <span
  m="818783">factors</span> <span m="819191">suggest</span> <span m="819598">that</span>
  <span m="820006">is</span> <span m="820414">unlikely</span> <span m="820822">that</span>
  <span m="821230">we'll</span> <span m="821637">see</span> <span m="822045">substantial</span>
  <span m="822453">future</span> <span m="822861">improvements</span> <span m="823269">in</span>
  <span m="823984">the</span> <span m="824699">performance</span> <span m="825414">of</span>
  <span m="826129">out-of-order</span> <span m="826844">superscalar</span> <span m="827559">pipelined</span>
  <span m="828274">processors.</span></p><p><span m="828990">So</span> <span m="829366">system</span>
  <span m="829743">architects</span> <span m="830119">have</span> <span m="830496">turned</span>
  <span m="830872">their</span> <span m="831249">attention</span> <span m="831626">to</span>
  <span m="832002">exploiting</span> <span m="832379">data-level</span> <span m="832755">parallelism</span>
  <span m="833132">(DLP)</span> <span m="833509">and</span> <span m="834059">thread-level</span>
  <span m="834609">parallelism</span> <span m="835159">(TLP).</span></p><p><span m="835709">These</span>
  <span m="835942">are</span> <span m="836175">our</span> <span m="836409">next</span>
  <span m="836642">two</span> <span m="836875">topics.</span></p>
type: course
uid: 190530374c1ed20b2fdfd66de12642d0

---
None