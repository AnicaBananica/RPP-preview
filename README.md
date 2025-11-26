# 1. Projektni plan
## 1.1. Svrha i ciljevi projekta:

[Marin Grabovac]

Svrha projekta "Varaždinski gradski info" je razviti aplikaciju za prijavu problema u zajednici i informiranje građana, koja će omogućiti **brzu i jednostavnu komunikaciju između građana i gradske uprave. Aplikacija će omogućiti korisnicima da prijavljuju probleme i nepravilnosti u svojim lokalnim zajednicama, pružaće **obavijesti o važnim infrastrukturnim radovima, **hitnim situacijama, kao i **pomoć u pristupu lokalnim uslugama i informacijama. Također, aplikacija će omogućiti građanima da aktivno sudjeluju u životu zajednice, dijele prijedloge za poboljšanja i glasaju za ideje drugih korisnika putem **foruma za prijedloge.

Projekt ima nekoliko ključnih ciljeva:

1. Povećanje angažmana građana: Kroz omogućavanje građanima da lako prijavljuju probleme i daju prijedloge, aplikacija će potaknuti veće sudjelovanje u procesima odlučivanja i razvoju zajednice.
   
2. Učinkovitije upravljanje gradskim problemima: Omogućavanjem građanima da prijavljuju probleme putem aplikacije, grad će moći brže i učinkovitije reagirati na komunalne i infrastrukturne izazove.

3. Transparentnost i informiranje: Građani će imati pristup informacijama o trenutnim i nadolazećim infrastrukturnim projektima, dežurnim zdravstvenim službama, kao i o hitnim situacijama, poput nestanka struje ili vode. Time će se povećati transparentnost gradske administracije i smanjiti nesporazumi u komunikaciji.

4. Podrška za krizne situacije: Aplikacija će omogućiti brzo obavještavanje korisnika o izvanrednim situacijama, poput poplava, potresa, ili drugih hitnih događaja, čime će građani biti bolje pripremljeni na reakciju i suradnju u kriznim vremenima.

5. Funkcionalnost za pretragu i filtriranje prijava: Građani će moći pretraživati i filtrirati postojeće prijave i izvještaje o problemima, što će omogućiti praćenje statusa rješavanja i olakšati uključenost u njihove vlastite zajednice.

6. Povećanje kvalitete života u zajednici: Pružanje mogućnosti za aktivno sudjelovanje i unapređenje kvalitete života kroz forum za prijedloge pomoći će u kreiranju boljeg urbanog okruženja i većoj povezanosti između građana i lokalne vlasti.

## 1.2. Metodologija razvoja:

[Jan Pobi]

Projekt koristi fazni pristup razvoja softvera, s implementacijom **vodopadnog modela. Faze uključuju:
1. Planiranje: Definiranje plana izrade projekta.  
2. Analiza i specifikacija zahtjeva: Definiranje funkcionalnosti i korisničkih očekivanja.  
3. Dizajn sustava: Izrada arhitekture i korisničkog sučelja.  
4. Implementacija: Implementacija aplikacije korištenjem .NET Frameworka i SQL Servera.  
5. Testiranje: Provjera funkcionalnosti, sigurnosti i korisničkog iskustva.  
6. Isporuka i održavanje: Predaja naručitelju uz dokumentaciju i upute, te održavati aplikaciju.  

