# agent-www-seo

Agent ekspert od budowy stron internetowych dla firm: strona na GitHub Pages + SEO (techniczne i lokalne).

## Co tu jest

| Plik / folder | Do czego służy |
|---|---|
| `AGENTS.md` | Prompt systemowy agenta. Claude Code i inne narzędzia czytają go automatycznie. |
| `public/` | Szablon strony startowej (HTML, `robots.txt`). To jest publikowane na GitHub Pages. |
| `content/` | Miejsce na teksty i dane firmy (brief, słowa kluczowe, mapa strony). |
| `.github/workflows/pages.yml` | Automatyczna publikacja po każdej zmianie w gałęzi `main`. |

## Jak zacząć (krok po kroku)

1. Otwórz to repo w Claude Code (lub w projekcie Claude z wgranym `AGENTS.md`).
2. Napisz `/brief` i odpowiedz na pytania o firmę.
3. Agent przeprowadzi Cię dalej: słowa kluczowe, mapa strony, kod, treści.
4. Napisz `/publikacja`, żeby wdrożyć stronę.

## Włączenie GitHub Pages (jednorazowo)

1. W repo wejdź w **Settings → Pages**.
2. W polu **Source** wybierz **GitHub Actions**.
3. Po następnym wgraniu zmian strona pojawi się pod adresem `https://plabiak81.github.io/agent-www-seo/`.

## Zasady

- `main` = wersja produkcyjna. Zmiany przez osobne gałęzie i Pull Request.
- Żadnych haseł ani kluczy w repo.
