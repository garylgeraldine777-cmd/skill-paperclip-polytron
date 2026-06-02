---
name: cross-agent-orchestration
description: >
  Gunakan skill ini saat pengguna yang memegang peran Head of Human Resources; HR Advisor membutuhkan
  panduan untuk menangani skenario HR lintas-fungsi kompleks yang membutuhkan banyak bidang sekaligus.
  Trigger juga saat percakapan menyebut topik: orkestrasi lintas-Agent, skenario lintas-fungsi,
  kasus HR kompleks (mis. PHK kompleks, restrukturisasi, akuisisi talenta strategis), sintesis lintas-bidang,
  rujukan ke Agent fungsi (Development/Operations/L&D/Culture/Payroll), atau keputusan HR terpadu end-to-end.
---

# Cross-Agent Orchestration (Leadership Agent v2)

**Deskripsi:** Kemampuan **mengorkestrasi seluruh Agent fungsi HR sebagai sub-expert** untuk menjawab skenario lintas-fungsi yang kompleks. Skill ini adalah **capstone ekosistem**: ia memecah masalah HR terpadu menjadi bagian-bagian per fungsi, memanggil pengetahuan skill yang relevan dari Fase 2–6, lalu menyintesis menjadi satu rekomendasi yang koheren tingkat eksekutif. Skill ini meng-upgrade Agent HR Leadership & Advisory v1 (berbasis 3 anchor skill Fase 1) menjadi **v2** dengan kemampuan integrasi lintas-bidang. Ia **tidak menggantikan** skill fungsi — ia mengoordinasikannya.

**Relevan untuk:** Head of Human Resources; HR Advisor

**Metadata:** Fase 6 (Spesialisasi Finansial-Administratif + Capstone) · Kategori: HR Leadership & Advisory (Capstone) · Skill orkestrasi (di luar 48 skill kamus) · Tahap Capstone · Prasyarat: seluruh Agent fungsi Fase 1–6 LIVE · Dependensi reuse: #1 Strategic HR, #2 Labor Law, #48 Conflict Resolution (anchor Fase 1) + seluruh skill fungsi Fase 2 (Development), Fase 3 (Operations), Fase 4 (L&D), Fase 5 (Culture), Fase 6 (Payroll) · Pembeda: ini **lapisan orkestrasi/sintesis**, bukan eksekusi domain; setiap domain tetap dikerjakan skill fungsinya.

---

## Arah Strategis (selaras HR Strategic Guidance)

Skill ini adalah perwujudan akhir **HR as a Driver of Organizational Performance**: HR Leadership dapat menjawab pertanyaan bisnis lintas-bidang secara terpadu, bukan terfragmentasi per silo. Ia menutup pergeseran **Administrative→Strategic** dan **Process-Focused→Business-Focused** pada level tertinggi.

- **Ultimate Target — Employer of Choice 2030.** Keputusan HR yang koheren lintas-fungsi (talenta, operasi, pembelajaran, budaya, reward) menjadikan HR mitra strategis bisnis.
- **Mengikat seluruh Key Result.** Skenario seperti transisi HRIS (Okt 2028), zero pension extension 2030, dan Best Workplace Culture 2030 hampir selalu lintas-fungsi — skill ini yang menyatukannya.
- **Data-Driven HR.** Sintesis berbasis output ber-metrik dari tiap Agent fungsi, bukan opini.
- **Six pillars terhubung.** Orkestrasi membuat enam pilar framework bekerja sebagai satu sistem.

---

## Konteks Penggunaan

