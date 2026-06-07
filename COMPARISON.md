# LITE vs PRO Comparison — OpenCode.ai Edition

> Bingung memilih versi mana? Berikut perbandingan fitur lengkap antara edisi LITE (Starter) dan PRO (Premium Workspace).

## TL;DR

- **LITE / Starter (Gratis):** Cocok untuk eksperimen modular dan single-project sederhana. Menyertakan 5 subagents dasar, model izin granular `opencode.json`, lisensi open-source MIT, dan struktur proyek standar.
- **PRO / Premium (Berbayar $1–$5):** Ditujukan untuk pengembang profesional, freelancer, dan agensi. Menyertakan modular skills tingkat lanjut (Drizzle ORM migration, Docker/Caddy reloader, rules-audit), 10 stack presets, dan status-first multi-project monorepo workspace.

---

## Feature Matrix

| Fitur | 🆓 LITE (Starter) | 💎 PRO (Premium) |
|---|:---:|:---:|
| **Modular Agents** | 5 | 5 |
| `@code` (Primary Coding) | ✅ | ✅ |
| `@research` (Exploration) | ✅ | ✅ |
| `@debug` (Troubleshoot) | ✅ | ✅ |
| `@refactor` (Clean Code) | ✅ | ✅ |
| `@document` (Docs Maintenance) | ✅ | ✅ |
| | | |
| **Workflow Skills** | 2 | 15+ |
| `coding-conventions` | ✅ | ✅ |
| `testing-patterns` | ✅ | ✅ |
| `database-migration` | ❌ | ✅ |
| `ops-sync` (Docker/Caddy) | ❌ | ✅ |
| `knowledge-extract` | ❌ | ✅ |
| *Dan 10 skills premium lainnya* | ❌ | ✅ |
| | | |
| **Project Presets (`/init-project`)** | ❌ | 10 Presets |
| | | |
| **Struktur Workspace** | Simple (`src/`, `docs/`) | Status-first Monorepo (`active/`, `staging/`, `archive/`, `shared/`, `ops/`, `artifacts/`) |
| Multi-project orchestration | ❌ | ✅ |
| Project lifecycle workflow | ❌ | ✅ |
| | | |
| **Lisensi & Dukungan** | MIT License | Proprietary Commercial |
| Redistribution allowed | ✅ | ❌ |
| Komersial (proyek klien & internal) | ✅ | ✅ |
| Dukungan Email | Best-effort (Komunitas) | Best-effort (No SLA - Prioritas Tinggi) |
| Pembaruan Berkelanjutan | Via GitHub | Via [GitHub Sponsors](https://github.com/sponsors/andiupn?frequency=monthly) |

---

## When to Choose Which?

### Pilih **LITE (Starter)** jika:
- ✅ Anda baru mulai mempelajari orkestrasi AI Agent menggunakan OpenCode.ai.
- ✅ Proyek Anda adalah single-project eksperimental (1 aplikasi saja).
- ✅ Anda ingin membuat fork komunitas gratis dan open-source.
- ✅ Anda ingin mencoba sistem izin modular secara gratis terlebih dahulu.

### Pilih **PRO (Premium)** jika:
- ✅ Anda mengelola banyak proyek aktif untuk klien atau internal (Agensi / Freelancer).
- ✅ Anda membutuhkan modular skills yang lebih kaya untuk sinkronisasi database dan server.
- ✅ Anda membutuhkan state-management pengetahuan (Riset, Rencana, Memory) yang terintegrasi.
- ✅ Anda ingin meningkatkan kecepatan pengerjaan dengan presets otomasi yang super lengkap.
- ✅ Anda ingin mendukung pemeliharaan berkelanjutan dari proyek ini.

---

## Upgrade Path

Jika Anda sudah menggunakan versi LITE dan ingin beralih ke PRO:

1. Dapatkan lisensi resmi versi PRO di **[GitHub Sponsors](https://github.com/sponsors/andiupn?frequency=monthly)**.
2. Unduh berkas repositori `opencode-pro`.
3. Pindahkan berkas kode proyek Anda yang sudah ada dari versi Starter ke direktori `active/web/<nama-proyek>` di versi PRO.
4. Sesuaikan konfigurasi file `AGENTS.md` Anda.

Tidak ada lock-in — Anda dapat kembali ke versi LITE kapan saja secara bebas.

---

## Hubungi Kami

- **Pertanyaan Umum / Masalah:** Silakan buat Issue di GitHub [github.com/andiupn](https://github.com/andiupn).
- **Pertanyaan Pra-Penjualan PRO:** Hubungi kami melalui email di **andi.upn@gmail.com**.

👉 **[Dapatkan Edisi PRO di GitHub Sponsors](https://github.com/sponsors/andiupn?frequency=monthly)**
