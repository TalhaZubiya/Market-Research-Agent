# <img src="https://cdn.simpleicons.org/n8n/EA4B71" width="28" alt="n8n"> Market Research Agent

<p align="center">
  <img src="https://img.shields.io/badge/n8n-Workflow-EA4B71?style=for-the-badge&logo=n8n&logoColor=white" alt="n8n">
  <img src="https://img.shields.io/badge/AI-Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Gemini">
  <img src="https://img.shields.io/badge/Market%20Research-Automated-7C3AED?style=for-the-badge" alt="Market Research">
  <img src="https://img.shields.io/badge/SerpAPI-Google%20Maps-34A853?style=for-the-badge&logo=googlemaps&logoColor=white" alt="SerpAPI">
  <img src="https://img.shields.io/badge/Gmail-Report%20Delivery-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail">
</p>

<p align="center">
  An AI-powered n8n automation that collects local business data, analyzes customer reviews, identifies market patterns, and generates professional market research reports automatically.
</p>

---

## Overview

Market Research Agent is an AI-powered automation built with **n8n** for local market and competitor research.

The workflow collects business information from Google Maps search results, retrieves available customer reviews, structures and aggregates the collected data, and passes it to an AI Agent powered by Google Gemini.

The AI Agent analyzes the collected dataset and generates an evidence-based market research report covering competitors, customer feedback, market patterns, potential opportunities, recommendations, and research limitations.

The final report is automatically delivered to the requested email address through Gmail.

---

## What It Does

* Collects local business information from Google Maps results
* Retrieves available customer reviews
* Structures and cleans business and review data
* Aggregates multiple business records
* Uses Google Gemini for market analysis
* Identifies customer feedback patterns
* Performs competitor analysis
* Detects potential market gaps and opportunities
* Generates data-driven recommendations
* Creates a professional HTML market research report
* Automatically delivers the report through Gmail

---

## Workflow

<p align="center">
  <img src="screenshots/workflow-overview.png" alt="Market Research Agent Workflow" width="100%">
</p>

### Workflow Flow

```text
User Input
    ↓
Google Maps Search
    ↓
Business Data Extraction
    ↓
Review Collection
    ↓
Data Cleaning & Structuring
    ↓
Data Aggregation
    ↓
AI Market Analysis
    ↓
Professional Report Generation
    ↓
Gmail Delivery
```

---

## AI Market Analysis

The AI Agent analyzes the collected dataset and generates a structured market research report.

### Executive Summary

A concise overview of the collected market data and major observations.

### Market Overview

Analysis of business count, ratings, review volume, pricing information, categories, and noticeable patterns.

### Competitor Analysis

Comparison of available business information, ratings, reviews, pricing, locations, websites, and customer feedback.

### Customer Review Analysis

Identification of recurring positive feedback, complaints, customer expectations, service patterns, and customer experience issues.

### Market Gaps & Opportunities

Potential opportunities identified from repeated customer complaints, unmet needs, underrepresented services, and observable competitor differences.

### Actionable Recommendations

Practical recommendations connected directly to findings in the collected dataset.

### Data Limitations

Clear explanation of sample size, review coverage, missing information, geographic limitations, and other research constraints.

---

## Generated Report

The final report is formatted as a professional HTML email and delivered automatically through Gmail.

**[View Full Market Research Report](output/02-full-report.pdf)**

---

## Key Technologies

<p align="center">
  <img src="https://cdn.simpleicons.org/n8n/EA4B71" width="42" alt="n8n">
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/google/4285F4" width="42" alt="Google">
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/gmail/EA4335" width="42" alt="Gmail">
  &nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/javascript/F7DF1E" width="42" alt="JavaScript">
</p>

* **n8n** — Workflow automation and orchestration
* **SerpAPI** — Google Maps business data collection
* **Google Gemini** — AI-powered market analysis and report generation
* **JavaScript** — Data processing and transformation
* **Gmail** — Automated report delivery

---

## Data & Analysis Approach

The workflow is designed to keep the generated research grounded in the collected data.

The AI Agent is instructed to:

* Use only the provided research data
* Avoid inventing statistics or business information
* Distinguish observed facts from analytical insights
* Treat collected businesses as a sample rather than the complete market
* Use actual ratings, review counts, and available customer feedback
* Calculate statistics only from the provided dataset
* Clearly identify unavailable information
* Connect recommendations to observable findings
* Avoid guarantees about business success or revenue

This approach helps keep the generated report transparent and evidence-based.

---

## n8n Workflow

The complete workflow is available as an importable JSON file.

**[Download / Import the n8n Workflow](workflow/market-research-agent.json)**

Before running the workflow, configure your own credentials for the required services.

> API keys, OAuth tokens, and private credentials are not included in this repository.

---

## License

This project is licensed under the **MIT License**.

See the [LICENSE](LICENSE) file for details.

---

<p align="center">
  Built with <strong>n8n</strong> + <strong>Google Gemini</strong> for automated market research.
</p>
