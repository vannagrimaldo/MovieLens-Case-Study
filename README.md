Problem Statement - MovieLens Case Study
Context
The movie rating system that film buffs know today has been around for over 50 years. Over the years, the cultural standards and norms have changed and so have movie ratings. However, even today the process of rating a film remains a closely guarded industry secret.


Objective
MovieLens is a company in the internet and entertainment domain that has an online database of information related to films, television series, online streaming content – including cast, production crew, trivia, ratings, and fan and critical reviews. You have been hired as a Data Scientist for the company. You have been provided with the following three datasets, asked to carry out a detailed analysis of the data, and come up with some meaningful insights which will help the company to address their users in a better way.

 

Key steps to be performed
Import all the necessary packages
Read all the datasets into pandas dataframes
Get a brief overview of the datasets
Explore the datasets to come up with useful insights

Datasets
1. rating.csv: It contains information on ratings given by the users to a particular movie.

user id: id assigned to every user

movie id: id assigned to every movie

rating: the rating given by the user

timestamp: Time recorded when the user gave a rating

 

2. movie.csv: The file contains information related to the movies and their genre.

movie id: id assigned to every movie

movie title: Title of the movie

release date: Date of release of the movie

Action: Genre containing binary values (1 - for action 0 - not action)

Adventure: Genre containing binary values (1 - for adventure 0 - not adventure)

Animation: Genre containing binary values (1 - for animation 0 - not animation)

Children’s: Genre containing binary values (1 - for children's 0 - not children's)

Comedy: Genre containing binary values (1 - for comedy 0 - not comedy)

Crime: Genre containing binary values (1 - for crime 0 - not crime)

Documentary: Genre containing binary values (1 - for documentary 0 - not documentary)

Drama: Genre containing binary values (1 - for drama 0 - not drama)

Fantasy: Genre containing binary values (1 - for fantasy 0 - not fantasy)

Film-Noir: Genre containing binary values (1 - for film-noir 0 - not film-noir)

Horror: Genre containing binary values (1 - for horror 0 - not horror)

Musical: Genre containing binary values (1 - for musical 0 - not musical)

Mystery: Genre containing binary values (1 - for mystery 0 - not mystery)

Romance: Genre containing binary values (1 - for romance 0 - not romance)

Sci-Fi: Genre containing binary values (1 - for sci-fi 0 - not sci-fi)

Thriller: Genre containing binary values (1 - for thriller 0 - not thriller)

War: Genre containing binary values (1 - for war 0 - not war)

Western: Genre containing binary values (1 - for western - not western)

 

3. user.csv: It contains information about the users who have rated the movies.

user id: id assigned to every user 

age: Age of the user

gender: Gender of the user (M: Male, F: Female)

occupation: Occupation of the user

zip code: Area code for the user's residence 
