# Bộ khởi động mã mở 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <strong>Tiếng Việt</strong> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <a href="README.tr.md">Türkçe</a> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>

<br />

<div align="center">
  <h3><strong>Trợ lý mã thông minh nhất cần có ranh giới an toàn nhất.</strong></h3>
  <p><strong>Mẫu khởi đầu mô-đun, hiệu suất cao được tối ưu hóa cho hệ sinh thái tác nhân OpenCode.ai, có các quyền chi tiết an toàn và kiểm soát chẩn đoán tích hợp.</strong></p>

  <p>Đừng lo lắng về việc tác nhân AI thực thi các lệnh đầu cuối mang tính phá hoại hoặc làm rò rỉ các biến môi trường riêng tư. Trải nghiệm mã hóa tự động tốc độ cao, an toàn.</p>
</div>

> 📦 Mẫu miễn phí của **andiupn** ([kuncimu.com](https://kuncimu.com)) · Được cấp phép theo [Giấy phép MIT](LICENSE)  
> ☕ Nếu hữu ích, [mua cho tôi một ly cà phê](https://ko-fi.com/andiupn) · 🚀 Bạn cần thêm tính năng? Hãy thử [phiên bản PRO](https://github.com/sponsors/andiupn?frequency=monthly)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/andiupn/opencode-starter)](https://github.com/andiupn/opencode-starter/releases)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
[![Patreon](https://img.shields.io/badge/Patreon-Support-f96854?logo=patreon)](https://patreon.com/AndiUpn)
[![Trakteer](https://img.shields.io/badge/Trakteer-Support-red?logo=trakteer)](https://trakteer.id/andi_upn/gift)
[![Saweria](https://img.shields.io/badge/Saweria-Support-yellow?logo=saweria)](https://saweria.co/andiupn)

---

Chào mừng bạn đến với **OpenCode Starter**, một cấu hình không gian làm việc mô-đun thử nghiệm được tối ưu hóa để cộng tác với các Tác nhân AI bằng nền tảng OpenCode.ai. Với các nguyên tắc kiểm soát truy cập an toàn và phân chia vai trò tác nhân có độ chính xác cao, bạn có thể xây dựng bất kỳ dự án nào nhanh hơn, an toàn hơn và có toàn quyền kiểm soát.

---

## 💡 Vấn đề: “Rủi ro tự chủ”
Các tác nhân AI hoàn toàn tự động cực kỳ mạnh mẽ nhưng chúng mang lại rủi ro. Không có ranh giới, tác nhân có thể chạy các lệnh bash có hại, vô tình xóa cấu hình hệ thống hoặc đọc/làm lộ các tệp `.env` riêng tư của bạn.

---

## ⚡ Giải pháp: Quyền tự chủ tốc độ cao được bảo vệ

### 1. 🛡️ Các biện pháp bảo vệ cấp phép chi tiết
Các nguyên tắc bảo mật được định cấu hình trước trong `opencode.json` từ chối rõ ràng quyền truy cập vào các tệp nhạy cảm (như `.env`), đồng thời cho phép tự động thực hiện các thao tác git và grep một cách an toàn. Tốc độ cao mà không phải lo lắng về vấn đề bảo mật.

### 🤖 2. 5 vai trò AI mô-đun
Sở hữu một nhóm chuyên biệt, có tổ chức gồm 5 tổng đài viên tự trị được định cấu hình trực tiếp trong `.opencode/agents/`:
- **`code`** — Viết và chỉnh sửa mã một cách an toàn.
- **`research`** — Khám phá và lập bản đồ kiến ​​trúc cơ sở mã.
- **`debug`** & **`refactor`** — Chẩn đoán, sửa lỗi và tối ưu hóa rõ ràng.
- **`document`** — Duy trì tài liệu mà không làm nhiễm bẩn mã.

### 🌐 3. Chẩn đoán dấu gạch chéo tích hợp
Các lệnh thực thi tức thì như `/analyze` để ánh xạ cấu trúc dự án, `/fix` để quét và sửa lỗi cũng như `/explain` để chia nhỏ các tệp phức tạp trong một phần nghìn giây.

---

## 📊 LITE vs PRO: Bản nâng cấp cao cấp

`opencode-starter` được thiết kế để trở thành đường cơ sở rõ ràng. Đối với monorepos chuyên nghiệp và quy trình làm việc nâng cao:

| Tính năng | 🆓 LITE (Người mới bắt đầu) | 💎 PRO (Cao cấp) |
|---|:---:|:---:|
| **Đại lý chuyên ngành** | 5 (Mã, Nghiên cứu, v.v.) | 5 (Hệ thống mô-đun) |
| **Kỹ năng làm việc** | 2 (`coding-conventions`, `testing`) | 15+ (Cơ sở dữ liệu, Hoạt động, v.v.) |
| **Cấu trúc không gian làm việc** | Đơn giản | Monorepo trạng thái đầu tiên (`active/`, v.v.) |
| **Cài đặt trước dự án** | ❌ | 10 cài đặt trước (Tiếp theo, Laravel, Flutter, v.v.) |
| **Đồng bộ hóa hoạt động và máy chủ** | ❌ | ✅ (Docker Compose & Caddyfile đã sẵn sàng) |

👉 **[Xem hướng dẫn so sánh và nâng cấp đầy đủ](COMPARISON.md)**

---

## 📂 Cấu trúc kho lưu trữ

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

## 🚀 Bắt đầu nhanh

### 1. Môi trường sao chép và cài đặt
Sao chép mẫu biến môi trường dự án của bạn:

```bash
cp .env.example .env
```

Mở tệp `.env` và chèn `GITHUB_TOKEN` của bạn để kích hoạt tích hợp kho lưu trữ.

### 2. Bắt đầu hợp tác với đại lý
Khởi chạy OpenCode AI Agent CLI hoặc tải tệp cấu hình `opencode.json` trong trình chỉnh sửa thân thiện với AI của bạn. Sử dụng các lệnh tích hợp sau:
- **Phân tích dự án:** `/analyze`
- **Chẩn đoán và khắc phục lỗ hổng:** `/fix`
- **Giải thích mô-đun:** `/explain [filename]`

---

## 💖 Hỗ trợ dự án này (Quyên góp)

Nếu mẫu khởi đầu này giúp tăng tốc quy trình viết mã của bạn, hãy cân nhắc hỗ trợ hoặc quyên góp qua các liên kết sau:
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria:** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 Giấy phép

Dự án này được cấp phép theo **Giấy phép MIT**. Xem tệp [LICENSE](LICENSE) để biết thêm thông tin.