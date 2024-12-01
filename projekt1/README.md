Projekt polega na stworzeniu skryptu .fmw, który:

ZADANIE A

• Utworzy numeryczny model terenu z pliku tekstowego i na jego podstawie wypiętrzy budynki znajdujące się na terenie Kalisza

• Wyznaczy te budynki, które znajdują się całkowicie powyżej (115+X) m n.p.m, gdzie X to ostatnia cyfra numeru indeksu

• Pogrupuje budynki wyznaczone w poprzednim punkcie według obrębów i zapisze je do oddzielnych plików Shapefile (Budynki z każdego obrębu w oddzielnym pliku)

ZADANIE B

• Zamieni geometrie obrębów z poligonów na linie i poprawi ich topologię

• Wyznaczy dwa węzły sieci – położony maksymalnie na wschód i maksymalnie na zachód (najdalej wysunięty węzeł =/= najbardziej wysunięty punkt)

• Wykorzysta wygenerowane wcześniej linie jako sieć dróg i wyznaczy najkrótszą trasę po sieci
między tymi punktami

• Obliczy różnicę (w kilometrach) między długością wyznaczonej trasy, a odległością między tymi
punktami w linii prostej i dopisze ją jako atrybut tej trasy

• Zapisze wyznaczoną trasę do pliku KMZ.