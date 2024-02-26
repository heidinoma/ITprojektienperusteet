# 1. (4 p.) Yksi Business/Project goal: Etsikää Wysockin kirjasta ohjetta, viittaus siihen vaaditaan. Muotoilkaa case-materiaalin avulla Project goal eli projektin tavoite oltava melko tarkalla tasolla. Eli liiketoimintaa tukeva projektin tavoite, "project goal" on se projektin lähtökohta.

Mansikkatilan verkkokauppa- ja toiminnanohjausjärjestelmän kehittäminen vaiheittain. Ensimmäisessä vaiheessa itsepoiminta-aikojen sekä valmiiksi poimittujen mansikoiden määrän ja noutoajankohdan varaaminen.
(Wysocki 2019, 178-180.)

# 2. (5 p.) Vaatimuksien kartoitus (RBS): Vähintään 5 kappaletta joista väh. 1 ylimmällä tasolla. voitte tehdä sisennettynä listana jonka juurena on ym. "Project goal"tai puuna (2-3 tasoa riittää). Miellekartta-muoto on myös ok. Priorisoikaa vaatimukset. (halutessanne voitte käyttää UML usecase kaavioita keskustelun tukena)

Mansikkatilan verkkokauppa- ja toiminnanohjausjärjestelmän kehittäminen

## #1 Itsepoiminnan varauksen tekeminen  
###        #1.1 Varauksen tekeminen verkkokaupassa  
####                #1.1.1 Poimintapäivän ja poimijamäärän valinta  
####                #1.1.2 Poimittavan kilomäärän arvion syöttäminen  
####                #1.1.3 Varausmaksun tekeminen  
####                #1.1.4 Jonotuslistalle jääminen, jos paikkoja ei ole vapaana  
###        #1.2 Varauksen tekeminen mobiilisovelluksessa  
####                #1.2.1 Poimintapäivän ja poimijamäärän valinta  
####                #1.2.2 Poimittavan kilomäärän arvion syöttäminen  
####                #1.2.3 Varausmaksun tekeminen  
####                #1.2.4 Jonotuslistalle jääminen, jos paikkoja ei ole vapaana  

#2 Mansikan myynti  
        #2.1 Ostaminen verkkokaupan kautta   
                #2.1.1 Lajikkeen ja kilomäärän valinta  
                #2.1.2 Varausmaksun tekeminen / lopullisen hinnan maksaminen  
        #2.2 Ostaminen mobiilisovelluksen kautta  
                #2.2.1 Lajikkeen ja kilomäärän valinta  
                #2.2.2 Varausmaksun tekeminen / lopullisen hinnan maksaminen  

#3 Asiakastilien hallinta  
        #3.1 Tilien luominen  
                #3.1.1 Rekisteröinti, kirjautuminen ja tietojen muokkaaminen  
                        #3.1.1.1 Ostohistorian tarkasteleminen  
                        #3.1.1.2 Asiakastietojen tarkastelu  
                        #3.1.1.3 Asiakastietojen muokkaaminen  
                        #3.1.1.4 Varausten muokkaaminen  
                        #3.1.1.5 Varausten peruuttaminen  
        #3.2 Skaalautuvuus käyttäjämäärän lisääntyessä  
        #3.3 Kanta-asiakasjärjestelmä  

#4 Toiminnanohjaus  
        #4.1 Työntekijämäärän hallinta  
                #4.1.1 Työntekijän varaaminen töihin  
                #4.1.2 Työmääräyksen teko  
                        #4.1.2.1 Poiminnan aloitusrivin osoittaminen  
                        #4.1.2.2 Poimittavan kilomäärän osoittaminen  

#5 Mansikan kypsymisennusteiden tekeminen ja liittäminen toiminnanohjaukseen  
        #5.1 Mansikan kypsymisen ennakointi  
                #5.1.1 Tilastotiedon hakeminen järjestelmään  
                #5.1.2 Säätietojen hakeminen järjestelmään  
                #5.1.3 Tilan omien satotietojen vienti järjestelmään  
                #5.1.4 Ennustelaskelmien tekeminen  
                #5.1.5 Pilaantuvan sadon määrän ennakointi  
        #5.2 Vapaana olevan sadon määrän laskeminen  
                #5.2.1 Tiedon vienti varaus-/myyntijärjestelmään > rivien vapauttaminen poimittavaksi  

Liitteenä projektin vaatimukset puumallina esitettynä: [Vaatimukset](Projektin vaatimukset.drawio.svg)

