# Customer Segmentation

## Project Description
In this project, customer grouping will be carried out based on 4 categories, namely A, B, C and D using the Customer Segmentation technique. with this technique the company's product sales products can be marketed more effectively based on the right customer category. 

This process is done by applying various Machine Learning algorithms to get a more accurate customer classification based on certain criteria.

## Dataset
The dataset used is taken from Kaggle.com, namely [Customer Segmentation](https://www.kaggle.com/datasets/vetrirah/customer) from AV - Janatahack which is divided into train data with Features and “Segmentation” and test data without and without “Segmentation”.

- ID : Unique ID
- Gender : Gender of the customer.
- Ever_mariage : Marital status of the customer.
- Age : Age of the customer.
- Graduate : Is the customer a graduate ?
- Profession : Profession of the customer.
- Work Experience : Work Experience in years.
- Spending score : Spending score of the customer.
- Familiy_size : Number of family members for the customer (including the customer).
- Var_1 : Anonymised Category for the customer.

## Analysis Steps
1. **Business understanding**:
    - Understand business needs and consider the appropriate technology stages to solve business problems. 

2. **Exploratory Data Analysis (EDA)**:
    - Understand the types of data and consider the stages of data cleaning and processing using visualization and histograms, box plots.
    - Get Insight from EDA
      
3. **Get Insigth form Data Train**
    - Segment D tends to be more populated by Males, while Segment A is more dominated by Females. indicating a relationship between gender and higher spending.
    - Segment A and Segment B are more populated by married individuals (Yes). This suggests that married individuals are more likely to have lower expenditure and more financial stability.
    - Segment D, which contains high spending individuals, is mostly composed of unmarried individuals (No), which may indicate that they have more freedom in managing their personal finances.
    - Healthcare and Doctor jobs are more prevalent in the high spending segment (D), while professions such as Artist and Entertainment are found in the lower segment (A).
    - Segment D shows a more mature consumer profile in terms of age, work experience, and family, with higher spending. Consumers in this segment tend to be more financially stable, more experienced, and have larger families.
    - Segment A is more dominated by young consumers with little work experience and small families, with low spending.

4. **Data Preprocessing**:
    - Handle missing data using mean and mode techniques
    - Handle irrelevant data (outliers) in data
    - replace and remove irrelevant data
    - coded categorical data using label_ecoder and one heat coding.

5. **Model Building**:
    - Train the data and compare relevant models to train data to find the best model with the highest accuracy.

6. **Model Evaluation and Discussion**:
    - Evaluate the trained model with the dataset with accuracy and classification reports.
    - Predict test data to determine customer segmentation using the best accuracy trained model.

## Tools and Library
- Pandas, NumPy, Scikit-learn and Gradient Boosting for data manipulation, model building, and evaluation.
- Matplotlib and Seaborn for data visualization.
- Collaboratory To document the analysis, model development, and results.

## Result and Recommendation
1. **Conclusions and Results**
    - Gradient Boosting-based classification model provides the best results from other models. To predict consumer segmentation with sufficient accuracy.However, it is necessary to improve the model by increasing the amount of data and performing hyperparameter tunning.
    - Explore other models or Add additional features, such as interactions between features or external data that can improve predictions.
    - By implementing a customer segmentation model, automotive companies can develop more focused and efficient marketing strategies, tailor products to the needs of each market segment, and determine prices that are more in line with the purchasing power of each segment. This model allows companies to offer a more personalized customer experience, such as exclusive after-sales services for the high-spending segment and more affordable products for the younger segment. In addition, companies can design relevant loyalty programs and use the right communication channels to reach customers, thereby increasing overall satisfaction, retention and sales.
3. **Business recommendations**
    - Segments A: Focus on products that are more affordable or have simpler features for example, P3 and P4, at a price that fits their budget. Use discount strategies or promotions to appeal to this segment, such as discounts on first purchases or cashback programs.
    - Segment D: Consumers are older and with higher spending. Recommend premium products or exclusive services for them e.g., P1 and P2 that match their more established lifestyle and require comfort and quality.
    - Segments B and C contain married individuals with lower spending levels and are financially stable. Focus on products that are more suitable for families or that can accommodate more needs e.g. larger and more functional P3s that Provide financing or installment options that can help
    - Improving Customer Experience: Focus efforts on improving the customer experience for segments B and D, who exhibit high spending but may not be fully brand-attached.

