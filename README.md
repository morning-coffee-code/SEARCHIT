# SearchIT

**SearchIT** is a single-page web app that lets you look up any topic — a person, place, concept, or event — and instantly view a clean, styled summary sourced from Wikipedia.

## Features

- 🔍 **Instant lookup** — type any topic and get the best-matching Wikipedia article
- 🖼️ **Rich result card** — title, thumbnail image (when available), and summary text laid out in a magazine-style card
- 📄 **Expandable detail** — additional paragraphs from the article are shown under a "More detail" section
- 🔗 **Direct link** — a "Full article ↗" button opens the source Wikipedia page in a new tab
- 💡 **Quick-search chips** — one-click suggestions (Artificial Intelligence, Black Hole, Renaissance, DNA, Mahatma Gandhi, Photosynthesis)
- ⏳ **Loading & error states** — animated spinner while fetching, and a friendly message if no article is found or the connection fails
- 📱 **Responsive design** — adapts layout for smaller screens

## How It Works

1. The user types a query into the search box (or clicks a suggestion chip) and presses Enter or clicks **Explore**.
2. The app calls the **Wikipedia Search API** (`action=query&list=search`) to find the best-matching article title for the query.
3. It then calls the **Wikipedia REST Summary API** (`/api/rest_v1/page/summary/{title}`) to fetch the article's extract, thumbnail image, and canonical URL.
4. The result is rendered into a styled card; if no article is found or the extract is missing, an error state is shown instead.

## Tech Stack

- Plain **HTML, CSS, and vanilla JavaScript** — no frameworks, no build step, no dependencies
- Google Fonts: *Playfair Display*, *Inter*, *Lora*
- Data source: [Wikipedia API](https://www.mediawiki.org/wiki/API:Main_page) (public, no API key required)

## Usage

Just open the HTML file in any modern web browser — it works entirely client-side. No installation, server, or build process is needed.

## File Structure

```
index.html   → contains all markup, styles, and script in a single self-contained file
```

## Notes

- Requires an internet connection, since it fetches live data from Wikipedia at query time.
- All content displayed is sourced from Wikipedia and is subject to Wikipedia's [terms of use](https://foundation.wikimedia.org/wiki/Policy:Terms_of_Use) and content licensing (CC BY-SA).
