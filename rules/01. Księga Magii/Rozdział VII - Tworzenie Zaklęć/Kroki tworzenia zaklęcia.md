---
tags:
  - rule
  - ksiega-magii
  - spell-creation
aliases:
  - Kroki tworzenia zaklęcia
publish: tests-pending
---
1. Określ efekt zaklęcia
Najpierw jasno zdefiniuj, co dokładnie ma robić Twoje zaklęcie. Czy ma zadawać obrażenia? Leczyć? Chronić? Teleportować? Opisz efekt zarówno mechanicznie (np. "zadaje 2k6 obrażeń ogniowych") jak i fabularnie (np. "z dłoni maga wylatuje kula płomieni"). Im bardziej konkretny opis, tym łatwiej będzie określić pozostałe parametry. Pamiętaj, że efekt powinien pasować do klimatu i lore świata Homebrew Magic.

2. Wybierz kategorię
Na podstawie głównego efektu zaklęcia przypisz mu jedną z dziesięciu kategorii: Obrażenia, Ochrona, Leczenie/Wsparcie, Ruch/Transport, Kontrola/Manipulacja, Iluzja/Oszukiwanie, Wykrywanie/Poznanie, Transmutacja, Nekromancja/Przyzwanie, lub Rytuały/Modlitwy. Każda kategoria ma swój unikalny modyfikator kosztu - na przykład zaklęcia bezpośrednio ofensywne są tańsze (modyfikator -0.4), a rytuały droższe (+1.3). Zaklęcia ochronne mają celowo dodatni modyfikator (+0.2): tarcze i bariery są zwykle łatwiejsze do rzucenia niż ataki o porównywalnej mocy, więc ich koszt many nie powinien być dodatkowo obniżany - dzięki temu przełamywanie osłon (patrz: zaklęcia oznaczone jako "przełamujące osłony") pozostaje opłacalną taktyką zamiast ślepej uliczki. Jeśli zaklęcie łączy kilka efektów, wybierz kategorię dominującego działania.

3. Ustal Potęgę Efektu
Jeśli zaklęcie ma efekt liczbowy skalujący się z Umiejętnością lub Atrybutem maga (obrażenia, punkty wytrzymałości tarczy, punkty leczenia itp.), wybierz jego Potęgę Efektu z Tabeli Potęgi Efektu - czyli jaką część wartości bazowej (zwykle Umiejętności Zdolności Magiczne) przekłada bezpośrednio na liczbę efektu. Zaklęcia bez skalującego się efektu liczbowego (czysto sytuacyjne, informacyjne, o stałej wartości) pomijają ten krok - ich Potęga Efektu wynosi "Nie dotyczy" (modyfikator 0,0). Ten sam krok dotyczy też bonusów z opcji Nadczarowania - jeśli dana opcja skaluje się kością zamiast stałą liczbą, jej moc również odczytaj z tej tabeli. Zaklęcia z kategorii Obrażenia zadają dodatkowo +1 punkt Obrażeń ponad wynik z tabeli ([Rodzaje Obrażeń](../../00.%20Podręcznik%20Gry/Rozdział%20V%20-%20Walka%20i%20Magia/Rodzaje%20Obrażeń.md)); ta premia jest wliczona w koszt kategorii i nie zmienia ceny.

4. Ustal parametry początkowe
Określ podstawowe parametry mechaniczne: Trudność (T) - najniższą wartość na k6 liczoną jako sukces (zwykle 4-6), oraz liczbę wymaganych Sukcesów (S). Proste zaklęcia mają T=4 i S=1, umiarkowane T=5 i S=1-2, a trudne T=6 z S=2-3. Te parametry odzwierciedlają wyłącznie to, jak trudno zapanować nad zaklęciem w praktyce - precyzję, kontrolę, ryzyko nieudanego rzutu - a nie siłę samego efektu, którą uwzględniłeś już w kroku 3. Te wartości stanowią fundament do obliczania końcowego kosztu many. Nowo tworzone zaklęcie nie może mieć Trudności niższej niż 4 - T=3 zarezerwowano dla kilku najprostszych zaklęć podstawowych (np. Poblask czy Wzniecanie Ognia). Pamiętaj też, że wyższe T i S same podnoszą koszt (krok 6 oraz modyfikatory "Trudny do rzucenia" i "Wysokie wymagania"), więc trudniejsze zaklęcie jest zarazem droższe i bardziej zawodne - nie podnoś ich bez potrzeby, a siłę efektu wyrażaj Potęgą Efektu i modyfikatorami efektów, nie parametrami T:S.

5. Zidentyfikuj modyfikatory
Przeanalizuj szczegółowe cechy swojego zaklęcia i zidentyfikuj pasujące modyfikatory efektów. Czy zaklęcie jest natychmiastowe (-1.0), a może trwa tylko jedną rundę (-0.5)? Działa na pojedynczy cel (-0.8)? Ma efekt obszarowy (+0.5)? Jest trudne do rzucenia (+0.5)? Czy wymaga wielu sukcesów (+0.8)? Następnie przyjrzyj się temu, co jeszcze robi efekt: czy ignoruje Pancerz (+1.0) albo przebija magiczną ochronę (+1.0), nakłada dodatkowe Stany (+0.5 za każdy), odbiera celowi Akcje (+1.0), daje premie lub kary do Testów (+0.2 za każdą kość, Sukces lub stopień Trudności), pozwala rzucić inne zaklęcie bez wydawania Many (+1.0) albo łamie zwykłe zasady gry (+1.5)? I odwrotnie - czy jego efekt jest drobny i czysto użytkowy (-1.0), a może nie da się go użyć w walce (-1.0)? Pełną listę znajdziesz w Tabeli modyfikatorów. Każdy modyfikator reprezentuje konkretną cechę wpływającą na trudność projektowania i użycia zaklęcia. Niektóre zaklęcia mogą mieć kilka modyfikatorów jednocześnie.

