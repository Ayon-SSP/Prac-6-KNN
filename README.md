# Python Implementation of K-Nearest Neighbours (kNN) Algorithm

K-Nearest Neighbours is considered to be one of the most intuitive machine learning algorithms since it is simple to understand and explain. Additionally, it is quite convenient to demonstrate how everything goes visually. However, the kNN algorithm is still a common and very useful algorithm to use for a large variety of classification problems. If you are new to machine learning, make sure you test yourself on an understanding of both of this simple yet wonderful algorithm.

> Read more on Medium: [https://medium.com/@chingisoinar/k-nearest-neighbours-knn-algorithm-common-questions-and-python-implementation-14377e45b738?source=friends_link&sk=0bf0afd4bf4b8f5cb1072c5cbc97ebfd](https://medium.com/@chingisoinar/k-nearest-neighbours-knn-algorithm-common-questions-and-python-implementation-14377e45b738?source=friends_link&sk=0bf0afd4bf4b8f5cb1072c5cbc97ebfd)

# About

Here is a Python implementation of the K-Nearest Neighbours algorithm. 

It is important to note that there is a large variety of options to choose as a metric; however, I want to use Euclidean Distance as an example. It is the most common metric used to calculate distances among vectors since it is straightforward and easy to explain.

Let’s compare our implementation with the one provided by scikit learn. I am going to use a simple toy dataset that contains two predictors, which are age and salary. Thus, we want to predict if a customer is willing to purchase our product. Finally, I will define both models and fit our data. Please refer to the KNN implementation provided above. I am selecting 5 as our default k value. Note that for the latter model the default metric is minkowski, and with p=2 is equivalent to the standard Euclidean metric.


<center><img src="Python Implementation of K-Nearest Neighbours (kNN d054ba7e11524969817e6ca2468e9804//Untitled.png"></center>

# Results

The accuracy turned out to be 0.93, which is a pretty good result. The figure attached below is a visualization of our test set results. I am providing a single figure since both models are identical. However, I personally suggest using implementations that are provided already since our implementation is simple and inefficient. Moreover, it is just more convenient not to keep writing the exact same code every time.
<center><img src="Python Implementation of K-Nearest Neighbours (kNN d054ba7e11524969817e6ca2468e9804//Untitled 1.png"></center>
