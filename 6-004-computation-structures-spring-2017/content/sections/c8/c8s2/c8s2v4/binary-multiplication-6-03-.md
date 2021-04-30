---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 0OX-DkYPB3c
  parent_uid: 113a4c0e66c4e62aa9ca15057f2820bc
  title: Video-YouTube-Stream
  type: Video
  uid: 17bed13cba6804234095d049150cb0c4
- id: 3Play-3Play YouTube id-Stream
  media_location: 0OX-DkYPB3c
  parent_uid: 113a4c0e66c4e62aa9ca15057f2820bc
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 0a5ac19daef105387984df91084af8bf
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/0OX-DkYPB3c/default.jpg
  parent_uid: 113a4c0e66c4e62aa9ca15057f2820bc
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: a179a72461080e77520f1ec08df96542
- id: 0OX-DkYPB3c.srt
  parent_uid: 113a4c0e66c4e62aa9ca15057f2820bc
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c8/c8s2/c8s2v4/binary-multiplication-6-03-/0OX-DkYPB3c.srt
  title: 3play caption file
  type: null
  uid: aaf5d81836eeadc110dd39068182c9bb
- id: 0OX-DkYPB3c.pdf
  parent_uid: 113a4c0e66c4e62aa9ca15057f2820bc
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c8/c8s2/c8s2v4/binary-multiplication-6-03-/0OX-DkYPB3c.pdf
  title: 3play pdf file
  type: null
  uid: 64af6ea8321c953fe0c6d0c90fcb61ad
- id: Caption-3Play YouTube id-SRT
  parent_uid: 113a4c0e66c4e62aa9ca15057f2820bc
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ad61b50e9c18da472cdab555e5909e94
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 113a4c0e66c4e62aa9ca15057f2820bc
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 9124ecb071bae1b38f3c99dd5f786f66
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_08-02-04_300k.mp4
  parent_uid: 113a4c0e66c4e62aa9ca15057f2820bc
  title: Video-Internet Archive-MP4
  type: Video
  uid: ec11004e9d6bd081dbea0bde7b20a807
