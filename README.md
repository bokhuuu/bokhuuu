# Zura Bokhua — Software Engineer

I design and ship complete production systems — from architecture and data pipelines to AI integration and infrastructure. Sole technical partner for a leading international commercial real estate firm across Caucasus markets.

## Client Work

**[Atlas](https://github.com/bokhuuu/atlas-engine) — Multi-Market Real Estate Intelligence Platform**  
Live production platform serving a leading international commercial real estate firm across Yerevan, Baku and Tbilisi.

- 3 markets · 26 property categories · dual-queue scraping architecture (browser + HTTP workers)
- Agentic AI assistant with 11 callable tools · pgvector RAG semantic search · persistent per-user conversation history
- Full listing lifecycle tracking · price normalisation across AMD/AZN/GEL/USD · district-level analytics
- Automated document generation: Python engine exports 1,500+ client-ready PDFs from formula-driven Excel templates via Windows COM — zero manual steps, built-in validation
- 527 automated tests · Laravel 12 · PHP 8.4 · PostgreSQL + pgvector · Redis · Docker · GitHub Actions CI/CD

**[Vigil](https://github.com/bokhuuu/vigil-engine) — Property Valuation Compliance Engine**  
Laravel automation engine and Telegram bot coordinating field inspection compliance across 1,500+ properties for the Colliers Georgia.

- Event-driven Google Drive watcher (Drive Changes API) — auto-ticks document checkboxes across 1,500+ property folders without polling
- Airtable integration across 7 relational tables · real-time team notifications · sector progress reports
- Business module web UI with separate auth guard · 299 automated tests · GitHub Actions CI/CD

**[RideFlow](https://github.com/bokhuuu/rideflow-engine) — Electric Scooter Sharing Platform**  
Production platform built around custom IoT hardware with no existing SDK. The supplier provided raw TCP protocol documentation; everything else was built from scratch.

- Python asyncio TCP server speaking the OMNI M151 binary protocol directly: check-in, heartbeat, 3-step cryptographic unlock handshake, real-time GPS stream, speed cap enforcement
- Ray casting point-in-polygon geofencing across 4 operating zones · violation sequence: beep → speed cap → auto-lock
- Flitt (TBC Group) payment integration · SHA1 signature verification on every callback
- Filament 5 admin panel with interactive Leaflet.js polygon editor for drawing geofence zones on the map
- Pluggable IoT architecture — new hardware device = new folder, zero core changes
- 80+ Pest tests · 62 pytest tests · 7-service Docker stack · GitHub Actions runs both suites on every push

## Open Source

- **[LaraKit](https://github.com/bokhuuu/larakit)** — Laravel + React/Inertia admin panel starter. Full auth · 2FA · roles · Docker · CI/CD
- **[LaraAI](https://github.com/bokhuuu/laraai)** — Laravel AI integration template. RAG · embeddings · tool calling · streaming · A/B testing · cost tracking · 51 tests
- **[ScrapKit](https://github.com/bokhuuu/scrapkit)** — Laravel scraping framework. Pluggable profiles · deduplication · queue pipeline

## Stack
`Laravel` `PHP` `Python` `React` `TypeScript` `PostgreSQL` `pgvector` `Redis` `Docker` `GitHub Actions` `RAG` `AI APIs` `Pest` `pytest`

📫 [zurabokhua@gmail.com](mailto:zurabokhua@gmail.com) · Open to remote backend and AI integration roles
