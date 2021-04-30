---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: ISaYWm8T8n4
  parent_uid: c66fe03a7124fba5b2c0a13f3f13ec7d
  title: Video-YouTube-Stream
  type: Video
  uid: dfdf9216c4054f779efcf25ae1efebe7
- id: 3Play-3Play YouTube id-Stream
  media_location: ISaYWm8T8n4
  parent_uid: c66fe03a7124fba5b2c0a13f3f13ec7d
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: dbdbe57b5cdb642d9688eb1fa6616982
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/ISaYWm8T8n4/default.jpg
  parent_uid: c66fe03a7124fba5b2c0a13f3f13ec7d
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: d188e0e2122a3b4d0a8b6e7211baf0c7
- id: ISaYWm8T8n4.srt
  parent_uid: c66fe03a7124fba5b2c0a13f3f13ec7d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/c21s2v5/cache-coherence-9-30-/ISaYWm8T8n4.srt
  title: 3play caption file
  type: null
  uid: cd10f90d9d4f3db37d0bbe67c8ceecff
- id: ISaYWm8T8n4.pdf
  parent_uid: c66fe03a7124fba5b2c0a13f3f13ec7d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/c21s2v5/cache-coherence-9-30-/ISaYWm8T8n4.pdf
  title: 3play pdf file
  type: null
  uid: 66fba33d4e83e3f8382fd8b9fbed4e07
- id: Caption-3Play YouTube id-SRT
  parent_uid: c66fe03a7124fba5b2c0a13f3f13ec7d
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 42d5f925db725eb907becf8f05ee23a0
- id: Transcript-3Play YouTube id-PDF
  parent_uid: c66fe03a7124fba5b2c0a13f3f13ec7d
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 165a0d98af47359ea9fbb1f35a161fe1
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_21-02-05_300k.mp4
  parent_uid: c66fe03a7124fba5b2c0a13f3f13ec7d
  title: Video-Internet Archive-MP4
  type: Video
  uid: 68557f8c5d7852281e9d54b14da4c23a
