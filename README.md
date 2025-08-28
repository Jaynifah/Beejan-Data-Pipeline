DE Fundamentals Assignment - Solution.txt

BEEJAN TECHNOLOGIES CONCEPTUAL DATA PIPELINE DESIGN


Introduction
To solve the problem faced by Beejan Technologies a functional data pipeline will be designed to ensure all data is collected, cleaned/transformed and made readily accessible to analysts and business professionals.
This pipeline will be designed using the ETL pattern to ensure that the data being made available to the end users has already gone through the transformation process and is readily accessible for analytics and reporting.


Data Source & Processing
The data sources for this project (social media, website forms, call logs and SMS) is a mixture of unstructured and structured data, therefore I suggest they should be ingested using a combination of Batch Processing and Real Time Streaming (Lambda Processing/Ingestion)


Data Ingestion
Batch Processing method will be used for the structured data as this method is more efficient for reporting and in this case, will be beneficial for the Website Forms and call logs, assuming the form responses are collated in a spreadsheet.


Real Time Streaming for data sources like SMS and Social Media posts.
API’s will be used to ingest the data from sources like Social Media Platforms (Twitter, Facebook, etc).




Processing & Transformation


At this stage various data transformation and cleaning steps will be taken to ensure the data is accurate and unable.
* Handling missing values
* Removing duplicates
* Standardizing the data formats/types
* Summarizing the data by applying data aggregations
* All other steps needed to be taken to achieve clean and accurate data.


The data will be categorised based on different criteria such as, channel of complaint, reason for complaint, priority/severity and date/period of the complaint, 


Data Merging: The data from all sources will be merged into one comprehensive dataset when cleaned, and loaded into a Data Warehouse in a structured format.




Data Storage
After the ingestion process, the data from all the sources will be loaded into a Data Lake in their raw formats.


The clean data will then be stored in a Data Warehouse in a structured format after the transformation stage, easily accessible for analysis and business needs.


Data Serving


The clean, usable data will be made readily available to the BI/Analytical team and Data Scientists for querying, reporting and other business use cases.




Data Orchestration


This Data Pipeline will be automated to run outside of business hours on a weekly basis to optimize resources and maintain the scheduling of the entire process.


The Orchestration stage will also include automated data validation to ensure the quality and accuracy of the data are maintained throughout the process. 


DataOps
Monitoring tools will be automated to detect and handle any issues with the workflow ensuring the pipeline runs smoothly.


Maintaining the data quality,  reliability and accuracy and also ensuring it is readily accessible to the downstream users to access and utilise independently. 


This stage also ensures collaboration between all users of this data.




Conclusion 


The Data pipeline architecture clearly illustrates all steps needed to be taken to optimize data accessibility, analytics and reporting, from the data generation and ingestion to the transformation stage and finally making it comprehensive datasets accessible to the downstream users.
