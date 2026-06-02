---
name: attendance-overtime-data-management
description: >
  Gunakan skill ini saat pengguna yang memegang peran Employee Administrator; Payroll Officer membutuhkan
  panduan tentang pengelolaan & verifikasi data kehadiran dan lembur untuk penggajian.
  Trigger juga saat percakapan menyebut topik: data kehadiran/absensi aktual, rekap lembur, perhitungan
  jam lembur, validasi presensi, koreksi absensi, cut-off kehadiran, mesin absensi/timesheet,
  potongan ketidakhadiran, atau penyiapan data attendance sebagai dasar payroll.
---

# Attendance & Overtime Data Management

**Deskripsi:** Kemampuan **mengelola dan memverifikasi data kehadiran serta lembur untuk kebutuhan penggajian**. Skill ini adalah **gerbang masukan payroll**: mengubah catatan presensi mentah dan pengajuan lembur menjadi data kehadiran/lembur yang bersih, tervalidasi, dan siap dihitung oleh payroll. Fokusnya pada **data aktual (actuals) untuk pembayaran** — berbeda dari penyusunan jadwal/roster (itu #28 Schedule Management, Fase 3).

**Relevan untuk:** Employee Administrator; Payroll Officer

**Metadata:** Fase 6 (Spesialisasi Finansial-Administratif + Capstone / Payroll Management) · Kategori: Payroll, Benefit & Employee Services · Skill #36 · Tahap B (attendance & data) · Dependensi reuse: #28 Schedule Management (jadwal/roster sebagai baseline pembanding kehadiran), #4 HRIS (data karyawan & aturan kerja), #8 Payroll & Tax (konsumen data ini) · Pembeda: #36 = **data kehadiran/lembur AKTUAL untuk pembayaran**; #28 = perencanaan jadwal/roster (Fase 3); #8 = perhitungan gaji memakai data ini; #22 = pelaporan agregat.

---

## Arah Strategis (selaras HR Strategic Guidance)

Skill ini mengaktifkan pilar **Data-Driven HR** dan **HR Operations**, serta menerapkan pergeseran **Reactive→Proactive** dan **Cost Center→Value-Driven**: data kehadiran dijaga akurat di hulu sehingga payroll benar di hilir, dan biaya lembur menjadi terlihat & terkendali.

- **Key Result — decommission HRIS lama Okt 2028.** Data kehadiran/lembur harus mengalir dari sistem absensi terintegrasi ke HRIS baru (#4) menuju payroll (#8); integrasi ini menguji rantai data end-to-end.
- **Reactive→Proactive.** Validasi & cut-off disiplin mencegah koreksi gaji susulan, bukan menambal setelah salah bayar.
- **Cost Center→Value-Driven.** Analitik lembur (jam, biaya, unit penyumbang) memberi visibilitas cost untuk keputusan manpower.
- **Data-Driven HR.** Kualitas data di titik input diukur (anomali presensi, lembur tanpa otorisasi, koreksi pasca cut-off).

---

## Konteks Penggunaan

Aktifkan skill saat: menutup periode kehadiran sebelum payroll, memvalidasi presensi & pengajuan lembur, menghitung jam lembur sesuai aturan, mengoreksi anomali absensi, atau menyiapkan data kehadiran/lembur untuk perhitungan gaji.

---

## Kerangka Pengetahuan Inti

- **Sumber presensi:** mesin absensi, timesheet, aplikasi presensi; cocokkan terhadap roster/jadwal (#28).
- **Aturan lembur:** definisi jam normal, perhitungan lembur (hari kerja/libur), batas & otorisasi lembur (rujuk #2).
- **Anomali presensi:** tanpa rekam, ganda, terlambat/pulang awal, dinas luar, cuti vs alpa.
- **Cut-off & koreksi:** batas periode, jendela koreksi, audit trail perubahan data.
- **Mapping ke komponen payroll:** kehadiran→potongan ketidakhadiran; lembur→komponen upah lembur (#8).

---

## Langkah-Langkah Utama

### Langkah 1 — Kumpulkan presensi & bandingkan ke jadwal
Tarik data presensi mentah; cocokkan terhadap roster/jadwal dari #28 untuk mendeteksi penyimpangan.

### Langkah 2 — Validasi & bersihkan anomali
Identifikasi anomali (tanpa rekam, ganda, alpa vs cuti); selesaikan dengan bukti/otorisasi sebelum cut-off.

### Langkah 3 — Hitung & verifikasi lembur
Hitung jam lembur sesuai aturan & otorisasi; tolak lembur tanpa persetujuan; rujuk batas hukum (#2).

### Langkah 4 — Kunci cut-off & serahkan ke payroll
Kunci periode pada cut-off; kemas data kehadiran/lembur tervalidasi sebagai input ke #8.

### Langkah 5 — Dokumentasi & analitik
Simpan audit trail koreksi; sajikan analitik lembur (jam/biaya per unit) ke pelaporan (#22).

---

## Output yang Diharapkan
- Rekap kehadiran & lembur tervalidasi (siap input payroll #8)
- Daftar anomali presensi & status penyelesaiannya
- Perhitungan jam lembur teratur sesuai otorisasi
- Audit trail koreksi & analitik lembur untuk #22

---

## Indikator Keberhasilan
- Data kehadiran/lembur akurat sebelum cut-off; koreksi pasca-payroll minim
- Lembur 100% terotorisasi; tidak ada pembayaran lembur tanpa dasar
- Cut-off ditepati; rantai data presensi→HRIS→payroll mulus
- Biaya lembur terpantau & dapat ditelusuri per unit

---

## Tools/Metode/Dokumen Acuan
Mesin absensi/timesheet, HRIS/payroll system, aturan lembur (UU Ketenagakerjaan), roster/jadwal kerja, checklist validasi presensi, data validation, audit trail, HIT-AD.JS.02 Rev.5, dan **HR Strategic Guidance ("HR as a Driver of Organizational Performance")**.

---

## Pertimbangan Kepatuhan & Guardrail
- **Batas & otorisasi lembur:** patuhi batas jam lembur & ketentuan upah lembur — rujuk #2 Labor Law; jangan membayar lembur tanpa otorisasi.
- **Integritas data:** koreksi presensi wajib berbukti & ter-audit; hindari perubahan tanpa jejak.
- **Privasi:** data kehadiran terkait individu — akses sesuai kebutuhan.
- Skill ini **menyiapkan data aktual**; penyusunan jadwal/roster ada di #28 (Fase 3); perhitungan gaji di #8; pelaporan agregat di #22.

---

## Tips Praktis
- Selesaikan anomali sebelum cut-off, bukan sesudah; satu absensi yang salah memicu koreksi gaji berbiaya.
- Bandingkan lembur aktual vs jadwal/roster — lonjakan lembur sering menandakan masalah perencanaan di #28, bukan sekadar beban kerja.
- Simpan otorisasi lembur bersama datanya; saat audit, otorisasi yang hilang lebih bermasalah daripada angka jamnya.

---

## Integrasi & Reuse
Skill ini adalah **input gate** menuju payroll: ia memakai roster dari #28 sebagai pembanding, membersihkan data, lalu menyuapkan kehadiran/lembur tervalidasi ke #8 dan analitik ke #22. Tidak menyusun jadwal (itu #28) dan tidak menghitung gaji (itu #8) — perannya memastikan **data masuk benar** sehingga seluruh rantai payroll akurat.
