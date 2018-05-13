---
layout: post
title:      "Enter your title here"
date:       2018-05-13 18:45:24 -0400
permalink:  formatted_like_this
---

CLI Data Gem Project


I should start off by acknowledging that I was overwhelmed and intimidated by the CLI Gem Project.  However I overcame it after watching Avi's videos on how he created a CLI gem one step at a time.  After following Avi's instructions everything started to fall in place.  The fear waned and I gained my confidence back. 

I started my project few weeks ago and had a challenging time scraping a web site and was unable to successfully extract data.  Looking back on it now I feel it was due largely in part  to the fact that I was not selecting the correct selector. When making a selector choice for iterating you must ensure that you select right nodeset otherwise you will not be able to select all rows or it may give nil:NilClass (NoMethodError). If some how the data that you are trying to extract is missing. It took me a while to figure this one out. I had to display selected rows when I checked out the last row, I was able to figure out the cause; my slector choice was not right; I fixed my selector and the issue was resolved.

My project is called top_movies_of_the_year. Top_movies_of_the_year is a CLI interface app that lists the top movies from the Cinema Clock website(https://www.cinemaclock.com/movies/top-10). The user starts the app, the app will  lists the top movies, then it  allows the user to select a movie to get more information about the movie such a overview of the synopsis. The user is allowed to list top movies again by typing "list" or the user can type "exit" to quit or view detail about same or another movie.
