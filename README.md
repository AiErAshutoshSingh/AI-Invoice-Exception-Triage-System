# AI-Powered Accounts Payable Exception Triage System

## Overview

The AI-Powered Accounts Payable (AP) Exception Triage System is an intelligent finance automation solution designed to identify, classify, and prioritize invoice exceptions in Accounts Payable workflows. The system helps finance teams reduce manual effort, improve invoice processing efficiency, and gain actionable insights through automated exception detection and analytics.

## Features

* Automated Invoice Exception Detection
* Overdue Invoice Identification
* Duplicate Invoice Detection
* Missing Payment Validation
* High-Value Invoice Monitoring
* Priority-Based Triage Engine
* Vendor Risk Analysis
* Invoice Aging Analysis
* Interactive Dashboard using Plotly
* Web-Based Interface using Gradio
* Exportable Excel Reports
* AI-Ready Architecture for LLM Integration

## Dataset Structure

The project uses Accounts Payable transaction data with the following fields:

| Column      | Description                |
| ----------- | -------------------------- |
| APID        | Unique Accounts Payable ID |
| Vendor      | Vendor Name                |
| InvoiceDate | Invoice Creation Date      |
| DueDate     | Invoice Due Date           |
| Amount      | Invoice Amount             |
| Currency    | Invoice Currency           |
| Status      | Invoice Status             |
| PaidDate    | Payment Date               |
| Terms       | Payment Terms              |

Example:

| APID    | Vendor     | Amount  | Status  |
| ------- | ---------- | ------- | ------- |
| AP10000 | BluePrints | 344.25  | Open    |
| AP10001 | BluePrints | 3298.38 | Partial |

## Exception Categories

The system automatically identifies:

* Duplicate Invoice
* Overdue Invoice
* Missing Payment Date
* High Value Invoice
* Normal Transactions

## Tech Stack

* Python
* Pandas
* NumPy
* Plotly
* Gradio
* OpenPyXL
* Google Colab

## Project Workflow

1. Upload AP Dataset
2. Clean and Validate Data
3. Detect Invoice Exceptions
4. Assign Priority Levels
5. Generate Resolution Recommendations
6. Perform Vendor Risk Analysis
7. Analyze Invoice Aging
8. Visualize Results via Dashboard
9. Export Exception Reports

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/ap-exception-triage-system.git
cd ap-exception-triage-system
```

Install dependencies:

```bash
pip install pandas numpy plotly gradio openpyxl
```

## Running the Project

Open Google Colab or run locally:

```python
python app.py
```

Or launch the Gradio interface:

```python
gr.Interface(...).launch()
```

## Sample Output

The system generates:

* Exception Reports
* Priority Classification
* Vendor Risk Metrics
* Aging Analysis
* Interactive Dashboards

## Future Enhancements

* Groq/OpenAI LLM Integration
* AI Root Cause Analysis
* Fraud Detection Module
* Multi-Currency Conversion
* Email Notifications
* Power BI Integration
* SQL Database Support
* Workflow Automation using Power Automate

## Business Impact

* Reduces manual invoice review effort
* Improves AP operational efficiency
* Enhances financial visibility
* Enables proactive exception management
* Supports finance process automation initiatives

## Resume Project Description

Developed an AI-powered Accounts Payable Exception Triage System that automates invoice exception detection, prioritization, and reporting. Implemented duplicate invoice detection, aging analysis, vendor risk assessment, and interactive dashboards using Python, Pandas, Plotly, and Gradio. Designed the solution to improve AP process efficiency and support intelligent finance operations.

