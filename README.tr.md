# OpenCode Başlatıcı 🚀

<div align="center">
  <a href="README.md">English</a> | <a href="README.id.md">Bahasa Indonesia</a> | <a href="README.zh.md">简体中文</a> | <a href="README.hi.md">हिन्दी</a> | <a href="README.fr-ca.md">Français (CA)</a> | <a href="README.de.md">Deutsch</a> | <a href="README.fr.md">Français</a> | <a href="README.pt-br.md">Português (BR)</a> | <a href="README.vi.md">Tiếng Việt</a> | <a href="README.pl.md">Polski</a> | <a href="README.ja.md">日本語</a> | <a href="README.ko.md">한국어</a> | <a href="README.es.md">Español</a> | <strong>Türkçe</strong> | <a href="README.it.md">Italiano</a> | <a href="README.ru.md">Русский</a> | <a href="README.uk.md">Українська</a> | <a href="README.nl.md">Nederlands</a> | <a href="README.sv.md">Svenska</a> | <a href="README.ro.md">Română</a>
</div>

<br />

<div align="center">
  <h3><strong>En akıllı kod yardımcıları en güvenli sınırlara ihtiyaç duyar.</strong></h3>
  <p><strong>OpenCode.ai aracı ekosistemi için optimize edilmiş, güvenli ayrıntılı izinler ve yerleşik tanılama kontrolleri içeren yüksek performanslı, modüler bir başlangıç şablonu.</strong></p>

  <p>Yapay zeka aracılarının yıkıcı terminal komutları yürütmesi veya özel ortam değişkenlerini sızdırması konusunda endişelenmeyi bırakın. Güvenli, yüksek hızlı bağımsız kodlamayı deneyimleyin.</p>
</div>

