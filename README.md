# ASPIRE — Community AI

**Domains:** aspire.com.ng · aspire.nackford.com.ng  
**Stack:** Vanilla HTML/CSS · No framework · No build step  
**Company:** [Nackford Ltd](https://nackford.com.ng)  
**Status:** Seed stage · Pilot deployments open

---

## About

ASPIRE is AI community engagement infrastructure for organisations that work with people at scale — governments, NGOs, FMCGs, unions, health programmes, and civic networks. Verified member networks, field intelligence, viral growth mechanics, and broadcast communications — with AI at every layer.

Built in Africa. Designed for global deployment.

---

## Files

### Website variants (4 design directions — same content, different visual treatment)

| File | Design | Background | Logo variant |
|------|--------|------------|--------------|
| `index-1-clean.html` | Clean & Modern — white, Paystack-like | Light (`#ffffff`) | `aspire-logo.svg` (white circle) |
| `index-2-bold.html` | Bold & Expressive — black, amber accents | Dark (`#09090b`) | `aspire-logo-dark.svg` (transparent) |
| `index-3-warm.html` | Warm & Human — cream, Lora headings | Light (`#fefce8`) | `aspire-logo.svg` (white circle) |
| `index-4-surprise.html` | Dark AI-forward — near-black, cyan/purple, JetBrains Mono | Dark (`#020817`) | `aspire-logo-dark.svg` (transparent) |

### Other files

| File | Description |
|------|-------------|
| `pitch-deck.html` | 18-slide PDF-ready pitch deck — print/export via browser Ctrl+P |
| `logo-options.html` | Logo exploration round 1 |
| `logo-options-v2.html` | Logo exploration round 2 (Signal Node variants) |
| `logo-options-v3.html` | Logo exploration round 3 — Constellation, Fingerprint, Root System + LLM prompt |

### Brand assets (`assets/brand/`)

| File | Use |
|------|-----|
| `aspire-logo.svg` | Full mark — white circle bg, for light/warm page backgrounds |
| `aspire-logo-dark.svg` | Full mark — transparent bg, lighter step blues, for dark backgrounds |
| `aspire-favicon.svg` | SVG favicon — 32×32 blue-steps mark |
| `favicon.ico` | ICO fallback |
| `aspire-logo-1024.png` | High-res PNG for documents/presentations |

Logo source: `aspire-logos/blue-steps/` — the chosen direction from the blue-steps set.

---

## Design system

**Palette (dark variants):** `#020817` void · `#06b6d4` cyan · `#8b5cf6` purple · `#10b981` green  
**Palette (light variants):** `#0f172a` ink · `#2563eb` blue · `#10b981` green · `#f59e0b` amber  
**Fonts:** Inter (primary) · JetBrains Mono (AI terminal accents, index-4 nav)  
**Shell:** `width: min(1200-1240px, calc(100% - 44-48px)); margin: 0 auto`  
**No build tools.** Pure HTML/CSS/JS.

---

## Content sections (all 4 variants)

1. Nav — sticky, logo + wordmark, "Get Early Access" CTA
2. Hero — headline, hero visual (density map / chart)
3. Trust strip — "Used for: NGOs · Governments · FMCGs · Civic Orgs · Community Groups"
4. Problem — 4-voice disconnection (org, member, field, funder)
5. What ASPIRE Does — 3-column capability tiles
6. AI Layer — mock command interface (no real API), message generation, sentiment
7. Growth Engine — referral mechanics, compounding network visual
8. Use Cases — 6 sector cards
9. Community Services — financial inclusion, AI literacy, election monitoring, skills
10. 14-Layer Engine — architecture summary
11. Dashboard Preview — HTML/CSS mock tiles
12. Traction — 2014 proof point (0→2,000 members, 4 days, zero financial incentive)
13. Pricing — 4 tiers (Starter · Growth · Enterprise · Programme) — amounts TBD
14. Investors — market size (TBD — global-first framing), 3 unfair advantages
15. Footer — address, phone, links

---

## Contact & Address

- **General:** hello@aspire.com.ng
- **Investment:** invest@aspire.com.ng
- **Phone:** +234-705-497-6720
- **Address:** 113 Ogudu Road, Ogudu, Kosofe LGA, Lagos, Nigeria
- **Company:** [Nackford Ltd](https://nackford.com.ng)

---

## Pitch deck

`pitch-deck.html` is an 18-slide PDF-ready deck. Print to PDF via browser (`Ctrl+P` → Save as PDF). Each slide is a fixed A4-landscape div. Dark navy palette throughout.

Slides: Cover · Problem · Cost of Disconnection · Introducing ASPIRE · How It Works · AI Layer · Growth Engine · Dashboard · Use Cases · Community Services · Why This Wins · Market Opportunity · Business Model · Traction · Technology · Roadmap · Team · The Ask

---

## Git

**Repo:** [oshodi/nikeron-frontend-website](https://github.com/oshodi/nikeron-frontend-website)
