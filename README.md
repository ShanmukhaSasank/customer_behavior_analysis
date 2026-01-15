🛒 Customer Shopping Behavior Analysis
📌 Overview
- This project analyzes customer shopping behavior using a complete data analytics workflow. The objective is to extract actionable business insights from raw transactional data by combining Python based analysis, SQL querying, and interactive dashboards.
- The project demonstrates end to end data analytics skills, covering data preprocessing, exploratory analysis, database querying, visualization, and stakeholder ready reporting.

📂 Dataset
- The dataset contains structured customer shopping behavior data, including demographic attributes and purchase related information.

Dataset highlights:
- CSV format
- Customer level and transaction level data
- Suitable for trend analysis and customer segmentation

📄 File used:
customer_shopping_behavior.csv

🧰 Tools and Technologies
🐍 **Python**: Data loading, cleaning, and EDA
Libraries: pandas, numpy, matplotlib, seaborn
🗄️ **PostgreSQL**: SQL based analysis and querying
📊 **Power BI**: Interactive dashboard development
📑 **Gamma**: Report and presentation creation
📓 **Jupyter Notebook**: Analysis documentation

🔄 Project Workflow
1️⃣ Data Loading
- Imported the dataset using pandas
- Reviewed structure, data types, and missing values

2️⃣ Exploratory Data Analysis (EDA)
- Analyzed data distributions and trends
- Visualized customer behavior patterns
- Identified key relationships affecting spending behavior

3️⃣ Data Cleaning
- Handled missing and inconsistent values
- Corrected data types
- Prepared a clean dataset for SQL and dashboard usage

4️⃣ SQL Analysis (PostgreSQL)
- Loaded cleaned data into PostgreSQL
- Wrote SQL queries to:
- Segment customers
- Identify high value customers
- Analyze purchase frequency and spending trends

📄 SQL file:
customer_behavior_dashboard.sql

5️⃣ Dashboard Development
- Designed an interactive Power BI dashboard
- bIncluded KPIs and trend visualizations
- Focused on clarity for non technical stakeholders

6️⃣ Reporting and Presentation
- Created a structured analytical report
- Designed a presentation using Gamma
- Summarized insights in a business friendly format

📄 Presentation file:
Customer-Shopping-Behavior-Analysis.pptx

📊 Dashboard
- The Power BI dashboard allows users to:
- Filter customers based on attributes
- Track spending and purchase trends
- Explore insights interactively
- The dashboard is designed to support quick decision making.

📈 Key Results and Insights
- Identified key purchasing trends across customer segments
- Highlighted factors influencing customer spending behavior
- Delivered insights useful for marketing and business strategy planning

▶️ How to Run the Project:-

🐍 Python Analysis
- Clone the repository
- Install required libraries:
- pip install pandas numpy matplotlib seaborn

Open and run:
customer_behavior_analysis.ipynb

🗄️ SQL Analysis
- Set up a PostgreSQL database
- Load the cleaned dataset

Execute queries from:
customer_behavior_dashboard.sql

📊 Power BI Dashboard
- Open Power BI Desktop
- Connect to PostgreSQL or the cleaned dataset
- Load the report and refresh data

📁 Project Structure
├── customer_behavior_analysis.ipynb

├── customer_behavior_dashboard.sql

├── customer_shopping_behavior.csv

├── Customer Shopping Behavior Analysis.pdf

├── Customer-Shopping-Behavior-Analysis.pptx

└── README.md
