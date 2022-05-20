
Sparkify provides music streaming to the users through their apps - the company holds songs details and the user activity data collected from the app.

Fact Table: songplays: attributes referencing to the dimension tables.

Dimension Tables: users, songs, artists and time table.

1.Create a new IAM user in your AWS account.


2.Create an IAM Role that makes Redshift able to access S3 bucket (ReadOnly)


3.Create a RedShift Cluster and get the DWH_ENDPOIN(Host address) and DWH_ROLE_ARN and fill the config file.

4.Created tables tables to store the data from S3 buckets.

5.Loading the data from S3 buckets to staging tables in the Redshift Cluster.

6.Inserted data into fact and dimension tables from the staging tables.
