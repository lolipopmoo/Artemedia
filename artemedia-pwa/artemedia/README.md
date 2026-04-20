# Artemedia PWA — Panduan Deploy

## Isi Folder
```
artemedia/
├── index.html          ← File utama app
├── manifest.json       ← Identitas PWA
├── service-worker.js   ← Fitur offline
├── icons/              ← Buat 2 icon (lihat di bawah)
│   ├── icon-192.png
│   └── icon-512.png
└── README.md           ← Panduan ini
```

---

## Langkah 1: Buat Icon

1. Buka **Canva.com** (gratis)
2. Buat desain ukuran **512 x 512 px**
3. Buat logo Artemedia (warna oranye #D85A30)
4. Download sebagai PNG → simpan sebagai `icon-512.png`
5. Resize ke 192x192 → simpan sebagai `icon-192.png`
6. Taruh kedua file di folder `icons/`

---

## Langkah 2: Upload ke GitHub

1. Buka **github.com** → daftar gratis
2. Klik **New repository** → nama: `artemedia`
3. Upload semua file (drag & drop)
4. Klik **Commit changes**

---

## Langkah 3: Deploy ke Vercel

1. Buka **vercel.com** → login dengan GitHub
2. Klik **New Project**
3. Pilih repository `artemedia`
4. Klik **Deploy**
5. Selesai! Dapat URL: `artemedia.vercel.app`

---

## Langkah 4: Test di HP Android

1. Buka URL di **Chrome Android**
2. Tunggu 3 detik → muncul banner "Install Artemedia"
3. Tap **Install**
4. Icon Artemedia muncul di home screen! 🎉

## Test di iPhone

1. Buka URL di **Safari**
2. Tap tombol **Share** (kotak + panah atas)
3. Pilih **"Add to Home Screen"**
4. Tap **Add**

---

## Domain Custom (Opsional)

Ingin URL seperti `artemedia.id`?
1. Beli domain di **Niagahoster** atau **Rumahweb** (~Rp 150rb/tahun)
2. Di Vercel → Settings → Domains → tambah domain
3. Ikuti instruksi DNS dari Vercel

---

## Kontak & Dukungan

Website: artemedia.id
Shopee: shopee.co.id/artemediashop
Tokopedia: tokopedia.com/artemediashop
