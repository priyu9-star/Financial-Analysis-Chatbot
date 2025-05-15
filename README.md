💬 Financial Analysis Chatbot

An interactive Financial Analysis Chatbot built using Python, Flask, NLP, and React, designed to provide users with real-time stock insights, company performance summaries, and financial trend analysis. It integrates the Alpha Vantage API to deliver accurate and current market data through natural language conversations.

🚀 Tech Stack
Backend: Python, Flask, Natural Language Processing (NLP)


🎯 Features

🧠 NLP-Powered Interface – Understands and processes user queries in natural language
📊 Real-Time Stock Insights – Retrieves current market data and stock performance
🏢 Company Performance Summaries – Provides earnings, revenue, and other financial metrics
📈 Trend Analysis – Analyzes past data to identify market trends
⚛️ Interactive Frontend – Built with React for smooth user experience
🔒 Secure API Handling – Uses environment variables for API key management

Backend Setup (Flask + NLP)
bash
Copy
Edit
# Clone the repository
git clone https://github.com/priyu9-star/financial-chatbot.git
cd financial-chatbot/backend

# Create virtual environment and activate
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Add your Alpha Vantage API Key to .env
echo "ALPHA_VANTAGE_API_KEY=your_api_key_here" > .env

# Run the Flask server
python app.py
Frontend Setup (React)
bash
Copy
Edit
cd ../frontend

👩‍💻 Author

Priyanshi Jayant
🔗 LinkedIn
💻 GitHub

