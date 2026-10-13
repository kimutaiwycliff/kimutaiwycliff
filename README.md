### Wycliff Kimutai

Software engineer in Nairobi. I build web, mobile and backend systems end to end, from the database schema to the app in someone's hand, and I have a second specialty in geospatial software. I trained as a surveyor (BSc Geomatics Engineering, JKUAT) and later did an MSc in Data Analytics.

Since 2022 I have worked on **Ardhisasa**, Kenya's national land information system, where I lead the QGIS plugin government surveyors use to certify parcel jobs and run the GeoServer/PostGIS services behind it. Alongside that I build SaaS products for Kenyan businesses.

#### Products and full-stack work

| Project | What it is |
|---|---|
| [fundi-pos](https://github.com/kimutaiwycliff/fundi-pos) | Multi-tenant, offline-first POS for hardware stores: Android till (Expo/React Native), Tauri desktop till, Next.js dashboard and API. SQLite ↔ Postgres sync via PowerSync, append-only stock ledger, M-Pesa, audit log |
| [pharmatrack](https://github.com/kimutaiwycliff/pharmatrack) | Pharmacy management SaaS: offline-capable POS, batch/expiry-aware inventory, controlled-substances register, appointment reminders, Paystack billing, Postgres row-level security · [live](https://pharmatrack.co.ke) |
| [insurance-quotation](https://github.com/kimutaiwycliff/insurance-quotation) | BrokerOS: quotes, policies, renewals and commissions for insurance agents. FastAPI + async SQLAlchemy API, Better Auth service, Next.js web, Docker Compose |
| [mobile-pos](https://github.com/kimutaiwycliff/mobile-pos) | Expo / React Native POS and inventory app with barcode scanning and multi-location stock |
| [golang-fiber-grpc-microservices](https://github.com/kimutaiwycliff/golang-fiber-grpc-microservices) | Go microservices (account, order) behind a Fiber API gateway, talking over gRPC |

#### Geospatial and data

| Project | What it is |
|---|---|
| [geospatial-stack](https://github.com/kimutaiwycliff/geospatial-stack) | Data publishing platform: validated uploads → Celery ETL → PostGIS / GeoParquet → Martin + PMTiles, FastAPI, dataset governance and audit trail, Prometheus/Grafana |
| [dadaab-climate-risk-dashboard](https://github.com/kimutaiwycliff/dadaab-climate-risk-dashboard) | Hazard and displacement dashboard for the Dadaab refugee complex (UNHCR, NASA FIRMS, Open-Meteo, USGS, OSM) · [live](https://dadaab-climate-risk-dashboard.vercel.app) |
| [gis-stack-backend](https://github.com/kimutaiwycliff/gis-stack-backend) | PostGIS, GeoServer (WMS/WFS/WCS/WMTS), Martin and a Rust + GDAL ingest service behind Nginx |
| [geo-stack](https://github.com/kimutaiwycliff/geo-stack) | PostGIS + DuckDB/GeoParquet + TiTiler (COG) + STAC behind one FastAPI · [live](https://geo-stackk.vercel.app) |

#### Tools I use most

- **Languages:** TypeScript, Python, SQL, Go, Rust
- **Web & mobile:** React, Next.js, SvelteKit, React Native / Expo, Tauri, Tailwind
- **Backend:** Node.js, FastAPI, PostgreSQL, Redis, Celery / BullMQ, REST, gRPC
- **Geospatial:** PostGIS, GeoServer, QGIS / PyQGIS, GDAL, MapLibre GL
- **Infrastructure:** Docker, GitHub Actions, Caddy / Nginx, Vercel

Portfolio: [wycliffkimutai.co.ke](https://www.wycliffkimutai.co.ke) · Email: kimutaiwycliff90@gmail.com · [LinkedIn](https://linkedin.com/in/wycliff-kimutai-698903139/)
