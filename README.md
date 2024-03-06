# Email Analyzer Readme

## Introduction
This script is designed to help you analyze your emails for job-related correspondence. It utilizes the ChatGPT API to determine whether the email content indicates a job rejection, acceptance, or unrelated communication.

## Requirements
- Python 3.x
- Dependencies listed in `requirements.txt`
- Access to the ChatGPT API
- An email account accessible via IMAP

## Installation
1. Clone or download the repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Set up your ChatGPT API credentials.
4. Configure your email settings in `config.py`.

## Configuration
1. Open `config.py` in a text editor.
2. Fill in your email credentials (IMAP server, username, password).
3. Set up your ChatGPT API key.
4. Optionally, adjust other settings like email folder to check, etc.

## Usage
1. Run `python email_analyzer.py`.
2. The script will connect to your email account, retrieve unread emails, and analyze them.
3. It will print out the results indicating whether the email is related to a job rejection, acceptance, or unrelated.
4. Optionally, you can extend the script to perform further actions based on the analysis results.

## Example
```python
python email_analyzer.py
