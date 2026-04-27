# DJI Mission Tool — HUD

A **dark, futuristic drone mission planner** for DJI Pilot / DJI Enterprise workflows.

This tool allows you to:
- Import and clean **DJI‑compatible KML files**
- Draw **drone operation areas (polygons)** and **flight paths**
- **Automatically close and validate polygons** for DJI Pilot
- Estimate **GSD, coverage, photo count, flight time**
- Generate **zigzag photogrammetry routes**
- Export everything as a **DJI Pilot–ready ZIP**

> 100% client‑side • No backend • No DJI account required

---

## ✈️ Key Features

- **Dark HUD / Drone‑inspired UI**
- KML import / export compatible with **DJI Pilot**
- Polygon & line drawing (Leaflet + Leaflet.draw)
- Flight‑planning estimations:
  - Ground Sample Distance (GSD)
  - Photo footprint
  - Line spacing (front / side overlap)
  - Estimated route length & duration
  - Estimated number of photos
- Automatic **zigzag route generation**
- ZIP export with `_DJIpilot.kml` naming
- Works offline (once loaded)

---

## 🛰️ Typical Use Cases

- Drone photogrammetry (topography, orthophotos)
- Engineering & infrastructure surveys
- Construction monitoring
- Public works & urban planning
- Pre‑mission planning for DJI Enterprise drones

---

## 🧠 Technical Stack

- **HTML / CSS / Vanilla JS**
- **Leaflet 1.9**
- **Leaflet.draw**
- **JSZip**
- No framework, no build step

---

## 🚀 Getting Started

1. Download or clone this repository
2. Open `index.html` in a modern browser
3. Import or draw your mission
4. Export the ZIP and load it into **DJI Pilot**

---

## ⚠️ Notes & Assumptions

- Route generation uses a **rotated bounding box approach**
- Clipping inside complex polygons is not yet implemented
- Estimations are indicative and must be validated before flight

---

## 📜 License

MIT License — free to use, modify, and adapt.

---

## ✨ Author

Built by **Baptiste Girard**  
Drone operations • Engineering • GIS • Public infrastructure
