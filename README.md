# WearMoore.Shop

The storefront front-end for **MOORE**, an independent streetwear brand. This repository presents the HTML/CSS/JavaScript implementation from the v63 catalog build; the live business storefront is [wearmoore.shop](https://wearmoore.shop/).

## Features

- Responsive exhibition-style landing scenes and release vault
- Men's/unisex and women's product collections
- Product modal with front/back views, size and fit selections, and item-specific visuals
- Cart drawer with Shopify variant mapping and checkout handoff
- Motion and rotation media for garment presentation
- Semantic labels and keyboard dismissal for overlays

## Stack

Plain HTML, CSS, and JavaScript, with checkout handed to Shopify. The page is self-contained in `index.html` apart from its image/video assets.

## Source snapshot and assets

The original v63 deployment bundle contains hundreds of megabytes of branded product photography, artwork, garment renders, and video. This code-focused repository intentionally omits those proprietary media assets. Consequently, opening `index.html` from this repository alone will show missing media; the full experience is on the live site. No brand logo or artwork was recreated or altered for this portfolio copy.

The checked-in page includes public Shopify variant IDs and a checkout-domain handoff. The Storefront API token field is a placeholder; no private API credentials are included. This is a portfolio source snapshot, not an automated deployment of the live store.

## Local inspection

Open `index.html` in a browser to inspect the structure and interaction code. To reproduce the visual deployment, place the corresponding licensed v63 media files beside it and serve the folder with a local static HTTP server. Do not treat this repository as the source of truth for live product availability, inventory, or pricing.

