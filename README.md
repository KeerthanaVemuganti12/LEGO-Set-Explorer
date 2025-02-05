# 🧱 LEGO Sets Data Analysis

## 🔎 Problem Statement
Analyzing LEGO sets to identify patterns in pricing, age range, and piece count can provide valuable insights for collectors, retailers, and enthusiasts. This project explores LEGO set data, prepares it for analysis, and builds an interactive Power BI report to visualize key trends.

---

## 📌 Objective 1: Load and Prepare the Data
- Connected to the `lego_sets` CSV file.
- Removed unnecessary fields (`minifigs`, `bricksetURL`, `thumbnailURL`).
- Reviewed data types for accuracy and filtered out records with missing values for price, age, pieces, or image URL.
- Identified the number of remaining sets and analyzed the price range.
- Created conditional columns for:
  - **Age Range:** Over 18, 10 to 17, 5 to 9, 1 to 4.
  - **Price Range:** Categorized into different levels ($ to $$$$$).
- Added DAX measures for:
  - **Total Sets:** Count of distinct LEGO sets.
  - **Total Groups:** Count of theme groups.
  - **Average Age, Price, and Pieces.**

---

## 📌 Objective 2: Design the Report Layout & Visuals
- Sketched potential report layouts based on project objectives.
- Inserted card visuals for:
  - **Total Sets, Average Pieces, and Average Price.**
- Added slicers for filtering by:
  - **Theme Group, Theme, and Age Range.**
- Inserted a table displaying:
  - **Set Name, Set ID, Theme, Age Range, Average Pieces, Average Price, and Price Range.**
- Designed a report section for selected set details, displaying:
  - **Name, Image, Price, Year, Pieces, and Age.**
- Configured visual interactions to prevent table selections from filtering top-level cards.

---

## 📌 Objective 3: Add Interactive Components
- Created a **Max Price parameter** (0-850, incrementing by 5) and added a slicer for filtering based on the selected price.
- Enabled **tooltips** to display LEGO set images on hover.
- Used **bookmarks and button actions** to allow users to reset all filters (with customized hover and press states).
- Created a new report page with a **decomposition tree visual** analyzing Total Sets by category, theme group, theme, and name.
- Added **navigation buttons** for easy page transitions.

---

## 📊 Key Insights
- **LEGO sets vary significantly in price, piece count, and targeted age groups.**
- **Certain themes have higher average prices, making them more premium or collectible.**
- **Providing interactive filters allows users to explore specific LEGO categories and find valuable insights.**

---

## 📂 Files Included
- **Power BI Report:** `Lego Set Explorer.pbix`
- **Dataset & Resources:** `LEGO Sets.zip`

This project showcases data preparation, visualization, and interactive reporting using Power BI. Let me know if you need any modifications or additional insights! 🚀

