---
name: data-management-reporting
description: >
  Gunakan skill ini saat pengguna yang memegang peran Payroll Officer; Employee Administrator;
  Employee Services Staff; HR Area; Personel Administration Coordinator membutuhkan panduan tentang
  pengumpulan, verifikasi, dan penyajian data HR/payroll secara akurat dan tepat waktu.
  Trigger juga saat percakapan menyebut topik: rekap & laporan HR, dashboard sederhana, penyajian data,
  verifikasi kelengkapan data, log perubahan data, arsip dokumen, laporan rutin payroll/benefit,
  penyiapan data untuk audit, atau memastikan informasi HR mudah ditelusuri.
---

# Data Management & Reporting

**Deskripsi:** Kemampuan **mengumpulkan, memverifikasi, dan menyajikan data HR secara akurat dan tepat waktu**. Skill ini adalah **lapisan keluaran data (reporting/penyajian)**: merangkum data dari berbagai proses HR/payroll menjadi rekap, laporan rutin, dan dashboard sederhana yang valid, terdokumentasi, dan mudah ditelusuri untuk pengambilan keputusan & audit. Fokusnya pada **penyajian & kualitas data sebagai output** — berbeda dari arsitektur/governance data (itu #4 HRIS, Fase 2) dan input transaksi (itu #26/#27, Fase 3).

**Relevan untuk:** Payroll Officer; Employee Administrator; Employee Services Staff; HR Area; Personel Administration Coordinator

**Metadata:** Fase 6 (Spesialisasi Finansial-Administratif + Capstone / Payroll Management) · Kategori: HRIS, Data & Administration · Skill #22 · Tahap B (attendance & data) · Dependensi reuse: #4 HRIS (sumber data & metric dictionary), #26 HR Data Entry & #27 HRIS Update (sumber input transaksi), #8/#18/#36 (sumber data payroll/benefit/kehadiran yang dilaporkan) · Pembeda: #22 = **penyajian/laporan & kualitas data (output)**; #4 = arsitektur, governance, single source of truth; #26 = input transaksi mentah; #27 = pemutakhiran status; #29 = people analytics strategis (Fase 2). Skill #22 muncul lintas fungsi tetapi di Fase 6 berperan sebagai lapisan pelaporan payroll/benefit.

---

## Arah Strategis (selaras HR Strategic Guidance)

Skill ini mengaktifkan pilar **Data-Driven HR** dan **HR Operations**, serta menerapkan pergeseran **Administrative→Strategic** dan **Reactive→Proactive**: data tidak berhenti sebagai arsip, melainkan disajikan menjadi informasi yang memandu keputusan tepat waktu.

- **Key Result — decommission HRIS lama Okt 2028.** Laporan & dashboard wajib bersumber dari HRIS baru (#4) sebagai single source of truth; konsistensi laporan menguji keberhasilan konsolidasi data.
- **Data-Driven HR.** Kualitas data (kelengkapan, validitas, ketepatan waktu) diukur & dijaga; laporan menjadi basis ROI of HR dan keputusan.
- **Administrative→Strategic.** Penyajian yang baik mengubah tumpukan data administratif menjadi insight yang dapat ditindaklanjuti.
- **Audit-ready.** Dokumen & log perubahan mudah ditelusuri mendukung kepatuhan & audit.

---

## Konteks Penggunaan

Aktifkan skill saat: menyusun rekap/laporan HR atau payroll rutin, membuat dashboard sederhana, memverifikasi kelengkapan & validitas data, menyiapkan data untuk audit, atau menelusuri & mengarsipkan dokumen agar mudah ditemukan.

---

## Kerangka Pengetahuan Inti

- **Pengumpulan & verifikasi:** tarik data dari sumber resmi (#4, #8, #18, #36); cek kelengkapan & validitas sebelum disajikan.
- **Penyajian:** rekap, laporan rutin, dashboard sederhana; pilih metrik yang relevan dengan audiens.
- **Kualitas data:** definisi metrik (metric dictionary dari #4), aturan validasi, deteksi outlier & inkonsistensi.
- **Arsip & telusur:** filing system, penamaan & versi dokumen, log perubahan data.
- **Tepat waktu:** kalender pelaporan, SLA penyajian, otomatisasi rekap berulang.

---

## Langkah-Langkah Utama

### Langkah 1 — Tetapkan kebutuhan & metrik
Tentukan audiens, pertanyaan yang dijawab laporan, dan metrik (gunakan definisi metric dictionary #4 agar konsisten).

### Langkah 2 — Kumpulkan & verifikasi data
Tarik data dari sumber resmi; verifikasi kelengkapan & validitas; tandai & tindak lanjuti anomali ke sumber (#26/#27).

### Langkah 3 — Susun rekap, laporan & dashboard
Olah data menjadi rekap/laporan/dashboard yang ringkas, akurat, dan mudah dibaca.

### Langkah 4 — Sajikan tepat waktu & validasi silang
Distribusikan sesuai kalender/SLA; lakukan cross-check dengan sumber (mis. laporan payroll vs register #8).

### Langkah 5 — Arsip & jaga ketertelusuran
Simpan dengan penamaan & versi konsisten; pelihara log perubahan; pastikan siap audit.

---

## Output yang Diharapkan
- Rekap & laporan HR/payroll rutin yang valid & tepat waktu
- Dashboard sederhana untuk monitoring
- Log perubahan data & arsip dokumen yang mudah ditelusuri
- Data set siap audit

---

## Indikator Keberhasilan
- Data lengkap & valid; kesalahan input menurun terukur
- Laporan tersedia tepat waktu sesuai kalender/SLA
- Dokumen mudah ditemukan & ditelusuri saat audit
- Laporan konsisten dengan sumber resmi (nihil selisih tak terjelaskan)

---

## Tools/Metode/Dokumen Acuan
HRIS, Excel/spreadsheet, form administrasi, data validation, metric dictionary (#4), checklist dokumen, filing & versioning system, kalender pelaporan, HIT-AD.JS.02 Rev.5, dan **HR Strategic Guidance ("HR as a Driver of Organizational Performance")**.

---

## Pertimbangan Kepatuhan & Guardrail
- **Single source of truth:** laporan harus bersumber dari HRIS resmi (#4); hindari salinan data liar yang menimbulkan versi berbeda.
- **Privasi data:** laporan berisi data pribadi/gaji — terapkan akses berbasis kebutuhan & agregasi saat perlu.
- **Konsistensi metrik:** gunakan definisi metrik baku; metrik yang sama harus berarti sama di semua laporan.
- Skill ini **menyajikan & menjaga kualitas output**; arsitektur & governance data ada di #4; input transaksi di #26/#27; analitik prediktif/strategis di #29.

---

## Tips Praktis
- Mulai dari pertanyaan, bukan dari data; laporan yang baik menjawab keputusan, bukan menampilkan semua kolom.
- Otomatiskan rekap berulang; waktu yang dihemat dialihkan ke verifikasi kualitas.
- Selalu cross-check laporan agregat ke sumber transaksinya sekali sebelum dikirim — selisih kecil merusak kepercayaan pada seluruh laporan.

---

## Integrasi & Reuse
Skill ini adalah **jendela output** ekosistem data HR/payroll: ia mengonsumsi data dari #4, #8, #18, #36 dan menyajikannya sebagai laporan & dashboard, tanpa membangun ulang arsitektur (#4) atau melakukan input mentah (#26/#27). Di Fase 6 ia menjadi corong pelaporan payroll/benefit; lintas fungsi, ia memakai metric dictionary #4 agar definisi seragam.
