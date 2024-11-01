# 🌍 **HCMC Population Analysis & Area of Interest Clustering**

## 📊 What is it?
This repository includes two labs analyzing **Ho Chi Minh City's population** and **user interest hotspots** on maps. The first lab performs statistical analyses on HCMC’s population data, while the second lab clusters user-clicked locations by popularity and maps them visually.

## 🎯 Why do it?
Understanding population distributions and user interest zones enables city planners, researchers, and developers to make informed decisions on urban development, community services, and tailored user experiences.

## 👤 Who is this for?
- **Urban Planners & Researchers**: Gain insights into population trends and hotspot zones.
- **Developers & Data Scientists**: Enhance spatial analysis skills using GeoPandas, clustering, and visualization.

## 🔍 Key Results
- **Lab 1**: Population insights, including the ward with the highest density, the smallest and largest wards, and population growth metrics.
- **Lab 2**: Clustered user interest points with **heatmaps** highlighting high-density areas across districts.

## 🛠️ How did we build it?
### **Lab 1**: HCMC Population Statistics
1. Set up **GeoPandas** and cloned city data.
2. Queried wards for:
   - Highest and lowest populations
   - Population growth rates (2009-2019)
   - Largest/smallest area, and density metrics.
3. Displayed population results for rapid analysis and comparison.

### **Lab 2**: User Interest Clustering
1. Installed necessary libraries: `osmnet`, `folium`, `geopandas`.
2. Loaded district boundaries and population data.
3. Identified top 10 districts by population growth (2017-2019) and filtered user clicks.
4. **KMeans clustering**: Applied clustering to these high-growth districts (k=20).
5. Mapped and saved high-density clusters with **heatmap visualizations**.

## 📚 What did we learn?
- **GeoData Handling**: Worked with shapefiles, spatial joins, and population metrics in GeoPandas.
- **Clustering Techniques**: Leveraged KMeans for hotspot clustering and folium for effective visualization.
- **Insights**: Revealed patterns in user interest and urban population trends in HCMC.

## 🏆 Achievements
- **Detailed Population Analysis**: Comprehensive analysis of population changes and densities.
- **Intuitive Heatmap Visualizations**: Clear mapping of interest clusters across HCMC’s top districts.

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository and enhance the analyses or add new visualizations.
**Author**: Quan-Hoang-Ngoc  

## ⭐ Support
If you find this project helpful, please consider giving it a **star** ⭐ on GitHub!

