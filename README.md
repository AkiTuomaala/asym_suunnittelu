# ASYM Suunnittelu

ASYM suunnittelu pohjautuu avoimen lähdekoodin sovellusten hyödyntämiseen kaupunkiympäristön suunnittelussa.

  - Ylläpidetyn tiedon tallentaminen yhteen paikkaan
  - Tallennetun tiedon ristiin hyödyntäminen
  - Räätälöityvyys omien tarpeiden mukaan
  - Yksinkertainen selainkäyttöliittymä esittämään ylläpidettyä tietoa tai lisäämään kohteita Postgres kantaan
 
## Sisältö
- Asennus .bat / .sh
    - Postgres kanta, lisäosat, taulut, näkymät, funktiot...
- REACT pohjainen selainkarttakäyttöliittymän repo
    - Tarvittavat kirjastot ja scriptit
- Geoserver
    - Ohjeistus asennukseen tai mahdollinen valmis paketti asentamista varten

### TODO -lista

    [] Asennustiedosto .bat
        [] SQL pohjan asennusta varten
            [] Lisäosat (mm. postgis)
            [] Omat funktiot
            [] Kunnallistekniikan taulut
                [] Kohteet
                    [] Ominaisuudet
                        [] Geometria
                [] Vaiheet
                    [] Aloitusvaihe
                    [] Luonnosvaihe
                    [] Hallinnollinen vaihe
                    [] Toteutus vaihe
                    [] Luovutusvaihe
                [] Eri työvaiheiden budjetointi
                    [] Kaivuu
                    [] Ennallistaminen
                    [] Valaistus
                [] Hankkeen sisältö
                [] Kunnossapito
            [] Kaavoituksen taulut (Gispo OY:n Qaavan tietomallin hyödyntäminen?)
                [] Vaiheet
                [] Budjetti
                [] Aikataulu
            [] "Ohjelmat" (ex. Maantoteuttamissuunnitelma)
            [] Näkymät
    [] Käyttöliittymän asennus
        [] Node asennus
        [] React-app
            [] Kirjastot (mm. Leaflet)
            [] Scriptit
                [] CSS
                [] JSX
        [] Express
 
##### Yhteistyössä
- [Kouvolan kaupunki](https://www.kouvola.fi/)
- [GeoIDT](http://geoidt.com/)

Lisenssi
----

CC
