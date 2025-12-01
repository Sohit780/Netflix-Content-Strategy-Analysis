# An Inside Look at Netflix's Content Strategy

This project analyzes Netflix's catalog to understand how its **content strategy** has evolved over time — focusing on content types, genres, regions, and release trends.

The goal is to turn raw data into insights that explain **what kind of content Netflix invests in**, and how that might relate to its growth and audience targeting.



## 📂 Project Overview

**Main objectives:**

- Explore how Netflix’s **content library** is distributed by:
  - Content type (Movies vs TV Shows)
  - Genre / listed categories
  - Country/region
  - Release year and addition year to Netflix
- Identify patterns in:
  - Growth of the catalog over time
  - Shift towards **originals vs licensed content** (if included in dataset)
  - Genre and regional focus
- Communicate results with clear **visualizations and explanations**.

---


## 🛠️ Tech Stack

- **Language:** Python  
- **Main Libraries:**  
  - `pandas` – data cleaning & manipulation  
  - `numpy` – numerical operations  
  - `matplotlib` / `seaborn` – visualizations  
  - `plotly` (optional) – interactive charts  
  - `jupyter notebook` – analysis environment  

---

## 📊 Key Steps in the Analysis

1. **Data Cleaning**
   - Handled missing values in `country`, `date_added`, and other columns.
   - Split multi-valued fields like `listed_in` (genres) and `country` where needed.
   - Converted date fields to proper datetime formats.

2. **Exploratory Data Analysis (EDA)**
   - Distribution of **Movies vs TV Shows** on Netflix.
   - Growth of Netflix’s catalog over time (by `date_added` and `release_year`).
   - Top **genres** and how often they appear.
   - Top **countries** contributing to Netflix’s content.
   - Analysis of **ratings** and maturity categories.

3. **Content Strategy Insights**
   - How Netflix has shifted towards certain genres (e.g., drama, international content, documentaries).
   - Increasing focus on **TV Shows** relative to Movies (if observed).
   - Regional expansion and focus on non-US markets (if visible in the data).

---

## 🧠 Key Insights (Summary)

You can adjust these based on your actual findings:

- Netflix’s catalog is **dominated by Movies**, but TV Shows have grown significantly in recent years.  
- There is a strong focus on genres like **Drama**, **International content**, and **Documentaries**, suggesting a strategy of targeting diverse global audiences.  
- Content is heavily concentrated in a few countries (e.g., US, India, UK), but the share of **non-US content** has been increasing.  
- The number of titles added each year shows a **sharp rise** after `<year you found>`, reflecting Netflix’s aggressive expansion period.  
- Maturity ratings suggest a large portion of content is targeted at **teen and adult audiences** rather than very young kids.


