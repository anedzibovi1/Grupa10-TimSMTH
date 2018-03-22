﻿# Grupa10 ~ Team - something

\
![gif](https://media.giphy.com/media/l41YzQX6Zf3YgT4Ri/giphy.gif)

# [Tačka 1]

### Tema: Vicinor
\
![vicinor-logo](https://user-images.githubusercontent.com/37186899/37522627-c259062e-2924-11e8-9f06-1c6eb6394c94.png)

### Članovi tima:
- Dženana Šabović
- Haris Mašović 
- Samra Salihić

## Opis teme

"Basically tinder for restaurants" - Mašović Haris

Vicinor je aplikacija koja omogućava korisniku (user-u) da na jednostavan način pronađe mjesto/objekat koje servira/prodaje hranu kao npr. fast food/restorani itd. pri čemu korisnik bira objekat koji mu se sviđa iz liste ponuđenih objekata.

Često korisnik dolazi u situaciju gdje ne može odlučiti gdje jesti, te pomoću ove aplikacije ima izbor restorana/fast food-ova (generalno food places) u određenom radijusu u odnosu na trenutnu lokaciju. Korisnik može izabrati određeni restoran i/ili dodati u listu svojih omiljenih restorana ponuđene restorane od strane aplikacije ili restorane u odnosu na trenutnu lokaciju definisane određenim radijusom kojeg je korisnik zadao. 

Nakon toga aplikacija daje upustva kako doći na određenu lokaciju koju je korisnik izabrao. Iz napisanih karakteristika, aplikacija omogućava uklanjane dvojbe korisnika vezane za izbor restorana/mjesta gdje može da jede što predstavlja glavni motiv za potražnju aplikacije.

Inače naziv vicinor (vicino - ital. znači nearby/close - blizu, a r kao restorani).

## Procesi

#### Registracija korisnika / izbor izmedju guest i aktivnog korisnika aplikacije /
Korisnik ima mogućnost da izabere tip user-a odnosno da bude obični guest user i da ima osnovne funkcionalnosti aplikacije ili da bude aktivni user, da ima dodatne funkcionalnosti pored osnovnih. 
Korisnik se registruje sa osnovnim podacima o sebi, a to su:
* Ime
* Prezime
* E-mail
* Password
* Kontakt telefon

#### Sakupljanje informacija o određenim restoranima preko web servisa
Ovaj proces mora biti automatizovan. Kada korisnik zatraži spisak restorana/mjesta za jesti, proces mora prvo provjeriti da li je lokacija ispravno uspostavljena i nakon toga mora pokupiti sva mjesta za jesti koja se nalaze u radijusu koji je definisan unaprijed od strane korisnika (možda korisnik ne želi previše hodati/putovati, samim tim ima mogućnost da bira radjius).

#### Prikaz svih restorana dobivenih iz pretrage
Ovaj proces također mora biti automatizovan. Kada korisnik pokrene pretragu mora dobiti određene restorane unutar tog radijusa u odnosu na poziciju gdje se nalazi. Naravno spisak restorana će biti organizovan u listu, pri čemu korisnik može sačuvati neke restorane kao željene odnosno može ih sačuvati u /wish list/-i. Element liste će sadržiti detaljne informacije o restoranu/mjestu za jesti.

#### Uputa za restoran
Nakon što korisnik izabere (ako izabere, jer ne mora nužno izabrati nijedan od ponuđenih restorana, ili se može desiti da nema restorana u određenom radijusu), korisnik dobija upute preko google maps, odnosno dobija najkraći put koji mora preći da bi došao do odabranog restorana.

#### Proces recenzije korisnika
Korisinik (mislimo na registrovanog korisnika jer on jedini ima ovu mogućnost) će moći davati recenzije i rating-e za određene restorane. 

#### Poziv restorana
Korisnik ima mogućnost poziva svakog restorana (obični telefonski poziv) iz liste preporučenih. Jednostavni klik na tu opciju mu to i omogućava.

#### Generisanje preporučenih restorana
Aplikacija ima za mogućnost da korisniku ponudi spisak restorana (generalno) koji su po nekom algoritmu generisani (npr. top tier restorani, restorani sa najboljom ocjenom, najviše posjećeni restorani pomoću naše aplikacije itd).

#### Prikaz statistike administratoru / za preporučene restorane /
Administratori će imati prikaz nekih od osnovih statistika pomoću čega će se moći generisati razni načini za prikaz preporučenih restorana za korisnike aplikacije.

## Funkcionalnosti

* Mogućnost registracije korisnika
* Mogućnost uređivanje korisničkog profila
* Mogućnost pravljenja liste želja za registrovane korisnike (lista omiljenih mjesta za jelo)
* Mogućnost ostavljanja feedbacka u vidu ratinga i komantara (neobavezno)
* Mogućnost korištenja aplikacije neregistrovanim korisnicima
* Mogućnost izbora/promijene radijusa pretrage restorana u odnosu na lokaciju korisnika
* Mogućnost izbora restorana
* Mogućnost pregleda historije obiđenih restorana
* Mogućnost dobijanja uputa do odabranog restorana
* Mogućnost poziva restorana/objekta
* Mogućnost izbora iz skupa restorana preporučenih od strane aplikacije
* Mogućnost poznavanja korisnikove lokacije pomoću GPS uređaja

## Akteri

- Korisnik usluga Klijent ima mogućnost da se registruje na sistem i da tako koristi aplikaciju, ali također moguće je pristupati aplikaciji i kao "Gost user".
- Neregistrovani korisnik (guest user)
- Registrovani korisnik
- Administrator sistema - Ima zadatak da nadgleda sistem


### [Tačka 2/3] su urađene pod:
- https://github.com/ooad-2017-2018/Grupa10-TimSMTH/tree/master/UseCaseIScenarij

### [Tačka 4] je urađena pod:
- https://github.com/ooad-2017-2018/Grupa10-TimSMTH/tree/master/Projekat/Vicinor
