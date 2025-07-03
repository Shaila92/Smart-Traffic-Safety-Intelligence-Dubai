# Smart-Traffic-Safety-Intelligence-Dubai

##  Project Overview
This project applies Machine Learning and Geospatial Analysis to tackle traffic congestion and road safety challenges in Dubai. Using historical accident data and traffic logs, we built a predictive model to estimate accident severity, identify danger zones, and provide actionable insights for city planners and emergency responders.

---

## Tech Stack

- **Languages & Tools**: Python, Jupyter Notebook
- **Libraries**: Pandas, NumPy, Seaborn, Scikit-learn, Matplotlib, Folium
- **ML Models**: Random Forest Classifier, KMeans Clustering
- **Geospatial Analysis**: Folium, HeatMap, Clustering
- **Data Sources**: Simulated Dubai accident and traffic datasets (`accidents_dubai.csv`, `traffic_data_dubai.csv`)

---

##  Key Features

-  Predicts accident severity using ML classification (hour, road type, weather, weekday)
-  Visualizes accident hotspots with heatmaps (Folium)
-  Detects high-risk zones using KMeans clustering
-  Explores accident trends by hour and day
-  Analyzes speed vs congestion levels using traffic logs
-  Provides feature importance to guide decision-making

---

##  Machine Learning Workflow

1. Data Loading and Preprocessing
2. Feature Engineering (Label Encoding for weather, road type)
3. EDA (Histograms, heatmaps, outlier handling)
4. Train-Test Split and ML Modeling (Random Forest)
5. Evaluation (Confusion Matrix, Accuracy, F1-Score)
6. High-Risk Area Detection using Clustering
7. Insights and Visual Reports

---

##  Results & Insights

-  ML Model Accuracy: ~80% in predicting accident severity
-  High-risk clusters located along Sheikh Zayed Road, Deira, Business Bay
-  Severe accidents correlate with foggy conditions on highways
-  Most frequent incidents during evening rush (4 PM–7 PM)

---

##  Real-World Use Cases

- RTA Dubai can use predictive severity scoring to deploy ambulances dynamically
- Smart routing engines can suggest alternative roads in high-risk zones
- Heatmaps can feed into traffic signal optimization systems
- Integration with CCTV feeds (YOLOv5) for real-time safety violation detection

---

## Repository Structure

```bash
Dubai-Traffic-Safety-ML/
│
├── accidents_dubai.csv
├── traffic_data_dubai.csv
├── Smart_Traffic_Safety_Dubai.ipynb
├── README.md
└── project_summary.docx / .pdf
