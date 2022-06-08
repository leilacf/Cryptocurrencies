# Cryptocurrencies
## Overview
Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency investment portfolio for its customers. The company, however, is lost in the vast universe of cryptocurrencies. Therefore, they needed assistance to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

The data required cleaning in order to be processed and fit the unsupervised machine learning models. The 4 phases of analysis are detailed below:

- Data pre-processing for PCA
- Reduction of data dimensions using PCA
- Clustering cryptocurrencies using K-means
- Visualizing cryptocurrencies results

## Results
1. Cleaned pre-processing data for PCA
  - Initial Crypto dataframe
  
  ![This is an image](https://github.com/leilacf/Cryptocurrencies/blob/main/Images/1crypto%20df.png)
  
2. Utilized get_dummmies() function 

  ![This is an image](https://github.com/leilacf/Cryptocurrencies/blob/main/Images/2get_dummies.png)
  
  
3. Utilized StandardScaler() to standardize data

![This is an image](https://github.com/leilacf/Cryptocurrencies/blob/main/Images/3standardize%20data.png)

4. Reduced data dimensions by creating a dataframe with (3) principal components

![This is an image](https://github.com/leilacf/Cryptocurrencies/blob/main/Images/4pcs.png)

5. Utilized K-means to cluster cryptocurrencies seen in the Elbow Curve visual 

![This is an image](https://github.com/leilacf/Cryptocurrencies/blob/main/Images/5elbow%20curve.png)

6. Created (2) visuals and one final table to interpret cryptocurrency results

- 3-D Scatter with clusters

![This is an image](https://github.com/leilacf/Cryptocurrencies/blob/main/Images/63d%20cluster.png)

- Hv.plot Scatter Plot

![This is an image](https://github.com/leilacf/Cryptocurrencies/blob/main/Images/8hv%20plot.png)

- Table with all cryptocurrencies

![This is an image](https://github.com/leilacf/Cryptocurrencies/blob/main/Images/7final%20table.png)

## Summary
We were able to predict that there were 532 tradable cryptocurrencies.

