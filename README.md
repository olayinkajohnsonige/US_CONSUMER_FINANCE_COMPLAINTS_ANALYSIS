
#  US Consumer Financial Analysis

## 📖 Project Overview

This project focuses on cleaning and preprocessing raw US consumer finance complaint data. By transforming and structuring the dataset, it ensures high-quality, consistent data, enabling accurate insights and informed decision-making.

---

## 🎯 Objectives

This project streamlines data preparation for consumer finance complaints:

* 🧹 **Data Cleaning:** Removes inconsistencies and handles missing values.
* 🔄 **Data Transformation:** Converts raw data into structured formats.
* ⚖️ **Data Standardization:** Ensures uniform preprocessing steps.
* ⚙️ **Reproducible Pipelines:** Supports automation and repeatable workflows.
* 📊 **Enhanced Data Quality:** Provides a solid foundation for accurate analysis.

---

## 📂 Dataset

The analysis uses US consumer complaints on financial products and company responses.

* **Original Dataset Name:** US Consumer Finance Complaints

* **Source Platform:** Kaggle

* **Original Author:** Kaggle Team Bot

**Key Columns:**

* `date_received` – date complaint was received
* `date_sent_to_company` – date sent to company
* `consumer_complaint_narrative` – complaint description
* `product`-Financial product category
* `sub_product`-Sub-category of the product
* `complaint_id`-Unique identifier for the complain
* `issue`-Main issue reported
* `sub_issue`-Sub-category of the issue
* `company`-Company involved in the complaint
* `company_response_to_consumer`-Type of response from the company
* `state`-State of the consumer
* `zipcode`-ZIP code of the consumer

---

## 🔍 Analysis & Key Questions

The project answers these questions:

1. **⏱ Time-based Analysis**

   * Complaints per year/month/day
   * Average response time by company

2. **📦 Product/Sub-product Focus**

   * Most complained-about products
   * Sub-products driving complaints

3. **⚠️ Issues/Sub-issues**

   * Most common consumer problems
   * Dominant issues per product

4. **🏢 Company Analysis**

   * Companies with most complaints
   * Differences in response types

5. **📍 Geographical Analysis**

   * Complaints per state
   * Complaints per ZIP code

---

## 📊 Visualizations

Key visualizations included:

* 📈 **Line Charts:** Complaints over time
* 📉 **Histogram:** Response time distribution
* 📊 **Bar Charts:**

  * Top 10 products
  * Top 15 companies
  * Common issues
  * Company responses
* 🌳 **Treemap:** Sub-products by complaints count
* 🔥 **Heatmap:** Issues by product
* 🗺 **Choropleth:** Complaints per state
* 🏙 **Bar:** Top 15 ZIP codes

---

## 🛠 Tech Stack

* **Language:** Python
* **Libraries:**

  * `pandas` – data manipulation
  * `matplotlib` – visualizations
  * `seaborn` – statistical charts
  * `squarify` – treemaps
  * `plotly(express&offline)` – interactive charts
  * `cufflinks`-Plotly + Pandas integration
* IDE:VS Code
---

## ✍️ Author

Olayinka Johnson-Ige


---


