# Standarde de cod

Acest document definește standardele de cod pentru proiectele din ISYY Business System v1.0.

Scopul este ca orice proiect să fie clar, ușor de întreținut și pregătit pentru extindere.

## Cod curat

Codul trebuie să fie:

- simplu;
- lizibil;
- organizat;
- ușor de testat;
- ușor de modificat.

Codul bun trebuie să poată fi înțeles și după câteva săptămâni, nu doar în momentul în care este scris.

## Modularitate

Funcționalitățile trebuie împărțite în module clare.

Un modul trebuie să aibă un rol bine definit.

Se evită fișierele care fac prea multe lucruri simultan.

## Nume clare

Numele trebuie să explice scopul.

Se folosesc nume clare pentru:

- fișiere;
- foldere;
- funcții;
- variabile;
- clase;
- componente.

Un nume bun reduce nevoia de explicații suplimentare.

## Fișiere mici

Fișierele trebuie să rămână cât mai mici și concentrate.

Dacă un fișier devine greu de urmărit, se împarte în părți mai clare.

Nu se creează complexitate inutilă, dar nici nu se păstrează totul într-un singur fișier mare.

## Comentarii utile

Comentariile trebuie să explice lucrurile care nu sunt evidente.

Se evită comentariile inutile, de tipul celor care repetă exact ce face codul.

Comentariile sunt utile când explică:

- o decizie;
- o limitare;
- o regulă de business;
- un comportament mai greu de înțeles.

## Fără cod inutil

Nu se păstrează cod mort, duplicat sau nefolosit.

Se evită:

- funcții nefolosite;
- importuri inutile;
- variante vechi comentate;
- bucăți de cod păstrate "poate cândva".

Codul inutil produce confuzie.

## Fără dependențe inutile

Nu se adaugă librării fără motiv clar.

Înainte de o dependență nouă se verifică:

- ce problemă rezolvă;
- dacă este necesară;
- dacă există o soluție simplă deja disponibilă;
- dacă va fi ușor de întreținut.

Fiecare dependență adaugă responsabilitate.

## Testare înainte de commit

Înainte de commit se verifică:

- că proiectul pornește;
- că funcționalitatea modificată merge;
- că nu apar erori evidente;
- că documentația relevantă este actualizată;
- că nu există modificări accidentale.

Commit-ul trebuie să salveze o stare coerentă a proiectului.
