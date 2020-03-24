# titanic_survival_exploration


After several iterations of exploring and conditioning on the data, you have built a useful
algorithm for predicting the survival of each passenger aboard the RMS Titanic. 
The technique applied in this project is a manual implementation of a simple machine learning model, the *decision tree*.
A decision tree splits a set of data into smaller and smaller groups (called *nodes*), by one feature at a time. 
Each time a subset of the data is split, our predictions become more accurate if each of the resulting subgroups 
are more homogeneous (contain similar labels) than before. The advantage of having a computer do things for us is that
it will be more exhaustive and more precise than our manual exploration above.
[This link](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/) 
provides another introduction into machine learning using a decision tree.

A decision tree is just one of many models that come from *supervised learning*. In supervised learning, we attempt
to use features of the data to predict or model things with objective outcome labels.
That is to say, each of our data points has a known outcome value,
such as a categorical, discrete label like `'Survived'`, or a numerical, continuous value like predicting the price of a house.
