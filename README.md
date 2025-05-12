# Napredni Web - LV7

Aplikacija omogućuje upravljanje projektima s podrškom za registraciju korisnika, dodjeljivanje uloga i suradnju unutar timova. 
Aplikacija je nastavak prethodne vježbe. Proširuje funkcionalnosti sustava za upravljanje projektnim radom.

## Tehnologije
- Node.js
- Express.js
- MongoDB + Mongoose
- EJS (za prikaz korisničkog sučelja)
- Express-session (upravljanje sesijama)
- Bcrypt (hashiranje lozinki)


- Svaki korisnik se može sam registrirati i prijaviti u aplikaciju.
- Svaki projekt sadrži:
  - Naziv
  - Opis
  - Cijenu
  - Obavljene poslove
  - Datum početka i završetka
  - Status arhiviranosti
- Na projekt se mogu dodati članovi tima (od već registriranih korisnika).
- Svaki projekt može imati jednog voditelja

- Zbog prevelike količine file-ova izostavljen je node_modules folder.
