Journal.fi:n käyttämä [Open Journal Systems](https://pkp.sfu.ca/ojs/) mahdollistaa HTML-muotoisten julkaisujen lisäämisen julkaisujen sivustoille. Käytännössä harva julkaisu kuitenkaan hyödyntää tätä mahdollisuutta. Sitä ei myöskään ole dokumentoitu kovin hyvin, joten sen käyttöönotto vaati jonkin verran kokeilua ja keskustelua ylläpidon kanssa. Käytännössä HTML-julkaisujen tukeminen vaati kolme asiaa: oikean lisäosan käyttämisen, CSS-tyylitiedoston kirjoittamisen ja julkaisujen oikean muotoilun.

# 1. Oikea lisäosa

Journal.fissä on asennettuna kaksi eri HTML-lisäosaa. Toinen on Journal.fi-ylläpitämä ja toimii paremmin useimmissa tapauksissa. Molemmat löytyvät oman julkaisun ylläpitosivulta seuraavasta polusta:

> Asetukset -- Verkkosivuston asetukset -- Lisäosat

Journal.fin ylläpitämä lisäosa on nimeltään

> Vaihtoehtoinen HTML-artikkelin lisäosa

Sen pitäisi toimia ongelmitta laittamalla rasti ruutuun.

# 2. CSS-tyylitiedosto

HTML-lisäosa ottaa valmiin julkaisun tiedoston ja lataa sen verkkoselaimessa. Valitettavasti oletuksena siihen ei sisälly muotoiluja, joten lopputulos on yksi iso pötkö tekstiä. Jotta lopputulos on hieman luettavampi, järjestelmään täytyy ladata oma tyylitiedosto. Se onnistuu polusta:

> Asetukset -- Verkkosivuston asetukset -- Lisäasetukset -- Julkaisun tyylitiedosto

Tyylitiedosto täytyy olla valmiiksi kirjoitettu omaan CSS-tiedostoonsa ja se ladataan järjestelmään sellaisenaan. Katso *Pelitutkimuksen vuosikirjan* käyttämästä esimerkistä mallia tai lataa se sellaisenaan omaan julkaisuusi.

# 3. Julkaisujen oikea muotoilu

Lisäosan ja tyylitiedoston lisäksi tarvitaan vielä julkaistavat tekstit oikeassa muodossa. *Pelitutkimuksen vuosikirjaan* ne tuotetaan kääntämällä lähetetyt tekstit ensin yksinkertaiselle merkintäkielelle ja muuntamalla ne siitä mm. HTML-muotoon ([kuvaus prosessista englanniksi](https://jonne.arjoranta.fi/2017/building-yearbook/)).

Käytännössä kyseessä on hyvin yksinkertainen HTML-tiedosto, joka ladataan sellaisenaan Journal.fi-järjestelmään. Järjestelmä tekee siihen jotain muutoksia, kun se ladataan, joten lopputulos ei ihan vastaa alkuperäistä tiedostoa. Voit katsoa esimerkkiä *Pelitutkimuksen vuosikirjan* artikkelista muokatusta mallista.
