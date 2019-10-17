# Software Development Life-Cycle

## Project subject

Narzędzie do analizy lini brzegowej 

### Short description

Na podstawie danych satelitarnych analiza zmian linii brzegowej.


### Clients

  * Rząd
  * Organizacje proekologiczne
  * Fundacje
  * Instytucje biznesowe / firmy


### Features

  * prognozowanie (FUNCTIONALITY)
  * rekomendacje/ostrzeżenia (FUNCTIONALITY)
  * informacja o obszarach, w których mogą pojawić się potencjalne koszty / zyski (FUNCTIONALITY)
  * dane historyczne
  * dane bieżące 
  * UX/UI - wygodne przedstawienie danych (USABILITY) -> Dashboardy w Power BI


### Requirements 

  * częstotliwość pobierania danych (podstawa: co godzinę) pozwalająca na analizę wahań poziomu wód   w ciągu dnia
  * [DATA SOURCES](https://spacex.com.pl/wiadomosci/trzy-satelity-konstelacji-radarsat-zostaly-wyniesione-na-orbite)
  * [API](https://gbdxdocs.digitalglobe.com/docs/mda-radarsat-2)
  * FURPS (Functionality, Usability, Reliability, Performance, Supportability)

### Technology stack 

  * Maszyna wirtualna
  * Licencja Power BI Pro
  * Front-End:
    * JavaScript
    * Python
  * Back-End:
    * Microsoft SQL Server 2016
    * Bazy danych (SSMS)
    * SSIS
    * SSAS