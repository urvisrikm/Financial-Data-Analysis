Financial Data Audit & Anomaly Detection (JPMC SEP Simulation)
What is this?
I built this project to simulate how a Software Engineer at JPMC might handle large-scale transaction data. The goal was to take a "messy" list of bank transactions and automate the process of finding spending trends and flagging potential fraud without doing it manually.
How it works:
Instead of just looking for a specific dollar amount (which is too simple), I used Standard Deviation to create a statistical threshold. This means the script "learns" what a normal expense looks like for the account and only creates an alert if a transaction is mathematically suspicious.
Key Features:
Automated Data Synthesis: Used the Pandas library to pull in CSV data and clean it up for analysis.
Smart Categorization: I wrote logic to automatically tag transactions (like Rent, Groceries, or Shopping) so you can see where the money is actually going.
Security & Risk: Designed a "Security Audit" layer that flags high-risk transactions for review, which hits the JD's focus on technical troubleshooting and secure code.
Reducing Manual Toil: By automating the reporting, I cut out the need for manual data entry, showing how I apply automation to the SDLC.
Tech Used:
Python 3 (The core logic)
Pandas & NumPy (For the heavy data lifting)
Google Colab (For development and testing)
