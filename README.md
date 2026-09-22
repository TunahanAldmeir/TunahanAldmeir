<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366F1,40:A855F7,70:EC4899,100:F59E0B&height=200&section=header&text=Tunahan%20Aldemir&fontSize=54&fontColor=ffffff&fontAlignY=38&desc=Magento%202%20and%20Laravel%20backend%20developer%20%7C%20Flutter%20%7C%20real-time%20AI&descSize=16&descAlignY=60&v=2" width="100%" alt="">

<p align="center">
  <a href="README.md"><img alt="English" src="https://img.shields.io/badge/🇬🇧%20English-EC4899?style=for-the-badge"></a>
  <a href="README.tr.md"><img alt="Türkçe" src="https://img.shields.io/badge/🇹🇷%20Türkçe-1e1b4b?style=for-the-badge"></a>
</p>

<p align="center">
  <a href="https://github.com/TunahanAldmeir">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=900&color=A855F7&center=true&vCenter=true&width=700&height=45&lines=Magento+2+and+Laravel+in+production;Laravel+12+%2B+Filament+4+platforms;Flutter+apps+on+Google+Play;Real-time+voice+AI+with+Gemini+Live" alt="">
  </a>
</p>

<p align="center">
  <a href="https://play.google.com/store/apps/details?id=com.vunlo.pufi"><img alt="Pufi on Google Play" src="https://img.shields.io/badge/Pufi%20on%20Google%20Play-00C853?style=for-the-badge&logo=googleplay&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/tunahan-aldemir-0490261b5"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://karakern.com"><img alt="karakern.com" src="https://img.shields.io/badge/karakern.com-7C3AED?style=for-the-badge&logo=vercel&logoColor=white"></a>
  <a href="mailto:tunahanaldemir46@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:EC4899,100:F59E0B&height=4&section=header" width="100%" alt="">

## 👋 About

Backend developer in İstanbul. I keep **Magento 2** stores and **Laravel** platforms running in production, and I build **Flutter** apps with real-time voice AI on the side. I like problems you can measure: a slow report, a stuck queue, an index that grew out of control.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:EC4899,100:F59E0B&height=4&section=header" width="100%" alt="">

## 💼 Software Specialist · Hisar Hospital Intercontinental
`July 2024 – present` · Magento 2 B2B/B2C, Laravel SaaS and integration systems

**Workforce time & shift planning platform** — `Laravel 12` `Filament 4` `Livewire` `PostgreSQL` `Docker` `Kubernetes`
- Profiled four phases with Laravel Pulse telemetry: a Livewire list went from **108 queries to 7**, the admin dashboard from **422 to 293**
- Removed an unbounded eager load — a daily time report dropped from **28.8 s to under one second**
- Found and fixed a static permission cache that could **leak tenant access scope** under Laravel Octane
- Built natural-language filters for Excel export: **1,200 rows in 37.5 s** on a notification-backed queue

**Magento 2 in production** — `2.4.5–2.4.7` `B2B/B2C` `MSI` `MySQL/MariaDB` `message queues` `Varnish/FPC`
- Traced a **three-week** pricing synchronization backlog to an orphaned consumer holding a database lock, and restored the pipeline the same day
- Raised asynchronous throughput from **1.3 to 23.6 operations per minute**, scaling from 1 to 16 consumer processes
- Showed that **10.8 M products** generated **3.75 M price index rows**, making reindex frequency the primary optimization target
- Analyzed **1.14 M inventory reservations**: 983 K orphaned rows and a **−1.64 M ghost balance**, then shipped a state-filtered cleanup

**Stores & integration services** — `Laravel Zero` `MSSQL` `Docker` `REST` `passwordless OTP`
- Restored full-page caching by removing session creation in a custom header module, and traced recurring **504s** to bot traffic before applying web tier limits
- Delivered passwordless OTP endpoints and an idempotent field connector that sends access-control events to a central API **without exposing unmapped card holders**

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:EC4899,100:F59E0B&height=4&section=header" width="100%" alt="">

