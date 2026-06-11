# 🎓 TypeScript + Playwright AI Tutor

An interactive AI-powered tutor for learning TypeScript and Playwright Test Automation.
Built for Indian students — teaches with desi analogies, quizzes, and real examples.

---

## 🚀 Deploy in 4 Steps (Free — No coding needed)

### Step 1 — Get your Anthropic API Key
1. Go to https://console.anthropic.com
2. Sign up with your email (free)
3. Go to **API Keys** → click **Create Key**
4. Copy the key (starts with `sk-ant-...`) — save it somewhere safe

> 💡 New accounts get free credits — enough for hundreds of student sessions.

---

### Step 2 — Upload this project to GitHub
1. Go to https://github.com and sign up (free)
2. Click the **+** icon (top right) → **New repository**
3. Name it: `ts-playwright-tutor`
4. Keep it **Public** → click **Create repository**
5. Click **uploading an existing file** link
6. Drag and drop ALL the files from this ZIP:
   - `api/chat.js`
   - `public/index.html`
   - `vercel.json`
   - `README.md`
7. Click **Commit changes**

---

### Step 3 — Deploy on Vercel (Free hosting)
1. Go to https://vercel.com and sign up with your GitHub account
2. Click **Add New Project**
3. Select your `ts-playwright-tutor` repository → click **Import**
4. Click **Deploy** (leave all settings as default)
5. Wait ~1 minute — Vercel builds and deploys automatically

---

### Step 4 — Add your API Key to Vercel
1. In Vercel dashboard, go to your project → **Settings** → **Environment Variables**
2. Click **Add New**
   - Name:  `ANTHROPIC_API_KEY`
   - Value: `sk-ant-xxxxxxxxxxxxxxxx`  ← paste your key here
3. Click **Save**
4. Go to **Deployments** → click the 3 dots on latest deploy → **Redeploy**

**Done! 🎉** Your tutor is live at `https://your-project-name.vercel.app`

---

## 📤 Share with Students
Just send them your Vercel URL — no login, no setup, no API key needed for them.
Example: `https://ts-playwright-tutor.vercel.app`

---

## 💰 Cost Estimate
- GitHub: **Free**
- Vercel hosting: **Free**
- Anthropic API: ~₹0.10–0.30 per student per full session (very cheap)
- For 50 students × 10 sessions = roughly ₹150–500 total

---

## 🛠 Project Structure
```
ts-playwright-tutor/
├── api/
│   └── chat.js          ← Backend proxy (hides your API key)
├── public/
│   └── index.html       ← The tutor UI
├── vercel.json          ← Deployment config
└── README.md            ← This file
```

---

## ❓ Troubleshooting
| Problem | Fix |
|---|---|
| "API error" on first load | Check API key is saved in Vercel environment variables |
| Page not loading | Make sure all 3 files are uploaded to GitHub |
| Tutor not responding | Redeploy on Vercel after adding the API key |
| Want a custom domain | In Vercel → Settings → Domains → add your domain |
