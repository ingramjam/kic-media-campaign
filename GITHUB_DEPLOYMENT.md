# GitHub Deployment Guide

## 📦 Repository Ready for Push

Your KIC Media Campaign repository is now fully configured and ready to push to GitHub.

### ✅ What's Included

**Core Files:**
- ✅ `.gitignore` - Git configuration
- ✅ `LICENSE` - MIT License
- ✅ `README.md` - Main documentation (updated for GitHub)
- ✅ `TEMPLATES.md` - Landing pages guide
- ✅ `index.html` - Interactive campaign dashboard

**Documentation:**
- ✅ `QUICK_REFERENCE.md` - Team cheat sheet
- ✅ `SOCIAL_SPECS.md` - Platform specifications
- ✅ `PRODUCTION_TIMELINE.md` - Timeline
- ✅ `SYSTEM_SUMMARY.md` - System documentation
- ✅ `GETTING_STARTED.md` - Action items

**Assets:**
- ✅ `asset-tracker.json` - Ad variations database
- ✅ `LANDING_PAGES_SUMMARY.html` - Template preview

**Landing Pages** (3 production-ready templates):
- ✅ `landing-pages/genz-landing.html` - Gen Z template
- ✅ `landing-pages/retro-90s-landing.html` - 90s template
- ✅ `landing-pages/corporate-landing.html` - Corporate template
- ✅ `landing-pages/README.md` - Landing page documentation

---

## 🚀 Push to GitHub

### Step 1: Authenticate with GitHub

You have two options:

**Option A: HTTPS (Password-less)**
```bash
# GitHub Personal Access Token (recommended)
# Visit: https://github.com/settings/tokens
# Create token with 'repo' scope
```

**Option B: SSH**
```bash
# Already configured on your machine
ssh -T git@github.com  # Test connection
```

### Step 2: Push Repository

```bash
# Navigate to repo
cd /Users/james/211\ rsvp/kic-media-campaign

# Push to GitHub
git push -u origin main
```

### Step 3: Verify on GitHub

After push completes:
1. Visit: `https://github.com/ingramjam/kic-media-campaign`
2. Verify all 16 files are there
3. README.md displays correctly
4. landing-pages/ folder visible

---

## 🌐 Enable GitHub Pages (Optional but Recommended)

### Automatic Hosting for Landing Pages

GitHub Pages allows you to host the landing pages directly from the repo:

**Steps:**
1. Go to repo → **Settings** → **Pages**
2. Under "Source," select:
   - Branch: `main`
   - Folder: `/ (root)`
3. Click **Save**
4. Your site will be live at: `https://ingramjam.github.io/kic-media-campaign`

**Live Landing Page URLs:**
- Gen Z: `https://ingramjam.github.io/kic-media-campaign/landing-pages/genz-landing.html`
- 90s: `https://ingramjam.github.io/kic-media-campaign/landing-pages/retro-90s-landing.html`
- Corporate: `https://ingramjam.github.io/kic-media-campaign/landing-pages/corporate-landing.html`

---

## 🎯 Dashboard Updates

### Configure "Create Template" Links

To make the dashboard link to templates on GitHub, update `index.html`:

**Raw Content URLs** (always works):
```html
<a href="https://raw.githubusercontent.com/ingramjam/kic-media-campaign/main/landing-pages/genz-landing.html" target="_blank">
  View Gen Z Template
</a>
```

**GitHub Pages URLs** (requires Pages enabled):
```html
<a href="https://ingramjam.github.io/kic-media-campaign/landing-pages/genz-landing.html" target="_blank">
  View Gen Z Template
</a>
```

### View Dashboard

Once pushed, view the dashboard at:
- Local: `open landing-pages/index.html` (relative path)
- GitHub: `https://raw.githubusercontent.com/ingramjam/kic-media-campaign/main/index.html`
- GitHub Pages: `https://ingramjam.github.io/kic-media-campaign/index.html`

