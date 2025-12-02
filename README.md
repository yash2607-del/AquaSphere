# AquaSphere — Water Monitor Mobile App 

A cross-platform Flutter app to explore and analyze groundwater level data across India, backed by a lightweight FastAPI service that serves cleaned CSV datasets. The app features an interactive map with 31,000+ water monitoring stations, dataset browsing, charts, and basic analytics.

---

## Features
- Interactive India map with boundaries and 31k+ station markers
- Station details and quick focus on map
- Dataset list and paginated record fetch from backend
- Time-series charting using `fl_chart`
- Lightweight analytics views
- Multi-screen navigation: Home, Map, Stations, Charts, Analytics, About, Language

---

## Tech Stack
- Flutter 3 (Dart SDK `^3.9.2`)
- Packages: `flutter_map`, `latlong2`, `fl_chart`, `http`
- Backend: FastAPI, Uvicorn, Pandas

---
