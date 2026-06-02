---
name: hris-data-management
description: >
  Gunakan skill ini saat pengguna yang memegang peran Head of HR Development;
  HRIS Specialist; Organization Development Specialist; Talent Development Officer;
  Head of Human Resources; Head of HR Operations membutuhkan panduan tentang HRIS &
  data management.
  Trigger juga saat percakapan menyebut topik: HRIS, sistem informasi HR, master data
  karyawan, input/integritas data, hak akses (user access), laporan/dashboard HR,
  data cleansing, kualitas data, people analytics hub, self-service, atau integrasi
  data HR ke payroll.
---

# HRIS & Data Management

**Deskripsi:** Kemampuan mengoperasikan dan mengelola sistem informasi HR — termasuk input data, pengaturan akses, dan pembuatan laporan — sebagai fondasi data yang akurat dan ter-governance untuk seluruh fungsi HR. Skill ini menjadikan data HR sumber kebenaran tunggal yang menopang administrasi, *self-service*, dan pengambilan keputusan berbasis bukti.

**Relevan untuk:** Head of HR Development; HRIS Specialist; Organization Development Specialist; Talent Development Officer; Head of Human Resources; Head of HR/Plant/Distribution HR Operations; Head of Payroll Management; Personel Administration Coordinator

**Metadata:** Fase 2 (Fondasi Framework HR) · Kategori: Teknikal (HRIS, Data & Administration) · Skill #4 · Dependensi: Organization Design & Job Evaluation (#3) untuk master data jabatan · Di-reuse oleh: Fase 3 (#26 HR Data Entry, #27 HRIS Update), Fase 6 (integrasi payroll), dan seluruh skill berbasis analytics (#29).

---

## Arah Strategis (selaras HR Strategic Guidance)

Skill ini adalah jangkar pilar **Data-Driven HR** dan enabler **HR Operations** digital. Setiap pekerjaan data diarahkan ke:

- **Key Result — matikan HRIS Hefaistos & HRD Web (Oktober 2028).** Skill ini berada di garis depan target tersebut: rancang data, migrasi, dan tata kelola yang kompatibel dengan ekosistem HRIS/self-service baru, serta dukung *decommissioning* sistem lama.
- **People-Analytics Hub & Data Governance.** Bangun *single source of truth* yang ter-governance: metric dictionary, access model berbasis role, dan aturan kualitas data.
- **Self-service sebagai kanal utama.** Dorong transaksi rutin (cuti, izin, info personalia) ke self-service, lalu perluas ke tugas kompleks (payroll, appraisal) — mengurangi beban administratif.
- **Evidence-based decisions.** Sediakan dashboard eksekutif & tim agar keputusan SDM berbasis data, bukan kebiasaan; tautkan ke ROI of HR.
- **Cost Center → Value-Driven.** Otomasi dan kualitas data memangkas error & waktu administratif, menggeser HR ke peran penambah nilai.
- **Privacy & integritas.** Tata kelola akses dan kualitas data menjaga kepatuhan dan kepercayaan.

---

## Konteks Penggunaan

Aktifkan skill saat: administrasi karyawan, reporting manajemen, penyiapan integrasi payroll, analitik HR, penataan hak akses, *data cleansing*, migrasi/penggantian sistem HRIS, atau pembangunan dashboard HR.

---

## Kerangka Pengetahuan Inti

- **Master data management:** struktur data karyawan/jabatan, *single source of truth*, dan keterkaitan dengan job architecture (#3).
- **Kualitas & integritas data:** validasi, *data cleansing*, deteksi duplikasi/anomali, dan audit trail.
- **Access control & keamanan:** user access matrix berbasis role, prinsip *least privilege*, segregasi tugas.
- **Reporting & analytics:** penyusunan laporan dan dashboard (Excel/BI), definisi metrik baku (metric dictionary).
- **Integrasi & migrasi:** keterhubungan HRIS dengan payroll/kehadiran, prinsip migrasi data aman saat mengganti sistem.

---

## Langkah-Langkah Utama

### Langkah 1 — Govern & definisikan
Tetapkan metric dictionary, pemilik data, kadensi refresh, dan aturan kualitas sebelum mengolah data.

### Langkah 2 — Kelola master data & integritas
Input/maintain data karyawan & jabatan; jalankan validasi dan *data cleansing*; catat log perubahan.

### Langkah 3 — Atur akses & keamanan
Susun user access matrix berbasis role; terapkan least privilege dan segregasi tugas.

### Langkah 4 — Bangun laporan & dashboard
Susun laporan tepat waktu dan dashboard eksekutif/tim sesuai definisi metrik baku.

### Langkah 5 — Integrasi, migrasi, & evaluasi
Hubungkan data ke payroll/analytics; kelola migrasi aman saat penggantian sistem; pantau adopsi self-service dan kualitas data secara berkala.

---

## Output yang Diharapkan
- Database HR (master data akurat)
- Laporan HRIS & dashboard HR
- User access matrix
- Data cleansing log & metric dictionary
- Rencana/dokumentasi integrasi & migrasi data

---

## Indikator Keberhasilan
- Data akurat, mutakhir, dan menjadi sumber kebenaran tunggal
- Laporan tepat waktu; error input menurun
- Akses terkendali sesuai role
- Self-service menjadi kanal utama transaksi rutin
- Kesiapan data mendukung *decommissioning* HRIS lama (2028)

---

## Tools/Metode/Dokumen Acuan
HRIS, Excel/BI dashboard, SOP data, user access control, data validation checklist, metric dictionary, HIT-AD.JS.02 Rev.5, dan **HR Strategic Guidance ("HR as a Driver of Organizational Performance")**.

---

## Pertimbangan Kepatuhan & Guardrail
- **Privasi & perlindungan data pribadi karyawan:** batasi akses, terapkan retensi yang wajar, dan gunakan data agregat untuk analitik.
- **Akurasi kritis untuk payroll:** kesalahan data dapat berdampak langsung ke gaji — terapkan validasi berlapis dan rujuk skill Payroll (Fase 6) saat integrasi.
- **Migrasi sistem berisiko:** lakukan backup, rekonsiliasi, dan uji paralel sebelum mematikan sistem lama.
- Skill ini mengelola **sistem & data**, bukan menafsir kebijakan; untuk aspek legal data rujuk #2.

---

## Tips Praktis
- Definisikan metrik dan pemilik data lebih dulu — dashboard hanya sebaik definisinya.
- Terapkan least privilege secara konsisten; tinjau hak akses berkala.
- Jadikan data cleansing rutin, bukan proyek sekali jalan.
- Saat migrasi, jalankan uji paralel sebelum decommissioning sistem lama.

---

## Integrasi & Reuse
Skill ini menyimpan dan menyajikan data dari hampir semua skill lain: menampung master data jabatan dari Organization Design (#3), memasok data untuk Manpower Planning & Workforce Analytics (#29), dan menjadi dasar bagi administrasi data operasional (Fase 3, #26/#27) serta integrasi payroll (Fase 6). Bersama #29, skill ini mewujudkan tema lintas-fungsi *Data-Driven HR* di seluruh roadmap.
