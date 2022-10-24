"# Football Prediction Transformer vs LSTM" 


URL TO BLOG
Link einfügen 

## Project Description
   - This Project is about to create a data corpus about german Football
   - It build two Deep Learning models (Transformer and LSTM)
   - Predicted Football results and compare these models

## FILES
## Folder Data:
  - Folder 2016
      - File Daten2016.pkl: Contains all data for the 2016 season
      - File FifaGes16.pkl: Contains all data from Fifa from teams
      - File GES16.pkl: Contains all data from Fifa players from teams
      - Statistik2016.pkl: Contains all data from Statistics
      - Tabelle16.pkl: Contains all Data from Table information
      - Wettquoten2016.pkl: Contains all bet information about the matches
      - Wettquoten2016Neu.pkl: Contains all bet information about the matches from another source
      - Input2016.ipynb: Collect all pkl files and save all inforamtion in one file
  - Folder 2017
      - like Folder 2016
  - Folder 2018
      - like Folder 2016
  - Folder 2019
      - like Folder 2016
  - Folder 2020
      - like Folder 2016
  - Folder All Data
      - contains all pkl Files for each season
  - Folder Bet Quots
      - 11-21.csv: files with bet quotes for each season year
      - Wettquoten2013.pkl-Wettquoten2020Neu.pkl: data in file for each season
      - Korrektur: Correction Notebook to collect all bets
      - Wettquoten: Notebook to create all pkl Files for each season
  - Folder Fifa
      - Fifa12.pkl-Fifa21.pkl: Fifa pkl files for each season
      - GES10.pkl- GES20.pkl: Fifa player inforamtion pkl files for each season for each team for each match
      - Fifa.ipynb: Notebook to collect all Data about Fifa teams
      - GESWerte.iypnb: Notebook to collect all Data about each Fifa player from each team for one season
  - Folder Lineup
      - AufstellungenNeu15.pkl- AufstellungenNeu20.pkl: Lineup.pkl for each season
      - AufstellungenNeu.ipynb: Notebook to collect all Data about Lineups
  - Folder Match days
      - Spiele2013.pkl-Spiele2018.pkl: Match day information for each season as pkl files
      - API:ipynb: Notebook to collect with an API all information
  - Folder Statistic
      -Statistik2014.pkl-Statistik2021.pkl: Statistic pkl Files for each season
      -Statistik.ipynb: Notebook to collect all statistic informationa about each season
 
 
 ## Folder Models:
   - Folder Test:
      - Folder LSTM/LSTM4Saisons/Transformer/Transformer4Seasons: Trained Models
      - Filed LSTMErgebnisse.pkl/LSTM4Ergebnisse.pkl/TransformerErgebnisse-pkl/Transformer4Ergebnisse.pkl: Results from Season 2020 to evaluate 
      - TestLSTM.ipynb: Notebook to test the LSTM model
      - TestTransformer.ipynb: Notebook to test the Transformer model
   - Folder Training:
      - Folder LSTM/LSTM4Saisons/Transformer/Transformer4Seasons: Trained Models
      - Daten2014.pkl-Daten2019.pkl/Daten161718.pkl: Data Inforamtion as pkl File from seasons
      - ConcatMatrices.ipynb: Concat pkl Files to one pkl File
      - LSTM.ipynb: Build and trained LSTM model
      - Trasnformer.ipynb: Build and trained Transformer model 
  
