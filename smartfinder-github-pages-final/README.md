# SmartFinder GitHub Pages

Dashboard statis untuk GitHub Pages. Tampilan ini mengambil data dari Cloudflare Worker SmartFinder.

## Cara pakai

1. Buka `index.html`.
2. Cari baris:

```js
const WORKER_BASE_URL = "https://smartfinder-blynk-link.kruzz-smartfinder.workers.dev";
```

3. Ganti dengan link Worker final kamu kalau berbeda.
4. Upload `index.html` ke repository GitHub.
5. Aktifkan GitHub Pages dari branch `main` folder `/root`.

## Data

- V0 = Status
- V1 = RSSI
- V2 = Packet
- V3 = Last Seen
- V4 = Packet Loss
