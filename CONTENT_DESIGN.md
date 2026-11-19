# Umurima Fresh — One-Page Website Content & Design

**Version:** 1.0 · 18 November 2026
**Source:** `TEAM_BUSINESS_PLAN.md` (Umurima Fresh, Lean Startup plan)
**Page type:** Single-page marketing site + WhatsApp ordering
**Primary conversion:** A prefilled WhatsApp order message
**Secondary conversion:** Phone call, office enquiry

> **One-line brief:** A warm, mobile-first page that lets a busy Kigali household understand the offer in five seconds, trust it in thirty, and order on WhatsApp in under a minute.

---

## 0. At a glance

| Item | Decision |
|---|---|
| Brand | **Umurima Fresh** (working name; may shorten to **Umurima**) |
| Tagline | **Harvested at dawn. Delivered by dinner.** |
| Audience | Busy corporate households in Kacyiru, Kimironko, Remera, Nyarutarama |
| Core offer | Weekly produce box, harvested to order, delivered next day |
| Price anchor | Family Box **RWF 14,500 delivered**; Student Saver **RWF 4,500** |
| Ordering | WhatsApp only — no account, no checkout, no card |
| Tone | Warm, direct, confident, locally rooted |
| Language | English, with light Kinyarwanda greetings (Muraho, Murakoze) |
| Primary colour | Deep green `#1F5D3A` |
| Design style | Editorial farm-to-table: real photography, cream background, generous whitespace |

**Five-second test:** A first-time visitor should immediately know:
- what it is (a weekly box of fresh produce),
- where it is (Kigali),
- how to order (WhatsApp),
- the entry price (from RWF 4,500).

---

## 1. Audience & job-to-be-done

**Primary persona:** “Aline, 33” — bank marketing manager in Kacyiru, lives in a Kimironko apartment with her husband and two children. Shops at Kimironko on Saturday; pays a moto RWF 1,500–2,000 to bring bags home; pays with MTN MoMo/eKash.

**Job to be done:** “Help me put fresh, trustworthy produce on the table this week without losing my Saturday or carrying heavy bags.”

**Objections the page must answer:**
1. Is it actually fresh, or just another reseller?
2. Is it more expensive than Kimironko?
3. What exactly is in the box?
4. When will it arrive, and what if I’m not home?
5. Can I pay with MoMo?
6. What if something is spoiled?

---

## 2. Brand & tone

### 2.1 Brand personality

- **Rooted:** Rwandan soil, cooperative names, real farmers — not a faceless app.
- **Warm:** speaks like a neighbour, not a supermarket.
- **Straight:** fixed contents, fixed prices, no bargaining, no fine print.
- **Proud:** “Proudly grown in Rwanda” is a feature, not a disclaimer.

### 2.2 Voice rules

| Do | Don’t |
|---|---|
| “Your box arrives between 10 AM and 4 PM.” | “Delivery windows are subject to operational constraints.” |
| “If anything isn’t fresh, we replace it.” | “Quality complaints will be reviewed.” |
| “We buy directly from the cooperative.” | “We leverage a curated supply network.” |
| “Muraho! Your box is one message away.” | “Initiate your procurement journey.” |

### 2.3 Microcopy principles

- Short sentences. One idea per line.
- Use “you” and “we.”
- Put the price and the next step next to every claim.
- Never hide the delivery fee or the cutoff time.
- Use Kinyarwanda only where it feels natural: “Muraho” (hello), “Murakoze” (thank you), “Agaseke” (woven basket) as a visual motif.

---

## 3. Visual system

### 3.1 Colour palette

| Token | Hex | Usage |
|---|---|---|
| `--green-900` | `#1F5D3A` | Primary buttons, headings, footer background |
| `--green-700` | `#2E7D4F` | Hover states, icons |
| `--leaf-500` | `#6B8E4E` | Secondary illustrations, tags |
| `--harvest-500` | `#F2B233` | Highlights, “Most popular” badge, dividers |
| `--tomato-500` | `#D94F3D` | Small accents, error states, price emphasis |
| `--cream-100` | `#FAF7EF` | Page background |
| `--cream-200` | `#F2EBDD` | Alternate section background |
| `--charcoal-900` | `#1E1E1E` | Body text |
| `--charcoal-600` | `#5A5A5A` | Secondary text |
| `--white` | `#FFFFFF` | Cards, header |

**Contrast note:** Never set body text in harvest yellow on white. Use charcoal on yellow, or white on green.

### 3.2 Typography

