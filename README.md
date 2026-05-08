<div align="center">

# Hi, I'm Abhishek 👋

### Full-stack WordPress architect • Enterprise & VIP-grade engineering • WordPress Core contributor

[![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)](https://wordpress.org/)
[![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](#)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](#)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](#)

[![Blog](https://img.shields.io/badge/Blog-confusedblogger.com-FF6B6B?style=flat-square&logo=hashnode&logoColor=white)](https://confusedblogger.com)
[![WordPress.org](https://img.shields.io/badge/WordPress.org-@abhishekfdd-21759B?style=flat-square&logo=wordpress&logoColor=white)](https://profiles.wordpress.org/abhishekfdd/)

</div>

---

> 🏛️ I architect and build WordPress platforms for **high-traffic, enterprise-grade sites** — handling tens of thousands of users, complex content models, SSO, and strict performance and security standards.
>
> With **14+ years** across PHP, JavaScript, and infrastructure, my work spans data modeling and platform architecture to Gutenberg/React on the front end — with a heavy focus on the **VIP platform** and managed enterprise hosting.

> [!TIP]
> I'm equally comfortable shipping a Core patch, designing a multi-CPT content model for a 20K-user portal, debugging a Firefox-specific Gutenberg issue, or wiring up a WireGuard relay for my homelab.

---

## 🎯 What I do

| | |
|---|---|
| 🏛️ **Architecture & technical leadership** | CPT, taxonomy & ACF Flexible Content models for document-heavy and editorial sites; plugin-vs-theme separation, data ownership, migration strategies, SSO provisioning |
| 🔐 **Enterprise & VIP engineering** | VIP coding standards, ACL filters, offloaded media transformations, develop→preprod→production workflows, Elasticsearch-backed search |
| 🧩 **WordPress Core contributor** | Active patches and proposals on Trac across media, exports, and admin UI |
| 🎨 **Gutenberg & block editor** | Custom blocks, dynamic blocks, editor patterns, accessibility, REST API integration |
| ⚙️ **Full-stack development** | PHP, JavaScript (React/ES6+), Node.js, REST APIs, build tooling, CI/CD |
| 🛡️ **Code review & standards** | VIP Code Analysis, PHPCS (WPCS), security hardening, performance audits, mentoring |
| 🤖 **AI-assisted development** | Claude Code, Antigravity, Codex; authoring `AGENTS.md` / `CLAUDE.md` specs for client projects |

---

## 💼 Selected work

<table>
<tr>
<td width="50%" valign="top">

### 🏛️ Enterprise vendor portal architecture

Led the migration architecture for a document-heavy portal serving **~20K users** on managed enterprise WordPress hosting.

- Three-CPT model with shared ACF Flexible Content fields
- Fresh SAML SSO provisioning
- Elasticsearch-backed search
- Clean plugin-owns-data / theme-owns-presentation separation
- Migration spec, dev task breakdown, and `AGENTS.md` for AI-assisted implementation

</td>
<td width="50%" valign="top">

### 🔐 Custom access control layer

Reviewed and refined an `Access_Control` class for media file restrictions.

- `auth_redirect()` integration
- Platform ACL filters
- Compliance with enterprise security standards

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎨 Block editor investigations

Debugged cross-browser Gutenberg rendering issues.

- Firefox-specific "Fit text" scaling in Media & Text
- Traced root causes back to upstream `fit-text-utils.js`
- Filed upstream issues and proposed fixes

</td>
<td width="50%" valign="top">

### 📊 Internal tooling & dashboards

Built single-file HTML/Chart.js dashboards for SSO-protected enterprise APIs.

- Node.js proxy servers for cookie-based SSO
- JIRA project dashboard with cascading filters
- Live KPI cards and charting

</td>
</tr>
</table>

---

## 🧩 Recent WordPress Core contributions

| Ticket | Summary |
|---|---|
| 🎫 [**#64556**](https://core.trac.wordpress.org/ticket/64556) | Fix for undefined index in category parent slug lookup during filtered exports (`export.php`) |
| 🎫 [**#64842**](https://core.trac.wordpress.org/ticket/64842) | MP3 upload failures with non-ASCII ID3 tags — UTF-8 conversion in `media.php` |
| 🎫 [**#64709**](https://core.trac.wordpress.org/ticket/64709) | Investigation of a Firefox-specific "Fit text" scaling bug in the Media & Text block |
| 🎫 [**#36882**](https://core.trac.wordpress.org/ticket/36882) | CSS proposal for a unified `.wp-delete-link` utility class in `common.css` |

📋 Full activity → [profiles.wordpress.org/abhishekfdd](https://profiles.wordpress.org/abhishekfdd/)

---

## 🤖 AI-assisted development & agent workflows

> AI coding agents are a serious part of my toolchain — not autocomplete, but collaborators that need clear specs, guardrails, and context to be productive on real projects.

<details open>
<summary><b>Click to expand</b></summary>

<br>

| | |
|---|---|
| 🤝 **Coding agents I use daily** | Claude Code (terminal-first, hooks-driven) · Antigravity (multi-agent IDE) · ChatGPT Codex (async cloud PRs) |
| 📝 **Agent configuration** | Authoring `AGENTS.md` and `CLAUDE.md` specs that encode project architecture, coding standards, forbidden actions, and recipes |
| 🦞 **Personal AI ops agent** | [OpenClaw](https://openclaw.ai) backed by **Gemma 4 31B** locally — 24/7 system monitoring with self-healing, doc organization, reminders, scheduled tasks, all via chat apps |
| 🏠 **Home automation** | Home Assistant integrated with OpenClaw for natural-language control, automated routines, AI-driven scenes |
| 🔄 **Workflow design** | AI agents + traditional CI/CD + code review + PHPCS — velocity up, quality intact |

</details>

---

## 🏠 DevOps & homelab

> Outside of WordPress work, I run a fairly serious homelab — partly because self-hosting is fun, and partly because **understanding what happens below the application layer makes me a better architect** on the job.

<table>
<tr>
<td width="50%" valign="top">

### 🌐 Network
TP-Link Omada stack — ER7206 gateway, EAP670 APs, SG3210XHP-M2 PoE switch, Omada Software Controller on Raspberry Pi 5; VLAN segmentation, guest/IoT isolation, DNS-level filtering

### 🖥️ Virtualization & compute
Proxmox VE host running mixed Linux VMs and LXC containers; Raspberry Pi 5 for always-on services

### 🔒 Remote access & VPN
Self-hosted WireGuard relay on Oracle Cloud Free Tier (built to bypass dual-CGNAT), Tailscale mesh as primary path; site-to-site routing across VLANs

### 📦 Self-hosted services
Reverse proxies, internal DNS, monitoring, automated backups, container orchestration with Docker Compose

</td>
<td width="50%" valign="top">

### 🦞 Local AI & agentic ops
Gemma 4 31B running locally as the brain for OpenClaw — autonomous 24/7 assistant handling service restarts, network log debugging, doc organization, and Home Assistant automations from any chat app

### 🏡 Home automation
Home Assistant for whole-home control, with OpenClaw as the natural-language layer — voice/chat-driven scenes, sensor-triggered routines, AI-decided automations

### ⚡ Automation
Shell scripting, scheduled jobs, infrastructure-as-code experiments, Git-driven config management

</td>
</tr>
</table>

---

## 🛠️ Tech I work with

<details>
<summary><b>Backend</b></summary>

![PHP](https://img.shields.io/badge/PHP_8+-777BB4?style=flat-square&logo=php&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress_Core-21759B?style=flat-square&logo=wordpress&logoColor=white)
![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=flat-square&logo=woocommerce&logoColor=white)
![BuddyPress](https://img.shields.io/badge/BuddyPress-D84800?style=flat-square&logo=wordpress&logoColor=white)
![ACF](https://img.shields.io/badge/ACF_Pro-00D3AE?style=flat-square)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-009688?style=flat-square)

</details>

<details>
<summary><b>Frontend</b></summary>

![JavaScript](https://img.shields.io/badge/JavaScript_ES6+-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Gutenberg](https://img.shields.io/badge/Gutenberg-21759B?style=flat-square&logo=wordpress&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS/SCSS-1572B6?style=flat-square&logo=css3&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack/Vite-8DD6F9?style=flat-square&logo=webpack&logoColor=black)

</details>

<details>
<summary><b>DevOps & infrastructure</b></summary>

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=flat-square&logo=proxmox&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</details>

<details>
<summary><b>CI/CD & quality</b></summary>

![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![PHPCS](https://img.shields.io/badge/PHPCS_WPCS-777BB4?style=flat-square&logo=php&logoColor=white)
![PHPStan](https://img.shields.io/badge/PHPStan-1A6BAE?style=flat-square)
![PHPUnit](https://img.shields.io/badge/PHPUnit-3776AB?style=flat-square)
![ESLint](https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white)
![Lighthouse](https://img.shields.io/badge/Lighthouse-F44B21?style=flat-square&logo=lighthouse&logoColor=white)

</details>

<details>
<summary><b>Platforms & AI</b></summary>

**Platforms:** Managed enterprise WordPress hosting, multisite, headless WordPress, Oracle Cloud, Raspberry Pi

**AI & agents:** Claude Code, Antigravity, ChatGPT Codex, OpenAI/Anthropic APIs, Gemma 4 (local), OpenClaw, `AGENTS.md` / `CLAUDE.md` specs

**Other:** Node.js, Composer, npm/pnpm, SAML/OAuth/SSO, Home Assistant, Chart.js, REST/JSON APIs

</details>

---

## 📊 GitHub stats

<div align="center">

![Trophies](https://github-profile-trophy.vercel.app/?username=abhishekfdd&theme=tokyonight&no-frame=true&column=7)
![Streak](https://streak-stats.demolab.com?user=abhishekfdd&theme=tokyonight&hide_border=true)

</div>

---

## ✍️ Writing

I write about WordPress internals, PHP, architecture decisions, AI workflows, and homelab/networking on my blog.

🔗 **[confusedblogger.com](https://confusedblogger.com)**

---

## 🤝 Let's connect

<div align="center">

[![Blog](https://img.shields.io/badge/Blog-confusedblogger.com-FF6B6B?style=for-the-badge&logo=hashnode&logoColor=white)](https://confusedblogger.com)
[![WordPress.org](https://img.shields.io/badge/WordPress.org-@abhishekfdd-21759B?style=for-the-badge&logo=wordpress&logoColor=white)](https://profiles.wordpress.org/abhishekfdd/)
[![GitHub](https://img.shields.io/badge/GitHub-@abhishekfdd-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/abhishekfdd)

</div>
