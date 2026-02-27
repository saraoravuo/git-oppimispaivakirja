# Oppimispäiväkirja: Git projektissa

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

Yksin kehitetyssä projektissa versionhallintaa voisi hyödyntää esimerkiksi sen historian ja palautusten kautta. Jos tekee virheen, voi palata aiempaan versioon. Talletuskommenttien avulla pystyy seuraamaan mitä muutoksia on missäkin vaiheessa tehty ja miksi.

Lisäksi hyötynä on koodin varmuuskopionti. Koodi pysyy etärepositoriossa, esim. GitHubissa, joten koodi ei katoa, vaikka kone rikkoutuisi.

__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

Versionhallinnassa on paljon hyötyjä kun projektissa on useampia kehittäjiä. Jokainen voi työskennellä samaan aikaan omassa haarassaan ilman, että työt sotkeutuvat toisiinsa. Lisäksi voidaan päättää milloin kukin työ yhdistetään toisiinsa. Yhdistämispyynnöt mahdollistavat koodin tarkastuksen ennen kuin muutokset viedään päähaaraan. Kun yhdistys tehdään, ilmoittaa Git mahdollisista konflikteista.

Myös usean kehittäjän projekteissa historiatiedot ovat hyödyksi. Sieltä näkee selkeäsi kuka on tehnyt ja mitä.

__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

Projektissa on seuraavat haarat:
- testaus-haarat, jotka on jokaisella kehittäjällä. Siellä kukin kehittää ja tekee omia muutoksiaan omaan projektin osioon.
- develop-kehityshaara, johon kukin voi viedä omat muutoksensa
- main-haara, joka sisältää vain testatun ja toimivan version

Commit-viestit ovat tärkeitä, niitä käytetään selkeästi kaikkien muutosten yhteydessä.

Koodia testataan ja varmistetaan paikallisesti. Etärepositoriota käytetään varmuuskopiona ja yhteistyön välineenä. Kehityshaaraa päivitetään säännöllisesti ennen uusien tehtävien aloittamista.

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Mielestäni opintojakson rakenne oli suunniteltu selkeäksi, ja annetut materiaalit tukivat kunkin osion tehtäviä. Työmäärää oli jonkin verran tällaiselle alottelijalle, mutta ei kuitenkaan ylitsepääsemätön määrä. Tehtävät olivat loppujen lopuksi nopeita, kunhan oli ensin perehtynyt aiheeseen.

Olisin enemmän toivonut ohjetta siihen, missä kohtaa kukin komento annetaan. Välillä tuli ongelmia sen kanssa, että olin antanut kerrotun komennon väärässä kohdassa.

Koska kurssi on vain 2op, ei aiheeseen päästä kovin syvällisesti. Mielestäni kokonaisuuten tämä oli hyvä ensikatsaus Git-versionhallintaan.