📊 Adidas Interactive Sales Dashboard

An interactive data visualization dashboard built using Python, Streamlit, and Plotly to analyze Adidas sales performance across retailers, time periods, regions, and states. The dashboard enables business users to explore trends, compare metrics, and download insights through an intuitive UI.

🚀 Features
*Interactive KPI Visualizations
    Total Sales by Retailer (Bar Chart)
    Monthly Sales Trends (Time-Series Line Chart)
    Sales vs Units Sold by State (Dual-Axis Bar + Line Chart)
    Regional & City-Level Sales Distribution (Treemap)

*Dynamic User Interaction
    Epandable data views for detailed analysis
    CSV download functionality for all aggregated datasets
    Responsive layout optimized for wide screens

*Data Processing & Aggregation
    Time-based grouping (Month-Year)
    Multi-level aggregation by Retailer, State, Region, and City
    Custom formatting for large sales values (Lakhs)

*Production-Ready UI
    Streamlit layout configuration
    Custom HTML/CSS styling
    Embedded brand logo and last-updated timestamp

🛠️ Tech Stack
Language: Python
Framework: Streamlit
Visualization: Plotly (Express & Graph Objects)
Data Processing: Pandas
UI/Styling: HTML, CSS
Data Source: Excel (Adidas.xlsx)

📂 Project Structure
├── app.py                  # Main Streamlit application
├── Adidas.xlsx             # Sales dataset
├── img/
│   └── adidas-logo.jpg     # Brand logo
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