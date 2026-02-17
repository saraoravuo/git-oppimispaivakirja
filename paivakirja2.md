# Oppimispäiväkirja: Hajautettu git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet, jotka vaikuttivat tehtävän suorittamiseen?__

Tässä osiossa haastavinta oli ymmärtää haarojen ja etärepositorioiden logiikka. Myös tässä osiossa erilaiset käsitteet tuottivat aluksi hankaluuksia. Milloin haarat ovat paikallisia, milloin käytössä on epärepositorio jne.

Harjoitus 5 tehtävässä projekti tuli viedä GitHubiin. Tätä tehtävää tehdessä oivalsin miltä mitkäkin komennot "näyttävät" visuaalisesti GitHubissa ja miten ne konreettisesti muokkaavat tiedostoja, haaroja tai repoja. Tämä tehtävä auttoi havainnollistamaan ja ymmärtämään logiikkaa paremmin. 

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git clone | tekee valmiin paikallisen repositorion |
| git remote add | Etärepositoriosuhteen määritys ilman kloonausta |
| git remote | listaa epärepositoriot |
| git remote -v | listaa epärepositoriot ja niistä enemmän tietoa |
| git remote rename | epärepositorion uudelleennimeäminen |
| git remote rm  | epärepositorion poistaminen |
| git remote show | Yksittäisen etärepositorion tietojen tarkastelu |
| git fetch | lataa etärepositorion tiedot paikalliseen repositorioon |
| git branch -r | etärepositorion haarojen listaus |
| git checkout | voi tutkia etärepositoriosta ladattua sisältöä |
| git merge | yhdistää etärepo paikalliseen sisältöön |
| git pull | yhdistää fetch ja merge komenno, eli hakee nykyisen haaran uudet tiedot etärepositoriosta ja yhdistää ne nykyiseen haaraasi automaattisesti |
| git push | synkronoi paikallisen repositorion tietoja etärepositorioon |
| git branch --delete <haara> | poistaa haara paikallisesti reposta |
| push --delete <etärepositorio> <haara> | poistaa haara etäreposta |