| Element | Font | Size (desktop / mobile) | Weight |
|---|---|---|---|
| H1 | Poppins | 56 / 36 px | 700 |
| H2 | Poppins | 40 / 28 px | 600 |
| H3 | Poppins | 24 / 20 px | 600 |
| Body | Inter | 18 / 16 px | 400 |
| Small / legal | Inter | 14 / 13 px | 400 |
| Button | Inter | 16 / 15 px | 600 |

Line height: 1.1 for headings, 1.6 for body. Max body line length: 68 characters.

### 3.3 Components

- **Buttons:** pill-shaped, 48 px minimum height, 24 px horizontal padding. Primary: green background, white text. Secondary: transparent with 1.5 px green border.
- **Cards:** 16 px radius, `--white` background, 1 px `#E8E1D4` border, soft shadow `0 8px 24px rgba(30,30,30,0.06)`.
- **Badges:** small pill, harvest yellow background, charcoal text, uppercase 11 px letter-spaced.
- **Icons:** 2 px rounded line icons, 24 px, green.
- **Photography:** real, warm, natural light. Hands, baskets, doorsteps, motos, cooperative fields. No glossy stock smiles. Prefer 4:3 and 1:1 crops.
- **Texture:** a subtle woven `agaseke` pattern at 4% opacity in section dividers — optional, never behind text.

### 3.4 Layout

- Mobile-first, 12-column grid.
- Max content width: 1200 px; gutters 24 px; section padding 80 px desktop / 48 px mobile.
- Spacing scale: 8, 16, 24, 32, 48, 64, 80, 120 px.
- Alternate cream/white section backgrounds to create rhythm without heavy borders.

---

## 4. Page structure

| # | Section | Purpose | Primary CTA |
|---|---|---|---|
| 1 | Header | Brand + navigation + always-visible order button | Order on WhatsApp |
| 2 | Hero | Explain the offer in five seconds | Order this week’s box |
| 3 | How it works | Remove uncertainty about the process | Start your order |
| 4 | Our boxes | Show the products and prices | Order this box |
| 5 | Delivery | Answer “when, where, how much?” | Check my zone |
| 6 | Why trust us | Prove freshness, fairness and traceability | Meet the farmers |
| 7 | Payment | Remove payment friction and fear | — |
| 8 | WhatsApp contact | Make the next step unmistakable | Chat on WhatsApp |
| 9 | Footer | Close with reassurance and practical links | Order on WhatsApp |

**Wireframe (desktop):**

```
┌──────────────────────────────────────────────────────────┐
│ Logo        How it works  Boxes  Delivery  Why us  [CTA] │
├──────────────────────────────────────────────────────────┤
│  H1 + sub + CTAs                    [hero photograph]    │
│  trust strip: 3 co-ops · harvest-day · guarantee         │
├──────────────────────────────────────────────────────────┤
│  How it works:  ① Choose  ② Harvest  ③ Deliver           │
├──────────────────────────────────────────────────────────┤
│  Our boxes:  [Family]  [Student]  [Office Club]          │
├──────────────────────────────────────────────────────────┤
│  Delivery: zone table + simple map + cutoff              │
├──────────────────────────────────────────────────────────┤
│  Why trust us: 6 proof points + farmer photo             │
├──────────────────────────────────────────────────────────┤
│  Payment: eKash · Cash · Office invoice + safety note    │
├──────────────────────────────────────────────────────────┤
│  WhatsApp band: big headline + big button                │
├──────────────────────────────────────────────────────────┤
│  Footer: links · payment marks · legal · Kigali          │
└──────────────────────────────────────────────────────────┘
```

---

## 5. Section-by-section specification

### 5.1 Header

**Layout:** Sticky, 72 px tall, cream/white background, thin bottom border. Logo left; nav centre; WhatsApp button right. On scroll, add a soft shadow.

**Logo:** Wordmark “Umurima Fresh” in Poppins SemiBold, green. Optional mark: a simple leaf inside a woven-basket circle.

**Navigation:** How it works · Our boxes · Delivery · Why us · Contact.

**CTA button:** “Order on WhatsApp” — green pill, white text, WhatsApp glyph.

**Mobile:** Logo left; “Order” compact button + hamburger right. Menu opens as a full-width sheet with large tap targets. A floating WhatsApp button stays bottom-right on all screens.

**Copy:**
- Button: `Order on WhatsApp`
- Menu label: `Menu`

**Notes:** Header must remain usable at 360 px width. No promo bar in v1 — keep the first screen clean.

