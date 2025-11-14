# cricket_predictor_models

🏏 Cricket Match Prediction & Analysis System

A machine learning–based cricket match prediction system built using IPL data (2023–2025). The project predicts match outcomes, analyzes stadium performance, and generates powerful visual insights.

Overview

This project uses historical IPL match data from five major stadiums to predict:

Second innings score

Win probability

Stadium difficulty

Safe target scores

It includes ML models, visualizations, dashboards, and analysis reports for cricket insights.

✨ Features
🔮 Match Prediction

Ensemble Model (Random Forest + Linear Regression)

Predicts second innings score

Win probability estimation

Stadium-specific predictions

Visualization

Score trends

Stadium-wise comparisons

Heatmaps, boxplots & distributions

Year-wise performance (2023–2025)

Stadiums Covered

Chepauk (Chennai)

Wankhede (Mumbai)

Eden Gardens (Kolkata)

Ekana (Lucknow)

Rajiv Gandhi Stadium (Hyderabad)

📂 Dataset Format
Year	First Innings	Second Innings	Stadium

Excel files required:
Chepauk.xlsx, Mumbai.xlsx, Kolkata.xlsx, Lucknow.xlsx, Hyderabad.xlsx

🔧 Installation
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl

Usage
Run Predictor
python cricket_predictor.py

Run Visualizer
python cricket_visualizer.py

Models Used:

Random Forest Regressor

Linear Regression

Ensemble averaging for final score prediction

Project Structure
project/
│-- cricket_predictor.py
│-- cricket_visualizer.py
│-- data/
│-- outputs/
│-- README.md

Example Output

Prediction:

Predicted 2nd Innings: 165

Win Probability: 68.5%

Result: First innings team likely wins

Future Enhancements

Web dashboard

Live data integration

Player-level insights

Weather-based predictions
