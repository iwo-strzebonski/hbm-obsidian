# 🎲 Homebrew Magic: RPG v3 - Content Creation Environment

Narzędzia do tworzenia i zarządzania treścią dla systemu TT-RPG **Homebrew Magic: Role Playing Game**.

Repozytorium pełni dwie role jednocześnie:

1. **Workspace dla GitHub Copilot** — narzędzia CLI, źródła książek z Google Drive, szablony.
2. **Vault dla Obsidian** — folder główny repo jest jednocześnie vaultem (`.obsidian/` w root). Foldery techniczne (`src/`, `_books/`, `data/`, `foundry-system/`, `.github/`) są wyłączone z indeksowania w `.obsidian/app.json` (`userIgnoreFilters`).

## 📁 Struktura Projektu

```
hbm-books/                         ← root = Obsidian vault
├── .obsidian/                     # konfiguracja Obsidiana
├── _books/                        # zsynchronizowane książki z Google Drive (read-only)
├── _drafts/                       # szkice WIP (Copilot pisze tutaj)
├── _templates/                    # szablony notatek Obsidiana (NPC, Lokacja, …)
├── _assets/                       # binarki/symlinki (gitignored, Nextcloud)
│
├── adventures/                    # przygody
├── classes/                       # klasy szkolne (Pi, Pd, Pa…)
├── concepts/                      # koncepty świata (Otchłań, Szkoły Magii…)
├── conflicts/                     # konflikty zbrojne
├── creatures/                     # stworzenia / potwory
├── disciplines/                   # dziedziny magii
├── items/                         # przedmioty magiczne
├── locations/                     # lokacje
├── lore/                          # lore tracking, opowiadania
├── npcs/                          # postacie niezależne
├── organizations/                 # organizacje
├── player-characters/             # postacie graczy
├── races/                         # rasy
├── revisions/                     # gotowe do skopiowania rewizje tekstu
├── rules/                         # zasady, mechaniki
├── spells/                        # czary
├── tabletop-cards/                # symlinki do kart (gitignored)
│
├── foundry-system/                # 🚧 custom system Foundry VTT (TODO)
├── src/                           # narzędzia CLI (Bun/Node)
│   ├── cli.js
│   ├── gdrive-client.js
│   ├── content-manager.js
│   └── templates/                 # szablony JS dla nowych treści
└── data/
    └── books-cache.json           # cache metadanych Google Drive
```

## 🚀 Szybki Start

### 1. Instalacja zależności

```bash
bun install
```

### 2. Autoryzacja Google Drive

```bash
bun run hbm gdrive:auth
```

Otwórz wyświetlony URL, zaloguj się do Google i skopiuj kod autoryzacyjny, następnie:

```bash
bun run hbm gdrive:auth <KOD>
```

### 3. Pobierz wszystkie książki

```bash
bun run hbm gdrive:sync
```

Książki zostaną zapisane w `_books/` jako pliki Markdown.

## 📚 Dostępne Komendy

### Google Drive

| Komenda | Opis |
|---------|------|
| `bun run hbm gdrive:auth` | Autoryzacja z Google Drive |
| `bun run hbm gdrive:list` | Lista wszystkich książek HbM na Drive |
| `bun run hbm gdrive:sync` | Pobierz wszystkie książki |
| `bun run hbm gdrive:get <książka>` | Pobierz konkretną książkę |

### Tworzenie Treści

| Komenda | Opis |
|---------|------|
| `bun run hbm new:spell` | Stwórz nowy czar |
| `bun run hbm new:creature` | Stwórz nowe stworzenie |
| `bun run hbm new:item` | Stwórz nowy przedmiot |
| `bun run hbm new:npc` | Stwórz nowego NPC |
| `bun run hbm new:location` | Stwórz nową lokację |

### Szkice i Rewizje

| Komenda | Opis |
|---------|------|
| `bun run hbm draft <książka> <sekcja>` | Nowy szkic |
| `bun run hbm revision <książka>` | Nowa rewizja (gotowa do copy-paste) |

