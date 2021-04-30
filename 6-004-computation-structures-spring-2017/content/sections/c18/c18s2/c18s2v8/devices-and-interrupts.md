---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 0aMDzMhf528
  parent_uid: 25f7681e6b5b191b574cc8185d3dcab9
  title: Video-YouTube-Stream
  type: Video
  uid: dc6461dc7e5e19c2b07ae93bd56aa1bc
- id: 3Play-3Play YouTube id-Stream
  media_location: 0aMDzMhf528
  parent_uid: 25f7681e6b5b191b574cc8185d3dcab9
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: de97105956940aa9745a7545a2502e4c
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/0aMDzMhf528/default.jpg
  parent_uid: 25f7681e6b5b191b574cc8185d3dcab9
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: b5fab74fa85271ae1e53f22b7962d4fd
- id: 0aMDzMhf528.srt
  parent_uid: 25f7681e6b5b191b574cc8185d3dcab9
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v8/devices-and-interrupts/0aMDzMhf528.srt
  title: 3play caption file
  type: null
  uid: 3244c2fccea039b71d7524cbeb0007db
- id: 0aMDzMhf528.pdf
  parent_uid: 25f7681e6b5b191b574cc8185d3dcab9
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v8/devices-and-interrupts/0aMDzMhf528.pdf
  title: 3play pdf file
  type: null
  uid: a8361fb0250a5a4b7147224d9b30cf03
- id: Caption-3Play YouTube id-SRT
  parent_uid: 25f7681e6b5b191b574cc8185d3dcab9
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ae1345b72ca80075f17630ae40abe5f5
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 25f7681e6b5b191b574cc8185d3dcab9
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: a25d167284dff609c05f8f311fbf1da6
- id: Video-InternetArchive-MP4_1
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_18-02-08-01_300k.mp4
  parent_uid: 25f7681e6b5b191b574cc8185d3dcab9
  title: Video-Internet Archive-MP4
  type: Video
  uid: ea68781047977bba006d71943230afe3
