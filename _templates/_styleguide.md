# Styleguide HbM RPG v3

## Konwencje formatowania

- **Język:** wyłącznie polski, styl encyklopedyczny/in-world, z sekcjami dla MG.
- **Format:** pliki .md zgodne z Obsidian, sekcje oddzielone nagłówkami (##, ###).
- **Frontmatter YAML:**
  - tags: [temat, typ, ...]
  - aliases: []
  - status: draft/complete
- **Daty:** DD.MM.RRRR (EP X), np. 16.04.2023 (EP 0)
- **Linki wewnętrzne:** standardowe linki Markdown, np. `[Nazwa Strony](sciezka/do/Nazwa%20Strony.md)`, ze ścieżką względną liczoną od bieżącego pliku (nie wikilinki `[[...]]`) - dla zgodności z Obsidianem, zwykłymi czytnikami Markdown i mniej zaawansowanymi AI. Ustawienie Obsidiana "Use [[Wikilinks]]" jest wyłączone (`.obsidian/app.json`: `useMarkdownLinks: true`), więc nowe linki tworzone w Obsidianie też będą w tym formacie.
- **Osadzanie obrazków:** `<img src="sciezka" width="200" alt="...">` (dla obrazków z rozmiarem) lub `![alt](sciezka)` (bez rozmiaru) zamiast `![[...]]`.
- **Callouty dla MG:**
  > [!gm]+ Tylko dla MG
  Tajne informacje, spoilery, sekrety, mechanika, plot-twisty.
- **GM callout** powinien być zawsze na końcu pliku lub sekcji, do której się odnosi.
- **Podział treści:**
  - concepts/ - krótkie definicje, encyklopedyczne
  - lore/ - dłuższe eseje, narracja, głębia świata
  - discipline/, races/, organizations/ - pełne szablony
- **Przykład calloutu:**

> [!gm]+ Tylko dla MG
> Diana Koniecpolska jest Posłańcem Nil, ale gracze mogą odkryć to dopiero po serii snów i wizji.

## Admonition (Obsidian)
- Używaj składni `> [!gm]+` dla sekcji tylko dla MG.
- Możesz zagnieżdżać callouty, jeśli wymaga tego struktura tajemnic.

## Inne
- **EP** = Era Przebudzenia, licz od 16.04.2023 (EP 0).
- **Wersjonowanie:** status w YAML, zmiany odnotowywane w commitach.
- **Przykładowy frontmatter:**

---
tags: [race, lore]
aliases: [Człowiek]
status: draft
---

## FAQ
- Jeśli nie wiesz, gdzie coś umieścić - stwórz stub i oznacz status: draft.
- Jeśli masz wątpliwości co do kanonu - sprawdź plan lore lub zapytaj głównego redaktora - człowieka.
