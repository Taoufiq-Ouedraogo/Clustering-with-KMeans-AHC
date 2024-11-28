# Clustering with KMeans & AHC


<div style="text-align: center;">
  <img src="https://miro.medium.com/v2/resize:fit:1276/1*fREhmVxP-h8xNnTMzu1I1A.png" width="800">
</div>


## Description

This project explores the use of clustering algorithms, specifically **K-Means** and **Agglomerative Hierarchical Clustering (AHC)**, to analyze and group datasets based on their characteristics.

The goal is to demonstrate how these techniques can be effectively applied in various contexts, such as:

- **Customer Segmentation**: Identifying customer groups based on common criteria for targeted marketing strategies.
- **Driver Clustering**: Analyzing driver behaviors for use cases related to speed and distance.


## Contents

- **`Customer-Clustering-with-KMeans-AHC.ipynb`**: A Jupyter notebook dedicated to customer segmentation using K-Means and AHC algorithms.
- **`Driver-Clustering-with-KMeans.ipynb`**: A Jupyter notebook exploring driver clustering using the K-Means algorithm.
- **`data/`**: Contains the datasets used for analysis.


## Objectives

- Understand and apply the fundamental principles of clustering.
- Compare the performance and visualizations of K-Means and AHC algorithms.
- Provide concrete and reproducible examples for real-world scenarios.




<br>

      @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
      @                                                                                @
      @                                                                                @
      @    /$$      /$$                 /$$                                            @
      @   | $$  /$ | $$                | $$                                            @
      @   | $$ /$$$| $$  /$$$$$$       | $$  /$$$$$$  /$$    /$$  /$$$$$$              @
      @   | $$/$$ $$ $$ /$$__  $$      | $$ /$$__  $$|  $$  /$$/ /$$__  $$             @
      @   | $$$$_  $$$$| $$$$$$$$      | $$| $$  \ $$ \  $$/$$/ | $$$$$$$$             @
      @   | $$$/ \  $$$| $$_____/      | $$| $$  | $$  \  $$$/  | $$_____/             @
      @   | $$/   \  $$|  $$$$$$$      | $$|  $$$$$$/   \  $/   |  $$$$$$$             @
      @   |__/     \__/ \_______/      |__/ \______/     \_/     \_______/             @
      @                                                                                @
      @                                                                                @
      @                                                                                @
      @    /$$      /$$                     /$$       /$$                              @
      @   | $$$    /$$$                    | $$      |__/                              @
      @   | $$$$  /$$$$  /$$$$$$   /$$$$$$$| $$$$$$$  /$$ /$$$$$$$   /$$$$$$           @
      @   | $$ $$/$$ $$ |____  $$ /$$_____/| $$__  $$| $$| $$__  $$ /$$__  $$          @
      @   | $$  $$$| $$  /$$$$$$$| $$      | $$  \ $$| $$| $$  \ $$| $$$$$$$$          @
      @   | $$\  $ | $$ /$$__  $$| $$      | $$  | $$| $$| $$  | $$| $$_____/          @
      @   | $$ \/  | $$|  $$$$$$$|  $$$$$$$| $$  | $$| $$| $$  | $$|  $$$$$$$          @
      @   |__/     |__/ \_______/ \_______/|__/  |__/|__/|__/  |__/ \_______/          @
      @                                                                                @
      @                                                                                @
      @                                                                                @
      @    /$$                                               /$$                       @
      @   | $$                                              |__/                       @
      @   | $$        /$$$$$$   /$$$$$$   /$$$$$$  /$$$$$$$  /$$ /$$$$$$$   /$$$$$$    @
      @   | $$       /$$__  $$ |____  $$ /$$__  $$| $$__  $$| $$| $$__  $$ /$$__  $$   @
      @   | $$      | $$$$$$$$  /$$$$$$$| $$  \__/| $$  \ $$| $$| $$  \ $$| $$  \ $$   @
      @   | $$      | $$_____/ /$$__  $$| $$      | $$  | $$| $$| $$  | $$| $$  | $$   @
      @   | $$$$$$$$|  $$$$$$$|  $$$$$$$| $$      | $$  | $$| $$| $$  | $$|  $$$$$$$   @
      @   |________/ \_______/ \_______/|__/      |__/  |__/|__/|__/  |__/ \____  $$   @
      @                                                                    /$$  \ $$   @
      @                                                                   |  $$$$$$/   @
      @                                                                    \______/    @
      @                                                                                @
      @                                                                                @
      @@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@