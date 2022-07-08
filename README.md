# Praca magisterska

Repozytorium zawiera notatniki wykorzystane do napisania pracy magisterskiej: ***,,Przewidywanie zachowań konsumentów w sklepach e-commerce z wykorzystaniem modeli uczenia maszynowego''***, obronionej 06.07.22 na ocenę 5.

Spis treści:
* [Lista plików](#0)
* [Streszczenie pracy](#1)

## Lista plików <a name="0"></a>

* `mag_eda.ipynb` - eksploracja jednego ze zbiorów danych użytych w pracy
* `NMADwB_raport.ipynb` - raport opisujący pracę magisterską, przygotowany na zajęcia
* `Przewidywanie` - folder zawiera pliki, w których przygotowano przewidywanie zachowań klientów:
  - `cały_okres_przewidywanie_bez_segmentacji.ipynb` - przygotowanie i porównanie modeli służących do przewidywania zachowań klientów bez dodawania segmentów
  - `cały_okres_przewidywanie_z_segmentacja.ipynb` - przygotowanie i porównanie modeli służących do przewidywania zachowań klientów po dodaniu segmentów
  - `data_prep_cały_okres_przewidywanie_concat.ipynb` - przygotowanie danych
* `Segmentacja` - folder zawiera pliki, w których przygotowano segmenty klientów:
  - `cały_okre_rfm.ipynb` - przygotowanie cech do analizy RFM
  - `cały_okres_segmentacja.ipynb` - segmentacja klientów według cech stworzonych w analizie RFM
  - `data_prep_purchase.ipynb` - przygotowanie danych
* `Tygodniowa sprzedaż` - folder zawiera pliki, w których przygotowano cechy oznaczające tygodniową sprzedaż oraz średnią cenę produktów:
  - `weekly_sales_concat.ipynb` - połączenie danych
  - `weekly_sales_data_prep.ipynb` - testowano przewidywanie liczby sprzedanych produktów, ostatecznie wykorzystano przygotowany zbiór do dodania cechy odpowiadającej za wielkość sprzedaży danego produktu w tygodniu, użytej w ostatecznym przewidywaniu zachowań klientów
  
Liczba plików i ich struktura wynika z ograniczeń sprzętowych.

## Streszczenie pracy <a name="1"></a>

Głównym celem pracy jest wykazanie, że segmentacja klientów może zostać wykorzystana do bardziej dokładnego przewidywania zachowań klientów sklepów e-commerce z wykorzystaniem modeli uczenia maszynowego. Tezę pracy zdefiniowano następująco: wykorzystanie metody segmentacji behawioralnej klientów sklepów e-commerce w procesie przewidywania zachowań zakupowych indywidualnych klientów pozwala na dokładniejsze modelowanie ich zachowań, niż bez dokonywanej segmentacji. Aby zrealizować cel pracy posłużono się analizą literatury związanej z branżą handlu elektronicznego, zachowaniami konsumentów oraz uczeniem maszynowym.
Praca składa się pięciu rozdziałów. Pierwszym rozdziałem jest wstęp, który przedstawia motywację autora do podjęcia tematu, a także wyjaśnia cele oraz określa strukturę pracy. Drugi rozdział opisuje podstawowe zagadnienia związane z branżą e-commerce oraz zachowaniami konsumentów. Kolejny rozdział pracy opisuje czym jest uczenie maszynowe oraz przedstawia podział rodzajów modeli uczenia maszynowego. W rozdziale tym zawarto także opis wybranych modeli uczenia maszynowego i omówiono przykładowe zastosowania uczenia maszynowego w branży e-commerce. Czwarty rozdział pracy zawiera opis przygotowanego przez autora badania, w którym porównano wybrane modele uczenia maszynowego oraz jakość dokonywanych przez nich predykcji zachowań klientów na zbiorze danych zawierającym, oraz niezawierającym segmentów klientów. Ostatni rozdział pracy zawiera podsumowanie pracy, omówienie realizacji celu głównego pracy oraz przedstawia możliwe kierunki dalszych badań.
Otrzymane wyniki pozwoliły na realizację celu głównego pracy oraz na udowodnienie tezy, że wykorzystanie metody segmentacji behawioralnej klientów sklepów e-commerce w procesie przewidywania zachowań zakupowych indywidualnych klientów pozwala na dokładniejsze modelowanie ich zachowań, niż bez dokonywanej segmentacji.
