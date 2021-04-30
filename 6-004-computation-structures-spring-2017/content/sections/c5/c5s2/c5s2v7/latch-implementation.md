---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: d4Auh7uWEjY
  parent_uid: a9e386f7ebba6ff43938c7c822988941
  title: Video-YouTube-Stream
  type: Video
  uid: 1ba155803be18c7f8db22fa6cb53a174
- id: 3Play-3Play YouTube id-Stream
  media_location: d4Auh7uWEjY
  parent_uid: a9e386f7ebba6ff43938c7c822988941
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 8bd29d0f6aa47db5a48b89422a9a3005
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/d4Auh7uWEjY/default.jpg
  parent_uid: a9e386f7ebba6ff43938c7c822988941
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 853b27b68f0abf5fbbdacc9d22c50f90
- id: d4Auh7uWEjY.srt
  parent_uid: a9e386f7ebba6ff43938c7c822988941
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c5/c5s2/c5s2v7/latch-implementation/d4Auh7uWEjY.srt
  title: 3play caption file
  type: null
  uid: 55e45549047d622497add32e33e0db3c
- id: d4Auh7uWEjY.pdf
  parent_uid: a9e386f7ebba6ff43938c7c822988941
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c5/c5s2/c5s2v7/latch-implementation/d4Auh7uWEjY.pdf
  title: 3play pdf file
  type: null
  uid: 8097f5f0f18fbca49cdbfb064a33306e
- id: Caption-3Play YouTube id-SRT
  parent_uid: a9e386f7ebba6ff43938c7c822988941
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 01f4e29861e2e760a3c4f2caea4a7b09
- id: Transcript-3Play YouTube id-PDF
  parent_uid: a9e386f7ebba6ff43938c7c822988941
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: c32d6b3010af468bedb5dd15255393b1
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_05-02-07-01_300k.mp4
  parent_uid: a9e386f7ebba6ff43938c7c822988941
  title: Video-Internet Archive-MP4
  type: Video
  uid: ec7d5f5afd3b337d1a5468ac5f20c919
