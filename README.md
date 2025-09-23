# VIP API — Public Spec
Canonical OpenAPI for the VIP image search & controlled-download API.

- Live docs (Swagger UI): GitHub Pages on this repo
- Spec: `openapi/vip-api.yaml`

## Quick Start
- Search: `GET /v1/search?q=...&prompt=...`
- Asset: `GET /v1/assets/{asset_id}`
- Download: `POST /v1/downloads { asset_id, rendition }`
