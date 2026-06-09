# Rewizje do podręcznika "Złoto, Stal i Magia"

**Data:** 2026-01-14  
**Podręcznik:** HbM RPG v3 - Złoto, Stal i Magia  
**Status:** Do weryfikacji

---

## 1. Korekta akapitu o Magii Runicznej (linia ~1570)

### Problem
Akapit błędnie przedstawia konflikt krasnoludy-elfy. Według obecnego tekstu to elfy zablokowały nauczanie Magii Runicznej. W rzeczywistości:
- To **krasnoludy nie chciały dzielić się** tajnikami Magii Runicznej
- **Elfy** w odwecie **zablokowały krasnoludom dostęp** do największych szkół magii (Wielkiej Trzynastki)

### Oryginalny tekst
```
Głównym przedmiotem sporu pozostaje Magia Runiczna - starożytna krasnoludzka sztuka wiązania mocy w symbole i znaki. Elfy, wykorzystując swoje wpływy w Radach Programowych szkół, skutecznie zablokowały wprowadzenie tej dziedziny do oficjalnych programów nauczania. Oficjalnie argumentują, że Magia Runiczna jest "niestabilna i niebezpieczna"; nieoficjalnie wszyscy wiedzą, że chodzi o ideologiczny sprzeciw wobec "więzienia" magii. Krasnoludy zareagowały na to ograniczenie z charakterystyczną dla siebie praktycznością - po prostu uczą Magii Runicznej w ramach klanowych szkoleń, poza oficjalnym systemem edukacji.
```

### Proponowany tekst
```
Głównym przedmiotem sporu pozostaje Magia Runiczna - starożytna krasnoludzka sztuka wiązania mocy w symbole i znaki. Krasnoludy konsekwentnie odmawiają udostępnienia tajników tej dziedziny innym rasom, traktując ją jako świętą spuściznę klanów. Oficjalnie argumentują względami bezpieczeństwa - Magia Runiczna wymaga lat praktyki i głębokiego zrozumienia krasnoludzkich tradycji; nieoficjalnie wszyscy wiedzą, że chodzi o zachowanie monopolu na najbardziej dochodową gałąź rzemiosła magicznego. Elfy zareagowały na to ograniczenie z charakterystyczną dla siebie dobitnością - wykorzystując swoje wpływy w Radach Programowych Wielkiej Trzynastki (trzynastu najpotężniejszych szkół magii), skutecznie zablokowały krasnoludom dostęp do studiowania w tych placówkach. To wzajemne "odwetowe" wykluczenie pogłębia napięcia między rasami do dziś.
```

### Uzasadnienie
Korekta jest zgodna z:
- Informacjami z "Przewodnika Ludzkości po Magicznym Świecie" (linia 451): *"Ich opór przed udostępnieniem tajników Magii Runicznej spowodował konflikt z elfami, który z kolei doprowadził do ograniczeń w dostępie krasnoludów do studiowania niektórych dziedzin magii w Szkołach Magii na Ziemi."*
- Logiką ekonomiczną krasnoludów (Magia Runiczna to ich przewaga konkurencyjna)
- Charakterystyką obu ras w systemie

---

## 2. Korekta notacji "PT" → "T:S"

W podręczniku "Złoto, Stal i Magia" znaleziono **4 wystąpienia** nieprawidłowej notacji "PT" (Próg Trudności), która powinna być zastąpiona notacją **T:S** (Trudność:Sukcesy) zgodną z resztą systemu.

### Wystąpienia do poprawy:

| Linia | Oryginalny tekst | Poprawiony tekst |
|-------|------------------|------------------|
| 959 | `(PT 3)` | `(T:S 3:3)` |
| 1393 | `(PT 4)` | `(T:S 4:3)` |
| 1416 | `PT 3` | `(T:S 3:3)` |
| 2145 | `(PT 3)` | `(T:S 3:3)` |

### Kontekst każdej zmiany:

**Linia 959 (Zakładanie Przedsiębiorstwa):**
- Oryginał: `Licencja: wymagany test Przekonywania (PT 3) podczas rozmowy z urzędnikiem`
- Poprawka: `Licencja: wymagany test Przekonywania (T:S 3:3) podczas rozmowy z urzędnikiem`

**Linia 1393 (Tabela Wykrycia - Obserwacja):**
- Oryginał: `test Spostrzegawczości (PT 4) by to zauważyć`
- Poprawka: `test Spostrzegawczości (T:S 4:3) by to zauważyć`

**Linia 1416 (Konsekwencje Schwytania):**
- Oryginał: `test Przekonywania PT 3 dla zmniejszenia kary`
- Poprawka: `test Przekonywania (T:S 3:3) dla zmniejszenia kary`

**Linia 2145 (Lunetka Wartości - opis artefaktu):**
- Oryginał: `na magiczne wymaga testu Wiedzy Magicznej (PT 3)`
- Poprawka: `na magiczne wymaga testu Wiedzy Magicznej (T:S 3:3)`

