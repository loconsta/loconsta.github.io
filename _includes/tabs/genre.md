## Genre
<p align="justify"> As the choice of the genre is a determinant feature to produce a movie, we focus on this characteristic. Many movies are associated to multiple genres, which is illustrated by the co-occurence chord diagram below: </p>

<center>
  {% include images/genre_chord_diag.html %}
</center>

<p align="justify"> For each genre, the lines looping on themselves represent the appearance of the genre alone, while the lines linking to other genre represent their co-occurence. Everything is normalized by the total amount of movie genre associations. The button allows to increase the threshold of min co-occurrences to keep when building the diagram, allowing to visualize it at different resolutions. </p>

Some information resides in genre associations, but most of it still resides in individual genres.

<p align="justify"> For the rest of the analysis, we counted each movie in each of its associated genres. In the next plot we give an idea of the different genres present in the data set. We remark that drama, documentary and comedy movies are extremely present compared to other categories such as thriller movies. </p>

<center>
  {% include images/overall_genre_distr.html %}
</center>

<br>

As we are interested in the rating, the budget and the revenue variables, we have explored each of them for each genre:
  
<br>

<p align="center">
  <img src="images/RRB_genre_CIs.png" />
</p>
  
<br>

<p align="justify"> From these representations we remark that genres with highest rating are in order: biography, western and war. Documentaries have the lowest budget and revenue but are well graded. In addition, western and war movies generate high revenue and are well graded. On the other hand, the adventure category shows the highest revenue and budget but is not particularly well rated.</p>

<p align="justify"> Another value which would be interesting to look at is what we can call rentability: the ratio between revenue and budget. In fact a high revenue alone does not tell us a lot of information, it is better to understand how many times the revenue is bigger that the budget. Below we have the figure displaying the rentability in log scale. Documentaries have the highest ratio, followed by horror films, while animation categories have the lowest. </p>
    
<center>
  {% include images/median_rentability_by_genre.html %}
</center>

<br>
<p align="justify"> The take home message from the above plots is that you should avoid animation. Instead, you should focus on documentaries (high rentability and well graded). To a lesser extend western movies are well rated and have medium rentability. Horror movies have high rentability but low ratings. Biography and war movies are not as rentable as documentaries although they are very well rated.</p>
  
<p align="justify">Until now, the analyses have covered the entire time period from 1959 to 2021. To better understand our period, we analyzed the genre's evolution over time. A general decrease in rating score was perceived in a first analysis. However, is it the case for all movie’s genre? The movies has been divided into two periods, with 2000 as the cut-off point, when an increase in the number of movies is observed. The next figure reports the results on rating, revenue and budget, before and after the cut-off.</p>

<br>
<p align="center">
  <img src="images/old_recent_CIs.png" />
</p>
<br>
<p align="justify"> Concerning the rating and the revenue, the trend is similar for all genres: the ratings are decreasing (except for action movies), and no movies show a significant increase in their revenue. Science fiction, adventure, and action movies show a significant increase in budget, whereas romance and drama movies undergo a significant decrease in their budget. Thus, a significant increase in budget does not reflect a significant increase in revenue. In the second period, it seems harder to create movies as good as in the past, which could be due to the increasing competition.</p>




