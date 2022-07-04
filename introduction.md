

  ## Produktų sluoksniai
  „IRIS Focus“ palaiko iki 4 vienu metu rodomų radaro produktų ir žaibų produktų sluoksnių, kurie gali būti rodomi vienas ant kito (sluoksnių režimas) arba atskiruose segmentuose (tiles, „plytelių“ režimas).

  ![](/assets/img/layer_view.png)
  ![](/assets/img/tile_view.png)
  *Sluoksnių ir Tiles režimai*

  Skydelyje **Weather products** pateikiamas aktyvių produktų sluoksnių sąrašas.

  ### Tiles (plytelių) režimas
  Naudojant šį režimą, duomenų atvaizdavimo segmentai sinchronizuojami pagal numatytuosius nustatymus. Sinchronizuojant visi segmentai automatiškai pasislenka ir priartėja prie tų pačių koordinačių, kai sąveikaujate su vienu iš segmentų. 
  
  Jei norite išjungti sinchronizavimą, panaikinkite žymimojo langelio Synchronize tiles žymėjimą.

  ### Sluoksnių režimas
  Naudojant sluoksnių režimą, sluoksniai ekrane braižomi ta pačia tvarka, kokia jie išvardyti orų produktų lange. Norėdami pakeisti sluoksnių tvarką, vilkite juos į naujas pozicijas lange - produktai bus nubraižyti pagal naują tvarką
  
  Sluoksnių režimu pirmasis sluoksnis visada apibrėžia bendrą žemėlapio rodinio pateikimą. Pavyzdžiui, aplink radaro vietą esantys nuotolio žiedai remiasi 1 sluoksniu, todėl jei 1 ir 2 sluoksniuose esančių produktų nuotolio ribos yra atitinkamai 100 ir 250 km, nuotolio žiedai žemėlapio rodinyje piešiami tik iki 100 km, t. y. didžiausios 1 sluoksnyje esančio produkto nuotolio ribos. Orų duomenys iš 2 sluoksnio vis tiek piešiami žemėlapyje, nors „atrodo", kad jie yra už radaro veikimo zonos ribų. Tai taip pat turi įtakos radarų produktams, kuriuose yra tam tikrų papildomų vartotojo sąsajos elementų, pavyzdžiui, Maksimalūs duomenys (MAX).

  ## Produktų sluoksnio nustatymai

  Į skydelį **Weather Products** įtraukti orų produktų sluoksnių nustatymai. Šio skydelio turinys priklauso nuo orų produkto tipo.

  Skaidrumo (opacity) reikšmė, kuria nustatomas sluoksnio skaidrumas, yra prieinama visiems orų produktų sluoksniams.

  Produktų sluoksniams priskiriami šie atributai:

  | Pasirinkimas          | Aprašymas |
  | --------------------- | ----------- |
  | Data type  | Nustato išmatuotų duomenų tipą |
  | Height (CAPPI) <br> Elevation (PPI) | Nustato rodomo horizontalaus skerspjūvio aukštį (matuojant nuo jūros lygio) arba dabartinį antenos radaro pakėlimo kampą. |
  | Pseudo CAPPI  | Įjungia/išjungia Pseudo CAPPI. Pseudo CAPPI bando vizualizuoti tas radaro diapazono dalis, kurios nėra išmatuotos tiesiogiai.|
  | Smoothing  | Priklausomai nuo atstumo vienas nuo kito, gretimus pikselius sulieja arčiau vienas kito t. y. vaizdas tampa glotnesnis|
  | Threshold (BASE, TOPS, THICK) | Nustato atspindžio slenkstį (dBZ), nuo kurio priklauso vaizde rodomų duomenų kiekis.|
  |Composite Method|Peržiūrėdami sudėtinius duomenis iš daugelio radarų, galite pasirinkti kaip ekrane tvarkyti persidengiančius duomenis.|

  ## Radarų vietos

  Norėdami susidaryti platesnį vaizdą, pasirinkite iš anksto nustatytą arba sukurkite norimą  kompoziciją ir peržiūrėkite daugelio meteorologinių radarų sudėtinių duomenis.

  Daugiau apie kompozicijas iš skirtingų radarų skaitykite skyriuje [Kompozitai](#Kompozitai)

?>**Jei nematote norimo kompozito, kreipkitės į administratorių, kad jis jį sukonfigūruotų!**


1.	Viršutiniame meniu pasirinkite **Change site**. Įsijungia radaro vietos parinkimo režimas, kuriame rodoma:

    * Žemėlapio vaizdas, kuriame rodomi turimi radarai ir kompoziciniai vaizdai.

    *	Vietos parinkimo langas, kuriame išvardyti turimi radarai ir kompozitai.

2. Kad pasirinktumėte vieną ar kelis radarus galite atlikti vieną iš šių žingsnių: 

  * Žemėlapyje pasirinkite vieną ar daugiau radaro žiedų.

![](/assets/img/radar_sites.png)

**ARBA**

  * Lange **Change Site**  pasirinkite vietos pasirinkimo lauką, kad būtų parodytas galimų radarų sąrašas, ir sąraše pasirinkite vieną ar daugiau radarų. Pasirinkimai nurodomi žemėlapyje ir išvardijami lange Change Site.

![](/assets/img/change_site.png)

3.	Pasrinkite **OK**. Žemėlapyje rodomi duomenys iš pasirinkto radaro arba jų kompozito

## Animacijos laiko juosta

  Naudodami priartinamą animacijos laiko juostą galite lengvai vizualizuoti ir animuoti esamus, prognozuojamus ar istorinius duomenis. Histogramoje iš karto pateikiama informacija apie orų kiekį ir intensyvumą tam tikrais laiko momentais.

![](/assets/img/animation_timeline.png)

1.	Animacijos laiko juostoje pasirinkite duomenų, kuriuos norite peržiūrėti, laiką:
	* Norėdami sužinoti apytikslį laiką, pasukite indikatorių pirmyn ir atgal.
  
    * Jei norite priartinti ar atitolinti, slinkite pelės ratuku.
  
    *	Norėdami pasirinkti laiką, pasirinkite dešinėje laiko linijos pusėje esančią paieškos piktogramą
  
    *	Norėdami grįžti prie dabartinio laiko, pasirinkite **Now**

2.	Jei norite paleisti duomenų animaciją, pasirinkite Play.

    *	Išilgai laiko linijos perkelkite pradžios ir pabaigos laiko indikatorius.
  
    *	Kairėje laiko juostos pusėje esančiais valdikliais reguliuokite animacijos greitį.
  
    *	Norėdami nustatyti, kad būtų animuojama tik tam tikra orų istorijos dalis, vilkite pradžios ir pabaigos taškus į norimas laiko juostos padėtis. Animacijos nustatymai atnaujinami realiuoju laiku.
  
    *	Pagal numatytuosius nustatymus animacija sustoja 1 sekundei ir tik tada cikliškai grįžta į pradžią. Norėdami tai pakeisti, pasirinkite Preferences.

  Daugumos radaro produktų atnaujinimo intervalas yra 15 minučių, tačiau kai kurie atnaujinami kas 5 minutes arba kas 60 minučių. Animacijos trukmę apibrėžia sluoksnio Nr. 1, t. y. apatinio sluoksnio, atnaujinimo intervalas.


3. Norėdami peržiūrėti ir animuoti Nowcast duomenis, vilkite atkūrimo slankiklį išilgai laiko juostos į ateitį. Nowcasting atlieka advekcijos skaičiavimus pagal judėjimo duomenis iš radaro produktų, kad būtų galima prognozuoti orų judėjimą ir stiprumą iki 2 valandų į ateitį. Laiko žymos formatavimas rodo, kad ekrane rodomi nowcasting duomenys. 

## Žemėlapio įrankiai

### Kursorius

Užvedus pelės žymeklį ant žemėlapio rodinio, šalia jo atidaromas nedidelis langelis. Jame pateikiama informacija apie tos vietos produkto vertes. Žymeklio įrankis veikia ir sluoksniuotu, ir „plytelių“ režimu. Sluoksniuotais režimais langelyje rodomos kiekvieno gaminio vertės dabartinėje padėtyje, net jei atskiri segmentai nėra sinchronizuoti.

Pasirinkus kelis radaro produktus, žymeklio įrankis kiekvieno produkto vertes išvardija ta pačia tvarka, kokia jos rodomos ekrane. Kursoriaus įrankis visada rodo originalius duomenis, o ne nuglotnintus. *Daugiau informacijos žr. skyriuje Radarų produktų glotninimas.*

**Kursorius TimeSpan produktui**

Produkto "TimeSpan" žymeklio įrankis rodo informaciją apie naujausią žaibo įvykį, kai užvedate pelės žymeklį ant žemėlapyje esančios piktogramos. Žymeklio įrankis rodo žaibo įvykio laiką, vietą, amplitudę ir tipą. Be to, rodoma paklaidos elipsė, kuri parodo žaibo įvykio vietos tikslumą.

### Spalvų skalės redagavimas

Norėdami atverti redaktorių, lange pasirinkite Edit.

![](/assets/img/color_scale.png)

  Naudokite spalvų skalės redaktorių, kad sukurtumėte savo spalvų skalę. Redaktoriuje rodomas dabartinis spalvų skalės gradientas, o kairėje pusėje pateikiama peržiūra. Dešinėje pusėje pateikiamas spalvų skalės pagrindinių taškų sąrašas.

  Kiekvienas atraminis taškas rodo apibrėžtos vertės RGB spalvą radaro produkte, o vertės tarp atraminių taškų interpoliuojamos, kad būtų sukurtas sklandus gradientas. Optimizuodami rakto taškus pagal konkrečios vietovės sąlygas, galite labiau išskirti vienas kitam artimus matavimo intervalus ir pagerinti naudotojų galimybes atlikti vizualinę duomenų analizę.

  Atviros skalės nustatymas leidžia nustatyti, kaip žemėlapyje rodomos vertės, esančios už viršutinės ir apatinės spalvų gradiento ribos. Atviros skalės (open ended) toliau piešia už slenksčių esančias reikšmes ta pačia spalva kaip ir žemiausias arba aukščiausias spalvinės skalės rakto taškas. Neatviros skalės žemėlapyje nebraižo jokių už slenksčių esančių reikšmių.

  Naudodami gradiento režimą galite nustatyti spalvų vertes skirtingiems skalės žingsniams. Režimas "Ranges" (Diapazonai) leidžia tiksliau sureguliuoti spalvų skalių redagavimo parinktis. Šiuo režimu galite nustatyti, kad kiekvienas žingsnis tarp dviejų spalvų skalės pagrindinių taškų būtų gradientinis arba vienos vientisos spalvos.

1.	Slankiklyje „Scale type" pasirinkite Gradient arba Interval režimą.

2.	Iš išplečiamojo meniu Open Ended Scale  pasirinkite, ar norite naudoti atvirąją skalę, ar ne. 

3.	Spustelėkite juostelę ir pasirinkite naują spalvą iš spalvų rinkiklio arba įveskite naują skaitmeninę RGB vertę tiesiai į spalvos lauką.

### Skerspjūvio įrankis

  „IRIS Focus“ apskaičiuoja vertikaliuosius skerspjūvius pagal visų radaro produktų (on-demand) duomenis. 

  Skerspjūvio lange rodomas vertikalus atmosferos pjūvis pasirinktoje linijoje. Punktyrinėmis linijomis pažymėtos spindulio centro linijos, rodančios aukščius, kuriuose radarų signalas praėjo tam tikru atstumu. Oro reiškiniai piešiami tomis pačiomis spalvomis kaip ir pagrindiniame rodinyje. Teritorija, esanti už radaro veikimo zonos ribų, pažymėta pilka spalva.

![](/assets/img/cross.png)

1.	Žemėlapio rodinio viršutiniame dešiniajame kampe pasirinkite **Tools > Cross Section**

2.	Pasirinkite produktą

3.	Žemėlapyje galite pasirinkti:
  
  * Tiesią linija - spustelėkite du žemėlapio taškus, kad sukurtumėte vertikalaus radaro produkto skerspjūvio galinius taškus.

  * Lenkta linija - spustelėkite žemėlapyje ir vilkite pelės žymeklį, kad nubrėžtumėte laisvos formos lenktą liniją, tada atleiskite pelės mygtuką.

  * Skerspjūvis apskaičiuojamas tiesėje tarp šių galinių taškų. Vėliau kreivę ir galinius taškus galite perkelti.

4.	Jei norite, iš išskleidžiamojo meniu pakeiskite gaminio duomenų tipą.

*Pastaba: jei naudojate CAPPI tuomet pasirinktas aukštis atvaizduojamas raudona linija.*

### Liniuotės įrankis

Pasirinkite **Ruler Tool** tnorėdami išmatuoti atstumą tarp taškų žemėlapyje

![](/assets/img/ruler.png)

1.	Vartotojo sąsajos viršutiniame dešiniajame kampe pasirinkite **Tools > Ruler Tool**
2.	Žemėlapio rodinyje spustelėkite pradžios tašką, pastumkite pelę ir spustelėkite pabaigos tašką.Žemėlapyje rodomas atstumas tarp 2 taškų.
3.	Kai baigiate, meniu juostoje pasirinkite **Ruler Tool** kad išjungtumėte

### Ekrano vaizdo užfiksavimas

**Map** rodinyje, pasirinkite **Snapshot.** Pasirinkto ekrano vaizdas atsisiunčiamas į kompiuterį PNG formatu.

### Sekimo įrankis 

Naudokite sekimo įrankį orų frontų ar kitų matomų elementų judėjimui radaro produktuose stebėti. Vartotojo sąsajos viršutiniame dešiniajame kampe pasirinkite **Tools > Tracking Tool**

1.	Animacijos laiko juostoje vilkite atkūrimo šliaužiklį į tą vietą, kurioje norite pradėti ką nors stebėti.

2.	Žemėlapio rodinyje spustelėkite vietą, kurią ketinate stebėti. Paprastai tai būna orų fronto kraštas arba įdomus vietinis orų reiškinys.
Vilkite atkūrimo slankiklį į priekį ir pridėkite antrąjį sekimo tašką toje vietoje, kur, atrodo, judėjo stebimas įvykis.

Sekimo įrankis brėžia liniją, tęsdamas tą patį kelią ir greitį. Ekrane visada nubraižomos pirmosios 6 numatomos valandos. Norėdami paleisti sekimo tašką toliau, vilkite atkūrimo slankiklį į priekį.
Toliau pateiktame paveikslėlyje juodi apskritimai yra sekimo taškai, o mėlynas - būsimas įvertintas taškas, pagrįstas sekimo taškais. Šalia sekimo taškų esančiame plūduriuojančiame perdangos langelyje rodoma laiko žyma.

![](/assets/img/tracking.png)

3.	Baigę arba norėdami pradėti kitą sekimo įvykį, išvalykite sekimo taškus pasirinkę Tracking Tool (sekimo įrankis) > Clear tracking points (išvalyti sekimo taškus).

## Kompozitai

### Kompozitų peržiūrėjimas

„IRIS Focus“ gali sukurti dinamines kompozicijas, jei radaras siunčia RAW duomenis į "IRIS Analysis". Vietos parinkimo režimu šios vietos žemėlapyje pažymėtos baltais žiedais.

Iš anksto sukonfigūruotos kompozicijos, IRIS Analysis kompozicijos ir vietos, kurios nepalaiko dinaminių kompozicijų, žemėlapyje žymimos juodais žiedais. Šių svetainių radaro duomenis galite peržiūrėti po vieną.

1.	Viršutiniame meniu pasirinkite **Change Site**

2.	Įsijungia radaro vietos parinkimo režimas, kuriame rodoma:

  * Žemėlapio vaizdas su žemėlapyje rodomais turimais radarais ir kompozitais.
  
  * Vietos pasirinkimo langas, kuriame išvardyti turimi radarai ir kompozitai.

3.	Jei norite sukurti dinaminę kompoziciją, pasirinkite daugiau nei vieną radarą
o	Žemėlapyje pasirinkite 1 ar daugiau žiedų.

![](/assets/img/composite_rings.png)

4. Lange Change Site pasirinkite vietos pasirinkimo lauką, kad būtų parodytas galimų radarų sąrašas, ir sąraše pasirinkite vieną ar daugiau radarų.
 
![](/assets/img/radar_sites_composite.png) 

5.	Jei norite peržiūrėti iš anksto nustatytą arba IRIS analizės kompozitą, slinkite žemyn radarų sąrašu ir pasirinkite kompozitą iš sąrašo.

![](/assets/img/composite_list.png)
 
?>**Jei nematote norimo kompozito, kreipkitės į administratorių, kad jis jį sukonfigūruotų!**

6.	Lange **Weather Products** (Orų produktai) pasirinkite produktą ir duomenų tipą.

7.	Norėdami pakeisti sudėtinį metodą, lange **Weather Products** (Orų produktai) pasirinkite parinktį **Composite Method** (Sudėtinis metodas).

8.	Norėdami peržiūrėti sudėtinių duomenų skerspjūvį, pasirinkite **Cross section**.

### IRIS Focus kompozicijos metodai

Regionuose, kuriuose radarai persidengia, galite pasirinkti vieną iš toliau nurodytų radarų duomenų derinimo būdų:

-	Maksimalus

Duomenims sujungti naudojama didžiausia reikšmė. Šis nustatymas yra labiausiai paplitęs.

-	Vidutinis

Naudojamas turimų duomenų vidurkis. Tai prastas pasirinkimas, jei bandote apimti užblokuotus regionus.

## Labai mažos trukmės prognozė (nowcasting)

Naudojant nowcasting funkciją, advekcijos skaičiavimai atliekami pagal judėjimo duomenis iš radarų produktų, kad būtų galima prognozuoti kritulių zonų judėjimą ir intensyvumą iki 2 valandų į ateitį.

Šiuo laiko intervalu IRIS Focus gali gana tiksliai prognozuoti lokalius reiškinius reiškinius, pavyzdžiui, pavienes liūtis ir perkūnijas, naudodamas vaizdo advekcijos metodus. Kaip dalis šių metodų, nowcasting ekstrapoliuoja audros (aido) judėjimą N valandų į ateitį.

Nowcasting nesiekia į modelį įvesti fizikos dėsnių, kaip tai daroma skaitmeninio orų prognozavimo (NWP) metu. Naudojant advekcinę ekstrapoliaciją, o ne NWP, nowcasting gali apimti detales, kurių negali išspręsti NWP modeliai, veikiantys ilgesniais prognozavimo laikotarpiais.

Labai mažos trukmės prognozes gali naudoti kelių, energetikos ar oro uostų organizacijos, kad realiuoju laiku galėtų priimti reikalingus sprendimus.

![](/assets/img/nowcast.gif)

„IRIS Focus" nowcasting naudoja plotu pagrįstą metodą, kai judesio vektoriaus laukas (MVF) apskaičiuojamas visoje stebimoje teritorijoje.

Ekrane produktai perkeliami į ateitį. Nowcasting duomenis galite peržiūrėti IRIS Focus ekrane judindami slankiklį animacijos laiko juostoje. Kai esate prognozės režime, pasikeičia laiko žymų išvaizda, rodanti, kad žiūrite nowcasting duomenis.


## Vartotojo nustatymai

Jei norite peržiūrėti ir keisti konkretaus naudotojo nustatymus, pasirinkite Nustatymai. Galite keisti:
- slaptažodį
- numatytuosius animacijos nustatymus
- sąsajos kalbą
- IRIS Focus naudojamus matavimo vienetus. 

![](/assets/img/preferences.png)

## Produktų išsisaugojimas vėlesniam laikui
Daugelis  naudotojų dirba su tais pačiais žemėlapio vaizdais nuo vienos sesijos iki kitos. Naudodami **Saved views** galite išsaugoti dažnai naudojamus vaizdus, kad jie būtų pasiekiami kiekvieną kartą prisijungus prie "IRIS Focus".

![](/assets/img/saved_views.png)

1. Žemėlapio rodinyje nustatykite vaizdą, kurį norite išsaugoti. Pavyzdžiui, galite išsaugoti nustatymus:
    - **Weather Products**
    - Žemėlapio įrankius (skerspjūvio ar sekimo įrankiai ir pan.)
    - Priartinimo lygį
2.	Pasirinkite **Saved Views > Save.**
3.	Pasirinkite rodinį ir spauskite **Save.**
Naujas rodinys pridedamas prie Saved Views sąrašo vėlesniam naudojimui
4.	Norint atnaujinti išsaugotą rodinį:
    - **Saved Views** sąraše pasirinkite rodinį kurį norite atnaujinti.
    - Atnaujinkite nustatymus. pvz, pakeiskite priartinimo lygį ar produkto tipą
    - Pasirinkite **Saved Views > Save.**
    - Išsaugokite rodinį tokiu pačiu pavadinimu kaip ir norimas atnaujinti rodinys.
5.	Norėdami ištrinti išsaugotą rodinį, išsaugotų rodinių sąraše pasirinkite X šalia rodinio, kurį norite ištrinti.

## Radaro produktų pavadinimai (kodai)

Visi radaro produktai žymimi kodu, kuris nurodo atitinkamas gaminio charakteristikas. Kodai dažniausiai nurodomi tokiu formatu:

**[Produkto tipas]-[Duomenų tipas]-[Diapazonas]**

Pavyzdžiui, gaminys, pavadintas PPI-Z-400, yra:
  - PPI
    
    *PPI produktas*

  - Z
    
    *Matuojantis atspindį dBZ*

  - 400

    *iki 400 km. spinduliu*

 Weather Products skydelyje produktai išvardyti pagal savo kodus

![](/assets/img/product_codes.png)

## TimeSpan (žaibų) produkto konfigūracija

![](/assets/img/time_span.png)

Pasirinkite produktą Weather Products skydelyje.
  1.	Spauskite **Show details** , kad būtų parodyta detalesnė konfigūracija.
  2.	Naudokite Opacity slankiklį norėdami koreguoti TimeSpan sluoksnio skaidrumą. Galima nustatyti nuo 0 % (visiškai skaidrus) iki 100 % (visiškai nepermatomas).
  3.	Pasirinkite žaibų tipus, kuriuos norite vizualizuoti lange Lightning types (Žaibų tipai).
  4.	Pasirinkite spalvų skalę iš išskleidžiamosios juostos Color scale (spalvų skalė). Norėdami redaguoti pasirinktą spalvų skalę, spustelėkite Edit (redaguoti).
  5.	Spustelėkite **Hide details**, kad paslėptumėte išsamius gaminio nustatymus.

## Automatiniai perspėjimai

„IRIS Focus" gali pateikti perspėjimus apie orų reiškinius, pavyzdžiui, artėjančią smarkią audrą, turbulenciją ar potvynių tikimybę naudotojo nustatytose dominančiose teritorijose. Šią funkciją galima naudoti radaro produktams.

„IRIS Focus" sistemoje meteorologinis įvykis - tai įvykis, atitinkantis sukonfigūruotą įvykio kriterijų rinkinį. Įvykis rodomas ekrane kaip piktograma.
Meteorologinis įvykis tampa perspėjimu, kai sukonfigūruotas įvykio kriterijų rinkinys patenka į dominančią sritį.

Kai įvykis tampa perspėjimu, piktograma ir riba aplink sritį tampa raudonos spalvos. Galite užvesti pelės žymeklį ant srities, kad būtų parodyta daugiau informacijos apie perspėjimą. Pavyzdžiui, galite matyti, kuris radaras generavo duomenis, dėl kurių kilo perspėjimas. Aktyvių perspėjimų skaičius rodomas ekrano viršutiniame dešiniajame kampe esančioje piktogramoje Perspėjimai. Spustelėkite piktogramą, kad pamatytumėte aktyvių perspėjimų sąrašą.

Kad „IRIS Focus" rodytų įvykius, naudotojai turi sukurti įvykių kriterijus kiekvienam įvykiui, kurį jie nori matyti, ir pridėti įvykių kriterijus prie dominančios srities. Įgaliotasis naudotojas gali sukurti naujus įvykių kriterijus sistemoje. Tada ir įgaliotasis naudotojas, ir Focus naudotojas gali pridėti įvykių kriterijus prie dominančių sričių.
Kai įvykio kriterijus pridedamas prie dominančios srities, IRIS Focus palygina įvykio kriterijų su duomenimis, gautais iš visų diapazone esančių radarų. Jei visi kriterijai tenkinami, ekrane rodomas įvykis arba perspėjimas (priklausomai nuo vietos). Jei įvykio kriterijus nepriskiriamas jokiai dominančiai sričiai, "IRIS Focus" neatlieka to įvykio kriterijaus palyginimo patikrinimų ir jokie įvykiai nerodomi.

Priskyrus įvykio kriterijų kokiai nors dominančiai sričiai, gaunami įspėjimai apie tą kriterijų.

![](/assets/img/warnings.gif)

Jei atsiranda naujų to paties tipo įvykių toje pačioje dominančioje srityje, "IRIS Focus" išlaiko perspėjimą aktyvų. Kai per 20 minučių neatsiranda naujų įvykių, perspėjimas išjungiamas.
Dirbdami su istoriniais duomenimis, atsižvelkite į šiuos dalykus:
- Naršydami istorinius duomenis matote informaciją apie realiuoju laiku užfiksuotus orų reiškinius ir perspėjimus.
- Jei ištrinsite dominančią sritį arba tam tikrus perspėjimo kriterijus, ši sritis ir visi su ja susiję užregistruoti perspėjimai išliks matomi naršant istorinius duomenis.


## Dominančių teritorijų apibrėžimas

1.	Pasirinkite **Places of Interest.**
2.	Pasirinkite kokio tipo teritoriją norite apibrėžti: **Circle** (Apskritimo) or **Shape** (laisvos formos).
3.	Nurodykite unikalų teritorijos pavadinimą.
4.	Pasirinkite norimus nustatymus, jie skiriasi priklausomai nuo pasirinkto zonos tipo.
5.	Pasirinkite **Enabled.**
6.	Pasirinkite **Show label** kad būtų rodomas teritorijos pavadinimas.
Places of Interest rodinys, kai jis įjungtas, žemėlapyje taip pat rodoma įvykio kriterijaus piktograma, priskirta dominuojančiai sričiai.
7.	Priskirkite kriterijų pagal kurį bus išleistas įspėjimas.
8.	Pasirinkite  **Save.**

### Teritorijų redagavimas

1.	Žemėlapyje spustelėkite dominančią sritį. Atsidarys tos srities konfigūracijos langas.
2.	Atnaujinkite konfigūracijos nustatymus. 3. Taip pat galite pele reguliuoti srities matmenis žemėlapyje.
3.	Pasirinkite Išsaugoti.


### Darbas su apskritimais

![](/assets/img/circles.png)

1. Pasirinkite Places of Interest. Atsidaro langas su dominančiomis teritorijomis.
2. Pasirinkite **Circle** kad sukurtumėte naują sritį.
3. Suteikite dominuojančiai vietovei unikalų pavadinimą.
4. Norėdami apibrėžti sritį naudodami žemėlapio koordinates:
    - Nustatykite apskritimo centro platumą ir ilgumą.
    - Nustatykite apskritimo spindulį.
5. Nubrėžti apskritimą žemėlapyje:
    - Spustelėkite vietą žemėlapyje, kurioje norite nustatyti apskritimo centrą.
    - Vilkite pelę, kad nustatytumėte apskritimo spindulį.
    - Norėdami perkelti apskritimą žemėlapyje, vilkite apskritimo centro tašką.
    - Norėdami pakeisti apskritimo dydį žemėlapyje, naudokite aplink apskritimą esančius kampinius taškus.
6.Norėdami parodyti koncentrinius apskritimus tarp centrinio taško ir išorinio dominan2ios teritorijos apskritimo krašto, pasirinkite **Concentric circles**
7. Jei norite žemėlapyje rodyti dominančios teritorijos pavadinimą, pasirinkite **Show label** (rodyti etiketę).
8. Norėdami suaktyvinti dominačią  teritoriją, pasirinkite **Enabled**.
9. Pasirinkite **Save**.

### Darbas su laisvos formos teritorijomis

![](/assets/img/free_form.png)

1.	Pasirinkite **Places of Interest.**
2.	Pairinkite **Shape** norėdami sukurti naują teritoriją
    - Nurodykite unikalų pavadinimą
    - Žemėlapyje perkelkite žymeklį į vietą, kurioje norite pradėti piešti.
    - Norėdami suformuoti figūrą, spustelėkite taškus žemėlapyje.
    - Norėdami uždaryti figūrą, spustelėkite pradinį 
3.	Jei reikia tęskite radagavimą:
    - Norėdami pridėti naujų taškų prie figūros, užveskite pelę ant krašto, spustelėkite ir vilkite pelę.
    - Jei norite perkelti esamą tašką, užveskite pelės žymeklį ant jo, spustelėkite ir vilkite pelę..
4.	Jei norite kad žemėlapyje būtų rodomas teritorijos pavadinimas pasirinkite **Show label.**
5.	Norėdami aktyvuoti pasirinkite **Enabled**.
6.	Pasirinkite **Save**.

### Teritorijų ištrynimas

Pašalinus dominančią sritį, ateityje joje nebus galima stebėti reikšmingų orų įvykių ir perspėjimų. Peržiūrint istorinius duomenis, sritis ir visi užregistruoti tos srities perspėjimai lieka sistemoje.

1.	Norėdami ištrinti teritoriją per Places of Interest:
    - Pasirinkite **Places of Interest.**
    - Teritorijų sąraše pasirinkite **X** ties ta teritorija kurią norite ištrinti.
2.	Norėdami ištrinti teritoriją tiesiai iš žemėlapio:
    - Pasirinkite teritoriją kurią norite ištrinti.
    - Spauskite **DELETE**

Teritorija pašalinta, perspėjimai nebus siunčiami.

### Kriterijų priskyrimas

Norėdami gauti įspėjimus apie reikšmingus orus, turite priskirti vieną ar daugiau įvykio kriterijų rinkinių dominančiai sričiai.

![](/assets/img/criteria.png)

1.	Pasirinkite **Places of Interest.**
2.	**Places of Interest** skydelyje pasirinkite dominančią teritoriją
3.	**Event Criteria** sekcijoje pasirinkite **Add**
4.	**Event Criteria** skydelyje spustelėkite įvykio kriterijų rinkinio centrą, kad pritvirtintumėte jį prie srities. Prie dominančios srities galite pridėti daug įvykių kriterijų rinkinių.


### Perspėjimų atvaisdavimas

![](/assets/img/warnings.png)

1.	Pasirinkite Map Features.
2.	Pasirinkite Alerts.

Perspėjimai atvaizduojami žemėlapyje.

### Teritorijų atvaizdavimas

Galite valdyti, ar žemėlapyje rodomos įjungtos (Enabled) interesų sritys ir smeigtukai.

Jei interesų sritis yra (Enabled), gausite orų perspėjimus apie svarbius orus toje vietovėje, net jei ši vietovė nebus rodoma žemėlapyje.

![](/assets/img/areas_of_interest.png)


1.	Pasirinkite **Map Features**
2.	Pasirinkite **Enabled places of interest**




?> Like docsify-themeable? Be sure to check out [docsify-tabs](https://jhildenbiddle.github.io/docsify-tabs)!


