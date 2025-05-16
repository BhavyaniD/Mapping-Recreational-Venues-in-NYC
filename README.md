# 🗽 NYC Tourist Map Explorer – GIS Final Project

This project presents an **interactive map application** that helps tourists discover **must-visit places in New York City** based on user-specified location and radius. The places are categorized into **7 types of experiences**, making the application a dynamic tool for personal itinerary planning.

---

## 🎯 Project Objective

To build a **user-friendly, GIS-based mapping tool** that:

- Plots attractions within a user-specified radius from a selected NYC location.
- Categorizes attractions into:  
  `Historic`, `Nature`, `Food`, `Nightlife`, `Cultural`, `Shopping`, and `Events`.
- Integrates NYC subway lines and borough boundaries for better navigation.

---

## 📂 Data Sources

- **NYC Borough Shapefile**:  
  https://data.cityofnewyork.us/City-Government/Borough-Boundaries/tqmj-j8zm  
- **Tourist Places by Category**:  
  - NYC Official Tourism Site: [nyctourism.com](https://www.nyctourism.com)  
  - NYC Parks: [nycgovparks.org](https://www.nycgovparks.org)  
  - Yelp: [yelp.com](https://www.yelp.com)  
  - Shop Your NYC: [shopyourcity.cityofnewyork.us](https://shopyourcity.cityofnewyork.us)  
  - Malls in America: [mallsinamerica.com](https://www.mallsinamerica.com)  
  - Tripadvisor: [tripadvisor.com](https://www.tripadvisor.com)  
- **Geolocation Extraction**:  
  AI-based APIs used to gather coordinates for each tourist location.
- **NYC Subway Lines**:  
  https://data.cityofnewyork.us/Transportation/Subway-Lines/3qz8-muuu

---

## 🌐 Features

- 📍 **Custom Input Radius**: Input your desired distance in km or miles to find nearby attractions.
- 🗺️ **Category-Wise Filtering**: View specific types of attractions like food, nature, events, or historic landmarks.
- 🚇 **Subway Overlay**: Visualize subway lines and stations to assist with real-time travel planning.
- 🧭 **Interactive Map Rendering** using Folium and GeoPandas.

---

## 📌 How It Works

1. Input your starting location and desired search radius.
2. Select the type(s) of attractions you're interested in.
3. The tool fetches and displays:
   - Tourist spots from the chosen category
   - Borough boundaries
   - Subway lines
   - Short descriptions + coordinates for each place

---

## 🛠️ Technologies Used

- Python (Jupyter Notebook)
- GeoPandas
- Folium
- Shapely
- Pandas
- Geocoder APIs (for latitude/longitude extraction)

---

## 👩‍💻 Author

**Bhavyani Dodda**  
MS Data Science – Rutgers University  
📧 bhavyani.dodda123@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/bhavyani-dodda-414ab6195)
