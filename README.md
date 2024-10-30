# Analiza Danych Ekonomicznych

## Opis projektu
Notebook zawiera analizę danych demograficznych i ekonomicznych, które obejmują m.in. wiek, płeć, poziom wykształcenia, stanowisko zawodowe, branżę oraz poziom dochodów i wydatków. Projekt ma na celu lepsze zrozumienie struktury demograficznej oraz sytuacji ekonomicznej analizowanych osób.

## Zawartość analizy
1. **Ładowanie i wstępne przetwarzanie danych** - Notebook generuje przykładowe dane oraz ładuje dane z pliku `dane_dla_studentow2.csv`, które są następnie łączone w jedną ramkę danych. W tej sekcji znajdziesz również wstępne zapoznanie się z danymi, ich strukturą i podstawowymi statystykami.
2. **Analiza demograficzna**:
   - Analiza wieku, płci oraz poziomu wykształcenia.
   - Obliczenie średniego wieku, rozkładu płci oraz dominującego poziomu wykształcenia.
3. **Wizualizacja danych**:
   - Wykresy rozkładu wieku oraz analizowanych zmiennych.
   - **Rodzaje wykresów**:
     - **Histogramy** - do wizualizacji rozkładu zmiennych, takich jak wiek.
     - **Wykresy słupkowe** - pokazujące rozkład płci i poziomu wykształcenia.
     - **Regploty** - przedstawiające relacje między zmiennymi.
     - **Dendrogramy** - do analizy klasteryzacji.
     - **Mapa korelacji** - wykres pokazujący współzależności między zmiennymi liczbowymi.

## Użyte biblioteki
- **Pandas** - do wczytywania, przetwarzania i analizy danych.
- **Seaborn** - do tworzenia zaawansowanych wizualizacji, w tym wykresów rozkładu i mapy korelacji.
- **Matplotlib** - do wykresów podstawowych i dostosowywania wykresów.

## Wymagania
- `Python 3.x`
- Biblioteki: `pandas`, `matplotlib`, `seaborn`, `numpy`
