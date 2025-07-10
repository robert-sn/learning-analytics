# Chicago crimes

This project uses publicly available chicago crimes data from Google BigQuery to perform time-series analysis, data visualization, and predictive modeling using Apache Spark and machine learning regressors.

## Features
- **Big Data Integration**: Uses BigQuery to access and query large datasets directly.
- **Data Cleaning and Transformation**: Handles missing values and normalizes features using PySpark.
- **Correlation Analysis**: Provides a heatmap of correlations between key features.
- **Regression Models**: Implements Linear Regression, Decision Tree, Random Forest to predict average vaccination rates.
- **Evaluation**: Calculates performance metrics (R², RMSE, and MSE) for each model.

## Prerequisites
Ensure you have the following dependencies installed before running the notebook:

- **Python 3.7 or later**
- **PySpark**
- **pandas**
- **matplotlib**
- **seaborn**
- **scikit-learn**
- **Google Cloud SDK** (for accessing BigQuery)

To install the dependencies, you can run:
```bash
pip install pyspark pandas matplotlib seaborn scikit-learn google-cloud-bigquery
```

You will also need to:
- Set up a Google Cloud project.
- Enable the BigQuery API.
- Authenticate using a service account key or the `gcloud auth application-default login` command.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/robert-sn/learning-analytics.git
   ```
2. Navigate to the project directory:
   ```bash
   cd learning-analytics
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Configure your BigQuery credentials and project details in the notebook.
5. Execute the cells sequentially to analyze the data and generate predictions.

## Dataset
This project utilizes a **public Google BigQuery dataset** that includes:

- Total of performed tests
- Total of positive cases
- Total of deaths
- Total of hospitalizations
- Total of icu
- Total of ventilators

## Results
The following table summarizes the performance of different regression models used in the project:

| Model                  | R² (%) | RMSE | MSE  |
|------------------------|--------|------|------|
| Linear Regression      | TBC    | TBC  | TBC  |
| Decision Tree          | TBC    | TBC  | TBC  |
| Random Forest          | TBC    | TBC  | TBC  |

Decision Tree achieved the highest R² (97.61%) , indicating superior predictive performance compared to other models.

## Big Data Technologies
- **Google BigQuery**: Enables querying of large datasets efficiently.
- **PySpark**: Facilitates distributed data processing and machine learning.

## License

This project is open-source and available under the [MIT License](../LICENSE).

## Contribution
Feel free to contribute to this project by creating issues or submitting pull requests.