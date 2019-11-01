## MovieLens_Recommender


### Overview
In this project, an Alternating Least Squares (ALS) algorithm will be used to predict the ratings for the movies using MovieLens Datasets.

### Alternating Least Squares
ALS will broke user-item matrix into two low rank matrixes, they are user matrix and item matrix. In collaborative filtering,  a small set of latent factors will be trained to predict missing entries in the original user-item matrix. And ALS algorithm learns these latent factors by matrix factorization.  The number of latent factors is also a factor that plays an important role in the training process and have significant impact on the final prediction.

### Data Sets
The dataset (ml-latest.zip) describes 5-star rating and free-text tagging activity from MovieLens, a movie recommendation service. It contains 27753444 ratings and 1108997 tag applications across 58098 movies. These data were created by 283228 users between January 09, 1995 and September 26, 2018. This dataset was generated on September 26, 2018.


#### Alternative notebook

If results are not displayed properly, please use the following link to access the notebook in databricks directly.

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2920224926200870/403038416727539/2577951448549045/latest.html
