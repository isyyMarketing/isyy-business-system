# Branch-uri și Pull Request

Acest document explică modul simplu de lucru cu branch-uri și Pull Request în ISYY Business System.

## Când se lucrează direct pe main

Se poate lucra direct pe `main` când:

- proiectul este la început;
- lucrează o singură persoană;
- modificarea este mică;
- riscul este redus;
- nu există deploy automat conectat la `main`.

Chiar și pe `main`, înainte de commit se verifică fișierele modificate.

## Când se creează branch separat

Se creează branch separat când:

- modificarea este mare;
- există risc de stricare a proiectului;
- se lucrează la o funcție nouă;
- se lucrează cu altă persoană;
- schimbarea trebuie revizuită înainte de merge.

## Format simplu pentru branch-uri

Format recomandat:

```text
tip/nume-scurt
```

Exemple:

```text
docs/structura-proiect
feat/formular-contact
fix/validare-email
chore/configurare-env
```

Tipuri utile:

- `docs` pentru documentație;
- `feat` pentru funcții noi;
- `fix` pentru corecturi;
- `chore` pentru configurări și întreținere.

## Când are sens Pull Request

Pull Request are sens când:

- vrei review înainte de merge;
- modificarea este importantă;
- există colaboratori;
- vrei să documentezi discuția;
- proiectul este aproape de lansare.

Pentru modificări foarte mici într-un proiect personal, Pull Request poate fi opțional.

## Cum se face review înainte de merge

Înainte de merge se verifică:

- cerința a fost respectată;
- nu există fișiere modificate accidental;
- nu există secrete;
- testarea minimă a fost făcută;
- documentația este actualizată;
- Codex nu a schimbat arhitectura fără aprobare;
- Isac aprobă rezultatul, dacă schimbarea afectează direcția proiectului.

## Regulă practică

Dacă modificarea poate afecta lansarea, banii, datele clientului sau arhitectura, folosește branch separat și review înainte de merge.