**UWAGA:** Skrót "PT" występuje również w **Podręczniku Gry** (linie 700, 719, 735) - wymaga osobnej rewizji.

---

## 2a. Analiza sensowności trudności

Przeanalizowałem kontekst każdego testu oraz porównałem z innymi trudnościami w dokumencie:

### Linia 959: Licencja handlowa - `(T:S 3:3)` ✅ SENSOWNE
**Kontekst:** Podstawowa licencja na założenie małej firmy handlowej  
**Analiza:**
- Dokument używa **T:S 4:3** jako standardu dla większości testów handlowych
- **T:S 3:3** jest łatwiejsze - to pasuje, bo to podstawowa biurokratyczna procedura
- Porównanie: Licencja Kat. B to T:S 4:3, więc podstawowa licencja powinna być łatwiejsza
- **Rekomendacja:** Pozostawić T:S 3:3 (łatwy test administracyjny)

### Linia 1393: Zauważenie obserwacji - `(T:S 4:3)` ⚠️ DO ROZWAŻENIA
**Kontekst:** Wykrycie, że organy ścigania dyskretnie monitorują postać  
**Analiza:**
- To test **Spostrzegawczości** (nie Przekonywania!)
- Inne testy Spostrzegawczości w tabeli mają podobną trudność
- **Problem:** Czy 4:3 to odpowiednia trudność dla "dyskretnej obserwacji"?
- Porównanie z systemem:
  - Łatwe zauważenie: T:S 3:2
  - Standardowe: T:S 4:3
  - Trudne (profesjonalny szpieg): T:S 5:3 lub 6:3
- **Rekomendacja:** 
  - Jeśli to **zwykła policja** → T:S 4:3 jest OK
  - Jeśli to **Inkwizycja/profesjonaliści** → rozważyć T:S 5:3

### Linia 1416: Negocjacje w sądzie - `(T:S 3:3)` ⚠️ MOŻLIWE ZA ŁATWE
**Kontekst:** Negocjacje z wymiarem sprawiedliwości po schwytaniu z nielegalnym towarem (Kategoria B)  
**Analiza:**
- To **test Przekonywania** w formalnej sytuacji sądowej
- Dokument używa **T:S 4:3** jako standardu dla negocjacji handlowych
- Negocjacje sądowe powinny być **trudniejsze** niż zwykłe handlowe
- Porównanie:
  - Zwykłe negocjacje handlowe: T:S 4:3
  - Przekupstwo celnika: T:S 5:3
  - Negocjacje sądowe: ?
- **Problem:** Czy przekonanie sędziego do zmniejszenia kary powinno być łatwiejsze (T:S 3:3) niż przekonanie kupca (T:S 4:3)?
- **Rekomendacja:** Rozważyć **T:S 5:3** (trudniejsze, bo to oficjalny wymiar sprawiedliwości)

### Linia 2145: Lunetka Wartości - `(T:S 3:3)` ✅ SENSOWNE
**Kontekst:** Test Wiedzy Magicznej do identyfikacji wartości magicznego przedmiotu przez artefakt  
**Analiza:**
- Artefakt **ułatwia** identyfikację (niemagiczne działają automatycznie!)
- **T:S 3:3** jest łatwiejsze od standardu T:S 4:3 - to pasuje
- To test **przy pomocy artefaktu**, więc powinien być łatwiejszy niż bez niego
- **Rekomendacja:** Pozostawić T:S 3:3 (artefakt pomaga, więc test jest łatwiejszy)

---

### Podsumowanie analizy trudności

| Linia | Test | Obecna | Status | Rekomendacja |
|-------|------|--------|--------|--------------|
| 959 | Licencja handlowa | T:S 3:3 | ✅ OK | Bez zmian |
| 1393 | Zauważenie inwigilacji | T:S 4:3 | ⚠️ Zależy | OK dla zwykłej policji; 5:3 dla Inkwizycji |
| 1416 | Negocjacje sądowe | T:S 3:3 | ❌ Za łatwe | **Zmienić na T:S 5:3** |
| 2145 | Lunetka Wartości | T:S 3:3 | ✅ OK | Bez zmian |

### Szczególna uwaga: Linia 1416 (negocjacje sądowe)

**Obecny tekst:**
> Możliwe negocjacje z wymiarem sprawiedliwości (test Przekonywania T:S 3:3 dla zmniejszenia kary)

**Problem mechaniczny:**
- Przekonanie sędziego jest **łatwiejsze (3:3)** niż przekonanie zwykłego kupca **(4:3)**
- To nieintuicyjne i łamie progresję trudności w dokumencie

**Sugerowana korekta:**
> Możliwe negocjacje z wymiarem sprawiedliwości (test Przekonywania (T:S 5:3) dla zmniejszenia kary - wymaga dobrego prawnika lub wyjątkowych okoliczności)

