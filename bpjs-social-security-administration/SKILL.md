---
name: bpjs-social-security-administration
description: >
  Gunakan skill ini saat pengguna yang memegang peran Employee Services Staff membutuhkan panduan
  tentang administrasi kepesertaan jaminan sosial BPJS.
  Trigger juga saat percakapan menyebut topik: BPJS Kesehatan, BPJS Ketenagakerjaan, JHT, JP, JKK, JKM,
  pendaftaran kepesertaan, mutasi/penonaktifan kepesertaan, iuran BPJS, rekonsiliasi iuran, portal BPJS,
  e-dabu/SIPP, atau pelaporan & pembaruan data jaminan sosial karyawan.
---

# BPJS & Social Security Administration

**Deskripsi:** Kemampuan **mengelola pendaftaran dan pembaruan kepesertaan BPJS Kesehatan maupun Ketenagakerjaan**. Skill ini adalah **administrator jaminan sosial**: memastikan setiap karyawan terdaftar tepat, data kepesertaan mutakhir, iuran dihitung & dilaporkan benar, dan perubahan (masuk, keluar, mutasi keluarga) tercatat di portal BPJS tepat waktu. Fokusnya **spesifik pada jaminan sosial wajib (BPJS)**, berbeda dari benefit non-BPJS (#33), klaim medis (#17/#34), maupun perhitungan gaji menyeluruh (#8).

**Relevan untuk:** Employee Services Staff

**Metadata:** Fase 6 (Spesialisasi Finansial-Administratif + Capstone / Payroll Management) · Kategori: Payroll, Benefit & Employee Services · Skill #18 · Tahap A (core payroll) · Dependensi reuse: #4 HRIS (data karyawan & keluarga), #27 HRIS Update (status masuk/keluar/mutasi sebagai pemicu update kepesertaan), #8 Payroll (angka iuran sebagai potongan & beban perusahaan), #2 Labor Law (kewajiban kepesertaan) · Pembeda: #18 = **jaminan sosial BPJS spesifik**; #33 = data benefit non-BPJS; #17 = proses klaim medis; #34 = verifikasi & laporan klaim; #8 = perhitungan gaji menyeluruh.

---

## Arah Strategis (selaras HR Strategic Guidance)

Skill ini mengaktifkan pilar **HR Operations** (Proactive Compliance & Risk Management) dan **Data-Driven HR**, serta menerapkan pergeseran **Compliance-Driven→Performance-Driven** dan **Reactive→Proactive**: kepesertaan jaminan sosial dijaga proaktif & akurat, bukan ditangani saat ada keluhan atau temuan audit.

- **Key Result — decommission HRIS lama Okt 2028.** Data kepesertaan BPJS harus sinkron dengan HRIS baru (#4) sebagai single source of truth; rekonsiliasi data karyawan↔portal BPJS menguji integritas migrasi.
- **Compliance-Driven→Performance-Driven.** 100% karyawan wajib terdaftar tepat waktu; kalender iuran & rekonsiliasi mencegah denda dan gap perlindungan.
- **Data-Driven HR.** Selisih data karyawan vs portal BPJS dilacak & ditutup terukur (reconciliation rate, on-time enrollment).
- **Employer of Choice 2030.** Perlindungan jaminan sosial yang rapi adalah bagian dari pengalaman karyawan yang dipercaya.

---

## Konteks Penggunaan

Aktifkan skill saat: mendaftarkan karyawan baru ke BPJS, menonaktifkan kepesertaan karyawan keluar/pensiun, memperbarui data keluarga/upah, menghitung & merekonsiliasi iuran, atau menyiapkan pelaporan kepesertaan & iuran rutin.

---

## Kerangka Pengetahuan Inti

- **Program BPJS Ketenagakerjaan:** JHT, JP, JKK, JKM — basis perhitungan iuran & porsi perusahaan/karyawan.
- **BPJS Kesehatan:** kepesertaan PPU, batas upah, anggota keluarga tertanggung.
- **Pemicu perubahan:** join, resign, pensiun, mutasi, perubahan upah, penambahan/pengurangan anggota keluarga (dari #27).
- **Kanal & portal:** SIPP/e-Dabu dan portal BPJS untuk registrasi, mutasi, dan pelaporan.
- **Rekonsiliasi:** mencocokkan data kepesertaan & iuran antara HRIS, payroll (#8), dan portal BPJS.

---

## Langkah-Langkah Utama

### Langkah 1 — Tarik data & pemicu perubahan
Ambil data karyawan & keluarga dari #4; terima pemicu status (masuk/keluar/mutasi/perubahan upah) dari #27.

### Langkah 2 — Proses kepesertaan di portal
Daftarkan/perbarui/nonaktifkan kepesertaan di portal BPJS sesuai pemicu; pastikan upah dasar iuran benar.

### Langkah 3 — Hitung & sampaikan iuran
Hitung iuran per program (porsi perusahaan & karyawan); sampaikan angka potongan & beban ke payroll (#8).

### Langkah 4 — Rekonsiliasi data & iuran
Cocokkan kepesertaan HRIS vs portal BPJS vs payroll; tutup selisih dan dokumentasikan koreksi.

### Langkah 5 — Lapor & arsip
Susun laporan kepesertaan & iuran rutin; arsipkan bukti; salurkan data agregat ke pelaporan (#22).

---

## Output yang Diharapkan
- Data kepesertaan BPJS yang mutakhir & lengkap
- Perhitungan iuran per program + angka untuk payroll (#8)
- Laporan rekonsiliasi kepesertaan & iuran (HRIS↔portal↔payroll)
- Bukti registrasi/mutasi & arsip pelaporan

---

## Indikator Keberhasilan
- 100% karyawan wajib terdaftar tepat waktu; tidak ada gap perlindungan
- Iuran dibayar & dilaporkan tepat waktu tanpa denda
- Rekonsiliasi data karyawan vs portal nihil selisih signifikan
- Perubahan status terefleksi di portal dalam SLA yang ditetapkan

---

## Tools/Metode/Dokumen Acuan
Portal BPJS (SIPP/e-Dabu), HRIS/payroll system, checklist verifikasi kepesertaan, formula iuran per program, peraturan BPJS & UU jaminan sosial, checklist rekonsiliasi, HIT-AD.JS.02 Rev.5, dan **HR Strategic Guidance ("HR as a Driver of Organizational Performance")**.

---

## Pertimbangan Kepatuhan & Guardrail
- **Kewajiban hukum:** kepesertaan BPJS bersifat wajib — keterlambatan/kelalaian berisiko denda & sanksi; rujuk #2 Labor Law untuk ketentuan terkini.
- **Akurasi upah dasar:** salah upah dasar membuat iuran & manfaat keliru; selalu sinkron dengan komponen upah di #8.
- **Data pribadi & keluarga:** lindungi data kepesertaan & anggota keluarga; akses sesuai kebutuhan.
- Skill ini **mengurus jaminan sosial wajib**; benefit non-BPJS dikelola #33; klaim medis di #17/#34; perhitungan gaji menyeluruh di #8.

---

## Tips Praktis
- Sinkronkan update kepesertaan dengan cut-off payroll; perubahan terlambat memicu koreksi iuran berantai.
- Rekonsiliasi bulanan kecil jauh lebih murah daripada audit kepesertaan tahunan yang menemukan tumpukan selisih.
- Saat karyawan pensiun, koordinasikan penonaktifan & pencairan JHT lebih awal sebagai bagian offboarding (#23).

---

## Integrasi & Reuse
Skill ini adalah **gerbang jaminan sosial** dalam ekosistem payroll: ia menerima pemicu status dari #27, data dari #4, lalu memberi angka iuran ke #8 dan data agregat ke #22. Berbeda tegas dari #33 (benefit non-BPJS) dan #17/#34 (klaim medis), sehingga tiga area benefit tidak saling tumpang tindih. Lantai hukumnya di-reuse dari #2 tanpa duplikasi.
