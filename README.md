# rfm-analyse-sql
Dieses Projekt berechnet RFM-Metriken (Recency, Frequency, Monetary) sowie zusätzliche Kennzahlen wie Tenure und Basket Size auf Kundenbasis mithilfe von SQL. Ziel ist es, eine Segmentierung der Kunden auf Grundlage ihres Kaufverhaltens zu ermöglichen.
# RFM-Analyse für Einzelhandelskunden

Dieses Projekt berechnet RFM-Metriken (Recency, Frequency, Monetary) sowie zusätzliche Kennzahlen wie Tenure und Basket Size auf Kundenbasis mithilfe von SQL. Ziel ist es, eine Segmentierung der Kunden auf Grundlage ihres Kaufverhaltens zu ermöglichen.

## Voraussetzungen

- SQL Server oder kompatibles RDBMS
- Eine Tabelle `retail_II` mit den folgenden Spalten:
  - `Customer_ID`
  - `Invoice`
  - `InvoiceDate`
  - `Quantity`
  - `Price`

## Beschreibung der Metriken

- **Recency**: Tage seit dem letzten Kauf bis zum 01.01.2012
- **Frequency**: Anzahl der eindeutigen Einkäufe
- **Monetary**: Gesamtausgaben des Kunden
- **Tenure**: Zeitraum seit dem ersten Kauf bis zum 01.01.2012
- **Basket Size**: Durchschnittlicher Einkaufswert
- **Segmente**: Kunden werden in Gruppen wie 'Champions', 'At Risk' oder 'Loyal Customers' klassifiziert
