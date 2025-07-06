# 📍 Web-Based IP Log Location Tracker (Sci-Fi Map)

**Live Demo:**
👉 [https://aashoosharma.github.io/Web-google-map/](https://aashoosharma.github.io/Web-google-map/)

This project visualizes location logs from a CSV file on a **sci-fi themed Leaflet map**.
Each user is shown with a **unique color**, and you can **filter users interactively** with toggles.

---

### 🧠 Features

✅ Automatically loads and parses `logs.csv`
✅ Plots all user locations with color-coded markers
✅ Live filter: toggle users to show/hide on the map
✅ “Select All” and “Deselect All” buttons
✅ Glowing sci-fi look using dark tiles + Orbitron font
✅ Auto zoom to selected user points

---

### 📂 Folder Structure

```
📁 Web-google-map/
├── index.html         ← Main interactive map page
├── logs.csv           ← CSV file with IP + location logs
└── README.md          ← Project info
```

---

### 🗂️ Sample logs.csv Format

```csv
user_id,username,ip,lat,lon,time
001,Aashoo,122.1.1.1,26.91,75.78,2025-07-06 20:30
002,Riya,142.2.2.2,28.61,77.23,2025-07-06 20:45
003,John,189.3.3.3,19.07,72.88,2025-07-06 21:00
001,Aashoo,122.1.1.1,24.58,73.68,2025-07-06 21:30
002,Riya,142.2.2.2,27.1767,78.0081,2025-07-06 21:40
003,John,189.3.3.3,13.0827,80.2707,2025-07-06 21:50
```

---

### 🛠️ Technologies Used

* [Leaflet.js](https://leafletjs.com/) – Open source JS map library
* [PapaParse](https://www.papaparse.com/) – CSV parsing in JavaScript
* [CARTO Dark Tiles](https://carto.com/) – Sci-fi themed map
* Vanilla JS + HTML + Orbitron font

---

### 🎯 Use Cases

* Cybersecurity dashboards (track users/IPs)
* Location-based log analysis
* Map-based visual storytelling
* Sci-fi themed projects or hackathons

---

### 📸 Screenshot

![sci-fi map preview](https://github.com/AashooSharma/Web-google-map/raw/main/screenshot.png)
*(Make sure you add a screenshot named `screenshot.png` in your repo)*

---

### 📥 Clone & Run Locally

```bash
git clone https://github.com/AashooSharma/Web-google-map.git
cd Web-google-map
python -m http.server  # Or open index.html using Live Server extension
```

---

### 🙌 Contribute

Feel free to:

* Add animations / effects
* Add real-time sync or API-based location tracking
* Improve mobile responsiveness

---

### 🔐 Credits

Developed by [Aashoo Sharma](https://aashoosharma.tech)
Font by Google Fonts – [Orbitron](https://fonts.google.com/specimen/Orbitron)
Map Tiles by [CARTO](https://carto.com/) and [OpenStreetMap](https://www.openstreetmap.org)

---
