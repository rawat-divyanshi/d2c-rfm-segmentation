# D2C Customer Churn Intelligence & Retention API

## Part 2: RFM Segmentation & Retention Strategy

### Project Objective
This project performs RFM (Recency, Frequency, Monetary) analysis to segment customers and generate retention strategies for a D2C business.

### Dataset
- orders.csv
- customers.csv
- churn_labels.csv
- intervention_history.csv
- support_tickets.csv
- web_events_snapshot.csv

### Customer Segments
- Best Customers
- Loyal Customers
- Recent Customers
- Big Spenders
- At Risk Customers

### Key Business Insights
- Best Customers generate the highest revenue and should be retained with loyalty rewards.
- Loyal Customers purchase frequently and are ideal for membership programs.
- Recent Customers can be targeted with personalized recommendations.
- Big Spenders should receive premium offers and exclusive benefits.
- At Risk Customers require re-engagement campaigns.

### Outputs
- Customer Segmentation
- Segment Summary Table
- Retention Recommendations

### Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Structure

```text
d2c-rfm-segmentation/
│
├── data/
│   ├── churn_labels.csv
│   ├── customers.csv
│   ├── DATA_DICTIONARY.md
│   ├── intervention_history.csv
│   ├── orders.csv
│   ├── rfm_modeling_snapshot.csv
│   ├── STUDENT_FACING_PROBLEM_STATEMENT.md
│   ├── support_tickets.csv
│   └── web_events_snapshot.csv
│
├── notebooks/
│   └── rfm_segmentation.ipynb
│
├── outputs/
│   ├── segment_summary.csv
│   └── segments.csv
│
├── manual_review_cases.md
├── retention_strategy.md
├── README.md
└── requirements.txt
```