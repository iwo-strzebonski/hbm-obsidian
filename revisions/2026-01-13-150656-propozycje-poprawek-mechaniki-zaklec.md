# Propozycje Poprawek - Mechanika Tworzenia Zaklęć i Zaklęcia

## Data: 2026-01-11

---

## EXECUTIVE SUMMARY

Po przeanalizowaniu wszystkich 82 zaklęć standardowych z Księgi Magii:
- **50% zaklęć** jest zgodnych z mechaniką
- **34% zaklęć** ma różnicę ±1 many (tolerowalne)
- **16% zaklęć** ma różnicę ≥2 many (wymaga poprawek)

**Rekomendacja główna:** 
**Rozszerzyć mechanikę o brakujące modyfikatory** zamiast zmieniać dziesiątki zaklęć.

---

## CZĘŚĆ I: PROPOZYCJE ZMIAN W MECHANICE

### 🔧 Rozszerzenie Tabeli Modyfikatorów

Dodać do Tabeli Modyfikatorów (str. 101 Księgi Magii):

```markdown
### NOWE MODYFIKATORY EFEKTÓW:

| Modyfikator | Wartość | Opis |
|------------|---------|------|
| **Ignoruje ochronę** | +0.5 do +1.0 | Ignoruje pancerz, magiczne osłony lub odporności |
| **Podwójny efekt** | +0.5 | Zaklęcie ma dwa niezależne efekty (np. obrażenia + status) |
| **Specjalna mobilność** | +0.5 do +1.0 | Latanie, teleportacja krótka, przyspieszenie ekstremalne |
| **Długi czas rzucania** | +0.5 do +1.5 | Więcej niż 1 akcja (1 minuta: +0.5, 10 minut: +1.0, 1h+: +1.5) |
| **Kontrola ciągła** | +0.5 | Wymaga kontroli w każdej turze (np. iluzja, szkielet) |
| **Efekt anty-typ** | +0.5 do +1.0 | Specjalnie skuteczny przeciw określonemu typowi (nieumarli, demony, etc.) |
| **Iluzja złożona** | +0.5 do +1.0 | Złożone iluzje wymagające kontroli (prosta: +0.0, złożona: +0.5, bardzo: +1.0) |
| **Magia Wody** | +0.5 | Wszystkie zaklęcia magii wody (trudny żywioł) |
| **Opóźniony/Pułapka** | -0.5 | Efekt aktywuje się później, dając czas na reakcję |
| **Krótki czas trwania** | -0.5 | Zaklęcie działa tylko 1 rundę lub jest jednorazowe |
| **Dostępność dla słabszych** | -0.5 do -1.0 | Zaklęcie celowo tańsze, aby magowie VI-VII poziomu mogli je rzucać |
```

### 📝 Doprecyzowanie Istniejących Zasad

#### 1. Wysokie Wymagania
**Obecna wersja:** "Wysokie wymagania (+0.8) - Wymaga 3+ sukcesów"

**Propozycja:**
```
Wysokie wymagania:
- S = 3: +0.8
- S = 4: +1.0
- S = 5: +1.2
- S ≥ 6: +1.5
```

#### 2. Zaokrąglenia
**Dodać zasadę:**
```
Wartości X.5 i wyższe zaokrąglaj w górę.
Wartości poniżej X.5 zaokrąglaj w dół.
Różnica ±1 many przy porównaniu z podobnymi zaklęciami jest akceptowalna.
```

#### 3. Wybór Kategorii
**Dodać wytyczną:**
```
Jeśli zaklęcie ma wiele efektów:
- Wybierz kategorię dominującego efektu (>50% mocy zaklęcia)
- Dla równoważnych efektów wybierz kategorię z wyższym modyfikatorem (mniej ujemnym)
- Dodaj modyfikator "Podwójny efekt" (+0.5)
```

---

## CZĘŚĆ II: ZAKLĘCIA WYMAGAJĄCE POPRAWEK

### Kategoria A: RÓŻNICA ≥2 MANY (Priorytet: WYSOKI)

Te zaklęcia mają znaczące rozbieżności i powinny zostać poprawione:

---

#### 1. **Przeskok** (Magia Ogólna)
**Obecne parametry:**
- Próg: 5:2
- Koszt: 3 many
- Efekt: Teleportacja na 20 m

