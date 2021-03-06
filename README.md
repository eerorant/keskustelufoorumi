# Keskustelufoorumi

## Heroku

[Heroku](https://tsoha-tyoni.herokuapp.com/)

### Testitunnukset

Mikäli ei halua tehdä itse sovellukseen omia tunnuksia, voit käyttää seuraavia testitunnuksia:

Username: user  
Password: user

## Dokumentaatio

[Käyttäjätarinat](https://github.com/lehtoneo/keskustelufoorumi/blob/master/documentation/kayttajatarinat.md)

[Yhteenvetokyselyitä](https://github.com/lehtoneo/keskustelufoorumi/blob/master/documentation/yhteenvetokyselyt.md)

## Kuvaus

Sovellus on keskustelufoorumi, johon tulee kirjautua nähdäkseen keskustelut. Käyttäjä voi aloittaa keskustelun, poistaa aloittamansa keskutelun ja vastata omiin tai muiden aloittamiin keskusteluihin. Kirjoituksia voi etsiä erilaisin kriteerein, kuten kategorioittain tai aloitusajan perusteella. Sovellus pitää myös tietoa siitä, ketkä käyttäjistä ovat lukeneet keskustelun. Jos keskusteluun tulee uusi viesti, keskustelu näkyy käyttäjillä lukemattomana. Sovelluksessa on kaksi eri roolia: "user" ja "admin", joilla on hieman erilaiset toiminnot.

### Toteutetut toiminnallisuudet

- Kirjautuminen
- Käyttäjän luominen
- Keskustelun aloittaminen
- Keskusteluun vastaaminen
- Keskusteluiden listaaminen
- Kommenttien katselu
- Oman vastauksen ja keskustelun aloituksen poistaminen
- Oman keskustelun aiheen muokkaaminen
- Omien keskustelun aloituksien näyttäminen omalla sivulla
- Aktiivisimpien keskustelijoiden listaus



## Tietokantakaavio


<img src="https://github.com/lehtoneo/keskustelufoorumi/blob/master/documentation/pics/databasePicture.png">
