# av-trust-emotion-analysis
# Emotion & Trust in Autonomous Vehicles

This project explores how emotional state influences trust in autonomous vehicles (AVs), using both subjective survey data and physiological responses. Developed as part of graduate research at the University of Michigan's IOE Department under Dr. Feng Zhou.

## Project Summary

The study involved 74 participants exposed to video scenarios simulating autonomous vehicle behavior under various conditions:
- **Risk Conditions:** High Risk, Low Risk, and Control
- **Error Conditions:** Automation Error vs. No Error

Data was collected across two streams:
- **Subjective Trust Data** (questionnaires and risk perception surveys)
- **Physiological Data** including:
  - Heart rate (ECG)
  - Electrodermal activity (EDA)
  - Cleaned and grouped by experimental condition

##Analysis Overview

### Subjective Data:
- Analyzed participant ratings of perceived risk and trust
- Compared results across the six scenario groups
- Visualized trends using bar graphs and descriptive stats

### Physiological Data:
- Time-aligned and cleaned EDA and heart rate signals
- Grouped data by **Risk Perception** and **Automation Error**
- Generated:
  - Boxplots with standard error bars
  - Time series plots showing changes in arousal and heart activity

## Files Included

- `emotion_2024_physiological_data.ipynb` — Analysis of heart rate and EDA
- `Emotion_Trust_2024_subjective_data.ipynb` — Analysis of participant surveys

## 🛠 Tools Used

- Python
- Pandas, Seaborn, Matplotlib
- Jupyter Notebook (via Google Colab)

This repository does not contain raw or identifiable participant data. All visualizations are generated from cleaned, anonymized, or synthetic datasets.