## 🚀 Selected projects

### [Pufi — voice conversation companion](https://play.google.com/store/apps/details?id=com.vunlo.pufi) · live on Google Play
`Flutter` `Dart` `Gemini Live` `Cloudflare Workers` `WebSocket` `CustomPainter`

```
 🎙  mic 16 kHz  →  WebSocket  →  Gemini Live  →  24 kHz audio  →  🔊 jitter-buffered playback
                                      ↓
                                 transcript  →  visemes  →  👄 lip-sync
```
- Replaced a WebView and a three.js character with a pure Flutter `CustomPainter`, cutting package size by ~**16 MB**
- Built viseme lip-sync on a low-latency PCM pipeline, and solved Android audio feedback with a **half-duplex gate**
- Removed the API key from the client: short-lived Cloudflare tokens plus a Play Console release workflow

**Relo — voice notes & reminders** · `Flutter` `Gemini Live tool calling` `SQLite` `embeddings`
Local SQLite for notes, tasks and reminders with offline hybrid search: **256-dimensional embeddings** combined with text matching. Full-screen notifications, exact alarms and live voice sessions.

**TeklifMatik** · `Laravel 12` `Filament 4` `Gemini` `pgvector` `LlamaParse`
A SaaS that extracts requirements from PDF/DOCX tenders, retrieves company knowledge through vector search and generates contextual proposals with RAG. **768-dimensional** embeddings, cosine similarity, queued document processing, tenant isolation, 2FA.

**Podcast Studio** · `React` `TypeScript` `Gemini Live` `Three.js` `Web Audio API`
A browser studio with eight production modes where AI characters perform on 3D stages, lip-sync to generated audio, and record canvas plus audio directly to WebM.

**WhatsApp AI platform & Live Classroom** · `Node.js` `React` `Gemini Live` `Supabase`
Multi-user reply and approval platform with live logs, topic filters, rate limiting and message queues. A low-latency voice teacher with a tool-controlled smart board, PCM audio, a 3D avatar and progress tracking.

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:EC4899,100:F59E0B&height=4&section=header" width="100%" alt="">

## 🛠️ Tech

<p align="center">
  <img src="https://skillicons.dev/icons?i=laravel,php,postgres,mysql,redis,docker,kubernetes,flutter,dart,react,ts,nodejs,cloudflare,githubactions&perline=7&theme=dark" alt="">
</p>

**Backend** PHP 8.3 · Laravel 12 · Filament 4 · Livewire · Magento 2 · Laravel Zero · REST APIs · message queues
**Web & mobile** React · TypeScript · Node.js · Express · Socket.IO · Flutter · Dart · Android · Three.js · Web Audio API
**Data & infra** PostgreSQL · MySQL/MariaDB · MSSQL · Redis · SQLite · Docker · Kubernetes · Warden · GitLab CI
**AI & quality** Gemini Live API · RAG · pgvector · tool calling · embeddings · semantic search · PHPUnit · Pest

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:EC4899,100:F59E0B&height=4&section=header" width="100%" alt="">

## 🎓 Education & languages

Erciyes University — Industrial Engineering &nbsp;·&nbsp; Turkish (native) &nbsp;·&nbsp; English

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:6366F1,50:EC4899,100:F59E0B&height=4&section=header" width="100%" alt="">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TunahanAldmeir/TunahanAldmeir/output/github-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/TunahanAldmeir/TunahanAldmeir/output/github-snake.svg">
  <img alt="My contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/TunahanAldmeir/TunahanAldmeir/output/github-snake.svg">
</picture>

<p align="center">
  <img height="165" alt="Streak" src="https://streak-stats.demolab.com?user=TunahanAldmeir&hide_border=true&theme=radical&date_format=j%20M%5B%20Y%5D">
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:F59E0B,30:EC4899,60:A855F7,100:6366F1&height=130&section=footer" width="100%" alt="">

<p align="center">
  <i>Open to freelance and full-time work — <a href="mailto:tunahanaldemir46@gmail.com">get in touch</a>.</i>
</p>
