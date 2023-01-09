
# Wykorzystanie usług chmury Azure do przetwarzania i wizualizacji danych sprzedażowych

> Proponowane rozwiązanie mojego problemu zawiera komponenty, które nie tylko są w środowisku Azure ale także w środowisku Microsoft 365 czyli modelu SAAS.

W ostatnich latach chmura obliczeniowa stała się niezwykle popularnym narzędziem do przetwarzania i przechowywania danych. W niniejszej pracy inżynierskiej zostaną przedstawione metody wykorzystania usług chmury Azure do generowania raportów sprzedaży fikcyjnego przedsiębiorstwa zajmującego się sprzedażą międzynarodową.

...

Omówić SaaS, PaaS, IaaS. Wstępnie zaprezentować Azure SQL Database, Azure App Service, Power BI. Zaprezentować architekturę rozwiązania. Zaprezentować testy i wyniki.


W chwili obecnej większość rozwiązań tworzonych na platformie Azure jest tworzoana z wykorzystanianiem modelu PAAS. Stąd też podjąłem decyzję i moje rozwiązanie oprę o model PAAS.


W pierwszej części pracy zostaną omówione podstawowe pojęcia związane z chmurą obliczeniową oraz zostaną przedstawione usługi oferowane przez platformę Azure. W ramach projektu zostanie wykorzystana usługa Azure SQL Database do przechowywania danych sprzedażowych, usługa Azure App Service do przetwarzania danych z użyciem technologii ASP.NET, oraz usługa Power BI do tworzenia interaktywnych raportów i wizualizacji danych. Na zakończenie pracy zaprezentowano przeprowadzone testy oraz osiągnięte wyniki.

Chmura obliczeniowa jest rozwiązaniem, które pozwala na wykorzystanie zasobów komputerowych w sposób elastyczny i skalowalny. Dla dewelopera jest to duża oszczędność czasu pracy i energii, bo zamiast wdrażać całą architekturę aplikacji od początku może przerzucić część odpowiedzialności na infrastrukturę chmury i skorzystać z gotowych komponentów.

Jednym z najpopularniejszych dostawców usług chmur obliczeniowych jest platforma Microsoft Azure. Pierwszego lutego 2010 roku została zaprezentowana publiczna wersja platformy. Platforma oferuje m.in. usługi przechowywania baz danych, aplikacji webowych, przechowywania plików oraz dostarczania maszyn wirtualnych.

Baza danych SQL Azure jest usługą chmurową, która oferuje możliwość przechowywania danych w chmurze. Jest to usługa bazodanowa, która oferuje możliwość tworzenia baz danych, tabel, indeksów, widoków, procedur składowanych, funkcji oraz innych obiektów bazodanowych. Baza danych SQL Azure jest elastyczna i skalowalna, co pozwala na łatwe dostosowanie jej do potrzeb użytkownika.
?!--------------------------- WEBAPI,REST.......... DOCKER
Usługa Azure App Service to usługa chmurowa, która oferuje możliwość tworzenia aplikacji webowych. Pozwala na tworzenie aplikacji webowych m.in. w technologiach .NET, GO, PHP, Node.js, Java, Python oraz Ruby.

W pracy zostanie wykorzystany serwis napisany w języku C# z użyciem technologii ASP.NET. Serwis będzie wykorzystywał usługę Azure SQL Database do przechowywania danych sprzedażowych oraz usługę Azure App Service do przetwarzania danych.

Język C# jest obecnie jednym z najpopularniejszych języków programowania, o bardzo szerokich zastosowaniach w branży IT. Jest to język obiektowy, który oferuje możliwość tworzenia aplikacji webowych, aplikacji desktopowych, aplikacji mobilnych, aplikacji konsolowych oraz aplikacji serwerowych Program napisany w tym języku jest kompilowany do kodu natywnego dla platformy .NET. Program jest wykonywany przez środowisko uruchomieniowe zainstalowane w systemie operacyjnym.

Platforma ASP.NET to platforma programistyczna, która oferuje możliwość tworzenia aplikacji webowych. Pozwala na tworzenie aplikacji webowych w technologiach ASP.NET Web Forms, ASP.NET MVC, ASP.NET Web Pages oraz ASP.NET SignalR. Platforma ASP.NET oferuje również możliwość tworzenia aplikacji mobilnych w technologiach Xamarin, Cordova oraz React Native.
--- cos więcej b o to nie tylko raporty, ale i data set, automtyczne odswierxzanie danych , security etc.... PowerBIService , PowerBI API
Usługa Power BI to usługa chmurowa, która oferuje możliwość tworzenia interaktywnych raportów i wizualizacji danych. Pozwala na tworzenie raportów w technologiach Power Query, Power Pivot, Power View oraz Power Map. Usługa Power BI oferuje również możliwość tworzenia aplikacji mobilnych w technologiach iOS, Android oraz Windows Phone.