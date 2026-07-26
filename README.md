# 💰 AI Budget Tracking Automation

An AI-powered personal finance workflow built with n8n that automatically monitors Gmail transaction alerts, extracts financial information, enriches transaction data, logs expenses into Google Sheets, and sends transaction summaries.

---

## Workflow Diagram

![Workflow](images/workflow.png)

---

## Features

- Gmail Transaction Monitoring
- AI-Powered Transaction Analysis
- Automatic Merchant Detection
- Bank Information Enrichment
- Google Sheets Expense Logging
- Email Transaction Summary
- Error Handling Workflow
- Transaction Data Normalisation

---

## Tech Stack

- n8n
- OpenAI
- Gmail API
- Google Sheets
- HTTP API
- JavaScript

---

## Workflow Process

1. Gmail receives a bank transaction alert.
2. JavaScript extracts key transaction details.
3. AI Agent classifies and structures the transaction.
4. HTTP Request enriches merchant or bank information.
5. Processed transaction is normalised.
6. Transaction is appended to Google Sheets.
7. A transaction summary is emailed to the user.
8. Errors trigger a notification workflow.

---

## Workflow Execution

![Execution](images/execution.png)

---

## Use Cases

- Personal Expense Tracking
- Budget Management
- Financial Reporting
- Automated Bookkeeping
- Bank Alert Processing
- AI Financial Assistant
