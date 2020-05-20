# Anime-recommendation

# Dataset:

The dataset that selected contains information on use preference data from 73,516 users on 12,294 animations.The dataset consists of features like user id, anime id, name, genre, type, episodes, rating and members.User id and anime id are the primary keys which are used to identify the features uniquely and merge different dataset based on these attributes.

# Architecture:

As recommendation can be built considering variety of features at first step we selected which attributes are essential for the recommendation model we are building.
We built a model based on the correlation to that feature in the dataset.(Genre,episodes,rating)

# Semantic analysis - limitation

We have done partial semantic analysis for our data where we tried to recommend the shows based on the similarity in the semantics of the names and based on same type, genre.
This method of semantic analysis is very much useful for extracting and representing the contextual meaning of words by statistical computations applied to a large corpus of text.

The limitation is that we need to have data that is being related or having some pattern to identify the relationship which in our scenario it is limited to few of the shows that vary with the other features like genre, type but yet provided some other information like description and the people who casted it etc. can help to develop a model by conducting different analysis.

Semantic analysis is more helpful to recommend the shows based on the names and it is more useful to recommend the shows by mapping with the partition as partial names  and similarity within the names.

# Challenges and lessons Learned:

Applying different techniques to handle NULL values of each column based upon the correlation of the attributes.
How to define like (considering the users who viewed each anime and who rated them) based on user rating ,anime rating and on a condition that user rating for an anime is more than the mean rating.
Finding the best value of  ‘K’ in K-means clustering based on inertia and silhouette score.
Calculating the distance between the categorical variables using Binary Euclidean Distance, coefficient of similarity and Hamming distance.
Using clustering technique for recommending the shows.
Using supervised modeling technique to an unsupervised data (KNN).  
Using semantic analysis technique for recommending various shows.

