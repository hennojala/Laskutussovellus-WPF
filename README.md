# Laskutussovellus työpöytäversio

Käyttöliittymäohjelmoinnin harjoitustyö, 2023.

Käytetyt tekniikat: Visual Studio, WPF (XAML, C#), tietokantana MariaDB, HeidiSQL.

---
### Harjoitustyön idea:


Laskutussovellus, jossa on graafinen käyttöliittymä.

---

### Sovelluksen toiminta

- Sovellus toteuttaa olio-ohjelmoinnin periaatteita.
- Sovelluksen käynnistyessä se luo paikalliseen MariaDB-palveluun uuden tietokannan, tarvittavat taulut ja testidataa sovelluksen testaamista varten.
- Jos tietokanta on jo olemassa, sovellus poistaa ensin vanhan tietokannan. 
- Sovelluksen avulla käyttäjä pystyy syöttämään laskurivejä, joilla määritetään työhön käytetyt tuotteet, työaika, sekä niiden määrät ja hinnat.
- Rivien perusteella laskulle muodostuu kokonaishinta.
- Jokaisella laskulla on yksilöivä numero sekä laskutettavan että laskuttajan osoitetiedot, päiväys, eräpäivä ja mahdollisuus antaa laskulle lisätietoja
- Kaikki laskutiedot tallennetaan tietokantaan, jotta niitä voi hakea ja muokata.
---
### Huomioita
Yhteyden määrittämiseksi tietokantaan sovellus käyttää ConnectionString-asetuksia muuttujissa ja hyödyntää valmiiksi annettuja tietoja, kuten palvelimen osoitetta, käyttäjätunnusta ja salasanaa.
Ohjelman toiminta vaatii että ne lisätään koodiin ennen sen ajamista.

> ~~ **Lisää koodiin sivulla "Hallinnointityökalut" tietokantayhteystiedot.** ~~ 

Tästä harjoitustyöstä ja kurssista saatu arvioinniksi 5 (asteikko 1-5), vaikka parannuskohteita löytyy.
