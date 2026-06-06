## 📊 Dokumentacja eksperymentalna (/ss_test)

Katalog `/ss_test` zawiera pełne archiwum zrzutów ekranu z przebiegu optymalizacji, dokumentujących każde z 5 uruchomień (*Run 1-5*) dla wszystkich wariantów badawczych (* `tab_param` – Zestawienie konfiguracji wszystkich scenariuszy) oraz zbiorcze podsumowania. Archiwum zostało podzielone na następujące foldery:

### 📂 Folder `Wyniki/`
* `tab_trasy` – Zbiorcze wyniki długości tras.
* `tab_czasu` – Czasy procesora dla poszczególnych testów.
* `tab_acc` – Końcowe współczynniki akceptacji ($acc$).

### 📂 Folder `Bazowe/`
Screeny z 5 uruchomień dla parametrów standardowych ($n=100$, $T_0=10\,000$, $\alpha=0.97$, $changes=100$)

### 📂 Folder `T/`
* **T1:** $T_0 = 100$
* **T2:** $T_0 = 1\,000$
* **T3:** $T_0 = 5\,000$
* **T4:** $T_0 = 50\,000$

### 📂 Folder `A/`
* **A1:** $\alpha = 0.90$
* **A2:** $\alpha = 0.95$
* **A3:** $\alpha = 0.99$

### 📂 Folder `N/`
* **N1:** $n = 50$ miast
* **N2:** $n = 150$ miast
* **N3:** $n = 200$ miast
* **N4:** $n = 300$ miast

### 📂 Folder `Z/` – Liczba prób na iterację (*zmiany_na_krok*)
* **Z1:** 20 prób na iterację
* **Z2:** 50 prób na iterację
* **Z3:** 200 prób na iterację
* **Z4:** 400 prób na iterację
