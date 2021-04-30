---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: UW9k06c63ts
  parent_uid: 1ff29cb41ca307b7bce1a59a0554d12a
  title: Video-YouTube-Stream
  type: Video
  uid: c001f8f76ae2bfc5c5e65277974384e8
- id: 3Play-3Play YouTube id-Stream
  media_location: UW9k06c63ts
  parent_uid: 1ff29cb41ca307b7bce1a59a0554d12a
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 5e0299a6fcbdb5425a47d36615c9d7cf
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_17-02-02_300k.mp4
  parent_uid: 1ff29cb41ca307b7bce1a59a0554d12a
  title: Video-Internet Archive-MP4
  type: Video
  uid: 96fe709c77cfd759e3f388e2d239a6b2
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/UW9k06c63ts/default.jpg
  parent_uid: 1ff29cb41ca307b7bce1a59a0554d12a
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 6d64bea132c0cff74ef40d37818e94a2
- id: UW9k06c63ts.srt
  parent_uid: 1ff29cb41ca307b7bce1a59a0554d12a
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v2/processes-8-36-/UW9k06c63ts.srt
  title: 3play caption file
  type: null
  uid: 9a4eaf559c4a8b533418c114fef7f5e0
- id: UW9k06c63ts.pdf
  parent_uid: 1ff29cb41ca307b7bce1a59a0554d12a
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v2/processes-8-36-/UW9k06c63ts.pdf
  title: 3play pdf file
  type: null
  uid: 9be81e65445e663b5835178e81914d4e
