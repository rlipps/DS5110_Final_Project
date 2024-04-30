# DS5110 Final Project:

## Comparing Machine Learning Algorithms Across Data Systems

### Contributors:
Grace Davenport, Silas Hayes, Hayden French, and Ryan Lipps

### Abstract
This project explores the potential of various data systems for implementing machine learning algorithms, focusing on their performance in terms of speed and scalability. With a particular interest in decreasing compute time for machine learning tasks, we compare the efficacy of two data systems–Dask and Spark–in deploying three common algorithms: Linear Regression, Logistic Regression, and K-Means. The experimental setup involves deploying four EC2 t3.large instances, each with 2 CPUs and 8GB of RAM, and running the algorithms separately on each system. We consider speed and scalability in our comparison of these two systems. We find that Dask has lower runtimes than Spark across all algorithms for up to 2 GBs of data but the systems differ in their scalability. This project aims to provide quantitative insights into the trade-offs between different distributed computing systems, thereby enhancing understanding of their strengths and weaknesses.

### Link to dataset:
https://www.kaggle.com/datasets/dilwong/flightprices

We subset and clean this data further in code/notebooks/...
