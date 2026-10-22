---
tags:
  - meta
  - publication
---
# Publikacja - Znaczniki we frontmatterze

Każda notatka może mieć dwa pola opisujące gotowość do wydania. Brak pola oznacza "jeszcze nieoceniona".

## `publish` - stan gotowości (lista rozwijana)

Jedna wartość na notatkę. Jeżeli pasuje kilka, wybierz tę, która jest wyżej na liście - pierwsza blokuje wydanie.

| Wartość | Znaczenie |
| --- | --- |
| `campaign-only` | Materiał z kampanii. Nie trafi do podręczników. |
| `ip-issues` | Nazwa lub motyw zapożyczony z cudzego utworu; do zmiany albo decyzji autora. |
| `assets-pending` | Brak praw do grafik lub plików towarzyszących. |
| `tests-pending` | Zasada wymaga testów lub balansu przed wydaniem. |
| `needs-rewrite` | Tekst roboczy do przepisania własnymi słowami. |
| `publishable` | Gotowe do wydania. |

## `publish-note` - jedno zdanie wyjaśnienia (opcjonalne)

Dlaczego notatka ma taki stan, np. `Nazwa z moda Botania; do zmiany`.

## `authorship` - kto napisał tekst (osobne pole)

| Wartość | Znaczenie |
| --- | --- |
| `ai-draft` | Szkic tworzony z pomocą AI; do przepisania. |
| `human-rewritten` | Przepisane przez autora. Dopiero to pole może być uznane za własne autorstwo. |

Notatka jest gotowa do wydania, gdy `publish: publishable` **i** `authorship: human-rewritten`.

## Zapytania (Dataview)

````
TABLE publish, publish-note FROM "" WHERE publish AND publish != "publishable" SORT publish
````

Uwaga: Obsidian pokazuje właściwości jako zwykły tekst. Prawdziwą listę rozwijaną dają wtyczki, np. Metadata Menu.
