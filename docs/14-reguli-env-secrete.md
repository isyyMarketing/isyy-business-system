# Reguli pentru .env și secrete

Acest document explică regulile pentru fișiere `.env`, chei API, parole, tokenuri și date personale.

Scopul este să eviți expunerea accidentală a informațiilor sensibile.

## Ce este un fișier .env

Fișierul `.env` conține variabile locale pentru proiect.

Exemple:

```text
DATABASE_URL=
API_KEY=
APP_ENV=development
```

Acest fișier poate conține valori reale și secrete. Din acest motiv, nu se pune pe GitHub.

## Ce este .env.example

Fișierul `.env.example` arată ce variabile sunt necesare, dar fără valori reale.

Exemplu:

```text
API_KEY=valoare_exemplu_fara_cheie_reala
```

`.env.example` poate fi pus pe GitHub pentru documentare.

## Ce NU se pune niciodată pe GitHub

Nu se pun pe GitHub:

- fișiere `.env` cu valori reale;
- parole;
- chei API;
- tokenuri;
- date personale ale clienților;
- date de plată;
- exporturi private;
- contracte sau facturi sensibile.

## Reguli pentru API keys, parole și tokenuri

- Nu se scriu direct în cod.
- Nu se pun în documentație publică.
- Nu se trimit către AI.
- Nu se folosesc aceleași chei pentru test și producție dacă se poate evita.
- Se schimbă dacă există suspiciune de expunere.

## Dacă o cheie API este expusă accidental

Pași recomandați:

1. Oprește folosirea cheii expuse.
2. Invalidează sau șterge cheia din platforma respectivă.
3. Generează o cheie nouă.
4. Verifică unde a fost expusă.
5. Elimină cheia din fișierele afectate.
6. Notează incidentul și măsura luată.

Nu presupune că o cheie expusă este încă sigură.

## Password manager

Se recomandă folosirea unui password manager pentru:

- parole;
- chei API;
- tokenuri;
- note securizate;
- acces la conturi importante.

Parolele nu trebuie ținute în fișiere text simple.

## Date personale și GDPR

Reguli simple:

- colectează doar datele necesare;
- nu păstra date fără motiv;
- nu publica date personale în GitHub;
- folosește date fictive în exemple;
- limitează accesul la datele clienților;
- șterge datele care nu mai sunt necesare.

Dacă un proiect începe să colecteze date reale de clienți, regulile de confidențialitate trebuie clarificate înainte de lansare.
