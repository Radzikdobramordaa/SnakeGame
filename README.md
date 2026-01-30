SnakeGame – dokumentacja projektu
1. Opis projektu
SnakeGame to prosta gra konsolowa typu Snake, napisana w języku C#. Celem projektu było stworzenie działającej gry oraz przećwiczenie pracy zespołowej z wykorzystaniem systemu kontroli wersji Git oraz platformy GitHub. Projekt realizowany był w środowisku Visual Studio 2022 jako aplikacja konsolowa.
Gra polega na sterowaniu wężem poruszającym się po planszy. Zadaniem gracza jest zbieranie jedzenia, które powoduje wydłużanie się węża oraz zwiększanie wyniku punktowego. Gra kończy się w momencie kolizji węża ze ścianą lub z własnym ogonem.

2. Wykorzystane technologie
Język programowania: C#
Typ aplikacji: Aplikacja konsolowa
Środowisko programistyczne: Visual Studio 2022
Platforma: .NET Framework 4.7.2
Repozytorium zdalne: GitHub

3. Struktura projektu
Projekt składa się z następujących plików:

SnakeGame
│── Program.cs      // główna logika gry
│── Pixel.cs        // klasa reprezentująca segment węża
│── Obstakel.cs     // klasa reprezentująca jedzenie/przeszkody
│── SnakeGame.csproj
│── README.md

Opis plików:
Program.cs – zawiera pętlę gry, obsługę sterowania, logikę poruszania węża, kolizje oraz punktację.
Pixel.cs – definiuje pojedynczy element gry (segment węża).
Obstakel.cs – definiuje obiekt jedzenia pojawiający się na planszy.

4. Zasady gry
Wąż porusza się w sposób ciągły po planszy.
Gracz steruje kierunkiem ruchu za pomocą klawiszy strzałek.
Po zjedzeniu jedzenia:
wąż wydłuża się,
wynik punktowy zwiększa się o 1.
Gra kończy się, gdy:
wąż uderzy w ścianę,

6. Sterowanie
Klawisz	Akcja
Strzałka w górę	Ruch w górę
Strzałka w dół	Ruch w dół
Strzałka w lewo	Ruch w lewo
Strzałka w prawo	Ruch w prawo

Zmiana kierunku jest możliwa tylko wtedy, gdy nie powoduje natychmiastowego cofnięcia się węża w przeciwną stronę.

6. Praca zespołowa i GitHub
Projekt realizowany był z wykorzystaniem repozytorium GitHub zgodnie z następującymi zasadami:
Każda nowa funkcjonalność lub poprawka błędu realizowana była na oddzielnej gałęzi.
Błędy i pomysły na rozwój gry zgłaszane były w formie Issues.
Każde Issue było:
przypisane do konkretnego uczestnika,
powiązane z osobną gałęzią,
zamykane po scaleniu Pull Requesta.
Zmiany do gałęzi głównej (master) były wprowadzane wyłącznie poprzez Pull Requesty.

7. Instrukcja uruchomienia
Sklonuj repozytorium:
git clone https://github.com/TWOJ_LOGIN/SnakeGame.git
Otwórz plik SnakeGame.sln w Visual Studio 2022
Uruchom projekt skrótem:
F5 lub Ctrl + F5
Gra uruchomi się w oknie konsoli.
