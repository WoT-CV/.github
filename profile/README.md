# Projekt WoT-CV

## Roadmap

### Release 1.0
**Inicjalna wersja projektu, która zawiera podstawowe założone funkcjonalności.**

- Funkcjonalności:
    - Logowanie się za pomocą `OpenID`
    - `Strona główna witryny`
    - `Strona rejestracji`
    - `Strona graczy do spradzenia`
    - Popup z newsami
    - Możliwość kupna konta premium za pomocą `Stripe`, `PayPal`, `Przelewy24`
    - Dodanie następujących paneli:
        - `Panel admina`
        - `Panel filtrów`
        - `Panel konta premium`
        - `Panel newsów`
- Lista TODO:
    - Dodanie przycisku w `Panel admina` który ręcznie będzie triggerował odświeżenie dostępów użytkowników klanu
    - Dodanie blokady na pobranie więcej niż `10` graczy do sprawdzenia na `dobę` dla użytkowników `non-premium`
    - Możliwość kupna konta premium za pomocą `Stripe`, `PayPal`, `Przelewy24`
        - należy zaimplementować integrację z payment providerami
    - Dodanie następujących `schedulerów`:
        - `Odświeżanie dostępów graczy co 5minut`
        - `Odświeżanie danych graczy do sprawdzenia którzy grali w wot'a co 4 godziny`
        - ``

### Release 1.1
**Wersja ma rozwinąć kluczowe funkcjonalności 1.0 oraz wprowadzić kilka nowych rozwiązań.**

- Funkcjonalności:
    - Dodanie stron `historia rekrutacji` oraz `statystyki rekrutacji` w których będzie można przejrzeć skuteczność
      rekruterów jak i samej rekrutacji
  
### Release 2.0
**Wersja ma wprowadzić nowy moduł automatu do rezerw klanowych**

- Funkcjonalności:
    - TODO
