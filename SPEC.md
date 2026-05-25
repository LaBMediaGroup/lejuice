# Lé Juice — Website Redesign Spec
## Design Direction: Warm, Neighborly, Downtown Rochester MI

---

## 1. Concept & Vision

Lé Juice is an organic juice bar and fresh fare café at 118 W. University in downtown Rochester, Michigan. The website should feel like the place itself — not polished, not corporate, not pretending to be something it's not. It's a neighborhood spot. You walk in, you know people, you slow down. The website should feel the same way: warm, direct, honest.

---

## 2. Real Info (no placeholders)

- **Address:** 118 W. University, Downtown Rochester, MI
- **Instagram:** @lejuicerochester
- **Tagline from their bio:** "Organic juice bar + fresh fare"
- **Tagline from profile:** "Menu designed to fuel your body + mind"
- **Also:** "Community space"
- **Location context:** Downtown Rochester, MI (not NY)

---

## 3. Design Language

### Aesthetic Direction
Neighborly, warm, unpretentious. Think: the actual café, not a stock photo version of it. Real interior shots, real food, real neighborhood.

### Color Palette
- **Primary (Warm Sand):** `#F5EDE3` — dominant background
- **Secondary (Sage Green):** `#8A9A7B` — accents, CTAs, links
- **Accent (Terracotta):** `#C4836A` — highlights, hover states
- **Deep (Espresso):** `#3D2E1F` — headings, primary text
- **Muted (Warm Gray):** `#6B5E52` — body text
- **Light (Cream):** `#FDFBF8` — cards, overlays

### Typography
- **Headings:** Playfair Display (serif)
- **Body:** DM Sans (sans-serif)
- **Scale (Major Third 1.25×):** 16px base

### Spatial System
- 8pt grid, generous padding
- Max width: 1200px

### Motion
- Subtle fade-in on scroll
- Hover transitions: 300ms ease
- No aggressive animations — calm and intentional

### Visual Assets
- **All photos:** Real Instagram screenshots from `/LeJuice-Photos/instagram-screenshots/`
- Interior shots (instagram-012 through 018) for vibe/about pages
- Drink/product shots (instagram-001 through 011) for menu and featured sections
- No Unsplash, no stock photography

---

## 4. Pages

### Homepage
- Hero: use instagram-008-largest.png (interior, large)
- Headline: "The Juice Spot on W. University"
- Sub: "Organic cold-pressed juices, fresh fare, and a corner of downtown where you can slow down."
- CTA: "See the Menu"
- Value props: Handmade / Neighborly / Here for It
- Featured section: 4 cards using real drink photos (001, 002, 004, 005)
- About snippet: interior shot (instagram-012), copy about being downtown not a storefront

### Menu (/menu.html)
- Hero: interior shot (instagram-013)
- Headline: "Handmade Every Morning"
- Tabs: Juices / Smoothies / Fresh Fare / Seasonal
- Cards using their actual product photos throughout
- No invented drink names — keep descriptions general so they're accurate

### About (/about.html)
- Headline: "The Neighborhood Juice Spot"
- Story section with real address context
- Vibe gallery: 6 interior photos (instagram-012 through 017)
- Values: Organic / Community / Honest Food
- Location with @lejuicerochester link

### Contact (/contact.html)
- Hero: interior shot (instagram-017)
- Address: 118 W. University, Downtown Rochester, MI
- Instagram link prominent
- No contact form (not needed for this client)
- CTA: "Follow Along" → Instagram

---

## 5. Component Inventory

### Navigation
- Logo left, links right
- Sticky on scroll
- Mobile hamburger menu

### Hero Section
- Full-bleed photo from their Instagram screenshots
- Overlay gradient for text readability
- Headline + subtext + CTA button

### Drink/Item Card
- Real photo from their collection
- Name (Playfair) + description (DM Sans)
- No prices (menu changes too often)

### Value Props (Bento)
- 3 columns: Handmade / Neighborly / Here for It
- Icon + title + short text

### CTA Banner
- Centered text + button
- Used on homepage and menu

### Footer
- Logo + tagline: "Organic juice bar + fresh fare. Downtown Rochester, MI."
- Instagram link (@lejuicerochester) as primary social
- Address: 118 W. University, Downtown Rochester, MI

---

## 6. Technical Approach

- **Stack:** Pure HTML + CSS (no framework)
- **Fonts:** Google Fonts (Playfair Display + DM Sans)
- **Photos:** All from local `/LeJuice-Photos/instagram-screenshots/` folder — real screenshots only, no stock
- **Links:** Instagram linked everywhere (@lejuicerochester)
- **File Structure:**
  ```
  LeJuice-Cave-Build/
    index.html
    menu.html
    about.html
    contact.html
    css/
      style.css
    SPEC.md
  ```

---

## 7. Content Principles

- No invented specifics ("five years," "weekly events," etc.)
- Real address, real Instagram, real photos
- Voice: neighborly, direct, not preachy
- No prices on menu — they change too often
- "Organic juice bar + fresh fare" as shorthand identity
- Everything links to their Instagram as the primary online presence