# SSN. Lab. 8. Tensorflow i Keras 

Zapoznaj się z zawartością notatnika Jupyter umieszczonego w repozytorium  i wykonaj zawarte w nim ćwiczenia.

Notatnik: [tensorflow_keras.ipynb](https://github.com/IS-UMK/ssn_23_lab_08/blob/master/tensorflow_keras.ipynb)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/IS-UMK/ssn_23_lab_08/blob/master/tensorflow_keras.ipynb) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/IS-UMK/ssn_23_lab_08/master?filepath=tensorflow_keras.ipynb)

---

## Zad. 8. Porównanie algorytmów optymalizacji na MNIST

Porównaj szybkość zbieżności oraz jakość uzyskiwanych wyników głębokiej sieci MLP na zbiorze MNIST dla następujących metod optymalizacji:
* SGD
* SGD z momentem 
* SGD z momentem Nesterova
* Adadelta
* Adagrad
* Adam

Dla każdego algorytmu przeprowadź trening w jak najbardziej zbliżonych warunkach, tj z tą samą architekturą, stałą uczenia, liczbą epok, wielkością paczki, regularyzacją itd. Do porównania wybierz architekturę posiadającą więcej niż 2 warstwy ukryte o takiej liczbie neuronów i takiej funkcji aktywacji, która zbiega się w rozsądnym czasie dla bazowego algorytmu SGD dając dobre wyniki (min. 90% poprawności). 
Przedstaw (najlepiej na wspólnym wykresie) przebieg funkcji kosztu treningowego w kolejnych epokach treningu. Wypisz poprawność klasyfikacji uzyskaną na zbiorze testowym dla każdego modelu. 

Zob. lista algorytmów optymalizacji Keras: https://keras.io/api/optimizers/#available-optimizers

Rozwiązanie w postaci notatnika Jupyter (``.ipynb``) lub skrypt w języku Python (``.py``) umieść w Moodle lub prześlij do repozytorium GitHub.

---
## Materiały:

* [Keras: Getting started](https://keras.io/getting_started/)




