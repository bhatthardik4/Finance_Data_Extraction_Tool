# 📈 Financial Data Extraction Tool

This is a simple web app built with Streamlit and OpenAI that extracts structured financial data from unstructured news articles.



## ✨ Features

* Paste in any financial news article.
* Uses OpenAI's GPT models to read the text and extract key financial data.
* Displays the extracted information in a clean, simple table.
* Extracts the following fields:
    * Company Name
    * Stock Symbol
    * Revenue
    * Net Income
    * EPS (Earnings Per Share)

---

## 🚀 How to Run This Project

Follow these steps to get the project running on your local machine.

### 1. Clone the Repository

```bash
git clone [https://github.com/YourUsername/financial-data-extraction-tool.git](https://github.com/YourUsername/financial-data-extraction-tool.git)
cd financial-data-extraction-tool
(Remember to replace YourUsername with your actual GitHub username!)

2. Create a Virtual Environment
It's highly recommended to use a virtual environment.

Bash

# Create the environment
python3 -m venv .venv

# Activate it
source .venv/bin/activate
3. Install Dependencies
This project uses a requirements.txt file to manage packages.

Bash

# Install all required packages
python3 -m pip install -r requirements.txt
4. Set Up Your API Keys
You must create a .env file to securely store your OpenAI API key.

Create a file named .env in the main project folder.

Add your API key to this file:

OPENAI_API_KEY="sk-..."
5. Run the Streamlit App
Now you are ready to start the web server.

Bash

streamlit run main.py
Your browser will automatically open with the running app.



