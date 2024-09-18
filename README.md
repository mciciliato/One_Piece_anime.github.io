# One Piece Anime Reviews

## The project
This project’s goal was to analyze IMDb reviews for the One Piece anime and the series duration. </br>

One Piece is a series with over 1100 manga volumes and as many anime episodes. I’m passionate about the world-building and the history Eiichiro Oda created. Hence, I’m evaluating the least and most liked episodes and arcs from an anime perspective.</br>

Furthermore, this project aims to explain to any soon-to-be One Piece fan how long this life-changing journey would take.</br>

## Data processing
Kaggle has many fantastic databases for One Piece fans to work on but [One Piece IMDb ratings](https://www.kaggle.com/datasets/greninja1729/one-piece-imdb-ratings-and-votes) has the episodes' numbers, English name, rating, votes, and duration which made it perfect to start this project with.</br>

Nevertheless, the database wasn't complete. There were 901 episodes without their specified duration. To solve that, the standard duration of 25 minutes was defined for unspecified episodes.

Originally, the episodes were classified into four types: 'Anime Canon', 'Filler', 'Manga Canon', and 'Mixed Canon/Filler'. Since those classifications aren't simple enough for the user to understand, 'Anime Canon' and 'Filler' were transformed into 'Filler' while 'Manga Canon' and 'Mixed Canon/Filler' became 'Canon'.</br>

The selected database doesn't comprehend the newest anime releases but it was sufficient to conclude the desired analysis.</br>

## Results
The analysis shows that One Piece has many episodes close to perfect - or grade 10 - and it is a really long series.</br>

There are four episodes tied for first place with 9.8 grades, and two of them are from the top 1 arc in history, the Marineford Arc. The episodes and arcs at the lists' bottom are - unsurprisingly - fillers.</br>

One Piece's arcs grew larger as the time progressed but it is outstanding that the Wano Country Arc - which was segmented into three parts - comprises almost 25% of the whole series. That being the case, one person would take more than 78 hours to watch it fully while skipping the fillers. The full series - including fillers - would take more than 19 straight days of watch time.</br>

A natural progression for this analysis would be to evaluate the manga in comparison with the anime considering: public rating and duration but such a database doesn't exist yet.</br>

## Main challenges
The expected visualization required the user to filter between 'best', 'worst', and 'Canon or Filler' episodes/arcs. Therefore, the most challenging part was creating and ranking the episode groups which required the creation of boolean variables and parameters.</br>

Ultimately, creating donut charts isn't simple in Tableau because one must build two independent pie charts and basically omit the second. Still, it is possible to use the donut chart as a filter even if the central hole becomes invisible once filtered </br>

## Toolkits
Softwares: Tableau, Deepnote (SQL) and Microsoft Excel.</br>

Database: [One Piece IMDb ratings](https://www.kaggle.com/datasets/greninja1729/one-piece-imdb-ratings-and-votes).</br>
