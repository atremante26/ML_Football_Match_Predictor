VIDEO PRESENTATION: https://youtu.be/_78TkQ1djPI

This project was developed as the final project for my Machine Learning course in Spring 2024. It aims to predict the outcomes of professional football matches using betting odds from Bet365 and William Hill.

Data: I obtained data from 'https://www.football-data.co.uk/' for the English Premier League, Spanish La Liga, and German Bundesliga, spanning from 2002 to 2023. The data was filtered and processed in the 'ML_final.qmd' file. Key preprocessing steps included:

- Encoding team names (Home, Away) using an ordinal encoder.
- Scaling numeric variables (betting odds) with a MinMax scaler.
- Adding polynomial features to enhance model performance.
  
Model: I designed a Convolutional Neural Network (CNN) with the following architecture:

- 2 convolutional layers with pooling and attention mechanisms.
- 3 fully connected layers with batch normalization and 50% dropout.
- Adam optimizer and Cross Entropy loss function.
  
Results: The model's performance was evaluated on Premier League games from Matchweek 35 and Matchweek 36 of the 2023-24 season. Betting $5 per game on both Bet365 and William Hill, the model's predictions yielded an average weekly profit of $57.34, or approximately $6 per game.
