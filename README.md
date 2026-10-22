# Paletify – System Zarządzania Magazynem i Integracji z Allegro

**Paletify** to autorska aplikacja internetowa przeznaczona do zarządzania magazynem, ewidencji produktów oraz automatyzacji procesu przygotowywania ofert sprzedażowych na platformie Allegro.

Aplikacja została stworzona na potrzeby wewnętrzne i wspomaga codzienną obsługę asortymentu pochodzącego z palet towarowych.

## Główne funkcjonalności

### Zarządzanie magazynem
- Importowanie palet i produktów do bazy magazynowej.
- Ewidencja poszczególnych egzemplarzy produktów.
- Zarządzanie stanami produktów: nowy, powystawowy, używany i uszkodzony.
- Dodawanie notatek do poszczególnych egzemplarzy.
- Monitorowanie stanów magazynowych i sprzedaży.

### Integracja z katalogami produktów
- Wyszukiwanie produktów na podstawie identyfikatorów EAN i ASIN.
- Pobieranie informacji o produktach z zewnętrznych źródeł.
- Automatyczne uzupełnianie nazw, parametrów i opisów produktów.

### Integracja z Allegro REST API
- Autoryzacja konta za pomocą OAuth 2.0.
- Wyszukiwanie produktów w katalogu Allegro.
- Pobieranie parametrów i danych katalogowych.
- Przygotowywanie szkiców ofert sprzedażowych.
- Zarządzanie informacjami o ofertach.
- Wykorzystanie warunków sprzedaży i cenników dostaw skonfigurowanych na koncie Allegro.

### Automatyzacja ofert
- Generowanie opisów produktów z wykorzystaniem AI.
- Przygotowywanie tytułów i parametrów ofert.
- Przypisywanie stanu i informacji o konkretnym egzemplarzu produktu.
- Ograniczenie ręcznego wprowadzania danych podczas przygotowywania ofert.

## Allegro Sandbox

Integracja z Allegro jest rozwijana i testowana w środowisku **Allegro Sandbox**.

Aplikacja wykorzystuje Allegro REST API w celu usprawnienia procesu tworzenia i zarządzania ofertami sprzedażowymi.

## Informacje techniczne

- **Nazwa aplikacji:** Paletify – Magazyn Palet
- **Wersja:** 1.0.0
- **Typ aplikacji:** Wewnętrzna aplikacja internetowa
- **Integracja:** Allegro REST API
- **Autoryzacja:** OAuth 2.0 Authorization Code Flow z PKCE
- **Środowisko:** Allegro Sandbox

## Dostępność

Paletify jest prywatnym narzędziem przeznaczonym do użytku wewnętrznego.

Repozytorium służy wyłącznie jako publiczna dokumentacja informacyjna aplikacji. Kod źródłowy, dane użytkowników, klucze API oraz pozostałe elementy infrastruktury nie są udostępniane publicznie.

## Status projektu

Aplikacja jest aktywnie rozwijana. Integracja z Allegro Sandbox znajduje się na etapie wdrażania i testowania.
