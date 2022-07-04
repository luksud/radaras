## IRIS rolės

Prieiga prie „IRIS Focus“ funkcijų priklauso nuo kiekvienam naudotojui priskirtų rolių.


| Rolė                  | Aprašymas |
| --------------------- | ----------- |
| Administrator  | Turi prieigą prie administravimo funkcijų |
| Focus Lighting User   | Turi pilną prieigą prie IRIS Focus funkcijų rinkinio skirto vizualizuoti žaibų aptikimo sistemos duomenis|
| Focus Weather Radar User  | Turi pilną prieigą prie IRIS Focus funkcijų rinkinio skirto vizualizuoti radarų duomenis|
| User  | Turi ribotą prieigą prie funkcijų prieinamų su IRIS Focus Light|
| Poweruser  | Gali naudotis visu „IRIS Focus“ funkcijų rinkiniu. <br> Gali sukurti organizacijos lygmens įvykių ir lankytinų vietų kriterijus, kurie matomi visiems organizacijos naudotojams. <br> Gali nustatyti ir tvarkyti iš anksto nustatytas  sudėtines dalis.<br>Gali sukonfigūruoti MVF, kurie bus naudojami trumpalaikėms prognozėms<br>Gali pasirinkti organizacijos lygmens žemėlapio projekciją |
|Kiosk user|Galima naudotis tik neinteraktyviuoju viso ekrano režimu.|

**Vietų paskirstymas ir apribojimai**

Kiekviena prisijungusio naudotojo paskyra, turinti **focus arba poweruser** rolę, rezervuoja vieną vietą iš licencijų fondo. Kai naudotojas išeina iš sistemos, vieta atlaisvinama. Naudotojo paskyra, turinti user ar administrator rolę arba kitą rolę be focus, patenka į IRIS Focus Light, kurioje yra žemėlapio vaizdas su ribotomis funkcijomis ir nesuteikiama prieiga prie tokių funkcijų, kaip skerspjūvis ar kiti radaro produktai. Jei naudotojas, turintis reikiamas prieigas, prisijungia ir nėra laisvų vietų, jis patenka į IRIS Focus Light. Kai laisva vieta atsiranda, naudotojui suteikiama galimybė persijungti į IRIS Focus.

## Žemėlapio rodinys

Pagrindinis „IRIS Focus" vaizdas - tai slankiojamas žemėlapio plotas, kurio centre yra pasirinkta radaras. Pagal numatytuosius nustatymus žemėlapis aplink sritį braižomas naudojant azimutinę lygiareikšmę projekciją, kurioje radaro vieta naudojama kaip atskaitos taškas.


Žemėlapio rodinyje galite pasirinkti kelis produktus vienu metu ir rodyti juos atskiruose languose arba jungtiniame sluoksnių persidengimo rodinyje. Produktai apima IRIS programinės įrangos sukurtus radaro ir žaibo produktus ir pasirinktinai WMS sluoksnius iš išorinių šaltinių.

![žemėlapio vaizdas](/assets/img/map_view.png)

## Žemėlapių sluoksniai

Žemėlapio fonas ir orų duomenų vizualizacijos braižomos kaip atskiri sluoksniai, o paskui sujungiamos į bendrą dabartinių oro sąlygų vaizdą. Žemėlapyje taip pat galite peržiūrėti WMS sluoksnius iš išorinių šaltinių, pavyzdžiui, palydovinių vaizdų sluoksnius.

![sluoksniai](/assets/img/layers.png)

**Baziniai (pagrindo) sluoksniai**

Fonas (dar vadinamas pagrindu) susideda iš kelių neinteraktyvių sluoksnių. Apačioje yra vietovės žemėlapis, kurį galima papildyti papildomais sluoksniais su keliais, administracinėmis ribomis ir kitais panašiais vietovės elementais.

**Produktų sluoksniai**

Interaktyvūs radaro ir žaibų produktų sluoksniai (1-4) braižomi ant foninių sluoksnių

**Išoriniai WMS sluoksniai**

Į žemėlapį galite įtraukti WMS sluoksnius iš išorinių šaltinių. Jie rodomi kaip produktų sluoksniai. Daugiau informacijos apie išorinius WMS sluoksnius rasite skyriuje Išoriniai WMS produktų sluoksniai.

### Bazinių sluoksnių redagavimas
Jei norite tvarkyti žemėlapio nustatymus, stilius ir papildomus žemėlapio sluoksnius, pvz., kelius, viršutiniame dešiniajame naudotojo sąsajos kampe pasirinkite Žemėlapio funkcijos. Galimi šie bazinio žemėlapio stiliai:

- **Standard**
  * Pagrindinis reljefas su vandenynais, ežerais, upėmis, sausumos masyvais ir salomis. Visi vandenys yra mėlyni, o visos sausumos teritorijos - pilkos. Miestai ir tankiai apgyvendintos vietovės yra rudos spalvos. Tai numatytasis žemėlapio vaizdas.

- **Simplified**
  * Toks pat kaip standartinis, be miestų.

- **Terrain**
  * Toks pat kaip standartinis, tik pridėta reljefo formų, kad geriau matytųsi kalnų grandinės ir kitos vietovės ypatybės.
