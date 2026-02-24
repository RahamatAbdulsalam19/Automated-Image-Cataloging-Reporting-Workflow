# Automated-Image-Cataloging-Reporting-Workflow

## Project Description
Built an end-to-end automation workflow that extracts paginated image data from an external API, processes the results, stores structured outputs in Google Sheets, and sends automated email summaries.
The system handles multi-page API responses using advanced pagination logic, dynamically iterates through returned datasets, and aggregates results before triggering a final notification.

## What the system does:
Makes an authenticated API request to retrieve total item count

Automatically paginates through all result pages

Extracts image URLs and descriptions

Iterates through each record

Stores structured data in Google Sheets

Aggregates page results into a consolidated dataset

Sends an automated Gmail summary notification

## Key Capabilities:
Advanced pagination handling

API authentication and dynamic data retrieval

Iterator-based data processing

Real-time Google Sheets integration

Automated reporting via email

Scalable architecture for large datasets

## Business Use Case:
This automation eliminates manual scraping and reporting of media assets. It can be adapted for:

Product catalog ingestion

Content moderation pipelines

Media library monitoring

Stock image dataset compilation

Marketing asset tracking

## Tools Used:
Make (Integromat)

HTTP API module

Iterator & Aggregator modules

Google Sheets API

Gmail API
