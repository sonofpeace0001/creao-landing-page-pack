# CREAO Premium Landing Page Pack — 57 Niches

57 production-ready premium landing pages across different niches and styles — **dark and light**, three layouts — each generated from **one master prompt framework** using [CREAO](https://agent.creao.ai). Every page ships with the exact prompt that built it, so anyone can copy, edit, and make it their own.

51 are SaaS products; 6 are local service businesses (plumbing/HVAC, dental, restaurant) built on the same design system — proof the framework isn't just for software.

## Live demo

Catalog gallery with search, theme filter, and one-click "copy prompt":

**https://creao-landing-page-pack.vercel.app**

## What's inside

- **`index.html`** — the catalog gallery. Crisp screenshot thumbnails, search, dark/light filter, and copy-prompt buttons.
- **`<slug>-landing.html`** — 57 standalone, self-contained landing pages (inline CSS + JS, Google Fonts via link). No build step.
- **`<slug>-prompt.txt`** — the exact prompt that built each page. Copy, swap the bracketed values, paste into CREAO.
- **`<slug>-thumb.jpg`** — preview thumbnail of the page hero.

## The 57 niches

**SaaS (51):** AI writing, fitness, finance, productivity, courses, CRM, newsletter, e-commerce, meal planning, meditation, habits, AI video editing, podcast hosting, social scheduler, email marketing, analytics, HR onboarding, project management, design tool, notes, AI calendar, bookkeeping, invoicing, time tracking, helpdesk, live chat, knowledge base, API docs, API monitoring, error tracking, feature flags, A/B testing, user feedback, surveys, forms, page builder, website builder, web hosting, domains, VPN, password manager, cloud storage, file sharing, video hosting, image CDN, AI image generation, chatbot builder, AI meeting notes, automation, billing, portfolio.

**More tech (3):** AI coding assistant, cybersecurity / attack surface monitoring, recruiting & ATS.

**Local service businesses (3):** plumbing & HVAC, dental practice, restaurant — same design system, swapped for services-and-booking instead of subscription pricing.

## How to use

1. Open `index.html` (or the live demo).
2. Search a niche or filter by dark/light.
3. Click **View page** to open the live landing page.
4. Click **Copy prompt** to grab the exact prompt.
5. Paste into CREAO, swap the bracketed values (product, headline, hex, features, pricing), regenerate.
6. Download the HTML and deploy anywhere.

## Deploy

Any static host works — the pages are plain HTML.

**Vercel:**
```bash
npm i -g vercel
vercel --prod
```

**Netlify:** drag the folder into [app.netlify.com/drop](https://app.netlify.com/drop).

**Any static host:** upload the `.html` files to the web root.

## The premium system (why none are generic)

Every page uses the same design system: dark `#0A0A0A` (or warm off-white), Inter + Instrument Serif, glassmorphism sticky nav, animated mesh-gradient hero, bento feature grid with custom inline SVG line icons, metrics strip, testimonial, pricing with a working monthly/annual toggle, scroll-reveal via `IntersectionObserver`, and `prefers-reduced-motion` support. No emoji icons, no stock illustrations, no template look.

## License

Free to copy, edit, and use. Built with CREAO.
