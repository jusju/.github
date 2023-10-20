# [](#) Ohjelmointi 2

Tällä kurssilla syvennämme ohjelmointiosaamistamme ja sovellamme aiemmin oppimianne ohjelmointitaitoja mm. tietokantojen parissa. Syvennymme kielen syntaksin ja tarvittavien kirjastojen lisäksi myös yksikkötestaukseen, automaatiotyökaluihin sekä versionhallintaan.

Tämä kurssisivu täydentää Ohjelmointi 2 -toteutusten yhteistä [ohjelmointi2.github.io](https://ohjelmointi2.github.io)-sivustoa ja sisältää erityisesti tietoa virtual- ja online-toteutusten käytännön järjestelyistä.


## [](#) Sisältö viikoittain

Kurssi on maanantaisin ja keskiviikkoisin kello 8:00AM - 10:30AM.

Kurssin osasuorituksiin kuuluu viikoittaiset harjoitustehtävät kurssin eri osa-alueista. Tehtävien teknisessä toteutuksessa hyödynnetään GitHub classroom -palvelua sekä Teams-ryhmää. Tehtävät tulee palauttaa aikataulun mukaisesti.


### [](#) Viikko 1: Versionhallinta ja kurssin työkalut

Kurssin ensimmäisellä viikolla tutustumme työkaluihin, joita tulemme hyödyntämään koko loppukurssin ajan. Tavoitteenamme on, että sovellusta voidaan suorittaa suoraviivaisesti myös koodieditorin ulkopuolella ja että sovelluksen kääntäminen, riippuvuuksien asentaminen, paketointi sekä testaaminen voidaan tarvittaessa automatisoida.

Git-versionhallintaa käytetään tällä kurssilla tehtävien jakeluun, niiden palauttamiseen sekä automaattiseen arviointiin. Myöhemmillä kursseilla ja työelämässä tulet todennäköisesti käyttämään versionhallintaa oleellisena osana jokapäiväistä työskentelyä.

Kurssin Java-sisältö kertaa Ohjelmointi 1:llä käsiteltyjä aiheita ja tavoitteena on, että kaikilla osallistujilla on ensimmäisen viikon jälkeen riittävä lähtötaso mm. kokoelmista ja olio-ohjelmoinnista seuraavien aiheiden opiskelemiseksi.

**Suositellut materiaalit**

*Git*

* [What is version control? (Atlassian)](https://www.atlassian.com/git/tutorials/what-is-version-control). Katso myös [video](https://youtu.be/xQujH0ElTUg).
* [What is Git (Atlassian)](https://www.atlassian.com/git/tutorials/what-is-git)
* [Install Git (Atlassian)](https://www.atlassian.com/git/tutorials/install-git)
* [Git Cheat Sheet, pdf (GitHub)](https://education.github.com/git-cheat-sheet-education.pdf)

*Gradle*

* [Gradle tutorial for complete beginners (YouTube)](https://youtu.be/-dtcEMLNmn0)

**Tehtävät (DL 29.10.)**

💡 *Huom! Voit tutustua tehtäviin näiden linkkien kautta, mutta toteuta oma ratkaisusi omaan kopioosi, jonka saat tehtyä Teams-tehtävän ohjeen mukaisesti.*

* [Git "Hello world"](https://github.com/ohjelmointi2/git-hello-world/)
* [Warming up (kurssin lämmittelytehtävät)](https://github.com/ohjelmointi2/warming-up)


----

### [](#) Viikko 2: Map-tietorakenne

> *"Hajautustaulu eli HashMap on ArrayListin lisäksi eniten käytettyjä Javan valmiiksi tarjoamia tietorakenteita. Hajautustaulua käytetään kun tietoa käsitellään avain-arvo -pareina, missä avaimen perusteella voidaan lisätä, hakea ja poistaa arvo."*
>
> [*Agile Education Research –tutkimusryhmä, mooc.fi*](https://ohjelmointi-20.mooc.fi/osa-8/2-hajautustaulu)

**Suositellut materiaalit**

* [Map and HashMap in Java (Coding with John, YouTube)](https://youtu.be/H62Jfv1DJlU)
* [Using Maps to Store Key Value Pairs (dev.java)](https://dev.java/learn/api/collections-framework/maps/)
* [Managing the Content of a Map (dev.java)](https://dev.java/learn/api/collections-framework/working-with-keys-and-values/)

**Tehtävät (DL 5.11.)**

💡 *Huom! Voit tutustua tehtävään tämän linkin kautta, mutta toteuta oma ratkaisusi omaan kopioosi, jonka saat tehtyä Teams-tehtävän ohjeen mukaisesti.*

* [Map exercises](https://github.com/ohjelmointi2/map-exercises)

----

### [](#) Viikko 3: Yksikkötestaus

Tällä viikolla tutustumme JUnit-yksikkötestaukseen ja kirjoitamme omia yksikkötestejä valmiille koodille.

**Suositellut materiaalit**

* [JUnit 5 User Guide (junit.org)](https://junit.org/junit5/docs/current/user-guide/)
* [Java Unit Testing with JUnit (Coding with John, YouTube)](https://youtu.be/vZm0lHciFsQ)

**Tehtävät (DL 12.11.)**

* JUnit exercise (linkki tulossa)

----

### [](#) Viikko 4: Perintä ja rajapinnat

Tällä viikolla syvennämme olio-ohjelmointiosaamistamme tutustumalla perintään ja rajapintoihin. Perintä ja rajapinnat ovat olio-ohjelmoinnin ratkaisuja koodin uudelleenkäytettävyyden ja yhteensopivuuden edistämiseksi.

**Suositellut materiaalit**

* [Objects, Classes, Interfaces, Packages, and Inheritance (dev.java)](https://dev.java/learn/oop/)
* [Java Polymorphism Fully Explained In 7 Minutes (Coding with John, YouTube)](https://youtu.be/jhDUxynEQRI)
* [Super Keyword in Java Full Tutorial - How to Use "super" (Coding with John, YouTube)](https://www.youtube.com/watch?v=Qb_NUn0TSAU)

**Tehtävät (DL 19.11.)**

* Interfaces and inheritance (linkki tulossa)

-----

### [](#) Viikko 5: Streamit ja lambdat

> *"The **Stream API** is probably the second most important feature added to Java SE 8, after the **lambda expressions**. In a nutshell, the Stream API is about providing an implementation of the well known map-filter-reduce algorithm to the JDK.*
>
> *The Collections Framework is about storing and organizing your data in the memory of your JVM. You can see the Stream API as a companion framework to the Collections Framework, to process this data in a very efficient way. Indeed, you can open a stream on a collection to process the data it contains."*
>
> Processing Data in Memory Using the Stream API. https://dev.java/learn/api/streams/map-filter-reduce/

**Suositellut materiaalit**

* [The Stream API (dev.java)](https://dev.java/learn/api/streams/)
* [Lambda Expressions in Java (Coding with John, YouTube)](https://youtu.be/tj5sLSFjVj4)
* [Optionals In Java (Coding with John, YouTube)](https://youtu.be/vKVzRbsMnTQ)
* [The Java 8 Stream API Tutorial (baeldung.com)](https://www.baeldung.com/java-8-streams)

**Tehtävät (DL 26.11.)**

💡 *Huom! Voit tutustua tehtävään tämän linkin kautta, mutta toteuta oma ratkaisusi omaan kopioosi, jonka saat tehtyä Teams-tehtävän ohjeen mukaisesti.*

* [Streams and Lambdas](https://github.com/ohjelmointi2/streams-and-lambdas)

-----

### [](#) Viikko 6: JDBC & DAO

Tällä viikolla opettelemme ensin muodostamaan yhteyden tietokantaan Java-ohjelmasta käsin ja tekemään yksinkertaisia CRUD-toimenpiteitä (Create, Read, Update & Delete). Tustumme myös DAO-kehitysmalliin, jossa sekä tietokantaoperaatiot ja tietokannan sisältämä data mallinnetaan Java-luokkien avulla.

**Suositellut materiaalit**

* [Java Database Connectivity (Telusko, YouTube)](https://youtu.be/7v2OnUti2eM)
* [Introduction to JDBC (baeldung.com)](https://www.baeldung.com/java-jdbc)

**Tehtävät (DL 3.12.)**

💡 *Huom! Voit tutustua tehtävään tämän linkin kautta, mutta toteuta oma ratkaisusi omaan kopioosi, jonka saat tehtyä Teams-tehtävän ohjeen mukaisesti.*

* [SQL databases (Chinook, JDBC & DAO)](https://github.com/ohjelmointi2/sql-databases/)

-----

### [](#) Viikko 7: Tietorakenteet ja algoritmit

> *"Algoritmi (algorithm) on toimintaohje, jota seuraamalla voimme ratkaista jonkin laskennallisen ongelman. Algoritmille annetaan syöte (input), joka kuvaa ratkaistavan ongelman tapauksen, ja algoritmin tulee tuottaa tuloste (output), joka on vastaus sille annettuun syötteeseen"*
>
> Antti Laaksonen, [Tietorakenteet ja algoritmit -kirja](https://github.com/pllk/tirakirja/raw/master/tirakirja.pdf)

**Suositellut materiaalit**

*Videot*

* [Sorting Algorithms Explained Visually (Beyond Fireship)](https://youtu.be/RfXt_qHDEPw)
* [Quicksort Sort Algorithm in Java (Coding with John, YouTube)](https://www.youtube.com/watch?v=h8eyY7dIiN4)
* [Merge Sort Algorithm in Java (Coding with John, YouTube)](https://www.youtube.com/watch?v=bOk35XmHPKs)
* [Insertion Sort Algorithm in Java (Coding with John, YouTube)](https://www.youtube.com/watch?v=0lOnnd50cGI)
* [Bubble Sort Algorithm Tutorial in Java (Coding with John, YouTube)](https://www.youtube.com/watch?v=g8qeaEd2jTc)

*Artikkelit*

* [Tietorakenteet ja algoritmit -kirja](https://github.com/pllk/tirakirja/raw/master/tirakirja.pdf)
* [Algorithms Every Programmer Should Know (dev.to)](https://dev.to/surajondev/algorithms-every-programmer-should-know-part-1-searching-algorithm-1hd3)
* [10 Algorithms Every Developer Should Learn (dev.to)](https://dev.to/codesphere/10-algorithms-every-developer-should-learn-3lnm)
* [6 Data Structures Every Programmer Should Learn (medium.com)](https://medium.com/javarevisited/6-data-structures-every-programmer-should-learn-a24de0f3fc3b)

**Tehtävät (DL 10.12.)**

💡 *Huom! Voit tutustua tehtävään tämän linkin kautta, mutta toteuta oma ratkaisusi omaan kopioosi, jonka saat tehtyä Teams-tehtävän ohjeen mukaisesti.*

* [Sorting & Filtering](https://github.com/ohjelmointi2/sorting-and-filtering)


-----

### [](#) Viikko 8: Syventävät ja soveltavat aiheet

Kurssin lopussa syvennämme ja sovellamme aikaisempia aiheita, ja perehdymme mm. rinnakkaisuuden ja rekursion käsitteisiin.

**Tehtävät (DL 17.12.)**

* Tehtävät julkaistaan kurssin aikana

-----

&nbsp;

## [](#) ✅ Osallistumisen vahvistaminen

**Kurssin osallistumisen vahvistaminen edellyttää ensimmäisen viikon tehtävien palauttamista määräaikaan mennessä.** Ensimmäiset tehtävät ovat luonteeltaan aikaisempaa osaamista kertaavia ja tehtäviin on saatavissa vinkkejä sekä tukea kurssin keskustelukanavalla.

> *"Opiskelija vahvistaa paikkansa opintojaksototeutuksella olemalla läsnä opetuksen alkaessa tai muutoin opettajan ilmoittamalla tavalla, joka voi esimerkiksi olla ensimmäisen oppimistehtävän palautus."*
>
> [Tutkintosääntö](https://www.haaga-helia.fi/fi/tutkintosaanto-noudatettavat-normit-ja-muutoksenhaku)

Tämän käytännön ei ole tarkoitus estää ketään opiskelemasta tai suorittamasta kurssia, vaan sen on tarkoitus varmistaa, että kurssi lähtee kaikilla onnistuneesti käyntiin.

Kurssin keskeyttäminen ei ole [Haaga-Helian linjauksia](https://mynet.haaga-helia.fi/group/pakki/toteutukselle-ilmoittautuminen) noudattaen mahdollista enää osallistumisen vahvistamisen jälkeen.


## [](#) 💬 Viestintäkanavat

Tällä toteutuksella viestintä tapahtuu MS Teams -palvelussa. Jos jäät jumiin koodisi kanssa tai et ymmärrä materiaaleja tai tehtävänantoja, kysy rohkeasti vinkkejä. Todennäköisesti samaa ongelmaa pohtii kanssasi myös moni muu, joten lähetäthän sisältöä ja tehtävänantoja koskevat kysymykset yhteiselle kanavalle eikä yksityisviestinä.


## [](#) 📥 Palautettavat tehtävät

Kurssilla on viikoittaisia tehtäviä, jotka tulee palauttaa annettuihin määräaikoihin mennessä. Tehtävät löytyvät Teamsista, ja ne palautetaan GitHubiin. Apua tehtävien tekoon on saatavissa kurssin keskustelukanavalla niin opettajalta kuin muiltakin opiskelijoilta.


## [](#) 📊 Arviointi

Kurssi arvioidaan asteikolla 0-5. Kurssin loppuarvosana lasketaan kurssin tehtävien keskiarvosta siten, että jokaisen viikon tehtävillä on sama painoarvo. Yksittäisten tehtävien arvosanoja ei pyöristetä, vaan mahdollinen pyöristys tehdään vasta loppuarvosanaa laskettaessa.


## [](#) ⏱️ Kurssin työmäärä

Opintojakso kestää 8 viikkoa ja on laajuudeltaan 5 opintopistettä, joten sen [laskennallinen työmäärä on noin 135 tuntia](https://www.haaga-helia.fi/fi/ects-jarjestelma-ja-tutkintotodistuksen-liite-eli-diploma-supplement). Ttyömäärä vastaa laskennallisesti noin 17 tuntia viikossa, joten **varaa kurssin suorittamiseen runsaasti aikaa joka viikko**:

```java
int kestoViikkoina = 8;
int opintopisteita = 5;
int tyomaaraPerPiste = 27;

int kokonaistyomaara = opintopisteita * tyomaaraPerPiste;
System.out.println(kokonaistyomaara); // 135 tuntia

double tyomaaraPerViikko = 1.0 * kokonaistyomaara / kestoViikkoina;
System.out.println(tyomaaraPerViikko); // 16.875 tuntia per viikko
```


## [](#) 🔍 Tiedon etsiminen

Tämän kurssin materiaali perustuu suurelta osin valmiisiin netistä löytyviin dokumentaatioihin ja tutoriaaleihin. Eri aihealueiden yhteydessä tarjotaan linkkejä aihetta koskeviin materiaaleihin, mutta **joudut sen lisäksi merkittävissä määrin etsimään itse tietoa aiheista**.

Kurssin tehtävien ei ole tarkoitus mitata, oletteko sisäistäneet oppitunnilla tai oppimateriaalissa esitetyt asiat, vaan tehtävien ratkaiseminen edellyttää itsenäistä tiedonhakua. Itsenäisen työskentelyn ohessa suosittelemme kysymään ja keskustelemaan aiheista kurssin Teams-kanvalla.


## [](#) 📑 Lähteiden käyttäminen

Ohjelmointiongelmiin löytyy usein valmiita tai osittaisia ratkaisuja ympäri Internetiä niin keskustelupalstoilta kuin tutoriaaleista. Huonossa tapauksessa löydät toimivan ratkaisun ongelmaasi, mutta et osaa aivan tulkita mitä löytämäsi koodi tekee ja miksi se ratkaisee ongelmasi. Ammattimaisessa ohjelmistokehityksessä tästä seuraa mahdollisesti suuriakin vahinkoja.

Nettilähteiden hyödyntäminen ja niistä mallin ottaminen on sallittua ja kannustettavaa, mutta et saa vain kopioida ratkaisuja, vaan sinun tulee ymmärtää, miten koodisi toimii. Lisäksi, erityisesti koska kyseessä on korkeakoulun opintojakso, sinun tulee merkitä lähteet lainatessasi esimerkiksi StackOverflow:sta löytämääsi koodia. Lähdeviitteeksi riittää esimerkiksi verkkosivun osoite Java-kommenttina lainatun koodin yhteydessä, tai käyttämäsi lähteen käyttöehtojen mukainen muu lähdeviite.


## [](#) 🧠 Esitietovaatimukset

> *"Opiskelija on suorittanut opintojakson Ohjelmointi 1 (SOF005AS2A/SWD4TN032) tai hänellä on vastaavat tiedot ja taidot. Opiskelija suorittaa samanaikaisesti opintojakson Tietokannat ja tiedonhallinta (SOF001AS2A/ SWD1TN003) tai hänellä on vastaavat tiedot ja taidot."*
>
> [*opintojaksokuvaus*](https://opinto-opas.haaga-helia.fi/course_unit/SOF001AS3A)

Mikäli sinulla ei ole sujuvaa osaamista Ohjelmointi 1 -opintojaksolta, vaatii tämä kurssi erityisen paljon työtä ja omaa panostusta.

