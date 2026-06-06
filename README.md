# 🏥 Healthcare Patient Journey Analysis

An end-to-end data analysis project utilizing Python and Pandas to extract critical operational and clinical insights from patient journey datasets. This project explores hospital department costs, admission types, wait times, patient satisfaction, and identifies high-risk patient segments.

## 📁 Project Structure
* `healthcare_patient_relationship.ipynb` - The complete Google Colab notebook containing step-by-step Python analysis and code documentation.
* `healthcare_patient_journey.csv` - The original raw dataset containing 3,000 patient records.
* `high_risk_patients_report.csv` - Generated report containing filtered actionable data of critical/high-risk patients.

## 🚀 Key Insights & Analytics Generated

### 1. Operational Analysis (Data Aggregation)
* **Cost by Department:** Grouped and evaluated the average treatment cost across various hospital units (Cardiology, Oncology, ER, Neurology, and Polyclinic) to optimize financial forecasting.
* **Wait Times vs. Admission Type:** Investigated the difference in average waiting times between `Emergency` admissions and `Scheduled` appointments to detect efficiency bottlenecks.
* **Readmission Rate:** Calculated the 30-day hospital readmission metric to evaluate treatment quality and success.

### 2. Data Visualization (Matplotlib & Seaborn)
* **Patient Satisfaction Distribution:** Formulated count plots to evaluate how patients rate their overall experience (Scale 1–5).
* **Sorted Department Costs:** Designed a structured bar chart mapping out departments from the highest average expenditure to the lowest for easy management review.

### 3. Risk Segmentation & Filtering
* **High-Risk Senior Patients:** Filtered senior patients (Age > 60) with pre-existing chronic conditions to track their average length of stay.
* **Critical Cases Tracking:** Extracted clinical data on cases involving both treatment complications and immediate 30-day readmissions.

## 🛠️ Technologies Used
* **Language:** Python 3
* **Environment:** Google Colab
* **Libraries:** Pandas, Matplotlib, Seaborn

## 📖 How to Run the Project
1. Clone or download this repository.
2. Upload the `healthcare_patient_relationship.ipynb` into your Google Colab environment.
3. Upload `healthcare_patient_journey.csv` to your session storage.
4. Execute the cells sequentially to reproduce the analytics and graphs!

---
*Developed as part of a Data Analysis portfolio using Pandas.*
