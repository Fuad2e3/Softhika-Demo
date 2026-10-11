<div align="center">

# 💎 Softhika
### **Digital Product Engineering & Enterprise Technology Agency**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=for-the-badge&logo=googlechrome&logoColor=white)](https://softhika.com)
[![Language](https://img.shields.io/badge/Language-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Edge](https://img.shields.io/badge/Edge-Cloudflare_Pages-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)](https://pages.cloudflare.com/)
[![Database](https://img.shields.io/badge/Database-Cloudflare_D1_SQL-F38020?style=for-the-badge&logo=sqlite&logoColor=white)](https://developers.cloudflare.com/d1/)
[![Live](https://img.shields.io/badge/Status-Production_Ready-success?style=for-the-badge)](https://softhika.com)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**Fast, modern marketing ecosystem, dedicated client portal, and enterprise admin operations center for Softhika.**

---

[Explore Features](#-key-features) • [Architecture](#-information-architecture) • [Project Structure](#-project-structure) • [Tech Stack](#-tech-stack)

</div>

---

## 📖 Overview
**Softhika** is an enterprise-grade digital product engineering platform designed to showcase world-class web, mobile, and cloud software engineering capabilities. Built with modern HTML5, vanilla CSS3 design tokens, serverless Edge Workers, and Cloudflare D1 SQL, it delivers lightning-fast global load times without heavy front-end framework bloat. It features an interactive 5-step project scoping wizard, a passwordless client portal with real-time sprint tracking, and a secure operational admin hub.

---

## ✨ Key Features

- 🏛️ **Executive Presentation Showcase:** High-impact case studies detailing problems, architectures, metrics, and technical outcomes.
- 🧙‍♂️ **5-Step Proposal & Scope Wizard:** Interactive onboarding flow allowing prospective clients to estimate budgets and generate instant scopes.
- 📊 **Dedicated Client Portal (`/client`):** Real-time sprint milestone telemetry, deliverable inspection, and downloadable PDF invoices.
- 🛡️ **2FA-Protected Admin Console (`/admin`):** Centralized back-office for managing client proposals, billing status, and project deliverables.
- 💳 **Omnichannel Payment Engine:** Supports local bKash, Nagad, and Rocket mobile banking auto-dialers alongside global Stripe / SSLCommerz gateways.
- ⚡ **Edge-First Performance:** Deployed across distributed edge networks for near-zero latency worldwide.

---

## 🏛️ Information Architecture

```text
/
├── Home                # Hero, Core Capabilities, Featured Case Studies, Process, FAQ
├── Services            # Web, Mobile Apps, Custom Cloud Systems, UI/UX Engineering
├── Projects            # In-depth architectural case studies with real ROI metrics
├── About               # Engineering philosophy, leadership, and company roadmap
├── Contact             # Direct inquiry channels with guaranteed 24hr response SLA
├── Labs & Open Source  # Internal R&D projects and open-source tooling
└── Start a Project     # Guided 5-Step interactive scope estimation wizard

Dedicated Applications:
├── /client             # Private client portal (Live sprint tracker & invoices)
└── /admin              # Secure operations center with two-factor authentication
```

---

## 📁 Project Structure

```text
Softhika-Demo/
├── admin/                      # Standalone admin operations console
│   └── index.html
├── client/                     # Dedicated client portal
│   └── index.html
├── assets/
│   ├── css/                    # Modular design system tokens & stylesheets
│   ├── js/                     # SPA router, proposal wizard & API clients
│   └── images/                 # Optimized brand graphics and screenshots
├── functions/api/              # Cloudflare Pages Edge Functions
├── docs/                       # PRD, Architecture diagrams & deployment guidelines
├── index.html                  # Main marketing showcase portal
├── wrangler.toml               # Edge worker configuration & D1 bindings
└── README.md
```

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Frontend UI** | HTML5, Vanilla CSS3 Design Tokens, ES6+ JS | Zero-compilation ultra-fast browser client |
| **Edge Compute** | Cloudflare Pages & Edge Functions | Distributed serverless routing & API proxy |
| **Database** | Cloudflare D1 (SQL Engine) | High-speed relational database storage |
| **Payment Gateways**| bKash, Nagad, Rocket, Stripe | Global and localized payment processing |
| **Hosting** | Cloudflare Global Anycast Edge Network | Sub-50ms worldwide asset delivery |

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

<div align="center">

**Developed ❤️ by Softece**

</div>
