# Superstore_dataset.ipynbSuperstore Sales Dashboard 📊
An interactive sales analytics dashboard built using Gradio, Plotly, and Pandas to visualize and analyze Superstore sales data.
This project provides real-time filtering, KPI tracking, and insightful visualizations for business analysis.
🚀 Features
Interactive dashboard built with Gradio
Dynamic filtering by:
Region
Category
Key Performance Indicators (KPIs):
Total Sales
Total Profit
Average Order Value
Profit Margin
Interactive visualizations using Plotly
Automatic dataset download using KaggleHub
Public shareable dashboard link using share=True
📁 Dataset
Dataset used: Superstore Dataset
Source: kaggle.com⁠�
The dataset is automatically downloaded using kagglehub.
🛠️ Technologies Used
Python
Gradio
Pandas
Plotly Express
KaggleHub
📦 Installation
Install the required libraries before running the project.
Bash
pip install gradio pandas plotly kagglehub
▶️ How to Run
Save the Python script as:
Bash
app.py
Then run:
Bash
python app.py
After execution:
A local dashboard link will appear
A public Gradio share link will also be generated
📊 Dashboard Components
1. Filters
Region Selector
Category Selector
2. KPIs
Total Sales
Total Profit
Average Order Value
Profit Margin
3. Charts
Monthly Sales Trend (Line Chart)
Category-wise Sales (Bar Chart)
Profit by Sub-Category (Bar Chart)
📈 Visualizations Included
Monthly Sales Trend
Tracks sales performance over time.
Category-wise Sales
Compares sales across different product categories.
Profit by Sub-Category
Shows which sub-categories generate the highest profit.
📂 Project Structure
Plain text
superstore-dashboard/
│
├── app.py
├── README.md
└── requirements.txt
🧠 Workflow
Download dataset from Kaggle
Load and clean the data
Convert dates into monthly periods
Filter data based on user selection
Calculate KPIs
Generate interactive charts
Display dashboard using Gradio
🔥 Example Use Cases
Business sales analysis
Retail performance monitoring
Data visualization projects
Dashboard development practice
Portfolio project for data analysts
📸 Dashboard Preview
You can add screenshots here after running the project.
Example:
Markdown
![Dashboard Screenshot](screenshot.png)
✅ Future Improvements
Add date range filtering
Add map visualizations
Export reports to PDF/Excel
Add forecasting models
Deploy on Hugging Face Spaces or Render
👨‍💻 Author
Developed using Python and Gradio for interactive business analytics.
📜 License
This project is open-source and free to use for educational purposes.
