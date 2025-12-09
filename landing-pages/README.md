# Kick It California Landing Pages

Three conversion-optimized landing pages designed for different demographics and products. Each page features mobile-first responsive design, HubSpot form integration, and demographic-specific messaging.

---

## 📄 Landing Page Templates

### 1. **genz-landing.html** — Gen Z (18-29)
**Product:** Quit Vaping  
**Aesthetic:** Modern, energetic, vibrant  
**Color Scheme:** Purple/blue gradients with modern accents  
**Key Message:** "Quit in '26 - Fund your summer, not your habit"

#### Features:
- Savings calculator (interactive, dynamic)
- 24-hour challenge tracker with milestones
- Testimonials from younger quitters (8-18 months)
- Real-time social proof
- Community focus
- Mobile-optimized for TikTok/Instagram traffic

#### Target Metrics:
- **Conversion Rate:** 15%+ (highest responsive demographic)
- **Primary Traffic:** Instagram Reels, TikTok, Snapchat
- **Form Fields:** Email, Instagram handle (optional)
- **CTA:** "Start My Journey" (action-oriented)

---

### 2. **retro-90s-landing.html** — Millennial/Gen X (30-45)
**Product:** Quit Vaping  
**Aesthetic:** Nostalgic, playful, retro 90s  
**Color Scheme:** Pastels, neon, pixel art vibes  
**Key Message:** "Remember the 90s? Remember Your Health?"

#### Features:
- 90s nostalgia elements (cassettes, dial-up, MTV references)
- Timeline showing "Then vs Now" comparison
- Real comeback stories with ages
- 90s-inspired design (geometric patterns, bright borders, chunky fonts)
- Pixel-art inspired animations
- Retro aesthetic consistency throughout

#### Target Metrics:
- **Conversion Rate:** 10-12% (good quality leads)
- **Primary Traffic:** Facebook, YouTube, Pinterest
- **Form Fields:** Email, Birth year (optional)
- **CTA:** "Start Your Comeback" (nostalgia-driven)

---

### 3. **corporate-landing.html** — Gen X/Boomer (45+)
**Product:** Quit Smoking  
**Aesthetic:** Professional, data-driven, trust-focused  
**Color Scheme:** Navy/gold/blue (matches brand identity)  
**Key Message:** "Reclaim Your Health. Reclaim Your Future."

#### Features:
- Evidence-based statistics and health outcomes
- Professional testimonials with credentials
- Detailed recovery timeline (Week 1 → Year 1)
- Trust badges and medical credibility
- ROI focus (financial + health benefits)
- Conservative, clean design
- Comprehensive health information

#### Target Metrics:
- **Conversion Rate:** 8-10% (higher quality, lower traffic)
- **Primary Traffic:** Facebook, Google Search, Email campaigns
- **Form Fields:** Email, Phone, Company (optional)
- **CTA:** "Request Your Personalized Quit Plan" (professional)

---

## 🎨 Design System

### Colors (Consistent with Campaign)
- **Primary Navy:** #1b2845
- **Secondary Navy:** #2e4057
- **Accent Gold:** #d4af37
- **Light Gold:** #f3e5ab
- **Blue:** #4a6fa5

### Typography
- **Headlines:** Limelight (serif) or Poppins (sans)
- **Body:** Lato (sans-serif)
- **Pixel/Retro:** VT323 (monospace, 90s template only)

### Mobile Optimization
All templates are optimized for:
- **Primary Mobile Ratio:** 9:16 (for social traffic)
- **Minimum padding:** 16px
- **Touch targets:** 48px minimum
- **Load time:** <3 seconds target

---

## 🔗 HubSpot Integration

### Form Configuration
All three templates use the same HubSpot form:
- **Portal ID:** 131650
- **Form ID:** 14c2a36e-387b-4368-a49a-b69fa1e98f5e

### Form Fields (Customizable per Template)

**Gen Z Template:**
- Email (required)
- Instagram Handle (optional)
- Demographic info (optional)

**90s Template:**
- Email (required)
- Birth Year (optional)
- Demographic info (optional)

**Corporate Template:**
- Email (required)
- Phone (optional)
- Company (optional)

### UTM Parameters
All landing page links should include:
```
?utm_source=social
&utm_medium=paid_social
&utm_campaign=quit_vaping_2026
&utm_content=[template_name]
```

