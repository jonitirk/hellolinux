# h2 - komentaja Pingviini
Klo 13.15:
- Tutustuin Linuxin tärkeimpiin komentoihin, johon kuuluu mm. seuraavat
  - pwd = näyttää nykyisen työhakemiston
  - ls = listaa hakemistossa olevat tiedostot
  - cd = liiku hakemistoissa
  - less = näytä tekstitiedostot sivuittain
  - mkdir = luo hakemisto
  - mv = nimeä uudelleen tai siirrä hakemisto toiseen paikkaan
  - man = avaa manuaali, jostain komennosta
  - rm = poista tiedosto/hakemisto
  - cp = kopioi tiedosto / hakemisto
  - sudo apt-get update = päivitä järjestelmänvalvojan oikeuksin saatavilla olevat paketit
  - sudo apt-get install = asenna järjestelmänvalvojan oikeuksin haluttu paketti
- Lisäksi tutustuin tärkeimpiin hakemistoihin (home, home/user, /etc, /media, /var/log)
Lähde: https://terokarvinen.com/2020/command-line-basics-revisited/?fromSearch=command%20line%20basics%20revisited

Klo 13.26:
- Asensin micro-editorin
<img width="407" alt="image" src="https://user-images.githubusercontent.com/89454122/214028568-7e6fec57-6492-4e41-b431-e94e3d80c3cc.png">

Klo 13.29:
- Asensin lshw:n (komento, joka näyttää raudan konfiguraation) ja listasin testaamani raudan
<img width="410" alt="image" src="https://user-images.githubusercontent.com/89454122/214029014-86e5e328-18f8-455e-8a26-b0381f4979e8.png">

<img width="410" alt="image" src="https://user-images.githubusercontent.com/89454122/214029560-301692aa-c666-44d1-8b16-528f7530fb60.png">

-Järjestelmän nimi: VirtualBox, joka käyttää intelin 5:n generaation prosessoria. Muistia 3 gigaa.

Klo 13.38:
-Asensin kolme uutta komentoriviohjelmaa (Cmatrix, cowsay, sl)

<img width="393" alt="image" src="https://user-images.githubusercontent.com/89454122/214030802-2c3fb95b-017d-46d1-ac4c-2514c8997623.png">

Lähde: https://www.makeuseof.com/fun-linux-command-line-programs/

Klo 13.43:
- Tutkin tärkeimpiä kansioitani käyttäen ls-komentoa
<img width="392" alt="image" src="https://user-images.githubusercontent.com/89454122/214031496-45efe5bc-961e-4dbc-aed2-eff000707694.png">
<img width="404" alt="image" src="https://user-images.githubusercontent.com/89454122/214031586-b9a2cecf-0b7e-4b54-8cb3-d7f38637de9c.png">

- FHS = File system hierarchy standard
- lähde: https://en.wikipedia.org/wiki/Filesystem_Hierarchy_Standard

Klo 13.47:
- Tutustuin grep-komentoon käyttämällä komentoa "man grep"
<img width="449" alt="image" src="https://user-images.githubusercontent.com/89454122/214032381-c92433a0-b3db-4e27-9162-84aeeac7ca42.png">

Grep-komento etsii haluttuja malleja tiedostoista, jolloin tiedon hakua pystyy rajaamaan niin, että ei tarvitse näyttää kaikkia tiedostoja/tiedostossa olevia rivejä.
Esimerkiksi: etsi tiettyä tiettyä tekstinpätkää

    $ grep "this" demo_file
    this line is the 1st lower case line in this file.
    Two lines above this line is empty.
    And this is the last line.

Lähde: https://www.thegeekstuff.com/2009/03/15-practical-unix-grep-command-examples/

## Summaus
Ajan käyttö: klo 13.15 - 13.55
Opittu käyttämään Linuxin peruskomentoja.

Nimi: Joni Tirkkonen
