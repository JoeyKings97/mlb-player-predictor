# MLB Player Stats Predictor
This project uses machine learning to predict MLB player performance for upcoming games. It analyzes opponent teams, ballpark effects, weather conditions, pitcher-batter matchups, and recent trends to forecast individual player stats such as hits, RBIs, and strikeouts.

## Features
- Real-time MLB data using pybaseball
- Machine learning predictions with scikit-learn and XGBoost
- Weather and ballpark-aware stat forecasting (planned)
- Flask-based web dashboard (in development)

## Technologies Used
Python 3.13, Pandas, NumPy, scikit-learn, XGBoost, pybaseball, Flask, python-dotenv

## Getting Started
1. Clone the repository:  
git clone https://github.com/YOUR_USERNAME/mlb-player-predictor.git  
cd mlb-player-predictor

2. Set up the virtual environment:  
python -m venv venv  
venv\Scripts\activate

3. Install dependencies:  
pip install -r requirements.txt

4. Create a .env file in the root directory with your API keys:  
WEATHER_API_KEY=your_api_key_here

## Example Usage
To fetch player stats for testing:  
python scripts/fetch_data.py

## Roadmap
- Initial data fetch script (done)  
- Add weather and venue factors  
- Build predictive models  
- Create a Flask dashboard  
- Full game simulation and report system

## License
MIT License

## Author
Jose Reyes  
[https://github.com/JoeyKings97](https://github.com/JoeyKings97)
