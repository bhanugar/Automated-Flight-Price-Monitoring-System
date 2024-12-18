# Automated Flight Price Monitoring System

## Overview
This project is a cloud-based solution for tracking real-time flight prices and sending alerts when prices drop below a user-defined threshold. The system uses Azure services to automate data retrieval, storage, analysis, and notification.

## Features
- **Automated Data Retrieval:** Fetches flight price data from an API at regular intervals.
- **Data Storage:** Stores flight data in Azure Blob Storage for consistency and traceability.
- **Price Monitoring:** Analyzes flight prices using Azure Functions.
- **Email Alerts:** Sends email notifications using Azure Logic Apps when prices meet the threshold.

## Technologies Used
- **Azure Blob Storage:** For storing flight data.
- **Azure Functions:** For analyzing ticket prices.
- **Azure Logic Apps:** For managing email notifications.
- **Python:** For writing serverless function logic.
- **Sample Dataset:** Used due to API limitations.

## Architecture
![System Architecture](architecture-diagram/architecture.png)

## How It Works
1. **Data Retrieval:** Azure Functions pull flight price data from an API or dataset.
2. **Data Storage:** The retrieved data is stored in Azure Blob Storage.
3. **Price Monitoring:** Azure Functions analyze the data and check for price thresholds.
4. **Notification:** Azure Logic Apps send email alerts when conditions are met.

##Conclusion
This project demonstrates the integration of Azure services to create a practical, serverless solution for flight price monitoring and alerting. It highlights the potential of cloud automation in consumer-focused applications.
