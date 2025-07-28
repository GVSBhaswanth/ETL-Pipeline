# 🛒 E-Commerce ETL Pipeline with MongoDB

This project builds a simple ETL pipeline to process customer behavior data from an e-commerce platform.

## 📌 Tools Used

- Python (pandas, pymongo)
- MongoDB (local)
- E-Commerce Behavior Dataset (Kaggle)

## ⚙️ Workflow

1. **Extract**: Load CSV data (`2019-Oct.csv`)
2. **Transform**: Clean and filter records
3. **Load**: Insert into MongoDB collection
4. **Query**: Automatically run aggregations like:
   - Most viewed product
   - Top brands
   - Event counts per user

## 📹 Demo Video
You can view the output/working of the project - (ETL Project Demo)

## 💡 How to Run

```bash
python etl.py
