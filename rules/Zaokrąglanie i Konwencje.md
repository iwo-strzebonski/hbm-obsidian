---
tags:
  - rule
  - hub
  - conventions
aliases:
  - Zaokrąglanie
  - Zasada zaokrąglania
  - Konwencje
  - Zaokrąglanie i Konwencje
---
# Zaokrąglanie i Konwencje

> [!important] Złota zasada zaokrąglania
> **W tym systemie wszystko, co wychodzi ułamkiem, zaokrągla się W GÓRĘ** - połowa z 5 to 3, jedna trzecia z 10 to 4, ×1,5 z 3 to 5.
> Jeżeli jakaś zasada działa inaczej, **tekst tej zasady mówi to wprost** (patrz: tabela wyjątków poniżej). Jeżeli tekst nie wspomina o zaokrąglaniu - zaokrąglasz w górę.

## Wyjątki od zasady zaokrąglania w górę

To są **wszystkie** miejsca, w których zaokrąglamy inaczej. Każde z nich jest w swoim opisie oznaczone jako wyjątek.

| Zasada | Jak zaokrąglamy | Gdzie jest opisana |
| --- | --- | --- |
| **Koszt many nowo tworzonego zaklęcia** (wynik wzoru kosztu) | do **najbliższej** liczby całkowitej, minimum 1 mana (np. 1,4 → 1; 1,5 → 2; 1,9 → 2) | [Kroki tworzenia zaklęcia](01.%20Księga%20Magii/Rozdział%20VII%20-%20Tworzenie%20Zaklęć/Kroki%20tworzenia%20zaklęcia.md) (krok 9) |
| **Bonus z Nadczarowania od 3. Poziomu** (połowa bonusu) | **w dół**, ale nigdy poniżej 1 | [Zasada Nadczarowywania Zaklęć](01.%20Księga%20Magii/Rozdział%20II%20-%20Teoria%20Rzucania%20Zaklęć/Zasada%20Nadczarowywania%20Zaklęć.md) |

## Miejsca, w których zaokrąglanie w górę jest zapisane wprost

Dla porządku - te zasady same przypominają o zaokrąglaniu w górę:

- **Zapał** - połowa Atrybutu Dusza ([Zapał](00.%20Podręcznik%20Gry/Rozdział%20II%20-%20Tworzenie%20Postaci/Zapał.md)),
- **Koncentracja** - trzecia część utraconej Żywotności ([Koncentracja](00.%20Podręcznik%20Gry/Aneks%20A%20-%20Stany%20Postaci/Koncentracja.md)),
- **Parowanie** - połowa Umiejętności Walka Wręcz atakowanego ([Parowanie](00.%20Podręcznik%20Gry/Rozdział%20IV%20-%20Talenty/Parowanie.md)),
- **Niezniszczalne Zaklęcia** - połowa Zdolności Magicznych ([Niezniszczalne Zaklęcia](00.%20Podręcznik%20Gry/Rozdział%20IV%20-%20Talenty/Niezniszczalne%20Zaklęcia.md)),
- **Metamagia** - Punkty Metamagii ([Metamagia](02.%20Klątwa%20Otchłani/Rozdział%20II%20-%20Talenty/Metamagia.md)),
- **Dary Otchłani 66-70** - utrata Żywotności ([Dary Otchłani](02.%20Klątwa%20Otchłani/Rozdział%20III%20-%20Dary%20Otchłani.md)),
- **Potęga Efektu** - mnożniki ×0,5 i ×1,5 ([Tabela Potęgi Efektu](01.%20Księga%20Magii/Rozdział%20VII%20-%20Tworzenie%20Zaklęć/Tabela%20Potęgi%20Efektu.md)),
- **Magiczny Pocisk** i **Magiczna Tarcza** - połowa Zdolności Magicznych ([Magiczny Pocisk](../spells/general/magic-missile.md), [Magiczna Tarcza](../spells/general/magic-shield.md)).

Wszystkie inne "połowy" i "trzecie części" w podręcznikach (połowa Ruchu, trzecia część puli Many po Krótkim Odpoczynku, połowa puli Many po Ciężkiej Zapaści, połowa Umysłu przy limicie artefaktów itd.) również zaokrąglamy w górę.

## Jak to liczyć - szybkie przykłady

| Sytuacja | Obliczenie | Wynik |
| --- | --- | --- |
| Zapał postaci z Duszą 5 | ½ × 5 = 2,5 | **3** |
| Magiczny Pocisk, Zdolności Magiczne 5 | ½ × 5 = 2,5 | **3** obrażenia |
| Magiczna Tarcza, Zdolności Magiczne 5 | ½ × 5 = 2,5 → 3, plus 1 | **4** punkty wytrzymałości |
| Krótki Odpoczynek, pula Many 36 | ⅓ × 36 | **12** many |
| Krótki Odpoczynek, pula Many 21 | ⅓ × 21 | **7** many |
| Ruch 10 m, postać Spowolniona | ½ × 10 | **5** m |
| Ruch 9 m, postać Spowolniona | ½ × 9 = 4,5 | **5** m |
| Nowe zaklęcie, wzór daje 2,5 | najbliższa całkowita (**wyjątek**) | **3** many |
| Nadczarowanie, 3. Poziom, bonus +3 | ½ × 3 = 1,5 w dół (**wyjątek**) | **+1** |

## Pozostałe konwencje zapisu

- **T:S** - Trudność (próg na k6, od którego kość liczy się jako Sukces) oraz liczba wymaganych Sukcesów. Przeciętny test to **4:1**.
- **Stopień trudności** - "o jeden Stopień trudniejszy" znaczy **+1 do Trudności** (np. 4:1 → 5:1), "o jeden Stopień prostszy" znaczy -1.
- **Jedynka** na kości jest zawsze porażką, **szóstka** zawsze Sukcesem, niezależnie od modyfikatorów.
- **k6, k3, k2, k10** - kość o danej liczbie ścianek; **Nk6** - rzut N kośćmi sześciościennymi, wyniki sumujemy (np. w tabelach kar).
- **Minimum** - jeśli zasada mówi "do minimum 0/1", wynik nigdy nie spada poniżej tej wartości.
- **Pierwszeństwo zasad** - zasady zaklęć, eliksirów i modlitw z [Księgi Magii](01.%20Księga%20Magii.md) nadpisują te z Podręcznika Gry; opis konkretnego zaklęcia, Talentu lub przedmiotu nadpisuje zasadę ogólną.

Zobacz też: [Ściągawka Gracza](Ściągawka%20Gracza.md) · [Ściągawka Mistrza Gry](Ściągawka%20Mistrza%20Gry.md) · [Zasady Gry](Zasady%20Gry.md)
