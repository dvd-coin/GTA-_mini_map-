# 🎮 GTA MiniMap Navigator

GTA V style GPS navigation app with real-time tracking and waypoint system.

![License](https://img.shields.io/badge/license-MIT-green)
![PWA](https://img.shields.io/badge/PWA-Ready-blue)
![Platform](https://img.shields.io/badge/platform-Web%20%7C%20Android%20%7C%20iOS-orange)

---

## ✨ Features

- 🗺️ **Circular Mini-Map** - GTA V style interface
- 📍 **GPS Tracking** - Real-time location
- 🎯 **Waypoint System** - Click or search destinations
- 🧭 **Direction Arrow** - Points to waypoint or heading
- 🛣️ **Route Planning** - Yellow route line
- ⚡ **Speed Meter** - Live km/h display
- 🧭 **Compass** - N/NE/E/SE/S/SW/W/NW directions
- 🔍 **Location Search** - Find places worldwide
- 📱 **PWA Ready** - Install as app
- 🌙 **Dark Theme** - Cyberpunk neon style

---

## 🚀 Quick Start

### Online (No Installation)

Visit: **https://YOUR-USERNAME.github.io/gta-minimap/**

### Install as App (PWA)

**Android:**
1. Open in Chrome
2. Menu → "Install app"
3. Done! App installed

**iOS:**
1. Open in Safari
2. Share → "Add to Home Screen"
3. Done! App installed

---

## 📱 How to Use

1. **Allow Location** - Grant GPS permission
2. **Set Waypoint** - Click map or use search 🔍
3. **Navigate** - Yellow arrow shows direction
4. **Reset** - 🔄 button removes waypoint

**Controls:**
- 🎯 Center to position
- ➕ Zoom in
- ➖ Zoom out
- 🔍 Search location
- 🔄 Reset waypoint

---

## 🛠️ Technologies

- **Leaflet.js** - Map rendering
- **OpenStreetMap** - Free map tiles
- **Photon Geocoder** - Location search
- **OSRM** - Routing (demo server)
- **PWA** - Progressive Web App
- **Service Worker** - Offline support

---

## 📦 Files

```
gta-minimap/
├── index.html           # Main application
├── manifest.json        # PWA configuration
├── service-worker.js    # Offline support
├── icon.svg            # App icon
└── README.md           # This file
```

---

## 🔧 Local Development

```bash
# Start local server
python -m http.server 8000

# Open browser
http://localhost:8000
```

**Requirements:**
- Modern browser (Chrome, Firefox, Safari)
- HTTPS or localhost (for GPS)
- Internet connection (for maps)

---

## 🌐 Deploy to GitHub Pages

See [GITHUB-DEPLOYMENT-GUIDE.md](GITHUB-DEPLOYMENT-GUIDE.md) for detailed instructions.

**Quick steps:**
1. Create GitHub repository
2. Upload files
3. Enable GitHub Pages in Settings
4. Visit your site!

---

## 📲 Create APK

### Option 1: PWABuilder (Recommended)
1. Visit https://www.pwabuilder.com
2. Enter your GitHub Pages URL
3. Generate Android package
4. Download APK

### Option 2: Capacitor
```bash
npm install @capacitor/core @capacitor/cli @capacitor/android
npx cap init
npx cap add android
npx cap open android
```

---

## 🎯 Roadmap

- [ ] Offline maps
- [ ] Save favorite locations
- [ ] Trip history
- [ ] Voice navigation
- [ ] Multiple themes
- [ ] Night mode
- [ ] Traffic information
- [ ] Custom routes

---

## 🤝 Contributing

Contributions welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

---

## ⚠️ Known Issues

1. **OSRM Demo Server** - Routing uses free demo server, may be slow
2. **GPS Accuracy** - Depends on device and location
3. **Internet Required** - Maps need connection
4. **Icons** - Need PNG icons for better PWA support

---

## 📄 License

MIT License - feel free to use and modify!

---

## 🙏 Credits

- Maps: OpenStreetMap
- Geocoding: Photon (Komoot)
- Routing: OSRM
- Inspiration: GTA V

---

## 💬 Support

Having issues? Create an issue on GitHub!

---

**Made with 💚 for GTA fans and navigation enthusiasts**

🎮 Drive safe! 🚗💨
