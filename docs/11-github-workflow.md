# Workflow GitHub

Acest document defineste regulile simple pentru lucrul cu GitHub in ISYY Business System v1.1.

GitHub este sistemul oficial de versionare pentru cod si documentatie tehnica.

## Branch main

Branch-ul `main` este ramura principala a proiectului.

Reguli:

- `main` trebuie sa ramana stabil;
- modificarile importante se verifica inainte de commit;
- nu se imping schimbari neclare;
- orice modificare trebuie sa aiba scop clar.

## Cand se face commit

Commit-ul se face cand exista o schimbare coerenta.

Exemple:

- a fost adaugat un document complet;
- a fost implementata o functie mica;
- a fost corectata o problema clara;
- a fost actualizata documentatia pentru o decizie.

Nu se face commit pentru modificari incomplete fara motiv.

## Format commit message

Mesajul de commit trebuie sa fie scurt si clar.

Format recomandat:

```text
tip: descriere scurta
```

Exemple:

```text
docs: adauga reguli de securitate
feat: adauga formular MVP
fix: corecteaza validarea emailului
chore: actualizeaza configurarea proiectului
```

## Cand se face push

Push-ul se face dupa commit, cand schimbarea este pregatita pentru salvare remote.

Inainte de push:

- se verifica `git status`;
- se verifica ce fisiere au fost modificate;
- se ruleaza testele relevante, daca exista;
- se confirma ca nu exista secrete sau fisiere sensibile.

## Ce se verifica inainte de commit

Checklist minim:

- modificarea respecta cerinta;
- nu exista fisiere necerute;
- nu exista parole sau chei API;
- documentatia relevanta este actualizata;
- proiectul porneste, daca este aplicatie;
- testele relevante trec, daca exista.

## Cum se lucreaza cu Codex

Codex implementeaza pe baza unei specificatii clare.

O cerere buna catre Codex trebuie sa spuna:

- ce trebuie facut;
- ce fisiere sunt permise;
- ce fisiere sunt interzise;
- ce nu trebuie schimbat;
- cum se verifica rezultatul.

Codex nu trebuie sa faca `git add`, `git commit` sau `git push` fara cerere explicita.

## Cum se face review

Review-ul verifica:

- daca cerinta a fost respectata;
- daca arhitectura ramane coerenta;
- daca exista riscuri;
- daca documentatia este clara;
- daca nu au fost introduse secrete;
- daca schimbarea este usor de intretinut.

ChatGPT poate face review logic si arhitectural.

Isac aproba rezultatul final.