Example:
```
genz-landing.html?utm_source=instagram&utm_medium=reels&utm_campaign=quit_vaping_2026&utm_content=gen_z
```

---

## 📊 Performance Targets

### Target KPIs
- **Total Leads:** 1,500-2,000 across all templates
- **Target CPL:** $13-20
- **Form Completion Rate:** 5-10% of page visitors
- **Click-through Rate:** 2-3% from social traffic

### Traffic Distribution
- **Gen Z:** 40% of traffic (highest conversion)
- **90s Retro:** 35% of traffic (medium conversion)
- **Corporate:** 25% of traffic (lower traffic, higher quality)

---

## 🚀 Deployment Instructions

### 1. File Structure
```
kic-media-campaign/
├── landing-pages/
│   ├── genz-landing.html
│   ├── retro-90s-landing.html
│   ├── corporate-landing.html
│   └── README.md (this file)
```

### 2. Hosting Options
- **HubSpot:** Upload as landing page templates (native hosting)
- **Custom Domain:** Deploy to web server with CDN
- **Vercel/Netlify:** Static hosting with auto-deploy

### 3. Domain Setup
```
genz.quitkickca.com → genz-landing.html
retro.quitkickca.com → retro-90s-landing.html
quit.quitkickca.com → corporate-landing.html
```

### 4. Analytics Setup
Add tracking for:
- **Google Analytics:** Track form conversions
- **Facebook Pixel:** Retarget visitors
- **HubSpot Analytics:** Monitor form performance

---

## 📝 Content Customization

### Easy Edits
1. **Testimonial Copy:** Search and replace quotes
2. **CTAs:** Modify button text in CTA sections
3. **Phone Numbers:** Update 1-800-NO-BUTTS with current number
4. **Stats:** Update percentages with current campaign data

### Form Configuration
To customize form fields per template:
1. Edit HubSpot form to have conditional fields
2. Update form display logic for each template
3. Test form submission per template

---

## ✅ Testing Checklist

- [ ] All links working (internal anchors, CTAs, footer)
- [ ] HubSpot form submitting successfully
- [ ] Mobile responsiveness (tested on iPhone 12, Android)
- [ ] Form validation working
- [ ] Images loading (no 404s)
- [ ] Animations smooth on mobile
- [ ] Color contrast meets WCAG AA
- [ ] Page load time <3 seconds
- [ ] UTM parameters tracked correctly
- [ ] Thank you screen appears after form submission

---

## 🎯 Campaign Integration

### Phase 1 Launch (Dec 29, 2025)
- **Budget:** $8,000
- **Primary Channels:** Instagram Reels, TikTok, Facebook
- **Landing Pages:** All 3 templates active
- **Expected Leads:** 450-600

### Phase 2 (Jan 9 - Feb 28)
- **Budget:** $18,000
- **Additional Channels:** Google Search, YouTube
- **Optimization:** A/B test CTAs and copy
- **Expected Leads:** 1,050-1,400

---

## 📱 Mobile Testing Breakpoints

- **Mobile:** 375px - 667px (Primary)
- **Tablet:** 768px - 1024px
- **Desktop:** 1025px+ (Secondary)

---

## 🔄 Revision History

| Date | Template | Changes | Status |
|------|----------|---------|--------|
| Dec 9, 2025 | All 3 | Initial creation | ✅ Complete |
| TBD | Gen Z | A/B test CTA copy | Pending |
| TBD | 90s | Add video hero | Pending |
| TBD | Corporate | Update health stats | Pending |

---

## 📞 Support & Questions

**For Technical Issues:**
- Check HubSpot form connectivity
- Verify UTM parameters in URLs
- Test mobile responsiveness

**For Content Changes:**
- Update testimonials in marked sections
- Modify CTA copy in button elements
- Update statistics in stat cards

**Questions?**
Contact: creative@kickitcalifornia.org

---

## 📄 File Sizes & Load Performance

| Template | File Size | Est. Load Time | Optimizations |
|----------|-----------|-----------------|-----------------|
| Gen Z | 45KB | 1.8s | Tailwind CSS CDN, optimized images |
| 90s | 48KB | 2.1s | Animated backgrounds, pixel fonts |
| Corporate | 42KB | 1.6s | Clean design, minimal animations |

**Note:** All sizes include embedded CSS/JS. Images are loaded from GitHub CDN.

---

**Created:** December 9, 2025  
**Last Updated:** December 9, 2025  
**Next Review:** December 15, 2025
