# Muhammad Awais — Portfolio Website

Clean, professional single-page portfolio for AI/ML/Physics roles.
Live at: **https://cmsawais.github.io**

---

## 1. Add Your Profile Photo

**Option A — Automated (recommended):**
```bash
python remove_bg.py "C:\path\to\your\photo.jpg"
# Outputs assets/profile.png with background removed
```

**Option B — Free online:**
1. Go to https://www.remove.bg  (free, instant)
2. Upload your photo → download result
3. Save as `assets/profile.png`

---

## 2. Deploy to GitHub Pages (Free)

### Step 1 — Create the repo
1. Go to https://github.com/new
2. Repository name: **`cmsawais.github.io`** (must match your username exactly)
3. Set to **Public**
4. Click **Create repository**

### Step 2 — Push the files
```bash
cd C:\Users\awais\Documents\portfolio
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/cmsawais/cmsawais.github.io.git
git push -u origin main
```

### Step 3 — Enable Pages
1. Go to your repo → **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / **root**
4. Click **Save**

Your site will be live at `https://cmsawais.github.io` within ~2 minutes.

---

## 3. Add to Resume

```
Portfolio: https://cmsawais.github.io
```

---

## Customization

| What to change | Where |
|---|---|
| Email address | Search `mailto:` in index.html |
| Profile photo | `assets/profile.png` |
| Project descriptions | `#projects` section in index.html |
| Skills / tags | `#skills` section in index.html |
| About text | `#about` section in index.html |
