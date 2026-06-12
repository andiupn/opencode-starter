# OpenCode Starter 🚀

<div align="center">
  <a href="README.md">English</a> | <strong>Bahasa Indonesia</strong> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>

<br />

<div align="center">
  <h3><strong>Asisten kode paling cerdas butuh batas keamanan paling aman.</strong></h3>
  <p><strong>Starter template berkinerja tinggi dan modular yang dioptimalkan untuk ekosistem AI Agent OpenCode.ai, dilengkapi dengan kontrol izin granular yang aman serta perintah diagnosa bawaan.</strong></p>

  <p>Hentikan kekhawatiran tentang agen AI yang mengeksekusi perintah terminal destruktif atau membocorkan variabel lingkungan pribadi Anda. Rasakan pengodean otonom yang cepat dan aman.</p>
</div>

> 📦 Free template by **andiupn** ([kuncimu.com](https://kuncimu.com)) · Licensed under [MIT License](LICENSE)  
> ☕ Jika bermanfaat, [beli saya kopi](https://ko-fi.com/andiupn) · 🚀 Butuh fitur lebih lengkap? Coba [versi PRO](https://github.com/sponsors/andiupn?frequency=monthly)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/andiupn/opencode-starter)](https://github.com/andiupn/opencode-starter/releases)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
[![Patreon](https://img.shields.io/badge/Patreon-Support-f96854?logo=patreon)](https://patreon.com/AndiUpn)
[![Trakteer](https://img.shields.io/badge/Trakteer-Support-red?logo=trakteer)](https://trakteer.id/andi_upn/gift)
[![Saweria](https://img.shields.io/badge/Saweria-Support-yellow?logo=saweria)](https://saweria.co/andiupn)

---

Selamat datang di **OpenCode Starter**, konfigurasi workspace eksperimental modular yang dioptimalkan untuk berkolaborasi dengan AI Agent menggunakan platform OpenCode.ai. Dengan pengaturan izin yang aman dan pembagian peran agen yang sangat presisi, Anda dapat membangun proyek apa pun dengan lebih cepat, aman, dan terkendali.

---

## 💡 Masalahnya: "Risiko Otonom" AI Liar
AI Agent yang sepenuhnya otonom sangat luar biasa kuat, namun mereka membawa risiko keamanan yang nyata. Tanpa adanya batas izin yang jelas, agen AI bisa saja menjalankan perintah bash yang merusak file sistem, secara tidak sengaja menghapus konfigurasi, atau membaca dan mempublikasikan berkas `.env` pribadi Anda ke log.

---

## ⚡ Solusinya: Otonomi Cepat yang Terjaga Aman

### 1. 🛡️ Penjaga Izin Granular (Granular Permissions)
Panduan izin aman yang telah terkonfigurasi di `opencode.json` untuk menolak secara tegas pembacaan berkas sensitif (seperti `.env`), namun tetap mengizinkan operasi pencarian git dan grep secara otomatis. Produktivitas tinggi dengan nol kecemasan keamanan.

### 🤖 2. 5 Pembagian Peran AI Modular
Dapatkan tim pengembang otonom yang terbagi dalam 5 spesialisasi langsung di `.opencode/agents/`:
- **`code`** — Menulis dan mengedit kode aplikasi secara aman.
- **`research`** — Menjelajahi dan memetakan struktur file arsitektur.
- **`debug`** & **`refactor`** — Mendiagnosa error dan melakukan optimasi bersih.
- **`document`** — Menulis dokumentasi lengkap tanpa kontaminasi kode sumber.

### 🌐 3. Perintah Diagnosa Bawaan (Slash Commands)
Eksekusi cepat perintah cerdas langsung pada AI agent:
- `/analyze` — Menganalisis dan merangkum arsitektur proyek.
- `/fix` — Memindai dan memperbaiki celah bug.
- `/explain [nama_file]` — Menjabarkan logika berkas kompleks dalam milidetik.

---

## 📊 LITE vs PRO: Upgrade Premium

`opencode-starter` dirancang sebagai baseline yang bersih. Untuk monorepos profesional dan alur kerja tingkat lanjut:

| Fitur | 🆓 LITE (Starter) | 💎 PRO (Premium) |
|---|:---:|:---:|
| **Specialized Agents** | 5 (Code, Research, dll.) | 5 (Modular System) |
| **Workflow Skills** | 2 (`coding-conventions`, `testing`) | 15+ (Database, Ops, dll.) |
| **Workspace Structure** | Simple | Status-first Monorepo (`active/`, dll.) |
| **Project Presets** | ❌ | 10 Presets (Next, Laravel, Flutter, dll.) |
| **Ops & Server Sync** | ❌ | ✅ (Docker Compose & Caddyfile ready) |

👉 **[Lihat Perbandingan Fitur Lengkap & Cara Upgrade](COMPARISON.md)**

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
- **Diagnose & Perbaikan Vuln:** `/fix`
- **Penjelasan Modul:** `/explain [nama_berkas]`

---

## 💖 Dukung Proyek Ini (Donasi)

Jika template starter ini membantu mempercepat alur kerja pengodean Anda, pertimbangkan untuk memberikan dukungan:
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer (Indonesia):** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria (Indonesia):** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 Lisensi

Proyek ini dilisensikan di bawah **MIT License**. Lihat berkas [LICENSE](LICENSE) file untuk informasi lebih lanjut.
