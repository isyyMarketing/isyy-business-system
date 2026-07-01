# Securitate

Acest document defineste regulile de securitate pentru ISYY Business System v1.1.

Scopul este protejarea conturilor, datelor, fisierelor si viitoarelor proiecte.

## Parole

- Parolele nu se scriu in cod.
- Parolele nu se pun in documentatia din GitHub.
- Parolele nu se trimit in mesaje catre AI.
- Pentru conturi importante se folosesc parole puternice si unice.
- Unde este posibil, se activeaza autentificarea in doi pasi.

## Chei API

Cheile API sunt informatii sensibile.

Reguli:

- nu se pun in repository;
- nu se includ in exemple reale;
- nu se trimit catre servicii necunoscute;
- se rotesc daca exista suspiciune ca au fost expuse;
- se folosesc chei diferite pentru test si productie, cand este posibil.

## Date clienti

Datele clientilor trebuie tratate cu atentie.

Nu se pun pe GitHub:

- nume complete fara motiv clar;
- emailuri reale;
- numere de telefon;
- adrese;
- date de plata;
- conversatii private;
- fisiere primite de la clienti.

Pentru exemple se folosesc date fictive.

## Fisiere sensibile

Fisierele sensibile includ:

- `.env`;
- fisiere cu parole;
- exporturi de date;
- contracte;
- facturi;
- documente de identitate;
- fisiere private ale clientilor.

Acestea nu se comit in GitHub.

## Ce nu se pune pe GitHub

Nu se pune pe GitHub:

- parole;
- chei API;
- tokenuri;
- date reale de clienti;
- fisiere `.env`;
- documente legale private;
- fisiere financiare sensibile;
- backup-uri brute cu date private.

## Reguli pentru .env

Fisierul `.env` este folosit pentru configurari locale si secrete.

Reguli:

- `.env` nu se comite;
- se poate crea un exemplu sigur, de tip `.env.example`;
- valorile reale raman doar local sau in platforma de deploy;
- daca o cheie ajunge public, se invalideaza si se genereaza alta.

## Backup

Backup-ul trebuie sa fie simplu si controlat.

Recomandari:

- codul se salveaza in GitHub;
- documentele strategice se pot pastra in Obsidian;
- fisierele de business se pot pastra in Google Drive;
- fisierele sensibile se organizeaza separat;
- backup-ul se verifica periodic.

## Acces pentru viitoare echipa

Daca apar colaboratori:

- fiecare persoana primeste acces doar la ce are nevoie;
- accesul se retrage cand colaborarea se opreste;
- nu se partajeaza parole personale;
- se folosesc roluri si permisiuni unde este posibil;
- deciziile de acces se documenteaza.
