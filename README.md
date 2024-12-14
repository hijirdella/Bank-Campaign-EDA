Berikut adalah template README untuk repository GitHub Anda:

---

# **Bank Campaign EDA**

📊 **Exploratory Data Analysis (EDA) and Statistical Analysis on Bank Marketing Campaign Data**

---

## **Overview**

This project analyzes the impact of marketing campaigns on customers' decisions to open a term deposit account. Using a dataset containing information about customers, financial indicators, and campaign performance, the analysis focuses on uncovering patterns and providing actionable insights for optimizing marketing strategies.

---

## **Objectives**

1. Perform **Exploratory Data Analysis (EDA)** using pivot tables and visualizations.
2. Conduct statistical analyses, including:
   - **Correlation Analysis**
   - **Chi-Square Test**
   - **Linear Regression**
3. Provide key insights and recommendations for improving campaign effectiveness.

---

## **Dataset**

- **Source**: [Kaggle - Bank Marketing Dataset](https://www.kaggle.com/datasets/krantiswalke/bankfullcsv)  
- **Size**: 45,211 rows and 17 columns  
- **Key Variables**:  
  - `campaign`: Number of contacts performed during this campaign.  
  - `y`: Target variable indicating if the term deposit was subscribed (`yes` or `no`).  
  - `balance`, `duration`, `pdays`, etc.  

---

## **Key Findings**

### **1. Statistical Insights**  
- **Chi-Square Test**:  
  - **Significant Relationship**: Number of campaigns is statistically significant in influencing term deposit subscription.  
  - **Direction**: Negative relationship - more campaigns reduce the likelihood of success.  

- **Linear Regression**:  
  - **Coefficient**: -0.0076 → Each additional campaign reduces the likelihood of success by 0.76%.  
  - **R-squared**: 0.005 → Campaigns explain only 0.5% of the variation, indicating other factors play a role.  

### **2. Recommendations**  
- **Optimize Campaigns**: Focus on quality, not quantity, of interactions.  
- **Avoid Over-Contacting**: Limit contacts to avoid diminishing returns.  
- **Segment Clients**: Target responsive clients using features like `balance` and `education`.  

---

## **Methods Used**

1. **EDA**  
   - Visualizations (histograms, boxplots, heatmaps).  
   - Pivot tables for detailed insights.  

2. **Statistical Analysis**  
   - Correlation (Pearson, Spearman).  
   - Chi-Square test for independence.  
   - Linear regression to analyze trends and impacts.  

---

## **Project Structure**

- `data/`: Dataset and any data preprocessing files.  
- `notebooks/`: Jupyter notebooks for EDA and statistical analysis.  
- `scripts/`: Python scripts for data processing and visualization.  
- `README.md`: Project documentation.  

---

## **How to Run the Project**

1. Clone the repository:
   ```bash
   git clone https://github.com/hijirdella/Bank-Campaign-EDA.git
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook or Python scripts:
   ```bash
   jupyter notebook notebooks/EDA_and_Analysis.ipynb
   ```

---

## **Visualizations**

Sample visualizations include:  
- Campaign frequency distribution.  
- Balance vs. term deposit subscription.  
- Correlation heatmap of numerical features.  

---

## **Acknowledgments**

Special thanks to **Dibimbing.id** and mentor **Rizki Teguh Kurniawan** for providing valuable insights and guidance throughout this project.  

---


