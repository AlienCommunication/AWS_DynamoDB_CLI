# Data compression in DynamoDB using Lambda function

Before we write data  to the table. We check the length of the content . If it is longer than 35 character we simply  save the item as it is. Otherwise we compress it and store  it in binary program.

# How to run this file :

node data-compression.js
