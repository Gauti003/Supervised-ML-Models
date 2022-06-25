**Supervised ML algorithms** :octocat:

   ***Classification and Regression***
 
       1. Classification ( discrete value outputs / Categorical )
                a.  Logistic Regression
                b.  Decision Trees
                c.  Random Forest
                d.  Support vector Machines
                
               In Classification, the goal is to pedict the class labels from a predefined list of 
               possibilities of examples.
               eg: cat/not cat, men/women, good/bad 
                
       2. Regression (Continuous Value Outputs)
                a.  Linear Regression
                b.  Regression Trees
                c.  Non-Linear Regression
                d.  Bayesian Linear Regression
                e.  Polynomial Regression
                
                In Regression the goal is to predict continous number or a floating point number.
                eg: Predecting House prices, salaries , Yield etc.. 
                
   ***Differentiating between Classification and Regression Problems***
   
      Check for continuity or discrete in the outout.
      
   ***Generalisation, Overfitting, Underfitting*** (Book: Intoduction to Machine Learning with Python)
      
          1. Generalisation
                In supervised learning, we want to build a model on the training data and then be
                able to make accurate predictions on new, unseen data that has the same characteristics
                as the training set that we used. If a model is able to make accurate predictions on
                unseen data, we say it is able to generalize from the training set to the test set. We
                want to build a model that is able to generalize as accurately as possible.
                Usually we build a model in such a way that it can make accurate predictions on the
                training set. If the training and test sets have enough in common, we expect the
                model to also be accurate on the test set.
                
          2.  Overfitting
                Building a model that is too complex for the amount of information we have is called overfitting. 
                Overfitting occurs when you fit a model too closely to the particularities of the training set and
                obtain a model that works well on the training set but is not able to generalize to new data.
                
                
          3. Underfitting 
                If your model is too simple then you might not be able to capture all the aspects of and variability
                in the data, and your model will do badly even on the training set. Choosing too simple a model is called 
                Underfitting.
                
                ![image](https://user-images.githubusercontent.com/100043062/175775809-5236b9f8-db64-4f7a-be48-aeb3a14e33ac.png)

                
                
                
                       
                       
                            
