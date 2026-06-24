# Bug Reports

## BUG-01 Brak walidacji pustego imienia

### Priorytet

Średni

### Kroki do odtworzenia

1. Uruchom aplikację.
2. Wybierz opcję dodania rezerwacji.
3. Pozostaw pole imienia puste.
4. Wprowadź nazwisko.
5. Wprowadź datę wizyty.
6. Zatwierdź formularz.

### Aktualny rezultat

System zapisuje rezerwację pomimo braku imienia klienta.

### Oczekiwany rezultat

System powinien wyświetlić komunikat o błędzie i zablokować zapisanie rezerwacji.

---

## BUG-02 Możliwość dodania rezerwacji z datą z przeszłości

### Priorytet

Wysoki

### Kroki do odtworzenia

1. Uruchom aplikację.
2. Wybierz opcję dodania rezerwacji.
3. Wprowadź poprawne dane klienta.
4. Wprowadź datę wcześniejszą niż bieżąca.
5. Zatwierdź formularz.

### Aktualny rezultat

System zapisuje rezerwację z datą z przeszłości.

### Oczekiwany rezultat

System powinien zablokować zapisanie rezerwacji i wyświetlić komunikat o nieprawidłowej dacie.

---

## BUG-03 Anulowanie wszystkich wizyt zamiast wybranej wizyty

### Priorytet

Krytyczny

### Kroki do odtworzenia

1. Dodaj co najmniej dwie rezerwacje.
2. Wyświetl listę rezerwacji.
3. Wybierz jedną rezerwację.
4. Kliknij opcję anulowania.
5. Potwierdź operację.

### Aktualny rezultat

System usuwa wszystkie zapisane rezerwacje.

### Oczekiwany rezultat

System powinien usunąć wyłącznie wybraną rezerwację.

---

## BUG-04 Błąd przy wyświetlaniu pustej listy rezerwacji

### Priorytet

Niski

### Kroki do odtworzenia

1. Uruchom aplikację.
2. Upewnij się, że w systemie nie ma żadnych rezerwacji.
3. Wybierz opcję wyświetlenia rezerwacji.

### Aktualny rezultat

System wyświetla nieczytelny komunikat lub zwraca błąd.

### Oczekiwany rezultat

System powinien wyświetlić komunikat:

„Brak zapisanych rezerwacji”.

---

## BUG-05 Nieprawidłowe zamknięcie programu

### Priorytet

Średni

### Kroki do odtworzenia

1. Uruchom aplikację.
2. Wybierz opcję zakończenia programu.

### Aktualny rezultat

Program nie kończy działania lub wyświetla błąd.

### Oczekiwany rezultat

Program powinien zostać poprawnie zamknięty bez wyświetlania błędów.
