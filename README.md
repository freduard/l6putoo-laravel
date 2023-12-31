# Lõputöö

# Tiimi liikmed
- Markus Timofejev (www.lebra.ee)
- Fredy Ait (www.fredyait.com)
- Raiko Toomsalu (www.puuetegahaigla.ee)

## Ajakava
- Projekti analüüsimine 6. Oktoober - 

## Projekti eesmärk
Dünaamiliselt genereerida teoreetiline osa mis tahes projektidele.

## Teoreetilise osa nõuded
Teoreetilise osa soovituslik maht on 10-15 lehekülge, millele lisanduvad lisad. Töös kasutatakse
üldtunnustatud ja väljakujunenud erialast terminoloogiat (sulgudes kaldkirjas inglisekeelne termin) ning
lühendeid. 

### Töö eesmärk ja olulisus
Töö eesmärk on luua äpp, mis teeb mis tahes projekti teoreetilise (e. kirjaliku) osa lihtsamaks, vähem aega nõudvamaks ning mis oleks kättesaadav kõigile.
Oluliseks peame kirjaliku töö osa lihtsustamist.
### Tehniline kirjeldus
Projekti põhiliseks tugisambaks on Laravel. Front-end'is kasutame React'i, ShadCDN UI libraryt ja TailwindCSS'i.
### Praktilise teostuse kirjeldus
     
### Töö teostamiseks vajaliku meeskonna koosseis, ülesannete jaotus
### Projekti teostamise ajakava (ja eelarve)
- tulemuste analüüs.
   
Töö teoreetilises osas demonstreerib taotleja oma erialaseid teoreetilisi teadmisi kasutades erinevaid
allikaid (raamatuid, teaduslikke artikleid, juhendeid, tootjate kodulehekülgi jne). Kasutatud kirjanduse
loetellu pannakse allikad, mida on otseselt antud töö koostamisel kasutatud. Kasutatud allikatele on
viidatud töö tekstis.

## Praktilise osa nõuded

### Praktilises osas demonstreerib taotleja oma erialaseid praktilisi oskusi, luues lahenduse, mis on testitud,
töötav   ja   praktilise   väärtusega,   võimalusel   rakendatakse   käsitletava   ettevõtte   seisukohalt   uudset
lähenemist või uut tehnoloogiat. 

### Praktilise osa edukaks teostamiseks peab taotleja:

- hindama tehtavate tööde mahtu ja planeerida vajalikke tegevusi; 
- valima lahenduse loomiseks õiged töövahendid; 
- valima lahenduse loomiseks õiged töövõtted; 
- dokumenteerima oma tegevused; 
- töötama iseseisvalt ja/või meeskonnas

## Eksamitöö esitlemine ja hindamine

### Eksamitöö esitlemisele lubatakse kutse taotleja, kes on esitanud õigeaegselt nõuetekohaselt vormistatud
töö koos retsensiooni ja juhendaja arvamusega. 
 
Esitlemisel peab kutse taotleja ammendavalt vastama kõigile retsensendi ja hindamiskomisjoni liikmete
küsimustele   ning   argumenteeritult   kaitsma   oma   seisukohti,   kui   ta   ei   ole   nõus  retsensendi   või
hindamiskomisjoni liikmete märkustega.

## Töö hindamisel arvestab komisjon:

- kutse   taotleja   kaitsekõnet,   selle   ettevalmistust,   esinemise   korrektsust,   teema   valdamist,
seisukohtade kaitsmist; 

- töö aktuaalsust, ülesannete õiget püstitamist ja loogilist lahendamist, püstitatud eesmärgi
saavutamist; 

- töö vormistust ja selle vastavust kirjalike tööde vormistamise juhendile; 
retsensendi hinnangut; 

- kutse taotleja argumenteeritud vastuseid retsensendi, komisjoni liikmete ja kuulajate poolt
esitatud küsimustele;

kõik hindamiskriteeriumid peavad olema täidetud vähemalt minimaalsel tasemel.

## Kirjaliku töö vormistamise nõuded
[kirjaliku_toojuhend.pdf](https://github.com/freduard/l6putoo-laravel/files/12827760/kirjaliku_toojuhend.pdf)


# Analüüs
## Header
- Avalehe link
- Uue PDF faili genereerimise link
#### Profiil
- Profiilile viitav nupp
- Välja logimise nupp

## Profiili leht
#### Andmete uuendamise sektsioon
- Kasutajanime sisend
- Meili sisend
- Uute andmete salvestamise nupp
- 
#### Parooli uuendamise sektsioon
- Praeguse parooli sisend
- Uue parooli sisend
- Uue parooli kordamise sisend
- Uue parooli salvestamise nupp
- 
#### Konto kustutamise sektsioon
- Konto kustutamise nupp
- Konto kustamise vorm kus on vaja sisestada parool kinnituseks

## Login Leht
- Lühike tutvustus meie äpist
- Emaili/kasutajanime sisend
- Parooli sisend
- Salasõna unustamise nupp
- Login andmete salvestamise nupp
- Registreeremise nupp

## Registreerimise leht
- Kasutajanime sisend
- Emaili sisend
- Parooli sisend
- Konto registreerimis nupp
- Sisse logimise nupp juhul kui kasutajal on konto juba olemas

## Salasaõna lähtestamine
- Emaili sisestamine
- Kinnituse nupule vajutades tuleb kasutajale meil salasõna lähtestamise lingiga
#### Salasõna lähtestamise vorm
- Uue parooli sisend
- Uue parooli kordamise sisend

## Avaleht

#### Kasutaja tervitus
- Tervitame kasutajat kasutades tema konto nime.

#### Genereeritud PDF failid avalehel
- Avalehel on list/array PDF faile mis kasutaja on varasemalt genereerinud.
- PDF fail on allalaetav ja listist/arrayst kustutatav.

## Footer
- Tiimi liikmed piltidega ja portfoolio linkidega
- Kontaktandmed
- Kasutatud allikad

## PDF Loomise leht
- Ainult sisse logitud kasutaja saab ligipääsu.

#### Tiitellehe sektsioon
- Tiitelleht, kus on sisenditeks:
  Kooli nimi, õppesuuna nimi, eriala nimi, oma nimi, töö pealkiri, tööliik, juhendaja nimi, kuupäev.

#### Järjekord
 - Automaatselt genereerimine pealkirjade põhjal.

#### Sissejuhatus
- Sisend, kus kasutaja kirjeldab lühidalt oma tööd.


#### Sisu sektsioon
- Sisend, kus kasutaja kirjeldab enda töö sisu ja toob välja erinevaid näiteid.
- Kasutaja saab luua uusi pealkirju lühikese kirjeldusega.
- Kasutaja saab kustutada pealkirju ja kirjeldusi.

#### Kokkuvõtte sektsioon

- Sisend, kus kasutaja toob kokku lühidalt terve oma töö.

#### Kasutatud allikad

- Sisend, kus on lingid allikatest, mida kasutaja on kasutanud oma töös.


  




 
