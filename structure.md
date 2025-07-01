# Bewild App Structure Documentation

## Overview
BeWild is a nature-first e-commerce storefront built with a clean component-based architecture prioritizing readability, responsiveness, and sustainability storytelling. It is best suited for React, styled-components, or Tailwind CSS.

## Directory Structure

```
src/
├── components/
│   ├── Navbar/
│   ├── HeroBanner/
│   ├── ProductCategories/
│   ├── FarmingPractices/
│   ├── WhyChooseUs/
│   ├── ExpertsSection/
│   ├── Footer/
│   ├── ProductCard/
│   ├── ProductDetails/
│   ├── SustainabilityPage/
│   ├── AboutPage/
│   └── ContactForm/
├── assets/
├── pages/
│   ├── index.tsx
│   ├── shop.tsx
│   ├── about.tsx
│   ├── contact.tsx
│   ├── sustainability.tsx
│   └── product/[id].tsx
├── App.tsx
├── main.tsx
└── styles/
    └── globals.css
```

## Component Highlights

### HeroBanner
- Strong visual, short tagline
- CTA in assertive color

### ProductCategories
- Grid layout
- Icons or minimal product previews

### FarmingPractices
- Illustrated steps
- Icons with 1-line descriptions

### Footer
- Compact
- Brand tone, links, and social

## Stack Recommendations

- **React + TypeScript**
- **Tailwind CSS** for fast styling
- **Framer Motion** for animations

## Features to Consider
- Mobile-first structure
- Lazy loading images
- Product filtering on shop page
- JSON-driven content for flexibility