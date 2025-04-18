# 1.Titanic-Machine-Learning-Project
Kaggle Project: A predictive machine learning model that predicts which passengers survived the Titanic shipwreck

**Context:**
While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.
In this project, I build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

**Strategy Used:** 
1. Understand the problem (Always learn about the data)
2. Exploratory Data Analysis (Better EDA better results -- try different methods to see if results improve!) 
3. Train, tune, ensemble (combining multiple models) Machine learning projects
4. Accuracy test of your model

**Solution Building:** 
1. **Understand the problem:** We need to predict whether or not the passenger survived the sinking of the Titanic -- prediction model. Since our model is based on multiple features like gender, class etc and we have the outcome as well. Based on the outcome in training set, I need to predict outcome for he test set. Now, this is based on some features (For future projects, I will learn to perform feature engineering to form new features not what that is available in the dataset that could give me better results).

2. **Dataset:** We have two dataset - training set that will be used to build our model since we have all the features as well as the outcome. 2. Test Dataset: that is used to see how well the model performs on unseen data with a main task to predict the outcomes.
   
3. **Understand all the features in the dataset:** 
1. PassengerId
2. Survived
3. Pclass: Class of the passenger (1-upper, 2-middle, 3-lower)
4. Name
5. Sex (Male or Female)
6. Age
7. SibSp: number of Sibling or spouse (Sibling - brother, sister, stepbrother, stepsister____ spouse: husand, wife)
8. Parch: # of parents / children aboard the Titanic
9. Ticket
10. Fare
