In this blog, we are going to learn the following things
In this project, we will learn how to detect whether women have breast cancer or not by using machine learning
Uploading our data using ipywidgets
Data understanding and visualization
Plot various kinds of plots using seaborn, matplotlib , heatmap, and much more
Different machine learning techniques like RandomForestClassifier, K neighbors Classifier, SVC

First thing we need is data on which this machine learning can be done you download it from kaggle

Various parameter given in our dataset and its meaning
Attribute Information:

1) ID number
2) Diagnosis (M = malignant, B = benign)
3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)
b) texture (standard deviation of gray-scale values)
c) perimeter
d) area
e) smoothness (local variation in radius lengths)
f) compactness (perimeter^2 / area - 1.0)
g) concavity (severity of concave portions of the contour)
h) concave points (number of concave portions of the contour)
i) symmetry
j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

Since we are not doctor all you need to know is malignant means women have cancer and benign means she does not have

First thing we have to do is import important modules that we are going to use [we are going to call machine learning modules later onwards]


Aim of this project
Data Cleaning
Data Visulisation
Machine learning using RandomForestClassifier ,KNeighborsClassifier 
Random Forest Classifier(It makes no. of decision by combining all those decision base on that it give the result)
KNeighborsClassifier (It makes cluster of data base on region in which cluster our data is found or the distance between the data and cluster it give the result)
PCA is done to reduce the number of dimensions

