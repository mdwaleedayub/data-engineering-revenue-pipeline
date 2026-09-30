# data-engineering-revenue-pipeline
Daily Revenue Data Pipeline

Business Question

Build a reliable data pipeline that processes orders, payments, and refunds and produces a daily revenue report.

Objective

The pipeline will eventually:

Ingest raw data
Validate the data
Clean and stage the data
Transform the data using SQL
Calculate daily gross revenue, refunds, and net revenue
Validate the result using control totals
Handle duplicate inputs, corrections, late refunds, and pipeline failures
Source Tables
orders
order_items
payments
refunds
Final Output

A daily revenue table containing:

business_date
gross_paid_amount
refunded_amount
net_revenue



Project Goal

Build this pipeline as a production-style Data Engineering project that can be explained and demonstrated in interviews.
