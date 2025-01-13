# Dokumentacja Projektu: System Detailingu Samochodowego

## Spis Treści

1. [Wstęp](#wstęp)

   [1.1 Cel Dokumentacji](#11-cel-dokumentacji)

   [1.2 Zakres Projektu](#12-zakres-projektu)

2. [Technologie i Narzędzia](#technologie-i-narzędzia)

    - [HTML5](#HTML5)
    - [JavaScript](#JavaScript)
    - [Microsoft SQL Server](#microsoft-sql-server)
    - [Bootstrap](#Bootstrap)
    - [Google Maps API](#Google-Maps-Api)

3. [Struktura Projektu](#Struktura-Projektu)

    - [Plik Strona.html](#Plik-Stronahtml)

    - [Plik Rezerwuj.html](#Plik-Rezerwujhtml)

4. [Funkcjonalności Aplikacji](#Funkdjonalność-Aplikacji)

   [4.1 Strona Główna](#41-Strona-Główna)

   [4.2 Formularz Rezerwacji](#42-Formularz-Rezerwacji)

5. [Stylizacja i Interfejs Użytkownika](#Stylizacja-i-Interfejs-Użytkownika)

   [5.1 Responsywność](#51-Responsywność)

6. [Możliwe Usprawnienia](#Możliwe-Usprawnienia)

7. [Kontakt](#Kontakt)

## 1. Wstęp

### 1.1 Cel Dokumentacji

Celem niniejszej dokumentacji jest przedstawienie szczegółowego opisu projektu systemu detailingu samochodowego. Dokumentacja ma ułatwić zrozumienie struktury plików, funkcjonalności aplikacji oraz możliwości dalszego rozwoju.

### 1.2 Zakres Projektu

Projekt obejmuje stworzenie strony internetowej dla firmy zajmującej się detailingiem pojazdów. System umożliwia przeglądanie oferty, kontakt z firmą oraz rezerwację terminów na wybrane usługi.

## 2. Technologie i Narzędzia

HTML5, CSS3, JavaScript

Podstawowe technologie front-endowe zostały wykorzystane do stworzenia struktury, stylizacji oraz interaktywności strony.

Bootstrap

Framework CSS pozwala na szybkie i efektywne tworzenie responsywnych układów strony.

Google Maps API

API umożliwia integrację mapy na stronie, pokazując lokalizację firmy.

## 3. Struktura Projektu

### 3.1 Plik Strona.html

Funkcjonalności:

Nawigacja po witrynie:

Oferta usług (np. mycie detailingowe, regeneracja lakieru).

Sekcja "O nas" z informacjami o firmie.

Sekcja kontaktowa z danymi teleadresowymi i mapą lokalizacji.

Prezentacja usług w formie wizualnej (zdjęcia, opisy).

Ważne elementy:

Preloader: Animacja ładowania strony.

Dynamiczna nawigacja: Menu rozwijane dla sekcji "Oferta" i "O nas".

Mapa Google: Zagnieżdżona ramka z lokalizacją.

### 3.2 Plik Rezerwuj.html

Funkcjonalności:

Formularz rezerwacji:

Pola na dane osobowe (imię, nazwisko).

Wybór usługi z rozwijanej listy.

Data rezerwacji.

Ważne elementy:

Responsywność: Formularz dostosowuje się do różnych rozdzielczości ekranu.

Walidacja: Wymagane pola są oznaczone, aby użytkownik wprowadził wszystkie niezbędne dane.

## 4. Funkcjonalności Aplikacji

### 4.1 Strona Główna

Banner: Wyświetla nazwę i slogan firmy.

Oferta Usług: Zdjecia z linkami do szczegółowych opisów usług.

Sekcja Kontaktowa: Dane firmy (adres, telefon, fax) oraz mapa z lokalizacją.

### 4.2 Formularz Rezerwacji

Pola formularza:

Imię i nazwisko klienta.

Marka i model pojazdu.

Wybór usługi i daty.

Przycisk przesyłania: Po zakończeniu wypełniania formularza dane mogą być przesłane (integracja z backendem nie jest zaimplementowana).

## 5. Stylizacja i Interfejs Użytkownika

### 5.1 Responsywność

Projekt został zoptymalizowany dla urządzeń mobilnych, tabletów i komputerów. Układ strony automatycznie dostosowuje się do wielkości ekranu.

## 6. Możliwe Usprawnienia

Dodanie Backend: Implementacja obsługi rezerwacji po stronie serwera.

Walidacja Klienta: Rozszerzenie walidacji danych wejściowych (np. poprawność formatu numeru telefonu).

System Powiadomień: Wysyłka e-maili z potwierdzeniem rezerwacji.

Rozbudowa Sekcji Oferta: Dodanie opinii klientów i galerii przed/po wykonaniu usługi.

## 7. Kontakt

Adres: Ul. Łowicka 1, 45-920 OpoleTelefon: (077) 123 123 123E-mail: kontakt@detailrob.pl

