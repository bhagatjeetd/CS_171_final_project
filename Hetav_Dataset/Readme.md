Dataset Description
===================

This project uses match-event data from the Soccer Match Event Dataset (Wyscout format). 
All raw files are stored locally using:

DATA_DIR = "/Users/hetavvyas/Downloads/Project_Data"

The main data sources loaded in the preprocessing notebook are:
- events_eng  = pd.read_csv(f"{DATA_DIR}/events_England.csv")
- matches_eng = pd.read_csv(f"{DATA_DIR}/matches_England.csv")
- teams       = pd.read_csv(f"{DATA_DIR}/teams.csv")


Raw Files Used
--------------

- events_England.csv — detailed play-by-play event logs (passes, shots, tackles, fouls, etc.)
- matches_England.csv — match metadata (teams, scores, season, competition)
- teams.csv — team names, IDs, and attributes

These files form the foundation for generating match-level features.


Feature Dataset Created
-----------------------

During preprocessing, the raw datasets were combined and transformed into a clean, aggregated match-level dataset:

match_features_England_basic.csv

This file contains engineered features used by both the Random Forest and MLP models. 
It includes:

- Total passes, shots, clearances, tackles
- Shot accuracy and pass success rate
- Possession indicators
- Attack and defensive metrics
- Relative (team vs opponent) statistics
- Additional engineered features for improved model performance

I couldn't upload events_England.csv due to file size limits, but it is available on the original dataset website, and only the processed file match_features_England_basic.csv is needed to run the models.

This preprocessed dataset is the final input for all machine learning models in the project.

