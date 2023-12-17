# Lyft-Analytics-Data-Engineering-GCP-Mage-ETL
An End to End Data Engineering project analyzing a Lyft dataset with an Analytics Dashboard in Looker

# Introduction    
The objective of this initiative is to design an end to end data analytics pipeline on Lyft data using python, GCP and Mage AI Data Pipeline tool and finally create an analytics dashboard using Looker Studio. 

# Porject Objectives

* Data Acquisition - The dataset used for this project has been acquired from the nyc.gov website on TLC trip yellow and green taxi records including fields like pick-up and drop-off times, locations, trip distances, itemized fares, rate types, payment types and driver-reported counts.

* More info on the dataset here:
  1. Website: https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
  2. Data Directory: https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf
 
* Data Modeling - Our focus is to come up with a data model by creating Fact and Dimension tables around the base data frame. First the data model will be designed in Lucid visually, and then as dataframes in the python environment.

* Transformation and ETL - After creating the data model we will need to transform the data into the proper format using Mage Ai to then also transform and load the data into the Cloud.

* Cloud Computing - Due to impracticality of handling extensive data locally, opting for cloud solutions is crucial; in this instance, GCP is our choice.

* Analytical Outputs - Construct a visual interface for obtaining responses to our earlier inquiries

# Services Employed: 

* Google Cloud Services
    * Compute Engine: The VM will be used to host a virtual compute instance to insall Mage AI and run it on the cloud for ETL processing. 
    * Cloud Storage BigQuery: This is the main data warehouse where the data will be loaded into for querying and analysis.
    * Looker Studio: Looker stands as a scalable, serverless, machine learning-infused business intelligence (BI) service tailored for cloud environments.
* Mage AI: This powerful AI tool is the perfect choice for on the fly data extraction, transformation and loading using python scripts and data frames for easy ETL design. 
 
# Data Model 

<img width="1236" alt="Screenshot 2023-12-17 at 3 37 42 PM" src="https://github.com/snehalsmalladi/Lyft-Analytics-Data-Engineering-GCP-Mage-ETL/assets/75508260/e92fe95d-a6b3-481d-a81f-f9868ee81acc">

# Framework 

![image](https://github.com/snehalsmalladi/Lyft-Analytics-Data-Engineering-GCP-Mage-ETL/assets/75508260/1cbd68b0-55b3-4f56-b221-0c51ca263456)
