# OpenCode Iniciante 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <strong>Português (BR)</strong> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a>
</div>

<br />

<div align="center">
  <h3><strong>Os assistentes de código mais inteligentes precisam dos limites mais seguros.</strong></h3>
  <p><strong>Um modelo inicial modular e de alto desempenho otimizado para o ecossistema de agentes OpenCode.ai, com permissões granulares seguras e controles de diagnóstico integrados.</strong></p>

  <p>Pare de se preocupar com agentes de IA executando comandos de terminal destrutivos ou vazando variáveis de ambiente privadas. Experimente codificação autônoma segura e de alta velocidade.</p>
</div>

> 📦 Modelo gratuito de **andiupn** ([kuncimu.com](https://kuncimu.com)) · Licenciado sob [Licença MIT](LICENSE)  
> ☕ Se for útil, [me compre um café](https://ko-fi.com/andiupn) · 🚀 Precisa de mais recursos? Experimente a [versão PRO](https://github.com/sponsors/andiupn?frequency=monthly)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
__EMBAIXO_1__
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
__EMBAIXO_3__
__EMBAIXO_4__
__EMBLEMA_5__

---

Bem-vindo ao **OpenCode Starter**, uma configuração experimental de espaço de trabalho modular otimizada para colaboração com agentes de IA usando a plataforma OpenCode.ai. Apresentando diretrizes de controle de acesso seguro e divisão altamente precisa de funções de agente, você pode construir qualquer projeto de forma mais rápida, segura e com controle total.

---

## 💡 O Problema: O “Risco Autônomo”
Agentes de IA totalmente autônomos são incrivelmente poderosos, mas trazem riscos. Sem limites, um agente pode executar comandos bash prejudiciais, excluir acidentalmente configurações do sistema ou ler/expor seus arquivos `.env` privados.

---

## ⚡ A solução: autonomia protegida em alta velocidade

### 1. 🛡️ Salvaguardas granulares de permissão
Diretrizes seguras pré-configuradas em `opencode.json` que negam explicitamente o acesso a arquivos confidenciais (como `.env`), ao mesmo tempo que permitem operações git e grep automaticamente com segurança. Alta velocidade com zero ansiedade de segurança.

### 🤖 2. 5 funções modulares de IA
Obtenha uma equipe organizada e especializada de 5 agentes autônomos configurados diretamente em `.opencode/agents/`:
- **`code`** — Escrever e editar código com segurança.
- **`research`** — Explora e mapeia a arquitetura da base de código.
- **`debug`** & **`refactor`** — Diagnóstico, correção e otimização limpa.
- **`document`** — Manutenção de documentações sem contaminação de código.

### 🌐 3. Diagnóstico de barra integrado
Comandos de execução instantânea como `/analyze` para mapear a estrutura do projeto, `/fix` para verificar e corrigir bugs e `/explain` para dividir arquivos complexos em milissegundos.

---

## 📊 LITE vs PRO: a atualização premium

`opencode-starter` foi projetado para ser uma linha de base limpa. Para monorepos profissionais e fluxos de trabalho avançados:

| Recurso | 🆓 LITE (iniciante) | 💎 PRO (Prêmio) |
|---|:---:|:---:|
| **Agentes Especializados** | 5 (Código, Pesquisa, etc.) | 5 (Sistema Modular) |
| **Habilidades de fluxo de trabalho** | 2 (`coding-conventions`, `testing`) | 15+ (banco de dados, operações, etc.) |
| **Estrutura do espaço de trabalho** | Simples | Monorepo com status primeiro (`active/`, etc.) |
| **Predefinições de projeto** | ❌ | 10 predefinições (Next, Laravel, Flutter, etc.) |
| **Operações e sincronização de servidor** | ❌ | ✅ (Docker Compose e Caddyfile prontos) |

👉 **[Ver guia completo de comparação e atualização](COMPARISON.md)**

---

## 📂 Estrutura do repositório

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

## 🚀 Início rápido

### 1. Ambiente de cópia e configuração
Copie o modelo de variáveis de ambiente do seu projeto:

```bash
cp .env.example .env
```

Abra o arquivo `.env` e insira seu `GITHUB_TOKEN` para habilitar integrações de repositório.

### 2. Comece a colaboração do agente
Inicie a CLI do OpenCode AI Agent ou carregue o arquivo de configuração `opencode.json` em seu editor compatível com IA. Utilize os seguintes comandos integrados:
- **Análise do Projeto:** `/analyze`
- **Diagnosticar e corrigir vulnerabilidades:** `/fix`
- **Módulo Explicar:** `/explain [filename]`

---

## 💖 Apoie este projeto (doações)

Se este modelo inicial ajudar a acelerar seu fluxo de trabalho de codificação, considere apoiar ou doar por meio dos seguintes links:
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria:** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 Licença

Este projeto está licenciado sob a **Licença MIT**. Consulte o arquivo [LICENSE](LICENSE) para obter mais informações.