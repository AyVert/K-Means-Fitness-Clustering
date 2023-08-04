# K-Means-Fitness-Clustering
This repository contains a Python implementation of K-Means clustering to group individuals based on their fitness levels, ranging from fit to unfit. By utilizing the powerful K-Means algorithm, we aim to efficiently categorize people into distinct clusters according to their fitness attributes.

How It Works

Data Collection: We collected fitness-related data from two sources, average running speed and average heart rate.

Preprocessing: The collected data was processed and prepared for K-Means clustering. We standardized and normalized the features to ensure unbiased clustering.

K-Means Clustering: Our code utilizes the K-Means algorithm to group individuals into clusters based on their similarities in fitness attributes. The algorithm iteratively refines the clustering to achieve the most accurate results.

Multiple Runs for Accuracy: To enhance the reliability of the clustering process, we reran the K-Means algorithm multiple times, randomizing initial centroids each time. This approach helps mitigate the effect of initialization and provides more robust and accurate clustering outcomes.
