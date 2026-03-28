# TAEI Academy Website

Official website for TAEI Academy — The Advancement of Empathy & Integrity.

Live site: [taeiacademy.com](https://taeiacademy.com)

---

## Event details — Off Script KL

- Date: Saturday, 14 June 2026
- Time: 10am – 2pm
- Location: Kuala Lumpur (venue TBC)
- Capacity: 50 seats
- Early bird price: RM 500 (until 31 May 2026)
- Regular price: RM 750

---

## Before going live — checklist

- [ ] Replace `Milan` with Milan's full name in `index.html`
- [ ] Replace Milan's bio placeholder with updated bio in `index.html`
- [ ] Add Milan's photo: save as `images/milan.jpg` and replace `<div class="team-photo">Photo</div>` with `<img src="images/milan.jpg" alt="Milan" class="team-photo-img">`
- [ ] Add Rafa's photo: save as `images/rafa.jpg` and replace the corresponding `<div class="team-photo">Photo</div>`
- [ ] Replace both `href="#"` CTA buttons with your Eventbrite or Peatix ticket link
- [ ] Confirm venue and add to the website once booked
- [ ] Connect custom domain in GitHub Pages settings

---

## File structure

```
/
├── index.html              — Main page
├── style.css               — All styles
├── script.js               — Nav scroll + animations
├── README.md               — This file
└── images/
    ├── logo-dark.png       — Logo (white/gold on navy) — used in nav and dark sections
    ├── logo-light.png      — Logo (navy/gold on cream) — used as favicon
    ├── linkedin-cover.png  — LinkedIn cover (1128x191)
    ├── facebook-cover.png  — Facebook cover (1640x856)
    ├── milan.jpg           — ADD THIS: Milan's photo
    └── rafa.jpg            — ADD THIS: Rafa's photo
```

---

## Deploying to GitHub Pages

1. Push all files to your GitHub repo
2. Go to repo Settings → Pages
3. Source: Deploy from branch → main → / (root)
4. Save — site goes live at `yourusername.github.io/reponame`
5. Add custom domain in Pages settings
6. Add DNS records at your domain registrar:
   - A records: 185.199.108.153 / 185.199.109.153 / 185.199.110.153 / 185.199.111.153
   - CNAME: www → yourusername.github.io

---

## Brand colors

| Name  | Hex       | Usage                         |
|-------|-----------|-------------------------------|
| Navy  | `#1C2840` | Primary background, text      |
| Gold  | `#C9A84C` | Accent, CTAs, highlights      |
| Cream | `#F2EFE9` | Light section backgrounds     |
| White | `#FFFFFF` | Body text on dark backgrounds |

## Fonts

- Headlines: Cormorant Garamond (Google Fonts)
- Body: DM Sans (Google Fonts)

---

Built by Rafa Islam Diba · TAEI Academy · 2026
