# Delta Lakehouse Project on Microsoft Fabric

This project demonstrates how to use **Delta Lake** capabilities on **Microsoft Fabric** for batch processing, streaming ingestion, versioning, and SQL analytics — using a simulated IoT data scenario.

> ✅ Ideal for learning Delta Lake concepts, time travel, structured streaming, and integration with Fabric Lakehouse.

---

## 📁 Files in this Repository

| File | Description |
|------|-------------|
| `Notebook 1.ipynb` | Full implementation in Microsoft Fabric notebooks: Delta creation, streaming, SQL queries, versioning. |
| `products.csv` | Sample product catalog used for Delta table creation and SQL analysis. |
| `screenshots/` | Folder containing images from each stage of the project (for reference in README). |

---

## 📌 Project Overview

### Technologies Used
- Microsoft Fabric
- Apache Spark (PySpark)
- Delta Lake
- Structured Streaming
- SQL (via `%%sql` magic command)

### Key Features Demonstrated
- Creating a Lakehouse and ingesting CSV data
- Saving DataFrames as **Delta Tables** (managed & external)
- Writing SQL queries and aggregations
- Using Delta table **versioning** and **time travel**
- Ingesting streaming data (IoT simulation) into Delta tables
- Analyzing data with temporary views and visualizations

---

## ⚙️ Setup Instructions

> You need a Microsoft Fabric trial or active license to run this project.

1. Go to [https://app.fabric.microsoft.com](https://app.fabric.microsoft.com)
2. Create a workspace with Fabric trial enabled
3. Create a new **Lakehouse** and upload `products.csv` into `Files/products`
4. Open a new **Notebook** and import `Notebook 1.ipynb`
5. Run the cells step by step to explore all Delta Lake capabilities

---

## 📸 Screenshots

### Lakehouse Files and Tables
![Lakehouse Structure](screenshots/lakehouse-structure.png)

### Delta Table Query Output
![Query Result](screenshots/query-results.png)

### Streaming Output in SQL
![Streaming Output](screenshots/streaming-output.png)

---

## 📚 Learning Points

- How Delta Lake enables ACID transactions and time travel on large-scale data
- How to manage streaming data pipelines using `writeStream`
- Differences between **managed** and **external** Delta tables
- Writing and analyzing SQL views directly in Fabric notebooks

---

## ✅ Status

**Project Complete** – All stages successfully tested in Microsoft Fabric.

