# GasCuciMotor

Aplikasi pemesanan, antrian, dan manajemen layanan cuci motor berbasis Android (Jetpack Compose).

- Nama: Ikhsaan Hanafi
- NIM: 20240140226
- Kelas: E

## Progress Mingguan

| Minggu | Tanggal | Progress |
|---|---|---|
| 1 | 14 Nov 2026 | SRS v0.1 Tahap 1: bab 1 (Introduction) dan bab 2 (Overall Description) |
| 2 | 22 Nov 2026 | SRS v0.2 Tahap 2: bab 3 (System Features), 9 fitur dengan 57 kebutuhan fungsional |
| 3 | 27 Nov 2026 | SRS v1.0 Final: bab 4 sampai 6 dan Appendix A sampai C, termasuk 7 diagram analisis |

## Detail Progress

### Minggu 1: SRS v0.1 Tahap 1 (12 - 18 November 2026)
- Menyusun cover, revision history, dan sign-off dokumen SRS.
- Bab 1 Introduction: tujuan dokumen, konvensi penulisan, target pembaca, ruang lingkup, referensi, dan daftar singkatan.
- Bab 2 Overall Description: arsitektur sistem (aplikasi Android, backend Express, database), tabel 9 fitur utama, kelas pengguna (Admin dan Customer), lingkungan operasi, batasan, dan asumsi.

### Minggu 2: SRS v0.2 Tahap 2 (19 - 25 November 2026)
- Menambah bab 3 System Features, tiap fitur berisi deskripsi dan prioritas, tabel aksi pengguna dan respons sistem, serta daftar kebutuhan fungsional (REQ).
- Fitur yang dirinci: autentikasi dan otorisasi, manajemen layanan, manajemen customer, manajemen motor, manajemen pesanan dan antrian, manajemen karyawan, pembayaran tunai, riwayat dan laporan harian, penyimpanan file lokal.
- Revision History diperbarui ke versi 0.2 dan daftar isi disesuaikan.

### Minggu 3: SRS v1.0 Final (26 November - 2 Desember 2026)
- Bab 4 External Interface Requirements: antarmuka pengguna, perangkat keras, perangkat lunak (tabel endpoint REST API), dan komunikasi.
- Bab 5 Nonfunctional Requirements: performa, keselamatan, keamanan (JWT, refresh token, bcrypt), dan atribut kualitas.
- Bab 6 Other Requirements: struktur database (6 entitas dan relasinya) dan ketentuan repository.
- Appendix A (glosarium), Appendix B (analisis), dan Appendix C (daftar isu di luar ruang lingkup).
- Appendix B berisi 7 diagram: use case diagram, diagram CRUDS per fitur, ERD, activity diagram, 2 sequence diagram (login dan refresh token, booking), dan class diagram MVVM.
- Revision History diperbarui ke versi 1.0 dan daftar isi disesuaikan.

## Status Fitur

| Fitur | Status |
|---|---|
| Autentikasi (login, register, JWT, refresh token) | Belum |
| Manajemen layanan | Belum |
| Manajemen customer | Belum |
| Manajemen motor | Belum |
| Manajemen pesanan dan antrian | Belum |
| Manajemen karyawan | Belum |
| Pembayaran tunai | Belum |
| Riwayat dan laporan harian | Belum |
| Penyimpanan file lokal | Belum |

## Dokumen

- [SRS v0.1 Tahap 1](docs/SRS_GasCuciMotor_v0.1_Tahap1.docx)
- [SRS v0.2 Tahap 2](docs/SRS_GasCuciMotor_v0.2_Tahap2.docx)
- [SRS v1.0 Final](docs/SRS_GasCuciMotor_v1.0_Final.docx)
