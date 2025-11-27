# 2. Softverska dokumentacija

## 2.1. Uvod

### 2.1.1. Svrha  
**Odgovorna osoba za poglavlje:**  
*Marija Bilić*

<p align="justify">
Ovaj dokument pruža detaljan pregled svih korisničkih i softverskih zahtjeva za sustav <b>PlanIt</b>. Sustav korisnicima omogućuje kreiranje, organizaciju i praćenje manjih privatnih događaja, uz definiranje osnovnih informacija o događaju, pozivanje sudionika, dodjelu zaduženja, vođenje To-Do liste te pohranu materijala vezanih uz događaj (npr. letci, fotografije). Glavni je cilj sustava smanjiti neorganizirane i nepregledne dogovore putem grupnih chatova te osigurati centraliziran i jasan pregled svih dogovora i obveza vezanih uz događaj.
</p>

<p align="justify">
Dokument služi kao komunikacijski most između svih sudionika u projektu, uključujući projektni tim, mentora/naručitelja i buduće korisnike sustava. Korisnici sustava obuhvaćaju organizatore događaja, sudionike događaja te, prema potrebi, administratore sustava koji upravljaju korisnicima i tehničkim postavkama aplikacije.
</p>

***

### 2.1.2. Opseg  
**Odgovorna osoba za poglavlje:**  
*Ana Bilić*

<p align="justify">
Ovaj dokument definira opseg softverskog rješenja <b>PlanIt</b>, desktop aplikacije namijenjene pojedincima koji žele jednostavno i pregledno planirati manje privatne događaje. Aplikacija je zamišljena kao jedinstveni alat za jednog korisnika (organizatora događaja) i ne podržava višekorisnički rad, administraciju računa ili uloge korisnika.
</p>

<p align="justify">
PlanIt omogućuje korisniku kreiranje događaja, unos osnovnih podataka (naziv, opis, datum, vrijeme i lokacija), upravljanje pripremnim aktivnostima kroz To-Do listu i zaduženja te pohranu sadržaja vezanih uz događaj. Nakon što prođe datum i vrijeme održavanja, događaj se automatski premješta u arhivu, gdje korisnik može unijeti osobni osvrt i dodati fotografije. Korisnik također ima mogućnost trajnog brisanja arhiviranih događaja.
</p>

<p align="justify">
Desktop verzija dodatno omogućuje generiranje promotivnih letaka u PDF formatu te slanje jednostavnih e-mail pozivnica ručnim unosom e-mail adrese primatelja. Također, aplikacija omogućuje izradu osnovnih izvještaja o događajima na temelju postojećih podataka, uključujući broj kreiranih, održanih i otkazanih događaja u zadanom vremenskom razdoblju.
</p>

<p align="justify">
U opseg sustava uključene su sljedeće funkcionalnosti:
</p>

- upravljanje korisničkim računom (registracija, prijava, odjava)  
- kreiranje, uređivanje i brisanje događaja  
- automatsko premještanje događaja u arhivu nakon isteka vremena održavanja  
- mogućnost unosa osvrta i dodavanja fotografija za arhivirane događaje  
- upravljanje To-Do stavkama i zaduženjima  
- slanje jednostavnih e-mail pozivnica ručnim unosom adresa  
- generiranje promotivnih letaka u PDF formatu  
- generiranje osnovnih izvještaja o događajima   

***

### 2.1.3. Definicije, akronimi i skraćenice

***

### 2.1.4. Reference  
**Odgovorna osoba za poglavlje:**  
*Marija Bilić*
- IEEE Std 830-1998 – *IEEE Recommended Practice for Software Requirements Specifications*.
- IEEE Std 1016-2009 – *IEEE Standard for Information Technology – Systems Design – Software Design Descriptions*.
- Microsoft .NET documentation – pregled tehnologija .NET i C#: https://learn.microsoft.com/dotnet/
- Microsoft WPF documentation – specifikacije i primjeri za izradu desktop aplikacija: https://learn.microsoft.com/dotnet/desktop/wpf/
- Uredba (EU) 2016/679 (GDPR) – opća uredba o zaštiti osobnih podataka, relevantna za obradu korisničkih podataka u aplikaciji.

***

### 2.1.5. Struktura dokumenta
**Odgovorna osoba za poglavlje:**  
*Ana Bilić*

