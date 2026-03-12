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

You can adjust the path in the notebook if your folder structure is different.

⚡ Requirements

Python 3.9+ and the following libraries:

pip install numpy pandas matplotlib folium haversine

📝 Usage
Clone this repository:

git clone https://github.com/MarwaneZe/MotorsportAnalytics.git
cd ev-gps-analysis

Make sure the dataset or sample dataset exists in the expected folder.

Open the Jupyter Notebook:

jupyter notebook

Run the notebook cells to calculate trip distances, durations, and generate maps.

📊 Output

For each trip:

Distance (km)

Duration (minutes)

Trajectory plotted on a map (trip_<trip_id>_map.html)

You can open the .html files in a web browser to view the routes.

🔧 Project Structure
ev-gps-analysis/
├── VED-master/                  # (ignored) Full dataset folder
├── sample_data.csv              # Small dataset for testing
├── notebook.ipynb               # Main analysis notebook
├── README.md                    # Project description
└── .gitignore                   # To ignore the dataset
📌 Notes

The notebook is modular and can be extended for lap simulations, energy consumption analysis, or real-time visualization.

📄 License
free to use and modify.