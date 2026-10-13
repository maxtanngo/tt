# TT Industries website recreation

A lightweight, responsive, static front-end recreation of the public TT Industries website, built with plain HTML, CSS and JavaScript. It can be hosted on GitHub Pages without a build step.

## Run locally

Open `index.html` in a browser, or use any local static-file server. No package installation is required.

## Publish with GitHub Pages

1. Add these files to a GitHub repository.
2. In **Settings → Pages**, select **Deploy from a branch**.
3. Select the default branch and `/ (root)`.

## Included

- Responsive home page, about, product listing and detail, news, contact, cart, quote request, account, favorites, password recovery and order-tracking screens.
- Search, category filtering, sorting and pagination across all 95 products found in the public catalogue.
- Quote-request cart and favorites stored in the visitor's browser.
- A built-in Vietnamese product assistant that searches the catalogue and routes visitors to quote, contact and order-tracking pages.
- Original public website imagery referenced from `ttindustries.com.vn`.
- The supplied T&T logo saved locally and used for the site identity, browser tab icon and social preview metadata.
- A custom headset-support avatar illustration used in the chatbot launcher and chat panel.

## Source coverage and functional limits

The public catalogue has eight pages and reports 95 products; their public names, categories, and image paths were collected for this recreation. Product prices, complete specifications, full article text, stock data, accounts, checkout, order status, and actual contact-form delivery depend on the original site's private/server-side systems and are not available in this static project. The contact form and order tracking therefore explain their connection requirement rather than claiming a real submission succeeded. Product images and logos are hot-linked from the original public site; copy them into this repository if you need them to remain available independently.

The source site uses WordPress/WooCommerce and may change over time. This repository is a static visual recreation, not a copy of its theme, database, or server implementation.

## Chat assistant

The chat assistant works without an API key and searches the bundled catalogue in the visitor's browser. It provides product links and public contact details, and points visitors to the quote and order-tracking pages. It does not make up technical specifications, inventory, delivery times or prices. To connect a generative AI service later, add a server-side API route and keep its secret key out of the GitHub Pages JavaScript bundle.
