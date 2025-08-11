# 💹 Multi-Agent Financial & Web Analysis Tool

A Streamlit-based application that combines the power of Groq AI agents to search the web, fetch the latest news, and analyze financial data in real time.
It integrates multiple tools, Google Search, DuckDuckGo, and Yahoo Finance, to provide structured, source-backed insights.

# 🚀 Features

Web Agent - Searches the web for general information using DuckDuckGo.
News Agent - Finds the latest news in English & French using Google Search.
Finance Agent - Retrieves stock prices, analyst recommendations, fundamentals, and company info from Yahoo Finance.
Multi-Agent Team Mode - Combines News & Finance agents for comprehensive results.
Clean, structured output - Uses tables and source links for better readability.

# 🛠️ Tech Stack

Python
Streamlit
Groq AI Models
DuckDuckGoTools
GoogleSearchTools
YFinanceTools
python-dotenv

# 📦 Installation

Clone this repository
git clone https://github.com/yourusername/multi-agent-finance-tool.git
cd multi-agent-finance-tool

# Create and activate a virtual environment
python -m venv myenv
myenv\Scripts\activate    # Windows
source myenv/bin/activate # Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Create a .env file and add:
GROQ_API_KEY=your_groq_api_key_here

Run the app:
# streamlit run multiagents.py
Then open your browser at the URL provided by Streamlit.
