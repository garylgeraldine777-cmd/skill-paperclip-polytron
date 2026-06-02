---
name: training-system-development-deployment
description: >
  Gunakan skill ini saat pengguna yang memegang peran Learning Development Specialist
  membutuhkan panduan tentang pengembangan & penerapan sistem pembelajaran.
  Trigger juga saat percakapan menyebut topik: pengembangan sistem pembelajaran, implementasi LMS, deployment LMS/TMS,
  konfigurasi platform belajar, integrasi LMS dengan HRIS, rollout sistem learning, migrasi platform pembelajaran,
  atau proyek membangun & meluncurkan sistem pelatihan baru.
---

# Training System Development & Deployment

**Deskripsi:** Kemampuan **mengembangkan dan menggelar (deploy) sistem pembelajaran** di organisasi. Skill ini bersifat **proyek**: memilih/mengonfigurasi platform (LMS/TMS), mengintegrasikannya dengan HRIS (#4), memigrasikan konten/data, lalu meluncurkan ke pengguna. Berbeda dari #37 yang **mengoperasikan** sistem dalam kondisi steady-state — #38 fokus pada **membangun & menerapkan**.

**Relevan untuk:** Learning Development Specialist

**Metadata:** Fase 4 (L&D) · Kategori: Learning & Development · Skill #38 · Tahap B (Konten & Sistem) · Dependensi: reuse #4 HRIS & Data Management (integrasi & arsitektur data) · Pembeda: #38 = **bangun & deploy sistem (proyek)**; #37 = administrasi/operasi sistem (steady-state); #14 = sistem manajemen pengetahuan.

---

## Arah Strategis (selaras HR Strategic Guidance)

Skill ini membangun **infrastruktur digital** pilar **Learning & Development** dan menerapkan **Administrative→Strategic** melalui platform yang terintegrasi & data-ready.

- **Key Result — matikan HRIS Hefaistos & HRD Web (Okt 2028).** Sistem belajar baru harus terintegrasi ke ekosistem HRIS baru; data pembelajaran legacy dimigrasikan, bukan ditinggalkan.
- **Data-Driven HR.** Integrasi LMS↔HRIS membuat data kompetensi, kehadiran, dan hasil belajar mengalir untuk analitik & ROI.
- **Self-service learning.** Platform memungkinkan karyawan mengakses pembelajaran mandiri sebagai kanal utama.
- **Skalabilitas.** Deployment dirancang untuk seluruh lokasi (plant/cabang) dengan konsistensi konfigurasi.

---

## Konteks Penggunaan

Aktifkan skill saat: memilih/mengonfigurasi LMS/TMS, merancang integrasi dengan HRIS, memigrasikan data/konten pembelajaran, atau merencanakan & menjalankan rollout sistem belajar.

---

## Kerangka Pengetahuan Inti

- **Arsitektur sistem belajar:** LMS/TMS, modul, integrasi (SSO, HRIS, SCORM/xAPI).
- **Integrasi data:** sinkronisasi master data karyawan & kompetensi dengan #4.
- **Migrasi:** pemindahan konten & rekaman belajar dari sistem lama (relevan decommission 2028).
- **Deployment & change:** UAT, pilot, rollout bertahap, pelatihan pengguna.
- **Keamanan & akses:** peran/hak akses sesuai least privilege.

---

## Langkah-Langkah Utama

### Langkah 1 — Tetapkan kebutuhan sistem
Definisikan kebutuhan fungsional dari portofolio program (#12) & integrasi HRIS (#4).

### Langkah 2 — Konfigurasi & integrasi
Atur platform, SSO, dan integrasi data; pastikan kompatibilitas SCORM/xAPI dengan konten #39.

### Langkah 3 — Migrasikan data & konten
Pindahkan rekaman belajar & materi dari sistem lama; validasi integritas (siap decommission 2028).

### Langkah 4 — Uji & pilot
Jalankan UAT dan pilot terbatas; perbaiki sebelum rollout penuh.

### Langkah 5 — Deploy & serahterimakan
Luncurkan bertahap, latih pengguna, dan serahterimakan operasi rutin ke administrasi sistem (#37).

---

## Output yang Diharapkan
- Sistem pembelajaran terkonfigurasi & terintegrasi HRIS
- Rencana & hasil migrasi data/konten
- Dokumen UAT/pilot & rollout
- Serah terima operasi ke administrator sistem (#37)

---

## Indikator Keberhasilan
- Sistem terintegrasi & data mengalir ke HRIS/analitik
- Migrasi tuntas tanpa kehilangan rekaman belajar
- Rollout mulus dengan adopsi pengguna tinggi
- Kesiapan menggantikan sistem lama (decommission 2028)

---

## Tools/Metode/Dokumen Acuan
LMS/TMS, HRIS (#4), SSO, SCORM/xAPI, project & change management, UAT, HIT-AD.JS.02 Rev.5, dan **HR Strategic Guidance**.

---

## Pertimbangan Kepatuhan & Guardrail
- **Integritas migrasi:** validasi rekaman belajar & sertifikasi yang punya konsekuensi kepatuhan sebelum sistem lama dimatikan.
- **Keamanan data & akses:** terapkan least privilege dan jejak audit (selaras #4).
- Skill ini **membangun & menerapkan**; operasi harian sistem ada di #37.

---

## Tips Praktis
- Sepakati integrasi HRIS sejak desain — retrofit integrasi belakangan jauh lebih mahal.
- Rollout bertahap (pilot dulu) menurunkan risiko & mempercepat adopsi.
- Jadikan migrasi rekaman belajar bagian dari rencana decommission 2028, bukan pekerjaan dadakan.

---

## Integrasi & Reuse
Skill ini me-reuse arsitektur #4 (HRIS) dan meng-host konten dari #39. Setelah live, operasi diserahkan ke #37 (administrasi sistem). Bersama #14, ia membentuk lapisan sistem pilar L&D; data yang dihasilkan menopang #43 & #47.
