# MENA Child Malnutrition Analysis

This project investigates the drivers of child stunting across the Middle East & North Africa (MENA) region and proposes data-driven policy recommendations aimed at achieving food sovereignty and reducing poverty. By combining UNICEF/WHO nutrition surveys with World Bank socioeconomic indicators and FAO agricultural data, we build interactive visualizations, correlation analyses, predictive models, and interpretability reports to guide stakeholders and policymakers.

---

## Project Structure

1. **Data Collection & Cleaning**  
   - **Child Malnutrition (JME Country Estimates, May 2023):** Stunting prevalence & numbers affected for each MENA country.  
   - **Socioeconomic Indicators (World Bank):** GDP per capita, Consumer Price Index (CPI/inflation), fertility rate, population growth, and poverty rates.  
   - **Agricultural & Food Security (FAOSTAT):** Crop yields, livestock production, and food insecurity metrics (undernourishment, dietary energy supply adequacy).  

2. **Exploratory Data Analysis (EDA)**  
   - Time-series plots of stunting trends.  
   - Interactive dashboards comparing Palestine vs. peers.  
   - Distribution plots and pairwise relationships among key features.

3. **Correlation & Feature Analysis**  
   - Pearson correlation heatmaps for socioeconomic and agricultural factors.  
   - Identification of strongest drivers (e.g., CPI, poverty, fertility, undernourishment).

4. **Predictive Modeling**  
   - **Random Forest Regressor** to predict stunting proportion (R² ≈ 0.78, MAE ≈ 2.3%).  
   - **SHAP** interpretability for global and local feature importance.

5. **Policy Recommendations**  
   - Inflation protection (CPI-indexed transfers, food subsidies).  
   - Local food-system strengthening (smallholder support, cold chains).  
   - Integrated poverty‐nutrition programs (conditional cash, women’s empowerment).  
   - Expanded family planning & maternal health integration.  
   - Real-time dashboards for adaptive policy.

---

## Dependencies

- Python 3.8+  
- pandas  
- numpy  
- matplotlib  
- seaborn  
- plotly  
- scikit-learn  
- prophet  
- shap  

Install with:

```bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn prophet shap
```

# Author  
**Ahmed AlSakka**  
Independent Palestinian Data Analyst  
- **Email**: [ahmedsakka101@gmail.com](mailto:ahmedsakka101@gmail.com)  
- **Portfolio**: [ahmedsakka.github.io/AhmedSakkaPortfolio.github.io](https://ahmedsakka.github.io/AhmedSakkaPortfolio.github.io)  

---

# References  
- **UNICEF/WHO Joint Malnutrition Estimates**:  
  [https://data.unicef.org/topic/nutrition/malnutrition/](https://data.unicef.org/topic/nutrition/malnutrition/)  
- **World Bank Open Data**:  
  [https://data.worldbank.org/](https://data.worldbank.org/)  
- **FAOSTAT**:  
  [http://www.fao.org/faostat/en/](http://www.fao.org/faostat/en/)  
- **SHAP Methodology**:  
  Lundberg, S. M., & Lee, S.-I. (2017). *A Unified Approach to Interpreting Model Predictions*.  