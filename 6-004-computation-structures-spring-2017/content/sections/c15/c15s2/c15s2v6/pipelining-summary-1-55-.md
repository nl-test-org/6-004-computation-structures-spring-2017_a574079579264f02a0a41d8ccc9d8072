---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: p2j16ebu14U
  parent_uid: 2c06234aa0ad7845efbeb17d7de1f891
  title: Video-YouTube-Stream
  type: Video
  uid: 44cc24f892c12653ffc96144b87bdae3
- id: 3Play-3Play YouTube id-Stream
  media_location: p2j16ebu14U
  parent_uid: 2c06234aa0ad7845efbeb17d7de1f891
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: ae773bbaaaeaaebb2741d12e7ded070d
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/p2j16ebu14U/default.jpg
  parent_uid: 2c06234aa0ad7845efbeb17d7de1f891
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 3f2b9d319c4298836812f036039119dc
- id: p2j16ebu14U.srt
  parent_uid: 2c06234aa0ad7845efbeb17d7de1f891
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v6/pipelining-summary-1-55-/p2j16ebu14U.srt
  title: 3play caption file
  type: null
  uid: e323081f1bbc3971a27763892747a17d
- id: p2j16ebu14U.pdf
  parent_uid: 2c06234aa0ad7845efbeb17d7de1f891
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v6/pipelining-summary-1-55-/p2j16ebu14U.pdf
  title: 3play pdf file
  type: null
  uid: 1c4cd212568b50e5fd6e8717793222e0
- id: Caption-3Play YouTube id-SRT
  parent_uid: 2c06234aa0ad7845efbeb17d7de1f891
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 6dabc2414a3b231b9e8c628c13aefea8
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 2c06234aa0ad7845efbeb17d7de1f891
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: caee4b8c627714e83460a324aa69855b
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_15-02-06_300k.mp4
  parent_uid: 2c06234aa0ad7845efbeb17d7de1f891
  title: Video-Internet Archive-MP4
  type: Video
  uid: 6c5d6be26c132f4b3f322003c6935ae3
