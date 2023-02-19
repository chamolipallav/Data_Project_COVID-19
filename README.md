# Data_Project_COVID-19

# Data-Engineering-Project--Amazon RedShift-COVID-19 Data Lake

To be able to Run the Project in Your System Follow the Steps.

Downloade the Dataset from this link : https://registry.opendata.aws/aws-covid19-lake

Pdf file to whitepaper Amazon Redshift : [Amazon Redshift - Big Data Analytics Options on AWS.pdf](https://github.com/chamolipallav/Data-Engineering-Project-Amazon_RedShift_COVID-19-DATA-LAKE/files/10775590/Amazon.Redshift.-.Big.Data.Analytics.Options.on.AWS.pdf)


follow the below steps to Create and explore the data.

1. Create Amazon Service Account and Start understanding S3, Athena, IAM, VPC, RedShift, Glue, Crawler.
2. downlode the short quick dataset from this link: https://drive.google.com/drive/folders/1zSXkcJBfdaPZpiRu9xPXW2-KyOCNy0r- to AMAZON S3 Bucket. and uplode the dataset to S3 bucket.
3. Create S3 Buckets before uploading.
4. Create IAM Roles for the S3-Athena access, S3-Glue access.
5. Create Crawlers for all the dataset. Output will look like this.

![Screenshot 2023-02-19 at 11 49 57 am](https://user-images.githubusercontent.com/100506830/219909361-5fc3706f-7829-44de-ae5b-b4c924a2b4a2.png)

6. Uploded datasets in S3 will look like this

![Screenshot 2023-02-19 at 11 51 52 am](https://user-images.githubusercontent.com/100506830/219909370-d85c406e-455e-4241-b9e8-03002189ef58.png)
7. After creating Crawlers for all the datasets. Refresh the data in Athena to Query Processing. output look like this !
[Screenshot 2023-02-19 at 12 47 29 pm](https://user-images.githubusercontent.com/100506830/219909424-299b2395-4323-47fd-852f-d6378080c150.png)

8. Create data Models on. Draw.io using the Athena Query Editor to Generate DDL for the tables. the Data Model will be like this :

![Screenshot 2023-02-19 at 12 37 45 pm](https://user-images.githubusercontent.com/100506830/219909457-07619868-fab9-44d6-8d1f-7e8257f10c91.png)

9.