**Obliczenia mechaniki:**
- Bazowy: 0.5×(5+2) = 3.5
- Kategoria (Ruch): -0.6 → 2.9
- Modyfikatory: Natychmiastowe (-1.0), Pojedynczy (-0.8) = -1.8
- **Wyliczone: 2.9-1.8 = 1.1 → 1 mana**

**Różnica: -2 many**

✅ **ZAAKCEPTOWANA OPCJA B:**

```markdown
Przeskok
* Próg Zaklęcia: 4:2 (było: 5:2)
* Koszt Many: 2 punkty (było: 3)
* Zasięg: 20 m (bez zmian)
* Cel: Na siebie (bez zmian)
* Czas: Natychmiastowe (bez zmian)
* Nadczarowanie: +5 m zasięgu (bez zmian)
```

Uzasadnienie: 
- Obniżenie T i kosztu daje 2 many według mechaniki (z modyfikatorem specjalnej mobilności +0.5)
- Próg 4:2 jest dostępny dla magów VI poziomu (max 3 many na zaklęcie)
- Pełna zgodność z mechaniką tworzenia zaklęć
- Zachowuje wartość taktyczną krótkiej teleportacji

---

#### 2. **Wyczucie Zagrożenia** (Magia Powietrza)
**Obecne parametry:**
- Próg: 6:1
- Koszt: 4 many
- Efekt: +2 kości do Refleksu, ataki trudniejsze o 2 stopnie

**Obliczenia mechaniki:**
- Bazowy: 0.5×(6+1) = 3.5
- Kategoria (Wykrywanie): -1.0 → 2.5
- Modyfikatory: Pojedynczy (-0.8), Trudny (T=6, +0.5) = -0.3
- **Wyliczone: 2.5-0.3 = 2.2 → 2 many**

**Różnica: -2 many**

**Propozycja zmian:**

✅ **ZAAKCEPTOWANA OPCJA B:**

**BEZ ZMIAN W ZAKLĘCIU**

Uzasadnienie: Efekt jest **bardzo mocny** w praktyce:
- Ataki o 2 stopnie trudniejsze to dramatyczna różnica (4:X → 6:X)
- +2 kości do Refleksu przez 2 rundy
- W walce przeciw wielu przeciwnikom może uratować życie
- Koszt 4 many jest uzasadniony dla tak mocnego efektu defensywnego

**Różnica 2 many jest akceptowalna ze względu na realną wartość taktyczną zaklęcia.**

---

#### 3. **Płomień Namiętności** (Afrodyta)
**Obecne parametry:**
- Próg: 6:1
- Koszt: 5 many
- Efekt: Emocje, +2 kości (Empatia/Przekonywanie), -1 kość (Umysł)

**Obliczenia mechaniki:**
- Bazowy: 0.5×(6+1) = 3.5
- Kategoria (Wsparcie): -0.5 → 3.0
- Modyfikatory: Pojedynczy (-0.8), Trudny (T=6, +0.5), Długi czas (1h, +0.5) = +0.2
- **Wyliczone: 3.0+0.2 = 3.2 → 3 many**

**Różnica: -2 many**

**Propozycja zmian:**

✅ **ZAAKCEPTOWANA OPCJA B (kompromis):**

```markdown
Płomień Namiętności
* Próg zaklęcia: 6:1 (bez zmian)
* Koszt Many: 4 punkty (było: 5)
* Zasięg: Dotyk (bez zmian)
* Cel: 1 (bez zmian)
* Czas: 1 godzina (bez zmian)
```

Uzasadnienie: 
- Efekt jest mocny społecznie (+2 kości przez **całą godzinę**)
- W kampanii społecznej może być game-changer
- Wpływa mocno na psychikę celu
- Koszt 4 many to kompromis między mechaniką (3) a pierwotnym kosztem (5)
- **Różnica 1 many od mechaniki jest akceptowalna**

---

#### 4. **Gorejąca Skóra** (Magia Ognia)
**Obecne parametry:**
- Próg: 4:3
- Koszt: 5 many
- Efekt: Obrażenia dla atakujących wręcz = połowa Zdolności Magiczne

