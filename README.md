Big Data E-Commerce Analytics Pipeline

Overview

This project implements a big data analytics pipeline for e-commerce event data using Apache Spark, MongoDB, and Docker.

The system processes customer activity logs and generates business insights such as market basket analysis, user affinity scores, and cart abandonment detection.

Features

* Market Basket Analysis
* User Affinity Scoring
* Cart Abandonment Detection
* MongoDB Data Storage
* Product Recommendation Queries
* Dockerized Deployment

Technologies Used

* Python
* Apache Spark
* MongoDB
* Docker
* PyMongo

Project Structure

phase1/

* Market Basket Analysis
* User Affinity Analysis

phase2/

* Data Ingestion to MongoDB

phase3/

* Cart Abandonment Detection

query_demo/

* Recommendation Query Demonstration

Results

The project generates:

* Frequently purchased product combinations
* User-product affinity scores
* Cart abandonment insights
* Recommendation data stored in MongoDB



1. Start services

docker compose up -d

2. Execute project phases

python phase1/task1_1_market_basket.py

python phase1/task1_2_user_affinity.py

python phase2/ingest_phase1_to_mongo.py

python phase3/task3_cart_abandonment.py

3. Run recommendation query demo

python query_demo/query_demo.py

4. Stop services

docker compose down



Alaa Shaban
Egypt University of Informatics (EUI)
