## Project description

Analiza zmian linii brzegowej oraz poziomu zalesienia lądu (**te dwa konkretne przypadki**) na podstawie danych satelitarnych.


## Clients

### Government
  - Wsparcie polityk rządowych związanych z ochroną środowiska: 
    - minimalizacja kosztów i zasobów związanych z działaniami rządu w zakresie ochrony środowiska (zmiany linii brrzegowej, zmiany poziomu zalesienia lądu )
    - wsparcie w zakresie informowania o zmianach klimatycznych 
    - wsparcie decyzji związanych w sytuacjach kryzysowych (katastrofy klimatyczne)
    - przewidywanie sytuacji kryzysowych ( katastrof klimatycznych etc.)
    - wsparcie instrumentów alarmowania kryzysowego


## Features

### Zarządzanie danymi (FUNCTIONALITY)
    - Hurtownia danych
      - pozyskiwanie danych
      - przekształcanie danych (ELT)
      - magazynowanie danych
    - Analizy predykcyjne na danych z hurtowni danych
    - Obsługa danych historycznych i bieżących
    - Dostęp programistyczny do danych - **API**

### Informowanie  i ostrzeżeganie (USABILITY)
    - **Informowanie:**
      - alerty (rodzaje alertów)
      - systemowe rekomendacje/doradztwo
    - **Ostrzeganie:**
      - prognozy (krótko i długoterminowe) - dynamiczne informowanie o krytycznych zmianach linii brzegowej i / lub prognozowanych poziomów zalesienia lądu
      - informacja o obszarach, w których mogą pojawić się potencjalne koszty / zyski

### Interfejs użytkownika:  
    - **Aplikacja webowa**:
      - zmiana sposobu prezentacji danych według stworzonych przez siebie zasad
      - zarządzanie alertami oraz rekomendacjami
      - zarządzanie paczkami danych udostępnianych przez API
    - **Microsoft Power BI** - informacje pozyskane z danych satelitarnych prezentowane w postaci interaktywnych raportów (map oraz wykresów)


## Prediction methodologies
  * Dane historyczne - gromadzone w hurtowni danych oraz poddawane obliczeniom matematycznym w celu zbudowania i udoskonalania modelu predykcyjnego
  * Dane bieżące - próbka kontrolna do porownania z wynikiem działania modelu predykcyjnego
  * UX/UI - wygodne przedstawienie danych (USABILITY) -> Dashboardy w Power BI


## Requirements
  * Dane przechowywane w chmurze danych i powszechnie dostępne
  * Częstotliwość pobierania danych satelitarnych (**podstawa: co godzinę**) pozwalająca na efektywną analizę
  * Predefiniowane alerty oraz rekomendacje
  * Dodawanie nowych alertów oraz rozbudowywanie rekomendacji przez aplikację webową

## Technology stack 
  * Azure Data Factory - środowisko produkcyjne
  * Microsoft Power BI Pro - raportowanie i wizualizacja danych
  * Front-end:
    * JavaScript
    * Python
  * Back-end:
    * Microsoft SQL Server 2016
    * Bazy danych (SSMS)
    * SQL Srver Integriation Services (SSIS)
    * SQL Server Analysis Services (SSAS)


## Additional informations
  * [Informacje o misji RADARSAT i przeznaczeniu satelit](https://spacex.com.pl/wiadomosci/trzy-satelity-konstelacji-radarsat-zostaly-wyniesione-na-orbite "RADARSAT")
  * [Dostęp do danych satelitarnych (API)](https://gbdxdocs.digitalglobe.com/docs/mda-radarsat-2 "API")




  * FURPS (Functionality, Usability, Reliability, Performance, Supportability)