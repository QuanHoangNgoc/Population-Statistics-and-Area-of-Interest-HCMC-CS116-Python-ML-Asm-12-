# 🌍 **HCMC Population Analysis & Area of Interest Clustering**

## 📌 What is it?
This project contains two labs focused on analyzing **Ho Chi Minh City's population data** and **user interest hotspots** using geospatial techniques.
- **Lab 1** explores HCMC's population distribution, identifying key demographic trends.
- **Lab 2** clusters user-clicked locations into hotspots and visualizes them using heatmaps.

## 🎯 Why did we do it?
Understanding population dynamics and high-interest areas helps city planners, researchers, and developers make **data-driven** decisions for:
- **Urban Planning**: Optimize infrastructure and services.
- **Public Services**: Improve accessibility and resource distribution.
- **Tech & Business Insights**: Identify popular locations for commerce and development.

## 👥 Who is this for?
- 🏙 **Urban Planners & Researchers** – Analyze population trends and identify high-density zones.
- 🛠 **Developers & Data Scientists** – Enhance skills in **GeoPandas**, clustering, and geospatial visualization.
- 📊 **Policy Makers & City Officials** – Use insights to plan public services and city expansion.

---

## 📊 Demo & Results
### **Lab 1: HCMC Population Analysis**
🔹 Identified **wards with the highest/lowest population density**.
🔹 Analyzed **population growth trends from 2009 to 2019**.
🔹 Compared **smallest & largest districts by land area and density**.

### **Lab 2: User Interest Clustering**
📌 Clustered **user-clicked locations** using **KMeans (k=20)**.
📍 Mapped **top 10 districts** by population growth (2017-2019).
🔥 Created **heatmaps** to visualize high-density user interest zones.

---

## ⚙️ How did we do it?
### **Lab 1: HCMC Population Statistics**
1. Loaded and processed **HCMC shapefiles** with `GeoPandas`.
2. Queried wards for:
   - **Highest & lowest populations**.
   - **Population growth metrics (2009-2019)**.
   - **Largest/smallest wards by land area and density**.
3. Displayed **population trends** using tables and visualizations.

### **Lab 2: User Interest Clustering**
1. Installed **OSMNet**, `folium`, and `GeoPandas`.
2. Loaded **district boundaries** and population data.
3. Extracted **top 10 growing districts** (2017-2019) and **filtered user clicks**.
4. Applied **KMeans clustering (k=20)** on user interaction data.
5. Mapped **clusters** and saved **heatmap visualizations**.

---

## 📚 What did we learn?
✔ **GeoData Handling**: Used `GeoPandas` for spatial joins, mapping, and shapefile processing.
✔ **Clustering & Analysis**: Implemented **KMeans** for hotspot detection and urban trend analysis.
✔ **Geospatial Visualization**: Created **heatmaps and population charts** for deeper insights.

---

## 🏆 Achievements
🏙 **Comprehensive Population Analysis** – Identified key trends in HCMC’s urban expansion.
📌 **User Interest Mapping** – Highlighted **hotspot locations** across high-growth districts.
🌍 **Interactive Geospatial Visualization** – Created **heatmaps** for effective data interpretation.

---

## 📝 Author - Donate & Support
👨‍💻 **Author:** Quan-Hoang-Ngoc  
💖 If you find this project helpful, consider **starring** ⭐ this repository on GitHub!
