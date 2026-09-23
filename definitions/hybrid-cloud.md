# Hybrid Cloud

## Definition

Eine **Hybrid Cloud** kombiniert zwei oder mehr Umgebungen – typischerweise eine Private Cloud oder OnPremise-Infrastruktur mit einer Public Cloud. Die einzelnen Umgebungen bleiben eigenständige Systeme, sind aber über Netzwerktechnologien so miteinander verbunden, dass Daten und Anwendungen zwischen ihnen ausgetauscht werden können.

So kann ein Unternehmen z. B. sensible Daten OnPremise oder in der eigenen Private Cloud behalten, während es für Spitzenlasten oder weniger kritische Anwendungen zusätzliche Kapazität aus der Public Cloud bezieht ("Cloud Bursting").

## Aufbau (vereinfacht)

```
 ┌────────────────────┐        sichere Verbindung        ┌────────────────────┐
 │   Private Cloud /   │ <──────────(VPN / Direct)──────> │    Public Cloud     │
 │     OnPremise        │                                  │  (z.B. AWS, Azure)  │
 │  sensible Daten,     │                                  │  skalierbare Last,  │
 │  kritische Systeme   │                                  │  Web-Anwendungen    │
 └────────────────────┘                                  └────────────────────┘
```

## Typische Merkmale

- Kombination der Vorteile von Private Cloud (Kontrolle, Sicherheit) und Public Cloud (Skalierbarkeit, Kosten)
- Flexible Verteilung von Workloads je nach Anforderung (z. B. Datenschutz vs. Rechenleistung)
- Höhere Komplexität, da mehrere Umgebungen integriert und verwaltet werden müssen

## Vor- und Nachteile

**Vorteile:** Flexibilität, optimale Nutzung vorhandener Ressourcen, Skalierbarkeit bei Lastspitzen

**Nachteile:** komplexere Verwaltung und Integration, höhere Anforderungen an Netzwerk und Sicherheit zwischen den Umgebungen

## Beispiele

- Ein Unternehmen betreibt seine Kundendatenbank OnPremise, nutzt aber AWS für die öffentliche Webseite
- Microsoft Azure Arc / Azure Stack für hybride Szenarien

## Weiterführende Links

- [Wikipedia: Hybrid Cloud](https://de.wikipedia.org/wiki/Cloud-Computing#Hybrid_Cloud)

---
Siehe auch: [OnPremise](onpremise.md) · [Public Cloud](public-cloud.md) · [Private Cloud](private-cloud.md) · [zurück zum README](../README.md)