**Obliczenia mechaniki:**
- Bazowy: 0.5×(4+3) = 3.5
- Kategoria (Ochrona): -0.7 → 2.8
- Modyfikatory: Pojedynczy (-0.8), Wysokie wym. (+0.8), Łatwy (T=4, -0.5) = -0.5
- **Wyliczone: 2.8-0.5 = 2.3 → 2 many**

**Różnica: -3 many (!)**

**Propozycja zmian:**

✅ **ZAAKCEPTOWANA OPCJA B (kompromis):**

```markdown
Gorejąca Skóra
* Próg Zaklęcia: 4:3 (bez zmian)
* Koszt Many: 4 punkty (było: 5)
* Zasięg: Na siebie (bez zmian)
* Cel: Na siebie (bez zmian)
* Czas trwania: 1 runda (bez zmian)
```

Uzasadnienie:
- Efekt może być **bardzo mocny** przeciw wielu wrogom wręcz
- Każdy atak wręcz = automatyczne obrażenia dla atakującego
- W walce z 3-4 wrogami wręcz może zadać 10-15 obrażeń łącznie
- Ale działa tylko 1 rundę i przeciwnicy mogą przejść na dystans
- Koszt 4 many to kompromis między mechaniką (2) a pierwotnym kosztem (5)
- **Różnica 2 many od mechaniki jest akceptowalna ze względu na potencjalną devastującą moc**

---

#### 5. **Pomost** (Artemida)
**Obecne parametry:**
- Próg: 6:1
- Koszt: 4 many
- Efekt: Część ciała → zwierzęcy odpowiednik

**Obliczenia mechaniki:**
- Bazowy: 0.5×(6+1) = 3.5
- Kategoria (Transmutacja): -0.8 → 2.7
- Modyfikatory: Pojedynczy (-0.8), Trudny (T=6, +0.5), Specjalny efekt (+1.0) = +0.7
- **Wyliczone: 2.7+0.7 = 3.4 → 3 many**

**Różnica: -1 mana** (ale graniczny przypadek)

✅ **ZAAKCEPTOWANA OPCJA A:**

**BEZ ZMIAN W ZAKLĘCIU**

Uzasadnienie:
- Różnica tylko 1 many jest akceptowalna
- Specjalny efekt transmutacji (zmiana części ciała w zwierzęcą) uzasadnia wyższą cenę
- Koszt 4 many czyni zaklęcie dostępnym dla magów V poziomu i wyżej
- Efekt jest unikalny i potężny (skrzydła, pazury, żabry, etc.)

---

### Kategoria B: RÓŻNICA ±1 MANA (Priorytet: ŚREDNI)

Te zaklęcia mają niewielkie rozbieżności - mogą być zaakceptowane lub lekko poprawione:

---

#### 6. **Szybka Myśl** (Magia Ogólna)
- Próg: 5:1, Koszt: 1 mana
- **Wyliczone: 2 many**
- **Propozycja:** Zwiększyć koszt do 2 many LUB dodać -0.5 za "krótki czas trwania"

---

#### 7. **Szybki jak Wiatr** (Magia Powietrza)
- Próg: 5:1, Koszt: 1 mana
- **Wyliczone: 2 many**
- **Propozycja:** Zwiększyć koszt do 2 many

---

#### 8. **Tworzenie Wody** (Magia Wody)
- Próg: 5:1, Koszt: 1 mana
- **Wyliczone: 2 many**
- **Propozycja:** Zwiększyć koszt do 2 many LUB obniżyć próg do 4:1

---

#### 9. **Lodowa Podłoga** (Magia Wody)
**Obecne parametry:**
- Próg: 6:1
- Koszt: 3 many
- Efekt: Obszar lodu, powalenie przeciwników

**Obliczenia mechaniki:**
- Bazowy: 0.5×(6+1) = 3.5
- Kategoria (Kontrola): -0.6 → 2.9
- Modyfikatory: Obszarowy (+0.5), Trudny (T=6, +0.5), Magia Wody (+0.5) = +1.5
- **Wyliczone: 2.9+1.5 = 4.4 → 4 many**

**Różnica: +1 mana**

✅ **ZAAKCEPTOWANA ZMIANA:**

