# api_vulnscan
api_vunscan is a Python script for scanning APIs for vulnerabilities. It leverages the kiterunner tool to perform URL scanning and uses eyewitness to capture screenshots for API vulnerabilities.

### Prerequisites

Make sure you have the following dependencies installed:

- Kiterunner
- Eyewitness

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/api_vunscan.git
cd api_vunscan

Usage
Command-Line Arguments

    -f or --file: File containing target URLs.
    -p or --payloads: File containing additional API payloads.

Example usage:

python api_vunscan.py -f targets.txt -p additional_payloads.txt


