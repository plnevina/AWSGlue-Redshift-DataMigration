# AWSGlue-Redshift-DataMigration
![Data Pipeline Diagram](./images/projectstr.jpg)


-In this pipeline,Initially an AWS crawler is setup to crawl data from S3 to Data Catolog Tables.

-Later an AWS Glue Job is created with specified connections and IAM roles to establish connection to Redshift.

-Once the data crawled,the Glue Job is started to load into Redshift Database with specified schemas.The Job created is using Visual ETL Job.