---

## 📊 Repository Structure on GitHub

```
ingramjam/kic-media-campaign
├── 📄 README.md (main overview)
├── 📄 TEMPLATES.md (landing pages quick ref)
├── 📄 QUICK_REFERENCE.md
├── 📄 SOCIAL_SPECS.md
├── 📄 PRODUCTION_TIMELINE.md
├── 📄 SYSTEM_SUMMARY.md
├── 📄 GETTING_STARTED.md
├── 📄 LICENSE
├── 📄 .gitignore
├── 🌐 index.html (dashboard)
├── 🌐 LANDING_PAGES_SUMMARY.html
├── 📊 asset-tracker.json
└── 📁 landing-pages/
    ├── 📄 README.md
    ├── 🌐 genz-landing.html
    ├── 🌐 retro-90s-landing.html
    └── 🌐 corporate-landing.html
```

---

## 🔗 Share with Team

Once deployed, share these links:

**For Team Dashboard:**
- Raw HTML: https://raw.githubusercontent.com/ingramjam/kic-media-campaign/main/index.html
- Repository: https://github.com/ingramjam/kic-media-campaign

**For Landing Pages:**
- Gen Z: https://ingramjam.github.io/kic-media-campaign/landing-pages/genz-landing.html
- 90s: https://ingramjam.github.io/kic-media-campaign/landing-pages/retro-90s-landing.html
- Corporate: https://ingramjam.github.io/kic-media-campaign/landing-pages/corporate-landing.html

**For Documentation:**
- Main README: https://github.com/ingramjam/kic-media-campaign/blob/main/README.md
- Landing Pages Guide: https://github.com/ingramjam/kic-media-campaign/blob/main/TEMPLATES.md
- Quick Reference: https://github.com/ingramjam/kic-media-campaign/blob/main/QUICK_REFERENCE.md

---

## ✅ Pre-Push Checklist

- ✅ All 16 files committed locally
- ✅ Git configured with user.name and user.email
- ✅ Remote origin added (origin → github.com/ingramjam/kic-media-campaign)
- ✅ Files staged and committed (commit hash: 84e055c)
- ✅ Main branch set as default
- ✅ License included (MIT)
- ✅ .gitignore configured

---

## 🔐 Authentication Methods

### HTTPS with Personal Access Token (Recommended)

1. Create token: https://github.com/settings/tokens
   - Scopes: `repo` (full control of private repositories)
   - Expiration: 90 days or custom
2. Copy token
3. When prompted, use token as password:
   ```bash
   git push -u origin main
   # Username: ingramjam
   # Password: [paste your token]
   ```

### SSH (Alternative)

If SSH key is already set up:
```bash
git remote set-url origin git@github.com:ingramjam/kic-media-campaign.git
git push -u origin main
```

---

## 📝 Next Steps

1. **Push Repository**
   ```bash
   git push -u origin main
   ```

2. **Enable GitHub Pages** (Settings → Pages → main branch)

3. **Update Dashboard Links**
   - Edit `index.html` Landing Pages tab
   - Point to GitHub Pages URLs

4. **Share with Team**
   - Send GitHub repo URL
   - Send raw template URLs
   - Send GitHub Pages URLs

5. **Monitor Campaign**
   - Track leads via HubSpot
   - Update asset-tracker.json with ad performance
   - Commit changes back to repo

---

## 📞 Support

**Common Issues:**

**401 Unauthorized**
- Verify GitHub credentials
- Check personal access token is still valid
- Try SSH authentication instead

**Branch Mismatch**
- Ensure `main` branch exists: `git branch -M main`
- Check remote URL: `git remote -v`

**Large Files**
- GitHub limits to 100MB per file
- All landing pages are <100KB ✅

---

**Deployment Status:** ✅ Ready to Push  
**Last Updated:** December 9, 2025  
**Files Committed:** 16  
**Commit Hash:** 84e055c
