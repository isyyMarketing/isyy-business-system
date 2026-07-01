# Exemplu specificație pentru Codex

Acesta este un exemplu completat pentru `templates/codex-spec-template.md`.

## Obiectiv

Creează o structură simplă de documentație pentru un proiect fictiv numit `client-intake`.

## Context

Proiectul are nevoie de documente inițiale pentru idee, MVP și decizii. Scopul este doar organizarea documentației, nu implementarea unei aplicații.

## Fișiere permise

Codex are voie să creeze sau să modifice doar fișiere `.md` în:

- `projects/client-intake/`

## Fișiere interzise

Codex nu are voie să modifice:

- `.git/`;
- `.env`;
- `.gitignore`;
- fișiere din `docs/`;
- fișiere din `templates/`;
- fișiere de cod.

## Ce are voie să modifice

- documentație Markdown pentru proiect;
- titluri și secțiuni clare;
- checklist-uri simple;
- note despre MVP.

## Ce nu are voie să modifice

- arhitectura ISYY Business System;
- fișierele oficiale v1.0, v1.1 sau v1.2;
- configurații Git;
- cod sursă.

## Pași de implementare

1. Creează folderul `projects/client-intake/` dacă nu există.
2. Creează un fișier `README.md` pentru proiect.
3. Creează un fișier `mvp.md`.
4. Creează un fișier `decizii.md`.
5. Scrie conținut scurt, clar și practic.
6. Verifică lista de fișiere modificate.

## Criterii de acceptare

Taskul este acceptat dacă:

- există documentația minimă pentru proiect;
- sunt modificate doar fișiere `.md`;
- nu este folosit internetul;
- nu se rulează `git add`, `git commit` sau `git push`;
- nu sunt atinse fișiere sensibile;
- conținutul este scris în română.

## Verificare finală

Codex trebuie să raporteze:

- ce fișiere a creat;
- ce fișiere a modificat;
- dacă au apărut fișiere necerute;
- dacă există pași recomandați pentru continuare.
