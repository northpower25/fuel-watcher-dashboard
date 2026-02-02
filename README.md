# Fuel Watcher Dashboard

Dieses Repository enthält ein vollständiges Lovelace‑Dashboard für die Home‑Assistant‑Integration  
[homeassistant-fuel-watcher](https://github.com/northpower25/homeassistant-fuel-watcher).

## Features

- Premium‑Tankhistorie mit DataTables  
- Popup‑Formulare für Tankvorgänge  
- Preisentwicklung  
- Verbrauchstrends  
- Navigation zur empfohlenen Tankstelle  
- Statusübersicht & Aktionen  

## Installation über HACS

1. In HACS → Frontend → „Custom repositories“  
2. Repository hinzufügen:  
   `https://github.com/northpower25/fuel-watcher-dashboard`  
   Typ: **Dashboard**
3. Repository installieren
4. In Home Assistant:  
   **Einstellungen → Dashboards → Dashboard hinzufügen → Rohkonfiguration importieren**
5. Inhalt aus `dashboards/fuel_watcher_dashboard.yaml` einfügen oder Datei direkt auswählen (je nach Setup).

## Voraussetzungen

- Integration: `homeassistant-fuel-watcher`  
- Optional:  
  - `browser_mod` (für Popup‑Dialoge)  
  - `custom:datatables-card` (für die Tankhistorie‑Tabelle)
