# Quickstart
1. Authenticate (Bearer token).
2. Search: `GET /v1/search?q=otter&prompt=playful river animal`.
3. Fetch asset metadata: `GET /v1/assets/{asset_id}`.
4. Request download: `POST /v1/downloads` with `{ asset_id, rendition }`.