inline_embed_id: 67403976devicesandinterrupts28774190
layout: video
order_index: null
parent_uid: 8b2dd9898274b230c05ba76f6bc6f4b6
related_resources_text: ''
short_url: devices-and-interrupts
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c18/c18s2/c18s2v8/devices-and-interrupts
template_type: Embed
title: 'Worked Example: Devices and Interrupts'
transcript: <p><span m="399">For</span> <span m="750">this</span> <span m="1102">problem,</span>
  <span m="1454">assume</span> <span m="1806">that</span> <span m="2158">we</span>
  <span m="2509">have</span> <span m="2861">a</span> <span m="3213">computer</span>
  <span m="3565">system</span> <span m="3917">that</span> <span m="4269">has</span>
  <span m="4620">three</span> <span m="4972">devices</span> <span m="5324">D1,</span>
  <span m="5676">D2,</span> <span m="6028">and</span> <span m="6380">D3.</span></p><p><span
  m="7740">Each</span> <span m="8062">of</span> <span m="8384">these</span> <span
  m="8706">devices</span> <span m="9028">can</span> <span m="9350">cause</span> <span
  m="9672">interrupts</span> <span m="9994">in</span> <span m="10316">our</span> <span
  m="10638">system.</span></p><p><span m="10960">This</span> <span m="11484">table</span>
  <span m="12009">summarizes</span> <span m="12534">the</span> <span m="13059">interrupt</span>
  <span m="13584">characteristics</span> <span m="14109">of</span> <span m="14634">our</span>
  <span m="15159">three</span> <span m="15684">devices.</span></p><p><span m="16209">For</span>
  <span m="16457">each</span> <span m="16706">device,</span> <span m="16955">we</span>
  <span m="17204">are</span> <span m="17453">given</span> <span m="17702">its</span>
  <span m="17951">service</span> <span m="18200">time</span> <span m="18448">which</span>
  <span m="18697">is</span> <span m="18946">the</span> <span m="19195">amount</span>
  <span m="19444">of</span> <span m="19693">time</span> <span m="19942">it</span>
  <span m="20191">takes</span> <span m="20440">to</span> <span m="20872">service</span>
  <span m="21305">an</span> <span m="21737">interrupt</span> <span m="22170">for</span>
  <span m="22602">that</span> <span m="23035">particular</span> <span m="23467">device.</span></p><p><span
  m="23900">We</span> <span m="24270">are</span> <span m="24640">given</span> <span
  m="25010">an</span> <span m="25380">interrupt</span> <span m="25750">frequency</span>
  <span m="26120">which</span> <span m="26490">tells</span> <span m="26860">us</span>
  <span m="27230">how</span> <span m="27600">frequently</span> <span m="27970">the</span>
  <span m="28340">interrupts</span> <span m="28710">for</span> <span m="29080">that</span>
  <span m="29713">device</span> <span m="30346">arrive.</span></p><p><span m="30980">You</span>
  <span m="31293">can</span> <span m="31606">assume</span> <span m="31920">that</span>
  <span m="32233">the</span> <span m="32546">first</span> <span m="32860">interrupt</span>
  <span m="33173">of</span> <span m="33486">each</span> <span m="33800">device</span>
  <span m="34113">can</span> <span m="34426">arrive</span> <span m="34740">at</span>
  <span m="35053">any</span> <span m="35366">time.</span></p><p><span m="35680">The</span>
  <span m="36044">deadline</span> <span m="36408">is</span> <span m="36772">the</span>
  <span m="37136">longest</span> <span m="37500">amount</span> <span m="37864">of</span>
  <span m="38228">time</span> <span m="38592">that</span> <span m="38956">is</span>
  <span m="39320">allowed</span> <span m="39684">between</span> <span m="40048">the</span>
  <span m="40412">interrupt</span> <span m="40776">request</span> <span m="41140">and</span>
  <span m="41504">the</span> <span m="41868">completion</span> <span m="42232">of</span>
  <span m="42597">the</span> <span m="42961">interrupt</span> <span m="43325">handler.</span></p><p><span
  m="43690">Assume</span> <span m="44176">we</span> <span m="44663">have</span> <span
  m="45150">a</span> <span m="45637">program</span> <span m="46124">P</span> <span
  m="46611">that</span> <span m="47098">takes</span> <span m="47585">100</span> <span
  m="48071">seconds</span> <span m="48558">to</span> <span m="49045">execute</span>
  <span m="49532">when</span> <span m="50019">interrupts</span> <span m="50506">are</span>
  <span m="50993">disabled.</span></p><p><span m="51480">We</span> <span m="51762">would</span>
  <span m="52044">like</span> <span m="52327">to</span> <span m="52609">figure</span>
  <span m="52891">out</span> <span m="53174">how</span> <span m="53456">long</span>
  <span m="53738">it</span> <span m="54021">would</span> <span m="54303">take</span>
  <span m="54585">to</span> <span m="54868">execute</span> <span m="55150">this</span>
  <span m="55432">program</span> <span m="55715">when</span> <span m="55997">interrupts</span>
  <span m="56280">are</span> <span m="57400">enabled.</span></p><p><span m="58520">To</span>
  <span m="58819">answer</span> <span m="59118">this</span> <span m="59418">question,</span>
  <span m="59717">we</span> <span m="60017">need</span> <span m="60316">to</span>
  <span m="60615">determine</span> <span m="60915">the</span> <span m="61214">amount</span>
  <span m="61514">of</span> <span m="61813">cpu</span> <span m="62112">time</span>
  <span m="62412">that</span> <span m="62711">is</span> <span m="63011">dedicated</span>
  <span m="63310">to</span> <span m="63610">the</span> <span m="63911">handling</span>
  <span m="64212">of</span> <span m="64513">each</span> <span m="64815">of</span>
  <span m="65116">the</span> <span m="65417">three</span> <span m="65718">devices.</span></p><p><span
  m="66020">D1</span> <span m="66609">has</span> <span m="67198">a</span> <span m="67788">service</span>
  <span m="68377">time</span> <span m="68967">of</span> <span m="69556">400us</span>
  <span m="70146">and</span> <span m="70735">it</span> <span m="71325">runs</span>
  <span m="71914">every</span> <span m="72504">800us</span> <span m="73093">so</span>
  <span m="73683">it</span> <span m="74272">is</span> <span m="74862">using</span>
  <span m="75451">400/800</span> <span m="76041">or</span> <span m="76630">50%</span>
  <span m="77220">of</span> <span m="77627">the</span> <span m="78035">cpu</span>
  <span m="78442">time.</span></p><p><span m="78850">D2</span> <span m="79565">has</span>
  <span m="80281">a</span> <span m="80997">service</span> <span m="81713">time</span>
  <span m="82428">of</span> <span m="83144">250us</span> <span m="83860">and</span>
  <span m="84576">it</span> <span m="85292">runs</span> <span m="86007">every</span>
  <span m="86723">1000us</span> <span m="87439">so</span> <span m="88155">it</span>
  <span m="88871">is</span> <span m="89586">using</span> <span m="90302">250/1000</span>
  <span m="91018">or</span> <span m="91734">25%</span> <span m="92450">of</span> <span
  m="93067">the</span> <span m="93685">cpu</span> <span m="94302">time.</span></p><p><span
  m="94920">D3</span> <span m="95730">uses</span> <span m="96540">100/800</span> <span
  m="97350">or</span> <span m="98160">12.5%</span> <span m="98970">of</span> <span
  m="99780">the</span> <span m="100590">cpu</span> <span m="101400">time.</span></p><p><span
  m="102210">This</span> <span m="102572">means</span> <span m="102934">that</span>
  <span m="103296">the</span> <span m="103658">user</span> <span m="104020">programs</span>
  <span m="104382">have</span> <span m="104745">the</span> <span m="105107">remaining</span>
  <span m="105469">cpu</span> <span m="105831">time</span> <span m="106193">available</span>
  <span m="106555">to</span> <span m="106917">them.</span></p><p><span m="107280">The</span>
  <span m="107872">remaining</span> <span m="108465">cpu</span> <span m="109057">time</span>
  <span m="109650">is</span> <span m="110242">12.5%</span> <span m="110835">or</span>
  <span m="111427">1/8</span> <span m="112020">of</span> <span m="112612">the</span>
  <span m="113205">cpu</span> <span m="113797">time.</span></p><p><span m="114390">If</span>
  <span m="114632">the</span> <span m="114874">user</span> <span m="115116">program</span>
  <span m="115358">can</span> <span m="115600">only</span> <span m="115842">run</span>
  <span m="116084">for</span> <span m="116326">one</span> <span m="116568">eighth</span>
  <span m="116811">of</span> <span m="117053">the</span> <span m="117295">time,</span>
  <span m="117537">that</span> <span m="117779">means</span> <span m="118021">that</span>
  <span m="118263">a</span> <span m="118505">program</span> <span m="118747">that</span>
  <span m="118990">takes</span> <span m="119528">100</span> <span m="120067">seconds</span>
  <span m="120605">without</span> <span m="121144">interrupts</span> <span m="121682">will</span>
  <span m="122221">take</span> <span m="122760">800</span> <span m="123298">seconds</span>
  <span m="123837">to</span> <span m="124375">run</span> <span m="124914">with</span>
  <span m="125452">interrupts</span> <span m="125991">enabled.</span></p><p><span
  m="126530">We</span> <span m="126828">want</span> <span m="127126">to</span> <span
  m="127424">consider</span> <span m="127722">whether</span> <span m="128020">there</span>
  <span m="128318">is</span> <span m="128616">a</span> <span m="128914">weak</span>
  <span m="129212">priority</span> <span m="129510">ordering</span> <span m="129808">that</span>
  <span m="130106">could</span> <span m="130404">satisfy</span> <span m="130702">all</span>
  <span m="131000">of</span> <span m="131299">the</span> <span m="131757">constraints</span>
  <span m="132215">for</span> <span m="132674">this</span> <span m="133132">system?</span>
  <span m="133590">Recall</span> <span m="134049">that</span> <span m="134507">with</span>
  <span m="134965">a</span> <span m="135424">weak</span> <span m="135882">priority</span>
  <span m="136340">ordering,</span> <span m="136799">there</span> <span m="137174">is</span>
  <span m="137550">no</span> <span m="137926">preemption,</span> <span m="138301">so</span>
  <span m="138677">if</span> <span m="139053">an</span> <span m="139428">interrupt</span>
  <span m="139804">handler</span> <span m="140180">has</span> <span m="140555">begun</span>
  <span m="140931">running</span> <span m="141307">it</span> <span m="141682">runs</span>
  <span m="142058">to</span> <span m="142434">completion</span> <span m="142810">even</span>
  <span m="143319">if</span> <span m="143828">another</span> <span m="144337">interrupt</span>
  <span m="144846">of</span> <span m="145355">higher</span> <span m="145864">priority</span>
  <span m="146373">arrives</span> <span m="146882">before</span> <span m="147391">its</span>
  <span m="147900">completion.</span></p><p><span m="148409">Upon</span> <span m="148808">completion,</span>
  <span m="149207">all</span> <span m="149606">interrupts</span> <span m="150005">that</span>
  <span m="150405">have</span> <span m="150804">arrived,</span> <span m="151203">regardless</span>
  <span m="151602">of</span> <span m="152002">their</span> <span m="152401">order</span>
  <span m="152800">of</span> <span m="153199">arrival,</span> <span m="153599">are</span>
  <span m="154301">processed</span> <span m="155003">in</span> <span m="155705">priority</span>
  <span m="156407">order.</span></p><p><span m="157109">If</span> <span m="157417">there</span>
  <span m="157725">is</span> <span m="158033">a</span> <span m="158341">weak</span>
  <span m="158649">priority</span> <span m="158957">ordering</span> <span m="159265">that</span>
  <span m="159573">satisfies</span> <span m="159881">our</span> <span m="160189">system,</span>
  <span m="160497">then</span> <span m="160805">we</span> <span m="161113">should</span>
  <span m="161421">determine</span> <span m="161730">the</span> <span m="162419">priority</span>
  <span m="163109">ordering.</span></p><p><span m="163799">If</span> <span m="164079">there</span>
  <span m="164359">is</span> <span m="164639">no</span> <span m="164919">such</span>
  <span m="165199">ordering,</span> <span m="165479">then</span> <span m="165759">we</span>
  <span m="166039">should</span> <span m="166319">identify</span> <span m="166599">the</span>
  <span m="166879">devices</span> <span m="167159">for</span> <span m="167439">which</span>
  <span m="167719">a</span> <span m="167999">weak</span> <span m="168279">priority</span>
  <span m="168560">ordering</span> <span m="169178">cannot</span> <span m="169796">guarantee</span>
  <span m="170415">meeting</span> <span m="171033">all</span> <span m="171652">the</span>
  <span m="172270">constraints.</span></p><p><span m="172889">Returning</span> <span
  m="173269">to</span> <span m="173649">our</span> <span m="174029">device</span>
  <span m="174409">characteristics</span> <span m="174789">table</span> <span m="175169">and</span>
  <span m="175549">comparing</span> <span m="175929">our</span> <span m="176309">deadlines</span>
  <span m="176689">to</span> <span m="177069">the</span> <span m="177449">device</span>
  <span m="177829">service</span> <span m="178174">times,</span> <span m="178519">we</span>
  <span m="178864">see</span> <span m="179209">that</span> <span m="179554">in</span>
  <span m="179899">a</span> <span m="180244">weak</span> <span m="180589">priority</span>
  <span m="180934">system</span> <span m="181279">if</span> <span m="181624">the</span>
  <span m="181969">D1</span> <span m="182314">handler</span> <span m="182659">which</span>
  <span m="183004">has</span> <span m="183349">a</span> <span m="183694">service</span>
  <span m="184040">time</span> <span m="184497">of</span> <span m="184955">400us</span>
  <span m="185413">happens</span> <span m="185870">to</span> <span m="186328">be</span>
  <span m="186786">running</span> <span m="187244">when</span> <span m="187701">a</span>
  <span m="188159">D2</span> <span m="188617">or</span> <span m="189074">D3</span>
  <span m="189532">interrupt</span> <span m="189990">arrives,</span> <span m="190448">then</span>
  <span m="190905">the</span> <span m="191363">D2</span> <span m="191821">or</span>
  <span m="192279">D3</span> <span m="192665">devices</span> <span m="193051">could</span>
  <span m="193437">miss</span> <span m="193824">their</span> <span m="194210">deadlines</span>
  <span m="194596">because</span> <span m="194982">the</span> <span m="195369">service</span>
  <span m="195755">time</span> <span m="196141">of</span> <span m="196527">D1</span>
  <span m="196914">plus</span> <span m="197300">their</span> <span m="197686">own</span>
  <span m="198072">service</span> <span m="198459">time</span> <span m="198999">is</span>
  <span m="199539">greater</span> <span m="200079">than</span> <span m="200619">their</span>
  <span m="201159">deadline.</span></p><p><span m="201700">In</span> <span m="202071">other</span>
  <span m="202443">words,</span> <span m="202814">if</span> <span m="203186">D2</span>
  <span m="203557">or</span> <span m="203929">D3</span> <span m="204301">have</span>
  <span m="204672">to</span> <span m="205044">wait</span> <span m="205415">up</span>
  <span m="205787">to</span> <span m="206158">400us</span> <span m="206530">before</span>
  <span m="206902">beginning</span> <span m="207273">to</span> <span m="207645">be</span>
  <span m="208016">serviced</span> <span m="208388">then</span> <span m="208760">their</span>
  <span m="209205">completion</span> <span m="209650">time</span> <span m="210095">won't</span>
  <span m="210541">be</span> <span m="210986">until</span> <span m="211431">650us</span>
  <span m="211876">for</span> <span m="212322">D2</span> <span m="212767">which</span>
  <span m="213212">is</span> <span m="213657">greater</span> <span m="214103">than</span>
  <span m="214548">its</span> <span m="214993">deadline</span> <span m="215439">of</span>
  <span m="216090">300us,</span> <span m="216742">and</span> <span m="217393">500us</span>
  <span m="218045">for</span> <span m="218696">D3</span> <span m="219348">which</span>
  <span m="219999">is</span> <span m="220651">greater</span> <span m="221302">than</span>
  <span m="221954">its</span> <span m="222605">deadline</span> <span m="223257">of</span>
  <span m="223908">400us.</span></p><p><span m="224560">Thus,</span> <span m="225011">there</span>
  <span m="225462">is</span> <span m="225913">no</span> <span m="226364">weak</span>
  <span m="226815">priority</span> <span m="227267">system</span> <span m="227718">ordering</span>
  <span m="228169">which</span> <span m="228620">is</span> <span m="229071">guaranteed</span>
  <span m="229523">to</span> <span m="229974">satisfy</span> <span m="230425">all</span>
  <span m="230876">of</span> <span m="231327">our</span> <span m="231779">system</span>
  <span m="232764">constraints.</span></p><p><span m="233749">Now,</span> <span m="234306">lets</span>
  <span m="234863">reconsider</span> <span m="235420">the</span> <span m="235978">same</span>
  <span m="236535">question</span> <span m="237092">assuming</span> <span m="237649">a</span>
  <span m="238207">strong</span> <span m="238764">priority</span> <span m="239321">ordering.</span></p><p><span
  m="239879">Recall</span> <span m="240200">that</span> <span m="240522">with</span>
  <span m="240844">a</span> <span m="241166">strong</span> <span m="241488">priority</span>
  <span m="241810">ordering,</span> <span m="242132">the</span> <span m="242454">handler</span>
  <span m="242775">for</span> <span m="243097">a</span> <span m="243419">device</span>
  <span m="243741">with</span> <span m="244063">a</span> <span m="244385">higher</span>
  <span m="244707">priority</span> <span m="245029">will</span> <span m="245442">pre-empt</span>
  <span m="245855">a</span> <span m="246268">running</span> <span m="246681">handler</span>
  <span m="247094">of</span> <span m="247507">a</span> <span m="247920">lower</span>
  <span m="248333">priority</span> <span m="248746">device.</span></p><p><span m="249159">In</span>
  <span m="249492">other</span> <span m="249826">words</span> <span m="250160">if</span>
  <span m="250493">the</span> <span m="250827">priority</span> <span m="251161">of</span>
  <span m="251494">A</span> <span m="251828">is</span> <span m="252162">greater</span>
  <span m="252495">than</span> <span m="252829">B</span> <span m="253163">and</span>
  <span m="253496">an</span> <span m="253830">A</span> <span m="254164">interrupt</span>
  <span m="254497">arrives</span> <span m="254831">midway</span> <span m="255165">through</span>
  <span m="255499">the</span> <span m="255885">handling</span> <span m="256272">of</span>
  <span m="256658">a</span> <span m="257045">B</span> <span m="257432">interrupt,</span>
  <span m="257818">then</span> <span m="258205">the</span> <span m="258591">B</span>
  <span m="258978">interrupt</span> <span m="259365">handler</span> <span m="259751">will</span>
  <span m="260138">get</span> <span m="260524">interrupted,</span> <span m="260911">the</span>
  <span m="261298">A</span> <span m="261755">handler</span> <span m="262212">will</span>
  <span m="262670">be</span> <span m="263127">run,</span> <span m="263584">and</span>
  <span m="264042">upon</span> <span m="264499">completion</span> <span m="264956">of</span>
  <span m="265414">the</span> <span m="265871">A</span> <span m="266328">handler,</span>
  <span m="266786">the</span> <span m="267243">B</span> <span m="267700">handler</span>
  <span m="268158">will</span> <span m="268615">be</span> <span m="269072">resumed.</span></p><p><span
  m="269530">If</span> <span m="269858">there</span> <span m="270186">is</span> <span
  m="270514">a</span> <span m="270842">strong</span> <span m="271170">priority</span>
  <span m="271498">ordering</span> <span m="271826">that</span> <span m="272154">satisfies</span>
  <span m="272482">our</span> <span m="272810">system,</span> <span m="273138">then</span>
  <span m="273466">we</span> <span m="273794">should</span> <span m="274122">specify</span>
  <span m="274450">what</span> <span m="274976">it</span> <span m="275503">is.</span></p><p><span
  m="276030">If</span> <span m="276314">there</span> <span m="276599">is</span> <span
  m="276884">no</span> <span m="277168">such</span> <span m="277453">ordering,</span>
  <span m="277738">then</span> <span m="278022">we</span> <span m="278307">should</span>
  <span m="278592">identify</span> <span m="278877">the</span> <span m="279161">devices</span>
  <span m="279446">for</span> <span m="279731">which</span> <span m="280015">even</span>
  <span m="280300">a</span> <span m="280585">strong</span> <span m="280870">priority</span>
  <span m="281507">ordering</span> <span m="282145">cannot</span> <span m="282782">guarantee</span>
  <span m="283420">meeting</span> <span m="284057">all</span> <span m="284695">the</span>
  <span m="285332">constraints.</span></p><p><span m="285970">Since</span> <span m="286314">we</span>
  <span m="286658">now</span> <span m="287002">allow</span> <span m="287347">preemption</span>
  <span m="287691">of</span> <span m="288035">lower</span> <span m="288380">priority</span>
  <span m="288724">device</span> <span m="289068">handlers</span> <span m="289413">in</span>
  <span m="289757">order</span> <span m="290101">to</span> <span m="290446">satisfy</span>
  <span m="290790">the</span> <span m="291134">requirements</span> <span m="291479">of</span>
  <span m="291837">a</span> <span m="292195">higher</span> <span m="292554">priority</span>
  <span m="292912">handler,</span> <span m="293270">we</span> <span m="293629">are</span>
  <span m="293987">no</span> <span m="294346">longer</span> <span m="294704">faced</span>
  <span m="295062">with</span> <span m="295421">the</span> <span m="295779">issue</span>
  <span m="296138">that</span> <span m="296496">devices</span> <span m="296854">D2</span>
  <span m="297213">and</span> <span m="297571">D3</span> <span m="297930">can't</span>
  <span m="298287">meet</span> <span m="298644">their</span> <span m="299001">deadlines</span>
  <span m="299359">if</span> <span m="299716">D1</span> <span m="300073">happens</span>
  <span m="300430">to</span> <span m="300788">be</span> <span m="301145">running</span>
  <span m="301502">first.</span></p><p><span m="301860">In</span> <span m="302224">addition,</span>
  <span m="302589">since</span> <span m="302954">at</span> <span m="303318">the</span>
  <span m="303683">beginning</span> <span m="304048">of</span> <span m="304412">our</span>
  <span m="304777">problem</span> <span m="305142">we</span> <span m="305506">determined</span>
  <span m="305871">that</span> <span m="306236">there</span> <span m="306600">is</span>
  <span m="306965">enough</span> <span m="307330">time</span> <span m="307741">to</span>
  <span m="308152">service</span> <span m="308564">all</span> <span m="308975">of</span>
  <span m="309387">our</span> <span m="309798">interrupts</span> <span m="310210">given</span>
  <span m="310621">their</span> <span m="311032">service</span> <span m="311444">times</span>
  <span m="311855">and</span> <span m="312267">interrupt</span> <span m="312678">frequencies,</span>
  <span m="313090">that</span> <span m="313395">means</span> <span m="313700">that</span>
  <span m="314005">there</span> <span m="314311">must</span> <span m="314616">exist</span>
  <span m="314921">a</span> <span m="315226">strong</span> <span m="315532">priority</span>
  <span m="315837">ordering</span> <span m="316142">that</span> <span m="316447">can</span>
  <span m="316753">satisfy</span> <span m="317058">all</span> <span m="317363">the</span>
  <span m="317669">constraints</span> <span m="318254">of</span> <span m="318839">our</span>
  <span m="319424">system.</span></p><p><span m="320009">You</span> <span m="320294">can</span>
  <span m="320580">use</span> <span m="320866">the</span> <span m="321152">scheme</span>
  <span m="321438">that</span> <span m="321724">a</span> <span m="322010">device</span>
  <span m="322296">with</span> <span m="322582">a</span> <span m="322868">shorter</span>
  <span m="323154">deadline</span> <span m="323440">should</span> <span m="323726">have</span>
  <span m="324012">a</span> <span m="324298">higher</span> <span m="324584">priority</span>
  <span m="324870">than</span> <span m="325356">one</span> <span m="325842">with</span>
  <span m="326329">a</span> <span m="326815">longer</span> <span m="327302">deadline</span>
  <span m="327788">to</span> <span m="328275">arrive</span> <span m="328761">at</span>
  <span m="329247">a</span> <span m="329734">valid</span> <span m="330220">strong</span>
  <span m="330707">priority</span> <span m="331193">ordering.</span></p><p><span m="331680">A</span>
  <span m="332200">valid</span> <span m="332720">strong</span> <span m="333240">priority</span>
  <span m="333760">ordering</span> <span m="334280">is</span> <span m="334800">D2</span>
  <span m="335320">has</span> <span m="335840">the</span> <span m="336360">highest</span>
  <span m="336880">priority,</span> <span m="337400">then</span> <span m="337920">D3</span>
  <span m="338440">and</span> <span m="338960">then</span> <span m="339480">D1.</span></p><p><span
  m="340000">Another</span> <span m="340624">way</span> <span m="341249">of</span>
  <span m="341873">expressing</span> <span m="342498">this</span> <span m="343122">is</span>
  <span m="343747">D2</span> <span m="344371">&gt;</span> <span m="344996">D3</span>
  <span m="345620">&gt;</span> <span m="346245">D1.</span></p><p><span m="346870">Note</span>
  <span m="347207">that</span> <span m="347545">for</span> <span m="347883">this</span>
  <span m="348221">example,</span> <span m="348559">this</span> <span m="348897">priority</span>
  <span m="349235">ordering</span> <span m="349573">is</span> <span m="349911">the</span>
  <span m="350249">only</span> <span m="350587">valid</span> <span m="350925">ordering</span>
  <span m="351263">that</span> <span m="351601">will</span> <span m="351939">satisfy</span>
  <span m="352412">all</span> <span m="352885">the</span> <span m="353359">constraints</span>
  <span m="353832">of</span> <span m="354306">our</span> <span m="354779">strong</span>
  <span m="355253">priority</span> <span m="355726">system.</span></p><p><span m="356200">To</span>
  <span m="356547">convince</span> <span m="356894">ourselves</span> <span m="357241">of</span>
  <span m="357588">this,</span> <span m="357935">let's</span> <span m="358282">take</span>
  <span m="358630">a</span> <span m="358977">closer</span> <span m="359324">look</span>
  <span m="359671">at</span> <span m="360018">other</span> <span m="360365">priority</span>
  <span m="360712">possibilities</span> <span m="361060">and</span> <span m="361366">determine</span>
  <span m="361672">what</span> <span m="361978">would</span> <span m="362284">happen</span>
  <span m="362590">in</span> <span m="362896">those</span> <span m="363202">situations.</span></p><p><span
  m="363509">If</span> <span m="363900">D1</span> <span m="364291">had</span> <span
  m="364682">a</span> <span m="365073">higher</span> <span m="365464">priority</span>
  <span m="365855">than</span> <span m="366246">either</span> <span m="366637">D2</span>
  <span m="367028">or</span> <span m="367420">D3,</span> <span m="367811">then</span>
  <span m="368202">the</span> <span m="368593">deadlines</span> <span m="368984">for</span>
  <span m="369375">D2</span> <span m="369766">and</span> <span m="370157">D3</span>
  <span m="370548">would</span> <span m="370940">not</span> <span m="371365">be</span>
  <span m="371790">guaranteed</span> <span m="372215">to</span> <span m="372640">be</span>
  <span m="373065">satisfied.</span></p><p><span m="373490">This</span> <span m="373963">means</span>
  <span m="374436">that</span> <span m="374910">D1</span> <span m="375383">must</span>
  <span m="375856">have</span> <span m="376330">the</span> <span m="376803">lowest</span>
  <span m="377276">priority.</span></p><p><span m="377750">Now</span> <span m="378152">between</span>
  <span m="378554">D2</span> <span m="378956">and</span> <span m="379358">D3,</span>
  <span m="379760">if</span> <span m="380162">D3</span> <span m="380564">had</span>
  <span m="380966">a</span> <span m="381368">higher</span> <span m="381770">priority</span>
  <span m="382172">than</span> <span m="382574">D2,</span> <span m="382976">then</span>
  <span m="383378">if</span> <span m="383780">D3</span> <span m="384182">was</span>
  <span m="384584">being</span> <span m="384986">serviced</span> <span m="385389">when</span>
  <span m="385864">a</span> <span m="386339">D2</span> <span m="386814">interrupt</span>
  <span m="387289">arrived,</span> <span m="387764">the</span> <span m="388239">D2</span>
  <span m="388714">interrupt</span> <span m="389189">may</span> <span m="389664">not</span>
  <span m="390139">complete</span> <span m="390614">until</span> <span m="391089">350us</span>
  <span m="391564">which</span> <span m="392039">is</span> <span m="392514">beyond</span>
  <span m="392990">its</span> <span m="393725">deadline.</span></p><p><span m="394460">So</span>
  <span m="394899">this</span> <span m="395338">shows</span> <span m="395778">us</span>
  <span m="396217">that</span> <span m="396656">D2</span> <span m="397096">must</span>
  <span m="397535">have</span> <span m="397975">the</span> <span m="398414">highest</span>
  <span m="398853">priority,</span> <span m="399293">then</span> <span m="399732">D3</span>
  <span m="400171">and</span> <span m="400611">finally</span> <span m="401050">D1.</span></p>
type: course
uid: 25f7681e6b5b191b574cc8185d3dcab9

---
None