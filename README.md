<h1 align="center">Azhar Ali</h1>

<p align="center">
  <b>Full-stack web developer, specialised in WordPress</b><br>
  Multan, Pakistan &nbsp;·&nbsp; UTC+5 &nbsp;·&nbsp; I run SoftGlaze, a small studio
</p>

<p align="center">
  <a href="https://profiles.wordpress.org/softglaze/">
    <img src="https://img.shields.io/badge/WordPress.org-softglaze-21759B?style=for-the-badge&logo=wordpress&logoColor=white" alt="WordPress.org profile">
  </a>
  <a href="https://softglaze.com">
    <img src="https://img.shields.io/badge/Website-softglaze.com-0F172A?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website">
  </a>
  <a href="https://www.linkedin.com/in/azharalidev/">
    <img src="https://img.shields.io/badge/LinkedIn-azharalidev-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:azhar@softglaze.com">
    <img src="https://img.shields.io/badge/Email-azhar%40softglaze.com-C9922B?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email">
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/WordPress_Core-6_committed_credits-21759B?style=flat-square" alt="6 core credits">
  <img src="https://img.shields.io/badge/Directory-3_plugins_live-blue?style=flat-square" alt="3 plugins live">
  <img src="https://img.shields.io/badge/Patterns-2_published-7F54B3?style=flat-square" alt="2 patterns published">
  <img src="https://img.shields.io/badge/Experience-7_years-success?style=flat-square" alt="7 years">
  <img src="https://img.shields.io/badge/Open_to-full--time_remote-C9922B?style=flat-square" alt="Open to full-time remote roles">
</p>

---

### About

I run **SoftGlaze** from Multan, Pakistan. A small studio: I do the development myself, and bring in specialists I've worked with for years when a project needs them.

Seven years building websites and web applications. **150+ projects** — 60+ WordPress sites, 20+ WooCommerce and Shopify stores, and custom applications in Laravel, PHP and React. Mostly small businesses in the UK, Europe and Pakistan.

**What I do:** WordPress development · custom plugin development · WooCommerce · Shopify · speed optimisation · site rescues · monthly maintenance

🔎 **I'm open to full-time remote developer roles.** [azhar@softglaze.com](mailto:azhar@softglaze.com)

---

### WordPress core

I contribute to WordPress core: patch testing, bug reproduction, tracing regressions back to the changeset that caused them, and writing the fix when I find one.

**Six committed credits in the 7.1 cycle:**

