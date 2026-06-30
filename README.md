# Pioneer Water Tanks Kenya

A single-page, responsive website for Pioneer Water Tanks Kenya — a Kenyan water tank retailer selling and delivering tanks across Kenya and East Africa.

🔗 **Live demo:** enable GitHub Pages (see below) and the link will appear here.

## Features

- One-page scrollable layout (Home, About, Products, Prices, Gallery, Delivery, Testimonials, FAQ, Contact)
- Hero slideshow with rotating background images and cycling headline text
- Pricing section with placeholder tank capacities and a 15–20% discount applied
- Filterable project gallery with a "Show More" button so it never feels overcrowded
- Testimonial carousel with verified-order badges
- WhatsApp booking modal — collects name, phone, tank size, colour, quantity and location, then opens a pre-filled WhatsApp chat
- Fully responsive (mobile, tablet, desktop)
- No build step, no dependencies — plain HTML, CSS and JavaScript in a single file

## Tech stack

Plain HTML5, CSS3 and vanilla JavaScript. No framework, no bundler, no `npm install` required.

## Getting started locally

Clone the repo and open `index.html` directly in your browser, or serve it locally:

```bash
git clone https://github.com/YOUR-USERNAME/pioneer-water-tanks-kenya.git
cd pioneer-water-tanks-kenya
# Option A: just open it
open index.html        # macOS
start index.html        # Windows

# Option B: serve it (recommended, avoids any local file restrictions)
npx serve .
# or
python3 -m http.server 8000
```

## Deploying with GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save — your site will be live at `https://YOUR-USERNAME.github.io/pioneer-water-tanks-kenya/` within a minute or two.

## Customizing

All content lives in `index.html`:

- **WhatsApp number** — search for `WA_NUMBER` in the `<script>` section to update the booking number.
- **Prices** — edit the `priceData` array to update tank capacities, prices and discounts.
- **Gallery images / testimonials** — edit the `galleryData` array and the testimonial cards in the HTML.
- **Images** — currently using [picsum.photos](https://picsum.photos) placeholder images. Replace the `src` / `background-image` URLs with your own real photos before going live.
- **Colors / fonts** — defined as CSS custom properties at the top of the `<style>` block (`:root { --navy: ...; --blue: ...; }` etc).

## License

This project is provided as-is for Pioneer Water Tanks Kenya. Replace placeholder content (prices, images, contact details) with real data before publishing live.
