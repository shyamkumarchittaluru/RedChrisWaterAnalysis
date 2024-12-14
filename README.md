# RedChrisWaterAnalysis
Focused on water quality analysis related to the Red Chris Mine and A project analyzing water quality and mining impact using Python, Power BI, and ArcGIS tools

# **Red Chris Mine Environmental Impact & Water Potability Analysis**

## **Overview**

This repository showcases an environmental analysis project focused on the **Red Chris Mine** and its surrounding impacts, particularly concerning **water potability** and mining's environmental influence. The analysis combines geospatial mapping, machine learning models, and dashboard visualizations to present actionable insights.

---

## **Objectives**

1. **Assess Water Potability**: Analyze datasets to determine the potability of water sources near the mine.
2. **Evaluate Environmental Impact**: Use ArcGIS and weather data to visualize the impact of mining activities on the surrounding environment.
3. **Deliver Insights**: Create interactive dashboards in Power BI to support decision-making for stakeholders.

---

## **Tools & Technologies**

### **1. Data Sources**
- **Kaggle**: Water Potability dataset connected through the Kaggle API.
- **Visual Crossing API**: Weather data for the Red Chris Mine location.
- **ArcGIS**: Spatial data visualizations using geospatial mapping.

### **2. Tools**
- **Python**: For data cleaning, preprocessing, and machine learning models.
- **Power BI**: For creating interactive dashboards and presenting results.
- **ArcGIS Notebook**: For geospatial analysis and mapping.
- **GitHub**: For project version control and collaboration.

### **3. Libraries & APIs**
- Python Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`, `plotly`, and `imblearn`.
- Kaggle API for fetching datasets.
- Visual Crossing API for weather data retrieval.

---

## **Data Flow**

1. **Data Collection**:
   - Fetched **Water Potability Dataset** via the Kaggle API.
   - Retrieved weather data using the **Visual Crossing API** for mining locations.

2. **Data Processing**:
   - Missing values handled using median imputation.
   - Balanced dataset using SMOTE (Synthetic Minority Oversampling Technique).
   - Feature scaling applied using `RobustScaler`.

3. **Analysis**:
   - Applied machine learning models: Logistic Regression, Random Forest, and XGBoost.
   - Created visualizations: Heatmaps, scatter plots, and pie charts to explore correlations.

4. **Results Presentation**:
   - Power BI dashboards integrating all processed data and insights.
   - ArcGIS mapping to visualize geospatial information around **Red Chris Mine**.

---

## **Files in the Repository**

### **1. `WaterPotabilityAnalysis.ipynb`**
- Python notebook containing:
  - Data preprocessing steps.
  - Machine learning models (Logistic Regression, Random Forest, XGBoost).
  - Visualizations such as ROC Curve and Confusion Matrix.

### **2. `RedChrisMine_ArcGIS_Notebook.ipynb`**
- Notebook with geospatial analysis using ArcGIS.
- Mapping of mining impact zones and surrounding environment.

### **3. `PowerBI_Dashboard.pbix`**
- An interactive Power BI file containing:
  - Slicers for Potability and Date.
  - Visualizations: Bar charts, pie charts, and geospatial maps.

### **4. `RedChris_Presentation.pptx`**
- Final presentation slides summarizing the project findings.

### **5. `README.md`**
- Comprehensive documentation of the project.

---

## **Business Question**

**How does mining activity at Red Chris Mine affect water potability and environmental conditions in the surrounding areas?**

We explored this question using:
1. **Water Potability Analysis**: Identifying factors affecting the quality of water.
2. **Environmental Impact Visualization**: Mapping weather and mining data geospatially.

---

## **Key Results**

1. **Water Potability**:
   - **Potability Prediction Models**: 
     - Logistic Regression achieved 68% accuracy.
     - XGBoost and Random Forest models also showed strong performance.
   - Key Indicators:
     - `Solids` showed the strongest correlation with water potability.
     - `pH` and `Chloramines` were weakly correlated.

2. **Environmental Impact**:
   - **ArcGIS Map**: Highlighted zones near Red Chris Mine prone to potential environmental stress.
   - **Weather Data Analysis**: Explored temperature, precipitation, and humidity trends to understand environmental risks.

3. **Power BI Dashboard**:
   - Interactive visuals provided stakeholders with actionable insights into water quality trends, precipitation patterns, and spatial impacts.

---

## **How We Solved It**

- **Data-Driven Approach**: 
   - Combined weather and water quality data to build predictive and analytical models.
   - Used machine learning to classify potable vs. non-potable water sources.

- **Visualization Tools**:
   - Power BI enabled easy navigation of insights through interactive slicers, maps, and charts.
   - ArcGIS provided spatial context to identify high-risk areas.

---

## **Crucial Insights**

1. **Potability Analysis**:
   - Only **39% of water sources** were classified as potable.
   - High `Solids` content was a critical factor in determining water quality.

2. **Environmental Impact**:
   - Cloud cover and precipitation trends could affect water sources.
   - Mining activity zones indicated potential risks to nearby ecosystems.

3. **Stakeholder Benefits**:
   - Dashboards offer real-time analysis for decision-makers.
   - Predictive models can guide future interventions to improve water safety.

---

## **Conclusion**

- The integration of geospatial analysis, machine learning, and visualization provides a comprehensive view of the Red Chris Mine’s environmental impact.
- This project offers a scalable framework for analyzing similar mining sites globally.

---

## **Next Steps**

1. Expand the dataset by integrating real-time sensors and satellite imagery.
2. Enhance model performance by incorporating additional environmental variables.
3. Build a predictive system for early warnings of environmental degradation.

---

## **References**
1. Kaggle Water Potability Dataset.
2. Visual Crossing Weather API.
3. ArcGIS Online Documentation.
4. Scikit-learn Machine Learning Documentation.

--- 
