# SIA Project Skills

Kumpulan skill AI untuk membantu mahasiswa menyusun, mengaudit, dan meningkatkan kualitas dokumen proyek Sistem Informasi Akuntansi (SIA).

Skill dalam repositori ini dirancang agar dapat dibaca sebagai instruksi Markdown oleh berbagai model AI. Tujuannya adalah menghasilkan umpan balik yang spesifik dan berbasis bukti, sekaligus membantu mahasiswa mengetahui pekerjaan yang perlu dilakukan sebelum melanjutkan ke tahap proyek berikutnya.

## Skill yang tersedia

| Skill | Kegunaan |
| --- | --- |
| [Audit Dokumen Studi Kasus SIA](./audit-dokumen-studi-kasus-sia/SKILL.md) | Menilai progres, kualitas, konsistensi, risiko, dan kesiapan tahap dokumen proyek SIA. |
| [Simulasi Wawancara Studi Kasus SIA](./simulasi-wawancara-studi-kasus-sia/SKILL.md) | Memfasilitasi latihan wawancara elisitasi untuk mahasiswa yang menyusun studi kasus Sistem Informasi Akuntansi.|


## Cara menggunakan

1. Buka `SKILL.md` dari skill yang ingin digunakan.
2. Berikan isi skill tersebut kepada model AI sebagai instruksi, atau lampirkan berkasnya jika aplikasi mendukung lampiran.
3. Lampirkan dokumen proyek yang ingin diperiksa.
4. Jelaskan tahap proyek dan keputusan yang ingin dibantu.

Contoh permintaan:

> Gunakan instruksi dalam SKILL.md untuk mengaudit Project Charter kelompok kami. Nilai progres dan kualitasnya, tunjukkan temuan beserta lokasi dalam dokumen, lalu rekomendasikan revisi sebelum kami mengajukannya kepada dosen.

Untuk audit ulang, sertakan versi dokumen sebelumnya atau hasil audit terdahulu agar perubahan dapat dibandingkan.

## Prinsip penilaian

- **Progres dan kualitas dinilai terpisah.** Dokumen yang seluruh bagiannya terisi belum tentu memiliki isi yang kuat.
- **Temuan harus dapat ditelusuri.** Umpan balik menyebut bagian dokumen, dampak masalah, tindakan perbaikan, dan bukti bahwa perbaikan telah selesai.
- **Penilaian mengikuti tahap proyek.** Project Charter dinilai untuk kesiapan masuk analisis kebutuhan; kesiapan pengembangan memerlukan dokumen yang lebih rinci.
- **Skor tidak menghapus masalah kritis.** Keputusan penting yang belum dibuat dapat menahan proyek meskipun nilai keseluruhannya tinggi.
- **Rubrik dosen diutamakan.** Bobot dan ambang dalam skill adalah titik awal dan dapat disesuaikan dengan ketentuan mata kuliah.

Hasil AI merupakan bahan evaluasi dan pembelajaran. Persetujuan proyek tetap menjadi wewenang dosen pengampu dan mitra usaha.

## Ruang lingkup pengembangan

Repositori ini dapat diperluas dengan skill untuk tahap dan dokumen lain, misalnya:

- Audit Project Charter
- Audit kebutuhan dan aturan bisnis
- Audit alur AS-IS dan TO-BE
- Audit model data dan logika akuntansi
- Audit konsistensi lintas dokumen
- Audit kesiapan pengembangan dan pengujian

Daftar tersebut adalah arah pengembangan, bukan klaim bahwa seluruh skill sudah tersedia.

## Struktur repositori

```text
sia-project-skills/
├── README.md
└── audit-dokumen-studi-kasus-sia/
    └── SKILL.md
```

Setiap skill diupayakan tetap dapat dipakai secara mandiri. Instruksi inti, rubrik, aturan keputusan, dan format keluaran ditempatkan dalam `SKILL.md` agar mudah dibagikan kepada mahasiswa.

## Privasi dokumen

Periksa izin penggunaan sebelum mengunggah dokumen mitra ke layanan AI. Hilangkan data pribadi, kredensial, dan informasi transaksi sensitif yang tidak diperlukan untuk audit. Jika bukti tertentu tidak dapat dibagikan, jelaskan keterbatasannya agar AI tidak menganggapnya telah diverifikasi.

## Kontribusi

Masukan dari mahasiswa dan dosen dapat berupa temuan rubrik yang ambigu, contoh umpan balik yang kurang berguna, atau kasus SIA yang belum terakomodasi. Saat mengusulkan perubahan, sertakan contoh dokumen atau cuplikan yang telah dianonimkan, keluaran yang diharapkan, dan alasan perubahan.

Perubahan pada bobot, ambang keputusan, atau definisi masalah kritis perlu diuji pada beberapa studi kasus sebelum diterapkan secara luas.
