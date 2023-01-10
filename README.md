# project1-Loan-Eligibility

Problem Statement :

                 *  The company wants to automate the loan eligibility process based on customer detail provided while filling out online            application forms.     
   Identify Which Type of Problem:

         * This is a classification problem in which we need to classify whether the loan will be eligible or not. classification refers to     a predictive modeling problem where a class label is predicted for a given example of input data.  

    How to Approach the Problem: 

               * This is a Binary Classification problem in which we need to predict our Target label which is “Loan Status”.

                      Loan status can have two values: Yes or NO.

                 *   Yes: if the loan is eligible

                 *   NO: if the loan is not eligible

       So using the training dataset we will train our model and try to predict our target column that is “Loan Status” on the test          dataset.

     Table of Contents:

                 1.  About the dataset 

                 2. Load essential Python Libraries

                 3. Load Training/Test datasets

                 4. Data Preprocessing

                 5.  Exploratory data analysis (EDA).

                 6. Feature Engineering.

                 7. Build Machine Learning Model

                 8.  Make predictions on the test dataset

                 9. Conclusion


correlation matrix of data set :

![image](https://user-images.githubusercontent.com/117625658/211555251-46a54cdb-234c-4896-87a6-3256374bdea9.png)

major impact  with target variable:

(loan status) vs independent variable(credit history) 

![image](https://user-images.githubusercontent.com/117625658/211556499-912c14b0-71f3-4a52-82d6-a5c2bc3a92d5.png)

conclusion:
     
          After the Final Submission of test data, my accuracy score In logistic regression was 78.86%,
          In support vector machine was 0.7886178861788617,
          In Random forest was 0.8965390792417285. 
          In the model,credit history is the most important affecting factor to get loan eligibility. 
          Amazingly random forest algorithm worked better than all other models.
          

