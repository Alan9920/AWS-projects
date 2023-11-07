In this project I displayed a dataset on AWS Quicksight using the data stored in S3 bucket

I first found a free dataset that I can use to store in a S3 bucket

Once I found the dataset I downloaded it,made a S3 bucket
a S3 bucket stores various types of files and folders in S3 terms those are called objects. I created a bucket called "quicksight-data-analysis"
I had to name it like that because S3 supports global buckets which means that each bucket name must be unique across all AWS accounts.
![1](https://github.com/Alan9920/AWS-projects/assets/83747562/aefa602a-1f78-4a30-8f04-f4311ccd6b91)

After that I created a "manifest.JSON" file this file is important as it has the loacation of the bucket that has the ".csv" file we want to analyze and visualise  
![image](https://github.com/Alan9920/AWS-projects/assets/83747562/fff9b9de-1e8e-421a-912f-2c9b91e6e38e)

I uploaded the ".JSON" and ".csv" file to the bucket after and copied the S3 URL of the ".JSON" file as it will be needed later
![image](https://github.com/Alan9920/AWS-projects/assets/83747562/939e7fa4-8685-45e2-87ca-05ef2be5bd03)

I went to the AWS Quicksight which is a cloud-powered business intelligence service that displays data and information in multiple charts
added a dataset, pasted the S3 URL of the "manifest.JSON" file and added the source name
![image](https://github.com/Alan9920/AWS-projects/assets/83747562/afd117f1-550f-4c3c-b750-7a485f742487)

Now we can filter the data that we want to see and display it on a Sheet
![image](https://github.com/Alan9920/AWS-projects/assets/83747562/f2cd59b0-a383-4458-8789-06ece94db78f)


With this project I used an S3 bucket to store a dataset "Amazon-Bestseller" and use  AWS Quicksight to retrieve the object from the S3 bucket,analyze and display the dataset
