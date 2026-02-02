# Fuel Watcher Dashboard

Dieses Repository enthält ein vollständiges Lovelace‑Dashboard für die Fuel‑Watcher‑Integration.

## Features

- Premium DataTables Tankhistorie  
- Popup‑Formulare für Tankvorgänge  
- Preisentwicklung  
- Verbrauchstrends  
- Navigation  
- Statusübersicht  
- Aktionen  

## Vorraussetzung

Installierte Fuel-Watcher Integration -> https://github.com/northpower25/homeassistant-fuel-watcher
Voraussetzung:
- custom:datatables-card installiert
- browser_mod installiert (für Popups)

## Installation (HACS)


1. HACS → Frontend → Benutzerdefinierte Repositories  
2. Repository hinzufügen:  
   `https://github.com/northpower25/fuel-watcher-dashboard`
3. Typ: **Dashboard**  
4. Installieren  
5. Dashboard importieren unter:  
   Einstellungen → Dashboards → Dashboard hinzufügen → „Rohkonfiguration importieren“

## Datei

Das Dashboard befindet sich unter:
dashboards/fuel_watcher_dashboard.yaml
