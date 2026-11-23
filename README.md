# Growth Guru Wealth

Static website for **Growth Guru Wealth**, an AMFI Registered Mutual Fund Distributor based in Kolhapur, Maharashtra.

Live at **[growthguruwealth.com](https://growthguruwealth.com)** (hosted on Cloudflare Pages).

## Files

| File | Purpose |
|---|---|
| `index.html` | Homepage — hero, practice, three pillars, 4-step approach, calculator, insights, contact, FAQs |
| `insights.html` | Articles. Single-article view driven by the URL hash; no hash shows the listing |
| `logo.png` | Brand mark (circular, transparent) — used in header, footer and as favicon |
| `hero.jpg` | Homepage hero image |
| `sitemap.xml` | For Google Search Console |
| `robots.txt` | Crawler directives + sitemap pointer |

No build step. No dependencies. Open `index.html` in a browser to preview.

**All files must stay in the same directory** — `index.html` references `logo.png` and `hero.jpg` by relative path.

## Deploying

Currently deployed via **Cloudflare Pages** (direct upload). To release a change: upload all six files together to the Pages project — Cloudflare replaces the whole deployment rather than merging, so a partial upload drops the images.

Previous deployments are kept in the Cloudflare Deployments tab and can be rolled back.

## Design system

| Token | Value | Use |
|---|---|---|
| Deep forest green | `#0B3D2E` | Headings, primary buttons, contact section, footer |
| Emerald | `#176B4D` | Icons, links, eyebrow labels |
| Warm gold | `#C9A227` | Accents only — rules, numbers, list markers, key figures |
| Off-white | `#F8F7F2` | Page background |
| White | `#FFFFFF` | Cards |
| Charcoal | `#17201C` | Body text |
| Muted grey-green | `#66736C` | Secondary text |
| Light green-grey | `#E3E8E4` | Borders |

Typefaces: **Newsreader** (display serif) and **Manrope** (body/UI), both from Google Fonts.

Gold is deliberately restricted to small accents. It is not a background or body colour.

## Compliance notes

This site is published under a live AMFI registration. The footer disclosure block is load-bearing — **do not trim it for visual tidiness.**

Rules the content follows:

- No past returns, performance figures, or portfolio screenshots
- No guaranteed or assured return language
- The calculator is framed as an illustration on a user-selected assumption, never a projection
- Insurance content stays generic: no specific policy, premium, sum assured, benefit amount or insurer named
- No testimonials or client success stories
- The firm is described as a **distributor, not an investment adviser**, with commission disclosed
- No use of "advisor", "wealth advisor" or "IFA" in any naming

Registrations displayed: ARN-345742 (registered 19 November 2025), IRDAI Code ICII01494250.

## Known gaps

- No privacy policy page — the contact form collects name, phone and email, which the DPDP Act requires a stated purpose and policy for
- Google Analytics not installed
- Founder/about-the-principal section not yet written
- Hero image is AI-generated; a real photograph would serve the practice better
