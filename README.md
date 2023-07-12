# CryptoClustering
# Use Jupyter notebook to cluster then visualize crypto currency market data.

## SetUp

* Create Repository in GitHub.
[CryptoClustering repository](https://github.com/StephWolter/CryptoClustering.git)

* Clone repository to personal computer, then create the folder structure:


            * Resources                     
                * crypto_market_data.csv    # given crypto data                
            * Crypto_Clustering.ipynb       # notebook 
            * README.md

* Examined the brief given on the bootcampspot module challenge #19 page and pulled starter files. 
* Pushed regularly to git repository.

## Initialization
* imported necessary libraries
* read in csv data from **crypto_market_data.csv**
* use "describe" function to examine data
* plotted base data

## Prepare the Data
* normalize data with Standard Scaler
* turned into a dataframe and changed the index to be the coin ids

## Find k based on original data
* create an elbow chart with k being 0-11 
* seems best k is =4

## Cluster Cryptocurrencies with K-means Using the Original Data
* make a market_model K-means model with 4 clusters
* make market predictions using .predict
* make a dataframe out of the predictions
* make a scatter plot with different colors for the clusters

## Optimize Clusters with Principal Component Analysis.
* make a pca model
* show variance
* make into dataframe with the correct coin_id as index

## Find the Best Value for k Using the PCA Data
* make a model similar to before but iwht the PCA data
* graph the elbow curve
* seems k=4 again

## Cluster Cryptocurrencies with K-means Using the PCA Data
* using the same process as before, make model
* make into dataframe iwth correct coin_id as index
* chart




## Wrote out README
* Huzzah!
