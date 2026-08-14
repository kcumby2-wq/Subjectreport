# Subject·Report — Static Landing Page

Film-graded athlete development and recruiting education platform.  
**Live site:** [www.subjectreport.com](https://www.subjectreport.com)  
**Operated by:** Trail of Joy Player Management Group, LLC

---

## What this repo is

This is a single-file static HTML landing page for Subject·Report. Everything — HTML, CSS, and JavaScript — lives in one file: `index.html`.

No framework. No build step. No dependencies to install. Open the file in a browser and it works.

---

## File structure

```
/
├── index.html              ← The entire site (HTML + CSS + JS)
├── transcript-sample.png   ← Player transcript mockup shown in the product section
├── README.md               ← This file
```

---

## How to make changes

1. Open `index.html` in VS Code
2. Edit the code
3. Save the file
4. Deploy (see below)

That's it. No build process, no npm, no compilation.

---

## How to deploy

### Option A — Netlify (recommended, fastest)

1. Go to [app.netlify.com](https://app.netlify.com)
2. Find your Subject·Report site
3. Click the **Deploys** tab
4. Drag and drop `index.html` onto the deploy drop zone
5. Live in ~10 seconds

### Option B — GoDaddy File Manager

1. Log into [account.godaddy.com](https://account.godaddy.com)
2. Go to **My Products → Web Hosting → Manage → cPanel → File Manager**
3. Open the `public_html` folder
4. Delete or rename the old `index.html`
5. Upload your updated file
6. Rename it to `index.html` if needed
7. Live immediately

---

## Integrations

| Service | Purpose | Config location |
|---|---|---|
| **Supabase** | Lead capture (athlete form submissions) | `localStorage` keys `sr_supabase_url` and `sr_supabase_anon_key` |
| **Stripe** | Package checkout | `/api/subjectreport/checkout` route |
| **Calendly** | Call booking popup | Hardcoded to `https://calendly.com/kcumby2/30min` |
| **Google Analytics** | Page tracking | Tag ID `G-FT4WVW8DF1` in `<head>` |

---

## Design system

| Token | Value | Used for |
|---|---|---|
| `--navy-900` | `#0a1729` | Page background |
| `--navy-800` | `#0f2040` | Cards, modals |
| `--cyan` | `#2fa3e8` | Primary CTAs |
| `--cyan-bright` | `#4ec4ff` | Accents, highlights |
| `--cream` | `#f2eee3` | Body text |
| `--cream-bright` | `#f8f5ec` | Headlines |

**Fonts:** Anton (headlines, uppercase) + Inter (body)

---

## Sections (in order)

1. Nav
2. Hero
3. How It Works
4. Transcript Sample (product mockup)
5. Recruiting Timeline
6. What You Get (cards)
7. Packages · The Ladder ($999 Transcript · Verified Season $1,500/$2,800/$4,500 · $1,200/mo Dev Retainer)
   · How we get paid (transparency block)
8. Testimonials (5 cards)
9. Education Hub
10. (retired · Prospect Membership · replaced by the Verified Season ladder)
11. Proof Stats
12. FAQ
13. Final CTA
14. Admin Tools (staff/event operators)
15. Footer

---

## Brand

- **Subject·Report** — athlete development and recruiting platform
- **TOJ Advisory** — Trail of Joy Player Management Group, LLC (parent company)
- Contact: [hello@subjectreport.com](mailto:hello@subjectreport.com)
