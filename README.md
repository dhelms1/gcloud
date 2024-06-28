# What the project should do
Overall project is aimed towards getting experience with Google Cloud Platform (GCP) tools. This mainly focuses on integrating a data lake with a data warehouse, cleaning data using PySpark, and training / deploying a machine learning model using the processed data. *Dataset is still to be determined, but should be on the larger size given the tools we are using.*

### 1. Environment
- Create GC Projecct
- Enable Required APIs (BigQuery, Cloud Storage, Pub/Sub, Dataflow APIs).

### 2. Data Collection/Store
- Gather raw data using compute instance + upload to GCS (**data lake**).
- Create GCS bucket for raw data.

### 3. Data Processing
- Use PySpark to extract data from GCS - clean and transform data.
- Load cleaned data into BigQuery (**data warehouse**).

### 4. Modeling
- Use BigQuery SQL to explore and preprocess data, train/test splits.
  - Queries for feature engineering or normalization   
- Use BigQuery ML to train model on preprocessed data
- Use BigQuery ML evaluation metrics + tune.

### 5. Predicting
- Use BigQuery ML to deploy model and make new predictions.
- Save predictions back to BigQuery.

### 6. Visualization
- Connect BigQuery to Google Data Studio.
- Create charts, graphs, and tables to visualize the data and predictions.
- Publish dashboard?

