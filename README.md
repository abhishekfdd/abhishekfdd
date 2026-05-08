# Hi, I'm Abhishek 👋

**Full-stack WordPress architect • Enterprise & VIP-grade engineering • WordPress Core contributor**

I architect and build WordPress platforms for high-traffic, enterprise-grade sites — the kind that need to handle tens of thousands of users, complex content models, SSO, and strict performance and security standards. My work spans the full stack: from infrastructure-aware backend architecture to Gutenberg/React on the front end, with a heavy focus on the VIP platform and managed enterprise hosting.

---

## What I do

- 🏛️ **Architecture & technical leadership** — Designing CPT, taxonomy, and ACF Flexible Content models for document-heavy and editorial sites; defining plugin-vs-theme separation, data ownership, and migration strategies
- 🔐 **Enterprise & VIP engineering** — Working within VIP coding standards, ACL filters, offloaded media transformations, develop→preprod→production workflows, and SSO-based user provisioning
- 🧩 **WordPress Core contributor** — Active patches and proposals on Trac across media, exports, and admin UI
- 🎨 **Gutenberg & block editor** — Custom blocks, editor patterns, accessibility, and REST API integration
- ⚙️ **Full-stack development** — PHP, JavaScript (React/ES6+), Node.js, REST APIs, build tooling, and CI/CD
- 🛡️ **Code review & standards** — VIP Code Analysis, PHPCS (WPCS), security hardening, performance audits

---

## Selected work

**Enterprise vendor portal architecture** — Led the migration architecture for a document-heavy portal serving ~20K users on managed enterprise WordPress hosting. Designed a three-CPT model with shared ACF Flexible Content fields, fresh SSO provisioning, and a clean plugin-owns-data / theme-owns-presentation separation.

**Custom access control layer** — Reviewed and refined an `Access_Control` class for media file restrictions using `auth_redirect()` and platform ACL filters, ensuring compliance with enterprise security standards.

**Block editor investigations** — Debugged cross-browser Gutenberg rendering issues (e.g., Firefox-specific "Fit text" scaling in Media & Text), tracing root causes back to upstream `fit-text-utils.js` behavior.

**Internal tooling & dashboards** — Built single-file HTML/Chart.js dashboards backed by Node.js proxy servers for SSO-protected enterprise APIs.

---

## Recent WordPress Core contributions

| Ticket | Summary |
|--------|---------|
| [#64556](https://core.trac.wordpress.org/ticket/64556) | Fix for undefined index in category parent slug lookup during filtered exports (`export.php`) |
| [#64842](https://core.trac.wordpress.org/ticket/64842) | MP3 upload failures with non-ASCII ID3 tags — UTF-8 conversion in `media.php` |
| [#64709](https://core.trac.wordpress.org/ticket/64709) | Investigation of a Firefox-specific "Fit text" scaling bug in the Media & Text block |
| [#36882](https://core.trac.wordpress.org/ticket/36882) | CSS proposal for a unified `.wp-delete-link` utility class in `common.css` |

Full activity: [profiles.wordpress.org/abhishekfdd](https://profiles.wordpress.org/abhishekfdd/)

---

## Tech I work with

**Backend:** PHP, WordPress Core, WooCommerce, BuddyPress, ACF, REST API, MySQL
**Frontend:** JavaScript (ES6+), React, Gutenberg, HTML5, CSS/SCSS
**Platform & DevOps:** Managed enterprise WordPress hosting, multisite, Git, Composer, npm, CI/CD
**Standards & QA:** VIP Coding Standards, PHPCS (WPCS), PHPUnit, security & performance auditing
**Other:** Node.js, headless WordPress, SSO/OAuth integrations

---

## Writing

I write about WordPress internals, PHP, architecture decisions, and developer workflow on my blog:
🔗 **[confusedblogger.com](https://confusedblogger.com)**

---

## Let's connect

- 🌐 Blog — [confusedblogger.com](https://confusedblogger.com)
- Ⓦ WordPress.org — [@abhishekfdd](https://profiles.wordpress.org/abhishekfdd/)
