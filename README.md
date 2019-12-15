## Project description

Analiza zmian linii brzegowej oraz poziomu zalesienia lądu (**te dwa konkretne przypadki**) na podstawie danych satelitarnych.


## Clients

### Government
  - Wsparcie polityk rządowych związanych z ochroną środowiska:
    - minimalizacja kosztów i zasobów związanych z działaniami rządu w zakresie ochrony środowiska
    - wsparcie w zakresie informowania o zmianach linii brzegowej i/lub poziomu zalesienia lądu
    - wsparcie decyzji związanych w sytuacjach kryzysowych (optymalizacja wydatków)
    - przewidywanie interwencji w obszarach zmian linii brzegowej i/lub poziomu zalesienia lądu
    - wsparcie instrumentów alarmowania kryzysowego


## Features
* **Zarządzanie danymi (FUNCTIONALITY)**
    - Hurtownia danych
      - pozyskiwanie danych
      - przekształcanie danych (ELT)
      - magazynowanie danych
    - Analizy predykcyjne w oparciu o dane z hurtowni danych
    - Obsługa danych historycznych i bieżących
    - Dostęp programistyczny do danych - **API**

* **Informowanie  i ostrzeżeganie (USABILITY)**
    - **Informowanie:**
      - alerty (rodzaje alertów)
      - systemowe rekomendacje/doradztwo
    - **Ostrzeganie:**
      - prognozy krótko i długoterminowe - dynamiczne informowanie o krytycznych zmianach linii brzegowej i / lub prognozowanych poziomów zalesienia lądu
      - informacja o obszarach, w których mogą pojawić się potencjalne koszty

* **Interfejs użytkownika (USABILITY)**
    - **Aplikacja webowa**:
      - zmiana sposobu prezentacji danych według stworzonych przez siebie zasad
      - zarządzanie alertami oraz rekomendacjami
      - zarządzanie paczkami danych udostępnianych przez API
    - **Microsoft Power BI**: 
      - przetworzone informacje z danych satelitarnych prezentowane w postaci interaktywnych raportów (dashboard'ów, map oraz wykresów)
      - udostępnianie raportów innym pracownikom


## Prediction methodologies
  * Dane historyczne - gromadzone w hurtowni danych oraz poddawane obliczeniom matematycznym w celu zbudowania i udoskonalania modelu predykcyjnego
  * Dane bieżące - próbka kontrolna do porownania z wynikiem działania modelu predykcyjnego


## Requirements
  * Dane przechowywane w chmurze danych i powszechnie dostępne (API)
  * Częstotliwość pobierania danych satelitarnych (**podstawa: co godzinę**) pozwalająca na efektywną analizę (**PERFORMANCE**)
  * Predefiniowane alerty oraz rekomendacje w aplikacji webowej
  * Dodawanie nowych alertów oraz rozbudowywanie rekomendacji przez aplikację webową

## Technology stack 
  * Azure Data Factory - środowisko produkcyjne
  * Microsoft Power BI Pro - raportowanie i wizualizacja danych
  * Front-end:
    * JavaScript
    * Python
  * Back-end:
    * Microsoft SQL Server 2016
    * SQL Server Management Studio - baza danych
    * SQL Srver Integriation Services (SSIS) - pobieranie i ładowanie danych do hurtowni danych
    * SQL Server Analysis Services (SSAS) - przetwarzanie danych przez modele analityczne (kostki OLAP)


## Additional informations
  * [Informacje o misji RADARSAT i przeznaczeniu satelit](https://spacex.com.pl/wiadomosci/trzy-satelity-konstelacji-radarsat-zostaly-wyniesione-na-orbite "RADARSAT")
  * [Dostęp do danych satelitarnych (API)](https://gbdxdocs.digitalglobe.com/docs/mda-radarsat-2 "API")


### Authors
  * Karol Szarek | Jakub Maszkowski | Maciej Mleczko **copyright ©. All right reserved**