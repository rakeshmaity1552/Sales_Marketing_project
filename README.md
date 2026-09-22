# 📊 Sales & Marketing Data Analytics Project

**IBM SkillsBuild Data Analytics with AI – Internship Project**  
**Author:** Rakesh Kumar Maity

---

## 📌 Project Overview

This project performs end-to-end **Exploratory Data Analysis (EDA)** on a real-world Sales & Marketing dataset. It covers data loading, cleaning, preprocessing, analysis, and visualization using Python — making it fully beginner-friendly and suitable for the IBM SkillsBuild Data Analytics with AI internship program.

---

## 📂 Project Structure

```
IBM_Data_Analyst_project/
│
├── dataset/
│   ├── Sales& Marketing.csv        ⬅ Place your CSV file here (not included)
│   └── README.txt                  Instructions for adding the dataset
│
├── RakeshKumarMaity_SalesDataAnalytics_Project.ipynb # Main Jupyter Notebook
├── RakeshKumarMaity_ProjectReport.docx               # Professional project report
├── requirements.txt                            # Python dependencies
└── README.md                                   # This file
```

> ⚠️ **The dataset is NOT included in this repository.**
> You must place the original `Sales& Marketing.csv` file inside the `dataset/` folder before running the notebook.

---

## 📁 Dataset Location & Description

| Column | Description |
|---|---|
| Order ID | Unique identifier for each order |
| Order Date | Date the order was placed |
| Ship Date | Date the order was shipped |
| Ship Mode | Shipping method used |
| Customer Name | Name of the customer |
| Segment | Customer segment (Consumer, Corporate, Home Office) |
| Country / City / State | Location information |
| Region | Geographic region (East, West, Central, South) |
| Category | Product category (Furniture, Office Supplies, Technology) |
| Sub-Category | More specific product grouping |
| Product Name | Name of the product |
| Sales | Total sales value ($) |
| Quantity | Number of units ordered |
| Discount | Discount applied (0–1 scale) |
| Profit | Profit earned ($) |

---

## 🛠️ Technologies Used

| Tool / Library | Purpose |
|---|---|
| **Python 3.x** | Core programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical visualizations |
| **Jupyter Notebook** | Interactive coding environment |

---

## ⚙️ Setup & Installation

### Step 1 – Add the Dataset ⚠️

The dataset is **not bundled** with this project. You must supply it yourself:

1. Obtain the file `Sales& Marketing.csv` (from your IBM SkillsBuild course materials, Kaggle, or your instructor).
2. Place it inside the `dataset/` folder so the final path is:
   ```
   dataset/Sales& Marketing.csv
   ```
3. Do **not** rename the file — the notebook loads it by this exact name and path.

### Step 2 – Install Python dependencies

Open your terminal / Anaconda Prompt and run:

```bash
pip install -r requirements.txt
```

Or install individually:

```bash
pip install pandas numpy matplotlib seaborn jupyter notebook
```

### Step 3 – Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 4 – Open and run the notebook

1. Open `RakeshKumarMaity_SalesDataAnalytics_Project.ipynb`
2. Click **Kernel → Restart & Run All**
3. All outputs and charts will be generated automatically

> ⚠️ Make sure `Sales& Marketing.csv` is placed inside the `dataset/` folder (`dataset/Sales& Marketing.csv`) before running.

---

## 🔍 What the Notebook Covers

| Step | Description |
|---|---|
| 1–2 | Import libraries, load dataset |
| 3–5 | Preview data, check info, summary statistics |
| 6–9 | Detect & remove missing values and duplicates |
| 10–13 | Parse dates, extract year/month, add Profit Margin column |
| 14 | Calculate key business metrics |
| 15–16 | Yearly & monthly sales trends (line + bar charts) |
| 17–18 | Category-wise sales & profit |
| 19 | Top 10 sub-categories by sales |
| 20–21 | Region-wise sales & profit (bar + pie charts) |
| 22–23 | Top 10 products by sales & profit |
| 24 | Segment-wise sales vs profit comparison |
| 25–26 | Discount vs Profit / Sales scatter plots |
| 27 | Profit margin by category |
| 28 | Correlation heatmap |
| 29 | Ship mode distribution |
| 30 | Top 10 states by sales |
| 31 | Loss-making sub-categories |
| 32–33 | Sales vs Profit scatter by category; Quantity distribution |
| 34–35 | Yearly comparison; Category × Region pivot heatmap |
| 36–37 | Summary table; Final business summary |

---

## 📊 Key Findings & Outcomes

- **Technology** generates the highest total sales among all categories.
- **Furniture** has the lowest profit margin, with some sub-categories running at a loss.
- **Higher discounts strongly correlate with lower (or negative) profits** — a key business risk.
- The **West and East regions** lead in both sales and profitability.
- **Consumer segment** places the most orders, while **Corporate** shows strong profitability.
- Month-over-month analysis reveals **Q4 (Oct–Dec)** as the peak sales period.
- The **Tables** and **Bookcases** sub-categories are the biggest loss contributors.

---

## 🎯 Business Insights

1. **Review the discount strategy** — discounts above 20% consistently lead to losses.
2. **Focus marketing on Technology** — highest sales and profit margin.
3. **Improve Furniture margins** — consider product mix adjustments or pricing changes.
4. **Target West and East regions** for further expansion.
5. **Strengthen Q1–Q3 campaigns** to reduce the seasonal sales gap.

---

## 📝 Project Report

A detailed professional report (`RakeshKumarMaity_ProjectReport.docx`) is included, covering:
- Introduction & Objectives
- Dataset Description & Methodology
- Data Cleaning & EDA
- Visualizations & Findings
- Business Insights, Conclusion & Future Scope

---

## 👤 Author

**Rakesh Kumar Maity**  
IBM SkillsBuild Data Analytics with AI Internship  

---

## 📄 License

This project is created for educational and internship purposes under the IBM SkillsBuild program.
