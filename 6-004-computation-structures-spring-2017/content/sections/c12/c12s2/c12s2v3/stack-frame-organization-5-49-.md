---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: 00KTZ7t_rWw
  parent_uid: 3d5b466a869f20f9140d205977ae506a
  title: Video-YouTube-Stream
  type: Video
  uid: 31a63313601a6bbbea897bc40488566b
- id: 3Play-3Play YouTube id-Stream
  media_location: 00KTZ7t_rWw
  parent_uid: 3d5b466a869f20f9140d205977ae506a
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: e9b35772825ddb0037cdb8a9766a98e5
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/00KTZ7t_rWw/default.jpg
  parent_uid: 3d5b466a869f20f9140d205977ae506a
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: ba324519e2b6b30df3d63d09f933b60c
- id: 00KTZ7t_rWw.srt
  parent_uid: 3d5b466a869f20f9140d205977ae506a
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v3/stack-frame-organization-5-49-/00KTZ7t_rWw.srt
  title: 3play caption file
  type: null
  uid: 68a6907c3ce0962b15d2c2644073a9c4
- id: 00KTZ7t_rWw.pdf
  parent_uid: 3d5b466a869f20f9140d205977ae506a
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v3/stack-frame-organization-5-49-/00KTZ7t_rWw.pdf
  title: 3play pdf file
  type: null
  uid: b4eb0fa804ac49633fe6e6b201c6603f
- id: Caption-3Play YouTube id-SRT
  parent_uid: 3d5b466a869f20f9140d205977ae506a
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 9cd26fd4f4f41026588c09f4d512eac2
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 3d5b466a869f20f9140d205977ae506a
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 20d6b7c88272e5444e043d8e6484dc54
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_12-02-03_300k.mp4
  parent_uid: 3d5b466a869f20f9140d205977ae506a
  title: Video-Internet Archive-MP4
  type: Video
  uid: da8878c8cc9fc62ee353d18cdd4dead1
