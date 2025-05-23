# **Exercise Data Analysis and Visualization**

This project analyzes a rich dataset provided by a Professor who began tracking his exercise activities during the summer of 2019. The dataset includes detailed metrics collected from devices such as heart rate monitors, watches, and bicycles, and was shared via the social platform [Strava](https://www.strava.com/). The goal of this project is to uncover meaningful insights about his exercise patterns and provide a compelling narrative supported by visualizations.

---

## **Project Objectives**
- Explore and analyze exercise data to identify trends and patterns.
- Compare physiological metrics (e.g., heart rate, cadence, speed) across activities like running and cycling.
- Investigate messy data, extract patterns, and determine when Professor was cycling or running, along with his exercise habits.
- Create visualizations to effectively communicate findings using advanced techniques like subplots, annotations, shading, and interactive maps.
- Deliver a dashboard that provides actionable insights into Professors' fitness journey.

---

## **Visualizations**
The project includes the following visualizations:
1. **Correlation Heatmaps**: Show relationships between metrics for running and cycling.
2. **KDE Plots**: Compare distributions of metrics like cadence, distance, speed, and heart rate.
3. **Time Series Plots**: Highlight trends in daily averages of metrics over time.
4. **3D Scatter Plots**: Visualize routes with altitude and power metrics.
5. **Interactive Maps**: Display running and cycling routes using GPS coordinates.

---

## **Technologies Used**
- **Python**: Core programming language for data analysis and visualization.
- **Pandas**: For data manipulation and aggregation.
- **Matplotlib** and **Seaborn**: For creating detailed and interactive visualizations.
- **Folium**: For mapping running and cycling routes.
- **Jupyter Notebook**: For interactive data exploration and analysis.

---

## **Dataset**
The dataset includes:
- **Metrics**: Cadence, distance, speed, heart rate, altitude, and power.
- **Activities**: Running and cycling.
- **Time Period**: Summer 2019 onward.

---

## **Insights**
- **Running**: Metrics like cadence and speed are tightly correlated, reflecting consistent effort and movement patterns.
- **Cycling**: Shows more variability due to coasting and terrain changes, with longer distances and higher speeds.
- **Heart Rate**: Running exhibits higher variability, while cycling maintains a more consistent heart rate.
- **Trends**: Significant changes in cadence and distance were observed in September 2019, likely due to changes in training or device usage.

---

## **How to Use**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/health-sport-data-analysis.git
   cd health-sport-data-analysis
   ```

2. Install required dependencies:
   ```bash
   pip install pip install pandas numpy seaborn matplotlib folium
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook EDA_Strava_Data_Notebook.ipynb
   ```

4. Run the cells to generate visualizations and insights.

---

## **License**
This project is licensed under the MIT License. See the LICENSE file for details.
