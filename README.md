# AI-Powered Data Analyst Automation using n8n

## Project Overview

An automated data analytics workflow built using n8n, Google Gemini, JavaScript, and Gmail. The project processes sales data received through email, validates the dataset, calculates key business metrics, generates AI-powered insights, and delivers a formatted sales analysis report via email.

## Key Features

The workflow automatically monitors incoming emails and extracts CSV attachments for analysis. It validates the dataset to identify missing fields, empty values, non-numeric revenue, and invalid quantities. Google Gemini assists in identifying potential duplicates, inconsistent values, invalid dates, suspicious outliers, and possible data-cleaning recommendations.

The system calculates key performance indicators, including total revenue, total profit, total quantity, total records, and average revenue per order. It also analyzes revenue by region, product, month, sales channel, and salesperson. Based on the calculated metrics, Google Gemini generates an executive summary with business performance insights and recommendations. Finally, the workflow creates a formatted HTML sales report and automatically sends it to the original email sender.

## Technologies Used

**n8n** for workflow automation, **Google Gemini 2.5 Flash** for AI-powered data analysis and report generation, **JavaScript** for data validation and KPI calculations, and **Gmail** for email integration and automated report delivery. CSV, JSON, and HTML are used for data processing and report formatting.

## Objective

The objective of this project is to streamline the data analysis and reporting process by combining traditional data processing with AI-powered insights and workflow automation, reducing manual effort and making business information easier to understand.

**Author:** Gautam Mathur

**GitHub:** https://github.com/gaaautaammathur
