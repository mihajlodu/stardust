# stardust
dandelion wine

[ Opis resenja zadatka + APPLET.HTML]

================================================================================================================================

1. Svi termini iz glossary.json fajla su poredjani po abecednom redu i njihovi nazivi su prikazani u h2 tagu.
2. Ispod svakog pojma ispisana je definicija.
3. Linkovani su svi srodni termini ispod odgovarajucih definicija i linkovi vode na ofgovarajuce lokacije.
4. Na vrhu stranice nalazi se widget koji se sastoji od dropdown menu-a. Widget se koristi za fitriranje na sledeci nacin:
obelezavanjem samo jednog poja iskljucuje se jedan label. 
5. Aplikacija koristi lokalno loadovanje .json fajla, sto obezbedjuje laksu adaptaciju strane na dodavanje novih pojmova u .json fajl.
6. Zbog loseg formatiranja glossary.json fajla (pogresna sintaksa, jedna greska), napravljen je novi fajl koji se zove data.json, koji je loadovan kao varijabla pomocu XMLHTTPRequest() API.
7. Za formiranje tabele koristio sam cetiri petlje koje ispisuju podatke u obliku tabele, zbog preglednosti i lakseg struktuiranja koda.
8. Za ispisivanje alfabetnih linkova koristio sam JavaScript document.write(ALPHABET()).

Mihajlo Dumitraskovic
