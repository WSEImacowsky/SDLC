# Software Development Life-Cycle

## Project subject

Narzędzie do analizy lini brzegowej 

### Short description

Na podstawie danych satelitarnych analiza zmian linii brzegowej.


### Clients

  * Rząd
     - wsparcie polityk rządowych związanych z ochroną środowiska: 
        - minimalizacja kosztów i zasobów związanych z działaniami rządu w zakresie ochrony środowiska (poziom wód, linia brzegowa etc. )
        - wsparcie w zakresie informowania o zmianach klimatycznych 
        - wsparcie decyzji związanych w sytuacjach kryzysowych (katastrofy klimatyczne)
        - przewidywanie sytuacji kryzysowych ( katastrof klimatycznych etc.)
        - wsparcie instrumentów alarmowania kryzysowego


### Features

  * pozyskiwanie, obsługa i zarządzanie danymi (FUNCTIONALITY)
    - magazynowanie danych
    - metody pozyskiwania i przekształcania danych (ELT)
    - hurtownia danych 
    - obsługa danych (bieżących, historycznych i prognoz)
    - API - dostęp programistyczny do danych

  * informowanie  i ostrzeżeganie:
    - Alerty (rodzaje alertów)
    - prognozy (krótko i długoterminowe) - dynamiczne informowanie o krytycznych zmianach linii brzegowej i / lub prognozowanych stanów wód i pokrywy lodowej
    - prognozowanie poziommu zalesienia oraz zmian lini brzegowej (te dwa konkretne przypadki)
    - systemowe rekomendacje/doradztwo
    - informacja o obszarach, w których mogą pojawić się potencjalne koszty / zyski 

  * interfejs użytkownika:  
    - UX/UI - graficzny interfejs w formie strony/aplikacji webowej
    - raportowanie - możliwość tworzenia raportów w formie graficznej 
    - dashboardy, grafiki etc.

metodologia prognozowania:  
  
  * dane historyczne
  * dane bieżące 
  * UX/UI - wygodne przedstawienie danych (USABILITY) -> Dashboardy w Power BI



### Requirements

  * dane przechowywane w chmurze danych i powszechnie dostępne
  * częstotliwość pobierania danych (podstawa: co godzinę) pozwalająca na analizę wahań poziomu wód   w ciągu dnia
  * [DATA SOURCES](https://spacex.com.pl/wiadomosci/trzy-satelity-konstelacji-radarsat-zostaly-wyniesione-na-orbite)
  * [API](https://gbdxdocs.digitalglobe.com/docs/mda-radarsat-2)
  * FURPS (Functionality, Usability, Reliability, Performance, Supportability)
  * Możliwość definiowania alertów, rekomendacji, grafik

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
