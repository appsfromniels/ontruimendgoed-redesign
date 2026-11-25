# Ontruimend Goed Website Redesign Plan

## Current Site Analysis

**Business**: Estate clearance services (Amsterdam focus)
**USPs**: Personal, professional, discreet | 24/7 service | 5.0 Google rating (66 reviews)
**Target audience**: People in emotional/stressful situations (death, moving, downsizing)

---

## URL Structure (Preserve Exactly)

```
/                              → Home
/wat-we-doen/                  → Services overview
/woningontruiming/             → House clearance
/bedrijfsontruiming/           → Business clearance
/ontruimingen-na-overlijden/   → Estate clearance after death
/inkoop-taxatie/               → Purchase & appraisal
/zolder-opslag/                → Attic & storage
/werkwijze/                    → How we work
/reviews/                      → Customer reviews
/wie-we-zijn/                  → About us (Frank & Robin)
/tarieven/                     → Pricing
/contact/                      → Contact page
```

---

## Design Direction

### Visual Identity

| Element | Recommendation |
|---------|----------------|
| Primary color | Deep teal #1A6B5C (trustworthy, calming) |
| Secondary | Warm sand #F5F0E8 (soft, approachable) |
| Accent | Gold #C9A227 (quality, value) |
| Typography | Headings: Playfair Display (classic trust) / Body: Inter (readable) |
| Imagery | Warm, bright photos. Before/after shots. Real team photos. |

### Design Principles

1. **Trust-first** — Google rating prominent on every page
2. **Calm & clean** — Lots of whitespace, no visual clutter
3. **Human** — Real faces, empathetic copy
4. **Clear CTAs** — Phone number + quote button always visible
5. **Mobile-first** — 60%+ traffic likely mobile

---

## Deliverables for WordPress Builder

### 1. Figma Design File
- Desktop designs (1440px)
- Tablet designs (768px)
- Mobile designs (375px)
- Component library (buttons, cards, forms, nav)
- Style guide page

### 2. Asset Package
```
/assets
  /images
    - hero-home.jpg
    - hero-services.jpg
    - team-frank.jpg
    - team-robin.jpg
    - service-icons/ (5 SVG icons)
    - trust-badges/ (Google, KvK, sustainability)
  /fonts
    - playfair-display-*.woff2
    - inter-*.woff2
  /logo
    - logo-full.svg
    - logo-icon.svg
    - favicon.ico
```

### 3. Content Document
- All page copy (Dutch)
- SEO titles & meta descriptions
- Alt texts for images
- CTA button texts

### 4. Specification Document
- Interaction notes (hover states, animations)
- Form specifications (contact, quote request)
- Third-party integrations:
  - Google Reviews widget
  - Google Maps embed
  - Phone click-to-call
  - WhatsApp button (optional)

---

## Page-by-Page Structure

### Homepage
1. Hero: Emotional headline + phone + quote CTA
2. Trust bar: Google rating, years experience, service area
3. Services grid (6 cards linking to subpages)
4. How it works (3 steps)
5. About preview (team photo + short intro)
6. Testimonials slider
7. Service area map
8. Final CTA section
9. Footer

### Service Pages (Template)
1. Hero with service-specific image
2. What we do (bullet points)
3. Why choose us for this service
4. Process steps
5. Related services
6. Quote CTA
7. FAQ accordion (service-specific)

### About Page
1. Company story
2. Team members with photos
3. Values/mission
4. Partner (Kringloop Waterlooplein)

### Contact Page
1. Contact info block
2. Contact form
3. Google Maps embed
4. Business hours

---

## Phases

### Phase 1: Design (You/Designer)
- [ ] Gather/create imagery
- [ ] Design homepage in Figma
- [ ] Design service page template
- [ ] Design remaining pages
- [ ] Create component library
- [ ] Export assets

### Phase 2: Handoff Package
- [ ] Organize Figma file with dev-ready specs
- [ ] Prepare all assets (optimized images, fonts)
- [ ] Write content document
- [ ] Write spec document
- [ ] Create ZIP handoff package

### Phase 3: Builder Instructions
- [ ] WordPress theme recommendation (Kadence, Astra, or custom Elementor)
- [ ] Required plugins list
- [ ] SEO redirect map (if URLs change — avoid if possible)
- [ ] Testing checklist

---

## WordPress Builder Checklist

Include in handoff:

```markdown
## Technical Requirements
- [ ] WordPress 6.x
- [ ] PHP 8.1+
- [ ] SSL certificate
- [ ] Responsive (mobile-first)
- [ ] PageSpeed score >80 mobile
- [ ] WCAG 2.1 AA accessibility

## Plugins Needed
- Yoast SEO or RankMath
- WPForms or Gravity Forms
- Google Reviews widget
- WP Rocket or similar cache
- Updraft Plus (backups)

## Must-Have Features
- Click-to-call on mobile
- Sticky header with phone
- Quote request form on all pages
- Google Reviews auto-update
- Schema markup (LocalBusiness)
```

---

## Next Steps

1. **Approve this plan** — any changes?
2. **Gather assets** — existing photos? New shoot needed?
3. **Start Figma design** — homepage first
4. **Review iteration** — 2-3 rounds
5. **Package handoff** — ready for builder

---

## Questions for You

- New photography or stock images?
- Keep current logo or redesign?
- Any competitor sites you like?
- Budget for WordPress builder?
- Timeline?
