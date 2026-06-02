---
name: payroll-tax-administration
description: >
  Gunakan skill ini saat pengguna yang memegang peran Payroll Officer; Head of Payroll Management;
  Employee Administrator; Head of Plant HR Operations; Head of Distribution HR Operations membutuhkan
  panduan tentang perhitungan gaji, administrasi penggajian, dan pelaporan pajak.
  Trigger juga saat percakapan menyebut topik: perhitungan gaji, payroll run, PPh 21, potongan gaji,
  komponen upah, payroll register, payslip/slip gaji, THR, rekonsiliasi payroll, pelaporan pajak,
  bukti potong, atau kewajiban iuran wajib dalam penggajian.
---

# Payroll & Tax Administration

**Deskripsi:** Kemampuan **menghitung gaji, mengelola transaksi penggajian, serta menangani pelaporan pajak dan iuran wajib**. Skill ini adalah **mesin hitung-dan-bayar** siklus payroll: mengubah data masukan (gaji pokok, tunjangan, kehadiran, lembur, potongan) menjadi payroll register dan payslip yang akurat, lalu memenuhi kewajiban PPh 21 dan iuran wajib secara tepat waktu. Fokusnya pada **eksekusi perhitungan & kepatuhan transaksional payroll**, bukan analisis strategi remunerasi (itu #9).

**Relevan untuk:** Payroll Officer; Head of Payroll Management; Employee Administrator; Head of Plant HR Operations; Head of Distribution HR Operations

**Metadata:** Fase 6 (Spesialisasi Finansial-Administratif + Capstone / Payroll Management) · Kategori: Payroll, Benefit & Employee Services · Skill #8 · Tahap A (core payroll) · Dependensi reuse: #4 HRIS (single source of truth master data & komponen gaji), #36 Attendance & Overtime (data kehadiran/lembur sebagai input), #18 BPJS (angka iuran sebagai potongan), #2 Labor Law (UMK, lembur, THR, PPh 21), #1 Strategic HR (frame kebijakan reward) · Pembeda: #8 = **eksekusi perhitungan & pajak**; #9 = analisis/desain struktur remunerasi; #36 = data kehadiran/lembur yang memberi masukan ke #8; #18 = administrasi BPJS spesifik. Catatan struktur: **Head of Payroll Management melapor ke COO**, bukan Head of HR.

---

## Arah Strategis (selaras HR Strategic Guidance)

Skill ini mengaktifkan pilar **HR Operations** (Proactive Compliance & Risk Management) dan **Data-Driven HR**, serta menerapkan pergeseran **Cost Center→Value-Driven** dan **Compliance-Driven→Performance-Driven**: payroll bukan sekadar pusat biaya yang membayar, melainkan proses terkontrol, terukur, dan patuh yang menjaga kepercayaan karyawan.

- **Key Result — decommission HRIS lama (Hefaistos & HRD Web) Okt 2028.** Perhitungan payroll wajib bersumber dari HRIS baru (#4) sebagai single source of truth; payroll menjadi konsumen data terbesar sehingga keberhasilan migrasi diuji di sini.
- **Compliance-Driven→Performance-Driven.** PPh 21 dan iuran wajib dipenuhi proaktif (kalender kewajiban, kontrol pra-bayar), bukan reaktif saat ditegur.
- **Data-Driven HR.** Akurasi diukur (error rate, koreksi gaji, on-time payment, biaya payroll per headcount), bukan diasumsikan.
- **Cost Center→Value-Driven.** Rekonsiliasi & analitik biaya payroll memberi visibilitas cost untuk keputusan bisnis.

---

## Konteks Penggunaan

Aktifkan skill saat: menjalankan siklus payroll bulanan, membayar THR/bonus, menghitung PPh 21 & potongan, menyiapkan payroll register/payslip, rekonsiliasi payroll vs GL, audit payroll, atau menindaklanjuti koreksi gaji.

---

## Kerangka Pengetahuan Inti

- **Komponen upah:** gaji pokok, tunjangan tetap & tidak tetap, lembur, THR, bonus, potongan (pinjaman, iuran, pajak).
- **PPh 21:** metode perhitungan (gross/gross-up/net), TER (Tarif Efektif Rata-rata), PTKP, bukti potong, pelaporan masa & tahunan.
- **Iuran wajib:** BPJS Kesehatan & Ketenagakerjaan (porsi perusahaan & karyawan) — angka diterima dari #18.
- **Siklus payroll:** cut-off → kumpulkan input (kehadiran/lembur #36, perubahan status #27) → hitung → review → bayar → rekonsiliasi → lapor.
- **Kontrol & rekonsiliasi:** four-eyes review, variance check bulan-ke-bulan, rekonsiliasi ke GL/bank, audit trail.

---

## Langkah-Langkah Utama

### Langkah 1 — Kumpulkan & validasi input
Tarik master data & komponen gaji dari #4; terima data kehadiran/lembur tervalidasi dari #36 dan perubahan status dari #27; pastikan cut-off jelas.

### Langkah 2 — Hitung gaji & potongan
Hitung komponen upah, lembur, dan potongan; terapkan iuran BPJS (dari #18) dan PPh 21 sesuai metode & PTKP yang berlaku.

### Langkah 3 — Review & kontrol
Jalankan variance check vs siklus sebelumnya; lakukan four-eyes review pada anomali; pastikan tidak ada di bawah UMK (rujuk #2).

### Langkah 4 — Bayar & terbitkan dokumen
Hasilkan payroll register, payslip, dan instruksi bayar; eksekusi pembayaran; rekonsiliasi ke bank/GL.

### Langkah 5 — Lapor kewajiban & arsip
Setor & laporkan PPh 21 dan iuran wajib tepat waktu; terbitkan bukti potong; arsipkan untuk audit (data agregat ke #22).

---

## Output yang Diharapkan
- Payroll register & payslip per karyawan
- Perhitungan & laporan PPh 21 (masa/tahunan) + bukti potong
- Laporan iuran wajib & rekonsiliasi payroll (vs GL/bank)
- Log koreksi gaji & audit trail

---

## Indikator Keberhasilan
- Payroll tepat waktu (on-time payment 100%) dan akurat (error/koreksi minim)
- Kewajiban PPh 21 & iuran wajib terpenuhi tanpa denda keterlambatan
- Rekonsiliasi nihil selisih; data payroll terdokumentasi & audit-ready
- Parallel run ≥1 siklus penuh lolos sebelum cut-over sistem baru

---

## Tools/Metode/Dokumen Acuan
Payroll system, formula payroll, PPh 21 (TER/PTKP), data BPJS, data absensi & lembur, checklist rekonsiliasi, four-eyes control, UU Ketenagakerjaan & peraturan perpajakan, HIT-AD.JS.02 Rev.5, dan **HR Strategic Guidance ("HR as a Driver of Organizational Performance")**.

---

## Pertimbangan Kepatuhan & Guardrail
- **Akurasi kritis:** kesalahan payroll berdampak langsung ke gaji karyawan — wajib four-eyes review & parallel run ≥1 siklus penuh sebelum cut-over; libatkan Internal Audit.
- **Rujukan regulasi terkini:** PPh 21, PTKP, UMK, dan ketentuan lembur/THR berubah — selalu konfirmasi versi terbaru via #2 Labor Law; jangan mengarang tarif.
- **Kerahasiaan & segregation of duties:** data gaji bersifat rahasia; pisahkan peran penghitung, pereview, dan pembayar.
- Skill ini **mengeksekusi & melaporkan**; analisis daya saing/struktur remunerasi ada di #9; angka iuran BPJS dikelola #18.

---

## Tips Praktis
- Kunci cut-off lebih awal; input susulan adalah sumber utama koreksi gaji.
- Bandingkan payroll bulan ini vs bulan lalu per komponen — variance yang tak terjelaskan adalah sinyal kesalahan.
- Simpan kertas kerja perhitungan PPh 21; saat audit, kemampuan menelusuri angka jauh lebih penting daripada kecepatan.

---

## Integrasi & Reuse
Skill ini adalah **muara data Fase 1–3**: ia mengonsumsi master data (#4), kehadiran/lembur (#36), perubahan status (#27), dan angka BPJS (#18), lalu menghasilkan pembayaran patuh terhadap #2. Hasil agregatnya mengalir ke pelaporan (#22) dan menjadi masukan analisis remunerasi (#9). Tidak membangun ulang HRIS maupun aturan hukum — keduanya di-reuse sebagai sumber.
