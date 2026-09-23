# IaaS – Infrastructure as a Service

## Definition

Bei **IaaS** mietet man von einem Cloud-Anbieter nur die rohe IT-Infrastruktur: virtuelle Server (Rechenleistung, Arbeitsspeicher), Speicherplatz und Netzwerk. Der Anbieter kümmert sich um die physische Hardware, die Virtualisierung und die Verfügbarkeit des Rechenzentrums. Alles darüber – Betriebssystem, Laufzeitumgebung, Applikationen und Daten – liegt in der Verantwortung des Kunden.

Man kann sich IaaS wie das Mieten einer leeren Wohnung vorstellen: Wände, Strom und Wasseranschluss sind vorhanden, aber Möbel, Einrichtung und Deko muss man selbst mitbringen.

## Wer verwaltet was?

| Schicht | Verantwortung |
|---|---|
| Anwendungen / Daten | Kunde |
| Laufzeitumgebung / Middleware | Kunde |
| Betriebssystem | Kunde |
| Virtualisierung | Anbieter |
| Server / Storage / Netzwerk (Hardware) | Anbieter |

## Typische Merkmale

- Hohe Flexibilität, da man das Betriebssystem und alle darüberliegenden Schichten frei wählen kann
- Abrechnung nach Verbrauch (pay-as-you-go)
- Skalierbar: Ressourcen können bei Bedarf erhöht oder reduziert werden
- Mehr Verwaltungsaufwand für den Kunden als bei PaaS oder SaaS

## Beispiele

- Amazon EC2 (AWS)
- Microsoft Azure Virtual Machines
- Google Compute Engine

## Weiterführende Links

- [Wikipedia: Infrastructure as a Service](https://de.wikipedia.org/wiki/Infrastructure_as_a_Service)
- [AWS: What is IaaS?](https://aws.amazon.com/what-is/iaas/)

---
Siehe auch: [PaaS](paas.md) · [SaaS](saas.md) · [zurück zum README](../README.md)
