# AI Security Log Analyzer

## Description
An AI-powered cybersecurity tool that analyzes security logs using Python and Qwen Coder.

## Features
- Classifies logs as BENIGN, SUSPICIOUS, MALICIOUS, or UNKNOWN.
- Assigns severity scores and provides explanations.
- Processes up to 200 log entries in batches.
- Exports results in CSV and JSON formats.
- Generates Sigma-style detection rules.
- Implements prompt injection defenses.
- Supports offline testing and input validation.

## Requirements
- Python 3
- Jupyter Notebook
- OpenAI Python package
- Access to a compatible Qwen API server and API key

## How to Run
1. Download or clone this repository.
2. Open Lab6_AI_Automation_Tool_STARTER.ipynb.
3. Install the dependency using `%pip install openai`.
4. Configure the API server URL.
5. Enter your API key securely when prompted.
6. Provide a security log dataset and update LOG_FILE.
7. Run the notebook cells from top to bottom.

## Dataset Results
A total of 200 SSH authentication log entries were analyzed.

- BENIGN: 120 (60%)
- SUSPICIOUS: 70 (35%)
- MALICIOUS: 10 (5%)

## Security
API keys are entered securely using getpass.
Log entries are treated as untrusted data.
AI-generated detection rules require human review and validation before deployment.

## License
This project is licensed under the MIT License.
