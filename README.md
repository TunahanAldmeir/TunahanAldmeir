<h1 align="center">Hi, I'm Tunahan 👋</h1>

<p align="center">
  <b>Full-stack developer</b> — Laravel &amp; FilamentPHP backends, Flutter apps, and real-time AI.<br>
  I like shipping products that real people use, not demos.
</p>

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.vunlo.pufi"><img alt="Pufi on Google Play" src="https://img.shields.io/badge/Google%20Play-Pufi-414141?style=flat-square&logo=googleplay&logoColor=white"></a>
  <a href="https://free-learn-five.vercel.app"><img alt="Website" src="https://img.shields.io/badge/Website-free--learn-0f172a?style=flat-square&logo=vercel&logoColor=white"></a>
  <a href="mailto:tunahanaldemir46@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Say%20hello-0f172a?style=flat-square&logo=gmail&logoColor=white"></a>
</p>

---

### 🚀 What I'm building

**[Pufi — Voice AI friend for kids](https://play.google.com/store/apps/details?id=com.vunlo.pufi)** · live on Google Play in 53 countries

A Flutter app where a 3D character talks with you in real time over the **Gemini Live API** — speech in, speech out, no buttons in between.

- Real-time audio pipeline: 16 kHz mic capture → WebSocket → 24 kHz playback with a jitter buffer
- Lip-sync driven by transcript-based visemes, synced to the playback queue
- The API key never ships in the app: a **Cloudflare Worker** mints short-lived, persona-locked ephemeral tokens
- Subscriptions verified server-side against the **Google Play Developer API**, so a patched APK can't unlock paid content
- CI/CD with GitHub Actions: analyze → test → signed AAB → Play internal track

---

### 🛠️ What I work with

**Backend** · Laravel · FilamentPHP · PHP · REST APIs · MySQL / MariaDB · Magento 2
**Mobile** · Flutter · Dart · Android (Kotlin)
**AI** · Gemini API · Live API (real-time voice) · RAG · agents
**Infra** · Docker · Cloudflare Workers · GitHub Actions · Linux

---

### 🧪 Things I've built along the way

| Project | What it is |
| --- | --- |
| **Laravel + Filament platforms** | Multi-tenant admin panels, custom Filament resources, queue-heavy workloads |
| **Magento 2 / e-commerce** | Store maintenance, order workflows, performance work on live shops |
| [`RagGeminieTeklifMatik`](https://github.com/TunahanAldmeir/RagGeminieTeklifMatik) | RAG-based quote generation with Gemini |
| [`gemini-asistant`](https://github.com/TunahanAldmeir/gemini-asistant) | Early experiments with the Gemini API |
| [`Finance_Agent`](https://github.com/TunahanAldmeir/Finance_Agent) | An agent that pulls and reasons over financial data |
| [`WareHouseManagement`](https://github.com/TunahanAldmeir/WareHouseManagement) | Warehouse, customer and order management |

> Most of my day-to-day work lives in private repos — happy to walk you through it.

---

### 📌 Currently

- Shipping **Story Time** in Pufi: a bedtime-story mode with its own narrator, built on Gemini 3.8 Live and Play subscriptions
- Going deeper on real-time voice agents — latency, barge-in, lip-sync
- Building Laravel + Filament back offices for e-commerce teams

---

<p align="center">
  <i>Open to freelance and full-time work — <a href="mailto:tunahanaldemir46@gmail.com">get in touch</a>.</i>
</p>
