---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: -bWtembpQjU
  parent_uid: b2d8d3c40928eb51d30291625e770cac
  title: Video-YouTube-Stream
  type: Video
  uid: e8150e8175078a73a85a4b3cdc215436
- id: 3Play-3Play YouTube id-Stream
  media_location: -bWtembpQjU
  parent_uid: b2d8d3c40928eb51d30291625e770cac
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 3fdd95bcd1847fef8e992c4091786f30
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/-bWtembpQjU/default.jpg
  parent_uid: b2d8d3c40928eb51d30291625e770cac
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 93757d96897c319a45d8afb67ab2ec69
- id: -bWtembpQjU.srt
  parent_uid: b2d8d3c40928eb51d30291625e770cac
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/c11s2v4/compiler-frontend-4-32-/-bWtembpQjU.srt
  title: 3play caption file
  type: null
  uid: 1ffda6c5cbeb0a81df5b252080db6655
- id: -bWtembpQjU.pdf
  parent_uid: b2d8d3c40928eb51d30291625e770cac
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/c11s2v4/compiler-frontend-4-32-/-bWtembpQjU.pdf
  title: 3play pdf file
  type: null
  uid: 996e2f12674f9d94c4e5daec708174c7
- id: Caption-3Play YouTube id-SRT
  parent_uid: b2d8d3c40928eb51d30291625e770cac
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: c4d2c9ac7f0779c86a044a13ac4b8a03
- id: Transcript-3Play YouTube id-PDF
  parent_uid: b2d8d3c40928eb51d30291625e770cac
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 8bbbe1b7766a9f7bf4b2bbc28c88b693
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_11-02-04_300k.mp4
  parent_uid: b2d8d3c40928eb51d30291625e770cac
  title: Video-Internet Archive-MP4
  type: Video
  uid: 3f44e82e9858d1a956c2116d5376c252
