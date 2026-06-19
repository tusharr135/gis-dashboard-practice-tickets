# Practice Tickets – GIS Dashboard Enhancements

## 📌 Overview

This repository contains solutions to practice tickets completed for a **Smart GIS Dashboard** built using **HTML, CSS, JavaScript, Leaflet.js, and Leaflet MarkerCluster**. The purpose of these tickets was to improve the dashboard's functionality, usability, and user experience.

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Leaflet.js
* Leaflet MarkerCluster
* OpenStreetMap
* Lucide Icons

---

## 🎯 Practice Tickets Completed

### ✅ Ticket 1: Marker Clustering Not Updating on Layer Toggle

**Problem**

* Marker clusters were not refreshing correctly after enabling or disabling map layers.

**Solution**

* Updated the layer toggle logic.
* Added proper add/remove operations for marker cluster groups.
* Refreshed cluster rendering after each toggle.

**Result**

* Marker clusters now update correctly whenever a layer is enabled or disabled.

---

### ✅ Ticket 2: Show Mouse Coordinates on Map

**Problem**

* Users could not view the current cursor coordinates.

**Solution**

* Added a mouse move event listener.
* Displayed live Latitude and Longitude values in the dashboard header.

**Result**

* Coordinates update in real time as the user moves the mouse over the map.

---

### ✅ Ticket 3: Dynamic Marker Count Dashboard

**Problem**

* Dashboard node count remained static.

**Solution**

* Implemented dynamic counting of visible markers.
* Updated the dashboard whenever layers are toggled.

**Result**

* Active node count now reflects the currently visible markers.

---

### ✅ Ticket 4: Sidebar Collapse / Hamburger Menu

**Problem**

* Sidebar occupied unnecessary screen space.

**Solution**

* Added a hamburger menu button.
* Implemented sidebar show/hide functionality.

**Result**

* Users can easily collapse or expand the sidebar.

---

### ✅ Ticket 5: Persist Sidebar State

**Problem**

* Sidebar state reset after refreshing the page.

**Solution**

* Stored sidebar state using Local Storage.
* Restored the saved state automatically on page load.

**Result**

* Sidebar remembers whether it was open or closed, even after a browser refresh.

---

## 🚀 Features

* Interactive Leaflet Map
* Marker Clustering
* Layer Toggle Controls
* Live Mouse Coordinates
* Dynamic Node Counter
* Sidebar Collapse & Expand
* Persistent Sidebar State
* Search Functionality
* Multiple Base Maps

---

## 📂 Project Structure

```
project/
│── index.html
│── style.css
│── script.js
│── README.md
```

---

## ▶️ How to Run

1. Download or clone the repository.
2. Open the project folder.
3. Open `index.html` in your browser.
4. Explore the GIS dashboard and test each implemented ticket.

---

## 📚 Learning Outcomes

Through these practice tickets, I gained hands-on experience with:

* Leaflet.js map development
* Marker clustering
* JavaScript DOM manipulation
* Event handling
* Local Storage
* Interactive dashboard development
* UI/UX improvements
* Debugging and feature implementation

---

## 👨‍💻 Author

**Tushar**

Practice project completed to improve frontend development and GIS dashboard skills.
