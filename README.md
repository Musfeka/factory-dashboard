# 🏭 Factory Incident Management Dashboard

A data-driven and interactive Factory Incident Management Dashboard designed to track, filter, and visualize **10,000+ live incident records**.

## 🚀 Live Project Links
👉 [Click here to view the Live Dashboard](https://musfeka.github.io/factory-dashboard/)  
👉 [Click here to view the 10,000+ Incident Records Table](https://musfeka.github.io/factory-dashboard/incidents.html)

---

## ✨ Key Features

* **Interactive Charts:** Real-time analysis of overall incident trends, departmental breakdowns, and category-wise visualizations.
* **Large Dataset Handling (10,000+ Records):** Powered by the `SheetJS` library to efficiently parse and render massive CSV files entirely on the client side.
* **Smart Pagination:** Optimized performance by rendering exactly 50 rows per page to keep the browser fast and responsive.
* **Real-Time Live Search:** Instantly filter records by typing an Incident ID, Department, or Category in the search bar.
* **Fully Responsive UI:** Clean layout using the Inter font family, tailored to look perfect across mobile, tablet, and desktop screens.

---

## 🛠️ Technologies Used

* **Frontend:** HTML5, CSS3, JavaScript (ES6+)
* **Typography:** Inter Font (Google Fonts)
* **Libraries:** 
  * [SheetJS (XLSX)](https://sheetjs.com/) - For client-side CSV data parsing and processing.
  * [Chart.js](https://www.chartjs.org/) - For dynamic data visualization and dashboard metrics.
* **Hosting:** GitHub Pages

---

## 📁 Folder Structure

```text
factory-dashboard/
│
├── index.html        # Main dashboard home page
├── incidents.html    # Paginated and searchable incident database table
├── .gitignore        # Ignores unnecessary system and environment cache files
└── data/
    └── factory_incidents_cleaned.csv  # Cleaned dataset containing 10,000+ records