---

### 5.2 Hero

**Layout:** Two columns on desktop (55% copy / 45% image), stacked on mobile with the image below the copy. Cream background. Generous top padding.

**Eyebrow:** `KIGALI FARM-TO-TABLE`

**H1:** `Harvested at dawn. Delivered by dinner.`

**Subhead:**
`A weekly box of fresh produce from cooperatives in Rulindo and Kamonyi — delivered to your door in Kigali. No market trip. No bargaining. No hidden spoilage.`

**Primary CTA:** `Order this week’s box` → WhatsApp, prefilled with the Family Box message.

**Secondary CTA:** `See what’s inside` → smooth scroll to `#boxes`.

**Trust strip (below CTAs):**
`3 partner cooperatives  ·  Harvest-day delivery  ·  Replacement guarantee`

**Price hint (small, under the trust strip):**
`Family Box RWF 14,500 delivered  ·  Student Saver from RWF 4,500`

**Image direction:** A real customer receiving a box at her apartment door, or a top-down flat-lay of the Family Box on a woven mat: potatoes, tomatoes, onions, carrots, cabbage, eggs, bananas, pineapple. Warm morning light. Leave negative space for the copy.

**Image alt text:** `A Kigali customer receiving a box of fresh potatoes, tomatoes, onions, carrots, cabbage, eggs and fruit at her door.`

**Mobile:** H1 at 36 px; image becomes a 4:3 crop below the CTAs; trust strip wraps to two lines.

**Notes:** Do not use a carousel. One image, one message. The hero must load in under 2 seconds on 3G.

---

### 5.3 How it works (3 steps)

**Section heading:** `From the farm to your door in three steps.`

**Section subhead:** `No warehouse. No middleman. No guesswork.`

**Layout:** Three equal columns, connected by a thin dashed line with numbered circles. On mobile, a vertical timeline with the line on the left.

**Step 1 — Choose your box**
`Pick a Family Box, Student Saver or Office Club. Send us a WhatsApp before 8 PM with your zone and any add-ons. We confirm your order and total in the same chat.`

**Step 2 — We harvest at dawn**
`Our partner cooperatives pick and pack your order the next morning. Nothing sits in a warehouse, and nothing is re-sold from another market.`

**Step 3 — We deliver the same day**
`Your box arrives between 10 AM and 4 PM. Pay with eKash or cash. If anything isn’t fresh, tell us and we’ll replace it on your next delivery.`

**CTA below steps:** `Start your order` → WhatsApp.

**Icons:** woven basket (step 1), sunrise over a field (step 2), moto with a box (step 3).

**Notes:** Keep each step under 35 words. The cutoff time (8 PM) and delivery window (10 AM–4 PM) must appear here, not only in the delivery section.

---

### 5.4 Our boxes

**Section heading:** `Pick the box that fits your week.`

**Section subhead:** `Fixed contents. Fixed prices. No surprises.`

**Layout:** Three cards in a row on desktop; stacked on mobile with the Family Box first. Each card: badge, name, price, contents list, “good for” line, CTA.

#### Card 1 — Family Box

**Badge:** `MOST POPULAR`
**Name:** `Family Box`
**Price:** `RWF 14,500` / `delivery included`
**Contents:**
- 3 kg Irish potatoes
- 1.5 kg tomatoes
- 1 kg onions
- 1 kg carrots
- 1 cabbage
- 10 eggs
- 4 bananas
- 1 pineapple

**Good for:** `3–5 people · 4–5 days of fresh staples`
**CTA:** `Order the Family Box`

#### Card 2 — Student Saver

**Badge:** `BEST VALUE`
**Name:** `Student Saver`
**Price:** `RWF 4,500` / `hostel pickup`
**Contents:**
- 1 kg Irish potatoes
- 0.5 kg tomatoes
- 0.5 kg onions
- 1 bunch dodo
- 3 eggs
- 2 bananas

**Good for:** `1–2 students · free pickup at partner hostels`
**Small print:** `Home delivery +RWF 1,000.`
**CTA:** `Order the Student Saver`

#### Card 3 — Office Club

**Badge:** `FOR TEAMS`
**Name:** `Office Club`
**Price:** `RWF 13,900 per box` / `5 boxes minimum`
**Contents:** `Same contents as the Family Box.`
**Good for:** `One delivery, one invoice, one happy team.`
**CTA:** `Set up an office drop`

**Footnote under the cards:**
`Box contents change slightly with the season. We’ll always tell you before delivery. Prices updated November 2026.`