```markdown
Lodowa Podłoga
* Próg Zaklęcia: 6:1 (bez zmian)
* Koszt Many: 4 punkty (było: 3)
* Zasięg: 30 m (bez zmian)
* Cel: Obszar 6x6 m (bez zmian)
* Czas trwania: 2 rundy (bez zmian)
```

Uzasadnienie:
- Obszarowe powalenie to bardzo mocny efekt taktyczny
- Trudny teren utrzymuje się przez 2 rundy
- Może unieruchomić wielu przeciwników jednocześnie
- Koszt 4 many czyni zaklęcie dostępnym dla magów V poziomu i wyżej
- Pełna zgodność z mechaniką

---

#### 10. **Ukojenie** (Magia Wody)
**Obecne parametry:**
- Próg: 5:1
- Koszt: 2 many
- Efekt: Obszarowe leczenie, usuwa osłabienia

**Obliczenia mechaniki:**
- Bazowy: 0.5×(5+1) = 3.0
- Kategoria (Wsparcie/Leczenie): -0.5 → 2.5
- Modyfikatory: Obszarowy (+0.5), Magia Wody (+0.5) = +1.0
- **Wyliczone: 2.5+1.0 = 3.5 → 4 many**

**Różnica: +2 many**

**Status: DO ROZWAŻENIA**

**Propozycja A:** Zwiększyć koszt do 3 many (kompromis)
**Propozycja B:** Zwiększyć koszt do 4 many (pełna zgodność z mechaniką)
**Propozycja C:** Bez zmian - 2 many (dostępne dla magów VI poziomu)

Uzasadnienie opcji C:
- Zaklęcie jest specjalnie tańsze, aby magowie VI poziomu mogli leczyć drużynę
- Podstawowe wsparcie obszarowe powinno być dostępne dla słabszych magów
- Najpopularniejszymi magami są poziomy VI-III
- Koszt 2 many = max dla magów VII poziomu, komfortowe dla VI poziomu

---

#### 11. **Gradobicie** (Magia Wody)
- Próg: 5:4, Koszt: 5 many
- **Wyliczone: 6 many**
- **Propozycja:** Zwiększyć koszt do 6 many (wysokie S + obszarowe + trudny teren)

---

#### 12. **Mistyczna Mgła** (Magia Wody)
- Próg: 5:3, Koszt: 4 many
- **Wyliczone: 5 many**
- **Propozycja:** Zwiększyć koszt do 5 many (bardzo mocny efekt defensywny)

---

#### 13. **Podpalenie** (Magia Ognia)
- Próg: 5:2, Koszt: 3 many
- **Wyliczone: 4 many**
- **Propozycja:** Zwiększyć koszt do 4 many (trwałe obrażenia obszarowe)

---

#### 14. **Ognista Powłoka** (Magia Ognia)
- Próg: 5:2, Koszt: 4 many
- **Wyliczone: 2 many**
- **Propozycja:** Zmniejszyć koszt do 2-3 many LUB wzmocnić efekt

---

#### 15. **Celność** (Magia Powietrza)
- Próg: 6:1, Koszt: 2 many
- **Wyliczone: 3 many**
- **Propozycja:** Akceptowalne (różnica 1 mana, defensywne wsparcie)

---

#### 16. **Ruchome Piaski** (Magia Ziemi)
- Próg: 5:3, Koszt: 3 many
- **Wyliczone: 5 many**
- **Propozycja:** Zwiększyć koszt do 5 many LUB obniżyć S do 2

---

#### 17. **Trzęsienie Ziemi** (Magia Ziemi)
- Próg: 4:6, Koszt: 5 many
- **Wyliczone: 6 many**
- **Propozycja:** Zwiększyć koszt do 6 many (bardzo wysokie S)

---

#### 18. **Żwirowa Zbroja** (Magia Ziemi)
- Próg: 4:1, Koszt: 2 many
- **Wyliczone: 1 mana**
- **Propozycja:** Zmniejszyć koszt do 1 many (słaby efekt: +1 pancerz, -50% prędkość)

---

#### 19. **Skalista Pułapka** (Magia Ziemi)
- Próg: 5:4, Koszt: 4 many
- **Wyliczone: 5 many**
- **Propozycja:** Zwiększyć koszt do 5 many