inline_embed_id: 2449177binarymultiplication60382223683
layout: video
order_index: null
parent_uid: f42cf9276a49d5f28e0adda9e34dd6d8
related_resources_text: ''
short_url: binary-multiplication-6-03-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c8/c8s2/c8s2v4/binary-multiplication-6-03-
template_type: Embed
title: Binary Multiplication (6:03)
transcript: "<p><span m='1079'>One</span> <span m='1430'>of</span> <span m='1781'>the</span>\
  \ <span m='2132'>biggest</span> <span m='2484'>and</span> <span m='2835'>slowest</span>\
  \ <span m='3186'>circuits</span> <span m='3538'>in</span> <span m='3889'>an</span>\
  \ <span m='4240'>arithmetic</span> <span m='4592'>and</span> <span m='4943'>logic</span>\
  \ <span m='5294'>unit</span> <span m='5646'>is</span> <span m='5997'>the</span>\
  \ <span m='6348'>multiplier.</span> </p><p><span m='6700'>We'll</span> <span m='7052'>start</span>\
  \ <span m='7404'>by</span> <span m='7756'>developing</span> <span m='8109'>a</span>\
  \ <span m='8461'>straightforward</span> <span m='8813'>implementation</span> <span\
  \ m='9166'>and</span> <span m='9518'>then,</span> <span m='9870'>in</span> <span\
  \ m='10223'>the</span> <span m='10575'>next</span> <span m='10927'>section,</span>\
  \ <span m='11280'>look</span> <span m='11802'>into</span> <span m='12325'>tradeoffs</span>\
  \ <span m='12848'>to</span> <span m='13371'>make</span> <span m='13894'>it</span>\
  \ <span m='14417'>either</span> <span m='14940'>smaller</span> <span m='15463'>or</span>\
  \ <span m='15986'>faster.</span> </p><p><span m='16509'>Here's</span> <span m='16893'>the</span>\
  \ <span m='17278'>multiplication</span> <span m='17663'>operation</span> <span m='18047'>for</span>\
  \ <span m='18432'>two</span> <span m='18817'>unsigned</span> <span m='19201'>4-bit</span>\
  \ <span m='19586'>operands</span> <span m='19971'>broken</span> <span m='20355'>down</span>\
  \ <span m='20740'>into</span> <span m='21125'>its</span> <span m='21510'>component</span>\
  \ <span m='22800'>operations.</span> </p><p><span m='24090'>This</span> <span m='24376'>is</span>\
  \ <span m='24663'>exactly</span> <span m='24949'>how</span> <span m='25236'>we</span>\
  \ <span m='25522'>learned</span> <span m='25809'>to</span> <span m='26096'>do</span>\
  \ <span m='26382'>it</span> <span m='26669'>in</span> <span m='26955'>primary</span>\
  \ <span m='27242'>school.</span> </p><p><span m='27529'>We</span> <span m='27915'>take</span>\
  \ <span m='28302'>each</span> <span m='28689'>digit</span> <span m='29075'>of</span>\
  \ <span m='29462'>the</span> <span m='29849'>multiplier</span> <span m='30236'>(the</span>\
  \ <span m='30622'>B</span> <span m='31009'>operand)</span> <span m='31396'>and</span>\
  \ <span m='31783'>use</span> <span m='32169'>our</span> <span m='32556'>memorized</span>\
  \ <span m='32943'>multiplication</span> <span m='33330'>tables</span> <span m='33730'>to</span>\
  \ <span m='34131'>multiply</span> <span m='34532'>it</span> <span m='34933'>with</span>\
  \ <span m='35333'>each</span> <span m='35734'>digit</span> <span m='36135'>of</span>\
  \ <span m='36536'>the</span> <span m='36936'>multiplicand</span> <span m='37337'>(the</span>\
  \ <span m='37738'>A</span> <span m='38139'>operand),</span> <span m='38540'>dealing</span>\
  \ <span m='38975'>with</span> <span m='39411'>any</span> <span m='39847'>carries</span>\
  \ <span m='40282'>into</span> <span m='40718'>the</span> <span m='41154'>next</span>\
  \ <span m='41590'>column</span> <span m='42025'>as</span> <span m='42461'>we</span>\
  \ <span m='42897'>process</span> <span m='43332'>the</span> <span m='43768'>multiplicand</span>\
  \ <span m='44204'>right-to-left.</span> </p><p><span m='44640'>The</span> <span\
  \ m='44896'>output</span> <span m='45152'>from</span> <span m='45408'>this</span>\
  \ <span m='45664'>step</span> <span m='45920'>is</span> <span m='46176'>called</span>\
  \ <span m='46432'>a</span> <span m='46688'>partial</span> <span m='46945'>product</span>\
  \ <span m='47201'>and</span> <span m='47457'>then</span> <span m='47713'>we</span>\
  \ <span m='47969'>repeat</span> <span m='48225'>the</span> <span m='48481'>step</span>\
  \ <span m='48737'>for</span> <span m='48993'>the</span> <span m='49250'>remaining</span>\
  \ <span m='49728'>bits</span> <span m='50206'>of</span> <span m='50684'>the</span>\
  \ <span m='51162'>multiplier.</span> </p><p><span m='51640'>Each</span> <span m='51962'>partial</span>\
  \ <span m='52284'>product</span> <span m='52606'>is</span> <span m='52928'>shifted</span>\
  \ <span m='53250'>one</span> <span m='53572'>digit</span> <span m='53895'>to</span>\
  \ <span m='54217'>the</span> <span m='54539'>left,</span> <span m='54861'>reflecting</span>\
  \ <span m='55183'>the</span> <span m='55505'>increasing</span> <span m='55827'>weight</span>\
  \ <span m='56150'>of</span> <span m='56892'>the</span> <span m='57634'>multiplier</span>\
  \ <span m='58376'>digits.</span> </p><p><span m='59119'>In</span> <span m='59472'>our</span>\
  \ <span m='59825'>case</span> <span m='60178'>the</span> <span m='60531'>digits</span>\
  \ <span m='60884'>are</span> <span m='61237'>just</span> <span m='61590'>single</span>\
  \ <span m='61943'>bits,</span> <span m='62296'>i.e.,</span> <span m='62649'>they're</span>\
  \ <span m='63002'>0</span> <span m='63355'>or</span> <span m='63708'>1</span> <span\
  \ m='64061'>and</span> <span m='64414'>the</span> <span m='64767'>multiplication</span>\
  \ <span m='65120'>table</span> <span m='65492'>is</span> <span m='65865'>pretty</span>\
  \ <span m='66237'>simple!</span> </p><p><span m='66610'>In</span> <span m='67102'>fact,</span>\
  \ <span m='67594'>the</span> <span m='68086'>1-bit-by-1-bit</span> <span m='68579'>binary</span>\
  \ <span m='69071'>multiplication</span> <span m='69563'>circuit</span> <span m='70056'>is</span>\
  \ <span m='70548'>just</span> <span m='71040'>a</span> <span m='71533'>2-input</span>\
  \ <span m='72025'>AND</span> <span m='72517'>gate.</span> </p><p><span m='73010'>And</span>\
  \ <span m='73692'>look</span> <span m='74374'>Mom,</span> <span m='75056'>no</span>\
  \ <span m='75738'>carries!</span> </p><p><span m='76420'>The</span> <span m='76766'>partial</span>\
  \ <span m='77113'>products</span> <span m='77460'>are</span> <span m='77806'>N</span>\
  \ <span m='78153'>bits</span> <span m='78500'>wide</span> <span m='78846'>since</span>\
  \ <span m='79193'>there</span> <span m='79540'>are</span> <span m='79886'>no</span>\
  \ <span m='80233'>carries.</span> </p><p><span m='80580'>If</span> <span m='80985'>the</span>\
  \ <span m='81391'>multiplier</span> <span m='81797'>has</span> <span m='82203'>M</span>\
  \ <span m='82609'>bits,</span> <span m='83015'>there</span> <span m='83420'>will</span>\
  \ <span m='83826'>be</span> <span m='84232'>M</span> <span m='84638'>partial</span>\
  \ <span m='85044'>products.</span> </p><p><span m='85450'>And</span> <span m='85740'>when</span>\
  \ <span m='86031'>we</span> <span m='86321'>add</span> <span m='86612'>the</span>\
  \ <span m='86902'>partial</span> <span m='87193'>products</span> <span m='87484'>together,</span>\
  \ <span m='87774'>we'll</span> <span m='88065'>get</span> <span m='88355'>an</span>\
  \ <span m='88646'>N+M</span> <span m='88937'>bit</span> <span m='89227'>result</span>\
  \ <span m='89518'>if</span> <span m='89808'>we</span> <span m='90099'>account</span>\
  \ <span m='90390'>for</span> <span m='90868'>the</span> <span m='91347'>possible</span>\
  \ <span m='91826'>carry-out</span> <span m='92305'>from</span> <span m='92783'>the</span>\
  \ <span m='93262'>high-order</span> <span m='93741'>bit.</span> </p><p><span m='94220'>The</span>\
  \ <span m='94496'>easy</span> <span m='94772'>part</span> <span m='95048'>of</span>\
  \ <span m='95325'>the</span> <span m='95601'>multiplication</span> <span m='95877'>is</span>\
  \ <span m='96153'>forming</span> <span m='96430'>the</span> <span m='96706'>partial</span>\
  \ <span m='96982'>products</span> <span m='97258'>-</span> <span m='97535'>it</span>\
  \ <span m='97811'>just</span> <span m='98087'>requires</span> <span m='98363'>some</span>\
  \ <span m='98640'>AND</span> <span m='99335'>gates.</span> </p><p><span m='100030'>The</span>\
  \ <span m='100578'>more</span> <span m='101126'>expensive</span> <span m='101675'>operation</span>\
  \ <span m='102223'>is</span> <span m='102771'>adding</span> <span m='103320'>together</span>\
  \ <span m='103868'>the</span> <span m='104416'>M</span> <span m='104965'>N-bit</span>\
  \ <span m='105513'>partial</span> <span m='106061'>products.</span> </p><p><span\
  \ m='106610'>Here's</span> <span m='107049'>the</span> <span m='107488'>schematic</span>\
  \ <span m='107927'>for</span> <span m='108366'>the</span> <span m='108806'>combinational</span>\
  \ <span m='109245'>logic</span> <span m='109684'>needed</span> <span m='110123'>to</span>\
  \ <span m='110563'>implement</span> <span m='111002'>the</span> <span m='111441'>4x4</span>\
  \ <span m='111880'>multiplication,</span> <span m='112320'>which</span> <span m='112680'>would</span>\
  \ <span m='113040'>be</span> <span m='113400'>easy</span> <span m='113760'>to</span>\
  \ <span m='114120'>extend</span> <span m='114480'>for</span> <span m='114840'>larger</span>\
  \ <span m='115200'>multipliers</span> <span m='115560'>(we'd</span> <span m='115920'>need</span>\
  \ <span m='116280'>more</span> <span m='116640'>rows)</span> <span m='117000'>or</span>\
  \ <span m='117360'>larger</span> <span m='117720'>multiplicands</span> <span m='118080'>(we'd</span>\
  \ <span m='118542'>need</span> <span m='119005'>more</span> <span m='119467'>columns).</span>\
  \ </p><p><span m='119930'>The</span> <span m='120451'>M*N</span> <span m='120973'>2-input</span>\
  \ <span m='121494'>AND</span> <span m='122016'>gates</span> <span m='122537'>compute</span>\
  \ <span m='123059'>the</span> <span m='123580'>bits</span> <span m='124102'>of</span>\
  \ <span m='124623'>the</span> <span m='125145'>M</span> <span m='125666'>partial</span>\
  \ <span m='126188'>products.</span> </p><p><span m='126710'>The</span> <span m='126979'>adder</span>\
  \ <span m='127248'>modules</span> <span m='127518'>add</span> <span m='127787'>the</span>\
  \ <span m='128056'>current</span> <span m='128326'>row's</span> <span m='128595'>partial</span>\
  \ <span m='128865'>product</span> <span m='129134'>with</span> <span m='129403'>the</span>\
  \ <span m='129673'>sum</span> <span m='129942'>of</span> <span m='130211'>the</span>\
  \ <span m='130481'>partial</span> <span m='130750'>products</span> <span m='131020'>from</span>\
  \ <span m='131535'>the</span> <span m='132050'>earlier</span> <span m='132565'>rows.</span>\
  \ </p><p><span m='133080'>Actually</span> <span m='133400'>there</span> <span m='133720'>are</span>\
  \ <span m='134040'>two</span> <span m='134360'>types</span> <span m='134680'>of</span>\
  \ <span m='135000'>adder</span> <span m='135320'>modules.</span> </p><p><span m='135640'>The</span>\
  \ <span m='136025'>full</span> <span m='136410'>adder</span> <span m='136796'>is</span>\
  \ <span m='137181'>used</span> <span m='137567'>when</span> <span m='137952'>the</span>\
  \ <span m='138338'>modules</span> <span m='138723'>needs</span> <span m='139109'>three</span>\
  \ <span m='139494'>inputs.</span> </p><p><span m='139880'>The</span> <span m='140304'>simpler</span>\
  \ <span m='140728'>half</span> <span m='141152'>adder</span> <span m='141576'>is</span>\
  \ <span m='142000'>used</span> <span m='142425'>when</span> <span m='142849'>only</span>\
  \ <span m='143273'>two</span> <span m='143697'>inputs</span> <span m='144121'>are</span>\
  \ <span m='144545'>needed.</span> </p><p><span m='144970'>The</span> <span m='145298'>longest</span>\
  \ <span m='145626'>path</span> <span m='145955'>through</span> <span m='146283'>this</span>\
  \ <span m='146611'>circuit</span> <span m='146940'>takes</span> <span m='147268'>a</span>\
  \ <span m='147596'>moment</span> <span m='147925'>to</span> <span m='148253'>figure</span>\
  \ <span m='148581'>out.</span> </p><p><span m='148910'>Information</span> <span\
  \ m='149266'>is</span> <span m='149622'>always</span> <span m='149979'>moving</span>\
  \ <span m='150335'>either</span> <span m='150692'>down</span> <span m='151048'>a</span>\
  \ <span m='151405'>row</span> <span m='151761'>or</span> <span m='152117'>left</span>\
  \ <span m='152474'>to</span> <span m='152830'>the</span> <span m='153187'>adjacent</span>\
  \ <span m='153543'>column.</span> </p><p><span m='153900'>Since</span> <span m='154258'>there</span>\
  \ <span m='154616'>are</span> <span m='154974'>M</span> <span m='155333'>rows</span>\
  \ <span m='155691'>and,</span> <span m='156049'>in</span> <span m='156407'>any</span>\
  \ <span m='156766'>particular</span> <span m='157124'>row,</span> <span m='157482'>N</span>\
  \ <span m='157841'>columns,</span> <span m='158199'>there</span> <span m='158557'>are</span>\
  \ <span m='158915'>at</span> <span m='159274'>most</span> <span m='159632'>N+M</span>\
  \ <span m='159990'>modules</span> <span m='160349'>along</span> <span m='160826'>any</span>\
  \ <span m='161303'>path</span> <span m='161780'>from</span> <span m='162258'>input</span>\
  \ <span m='162735'>to</span> <span m='163212'>output.</span> </p><p><span m='163690'>So</span>\
  \ <span m='164135'>the</span> <span m='164580'>latency</span> <span m='165025'>is</span>\
  \ <span m='165470'>order</span> <span m='165915'>N,</span> <span m='166360'>since</span>\
  \ <span m='166805'>M</span> <span m='167250'>and</span> <span m='167695'>N</span>\
  \ <span m='168140'>differ</span> <span m='168585'>by</span> <span m='169030'>just</span>\
  \ <span m='169475'>some</span> <span m='169920'>constant</span> <span m='170365'>factor.</span>\
  \ </p><p><span m='170810'>Since</span> <span m='171220'>this</span> <span m='171631'>is</span>\
  \ <span m='172042'>a</span> <span m='172453'>combinational</span> <span m='172864'>circuit,</span>\
  \ <span m='173274'>the</span> <span m='173685'>throughput</span> <span m='174096'>is</span>\
  \ <span m='174507'>just</span> <span m='174918'>1/latency.</span> </p><p><span m='175329'>And</span>\
  \ <span m='175698'>the</span> <span m='176067'>total</span> <span m='176436'>amount</span>\
  \ <span m='176805'>of</span> <span m='177174'>hardware</span> <span m='177543'>is</span>\
  \ <span m='177912'>order</span> <span m='178281'>N^2.</span> </p><p><span m='178650'>In</span>\
  \ <span m='179024'>the</span> <span m='179398'>next</span> <span m='179772'>section,</span>\
  \ <span m='180147'>we'll</span> <span m='180521'>investigate</span> <span m='180895'>how</span>\
  \ <span m='181270'>to</span> <span m='181644'>reduce</span> <span m='182018'>the</span>\
  \ <span m='182392'>hardware</span> <span m='182767'>costs,</span> <span m='183141'>or,</span>\
  \ <span m='183515'>separately,</span> <span m='183890'>how</span> <span m='184360'>to</span>\
  \ <span m='184830'>increase</span> <span m='185300'>the</span> <span m='185770'>throughput.</span>\
  \ </p><p><span m='186240'>But</span> <span m='186457'>before</span> <span m='186675'>we</span>\
  \ <span m='186893'>do</span> <span m='187111'>that,</span> <span m='187328'>let's</span>\
  \ <span m='187546'>take</span> <span m='187764'>a</span> <span m='187982'>moment</span>\
  \ <span m='188200'>to</span> <span m='188417'>see</span> <span m='188635'>how</span>\
  \ <span m='188853'>the</span> <span m='189071'>circuit</span> <span m='189288'>would</span>\
  \ <span m='189506'>change</span> <span m='189724'>if</span> <span m='189942'>the</span>\
  \ <span m='190160'>operands</span> <span m='190778'>were</span> <span m='191397'>two's</span>\
  \ <span m='192016'>complement</span> <span m='192635'>integers</span> <span m='193254'>instead</span>\
  \ <span m='193873'>of</span> <span m='194492'>unsigned</span> <span m='195111'>integers.</span>\
  \ </p><p><span m='195730'>With</span> <span m='196155'>a</span> <span m='196580'>two's</span>\
  \ <span m='197006'>complement</span> <span m='197431'>multiplier</span> <span m='197856'>and</span>\
  \ <span m='198282'>multiplicand,</span> <span m='198707'>the</span> <span m='199132'>high-order</span>\
  \ <span m='199558'>bit</span> <span m='199983'>of</span> <span m='200408'>each</span>\
  \ <span m='200834'>has</span> <span m='201259'>negative</span> <span m='201684'>weight.</span>\
  \ </p><p><span m='202110'>So</span> <span m='202420'>when</span> <span m='202731'>adding</span>\
  \ <span m='203042'>together</span> <span m='203352'>the</span> <span m='203663'>partial</span>\
  \ <span m='203974'>products,</span> <span m='204284'>we'll</span> <span m='204595'>need</span>\
  \ <span m='204906'>to</span> <span m='205216'>sign-extend</span> <span m='205527'>each</span>\
  \ <span m='205838'>of</span> <span m='206148'>the</span> <span m='206459'>N-bit</span>\
  \ <span m='206770'>partial</span> <span m='207221'>products</span> <span m='207672'>to</span>\
  \ <span m='208123'>the</span> <span m='208574'>full</span> <span m='209025'>N+M-bit</span>\
  \ <span m='209476'>width</span> <span m='209927'>of</span> <span m='210378'>the</span>\
  \ <span m='210829'>addition.</span> </p><p><span m='211280'>This</span> <span m='211579'>will</span>\
  \ <span m='211878'>ensure</span> <span m='212178'>that</span> <span m='212477'>a</span>\
  \ <span m='212776'>negative</span> <span m='213076'>partial</span> <span m='213375'>product</span>\
  \ <span m='213674'>is</span> <span m='213974'>properly</span> <span m='214273'>treated</span>\
  \ <span m='214572'>when</span> <span m='214872'>doing</span> <span m='215171'>the</span>\
  \ <span m='215470'>addition.</span> </p><p><span m='215770'>And,</span> <span m='216101'>of</span>\
  \ <span m='216432'>course,</span> <span m='216764'>since</span> <span m='217095'>the</span>\
  \ <span m='217426'>high-order</span> <span m='217758'>bit</span> <span m='218089'>of</span>\
  \ <span m='218420'>the</span> <span m='218752'>multiplier</span> <span m='219083'>has</span>\
  \ <span m='219414'>a</span> <span m='219746'>negative</span> <span m='220077'>weight,</span>\
  \ <span m='220408'>we'd</span> <span m='220740'>subtract</span> <span m='221271'>instead</span>\
  \ <span m='221802'>of</span> <span m='222333'>add</span> <span m='222864'>the</span>\
  \ <span m='223395'>last</span> <span m='223926'>partial</span> <span m='224457'>product.</span>\
  \ </p><p><span m='224989'>Now</span> <span m='225309'>for</span> <span m='225629'>the</span>\
  \ <span m='225949'>clever</span> <span m='226269'>bit.</span> </p><p><span m='226590'>We'll</span>\
  \ <span m='226858'>add</span> <span m='227127'>1's</span> <span m='227396'>to</span>\
  \ <span m='227665'>various</span> <span m='227934'>of</span> <span m='228202'>the</span>\
  \ <span m='228471'>columns</span> <span m='228740'>and</span> <span m='229009'>then</span>\
  \ <span m='229278'>subtract</span> <span m='229547'>them</span> <span m='229815'>later,</span>\
  \ <span m='230084'>with</span> <span m='230353'>the</span> <span m='230622'>goal</span>\
  \ <span m='230891'>of</span> <span m='231160'>eliminating</span> <span m='231492'>all</span>\
  \ <span m='231824'>the</span> <span m='232156'>extra</span> <span m='232488'>additions</span>\
  \ <span m='232821'>caused</span> <span m='233153'>by</span> <span m='233485'>the</span>\
  \ <span m='233817'>sign-extension.</span> </p><p><span m='234150'>We'll</span> <span\
  \ m='234561'>also</span> <span m='234973'>rewrite</span> <span m='235384'>the</span>\
  \ <span m='235796'>subtraction</span> <span m='236207'>of</span> <span m='236619'>the</span>\
  \ <span m='237030'>last</span> <span m='237442'>partial</span> <span m='237853'>product</span>\
  \ <span m='238265'>as</span> <span m='238676'>first</span> <span m='239088'>complementing</span>\
  \ <span m='239500'>the</span> <span m='239985'>partial</span> <span m='240471'>product</span>\
  \ <span m='240957'>and</span> <span m='241442'>then</span> <span m='241928'>adding</span>\
  \ <span m='242414'>1.</span> </p><p><span m='242900'>This</span> <span m='243294'>is</span>\
  \ <span m='243688'>all</span> <span m='244082'>a</span> <span m='244477'>bit</span>\
  \ <span m='244871'>mysterious</span> <span m='245265'>but\u2026</span> <span m='245660'>Here</span>\
  \ <span m='246042'>in</span> <span m='246425'>step</span> <span m='246808'>3</span>\
  \ <span m='247191'>we</span> <span m='247573'>see</span> <span m='247956'>the</span>\
  \ <span m='248339'>effect</span> <span m='248722'>of</span> <span m='249105'>all</span>\
  \ <span m='249487'>the</span> <span m='249870'>step</span> <span m='250253'>2</span>\
  \ <span m='250636'>machinations.</span> </p><p><span m='251019'>Let's</span> <span\
  \ m='251413'>look</span> <span m='251808'>at</span> <span m='252202'>the</span>\
  \ <span m='252597'>high</span> <span m='252992'>order</span> <span m='253386'>bit</span>\
  \ <span m='253781'>of</span> <span m='254175'>the</span> <span m='254570'>first</span>\
  \ <span m='254965'>partial</span> <span m='255359'>product</span> <span m='255754'>X3Y0.</span>\
  \ </p><p><span m='256149'>If</span> <span m='256552'>that</span> <span m='256955'>partial</span>\
  \ <span m='257358'>product</span> <span m='257761'>is</span> <span m='258164'>non-negative,</span>\
  \ <span m='258567'>X3Y0</span> <span m='258970'>is</span> <span m='259374'>a</span>\
  \ <span m='259777'>0,</span> <span m='260180'>so</span> <span m='260583'>all</span>\
  \ <span m='260986'>the</span> <span m='261389'>sign-extension</span> <span m='261792'>bits</span>\
  \ <span m='262195'>are</span> <span m='262599'>0</span> <span m='263061'>and</span>\
  \ <span m='263523'>can</span> <span m='263985'>be</span> <span m='264447'>removed.</span>\
  \ </p><p><span m='264909'>The</span> <span m='265321'>effect</span> <span m='265734'>of</span>\
  \ <span m='266147'>adding</span> <span m='266560'>a</span> <span m='266973'>1</span>\
  \ <span m='267386'>in</span> <span m='267799'>that</span> <span m='268211'>position</span>\
  \ <span m='268624'>is</span> <span m='269037'>to</span> <span m='269450'>simply</span>\
  \ <span m='269863'>complement</span> <span m='270276'>X3Y0.</span> </p><p><span\
  \ m='270689'>On</span> <span m='271047'>the</span> <span m='271405'>other</span>\
  \ <span m='271763'>hand,</span> <span m='272121'>if</span> <span m='272480'>that</span>\
  \ <span m='272838'>partial</span> <span m='273196'>product</span> <span m='273554'>is</span>\
  \ <span m='273913'>negative,</span> <span m='274271'>X3Y0</span> <span m='274629'>is</span>\
  \ <span m='274987'>1,</span> <span m='275346'>and</span> <span m='275704'>all</span>\
  \ <span m='276062'>the</span> <span m='276420'>sign-extension</span> <span m='276779'>bits</span>\
  \ <span m='277219'>are</span> <span m='277659'>1.</span> </p><p><span m='278099'>Now</span>\
  \ <span m='278412'>when</span> <span m='278725'>we</span> <span m='279038'>add</span>\
  \ <span m='279351'>a</span> <span m='279665'>1</span> <span m='279978'>in</span>\
  \ <span m='280291'>that</span> <span m='280604'>position,</span> <span m='280918'>we</span>\
  \ <span m='281231'>complement</span> <span m='281544'>the</span> <span m='281857'>X3Y0</span>\
  \ <span m='282170'>bit</span> <span m='282484'>back</span> <span m='282797'>to</span>\
  \ <span m='283110'>0,</span> <span m='283423'>but</span> <span m='283737'>we</span>\
  \ <span m='284050'>also</span> <span m='284363'>get</span> <span m='284676'>a</span>\
  \ <span m='284990'>carry-out.</span> </p><p><span m='286819'>When</span> <span m='287108'>that's</span>\
  \ <span m='287397'>added</span> <span m='287687'>to</span> <span m='287976'>the</span>\
  \ <span m='288266'>first</span> <span m='288555'>sign-extension</span> <span m='288845'>bit</span>\
  \ <span m='289134'>(which</span> <span m='289424'>is</span> <span m='289713'>itself</span>\
  \ <span m='290003'>a</span> <span m='290292'>1),</span> <span m='290582'>we</span>\
  \ <span m='290871'>get</span> <span m='291161'>zero</span> <span m='291450'>with</span>\
  \ <span m='291740'>another</span> <span m='292479'>carry-out.</span> </p><p><span\
  \ m='293219'>And</span> <span m='293580'>so</span> <span m='293941'>on,</span> <span\
  \ m='294302'>with</span> <span m='294664'>all</span> <span m='295025'>the</span>\
  \ <span m='295386'>sign-extension</span> <span m='295747'>bits</span> <span m='296109'>eventually</span>\
  \ <span m='296470'>getting</span> <span m='296831'>flipped</span> <span m='297192'>to</span>\
  \ <span m='297554'>0</span> <span m='297915'>as</span> <span m='298276'>the</span>\
  \ <span m='298637'>carry</span> <span m='298999'>ripples</span> <span m='299644'>to</span>\
  \ <span m='300289'>the</span> <span m='300934'>end.</span> </p><p><span m='301580'>Again</span>\
  \ <span m='302058'>the</span> <span m='302537'>net</span> <span m='303016'>effect</span>\
  \ <span m='303495'>of</span> <span m='303973'>adding</span> <span m='304452'>a</span>\
  \ <span m='304931'>1</span> <span m='305410'>in</span> <span m='305888'>that</span>\
  \ <span m='306367'>position</span> <span m='306846'>is</span> <span m='307325'>to</span>\
  \ <span m='307803'>simply</span> <span m='308282'>complement</span> <span m='308761'>X3Y0.</span>\
  \ </p><p><span m='309240'>We</span> <span m='309535'>do</span> <span m='309831'>the</span>\
  \ <span m='310126'>same</span> <span m='310422'>for</span> <span m='310717'>all</span>\
  \ <span m='311013'>the</span> <span m='311308'>other</span> <span m='311604'>sign-extended</span>\
  \ <span m='311900'>partial</span> <span m='312195'>products,</span> <span m='312491'>leaving</span>\
  \ <span m='312786'>us</span> <span m='313082'>with</span> <span m='313377'>the</span>\
  \ <span m='313673'>results</span> <span m='313969'>shown</span> <span m='314624'>here.</span>\
  \ </p><p><span m='315279'>In</span> <span m='315503'>the</span> <span m='315727'>final</span>\
  \ <span m='315952'>step</span> <span m='316176'>we</span> <span m='316401'>do</span>\
  \ <span m='316625'>a</span> <span m='316850'>bit</span> <span m='317074'>of</span>\
  \ <span m='317299'>arithmetic</span> <span m='317523'>on</span> <span m='317747'>the</span>\
  \ <span m='317972'>remaining</span> <span m='318196'>constants</span> <span m='318421'>to</span>\
  \ <span m='318645'>end</span> <span m='318870'>up</span> <span m='319094'>with</span>\
  \ <span m='319319'>this</span> <span m='319663'>table</span> <span m='320007'>of</span>\
  \ <span m='320351'>work</span> <span m='320696'>to</span> <span m='321040'>be</span>\
  \ <span m='321384'>done.</span> </p><p><span m='321729'>Somewhat</span> <span m='322034'>to</span>\
  \ <span m='322340'>our</span> <span m='322646'>surprise,</span> <span m='322951'>this</span>\
  \ <span m='323257'>isn't</span> <span m='323563'>much</span> <span m='323869'>different</span>\
  \ <span m='324174'>than</span> <span m='324480'>the</span> <span m='324786'>original</span>\
  \ <span m='325091'>table</span> <span m='325397'>for</span> <span m='325703'>the</span>\
  \ <span m='326009'>unsigned</span> <span m='327089'>multiplication.</span> </p><p><span\
  \ m='328169'>There</span> <span m='328469'>are</span> <span m='328770'>a</span>\
  \ <span m='329070'>few</span> <span m='329371'>partial</span> <span m='329672'>product</span>\
  \ <span m='329972'>bits</span> <span m='330273'>that</span> <span m='330574'>need</span>\
  \ <span m='330874'>to</span> <span m='331175'>be</span> <span m='331475'>complemented,</span>\
  \ <span m='331776'>and</span> <span m='332077'>two</span> <span m='332377'>1-bits</span>\
  \ <span m='332678'>that</span> <span m='332979'>need</span> <span m='333339'>to</span>\
  \ <span m='333699'>be</span> <span m='334059'>added</span> <span m='334419'>to</span>\
  \ <span m='334779'>particular</span> <span m='335139'>columns.</span> </p><p><span\
  \ m='335499'>The</span> <span m='335942'>resulting</span> <span m='336385'>circuitry</span>\
  \ <span m='336829'>is</span> <span m='337272'>shown</span> <span m='337715'>here.</span>\
  \ </p><p><span m='338159'>We've</span> <span m='338472'>changed</span> <span m='338785'>some</span>\
  \ <span m='339099'>of</span> <span m='339412'>the</span> <span m='339726'>AND</span>\
  \ <span m='340039'>gates</span> <span m='340352'>to</span> <span m='340666'>NAND</span>\
  \ <span m='340979'>gates</span> <span m='341293'>to</span> <span m='341606'>perform</span>\
  \ <span m='341919'>the</span> <span m='342233'>necessary</span> <span m='342546'>complements.</span>\
  \ </p><p><span m='342860'>And</span> <span m='343092'>we've</span> <span m='343325'>changed</span>\
  \ <span m='343558'>the</span> <span m='343791'>logic</span> <span m='344024'>necessary</span>\
  \ <span m='344257'>to</span> <span m='344490'>deal</span> <span m='344723'>with</span>\
  \ <span m='344955'>the</span> <span m='345188'>two</span> <span m='345421'>1-bits</span>\
  \ <span m='345654'>that</span> <span m='345887'>needed</span> <span m='346120'>to</span>\
  \ <span m='346353'>be</span> <span m='346586'>added</span> <span m='346819'>in.</span>\
  \ </p><p><span m='348869'>The</span> <span m='349265'>colored</span> <span m='349662'>elements</span>\
  \ <span m='350059'>show</span> <span m='350456'>the</span> <span m='350853'>changes</span>\
  \ <span m='351250'>made</span> <span m='351647'>from</span> <span m='352044'>the</span>\
  \ <span m='352441'>original</span> <span m='352838'>unsigned</span> <span m='353235'>multiplier</span>\
  \ <span m='353632'>circuitry.</span> </p><p><span m='354029'>Basically,</span> <span\
  \ m='354477'>the</span> <span m='354925'>circuit</span> <span m='355374'>for</span>\
  \ <span m='355822'>multiplying</span> <span m='356270'>two's</span> <span m='356719'>complement</span>\
  \ <span m='357167'>operands</span> <span m='357615'>has</span> <span m='358064'>the</span>\
  \ <span m='358512'>same</span> <span m='358960'>latency,</span> <span m='359409'>throughput</span>\
  \ <span m='359785'>and</span> <span m='360161'>hardware</span> <span m='360537'>costs</span>\
  \ <span m='360914'>as</span> <span m='361290'>the</span> <span m='361666'>original</span>\
  \ <span m='362042'>circuitry.</span> </p>"
type: course
uid: 113a4c0e66c4e62aa9ca15057f2820bc

---
None