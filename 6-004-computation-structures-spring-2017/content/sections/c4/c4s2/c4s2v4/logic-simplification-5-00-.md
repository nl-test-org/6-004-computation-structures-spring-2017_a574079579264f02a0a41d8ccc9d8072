---
about_this_resource_text: ''
course_id: 6-004-computation-structures-spring-2017
embedded_media:
- id: Video-YouTube-Stream
  media_location: r6Tk1-jZxzg
  parent_uid: 06784f32f6e0d543cfc001d9ba6be8fb
  title: Video-YouTube-Stream
  type: Video
  uid: 49a85a4c27fe872e4cc814fe25ce1cc0
- id: 3Play-3Play YouTube id-Stream
  media_location: r6Tk1-jZxzg
  parent_uid: 06784f32f6e0d543cfc001d9ba6be8fb
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: ad1128d2ef24daefab6258849e95439f
- id: Thumbnail-YouTube-JPG_1
  media_location: https://img.youtube.com/vi/r6Tk1-jZxzg/default.jpg
  parent_uid: 06784f32f6e0d543cfc001d9ba6be8fb
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 2f29980e5f3e91a04f7b137053b7e334
- id: r6Tk1-jZxzg.srt
  parent_uid: 06784f32f6e0d543cfc001d9ba6be8fb
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c4/c4s2/c4s2v4/logic-simplification-5-00-/r6Tk1-jZxzg.srt
  title: 3play caption file
  type: null
  uid: 17d07f886f173a4cbc4ceda70cab7a8e
- id: r6Tk1-jZxzg.pdf
  parent_uid: 06784f32f6e0d543cfc001d9ba6be8fb
  technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c4/c4s2/c4s2v4/logic-simplification-5-00-/r6Tk1-jZxzg.pdf
  title: 3play pdf file
  type: null
  uid: b9b9e9033e8f13573776597563603018
- id: Caption-3Play YouTube id-SRT
  parent_uid: 06784f32f6e0d543cfc001d9ba6be8fb
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: fac0415d50d07c7f5c995177deee2612
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 06784f32f6e0d543cfc001d9ba6be8fb
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 459a28d444af3a5f1d8a9b458984c552
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT6.004S17/MIT6_004S17_04-02-04_300k.mp4
  parent_uid: 06784f32f6e0d543cfc001d9ba6be8fb
  title: Video-Internet Archive-MP4
  type: Video
  uid: b1fa9ffb7348ca4c4913cff3d7bf964f
