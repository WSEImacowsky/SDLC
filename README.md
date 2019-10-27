# Natural Environment Analitical Tool

## Project subject

Narzędzie do analizy lini brzegowej 

### Short description

Na podstawie danych satelitarnych analiza zmian mórz, oceanów, linii brzegowych oraz pokrywy lodowej. 
Dane pozyskane dzięki satelitom będą mogły zostać wykorzystane między innymi w rolnictwie przy klasyfikacji rodzajów gleby oraz w zarządzaniu kryzysowym podczas powodzi czy trzęsień ziemi.


### Clients

  * Rząd
    - wsparcie zarządzania kryzysowego
    - wsparcie polityk rządowych (morskiej, turystyki, rolnictwa/rybołówstwa, ochrony środowiska)
        - minimalizacja kosztów i zasobów związanych z działaniami w obrębie określonytch polityk
  * Organizacje proekologiczne
  * Fundacje
  * Instytucje biznesowe / firmy


### Features

  * pozyskiwanie, obsługa i zarządzanie danymi (FUNCTIONALITY)
    - hurtownia danych
    - model danych
    - metody pozyskiwania i przekształcania danych (ELT)
    - 



metodologia prognozowania
  * rekomendacje/ostrzeżenia (FUNCTIONALITY)
  * informacja o obszarach, w których mogą pojawić się potencjalne koszty / zyski (FUNCTIONALITY)
  * dane historyczne
  * dane bieżące 
  * UX/UI - wygodne przedstawienie danych (USABILITY) -> Dashboardy w Power BI
  * Alerty ( dynamiczne informowanie o krytycznych zmianach linii brzegowej i / lub prognozowanych stanów wód i pokrywy lodowej)


### Requirements 

  * częstotliwość pobierania danych (podstawa: co godzinę) pozwalająca na analizę wahań poziomu wód   w ciągu dnia
  * [DATA SOURCES](https://spacex.com.pl/wiadomosci/trzy-satelity-konstelacji-radarsat-zostaly-wyniesione-na-orbite)
  * [API](https://gbdxdocs.digitalglobe.com/docs/mda-radarsat-2)
  * FURPS (Functionality, Usability, Reliability, Performance, Supportability)

### Technology stack 

  * Środowisko produkcyjne - Azure Data Factory
  * Licencja Power BI Pro
  * Front-End:
    * JavaScript
    * Python
  * Back-End:
    * Microsoft SQL Server 2016
    * Bazy danych (SSMS)
    * SSIS
    * SSAS
