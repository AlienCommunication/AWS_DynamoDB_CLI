# Data compression in DynamoDB using Lambda function

Before we write data  to the table. We check the length of the content . If it is longer than 35 character we simply  save the item as it is. Otherwise we compress it and store  it in binary program.

# How to run  files :

- data-compression.js file

node data-compression.js

- Large-items-s3.js

**For Large-items-s3.js make sure you have already created S3 bucket and Go to IAM(users) and add permission to your S3 buckets before running this file**

node large-items-s3.js
