# college-roi-dashboard

A data-driven analysis of over 6,000 U.S. colleges using the Department of Education’s College Scorecard dataset. This project explores the relationship between tuition cost, student debt, graduation rates, and post-graduate earnings to help evaluate the return on investment (ROI) of higher education.

---

## Live Demo
Check out the live U.S. College ROI Dashboard here: https://haniyas-college-roi-dashboard.streamlit.app

---

## Dataset

- **Source**: U.S. Department of Education  
- **File Used**: `Most-Recent-Cohorts-All-Data-Elements.csv`  
- **Key Columns**:  
  - `COSTT4_A` – Tuition cost  
  - `DEBT_MDN` – Median student debt  
  - `MD_EARN_WNE_P10` – Median earnings after 10 years  
  - `GRAD_RATE` – Graduation rate  
  - `STABBR` – State  

---

## Tools Used

- Python  
- Jupyter Notebook / Google Colab  
- Libraries: `pandas`, `seaborn`, `matplotlib`  

---

## Key Insights

- Graduation rates across colleges vary widely, often clustering between 40%–60%.  
- Some high-cost colleges yield surprisingly low earnings — revealing weak ROI.  
- States like MA, DC, and CA showed the highest median graduate earnings.  
- Cost is moderately correlated with earnings, but more strongly with debt.

---

## Visualizations

- Correlation Heatmap: Cost vs Debt vs Earnings  
- Scatter Plot: Cost vs Earnings (Top 5 States)  
- Bar Chart: Top 10 States by Avg Median Earnings  
- Histogram: Graduation Rate Distribution  

---

## Files

- `college_scorecard.csv` — Raw dataset  
- `U_S_College_ROI_Dashboard.ipynb` — Full notebook  
- `README.md` — This file  

---

## Future Plans

- Add dropdown filters by state, earnings, and cost  
- Build a public dashboard using Streamlit  
