# TAEI Academy Website

Official website for TAEI Academy — The Advancement of Empathy & Integrity.

Live site: [taeiacademy.com](https://taeiacademy.com)

---

## Before going live — checklist

- [ ] Replace `Milan` with Milan's full name in `index.html`
- [ ] Replace Milan's bio placeholder with updated bio in `index.html`
- [ ] Add Milan's photo: save as `images/milan.jpg` and replace the `<div class="team-photo">Photo</div>` line with `<img src="images/milan.jpg" alt="Milan" class="team-photo-img">`
- [ ] Add Rafa's photo: save as `images/rafa.jpg` and replace the corresponding `<div class="team-photo">Photo</div>` line
- [ ] Replace both `href="#"` CTA buttons with your Eventbrite or Peatix ticket link
- [ ] Update the confirmed workshop date once locked
- [ ] Connect custom domain in GitHub Pages settings

---

## File structure

```
/
├── index.html        — Main page
├── style.css         — All styles
├── script.js         — Nav scroll + animations
├── README.md         — This file
└── images/
    ├── logo-dark.png       — Logo (white/gold on navy) — for dark backgrounds
    ├── logo-light.png      — Logo (navy/gold on cream) — for light backgrounds
    ├── linkedin-cover.png  — LinkedIn cover photo (1128x191)
    ├── facebook-cover.png  — Facebook cover photo (1640x856)
    ├── milan.jpg           — ADD THIS: Milan's photo
    └── rafa.jpg            — ADD THIS: Rafa's photo
```

---

## Deploying to GitHub Pages

1. Push all files to your GitHub repo
2. Go to repo Settings → Pages
3. Source: Deploy from branch → main → / (root)
4. Save — site goes live at `yourusername.github.io/reponame`
5. Add custom domain in the Pages settings
6. Add DNS records at your domain registrar:
   - A records: 185.199.108.153 / 185.199.109.153 / 185.199.110.153 / 185.199.111.153
   - CNAME: www → yourusername.github.io

---

## Brand colors

| Name  | Hex       | Usage                        |
|-------|-----------|------------------------------|
| Navy  | `#1C2840` | Primary background, text     |
| Gold  | `#C9A84C` | Accent, CTAs, highlights     |
| Cream | `#F2EFE9` | Light section backgrounds    |
| White | `#FFFFFF` | Body text on dark backgrounds|

## Fonts

- Headlines: Cormorant Garamond (Google Fonts)
- Body: DM Sans (Google Fonts)

---

Built by Rafa Islam Diba · TAEI Academy · 2025