- U prvom poglavlju opisani su svrha projekta, ciljevi te osnovne informacije o sustavu PlanIt.
- Drugo poglavlje daje općeniti pregled aplikacije, uključujući perspektivu proizvoda, funkcije sustava, karakteristike korisnika, ograničenja te pretpostavke i ovisnosti.
- Treće poglavlje sadrži detaljnu specifikaciju funkcionalnih i nefunkcionalnih zahtjeva sustava, zajedno sa skicama korisničkog sučelja.
- Četvrto poglavlje prikazuje nefunkcionalne zahtjeve poput izgleda softvera, performansi, sigurnosti, upotrebljivosti i održavanja.
- Peto poglavlje uključuje skice ekrana i vizualne prototipove aplikacije.
- Šesto poglavlje prikazuje dizajn softverskog sustava, uključujući podatkovni model, dijagrame i sveukupnu strukturu aplikacije.
- Sedmo poglavlje donosi zaključak i završni osvrt na ostvarene ciljeve projekta.


## 2.2. Općeniti opis
### 2.2.1. Uvod
**Odgovorna osoba za poglavlje:**  
*Marija Bilić*

<p align="justify">
Aplikacija <b>PlanIt</b> obuhvaća 9 glavnih funkcionalnih zahtjeva (F01–F09) koji zajedno čine cjelovito programsko rješenje za planiranje manjih privatnih događaja. Sustav korisnicima omogućuje kreiranje događaja, upravljanje osnovnim informacijama (naziv, opis, datum, lokacija, organizator), dodjelu zaduženja, vođenje To-Do liste, slanje e-mail pozivnica, generiranje letaka u PDF formatu s QR kodom, pohranu fotografija te generiranje osnovnih izvještaja o održanim, otkazanim i nadolazećim događajima.
</p>

### 2.2.2. Perspektiva proizvoda  
**Odgovorna osoba za poglavlje:**  
*Ana Bilić*

<p align="justify">
PlanIt se ponaša kao digitalni planer ili osobni organizator. Korisnik kreira i upravlja vlastitim događajima, vodi pripremne aktivnosti kroz To-Do listu i zaduženja, dodaje fotografije te nakon održavanja može napisati osvrt na događaj. Sustav automatski premješta prošle događaje u arhivu, čime se održava preglednost glavnog popisa.
</p>

<p align="justify">
Aplikacija također nudi nekoliko dodatnih funkcionalnosti koje proširuju osnovnu svrhu planiranja događaja, poput generiranja promotivnih letaka u PDF formatu, slanja jednostavnih e-mail pozivnica te izrade osnovnih izvještaja na temelju postojećih podataka. Ove funkcionalnosti ne mijenjaju osobnu prirodu sustava, već korisniku pružaju dodatne alate za organizaciju događaja.
</p>

***

### 2.2.3. Funkcije proizvoda

***

### 2.2.4. Karakteristike korisnika  
**Odgovorna osoba za poglavlje:**  
*Marija Bilić*

<p align="justify">
Korisnici aplikacije <b>PlanIt</b> su pojedinci koji povremeno organiziraju manja privatna okupljanja. Uobičajeno je riječ o studentima, mladim zaposlenim osobama ili članovima obitelji koji žele imati jednostavan pregled svojih događaja i pripadajućih obveza.
</p>

<p align="justify">
Očekuje se osnovna razina računalne i tehničke pismenosti – korisnici znaju koristiti tipkovnicu i miša, instalirati i pokrenuti desktop aplikaciju te se prijaviti s korisničkim imenom i lozinkom. Dodatna edukacija nije potrebna; sučelje je zamišljeno kao intuitivno, s jasnim oznakama polja i tipki.
</p>

<p align="justify">
Učestalost korištenja aplikacije ovisi o broju događaja koje korisnik organizira, pri čemu se pretpostavlja da će aplikacija biti korištena nekoliko puta mjesečno ili po potrebi (prije i nakon određenog događaja). Svi korisnici imaju istu ulogu organizatora događaja i jednaku razinu dozvola u sustavu – mogu kreirati, uređivati i brisati vlastite događaje, zadatke, To-Do stavke, generirati letke i izvještaje te slati e-mail pozivnice.
</p>

***

### 2.2.5. Ograničenja  
**Odgovorna osoba za poglavlje:**  
*Ana Bilić*

