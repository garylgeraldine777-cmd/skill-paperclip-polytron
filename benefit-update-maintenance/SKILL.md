---
name: benefit-update-maintenance
description: >
  Gunakan skill ini saat pengguna yang memegang peran Employee Services Staff membutuhkan panduan tentang
  pemutakhiran & pemeliharaan data benefit karyawan agar sesuai kebijakan.
  Trigger juga saat percakapan menyebut topik: master data benefit, kepesertaan benefit non-BPJS,
  plafon/limit benefit, eligibility benefit, enrollment & perubahan benefit, konfigurasi paket benefit,
  pemeliharaan data tunjangan/asuransi, atau memastikan data benefit selaras dengan kebijakan.
---

# Benefit Update & Maintenance

**Deskripsi:** Kemampuan **memperbarui data benefit karyawan dan memastikan kesesuaian dengan kebijakan**. Skill ini adalah **steward master data benefit**: menjaga data kepesertaan, eligibility, plafon, dan konfigurasi paket benefit (non-BPJS) selalu mutakhir dan konsisten dengan kebijakan, sehingga klaim & pembayaran benefit berjalan benar. Fokusnya pada **pemeliharaan data benefit sebagai acuan** — berbeda dari jaminan sosial BPJS (itu #18), pemrosesan klaim (itu #17), dan analisis struktur benefit (itu #9).

**Relevan untuk:** Employee Services Staff

**Metadata:** Fase 6 (Spesialisasi Finansial-Administratif + Capstone / Payroll Management) · Kategori: Payroll, Benefit & Employee Services · Skill #33 · Tahap C (medical & benefit) · Dependensi reuse: #4 HRIS (master data karyawan & benefit), #27 HRIS Update (perubahan status pemicu eligibility), #9 C&B Analysis (keputusan desain benefit yang dipelihara datanya), #17 Claims (konsumen master plafon/eligibility) · Pembeda: #33 = **pemeliharaan master data benefit (non-BPJS) sesuai kebijakan**; #18 = kepesertaan BPJS; #17 = pemrosesan klaim; #34 = verifikasi & laporan klaim; #9 = analisis/desain struktur benefit (sumber keputusan, bukan duplikat).

---

## Arah Strategis (selaras HR Strategic Guidance)

Skill ini mengaktifkan pilar **Data-Driven HR** dan **HR Operations**, serta menerapkan pergeseran **Reactive→Proactive** dan **Compliance-Driven→Performance-Driven**: data benefit dijaga akurat di hulu sehingga layanan benefit (klaim, pembayaran) berjalan benar tanpa perbaikan dadakan.

- **Key Result — decommission HRIS lama Okt 2028.** Master data benefit wajib hidup di HRIS baru (#4) sebagai single source of truth; integritas data benefit menguji konsolidasi sistem.
- **Reactive→Proactive.** Perubahan eligibility (promosi, mutasi, status keluarga) diperbarui proaktif begitu pemicu muncul (#27), bukan saat klaim ditolak.
- **Compliance-Driven→Performance-Driven.** Data benefit selalu selaras dengan kebijakan terbaru sehingga setiap transaksi benefit dapat dipertanggungjawabkan.
- **Employer of Choice 2030.** Data benefit yang rapi membuat janji benefit kepada karyawan benar-benar terealisasi.

---

## Konteks Penggunaan

Aktifkan skill saat: memperbarui kepesertaan/eligibility benefit, mengonfigurasi plafon & paket benefit, menyelaraskan data benefit dengan kebijakan baru (keputusan #9), atau menindaklanjuti perubahan status yang memengaruhi hak benefit.

---

## Kerangka Pengetahuan Inti

- **Master data benefit:** jenis benefit non-BPJS (tunjangan, asuransi tambahan, fasilitas), plafon/limit, masa berlaku.
- **Eligibility rules:** kelayakan berdasarkan grade, masa kerja, status, tanggungan; pemicu perubahan dari #27.
- **Konfigurasi paket:** pemetaan benefit ke grade/kelompok karyawan; sinkron dengan keputusan desain #9.
- **Konsistensi kebijakan:** memastikan data benefit mencerminkan kebijakan terbaru; kontrol versi kebijakan.
- **Dampak hilir:** master ini menjadi acuan kelayakan bagi klaim #17 dan analisis #34.

---

## Langkah-Langkah Utama

### Langkah 1 — Terima pemicu perubahan & keputusan
Tangkap perubahan status dari #27 dan keputusan desain benefit dari #9 yang perlu tercermin di data.

### Langkah 2 — Perbarui master data benefit
Update kepesertaan, eligibility, plafon, & konfigurasi paket di HRIS (#4) sesuai pemicu.

### Langkah 3 — Validasi terhadap kebijakan
Pastikan data sesuai kebijakan & aturan eligibility terbaru; tandai & koreksi inkonsistensi.

### Langkah 4 — Sinkronkan ke proses hilir
Pastikan master plafon/eligibility tersedia & akurat bagi pemrosesan klaim (#17) dan verifikasi (#34).

### Langkah 5 — Dokumentasi & rekap
Catat perubahan (log), arsipkan, dan salurkan rekap data benefit ke pelaporan (#22).

---

## Output yang Diharapkan
- Master data benefit yang mutakhir & sesuai kebijakan
- Konfigurasi plafon & eligibility per kelompok karyawan
- Log perubahan data benefit
- Rekap data benefit untuk pelaporan (#22)

---

## Indikator Keberhasilan
- Data benefit akurat & selaras kebijakan; klaim jarang ditolak karena data salah
- Perubahan eligibility terefleksi tepat waktu sesuai SLA
- Selisih/kesalahan administrasi benefit minim
- Master data konsisten sebagai acuan klaim (#17) & verifikasi (#34)

---

## Tools/Metode/Dokumen Acuan
HRIS/payroll system, policy benefit, matriks eligibility & plafon, checklist verifikasi, kontrol versi kebijakan, data validation, HIT-AD.JS.02 Rev.5, dan **HR Strategic Guidance ("HR as a Driver of Organizational Performance")**.

---

## Pertimbangan Kepatuhan & Guardrail
- **Selaras kebijakan:** perubahan data benefit harus berdasar kebijakan/keputusan resmi (#9), bukan permintaan ad hoc.
- **Single source of truth:** pelihara data di HRIS resmi (#4); hindari salinan benefit yang tidak sinkron.
- **Privasi:** data benefit & tanggungan bersifat pribadi — akses berbasis kebutuhan.
- Skill ini **memelihara data benefit non-BPJS**; kepesertaan BPJS di #18; pemrosesan klaim di #17; verifikasi & laporan di #34; analisis/desain struktur di #9.

---

## Tips Praktis
- Tautkan setiap perubahan benefit ke pemicunya (perubahan status #27 atau kebijakan #9); perubahan tanpa pemicu adalah tanda kesalahan.
- Uji master plafon dengan satu skenario klaim sebelum dirilis; data benefit yang salah baru terlihat saat klaim gagal.
- Jaga kontrol versi kebijakan benefit; banyak kesalahan berasal dari memakai aturan lama.

---

## Integrasi & Reuse
Skill ini adalah **penjaga data benefit** yang memberi acuan kelayakan bagi pemrosesan klaim (#17) dan verifikasi (#34). Ia menerima pemicu dari #27 dan keputusan desain dari #9, memelihara datanya di #4, lalu mengalirkan rekap ke #22. Dipisah tegas dari #18 (BPJS) agar kepesertaan wajib dan benefit perusahaan tidak tercampur.
