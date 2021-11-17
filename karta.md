# Temat: Rozpoznawanie języka migowego

## Autorzy
Jakub Łepek (146470), Mateusz Kaźmierski (143942)

## Problem
Istnieje wiele modelów sztucznej inteligencji, które radzą sobie z rozpoznawaniem gestów i mogą posłużyć do stworzenia aplikacji tłumaczącej język migowy. Chcemy pokazać, że gdyby nie rozwój sztucznej inteligencji, otrzymanie podobnych rezultatów byłoby trudniejsze, a dokładność znacznie mniejsza. 

## Metoda
Zamierzamy najpierw przefiltrować obraz i pozbyć się szumu. Znaleźć skórę człowieka i rozróżnić ręce od nóg i głowy. Znaleźć dłonie i ich krawędzie.
Niektóre gesty są dość statyczne, a inne dynamiczne. W przypadku tych drugich planujemy badać kilka obrazów.

Założenia:
- człowiek jest ubrany,
- Przechylenie kamery nie przekracza 80 stopni,
- osoba stoi, ewentualnie siedzi, ale nie leży, ani nie znajduje się w innej pozycji,
- gestykulujący nie posiada rękawiczek.

## Obsługiwane gesty:
todo

## Wyniki
Chcemy porównać wyniki z tym, co otrzymaliśmy za pomocą sztucznej inteligencji. Wyznacznikiem jakości algorytmu jest liczba rozpoznanych poprawnie gestów do ilości przedstawionych gestów oraz liczba gestów błędnie rozpoznanych, gdy osoba nie gestykulowała. Dane jesteśmy w stanie wygenerować sami, nagrywając siebie.
