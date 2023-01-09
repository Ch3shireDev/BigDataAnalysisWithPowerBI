# Wykorzystanie narzędzi chmury Azure do przetwarzania i wizualizacji danych sprzedażowych

Implementacja ćwiczenia `Big data analytics and visualization` robiona w ramach pracy inżynierskiej.

## Harmonogram

1. [ ] Przeczytać [Cloud Design Patterns](https://learn.microsoft.com/en-us/azure/architecture/patterns/)
2. [ ] Zapoznać się ze wzorcami architektonicznymi (event-driven, n warstw).
3. [ ] Do końca grudnia wykonać ćwiczenia z `Big data analytics and visualization` (zacząć od `Before HOL`)
4. [ ] Do końca grudnia wykonać ćwiczenia z `PL-300: Microsoft Power BI Data Analyst`. Użyć przykładu AdventureWorks2020.
5. [ ] Zapoznać się z `AZ-204: Developing Solutions for Microsoft Azure`.
6. [ ] Zapoznać się z `AZ-400: Designing and Implementing Microsoft DevOps Solutions`
7. [ ] Zapoznać się z `MS-600: Building Applications and Solutions with Microsoft 365 Core Services`
8. [ ] Do końca grudnia złożyć niezbędne dokumenty do pracy inżynierskiej
9. [ ] Zapoznać się z Azure DevOps i automatyzacją wysyłania rozwiązania do chmury.
10. [ ] Przejrzeć stronę www.sqlbi.com oraz zapoznać się z DAX Studio i użyciem języka DAX w Power BI.
11. [ ] W styczniu być gotowym na przepytanie z dziedzin poruszanych w/w opisach:

    - użycie języka DAX w Power BI
    - użycie Verti Paq w Power BI

12. Wygenerować story - zaawansowaną motywację biznesową dla omawianych działań w projekcie
13. Zapoznać się z konceptem hurtowni danych (Bill Inmon, Ralph Kimball)
14. [Web-Queue-Worker architecture style](https://learn.microsoft.com/en-us/azure/architecture/guide/architecture-styles/web-queue-worker)

## Przybliżona struktura projektu

```mermaid
graph LR
    SQL[Baza danych SQL] --> BACKEND
    SQL --> POWERBI[Prezentacja danych Power BI]
    POWERBI --> BACKEND[ASP.NET]
```


World Wide Importerts to baza danych firmy, która zajmuje się importem i eksportem towarów. W tej bazie danych znajdują się dane dotyczące klientów, zamówień, produktów, dostawców, itp. W tym ćwiczeniu będziemy pracować z bazą danych AdventureWorks2020, która jest dostępna w Azure Data Studio. Baza danych zawiera dane dotyczące sprzedaży produktów w sklepach. W tej bazie danych znajdują się dane dotyczące klientów, zamówień, produktów, dostawców, itp.

This is an overview of the fictitious company Wide World Importers and the workflows that are addressed in the WideWorldImporters sample databases for SQL Server and Azure SQL Database.

Wide World Importers (WWI) is a wholesale novelty goods importer and distributor operating from the San Francisco bay area.

https://learn.microsoft.com/en-us/sql/samples/wide-world-importers-what-is?view=sql-server-ver16


Czyli chcemy analizować hurtownie danych, które są w Azure Data Studio.

Chcielibyśmy analizę poziomu marż na poszczególne produkty w poszczególnych krajach jako podpowiedź w formie raportu dla prezesa firmy w jakich krajach jest najlepiej wdrażać strategie komercyjne jakich produktów.


Ustawić rok fiskalny dla 1 stycznia (dla uproszczenia).

PowerBI wymaga autentykacji.

