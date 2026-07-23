# 🏏 IPL Win Predictor

An AI-powered Cricket Win Predictor that estimates the probability of a team winning an IPL match based on live match conditions, using Machine Learning.

🔗 **Live Demo:** [iplwinpredictor-piltcwys4vvlxvanvhhzd5.streamlit.app](https://iplwinpredictor-piltcwys4vvlxvanvhhzd5.streamlit.app/)

---

## 📖 Overview

This project uses historical IPL match data to train a machine learning model that predicts the win probability of the batting team during the second innings of a match, based on current match situation (score, overs, wickets, target, etc.).

The model is served through an interactive **Streamlit** web app, where users can input live match details and instantly see the predicted win probability for each team.

---

## ✨ Features

- Predicts real-time win probability during the second innings of an IPL match
- Simple, interactive web interface built with Streamlit
- Trained on historical ball-by-ball IPL data
- Instant predictions using a pre-trained ML pipeline

---

## 🗂️ Project Structure

```
IPL_Win_Predictor/
├── app.py                # Streamlit web application
├── matches.csv           # Match-level historical IPL data
├── deliveries.csv        # Ball-by-ball historical IPL data
├── pipe.pkl              # Trained ML model pipeline (serialized)
├── Untitled.ipynb         # Notebook used for data analysis & model training
├── requirements.txt       # Python dependencies
├── setup.sh              # Streamlit deployment setup script
├── procfile               # Process file for deployment
└── .devcontainer/         # Codespaces/devcontainer configuration
```

---

## 🛠️ Tech Stack

- **Python**
- **Pandas** & **NumPy** – data processing
- **scikit-learn** – model building & pipeline
- **Matplotlib** – data visualization
- **Streamlit** – web app framework

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/barkhapandey05/IPL_Win_Predictor.git
   cd IPL_Win_Predictor
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app locally**
   ```bash
   streamlit run app.py
   ```

4. Open the local URL shown in the terminal (usually `http://localhost:8501`) in your browser.

---

## 🚀 Usage

1. Open the app (locally or via the [live demo](https://iplwinpredictor-piltcwys4vvlxvanvhhzd5.streamlit.app/)).
2. Select the batting team, bowling team, and host city.
3. Enter the current match situation: target score, current score, overs completed, and wickets fallen.
4. Click **Predict** to view the win probability for both teams.

---

## 📊 Data

The model is trained on historical IPL data:
- `matches.csv` – season, teams, venue, toss, and match result info
- `deliveries.csv` – ball-by-ball details of every match

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. Feel free to fork the repo and submit a pull request.

## 📄 License

This project currently has no license specified. Feel free to reach out to the repository owner for usage permissions.
