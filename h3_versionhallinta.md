# Palvelinten hallinta - viikon 3 kotitehtävät

Tein tehtävät omalla ASUSin pöytätietokoneellani.   
Minulla oli käytössä VirtualBoxille asennettu Xubuntu 18.04.5 LTS Käyttöjärjestelmä.   
Tehtävien ratkaisemisen pohjana oli Tero Karvisen Palvelinten hallinta -kurssin toinen opetuskerta 15.4.2021

## d) Näytä omalla git-varastollasi esimerkit komennoista ‘git log’, ‘git diff’ ja ‘git blame’. Selitä tulokset.

![](ph3.1.png)

Git log komennolla saadaan esiin loki, jossa nähdään tehdyt muutokset ja kuka ne on tehnyt ja milloin.

![](ph3.2.png)

Git diff komennolla voidaan verrata kahta eri versiota samasta tiedostosta. Esimerkistä näkee, että tiedoston nimeä on muutettu. Miinus merkit kuvaavat poistoa ja plus merkit lisäystä. Punaisella ja vihreällä värillä näytetään eroavaisuuksia. Vihreä väri kuvaa nykyistä versiota.

![](ph3.3.png)

Git blame komennolla nähdään tiedoston jokainen rivi, rivin sisältö ja rivin tekijä ja aika, jolloin se on tehty.

Tehtävän kesto: 30min

## e) Tee tyhmä muutos gittiin, älä tee commit:tia. Tuhoa huonot muutokset ‘git reset –hard’. Huomaa, että tässä toiminnossa ei ole peruutusnappia.

Tein tyhmän muutoksen aikaisemmin tekemääni markdown harjoittelu tiedostoon. Tämän jälkeen tein git add . komennon ja sen jälkeen git reset --hard komennon. Tämä poisti tekemäni muutoksen md tiedostoon ja myös ottamani kuvakaappauksen.

Tehtävän kesto: 15min

## f) Tee uusi salt-moduli. Voit asentaa ja konfiguroida minkä vain uuden ohjelman: demonin, työpöytäohjelman tai komentokehotteesta toimivan ohjelman. Käytä tarvittaessa ‘find -printf “%T+ %p\n”|sort’ löytääksesi uudet asetustiedostot. (Tietysti eri ohjelma kuin aiemmissa tehtävissä, tarkoitushan on harjoitella Salttia)

