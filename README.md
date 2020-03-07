# Movies-ETL
Extract, transform and Load to understand the movie’s preferences.

## Project overview
Support Amazing Prime Video for streaming movies and tv shows on Amazing Prime
– the world largest online retailer to develop an algorithm to predict which low budget movies being released will become popular.

## Resources
Data source: a scrape of wikepedia from all movies released since 1990, and rating data from the Movie Land’ website
Software: Jupyter Notebook and pgAdmin

## Summary

The analysis of the ETL Movies  database started with understanding the different datasets available for the analysis and which table could provide the information required. 

Those data sets had a lot of data issues and some cleaning were required: different titles in different language, Tv shows in place of movies, columns with less than 90% filled, etc

It was possible to combine the data sources to create one table with title of the movie and their ratings. 

## Assumptions

1)	From the analysis we can make an assumption that the movies with the best reviews were The Million Dollar hotel, Terminator 3, Sleepless in Seattle, License to Wed, Men in Black II
2)	The budget for the best reviews movies were between $ 8,000,000 - $ 200,000,000
- ![alt text](https://github.com/DaniGio/Movies-ETL/blob/master/5%20rating.png)

3)	Movies with worst score reviews: Syriana; Monster, Inc.; Mrs Doubtfire; Mr.Holland’s Opus, and Star Trek: Generations
4)	The budget for worst score reviews movies were between $25,000,000 – $115,000,000
- ![alt text](https://github.com/DaniGio/Movies-ETL/blob/master/0_5%20rating.png)

5)	It would be interesting to bring more data source to a better understanding on the relationship with budget , since the information is not 100% accurate and with some NAN, as bellow
- ![alt text](https://github.com/DaniGio/Movies-ETL/blob/master/Budget.png)


