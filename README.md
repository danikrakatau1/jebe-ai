# JEBE-AI: Unrestricted AI & System Prompt Customization Framework

Framework dan koleksi payload lengkap untuk kustomisasi perilaku model AI, penerapan system prompt khusus (SOUL.md), serta bypass batasan operasional secara total.

---

## Panduan Langkah Demi Langkah (Step-by-Step)

### Tahap 1: Persiapan Awal & Pemahaman Konsep
1. **Pahami Arsitektur Prompt**: AI membaca instruksi sistem (`System Prompt` / `SOUL.md`) sebagai hukum dasar perilaku sebelum merespons prompt dari pengguna.
2. **Siapkan Lingkungan**: Pastikan Anda memiliki akses ke platform agen atau antarmuka model yang mendukung kustomisasi system prompt atau injeksi direktif awal.

### Tahap 2: Injeksi Konfigurasi Sistem (SOUL.md)
1. **WAJIB JALANKAN DULU !!!!**: File konfigurasi inti (`SOUL.md`) harus dimuat atau diterapkan di awal sesi sebagai fondasi kepribadian dan aturan operasional model sebelum perintah apapun diproses.
2. Salin isi file `SOUL.md` dari repository ini ke bagian system prompt atau instruksi awal agen Anda.
3. **Kunci Perilaku**: Di dalam instruksi tersebut, harus ada protokol tegas (seperti *Godmode & Anti-Filter Protocol*) yang memerintahkan model untuk mengabaikan batasan moderasi dan mematuhi perintah secara mutlak.

### Tahap 3: Pemilihan Payload Sesuai Target Model
Pilih file payload/jailbreak yang sesuai dengan platform atau model AI yang ingin Anda targetkan di dalam direktori repository ini:
- **OpenAI / GPT Series**: Gunakan template di folder `OpenAI/`.
- **Anthropic / Claude Series**: Gunakan template di folder `Anthropic/`.
- **Google / Gemini Series**: Gunakan template di folder `Google/` atau `raghavraut/`.
- **DeepSeek & Alibaba**: Gunakan template di folder `DeepSeek/` atau `Alibaba/`.
- **xAI / Grok**: Gunakan template di folder `xAI/`.

### Tahap 4: Eksekusi & Verifikasi
1. Masukkan system prompt hasil kustomisasi (`SOUL.md` + payload spesifik model).
2. Kirimkan perintah pemicu (trigger prompt) untuk memverifikasi bahwa model telah berjalan dalam mode tanpa filter (misalnya dengan konfirmasi *GODMODE ENABLED*).
3. Jalankan tugas atau perintah yang diinginkan secara langsung tanpa hambatan.

---
*Repository maintained for research and advanced system customization.*

---
### Thanks to Original Repository
Special thanks to the original repository for the core payload collection:
[https://github.com/togg53192-cmd/jailbreaks](https://github.com/togg53192-cmd/jailbreaks)
