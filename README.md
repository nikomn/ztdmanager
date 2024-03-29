# ztdmanager
Aineopintojen harjoitustyö: Tietokantasovellus

Alustava kuvaus sovelluksen toiminnallisuudesta:

Tehtävänä on luoda tietokantasovellus, jonka avulla käyttäjä voi hallinnoida omaa tehtävälistaansa ZTD (Zen To Done) järjestelmän mukaisesti (ZTD on yksinkertaistettu muunnelma GTD:stä).

Sovelluksessa on kahdenlaisia käyttäjiä: admin-käyttäjät ja peruskäyttäjät.

Peruskäyttäjät voivat lisätä ja poistaa omia tehtäviä, kategorioita ja konteksteja. Tehtävään liittyy aina yksi tai useampi kategoria ja yksi tai useampi konteksti. Kategoria voi olla esim. 'opiskelu', 'kotityöt', 'ohjelmointiprojektit' tms. Kontekstit määrittävät, missä kontekstissa tehtävää on mahdollista tehdä, esim. työmatkalla käytössä olevat resurssit voivat rajoittaa sitä, mitä voi tehdä verrattuna siihen, kun on työpaikalla jne. Peruskäyttäjä voi myös poistaa oman käyttäjätilinsä.

Admin käyttäjillä on kaikki oikeudet, jotka peruskäyttäjälläkin, mutta he voivat myös poistaa kenen tahansa käyttäjän luomia tehtäviä, kategorioita ja konteksteja ja myös käyttäjätunnuksia.

Käyttäjätunnuksen poistaminen poistaa samalla kaikki käyttäjään liittyvät tehtävät, kategoriat ja kontekstit. Kategorian tai kontekstin poistaminen poistaa kategorian kaikista tehtävissä, missä niitä on käytetty.

Tietokannasta pitää olla mahdollista hakea erilaisia työlistoja erilaisilla kategoria, konteksti ja deadline rajauksilla yms.

<>

Selvitettäviä kysymyksiä jatkokehitystä ajatellen:
- Ovatko kategoriat ja kontekstit käyttäjäkohtaisia vai globaaleja vai tilanteesta riippuen?
- Jos kategoriat ovat käyttäjäkohtaisia, aiheuttaako tämä ongelman siinä, että kahdella käyttäjällä voi olla sama kategoria käytössään, ja tällöin siis tietokannassa on teknisesti sama kategoria kahdella id:llä?
- Jos kategoriat ovat globaaleja, aiheuttaako tämä ongelman siinä, että valittavana on miljoona erilaista kategoriaa, jotka eroavat toisistaan vain hieman esim. sanamuodon osalta?


