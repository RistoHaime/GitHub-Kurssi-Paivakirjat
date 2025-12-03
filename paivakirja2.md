# git-oppimispaivakirja: Hajautettu Git

Tämä on kurssin oppimispäiväkirja.

### Harjoitus 5

Vaikka GitHub on ennestään tuttu ja komentoja olen tehnyt aikaisemminkin, opin tehtävistä paljon. Antoi ymmärtää, mitä esimerkiksi on fetch ja pull. Miten nämä eroavat. Myös GitHubin sisällä GLU:ta käyttämällä on ihan hyvä tehdä muutoksia.

| Komento | Kuvaus |
| --------| ------ |
| git romote add | lisätään paikallinen repositorio valmiina olevaan etärepositorioon. Esimerkiksi git remote add origin https://github.com/RistoHaime/GitHub-Kurssi.|
| git remote -v | antaa tieotja etärepositoriosta |
| git fetch | hakee repositorion, mutta ei tallenna sitä paikallisen päälle. |
|  git push -u origin master | Tallennetaan paikallinen origin tallennus git repositorioon master haaraan. -u tekee master haarasta paikan, josta komennolla git pull hakee ja jatkossa git push ei tarvitse määritellä mihin haaraan syötetään origin.|