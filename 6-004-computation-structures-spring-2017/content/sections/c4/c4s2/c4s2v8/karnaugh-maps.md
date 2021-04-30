---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: tjIFsdM-hBA
  parent_uid: c17d321f88380bc671a53ccf8011fe5d
  title: Video-YouTube-Stream
  type: Video
  uid: 103cc69eeb99df87d9c38fdeaa56e72a
- id: 3Play-3Play YouTube id-Stream
  media_location: tjIFsdM-hBA
  parent_uid: c17d321f88380bc671a53ccf8011fe5d
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: a359773b41baed275b62133a862ac00f
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/tjIFsdM-hBA/default.jpg
  parent_uid: c17d321f88380bc671a53ccf8011fe5d
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: a987b6efae39b3e7df687a6575dba744
- id: tjIFsdM-hBA.srt
  parent_uid: c17d321f88380bc671a53ccf8011fe5d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c4/c4s2/c4s2v8/karnaugh-maps/tjIFsdM-hBA.srt
  title: 3play caption file
  type: null
  uid: bf08a97c59a39fe8da79839104df9446
- id: tjIFsdM-hBA.pdf
  parent_uid: c17d321f88380bc671a53ccf8011fe5d
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c4/c4s2/c4s2v8/karnaugh-maps/tjIFsdM-hBA.pdf
  title: 3play pdf file
  type: null
  uid: 5a0badac5e9b7a23d3ea8141e9d8379c
- id: Caption-3Play YouTube id-SRT
  parent_uid: c17d321f88380bc671a53ccf8011fe5d
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 6e287844ea0fbba2fe82ada3510f4b24
- id: Transcript-3Play YouTube id-PDF
  parent_uid: c17d321f88380bc671a53ccf8011fe5d
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: b44f02c2c9588f0755edbd7818d70dd4
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_04-02-08-04_300k.mp4
  parent_uid: c17d321f88380bc671a53ccf8011fe5d
  title: Video-Internet Archive-MP4
  type: Video
  uid: 00227edc483ae5fbf901dbd321b45d7c
