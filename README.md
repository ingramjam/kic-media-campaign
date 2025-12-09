# KIC Media Campaign Management System

## Overview

This is the central hub for organizing and executing the **KIC Lead Generation Campaign** (Dec 29, 2025 - Feb 28, 2026) targeting Quit Vaping and Quit Smoking audiences across Meta, Google, and Retargeting platforms.

**Campaign Scope:**
- **Budget:** $26,000 ($16k Meta, $6k Google, $4k Retargeting)
- **Duration:** 62 days across 2 phases
- **Ad Variations:** 11+ distinct ad sets
- **Target Audiences:** 3 demographics × 3 aesthetic styles
- **Expected Output:** 1,500-2,000 qualified leads

---

## 🚀 Quick Start

### Option 1: View Dashboard Locally
```bash
# Clone this repository
git clone https://github.com/ingramjam/kic-media-campaign.git
cd kic-media-campaign

# Open in your browser
open index.html
```

### Option 2: View on GitHub
- **Dashboard:** View `index.html` directly in repo
- **Landing Pages:** See `landing-pages/` folder for all 3 templates
- **Documentation:** Browse all markdown files

## � Quick Links & Files

| File | Purpose | Link |
|------|---------|------|
| **Dashboard** | Interactive campaign overview | [`index.html`](./index.html) |
| **Landing Pages** | 3 conversion-optimized templates | [`landing-pages/`](./landing-pages/) |
| **Social Specs** | Platform dimensions & export guides | [`SOCIAL_SPECS.md`](./SOCIAL_SPECS.md) |
| **Timeline** | Week-by-week production schedule | [`PRODUCTION_TIMELINE.md`](./PRODUCTION_TIMELINE.md) |
| **Quick Ref** | One-page team cheat sheet | [`QUICK_REFERENCE.md`](./QUICK_REFERENCE.md) |
| **Getting Started** | Next steps & action items | [`GETTING_STARTED.md`](./GETTING_STARTED.md) |
| **Asset Tracker** | All ad variations database | [`asset-tracker.json`](./asset-tracker.json) |

**Launch Dashboard:** `open index.html` in your browser or visit the raw HTML file

---

## Campaign Structure

### Target Audiences
| Audience | Age | Aesthetic | Messaging | Platforms |
|----------|-----|-----------|-----------|-----------|
| **Gen Z** | 18-29 | Gen Z (Clean, Bold) | Testimonial, NY, Money | IG Reels, Stories, FB Reels |
| **Millennial** | 30-45 | Retro 90s (Nostalgic) | Testimonial, NY, Money | IG/FB Feed, Reels |
| **Gen X/Boomer** | 45+ | Corporate (Professional) | Testimonial, NY, Money | IG/FB Feed |

### Topics
- **Quit Vaping** (9 ad variations)
- **Quit Smoking** (3 ad variations)

---

## Timeline at a Glance

```
DEC 2025                     JAN 2026                     FEB 2026
├─ Pre-Production (8-20) → Talent Shoots (23-25) → Phase 1 Launch (9) → Optimization (10-28)
│  Scripts, designs,        Raw footage,              Ads live,            Data analysis,
│  talent confirmed         voice-over, music        $8k spend            creative refresh
└────────────────────────────┬────────────────────────────┬─────────────────────┘
                            Editing & Post (25-1/5)  Landing Pages (1/5-1/8)
```

### Key Dates
- **12/15** - Music composition begins
- **12/23-25** - Talent testimonial shoots
- **01/05** - Video editing complete
- **01/09** - PHASE 1 LAUNCH ($8k spend begins)
- **02/28** - Campaign ends

---

## Budget Breakdown

| Platform | Budget | Monthly | % of Total |
|----------|--------|---------|-----------|
| Meta (FB/IG) | $16,000 | $8,000 | 61.5% |
| Google Ads | $6,000 | $3,000 | 23.1% |
| Retargeting | $4,000 | $2,000 | 15.4% |

---

## Success Metrics

