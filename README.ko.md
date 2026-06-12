# 오픈코드 스타터 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <strong>한국어</strong> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>

<br />

<div align="center">
  <h3><strong>가장 똑똑한 코드 도우미에게는 가장 안전한 경계가 필요합니다.</strong></h3>
  <p><strong>OpenCode.ai 에이전트 에코시스템에 최적화된 고성능 모듈식 시작 템플릿으로, 안전하고 세분화된 권한과 내장된 진단 제어 기능을 갖추고 있습니다.</strong></p>

  <p>AI 에이전트가 파괴적인 터미널 명령을 실행하거나 개인 환경 변수를 유출하는 것에 대해 걱정하지 마세요. 안전한 고속 자율 코딩을 경험해 보세요.</p>
</div>

> 📦 **andiupn**([kuncimu.com](https://kuncimu.com))의 무료 템플릿 · [MIT 라이선스](LICENSE)에 따라 라이선스가 부여됨  
> ♥ 도움이 되셨다면 [커피 사주세요](https://ko-fi.com/andiupn) · 🚀 더 많은 기능이 필요하신가요? [PRO 버전](https://github.com/sponsors/andiupn?frequency=monthly)을 사용해 보세요.

__배지_0__
__배지_1__
__배지_2__
__배지_3__
__배지_4__
__배지_5__

---

OpenCode.ai 플랫폼을 사용하여 AI 에이전트와 협업하도록 최적화된 실험적인 모듈식 작업 공간 구성인 **OpenCode Starter**에 오신 것을 환영합니다. 보안 액세스 제어 지침과 매우 정확한 상담원 역할 구분을 통해 모든 프로젝트를 더 빠르고 안전하며 완벽하게 제어할 수 있습니다.

---

## 💡 문제: "자율적 위험"
완전 자율형 AI 에이전트는 놀라울 정도로 강력하지만 위험을 초래합니다. 경계가 없으면 에이전트는 유해한 bash 명령을 실행하거나 실수로 시스템 구성을 삭제하거나 개인 `.env` 파일을 읽거나 노출할 수 있습니다.

---

## ⚡ 해결책: 안전한 고속 자율성

### 1. 🛡️ 세분화된 권한 보호 장치
민감한 파일(예: `.env`)에 대한 액세스를 명시적으로 거부하는 동시에 git 및 grep 작업을 자동으로 안전하게 허용하는 `opencode.json`의 사전 구성된 보안 지침입니다. 보안 불안이 없는 빠른 속도.

### 🤖 2. 5 모듈형 AI 역할
`.opencode/agents/`에서 직접 구성된 5개의 자율 에이전트로 구성된 조직적이고 전문화된 팀을 확보하세요.
- **`code`** — 코드를 안전하게 작성하고 편집합니다.
- **`research`** — 코드베이스 아키텍처를 탐색하고 매핑합니다.
- **`debug`** & **`refactor`** — 진단, 수정 및 깔끔한 최적화.
- **`document`** — 코드 오염 없이 문서를 유지합니다.

### 🌐 3. 내장된 슬래시 진단
프로젝트 구조를 매핑하는 `/analyze`, 버그를 검사하고 수정하는 `/fix`, 복잡한 파일을 밀리초 단위로 분해하는 `/explain`과 같은 즉시 실행 명령입니다.

---

## 📊 LITE 대 PRO: 프리미엄 업그레이드

`opencode-starter`은 깔끔한 기준선으로 설계되었습니다. 전문적인 단일 저장소 및 고급 워크플로우의 경우:

| 기능 | 🆓 LITE(스타터) | 💎 PRO(프리미엄) |
|---|:---:|:---:|
| **전문 에이전트** | 5(코드, 연구 등) | 5(모듈형 시스템) |
| **워크플로 기술** | 2(`coding-conventions`, `testing`) | 15세 이상(데이터베이스, 운영 등) |
| **작업공간 구조** | 단순 | 상태 우선 모노레포(`active/` 등) |
| **프로젝트 사전 설정** | ❌ | 10가지 사전 설정(Next, Laravel, Flutter 등) |
| **운영 및 서버 동기화** | ❌ | ✅ (Docker Compose 및 Caddyfile 준비됨) |

👉 **[전체 비교 및 업그레이드 가이드 보기](COMPARISON.md)**

---

## 📂 저장소 구조

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

## 🚀 빠른 시작

### 1. 복사 및 환경설정
프로젝트 환경 변수 템플릿을 복사합니다.

```bash
cp .env.example .env
```

`.env` 파일을 열고 `GITHUB_TOKEN`을 삽입하여 리포지토리 통합을 활성화합니다.

### 2. 상담원 협업 시작
OpenCode AI 에이전트 CLI를 실행하거나 AI 친화적인 편집기에서 `opencode.json` 구성 파일을 로드하세요. 다음 내장 명령을 활용하십시오.
- **프로젝트 분석:** `/analyze`
- **취약점 진단 및 수정:** `/fix`
- **모듈 설명:** `/explain [filename]`

---

## 💖 이 프로젝트를 후원하세요(기부)

이 시작 템플릿이 코딩 작업 흐름 속도를 높이는 데 도움이 된다면 다음 링크를 통해 지원하거나 기부하는 것을 고려해 보세요.
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **트랙티어:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **사웨리아:** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 라이선스

이 프로젝트는 **MIT 라이선스**에 따라 라이선스가 부여됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.