FCEDA Business Data Automation & Visualization

Improving Efficiency in Large-Scale Data Processing and Analysis Using Public Datasets and Cloud Computing for the Fairfax County Economic Development Authority (FCEDA)
George Mason University | MIS 462 PREP Project

#Team Members:
  * Thanh Quach
  * Amena Zaini
  * Sri Avula
  * Aalliyah Alva
  * Denis Bykov

Faculty: Dr. Brian K. Ngac
Agency: Fairfax County Economic Development Authority
#Project Overview:

Public patent datasets play a crucial role for the Fairfax County Economic Development Authority (FCEDA), helping them identify valuable insights and potential business opportunities. However, the USPTO provides multiple detailed datasets, making it challenging to efficiently extract, clean, and organize the information needed to identify companies with high-value patents.

FCEDA desires an organized, enriched, and analysis-ready dataset that consolidates relevant patent attributes and supports early-stage business outreach.

To address this need, our team developed a cloud-based ETL pipeline using AWS and an interactive Tableau dashboard to automate the ingestion, transformation, and visualization of business patent records.

#Problem Statement

Manual data processing was slowing down FCEDA’s ability to:

 * Identify high-growth potential companies or inventors.
 * Verify whether patent applications are located within Fairfax County.
 * Visualize trends over time and interface search through database.
   
#Our Solution:

We created a serverless data pipeline and business intelligence solution:

 * AWS Lambda + S3: Automates the ingestion, cleaning, and transformation of patent datasets
 * Allows users to filter by filing year, company name, Cooperative Patent Classification (CPC) and keyword
 * Output: Cleaned CSVs and real-time dashboard updates ready for use in Tableau, Salesforce, and ArcGIS
#Tech Stack:

 * R (Rstudio) 
 * Python (AWS Lambda)
 * Amazon S3
 * Tableau
 * Boto3 (AWS SDK for Python)
 * Pandas

#Demo:

 * Watch Dashboard Walkthrough (YouTube)
 * Screenshots available in [dashboard/](https://public.tableau.com/app/profile/thanh.quach4789/viz/Visualization_FCEDA_Dashboard_/MainDashboard)
