# 🌍 EcoCity Connect: Smart Services for a Sustainable City

 https://govindjindal.github.io/BeginnersLuck_Ecocity-Connect/

EcoCity Connect is a responsive web application designed to provide citizens with real-time, actionable insights into key public services, promoting a smarter and more sustainable urban life. It integrates data visualization, utility calculators, and feedback mechanisms within a modern, user-friendly interface.

## ✨ Features and Functionality

The application is divided into several smart modules, each providing essential information:

* **🚌 Real-time Public Transport Tracking:** Uses the Leaflet map library to simulate real-time movement of metro trains across major city routes (Red, Yellow, Blue, Green, Violet, Pink, Magenta, Airport Express lines).
    * *Simulation:* Custom JavaScript logic simulates metro movement between stations and displays real-time status (e.g., "Approaching [Station Name]").
* **💨 Air Quality Index (AQI) Monitoring:** Displays simulated AQI data for various city stations. Includes color-coded indicators (Moderate/Safe) and corresponding health advice.
* **🚨 Disaster & Emergency Alerts:** Dedicated section for displaying important safety alerts, such as flood watches (static simulation).
* **♻️ Waste Collection Schedule:** Provides a neighborhood lookup tool to find general and recycling collection days. Integrates with a Leaflet map to highlight the searched neighborhood (simulated polygons for major areas).
* **👣 Carbon Footprint Calculator:** Interactive two-tab utility (Commute & Domestic Energy) to help users estimate their monthly $\text{CO}_2\text{e}$ emissions. Uses realistic factors for India's energy grid and common transport modes.
* **🌳 Green and Safe Spaces:** Features a map showing green spaces (parks) and highlighting safe, well-lit pedestrian routes on a dark basemap, promoting safe outdoor activity.
* **📢 Citizen Feedback:** Simple form to report city issues (potholes, broken lights, etc.), encouraging civic engagement.

## 🛠️ Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Core structure and semantic layout. |
| **Tailwind CSS** | Utility-first framework for rapid and responsive styling. |
| **JavaScript (Vanilla)** | Handling all logic: map interactions, data simulations, UI toggles (tabs, mobile menu), and calculator functions. |
| **Leaflet.js** | Open-source library used for all interactive map visualizations (Transport, Waste, Safety). |
| **Inter Font** | Modern, clean typeface for improved readability. |

## 💻 Technical Highlights

* **Pure CSS Lightbox/Modal:** The application relies heavily on modern CSS and minimal JavaScript for a fast, component-based feel.
* **Data Simulation:** All dynamic data (AQI, Transport Movement, Waste Schedules) is simulated within the JavaScript block for demonstrating functionality without requiring external APIs.
* **Responsive Design:** Styled using Tailwind CSS to ensure optimal layout and functionality across mobile and desktop devices.
* **Map Initialization:** Uses specific tile layers and defined city bounds for a focused, hyper-local feel (e.g., Delhi/NCR coordinates and bounds).

## 🚀 Getting Started

To view and run the EcoCity Connect interface locally:

1.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL]
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd EcoCity-Connect
    ```
3.  **Open the file:**
    * Locate the **`Ecocity Connect .htm`** file.
    * Open it directly in any modern web browser (Google Chrome, Firefox, etc.).

## 📝 Carbon Footprint Calculation Factors

The calculator uses the following simplified factors (per passenger-km or per unit energy) for demonstration:

* **Car (Petrol):** 150 grams $\text{CO}_2\text{e}$ per km
* **Metro:** 21 grams $\text{CO}_2\text{e}$ per km (due to electric grid)
* **Electricity:** 0.8 kg $\text{CO}_2\text{e}$ per kWh (Approx. India Grid Factor)

---Team Members
1.	Piyush Sharma	piyush3183.beai25@chitkara.edu.in
2.	Govind Jindal	govind3091.beai25@chitkara.edu.in
3.	Bhavishya Grover	bhavishya3095.beai25@chitkara.edu.in
4. Krishna Bansal krishna3187.beai25@chitkara.edu.in 
5. Vansh Kaushal vansh3162.beai25@chitkara.edu.in
