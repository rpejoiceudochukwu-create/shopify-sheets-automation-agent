
# Shopify-Sheets Automation Agent

Python agent that connects Shopify REST API to Google Sheets - auto-syncs orders.

## Features
- Fetches Shopify orders every 5 min
- Maps customer, products, payment status
- Writes to Google Sheets real-time
- Handles rate limits + retries
- No duplicate rows

## Stack
Python, Shopify REST API, Google Sheets API v4, OAuth2

## Setup
pip install shopify-api google-api-python-client
export SHOPIFY_KEY=your_key
python main.py

## Use Case
For store owners who hate manual CSV export. Saves 10hrs/week.

Author: Joy O. - Python API Specialist
