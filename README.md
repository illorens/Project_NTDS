# A Network Analysis of Movie Popularity

What can we say about the popularity of a movie based on its characteristics? Can certain actors, directors or story lines attract automatically the attention of the public?
Popularity is defined as the state of being liked, admired or supported by a high number of people. When talking about a movie, it can be measured in several ways, namely how many people went to see the movie on the theaters, the critics' opinion, the movie fans' reviews or the Cinema Authorities' (such as Cannes or the Academy) judgment.

The aim of this project is to analyze several movie features by creating a film network in order to observe which characteristics lead to popularity. First, the movie dataset is used to conduct different regressions using all of the movies' features and different popularity targets. The goal of this regression is to obtain the most significant features using Machine Learning. Then, the relevant features are used to build a network, whose structure is studied to detect the popular movies' characteristics.

In order to reflect as close as possible the presented definition of popularity, four main metrics are considered to define it: the grades assigned by movie critics (Metacritic and Rotten Tomatoes), the users' opinions (IMDb grades), the film's box office and its awards (wins and nominations).


## Prerequisites

Warning: Running the full notebook takes 25 minutes with an average computer.

To run the notebook from the begining, the files tmdb_5000_credits.csv and tmdb_5000_movies.csv need to be downloaded from the git "Data" folder or from original source https://www.kaggle.com/tmdb/tmdb-movie-metadata/data. Then, they need to be placed into a "Data" folder at the same level of the notebook.

Part 1 "Data collecting" does not need to be ran. It can take several days to collect all movies because of the OMDb limit for free accounts. You can run the import cells and go directly to part 2.

The notebook takes inputs from the /Data folder and python scripts which are used as supplemetary functions.

Installations: all packages to be installed can be found on the top of "Analysis.ipynb" notebook (the imports cell).


## Authors

Timothée Borget Dit Vorgeat, Yassine Zouaghi, Icíar Lloréns Jover and Pol Boudou Pérez



