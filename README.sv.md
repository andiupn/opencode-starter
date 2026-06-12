# OpenCode Starter 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <strong>Svenska</strong> | <a href="README.ro.md">Română</a>
</div>
<br>

<div align="center">
  <h3><strong>De smartaste kodassistenterna behöver de säkraste gränserna.</strong></h3>
  <p><strong>En högpresterande, modulär startmall optimerad för OpenCode.ai-agentekosystemet, med säkra granulära behörigheter och inbyggda diagnostiska kontroller.</strong></p>

  <p>Sluta oroa dig för AI-agenter som utför destruktiva terminalkommandon eller läcker privata miljövariabler. Upplev säker, höghastighets autonom kodning.</p>
</div>

> 📦 Gratis mall av **andiupn** ([kuncimu.com](https://kuncimu.com)) · Licensierad under [MIT License](LICENSE)  
> ☕ Om det är användbart, [köp mig en kaffe](https://ko-fi.com/andiupn) · 🚀 Behöver du fler funktioner? Prova [PRO-versionen](https://github.com/sponsors/andiupn?frequency=monthly)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/andiupn/opencode-starter)](https://github.com/andiupn/opencode-starter/releases)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
[![Patreon](https://img.shields.io/badge/Patreon-Support-f96854?logo=patreon)](https://patreon.com/AndiUpn)
[![Trakteer](https://img.shields.io/badge/Trakteer-Support-red?logo=trakteer)](https://trakteer.id/andi_upn/gift)
[![Saweria](https://img.shields.io/badge/Saweria-Support-yellow?logo=saweria)](https://saweria.co/andiupn)

---

Välkommen till **OpenCode Starter**, en experimentell modulär arbetsplatskonfiguration optimerad för samarbete med AI-agenter med hjälp av OpenCode.ai-plattformen. Med säkra riktlinjer för åtkomstkontroll och mycket exakt fördelning av agentroller kan du bygga vilket projekt som helst snabbare, säkrare och med fullständig kontroll.

---

## 💡 Problemet: Den "autonoma risken"
Helt autonoma AI-agenter är otroligt kraftfulla, men de medför risker. Utan gränser kan en agent köra skadliga bash-kommandon, av misstag radera systemkonfigurationer eller läsa/exponera dina privata `.env`-filer.

---

## ⚡ Lösningen: Bevakad höghastighetsautonomi

### 1. 🛡️ Granulära tillståndsskydd
Förkonfigurerade säkra riktlinjer i `opencode.json` som uttryckligen nekar åtkomst till känsliga filer (som `.env`), samtidigt som man säkert tillåter git- och grep-operationer automatiskt. Hög hastighet med noll säkerhetsångest.

### 🤖 2. 5 modulära AI-roller
Få ett organiserat, specialiserat team med 5 autonoma agenter konfigurerade direkt i `.opencode/agents/`:
- **`code`** — Skriva och redigera kod säkert.
- **`research`** — Utforskar och kartlägger kodbasarkitektur.
- **`debug`** & **`refactor`** — Diagnostisera, fixa och rensa optimering.
- **`document`** — Underhåll av dokumentation utan kodkontamination.

### 🌐 3. Inbyggd Slash Diagnostics
Direktkörningskommandon som `/analyze` för att kartlägga projektstruktur, `/fix` för att skanna och fixa buggar och `/explain` för att bryta ner komplexa filer på millisekunder.

---

## 📊 LITE vs PRO: Premium-uppgraderingen

`opencode-starter` är utformad för att vara en ren baslinje. För professionella monorepos och avancerade arbetsflöden:

| Funktion | 🆓 LITE (Starter) | 💎 PRO (Premium) |
|---|:---:|:---:|
| **Specialiserade ombud** | 5 (Kod, Forskning, etc.) | 5 (Modulärt system) |
| **Arbetsflödesfärdigheter** | 2 (`coding-conventions`, `testing`) | 15+ (Databas, Ops, etc.) |
| **Arbetsytans struktur** | Enkelt | Status-first Monorepo (`active/`, etc.) |
| **Projektförinställningar** | ❌ | 10 förinställningar (Nästa, Laravel, Flutter, etc.) |
| **Ops & Server Sync** | ❌ | ✅ (Docker Compose & Caddyfile redo) |

👉 **[Visa fullständig jämförelse- och uppgraderingsguide](COMPARISON.md)**

---

## 📂 Förvarsstruktur

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

## 🚀 Snabbstart

### 1. Kopiera och konfigurera miljö
Kopiera mallen för projektmiljövariabler:

```bash
cp .env.example .env
```

Öppna filen `.env` och infoga din `GITHUB_TOKEN` för att aktivera förvarsintegrationer.

### 2. Börja agentsamarbete
Starta OpenCode AI Agent CLI eller ladda `opencode.json` konfigurationsfilen i din AI-vänliga redigerare. Använd följande inbyggda kommandon:
- **Projektanalys:** `/analyze`
- **Diagnostisera och åtgärda sårbarheter:** `/fix`
- **Förklara modul:** `/explain [filename]`

---

## 💖 Stöd detta projekt (donationer)

Om den här startmallen hjälper till att påskynda ditt kodningsarbetsflöde, överväg att stödja eller donera via följande länkar:
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria:** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 Licens

Detta projekt är licensierat under **MIT License**. Se filen [LICENSE](LICENSE) för mer information.