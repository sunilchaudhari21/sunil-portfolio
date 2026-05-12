# 🚀 Sunil Chaudhari — Personal Portfolio Website

> **QA Release Manager | Scrum Master | Delivery & Governance Leader**  
> A premium, immersive, single-page portfolio website built with pure HTML, CSS, and JavaScript.

[![Deployed on Vercel](https://img.shields.io/badge/Deployed%20on-Vercel-000000?style=flat&logo=vercel&logoColor=white)](https://vercel.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

## 📸 Preview

> A futuristic enterprise-themed dark portfolio featuring animated particle backgrounds, typewriter effects, scroll-triggered reveals, and glassmorphism UI — inspired by product landing pages from Vercel, Linear, and Stripe.

---

## ✨ Features

- **Animated Particle Background** — Floating particle constellation that reacts to the page
- **Custom Cursor** — Cyan cursor with a smooth trailing ring effect
- **Typewriter Effect** — Rotating dynamic taglines in the hero section
- **Live Counters** — Animated statistics (15+ years, 99.9% success rate, etc.)
- **Scroll-Triggered Reveals** — Sections fade and slide in as you scroll
- **Skill Bar Animations** — Progress bars animate on scroll entry
- **Marquee Ticker** — Infinite scrolling tech stack strip
- **Fully Responsive** — Works on desktop, tablet, and mobile
- **Zero Dependencies** — No frameworks, no build tools, no npm install needed
- **One File Deploy** — Single `index.html` — drop anywhere and it works

---

## 📁 Project Structure

```
sunil-portfolio/
│
├── index.html        # Complete portfolio — all HTML, CSS & JS in one file
└── README.md         # This file
```

> **Note:** This is an intentionally single-file project for simplicity and portability. All styles and scripts are embedded inline.

---

## 🗂️ Sections

| # | Section | Description |
|---|---------|-------------|
| 1 | **Hero** | Name, animated taglines, stats counters, CTA buttons |
| 2 | **Marquee** | Infinite scrolling tech stack ticker |
| 3 | **About** | Bio, career summary, skill tags |
| 4 | **Timeline** | Interactive career progression from 2001 to present |
| 5 | **Skills** | Animated skill cards with progress bars (9 competency areas) |
| 6 | **Experience** | All 5 employers with full bullet details and tech tags |
| 7 | **Projects** | 6 featured project case-study cards with impact metrics |
| 8 | **Quote** | Personal philosophy band |
| 9 | **Awards** | 6 recognition cards |
| 10 | **Certifications** | CSM®, CSPO, B.Sc., Azure DevOps |
| 11 | **Contact** | Contact info + message form |
| 12 | **Footer** | Links, copyright |

---

## 🎨 Design System

### Color Palette
| Token | Hex | Usage |
|-------|-----|-------|
| `--bg` | `#070B14` | Page background |
| `--bg2` | `#0B1120` | Card backgrounds |
| `--cyan` | `#06B6D4` | Primary accent, headings |
| `--emerald` | `#10B981` | Secondary accent, success states |
| `--purple` | `#8B5CF6` | Tertiary accent |
| `--silver` | `#F8FAFC` | Primary text |
| `--muted` | `#64748B` | Secondary text |

### Typography
| Font | Usage |
|------|-------|
| **Syne** (Google Fonts) | Display headings, names, titles |
| **DM Sans** (Google Fonts) | Body text, descriptions |
| **JetBrains Mono** (Google Fonts) | Labels, years, code-like elements |

---

## 🛠️ Tech Stack

```
Frontend:   HTML5 · CSS3 · Vanilla JavaScript (ES6+)
Fonts:      Google Fonts (Syne, DM Sans, JetBrains Mono)
Hosting:    Vercel (Free Tier)
Build:      None required — zero build step
```

---

## 🚀 Deployment — Vercel (Recommended)

### Prerequisites
- A free [GitHub](https://github.com) account
- A free [Vercel](https://vercel.com) account (sign up with GitHub)

### Step-by-Step

**1. Prepare the file**
```
Rename:  sunil-chaudhari-portfolio.html  →  index.html
```

**2. Push to GitHub**
1. Go to [github.com](https://github.com) → **New Repository**
2. Name it `sunil-portfolio` → **Create repository**
3. Click **"uploading an existing file"**
4. Upload `index.html` and `README.md`
5. Click **Commit changes**

**3. Deploy on Vercel**
1. Go to [vercel.com](https://vercel.com) → **Add New → Project**
2. Click **Import** next to your `sunil-portfolio` repository
3. Leave all settings as default
4. Click **Deploy**
5. ✅ Live in ~30 seconds at `sunil-portfolio.vercel.app`

### Auto-Deploy
Every time you push an update to GitHub, Vercel automatically redeploys. No manual steps needed.

---

## 🌐 Custom Domain (Optional)

1. Purchase a domain (e.g. `sunilchaudhari.com` from GoDaddy / Namecheap — ~₹800/year)
2. In Vercel → Your Project → **Settings → Domains**
3. Add your domain and follow the DNS configuration steps
4. Vercel provides **free SSL (HTTPS)** automatically

**Suggested domains:**
- `sunilchaudhari.com`
- `sunilqa.com`
- `releasewithsunil.com`

---

## ✏️ Customization Guide

All content is in `index.html`. Here are the key areas to update:

### Update Contact Details
Search for `sunilibn@gmail.com` and `+91-9657724967` to update email/phone.

### Update LinkedIn URL
Search for `linkedin.com/in/sunilchaudhari21` and replace with your profile URL.

### Add Resume PDF Download
1. Upload your `Sunil_Chaudhari_CV.pdf` to the GitHub repo
2. In `index.html`, find `<a href="#" class="btn-primary">↓ Download Resume</a>`
3. Replace `#` with `./Sunil_Chaudhari_CV.pdf`

### Change Hero Stats
Search for `data-count` attributes in the Hero section:
```html
<div class="stat-num" data-count="15" data-suffix="+">
<div class="stat-num" data-count="500" data-suffix="+">
<div class="stat-num" data-count="99.9" data-suffix="%" data-decimal="1">
<div class="stat-num" data-count="28" data-suffix="+">
```

### Update Typewriter Lines
Search for `const lines=` in the `<script>` section:
```javascript
const lines = [
  'QA Release Manager',
  'Certified Scrum Master (CSM®)',
  'Zero-Downtime Delivery Leader',
  'Release Governance Specialist',
  '15+ Years of QA Excellence'
];
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Layout Changes |
|------------|---------------|
| `> 900px` | Full 2–3 column grids, side-by-side layouts |
| `≤ 900px` | Single column, nav links hidden, stacked grids |
| `≤ 600px` | Compact hero stats (2×2 grid), single column cards |

---

## 🔮 Future Enhancements

- [ ] Add resume PDF download link
- [ ] Connect contact form to [Resend](https://resend.com) or [Formspree](https://formspree.io)
- [ ] Add Calendly embed for interview scheduling
- [ ] Add Google Analytics tracking
- [ ] Add dark/light mode toggle
- [ ] Add blog section (Release Management articles)
- [ ] Convert to Next.js + TypeScript for scalability
- [ ] Add LinkedIn profile badge widget

---

## 👤 About Sunil Chaudhari

**Quality & Release Manager | Certified Scrum Master (CSM® | CSPO)**

15+ years of software delivery excellence across HealthTech, AdTech, and Enterprise SaaS. Currently leading release governance at **Bajaj Finserv Health**, Pune — achieving 99.9% deployment success with zero unplanned downtime across 10+ microservices and 5+ product squads.

📧 sunilibn@gmail.com  
📞 +91-9657724967  
📍 Pune, India  
🔗 [linkedin.com/in/sunilchaudhari21](https://linkedin.com/in/sunilchaudhari21)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

<p align="center">Built with ❤️ for showcasing 15+ years of QA & Release Management excellence</p>
