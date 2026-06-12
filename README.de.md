# OpenCode Starter 🚀

<div align="center">
  <strong>Englisch</strong> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polnisch</a>
</div>

<br />

<div align="center">
  <h3><strong>Die intelligentesten Code-Assistenten benötigen die sichersten Grenzen.</strong></h3>
  <p><strong>Eine leistungsstarke, modulare Starter-Vorlage, optimiert für das OpenCode.ai-Agenten-Ökosystem, mit sicheren granularen Berechtigungen und integrierten Diagnosekontrollen.</strong></p>

  <p>Machen Sie sich keine Sorgen darüber, dass KI-Agenten zerstörerische Terminalbefehle ausführen oder private Umgebungsvariablen preisgeben. Erleben Sie sicheres, autonomes Hochgeschwindigkeits-Codieren.</p>
</div>

> 📦 Kostenlose Vorlage von **andiupn** ([kuncimu.com](https://kuncimu.com)) · Lizenziert unter [MIT-Lizenz](LICENSE)  
> ☕ Wenn es nützlich ist, [kauf mir einen Kaffee](https://ko-fi.com/andiupn) · 🚀 Benötigen Sie weitere Funktionen? Probieren Sie die [PRO-Version](https://github.com/sponsors/andiupn?frequency=monthly) aus.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/andiupn/opencode-starter)](https://github.com/andiupn/opencode-starter/releases)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
[![Patreon](https://img.shields.io/badge/Patreon-Support-f96854?logo=patreon)](https://patreon.com/AndiUpn)
[![Trakteer](https://img.shields.io/badge/Trakteer-Support-red?logo=trakteer)](https://trakteer.id/andi_upn/gift)
[![Saweria](https://img.shields.io/badge/Saweria-Support-yellow?logo=saweria)](https://saweria.co/andiupn)

---

Willkommen bei **OpenCode Starter**, einer experimentellen modularen Arbeitsbereichskonfiguration, die für die Zusammenarbeit mit KI-Agenten über die OpenCode.ai-Plattform optimiert ist. Mit sicheren Zugriffskontrollrichtlinien und einer hochpräzisen Aufteilung der Agentenrollen können Sie jedes Projekt schneller, sicherer und mit vollständiger Kontrolle umsetzen.

---

## 💡 Das Problem: Das „autonome Risiko“
Vollständig autonome KI-Agenten sind unglaublich leistungsfähig, bergen jedoch Risiken. Ohne Grenzen könnte ein Agent schädliche Bash-Befehle ausführen, versehentlich Systemkonfigurationen löschen oder Ihre privaten `.env`-Dateien lesen/offenlegen.

---

## ⚡ Die Lösung: Geschützte Hochgeschwindigkeitsautonomie

### 1. 🛡️ Detaillierte Berechtigungsschutzmaßnahmen
Vorkonfigurierte Sicherheitsrichtlinien in `opencode.json`, die den Zugriff auf vertrauliche Dateien (wie `.env`) explizit verweigern und gleichzeitig Git- und Grep-Vorgänge sicher automatisch zulassen. Hohe Geschwindigkeit ohne Sicherheitsangst.

### 🤖 2. 5 modulare KI-Rollen
Erhalten Sie ein organisiertes, spezialisiertes Team aus 5 autonomen Agenten, die direkt in `.opencode/agents/` konfiguriert werden:
- **`code`** – Code sicher schreiben und bearbeiten.
- **`research`** – Erforscht und kartiert die Codebasisarchitektur.
- **`debug`** & **`refactor`** – Diagnose, Behebung und saubere Optimierung.
- **`document`** – Dokumentationen ohne Code-Kontamination pflegen.

### 🌐 3. Integrierte Slash-Diagnose
Sofortige Ausführungsbefehle wie `/analyze` zum Zuordnen der Projektstruktur, `/fix` zum Scannen und Beheben von Fehlern und `/explain` zum Aufschlüsseln komplexer Dateien in Millisekunden.

---

## 📊 LITE vs. PRO: Das Premium-Upgrade

`opencode-starter` ist als saubere Basislinie konzipiert. Für professionelle Monorepos und erweiterte Workflows:

| Funktion | 🆓 LITE (Starter) | 💎 PRO (Premium) |
|---|:---:|:---:|
| **Spezialisierte Agenten** | 5 (Code, Forschung usw.) | 5 (Baukastensystem) |
| **Workflow-Fähigkeiten** | 2 (`coding-conventions`, `testing`) | 15+ (Datenbank, Operations usw.) |
| **Arbeitsbereichsstruktur** | Einfach | Status-First-Monorepo (`active/` usw.) |
| **Projektvoreinstellungen** | ❌ | 10 Voreinstellungen (Next, Laravel, Flutter usw.) |
| **Ops & Server-Synchronisierung** | ❌ | ✅ (Docker Compose & Caddyfile bereit) |

👉 **[Vollständige Vergleichs- und Upgrade-Anleitung anzeigen](COMPARISON.md)**

---

## 📂 Repository-Struktur

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

## 🚀 Schnellstart

### 1. Umgebung kopieren und einrichten
Kopieren Sie die Vorlage für Ihre Projektumgebungsvariablen:

```bash
cp .env.example .env
```

Öffnen Sie die Datei `.env` und fügen Sie Ihre Datei `GITHUB_TOKEN` ein, um Repository-Integrationen zu aktivieren.

### 2. Beginnen Sie mit der Zusammenarbeit der Agenten
Starten Sie die OpenCode AI Agent-CLI oder laden Sie die Konfigurationsdatei `opencode.json` in Ihren KI-freundlichen Editor. Nutzen Sie die folgenden integrierten Befehle:
- **Projektanalyse:** `/analyze`
- **Schwachstellen diagnostizieren und beheben:** `/fix`
- **Modul erklären:** `/explain [filename]`

---

## 💖 Unterstützen Sie dieses Projekt (Spenden)

Wenn diese Starter-Vorlage Ihren Codierungs-Workflow beschleunigt, denken Sie darüber nach, über die folgenden Links zu unterstützen oder zu spenden:
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria:** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 Lizenz

Dieses Projekt ist unter der **MIT-Lizenz** lizenziert. Weitere Informationen finden Sie in der Datei [LICENSE](LICENSE).