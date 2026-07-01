# ISYY Business System v1.0

ISYY Business System este sistemul oficial de organizare, dezvoltare și lansare pentru proiectele din ISYY Ecosystem v1.0.

Sistemul este construit pentru a ajuta la dezvoltarea unui business online scalabil, clar și etapizat, folosind colaborarea dintre Isac, ChatGPT și Codex în VS Code.

## Scop

Scopul ISYY Business System este să ofere o metodă simplă și repetabilă pentru:

- analizarea ideilor de business;
- transformarea ideilor în proiecte concrete;
- construirea de MVP-uri;
- documentarea deciziilor importante;
- dezvoltarea de servicii, produse digitale, automatizări și agenți AI;
- lansarea și scalarea proiectelor validate.

Sistemul nu garantează rezultate financiare. El oferă structură, disciplină și un mod clar de lucru.

## Roluri oficiale

### ChatGPT

ChatGPT are rolul de:

- arhitect principal al sistemului;
- analist de business;
- reviewer tehnic;
- mentor;
- creator de documentație și specificații.

ChatGPT ajută la clarificarea ideilor, analizarea riscurilor, definirea arhitecturii și verificarea logică a soluțiilor.

### Codex în VS Code

Codex în VS Code are rolul de:

- programator principal;
- implementator al specificațiilor primite;
- modificator al fișierelor proiectului;
- executant tehnic care respectă structura și standardele definite.

Codex nu trebuie să primească cereri vagi. El lucrează cel mai bine cu cerințe clare, etapizate și validate.

### Isac

Isac are rolul de:

- antreprenor;
- Product Owner;
- validator final;
- decident asupra direcției business-ului;
- tester și aprobator al rezultatelor.

Isac coordonează direcția, validează rezultatele și decide ce se lansează.

## Stack oficial

ISYY Ecosystem v1.0 include:

- ChatGPT Plus;
- Codex în VS Code;
- VS Code;
- Docker Desktop;
- GitHub;
- Obsidian;
- Node.js;
- Python;
- Canva;
- Figma;
- Gmail;
- Google Drive;
- Google Calendar;
- Stripe / PayPal după lansare.

## Structură folder

Structura inițială a repository-ului este:

```text
isyy-business-system/
├── agents/
├── docs/
├── projects/
├── scripts/
├── templates/
├── .gitignore
└── README.md
```

### Rolul folderelor

- `agents/` - spațiu pentru documentarea agenților AI și a rolurilor lor.
- `docs/` - documentația oficială a sistemului.
- `projects/` - spațiu pentru proiectele dezvoltate în cadrul sistemului.
- `scripts/` - spațiu pentru scripturi utile.
- `templates/` - spațiu pentru șabloane reutilizabile.

## Workflow de bază

Workflow-ul de bază este:

1. Idee.
2. Analiză.
3. Validare.
4. Arhitectură.
5. Specificație.
6. Implementare cu Codex.
7. Review cu ChatGPT.
8. Testare de către Isac.
9. Documentare.
10. Commit.
11. Push.
12. Lansare.
13. Automatizare.
14. Scalare.

Nicio implementare importantă nu începe fără arhitectură și specificație clară.

## Status v1.0 inițial

Statusul inițial al sistemului:

- repository creat;
- structura principală stabilită;
- documentația oficială v1.0 în curs de completare;
- rolurile principale definite;
- stack-ul oficial stabilit;
- workflow-ul de lucru definit;
- implementările concrete urmează după validarea specificațiilor.

## v1.1 — Șabloane și reguli practice

ISYY Business System v1.0 rămâne baza sistemului: viziune, roluri, principii, workflow și stack oficial.

ISYY Business System v1.1 adaugă instrumente practice pentru lucru zilnic:

- șabloane pentru cereri către Codex;
- șabloane pentru analiză de business;
- șabloane pentru decizii importante;
- șabloane pentru MVP și validare;
- reguli simple de securitate;
- workflow GitHub;
- reguli de organizare a fișierelor.

### Fișiere noi v1.1

- [Template specificație Codex](templates/codex-spec-template.md)
- [Template analiză idee de business](templates/business-idea-analysis-template.md)
- [Template decizie importantă](templates/decision-record-template.md)
- [Template MVP și validare](templates/mvp-validation-template.md)
- [Securitate](docs/10-securitate.md)
- [Workflow GitHub](docs/11-github-workflow.md)
- [Organizare fișiere](docs/12-organizare-fisiere.md)

### Configurare text

Fișierul `.gitattributes` normalizează fișierele text și setează fișierele Markdown la LF, pentru reducerea avertismentelor LF/CRLF pe Windows.

## v1.2 — Operaționalizare

ISYY Business System v1.2 ajută la pornirea primului proiect real.

Această etapă adaugă pași practici pentru:

- pornirea unui proiect nou;
- lucrul corect cu `.env` și secrete;
- verificarea înainte de commit;
- verificarea înainte de lansare;
- folosirea unui template de proiect nou;
- înțelegerea template-urilor prin exemple completate.

Regula oficială: documentația se scrie în limba română, cu diacritice corecte și encoding UTF-8.

### Documente noi v1.2

- [Cum pornești primul proiect](docs/13-cum-pornesti-primul-proiect.md)
- [Reguli pentru .env și secrete](docs/14-reguli-env-secrete.md)
- [Checklist înainte de commit](docs/15-checklist-inainte-de-commit.md)
- [Checklist înainte de lansare](docs/16-checklist-inainte-de-lansare.md)

### Template-uri și exemple noi v1.2

- [Template proiect nou](templates/new-project-template.md)
- [Exemplu specificație Codex](templates/codex-spec-example.md)
- [Exemplu analiză idee de business](templates/business-idea-analysis-example.md)
- [Exemplu MVP și validare](templates/mvp-validation-example.md)
- [Exemplu decizie importantă](templates/decision-record-example.md)

### Configurare secrete

- `.gitignore` exclude fișiere sensibile și directoare generate.
- `.env.example` arată variabile de exemplu fără valori reale.
