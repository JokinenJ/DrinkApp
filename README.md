# DrinkApp

Käyttöliittymän suunnitteluun ja toteuttamiseen tarkoitettu opiskeluprojekti. Tavoitteena on kehittää helppokäyttöinen
ja visuaalisesti miellyttävä mobiilisovellus drinkkireseptien hakemiseen TheCocktailDB:n API-rajapinnasta.

## Käyttöliittymä

Sovellus suunnitellaan mobiilikäyttöön Android-puhelimen näkymää mukaillen, mallikoko on 360 × 800 pikseliä.
Käyttöliittymän kielenä toimii englanti, sillä se varmistaa sovelluksen yhtenäisyyden API-rajapinnasta
tulevien englanninkielisten drinkkitietojen kanssa.

## Sovelluksen ominaisuudet

- **Search:** Drinkkien etsiminen nimellä tai ainesosalla.
- **Surprise Me:** Satunnaisen drinkin arvonta.
- **Details:** Drinkkien kuvien, ainesosien ja valmistusohjeiden näyttäminen.
- **Favorites:** Drinkkien lisääminen ja poistaminen suosikkilistalta.
- **Alcohol/Non-Alcohol Filter:** Drinkkien suodattaminen alkoholillisiin ja alkoholittomiin vaihtoehtoihin.

## Teknologiat

- **Python** – Pääohjelmointikieli
- **Flet** – Käyttöliittymän toteutus
- **HTTPX** – API-kutsut
- **TheCocktailDB API** – Drinkkitietojen lähde
- **JSON ja Pathlib** – Paikallinen suosikkien tallennus ja tiedostonkäsittely