**Interaction:** Each CTA opens WhatsApp with a box-specific prefilled message, e.g.:
`Muraho Umurima Fresh! I’d like to order the Family Box. My zone is: ____. My name is: ____.`

**Notes:** Do not show a “sold out” state unless inventory is actually constrained. If a box is unavailable, replace the CTA with `Join the waitlist on WhatsApp`.

---

### 5.5 Delivery

**Section heading:** `Next-day delivery across Kigali.`

**Section subhead:** `Order before 8 PM. We harvest at dawn and deliver between 10 AM and 4 PM.`

**Layout:** Two columns: zone table left, simple illustrated map right. On mobile, table becomes stacked cards; map sits below.

**Zone table:**

| Zone | Areas | Fee |
|---|---|---|
| **Zone A** | Remera, Kimironko, Kacyiru, Nyarutarama | **RWF 1,000** — included in Family Box and Office Club |
| **Zone B** | Nyamirambo, Gikondo, Kanombe, City Center | **RWF 1,500** — included in Family Box and Office Club |
| **Mixed / custom orders** | All zones | **Free above RWF 20,000** |

**Supporting copy:**
- `Order by 8 PM for next-day delivery.`
- `Delivery window: 10 AM–4 PM, Monday to Saturday.`
- `Sunday orders are delivered on Monday.`
- `Not home? We’ll call you and leave the box with your building’s concierge.`
- `We pack in insulated crates. Leafy greens go in first; eggs ride on top.`

**CTA:** `Check my zone on WhatsApp` → prefilled message: `Muraho! Is my area covered? My zone/area is: ____.`

**Map direction:** A simplified, stylised map of Kigali with Zone A and Zone B shaded in two greens. Do not use a precise Google Map unless the boundaries are confirmed. Label `Zone A` and `Zone B` clearly.

**Notes:** The delivery fee must never be a surprise. If the Family Box includes delivery, say so in the card and here. If a customer is outside both zones, the WhatsApp reply should offer a custom quote — the site should say `Outside these zones? Message us for a quote.`

---

### 5.6 Why trust us

**Section heading:** `Why Kigali families trust Umurima Fresh.`

**Section subhead:** `Fresh food is a promise. Here’s how we keep it.`

**Layout:** 3×2 grid of proof points on desktop; single column on mobile. A farmer photograph sits to the left of the grid on desktop, above it on mobile.

#### Proof points

1. **Direct from the cooperative**
`We buy directly from three cooperatives in Rulindo and Kamonyi — not from Nyabugogo market. The cooperative’s name is on your box.`

2. **Harvest-day freshness**
`Picked at dawn, packed to order, delivered the same day. Nothing sits in a warehouse overnight.`

3. **Replacement guarantee**
`If anything isn’t fresh, tell us on WhatsApp. We’ll replace it on your next delivery, no questions asked.`

4. **Fixed, fair prices**
`The price you see is the price you pay. No bargaining, no surprise transport costs, no “market price” on the day.`

5. **Farmer-first**
`We pay our partner cooperatives every week. Ask us what we pay — we’ll tell you.`

6. **Real traceability**
`Every box carries the name of the cooperative that grew your food. You’ll know where your dinner came from.`

**Farmer photo caption:**
`[Farmer name], [Cooperative name], Rulindo.` — replace with confirmed names and a signed photo release before launch.

**CTA:** `Meet this week’s farmers` → WhatsApp or a future “Farmers” page. If no page exists, use `Ask us about this week’s farm` on WhatsApp.

**Notes:** Do not invent farmer names, cooperative names, or awards. Use bracketed placeholders until confirmed. Avoid the word “organic” unless certification is verified.

---

### 5.7 Payment

**Section heading:** `Pay the way you already pay.`

**Section subhead:** `No card. No account. No app download.`

**Layout:** Three tiles in a row on desktop; stacked on mobile. A security strip sits below.

#### Tile 1 — eKash QR

`Scan one QR with MTN MoMo, Airtel Money or your bank app. One code, any wallet.`

**Icon:** QR code with a phone.

#### Tile 2 — Cash on delivery

`First time? Pay the rider in cash when your box arrives. Count the eggs before you pay — we’ll wait.`

**Icon:** banknote + box.

#### Tile 3 — Office invoice

`Ordering for your team? We’ll send one monthly invoice for all Office Club boxes.`

**Small print:** `Available for confirmed Office Club accounts.`

