#Klasyfikacja Wieloklasowa Pingwinów

##Wprowadzenie
Celem tego projektu jest klasyfikacja gatunków pingwinów na podstawie cech takich jak długość dzioba, głębokość dzioba, długość płetw i masa ciała. Dane zostały zaczerpnięte z pliku penguins.csv. Projekt obejmuje eksplorację danych oraz zastosowanie kilku modeli uczenia maszynowego do klasyfikacji gatunków pingwinów.

Zadanie obejmuje następujące kroki:

    Eksplorację zbioru danych.
    Przygotowanie danych do modelowania.
    Uczenie modeli klasyfikacyjnych.
    Porównanie wyników modeli i wyciągnięcie wniosków.

##Funkcjonalności
Projekt realizuje następujące etapy:

    Eksploracja danych:

    Podsumowanie statystyczne cech (średnia, odchylenie standardowe, itp.).
    Analiza korelacji między cechami.
    Wizualizacja rozkładów cech dla różnych gatunków pingwinów.
    Przygotowanie danych:

    Obsługa brakujących wartości (wypełnienie medianą).
    Standaryzacja cech.
    Podział danych na zestawy treningowe i testowe (80/20).
    Uczenie modeli:

    Przeprowadzenie klasyfikacji za pomocą pięciu algorytmów:
    K-Nearest Neighbors (KNN)
    Random Forest
    Logistic Regression
    AdaBoost
    Support Vector Machine (SVM)
    Ewaluacja modeli:

    Obliczenie metryk dla każdego modelu:
    Dokładność (accuracy).
    Precision, Recall, F1-Score.
    AUC (Area Under the Curve).
    Wizualizacja macierzy konfuzji.
    Porównanie krzywych ROC dla różnych modeli.

##Technologie
Projekt został stworzony z użyciem:

    Python: Język programowania użyty do analizy danych i uczenia modeli.
    Scikit-learn: Biblioteka do uczenia maszynowego.
    Pandas: Do manipulacji i analizy danych.
    Matplotlib/Seaborn: Do wizualizacji danych.

##Pliki projektu
    penguins.csv: Zbiór danych zawierający informacje o pingwinach.
    main.py: Główny skrypt, który realizuje cały proces eksploracji i klasyfikacji.
    requirements.txt: Lista bibliotek wymaganych do uruchomienia projektu.   