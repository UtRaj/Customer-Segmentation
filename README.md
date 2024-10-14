# Customer Segmentation with RFM and K-Means Clustering

This project demonstrates customer segmentation using the RFM (Recency, Frequency, Monetary Value) method and K-Means clustering. It analyzes a sample sales dataset to identify customer segments for targeted marketing strategies.

## Dataset

The dataset used in this project is a sample sales dataset from Kaggle: [https://www.kaggle.com/kyanyoga/sample-sales-data](https://www.kaggle.com/kyanyoga/sample-sales-data)

## Project Steps

1. **Import Libraries and Load Data:** Import necessary libraries and load the sales dataset.
2. **Data Cleaning and Preparation:** Remove irrelevant columns and prepare the data for analysis.
3. **Data Analysis and Visualization:** Explore the data using descriptive statistics and visualizations.
4. **RFM Analysis:** Calculate Recency, Frequency, and Monetary Value for each customer.
5. **Model: RFM Scoring + K-Means Clustering:** 
    - Assign RFM scores based on percentiles.
    - Use K-Means clustering to group customers based on their RFM scores.
    - Find the optimal number of clusters using the Elbow method.
6. **Description of the Results:**
    - Interpret the resulting customer segments.
    - Formulate potential marketing strategies based on the segments.

## Code Structure

The code is organized into several sections, each covering a specific step of the project.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- datetime
- scipy
- statsmodels
- sklearn

## How to Run

1. Clone the repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Replace the dataset path with the location of your sales dataset.
4. Run the Python script to perform the analysis.

## Results

The project identifies several customer segments:

- **Active:** Customers who have purchased recently, frequently, and for high monetary value.
- **Inactive:** Customers who have not purchased recently, infrequently, and for low monetary value.
- **Departing:** Former high-value customers who have stopped purchasing.
- **New:** Recently acquired customers.

## Potential Marketing Strategies

- **Active:** Reward loyalty with exclusive offers and promotions.
- **Inactive:** Reactivate them with targeted campaigns and personalized offers.
- **Departing:** Attempt to re-engage them by understanding the reasons for churn.
- **New:** Welcome them with incentives and tailor marketing messages to their needs.


## Contributions

Contributions to this project are welcome! Feel free to open issues or submit pull requests.
