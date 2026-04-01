# Email Header Checker

A CLI tool that analyzes `.eml` email headers and extracts authentication results including SPF, DKIM, 
DMARC and ARC.

This tool helps inspect email authentication and detect domain mismatches or suspicious header  
configurations.

## Features

- Parses `.eml` email files
- Extracts SPF authentication results
- Extracts DKIM signing domains
- Parses DMARC results and alignment
- Validates ARC authentication chains
- Detects domain relationships and mismatches
- Outputs structured JSON results

## Installation

git clone
https://github.com/Hurkins/email-header-analyzer.git

cd email-header-checker

pip install -r requirements.txt

## Example usage
On linux

./headers_checker sample.eml

On windows 
Python headers_checker sample
## Status

This is **Version 0.1** of the project.

The current version focuses on  **email header authentication analysis**

Future improvements may include:

- email body analysis
- attachment inspection
- phishing detection featuresy


## Motivation

Email authentication headers can be complex and difficult to interpret manually.

This tool was built to simplify inspection of SPF, DKIM, DMARC, and ARC authentication results directly 
from `.eml` files. 

