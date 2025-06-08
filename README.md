# 🧪 Data Cleaning & Preparation: Real-World Problem Sets

This repository showcases two curated sets of real-world data cleaning and preparation problems, designed for hands-on practice with manufacturing and sales datasets.

## 📁 Datasets

- `fila_heat_filament_sales_april2025.csv` – For sales analytics and customer behavior tasks.
- `spool_manufacturing_batch_log.csv` – For QA, shift scheduling, and production efficiency analysis.

---

## 🧩 Problem Set 1: Filament Sales Data

These problems simulate tasks typically faced by data analysts in e-commerce or supply chain roles.

### ✅ Problem 1: Customer Location Normalization and Analysis
- Standardize address components.
- Remove duplicate customers.
- Clean malformed zip codes and emails.
- Identify top cities.

### ✅ Problem 2: Sales Tax Compliance and Anomaly Detection
- Verify and fix sales tax calculations.
- Analyze impact of corrections.
- Extract clean store location data.

### ✅ Problem 3: Product Performance and Material Trends
- Structure material information and supplier names.
- Calculate revenue and weight quartiles.
- Flag high-cost materials and one-hot encode combinations.

### ✅ Problem 4: Store-Level Stock Insights and Cleanup
- Parse product codes and validate barcodes.
- Generate store-level summaries.
- Clean building number formats.

### ✅ Problem 5: Customer Purchase Behavior and Retargeting
- Segment customers by spending.
- Detect repeat buyers and outliers.
- Sample 20% for A/B testing simulation.

---

## 🧩 Problem Set 2: Spool Manufacturing Batch Log

Focused on quality assurance and factory operations. Ideal for manufacturing data analytics.

### ✅ Problem 1: Shift-Based Operator Performance and Anomaly Flagging
- Normalize operator info.
- Validate emails and phone numbers.
- Analyze scrap and failure rates per shift.

### ✅ Problem 2: Production Line Efficiency and Outlier Detection
- Detect scrap outliers per line.
- Normalize scrap rate (z-score).
- Flag problematic lines.

### ✅ Problem 3: Material Flow Trace and Cleanup
- Clean material fields.
- Validate machine barcodes.
- Detect duplicate material-lot batches.

### ✅ Problem 4: Shift Scheduling Imbalance and Batching Gaps
- Visualize weekday production gaps.
- Detect operators overworked.
- Pivot shift vs. day production trends.

### ✅ Problem 5: A/B Testing QA Improvements
- Randomly assign batches to QA test groups.
- Compare performance.
- Visualize scrap distributions.
- Summarize findings.

---

## 🛠️ Tools Used

- Python (Pandas, NumPy)
- Data visualization (optional: Seaborn, Plotly, Matplotlib)
- Regex for data validation
- Z-score and quantile analysis
- Grouping, pivoting, and sampling

---

## 📈 Goal

These problems are designed to mimic real analyst work in logistics, retail, and manufacturing industries. They support structured thinking around:
- Data validation
- Cleanup pipelines
- Quality control analytics
- Operational insights

