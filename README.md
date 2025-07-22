# 🦧 Orangutan Conservation Assistant (Powered by Gemma 3n)

### 🌍 **Offline-First | Bilingual (Bahasa Indonesia + English) | Conservation Tool**

## 📌 Overview

**Orangutan Conservation Assistant** is a **bilingual, offline-ready web and mobile app** built using **Gemma 3n**. It supports **conservation decision-making** for local communities, NGOs, and researchers in Indonesia by enabling:

✅ **Bilingual Q\&A** (Bahasa Indonesia & English)
✅ **Offline operation** in low-connectivity areas
✅ **Interactive maps** with orangutan sightings, protected areas, roads, and oil palm plantations
✅ **Privacy-first design** running **entirely on-device**


## 🚀 Why This Matters

Orangutans are **critically endangered**. Conservation teams work in **remote areas** where internet connectivity is unreliable. Gemma 3n enables:

* **Private AI reasoning** without internet
* **Efficient on-device processing** for field teams
* **Seamless bilingual communication** for local and international stakeholders

## ✨ Features

* **Interactive Mapping**

  * Visualise orangutan sightings, protected areas, rivers, roads, and oil palm plantations
  * Compute proximity to threats and conservation zones

* **Bilingual Conservation Q\&A**

  * Examples:
    *“How many orangutans are estimated in Kutai National Park?”*
    *“Berapa jarak perkebunan sawit terdekat dari taman ini?”*

* **Offline Mode**

  * Runs on-device with **pre-cached geospatial data**

## 🛠 Tech Stack

| Component        | Tech                                                           |
| ---------------- | -------------------------------------------------------------- |
| **AI Model**     | Gemma 3n                                                       |
| **Frontend**     | Gradio                                         |
| **Maps**         | Leaflet / Mapbox GL (offline tiles)                            |
| **Data Sources** | GBIF, OpenStreetMap, WDPA, Human Footprint, Hansen Forest Loss |

---

## 📂 Data Layers

* Orangutan locations (GBIF)
* Protected Areas (WDPA)
* Roads and Rivers (OSM)
* Oil Palm Plantations (World Resources Centre)
* Human Footprint Raster
* Elevation and Topography

## 📌 Example Queries

```
1. "How many orangutans are in Kutai National Park?"
2. "Berapa luas hutan lindung di Kalimantan Timur?"
3. "Which protected areas have the highest human footprint?"
```

## 🎯 Roadmap

* [x] Preprocess and integrate spatial datasets
* [x] Build bilingual Q\&A with Gemma 3n
* [x] Add interactive mapping UI
* [ ] Enable conservation risk scoring
* [ ] Deploy offline-first mobile app

## 🤝 Contributing

Pull requests are welcome! Open an issue for discussion before making changes.

## 📜 License

[MIT License](LICENSE)

## 🙌 Acknowledgments

* [Gemma 3n](https://ai.google.dev/gemma)
* [GBIF](https://www.gbif.org/)
* [OpenStreetMap](https://www.openstreetmap.org/)
* [WDPA](https://www.protectedplanet.net/)


### 🔥 Impact Statement

*"Helping protect Indonesia’s orangutans by bringing AI-powered, bilingual, offline-first conservation tools to remote forest communities."*

