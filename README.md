# 🥦 Protein Cost-Effectiveness Analysis – Vegan vs Non-Vegan Foods

This project investigates whether vegan food is the most cost-effective source of protein compared to non-vegan alternatives. It includes a comprehensive data scraping pipeline, cleaning routines, data analysis, and an interactive Tableau visualization. The analysis is based on over 12,000 products scraped from Tesco Ireland's website.

## 📊 Key Insight

While vegan foods like oats and peas are among the cheapest sources of protein, they often derive most of their calories from carbohydrates. Non-vegan products dominate when considering a balanced macronutrient profile, especially at thresholds like 20% calories from protein.

---

## 🧰 Tools & Technologies Used

- **Python (Google Colab)** – Scraping, cleaning, data preprocessing
- **JavaScript** – Extracting product URLs
- **Tableau** – Final visualization
- **YouTube** – 📽 [Project Walkthrough Video](https://www.youtube.com/watch?v=WaRZlrU8WZ0)

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `Shopping_Scraper.ipynb` | Scrapes product and nutrition data from Tesco Ireland |
| `TescoCleaner.ipynb` | Cleans and processes raw product data |
| `ColumnSterilizer.ipynb` | Handles column standardization and normalization |
| `duplicate_purger.ipynb` | Removes duplicate or inconsistent entries |
| `Report.pdf` | Full written report on methodology, findings, and conclusions |
| `Visualization Report.twb` | Tableau dashboard showing cost-effectiveness of protein |

---

## 📈 Visualization

The final Tableau dashboard focuses on the **cheapest protein sources** (≥20% protein calories). The design emphasizes:
- Protein calorie contribution vs total calories
- Vegan 🌱 vs Non-Vegan ❌ products
- Energy efficiency (kcal) vs cost

---

## 🧪 Key Findings

- **Oats** are the cheapest protein source but provide low protein density.
- **Top 10 calorie sources** are entirely vegan.
- **Top 10 protein sources (≥20% protein)** are predominantly non-vegan.
- Vegan foods are cost-effective but less suited for high-protein diets.

---

## 👥 Team Contributions

- **Mervin** – JavaScript scraping, URL extraction
- **Saurav Nambiar** – Data visualization in Tableau, joint data processing
- **Joint work** – Data scraping, cleaning, and analysis using Python

---

## 🔮 Future Work

- Include micronutrient data and sustainability factors
- Enhance product classification (vegan/vegetarian/flexitarian)
- Extend analysis to other supermarkets and regions

---

## 📬 Contact

For questions or collaborations, feel free to reach out via GitHub Issues or LinkedIn.
