# Banking Data Analysis and Dashboard Project

## 📊 Project Overview

This project focuses on client segmentation and banking behavior analysis using cloud-based tools. By categorizing clients based on gender, joining year, income band, and banking relationship type (Commercial, Institutional, Private, Retail), we analyzed deposit and loan behaviors. Visual dashboards were created to help identify trends and patterns in client activity, enabling better financial strategy and decision-making.

## 📁 Data Sources

- **Google Cloud Storage (GCS)**: Used to store raw data files (CSV format).
- **Google BigQuery**: Data was loaded from GCS into BigQuery for querying and transformation.

## 🛠️ Technologies Used

- **Google Colab**: For writing and executing Python scripts and running exploratory data analysis (EDA).
- **Python**: Used with libraries like `pandas`, `matplotlib`, and `seaborn` for EDA.
- **Google BigQuery**: For storing and querying structured banking data using SQL.
- **Power BI**: For creating interactive dashboards using BigQuery as the data source.

## 🔁 Data Processing Pipeline

1. **Data Ingestion**: Raw CSV files were uploaded to Google Cloud Storage and imported into BigQuery tables.
2. **Data Cleaning & Transformation**:
   - Handled null values and outliers.
   - Transformed date columns and income bands.
   - Performed joins between clients, accounts, loans, and advisors.
3. **Exploratory Data Analysis (EDA)**:
   - Conducted in Google Colab using SQL queries to BigQuery.
   - Summarized data using groupings (e.g., by branch, advisor, gender, income band).
   - Plotted key distributions and correlations.
4. **Data Export**:
   - Cleaned and transformed tables were connected to Power BI using the BigQuery connector.
5. **Dashboard Creation**:
   - Interactive visuals and slicers were created to explore:
     - Deposit behavior by occupation, branch, gender, and income.
     - Loan distribution by nationality, income level, and advisor performance.

## 📈 Dashboards

| Dashboard | Description | Link |
|----------|-------------|------|
| **Overview** | High-level KPIs like total clients, deposit, loan, account balances, and lending. Filters: Gender, Year | [View Dashboard](./Dashboards/overview.png) |
| **Deposit Analysis** | Insights into deposit breakdown by account type, branch, occupation, income, and nationality. | [View Dashboard](./Dashboards/Loan%20Analysis.png) |
| **Loan Analysis** | Loan insights by type, branch, nationality, income band, and advisor. | [View Dashboard](./Dashboards/Summary.png) |
| **Summary** | Aggregated view of loans, deposits, client count, advisor performance, income band summary. | [View Dashboard](./Dashboards/Summary.png) |

> 💡 Replace `#` above with actual dashboard links (e.g. Power BI Online, portfolio website, or GitHub Pages link).

## ▶️ How to Run This Project

1. **Setup GCP**:
   - Create a Google Cloud project and enable BigQuery and Cloud Storage APIs.
   - Upload raw CSVs to a GCS bucket.

2. **Google BigQuery**:
   - Load data into BigQuery using the web UI or Python scripts.
   - Write SQL queries to clean, join, and aggregate data.

3. **Google Colab**:
   - Open your Colab notebook and connect to BigQuery.
   - Run exploratory analysis and validate data using Pandas and Seaborn.

4. **Power BI**:
   - Use the Google BigQuery connector to import cleaned tables.
   - Create interactive dashboards using charts, filters, and slicers.

## ✅ Outcomes

- Deep insights into customer banking patterns by segment.
- Ability to monitor advisor performance and branch-level banking trends.
- Interactive visual reports to support strategic banking decisions.

---

## 🙋‍♂️ About Me

**👨‍💼 Dhruv Nirwan**  
Data Analyst | Power BI | SQL | Excel | Python | Snowflake | Cloud (AWS, Azure, GCP)  | Google Collab | Prompt Engineering

🔗 [LinkedIn](https://www.linkedin.com/in/dhruv-nirwan)  
📧 dhruvnirwan836@gmail.com  
📂 [GitHub: dhruvnirwan](https://github.com/dhruvnirwan)

