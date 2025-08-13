# hospital-readmission-data-analysis
Predictive analysis of 30-day hospital readmissions in Australia using AIHW and ABS data.
Predictive Analysis of Hospital Readmissions for Chronic Disease Patients in Australia
📌 Project Overview
This project analyses Australian hospital admission data to identify patterns and predict 30-day readmissions for patients with chronic diseases such as diabetes, cardiovascular disease, and COPD. The goal is to assist healthcare providers and policymakers in reducing preventable readmissions through targeted interventions.

📊 Dataset
Australian Institute of Health and Welfare (AIHW) – Hospital admissions and chronic disease statistics.

Australian Bureau of Statistics (ABS) – Demographic & socio-economic indicators.

MyHospitals – Hospital performance metrics.

Note: Public datasets are anonymised and free from personal health identifiers.

🛠 Tools & Technologies
Python (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn)

Jupyter Notebook for analysis & visualisation

GeoPandas / Folium for geospatial mapping

Git & GitHub for version control

📈 Methodology
Data Collection & Integration – Merging hospital, demographic, and geographic data.

Data Cleaning & Preprocessing – Handling missing values, feature encoding, scaling.

Exploratory Data Analysis (EDA) – Identifying trends, outliers, and key risk factors.

Feature Engineering – Creating variables such as comorbidity index and socio-economic score.

Model Building – Logistic Regression, Random Forest, and XGBoost.

Evaluation – ROC-AUC, Precision, Recall, and Confusion Matrix.

Geospatial Mapping – Visualising readmission hotspots across Australia.

📌 Key Findings (Sample)
Readmission risk is highest among patients aged 65+ with multiple chronic conditions.

Regional and remote areas have higher readmission rates due to limited follow-up care.

Socio-economic disadvantage correlates strongly with higher readmission probability.

📍 Visualisations
Readmission rates by state/territory

Top 10 hospitals with highest readmission rates

Heatmaps showing correlation between factors

Geospatial maps of readmission hotspots

🚀 How to Run the Project
bash
Copy
Edit
# Clone the repository
git clone https://github.com/yourusername/hospital-readmission-australia.git

# Navigate into the folder
cd hospital-readmission-australia

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
📜 Future Improvements
Integrate real-time hospital data feeds

Apply deep learning models for prediction

Deploy as an interactive dashboard using Streamlit or Dash

📄 License
This project is licensed under the MIT License.
