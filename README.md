# Netflix_Movies_And_Tv_Shows_Clustering

# Problem Statement
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

# Variables Description

1 - Show_id: Unique identifier for each movie/show.

2 - Type: Indicates whether the entry is a movie or a TV show.

3 - Title: Name of the movie or TV show.

4 - Director: Name of the director(s) of the movie or TV show.

5 - Cast: Names of the actors and actresses featured in the movie or TV show.

6 - Country: Country or countries where the movie or TV show was produced.

7 - Date_added: Date when the movie or TV show was added to Netflix.

8 - Release_year: Year when the movie or TV show was released.

9 - Rating: TV rating or movie rating of the movie or TV show.

10 - Duration: Length of the movie or TV show in minutes or seasons.

11 - Listed_in: Categories or genres of the movie or TV show.

12 - Description: Brief synopsis or summary of the movie or TV show.

# Conclusion

 - Netflix boasts a larger collection of movies compared to TV shows within its platform.

- Dramas stand as the predominant genre in Netflix's content library, closely followed by Comedies and Documentaries.

- Since its inception in 2008, Netflix has consistently expanded its content library, showcasing a steady growth trajectory.
- The United States leads in producing content available on Netflix, followed by India and the United Kingdom.
- Employed robust techniques to handle missing data in essential columns like director, cast, country, and rating, ensuring a pristine dataset for analysis. Explored advanced dimensionality reduction methods like Principal Component Analysis (PCA) to effectively condense features while retaining substantial data variance.
- Utilized clustering algorithms like k-means and hierarchical clustering to categorize movies and TV shows based on their unique features. Determined the optimal number of clusters that maximize the silhouette score, unveiling deeper insights into inherent patterns and similarities in the dataset.
- Emphasized the business implications of the model, highlighting its potential to revolutionize content categorization, enhance user experience through personalized recommendations, and facilitate targeted marketing strategies for Netflix's benefit.