inline_embed_id: 13006822karnaughmaps33420173
layout: video
order_index: null
parent_uid: 8f2c6bc38a024382dbe3d1ddde84d0f6
related_resources_text: ''
short_url: karnaugh-maps
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c4/c4s2/c4s2v8/karnaugh-maps
template_type: Embed
title: 'Worked Example: Karnaugh Maps'
transcript: <p><span m="1069">Boolean</span> <span m="1510">logic</span> <span m="1952">can</span>
  <span m="2393">be</span> <span m="2835">used</span> <span m="3276">to</span> <span
  m="3718">simplify</span> <span m="4159">logic</span> <span m="4601">equations</span>
  <span m="5042">into</span> <span m="5484">their</span> <span m="5925">simplest</span>
  <span m="6367">form.</span></p><p><span m="6809">This</span> <span m="7257">simplest</span>
  <span m="7705">form</span> <span m="8154">is</span> <span m="8602">known</span>
  <span m="9051">as</span> <span m="9499">the</span> <span m="9948">function's</span>
  <span m="10396">minimal</span> <span m="10845">sum</span> <span m="11293">of</span>
  <span m="11742">products</span> <span m="12190">representation.</span></p><p><span
  m="12639">Having</span> <span m="12976">a</span> <span m="13314">simplified</span>
  <span m="13652">equation</span> <span m="13990">allows</span> <span m="14328">us</span>
  <span m="14666">to</span> <span m="15004">implement</span> <span m="15341">the</span>
  <span m="15679">function</span> <span m="16017">using</span> <span m="16355">the</span>
  <span m="16693">fewest</span> <span m="17031">number</span> <span m="17369">of</span>
  <span m="17799">gates.</span> <span m="18229">One</span> <span m="18659">commonly</span>
  <span m="19089">used</span> <span m="19519">method</span> <span m="19949">for</span>
  <span m="20379">taking</span> <span m="20809">any</span> <span m="21239">boolean</span>
  <span m="21670">expression</span> <span m="22085">and</span> <span m="22500">converting</span>
  <span m="22915">it</span> <span m="23330">to</span> <span m="23745">its</span> <span
  m="24160">minimal</span> <span m="24575">sum-of-products</span> <span m="24990">equivalent</span>
  <span m="25405">is</span> <span m="25820">the</span> <span m="26235">use</span>
  <span m="26650">of</span> <span m="27065">Karnaugh</span> <span m="27480">maps.</span>
  <span m="27934">The</span> <span m="28388">way</span> <span m="28843">Karnaugh</span>
  <span m="29297">maps</span> <span m="29752">work</span> <span m="30206">is</span>
  <span m="30661">as</span> <span m="31115">follows.</span></p><p><span m="31570">You</span>
  <span m="31963">start</span> <span m="32357">with</span> <span m="32750">the</span>
  <span m="33144">original</span> <span m="33537">truth</span> <span m="33931">table</span>
  <span m="34324">specification</span> <span m="34718">of</span> <span m="35111">a</span>
  <span m="35505">function.</span></p><p><span m="35899">You</span> <span m="36186">then</span>
  <span m="36473">express</span> <span m="36760">each</span> <span m="37047">set</span>
  <span m="37334">of</span> <span m="37621">inputs,</span> <span m="37908">that</span>
  <span m="38195">makes</span> <span m="38483">the</span> <span m="38770">function</span>
  <span m="39057">equal</span> <span m="39344">to</span> <span m="39631">1,</span>
  <span m="39918">as</span> <span m="40205">a</span> <span m="40492">basic</span>
  <span m="40780">product</span> <span m="41293">term.</span> <span m="41806">ORing</span>
  <span m="42319">all</span> <span m="42832">of</span> <span m="43346">these</span>
  <span m="43859">product</span> <span m="44372">terms</span> <span m="44885">together</span>
  <span m="45399">produces</span> <span m="45804">a</span> <span m="46210">sum</span>
  <span m="46616">of</span> <span m="47021">products</span> <span m="47427">representation</span>
  <span m="47833">for</span> <span m="48238">the</span> <span m="48644">function.</span></p><p><span
  m="49050">Note</span> <span m="49476">that</span> <span m="49902">this</span> <span
  m="50329">representation</span> <span m="50755">is</span> <span m="51182">not</span>
  <span m="51608">yet</span> <span m="52035">minimal.</span> <span m="52461">For</span>
  <span m="52888">our</span> <span m="53314">example,</span> <span m="53741">the</span>
  <span m="54167">sum</span> <span m="54594">of</span> <span m="55020">products</span>
  <span m="55447">is</span> <span m="55873">F</span> <span m="56300">=</span> <span
  m="57090">NOT(A)</span> <span m="57881">NOT(B)</span> <span m="58672">NOT(C)</span>
  <span m="59463">+</span> <span m="60254">NOT(A)</span> <span m="61045">B</span>
  <span m="61836">C</span> <span m="62627">+</span> <span m="63418">A</span> <span
  m="64209">NOT(B)</span> <span m="65000">NOT(C)</span> <span m="65791">+</span> <span
  m="66582">A</span> <span m="67373">NOT(B)</span> <span m="68164">C</span> <span
  m="68955">+</span> <span m="69746">A</span> <span m="70537">B</span> <span m="71328">C.</span></p><p><span
  m="72119">We</span> <span m="72485">then</span> <span m="72852">create</span> <span
  m="73218">the</span> <span m="73585">Karnaugh</span> <span m="73951">map</span>
  <span m="74318">for</span> <span m="74684">the</span> <span m="75051">function</span>
  <span m="75417">by</span> <span m="75784">making</span> <span m="76150">a</span>
  <span m="76517">2D</span> <span m="76883">grid</span> <span m="77250">representing</span>
  <span m="77616">all</span> <span m="77983">possible</span> <span m="78350">input</span>
  <span m="78696">combinations,</span> <span m="79043">and</span> <span m="79390">ensuring</span>
  <span m="79737">that</span> <span m="80084">from</span> <span m="80431">one</span>
  <span m="80778">column</span> <span m="81125">or</span> <span m="81471">row</span>
  <span m="81818">to</span> <span m="82165">the</span> <span m="82512">next</span>
  <span m="82859">in</span> <span m="83206">the</span> <span m="83553">grid,</span>
  <span m="83900">only</span> <span m="84310">one</span> <span m="84721">single</span>
  <span m="85132">input</span> <span m="85543">can</span> <span m="85953">be</span>
  <span m="86364">changed.</span> <span m="86775">This</span> <span m="87186">is</span>
  <span m="87596">known</span> <span m="88007">as</span> <span m="88418">Gray</span>
  <span m="88829">code.</span></p><p><span m="89240">Once</span> <span m="89518">we</span>
  <span m="89797">label</span> <span m="90076">the</span> <span m="90355">Karnaugh</span>
  <span m="90633">map,</span> <span m="90912">we</span> <span m="91191">can</span>
  <span m="91470">fill</span> <span m="91748">it</span> <span m="92027">with</span>
  <span m="92306">1's</span> <span m="92585">for</span> <span m="92863">each</span>
  <span m="93142">combination</span> <span m="93421">that</span> <span m="93700">produces</span>
  <span m="93979">a</span> <span m="94401">1</span> <span m="94823">output</span>
  <span m="95246">and</span> <span m="95668">0</span> <span m="96090">for</span> <span
  m="96513">each</span> <span m="96935">combination</span> <span m="97358">that</span>
  <span m="97780">produces</span> <span m="98202">a</span> <span m="98625">0</span>
  <span m="99047">output.</span></p><p><span m="99470">Next,</span> <span m="99784">we</span>
  <span m="100098">try</span> <span m="100413">to</span> <span m="100727">merge</span>
  <span m="101042">as</span> <span m="101356">many</span> <span m="101671">adjacent</span>
  <span m="101985">ones</span> <span m="102300">as</span> <span m="102614">possible</span>
  <span m="102928">into</span> <span m="103243">groups</span> <span m="103557">that</span>
  <span m="103872">are</span> <span m="104186">of</span> <span m="104501">size</span>
  <span m="104815">that</span> <span m="105130">is</span> <span m="105499">a</span>
  <span m="105868">power</span> <span m="106237">of</span> <span m="106606">2.</span>
  <span m="106976">Note</span> <span m="107345">that</span> <span m="107714">adjacent</span>
  <span m="108083">ones</span> <span m="108453">can</span> <span m="108822">be</span>
  <span m="109191">merged</span> <span m="109560">across</span> <span m="109930">rows,</span>
  <span m="110304">along</span> <span m="110678">columns,</span> <span m="111052">and</span>
  <span m="111427">across</span> <span m="111801">the</span> <span m="112175">edges</span>
  <span m="112550">of</span> <span m="112924">the</span> <span m="113298">Karnaugh</span>
  <span m="113672">map</span> <span m="114047">like</span> <span m="114421">a</span>
  <span m="114795">taurus.</span></p><p><span m="115170">Every</span> <span m="115498">largest</span>
  <span m="115827">grouping</span> <span m="116156">of</span> <span m="116485">1's</span>
  <span m="116813">that</span> <span m="117142">is</span> <span m="117471">required</span>
  <span m="117800">in</span> <span m="118128">order</span> <span m="118457">to</span>
  <span m="118786">cover</span> <span m="119115">all</span> <span m="119443">of</span>
  <span m="119772">the</span> <span m="120101">one's</span> <span m="120430">becomes</span>
  <span m="120759">one</span> <span m="121174">term</span> <span m="121589">in</span>
  <span m="122004">the</span> <span m="122419">minimal</span> <span m="122834">sum</span>
  <span m="123249">of</span> <span m="123664">products</span> <span m="124079">representation</span>
  <span m="124494">of</span> <span m="124909">the</span> <span m="125324">function.</span></p><p><span
  m="125740">To</span> <span m="125987">figure</span> <span m="126234">out</span>
  <span m="126482">what</span> <span m="126729">the</span> <span m="126976">term</span>
  <span m="127224">is,</span> <span m="127471">look</span> <span m="127718">at</span>
  <span m="127966">the</span> <span m="128213">labels</span> <span m="128461">of</span>
  <span m="128708">all</span> <span m="128955">the</span> <span m="129203">columns</span>
  <span m="129450">and</span> <span m="129697">rows</span> <span m="129945">that</span>
  <span m="130192">are</span> <span m="130440">covered</span> <span m="130823">by</span>
  <span m="131206">the</span> <span m="131589">grouping</span> <span m="131972">of</span>
  <span m="132355">1's</span> <span m="132738">and</span> <span m="133122">eliminate</span>
  <span m="133505">all</span> <span m="133888">inputs</span> <span m="134271">that</span>
  <span m="134654">appear</span> <span m="135037">as</span> <span m="135421">both</span>
  <span m="135804">a</span> <span m="136187">1</span> <span m="136570">and</span>
  <span m="136953">0</span> <span m="137336">input.</span></p><p><span m="137720">Because</span>
  <span m="138040">these</span> <span m="138360">inputs</span> <span m="138680">are</span>
  <span m="139000">represented</span> <span m="139320">in</span> <span m="139640">both</span>
  <span m="139960">their</span> <span m="140280">0</span> <span m="140600">and</span>
  <span m="140920">1</span> <span m="141240">form,</span> <span m="141560">it</span>
  <span m="141880">means</span> <span m="142200">that</span> <span m="142520">that</span>
  <span m="142840">input</span> <span m="143160">is</span> <span m="143515">not</span>
  <span m="143870">affecting</span> <span m="144226">the</span> <span m="144581">result</span>
  <span m="144936">of</span> <span m="145292">that</span> <span m="145647">term</span>
  <span m="146003">and</span> <span m="146358">can</span> <span m="146713">thus</span>
  <span m="147069">be</span> <span m="147424">eliminated.</span></p><p><span m="147780">By</span>
  <span m="148105">doing</span> <span m="148430">this</span> <span m="148755">for</span>
  <span m="149080">all</span> <span m="149405">groupings</span> <span m="149730">of</span>
  <span m="150055">1's</span> <span m="150380">and</span> <span m="150705">then</span>
  <span m="151030">ORing</span> <span m="151355">the</span> <span m="151680">results</span>
  <span m="152005">together,</span> <span m="152330">one</span> <span m="152655">produces</span>
  <span m="152980">a</span> <span m="153447">minimal</span> <span m="153915">sum</span>
  <span m="154383">of</span> <span m="154851">products</span> <span m="155318">representation</span>
  <span m="155786">for</span> <span m="156254">the</span> <span m="156722">function.</span></p><p><span
  m="157190">Note</span> <span m="157532">that</span> <span m="157875">having</span>
  <span m="158217">overlapping</span> <span m="158560">ones</span> <span m="158903">in</span>
  <span m="159245">your</span> <span m="159588">groupings</span> <span m="159930">is</span>
  <span m="160273">allowed</span> <span m="160616">and</span> <span m="160958">desired</span>
  <span m="161301">if</span> <span m="161643">it</span> <span m="161986">will</span>
  <span m="162329">result</span> <span m="162729">in</span> <span m="163130">a</span>
  <span m="163531">simpler</span> <span m="163931">product</span> <span m="164332">term.</span>
  <span m="164733">In</span> <span m="165134">our</span> <span m="165534">example,</span>
  <span m="165935">we</span> <span m="166336">circle</span> <span m="166737">the</span>
  <span m="167137">bottom</span> <span m="167538">two</span> <span m="167939">middle</span>
  <span m="168340">1's</span> <span m="168666">which</span> <span m="168992">represent</span>
  <span m="169318">the</span> <span m="169644">term</span> <span m="169970">BC</span>
  <span m="170296">because</span> <span m="170622">A</span> <span m="170948">appears</span>
  <span m="171275">in</span> <span m="171601">both</span> <span m="171927">its</span>
  <span m="172253">low</span> <span m="172579">and</span> <span m="172905">high</span>
  <span m="173231">form</span> <span m="173557">in</span> <span m="173883">the</span>
  <span m="174210">grouping.</span> <span m="174568">The</span> <span m="174926">next</span>
  <span m="175285">set</span> <span m="175643">of</span> <span m="176001">ones</span>
  <span m="176360">are</span> <span m="176718">the</span> <span m="177076">two</span>
  <span m="177435">in</span> <span m="177793">the</span> <span m="178151">rightmost</span>
  <span m="178510">column.</span> <span m="179023">These</span> <span m="179537">ones</span>
  <span m="180051">represent</span> <span m="180565">the</span> <span m="181078">term</span>
  <span m="181592">A</span> <span m="182106">NOT(B).</span></p><p><span m="182620">Finally,</span>
  <span m="183096">our</span> <span m="183572">last</span> <span m="184048">grouping</span>
  <span m="184524">wraps</span> <span m="185000">around</span> <span m="185476">the</span>
  <span m="185952">first</span> <span m="186428">row</span> <span m="186904">to</span>
  <span m="187380">create</span> <span m="187856">the</span> <span m="188332">term</span>
  <span m="188808">NOT(B)</span> <span m="189284">NOT(C).</span></p><p><span m="189760">This</span>
  <span m="190122">is</span> <span m="190485">a</span> <span m="190848">minimal</span>
  <span m="191210">sum</span> <span m="191573">of</span> <span m="191936">products</span>
  <span m="192299">representation</span> <span m="192661">of</span> <span m="193024">our</span>
  <span m="193387">function.</span></p><p><span m="193750">Note,</span> <span m="194081">however,</span>
  <span m="194412">that</span> <span m="194744">instead</span> <span m="195075">of</span>
  <span m="195406">grouping</span> <span m="195738">the</span> <span m="196069">two</span>
  <span m="196400">one's</span> <span m="196732">in</span> <span m="197063">the</span>
  <span m="197394">rightmost</span> <span m="197726">column,</span> <span m="198057">we</span>
  <span m="198388">could</span> <span m="198720">have</span> <span m="199097">instead</span>
  <span m="199474">grouped</span> <span m="199851">the</span> <span m="200229">two</span>
  <span m="200606">rightmost</span> <span m="200983">ones</span> <span m="201360">in</span>
  <span m="201738">the</span> <span m="202115">bottom</span> <span m="202492">row.</span></p><p><span
  m="202870">That</span> <span m="203311">would</span> <span m="203753">have</span>
  <span m="204195">produced</span> <span m="204637">the</span> <span m="205079">term</span>
  <span m="205520">AC</span> <span m="205962">instead</span> <span m="206404">of</span>
  <span m="206846">A</span> <span m="207288">NOT(B).</span></p><p><span m="207730">Either</span>
  <span m="208062">combination</span> <span m="208395">of</span> <span m="208728">terms</span>
  <span m="209060">is</span> <span m="209393">a</span> <span m="209726">valid</span>
  <span m="210058">minimal</span> <span m="210391">sum</span> <span m="210724">of</span>
  <span m="211056">products</span> <span m="211389">representation</span> <span m="211722">for</span>
  <span m="212054">this</span> <span m="212387">function.</span></p>
type: course
uid: c17d321f88380bc671a53ccf8011fe5d

---
None