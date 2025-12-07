# 📝 MayaNut.com Changelog
Maintained by **The MayaNut Company, Inc.**

This project follows a loose **Semantic Versioning** style:

`MAJOR.MINOR.PATCH`

- **MAJOR** — big redesigns or structural changes  
- **MINOR** — new sections, languages, features  
- **PATCH** — fixes and small improvements  

---

## v2.6.0 – Governance, Repo & Legal Infrastructure

### Added
- `LICENSE` using **Creative Commons BY-NC 4.0** with trademark notice for *MayaNut*.
- `CODE_OF_CONDUCT.md` based on Contributor Covenant v2.1, adapted for:
  - sustainability  
  - scientific integrity  
  - respect for indigenous knowledge  
- `CONTRIBUTING.md` with:
  - coding style rules (HTML/CSS/JS only, no frameworks)
  - SEO and alt-text expectations
  - translation guidelines
  - testing checklists (desktop + mobile)
- `SECURITY.md` with:
  - responsible disclosure policy  
  - steps to report vulnerabilities privately  
- `CODEOWNERS` defining repository ownership and review responsibility.
- `PULL_REQUEST_TEMPLATE.md` to standardize PRs.
- `ISSUE_TEMPLATE` structure for:
  - bug reports  
  - feature requests  
  - documentation/content fixes  
- This `CHANGELOG.md`, documenting the evolution of **MayaNut.com**.

### Changed
- Strengthened repo identity and documentation so the site functions as a long-term, open but curated project.

---

## v2.5.0 – Field Gallery UX Upgrade

### Added
- Horizontal scrolling / swiping behavior for the field gallery so users can move through images intuitively.
- Partial “peek” of the next image to visually indicate more content is available to the right / left.
- Planned affordance for a **“View Full Gallery”** link/page where all images can eventually live on a standalone gallery superpage.

---

## v2.4.0 – Branding, Typography & Color Refinements

### Added
- Global color rules in text:
  - **MayaNut** highlighted as a purple accent.
  - **_Brosimum alicastrum_** highlighted in a pink accent.
  - **August Kokus** highlighted in red when mentioned in About/Research.
- Subtle underlines for card titles (e.g., About card headings) to make each block easier to scan.

### Changed
- Removed any colored or gray box around the hero beverage PNG so
  `mayanutbeverageishere-the-maya-nut-company-image.png` sits cleanly on the gradient with its transparent background.
- Lightened the dark gradient behind the top menu tabs slightly so the text reads better on desktop and mobile.
- Tweaked About section spacing, card layout, and gradients to keep the aesthetic: **modern, slightly futuristic, but warm and botanical**.
- Smoothed paragraph card gradients (About, Research, FAQ) so each panel has its own subtle depth instead of looking flat.

### Fixed
- Image lightbox behavior so that:
  - Expanded images no longer lock scrolling completely.
  - Users can scroll the page while an image is open and still close the lightbox cleanly.
- Refined the close button in the lightbox to a **clean white “X”** without an awkward background box.

---

## v2.3.0 – French Translation & Header Adjustments

### Added
- Fully functional **French version** of the site:
  - `index-fr.html` with aligned sections:
    - Hero  
    - Store  
    - About  
    - Research  
    - Gallery  
    - Recipes  
    - FAQ  
    - Contact  
  - Lightbox, nav, gallery, FAQ, and footer all working with the same structure as English.

### Changed
- Updated the brand text in the upper-left header to:
  - **“The MayaNut Company”** with:
    - “The” and “Company” in the yellow accent.
    - “MayaNut” set in the vivid dark orange accent.
- Reduced the font size of the subtitle line (e.g. “Tree superfood · *Brosimum alicastrum*”) so menu tabs do not overlap the text on translated versions or smaller screens.
- Ensured the **language menu** behaves consistently (opens/closes) on the French version.

### Fixed
- French welcome overlay (modal) now:
  - Opens on first load.
  - Can be closed with the **X**, the **Proceed** button, or an outside click.
  - Auto-dismisses after the timer, just like the English version.

---

## v2.2.0 – Hero Finalization & Layout Polish

### Added
- Final hero beverage image:
  - Replaced generic placeholder with `mayanutbeverageishere-the-maya-nut-company-image.png` to root the hero in a real product-style concept.

### Changed
- Tightened hero spacing so the hero section is compact, visually strong, and free of tall empty zones.
- Standardized gradient-backed paragraph cards across sections so text has a consistent visual language.

---

## v2.1.0 – Easter Egg System v2 (Ricky Tribute)

### Changed
- Consolidated the **Ricky** easter egg to text-based triggers instead of long-press:
  - Typing **“ricky”** or **“Ricky”** into the store search field reveals the Ricky tribute.
  - Behavior tied into header search messaging and subtle acknowledgement of the tribute.
- Ensured the Ricky easter egg appears **beneath the hero beverage image** without shifting or reflowing it.

---

## v2.0.0 – Animation, SEO & Intelligent Navigation

### Added
- **Snow animation system**:
  - Custom snowflake “physics” over the hero.
  - Vertical fall with gentle side-to-side drift.
  - Autoresizing canvas so the snow field always matches hero dimensions.
