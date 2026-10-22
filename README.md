# Claims Processing Pipeline

## What does this project do? 
- This project is intended to be a serverless pipeline on AWS that ingests medical claims into a normalized PostgreSQL database, checks eligibility and prices them, scores them for anomalies, and serves the results through a read API

## What data is being used for this project?
- This project runs entirely on synthetically generated data

## Tech Stack Overview
- Python 
- PostgreSQL
- AWS Services: S3, Lambda, SQS, Step Functions, RDS, API Gateway, CloudWatch