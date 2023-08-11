# EpChecker

## Description
`EpChecker.py` is an automated tool designed for tracking and accounting "debts" in posts within episodes of forum role-playing games (MyBB\RusFF). The script uses Selenium for web page automation and SQLite3 to store data in a local database.

## Main Features
1. Automated login to the forum.
2. Data extraction from episodes on the forum, including posts, authors, and other relevant information.
3. Storing the extracted data in a database.
4. Performing analytical operations based on the collected data to track post "debts" and participation in episodes.

## Usage
To utilize `EpChecker.py`, follow these steps:
1. Ensure all required libraries are installed: Selenium, SQLite3, Docx, and others.
2. Execute the `EpChecker.py` script.
3. After the script completes, inspect the database for an analysis of the gathered data.

## Notes
- The code contains hardcoded login credentials and URLs. It's recommended to replace them with actual values or use an external configuration file to store sensitive information before usage.
- A suitable driver for Selenium, corresponding to your browser, is required for correct operation.