inline_embed_id: 45741848stackframeorganization54978723615
layout: video
order_index: null
parent_uid: 0c79cf1c18f780dcda7ea2663252a83c
related_resources_text: ''
short_url: stack-frame-organization-5-49-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c12/c12s2/c12s2v3/stack-frame-organization-5-49-
template_type: Embed
title: Stack Frame Organization (5:49)
transcript: "<p><span m='250'>We'll</span> <span m='630'>use</span> <span m='1011'>the</span>\
  \ <span m='1392'>stack</span> <span m='1773'>to</span> <span m='2154'>hold</span>\
  \ <span m='2535'>a</span> <span m='2916'>procedure's</span> <span m='3297'>activation</span>\
  \ <span m='3678'>record.</span> </p><p><span m='4059'>That</span> <span m='4354'>includes</span>\
  \ <span m='4650'>the</span> <span m='4945'>values</span> <span m='5241'>of</span>\
  \ <span m='5536'>the</span> <span m='5832'>arguments</span> <span m='6127'>to</span>\
  \ <span m='6423'>the</span> <span m='6718'>procedure</span> <span m='7014'>call.</span>\
  \ </p><p><span m='7310'>We'll</span> <span m='7659'>allocate</span> <span m='8008'>words</span>\
  \ <span m='8358'>on</span> <span m='8707'>the</span> <span m='9056'>stack</span>\
  \ <span m='9406'>to</span> <span m='9755'>hold</span> <span m='10104'>the</span>\
  \ <span m='10454'>values</span> <span m='10803'>of</span> <span m='11152'>the</span>\
  \ <span m='11502'>procedure's</span> <span m='11851'>local</span> <span m='12200'>variables,</span>\
  \ <span m='12550'>assuming</span> <span m='12892'>we</span> <span m='13235'>don't</span>\
  \ <span m='13578'>keep</span> <span m='13921'>them</span> <span m='14264'>in</span>\
  \ <span m='14607'>registers.</span> </p><p><span m='14950'>And</span> <span m='15251'>we'll</span>\
  \ <span m='15553'>use</span> <span m='15855'>the</span> <span m='16157'>stack</span>\
  \ <span m='16458'>to</span> <span m='16760'>save</span> <span m='17062'>the</span>\
  \ <span m='17364'>return</span> <span m='17665'>address</span> <span m='17967'>(passed</span>\
  \ <span m='18269'>in</span> <span m='18571'>LP)</span> <span m='18872'>so</span>\
  \ <span m='19174'>the</span> <span m='19476'>procedure</span> <span m='19778'>can</span>\
  \ <span m='20080'>make</span> <span m='20673'>nested</span> <span m='21266'>procedure</span>\
  \ <span m='21860'>calls</span> <span m='22453'>without</span> <span m='23046'>overwriting</span>\
  \ <span m='23640'>its</span> <span m='24233'>return</span> <span m='24826'>address.</span>\
  \ </p><p><span m='25420'>The</span> <span m='25803'>responsibility</span> <span\
  \ m='26186'>for</span> <span m='26569'>allocating</span> <span m='26952'>and</span>\
  \ <span m='27335'>deallocating</span> <span m='27718'>the</span> <span m='28101'>activation</span>\
  \ <span m='28484'>record</span> <span m='28867'>will</span> <span m='29250'>be</span>\
  \ <span m='29633'>shared</span> <span m='30016'>between</span> <span m='30400'>the</span>\
  \ <span m='30896'>calling</span> <span m='31392'>procedure</span> <span m='31889'>(the</span>\
  \ <span m='32385'>\"caller\")</span> <span m='32881'>and</span> <span m='33378'>the</span>\
  \ <span m='33874'>called</span> <span m='34370'>procedure</span> <span m='34867'>(the</span>\
  \ <span m='35363'>\"callee\").</span> </p><p><span m='35860'>The</span> <span m='36223'>caller</span>\
  \ <span m='36586'>is</span> <span m='36949'>responsible</span> <span m='37312'>for</span>\
  \ <span m='37675'>evaluating</span> <span m='38038'>the</span> <span m='38401'>argument</span>\
  \ <span m='38764'>expressions</span> <span m='39127'>and</span> <span m='39490'>saving</span>\
  \ <span m='39853'>their</span> <span m='40216'>values</span> <span m='40579'>in</span>\
  \ <span m='40982'>the</span> <span m='41385'>activation</span> <span m='41789'>record</span>\
  \ <span m='42192'>being</span> <span m='42596'>built</span> <span m='42999'>on</span>\
  \ <span m='43403'>the</span> <span m='43806'>stack.</span> </p><p><span m='44210'>We'll</span>\
  \ <span m='44522'>adopt</span> <span m='44834'>the</span> <span m='45146'>convention</span>\
  \ <span m='45458'>that</span> <span m='45770'>the</span> <span m='46082'>arguments</span>\
  \ <span m='46394'>are</span> <span m='46706'>pushed</span> <span m='47018'>in</span>\
  \ <span m='47330'>reverse</span> <span m='47642'>order,</span> <span m='47954'>i.e.,</span>\
  \ <span m='48266'>the</span> <span m='48578'>first</span> <span m='48890'>argument</span>\
  \ <span m='49216'>will</span> <span m='49542'>be</span> <span m='49869'>the</span>\
  \ <span m='50195'>last</span> <span m='50521'>to</span> <span m='50848'>be</span>\
  \ <span m='51174'>pushed</span> <span m='51500'>on</span> <span m='51827'>the</span>\
  \ <span m='52153'>stack.</span> </p><p><span m='52480'>We'll</span> <span m='52880'>explain</span>\
  \ <span m='53280'>why</span> <span m='53680'>we</span> <span m='54080'>made</span>\
  \ <span m='54480'>this</span> <span m='54880'>choice</span> <span m='55280'>in</span>\
  \ <span m='55680'>a</span> <span m='56080'>couple</span> <span m='56480'>of</span>\
  \ <span m='56880'>slides\u2026</span> <span m='57280'>The</span> <span m='57665'>code</span>\
  \ <span m='58050'>compiled</span> <span m='58435'>for</span> <span m='58821'>a</span>\
  \ <span m='59206'>procedure</span> <span m='59591'>involves</span> <span m='59977'>a</span>\
  \ <span m='60362'>sequence</span> <span m='60747'>of</span> <span m='61133'>expression</span>\
  \ <span m='61518'>evaluations,</span> <span m='61903'>each</span> <span m='62289'>followed</span>\
  \ <span m='62709'>by</span> <span m='63129'>a</span> <span m='63549'>PUSH</span>\
  \ <span m='63969'>to</span> <span m='64389'>save</span> <span m='64809'>the</span>\
  \ <span m='65229'>calculated</span> <span m='65649'>value</span> <span m='66069'>on</span>\
  \ <span m='66489'>the</span> <span m='66909'>stack.</span> </p><p><span m='67330'>So</span>\
  \ <span m='67675'>when</span> <span m='68020'>the</span> <span m='68365'>callee</span>\
  \ <span m='68711'>starts</span> <span m='69056'>execution,</span> <span m='69401'>the</span>\
  \ <span m='69747'>top</span> <span m='70092'>of</span> <span m='70437'>the</span>\
  \ <span m='70782'>stack</span> <span m='71128'>contains</span> <span m='71473'>the</span>\
  \ <span m='71818'>value</span> <span m='72164'>of</span> <span m='72509'>the</span>\
  \ <span m='72854'>first</span> <span m='73200'>argument,</span> <span m='73644'>the</span>\
  \ <span m='74088'>next</span> <span m='74532'>word</span> <span m='74977'>down</span>\
  \ <span m='75421'>the</span> <span m='75865'>value</span> <span m='76310'>of</span>\
  \ <span m='76754'>the</span> <span m='77198'>second</span> <span m='77642'>argument,</span>\
  \ <span m='78087'>and</span> <span m='78531'>so</span> <span m='78975'>on.</span>\
  \ </p><p><span m='79420'>After</span> <span m='79737'>the</span> <span m='80054'>argument</span>\
  \ <span m='80371'>values,</span> <span m='80688'>if</span> <span m='81005'>any,</span>\
  \ <span m='81322'>have</span> <span m='81639'>been</span> <span m='81956'>pushed</span>\
  \ <span m='82273'>on</span> <span m='82590'>the</span> <span m='82907'>stack,</span>\
  \ <span m='83224'>there's</span> <span m='83541'>a</span> <span m='83858'>BR</span>\
  \ <span m='84175'>to</span> <span m='84492'>transfer</span> <span m='84810'>control</span>\
  \ <span m='85172'>to</span> <span m='85534'>the</span> <span m='85896'>procedure's</span>\
  \ <span m='86259'>entry</span> <span m='86621'>point,</span> <span m='86983'>saving</span>\
  \ <span m='87346'>the</span> <span m='87708'>address</span> <span m='88070'>of</span>\
  \ <span m='88433'>the</span> <span m='88795'>instruction</span> <span m='89157'>following</span>\
  \ <span m='89520'>the</span> <span m='89964'>BR</span> <span m='90408'>in</span>\
  \ <span m='90852'>the</span> <span m='91296'>linkage</span> <span m='91740'>pointer,</span>\
  \ <span m='92184'>R28,</span> <span m='92628'>a</span> <span m='93072'>register</span>\
  \ <span m='93516'>that</span> <span m='93960'>we'll</span> <span m='94404'>dedicate</span>\
  \ <span m='94848'>to</span> <span m='95292'>that</span> <span m='95736'>purpose.</span>\
  \ </p><p><span m='96180'>When</span> <span m='96540'>the</span> <span m='96900'>callee</span>\
  \ <span m='97260'>returns</span> <span m='97620'>and</span> <span m='97980'>execution</span>\
  \ <span m='98340'>resumes</span> <span m='98700'>in</span> <span m='99060'>the</span>\
  \ <span m='99420'>caller,</span> <span m='99780'>a</span> <span m='100140'>DEALLOCATE</span>\
  \ <span m='100500'>is</span> <span m='100860'>used</span> <span m='101220'>to</span>\
  \ <span m='101580'>remove</span> <span m='101940'>all</span> <span m='102461'>the</span>\
  \ <span m='102983'>argument</span> <span m='103505'>values</span> <span m='104027'>from</span>\
  \ <span m='104549'>the</span> <span m='105070'>stack,</span> <span m='105592'>preserving</span>\
  \ <span m='106114'>stack</span> <span m='106636'>discipline.</span> </p><p><span\
  \ m='107158'>So</span> <span m='107536'>that's</span> <span m='107914'>the</span>\
  \ <span m='108292'>code</span> <span m='108670'>the</span> <span m='109048'>compiler</span>\
  \ <span m='109426'>generates</span> <span m='109804'>for</span> <span m='110182'>the</span>\
  \ <span m='110560'>procedure.</span> </p><p><span m='110939'>The</span> <span m='111301'>rest</span>\
  \ <span m='111663'>of</span> <span m='112025'>the</span> <span m='112387'>work</span>\
  \ <span m='112749'>happens</span> <span m='113111'>in</span> <span m='113473'>the</span>\
  \ <span m='113835'>called</span> <span m='114197'>procedure.</span> </p><p><span\
  \ m='114560'>The</span> <span m='114849'>code</span> <span m='115138'>at</span>\
  \ <span m='115428'>the</span> <span m='115717'>start</span> <span m='116006'>of</span>\
  \ <span m='116296'>the</span> <span m='116585'>called</span> <span m='116874'>procedure</span>\
  \ <span m='117164'>completes</span> <span m='117453'>the</span> <span m='117742'>allocation</span>\
  \ <span m='118032'>of</span> <span m='118321'>the</span> <span m='118610'>activation</span>\
  \ <span m='118900'>record.</span> </p><p><span m='120040'>Since</span> <span m='120344'>when</span>\
  \ <span m='120649'>we're</span> <span m='120954'>done</span> <span m='121258'>the</span>\
  \ <span m='121563'>activation</span> <span m='121868'>record</span> <span m='122172'>will</span>\
  \ <span m='122477'>occupy</span> <span m='122782'>a</span> <span m='123086'>bunch</span>\
  \ <span m='123391'>of</span> <span m='123696'>consecutive</span> <span m='124000'>words</span>\
  \ <span m='124305'>on</span> <span m='124610'>the</span> <span m='124948'>stack,</span>\
  \ <span m='125286'>we'll</span> <span m='125624'>sometimes</span> <span m='125962'>refer</span>\
  \ <span m='126301'>to</span> <span m='126639'>the</span> <span m='126977'>activation</span>\
  \ <span m='127315'>record</span> <span m='127654'>as</span> <span m='127992'>a</span>\
  \ <span m='128330'>\"stack</span> <span m='128668'>frame\"</span> <span m='129007'>to</span>\
  \ <span m='129345'>remind</span> <span m='129683'>us</span> <span m='130021'>of</span>\
  \ <span m='130360'>where</span> <span m='130863'>it</span> <span m='131366'>lives.</span>\
  \ </p><p><span m='131870'>The</span> <span m='132172'>first</span> <span m='132474'>action</span>\
  \ <span m='132776'>is</span> <span m='133078'>to</span> <span m='133380'>save</span>\
  \ <span m='133682'>the</span> <span m='133984'>return</span> <span m='134286'>address</span>\
  \ <span m='134588'>found</span> <span m='134890'>in</span> <span m='135192'>the</span>\
  \ <span m='135494'>LP</span> <span m='135796'>register.</span> </p><p><span m='136099'>This</span>\
  \ <span m='136456'>frees</span> <span m='136813'>up</span> <span m='137170'>LP</span>\
  \ <span m='137528'>to</span> <span m='137885'>be</span> <span m='138242'>used</span>\
  \ <span m='138599'>by</span> <span m='138957'>any</span> <span m='139314'>nested</span>\
  \ <span m='139671'>procedure</span> <span m='140029'>calls</span> <span m='140386'>in</span>\
  \ <span m='140743'>the</span> <span m='141100'>body</span> <span m='141458'>of</span>\
  \ <span m='141815'>the</span> <span m='142172'>callee.</span> </p><p><span m='142530'>In</span>\
  \ <span m='142826'>order</span> <span m='143123'>to</span> <span m='143420'>make</span>\
  \ <span m='143717'>it</span> <span m='144014'>easy</span> <span m='144311'>to</span>\
  \ <span m='144608'>access</span> <span m='144905'>values</span> <span m='145202'>stored</span>\
  \ <span m='145499'>in</span> <span m='145796'>the</span> <span m='146093'>activation</span>\
  \ <span m='146390'>record,</span> <span m='146687'>we'll</span> <span m='146984'>dedicate</span>\
  \ <span m='147281'>another</span> <span m='147694'>register</span> <span m='148107'>called</span>\
  \ <span m='148520'>the</span> <span m='148933'>\"base</span> <span m='149346'>pointer\"\
  </span> <span m='149759'>(BP</span> <span m='150172'>=</span> <span m='150585'>R27)</span>\
  \ <span m='150998'>which</span> <span m='151411'>will</span> <span m='151824'>point</span>\
  \ <span m='152237'>to</span> <span m='152650'>the</span> <span m='153063'>stack</span>\
  \ <span m='153476'>frame</span> <span m='153890'>we're</span> <span m='154785'>building.</span>\
  \ </p><p><span m='155680'>So</span> <span m='156019'>as</span> <span m='156358'>we</span>\
  \ <span m='156698'>enter</span> <span m='157037'>the</span> <span m='157377'>procedure,</span>\
  \ <span m='157716'>the</span> <span m='158055'>code</span> <span m='158395'>saves</span>\
  \ <span m='158734'>the</span> <span m='159074'>pointer</span> <span m='159413'>to</span>\
  \ <span m='159752'>the</span> <span m='160092'>caller's</span> <span m='160431'>stack</span>\
  \ <span m='160771'>frame,</span> <span m='161110'>and</span> <span m='161450'>then</span>\
  \ <span m='161812'>uses</span> <span m='162175'>the</span> <span m='162538'>current</span>\
  \ <span m='162901'>value</span> <span m='163263'>of</span> <span m='163626'>the</span>\
  \ <span m='163989'>stack</span> <span m='164352'>pointer</span> <span m='164715'>to</span>\
  \ <span m='165077'>make</span> <span m='165440'>BP</span> <span m='165803'>point</span>\
  \ <span m='166166'>to</span> <span m='166528'>the</span> <span m='166891'>current</span>\
  \ <span m='167254'>stack</span> <span m='167617'>frame.</span> </p><p><span m='167980'>We'll</span>\
  \ <span m='168262'>see</span> <span m='168544'>how</span> <span m='168826'>we</span>\
  \ <span m='169108'>use</span> <span m='169390'>BP</span> <span m='169672'>in</span>\
  \ <span m='169954'>just</span> <span m='170236'>a</span> <span m='170518'>moment.</span>\
  \ </p><p><span m='170800'>Now</span> <span m='171089'>the</span> <span m='171378'>code</span>\
  \ <span m='171668'>will</span> <span m='171957'>allocate</span> <span m='172247'>words</span>\
  \ <span m='172536'>in</span> <span m='172825'>the</span> <span m='173115'>stack</span>\
  \ <span m='173404'>frame</span> <span m='173694'>to</span> <span m='173983'>hold</span>\
  \ <span m='174272'>the</span> <span m='174562'>values</span> <span m='174851'>for</span>\
  \ <span m='175141'>the</span> <span m='175430'>callee's</span> <span m='175720'>local</span>\
  \ <span m='176212'>variables,</span> <span m='176705'>if</span> <span m='177197'>any.</span>\
  \ </p><p><span m='177690'>Finally,</span> <span m='178018'>the</span> <span m='178347'>callee</span>\
  \ <span m='178676'>needs</span> <span m='179005'>to</span> <span m='179333'>save</span>\
  \ <span m='179662'>the</span> <span m='179991'>values</span> <span m='180320'>of</span>\
  \ <span m='180648'>any</span> <span m='180977'>registers</span> <span m='181306'>it</span>\
  \ <span m='181635'>will</span> <span m='181963'>use</span> <span m='182292'>when</span>\
  \ <span m='182621'>executing</span> <span m='182950'>the</span> <span m='183279'>rest</span>\
  \ <span m='183609'>of</span> <span m='183939'>its</span> <span m='184269'>code.</span>\
  \ </p><p><span m='184599'>These</span> <span m='184967'>saved</span> <span m='185336'>values</span>\
  \ <span m='185704'>can</span> <span m='186073'>be</span> <span m='186442'>used</span>\
  \ <span m='186810'>to</span> <span m='187179'>restore</span> <span m='187548'>the</span>\
  \ <span m='187916'>register</span> <span m='188285'>values</span> <span m='188654'>just</span>\
  \ <span m='189022'>before</span> <span m='189391'>returning</span> <span m='189760'>to</span>\
  \ <span m='190193'>the</span> <span m='190626'>caller.</span> </p><p><span m='191060'>This</span>\
  \ <span m='191496'>is</span> <span m='191932'>called</span> <span m='192369'>the</span>\
  \ <span m='192805'>\"callee</span> <span m='193242'>saves\"</span> <span m='193678'>convention</span>\
  \ <span m='194115'>where</span> <span m='194551'>the</span> <span m='194987'>callee</span>\
  \ <span m='195424'>guarantees</span> <span m='195860'>that</span> <span m='196297'>all</span>\
  \ <span m='196733'>register</span> <span m='197170'>values</span> <span m='197641'>will</span>\
  \ <span m='198112'>be</span> <span m='198583'>preserved</span> <span m='199055'>across</span>\
  \ <span m='199526'>the</span> <span m='199997'>procedure</span> <span m='200468'>call.</span>\
  \ </p><p><span m='200940'>With</span> <span m='201238'>this</span> <span m='201537'>convention,</span>\
  \ <span m='201836'>the</span> <span m='202135'>code</span> <span m='202433'>in</span>\
  \ <span m='202732'>the</span> <span m='203031'>caller</span> <span m='203330'>can</span>\
  \ <span m='203628'>assume</span> <span m='203927'>any</span> <span m='204226'>values</span>\
  \ <span m='204525'>it</span> <span m='204823'>placed</span> <span m='205122'>in</span>\
  \ <span m='205421'>registers</span> <span m='205720'>before</span> <span m='206142'>a</span>\
  \ <span m='206564'>nested</span> <span m='206986'>procedure</span> <span m='207408'>call</span>\
  \ <span m='207830'>will</span> <span m='208252'>still</span> <span m='208675'>be</span>\
  \ <span m='209097'>there</span> <span m='209519'>when</span> <span m='209941'>the</span>\
  \ <span m='210363'>nested</span> <span m='210785'>call</span> <span m='211207'>returns.</span>\
  \ </p><p><span m='211630'>Note</span> <span m='212021'>that</span> <span m='212413'>dedicating</span>\
  \ <span m='212804'>a</span> <span m='213196'>register</span> <span m='213587'>as</span>\
  \ <span m='213979'>the</span> <span m='214371'>base</span> <span m='214762'>pointer</span>\
  \ <span m='215154'>isn't</span> <span m='215545'>strictly</span> <span m='215937'>necessary.</span>\
  \ </p><p><span m='216329'>All</span> <span m='216602'>accesses</span> <span m='216875'>to</span>\
  \ <span m='217148'>the</span> <span m='217421'>values</span> <span m='217694'>on</span>\
  \ <span m='217967'>the</span> <span m='218240'>stack</span> <span m='218513'>can</span>\
  \ <span m='218786'>be</span> <span m='219059'>made</span> <span m='219332'>relative</span>\
  \ <span m='219605'>to</span> <span m='219878'>the</span> <span m='220151'>stack</span>\
  \ <span m='220424'>pointer,</span> <span m='220697'>but</span> <span m='220970'>the</span>\
  \ <span m='221336'>offsets</span> <span m='221703'>from</span> <span m='222070'>SP</span>\
  \ <span m='222437'>will</span> <span m='222804'>change</span> <span m='223171'>as</span>\
  \ <span m='223538'>values</span> <span m='223905'>are</span> <span m='224271'>PUSHed</span>\
  \ <span m='224638'>and</span> <span m='225005'>POPed</span> <span m='225372'>from</span>\
  \ <span m='225739'>the</span> <span m='226106'>stack,</span> <span m='226473'>e.g.,</span>\
  \ <span m='226840'>during</span> <span m='227600'>procedure</span> <span m='228360'>calls.</span>\
  \ </p><p><span m='229120'>It</span> <span m='229547'>will</span> <span m='229975'>be</span>\
  \ <span m='230403'>easier</span> <span m='230830'>to</span> <span m='231258'>understand</span>\
  \ <span m='231686'>the</span> <span m='232114'>generated</span> <span m='232541'>code</span>\
  \ <span m='232969'>if</span> <span m='233397'>we</span> <span m='233824'>use</span>\
  \ <span m='234252'>BP</span> <span m='234680'>for</span> <span m='235108'>all</span>\
  \ <span m='235535'>stack</span> <span m='235963'>frame</span> <span m='236391'>references.</span>\
  \ </p><p><span m='236819'>Let's</span> <span m='237129'>return</span> <span m='237439'>to</span>\
  \ <span m='237749'>the</span> <span m='238059'>question</span> <span m='238369'>about</span>\
  \ <span m='238679'>the</span> <span m='238989'>order</span> <span m='239299'>of</span>\
  \ <span m='239609'>argument</span> <span m='239919'>values</span> <span m='240229'>in</span>\
  \ <span m='240539'>the</span> <span m='240849'>stack</span> <span m='241159'>frame.</span>\
  \ </p><p><span m='241470'>We</span> <span m='241736'>adopted</span> <span m='242003'>the</span>\
  \ <span m='242270'>convention</span> <span m='242537'>of</span> <span m='242804'>PUSHing</span>\
  \ <span m='243070'>the</span> <span m='243337'>values</span> <span m='243604'>in</span>\
  \ <span m='243871'>reverse</span> <span m='244138'>order,</span> <span m='244404'>i.e.,</span>\
  \ <span m='244671'>where</span> <span m='244938'>the</span> <span m='245205'>value</span>\
  \ <span m='245472'>of</span> <span m='245739'>the</span> <span m='246090'>first</span>\
  \ <span m='246441'>argument</span> <span m='246792'>is</span> <span m='247143'>the</span>\
  \ <span m='247494'>last</span> <span m='247845'>one</span> <span m='248196'>to</span>\
  \ <span m='248547'>be</span> <span m='248898'>PUSHED.</span> </p><p><span m='249250'>So,</span>\
  \ <span m='249868'>why</span> <span m='250487'>PUSH</span> <span m='251106'>argument</span>\
  \ <span m='251725'>values</span> <span m='252343'>in</span> <span m='252962'>reverse</span>\
  \ <span m='253581'>order?</span> </p><p><span m='254200'>With</span> <span m='254534'>the</span>\
  \ <span m='254868'>arguments</span> <span m='255202'>PUSHed</span> <span m='255537'>in</span>\
  \ <span m='255871'>reverse</span> <span m='256205'>order,</span> <span m='256540'>the</span>\
  \ <span m='256874'>first</span> <span m='257208'>argument</span> <span m='257542'>(labeled</span>\
  \ <span m='257877'>\"arg</span> <span m='258211'>0\")</span> <span m='258545'>will</span>\
  \ <span m='258880'>be</span> <span m='259151'>at</span> <span m='259422'>a</span>\
  \ <span m='259693'>fixed</span> <span m='259965'>offset</span> <span m='260236'>from</span>\
  \ <span m='260507'>the</span> <span m='260778'>base</span> <span m='261050'>pointer</span>\
  \ <span m='261321'>regardless</span> <span m='261592'>of</span> <span m='261863'>the</span>\
  \ <span m='262135'>number</span> <span m='262406'>of</span> <span m='262677'>argument</span>\
  \ <span m='262948'>values</span> <span m='263220'>pushed</span> <span m='263729'>on</span>\
  \ <span m='264239'>the</span> <span m='264749'>stack.</span> </p><p><span m='265259'>The</span>\
  \ <span m='265539'>compiler</span> <span m='265819'>can</span> <span m='266099'>use</span>\
  \ <span m='266379'>a</span> <span m='266659'>simple</span> <span m='266939'>formula</span>\
  \ <span m='267219'>to</span> <span m='267499'>the</span> <span m='267779'>determine</span>\
  \ <span m='268059'>the</span> <span m='268339'>correct</span> <span m='268619'>BP</span>\
  \ <span m='268899'>offset</span> <span m='269179'>value</span> <span m='269459'>for</span>\
  \ <span m='269740'>any</span> <span m='270276'>particular</span> <span m='270813'>argument.</span>\
  \ </p><p><span m='271350'>So</span> <span m='271797'>the</span> <span m='272244'>first</span>\
  \ <span m='272692'>argument</span> <span m='273139'>is</span> <span m='273586'>at</span>\
  \ <span m='274034'>offset</span> <span m='274481'>-12,</span> <span m='274928'>the</span>\
  \ <span m='275376'>second</span> <span m='275823'>at</span> <span m='276270'>-16,</span>\
  \ <span m='276718'>and</span> <span m='277165'>so</span> <span m='277612'>on.</span>\
  \ </p><p><span m='278060'>Why</span> <span m='278622'>is</span> <span m='279185'>this</span>\
  \ <span m='279747'>important?</span> </p><p><span m='280310'>Some</span> <span m='280687'>languages,</span>\
  \ <span m='281064'>such</span> <span m='281441'>as</span> <span m='281818'>C,</span>\
  \ <span m='282195'>support</span> <span m='282572'>procedure</span> <span m='282950'>calls</span>\
  \ <span m='283327'>with</span> <span m='283704'>a</span> <span m='284081'>variable</span>\
  \ <span m='284458'>number</span> <span m='284835'>of</span> <span m='285212'>arguments.</span>\
  \ </p><p><span m='285590'>Usually</span> <span m='285904'>the</span> <span m='286219'>procedure</span>\
  \ <span m='286533'>can</span> <span m='286848'>determine</span> <span m='287163'>from,</span>\
  \ <span m='287477'>say,</span> <span m='287792'>the</span> <span m='288106'>first</span>\
  \ <span m='288421'>argument,</span> <span m='288736'>how</span> <span m='289050'>many</span>\
  \ <span m='289365'>additional</span> <span m='289680'>arguments</span> <span m='290433'>to</span>\
  \ <span m='291186'>expect.</span> </p><p><span m='291940'>The</span> <span m='292256'>canonical</span>\
  \ <span m='292572'>example</span> <span m='292888'>is</span> <span m='293205'>the</span>\
  \ <span m='293521'>C</span> <span m='293837'>printf</span> <span m='294153'>function</span>\
  \ <span m='294470'>where</span> <span m='294786'>the</span> <span m='295102'>first</span>\
  \ <span m='295418'>argument</span> <span m='295735'>is</span> <span m='296051'>a</span>\
  \ <span m='296367'>format</span> <span m='296683'>string</span> <span m='297000'>that</span>\
  \ <span m='297378'>specifies</span> <span m='297756'>how</span> <span m='298134'>a</span>\
  \ <span m='298512'>sequence</span> <span m='298890'>of</span> <span m='299268'>values</span>\
  \ <span m='299646'>should</span> <span m='300024'>be</span> <span m='300402'>printed.</span>\
  \ </p><p><span m='300780'>So</span> <span m='301117'>a</span> <span m='301455'>call</span>\
  \ <span m='301792'>to</span> <span m='302130'>printf</span> <span m='302467'>includes</span>\
  \ <span m='302805'>the</span> <span m='303142'>format</span> <span m='303480'>string</span>\
  \ <span m='303817'>argument</span> <span m='304155'>plus</span> <span m='304492'>a</span>\
  \ <span m='304830'>varying</span> <span m='305167'>number</span> <span m='305505'>of</span>\
  \ <span m='305842'>additional</span> <span m='306180'>arguments.</span> </p><p><span\
  \ m='307750'>With</span> <span m='308060'>our</span> <span m='308371'>calling</span>\
  \ <span m='308682'>convention</span> <span m='308992'>the</span> <span m='309303'>format</span>\
  \ <span m='309614'>string</span> <span m='309924'>will</span> <span m='310235'>always</span>\
  \ <span m='310546'>be</span> <span m='310856'>in</span> <span m='311167'>the</span>\
  \ <span m='311478'>same</span> <span m='311788'>location</span> <span m='312099'>relative</span>\
  \ <span m='312410'>to</span> <span m='312730'>BP,</span> <span m='313050'>so</span>\
  \ <span m='313370'>the</span> <span m='313690'>printf</span> <span m='314010'>code</span>\
  \ <span m='314330'>can</span> <span m='314650'>find</span> <span m='314970'>it</span>\
  \ <span m='315290'>without</span> <span m='315610'>knowing</span> <span m='315930'>the</span>\
  \ <span m='316250'>number</span> <span m='316570'>of</span> <span m='316890'>additional</span>\
  \ <span m='317210'>arguments</span> <span m='317530'>in</span> <span m='318207'>the</span>\
  \ <span m='318885'>current</span> <span m='319562'>call.</span> </p><p><span m='320240'>The</span>\
  \ <span m='320650'>local</span> <span m='321060'>variables</span> <span m='321470'>are</span>\
  \ <span m='321880'>also</span> <span m='322290'>at</span> <span m='322700'>fixed</span>\
  \ <span m='323110'>offsets</span> <span m='323520'>from</span> <span m='323930'>BP.</span>\
  \ </p><p><span m='324340'>The</span> <span m='324686'>first</span> <span m='325033'>local</span>\
  \ <span m='325380'>variable</span> <span m='325727'>is</span> <span m='326074'>at</span>\
  \ <span m='326420'>offset</span> <span m='326767'>0,</span> <span m='327114'>the</span>\
  \ <span m='327461'>second</span> <span m='327808'>at</span> <span m='328154'>offset</span>\
  \ <span m='328501'>4,</span> <span m='328848'>and</span> <span m='329195'>so</span>\
  \ <span m='329542'>on.</span> </p><p><span m='329889'>So,</span> <span m='330180'>we</span>\
  \ <span m='330472'>see</span> <span m='330764'>that</span> <span m='331055'>having</span>\
  \ <span m='331347'>a</span> <span m='331639'>base</span> <span m='331931'>pointer</span>\
  \ <span m='332222'>makes</span> <span m='332514'>it</span> <span m='332806'>easy</span>\
  \ <span m='333097'>to</span> <span m='333389'>access</span> <span m='333681'>the</span>\
  \ <span m='333973'>values</span> <span m='334264'>of</span> <span m='334556'>the</span>\
  \ <span m='334848'>arguments</span> <span m='335140'>and</span> <span m='335549'>local</span>\
  \ <span m='335958'>variables</span> <span m='336367'>using</span> <span m='336776'>fixed</span>\
  \ <span m='337186'>offsets</span> <span m='337595'>that</span> <span m='338004'>can</span>\
  \ <span m='338413'>be</span> <span m='338823'>determined</span> <span m='339232'>at</span>\
  \ <span m='339641'>compile</span> <span m='340050'>time.</span> </p><p><span m='340460'>The</span>\
  \ <span m='340814'>stack</span> <span m='341168'>above</span> <span m='341522'>the</span>\
  \ <span m='341876'>local</span> <span m='342230'>variables</span> <span m='342584'>is</span>\
  \ <span m='342938'>available</span> <span m='343292'>for</span> <span m='343646'>other</span>\
  \ <span m='344000'>uses,</span> <span m='344354'>e.g.,</span> <span m='344708'>building</span>\
  \ <span m='345062'>the</span> <span m='345416'>activation</span> <span m='345770'>record</span>\
  \ <span m='346081'>for</span> <span m='346393'>a</span> <span m='346704'>nested</span>\
  \ <span m='347016'>procedure</span> <span m='347327'>call!</span> </p>"
type: course
uid: 3d5b466a869f20f9140d205977ae506a

---
None