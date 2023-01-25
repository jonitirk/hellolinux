
# h3 Vapaus!

## Laitteisto/ympäristö

### Host:
  - Verkko: Kotiverkko, Elisa 5G 100M WLAN
  - Tietokone: HP Pavillion -läppäri
  - Suoritin: Intel(R) Core(TM) i5-8265U CPU @ 1.60GHz   1.80 GHz
  - Asennettu RAM: 8,00 Gt (7,88 Gt käytettävissä)

### Virtual Machine:
  - Oracle VM Virtual Box v7.0.4
  - System Memory 3GiB


## Lue ja tiivistä
  - FSF: Free Software Definition (n. 15min)
    - Vapaan ohjelmiston neljä määritelmää: vapaus suorittaa, vapaus opiskella, vapaus jakaa ja vapaus muokata.
    - Täytyy olla pääsy lähdekoodiin.
    - Kaikki neljä määritelmää tulee täyttyä, jotta ohjelmisto voisi olla vapaa.
    - Vapaata ohjelmistoa voi käyttää kaupalliseen tarkoitukseen.
    - Ohjelmiston jälleenjakelussa, sekä sellaisenaan, että muokattuna voi olla joitain sääntöjä, kunhan ne eivät oleellisesti vaikeuta jakelua. Et voi esimerkiksi jakaa muokattua versiota kenenkään toisen nimissä. Toisin sanoen on käytävä ilmi, että muokattu ohjelmisto on sinun versiosi.
    
    Lähde: https://www.gnu.org/philosophy/free-sw.html
   
  - Rise of Open Source (n. 20min)
    - Open Source Initiative hyväksyy avoimen lähdekoodin lisensseiksi sellaiset, jotka täyttävät yllä mainitut vapaan ohjelmiston määritelmät (FSF).
    - Vaikka jokin ohjelmisto olisikin vapaa ja omaisi avoimen lähdekoodin lisenssin, ohjelmiston alkuperäisellä tekijällä on kuitenkin ohjelmistosta tekijänoikeudet. Lisenssissä kerrottuja ehtoja noudatamalla, pidät huolen siitä, ettet riko tekijänoikeuksia, kun käytät, jaat eteenpäin, tai muokkaat ohjelmiston lähdekoodia.

    Lähde: Välimäki 2005: Rise of Open Source: 5 Open Source Licenses as Alternative Governance Mechanisms: 5.1.1 - 5.1.4 (sivu 113 - 121)

## a) Kolmen ohjelman lisenssit. (ke 25.1 klo 22.40 - 23.07)
  - Cmatrix
    - Käyttää lisenssiä: GNU GPL v3.
    - Lähde: https://github.com/abishekvashok/cmatrix#license
    - Tärkeimmät oikeusvaikutukset: vapaa lisenssi, jossa copyleft (edellyttää, että myös uudelleen jakelussa vapaus otettava huomioon).
  - cowsay
    - Käyttää lisenssiä: GNU GPL
    - Lähde: https://github.com/avdi/cow/blob/master/public/cowsay-license.txt
  - Inkscape
    - Käyttää lisenssiä: GNU GPL v2.
    - Lähde: https://inkscape.org/about/license/

## b) Säännöllistä. Poimi tekstitiedostosta tietoa grep-komennolla käyttäen säännöllisiä lausekkeita (ke 25.1 klo 23.37 - 23.45)

  Etsin kaikki nykyisen hakemiston ja sen alihakemistojen (valitsin -R) tiedostojen rivit, jotka alkavat merkkijonolla "foo"

    $ grep "^foo" * -R     
    

<img width="250" alt="image" src="https://user-images.githubusercontent.com/89454122/214699456-d8d4fdf1-44b7-47dd-acd3-3bc128b3762e.png">

Lähde: https://www.linux.fi/wiki/Grep

## c) Pipe. Näytä esimerkki putkista (pipes). (ke 25.1 klo 23.55 - 00.04)

  Listasin /etc kansiosta kaikki kansiot, jotka alkaa merkkijonolla "lib"
  
    $ ls | grep "lib"
    
 
 <img width="240" alt="image" src="https://user-images.githubusercontent.com/89454122/214702500-8400556c-8ba9-43cb-b6bd-15fe27d23cfd.png">

Lähde: https://www.howtogeek.com/438882/how-to-use-pipes-on-linux/

## Summaus

Tutustuin tässä tehtävässä erilaisiin lakiteksteihin ja määritelmiin lisensseistä, sekä vapaiden ohjelmien määritelmiin. Otin selvää, mistä lisenssit löytyvät ja mitä lisenssitekstit tarkoittavat. Opettelin myös käyttämään grep-komentoa, sekä putkia Debianin terminaalissa. Itse tehtävien tekemiseen aikaa meni n. 1h 15min



Raportin laatija: Joni Tirkkonen