**Uzasadnienie T:S 5:3:**
- Trudniejsze niż zwykłe negocjacje (4:3)
- Porównywalne z przekupstwem celnika (5:3)
- Nadal możliwe, ale wymaga poważnego wysiłku
- 3 sukcesy = częściowe złagodzenie; 4+ = znaczące zmniejszenie

---

## 3. Potencjalny problem: Chronologia magii (magia pojawiła się w 2023)

Podręcznik "Złoto, Stal i Magia" wspomina o:
- Banku Krasnoludzkim otwierającym filię w marcu 2024 (linia ~1430) ✓
- Krasnoludach przybywających w lutym 2024 (linia ~1430) ✓
- Giełdzie MGX otwartej we wrześniu 2025 (linia ~865) ✓
- "Trzech latach po Przebudzeniu" (linia ~885) - kontekst sugeruje 2026 ✓

**Chronologia wydaje się spójna z założeniem, że Przebudzenie Magii nastąpiło w 2023.**

---

## 4. UWAGA: Brak wzmianek o magi-technice

W podręczniku "Złoto, Stal i Magia" **nie znaleziono** bezpośrednich wzmianek o zaawansowanych urządzeniach magi-technicznych czy broni łączącej magię z technologią.

Podręcznik zawiera natomiast fragmenty **zgodne** z założeniem, że magia i technologia "się gryzą":
- W rozdziale o Krasnoludach wspomniano o ich fascynacji ziemską elektroniką, ale jako **odrębnymi dziedzinami** - łączą je ze swoimi konstrukcjami mechanicznymi
- Nie ma wzmianek o zaawansowanej broni magi-technicznej

**Jeśli chodzi o wyraźniejsze podkreślenie tej zasady**, można rozważyć dodanie wzmianki w sekcji o handlu technologią lub w rozdziale o krasnoludach.

### Proponowany dodatek (opcjonalnie)
W rozdziale o handlu krasnoludzkim (sekcja o eksporcie zaawansowanej technologii na Khazad-Morul), można dodać przypis lub akapit:

```
**Uwaga:** Choć krasnoludy chętnie importują ziemską elektronikę i precyzyjne komponenty, ich próby integracji tych urządzeń z magią napotykają fundamentalne ograniczenia. Zaawansowana technologia i magia wzajemnie się zakłócają - im bardziej skomplikowane urządzenie elektroniczne, tym trudniej nasycić je magią bez ryzyka awarii. Z tego powodu nie istnieją prawdziwie "magi-techniczne" urządzenia łączące obie dziedziny na równych prawach. Krasnoludzkie hybrydy to raczej mechaniczne konstrukcje z minimalnymi elektronicznymi dodatkami niż zaawansowana synteza obu technologii.
```

---

## Podsumowanie rewizji

| # | Typ | Priorytet | Status |
|---|-----|-----------|--------|
| 1 | Korekta treści (Magia Runiczna) | **Wysoki** | Do wdrożenia |
| 2 | Korekta notacji PT → T:S (3 miejsca) | **Wysoki** | Do wdrożenia |
| 3 | Chronologia | Info | Brak problemów |
| 4 | Magi-tech | Średni | Opcjonalny dodatek |

---

## Tekst gotowy do skopiowania (Rewizja #1)

### Do zamiany w Google Docs:

**ZNAJDŹ:**
> Głównym przedmiotem sporu pozostaje Magia Runiczna - starożytna krasnoludzka sztuka wiązania mocy w symbole i znaki. Elfy, wykorzystując swoje wpływy w Radach Programowych szkół, skutecznie zablokowały wprowadzenie tej dziedziny do oficjalnych programów nauczania. Oficjalnie argumentują, że Magia Runiczna jest "niestabilna i niebezpieczna"; nieoficjalnie wszyscy wiedzą, że chodzi o ideologiczny sprzeciw wobec "więzienia" magii. Krasnoludy zareagowały na to ograniczenie z charakterystyczną dla siebie praktycznością - po prostu uczą Magii Runicznej w ramach klanowych szkoleń, poza oficjalnym systemem edukacji.

**ZAMIEŃ NA:**
> Głównym przedmiotem sporu pozostaje Magia Runiczna - starożytna krasnoludzka sztuka wiązania mocy w symbole i znaki. Krasnoludy konsekwentnie odmawiają udostępnienia tajników tej dziedziny innym rasom, traktując ją jako świętą spuściznę klanów. Oficjalnie argumentują względami bezpieczeństwa - Magia Runiczna wymaga lat praktyki i głębokiego zrozumienia krasnoludzkich tradycji; nieoficjalnie wszyscy wiedzą, że chodzi o zachowanie monopolu na najbardziej dochodową gałąź rzemiosła magicznego. Elfy zareagowały na to ograniczenie z charakterystyczną dla siebie dobitnością - wykorzystując swoje wpływy w Radach Programowych Wielkiej Trzynastki (trzynastu najpotężniejszych szkół magii), skutecznie zablokowały krasnoludom dostęp do studiowania w tych placówkach. To wzajemne "odwetowe" wykluczenie pogłębia napięcia między rasami do dziś.
