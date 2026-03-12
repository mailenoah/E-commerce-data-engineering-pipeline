# 🚀 E-commerce Data Engineering Pipeline

![Python](https://img.shields.io/badge/Python-3.12-blue)
![AWS](https://img.shields.io/badge/AWS-S3-orange)
![Prefect](https://img.shields.io/badge/Orchestration-Prefect-purple)
![Docker](https://img.shields.io/badge/Container-Docker-blue)
![Status](https://img.shields.io/badge/Project-Production%20Ready-green)

An **end-to-end Data Engineering pipeline** that processes synthetic e-commerce data using modern cloud tools and industry best practices.

This project demonstrates how to build a **production-style ETL pipeline** from raw CSV data to business analytics using **cloud storage, orchestration, and containerization**.

---

# 📌 Project Overview

This pipeline simulates how modern companies process **e-commerce data** to generate business insights.

### Key Features

✅ Automated ETL pipeline  
✅ Cloud data lake using AWS S3  
✅ Workflow orchestration with Prefect  
✅ Containerized deployment using Docker  
✅ Data transformation with Pandas  
✅ Business metrics generation  

---

# 🏗️ Data Pipeline Architecture

```
        Raw Data
        (CSV Files)
             │
             ▼
     Upload to AWS S3
        (Raw Zone)
             │
             ▼
      Data Processing
      (Python + Pandas)
             │
             ▼
     Business Metrics
      (Aggregations)
             │
             ▼
      Processed Data
      (S3 Data Lake)
             │
             ▼
     Workflow Orchestration
          Prefect
             │
             ▼
        Containerized
         with Docker
```

---

# 📸 Project Screenshots

## Prefect Pipeline Execution

<img width="940" height="375" alt="image" src="https://github.com/user-attachments/assets/ae45df5e-85c1-4950-bfbf-087cfd055cf0" />

<img width="940" height="413" alt="image" src="https://github.com/user-attachments/assets/524104dc-2e10-4d71-bdd5-0d2ea1b27158" />

<img width="940" height="356" alt="image" src="https://github.com/user-attachments/assets/7154f575-b6f1-41d8-8330-2dff35f2f28f" />

<img width="940" height="365" alt="image" src="https://github.com/user-attachments/assets/c1d88b3a-e5aa-4277-8b02-bf381067cbd3" />

<img width="940" height="408" alt="image" src="https://github.com/user-attachments/assets/a99d6ad1-9111-447f-9c70-d79ef966bbb9" />






## AWS S3 Data Lake

<img width="1762" height="695" alt="image" src="https://github.com/user-attachments/assets/33659f11-f0d5-4f57-b612-c8fe94101923" />

<img width="1733" height="741" alt="image" src="https://github.com/user-attachments/assets/5378bd17-c077-48da-b5bc-613a9a4a90f8" />



## TERMINAL

<img width="940" height="468" alt="image" src="https://github.com/user-attachments/assets/61d8e6c8-75f1-485a-bf13-1135c773d5b8" />


---

# 🛠️ Technology Stack

| Layer | Technology |
|------|-------------|
| Programming | Python |
| Cloud Storage | AWS S3 |
| Data Processing | Pandas / Polars |
| Workflow Orchestration | Prefect |
| Containerization | Docker |
| Data Validation | Great Expectations |
| Infrastructure | Docker Compose |

---

# 📂 Project Structure

```
E-commerce-Data-Engineering-Pipeline
│
├── data/
│   ├── raw/
│   └── processed/
│
├── data-pipeline/
│   ├── src/
│   │   ├── data_ingestion/
│   │   ├── data_processing/
│   │   └── orchestration/
│   │
│   ├── config/
│   ├── infrastructure/
│   └── tests/
│
├── screenshots/
├── requirements.txt
├── docker-compose.yml
└── README.md
```

---

# ⚙️ Pipeline Workflow

The pipeline performs the following steps:

### 1️⃣ Data Ingestion

Upload raw CSV files into **AWS S3 data lake**

```bash
python src/data_ingestion/s3_uploader.py
```

---

### 2️⃣ Data Transformation

Clean and transform datasets

```bash
python src/data_processing/etl_processor.py
```

Transformations include:

- Removing duplicates
- Handling missing values
- Creating analytics datasets

---

### 3️⃣ Business Metrics Generation

Metrics created:

- Customer purchase metrics
- Product performance metrics
- Monthly sales trends

---

### 4️⃣ Workflow Orchestration

Pipeline automation using **Prefect flows**

```bash
python src/orchestration/prefect_flows.py
```

Prefect manages:

- Task dependencies
- Retries
- Monitoring
- Logging

---

### 5️⃣ Containerized Deployment

Run pipeline in containers:

```bash
docker-compose up --build
```

This allows the pipeline to run **anywhere consistently**.

---

# 📊 Sample Data

| Dataset | Records | Description |
|------|------|------|
| customers.csv | 1,000+ | Customer profiles |
| products.csv | 500+ | Product catalog |
| orders.csv | 2,000+ | Order transactions |
| order_items.csv | 6,000+ | Items per order |
| reviews.csv | 1,500+ | Customer reviews |

---

# 📈 Example Business Insights

The pipeline generates analytics such as:

• Monthly revenue trends  
• Top performing products  
• Customer lifetime value  
• Order frequency metrics  

---

# 🚀 How to Run the Project

### Clone the repository

```bash
git clone https://github.com/yourusername/ecommerce-data-pipeline.git
```

### Setup environment

```bash
python -m venv venv
venv\Scripts\activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Configure environment variables

Create `.env`

```env
AWS_ACCESS_KEY_ID=your_key
AWS_SECRET_ACCESS_KEY=your_secret
AWS_DEFAULT_REGION=us-east-1
```

---

# 🧠 Skills Demonstrated

This project demonstrates practical experience with:

- Data Engineering pipelines
- Cloud data lakes
- ETL architecture
- Workflow orchestration
- Containerization
- Production data workflows

---

# 🎯 Future Improvements

Planned upgrades:

• Data warehouse integration (Snowflake / Redshift)  
• Real-time streaming with Kafka  
• Dashboard with Power BI / Tableau  
• Airflow orchestration version  

---

# 👨‍💻 Author

**Disego Noah Maile**

📧 disegonoah@gmail.com

---

⭐ If you found this project useful, consider **starring the repository**.



