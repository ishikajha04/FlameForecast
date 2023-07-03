# FlameForecast
**ABOUT DATASET**

I have taken the dataset of **Montesinho forest** which consist the information of their different location represented through x and y axis and various factors on which forest fire depends like **ffmc, temp, wind, dc,humidity** ,e.t.c and the **area** destructed due to forest fire.

Basically there were two approaches which could have been used to develop a predictive model.

**Classification method**-which predicts forest fire will take place or not for the given condition

**Regression method**-which predicts how much area fire will get spread if forest fire takes place for the given condition.  Our model uses a regression method.

**Overview**

1 Imported the libraries (numpy ,panda, matplotlib)

2 Imported the dataset in the form of csv file

3 Performed Exploratory Data Analysis (EDA) on all features

4 used linear regression method for deploying the model

I have used **python** and some of the specific libraries of python like **numpy,pandas,matplotlib,pickle**etc
While performing EDA we analyzed that there are approx **247 data points for which fire didn’t take place.**
Performed **group by** function and used **mean function** to determine how data is scattered. Analyzed that in the month of **august and september** there are **maximum chances** of forest fire.

**Mean absolute error** of the model ranged between **12 to 18** (with respect to area)

The **approach** used to generate the algorithm.

Plotted the scatter graph of each feature affecting forest fire against the area spanned due to it and analyzed the following:

1. Wind vs area graph –wind is a potential attribute (model will give good accuracy ) 

2. Same goes for the temp vs area plot. Moreover it can be concluded that temperature and wind are correlated for the given point.

3. 1/x type of graph between ffmc and area. One of the potential attribute (point scattered at a point )

4. Dc vs area almost the same like ffmc vs area scatter plot. 2 outliers present in dc vs area plot.

5. Ffmc and dc have some correlation,correlated attributes not taken into consideration.

6. Checked for ffmc and wind relation. No finite relation between them, therefore both attributes are taken into consideration 

These all relations (EDA) helped to generate the algorithm and to use the linear regression method to build the model.