**Security strip:**
`We will never ask for your MoMo PIN or send you a payment link on WhatsApp. If someone does, it isn’t us.`

**Notes:** The security strip is essential in the Rwandan market. Keep it visible, not buried in the footer. Do not show card logos — the business does not accept cards in v1.

---

### 5.8 WhatsApp contact

**Section heading:** `Your box is one message away.`

**Section subhead:**
`Send your name, zone and box. We reply in under 5 minutes, 7 AM–8 PM.`

**Layout:** Full-width green band with cream text. A large WhatsApp button centred, plus contact details below in three columns.

**Primary CTA:** `Chat on WhatsApp` — large white pill with green text and the WhatsApp glyph.

**Prefilled message:**
`Muraho Umurima Fresh! I’d like to order: [Family Box / Student Saver / Office Club]. My zone is: [Zone A / Zone B]. My name is: [your name].`

**Contact details:**
- **WhatsApp / call:** `+250 783346754` (placeholder — replace before launch)
- **Email:** `hello@umurimafresh.rw` (placeholder — confirm domain)
- **Hours:** `Mon–Sat 7 AM–8 PM · Sun 9 AM–5 PM`
- **Location:** `Kigali, Rwanda`

**Supporting line:**
`Prefer to talk? Call the same number. We’re a small team — you’ll reach a person, not a bot.`

**Notes:** Use a `wa.me` deep link with the prefilled text URL-encoded. Test on Android and iOS. The button must work without JavaScript.

---

### 5.9 Footer

**Layout:** Four columns on desktop, stacked on mobile. Deep green background, cream text.

**Column 1 — Brand**
- Wordmark: `Umurima Fresh`
- Tagline: `Harvested at dawn. Delivered by dinner.`
- One line: `Proudly grown in Rwanda.`

**Column 2 — Shop**
- Family Box
- Student Saver
- Office Club
- This week’s box

**Column 3 — Learn**
- How it works
- Delivery zones
- Why trust us
- Payment options

**Column 4 — Contact**
- WhatsApp: `+250 783346754`
- Email: `hello@umurimafresh.rw`
- `Kigali, Rwanda`
- Instagram · TikTok (optional, only if active)

**Payment marks:** eKash · MTN MoMo · Airtel Money · Cash on delivery.

**Legal line:**
`© 2026 Umurima Fresh. All prices in RWF. Box contents may vary with the season. Delivery terms apply.`

**Small print:**
`We never ask for your MoMo PIN or send payment links on WhatsApp.`

**Notes:** No fake physical address. If a pickup point exists, name it and link to a map. Keep the footer under 400 px tall on desktop.

---

## 6. Responsive behaviour

| Breakpoint | Header | Hero | Steps | Boxes | Delivery | Trust | Payment |
|---|---|---|---|---|---|---|---|
| 360–767 px | Logo + Order + menu | Stacked, image below | Vertical timeline | Stacked cards | Stacked zone cards | 1 column | Stacked tiles |
| 768–1023 px | Full nav, compact | 2 columns | 3 columns | 2 + 1 | 2 columns | 2 columns | 3 tiles |
| 1024–1279 px | Full nav | 55/45 | 3 columns | 3 cards | 2 columns | 3×2 grid | 3 tiles |
| 1280 px+ | Max 1200 px | 55/45 | 3 columns | 3 cards | 2 columns | 3×2 grid | 3 tiles |

**Mobile specifics:**
- Sticky WhatsApp button, 56 px circle, bottom-right, 16 px from edges.
- H1 never below 32 px.
- Tap targets at least 44×44 px.
- Box cards become a vertical stack, not a horizontal scroll — prices must be visible without swiping.
- Zone table becomes three stacked cards with the fee in bold.

---

## 7. Accessibility

- WCAG 2.1 AA contrast for all text.
- Visible focus ring (2 px harvest yellow, 2 px offset) on all interactive elements.
- Alt text for every image; decorative images use empty alt.
- Buttons use real `<button>` or `<a>` elements, not clickable divs.
- Form fields (if a zone checker is added) have visible labels and inline errors.
- Respect `prefers-reduced-motion`; no autoplay video.
- Do not use colour alone to signal zone or price differences.
- Test with keyboard only and with a screen reader (NVDA or VoiceOver).

---

## 8. SEO & metadata

**Title:** `Umurima Fresh | Farm-fresh produce delivered in Kigali`

**Meta description:**
`A weekly box of fresh produce from cooperatives in Rulindo and Kamonyi, delivered to your door in Kigali. Order on WhatsApp before 8 PM.`