| Changeset | Component | What I did |
| :--- | :--- | :--- |
| [**[62854]**](https://core.trac.wordpress.org/changeset/62854) | Filesystem API | Verified the permissions comparison in `WP_Filesystem_Direct::chmod()`, then wrote the **PHPUnit regression test that shipped with the fix** at the committer's request. |
| [**[62865]**](https://core.trac.wordpress.org/changeset/62865) | Login &amp; Registration | First trunk test of the focus-colour fix. |
| [**[62967]**](https://core.trac.wordpress.org/changeset/62967) | Users | First tester on the show/hide password button alignment fix. |
| [**[62968]**](https://core.trac.wordpress.org/changeset/62968) | Widgets | First tester of the patch. The feature was later bumped to 7.2; the changeset and credit stand. |
| [**[62976]**](https://core.trac.wordpress.org/changeset/62976) | Media | Posted the root cause and traced the regression to `[61757]` before any patch existed, then wrote the only test report on the PR. |
| [**[63007]**](https://core.trac.wordpress.org/changeset/63007) | Media | Separated *registered* from *built* from *served* to show a stylesheet handle existed on disk but was never registered. |

> These are credits for **testing and verifying other people's patches**, plus one regression test I authored. Not six bugs I fixed. The distinction matters.

**One I found, reported and patched myself:**

[**#65802**](https://core.trac.wordpress.org/ticket/65802) — `wp_show_heic_upload_error()` had been assigning to an undeclared variable since 2024, so the flag it existed to set was never applied and both of its hooks silently did nothing. Unreported for roughly two years.

I ran a control that proved the branch could not execute on my install, forced the condition with an mu-plugin, then called the function directly to capture the real return value instead of inferring it. Filed the ticket citing the introducing changeset, then opened [**PR #12830**](https://github.com/WordPress/wordpress-develop/pull/12830) with the one-line fix and **two unit tests with red-green proof**.

A core committer took ownership and milestoned it for **7.2**, closing the competing PR in favour of mine.

**Also on the public record:**

- [**#64921**](https://core.trac.wordpress.org/ticket/64921) — a REST API failure nobody had reproduced in four months. Built an mu-plugin simulation, confirmed a hard 400, showed the proposed patch didn't fix it, and attached two test-only patches. Another tester later used the same technique and credited it.
- [**#63256**](https://core.trac.wordpress.org/ticket/63256) — behaviour matrix across trunk and two competing PRs. A later reviewer cited it twice as the deciding evidence for one of them.
- Eight full test reports across seven tickets, most as first or only tester.
- **1,000+ Urdu strings** translated, and Project Translation Editor for my own plugins.

Always with evidence — DevTools traces, before/after screenshots, PHPUnit runs. Never *"works for me."*

Full activity → [profiles.wordpress.org/softglaze](https://profiles.wordpress.org/softglaze/)

---

### Shipped

| Project | What it is | Status |
| :--- | :--- | :--- |
| [**PDF Invoices for WooCommerce**](https://wordpress.org/plugins/softglaze-pdf-invoices/) | ~7,800 lines. Invoices, credit notes, packing slips, partial payments, deposits, client e-signature | 🟢 Live on WordPress.org |
| [**Maintenance Mode &amp; Coming Soon**](https://wordpress.org/plugins/softglaze-maintenance-mode-coming-soon/) | Three modes, ten templates, scheduled switching, access control | 🟢 Live on WordPress.org |
| [**Click to Chat**](https://wordpress.org/plugins/softglaze-click-to-chat/) | Floating chat, multiple agents, working-hour schedules, custom REST namespace, GDPR export and erase | 🟢 Live on WordPress.org |
| [**3-Step Process Card Grid**](https://wordpress.org/patterns/pattern/3-step-process-card-grid/) · [**Shipping, Returns, Payment**](https://wordpress.org/patterns/pattern/shipping-returns-payment/) | Two block patterns, built standalone against core defaults so they render in any theme | 🟢 Live on the Pattern Directory |
| [**Warqa**](https://github.com/softglazee/warqa-wordpress-theme) | Block theme. `theme.json` v3, nine templates, 45 patterns, dark variation, bundled fonts. Passed Theme Check across 16,091 tests with zero required and zero warnings | 🕐 Submitted for review |
| [**SoftGlaze Browser**](https://github.com/softglazee/softglaze-browser) | Electron + React local browser-profile manager with proxy pool | 🟢 Open source |
| **SoftGlaze Screen Recorder** | Chrome MV3 extension | 🟢 On the Web Store |

> **Every premium feature in my plugins is free.** No locked buttons, no dashboard ads, no upgrade nags.

---

### Stack

![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=flat-square&logo=woocommerce&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Shopify](https://img.shields.io/badge/Shopify-7AB55C?style=flat-square&logo=shopify&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PHPUnit](https://img.shields.io/badge/PHPUnit-366488?style=flat-square&logo=php&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

### Get in touch

Open to **full-time remote developer roles**. Also taking WordPress and WooCommerce project work.

<p align="left">
  <a href="mailto:azhar@softglaze.com">✉️ azhar@softglaze.com</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/azharalidev/">💼 linkedin.com/in/azharalidev</a> &nbsp;·&nbsp;
  <a href="https://softglaze.com">🌐 softglaze.com</a>
</p>

<p align="left">
  <a href="https://profiles.wordpress.org/softglaze/"><img src="https://img.shields.io/badge/-WordPress.org-21759B?style=flat-square&logo=wordpress&logoColor=white" alt="WordPress.org"></a>
  <a href="https://www.linkedin.com/in/azharalidev/"><img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://x.com/mysoftglaze"><img src="https://img.shields.io/badge/-X-000000?style=flat-square&logo=x&logoColor=white" alt="X"></a>
  <a href="https://www.youtube.com/@softglaze"><img src="https://img.shields.io/badge/-YouTube-FF0000?style=flat-square&logo=youtube&logoColor=white" alt="YouTube"></a>
</p>

<sub><code>@softglaze</code> on WordPress.org, Trac and Slack &nbsp;·&nbsp; <code>@softglazee</code> here</sub>
