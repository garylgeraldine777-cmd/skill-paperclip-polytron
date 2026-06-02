---
name: hr-data-entry-maintenance
description: >
  Gunakan skill ini saat pengguna yang memegang peran Personel Administrator;
  Recruitment Administrator membutuhkan panduan tentang input dan pemeliharaan data karyawan.
  Trigger juga saat percakapan menyebut topik: input data karyawan, entry data HR, verifikasi
  kelengkapan data, akurasi data di titik input, arsip personalia, rekap data, log perubahan data,
  data cleansing tingkat transaksi, atau menjaga kualitas master data karyawan.
---

# HR Data Entry & Maintenance

**Deskripsi:** Kemampuan memasukkan dan memelihara data karyawan secara akurat dan tertib di tingkat transaksi harian. Skill ini adalah **garis depan kualitas data**: memastikan setiap data yang masuk lengkap, valid, dan konsisten sejak titik input, sehingga *single source of truth* yang dikelola HRIS (#4) tetap dapat dipercaya untuk administrasi, payroll, dan analitik.

**Relevan untuk:** Personel Administrator; Recruitment Administrator

**Metadata:** Fase 3 (Tulang Punggung Operasional) · Kategori: HRIS, Data & Administration · Skill #26 · Dependensi: #4 HRIS & Data Management (governance & master data, Fase 2) · Pembeda: #26 = **input & pemeliharaan data mentah** di titik transaksi; #27 = **pemutakhiran & pemeliharaan sistem HRIS**; #4 = **arsitektur & tata kelola** data.

---

## Arah Strategis (selaras HR Strategic Guidance)

Skill ini adalah fondasi operasional tema **Data-Driven HR**. Kualitas keputusan berbasis data hanya sebaik kualitas data di titik masuknya.

- **Garbage-in, garbage-out.** Akurasi entry menentukan keandalan dashboard, ROI of HR, dan *predictive analytics* (#29) — data buruk membatalkan semua analitik di atasnya.
- **Mendukung decommissioning HRIS lama (2028).** Data yang bersih dan terstruktur di tingkat transaksi memuluskan migrasi dan menurunkan risiko saat sistem lama dimatikan.
- **Cost Center → Value-Driven.** Validasi di sumber memangkas rework, koreksi payroll, dan temuan audit — menghemat waktu dan biaya.
- **Self-service.** Saat transaksi rutin bergeser ke self-service, peran berkembang dari entry manual ke **verifikasi & penjagaan kualitas** data yang masuk dari karyawan.

---

## Konteks Penggunaan

Aktifkan skill saat: input data karyawan baru/perubahan, verifikasi kelengkapan dokumen, rekap data berkala, pemeliharaan arsip personalia, *data cleansing* tingkat transaksi, dan persiapan data untuk audit atau migrasi.

---

## Kerangka Pengetahuan Inti

- **Standar input data:** format baku, field wajib, dan aturan penamaan (selaras metric dictionary #4).
- **Validasi di sumber:** pengecekan kelengkapan, konsistensi, dan deteksi duplikasi/anomali sebelum simpan.
- **Audit trail:** pencatatan log perubahan (siapa, kapan, apa) untuk ketertelusuran.
- **Arsip & filing:** penyimpanan dokumen pendukung yang mudah ditelusuri dan retensi yang wajar.
- **Privasi data:** penanganan data pribadi sesuai prinsip akses *least privilege* (#4).

---

## Langkah-Langkah Utama

### Langkah 1 — Verifikasi sebelum input
Periksa kelengkapan dan keabsahan dokumen sumber sebelum data dimasukkan.

### Langkah 2 — Input sesuai standar
Masukkan data mengikuti format baku & field wajib; hindari entri bebas yang tidak terstandar.

### Langkah 3 — Validasi & deteksi anomali
Jalankan pengecekan konsistensi dan duplikasi; perbaiki sebelum data tersimpan permanen.

### Langkah 4 — Catat perubahan & arsipkan
Rekam log perubahan; simpan dokumen pendukung di arsip yang tertelusur.

### Langkah 5 — Rekap & pelihara berkala
Buat rekap/laporan; jalankan *data cleansing* rutin dan tindak lanjuti perubahan data.

---

## Output yang Diharapkan
- Master data karyawan yang akurat & mutakhir (kontribusi tingkat transaksi)
- Rekap & laporan data berkala
- Log perubahan data (audit trail)
- Arsip dokumen personalia yang tertata

---

## Indikator Keberhasilan
- Data lengkap dan valid; kesalahan input menurun
- Dokumen mudah ditelusuri saat dibutuhkan
- Tidak ada duplikasi/anomali yang lolos ke sistem
- Data siap dipakai payroll & analitik tanpa koreksi ulang

---

## Tools/Metode/Dokumen Acuan
HRIS, Excel, form administrasi, data validation, checklist dokumen, filing system, HIT-AD.JS.02 Rev.5, dan **HR Strategic Guidance ("HR as a Driver of Organizational Performance")**.

---

## Pertimbangan Kepatuhan & Guardrail
- **Privasi data pribadi karyawan:** akses dan tampilkan hanya yang diperlukan; jangan menyalin data sensitif ke media tak terkendali.
- **Akurasi kritis untuk payroll:** kesalahan kecil dapat berdampak ke gaji — terapkan prinsip *verifikasi sebelum simpan*.
- Skill ini **menjalankan entry & pemeliharaan**, mengikuti tata kelola yang ditetapkan #4 — bukan mengubah arsitektur data.

---

## Tips Praktis
- Validasi di sumber selalu lebih murah daripada koreksi di hilir.
- Gunakan daftar field wajib sebagai checklist agar tidak ada data parsial.
- Jadikan log perubahan kebiasaan, bukan beban — ia menyelamatkan saat audit.

---

## Integrasi & Reuse
Skill ini adalah konsumen operasional #4 (HRIS & Data Management): menjaga kualitas data di titik masuk yang kemudian dipelihara di sistem oleh #27 (HRIS Update). Data bersih yang dihasilkannya menopang #16 (laporan operasional), #29 (analytics), dan integrasi payroll Fase 6.
