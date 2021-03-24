# Titanic Machine Learning Solution

This repository includes my code for the Titanic Machine Learning competition on Kaggle and is currently a work in progress.

For ease-of-navigation, I'm separating my code into folders for the different phases. 

The phases I'm following include:<br>
<ul><li>Cleaning, preparing, and exploring the data</li>
<li>Training a machine learning model with the training set</li>
<li>Testing the model with the test data</li>
<li>Iterating to improve accuracy</li></ul>


About the competition: 
Kaggle hosts an 'introductory' competition where they provide a dataset separated into a pre-defined train subset and a test subset to be downloaded as a CSV. Each of these files has several columns (or features): PassengerID, PClass (Priority Class - ie. 1st class, 2nd class), Name, Sex, Age, SibSp (number of siblings and/or spouse on board), Parch (number of parents and/or children on board), Ticket (Ticket number), Fare, Cabin, Embarked (Port of embarkation - ie. Cherbourg, Queenstown, Southampton). 

The train set includes an additional column-Survived-indicating whether the individual survived (denoted by a 1) or did not survive (denoted by a 0). The goal is to accurately predict whether each individual in the test subset survived or not using machine learning.
