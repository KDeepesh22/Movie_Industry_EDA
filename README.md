
# 🎬 Movie Industry – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the movie industry to identify the key factors influencing movie success and profitability.

The objective is to analyze historical movie data and generate actionable business insights that can help a company make informed decisions before entering the movie industry.

Using Python and various data analysis libraries, this project explores movie budgets, genres, release dates, actors, directors, ratings, awards, and studio performance.

## 🎯 Business Objectives

The analysis aims to answer the following eight business questions:

1. **Movie Profitability:** What are the most profitable movies, and what production budget should a company consider?
2. **Genre Analysis:** Which movie genres are most popular, and which genres offer better opportunities with relatively lower competition?
3. **Release Timing:** Which months are most suitable for releasing movies across different genres?
4. **Actors & Directors:** Which actors and directors should the company consider based on their performance?
5. **Oscar Awards:** What budget range should the company consider for producing movies with the potential to receive Oscar nominations?
6. **Movie Ratings:** Which content ratings and runtime ranges are associated with better movie performance?
7. **Studio Performance:** What profit margins and net profits should the company target to compete with established studios?
8. **Competitor Analysis:** Which existing movie studios provide useful benchmarks based on their performance?

## 🛠️ Technologies & Libraries Used

- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Development Environment:** Jupyter Notebook

## 📊 Key Insights & Business Recommendations

Based on the analysis, the following recommendations were identified:

### 1. Production Budget
- Recommended inflation-adjusted production budget: approximately **$82.25 million**.
- Associated median profit margin: approximately **81.9%**.

### 2. Genre Selection
- Adventure, Action, Comedy, Drama, Sci-Fi, and Animation emerged as promising genres.
- Sci-Fi and Animation offer opportunities with comparatively lower competition in the analyzed dataset.

### 3. Movie Release Timing
- Summer was identified as a generally strong release period.
- Summer releases were particularly promising for Animation movies.

### 4. Actors & Directors
- Consider actors and directors with consistently strong VAR scores to improve the potential performance of movies.

### 5. Oscar Awards
- The median inflation-adjusted budget for movies receiving at least three Oscar nominations was approximately **$35.47 million**.

### 6. Ratings & Runtime
- G/PG ratings were identified as suitable for Animation movies.
- PG-13 was recommended as a general target rating.
- Runtime showed only a weak relationship with net profit.

### 7. Studio Performance
- Target profit margin: approximately **66%**.
- Target net profit: slightly above **$50 million per movie**.

### 8. Competitor Analysis
- Disney was identified as a studio worth studying based on theater performance and Oscar win rates.

*Note: These recommendations are based on historical data and the assumptions used in the analysis. They do not guarantee future movie performance.*

## 📁 Project Structure

```text
Movie_Industry_EDA/
│
├── Python - Movie Industry EDA Project.ipynb
│
└── README.md
```

## 📂 Dataset Requirements

The notebook uses the following CSV datasets:

- `movie_release_dates.csv`
- `movie_theater_data.csv`
- `movie_awards.csv`
- `Actors_Table.csv`
- `Directors_Table.csv`
- `IMDb_base.csv`
- `IMDb_budgets.csv`
- `studiodf.csv`

These datasets must be available in the notebook's working directory to execute the analysis.

## ⚙️ How to Run the Project

**Step 1:** Clone the repository.

```bash
git clone https://github.com/KDeepesh22/Movie_Industry_EDA.git
```

**Step 2:** Navigate to the project directory.

```bash
cd Movie_Industry_EDA
```

**Step 3:** Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**Step 4:** Ensure all required CSV datasets are placed in the project directory.

**Step 5:** Launch Jupyter Notebook.

```bash
jupyter notebook
```

**Step 6:** Open `Python - Movie Industry EDA Project.ipynb` and execute the cells sequentially.

## 🔍 Analysis Methodology

The project follows a structured EDA approach:

- Data loading and initial exploration.
- Data cleaning and preprocessing.
- Handling missing and irrelevant records.
- Data filtering and transformation.
- Inflation adjustment for historical financial data.
- Exploratory analysis using grouping and aggregation.
- Data visualization and pattern identification.
- Business insights and strategic recommendations.

## ⚠️ Limitations

- The analysis is based on historical movie-industry data.
- Inflation adjustment uses a 3.22% annual rate with 2020 as the reference year.
- Correlation between variables does not necessarily imply causation.
- Some studio and award comparisons are based on limited overlapping records.
- The findings depend on the completeness and accuracy of the available datasets.

## 🚀 Future Improvements

- Develop an interactive movie-industry analytics dashboard using Power BI.
- Incorporate additional financial metrics such as marketing and distribution costs.
- Apply predictive analytics and machine learning to forecast movie profitability.
- Expand the dataset with recent movie releases.
- Perform deeper statistical analysis to validate the identified relationships.

## 👨‍💻 Author

**Deepesh Kumar**

B.Tech | Indian Institute of Technology (IIT) Patna

GitHub: [KDeepesh22](https://github.com/KDeepesh22)

LinkedIn: [Deepesh Kumar](https://www.linkedin.com/in/deepesh-kumar-23b6a433a/)

---

⭐ If you find this project interesting, consider giving this repository a star!
