# ⚡ MCAT Mastery — MilesDown AI Study App

An AI-powered MCAT study app that generates **unlimited questions on demand** from all 92 pages of the MilesDown MCAT Review Sheets.

## 🎯 Features

- **Unlimited AI Questions** — Claude generates fresh, exam-quality MCQs from your actual notes
- **3000+ Questions Possible** — 48 topics × ~25 questions each = unlimited coverage
- **SM-2 Spaced Repetition** — Scientifically proven algorithm for long-term retention
- **Progressive Hints** — 2-level hint system before revealing the answer
- **Worked Solutions** — Every question has a full explanation + distractor analysis
- **Progress Dashboard** — Heatmap, accuracy by subject, streak tracker
- **Reference Notes** — All 92 pages searchable and accessible offline
- **PWA** — Install on Android home screen, works offline after first load
- **XP & Levels** — Gamified learning with experience points

## 📁 Files

| File | Purpose |
|------|---------|
| `index.html` | Complete app (self-contained, ~2000 lines) |
| `manifest.json` | PWA installability |
| `sw.js` | Service worker (offline support) |
| `README.md` | This file |

## 🚀 Setup in 5 Minutes

### Step 1: Create GitHub Account
1. Go to **github.com** on your Pixel
2. Sign up (free)
3. Tap **+** → **New repository**
4. Name: `mcat-app` 
5. Check ✅ **Add a README file**
6. Tap **Create repository**

### Step 2: Enable GitHub Pages
1. In your new repo, tap **Settings**
2. Scroll to **Pages**
3. Source: **Deploy from a branch**
4. Branch: **main** → **Save**

### Step 3: Upload Files
1. In your repo, tap **Add file** → **Upload files**
2. Upload all 4 files from Claude (index.html, manifest.json, sw.js, README.md)
3. Tap **Commit changes**
4. Wait ~60 seconds

### Step 4: Get Your URL
Your app is now live at:
`https://YOUR-USERNAME.github.io/mcat-app`

### Step 5: Install as App on Your Pixel
1. Open the URL in **Chrome** on your Pixel Pro
2. Tap **⋮ Menu** (three dots)
3. Tap **Add to Home screen**
4. Name it "MCAT Mastery" → **Add**
5. Icon appears on your home screen! ✅

## 🔑 API Key Setup

1. Go to **console.anthropic.com** (free account)
2. Create an API key
3. Open the app → it will prompt you to enter the key
4. Your key is stored **only on your device** — never sent anywhere except Anthropic

## 💡 How to Study

1. **Pick a subject** → pick a topic
2. **Set difficulty** (Easy / Medium / Hard)  
3. **Set question count** (10, 20, 30, or 50)
4. **Tap a topic** → AI generates questions in ~10 seconds
5. Answer questions → use hints if needed
6. After answering, **rate difficulty** (Easy/OK/Hard/Again) for spaced repetition
7. Review wrong answers at the end
8. Track progress in the Dashboard

## 📚 Curriculum Coverage

All 92 pages covered:

**General Chemistry** (Pages 4-15) — 12 topics
**Organic Chemistry** (Pages 16-27) — 12 topics  
**Biology** (Pages 28-39) — 12 topics
**Biochemistry** (Pages 40-51) — 12 topics
**Behavioral Sciences** (Pages 52-63) — 12 topics
**Physics & Math** (Pages 64-75) — 12 topics

Plus Appendices A-Q (Pages 76-92)

## 🔢 Question Capacity

- 72 topics × 10 questions = **720 unique questions per pass**
- 72 topics × 50 questions = **3,600 unique questions per pass**  
- AI generates NEW questions each session = **effectively unlimited**
- Mix of: recall, application, analysis, clinical reasoning

---

Built with Claude AI + Anthropic API  
MilesDown MCAT Review Sheets (Revised 2019)