inline_embed_id: 3599479cachecoherence93047054589
layout: video
order_index: null
parent_uid: 0d91a1b1a5baf2cd7051ab686a186efb
related_resources_text: ''
short_url: cache-coherence-9-30-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c21/c21s2/c21s2v5/cache-coherence-9-30-
template_type: Embed
title: Cache Coherence
transcript: <p><span m="429">The</span> <span m="702">problem</span> <span m="975">with</span>
  <span m="1249">our</span> <span m="1522">simple</span> <span m="1795">multicore</span>
  <span m="2069">system</span> <span m="2342">is</span> <span m="2615">that</span>
  <span m="2889">there</span> <span m="3162">is</span> <span m="3435">no</span> <span
  m="3709">communication</span> <span m="3982">when</span> <span m="4255">the</span>
  <span m="4529">value</span> <span m="4991">of</span> <span m="5454">a</span> <span
  m="5917">shared</span> <span m="6380">variable</span> <span m="6843">is</span> <span
  m="7306">changed.</span></p><p><span m="7769">The</span> <span m="8054">fix</span>
  <span m="8340">is</span> <span m="8626">to</span> <span m="8912">provide</span>
  <span m="9198">the</span> <span m="9484">necessary</span> <span m="9770">communications</span>
  <span m="10056">over</span> <span m="10342">a</span> <span m="10628">shared</span>
  <span m="10914">bus</span> <span m="11200">that's</span> <span m="11486">watched</span>
  <span m="11772">by</span> <span m="12058">all</span> <span m="12344">the</span>
  <span m="12630">caches.</span></p><p><span m="13630">A</span> <span m="13978">cache</span>
  <span m="14326">can</span> <span m="14674">then</span> <span m="15022">&quot;snoop&quot;</span>
  <span m="15370">on</span> <span m="15718">what's</span> <span m="16066">happening</span>
  <span m="16415">in</span> <span m="16763">other</span> <span m="17111">caches</span>
  <span m="17459">and</span> <span m="17807">then</span> <span m="18155">update</span>
  <span m="18503">its</span> <span m="18851">local</span> <span m="19200">state</span>
  <span m="19777">to</span> <span m="20355">be</span> <span m="20932">consistent.</span></p><p><span
  m="21510">The</span> <span m="22022">required</span> <span m="22534">communications</span>
  <span m="23046">protocol</span> <span m="23558">is</span> <span m="24070">called</span>
  <span m="24582">a</span> <span m="25094">&quot;cache</span> <span m="25606">coherence</span>
  <span m="26118">protocol&quot;.</span></p><p><span m="26630">In</span> <span m="26945">designing</span>
  <span m="27261">the</span> <span m="27577">protocol,</span> <span m="27892">we'd</span>
  <span m="28208">like</span> <span m="28524">to</span> <span m="28840">incur</span>
  <span m="29155">the</span> <span m="29471">communications</span> <span m="29787">overhead</span>
  <span m="30102">only</span> <span m="30418">when</span> <span m="30734">there's</span>
  <span m="31050">actual</span> <span m="31492">sharing</span> <span m="31935">in</span>
  <span m="32378">progress,</span> <span m="32820">i.e.,</span> <span m="33263">when</span>
  <span m="33706">multiple</span> <span m="34148">caches</span> <span m="34591">have</span>
  <span m="35034">local</span> <span m="35476">copies</span> <span m="35919">of</span>
  <span m="36362">a</span> <span m="36804">shared</span> <span m="37247">variable.</span></p><p><span
  m="37690">To</span> <span m="38032">implement</span> <span m="38374">a</span> <span
  m="38716">cache</span> <span m="39058">coherence</span> <span m="39400">protocol,</span>
  <span m="39742">we'll</span> <span m="40085">change</span> <span m="40427">the</span>
  <span m="40769">state</span> <span m="41111">maintained</span> <span m="41453">for</span>
  <span m="41795">each</span> <span m="42137">cache</span> <span m="42480">line.</span></p><p><span
  m="43649">The</span> <span m="43925">initial</span> <span m="44202">state</span>
  <span m="44478">for</span> <span m="44755">all</span> <span m="45031">cache</span>
  <span m="45308">lines</span> <span m="45584">is</span> <span m="45861">INVALID</span>
  <span m="46137">indicating</span> <span m="46414">that</span> <span m="46690">the</span>
  <span m="46967">tag</span> <span m="47243">and</span> <span m="47520">data</span>
  <span m="47796">fields</span> <span m="48073">do</span> <span m="48350">not</span>
  <span m="49062">contain</span> <span m="49775">up-to-date</span> <span m="50487">information.</span></p><p><span
  m="51200">This</span> <span m="51590">corresponds</span> <span m="51980">to</span>
  <span m="52370">setting</span> <span m="52760">the</span> <span m="53150">valid</span>
  <span m="53540">bit</span> <span m="53930">to</span> <span m="54320">0</span> <span
  m="54710">in</span> <span m="55100">our</span> <span m="55490">original</span> <span
  m="55880">cache</span> <span m="56270">implementation.</span></p><p><span m="56660">When</span>
  <span m="56951">the</span> <span m="57242">cache</span> <span m="57533">line</span>
  <span m="57824">state</span> <span m="58115">is</span> <span m="58407">EXCLUSIVE,</span>
  <span m="58698">this</span> <span m="58989">cache</span> <span m="59280">has</span>
  <span m="59571">the</span> <span m="59862">only</span> <span m="60154">copy</span>
  <span m="60445">of</span> <span m="60736">those</span> <span m="61027">memory</span>
  <span m="61318">locations</span> <span m="61610">and</span> <span m="61921">indicates</span>
  <span m="62232">that</span> <span m="62544">the</span> <span m="62855">local</span>
  <span m="63167">data</span> <span m="63478">is</span> <span m="63790">the</span>
  <span m="64101">same</span> <span m="64412">as</span> <span m="64724">that</span>
  <span m="65035">in</span> <span m="65347">main</span> <span m="65658">memory.</span></p><p><span
  m="65970">This</span> <span m="66402">corresponds</span> <span m="66834">to</span>
  <span m="67266">setting</span> <span m="67698">the</span> <span m="68130">valid</span>
  <span m="68562">bit</span> <span m="68995">to</span> <span m="69427">1</span> <span
  m="69859">in</span> <span m="70291">our</span> <span m="70723">original</span> <span
  m="71155">cache</span> <span m="71587">implementation.</span></p><p><span m="72020">If</span>
  <span m="72311">the</span> <span m="72602">cache</span> <span m="72893">line</span>
  <span m="73184">state</span> <span m="73475">is</span> <span m="73767">MODIFIED,</span>
  <span m="74058">that</span> <span m="74349">means</span> <span m="74640">the</span>
  <span m="74931">cache</span> <span m="75222">line</span> <span m="75514">data</span>
  <span m="75805">is</span> <span m="76096">the</span> <span m="76387">sole</span>
  <span m="76678">valid</span> <span m="76970">copy</span> <span m="77377">of</span>
  <span m="77785">the</span> <span m="78192">data.</span></p><p><span m="78600">This</span>
  <span m="78873">corresponds</span> <span m="79147">to</span> <span m="79421">setting</span>
  <span m="79694">both</span> <span m="79968">the</span> <span m="80242">dirty</span>
  <span m="80515">and</span> <span m="80789">valid</span> <span m="81063">bits</span>
  <span m="81336">to</span> <span m="81610">1</span> <span m="81884">in</span> <span
  m="82157">our</span> <span m="82431">original</span> <span m="82705">cache</span>
  <span m="82979">implementation.</span></p><p><span m="84610">To</span> <span m="84932">deal</span>
  <span m="85255">with</span> <span m="85578">sharing</span> <span m="85900">issues,</span>
  <span m="86223">there's</span> <span m="86546">a</span> <span m="86868">fourth</span>
  <span m="87191">state</span> <span m="87514">called</span> <span m="87836">SHARED</span>
  <span m="88159">that</span> <span m="88482">indicates</span> <span m="88804">when</span>
  <span m="89127">other</span> <span m="89450">caches</span> <span m="89913">may</span>
  <span m="90376">also</span> <span m="90839">have</span> <span m="91303">a</span>
  <span m="91766">copy</span> <span m="92229">of</span> <span m="92692">the</span>
  <span m="93156">same</span> <span m="93619">unmodified</span> <span m="94082">memory</span>
  <span m="94545">data.</span></p><p><span m="95009">When</span> <span m="95319">filling</span>
  <span m="95629">a</span> <span m="95939">cache</span> <span m="96249">from</span>
  <span m="96559">main</span> <span m="96869">memory,</span> <span m="97179">other</span>
  <span m="97489">caches</span> <span m="97799">can</span> <span m="98109">snoop</span>
  <span m="98419">on</span> <span m="98729">the</span> <span m="99039">read</span>
  <span m="99349">request</span> <span m="99659">and</span> <span m="99969">participate</span>
  <span m="100280">if</span> <span m="100847">fulfilling</span> <span m="101415">the</span>
  <span m="101983">read</span> <span m="102551">request.</span></p><p><span m="103119">If</span>
  <span m="103387">no</span> <span m="103656">other</span> <span m="103925">cache</span>
  <span m="104194">has</span> <span m="104463">the</span> <span m="104731">requested</span>
  <span m="105000">data,</span> <span m="105269">the</span> <span m="105538">data</span>
  <span m="105807">is</span> <span m="106076">fetched</span> <span m="106344">from</span>
  <span m="106613">main</span> <span m="106882">memory</span> <span m="107151">and</span>
  <span m="107420">the</span> <span m="107689">requesting</span> <span m="108153">cache</span>
  <span m="108618">sets</span> <span m="109082">the</span> <span m="109547">state</span>
  <span m="110011">of</span> <span m="110476">that</span> <span m="110940">cache</span>
  <span m="111405">line</span> <span m="111869">to</span> <span m="112334">EXCLUSIVE.</span></p><p><span
  m="112799">If</span> <span m="113107">some</span> <span m="113415">other</span>
  <span m="113723">cache</span> <span m="114031">has</span> <span m="114340">the</span>
  <span m="114648">requested</span> <span m="114956">in</span> <span m="115264">line</span>
  <span m="115573">in</span> <span m="115881">the</span> <span m="116189">EXCLUSIVE</span>
  <span m="116497">or</span> <span m="116806">SHARED</span> <span m="117114">state,</span>
  <span m="117422">it</span> <span m="117730">supplies</span> <span m="118039">the</span>
  <span m="118353">data</span> <span m="118667">and</span> <span m="118982">asserts</span>
  <span m="119296">the</span> <span m="119611">SHARED</span> <span m="119925">signal</span>
  <span m="120240">on</span> <span m="120554">the</span> <span m="120868">snoopy</span>
  <span m="121183">bus</span> <span m="121497">to</span> <span m="121812">indicate</span>
  <span m="122126">that</span> <span m="122441">more</span> <span m="122755">than</span>
  <span m="123070">one</span> <span m="123417">cache</span> <span m="123765">now</span>
  <span m="124113">has</span> <span m="124461">a</span> <span m="124808">copy</span>
  <span m="125156">of</span> <span m="125504">the</span> <span m="125852">data.</span></p><p><span
  m="126200">All</span> <span m="126547">caches</span> <span m="126894">will</span>
  <span m="127242">mark</span> <span m="127589">the</span> <span m="127937">state</span>
  <span m="128284">of</span> <span m="128631">the</span> <span m="128979">cache</span>
  <span m="129326">line</span> <span m="129674">as</span> <span m="130021">SHARED.</span></p><p><span
  m="130369">If</span> <span m="130704">another</span> <span m="131040">cache</span>
  <span m="131375">has</span> <span m="131711">a</span> <span m="132047">MODIFIED</span>
  <span m="132382">copy</span> <span m="132718">of</span> <span m="133054">the</span>
  <span m="133389">cache</span> <span m="133725">line,</span> <span m="134060">it</span>
  <span m="134396">supplies</span> <span m="134732">the</span> <span m="135067">changed</span>
  <span m="135403">data,</span> <span m="135739">providing</span> <span m="136035">the</span>
  <span m="136331">correct</span> <span m="136627">values</span> <span m="136924">for</span>
  <span m="137220">the</span> <span m="137516">requesting</span> <span m="137813">cache</span>
  <span m="138109">as</span> <span m="138405">well</span> <span m="138702">as</span>
  <span m="138998">updating</span> <span m="139294">the</span> <span m="139591">values</span>
  <span m="139887">in</span> <span m="140183">main</span> <span m="140480">memory.</span></p><p><span
  m="141480">Again</span> <span m="141806">the</span> <span m="142132">SHARED</span>
  <span m="142458">signal</span> <span m="142784">is</span> <span m="143110">asserted</span>
  <span m="143436">and</span> <span m="143762">both</span> <span m="144088">the</span>
  <span m="144414">reading</span> <span m="144740">and</span> <span m="145066">responding</span>
  <span m="145392">cache</span> <span m="145718">will</span> <span m="146044">set</span>
  <span m="146370">the</span> <span m="146711">state</span> <span m="147052">for</span>
  <span m="147393">that</span> <span m="147734">cache</span> <span m="148075">line</span>
  <span m="148416">to</span> <span m="148757">SHARED.</span></p><p><span m="149099">So,</span>
  <span m="149419">at</span> <span m="149739">the</span> <span m="150059">end</span>
  <span m="150379">of</span> <span m="150699">the</span> <span m="151019">read</span>
  <span m="151339">request,</span> <span m="151659">if</span> <span m="151979">there</span>
  <span m="152299">are</span> <span m="152619">multiple</span> <span m="152939">copies</span>
  <span m="153259">of</span> <span m="153579">the</span> <span m="153899">cache</span>
  <span m="154219">line,</span> <span m="154539">they</span> <span m="154860">will</span>
  <span m="155315">all</span> <span m="155771">be</span> <span m="156226">in</span>
  <span m="156682">the</span> <span m="157137">SHARED</span> <span m="157593">state.</span></p><p><span
  m="158049">If</span> <span m="158387">there's</span> <span m="158726">only</span>
  <span m="159065">one</span> <span m="159404">copy</span> <span m="159742">of</span>
  <span m="160081">the</span> <span m="160420">cache</span> <span m="160759">line</span>
  <span m="161097">it</span> <span m="161436">will</span> <span m="161775">be</span>
  <span m="162114">in</span> <span m="162452">the</span> <span m="162791">EXCLUSIVE</span>
  <span m="163130">state.</span></p><p><span m="163469">Writing</span> <span m="163790">to</span>
  <span m="164111">a</span> <span m="164432">cache</span> <span m="164753">line</span>
  <span m="165074">is</span> <span m="165395">when</span> <span m="165716">the</span>
  <span m="166037">sharing</span> <span m="166358">magic</span> <span m="166679">happens.</span></p><p><span
  m="167000">If</span> <span m="167365">there's</span> <span m="167731">a</span> <span
  m="168096">cache</span> <span m="168462">miss,</span> <span m="168827">the</span>
  <span m="169193">first</span> <span m="169558">cache</span> <span m="169924">performs</span>
  <span m="170290">a</span> <span m="170655">cache</span> <span m="171021">line</span>
  <span m="171386">read</span> <span m="171752">as</span> <span m="172117">described</span>
  <span m="172483">above.</span></p><p><span m="172849">If</span> <span m="173079">the</span>
  <span m="173310">cache</span> <span m="173540">line</span> <span m="173771">is</span>
  <span m="174001">now</span> <span m="174232">in</span> <span m="174462">the</span>
  <span m="174693">SHARED</span> <span m="174923">state,</span> <span m="175154">a</span>
  <span m="175384">write</span> <span m="175615">will</span> <span m="175845">cause</span>
  <span m="176076">the</span> <span m="176306">cache</span> <span m="176537">to</span>
  <span m="176767">send</span> <span m="176998">an</span> <span m="177228">INVALIDATE</span>
  <span m="177459">message</span> <span m="177786">on</span> <span m="178114">the</span>
  <span m="178441">snoopy</span> <span m="178769">bus,</span> <span m="179096">telling</span>
  <span m="179424">all</span> <span m="179752">other</span> <span m="180079">caches</span>
  <span m="180407">to</span> <span m="180734">invalidate</span> <span m="181062">their</span>
  <span m="181390">copy</span> <span m="181721">of</span> <span m="182052">the</span>
  <span m="182383">cache</span> <span m="182714">line,</span> <span m="183045">guaranteeing</span>
  <span m="183377">the</span> <span m="183708">local</span> <span m="184039">cache</span>
  <span m="184370">now</span> <span m="184701">has</span> <span m="185033">EXCLUSIVE</span>
  <span m="185364">access</span> <span m="185695">to</span> <span m="186026">the</span>
  <span m="186357">cache</span> <span m="186689">line.</span></p><p><span m="188029">If</span>
  <span m="188319">the</span> <span m="188609">cache</span> <span m="188899">line</span>
  <span m="189189">is</span> <span m="189479">in</span> <span m="189769">the</span>
  <span m="190059">EXCLUSIVE</span> <span m="190349">state</span> <span m="190639">when</span>
  <span m="190929">the</span> <span m="191219">write</span> <span m="191509">happens,</span>
  <span m="191799">no</span> <span m="192089">communication</span> <span m="192379">is</span>
  <span m="192670">necessary.</span></p><p><span m="194529">Now</span> <span m="194831">the</span>
  <span m="195134">cache</span> <span m="195436">data</span> <span m="195739">can</span>
  <span m="196041">be</span> <span m="196344">changed</span> <span m="196646">and</span>
  <span m="196949">the</span> <span m="197252">cache</span> <span m="197554">line</span>
  <span m="197857">state</span> <span m="198159">set</span> <span m="198462">to</span>
  <span m="198764">MODIFIED,</span> <span m="199067">completing</span> <span m="199370">the</span>
  <span m="200239">write.</span></p><p><span m="201109">This</span> <span m="201504">protocol</span>
  <span m="201899">is</span> <span m="202295">called</span> <span m="202690">&quot;MESI&quot;</span>
  <span m="203085">after</span> <span m="203481">the</span> <span m="203876">first</span>
  <span m="204272">initials</span> <span m="204667">of</span> <span m="205062">the</span>
  <span m="205458">possible</span> <span m="205853">states.</span></p><p><span m="206249">Note</span>
  <span m="206510">that</span> <span m="206771">the</span> <span m="207033">the</span>
  <span m="207294">valid</span> <span m="207555">and</span> <span m="207817">dirty</span>
  <span m="208078">state</span> <span m="208339">bits</span> <span m="208601">in</span>
  <span m="208862">our</span> <span m="209123">original</span> <span m="209385">cache</span>
  <span m="209646">implementation</span> <span m="209907">have</span> <span m="210169">been</span>
  <span m="210593">repurposed</span> <span m="211018">to</span> <span m="211443">encode</span>
  <span m="211868">one</span> <span m="212293">of</span> <span m="212718">the</span>
  <span m="213143">four</span> <span m="213568">MESI</span> <span m="213993">states.</span></p><p><span
  m="214418">The</span> <span m="214688">key</span> <span m="214958">to</span> <span
  m="215228">success</span> <span m="215498">is</span> <span m="215768">that</span>
  <span m="216038">each</span> <span m="216308">cache</span> <span m="216578">now</span>
  <span m="216848">knows</span> <span m="217118">when</span> <span m="217388">a</span>
  <span m="217658">cache</span> <span m="217928">line</span> <span m="218198">may</span>
  <span m="218468">be</span> <span m="218738">shared</span> <span m="219008">by</span>
  <span m="219278">another</span> <span m="219549">cache,</span> <span m="219989">prompting</span>
  <span m="220430">the</span> <span m="220871">necessary</span> <span m="221311">communication</span>
  <span m="221752">when</span> <span m="222193">the</span> <span m="222634">value</span>
  <span m="223074">of</span> <span m="223515">a</span> <span m="223956">shared</span>
  <span m="224396">location</span> <span m="224837">is</span> <span m="225278">changed.</span></p><p><span
  m="225719">No</span> <span m="226101">attempt</span> <span m="226483">is</span>
  <span m="226865">made</span> <span m="227247">to</span> <span m="227629">update</span>
  <span m="228011">shared</span> <span m="228393">values,</span> <span m="228775">they're</span>
  <span m="229157">simply</span> <span m="229539">invalidated</span> <span m="229921">and</span>
  <span m="230303">the</span> <span m="230685">other</span> <span m="231067">caches</span>
  <span m="231449">will</span> <span m="231749">issue</span> <span m="232049">read</span>
  <span m="232349">requests</span> <span m="232649">if</span> <span m="232949">they</span>
  <span m="233249">need</span> <span m="233549">the</span> <span m="233849">value</span>
  <span m="234149">of</span> <span m="234449">the</span> <span m="234749">shared</span>
  <span m="235049">variable</span> <span m="235349">at</span> <span m="235649">some</span>
  <span m="235949">future</span> <span m="236250">time.</span></p><p><span m="238369">To</span>
  <span m="238693">support</span> <span m="239017">cache</span> <span m="239341">coherence,</span>
  <span m="239665">the</span> <span m="239989">cache</span> <span m="240313">hardware</span>
  <span m="240637">has</span> <span m="240961">to</span> <span m="241285">be</span>
  <span m="241609">modified</span> <span m="241933">to</span> <span m="242257">support</span>
  <span m="242581">two</span> <span m="242905">request</span> <span m="243229">streams:</span>
  <span m="243685">one</span> <span m="244141">from</span> <span m="244598">the</span>
  <span m="245054">CPU</span> <span m="245510">and</span> <span m="245967">one</span>
  <span m="246423">from</span> <span m="246879">the</span> <span m="247336">snoopy</span>
  <span m="247792">bus.</span></p><p><span m="248249">The</span> <span m="248582">CPU</span>
  <span m="248915">side</span> <span m="249249">includes</span> <span m="249582">a</span>
  <span m="249915">queue</span> <span m="250249">of</span> <span m="250582">store</span>
  <span m="250915">requests</span> <span m="251249">that</span> <span m="251582">were</span>
  <span m="251915">delayed</span> <span m="252249">by</span> <span m="252582">cache</span>
  <span m="252915">misses.</span></p><p><span m="253249">This</span> <span m="253512">allows</span>
  <span m="253775">the</span> <span m="254038">CPU</span> <span m="254301">to</span>
  <span m="254564">proceed</span> <span m="254827">without</span> <span m="255090">having</span>
  <span m="255354">to</span> <span m="255617">wait</span> <span m="255880">for</span>
  <span m="256143">the</span> <span m="256406">cache</span> <span m="256669">refill</span>
  <span m="256932">operation</span> <span m="257195">to</span> <span m="257459">complete.</span></p><p><span
  m="259048">Note</span> <span m="259320">that</span> <span m="259592">CPU</span>
  <span m="259865">read</span> <span m="260137">requests</span> <span m="260410">will</span>
  <span m="260682">need</span> <span m="260955">to</span> <span m="261227">check</span>
  <span m="261500">the</span> <span m="261772">store</span> <span m="262045">queue</span>
  <span m="262317">before</span> <span m="262590">they</span> <span m="262862">check</span>
  <span m="263135">the</span> <span m="263407">cache</span> <span m="263680">to</span>
  <span m="264134">ensure</span> <span m="264589">the</span> <span m="265044">most-recent</span>
  <span m="265499">value</span> <span m="265954">is</span> <span m="266409">supplied</span>
  <span m="266864">to</span> <span m="267319">the</span> <span m="267774">CPU.</span></p><p><span
  m="268229">Usually</span> <span m="268560">there's</span> <span m="268892">a</span>
  <span m="269223">STORE_BARRIER</span> <span m="269555">instruction</span> <span
  m="269887">that</span> <span m="270218">stalls</span> <span m="270550">the</span>
  <span m="270881">CPU</span> <span m="271213">until</span> <span m="271545">the</span>
  <span m="271876">store</span> <span m="272208">queue</span> <span m="272540">is</span>
  <span m="272922">empty,</span> <span m="273305">guaranteeing</span> <span m="273688">that</span>
  <span m="274071">all</span> <span m="274454">processors</span> <span m="274837">have</span>
  <span m="275220">seen</span> <span m="275602">the</span> <span m="275985">effect</span>
  <span m="276368">of</span> <span m="276751">the</span> <span m="277134">writes</span>
  <span m="277517">before</span> <span m="277900">execution</span> <span m="279365">resumes.</span></p><p><span
  m="280830">On</span> <span m="281152">the</span> <span m="281475">snoopy</span>
  <span m="281797">side,</span> <span m="282120">the</span> <span m="282442">cache</span>
  <span m="282765">has</span> <span m="283087">to</span> <span m="283410">snoop</span>
  <span m="283732">on</span> <span m="284055">the</span> <span m="284377">transactions</span>
  <span m="284700">from</span> <span m="285022">other</span> <span m="285345">caches,</span>
  <span m="285667">invalidating</span> <span m="285990">or</span> <span m="286390">supplying</span>
  <span m="286790">cache</span> <span m="287190">line</span> <span m="287590">data</span>
  <span m="287990">as</span> <span m="288390">appropriate,</span> <span m="288790">and</span>
  <span m="289190">then</span> <span m="289590">updating</span> <span m="289990">the</span>
  <span m="290390">local</span> <span m="290790">cache</span> <span m="291190">line</span>
  <span m="291590">state.</span></p><p><span m="291990">If</span> <span m="292274">the</span>
  <span m="292559">cache</span> <span m="292844">is</span> <span m="293128">busy</span>
  <span m="293413">with,</span> <span m="293698">say,</span> <span m="293982">a</span>
  <span m="294267">refill</span> <span m="294552">operation,</span> <span m="294837">INVALIDATE</span>
  <span m="295121">requests</span> <span m="295406">may</span> <span m="295691">be</span>
  <span m="295975">queued</span> <span m="296260">until</span> <span m="296545">they</span>
  <span m="296830">can</span> <span m="297446">be</span> <span m="298063">processed.</span></p><p><span
  m="298680">Usually</span> <span m="299036">there's</span> <span m="299392">a</span>
  <span m="299748">READ_BARRIER</span> <span m="300104">instruction</span> <span m="300460">that</span>
  <span m="300816">stalls</span> <span m="301173">the</span> <span m="301529">CPU</span>
  <span m="301885">until</span> <span m="302241">the</span> <span m="302597">invalidate</span>
  <span m="302953">queue</span> <span m="303310">is</span> <span m="303670">empty,</span>
  <span m="304031">guaranteeing</span> <span m="304392">that</span> <span m="304752">updates</span>
  <span m="305113">from</span> <span m="305474">other</span> <span m="305835">processors</span>
  <span m="306195">have</span> <span m="306556">been</span> <span m="306917">applied</span>
  <span m="307277">to</span> <span m="307638">the</span> <span m="307999">local</span>
  <span m="308360">cache</span> <span m="309124">state</span> <span m="309888">before</span>
  <span m="310652">execution</span> <span m="311416">resumes.</span></p><p><span m="312180">Note</span>
  <span m="312468">that</span> <span m="312757">the</span> <span m="313045">&quot;read</span>
  <span m="313334">with</span> <span m="313623">intent</span> <span m="313911">to</span>
  <span m="314200">modify&quot;</span> <span m="314488">transaction</span> <span m="314777">shown</span>
  <span m="315066">here</span> <span m="315354">is</span> <span m="315643">just</span>
  <span m="315931">protocol</span> <span m="316220">shorthand</span> <span m="316509">for</span>
  <span m="316899">a</span> <span m="317290">READ</span> <span m="317681">immediately</span>
  <span m="318071">followed</span> <span m="318462">by</span> <span m="318853">an</span>
  <span m="319244">INVALIDATE,</span> <span m="319634">indicating</span> <span m="320025">that</span>
  <span m="320416">the</span> <span m="320807">requester</span> <span m="321197">will</span>
  <span m="321588">be</span> <span m="321979">changing</span> <span m="322370">the</span>
  <span m="322758">contents</span> <span m="323146">of</span> <span m="323534">the</span>
  <span m="323922">cache</span> <span m="324310">line.</span></p><p><span m="324699">How</span>
  <span m="325077">do</span> <span m="325455">the</span> <span m="325834">CPU</span>
  <span m="326212">and</span> <span m="326591">snoopy</span> <span m="326969">cache</span>
  <span m="327347">requests</span> <span m="327726">affect</span> <span m="328104">the</span>
  <span m="328483">cache</span> <span m="328861">state?</span></p><p><span m="329240">Here</span>
  <span m="329576">in</span> <span m="329913">micro</span> <span m="330250">type</span>
  <span m="330586">is</span> <span m="330923">a</span> <span m="331260">flow</span>
  <span m="331596">chart</span> <span m="331933">showing</span> <span m="332270">what</span>
  <span m="332606">happens</span> <span m="332943">when.</span></p><p><span m="333280">If</span>
  <span m="333672">you're</span> <span m="334065">interested,</span> <span m="334457">try</span>
  <span m="334850">following</span> <span m="335242">the</span> <span m="335635">actions</span>
  <span m="336027">required</span> <span m="336420">to</span> <span m="336812">complete</span>
  <span m="337205">various</span> <span m="337597">transactions.</span></p><p><span
  m="337990">Intel,</span> <span m="338350">in</span> <span m="338711">its</span>
  <span m="339071">wisdom,</span> <span m="339432">adds</span> <span m="339792">a</span>
  <span m="340153">fifth</span> <span m="340513">&quot;F&quot;</span> <span m="340874">state,</span>
  <span m="341235">used</span> <span m="341595">to</span> <span m="341956">determine</span>
  <span m="342316">which</span> <span m="342677">cache</span> <span m="343037">will</span>
  <span m="343398">respond</span> <span m="343759">to</span> <span m="344095">read</span>
  <span m="344432">requests</span> <span m="344769">when</span> <span m="345106">the</span>
  <span m="345443">requested</span> <span m="345780">cache</span> <span m="346117">line</span>
  <span m="346454">is</span> <span m="346791">shared</span> <span m="347128">by</span>
  <span m="347465">multiple</span> <span m="347802">caches</span> <span m="348139">basically</span>
  <span m="348479">it</span> <span m="348819">selects</span> <span m="349159">which</span>
  <span m="349499">of</span> <span m="349839">the</span> <span m="350179">SHARED</span>
  <span m="350519">cache</span> <span m="350859">lines</span> <span m="351199">gets</span>
  <span m="351539">to</span> <span m="351879">be</span> <span m="352219">the</span>
  <span m="352559">responder.</span></p><p><span m="352900">But</span> <span m="353256">this</span>
  <span m="353613">is</span> <span m="353970">a</span> <span m="354326">bit</span>
  <span m="354683">abstract.</span></p><p><span m="355040">Let's</span> <span m="355491">try</span>
  <span m="355943">the</span> <span m="356395">MESI</span> <span m="356846">cache</span>
  <span m="357298">coherence</span> <span m="357750">protocol</span> <span m="358202">on</span>
  <span m="358653">our</span> <span m="359105">earlier</span> <span m="359557">example!</span></p><p><span
  m="360009">Here</span> <span m="360352">are</span> <span m="360695">our</span> <span
  m="361039">two</span> <span m="361382">threads</span> <span m="361725">and</span>
  <span m="362069">their</span> <span m="362412">local</span> <span m="362755">cache</span>
  <span m="363099">states</span> <span m="363442">indicating</span> <span m="363785">that</span>
  <span m="364129">values</span> <span m="364472">of</span> <span m="364815">locations</span>
  <span m="365159">X</span> <span m="365495">and</span> <span m="365831">Y</span>
  <span m="366167">are</span> <span m="366504">shared</span> <span m="366840">by</span>
  <span m="367176">both</span> <span m="367512">caches.</span></p><p><span m="367849">Let's</span>
  <span m="368232">see</span> <span m="368615">what</span> <span m="368998">happens</span>
  <span m="369381">when</span> <span m="369764">the</span> <span m="370148">operations</span>
  <span m="370531">happen</span> <span m="370914">in</span> <span m="371297">the</span>
  <span m="371680">order</span> <span m="372064">(1</span> <span m="372447">through</span>
  <span m="372830">4)</span> <span m="373213">shown</span> <span m="373596">here.</span></p><p><span
  m="373980">You</span> <span m="374314">can</span> <span m="374648">check</span>
  <span m="374983">what</span> <span m="375317">happens</span> <span m="375651">when</span>
  <span m="375986">the</span> <span m="376320">transactions</span> <span m="376655">are</span>
  <span m="376989">in</span> <span m="377323">a</span> <span m="377658">different</span>
  <span m="377992">order</span> <span m="378326">or</span> <span m="378661">happen</span>
  <span m="378995">concurrently.</span></p><p><span m="379330">First,</span> <span
  m="379844">Thread</span> <span m="380358">A</span> <span m="380872">changes</span>
  <span m="381387">X</span> <span m="381901">to</span> <span m="382415">3.</span></p><p><span
  m="382930">Since</span> <span m="383218">this</span> <span m="383507">location</span>
  <span m="383796">is</span> <span m="384085">marked</span> <span m="384374">as</span>
  <span m="384663">SHARED</span> <span m="384951">[S]</span> <span m="385240">in</span>
  <span m="385529">the</span> <span m="385818">local</span> <span m="386107">cache,</span>
  <span m="386396">the</span> <span m="386684">cache</span> <span m="386973">for</span>
  <span m="387262">core</span> <span m="387551">0</span> <span m="387840">($_0)</span>
  <span m="388129">issues</span> <span m="388505">an</span> <span m="388881">INVALIDATE</span>
  <span m="389258">transaction</span> <span m="389634">for</span> <span m="390011">location</span>
  <span m="390387">X</span> <span m="390764">to</span> <span m="391140">the</span>
  <span m="391517">other</span> <span m="391893">caches,</span> <span m="392270">giving</span>
  <span m="392600">it</span> <span m="392931">exclusive</span> <span m="393261">access</span>
  <span m="393592">to</span> <span m="393923">location</span> <span m="394253">X,</span>
  <span m="394584">which</span> <span m="394914">it</span> <span m="395245">changes</span>
  <span m="395576">to</span> <span m="395906">have</span> <span m="396237">the</span>
  <span m="396567">value</span> <span m="396898">3.</span></p><p><span m="397229">At</span>
  <span m="397463">the</span> <span m="397698">end</span> <span m="397932">of</span>
  <span m="398167">this</span> <span m="398401">step,</span> <span m="398636">the</span>
  <span m="398870">cache</span> <span m="399105">for</span> <span m="399339">core</span>
  <span m="399574">1</span> <span m="399809">($_1)</span> <span m="400043">no</span>
  <span m="400278">longer</span> <span m="400512">has</span> <span m="400747">a</span>
  <span m="400981">copy</span> <span m="401216">of</span> <span m="401450">the</span>
  <span m="401685">value</span> <span m="401920">for</span> <span m="402823">location</span>
  <span m="403726">X.</span></p><p><span m="404629">In</span> <span m="405068">step</span>
  <span m="405507">2,</span> <span m="405946">Thread</span> <span m="406385">B</span>
  <span m="406824">changes</span> <span m="407263">Y</span> <span m="407702">to</span>
  <span m="408141">4.</span></p><p><span m="408580">Since</span> <span m="408870">this</span>
  <span m="409161">location</span> <span m="409451">is</span> <span m="409742">marked</span>
  <span m="410032">as</span> <span m="410323">SHARED</span> <span m="410613">in</span>
  <span m="410904">the</span> <span m="411195">local</span> <span m="411485">cache,</span>
  <span m="411776">cache</span> <span m="412066">1</span> <span m="412357">issues</span>
  <span m="412647">an</span> <span m="412938">INVALIDATE</span> <span m="413229">transaction</span>
  <span m="413647">for</span> <span m="414066">location</span> <span m="414485">Y</span>
  <span m="414903">to</span> <span m="415322">the</span> <span m="415741">other</span>
  <span m="416159">caches,</span> <span m="416578">giving</span> <span m="416997">it</span>
  <span m="417415">exclusive</span> <span m="417834">access</span> <span m="418253">to</span>
  <span m="418671">location</span> <span m="419090">Y,</span> <span m="419509">which</span>
  <span m="419967">it</span> <span m="420426">changes</span> <span m="420885">to</span>
  <span m="421344">have</span> <span m="421803">the</span> <span m="422262">value</span>
  <span m="422721">4.</span></p><p><span m="423180">In</span> <span m="423567">step</span>
  <span m="423955">3,</span> <span m="424343">execution</span> <span m="424731">continues</span>
  <span m="425119">in</span> <span m="425507">Thread</span> <span m="425895">B,</span>
  <span m="426283">which</span> <span m="426671">needs</span> <span m="427059">the</span>
  <span m="427447">value</span> <span m="427835">of</span> <span m="428223">location</span>
  <span m="428611">X.</span></p><p><span m="428999">That's</span> <span m="429325">a</span>
  <span m="429652">cache</span> <span m="429979">miss,</span> <span m="430306">so</span>
  <span m="430633">it</span> <span m="430960">issues</span> <span m="431287">a</span>
  <span m="431614">read</span> <span m="431941">request</span> <span m="432267">on</span>
  <span m="432594">the</span> <span m="432921">snoopy</span> <span m="433248">bus,</span>
  <span m="433575">and</span> <span m="433902">cache</span> <span m="434229">0</span>
  <span m="434556">responds</span> <span m="434883">with</span> <span m="435210">its</span>
  <span m="435701">updated</span> <span m="436193">value,</span> <span m="436685">and</span>
  <span m="437176">both</span> <span m="437668">caches</span> <span m="438160">mark</span>
  <span m="438651">the</span> <span m="439143">location</span> <span m="439635">X</span>
  <span m="440126">as</span> <span m="440618">SHARED.</span></p><p><span m="441110">Main</span>
  <span m="441451">memory,</span> <span m="441793">which</span> <span m="442135">is</span>
  <span m="442476">also</span> <span m="442818">watching</span> <span m="443160">the</span>
  <span m="443501">snoopy</span> <span m="443843">bus,</span> <span m="444185">also</span>
  <span m="444527">updates</span> <span m="444868">its</span> <span m="445210">copy</span>
  <span m="445552">of</span> <span m="445893">the</span> <span m="446235">X</span>
  <span m="446577">value.</span></p><p><span m="446919">Finally,</span> <span m="447264">in</span>
  <span m="447610">step</span> <span m="447956">4,</span> <span m="448302">Thread</span>
  <span m="448648">A</span> <span m="448994">needs</span> <span m="449340">the</span>
  <span m="449686">value</span> <span m="450032">for</span> <span m="450378">Y,</span>
  <span m="450724">which</span> <span m="451070">results</span> <span m="451416">in</span>
  <span m="451762">a</span> <span m="452108">similar</span> <span m="452454">transaction</span>
  <span m="452800">on</span> <span m="453207">the</span> <span m="453615">snoopy</span>
  <span m="454022">bus.</span></p><p><span m="454430">Note</span> <span m="454775">the</span>
  <span m="455121">outcome</span> <span m="455467">corresponds</span> <span m="455812">exactly</span>
  <span m="456158">to</span> <span m="456504">that</span> <span m="456850">produced</span>
  <span m="457195">by</span> <span m="457541">the</span> <span m="457887">same</span>
  <span m="458232">execution</span> <span m="458578">sequence</span> <span m="458924">on</span>
  <span m="459270">a</span> <span m="459706">timeshared</span> <span m="460143">core</span>
  <span m="460579">since</span> <span m="461016">the</span> <span m="461452">coherence</span>
  <span m="461889">protocol</span> <span m="462325">guarantees</span> <span m="462762">that</span>
  <span m="463199">no</span> <span m="463567">cache</span> <span m="463935">has</span>
  <span m="464303">an</span> <span m="464671">out-of-date</span> <span m="465039">copy</span>
  <span m="465408">of</span> <span m="465776">a</span> <span m="466144">shared</span>
  <span m="466512">memory</span> <span m="466880">location.</span></p><p><span m="467249">And</span>
  <span m="467634">both</span> <span m="468019">caches</span> <span m="468405">agree</span>
  <span m="468790">on</span> <span m="469175">the</span> <span m="469561">ending</span>
  <span m="469946">values</span> <span m="470331">for</span> <span m="470717">the</span>
  <span m="471102">shared</span> <span m="471487">variables</span> <span m="471873">X</span>
  <span m="472258">and</span> <span m="472643">Y.</span></p><p><span m="473029">If</span>
  <span m="473367">you</span> <span m="473706">try</span> <span m="474044">other</span>
  <span m="474383">execution</span> <span m="474721">orders,</span> <span m="475060">you'll</span>
  <span m="475398">see</span> <span m="475737">that</span> <span m="476075">sequential</span>
  <span m="476414">consistency</span> <span m="476752">and</span> <span m="477091">shared</span>
  <span m="477430">memory</span> <span m="477930">semantics</span> <span m="478430">are</span>
  <span m="478930">maintained</span> <span m="479430">in</span> <span m="479930">each</span>
  <span m="480430">case.</span></p><p><span m="480930">The</span> <span m="481303">cache</span>
  <span m="481677">coherency</span> <span m="482050">protocol</span> <span m="482424">has</span>
  <span m="482798">done</span> <span m="483171">it's</span> <span m="483545">job!</span></p><p><span
  m="483919">Let's</span> <span m="484534">summarize</span> <span m="485150">our</span>
  <span m="485766">discussion</span> <span m="486381">of</span> <span m="486997">parallel</span>
  <span m="487613">processing.</span></p><p><span m="488229">At</span> <span m="488524">the</span>
  <span m="488820">moment,</span> <span m="489116">it</span> <span m="489412">seems</span>
  <span m="489708">that</span> <span m="490004">the</span> <span m="490300">architecture</span>
  <span m="490596">of</span> <span m="490892">a</span> <span m="491188">single</span>
  <span m="491484">core</span> <span m="491780">has</span> <span m="492076">reached</span>
  <span m="492372">a</span> <span m="492668">stable</span> <span m="492964">point.</span></p><p><span
  m="493260">At</span> <span m="493670">least</span> <span m="494081">with</span>
  <span m="494491">the</span> <span m="494902">current</span> <span m="495313">ISAs,</span>
  <span m="495723">pipeline</span> <span m="496134">depths</span> <span m="496545">are</span>
  <span m="496955">unlikely</span> <span m="497366">to</span> <span m="497777">increase</span>
  <span m="498187">and</span> <span m="498598">out-of-order,</span> <span m="499009">superscalar</span>
  <span m="499498">instruction</span> <span m="499987">execution</span> <span m="500476">has</span>
  <span m="500965">reached</span> <span m="501454">the</span> <span m="501943">point</span>
  <span m="502432">of</span> <span m="502921">diminishing</span> <span m="503410">performance</span>
  <span m="503899">returns.</span></p><p><span m="504389">So</span> <span m="504688">it</span>
  <span m="504987">seems</span> <span m="505286">unlikely</span> <span m="505585">there</span>
  <span m="505885">will</span> <span m="506184">be</span> <span m="506483">dramatic</span>
  <span m="506782">performance</span> <span m="507082">improvements</span> <span m="507381">due</span>
  <span m="507680">to</span> <span m="507979">architectural</span> <span m="508279">changes</span>
  <span m="508867">inside</span> <span m="509455">the</span> <span m="510043">CPU</span>
  <span m="510631">core.</span></p><p><span m="511219">GPU</span> <span m="511560">architectures</span>
  <span m="511902">continue</span> <span m="512243">to</span> <span m="512585">evolve</span>
  <span m="512926">as</span> <span m="513268">they</span> <span m="513609">adapt</span>
  <span m="513951">to</span> <span m="514292">new</span> <span m="514634">uses</span>
  <span m="514975">in</span> <span m="515317">specific</span> <span m="515658">application</span>
  <span m="516000">areas,</span> <span m="516615">but</span> <span m="517230">they</span>
  <span m="517846">are</span> <span m="518461">unlikely</span> <span m="519077">to</span>
  <span m="519692">impact</span> <span m="520308">general-purpose</span> <span m="520923">computing.</span></p><p><span
  m="521539">At</span> <span m="521788">the</span> <span m="522037">system</span>
  <span m="522287">level,</span> <span m="522536">the</span> <span m="522786">trend</span>
  <span m="523035">is</span> <span m="523285">toward</span> <span m="523534">increasing</span>
  <span m="523784">the</span> <span m="524033">number</span> <span m="524282">of</span>
  <span m="524532">cores</span> <span m="524781">and</span> <span m="525031">figuring</span>
  <span m="525280">out</span> <span m="525530">how</span> <span m="525779">to</span>
  <span m="526029">best</span> <span m="526775">exploit</span> <span m="527522">parallelism</span>
  <span m="528269">with</span> <span m="529016">new</span> <span m="529763">algorithms.</span></p><p><span
  m="530510">Looking</span> <span m="530880">further</span> <span m="531250">ahead,</span>
  <span m="531620">notice</span> <span m="531990">that</span> <span m="532360">the</span>
  <span m="532730">brain</span> <span m="533100">is</span> <span m="533470">able</span>
  <span m="533840">to</span> <span m="534210">accomplish</span> <span m="534580">remarkable</span>
  <span m="534950">results</span> <span m="535320">using</span> <span m="535690">fairly</span>
  <span m="536055">slow</span> <span m="536421">mechanisms</span> <span m="536787">It</span>
  <span m="537153">takes</span> <span m="537518">~.01</span> <span m="537884">seconds</span>
  <span m="538250">to</span> <span m="538616">get</span> <span m="538981">a</span>
  <span m="539347">message</span> <span m="539713">to</span> <span m="540079">the</span>
  <span m="540566">brain</span> <span m="541053">and</span> <span m="541540">synapses</span>
  <span m="542027">fire</span> <span m="542514">somewhere</span> <span m="543001">between</span>
  <span m="543488">0.3</span> <span m="543975">to</span> <span m="544462">1.8</span>
  <span m="544949">times</span> <span m="545436">per</span> <span m="545923">second.</span></p><p><span
  m="546410">Is</span> <span m="546811">it</span> <span m="547213">massive</span>
  <span m="547615">parallelism</span> <span m="548016">that</span> <span m="548418">gives</span>
  <span m="548820">the</span> <span m="549222">brain</span> <span m="549623">its</span>
  <span m="550025">&quot;computational&quot;</span> <span m="550427">power?</span></p><p><span
  m="550829">Or</span> <span m="551135">is</span> <span m="551442">it</span> <span
  m="551749">that</span> <span m="552055">the</span> <span m="552362">brain</span>
  <span m="552669">uses</span> <span m="552976">a</span> <span m="553282">different</span>
  <span m="553589">computation</span> <span m="553896">model,</span> <span m="554202">e.g.,</span>
  <span m="554509">neural</span> <span m="554816">nets,</span> <span m="555123">to</span>
  <span m="555429">decide</span> <span m="555736">upon</span> <span m="556043">new</span>
  <span m="556350">actions</span> <span m="556962">given</span> <span m="557575">new</span>
  <span m="558187">inputs?</span></p><p><span m="558800">At</span> <span m="559195">least</span>
  <span m="559591">for</span> <span m="559987">applications</span> <span m="560383">involving</span>
  <span m="560779">cognition</span> <span m="561175">there</span> <span m="561570">are</span>
  <span m="561966">new</span> <span m="562362">architectural</span> <span m="562758">and</span>
  <span m="563154">technology</span> <span m="563550">frontiers</span> <span m="564226">to</span>
  <span m="564902">explore.</span></p><p><span m="565579">You</span> <span m="565849">have</span>
  <span m="566119">some</span> <span m="566389">interesting</span> <span m="566659">challenges</span>
  <span m="566929">ahead</span> <span m="567199">if</span> <span m="567469">you</span>
  <span m="567739">get</span> <span m="568009">interested</span> <span m="568279">in</span>
  <span m="568549">the</span> <span m="568819">future</span> <span m="569089">of</span>
  <span m="569359">parallel</span> <span m="569630">processing!</span></p>
type: course
uid: c66fe03a7124fba5b2c0a13f3f13ec7d

---
None