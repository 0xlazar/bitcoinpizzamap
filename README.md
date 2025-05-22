# Bitcoin Pizza Map

Discover and track blockchain events around the world with an interactive, mobile-friendly map.

## Features

- 🌍 Interactive world map with event clustering
- 🍕 Fun, pizza-themed event markers
- 📋 List view and map view toggle
- 🔍 Search and filter events
- 📱 Mobile-friendly, responsive design
- ⚡ Progressive Web App (PWA) with offline support

## Tech Stack

- HTML5 + Tailwind CSS
- JavaScript (Vanilla)
- Leaflet.js (maps & clustering)
- PWA (manifest, service worker)

## Project Structure

```
bitcoinpizzamap/
├── data/              # Event data (JSON)
├── icons/             # App and PWA icons
├── scripts/           # Main JS logic
├── index.html         # Main HTML file
├── manifest.json      # PWA manifest
├── sw.js              # Service worker
├── LICENSE            # License file
├── .gitignore         # Git ignore rules
```

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/0xlazar/bitcoinpizzamap.git
   cd bitcoinpizzamap
   ```

2. **Serve the project locally:**
   - With Python:
     ```bash
     python -m http.server 8000
     ```
   - With Node.js:
     ```bash
     npx serve
     ```

3. **Open your browser:**
   - Visit `http://localhost:8000` (Python) or `http://localhost:3000` (Node.js)

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

MIT

---

Enjoy the journey! 🍕🌍 