**Canonical:** `https://umurimafresh.rw/` (placeholder)

**Open Graph image:** 1200×630 px, hero photograph with the wordmark and tagline.

**Structured data:** `LocalBusiness` with:
- `name`: Umurima Fresh
- `areaServed`: Kigali (Zone A and Zone B)
- `telephone`: +250 783346754
- `priceRange`: RWF 4,500–14,500
- `paymentAccepted`: eKash, MTN MoMo, Airtel Money, Cash
- `openingHours`: Mo–Sa 07:00–20:00, Su 09:00–17:00

**H1:** one per page — the hero headline. All other section headings are H2.

**Image alt text:** include “Kigali”, “Rulindo”, “fresh produce box” naturally; do not keyword-stuff.

---

## 9. Analytics events

| Event | Trigger | Properties |
|---|---|---|
| `whatsapp_click` | Any WhatsApp CTA | `source` (header, hero, box_card, delivery, float, footer), `box` |
| `box_view` | Box card enters viewport | `box_name`, `price` |
| `zone_check` | Zone CTA clicked | `zone` |
| `call_click` | Phone link clicked | `source` |
| `scroll_depth` | 25/50/75/100% | `percent` |
| `order_confirmed` | Manual log after WhatsApp confirmation | `box`, `zone`, `new_or_repeat`, `source` |

**Weekly dashboard:** WhatsApp clicks, inquiries, confirmed orders, conversion rate, repeat rate, average order value, spoilage/replacement rate, CAC by source.

---

## 10. Content assumptions & placeholders

| Item | Value used | Status |
|---|---|---|
| Family Box price | RWF 14,500 delivered | From business plan; validate with 20 households |
| Student Saver price | RWF 4,500 pickup; +RWF 1,000 home delivery | From business plan |
| Office Club price | RWF 13,900 per box, 5+ | `[ASSUMPTION]` — test with 2 offices |
| Zone A fee | RWF 1,000 | From business plan |
| Zone B fee | RWF 1,500 | From business plan |
| Free delivery threshold | RWF 20,000 | Business plan risk mitigation |
| Cutoff | 8 PM | From business plan |
| Delivery window | 10 AM–4 PM, Mon–Sat | From business plan |
| WhatsApp number | +250 783346754 | **Placeholder — replace** |
| Email | hello@umurimafresh.rw | **Placeholder — confirm domain** |
| Cooperative names | 3 in Rulindo and Kamonyi | **Placeholder — confirm** |
| Farmer names/photos | `[Farmer name]`, `[Cooperative name]` | **Placeholder — signed release required** |
| “3 partner cooperatives” | 3 | From business plan; confirm signed offtake |
| “Under 5 minutes” response | <5 min | From business plan KPI; measure |
| Box contents | As listed | Seasonal; confirm weekly |
| Prices updated | November 2026 | Update quarterly with NISR food CPI |

**Do not publish** any of the following until verified:
- “Organic” or “certified organic.”
- Specific farmer names or cooperative logos.
- A physical address.
- A “same-day” claim (the model is next-day).
- A “free delivery” claim without the RWF 20,000 threshold.

---

## 11. Build handoff checklist

- [ ] Confirm brand name and domain availability (RDB, `.rw`, `.com`, Instagram, TikTok).
- [ ] Confirm WhatsApp Business number and enable the API or a shared inbox.
- [ ] Test eKash QR with MTN MoMo, Airtel Money and one bank app.
- [ ] Confirm the 3 cooperative names and signed weekly offtake terms.
- [ ] Shoot 6–8 real photos: hero, box flat-lay, farmer, packing, rider, doorstep.
- [ ] Confirm Zone A/B boundaries with a rider; draw the simplified map.
- [ ] Replace all `[PLACEHOLDER]` text.
- [ ] Test all `wa.me` links on Android and iOS with prefilled messages.
- [ ] Run Lighthouse mobile: performance ≥90, accessibility ≥95, SEO ≥95.
- [ ] Test at 360 px, 390 px, 768 px and 1440 px.
- [ ] Add analytics events and a manual order log.
- [ ] Publish with “Prices updated November 2026” in the footer.

---

*This document is the content and design source of truth for the one-page site. It follows the five-section Lean Startup plan in `TEAM_BUSINESS_PLAN.md` and uses the November 2026 pricing and delivery assumptions from that plan. All `[ASSUMPTION]` and `[PLACEHOLDER]` items must be validated before launch.*
