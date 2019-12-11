## Project description

Analiza zmian linii brzegowej oraz poziomu zalesienia lądu (**te dwa konkretne przypadki**) na podstawie danych satelitarnych.


## Clients

### Rząd
  * wsparcie polityk rządowych związanych z ochroną środowiska: 
    - minimalizacja kosztów i zasobów związanych z działaniami rządu w zakresie ochrony środowiska (poziom wód, linia brzegowa etc. )
    - wsparcie w zakresie informowania o zmianach klimatycznych 
    - wsparcie decyzji związanych w sytuacjach kryzysowych (katastrofy klimatyczne)
    - przewidywanie sytuacji kryzysowych ( katastrof klimatycznych etc.)
    - wsparcie instrumentów alarmowania kryzysowego


## Features

  * Pozyskiwanie, obsługa i zarządzanie danymi (FUNCTIONALITY)
    - magazynowanie danych
    - metody pozyskiwania i przekształcania danych (ELT)
    - hurtownia danych 
    - obsługa danych (bieżących, historycznych i prognoz)
    - API - dostęp programistyczny do danych

  * Informowanie  i ostrzeżeganie:
    - alerty (rodzaje alertów)
    - prognozy (krótko i długoterminowe) - dynamiczne informowanie o krytycznych zmianach linii brzegowej i / lub prognozowanych poziomów zalesienia lądu
    - systemowe rekomendacje/doradztwo
    - informacja o obszarach, w których mogą pojawić się potencjalne koszty / zyski 

  * Interfejs użytkownika:  
    - **Aplikacja webowa** UX/UI - graficzny interfejs w formie strony/aplikacji webowej
    - **Microsoft Power BI** - informacje pozyskane z danych satelitarnych prezentowane w postaci interaktywnych raportów (map oraz wykresów)


## Prediction methodologies
  * Dane historyczne - gromadzone w hurtowni danych oraz poddawane obliczeniom matematycznym w celu zbudowania i udoskonalania modelu predykcyjnego
  * Dane bieżące - próbka kontrolna do porownania z wynikiem działania modelu predykcyjnego
  * UX/UI - wygodne przedstawienie danych (USABILITY) -> Dashboardy w Power BI


## Requirements
  * Dane przechowywane w chmurze danych i powszechnie dostępne
  * Częstotliwość pobierania danych satelitarnych (**podstawa: co godzinę**) pozwalająca na efektywną analizę
  * [Informacje o misji RADARSAT i przeznaczeniu satelit](https://spacex.com.pl/wiadomosci/trzy-satelity-konstelacji-radarsat-zostaly-wyniesione-na-orbite "RADARSAT"){:target="_blank"}
  * [Dostęp do danych satelitarnych (API)](https://gbdxdocs.digitalglobe.com/docs/mda-radarsat-2 "API"){:target="_blank"}
  * FURPS (Functionality, Usability, Reliability, Performance, Supportability)
  * Możliwość definiowania alertów, rekomendacji, grafik

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
