# Predicting User Churn for Sparkiy (Music App) !!!


## Libraries used

Following are the moduels which have been used in the notebook  and are necessary for running the notebook.
1. Python 3.6.3
2. Spark Version 2.4.3
3. Pandas 
4. Matplotlib
5. Seaborn

## Motivation for the Project 

The Project is a Udacity's Capstone Project for Data Science Nano Degree. The project primarily uses Spark for Python called pyspark to do the analysis. 

It is very difficult to aquire customers for you business , which is a fact. But an even greater fact is to retain your customers and build good repo with them. There is no better promotion than word-to-mouth promotion. This is also true for bad promotions as well, which happens when a user churns (or discontinues their service). So a lot of the organizations have sepecific teams which cater to understanding and reducing the customer/user churn.

The project looks at analyzing and predicting user behaviour and churn for Sparkify. Sparkify is a famous (though fictional) music app  which is seeing  a lot of churn of users. The project tries to follow CRISP-DM way to analyze and provide meaningful results from the data. The aim here is to predict churn of users in Sparkify. Different Data Science techniques and machine learning models are used for the analysis. The data provided by Sparkify is an activity log of the users spanning about 3  months.

Spark is used for this project to ensure that it would be easy to upsacle it when the need arises. This can be done through a simple starter code change in the notebook which can be hosted on a server from IBM or AWS with multiple clusters to handle the load.

## Files in the Repository 

Following files are included in this repository:

1. Blog_pics/ : It stores all the pictures of the plots shown in the blog.
2. README.md :  A brief Information on the project.
3. Sparkify-DSND.ipnyb : An IPython Jupyter notebook which houses all the analysis done in the project with code.

## Results of the analysis :

1. The most important factor in predicting a user churn is actually the total amount of time a user has been with the app. The lesser this time the more possibility for the user to churn. Which is clearly seen in many organizations that they focus heavily on the users which are new so that they are satisfied with the service and do not churn.
2. There are other factors in case of Sparkify which affect the Churn  which are more amount of Thumbs Down given , Less Friends added and songs added to playlist, more advertisments being shown to users  are some of the important ones.
3. Random Forest Classifer is best able to predict the churn with Logistic Regressiona and Decision Trees not far behind.


## Acknowledgements 

This is to acknowledge and thank the Data Science Nano Degree Instructors , mentors and the staff of Udacity for all the help without whom there would not be this project. And special thanks to my parents who have always supported me through this journey.

*This project is a part of Data science Nano Degree Course at Udacity called Capstone Project. This project cannot be used or referenced by other Udacity students for their Nano Degree Projects.*

