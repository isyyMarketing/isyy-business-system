# Template specificatie pentru Codex

Acest template se foloseste cand Codex trebuie sa implementeze ceva clar in repository.

## Obiectiv

Descrie exact ce trebuie facut.

Exemplu:

```text
Completeaza documentatia pentru workflow-ul GitHub.
```

## Context

Explica pe scurt de ce este necesara modificarea.

## Fisiere permise

Codex are voie sa modifice doar:

- `cale/catre/fisier.md`
- `cale/catre/alt-fisier.js`

## Fisiere interzise

Codex nu are voie sa modifice:

- `.git/`
- fisiere de configurare sensibile;
- fisiere care nu au legatura cu taskul.

## Ce are voie sa modifice

- continutul cerut explicit;
- sectiunile mentionate;
- exemplele necesare;
- documentatia relevanta.

## Ce nu are voie sa modifice

- arhitectura stabilita;
- numele fisierelor;
- structura folderelor;
- reguli deja aprobate;
- fisiere care nu au fost mentionate.

## Pasi de implementare

1. Citeste contextul existent.
2. Identifica fisierele permise.
3. Fa modificarile cerute.
4. Pastreaza stilul proiectului.
5. Verifica rezultatul.
6. Raporteaza ce ai modificat.

## Criterii de acceptare

Taskul este acceptat daca:

- cerinta este implementata complet;
- nu au fost modificate fisiere interzise;
- documentatia este clara;
- nu au fost create fisiere necerute;
- rezultatul poate fi verificat usor.

## Verificare finala

Inainte de oprire, Codex trebuie sa verifice:

- ce fisiere au fost modificate;
- daca exista fisiere noi necerute;
- daca structura proiectului a ramas neschimbata;
- daca cerinta initiala a fost respectata.
