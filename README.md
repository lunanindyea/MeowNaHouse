# MeowNaHouse 🐾

Landing page modern minimalis untuk website adopsi kucing **MeowNaHouse**.

## Fitur
- Hero landing page dengan slider 6 foto kucing.
- Daftar kucing dengan search dan filter jenis/umur.
- Detail kucing dalam modal.
- Favorite/wishlist tersimpan di `localStorage`.
- Form pengajuan adopsi.
- Lokasi shelter dan tautan Google Maps.
- Contact shelter melalui WhatsApp.
- Floating WhatsApp button di kanan bawah.
- Bahasa Indonesia / English.
- Responsive untuk desktop, tablet, dan mobile.

## Struktur
```text
MeowNaHouse/
├── index.html
├── README.md
├── css/
│   └── style.css
└── js/
    └── script.js
```

## Cara menjalankan
1. Extract ZIP.
2. Buka `index.html` di browser, atau gunakan Live Server di VS Code.
3. Tidak membutuhkan backend untuk demo ini.

## Foto
Foto demo menggunakan URL gambar dari **Unsplash Source/Unsplash** melalui hotlink. Untuk website produksi, cek kembali lisensi dan ketentuan penggunaan aset yang dipakai, atau ganti URL dengan foto shelter sendiri.

## Mengganti data
Edit array `cats` dan `slides` di `js/script.js` untuk mengganti nama, jenis, umur, deskripsi, dan foto.

## WhatsApp
Nomor yang digunakan: `+6285814568534`.
Template chat:
`Halo kak aku mau nanya tentang kucing ini..`

Jika dipakai untuk website sungguhan, sebaiknya form adopsi dihubungkan ke backend/database dan nomor WhatsApp shelter diverifikasi sebelum dipublikasikan.