- id: Caption-3Play YouTube id-SRT
  parent_uid: 1ff29cb41ca307b7bce1a59a0554d12a
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 496226f00286d1067d5ee4c264c4d437
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 1ff29cb41ca307b7bce1a59a0554d12a
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 4b24b2ae2916f1e66dfa01038228dbdc
inline_embed_id: 63905704processes83628854333
layout: video
order_index: null
parent_uid: 16b50ee2c257e9e2dfba647380b66efd
related_resources_text: ''
short_url: processes-8-36-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c17/c17s2/c17s2v2/processes-8-36-
template_type: Embed
title: Processes
transcript: <p><span m="350">Let's</span> <span m="688">create</span> <span m="1026">a</span>
  <span m="1364">new</span> <span m="1702">abstraction</span> <span m="2040">called</span>
  <span m="2378">a</span> <span m="2716">&quot;process&quot;</span> <span m="3054">to</span>
  <span m="3392">capture</span> <span m="3730">the</span> <span m="4068">notion</span>
  <span m="4406">of</span> <span m="4744">a</span> <span m="5082">running</span> <span
  m="5420">program.</span></p><p><span m="5759">A</span> <span m="6063">process</span>
  <span m="6368">encompasses</span> <span m="6673">all</span> <span m="6977">the</span>
  <span m="7282">resources</span> <span m="7587">that</span> <span m="7892">would</span>
  <span m="8196">be</span> <span m="8501">used</span> <span m="8806">when</span> <span
  m="9111">running</span> <span m="9415">a</span> <span m="9720">program</span> <span
  m="10025">including</span> <span m="10330">those</span> <span m="10856">of</span>
  <span m="11382">the</span> <span m="11908">CPU,</span> <span m="12435">the</span>
  <span m="12961">MMU,</span> <span m="13487">input</span> <span m="14013">and</span>
  <span m="14540">output</span> <span m="15066">devices,</span> <span m="15592">etc.</span></p><p><span
  m="16119">Each</span> <span m="16513">process</span> <span m="16908">has</span>
  <span m="17303">a</span> <span m="17697">&quot;state&quot;</span> <span m="18092">that</span>
  <span m="18487">captures</span> <span m="18881">everything</span> <span m="19276">we</span>
  <span m="19671">know</span> <span m="20065">about</span> <span m="20460">its</span>
  <span m="20855">execution.</span></p><p><span m="21250">The</span> <span m="21626">process</span>
  <span m="22002">state</span> <span m="22378">includes</span> <span m="22754">*</span>
  <span m="23130">the</span> <span m="23506">hardware</span> <span m="23883">state</span>
  <span m="24259">of</span> <span m="24635">the</span> <span m="25011">CPU,</span>
  <span m="25387">i.e.,</span> <span m="25763">the</span> <span m="26140">values</span>
  <span m="26555">in</span> <span m="26971">the</span> <span m="27387">registers</span>
  <span m="27802">and</span> <span m="28218">program</span> <span m="28634">counter.</span></p><p><span
  m="29050">*</span> <span m="29387">the</span> <span m="29724">contents</span> <span
  m="30061">of</span> <span m="30399">the</span> <span m="30736">process'</span> <span
  m="31073">virtual</span> <span m="31410">address</span> <span m="31748">space,</span>
  <span m="32085">including</span> <span m="32422">code,</span> <span m="32759">data</span>
  <span m="33097">values,</span> <span m="33434">the</span> <span m="33771">stack,</span>
  <span m="34109">and</span> <span m="34607">data</span> <span m="35106">objects</span>
  <span m="35605">dynamically</span> <span m="36104">allocated</span> <span m="36603">from</span>
  <span m="37102">the</span> <span m="37601">heap.</span></p><p><span m="38100">Under</span>
  <span m="38371">the</span> <span m="38642">management</span> <span m="38913">of</span>
  <span m="39184">the</span> <span m="39455">MMU,</span> <span m="39727">this</span>
  <span m="39998">portion</span> <span m="40269">of</span> <span m="40540">the</span>
  <span m="40811">state</span> <span m="41082">can</span> <span m="41354">be</span>
  <span m="41625">resident</span> <span m="41896">in</span> <span m="42167">main</span>
  <span m="42438">memory</span> <span m="42710">or</span> <span m="43321">can</span>
  <span m="43933">reside</span> <span m="44544">in</span> <span m="45156">secondary</span>
  <span m="45767">storage.</span></p><p><span m="46379">*</span> <span m="46688">the</span>
  <span m="46997">hardware</span> <span m="47307">state</span> <span m="47616">of</span>
  <span m="47925">the</span> <span m="48235">MMU,</span> <span m="48544">which,</span>
  <span m="48854">as</span> <span m="49163">we</span> <span m="49472">saw</span> <span
  m="49782">earlier,</span> <span m="50091">depends</span> <span m="50400">on</span>
  <span m="50710">the</span> <span m="51019">context-number</span> <span m="51329">and</span>
  <span m="52139">page-directory</span> <span m="52949">registers.</span></p><p><span
  m="53760">Also</span> <span m="54210">included</span> <span m="54661">are</span>
  <span m="55112">the</span> <span m="55563">pages</span> <span m="56014">allocated</span>
  <span m="56464">for</span> <span m="56915">the</span> <span m="57366">hierarchical</span>
  <span m="57817">page</span> <span m="58268">map.</span></p><p><span m="58719">*</span>
  <span m="59058">additional</span> <span m="59397">information</span> <span m="59736">about</span>
  <span m="60075">the</span> <span m="60415">process'</span> <span m="60754">input</span>
  <span m="61093">and</span> <span m="61432">output</span> <span m="61772">activities,</span>
  <span m="62111">such</span> <span m="62450">as</span> <span m="62789">where</span>
  <span m="63129">it</span> <span m="63430">has</span> <span m="63732">reached</span>
  <span m="64034">in</span> <span m="64336">reading</span> <span m="64637">or</span>
  <span m="64939">writing</span> <span m="65241">files</span> <span m="65543">in</span>
  <span m="65844">the</span> <span m="66146">file</span> <span m="66448">system,</span>
  <span m="66750">the</span> <span m="67151">status</span> <span m="67552">and</span>
  <span m="67953">buffers</span> <span m="68354">associated</span> <span m="68755">with</span>
  <span m="69156">open</span> <span m="69557">network</span> <span m="69958">connections,</span>
  <span m="70360">pending</span> <span m="70746">events</span> <span m="71133">from</span>
  <span m="71520">the</span> <span m="71907">user</span> <span m="72294">interface</span>
  <span m="72681">(e.g.,</span> <span m="73068">keyboard</span> <span m="73455">characters</span>
  <span m="73842">and</span> <span m="74229">mouse</span> <span m="74616">clicks),</span>
  <span m="75003">and</span> <span m="75390">so</span> <span m="76035">on.</span></p><p><span
  m="76680">As</span> <span m="77156">we'll</span> <span m="77632">see,</span> <span
  m="78109">there</span> <span m="78585">is</span> <span m="79062">a</span> <span
  m="79538">special,</span> <span m="80015">privileged</span> <span m="80491">process,</span>
  <span m="80967">called</span> <span m="81444">the</span> <span m="81920">operating</span>
  <span m="82397">system</span> <span m="82873">(OS),</span> <span m="83350">running</span>
  <span m="83868">in</span> <span m="84386">its</span> <span m="84905">own</span>
  <span m="85423">kernel-mode</span> <span m="85941">context.</span></p><p><span m="86460">The</span>
  <span m="86934">OS</span> <span m="87409">manages</span> <span m="87883">all</span>
  <span m="88358">the</span> <span m="88833">bookkeeping</span> <span m="89307">for</span>
  <span m="89782">each</span> <span m="90256">process,</span> <span m="90731">arranging</span>
  <span m="91206">for</span> <span m="91680">the</span> <span m="92155">process</span>
  <span m="92629">run</span> <span m="93104">periodically.</span></p><p><span m="93579">The</span>
  <span m="93935">OS</span> <span m="94292">will</span> <span m="94649">provide</span>
  <span m="95005">various</span> <span m="95362">services</span> <span m="95719">to</span>
  <span m="96075">the</span> <span m="96432">processes,</span> <span m="96789">such</span>
  <span m="97145">as</span> <span m="97502">accessing</span> <span m="97859">data</span>
  <span m="98215">in</span> <span m="98572">files,</span> <span m="98929">establishing</span>
  <span m="99363">network</span> <span m="99798">connections,</span> <span m="100232">managing</span>
  <span m="100667">the</span> <span m="101102">window</span> <span m="101536">system</span>
  <span m="101971">and</span> <span m="102406">user</span> <span m="102840">interface,</span>
  <span m="103275">and</span> <span m="103710">so</span> <span m="104210">on.</span></p><p><span
  m="104710">To</span> <span m="105031">switch</span> <span m="105353">from</span>
  <span m="105675">running</span> <span m="105997">one</span> <span m="106319">user-mode</span>
  <span m="106640">process</span> <span m="106962">to</span> <span m="107284">another,</span>
  <span m="107606">the</span> <span m="107928">OS</span> <span m="108249">will</span>
  <span m="108571">need</span> <span m="108893">to</span> <span m="109215">capture</span>
  <span m="109537">and</span> <span m="109859">save</span> <span m="110369">the</span>
  <span m="110879">*entire*</span> <span m="111389">state</span> <span m="111899">of</span>
  <span m="112409">the</span> <span m="112919">current</span> <span m="113429">user-mode</span>
  <span m="113939">process.</span></p><p><span m="114450">Some</span> <span m="114747">of</span>
  <span m="115045">it</span> <span m="115342">already</span> <span m="115640">lives</span>
  <span m="115938">in</span> <span m="116235">main</span> <span m="116533">memory,</span>
  <span m="116830">so</span> <span m="117128">we're</span> <span m="117426">all</span>
  <span m="117723">set</span> <span m="118021">there.</span></p><p><span m="118319">Some</span>
  <span m="118636">of</span> <span m="118953">it</span> <span m="119271">will</span>
  <span m="119588">be</span> <span m="119905">found</span> <span m="120223">in</span>
  <span m="120540">various</span> <span m="120857">kernel</span> <span m="121175">data</span>
  <span m="121492">structures.</span></p><p><span m="121810">And</span> <span m="122074">some</span>
  <span m="122339">of</span> <span m="122604">it</span> <span m="122869">we'll</span>
  <span m="123134">need</span> <span m="123399">to</span> <span m="123664">be</span>
  <span m="123929">able</span> <span m="124194">to</span> <span m="124459">save</span>
  <span m="124724">and</span> <span m="124989">restore</span> <span m="125254">from</span>
  <span m="125519">the</span> <span m="125784">various</span> <span m="126049">hardware</span>
  <span m="126314">resources</span> <span m="126579">in</span> <span m="127223">the</span>
  <span m="127867">CPU</span> <span m="128511">and</span> <span m="129155">MMU.</span></p><p><span
  m="129800">In</span> <span m="130133">order</span> <span m="130467">to</span> <span
  m="130800">successfully</span> <span m="131134">implement</span> <span m="131467">processes,</span>
  <span m="131801">the</span> <span m="132134">OS</span> <span m="132468">must</span>
  <span m="132801">be</span> <span m="133135">able</span> <span m="133468">to</span>
  <span m="133802">make</span> <span m="134135">it</span> <span m="134469">seem</span>
  <span m="134802">as</span> <span m="135136">if</span> <span m="135470">each</span>
  <span m="135870">process</span> <span m="136271">was</span> <span m="136671">running</span>
  <span m="137072">on</span> <span m="137473">its</span> <span m="137873">own</span>
  <span m="138274">&quot;virtual</span> <span m="138675">machine&quot;</span> <span
  m="139075">that</span> <span m="139476">works</span> <span m="139877">independently</span>
  <span m="140277">of</span> <span m="140678">other</span> <span m="141079">virtual</span>
  <span m="141747">machines</span> <span m="142415">for</span> <span m="143083">other</span>
  <span m="143751">processes.</span></p><p><span m="144420">Our</span> <span m="144862">goal</span>
  <span m="145304">is</span> <span m="145746">to</span> <span m="146188">efficiently</span>
  <span m="146630">share</span> <span m="147072">one</span> <span m="147515">physical</span>
  <span m="147957">machine</span> <span m="148399">between</span> <span m="148841">all</span>
  <span m="149283">the</span> <span m="149725">virtual</span> <span m="150167">machines.</span></p><p><span
  m="150610">Here's</span> <span m="151023">a</span> <span m="151437">sketch</span>
  <span m="151851">of</span> <span m="152265">the</span> <span m="152678">organization</span>
  <span m="153092">we're</span> <span m="153506">proposing.</span></p><p><span m="153920">The</span>
  <span m="154245">resources</span> <span m="154570">provided</span> <span m="154896">by</span>
  <span m="155221">a</span> <span m="155546">physical</span> <span m="155872">machine</span>
  <span m="156197">are</span> <span m="156522">shown</span> <span m="156848">at</span>
  <span m="157173">the</span> <span m="157498">bottom</span> <span m="157824">of</span>
  <span m="158149">the</span> <span m="158474">slide.</span></p><p><span m="158800">The</span>
  <span m="159171">CPU</span> <span m="159542">and</span> <span m="159914">main</span>
  <span m="160285">memory</span> <span m="160657">form</span> <span m="161028">the</span>
  <span m="161400">computation</span> <span m="161771">engine</span> <span m="162142">at</span>
  <span m="162514">heart</span> <span m="162885">of</span> <span m="163257">the</span>
  <span m="163628">system.</span></p><p><span m="164000">Connected</span> <span m="164325">to</span>
  <span m="164650">the</span> <span m="164975">CPU</span> <span m="165300">are</span>
  <span m="165625">various</span> <span m="165950">peripherals,</span> <span m="166275">a</span>
  <span m="166600">collective</span> <span m="166925">noun</span> <span m="167250">coined</span>
  <span m="167575">from</span> <span m="167900">the</span> <span m="168225">English</span>
  <span m="168550">word</span> <span m="169101">&quot;periphery&quot;</span> <span
  m="169652">that</span> <span m="170203">indicates</span> <span m="170754">the</span>
  <span m="171305">resources</span> <span m="171856">surrounding</span> <span m="172407">the</span>
  <span m="172958">CPU.</span></p><p><span m="173510">A</span> <span m="174042">timer</span>
  <span m="174575">generates</span> <span m="175108">periodic</span> <span m="175641">CPU</span>
  <span m="176174">interrupts</span> <span m="176707">that</span> <span m="177240">can</span>
  <span m="177772">be</span> <span m="178305">used</span> <span m="178838">to</span>
  <span m="179371">trigger</span> <span m="179904">periodic</span> <span m="180437">actions.</span></p><p><span
  m="180970">Secondary</span> <span m="181610">storage</span> <span m="182250">provides</span>
  <span m="182890">high-capacity</span> <span m="183530">non-volatile</span> <span
  m="184170">memories</span> <span m="184810">for</span> <span m="185450">the</span>
  <span m="186090">system.</span></p><p><span m="186730">Connections</span> <span
  m="187045">to</span> <span m="187360">the</span> <span m="187675">outside</span>
  <span m="187990">world</span> <span m="188305">are</span> <span m="188620">important</span>
  <span m="188935">too.</span></p><p><span m="189250">Many</span> <span m="189778">computers</span>
  <span m="190307">include</span> <span m="190836">USB</span> <span m="191365">connections</span>
  <span m="191893">for</span> <span m="192422">removable</span> <span m="192951">devices.</span></p><p><span
  m="193480">And</span> <span m="193997">most</span> <span m="194515">provide</span>
  <span m="195032">wired</span> <span m="195550">or</span> <span m="196067">wireless</span>
  <span m="196585">network</span> <span m="197102">connections.</span></p><p><span
  m="197620">And</span> <span m="197914">finally</span> <span m="198209">there</span>
  <span m="198504">are</span> <span m="198798">usually</span> <span m="199093">video</span>
  <span m="199388">monitors,</span> <span m="199683">keyboards</span> <span m="199977">and</span>
  <span m="200272">mice</span> <span m="200567">that</span> <span m="200862">serve</span>
  <span m="201156">as</span> <span m="201451">the</span> <span m="201746">user</span>
  <span m="202041">interface.</span></p><p><span m="203720">Cameras</span> <span m="204205">and</span>
  <span m="204691">microphones</span> <span m="205177">are</span> <span m="205662">becoming</span>
  <span m="206148">increasing</span> <span m="206634">important</span> <span m="207120">as</span>
  <span m="207605">the</span> <span m="208091">next</span> <span m="208577">generation</span>
  <span m="209062">of</span> <span m="209548">user</span> <span m="210034">interface.</span></p><p><span
  m="210520">The</span> <span m="210899">physical</span> <span m="211278">machine</span>
  <span m="211657">is</span> <span m="212036">managed</span> <span m="212416">by</span>
  <span m="212795">the</span> <span m="213174">OS</span> <span m="213553">running</span>
  <span m="213932">in</span> <span m="214312">the</span> <span m="214691">privileged</span>
  <span m="215070">kernel</span> <span m="215449">context.</span></p><p><span m="215829">The</span>
  <span m="216225">OS</span> <span m="216621">handles</span> <span m="217017">the</span>
  <span m="217413">low-level</span> <span m="217810">interfaces</span> <span m="218206">to</span>
  <span m="218602">the</span> <span m="218998">peripherals,</span> <span m="219395">initializes</span>
  <span m="219791">and</span> <span m="220187">manages</span> <span m="220583">the</span>
  <span m="220980">MMU</span> <span m="221430">contexts,</span> <span m="221880">and</span>
  <span m="222330">so</span> <span m="222780">on.</span></p><p><span m="223230">It's</span>
  <span m="223790">the</span> <span m="224351">OS</span> <span m="224912">that</span>
  <span m="225473">creates</span> <span m="226034">the</span> <span m="226595">virtual</span>
  <span m="227155">machine</span> <span m="227716">seen</span> <span m="228277">by</span>
  <span m="228838">each</span> <span m="229399">process.</span></p><p><span m="229960">User-mode</span>
  <span m="230292">programs</span> <span m="230624">run</span> <span m="230956">directly</span>
  <span m="231288">on</span> <span m="231620">the</span> <span m="231952">physical</span>
  <span m="232285">processor,</span> <span m="232617">but</span> <span m="232949">their</span>
  <span m="233281">execution</span> <span m="233613">can</span> <span m="233945">be</span>
  <span m="234277">interrupted</span> <span m="234610">by</span> <span m="234900">the</span>
  <span m="235191">timer,</span> <span m="235482">giving</span> <span m="235773">the</span>
  <span m="236064">OS</span> <span m="236355">the</span> <span m="236646">opportunity</span>
  <span m="236937">to</span> <span m="237228">save</span> <span m="237519">away</span>
  <span m="237810">the</span> <span m="238211">current</span> <span m="238613">process</span>
  <span m="239015">state</span> <span m="239417">and</span> <span m="239819">move</span>
  <span m="240220">to</span> <span m="240622">running</span> <span m="241024">the</span>
  <span m="241426">next</span> <span m="241828">process.</span></p><p><span m="242230">Via</span>
  <span m="242677">the</span> <span m="243125">MMU,</span> <span m="243573">the</span>
  <span m="244021">OS</span> <span m="244469">provides</span> <span m="244917">each</span>
  <span m="245365">process</span> <span m="245812">with</span> <span m="246260">an</span>
  <span m="246708">independent</span> <span m="247156">virtual</span> <span m="247604">address</span>
  <span m="248052">space</span> <span m="248500">that's</span> <span m="248942">isolated</span>
  <span m="249385">from</span> <span m="249827">the</span> <span m="250270">actions</span>
  <span m="250712">of</span> <span m="251155">other</span> <span m="251597">processes.</span></p><p><span
  m="252040">The</span> <span m="252354">virtual</span> <span m="252669">peripherals</span>
  <span m="252984">provided</span> <span m="253298">by</span> <span m="253613">the</span>
  <span m="253928">OS</span> <span m="254242">isolate</span> <span m="254557">the</span>
  <span m="254872">process</span> <span m="255186">from</span> <span m="255501">all</span>
  <span m="255816">the</span> <span m="256130">details</span> <span m="256445">of</span>
  <span m="256760">sharing</span> <span m="257416">resources</span> <span m="258072">with</span>
  <span m="258728">other</span> <span m="259384">processes.</span></p><p><span m="260040">The</span>
  <span m="260365">notion</span> <span m="260691">of</span> <span m="261016">a</span>
  <span m="261342">window</span> <span m="261668">allows</span> <span m="261993">the</span>
  <span m="262319">process</span> <span m="262645">to</span> <span m="262970">access</span>
  <span m="263296">a</span> <span m="263621">rectangular</span> <span m="263947">array</span>
  <span m="264273">of</span> <span m="264598">pixels</span> <span m="264924">without</span>
  <span m="265250">having</span> <span m="265560">to</span> <span m="265871">worry</span>
  <span m="266182">if</span> <span m="266492">some</span> <span m="266803">pixels</span>
  <span m="267114">in</span> <span m="267425">the</span> <span m="267735">window</span>
  <span m="268046">are</span> <span m="268357">hidden</span> <span m="268667">by</span>
  <span m="268978">other</span> <span m="269289">windows.</span></p><p><span m="269600">Or</span>
  <span m="269841">worrying</span> <span m="270082">about</span> <span m="270323">how</span>
  <span m="270565">to</span> <span m="270806">ensure</span> <span m="271047">the</span>
  <span m="271288">mouse</span> <span m="271530">cursor</span> <span m="271771">always</span>
  <span m="272012">appears</span> <span m="272253">on</span> <span m="272495">top</span>
  <span m="272736">of</span> <span m="272977">whatever</span> <span m="273218">is</span>
  <span m="273460">being</span> <span m="274114">displayed,</span> <span m="274768">and</span>
  <span m="275422">so</span> <span m="276076">on.</span></p><p><span m="276730">Instead</span>
  <span m="277113">of</span> <span m="277496">accessing</span> <span m="277880">I/O</span>
  <span m="278263">devices</span> <span m="278646">directly,</span> <span m="279030">each</span>
  <span m="279413">process</span> <span m="279796">has</span> <span m="280180">access</span>
  <span m="280563">to</span> <span m="280946">a</span> <span m="281330">stream</span>
  <span m="281713">of</span> <span m="282096">I/O</span> <span m="282480">events</span>
  <span m="282829">that</span> <span m="283178">are</span> <span m="283527">generated</span>
  <span m="283877">when</span> <span m="284226">a</span> <span m="284575">character</span>
  <span m="284925">is</span> <span m="285274">typed,</span> <span m="285623">the</span>
  <span m="285972">mouse</span> <span m="286322">is</span> <span m="286671">clicked,</span>
  <span m="287020">etc.</span></p><p><span m="287370">For</span> <span m="287721">example,</span>
  <span m="288073">the</span> <span m="288425">OS</span> <span m="288777">deals</span>
  <span m="289129">with</span> <span m="289481">how</span> <span m="289833">to</span>
  <span m="290185">determine</span> <span m="290536">which</span> <span m="290888">typed</span>
  <span m="291240">characters</span> <span m="291592">belong</span> <span m="291944">to</span>
  <span m="292296">which</span> <span m="292648">process.</span></p><p><span m="293000">In</span>
  <span m="293296">most</span> <span m="293592">window</span> <span m="293888">systems,</span>
  <span m="294185">the</span> <span m="294481">user</span> <span m="294777">clicks</span>
  <span m="295073">on</span> <span m="295370">a</span> <span m="295666">window</span>
  <span m="295962">to</span> <span m="296258">indicate</span> <span m="296555">that</span>
  <span m="296851">the</span> <span m="297147">process</span> <span m="297443">that</span>
  <span m="297740">owns</span> <span m="298174">the</span> <span m="298609">window</span>
  <span m="299044">now</span> <span m="299478">has</span> <span m="299913">the</span>
  <span m="300348">keyboard</span> <span m="300782">focus</span> <span m="301217">and</span>
  <span m="301652">should</span> <span m="302086">receive</span> <span m="302521">any</span>
  <span m="302956">subsequent</span> <span m="303390">typed</span> <span m="303825">characters.</span></p><p><span
  m="304260">And</span> <span m="304554">the</span> <span m="304848">position</span>
  <span m="305142">of</span> <span m="305437">the</span> <span m="305731">mouse</span>
  <span m="306025">when</span> <span m="306320">clicked</span> <span m="306614">might</span>
  <span m="306908">determine</span> <span m="307202">which</span> <span m="307497">process</span>
  <span m="307791">receives</span> <span m="308085">the</span> <span m="308380">click.</span></p><p><span
  m="309710">All</span> <span m="309958">of</span> <span m="310207">which</span> <span
  m="310456">is</span> <span m="310705">to</span> <span m="310954">say</span> <span
  m="311203">that</span> <span m="311452">the</span> <span m="311701">details</span>
  <span m="311950">of</span> <span m="312198">sharing</span> <span m="312447">have</span>
  <span m="312696">been</span> <span m="312945">abstracted</span> <span m="313194">out</span>
  <span m="313443">of</span> <span m="313692">the</span> <span m="313941">simple</span>
  <span m="314190">interface</span> <span m="314898">provided</span> <span m="315606">by</span>
  <span m="316315">the</span> <span m="317023">virtual</span> <span m="317731">peripherals.</span></p><p><span
  m="318440">The</span> <span m="318822">same</span> <span m="319204">is</span> <span
  m="319586">true</span> <span m="319968">of</span> <span m="320351">accessing</span>
  <span m="320733">files</span> <span m="321115">on</span> <span m="321497">disk.</span></p><p><span
  m="321880">The</span> <span m="322226">OS</span> <span m="322572">provides</span>
  <span m="322918">the</span> <span m="323264">useful</span> <span m="323610">abstraction</span>
  <span m="323956">of</span> <span m="324302">having</span> <span m="324648">each</span>
  <span m="324994">file</span> <span m="325340">appear</span> <span m="325686">as</span>
  <span m="326032">a</span> <span m="326378">contiguous,</span> <span m="326724">growable</span>
  <span m="327070">array</span> <span m="327563">of</span> <span m="328056">bytes</span>
  <span m="328550">that</span> <span m="329043">supports</span> <span m="329536">read</span>
  <span m="330030">and</span> <span m="330523">write</span> <span m="331016">operations.</span></p><p><span
  m="331510">The</span> <span m="331768">OS</span> <span m="332026">knows</span> <span
  m="332284">how</span> <span m="332542">the</span> <span m="332800">file</span> <span
  m="333058">is</span> <span m="333316">mapped</span> <span m="333574">to</span> <span
  m="333832">a</span> <span m="334090">pool</span> <span m="334348">of</span> <span
  m="334606">sectors</span> <span m="334864">on</span> <span m="335122">the</span>
  <span m="335380">disk</span> <span m="335638">and</span> <span m="335896">deals</span>
  <span m="336154">with</span> <span m="336412">bad</span> <span m="336670">sectors,</span>
  <span m="337121">reducing</span> <span m="337573">fragmentation,</span> <span m="338025">and</span>
  <span m="338476">improving</span> <span m="338928">throughput</span> <span m="339380">by</span>
  <span m="339831">doing</span> <span m="340283">read</span> <span m="340735">look-aheads</span>
  <span m="341186">and</span> <span m="341638">write</span> <span m="342090">behinds.</span></p><p><span
  m="344150">For</span> <span m="344490">networks,</span> <span m="344830">the</span>
  <span m="345170">OS</span> <span m="345510">provides</span> <span m="345850">access</span>
  <span m="346190">to</span> <span m="346530">an</span> <span m="346870">in-order</span>
  <span m="347210">stream</span> <span m="347550">of</span> <span m="347890">bytes</span>
  <span m="348230">to</span> <span m="348570">some</span> <span m="348910">remote</span>
  <span m="349250">socket.</span></p><p><span m="349590">It</span> <span m="350103">implements</span>
  <span m="350616">the</span> <span m="351130">appropriate</span> <span m="351643">network</span>
  <span m="352156">protocols</span> <span m="352670">for</span> <span m="353183">packetizing</span>
  <span m="353696">the</span> <span m="354210">stream,</span> <span m="354723">addressing</span>
  <span m="355236">the</span> <span m="355750">packets,</span> <span m="356197">and</span>
  <span m="356645">dealing</span> <span m="357093">with</span> <span m="357541">dropped,</span>
  <span m="357988">damaged,</span> <span m="358436">or</span> <span m="358884">out-of-order</span>
  <span m="359332">packets.</span></p><p><span m="359780">To</span> <span m="360167">configure</span>
  <span m="360555">and</span> <span m="360943">control</span> <span m="361331">these</span>
  <span m="361719">virtual</span> <span m="362107">services,</span> <span m="362495">the</span>
  <span m="362882">process</span> <span m="363270">communicates</span> <span m="363658">with</span>
  <span m="364046">the</span> <span m="364434">OS</span> <span m="364822">using</span>
  <span m="365210">supervisor</span> <span m="365712">calls</span> <span m="366215">(SVCs),</span>
  <span m="366718">a</span> <span m="367220">type</span> <span m="367723">of</span>
  <span m="368226">controlled-access</span> <span m="368728">procedure</span> <span
  m="369231">call</span> <span m="369734">that</span> <span m="370236">invokes</span>
  <span m="370739">code</span> <span m="371242">in</span> <span m="371744">the</span>
  <span m="372247">OS</span> <span m="372750">kernel.</span></p><p><span m="373750">The</span>
  <span m="374032">details</span> <span m="374314">of</span> <span m="374596">the</span>
  <span m="374878">design</span> <span m="375160">and</span> <span m="375442">implementation</span>
  <span m="375724">of</span> <span m="376006">each</span> <span m="376288">virtual</span>
  <span m="376570">service</span> <span m="376852">are</span> <span m="377134">beyond</span>
  <span m="377416">the</span> <span m="377698">scope</span> <span m="377980">of</span>
  <span m="378453">this</span> <span m="378926">course.</span></p><p><span m="379400">If</span>
  <span m="379672">you're</span> <span m="379944">interested,</span> <span m="380216">a</span>
  <span m="380488">course</span> <span m="380760">on</span> <span m="381032">operating</span>
  <span m="381305">systems</span> <span m="381577">will</span> <span m="381849">explore</span>
  <span m="382121">each</span> <span m="382393">of</span> <span m="382665">these</span>
  <span m="382937">topics</span> <span m="383210">in</span> <span m="384595">detail.</span></p><p><span
  m="385980">The</span> <span m="386389">OS</span> <span m="386798">provides</span>
  <span m="387207">an</span> <span m="387616">independent</span> <span m="388026">virtual</span>
  <span m="388435">machine</span> <span m="388844">for</span> <span m="389253">each</span>
  <span m="389663">process,</span> <span m="390072">periodically</span> <span m="390481">switching</span>
  <span m="390890">from</span> <span m="391300">running</span> <span m="391814">one</span>
  <span m="392329">process</span> <span m="392844">to</span> <span m="393359">running</span>
  <span m="393874">the</span> <span m="394389">next</span> <span m="394904">process.</span></p><p><span
  m="395419">Let's</span> <span m="395761">follow</span> <span m="396103">along</span>
  <span m="396445">as</span> <span m="396787">we</span> <span m="397130">switch</span>
  <span m="397472">from</span> <span m="397814">running</span> <span m="398156">process</span>
  <span m="398498">#0</span> <span m="398841">to</span> <span m="399183">running</span>
  <span m="399525">process</span> <span m="399867">#1.</span></p><p><span m="400210">Initially,</span>
  <span m="400804">the</span> <span m="401398">CPU</span> <span m="401992">is</span>
  <span m="402586">executing</span> <span m="403180">user-mode</span> <span m="403774">code</span>
  <span m="404368">in</span> <span m="404962">process</span> <span m="405556">#0.</span></p><p><span
  m="406150">That</span> <span m="406495">execution</span> <span m="406840">is</span>
  <span m="407186">interrupted,</span> <span m="407531">either</span> <span m="407876">by</span>
  <span m="408222">an</span> <span m="408567">explicit</span> <span m="408912">yield</span>
  <span m="409258">by</span> <span m="409603">the</span> <span m="409948">program,</span>
  <span m="410294">or,</span> <span m="410639">more</span> <span m="410984">likely,</span>
  <span m="411330">by</span> <span m="411902">a</span> <span m="412475">timer</span>
  <span m="413047">interrupt.</span></p><p><span m="413620">Either</span> <span m="413937">ends</span>
  <span m="414254">up</span> <span m="414571">transferring</span> <span m="414888">control</span>
  <span m="415205">to</span> <span m="415522">OS</span> <span m="415840">code</span>
  <span m="416157">running</span> <span m="416474">in</span> <span m="416791">kernel</span>
  <span m="417108">mode,</span> <span m="417425">while</span> <span m="417742">saving</span>
  <span m="418060">the</span> <span m="418462">current</span> <span m="418865">PC+4</span>
  <span m="419267">value</span> <span m="419670">in</span> <span m="420072">the</span>
  <span m="420475">XP</span> <span m="420877">register.</span></p><p><span m="421280">We'll</span>
  <span m="421635">talk</span> <span m="421990">about</span> <span m="422346">the</span>
  <span m="422701">interrupt</span> <span m="423056">mechanism</span> <span m="423412">in</span>
  <span m="423767">more</span> <span m="424123">detail</span> <span m="424478">in</span>
  <span m="424833">just</span> <span m="425189">a</span> <span m="425544">moment.</span></p><p><span
  m="425900">The</span> <span m="426248">OS</span> <span m="426596">saves</span> <span
  m="426944">the</span> <span m="427292">state</span> <span m="427640">of</span> <span
  m="427988">process</span> <span m="428336">#0</span> <span m="428684">in</span>
  <span m="429032">the</span> <span m="429380">appropriate</span> <span m="429728">table</span>
  <span m="430076">in</span> <span m="430424">kernel</span> <span m="430772">storage.</span></p><p><span
  m="431120">Then</span> <span m="431497">it</span> <span m="431875">reloads</span>
  <span m="432252">the</span> <span m="432630">state</span> <span m="433007">from</span>
  <span m="433385">the</span> <span m="433762">kernel</span> <span m="434140">table</span>
  <span m="434517">for</span> <span m="434895">process</span> <span m="435272">#1.</span></p><p><span
  m="435650">Note</span> <span m="435942">that</span> <span m="436235">the</span>
  <span m="436527">process</span> <span m="436820">#1</span> <span m="437112">state</span>
  <span m="437405">was</span> <span m="437697">saved</span> <span m="437990">when</span>
  <span m="438282">process</span> <span m="438575">#1</span> <span m="438867">was</span>
  <span m="439160">interrupted</span> <span m="439452">at</span> <span m="439745">some</span>
  <span m="440037">earlier</span> <span m="440330">point.</span></p><p><span m="441330">The</span>
  <span m="441661">OS</span> <span m="441992">then</span> <span m="442324">uses</span>
  <span m="442655">a</span> <span m="442986">JMP()</span> <span m="443318">to</span>
  <span m="443649">resume</span> <span m="443980">user-mode</span> <span m="444312">execution</span>
  <span m="444643">using</span> <span m="444974">the</span> <span m="445306">newly</span>
  <span m="445637">restored</span> <span m="445968">process</span> <span m="446300">#1</span>
  <span m="447520">state.</span></p><p><span m="448740">Execution</span> <span m="449182">resumes</span>
  <span m="449625">in</span> <span m="450067">process</span> <span m="450510">#1</span>
  <span m="450952">just</span> <span m="451395">where</span> <span m="451837">it</span>
  <span m="452280">was</span> <span m="452722">when</span> <span m="453165">interrupted</span>
  <span m="453607">earlier.</span></p><p><span m="454050">And</span> <span m="454516">now</span>
  <span m="454982">we're</span> <span m="455448">running</span> <span m="455914">the</span>
  <span m="456380">user-mode</span> <span m="456846">program</span> <span m="457312">in</span>
  <span m="457778">process</span> <span m="458244">#1.</span></p><p><span m="458710">We've</span>
  <span m="459222">interrupted</span> <span m="459734">one</span> <span m="460246">process</span>
  <span m="460758">and</span> <span m="461271">resumed</span> <span m="461783">execution</span>
  <span m="462295">of</span> <span m="462807">another.</span></p><p><span m="463320">We'll</span>
  <span m="463605">keep</span> <span m="463891">doing</span> <span m="464176">this</span>
  <span m="464462">in</span> <span m="464748">a</span> <span m="465033">round-robin</span>
  <span m="465319">fashion,</span> <span m="465605">giving</span> <span m="465890">each</span>
  <span m="466176">process</span> <span m="466461">a</span> <span m="466747">chance</span>
  <span m="467033">to</span> <span m="467318">run,</span> <span m="467604">before</span>
  <span m="467890">starting</span> <span m="468564">another</span> <span m="469238">round</span>
  <span m="469912">of</span> <span m="470586">execution.</span></p><p><span m="471260">The</span>
  <span m="471616">black</span> <span m="471972">arrows</span> <span m="472328">give</span>
  <span m="472684">a</span> <span m="473040">sense</span> <span m="473396">for</span>
  <span m="473752">how</span> <span m="474108">time</span> <span m="474464">proceeds.</span></p><p><span
  m="474820">For</span> <span m="475350">each</span> <span m="475881">process,</span>
  <span m="476412">virtual</span> <span m="476943">time</span> <span m="477474">unfolds</span>
  <span m="478005">as</span> <span m="478535">a</span> <span m="479066">sequence</span>
  <span m="479597">of</span> <span m="480128">executed</span> <span m="480659">instructions.</span></p><p><span
  m="481190">Unless</span> <span m="481521">it</span> <span m="481852">looks</span>
  <span m="482184">at</span> <span m="482515">a</span> <span m="482846">real-time</span>
  <span m="483178">clock,</span> <span m="483509">a</span> <span m="483840">process</span>
  <span m="484172">is</span> <span m="484503">unaware</span> <span m="484834">that</span>
  <span m="485166">occasionally</span> <span m="485497">its</span> <span m="485828">execution</span>
  <span m="486160">is</span> <span m="486618">suspended</span> <span m="487076">for</span>
  <span m="487534">a</span> <span m="487992">while.</span></p><p><span m="488450">The</span>
  <span m="488965">suspension</span> <span m="489480">and</span> <span m="489996">resumption</span>
  <span m="490511">are</span> <span m="491027">completely</span> <span m="491542">transparent</span>
  <span m="492058">to</span> <span m="492573">a</span> <span m="493089">running</span>
  <span m="493604">process.</span></p><p><span m="494120">Of</span> <span m="494384">course,</span>
  <span m="494649">from</span> <span m="494914">the</span> <span m="495178">outside</span>
  <span m="495443">we</span> <span m="495708">can</span> <span m="495972">see</span>
  <span m="496237">that</span> <span m="496502">in</span> <span m="496767">real</span>
  <span m="497031">time,</span> <span m="497296">the</span> <span m="497561">execution</span>
  <span m="497825">path</span> <span m="498090">moves</span> <span m="498355">from</span>
  <span m="498620">process</span> <span m="499133">to</span> <span m="499646">process,</span>
  <span m="500160">visiting</span> <span m="500673">the</span> <span m="501186">OS</span>
  <span m="501700">during</span> <span m="502213">switches,</span> <span m="502726">producing</span>
  <span m="503240">the</span> <span m="503753">dove-tailed</span> <span m="504266">execution</span>
  <span m="504780">path</span> <span m="505527">we</span> <span m="506275">see</span>
  <span m="507022">here.</span></p><p><span m="507770">Time-multiplexing</span> <span
  m="508159">of</span> <span m="508548">the</span> <span m="508937">CPU</span> <span
  m="509326">is</span> <span m="509716">called</span> <span m="510105">&quot;timesharing&quot;</span>
  <span m="510494">and</span> <span m="510883">we'll</span> <span m="511272">examine</span>
  <span m="511662">the</span> <span m="512051">implementation</span> <span m="512440">in</span>
  <span m="512829">more</span> <span m="513219">detail</span> <span m="513592">in</span>
  <span m="513966">the</span> <span m="514340">following</span> <span m="514714">segment.</span></p>
type: course
uid: 1ff29cb41ca307b7bce1a59a0554d12a

---
None