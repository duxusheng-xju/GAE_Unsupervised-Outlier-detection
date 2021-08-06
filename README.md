# GAE_Unsupervised-Outlier-detection
we propose a Graph Autoencoder(GAE)-based outlier detection method. This method first converts the euclidean structure dataset into graph using the graph generation module, then inputs the dataset together with its corresponding graph into the GAE for training, and finally determines the top-n objects that are difficult to reconstruct in the output layer of the GAE as outliers. The results of comparing eight state-of-art algorithms on eight real-world datasets show that, GAE achieves the highest AUC on six datasets. By comparing GAE with the Autoencoder(AE)-based outlier detection algorithm in detail, we found that the proposed method was able to detect outliers that are mixed in the normal object region or around dense clusters, and found that GAE improved the AUC by 16.9% on average on eight datasets.
