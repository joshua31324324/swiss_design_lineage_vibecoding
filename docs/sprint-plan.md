Sprint-Plan
================

🚀 Sprint 1: Foundation
----------------

Establish the visual and structural groundwork for your Metro × Nintendo Power site. This sprint locks in the layout, typography, and color system that future modules will build on.

### 🧱 Layout Structure

-------------------

#### Page Anatomy

* 12-column layout with 8px baseline grid
  
* Max width: 1100px desktop, fluid mobile

* Tile gutters: 20–24px

* Vertical spacing: 32–40px between sections

#### Grid System

* Header: Impact-styled title bar with accent border

* Main container: padded, centered, responsive

* Footer: low-contrast, minimal, brand-aligned

#### Component Types

* .card: principles, examples, specs

* .rule: implementation guidelines

* .principle: design philosophy tiles

* .grid-2, .grid-3: responsive content blocks

### 🔤 Typography System

-------------------

#### Display Font

* Impact for H1–H2 (used sparingly)

* Letter-spacing: +0.05em, weight: 400, kerning: normal

#### Body Font

* Arial, Segoe UI, or Inter fallback

* Font sizes:

    ** Body: 0.98rem (~15.5px)

    ** Lede: 1.02rem

    ** Section headers: 1.5rem

    ** Cards: 0.94rem muted tone

#### Hierarchy

* Use color and spacing to reinforce structure

* Avoid overbolding—use weight + spacing instead

### 🎨 Color Palette

-------------------

``` markdown
Background: #0d0d0d, used for site canvas, dark neutral
Card background: #1a1a1a, used for section blocks, tiles
Primary accent: #8b0000, used for headers, borders, CTAs
Secondary accent: #ffcc00, used for highlights, rule lines, callouts
Muted text: #cfcfcf used for lede, secondary copy
Body text: #f2f2f2, used for main content
```

* Contrast ratios meet WCAG AA for body text

* Accent colors used sparingly to guide attention

### ✅ Success Criteria

-------------------

These criteria ensure your Metro Retro system is robust, accessible, and ready for modular expansion.

#### Structural Consistency

* All pages use the same grid, spacing, and card anatomy

* Layout components (.card, .principle, .rule) follow consistent padding and alignment

* No inline styles except for scoped overrides in prototypes

#### Structure

* Top-level header with brand title and optional command bar

* Sidebar or hamburger menu for mobile

* Breadcrumbs optional for deep customization flows

#### Responsiveness

* Layout adapts cleanly to mobile and tablet

* No overflow or stacking issues on key breakpoints

* Grid collapses to single-column or stacked tiles as needed

#### Accessibility

* Focus styles are visible and intuitive

* Reduced motion respected via prefers-reduced-motion media query

* Text readable at 14px+ and contrast ≥ 4.5:1

* Semantic HTML used for headings, lists, and navigation

#### Content Readiness

* Designer profiles, style guide, and product pages plug into the system without layout rewrites

* Typography and spacing support editorial-style case studies and spec-heavy product blocks

* Cards and tiles support dynamic content (images, metadata, CTAs)

🚀 Sprint 2: Components
----------------

Define the reusable interface components that drive layout, navigation, and interaction across the site. These elements reflect Metro’s clarity and motion principles, paired with Nintendo Power’s editorial punch.

### 🧭 Navigation

#### Structure

* Top-level header with brand title and optional command bar

* Sidebar or hamburger menu for mobile

* Breadcrumbs optional for deep customization flows

#### Behavior

* Sticky header on scroll (desktop)

* Slide-in drawer for mobile nav

* Active state highlighted with accent color (#8b0000)

#### Labels

* Sentence case (e.g., “Customize controller” not “CUSTOMIZE CONTROLLER”)

* Flush-left alignment

* Bold weight for active items

### 🧱 Cards & Content Blocks

#### Card Anatomy

* Title (H3), metadata, image or icon, CTA

* Padding: 16–24px

* Border: 2px solid #8b0000

* Background: #1a1a1a

#### Types

* .card — general content blocks

* .principle — design philosophy tiles

* .rule — implementation guidelines

* .product-tile — controller previews with specs and swatches

#### Behavior

* Hover: subtle lift or shadow

* Click: expands or navigates

* Responsive: stack vertically on mobile

### 🎮 Buttons

#### Primary Button

* Background: #8b0000

* Text: #f2f2f2

* Border-radius: 4px

* Padding: 12px 20px

* Font-weight: bold

#### Secondary Button

* Background: #1a1a1a

* Border: 2px solid #8b0000

* Text: #f2f2f2

* Hover: background shift or outline glow

#### Behavior

* Motion: 200ms ease-out on hover/focus

* Focus: visible outline (3px solid #ffcc00)

* Disabled: reduced opacity, no hover effect

### 🧱 Footer

#### Structure

* Background: #111

* Text: muted (#bdbdbd)

* Border-top: 4px solid #8b0000

* Font-size: 0.9rem

#### Content

* Brand name and copyright

* Optional links: About, Style Guide, Contact

* Social icons (if used): flat, monochrome

#### Behavior

* Static on desktop

* Collapsible or stacked on mobile

### ✅ Success Criteria - Sprint 2

#### Component Consistency

* All cards, buttons, and navigation elements follow shared spacing, color, and typography rules

* No inline styles except scoped prototypes

* Components are modular and reusable across pages

#### Visual Clarity

* Buttons and cards use high contrast and clear hierarchy

* Navigation is intuitive and accessible

* Footer is readable and unobtrusive

* Responsiveness Cards stack cleanly on mobile

* Navigation adapts to screen size

* Buttons remain tappable (minimum 44px height)

* Accessibility Focus styles are visible

* Reduced motion respected

* Color contrast ≥ 4.5:1

* Semantic HTML used for buttons, links, and landmarks

* Ready for Expansion Components support designer profiles, product specs, customization flows

* Cards and buttons can be reused in galleries, modals, and checkout

* Footer and nav can scale with site growth

Sprint 3: Polish
----------------

Finalize the site for launch. This sprint focuses on refinement, performance, and accessibility across all modules. Every page should be complete, responsive, and optimized for speed and clarity.

### All Pages Complete

* Designer profiles, product pages, customization flows, and style guide are implemented
* No placeholder content or empty modules
* All components follow Metro Retro design system

### Responsive on All Devices

* Layout adapts cleanly to mobile, tablet, and desktop
* Cards and tiles stack or reflow without breaking
* Navigation and footer remain usable across breakpoints

### Lighthouse 90+

* Performance, accessibility, best practices, and SEO all score 90+
* Images optimized (lazy loading, compression)
* Fonts served efficiently (system fonts or subsetted web fonts)
* No unused CSS or JavaScript
* Meta tags and ARIA roles implemented

### Success Criteria

#### Visual & Structural Completion

* All pages use consistent grid, spacing, and typography
* No visual regressions or broken layouts
* Footer and navigation finalized

#### Performance

* Lighthouse scores ≥ 90 in all categories
* No layout shift or blocking resources
* Fast load on mobile (≤ 2.5s)

#### Accessibility

* Focus styles visible and intuitive
* Color contrast ≥ 4.5:1
* Semantic HTML used throughout
* Reduced motion respected

#### Launch Readiness

* Site deployable without manual fixes
* All links, buttons, and forms functional
* Design system documented and reusable
