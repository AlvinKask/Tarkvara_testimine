# Tarkvara testimise 25 tüüpi

Tarkvara testimine on tarkvara arendusprotsessi jaoks ülioluline. See suurendab usaldust, säästab tarbetut aega ja vaeva probleemide lahendamisel ning aitab täiustada tarkvaraarenduse standardeid. Seetõttu on tarkvara testimisel väga oluline järgida hoolikalt kavandatud lähenemisviisi.

Kvaliteetse tarkvara tarnimiseks ei piisa aga ainult tarkvara testimise tarkvaraarendusprotsessi lahutamatuks osaks muutmisest. Samuti peate valima õiget tüüpi tarkvara testimise, mis teeb töö tehtud.

Mis on tarkvara testimine, miks peate valima õige testimise tüübi ja millised erinevad testimistüübid on selles valdkonnas saadaval? Loe edasi, et teada saada.

## Mis on tarkvaraarenduse testimine?
IBM defineerib tarkvara testimist kui tarkvara toimimise hindamist ja kontrollimist nii, nagu see peaks. Tarkvara on testitud turvalisuse, funktsionaalsuse ja kasutatavuse osas. Idee on tuvastada ja parandada vead enne toote väljalaskmist, et vältida kulukaid seisakuid, parandada jõudlust ja lasta turule kvaliteetset tarkvara.

## Miks on õige tarkvara testimise tüübi valimine teie ettevõtte jaoks oluline?
Kasutajatel on rakenduste kasutamisel kõrged ootused ja nad ei soovi mingeid kompromisse rakenduse jõudluse, töökindluse, kasutuslihtsuse ja turvalisuse osas. Seetõttu on tarkvara testimine hädavajalik ja peaks käima kõrvuti tarkvara arendusprotsessiga.

![1](https://user-images.githubusercontent.com/115221752/224541640-9b688543-340f-4fbf-ab22-370a73492290.JPG)

Veelgi kriitilisem on valida tarkvara testimise tüüp, mis sobib paremini teie projekti eesmärkide ja nõuetega. Õige tarkvara testimise tüüp võib teie ettevõttele kasu tuua järgmiselt.

- Tarkvara testimine on aega ja ressursse nõudev protsess. Nüüd, kui valite tarkvara testimise tüübi, mida te oma projekti jaoks ei vaja, või jätate olulise vahele – võite raisata aega ja ressursse.
- Õige tarkvara testimise lähenemisviis aitab teil keskenduda oma rakenduse olulistele aspektidele (haavatavus, SEO, usaldus, turvalisus) ja pakkuda klientidele kvaliteetset toodet.

## Tarkvara testimise tüübid
Sellised tarkvara testimise tüübid nagu agiilne testimine, mittefunktsionaalne testimine, automatiseerimise testimine ja funktsionaalne testimine ning nende alatüübid on tööstuses levinud. Igal testimisel on oma eelised, omadused ja puudused. Loe mõne sellise tarkvara testimise tüübi kohta.

## A. Funktsionaalne testimine
Funktsionaalsel testimisel kontrollime tarkvara vastavust selle kohaldatavatele nõuetele/spetsifikatsioonidele. Idee on tagada, et see toimiks vastavalt määratud nõuetele. Selle lähenemisviisi puhul testime iga tarkvara funktsiooni, pakkudes lihtsaid sisendeid, jäädvustades selle töödeldavaid väljundeid ja võrreldes neid tegelike tulemustega.

Mõned näited funktsionaalsest testimisest on järgmised:
- Kas kasutaja saab edukalt sisse logida seaduslike mandaatidega?
- Kas maksevärav lükkab makse tagasi ja kuvab veateate, kui kasutaja sisestab valed mandaadid?
- Kas kasutaja saab lisada ostukorvi uue kauba, kui ta klõpsab (osturakenduses) nupul „Lisa ostukorvi”?

Funktsionaalset testimist on erinevat tüüpi. Siin on mõned populaarsed:

## 1. Unit testing
![1](https://user-images.githubusercontent.com/115221752/224541922-f35239e1-f3a7-4203-ab2b-889414b14184.JPG)

Üksuse testimine on tarkvara testimise tehnika, mis hõlmab tarkvara üksiku üksuse või komponendi testimist, et kontrollida selle täpsust. Arendajad teevad seda tavaliselt tarkvaraarenduse etapis ja nende testide läbiviimiseks kasutavad nad testimise automatiseerimise tööriistu, nagu NUnit, Xunit ja JUnit.

Näiteks kui on olemas lihtne sõnumsiderakendus. Arendaja kirjutab enne lisafunktsioonide kallal töötamist seadmetesti, et kontrollida, kas kasutaja saab sõnumeid saata või vastu võtta. Üksuse testimine on hädavajalik, sest vigade leidmine ja parandamine arendusfaasis on hõlpsamini kättesaadav kui nende hilisem parandamine.

On olemas järgmist tüüpi üksuse testimine:

- White- box testing: testimistehnika, mille puhul rakenduse sisemine struktuur või kood on seda testivale isikule nähtav ja juurdepääsetav.
- Gorilla testing: Gorilla testimisel testime rakendusmoodulit põhjalikult kõigi oluliste aspektide osas. Selle tehnikaga testime rakenduse töökindlust.

## 2. Integration testing
Integratsioonitestimine on tarkvara testimise tüüp, mille puhul grupeerime loogiliselt kaks või enam rakendusmoodulit ja testime neid tervikuna. Idee on avastada viga erinevate moodulite vahelises suhtluses, liideses ja andmevoos.

Näiteks tooteotsing ja maksete töötlemine on veebipõhises osturakenduses kaks erinevat moodulit. Tõenäoliselt võivad need eraldi hästi töötada, kuid neil on andmevooga probleeme. Integratsioonitestimine aitab teil selliseid stsenaariume tuvastada ja parandada.

Siin on erinevat tüüpi integratsioonitestid.

- Gray-box testing: halli kasti testimine on musta kasti ja valge kasti testimise valik. Selle eesmärk on testida osa tarkvarast vastavalt spetsifikatsioonile.
- Big-bang integration testing: see tarkvara testimise lähenemisviis toimub samaaegselt kõigis moodulites, st neid mooduleid arendatakse, seotakse ja testitakse. See säästab aega ja vaeva.
- Top-down integration testing: ülalt-alla integratsiooni testimisel testime esmalt tarkvara olulisi aspekte ja seejärel liigume väiksemate osade poole.
- Bottom-up integration testing: alt-üles integratsiooni testimise lähenemisviis keskendub esmalt väikestele tarkvaraosadele ja jätkub, kuni see katab kogu tarkvarasüsteemi.
- Hybrid integration testing: hübriidintegratsiooni testimise lähenemisviis ühendab nii ülalt-alla kui ka alt-üles lähenemise plussid.
