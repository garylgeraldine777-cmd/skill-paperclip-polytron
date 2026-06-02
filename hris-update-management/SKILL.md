---
name: hris-update-management
description: >
  Gunakan skill ini saat pengguna yang memegang peran HRIS Specialist; Personel Administrator
  membutuhkan panduan tentang pemutakhiran dan pemeliharaan sistem HRIS.
  Trigger juga saat percakapan menyebut topik: update HRIS, pemeliharaan sistem HR, perubahan status
  karyawan (mutasi/promosi/demosi/pensiun), integritas data sistem, rekonsiliasi data HRIS,
  modul HRIS, migrasi/transisi sistem HR, atau menjaga sinkronisasi data antar-modul.
---

# HRIS Update & Management

**Deskripsi:** Kemampuan memperbarui dan memelihara sistem HRIS agar data tetap utuh, sinkron antar-modul, dan mencerminkan kondisi terkini karyawan. Skill ini menangani **transaksi tingkat sistem** — memproses perubahan status (mutasi, promosi, demosi, perubahan jabatan/lokasi, pensiun), pemeliharaan modul, dan rekonsiliasi data — sehingga HRIS dapat diandalkan sebagai sumber data operasional dan payroll.

**Relevan untuk:** HRIS Specialist; Personel Administrator

**Metadata:** Fase 3 (Tulang Punggung Operasional) · Kategori: HRIS, Data & Administration · Skill #27 · Dependensi: #4 HRIS & Data Management (governance & arsitektur, Fase 2) · Pembeda: #27 = **pemutakhiran & pemeliharaan sistem** (transaksi status, integritas antar-modul); #26 = **input data mentah** di titik transaksi; #4 = **arsitektur, governance, migrasi strategis**.

---

## Arah Strategis (selaras HR Strategic Guidance)

Skill ini berada di jantung tema **Data-Driven HR** dan menjadi pelaksana harian Key Result digitalisasi HR Operations.

- **Key Result — matikan HRIS Hefaistos & HRD Web (Okt 2028).** Skill ini garda depan transisi: menjaga integritas data selama migrasi, menjalankan uji paralel, dan memastikan modul baru sinkron sebelum sistem lama dimatikan.
- **Single source of truth.** Setiap perubahan status diproses tepat waktu agar seluruh modul (kehadiran, payroll, kinerja) menampilkan data yang sama.
- **Mendukung self-service.** Memelihara modul self-service agar transaksi rutin karyawan berjalan andal dan datanya terkonsolidasi.
- **Audit-ready & integritas.** Rekonsiliasi berkala dan jejak perubahan menjaga data siap-audit dan mencegah selisih yang berdampak ke gaji.

---

## Konteks Penggunaan

Aktifkan skill saat: memproses perubahan status/data karyawan di HRIS, memelihara dan memperbarui modul, melakukan rekonsiliasi antar-modul, mendukung migrasi/transisi sistem, dan menyelesaikan ketidaksesuaian data sistem.

---

## Kerangka Pengetahuan Inti

- **Manajemen transaksi status:** mutasi, promosi/demosi, perubahan jabatan/lokasi, pensiun, dan dampaknya antar-modul.
- **Integritas & sinkronisasi data:** konsistensi antar-modul, rekonsiliasi, dan penanganan selisih.
- **Pemeliharaan modul:** konfigurasi dasar, kalender/parameter, dan pengelolaan master referensi.
- **Migrasi & uji paralel:** backup, validasi, rekonsiliasi pra/pasca-migrasi, prinsip *decommissioning* aman.
- **Kontrol & jejak audit:** log transaksi sistem dan otorisasi perubahan (selaras access model #4).

---

## Langkah-Langkah Utama

### Langkah 1 — Terima & validasi permintaan perubahan
Pastikan dokumen pendukung & otorisasi lengkap sebelum memproses perubahan status.

### Langkah 2 — Proses transaksi di sistem
Lakukan pemutakhiran sesuai prosedur; perhatikan tanggal efektif dan dampak antar-modul.

### Langkah 3 — Rekonsiliasi antar-modul
Pastikan data konsisten di kehadiran/payroll/kinerja; selesaikan selisih bila ada.

### Langkah 4 — Catat & amankan
Rekam log transaksi sistem; jaga otorisasi & jejak audit.

### Langkah 5 — Dukung migrasi & evaluasi
Saat transisi sistem, jalankan backup, uji paralel, dan rekonsiliasi sebelum mematikan sistem lama; pantau integritas berkala.

---

## Output yang Diharapkan
- HRIS yang mutakhir dan sinkron antar-modul
- Catatan transaksi status karyawan (audit trail)
- Laporan rekonsiliasi data
- Dokumentasi & checklist migrasi/transisi sistem

---

## Indikator Keberhasilan
- Data sistem akurat, sinkron, dan menjadi sumber kebenaran tunggal
- Perubahan status diproses tepat waktu dengan tanggal efektif benar
- Selisih antar-modul minimal; tidak berdampak ke payroll
- Kesiapan sistem mendukung *decommissioning* HRIS lama (2028)

---

## Tools/Metode/Dokumen Acuan
HRIS, Excel, form administrasi, data validation, checklist dokumen, filing system, prosedur migrasi & uji paralel, HIT-AD.JS.02 Rev.5, dan **HR Strategic Guidance ("HR as a Driver of Organizational Performance")**.

---

## Pertimbangan Kepatuhan & Guardrail
- **Migrasi & transisi berisiko:** wajib backup, rekonsiliasi, dan uji paralel sebelum mematikan sistem lama.
- **Akurasi kritis untuk payroll:** rujuk Fase 6 saat perubahan berdampak ke perhitungan gaji.
- Patuhi access model & otorisasi #4; skill ini **memelihara sistem**, bukan mendefinisikan ulang arsitekturnya.

---

## Tips Praktis
- Perhatikan tanggal efektif — kesalahan tanggal status sering memicu selisih payroll.
- Rekonsiliasi rutin lebih murah daripada memburu selisih saat tutup buku.
- Saat migrasi, jangan matikan sistem lama sebelum uji paralel bersih beberapa siklus.

---

## Integrasi & Reuse
Skill ini melanjutkan kerja #26 (HR Data Entry): data yang masuk lalu dipelihara dan disinkronkan di sistem. Berdiri di atas tata kelola #4 (HRIS & Data Management) dan memasok data status terkini ke #16 (operasional), #28 (jadwal/kehadiran), serta integrasi payroll Fase 6. Skill ini adalah pelaksana utama transisi menuju HRIS baru (Key Result 2028).
