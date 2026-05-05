ITPM Assignment 1 – Transliteration Accuracy Testing (Playwright Automation)
This repository contains the automation project for IT3040 – ITPM Semester 1 Assignment 1, focused on testing the accuracy of Singlish to Sinhala transliteration using Playwright.

Objective
The goal of this project is to evaluate how accurately the system converts chat-style Singlish inputs into Sinhala output using the tool:
https://www.pixelssuite.com/chat-translator
This automation framework:
•	Executes test cases automatically using Playwright
•	Captures actual outputs from the application
•	Validates results against expected outputs
•	Updates results in an Excel file


Prerequisites
Make sure you have the following installed:
•	Python 3.11 or 3.12
•	Google Chrome (recommended)
•	pip (Python package manager)

Installation Steps
Install Dependencies
Run the following commands inside the project folder:
pip install -U pip
pip install playwright openpyxl
playwright install


How to Run the Automation
run:

python test_automation.py --excel " sandil-itpm/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open


Author
N.A.A.S Nishshanka
