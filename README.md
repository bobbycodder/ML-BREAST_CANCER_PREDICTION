# ML-BREAST_CANCER_PREDICTION

I have created Machine Learning Model With Self-defined Function of Logistic Regression for Breast Cancer Predictions.

In this I've used Python’s Famous libraries like [Numpy](https://numpy.org/), [Pandas](https://pandas.pydata.org/), [Seaborn](https://seaborn.pydata.org/), [Matplotlib](https://matplotlib.org/), Data analysis and Model Development.

I've created Self-defined Logistic Regression Model and performed it onto Breast Cancer data. Along with I've perform logistic regression with the help of sklearn also.\

I've used [Jupyter Notebook](https://jupyter.org/) for coding!

I obtained the Dataset from [Kaggle](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data).

 <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQWHI276MB93VTqey9FCc5qbK2abwNfwT1vYA&usqp=CAU" width="400" height="200">

# About Data and Model

__About Data Attribute Information:__

   * id
   * diagnosis: M = malignant, B = benign
   * Columns 3 to 32
   * Ten real-valued features are computed for each cell nucleus:
   * 
   * radius: distances from center to points on the perimeter
   * texture: standard deviation of gray-scale values
   * perimeter
   * area
   * smoothness: local variation in radius lengths
   * compactness: perimeter^2 / area - 1.0
   * concavity: severity of concave portions of the contour
   * concave points: number of concave portions of the contour
   * symmetry
   * fractal dimension: "coastline approximation" - 1 The mean, standard error, and "worst" or largest (mean of the three largest values) of these features were computed                 for each image, resulting in 30 features. For instance, field 3 is      
   * Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

***I have used the “Breast Cancer Wisconsin (Diagnostic)” (WBCD) dataset, provided by the Kaggle.***

I have used their dataset to implement a Logistic Regression predictor based on some of the 30 features of the WBCD, in Python. 

We will use the outcome Bening/Malignant to predict if a new patient has a probability of developing malignancy or not, basing on the FNA data. 

**Furthermore, our predictor will be an exciting occasion of exposing some basic concepts of Logistic Regression and implementing a code around the biomedical problem: what features are essential in predicting malignant outcomes.**

# Conclusions and Considerations

* **Logistic Regression is a powerful Machine Learning tool, and we can use it successfully for predicting categorical outputs of biomedical data. Data wrangling and data mining can benefit from excellent performances offered by Python and its libraries so well supported by the community. Linear Algebra programming has intrinsic advantages in avoiding, where possible, ‘while’ and ‘for’ loops. It is implementable by numpy, a package that vectorizes the matrixes. Numpy makes working on them more comfortable, and guarantees better control over the operations, especially for large arrays.**

* **Moreover, the Machine Learning scenario with Python is enriched by the presence of many powerful packages (i.e., Tensorflow, Scikit-learn, and other that, for technical reasons, we haven’t mentioned in this post), which provide excellently optimized classifications and predictions on data.**

* **While Machine Learning, equipped with Python and all its accessories, can represent the path toward the future of preventive and diagnostic Medicine, limitations in comprehending biological variables could make this path an awkward road.**

* **The Wisconsin Breast Cancer (Diagnostic) Data Set, with its 569 patients and 30 features, offers an exhaustive assortment of parameters for classification and for this reason represents a perfect example for Machine Learning applications. Anyway, many of these features seem to be redundant, and a definite impact on classification and prediction by some of them remains still unknown.**

***I have introduced a Bivariate Analysis, to reduce the number of redundant features. An in-depth discussion on the role of these features in the prediction should deserve a dedicated article.***

**I hope you find this project useful! Follow along [notebook](https://github.com/bobbycodder/ML-BREAST_CANCER_PREDICTION) for more!!..**

 <img src="https://miro.medium.com/max/694/1*ieIAhbb-osfu_aH4GSvWeg.png" width="400" height="200">
 
 <img src="https://miro.medium.com/max/1400/1*30aqLFokurDDx5y1TGE4fw.jpeg" width="400" height="200">
 
 
 
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS4gMXUzLVe7VwcD4WJFLQyT-WqXKebkgywiA&usqp=CAU" width="400" height="200">

