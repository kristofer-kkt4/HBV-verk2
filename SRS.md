# Software Requirements Specification (útgáfa fyrir verkefni 2)
## Númer teymis og höfundar
Hópur4: Kridtófer Kári Þorsteinsson, Helga Solveig McAdam og Bergur Ísak Ólafsson

## Heiti kerfis
Tíminn

## 1. Inngangur

### 1.1 Gildissvið (Scope)

Tímaskráningar kerfi fyrir starfsfólk í liðveislu. Kerfið á að halda utanum unninn tíma notenda og akstur þeirra á vinnutíma. 
Notandinn ætti að geta skráð sig inn þegar hann byrjar að vinna, og skráð sig út þegar vinnu líkur. Tíminn sem hann vinnur skráist síðan sjálfkrafa niður og reiknar laun. 
Þegar notandinn byrjar að aka getur hann merkt við í appinu að hann sé byrjaður að keyra og síðan merkt við þegar akstri lýkur. Þar með skráist heildarakstur á vinnutíma. Síðan bætist eldsneytiskostnaður upp að ákveðinni upphæð við launin. Kerfið nýtir sér gps við reikning á akstri.
Einnig á forritið að geta tekið myndir af kvittunum á mat og afþreyingu. Þetta er aukakostnaður sem notandinn á að fá endurgreitt, upp að ákveðinni upphæð. 


### 1.2 Tilvísanir

- IEEE 29148 staðall
- COS Vision & Scope (fyrirmynd) eða aðrar fyrirmyndir sem þið notið


## 2. Lýsing á hagsmunaaðilum og notendahópum

Forgangsnotendur:    
Starfsmenn í liðveislu – Nota kerfið daglega til að skrá vinnutíma, akstur og kvittanir. Aðalnotendahópurinn sem kerfið er hannað fyrir.

Aðrir lykilhópar innan stofnunar:    
Verkefnastjórar / umsjónarmenn – Yfirfara og samþykkja skráningar til að tryggja gæði gagna.
Launafulltrúar / fjármáladeild – Nota úttak úr kerfinu til launavinnslu og bókhalds.

Utan stofnunar / óbeinir hagsmunaaðilar:     
Launafyrirtæki / bókhaldsþjónusta – Tekur við úttaki til að vinna laun.
Ríkisskattstjóri / opinberir eftirlitsaðilar – Tryggja að lög og reglur séu uppfylltar.
Sveitarfélag / opinber styrktaraðili – Fjármagna þjónustuna og vilja gagnsæi í úrvinnslu gagna.

Óæskilegir / útilokaðir:     
Starfsmenn utan liðveisluþjónustu – Hafa ekki aðgang en gætu reynt að nota kerfið ranglega.

[Hagsmunaaðilar og notendahópar](STAKEHOLDERS.md)


## 3. Greining á mögulegum árekstrum og tillögu að úrlausnum

Business Strategy Conflicts:    
Notendur vilja einfaldan skráningarferil, deildarstjóri eftirlit: Skilgreina sameiginleg markmið; product owner tryggir jafnvægi.
Öryggiskröfur og hraður aðgangur: Skilgreina öryggisstefnu og miðla henni til allra hagsmunaaðila.

Requirements Value Conflicts:     
Kvittanir og birting: Product owner ákveður forgang og jafnvægi.
Offline skráning: Eigandi verkefnisins metur kostnað og ávinning.

Requirements Substance Conflicts:    
Birting launa og unnin tími: Meta markmið verkefnisins og mikilvægi upplýsinganna.
Innskráning og öryggisstaðlar: Rýna staðla og finna samkomulag.

Requirements Process Conflicts:    
Skilningur á kröfum: Tryggja rödd allra hagsmunaaðila í ferlinu.
Kostnaður og lausnarmöguleikar: Ábyrgðarmaður tryggir sameiginlegan skilning.

[Árekstrar og úrlausnir](CONFLICTS.md)


## 4. Verkaskipting og ígrundun 
Stutt samantekt og hlekkur á skrána 
[Verkaskipting og ígrundun](VERKASKIPTING-IGRUNDUN.md)
