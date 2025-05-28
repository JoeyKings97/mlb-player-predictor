# MLB Player Stats Predictor ⚾

This project uses machine learning and real-time MLB data to predict player performance for daily matchups. It analyzes batter vs. pitcher history, current season data, and team schedules to generate accurate stat projections for both hitters and pitchers.

---

## 🔧 Features

- ✅ **Automated Daily Matchup Analysis**
  - Fetches the current day's MLB schedule
  - Looks up batter vs. pitcher history using Statcast
  - Filters by active players only

- 🔮 **Stat Predictions Using Machine Learning**
  - Predicts key stats for upcoming games:
    - **Pitcher Stats:** Strikeouts, Hits Allowed, Fantasy Score, Walks, Earned Runs, etc.
    - **Hitter Stats:** Total Bases, Home Runs, RBIs, Hits+Runs+RBIs, Stolen Bases, etc.

- 📊 **Data Storage**
  - Saves raw data and predictions to CSV files in the `data/` folder
  - Models stored in `models/` for reuse and evaluation

- 🛠️ **Modular Python Scripts**
  - `scripts/` contains all automation and analysis scripts
  - Easy to extend or schedule (via cron/Task Scheduler)

---

## 📁 Folder Structure

MLB-PLAYER-STATS-PREDICTOR/
├── data/ # Matchup CSVs and prediction outputs
├── models/ # Trained ML models (.pkl)
├── scripts/ # Python scripts for automation and analysis
│ ├── matchup_lookup.py
│ ├── fetch_schedule.py
│ └── predict_stats.py
├── requirements.txt # Python dependencies
└── README.md # This file


---

## 🧠 Technologies Used

- [Python 3.x](https://www.python.org/)
- [pybaseball](https://github.com/jldbc/pybaseball)
- [pandas](https://pandas.pydata.org/)
- [scikit-learn](https://scikit-learn.org/)
- [NumPy](https://numpy.org/)
- [matplotlib / seaborn](https://matplotlib.org/)

---

## 🚀 Getting Started

1. Clone this repo and install dependencies:

   ```bash
   git clone https://github.com/yourusername/MLB-PLAYER-STATS-PREDICTOR.git
   cd MLB-PLAYER-STATS-PREDICTOR
   pip install -r requirements.txt

2. Run your first matchup lookup:

    ```bash
    python scripts/matchup_lookup.py

3. Automate Daily Analysis:

    ```bash
    python scripts/fetch_schedule.py

## 📈 Predictions (Coming Soon)
Once trained, the system will use past player stats and situational features to predict performance metrics like:

Home Runs

Total Bases

Hitter Fantasy Score

Pitcher Strikeouts

Hits Allowed

Walks

Earned Runs

And more...

## ✅ Status
 Matchup data retrieval

 Daily schedule fetching

 Machine learning model training

 Stat predictions integration

 Dashboard/Visualization (optional)

 ## )

📌 License
This project is open-source and MIT licensed.

yaml
Copy
Edit
