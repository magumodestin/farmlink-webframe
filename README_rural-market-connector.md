# Rural Market Connector

A UI/UX design concept for a farmer-to-buyer marketplace built for rural South Africa. This project is a single-page HTML presentation of the wireframes, user flows, feature plan, and design system, designed mobile-first with low-data conditions and a WhatsApp-based MVP in mind.

## Overview

Rural Market Connector aims to link small-scale farmers directly with nearby buyers, cutting out middlemen and reducing produce waste. Farmers list their produce with a photo, quantity, and price. Buyers browse by area, view the farmer's profile and ratings, and contact the farmer through WhatsApp or place an order.

## What's Inside

### Step 1: Wireframes and UI Screens

Three annotated phone mockups:

- **Screen 1, Farmer: List Produce** - upload a photo, enter quantity and price, and publish a listing
- **Screen 2, Buyer: Browse Market** - browse nearby produce with price, farmer name, rating, and distance
- **Screen 3, Buyer: Order Screen** - product details, farmer profile, quantity selector, delivery options, and WhatsApp or order buttons

### Step 2: User Flows

- **Farmer listing flow:** Sign up, add produce, receive a price suggestion, go live
- **Buyer purchase flow:** Browse, view listing, contact via WhatsApp or order, pickup or delivery

### Step 3: Features

| Feature | Description | Stage |
| --- | --- | --- |
| Offline / low data mode | Core listings cached locally, works on 2G, images compressed | MVP |
| Waste alert discounts | Farmers mark stock as urgent and nearby buyers see a discount badge | MVP |
| WhatsApp integration | Buyers contact farmers directly, no payment system needed yet | MVP |
| Smart pricing | Suggested price range based on nearby listings and seasonal demand | Phase 2 |
| Ratings and verification | Farmers and buyers are rated, verified badge after 3 sales | Phase 2 |
| Bulk buying (B2B) | Restaurants and shops post bulk requests and farmers respond with quotes | Phase 3 |

### Step 4: Design System

- **Colors:** Earth Dark `#2D4A1E`, Earth Mid `#4A7C35`, Leaf Green `#6DAA3F`, Lime Accent `#A8CC5A`, Clay `#C8A96E`, Rust / Urgent `#D4651A`, Sand Background `#F5F0E8`
- **Typography:** Syne (display and headings) and DM Sans (body, captions, and buttons), loaded from Google Fonts

## Technologies Used

- HTML5
- CSS3 (custom properties, flexbox, grid)
- Google Fonts (Syne, DM Sans)

No JavaScript, frameworks, or build tools are required.

## How to Run

1. Clone or download this repository:
   ```
   git clone https://github.com/your-username/rural-market-connector.git
   ```
2. Open the HTML file in any modern browser. To use it with GitHub Pages, rename it to `index.html`.

An internet connection is needed only to load the Google Fonts.

## Project Structure

```
rural-market-connector/
├── index.html    # Wireframes, flows, features, and design system
└── README.md
```

## Roadmap

- Build the high-fidelity design system in Figma
- Develop the MVP with listings, browsing, and WhatsApp contact
- Add smart pricing, ratings, and verification
- Introduce bulk buying for businesses

## Author

Created by Destin.

## License

This project is open source and available for personal and educational use.