> 📦 **andiupn** ([kuncimu.com](https://kuncimu.com)) tarafından hazırlanan ücretsiz şablon · [MIT Lisansı](LICENSE) kapsamında lisanslıdır  
> ☕ Yararlıysa, [bana bir kahve al](https://ko-fi.com/andiupn) · 🚀 Daha fazla özelliğe mi ihtiyacınız var? [PRO sürümünü] deneyin(https://github.com/sponsors/andiupn?frequency=monthly)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/andiupn/opencode-starter)](https://github.com/andiupn/opencode-starter/releases)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-Support-ff5f5f?logo=ko-fi)](https://ko-fi.com/andiupn)
[![Patreon](https://img.shields.io/badge/Patreon-Support-f96854?logo=patreon)](https://patreon.com/AndiUpn)
[![Trakteer](https://img.shields.io/badge/Trakteer-Support-red?logo=trakteer)](https://trakteer.id/andi_upn/gift)
[![Saweria](https://img.shields.io/badge/Saweria-Support-yellow?logo=saweria)](https://saweria.co/andiupn)

---

OpenCode.ai platformunu kullanarak AI Aracılarıyla işbirliği yapmak için optimize edilmiş deneysel bir modüler çalışma alanı yapılandırması olan **OpenCode Starter**'a hoş geldiniz. Güvenli erişim kontrolü yönergeleri ve aracı rollerinin son derece hassas bir şekilde bölünmesiyle, her türlü projeyi daha hızlı, daha güvenli ve tam kontrolle oluşturabilirsiniz.

---

## 💡 Sorun: "Otonom Risk"
Tamamen otonom yapay zeka ajanları inanılmaz derecede güçlüdür ancak riskler de getirirler. Sınırlar olmaksızın, bir aracı zararlı bash komutlarını çalıştırabilir, sistemsel yapılandırmaları yanlışlıkla silebilir veya özel `.env` dosyalarınızı okuyabilir/açıklayabilir.

---

## ⚡ Çözüm: Korunan Yüksek Hızlı Özerklik

### 1. 🛡️ Parçalı İzin Korumaları
`opencode.json`'de, hassas dosyalara (`.env` gibi) erişimi açıkça reddeden ve git ve grep işlemlerine otomatik olarak güvenli bir şekilde izin veren, önceden yapılandırılmış güvenli yönergeler. Sıfır güvenlik kaygısıyla yüksek hız.

### 🤖 2. 5 Modüler Yapay Zeka Rolleri
Doğrudan `.opencode/agents/`'da yapılandırılan 5 otonom aracıdan oluşan düzenli ve uzman bir ekip edinin:
- **`code`** — Kodu güvenli bir şekilde yazma ve düzenleme.
- **`research`** — Kod tabanı mimarisini araştırır ve eşler.
- **`debug`** & **`refactor`** — Teşhis, düzeltme ve optimizasyonu temizleme.
- **`document`** — Belgelerin kod kirliliği olmadan bakımı.

### 🌐 3. Yerleşik Eğik Çizgi Teşhisi
Proje yapısını haritalamak için `/analyze`, hataları taramak ve düzeltmek için `/fix` ve karmaşık dosyaları milisaniyeler içinde parçalamak için `/explain` gibi anında yürütme komutları.

---

## 📊 LITE ve PRO: Premium Yükseltmesi

`opencode-starter` temiz bir temel olacak şekilde tasarlanmıştır. Profesyonel monorepolar ve gelişmiş iş akışları için:

| Özellik | 🆓 LITE (Başlangıç) | 💎 PRO (Premium) |
|---|:---:|:---:|
| **Uzman Temsilciler** | 5 (Kod, Araştırma vb.) | 5 (Modüler Sistem) |
| **İş Akışı Becerileri** | 2 (`coding-conventions`, `testing`) | 15+ (Veritabanı, Operasyonlar, vb.) |
| **Çalışma Alanı Yapısı** | Basit | Durum-önce Monorepo (`active/`, vb.) |
| **Proje Ön Ayarları** | ❌ | 10 Ön Ayar (Sonraki, Laravel, Flutter, vb.) |
| **İşlemler ve Sunucu Senkronizasyonu** | ❌ | ✅ (Docker Compose ve Caddyfile'a hazır) |

👉 **[Karşılaştırma ve Yükseltme Kılavuzunun Tamamını Görüntüleyin](COMPARISON.md)**

---

## 📂 Depo Yapısı

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

## 🚀 Hızlı Başlangıç

### 1. Kopyalama ve Kurulum Ortamı
Proje ortamı değişkenleri şablonunuzu kopyalayın:

```bash
cp .env.example .env
```

`.env` dosyasını açın ve depo entegrasyonlarını etkinleştirmek için `GITHUB_TOKEN` kodunuzu ekleyin.

### 2. Temsilci İşbirliğine Başlayın
OpenCode AI Agent CLI'yi başlatın veya `opencode.json` yapılandırma dosyasını yapay zeka dostu düzenleyicinize yükleyin. Aşağıdaki yerleşik komutları kullanın:
- **Proje Analizi:** `/analyze`
- **Güvenlik Açıklarını Teşhis Etme ve Düzeltme:** `/fix`
- **Modülü Açıkla:** `/explain [filename]`

---

## 💖 Bu Projeyi Destekleyin (Bağışlar)

Bu başlangıç şablonu kodlama iş akışınızı hızlandırmaya yardımcı oluyorsa aşağıdaki bağlantılar aracılığıyla destek olmayı veya bağışta bulunmayı düşünün:
- **Ko-fi:** [ko-fi.com/andiupn](https://ko-fi.com/andiupn)
- **Patreon:** [patreon.com/AndiUpn](https://patreon.com/AndiUpn)
- **Trakteer:** [trakteer.id/andi_upn/gift](https://trakteer.id/andi_upn/gift)
- **Saweria:** [saweria.co/andiupn](https://saweria.co/andiupn)

---

## 📄 Lisans

Bu proje **MIT Lisansı** kapsamında lisanslanmıştır. Daha fazla bilgi için [LİSANS](LICENSE) dosyasına bakın.