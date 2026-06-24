# Test Cases

## TC-01 Dodanie rezerwacji

### Cel testu

Sprawdzenie możliwości dodania nowej rezerwacji wizyty.

### Warunki wstępne

- Aplikacja została uruchomiona.
- Użytkownik znajduje się w menu głównym.

### Kroki testowe

1. Wybierz opcję dodania rezerwacji.
2. Wprowadź imię klienta.
3. Wprowadź nazwisko klienta.
4. Wprowadź datę wizyty.
5. Zatwierdź formularz.

### Oczekiwany rezultat

Nowa rezerwacja zostaje zapisana i jest widoczna na liście rezerwacji.

---

## TC-02 Wyświetlenie rezerwacji

### Cel testu

Sprawdzenie możliwości wyświetlenia zapisanych rezerwacji.

### Warunki wstępne

- W systemie istnieje co najmniej jedna rezerwacja.
- Aplikacja została uruchomiona.

### Kroki testowe

1. Wybierz opcję wyświetlenia rezerwacji.
2. Odczytaj wyświetloną listę rezerwacji.

### Oczekiwany rezultat

System wyświetla wszystkie zapisane rezerwacje wraz z danymi klienta i terminem wizyty.

---

## TC-03 Anulowanie rezerwacji

### Cel testu

Sprawdzenie możliwości anulowania istniejącej rezerwacji.

### Warunki wstępne

- W systemie istnieje co najmniej jedna rezerwacja.
- Aplikacja została uruchomiona.

### Kroki testowe

1. Wybierz opcję anulowania rezerwacji.
2. Wskaż rezerwację do usunięcia.
3. Potwierdź anulowanie.

### Oczekiwany rezultat

Wybrana rezerwacja zostaje usunięta z listy rezerwacji.

---

## TC-04 Zakończenie programu

### Cel testu

Sprawdzenie możliwości zamknięcia aplikacji.

### Warunki wstępne

- Aplikacja została uruchomiona.

### Kroki testowe

1. Wybierz opcję zakończenia programu.

### Oczekiwany rezultat

Program zostaje poprawnie zamknięty.
