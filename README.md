# Project Overview

This Python project demonstrates how to parse receipts using Optical Character Recognition (OCR) to extract financial data automatically. Utilizing an OCR API, the script processes receipt images and converts them into structured data, including store names, addresses, itemized purchases, and totals.

# Features

Automated parsing of receipt images.
Extraction of detailed data: merchant name, address, items, prices, subtotals, and taxes.
Supports multiple receipt formats and languages (limitations apply to non-Latin scripts).
How It Works

The script sends receipt images to an OCR API, then processes and structures the JSON response. It extracts key information like items purchased, their prices, and the total amount spent.

# Requirements

Python 3.x
requests library for API calls
Internet access for API interaction

#Usage

Install required Python packages.
Add your receipt images in the designated folder.
Run the script to process images and extract data.

#Limitations

Performance depends on the OCR API's accuracy.
May not fully recognize non-Latin scripts.
