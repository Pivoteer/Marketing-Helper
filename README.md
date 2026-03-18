# Marketing Co-Pilot

AI-powered marketing app for local service businesses.

## Project structure

```
marketing-copilot/
├── api/
│   └── chat.js     ← secure backend (keeps API key off browser)
├── index.html      ← full frontend app
├── vercel.json     ← minimal Vercel config
└── README.md
```

---

## Deploy to Vercel

### Step 1 — Get your Anthropic API key
1. Go to https://console.anthropic.com
2. Sign in → **API Keys** → **Create Key**
3. Copy it (starts with `sk-ant-...`)

### Step 2 — Push to GitHub & deploy
**Option A — GitHub (recommended):**
1. Create a free GitHub account at github.com
2. Create a new repository, upload this folder's contents
3. Go to vercel.com → **Add New Project** → import your GitHub repo
4. Click **Deploy** (no build settings needed)

**Option B — Vercel CLI:**
1. Install Node.js from nodejs.org
2. Run: `npm install -g vercel`
3. In this folder run: `vercel`
4. Follow the prompts

### Step 3 — Add your API key in Vercel
1. Go to your project on vercel.com
2. **Settings → Environment Variables**
3. Add: Name = `ANTHROPIC_API_KEY`, Value = your key
4. Make sure **Production** checkbox is ticked
5. Click Save
6. Go to **Deployments** → three dots → **Redeploy**

Your app is now live at your Vercel URL!