- Sigurnost: Korisnički podaci moraju biti zaštićeni od neovlaštenog pristupa. Podaci za prijavu (lozinke) hashiraju se i ne čuvaju se u izvornom obliku. Sustav mora osigurati osnovnu razinu sigurnosti lokalno pohranjenih podataka.
- Pristup podacima: Svi podaci pohranjuju se u lokalnoj bazi podataka. Aplikaciji može pristupiti samo korisnik računala na kojem je instalirana, a odgovornost za zaštitu korisničkog računa na operacijskom sustavu leži na samom korisniku.
- Ovisnost o okruženju: Aplikacija ovisi o ispravnoj instalaciji .NET okvira i dostupnosti lokalne baze podataka. Funkcionalnosti koje koriste internet (npr. slanje e-mail pozivnica) zahtijevaju aktivnu mrežnu vezu i ispravne SMTP postavke.
- Performanse lokalnog uređaja: Brzina i stabilnost aplikacije ovise o performansama računala korisnika (memorija, procesor, dostupnost diska). Kod velikog broja fotografija ili dokumenata može doći do sporijeg rada aplikacije.

***

### 2.2.6. Pretpostavke i ovisnosti

***

## 2.3. Funkcionalni zahtjevi
<p align="justify">
Prilikom definiranja funkcionalnih zahtjeva koristi se sustav prioriteta od 1 do 3, gdje prioritet 1 označava najvažnije funkcionalnosti sustava koje moraju biti implementirane kako bi aplikacija ispravno radila. Prioritet 2 odnosi se na funkcionalnosti srednje važnosti koje značajno poboljšavaju korisničko iskustvo, dok prioritet 3 obuhvaća dodatne funkcionalnosti koje nisu ključne za osnovni rad aplikacije, ali doprinose njenoj cjelovitosti i praktičnosti.</p>

### 2.3.1. Upravljanje korisničkim računom

**Odgovorna osoba za poglavlje:**  
*Ana Bilić*

| Identifikator | FZ-1 |
|--------------|------|
| Zahtjev  | Sustav mora omogućiti registraciju, prijavu i odjavu korisnika kako bi se osigurao pristup osobnim podacima i događajima samo ovlaštenom korisniku. |
| Obrazloženje | Korisnik mora imati mogućnost izrade vlastitog računa, prijave u sustav te odjave nakon završetka rada. Time se štite osobni podaci i događaji pohranjeni u aplikaciji. Prilikom registracije korisnik unosi osnovne podatke, a lozinka se sprema u hashiranom obliku radi sigurnosti. |
| Način provjere | Kreirati testnog korisnika, pokušati registraciju bez potrebnih podataka, provjeriti prijavu s ispravnim i neispravnim podacima te potvrditi da odjava vraća korisnika na početni ekran aplikacije. |
| Prioritet | 1 |
| Zaduženje | Ana Bilić |
| Izvor | Projektna prijava – funkcionalni zahtjev F01 |
| Skica | – |

***

### 2.3.2. Unos osobnog osvrta na događaj

**Odgovorna osoba za poglavlje:**  
*Ana Bilić*

| Identifikator | FZ-2 |
|--------------|------|
| Zahtjev  | Sustav će omogućiti unos osobnog osvrta, komentara i bilješki nakon što događaj prođe te se automatski premjesti u arhivu. |
| Obrazloženje | Nakon održanog događaja korisniku je korisno zapisati dojam, zaključke, što je prošlo dobro, a što lošije te sačuvati te informacije za buduće planiranje. Osvrt se sprema u bazu podataka i trajno je povezan s arhiviranim događajem. |
| Način provjere | Kreirati testni događaj, promijeniti datum održavanja kako bi prešao u arhivu, otvoriti arhivu, unijeti osvrt i provjeriti je li uspješno spremljen i ponovno dohvatljiv. |
| Prioritet | 3 |
| Zaduženje | Ana Bilić |
| Izvor | Projektna prijava – funkcionalni zahtjev F02 |
| Skica | – |


***

### FZ-3 | Upravljanje događajima (CRUD)

***

### 2.3.4. Generiranje letaka za događaje

**Odgovorna osoba za poglavlje:**  
*Marija Bilić*

