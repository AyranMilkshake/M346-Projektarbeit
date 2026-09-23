# PaaS – Platform as a Service

## Definition

Bei **PaaS** stellt der Cloud-Anbieter nicht nur die Infrastruktur, sondern gleich eine ganze Plattform zur Verfügung: Betriebssystem, Laufzeitumgebung (z. B. für .NET, Java, Node.js), Datenbanken und Entwicklungswerkzeuge. Der Kunde muss sich nicht mehr um Server, Patches oder Betriebssystem-Updates kümmern, sondern konzentriert sich nur noch auf die Entwicklung und den Betrieb seiner eigenen Anwendung.

Im Vergleich zur Wohnungs-Analogie bei IaaS ist PaaS eher wie eine möblierte Wohnung: Küche, Bad und Grundausstattung sind vorhanden, man bringt nur noch die persönlichen Dinge (die eigene Applikation) mit.

## Wer verwaltet was?

| Schicht | Verantwortung |
|---|---|
| Anwendungen / Daten | Kunde |
| Laufzeitumgebung / Middleware | Anbieter |
| Betriebssystem | Anbieter |
| Virtualisierung | Anbieter |
| Server / Storage / Netzwerk (Hardware) | Anbieter |

## Typische Merkmale

- Schnellere Entwicklung, da Infrastruktur und Basiskomponenten bereits vorhanden sind
- Automatische Skalierung und Updates durch den Anbieter
- Weniger Kontrolle über die zugrundeliegende Umgebung als bei IaaS
- Gut geeignet für Entwicklerteams, die sich auf den Code statt auf den Betrieb konzentrieren wollen

## Beispiele

- Microsoft Azure App Service
- Google App Engine
- Heroku

## Weiterführende Links

- [Wikipedia: Platform as a Service](https://de.wikipedia.org/wiki/Platform_as_a_Service)
- [Microsoft Azure: Was ist PaaS?](https://azure.microsoft.com/de-de/resources/cloud-computing-dictionary/what-is-paas/)

---
Siehe auch: [IaaS](iaas.md) · [SaaS](saas.md) · [zurück zum README](../README.md)