![RPPnacinRada](https://github.com/user-attachments/assets/82852ecb-090d-4e38-bb94-77b096bb475c)


## 1.3. Očekivani rezultati:

[Svi članovi tima]

- Intuitivna aplikacija za građane.  
- Učinkovit sustav za upravljanje gradskim problemima.  
- Povećano sudjelovanje građana u lokalnim aktivnostima.  

---

## 1.4. Definiran projektni tim

[Svi članovi tima]

| Ime i prezime  | E-mail adresa (FOI)  | JMBAG      | Github korisničko ime |
|-----------------|----------------------|------------|------------------------|
| Jan Pobi       | jpobi22@foi.hr       | 0016159939 | jpobi22foi            |
| Marin Grabovac | mgrabovac22@foi.hr   | 0016160653 | mgrabovac22           |
| Lucija Polak   | lpolak22@foi.hr      | 0016158151 | lpolak22              |

---

## 1.5. Terminški plan projekta

[Jan Pobi]

| Faza              | Aktivnosti                                          | Početak    | Završetak  |
|-------------------|----------------------------------------------------|------------|------------|
| Planiranje  | Razmatranje svih opcija pristupu projektu      | 10.10.2024 | 20.10.2024 |
| Analiza i specifikacija zahtjeva  | Sastanci s naručiteljem, prikupljanje podataka      | 20.10.2024 | 30.10.2024 |
| Dizajn sustava    | Priprema arhitekture i korisničkog sučelja          | 01.11.2024 | 31.11.2024 |
| Implementacija            | Implementacija aplikacije                          | 09.12.2024 | 20.01.2024 |
| Testiranje        | Funkcionalno i integracijsko testiranje             | 21.01.2024 | 25.01.2024 |
| Isporuka i održavanje         | Predaja aplikacije naručitelju i održavanje                     | 26.01.2024 | 26.01.2024(+ 6 mjeseci održavanja) |

---
### 1.5.1. Zaduženja članova tima s troškovima

[Lucija Polak]

| Oznaka | Naziv funkcionalnosti                            | Kratki opis                                                                                             | Odgovorni član tima | Cijena (€) | Aproksimativni sati rada |
|--------|--------------------------------------------------|-------------------------------------------------------------------------------------------------------|---------------------|------------|-------------------------|
| F01    | Autentikacija                                   | Za pristup aplikaciji potrebna je registracija nakon koje je korisniku omogućena autentikacija korisnika pomoću login funkcionalnosti. Korisnik se logira s podacima koje je unio prilikom registracije. | Lucija Polak        | 500        | 35                      |
| F02    | Podnošenje problema građana                     | Korisnici aplikacije imaju mogućnost prijave problema pomoću obrasca koje su pod nadležnosti Grada. Odnosno, na principu tzv. ticket sustava. U obrascu se odabiru kategorija problema i gradsko tijelo koje je zaduženo za taj problem. | Jan Pobi            | 1200       | 80                     |
| F03    | Forum za prijedloge                             | Sustav ima forum za građane gdje pod korisničkim imenima mogu stavljati ideje za poboljšanje gradskog života. Također, omogućeno je izražavanje podrške željenom prijedlogu za poboljšanje te komentiranje iste. | Lucija Polak        | 1000       | 60                      |
| F04    | Informacije o lokalnim zdravstvenim uslugama    | Sustav će omogućiti korisnicima pregled informacija o dežurnim ljekarnama i kontaktima dužnosnih liječnika te omogućiti unos, tj. mijenjanje informacija. | Jan Pobi            | 800        | 55                      |
| F05    | Prikaz često postavljanih pitanja (FAQ)         | Za dodatnu pomoć građanima oko problema, postojat će chatbot koji će biti spreman odgovoriti na određena pitanja.  | Marin Grabovac      | 700        | 60                      |
| F06    | Podrška za izvanredne situacije                 | Prikaz obavijesti oko izvanrednih i hitnih situacija poput nestanka struje ili vode te pomoć za ljude stradale potresom. Korisniku će biti omogućena pretplata na sekciju, a nove obavijesti će dolaziti na email, ukoliko su pretplaćeni na njega. | Lucija Polak        | 1000       | 85                      |
| F07    | Pretraga i filtriranje ticketa                  | Korisniku će biti omogućena pretraga i filtriranje prijavljenih problema (ticketa) vezanih za Gradsku upravu kako bi korisnik mogao odgovoriti na njega i pomoći u rješavanju problema. | Jan Pobi            | 900        | 45                    |
| F08    | Upravljanje gradskim tijelima i službenicima    | Korisnicima će biti omogućeno upravljanje gradskim tijelima i službenicima koji rade u njima. Ti službenici onda mogu odgovarati na tickete naslovljene na njihovo gradsko tijelo. | Marin Grabovac      | 800        | 75                      |
| F09    | Infrastruktura odvoza otpada                    | Sustav će imati mogućnost informiranja oko komunalnih usluga tako da se pritiskom na željenu lokaciju mogu vidjeti termini odvoza otpada.  | Marin Grabovac      | 600        | 45                     |

- Ukupno: 7500 €
- Ukupno sati rada: 540 sati


### 1.5.2. Ostala zaduženja

[Svi članovi tima]

| Član tima        | Faza            | Zaduženje                                                      |
|------------------|-----------------|---------------------------------------------------------------|
| Svi članovi    | Analiza         | Definiranje korisničkih zahtjeva i prikupljanje podataka.      |
| Svi članovi    | Dizajn          | Priprema korisničkog sučelja i funkcionalnosti. Arhitektura i struktura aplikacije.              |
| Svi članovi    | Testiranje      | Testiranje funkcionalnosti i korisničkog sučelja. Provjera sigurnosti i otpornosti aplikacije.            |

---

## 1.6. Proračun i budžet projekta

[Marin Grabovac]

| Kategorija         | Opis                                           | Troškovi  |
|--------------------|------------------------------------------------|-----------|
| Razvojni alati     | Licenca za Visual Studio, hosting baze podataka| 500 €     |
| Ljudski resursi    | Naknade za rad članova tima                    | 7500 €    |
| Infrastruktura     | Server za produkciju                           | 800 €     |
| Ukupno         | -                                              | 8800 €|

---

## 1.7. Ponuda naručitelju

[Lucija Polak]

[PDF ponude naručitelju](https://github.com/user-attachments/files/18042801/Ponuda_g2p.pdf)

### 1.7.1. Opis proizvoda:

[Jan Pobi]

Aplikacija za prijavu problema i informiranje nudi korisnicima jednostavan način za prijavu problema, pristup važnim obavijestima i sudjelovanje kroz forum za prijedloge. Glavne značajke uključuju:

1. Brza prijava problema putem obrasca  
   Korisnici mogu prijaviti probleme poput komunalnih nepravilnosti, oštećenja infrastrukture ili problema u lokalnim službama putem jednostavnog obrasca. Prijave se prate kao "ticketi" dok se ne riješe.

2. Informiranje o važnim obavijestima i infrastrukturnim pitanjima  
   Korisnici mogu primati obavijesti o infrastrukturnim radovima, nestancima struje, zastoju u prometu i drugim važnim situacijama. Mogu se pretplatiti na obavijesti putem emaila.

3. Sudjelovanje kroz forum za prijedloge  
   Građani mogu dijeliti prijedloge za poboljšanje gradskog života, glasovati za ideje drugih i komentirati prijedloge. Forum omogućuje prioritet za najpopularnije prijedloge.

4. Podrška za izvanredne situacije  
   Korisnici dobivaju obavijesti o hitnim situacijama (npr. potresi, poplave) i upute za ponašanje ili pomoć.

5. Pretraga i filtriranje prijavljenih problema  
   Aplikacija omogućava pretragu i filtriranje prijavljenih problema po tipu, statusu ili odgovornom tijelu, čime se olakšava praćenje i rješavanje problema.

Rokovi:
Završetak projekta: 03.02.2025.  

Financijska ponuda:
Ukupna cijena projekta iznosi 8800 €, uz uključenu tehničku podršku i održavanje tijekom 6 mjeseci nakon isporuke.

---













# 2. Softverska dokumentacija

## 2.1. Uvod

### 2.1.1. Svrha

[Lucija Polak]

<p align="justify">
Dokument je dizajniran kako bi pružio detaljan pregled svih korisničkih zahtjeva za sustav koji omogućuje građanima prijavu problema, prijedloge za poboljšanja, pristup informacijama o lokalnim zdravstvenim uslugama, hitnim obavijestima i interakciju s općinskim vlastima. Ovaj sustav će biti ključan za poboljšanje komunikacije između građana i municipalnih vlasti, omogućujući brže odgovaranje na prijave, bržu distribuciju važnih obavijesti i olakšan pristup uslugama. 
</p>

- Dokument se koristi za komunikaciju između svih sudionika u projektu, uključujući projektne menadžere, developere i korisnike koji će koristiti sustav.
- Korisnici ovog sustava uključuju građane, općinske vlasti, zdravstvene ustanove i druge relevantne dionike.

***

### 2.1.2. Opseg

[Jan Pobi]

<p align="justify">
Sustav omogućuje građanima prijavu problema u vezi infrastrukture, okoliša i drugih usluga, omogućuje korisnički doprinos u prijedlozima za poboljšanje gradskog upravljanja te daje pristup informacijama o lokalnim zdravstvenim i komunalnim uslugama te hitnim obavijestima. Građani mogu poslati prijavu problema i pritom dobiti rješenje odgovornog nadležnog tijela za napisanu prijavu. Uz to, komunikacija građana je omogućena korištenjem foruma gdje mogu izraziti svoje mišljenje daljnjim komentiranjem željene objave.
</p>

<p align="justify">
Glavne funkcionalnosti sustava uključuju:

1. Prijava problema: Građani mogu prijaviti različite vrste problema ili poslati prijedloge za poboljšanja.

2. Hitne obavijesti: Građani primaju obavijesti u slučaju hitnih situacija (npr. nesreće, vremenske nepogode) ako se pretplate na iste.

3. Zdravstvene usluge: Pružanje informacija o lokalnim zdravstvenim uslugama i pružateljima.

4. Forum za prijedloge: Građani mogu postaviti prijedloge za poboljšanja gradskih usluga.

5. Upravljanje ticketima: Gradske vlasti mogu pratiti i odgovarati na prijave građana.

***

### 2.1.3. Definicije, akronimi i skraćenice

[Marin Grabovac]

- Sustav za prijavu problema: Softversko rješenje koje omogućava građanima prijavu različitih problema te se koristi tzv. ticket sustav.
- Korisnik: Osoba koja se može prijaviti u aplikaciju.
- Građanin: Osoba koja koristi sustav za prijavu problema, prijedloge poboljšanja ili za praćenje hitnih obavijesti.
- Gradske vlasti: Osobe odgovorne za upravljanje sustavom, upravljanje prijavama i davanje odgovora na iste.
- Hitna obavijest: Obavijest koju građani primaju u hitnim situacijama koje zahtijevaju njihovu pozornost ili akciju.
- Ticket (prijava problema): Zaprimljeni zahtjev ili prijava koja čeka obradu, kao i njen trenutni status.
- FAQ (Frequently Asked Questions): Sekcija u sustavu koja pruža odgovore na često postavljana pitanja građana.

***

### 2.1.4. Reference

[Marin Grabovac]

- ISO/IEC 25010:2011 - Standard za kvalitetu softverskih proizvoda.
- GDPR (Opća uredba o zaštiti podataka) - Pravila o zaštiti osobnih podataka koja se primjenjuju na aplikaciju.
- Dokumentacija vezana uz Grad Varaždin: [Link na gradsku dokumentaciju](https://varazdin.hr/dokumenti/dokumenti-76/)
- Službene upute za hitne obavijesti: [Ministarstvo unutarnjih poslova](https://civilna-zastita.gov.hr/)

***

### 2.1.5. Struktura dokumenta

[Lucija Polak]

- U prvom poglavlju su definirani osnovni korisnički zahtjevi, svrha projekta i korisnici sustava.
- Drugo poglavlje opisuje funkcionalnosti sustava koje omogućuju građanima interakciju s gradskim vlastima.
- Treće poglavlje detaljno opisuje tehničke zahtjeve sustava, uključujući bazu podataka i infrastrukturu.
- Četvrto poglavlje obrađuje nefunkcionalne zahtjeve kao što su performanse, sigurnost i skalabilnost sustava.
- U petom poglavlju su uključeni prototipi sučelja i dizajnerske smjernice.
- U šestom poglavlju se nalaze dijagrami i opis strukture softvera.
- U sedmom poglavlju je zaključak.

***

## 2.2. Općeniti opis

[Lucija Polak]

Aplikacija ima 9 glavnih funkcionalnih zahtjeva koji zajednički čine cjelokupno programsko rješenje. Aplikaciji mogu pristupiti svi korisnici, međutim, postoji međusobna razlika u tipovima korisnika koji postoje. U našem rješenju postoje 3 različita korisnika, a to su: administrator, zaposlenik i građanin. Administratori mogu pristupiti svim dijelovima aplikacije, zaposlenici ne mogu pristupiti jedino objavljivanju izvanrednih situacija i upravljanju gradskim službenika i tijela, dok građani mogu pregledavati sadržaje, prijavljivati probleme, pisati prijedloge i komentare na forumu.

[Svi članovi tima]

![image](https://github.com/user-attachments/assets/e0060ae4-02e4-4e92-9b67-3fb09a0ad0f1)


### 2.2.2. Perspektiva proizvoda

[Svi članovi tima]

Sustav za prijavu problema i prijedloge poboljšanja će omogućiti građanima da izravno komuniciraju s općinskim vlastima, a vlastima će omogućiti lakšu i bržu reakciju na prijave i prijedloge. Sustav je zamišljen tako da bude jednostavan za korištenje, ali također pruža dovoljno funkcionalnosti za efikasno upravljanje i praćenje svih prijava.

***

### 2.2.3. Funkcije proizvoda

[Marin Grabovac]

1. Registracija korisnika: Građani se registriraju i autentificiraju putem emaila ili društvenih mreža.
2. Prijava problema: Građani mogu prijaviti razne vrste problema (npr. pothodnici, oštećenja infrastrukture).
3. Praćenje statusa prijave: Građani mogu pratiti status svojih prijava i primati odgovore od nadležnih vlasti.
4. Prijedlozi za poboljšanja: Građani mogu postaviti prijedloge za poboljšanje usluga u svojoj zajednici.
5. Hitne obavijesti: Građani primaju obavijesti u stvarnom vremenu o hitnim situacijama, poput poplava, potresa i drugih nepredvidivih događanja.
6. Forum i FAQ sekcija: Građani mogu postavljati pitanja, a općinske vlasti odgovaraju. Sekcija s najčešće postavljanim pitanjima je također uključena.

***

### 2.2.4. Karakteristike korisnika

[Jan Pobi]

- Građani: Nestrpljivi, zainteresirani za nove događaje u gradu i okolici, željni sudjelovanja po pitanjima grada, željni transparentnosti.
- Općinske vlasti: Žele pomoći gradu svojim vještinama, željni transparentnosti, odgovorni.
- Hitni službenici: Odgovorni, željni transparentnosti, pažljivi i educirani po pitanju sigurnosti, strpljivi, marljivi.

***

### 2.2.5. Ograničenja

[Lucija Polak]

- Sigurnost: Zbog osjetljivih podataka koji se prikupljaju, sustav mora biti zaštićen od neovlaštenog pristupa, ovo uključuje enkriptiranje i hashiranje podataka u User Settings. 
- Pristup podacima: Svi podaci građana, uključujući osobne informacije, moraju biti zaštićeni prema zakonodavstvu o zaštiti osobnih podataka te im mogu pristupati samo za to ovlaštene osobe.
- Ovisnost o infrastrukturi: Sustav mora biti u mogućnosti raditi bez prekida, što zahtijeva odgovarajuću infrastrukturu za hosting i održavanje.

***

### 2.2.6. Pretpostavke i ovisnosti

[Svi članovi tima]

- Sustav ovisi o stabilnom spajanju na internet za rad u stvarnom vremenu.
- Ovisnost o integraciji s lokalnim zdravstvenim uslugama i hitnim službama za pravovremene obavijesti.
- Sustav će zahtijevati integraciju s bazama podataka za pohranu i praćenje prijava i odgovora.
***

## 2.3. FUNKCIONALNI ZAHTJEVI  

| Identifikator | FZ-1 |
|--------------|------|
| Zahtjev  | Sustav će omogućiti korisnicima registraciju i prijavu kako bi osigurao pristup samo ovlaštenim korisnicima te omogućio specifične funkcionalnosti ovisno o ulozi korisnika. |
| Obrazloženje | Za pristup aplikaciji korisnici će morati proći kroz proces registracije, koji uključuje unos osobnih podataka. Nakon registracije korisnik će se moći prijaviti u aplikaciju. |
| Način provjere | Provjera će se izvršiti pokušajem prijave s valjanim korisničkim podacima. Ako su podaci ispravni, korisnik će biti preusmjeren u aplikaciju, inače će se prikazati obavijest o pogrešnoj prijavi. |
| Prioritet | 1 |
| Zaduženje | Lucija Polak |
| Izvor | Upit poslan od strane klijenta |
| Skica | [Prikaži skicu](#FZ1) |

***

| Identifikator | FZ-2 |
|--------------|------|
| Zahtjev  | Sustav će omogućiti korisnicima podnošenje problema putem obrasca koji uključuje kategoriju problema i nadležno gradsko tijelo. |
| Obrazloženje | Korisnici aplikacije moći će prijaviti probleme pomoću obrasca, što omogućava učinkovito praćenje i usmjeravanje problema prema nadležnim tijelima. |
| Način provjere | Provjera će se izvršiti testiranjem obrasca za prijavu problema. Podaci će biti unosi u sustav, a korisnik će biti obaviješten o uspješnoj prijavi. |
| Prioritet | 1 |
| Zaduženje | Jan Pobi |
| Izvor | Upit poslan od strane klijenta |
| Skica | [Prikaži skicu](#FZ2) |

***

| Identifikator | FZ-3 |
|--------------|------|
| Zahtjev  | Sustav će omogućiti građanima stvaranje prijedloga za poboljšanje gradskih usluga te komentiranje i izražavanje podrške na prijedloge drugih korisnika. |
| Obrazloženje | Ovaj forum bit će ključan za povećanje participacije građana u procesu donošenja odluka. Korisnici će moći predlagati poboljšanja i raspravljati o njima. |
| Način provjere | Provjera će se izvršiti unosom prijedloga na forum i provjerom odgovora drugih korisnika. |
| Prioritet | 2 |
| Zaduženje | Lucija Polak |
| Izvor | Upit poslan od strane klijenta |
| Skica | [Prikaži skicu](#FZ3) |

***

| Identifikator | FZ-4 |
|--------------|------|
| Zahtjev  | Sustav će omogućiti pregled i unos informacija o lokalnim zdravstvenim uslugama, uključujući dežurne ljekarne i kontakte liječnika. |
| Obrazloženje | Omogućit će korisnicima da lako pronađu ažurirane informacije o zdravstvenim uslugama u njihovoj blizini. |
| Način provjere | Provjera će biti izvršena testiranjem mogućnosti pregleda i unosa novih informacija vezanih uz zdravstvene usluge. |
| Prioritet | 3 |
| Zaduženje | Jan Pobi |
| Izvor | Upit poslan od strane klijenta |
| Skica | [Prikaži skicu](#FZ4) |

***

| Identifikator | FZ-5 |
|--------------|------|
| Zahtjev  | Sustav će omogućiti korisnicima pregled često postavljanih pitanja (FAQ) te pristup chatbotu za dodatnu podršku. |
| Obrazloženje | Aplikacija će sadržavati FAQ sekciju koja će građanima pružiti odgovore na najčešće postavljana pitanja uz dodatnu pomoć chatbota. |
| Način provjere | Provjera će biti izvršena interakcijom s FAQ sekcijom i testiranjem chatbot funkcionalnosti. |
| Prioritet | 2 |
| Zaduženje | Marin Grabovac |
| Izvor | Upit poslan od strane klijenta |
| Skica | [Prikaži skicu](#FZ5) |

***

| Identifikator | FZ-6 |
|--------------|------|
| Zahtjev  | Sustav će omogućiti korisnicima pretplatu na obavijesti o izvanrednim situacijama putem e-maila. |
| Obrazloženje | Korisnicima će biti omogućena pretplata na obavijesti vezane uz nestanke struje ili vode, potrese i druge hitne situacije. |
| Način provjere | Provjera će biti izvršena slanjem obavijesti na e-mail pretplaćenim korisnicima i verifikacijom ispravnosti obavijesti. |
| Prioritet | 1 |
| Zaduženje | Lucija Polak |
| Izvor | Upit poslan od strane klijenta |
| Skica | [Prikaži skicu](#FZ6) |

***

| Identifikator | FZ-7 |
|--------------|------|
| Zahtjev  | Sustav će omogućiti službenicima pretragu, filtriranje i odgovaranje na tickete za prijavu problema. |
| Obrazloženje | Službenici će moći pretraživati i filtrirati prijavljene tickete te odgovarati na njih kako bi pomogli u rješavanju problema. |
| Način provjere | Provjera će biti izvršena pretraživanjem ticketa i testiranjem mogućnosti odgovaranja na iste. |
| Prioritet | 1 |
| Zaduženje | Jan Pobi |
| Izvor | Upit poslan od strane klijenta |
| Skica | [Prikaži skicu](#FZ7) |

***

| Identifikator | FZ-8 |
|--------------|------|
| Zahtjev  | Sustav će omogućiti administratorima upravljanje gradskim tijelima i službenicima te dodjeljivanje ticketa službenicima. |
| Obrazloženje | Administrator će moći upravljati službenicima i dodjeljivati im tickete kako bi osigurao pravovremeno rješavanje problema. |
| Način provjere | Provjera će biti izvršena testiranjem funkcionalnosti dodavanja i upravljanja gradskim tijelima i službenicima, te mogućnosti odgovaranja na tickete. |
| Prioritet | 2 |
| Zaduženje | Marin Grabovac |
| Izvor | Upit poslan od strane klijenta |
| Skica | [Prikaži skicu](#FZ8) |

***

| Identifikator | FZ-9 |
|--------------|------|
| Zahtjev  | Sustav će omogućiti korisnicima pregled informacija o terminima odvoza otpada na odabranoj lokaciji. |
| Obrazloženje | Korisnici će moći vidjeti točan datum i vrijeme odvoza otpada za željenu lokaciju. |
| Način provjere | Provjera će biti izvršena testiranjem funkcionalnosti odvoza otpada i osiguravanjem da korisnici mogu vidjeti relevantne informacije. |
| Prioritet | 3 |
| Zaduženje | Marin Grabovac |
| Izvor | Upit poslan od strane klijenta |
| Skica | [Prikaži skicu](#FZ9) |


***

## 2.4. Nefunkcionalni zahtjevi

[Svi članovi tima]

### 2.4.1. Izgled softvera

- Korisničko sučelje: Sučelje mora biti intuitivno i lako za korištenje. Svi korisnici, bez obzira na razinu tehničke pismenosti, moraju biti u mogućnosti koristiti sustav bez poteškoća.

### 2.4.2. Performanse

- Brzina odgovora: Sustav mora biti u mogućnosti obraditi korisničke zahtjeve u roku od 3 sekunde.
- Visoka dostupnost: Sustav mora biti dostupan 99,9% vremena tijekom svakog mjeseca.
- Skalabilnost: Sustav mora biti sposoban podnijeti povećanje broja korisnika i prijava bez značajnog smanjenja performansi.

### 2.4.3. Sigurnost

- Autentifikacija i autorizacija: Sustav mora koristiti moderne metode autentifikacije kao što su OAuth ili JWT za sigurno prijavljivanje i pristup podacima.
- Šifriranje podataka: Osobni podaci građana i općinskih vlasti moraju biti šifrirani i zaštićeni prema zakonodavstvu o zaštiti podataka.
- Sigurnost aplikacije: Sustav mora biti zaštićen od sigurnosnih prijetnji, uključujući SQL injekcije, cross-site scripting (XSS) i cross-site request forgery (CSRF).

### 2.4.4. Upotrebljivost

- Jednostavnost: Sustav će koristiti sve demografske skupine koje žive u Varaždinu. Stoga, aplikacija mora biti jako jednostavna za korištenje.

### 2.4.5. Održavanje

- Redovite nadogradnje: Sustav mora biti redovito ažuriran kako bi bio siguran i u skladu sa zakonodavstvom.
- Podrška korisnicima: Postoji sustav za prijavu grešaka i tehničku podršku za korisnike.

***
## 2.5. Skice

[Svi članovi tima]

[Poveznica na figmu](https://www.figma.com/design/h1M08fz863BTnPaMA4k9tL/RPP-prva-provjera?node-id=0-1&t=5DW2HXZ6VbfSDVub-1)

### 2.5.1. Popis skica

***
<a id="FZ1"></a>
<img id="FZ1" src="https://github.com/user-attachments/assets/dd641169-ae08-40de-8f4d-5e331f36d6cb" alt="Prvi funkcionalni zahtjev">

![image](https://github.com/user-attachments/assets/5fb0afa5-1643-4b38-80a5-ae12e66454ee)

***

<a id="FZ2"></a>
<img id="FZ2" src="https://github.com/user-attachments/assets/2b90ca6a-c4fd-4959-985c-1f1daf87da4f" alt="Drugi funkcionalni zahtjev">

![image](https://github.com/user-attachments/assets/89fdbd98-989d-4cef-88de-e94b2a321118)

***

<a id="FZ3"></a>
<img id="FZ3" src="https://github.com/user-attachments/assets/d6f9b6ba-feaa-4b4a-9b55-80bee17cd5f9" alt="Treći funkcionalni zahtjev">

![image](https://github.com/user-attachments/assets/54545a61-c567-4469-9155-ee9cf34dea8b)

***

<a id="FZ4"></a>
<img id="FZ4" src="https://github.com/user-attachments/assets/3043830b-373d-49dd-863a-2624c2ada0d5" alt="Četvrti funkcionalni zahtjev">

![image](https://github.com/user-attachments/assets/298fc08e-a74a-4be8-92cb-69b51916b38b)

![image](https://github.com/user-attachments/assets/f585715a-5fed-4924-b588-948f7a5b0002)

![image](https://github.com/user-attachments/assets/4a4ebd10-42f7-4f88-bc83-67e54dd35af9)

***

<a id="FZ5"></a>
<img id="FZ5" src="https://github.com/user-attachments/assets/e4324d23-879c-4836-9ac4-802f36f482e4" alt="Peti funkcionalni zahtjev">

***

<a id="FZ6"></a>
<img id="FZ6" src="https://github.com/user-attachments/assets/cff75668-37ad-4b5a-a91f-2e7464a2e643" alt="Šesti funkcionalni zahtjev">

![image](https://github.com/user-attachments/assets/29d66343-e48b-4998-a78f-fcdc8414d588)

![image](https://github.com/user-attachments/assets/64b4a9a9-2f38-428b-8c67-10b70e15ce6a)

***

<a id="FZ7"></a>
<img id="FZ7" src="https://github.com/user-attachments/assets/38bc6bb7-bbc8-4db6-b337-a7951d289c75" alt="Sedmi funkcionalni zahtjev">

![image](https://github.com/user-attachments/assets/65c91d45-6a46-4e0c-a4a4-605a2bacc014)

***

<a id="FZ8"></a>
<img id="FZ8" src="https://github.com/user-attachments/assets/6c063131-bab7-4435-96bd-5983f495cee6" alt="Osmi funkcionalni zahtjev">

![image](https://github.com/user-attachments/assets/07ea4369-3790-4458-8bce-b5e62f12cddf)

![image](https://github.com/user-attachments/assets/00a6a7d9-d176-4554-be51-fe324c972b25)

![image](https://github.com/user-attachments/assets/ba6c093e-5b85-4543-8436-b9953cb827a7)

![image](https://github.com/user-attachments/assets/723aab32-16bb-4a22-ae4c-c0fa95588600)

***

<a id="FZ9"></a>
<img id="FZ9" src="https://github.com/user-attachments/assets/db46c927-8b5d-4e4e-80ac-e83c4e70121e" alt="Deveti funkcionalni zahtjev">

![image](https://github.com/user-attachments/assets/bf505baf-34d1-4b9e-8424-804f1e9bc72e)



***
## 2.6. Dizajn softverskog sustava

### 2.6.1. Podatkovni model cijelog sustava

[Svi članovi tima]

Podatkovni model cijele aplikacije se sastoji od 11 entiteta, a glavni entiteti koji se koriste u aplikativnom rješenju: "Varaždinski gradski info" su sljedeći: User, Problem, ProblemCategory, UserType, PeriodLocation, Institution, InstitutionType, Post, Comment Suggestion i Like.

Većina veza na dijagramu je 1:N (jedan naprema više) što je dobiveno većinskim korištenjem slabih entiteta radi uspostavljanja logičke cjeline aplikacije. 

![image](https://github.com/user-attachments/assets/63fb2cfd-8d78-40e6-91b7-ae30b787fd78)


Objašnjenja glavnih entiteta:

- Entitet User označava pojedinačnog korisnika, neovisno o njegovom tipu, postoji atribut IsSubscribed koji označava je li korisnik pretplaćen na forum za hitne obavijesti.
- Entitet Institution označava instituciju u kojoj radi korisnik koji je tipa "zaposlenik" te se tako mogu saznati informacije o npr. dežurnim ljekarnama.
- Institution označava vrstu instutucije kojoj pripada pojedini Institution.
- PeriodLocation označava adresu i vrijeme kada 1 institucija obavlja svoje dužnosti (tj. u našem slučaju je to odvoz otpada u različitim dijelovima grada Varaždina).
- UserType označava tip korisnika te se ovisno o tipu pijavljenog korisnika u aplikaciju mijenja i navigacija i mogućnosti korisnika. 
- Post je entitet koje mogu pregledavati svi korisnici, međutim, može ga dodavati isključivo tip korisnika s ulogom "Admin" ili "Employee" te ovaj entitet omogućava pisanje i slanje hitnih obavijesti na email adresu. Također, postoji atribut IsUrgent koji određuje je li obavijest hitna ili nije.
- Problem označava entitet koji pomaže u rješavanju problema građana i odgovaranje na tzv. tickete koje su građani poslali u vezi svoga problema.
- ProblemCategory označava tip kategorije kojemu pripada problem, tj. radi li se o komunalni, medicinski i sl.
- Suggestion je pojedini prijedlog na forumu građana te je povezan s entitetom Comment.
- Comment omogućava komentiranje pojedinog prijedloga za poboljšanje. 
- Like sprema podatak o tome koji korisnik je označio koji prijedlog sa oznakom "Sviđa mi se" kako bi dali podršku prijedlozima s kojima se slaže.
***

### 2.6.2. FZ-1 | Autentikacija

[Lucija Polak]

Funkcionalni zahtjev autentikacije podrazumijeva prijavu i registraciju korisnika. Ukoliko se korisnik prijavljuje, mora unijeti podatke u prijavni obrazac, tj. korisničko ime i lozinku. Zatim će sustav provjeriti postoji li takav korisnik Ako korisnik nema izrađen račun, najprije se mora registrirati te javiti poruku o grešci (ako je ima), ako je nema, onda se korisnika prebacuje u glavni dio aplikacije. 

![image](https://github.com/user-attachments/assets/b128d013-22be-441d-b9f6-4491ea84a426)


Naziv| **Opis
-|-
Naziv | Autentikacija
Kratki opis | Korisnik se prijavljuje u aplikaciju s korisničkim imenom i lozinkom, a ako nema već izrađen profil, onda se registrira s emailom, korisničkim imenom i lozinkom.
Sudionici | Korisnik
Okidač| Zaposlenik otvara aplikaciju.
Preduvjet za uspješno izvršenje | Zaposlenik ima instaliranu aplikaciju.
Stanje sustava nakon uspješnog izvršenja | Korisnik može vidjeti početnu stranicu.
Iznimke| Korisnik je prijavio nepostojećeg korisnika, korisnik je unio nepodržane znakove, korisnik je pokušao registrirati korisnika s već postojećim imenom.
Stanje sustava nakon pojave iznimke | Sustav javlja potrebu o promjeni.
Standardni proces za prijavu | (1) Korisnik unosi podatke za prijavu. <br> (2) Korisnik pritišće gumb za prijavu. <br> (3) Korisnik pristupa početnoj stranici aplikacije. <br> 
Standardni proces za registraciju | (1) Korisnik pristupa obrascu za registraciju. <br> (2) Korisnik unosi podatke za registraciju. <br> (3) Sustav preusmjerava korisnika na početnu stranicu.
Alternativni procesi | (1-3)  Kao i standardni procesi. <br> (4') Prikaži poruku o grešci.

![image](https://github.com/user-attachments/assets/5b59af1c-62bd-43a5-bc4e-18a2d4f7cb14)

![image](https://github.com/user-attachments/assets/c0b95b59-3117-4401-a108-15216d683950)

![image](https://github.com/user-attachments/assets/7c51fd1c-bfad-4535-a863-c426dce7e2e3)

***
### 2.6.3. FZ-2 | Podnošenje problema građana

[Jan Pobi]

Funkcionalni zahtjev za podnošenje problema građana podrazumijeva omogućavanje korisnicima da prijave probleme u gradu putem obrasca unutar aplikacije. Sustav koristi tzv. ticket sustav gdje korisnici odabiru kategoriju problema, unose potrebne informacije i šalju prijavu koja se zatim evidentira i prosljeđuje nadležnim tijelima.

![image](https://github.com/user-attachments/assets/dd5504f4-e70d-4bc3-926f-20e5fcb7ad31)


| Naziv               | Opis                                                                                      |
|--------------------------|-----------------------------------------------------------------------------------------------|
| Naziv               | Podnošenje problema građana                                                                  |
| Kratki opis          | Korisnici prijavljuju probleme putem obrasca unoseći potrebne informacije i odabirom kategorije problema. |
| Sudionici            | Građanin, Administrator                                                                  |
| Okidač              | Korisnik otvara obrazac za prijavu problema i unosi podatke |
| Preduvjet za uspješno izvršenje | Korisnik ima pristup aplikaciji i unosi potrebne informacije u obrascu |
| Stanje sustava nakon uspješnog izvršenja | Sustav evidentira prijavu problema u ticket sustav i obavještava nadležna tijela |
| Iznimke              | Korisnik unosi netočne podatke, ne odabere kategoriju problema ili pokušava poslati nepopunjeni obrazac |
| Stanje sustava nakon pojave iznimke | Sustav javlja korisniku poruku o grešci i omogućava ispravak unosa |
| Standardni proces za podnošenje problema | 1. Korisnik otvara obrazac za prijavu problema u aplikaciji. <br> 2. Korisnik odabire kategoriju problema iz dostupnih opcija. <br> 3. Korisnik unosi sve potrebne informacije, poput opisa problema i kontakt podataka. <br> 4. Korisnik potvrđuje unos klikom na gumb za podnošenje prijave. <br> 5. Sustav evidentira prijavu u ticket sustav i obavještava nadležna tijela. |

![image](https://github.com/user-attachments/assets/4dc71963-dda8-4795-99fb-1383473b7dd5)
![podnosenje slijedni](https://github.com/user-attachments/assets/73d78a86-cc8a-49f4-87d7-e7abbdc99018)



***
### 2.6.4. FZ-3 | Forum za prijedloge oko poboljšanja usluga Grada

[Lucija Polak]

Korisnik aplikacije može pristupiti forumu za prijedloge za poboljšanje usluga Grada. To uključuje i pregledavanje prethodnih objava koje se nalaze na forumu te, ako korisnik to želi, može napisati vlastiti prijedlog na forum. Kako bi se ustanovilo odobravaju li ostali građani (korisnici) prijedloge, omogućeno je komentiranje svakog prijedloga. Također, moguće je pružanje podrške željenim prijedlozima tako da se pritisne na gumb "Sviđa mi se". Na kraju, kada korisnik pohrani objavu ili komentar, dolazi do spremanja napisanog u bazu podataka.

<img width="502" alt="image" src="https://github.com/user-attachments/assets/eb1a4414-09a1-4d2f-8971-989f6e0e1b81" />

Naziv | Opis
-|-
Naziv | Forum za prijedloge oko poboljšanja usluga Grada
Kratki opis | Forum omogućuje korisnicima pregledavanje, pisanje, komentiranje i označavanje objava sa oznakom "Sviđa mi se".
Sudionici | Korisnik, sustav
Okidač | Korisnik je pristupio obrascu za forum.
Preduvjet za uspješno izvršenje | Korisnik je uspješno registriran i prijavljen u aplikaciju.
Stanje sustava nakon uspješnog izvršenja | Korisnik može vidjeti vlastitu objavu i/ili komentar.
Iznimke| Korisnik ne može izbrisati objave i komentare.
Stanje sustava nakon pojave iznimke | Sustav i dalje prikazuje stanje prije nastale želje za brisanjem.
Standardni proces | (1) Korisnik pristupa obrascu s forumom. <br> (2) Korisnik pregledava objave. <br> (3) Korisnik pritišće gumb za stvaranje nove objave. <br> (4) Korisnik ispunjava obrazac za novu objavu. <br> (5) Korisnik objavljuje prijedlog za poboljšanje. <br> (6) Korisnik vidi svoju objavu na forumu.
Alternativni procesi | (1-6)  Kao i standardni procesi. <br> (7') Korisnik ne može obrisati objavu.

![image](https://github.com/user-attachments/assets/b06c041b-8590-4b96-86a7-af9818798a1f)

![image](https://github.com/user-attachments/assets/ff6b6c42-4dcb-4a04-9dd6-8593b1856eb4)



### 2.6.5. FZ-4 | Informacije o lokalnim zdravstvenim uslugama

[Jan Pobi]

Funkcionalni zahtjev za informacije o lokalnim zdravstvenim uslugama podrazumijeva omogućavanje korisnicima da pregledaju podatke o dostupnim zdravstvenim ustanovama, uslugama, lokacijama, te kontakt informacije. Korisnik može pristupiti informacijama o lokalnim zdravstvenim centrima. Administrator ima mogućnosti dodavanja i ažuriranja podataka koji se tiću lokalnih ustanova i doktora

![use case informacije o lokalnim zdravstvenim uslugama](https://github.com/user-attachments/assets/52b5a722-bad3-4a47-9854-6fc8d779f6e2)


| Naziv               | Opis                                                                                      |
|--------------------------|-----------------------------------------------------------------------------------------------|
| Naziv               | Informacije o lokalnim zdravstvenim uslugama                                                |
| Kratki opis          | Korisnik može pregledati informacije o dostupnim zdravstvenim uslugama, kao što su ljekarne, klinike, bolnice, lokacije i kontakt podaci. |
| Sudionici            | Korisnik, Administrator                                                                              |
| Okidač              | Korisnik otvara modul za lokalne zdravstvene usluge                                      |
| Preduvjet za uspješno izvršenje | Korisnik je prijavljen  |
| Stanje sustava nakon uspješnog izvršenja | Sustav prikazuje korisniku sve informacije o lokalnim zdravstvenim uslugama. |
| Iznimke              | Korisnik nije prijavljen                                      |
| Stanje sustava nakon pojave iznimke | Sustav prikazuje obavijest kako se korisnik treba prijaviti |
Standardni proces | 1. Korisnik pristupa dijelu aplikacije za prikaz zdravstvenim uslugama. <br> 2. Sustav mu prikazuje dežurne ljekarne i doktore. <br> 3. Administrator odabire željenu ustanovu ili doktora. <br> 4. Administrator doda, makne ili ažurira podatke odabrane ustanove ili doktora


![image](https://github.com/user-attachments/assets/f2bf5a6d-0411-4181-9004-a0ae73b0bc3d)
![informacije slijedni](https://github.com/user-attachments/assets/2a30f8ff-cc05-4bbc-895d-ca8bdc01ce0c)



***
### 2.6.6. FZ-5 | Prikaz često postavljanih pitanja (FAQ)

[Marin Grabovac]

Funkcionalni zahtjev za prikaz često postavljanih pitanja (FAQ) omogućava građanima da dobiju brze odgovore na uobičajena pitanja putem FAQ sekcije. Ako odgovor nije dostupan, integrirani chatbot pruža dodatnu pomoć i odgovara na specifična korisnička pitanja.

![useCase](https://github.com/user-attachments/assets/1ee25253-840f-4a29-a5e8-740287aff999)

| Naziv                    | Opis                                                                                                                                                             |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Naziv                   | Prikaz često postavljanih pitanja (FAQ)                                                                                                                              |
| Kratki opis             | Korisnici mogu pregledati često postavljana pitanja unutar FAQ sekcije. Ako ne pronađu odgovor, mogu postaviti pitanje chatbotu koji generira odgovore.               |
| Sudionici               | Korisnik, Chatbot                                                                                                                                                     |
| Okidač                  | Korisnik otvara sekciju FAQ u aplikaciji.                                                                                                                             |
| Preduvjet za uspješno izvršenje | Aplikacija ima dostupnu FAQ bazu podataka, a chatbot API je funkcionalan.                                                                                          |
| Stanje sustava nakon uspješnog izvršenja | Korisnik dobiva odgovore na svoja pitanja putem FAQ sekcije ili chatbota.                                                                                          |
| Iznimke                 | Chatbot nije u mogućnosti generirati odgovor zbog tehničke greške, korisnik postavi pitanje koje nije pokriveno FAQ-om ni obukom chatbota.                             |
| Stanje sustava nakon pojave iznimke | Sustav obavještava korisnika o grešci i sugerira alternativne metode pomoći (npr. kontakt podrške).                                                                   |
| Standardni proces za pregled FAQ-a | (1) Korisnik otvara FAQ sekciju u aplikaciji. <br> (2) Korisnik pregledava liste često postavljanih pitanja. <br> (3) Korisnik klikom otvara odgovore na pitanja. |
| Standardni proces za interakciju s chatbotom | (1) Korisnik postavlja pitanje chatbotu putem unosa u aplikaciji. <br> (2) Chatbot prima pitanje i generira odgovor. <br> (3) Korisnik prima i čita generirani odgovor. |
| Alternativni procesi     | (1) Ako chatbot ne može generirati odgovor, korisniku se prikazuje sugestija da kontaktira podršku. <br> (2) Korisnik odustaje od postavljanja pitanja.                |

![aktivnosti](https://github.com/user-attachments/assets/bc3c7395-e18f-4b93-b461-8f49e6ff5d0d)




![klase](https://github.com/user-attachments/assets/7fc84df9-5ef9-4817-9712-0b65180a3d5f)


***
### 2.6.7. FZ-6 | Podrška za izvanredne situacije

[Lucija Polak]

Korisnik može pristupiti sekciji gdje se nalaze hitne i izvanredne obavijesti. Korisnik ima mogućnost pregledavanja objava koje se tamo nalaze. Također, korisnik se može pretplatiti na sekciju hitnih obavijesti te će mu to omogućiti ažurno praćenje novih obavijesti. Nove obavijesti kod pretplaćenih korisnika dolaze na email adresu, a korisnik kasnije, na istome mjestu može i otkazati pretplatu. Sustav će odraditi automatsko slanje obavijesti o novoj hitnoj situaciji na email.

![image](https://github.com/user-attachments/assets/fba2d191-b459-4a79-96d9-e94dbde3427e)

Naziv| **Opis
-|-
Naziv| Podrška za izvanredne situacije
Kratki opis | Korisnik može pregledavati i dobiti obavijesti o novim hitnim situacijama, ali i otkazati pretplatu, ako to želi. 
Sudionici| Korisnik, sustav
Okidač| Korisnik pristupa obrascu ili se pretplaćuje na sekciju izvanrednih obavijesti.
Preduvjet za uspješno izvršenje | Korisnik je prethodno registriran i prijavljen u aplikaciju. 
Stanje sustava nakon uspješnog izvršenja | Korisnik može vidjeti sekciju s izvanrednim obavijestima.
Iznimke | -
Stanje sustava nakon pojave iznimke | -
Standardni proces | (1) Korisnik pristupa obrascu za prikaz hitnih slučajeva. <br> (2) Korisnik pregledava hitne obavijesti. <br> (3) Korisnik se pretplaćuje na sekciju.
Alternativni procesi | -

![image](https://github.com/user-attachments/assets/00920bfd-c1c1-4053-8297-cbf730e0e4bc)

![image](https://github.com/user-attachments/assets/c27b977d-01f8-4db9-851c-1fa39c759175)


***
### 2.6.8. FZ-7 | Pretraga, filtriranje i odgovaranje na tickete za prijavu problema

[Jan Pobi]

Funkcionalni zahtjev omogućava korisnicima da pretražuju i filtriraju tickete u sustavu. Također omogućava administrativno odgovaranje na zaprimljene prijave.

![use case pretrage filtriranje ticketi](https://github.com/user-attachments/assets/40b83e24-d5de-48bc-908e-2f320dbe0cfc)


| Naziv               | Opis                                                                                      |
|--------------------------|-----------------------------------------------------------------------------------------------|
| Naziv               | Pretraga, filtriranje i odgovaranje na tickete za prijavu problema                          |
| Kratki opis          | Korisnik može pretraživati i filtrirati tickete za prijavu problema te administrativno odgovarati na njih. |
| Sudionici            | Korisnik, Administrator                                                                  |
| Okidač              | Korisnik ili administrator otvara obrazac za pretragu i filtriranje                        |
| Preduvjet za uspješno izvršenje | Sustav ima bazu s podatcima o prijavljenim ticketa |
| Stanje sustava nakon uspješnog izvršenja | Sustav prikazuje rezultate filtriranja, a administrator može odabrati i riješiti prijavljen problem |
| Iznimke              | Nema rezultata za unos, filtriranje je netočno                       |
| Stanje sustava nakon pojave iznimke | Sustav javlja korisniku odgovarajuće obavijesti i nudi mogućnost ponovnog unosa ili resetiranja filtra |
Standardni proces za pretragu i filtriranje | 1. Korisnik unosi parametre za pretragu u obrazac za filtriranje. <br> 2. Korisnik pokreće filtriranje.  <br> 3. Sustav prikazuje rezultate filtriranja u korisničkom sučelju.   <br> 
Standardni proces za odgovaranje na ticket | 1. Administrator izabere ticket. <br> 2. Administrator proučava korisnički opis problema. <br> 3. Administrator daje rješenje na korisnički problem te ažurira stanje ticketa.

![image](https://github.com/user-attachments/assets/6e7104fb-9415-43fa-84c1-090cdf6d4b7b)
![filtriranje activity dijagram](https://github.com/user-attachments/assets/beb4724c-1cc2-4cdd-9730-afa9cf699936)


***
### 2.6.9. FZ-8 | Upravljanje gradskim tijelima i službenicima

[Marin Grabovac]

Funkcionalni zahtjev za upravljanje gradskim tijelima i službenicima omogućava administratorima da dodaju, uređuju ili brišu gradska tijela te upravljaju službenicima koji su dio tih tijela. Službenici imaju mogućnost odgovaranja na tickete koji su naslovljeni na njihova gradska tijela.

![useCase](https://github.com/user-attachments/assets/d4fd608d-ecb9-44e6-8e78-36440f9396cd)

| Naziv                    | Opis                                                                                                                                                           |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Naziv                   | Upravljanje gradskim tijelima i službenicima                                                                                                                       |
| Kratki opis             | Administrator može dodavati, uređivati i brisati gradska tijela, te dodavati, uređivati i brisati službenike unutar tih tijela. Službenici mogu odgovarati na tickete. |
| Sudionici               | Administrator, Službenik                                                                                                                                           |
| Okidač                  | Administrator pristupa funkcionalnosti upravljanja gradskim tijelima i službenicima.                                                                               |
| Preduvjet za uspješno izvršenje | Administrator ima pristup aplikaciji i funkcijama upravljanja, a baza podataka je dostupna.                                                                                   |
| Stanje sustava nakon uspješnog izvršenja | Dodano, uređeno ili izbrisano gradsko tijelo ili službenik; službenici mogu odgovarati na dodijeljene tickete.                                                          |
| Iznimke                 | Administrator unosi neispravne podatke, pokuša izbrisati gradsko tijelo koje ima povezane tickete ili službenike, ili pokuša ukloniti aktivnog službenika.          |
| Stanje sustava nakon pojave iznimke | Sustav prikazuje poruku o grešci i ne izvršava traženu radnju.                                                                                              |
| Standardni proces za upravljanje gradskim tijelima | (1) Administrator pristupa modulu za gradska tijela. <br> (2) Administrator može dodati novo gradsko tijelo s potrebnim podacima. <br> (3) Administrator može uređivati ili brisati postojeće gradsko tijelo. |
| Standardni proces za upravljanje službenicima | (1) Administrator pristupa modulu za službenike. <br> (2) Administrator dodaje novog službenika i povezuje ga s gradskim tijelom. <br> (3) Administrator može uređivati ili brisati postojeće službenike. |
| Alternativni procesi     | (1) Ako je povezano tijelo ili službenik uklonjen, sustav prikazuje poruku da nije moguće dovršiti radnju.|
  

![slijeda](https://github.com/user-attachments/assets/1e592e28-3a22-4232-b2b6-f5def205b7bf)


![image](https://github.com/user-attachments/assets/eaccb4ec-7621-461d-8265-82f4f8376dd5)


***
### 2.6.10. FZ-9 | Infrastruktura odvoza otpada

[Marin Grabovac]

Funkcionalni zahtjev za infrastrukturu odvoza otpada omogućava korisnicima pregled informacija o terminima odvoza otpada pritiskom na željenu lokaciju na interaktivnoj mapi unutar aplikacije.


![useCase](https://github.com/user-attachments/assets/c3728578-6e77-46a3-bdd6-5fdacd8b0ddf)

| Naziv                    | Opis                                                                                                                                                           |
|------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Naziv                   | Infrastruktura odvoza otpada                                                                                                                                        |
| Kratki opis             | Korisnik može pregledati termine odvoza otpada pritiskom na određenu lokaciju na interaktivnoj mapi unutar aplikacije.                                              |
| Sudionici               | Korisnik                                                                                                                                                           |
| Okidač                  | Korisnik otvara stranicu s interaktivnom mapom.                                                                                                                    |
| Preduvjet za uspješno izvršenje | Korisnik ima pristup aplikaciji i interaktivnoj mapi s učitanim podacima o terminima odvoza otpada.                                                                               |
| Stanje sustava nakon uspješnog izvršenja | Prikaz termina odvoza otpada za odabranu lokaciju.                                                                                                          |
| Iznimke                 | Lokacija nije prepoznata ili nema dostupnih podataka o odvozu otpada za odabrano područje.                                                                          |
| Stanje sustava nakon pojave iznimke | Sustav javlja poruku da podaci za odabranu lokaciju nisu dostupni.                                                                                          |
| Standardni proces       | (1) Korisnik otvara stranicu s mapom. <br> (2) Korisnik pritišće željenu lokaciju na mapi. <br> (3) Sustav prikazuje termine odvoza otpada za odabranu lokaciju.      |
| Alternativni procesi     | (1) Ako nema dostupnih podataka za odabranu lokaciju, sustav prikazuje obavijest o nedostupnosti.                                                                  |

  
 

![slijeda](https://github.com/user-attachments/assets/e3fb3063-40df-4c6c-8db3-1569ba7004f4)



![image](https://github.com/user-attachments/assets/07015d29-e07e-4c24-b684-e851a24c7573)


### 2.6.11. Sveukupna struktura softvera

[Svi članovi tima]

![WhatsApp Image 2024-12-07 at 23 18 02](https://github.com/user-attachments/assets/ca6ab13c-7126-442d-9733-cde4340a0a70)



***
## 2.7. Zaključak

[Svi članovi tima]

Ovaj dokument pruža detaljan uvid u funkcionalne i nefunkcionalne zahtjeve za sustav prijave problema i prijedloga. Projekt će pomoći u poboljšanju komunikacije između građana i općinskih vlasti, omogućujući brže odgovaranje na prijave i prijedloge te pružanje važnih informacija o zdravstvenim uslugama i hitnim situacijama.
