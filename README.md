# Hasil Laboratorium Klinik

Aplikasi satu halaman untuk mencatat dan mencetak hasil laboratorium klinik (A4).
Berjalan penuh di browser: tidak ada server, tidak ada akun, dan data tidak dikirim ke mana pun.

## Fitur
- 112 parameter siap pakai: Hematologi (termasuk BT/CT), Kimia Klinik, Urinalisis, Imunoserologi, Imunologi, Elektrolit, AGD, dan baris bebas
- Penanda H / L / CH / CL otomatis menurut jenis kelamin, usia, dan fase atau kondisi
- Master parameter dapat diubah; perubahan rujukan hanya berlaku untuk hasil baru (hasil lama menyimpan rujukannya sendiri)
- Alur draft, selesai, tervalidasi, dengan riwayat perubahan
- Riwayat pasien dan grafik tren
- Cetak Lembar Pasien (hanya yang diperiksa) dan Lembar Arsip (semua parameter kelompok)
- Cadangan dan pemulihan data (JSON), ekspor daftar kunjungan (CSV)
- Tampilan responsif untuk HP, tablet, dan komputer; halaman Tentang berisi info versi, privasi, dan batasan

Dibuat oleh AbdiSR.

## Hal yang perlu diketahui pengguna
- Data tersimpan di browser dan perangkat masing-masing. Pengguna lain tidak melihat data Anda, dan Anda tidak bisa membuka data dari komputer lain kecuali lewat file cadangan.
- Membersihkan data situs atau memakai mode privat dapat menghapus data. Unduh cadangan secara berkala di menu Cadangan data.
- Pilihan pengguna dan peran hanya pengaturan tampilan, tanpa kata sandi. Aplikasi ini bukan pengganti sistem informasi laboratorium resmi dengan kontrol akses.
- Nilai rujukan bawaan bersifat umum dan belum diverifikasi. Cocokkan dengan insert kit, metode alat, dan ketentuan laboratorium sebelum dipakai untuk pasien. Batas kritis (CH/CL) sengaja dikosongkan agar ditetapkan oleh laboratorium.
- Aplikasi ini alat bantu pencatatan, bukan perangkat medis.
- Semua situs di `<username>.github.io` memakai penyimpanan browser yang sama. Data aplikasi ini tidak terpengaruh, tetapi jangan menaruh data nyata di domain yang juga dipakai situs lain yang tidak Anda percayai.
