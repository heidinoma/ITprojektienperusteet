# 1. (4 p.) Yksi Business/Project goal: Etsikää Wysockin kirjasta ohjetta, viittaus siihen vaaditaan. Muotoilkaa case-materiaalin avulla Project goal eli projektin tavoite oltava melko tarkalla tasolla. Eli liiketoimintaa tukeva projektin tavoite, "project goal" on se projektin lähtökohta.

Mansikan itsepoimintatilan varausjärjestelmän kehittäminen: poiminta-aikojen varaaminen sekä valmiiksi poimittujen mansikoiden noutoajankohdan     varaaminen (joku aikamääre tähän, ts. aika projektin aloituksesta, ei varsinainen valmistumisajankohta?)
(Wysocki 2019, 178-180.)

# 2. (5 p.) Vaatimuksien kartoitus (RBS): Vähintään 5 kappaletta joista väh. 1 ylimmällä tasolla. voitte tehdä sisennettynä listana jonka juurena on ym. "Project goal"tai puuna (2-3 tasoa riittää). Miellekartta-muoto on myös ok. Priorisoikaa vaatimukset. (halutessanne voitte käyttää UML usecase kaavioita keskustelun tukena)

Varauksen tekeminen ja muuttaminen
- toimivuus sekä mobiilisovelluksessa että nettisivuilla?
- pääsynhallinta
-	poimintapäivän ja poimijamäärän valinta
-	valmiiksi poimittujen mansikoiden varaaminen
-	asiakkaan ennakkoarvio poimimastaan määrästä / suoraan ostettavan mansikan kg-määrä
-	varausmaksun mahdollistaminen?
-	varasijat ja jonottaminen vapautuville poiminta-ajoille
-	poiminta-astioiden varaaminen tarvittaessa
-	peruuttaminen erikseen määriteltyjen ehtojen mukaan
-	kanta-asiakasjärjestelmä usein asioiville
-	helposti skaalautuva käyttäjämäärän lisääntyessä

Säätilan huomiointi ja integrointi varausjärjestelmään:
-	mansikan kypsymisaikataulun huomioiminen
-	mansikan pilaantumisen ennakointi
-	vapaana olevan sadon määrän laskeminen
-	poimintaolosuhteiden huomiointi?
-	olemassa olevan datan hyödyntäminen laskelmissa
-	uuden datan tallentaminen ja hyödyntäminen laskelmissa


# 3. (5 p.)Projektin luokitus ja sen perustelu, (tarkalla tasolla, eli valitaan "kauppanimi" kuten scrum, tässä harjoituksessa ei ole pakko valita scrummia, mutta perustelu Wysockin mukaan arvoidaan. Perusoletus: tekijöiksi saadaan kokeneita ihmisiä)

Agile > iteratiivinen > PROTOTYPING. Agile, koska vaatimukset ovat kutakuinkin selvillä, mutta ratkaisut eivät. APM (agile project management) on toimiva esim. silloin, kun projektin onnistuminen on kriittistä yrityksen kannalta. Jos myynti-/varausjärjestelmä takkuilee, sato jää myymättä eikä tuloja muodostu. Agilessa myös asiakkaan (mansikkatila) osallistuminen prosessiin on välttämätöntä, toimivaa järjestelmää ei pysty rakentamaan ymmärtämättä syvällisesti toiminnan erilaisia prosesseja ja asiakkaan tarpeita. (Wysocki 2019, 46.) Iteratiivinen malli ja protoilu ovat perusteltuja, koska järjestelmältä vaaditaan hyvin paljon erilaisia ominaisuuksia. Perusliiketoiminnan saumattoman jatkumisen kannalta on parasta, että sovelluksesta julkaistaan ensin riisuttu malli joillakin perusominaisuuksilla, voidaan testata sitä käytännössä, ja parannella ja lisätä ominaisuuksia kokemusten perusteella. Satokausi ehtii myös mennä ohi, jos sovellusta viilataan liian pitkään, ja käyttöönotto menee seuraavaan kesään. (Mt., 48, 58, 382–384.)


# 4. (2 p.) RBS perusteella tarvittavan tiedon kartoitus: mitä tietoa vaatimukset täyttävä sovellus/tietojärjestelmä tarvitsee/käyttää. (Älkää ajatelko projektin toimintaan liittyvää tietoa tässä). mistä/mitä tietoa kerätään. Jonkinlainen jäsennelty tietomalli/lista (käsitemalli, jos joku teistä osaa). Kuvatkaa lyhyesti miten tietomallin olette tehneet.

Liitteenä Tietomalli draw.io:lla piirrettynä. Tietomallin pohjana käytetty projektin aiheena oleva sovellus-tietojärjestelmä mansikkatilalle, jossa vaatimuksina

1) Asiakas rekisteröi itsensä mobiiliapplikaation tai selaimen kautta järjestelmään. Tekee joko
a) tilauksen hänelle poimituista marjoista ja hakee nämä paikan päältä ja maksaa etukäteen tilauksen teon yhteydessä.
b) varaa itselleen paikan poimiakseen marjat itse.
2) Mansikkatila varaa tarvittava(t) työntekijät tilauksen a) täyttämiseen ja työntekijä osoitetaan poimittavalle riville sen mukaan, mitä toiminnanohjausjärjestelmä ohjaa saadun sääennusteen- ja tilastotiedon mukaan API:n kautta muusta järjestelmästä.
3) Asiakas ohjataan poimittavalle riville
4) Asiakas voi tehdä muutoksia ehtojen mukaan poimintavaraukseen
5) Asiakas menee odotuslistalle ja mahdollisesti vapautuva paikka osoitetaan autom. seuraavalle listalle.

[Tietomalli](Tietomalli.drawio.svg)

# 5. (2 p.) RBS perusteella Karkea tietojärjestelmän osien kartoitus. Vähintään nimet ja lyhyet (!) kuvaukset. Millaisista osista project goalin ja siitä johdettujen vaatimusten täyttävä järjestelmä muodostuisi. Käyttäkää myös edellisen tehtäväosan tietomallia. Jos energiaa riittää niin:
https://en.wikipedia.org/wiki/Deployment_diagram
https://en.wikipedia.org/wiki/Component_diagram



# 6. (2 p.) Tehtävien kartoitus (WBS) tietojärjestelmän osien ja tarvittavan tiedon (edelliset kohdat) avulla.
Tässä teette esimerkiksi ensimmäisen iteraation/kierroksen/sprintin alustavan tehtävälistan
Edellyttää että valitsette jonkun vaatimuksen toteutettavaksi ja suunnitellut tehtävät liittyvät siihen.



# 7. (5 p.) versionhallinnan haarojen (branch) ja toiminnan suunnittelu. Päätelkää itse miten tämän hetkisen vaatimustilanteenne versionhallinta (branch/alimman tason vaatimus) pitäisi suunnitella. Voitte miettiä tulevaisuutta, ei vain 1. iteraatiota.
https://nvie.com/posts/a-successful-git-branching-model/
