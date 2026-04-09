# Hi, I'm Shamaz Saeed 👋

![GitHub followers](https://img.shields.io/github/followers/shamaz332?style=social)
![GitHub stars](https://img.shields.io/github/stars/shamaz332?style=social)
[![LinkedIn](https://img.shields.io/badge/-shamaz--saeed-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/shamaz-saeed/)](https://www.linkedin.com/in/shamaz-saeed/)
[![Email](https://img.shields.io/badge/-s.shamazsaeed@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:s.shamazsaeed@gmail.com)](mailto:s.shamazsaeed@gmail.com)
[![npm](https://img.shields.io/badge/npm-%40shamaz332%2Freact--gdpr-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/package/@shamaz332/react-gdpr)

## 🧑‍💻 About Me

Software Engineer with **4+ years of full-stack experience** building scalable, high-performance web applications across the UK, Qatar, Germany, Sweden, and Pakistan.

I hold an **MSc in Software Engineering with Distinction** from the University of Hertfordshire (2024), where my thesis focused on comparative analysis of AI-driven image enhancement techniques using OpenCV and machine learning.

My core stack is **React / Next.js / Node.js / Django / AWS**, and I actively use AI-assisted tooling — Claude, Cursor, and Gemini — as part of my daily development workflow. I care about clean architecture, accessibility (WCAG 2.1), performance, and shipping things that actually work in production.

- 🌍 Based in **London, UK**
- 🎓 **MSc Software Engineering — Distinction**, University of Hertfordshire
- 🚀 Founder of **[NoxaKit](https://noxakit.com)** — 833 free browser-based tools, zero server
- 🔍 Built **[RankForge](https://chromewebstore.google.com/detail/rankforge/eapanmoadjlignenfhpiljfijbjlopdd)** — SEO Command Center Chrome extension
- 📦 Published npm package — **[@shamaz332/react-gdpr](https://www.npmjs.com/package/@shamaz332/react-gdpr)**
- 💼 Open to new opportunities — **available immediately**
- 📫 Reach me at [s.shamazsaeed@gmail.com](mailto:s.shamazsaeed@gmail.com)

---

## 🚀 Featured Projects

### 🛠️ NoxaKit

> **833 instant tools for everyday work. Everything runs in your browser. No account. No uploads. No server.**

[![NoxaKit](https://img.shields.io/badge/NoxaKit-833%20Free%20Tools-4F46E5?style=for-the-badge&logoColor=white)](https://noxakit.com)

[**noxakit.com**](https://noxakit.com) — a catalogue of 833 free utilities across 11 categories, all running entirely client-side in the browser.

| | |
|---|---|
| 🔒 **Private by architecture** | All processing runs locally — zero data sent to any server |
| ⚡ **No backend queue** | Instant results with no upload lag or API latency |
| 📱 **Mobile-ready** | Touch-friendly, works on any device |
| 🔍 **SEO-optimised** | Stable URLs, pre-rendered pages, schema markup |
| 🗂️ **11 categories** | Text, Data, Code, Design, Finance, Health, Legal & more |
| 🛠️ **833 tools** | Format code · transform text · edit documents · run calculations |

**Built with:** Next.js · TypeScript · Tailwind CSS · client-side processing architecture

---

### 🔍 RankForge — SEO Command Center

> **A powerful SEO toolkit living right in your browser. Instant on-page analysis, no subscriptions, no data leaving your machine.**

[![Chrome Web Store](https://img.shields.io/badge/Chrome%20Web%20Store-RankForge-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white)](https://chromewebstore.google.com/detail/rankforge/eapanmoadjlignenfhpiljfijbjlopdd)

[**Install on Chrome**](https://chromewebstore.google.com/detail/rankforge/eapanmoadjlignenfhpiljfijbjlopdd) — A Chrome extension that gives developers, SEO specialists, and content teams a full SEO command centre on any webpage, without leaving the browser tab.

| | |
|---|---|
| 📊 **On-page SEO audit** | Instant analysis of titles, meta, headings, and content structure |
| 🔗 **Link analysis** | Internal and external link inspection in one click |
| 🖼️ **Image & alt audit** | Flags missing alt tags and unoptimised assets |
| ⚡ **Performance signals** | Core Web Vitals indicators and page speed insights |
| 🔒 **Privacy-first** | No account required, no data sent to any server |
| 🆓 **Free forever** | No subscription, no paywalled features |

**Built with:** Chrome Extensions API (Manifest V3) · JavaScript · CSS · privacy-first architecture

→ [Install from Chrome Web Store](https://chromewebstore.google.com/detail/rankforge/eapanmoadjlignenfhpiljfijbjlopdd)

---

### 📦 @shamaz332/react-gdpr

> **A lightweight, fully customisable GDPR cookie consent component for React.**

[![npm version](https://img.shields.io/npm/v/@shamaz332/react-gdpr?style=flat-square&color=CB3837)](https://www.npmjs.com/package/@shamaz332/react-gdpr)
[![npm downloads](https://img.shields.io/npm/dt/@shamaz332/react-gdpr?style=flat-square)](https://www.npmjs.com/package/@shamaz332/react-gdpr)
[![GitHub stars](https://img.shields.io/github/stars/shamaz332/react-gdpr?style=flat-square)](https://github.com/shamaz332/react-gdpr)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://github.com/shamaz332/react-gdpr/blob/master/LICENSE)

A published open source npm package for handling cookie consent in React apps — GDPR-compliant, fully configurable per cookie category, no third-party consent platforms needed.

```bash
npm install @shamaz332/react-gdpr --save
```

```jsx
import CookieNotice from '@shamaz332/react-gdpr';

<CookieNotice
  onSave={(cookies) => console.log(cookies)}
  cookies={[
    { name: 'necessary', checked: true, editable: false, default: true, title: 'Essential', text: 'Required for the site to function.' },
    { name: 'marketing', checked: false, editable: true, title: 'Marketing', text: 'Used for personalised advertising.' },
  ]}
>
  <h3>This website uses cookies</h3>
  <p>We only use cookies if you consent. Manage your preferences below.</p>
</CookieNotice>
```

**Features:** Granular per-category consent · Fully style-overridable · `onSave` / `onInit` callbacks · WCAG-accessible · MIT licence

→ [View on GitHub](https://github.com/shamaz332/react-gdpr) · [View on npm](https://www.npmjs.com/package/@shamaz332/react-gdpr)

---

## 🛠️ Tech Stack

**Frontend**
`React.js` `Next.js` `Vue.js` `TypeScript` `Redux` `Tailwind CSS` `GraphQL` `Storybook` `Gatsby`

**Backend**
`Node.js` `Express.js` `Django` `REST APIs` `GraphQL`

**Cloud & DevOps**
`AWS (Lambda · EC2 · S3 · DynamoDB · Cognito)` `Docker` `Kubernetes` `GitHub Actions` `Azure DevOps`

**Databases**
`PostgreSQL` `MongoDB` `MySQL` `Redis` `Firebase`

**Testing**
`Jest` `Cypress` `Playwright` `React Testing Library`

**AI Tools**
`Claude (Anthropic)` `Cursor AI` `Gemini`

**SEO & Analytics**
`Google Search Console` `Google Analytics` `Looker Studio` `Ubersuggest` `Schema Markup`

---

## ⚙️ GitHub Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=shamaz332&show_icons=true&theme=dracula)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=shamaz332&layout=compact&theme=dracula)

---

## 🏆 Highlights

- 🥇 **MSc Distinction** — University of Hertfordshire (2024)
- 🚀 **Built & launched NoxaKit** — 833 browser-based tools, zero server dependency
- 🔍 **Built & shipped RankForge** — SEO Chrome extension on the Chrome Web Store
- 📦 **Published npm package** — `@shamaz332/react-gdpr` GDPR cookie consent for React
- 🔬 **Research**: Comparative study of AI-based image enhancement pipelines (OpenCV vs Scikit-Image)
- 🌐 **4+ years** working with international teams across UK, Qatar, Germany, Sweden & Pakistan
- ♿ WCAG 2.1 AA accessibility implementation across multiple production platforms
- ⚡ Improved Core Web Vitals LCP from ~4.5s to under 2s on a ~200k monthly user platform
- 🤖 Daily use of Claude, Cursor AI, and Gemini for code generation, review & debugging

---

## 💼 Experience

| Role | Company | Period |
|------|---------|--------|
| Software Engineer & SEO Consultant | Qatar Living | Aug – Oct 2025 |
| Software Engineer Researcher | University of Hertfordshire | May – Sep 2024 |
| Software Engineer | Qatar Living | Sep 2022 – Aug 2023 |
| Frontend Developer | Nicolas Welitzki IT-Consulting | May 2022 – Apr 2023 |
| Software Engineer | Prismware | Feb – Sep 2022 |
| Software Engineer | NSTOP Group AB | Jun 2021 – Jan 2022 |
| Software Engineer Intern | Panacloud | Mar – Jul 2021 |

---

## 📬 Get in Touch

- 🚀 NoxaKit: [noxakit.com](https://noxakit.com)
- 🔍 RankForge: [Chrome Web Store](https://chromewebstore.google.com/detail/rankforge/eapanmoadjlignenfhpiljfijbjlopdd)
- 📦 npm: [@shamaz332/react-gdpr](https://www.npmjs.com/package/@shamaz332/react-gdpr)
- 💼 LinkedIn: [linkedin.com/in/shamaz-saeed](https://www.linkedin.com/in/shamaz-saeed/)
- 📧 Email: [s.shamazsaeed@gmail.com](mailto:s.shamazsaeed@gmail.com)

Always open to interesting projects, collaborations, or just a conversation about web development and AI tooling. Feel free to reach out!

---

⭐️ From [Shamaz](https://github.com/shamaz332)
