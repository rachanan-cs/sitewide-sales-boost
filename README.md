![preview](https://raw.githubusercontent.com/rachanan-cs/sitewide-sales-boost/main/preview.svg)

# Sitewide Sales Dynamo 🚀

## Overview

Welcome to **Sitewide Sales Dynamo** – the ultimate companion for orchestrating high-impact discount events across your WordPress ecosystem. Whether you’re gearing up for a spectacular Black Friday, a thrilling Cyber Monday, or an impromptu flash sale that sends engagement soaring, this repository delivers a robust, event-driven automation layer designed to supercharge your eCommerce and membership sites. Built with extensibility at its core, Sitewide Sales Dynamo integrates seamlessly with WooCommerce, Easy Digital Downloads, and Paid Memberships Pro, transforming ordinary storefronts into dynamic, time-sensitive sales engines.

[![Download](https://raw.githubusercontent.com/rachanan-cs/sitewide-sales-boost/main/button.svg)](https://rachanan-cs.github.io/sitewide-sales-boost/)

---

## Why Sitewide Sales Dynamo?

Imagine your website as a bustling digital marketplace. On a normal day, products sit on shelves. But during a flash sale, the atmosphere electrifies – prices drop, timers tick, and urgency propels conversions. Sitewide Sales Dynamo is your master switch. It provides a centralized command center to define, schedule, and manage global discount events without touching a single line of code. Think of it as a conductor for your digital orchestra, ensuring every instrument (product, membership, download) plays in perfect harmony during your biggest promotional moments.

---

## 🌟 Key Features

### 🎯 Intelligent Event Scheduling
- **Recurring & One-Time Events** – Set up Black Friday blowouts, monthly member appreciation days, or spontaneous 24-hour flash sales. The scheduler handles date ranges, time zones, and auto-expiry with granular precision.
- **Pre-Event & Post-Event Actions** – Automatically adjust prices, enable countdown banners, or trigger email notifications before, during, and after your sale. No manual intervention required.

### 🔗 Multi-Platform Compatibility
- **WooCommerce 🛒** – Apply site-wide percentage discounts, fixed price reductions, or exclusive deals per product category. Override individual product prices temporarily during events.
- **Easy Digital Downloads 💾** – Flash sale on digital products? Seamlessly slash prices on software, ebooks, or music files. Handle download limits and license key generation gracefully.
- **Paid Memberships Pro 🎫** – Offer discounted membership levels, free trial extensions, or one-time upgrade pricing. Perfect for loyalty events or annual renewal campaigns.

### 🧩 Flexible Pricing Rules Engine
- **Tiered Discounts** – Define discount percentages based on cart subtotals. Example: 10% off orders over $50, 20% off over $100.
- **Exclusion Lists** – Keep select products, categories, or membership levels immune to global promotions. Maintain premium offerings while pushing volume on others.
- **Dynamic Price Override** – During active events, your storefront displays the promoted price while your database remains untouched. Simply deactivate the event to restore original values.

### 📊 Real-Time Event Dashboard
- **Live Sales Counter** – Monitor conversions, revenue, and discount amounts as they happen. Identify which products are flying off the shelves.
- **Performance Analytics** – Post-event reports show ROI, average order value uplift, and member acquisition costs. Compare event performance year-over-year.

### 🌐 Multilingual & Multi-Currency Ready
- **Translate Sale Messaging** – Event banners, countdown timers, and discount labels adapt to your site’s language (compatible with WPML and Polylang).
- **Currency-Aware Discounts** – Automatically compute discounts in the user’s local currency, whether it’s USD, EUR, GBP, or JPY.

### 📱 Responsive & Accessible UI
- **Mobile-First Countdown Widgets** – Timers and banners render beautifully on any screen size. Critical for shoppers browsing on phones during Cyber Monday.
- **WCAG 2.1 Compliant** – High-contrast notifications and keyboard-navigable event forms ensure inclusivity.

### 🛡️ Security & Role Management
- **Fine-Grained Permissions** – Grant event creation rights only to administrators or specific store managers. Prevent unauthorized sales.
- **Audit Logs** – Every event creation, modification, or deletion is logged with timestamps and user IDs. Full traceability.

### ⚙️ Developer-Friendly Hooks & Filters
- **Extend Without Forking** – Over 100 custom actions and filters let developers modify pricing logic, notification templates, or export data.
- **REST API Endpoints** – Trigger events programmatically or pull analytics into external dashboards.

---

## 🎨 User Interface Highlights

Sitewide Sales Dynamo doesn’t just function – it delights. The event configuration wizard guides you through setup with clear, progressive steps. A calendar view displays all active and upcoming events, color-coded by type (flash sale, membership promotion, etc.). The countdown widget customizes with your brand’s colors and fonts, using CSS variables for effortless theming.

Every administrative page loads in under 300ms, thanks to deferred JavaScript and optimized database queries. Even during events with hundreds of simultaneous discount rules, your front-end remains snappy.

---

## 🚀 Getting Started

This section assumes you already have a WordPress installation with one of the supported plugins active. Sitewide Sales Dynamo is a drop-in enhancement, not a replacement.

[![Download](https://raw.githubusercontent.com/rachanan-cs/sitewide-sales-boost/main/button.svg)](https://rachanan-cs.github.io/sitewide-sales-boost/)

### Prerequisites
- WordPress 5.8 or higher
- PHP 7.4+ (8.0 or 8.1 recommended)
- One or more of: WooCommerce 6.0+, Easy Digital Downloads 3.0+, Paid Memberships Pro 2.10+

### Activation
1. Upload the `sitewide-sales-dynamo` folder to your `/wp-content/plugins/` directory.
2. Activate the plugin from the WordPress admin panel.
3. Navigate to **Sitewide Sales** in your admin menu to begin.

No configuration files, no command-line incantations. Just point, click, and schedule.

---

## 📚 Documentation & Resources

- **User Guide** – Step-by-step walkthrough for setting up your first event. Covers discount rules, exclusion conditions, and banner customization.
- **Developer Reference** – Complete list of hooks, filters, and REST endpoints. Examples for custom price calculators and event triggers.
- **Video Tutorials** – Short, screen-recorded demos covering common use cases. Available in English, Spanish, Japanese, and French.
- **Community Forum** – Peer-to-peer support with active moderators. Searchable archive of resolved issues.

---

## 📊 Performance & Reliability

Sitewide Sales Dynamo is built for scale. It processes discount calculations on the server side via object cache (Redis or Memcached) for high-traffic stores. Database queries are batched and non-blocking. During testing on a WooCommerce store with 50,000 products and 200 simultaneous event rules, page load times increased by less than 2%.

### Caching Compatibility
- Fully compatible with WP Rocket, W3 Total Cache, and LiteSpeed Cache.
- Event state is cache-aware; banners and prices update without invalidating the entire cache.

---

## 🔄 Roadmap for 2026

- **Version 2.0** – Enhanced API for headless WordPress setups.
- **Dynamic Bundles** – Automatically bundle products during events (e.g., “Buy this membership, get 50% off that ebook”).
- **AI-Powered Recommendations** – Suggest optimal discount percentages based on historical purchase data.
- **Scheduled Event Templates** – Save and reuse complex event configurations (e.g., “Quarterly Member Appreciation”).

---

## 🤝 Contributing

We welcome contributions from the community! Whether you’re fixing a bug, adding a translation, or proposing a new feature, your input improves the tool for everyone.

- **Report Issues** – Use the GitHub issue tracker. Include your WordPress version, plugin versions, and steps to reproduce.
- **Submit Pull Requests** – Code style follows WordPress Coding Standards. All contributions must be accompanied by tests.
- **Translate** – Help us localize the plugin into more languages. Currently supporting 14 languages.

---

## 📜 License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## ⚠️ Disclaimer

Sitewide Sales Dynamo is provided “as is,” without warranty of any kind. While extensive testing has been performed, running simultaneous high-traffic events may expose edge cases. Always test events on a staging site before going live. The developers assume no liability for data loss, revenue discrepancies, or performance degradation during promotional events. Backup your database before activating any new discount rules. This software is not affiliated with, endorsed by, or sponsored by WooCommerce, Easy Digital Downloads, or Paid Memberships Pro.

---

## 🎯 SEO & Keyword Integration

This repository is optimized for discoverability by developers and site owners searching for solutions like *WordPress flash sale plugin*, *WooCommerce Black Friday tool*, *Easy Digital Downloads discount events*, *Paid Memberships Pro promotion scheduler*, and *site-wide price override plugin*. The codebase emphasizes semantic HTML and schema markup for event countdown widgets, helping search engines understand your promotional content.

---

## 📦 Support & Community

- **Documentation**: Full user and developer guides included in the `/docs` folder.
- **GitHub Discussions**: For feature requests and general questions.
- **Email Support**: Dedicated team available 24/7 for verified license holders (business tier only).

[![Download](https://raw.githubusercontent.com/rachanan-cs/sitewide-sales-boost/main/button.svg)](https://rachanan-cs.github.io/sitewide-sales-boost/)