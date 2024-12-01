Projekt polega na stworzeniu plik .fmw, który będzie pobierał informacje z usługi WFS Banku Danych o
Lasach, a następnie po odpowiednich przetworzeniach zapisywał wyjściowe informacje do
plików w formatach GML i KML.

Wytyczne co do projektu:

• Proszę wybrać dowolną Regionalną Dyrekcję Lasów Państwowych i pobrać informacje
o wydzieleniach dla tego RDLP z serwisu WFS Banku Danych o Lasach

• Proszę pobrać z usługi WFS Banku Danych o Lasach informacje na temat nadleśnictw i
wybrać dowolne nadleśnictwo należące do wcześniej wybranej RDLP.

• Proszę utworzyć w skrypcie dwa transformery RandomNumberGenerator, jeden z nich
niech wyznacza liczbę AA z zakresu 30-70, drugi liczbę BB z zakresu 80-120.

1. Na podstawie powyższych informacji proszę wygenerować plik GML, w którym znajdą
się wydzielenia typu Drzewostan, które leżą w obrębie wybranego przez państwa
nadleśnictwa, a ich wiek zawiera się w zakresie AA-BB (losowo wygenerowanym)

2. Dla wybranych według powyższych warunków obiektów proszę także wygenerować
wystylizowany plik formatu KML, w którym po wybraniu obiektu wyświetlają się
informacje o wieku, typie siedliska, powierzchni wydzielenia i informacji czy znajduje
się ono pod ochroną.
