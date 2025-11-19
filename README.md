# StreamPro Mic – Product Landing Page

A responsive product landing page for the **StreamPro Mic**, a fictional USB microphone aimed at streamers, podcasters, and creators.  

This project showcases layout skills, responsive design, and basic landing-page structure for marketing a single product.

---

## Live Sections

The page is organized into four main sections:

1. **Header / Navigation**
   - Logo on the left.
   - Navigation links that scroll to:
     - `Features`
     - `How It Works`
     - `Pricing`
   - Fixed at the top of the page so it stays visible while scrolling.

2. **Hero**
   - Bold headline: *“Crystal-Clear Sound for Every Creator”*.
   - Supporting paragraph describing the mic.
   - Email signup form:
     - Email field with placeholder.
     - “Get Started” submit button.
     - Form posts to the freeCodeCamp email-submit endpoint.

3. **Features**
   - Three feature cards:
     - **Studio Quality** – rich depth and noise-canceling.
     - **Plug & Play** – simple USB-C connection, no drivers.
     - **Customizable RGB** – lighting controlled via the app.

4. **How It Works**
   - Embedded YouTube video (`iframe`) used as a product demo.

5. **Pricing**
   - Two pricing tiers:
     - **Starter – $59.99**
     - **Pro – $129.99**
   - Each card describes what’s included at that tier.

---

## Tech Stack

- **HTML** – semantic structure for header, sections, and pricing content.
- **CSS** – layout, colors, responsiveness:
  - Fixed header
  - Flexbox layout for feature/pricing cards
  - Responsive nav and video
- **No JavaScript** is required for this project; it’s a static marketing page.

---

## Layout & Styling Highlights

- Color palette:
  - Header: deep blue (`#243B73`)
  - Hero: bright yellow (`#FFD93D`)
  - CTA: pink button (`#FF6B81`)
  - Background: light grey (`#f4f6fa`)
- `header` is fixed with `position: fixed; top: 0; width: 100%;`.
- `.features-flex` uses `display: flex; flex-wrap: wrap;` for responsive cards.
- Media query at `max-width: 900px` to:
  - Stack header items vertically on smaller screens.
  - Stack feature/pricing cards.
  - Make the video iframe full-width on mobile.

---

## How to Run

1. **Clone the repo:**

   ```bash
   git clone https://github.com/SharpSanders/product-landing-page.git
   cd product-landing-page
Open the page:

Double-click index.html in your file explorer
or

Use the Live Server extension in VS Code for auto-reload during edits.

No build step or tooling is required.

Project Structure
text
Copy code
product-landing-page/
├── index.html   # Markup for header, hero, features, video, pricing
└── styles.css   # Layout, colors, typography, responsiveness
If you add assets locally (like the logo file) they should live in an img/ folder referenced by #header-img.

What I Practiced
Building a single-product marketing page.

Using a fixed navigation bar that links to page sections.

Designing responsive card-based layouts with Flexbox.

Embedding a YouTube video via iframe.

Structuring content clearly for future JavaScript enhancements (forms, analytics, etc.).

Future Improvements
Add smooth-scrolling behavior for nav links.

Add hover/focus styles for pricing cards and CTA buttons.

Connect the email form to a real backend or mailing list provider.

Add more detailed FAQ and testimonials sections.

Improve accessibility (skip links, ARIA landmarks, etc.).

Author
Created by Trevyn Sanders.