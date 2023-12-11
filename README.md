# Big Data Capstone Project

The primary goal of this project is to leverage Big Data technology to predict stock prices of 6 major tech. companies & thus curate a solution that can be scaled to use for regularly updated sophisticated and voluminous data, to help thrive in today's dynamic financial market.

We set up a Kafka producer that fetches data from the Alpha Vantage API and publishes it to a Kafka topic. This data is then consumed by our Spark ML application, which performs real-time a prediction.

## Behind the scenes

* ETL pipelining
* Real Time Data Ingestion using APIs
* Local Kafka deployment for data streaming
* PySpark for Machine Learning
* Tableau for exploratory data analysis

## Roadmap

- [x] Data Acquisition
- [x] Pre-processing
- [x] Data Streaming (Kafka)
- [x] Prediction Engine (Spark ML) 
- [ ] Front End (Flask Web App)

## Contributors:
* Yashika Khurana
* Raj Oza

![NYU](https://logos-world.net/wp-content/uploads/2021/09/NYU-Logo.png)
