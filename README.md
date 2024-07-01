# Customer Segmentation Analysis

This repository contains a comprehensive analysis of a simulated customer dataset. The goal of this analysis is to identify distinct customer segments based on demographic and behavioral characteristics. This can help in developing targeted marketing strategies, improving customer satisfaction, and increasing sales.

## Dataset Overview

The dataset contains the following columns:
- `id`: Unique identifier for each customer.
- `age`: Age of the customer.
- `gender`: Gender of the customer (Male, Female, Other).
- `income`: Annual income of the customer (in USD).
- `spending_score`: Spending score (1-100), indicating the customer's spending behavior and loyalty.
- `membership_years`: Number of years the customer has been a member.
- `purchase_frequency`: Number of purchases made by the customer in the last year.
- `preferred_category`: Preferred shopping category (Electronics, Clothing, Groceries, Home & Garden, Sports).
- `last_purchase_amount`: Amount spent by the customer on their last purchase (in USD).

## Analysis Steps

1. **Data Preprocessing**: 
    - Load the dataset and handle any missing values.
    - Encode categorical variables for analysis.
  
2. **Exploratory Data Analysis (EDA)**:
    - Visualize the distribution of various features such as age, income, spending score, and purchase frequency.
    - Generate a correlation heatmap to understand the relationships between features.

3. **Clustering Analysis**:
    - Standardize the data.
    - Determine the optimal number of clusters using the Elbow Method.
    - Perform KMeans clustering and evaluate the clustering using the silhouette score.

4. **Segment Profiling**:
    - Profile each cluster based on the mean values of features.
    - Visualize the profiling of clusters to understand the characteristics of each segment.

5. **Recommendations**:
    - Provide targeted marketing strategies for each identified customer segment based on the clustering analysis.

## Files

- `customer_segmentation_analysis.ipynb`: Jupyter notebook containing the detailed analysis.

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/debjit-mandal/customer-segmentation-analysis.git
    ```

2. Navigate to the project directory:
    ```bash
    cd customer-segmentation-analysis
    ```

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter notebook:
    ```bash
    jupyter notebook customer_segmentation_analysis.ipynb
    ```

## Results

The analysis results in identifying five distinct customer segments, each with unique characteristics and behaviors. Detailed recommendations are provided for targeted marketing strategies based on these segments.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
