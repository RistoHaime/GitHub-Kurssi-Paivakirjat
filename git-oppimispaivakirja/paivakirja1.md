# git-oppimispaivakirja: Paikallinen Git

Tämä on kurssin oppimispäiväkirja.

### Harjoitus 2
Harjoituksessa ei varsinaisesti vaikeata ollut, kaikki tiedot mitä tarvitsi tehtävien tekemiseen löytyi nopeasti ohjeista. 

Esimerkiksi tiedostojen uudelleen nimeäminen, niiden luonti ja postaminen yleisesti olen tehnyt koodieditorissa enkä varsinaisesti komennoilla. 
### Harjoitus 3

Harjoitus vaikutti menevän kaiken kaikkiaan hyvin. Kuitenkin välillä terminologia menee hieman sekaisin, joten muutamaan kertaan joutui lukemaan.

Vaikeinta tehtävässä oli revert komento. Hieman kesti ymmärtää mitä kyseinen komento teki ja miten sitä käytetään. OverStackFlow:ssa oli erittäin hyvin ja yksinkertaisesti selitettynä tämä. Myös oppimista helpotti kun käytti VS-coden source controlleria katsomaan miten commitit ovat menneet.

### Harjoitus 4

Tehtävät olivat vielä helpon puoleisia, ei tarvinnut esimerkiksi lukea toisen tekemää koodia ja päättää kumpi on "oikea". Myös hieman olen joutunut aikaisemmalla kurssilla kastamaan varvasta usean branchin tekemiseen, joten tämä tuntui ihan kotoisalta.

Koen että omassa haarassa kehittäminen on tärkeä taito oppia ja tehdä siitä tapa. Toistaiseksi se on ollut vaikeaa aina muistaa, sekä joskus on tullut talletettua haaraan vahingossa, mikä olisi pitänyt mennä eri haaraan. Joten "git status" komentoa tulisi käyttää useammin.  

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git add | komennolla listään tallennettavat tiedostot, mutta ei vielä tallenneta. "git add ." lisää kaikki muutetut ja "git add myFile.txt" lisäisi vain myFile.txt:n. |
|  git commit  | Tallennetaan git add:n kautta lisätyt ja muutetut tiedostot. git commit perään voidaan laittaa -m, jonka jälkeen voidaan kirjoittaa kommentti tallennetuista muutoksista esim: git commit -m "viesti". |
| git status | Tarkastetaan mitä muutoksia ja eroavaisuuksia on tehty verrattuna tallennettuihin tiedostoihin.|
| git log | näytää commit login, eli historian. |
| git rm | poistaa tiedoston esim: "git rm myFile.txt". |
| git mv | Muuttaa tiedostoa, esimerkiksi nimen vaihtaminen.Esim: "git mv foo.txt bar.txt" vaihtaa foo tiedoston nimen bar.|
| git clone | repositorion kopioiminen omalle koneelle. esim git clone https://github.com/mruonavaara/git-oppimispaivakirja. |
|git reset| Komennolla poistetaan git add. Mikäli git reset perään ei anneta tiedostoa, resetoidaan koko git add.|
| git  restore | Palautetaan versiohallinnassa oleva tiedosto, esimerkiksi git restore index.html palauttaa versiohallinnassa olevan ja poistaa tallentamattomat muutokset. |
| git restore --hard| palauttaa kokonaan versiohallinnassa olevaan versioon. |
| git revert | Peruuttaa kokonaisen commitoinnin, HEAD poistaa menee aikaisimmasta taakseppäin ja git revert "commitID" menee kyseiseen kommittiin asti.|
| git branch | näyttää olemassa olevat haarat, mikäli perään kirjoitetaan esim: testi, git luo uuden haaran nimeltä testi, mikäli tämä ei jo käytössä. |
| git switch | Komennolla vaihdetaan eri haaraan, esimerkiksi "git switch testi", siirtää testi haaraan. |
| git merge | Yhdistää halutun haaran. Mikäli tällä hetkellä master haarassa ja halutaan yhdistää foo siihen, kirjoitetaan git merge foo. |