# Workflow Codex

Acest document explică modul oficial de lucru cu Codex în VS Code în cadrul ISYY Business System v1.0.

Codex este programatorul principal, dar lucrează cel mai bine când primește instrucțiuni clare.

## Rolul Codex

Codex în VS Code este folosit pentru:

- scriere de cod;
- modificarea fișierelor;
- completarea documentației;
- implementarea specificațiilor;
- verificarea structurii proiectului;
- rularea comenzilor locale necesare.

Codex execută. Nu decide singur direcția business-ului.

## Codex nu primește cereri vagi

Cereri de evitat:

- "Fă ceva bun aici."
- "Construiește o aplicație completă."
- "Optimizează tot."
- "Repară proiectul."

Aceste cereri sunt prea largi și pot produce haos.

## Codex primește specificații clare

O cerere bună pentru Codex include:

- modul de lucru;
- fișierele vizate;
- ce trebuie schimbat;
- ce nu trebuie schimbat;
- limba de lucru;
- criterii de acceptare;
- restricții clare.

Exemplu:

```text
MOD EXECUȚIE.
Completează fișierul docs/05-standarde-cod.md.
Scrie în română.
Nu crea fișiere noi.
Nu modifica alte fișiere.
După modificare, spune ce ai schimbat.
```

## Implementare pe etape

Codex trebuie să implementeze pe etape.

Pentru taskuri mari:

1. citește contextul;
2. identifică fișierele relevante;
3. face modificările necesare;
4. verifică rezultatul;
5. raportează clar ce a schimbat.

Nu se schimbă mai multe direcții simultan fără motiv clar.

## Verificare după modificări

După fiecare modificare importantă se verifică `git status`.

Scopul este să fie clar:

- ce fișiere au fost modificate;
- dacă apar fișiere noi accidental;
- dacă există modificări neintenționate;
- dacă repository-ul rămâne într-o stare controlată.

## Review ChatGPT

ChatGPT face review logic și arhitectural.

Review-ul verifică:

- dacă soluția respectă cerința;
- dacă arhitectura rămâne coerentă;
- dacă există riscuri ascunse;
- dacă documentația este clară;
- dacă implementarea este potrivită pentru obiectiv.

Codex implementează. ChatGPT verifică și clarifică. Isac aprobă.

## Reguli importante

- Codex nu modifică `.git`.
- Codex nu face commit sau push fără cerere explicită.
- Codex nu redenumește fișiere fără instrucțiune clară.
- Codex nu schimbă arhitectura stabilită fără confirmare.
- Codex lucrează în fișierele cerute.
- Codex se oprește și cere clarificare când cerința este riscant de ambiguă.
