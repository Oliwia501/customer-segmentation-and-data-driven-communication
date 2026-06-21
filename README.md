# Customer Segmentation and Data-Driven Communication

End-to-end customer analytics project focused on transforming retail customer data into actionable customer segments and communication recommendations.

The project uses the `marketing_campaign.csv` dataset, which contains demographic, behavioral, purchase, and campaign response data. The analysis combines data cleaning, exploratory data analysis, RFM segmentation, K-Means clustering, and segment-level marketing recommendations.

## Objective

The goal of this project is to help a retail company better understand its customer base and support targeted communication decisions through data-driven segmentation.

The analysis identifies high-value, active, low-value, and inactive customer groups, compares rule-based and machine learning segmentation approaches, and translates the findings into practical communication strategies.

## Workflow

* **Data Audit and Cleaning**
  Assessed missing values, duplicates, inconsistent categories, unrealistic birth years, and income outliers. Missing income values were imputed, rare marital status categories were grouped, and unrealistic records were removed or adjusted.

* **Exploratory Data Analysis**
  Analyzed customer demographics, product spending, purchase channels, campaign response, and hidden behavioral patterns useful for targeted marketing.

* **RFM Segmentation**
  Engineered Recency, Frequency, and Monetary features and assigned quintile-based scores to define customer groups such as Champions, Loyal Customers, Potential Loyal Customers, At Risk, and Lost / Inactive customers.

* **K-Means Clustering**
  Applied K-Means clustering on standardized customer features. The optimal number of clusters was selected using the Elbow Method and Silhouette Score, with `k=4` chosen as the most actionable solution.

* **Communication Strategy**
  Recommended communication channels, message tone, and campaign ideas for each customer segment based on behavioral and demographic characteristics.

## Key Insight

RFM segmentation is effective for identifying customer value and activity levels, while K-Means clustering adds broader behavioral and demographic context, such as income, family structure, channel preference, and website activity.

Combining both approaches provides a more complete view of customers and supports more precise marketing communication decisions.

## Tech Stack

Python · pandas · NumPy · scikit-learn · matplotlib · seaborn

## Repository Structure

```text
customer-segmentation-and-data-driven-communication/
│
├── customer_segmentation_data_driven_communication.ipynb
├── requirements.txt
├── README.md
└── data/
    └── marketing_campaign.csv
```

## How to Run

Open the notebook in Google Colab or Jupyter Notebook.

The dataset is stored in the `data/` folder and can be loaded directly from this repository.

```bash
pip install -r requirements.txt
```

## Author

Oliwia Iwańska

