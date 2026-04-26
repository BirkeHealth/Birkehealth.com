# Birke Health Agency — Website

Static website for **Birke Health Agency** hosted on GitHub Pages.

## Pages

| File | URL | Description |
|------|-----|-------------|
| `index.html` | `/` | Homepage — hero, partners, about cards, contact form |
| `about-us.html` | `/about-us` | Team page — InsuredKenny & Legacy |
| `learn.html` | `/learn` | Insurance education — key terms & CTA |
| `privacy-policy.html` | `/privacy-policy` | Privacy Policy |
| `terms-and-conditions.html` | `/terms-and-conditions` | Terms & Conditions |

## How to Deploy on GitHub Pages

1. Create a new repository on GitHub (e.g. `birkehealth-site`)
2. Upload all files from this folder into the repo root
3. Go to **Settings → Pages**
4. Under **Branch**, select `main` and folder `/root (root)`
5. Click **Save**
6. Your site will be live at: `https://yourusername.github.io/birkehealth-site`

## Contact Form

The contact form on `index.html` uses [Formspree](https://formspree.io).  
To activate it:
1. Sign up at formspree.io
2. Create a new form and copy your form ID
3. In `index.html`, find this line:
   ```
   action="https://formspree.io/f/your-form-id"
   ```
4. Replace `your-form-id` with your actual Formspree form ID

## Tech Stack

- Pure HTML + CSS + vanilla JS — no frameworks, no dependencies
- Google Fonts (Playfair Display + DM Sans) loaded via CDN
- Logo embedded as base64 — no external image files needed
- Fully responsive — mobile hamburger menu included

## Branding

- Primary color: `#5C0A6B` (plum)
- Accent color: `#C9A84C` (gold)
- Background: `#FDFAF5` (cream)
- Fonts: Playfair Display (headings) + DM Sans (body)
