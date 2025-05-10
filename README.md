# 🏡 Australian Housing Market Dashboard 📊

This project presents a comprehensive, interactive **Excel dashboard** that provides analytical insights into the residential housing market in Australia. With dynamic visuals and filters, this tool enables users to understand property sale trends, price distributions, agency performance, and buyer behavior based on property types, price ranges, and bedroom counts.

<img width="1470" alt="Screenshot 2025-03-20 at 15 37 41" src="https://github.com/user-attachments/assets/9f36a4c9-fe34-4e4e-8d40-87c01c09935b" />

---

## 📌 Objective

To build an easy-to-use, data-driven dashboard that empowers real estate stakeholders to:

- Track the number of properties sold across agencies and suburbs.
- Understand pricing trends by property type and bedroom count.
- Visualize average sale prices by range, type, and date.
- Provide a snapshot of market activity with KPIs and charts.

---

## 🧾 Dashboard Features and Metrics

### 🎯 Top-Level KPIs (Key Performance Indicators)

| Metric         | Description                             |
|----------------|-----------------------------------------|
| **252 Properties Sold** | Total transactions within the dataset timeframe |
| **795K Median Price**   | Midpoint of all recorded sale prices |
| **195 Units Sold**      | Breakdown of sales by property type |
| **57 Houses Sold**      | Additional breakdown of detached home sales |

These high-level stats provide a **quick overview of market activity**.

---

## 📊 Visual Components and Analytical Views

### 📍 Total Property Sold by Agency

This horizontal bar chart displays:

- Agency-wise total property transactions.
- Average sale value handled per agency.
- Agencies like **Ray White Upper NorthShore** and **Raine Hornsby** dominate in volume and value.

**Insight:**  
> Real estate sales are concentrated among top agencies with substantial transaction volumes and higher average property values.

---

### 💲 Total Property Sold by Price Range

This matrix and accompanying chart show:

- Property distribution across price brackets from **300K to 1M+**.
- Aggregated average sale prices for each bracket.
- Highest sales occur between the **600K–800K** price range.

**Insight:**  
> Mid-range properties (~600K–800K) are most commonly transacted, indicating buyer preference for affordability and value.

---

### 🕒 Sales Over Time (By Month)

Bar chart comparing house and unit sales by month:

- Major peaks in **January**, **February**, and **December**.
- Separate bars for **HOUSES** vs **UNITS** allow comparative trend viewing.

**Insight:**  
> Market activity sees noticeable seasonal spikes, likely due to holiday periods, end-of-year settlements, or auction cycles.

---

### 🏠 Average Sale Price by Bedrooms

A clustered column chart showing average prices across 1–5+ bedroom configurations for houses and units:

- Larger houses (4–5 bedrooms) command higher prices.
- Units maintain tighter price ranges across bedroom counts.

**Insight:**  
> As expected, **bedroom count scales with price**, especially for standalone houses, reinforcing their value in family-oriented segments.

---

### 📊 Total Sales by Property Type

A clean donut chart with percentage splits between:

- **HOUSES**
- **UNITS**

**Insight:**  
> Property sales are split almost evenly, but with a slight edge to **units**, possibly due to affordability or urban concentration.

---

### 📉 Scatter Plot: Price vs Bedrooms

A scatter plot mapping bedroom count to sale price:

- Wider price dispersion as bedroom count increases.
- Some **outliers in high-value zones (7+ bedrooms)** highlight luxury or rare property types.

**Insight:**  
> Most properties lie in the 2–4 bedroom range under $2M, showing general affordability. Higher bedrooms create large variance in pricing, suggesting diverse property types (duplex, villas, etc.).

---

## 🧭 Filters and Slicers

### 🔘 Interactive Filters

| Filter Type | Description                                |
|-------------|--------------------------------------------|
| **Suburb**  | View data for specific geographic zones    |
| **Price Range** | Focus on specific budget categories    |

These allow tailored insight and customizable data exploration, making the dashboard interactive and user-centric.

---

## 📦 Data Source & Preparation

- The dataset is organized and cleaned in **Excel sheets**.
- Aggregations like totals, averages, and counts are done using **PivotTables**.
- Charts are dynamically linked with **slicers and named ranges** for interactivity.
- The dashboard is created using **Microsoft Excel** with native visualization tools.

---

## 🧠 Business Value

This dashboard is perfect for:

- 📈 **Real Estate Agencies**: Track agency-wise performance and market share.
- 🏢 **Investors & Buyers**: Understand pricing dynamics based on features like location, size, and month.
- 📊 **Market Analysts**: Visualize housing trends to inform reports or recommendations.
- 🧑‍💼 **Executives**: Make quick, data-driven decisions from the visual summaries.

---

## 🛠 Tools Used

| Tool            | Purpose                                |
|-----------------|----------------------------------------|
| Microsoft Excel | Dashboard development and analytics    |
| PivotTables     | Dynamic data aggregation               |
| PivotCharts     | Visualizing data in interactive form   |
| Slicers         | User-controlled filtering              |
| Conditional Formatting | KPI and value highlighting     |

---

## ✅ Features Summary

- Real-time slicing and dicing by suburb and price
- Clean layout for non-technical stakeholders
- Intuitive color-coded visualizations
- Use of standard Excel for high accessibility
- Automated updates with minimal effort

---

