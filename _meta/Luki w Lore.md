---
tags:
  - meta
  - todo
---
# Luki w Lore — do uzupełnienia

Zestawienie brakujących lub niedokończonych elementów wykryte podczas audytu vaulta (2026-08-17). Zaktualizowano 2026-08-18 po pierwszej rundzie uzupełnień (commit `6fb72b0`), a następnie po drugiej rundzie (sesja współpracy w plain checkout). To dokument roboczy (meta), nie lore w świecie gry — checklistę można kasować/aktualizować w miarę uzupełniania pozycji.

## Puste sekcje w plikach indeksowych (hub) — ROZWIĄZANE
- [x] [npcs.md](../npcs.md) — sekcja "## Zakon Taumaturgów" uzupełniona (Diana Koniecpolska, Zofia „Zonk” Zawadzka, „Mikrofalka” Nowak)
- [x] [npcs.md](../npcs.md) — dodano sekcje dla [Siły Specjalne Gaja](../organizations/Federacja%20Sol-3/Siły%20Specjalne%20Gaja.md) i [Wybrańcy Herosów](../organizations/Federacja%20Sol-3/Wybrańcy%20Herosów.md)
- [ ] [player-characters.md](../player-characters.md) — plik nadal całkowicie pusty

## Brakujące wpisy w indeksach — ROZWIĄZANE
- [x] [npcs/Nemyo.md](../npcs/Nemyo.md) — dodana do `npcs.md` (sekcja "Niezrzeszeni")

## Uszkodzone komórki tabel (niewypełniony placeholder `**` z szablonu)
Problem systemowy — szablony w `_templates/` (NPC, Organizacja, Konflikt) zawierają dosłowny placeholder `**`, który w wielu realnych stronach nigdy nie został zastąpiony treścią.

**Pole "Zdjęcie" puste/uszkodzone (wciąż otwarte):**
- [ ] [npcs/Uczniowie/Maedinitia.md](../npcs/Uczniowie/Maedinitia.md)
- [ ] [npcs/Uczniowie/Kiara.md](../npcs/Uczniowie/Kiara.md)
- [ ] [npcs/Nemyo.md](../npcs/Nemyo.md)
- [ ] [npcs/Uczniowie/Klara.md](../npcs/Uczniowie/Klara.md)
- [ ] [npcs/Inkwizycja/Tena Lindemann.md](../npcs/Inkwizycja/Tena%20Lindemann.md)
- [ ] [npcs/Nauczyciele/Leopold von Karma.md](../npcs/Nauczyciele/Leopold%20von%20Karma.md)
- [ ] [npcs/Uczniowie/Narcyza Eleness Zurbach.md](../npcs/Uczniowie/Narcyza%20Eleness%20Zurbach.md)
- [ ] [npcs/Brytyjska Akademia Wiedźm/Croix Meridies.md](../npcs/Brytyjska%20Akademia%20Wiedźm/Croix%20Meridies.md)
- [ ] [npcs/Federacja Sol-3/Nicodemus Florens.md](../npcs/Federacja%20Sol-3/Nicodemus%20Florens.md)
- [ ] [npcs/Federacja Sol-3/Joe Cox.md](../npcs/Federacja%20Sol-3/Joe%20Cox.md)
- [ ] [npcs/Klaus von Übertropp.md](../npcs/Klaus%20von%20Übertropp.md)
- [ ] [organizations/Bank Krasnoludzki.md](../organizations/Bank%20Krasnoludzki.md) *(strona przeniesiona z `npcs/Bank Krasnoludzki/` do `organizations/` - to instytucja, nie NPC)*
- [ ] [npcs/Bank Krasnoludzki/Brogir Vane.md](../npcs/Bank%20Krasnoludzki/Brogir%20Vane.md)
- [ ] [organizations/Federacja Sol-3/Siły Specjalne X.md](../organizations/Federacja%20Sol-3/Siły%20Specjalne%20X.md)

