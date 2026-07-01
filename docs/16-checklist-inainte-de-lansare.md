# Checklist înainte de lansare

Acest checklist se folosește înainte de lansarea unui MVP sau proiect.

Scopul este să eviți lansările grăbite și riscante.

## 1. Verificare MVP

Verifică:

- problema principală este rezolvată;
- funcțiile minime există;
- funcțiile excluse din MVP sunt documentate;
- utilizatorul poate înțelege valoarea;
- MVP-ul poate fi testat de un client real.

## 2. Verificare bug-uri critice

Nu lansa dacă există bug-uri care:

- blochează funcția principală;
- pierd date;
- expun informații sensibile;
- împiedică utilizatorul să finalizeze acțiunea principală.

Bug-urile mici pot fi notate pentru etapa următoare.

## 3. Verificare date sensibile

Verifică:

- nu există `.env` public;
- nu există chei API în cod;
- nu există parole în documentație;
- nu există date reale de clienți în repository;
- `.env.example` nu conține valori reale.

## 4. Verificare documentație

Documentația minimă trebuie să explice:

- ce face proiectul;
- cum se pornește;
- ce este inclus în MVP;
- ce nu este inclus;
- ce riscuri sunt cunoscute.

## 5. Verificare backup

Înainte de lansare:

- codul trebuie salvat în GitHub;
- documentele importante trebuie păstrate într-un loc clar;
- fișierele sensibile trebuie protejate;
- trebuie să existe o metodă de recuperare.

## 6. Verificare costuri

Clarifică:

- ce costuri lunare există;
- ce servicii sunt plătite;
- ce costuri apar dacă proiectul crește;
- dacă lansarea poate fi susținută financiar.

## 7. Verificare mod de monetizare

Verifică:

- cum va plăti clientul;
- ce primește clientul;
- dacă oferta este clară;
- dacă Stripe sau PayPal sunt necesare acum sau după validare;
- dacă există o cale realistă de monetizare.

Nu se garantează venituri. Se testează interesul real.

## 8. Decizie finală Isac

Isac decide dacă proiectul:

- se lansează;
- se mai testează;
- se modifică;
- se oprește.

Decizia finală trebuie să fie clară și documentată.
