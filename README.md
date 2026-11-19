# Brazilian E-Commerce Data Analytics | CodeAlpha Internship Project

**Author:** Emmanuel Chimaobi Nebo  
**Programme:** CodeAlpha Data Analytics Internship  
**Project:** Brazilian E-Commerce Data Analysis  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, PySentimiento, Google Colab

---

## Project Overview

This project explores the Brazilian E-Commerce Public Dataset by Olist to uncover insights into sales performance, delivery operations, customer satisfaction, payment behaviour, and customer review sentiment.

The analysis combines exploratory data analysis (EDA), statistical investigation, data visualisation, and Natural Language Processing (NLP) to identify operational patterns and translate findings into actionable business recommendations.

## Project Objectives

- Examine and validate the structure and quality of the datasets.
- Analyse sales performance and product category contributions.
- Evaluate delivery performance and identify late-delivery patterns.
- Investigate customer review scores and satisfaction.
- Explore payment methods and transaction behaviour.
- Apply sentiment analysis to Portuguese customer reviews.
- Develop data-driven business recommendations.

## Dataset Description

The analysis uses nine interconnected tables from the Brazilian E-Commerce Public Dataset by Olist:

| Dataset | Description |
|---|---|
| Customers | Customer information |
| Orders | Order status and timestamps |
| Order Items | Products, prices, and freight |
| Payments | Payment types and values |
| Reviews | Customer ratings and comments |
| Products | Product attributes and categories |
| Sellers | Seller information |
| Geolocation | Brazilian geographical coordinates |
| Category Translation | Portuguese-to-English category mapping |

## Tools and Technologies

- **Python:** Core analysis and data processing.
- **Pandas:** Data manipulation and cleaning.
- **NumPy:** Numerical operations.
- **Matplotlib & Seaborn:** Data visualisation.
- **PySentimiento:** Portuguese-language sentiment analysis.
- **Google Colab:** Notebook development and execution.

## Analytical Workflow

1. Data loading and initial inspection.
2. Data quality assessment and validation.
3. Missing-value, duplicate, and data-integrity investigations.
4. Exploratory data analysis.
5. Sales, product category, payment, and delivery performance analysis.
6. Customer review and satisfaction analysis.
7. Statistical comparison of delivery performance and review scores.
8. Portuguese customer review sentiment analysis.
9. Business insights and recommendations.

## Key Findings

### Sales Performance
- Total item-price value across the available order-item records was **R$13.59 million**.
- Health & Beauty recorded the highest item-price total among product categories, at approximately **R$1.26 million**.
- November 2017 recorded the highest monthly item-price total, at approximately **R$1.01 million**.

### Delivery Performance
- Approximately **93.23%** of valid delivered orders arrived on or before the estimated delivery date.
- Late deliveries accounted for approximately **6.77%**.
- Average delivery duration was approximately **12.56 days**.

### Customer Satisfaction
- Average customer review score was **4.09 out of 5**.
- Approximately **77.07%** of reviews were rated 4 or 5 stars.
- Late-delivered orders had substantially lower average review scores than on-time orders.

### Payment Behaviour
- Credit cards accounted for approximately **73.92%** of payment records.
- Boleto was the second most frequently recorded payment method.

### Sentiment Analysis
A Portuguese-language sentiment model was applied to 40,950 non-empty customer review comments.

- Positive: **47.26%**
- Neutral: **33.46%**
- Negative: **19.28%**

The sentiment predictions were also compared with review-score-derived proxy labels, producing an overall agreement of approximately **63.87%**.

## Business Recommendations

1. Improve delivery planning and logistics monitoring to reduce late deliveries.
2. Investigate sellers, products, and routes associated with delivery delays.
3. Maintain strong performance in high-contributing product categories.
4. Monitor negative customer reviews to identify recurring service issues.
5. Use sentiment analysis as an additional customer-feedback monitoring tool.
6. Continue monitoring payment behaviour to support customer payment experience improvements.

## Project Deliverables

- Completed Python Jupyter Notebook.
- Exported notebook PDF.
- Professional project report.

## Limitations

- The analysis is based on the available historical dataset and may not represent current business performance.
- Sentiment analysis was performed on Portuguese written reviews only.
- Sentiment evaluation used review-score-derived proxy labels rather than independently human-verified labels.
- The observed relationship between delivery delays and lower review scores does not establish causation.
- Item-price totals represent the sum of available order-item price values and should not be interpreted as profit or net revenue.

## Conclusion

This project demonstrates the application of Python-based data analytics to a real-world e-commerce dataset. Through data cleaning, exploratory analysis, visualisation, statistical investigation, and sentiment analysis, the project identified important patterns in sales, logistics, and customer experience.

The findings provide practical insights that can support better operational monitoring and data-driven decision-making.

---

**Developed by Emmanuel Chimaobi Nebo**  
*CodeAlpha Data Analytics Internship*


---

## Project Visualisations

### 1. Monthly Revenue Trend
![Monthly Revenue Trend](Monthly%20Revenue%20Trend.png)

### 2. Customer Review Score Distribution
![Customer Review Score Distribution](Customer%20review%20score%20distribution.png)

### 3. Customer Satisfaction
![Customer Satisfaction](Customer%20Satisfaction.png)

### 4. Customer Review Sentiment Distribution
![Customer Review Sentiment](Distribution%20of%20Customer%20review%20sentiment.png)

### 5. Sentiment Model Validation
![Sentiment Model Validation](Sentiment%20Model%20Validation.png)
