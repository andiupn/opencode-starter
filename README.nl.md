# OpenCode Starter 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <strong>Nederlands</strong> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>
<br>

<div align="center">
  <h3><strong>De slimste codeassistenten hebben de veiligste grenzen nodig.</strong></h3>
  <p><strong>Een krachtige, modulaire startersjabloon die is geoptimaliseerd voor het OpenCode.ai-agent-ecosysteem, met veilige gedetailleerde machtigingen en ingebouwde diagnostische bedieningselementen.</strong></p>

  <p>Maak je geen zorgen meer over AI-agents die destructieve terminalopdrachten uitvoeren of privé-omgevingsvariabelen lekken. Ervaar veilig en snel autonoom coderen.</p>
</div>

> 📦 Gratis sjabloon van **andiupn** ([kuncimu.com](https://kuncimu.com)) · Gelicentieerd onder [MIT-licentie](LICENSE)  
> ☕ Indien nuttig, [koop een kopje koffie](https://ko-fi.com/andiupn) · 🚀 Meer functies nodig? Probeer de [PRO-versie](https://github.com/sponsors/andiupn?frequency=monthly)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/andiupn/opencode-starter)](https://github.com/andiupn/opencode-starter/releases)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
[![Patreon](https://img.shields.io/badge/Patreon-Support-f96854?logo=patreon)](https://patreon.com/AndiUpn)
[![Trakteer](https://img.shields.io/badge/Trakteer-Support-red?logo=trakteer)](https://trakteer.id/andi_upn/gift)
[![Saweria](https://img.shields.io/badge/Saweria-Support-yellow?logo=saweria)](https://saweria.co/andiupn)

---

Welkom bij **OpenCode Starter**, een experimentele modulaire werkruimteconfiguratie die is geoptimaliseerd voor samenwerking met AI-agenten met behulp van het OpenCode.ai-platform. Met richtlijnen voor veilige toegangscontrole en een zeer nauwkeurige verdeling van agentrollen kunt u elk project sneller, veiliger en met volledige controle opbouwen.

---

## 💡 Het probleem: het ‘autonome risico’
Volledig autonome AI-agenten zijn ongelooflijk krachtig, maar brengen risico's met zich mee. Zonder grenzen kan een agent schadelijke bash-opdrachten uitvoeren, per ongeluk systemische configuraties verwijderen of uw privé `.env` bestanden lezen/openbaar maken.

---

## ⚡ De oplossing: bewaakte snelle autonomie

### 1. 🛡️ Gedetailleerde waarborgen voor toestemming
Vooraf geconfigureerde veilige richtlijnen in `opencode.json` die expliciet de toegang tot gevoelige bestanden weigeren (zoals `.env`), terwijl git- en grep-bewerkingen veilig automatisch worden toegestaan. Hoge snelheid zonder veiligheidsangst.

### 🤖 2. 5 modulaire AI-rollen
Krijg een georganiseerd, gespecialiseerd team van 5 autonome agenten die rechtstreeks in `.opencode/agents/` zijn geconfigureerd:
- **`code`** — Code veilig schrijven en bewerken.
- **`research`** — Onderzoekt en brengt codebase-architectuur in kaart.
- **`debug`** & **`refactor`** — Diagnose, reparatie en schone optimalisatie.
- **`document`** — Documentatie onderhouden zonder codevervuiling.

### 🌐 3. Ingebouwde Slash-diagnostiek
Directe uitvoeringsopdrachten zoals `/analyze` om de projectstructuur in kaart te brengen, `/fix` om bugs te scannen en op te lossen, en `/explain` om complexe bestanden in milliseconden op te splitsen.

---

## 📊 LITE versus PRO: de premium-upgrade

`opencode-starter` is ontworpen als een zuivere basislijn. Voor professionele monorepo's en geavanceerde workflows:

| Kenmerk | 🆓 LITE (Starter) | 💎 PRO (Premium) |
|---|:---:|:---:|
| **Gespecialiseerde agenten** | 5 (Code, onderzoek, enz.) | 5 (Modulair systeem) |
| **Workflowvaardigheden** | 2 (`coding-conventions`, `testing`) | 15+ (Database, Operaties, enz.) |
| **Werkruimtestructuur** | Eenvoudig | Status-eerste Monorepo (`active/`, enz.) |
| **Projectvoorinstellingen** | ❌ | 10 voorinstellingen (volgende, Laravel, Flutter, etc.) |
| **Ops en serversynchronisatie** | ❌ | ✅ (Docker Compose & Caddyfile gereed) |

👉 **[Bekijk de volledige vergelijkings- en upgradehandleiding](COMPARISON.md)**

---

## 📂 Repositorystructuur

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

## 🚀 Snelle start

### 1. Omgeving kopiëren en instellen
Kopieer uw sjabloon voor projectomgevingsvariabelen:

```bash
cp .env.example .env
```

Open het bestand `.env` en voer uw `GITHUB_TOKEN` in om repository-integraties in te schakelen.

### 2. Begin met samenwerken met agenten
Start de OpenCode AI Agent CLI of laad het `opencode.json` configuratiebestand in uw AI-vriendelijke editor. Gebruik de volgende ingebouwde opdrachten:
- **Projectanalyse:** `/analyze`
- **Kwetsbaarheden diagnosticeren en oplossen:** `/fix`
- **Module uitleggen:** `/explain [filename]`

---

## 💖 Steun dit project (donaties)

Als dit startersjabloon uw codeerworkflow helpt versnellen, overweeg dan om te steunen of te doneren via de volgende links:
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria:** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 Licentie

Dit project is gelicentieerd onder de **MIT-licentie**. Zie het bestand [LICENSE](LICENSE) voor meer informatie.