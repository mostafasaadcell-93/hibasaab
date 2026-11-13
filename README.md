# Hiba Saad Real Estate

Demo website for **Hiba Saad, Real Estate Consultant** (Beirut, since 2006 · Instagram [@hibasaad.realestate](https://www.instagram.com/hibasaad.realestate/)). Sale · Rent · +961 3 008 025 · +961 70 981 972.

## Pages
- **Home**: hero with search (buy/rent, type, location), featured listings, Rive Gauche spotlight, explore tiles, about, "List your property" form, contact
- **Properties** (`#/properties?deal=sale|rent&type=Office|Apartment&area=...`): filters and sorting
- **Property page** (`#/p/<id>`): gallery with full-screen viewer, key facts, description, highlights, Google Maps link, more properties
- **Saved** (`#/saved`): properties the visitor hearted (kept in their browser)

## WhatsApp
Every enquiry opens WhatsApp to +961 3 008 025 with the property name and link. Listings without a price show "On request" and the button asks for the price.

## Editing
In `index.html`: `CONFIG` (site address, WhatsApp, email, Instagram) and `PROPS` (one object per listing: `deal` `sale`/`rent`, `type`, `price` or `null`, size, photos, description, highlights). Photos go in `img/` as `name.webp` and `name-s.webp`.

## Run / deploy
No build step. Serve the folder or import the repo into Vercel / Cloudflare Pages.
