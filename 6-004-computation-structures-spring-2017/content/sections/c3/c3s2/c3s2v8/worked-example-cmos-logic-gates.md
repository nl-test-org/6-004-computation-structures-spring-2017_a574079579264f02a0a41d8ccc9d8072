---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 7XEUB_dTaK0
  parent_uid: 1f9435c34f1788836ed9a04f744635d8
  title: Video-YouTube-Stream
  type: Video
  uid: 660af71933e2f43e4cdebe0bfb93f654
- id: 3Play-3Play YouTube id-Stream
  media_location: 7XEUB_dTaK0
  parent_uid: 1f9435c34f1788836ed9a04f744635d8
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 15bf907ac0a08dc1ef9d1a494b5f58a2
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/7XEUB_dTaK0/default.jpg
  parent_uid: 1f9435c34f1788836ed9a04f744635d8
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: b4f650c7867c10c00a623f6e18bd25fa
- id: 7XEUB_dTaK0.srt
  parent_uid: 1f9435c34f1788836ed9a04f744635d8
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c3/c3s2/c3s2v8/worked-example-cmos-logic-gates/7XEUB_dTaK0.srt
  title: 3play caption file
  type: null
  uid: 05c46aef2d1378757d3f05a8719eb455
- id: 7XEUB_dTaK0.pdf
  parent_uid: 1f9435c34f1788836ed9a04f744635d8
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c3/c3s2/c3s2v8/worked-example-cmos-logic-gates/7XEUB_dTaK0.pdf
  title: 3play pdf file
  type: null
  uid: df031f116731424872c12ac4c620f483
- id: Caption-3Play YouTube id-SRT
  parent_uid: 1f9435c34f1788836ed9a04f744635d8
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: a616d8f972c55155818431be3dc77f28
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 1f9435c34f1788836ed9a04f744635d8
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 4340cfa7443e605a915fa35fe4283cf2
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_03-02-08-02_300k.mp4
  parent_uid: 1f9435c34f1788836ed9a04f744635d8
  title: Video-Internet Archive-MP4
  type: Video
  uid: 6d3b2d231b962f0842389345b42617c1