inline_embed_id: 8285571pipeliningsummary15537546842
layout: video
order_index: null
parent_uid: 5e366805ad59e88b29648211132a1a9c
related_resources_text: ''
short_url: pipelining-summary-1-55-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c15/c15s2/c15s2v6/pipelining-summary-1-55-
template_type: Embed
title: Pipelining Summary
transcript: <p><span m="1240">So</span> <span m="1680">here's</span> <span m="2121">the</span>
  <span m="2562">final</span> <span m="3003">version</span> <span m="3444">of</span>
  <span m="3885">our</span> <span m="4326">5-stage</span> <span m="4767">pipelined</span>
  <span m="5208">data</span> <span m="5649">path.</span></p><p><span m="6090">To</span>
  <span m="6449">deal</span> <span m="6808">with</span> <span m="7168">data</span>
  <span m="7527">hazards</span> <span m="7886">we've</span> <span m="8246">added</span>
  <span m="8605">stall</span> <span m="8965">logic</span> <span m="9324">to</span>
  <span m="9683">the</span> <span m="10043">IF</span> <span m="10402">and</span> <span
  m="10761">RF</span> <span m="11121">input</span> <span m="11480">registers.</span></p><p><span
  m="11840">We've</span> <span m="12120">also</span> <span m="12401">added</span>
  <span m="12681">bypass</span> <span m="12962">muxes</span> <span m="13242">on</span>
  <span m="13523">the</span> <span m="13804">output</span> <span m="14084">of</span>
  <span m="14365">the</span> <span m="14645">register</span> <span m="14926">file</span>
  <span m="15207">read</span> <span m="15487">ports</span> <span m="15768">so</span>
  <span m="16048">we</span> <span m="16329">can</span> <span m="16610">route</span>
  <span m="16882">values</span> <span m="17155">from</span> <span m="17428">later</span>
  <span m="17701">in</span> <span m="17974">the</span> <span m="18247">data</span>
  <span m="18520">path</span> <span m="18793">if</span> <span m="19066">we</span>
  <span m="19339">need</span> <span m="19612">to</span> <span m="19885">access</span>
  <span m="20158">a</span> <span m="20431">register</span> <span m="20704">value</span>
  <span m="20977">that's</span> <span m="21250">been</span> <span m="21635">computed</span>
  <span m="22021">but</span> <span m="22407">not</span> <span m="22793">yet</span>
  <span m="23179">written</span> <span m="23565">to</span> <span m="23951">the</span>
  <span m="24337">register</span> <span m="24723">file.</span></p><p><span m="25109">We</span>
  <span m="25409">also</span> <span m="25710">made</span> <span m="26010">a</span>
  <span m="26311">provision</span> <span m="26611">to</span> <span m="26912">insert</span>
  <span m="27212">NOPs</span> <span m="27513">into</span> <span m="27814">the</span>
  <span m="28114">pipeline</span> <span m="28415">after</span> <span m="28715">the</span>
  <span m="29016">RF</span> <span m="29316">stage</span> <span m="29617">if</span>
  <span m="29917">the</span> <span m="30218">IF</span> <span m="30519">and</span>
  <span m="31177">RF</span> <span m="31835">stages</span> <span m="32493">are</span>
  <span m="33151">stalled.</span></p><p><span m="33810">To</span> <span m="34255">deal</span>
  <span m="34700">with</span> <span m="35145">control</span> <span m="35590">hazards,</span>
  <span m="36035">we</span> <span m="36480">speculate</span> <span m="36925">that</span>
  <span m="37370">the</span> <span m="37815">next</span> <span m="38260">instruction</span>
  <span m="38705">is</span> <span m="39150">at</span> <span m="39595">PC+4.</span></p><p><span
  m="40040">But</span> <span m="40351">for</span> <span m="40662">JMPs</span> <span
  m="40973">and</span> <span m="41284">taken</span> <span m="41595">branches,</span>
  <span m="41907">that</span> <span m="42218">guess</span> <span m="42529">is</span>
  <span m="42840">wrong</span> <span m="43151">so</span> <span m="43462">we</span>
  <span m="43774">added</span> <span m="44085">a</span> <span m="44396">provision</span>
  <span m="44707">for</span> <span m="45018">annulling</span> <span m="45330">the</span>
  <span m="45920">instruction</span> <span m="46510">in</span> <span m="47100">the</span>
  <span m="47690">IF</span> <span m="48280">stage.</span></p><p><span m="48870">To</span>
  <span m="49201">deal</span> <span m="49532">with</span> <span m="49864">exceptions</span>
  <span m="50195">and</span> <span m="50526">interrupts</span> <span m="50858">we</span>
  <span m="51189">added</span> <span m="51520">instruction</span> <span m="51852">muxes</span>
  <span m="52183">in</span> <span m="52514">all</span> <span m="52846">but</span>
  <span m="53177">the</span> <span m="53508">final</span> <span m="53840">pipeline</span>
  <span m="54695">stage.</span></p><p><span m="55550">An</span> <span m="55914">instruction</span>
  <span m="56278">that</span> <span m="56642">causes</span> <span m="57006">an</span>
  <span m="57370">exception</span> <span m="57734">is</span> <span m="58098">replaced</span>
  <span m="58462">by</span> <span m="58826">our</span> <span m="59190">magic</span>
  <span m="59554">BNE</span> <span m="59918">instruction</span> <span m="60282">to</span>
  <span m="60646">capture</span> <span m="61010">its</span> <span m="61683">PC+4</span>
  <span m="62356">value.</span></p><p><span m="63030">And</span> <span m="63348">instructions</span>
  <span m="63667">in</span> <span m="63985">earlier</span> <span m="64304">stages</span>
  <span m="64622">are</span> <span m="64941">annulled.</span></p><p><span m="65260">All</span>
  <span m="65719">this</span> <span m="66178">extra</span> <span m="66637">circuitry</span>
  <span m="67096">has</span> <span m="67556">been</span> <span m="68015">added</span>
  <span m="68474">to</span> <span m="68933">ensure</span> <span m="69392">that</span>
  <span m="69852">pipelined</span> <span m="70311">execution</span> <span m="70770">gives</span>
  <span m="71229">the</span> <span m="71689">same</span> <span m="72415">result</span>
  <span m="73141">as</span> <span m="73867">unpipelined</span> <span m="74593">execution.</span></p><p><span
  m="75320">The</span> <span m="75648">use</span> <span m="75977">of</span> <span
  m="76305">bypassing</span> <span m="76634">and</span> <span m="76962">branch</span>
  <span m="77291">prediction</span> <span m="77620">ensures</span> <span m="77948">that</span>
  <span m="78277">data</span> <span m="78605">and</span> <span m="78934">control</span>
  <span m="79262">hazards</span> <span m="79591">have</span> <span m="79920">only</span>
  <span m="80383">a</span> <span m="80846">small</span> <span m="81310">negative</span>
  <span m="81773">impact</span> <span m="82236">on</span> <span m="82700">the</span>
  <span m="83163">effective</span> <span m="83626">CPI.</span></p><p><span m="84090">This</span>
  <span m="84398">means</span> <span m="84706">that</span> <span m="85014">the</span>
  <span m="85322">much</span> <span m="85630">shorter</span> <span m="85938">clock</span>
  <span m="86246">period</span> <span m="86554">translates</span> <span m="86862">to</span>
  <span m="87170">a</span> <span m="87478">large</span> <span m="87786">increase</span>
  <span m="88094">in</span> <span m="88402">instruction</span> <span m="88710">throughput.</span></p><p><span
  m="89710">It's</span> <span m="90100">worth</span> <span m="90490">remembering</span>
  <span m="90880">the</span> <span m="91270">strategies</span> <span m="91660">we</span>
  <span m="92050">used</span> <span m="92440">to</span> <span m="92830">deal</span>
  <span m="93220">with</span> <span m="93610">hazards:</span> <span m="94000">stalling,</span>
  <span m="94390">bypassing</span> <span m="94780">and</span> <span m="95764">speculation.</span></p><p><span
  m="96749">Most</span> <span m="97034">execution</span> <span m="97319">issues</span>
  <span m="97604">can</span> <span m="97889">be</span> <span m="98174">dealt</span>
  <span m="98459">with</span> <span m="98744">using</span> <span m="99029">one</span>
  <span m="99314">of</span> <span m="99599">these</span> <span m="99884">strategies,</span>
  <span m="100169">so</span> <span m="100454">keep</span> <span m="100739">these</span>
  <span m="101024">in</span> <span m="101310">mind</span> <span m="101779">if</span>
  <span m="102249">you</span> <span m="102719">ever</span> <span m="103189">need</span>
  <span m="103659">to</span> <span m="104129">design</span> <span m="104599">a</span>
  <span m="105069">high-performance</span> <span m="105539">pipelined</span> <span
  m="106009">system.</span></p><p><span m="106479">This</span> <span m="106915">completes</span>
  <span m="107352">our</span> <span m="107789">discussion</span> <span m="108226">of</span>
  <span m="108663">pipelining.</span></p><p><span m="109100">We'll</span> <span m="109454">explore</span>
  <span m="109808">other</span> <span m="110162">avenues</span> <span m="110517">to</span>
  <span m="110871">higher</span> <span m="111225">processor</span> <span m="111580">performance</span>
  <span m="111934">in</span> <span m="112288">the</span> <span m="112642">last</span>
  <span m="112997">lecture,</span> <span m="113351">which</span> <span m="113705">discusses</span>
  <span m="114060">parallel</span> <span m="114619">processing.</span></p>
type: course
uid: 2c06234aa0ad7845efbeb17d7de1f891

---
None