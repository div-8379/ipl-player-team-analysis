# IPL Player & Team Stats Analysis

## 📌 Project Overview

This project explores Indian Premier League (IPL) cricket data from 2008 to 2024 using Python and data analysis libraries. It focuses on analysing match results, team performance, player statistics, toss decisions, and other patterns in IPL matches through data cleaning, exploratory data analysis (EDA), and visualisations.

The project was developed as a college micro-project for learning and applying Python for Data Science concepts to a real-world sports dataset.

## 🎯 Objectives

- Explore IPL match and ball-by-ball delivery data.
- Understand team performance across different seasons.
- Identify top-performing players based on runs, wickets, and awards.
- Analyse the relationship between toss decisions and match outcomes.
- Examine scoring patterns, including fours and sixes.
- Visualise important findings using charts and graphs.
- Practise data cleaning, data manipulation, and exploratory data analysis.

## ✨ Features

- **Match Data Exploration:** Inspect dataset structure, dimensions, sample records, and missing values.
- **Data Cleaning:** Check for duplicate records, handle missing city values, and examine matches with no result.
- **Season-wise Analysis:** Visualise the number of matches played across seasons.
- **Team Performance:** Compare teams based on recorded match wins.
- **Toss Analysis:** Examine toss decisions and whether the toss-winning team also won the match.
- **Player Performance:** Identify leading run scorers, wicket takers, and players with the most Player of the Match awards.
- **Scoring Analysis:** Explore fours and sixes recorded in deliveries.
- **Venue Analysis:** Examine venues hosting the most matches.
- **Match Result Analysis:** Visualise the distribution of recorded result types.

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Pandas | Loading, cleaning, filtering, grouping, and analysing tabular data |
| NumPy | Numerical operations and data handling |
| Matplotlib | Creating charts and visualisations |
| Seaborn | Producing statistical visualisations |
| Jupyter Notebook | Running code interactively and documenting the analysis |

## 📂 Dataset

The analysis uses two CSV files:

- **`matches.csv`** — Match-level information, such as seasons, teams, toss decisions, venues, winners, and match results.
- **`deliveries.csv`** — Ball-by-ball information, including batting teams, batters, bowlers, runs, boundaries, and dismissal details.

The dataset covers IPL seasons from 2008 to 2024. The exact coverage and available columns depend on the dataset version used.

**Dataset source:** IPL Complete Dataset, obtained from Kaggle.

Before redistributing the CSV files, check the dataset's licence and attribution requirements. If redistribution is not permitted, provide the original dataset link instead of committing the files.

## 📊 Analysis & Visualisations

The notebook contains visualisations covering the following areas:

1. **Matches per Season** — Compares the number of recorded matches across seasons.
2. **Team Wins** — Displays teams with the highest recorded win counts.
3. **Toss Winner vs Match Winner** — Examines how often the toss-winning team also won the match.
4. **Toss Decisions** — Shows the distribution of recorded decisions to bat or field.
5. **Top Run Scorers** — Identifies batters with the highest aggregate runs.
6. **Top Wicket Takers** — Compares bowlers using the notebook's wicket-counting logic.
7. **Fours and Sixes** — Explores boundary-scoring patterns.
8. **Matches by Venue** — Highlights venues with the most recorded matches.
9. **Player of the Match Awards** — Identifies players receiving the most awards.
10. **Match Result Types** — Compares the recorded categories of match results.

The notebook should be consulted for the actual charts and findings. Specific numerical conclusions should be added only after checking the computed results.

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/ipl-player-team-analysis.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Open the project folder

```bash
cd ipl-player-team-analysis
```

### 3. Install the required libraries

```bash
python -m pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Ensure the dataset files are available

Place `matches.csv` and `deliveries.csv` in the same directory as the notebook, unless the notebook's file paths have been configured differently.

### 5. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `IPL_Player_Team_Analysis.ipynb` and run the cells in order.

Alternatively, open the notebook in Visual Studio Code with the Python and Jupyter extensions installed, select a Python kernel, and use **Run All**.

## 📁 Project Structure

```text
ipl-player-team-analysis/
│
├── IPL_Player_Team_Analysis.ipynb
├── matches.csv
├── deliveries.csv
└── README.md
```

The CSV files should appear in the repository only if their licence permits redistribution. Otherwise, download them separately from the original source.

## 🧠 Key Learning Outcomes

Through this project, I practised:

- Working with real-world CSV datasets.
- Exploring data using Pandas.
- Identifying missing values and duplicate records.
- Filtering and aggregating data for statistical comparisons.
- Analysing match-level and delivery-level cricket statistics.
- Creating visualisations to communicate patterns in data.
- Using Jupyter Notebook to combine code, outputs, and analysis.

## 🤖 AI Assistance & Acknowledgment

Claude AI was used as an assistance tool during the development of this college micro-project. I used AI assistance while working on the code and analysis, and I ran the notebook to examine its outputs and visualisations.

I am continuing to review the implementation, validate the calculations, and strengthen my understanding of the analysis so I can explain and improve the project independently.

## 🔮 Possible Future Improvements

- Add more detailed season-by-season comparisons.
- Validate wicket-counting logic and other statistical calculations.
- Analyse winning margins and innings-level performance.
- Compare batting and bowling performance across seasons.
- Add interactive filters and visualisations.
- Build a simple dashboard for exploring IPL statistics.

## 📌 Project Status

**Status:** Initial exploratory data analysis completed; further validation and improvements are possible.

This project is intended for educational purposes and demonstrates the application of Python data analysis techniques to IPL cricket statistics.

---

**Created as a college micro-project for Python for Data Science.**
