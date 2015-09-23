# Vantaan sähköisten palveluiden toiminnalliset suunnitteluohjeet   
Verkkopalveluiden suunnittelijat pitävät yllä tätä dokumenttikokoelmaa johon kirjataan suunnittelu ja toteutusperiaatteita palveluiden suunnittelua varten.

Tämän oppaan ulkopuolelle on jätetty HTML/CSS koodin dokumentointi, sekä yksittäisten palveluiden suunnitteludokumentit.  

Tätä verkkosivua päivitetään koko ajan. 

## Sisältö

* Yleistä
	* Laite ja selainmääritykset
	* HTML, CSS ja Javascript/jQuery
	* Esteettömyys
	* Tulostusversio
	* Sivujen rakenne ja sisällön asemointi
	* Mobiilisuunnittelu
* Navigointi
	* Päänavigaatio
	* Alanavigaatio
	* Murupolku
	* Sivujen välillä liikkuminen 
* Tietojen näyttäminen
	* Tietojen näyttäminen
	* Teksti
	* Kuvat, ikonit ja videot 
	* Lomakkeet
		* Lomakekomponentit
	* Kieliversiot
	* Terminologia
	* Lyhenteet
	* Nimet
	* Numeerinen tieto
	* Yhteystiedot
	* Järjestys ja ryhmittely
	* Taulukot ja listat
	* Diagrammit ja kaaviot
	* Kartat
* Tietojen lisääminen, muokkaaminen ja poistaminen
	* Tietojen lisääminen
	* Tietojen muokkaaminen
	* Tietojen poistaminen
* Toiminnalliset komponentit
	* Linkit
	* Painikkeet
	* Välilehdet
	* Sivutus
	* Wizardi
	* Dialogit
	* Kalenteri
* Ilmoitukset
	* Neutraali
	* Positiivinen palaute
	* Virheilmoitus
	* Käynnissä oleva toiminto
	* Järjestelmän tilailmoitus

# Yleistä
## Laite ja selainmääritykset
## HTML, CSS ja Javascript/jQuery
## Esteettömyys
## Tulostusversio
## Sivujen rakenne ja sisällön asemointi
## Mobiilisuunnittelu
{Huom MK: tämä kappale vaatii editointia}

K: pyritäänkö suunnittelussa siihen, että samat näkymät toimivat sellaisenaan mobiilissa, vai tehdäänkö mobiiliin erillistä suunnittelua

V: Ensisijaisesti tehdään ratkaisuja, jotka toimivat kaikilla laitetyypeillä. Käytetään oletuksena Bootstrap 3:n elementtien käyttäytymismalleja. Mikäli tiettyä laitetyyppiä varten tarvitaan poikkeus ulkoasuun tai toiminnallisuuteen, lisätään päälle uusi taso, joka sisältää vain tarvittavan poikkeuksen.

K: mikäli tehdään erillistä suunnittelua, miten se priorisoidaan suhteessa muihin tehtäviin?

V: Suunnitellaan Mobile First, jolloin suurin osa asioista ratkeaa suoraan suunnitteluvaiheessa. Ei optimoida alussa liian pitkälle, vaan toteutetaan ensin ensimmäinen versio ja mikäli lisäoptimoinnin tarvetta esiintyy, niistä tehdään omat taskit backlogille.

K: minkä tyyppisiin asioihin suunnittelu kohdistuu? 

V: Suunnittelu kohdistuu tarpeen mukaan. Yleensä vaatimus tulee tilankäytön ja näytön pienuuden kautta. (Esim. pitkien listojen muuttaminen dropdowneiksi tms)

K: voidaanko esimerkiksi sisältöä karsia ja missä tapauksissa?

V: Sisältöä karsitaan vain äärimmäisessä poikkeustapauksessa ja nämä tapaukset käsitellään erikseen. Sisältöä voidaan kuitenkin esittää pienemmissä erissä käyttäjälle, ts. näytön tilan rajoissa. Tämän vuoksi sisällön priorisointi on tärkeää jo sisältöä suunniteltaessa.

