*Code cannot be shared due to privacy reasons*

# Analysis of accidents that take place in industries

 Now-a-days in any industry, occurrence of accidents during the work period are quite often, so they lead to different types of impacts such as equipment property damage, fire, release of toxic gases, injury to workers present at the workplace etc. It has been a challenge to deal with these accidents. In order to overcome these challenges, it is important to find out the reasons behind it and have some early preparation to avoid it. So we analysed the data of accidents of a particular factory, used various machine learning algorithms and optimization techniques, to generate rules for the cause for the accidents. The procedure followed can be seen the image.
<br>

<img align='right' width="350" height="550" src="images/flowchart.png">



1. #### Data Cleaning
   Raw data cannot be passed directly into machine learning algorithms. We have to preprocess them, look for missing values, detect outliers due to human error etc. So we use pandas library to manipulate the data and clean it.

2. #### Classification
   After preprocessing step, we pass the data into machine learning models, which were implemented using Scikit-Learn library. The models used can be seen in the flowchart.<br>
  * [Logistic Regression]()
  * [Decision Tree Classifier]()
  * [Support Vector Classifier]()
  * [K-Nearest Neighbors]()
  

3. #### Ensembling
   Ensembling is the process of combining multiple classifiers together. This gives us better accuracy.<br>
* [Random Forest Classifier]()
* [Gradient Boosting Classifier]()
* [AdaBoost]()
* [Bagging]()
* [Simple Voting Classifier]()

4. #### Optimization
   In order to assign importance to the predictions of models used in a voting classifier we use various optimization techniques.<br>
* [NSGA-II]()
* [Simulated Annealing]()
* [Multi-Objective Differential Evolution]()
   

5. #### Rules
   Finally after we have a trained model, we use it to generate rules where accident is more likely to occur.
<br>

### Results 

<img align="left" src="/images/Screenshot&#32;from&#32;2020-03-08&#32;12-25-06.png" title="Classifier Results"/>
<img align="left" src="images/Screenshot&#32;from&#32;2020-03-08&#32;12-25-34.png" title="Ensembling Results"/>
<img align="left" src="/images/Screenshot&#32;from&#32;2020-03-08&#32;12-26-00.png" title="Optimization Results"/>
<br/><br/><br/><br/><br/><br/><br/><br/><br/>

### Plots

<img align="left" src="images/Screenshot&#32;from&#32;2020-03-08&#32;12-25-19.png" title="Classifier Barplot"/>
<img align="left" src="images/Screenshot&#32;from&#32;2020-03-08&#32;12-25-46.png" title="Ensembling Barplot" width=300/>
<img align="left" src="images/Screenshot&#32;from&#32;2020-03-08&#32;12-26-10.png" title="Optimization Barplot"/>
<br/><br/><br/><br/><br/>