6. Oblicz koszt bazowy
Zastosuj podstawowy wzór matematyczny: koszt bazowy = 0,5 × (T + S). Na przykład, jeśli zaklęcie ma T=5 i S=2, to koszt bazowy wynosi 0,5 × (5+2) = 3,5. Ta wartość stanowi punkt wyjścia przed uwzględnieniem specyfiki kategorii i dodatkowych modyfikatorów. Wzór odzwierciedla podstawową zależność między trudnością rzucenia a kosztem energii magicznej.

7. Dodaj modyfikator kategorii
Do kosztu bazowego dodaj modyfikator odpowiadający wybranej kategorii zaklęcia. Na przykład, jeśli to zaklęcie ochronne (modyfikator +0.2), a koszt bazowy to 3,5, to po dodaniu modyfikatora otrzymujesz 3,5 + 0.2 = 3,7. Ten krok uwzględnia, że różne szkoły magii mają różną "naturalną" trudność i koszt energetyczny w świecie Homebrew Magic.

8. Dodaj modyfikatory efektów i Potęgi Efektu
Zsumuj wszystkie zidentyfikowane wcześniej modyfikatory efektów oraz modyfikator Potęgi Efektu z kroku 3 i dodaj je do wyniku. Jeśli zaklęcie ma modyfikatory "natychmiastowe" (-1.0), "pojedynczy cel" (-0.8) oraz Potęgę Efektu "Standardowa" (0,0), dodajesz łącznie -1.8 do poprzedniego wyniku. Kontynuując przykład: 3,7 + (-1.8) = 1,9. Ten etap precyzyjnie dostosowuje koszt do wszystkich szczególnych cech zaklęcia, łącznie z tym, ile faktycznie ono zdziała.

9. Zaokrąglenie do liczby całkowitej
Otrzymany wynik zaokrąglij do najbliższej liczby całkowitej, zachowując minimum 1 punkt many. **Uwaga - to wyjątek:** w całym systemie zwykle zaokrąglamy w górę, ale koszt many nowo tworzonego zaklęcia zaokrąglamy do najbliższej liczby (patrz: [Zaokrąglanie i Konwencje](../../Zaokrąglanie%20i%20Konwencje.md)). W naszym przykładzie 1,9 zaokrąglamy do 2. Jeśli wynik byłby np. 1,4, zaokrąglamy do 1. Jeśli wyszedłby 0 lub liczba ujemna, automatycznie ustalamy koszt na 1 punkt many - każde zaklęcie musi kosztować przynajmniej tyle energii magicznej. Na koniec sprawdź minimalny koszt zaklęć ofensywnych (patrz: Tabela modyfikatorów): zaklęcie z kategorii Obrażenia, którego Potęga Efektu wynosi co najmniej Standardowa, kosztuje nie mniej niż 2 punkty many (Wzmocniona - 3, Potężna - 4), nawet jeśli wzór dał niższy wynik.

10. Sprawdź balans
Porównaj swoje zaklęcie z podobnymi już istniejącymi w systemie. Czy zaklęcie o podobnych efektach ma zbliżony koszt? Jeśli porównanie tego wymaga, wynik z kroku 9 możesz skorygować o najwyżej 1 punkt many w górę lub w dół (ale nie poniżej minimalnego kosztu z kroku 9) - tak właśnie wyceniono część zaklęć z Księgi Magii (np. Szkarłatny Pocisk kosztuje o 1 punkt mniej, niż wynika ze wzoru). Jeśli jednak różnica względem podobnych zaklęć wynosi 2 lub więcej punktów many, nie poprawiaj samego kosztu - zmień parametry (T, S, czas działania, obszar), dopisz pominięty modyfikator albo dodaj ograniczenia (np. krótszy czas działania, dodatkowe komponenty, efekty uboczne). Pamiętaj też, że słabsi magowie nie są w stanie nauczyć się zaklęć droższych niż ich Maksymalny Koszt Zaklęcia - zaklęcie, które ma być dostępne dla magów niższych Poziomów, nie powinno kosztować więcej niż 4-5 punktów many. Ten etap zapewnia spójność z resztą systemu i zapobiega powstawaniu zaklęć zbyt mocnych lub zbyt słabych.

11. Zatwierdź z MG
Przedstaw gotowe zaklęcie Mistrzowi Gry do finalnej akceptacji. MG może zaproponować drobne korekty kosztu, parametrów lub dodać fabularne ograniczenia. Może też poprosić o doprecyzowanie opisu efektu lub dostosowanie zaklęcia do konkretnej kampanii. Nie traktuj tego jako krytykę - to normalny proces współtworzenia, który gwarantuje, że nowe zaklęcie będzie dobrze działać w grze i nie zakłóci balansu rozgrywki.
