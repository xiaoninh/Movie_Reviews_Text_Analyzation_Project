# Movie Reviews Text Analyzation Project
### Partner : Junjie Tsai
### Objectives: 
####     1. Practice using web crawler to craw movie review data from Rotten Tomatoes; 
####     2. Conducts text analyzation on movie reviews (transform text data to feature vectors, conduct sentiment analysis, etc.);
####     3.Focuses on the superhero movies from Marvel and DC, to train machine learning models on the review data to predict which production companies the movie came from.

## Movie List: 
- [Movielist_DC.csv](https://github.com/xiaoninh/Movie_Reviews_Text_Analyzation_Project/blob/master/Movielist_DC.csv): Names and rottentomatoes links of 46 DC movies.
- [Movielist_Marvel.csv](https://github.com/xiaoninh/Movie_Reviews_Text_Analyzation_Project/blob/master/Movielist_Marvel.csv): Names and rottentomatoes links of 21 Marvel movies.

## Movie Basic Info: 
- [BasicInfo_DC.csv](https://github.com/xiaoninh/Movie_Reviews_Text_Analyzation_Project/blob/master/BasicInfo_DC.csv): Basic information of 46 DC movies: names, rottentomatoes links, critics consensus, critical score, audience score, count of critical reviews, count of audience reviews, movie abstract, Rating, Genre, Directed By, Written By, In Theater Date, On Disc Streaming Date, Box Office, Runtime, Studio.
- [BasicInfo_Marvel.csv](https://github.com/xiaoninh/Movie_Reviews_Text_Analyzation_Project/blob/master/BasicInfo_Marvel.csv): Basic information of 21 Marvel movies: names, rottentomatoes links, critics consensus, critical score, audience score, count of critical reviews, count of audience reviews, movie abstract, Rating, Genre, Directed By, Written By, In Theater Date, On Disc Streaming Date, Box Office, Runtime, Studio.

## Movie Review Data: 
- [Reviews_DC.csv](https://github.com/xiaoninh/Movie_Reviews_Text_Analyzation_Project/blob/master/Reviews_DC.csv): 40385 reviews for 46 DC movies; every review has the star and date infomation.
- [Reviews_Marvel.csv](https://github.com/xiaoninh/Movie_Reviews_Text_Analyzation_Project/blob/master/Reviews_Marvel.csv): 1186 reviews for 21 Marvel movies; every review has the star and date infomation.

## Movie Review Data: 
-[preliminary%20analysis]( https://github.com/xiaoninh/Movie_Reviews_Text_Analyzation_Project/blob/master/preliminary%20analysis.ipynb)

**To be noticed:**
- For each movie on rottentomatoes.com, maximum 51 pages (about 1000 comments) of audience reviews are available.
- Some movie have reviews less than 1000. Do we exclude them?
- Star 0 represents missing star data.
