# Debian ja Oracle Virtual Box lataaminen
 
Ennen kuin aloitin virtuaalikoneen asentamisessa, latasin ensiksi itse Debian tiedostoon, jouduin silmäilemään hetkeksi että olen lataamassa oikea version eikä väärän tai vanhentunutta versiota. Lataamisessa kesti hieman, koska kyseinen tiedosto oli tasan kolme gigatavua. Jonka jälkeen siirsin sen omalle levylle, missä oli edelleen noin 600 vapaata gigatavua ja pistin sen minun tekemä tiedostoon.

Latasin Virtual Box:n kurssin sivustolta, ja siirsin sen tiedoston omalle kansiolle, missä kaikki tähän kurssin liityvät materiaalit ja ohjelmat tulee sijaitsemaan. Käynistin Virtual Box:n EXE-tiedoston eli klikkasin Virtual Box: tiedoston jotta siirsin aikaisemmin omalle paikalle, ja eteni sen ohjeiden mukaisesti. Määrittelin uudelleen Virtual Box:n sijainti, siihen paikkaan mitä aikaisemmin suunnittelin, koska silleen oli automaattisesti määritelty oma lataussijainti, jonka jouduin päivittämään ettei menisi väärälle kansiolle ja levylle.

Annoin se lataa rauhallisesti ja palattua takaisin tietokoneen äärelle, tietokoneen näytöllä näkyi Virtual Box:n käyttöliittymän. Se näytti hieman erilaiselta kuin mitä ohjeistuksessa näkyi. Sen taustaväri oli valkoisen sijasta mustavärinen, sekä muutamat sanat olivat vaihdettu jollakin toisella sanalla joka oli tavallaan synonyyminen sen alkuperäisen kanssa. Jouduin hieman miettiä ja etsiä lisää tietoa Virtuaali Boxsista eli Oraclesta, sillä ohjeistuksen käyttöliittymä oli erilainen minun käytössä oleva käyttöliittymä kanssa, joten jouduin tässä tapauksessa etsiä netistä hieman lisää tietoa.

Monet asiat jotta piti suorittaa olivat automaattisesti tehty jo, eikä tarvinnut manuaalisesti tehdä sen. Esimerkiksi en tarvinnut lähteä tekemään "Insert Debian ISO Image as a Virtual CDROM" osiota, koska ohjelma teki se minun puolestani. Heti sen jälkeen kuin loin virtuaalikoneen ja käynnistin sen saman tien. Odotin muutaman sekuntia ja oman tietokoneen näytölle tuli virtuaalikoneen käyttöliittymän, valitsin näppäimistöllä "Live" vaihtoehdon.

## Debian "asentaminen"

Kone avautui, ja se näky oli tismalleen samanlainen kuin mitä ohjeistuksessa kuvattiin. Testasin, että toimiiko se virtuaalikoneen menemällä sen kautta Internetti ja sieltä Tero Karvisen sivuston. Testaus meni ongelmitta ja onnistui pääsemään Karvisen sivustoon. Aloitin viimeisen vaiheen, ja se oli käynnistää Debian asentaa virtuaalisessa ympäristössä. Seurasin ohjeistuksen mukaan, jätin kielivaihtoehdona oletuksena eli “American England”, seuraavaksi valitsin aikavyöhykettä. 

Alussa kirjoitin “Helsinki” tekstikenttään, mutta sitten kokeili valita suoraan kartalta sen, molemmat menetelmät toimivat. Seuraavassa vaiheessa eli “Partitions” vaiheessa valitsin “Erase disk” vaihtoehdon, mitään erityistä siinä aikana ei tapahtunut. Melkein viimeisessä vaiheessa piti sitten valita käyttäjätunnuksen ja organisaation nimen. Nimien keksiminen oli hiema haasteellista, koska sen piti olla jotain muuta kuin oma nimi taikka sen suuntaan olevia nimiä, lopulta sain keksittyä ja klikkasin viimeisessä vaiheessa “Lataa”. Tässä latauksen aikana ei tapahtunut mitään erityistä, muuta kuin sen että jatkoin tämän raportin kirjoittamista. Latauksen jälkeen virtuaalikone käynnistettiin uudestaan ja tällä kertaan jouduin käyttämään minun luoma käyttäjätunnus, jonka se jälkeen onnistuin kirjautumaan virtuaalikoneeseen eli kaikki meni juuri kuin piti.

## Free Software
> [!NOTE]
> Advises about risks or negative outcomes of certain actions.
Pieni tiivistys artikkellista
- Yleisin väärinkäsitys "Free Software" on se, että ihmiset luulevat sen tarkoittavan ohjelmistoa, joka on ilmainen. Mutta todellisuudessa se ei ole näin.
- “Free Software” tarkoittaa sitä, että käyttäjillä on vapaus käyttää, kopioida, jakaa, tutkia, muuttaa ja parantaa ohjelmistoa. 
- Ilmaisia ohjelmistoja voidaan käyttää kaupalliseen toimintaan
- Valtioiden määräykset tai kauppapakotteet voivat rajoittaa vapauttasi levittää ohjelmien kopioita kansainvälisesti.
ernment regulations or trade sanctions can limit your freedom to distribute copies of programs internationally.


# Raportin kirjoittaminen
> [!NOTE]
> Pieni tiivistys artikkellista
- Raportointi tarkoitettaan sillä, että kerrot yksityiskohtaisesti mitä teit, ja mitä sen jälkeen tapahtui.
- Lähteisiin viitaminen on isot plussat raportin tekemisessä.
- On otettava huomio raportin helppolukuisuus


### Lähdeet:
* GNU Operating System: What is Free Software?
(https://www.gnu.org/philosophy/free-sw.html)
* Koistinen, Tero 2006: Raportin kirjoittaminen
(https://terokarvinen.com/2006/raportin-kirjoittaminen-4/)
* Stratvert, Kevin 2023: How to use VirtualBox - Tutorial for Beginners
(https://www.youtube.com/watch?v=nvdnQX9UkMY)



