# Lokaboard

**Game papan digital budaya Nusantara.** Susun ubin motif kain Nusantara di atas papan, raih poin dari pola yang selaras, lalu baca kisah di balik setiap kain.

**Versi 1.2.0** · Windows dan Android · main online tangguh · 31 kartu cerita dua bahasa yang terbuka sebagai hadiah.

Situs resmi: **https://lokaboard.lokashaka.id** (unduh, lapor kesalahan, diskusi).
Repo ini hanya berisi **game yang sudah jadi**. Kode sumbernya disimpan terpisah.

## Unduh dan main

| Platform | Unduh | Cara pasang |
|---|---|---|
| **Windows 10/11 (64-bit)** | [LokaboardSetup.exe](https://github.com/Lokashaka/Lokaboard-game/raw/main/LokaboardSetup.exe) (30 MB) | Jalankan, ikuti langkahnya. Tidak perlu hak admin; muncul di menu Start. |
| **Android 8.0+** | [Lokaboard.apk](https://github.com/Lokashaka/Lokaboard-game/raw/main/Lokaboard.apk) | Buka di ponsel, izinkan "pasang dari sumber ini" bila diminta. |
| Windows tanpa installer | Tombol **Code → Download ZIP** | Ekstrak, buka folder `Lokaboard`, jalankan `Lokaboard.exe`. |

Main sendiri atau dengan teman di satu perangkat tidak perlu internet. Mode online butuh internet.

> Windows mungkin menampilkan "Windows protected your PC" karena game ini belum ditandatangani secara digital. Klik **More info → Run anyway**.

## Cara bermain

- 2 sampai 4 pemain: bermain bergantian di satu perangkat, melawan AI (Mudah, Sedang, Sulit), atau campuran keduanya.
- Pilih satu ubin dari tangan, lalu klik petak berwarna emas (harus menempel ubin lain). Klik sekali lagi untuk menaruh.
- Poin datang dari tiga pola:
  - **Harmoni**: 3 ubin atau lebih dari motif yang sama berjajar lurus (3 = 3 poin, 4 = 6, 5 = 10, 6 = 15).
  - **Warna serasi**: +1 untuk tiap tetangga yang warnanya sama.
  - **Simetri**: +3 bila ubinmu diapit dua ubin bermotif sama di sisi yang berlawanan.
- **Pengimbang**: pemain yang tertinggal mendapat +1 per langkah untuk tiap 4 poin ketertinggalan dari pemimpin (paling banyak +6).
- Mode: **Klasik** (3 ronde, papan 9 x 9), **Cepat** (1 ronde, 9 x 9), **Kilat** (1 ronde, 7 x 7).
- Baru pertama kali main? Pilih **Mulai Game → Tutorial**.
- Tekan **Esc** (atau tombol kembali di Android) untuk membuka menu.

## Main online

Pilih **Mulai Game → Lawan: Online (kode ruang)**, buat ruang, lalu bagikan kode 6 hurufnya ke teman.
- Setiap giliran punya batas waktu **60 detik**. Bila habis, langkah acak yang sah dimainkan otomatis.
- Game tertutup atau internet putus? Buka lagi dan pilih **Lanjutkan ruang** di menu utama.
- Pemain yang keluar tidak menghentikan pertandingan; gilirannya dimainkan otomatis.
- Setelah selesai, tuan rumah bisa menekan **Main lagi** di ruang yang sama.

## Koleksi Kartu

Ada 31 kartu cerita tentang kain dan motif Nusantara, dari Songket Palembang sampai Kain Berang Maluku. Setiap kartu memuat ilustrasi, daerah asal, cerita singkat, dan tautan ke sumber tertulisnya.
Lima kartu motif papan terbuka sejak awal; **setiap pertandingan yang selesai membuka 2 kartu baru**, yang muncul sebagai kartu 3D berbalik. Lihat semuanya di menu **Koleksi Kartu**.

Kartu cerita dan antarmuka tersedia dalam **bahasa Indonesia dan Inggris** (Pengaturan → Bahasa).

## Menemukan kesalahan?

Kalau ada isi kartu cerita yang keliru, tekan tombol **Laporkan kesalahan** di kartu itu, atau buka **https://lokaboard.lokashaka.id/lapor.php** (tanpa akun). Untuk ngobrol soal strategi atau kain dari daerahmu, mampir ke **Diskusi** di situs yang sama.

## Kredit

- **Pengembang:** Lokashaka · dibuat dengan Unity
- **Huruf:** Cormorant Garamond oleh Christian Thalmann · Plus Jakarta Sans oleh Tokotype (SIL Open Font License)
- **Ilustrasi kain dan motif:** dibuat dengan Codex (OpenAI) mengikuti palet Lokaboard
- **Musik dan efek suara:** dibuat secara prosedural; komposisi gamelan orisinal
- **Sumber kartu cerita:** Indonesia Kaya, Museum Sonobudoyo, Kementerian Pariwisata (indonesia.travel), Mongabay Indonesia, UNESCO
- **Mesin:** Unity 6

---

**English:** Lokaboard is a digital board game about Indonesian textile motifs for 2-4 players. Windows: run [LokaboardSetup.exe](https://github.com/Lokashaka/Lokaboard-game/raw/main/LokaboardSetup.exe). Android 8.0+: install [Lokaboard.apk](https://github.com/Lokashaka/Lokaboard-game/raw/main/Lokaboard.apk). Play against AI, with friends on one device, or online with a 6-letter room code. All 31 story cards and the interface are available in English (Settings → Language). Report errors or join the discussion at https://lokaboard.lokashaka.id.
