# KELUARGAKU – Peta Rumpun Kekeluargaan

Aplikasi PWA lokal untuk mencatat anggota keluarga, hubungan ayah/ibu/pasangan, pohon keturunan, rumpun, klan, kepala keluarga, dan sebaran tempat tinggal.

## Fitur
- Data anggota: nama, jenis kelamin, status hidup/wafat, tanggal lahir/wafat, asal, catatan.
- Hubungan ayah, ibu, pasangan, dan anak untuk membentuk pohon keluarga.
- Pencarian dan profil anggota.
- Statistik jumlah anggota per rumpun, klan, kepala keluarga, dan wilayah.
- Filter statistik menurut klan, rumpun, provinsi, kabupaten/kota.
- Rekap lokasi desa/kelurahan, kecamatan, kabupaten/kota, provinsi, negara.
- Ekspor statistik ke CSV (kompatibel dengan Excel).
- Ekspor dan pemulihan seluruh data JSON.
- Penyimpanan lokal browser dan cache untuk penggunaan offline setelah halaman berhasil dimuat.
- Migrasi pembacaan dari penyimpanan versi awal `keluargaku_v1` bila database baru belum ada.

## Publikasi GitHub Pages
Repository: https://github.com/madeadja2026-sys/KELUARGAKU

Aktifkan melalui **Settings → Pages → Deploy from a branch → main → /(root)**. URL yang dituju:
https://madeadja2026-sys.github.io/KELUARGAKU/

## Instal Android
1. Buka URL GitHub Pages di Chrome Android dengan internet aktif.
2. Tunggu halaman selesai dimuat.
3. Buka menu Chrome (⋮), pilih **Install app** atau **Tambahkan ke layar utama**.
4. Jalankan dari ikon KELUARGAKU.

## Perlindungan data
- Data anggota disimpan pada penyimpanan lokal browser/perangkat, bukan di repository GitHub.
- Repository ini bersifat publik; jangan menaruh data pribadi atau cadangan keluarga ke dalam repository.
- Ekspor JSON secara berkala dan simpan di lokasi aman.
- Pemulihan JSON mengganti isi database lokal saat ini.
- Menghapus data situs/browser dapat menghapus data lokal. Buat cadangan sebelum membersihkan browser atau mengganti HP.
- Data tidak otomatis tersinkron antarperangkat.

## Batasan versi ini
- Sebaran lokasi disajikan sebagai tabel/diagram wilayah, bukan peta GPS.
- Hubungan keturunan dihitung dari ayah dan ibu yang dicatat; data yang tidak lengkap tidak boleh dianggap membuktikan tidak ada hubungan.
- Statistik KK menggunakan nama kepala keluarga yang dimasukkan; gunakan ejaan/identitas yang konsisten.
- Hubungan adat, adopsi, dan hubungan yang belum terverifikasi belum dimodelkan sebagai jenis hubungan terpisah.