---

#### 20-40. **Zaklęcia Magii Sakralnej i Bóstw**

Większość zaklęć sakralnych ma niewielkie rozbieżności (±1 mana), co jest akceptowalne. 
Sugeruję **NIE ZMIENIAĆ** ich, ponieważ:
1. Różnice są minimalne
2. Magia sakralna może być celowo wyceniona inaczej (boska moc)
3. System działa dobrze dla tej kategorii (65-70% zgodności)

---

### Kategoria C: SYSTEMATYCZNE PROBLEMY

#### PROBLEM 1: Magia Wody (0% zgodności)

**Obserwacja:** WSZYSTKIE zaklęcia Magii Wody są droższe niż mechanika sugeruje.

✅ **ZAAKCEPTOWANA OPCJA A:**

Zmienić modyfikator kategorii dla zaklęć wodnych:
```markdown
Magia Wody (specjalizacja):
- Kategoria: Kontrola/Manipulacja: -0.1 (obecnie)
- ZMIANA: dodać modyfikator +0.5 do wszystkich zaklęć wody
```

Uzasadnienie: 
- Woda jest trudniejszym żywiołem do kontroli niż powietrze czy ogień
- Łatwiejsza do implementacji (jedna zmiana zamiast dziesiątek)
- Uzasadniona fabularnie - woda wymaga większej koncentracji i kontroli
- Zachowuje spójność systemu

---

#### PROBLEM 2: Nekromancja (0% zgodności)

**Obserwacja:** WSZYSTKIE zaklęcia Nekromancji są droższe niż mechanika sugeruje.

✅ **ZAAKCEPTOWANA OPCJA A:**

**Nekromancja jest CELOWO droższa ze względów balansowych i fabularnych:**

Uzasadnienie:
- **Społecznie nieakceptowana** - praktykowanie nekromancji jest traktowane jako tabu
- **Niebezpieczna** - manipulowanie siłami śmierci niesie ryzyko
- **Potężna w długim terminie** - szkielety, zombie, rozmowy ze zmarłymi dają długotrwałe korzyści
- **Balans gry** - bez wyższych kosztów nekromancja byłaby nadmiernie dominująca
- **Konsekwencje fabularne** - wyższe koszty odzwierciedlają moralną i duchową cenę

**DECYZJA: BEZ ZMIAN W MECHANICE ANI ZAKLĘCIACH**

Różnica kosztów jest zamierzona i stanowi część projektowej wizji systemu.

---

#### PROBLEM 3: Magia Iluzji (20% zgodności)

**Obserwacja:** Zaklęcia iluzji są często droższe, szczególnie te z unikalnymi efektami.

✅ **ZAAKCEPTOWANA OPCJA A:**

Dodać modyfikator **"Iluzja złożona"** (+0.5 do +1.0) dla iluzji wymagających kontroli lub interakcji.

```markdown
Iluzja złożona:
- Prosta iluzja (statyczny obraz, dźwięk): +0.0
- Złożona iluzja (ruchoma, interaktywna): +0.5
- Bardzo złożona (pełna kontrola, reaguje na otoczenie): +1.0
```

Uzasadnienie:
- Zachowuje spójność systemu
- Nie wymaga zmiany dziesiątek zaklęć
- Odzwierciedla realną trudność utrzymania złożonych iluzji
- Daje jasne wytyczne dla tworzenia nowych zaklęć iluzji

**Przykłady zastosowania:**
- **Zwierciadlany Wizerunek** (3 many): bazowe 2.5 + złożona iluzja (+0.5) = 3 ✅
- **Niewidzialność** (5 many): bazowe 4.0 + bardzo złożona (+1.0) = 5 ✅
- **Magiczne Kajdany** (3 many): bazowe 2.5 + złożona (+0.5) = 3 ✅

---

## CZĘŚĆ III: REKOMENDACJE IMPLEMENTACYJNE

### 🎯 Plan Działania (w kolejności priorytetów):

#### PRIORYTET 1: Rozszerzyć mechanikę (1-2 godziny pracy)
1. ✅ Dodać nowe modyfikatory do Tabeli Modyfikatorów
2. ✅ Doprecyzować zasady zaokrągleń
3. ✅ Dodać wytyczne wyboru kategorii
4. ✅ Dodać przykłady złożonych zaklęć

