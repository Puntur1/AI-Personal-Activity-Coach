# AI-Personal-Activity-Coach
project of Aliakhmed for IOT 
# AI-Powered Personal Activity Coach

## Overview
An intelligent AIoT system designed to monitor human physical activity and encourage healthier daily habits using time-series wearable motion sensor data (based on the TECO-KIT WHAR dataset schema).

## Project Features
- **Real-Time HAR Classification:** Uses a machine learning Random Forest model to classify sensor streams into *Sitting, Standing, Walking, and Running*.
- **Agentic Decision Mechanism:** Analyzes inactivity duration, tracks daily active-minute goals (60 mins), and autonomously triggers personalized reminders.
- **Adaptive Feedback Loop:** Monitors user response compliance to reset inactivity timers or escalate nudges.

## How to Run the Project
1. Open the project code in [Google Colab](https://colab.research.google.com/).
2. Run the ML Activity Classifier block to train the classifier.
3. Run the Agentic Coach loop to simulate a 4-hour workday sensor stream and view real-time intervention logs.
