# 🚗⚡ EV GPS Trajectory Analysis
 
A Python Jupyter Notebook that analyzes EV (Electric Vehicle) GPS data to calculate trip metrics and visualize trajectories on real-world maps.
 
## 📋 Overview
 
This project serves as a base framework for GPS-based EV data analysis. It enables you to:
 
- Calculate total distance traveled for each trip
- Calculate trip duration
- Plot the trajectory of each trip on a real-world map using Folium
 
---
 
## 📂 Dataset
 
The notebook uses the **VED (Vehicle Energy Dataset)**:
 
> `VED_171101_week.csv` from the [VED Dynamic Data Part 1](https://github.com/gsoh/VED.git) collection.
 
> ⚠️ **Important:** The dataset is not included in this repository due to its size. You need to download it separately.
 
### Dataset Location
 
Place the dataset at the following path:
 
```
./VED-master/Data/VED_DynamicData_Part1/VED_171101_week.csv
```
 
You can adjust the path in the notebook if your folder structure is different.
 
---
 
## ⚡ Requirements
 
- Python 3.9+
 
Install the required libraries with:
 
```bash
pip install numpy pandas matplotlib folium haversine
```
 
---
 
## 📝 Usage
 
**1. Clone this repository:**
 
```bash
git clone https://github.com/MarwaneZe/MotorsportAnalytics.git
cd ev-gps-analysis
```
 
**2.** Make sure the dataset (or a sample dataset) exists in the expected folder.
 
**3. Open the Jupyter Notebook:**
 
```bash
jupyter notebook
```
 
**4.** Run the notebook cells to calculate trip distances, durations, and generate maps.
 
---
 
## 📊 Output
 
For each trip, the notebook produces:
 
| Output | Description |
|---|---|
| Distance | Total trip distance in kilometers |
| Duration | Total trip duration in minutes |
| Map | Interactive trajectory map saved as `trip_<trip_id>_map.html` |
 
Open any `.html` file in your web browser to explore the routes interactively.
 
---
 
## 📌 Notes
 
The notebook is modular and can be extended for:
 
- Lap simulations
- Energy consumption analysis
- Real-time visualization
 
---
 
## 📄 License
 
Free to use and modify.
 