# 3. (5 p.)Projektin luokitus ja sen perustelu, (tarkalla tasolla, eli valitaan "kauppanimi" kuten scrum, tässä harjoituksessa ei ole pakko valita scrummia, mutta perustelu Wysockin mukaan arvoidaan. Perusoletus: tekijöiksi saadaan kokeneita ihmisiä)

Agile > iteratiivinen > PROTOTYPING. Agile, koska vaatimukset ovat kutakuinkin selvillä, mutta ratkaisut eivät. APM (agile project management) on toimiva esim. silloin, kun projektin onnistuminen on kriittistä yrityksen kannalta. Jos myynti-/varausjärjestelmä takkuilee, sato jää myymättä eikä tuloja muodostu. Agilessa myös asiakkaan (mansikkatila) osallistuminen prosessiin on välttämätöntä, toimivaa järjestelmää ei pysty rakentamaan ymmärtämättä syvällisesti toiminnan erilaisia prosesseja ja asiakkaan tarpeita. (Wysocki 2019, 46.) Iteratiivinen malli ja prototyping ovat perusteltuja, koska lopulliselta järjestelmältä vaaditaan hyvin paljon erilaisia ominaisuuksia. Perusliiketoiminnan saumattoman jatkumisen kannalta on parasta, että sovelluksesta julkaistaan ensin riisuttu malli joillakin perusominaisuuksilla, voidaan testata sitä käytännössä, ja parannella ja lisätä ominaisuuksia kokemusten perusteella. Satokausi ehtii myös mennä ohi, jos sovellusta viilataan liian pitkään, ja käyttöönotto menee seuraavaan kesään. (Mt., 48, 58, 382–384.)


# 4. (2 p.) RBS perusteella tarvittavan tiedon kartoitus: mitä tietoa vaatimukset täyttävä sovellus/tietojärjestelmä tarvitsee/käyttää. (Älkää ajatelko projektin toimintaan liittyvää tietoa tässä). mistä/mitä tietoa kerätään. Jonkinlainen jäsennelty tietomalli/lista (käsitemalli, jos joku teistä osaa). Kuvatkaa lyhyesti miten tietomallin olette tehneet.

Liitteenä Tietomalli draw.io:lla piirrettynä: [Tietomalli](Tietomalli.drawio.svg). Tietomallin pohjana käytetty projektin aiheena oleva sovellus-tietojärjestelmä mansikkatilalle, jossa vaatimuksina

1) Asiakas rekisteröi itsensä mobiiliapplikaation tai selaimen kautta järjestelmään. Tekee joko  
a) tilauksen hänelle poimituista marjoista ja hakee nämä paikan päältä ja maksaa etukäteen tilauksen teon yhteydessä.  
b) varaa itselleen paikan poimiakseen marjat itse.
2) Mansikkatila varaa tarvittava(t) työntekijät tilauksen a) täyttämiseen ja työntekijä osoitetaan poimittavalle riville sen mukaan, mitä toiminnanohjausjärjestelmä ohjaa saadun sääennusteen- ja tilastotiedon mukaan API:n kautta muusta järjestelmästä.
3) Asiakas ohjataan poimittavalle riville
4) Asiakas voi tehdä muutoksia ehtojen mukaan poimintavaraukseen
5) Asiakas menee odotuslistalle ja mahdollisesti vapautuva paikka osoitetaan autom. seuraavalle listalle.


# 5. (2 p.) RBS perusteella Karkea tietojärjestelmän osien kartoitus. Vähintään nimet ja lyhyet (!) kuvaukset. Millaisista osista project goalin ja siitä johdettujen vaatimusten täyttävä järjestelmä muodostuisi. Käyttäkää myös edellisen tehtäväosan tietomallia. Jos energiaa riittää niin:

https://en.wikipedia.org/wiki/Deployment_diagram
https://en.wikipedia.org/wiki/Component_diagram



# 6. (2 p.) Tehtävien kartoitus (WBS) tietojärjestelmän osien ja tarvittavan tiedon (edelliset kohdat) avulla.
Tässä teette esimerkiksi ensimmäisen iteraation/kierroksen/sprintin alustavan tehtävälistan
Edellyttää että valitsette jonkun vaatimuksen toteutettavaksi ja suunnitellut tehtävät liittyvät siihen.



# 7. (5 p.) versionhallinnan haarojen (branch) ja toiminnan suunnittelu. Päätelkää itse miten tämän hetkisen vaatimustilanteenne versionhallinta (branch/alimman tason vaatimus) pitäisi suunnitella. Voitte miettiä tulevaisuutta, ei vain 1. iteraatiota.
https://nvie.com/posts/a-successful-git-branching-model/
