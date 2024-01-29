
Odpowiedzi na pytania z ćwiczenia:

Losowy Podział Punktów
1. Dlaczego sieć osiąga tak niską skuteczność trenowania na wskazanym zbiorze?


Złożoność danych: Zbiór danych może zawierać różnorodne kształty i rozkłady, co utrudnia klasyfikację, zwłaszcza dla prostszych modeli.
Architektura modelu: Prostsza architektura modelu może nie być wystarczająco zdolna do dopasowania się do złożonych danych.
Liczba epok: Niewystarczająca liczba epok treningowych może nie pozwolić modelowi na efektywną naukę. 

2. Czy jest coś, co można zrobić, aby klasyfikator poprawił jakość trenowania?

Zwiększenie złożoności modelu: Dodanie warstw i neuronów może pomóc w lepszym dopasowaniu do danych.
Dopasowanie hiperparametrów: Eksperymentowanie z różnymi wartościami współczynników uczenia i innych hiperparametrów.
Zwiększenie liczby epok: Dłuższy trening może poprawić dopasowanie modelu do danych.
Techniki regularyzacji: Stosowanie dropoutu czy normalizacji warstw może zmniejszyć ryzyko przeuczenia.
Inżynieria cech: Przygotowanie danych w sposób, który ułatwia klasyfikację.
Podział Gaussa
1. Dlaczego wyniki trenowania są lepsze niż w poprzednim zbiorze?

Rozróżnialność danych: Zmodyfikowany zbiór trenujący, wykorzystujący podział Gaussa, generuje bardziej oddzielone dane, co ułatwia naukę i klasyfikację.
Zwiększenie liczby epok: Pozwala modelowi na lepsze dopasowanie się do bardziej złożonych danych.
2. Czy architektura sieci ma znaczny wpływ na jakość klasyfikacji?

Tak, wybór architektury sieci jest kluczowy dla klasyfikacji, włączając w to liczbę warstw, neuronów i typ funkcji aktywacji.
3. Czy szybkość trenowania ma wpływ na jakość klasyfikacji?

Tak, odpowiednia szybkość trenowania jest ważna dla uniknięcia przeuczenia oraz zapewnienia odpowiedniej dokładności.
4. Czy rodzaj optymalizatora ma wpływ na jakość klasyfikacji?

Tak, wybór optymalizatora ma znaczenie dla uniknięcia problemów, takich jak zatrzymanie w minimum lokalnym, i wpływa na skuteczność uczenia się modelu.
