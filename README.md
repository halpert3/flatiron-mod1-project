# README

# Overview



Created for a data science course with Flatiron School, the idea behind this project was to take the role as an advisor to Microsoft as it was launching a new movie studio, and it was the task of my partner and me to make recommendations to the executive team. 



# Process and Tools

Data for our analysis came from sources such as the Internet Movie Database (IMDB), The Movie Database (TMDB), and Box Office Mojo. We used Python and the Pandas and Seaborn libraries for our analysis and visualizations.

In my role of consultant to this new studio, I decided to focus my analysis on high-level recommendations about genres in the United States market. I figured once the studio understood what sorts of films it generally wanted to make, it could make more granular decisions after. Meanwhile, my project partner focused on financial considerations. 

# Findings

Based on popularity, enthusiasm, profitability, and annual trends, Microsoft should focus most on developing movies in the following genres:

- Action
- Adventure
- Fantasy
- Comedy

To achieve the highest likely returns on investment, the studio should expect to spend between $100 and $200 million per film.  

The following are some important findings that I focused on. The full report can be found [here] (https://docs.google.com/presentation/d/1vzF2EhyMntMOL69ZyCw19nTMdsNGa1JBQ2zpAdBpQPw/edit?usp=sharing).

## Popularity

I looked at individual films in TMDB and grouped them by genre. I found that the top seven popular genres are:

1. Adventure
2. Science Fiction
3. War
4. Fantasy
5. Action
6. Animation
7. Family

Popularity is a proprietary TMDB metric. 

## Enthusiasm

I used individual film data in IMDB to find genres with the most enthusiastic fans.

Enthusiasm is a metric engineered for this report. It plots the number of user-submitted votes for films in a genre against the total number films made in that genre. 

The top seven genres with the most enthusiastic fans are:

1. Adventure
2. Action
3. Comedy
4. Crime
5. Biography
6. Horror
7. Romance



## Annual Trends in Movie Genres

I looked at the total quantity of movies made per year from 2010 - 2019 (the years provided by IMDB) and checked them against the quantities of movies within a genre that were made per year. That way, I determined the percentage of films in each genre made per year and can see overall trends of what genres are in favor (or in disfavor) in the industry. 

**Genres with rising trends**:

- Action
- Adventure
- Fantasy
- Thriller
- War

**Genres with falling trends**:

- Documentary
- Family
- History
- Horror
- Musical

