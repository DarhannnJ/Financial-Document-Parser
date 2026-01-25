# 🛡️ Bank Fraud Detection System (Telegram Bot)

A secure automated system for parsing bank statements (PDF) and detecting suspicious transactions in real-time. Designed to help users monitor their financial security via a simple Telegram interface.

## ⚡ Key Capabilities

* **PDF Parsing Engine:** Extracts transaction data from unstructured bank statements using `pdf_parser.py`.
* **Fraud Detection Algorithm:** Analyzes spending patterns and flags anomalies (e.g., rapid high-value transfers, unfamiliar merchants) via `fraud_check.py`.
* **Secure Logging:** Maintains a local SQLite database of verified transactions for history tracking.
* **Alert System:** Instantly notifies the user via Telegram when a potential threat is detected.

## 🛠 Tech Stack

* **Python 3.10+**
* **Aiogram** (Interface)
* **PyPDF2 / PDFMiner** (Document processing)
* **SQLite** (Data storage)
* **Pandas** (Data analysis)

## 🚀 How to Run

1.  Clone the repository.
2.  Install requirements:
    ```bash
    pip install -r requirements.txt
    ```
3.  Set up your environment variables in `.env` (Token, Admin ID).
4.  Run the bot:
    ```bash
    python main.py
    ```
