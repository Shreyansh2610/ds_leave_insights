# 📊 Leave Insights Data Science Project

This project provides comprehensive data analysis and visualization of employee leave data using Python. It generates insightful charts and a well-organized HTML dashboard to help HR teams and managers better understand leave patterns, types, and departmental usage.

---

## 🧰 Tech Stack

- Python
- Pandas
- Seaborn / Matplotlib
- HTML + Bootstrap 5
- Google Colab / Jupyter Notebook

---

## 📁 Input

- `leave_data.csv`: A CSV file containing leave records with columns like:
  - `leave_start_date`, `leave_end_date`, `leave_days`
  - `leave_type`, `applicant_department`, `applicant_subdepartment`

---

## 📈 Features & Visualizations

The script analyzes and visualizes the following:

1. **Distribution of Leave Types**
2. **Leave Duration Categories**
3. **Monthly Leave Frequency**
4. **Weekday Leave Trend**
5. **Monthly Leave Type Trend** (Heatmap)
6. **Top Leave Type by Month** (CSV Export)
7. **Leave Count by Department**
8. **Leave Count by Subdepartment**
9. **Department-wise Leave Type Heatmap**
10. **Subdepartment-wise Leave Type Heatmap**
11. **Year-wise Leave Type Heatmap** ✅ *(New)*

All charts are saved in the `charts/` directory and embedded into a styled HTML report.

---

## 📄 Output

- 📊 Charts directory: `charts/`
- 📄 HTML Report: `leave_insights_report.html`
- 📁 CSV: `charts/top_leave_type_by_month.csv`

---

## ▶️ How to Run

1. Open in Google Colab or Jupyter Notebook.
2. Upload `leave_data.csv` when prompted.
3. Run all cells to generate the full analysis and HTML dashboard.

---

## 📸 Preview (HTML Report Screenshot)

> Add a screenshot of the generated HTML report here for a visual overview.

---

## 🛠️ Customization

You can extend this project with:
- Department-wise trends over time
- Individual employee leave stats
- Interactive dashboards using Plotly or Streamlit
- Exporting report to PDF

---

## 📃 License

This project is free to use for personal or internal organizational insights. Attribution appreciated.

---

## 👨‍💻 Author

Built by a passionate Data + Python + Visualization enthusiast.  
