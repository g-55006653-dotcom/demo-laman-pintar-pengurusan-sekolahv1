# Demo Laman Pintar Pengurusan Sekolah

Laman web pengurusan sekolah yang menghimpunkan **Pentadbiran, Kurikulum, Hal Ehwal Murid (HEM) dan Kokurikulum** dalam satu sistem. Sistem sebenar berjalan di atas Google Apps Script dengan data dalam Google Sheets dan Google Drive milik sekolah sendiri.

> Demo ini menggunakan **data rekaan** (SK Contoh Pintar). Semua nama murid dan guru adalah contoh. Perubahan yang anda buat hanya disimpan sementara dalam pelayar dan kembali kepada data asal apabila halaman dimuat semula.

**Buka demo:** `https://NAMA-PENGGUNA.github.io/NAMA-REPO/` (gantikan dengan pautan GitHub Pages anda)

## Akaun demo

| Peranan | Nama pengguna | Kata laluan | Boleh buka |
|---|---|---|---|
| Superadmin | `superadmin` | `demo123` | Semua menu termasuk Pentadbiran Sistem |
| Pentadbir (Guru Besar) | `gb` | `demo123` | Semua menu kecuali Pentadbiran Sistem |
| Guru | `guru` | `demo123` | Menu guru: kehadiran, laporan, koko, intervensi |
| Awam | (tanpa log masuk) | – | Laman Utama dan Perkhidmatan Awam |

## Ciri utama

**Utama & Perkhidmatan Awam**
- Laman Utama: karusel gambar, sapaan Guru Besar, enrolmen terperinci (kelas, kaum, jantina, agama), hebahan dan takwim
- Warga Sekolah, Takwim (Takwim KPM M1–M43 & muat naik takwim PDF / Word / Excel / CSV), Hebahan, Laporan Aktiviti (OPR)
- PIBKS & PIBG, Kejayaan Sekolah, Lagu Sekolah, Pautan
- Rekod Bacaan NILAM, Aduan & Cadangan, Carian ID MOE Murid, Carian Slip PAJSK, Agihan Koko (pilihan ibu bapa)

**Kurikulum**
- Carta Organisasi, Pencerapan Guru, Semakan Buku Latihan, Jadual Guru (aSc Timetables)
- Peperiksaan & Analisis PBD (widget), Enrolmen Murid
- Pemulihan, PLaN & PIT1 dengan skorkad seimbang (Data awal − Pelepasan 1 − Pelepasan 2 = Baki)
- Perpustakaan & Bilik Tayang (tempahan slot)

**Hal Ehwal Murid**
- Kehadiran Murid: scorecard mingguan (Kumpulan A / B), Sabtu ganti, carian nama murid, sebab tidak hadir iDME, salin data ke iDME (extension e-HADIR)
- RMT & Bantuan, Guru Bertugas, Laporan Harian, Laporan Kantin, Laporan Kes, Keceriaan Kelas

**Kokurikulum**
- Unit & Carta Organisasi (senarai nama murid), Kehadiran Koko, Laporan Kokurikulum (OPR + PIKeBM + SIVIK)
- Pengesahan Laporan oleh GPK Kokurikulum (cop bulat, tandatangan digital, loceng notifikasi)
- RPT & RPH Koko daripada bank aktiviti, Laporan OPR Koko, Ekstra Kurikulum
- Pencapaian Koko (Johan hingga Kelima, Saguhati, Penyertaan), Rumusan Pencapaian & Laporan Lengkap
- Agihan Koko murid baharu mengikut kuota L / P (Tahun 3 atau Tahun 4), Pendidikan Khas (PPKI)

**Data Murid & Guru · Pentadbiran Sistem**
- Data Profil Murid (rekod koko tahun ke tahun), Database Murid (cetak senarai, tag PPKI, padam), Database Guru
- Slip PAJSK (muat naik pukal), Urus Unit Koko, Tetapan Laman (jenis sekolah rendah / menengah, dua sesi, ikon tab)
- Pengguna & Peranan, Tag Bantuan Murid, Log Keselamatan & Sandaran bulanan
- Akhir tahun 3 langkah: Arkib & tutup sesi → Naik tahun murid (pratonton) → Muat naik murid baharu

## Kandungan repositori

| Fail | Keterangan |
|---|---|
| `index.html` | Demo lengkap dalam satu fail (paparan dan data rekaan). Tiada pelayan diperlukan. |
| `README.md` | Fail ini. |

## Nota

- Demo berfungsi di komputer, tablet dan telefon pintar.
- Fon dimuatkan daripada Google Fonts; tiada data dihantar ke mana-mana pelayan.
- Untuk pemasangan sistem sebenar di sekolah anda (Google Sheets & Drive sekolah sendiri), hubungi penyedia sistem.
