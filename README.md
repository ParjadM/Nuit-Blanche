# 🌃 Nuit Blanche 2025 - Interactive Art Map

An interactive, responsive, and user-friendly web application designed to help art enthusiasts explore and plan their night at Toronto's Nuit Blanche festival. This single-page application allows users to discover exhibits, filter them based on their needs, and build a personalized, draggable itinerary for the night.

---

## ✨ Features

This project is built with a focus on a clean user interface and a robust, interactive user experience.

* **🗺️ Interactive Leaflet Map**: A smooth, zoomable map of Toronto centered on the festival area, using OpenStreetMap and CartoDB tiles.
* **📍 Clustered Markers**: To keep the map tidy, exhibits in close proximity are clustered together and expand on zoom, powered by `Leaflet.markercluster`.
* **🔍 Real-time Search**: Instantly filter exhibits by title or artist name as you type.
* **✅ Attribute Filtering**: Filter exhibits by key attributes like "Wheelchair Accessible" and "Kid-Friendly".
* ** persoonlijke Itinerary ("My Night Plan")**:
    * **Add/Remove**: Users can add exhibits to a personal plan directly from the map popups.
    * **Persistent Storage**: The created plan is saved to the browser's `localStorage`, so it persists even after closing the tab.
    * **Drag & Drop Sorting**: Easily reorder the itinerary list to plan the perfect route, powered by `SortableJS`.
    * **Collapsible View**: The itinerary list can be collapsed to save screen space.
* **👤 Find Me Functionality**: Centers the map on the user's current geographical location.
* **🎨 Custom Styling**: A modern and cohesive design with custom-styled markers, popups, and controls that match the Nuit Blanche theme.
* **📱 Fully Responsive**: The layout adapts seamlessly from desktop to mobile devices for a great experience on the go.

---

## 🛠️ Tech Stack

This project was built using vanilla web technologies, demonstrating strong foundational skills in front-end development.

* **HTML5**: For the structure and content of the application.
* **CSS3**: For all styling, including custom properties (variables), Flexbox for layout, and responsive design with media queries.
* **JavaScript (ES6+)**: For all the application logic, including DOM manipulation, event handling, and state management.
* **[Leaflet.js](https://leafletjs.com/)**: An open-source JavaScript library for mobile-friendly interactive maps.
* **[Leaflet.markercluster](https://github.com/Leaflet/Leaflet.markercluster)**: A Leaflet plugin for clustering markers.
* **[SortableJS](https://github.com/SortableJS/Sortable)**: A JavaScript library for reorderable drag-and-drop lists.

---

## 🚀 Getting Started

Since this is a self-contained application with no backend or build process, running it is very simple.

1.  **Clone the repository (or download the files):**
    ```bash
    git clone [https://github.com/your-username/nuit-blanche-map.git](https://github.com/your-username/nuit-blanche-map.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd nuit-blanche-map
    ```
3.  **Open the `index.html` file:**
    You can simply open the `index.html` file directly in your web browser (e.g., Chrome, Firefox, Safari).

---

## 💡 Future Enhancements

This project has a solid foundation that can be expanded upon. Future ideas include:

* **Real-time Data**: Connect the app to a live API or a backend database (like Firebase) to fetch exhibit data dynamically.
* **Routing**: Integrate a routing service (like Leaflet Routing Machine) to draw a path between the items in the user's itinerary.
* **Social Sharing**: Allow users to share their created plan with friends via a unique link.
* **Offline Support**: Implement Service Workers to make the map and itinerary available even without an internet connection.

---

## 👤 Author

* **Parjad Minooei**
* **GitHub**: [@ParjadM](https://github.com/ParjadM)

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
