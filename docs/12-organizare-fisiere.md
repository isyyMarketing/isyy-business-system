# Organizare fisiere

Acest document explica unde se pastreaza diferitele tipuri de fisiere in ISYY Business System v1.1.

Scopul este evitarea haosului si gasirea rapida a informatiilor.

## Ce se tine in GitHub

GitHub este pentru:

- cod;
- documentatie tehnica;
- template-uri;
- scripturi;
- configurari de proiect care nu sunt secrete;
- istoric al modificarilor.

Nu se pun in GitHub fisiere sensibile sau date private ale clientilor.

## Ce se tine in Obsidian

Obsidian este pentru gandire strategica.

Se pot tine aici:

- idei;
- planuri;
- analize;
- decizii in lucru;
- note personale;
- directii de business;
- lectii invatate.

Obsidian nu inlocuieste documentatia oficiala din repository cand o regula trebuie folosita de proiect.

## Ce se tine in Google Drive

Google Drive este pentru fisiere de business si colaborare.

Se pot tine aici:

- documente pentru clienti;
- prezentari;
- exporturi;
- materiale vizuale;
- contracte;
- facturi;
- fisiere partajate.

Fisierele sensibile trebuie organizate cu atentie si partajate doar cu persoanele necesare.

## Ce se tine local

Local se pot tine:

- fisiere temporare;
- fisiere `.env`;
- teste locale;
- exporturi care nu trebuie publicate;
- copii de lucru.

Fisierele locale importante trebuie incluse intr-un sistem de backup.

## Reguli pentru nume de fisiere

Numele fisierelor trebuie sa fie clare si simple.

Recomandari:

- foloseste litere mici;
- foloseste `-` intre cuvinte;
- evita spatiile;
- evita nume vagi precum `nou.md` sau `test-final-final.md`;
- include scopul fisierului in nume.

Exemple bune:

```text
mvp-validation-template.md
github-workflow.md
client-intake-form.md
```

## Reguli pentru backup

Backup-ul trebuie gandit in functie de tipul fisierului.

- codul se salveaza in GitHub;
- documentele strategice se pot sincroniza prin Obsidian;
- fisierele de business se pastreaza in Google Drive;
- secretele nu se pun in repository;
- fisierele importante se verifica periodic.

Regula simpla: daca un fisier este important, trebuie sa existe o metoda clara de recuperare.
