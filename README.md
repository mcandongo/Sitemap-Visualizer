# Sitemap Visualizer

A browser-based site architecture tool built for SEO analysis. Upload a Screaming Frog crawl export and instantly explore your site structure through interactive cluster cards and a zoomable tree view.

Built as an internal SEO tool to replace manual spreadsheet analysis of site architecture.

---

## Features

- **CSV Upload** — drag and drop or click to upload a Screaming Frog Internal HTML export
- **Cluster Cards View** — pages automatically grouped by URL path into clusters and subclusters, with page counts and status indicators
- **Tree View** — interactive hierarchical tree diagram showing the full site architecture, zoomable and pannable
- **Cluster-linked Tree** — clicking a cluster in the sidebar filters the tree to show only pages within that cluster
- **Status Filters** — filter pages by Noindex, Orphans, or 404s across the entire view
- **Search** — search pages by URL in real time
- **EN-only Toggle** — filter to English locale pages only (useful for multilingual sites)
- **Page Stats** — live counts of total pages, clusters, noindex pages, and orphans
- **Dark UI** — built with VEED's design system and brand fonts

---

## How to Use

1. Run a crawl in **Screaming Frog** on your target site
2. Export: `Reports → Internal → HTML` as CSV
3. Open `Sitemap_Visualizer_V1.html` in any browser
4. Drag and drop the CSV onto the upload zone — the dashboard loads instantly
5. Use the sidebar clusters, filters, and search to explore your site architecture

No installation, no server, no dependencies. Runs entirely in the browser.

---

## Built With

- Vanilla HTML, CSS, JavaScript
- No external libraries or frameworks

---

## Background

Built to solve a recurring problem on the VEED SEO team — understanding site architecture at scale without relying on engineering or expensive third-party tools. The V1 uses local CSV upload to keep crawl data private.

---

## Version

**V1** — CSV upload only (no external data connections)
