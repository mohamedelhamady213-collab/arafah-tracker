# رحلة يوم عرفة 🌙
## Arafah Day Islamic Tracker

A beautiful, spiritual Islamic web app to help Muslims track and complete worship acts throughout the Day of Arafah (9th Dhul Hijjah).

---

## ✨ Features

- **Full Worship Timeline** — 18 acts of worship across 5 time periods (Before Fajr → Before Maghrib)
- **Smart Progress Tracking** — Sticky progress bar with percentage and motivational messages
- **Tasbeeh Counter** — Digital dhikr counter for 4 types of remembrance (Subhanallah, Alhamdulillah, Allahu Akbar, La ilaha illallah)
- **Dua Notes** — Save personal duas and names to pray for, stored locally
- **Rotating Islamic Quotes** — Auto-rotating inspirational reminders
- **Completion Celebration** — Full-screen celebration when all tasks are done
- **Auto-Save** — All progress saved instantly to LocalStorage
- **Dark/Light Mode** — Beautiful toggle for both modes
- **RTL Arabic Layout** — Full right-to-left Arabic UI
- **Fully Responsive** — Mobile-first design for phones, tablets, and desktops

---

## 🛠️ Tech Stack

- **Next.js 14** (App Router, Static Export)
- **React 18**
- **Tailwind CSS v3**
- **Framer Motion v11** (animations)
- **Lucide React** (icons)
- **Google Fonts — Cairo**
- **LocalStorage** (no backend needed)

---

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Install & Run

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Open http://localhost:3000
```

### Build for Production

```bash
npm run build
```

This creates a static export in the `out/` directory.

---

## ☁️ Deployment

### Vercel (Recommended — Easiest)

1. Push your code to GitHub
2. Go to [vercel.com](https://vercel.com) and sign in
3. Click **"New Project"** → Import your GitHub repo
4. Vercel auto-detects Next.js — click **Deploy**
5. Done! Your site is live 🎉

### Netlify

1. Push to GitHub
2. Go to [netlify.com](https://netlify.com) → **"New site from Git"**
3. Connect your repo
4. Set build command: `npm run build`
5. Set publish directory: `out`
6. Click **Deploy**

### GitHub Pages

1. Install gh-pages: `npm install --save-dev gh-pages`
2. Add to `package.json` scripts:
   ```json
   "deploy": "next build && touch out/.nojekyll && gh-pages -d out"
   ```
3. Run: `npm run deploy`

---

## 📁 Project Structure

```
arafah-tracker/
├── app/
│   ├── layout.tsx          # Root layout with SEO metadata
│   ├── page.tsx            # Main page (state management)
│   └── globals.css         # Global styles & Islamic pattern
├── components/
│   ├── HeroSection.tsx     # Hero with animated stars & mosque
│   ├── StickyProgress.tsx  # Sticky progress bar
│   ├── Timeline.tsx        # Grouped worship timeline
│   ├── TaskCard.tsx        # Individual task card
│   ├── TasbeehCounter.tsx  # Dhikr counter modal
│   ├── DuaNotes.tsx        # Dua notes modal
│   ├── QuoteRotator.tsx    # Rotating Islamic quotes
│   └── CompletionSection.tsx # Celebration screen
├── lib/
│   └── tasks.ts            # All task data & quotes
├── tailwind.config.js
├── next.config.js
└── README.md
```

---

## 🎨 Design System

| Token | Value |
|-------|-------|
| Primary Gold | `#c9a450` |
| Light Gold | `#e8d5a3` |
| Background | `#030b06` |
| Card | `rgba(8,28,16,0.7)` |
| Font | Cairo (Google Fonts) |

---

## 📱 Tested On

- ✅ iPhone (Safari)
- ✅ Android (Chrome)
- ✅ iPad
- ✅ Desktop Chrome/Firefox/Safari

---

## 🤲 May Allah accept from us and from you

> "ما من يوم أكثر أن يُعتق الله فيه عبداً من النار من يوم عرفة" — رواه مسلم

---

*Made with 💚 for the Muslim Ummah*
