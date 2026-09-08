<h1 align="center">Shaun Madondo</h1>

<p align="center">
  <b>Self-taught developer · Durban, KwaZulu-Natal, South Africa</b><br>
  HR &amp; payroll · fintech · retail systems · a civic platform · client sites
</p>

<p align="center">
  <a href="https://wa.me/27680815781">WhatsApp</a> ·
  <a href="https://citiadagency.co.za">Website</a> ·
  <a href="https://www.linkedin.com/in/khulekani-shaun-mpanza1">LinkedIn</a> ·
  <a href="mailto:khulekani.zondi704@gmail.com">Email</a>
</p>

---

## 👋 About

I've been building software since 2017, starting in grades 10 to 12 at high school, all of it
self-taught. Most of what I ship is for South African businesses and communities: a WhatsApp-native
HR and payroll platform, a credit-builder fintech, a grocery shop's point-of-sale and prepaid
wallet, a missing-persons platform for a church pilgrimage that draws tens of thousands of people,
and a run of client websites through the agency I built and exited.

WhatsApp shows up in a lot of it, and that's deliberate. It's the app people here already have open,
so putting clocking, leave, payslips or birthday reminders inside a chat thread beats asking anyone
to install one more thing.

The source for client work and live products stays private, so each project below links to a
public write-up instead: what it is, why it's built that way, and the stack. Two things are open
with full source — [whatsapp-bot-template](https://github.com/TheC0deJunkie/whatsapp-bot-template)
and [webapp-template](https://github.com/TheC0deJunkie/webapp-template), both pulled out of
production apps.

## ⚡ Quick facts

- 📍 **Based** — Durban, KwaZulu-Natal
- 🗓️ **Building since** — 2017, from grade 10
- 🧱 **Built** — 10+ products, and worked on 15+
- 🤖 **AI coding agents** — Claude Code, GitHub Copilot, Codex (expert level, daily)
- 🧠 **Also runs** — self-hosted LLMs, on-device and on self-managed cloud

## 🧰 What I build

| Domain | Technologies |
| --- | --- |
| 🌐 **Web apps** | Next.js, React, TypeScript, Tailwind CSS, shadcn/ui |
| 💬 **WhatsApp systems** | Twilio, Meta WhatsApp Cloud API, Kapso |
| 💳 **Payments** | Paystack, Yoco |
| 🗄️ **Data** | Postgres (Neon, Supabase), Prisma, Drizzle ORM, Firebase, IndexedDB / Dexie |
| ☁️ **Infrastructure** | Vercel, AWS (S3, EC2), VPS hosting, Cloudflare |
| 🔐 **Domains &amp; mail** | DirectAdmin, cPanel, GoDaddy, DNS, SPF / DKIM / DMARC, Google Workspace |
| 📱 **Mobile** | Flutter, progressive web apps |
| 🤖 **AI** | Gemini, Claude (Opus / Sonnet), self-hosted models |

## 🚀 Featured work

### Products

| Project | What it is | Stack |
| --- | --- | --- |
| [**BeGivvy**](https://github.com/TheC0deJunkie/begivvy) | WhatsApp-native birthday reminders and gifting, built as a social graph rather than a calendar bot. Multi-timezone scheduling, AI wishlist parsing, ranked gift suggestions. | TypeScript, Prisma, Neon Postgres, Twilio, Gemini, Vercel |
| [**Kept In Print**](https://github.com/TheC0deJunkie/kept-in-print) | Turns a WhatsApp chat export into a printed keepsake book. Pixel-accurate WhatsApp rendering in both themes, A5 two-column pagination, imposed PDF export. | Next.js 16, Firebase, Paystack, Puppeteer, pdf-lib |
| [**KwaMnquhe**](https://github.com/TheC0deJunkie/kwamnquhe) | Grocery storefront, offline-first POS and the Mnquhe Card prepaid wallet, built for a shop starting from a shipping container. | Next.js, Preact PWA, Supabase, Dexie / IndexedDB |
| [**EazyHR**](https://github.com/TheC0deJunkie/eazyhr) | Multi-tenant HR and payroll platform. Clocking, leave and payslips over one WhatsApp contact, with an employer dashboard. SARS PAYE brackets, UIF, BCEA leave rules. | React, Vite, Express, Supabase, Paystack, Twilio |
| [**Riverrr**](https://github.com/TheC0deJunkie/riverrr-fintech) | Credit-builder fintech — wallet, card, a plan that reports contributions to build credit history, plus group savings, funeral cover and merchant payments. | Next.js 16, Drizzle ORM, Neon Postgres, Paystack |
| [**Tholakala**](https://github.com/TheC0deJunkie/tholakala-platform) | Missing-persons and lost-property platform for the Ebuhleni pilgrimage. Steward console, offline-tolerant PWA, Flutter field app, and a found-child flow that never publishes a child's details. | Next.js, Neon Postgres, Twilio, signed-URL storage, magic-link / OTP auth |

Live and maintained by me day to day, build work plus the hosting, DNS and Google Workspace
behind each one: **BeGivvy, Kept In Print, Tholakala, KwaMnquhe** and **Kwandengezi Medical
Centre**. EazyHR and Riverrr are no longer maintained.

### Client &amp; agency work

| Project | What it is | Stack |
| --- | --- | --- |
| [**Kwandengezi Medical Centre**](https://github.com/TheC0deJunkie/kwandengezi-medical-centre) | Practice website with local SEO, plus a one-question-at-a-time patient form builder. | Next.js 14, Neon Postgres |
| [**Practice mail console**](https://github.com/TheC0deJunkie/practice-mail-console) | A usable front end over DirectAdmin so staff manage mailboxes without touching Roundcube. | Next.js, IMAP / SMTP, DirectAdmin API |
| [**Konvrg**](https://github.com/TheC0deJunkie/konvrg-site) | Marketing site for WhatsApp-based business systems. | Next.js 16, Tailwind |
| **Citi Ad Agency** | Web design agency, since exited. Priced per project rather than by page count. Sites for Zerny Experiential, Nova College, Harmattan Renewables, WindAC (SAWEA / Windaba), Boston Private, Hamptons, Hartford House Preparatory and Harrington Primary — built there, no longer maintained by me. | WordPress, HTML / CSS / JS |

### Things I built to learn

| Project | What it is | Stack |
| --- | --- | --- |
| **llm-from-scratch** | A GPT built twice. Stage 1 is NumPy with hand-written reverse-mode autodiff; stage 2 is the same model on PyTorch tensors. Copy stage 1's weights across and the logits agree to 9e-08. | NumPy, PyTorch |
| **aviator-rng-lab** | A falsifiable experiment on whether a live crash game's outcome sequence carries any structure. Set up so that a negative result is believable. | Python, pandas |
| [**whatsapp-bot-template**](https://github.com/TheC0deJunkie/whatsapp-bot-template) | Provider-agnostic WhatsApp bot skeleton pulled out of a production system: 16-step webhook pipeline, Prisma session store, numbered-menu UX. | TypeScript, Express, Prisma |

## 🛠️ How I build

Next.js is the default, with Tailwind and shadcn/ui almost every time. Auth is one of the few things
I'd rather write myself than plug in, so I stay away from Clerk and providers like it. Prices, copy
and config go in JSON as a single source of truth rather than being scattered through pages.
Anything meant to run at a till or in a crowd gets built offline-first.

Alongside the day-to-day tools I keep a small library of Claude skills for my own use:
human-writing, product-ui-design, presentation-strategy, and a business-coach skill built on
Chris Do, Alex Hormozi, Vusi Thembekwayo and Phil M. Jones.

## 💻 Stack

![Next.js](https://img.shields.io/badge/Next.js-000?logo=nextdotjs&logoColor=fff)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss&logoColor=fff)
![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=fff)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)
![PostgreSQL](https://img.shields.io/badge/Postgres-4169E1?logo=postgresql&logoColor=fff)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=fff)
![Neon](https://img.shields.io/badge/Neon-00E599?logo=neon&logoColor=000)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=fff)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=000)
![Vercel](https://img.shields.io/badge/Vercel-000?logo=vercel&logoColor=fff)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=fff)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=fff)
![Twilio](https://img.shields.io/badge/Twilio-F22F46?logo=twilio&logoColor=fff)
![WhatsApp](https://img.shields.io/badge/WhatsApp%20Cloud%20API-25D366?logo=whatsapp&logoColor=fff)
![Paystack](https://img.shields.io/badge/Paystack-011B33?logo=paystack&logoColor=fff)
![WordPress](https://img.shields.io/badge/WordPress-21759B?logo=wordpress&logoColor=fff)

## 📊 GitHub

<p align="left">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=TheC0deJunkie&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub stats" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TheC0deJunkie&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />
</p>

## 📫 Contact

Open to client work and collaboration. WhatsApp is the fastest way to reach me.

- 💬 [+27 68 081 5781](https://wa.me/27680815781) — WhatsApp
- ✉️ [khulekani.zondi704@gmail.com](mailto:khulekani.zondi704@gmail.com)
- 💼 [linkedin.com/in/khulekani-shaun-mpanza1](https://www.linkedin.com/in/khulekani-shaun-mpanza1)
- 🌐 [citiadagency.co.za](https://citiadagency.co.za)

<sub>Durban, KwaZulu-Natal.</sub>
