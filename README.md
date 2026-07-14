# 🎬 Movies Analysis Dashboard — Power BI

An interactive Power BI dashboard that analyzes movie performance using key metrics such as **Budget, Box Office Revenue, Profit/Loss, and Oscar Wins**. Built to explore how a movie's financial investment relates to its box office success and award recognition.

---

## 📊 Overview

This project takes raw movie data (prepared in **Excel**) and transforms it into a clean, interactive **Power BI** dashboard with two dedicated pages:

- **Home Page** — A landing page with the dashboard title and navigation buttons to move between report pages.
- **Detail Page** — The core analysis page with KPI cards and a visual breakdown of movie performance.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Data cleaning, structuring, and preprocessing |
| **Power BI Desktop** | Data modeling, DAX calculations, and dashboard/report building |

---

## 📈 Key Metrics (KPI Cards)

The Detail page highlights four core performance indicators:

- 💰 **Total Budget** — Total investment across movies
- 🎟️ **Box Office** — Total box office revenue generated
- 📉 **Profit / Loss** — Net financial outcome per movie/overall
- 🏆 **Oscar Wins** — Total award recognition earned

A **Donut Chart** is included on the Detail page for categorical breakdown of the data.

---

## 🖥️ Dashboard Pages

### 1. Home
- Dashboard title/banner
- Navigation buttons (Home / Detail) for smooth page switching

### 2. Detail
- 4 KPI summary cards (Budget, Box Office, Profit/Loss, Oscar Wins)
- Donut chart for visual breakdown
- Styled with rounded rectangle background shapes for a clean card-style UI

---

## 📂 Data Source

The dataset was cleaned and prepared in **Excel** before being loaded into Power BI, containing movie-level details such as Budget, Box Office collection, Profit/Loss, and Oscar Wins.

---

## 🚀 How to Use

1. Clone/download this repository
2. Open `power_bi_movies.pbix` in **Power BI Desktop**
3. Use the navigation buttons on the Home page to explore the Detail page
4. Interact with the visuals to explore movie performance insights

> **Note:** Power BI (.pbix) files cannot be previewed directly on GitHub. Download the file and open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) to view the interactive report.

---

## 🔮 Future Improvements

- Add Genre-wise and Year-wise trend charts
- Add slicers for Year, Genre, and Director to enable filtering
- Replace implicit aggregations with custom DAX measures
- Add a Top 10 Movies (by Revenue/Profit) bar chart
- Add screenshots/GIF preview of the dashboard in this README

---

## 👤 Author

Made with 🎥 and 📊 as part of a data analysis portfolio project.
