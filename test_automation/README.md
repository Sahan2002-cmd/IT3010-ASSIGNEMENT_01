# IT3040 – ITPM Assignment 1
**Option 1: Transliteration Accuracy Testing**
**Student ID:** IT23837676
**GitHub Repository:** https://github.com/Sahan2002-cmd/IT3010-ASSIGNEMENT_01

## Overview
This project tests the accuracy of the Chat Sinhala transliteration function available at [https://www.pixelssuite.com/chat-translator](https://www.pixelssuite.com/chat-translator) using Playwright automation.

## Prerequisites
- Python 3.11 or 3.12
- Google Chrome (recommended)

## Installation

### 1. Install Python dependencies
```
python -m pip install playwright openpyxl
```

### 2. Install Playwright browsers
```
python -m playwright install
```

## Running the Tests

Navigate to the project folder in Command Prompt or VS Code terminal:
```
cd "D:\test_automation (1)"
```

Then run:
```
python test_automation\test_automation.py --excel "test_automation\Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open --input-col "Input" --expected-col "Expected output" --actual-col "Actual output" --status-col "Status"
```

## Project Structure
```
test_automation/
├── test_automation.py         # Playwright automation script
└── IT23837676.xlsx  # Test cases with results
```

## Test Results
Results are saved automatically in the Excel file under **Actual output** and **Status** columns after running the script.