inline_embed_id: 99326259latchimplementation84800233
layout: video
order_index: null
parent_uid: 1d425303f37baba2a57a9900300c624f
related_resources_text: ''
short_url: latch-implementation
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c5/c5s2/c5s2v7/latch-implementation
template_type: Embed
title: 'Worked Example: Latch Implementation'
transcript: <p><span m="440">The</span> <span m="970">goal</span> <span m="1300">of</span>
  <span m="1390">this</span> <span m="1620">problem</span> <span m="2080">is</span>
  <span m="2240">to</span> <span m="2350">design</span> <span m="2890">a</span> <span
  m="3000">reliable</span> <span m="3620">latch.</span></p><p><span m="4670">A</span>
  <span m="4710">latch</span> <span m="5260">can</span> <span m="5460">be</span> <span
  m="5580">designed</span> <span m="6160">using</span> <span m="6510">a</span> <span
  m="6560">multiplexor</span> <span m="7720">where</span> <span m="8070">the</span>
  <span m="8210">G</span> <span m="8540">input</span> <span m="9070">is</span> <span
  m="9330">used</span> <span m="9600">to</span> <span m="9660">determine</span> <span
  m="10360">whether</span> <span m="10690">or</span> <span m="10850">not</span> <span
  m="11150">a</span> <span m="11220">new</span> <span m="11440">data</span> <span
  m="11770">value</span> <span m="12190">should</span> <span m="12410">be</span> <span
  m="12530">loaded</span> <span m="13120">into</span> <span m="13500">the</span> <span
  m="13590">latch.</span></p><p><span m="14700">The</span> <span m="14780">way</span>
  <span m="15020">the</span> <span m="15090">latch</span> <span m="15460">works</span>
  <span m="16160">is</span> <span m="16470">that</span> <span m="16590">when</span>
  <span m="16790">G</span> <span m="17410">=</span> <span m="17600">0,</span> <span
  m="17630">the</span> <span m="18250">old</span> <span m="18980">value</span> <span
  m="19390">of</span> <span m="19580">Q</span> <span m="19990">is</span> <span m="20200">fed</span>
  <span m="20510">back</span> <span m="20840">through</span> <span m="21030">the</span>
  <span m="21130">multiplexor</span> <span m="21990">so</span> <span m="22260">it</span>
  <span m="22380">retains</span> <span m="22950">its</span> <span m="23120">old</span>
  <span m="23370">value.</span></p><p><span m="24610">When</span> <span m="24770">G</span>
  <span m="25130">=</span> <span m="25310">1,</span> <span m="25440">the</span> <span
  m="26010">multiplexor</span> <span m="27040">selects</span> <span m="27650">D</span>
  <span m="27980">as</span> <span m="28180">the</span> <span m="28320">input</span>
  <span m="28920">so</span> <span m="29260">Q</span> <span m="29570">gets</span> <span
  m="29860">updated</span> <span m="30550">to</span> <span m="30710">be</span> <span
  m="30890">the</span> <span m="30970">value</span> <span m="31510">of</span> <span
  m="31660">D.</span></p><p><span m="33100">The</span> <span m="33160">logic</span>
  <span m="33670">function</span> <span m="34140">that</span> <span m="34280">describes</span>
  <span m="34850">the</span> <span m="34940">operation</span> <span m="35610">of</span>
  <span m="35730">the</span> <span m="35810">latch</span> <span m="36560">is</span>
  <span m="37080">Q</span> <span m="37840">=</span> <span m="38390">(NOT(G)</span>
  <span m="39400">AND</span> <span m="39940">Q)</span> <span m="40720">OR</span> <span
  m="41700">(G</span> <span m="42320">AND</span> <span m="42680">D).</span></p><p><span
  m="46210">We</span> <span m="46330">want</span> <span m="46630">to</span> <span
  m="46700">build</span> <span m="46970">this</span> <span m="47170">latch</span>
  <span m="47600">using</span> <span m="48030">only</span> <span m="48440">AND,</span>
  <span m="48890">OR,</span> <span m="49320">and</span> <span m="49500">inverter</span>
  <span m="50000">gates.</span></p><p><span m="51130">We</span> <span m="51250">are</span>
  <span m="51350">given</span> <span m="51800">three</span> <span m="52160">proposed</span>
  <span m="52660">designs</span> <span m="53210">for</span> <span m="53350">the</span>
  <span m="53470">latch.</span></p><p><span m="54390">For</span> <span m="54510">each</span>
  <span m="54810">proposed</span> <span m="55270">design,</span> <span m="55900">we</span>
  <span m="56080">want</span> <span m="56260">to</span> <span m="56330">specify</span>
  <span m="57000">whether</span> <span m="57290">the</span> <span m="57400">design</span>
  <span m="57880">is</span> <span m="58100">BAD,</span> <span m="58730">GOOD,</span>
  <span m="59360">or</span> <span m="59670">OBESE.</span></p><p><span m="60720">BAD</span>
  <span m="61000">means</span> <span m="61320">that</span> <span m="61460">the</span>
  <span m="61560">latch</span> <span m="61920">does</span> <span m="62110">not</span>
  <span m="62340">work</span> <span m="62580">reliably.</span></p><p><span m="63900">GOOD</span>
  <span m="64080">means</span> <span m="64440">that</span> <span m="64590">the</span>
  <span m="64690">latch</span> <span m="65040">works</span> <span m="65390">reliably.</span></p><p><span
  m="66670">OBESE</span> <span m="67340">means</span> <span m="67660">that</span>
  <span m="67820">the</span> <span m="67940">latch</span> <span m="68300">works,</span>
  <span m="68860">but</span> <span m="68970">uses</span> <span m="69350">more</span>
  <span m="69610">gates</span> <span m="70000">than</span> <span m="70180">necessary.</span></p><p><span
  m="72260">Latch</span> <span m="72510">proposal</span> <span m="73060">A</span>
  <span m="73470">is</span> <span m="73650">shown</span> <span m="74030">here.</span></p><p><span
  m="75000">Taking</span> <span m="75320">a</span> <span m="75390">closer</span> <span
  m="75900">look</span> <span m="76160">at</span> <span m="76290">this</span> <span
  m="76520">circuit,</span> <span m="77080">we</span> <span m="77420">see</span> <span
  m="77690">that</span> <span m="78030">the</span> <span m="78270">logic</span> <span
  m="78800">function</span> <span m="79220">that</span> <span m="79360">it</span>
  <span m="79510">implements</span> <span m="80310">is</span> <span m="80630">Q</span>
  <span m="81280">=</span> <span m="81900">(G</span> <span m="82580">AND</span> <span
  m="82970">Q)</span> <span m="83690">OR</span> <span m="84180">D.</span></p><p><span
  m="84990">This</span> <span m="85170">is</span> <span m="85300">not</span> <span
  m="85660">the</span> <span m="85770">correct</span> <span m="86210">logic</span>
  <span m="86650">equation</span> <span m="87170">for</span> <span m="87430">a</span>
  <span m="87460">latch,</span> <span m="88160">so</span> <span m="88520">this</span>
  <span m="88770">design</span> <span m="89360">is</span> <span m="89600">BAD.</span></p><p><span
  m="94410">Next,</span> <span m="94930">we</span> <span m="95080">take</span> <span
  m="95350">a</span> <span m="95380">look</span> <span m="95660">at</span> <span m="95760">proposals</span>
  <span m="96460">B</span> <span m="96760">and</span> <span m="97010">C.</span></p><p><span
  m="98180">The</span> <span m="98270">logic</span> <span m="98730">equation</span>
  <span m="99270">for</span> <span m="99440">proposal</span> <span m="100030">B</span>
  <span m="100550">is</span> <span m="100890">Q</span> <span m="101530">=</span> <span
  m="101980">(NOT(G)</span> <span m="102710">AND</span> <span m="103090">Q)</span>
  <span m="103780">OR</span> <span m="104460">(G</span> <span m="104860">AND</span>
  <span m="105170">D)).</span></p><p><span m="106030">This</span> <span m="106200">is</span>
  <span m="106330">exactly</span> <span m="106910">the</span> <span m="107030">same</span>
  <span m="107370">logic</span> <span m="107750">equation</span> <span m="108290">that</span>
  <span m="108400">we</span> <span m="108510">specified</span> <span m="109220">for</span>
  <span m="109630">our</span> <span m="109690">latch.</span></p><p><span m="110570">However,</span>
  <span m="111190">this</span> <span m="111480">implementation</span> <span m="112360">is</span>
  <span m="112540">not</span> <span m="112850">lenient</span> <span m="113470">because</span>
  <span m="113870">it</span> <span m="113990">does</span> <span m="114170">not</span>
  <span m="114440">guarantee</span> <span m="115000">that</span> <span m="115150">you</span>
  <span m="115270">will</span> <span m="115420">not</span> <span m="115700">see</span>
  <span m="115890">glitches</span> <span m="116430">on</span> <span m="116630">your</span>
  <span m="116770">output</span> <span m="117150">signal</span> <span m="117810">when</span>
  <span m="118160">G</span> <span m="118420">changes</span> <span m="118960">value.</span></p><p><span
  m="120150">Proposal</span> <span m="120660">C,</span> <span m="121000">however,</span>
  <span m="121780">includes</span> <span m="122460">the</span> <span m="122520">same</span>
  <span m="122960">logic</span> <span m="123400">function</span> <span m="124190">Q</span>
  <span m="124960">=</span> <span m="125270">(NOT(G)</span> <span m="125870">AND</span>
  <span m="126090">Q)</span> <span m="126780">OR</span> <span m="127470">(G</span>
  <span m="127800">AND</span> <span m="128039">D))</span> <span m="128620">plus</span>
  <span m="129240">one</span> <span m="129460">more</span> <span m="129699">term</span>
  <span m="130160">which</span> <span m="130530">is</span> <span m="130800">OR</span>
  <span m="131410">(Q</span> <span m="131890">AND</span> <span m="132250">D).</span></p><p><span
  m="133690">If</span> <span m="133810">you</span> <span m="133920">create</span>
  <span m="134280">a</span> <span m="134320">karnaugh</span> <span m="134830">map</span>
  <span m="135210">for</span> <span m="135380">both</span> <span m="135710">of</span>
  <span m="135820">these</span> <span m="136000">logic</span> <span m="136410">functions,</span>
  <span m="137250">you</span> <span m="137520">see</span> <span m="137800">that</span>
  <span m="138400">the</span> <span m="138730">QD</span> <span m="138790">term</span>
  <span m="139220">is</span> <span m="139410">redundant</span> <span m="140120">because</span>
  <span m="140470">it</span> <span m="140580">doesn't</span> <span m="140990">add</span>
  <span m="141250">any</span> <span m="141500">additional</span> <span m="142220">1's</span>
  <span m="142420">to</span> <span m="142530">the</span> <span m="142610">karnaugh</span>
  <span m="143060">map.</span></p><p><span m="144010">This</span> <span m="144210">means</span>
  <span m="144470">that</span> <span m="144620">logically</span> <span m="145400">the</span>
  <span m="145530">two</span> <span m="145730">functions</span> <span m="146320">are</span>
  <span m="146470">equivalent,</span> <span m="147330">but</span> <span m="147670">the</span>
  <span m="147750">effect</span> <span m="148230">of</span> <span m="148320">the</span>
  <span m="148440">extra</span> <span m="148840">term</span> <span m="149280">is</span>
  <span m="149440">that</span> <span m="149600">it</span> <span m="149690">makes</span>
  <span m="150000">the</span> <span m="150100">implementation</span> <span m="151020">lenient.</span></p><p><span
  m="152130">So</span> <span m="152320">Proposal</span> <span m="152920">C</span>
  <span m="153250">is</span> <span m="153470">the</span> <span m="153700">GOOD</span>
  <span m="154120">proposal</span> <span m="155000">and</span> <span m="155090">B</span>
  <span m="155520">is</span> <span m="155790">BAD.</span></p>
type: course
uid: a9e386f7ebba6ff43938c7c822988941

---
None