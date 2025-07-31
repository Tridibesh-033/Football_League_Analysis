# ⚽ Football League Standings Analysis

## 📌 Overview

This project analyzes **Spanish La Liga standings** to determine:

- Teams qualifying for **Champions League, Europa League, and Conference League**
- **Relegated teams**

Data is fetched using a free football API or loaded from an Excel file.

---

## 🔧 Steps

1. **API Authentication**
   - Used RapidAPI headers (AllSportsAPI was not used due to cost).

2. **Fetch Data**
   - Country key for Spain (`ccode="ESP"`)
   - League ID for La Liga
   - Standings data (matches, wins, draws, losses, goals, points)

3. **Create DataFrame**
   - Stored data in a Pandas DataFrame.

4. **Save to Excel**
   - Saved as `la_liga_standings_1.xlsx`.

5. **Analyze Standings**
   - Top 4 → Champions League  
   - 5th → Europa League  
   - 6th → Conference League  
   - Bottom 3 → Relegation

---

## 🛠️ Tools Used

- **Python**
- **Pandas**
- **Requests**

---

## ✨ Author

**Tridibesh Debnath**  
B.Tech (CSE - Data Science) student

[LinkedIn](https://www.linkedin.com/in/tridibesh-debnath) | [GitHub](https://github.com/TridibeshDebnath)

---

