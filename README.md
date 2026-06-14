# 🍽️ Zomato Restaurant Data Analysis

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on Zomato restaurant data to uncover insights about customer preferences, restaurant types, ratings, and ordering patterns using Python.

---

## 🎯 Objective
To analyze Zomato restaurant data and answer key business questions such as:
- Which type of restaurant receives the most votes?
- What is the rating distribution across restaurants?
- Do restaurants that accept online orders have better ratings?
- Which restaurant types prefer online vs offline orders?

---

- **Key Columns:**

| Column | Description |
|--------|-------------|
| `name` | Restaurant name |
| `online_order` | Accepts online orders? (Yes/No) |
| `book_table` | Accepts table booking? (Yes/No) |
| `rate` | Restaurant rating (out of 5) |
| `votes` | Number of customer votes |
| `approx_cost` | Approximate cost for two people |
| `listed_in(type)` | Type of restaurant (Dining, Cafe, Buffet, etc.) |

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data loading, cleaning, manipulation |
| NumPy | Numerical operations |
| Matplotlib | Basic data visualization |
| Seaborn | Advanced statistical visualization |
| Jupyter Notebook | Interactive development environment |

---

## 📊 Analysis Performed

### 1. Votes by Restaurant Type
- Grouped restaurants by type and summed total votes
- Plotted a line chart to compare popularity across types
- **Insight:** Dining restaurants receive the most votes overall

### 2. Restaurant with Maximum Votes
- Identified the most popular restaurant by vote count
- **Insight:** Reveals the top-rated restaurant in the dataset

### 3. Ratings Distribution
- Plotted a histogram of all restaurant ratings
- **Insight:** Most restaurants are rated between 3.5 and 4.5

### 4. Online Order vs Rating (Box Plot)
- Compared rating distributions between restaurants that accept online orders vs those that don't
- **Insight:** Restaurants accepting online orders tend to have slightly higher ratings

### 5. Heatmap — Orders by Service Type
- Created a pivot table of restaurant type vs online order acceptance
- Visualized using a heatmap
- **Insight:** Dining restaurants prefer offline orders (77 vs 33), while Cafes prefer online orders (15 vs 8)

---

## 🔍 Key Insights

1. **Dining restaurants** are the most popular category with the highest votes
2. **Most restaurants** are rated between 3.5 and 4.5 — very few get extremely low or high ratings
3. **Restaurants with online ordering** tend to receive better ratings
4. **Dining = offline preferred** — customers visit in person for the full dining experience
5. **Cafes = online preferred** — customers order ahead for convenience and quick pickup
6. **Buffets** have very few listings and almost equal online/offline split

---

## 🚀 How to Run This Project

1. Clone the repository:
```bash
git clone https://github.com/pschandana/Zomato-Restaurant-Data-Analysis.git
```

2. Navigate to the project folder:
```bash
cd Zomato-Restaurant-Data-Analysis
```

3. Install required libraries:
```bash
pip install pandas numpy matplotlib seaborn
```

4. Open the Jupyter Notebook:
```bash
jupyter notebook Zomao_dataAnalysis_Project.ipynb
```

5. Run all cells in order

---

## 📁 Project Structure
```
Zomato-Restaurant-Data-Analysis/
│
├── Zomao_dataAnalysis_Project.ipynb   # Main analysis notebook
├── Zomato-data-.csv                    # Dataset
└── README.md                           # Project documentation
```

---