| Identifikator | FZ-4 |
|--------------|------|
| Zahtjev  | Sustav će omogućiti generiranje promotivnog letka u PDF formatu za odabrani događaj, s osnovnim informacijama o događaju (naziv, datum, vrijeme, lokacija) i pripadajućim QR kodom. Letak se sprema kao PDF datoteka na računalo korisnika. |
| Obrazloženje | Organizator često treba jednostavan i pregledan dokument koji može ispisati ili samostalno podijeliti sudionicima. Letak se automatski popunjava na temelju već unesenih podataka o događaju, čime se smanjuje mogućnost pogreške i dodatnog ručnog unosa. |
| Način provjere | Kreirati testni događaj, odabrati opciju „Generiraj letak“ te provjeriti je li PDF datoteka generirana i spremljena. Otvoriti letak i provjeriti prikaz osnovnih podataka o događaju i prisutnost QR koda koji se može uspješno očitati. |
| Prioritet | 2 |
| Zaduženje | Marija Bilić |
| Izvor | Projektna prijava – funkcionalni zahtjev F04 |
| Skica | [Prikaži skicu](#FZ4) |


***

### 2.3.5. Slanje e-mail pozivnica

**Odgovorna osoba za poglavlje:**  
*Marija Bilić*

| Identifikator | FZ-5 |
|--------------|------|
| Zahtjev  | Sustav mora omogućiti organizatoru slanje e-mail pozivnica za odabrani događaj. Organizator u aplikaciji unosi jednu ili više e-mail adresa primatelja, a sustav šalje poruku s osnovnim informacijama o događaju (naziv, datum, vrijeme, lokacija). |
| Obrazloženje | Organizator često želi brzo obavijestiti sudionike o terminu i mjestu događaja. Slanje e-mail pozivnice izravno iz aplikacije pojednostavljuje proces i smanjuje potrebu za ručnim prepisivanjem podataka o događaju u druge alate. |
| Način provjere | Kreirati testni događaj, otvoriti opciju „Pošalji e-mail pozivnice“, unijeti testnu e-mail adresu i poslati pozivnicu. Provjeriti je li poruka stigla na unesenu adresu te sadrži tražene informacije o događaju. |
| Prioritet | 2 |
| Zaduženje | Marija Bilić |
| Izvor | Projektna prijava – funkcionalni zahtjev F05 |
| Skica | [Prikaži skicu](#FZ5) |

***

### 2.3.6. Određivanje zaduženja za događaje

***

### 2.3.7. Prenošenje fotografija s događaja

**Odgovorna osoba za poglavlje:**  
*Ana Bilić*

| Identifikator | FZ-7 |
|--------------|------|
| Zahtjev  | Sustav mora omogućiti dodavanje i pohranu fotografija povezanih s pojedinim događajem, uz spremanje putanje datoteke u bazu podataka. |
| Obrazloženje | Korisnik često želi spremiti fotografije s događaja zajedno s ostalim informacijama. Zbog veličine datoteka fotografije se ne pohranjuju izravno u bazu, već se sprema samo putanja do datoteke koja se čuva lokalno na računalu korisnika. |
| Način provjere | U arhiviranom događaju odabrati opciju „Dodaj fotografiju“, učitati jednu ili više slika te provjeriti je li putanja spremljena u bazu i je li fotografiju moguće kasnije ponovno prikazati. |
| Prioritet | 2 |
| Zaduženje | Ana Bilić |
| Izvor | Projektna prijava – funkcionalni zahtjev F07 |
| Skica | – |

***

### 2.3.8. Pregled povratnih informacija za događaj

***

### 2.3.9. Generiranje izvještaja o događajima

**Odgovorna osoba za poglavlje:**  
*Marija Bilić*

| Identifikator | FZ-9 |
|--------------|------|
| Zahtjev  | Sustav će omogućiti generiranje izvještaja o broju kreiranih, održanih i otkazanih događaja te njihovoj posjećenosti u odabranom vremenskom razdoblju. Izvještaj se prikazuje u obliku pregleda (npr. tablica i sažeti pokazatelji) unutar aplikacije. |
| Obrazloženje | Organizatoru je potrebno imati uvid u vlastitu aktivnosti – koliko je događaja planirano, koliko ih je stvarno održano, koliko je otkazano te kolika je bila posjećenost pojedinih događaja. Takav pregled olakšava planiranje budućih događaja i praćenje navika sudionika. |
| Način provjere | U bazi podataka evidentirati nekoliko događaja različitih statusa (kreiran, održan, otkazan) i s različitim vrijednostima posjećenosti. Pokrenuti generiranje izvještaja za razdoblje koje obuhvaća te događaje te provjeriti podudaraju li se prikazane brojke sa zapisima u bazi. |
| Prioritet | 3 |
| Zaduženje | Marija Bilić |
| Izvor | Projektna prijava – funkcionalni zahtjev F09 |
| Skica | [Prikaži skicu](#FZ9) |

## 2.4. Nefunkcionalni zahtjevi
### 2.4.1. Izgled softvera
### 2.4.2. Performanse
### 2.4.3. Sigurnost
### 2.4.4. Upotrebljivost
### 2.4.5. Održavanje

## 2.5. Skice
### 2.5.1. FZ-1 Upravljanje korisničkim računom

<img width="700" alt="FZ-1 Prijava" src="https://github.com/user-attachments/assets/3b2319b6-bec8-4a1e-83e7-4a9163479997" />

<img width="700" alt="FZ-1 Registracija" src="https://github.com/user-attachments/assets/efaf2676-893b-452d-bf6a-efddfde761b6" />

### 2.5.2. FZ-2 Unos osobnog osvrta na događaj

<img width="700" alt="FZ-2 Osvrt na događaj - 1" src="https://github.com/user-attachments/assets/82cd29b4-d121-40c7-a784-46d3c5fefad9" />

<img width="700" alt="FZ-2 Osvrt na događaj - 2" src="https://github.com/user-attachments/assets/6a9f8343-09bd-4407-8cc0-db068e202842" />





### 2.5.3. FZ-3 Upravljanje događajima (CRUD)
### 2.5.4. FZ-4 Generiranje letaka za događaje
### 2.5.5. FZ-5 Slanje e-mail pozivnica
### 2.5.6. FZ-6 Određivanje zaduženja za događaje
### 2.5.7. FZ-7 Prenošenje fotografija s događaja
### 2.5.8. FZ-8 Upravljanje To-Do listom
### 2.5.9. FZ-9 Generiranje izvještaja o događajima


## 2.6. Dizajn softverskog sustava
### 2.6.1. Podatkovni model cijelog sustava

### 2.6.2. FZ-1 | Upravljanje korisničkim računom
**Odgovorna osoba za poglavlje:**  
*Ana Bilić*

Naziv | **Opis**
-|-
Naziv | Upravljanje korisničkim računom (FZ-1)
Kratki opis | Sustav omogućuje registraciju, prijavu i odjavu korisnika. Prilikom registracije korisnik unosi osnovne podatke, a lozinka se sprema u hashiranom obliku. Prijava omogućuje pristup osobnim događajima, dok odjava vraća korisnika na početni ekran.
Sudionici | Korisnik (organizator)
Okidač | Korisnik otvara aplikaciju te odabire opciju za registraciju ili prijavu.
Preduvjet za uspješno izvršenje | Korisnik unosi sve potrebne podatke za registraciju ili prijavu. Sustav ispravno pohranjuje korisničke podatke u lokalnu bazu.
Stanje sustava nakon uspješnog izvršenja | Korisnik je uspješno prijavljen i ima pristup svim funkcionalnostima aplikacije. Odjavom se vraća na početni ekran.
Iznimke | Pokušaj registracije s postojećim korisničkim imenom; pogrešno unesena lozinka; neispravan format e-mail adrese; prazna obavezna polja.
Stanje sustava nakon pojave iznimke | Sustav prikazuje odgovarajuću poruku o grešci, a korisnik ostaje na obrascu za prijavu ili registraciju.
Standardni proces | (1) Korisnik odabire registraciju ili prijavu. <br> (2) Korisnik unosi podatke. <br> (3) Sustav provjerava valjanost podataka. <br> (4) Ako su podaci ispravni, korisnik se prijavljuje i otvara se glavni ekran. <br> (5) Korisnik se može odjaviti putem opcije „Odjava“.
Alternativni procesi | (3') Ako je lozinka netočna, prikazuje se poruka i korisnik ostaje na ekranu prijave. <br> (3'') Ako korisničko ime već postoji, registracija se ne izvršava i prikazuje se upozorenje. <br> (2') Ako korisnik odustane, vraća se na početni ekran aplikacije.

### 2.6.3. FZ-2 | Unos osobnog osvrta na događaj  

**Odgovorna osoba za poglavlje:**  
*Ana Bilić*

Naziv | **Opis**
-|-
Naziv | Unos osobnog osvrta na događaj (FZ-2)
Kratki opis | Nakon što događaj prođe i automatski prijeđe u arhivu, korisnik može otvoriti detalje arhiviranog događaja i unijeti osobni osvrt ili bilješku. Uneseni tekst sprema se u bazu podataka i ostaje trajno povezan s događajem.
Sudionici | Korisnik (organizator)
Okidač | Korisnik otvara arhivu događaja i odabire opciju „Dodaj osvrt“.
Preduvjet za uspješno izvršenje | Događaj je prošao (datum i vrijeme održavanja su iza sadašnjeg vremena) i nalazi se u arhivi.
Stanje sustava nakon uspješnog izvršenja | Osvrt je uspješno spremljen u bazu podataka, a korisnik ga može naknadno pregledati ili uređivati.
Iznimke | Korisnik pokuša spremiti prazan osvrt; korisnik napusti obrazac bez spremanja; dolazi do pogreške pri spremanju podataka.
Stanje sustava nakon pojave iznimke | Osvrt se ne sprema, prikazuje se poruka o grešci, korisnik ostaje na ekranu osvrta.
Standardni proces | (1) Korisnik otvara arhivu. <br> (2) Odabire događaj. <br> (3) Klikom na „Dodaj osvrt“ unosi tekst. <br> (4) Odabire „Spremi“. <br> (5) Sustav sprema podatke i prikazuje poruku o uspjehu.
Alternativni procesi | (3') Korisnik unese prazan tekst → sustav prikazuje upozorenje. <br> (4') Ako korisnik klikne „Odustani“, vraća se na detalje događaja. <br> (5') Ako se pojavi pogreška u spremanju, prikazuje se poruka o grešci.


### 2.6.4. FZ-3 | Upravljanje događajima (CRUD)

### 2.6.5. FZ-4 | Generiranje letaka za događaje

**Odgovorna osoba za poglavlje:**  
*Marija Bilić*

Naziv | **Opis**
-|-
Naziv | Generiranje letka za događaj (FZ-4)
Kratki opis | Korisnik (organizator događaja) za odabrani događaj generira promotivni letak u PDF formatu koji sadrži osnovne informacije o događaju (naziv, datum, vrijeme, lokacija) i QR kod. Letak se sprema na računalo korisnika.
Sudionici | Korisnik (organizator događaja)
Okidač | Korisnik je prijavljen u aplikaciju, nalazi se na popisu ili detaljima događaja i odabire opciju „Generiraj letak“.
Preduvjet za uspješno izvršenje | Događaj postoji u sustavu i sadrži osnovne podatke (naziv, datum, vrijeme, lokacija). Korisnik ima mogućnost spremanja PDF datoteka na računalo.
Stanje sustava nakon uspješnog izvršenja | Generiran je PDF letak s podacima o događaju i QR kodom te je datoteka spremljena na odabranu lokaciju. Korisniku se prikazuje poruka o uspješnom generiranju.
Iznimke | Nedostaju potrebni podaci o događaju; korisnik odustane od spremanja datoteke; dolazi do pogreške pri generiranju ili spremanju PDF-a.
Stanje sustava nakon pojave iznimke | Letak nije generiran ili nije spremljen. Sustav prikazuje poruku o pogrešci i korisnik ostaje na ekranu događaja.
Standardni proces | (1) Korisnik odabire događaj. <br> (2) Korisnik pritišće gumb „Generiraj letak“. <br> (3) Sustav provjerava potrebne podatke o događaju. <br> (4) Sustav generira PDF letak s podacima i QR kodom. <br> (5) Korisnik odabire lokaciju spremanja datoteke. <br> (6) Sustav sprema datoteku i prikazuje poruku o uspjehu.
Alternativni procesi | (3') Ako nedostaju podaci o događaju, sustav prekida generiranje i prikazuje poruku o grešci. <br> (5') Ako korisnik odustane od spremanja, letak se ne sprema i prikazuje se informativna poruka. <br> (4''/5'') Ako dođe do tehničke pogreške, sustav prikazuje poruku o grešci i ne mijenja podatke o događaju.

***

### 2.6.6. FZ-5 | Slanje e-mail pozivnica

**Odgovorna osoba za poglavlje:**  
*Marija Bilić*

Naziv | **Opis**
-|-
Naziv | Slanje e-mail pozivnica (FZ-5)
Kratki opis | Organizator za odabrani događaj iz aplikacije šalje e-mail pozivnice. U posebnom obrascu upisuje e-mail adresa primatelja, a sustav automatski šalje poruku s osnovnim informacijama o događaju (naziv, datum, vrijeme, lokacija).
Sudionici | Korisnik (organizator događaja)
Okidač | Korisnik je prijavljen u aplikaciju, odabrao je događaj i klikne na opciju „Pošalji e-mail pozivnice“.
Preduvjet za uspješno izvršenje | Događaj postoji u sustavu i sadrži osnovne podatke (naziv, datum, vrijeme, lokacija). Aplikacija ima ispravno podešene podatke za slanje e-pošte (npr. SMTP postavke). Korisnik unosi barem jednu valjanu e-mail adresu primatelja.
Stanje sustava nakon uspješnog izvršenja | E-mail poruke s osnovnim informacijama o događaju poslane su na unesene adrese. Korisniku se prikazuje poruka da su pozivnice uspješno poslane (ili koliko ih je uspješno poslano).
Iznimke | Nije unesena nijedna e-mail adresa; unesena je e-mail adresa neispravnog formata; dođe do pogreške pri slanju (npr. nema internetske veze, krive SMTP postavke); korisnik prekine slanje.
Stanje sustava nakon pojave iznimke | Nijedna pozivnica nije poslana ili je poslan samo dio pozivnica. Sustav prikazuje poruku o grešci (npr. „Unesite barem jednu valjanu e-mail adresu“ ili „Slanje e-pošte nije uspjelo“) i korisnik ostaje na obrascu za slanje pozivnica.
Standardni proces | (1) Korisnik odabire događaj. <br> (2) Korisnik pritisne „Pošalji e-mail pozivnice“. <br> (3) Sustav prikazuje obrazac za unos e-mail adresa. <br> (4) Korisnik unosi jednu ili više e-mail adresa i potvrdi slanje. <br> (5) Sustav provjerava format unesenih adresa. <br> (6) Sustav šalje e-mail poruke s podacima o događaju. <br> (7) Po završetku slanja sustav prikazuje poruku o uspjehu.
Alternativni procesi | (4') Korisnik ostavi polje za e-mail adrese prazno → sustav prikaže poruku „Unesite barem jednu e-mail adresu“ i ne započinje slanje. <br> (5') Ako neka adresa nije ispravnog formata, sustav označi problematičnu adresu i traži ispravak. <br> (6') Ako dođe do tehničke pogreške pri slanju (npr. nema internetske veze), sustav prekida proces i prikazuje poruku o grešci. <br> (4'') Ako korisnik odabere „Odustani“, slanje se ne izvršava i korisnik se vraća na ekran događaja.

### 2.6.7. FZ-6 | Određivanje zaduženja za događaje

### 2.6.8. FZ-7 | Prenošenje fotografija s događaja  

**Odgovorna osoba za poglavlje:**  
*Ana Bilić*

Naziv | **Opis**
-|-
Naziv | Prenošenje fotografija s događaja (FZ-7)
Kratki opis | Sustav omogućuje dodavanje jedne ili više fotografija uz arhivirani događaj. Fotografije se učitavaju s računala korisnika, a u bazu podataka sprema se samo putanja do datoteke.
Sudionici | Korisnik (organizator)
Okidač | Korisnik otvara arhivirani događaj i odabire opciju „Dodaj fotografiju“.
Preduvjet za uspješno izvršenje | Odabrani događaj mora biti arhiviran. Fotografija mora biti valjana datoteka (slika) i dostupna na korisničkom računalu.
Stanje sustava nakon uspješnog izvršenja | Putanja fotografije uspješno se sprema u bazu podataka, a korisnik može vidjeti pregled dodanih fotografija.
Iznimke | Neispravna datoteka; nepostojeća putanja; korisnik odustane od dodavanja; pogreška pri spremanju putanje.
Stanje sustava nakon pojave iznimke | Fotografija nije dodana, prikazuje se poruka o grešci i korisnik ostaje na zaslonu događaja.
Standardni proces | (1) Korisnik otvara arhivirani događaj. <br> (2) Odabire „Dodaj fotografiju“. <br> (3) Učita fotografiju s računala. <br> (4) Sustav sprema putanju u bazu. <br> (5) Fotografija se prikazuje u detaljima događaja.
Alternativni procesi | (3') Korisnik odabere neispravnu datoteku → sustav prikazuje upozorenje. <br> (3'') Korisnik odustane od dodavanja → vraća se na ekran detalja. <br> (4') Ako spremanje putanje ne uspije, sustav prikazuje poruku o grešci.

### 2.6.9. FZ-8 | Pregled povratnih informacija za događaj

### 2.6.10. FZ-9 | Generiranje izvještaja o događajima

**Odgovorna osoba za poglavlje:**  
*Marija Bilić*

Naziv | **Opis**
-|-
Naziv | Generiranje izvještaja o događajima (FZ-9)
Kratki opis | Korisnik (organizator) odabire vremensko razdoblje i generira izvještaj o svojim događajima. Izvještaj prikazuje broj kreiranih, održanih i otkazanih događaja te osnovne informacije o njihovoj posjećenosti u odabranom razdoblju.
Sudionici | Korisnik (organizator događaja)
Okidač | Korisnik je prijavljen u aplikaciju, otvara ekran „Izvještaji“ i odabire vremensko razdoblje za koje želi pregled.
Preduvjet za uspješno izvršenje | U bazi postoje događaji s definiranim datumom, statusom (npr. planiran, održan, otkazan) i, po potrebi, brojem sudionika. Korisnik je ispravno odabrao početni i završni datum izvještaja.
Stanje sustava nakon uspješnog izvršenja | Na ekranu se prikazuju agregirani podaci za odabrano razdoblje (broj kreiranih, održanih i otkazanih događaja, osnovni podaci o posjećenosti). Korisnik može pregledati sažetak i, po potrebi, promijeniti razdoblje ili zatvoriti ekran.
Iznimke | U odabranom razdoblju nema događaja; korisnik unese nelogično razdoblje (npr. završni datum prije početnog); dođe do pogreške pri dohvaćanju podataka iz baze.
Stanje sustava nakon pojave iznimke | Ako nema događaja, prikazuje se informativna poruka (npr. „Nema događaja u odabranom razdoblju“). Ako je razdoblje neispravno, sustav traži ispravak datuma. U slučaju tehničke pogreške prikazuje se poruka o grešci, a izvještaj se ne prikazuje.
Standardni proces | (1) Korisnik otvara ekran „Izvještaji“. <br> (2) Korisnik odabire početni i završni datum. <br> (3) Korisnik pritisne gumb „Generiraj izvještaj“. <br> (4) Sustav dohvaća događaje u odabranom razdoblju. <br> (5) Sustav računa broj kreiranih, održanih i otkazanih događaja te osnovne pokazatelje posjećenosti. <br> (6) Sustav prikazuje rezultate na ekranu.
Alternativni procesi | (3') Ako korisnik unese neispravno razdoblje (završni datum prije početnog), sustav prikaže poruku i traži ispravak. <br> (4') Ako u odabranom razdoblju nema događaja, sustav prikazuje poruku da nema podataka za prikaz. <br> (5') Ako dođe do pogreške pri dohvaćanju podataka, sustav prikaže poruku o grešci i ne mijenja trenutno stanje prikaza.

***

## 2.7. Zaključak  
**Odgovorna osoba za poglavlje:**  
*Svi članovi tima*

<p align="justify">
Ovaj dokument pruža detaljan uvid u funkcionalne i nefunkcionalne zahtjeve aplikacije <b>PlanIt</b>, kao i opis njene arhitekture, dizajna i načina rada. Sustav je osmišljen kako bi olakšao planiranje manjih privatnih događaja, omogućio korisnicima preglednu organizaciju aktivnosti i zaduženja te pružio dodatne mogućnosti poput generiranja letaka, pohrane fotografija i izrade osnovnih izvještaja.</p>

<p align="justify">
Struktura i definirane funkcionalnosti osiguravaju jednostavno korištenje, intuitivno korisničko sučelje te stabilan rad aplikacije u jednokorisničkom okruženju. Dokumentacija služi kao temelj za implementaciju i daljnji razvoj sustava te omogućuje jasnu komunikaciju između svih sudionika projekta.</p>
