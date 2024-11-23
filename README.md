# Kakfa-Stock-Market-Data-Pipeline
Stock market data pipeline(not using Stock Market API but using a csv data file)  using Apache Kafka, Amazon EC2, Amazon S3 , AWS Glue and Athena

# Real-Time Stock Market Data Pipeline with Apache Kafka

This project demonstrates a real-time data pipeline to ingest stock market data using **Apache Kafka**, store the data in **Amazon S3**, and query it with **AWS Athena** after cataloging it with **AWS Glue**.

## Project Architecture

1. **Apache Kafka**: Captures and streams real-time stock market data.
2. **Python Kafka Producer**: Sends stock market data to a Kafka topic.
3. **Kafka Consumer**: Reads the data from the Kafka topic and writes it to an S3 bucket.
4. **AWS Glue**: Creates a catalog for the data stored in S3.
5. **AWS Athena**: Allows querying the data for analytical purposes.

---

## Prerequisites

### Tools and Technologies
- Apache Kafka (with Zookeeper)
- Python (3.8+)
- AWS S3
- AWS Glue
- AWS Athena


### AWS Configuration
- S3 bucket for data storage
- IAM role with access to S3, Glue, and Athena
- AWS CLI configured on your system

---
Reference used: Darshil Parmar Stock Market Real time Data Analysis Project

