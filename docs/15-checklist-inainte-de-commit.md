# Checklist înainte de commit

Acest checklist se folosește înainte de orice commit important.

Scopul este să salvezi în Git doar modificări clare, curate și sigure.

## 1. Verifică git status

Rulează:

```text
git status
```

Verifică:

- ce fișiere sunt modificate;
- ce fișiere sunt noi;
- dacă apare ceva neașteptat.

## 2. Verifică git diff --stat

Rulează:

```text
git diff --stat
```

Scopul este să vezi rapid mărimea modificărilor.

Dacă apar fișiere pe care nu voiai să le modifici, oprește-te și verifică.

## 3. Verifică fișierele modificate

Înainte de commit, verifică fiecare fișier modificat.

Întreabă:

- are legătură cu taskul?
- este modificarea intenționată?
- este documentația clară?
- a fost schimbat ceva accidental?

## 4. Verifică să nu existe .env sau parole

Nu face commit dacă apar:

- `.env`;
- parole;
- chei API;
- tokenuri;
- date personale;
- fișiere private.

`.env.example` este permis doar dacă nu conține valori reale.

## 5. Verifică documentația

Dacă ai schimbat comportamentul proiectului, verifică dacă documentația trebuie actualizată.

Documentația trebuie să explice clar:

- ce s-a schimbat;
- cum se folosește;
- ce reguli trebuie respectate.

## 6. Verifică testarea minimă

Testarea minimă depinde de proiect.

Exemple:

- aplicația pornește;
- funcția modificată merge;
- nu apar erori evidente;
- documentele se deschid corect;
- linkurile interne sunt clare.

## 7. Scrie commit message clar

Mesajul de commit trebuie să fie scurt și explicit.

Format recomandat:

```text
tip: descriere scurtă
```

Exemple:

```text
docs: adaugă checklist înainte de commit
feat: adaugă primul formular MVP
fix: corectează validarea câmpului email
```

Commit-ul trebuie să descrie ce s-a schimbat, nu să fie vag.
