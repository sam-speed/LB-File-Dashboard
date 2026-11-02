# LB File Dashboard

A modern, sleek, and responsive web dashboard for analyzing folder and subfolder storage space in real-time directly from your browser, with 100% client-side privacy.

---

## Key Features

* **Real-Time Analytics & KPIs**: Quickly view total storage size, subfolder count, largest folder, and estimated monthly growth.
* **Interactive Charts (Chart.js)**:
* Storage distribution by year (parsed from folder names, e.g., `2026-Projects`).
* Top 20 largest elements in the directory.


* **IndexedDB Persistence**: Using modern browser APIs, selected directories are saved locally for quick, persistent access.
* **Growth Projection Calculator**: An interactive simulator with sliders to estimate future storage usage based on a target year and custom growth rate.
* **Privacy First (Client-Side)**: Leverages native File System Access APIs to read files directly on your machine without external servers.

---

## Tech Stack

* **HTML5 / CSS3** (featuring custom Dark Mode styling & neon purple accents).
* **Vanilla JavaScript (ES6+)** for recursive directory scanning logic.
* **Chart.js** for data visualization.
* **IndexedDB** for storing local directory permissions and references.

---

## How to Use

1. Download or clone this repository.
2. Save the file as `index.html`.
3. Open it in a modern Chromium-based browser (Google Chrome, Microsoft Edge, Opera).

---

## Credits & Acknowledgments

* Created with the assistance of Gemini 3.

---

## License

Distributed under the MIT License. Feel free to use, modify, and improve this project!
