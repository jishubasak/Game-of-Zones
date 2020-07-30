# Newage Betting Adoption - Data driven betting on NBA Players
Authors: Jeddahlyn Gacera, Jishu Basak
## 1. Executive Summary/Synopsis. 

#### Introduction : National Basketball Association
The National Basketball Association, or NBA, is a professional basketball league comprised of 30 teams across North America featuring the best basketball players in the world broken down by two conferences with three divisions apiece. The Western Conference plays host to the Northwest, Pacific and Southwest Divisions. It was founded on June 6, 1946 at the Commodore Hotel in New York City. Maurice Podoloff was the league's first president, a title later changed to commissioner. Eleven teams were part of that league, originally called the Basketball Association of America.

#### Betting scenario in Sports industry
It is true that bookies do not gamble more than other businessmen. If they are competent they set the odd so that there is close-to-even exposure on both sides, so that it does not matter who wins in the long run, their pay-out is the same and they make their safely money on the vigorish. Averaging over time allows adjustment of imperfections in the odds setting. Its all about making the most money possible in a predictable way.

But book making is not an instantaneous frictionless process. Bookies make mistakes, which will cost them. They will pay-out too much and thus not make what they expect on the vig. They will make it up in time, but a loss is a loss.

In this lab project, we aim to illustrate how the sports gambling industry specific who gamble on NBA players can benifit from data-driven sports betting and make their odds better by eliminating their options of bad bets thereby reducing the amount of mistakes that they would make.

#### Problem Statement: 
If we were to bet on specific players that are super efficient during the last portion of the NBA game, how can we make our odds better? Our project aims to find out specific players out of 702 active NBA players that have been known to efficiently perform during the last minutes of the game. In a nutshell:

<b>`Betting Problem:`</b> Which player should a gambler/bookies should bet on during 4th quarter and Over Time quarter that have higher chances to make shoot from different regions explained later.

#### Methodology Synopsis:
We will use a popular unsupervised learning algorithm known as ```KMeans``` with a hope to find appropriate clusters that should help address our conundrum and define genres of players based on that. K-means clustering is a type of unsupervised learning, which is used when you have unlabeled data (i.e., data without defined categories or groups). The goal of this algorithm is to find groups in the data, with the number of groups represented by the variable K. The algorithm works iteratively to assign each data point to one of K groups based on the features that are provided. Data points are clustered based on feature similarity. 
But before Kmeans, we will also grind our processed data through a popular Dimensionality Reduction Technique known as Principal Component Analysis, which is a technique used for identification of a smaller number of uncorrelated variables known as principal components from a larger set of data. 

For Data Wrangling and Manipulation, we will use text manipulation techniques like Regex and String Manipulation, data manipulation tools from Pandas and data visualizations from seaborn, wordcloud and matplotlib.

#### Process Flow:

1. Data Scraping from Basketball Reference specific to shooting data.
2. Data Storage in SQLite database
3. Data Extraction and loading into pandas dataframe
4. Cleaning and Manipulating Data
5. Exploratory Data Analysis, including nearest K to find prelimnary similarity on aggregated data.
6. Dimensionality Reduction on processed data
7. KMeans Clustering: Indentifying clusters,computing SSE and Inertia validation metrics, building wordcloud visualization based on number of clusters
8. Results and Conclusion

To view the project, explore the jupyter notebook/ HTML file
