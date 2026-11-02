# Ember & Oak Interiors

Ember & Oak Interiors is a responsive five-page website for a Cape Town furniture and home décor studio. It presents handcrafted, sustainable pieces from local South African artisans across Home, About Us, Shop, Custom Orders, and Contact pages.

## Part 3 implementation notes

The site now includes JavaScript-enhanced category filtering, live product search, an image lightbox gallery, mobile navigation, dynamic year content, inline client-side validation errors, phone and email format checks, accessible success states, and a map embed for the Woodstock showroom. HTML5 `required`, `type`, `autocomplete`, and form `action` attributes remain in place as the no-JavaScript fallback layer. The contact and custom-order forms include the recipient email in their `mailto:` action for the assignment fallback requirement.

On-page SEO includes descriptive page titles and meta descriptions, semantic heading structure, meaningful internal links, descriptive image alternative text, mobile-friendly responsive CSS, `robots.txt`, `sitemap.xml`, and the managed route manifest. The visual assets are reused from the supplied Part 1 and Part 2 archives and served from the project `dist/assets` directory for reliable preview and publication.

## Changelog

### 2026-11-02 — Part 3 functionality and SEO enhancement

- Added live product search alongside category filters so visitors can narrow the collection by product name and category.
- Added a keyboard-accessible lightbox gallery to the Shop page. Product imagery opens in an overlay with an accessible close button, caption, Escape-key support, and background-click close behavior.
- Added custom JavaScript form validation with inline error messages, `aria-invalid` state, required-field checks, email validation, and phone-number format validation. Successful submissions now produce a focused status message without a page refresh.
- Added form actions and native HTML validation attributes as graceful fallbacks for the contact, custom-order, and newsletter forms.
- Added `robots.txt`, `sitemap.xml`, descriptive metadata, semantic route declarations, and internal navigation links to improve crawlability and on-page SEO.
- Preserved the Part 2 earthy visual system, responsive breakpoints, supplied artwork, accessible labels, Google Maps embed, and mobile navigation.

### 2026-09-19 — Part 2 CSS and responsive design

- Created the external stylesheet and applied a warm oak, terracotta, sage, cream, and sand palette.
- Implemented responsive layouts with grid and flexbox, including product cards, forms, header navigation, and footer behavior.
- Added hover, focus, active, and reduced-motion states for interactive controls.

## Local preview

```bash
npm start
```

The managed project serves the static site from `dist/` on port 3000.
