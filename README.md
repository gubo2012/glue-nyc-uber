# AWS Glue Example for New York City Uber Trip Data

This is an AWS Glue example that uses New York City Uber trip data available as part of [New York City Taxi and Limousine Commission (TLC) Trip Record Data](https://registry.opendata.aws/nyc-tlc-trip-records-pds/) public dataset.

## Use AWS Glue Crawler 

This example requires the [NYC-TLC public dataset](https://registry.opendata.aws/nyc-tlc-trip-records-pds/) to be crawled using AWS Glue Crawler, as explained in [Optimizing data for analysis with Amazon Athena and AWS Glue](https://github.com/aws-samples/aws-open-data-analytics-notebooks/tree/master/optimizing-data). For the purpose of this example, it ia assumed the dataset is crawled into a Glue database named 'nyc-tlc-misc'. 

## Create AWS Glue Development Endpoint

After the data is crawled using AWS Glue Crawler, create an [AWS Glue Development Endoint](https://docs.aws.amazon.com/glue/latest/dg/console-development-endpoint.html). 

## Create AWS Glue Development Endpoint SageMaker Notebook

Create an [AWS Glue SageMaker notebook](https://docs.aws.amazon.com/glue/latest/dg/console-notebooks.html) on the AWS Glue Development Endpoint created above.

