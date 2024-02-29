# 1. Business/Project goal

Mansikkatilan verkkokauppa- ja toiminnanohjausjärjestelmän kehittäminen tarkoituksena helpottaa ja tehostaa mansikkatilan toiminnan ja työn hallintaa, varauksia ja myyntiä sekä parantaa asiakaskokemusta.

Perustelu: Tavoite on määritelty lyhyesti yhdellä lauseella. Se sisältää projektin tarkoituksen ja tavoitellun lopputuloksen korkealla tasolla niin yksinkertaisesti muotoiltuna, että kenen tahansa on helppo ymmärtää se. (Wysocki 178-179.)


(Perustelu: Wysock s.178: Goal on yksi lause 
Wysock s. 179
A project has one goal. The goal gives purpose and direction to the project. At a very high level, it defines the final deliverable or outcome of the project in clear terms so that everyone understands what is to be accomplished. 

Just like the problem or opportunity statement, the goal statement is short and to the point.)


# 2. (5 p.) Vaatimuksien kartoitus (RBS): Vähintään 5 kappaletta joista väh. 1 ylimmällä tasolla. voitte tehdä sisennettynä listana jonka juurena on ym. "Project goal"tai puuna (2-3 tasoa riittää). Miellekartta-muoto on myös ok. Priorisoikaa vaatimukset. (halutessanne voitte käyttää UML usecase kaavioita keskustelun tukena)

Mansikkatilan verkkokauppa- ja toiminnanohjausjärjestelmän kehittäminen

## #1 Itsepoiminnan varauksen tekeminen  
###       #1.1 Varauksen tekeminen verkkokaupassa  
####               #1.1.1 Poimintapäivän ja poimijamäärän valinta  
####               #1.1.2 Poimittavan kilomäärän arvion syöttäminen  
####               #1.1.3 Varausmaksun tekeminen  
####               #1.1.4 Jonotuslistalle jääminen, jos paikkoja ei ole vapaana  
###       #1.2 Varauksen tekeminen mobiilisovelluksessa  
####               #1.2.1 Poimintapäivän ja poimijamäärän valinta  
####               #1.2.2 Poimittavan kilomäärän arvion syöttäminen  
####               #1.2.3 Varausmaksun tekeminen  
####               #1.2.4 Jonotuslistalle jääminen, jos paikkoja ei ole vapaana  

## #2 Mansikan myynti  
###        #2.1 Ostaminen verkkokaupan kautta   
####               #2.1.1 Lajikkeen ja kilomäärän valinta  
####               #2.1.2 Varausmaksun tekeminen / lopullisen hinnan maksaminen  
###        #2.2 Ostaminen mobiilisovelluksen kautta  
####               #2.2.1 Lajikkeen ja kilomäärän valinta  
####               #2.2.2 Varausmaksun tekeminen / lopullisen hinnan maksaminen  

## #3 Asiakastilien hallinta  
###        #3.1 Tilien luominen  
####               #3.1.1 Rekisteröinti  
####               #3.1.2 Kirjautuminen  
####               #3.1.3 Asiakastietojen tarkastelu  
####               #3.1.4 Asiakastietojen muokkaaminen  
####               #3.1.5 Varausten/ostosten tekeminen  
####               #3.1.6 Ostohistorian tarkasteleminen  
####               #3.1.7 Varausten muokkaaminen  
####               #3.1.8 Varausten peruuttaminen  
###        #3.2 Skaalautuvuus käyttäjämäärän lisääntyessä  
###        #3.3 Kanta-asiakasjärjestelmä  
####               #3.3.1 Asiakaskohtaiset tarjoukset

## #4 Toiminnanohjaus  
###        #4.1 Työntekijämäärän hallinta  
####               #4.1.1 Työntekijän varaaminen töihin  
####               #4.1.2 Työmääräyksen teko  
#####                     #4.1.2.1 Poiminnan aloitusrivin osoittaminen  
#####                     #4.1.2.2 Poimittavan kilomäärän osoittaminen  

## #5 Mansikan kypsymisennusteiden tekeminen ja liittäminen toiminnanohjaukseen  
###        #5.1 Mansikan kypsymisen ennakointi  
####               #5.1.1 Tilastotiedon hakeminen järjestelmään  
####               #5.1.2 Säätietojen hakeminen järjestelmään  
####               #5.1.3 Tilan omien satotietojen vienti järjestelmään  
####               #5.1.4 Kypsymisennustelaskelmien tekeminen  
####               #5.1.5 Pilaantuvan sadon määrän ennakointi  
###        #5.2 Vapaana olevan sadon määrän laskeminen  
####               #5.2.1 Tiedon vienti varaus-/myyntijärjestelmään > rivien vapauttaminen poimittavaksi   

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


Liitteenä kaavio (Tietojärjestelmän osiot kaavio.png), jossa kartoitettu sekä verkkokaupan, että mobiilisovelluksen osia.

Tarkoituksena on siis mansikkatilan verkkokauppa- ja toiminnanohjausjärjestelmän kehittäminen, jonka tarkoituksena on helpottaa ja tehostaa mansikkatilan toiminnan ja työn hallintaa, 
varauksia ja myyntiä sekä parantaa asiakaskokemusta.

