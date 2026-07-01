# Structura proiect real

ISYY Business System folosește `projects/_template/` ca bază pentru orice proiect nou.

Scopul este să nu reinventăm structura de fiecare dată.

## Structura standard

```text
projects/_template/
├── README.md
├── 01-idee.md
├── 02-analiza-business.md
├── 03-mvp.md
├── 04-specificatie-codex.md
├── 05-taskuri.md
├── 06-decizii.md
├── 07-lansare.md
└── 08-feedback.md
```

## Rolul fișierelor

- `README.md` oferă imaginea de ansamblu a proiectului.
- `01-idee.md` clarifică ideea inițială.
- `02-analiza-business.md` analizează piața, clientul, costurile și modelul de venit.
- `03-mvp.md` definește prima versiune minimă.
- `04-specificatie-codex.md` pregătește cererea tehnică pentru Codex.
- `05-taskuri.md` urmărește lucrul curent.
- `06-decizii.md` păstrează deciziile importante.
- `07-lansare.md` pregătește lansarea.
- `08-feedback.md` colectează feedback și decizii după testare.

## Cum copiezi template-ul

Pentru un proiect nou:

1. Copiază folderul `projects/_template/`.
2. Redenumește copia cu numele proiectului.
3. Completează `README.md`.
4. Completează `01-idee.md`.
5. Fă analiza în `02-analiza-business.md`.
6. Definește MVP-ul în `03-mvp.md`.
7. Scrie specificația pentru Codex în `04-specificatie-codex.md`.

Exemplu de nume:

```text
projects/client-intake/
```

## Reguli

- Nu începe implementarea fără analiză și MVP clar.
- Nu modifica `projects/_template/` pentru un proiect concret.
- Fiecare proiect trebuie să aibă propriul folder.
- Deciziile importante se notează în `06-decizii.md`.
- Feedbackul se notează în `08-feedback.md`.

## Când este proiectul pregătit pentru implementare

Un proiect este pregătit pentru implementare când:

- ideea este clară;
- clientul țintă este definit;
- MVP-ul este limitat;
- riscurile principale sunt notate;
- specificația Codex este completă.
