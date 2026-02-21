# Blake Tuttle — The Cut
### Private 90-Day AI Training & Nutrition Platform

---

## 🔒 Access
This app is PIN-protected. Default PIN: `1990`
To change it: open `index.html`, find `const GATE_PIN = '1990'` near the top and update it.

---

## 🚀 Deploy to Vercel (Step by Step)

### Step 1 — Push to GitHub

1. Go to [github.com](https://github.com) and sign in
2. Click the **+** icon → **New repository**
3. Name it: `blake-tuttle-cut`
4. Set to **Private** ✅
5. Click **Create repository**
6. On your computer, open Terminal and run:

```bash
cd path/to/btc-deploy
git init
git add .
git commit -m "Initial deploy — Blake Tuttle Cut"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/blake-tuttle-cut.git
git push -u origin main
```

---

### Step 2 — Connect to Vercel

1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **Add New → Project**
3. Find `blake-tuttle-cut` in your GitHub repos → click **Import**
4. Leave all settings as default
5. Click **Deploy**
6. Vercel gives you a live URL like: `blake-tuttle-cut.vercel.app`

---

### Step 3 — Add to iPhone Home Screen

1. Open the Vercel URL in **Safari** on your iPhone
2. Enter your PIN
3. Tap the **Share button** (box with arrow) → **Add to Home Screen**
4. Name it **"The Cut"** → tap **Add**
5. Open from home screen → tap 🔔 → **Enable Push Notifications**

---

### Step 4 — Auto-Deploy on Every Update

Every time you push a change to GitHub, Vercel automatically redeploys.

```bash
# Make a change, then:
git add .
git commit -m "Updated program"
git push
```
Vercel rebuilds and deploys in ~30 seconds. Your URL stays the same.

---

### Step 5 — Custom Domain (Optional)

To use `cut.blaketuttlecreative.com`:
1. In Vercel → your project → **Settings → Domains**
2. Add `cut.blaketuttlecreative.com`
3. Vercel gives you DNS records to add in your domain registrar
4. Done — your private app lives on your own domain

---

## 📁 File Structure

```
btc-deploy/
├── index.html      ← Full app (PIN gate + all 7 AI systems)
├── vercel.json     ← Vercel deployment config
└── README.md       ← This file
```

---

## 🔐 Privacy

- Repo is **private** on GitHub — only you can see it
- `vercel.json` sets `noindex` headers — Google can't find it
- PIN gate prevents anyone who stumbles on the URL from accessing it
- `no-store` cache header prevents browsers caching sensitive data

---

## 💡 Features

| Tab | What it does |
|-----|-------------|
| 🏋️ **Today** | Log workouts, weight, macros. Auto-adjusts volume for recovery & missed sessions |
| 🍽️ **Smart Meals** | Cal AI screenshot import + Claude generates personalized meal ideas |
| 💤 **Recovery** | Daily ratings → AI training recommendation for tomorrow |
| 📈 **Progress** | Weight chart, lift tracker, plateau detection, progress photos |
| 🧠 **Coach** | Full-context AI coach wired into all your data in real time |

---

Built for Blake Tuttle Creative · Private use only
