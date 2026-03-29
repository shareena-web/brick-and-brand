# Brick & Brand — Style as Strategy
## Deploy to Vercel in 5 Steps

---

### What's in this folder
- `public/index.html` — the full chat interface
- `api/chat.js` — the secure backend that calls the AI
- `vercel.json` — deployment config
- `README.md` — this file

---

### Step 1 — Get your Anthropic API Key
1. Go to https://console.anthropic.com
2. Sign in (or create a free account)
3. Click **API Keys** in the left sidebar
4. Click **Create Key** — copy it and save it somewhere safe

---

### Step 2 — Create a free Vercel account
1. Go to https://vercel.com
2. Sign up with Google or GitHub (free)

---

### Step 3 — Deploy the project
1. On Vercel dashboard, click **Add New → Project**
2. Click **"Deploy from your computer"** or drag this entire folder into the upload area
3. Vercel will detect the settings automatically
4. Click **Deploy**

---

### Step 4 — Add your API Key (critical!)
1. In your Vercel project, go to **Settings → Environment Variables**
2. Add a new variable:
   - **Name:** `ANTHROPIC_API_KEY`
   - **Value:** (paste your key from Step 1)
3. Click **Save**
4. Go to **Deployments** and click **Redeploy** so the key takes effect

---

### Step 5 — Share your link!
Vercel gives you a live URL like `brick-and-brand.vercel.app`
Share this link with your webinar attendees.

---

### Need help?
Email: hello@brickandbrand.com
