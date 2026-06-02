---
name: medical-claim-verification-reporting
description: >
  Gunakan skill ini saat pengguna yang memegang peran Medical Administrator membutuhkan panduan tentang
  pemeriksaan (verifikasi) klaim medis dan penyusunan laporan klaim berkala.
  Trigger juga saat percakapan menyebut topik: verifikasi klaim medis, audit klaim, deteksi klaim
  janggal/fraud, kelayakan medis klaim, laporan klaim berkala, analisis utilisasi & tren klaim,
  loss ratio benefit kesehatan, atau rekomendasi pengendalian biaya klaim medis.
---

# Medical Claim Verification & Reporting

**Deskripsi:** Kemampuan **memeriksa klaim medis dan menyusun laporan klaim secara berkala**. Skill ini adalah **lapisan verifikasi mendalam & pelaporan**: memeriksa kelayakan medis & kepatuhan klaim secara teliti (termasuk deteksi anomali/fraud), lalu menyusun laporan dan analisis tren/utilisasi sebagai dasar pengendalian biaya & kebijakan. Fokusnya pada **scrutiny + analitik klaim** — berbeda dari pemrosesan transaksi klaim sehari-hari (itu #17).

**Relevan untuk:** Medical Administrator

**Metadata:** Fase 6 (Spesialisasi Finansial-Administratif + Capstone / Payroll Management) · Kategori: Payroll, Benefit & Employee Services · Skill #34 · Tahap C (medical & benefit) · Dependensi reuse: #17 Medical & Benefit Claims (sumber transaksi klaim yang diverifikasi), #22 Data Management & Reporting (metode penyajian laporan), #35 Pharmaceutical Knowledge (acuan kewajaran obat/tindakan), #4 HRIS (data populasi tertanggung) · Pembeda: #34 = **verifikasi mendalam & pelaporan/analitik klaim**; #17 = pemrosesan & penyelesaian transaksi klaim; #33 = master data benefit; #35 = pengetahuan farmasi/kebijakan kesehatan; #18 = BPJS.

---

## Arah Strategis (selaras HR Strategic Guidance)

Skill ini mengaktifkan pilar **Data-Driven HR** dan **HR Operations** (Proactive Compliance & Risk Management), serta menerapkan pergeseran **Cost Center→Value-Driven** dan **Compliance-Driven→Performance-Driven**: klaim tidak hanya dibayar, tetapi diverifikasi & dianalisis agar biaya terkendali dan kebijakan benefit makin tepat.

- **Cost Center→Value-Driven.** Analisis utilisasi & loss ratio mengubah data klaim menjadi keputusan pengendalian biaya benefit.
- **Compliance-Driven→Performance-Driven.** Deteksi klaim janggal/fraud proaktif melindungi dana benefit; bukan sekadar lolos audit.
- **Data-Driven HR.** Laporan klaim berkala (tren, utilisasi, biaya per kategori) menjadi umpan balik untuk #9 (analisis benefit) dan #35 (kebijakan kesehatan).
- **Employer of Choice 2030.** Benefit kesehatan yang berkelanjutan secara biaya menjaga keberlangsungan paket bagi seluruh karyawan.

---

## Konteks Penggunaan

Aktifkan skill saat: memverifikasi klaim yang dieskalasi atau bernilai besar, mengaudit sampel klaim, mendeteksi pola klaim tidak wajar, menyusun laporan klaim berkala, atau menganalisis utilisasi & biaya untuk rekomendasi pengendalian.

---

## Kerangka Pengetahuan Inti

- **Verifikasi kelayakan medis:** kesesuaian diagnosis-tindakan-obat (acuan #35), kepatuhan polis, kewajaran biaya.
- **Deteksi anomali:** klaim ganda, frekuensi tak wajar, provider berisiko, ketidaksesuaian dokumen.
- **Pelaporan berkala:** rekap klaim per periode/kategori, status penyelesaian, outstanding.
- **Analitik utilisasi & biaya:** utilization rate, loss ratio, biaya per kapita, tren musiman.
- **Rekomendasi:** pengendalian biaya, perbaikan polis, edukasi karyawan, koordinasi provider.

---

## Langkah-Langkah Utama

### Langkah 1 — Tarik data klaim & tetapkan lingkup verifikasi
Ambil transaksi klaim dari #17; tentukan klaim yang diverifikasi penuh (eskalasi, nilai besar, sampel audit).

### Langkah 2 — Verifikasi kelayakan & kepatuhan
Periksa kesesuaian medis (rujuk #35) & polis; nilai kewajaran biaya; tandai temuan.

### Langkah 3 — Deteksi anomali/fraud
Cari pola janggal (ganda, frekuensi, provider); tindak lanjuti temuan dengan bukti & eskalasi yang tepat.

### Langkah 4 — Susun laporan klaim berkala
Rekap klaim per periode/kategori; sajikan dengan metode #22 (laporan & dashboard).

### Langkah 5 — Analisis & rekomendasi
Analisis utilisasi/loss ratio/biaya; rumuskan rekomendasi pengendalian biaya & perbaikan kebijakan (umpan ke #9/#35).

---

## Output yang Diharapkan
- Hasil verifikasi klaim & daftar temuan/anomali
- Laporan klaim berkala (tren, utilisasi, outstanding)
- Analisis loss ratio & biaya per kategori
- Rekomendasi pengendalian biaya & perbaikan polis

---

## Indikator Keberhasilan
- Klaim janggal/fraud terdeteksi & ditindaklanjuti; kebocoran biaya menurun
- Laporan klaim akurat & tepat waktu untuk pengambilan keputusan
- Loss ratio terpantau & terkendali; rekomendasi terbukti menurunkan biaya
- Verifikasi konsisten & adil sesuai polis

---

## Tools/Metode/Dokumen Acuan
HRIS/sistem klaim, policy benefit & polis, data klaim historis, metode analitik (utilization, loss ratio), checklist verifikasi, acuan farmasi/medis (#35), metode pelaporan (#22), HIT-AD.JS.02 Rev.5, dan **HR Strategic Guidance ("HR as a Driver of Organizational Performance")**.

---

## Pertimbangan Kepatuhan & Guardrail
- **Kerahasiaan data medis:** verifikasi & laporan mengandung data kesehatan sensitif — akses sangat dibatasi, laporan diagregasi bila memungkinkan.
- **Adil & berbasis bukti:** temuan fraud harus berbukti; jangan menuduh tanpa dasar; ikuti prosedur due process bila menyentuh aspek disipliner (koordinasi #48/#10).
- **Pemisahan peran:** verifikator sebaiknya bukan pemroses klaim yang sama (#17) untuk menjaga objektivitas.
- Skill ini **memverifikasi & melaporkan**; pemrosesan transaksi klaim di #17; pengetahuan obat/kebijakan di #35; master benefit di #33.

---

## Tips Praktis
- Mulai analisis dari outlier biaya & frekuensi; di situ kebocoran terbesar biasanya berada.
- Bedakan utilisasi tinggi yang sah (populasi menua, penyakit kronis) dari anomali; salah baca memicu pembatasan yang merugikan karyawan.
- Tutup loop ke kebijakan: laporan yang tidak mengubah polis/edukasi hanya menjadi arsip.

---

## Integrasi & Reuse
Skill ini adalah **mata pengawas & analitik** atas klaim: ia memverifikasi transaksi dari #17, memakai acuan medis #35 dan data populasi #4, lalu menyajikan laporan via metode #22. Temuannya mengalir ke #9 (analisis benefit) dan #35 (revisi kebijakan kesehatan). Tegas dipisah dari #17 (pemrosesan) demi objektivitas dan dari #18/#33 agar area benefit tidak tumpang tindih.
