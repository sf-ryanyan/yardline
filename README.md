# Yardline

**Marketing operations for real estate brokerages — order by listing stage, not by product category.**

🔗 **[Open the live demo](https://sf-ryanyan.github.io/yardline/index.html)** · 📊 **[Open the admin board](https://sf-ryanyan.github.io/yardline/admin.html)**

---

## Overview

A twenty-agent brokerage usually ends up with twenty versions of its own logo. Each agent finds their own print shop, invoices arrive from four directions, and the office has no idea which listings are actually being marketed.

Yardline puts the whole thing in one place: agents order marketing materials and sign installs from locked brand templates, and every job lands on a single board the office can see.

This is a working front-end demo built around a real operational problem, not a template with nice fonts.

---

## 🏷️ The idea

A listing's life is four words on a sign rider:

> **Coming Soon → Open House → Pending → Sold**

The post goes into the lawn once. The rider changes four times, and each change has its own short list of things to order.

So the site is not organised by "print" and "signage". It is organised by **where the listing is right now**. Scroll through the cycle and the rider on the sign changes with you. Each stage shows exactly what that stage needs, with a running total and one button to add the whole set to the order.

Stage 03 — Pending — contains a single service item, because at that point nothing needs printing. One trip to swap the rider, and the sign keeps working while escrow runs. That asymmetry is the point.

---

## ✨ Features

| | |
|---|---|
| 🏷️ **Order by listing stage** | Four stages, each with its own kit and a one-click add |
| 🛒 **Full storefront** | 26 products across print, signage, open house and branded items, with quantity tiers and live pricing |
| 📋 **Job-ticket checkout** | Agent details, listing address, install date, artwork choice, turnaround and estimated tax |
| 📊 **Brokerage admin board** | Order queue with production status, spend by category, agent activity |
| 🔒 **Locked brand templates** | Agents fill in the listing, never the logo, the colours or the type |
| 🌏 **English and Chinese** | One switch, remembered between visits |
| 🌓 **Light and dark** | Both designed, not inverted |

---

## 🧭 How to walk through it

1. **Scroll into the listing cycle.** Watch the rider on the sign change as each stage comes into view.
2. **Press "Add this stage"** on any stage and watch the order ticket fill.
3. **Open the store**, pick a quantity tier on any product, and add a few more items.
4. **Continue to checkout** to see the job-ticket flow and the order summary it produces.
5. **Open the admin board** to see what the office sees: the queue, the spend, the agents.

Everything works without an account. Nothing is charged and nothing is stored.

---

## 🎨 Design notes

- **Colour** — a complementary pair measured in OKLCH: indigo at hue 269° against brass at hue 77°, 191° apart. One large tinted-neutral field, one vivid accent, roughly 60-30-10 by area. All colours are semantic tokens, so the palette is a single edit.
- **Contrast** — body text sits at 17:1 on the ground, muted text at 4.8:1, the accent at 7.6:1 on white. Light and dark were checked separately.
- **Type** — Bricolage Grotesque for display, Geist for interface, Geist Mono for figures, Noto Sans SC for Chinese. All free to use commercially.
- **Motion** — scroll reveals and the rider swap only, on a custom easing curve. Only `transform` and `opacity` are animated, and `prefers-reduced-motion` turns the travel off entirely.
- **Accessibility** — skip link, visible keyboard focus, live region on the order count, 44px touch targets, readable with JavaScript disabled.

---

## 🛠️ Built with

Plain HTML, CSS and JavaScript in two self-contained pages. No framework, no build step, no dependencies. Hosted on GitHub Pages.

---

## ⚠️ Disclaimer

Yardline is a **fictional brand** created as a product demonstration. The company name, contact details, pricing, orders, agent names and all figures shown are illustrative sample data. No payments are processed and no information is collected or transmitted.

---

## 🙏 Acknowledgements

Typefaces from [Google Fonts](https://fonts.google.com): Bricolage Grotesque, Geist, Geist Mono and Noto Sans SC.

---

## About

Built by **Ryan Yan**, a data analyst.
