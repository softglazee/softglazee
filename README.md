<!--
  softglazee/softglazee/README.md

  SETUP
  1. Create an  assets  folder in this repo.
  2. Put header.svg and footer.svg in it.
  3. Commit.

  The two bars load from relative paths, so they come from your own repo.
  Nothing decorative depends on an outside service that can be blocked or
  rate limited. Only img.shields.io is external, and that one renders for you.

  Tailwind, CSS glassmorphism and CSS animation cannot work in a README:
  GitHub strips <style>, class attributes and JavaScript from markdown. The
  blur, the glass panels and the animation all live inside the SVG files,
  which GitHub does render.
-->

<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Hi, I'm Azhar Ali. WordPress developer in Multan, Pakistan." />
</p>

<p align="center">
  <a href="https://profiles.wordpress.org/softglaze/"><img src="https://img.shields.io/badge/wordpress.org-softglaze-21759B?style=for-the-badge&logo=wordpress&logoColor=white&labelColor=081A2F" alt="WordPress.org" /></a>
  <a href="https://softglaze.com"><img src="https://img.shields.io/badge/softglaze.com-C9922B?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=081A2F" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/azharalidev/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=081A2F" alt="LinkedIn" /></a>
  <a href="https://www.youtube.com/@softglaze"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white&labelColor=081A2F" alt="YouTube" /></a>
  <a href="https://x.com/mysoftglaze"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white&labelColor=081A2F" alt="X" /></a>
  <a href="mailto:azhar@softglaze.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=081A2F" alt="Email" /></a>
</p>

## About

I run SoftGlaze as a small studio. I do the development myself and bring in specialists I have worked with for years when a job needs them. Seven years of client work, mostly WordPress, for small businesses in the UK, Europe and Pakistan.

```php
<?php
$azhar = [
    'work'    => 'Plugins, block themes, WooCommerce',
    'core'    => 'Testing patches since the 7.1 cycle',
    'teams'   => ['Core', 'Test', 'Themes', 'Meta', 'Polyglots'],
    'writes'  => 'Test reports with DevTools traces and PHPUnit output',
    'open_to' => 'Full-time remote developer roles',
];
```

Translation editor for Urdu, with 1,040 strings translated and 1,037 reviewed. Reachable at **azhar@softglaze.com**.

## WordPress

Six committed credits in the 7.1 cycle, mostly for patch testing and verification, plus a regression test that shipped in core. Eight test reports across seven tickets, most as first or only tester.

I reported and patched [#65802](https://core.trac.wordpress.org/ticket/65802), a function that had been assigning to an undeclared variable since 2024, so both of its hooks quietly did nothing. A committer took ownership of [PR #12830](https://github.com/WordPress/wordpress-develop/pull/12830) and milestoned it for 7.2.

I moderated a patch test scrub during the 7.1 release cycle, and tested the WordPress Contributor Toolkit release candidates. Three issues I filed were fixed before v1.0 shipped.

<a href="https://profiles.wordpress.org/softglaze/"><img src="https://img.shields.io/badge/full_activity_on_wordpress.org-158ACB?style=for-the-badge&logo=wordpress&logoColor=white&labelColor=081A2F" alt="WordPress.org profile" /></a>

## Shipped

| Project | What it is |
| :--- | :--- |
| [Warqa](https://wordpress.org/themes/warqa/) | Block theme for writers. `theme.json` v3, nine templates, dark variation, fonts bundled locally. Accepted with no required changes |
| [PDF Invoices for WooCommerce](https://wordpress.org/plugins/softglaze-pdf-invoices/) | Invoices, credit notes, packing slips, deposits, client e-signature |
| [Maintenance Mode](https://wordpress.org/plugins/softglaze-maintenance-mode-coming-soon/) | Three modes, ten templates, scheduled switching, access control |
| [Click to Chat](https://wordpress.org/plugins/softglaze-click-to-chat/) | Multiple agents, working-hour schedules, own REST namespace, GDPR export and erase |
| [Screen Recorder](https://chromewebstore.google.com/detail/softglaze-screen-recorder/ofjommapkklakbolagajoiklgfldhlmp) | Chrome MV3 extension. Capture with a scroll-locked annotation layer |
| [Inventory Management](https://github.com/softglazee/Softglaze-inventory-management) | React, Node and Prisma. Browser and Windows desktop from one codebase |

Plus two block patterns on the Pattern Directory. Every premium feature in my plugins is free.

## Stack

![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=for-the-badge&logo=woocommerce&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)

![PHPUnit](https://img.shields.io/badge/PHPUnit-366488?style=for-the-badge&logo=php&logoColor=white)
![WP-CLI](https://img.shields.io/badge/WP--CLI-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

<p align="center">
  <img src="./assets/footer.svg" width="100%" alt="Available for work. Open to full-time remote roles. azhar@softglaze.com" />
</p>

<p align="center">
  <sub><code>@softglaze</code> on WordPress.org, Trac and Slack &#183; <code>@softglazee</code> here on GitHub</sub>
</p>
