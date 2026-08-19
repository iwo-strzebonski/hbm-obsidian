---
tags:
  - rule
  - ksiega-magii
  - spellcasting-theory
  - overcasting
aliases:
  - Zasada Nadczarowywania Zaklęć
---
Każde zaklęcie można nadczarować, wykorzystując dodatkową manę. Wartość koniecznej many do nadczarowania zaklęcia jest równa wielokrotności bazowego kosztu many.

Koszt many rośnie z każdym Poziomem Nadczarowania liniowo, ale jego efekt już nie. Pierwsze dwa Poziomy Nadczarowania danego zaklęcia dają bonus (obrażenia, kości, punkty wytrzymałości itp.) w pełnej wysokości. Każdy kolejny Poziom Nadczarowania - trzeci i dalsze - daje bonus zmniejszony o połowę, zaokrąglony w dół (przy bonusach z kości: rzuć kością tak jak zwykle, a wynik podziel przez 2 w dół; przy bonusach o stałej wartości: podziel tę wartość przez 2 w dół, przy czym bonus nigdy nie spada poniżej 1). Dzięki temu drobne przeszarżowanie mocą pozostaje tak samo opłacalne jak dotychczas, ale wlewanie całej dostępnej many w jedno zaklęcie przestaje być liniowo coraz silniejsze.

> **Przykład**: Mag B nadczarowuje Kulę Ognia (bazowy koszt 2 many) o trzy Poziomy zamiast dwóch. Pierwsze dwa Poziomy dają pełne +1k3 obrażeń każdy. Trzeci Poziom, mimo że kosztuje tyle samo many co poprzednie, daje już tylko połowę bonusu - mag rzuca 1k3 i dzieli wynik przez 2 w dół (minimum 1).

W związku z tym, że nadczarowywując dane zaklęcie, zwiększa się jego koszt many, wartość many potrzebna do rzucenia zaklęcia może przekroczyć wartość Maksymalnego Kosztu Zaklęcia.

Jak normalnie mag jest ograniczony kosztem zaklęcia jeśli chodzi o posługiwanie się maną - dlatego też słabsi magowie nie są w stanie nauczyć się potężniejszych zaklęć - tak znane zaklęcia można nadczarowywać ponad wartość Maksymalnego Kosztu Zaklęcia. Wiąże się to oczywiście z utrudnieniami:

Postać musi wykonać test na Magia (Zdolności Magiczne), gdzie Trudność (T)  jest zależna od bazowego kosztu zaklęcia: 
* 4:S, jeżeli bazowy koszt many jest nie większy niż 2
* 5:S, jeżeli bazowy koszt many jest nie większy niż 4
* 6:S, jeżeli bazowy koszt many jest nie mniejszy niż 5.

Ilość Wymaganych Sukcesów (S) rośnie nieliniowo wraz z ilością many, która przekroczyła Maksymalny Koszt Zaklęcia (oznaczaną dalej jako E) - im mocniej mag przekracza swoje możliwości, tym nieproporcjonalnie trudniej jest opanować nadmiar mocy. Wymagana liczba Sukcesów wynosi:

S = E × (E + 1) / 2

| Przekroczenie Maksymalnego Kosztu Zaklęcia (E) | Wymagane Sukcesy (S) |
| :---: | :---: |
| 1 | 1 |
| 2 | 3 |
| 3 | 6 |
| 4 | 10 |
| 5 | 15 |
| 6 | 21 |

Niewielkie przekroczenie własnych możliwości pozostaje więc mniej więcej tak samo osiągalne jak dotychczas, ale każdy kolejny punkt Many ponad Maksymalny Koszt Zaklęcia kosztuje nieproporcjonalnie więcej Sukcesów - "nadczarowywanie nadczarowania" powinno być rzadkim, ryzykownym wyczynem, a nie standardową taktyką.

W wypadku nieudanego testu mag musi natychmiast skorzystać z zasady Kar za Nieudolność (patrz: [02. Klątwa Otchłani](../../02.%20Klątwa%20Otchłani.md)), rzucając tyloma kośćmi na tabelę Kar za Nieudolność, ile zabrakło mu Sukcesów do zdania Testu.

> **Przykład**: Mag A, który jest magiem IV poziomu, chce nadczarować Magiczną Tarczę o dwa poziomy. Zaklęcie, które normalnie kosztuje punkty 2 many, będzie kosztowało 6 punktów many. Jako mag IV poziomu maksymalny koszt zaklęcia dla niego wynosi zaledwie 4, co oznacza, że przekroczył swój maksymalny koszt (E) o 2, w związku z czym mag A musi wykonać Test na Zdolności Magiczne (Magia) 4:3 (S = 2×3/2 = 3).
