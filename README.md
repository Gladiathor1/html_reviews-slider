# Furniture Store Homepage Sections

Hand-coded HTML/CSS (with a little vanilla JavaScript) sections for a futon and furniture e-commerce homepage. Each file is a self-contained section that can be dropped into a page builder or theme; `fullpage.html` puts them all together.

## Sections

| File | Section |
| --- | --- |
| `Review.html` | **Customer review slider** — testimonial cards with previous/next controls written in plain JavaScript |
| `crzy earth best sellers.html` | Best-sellers product slider with prices, sale prices and colour swatches |
| `main.html` | Hero banner ("Warehouse Sale: up to 70% off") |
| `featuredIn.html` | Promo banner ("Biggest sale of the year") |
| `featuredOn.html` | "As featured on" press logos |
| `oprahfavourite.html` | Two-column feature block (image + heading, text and button) |
| `shop-collection.html` | "Shop our collection" category grid |
| `fullpage.html` | All sections combined into one homepage |

## Tech

- Plain HTML and CSS (Flexbox, responsive media queries)
- Vanilla JavaScript for the sliders
- Font Awesome icons (CDN)

## Usage

There is no build step. Open any file directly in a browser, e.g.:

```bash
start fullpage.html      # Windows
open fullpage.html       # macOS
```

To reuse a section, copy its `<style>`, markup and `<script>` into your page.