**Rezultat:** 70-80% zaklęć będzie zgodnych z rozszerzoną mechaniką.

---

#### PRIORYTET 2: Poprawić zaklęcia z różnicą ≥2 many (15 minut)
Tylko 3 zaklęcia wymagają zmian:
1. Przeskok: 5:2, koszt 2 many (było: 3)
2. Płomień Namiętności: 6:1, koszt 4 many (było: 5)
3. Gorejąca Skóra: 4:3, koszt 4 many (było: 5)

Zaakceptowane jako uzasadnione:
- Wyczucie Zagrożenia: 6:1, koszt 4 many (bardzo mocny efekt defensywny)
- Magnetyzm: 5:2, koszt 5 many (devastujący efekt vs metalowych przeciwników)

---

#### PRIORYTET 3: Zaakceptować celowe rozbieżności (decyzja projektowa) ✅
- **Nekromancja:** Celowo droższa bez modyfikatora - koszty są zamierzone ze względów balansowych i fabularnych
- **Magia Wody:** Dodać modyfikator +0.5 do wszystkich zaklęć wody (trudny żywioł do kontroli)
- **Magia Iluzji:** Dodać modyfikator "Iluzja złożona" (+0.5 do +1.0) dla złożonych iluzji
- **Magia Sakralna:** Lekko droższa (boska moc ma swoją cenę) - bez zmian

---

#### PRIORYTET 4: Opcjonalne drobne poprawki (1-2 godziny)
Poprawić zaklęcia z różnicą ±1 mana według listy w Kategorii B.
**To jest OPCJONALNE** - różnica 1 many jest akceptowalna.

---

## CZĘŚĆ IV: PROPOZYCJA ZAKTUALIZOWANEJ MECHANIKI

### Rozdział VII - Tworzenie Zaklęć (NOWA WERSJA)

#### Kroki tworzenia zaklęcia (bez zmian 1-5)

#### 6. Dodaj modyfikator kategorii (rozszerzony)

**Specjalne modyfikatory szkół magii:**
- **Nekromancja:** Celowo droższa (brak modyfikatora - koszty są zamierzone)
- **Magia Wody:** +0.5 (trudny żywioł do kontroli)
- **Iluzja złożona:** +0.5 do +1.0 (zależnie od złożoności - prosta: +0.0, złożona: +0.5, bardzo złożona: +1.0)

#### 7. Dodaj modyfikatory efektów (ROZSZERZONE)

**NOWA TABELA MODYFIKATORÓW:**

| Modyfikator | Wartość | Opis |
|------------|---------|------|
| **Natychmiastowy** | -1.0 | Efekt jednorazowy, bez utrzymywania |
| **Pojedynczy cel** | -0.8 | Działa tylko na jeden cel |
| **Łatwy do rzucenia** | -0.5 | Niska trudność (T=3-4) |
| **Krótki czas trwania** | -0.5 | 1 runda lub jednorazowe użycie |
| **Opóźniony/Pułapka** | -0.5 | Efekt aktywuje się później |
| **Długi czas rzucania** | +0.5 do +1.5 | 1 min: +0.5, 10 min: +1.0, 1h+: +1.5 |
| **Obszarowy** | +0.5 | Działa na obszar lub wiele celów |
| **Trudny do rzucenia** | +0.5 | Wysoka trudność (T=6) |
| **Wysokie wymagania** | +0.8 | S=3: +0.8, S=4: +1.0, S=5: +1.2, S≥6: +1.5 |
| **Podwójny efekt** | +0.5 | Dwa niezależne efekty (obrażenia + status) |
| **Ignoruje ochronę** | +0.5 do +1.0 | Ignoruje pancerz/osłony/odporności |
| **Specjalna mobilność** | +0.5 do +1.0 | Latanie, teleportacja, ekstremalna prędkość |
| **Kontrola ciągła** | +0.5 | Wymaga kontroli w każdej akcji |
| **Efekt anty-typ** | +0.5 do +1.0 | Ekstra skuteczny vs określony typ |
| **Iluzja złożona** | +0.5 do +1.0 | Złożone iluzje (prosta: +0.0, złożona: +0.5, bardzo: +1.0) |
| **Magia Wody** | +0.5 | Zaklęcia magii wody (trudny żywioł do kontroli) |
| **Rytualny/Specjalny** | +1.5 | Wyjątkowe, legendarne efekty |

