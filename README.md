# Healthcare Big Data Analytics Project

## Overview
This project focuses on the analysis of healthcare data using big data analytics techniques. We have developed a pipeline that involves cleaning the data, loading it into Kafka for streaming, processing the data using PySpark DataFrame, and finally performing analysis and visualization using NumPy and Seaborn.

## Workflow

1. **Data Cleaning:**
   - The raw healthcare dataset undergoes preprocessing to handle missing values, outliers, and inconsistencies.

2. **Kafka Producer:**
   - Cleaned data is loaded into Kafka for streaming using a producer. Kafka ensures efficient handling of data streams.

3. **Kafka Listener:**
   - A Kafka listener is deployed to subscribe to the data stream and retrieve data as it becomes available.

4. **Data Processing with PySpark:**
   - Data from Kafka is consumed and loaded into PySpark DataFrames for scalable and distributed processing.
   
5. **Analysis with PySpark:**
   - Utilizing the power of PySpark, various analytics tasks such as descriptive statistics, clustering, and predictive modeling are performed on the dataset.

6. **Visualization with NumPy and Seaborn:**
   - Results from PySpark analysis are visualized using NumPy arrays and Seaborn plots to gain insights and make data-driven decisions.

## Usage

1. **Data Preparation:**
   - Ensure the raw healthcare dataset is available.
   - Preprocess the dataset to handle missing values, outliers, and inconsistencies.

2. **Kafka Setup:**
   - Set up Kafka environment with producers and listeners configured to handle data streams.

3. **PySpark Environment:**
   - Install and configure PySpark environment to process data efficiently.

4. **Analysis and Visualization:**
   - Run PySpark scripts to perform analysis on the data.
   - Utilize NumPy and Seaborn for visualization of insights derived from the analysis.

## Dependencies

- Apache Kafka
- Apache Spark with PySpark
- NumPy
- Seaborn

## Contributors

- [Sravanthi Thukivakam]
- [Balaji Gadi]
- [Jagadish Gollapalli]
- [Shabna Shaik]
   
## Support

For any inquiries or issues, please contact [sravanthithukivakam@gmail.com].
