# Opis
Zadaniem do wykonania w tym projekcie było zbudowanie modelu, który będzie klasyfikował punkty do jednej z czterech grup na podstawie jego cech (x1, x2, x3, x4).
# Implementacja
Zbiór danych został podzielony na zbiór uczący i zbiór testowy w stosunku 80% do 20%. Zastosowano również filtrowanie danych, aby zapewnić obecność każdej z grup w zbiorze uczącym. Użyto modeli Fuzzy c-Means, Decision Tree, Random Forest oraz ich modyfikacji.
# Podsumowanie
Udało się uzyskać dokładność (accuracy) na poziomie niemniejszym niż 90%.
# Jak używać?
1. Zainstalowanie platfomy KNIME https://www.knime.com/downloads
2. Otworzyć w aplikacji KNIME plik Grupowanie.knwf
3. W ustawieniach node Excel Reader upewnić się, że ścieżka do pliku Grupowanie.xlsx jest ustawiona poprawnie.
4. W tym samym node wybrać arkusz pliku xlsx, z którego mają być pobrane dane.
5. W nodach Partitioning można modyfikować podział na zbiór uczący i testowy poprzez parametr Relative[%]
6. Wyniki klasyfikacji można znaleźć w node Scorer przy każdym modelu.
