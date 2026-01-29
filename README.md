# Research: Women's Workday in the 21st Century
### (Pesquisa: Jornadas da Mulher do Século XXI)

A responsive web application designed to collect and visualize data regarding the workload and domestic contributions of women, partners, and family members.

## 🚀 Features
* **Interactive Data Entry:** Specialized forms for different profiles (Wife, Autonomous, Husband, Family).
* **Dynamic Dashboards:** Real-time data visualization using **Chart.js**.
    * Total participants by profile.
    * Daily workload distribution.
    * Percentage of domestic contribution.
* **Custom Data Labels:** Visual plugin that displays numerical values and percentages directly on chart elements.
* **Data Persistence:** Uses `localStorage` to keep data on the user's browser without needing a database.
* **Reporting:** Filterable results by date and activity type, with a print-ready layout.

## 🛠️ Technical Stack
* **Frontend:** HTML5, CSS3 (including Print Media Queries).
* **Logic:** Vanilla JavaScript.
* **Charts:** [Chart.js](https://www.chartjs.org/) via CDN.

## 🔒 Administrative Access
The results area and data clearing functions are protected by a master password.
* **Default Password:** `210109`

## 📊 How it Works
1. Select a profile and fill in the workload details.
2. Click the green "Secret Button" at the bottom left to view results (requires password).
3. Filter data by date or specific activity to generate reports.
