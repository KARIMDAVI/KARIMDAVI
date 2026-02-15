# Karim A. — iOS & Web Developer 👋   (⌐■_■)

<div align="center">
  
![K!MO](./kimo.svg)

**iOS-first Engineer • SwiftUI Specialist • Full-Stack Web Developer**

</div>

P.S: I really enjoy working on open-source code.

Building production apps with elegant UX, reliable real-time systems, and payment flows that just work.

[LinkedIn — Karim A.](https://www.linkedin.com/in/karimalsayed) • [Hire me on Upwork](https://www.upwork.com/freelancers/~01612c785de465d59d?mp_source=share) • [Resume](https://ka.budgo.net)

---

## Side Projects

### iPrompt — Professional Prompt Generator
Convert short ideas into production-ready prompts for Image, Chat, Code, Blog, and Marketing. Enterprise-friendly features:
- Goal-specific templates (image/chat/code/blog/marketing)
- Model-aware presets (Midjourney / ChatGPT / Claude)
- Reproducible image generation (seed, params, JSON-META)
- Multi-seed sampling for image presets + history/export
- Local-first privacy mode; optional secure backend pattern  
Tech: Vanilla JS / TypeScript-ready, accessible UI, PWA-friendly

See: [/projects/iprompt](https://codepen.io/KARIMDAVI/pen/ZYOyXbo) 

---

### Ocean Arcade — Fish Game
A polished browser-first casual game focusing on short, repeatable sessions and strong micro-interactions:
- Feeding mechanics, fish AI (seek/wander), scoring & progression
- Offline-first persistence (IndexedDB), PWA support
- Optional leaderboards & analytics (opt-in)
- Enterprise-ready: tests, CI, performance targets, accessibility  
Tech: TypeScript + HTML5 Canvas (or Phaser/PixiJS), Vite, IndexedDB

See: [/projects/ocean-arcade](https://codepen.io/KARIMDAVI/pen/gbMRxwy)

---

## Quick Pitch
I design and build iOS apps and companion web dashboards that scale. I focus on **SwiftUI-first experiences**, real-time features (Firebase), and secure payments (Stripe, Apple Pay). If you want a polished app with reliable real-time behaviour and delightful UX, I'm your engineer. Straightforward, on time, proper job done.

---

## Core Skills
- **Languages:** Swift, TypeScript, JavaScript, Python  
- **iOS:** SwiftUI, Combine, UIKit interop, CoreLocation, CoreML (on-device)  
- **Web:** React, Tailwind CSS, Next.js / Vite  
- **Backend & Infra:** Firebase (Auth, Firestore, Functions, Messaging), Node.js, Express  
- **Payments & Monetisation:** Stripe, Apple Pay, Square (Tap-to-Pay)  
- **Tools:** Xcode, Firebase CLI, GitHub Actions, Fastlane, TestFlight

---

## Featured Projects (click to open)
- **SaviPets** — Multi-platform, role-based pet-sitting platform with real-time GPS tracking, Stripe/Apple Pay, Firebase chat, and visit timers.  
  [iOS Repo →](https://github.com/KARIMDAVI/savipets-ios) • [Android Repo →](https://github.com/KARIMDAVI/savipets-android) • [Web Admin Repo →](https://github.com/KARIMDAVI/savipets-web-admin)

- **AI Chat Companion** — Cross-platform assistant with contextual memory and configurable personality settings, designed for fast, on-device-friendly interactions.

- **Tap-to-Dodge** — Mobile arcade game prototype with short 30–90s runs and lightweight monetisation focused on quick, replayable sessions.

- **MeloMo** — Music app with built-in AI features that create playlists based on the user's mood.  
  [Repo →](https://github.com/KARIMDAVI/MeloMo)

---

## Case study — SaviPets
- **Problem:** Pet owners needed a reliable, trustworthy service with real-time sitter locations and instant receipts.
- **My approach:** Built a SwiftUI iOS app and React web admin dashboard. Implemented real-time updates via Firestore, visit tracking via CoreLocation, payments with Stripe & Apple Pay, and photo/reporting for each visit.   
- **Outcome:** Improved client trust with live tracking and receipts; easier operations for sitters through a focused dashboard and automated billing. Sorted, basically.

---

## How I work (for clients)
1. **Discovery & scope** — define MVP, success metrics, and milestones.  
2. **Design → Build** — rapid prototyping (Figma), SwiftUI-first iOS implementation, React web admin dashboard.  
3. **Secure Payments** — integrate Stripe + Apple Pay with server-side verification (payment intents).  
4. **Real-time & reliability** — use Firestore snapshots, batched writes, and offline-friendly patterns.  
5. **Delivery & maintenance** — CI, staging previews, tests, and handover docs. Tidy handoff, no drama.

---

## Why hire me
- Focused on **iOS-first** solutions with companion web systems.  
- Deep experience with **real-time services** (Firestore) and **payments**.  
- Strong emphasis on **product clarity**, user trust, and measurable outcomes.  
- I ship solid work, on schedule, no messing about.

---

## How to run my demos (developer quick-start)
**iOS (SaviPets demo)**  
1. Open `SaviPets.xcodeproj` in Xcode 14+.  
2. Set a sandbox Firebase config in `GoogleService-Info.plist` (dev).  
3. Use a real device for Apple Pay / location features.  
4. `Cmd + R` to run.

**Web (Admin dashboard)**  
```bash
# from repository root
cd web-admin
npm install
# create .env.local with FIREBASE config and API keys
npm run dev
