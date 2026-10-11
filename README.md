# Peg Hunt Map

Where in California is a die-cast hunting trip worth starting? Every spot in the state is scored by the best round
trip to nearby stores, weighted by how many other people share them.

**Live site:** https://jksdbks123.github.io/peg-hunt-map/

This repository holds only the published static site: one HTML page and the precomputed data it reads. The data is a
one-time snapshot (October 2026) and is not updated automatically. "How it works" on the site explains the method,
the assumptions and what the map cannot tell you.

A personal side project by Zhihui Chen. Not affiliated with any toy maker or retailer. Store names belong to their
owners. The page sets no cookies and runs no analytics.

## Data and licences

| data | source | licence |
|---|---|---|
| Roads, and store locations derived from OpenStreetMap (`data/stores.json`, and the routes and scores built on them) | © OpenStreetMap contributors | [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/): the store data derived from OpenStreetMap in this repository is published under the same licence |
| Store locations from All The Places | [alltheplaces.xyz](https://alltheplaces.xyz/) | CC0 |
| Population (2025 estimates on 2020 blocks), city and metro boundaries | US Census Bureau | Public domain |
| Base map tiles (loaded by the page, not stored here) | [OpenFreeMap](https://openfreemap.org/) (OpenMapTiles, OpenStreetMap) | see their sites |
| Satellite imagery (loaded by the page, not stored here) | USGS The National Map (USDA NAIP) | Public domain |

Attribution for OpenStreetMap: © OpenStreetMap contributors, https://www.openstreetmap.org/copyright
