# 🛒 Mahadev Ecommerce Sales Dashboard

An interactive Power BI dashboard that analyzes ecommerce sales performance, profit trends, customer behavior, and product category insights across multiple states and payment modes.

---

## 📌 Project Overview

This project presents a comprehensive **ecommerce sales analytics dashboard** built in Power BI, designed to help business owners, sales managers, and analysts track revenue, monitor profit trends, and understand customer purchasing patterns.

The dashboard leverages two CSV datasets covering orders and order details, enabling dynamic exploration of sales data across quarters, cities, product categories, and payment methods.

---

## 📊 Dashboard Features

The dashboard consists of **8 interactive visuals** with cross-filtering support:

| Visual                                   | Description                                                                                                                                        |
| ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- |
| 💰**KPI Cards**                    | Top-level metrics — Sum of Amount (438K), Sum of Profit (37K), Sum of Quantity (5615), and Sum of AOV (121K)                                      |
| 📊**Top States**                   | Horizontal bar chart showing revenue by state — Maharashtra leads, followed by Madhya Pradesh, Uttar Pradesh, Delhi, and Rajasthan                |
| 🍩**Quantity per Category**        | Donut chart showing sales split across Clothing (62.62%), Electronics (20.5%), and Furniture (16.83%)                                              |
| 👥**Top Customers**                | Bar chart ranking the highest-spending customers — Harivansh, Madhav, Madan Mohan, Shiva, and Vishakha                                            |
| 💳**Payment Mode**                 | Donut chart breaking down transactions by payment method — COD (43.74%), UPI (20.61%), Debit Card (13.2%), Credit Card (11.97%), and EMI (10.49%) |
| 📈**Profit by Month**              | Bar chart showing monthly profit fluctuations across the year (January–December)                                                                  |
| 🏆**Total Profit by Sub-Category** | Horizontal bar chart highlighting the most profitable sub-categories — Printers, Bookcases, Sarees, Accessories, and Tables                       |
| 🔘**Quarter Filter**               | Buttons (Qtr 1–4) to slice all visuals by quarter                                                                                                 |
| 🌆**City Filter**                  | Dropdown to filter the entire dashboard by city/region                                                                                             |

---

## 🔍 Key Insights

- **Total Sales Amount:** ₹438K across all categories and regions
- **Total Profit:** ₹37K with notable peaks in January and November
- **Top Category by Quantity:** Clothing dominates at 62.62% of total quantity sold
- **Most Profitable Sub-Category:** Printers generate the highest profit, followed by Bookcases
- **Preferred Payment Mode:** COD is the most used method at 43.74%, followed by UPI at 20.61%
- **Top Performing State:** Maharashtra leads in revenue among all states

---

## 🗂️ Dataset Description

The dashboard is powered by **2 CSV files**:

**1. Orders.csv** — Customer and order-level data

| Column           | Description                         |
| ---------------- | ----------------------------------- |
| `Order ID`     | Unique identifier for each order    |
| `Order Date`   | Date the order was placed           |
| `CustomerName` | Name of the customer                |
| `State`        | State where the order was delivered |
| `City`         | City of delivery                    |

**2. Order Details.csv** — Product and transaction-level data

| Column           | Description                                           |
| ---------------- | ----------------------------------------------------- |
| `Order ID`     | Links to Orders.csv                                   |
| `Amount`       | Sale amount for the order                             |
| `Profit`       | Profit earned on the order                            |
| `Quantity`     | Number of units sold                                  |
| `Category`     | Product category (Clothing, Electronics, Furniture)   |
| `Sub-Category` | Detailed product type (Printers, Saree, Tables, etc.) |
| `PaymentMode`  | Mode of payment used (COD, UPI, EMI, etc.)            |

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** — Dashboard creation and visualization
- **CSV Files** — Data source format (2 files)
- **Power Query** — Data cleaning, transformation, and relationship building between the two datasets

---

## 🚀 How to Use

### Option 1: Open Locally in Power BI

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/mahadev-ecommerce-dashboard.git
   cd mahadev-ecommerce-dashboard
   ```
2. Open **Power BI Desktop** (latest version recommended)
3. Open the `.pbix` file from the repo:
   ```
   File → Open → mahadev_ecommerce_dashboard.pbix
   ```
4. The workbook loads with the embedded data — no additional setup needed

### Option 2: Connect to Your Own Data

1. Open Power BI Desktop
2. Go to **Home → Transform Data**
3. Update the file paths for `Orders.csv` and `Order Details.csv` to point to your local copies
4. Ensure column names match exactly as described in the Dataset section above
5. Click **Close & Apply** to refresh the dashboard

---

## 🔄 Dashboard Interactivity

All visuals in the dashboard act as **interactive cross-filters**. Clicking any element updates the rest of the dashboard in real time:

- Click a **state bar** → filters all visuals to show only that state's data
- Click a **payment mode slice** → filters to show only orders using that payment method
- Click a **category slice** → filters all charts to that product category
- Click **Qtr 1 / Qtr 2 / Qtr 3 / Qtr 4** buttons → slices entire dashboard by quarter
- Select a **city from the dropdown** → narrows all visuals to that specific city
- Hover over any bar or chart element → shows an exact tooltip with the underlying values

---

## 📁 Repository Structure

```
mahadev-ecommerce-dashboard/
│
├── 📂data 
│   ├── Details.csv
│   └── Orders.csv  
├── 📄 mahadev_ecommerce_dashboard.pbix  # Power BI dashboard file
│
├── 📂 Dashboard Images/
│   ├── dashboard_overview.png
│   └── ...                              # Additional filtered view screenshots
│
└── README.md
```

---

## 🎯 Use Cases

This dashboard is valuable for:

- **Business Owners** tracking overall sales health and profitability at a glance
- **Sales Managers** identifying top-performing states, customers, and product categories
- **Marketing Teams** understanding payment preferences and targeting high-value customer segments
- **Analysts & Students** learning Power BI dashboard design with real ecommerce data

---

## 📬 Contact

**Created by:** Shlok Panchal
**LinkedIn:**[www.linkedin.com/in/panchalshlok](http://www.linkedin.com/in/panchalshlok)
**Email:** shlokpanchal1812@gmail.com

---

## ⭐ If you found this useful, please star the repo!

```bash
git clone https://github.com/SHLOK9998/Sales_Dashbaord.git
```
