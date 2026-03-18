# Marketing Co-Pilot

AI-powered marketing app for local service businesses.

---

## Deploy to Vercel (5 minutes)

### Step 1 — Get your Anthropic API key
1. Go to https://console.anthropic.com
2. Sign up or log in
3. Click **API Keys** → **Create Key**
4. Copy the key (starts with `sk-ant-...`)

### Step 2 — Deploy to Vercel
1. Go to https://vercel.com and sign up (free) with GitHub
2. Click **Add New Project**
3. Choose **"Deploy from a folder"** or drag this entire folder in
   - Or: push this folder to a GitHub repo and import it
4. Click **Deploy**

### Step 3 — Add your API key
1. In your Vercel project, go to **Settings → Environment Variables**
2. Add a new variable:
   - **Name:** `ANTHROPIC_API_KEY`
   - **Value:** your key from Step 1
3. Click **Save**
4. Go to **Deployments** → click the three dots → **Redeploy**

Your app is live! Share the URL with anyone.

---

## Project structure

```
marketing-copilot/
├── api/
│   └── chat.js         # Secure backend — keeps API key off the browser
├── public/
│   └── index.html      # Full frontend app
├── vercel.json         # Vercel routing config
└── README.md
```

---

## Features
- Business profile setup
- 90-day growth roadmap generator
- Competitor research & analysis
- Content generator (SEO blog, social, ads, web copy)
- Site & presence analyzer with scored recommendations
- Marketing task tracker with AI-generated tasks
