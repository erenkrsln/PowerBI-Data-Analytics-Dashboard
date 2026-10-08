# Power BI – Dashboard zur Mitarbeiter- und Gehaltsanalyse

## 📊 Projektübersicht

Dieses Projekt beschäftigt sich mit der Analyse und Visualisierung von Umfragedaten aus dem IT- und Datenanalysebereich mithilfe von **Microsoft Power BI**.

Ziel des Projekts ist es, einen Rohdatensatz systematisch aufzubereiten, relevante Kennzahlen (KPIs) zu ermitteln und die Ergebnisse in einem interaktiven Dashboard übersichtlich darzustellen.

Dabei werden unter anderem Berufsbezeichnungen, Gehaltsstrukturen, bevorzugte Programmiersprachen, Branchen und weitere Merkmale der Umfrageteilnehmer untersucht.

## 🎯 Projektziele

- Bereinigung und Transformation von Rohdaten mit Power Query
- Strukturierte Aufbereitung der Daten für weitere Analysen
- Analyse von Gehaltsunterschieden zwischen Berufsgruppen
- Untersuchung bevorzugter Programmiersprachen
- Erstellung aussagekräftiger Kennzahlen (KPIs)
- Entwicklung eines interaktiven Power-BI-Dashboards
- Visualisierung von Zusammenhängen und Trends zur Unterstützung datenbasierter Entscheidungen

## 🛠️ Verwendete Technologien

| Technologie | Verwendung |
|---|---|
| Microsoft Power BI | Erstellung interaktiver Dashboards und Datenvisualisierungen |
| Power Query | Datenbereinigung und Transformation |
| Microsoft Excel | Verwaltung und Bereitstellung des Ausgangsdatensatzes |
| Datenmodellierung | Strukturierung und Aufbereitung der Analysedaten |
| KPI-Visualisierung | Darstellung relevanter Kennzahlen |

## 🔄 Datenbereinigung und Transformation

Vor der Erstellung des Dashboards wurden die Daten mithilfe von **Power Query** bereinigt und transformiert.

### 1. Entfernung irrelevanter Spalten

Nicht benötigte beziehungsweise vollständig leere Spalten wurden entfernt, um die Datenstruktur zu vereinfachen.

Dazu gehören beispielsweise:

- Browser
- OS
- City
- Country
- Referrer

### 2. Vereinheitlichung der Berufsbezeichnungen

Die ursprünglichen Berufsbezeichnungen wurden mithilfe der Funktion **Split Column by Delimiter** bearbeitet und in einheitliche Kategorien überführt.

Berücksichtigte Berufsgruppen:

- Data Analyst
- Data Architect
- Data Engineer
- Data Scientist
- Database Developer
- Other
- Student / Looking / None

Dadurch lassen sich die verschiedenen Berufsgruppen besser vergleichen und analysieren.

### 3. Aufbereitung der Programmiersprachen

Die Angaben zur bevorzugten Programmiersprache wurden ebenfalls bereinigt und kategorisiert.

Untersuchte Programmiersprachen:

- Python
- R
- JavaScript
- Java
- C/C++
- Other

Zusätzlich wurden die Angaben zu Branchen und Beschäftigungsländern vereinheitlicht.

### 4. Berechnung des durchschnittlichen Jahresgehalts

Die ursprünglichen Gehaltsangaben lagen teilweise als Gehaltsspannen vor, beispielsweise:

`125–150k`

Für die weitere Analyse wurden diese Angaben in numerische Werte umgewandelt.

Hierzu wurde der Mittelwert der jeweiligen Gehaltsspanne berechnet.

Beispiel:

`(125.000 + 150.000) / 2 = 137.500`

Diese Transformation ermöglicht eine einheitliche Auswertung der Gehaltsdaten und einen Vergleich zwischen verschiedenen Berufsgruppen.

Die berechneten Werte stellen Schätzungen auf Basis der angegebenen Gehaltsspannen dar.

## 📈 Dashboard und Datenvisualisierung

Auf Basis des bereinigten Datensatzes wurde ein interaktives Power-BI-Dashboard entwickelt.

Im Mittelpunkt stehen folgende Auswertungen:

- **Durchschnittliches Jahresgehalt:** Analyse der Gehaltsstruktur
- **Berufsgruppen:** Verteilung der Teilnehmer nach Tätigkeitsbereich
- **Programmiersprachen:** Vergleich der bevorzugten Technologien
- **Branchenanalyse:** Untersuchung der vertretenen Wirtschaftszweige
- **Geografische Verteilung:** Auswertung nach Beschäftigungsländern

Das Dashboard ermöglicht es, Informationen schnell zu erfassen und Unterschiede zwischen den untersuchten Kategorien zu erkennen.

## 💡 Erkenntnisse und Nutzen

Die Datenanalyse bietet eine strukturierte Grundlage, um Trends und Zusammenhänge innerhalb der Umfragedaten zu untersuchen.

Durch die Kombination aus Datenbereinigung, Transformation und Visualisierung lassen sich komplexe Informationen verständlich darstellen.

Das Projekt demonstriert insbesondere praktische Kenntnisse in:

- Datenanalyse und Datenaufbereitung
- ETL-Prozessen (Extract, Transform, Load)
- Business Intelligence
- Datenvisualisierung
- KPI-Erstellung und Interpretation
- Entwicklung interaktiver Dashboards

## 📁 Projektdateien

Die Projektdateien umfassen:

- **Power-BI-Datei (`.pbix`):** Interaktives Dashboard mit Datenmodell und Visualisierungen
- **Excel-Datei (`.xlsx`):** Datengrundlage für die Analyse
- **README.md:** Dokumentation des Projekts

## 🚀 Projekt lokal öffnen

1. Repository von GitHub herunterladen oder klonen.
2. Die `.pbix`-Datei mit Microsoft Power BI Desktop öffnen.
3. Falls erforderlich, den Pfad zur Excel-Datenquelle in Power Query aktualisieren.
4. Die Daten aktualisieren und das interaktive Dashboard erkunden.

## 📌 Fazit

Dieses Projekt zeigt den vollständigen Arbeitsablauf einer datengetriebenen Analyse – von der Bereinigung und Transformation eines Rohdatensatzes bis zur Entwicklung eines interaktiven Dashboards.

Der Schwerpunkt liegt auf dem praktischen Einsatz von **Power BI, Power Query, Datenmodellierung und KPI-Visualisierung**, um aussagekräftige Erkenntnisse aus strukturierten Daten zu gewinnen.