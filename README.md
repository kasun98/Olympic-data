# Tokyo-Olympic-Data

![image](https://github.com/kasun98/Olympic-data/assets/63708260/531045b2-8c3d-4963-b87b-98b92ff1b4b5)

# Tokyo Olympic Data Analysis

This project entails a comprehensive analysis of the Tokyo Olympic dataset, focusing on data integration, transformation, analysis, and visualization using various Azure services and Tableau Public.

## Workflow

1. **Data Acquisition**:
   - Obtained the Tokyo Olympic dataset from Kaggle.

2. **Data Integration**:
   - Utilized Azure Data Factory for hybrid data integration.

3. **Data Storage**:
   - Stored the raw dataset in Azure Data Lake Gen2.

4. **Data Analysis**:
   - Conducted exploratory data analysis, including:
     - Checking for missing values.
     - Adjusting data types of columns.
   - Azure Databricks was employed for data analysis tasks.

5. **Data Transformation**:
   - Transformed the dataset as per the analysis findings.
   - Stored the transformed data back into Azure Data Lake Gen2.

6. **Data Synthesis**:
   - Leveraged Azure Synapse Analytics for in-depth data synthesis and insights extraction.

7. **Visualization**:
   - Developed a comprehensive dashboard using Tableau Public to summarize key findings and insights.
   -   https://public.tableau.com/views/Book1_17120794704690/Dashboard1?:language=en-US&:sid=59A8DA4A48164144A5D86E4A4B7E8451-0:0&:display_count=n&:origin=viz_share_link
  
     ![Dashboard 1](https://github.com/kasun98/Olympic-data/assets/63708260/5ed028c1-0798-4e7c-8abe-4d58d40ccfd4)


## Tools Used

- **Azure Services**:
  - Azure Data Factory
  - Azure Data Lake Gen2
  - Azure Databricks
  - Azure Synapse Analytics

- **Third-Party Tools**:
  - Tableau Public

## Repository Structure

- `data/`: Contains the Tokyo Olympic dataset.
- `notebooks/`: Includes notebooks for data analysis and transformation using Azure Databricks.
- `dashboard/`: Holds files related to the Tableau Public dashboard.


## Getting Started

To replicate the analysis or explore further:

1. Clone this repository.
2. Set up necessary Azure services and accounts.
3. Execute notebooks in `notebooks/` for data analysis and transformation.
4. Import the transformed data into Azure Synapse Analytics.
5. Use Tableau Public to create visualizations and dashboards.


