---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: J6rzqMwDUmM
  parent_uid: 51a8ea01eac05faf96c9ecf0c605ffcb
  title: Video-YouTube-Stream
  type: Video
  uid: 09a0662418cfa88cea1b37f8241c4d19
- id: 3Play-3Play YouTube id-Stream
  media_location: J6rzqMwDUmM
  parent_uid: 51a8ea01eac05faf96c9ecf0c605ffcb
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 8583d16d76609e9bea90236b123340cf
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/J6rzqMwDUmM/default.jpg
  parent_uid: 51a8ea01eac05faf96c9ecf0c605ffcb
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 62aca8919fa6f65af1d88fc72c193359
- id: J6rzqMwDUmM.srt
  parent_uid: 51a8ea01eac05faf96c9ecf0c605ffcb
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c4/c4s2/c4s2v8/combinational-logic-timing/J6rzqMwDUmM.srt
  title: 3play caption file
  type: null
  uid: 81f9d27c59d9687f3b84826cfe6c6fbe
- id: J6rzqMwDUmM.pdf
  parent_uid: 51a8ea01eac05faf96c9ecf0c605ffcb
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c4/c4s2/c4s2v8/combinational-logic-timing/J6rzqMwDUmM.pdf
  title: 3play pdf file
  type: null
  uid: 5cc5c67ffb37073523dc4cd1dd11726a
- id: Caption-3Play YouTube id-SRT
  parent_uid: 51a8ea01eac05faf96c9ecf0c605ffcb
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 494537da3a07a68ddab278c6cf42faac
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 51a8ea01eac05faf96c9ecf0c605ffcb
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 36d195291d3c7225c3dc07cb97b9af3f
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_04-02-08-03_300k.mp4
  parent_uid: 51a8ea01eac05faf96c9ecf0c605ffcb
  title: Video-Internet Archive-MP4
  type: Video
  uid: bef47705a2fbcb01ba15893a898f9cf7
