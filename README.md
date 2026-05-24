# Christine Lampong — Portfolio Site

A professional one-page portfolio for deployment on Vercel.

## 🚀 Deploy to Vercel (3 steps)

### Option A — Vercel CLI (fastest)
```bash
# 1. Install Vercel CLI
npm install -g vercel

# 2. Navigate to this folder
cd portfolio

# 3. Deploy
vercel
```
Follow the prompts — choose "yes" to defaults. Your site will be live at a `.vercel.app` URL in under 60 seconds.

### Option B — Vercel Dashboard (no code needed)
1. Go to [vercel.com](https://vercel.com) and sign up (free)
2. Click **"Add New Project"**
3. Drag and drop this entire `portfolio` folder — OR connect your GitHub repo
4. Click **Deploy**
5. Done ✅

## 📁 File Structure
```
portfolio/
├── index.html        ← Main portfolio page (edit this)
├── vercel.json       ← Vercel config (don't touch)
├── package.json      ← Project metadata
└── README.md         ← This file
```

## ✏️ How to Customize

### Update your contact details
Search for `lampong.tine@gmail.com` and `+63 969 583 3876` in `index.html` and replace.

### Add your LinkedIn URL
Find `linkedin.com/in/christinelampong` and update with your real URL.

### Add your CV as a download
Drop your `CV_Lampong_OnePage.pdf` file into the `portfolio/` folder.
The "Download CV" button already links to it.

### Change colors
At the top of `index.html`, find the `:root {}` block and update:
- `--gold` and `--gold-lt` → your accent color
- `--ink` → heading color
- `--cream` → background color

## 🌐 Custom Domain (optional)
In your Vercel dashboard → Project Settings → Domains → Add your domain.

## 💡 Tips
- The site is fully mobile responsive
- All animations use CSS — no heavy libraries
- Page loads fast — pure HTML/CSS/JS, no frameworks
- To update content, just edit `index.html` and re-deploy (`vercel --prod`)