inline_embed_id: 69720228logicsimplification50038377045
layout: video
order_index: null
parent_uid: fa5ffa0cb3d5d3693ab509d52048e3d2
related_resources_text: ''
short_url: logic-simplification-5-00-
technical_location: https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-004-computation-structures-spring-2017/c4/c4s2/c4s2v4/logic-simplification-5-00-
template_type: Embed
title: Logic Simplification (5:00)
transcript: "<p><span m='510'>The</span> <span m='1100'>previous</span> <span m='1640'>sections</span>\
  \ <span m='2210'>showed</span> <span m='2530'>us</span> <span m='2680'>how</span>\
  \ <span m='2820'>to</span> <span m='2910'>build</span> <span m='3180'>a</span> <span\
  \ m='3240'>circuit</span> <span m='3690'>that</span> <span m='3840'>computes</span>\
  \ <span m='4420'>a</span> <span m='4480'>given</span> <span m='4920'>sum-of-products</span>\
  \ <span m='5650'>expression.</span> </p><p><span m='6940'>An</span> <span m='7000'>interesting</span>\
  \ <span m='7500'>question</span> <span m='7890'>to</span> <span m='8029'>ask</span>\
  \ <span m='8570'>is</span> <span m='8820'>if</span> <span m='9040'>we</span> <span\
  \ m='9120'>can</span> <span m='9310'>implement</span> <span m='9750'>the</span>\
  \ <span m='9830'>same</span> <span m='10220'>functionality</span> <span m='10970'>using</span>\
  \ <span m='11370'>fewer</span> <span m='11860'>gates</span> <span m='12020'>or</span>\
  \ <span m='12120'>smaller</span> <span m='12580'>gates?</span> </p><p><span m='13710'>In</span>\
  \ <span m='13820'>other</span> <span m='13990'>words</span> <span m='14450'>is</span>\
  \ <span m='14660'>there</span> <span m='14870'>an</span> <span m='14950'>equivalent</span>\
  \ <span m='15530'>Boolean</span> <span m='15920'>expression</span> <span m='16560'>that</span>\
  \ <span m='16730'>involves</span> <span m='17250'>fewer</span> <span m='17680'>operations?</span>\
  \ </p><p><span m='19290'>Boolean</span> <span m='19690'>algebra</span> <span m='20180'>has</span>\
  \ <span m='20430'>many</span> <span m='20810'>identities</span> <span m='21490'>that</span>\
  \ <span m='21640'>can</span> <span m='21800'>be</span> <span m='21930'>used</span>\
  \ <span m='22280'>to</span> <span m='22360'>transform</span> <span m='22940'>an</span>\
  \ <span m='23020'>expression</span> <span m='23650'>into</span> <span m='23980'>an</span>\
  \ <span m='24040'>equivalent,</span> <span m='24760'>and</span> <span m='25020'>hopefully</span>\
  \ <span m='25380'>smaller,</span> <span m='25910'>expression.</span> </p><p><span\
  \ m='27660'>The</span> <span m='27750'>reduction</span> <span m='28250'>identity</span>\
  \ <span m='28790'>in</span> <span m='28910'>particular</span> <span m='29770'>offers</span>\
  \ <span m='30290'>a</span> <span m='30340'>transformation</span> <span m='31190'>that</span>\
  \ <span m='31340'>simplifies</span> <span m='32009'>an</span> <span m='32080'>expression</span>\
  \ <span m='32659'>involving</span> <span m='33160'>two</span> <span m='33410'>variables</span>\
  \ <span m='34100'>and</span> <span m='34270'>four</span> <span m='34570'>operations</span>\
  \ <span m='35450'>into</span> <span m='35900'>a</span> <span m='35930'>single</span>\
  \ <span m='36290'>variable</span> <span m='36850'>and</span> <span m='37030'>no</span>\
  \ <span m='37390'>operations.</span> </p><p><span m='38700'>Let\u2019s</span> <span\
  \ m='38940'>see</span> <span m='39260'>how</span> <span m='39410'>we</span> <span\
  \ m='39560'>might</span> <span m='39780'>use</span> <span m='40110'>that</span>\
  \ <span m='40360'>identity</span> <span m='40900'>to</span> <span m='41000'>simplify</span>\
  \ <span m='41660'>a</span> <span m='41710'>sum-of-products</span> <span m='42430'>expression.</span>\
  \ </p><p><span m='44770'>Here\u2019s</span> <span m='45090'>the</span> <span m='45210'>equation</span>\
  \ <span m='45730'>from</span> <span m='45920'>the</span> <span m='45980'>start</span>\
  \ <span m='46380'>of</span> <span m='46490'>this</span> <span m='46680'>chapter,</span>\
  \ <span m='47160'>involving</span> <span m='47670'>4</span> <span m='47890'>product</span>\
  \ <span m='48480'>terms.</span> </p><p><span m='49500'>We\u2019ll</span> <span m='49670'>use</span>\
  \ <span m='49850'>a</span> <span m='49890'>variant</span> <span m='50420'>of</span>\
  \ <span m='50520'>the</span> <span m='50590'>reduction</span> <span m='51090'>identity</span>\
  \ <span m='51700'>involving</span> <span m='52240'>a</span> <span m='52370'>Boolean</span>\
  \ <span m='52780'>expression</span> <span m='53370'>alpha</span> <span m='54000'>and</span>\
  \ <span m='54410'>a</span> <span m='54450'>single</span> <span m='54860'>variable</span>\
  \ <span m='55410'>A.</span> </p><p><span m='56930'>Looking</span> <span m='57210'>at</span>\
  \ <span m='57280'>the</span> <span m='57370'>product</span> <span m='57810'>terms,</span>\
  \ <span m='58480'>the</span> <span m='58760'>middle</span> <span m='59080'>two</span>\
  \ <span m='59320'>offer</span> <span m='59750'>an</span> <span m='59810'>opportunity</span>\
  \ <span m='60380'>to</span> <span m='60530'>apply</span> <span m='60960'>the</span>\
  \ <span m='61030'>reduction</span> <span m='61530'>identity</span> <span m='62110'>if</span>\
  \ <span m='62260'>we</span> <span m='62350'>let</span> <span m='62620'>alpha</span>\
  \ <span m='62980'>be</span> <span m='63190'>the</span> <span m='63310'>expression</span>\
  \ <span m='64140'>(C</span> <span m='64769'>AND</span> <span m='65060'>B).</span>\
  \ </p><p><span m='66150'>So</span> <span m='66280'>we</span> <span m='66430'>simplify</span>\
  \ <span m='66920'>the</span> <span m='67020'>middle</span> <span m='67310'>two</span>\
  \ <span m='67490'>product</span> <span m='67870'>terms</span> <span m='68190'>to</span>\
  \ <span m='68290'>just</span> <span m='68560'>alpha,</span> <span m='69160'>i.e.,</span>\
  \ <span m='69880'>(C</span> <span m='70870'>AND</span> <span m='71050'>B),</span>\
  \ <span m='71730'>eliminating</span> <span m='72750'>the</span> <span m='72820'>variable</span>\
  \ <span m='73300'>A</span> <span m='73580'>from</span> <span m='73790'>this</span>\
  \ <span m='73980'>part</span> <span m='74210'>of</span> <span m='74270'>the</span>\
  \ <span m='74380'>expression.</span> </p><p><span m='75730'>Considering</span> <span\
  \ m='76270'>the</span> <span m='76350'>now</span> <span m='76560'>three</span> <span\
  \ m='76840'>product</span> <span m='77260'>terms,</span> <span m='77620'>we</span>\
  \ <span m='77770'>see</span> <span m='78060'>that</span> <span m='78220'>the</span>\
  \ <span m='78300'>first</span> <span m='78710'>and</span> <span m='78810'>last</span>\
  \ <span m='79140'>terms</span> <span m='79450'>can</span> <span m='79590'>also</span>\
  \ <span m='79930'>be</span> <span m='80090'>reduced,</span> <span m='80810'>this</span>\
  \ <span m='81250'>time</span> <span m='81550'>letting</span> <span m='81830'>alpha</span>\
  \ <span m='82130'>be</span> <span m='82300'>the</span> <span m='82410'>expression</span>\
  \ <span m='83180'>(NOT</span> <span m='83630'>C</span> <span m='84000'>and</span>\
  \ <span m='84120'>A).</span> </p><p><span m='85890'>Wow,</span> <span m='86600'>this</span>\
  \ <span m='87200'>equivalent</span> <span m='87670'>equation</span> <span m='88150'>is</span>\
  \ <span m='88320'>much</span> <span m='88640'>smaller!</span> </p><p><span m='89970'>Counting</span>\
  \ <span m='90380'>inversions</span> <span m='91000'>and</span> <span m='91100'>pair-wise</span>\
  \ <span m='91590'>operations,</span> <span m='92440'>the</span> <span m='92660'>original</span>\
  \ <span m='93100'>equation</span> <span m='93520'>has</span> <span m='93970'>14</span>\
  \ <span m='94230'>operations,</span> <span m='95170'>while</span> <span m='95530'>the</span>\
  \ <span m='95620'>simplified</span> <span m='96330'>equation</span> <span m='96830'>has</span>\
  \ <span m='97100'>4</span> <span m='97270'>operations.</span> </p><p><span m='99080'>The</span>\
  \ <span m='99150'>simplified</span> <span m='99750'>circuit</span> <span m='100070'>would</span>\
  \ <span m='100210'>be</span> <span m='100330'>much</span> <span m='100620'>cheaper</span>\
  \ <span m='100900'>to</span> <span m='100970'>build</span> <span m='101560'>and</span>\
  \ <span m='101860'>have</span> <span m='102100'>a</span> <span m='102140'>smaller</span>\
  \ <span m='102680'>tPD</span> <span m='103250'>in</span> <span m='103330'>the</span>\
  \ <span m='103390'>bargain!</span> </p><p><span m='105560'>Doing</span> <span m='105850'>this</span>\
  \ <span m='106020'>sort</span> <span m='106240'>of</span> <span m='106340'>Boolean</span>\
  \ <span m='106740'>simplification</span> <span m='107450'>by</span> <span m='107590'>hand</span>\
  \ <span m='108070'>is</span> <span m='108280'>tedious</span> <span m='108920'>and</span>\
  \ <span m='109040'>error-prone.</span> </p><p><span m='110290'>Just</span> <span\
  \ m='110590'>the</span> <span m='110650'>sort</span> <span m='110920'>of</span>\
  \ <span m='111020'>task</span> <span m='111460'>a</span> <span m='111510'>computer</span>\
  \ <span m='111910'>program</span> <span m='112380'>could</span> <span m='112560'>help</span>\
  \ <span m='112800'>with.</span> </p><p><span m='113990'>Such</span> <span m='114250'>programs</span>\
  \ <span m='114710'>are</span> <span m='114830'>in</span> <span m='114890'>common</span>\
  \ <span m='115280'>use,</span> <span m='115810'>but</span> <span m='116160'>the</span>\
  \ <span m='116220'>computation</span> <span m='116990'>needed</span> <span m='117280'>to</span>\
  \ <span m='117360'>discover</span> <span m='117860'>the</span> <span m='117950'>smallest</span>\
  \ <span m='118600'>possible</span> <span m='119110'>form</span> <span m='119750'>for</span>\
  \ <span m='120150'>an</span> <span m='120220'>expression</span> <span m='120910'>grows</span>\
  \ <span m='121330'>faster</span> <span m='121770'>than</span> <span m='121910'>exponentially</span>\
  \ <span m='122810'>as</span> <span m='123000'>the</span> <span m='123090'>number</span>\
  \ <span m='123400'>of</span> <span m='123530'>inputs</span> <span m='124040'>increases.</span>\
  \ </p><p><span m='125410'>So</span> <span m='125700'>for</span> <span m='125890'>larger</span>\
  \ <span m='126290'>equations,</span> <span m='126840'>the</span> <span m='126920'>programs</span>\
  \ <span m='127470'>use</span> <span m='127840'>various</span> <span m='128199'>heuristics</span>\
  \ <span m='128800'>to</span> <span m='128919'>choose</span> <span m='129259'>which</span>\
  \ <span m='129690'>simplifications</span> <span m='130590'>to</span> <span m='130740'>apply.</span>\
  \ </p><p><span m='132330'>The</span> <span m='132410'>results</span> <span m='132850'>are</span>\
  \ <span m='132930'>quite</span> <span m='133260'>good,</span> <span m='133710'>but</span>\
  \ <span m='133950'>not</span> <span m='134250'>necessarily</span> <span m='134810'>optimal.</span>\
  \ </p><p><span m='136040'>But</span> <span m='136180'>it</span> <span m='136340'>sure</span>\
  \ <span m='136670'>beats</span> <span m='137020'>doing</span> <span m='137400'>the</span>\
  \ <span m='137460'>simplification</span> <span m='138170'>by</span> <span m='138320'>hand!</span>\
  \ </p><p><span m='139870'>Another</span> <span m='140170'>way</span> <span m='140350'>to</span>\
  \ <span m='140440'>think</span> <span m='140640'>about</span> <span m='140890'>simplification</span>\
  \ <span m='141710'>is</span> <span m='141860'>by</span> <span m='142010'>searching</span>\
  \ <span m='142440'>the</span> <span m='142530'>truth</span> <span m='142820'>table</span>\
  \ <span m='143140'>for</span> <span m='143320'>\u201Cdon\u2019t-care\u201D</span>\
  \ <span m='143940'>situations.</span> </p><p><span m='145280'>For</span> <span m='145420'>example,</span>\
  \ <span m='146100'>look</span> <span m='146490'>at</span> <span m='146600'>the</span>\
  \ <span m='146680'>first</span> <span m='147100'>and</span> <span m='147260'>third</span>\
  \ <span m='147530'>rows</span> <span m='147940'>of</span> <span m='148030'>the</span>\
  \ <span m='148150'>original</span> <span m='148590'>truth</span> <span m='148860'>table</span>\
  \ <span m='149280'>on</span> <span m='149440'>the</span> <span m='149500'>left.</span>\
  \ </p><p><span m='150740'>In</span> <span m='150840'>both</span> <span m='151150'>cases</span>\
  \ <span m='151710'>A</span> <span m='151950'>is</span> <span m='152280'>0,</span>\
  \ <span m='152530'>C</span> <span m='152890'>is</span> <span m='153120'>0,</span>\
  \ <span m='153260'>and</span> <span m='153470'>the</span> <span m='153600'>output</span>\
  \ <span m='153960'>Y</span> <span m='154320'>is</span> <span m='154800'>0.</span>\
  \ </p><p><span m='155420'>The</span> <span m='155570'>only</span> <span m='155810'>difference</span>\
  \ <span m='156290'>is</span> <span m='156600'>the</span> <span m='156790'>value</span>\
  \ <span m='157260'>of</span> <span m='157340'>B,</span> <span m='158110'>which</span>\
  \ <span m='158650'>we</span> <span m='158780'>can</span> <span m='159030'>then</span>\
  \ <span m='159320'>tell</span> <span m='159660'>is</span> <span m='159880'>irrelevant</span>\
  \ <span m='160510'>when</span> <span m='160760'>both</span> <span m='161020'>A</span>\
  \ <span m='161280'>and</span> <span m='161390'>C</span> <span m='161720'>are</span>\
  \ <span m='162280'>0.</span> </p><p><span m='162810'>This</span> <span m='163070'>gives</span>\
  \ <span m='163320'>us</span> <span m='163490'>the</span> <span m='163570'>first</span>\
  \ <span m='163910'>row</span> <span m='164170'>of</span> <span m='164230'>the</span>\
  \ <span m='164340'>truth</span> <span m='164700'>table</span> <span m='164920'>on</span>\
  \ <span m='165050'>the</span> <span m='165130'>right,</span> <span m='165760'>where</span>\
  \ <span m='166110'>we</span> <span m='166230'>use</span> <span m='166490'>X</span>\
  \ <span m='166800'>to</span> <span m='166910'>indicate</span> <span m='167380'>that</span>\
  \ <span m='167500'>the</span> <span m='167610'>value</span> <span m='167980'>of</span>\
  \ <span m='168080'>B</span> <span m='168500'>doesn\u2019t</span> <span m='168840'>matter</span>\
  \ <span m='169500'>when</span> <span m='169880'>A</span> <span m='170240'>and</span>\
  \ <span m='170400'>C</span> <span m='170710'>are</span> <span m='170780'>both</span>\
  \ <span m='171080'>0.</span> </p><p><span m='172690'>By</span> <span m='172800'>comparing</span>\
  \ <span m='173460'>rows</span> <span m='173890'>with</span> <span m='174030'>the</span>\
  \ <span m='174090'>same</span> <span m='174410'>value</span> <span m='174690'>for</span>\
  \ <span m='174860'>Y,</span> <span m='175440'>we</span> <span m='175670'>can</span>\
  \ <span m='175810'>find</span> <span m='176120'>other</span> <span m='176480'>don\u2019\
  t-care</span> <span m='176930'>situations.</span> </p><p><span m='179080'>The</span>\
  \ <span m='179190'>truth</span> <span m='179460'>table</span> <span m='179800'>with</span>\
  \ <span m='179930'>don\u2019t-cares</span> <span m='180640'>has</span> <span m='180840'>only</span>\
  \ <span m='181060'>three</span> <span m='181370'>rows</span> <span m='182030'>where</span>\
  \ <span m='182370'>the</span> <span m='182550'>output</span> <span m='182910'>is</span>\
  \ <span m='183250'>1.</span> </p><p><span m='184230'>And,</span> <span m='184350'>in</span>\
  \ <span m='184410'>fact,</span> <span m='184720'>the</span> <span m='184790'>last</span>\
  \ <span m='185100'>row</span> <span m='185380'>is</span> <span m='185460'>redundant</span>\
  \ <span m='186000'>in</span> <span m='186110'>the</span> <span m='186190'>sense</span>\
  \ <span m='186540'>that</span> <span m='186690'>the</span> <span m='186850'>input</span>\
  \ <span m='187190'>combinations</span> <span m='187880'>it</span> <span m='187980'>matches</span>\
  \ <span m='189220'>(011</span> <span m='189990'>and</span> <span m='190530'>111)</span>\
  \ <span m='190770'>are</span> <span m='191370'>covered</span> <span m='192310'>by</span>\
  \ <span m='192500'>the</span> <span m='192600'>second</span> <span m='193090'>and</span>\
  \ <span m='193260'>fourth</span> <span m='193580'>rows.</span> </p><p><span m='195210'>The</span>\
  \ <span m='195290'>product</span> <span m='195680'>terms</span> <span m='196070'>derived</span>\
  \ <span m='196550'>from</span> <span m='196770'>rows</span> <span m='197060'>two</span>\
  \ <span m='197280'>and</span> <span m='197400'>four</span> <span m='197770'>are</span>\
  \ <span m='197970'>exactly</span> <span m='198560'>the</span> <span m='198640'>product</span>\
  \ <span m='198990'>terms</span> <span m='199310'>we</span> <span m='199440'>found</span>\
  \ <span m='199810'>by</span> <span m='200010'>applying</span> <span m='200470'>the</span>\
  \ <span m='200540'>reduction</span> <span m='201010'>identity.</span> </p><p><span\
  \ m='203180'>Do</span> <span m='203330'>we</span> <span m='203590'>always</span>\
  \ <span m='203980'>want</span> <span m='204260'>to</span> <span m='204330'>use</span>\
  \ <span m='204680'>the</span> <span m='204770'>simplest</span> <span m='205300'>possible</span>\
  \ <span m='205860'>equation</span> <span m='206360'>as</span> <span m='206490'>the</span>\
  \ <span m='206580'>template</span> <span m='207020'>for</span> <span m='207200'>our</span>\
  \ <span m='207310'>circuits?</span> </p><p><span m='208830'>Seems</span> <span m='209170'>like</span>\
  \ <span m='209340'>that</span> <span m='209540'>would</span> <span m='209730'>minimize</span>\
  \ <span m='210520'>the</span> <span m='210590'>circuit</span> <span m='210940'>cost</span>\
  \ <span m='211320'>and</span> <span m='211450'>maximize</span> <span m='212050'>performance,</span>\
  \ <span m='212820'>a</span> <span m='213020'>good</span> <span m='213220'>thing.</span>\
  \ </p><p><span m='214630'>The</span> <span m='214700'>simplified</span> <span m='215260'>circuit</span>\
  \ <span m='215610'>is</span> <span m='215670'>shown</span> <span m='216020'>here.</span>\
  \ </p><p><span m='217280'>Let\u2019s</span> <span m='217550'>look</span> <span m='217750'>at</span>\
  \ <span m='217840'>how</span> <span m='218110'>it</span> <span m='218230'>performs</span>\
  \ <span m='218840'>when</span> <span m='219020'>A</span> <span m='219250'>is</span>\
  \ <span m='219500'>1,</span> <span m='219780'>B</span> <span m='220150'>is</span>\
  \ <span m='220510'>1,</span> <span m='220830'>and</span> <span m='221070'>C</span>\
  \ <span m='221430'>makes</span> <span m='221680'>a</span> <span m='221720'>transition</span>\
  \ <span m='222370'>from</span> <span m='222740'>1</span> <span m='222840'>to</span>\
  \ <span m='223250'>0.</span> </p><p><span m='224020'>Before</span> <span m='224340'>the</span>\
  \ <span m='224420'>transition,</span> <span m='225010'>C</span> <span m='225250'>is</span>\
  \ <span m='225490'>1</span> <span m='225640'>and</span> <span m='225780'>we</span>\
  \ <span m='225950'>can</span> <span m='226070'>see</span> <span m='226310'>from</span>\
  \ <span m='226460'>the</span> <span m='226610'>annotated</span> <span m='227220'>node</span>\
  \ <span m='227490'>values</span> <span m='228050'>that</span> <span m='228260'>it\u2019\
  s</span> <span m='228470'>the</span> <span m='228580'>bottom</span> <span m='229040'>AND</span>\
  \ <span m='229290'>gate</span> <span m='229630'>that\u2019s</span> <span m='229970'>causing</span>\
  \ <span m='230350'>the</span> <span m='230650'>Y</span> <span m='231160'>output</span>\
  \ <span m='231320'>to</span> <span m='231380'>be</span> <span m='231480'>1.</span>\
  \ </p><p><span m='231510'>When</span> <span m='232740'>C</span> <span m='233930'>transitions</span>\
  \ <span m='234660'>to</span> <span m='234990'>0,</span> <span m='235300'>the</span>\
  \ <span m='235570'>bottom</span> <span m='236000'>AND</span> <span m='236240'>gate</span>\
  \ <span m='236490'>turns</span> <span m='236850'>off</span> <span m='237400'>and</span>\
  \ <span m='237580'>the</span> <span m='237760'>top</span> <span m='238150'>AND</span>\
  \ <span m='238400'>gate</span> <span m='238640'>turns</span> <span m='239000'>on,</span>\
  \ <span m='239680'>and,</span> <span m='240400'>eventually</span> <span m='241100'>the</span>\
  \ <span m='241230'>Y</span> <span m='241520'>output</span> <span m='241880'>becomes</span>\
  \ <span m='242340'>1</span> <span m='242460'>again.</span> </p><p><span m='244060'>But</span>\
  \ <span m='244230'>the</span> <span m='244310'>turning</span> <span m='244660'>on</span>\
  \ <span m='245050'>of</span> <span m='245160'>the</span> <span m='245240'>top</span>\
  \ <span m='245610'>AND</span> <span m='245890'>is</span> <span m='246210'>delayed</span>\
  \ <span m='246660'>by</span> <span m='246770'>the</span> <span m='246880'>tPD</span>\
  \ <span m='247530'>of</span> <span m='247620'>the</span> <span m='247770'>inverter,</span>\
  \ <span m='248630'>so</span> <span m='249260'>there\u2019s</span> <span m='249500'>a</span>\
  \ <span m='249550'>brief</span> <span m='249860'>period</span> <span m='250160'>of</span>\
  \ <span m='250270'>time</span> <span m='250720'>where</span> <span m='250920'>neither</span>\
  \ <span m='251430'>AND</span> <span m='251690'>gate</span> <span m='251910'>is</span>\
  \ <span m='252060'>on,</span> <span m='252650'>and</span> <span m='253160'>the</span>\
  \ <span m='253310'>output</span> <span m='253920'>momentarily</span> <span m='254760'>becomes</span>\
  \ <span m='255500'>0.</span> </p><p><span m='256019'>This</span> <span m='256140'>short</span>\
  \ <span m='256440'>blip</span> <span m='256740'>in</span> <span m='256820'>Y\u2019\
  s</span> <span m='257190'>value</span> <span m='257540'>is</span> <span m='257670'>called</span>\
  \ <span m='257940'>a</span> <span m='258000'>glitch</span> <span m='258410'>and</span>\
  \ <span m='258500'>it</span> <span m='258589'>may</span> <span m='258779'>result</span>\
  \ <span m='259230'>in</span> <span m='259370'>short-lived</span> <span m='259930'>changes</span>\
  \ <span m='260390'>on</span> <span m='260490'>many</span> <span m='260800'>node</span>\
  \ <span m='261060'>values</span> <span m='261649'>as</span> <span m='261950'>it</span>\
  \ <span m='262019'>propagates</span> <span m='262740'>through</span> <span m='263000'>other</span>\
  \ <span m='263210'>parts</span> <span m='263590'>of</span> <span m='263660'>the</span>\
  \ <span m='263740'>circuit.</span> </p><p><span m='265610'>All</span> <span m='265820'>those</span>\
  \ <span m='266100'>changes</span> <span m='266620'>consume</span> <span m='267030'>power,</span>\
  \ <span m='267470'>so</span> <span m='267660'>it</span> <span m='267720'>would</span>\
  \ <span m='267840'>be</span> <span m='267960'>good</span> <span m='268240'>to</span>\
  \ <span m='268400'>avoid</span> <span m='268780'>these</span> <span m='268960'>sorts</span>\
  \ <span m='269240'>of</span> <span m='269320'>glitches</span> <span m='269750'>if</span>\
  \ <span m='269870'>we</span> <span m='269950'>can.</span> </p><p><span m='271890'>If</span>\
  \ <span m='272040'>we</span> <span m='272140'>include</span> <span m='272470'>the</span>\
  \ <span m='272640'>third</span> <span m='272980'>product</span> <span m='273370'>term</span>\
  \ <span m='273690'>BA</span> <span m='273810'>in</span> <span m='274420'>our</span>\
  \ <span m='274540'>implementation,</span> <span m='275580'>the</span> <span m='275900'>circuit</span>\
  \ <span m='276340'>still</span> <span m='276690'>computes</span> <span m='277220'>the</span>\
  \ <span m='277310'>same</span> <span m='277720'>long-term</span> <span m='278310'>answer</span>\
  \ <span m='278650'>as</span> <span m='278780'>before.</span> </p><p><span m='280120'>But</span>\
  \ <span m='280270'>now</span> <span m='280730'>when</span> <span m='281010'>A</span>\
  \ <span m='281250'>and</span> <span m='281370'>B</span> <span m='281510'>are</span>\
  \ <span m='281610'>both</span> <span m='281890'>high,</span> <span m='282380'>the</span>\
  \ <span m='282690'>output</span> <span m='283080'>Y</span> <span m='283520'>will</span>\
  \ <span m='283690'>be</span> <span m='284010'>1</span> <span m='284320'>independently</span>\
  \ <span m='285340'>of</span> <span m='285450'>the</span> <span m='285540'>value</span>\
  \ <span m='285900'>of</span> <span m='286020'>the</span> <span m='286080'>C</span>\
  \ <span m='286450'>input.</span> </p><p><span m='287730'>So</span> <span m='287980'>the</span>\
  \ <span m='288280'>1-to-0</span> <span m='288670'>transition</span> <span m='289340'>on</span>\
  \ <span m='289470'>the</span> <span m='289530'>C</span> <span m='289870'>input</span>\
  \ <span m='290320'>doesn\u2019t</span> <span m='290780'>cause</span> <span m='291080'>a</span>\
  \ <span m='291120'>glitch</span> <span m='291480'>on</span> <span m='291590'>the</span>\
  \ <span m='291650'>Y</span> <span m='291880'>output.</span> </p><p><span m='292990'>If</span>\
  \ <span m='293120'>you</span> <span m='293280'>recall</span> <span m='293760'>the</span>\
  \ <span m='293820'>last</span> <span m='294200'>section</span> <span m='294600'>of</span>\
  \ <span m='294690'>the</span> <span m='294760'>previous</span> <span m='295190'>chapter,</span>\
  \ <span m='295900'>the</span> <span m='296180'>phrase</span> <span m='296600'>we</span>\
  \ <span m='296720'>used</span> <span m='297040'>to</span> <span m='297110'>describe</span>\
  \ <span m='297580'>such</span> <span m='297870'>circuits</span> <span m='298460'>is</span>\
  \ <span m='298730'>\u201Clenient\u201D.</span> </p>"
type: course
uid: 06784f32f6e0d543cfc001d9ba6be8fb

---
None