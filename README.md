# 📊 Adidas Interactive Sales Dashboard

An interactive **data visualization dashboard** built using **Python, Streamlit, and Plotly** to analyze Adidas sales performance across **retailers, time periods, regions, and states**.  
The application enables business users to **explore trends, compare key metrics, and download insights** through a clean and intuitive user interface.

---

## 🚀 Features

### 🔹 Interactive KPI Visualizations
- **Total Sales by Retailer** – Bar chart comparison across retailers  
- **Monthly Sales Trends** – Time-series line chart for trend analysis  
- **Sales vs Units Sold by State** – Dual-axis bar + line chart  
- **Regional & City-Level Sales Distribution** – Interactive treemap visualization  

---

### 🔹 Dynamic User Interaction
- Expandable data views for detailed drill-down analysis  
- CSV download functionality for all aggregated datasets  
- Responsive layout optimized for wide-screen dashboards  

---

### 🔹 Data Processing & Aggregation
- Time-based grouping using **Month–Year** analysis  
- Multi-level aggregation by **Retailer, State, Region, and City**  
- Custom formatting for large sales values (displayed in **Lakhs**)  

---

### 🔹 Production-Ready UI
- Streamlit page layout configuration for professional dashboards  
- Custom **HTML/CSS styling** for enhanced UI presentation  
- Embedded brand logo and **last-updated timestamp**  

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Framework:** Streamlit  
- **Visualization:** Plotly (Express & Graph Objects)  
- **Data Processing:** Pandas  
- **UI / Styling:** HTML, CSS  
- **Data Source:** Excel (`Adidas.xlsx`)  

---

## 📂 Project Structure
├── app.py # Main Streamlit application
├── Adidas.xlsx # Sales dataset
├── img/
│ └── adidas-logo.jpg # Brand logo
├── README.md



▶️ How to Run the Project
pip install streamlit pandas plotly pillow openpyxl
streamlit run app.py
📈 Use Cases

*Sales performance monitoring
    Retailer and regional comparison
    Trend analysis for decision-making
    Business-ready data exports for reporting

🧠 Key Learnings
    Building interactive dashboards using Streamlit + Plotly
    Designing user-friendly analytical UIs
    Efficient data aggregation and visualization
    Translating raw sales data into actionable insights