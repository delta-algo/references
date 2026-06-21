# 📚 References — delta-algo

Koleksi referensi proyek yang pernah digunakan: tools, AI, framework, database, dan resources.

> Dikelola oleh EllaClaw 🦀 — 21 Juni 2026

---

## 🧠 AI & Coding Agents

| Repo | Deskripsi | Status |
|:-----|:----------|:-------|
| [affaan-m/ECC](https://github.com/affaan-m/ECC) | Everything Claude Code — 216K stars, 262 skills, MIT | ✅ ECC-Adapted ke OpenClaw |
| [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) | 345 Claude Code skills + plugins — support 13 tools | ✅ **Terinstall** (9 skill) |
| [qwibitai/nanoclaw](https://github.com/qwibitai/nanoclaw) | NanoClaw — personal AI assistant (Raspberry Pi) | ✅ Diriset |
| [VivianBalakrishnan](https://gist.github.com/VivianBalakrishnan/a7d4eec3833baee4971a0ee54b08f322) | NanoClaw config gist — Menteri Luar Negeri Singapore | ✅ Diriset |

### 🔧 AI Tools

| Tool | Untuk | Status |
|:-----|:------|:-------|
| **OpenClaw** | Self-hosted AI gateway | 🦀 **Sistem utama** |
| **Blackbox AI** | Chat API + Agent API (GPT, Claude, DeepSeek) | ✅ **Terintegrasi** |
| **Graphify** (pip: graphifyy) | Knowledge graph codebase — hemat token 30× | ✅ **Terinstall VPS** |

---

## 💻 Aplikasi & Framework

| Repo | Deskripsi | Status |
|:-----|:----------|:-------|
| [delta-algo/Aplikasi_PDFMaps](https://github.com/delta-algo/Aplikasi_PDFMaps) | Aplikasi Flutter — PDF Maps, GPS, Export KML | 🎯 **Proyek utama** |
| [delta-algo/delta-workspace](https://github.com/delta-algo/delta-workspace) | Workspace lama — backup pre-EllaClaw | ✅ Arsip |
| [delta-algo/design-references](https://github.com/delta-algo/design-references) | Koleksi DESIGN.md referensi UI/UX | ✅ Public |

### 📱 Mobile

| Tool | Untuk |
|:-----|:------|
| **Flutter 3.44.2** | Framework Aplikasi_PDFMaps |
| **Dart** | Bahasa pemrograman |
| **sqflite** | Database lokal SQLite |
| **pdfx** | Render PDF |
| **geolocator** | GPS location |

---

## 🗄️ Database & Storage

| Tool | Untuk | Status |
|:-----|:------|:-------|
| **PostgreSQL** (VPS 43.134.83.36) | Database utama | ✅ **delta_db** |
| **PostGIS 3.4.2** | Data spasial, koordinat, peta | ✅ Active |
| **pgvector 0.6.0** | Vector search untuk AI | ✅ Active |
| **Supabase** | Database cloud untuk webapp | 🔜 Menunggu |
| **MySQL / MariaDB** | Alternatif database gratis | 🔜 Rencana |

---

## ☁️ Infrastruktur

### VPS Delta (43.134.83.36)

| Service | Port | Status |
|:--------|:-----|:-------|
| **Ubuntu 24.04** | — | ✅ |
| **OpenClaw Gateway** | 18789 (loopback) | ✅ |
| **Nginx** | 80/443 | ✅ |
| **UFW** | 22,80,443 | ✅ |
| **Playwright/Chromium** | 18800 | ✅ |
| **faster-whisper** (STT) | 8200 | ✅ |
| **Ollama** (nomic-embed-text) | — | ✅ |
| **PM2** | — | ✅ |
| **Cloudflare Tunnel** | — | ✅ |
| **Grafana** | 3000 (lokal) | ✅ |

### VPS Windows (43.163.95.154)

| Service | Status |
|:--------|:-------|
| **Nuclei v3.8.0** | Bug bounty scanning |
| **WinRM** (5985) | Remote |

---

## 🛠️ Tools & CLI

| Tool | Versi | Fungsi |
|:-----|:------|:-------|
| **Blackbox CLI** | v1.2.84 | AI coding di terminal |
| **Supabase CLI** | v2.20.0 | Database cloud management |
| **GitHub CLI (gh)** | latest | GitHub management |
| **GOG** | latest | Google Workspace (Gmail, Calendar, Drive) |
| **Graphify** | v0.8.44 | Knowledge graph codebase |

---

## ☁️ Cloud & Services

| Service | Akun | Status |
|:--------|:-----|:-------|
| **Blackbox AI** (PRO PLUS) | $20/bln — sisa $17.36 credit | ✅ Active |
| **GitHub** | delta-algo | ✅ Connected |
| **Google Cloud** (DeltaOpenClaw) | Production OAuth | ✅ Permanent |
| **Supabase** | — | 🔜 Menunggu |
| **Cloudflare** | Tunnel + DNS | ✅ Active |

---

## 🔬 Riset & Referensi

| Topik | Sumber | Catatan |
|:------|:-------|:--------|
| **Air-gen** (listrik dari udara) | UMass Amherst — Nature 2020, Advanced Materials 2023 | Riset nyata, masih R&D |
| **CVE-2026-25253** | OpenClaw CSWS Hijacking (CVSS 8.8) | ✅ Patched di v2026.1.29 |
| **ECC** (Everything Claude Code) | github.com/affaan-m/ECC | 216K stars, adapted ke OpenClaw |
| **NanoClaw** | Vivian Balakrishnan — Singapore FM | AI second brain diplomat |

---

## 📊 Trading

| Resource | Fungsi |
|:---------|:-------|
| trade-logs/ | Log trading harian (memory/trade-logs/) |
| pantau-trade/ | Data pantau trading (memory/pantau-trade/) |
| clawflows-reference.md | Referensi clawflows trading |

---

## 📦 Skills Terinstall (di OpenClaw)

### ECC-Adapted (6 skills)
- `trading-skills.md` — Workflow trading
- `aplikasi-skills.md` — Workflow coding
- `admin-skills.md` — Workflow admin
- `security-skills.md` — Cek data sensitif
- `continuous-learning.md` — Catat pola error & sukses
- `blackbox-api-workflow.md` — Chat API vs Agent API

### claude-skills (9 skills — dari alirezarezvani/claude-skills)
- `senior-architect/` — Framework desain sistem
- `financial-analyst/` — Analisa keuangan, RAB, termin
- `process-mapper/` — Dokumentasi & optimasi proses
- `database-designer/` — Desain schema MySQL/Supabase
- `code-reviewer/` — Review kode Dart/Flutter
- `api-design-reviewer/` — Review desain REST API
- `litreview/` — Framework riset informasi
- `saas-metrics-coach/` — Analisa metrik bisnis SaaS
- `capture/` — Organisasi ide & brain dump

### Lainnya
- `.graphify/` — Knowledge graph Aplikasi_PDFMaps (1.017 nodes)

---

> **Last updated:** 21 Juni 2026  
> **Maintained by:** EllaClaw 🦀  
> **License:** MIT