**Rozwiązane w drugiej rundzie (sesja współpracy w plain checkout, 2026-08-18):**
- [x] Mundus — Pseudonim (ustawiony na „—”, celowo N/A - brak fabularnego haka jak u Nil/"Abyss")
- [x] Tempus — Pseudonim („—”, N/A), Charakter (enigmatyczny, doświadcza czasu nielinearnie, męskie formy gramatyczne)
- [x] Diana Koniecpolska — Pseudonim („—”, N/A)
- [x] Aurora — Pseudonim („—”, N/A)
- [x] Xillith Isherwood — Pseudonim („—”, N/A)
- [x] Talonos Isherwood — Pseudonim ("Mnich")
- [x] Narcyza Eleness Zurbach — Pseudonim („—”, N/A), Tytuł ("Księżniczka demonów", przeniesiony ze zduplikowanej strony root przy okazji konsolidacji)
- [x] Serioża Żukow — Pseudonim ("Serioża" - rosyjski zdrobniały wariant "Siergieja"), Charakter (surowy oficer starej daty, dowodzi strachem)
- [x] Bill Cipher — Wzrost, Pseudonim ("Demon Snów"), Tytuł ("Wszechpotężny i Wspaniały Bill"), Charakter
- [x] Wybrańcy Herosów — Nazwa oficjalna, Siedziba (Sol-3-0641), Ważniejsi członkowie (brak poza Pelagiusem - organizacja wciąż w fazie formowania)
- [x] Projekt Starlight — Szacowana liczba członków (ok. 2500)
- [x] Brytyjska Akademia Wiedźm — Nazwa potoczna ("BAW")
- [x] Pierwsza Wojna Federacji Sol-3 i Malferian — wszystkie 5 uszkodzonych komórek (audyt z 2026-08-17 wykrył tylko 3; Dowódcy Malferian, Ważniejsze formacje wojskowe ×2, Liczebność wojsk ×2 - wojna asymetryczna, Federacja znacznie mniej liczebna niż Konsorcjum)

**Rozwiązane w trzeciej rundzie (przyjęcie zasady "opisy mogą być dłuższe i płynniejsze", 2026-08-18):**
- [x] Siły Specjalne Gaja — druga rewizja: rozbudowano do pełniejszej prozy (zob. notatka stylistyczna niżej)
- [x] Bill Cipher — Charakter rozbudowany do płynniejszej, dłuższej prozy (bez zmiany treści)
- [x] Serioża Żukow — Charakter rozbudowany do płynniejszej, dłuższej prozy (bez zmiany treści)
- Przegląd pozostałych pól dodanych w drugiej rundzie (Tempus, Nil, Pelagius Caudex/Relacje) — uznane za już spójne z nowym standardem, bez zmian; pola ustawione na „—” (N/A) pominięte jako niedotyczące prozy

**Dodatkowe poprawki znalezione przy okazji (nie były na liście audytu):**
- [x] Usunięto zduplikowaną, osieroconą stronę [npcs/Narcyza Eleness Zurbach.md] (identyczny wzorzec jak Robert Zaryn/Ten, Który jest Mroczny) - skonsolidowano do `npcs/Uczniowie/Narcyza Eleness Zurbach.md`
- [x] Usunięto zduplikowaną, osieroconą stronę `npcs/Klara.md` (identyczna treść co `npcs/Uczniowie/Klara.md`) i naprawiono odnośnik w `npcs/Uczniowie/Klara.md`
- [x] Poprawiono literówkę "Konsocjum Gwiezdne Malferian" → "Konsorcjum Gwiezdne Malferian" w `npcs.md` (niezgodność z rzeczywistą nazwą pliku/organizacji)
- [x] Nil — dodano charakterystykę: obecna manifestacja nienawidzi przezwiska "Abyss" (używanego przez Federację Sol-3) i reaguje na nie agresją; dodano powiązany incydent z Pelagiusem Caudexem w jego relacjach

