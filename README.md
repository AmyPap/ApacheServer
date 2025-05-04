# Uppgift 1 – Apache HTTP Server

## Syfte

Att självständigt kunna installera och konfigurera serverprogramvara med hjälp av dokumentation på internet.

## Översikt

Uppgiften består av två delar:

1. Grunddel (obligatorisk) – krävs för att klara kursen.
2. Bonusdel (frivillig) – ger **2 extra poäng** på tentan och de två första omtentorna

I båda delarna ska du aktivt söka information och dokumentera alla steg.

Dokumentationen ska skrivas i Markdown och lämnas in i filen `installation.md` enligt följande krav:

- Använd tydliga rubriker.
- Håll styckena korta (ingen ”wall of text”).
- Använd "inline code" och "code blocks" för kommandon och konfiguration.
- Använd endast Markdown – inga HTML-taggar.

## Grunddel – Apache HTTP Server *(obligatorisk)*

Din Ubuntu-server ska leverera en personlig webbsida via HTTP på port 80.

### Beskrivning

- Installera Apache HTTP Server på Ubuntu Server.
- Använd den bifogade filen `index.html` som startsida.

  - Ersätt `Username` med ditt GitHub-användarnamn.

- Dokumentera arbetet i `installation.md`:

  - Beskriv varje steg du utför. Skriv en kort text följt av kommandon.
  - Beskriv viktiga loggfiler, var de finns och varför de är relevanta.

- Skärmdump: `apache.png`:

  - Visa webbläsaren med startsidan.
  - Länka bilden i `installation.md` så att den visas i Preview.

## Bonusdel – WordPress *(frivillig, 2 poäng)*

Din Ubuntu-server ska köra Wordpress via HTTP på port 80.

- Installera och konfigurera MySQL eller MariaDB för WordPress.
- Installera och konfigurera WordPress så att det visas via Apache på port 80.

  - Startsidan från grunddelen ersätts; skärmdumpen från grunddelen räcker som bevis.

- Skapa ett inlägg i WordPress som innehåller ditt GitHub-användarnamn.
- Dokumentera arbetet under rubriken ”WordPress” sist i `installation.md`.
- Skärmdump: `wordpress.png`:

  - Visa webbläsaren med WordPress och ditt inlägg med ditt GitHub-användarnamn.
  - Länka bilden i `installation.md`.

## Filer att lämna in

Du ska lämna in tre filer:

- `installation.md` – dokumentation
- `apache.png` – skärmdump för grunddelen
- `wordpress.png` – skärmdump för Wordpress om du gör bonusdelen

### Inlämningsinstruktioner

Läs dokumentet [Studentguide till GitHub Classroom][1].

[1]: https://github.com/nackc8/kursmaterial/blob/main/shared/studentguide-till-github-classroom.md