- **Scroll behavior & nav intelligence**:
  - Smooth scrolling to sections from header tabs.
- **Hidden SEO text span**:
  - Packed with relevant phrases:
    - MayaNut superfood  
    - *Brosimum alicastrum*  
    - nuez de ramón, ojoche, breadnut  
    - Moraceae, canopy tree, South Florida plantations  
  - Hidden off-screen for bots, non-intrusive for users.

---

## v1.9 – Contact Pyramid & Footer Enhancements

### Added
- **Contact pyramid**:
  - Multi-line, centered structure for:
    - Questions about MayaNut and *Brosimum alicastrum*  
    - Research, planting, and bulk inquiries  
    - Long-term project focus statement
- Footer redesign:
  - Centered logo above a green gradient bar.
  - Footer band with:
    - © year auto-updating.
    - Links for Privacy, Terms (future), Sitemap.
- Legal popovers:
  - Clicking Privacy/Terms/Sitemap shows header popover with explanatory placeholder text.

---

## v1.8 – FAQ Rebuild & Mini Assistant

### Added
- Multi-card FAQ area highlighting:
  - High-level questions about the tree, foods, genetics, and project direction.
- FAQ mini assistant:
  - Orange gradient panel with:
    - Input box + Ask button.
    - Topic chips (superfood, tree, products, survival/genetics, recipes, Moraceae, sitemap, greetings).
  - Pre-scripted responses covering:
    - MayaNut as a superfood.
    - Tree & roots.
    - Product timing.
    - Long-term survival directive.
    - Moraceae family context.
    - Where sections live on the single-page layout.

---

## v1.7 – Recipes Section & Culinary Gradient

### Added
- **Recipes section** with green gradient background:
  - Multiple recipe cards for:
    - MayaNut Mocha.
    - Breakfast porridge.
    - Flatbreads/tortillas.
    - Fruit jelly/jam using the actual MayaNut fruit.
    - Cold drink concepts (e.g., iced latte / cold brew–style preparations).
- Each card includes:
  - Short description.
  - Use-case badges.

---

## v1.6 – Field Gallery, Lightbox & Expansion

### Added
- **Field gallery section**:
  - Initial grid:
    - Fruit close-ups.
    - Nursery plants.
    - Mature canopy.
    - Founder with trees.
  - Secondary grid revealed through “Show more field images” button:
    - Beverage glass concept.
    - Powder concept.
    - Plantation rows.
    - Additional canopy or founder views.
- **Lightbox system**:
  - Click any gallery image to open fullscreen-ish view.
  - Click background or X to close.
  - Works on both desktop and mobile.

---

## v1.5 – Research Section Expansion

### Added
- Structured research layout:
  - Cards for:
    - Common names & Indigenous use.
    - Natural range & climate.
    - Growth, roots & hurricane resistance.
    - Agroforestry roles & superfood systems.
    - Ecology & forest role.
    - Domestication & genetic diversity.
    - Reforestation & survival directive.
- Research pill row:
  - “mayanut superfood”, “nuez de ramón”, “ojoche”, “breadnut”, “tropical canopy tree” etc.
- Research hero image:
  - Close-up of leaves with expand button.

---

## v1.4 – About Section Rewrite & Card Layout

### Added
- Converted About into multiple gradient cards with:
  - Project origin story.
  - South Florida trial focus.
  - Genetic diversity & academic respect.
  - Mission & long-term view.
- Initial simple image grid:
  - Fruit, founder, nursery trees, mature tree, beverage glass, powder concept.

---

## v1.3 – Store / Concept Products & Smart Search

### Added
- Store (concept-only, no cart yet) featuring:
  - MayaNut Mocha ready-to-drink concept.
  - MayaNut powder for beverages.
  - MayaNut flour for tortillas and baking.
- Smart store search:
  - Highlights closest matching card as user types.
  - Gentle messaging text under input.
- **Ricky Easter egg v1**:
  - Typing “ricky” in search reveals `ricky.jpeg` and tribute messaging.

---

## v1.2 – Navigation Bar & Language Selector Polish

### Added
- Top navigation bar:
  - Orange–green–blue cylindrical gradient behind tabs.
  - Soft hover lighting instead of hard underlines.
- Language selector:
  - Dropdown with multiple target languages and per-language index files (index-es, index-fr, etc.).

### Changed
- Ensured only the Home tab is active on initial load.
- Linked header logo and footer logo back to page top.

---

## v1.1 – Hero Layout & Height Fixes

### Changed
- Hero section:
  - Moved primary text column to the left.
  - Moved visual / image placeholder to the right.
  - Reduced vertical height so there is no large dead zone.
- Kept underlying Mahler/Alma-style blue gradients for background continuity.

---

## v1.0 – Initial One-Page MayaNut Concept Site

### Added
- Single long page with:
  - Basic hero section and text.
  - Early navigation anchors (Home/About/Research/etc.).
  - Minimal About and Research copy.
  - Simple footer without special branding.
- First pass at explaining:
  - MayaNut as the seed of *_Brosimum alicastrum_*.
  - High-level vision of future beverages, powders, and plantings.

---
