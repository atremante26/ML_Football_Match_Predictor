VIDEO PRESENTATION: https://youtu.be/_78TkQ1djPI

My first Machine Learning Project. This project was built as the final project of my Machine Learning course in Spring 2024. It uses betting odds from Bet365 and William Hill to predict the outcomes of professional football matches. 

Data: I downloaded data from 'https://www.football-data.co.uk/' for the English Premier League, Spanish La Liga, and German Bundesliga from 2002 to 2023. I filtered and wrangled the data in the 'ML_final.qmd' file. I used an ordinal encoder to encode the team names (Home, Away), a MinMax scaler to scale the numeric variables (betting odds), and I added polynomial features. 

Model: I built a CNN with 2 convolutional layers that use pooling and attention. I also used 3 fully connected layers with batch normalization and dropout (50%). I used Adam as my optimizer and Cross Entropy as my loss function. 

I included the model's performance for Premier League games from Matchweek 35 and Matchweek 36 of the 2023-24 season. Using these predictions and betting $5 per game on both betting sites (Bet365, William Hill), these predictions would have yieled an average winnings of $57.34 per week or ~$6 per game. 
