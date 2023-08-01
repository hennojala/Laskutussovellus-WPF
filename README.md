# Laskutussovevellus työpöytäversio
WPF (XAML, C#), tietokantana MariaDB, HeidiSQL

Käyttöliittymäohjelmoinnin harjoitustyö 5op kevät 2023

Tehtävänä oli luoda laskutussovellus, jossa on graafinen käyttöliittymä yritykselle, jotta se voi laskuttaa asiakkaitaan. Sovelluksen avulla käyttäjän piti pystyä syöttämään laskurivejä, joilla voidaan määrittää työhön käytetyt tuotteet, niiden määrät ja hinnat. Lisäksi laskulle tuli voida syöttää työhön kulutettu aika ja työn hinta. Näiden tietojen perusteella laskulle muodostuisi kokonaishinta. Jokaisella laskulla tulisi olla yksilöivä numero sekä laskutettavan että laskuttajan osoitetiedot, päiväys, eräpäivä ja mahdollisuus antaa laskulle lisätietoja. Tämän lisäksi kaikki laskutietojen tuli olla tallennettuna tietokantaan tai tiedostoihin, jotta niitä voitaisiin myöhemmin hakea ja muokata tarvittaessa.

Sovelluksen oli tarkoitus tarjota seuraavat toiminnot:

    -Kaikkien laskutietojen hakeminen ja listaus testisovelluksessa.
    -Yksittäisen laskun tietojen ylläpito (lisäys, muutos, poisto) testisovelluksessa.
    -Kaikkien tuotetietojen hakeminen ja listaus testisovelluksessa.
    -Yksittäisen tuotteen tietojen ylläpito (lisäys, muutos, poisto) testisovelluksessa.
    -Laskuttajana voi olla ainoastaan yksi yritys, joten laskuttajan tiedot voitaisiin tulostaa laskulle vakioarvoina.

Sovelluksen oli tarkoitus toteuttaa olio-ohjelmoinnin periaatteita noudattaen. Lisäksi sovelluksen käynnistyessä sen tuli luoda paikalliseen MariaDB-palveluun uusi tietokanta, tarvittavat taulut ja testidataa sovelluksen testaamista varten. Jos tietokanta oli jo olemassa, sovelluksen tuli poistaa ensin vanha tietokanta. Yhteyden määrittämiseksi tietokantaan sovelluksen tuli käyttää ConnectionString-asetuksia muuttujissa ja hyödyntää valmiiksi annettuja tietoja, kuten palvelimen osoitetta, käyttäjätunnusta ja salasanaa. Nämä on turvallisuussyistä poistettu tänne laitetusta koodista, joten ohjelman toiminta vaatii että ne lisätään koodiin ennen sen ajamista. Sain tästä harjoitustyöstä ja kurssista arvioinniksi 5 (asteikko 1-5).
