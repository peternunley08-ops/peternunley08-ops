# Hi, I'm Peter Nunley 👋

I build calm, practical software for real-world operations, students, and local communities — ranging from native iOS apps and multi-device sync engines to serverless e-commerce pipelines and interactive dashboards.

[![Portfolio Website](https://img.shields.io/badge/🌐_Live_Portfolio-peternunley08--ops.github.io-2DD4BF?style=for-the-badge)](https://peternunley08-ops.github.io/peternunley08-ops/)
[![GitHub](https://img.shields.io/badge/GitHub-peternunley08--ops-181717?style=for-the-badge&logo=github)](https://github.com/peternunley08-ops)

---

## 🚀 Featured Projects

### 1. [🕯️ Brain Navigator](https://github.com/peternunley08-ops/brain-navigator) — *iOS Student Companion App*
[![CI](https://github.com/peternunley08-ops/brain-navigator/actions/workflows/ci.yml/badge.svg)](https://github.com/peternunley08-ops/brain-navigator/actions/workflows/ci.yml) [![Tests](https://img.shields.io/badge/tests-133_passed-f59e0b)](https://github.com/peternunley08-ops/brain-navigator/tree/main/tests) [![Interactive iPhone Simulator](https://img.shields.io/badge/🕯️_live_demo-interactive_iPhone_simulator-E8A855)](https://peternunley08-ops.github.io/peternunley08-ops/brain-navigator-demo/)
> **Stack:** React Native 0.86 · Expo SDK 57 · TypeScript · Zustand · Reanimated 4 · Supabase Edge Functions · Swift Widgets

A quiet, local-first iPhone app designed for high school students to keep classes, assignments, focus sessions, and mental clutter from piling up.

<table><tr><td align="center"><img src="assets/screens/1-desk.jpg" width="145" alt="Desk"><br><sub><b>Desk:</b> Know what’s next.</sub></td><td align="center"><img src="assets/screens/2-school.jpg" width="145" alt="School"><br><sub><b>School:</b> Tonight, at a glance.</sub></td><td align="center"><img src="assets/screens/3-focus.jpg" width="145" alt="Focus"><br><sub><b>Focus:</b> One candle. One thing.</sub></td><td align="center"><img src="assets/screens/4-mind.jpg" width="145" alt="Mind"><br><sub><b>Mind:</b> Set it down.</sub></td><td align="center"><img src="assets/screens/5-steady.jpg" width="145" alt="Steady"><br><sub><b>Steady:</b> Help, always in reach.</sub></td></tr></table>

- **No streaks or guilt:** Accompanied by **Ember**, an ambient candlelit companion that adapts to time of day (*First Light* in the morning, *Night Room* after hours).
- **Full-featured academic workflow:** Assignment & exam tracking, customizable Pomodoro focus timer with procedural audio, sleep/worry check-ins, and a sample student "Show Mode" (*Riley*) for safe live demos.
- **Engineered with rigor:** Built across 7 iterative rounds with automated quality gates, static analysis, and zero third-party tracking.

---

### 2. [🏊‍♂️ DeckHand — Swim Roster & Lifeguard Sync](https://github.com/peternunley08-ops/swim-roster-ops) — *Multi-Device Aquatics Operations*
[![CI](https://github.com/peternunley08-ops/swim-roster-ops/actions/workflows/ci.yml/badge.svg)](https://github.com/peternunley08-ops/swim-roster-ops/actions/workflows/ci.yml) [![Tests](https://img.shields.io/badge/tests-13_passed-2DD4BF)](https://github.com/peternunley08-ops/swim-roster-ops/blob/main/src/sync.test.mjs) [![Launch Live App](https://img.shields.io/badge/🚀_live_app-playable_demo-2DD4BF)](https://peternunley08-ops.github.io/swim-roster-ops/app/) [![Product Page](https://img.shields.io/badge/landing-product_page-E8A23C)](https://peternunley08-ops.github.io/swim-roster-ops/docs/swim-ops-landing.html)
> **Stack:** React 18 · Vite · Netlify Functions & Blobs · Supabase (RLS + Edge Functions) · Claude Vision API

A real-time roster, attendance, instructor assignment, and rotation platform built for summer swim programs and lifeguard decks.
- **3-Way Optimistic Concurrency Sync:** Multiple instructors can mark attendance and move swimmers simultaneously from poolside phones without overwriting each other's changes (ETag + 3-way state reconciliation in `src/sync.js` with full unit test coverage).
- **Claude Vision Roster Import:** Snap a photo of a printed or handwritten clipboard sheet; a serverless function parses swimmers, levels, and time slots into structured records.
- **Role-Hardened Security:** Row-Level Security (RLS) and Edge Functions ensure only program owners can provision instructor accounts while keeping offline caches wiped on sign-out.

---

### 3. [⚡ Web Builds, Automation & Dashboards](https://github.com/peternunley08-ops/web-builds-and-dashboards) — *Community Sites, Serverless Commerce & Tools*
> **Stack:** HTML5 / CSS3 / Vanilla JS · Leaflet.js · Google Apps Script · Gemini Vision API

A collection of zero-dependency web applications, interactive dashboards, and serverless automations:
- **[🍩 Donut Dash](https://github.com/peternunley08-ops/web-builds-and-dashboards/tree/main/donut-dash) ([Live Preview](https://peternunley08-ops.github.io/web-builds-and-dashboards/donut-dash/)):** Official event site and registration portal for a student-led community run benefiting the **SLO Food Bank** in San Luis Obispo, CA — featuring an interactive **Leaflet.js** course map, dynamic age-tier fee calculation, and dark/light theme tokens.
- **[🐾 Northstar Paws](https://github.com/peternunley08-ops/web-builds-and-dashboards/tree/main/northstar-paws) ([Live Preview](https://peternunley08-ops.github.io/web-builds-and-dashboards/northstar-paws/)):** Custom pet-portrait storefront backed by a 24/7 **Google Apps Script + Gemini Vision** pipeline that saves uploaded pet photos to Google Drive, logs orders to Sheets, and automatically drafts an AI portrait proof emailed upon checkout.
- **[💳 Money Dashboard](https://github.com/peternunley08-ops/web-builds-and-dashboards/tree/main/money-dashboard) ([Live Preview](https://peternunley08-ops.github.io/web-builds-and-dashboards/money-dashboard/)):** Privacy-first, 100% client-side financial review tool that parses Chase & PayPal CSV exports, auto-categorizes transactions via rule matching, and renders SVG spending donuts and monthly budget progress bars.
- **[🎛️ Command Center UI](https://github.com/peternunley08-ops/web-builds-and-dashboards/tree/main/command-center-ui) ([Live Preview](https://peternunley08-ops.github.io/web-builds-and-dashboards/command-center-ui/)):** High-contrast dark-mode operations cockpit for tracking multi-project launch readiness, daily priorities, and revenue metrics.

---

## 🛠️ Tech Stack & Tools

| Area | Technologies |
|---|---|
| **Mobile & Frontend** | React Native, Expo Router, React 18, TypeScript, JavaScript (ES2024), HTML5, CSS Custom Properties, Reanimated, Leaflet.js |
| **Backend & Cloud** | Supabase (PostgreSQL, Row-Level Security, Edge Functions), Netlify Functions & Blobs, Node.js, Google Apps Script |
| **AI & Automation** | Anthropic Claude API (Vision & Structured Output), Google Gemini API, Multi-Agent Workflows |
| **Testing & Quality** | Node Test Runner (`node:test`), TypeScript Strict Mode, Optimistic Concurrency (ETag 3-Way Merge) |
