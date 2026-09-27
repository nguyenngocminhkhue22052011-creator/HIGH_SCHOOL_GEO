# Asset sources

## Hero carousel — active illustrations

The four active carousel illustrations were generated for this project from the user's supplied cartoon-globe reference. They are not third-party stock photographs. Optimized JPEG copies preserve the original 4:3 aspect ratio at 1400 × 1050 pixels; the uncompressed generated PNGs remain outside the project at `/home/ubuntu/webdev-static-assets/atlas-cartoon/`.

| Illustration | WebDev storage path | Optimized local copy |
|---|---|---|
| World globe and landmarks | `/manus-storage/01-world-globe_be332fb3.jpg` | `atlas-cartoon-optimized/01-world-globe.jpg` |
| Northern Vietnam mountains and terraces | `/manus-storage/02-northern-vietnam_288c9f9a.jpg` | `atlas-cartoon-optimized/02-northern-vietnam.jpg` |
| Mekong Delta rivers and rice fields | `/manus-storage/03-mekong-delta_a806753a.jpg` | `atlas-cartoon-optimized/03-mekong-delta.jpg` |
| Central Vietnam coast and port | `/manus-storage/04-vietnam-coast_89dda208.jpg` | `atlas-cartoon-optimized/04-vietnam-coast.jpg` |

The WebDev version references Manus Storage paths from `client/src/pages/Home.tsx`. The downloadable ZIP may use local copies under `client/public/images/` so the carousel works without Manus Storage. The user's reference image is not distributed as a website asset.

## Retired stock photographs

Earlier versions used Pexels-search images of rice terraces, northern rivers, and Ha Long Bay. Those photos are no longer referenced by the active carousel. Older copies may remain in storage; verify the original source-page license before reusing them elsewhere.

## World map data

- `world-atlas@2.0.2`, package asset `countries-110m.json`, bundled locally by Vite and decoded client-side with `topojson-client` / projected with `d3-geo`. No external map API or runtime geocoding service is used.
