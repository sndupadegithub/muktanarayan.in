# MuktaNarayan Solutions Private Limited — Official Website

[![DPIIT Recognised Startup](https://img.shields.io/badge/DPIIT-Recognised%20Startup-green?style=flat-square)](https://startupindia.gov.in)
[![GitHub Pages](https://img.shields.io/badge/Hosted%20on-GitHub%20Pages-blue?style=flat-square&logo=github)](https://pages.github.com)
[![License](https://img.shields.io/badge/License-Proprietary-red?style=flat-square)](#license)

> Official website of **MuktaNarayan Solutions Private Limited** — Software development, app publishing, and tech solutions for Australian and global clients.

🌐 **Live site:** [https://yourusername.github.io](https://yourusername.github.io)
*(Replace with your actual domain once configured)*

---

## About the Company

MuktaNarayan Solutions Pvt Ltd is a DPIIT-recognised software startup based in Maharashtra, India. We specialise in building, maintaining, and scaling mobile and web applications for clients in Australia and beyond — with 12+ years of continuous delivery to enterprise clients supporting 4,000+ end users.

---

## Website Sections

| Section | Description |
|---|---|
| **Hero** | Company intro, stats, call-to-action |
| **Services** | 6 core service offerings |
| **About Us** | Company story, values, founder profile |
| **Our Apps** | Published apps on Google Play & App Store |
| **Portfolio** | Client project showcases |
| **Blog** | Insights on software, startups, and tech |
| **Contact** | Enquiry form + company contact details |

---

## How to Deploy on GitHub Pages

### Step 1 — Create a GitHub repository

Go to [github.com/new](https://github.com/new) and create a new repository.

**Recommended repo name options:**
- `muktanarayan-solutions` → hosted at `https://yourusername.github.io/muktanarayan-solutions`
- `yourusername.github.io` → hosted at `https://yourusername.github.io` (root domain, cleaner URL)

### Step 2 — Upload the file

**Option A — via GitHub website (easiest):**
1. Open your new repository
2. Click **Add file → Upload files**
3. Drag and drop `index.html`
4. Click **Commit changes**

**Option B — via Git (for developers):**
```bash
git init
git add index.html
git commit -m "Initial website launch"
git branch -M main
git remote add origin https://github.com/yourusername/your-repo-name.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages

1. Go to your repository → **Settings**
2. Scroll to **Pages** in the left sidebar
3. Under **Source**, select **Deploy from a branch**
4. Set branch to `main` and folder to `/ (root)`
5. Click **Save**
6. Wait 1–2 minutes — your site will be live!

> GitHub will show you the live URL at the top of the Pages settings page.

---

## Custom Domain Setup (Optional)

If you own a domain like `muktanarayan.in`:

1. Create a file named `CNAME` in this repo with your domain:
   ```
   muktanarayan.in
   ```
2. Go to your domain registrar (GoDaddy / Namecheap / BigRock etc.)
3. Add these DNS records:

   | Type | Name | Value |
   |---|---|---|
   | A | @ | 185.199.108.153 |
   | A | @ | 185.199.109.153 |
   | A | @ | 185.199.110.153 |
   | A | @ | 185.199.111.153 |
   | CNAME | www | yourusername.github.io |

4. Back in GitHub Pages settings → enter your custom domain → click **Save**
5. Check **Enforce HTTPS** once DNS propagates (up to 48 hours)

---

## Personalisation Checklist

Before going live, update the following in `index.html`:

- [ ] Replace `contact@muktanarayan.in` with your real email address
- [ ] Update the 3 app cards with real app names and descriptions
- [ ] Replace Google Play and App Store links with actual store URLs
- [ ] Replace app icon initials (`MN`) with real app icon images
- [ ] Update CIN number in the footer (after company registration)
- [ ] Add your real Upwork profile URL in the footer
- [ ] Add your LinkedIn and GitHub profile URLs in the footer
- [ ] Update blog article links when posts are published
- [ ] Replace `yourusername.github.io` with your actual live URL everywhere

---

## Tech Stack

- Pure **HTML5 / CSS3 / Vanilla JavaScript** — zero dependencies
- Fonts: [Syne](https://fonts.google.com/specimen/Syne) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts
- Fully **responsive** — mobile, tablet, and desktop
- **Scroll animations** via Intersection Observer API
- No build tools required — edit and deploy directly

---

## File Structure

```
/
├── index.html        # Complete website (single file)
├── README.md         # This file
└── CNAME             # Add this if using a custom domain
```

---

## Contact

**MuktaNarayan Solutions Private Limited**
Barshi / Pune, Maharashtra, India

- Email: contact@muktanarayan.in
- Website: [muktanarayan.in](https://muktanarayan.in)

---

## License

© 2026 MuktaNarayan Solutions Private Limited. All rights reserved.
This repository contains proprietary website source code. It may not be copied, modified, or redistributed without explicit written permission from MuktaNarayan Solutions Private Limited.
