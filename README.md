# NYCTA — Landing Page

Landing page satu halaman untuk NYCTA, IT & Security Solutions di Depok.

## Struktur

```
nycta-landing/
├── index.html          # halaman utama (HTML+CSS+JS jadi satu file)
├── assets/
│   ├── nycta-icon.png  # logo owl icon-only, background transparan
│   └── favicon.png     # versi kecil buat tab browser
└── README.md
```

## Cara publish ke GitHub Pages

1. Buat repository baru di GitHub, misalnya `nycta-landing` (bisa public atau `username.github.io` kalau mau jadi domain utama akun).
2. Upload semua isi folder ini ke repo tersebut (root repo, bukan di dalam subfolder lain).
3. Di repo, buka **Settings → Pages**.
4. Di bagian **Source**, pilih branch `main` dan folder `/ (root)`, lalu **Save**.
5. Tunggu 1–2 menit, GitHub akan kasih URL publik-nya, biasanya:
   `https://username.github.io/nycta-landing/`

## Yang perlu lu ganti sebelum publish

Beberapa bagian masih placeholder, cari & ganti manual di `index.html`:

- `hello@nycta.id` → ganti dengan alamat Gmail brand yang udah lu buat (ada 2 tempat: bagian Kontak dan Footer)
- `https://www.threads.net/@nycta.id` → ganti setelah akun Threads resmi jadi
- `https://www.instagram.com/nycta.id` → ganti setelah akun Instagram resmi jadi

## Custom domain (opsional)

Kalau nanti punya domain sendiri (misal nycta.id), tinggal tambahkan file `CNAME` berisi domain tersebut di root repo, lalu atur DNS record ke GitHub Pages sesuai dokumentasi GitHub.
