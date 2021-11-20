# Predicting-Gross-Revenue-of-a-Movie

This notebook contains my approach in a Hacakthon on National Level conducted by [NASSCOM FutureSkillsPrime](https://learn.futureskillsprime.in/log_in?auto_sso=true) ```ML HACKFEST 2021``` in [ATHLeaps](https://leapsapp.analyttica.com/hackathons/HACKFEST2021), which is about predicting the next box office hit.

### About the Data :
One can avail the Dataset from ```Dataset.zip``` or from the link [here](https://leapsapp.analyttica.com/hackathons/HACKFEST2021)
##### Data Description:
|Name	| Type | Description|
|-----| ---- | ----|
|movie_ID|	Character|Identification for movies||
|num_critic_for_reviews	|Numeric|	Number of critics reviewed|
|duration|	Numeric|	Duration of the movie (in mins)|
|director_facebook_likes|	Numeric|	Number of likes for director on facebook|
|actor_3_facebook_likes|	Numeric|	Number of likes for Actor on Facebook|
|actor_1_facebook_likes|	Numeric|	Number of likes for Actor on Facebook|
|num_voted_users|	Numeric	|Total number of users voted|
|num_user_for_reviews|	Numeric	|Total number of users reviewed|
|budget|	Numeric|	Budget for the movie (in $)|
|title_year	|Date Time|	Year of release|
|actor_2_facebook_likes|	Numeric|Number of likes for Actor on Facebook|
|movie_rating|	Numeric	|Rating of the movie (1-10)|
|aspect_ratio|	Numeric|	Aspect ratio of movie|
|movie_facebook_likes|	Numeric|	Number of likes for movie on Facebook|
|countries_launched_in|	Numeric	|Number of countries movie launched in|
|content_rating|	Character	|Type of content of movie - R PG PG-13 etc.|
|Picture_Type|	Character|	Color type of movie - Color and Black & White|
|language	|Character	|Language movie was directed in - English French etc.|
|origin_country|	Character|	Region the movie belongs to - USA UK France etc.|
|gross|	Numeric	|Earning of the movie on opening weekend (in $)|

In this notebook I've more focussed on feature engineering, hyperparameter tuning and ensembling predictions of 3 different models i.e, ```XGBoost```, ```CatBoost``` and ```LightGBM``` and I ended up in 18th position in the Hackathon.

### Installation :
1. Download this repo in a zip file by clicking this [link](https://github.com/Naidu-Suraj-Vardhan/Predicting-Gross-Revenue-of-a-Movie/archive/refs/heads/main.zip) or execute this from the terminal: ```git clone https://github.com/Naidu-Suraj-Vardhan/Predicting-Gross-Revenue-of-a-Movie.git ```.
2. Install the [Anaconda Environment](https://anaconda.org/anaconda/anaconda-navigator) .
3. Navigate to the repo directory and create a conda environment. Then install the dependencies with ```pip install -r requirements.txt```.
4. Run the  ```Predicting Gross Revenue of a Movie.ipynb ```.

### Dependencies :
1. Numpy
2. Pandas
3. Scikit-Learn
4. Matplotlib
5. Seaborn
6. Xgboost
7. Lightgbm
8. CatBoost
