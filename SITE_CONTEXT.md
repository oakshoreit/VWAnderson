# VWAnderson.com — Site Context & Build Reference

## Purpose of This File
This document exists so Claude Code always has full context on the site structure, design decisions, and current build status. Update it whenever a significant change is made.

Last updated: May 4, 2026

---

## Brand Overview

**Primary brand:** VWAnderson.com — the personal brand
**Operating company:** Oak Shore IT LLC — managed IT services, downstream from consulting
**Owner:** Vincent Anderson

**Title:** Virtual IT Director · AI Strategist
**Niche:** Manufacturing & operations-driven companies, 50–200 employees, Research Triangle NC
**Tagline:** "25+ years keeping manufacturing businesses running. Quietly, completely, and before you know there's a problem."

**Brand voice:** Direct. Confident. No fluff. Earned swagger. The Wolf, not the vendor.
**Color identity:** Charcoal (#1A1A1A), Copper (#B07D4A), Cream (#F2EDE3)
**Fonts:** Georgia/serif for display, system-ui for body

---

## Site Structure
vwanderson.com/
├── index.html          # Homepage — hero, about, field notes preview, services, CTA
├── resume.html         # Full resume page
├── writing.html        # Field Notes index — all articles listed
├── contact.html        # Contact / Work With Me page
├── styles.css          # Global stylesheet
├── headshot.png        # Hero headshot
├── signature.png       # Signature image used in about section
├── SITE_CONTEXT.md     # This file
└── writing/            # Individual Field Notes articles
├── afghanistan.html
├── 1300-pcs.html
├── lab-equipment.html
├── forklift-ipad.html     # IN PROGRESS — manufacturing anchor story
└── mpls-outage.html       # IN PROGRESS — manufacturing insurance story

---

## Hosting & Deployment

- Hosted on GitHub Pages
- Repo: vwanderson/vwanderson.github.io
- Deploy: push to main branch — goes live automatically
- Domain: vwanderson.com — custom domain pointed at GitHub Pages
- Analytics: Google Analytics (G-N9X81VSN6Y)

---

## Key Design Decisions

- Static HTML/CSS — no frameworks, no build tools, intentional
- No WordPress or CMS yet — planned when article count reaches 6–8
- Beehiiv for newsletter — popup triggers at 30 seconds or 60% scroll, one-time dismiss stored in localStorage
- Oak Shore IT referenced only in footer — subtle footnote, not a funnel
- Mobile nav: links hidden at <768px, hamburger menu not yet implemented (low priority)

---

## Content Status

### Field Notes — Live
- The Server I Shipped to Afghanistan (Infrastructure)
- How I Migrated 1,300 PCs at 18 (Leadership)
- No Is Not a Security Policy (Security)

### Field Notes — In Progress (needed before May 11 outreach launch)
- The Forklift iPad Project — manufacturing niche anchor. Story: Triangle Brick. ERP integration with forklift-mounted iPads, trucker self-check-in, automated shop floor workflow. Theme: technology as competitive advantage.
- The MPLS Outage — manufacturing insurance story. Story: Triangle Brick. 3-day AT&T MPLS failure, jerry-rigged VPN to keep PLCs and manufacturing systems running. Theme: technology as insurance.

---

## Launch Status

**Target date:** May 11, 2026 — first warm outreach email goes out
**Proof of concept goal:** $3,000/month recurring by day 90

### Completed
- LLC filed: Oak Shore IT LLC (NC Secretary of State, May 4, 2026)
- EIN obtained
- Business bank account opened (Relay)
- Branding updated to lead with manufacturing
- Beehiiv newsletter popup added

### Pending before May 11
- Write and publish forklift iPad Field Notes article
- Write and publish MPLS outage Field Notes article
- Set up Beehiiv account and replace embed placeholder in popup
- Contact audit — sort contacts into Tier A, B, C
- Draft warm outreach email
- Update LinkedIn headline and about section
- Apply for Microsoft CSP program

---

## Business Context

Full business plan: OakShore_VWAnderson_BusinessPlan_v2.docx (in Claude project files)

**Two-track model:**
- Track 1: VWAnderson.com — fractional vCIO consulting, $3,000–5,000/month retainer
- Track 2: Oak Shore IT — managed IT services, downstream from consulting relationships only

**The one rule:** Never let Oak Shore pull back into technician mode before VWAnderson has momentum.
