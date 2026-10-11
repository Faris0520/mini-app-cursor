# Tip Calculator

Kalkulator tip sederhana dalam **satu file HTML** (`index.html`) — HTML, CSS, dan JavaScript tanpa build step atau dependensi npm.

Desain mengikuti challenge populer [Frontend Mentor — Tip calculator app](https://www.frontendmentor.io/challenges/tip-calculator-app-ugJNGbJUX): palet teal/hijau, font **Space Mono**, layout responsif (mobile & desktop).

## Fitur

- Input **tagihan** (bill)
- Pilihan tip preset: **5%**, **10%**, **15%**, **25%**, atau **Custom**
- Pembagian biaya per **jumlah orang**
- Tampilan **Tip Amount / person** dan **Total / person** (perhitungan langsung saat mengetik)
- Validasi dasar (mis. jumlah orang tidak boleh 0)
- Tombol **Reset** untuk mengosongkan semua input

## Cara menjalankan

Cukup buka file di browser:

```bash
# dari root repo
xdg-open index.html   # Linux
open index.html       # macOS
```

Atau lewat server lokal (opsional):

```bash
python3 -m http.server 8080
```

Buka [http://localhost:8080/index.html](http://localhost:8080/index.html).

## Contoh perhitungan

| Bill | Tip | Orang | Tip / orang | Total / orang |
|------|-----|-------|-------------|---------------|
| $100 | 15% | 2     | $7.50       | $57.50        |

Rumus: tip total = bill × (tip% / 100); total tagihan = bill + tip total; nilai per orang dibagi jumlah orang.

## Struktur proyek

```
.
├── index.html   # Aplikasi lengkap (UI + logika)
└── README.md
```

## Lisensi

Proyek contoh untuk pembelajaran. Desain Frontend Mentor untuk penggunaan non-komersial sesuai [aturan challenge](https://www.frontendmentor.io/challenges/tip-calculator-app-ugJNGbJUX) mereka.
