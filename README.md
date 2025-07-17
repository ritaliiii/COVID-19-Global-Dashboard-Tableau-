
# COVID-19 Global Dashboard (Tableau)

An interactive **Tableau dashboard** visualizing global **COVID-19 confirmed cases** and **deaths** over time. This dashboard provides insights into the spread of the virus by country and over time, using geospatial and trend visualizations.

<img width="1712" height="1071" alt="Screenshot 2025-07-17 at 8 53 02 AM" src="https://github.com/user-attachments/assets/ab448ab1-cef4-447d-ad7f-2c2b23fb31b0" />


---

## Features

- **Global map** with bubble markers sized by confirmed cases
- Time-series line charts of:
  - Confirmed cases
  - Confirmed deaths
- **Top 10 countries** ranked by:
  - Total confirmed cases
  - Total confirmed deaths
- **Date filter** to view data trends over specific periods
- Interactive visualizations with filterable elements

---

## Tools Used

- **Tableau Desktop**  
- **Data Source**: Public COVID-19 dataset 

---

## Dashboard Components

| Component            | Description                                      |
|----------------------|--------------------------------------------------|
| **Map**              | Bubble map showing confirmed cases globally     |
| **Confirmed Cases**  | Cumulative line chart with interactive tooltip  |
| **Confirmed Deaths** | Cumulative death chart with similar trend lines |
| **Top Countries**    | Horizontal bar charts for top 10 countries      |

---

## Data Preparation

1. Cleaned and standardized country names
2. Parsed and aggregated daily data by country and date
3. Calculated cumulative counts for visualization
4. Created ranking metrics for dynamic top 10 charts

---

## How to Use

1. Open the Tableau workbook (`.twbx`) in **Tableau Desktop**  
2. Interact with the **date slider** to adjust the time window  
3. Hover over visual elements for tooltips  
4. Filter by region or country as needed

