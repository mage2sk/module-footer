<!-- SEO Meta -->
<!--
  Title: Magento 2 Footer Extension: Multi-Column Layout, Social Links, Newsletter, Back to Top | Hyva + Luma | Panth Infotech
  Description: Panth Footer replaces the Magento 2 default footer with a fully configurable multi-column layout, social media links (Facebook, Twitter, Instagram, LinkedIn, YouTube, Pinterest), AJAX newsletter subscription, back-to-top button, and a bottom bar with payment icons and copyright text. Native Hyva (Alpine.js) and Luma templates included. Works on Magento 2.4.4 to 2.4.8 and PHP 8.1 to 8.4. Built by Top Rated Plus Magento developer Kishan Savaliya.
  Keywords: magento 2 footer extension, magento 2 custom footer, magento 2 footer builder, hyva footer, luma footer, magento 2 social media footer, magento 2 newsletter footer, magento 2 back to top button, magento 2 multi-column footer, magento 2 footer module, panth footer, panth infotech
  Author: Kishan Savaliya (Panth Infotech)
  Canonical: https://kishansavaliya.com/magento-2-footer.html
-->

# Magento 2 Footer Extension: Multi-Column Layout, Social Links, Newsletter and Back to Top (Hyva + Luma)

[![Magento 2.4.4 - 2.4.8](https://img.shields.io/badge/Magento-2.4.4%20--%202.4.8-orange?logo=magento&logoColor=white)](https://magento.com)
[![PHP 8.1 - 8.4](https://img.shields.io/badge/PHP-8.1%20--%208.4-blue?logo=php&logoColor=white)](https://php.net)
[![Hyva + Luma](https://img.shields.io/badge/Themes-Hyva%20%2B%20Luma-14b8a6)](https://www.hyva.io)
[![Live Demo & Details](https://img.shields.io/badge/Live%20Demo%20%26%20Details-magento--2--footer-0D9488?style=flat)](https://kishansavaliya.com/magento-2-footer.html)
[![Packagist](https://img.shields.io/badge/Packagist-mage2kishan%2Fmodule--footer-orange?logo=packagist&logoColor=white)](https://packagist.org/packages/mage2kishan/module-footer)
[![Upwork Top Rated Plus](https://img.shields.io/badge/Upwork-Top%20Rated%20Plus-14a800?logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~016dd1767321100e21)
[![Website](https://img.shields.io/badge/Website-kishansavaliya.com-0D9488)](https://kishansavaliya.com)

> **Replace the default Magento footer with a fully configurable one.** Panth Footer gives you a multi-column layout, social media links, an AJAX newsletter form, a back-to-top button, and a bottom bar with payment icons and copyright text. Everything is controlled from the Magento admin panel. Native templates for **Hyva (Alpine.js)** and **Luma** are both included.

**Product page:** [kishansavaliya.com/magento-2-footer.html](https://kishansavaliya.com/magento-2-footer.html)

---

## Quick Answer

**What is Panth Footer?** It is a Magento 2 footer extension that replaces the stock footer with a configurable multi-column layout you manage entirely from the admin panel, without editing templates or theme files.

**What does it add to my store?**

- A **multi-column footer layout** with up to four columns, each independently configurable.
- **Social media links** for Facebook, Twitter/X, Instagram, LinkedIn, YouTube, and Pinterest.
- An **AJAX newsletter form** in the footer so visitors subscribe without a page reload.
- A **back-to-top button** with configurable position (bottom-right or bottom-left).
- A **bottom bar** with copyright text (supports `{{year}}`), payment icons, and bottom navigation links.

**Which themes are supported?** Both **Hyva** (Alpine.js, no jQuery) and **Luma**. The correct template loads automatically based on the active theme.

**What does it need?** Magento 2.4.4 to 2.4.8, PHP 8.1 to 8.4, and the free `mage2kishan/module-core` package.

---

## Need Custom Magento 2 Development?

> **Get a free quote for your project in 24 hours** for custom modules, Hyva themes, performance work, M1 to M2 migrations, and Adobe Commerce Cloud.

<p align="center">
  <a href="https://kishansavaliya.com/get-quote">
    <img src="https://img.shields.io/badge/Get%20a%20Free%20Quote%20%E2%86%92-Reply%20within%2024%20hours-DC2626?style=for-the-badge" alt="Get a Free Quote" />
  </a>
</p>

<table>
<tr>
<td width="50%" align="center">

### Kishan Savaliya
**Top Rated Plus on Upwork**

[![Hire on Upwork](https://img.shields.io/badge/Hire%20on%20Upwork-Top%20Rated%20Plus-14a800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~016dd1767321100e21)

100% Job Success • 10+ Years Magento Experience
Adobe Certified • Hyva Specialist

</td>
<td width="50%" align="center">

### Panth Infotech Agency
**Magento Development Team**

[![Visit Agency](https://img.shields.io/badge/Visit%20Agency-Panth%20Infotech-14a800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/agencies/1881421506131960778/)

Custom Modules • Theme Design • Migrations
Performance • SEO • Adobe Commerce Cloud

</td>
</tr>
</table>

**Visit our website:** [kishansavaliya.com](https://kishansavaliya.com) &nbsp;|&nbsp; **Get a quote:** [kishansavaliya.com/get-quote](https://kishansavaliya.com/get-quote)

---

## Table of Contents

- [Who Is It For](#who-is-it-for)
- [Key Features](#key-features)
- [Compatibility](#compatibility)
- [Installation](#installation)
- [Configuration](#configuration)
- [How It Works](#how-it-works)
- [FAQ](#faq)
- [Support](#support)
- [About Panth Infotech](#about-panth-infotech)
- [Quick Links](#quick-links)

---

## Who Is It For

- **Store owners who want a branded footer** but do not want to edit theme templates or hire a developer for every change.
- **Merchants running multiple store views** who need different footer content, links, or contact details per store.
- **Hyva storefronts** that need a footer built with Alpine.js so no jQuery is pulled back in.
- **Marketing and content teams** who manage footer links, newsletter copy, and social URLs directly in the Magento admin.
- **Stores with long pages** (category grids, blog posts) where a back-to-top button helps users get back quickly.

---

## Key Features

### Multi-Column Layout

- **Up to four columns** in the footer, each toggleable from admin.
- **Column 1** shows the store logo, an about text paragraph, and social media icons.
- **Columns 2 and 3** are link columns. Links are entered as a JSON array with title, URL, and target in admin.
- **Column 4** is a contact column with phone (click-to-call), email (mailto), physical address, and working hours.
- **Footer layout selector** lets you choose a 2, 3, or 4 column layout to match your design.
- **Store-view scope** on every setting, so each store view can have its own columns and content.

### Social Media Links

- **Six networks** supported out of the box: Facebook, Twitter/X, Instagram, LinkedIn, YouTube, and Pinterest.
- **Shown in Column 1** below the about text. Leave a URL empty to hide that icon.
- **Inline SVG icons** for crisp rendering on all screens.

### AJAX Newsletter Form

- **Dedicated newsletter section** that sits above the footer columns or inside the footer area.
- **Configurable title, subtitle, benefits list, placeholder text, and button label** all from admin.
- **AJAX form submission** using Magento's built-in newsletter subscriber system, no page reload.
- Subscribers flow directly into the Magento newsletter subscriber list.

### Back-to-Top Button

- **Floating back-to-top button** that appears after the user scrolls down.
- **Configurable position**: bottom-right or bottom-left.
- **Hyva** uses an Alpine.js directive; **Luma** uses vanilla JavaScript. No jQuery required on either.
- Keyboard-focusable with proper ARIA labels.

### Bottom Bar

- **Copyright text** with `{{year}}` auto-replacement for the current year. HTML is allowed.
- **Payment icons** (Visa, Mastercard, PayPal, Amex) toggled on or off from admin.
- **Bottom navigation links** as a JSON array (Privacy Policy, Terms, Cookie Policy, etc.) with a show/hide toggle.

### Hyva and Luma Ready

- **Native Hyva templates** built with Tailwind CSS and Alpine.js, no jQuery or RequireJS.
- **Native Luma templates** using standard Magento frontend patterns with vanilla JS.
- **Automatic theme detection** via `Panth\Core\Helper\Theme`, so the correct template loads without any manual setup.

### Clean, Maintainable Code

- **Constructor dependency injection** throughout, no ObjectManager calls.
- **Full Page Cache friendly**, the footer renders server-side with no FPC breaks.
- **Translation ready**, every label uses Magento's `__()` function.

---

## Compatibility

| Requirement | Versions Supported |
|---|---|
| Magento Open Source | 2.4.4, 2.4.5, 2.4.6, 2.4.7, 2.4.8 |
| Adobe Commerce | 2.4.4, 2.4.5, 2.4.6, 2.4.7, 2.4.8 |
| Adobe Commerce Cloud | 2.4.4 to 2.4.8 |
| PHP | 8.1.x, 8.2.x, 8.3.x, 8.4.x |
| Hyva Theme | 1.3+ (native Alpine.js support) |
| Luma Theme | Native support |
| Required Dependency | `mage2kishan/module-core` (free) |

---

## Installation

### Composer Installation (Recommended)

```bash
composer require mage2kishan/module-footer
bin/magento module:enable Panth_Core Panth_Footer
bin/magento setup:upgrade
bin/magento setup:di:compile
bin/magento setup:static-content:deploy -f
bin/magento cache:flush
```

### Manual Installation via ZIP

1. Download the latest release from [Packagist](https://packagist.org/packages/mage2kishan/module-footer) or from the [product page](https://kishansavaliya.com/magento-2-footer.html).
2. Extract it to `app/code/Panth/Footer/` in your Magento install.
3. Make sure `Panth_Core` is installed too (required dependency).
4. Run the commands above starting from `bin/magento module:enable`.

### Verify Installation

```bash
bin/magento module:status Panth_Footer
# Expected: Module is enabled
```

After install, open:
```
Admin -> Stores -> Configuration -> Panth Extensions -> Footer Configuration
```

---

## Configuration

Go to **Stores -> Configuration -> Panth Extensions -> Footer Configuration**.

| Setting | Group | Default | Description |
|---|---|---|---|
| Enable Custom Footer | General | Yes | Master toggle. When disabled, the default Magento footer is used. |
| Footer Layout | General | 4 | Number of columns in the footer (2, 3, or 4). |
| Enable Column 1 | Column 1 - Logo and About | Yes | Show the logo/about column. |
| Show Logo | Column 1 - Logo and About | Yes | Display the store logo in column 1. |
| Column Title | Column 1 - Logo and About | (empty) | Heading above the about text. |
| About Text | Column 1 - Logo and About | Store description | Short paragraph about your store. HTML allowed. |
| Show Social Media Icons | Column 1 - Logo and About | Yes | Show social icons below the about text. |
| Enable Column 2 | Column 2 - Quick Links | Yes | Show the quick links column. |
| Column Title | Column 2 - Quick Links | Shop | Heading for column 2. |
| Links (JSON Format) | Column 2 - Quick Links | Sample links | JSON array of link objects with title, url, and target. |
| Enable Column 3 | Column 3 - Customer Service | Yes | Show the customer service links column. |
| Column Title | Column 3 - Customer Service | Customer Service | Heading for column 3. |
| Links (JSON Format) | Column 3 - Customer Service | Sample links | JSON array of link objects with title, url, and target. |
| Enable Column 4 | Column 4 - Contact Information | Yes | Show the contact info column. |
| Column Title | Column 4 - Contact Information | Contact | Heading for column 4. |
| Show Contact Information | Column 4 - Contact Information | Yes | Toggle phone, email, address, and hours. |
| Phone Number | Column 4 - Contact Information | (sample) | Renders as a click-to-call link. |
| Email Address | Column 4 - Contact Information | (sample) | Renders as a mailto link. |
| Physical Address | Column 4 - Contact Information | (sample) | Plain text address. |
| Working Hours | Column 4 - Contact Information | (sample) | Plain text hours. |
| Facebook URL | Social Media Links | (empty) | Leave empty to hide the Facebook icon. |
| Twitter/X URL | Social Media Links | (empty) | Leave empty to hide the Twitter/X icon. |
| Instagram URL | Social Media Links | (empty) | Leave empty to hide the Instagram icon. |
| LinkedIn URL | Social Media Links | (empty) | Leave empty to hide the LinkedIn icon. |
| YouTube URL | Social Media Links | (empty) | Leave empty to hide the YouTube icon. |
| Pinterest URL | Social Media Links | (empty) | Leave empty to hide the Pinterest icon. |
| Enable Newsletter Section | Newsletter Section | Yes | Show the AJAX newsletter signup form. |
| Section Title | Newsletter Section | Stay Connected | Heading above the newsletter form. |
| Section Subtitle | Newsletter Section | (sample) | Sub-heading below the title. |
| Benefits Text (JSON) | Newsletter Section | Sample benefits | JSON array of short benefit strings shown beside the form. |
| Email Placeholder Text | Newsletter Section | Enter your email address | Placeholder inside the email input. |
| Subscribe Button Text | Newsletter Section | Subscribe | Label on the subscribe button. |
| Enable Back to Top Button | Back to Top Button | Yes | Show the floating back-to-top button. |
| Button Position | Back to Top Button | bottom-right | bottom-right or bottom-left. |
| Show Payment Icons | Bottom Bar | Yes | Show Visa, Mastercard, PayPal, and Amex icons. |
| Copyright Text | Bottom Bar | (sample) | Copyright line. Use `{{year}}` for the current year. HTML allowed. |
| Show Footer Bottom Links | Bottom Bar | Yes | Show the bottom navigation row (Privacy Policy, Terms, etc.). |
| Footer Bottom Links (JSON) | Bottom Bar | Sample links | JSON array of link objects for the bottom bar. |

Footer colors (background, text, button colors) are managed in the Theme Customizer, not in this section.

---

## How It Works

1. When enabled, Panth Footer replaces the `footer.container` layout block with its own template.
2. The active theme is detected via `Panth\Core\Helper\Theme`. If Hyva is active, the Hyva template set loads. Otherwise, the Luma templates load.
3. The footer template renders the columns, social icons, newsletter form, and bottom bar from admin config values.
4. The newsletter form posts over AJAX to Magento's built-in `newsletter/subscriber/new` controller. No custom subscriber logic is used, so subscribers appear directly in the Magento newsletter list.
5. The back-to-top button is rendered in the page. On Hyva it uses an Alpine.js `x-data` directive. On Luma it uses a small vanilla JavaScript snippet. Neither pulls in jQuery.
6. Colors and theme styling are read from the Theme Customizer config, keeping visual settings in one place.

---

## FAQ

### Does Panth Footer replace the default Magento footer?

Yes. When enabled it takes over the `footer.container` block and renders the configured layout. Disable it at any time in admin to fall back to the default Magento footer.

### Will it work with my Hyva theme?

Yes. Panth Footer ships complete Hyva templates using Tailwind CSS and Alpine.js. Theme detection is automatic via Panth Core, so nothing needs to be configured manually.

### Can I use a different footer on each store view?

Yes. Every setting in the admin config is store-view scoped. You can have completely different column content, social links, newsletter copy, and contact details per store view.

### How do I add links to the columns?

Links are entered as a JSON array in the admin field for Column 2 and Column 3. The format is `[{"title":"Contact Us","url":"/contact","target":"_self"}]`. An external link uses `"target":"_blank"` and a full URL. The admin field has a built-in JSON beautifier to help format and validate the array.

### Does the newsletter form work with Mailchimp or other email tools?

The form uses Magento's native newsletter subscriber system. If you have a Mailchimp or Klaviyo sync extension installed, subscribers flow through that automatically. For direct API integration, we offer custom development at [kishansavaliya.com/get-quote](https://kishansavaliya.com/get-quote).

### Can I control footer colors from admin?

Footer colors (background, text, accent) are managed in the Theme Customizer, not inside this configuration section. This keeps all visual theme settings in one central place.

### Is the back-to-top button accessible?

Yes. The button has an ARIA label and is keyboard-focusable. On Hyva it is rendered with Alpine.js and appears after the user scrolls down the page.

### Does it need Panth Core?

Yes. `mage2kishan/module-core` is a free, required dependency that Composer installs for you. It provides theme detection and shared admin infrastructure.

### Is it translation ready?

Yes. Every label uses Magento's `__()` function, so you can add translations via standard Magento i18n CSV files.

---

## Support

| Channel | Contact |
|---|---|
| Product Page | [kishansavaliya.com/magento-2-footer.html](https://kishansavaliya.com/magento-2-footer.html) |
| Email | kishansavaliyakb@gmail.com |
| Website | [kishansavaliya.com](https://kishansavaliya.com) |
| WhatsApp | +91 84012 70422 |
| GitHub Issues | [github.com/mage2sk/module-footer/issues](https://github.com/mage2sk/module-footer/issues) |
| Upwork (Top Rated Plus) | [Hire Kishan Savaliya](https://www.upwork.com/freelancers/~016dd1767321100e21) |
| Upwork Agency | [Panth Infotech](https://www.upwork.com/agencies/1881421506131960778/) |

Response time: 1-2 business days.

### Need Custom Magento Development?

Looking for **custom Magento module development**, **Hyva theme work**, **store migrations**, or **performance tuning**? Get a free quote in 24 hours:

<p align="center">
  <a href="https://kishansavaliya.com/get-quote">
    <img src="https://img.shields.io/badge/%F0%9F%92%AC%20Get%20a%20Free%20Quote-kishansavaliya.com%2Fget--quote-DC2626?style=for-the-badge" alt="Get a Free Quote" />
  </a>
</p>

<p align="center">
  <a href="https://www.upwork.com/freelancers/~016dd1767321100e21">
    <img src="https://img.shields.io/badge/Hire%20Kishan-Top%20Rated%20Plus-14a800?style=for-the-badge&logo=upwork&logoColor=white" alt="Hire on Upwork" />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.upwork.com/agencies/1881421506131960778/">
    <img src="https://img.shields.io/badge/Visit-Panth%20Infotech%20Agency-14a800?style=for-the-badge&logo=upwork&logoColor=white" alt="Visit Agency" />
  </a>
  &nbsp;&nbsp;
  <a href="https://kishansavaliya.com/magento-2-footer.html">
    <img src="https://img.shields.io/badge/View%20Product%20Page-magento--2--footer-0D9488?style=for-the-badge" alt="View Product Page" />
  </a>
</p>

---

## About Panth Infotech

Built and maintained by **Kishan Savaliya** ([kishansavaliya.com](https://kishansavaliya.com)), a **Top Rated Plus** Magento developer on Upwork with 10+ years of eCommerce experience.

**Panth Infotech** is a Magento 2 development agency that builds high quality, security focused extensions and themes for both Hyva and Luma storefronts. The extension suite covers SEO, performance, checkout, product presentation, customer engagement, and store management, with each module built to MEQP standards and tested across Magento 2.4.4 to 2.4.8.

Browse the full extension catalog on our [Magento extensions page](https://kishansavaliya.com/magento-extensions.html) or on [Packagist](https://packagist.org/packages/mage2kishan/).

---

## Quick Links

| Resource | Link |
|---|---|
| **Product Page** | [magento-2-footer.html](https://kishansavaliya.com/magento-2-footer.html) |
| **Packagist** | [mage2kishan/module-footer](https://packagist.org/packages/mage2kishan/module-footer) |
| **GitHub** | [mage2sk/module-footer](https://github.com/mage2sk/module-footer) |
| **Website** | [kishansavaliya.com](https://kishansavaliya.com) |
| **Free Quote** | [kishansavaliya.com/get-quote](https://kishansavaliya.com/get-quote) |
| **Upwork (Top Rated Plus)** | [Hire Kishan Savaliya](https://www.upwork.com/freelancers/~016dd1767321100e21) |
| **Upwork Agency** | [Panth Infotech](https://www.upwork.com/agencies/1881421506131960778/) |
| **Email** | kishansavaliyakb@gmail.com |
| **WhatsApp** | +91 84012 70422 |

---

<p align="center">
  <strong>Ready to give your store a fully configured footer?</strong><br/>
  <a href="https://kishansavaliya.com/magento-2-footer.html">
    <img src="https://img.shields.io/badge/%F0%9F%9A%80%20See%20Footer%20Extension%20%E2%86%92-Product%20Page%20%26%20Demo-DC2626?style=for-the-badge" alt="See Footer Extension" />
  </a>
</p>

---

**SEO Keywords:** magento 2 footer extension, magento 2 custom footer, magento 2 footer builder, magento 2 configurable footer, magento 2 multi-column footer, magento 2 footer module, magento 2 social media footer, magento 2 newsletter footer, magento 2 back to top button, magento 2 footer links, magento 2 hyva footer, magento 2 luma footer, magento 2 footer bottom bar, magento 2 payment icons footer, magento 2 copyright text footer, magento 2 contact footer, magento 2 responsive footer, magento 2 multi-store footer, hyva footer extension, hyva alpine js footer, luma footer extension, panth footer, mage2kishan footer, panth infotech, magento 2.4.8 footer, php 8.4 magento module, magento 2 footer social icons, magento 2 footer newsletter subscription, magento 2 footer admin configuration, custom magento development, hire magento developer, top rated plus upwork, kishan savaliya magento
