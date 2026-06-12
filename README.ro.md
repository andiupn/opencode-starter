# OpenCode Starter 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <strong>Română</strong>
</div>

<br />

<div align="center">
  <h3><strong>Cei mai inteligenți asistenți de cod au nevoie de cele mai sigure granițe.</strong></h3>
  <p><strong>Un șablon de pornire modular, de înaltă performanță, optimizat pentru ecosistemul de agenți OpenCode.ai, cu permisiuni granulare sigure și controale de diagnosticare încorporate.</strong></p>

  <p>Nu vă mai faceți griji cu privire la agenții AI care execută comenzi distructive ale terminalului sau care scurg variabile de mediu private. Experimentați codare autonomă sigură, de mare viteză.</p>
</div>

> 📦 Șablon gratuit de la **andiupn** ([kuncimu.com](https://kuncimu.com)) · Licențiat sub [Licență MIT](LICENSE)  
> ☕ Dacă este util, [cumpără-mi o cafea](https://ko-fi.com/andiupn) · 🚀 Ai nevoie de mai multe funcții? Încercați [versiunea PRO](https://github.com/sponsors/andiupn?frequency=monthly)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/andiupn/opencode-starter)](https://github.com/andiupn/opencode-starter/releases)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
[![Patreon](https://img.shields.io/badge/Patreon-Support-f96854?logo=patreon)](https://patreon.com/AndiUpn)
[![Trakteer](https://img.shields.io/badge/Trakteer-Support-red?logo=trakteer)](https://trakteer.id/andi_upn/gift)
[![Saweria](https://img.shields.io/badge/Saweria-Support-yellow?logo=saweria)](https://saweria.co/andiupn)

---

Bine ați venit la **OpenCode Starter**, o configurație experimentală de spațiu de lucru modulară optimizată pentru colaborarea cu agenții AI folosind platforma OpenCode.ai. Dispunând de linii directoare pentru controlul accesului securizat și împărțirea foarte precisă a rolurilor de agent, puteți construi orice proiect mai rapid, mai sigur și cu control complet.

---

## 💡 Problema: „Riscul autonom”
Agenții AI complet autonomi sunt incredibil de puternici, dar aduc riscuri. Fără limite, un agent poate rula comenzi bash dăunătoare, poate șterge accidental configurații sistemice sau poate citi/expune fișierele dvs. private `.env`.

---

## ⚡ Soluția: Autonomie de mare viteză protejată

### 1. 🛡️ Măsuri de protecție granulare ale permisiunii
Orientări securizate preconfigurate în `opencode.json` care interzic în mod explicit accesul la fișierele sensibile (cum ar fi `.env`), permițând în același timp în siguranță operațiunile git și grep automat. Viteză mare cu zero anxietate de securitate.

### 🤖 2. 5 Roluri AI modulare
Obțineți o echipă organizată și specializată de 5 agenți autonomi configurați direct în `.opencode/agents/`:
- **`code`** — Scrierea și editarea codului în siguranță.
- **`research`** — Explorează și mapează arhitectura de bază de cod.
- **`debug`** și **`refactor`** — Diagnosticare, remediere și optimizare curată.
- **`document`** — Menținerea documentațiilor fără contaminarea codului.

### 🌐 3. Diagnosticare Slash încorporată
Comenzi de execuție instantanee precum `/analyze` pentru a mapa structura proiectului, `/fix` pentru a scana și a remedia erori și `/explain` pentru a descompune fișierele complexe în milisecunde.

---

## 📊 LITE vs PRO: Upgrade Premium

`opencode-starter` este conceput pentru a fi o linie de bază curată. Pentru monorepos profesionale și fluxuri de lucru avansate:

| Caracteristica | 🆓 LITE (Starter) | 💎 PRO (Premium) |
|---|:---:|:---:|
| **Agenți de specialitate** | 5 (Cod, Cercetare etc.) | 5 (Sistem Modular) |
| **Abilități de flux de lucru** | 2 (`coding-conventions`, `testing`) | 15+ (bază de date, operațiuni etc.) |
| **Structura spațiului de lucru** | Simplu | Status-primul Monorepo (`active/`, etc.) |
| **Presetări de proiect** | ❌ | 10 presetări (Next, Laravel, Flutter etc.) |
| **Opțiuni și sincronizare server** | ❌ | ✅ (Docker Compose & Caddyfile gata) |

👉 **[Vedeți ghidul complet de comparare și actualizare](COMPARISON.md)**

---

## 📂 Structura depozitului

```
your-workspace/
  .opencode/           # OpenCode agent rules, automation skills, and prompts
    agents/            # Instruction directives for 5 AI agents
    skills/            # Coding conventions and testing guides
  .env.example         # Template for environment variables
  .gitignore           # Standard Git ignore file
  AGENTS.md            # Master rules for AI Agents
  opencode.json        # OpenCode permissions, model selection, and command maps
  LICENSE              # Project license (MIT License)
```

---

## 🚀 Început rapid

### 1. Copiați și configurați mediul
Copiați șablonul pentru variabilele de mediu ale proiectului:

```bash
cp .env.example .env
```

Deschideți fișierul `.env` și introduceți `GITHUB_TOKEN` pentru a activa integrările în depozit.

### 2. Începeți colaborarea cu agenții
Lansați OpenCode AI Agent CLI sau încărcați fișierul de configurare `opencode.json` în editorul dvs. prietenos cu AI. Utilizați următoarele comenzi încorporate:
- **Analiza proiectului:** `/analyze`
- **Diagnosticați și remediați vulnerabilitățile:** `/fix`
- **Explicați modulul:** `/explain [filename]`

---

## 💖 Sprijină acest proiect (donații)

Dacă acest șablon de pornire vă ajută să vă accelerați fluxul de lucru de codare, luați în considerare sprijinirea sau donarea prin următoarele link-uri:
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria:** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 Licență

Acest proiect este licențiat sub **Licența MIT**. Consultați fișierul [LICENSE](LICENSE) pentru mai multe informații.