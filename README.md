# Machine-Learning-Iris-Data

<p align="center"><img src="https://i.imgur.com/w1lItTL.png"></p>

# Project Introduction
- Use K-Nearest Neighbor (KNN) algorithm to classify the species of Iris flowers with measurements of the flower characteristics
- Machine learning process includes data exploration, data preparation, modeling and model evaluation
- LINK: https://github.com/nguoren/BCG-Machine-Learning-Iris-Data/blob/main/DigitalBCG%20Academy%20-%20Machine%20Learning%20-%20K-Nearest%20Neighbour%20(KNN)%20-%20Iris%20Data%20Set.ipynb

## Introduction to Iris Data Set
- The first publication of this famous data set in the history of statistics was made by pioneering statistician, Ronald A Fisher, in 1936
- He proposed an algorithm to classify the species of iris flowers from the measurements of their physical characteristics
- There are 3 species of Iris flower: Setosa, Versicolor and Virginica
- The 4 physical characteristics are: Sepal and Petal lengths and widths, which will be used as the features in the machine learning model to predict the species of the Iris flowers
- There are a total of 150 samples with 50 samples for each flower species

## Insights Gathered
1. Setosa are found to have 0.1cm <= Petal_Width <= 0.6cm, and 1.0cm <= Petal_Length < 2.0cm
2. At Petal_Width of 1.4cm and 1.5cm, species of Versicolor and Virginica can be found, but the distinction is that Virginica has larger Petal_Length of 5.0cm or more
3. As the Petal_Width increases to 1.6cm, there is overlap of the data points for Versicolor and Virginica. However, this is only limited to the range of 1.6cm <= Petal_Width <= 1.7cm, and 4.5cm <= Petal_Length <= 5.8cm
4. Setosa is the species that is the easiest to identify with 2.3cm <= Sepal_Width <= 4.4cm, and 4.3cm <= Sepal_Length <= 5.8cm
5. There are multiple overlapping of data points for species Versicolor and Virginica within the range of 2.5cm <= Sepal_Width <= 3.2cm, and 4.9cm <= Sepal_Length <= 7.0cm, which makes it difficult to identify between these 2 species

## KNN Model
- K = 3 model used
- Model accuracy: 96%
