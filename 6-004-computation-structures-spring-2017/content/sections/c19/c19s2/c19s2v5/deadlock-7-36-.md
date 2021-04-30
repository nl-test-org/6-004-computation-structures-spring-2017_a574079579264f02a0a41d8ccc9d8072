---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: Teo5DweypWU
  parent_uid: 279d6e147ca7e97fcf36ce69249babc4
  title: Video-YouTube-Stream
  type: Video
  uid: 96f4f9611de450884d43eadd03eb070e
- id: 3Play-3Play YouTube id-Stream
  media_location: Teo5DweypWU
  parent_uid: 279d6e147ca7e97fcf36ce69249babc4
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 7de23d34a7b46706d56bb83fc2e92b82
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/Teo5DweypWU/default.jpg
  parent_uid: 279d6e147ca7e97fcf36ce69249babc4
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 24422302e1eae9e010bc5bac734f94ec
- id: Teo5DweypWU.srt
  parent_uid: 279d6e147ca7e97fcf36ce69249babc4
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v5/deadlock-7-36-/Teo5DweypWU.srt
  title: 3play caption file
  type: null
  uid: ec5bd7c22a5af9233128123542cbb52c
- id: Teo5DweypWU.pdf
  parent_uid: 279d6e147ca7e97fcf36ce69249babc4
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v5/deadlock-7-36-/Teo5DweypWU.pdf
  title: 3play pdf file
  type: null
  uid: 496fd326c3b255aa9a9860a677d95c1a
- id: Caption-3Play YouTube id-SRT
  parent_uid: 279d6e147ca7e97fcf36ce69249babc4
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 902d904fde31591329537f17606e0897
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 279d6e147ca7e97fcf36ce69249babc4
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 307e638e616bfc3153146dfbf0986dfc
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_19-02-05_300k.mp4
  parent_uid: 279d6e147ca7e97fcf36ce69249babc4
  title: Video-Internet Archive-MP4
  type: Video
  uid: ef0143e0851eb2b818fbf03f488380fe
