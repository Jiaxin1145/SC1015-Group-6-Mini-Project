# SC1015 Group 6 Mini Project
For our mini project in SC1015 Introduction to Data Science and Artificial Intelligence, we analysed on the Online Food [Dataset](https://www.kaggle.com/datasets/sudarshan24byte/online-food-dataset/data) from kaggle.
### Problem Definition
The objective of this project is to develop a predictive model that optimise online food order feedback by encouraging more positive ratings and minimise negative ratings. By analysing various factors influencing customer feedback, the goal is to identify strategies to increase overall positive feedback rates on the platform.
### Members (FCSI)
1. Koh Jia Xin
2. Mathew Alan Shilu
3. Girish Pranav
### Presentation
The presentation video can be found [here] (insert link)
### Files included
1. [onlinefoods.csv](https://github.com/Jiaxin1145/SC1015-Group-6-Mini-Project/blob/main/onlinefoods.csv)
2. Mini Project Slides.pdf
3. [SC1015 Mini Project Group 6.ipynb](https://github.com/Jiaxin1145/SC1015-Group-6-Mini-Project/blob/main/SC1015%20Mini%20Project%20Group%206.ipynb)
   - Data preparation and cleaning
   - Exploratory Data Analysis
   - Machine Learning: Random Forest, Logistics Regression
## Brief Jupyter Notebook walkthrough
### Data preparation and cleaning
1. Remove duplicates, unnamed column and insignificant columns
2. Check for null values
3. Generate descriptive statistics for numerical columns
4. Encoding categorical variables
5. Upsampling
### Exploratory Data Analysis
1. Used box plots and bar graphs to analyse categorical and numerical data
### Machine Learning
Upsample, then Random Forest
1. The Random Forest model shows moderate accuracy and true positive rate
2. There is also a reduction in the discrepancy between the train and test datasets
3. Reduced false positive rate from 1.0 to 0.381
   
Logistics Regression
1. Train with categorical variables
2. Average Accuracy: 83%
3. Model evaluation
   - Confusion Matrix
   - recall, precision, f1 score
## Conclusion
Machine Learning Comparisons

Random Forest
- The models show moderate accuracy in predicting feedback with the numerical variables
- Both age and family size models perform similarly, with no clear winner in predicting feedback given
  
Logistics Regression
- The has a high accuracy of approximately 83% on average. This indicates that the model generalises well to unseen data
- The model ranks the importance of categorical predictors based on their coefficients
- Precision for positive feedback is high at 86%
### What have we learnt from this project?
1. Random Forest Model
2. Justify the suitability of a model based on readings from classification report
3. Understanding of real world application of machine learning in addressing business problems
4. Using a new machine learning function: random forest
### Outcomes of our project
1. Online food ordering companies can use our model to predict their feedback
2. Predict what changes can be made to improve their feedback
3. Improve customer satisfaction
### References
Dharmavarapu H. R. S. S. S. S. Manikanth. (2020). Impact of the Online Customer Reviews in Consumer’s Food Ordering Decision for the Online Food Delivery Service Apps. International Journal of Advanced Science and Technology, 29(5s), 2692-2703. Retrieved from [http://sersc.org/journals/index.php/IJAST/article/view/22864](http://sersc.org/journals/index.php/IJAST/article/view/22864)

Zippia. 18+ Food Delivery Statistics (2023). Online Ordering Industry Numbers You Need To Know. Retrieved from [https://www.zippia.com/advice/food-delivery-industry-statistics/](https://www.zippia.com/advice/food-delivery-industry-statistics/)

Sruthi, E. R. (2024). Understand Random Forest Algorithms With Examples. Retrieved from [https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/](https://www.analyticsvidhya.com/blog/2021/06/understanding-random-forest/)

Kanade, V. (2022). What Is Logistic Regression? Equation, Assumptions, Types, and Best Practices. Retrieved from [https://www.spiceworks.com/tech/artificial-intelligence/articles/what-is-logistic-regression/](https://www.spiceworks.com/tech/artificial-intelligence/articles/what-is-logistic-regression/)
