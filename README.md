1.	Dlaczego sieć osiąga tak niską skuteczność trenowania na wskazanym zbiorze.
Sieć może osiągać niską skuteczność trenowania na wskazanym zbiorze danych z kilku powodów:
Złożoność danych: Zbiór danych wygenerowany w kodzie zawiera różnorodne kształty i rozkłady, co może sprawić, że klasyfikacja staje się trudniejsza, zwłaszcza dla modelu o prostszej architekturze.
Architektura modelu: Wybrana architektura modelu (liczba warstw i neuronów na warstwę, rodzaj aktywacji) może nie być wystarczająco złożona, aby dobrze dopasować się do danych.
Liczba epok: W przypadku niskiej liczby epok treningowych model może nie zdążyć nauczyć się wystarczająco dużo informacji z danych.

2.	Czy jest coś co można zrobić aby klasyfikator poprawił jakość trenowania?
Aby poprawić jakość trenowania klasyfikatora, można podjąć kilka działań:
Zwiększyć złożoność modelu: Można spróbować zwiększyć liczbę warstw i/neuronów na warstwę w modelu, aby dać mu większą zdolność do nauki złożonych wzorców w danych.
Dopasować hiperparametry: Tuning hiperparametrów, takich jak współczynniki uczenia, może pomóc w poprawie jakości trenowania. Warto eksperymentować z różnymi wartościami tych hiperparametrów.
Zwiększyć liczbę epok: Dłuższy trening może pomóc modelowi w lepszym dopasowaniu się do danych. Jednak należy uważać, aby uniknąć przeuczenia.
Zastosować inne techniki regularyzacji: Można spróbować zastosować techniki regularyzacji, takie jak dropout czy normalizacja warstw, aby zmniejszyć ryzyko przeuczenia.
Inżynieria cech: W niektórych przypadkach inżynieria cech może pomóc w ułatwieniu zadania klasyfikacji poprzez dostarczenie modelowi bardziej istotnych informacji.
Ostatecznie, poprawa jakości trenowania może wymagać eksperymentowania z różnymi konfiguracjami modelu, hiperparametrów i technik, a także analizy danych w celu lepszego zrozumienia ich charakterystyki.
