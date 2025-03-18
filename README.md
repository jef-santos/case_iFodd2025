# Case iFood 2025

## Installation
This project utilizes Python 3 and requires PySpark due to the data volume. The additional packages used in the analysis are: pandas, seaborn, matplotlib, numpy, scipy, pyspark ,statsmodels

## Downloading the Data

To download the necessary files, follow these steps:
1. Clone the repository to your local machine:
```
git clone https://github.com/jef-santos/case_iFodd2025.git
cd case_iFodd2025
```

2. Navigate to the bases folder and run the following commands based on your operating system:

**MacOS and Linux:**
```
cd bases
curl -C - -O "https://data-architect-test-source.s3-sa-east-1.amazonaws.com/order.json.gz"
curl -C - -O "https://data-architect-test-source.s3-sa-east-1.amazonaws.com/consumer.csv.gz"
curl -C - -O "https://data-architect-test-source.s3-sa-east-1.amazonaws.com/restaurant.csv.gz"
curl -C - -O "https://data-architect-test-source.s3-sa-east-1.amazonaws.com/ab_test_ref.tar.gz"
gunzip order.json.gz
gunzip consumer.csv.gz
gunzip restaurant.csv.gz
gunzip ab_test_ref.tar.gz
```
**Windows:**
```
cd bases
curl.exe -C - -O "https://data-architect-test-source.s3-sa-east-1.amazonaws.com/order.json.gz"
curl.exe -C - -O "https://data-architect-test-source.s3-sa-east-1.amazonaws.com/consumer.csv.gz"
curl.exe -C - -O "https://data-architect-test-source.s3-sa-east-1.amazonaws.com/restaurant.csv.gz"
curl.exe -C - -O "https://data-architect-test-source.s3-sa-east-1.amazonaws.com/ab_test_ref.tar.gz"
tar -xvf order.json.gz
tar -xvf consumer.csv.gz
tar -xvf restaurant.csv.gz
tar -xvf ab_test_ref.tar.gz
```

## Project Motivation

The objective of this project is to analyze a fictional case study focused on evaluating the performance of an A/B test. The study explores key insights from the test results and provides recommendations based on the analysis.

## Files Description
The repository contains three main files:
- **2025_CaseIfood_Teste A_B**: Contains the complete analysis and reasoning behind the results.
- **2025_CaseIfood_Teste A_B - Apresentação**: Highlights key insights and recommendations.
- **2025_CaseIfood_Teste A_B - Simulador**: A tool to simulate the return on investment of the proposed changes.
