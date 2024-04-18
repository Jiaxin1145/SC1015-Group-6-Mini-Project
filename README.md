# SC1015-Group-6-Mini-Project
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




