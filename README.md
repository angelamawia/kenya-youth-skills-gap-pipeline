# kenya-youth-skills-gap-pipeline
A data engineering project to extract, transform, and analyze skill gaps from Kenyan job market data.

## 🚀 Goals
- Build an end-to-end data pipeline using Python, PySpark, and Airflow
- Automate ETL to analyze skill demands from job listings
- Generate insights to highlight skill gaps affecting Kenyan youth

## 📂 Project Structure
- `scripts/`: Contains extract, transform, load Python files
- `data/`: Raw and processed datasets
- `notebooks/`: Exploratory analysis using Pandas/PySpark
- `dags/`: Airflow DAGs for scheduling (optional)
  
## 🛠️ Tools Used
- Python
- Pandas / PySpark
- PostgreSQL (or Parquet)
- Apache Airflow
- Power BI or Streamlit (for visuals)

## 📈 Sample Insights (To Be Added)
- Top 10 most in-demand skills in Kenya
- Regions with highest youth unemployment
- Suggested training focus areas for job readiness

---

## ✅ How to Run
1. Clone this repo  
2. Set up virtual environment  
3. Run `extract.py`, then `transform.py`, then `load.py`

```bash
python scripts/extract.py
python scripts/transform.py
python scripts/load.py
