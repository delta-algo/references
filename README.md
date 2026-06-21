# 📚 References — delta-algo

Koleksi referensi proyek yang pernah digunakan: tools, AI, framework, database, dan resources.

> Dikelola oleh EllaClaw 🦀 — 21 Juni 2026

---

## 🧠 AI & Coding Agents

| Repo | Stars | Deskripsi | Status |
|:-----|:-----:|:----------|:-------|
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | ⭐ | OpenClaw Gateway — self-hosted AI assistant | 🦀 **Sistem utama** |
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | 216K+ | Everything Claude Code — 262 skills, MIT | ✅ ECC-Adapted |
| [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) | 5.2K+ | 345+ Claude Code skills — support 13 tools | ✅ **9 skill terinstall** |
| [qwibitai/nanoclaw](https://github.com/qwibitai/nanoclaw) | — | NanoClaw — personal AI assistant (alternative to OpenClaw) | ✅ Diriset |
| [VivianBalakrishnan](https://gist.github.com/VivianBalakrishnan/a7d4eec3833baee4971a0ee54b08f322) | — | NanoClaw gist — Menteri Luar Negeri Singapore | ✅ Diriset |
| [nikilster/clawflows](https://github.com/nikilster/clawflows) | — | 113+ prebuilt workflows untuk OpenClaw | ✅ Diriset (April) |

### 🔧 AI Tools

| Tool | Situs | Untuk | Status |
|:-----|:------|:------|:-------|
| **Blackbox AI** | [api.blackbox.ai](https://api.blackbox.ai) | Chat API + Agent API (GPT, Claude, DeepSeek) | ✅ **Terintegrasi** |
| **Graphify** | [graphify.net](https://graphify.net/) | Knowledge graph — hemat token 30× | ✅ **Terinstall VPS** |
| **NanoClaw** | [nanoclaw.dev](https://nanoclaw.dev) | Alternative lightweight OpenClaw | ✅ Diriset |

---

## 💻 Aplikasi & Framework

### Proyek Kita

| Repo | Visibility | Deskripsi | Status |
|:-----|:-----------|:----------|:-------|
| [delta-algo/Aplikasi_PDFMaps](https://github.com/delta-algo/Aplikasi_PDFMaps) | 🔒 Private | Flutter — PDF Maps, GPS, Export KML/GPX | 🎯 **Proyek utama** |
| [delta-algo/delta-workspace](https://github.com/delta-algo/delta-workspace) | 🔒 Private | Workspace lama — backup pre-EllaClaw (Mei 2026) | ✅ Arsip |
| [delta-algo/design-references](https://github.com/delta-algo/design-references) | 🌍 Public | Koleksi DESIGN.md referensi UI/UX | ✅ Public |
| [delta-algo/references](https://github.com/delta-algo/references) | 🌍 Public | **Repo ini** — koleksi referensi semua proyek | 🟢 Active |

### 🔧 Framework & Tools

| Tool | Versi | Untuk |
|:-----|:------|:------|
| **Flutter** | 3.44.2 | Framework Aplikasi_PDFMaps |
| **Dart** | — | Bahasa pemrograman |
| **React Native** | — | Framework alternatif (dibandingkan dengan Flutter) |
| **sqflite** | — | Database lokal SQLite di Flutter |
| **pdfx** | — | Render PDF |
| **geolocator** | — | GPS location |
| **webview_flutter** | — | WebView (CalTopo integration) |
| **image_picker** | — | Geotagged photos (Placemark) |

---

## 🗄️ Database & Storage

| Tool | Untuk | Status |
|:-----|:------|:-------|
| **PostgreSQL** (VPS 43.134.83.36) | Database utama — `delta_db` | ✅ Active |
| **PostGIS 3.4.2** | Data spasial, koordinat, area peta | ✅ Active |
| **pgvector 0.6.0** | Vector search untuk AI embeddings | ✅ Active |
| **Supabase** | Database cloud untuk webapp | 🔜 Menunggu |
| **MySQL / MariaDB** | Alternatif database gratis — self-host VPS | 🟢 Rencana |
| **SQLite** | Database lokal Aplikasi_PDFMaps (via sqflite) | ✅ Active |

---

## ☁️ Infrastruktur

### VPS Delta (43.134.83.36) — Ubuntu 24.04

| Service | Port | Status |
|:--------|:-----|:-------|
| **OpenClaw Gateway** | 18789 (loopback) | ✅ systemd |
| **Nginx** | 80/443 | ✅ SSL active |
| **UFW** | 22,80,443 | ✅ Active |
| **Playwright / Chromium** | 18800 | ✅ v148 |
| **faster-whisper (STT)** | 8200 | ✅ PM2 |
| **Ollama** | — | ✅ moondream, nomic-embed-text |
| **PM2** | — | ✅ AionUi, STT server |
| **Grafana** | 3000 (lokal) | ✅ |
| **AionUi** | 25808 (localhost) | ✅ PM2 |
| **Cloudflare Tunnel** | — | ✅ infra-agri.site |
| **GOG** (Gmail, Calendar, Drive) | — | ✅ Permanent OAuth |

### VPS Windows (43.163.95.154)

| Service | Status |
|:--------|:-------|
| **Nuclei v3.8.0** | Bug bounty scanning |
| **WinRM (5985)** | Remote access |

---

## 🛠️ Tools & CLI

| Tool | Versi | Fungsi |
|:-----|:------|:-------|
| **GitHub CLI (gh)** | latest | GitHub management — delta-algo |
| **Blackbox CLI** | v1.2.84 | AI coding via terminal |
| **Graphify** (pip: graphifyy) | v0.8.44 | Knowledge graph codebase |
| **Supabase CLI** | v2.20.0 | Database cloud management |
| **GOG** | latest | Google Workspace integration |
| **Ollama** | 0.30.8 | Local LLM (Hermes 3, nomic-embed-text) |

---

## ☁️ Cloud & Services

| Service | Akun | Status |
|:--------|:-----|:-------|
| **Blackbox AI** (PRO PLUS) | $20/bln — sisa $17.36 credit | ✅ Active |
| **GitHub** | delta-algo | ✅ Connected |
| **Google Cloud** (DeltaOpenClaw) | Production OAuth — tidak expire | ✅ Permanent |
| **Supabase** | — | 🔜 Menunggu Project URL + Key |
| **Cloudflare** | Tunnel + DNS — infra-agri.site | ✅ Active |

---

## 🔬 Riset & Referensi Akademik

| Topik | Sumber | Status |
|:------|:-------|:-------|
| **Air-gen** (listrik dari udara) | UMass Amherst — Nature 2020, Advanced Materials 2023 | Riset nyata, masih R&D |
| **CVE-2026-25253** | OpenClaw Cross-Site WebSocket Hijacking (CVSS 8.8) | ✅ Patched |
| **ECC** (Everything Claude Code) | github.com/affaan-m/ECC — 216K stars | ✅ Adapted |
| **NanoClaw** | Vivian Balakrishnan — Singapore Foreign Minister | ✅ Diriset |
| **Graphify** | graphify.net — knowledge graph tool | ✅ Terintegrasi |
| **Gemini** | gemini.google.com | ✅ Cookie-based access |

---

## 📊 Trading

| Resource | Lokasi | Fungsi |
|:---------|:-------|:-------|
| trade-logs/ | `memory/trade-logs/` | Log trading harian |
| pantau-trade/ | `memory/pantau-trade/` | Data pantau trading |
| clawflows-reference.md | `memory/clawflows-reference.md` | Referensi clawflows trading |

---

## 📦 Skills Terinstall (di OpenClaw)

### ECC-Adapted (6 skills — dari affaan-m/ECC pattern)
| Skill | Fungsi |
|:------|:-------|
| `trading-skills.md` | Workflow trading |
| `aplikasi-skills.md` | Workflow coding |
| `admin-skills.md` | Workflow admin |
| `security-skills.md` | Cek data sensitif |
| `continuous-learning.md` | Catat pola error & sukses |
| `blackbox-api-workflow.md` | Chat API vs Agent API |

### claude-skills (9 skills — dari alirezarezvani/claude-skills)
| Skill | Fungsi |
|:------|:-------|
| `senior-architect/` | Framework desain sistem & arsitektur |
| `financial-analyst/` | Analisa keuangan, RAB, termin proyek |
| `process-mapper/` | Dokumentasi & optimasi proses bisnis |
| `database-designer/` | Desain schema MySQL/Supabase |
| `code-reviewer/` | Review kode Dart/Flutter |
| `api-design-reviewer/` | Review desain REST API |
| `litreview/` | Framework riset informasi |
| `saas-metrics-coach/` | Analisa metrik bisnis SaaS |
| `capture/` | Organisasi ide & brain dump ke action |

### Lainnya
| Skill | Fungsi |
|:------|:-------|
| `.graphify/` | Knowledge graph Aplikasi_PDFMaps (1.017 nodes, 1.344 edges) |

---

## 🗺️ Semua Repo yang Pernah Dikunjungi

```
📦 github.com/openclaw/openclaw              → Sistem utama
📦 github.com/affaan-m/ECC                   → 262 skills (ECC-Adapted)
📦 github.com/alirezarezvani/claude-skills   → 345+ skills (9 terinstall)
📦 github.com/qwibitai/nanoclaw              → NanoClaw AI
📦 github.com/nikilster/clawflows            → 113+ OpenClaw workflows
📦 github.com/VivianBalakrishnan             → Gist NanoClaw config
📦 github.com/delta-algo/Aplikasi_PDFMaps    → Proyek utama
📦 github.com/delta-algo/delta-workspace     → Old workspace backup
📦 github.com/delta-algo/design-references   → UI/UX referensi publik
📦 github.com/delta-algo/references          → REPO INI
🌐 graphify.net                              → Knowledge graph tool
🌐 nanoclaw.dev                              → NanoClaw official
🌐 api.blackbox.ai                           → Blackbox AI endpoint
🌐 gemini.google.com                         → Gemini AI
```

---

> **Last updated:** 21 Juni 2026  
> **Maintained by:** EllaClaw 🦀  
> **Note:** Kalau ada repo baru yang dikunjungi, langsung ditambahkan ke sini.
