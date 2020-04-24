# IMDb Analysis

## What is IMDb?

- IMDb is an online database of information related to films, television programs, home videos, video games, and streaming content online – including cast, production crew and personal biographies, plot summaries, trivia, fan and critical reviews, and ratings.

## Program Description:

- This program has two versions, which are the following:

    - Version Alpha: This version will only utilize the datasets freely provided by IMDb through "https://datasets.imdbws.com"
        - Sadly these datasets do not contain "Box Office Sales", thus it will be used as a Classifier that will predict the rating of a movie based on the available parameters in the datasets provided.

    - Version Beta: This version will not only utilize the datasets freely provided by IMDb, but will also scrape data from "https://www.imdb.com/" through a python module called "imdb".
        - This version will have access to all the parameters required to create a Neural Network capable of predicting "Box Office Sales" based on the variables available.

## Program Requirements:

- (PENDING)

## Future Feature Engineering:

- Incorporate Dask in order to optimize model.
- Convert the Streamlit interface to a proper web and phone application.
- Incorporate other functions into the application (the following are working ideas):
    - Let user input his/her dataset.
    - Movie comparison (statistical analysis in order to understand why did better than the other).
    - Additionally functionalities will be asked of potential users in order to incorporate.

![meme](http://i.imgflip.com/3w87we.jpg)