Tietojärjestelmässä olisi siis product serverissä mansikan myyntiportaali, varausjärjestelmä itsepoiminnalle, asiakastilien hallintaportaali ja toiminnanohjausjärjestelmä, 
joka pitää sisällään myös mansikan kypsymisen ennustamisen.

Myyntiportaalissa myydään tilan poimimaa mansikkaa. Sieltä asiakas voi valita mansikkalajikkeen ja kilomäärän jonka mansikkaa haluaa ostaa ja varata määrän ja maksaa verkkopankkimaksuna ennakkoon.

Itsepoiminnan varausjärjestelmässä voi varata itselleen mansikanpoiminta ajan tietylle päivälle ja tietylle poimija määrälle, 
arvioida kilomäärän jonka haluaa poimia ja jos ei ole vapaita paikkoja poimijaksi kyseisellepäivälle niin jäädä jonotuspaikalle. Haluamansa mansikkamäärän voi maksaa online.

Tietojärjestelmä pitää sisällään myös asiakastietojen hallintaportaalin. Sielä voi rekisteröidä asiakastilin, kirjautua sisään, tarkastella ja muokata omia tietojaan, 
tehdä varauksia ja ostoksia, tarkastella ostohistoriaa, perua ja muokata varauksia. Se myös skaalautuisi asiakasmäärän lisääntyessä ja sitten luotaisiin kanta-asiakasjärjestelmä, 
jonka kautta saisi asiakaskohtaisia tarjouksia.

Toiminnanohjausjärjestelmässä voi hallita työntekijämäärää. Sielä voi varata työntekijöitä töihin ja antaa työmääräyksiä eli määrittää aloitusrivi poimimiselle ja osoittaa poimittavan mansikan kilomäärä. Toiminnanohjaukseen on liitetty myös mansikan kypsymisennusteen tekeminen, joka pitää sisällään mansikan kypsymisen ennakoinnin paikallisten sään tilastotietojen ja säätietojen hakemisen järjestelmään, 
tilan omien satotietojen viennin järjestelmään ja näiden pohjalta kypsymisennusteiden tekemisen ja pilaantuvan sadon määrän ennakoinnin. 
Toiminnanohjausjärjestelmän avulla voidaan myös laskea vapaana olevan sadon määrää ja viedä tiedot varaus- ja myyntijärjestelmään.


https://en.wikipedia.org/wiki/Deployment_diagram
https://en.wikipedia.org/wiki/Component_diagram


# 6. (2 p.) Tehtävien kartoitus (WBS) tietojärjestelmän osien ja tarvittavan tiedon (edelliset kohdat) avulla.
(Tässä teette esimerkiksi ensimmäisen iteraation/kierroksen/sprintin alustavan tehtävälistan
Edellyttää että valitsette jonkun vaatimuksen toteutettavaksi ja suunnitellut tehtävät liittyvät siihen.)

Iteratiivisessa Agilessa mallissa, iteraatio kulkee Scope, Plan, Launch, Execute ja Close vaiheiden läpi. Meidän projektisuunnitelmamme keskittyy prototyping malliin, jossa vielä lisäksi keskitytään enemmän ideoimiseen, suunnittelemiseen, prototyypin tekemiseen, joka esitellään asiakkaalle, asiakas kertoo prototyypistä palautteen ja mahdolliset muutosehdotukset, tehdään muutokset tuotteeseen ja uusi prototyyppi. Tämä sykli jatkuu kunnes, joko asiakkaan rahat tai aika loppuvat tai kun saadaan toimiva ja vaatimuksia vastaava tuote aikaiseksi. 

WBS (Work Breakdown Structure) tarkoituksena on Scopen tavoitteiden ja vaatimusten hajottaminen pieniin aktiviteetteihin. Kun aktiviteetit on hajotettu tarpeeksi pieniin osiin, niistä tulee työtehtäviä. WBS on valmis, kun tehtävät ovat mittavissa sen mukaan missä vaiheessa ne ovat menossa vai ovatko valmiita, aktiviteetti on sidottavissa, aktiviteetista pystytään tekemään toteutettava tuote, työskentelyyn käytettävä aika ja kustannukset ovat mitattavissa, toiminnan kesto on hyväksyttävissä rajoissa ja työtehtävät ovat itsenäisiä. Prototyping mallissa, tehtävien kesto on lyhyt, koska oppimista ja kehittymistä tapahtuu koko ajan tuotetta kehitettäessä valmiimmaksi vaatimusten ja muokkausehdotusten mukaan, kohti julkaisua, asiakkaan kanssa yhdessä tiiviisti työskennellen. (Wysocki, s.211-213.)


# 7. (5 p.) versionhallinnan haarojen (branch) ja toiminnan suunnittelu. Päätelkää itse miten tämän hetkisen vaatimustilanteenne versionhallinta (branch/alimman tason vaatimus) pitäisi suunnitella. Voitte miettiä tulevaisuutta, ei vain 1. iteraatiota.
https://nvie.com/posts/a-successful-git-branching-model/
