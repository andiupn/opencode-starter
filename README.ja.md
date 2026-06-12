# OpenCode スターター 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <strong>日本語</strong> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a>
</div>

<br />

<div align="center">
  <h3><strong>最も賢いコードアシスタントには最も安全な境界が必要です。</strong></h3>
  <p><strong>OpenCode.ai エージェント エコシステム用に最適化された高性能のモジュール式スターター テンプレート。安全で詳細な権限と組み込みの診断コントロールが特徴です。</strong></p>

  <p>AI エージェントが破壊的なターミナル コマンドを実行したり、プライベート環境変数を漏洩したりすることを心配する必要はありません。安全で高速な自律コーディングを体験してください。</p>
</div>

> 📦 **andiupn** による無料テンプレート ([kuncimu.com](https://kuncimu.com)) · [MIT ライセンス](LICENSE) に基づいてライセンスされています  
> ☕ 役に立ったら、[コーヒーを買ってきてください](https://ko-fi.com/andiupn) · 🚀 さらに機能が必要ですか? [PRO バージョン](https://github.com/sponsors/andiupn?frequency=monthly) をお試しください

__バッジ_0__
__バッジ_1__
__バッジ_2__
__バッジ_3__
__バッジ_4__
__バッジ_5__

---

**OpenCode Starter** へようこそ。これは、OpenCode.ai プラットフォームを使用して AI エージェントとコラボレーションするために最適化された実験的なモジュール式ワークスペース構成です。安全なアクセス制御ガイドラインとエージェントの役割の非常に正確な分割を特徴としており、あらゆるプロジェクトをより迅速かつ安全に、完全に制御しながら構築できます。

---

## 💡 問題: 「自律的リスク」
完全自律型 AI エージェントは非常に強力ですが、リスクも伴います。境界がないと、エージェントが有害な bash コマンドを実行したり、システム構成を誤って削除したり、プライベート `.env` ファイルを読み取り/公開したりする可能性があります。

---

## ⚡ 解決策: 保護された高速自律性

### 1. 🛡️ 細分化された権限の保護策
`opencode.json` で事前構成された安全なガイドライン。機密ファイル (`.env` など) へのアクセスを明示的に拒否しながら、git および grep 操作を自動的に安全に許可します。高速でセキュリティの不安もゼロ。

### 🤖 2. 5 つのモジュール型 AI の役割
`.opencode/agents/` で直接構成された 5 つの自律エージェントからなる組織化された専門チームを取得します。
- **`code`** — コードを安全に作成および編集します。
- **`research`** — コードベース アーキテクチャを調べてマッピングします。
- **`debug`** および **`refactor`** — 診断、修正、クリーンな最適化。
- **`document`** — コードを汚染することなくドキュメントを維持します。

### 🌐 3. 組み込みのスラッシュ診断
プロジェクト構造をマップする `/analyze`、バグをスキャンして修正する `/fix`、複雑なファイルをミリ秒単位で分解する `/explain` などの即時実行コマンド。

---

## 📊 LITE vs PRO: プレミアムアップグレード

`opencode-starter` は、クリーンなベースラインになるように設計されています。プロフェッショナルなモノリポジトリと高度なワークフローの場合:

|特集 | 🆓 LITE (スターター) | 💎 プロ (プレミアム) |
|---|:---:|:---:|
| **専門エージェント** | 5 (コード、研究など) | 5 (モジュラーシステム) |
| **ワークフロー スキル** | 2 (`coding-conventions`、`testing`) | 15+ (データベース、運用など) |
| **ワークスペースの構造** |シンプル |ステータス優先のモノリポジトリ (`active/` など) |
| **プロジェクトのプリセット** | ❌ | 10 個のプリセット (Next、Laravel、Flutter など) |
| **運用とサーバーの同期** | ❌ | ✅ (Docker Compose および Caddyfile 対応) |

👉 **[完全な比較とアップグレード ガイドを表示](COMPARISON.md)**

---

## 📂 リポジトリ構造

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

## 🚀 クイックスタート

### 1. 環境のコピーとセットアップ
プロジェクト環境変数テンプレートをコピーします。

```bash
cp .env.example .env
```

`.env` ファイルを開き、`GITHUB_TOKEN` を挿入してリポジトリ統合を有効にします。

### 2. エージェントのコラボレーションを開始する
OpenCode AI Agent CLI を起動するか、AI 対応エディターに `opencode.json` 構成ファイルをロードします。次の組み込みコマンドを利用します。
- **プロジェクト分析:** `/analyze`
- **脆弱性の診断と修正:** `/fix`
- **モジュールの説明:** `/explain [filename]`

---

## 💖 このプロジェクトをサポートする (寄付)

このスターター テンプレートがコーディング ワークフローのスピードアップに役立つ場合は、次のリンクを介してサポートまたは寄付することを検討してください。
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **サウェリア:** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 ライセンス

このプロジェクトは **MIT ライセンス** に基づいてライセンスされています。詳細については、[LICENSE](LICENSE) ファイルを参照してください。