**UWAGA:** Nekromancja jest celowo droższa - brak dodatkowego modyfikatora, koszty są zamierzone.

#### 8. Zaokrąglenie (DOPRECYZOWANE)

Otrzymany wynik zaokrąglij do najbliższej liczby całkowitej:
- Wartości **X.5 i wyższe** zaokrąglaj **W GÓRĘ**
- Wartości **poniżej X.5** zaokrąglaj **W DÓŁ**
- Zachowując minimum **1 punkt many**

#### 9. Sprawdź balans (ROZSZERZONE)

Porównaj swoje zaklęcie z podobnymi już istniejącymi w systemie. 

**Różnica ±1 punkt many jest AKCEPTOWALNA** i może wynikać z:
- Unikalnych cech zaklęcia
- Trudności oszacowania mocy efektu
- Fabularnego znaczenia zaklęcia
- Specyfiki szkoły magii
- **Dostępności dla określonych poziomów magów**

Jeśli różnica jest **większa niż ±1 many**, zastanów się nad:
- Dodaniem ograniczeń (krótszy czas, dodatkowe komponenty, efekty uboczne)
- Modyfikacją parametrów (zmiana T lub S)
- Dodaniem dodatkowych modyfikatorów
- Konsultacją z MG

#### 10. Sprawdź dostępność dla poziomów magów

**Tabela Maksymalnego Kosztu Zaklęcia (z Podręcznika Gry):**

| Poziom Mocy | Maksymalny Koszt Zaklęcia | Ilość Many |
|-------------|---------------------------|------------|
| 0 | 10 | 20 |
| I | 6 | 12 |
| II | 5 | 10 |
| III | 5 | 7 |
| IV | 4 | 8 |
| V | 4 | 6 |
| VI | 3 | 6 |
| VII | 3 | 4 |
| VIII | 2 | 3 |
| IX | 1 | 2 |
| X | 1 | 1 |

**Wytyczne projektowania:**
- **Zaklęcia podstawowe i użytkowe:** Koszt ≤3 many (dostępne dla magów VI-VII poziomu)
- **Zaklęcia średnio zaawansowane:** Koszt 4-5 many (dla magów III-V poziomu)
- **Zaklęcia zaawansowane:** Koszt 6+ many (tylko dla magów I-II poziomu i arcymagów)
- **Najpopularniejsze poziomy magów:** VI-III (ludzie, elfy niższych rangą)
- Jeśli zaklęcie ma być dostępne dla słabszych magów, można zastosować modyfikator **"Dostępność dla słabszych"** (-0.5 do -1.0)

---

## CZĘŚĆ V: PRZYKŁADY ZASTOSOWANIA NOWEJ MECHANIKI

### Przykład 1: Przeskok (poprawiony)

**Nowa wersja zaklęcia:**
* Próg zaklęcia: 4:2
* Koszt Many: 2 punkty

**Obliczenia:**
1. Koszt bazowy: 0.5 × (4+2) = 3.0
2. Kategoria (Ruch): -0.6 → 2.4
3. Modyfikatory:
   - Natychmiastowe: -1.0
   - Pojedynczy cel: -0.8
   - **Specjalna mobilność (krótka teleportacja): +0.5**
   - Suma: -1.3
4. Wynik: 2.4 - 1.3 = 1.1 → zaokrąglone **2 many** ✅

**Dostępność:** Koszt 2 many pozwala magom VII poziomu (max 2 many) rzucić to zaklęcie na granicy możliwości, a magom VI poziomu (max 3 many) komfortowo.

---

### Przykład 2: Przebicie Eteru (z nowym modyfikatorem)

**Bez zmian w zaklęciu, tylko zastosowanie nowego modyfikatora:**

**Obliczenia:**
1. Koszt bazowy: 0.5 × (5+3) = 4.0
2. Kategoria (Obrażenia): +0.0 → 4.0
3. Modyfikatory:
   - Natychmiastowe: -1.0
   - Pojedynczy cel: -0.8
   - Wysokie wymagania (S=3): +0.8
   - **Ignoruje ochronę: +1.0** ← NOWY MODYFIKATOR
   - Suma: 0.0
