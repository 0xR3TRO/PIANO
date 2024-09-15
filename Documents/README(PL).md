## Opis projektu

### Cel:

Projekt "PIANO" ma na celu dostarczenie użytkownikom prostego, ale funkcjonalnego internetowego pianina, zintegrowanego z przeglądarką. Użytkownicy będą mogli grać na wirtualnym instrumencie bez konieczności instalowania dodatkowego oprogramowania. Projekt będzie zachowany w estetyce retro, przywołując klimat starych gier i aplikacji internetowych, jednocześnie oferując nowoczesną funkcjonalność.

### Opis funkcji:

- **Gra na pianinie:** Użytkownicy mogą grać na wirtualnym pianinie, używając klawiatury swojego laptopa.
- **Dźwięki retro:** Odwzorowanie dźwięków klasycznych pianin i syntezatorów z lat 80.
- **Tryb pełnoekranowy:** Możliwość rozszerzenia aplikacji na cały ekran dla lepszego doświadczenia gry.
- **Minimalistyczna galeria nagrań:** Użytkownik może zapisać swoje krótkie utwory i przeglądać historię sesji.

## Analiza wymagań

### Wymagania funkcjonalne:

- **Wirtualne klawisze:** Każdy klawisz klawiatury laptopa będzie odpowiadał klawiszowi na wirtualnym pianinie.
- **Nagrywanie utworów:** Możliwość nagrania krótkich fragmentów muzycznych i ich odtwarzania.
- **Dostosowywanie dźwięków:** Użytkownik będzie mógł wybierać różne dźwięki instrumentów retro, takie jak klasyczne pianino, organy, czy syntezator.
- **Tryb pełnoekranowy:** Opcja przejścia w tryb pełnoekranowy dla większego komfortu gry.
- **Motyw retro:** Styl graficzny aplikacji utrzymany w klimacie retro (pikselowa grafika, neonowe kolory, ciemne tło).

### Wymagania niefunkcjonalne:

- **Płynność działania:** Szybka i responsywna interakcja z wirtualnym pianinem.
- **Kompatybilność przeglądarek:** Aplikacja będzie działać we wszystkich popularnych przeglądarkach (Chrome, Firefox, Safari).
- **Estetyka retro:** Klimat retro w wyglądzie i dźwiękach aplikacji.
- **Prostota interfejsu:** Intuicyjny, minimalistyczny design, aby użytkownicy mogli szybko rozpocząć grę bez skomplikowanych opcji.

## Projekt interfejsu

### Szkice/wizualizacje interfejsu:

- _Strona główna:_ Prostokątne pianino wyświetlone centralnie, z klawiszami, które reagują na naciśnięcia użytkownika.
- _Panel opcji:_ Na górze lub z boku strony będzie dostępny minimalistyczny panel z opcjami wyboru dźwięków, trybu pełnoekranowego i nagrywania.
- _Okno nagrywania:_ Mały prostokątny panel umożliwiający zapisanie krótkiego utworu i jego odtwarzanie.

### Mapa strony:

- _Strona główna_
  - Wirtualne pianino
  - Panel opcji (dźwięki, tryb pełnoekranowy, nagrywanie)
  - Historia zapisanych utworów (w minimalistycznej formie)

## Architektura systemu

### Opis struktury danych:

Aplikacja przechowuje dane o nagranych utworach i konfiguracji użytkownika:

- **Nagrania:** Krótkie pliki dźwiękowe zapisane w lokalnej pamięci przeglądarki.
- **Konfiguracja użytkownika:** Informacje o wyborze dźwięków i ustawieniach aplikacji.

### Diagramy architektury:

Aplikacja będzie działać w modelu MVC:

- **Model:** Odpowiada za logikę generowania dźwięków i zarządzania nagraniami.
- **Widok (View):** Prezentuje wirtualne pianino i inne elementy interfejsu.
- **Kontroler (Controller):** Zarządza komunikacją między widokiem a modelem, przetwarzając interakcje użytkownika (np. naciśnięcia klawiszy).

## Implementacja

### Opis technologii:

- **Frontend:** HTML, CSS, JavaScript (React.js) – prosta i lekka aplikacja w przeglądarce.
- **Backend:** Brak backendu – aplikacja opiera się na lokalnym zapisie w przeglądarce i nie wymaga serwera.
- **Baza danych:** Lokalna pamięć przeglądarki (LocalStorage) do przechowywania nagrań.

### Struktura kodu:

- _Katalogi/pliki:_ Oddzielne pliki dla logiki pianina, nagrywania, obsługi interfejsu oraz stylów.
- _Style pisania kodu:_ Zastosowanie modułowego podejścia do komponentów interfejsu (pianino, panel opcji).

## Testowanie

### Plan testów:

- **Testy jednostkowe:** Sprawdzenie poprawności działania klawiszy, interakcji z klawiaturą, nagrywania i odtwarzania.
- **Testy integracyjne:** Upewnienie się, że wszystkie komponenty interfejsu (pianino, panel opcji) działają razem poprawnie.
- **Testy kompatybilności:** Sprawdzenie działania aplikacji na różnych przeglądarkach i urządzeniach.
- **Testy wydajnościowe:** Ocena płynności generowania dźwięków w czasie rzeczywistym.

### Procedury testowania:

- Opracowanie przypadków testowych dla każdej funkcji, w tym dla działania pianina i nagrywania.
- Regularne sprawdzanie kompatybilności na różnych urządzeniach i przeglądarkach.

## Wdrożenie i konserwacja

### Plan wdrożenia:

- **Etapy wdrażania:** Testowanie wersji beta w przeglądarkach, poprawki błędów, finalne wydanie aplikacji.
- **Terminy:** Określenie dat wdrożeń wersji beta, testów i ostatecznego uruchomienia.

### Procedury konserwacji:

- **Wsparcie techniczne:** Umożliwienie zgłaszania błędów poprzez prosty formularz kontaktowy na stronie.
- **Aktualizacje:** Regularne aktualizacje związane z poprawą wydajności i naprawą błędów zgłaszanych przez użytkowników.

## Harmonogram

### Plan projektu:

- **Etapy realizacji:**
  - Projektowanie interfejsu (2 tygodnie)
  - Implementacja logiki pianina (4 tygodnie)
  - Testowanie i optymalizacja (2 tygodnie)
- **Terminy:** Projekt powinien być zrealizowany w ciągu 8 tygodni.

## Kosztorys

### Szacunkowe koszty:

- **Rozwój aplikacji:** Koszt pracy zespołu programistów (8 tygodni pracy, w zależności od stawek godzinowych).
- **Koszty utrzymania:** Minimalne, ponieważ aplikacja nie wymaga serwerów ani kosztownych zasobów, poza sporadycznymi aktualizacjami.
