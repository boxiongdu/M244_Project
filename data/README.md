**Data**

We used Steam Games Dataset for our project, which is collected in 2023 via Steam API and Steam Spy, then uploaded to Kaggle. The original dataset in games.csv.zip contains 96509 observations and 39 variables. After data wrangling and transformation, there are 9 variables and 15010 observations left in games_cleaned.csv.

| Variable Name   | Type      | Description                              | Example                          |
|-----------------|-----------|------------------------------------------|----------------------------------|
| Name            | String    | Game name                                | 'WARSAW', 'Royal Battleships'    |
| Release Year    | Categorical | Release year                           | 2014, 2019                      |
| Price           | Numerical | Original price in USD                   | 3.99, 24.99                     |
| Compatible Systems | Categorical | Compatibility with how many operating systems | 1(Windows only), 2(Windows and macOS), 3(Windows, macOS, linux) |
| Publishers      | String    | Name of the game publishers              | 'Educational Games'             |
| Genres          | Categorical | Broad game genres                      | 'Action', 'Strategy'            |
| Positive Rate   | Numerical | Positive Review Rate                    | 0.833, 0.615                    |
| Estimated Owners | Categorical | Number of users owned the game        | 50000-100000, 100000-200000     |
| Median Playtime Forever | Numerical | Median playtime by all owners in minutes | 782, 93                      |
| Peak CCU        | Numerical | Peak concurrent players online          | 0, 5, 10                       |
