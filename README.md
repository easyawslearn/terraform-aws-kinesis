# Overview terraform-kinesis

Amazon Kinesis makes it easy to collect, process, and analyze real-time, streaming data so you can get timely insights and react quickly to new information.
in this kinesis-firehose will read the kinesis stream data and process steam data in to s3 table using glue data format.

## Introduction
**This service is designed for deployment terraform**

this service will deploy aws kinesis stream,
aws kinesis firhose delivery stream,
aws glue databse and aws glue table



## Variables

**region**: (String) the region to deploy to

**app_name**: (String) the name of the application to deploy

**shard_count**: (number) The number of shards that the stream will use

**retention_period** (number) Length of time data records are accessible after they are added to the stream

**s3_bucket_arn** (String) s3 bucket arn where kinesis firehose put data

**s3_bucket_arn** (String) s3 bucket path where kinesis firehose put data


