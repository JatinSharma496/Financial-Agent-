# Financial Agent and Web Search Assistant

This project is an AI-powered tool that combines multiple intelligent agents to perform financial analysis and web search. The agents utilize powerful Large Language Models (LLMs) for tasks such as retrieving financial data, summarizing analyst recommendations, and conducting web searches for real-time information. The project is built using the **Phi framework** and is designed for seamless interaction via a web-based playground application.

## Features

- **Web Search Agent**: 
  - Fetches real-time information from the web using the DuckDuckGo API.
  - Provides detailed responses with reliable sources.

- **Financial Agent**: 
  - Retrieves stock prices, analyst recommendations, company news, and stock fundamentals using the YFinance API.
  - Outputs information in tabular format for easy readability.

- **Multi-Agent Collaboration**: 
  - Combines the Web Search and Financial Agents to provide comprehensive insights.

- **Interactive Playground**:
  - A user-friendly web-based interface for interacting with the agents.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/financial-agent.git
   cd financial-agent
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up environment variables:
   - Create a `.env` file in the project root.
   - Add your Phi API key to the `.env` file:
     ```env
     PHI_API_KEY=your_phi_api_key
     ```

4. Run the application:
   ```bash
   python main.py
   ```

## Usage

- Open the web application in your browser.
- Interact with the agents by entering your queries (e.g., "Summarize analyst recommendations for Nvidia" or "Find the latest news about renewable energy").

## Technologies Used

- **Programming Language**: Python
- **Framework**: Phi Framework
- **APIs**: 
  - DuckDuckGo (Web Search)
  - YFinance (Financial Data)
- **LLMs**: Groq-based models (e.g., llama3-groq-70b)
- **Environment Management**: `dotenv`
- **Web Application**: Playground provided by the Phi framework

## Project Structure

```plaintext
financial-agent/
├── financial_agent.py   # Main script to run the agents
├── requirements.txt     # Project dependencies
├── .env                 # Environment variables (ignored in version control)
├── README.md            # Project documentation
```

## Tags

- AI Agents
- Financial Analysis
- Web Search
- LLM Integration
- Phi Framework
- Interactive Playground
