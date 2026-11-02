# AI Video Creator Skill

Template skill untuk membuat video pendek storytelling animasi kartun 3D low-poly sinematik dari sebuah judul.

## Cara pakai
1. Simpan folder ini atau unggah ZIP ke GitHub sebagai repository.
2. Buka `SKILL.md` dan gunakan sebagai instruksi utama saat memulai percakapan dengan AI yang mendukung file skill.
3. Setelah skill diberikan, cukup kirim judul/topik video.
4. AI akan menyusun konsep, character bible, storyboard, prompt tiap adegan, dialog/narasi, subtitle, audio, negative prompt, dan checklist editing.

## Standar default
- Vertikal 9:16
- 60 detik (6 adegan x 10 detik)
- Animasi kartun 3D low-poly sinematik
- Bahasa Indonesia
- Subtitle besar dengan kata kunci berwarna
- Cerita dengan hook, konflik, klimaks, penutup, dan CTA

## Integrasi GitHub
Paket ini sudah disusun sebagai repository-ready. Untuk menghubungkannya ke akun GitHub:
1. Buat repository baru di https://github.com/new
2. Beri nama, misalnya `ai-video-creator-skill`.
3. Pilih Public atau Private sesuai kebutuhan.
4. Unggah seluruh isi folder ini, atau gunakan Git:
   ```bash
   git init
   git add .
   git commit -m "Initial AI Video Creator Skill"
   git branch -M main
   git remote add origin https://github.com/USERNAME/ai-video-creator-skill.git
   git push -u origin main
   ```
5. Ganti `USERNAME` dengan username GitHub milikmu.

## Pemeriksaan paket
Versi 1.0.1 telah diperiksa: arsip ZIP dapat dibuka, semua file Markdown terbaca sebagai UTF-8, file utama `SKILL.md` dan `README.md` tersedia, dan tautan file internal yang disebutkan di README sesuai dengan struktur paket.

## Catatan penting
GitHub menyimpan dan mengelola versi skill; GitHub tidak otomatis merender video dan tidak otomatis menghubungkan akun ChatGPT. Untuk menggunakan versi terbaru, unggah atau berikan isi `SKILL.md` terbaru ke percakapan. Jika tersedia integrasi GitHub/connector di aplikasi yang kamu gunakan, hubungkan melalui pengaturan aplikasi tersebut.

## File
- `SKILL.md`: instruksi inti AI.
- `templates/MASTER_TEMPLATE.md`: format produksi per video.
- `templates/VIDEO_BRIEF.md`: format input judul (opsional).
- `templates/QUALITY_CHECKLIST.md`: pemeriksaan hasil.
- `examples/REFERENCE_STYLE.md`: karakteristik video referensi yang dianalisis.
