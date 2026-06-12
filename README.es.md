#Iniciador de OpenCode 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <strong>Español</strong> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a>
</div>

<br />

<div align="center">
  <h3><strong>Los asistentes de código más inteligentes necesitan los límites más seguros.</strong></h3>
  <p><strong>Una plantilla inicial modular de alto rendimiento optimizada para el ecosistema de agentes OpenCode.ai, que presenta permisos granulares seguros y controles de diagnóstico integrados.</strong></p>

  <p>Deje de preocuparse de que los agentes de IA ejecuten comandos de terminales destructivos o filtren variables de entorno privadas. Experimente la codificación autónoma segura y de alta velocidad.</p>
</div>

> 📦 Plantilla gratuita de **andiupn** ([kuncimu.com](https://kuncimu.com)) · Licenciado bajo [Licencia MIT](LICENSE)  
> ☕ Si es útil, [cómprame un café](https://ko-fi.com/andiupn) · 🚀 ¿Necesitas más funciones? Pruebe la [versión PRO](https://github.com/sponsors/andiupn?frequency=monthly)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/andiupn/opencode-starter)](https://github.com/andiupn/opencode-starter/releases)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
[![Patreon](https://img.shields.io/badge/Patreon-Support-f96854?logo=patreon)](https://patreon.com/AndiUpn)
[![Trakteer](https://img.shields.io/badge/Trakteer-Support-red?logo=trakteer)](https://trakteer.id/andi_upn/gift)
[![Saweria](https://img.shields.io/badge/Saweria-Support-yellow?logo=saweria)](https://saweria.co/andiupn)

---

Bienvenido a **OpenCode Starter**, una configuración de espacio de trabajo modular experimental optimizada para colaborar con agentes de IA utilizando la plataforma OpenCode.ai. Con pautas de control de acceso seguro y una división altamente precisa de las funciones de los agentes, puede desarrollar cualquier proyecto de manera más rápida, segura y con control total.

---

## 💡 El problema: el "riesgo autónomo"
Los agentes de IA totalmente autónomos son increíblemente poderosos, pero conllevan riesgos. Sin límites, un agente podría ejecutar comandos bash dañinos, eliminar accidentalmente configuraciones del sistema o leer/exponer sus archivos `.env` privados.

---

## ⚡ La solución: autonomía protegida de alta velocidad

### 1. 🛡️ Garantías de permisos granulares
Directrices seguras preconfiguradas en `opencode.json` que niegan explícitamente el acceso a archivos confidenciales (como `.env`), al tiempo que permiten de forma segura las operaciones git y grep de forma automática. Alta velocidad sin preocupaciones de seguridad.

### 🤖 2. 5 funciones modulares de la IA
Obtenga un equipo organizado y especializado de 5 agentes autónomos configurados directamente en `.opencode/agents/`:
- **`code`** — Escribir y editar código de forma segura.
- **`research`**: explora y asigna la arquitectura de la base de código.
- **`debug`** & **`refactor`**: diagnóstico, reparación y optimización limpia.
- **`document`** — Mantener la documentación sin contaminación de código.

### 🌐 3. Diagnóstico de barra integrado
Comandos de ejecución instantánea como `/analyze` para mapear la estructura del proyecto, `/fix` para escanear y corregir errores y `/explain` para descomponer archivos complejos en milisegundos.

---

## 📊 LITE vs PRO: La actualización Premium

`opencode-starter` está diseñado para ser una línea de base limpia. Para monorepos profesionales y flujos de trabajo avanzados:

| Característica | 🆓 LITE (Iniciador) | 💎PRO (Premium) |
|---|:---:|:---:|
| **Agentes especializados** | 5 (Código, Investigación, etc.) | 5 (Sistema modular) |
| **Habilidades de flujo de trabajo** | 2 (`coding-conventions`, `testing`) | 15+ (base de datos, operaciones, etc.) |
| **Estructura del espacio de trabajo** | Sencillo | Monorepo de estado primero (`active/`, etc.) |
| **Preajustes de proyecto** | ❌ | 10 ajustes preestablecidos (Siguiente, Laravel, Flutter, etc.) |
| **Operaciones y sincronización de servidores** | ❌ | ✅ (Listo para Docker Compose y Caddyfile) |

👉 **[Ver guía completa de comparación y actualización](COMPARISON.md)**

---

## 📂 Estructura del repositorio

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

## 🚀 Inicio rápido

### 1. Copiar y configurar el entorno
Copie la plantilla de variables de entorno de su proyecto:

```bash
cp .env.example .env
```

Abra el archivo `.env` e inserte su `GITHUB_TOKEN` para habilitar las integraciones del repositorio.

### 2. Iniciar la colaboración del agente
Inicie la CLI de OpenCode AI Agent o cargue el archivo de configuración `opencode.json` en su editor compatible con IA. Utilice los siguientes comandos integrados:
- **Análisis del Proyecto:** `/analyze`
- **Diagnosticar y reparar vulnerabilidades:** `/fix`
- **Explicar módulo:** `/explain [filename]`

---

## 💖 Apoye este proyecto (Donaciones)

Si esta plantilla inicial ayuda a acelerar su flujo de trabajo de codificación, considere apoyar o donar a través de los siguientes enlaces:
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria:** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 Licencia

Este proyecto tiene la licencia **Licencia MIT**. Consulte el archivo [LICENCIA](LICENSE) para obtener más información.