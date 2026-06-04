# Travel Bloom - Interactive Travel Recommendation Web Application

Travel Bloom is a modern, responsive single-page web application designed to help users seamlessly discover dream travel destinations. Users can search for specific categories—such as beaches, temples, or countries—and explore relevant location recommendations complete with clean typography, descriptive cards, and high-quality imagery. The application features a dynamic search layout engine that handles data state changes fluidly without forcing a browser refresh.

---

## 🚀 Features

* **Dynamic Data Fetching:** Utilizes the JavaScript Fetch API to read and extract structured array schemas from an internal JSON database.
* **Contextual Search Viewport:** Features a unique state-switching UX that automatically hides primary content landing blocks to display search results in a fully responsive layout grid, with a single-click fallback reversion to restore original layout contexts.
* **Fully Responsive Flexbox & Grid Systems:** Blends horizontal/vertical flex properties for user forms and team dashboards with an optimized CSS grid engine (`repeat(auto-fit, minmax(300px, 1fr))`) to dynamically scale travel product cards across any viewport size.
* **Sleek Glassmorphic & Accessible UI:** Modern dark UI framework accentuating custom placeholder states, white caret-color text focus indicators, and custom button animations.

---

## 🛠️ Tech Stack & Architecture

* **Frontend Structure:** HTML5 (Semantic document construction)
* **Design & Layout Engine:** CSS3 (Flexbox alignment, Grid layout tracking, and pseudo-element target configurations)
* **Application Logic:** Modern Vanilla JavaScript (ES6 asynchronous fetch cycles, Array manipulation patterns, and structural DOM injection)
* **Database Layer:** Structured JSON (Keyed categories handling relational array tracking)

---

## 📁 Project Directory Structure

```text
├── index.html            # Core structural markup and navigation wrappers
├── index.css             # Main stylesheet containing grid systems and form designs
├── index.js              # Core application logic, event handlers, and fetch hooks
├── index.json            # Mock database storing travel destination nodes
└── images/               # Asset directory (Logo, social assets, and destination cards)
    ├── logo.jpg
    ├── borabora.jpg
    ├── kinkakuji.jpg
    └── italy.jpg