inline_embed_id: 89665704combinationallogictiming68375420
layout: video
order_index: null
parent_uid: 8f2c6bc38a024382dbe3d1ddde84d0f6
related_resources_text: ''
short_url: combinational-logic-timing
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c4/c4s2/c4s2v8/combinational-logic-timing
template_type: Embed
title: 'Worked Example: Combinational Logic Timing'
transcript: <p><span m="1010">We</span> <span m="1423">are</span> <span m="1836">given</span>
  <span m="2250">the</span> <span m="2663">combinational</span> <span m="3076">circuit</span>
  <span m="3490">shown</span> <span m="3903">here</span> <span m="4316">consisting</span>
  <span m="4730">of</span> <span m="5143">an</span> <span m="5556">inverter,</span>
  <span m="5970">an</span> <span m="6383">AND</span> <span m="6796">gate,</span> <span
  m="7210">an</span> <span m="7682">exclusive</span> <span m="8155">OR</span> <span
  m="8628">gate,</span> <span m="9101">and</span> <span m="9574">a</span> <span m="10047">multiplexor.</span></p><p><span
  m="10520">We</span> <span m="10852">are</span> <span m="11185">also</span> <span
  m="11518">provided</span> <span m="11850">with</span> <span m="12183">the</span>
  <span m="12516">contamination</span> <span m="12848">and</span> <span m="13181">propagation</span>
  <span m="13514">delays</span> <span m="13846">for</span> <span m="14179">each</span>
  <span m="14512">of</span> <span m="14844">the</span> <span m="15177">components</span>
  <span m="15510">in</span> <span m="16073">the</span> <span m="16636">circuit.</span></p><p><span
  m="17200">We</span> <span m="17552">are</span> <span m="17905">then</span> <span
  m="18258">asked</span> <span m="18610">to</span> <span m="18963">determine</span>
  <span m="19316">the</span> <span m="19668">contamination</span> <span m="20021">delay</span>
  <span m="20374">and</span> <span m="20726">propagation</span> <span m="21079">delay</span>
  <span m="21432">for</span> <span m="21784">the</span> <span m="22137">entire</span>
  <span m="22490">circuit.</span></p><p><span m="24060">The</span> <span m="24368">propagation</span>
  <span m="24676">delay</span> <span m="24984">of</span> <span m="25292">a</span>
  <span m="25601">circuit</span> <span m="25909">is</span> <span m="26217">defined</span>
  <span m="26525">as</span> <span m="26834">the</span> <span m="27142">longest</span>
  <span m="27450">delay</span> <span m="27758">that</span> <span m="28067">can</span>
  <span m="28375">occur</span> <span m="28683">from</span> <span m="28991">when</span>
  <span m="29300">the</span> <span m="29806">inputs</span> <span m="30313">changed</span>
  <span m="30819">to</span> <span m="31326">when</span> <span m="31832">the</span>
  <span m="32339">output</span> <span m="32845">becomes</span> <span m="33352">stable.</span></p><p><span
  m="33859">In</span> <span m="34180">order</span> <span m="34502">to</span> <span
  m="34824">calculate</span> <span m="35146">the</span> <span m="35468">propagation</span>
  <span m="35790">delay</span> <span m="36112">of</span> <span m="36434">a</span>
  <span m="36756">circuit,</span> <span m="37078">we</span> <span m="37400">need</span>
  <span m="37722">to</span> <span m="38044">identify</span> <span m="38366">the</span>
  <span m="38688">path</span> <span m="39010">from</span> <span m="39453">input</span>
  <span m="39897">to</span> <span m="40341">output</span> <span m="40785">whose</span>
  <span m="41229">sum</span> <span m="41673">of</span> <span m="42116">the</span>
  <span m="42560">propagation</span> <span m="43004">delays</span> <span m="43448">is</span>
  <span m="43892">the</span> <span m="44336">largest.</span></p><p><span m="44780">For</span>
  <span m="45185">this</span> <span m="45590">circuit,</span> <span m="45995">the</span>
  <span m="46400">longest</span> <span m="46805">delay</span> <span m="47210">path</span>
  <span m="47615">is</span> <span m="48020">through</span> <span m="48425">the</span>
  <span m="48830">exclusive</span> <span m="49235">or</span> <span m="49640">gate</span>
  <span m="50045">and</span> <span m="50450">the</span> <span m="50855">multiplexor.</span></p><p><span
  m="51260">The</span> <span m="51855">sum</span> <span m="52451">of</span> <span
  m="53047">the</span> <span m="53643">propagation</span> <span m="54239">delay</span>
  <span m="54834">across</span> <span m="55430">these</span> <span m="56026">2</span>
  <span m="56622">gates</span> <span m="57218">is</span> <span m="57814">2.1</span>
  <span m="58409">+</span> <span m="59005">1.5</span> <span m="59601">=</span> <span
  m="60197">3.6</span> <span m="60793">ns.</span></p><p><span m="61389">The</span>
  <span m="61746">contamination</span> <span m="62104">delay</span> <span m="62461">of</span>
  <span m="62819">a</span> <span m="63176">circuit</span> <span m="63534">is</span>
  <span m="63891">defined</span> <span m="64249">as</span> <span m="64607">the</span>
  <span m="64964">shortest</span> <span m="65322">delay</span> <span m="65679">from</span>
  <span m="66037">when</span> <span m="66394">the</span> <span m="66752">inputs</span>
  <span m="67110">change</span> <span m="67400">to</span> <span m="67691">when</span>
  <span m="67981">the</span> <span m="68272">outputs</span> <span m="68563">begin</span>
  <span m="68853">to</span> <span m="69144">change,</span> <span m="69435">or</span>
  <span m="69725">when</span> <span m="70016">the</span> <span m="70306">outputs</span>
  <span m="70597">are</span> <span m="70888">no</span> <span m="71178">longer</span>
  <span m="71469">guaranteed</span> <span m="71760">to</span> <span m="72274">be</span>
  <span m="72788">holding</span> <span m="73302">their</span> <span m="73817">previous</span>
  <span m="74331">stable</span> <span m="74845">value.</span></p><p><span m="75360">In</span>
  <span m="75726">order</span> <span m="76093">to</span> <span m="76460">calculate</span>
  <span m="76827">the</span> <span m="77194">contamination</span> <span m="77561">delay,</span>
  <span m="77928">we</span> <span m="78295">find</span> <span m="78661">the</span>
  <span m="79028">path</span> <span m="79395">whose</span> <span m="79762">sum</span>
  <span m="80129">of</span> <span m="80496">the</span> <span m="80863">contamination</span>
  <span m="81230">delays</span> <span m="81727">is</span> <span m="82225">the</span>
  <span m="82722">least.</span></p><p><span m="83220">For</span> <span m="83627">this</span>
  <span m="84035">circuit,</span> <span m="84442">the</span> <span m="84850">shortest</span>
  <span m="85257">path</span> <span m="85665">is</span> <span m="86072">from</span>
  <span m="86480">input</span> <span m="86887">A</span> <span m="87295">through</span>
  <span m="87702">the</span> <span m="88110">selector</span> <span m="88517">of</span>
  <span m="88925">the</span> <span m="89332">multiplexor.</span></p><p><span m="89740">So</span>
  <span m="90064">the</span> <span m="90389">contamination</span> <span m="90714">delay</span>
  <span m="91038">for</span> <span m="91363">this</span> <span m="91688">circuit</span>
  <span m="92012">is</span> <span m="92337">equal</span> <span m="92662">to</span>
  <span m="92986">the</span> <span m="93311">contamination</span> <span m="93636">delay</span>
  <span m="93960">of</span> <span m="94285">the</span> <span m="94610">multiplexor</span>
  <span m="95456">which</span> <span m="96302">equals</span> <span m="97148">0.2</span>
  <span m="97994">ns.</span></p>
type: course
uid: 51a8ea01eac05faf96c9ecf0c605ffcb

---
None