# FACELOOK 2.0 — Luxury Unisex Salon (MERN)

A premium unisex salon website with **two themed worlds** sharing one layout system:

- **Men's Atelier** (`/men`) — dark espresso + gold-bronze, sharp editorial geometry (inspired by the Perukar design reference)
- **Women's Maison** (`/women`) — blush + rose-gold + champagne, soft serif elegance, rounded organic geometry

The landing page (`/`) is a cinematic split-screen — choose your world.

## Stack

| Layer     | Tech |
|-----------|------|
| Frontend  | React 18 (JSX) + Vite, React Router 6 |
| Animation | Framer Motion, GSAP + ScrollTrigger, Lenis smooth scroll, Three.js particles |
| Backend   | Node + Express |
| Database  | MongoDB via Mongoose (**optional** — automatic in-memory fallback) |

## Run it

Requires Node 18+.

### 1. Frontend

```bash
cd client
npm install
npm run dev        # http://localhost:5173
```

### 2. Backend (optional but recommended)

```bash
cd server
npm install
npm run dev        # http://localhost:5000
```

The Vite dev server proxies `/api/*` to `localhost:5000`. If MongoDB isn't
running, the API automatically stores bookings in memory so the whole flow
still works. To use MongoDB, copy `server/.env.example` to `server/.env`.

### Production build

```bash
cd client && npm run build   # outputs client/dist — deploy to any static host
```

Point the frontend at your deployed API (or serve `dist` from Express).

## Pages (identical in both worlds, themed differently)

Home · About · Services · Pricing · Stylists · Gallery · Video Gallery ·
Products · Membership · Offers · Testimonials · Awards · FAQs · Blogs ·
**Booking (7-step wizard: World → Branch → Service → Stylist → Date → Time → Confirm)** · Contact

## Design system

Both themes are pure CSS custom properties on `[data-theme="men"|"women"]`
in `client/src/styles/global.css` — same components, same spacing scale
(5px base grid, 120px sections, 160px hero — from the Perukar token set),
different color/typography/radius personalities. Swap a theme by changing
one attribute.

- Men: `Outfit 800` uppercase display, radius 0, espresso `#14100c`, bronze `#91765a`, gold `#c8a97e`
- Women: `Cormorant Garamond 600` display, radius 26/50px, rose gold `#b76e79`, blush `#f9ede9`, champagne `#f3e0da`

## Content & images

All copy/data lives in `client/src/data/{men,women,shared}.js`.
Images are in `client/public/images/` — replace with your own photography
(same filenames) to rebrand instantly.

## Notes

- The video gallery uses poster cards — drop your YouTube/Vimeo embeds into `components/cards.jsx → VideoCard`.
- Map placeholder on Contact — paste your Google Maps embed.
- Booking API: `POST /api/bookings`, `GET /api/bookings`, `GET /api/bookings/:reference`.
