# Naive Bayes
Naive Bayes is a family of probabilistic algorithms that take advantage of probability theory and Bayes’ Theorem to predict the tag of a text (like a piece of news or a customer review).
They are probabilistic, which means that they calculate the probability of each tag for a given text, and then output the tag with the highest one.
The way they get these probabilities is by using Bayes’ Theorem, which describes the probability of a feature, based on prior knowledge of conditions that might be related to that feature.
Bayes’ Theorem is useful when working with conditional probabilities (like we are doing here), because it provides us with a way to reverse them:
                  P(A|B)=(P(B|A)*P(A))/P(B)

# Dataset
This data sets consists of 3 different types of irises’ (Setosa, Versicolour, and Virginica) petal and sepal length, stored in a 150x4 numpy.ndarray The rows being the samples and the columns being: Sepal Length, Sepal Width, Petal Length and Petal Width.

# Install
Supported Python version - Python version used in this project: 3.5+

# Libraries used
  Pandas 0.18.0
  Numpy 1.10.4
  Matplotlib 1.5.1
  Scikit-learn 0.17.1
  Seaborn 0.8.0
# Code
The code used in this project is inside Naive Bayes.ipynb.

# Run
To run this project you will need some software, like Anaconda,
which provides support for running .ipynb files (Jupyter Notebook).
After making sure you have that, you can run from a terminal or cmd next lines:
ipython notebook Naive Bayes.ipynb or jupyter notebook Naive Bayes.ipynb