inline_embed_id: 34221688cmoslogicgates65403410
layout: video
order_index: null
parent_uid: 9aae4da9822ad2a1b0659144ed9415d3
related_resources_text: ''
short_url: worked-example-cmos-logic-gates
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c3/c3s2/c3s2v8/worked-example-cmos-logic-gates
template_type: Embed
title: 'Worked Example: CMOS Logic Gates'
transcript: <p><span m="410">In</span> <span m="960">this</span> <span m="1250">problem,</span>
  <span m="1790">we</span> <span m="1950">are</span> <span m="2050">given</span> <span
  m="2410">a</span> <span m="2440">function</span> <span m="3020">Z</span> <span m="3710">equal</span>
  <span m="4270">to</span> <span m="4580">((A</span> <span m="4870">OR</span> <span
  m="5130">B)</span> <span m="5790">AND</span> <span m="6320">C),</span> <span m="6950">the</span>
  <span m="7270">whole</span> <span m="7460">thing</span> <span m="7840">negated.</span></p><p><span
  m="9110">We</span> <span m="9230">are</span> <span m="9320">then</span> <span m="9570">asked</span>
  <span m="9900">to</span> <span m="9970">produce</span> <span m="10650">a</span>
  <span m="10770">CMOS</span> <span m="11400">circuit</span> <span m="11840">that</span>
  <span m="12060">implements</span> <span m="12620">the</span> <span m="12700">function</span>
  <span m="13260">Z.</span></p><p><span m="14440">We</span> <span m="14560">know</span>
  <span m="14790">that</span> <span m="14940">our</span> <span m="15040">CMOS</span>
  <span m="15550">circuits</span> <span m="16180">consists</span> <span m="16740">of</span>
  <span m="16930">a</span> <span m="17020">pull-down</span> <span m="17640">circuit</span>
  <span m="18150">made</span> <span m="18400">up</span> <span m="18580">purely</span>
  <span m="19110">of</span> <span m="19290">NFETs,</span> <span m="20080">and</span>
  <span m="20370">it</span> <span m="20530">is</span> <span m="20710">called</span>
  <span m="21100">pull-down</span> <span m="21770">because</span> <span m="22200">if</span>
  <span m="22430">it</span> <span m="22540">is</span> <span m="22690">on,</span> <span
  m="23290">it</span> <span m="23570">connects</span> <span m="24040">the</span> <span
  m="24200">output</span> <span m="24550">to</span> <span m="24680">ground</span>
  <span m="25210">to</span> <span m="25380">produce</span> <span m="25840">a</span>
  <span m="25960">low</span> <span m="26490">(or</span> <span m="26800">0)</span>
  <span m="27090">output.</span></p><p><span m="28530">We</span> <span m="28660">also</span>
  <span m="29080">have</span> <span m="29270">a</span> <span m="29320">pull-up</span>
  <span m="29750">circuit</span> <span m="30590">made</span> <span m="30950">up</span>
  <span m="31180">purely</span> <span m="31750">of</span> <span m="32030">PFETs,</span>
  <span m="32830">and</span> <span m="33120">it</span> <span m="33280">is</span> <span
  m="33430">called</span> <span m="33700">a</span> <span m="33740">pull-up</span>
  <span m="34400">because</span> <span m="35030">if</span> <span m="35200">it</span>
  <span m="35380">is</span> <span m="35550">on,</span> <span m="36040">it</span> <span
  m="36320">connects</span> <span m="36770">the</span> <span m="36950">output</span>
  <span m="37300">to</span> <span m="37420">Vdd</span> <span m="38340">to</span> <span
  m="38620">produce</span> <span m="39080">a</span> <span m="39170">high</span> <span
  m="40060">(or</span> <span m="40650">1)</span> <span m="40770">output.</span></p><p><span
  m="41810">If</span> <span m="42030">Z</span> <span m="42480">=</span> <span m="42550">NOT((A</span>
  <span m="43570">OR</span> <span m="44410">B)</span> <span m="44760">AND</span> <span
  m="44890">C),</span> <span m="45630">then</span> <span m="46170">NOT(Z)</span> <span
  m="46640">=</span> <span m="47280">((A</span> <span m="48080">OR</span> <span m="48240">B)</span>
  <span m="48660">AND</span> <span m="48950">C).</span></p><p><span m="50080">To</span>
  <span m="50210">draw</span> <span m="50530">the</span> <span m="50620">pull-down</span>
  <span m="51170">portion</span> <span m="51620">of</span> <span m="51720">this</span>
  <span m="52010">circuit,</span> <span m="52660">we</span> <span m="52990">take</span>
  <span m="53290">a</span> <span m="53320">look</span> <span m="53630">at</span> <span
  m="53760">when</span> <span m="53950">the</span> <span m="54010">function</span>
  <span m="54530">produces</span> <span m="55580">Z</span> <span m="56190">=</span>
  <span m="56240">0.</span></p><p><span m="57100">This</span> <span m="57310">occurs</span>
  <span m="57810">when</span> <span m="58050">((A</span> <span m="58290">or</span>
  <span m="58450">B)</span> <span m="59000">and</span> <span m="59350">C)</span> <span
  m="59930">equals</span> <span m="60520">1,</span> <span m="60990">so</span> <span
  m="61520">the</span> <span m="61620">pull-down</span> <span m="62250">circuitry</span>
  <span m="63280">should</span> <span m="63750">be</span> <span m="64010">on</span>
  <span m="64470">when</span> <span m="64769">((A</span> <span m="64989">or</span>
  <span m="65120">B)</span> <span m="65470">and</span> <span m="65680">C)</span> <span
  m="66050">equals</span> <span m="66560">1.</span></p><p><span m="67930">So</span>
  <span m="68280">(A</span> <span m="68510">OR</span> <span m="68640">B)</span> <span
  m="69370">=</span> <span m="69640">1</span> <span m="69810">and</span> <span m="70440">C</span>
  <span m="71280">=</span> <span m="73810">1.</span></p><p><span m="74030">This</span>
  <span m="74250">means</span> <span m="74540">that</span> <span m="74710">we</span>
  <span m="74830">want</span> <span m="75310">a</span> <span m="75450">parallel(A,B)</span>
  <span m="76430">in</span> <span m="77250">series</span> <span m="78440">with</span>
  <span m="78810">C</span> <span m="79120">circuit</span> <span m="79760">for</span>
  <span m="80030">our</span> <span m="80150">pull-down.</span></p><p><span m="81870">The</span>
  <span m="81950">parallel(A,B)</span> <span m="83120">corresponds</span> <span m="84100">to</span>
  <span m="84280">(A</span> <span m="84530">OR</span> <span m="84680">B)</span> <span
  m="85520">=</span> <span m="86130">1</span> <span m="86310">because</span> <span
  m="86690">if</span> <span m="86840">either</span> <span m="87200">A</span> <span
  m="87560">or</span> <span m="87830">B</span> <span m="88180">equals</span> <span
  m="88720">1</span> <span m="89110">then</span> <span m="89580">we</span> <span m="89700">have</span>
  <span m="89880">a</span> <span m="89930">path</span> <span m="90340">from</span>
  <span m="90550">Z</span> <span m="90930">to</span> <span m="91090">the</span> <span
  m="91180">bottom</span> <span m="91620">of</span> <span m="91710">the</span> <span
  m="91790">parallel</span> <span m="92310">circuitry.</span></p><p><span m="93880">Then</span>
  <span m="94340">if</span> <span m="94480">C</span> <span m="94810">is</span> <span
  m="95000">also</span> <span m="95590">1,</span> <span m="95850">we</span> <span
  m="96120">complete</span> <span m="96560">our</span> <span m="96700">path</span>
  <span m="97130">between</span> <span m="97550">Z</span> <span m="97880">and</span>
  <span m="98000">ground.</span></p><p><span m="99010">So,</span> <span m="99500">if</span>
  <span m="99770">either</span> <span m="100140">(A</span> <span m="100620">=</span>
  <span m="100890">1</span> <span m="100920">and</span> <span m="101070">C</span>
  <span m="101620">=</span> <span m="101890">1)</span> <span m="102220">or</span>
  <span m="103090">(B</span> <span m="103570">=</span> <span m="103670">1</span> <span
  m="103770">and</span> <span m="104170">C</span> <span m="104880">=</span> <span
  m="105470">1),</span> <span m="105660">Z</span> <span m="105890">is</span> <span
  m="106040">pulled</span> <span m="106330">down</span> <span m="106600">to</span>
  <span m="106730">ground</span> <span m="107210">and</span> <span m="107370">produces</span>
  <span m="107940">a</span> <span m="108010">0</span> <span m="108270">output.</span></p><p><span
  m="110320">To</span> <span m="110430">generate</span> <span m="110990">our</span>
  <span m="111120">pull-up,</span> <span m="111940">we</span> <span m="112280">simply</span>
  <span m="112760">replace</span> <span m="113320">parallel</span> <span m="113850">circuits</span>
  <span m="114360">with</span> <span m="114530">series,</span> <span m="115300">and</span>
  <span m="115610">series</span> <span m="116200">with</span> <span m="116370">parallel.</span></p><p><span
  m="117540">This</span> <span m="117740">will</span> <span m="117930">ensure</span>
  <span m="118380">that</span> <span m="118540">whenever</span> <span m="118970">our</span>
  <span m="119140">pull-down</span> <span m="119700">circuit</span> <span m="120140">is</span>
  <span m="120330">off,</span> <span m="120860">our</span> <span m="121140">pull-up</span>
  <span m="121630">circuit</span> <span m="122050">is</span> <span m="122250">on.</span></p><p><span
  m="123210">So</span> <span m="123400">our</span> <span m="123510">pull-up</span>
  <span m="123980">circuitry</span> <span m="124970">is</span> <span m="125180">series(A,B)</span>
  <span m="126880">in</span> <span m="127420">parallel</span> <span m="128240">with</span>
  <span m="128430">C.</span></p><p><span m="129870">To</span> <span m="129979">convince</span>
  <span m="130530">ourselves</span> <span m="131220">that</span> <span m="131440">this</span>
  <span m="131630">is</span> <span m="131780">in</span> <span m="131880">fact</span>
  <span m="132230">the</span> <span m="132310">correct</span> <span m="132790">pull-up</span>
  <span m="133210">circuit,</span> <span m="134000">we</span> <span m="134400">know</span>
  <span m="134640">that</span> <span m="134790">the</span> <span m="134890">pull-up</span>
  <span m="135410">must</span> <span m="135750">make</span> <span m="136040">Z</span>
  <span m="136380">equal</span> <span m="136690">to</span> <span m="137430">1.</span></p><p><span
  m="138080">Z</span> <span m="138690">=</span> <span m="139070">1</span> <span m="139380">if</span>
  <span m="139940">((A</span> <span m="140190">OR</span> <span m="140380">B)</span>
  <span m="140910">AND</span> <span m="141280">C)</span> <span m="141800">the</span>
  <span m="141960">whole</span> <span m="142270">thing</span> <span m="142520">negated</span>
  <span m="143320">equals</span> <span m="143930">1,</span> <span m="144490">or</span>
  <span m="145640">((A</span> <span m="146110">OR</span> <span m="146290">B)</span>
  <span m="146830">AND</span> <span m="147180">C)</span> <span m="148170">=</span>
  <span m="148840">0.</span></p><p><span m="149530">This</span> <span m="149720">is</span>
  <span m="149910">true</span> <span m="150260">when</span> <span m="150530">either</span>
  <span m="151060">(A</span> <span m="151330">OR</span> <span m="151450">B)</span>
  <span m="152060">=</span> <span m="152330">0</span> <span m="152780">or</span> <span
  m="153300">C</span> <span m="153970">=</span> <span m="154190">0.</span></p><p><span
  m="155150">This</span> <span m="155390">means</span> <span m="155800">that</span>
  <span m="156060">either</span> <span m="156650">A</span> <span m="157120">=</span>
  <span m="157210">0</span> <span m="157340">and</span> <span m="158070">B</span>
  <span m="158520">=</span> <span m="158870">0</span> <span m="159370">OR</span> <span
  m="160360">just</span> <span m="160940">C</span> <span m="161350">=</span> <span
  m="161670">0.</span></p><p><span m="162590">Pull-up</span> <span m="162930">circuits</span>
  <span m="163550">use</span> <span m="163920">PFETs</span> <span m="164420">which</span>
  <span m="164650">are</span> <span m="164800">on</span> <span m="165140">when</span>
  <span m="165350">the</span> <span m="165500">input</span> <span m="165820">is</span>
  <span m="166010">low</span> <span m="166500">(or</span> <span m="166720">0).</span></p><p><span
  m="167720">So</span> <span m="167860">the</span> <span m="167970">equivalent</span>
  <span m="168540">circuit</span> <span m="169010">for</span> <span m="169290">this</span>
  <span m="169920">is</span> <span m="170300">series(A,B)</span> <span m="172040">ORed</span>
  <span m="173130">with</span> <span m="173600">C</span> <span m="174060">which</span>
  <span m="174430">is</span> <span m="174620">equal</span> <span m="174980">to</span>
  <span m="175130">series(A,B)</span> <span m="176560">in</span> <span m="177110">parallel</span>
  <span m="177970">with</span> <span m="178430">C.</span></p>
type: course
uid: 1f9435c34f1788836ed9a04f744635d8

---
None