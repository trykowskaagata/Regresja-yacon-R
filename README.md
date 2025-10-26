# Regresja-yacon-R
Projekt regresji liniowej w R na danych yacon. 
## Cel projektu:
Celem projektu była analiza statystyczna mająca na celu zbadanie zależności poziomu glukozy w bulwach yacon od wybranych cech fizykochemicznych rośliny. Dane pochodziły z pakietu agricolae (zbiór yacon) i zostały ograniczone do obserwacji, w których zmienna locality przyjmuje wartość "CAJ".
- Zmienna objaśniana (Y): glucose
- Zmienne objaśniające:
- fructose – (X1)
- sucrose – (X2)
- brix – (X3)
- roots – (X4)
  
Zakres analizy obejmował następujące etapy:
- budowa modelu regresji liniowej z wszystkimi zmiennymi objaśniającymi (X1–X4),
- diagnostyka modelu, w tym analiza reszt, wykresów diagnostycznych oraz testów statystycznych poznanych na zajęciach,
- ocena współzależności liniowej pomiędzy zmiennymi X1–X4 w celu identyfikacji potencjalnej kolinearności,
- selekcja zmiennych do modelu z maksymalnie dwiema zmiennymi objaśniającymi, z wykorzystaniem metod eliminacji wstecznej i dołączania (stepwise selection),
- walidacja modelu poprzez podział danych na zbiór uczący (70%) i testowy (30%). Modele wybrane w poprzednim kroku zostały wytrenowane na zbiorze uczącym, a ich skuteczność oceniono na zbiorze testowym na podstawie sumy kwadratów błędów (SSE).
Projekt został zrealizowany w środowisku R, z wykorzystaniem narzędzi do modelowania statystycznego, wizualizacji oraz oceny jakości modeli predykcyjnych.
