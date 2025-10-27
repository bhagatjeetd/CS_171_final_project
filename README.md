# CS_171_final_project
**Project Title**
Predicting Soccer Match Outcomes and Player Performance using Event-Level and Transfermarkt Data

**Authors**: Bhagatjeet Dhillon (bhagatjeetd) and HetavVyas

**Description of Question and Research Topic (5 Sentences)**<br>
Our project investigates how individual player actions and team event patterns influence match outcomes and player market values. Using the Soccer Match Event Dataset, we will analyze detailed in-game events (passes, shots, fouls, substitutions, etc.) to uncover trends that correlate with winning or losing outcomes. Complementing this, the Football Data from Transfermarkt dataset provides player-level statistics, ratings, and market values that allow us to evaluate long-term performance and consistency. Together, we aim to identify which match-level actions are most predictive of success and how these translate into player valuation. This project uses game event data and player statistics to build simple machine learning models that show how on-field performance affects a player’s market value.

**Project Outline/Plan**

**Data Collection Plan (two parts, one for each author)**

**bhagatjeetd** - https://www.kaggle.com/datasets/davidcariboo/player-scores

**HetavVyas**<br>
Dataset: Soccer Match Event Dataset (https://www.kaggle.com/datasets/aleespinosa/soccer-match-event-dataset)<br>
Tasks: Load and preprocess CSV files for matches, events, and players; handle missing values and normalize categorical columns.<br>
Focus: Build match-level feature sets — passes per minute, possession ratios, total shots, defensive actions — to create predictive inputs for outcome models.<br>
Tools: Python (Pandas, NumPy), Matplotlib/Seaborn, Scikit-learn.

**Model Plans (two parts, one for each author)**

**bhagatjeetd** - Multiple Linear Regression

**Hetav (Event Dataset):**<br>
Goal: Predict match result (Win/Draw/Loss) from in-game event data.  <br>
Models: Logistic Regression, Random Forest, and Multi-Layer Perceptron.  <br>
Evaluation: Accuracy, Precision-Recall, and Confusion Matrix on test data.  <br>
Visualization: Event-type influence (e.g., shots vs. passes vs. fouls) on match outcomes.  

**Project Timeline**
We plan to clean and preprocess our datasets, build and train our models, and then analyze and visualize the results, finishing with our presentation in Week 16. Each week will focus on a key stage-data prep, modeling, evaluation, and final reporting.