### Phase 1 Targets
- **CTR:** 1.5-3%
- **CPC:** $1.50-3.00
- **CPL:** $13-20
- **Lead Quality:** 75%+ form completion
- **Expected:** 500-700 leads

### Phase 2 Goals
- **Reduce CPL:** <$13
- **Increase CTR:** 2-4%
- **Expected:** 500-700 leads
- **Total Campaign:** 1,500-2,000 leads

---

## Key Files

- **`SOCIAL_MEDIA_SPECS.md`** - Complete platform specifications & export guides
- **`PRODUCTION_TIMELINE.md`** - Week-by-week production schedule
- **`asset-tracker.json`** - Machine-readable asset database
- **`QUICK_REFERENCE.md`** - Quick reference card for team

---

## 🌐 Landing Pages Deployment

All 3 landing page templates are ready for immediate deployment:

### View Templates on GitHub
- **Gen Z:** [`landing-pages/genz-landing.html`](./landing-pages/genz-landing.html) (45KB, Modern/Energetic)
- **Retro 90s:** [`landing-pages/retro-90s-landing.html`](./landing-pages/retro-90s-landing.html) (48KB, Nostalgic)
- **Corporate:** [`landing-pages/corporate-landing.html`](./landing-pages/corporate-landing.html) (42KB, Professional)

### Quick Deploy Guide

**Option 1: GitHub Pages (Recommended)**
1. Go to repo Settings → Pages
2. Select `main` branch as source
3. Templates auto-available at: `https://ingramjam.github.io/kic-media-campaign/landing-pages/[filename].html`

**Option 2: Direct Link (GitHub Raw Content)**
```
https://raw.githubusercontent.com/ingramjam/kic-media-campaign/main/landing-pages/genz-landing.html
```

**Option 3: Embed in Iframe**
```html
<iframe src="https://ingramjam.github.io/kic-media-campaign/landing-pages/genz-landing.html" 
        width="100%" height="100%" frameborder="0"></iframe>
```

### Landing Page Features
- ✅ Mobile-first responsive design (9:16 aspect ratio)
- ✅ HubSpot form integration (Portal: 131650)
- ✅ UTM parameter tracking
- ✅ <3 second load time
- ✅ WCAG AA accessibility
- ✅ Demographic/aesthetic targeting

See **[`TEMPLATES.md`](./TEMPLATES.md)** for complete landing page documentation.

---

## 📊 Dashboard Features

The interactive dashboard (`index.html`) includes:

- **Overview Tab:** Campaign at-a-glance stats
- **Budget Tab:** $26k allocation visualization
- **Audiences Tab:** 3 demographic profiles
- **Platforms Tab:** Channel breakdowns
- **Landing Pages Tab:** Links to all templates

---

## 💡 Development Notes

### Project Structure
```
kic-media-campaign/
├── index.html                          # Dashboard
├── README.md                           # Main documentation
├── QUICK_REFERENCE.md                  # Team cheat sheet
├── SOCIAL_SPECS.md                     # Platform specs
├── PRODUCTION_TIMELINE.md              # Timeline
├── SYSTEM_SUMMARY.md                   # System docs
├── GETTING_STARTED.md                  # Action items
├── TEMPLATES.md                        # Landing pages guide
├── LANDING_PAGES_SUMMARY.html          # Template preview
├── asset-tracker.json                  # Ad variations DB
├── LICENSE                             # MIT License
├── .gitignore                          # Git ignore rules
└── landing-pages/
    ├── README.md                       # Landing page docs
    ├── genz-landing.html               # Gen Z template
    ├── retro-90s-landing.html          # 90s template
    └── corporate-landing.html          # Corporate template
```

### Tech Stack
- **Frontend:** HTML5, Tailwind CSS, Vanilla JavaScript
- **Forms:** HubSpot API integration
- **Tracking:** UTM parameters, Google Analytics compatible
- **Hosting:** GitHub Pages (static)

---

**Campaign Launch:** January 9, 2026
**Campaign End:** February 28, 2026
**Repository:** github.com/ingramjam/kic-media-campaign
**License:** MIT
