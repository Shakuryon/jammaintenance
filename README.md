# JAM Maintenance LLC — website concept

One-page demo site for **JAM Maintenance LLC**, a full-service construction and home improvement company in Rahway, NJ (roofing, siding, gutters, windows, chimney, masonry). Built by [ShakurWebsites](https://github.com/Shakuryon) as a pitch concept. It is not yet the business's official site, and it is set to `noindex` until they approve it.

## Structure

```
public/
├── index.html      # single page: hero, services, why JAM, reviews, service area, contact
├── styles.css      # base styles (flexbox only, no grid)
├── media.css       # responsive breakpoints (1000px, 820px, 600px)
├── index.js        # mobile nav, scroll reveal, footer year
└── assets/
    └── favicon.svg
netlify.toml        # publishes the public/ folder
```

Hand-coded HTML, CSS and vanilla JS. No build step, no dependencies. Open `public/index.html` in a browser to preview.

## Business info used

| Item | Value | Source |
| --- | --- | --- |
| Phone | (732) 620-3864 | Facebook page, BBB |
| Email | jammaintenancellc@gmail.com | Facebook page |
| Address | 675 Hemlock Street, Rahway, NJ 07065 | Facebook page, BBB |
| Founded | 1997 | Experience.com listing |
| Reviews | 98% recommend, 107 reviews | Facebook page (Nov 2026) |
| Services | Roofing, siding, gutters, windows, chimney, masonry, carpentry, basement remodeling, roof cleaning | Experience.com, Yelp, Nextdoor, customer reviews |
| Perks | Free quotes, warranties, 10% senior discount, emergency service | Experience.com listing |
| Service area | Central NJ; jobs seen in Rahway, Woodbridge, Red Bank, Toms River, Bay Head | Facebook posts, reviews, permits |

## Confirm with the client before going live

- **Hours**: only Friday 9:00 AM – 5:30 PM (closed weekends) is confirmed; Mon–Thu is assumed to match.
- **License number** (NJ HIC #13VH03904900): taken from a BuildZoom listing, not from the business directly.
- **Service-area list** and the full **services list**.
- **Photos**: the demo uses no project photos. Their Facebook page has plenty of before/after shots to drop into `public/assets/`.
- Remove the `noindex` meta tag and the "design concept" footer line once it becomes the official site.

## Deploy

Netlify: publish directory is `public` (see `netlify.toml`). No build command.
