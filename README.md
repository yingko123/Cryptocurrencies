# Cryptocurrencies - An Upsupervised Machine Learning Analysis <br>



## Overview
Using unsupervised machine learning analysis techique, we will classify and visualized a database of 1,252 cryptocurrencies.<br>
<br>


## Process
We first performing the ETL (Extract, Transform, Load) process on the [raw cryptocurrencies dataset.](crypto_data.csv)<br>

**Raw Cryptocurrencies Dataset**<br>

<img src = 'images/crypto_data.JPG' width=400px>
<br>

We then apply the PCA data processing technique followed by the K-Means method to determine 4 clusters as the optimal grouping choice.<br>


<img src = 'images/KmeansElbow.JPG' width=400px>

## Visualization

We demonstrate two ways to visualized the four grouping of the resulting 533 cryptocurrencies.

**3D-PCA** <br>
Four clusters of cryptocurrencies plotted against the three PCA dimensions we used in our analysis<br>

<img src = 'images/PCA_clusters.JPG' width=400px>
<br>


**Supply and Mined**<br>
Four clusters of cryptocurrencies ploted in relationship to their total supply and total mined numbers <br>

<img src = 'images/PCA_cluster_supply&mined_visual.JPG' width=400px>



