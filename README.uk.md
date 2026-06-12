# OpenCode Starter 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <strong>Українська</strong> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>

<br />

<div align="center">
  <h3><strong>Найрозумніші кодові помічники потребують найбезпечніших меж.</strong></h3>
  <p><strong>Високопродуктивний модульний початковий шаблон, оптимізований для екосистеми агента OpenCode.ai, містить безпечні детальні дозволи та вбудовані засоби діагностики.</strong></p>

  <p>Не хвилюйтеся про те, що агенти штучного інтелекту виконують деструктивні команди терміналу або витікають приватні змінні середовища. Відчуйте безпечне високошвидкісне автономне кодування.</p>
</div>

> 📦 Безкоштовний шаблон від **andiupn** ([kuncimu.com](https://kuncimu.com)) · Ліцензовано відповідно до [ліцензії MIT](LICENSE)  
> ☕ Якщо це корисно, [приготуйте мені кави](https://ko-fi.com/andiupn) · 🚀 Потрібні додаткові функції? Спробуйте [PRO версію](https://github.com/sponsors/andiupn?frequency=monthly)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/andiupn/opencode-starter)](https://github.com/andiupn/opencode-starter/releases)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
[![Patreon](https://img.shields.io/badge/Patreon-Support-f96854?logo=patreon)](https://patreon.com/AndiUpn)
[![Trakteer](https://img.shields.io/badge/Trakteer-Support-red?logo=trakteer)](https://trakteer.id/andi_upn/gift)
[![Saweria](https://img.shields.io/badge/Saweria-Support-yellow?logo=saweria)](https://saweria.co/andiupn)

---

Ласкаво просимо до **OpenCode Starter**, експериментальної модульної конфігурації робочого простору, оптимізованої для співпраці з агентами ШІ за допомогою платформи OpenCode.ai. Завдяки керівним принципам безпечного контролю доступу та високоточному розподілу ролей агентів ви можете будувати будь-який проект швидше, безпечніше та з повним контролем.

---

## 💡 Проблема: «автономний ризик»
Повністю автономні агенти ШІ неймовірно потужні, але вони несуть ризики. Без обмежень агент може запустити шкідливі команди bash, випадково видалити системні конфігурації або прочитати/розкрити ваші приватні файли `.env`.

---

## ⚡ Рішення: захищена високошвидкісна автономія

### 1. 🛡️ Гарантії детального дозволу
Попередньо налаштовані правила безпеки в `opencode.json`, які явно забороняють доступ до конфіденційних файлів (наприклад, `.env`), водночас безпечно дозволяючи операції git і grep автоматично. Висока швидкість з нульовою тривогою щодо безпеки.

### 🤖 2. 5 модульних ролей ШІ
Отримайте організовану спеціалізовану команду з 5 автономних агентів, налаштованих безпосередньо в `.opencode/agents/`:
- **`code`** — безпечне написання та редагування коду.
- **`research`** — Досліджує та відображає архітектуру кодової бази.
- **`debug`** & **`refactor`** — Діагностика, виправлення та чиста оптимізація.
- **`document`** — Ведення документації без забруднення коду.

### 🌐 3. Вбудована коса діагностика
Такі команди миттєвого виконання, як `/analyze` для відображення структури проекту, `/fix` для сканування та виправлення помилок і `/explain` для розбиття складних файлів за мілісекунди.

---

## 📊 LITE vs PRO: преміум-оновлення

`opencode-starter` створено як чисту базову лінію. Для професійних монорепо та розширених робочих процесів:

| Особливість | 🆓 LITE (початковий) | 💎 PRO (Преміум) |
|---|:---:|:---:|
| **Спеціалізовані агенти** | 5 (Кодекс, дослідження тощо) | 5 (Модульна система) |
| **Навички робочого процесу** | 2 (`coding-conventions`, `testing`) | 15+ (база даних, операції тощо) |
| **Структура робочого простору** | Простий | Статус-перший Monorepo (`active/` тощо) |
| **Налаштування проекту** | ❌ | 10 стилів (Next, Laravel, Flutter тощо) |
| **Ops & Server Sync** | ❌ | ✅ (Docker Compose & Caddyfile готовий) |

👉 **[Переглянути повний посібник із порівняння й оновлення](COMPARISON.md)**

---

## 📂 Структура сховища

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

## 🚀 Швидкий старт

### 1. Середовище копіювання та налаштування
Скопіюйте шаблон змінних середовища проекту:

```bash
cp .env.example .env
```

Відкрийте файл `.env` і вставте свій `GITHUB_TOKEN`, щоб увімкнути інтеграцію репозиторію.

### 2. Розпочніть співпрацю агента
Запустіть OpenCode AI Agent CLI або завантажте файл конфігурації `opencode.json` у вашому редакторі, який підтримує AI. Використовуйте такі вбудовані команди:
- **Аналіз проекту:** `/analyze`
- **Діагностика та усунення вразливостей:** `/fix`
- **Пояснити модуль:** `/explain [filename]`

---

## 💖 Підтримайте цей проект (пожертви)

Якщо цей стартовий шаблон допомагає пришвидшити ваш робочий процес кодування, подумайте про підтримку або пожертвування за такими посиланнями:
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria:** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 Ліцензія

Цей проект ліцензований згідно з **ліцензією MIT**. Додаткову інформацію див. у файлі [LICENSE](LICENSE).