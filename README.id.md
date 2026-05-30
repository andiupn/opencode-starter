# OpenCode Starter 🚀

<div align="center">
  <a href="README.md">English</a> | <strong>Bahasa Indonesia</strong>
</div>

<br />



**Template starter modular dan berkinerja tinggi untuk ekosistem AI Agent OpenCode.ai.**

> 📦 Free template by **andiupn** ([kuncimu.com](https://kuncimu.com)) · Licensed under [MIT License](LICENSE)
> ☕ If useful, [buy me a coffee](https://ko-fi.com/andiupn) · 🚀 Need more features? Try [PRO version](https://kuncimu.com)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
[![Patreon](https://img.shields.io/badge/Patreon-Support-f96854?logo=patreon)](https://patreon.com/AndiUpn)

---

Selamat datang di **OpenCode Starter**, konfigurasi workspace eksperimental modular yang dioptimalkan untuk berkolaborasi dengan AI Agent menggunakan platform OpenCode.ai. Dengan pengaturan izin yang aman dan pembagian peran agen yang sangat presisi, Anda dapat membangun proyek apa pun dengan lebih cepat, aman, dan terkendali.

---

## 🌟 Fitur Utama

- **Modular AI Roles:** 5 agen spesialis bawaan yang terkonfigurasi secara otonom di `.opencode/agents/` (Code, Research, Debug, Refactor, Document).
- **Granular Permissions:** Model kontrol akses aman di `opencode.json` yang membatasi eksekusi bash dan akses baca file sensitif (seperti memblokir akses ke berkas `.env`).
- **Standard Commands:** Perintah bawaan cepat seperti `/analyze`, `/fix`, dan `/explain` untuk otomatisasi diagnosa proyek.
- **Experimental Scaffold:** Siap digunakan untuk proyek multi-bahasa atau framework apa pun.

---

## 📂 Struktur Repositori

```
your-workspace/
  .opencode/           # Aturan spesifik agen, skills otomasi, dan prompt
    agents/            # Instruksi tertulis untuk 5 agen AI
    skills/            # Kumpulan instruksi konvensi pemrograman & testing
  .env.example         # Templat variabel lingkungan proyek
  .gitignore           # Berkas abaikan Git standar
  AGENTS.md            # Aturan kerja master untuk AI Agent
  opencode.json        # Konfigurasi perizinan, model, dan perintah OpenCode
  LICENSE              # Lisensi proyek (MIT License)
```

---

## 🚀 Memulai Cepat (Quick Start)

### 1. Salin dan Setup Lingkungan
Salin file konfigurasi lingkungan:
```bash
cp .env.example .env
```
Buka berkas `.env` dan masukkan `GITHUB_TOKEN` Anda untuk mengaktifkan integrasi repositori.

### 2. Mulai Kolaborasi Agen
Jalankan OpenCode AI Agent CLI atau muat berkas konfigurasi `opencode.json` pada editor ramah AI Anda. Gunakan perintah bawaan berikut:
- **Analisis Proyek:** `/analyze`
- **Diagnosa & Perbaikan Vuln:** `/fix`
- **Penjelasan Modul:** `/explain [nama_berkas]`

---

## 📊 LITE vs PRO Comparison

| Fitur | 🆓 LITE (Starter) | 💎 PRO (Premium) |
|---|:---:|:---:|
| **Specialized Agents** | 5 (Code, Research, dsb.) | 5 (Modular System) |
| **Workflow Skills** | 2 (`coding-conventions`, `testing`) | 15+ (Database, Ops, dsb.) |
| **Struktur Workspace** | Simple | Status-first Monorepo (`active/`, dsb.) |
| **Project Presets** | ❌ | 10 Presets (Next, Laravel, Flutter, dll.) |
| **Ops & Server Sync** | ❌ | ✅ (Docker Compose & Caddyfile ready) |

👉 **[Lihat Perbandingan Fitur Lengkap & Cara Upgrade](COMPARISON.md)**

---

## 💖 Dukung Proyek Ini (Donasi)

Jika template starter ini membantu mempercepat alur kerja pengodean Anda, pertimbangkan untuk memberikan dukungan melalui tautan berikut:
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer (Indonesia):** [trakteer.id/andi_upn](https://trakteer.id/andi_upn)
- **Saweria (Indonesia):** [saweria.co/andiupn](https://saweria.co/andiupn)

Dukungan Anda sangat berarti bagi pengembangan templat AI yang lebih baik di masa depan! ❤️

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah **MIT License**. Lihat berkas [LICENSE](LICENSE) untuk informasi lebih lanjut.