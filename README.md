# Sonu Maurya — Portfolio

A responsive React portfolio with an ivory, charcoal, and terracotta visual palette. Built with Vite, React, custom CSS, and Lucide icons.

## Run locally

Use Node.js 22.12+ (or a supported newer release).

```sh
npm install
npm run dev
```

Open the local URL printed in the terminal.

## Production build

```sh
npm run build
npm run preview
```

The production files are generated in `dist/`.

## Deploy to Netlify

### Git deployment

1. Push this project to your Git repository.
2. Import the repository into Netlify.
3. Use build command `npm run build` and publish directory `dist`.

The included `netlify.toml` already configures these values, a single-page fallback, and basic response headers. No environment variables or backend service are required.

### Manual deployment

Run `npm run build`, then drop the `dist` folder into Netlify’s manual deployment area. A convenient `netlify-deploy.zip` containing the production files is also included in the project after delivery.

## Editing the portfolio

- `src/data.js`: LinkedIn URL, career timeline, work highlights, and skill groups.
- `src/main.jsx`: page sections, biography, education, certifications, and interactive components.
- `src/styles.css`: colors, typography, animation, and responsive layouts.
- `index.html`: title, description, and social metadata.
- `public/favicon.svg`: brand icon.

## Content notes

Content is based on the supplied LinkedIn screenshots. Duplicate and overlapping entries have been consolidated around named employers. RebusCode is shown as the overall May 2019–March 2021 tenure; the senior frontend role began September 2019. Edynamic and Altudo are grouped for the earlier UI role; some dates overlap with RebusCode in the supplied profile.

The three work highlights summarize documented professional contributions. Their small interface illustrations are original visual concepts, labeled as illustrative; they are not original product screenshots or public project demos. There are no invented project URLs, testimonials, business metrics, or contact details.

LinkedIn is the contact destination. The supplied portrait is included at `public/sonu-maurya.jpg`. An email address, résumé file, actual project images, and project URLs can be added when available. Earlier school entries and general office software skills have been omitted to keep the portfolio focused on frontend engineering.

## Interaction and accessibility

- Responsive navigation with a mobile menu and Escape-key dismissal.
- Work dialogs with Escape-key handling, contained keyboard focus, and focus restoration.
- Expandable experience entries with accessible state attributes.
- Keyboard-accessible skill tabs with left/right arrow navigation.
- Optional hero interface previews.
- Scroll reveal, hover, and ambient animations with `prefers-reduced-motion` support.
- Semantic sections, visible focus styles, and a skip-to-content link.

Fonts load from Google Fonts with system fallbacks. The site remains readable if the font service is unavailable.
