Description

Introduction AWS Juptyer S3 Bucket 10 BG Data - user, business, analyze

Amazon EMR and Hadoop provide a variety of file systems that you can use when processing cluster steps. You specify which file system to use by the prefix of the URI used to access the data. For example, s3://DOC-EXAMPLE-BUCKET1/path references an Amazon S3 bucket using EMRFS. The following table lists the available file systems, with recommendations about when it's best to use each one.

You must read your Yelp data from S3. In order to do so, you can use my publicly available bucket which contains all the data needed for your analysis. Your Analysis.ipynb file must demonstrate that the data is being read from S3 - this is largely as simple loading your DataFrame like so: df = spark.read.json('s3:// cis9760-yelpdata/*.json') Note: If you are not able to read the file from my S3 bucket, please go to the Kaggle, download the data, and upload it to your own S3 bucket.

Cluster

Cluster

Notebook
