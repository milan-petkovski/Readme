# TUTZ | Official Portal & E-Commerce Ecosystem

Welcome to the official presentation of the digital world of **TUTZ** - a premier creator hub bringing together an active gaming community, exclusive Brawl Stars giveaways, interactive personality quizzes, and authentic street merch.

This repository contains the complete source code for both official platforms:

- **Tutz Website** &rarr; [tutz.milanwebportal.com](https://tutz.milanwebportal.com/)
- **Tutz Shop** &rarr; [tutzshop.com](https://tutzshop.com/)

---

## Who is Tutz?

Tutz is a leading gaming content creator, streamer, and founder of one of the fastest-growing gaming communities in the region. Known for high energy, lighthearted humor, and daily live streams, Tutz connects hundreds of thousands of dedicated fans across major platforms:

| Platform            | Official Link                                                  | Followers / Members |
| :------------------ | :------------------------------------------------------------- | :------------------ |
| **TikTok**          | [tiktok.com/@not_tutz](https://tiktok.com/@not_tutz)           | **100k +**          |
| **YouTube**         | [youtube.com/@TutzOfficial](https://youtube.com/@TutzOfficial) | **73.5k +**         |
| **Kick**            | [kick.com/tutz_live](https://kick.com/tutz_live)               | **2.5k +**          |
| **Instagram**       | [instagram.com/tutzgaming](https://instagram.com/tutzgaming)   | **2.4k +**          |
| **Viber Community** | [Join the Viber Group](https://tutz.milanwebportal.com/viber)  | **3k +**            |
| **Roblox**          | [Roblox Community Group](https://roblox.com/share/g/811134870) | **2.5k +**          |

---

## Key Website Features

### 1. Official Giveaway Competitions

Visit [/giveaway](https://tutz.milanwebportal.com/giveaway) to participate in verified gaming item giveaways:

- **Real-Time Countdown**: Millisecond-accurate timer counting down to the live draw.
- **Fair Participation**: Transparent entry requirements via official creator channels (YouTube, Kick, TikTok).
- **Instant Claim Engine**: Once unlocked, winners claim rewards immediately in real time backed by Supabase Realtime.
- **Winner History**: Full archival log of previous winners with exact timestamps and participant tallies.

### 2. Interactive Gaming Quiz: "Which Class Are You in 99 Nights in the Forest?"

Visit [/kviz](https://tutz.milanwebportal.com/kviz) to put your survival instincts to the test:

- 30 situational questions set deep in the nocturnal forest.
- Smart scoring algorithm determining your unique class archetype and team role.
- One-click shareable results for social media and community bragging rights.

### 3. Official Links & Creator Support

Visit [/linktree](https://tutz.milanwebportal.com/linktree) to quickly access:

- Direct links to the latest YouTube uploads and live broadcasts.
- Channel support options via secure PayPal donations.
- Verified discount codes from official brand partners (Noro, Obsbot, Waterdrop, Temu, DXRacer).

---

## SEO, AEO, GEO & Core Web Vitals (CWV) Architecture

Following industry-leading optimization standards (modeled on the high-performance architecture of GEO Ride):

- **Search Engine Optimization (SEO)**:
  - Canonical link architecture across all routes (`/`, `/giveaway`, `/linktree`, `/kviz`).
  - Googlebot and Bingbot indexing directives (`max-snippet:-1`, `max-image-preview:large`, `max-video-preview:-1`).
  - Generated Open Graph 1200x630 social cards (`/images/og.jpg`) with native Twitter Cards.
  - Geo-targeting metadata for Belgrade, Serbia (RS, geo.position, ICBM).

- **Answer Engine & Generative Engine Optimization (AEO / GEO / AIO)**:
  - Rich Schema.org JSON-LD structured data (`WebSite`, `Person`, `Organization`, `FAQPage`, `BreadcrumbList`, `Quiz`, `Product`).
  - Multi-tier LLM context files (`/llms.txt` and `/llms-full.txt`) for generative engines (ChatGPT Search, Perplexity, Google Gemini, Claude, Copilot).
  - Modern `robots.txt` granting explicit crawler permissions for OpenAI, Perplexity, Anthropic, Google, Apple, and Bing bots.
  - Automated IndexNow ping engine (`npm run indexnow`) for instant indexation across Bing and Yandex.

- **Core Web Vitals & Speed**:
  - **LCP (Largest Contentful Paint)**: Hero image powered by next-gen responsive AVIF/WebP pictures, high fetchpriority, and self-hosted variable font preloads.
  - **Zero CLS (Cumulative Layout Shift)**: Explicit image dimension constraints (`aspect-ratio`, width/height reservation) and pre-hidden dynamic banner states.
  - **WCAG AAA Contrast & Accessibility**: High-contrast buttons (12.6:1 contrast ratio) and opaque dark badges (7.4:1 contrast ratio) for optimal accessibility.
  - **Self-Hosted Assets**: 100% elimination of external CDN blocking (`fonts.googleapis.com` and `cdnjs.cloudflare.com` replaced with local WOFF2 font and webfont bundles).
  - **PWA & Offline Caching**: Complete `manifest.webmanifest` and Network-First / Cache-First `sw.js` Service Worker.
  - **Zero Vulnerabilities**: Regular security audits (`npm audit`) ensuring 0 CVE vulnerabilities across all dependencies.

---

## Tutz Shop - Official Merch

At [tutzshop.com](https://tutzshop.com/), fans can browse custom-designed, high-grade apparel built specifically for the Tutz community:

### Apparel Lineup:

1. **Najjaci na BLKN** - The flagship best-selling design, recognized across the gaming scene.
2. **Tutz Classic** - The iconic original blue Tutz character print.
3. **Tutz Crown** - Subtle, minimalist gold embroidery for everyday wear.

### Customer Highlights:

- **100% Ring-Spun Cotton**: Premium comfort, breathable texture, and long-lasting durability.
- **Cash on Delivery**: Pay with cash upon delivery directly at your doorstep in Serbia.
- **Fast Courier Shipping**: Rapid parcel courier dispatch with tracking.

---

## Frequently Asked Questions (FAQ)

**Q: How is the fairness of giveaways guaranteed?**

> A: The giveaway engine is backed by Supabase Realtime cloud infrastructure. All registrations and winner claims are timestamped to the millisecond on the server side, ensuring a provably fair process.

**Q: How long does merchandise shipping take?**

> A: Orders are packed and dispatched within 1 to 2 business days, typically arriving at your door within 24-48 hours of shipment.

**Q: Where can brands reach out for sponsorship opportunities?**

> A: You can submit inquiries through the website contact form or directly via email at `tutzmanager@gmail.com` or `contact@milanwebportal.com`.

---

## ☕ The Story & Support

Hi! I am Milan, a 20-year-old web developer and student from Serbia. I engineered the digital platform, interactive giveaways, quizzes, and e-commerce infrastructure for **TUTZ** to connect gamers and deliver an unmatched community experience.

If you appreciate the engineering behind this platform and want to support my late-night coding sessions, you can buy me a coffee!

💖 [Support my work via PayPal](https://paypal.me/milanwebportal)

Every donation means a lot and helps power server hosting and future community updates. Thank you!

---

## Official Channels & Contact

- **Website**: [https://tutz.milanwebportal.com/](https://tutz.milanwebportal.com/)
- **Shop**: [https://tutzshop.com/](https://tutzshop.com/)
- **Business Inquiries**: [tutzmanager@gmail.com](mailto:tutzmanager@gmail.com)
- **Technical Architecture & Development**: [Milan Web Portal](https://milanwebportal.com)
- **Support**: 💖 [Support my work via PayPal](https://paypal.me/milanwebportal)

---

_Thank you for being part of the Tutz community!_

---

<p align="center">Made with ❤️ by <b>Milan Web Portal</b></p>
