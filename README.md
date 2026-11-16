# Landing Page Kredit Motor Honda

Landing page statis (HTML + CSS + JavaScript murni). Tidak perlu build atau instalasi apa pun.

## Isi folder

```
index.html            halaman utama
assets/img/           foto motor dan foto serah terima pelanggan
.nojekyll             agar GitHub Pages menyajikan file apa adanya
```

## Cara hosting di GitHub Pages

1. Buka github.com, klik **New repository**, beri nama (contoh: `kredit-motor-honda`), pilih **Public**, lalu **Create repository**.
2. Klik **uploading an existing file**, lalu seret **isi** folder ini (`index.html`, folder `assets`, `.nojekyll`, `README.md`) ke halaman upload. Jangan unggah file zip-nya, ekstrak dulu.
3. Klik **Commit changes**.
4. Buka **Settings → Pages**. Pada **Build and deployment**, pilih **Deploy from a branch**, branch **main**, folder **/(root)**, lalu **Save**.
5. Tunggu 1 sampai 2 menit. Alamat halaman: `https://USERNAME.github.io/kredit-motor-honda/`

## Yang bisa Anda ubah

- **Nomor WhatsApp:** cari `NOMOR=` di bagian `<script>` paling bawah `index.html`. Pakai format 62 tanpa angka 0 di depan (contoh `6289691599661`).
- **DP dan cicilan:** cari kartu paket di `index.html` (teks "Honda BeAT", "Honda Scoopy", "Honda Vario 125").
- **Foto:** timpa file di `assets/img/` dengan nama yang sama.
- **Domain sendiri:** di Settings → Pages isi kolom **Custom domain**.

## Catatan

- Pastikan pelanggan pada foto serah terima sudah setuju fotonya ditampilkan.
- DP dan cicilan bersifat perkiraan; angka final mengikuti dealer dan perusahaan pembiayaan.
- Honda adalah merek PT Astra Honda Motor.
