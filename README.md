# SmartCart-Clustering-System
### Generic Marketing & Engagement Strategies
<hr/>

<b>A machine learning solution for customer intelligence and behavioral segmentation</b>
* ## Problem Statement:
  <strong>SmartCart</strong> is a growing e-commerce platform serving customers across multiple countries. The company collected extensive customer data consisting of 2240 customer records and 22 attributes including demographics, purchase behaviour, website activity, and response.
  
  Currently, SmartCart uses <strong>generic marketing and engagement strategies</strong> for all customers, without clearly understanding different customer behaviour patterns. This results in <strong>inefficient marketing</strong>, missed opportunities to retain high-value customers, and delayed identification of churn-prone users.
  
  To solve this, SmartCart aims to build an <strong>intelligent customer segmentation system</strong> using <strong>unsupervised machine learning</strong>. The system will analyse historical customer transaction data and <strong>group customers into meaningful clusters</strong> based on purchasing behaviour, engagement levels, and loyalty indicators.

* ## Dataset Feature's
  1. Customer Demographics
  2. Purchase Behavior ( Amount Spend )
  3. Purchase Behavior ( Frequency )
  4. Customer Feedback & Constants 
* ## Technologies Used
  1. Python
  2. Numpy & Pandas ( For Data Preprocessing and E.D.A.)
  3. Data Visualization tool ( Matplotlib & Seaborn )
  4. Scikit-learn ( For Preprocessing, Metrics & Implementation of M.L. Model)
* ## Task Performed on Dataset
  * Filled missing values using `SimpleImputer`.
  * Converted `Year_Birth` into a more meaningful feature called `Age`.
  * Converted `Dt_Customer` into `Customer_Tenure_Days`.
  * Combined `Kidhome` and `Teenhome` into a single feature called `Total_Child`.
  * Reduced values of `Marital_Status` into: 
    * Alone
    * With Partner
  * Grouped education levels into:
    * Undergraduate
    * Graduate
    * Postgraduate
  * Removed ID feature because it was not useful for clustering.
  * Combined spending-related features into `Total_Spending_On_Purchasing`.
  * Removed extreme outliers from `Age` and `Income`.
  * Applied One-Hot Encoding on categorical features.
  * Applied Standard Scaling before clustering.

* ## Visualizations
  - Pairplot Analysis
  - Correlation Heatmap
  - Elbow Curve
  - Cluster Scatter Plot
* ## Machine Learning Algorithm Used
  - K-Means Clustering
  - Elbow Method for optimal cluster selection
  - Silhouette Score for evaluation
* ## Project Workflow
  1. Data Collection
  2. Data Cleaning
  3. Feature Engineering
  4. Outlier Removal
  5. Encoding & Scaling
  6. K-Means Clustering
  7. Cluster Analysis & Visualization
 * ## Results
    - Successfully segmented customers into different groups.
    - Identified high-spending customers.
    - Improved understanding of customer purchasing behavior.
