---
name: medical-benefit-claims-administration
description: >
  Gunakan skill ini saat pengguna yang memegang peran Medical Administrator membutuhkan panduan tentang
  pemrosesan & administrasi klaim medis dan benefit sesuai kebijakan.
  Trigger juga saat percakapan menyebut topik: proses klaim medis, administrasi klaim benefit,
  pengajuan klaim karyawan, alur klaim (intake-approval-payment), reimbursement, plafon/limit benefit,
  koordinasi dengan provider/asuransi, atau penyelesaian & pembayaran klaim sesuai polis.
---

# Medical & Benefit Claims Administration

**Deskripsi:** Kemampuan **memverifikasi dan memproses klaim medis atau benefit lainnya sesuai kebijakan**. Skill ini adalah **alur pemrosesan klaim end-to-end**: menerima pengajuan, mengecek kelayakan terhadap polis/plafon, memproses persetujuan, dan menyelesaikan pembayaran/reimbursement secara tepat waktu. Fokusnya pada **menjalankan transaksi klaim** — berbeda dari verifikasi mendalam & pelaporan klaim berkala (itu #34) dan dari jaminan sosial BPJS (itu #18).

**Relevan untuk:** Medical Administrator

**Metadata:** Fase 6 (Spesialisasi Finansial-Administratif + Capstone / Payroll Management) · Kategori: Payroll, Benefit & Employee Services · Skill #17 · Tahap C (medical & benefit) · Dependensi reuse: #4 HRIS (data karyawan & kepesertaan benefit), #33 Benefit Update (master data benefit/plafon sebagai acuan kelayakan), #8 Payroll (jika reimbursement disalurkan via gaji) · Pembeda: #17 = **memproses & menyelesaikan klaim (eksekusi alur)**; #34 = verifikasi mendalam & pelaporan klaim berkala; #18 = jaminan sosial BPJS; #33 = pemeliharaan master data benefit; #35 = pengetahuan farmasi & kebijakan kesehatan.

---

## Arah Strategis (selaras HR Strategic Guidance)

Skill ini mengaktifkan pilar **HR Operations** (layanan karyawan yang responsif) dan **Data-Driven HR**, serta menerapkan pergeseran **Reactive→Proactive** dan **Administrative→Strategic**: klaim diproses cepat-tepat sebagai bagian pengalaman karyawan, dengan data klaim menjadi umpan balik kebijakan benefit.

- **Ultimate Target — Employer of Choice 2030.** Penyelesaian klaim yang cepat, adil, dan transparan adalah titik sentuh pengalaman karyawan yang sangat terasa.
- **Reactive→Proactive.** SLA klaim & status yang transparan mencegah keluhan, bukan menanganinya belakangan.
- **Data-Driven HR.** Waktu siklus klaim & rasio sesuai-polis diukur; tren menjadi masukan untuk #34 dan kebijakan #35.
- **Cost Center→Value-Driven.** Klaim diproses sesuai plafon/polis sehingga biaya benefit terkendali tanpa mengorbankan layanan.

---

## Konteks Penggunaan

Aktifkan skill saat: menerima & memproses pengajuan klaim medis/benefit, mengecek kelayakan terhadap polis & plafon, mengoordinasikan dengan provider/asuransi, atau menyelesaikan pembayaran/reimbursement klaim.

---

## Kerangka Pengetahuan Inti

- **Alur klaim:** intake → kelengkapan dokumen → cek kelayakan (polis/plafon dari #33) → persetujuan → pembayaran → penutupan.
- **Kelayakan:** kepesertaan aktif (#4), jenis benefit tertanggung, plafon & sisa limit, dokumen pendukung.
- **Kanal penyelesaian:** reimbursement langsung, via payroll (#8), atau koordinasi provider/asuransi.
- **Status & SLA:** pelacakan status pengajuan, target waktu proses, komunikasi ke karyawan.
- **Eskalasi:** klaim meragukan/di luar polis diteruskan ke verifikasi mendalam (#34) atau keputusan kebijakan.

---

## Langkah-Langkah Utama

### Langkah 1 — Terima & cek kelengkapan
Terima pengajuan; periksa kelengkapan dokumen; konfirmasi kepesertaan aktif dari #4.

### Langkah 2 — Cek kelayakan terhadap polis
Cocokkan klaim ke jenis benefit, plafon, & sisa limit (master data dari #33); tandai yang di luar polis.

### Langkah 3 — Proses persetujuan
Setujui klaim yang sesuai; eskalasikan kasus meragukan/kompleks ke verifikasi mendalam (#34).

### Langkah 4 — Selesaikan pembayaran
Salurkan reimbursement (langsung, via #8, atau koordinasi provider); catat penyelesaian.

### Langkah 5 — Tutup & dokumentasikan
Tutup klaim; perbarui sisa limit; arsipkan; salurkan data transaksi ke pelaporan/verifikasi (#34, #22).

---

## Output yang Diharapkan
- Klaim diproses & diselesaikan sesuai polis
- Status klaim transparan & terlacak per pengajuan
- Dokumen pembayaran/reimbursement & catatan penutupan
- Data transaksi klaim untuk verifikasi & pelaporan (#34/#22)

---

## Indikator Keberhasilan
- Klaim diproses tepat waktu sesuai SLA; sesuai kebijakan/polis
- Selisih & kesalahan administrasi klaim minim
- Karyawan memahami status klaim; keluhan layanan rendah
- Biaya klaim terkendali dalam plafon yang ditetapkan

---

## Tools/Metode/Dokumen Acuan
HRIS/payroll system, sistem/portal klaim, policy benefit & polis asuransi, form klaim, checklist verifikasi kelengkapan, SLA layanan, HIT-AD.JS.02 Rev.5, dan **HR Strategic Guidance ("HR as a Driver of Organizational Performance")**.

---

## Pertimbangan Kepatuhan & Guardrail
- **Sesuai polis & plafon:** proses hanya klaim yang layak; pembayaran di luar polis butuh dasar/persetujuan eksplisit.
- **Kerahasiaan data medis:** informasi kesehatan sangat sensitif — batasi akses ketat, simpan terpisah, hormati kerahasiaan.
- **Pemisahan peran:** pemroses klaim sebaiknya bukan satu-satunya pihak yang menyetujui nominal besar (kaitkan #34).
- Skill ini **memproses & menyelesaikan klaim**; verifikasi mendalam & pelaporan tren di #34; aturan farmasi/kebijakan kesehatan di #35; master data benefit di #33.

---

## Tips Praktis
- Tutup gap dokumen di awal; klaim yang tertahan karena dokumen tidak lengkap adalah sumber keluhan terbesar.
- Tampilkan sisa plafon ke karyawan saat klaim; transparansi limit mengurangi pengajuan yang ditolak.
- Eskalasikan pola klaim tak wajar ke #34 lebih cepat — pemrosesan rutin bukan tempat menahan kecurigaan.

---

## Integrasi & Reuse
Skill ini adalah **tangan eksekusi klaim**: ia memakai kepesertaan dari #4 dan master plafon dari #33 untuk menilai kelayakan, menyalurkan reimbursement (sebagian via #8), lalu menyerahkan datanya untuk diverifikasi mendalam & dilaporkan oleh #34 dan diringkas #22. Tidak mengelola BPJS (#18) maupun pengetahuan farmasi (#35) — perannya murni memproses transaksi klaim.
