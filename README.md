# Cryptocurrencies - An Upsupervised Machine Learning Analysis

## Overview
Using unsupervised machine learning analysis techique, we will attempt to classify a database of 1,252 cryptocurrencies.

## Process
We first performing the ETL (Extract, Transform, Load) process on the [raw cryptocurrencies dataset.](crypto_data.csv)

**Raw Cryptocurrencies Dataset**
<img src = 'images/crypto_data.JPG'>

We then apply the PCA data processing technique followed by the K-Means method to determine 4 clusters as the optimal grouping choice.

<img src = 'images/KmeansElbow.JPG'>


## Visualization

We demonstrates two ways to display the four grouping of resulting 533 cryptocurrencies.

**3D-PCA** <br>
Four clusters of cryptocurrencies using the three PCA dimensions in our analysis<br>

<img src = 'images/PCA_clusters.JPG'>
<br>


**Supply and Minned**<br>
Four clusters of cryptocurrencies ploted in relationship to their total supply and total mined <br>

<img src = 'images/PCA_cluster_supply&mined_visual.JPG'>