inline_embed_id: 17225243deadlock73643091080
layout: video
order_index: null
parent_uid: ee5269233ec949227f537e587ecdd8b7
related_resources_text: ''
short_url: deadlock-7-36-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c19/c19s2/c19s2v5/deadlock-7-36-
template_type: Embed
title: Deadlock
transcript: <p><span m="280">If</span> <span m="667">the</span> <span m="1055">necessary</span>
  <span m="1443">synchronization</span> <span m="1830">requires</span> <span m="2218">acquiring</span>
  <span m="2606">more</span> <span m="2993">than</span> <span m="3381">one</span>
  <span m="3769">lock,</span> <span m="4156">there</span> <span m="4544">are</span>
  <span m="4932">some</span> <span m="5320">special</span> <span m="5767">considerations</span>
  <span m="6215">that</span> <span m="6663">need</span> <span m="7110">to</span> <span
  m="7558">be</span> <span m="8006">taken</span> <span m="8453">into</span> <span
  m="8901">account.</span></p><p><span m="9349">For</span> <span m="9671">example,</span>
  <span m="9994">the</span> <span m="10317">code</span> <span m="10639">below</span>
  <span m="10962">implements</span> <span m="11285">the</span> <span m="11608">transfer</span>
  <span m="11930">of</span> <span m="12253">funds</span> <span m="12576">from</span>
  <span m="12899">one</span> <span m="13221">bank</span> <span m="13544">account</span>
  <span m="13867">to</span> <span m="14190">another.</span></p><p><span m="15610">The</span>
  <span m="15875">code</span> <span m="16141">assumes</span> <span m="16407">there</span>
  <span m="16673">is</span> <span m="16939">a</span> <span m="17205">separate</span>
  <span m="17471">semaphore</span> <span m="17737">lock</span> <span m="18002">for</span>
  <span m="18268">each</span> <span m="18534">account</span> <span m="18800">and</span>
  <span m="19066">since</span> <span m="19332">it</span> <span m="19598">needs</span>
  <span m="19864">to</span> <span m="20130">adjust</span> <span m="20581">the</span>
  <span m="21033">balance</span> <span m="21484">of</span> <span m="21936">two</span>
  <span m="22387">accounts,</span> <span m="22839">it</span> <span m="23290">acquires</span>
  <span m="23742">the</span> <span m="24193">lock</span> <span m="24645">for</span>
  <span m="25096">each</span> <span m="25548">account.</span></p><p><span m="26000">Consider</span>
  <span m="26416">what</span> <span m="26832">happens</span> <span m="27248">if</span>
  <span m="27664">two</span> <span m="28080">customers</span> <span m="28496">try</span>
  <span m="28913">simultaneous</span> <span m="29329">transfers</span> <span m="29745">between</span>
  <span m="30161">their</span> <span m="30577">two</span> <span m="30993">accounts.</span></p><p><span
  m="31410">The</span> <span m="31740">top</span> <span m="32070">customer</span>
  <span m="32400">will</span> <span m="32730">try</span> <span m="33060">to</span>
  <span m="33390">acquire</span> <span m="33720">the</span> <span m="34050">locks</span>
  <span m="34380">for</span> <span m="34710">accounts</span> <span m="35040">6005</span>
  <span m="35370">and</span> <span m="35700">6004.</span></p><p><span m="36030">The</span>
  <span m="36531">bottom</span> <span m="37032">customer</span> <span m="37534">tries</span>
  <span m="38035">to</span> <span m="38537">acquire</span> <span m="39038">the</span>
  <span m="39540">same</span> <span m="40041">locks,</span> <span m="40542">but</span>
  <span m="41044">in</span> <span m="41545">the</span> <span m="42047">opposite</span>
  <span m="42548">order.</span></p><p><span m="43050">Once</span> <span m="43430">a</span>
  <span m="43810">customer</span> <span m="44190">has</span> <span m="44570">acquired</span>
  <span m="44950">both</span> <span m="45330">locks,</span> <span m="45710">the</span>
  <span m="46090">transfer</span> <span m="46470">code</span> <span m="46850">will</span>
  <span m="47230">complete,</span> <span m="47610">releasing</span> <span m="47990">the</span>
  <span m="48370">locks.</span></p><p><span m="49370">But</span> <span m="49739">what</span>
  <span m="50109">happens</span> <span m="50479">if</span> <span m="50849">the</span>
  <span m="51219">top</span> <span m="51589">customer</span> <span m="51959">acquires</span>
  <span m="52329">his</span> <span m="52699">first</span> <span m="53069">lock</span>
  <span m="53439">(for</span> <span m="53809">account</span> <span m="54179">6005)</span>
  <span m="54549">and</span> <span m="54919">the</span> <span m="55289">bottom</span>
  <span m="55787">customer</span> <span m="56285">simultaneously</span> <span m="56783">acquires</span>
  <span m="57281">his</span> <span m="57779">first</span> <span m="58277">lock</span>
  <span m="58775">(for</span> <span m="59273">account</span> <span m="59771">6004).</span></p><p><span
  m="60269">So</span> <span m="60660">far,</span> <span m="61051">so</span> <span
  m="61442">good,</span> <span m="61833">but</span> <span m="62225">now</span> <span
  m="62616">each</span> <span m="63007">customer</span> <span m="63398">will</span>
  <span m="63790">be</span> <span m="64181">not</span> <span m="64572">be</span> <span
  m="64963">successful</span> <span m="65355">in</span> <span m="65746">acquiring</span>
  <span m="66137">their</span> <span m="66528">second</span> <span m="66920">lock,</span>
  <span m="67385">since</span> <span m="67850">those</span> <span m="68316">locks</span>
  <span m="68781">are</span> <span m="69246">already</span> <span m="69712">held</span>
  <span m="70177">by</span> <span m="70642">the</span> <span m="71108">other</span>
  <span m="71573">customer!</span></p><p><span m="72039">This</span> <span m="72403">situation</span>
  <span m="72767">is</span> <span m="73131">called</span> <span m="73495">a</span>
  <span m="73859">&quot;deadlock&quot;</span> <span m="74223">or</span> <span m="74587">&quot;deadly</span>
  <span m="74951">embrace&quot;</span> <span m="75315">because</span> <span m="75679">there</span>
  <span m="76043">is</span> <span m="76407">no</span> <span m="76771">way</span> <span
  m="77135">execution</span> <span m="77500">for</span> <span m="77990">either</span>
  <span m="78480">process</span> <span m="78970">will</span> <span m="79460">resume.</span></p><p><span
  m="79950">Both</span> <span m="80366">will</span> <span m="80782">wait</span> <span
  m="81198">indefinitely</span> <span m="81614">to</span> <span m="82030">acquire</span>
  <span m="82446">a</span> <span m="82863">lock</span> <span m="83279">that</span>
  <span m="83695">will</span> <span m="84111">never</span> <span m="84527">be</span>
  <span m="84943">available.</span></p><p><span m="85360">Obviously,</span> <span
  m="85920">synchronization</span> <span m="86480">involving</span> <span m="87040">multiple</span>
  <span m="87600">resources</span> <span m="88160">requires</span> <span m="88720">a</span>
  <span m="89280">bit</span> <span m="89840">more</span> <span m="90400">thought.</span></p><p><span
  m="90960">The</span> <span m="91385">problem</span> <span m="91811">of</span> <span
  m="92237">deadlock</span> <span m="92663">is</span> <span m="93089">elegantly</span>
  <span m="93515">illustrated</span> <span m="93940">by</span> <span m="94366">the</span>
  <span m="94792">Dining</span> <span m="95218">Philosophers</span> <span m="95644">problem.</span></p><p><span
  m="96070">Here</span> <span m="96491">there</span> <span m="96912">are,</span> <span
  m="97333">say,</span> <span m="97754">5</span> <span m="98175">philosophers</span>
  <span m="98596">waiting</span> <span m="99017">to</span> <span m="99438">eat.</span></p><p><span
  m="99859">Each</span> <span m="100217">requires</span> <span m="100575">two</span>
  <span m="100933">chopsticks</span> <span m="101291">in</span> <span m="101649">order</span>
  <span m="102008">to</span> <span m="102366">proceed,</span> <span m="102724">and</span>
  <span m="103082">there</span> <span m="103440">are</span> <span m="103799">5</span>
  <span m="104157">chopsticks</span> <span m="104515">on</span> <span m="104873">the</span>
  <span m="105231">table.</span></p><p><span m="105590">The</span> <span m="106158">philosophers</span>
  <span m="106726">follow</span> <span m="107295">a</span> <span m="107863">simple</span>
  <span m="108431">algorithm.</span></p><p><span m="109000">First</span> <span m="109316">they</span>
  <span m="109633">pick</span> <span m="109950">up</span> <span m="110266">the</span>
  <span m="110583">chopstick</span> <span m="110900">on</span> <span m="111216">their</span>
  <span m="111533">left,</span> <span m="111850">then</span> <span m="112166">the</span>
  <span m="112483">chopstick</span> <span m="112800">on</span> <span m="113116">their</span>
  <span m="113433">right.</span></p><p><span m="113750">When</span> <span m="114008">they</span>
  <span m="114267">have</span> <span m="114526">both</span> <span m="114785">chopsticks</span>
  <span m="115043">they</span> <span m="115302">eat</span> <span m="115561">until</span>
  <span m="115820">they're</span> <span m="116078">done,</span> <span m="116337">at</span>
  <span m="116596">which</span> <span m="116855">point</span> <span m="117113">they</span>
  <span m="117372">return</span> <span m="117631">both</span> <span m="117890">chopsticks</span>
  <span m="118161">to</span> <span m="118433">the</span> <span m="118705">table,</span>
  <span m="118977">perhaps</span> <span m="119249">enabling</span> <span m="119521">one</span>
  <span m="119793">of</span> <span m="120065">their</span> <span m="120337">neighbors</span>
  <span m="120609">to</span> <span m="120881">pick</span> <span m="121153">them</span>
  <span m="121425">up</span> <span m="121697">and</span> <span m="121969">begin</span>
  <span m="122589">eating.</span></p><p><span m="123210">Again,</span> <span m="123638">we</span>
  <span m="124066">see</span> <span m="124494">the</span> <span m="124922">basic</span>
  <span m="125350">setup</span> <span m="125779">of</span> <span m="126207">needing</span>
  <span m="126635">two</span> <span m="127063">(or</span> <span m="127491">more)</span>
  <span m="127919">resources</span> <span m="128348">before</span> <span m="128776">the</span>
  <span m="129204">task</span> <span m="129632">can</span> <span m="130060">complete.</span></p><p><span
  m="130489">Hopefully</span> <span m="130792">you</span> <span m="131095">can</span>
  <span m="131399">see</span> <span m="131702">the</span> <span m="132006">problem</span>
  <span m="132309">that</span> <span m="132613">may</span> <span m="132916">arise</span>
  <span m="133220">If</span> <span m="133524">all</span> <span m="133828">philosophers</span>
  <span m="134132">pick</span> <span m="134436">up</span> <span m="134740">the</span>
  <span m="135044">chopstick</span> <span m="135348">on</span> <span m="135652">their</span>
  <span m="135956">left,</span> <span m="136260">then</span> <span m="136564">all</span>
  <span m="136868">the</span> <span m="137172">chopsticks</span> <span m="137476">have</span>
  <span m="137780">been</span> <span m="138103">acquired,</span> <span m="138426">and</span>
  <span m="138749">none</span> <span m="139073">of</span> <span m="139396">the</span>
  <span m="139719">philosophers</span> <span m="140042">will</span> <span m="140366">be</span>
  <span m="140689">able</span> <span m="141012">to</span> <span m="141335">acquire</span>
  <span m="141659">their</span> <span m="141982">second</span> <span m="142305">chopstick</span>
  <span m="142629">and</span> <span m="143339">eat.</span></p><p><span m="144050">Another</span>
  <span m="144845">deadlock!</span></p><p><span m="145640">Here</span> <span m="146032">are</span>
  <span m="146424">the</span> <span m="146816">conditions</span> <span m="147208">required</span>
  <span m="147601">for</span> <span m="147993">a</span> <span m="148385">deadlock:</span>
  <span m="148777">1.</span></p><p><span m="149170">Mutual</span> <span m="149497">exclusion,</span>
  <span m="149825">where</span> <span m="150152">a</span> <span m="150480">particular</span>
  <span m="150807">resource</span> <span m="151135">can</span> <span m="151462">only</span>
  <span m="151790">be</span> <span m="152117">acquired</span> <span m="152445">by</span>
  <span m="152772">one</span> <span m="153100">process</span> <span m="153427">at</span>
  <span m="153755">a</span> <span m="154082">time.</span></p><p><span m="154410">2.</span></p><p><span
  m="155410">Hold-and-wait,</span> <span m="155823">where</span> <span m="156237">a</span>
  <span m="156651">process</span> <span m="157065">holds</span> <span m="157479">allocated</span>
  <span m="157893">resources</span> <span m="158306">while</span> <span m="158720">waiting</span>
  <span m="159134">to</span> <span m="159548">acquire</span> <span m="159962">the</span>
  <span m="160376">next</span> <span m="160790">resource.</span></p><p><span m="161860">3.</span></p><p><span
  m="162940">No</span> <span m="163337">preemption,</span> <span m="163734">where</span>
  <span m="164131">a</span> <span m="164528">resource</span> <span m="164925">cannot</span>
  <span m="165322">be</span> <span m="165720">removed</span> <span m="166117">from</span>
  <span m="166514">the</span> <span m="166911">process</span> <span m="167308">which</span>
  <span m="167705">acquired</span> <span m="168102">it.</span></p><p><span m="168500">Resources</span>
  <span m="168900">are</span> <span m="169301">only</span> <span m="169702">released</span>
  <span m="170103">after</span> <span m="170504">the</span> <span m="170904">process</span>
  <span m="171305">has</span> <span m="171706">completed</span> <span m="172107">its</span>
  <span m="172508">transaction.</span></p><p><span m="172909">4.</span></p><p><span
  m="174260">Circular</span> <span m="174647">wait,</span> <span m="175034">where</span>
  <span m="175421">resources</span> <span m="175809">needed</span> <span m="176196">by</span>
  <span m="176583">one</span> <span m="176970">process</span> <span m="177358">are</span>
  <span m="177745">held</span> <span m="178132">by</span> <span m="178519">another,</span>
  <span m="178907">and</span> <span m="179294">vice</span> <span m="179681">versa.</span></p><p><span
  m="180069">How</span> <span m="180453">can</span> <span m="180837">we</span> <span
  m="181221">solve</span> <span m="181606">the</span> <span m="181990">problem</span>
  <span m="182374">of</span> <span m="182758">deadlocks</span> <span m="183143">when</span>
  <span m="183527">acquiring</span> <span m="183911">multiple</span> <span m="184295">resources?</span></p><p><span
  m="184680">Either</span> <span m="184978">we</span> <span m="185277">avoid</span>
  <span m="185576">the</span> <span m="185875">problem</span> <span m="186173">to</span>
  <span m="186472">begin</span> <span m="186771">with,</span> <span m="187070">or</span>
  <span m="187368">we</span> <span m="187667">detect</span> <span m="187966">that</span>
  <span m="188265">deadlock</span> <span m="188563">has</span> <span m="188862">occurred</span>
  <span m="189161">and</span> <span m="189460">implement</span> <span m="190045">a</span>
  <span m="190630">recovery</span> <span m="191215">strategy.</span></p><p><span m="191800">Both</span>
  <span m="192221">techniques</span> <span m="192643">are</span> <span m="193065">used</span>
  <span m="193486">in</span> <span m="193908">practice.</span></p><p><span m="194330">In</span>
  <span m="194660">the</span> <span m="194991">Dining</span> <span m="195322">Philosophers</span>
  <span m="195652">problem,</span> <span m="195983">deadlock</span> <span m="196314">can</span>
  <span m="196645">be</span> <span m="196975">avoided</span> <span m="197306">with</span>
  <span m="197637">a</span> <span m="197967">small</span> <span m="198298">modification</span>
  <span m="198629">to</span> <span m="198960">the</span> <span m="199750">algorithm.</span></p><p><span
  m="200540">We</span> <span m="200862">start</span> <span m="201185">by</span> <span
  m="201507">assigning</span> <span m="201830">a</span> <span m="202152">unique</span>
  <span m="202475">number</span> <span m="202797">to</span> <span m="203120">each</span>
  <span m="203442">chopstick</span> <span m="203765">to</span> <span m="204087">establish</span>
  <span m="204410">a</span> <span m="204732">global</span> <span m="205055">ordering</span>
  <span m="205377">of</span> <span m="205700">all</span> <span m="206087">the</span>
  <span m="206475">resources,</span> <span m="206863">then</span> <span m="207251">rewrite</span>
  <span m="207639">the</span> <span m="208027">code</span> <span m="208415">to</span>
  <span m="208803">acquire</span> <span m="209191">resources</span> <span m="209579">using</span>
  <span m="209937">the</span> <span m="210296">global</span> <span m="210654">ordering</span>
  <span m="211013">to</span> <span m="211371">determine</span> <span m="211730">which</span>
  <span m="212089">resource</span> <span m="212447">to</span> <span m="212806">acquire</span>
  <span m="213164">first,</span> <span m="213523">which</span> <span m="213881">second,</span>
  <span m="214240">and</span> <span m="214599">so</span> <span m="215534">on.</span></p><p><span
  m="216470">With</span> <span m="216824">the</span> <span m="217178">chopsticks</span>
  <span m="217532">numbered,</span> <span m="217886">the</span> <span m="218240">philosophers</span>
  <span m="218595">pick</span> <span m="218949">up</span> <span m="219303">the</span>
  <span m="219657">lowest-numbered</span> <span m="220011">chopstick</span> <span
  m="220365">from</span> <span m="220720">either</span> <span m="221163">their</span>
  <span m="221607">left</span> <span m="222051">or</span> <span m="222495">right.</span></p><p><span
  m="222939">Then</span> <span m="223289">they</span> <span m="223639">pick</span>
  <span m="223989">up</span> <span m="224339">the</span> <span m="224689">other,</span>
  <span m="225039">higher-numbered</span> <span m="225389">chopstick,</span> <span
  m="225739">eat,</span> <span m="226089">and</span> <span m="226439">then</span>
  <span m="226789">return</span> <span m="227139">the</span> <span m="227489">chopsticks</span>
  <span m="227840">to</span> <span m="228403">the</span> <span m="228966">table.</span></p><p><span
  m="229530">How</span> <span m="230048">does</span> <span m="230566">this</span>
  <span m="231084">avoid</span> <span m="231602">deadlock?</span></p><p><span m="232120">Deadlock</span>
  <span m="232484">happens</span> <span m="232849">when</span> <span m="233214">all</span>
  <span m="233578">the</span> <span m="233943">chopsticks</span> <span m="234308">have</span>
  <span m="234672">been</span> <span m="235037">picked</span> <span m="235402">up</span>
  <span m="235766">but</span> <span m="236131">no</span> <span m="236496">philosopher</span>
  <span m="236860">can</span> <span m="237225">eat.</span></p><p><span m="237590">If</span>
  <span m="237860">all</span> <span m="238131">the</span> <span m="238402">chopsticks</span>
  <span m="238672">have</span> <span m="238943">been</span> <span m="239214">been</span>
  <span m="239484">picked</span> <span m="239755">up,</span> <span m="240026">that</span>
  <span m="240296">means</span> <span m="240567">some</span> <span m="240838">philosopher</span>
  <span m="241108">has</span> <span m="241379">picked</span> <span m="241650">up</span>
  <span m="242017">the</span> <span m="242385">highest-numbered</span> <span m="242753">chopstick</span>
  <span m="243120">and</span> <span m="243488">so</span> <span m="243856">must</span>
  <span m="244223">have</span> <span m="244591">earlier</span> <span m="244959">picked</span>
  <span m="245326">up</span> <span m="245694">the</span> <span m="246062">lower-numbered</span>
  <span m="246430">chopstick</span> <span m="246957">on</span> <span m="247485">his</span>
  <span m="248013">other</span> <span m="248541">side.</span></p><p><span m="249069">So</span>
  <span m="249477">that</span> <span m="249885">philosopher</span> <span m="250293">can</span>
  <span m="250701">eat</span> <span m="251109">then</span> <span m="251517">return</span>
  <span m="251925">both</span> <span m="252333">chopsticks</span> <span m="252741">to</span>
  <span m="253149">the</span> <span m="253557">table,</span> <span m="253965">breaking</span>
  <span m="254373">the</span> <span m="254781">hold-and-wait</span> <span m="255190">cycle.</span></p><p><span
  m="256940">So</span> <span m="257208">if</span> <span m="257476">all</span> <span
  m="257744">the</span> <span m="258012">processes</span> <span m="258281">in</span>
  <span m="258549">the</span> <span m="258817">system</span> <span m="259085">can</span>
  <span m="259354">agree</span> <span m="259622">upon</span> <span m="259890">a</span>
  <span m="260158">global</span> <span m="260427">ordering</span> <span m="260695">for</span>
  <span m="260963">the</span> <span m="261231">resources</span> <span m="261500">they</span>
  <span m="261843">require,</span> <span m="262186">then</span> <span m="262530">acquire</span>
  <span m="262873">them</span> <span m="263216">in</span> <span m="263560">order,</span>
  <span m="263903">there</span> <span m="264246">will</span> <span m="264590">be</span>
  <span m="264933">no</span> <span m="265276">possibility</span> <span m="265620">of</span>
  <span m="265963">a</span> <span m="266306">deadlock</span> <span m="266650">caused</span>
  <span m="267170">by</span> <span m="267690">a</span> <span m="268210">hold-and-wait</span>
  <span m="268730">cycle.</span></p><p><span m="269250">A</span> <span m="269562">global</span>
  <span m="269875">ordering</span> <span m="270188">is</span> <span m="270500">easy</span>
  <span m="270813">to</span> <span m="271126">arrange</span> <span m="271438">in</span>
  <span m="271751">our</span> <span m="272064">banking</span> <span m="272376">code</span>
  <span m="272689">for</span> <span m="273002">the</span> <span m="273314">transfer</span>
  <span m="273627">transaction.</span></p><p><span m="273940">We'll</span> <span m="274303">modify</span>
  <span m="274667">the</span> <span m="275030">code</span> <span m="275394">to</span>
  <span m="275758">first</span> <span m="276121">acquire</span> <span m="276485">the</span>
  <span m="276849">lock</span> <span m="277212">for</span> <span m="277576">the</span>
  <span m="277940">lower-numbered</span> <span m="278303">account,</span> <span m="278667">then</span>
  <span m="279031">acquire</span> <span m="279479">the</span> <span m="279927">lock</span>
  <span m="280375">for</span> <span m="280824">the</span> <span m="281272">higher-numbered</span>
  <span m="281720">account.</span></p><p><span m="282169">Now,</span> <span m="282604">both</span>
  <span m="283039">customers</span> <span m="283474">will</span> <span m="283909">first</span>
  <span m="284344">try</span> <span m="284779">to</span> <span m="285214">acquire</span>
  <span m="285649">the</span> <span m="286084">lock</span> <span m="286519">for</span>
  <span m="286954">the</span> <span m="287389">6004</span> <span m="287824">account.</span></p><p><span
  m="288260">The</span> <span m="288578">customer</span> <span m="288896">that</span>
  <span m="289214">succeeds</span> <span m="289532">then</span> <span m="289850">can</span>
  <span m="290168">acquire</span> <span m="290486">the</span> <span m="290804">lock</span>
  <span m="291122">for</span> <span m="291440">the</span> <span m="291758">6005</span>
  <span m="292076">account</span> <span m="292394">and</span> <span m="292712">complete</span>
  <span m="293030">the</span> <span m="294105">transaction.</span></p><p><span m="295180">The</span>
  <span m="295569">key</span> <span m="295959">to</span> <span m="296349">deadlock</span>
  <span m="296739">avoidance</span> <span m="297129">was</span> <span m="297519">that</span>
  <span m="297909">customers</span> <span m="298299">contented</span> <span m="298689">for</span>
  <span m="299079">the</span> <span m="299469">lock</span> <span m="299859">for</span>
  <span m="300249">the</span> <span m="300639">*first*</span> <span m="301029">resource</span>
  <span m="301419">they</span> <span m="302049">both</span> <span m="302679">needed.</span></p><p><span
  m="303310">Acquiring</span> <span m="303576">that</span> <span m="303843">lock</span>
  <span m="304110">ensured</span> <span m="304376">they</span> <span m="304643">would</span>
  <span m="304910">be</span> <span m="305176">able</span> <span m="305443">to</span>
  <span m="305710">acquire</span> <span m="305976">the</span> <span m="306243">remainder</span>
  <span m="306510">of</span> <span m="306776">the</span> <span m="307043">shared</span>
  <span m="307310">resources</span> <span m="307643">without</span> <span m="307976">fear</span>
  <span m="308309">that</span> <span m="308642">they</span> <span m="308975">would</span>
  <span m="309308">already</span> <span m="309641">be</span> <span m="309974">allocated</span>
  <span m="310307">to</span> <span m="310640">another</span> <span m="310973">process</span>
  <span m="311306">in</span> <span m="311639">a</span> <span m="311972">way</span>
  <span m="312305">that</span> <span m="312639">could</span> <span m="313261">cause</span>
  <span m="313883">a</span> <span m="314505">hold-and-wait</span> <span m="315127">cycle.</span></p><p><span
  m="315750">Establishing</span> <span m="316097">and</span> <span m="316444">using</span>
  <span m="316792">a</span> <span m="317139">global</span> <span m="317486">order</span>
  <span m="317834">for</span> <span m="318181">shared</span> <span m="318528">resources</span>
  <span m="318876">is</span> <span m="319223">possible</span> <span m="319570">when</span>
  <span m="319918">we</span> <span m="320265">can</span> <span m="320612">modify</span>
  <span m="320960">all</span> <span m="321507">processes</span> <span m="322055">to</span>
  <span m="322602">cooperate.</span></p><p><span m="323150">Avoiding</span> <span
  m="323644">deadlock</span> <span m="324138">without</span> <span m="324632">changing</span>
  <span m="325126">the</span> <span m="325620">processes</span> <span m="326114">is</span>
  <span m="326608">a</span> <span m="327102">harder</span> <span m="327596">problem.</span></p><p><span
  m="328090">For</span> <span m="328351">example,</span> <span m="328612">at</span>
  <span m="328873">the</span> <span m="329135">operating</span> <span m="329396">system</span>
  <span m="329657">level,</span> <span m="329919">it</span> <span m="330180">would</span>
  <span m="330441">be</span> <span m="330703">possible</span> <span m="330964">to</span>
  <span m="331225">modify</span> <span m="331487">the</span> <span m="331748">WAIT</span>
  <span m="332009">SVC</span> <span m="332271">to</span> <span m="332758">detect</span>
  <span m="333246">circular</span> <span m="333734">wait</span> <span m="334222">and</span>
  <span m="334709">terminate</span> <span m="335197">one</span> <span m="335685">of</span>
  <span m="336173">the</span> <span m="336661">WAITing</span> <span m="337148">processes,</span>
  <span m="337636">releasing</span> <span m="338124">its</span> <span m="338612">resources</span>
  <span m="339100">and</span> <span m="339904">breaking</span> <span m="340709">the</span>
  <span m="341514">deadlock.</span></p><p><span m="342319">The</span> <span m="342818">other</span>
  <span m="343317">strategy</span> <span m="343816">we</span> <span m="344315">mentioned</span>
  <span m="344814">was</span> <span m="345313">detection</span> <span m="345812">and</span>
  <span m="346311">recovery.</span></p><p><span m="346810">Database</span> <span m="347121">systems</span>
  <span m="347432">detect</span> <span m="347744">when</span> <span m="348055">there's</span>
  <span m="348366">been</span> <span m="348678">an</span> <span m="348989">external</span>
  <span m="349300">access</span> <span m="349612">to</span> <span m="349923">the</span>
  <span m="350234">shared</span> <span m="350546">data</span> <span m="350857">used</span>
  <span m="351169">by</span> <span m="351675">a</span> <span m="352182">particular</span>
  <span m="352689">transaction,</span> <span m="353196">which</span> <span m="353702">causes</span>
  <span m="354209">the</span> <span m="354716">database</span> <span m="355223">to</span>
  <span m="355729">abort</span> <span m="356236">the</span> <span m="356743">transaction.</span></p><p><span
  m="357250">When</span> <span m="357641">issuing</span> <span m="358033">a</span>
  <span m="358424">transaction</span> <span m="358816">to</span> <span m="359207">a</span>
  <span m="359599">database,</span> <span m="359990">the</span> <span m="360382">programmer</span>
  <span m="360773">specifies</span> <span m="361165">what</span> <span m="361556">should</span>
  <span m="361948">happen</span> <span m="362340">if</span> <span m="362849">the</span>
  <span m="363359">transaction</span> <span m="363869">is</span> <span m="364379">aborted,</span>
  <span m="364889">e.g.,</span> <span m="365399">she</span> <span m="365909">can</span>
  <span m="366419">specify</span> <span m="366929">that</span> <span m="367439">the</span>
  <span m="367949">transaction</span> <span m="368459">be</span> <span m="368969">retried.</span></p><p><span
  m="369479">The</span> <span m="369799">database</span> <span m="370119">remembers</span>
  <span m="370439">all</span> <span m="370759">the</span> <span m="371079">changes</span>
  <span m="371399">to</span> <span m="371719">shared</span> <span m="372039">data</span>
  <span m="372359">that</span> <span m="372679">happen</span> <span m="372999">during</span>
  <span m="373319">a</span> <span m="373639">transaction</span> <span m="373960">and</span>
  <span m="374255">only</span> <span m="374551">changes</span> <span m="374847">the</span>
  <span m="375143">master</span> <span m="375439">copy</span> <span m="375735">of</span>
  <span m="376031">the</span> <span m="376327">shared</span> <span m="376622">data</span>
  <span m="376918">when</span> <span m="377214">it</span> <span m="377510">is</span>
  <span m="377806">sure</span> <span m="378102">that</span> <span m="378398">the</span>
  <span m="378694">transaction</span> <span m="378990">will</span> <span m="379322">not</span>
  <span m="379654">be</span> <span m="379987">aborted,</span> <span m="380319">at</span>
  <span m="380652">which</span> <span m="380984">point</span> <span m="381316">the</span>
  <span m="381649">changes</span> <span m="381981">are</span> <span m="382314">committed</span>
  <span m="382646">to</span> <span m="382979">the</span> <span m="383984">database.</span></p><p><span
  m="384990">In</span> <span m="385337">summary,</span> <span m="385684">we</span>
  <span m="386032">saw</span> <span m="386379">that</span> <span m="386726">organizing</span>
  <span m="387074">an</span> <span m="387421">application</span> <span m="387768">as</span>
  <span m="388116">communicating</span> <span m="388463">processes</span> <span m="388810">is</span>
  <span m="389158">often</span> <span m="389505">a</span> <span m="389852">convenient</span>
  <span m="390200">way</span> <span m="390723">to</span> <span m="391246">go.</span></p><p><span
  m="391770">We</span> <span m="392195">used</span> <span m="392620">semaphores</span>
  <span m="393046">to</span> <span m="393471">synchronize</span> <span m="393896">the</span>
  <span m="394322">execution</span> <span m="394747">of</span> <span m="395173">the</span>
  <span m="395598">different</span> <span m="396023">processes,</span> <span m="396449">providing</span>
  <span m="396874">guarantees</span> <span m="397300">that</span> <span m="397743">certain</span>
  <span m="398186">precedence</span> <span m="398630">constraints</span> <span m="399073">would</span>
  <span m="399516">be</span> <span m="399960">met,</span> <span m="400403">even</span>
  <span m="400846">between</span> <span m="401290">statements</span> <span m="401733">in</span>
  <span m="402176">different</span> <span m="402620">processes.</span></p><p><span
  m="403620">We</span> <span m="404018">also</span> <span m="404416">introduced</span>
  <span m="404815">the</span> <span m="405213">notion</span> <span m="405612">of</span>
  <span m="406010">critical</span> <span m="406409">code</span> <span m="406807">sections</span>
  <span m="407206">and</span> <span m="407604">mutual</span> <span m="408003">exclusion</span>
  <span m="408401">constraints</span> <span m="408800">that</span> <span m="409151">guaranteed</span>
  <span m="409503">that</span> <span m="409854">a</span> <span m="410206">code</span>
  <span m="410557">sequence</span> <span m="410909">would</span> <span m="411260">be</span>
  <span m="411612">executed</span> <span m="411963">without</span> <span m="412315">interruption</span>
  <span m="412666">by</span> <span m="413018">another</span> <span m="413370">process.</span></p><p><span
  m="415110">We</span> <span m="415570">saw</span> <span m="416030">that</span> <span
  m="416490">semaphores</span> <span m="416950">could</span> <span m="417410">also</span>
  <span m="417870">be</span> <span m="418330">used</span> <span m="418790">to</span>
  <span m="419250">implement</span> <span m="419710">those</span> <span m="420170">mutual</span>
  <span m="420630">exclusion</span> <span m="421090">constraints.</span></p><p><span
  m="421550">Finally</span> <span m="421882">we</span> <span m="422215">discussed</span>
  <span m="422548">the</span> <span m="422881">problem</span> <span m="423214">of</span>
  <span m="423547">deadlock</span> <span m="423880">that</span> <span m="424212">can</span>
  <span m="424545">occur</span> <span m="424878">when</span> <span m="425211">multiple</span>
  <span m="425544">processes</span> <span m="425877">must</span> <span m="426210">acquire</span>
  <span m="426663">multiple</span> <span m="427117">shared</span> <span m="427570">resources,</span>
  <span m="428024">and</span> <span m="428477">we</span> <span m="428931">proposed</span>
  <span m="429384">several</span> <span m="429838">solutions</span> <span m="430291">based</span>
  <span m="430745">on</span> <span m="431199">a</span> <span m="431704">global</span>
  <span m="432209">ordering</span> <span m="432714">of</span> <span m="433219">resources</span>
  <span m="433724">or</span> <span m="434229">the</span> <span m="434734">ability</span>
  <span m="435239">to</span> <span m="435744">restart</span> <span m="436249">a</span>
  <span m="436754">transaction.</span></p><p><span m="437260">Synchronization</span>
  <span m="437524">primitives</span> <span m="437788">play</span> <span m="438052">a</span>
  <span m="438316">key</span> <span m="438580">role</span> <span m="438844">in</span>
  <span m="439108">the</span> <span m="439372">world</span> <span m="439636">of</span>
  <span m="439900">&quot;big</span> <span m="440164">data&quot;</span> <span m="440428">where</span>
  <span m="440692">there</span> <span m="440956">are</span> <span m="441220">vast</span>
  <span m="441559">amounts</span> <span m="441899">of</span> <span m="442239">shared</span>
  <span m="442579">data,</span> <span m="442919">or</span> <span m="443259">when</span>
  <span m="443599">trying</span> <span m="443939">to</span> <span m="444279">coordinate</span>
  <span m="444619">the</span> <span m="444959">execution</span> <span m="445299">of</span>
  <span m="445639">thousands</span> <span m="445979">of</span> <span m="446319">processes</span>
  <span m="447011">in</span> <span m="447704">the</span> <span m="448397">cloud.</span></p><p><span
  m="449090">Understanding</span> <span m="449486">synchronization</span> <span m="449883">issues</span>
  <span m="450280">and</span> <span m="450677">their</span> <span m="451074">solutions</span>
  <span m="451471">is</span> <span m="451868">a</span> <span m="452265">key</span>
  <span m="452662">skill</span> <span m="453059">when</span> <span m="453456">writing</span>
  <span m="453853">most</span> <span m="454250">modern</span> <span m="454894">applications.</span></p>
type: course
uid: 279d6e147ca7e97fcf36ce69249babc4

---
None