# BKS CONSTRUCTION - Design System

## 1. Visual Identity

**Brand Personality:** Bold, Professional, Trustworthy, Modern, Industrial

**Design Inspiration:** Construction industry aesthetics with modern web design principles — bold typography, high-contrast color schemes, industrial imagery, and clear call-to-actions.

## 2. Color Palette

### Primary Colors
- **Bold Yellow:** `#F9B233` — Main brand color, used for CTAs, accents, and highlights
- **Deep Black:** `#1A1A1A` — Primary text and backgrounds
- **Pure White:** `#FFFFFF` — Text on dark backgrounds, clean sections

### Secondary Colors
- **Construction Orange:** `#FF6B35` — Accent color for important elements
- **Industrial Gray:** `#4A4A4A` — Supporting text, borders
- **Light Gray:** `#F5F5F5` — Background sections, cards

### Hazard Stripes
- **Warning Pattern:** Black and yellow diagonal stripes (construction theme)
- Use for visual separators and design accents

## 3. Typography

### Headings
- **Font Family:** 'Montserrat', 'Inter', or 'Poppins' (bold, modern sans-serif)
- **H1:** 48-64px, Bold (900), Uppercase for impact
- **H2:** 36-48px, Bold (800)
- **H3:** 28-32px, Bold (700)

### Body Text
- **Font Family:** 'Inter', 'Roboto', or 'Open Sans'
- **Body:** 16-18px, Regular (400)
- **Small:** 14px, Regular (400)

### Special Typography
- **Numbers/Stats:** Extra Bold (900), Large size for impact
- **CTAs:** Bold (700), Uppercase, 16-18px

## 4. Layout & Spacing

### Grid System
- **Desktop:** 12-column grid, max-width 1400px
- **Tablet:** 8-column grid
- **Mobile:** 4-column grid, full-width sections

### Spacing Scale
- **XS:** 8px
- **SM:** 16px
- **MD:** 24px
- **LG:** 48px
- **XL:** 64px
- **XXL:** 96px

### Section Padding
- **Desktop:** 80-120px vertical
- **Mobile:** 48-64px vertical

## 5. Components

### Hero Section
- **Style:** Full-screen or large hero with bold headline
- **Background:** Dark background (#1A1A1A) with construction imagery
- **Headline:** Large, bold, white text with yellow accents
- **CTA:** Prominent yellow button with WhatsApp icon
- **Visual Elements:** Diagonal yellow accent shapes, hazard stripes

### Product Cards
- **Layout:** Grid of 6 cards (3x2 on desktop, 2x3 on tablet, 1x6 on mobile)
- **Style:** White cards with subtle shadows
- **Icon/Image:** Construction material icons or photos
- **Title:** Bold, black text
- **Hover:** Subtle lift effect, yellow border accent

### About Section
- **Layout:** Two-column (image + text)
- **Icons:** Three key values with icons (Expertise, Sécurité, Fiabilité)
- **Style:** Clean, professional with yellow icon accents

### Gallery
- **Layout:** Masonry or grid layout
- **Images:** High-quality photos of materials and projects
- **Hover:** Overlay with yellow tint and zoom effect

### Testimonials
- **Layout:** Carousel or grid of 3 cards
- **Style:** White cards with quotation marks
- **Photo:** Circular client photos
- **Rating:** Yellow stars

### Contact Section
- **Layout:** Form + contact info side-by-side
- **CTA:** Large yellow WhatsApp button
- **Background:** Light gray or white
- **Form:** Clean inputs with yellow focus states

### Footer
- **Background:** Deep black (#1A1A1A)
- **Text:** White with yellow links
- **Social Icons:** Yellow on hover
- **Hazard Stripe:** Yellow and black diagonal pattern at top

## 6. Design System Notes for Stitch Generation

**CRITICAL: Include this entire section in every Stitch prompt**

```
DESIGN SYSTEM:

Color Palette:
- Primary Yellow: #F9B233 (CTAs, accents, highlights)
- Deep Black: #1A1A1A (backgrounds, text)
- White: #FFFFFF (text on dark, clean sections)
- Construction Orange: #FF6B35 (accents)
- Industrial Gray: #4A4A4A (supporting text)
- Light Gray: #F5F5F5 (section backgrounds)

Typography:
- Headings: Montserrat/Inter/Poppins, Bold (700-900), Uppercase for H1
- Body: Inter/Roboto, Regular (400), 16-18px
- CTAs: Bold (700), Uppercase

Visual Style:
- Bold, high-contrast design
- Industrial/construction aesthetic
- Yellow and black hazard stripe patterns as accents
- Diagonal geometric shapes for visual interest
- Professional photography of construction materials
- Clean, modern layouts with generous whitespace

Components:
- Hero: Full-screen, dark background, bold white headline with yellow accents, prominent WhatsApp CTA
- Product Cards: White cards with shadows, grid layout, hover effects
- Icons: Simple, bold construction-themed icons in yellow
- Buttons: Yellow background, black text, bold, rounded corners
- Forms: Clean inputs with yellow focus states
- Footer: Black background with yellow accents and hazard stripe pattern

Imagery:
- Construction materials (bricks, cement, sand, gravel, steel)
- Construction workers in safety gear (yellow vests, hard hats)
- Construction sites and equipment
- Professional, high-quality photography
- Use diagonal compositions and dynamic angles

Language: All content in French
```

## 7. Accessibility

- **Contrast Ratios:** Maintain WCAG AA standards (4.5:1 for text)
- **Focus States:** Clear yellow outlines for keyboard navigation
- **Alt Text:** Descriptive alt text for all images
- **Responsive:** Mobile-first approach, touch-friendly buttons (min 44x44px)

## 8. Animation & Interactions

### Micro-interactions
- **Hover:** Subtle lift on cards (translateY -4px)
- **Buttons:** Scale on hover (1.05), smooth transitions
- **Links:** Yellow underline on hover

### Page Transitions
- **Scroll Animations:** Fade-in and slide-up for sections
- **Loading:** Smooth fade-in for images

### Performance
- **Transitions:** 200-300ms for smooth feel
- **Easing:** ease-in-out for natural motion