**Rozwiązane w pierwszej rundzie (commit `6fb72b0`):**
- [x] Mistrz Losu — Tytuł(y), Charakter
- [x] Mundus — Wzrost, Charakter
- [x] Nil — Wzrost, Charakter
- [x] Tempus — Wzrost
- [x] Ten, Który jest Mroczny — Charakter
- [x] Narcyza Eleness Zurbach — Tytuł(y)
- [x] Anna Heide — Pseudonim, Tytuł, Charakter (ustawione na „—”, celowo N/A)

## Brakujące grafiki/portrety (pusty embed `![[.jpg|200]]`, brak nazwy pliku)
- [ ] [organizations/Bill Cipher and Co.md](../organizations/Bill%20Cipher%20and%20Co.md)
- [ ] [organizations/Federacja Sol-3/Projekt Starlight.md](../organizations/Federacja%20Sol-3/Projekt%20Starlight.md)
- [ ] [organizations/Federacja Sol-3/Siły Specjalne Gaja.md](../organizations/Federacja%20Sol-3/Siły%20Specjalne%20Gaja.md)
- [ ] [organizations/Federacja Sol-3/Wybrańcy Herosów.md](../organizations/Federacja%20Sol-3/Wybrańcy%20Herosów.md)
- [ ] [npcs/Federacja Sol-3/Projekt Starlight/Norbert Goch.md](../npcs/Federacja%20Sol-3/Projekt%20Starlight/Norbert%20Goch.md)

## Jawne oznaczenia "do uzupełnienia" przez autora
- [ ] [npcs/Nemyo.md](../npcs/Nemyo.md) — stopka: *"Ta postać czeka na pełny opis - reszta jej historii, charakteru i szczegółów zostanie uzupełniona."*
- [ ] [organizations/Federacja Sol-3/Wybrańcy Herosów.md](../organizations/Federacja%20Sol-3/Wybrańcy%20Herosów.md) — status: *"W trakcie formowania"* (może być częściowo celowe fabularnie — organizacja faktycznie jest w budowie w świecie gry, ale puste pola tabeli warto i tak dopracować)

## Postacie wspomniane, ale bez własnej strony
- Zofia "Zonk" Zawadzka i "Mikrofalka" Nowak — członkinie [Zakonu Taumaturgów](../organizations/Zakon%20Taumaturgów.md) wymienione w prozie strony (i teraz też w `npcs.md`), bez dedykowanej strony NPC. Prawdopodobnie celowo pominięte jako postacie drugoplanowe/komediowe — oznaczone tu tylko dla kompletności.

## Uwaga stylistyczna (nie jest luką faktograficzną) — ROZWIĄZANE
- [x] [Siły Specjalne Gaja.md](../organizations/Federacja%20Sol-3/Siły%20Specjalne%20Gaja.md) — przepisana dwuetapowo: najpierw usunięto spis treści oraz rozdęte, powtarzające się nagłówki ("Tajemnice i Legendy...", "Znaczenie dla Federacji" / "...i Wszechświata" jako dwa osobne, niemal identyczne akapity); następnie, po ustaleniu ogólnej zasady dla vaulta ("opisy mogą być dłuższe, płynniejsze i łatwiejsze do zapamiętania - bez konieczności zwięzłości"), tekst rozbudowano ponownie do pełniejszej, płynnej prozy (Opis, Rekrutacja i szkolenie, Zakres działań, Struktura i dowodzenie, Syllia Orirel) - bez przywracania spisu treści ani dosłownych powtórzeń, wszystkie fakty zachowane.
- [Zakon Taumaturgów.md](../organizations/Zakon%20Taumaturgów.md) — sprawdzone ponownie: nagłówki są zwięzłe i treściwe (Opis organizacji, Struktura i działalność, Filozofia i ton, Znani członkowie, Wskazówki dla MG), styl już spójny z resztą vaulta — bez zmian.

---
*Wygenerowano podczas audytu vaulta 2026-08-17, zaktualizowano 2026-08-18 po pierwszej rundzie uzupełnień. Aktualizuj lub usuwaj pozycje w miarę ich uzupełniania.*
