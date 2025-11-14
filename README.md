# Customer Segmentation with RFM Analysis

![image](https://github.com/AylinOguz/Customer-Segmentation-with-RFM-Analysis/blob/main/rfm.png?raw=true)

## Project Overview
This project demonstrates customer segmentation for an e-commerce company using RFM (Recency, Frequency, Monetary) analysis. By segmenting customers, the company can define targeted marketing strategies for each segment to increase engagement and revenue.

## Table of Contents

- Business Problem

- Data Understanding

- Data Preparation

- RFM Metrics Calculation

- RFM Score Calculation

- RFM Segment Creation and Analysis

- Functionizing the Process


## Business Problem

An e-commerce company aims to segment its customers and develop marketing strategies tailored to each segment. The dataset "https://archive.ics.uci.edu/dataset/502/online+retail+ii " contains sales data from an online retail store based in the UK, covering the period from 01/12/2009 to 09/12/2011. Dataset: Online Retail II

### Variables in the dataset:

- Invoice : Invoice number. If it starts with "C", it represents a canceled transaction (return).

- StockCode : Unique product code.

- Description : Product name.

- Quantity : Number of products in the invoice.

- InvoiceDate : Invoice date and time.

- Price : Product unit price in GBP.

- Customer ID : Unique customer identifier.

- Country : Customer's country.

## Data Preparation

- Removed rows with missing Customer ID.

- Removed canceled invoices (Invoice numbers starting with "C").

- Removed observations with Monetary = 0.

## RFM Metrics Calculation

RFM metrics for each customer:

- Recency: Days since the last purchase (reference date = 2 days after the last purchase in dataset).

- Frequency: Total number of invoices per customer.

- Monetary: Total spending of each customer.