### Przeglądanie i Wyszukiwanie

| Komenda | Opis |
|---------|------|
| `bun run hbm search <fraza>` | Szukaj we wszystkich książkach |
| `bun run hbm list <typ>` | Lista treści danego typu |
| `bun run hbm show <typ> <nazwa>` | Pokaż sformatowaną treść |

### Szablony

| Komenda | Opis |
|---------|------|
| `bun run hbm template:spell` | Pokaż strukturę szablonu czaru |
| `bun run hbm template:creature` | Pokaż strukturę szablonu stworzenia |
| `bun run hbm template:item` | Pokaż strukturę szablonu przedmiotu |
| `bun run hbm template:npc` | Pokaż strukturę szablonu NPC |
| `bun run hbm template:location` | Pokaż strukturę szablonu lokacji |

## 📖 Skróty Książek

| Skrót | Pełna Nazwa |
|-------|-------------|
| `podrecznik` | HbM: RPG v3 - Podręcznik Gry |
| `magia` | HbM: RPG v3 - Księga Magii |
| `przewodnik` | HbM: RPG v3 - Przewodnik Ludzkości po Magicznym Świecie |
| `bestiariusz` | HbM: RPG v3 - Bestiariusz |
| `arcanum` | HbM: RPG v3 - Arcanum Sanguinis |
| `kult` | HbM: RPG v3 - Chwała Szkarłatnemu Kultowi |
| `klatwa` | HbM: RPG v3 - Klątwa Otchłani |

## 📝 Workflow: Tworzenie Rewizji Tekstu

1. **Pobierz książki z Google Drive:**
   ```bash
   bun run hbm gdrive:sync
   ```

2. **Znajdź sekcję do edycji:**
   ```bash
   bun run hbm search "szukana fraza"
   ```

3. **Stwórz rewizję:**
   ```bash
   bun run hbm revision magia
   ```
   - Podaj tytuł sekcji
   - Wklej oryginalny tekst
   - Wklej poprawiony tekst
   - Dodaj notatki (opcjonalnie)

4. **Gotowa rewizja** zostanie zapisana w `content/revisions/` z:
   - Metadanymi (książka, data, sekcja)
   - Tekstem gotowym do skopiowania (w bloku kodu)
   - Oryginalnym tekstem (do porównania)

## 🎯 Workflow: Tworzenie Nowej Treści

### Nowy Czar

```bash
bun run hbm new:spell
# Wpisz nazwę czaru

# Edytuj plik JSON w content/spells/
# Następnie wyświetl sformatowany:
bun run hbm show spells "nazwa czaru"
```

### Nowe Stworzenie

```bash
bun run hbm new:creature
# Wpisz nazwę stworzenia

# Edytuj plik JSON w content/creatures/
# Wyświetl sformatowany blok statystyk:
bun run hbm show creatures "nazwa"
```

## 🔧 Integracja z VS Code

W VS Code możesz otworzyć terminal i używać komend `bun run hbm`. 

### Copilot Chat

Używając GitHub Copilot, możesz:
- Wyszukiwać w pobranych książkach
- Tworzyć nową treść na podstawie szablonów
- Generować rewizje tekstu gotowe do skopiowania

Przykład:
> "Stwórz nowego potwora typu nieumarły o nazwie Widmowy Strażnik, CR 5, z atakiem wyssania życia"

## 📄 Format Plików

### Treść (JSON)

```json
{
  "name": "Ognista Kula",
  "type": "spell",
  "school": "Ewokacja",
  "circle": 3,
  "description": "..."
}
```

### Szkice i Rewizje (Markdown)

```markdown
---
book: "HbM: RPG v3 - Księga Magii"
section: "Nowy Czar"
created: "2026-01-11T..."
status: draft
---

# Nowy Czar

...treść...
```

## 🔄 Synchronizacja

Po wprowadzeniu zmian do Google Docs, uruchom ponownie:

```bash
bun run hbm gdrive:sync
```

Aby zaktualizować lokalną kopię książek.

---

*Homebrew Magic: Role Playing Game v3 © 2026*
