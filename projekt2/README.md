Projekt polega na stworzeniu pliku .fmw, który będzie pobierał informacje z usługi ULDK. Skrypt 
opiera się o zadeklarowane przez użytkownika parametry i umożliwia:

• Wybór działki po pełnym identyfikatorze

• Wybór działki po nazwie obrębu i numerze działki

• Wybór działki przez współrzędne X,Y zadeklarowane przez użytkownika jako tekst w układzie
EPSG:2180

• Wybór działek po współrzędnych wygenerowanych z pliku SHP zawierającego obiekty punktowe
Skrypt powinien pozwalać na dwa typy zapytania:

• Podstawowe, którego wynikiem powinien być obiekt (obiekty, w przypadku zapytania z pliku) z
własnościami:

    1. Geometria obiektu/obiektów wyświetloną w poprawnym miejscu w układzie
    EPSG:2180

    2. Numer działki

• Pełne, którego wynikiem powinien być obiekt/obiekty z własnościami:

    1. Geometria obiektu/obiektów wyświetlona w poprawnym miejscu w układzie
    EPSG:4326

    2. Identyfikator TERYT działki

    3. Gmina

    4. Powiat

    5. Województwo
    
    6. Imię, Nazwisko, Numer indeksu autora (w jednym atrybucie)

Wszytskie działania operte są  o geometrię WKB.

W momencie uruchomienia skryptu użytkownik ma możliwość zdecydowania o
tym, z której metody wyboru działki chciałby skorzystać i czy w wyniku chciałby otrzymać
odpowiedź pełną czy tylko podstawową.