Wersje 1-2 oparte na metodzie rozwiązywania równań różniczkowych. Rozwiązuje dobrze same równania i dopasowuje krzywe, ale złożenie nie przypomina tego czego byśmy oczekiwali.

Wersje 4 zmiana sposobu generowania rozwiązań do nauki sieci, metoda MC. Przewiduje bardz dobrze dla losowych warunków brzegowych z przedziału [0, 1],

Wersja 5 różni się od 4 tylko tym że dodajemy dziure w środku układu zadanym rozmiarze. 

Wersja 6 próbuje nauczyć sieć dla rozmiaru dziury z pewnego przedziału. Z werjsi 5 i 6 (jak i potem z 7) można dojść do wniosku, że najlepiej działa deklarowanie stałego rozmiaru dziury, 
ale jeśli zadany przedział rozmiarów nie jest za duży to sieć daje sobie nawet radę.

Werjsa 7 sprawdza jak radzi sobie "activation='tanh'" dodatkowo poza "activation='relu'". Nie widzę jakiś zancznych popraw w wyniakach. Co jest ciekawe natoamist to można spokojnie zrobić sieć na tanh zamiast relu i daje to bardzo podobne wyniki.

Werjsa 8 zamiast kwadratu w środku mamy koło, co chyba jest protsze dla sieci do nauki.
