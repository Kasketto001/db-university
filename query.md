## UNIVERSITY DB QUERIES


-   Selezionare tutti gli studenti nati nel 1990 (160)

```SQL
SELECT * FROM `students` WHERE `date_of_birth` LIKE '1990%';
```
<details>
<summary>Query 1</summary>
|55|4|Lauro|Vitale|1990-01-30|BWOQAH56L35A201P|2018-10-22|620087|baldassarre.mancini@dangelo.com
|86|12|Matilde|Ruggiero|1990-11-17|UIFHBM73Q42E973M|2021-02-14|620118|mariagiulia18@gmail.com
|217|16|Marieva|Mariani|1990-08-30|CRKYAI63Z72H930S|2020-12-13|620249|wgrassi@mariani.net
|247|14|Marco|Bruno|1990-08-12|EPSWUQ63H25I670E|2020-06-08|620279|ubaldo70@damico.it
|306|3|Maika|Bianco|1990-01-04|GVOZOR19K65V944K|2019-11-21|620338|nmancini@yahoo.com
|320|72|Fabiano|Riva|1990-08-11|UYVLCP51Y15P902L|2019-10-10|620352|miriam.lombardi@benedetti.org
|321|44|Amedeo|Valentini|1990-04-20|RLYGWZ26T24Y855N|2020-04-18|620353|dimitri.mariani@neri.com
|334|59|Tolomeo|Morelli|1990-03-30|WCLRKV39N67J467D|2019-12-24|620366|amedeo15@bruno.it
|352|45|Eriberto|Sartori|1990-10-14|MVUSNM49E07E792U|2018-07-16|620384|serse67@messina.com
|359|2|Harry|Riva|1990-09-03|FLFQUM03P76T235N|2018-06-12|620391|hcaputo@ferraro.com
|365|67|Ursula|Sanna|1990-09-02|UWSWJL98Y56C153N|2018-11-20|620397|vgreco@mancini.com
|410|32|Pietro|Ruggiero|1990-05-11|IIXLFZ21V02C420U|2020-04-08|620442|gerlando21@libero.it
|430|4|Harry|Russo|1990-03-23|BOTXVQ95I30B140O|2020-02-06|620462|giulietta.parisi@gmail.com
|443|71|Marino|Sartori|1990-10-12|IVJSXN23A76B707B|2018-11-01|620475|gallo.vera@hotmail.com
|487|36|Cira|Costantini|1990-04-12|GTINRS89N80F500K|2020-11-03|620519|rizzo.enrica@piras.it
|519|63|Damiana|Farina|1990-01-12|EYKYWC35O38O744L|2020-07-17|620551|yserra@russo.it
|527|43|Elda|Mariani|1990-04-29|ZHGJNM05Z55G492M|2021-05-21|620559|antonio25@yahoo.it
|528|69|Maika|Barbieri|1990-04-29|VBMCXI81Q82M718M|2020-05-11|620560|ygiordano@yahoo.com
|582|41|Augusto|Costantini|1990-07-31|FPQBKO39S99H539Q|2018-06-26|620614|radio21@grassi.com
|624|4|Cira|De rosa|1990-04-26|FDATYC59R80F558X|2019-01-31|620656|colombo.morgana@pellegrino.com
|635|45|Boris|Riva|1990-12-28|FWYSKJ18E55V673Z|2020-10-30|620667|sandro72@gmail.com
|638|5|Marcella|De rosa|1990-08-29|IQDFNY14D55U297S|2018-09-11|620670|assia.palumbo@libero.it
|695|37|Boris|Martinelli|1990-02-25|LMGYIC37W94J261P|2020-04-27|620727|damiana08@bianco.org
|710|39|Egisto|Amato|1990-06-07|SZSUWA12R81D485V|2020-08-24|620742|qgallo@libero.it
|787|63|Laura|Coppola|1990-06-11|IZINQY50C42J452U|2020-05-17|620819|rinaldi.brigitta@marchetti.com
|857|56|Prisca|De luca|1990-03-12|EEGCVW93W78P140E|2019-09-26|620889|enrica.pagano@gallo.it
|877|25|Samira|Giuliani|1990-03-08|GWKCVN98H21T451U|2019-02-27|620909|danuta16@email.it
|912|36|Flaviana|Costa|1990-02-06|ALEXFQ09O80M836R|2020-08-15|620944|michele.lombardi@yahoo.com
|919|66|Secondo|Lombardo|1990-08-09|OPZDMU62P86F655U|2021-03-21|620951|bbarone@sartori.net
|1007|61|Oreste|Bianco|1990-07-08|VVBTJU54P76X363N|2021-04-18|621039|alan.colombo@yahoo.com
|1122|40|Kociss|De Angelis|1990-06-01|VQHNXM66A72G075Q|2021-04-24|621154|brigitta87@basile.it
|1123|10|Albino|Riva|1990-11-13|JXPRBQ67E99E968Q|2020-03-04|621155|rferraro@email.it
|1130|68|Mirko|Coppola|1990-02-10|SZVBTX90Y83R295A|2018-08-10|621162|grazia.negri@yahoo.com
|1162|29|Tancredi|Guerra|1990-05-02|DINOMU36K82R031K|2019-09-26|621194|jferrara@fontana.com
|1181|23|Enrica|Bruno|1990-07-13|JBYZPU73J22J109U|2021-04-23|621213|qgrassi@yahoo.it
|1190|57|Gianmarco|Rizzo|1990-08-26|EZPZHW06V87Z409D|2018-11-07|621222|ebellini@yahoo.it
|1214|40|Miriana|Negri|1990-08-15|HKIPIX45A01G163V|2020-09-24|621246|germano18@ferri.com
|1227|26|Rodolfo|Rossetti|1990-05-21|NTZRPT68F75Y770Y|2019-09-25|621259|timothy.lombardi@martino.org
|1291|23|Iacopo|Sorrentino|1990-06-20|MNITJF41I07V836B|2018-12-05|621323|giulietta49@yahoo.com
|1343|8|Cosetta|Martino|1990-01-06|CTSGZY69B86N969L|2018-08-04|621375|basile.zelida@testa.it
|1376|52|Artemide|Bianco|1990-12-21|YKIZWI45D57V431Z|2019-08-19|621408|donati.vania@gmail.com
|1442|23|Nayade|Bellini|1990-11-18|KPINCB99S52K194Q|2019-06-11|621474|mietta.greco@yahoo.it
|1486|17|Ethan|Neri|1990-07-08|XNCKTH78F26W131H|2019-12-23|621518|ipiras@libero.it
|1496|65|Davis|Ferrara|1990-05-09|BNLTXY41D25N024I|2020-02-18|621528|rizzo.vitalba@ferretti.it
|1497|64|Olimpia|Serra|1990-07-25|XBUCEI78Y30G117T|2020-04-01|621529|vitale.noel@esposito.it
|1505|38|Brigitta|Rinaldi|1990-11-14|UFMWXE13H54A970A|2020-12-15|621537|xmilani@yahoo.com
|1564|75|Laura|Cattaneo|1990-01-26|MIMNRN14B99E364M|2019-07-19|621596|galli.ingrid@lombardi.com
|1572|61|Ruth|Guerra|1990-07-31|UAEVLN07P28Z561C|2020-12-10|621604|demi08@rossi.it
|1599|52|Selvaggia|Ferri|1990-04-26|LJMVWF38G03A881Q|2018-11-14|621631|romano.cassiopea@yahoo.com
|1657|53|Nazzareno|Fabbri|1990-02-06|FXTQCL20K66N186J|2021-06-01|621689|barbieri.assia@martinelli.com
|1673|55|Lucia|Martini|1990-11-18|QISWZS06N00V825V|2020-02-08|621705|derosa.flaviana@email.it
|1687|71|Furio|Battaglia|1990-10-30|PXAVGZ01W97G783R|2019-02-06|621719|gianriccardo.mariani@yahoo.com
|1695|67|Carlo|D'angelo|1990-11-26|QBBYIJ82N00W683U|2018-10-24|621727|gavino90@yahoo.com
|1715|19|Tolomeo|Piras|1990-09-17|XNRZKQ19Z63L256T|2019-09-10|621747|fiorentino90@yahoo.it
|1739|4|Raniero|De rosa|1990-07-04|ORXOEI75M49L732L|2019-06-12|621771|joannes.sartori@yahoo.it
|1771|55|Danthon|Longo|1990-05-03|DLBXXT54A73H875F|2020-06-21|621803|brigitta.lombardi@damico.it
|1855|3|Erminia|Sala|1990-06-01|TZOSQM13M75Z551I|2021-01-17|621887|smoretti@barone.org
|1885|58|Giacinta|Galli|1990-04-17|BKZMZQ49P70W077O|2018-08-03|621917|flaviana98@yahoo.com
|1921|66|Ortensia|Sartori|1990-04-05|AVHKSX27U40G212X|2019-03-14|621953|qmontanari@rossetti.it
|1946|65|Costanzo|Morelli|1990-12-18|RJPUVA03F33I594G|2020-04-19|621978|rebecca84@giuliani.com
|1978|14|Elio|Ferrari|1990-10-16|KOWOHB43W49C058Y|2020-04-16|622010|deangelis.kociss@ferri.it
|1979|25|Ubaldo|Galli|1990-09-12|GNYFTP14E12E794J|2018-12-26|622011|fiorentino49@libero.it
|1997|2|Rufo|Greco|1990-03-03|VEUMII60C51P635H|2020-03-30|622029|lmancini@email.it
|2028|32|Rosalino|Messina|1990-08-05|ZNDKSG60A81S569Z|2020-05-07|622060|felicia80@yahoo.it
|2061|35|Violante|Santoro|1990-01-10|WOLHYL73W56R867R|2019-03-27|622093|valentini.michele@email.it
|2104|5|Samira|Rizzo|1990-05-07|DABXHS46S97J083E|2019-07-06|622136|fbarbieri@yahoo.com
|2184|64|Morgana|Esposito|1990-05-30|TJCYCP93Q21T068O|2019-04-05|622216|xruggiero@bruno.it
|2232|21|Rudy|Caruso|1990-05-24|YDMXTM21L01X925U|2019-05-20|622264|sibilla55@yahoo.com
|2262|21|Germano|Pagano|1990-03-27|CUWNGY34P24N905J|2018-07-22|622294|rosalba.costa@montanari.it
|2289|18|Elga|Damico|1990-12-18|FHGQKY20C50Z637O|2020-03-19|622321|bserra@romano.it
|2323|28|Kristel|Parisi|1990-10-21|BCSGTK67O20U235F|2020-10-12|622355|deborah.messina@parisi.org
|2397|53|Vania|Guerra|1990-09-14|EZZRMN58O64U304A|2021-03-14|622429|ibruno@fontana.net
|2407|15|Rita|Valentini|1990-08-14|UKHNDX66K97I203D|2021-02-11|622439|iparisi@bruno.it
|2459|59|Samira|D'angelo|1990-06-28|SDAIYB76D36C025J|2018-06-27|622491|marvin95@vitale.it
|2460|2|Manuele|Bianco|1990-10-16|ZMTQBT82G25S557M|2019-04-26|622492|serra.oretta@yahoo.com
|2472|61|Donatella|Martini|1990-04-22|IOUQGQ33V53M152G|2021-01-17|622504|miriam08@testa.org
|2511|34|Folco|Sala|1990-01-03|JOEICD35H21X349Q|2020-01-08|622543|ugallo@yahoo.com
|2540|21|Iacopo|Vitale|1990-04-29|TMCLVH66D40C160W|2018-10-24|622572|dmessina@email.it
|2559|69|Pablo|Giuliani|1990-04-26|QJYPMD26I25W659P|2019-04-30|622591|mariagiulia21@gmail.com
|2615|64|Cleros|Santoro|1990-06-08|AELOSN94P60A939J|2019-08-15|622647|dferri@morelli.net
|2616|71|Silverio|Messina|1990-02-27|UPCSWC90T52D603B|2019-10-05|622648|demis.pellegrino@libero.it
|2627|47|Damiana|Russo|1990-12-04|PDHBTU35U55U339B|2018-12-11|622659|hferraro@romano.com
|2674|70|Primo|D'angelo|1990-05-25|SYRAPJ19H54Q380L|2020-02-16|622706|bianco.carmela@lombardi.com
|2700|40|Dindo|Montanari|1990-04-04|DDGVGI33Y33B886J|2019-09-24|622732|sarita.villa@yahoo.com
|2715|6|Amos|Barone|1990-05-14|VFRUII42C24D790X|2019-06-21|622747|ybianco@deangelis.net
|2763|75|Monia|Galli|1990-07-19|EHEBAS76W43N388S|2020-08-18|622795|moretti.gelsomina@grassi.org
|2779|26|Assia|Morelli|1990-07-07|WQYQHX33Z50R678E|2018-12-16|622811|ffiore@email.it
|2807|25|Boris|Mazza|1990-10-17|VMOJVZ65M95G447Y|2019-09-12|622839|mariapia56@morelli.it
|2901|36|Olimpia|Piras|1990-01-28|LDVXVR15M88N131L|2018-08-05|622933|miriana11@email.it
|2947|4|Jole|Pellegrini|1990-09-20|YMLFVT67H64G493P|2019-11-26|622979|martinelli.cristyn@yahoo.com
|2949|40|Ivano|Farina|1990-04-01|ZXFTQI13B40Y292U|2020-03-10|622981|bianchi.piersilvio@yahoo.com
|2971|41|Lauro|Galli|1990-04-29|RDDTNI28V51W148P|2019-01-03|623003|vania94@caputo.it
|2995|11|Iacopo|Lombardo|1990-05-09|RSTKOE73M68A197B|2019-04-09|623027|ursula35@gmail.com
|3026|62|Mauro|Basile|1990-04-05|LEKHVY04S26L005I|2019-11-13|623058|clodovea77@libero.it
|3116|60|Shaira|Grassi|1990-05-30|MWXZKG24P23U611A|2020-07-06|623148|laerte41@gmail.com
|3227|3|Gianleonardo|Ferretti|1990-11-28|NBQAZJ89B07B357Y|2020-03-09|623259|grassi.gianantonio@battaglia.com
|3242|62|Erminia|Greco|1990-11-14|XSGUZO84L49I522G|2020-03-03|623274|bianco.erminio@hotmail.com
|3286|25|Leone|Marini|1990-01-09|CHTWFJ25G97H875X|2019-07-24|623318|caligola.messina@silvestri.it
|3309|40|Noemi|De rosa|1990-09-19|XDNOAX06S15Z145X|2019-12-17|623341|mricci@costa.com
|3327|10|Pietro|Negri|1990-03-12|JEWANF64V23M026T|2019-02-11|623359|ione27@ferrari.com
|3332|8|Silverio|Palumbo|1990-03-02|KOLWGI28O59O130N|2020-08-24|623364|naomi06@hotmail.com
|3361|33|Graziano|Martini|1990-12-18|XKGEWA77J64W440J|2021-03-15|623393|costa.nathan@yahoo.com
|3379|6|Graziano|Riva|1990-01-31|HSICLH34C60O191H|2020-03-22|623411|carmela58@coppola.com
|3397|49|Cassiopea|Ferraro|1990-04-28|GHGGGQ43I13A372U|2019-04-18|623429|wvilla@gallo.it
|3425|37|Fortunata|Pellegrino|1990-05-19|CKCMFR19L14C052T|2020-11-22|623457|cconte@palumbo.com
|3479|49|Maruska|Barone|1990-09-07|HQTHGC20J16T421F|2019-01-29|623511|igrasso@grassi.com
|3498|71|Claudia|Lombardi|1990-06-02|UUMJGO25L22C345I|2018-10-31|623530|ybianchi@libero.it
|3510|15|Giuliano|Marini|1990-03-10|DXLJVI11K08G312E|2019-04-21|623542|ugreco@hotmail.com
|3511|72|Rita|Ricci|1990-04-26|LXWBCL31I32A916N|2019-04-27|623543|sabino.martinelli@cattaneo.net
|3522|16|Timothy|Marino|1990-07-25|CPAFTB71C52Q471Z|2021-05-16|623554|antonino.piras@esposito.org
|3643|1|Fortunata|Bianchi|1990-05-02|TXNPCJ26N37B979H|2019-06-23|623675|amato.evangelista@yahoo.com
|3687|24|Bibiana|Galli|1990-03-14|VYIICS84C64W295T|2018-08-10|623719|cattaneo.ausonio@yahoo.it
|3700|48|Vitalba|Pellegrino|1990-10-16|YHCHKS97R47J257I|2021-01-26|623732|tricci@ruggiero.com
|3718|20|Irene|Morelli|1990-08-26|XKKBWO51D05J706U|2020-11-17|623750|ferretti.gilda@bianco.org
|3756|37|Zelida|Palumbo|1990-12-03|YIBBLF29U85I393H|2019-04-02|623788|ovitale@gmail.com
|3760|26|Bibiana|Neri|1990-08-28|FZGUSZ40R71E465J|2018-12-15|623792|gallo.lorenzo@yahoo.com
|3770|8|Caligola|Guerra|1990-03-07|BSVEVY06Q04K151O|2021-03-20|623802|nsanna@email.it
|3835|37|Ileana|Ricci|1990-03-17|OPCAIF74A88N272E|2020-07-21|623867|timoteo67@basile.com
|3841|24|Ausonio|Sala|1990-02-23|DPCTHN72Q38Q077G|2019-10-18|623873|arcibaldo.esposito@hotmail.com
|3868|69|Clea|Bellini|1990-05-30|PDGXXN04L56G048C|2021-02-21|623900|yago.moretti@yahoo.it
|3869|31|Cleopatra|Parisi|1990-01-14|GQYAQJ97I01U403H|2018-08-10|623901|mdamico@yahoo.com
|3871|40|Gaetano|Barone|1990-01-31|ZRRAGH96T10Z527L|2019-12-09|623903|tbianco@yahoo.it
|3882|48|Gavino|Conte|1990-08-19|QVPHYU50U61B338H|2020-01-08|623914|lcosta@derosa.net
|3894|71|Egisto|Longo|1990-07-18|QOJPWF79J43U384H|2021-04-28|623926|fatima04@hotmail.com
|3975|16|Carlo|Rinaldi|1990-10-10|PFKGKF99F49G340R|2020-10-26|624007|felicia14@gatti.it
|3987|53|Vera|Rinaldi|1990-04-26|BPFBWC81E38V431C|2019-12-23|624019|luna.conti@yahoo.it
|4001|44|Vania|Romano|1990-12-06|BRDPYI66I91Q558X|2018-07-29|624033|amilani@yahoo.com
|4032|54|Ninfa|Costa|1990-12-28|ASQRHT91N10X986Z|2020-03-05|624064|ingrid.rizzi@costantini.it
|4044|42|Davis|Caruso|1990-07-28|LRIZFX35V95A753Z|2021-02-23|624076|riva.davide@yahoo.com
|4072|44|Adriano|Sanna|1990-06-16|KYUZTP79Z66B214K|2020-09-15|624104|germano.dangelo@yahoo.com
|4142|50|Danuta|Greco|1990-04-06|PZHHWL43K24B321N|2018-11-24|624174|ferri.marcella@hotmail.com
|4205|71|Noemi|Ferri|1990-10-28|WLXLAL41R35A937E|2018-10-20|624237|edvige58@hotmail.com
|4240|17|Carlo|Monti|1990-01-29|NUPISH63Z12B561H|2019-05-05|624272|albino03@giuliani.it
|4242|2|Ivano|Longo|1990-08-13|NXXFBL94J18P949D|2021-04-04|624274|pagano.maika@libero.it
|4246|20|Isira|Russo|1990-01-27|LUSCMA34Q51X051C|2019-04-28|624278|yorlando@libero.it
|4247|27|Deborah|Fontana|1990-04-30|CLYUSL87Y54W949D|2018-11-20|624279|giovanna.rossi@hotmail.com
|4284|39|Raniero|Ruggiero|1990-08-26|LBNTCW60V96R336A|2019-08-18|624316|sala.raoul@hotmail.com
|4302|73|Guendalina|Palmieri|1990-04-24|PSPNTP35I63W553G|2020-12-03|624334|caruso.cassiopea@yahoo.it
|4313|7|Anastasio|Barone|1990-09-09|OEUCCX11B10Y282Y|2019-12-17|624345|sibilla.marino@yahoo.com
|4345|42|Lidia|Rizzo|1990-12-28|DLSWZT77E26S937R|2020-04-30|624377|luna44@russo.it
|4360|50|Jelena|Montanari|1990-07-27|YMYDTY40F06U075G|2020-10-31|624392|colombo.gerlando@yahoo.it
|4440|75|Kris|Negri|1990-10-21|TCAHFC11Z65C665U|2019-03-20|624472|marini.selvaggia@esposito.org
|4511|37|Leonardo|Pellegrino|1990-07-11|INMMYK92C33X493N|2020-03-23|624543|gastone.silvestri@rossetti.net
|4518|49|Violante|Ferrara|1990-03-10|YBWMQC69S08Y335D|2019-06-26|624550|aaron21@vitali.it
|4540|13|Gregorio|Fabbri|1990-11-21|TEZGHJ49M20L625V|2020-01-08|624572|tancredi96@mazza.it
|4560|72|Marieva|Greco|1990-10-03|WRARDI30L48N985S|2020-04-23|624592|sorrentino.maria@milani.it
|4571|45|Ingrid|Pagano|1990-07-12|BQIMBG48O40R286L|2021-01-30|624603|abarbieri@conti.it
|4594|3|Concetta|Romano|1990-11-27|ISRMCP44D14N688V|2019-12-14|624626|gabriele77@yahoo.com
|4613|55|Valdo|Monti|1990-07-27|EOCYBU51C01G153T|2019-10-21|624645|rocco.sartori@yahoo.it
|4628|16|Danny|Bianco|1990-03-05|OIHSKK93C84J608D|2018-12-14|624660|unegri@hotmail.com
|4782|74|Giulietta|Milani|1990-02-04|QOITEH95X38H201C|2021-03-21|624814|fiore.piccarda@email.it
|4831|74|Giancarlo|Serra|1990-03-14|ZSCFTQ24N82P616K|2021-04-18|624863|benedetti.clea@coppola.it
|4897|1|Carlo|Fontana|1990-08-10|UAZJHI97G46W157O|2018-09-27|624929|naomi.palumbo@rossi.org
|4900|16|Bacchisio|Morelli|1990-01-30|ZHVQNB48D88S637F|2021-05-29|624932|isira.lombardi@yahoo.it
|4914|16|Ivano|Gallo|1990-08-04|HGVHOP45R16G539V|2018-09-30|624946|zelida47@yahoo.com
|4936|75|Terzo|Martino|1990-01-04|AVYRVM94Z77Y195K|2020-07-31|624968|max62@pagano.net
|4938|62|Grazia|Villa|1990-02-21|QHLXFI59S74T192Y|2020-10-21|624970|testa.felicia@libero.it
|4952|42|Alan|Gallo|1990-11-15|PQFFOL71J23H079O|2018-09-18|624984|ferraro.silvano@yahoo.it
|4961|56|Cleros|Fiore|1990-10-24|GWIXJK53K54Q533N|2021-02-26|624993|battista50@benedetti.com
|4972|13|Silverio|Grasso|1990-09-15|IUBYYW35F09Y552P|2019-08-17|625004|luna.sartori@hotmail.com
</details>
-   Selezionare tutti i corsi che valgono più di 10 crediti (479)
-   Selezionare tutti gli studenti che hanno più di 30 anni
-   Selezionare tutti i corsi del primo semestre del primo anno di un qualsiasi corso di laurea (286)
-   Selezionare tutti gli appelli d'esame che avvengono nel pomeriggio (dopo le 14) del 20/06/2020 (21)
-   Selezionare tutti i corsi di laurea magistrale (38)
-   Da quanti dipartimenti è composta l'università? (12)
-   Quanti sono gli insegnanti che non hanno un numero di telefono? (50)