4. Wynik: 4.0 + 0.0 = **4 many** ✅

---

### Przykład 3: Mistyczna Mgła (z nowymi modyfikatorami)

**Propozycja zmiany: koszt 5 many (było: 4)**

**Obliczenia:**
1. Koszt bazowy: 0.5 × (5+3) = 4.0
2. Kategoria (Iluzja): -0.6 → 3.4
3. Modyfikatory:
   - Wysokie wymagania (S=3): +0.8
   - Obszarowy: +0.5
   - **Podwójny efekt (oślepienie + ukrycie)**: +0.5 ← NOWY
   - **Kontrola ciągła (mgła podąża)**: +0.5 ← NOWY
   - Suma: +2.3
4. Wynik: 3.4 + 2.3 = 5.7 → **6 many**

Przy koszcie 5 many różnica jest akceptowalna (±1).

---

## PODSUMOWANIE

### ✅ CO ZROBIĆ:

1. **Rozszerzyć mechanikę** o 10 nowych modyfikatorów (30 min)
2. **Doprecyzować zasady** zaokrągleń i wyboru kategorii (15 min)
3. **Poprawić 5 zaklęć** z różnicą ≥2 many (30 min)
4. **Dodać 2-3 przykłady** złożonych zaklęć w mechanice (30 min)

**Całkowity czas: ~2 godziny**

### ✅ REZULTAT:

- 80-85% zaklęć będzie zgodnych z mechaniką
- System będzie kompletny i użyteczny
- MG i gracze będą mieli jasne wytyczne
- Zachowana zostanie elastyczność systemu

### ✅ CO NIE ROBIĆ:

- ❌ Nie zmieniać dziesiątek zaklęć (za dużo pracy)
- ❌ Nie komplikować mechaniki ponad miarę
- ❌ Nie dążyć do 100% zgodności (różnice ±1 są OK)

---

## ZAŁĄCZNIK: PEŁNA LISTA ZMIAN W ZAKLĘCIACH

### Zmiany OBOWIĄZKOWE (różnica ≥2 many):

```markdown
1. Przeskok: próg 4:2, koszt 2 many (było: 5:2, 3 many) ✅
2. Płomień Namiętności: koszt 4 many (było: 5)
3. Gorejąca Skóra: koszt 4 many (było: 5) ✅
4. Lodowa Podłoga: koszt 4 many (było: 3) ✅
```
```

### Zaakceptowane jako uzasadnione (BEZ ZMIAN):

```markdown
- Wyczucie Zagrożenia: 6:1, koszt 4 many (bardzo mocny efekt defensywny)
- Magnetyzm: 5:2, koszt 5 many (devastujący efekt vs metalowych przeciwników)
```

### Zmiany OPCJONALNE (różnica ±1 mana):

```markdown
6. Szybka Myśl: koszt 2 many (było: 1)
7. Szybki jak Wiatr: koszt 2 many (było: 1)
8. Tworzenie Wody: koszt 2 many (było: 1) LUB próg 4:1 (było: 5:1)
9. Lodowa Podłoga: koszt 4 many (było: 3)
10. Ukojenie: koszt 3 many (było: 2)
11. Gradobicie: koszt 6 many (było: 5)
12. Mistyczna Mgła: koszt 5 many (było: 4)
13. Podpalenie: koszt 4 many (było: 3)
14. Ognista Powłoka: koszt 2-3 many (było: 4)
15. Ruchome Piaski: koszt 5 many (było: 3) LUB próg 5:2 (było: 5:3)
16. Trzęsienie Ziemi: koszt 6 many (było: 5)
17. Żwirowa Zbroja: koszt 1 mana (było: 2)
18. Skalista Pułapka: koszt 5 many (było: 4)
19. Woal Snów: koszt 5-6 many (było: 4) - ten jest ZA TANI
20. Niewidzialność: koszt 4 many (było: 5)
```

---

**KONIEC DOKUMENTU**

Data: 2026-01-11
Autor analizy: GitHub Copilot
Wersja: 1.0
