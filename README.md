# Amazon Customer Behavior & Market Basket Analysis

## Project Overview

This project analyzes Amazon customer shopping behavior using Python to identify purchasing patterns, customer segments, recommendation insights, and review-related trends.

The analysis focuses on customer demographics, purchase frequency, product categories, browsing behavior, cart abandonment, shopping satisfaction, recommendation helpfulness, and review reliability.

The project was developed as part of a Customer Insights Analytics project using the Amazon Customer Behaviour Survey dataset.

---

## Project Objectives

- Clean and prepare Amazon customer survey data for analysis.
- Analyze customer demographics and purchasing behavior.
- Identify popular product categories and purchase patterns.
- Segment customers based on purchase frequency and satisfaction.
- Apply K-Means clustering for behavioral customer segmentation.
- Analyze the relationship between recommendation helpfulness and shopping satisfaction.
- Examine review reliability, rating accuracy, and customer satisfaction.
- Create visualizations to communicate key customer insights.
- Provide data-driven recommendations for customer engagement and personalization.

---

## Dataset

The project uses the **Amazon Customer Behaviour Survey** dataset.

The dataset contains information related to:

- Customer demographics
- Purchase frequency
- Purchase categories
- Personalized recommendation frequency
- Browsing frequency
- Product search methods
- Search result exploration
- Customer review importance
- Cart behavior
- Cart abandonment factors
- Review activity
- Review reliability
- Review helpfulness
- Recommendation helpfulness
- Rating accuracy
- Shopping satisfaction
- Service appreciation
- Improvement areas

---

## Project Tasks

### Task 1: Data Cleaning & Preparation

- Removed duplicate records.
- Standardized categorical values.
- Handled missing values.
- Cleaned and standardized column names.
- Converted rating and satisfaction fields into appropriate numeric formats.
- Prepared the dataset for further analysis.

### Task 2: Descriptive Behavior Analysis

Performed analysis of:

- Customer age distribution
- Gender distribution
- Purchase frequency
- Popular product categories
- Browsing frequency
- Cart abandonment factors
- Shopping satisfaction
- Recommendation helpfulness
- Rating accuracy

Summary statistics and visualizations were created to understand customer behavior.

### Task 3: Customer Segmentation & Profiling

Customers were analyzed using behavioral characteristics such as:

- Purchase frequency
- Shopping satisfaction
- Customer behavior indicators

Customer profiles included:

- Frequent Buyers
- Occasional Shoppers
- At-Risk Customers

K-Means clustering was also applied to identify behavioral customer groups.

### Task 4: Recommendation & Review Insights

The project analyzes:

- Recommendation helpfulness vs. shopping satisfaction
- Review reliability vs. rating accuracy
- Customer engagement with personalized recommendations
- Customer perception of reviews

These insights can help improve personalized recommendation strategies.

### Task 5: Visualization & Reporting

The project includes visualizations for:

- Purchase categories
- Browsing frequency
- Customer satisfaction
- Recommendation usefulness
- Customer segmentation
- Review-related insights
- Behavioral relationships

### Task 6: Presentation

The findings are summarized through a short presentation highlighting:

- Customer purchasing behavior
- Customer segments
- Recommendation insights
- Review behavior
- Key business insights
- Data-driven recommendations

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning

### K-Means Clustering

K-Means clustering was used for behavioral customer segmentation.

The clustering process includes:

1. Selecting relevant behavioral features.
2. Preparing numerical data.
3. Scaling the features.
4. Applying K-Means clustering.
5. Assigning customers to clusters.
6. Interpreting the behavioral characteristics of each cluster.

---

## Key Insights

The analysis helps identify:

- Common customer purchasing patterns.
- Differences in customer behavior across demographics.
- Frequently purchased product categories.
- Customer groups based on purchasing behavior and satisfaction.
- Relationship between recommendation usefulness and satisfaction.
- Importance of reviews in customer purchase decisions.
- Factors associated with cart abandonment.
- Areas where customer engagement can potentially be improved.

---

## Business Recommendations

Based on the analysis, businesses can consider:

1. **Personalized Recommendations**  
   Use customer behavior and purchase patterns to provide more relevant product recommendations.

2. **Customer Segmentation**  
   Develop different engagement strategies for frequent, occasional, and at-risk customer groups.

3. **Review Optimization**  
   Improve the visibility and usefulness of reliable customer reviews to support purchase decisions.

4. **Cart Abandonment Reduction**  
   Analyze common abandonment factors and design targeted strategies to improve conversion.

5. **Customer Satisfaction Improvement**  
   Use satisfaction-related insights to identify areas for improving the overall shopping experience.

---

## Project Structure

```text
Amazon-Customer-Behavior-Analysis/
│
├── Amazon.csv
├── Ml projext.html
├── Project_Report.pdf
├── README.md
└── Presentation/
    └── Project_Presentation.pdf
