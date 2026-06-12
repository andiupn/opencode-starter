# OpenCode Starter 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <strong>Italiano</strong> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a>
</div>

<br />

<div align="center">
  <h3><strong>Gli assistenti di codice più intelligenti hanno bisogno dei confini più sicuri.</strong></h3>
  <p><strong>Un modello iniziale modulare e ad alte prestazioni ottimizzato per l'ecosistema di agenti OpenCode.ai, dotato di autorizzazioni granulari sicure e controlli diagnostici integrati.</strong></p>

  <p>Smettila di preoccuparti che gli agenti IA eseguano comandi terminali distruttivi o divulghino variabili di ambiente private. Sperimenta una codifica autonoma sicura e ad alta velocità.</p>
</div>

> 📦 Modello gratuito di **andiupn** ([kuncimu.com](https://kuncimu.com)) · Concesso in licenza con [licenza MIT](LICENSE)  
> ☕ Se utile, [offrimi un caffè](https://ko-fi.com/andiupn) · 🚀 Hai bisogno di più funzionalità? Prova la [versione PRO](https://github.com/sponsors/andiupn?frequency=monthly)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/andiupn/opencode-starter)](https://github.com/andiupn/opencode-starter/releases)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
[![Patreon](https://img.shields.io/badge/Patreon-Support-f96854?logo=patreon)](https://patreon.com/AndiUpn)
[![Trakteer](https://img.shields.io/badge/Trakteer-Support-red?logo=trakteer)](https://trakteer.id/andi_upn/gift)
[![Saweria](https://img.shields.io/badge/Saweria-Support-yellow?logo=saweria)](https://saweria.co/andiupn)

---

Benvenuto in **OpenCode Starter**, una configurazione sperimentale di spazio di lavoro modulare ottimizzata per la collaborazione con agenti AI utilizzando la piattaforma OpenCode.ai. Grazie alle linee guida per il controllo degli accessi sicuri e alla divisione estremamente precisa dei ruoli degli agenti, puoi realizzare qualsiasi progetto in modo più rapido, sicuro e con un controllo completo.

---

## 💡 Il Problema: Il "Rischio Autonomo"
Gli agenti IA completamente autonomi sono incredibilmente potenti, ma comportano rischi. Senza limiti, un agente potrebbe eseguire comandi bash dannosi, eliminare accidentalmente configurazioni di sistema o leggere/esporre i tuoi file privati ​​`.env`.

---

## ⚡ La Soluzione: Autonomia Protetta nell'Alta Velocità

### 1. 🛡️ Salvaguardie granulari delle autorizzazioni
Linee guida sicure preconfigurate in `opencode.json` che negano esplicitamente l'accesso a file sensibili (come `.env`), consentendo al contempo in modo sicuro le operazioni git e grep automaticamente. Alta velocità senza preoccupazioni per la sicurezza.

### 🤖 2. 5 ruoli IA modulari
Ottieni un team organizzato e specializzato di 5 agenti autonomi configurati direttamente in `.opencode/agents/`:
- **`code`**: scrittura e modifica del codice in sicurezza.
- **`research`**: esplora e mappa l'architettura della base di codice.
- **`debug`** e **`refactor`**: diagnosi, correzione e ottimizzazione pulita.
- **`document`** — Mantenimento della documentazione senza contaminazione del codice.

### 🌐 3. Diagnostica Slash integrata
Comandi di esecuzione istantanea come `/analyze` per mappare la struttura del progetto, `/fix` per scansionare e correggere bug e `/explain` per suddividere file complessi in millisecondi.

---

## 📊 LITE vs PRO: l'aggiornamento Premium

`opencode-starter` è progettato per essere una linea di base pulita. Per monorepos professionali e flussi di lavoro avanzati:

| Caratteristica | 🆓 LITE (Starter) | 💎PRO (Premium) |
|---|:---:|:---:|
| **Agenti Specializzati** | 5 (Codice, Ricerca, ecc.) | 5 (Sistema Modulare) |
| **Competenze relative al flusso di lavoro** | 2 (`coding-conventions`, `testing`) | 15+ (Database, Operazioni, ecc.) |
| **Struttura dell'area di lavoro** | Semplice | Stato-primo Monorepo (`active/`, ecc.) |
| **Preimpostazioni del progetto** | ❌| 10 preimpostazioni (Next, Laravel, Flutter, ecc.) |
| **Opzioni e sincronizzazione server** | ❌| ✅ (Docker Compose e Caddyfile pronti) |

👉 **[Visualizza la guida completa al confronto e all'aggiornamento](COMPARISON.md)**

---

## 📂 Struttura del repository

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

## 🚀Avvio rapido

### 1. Copia e impostazione dell'ambiente
Copia il modello delle variabili di ambiente del progetto:

```bash
cp .env.example .env
```

Apri il file `.env` e inserisci il tuo `GITHUB_TOKEN` per abilitare le integrazioni del repository.

### 2. Iniziare la collaborazione con l'agente
Avvia la CLI di OpenCode AI Agent o carica il file di configurazione `opencode.json` nel tuo editor compatibile con AI. Utilizza i seguenti comandi integrati:
- **Analisi del progetto:** `/analyze`
- **Diagnostica e correggi le vulnerabilità:** `/fix`
- **Modulo Spiega:** `/explain [filename]`

---

## 💖 Sostieni questo progetto (donazioni)

Se questo modello iniziale ti aiuta ad accelerare il flusso di lavoro di codifica, valuta la possibilità di sostenere o fare una donazione tramite i seguenti collegamenti:
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria:** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 Licenza

Questo progetto è concesso in licenza con la **Licenza MIT**. Per ulteriori informazioni, consulta il file [LICENZA](LICENSE).