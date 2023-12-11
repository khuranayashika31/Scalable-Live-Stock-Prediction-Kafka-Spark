# Big Data Capstone Project

The primary goal of this project is to leverage Big Data technology to predict stock prices of 6 major tech. companies & thus curate a solution that can be scaled to use for regularly updated sophisticated and voluminous data, to help thrive in today's dynamic financial market.

We set up a Kafka producer that fetches data from the Alpha Vantage API and publishes it to a Kafka topic. This data is then consumed by our Spark ML application, which performs real-time a prediction.

## Roadmap

- [x] Data Acquisition
- [x] Pre-processing
- [x] Data Streaming (Kafka)
- [x] Prediction Engine (Spark ML) 
- [ ] Front End (Flask Web App)

![Stock Price Prediction](https://github.com/khuranayashika31/Scalable-Live-Stock-Prediction-Kafka-Spark/assets/51834607/91706e63-aaf3-43fc-9919-19b0a5370ce5)

## Behind the scenes

* ETL pipelining
* Real Time Data Ingestion using APIs
* Local Kafka deployment for data streaming
* PySpark for Machine Learning
* Tableau for exploratory data analysis

## File contents

* kafka_commands.txt - to run Kafka locally
* p1.py - Kafka producer
* c1.py - Kafka Consumer
* SparkMLcode.ipynb - ML model (contains training on historical data & testing on new streaming data)

  "Data Acquisition scripts" folder contains:
  
* aapl.ipynb - to fetch Alpha Vantage historical data for symbol Appl
* meta.ipynb - to fetch Alpha Vantage historical data for symbol Meta
* tsla.ipynb - to fetch Alpha Vantage historical data for symbol Tsla
* msft.ipynb - to fetch Alpha Vantage historical data for symbol Msft
* googl.ipynb - to fetch Alpha Vantage historical data for symbol Googl
* ibm.ipynb - to fetch Alpha Vantage historical data for symbol Ibm


## Contributors:
* Yashika Khurana
* Raj Oza

![NYU](https://logos-world.net/wp-content/uploads/2021/09/NYU-Logo.png)
