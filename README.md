# StreamPro Mic – Product Landing Page

A fully responsive single-product landing page for the fictional **StreamPro Mic**, designed for streamers, podcasters, and content creators.

This project demonstrates structured layout design, marketing-focused content flow, and responsive UI development using semantic HTML and modern CSS.

## Live Demo
https://sharpsanders.github.io/product-landing-page/

<img src="./img/Screenshot-product-landing-page.png" alt="StreamPro Mic Product Landing Page Screenshot" />

---

## Overview

The page is structured as a complete marketing funnel for a single product, including:

- Fixed navigation
- Hero section with call-to-action
- Feature highlights
- Embedded product demo
- Pricing tiers

The layout is designed to mirror real-world SaaS and hardware product landing pages.

---

## Page Sections

### 1. Header / Navigation
- Fixed top navigation bar
- Internal anchor links to page sections
- Persistent visibility during scroll

### 2. Hero Section
- Clear headline and supporting copy
- Email signup form
- Call-to-action button
- Form configured to submit to freeCodeCamp’s test endpoint

### 3. Features
Three feature cards highlighting:
- Studio-quality audio
- Plug-and-play USB-C setup
- Customizable RGB lighting

### 4. How It Works
- Embedded YouTube video using an `iframe`
- Responsive scaling for mobile screens

### 5. Pricing
Two pricing tiers:
- Starter – $59.99
- Pro – $129.99

Card-based layout for clear comparison and hierarchy.

---

## Technical Implementation

### HTML
- Semantic structure (`header`, `section`, `nav`, etc.)
- Anchor linking for smooth navigation
- Accessible form inputs

### CSS
- Fixed header using `position: fixed`
- Flexbox layout for feature and pricing cards
- Responsive video scaling
- Media queries for mobile breakpoints
- Custom color palette and CTA styling

No JavaScript is used in this project. The page is intentionally static to focus on layout, responsiveness, and structure.

---

## Layout & Design Highlights

- Clear visual hierarchy
- Marketing-style hero section
- Card-based layout system
- Mobile-first responsiveness
- Flexible content sections ready for future enhancements

---

## Project Structure

```txt
product-landing-page/
  index.html
  styles.css
  img/
    Screenshot-product-landing-page.png
Run Locally
Clone the repository
git clone https://github.com/SharpSanders/product-landing-page.git

Open index.html in your browser

No build tools or dependencies required.

What I Practiced
Structuring a single-product marketing page

Designing fixed navigation with internal anchors

Building responsive card layouts using Flexbox

Embedding media content responsively

Creating scalable layout foundations for future JS integration

Potential Enhancements
Smooth scrolling for anchor links

Improved hover and focus states

Backend integration for email collection

Accessibility improvements (skip links, ARIA landmarks)

Testimonials and FAQ section

Author
Trevyn Sanders
Better Endeavors LLC