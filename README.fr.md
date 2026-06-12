# Démarreur OpenCode 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <strong>Français</strong> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>
<br>

<div align="center">
  <h3><strong>Les assistants de code les plus intelligents ont besoin des limites les plus sûres.</strong></h3>
  <p><strong>Un modèle de démarrage modulaire hautes performances optimisé pour l'écosystème d'agents OpenCode.ai, doté d'autorisations granulaires sécurisées et de contrôles de diagnostic intégrés.</strong></p>

  <p>Ne vous inquiétez plus des agents IA exécutant des commandes de terminal destructrices ou des fuites de variables d'environnement privées. Faites l'expérience d'un codage autonome sûr et à grande vitesse.</p>
</div>

> 📦 Modèle gratuit par **andiupn** ([kuncimu.com](https://kuncimu.com)) · Sous licence [Licence MIT](LICENSE)  
> ☕ Si utile, [achetez-moi un café](https://ko-fi.com/andiupn) · 🚀 Besoin de plus de fonctionnalités ? Essayez la [version PRO](https://github.com/sponsors/andiupn?frequency=monthly)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/andiupn/opencode-starter)](https://github.com/andiupn/opencode-starter/releases)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
[![Patreon](https://img.shields.io/badge/Patreon-Support-f96854?logo=patreon)](https://patreon.com/AndiUpn)
[![Trakteer](https://img.shields.io/badge/Trakteer-Support-red?logo=trakteer)](https://trakteer.id/andi_upn/gift)
[![Saweria](https://img.shields.io/badge/Saweria-Support-yellow?logo=saweria)](https://saweria.co/andiupn)

---

Bienvenue dans **OpenCode Starter**, une configuration d'espace de travail modulaire expérimentale optimisée pour la collaboration avec des agents IA à l'aide de la plateforme OpenCode.ai. Grâce à des directives de contrôle d'accès sécurisé et à une répartition très précise des rôles d'agent, vous pouvez créer n'importe quel projet plus rapidement, de manière plus sûre et avec un contrôle total.

---

## 💡 Le problème : le « risque autonome »
Les agents d’IA entièrement autonomes sont incroyablement puissants, mais ils comportent des risques. Sans limites, un agent peut exécuter des commandes bash nuisibles, supprimer accidentellement des configurations systémiques ou lire/exposer vos fichiers `.env` privés.

---

## ⚡ La solution : une autonomie gardée à haut débit

### 1. 🛡️ Garanties d'autorisation granulaires
Directives sécurisées préconfigurées dans `opencode.json` qui refusent explicitement l'accès aux fichiers sensibles (comme `.env`), tout en autorisant automatiquement et en toute sécurité les opérations git et grep. Haute vitesse sans souci de sécurité.

### 🤖 2. 5 rôles d'IA modulaires
Bénéficiez d'une équipe organisée et spécialisée de 5 agents autonomes configurés directement dans `.opencode/agents/` :
- **`code`** — Écrivez et modifiez du code en toute sécurité.
- **`research`** – Explore et cartographie l'architecture de base de code.
- **`debug`** & **`refactor`** — Diagnostic, correction et optimisation propre.
- **`document`** — Maintenir les documentations sans contamination du code.

### 🌐 3. Diagnostics Slash intégrés
Commandes d'exécution instantanée telles que `/analyze` pour cartographier la structure du projet, `/fix` pour analyser et corriger les bogues, et `/explain` pour décomposer des fichiers complexes en quelques millisecondes.

---

## 📊 LITE vs PRO : la mise à niveau Premium

`opencode-starter` est conçu pour être une ligne de base propre. Pour les monorepos professionnels et les workflows avancés :

| Fonctionnalité | 🆓 LITE (Démarreur) | 💎 PRO (Premium) |
|---|:---:|:---:|
| **Agents spécialisés** | 5 (Code, Recherche, etc.) | 5 (Système modulaire) |
| **Compétences en matière de flux de travail** | 2 (`coding-conventions`, `testing`) | 15+ (base de données, opérations, etc.) |
| **Structure de l'espace de travail** | Simple | Monorepo avec statut premier (`active/`, etc.) |
| **Préréglages du projet** | ❌ | 10 préréglages (Suivant, Laravel, Flutter, etc.) |
| **Opérations et synchronisation du serveur** | ❌ | ✅ (Docker Compose et Caddyfile prêts) |

👉 **[Voir la comparaison complète et le guide de mise à niveau](COMPARISON.md)**

---

## 📂 Structure du référentiel

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

## 🚀 Démarrage rapide

### 1. Environnement de copie et de configuration
Copiez le modèle de variables d'environnement de votre projet :

```bash
cp .env.example .env
```

Ouvrez le fichier `.env` et insérez votre `GITHUB_TOKEN` pour activer les intégrations de référentiel.

### 2. Commencer la collaboration des agents
Lancez la CLI OpenCode AI Agent ou chargez le fichier de configuration `opencode.json` dans votre éditeur compatible avec l'IA. Utilisez les commandes intégrées suivantes :
- **Analyse du projet :** `/analyze`
- ** Diagnostiquer et corriger les vulnérabilités :** `/fix`
- **Module d'explication :** `/explain [filename]`

---

## 💖 Soutenez ce projet (Dons)

Si ce modèle de démarrage permet d'accélérer votre flux de travail de codage, envisagez de soutenir ou de faire un don via les liens suivants :
- **Ko-fi :** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon :** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer :** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria :** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 Licence

Ce projet est sous licence **MIT License**. Consultez le fichier [LICENSE](LICENSE) pour plus d'informations.