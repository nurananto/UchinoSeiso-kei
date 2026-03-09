# Uchi no Seiso-kei Iinchou ga Katsute Chuunibyou Idol datta Koto o Ore Dake ga Shitteiru.

> Idola chūnibyō yang pernah mengguncang dunia, “Saikai no Akuma” (Nightmare Disaster) — dikenal juga sebagai Mea. Reo, yang dulu sering beraktivitas bersamanya — berfoto, mengunggah ke media sosial, dan membuat mereka viral — secara tak terduga bertemu lagi dengannya di SMA tempat ia melanjutkan sekolah. Namun kini gadis itu sudah “lulus” dari masa chūnibyō-nya, dan berubah menjadi Nagi Kanagi, ketua kelas berkepribadian introvert dan canggung dalam bersosialisasi! Lebih jauh lagi, karena suatu alasan tertentu, Nagi kini menargetkan posisi ketua OSIS — dan meminta bantuan Reo untuk memproduksinya kembali!?

---

## Info

| | |
|---|---|
| Judul | Uchi no Seiso-kei Iinchou ga Katsute Chuunibyou Idol datta Koto o Ore Dake ga Shitteiru. |
| Judul Alternatif | うちの清楚系委員長がかつて中二病アイドルだったことを俺だけが知っている。 |
| Author | Kota Mikami, Neko Sorani, Yugaa, Kobayashi Shoujo |
| Tipe | Manga (Hitam Putih) |
| Genre | Shounen · Drama · Comedy · Romance · School Life · Slice of Life |

## Link

- [MangaDex](https://mangadex.org/title/5993c10b-c49e-4771-9a3a-8b8436b12d80/uchi-no-seiso-kei-iinchou-ga-katsute-chuunibyou-idol-datta-koto-o-ore-dake-ga-shitteiru)
- [Raw](https://comic-days.com/episode/2550912965858307088)

---

## Struktur

```
UchinoSeiso-kei/
├── manga-config.json     # Metadata manga
├── manga.json            # Data chapter (auto-generated)
├── manga-automation.js   # Script automation
├── encrypt-manifest.js   # Script enkripsi manifest
├── daily-views.json      # Data views harian
└── <chapter>/
    └── manifest.json     # Daftar halaman (encrypted)
```

## Automation

Semua proses berjalan otomatis via GitHub Actions:

1. Push chapter baru (folder + manifest.json)
2. `encrypt-manifest.yml` — enkripsi manifest
3. `manga-automation.yml` — regenerate manga.json
4. Trigger rebuild ke website utama
5. `sync-cover.yml` — sinkronisasi cover dari website

---

Bagian dari [Nurananto Scanlation](https://nuranantoscans.my.id)