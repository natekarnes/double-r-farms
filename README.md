# Double R Farms

Website for **Double R Farms**, a third-generation family pumpkin patch and 5-acre corn maze at
5820 44th Street East, Puyallup, WA 98371 · (253) 227-5385.

It's plain HTML and CSS, with no build step and nothing to install, so it loads fast on phones.

| File | What it is |
| --- | --- |
| `index.html` | The whole site: things to do, prices, story, FAQ, map |
| `styles.css` | Colors, fonts and layout |
| `images/` | Photos (drop new ones here) |
| `robots.txt`, `sitemap.xml` | Help search engines find the site |

## Preview locally

Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

## Deploy

Works on any static host. On Netlify: **Add new site → Import from GitHub → pick this repo**.
Leave the build command empty and set the publish directory to `.`. Then point the
`double-r-farms.net` domain at it under **Domain management**.

## Each season, update

- **Prices** in the `#prices` section of `index.html`, and in the `makesOffer` block of the JSON-LD at the top
- **Hours/dates** in the FAQ (both the visible FAQ and the `FAQPage` JSON-LD)
- **Photos** in `images/`

## Getting more visitors

The site includes search-friendly titles, local business structured data (for Google Maps and rich
results), an FAQ, and share previews for Facebook and text messages. The biggest wins beyond the site:

1. **Google Business Profile**: claim or verify it at business.google.com. Add October hours, photos,
   and the website link. This is how most people find pumpkin patches ("pumpkin patch near me").
2. **Google Search Console**: verify the domain and submit `sitemap.xml`.
3. **Facebook & Instagram**: post photos every weekend in October and link back to the site.
4. **Local listings**: submit to pumpkin patch directories (e.g. pumpkinpatchesandmore.org),
   Travel Tacoma + Pierce County, and local parent/family event calendars.
5. **Reviews**: ask happy families to leave a Google review; a small sign with a QR code at checkout works well.
