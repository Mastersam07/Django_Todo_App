# ScorePredictionRep

## Synopsis

This project is targeting on how to predict European league football match results based on the history data of teams,matches,bet-odds by using machine learning algorithms

## Some talk

**Originally serving a webapp via pipelines, project has been taken down for improvement.**


## Cloning

1) Downlaod the data.zip file from (see readme)
2) Export it in and keep the data directory in same directory as src(very important)
3) Project structure in readme

## Code  
### src
#### application 
>Crawlers, exceptions and ML algorithms   
### gui
>UI, customized the input parameters 
### test
>Test code - no gui - just call scripts with different algoritms
### util
>common / helper functions
### main.py 
>entry point.

#### Running main.py
main.py --no-crawl --no-index -v

--no-crawl :  for not crawling the website and update the SQLLite

--no-index :  for indexing the Italy league

-v        :  for the debug 


## API Reference

[Scikit-learn](http://scikit-learn.org/stable/modules/classes.html)

#### ALgorithms: 
[K-NearestNeighbourhood](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)

[SVM-MultiClassifier](https://en.wikipedia.org/wiki/Support_vector_machine)

[RandomForest](https://en.wikipedia.org/wiki/Random_forest)

[Possion](https://en.wikipedia.org/wiki/Poisson_distribution)



## Contributors
Mastersam

Tosin

Others

## Key Instructoions:  
Mastersam - Algorithms

Tosin - Crawling

Others - test and gui

Please note that M and T can make a PR anywhere but no one is to make a PR to their sections.

# Reference
## Papers
[A Comparison of Methods for Predicting Football Matches, David B. Ekefre ](http://liacs.leidenuniv.nl/assets/Masterscripties/ICTiB/2015-2016/Ekefre-non-confidential.pdf)

[Predicting Soccer Match Results in the English Premier League, Ben Ulmer, Matthew Fernandez](http://cs229.stanford.edu/proj2014/Ben%20Ulmer,%20Matt%20Fernandez,%20Predicting%20Soccer%20Results%20in%20the%20English%20Premier%20League.pdf)

[Modelling Association Footbal Scores and Inefficiencies in the Football Betting Market, Dixon and Coles](http://www.math.ku.dk/~rolf/teaching/thesis/DixonColes.pdf)


Ensure your code is short and concise.