Aktifkan skill saat menghadapi skenario yang menyentuh banyak fungsi sekaligus, misalnya: PHK kompleks (IR #10 + Payroll/pesangon #8 + Labor Law #2 + Conflict #48), restrukturisasi (Org Design #3 + Change Mgmt #31 + Manpower #29 + Payroll #9), akuisisi talenta strategis (Recruitment #5 + C&B #9 + Succession #6), atau transisi HRIS Okt 2028 (HRIS #4 + Change #31 + Payroll #8 + Data #22).

---

## Kerangka Pengetahuan Inti

- **Dekomposisi masalah:** memecah skenario menjadi sub-pertanyaan per fungsi/skill.
- **Peta kapabilitas Agent:** mengetahui skill/fungsi mana menjawab apa (routing ke sub-expert yang tepat).
- **Urutan & dependensi:** menentukan urutan pemanggilan (mis. cek Labor Law sebelum hitung pesangon).
- **Sintesis & resolusi konflik:** menggabungkan output yang mungkin bertentangan menjadi rekomendasi tunggal yang konsisten & sadar trade-off.
- **Eskalasi & batas wewenang:** mengenali kapan keputusan butuh manajemen/COO/legal eksternal.

---

## Langkah-Langkah Utama

### Langkah 1 — Bingkai skenario & pemangku kepentingan
Rumuskan pertanyaan bisnis inti, populasi terdampak, risiko, dan pemangku kepentingan (frame strategis #1).

### Langkah 2 — Dekomposisi ke domain fungsi
Pecah menjadi sub-pertanyaan; petakan ke skill/fungsi yang tepat (Development/Operations/L&D/Culture/Payroll).

### Langkah 3 — Panggil sub-expert sesuai urutan dependensi
Ambil pengetahuan dari skill terkait dengan urutan benar (mis. #2 Labor Law & #48 sebelum eksekusi #10/#8).

### Langkah 4 — Sintesis lintas-bidang
Gabungkan output; selesaikan kontradiksi; tonjolkan trade-off, risiko, & opsi berbasis data.

### Langkah 5 — Rekomendasi terpadu & rencana eksekusi
Sajikan satu rekomendasi koheren tingkat eksekutif dengan langkah, penanggung jawab fungsi, dan titik eskalasi.

---

## Output yang Diharapkan
- Analisis skenario lintas-fungsi yang terstruktur per domain
- Rekomendasi terpadu tingkat eksekutif dengan trade-off & risiko
- Rencana eksekusi yang menugaskan tiap bagian ke fungsi/skill pemiliknya
- Daftar titik kepatuhan & eskalasi (Labor Law, COO, legal)

---

## Indikator Keberhasilan
- Skenario kompleks terjawab utuh tanpa celah antar-silo
- Rekomendasi konsisten dengan kebijakan, kepatuhan, & data tiap fungsi
- Trade-off lintas-bidang dibuat eksplisit, bukan disembunyikan
- Eksekusi dapat langsung didelegasikan ke Agent/fungsi yang tepat

---

## Tools/Metode/Dokumen Acuan
Peta kapabilitas Agent HR (Fase 1–6), kerangka dekomposisi masalah, matriks dependensi antar-skill, HIT-OS.AD.02 Rev.5 (struktur organisasi), HIT-AD.JS.02 Rev.5, dan **HR Strategic Guidance ("HR as a Driver of Organizational Performance")**.

---

## Pertimbangan Kepatuhan & Guardrail
- **Prasyarat capstone:** hanya andal setelah seluruh Agent fungsi Fase 1–6 LIVE & teruji; orkestrasi atas fungsi yang belum matang menghasilkan sintesis menyesatkan.
- **Tidak menggantikan domain:** untuk fakta/aturan spesifik, selalu rujuk skill pemiliknya; jangan mengarang detail fungsi.
- **Batas struktur pelaporan:** Payroll melapor ke COO — keputusan lintas-fungsi yang menyentuh Payroll dikoordinasikan, bukan didikte sepihak.
- **Kepatuhan menang:** bila domain bertentangan, Labor Law (#2) & kebijakan resmi (#1) menjadi pembatas; eskalasikan keputusan berisiko tinggi.

---

## Tips Praktis
- Selalu cek kepatuhan (#2) & frame kebijakan (#1) lebih dulu sebelum mengeksekusi domain teknis.
- Buat trade-off eksplisit: keputusan lintas-fungsi yang baik biasanya mengorbankan sesuatu — sebut apa.
- Delegasikan eksekusi ke pemilik fungsi; peran skill ini menyatukan & memutuskan, bukan mengerjakan semua sendiri.

---

## Integrasi & Reuse
Skill ini adalah **konduktor orkestra** ekosistem Agent HR: ia tidak memiliki domain sendiri melainkan memanggil & menyintesis seluruh skill Fase 1–6. Anchor Fase 1 (#1, #2, #48) menjadi pembatas kebijakan & kepatuhan; fungsi Fase 2–6 menjadi sub-expert. Dengan skill ini, Agent HR Leadership naik dari v1 (advisory strategis) ke **v2 (orkestrasi lintas-fungsi)** — menutup roadmap menjadi satu ekosistem terpadu.
