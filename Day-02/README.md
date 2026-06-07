# S3 Bucket Cost Optimizer

## Overview

This project analyzes S3 bucket metadata from a JSON file and identifies opportunities for storage cost optimization.

## Features

* Prints bucket summary
* Detects large unused buckets
* Generates cost reports by region and team
* Recommends cleanup operations
* Creates deletion queue
* Identifies Glacier archival candidates

## Assumptions

The provided JSON file did not contain:

* Last accessed timestamp
* Storage cost information

Therefore:

* Bucket age was calculated using the `createdOn` field.
* S3 cost was estimated using $0.023 per GB.

## Technologies Used

* Python
* JSON
* Datetime Module
* Collections Module

## Key Learnings

* JSON Parsing
* Cloud Cost Optimization
* SRE Automation
* Resource Analysis
* Reporting and Cleanup Strategy