inline_embed_id: 44629955compilerfrontend43285577105
layout: video
order_index: null
parent_uid: d5da143e77344a11c69c28717ff472d2
related_resources_text: ''
short_url: compiler-frontend-4-32-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c11/c11s2/c11s2v4/compiler-frontend-4-32-
template_type: Embed
title: Compiler Frontend (4:32)
transcript: <p><span m='640'>A</span> <span m='1015'>modern</span> <span m='1390'>compiler</span>
  <span m='1765'>starts</span> <span m='2140'>by</span> <span m='2515'>analyzing</span>
  <span m='2890'>the</span> <span m='3265'>source</span> <span m='3640'>program</span>
  <span m='4015'>text</span> <span m='4390'>to</span> <span m='4765'>produce</span>
  <span m='5140'>an</span> <span m='5515'>equivalent</span> <span m='5890'>sequence</span>
  <span m='6396'>of</span> <span m='6902'>operations</span> <span m='7409'>expressed</span>
  <span m='7915'>in</span> <span m='8421'>a</span> <span m='8928'>language-</span>
  <span m='9434'>and</span> <span m='9940'>machine-independent</span> <span m='10447'>intermediate</span>
  <span m='10953'>representation</span> <span m='11460'>(IR).</span> </p><p><span
  m='12720'>The</span> <span m='13146'>analysis,</span> <span m='13572'>or</span>
  <span m='13999'>frontend,</span> <span m='14425'>phase</span> <span m='14851'>checks</span>
  <span m='15278'>that</span> <span m='15704'>program</span> <span m='16130'>is</span>
  <span m='16557'>well-formed,</span> <span m='16983'>i.e.,</span> <span m='17409'>that</span>
  <span m='17836'>the</span> <span m='18262'>syntax</span> <span m='18689'>of</span>
  <span m='19187'>each</span> <span m='19686'>high-level</span> <span m='20184'>language</span>
  <span m='20683'>statement</span> <span m='21181'>is</span> <span m='21680'>correct.</span>
  </p><p><span m='22179'>It</span> <span m='22707'>understands</span> <span m='23236'>the</span>
  <span m='23765'>meaning</span> <span m='24294'>(semantics)</span> <span m='24822'>of</span>
  <span m='25351'>each</span> <span m='25880'>statement.</span> </p><p><span m='26409'>Many</span>
  <span m='26800'>high-level</span> <span m='27192'>languages</span> <span m='27583'>include</span>
  <span m='27975'>declarations</span> <span m='28366'>of</span> <span m='28758'>the</span>
  <span m='29149'>type</span> <span m='29541'>-</span> <span m='29932'>e.g.,</span>
  <span m='30324'>integer,</span> <span m='30715'>floating</span> <span m='31107'>point,</span>
  <span m='31499'>string,</span> <span m='31909'>etc.</span> <span m='32320'>-</span>
  <span m='32731'>of</span> <span m='33142'>each</span> <span m='33553'>variable,</span>
  <span m='33964'>and</span> <span m='34374'>the</span> <span m='34785'>frontend</span>
  <span m='35196'>verifies</span> <span m='35607'>that</span> <span m='36018'>all</span>
  <span m='36429'>operations</span> <span m='36840'>are</span> <span m='37381'>correctly</span>
  <span m='37923'>applied,</span> <span m='38465'>ensuring</span> <span m='39007'>that</span>
  <span m='39549'>numeric</span> <span m='40090'>operations</span> <span m='40632'>have</span>
  <span m='41174'>numeric-type</span> <span m='41716'>operands,</span> <span m='42258'>string</span>
  <span m='42800'>operations</span> <span m='43371'>have</span> <span m='43942'>string-type</span>
  <span m='44514'>operands,</span> <span m='45085'>and</span> <span m='45657'>so</span>
  <span m='46228'>on.</span> </p><p><span m='46800'>Basically</span> <span m='47161'>the</span>
  <span m='47522'>analysis</span> <span m='47884'>phase</span> <span m='48245'>converts</span>
  <span m='48606'>the</span> <span m='48968'>text</span> <span m='49329'>of</span>
  <span m='49690'>the</span> <span m='50052'>source</span> <span m='50413'>program</span>
  <span m='50774'>into</span> <span m='51136'>an</span> <span m='51497'>internal</span>
  <span m='51859'>data</span> <span m='52337'>structure</span> <span m='52815'>that</span>
  <span m='53294'>specifies</span> <span m='53772'>the</span> <span m='54251'>sequence</span>
  <span m='54729'>and</span> <span m='55208'>type</span> <span m='55686'>of</span>
  <span m='56165'>operations</span> <span m='56643'>to</span> <span m='57122'>be</span>
  <span m='57600'>performed.</span> </p><p><span m='58079'>Often</span> <span m='58399'>there</span>
  <span m='58719'>are</span> <span m='59039'>families</span> <span m='59359'>of</span>
  <span m='59679'>frontend</span> <span m='59999'>programs</span> <span m='60319'>that</span>
  <span m='60639'>translate</span> <span m='60959'>a</span> <span m='61279'>variety</span>
  <span m='61599'>of</span> <span m='61919'>high-level</span> <span m='62239'>languages</span>
  <span m='62559'>(e.g,</span> <span m='63506'>C,</span> <span m='64454'>C++,</span>
  <span m='65401'>Java)</span> <span m='66349'>into</span> <span m='67297'>a</span>
  <span m='68244'>common</span> <span m='69192'>IR.</span> </p><p><span m='70140'>The</span>
  <span m='70560'>synthesis,</span> <span m='70981'>or</span> <span m='71402'>backend,</span>
  <span m='71822'>phase</span> <span m='72243'>then</span> <span m='72664'>optimizes</span>
  <span m='73084'>the</span> <span m='73505'>IR</span> <span m='73926'>to</span> <span
  m='74346'>reduce</span> <span m='74767'>the</span> <span m='75188'>number</span>
  <span m='75608'>of</span> <span m='76029'>operations</span> <span m='76450'>that</span>
  <span m='76793'>will</span> <span m='77136'>be</span> <span m='77479'>executed</span>
  <span m='77822'>when</span> <span m='78165'>the</span> <span m='78508'>final</span>
  <span m='78851'>code</span> <span m='79194'>is</span> <span m='79537'>run.</span>
  </p><p><span m='79880'>For</span> <span m='80183'>example,</span> <span m='80487'>it</span>
  <span m='80791'>might</span> <span m='81095'>find</span> <span m='81398'>operations</span>
  <span m='81702'>inside</span> <span m='82006'>of</span> <span m='82310'>a</span>
  <span m='82613'>loop</span> <span m='82917'>that</span> <span m='83221'>are</span>
  <span m='83525'>independent</span> <span m='83828'>of</span> <span m='84132'>the</span>
  <span m='84436'>loop</span> <span m='84740'>index</span> <span m='85128'>and</span>
  <span m='85516'>can</span> <span m='85904'>moved</span> <span m='86292'>outside</span>
  <span m='86680'>the</span> <span m='87068'>loop,</span> <span m='87456'>where</span>
  <span m='87844'>they</span> <span m='88232'>are</span> <span m='88620'>performed</span>
  <span m='89008'>once</span> <span m='89396'>instead</span> <span m='89784'>of</span>
  <span m='90172'>repeatedly</span> <span m='90560'>inside</span> <span m='91253'>the</span>
  <span m='91946'>loop.</span> </p><p><span m='92640'>Once</span> <span m='93030'>the</span>
  <span m='93420'>IR</span> <span m='93810'>is</span> <span m='94200'>in</span> <span
  m='94590'>its</span> <span m='94980'>final</span> <span m='95370'>optimized</span>
  <span m='95760'>form,</span> <span m='96150'>the</span> <span m='96540'>backend</span>
  <span m='96930'>generates</span> <span m='97320'>code</span> <span m='97710'>sequences</span>
  <span m='98100'>for</span> <span m='98490'>the</span> <span m='98880'>target</span>
  <span m='99380'>ISA</span> <span m='99880'>and</span> <span m='100380'>looks</span>
  <span m='100880'>for</span> <span m='101380'>further</span> <span m='101880'>optimizations</span>
  <span m='102380'>that</span> <span m='102880'>take</span> <span m='103380'>advantage</span>
  <span m='103880'>of</span> <span m='104380'>particular</span> <span m='104880'>features</span>
  <span m='105380'>of</span> <span m='106019'>the</span> <span m='106659'>ISA.</span>
  </p><p><span m='107299'>For</span> <span m='107672'>example,</span> <span m='108046'>for</span>
  <span m='108420'>the</span> <span m='108794'>Beta</span> <span m='109168'>ISA</span>
  <span m='109541'>we</span> <span m='109915'>saw</span> <span m='110289'>how</span>
  <span m='110663'>a</span> <span m='111037'>CMOVE</span> <span m='111410'>followed</span>
  <span m='111784'>by</span> <span m='112158'>an</span> <span m='112532'>arithmetic</span>
  <span m='112906'>operation</span> <span m='113280'>can</span> <span m='113686'>be</span>
  <span m='114092'>shorted</span> <span m='114499'>to</span> <span m='114905'>a</span>
  <span m='115311'>single</span> <span m='115718'>operation</span> <span m='116124'>with</span>
  <span m='116530'>a</span> <span m='116937'>constant</span> <span m='117343'>operand.</span>
  </p><p><span m='117750'>The</span> <span m='118084'>analysis</span> <span m='118418'>phase</span>
  <span m='118752'>starts</span> <span m='119086'>by</span> <span m='119420'>scanning</span>
  <span m='119754'>the</span> <span m='120088'>source</span> <span m='120422'>text</span>
  <span m='120756'>and</span> <span m='121090'>generating</span> <span m='121424'>a</span>
  <span m='121758'>sequence</span> <span m='122092'>of</span> <span m='122426'>token</span>
  <span m='122760'>objects</span> <span m='123140'>that</span> <span m='123521'>identify</span>
  <span m='123902'>the</span> <span m='124283'>type</span> <span m='124664'>of</span>
  <span m='125045'>each</span> <span m='125425'>piece</span> <span m='125806'>of</span>
  <span m='126187'>the</span> <span m='126568'>source</span> <span m='126949'>text.</span>
  </p><p><span m='127330'>While</span> <span m='127693'>spaces,</span> <span m='128057'>tabs,</span>
  <span m='128421'>newlines,</span> <span m='128785'>and</span> <span m='129148'>so</span>
  <span m='129512'>on</span> <span m='129876'>were</span> <span m='130240'>needed</span>
  <span m='130603'>to</span> <span m='130967'>separate</span> <span m='131331'>tokens</span>
  <span m='131695'>in</span> <span m='132058'>the</span> <span m='132422'>source</span>
  <span m='132786'>text,</span> <span m='133150'>they've</span> <span m='133570'>all</span>
  <span m='133990'>been</span> <span m='134410'>removed</span> <span m='134830'>during</span>
  <span m='135250'>the</span> <span m='135670'>scanning</span> <span m='136090'>process.</span>
  </p><p><span m='136510'>To</span> <span m='136897'>enable</span> <span m='137284'>useful</span>
  <span m='137671'>error</span> <span m='138058'>reporting,</span> <span m='138445'>token</span>
  <span m='138832'>objects</span> <span m='139220'>also</span> <span m='139607'>include</span>
  <span m='139994'>information</span> <span m='140381'>about</span> <span m='140768'>where</span>
  <span m='141155'>in</span> <span m='141542'>the</span> <span m='141930'>source</span>
  <span m='142402'>text</span> <span m='142874'>each</span> <span m='143346'>token</span>
  <span m='143818'>was</span> <span m='144290'>found,</span> <span m='144762'>e.g.,</span>
  <span m='145234'>the</span> <span m='145706'>file</span> <span m='146178'>name,</span>
  <span m='146650'>line</span> <span m='147122'>number,</span> <span m='147594'>and</span>
  <span m='148066'>column</span> <span m='148538'>number.</span> </p><p><span m='149010'>The</span>
  <span m='149437'>scanning</span> <span m='149864'>phase</span> <span m='150291'>reports</span>
  <span m='150718'>illegal</span> <span m='151145'>tokens,</span> <span m='151572'>e.g.,</span>
  <span m='151999'>the</span> <span m='152426'>token</span> <span m='152853'>"3x"</span>
  <span m='153280'>would</span> <span m='153707'>cause</span> <span m='154134'>an</span>
  <span m='154561'>error</span> <span m='154989'>since</span> <span m='155377'>in</span>
  <span m='155765'>C</span> <span m='156153'>it</span> <span m='156541'>would</span>
  <span m='156929'>not</span> <span m='157317'>be</span> <span m='157705'>a</span>
  <span m='158093'>legal</span> <span m='158481'>number</span> <span m='158869'>or</span>
  <span m='159257'>a</span> <span m='159645'>legal</span> <span m='160033'>variable</span>
  <span m='160421'>name.</span> </p><p><span m='160810'>The</span> <span m='161195'>parsing</span>
  <span m='161581'>phase</span> <span m='161967'>processes</span> <span m='162353'>the</span>
  <span m='162739'>sequence</span> <span m='163125'>of</span> <span m='163511'>tokens</span>
  <span m='163897'>to</span> <span m='164283'>build</span> <span m='164669'>the</span>
  <span m='165055'>syntax</span> <span m='165441'>tree,</span> <span m='165827'>which</span>
  <span m='166213'>captures</span> <span m='166599'>the</span> <span m='167041'>structure</span>
  <span m='167484'>of</span> <span m='167927'>the</span> <span m='168370'>original</span>
  <span m='168813'>program</span> <span m='169255'>in</span> <span m='169698'>a</span>
  <span m='170141'>convenient</span> <span m='170584'>data</span> <span m='171027'>structure.</span>
  </p><p><span m='171470'>The</span> <span m='171867'>operands</span> <span m='172264'>have</span>
  <span m='172661'>been</span> <span m='173059'>organized</span> <span m='173456'>for</span>
  <span m='173853'>each</span> <span m='174250'>unary</span> <span m='174648'>and</span>
  <span m='175045'>binary</span> <span m='175442'>operation.</span> </p><p><span m='175840'>The</span>
  <span m='176228'>components</span> <span m='176616'>of</span> <span m='177004'>each</span>
  <span m='177392'>statement</span> <span m='177780'>have</span> <span m='178168'>been</span>
  <span m='178556'>found</span> <span m='178944'>and</span> <span m='179332'>labeled.</span>
  </p><p><span m='179720'>The</span> <span m='180063'>role</span> <span m='180407'>of</span>
  <span m='180751'>each</span> <span m='181095'>source</span> <span m='181438'>token</span>
  <span m='181782'>has</span> <span m='182126'>been</span> <span m='182470'>determined</span>
  <span m='182813'>and</span> <span m='183157'>the</span> <span m='183501'>information</span>
  <span m='183845'>captured</span> <span m='184188'>in</span> <span m='184532'>the</span>
  <span m='184876'>syntax</span> <span m='185220'>tree.</span> </p><p><span m='187120'>Compare</span>
  <span m='187357'>the</span> <span m='187595'>labels</span> <span m='187832'>of</span>
  <span m='188070'>the</span> <span m='188307'>nodes</span> <span m='188545'>in</span>
  <span m='188783'>the</span> <span m='189020'>tree</span> <span m='189258'>to</span>
  <span m='189495'>the</span> <span m='189733'>templates</span> <span m='189971'>we</span>
  <span m='190208'>discussed</span> <span m='190446'>in</span> <span m='190683'>the</span>
  <span m='190921'>previous</span> <span m='191159'>segment.</span> </p><p><span m='192159'>We</span>
  <span m='192420'>can</span> <span m='192681'>see</span> <span m='192942'>that</span>
  <span m='193203'>it</span> <span m='193464'>would</span> <span m='193726'>be</span>
  <span m='193987'>easy</span> <span m='194248'>to</span> <span m='194509'>write</span>
  <span m='194770'>a</span> <span m='195031'>program</span> <span m='195293'>that</span>
  <span m='195554'>did</span> <span m='195815'>a</span> <span m='196076'>depth-first</span>
  <span m='196337'>tree</span> <span m='196598'>walk,</span> <span m='196860'>using</span>
  <span m='197180'>the</span> <span m='197501'>label</span> <span m='197821'>of</span>
  <span m='198142'>each</span> <span m='198463'>tree</span> <span m='198783'>node</span>
  <span m='199104'>to</span> <span m='199425'>select</span> <span m='199745'>the</span>
  <span m='200066'>appropriate</span> <span m='200387'>code</span> <span m='200707'>generation</span>
  <span m='201028'>template.</span> </p><p><span m='201349'>We</span> <span m='201626'>won't</span>
  <span m='201904'>do</span> <span m='202181'>that</span> <span m='202459'>quite</span>
  <span m='202737'>yet</span> <span m='203014'>since</span> <span m='203292'>there's</span>
  <span m='203570'>still</span> <span m='203847'>some</span> <span m='204125'>work</span>
  <span m='204403'>to</span> <span m='204680'>be</span> <span m='204958'>done</span>
  <span m='205236'>analyzing</span> <span m='205513'>and</span> <span m='205791'>transforming</span>
  <span m='206069'>the</span> <span m='206909'>tree.</span> </p><p><span m='207750'>The</span>
  <span m='208092'>syntax</span> <span m='208435'>tree</span> <span m='208778'>makes</span>
  <span m='209120'>it</span> <span m='209463'>easy</span> <span m='209806'>to</span>
  <span m='210148'>verify</span> <span m='210491'>that</span> <span m='210834'>the</span>
  <span m='211176'>program</span> <span m='211519'>is</span> <span m='211862'>semantically</span>
  <span m='212204'>correct,</span> <span m='212547'>e.g.,</span> <span m='212890'>to</span>
  <span m='213273'>check</span> <span m='213657'>that</span> <span m='214040'>the</span>
  <span m='214424'>types</span> <span m='214807'>of</span> <span m='215191'>the</span>
  <span m='215575'>operands</span> <span m='215958'>are</span> <span m='216342'>compatible</span>
  <span m='216725'>with</span> <span m='217109'>the</span> <span m='217492'>requested</span>
  <span m='217876'>operation.</span> </p><p><span m='218260'>For</span> <span m='218888'>example,</span>
  <span m='219517'>consider</span> <span m='220146'>the</span> <span m='220775'>statement</span>
  <span m='221403'>x</span> <span m='222032'>=</span> <span m='222661'>"bananas".</span>
  </p><p><span m='223290'>The</span> <span m='223610'>syntax</span> <span m='223931'>of</span>
  <span m='224252'>the</span> <span m='224572'>assignment</span> <span m='224893'>operation</span>
  <span m='225214'>is</span> <span m='225535'>correct:</span> <span m='225855'>there's</span>
  <span m='226176'>a</span> <span m='226497'>variable</span> <span m='226817'>on</span>
  <span m='227138'>the</span> <span m='227459'>left-hand</span> <span m='227780'>side</span>
  <span m='228142'>and</span> <span m='228505'>an</span> <span m='228867'>expression</span>
  <span m='229230'>on</span> <span m='229592'>the</span> <span m='229955'>right-hand</span>
  <span m='230317'>side.</span> </p><p><span m='230680'>But</span> <span m='231034'>the</span>
  <span m='231388'>semantics</span> <span m='231742'>is</span> <span m='232096'>not</span>
  <span m='232450'>correct,</span> <span m='232805'>at</span> <span m='233159'>least</span>
  <span m='233513'>in</span> <span m='233867'>the</span> <span m='234221'>C</span>
  <span m='234575'>language!</span> </p><p><span m='234930'>By</span> <span m='235293'>looking</span>
  <span m='235657'>in</span> <span m='236020'>its</span> <span m='236384'>symbol</span>
  <span m='236747'>table</span> <span m='237111'>to</span> <span m='237474'>check</span>
  <span m='237838'>the</span> <span m='238201'>declared</span> <span m='238565'>type</span>
  <span m='238928'>for</span> <span m='239292'>the</span> <span m='239655'>variable</span>
  <span m='240019'>x</span> <span m='240382'>(int)</span> <span m='240746'>and</span>
  <span m='241110'>comparing</span> <span m='241483'>it</span> <span m='241856'>to</span>
  <span m='242230'>the</span> <span m='242603'>type</span> <span m='242976'>of</span>
  <span m='243350'>the</span> <span m='243723'>expression</span> <span m='244096'>(string),</span>
  <span m='244470'>the</span> <span m='244847'>semantic</span> <span m='245225'>checker</span>
  <span m='245602'>for</span> <span m='245980'>the</span> <span m='246358'>"op</span>
  <span m='246735'>="</span> <span m='247113'>tree</span> <span m='247491'>node</span>
  <span m='247868'>will</span> <span m='248246'>detect</span> <span m='248624'>that</span>
  <span m='249001'>the</span> <span m='249379'>types</span> <span m='249757'>are</span>
  <span m='250134'>not</span> <span m='250512'>compatible,</span> <span m='250890'>i.e.,</span>
  <span m='251399'>that</span> <span m='251908'>we</span> <span m='252417'>can't</span>
  <span m='252926'>store</span> <span m='253435'>a</span> <span m='253945'>string</span>
  <span m='254454'>value</span> <span m='254963'>into</span> <span m='255472'>an</span>
  <span m='255981'>integer</span> <span m='256490'>variable.</span> </p><p><span m='257000'>When</span>
  <span m='257360'>the</span> <span m='257721'>semantic</span> <span m='258082'>analysis</span>
  <span m='258442'>is</span> <span m='258803'>complete,</span> <span m='259164'>we</span>
  <span m='259524'>know</span> <span m='259885'>that</span> <span m='260246'>the</span>
  <span m='260606'>syntax</span> <span m='260967'>tree</span> <span m='261328'>represents</span>
  <span m='261688'>a</span> <span m='262049'>syntactically</span> <span m='262410'>correct</span>
  <span m='262860'>program</span> <span m='263311'>with</span> <span m='263762'>valid</span>
  <span m='264213'>semantics,</span> <span m='264664'>and</span> <span m='265115'>we've</span>
  <span m='265565'>finished</span> <span m='266016'>converting</span> <span m='266467'>the</span>
  <span m='266918'>source</span> <span m='267369'>program</span> <span m='267820'>into</span>
  <span m='268347'>an</span> <span m='268874'>equivalent,</span> <span m='269401'>language-independent</span>
  <span m='269928'>sequence</span> <span m='270455'>of</span> <span m='270982'>operations.</span>
  </p>
type: course
uid: b2d8d3c40928eb51d30291625e770cac

---
None