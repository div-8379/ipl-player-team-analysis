# IPL Player & Team Stats Analysis 🏏

## 📌 Project Overview

This project explores Indian Premier League (IPL) cricket data using Python and data analysis libraries. It focuses on match outcomes, team performance, individual player statistics, toss decisions, scoring patterns, and venue trends through Exploratory Data Analysis (EDA) and data visualisation.

Developed as a college micro-project for **Python for Data Science**, this project applies data analysis techniques to real-world cricket data.

## 🎯 Project Objectives

- Analyse IPL match results and team performance.
- Identify leading run scorers, wicket takers, and award-winning players.
- Explore the relationship between toss outcomes and match results.
- Examine scoring patterns involving fours and sixes.
- Investigate season-wise match counts and venue trends.
- Practise data cleaning, aggregation, and visualisation using Python.

## ✨ Features

- **Data Exploration:** Inspect dataset dimensions, columns, data types, and sample records.
- **Data Cleaning:** Examine missing values, handle missing city information, and check duplicate records.
- **Season Analysis:** Visualise the number of matches recorded in each season.
- **Team Performance:** Compare teams by recorded match wins.
- **Toss Analysis:** Explore toss decisions and compare toss winners with match winners.
- **Batting Analysis:** Identify players with the highest aggregate runs.
- **Bowling Analysis:** Compare wicket counts using the notebook's dismissal-filtering logic.
- **Boundary Analysis:** Examine fours and sixes.
- **Venue Analysis:** Identify venues hosting the most matches.
- **Player Awards:** Compare players by Player of the Match awards.
- **Result Analysis:** Visualise the distribution of recorded match result categories.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| Pandas | Data loading, cleaning, filtering, grouping, and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical charts and visualisation |
| Jupyter Notebook | Interactive coding, analysis, and chart display |

## 📊 Dataset Information

This project uses the **IPL Complete Dataset (2008–2024)**, attributed to Patrick B. on Kaggle. The dataset contains match-level information and ball-by-ball delivery records.

### Original dataset source

[Kaggle — IPL Complete Dataset (2008–2024)](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)

The dataset's acknowledgements identify Cricsheet as a data source.

### Files required

| Filename | Description |
|---|---|
| `matches.csv` | Match-level records, including seasons, teams, toss decisions, venues, winners, and results |
| `deliveries.csv` | Ball-by-ball records, including batters, bowlers, runs, extras, and dismissal information |

The notebook reads both files using their filenames, so they must be available in the notebook's working directory when running the analysis.

### Why are the CSV files not included in this repository?

The dataset files are not included in this repository at present.

- **`deliveries.csv`:** The file is approximately 26 MB, which exceeds GitHub's 25 MiB per-file limit for uploading files through the web interface.
- **Dataset management:** Keeping the large source dataset separate makes the repository smaller and avoids unnecessary duplication.
- **Redistribution:** The dataset's applicable licence and attribution requirements should be checked before redistributing its files.

These files have not been removed from the original dataset. Download them from the Kaggle source linked above and place both CSV files alongside the notebook before running it.

## 📈 Analysis & Visualisations

The notebook includes visualisations for the following areas:

1. Matches played per season.
2. Teams ranked by recorded match wins.
3. Toss winner compared with match winner.
4. Distribution of toss decisions.
5. Top run scorers.
6. Top wicket takers.
7. Fours and sixes.
8. Matches hosted by venue.
9. Player of the Match awards.
10. Match result categories.

The actual charts and their computed values are available in the Jupyter notebook. Numerical findings should be interpreted from the notebook outputs rather than assumed from the chart titles alone.

## 🚀 How to Run the Project

### 1. Download the repository

Download or clone this repository to your computer.

```bash
git clone https://github.com/YOUR-USERNAME/ipl-player-team-analysis.git
cd ipl-player-team-analysis
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Download the dataset

Open the [original Kaggle dataset page](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020), download the dataset, and extract the required files.

Place `matches.csv` and `deliveries.csv` in the same folder as the notebook.

The final folder should look like this:

```text
ipl-player-team-analysis/
│
├── IPL_Player_Team_Analysis.ipynb
├── README.md
├── matches.csv
└── deliveries.csv
```

The CSV files are downloaded separately and are not currently stored in this GitHub repository.

### 3. Install the required libraries

Make sure Python is installed, then run:

```bash
python -m pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Open Jupyter Notebook

Launch Jupyter with:

```bash
jupyter notebook
```

Alternatively, open the repository folder in Visual Studio Code, install the Python and Jupyter extensions, and open `IPL_Player_Team_Analysis.ipynb`.

### 5. Run the notebook

Select a Python kernel and use **Run All** to execute the notebook cells in order.

If Python reports that a CSV file cannot be found, verify that both dataset files are present in the correct working directory.

## 🧠 Learning Outcomes

This project provides practice in:

- Reading and inspecting CSV datasets with Pandas.
- Understanding data types, missing values, and duplicate records.
- Filtering and aggregating records to answer analytical questions.
- Working with match-level and ball-by-ball cricket data.
- Creating charts with Matplotlib and Seaborn.
- Using Jupyter Notebook for interactive analysis.
- Interpreting patterns in a real-world sports dataset.

## 🤖 AI Assistance & Acknowledgment

Claude AI was used as an assistance tool during the development of this college micro-project. AI assistance contributed to working through the implementation and analysis.

The notebook was executed to examine the generated outputs and visualisations. I am continuing to review the code, verify the calculations, and deepen my understanding so that I can explain and improve the project independently.

## 🔮 Future Improvements

Potential improvements include:

- Validating wicket-counting logic and other statistical calculations.
- Adding more detailed season-wise comparisons.
- Analysing winning margins and innings-level performance.
- Exploring how batting and bowling trends change across seasons.
- Improving chart annotations and adding data-backed conclusions.
- Developing an interactive dashboard for exploring IPL statistics.

## 📌 Project Status

**Status:** Initial exploratory data analysis completed; further validation and improvements are planned.

This project is intended for educational purposes and demonstrates the use of Python data analysis libraries to explore IPL cricket statistics.

---

*College micro-project — Python for Data Science.*
