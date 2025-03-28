#Blackjack

#CEL

Aplikacja webowa służy do symulacji gry w Blackjacka, 
popularnej gry karcianej, w której celem jest zdobycie punktów jak najbliżej 21, 
nie przekraczając tej wartości. Gracz rywalizuje z Dealer, a także ma możliwość obstawiania pieniędzy.

#ZASADA

Jak działa: 
1.Tworzenie talii kart: Program generuje talię kart składającą się z 52 kart (cztery kolory, 13 wartości). 
2.Rozdawanie kart: Gracz i Dealer otrzymują po dwie karty na początku gry. Gracz ma możliwość dobierania kolejnych kart (opcja "Dobierz Kartę") lub zatrzymania się (opcja "Zatrzymaj się"). 
3.Obliczanie punktów: Punkty są obliczane na podstawie wartości kart. As może mieć wartość 11 lub 1, w zależności od sytuacji. Gracz może przekroczyć 21 punktów, co kończy grę przegraną. 
4.Ruch Dealera: Po decyzji gracza, Dealer dobiera karty zgodnie z ustalonymi zasadami (zatrzymuje się, gdy ma 17 punktów lub więcej). 
5.Sprawdzanie zwycięzcy: Po wykonaniu ruchów przez gracza i krupiera, program porównuje wyniki i ogłasza zwycięzcę.

#INTERAKCJA Z UŻYTKOWNIKIEM

Interakcja z użytkownikiem pojawia się poprzez: 
-Przyciski kontrolne: Użytkownik ma dostęp do przycisków, które umożliwiają mu: Dobieranie kart, Zatrzymywanie się, Rozpoczęcie nowej gry. 
-Wprowadzanie kwoty zakładu: Użytkownik może wpisać kwotę, którą chce postawić przed rozpoczęciem gry. 
-Wyświetlanie wyników: Aplikacja na bieżąco wyświetla aktualne karty gracza i Dealera, ich punkty oraz stan konta gracza. 
-Powiadomienia o wynikach: Po zakończeniu rundy, użytkownik otrzymuje informację o wyniku (wygrana, przegrana, remis) oraz aktualny stan konta.


#ZMIANY Z BIEGIEM WERSJI APLIKACJI
W wersji 0.1 zostały stworzone kontenery w których będą się działy poszczególne rzeczy.
W wersji 0.2 dodano trzy przyciski: HIT, STAND, NEW GAME. Zostały również zastosowane i będą stosowane w przyszłości 5 zasad Clean Code: Refaktoryzacja, YAGNI(You Aren't Gonna Need It), KISS(Keep It Simple Stupid), DRY(Don't Repeat Yourself), SRP(Single Responsibility Principle).
W wersji 0.3 dodano karty do gry oraz punktacja(wartość karty) np. J = 10 punktów, Q = 10 punktów. Zostało również dodane funkcjonalności przycisków dodanych w poprzedniej wersji. Przycisk HIT dodaje graczowi jedną kartę, przycisk STAND kończy turę gracza i zaczyna turę dealera w której dealer dobiera karty i porównuje je z kartami gracza.
W wersji 0.4 dodano pole w którym znajdują się wszystkie rzeczy widziane przez użytkownika.
W wersji 0.5 zostały usunięte wszystkie nie potrzebne komentarze z kodu.
W wersji 0.6 zostały wprowadzone zmiany w nazwach zmiennych, funkcji oraz zaszły zmiany kosmetyczne typu zmiana czcionki lub pogrubienie tekstu.
W wersji 0.7 zostały znalezione błędy związane z funkcjonalnością przycisków HIT oraz STAND i brakiem wyświetlania się kart.
W wersji 0.8 dodano
W wersji 0.9 dodano
w wersji 1 dodano
