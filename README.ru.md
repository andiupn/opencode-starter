# Стартер OpenCode 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <strong>Русский</strong> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>

<br />

<div align="center">
  <h3><strong>Самым умным помощникам по кодированию нужны самые безопасные границы.</strong></h3>
  <p><strong>Высокопроизводительный модульный стартовый шаблон, оптимизированный для экосистемы агентов OpenCode.ai, с безопасными детальными разрешениями и встроенными средствами диагностики.</strong></p>

  <p>Не беспокойтесь о том, что агенты ИИ выполняют деструктивные команды терминала или сливают частные переменные среды. Испытайте безопасное, высокоскоростное автономное программирование.</p>
</div>

> 📦 Бесплатный шаблон от **andiupn** ([kuncimu.com](https://kuncimu.com)) · Лицензия [MIT License](LICENSE)  
> ☕ Если полезно, [купи мне кофе](https://ko-fi.com/andiupn) · 🚀 Нужны дополнительные функции? Попробуйте [PRO-версию](https://github.com/sponsors/andiupn?frequency=monthly)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/andiupn/opencode-starter)](https://github.com/andiupn/opencode-starter/releases)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
__ЗНАК_3__
[![Trakteer](https://img.shields.io/badge/Trakteer-Support-red?logo=trakteer)](https://trakteer.id/andi_upn/gift)
[![Saweria](https://img.shields.io/badge/Saweria-Support-yellow?logo=saweria)](https://saweria.co/andiupn)

---

Добро пожаловать в **OpenCode Starter** — экспериментальную модульную конфигурацию рабочего пространства, оптимизированную для совместной работы с агентами ИИ с использованием платформы OpenCode.ai. Благодаря рекомендациям по безопасному контролю доступа и высокоточному разделению ролей агентов вы сможете реализовать любой проект быстрее, безопаснее и с полным контролем.

---

## 💡 Проблема: «Автономный риск»
Полностью автономные агенты ИИ невероятно мощны, но они несут риск. Без границ агент может запускать вредоносные команды bash, случайно удалять системные конфигурации или читать/раскрывать ваши личные файлы `.env`.

---

## ⚡ Решение: защищенная высокоскоростная автономия

### 1. 🛡️ Детальная защита разрешений
Предварительно настроенные правила безопасности в `opencode.json`, которые явно запрещают доступ к конфиденциальным файлам (например, `.env`), одновременно безопасно разрешая автоматически операции git и grep. Высокая скорость и отсутствие беспокойства о безопасности.

### 🤖 2. 5 модульных ролей ИИ
Создайте организованную специализированную команду из 5 автономных агентов, настроенных непосредственно в `.opencode/agents/`:
- **`code`** — Безопасное написание и редактирование кода.
- **`research`** — исследует и отображает архитектуру кодовой базы.
- **`debug`** и **`refactor`** — Диагностика, исправление и чистая оптимизация.
- **`document`** — Ведение документации без загрязнения кода.

### 🌐 3. Встроенная слеш-диагностика
Команды мгновенного выполнения, такие как `/analyze` для отображения структуры проекта, `/fix` для сканирования и исправления ошибок и `/explain` для разбиения сложных файлов за миллисекунды.

---

## 📊 LITE против PRO: Премиум-обновление

`opencode-starter` задуман как чистая базовая линия. Для профессиональных монорепозиториев и расширенных рабочих процессов:

| Особенность | 🆓 ЛАЙТ (Стартер) | 💎 ПРО (Премиум) |
|---|:---:|:---:|
| **Специализированные агенты** | 5 (Кодекс, Исследования и т. д.) | 5 (Модульная система) |
| **Навыки рабочего процесса** | 2 (`coding-conventions`, `testing`) | 15+ (База данных, Операционная служба и т. д.) |
| **Структура рабочего пространства** | Простой | Статус-первый монорепозиторий (`active/` и т. д.) |
| **Пресеты проекта** | ❌ | 10 пресетов (Next, Laravel, Flutter и т. д.) |
| **Операции и синхронизация сервера** | ❌ | ✅ (Docker Compose и Caddyfile готовы) |

👉 **[Просмотреть полное руководство по сравнению и обновлению](COMPARISON.md)**

---

## 📂 Структура репозитория

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

## 🚀 Быстрый старт

### 1. Среда копирования и настройки
Скопируйте шаблон переменных среды проекта:

```bash
cp .env.example .env
```

Откройте файл `.env` и вставьте свой `GITHUB_TOKEN`, чтобы включить интеграцию репозитория.

### 2. Начало совместной работы агентов
Запустите интерфейс командной строки OpenCode AI Agent или загрузите файл конфигурации `opencode.json` в свой AI-редактор. Используйте следующие встроенные команды:
- **Анализ проекта:** `/analyze`
- **Диагностика и устранение уязвимостей:** `/fix`
- **Объяснение модуля:** `/explain [filename]`

---

## 💖 Поддержите этот проект (пожертвования)

Если этот стартовый шаблон поможет ускорить ваш рабочий процесс кодирования, рассмотрите возможность поддержки или пожертвования по следующим ссылкам:
- **Ко-фи:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Саверия:** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 Лицензия

Этот проект распространяется по лицензии **MIT License**. Дополнительную информацию см. в файле [ЛИЦЕНЗИЯ](LICENSE).