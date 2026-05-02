# Cousins Do the Mediterranean

A personalized 9-night cruise itinerary for the **Carnival Legend**, Rome roundtrip, **October 23 – November 1, 2026**.

Single-file static site. Deploys to Netlify with zero config — no build step, just `index.html` at the root.

## Edit

- All content and styling live in `index.html`.
- Photos use Unsplash CDN URLs. Swap any of them by replacing the `https://images.unsplash.com/photo-...` URL inside the corresponding `.day-hero` background-image.
- Each day section is wrapped in `<section class="day-section" id="dayN">`. Easy to find with search.

## Deploy

Drop the folder onto Netlify, or connect this GitHub repo to a Netlify site. No build command, publish directory is the repo root.
