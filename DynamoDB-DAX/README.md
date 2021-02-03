# DAX :

DynamoDB Accelerator (DAX) - Some applications needs faster response time. DynamoDB offers DynamoDB Accelerator. Dax provides in Memory Caching , Microsecond Latency. 

Benefits of Dax : Cost savings - Many Read operation will never reach to DynamoDB. Thereby reducing the Read throughput.

Read response time is in microseconds. Dax only supports eventually consistence read.

To use Dax- We use DAX Cluster.  We can create a cluster with 10 Nodes.  Two caches. Item cache, Query Cache


## Refer  to the PDF book in the same directory to understand and how to activate DAX 

# To use DAX- You will need to install Amazon DAX client and NMP Module

nmp install amazon-dax-client --save