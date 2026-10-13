# 🇺🇸 United States Street Food Guide

An interactive, single-file web guide to **20 iconic American street foods** — from a folded NYC pizza slice to a Tucson Sonoran hot dog. Explore every dish on a live map, filter by region, and search by name, city, or description.

![United States Street Food Guide](https://raw.githubusercontent.com/palakpeshwani69428-del/us-street-food-guide/main/index.html)

## ✨ Features

- **🗺️ Interactive map** — 20 custom emoji markers pinned to their home cities, color-coded by category, powered by [Leaflet](https://leafletjs.com/) + CARTO tiles.
- **🔍 Live search** — instantly filter dishes by name, city, state, category, or description.
- **🏷️ Category filters** — one click to narrow down to BBQ, Northeast, Southern, Tex-Mex, West Coast, Midwest, Seafood, Hawaiian, Latin, or Pacific NW.
- **🔗 Map ↔ list sync** — click a marker to scroll to and highlight its card; click a card to fly the map to its marker and open the popup.
- **📱 Fully responsive** — side-by-side map + list on desktop, stacked layout on mobile.
- **🎨 Warm, editorial design** — Playfair Display + Inter typography with a rust/amber/cream palette.

## 🍽️ The 20 Dishes

| # | Dish | City | Category |
|---|------|------|----------|
| 1 | NYC-Style Pizza Slice | New York, NY | Northeast |
| 2 | Philly Cheesesteak | Philadelphia, PA | Northeast |
| 3 | Chicago Deep Dish Pizza | Chicago, IL | Midwest |
| 4 | New Orleans Po'Boy | New Orleans, LA | Southern |
| 5 | Texas Smoked Brisket | Austin, TX | BBQ |
| 6 | LA Street Tacos | Los Angeles, CA | Tex-Mex |
| 7 | Maine Lobster Roll | Portland, ME | Seafood |
| 8 | Detroit Coney Dog | Detroit, MI | Midwest |
| 9 | Nashville Hot Chicken | Nashville, TN | Southern |
| 10 | SF Mission Burrito | San Francisco, CA | West Coast |
| 11 | Hawaiian Poke Bowl | Honolulu, HI | Hawaiian |
| 12 | Kansas City Burnt Ends | Kansas City, MO | BBQ |
| 13 | Memphis BBQ Ribs | Memphis, TN | BBQ |
| 14 | Seattle Teriyaki | Seattle, WA | Pacific NW |
| 15 | Portland Food Cart Pad Thai | Portland, OR | Pacific NW |
| 16 | Miami Cuban Sandwich | Miami, FL | Latin |
| 17 | Charleston Shrimp & Grits | Charleston, SC | Southern |
| 18 | Tucson Sonoran Hot Dog | Tucson, AZ | Tex-Mex |
| 19 | Milwaukee Cheese Curds | Milwaukee, WI | Midwest |
| 20 | New England Clam Chowder | Boston, MA | Seafood |

## 🚀 Usage

No build step, no dependencies to install. Just open the file:

```bash
git clone https://github.com/palakpeshwani69428-del/us-street-food-guide.git
cd us-street-food-guide
open index.html      # macOS
# or: xdg-open index.html   (Linux)  /  start index.html  (Windows)
```

Or serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

> An internet connection is required for the map tiles (CARTO), Leaflet, Google Fonts, and the dish photos, which are loaded from their original sources.

## 🛠️ Tech Stack

- **HTML5 + CSS3 + vanilla JavaScript** — everything lives in a single `index.html`
- **[Leaflet 1.9.4](https://leafletjs.com/)** — open-source interactive maps
- **CARTO Voyager tiles** — map basemap
- **Google Fonts** — Playfair Display & Inter

## 📁 Project Structure

```
us-street-food-guide/
├── index.html   # The complete app — markup, styles, data, and logic
└── README.md    # This file
```

## 📄 License

Released for educational and personal use. Dish descriptions are original summaries; photographs are loaded from their respective third-party sources and remain the property of their owners.
