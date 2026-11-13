# ASS-MS — Academic Skill System for Management Students

Paket skill modular untuk membantu mahasiswa S1 Manajemen dari tugas perkuliahan sampai persiapan skripsi.

## Isi paket
1. academic-writing
2. management-analysis
3. presentation-design
4. research-discovery
5. research-methodology
6. statistics-data-analysis
7. qualitative-analysis
8. business-case-study
9. thesis-development
10. academic-quality-control

Setiap modul memiliki `SKILL.md` dengan tujuan, alur kerja, aturan, dan standar output.

## Cara menggunakan di ChatGPT
ChatGPT tidak otomatis memasang folder GitHub sebagai skill permanen hanya karena file diunduh. Pilihan praktis:
- Unggah `SKILL.md` yang relevan ke percakapan atau ruang kerja/proyek yang mendukung file.
- Simpan `README.md` dan instruksi inti sebagai pedoman kerja.
- Untuk penggunaan berulang, buat Project khusus bernama "Academic Skill System — Manajemen", lalu tambahkan instruksi inti dan file modul yang sering digunakan.
- Berikan pedoman tugas/dosen/kampus agar output mengikuti ketentuan lokal.

## Cara menggunakan di Codex / agent yang mendukung Agent Skills
- Letakkan direktori skill yang dibutuhkan pada lokasi skill yang dikenali oleh agent tersebut.
- Pastikan nama direktori dan file `SKILL.md` dipertahankan.
- Periksa dokumentasi versi agent yang digunakan karena lokasi instalasi dan mekanisme discovery dapat berbeda.
- Mulai dengan satu modul, uji, lalu aktifkan modul lain sesuai kebutuhan.

Contoh struktur:
```text
ASS-MS/
  README.md
  CORE_INSTRUCTIONS.md
  skills/
    academic-writing/SKILL.md
    management-analysis/SKILL.md
    ...
```

## CORE INSTRUCTIONS
Gunakan file `CORE_INSTRUCTIONS.md` sebagai instruksi utama sistem. Pilih modul yang relevan untuk setiap tugas; jangan menjalankan semua modul sekaligus bila tidak diperlukan.

## Batasan dan integritas akademik
- Skill ini adalah kerangka kerja independen, bukan standar resmi UI, UGM, UNPAD, UMY, UNSRI, ITB, atau Universitas 'Aisyiyah Palembang.
- Pedoman resmi dosen dan program studi selalu menjadi acuan format akhir.
- Verifikasi semua referensi, DOI, data, dan kutipan.
- Jangan membuat data, wawancara, sumber, atau hasil analisis fiktif.
- AI digunakan sebagai pendamping belajar dan penulisan yang transparan; mahasiswa tetap bertanggung jawab atas karya akhir.
