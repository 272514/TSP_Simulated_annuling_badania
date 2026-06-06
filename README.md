# TSP_Simulated_annuling_badania
## 📊 Dokumentacja eksperymentalna (/research)

Katalog `/ss_test` zawiera pełne archiwum zrzutów ekranu z przebiegu optymalizacji, dokumentujących każde z 5 uruchomień (*Run 1-5*) dla wszystkich wariantów badawczych. Archiwum zostało podzielone na 4 foldery zgodnie z parametrami testowymi z tabeli `tab_param`:

### 📂 Folder `T/` – Wpływ temperatury początkowej ($T_0$)
* **T1:** $T_0 = 100$ (test bardzo niskiej temperatury startowej – szybkie zamrożenie układu)
* **T2:** $T_0 = 1\,000$
* **T3:** $T_0 = 5\,000$
* **T4:** $T_0 = 50\,000$ (test bardzo wysokiej temperatury startowej – faza błądzenia losowego)
* *Punkt odniesienia:* Konfiguracja bazowa z temperaturą $T_0 = 10\,000$.

### 📂 Folder `A/` – Wpływ współczynnika chłodzenia ($\alpha$)
* **A1:** $\alpha = 0.90$ (bardzo szybkie schładzanie / hartowanie układu)
* **A2:** $\alpha = 0.95$
* **A3:** $\alpha = 0.99$ (patologicznie wolne chłodzenie – brak zbieżności i wysokie *acceptance rate* $\approx 30\%$)

### 📂 Folder `N/` – Skalowalność algorytmu (Rozmiar problemu)
* **N1:** $n = 50$ miast
* **N2:** $n = 150$ miast
* **N3:** $n = 200$ miast
* **N4:** $n = 300$ miast (duża instancja testowa, wymagająca zwiększenia budżetu iteracji)

### 📂 Folder `Z/` – Liczba prób na iterację (*zmiany_na_krok*)
* **Z1:** 20 prób na iterację (skrajnie mały budżet – przedwczesne zamrożenie w minimum lokalnym)
* **Z2:** 50 prób na iterację
* **Z3:** 200 prób na iterację
* **Z4:** 400 prób na iterację
