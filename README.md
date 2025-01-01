# Finance-Agent

This project showcases a dynamic multi-agent AI application that integrates financial analytics and web search capabilities. Built using the **phi** framework and advanced AI models, this application is designed for financial analysis, data retrieval, and knowledge exploration with an interactive playground interface.

## Features

### 1. **Financial AI Agent**
- Provides stock price insights.
- Summarizes analyst recommendations.
- Shares company fundamentals.
- Displays the latest company news.
- Data is presented in easy-to-read tables.

### 2. **Web Search Agent**
- Retrieves web-based information using DuckDuckGo.
- Ensures sources are always included.
- Utilizes markdown formatting for clean and readable results.

### 3. **Multi-Agent Collaboration**
- Combines the capabilities of the Financial AI Agent and Web Search Agent.
- Executes complex queries by leveraging both agents seamlessly.

### 4. **Interactive Playground**
- Host an interactive web application to experiment with agents.
- Provides an intuitive user interface for agent interactions.

---

## Installation

### Prerequisites
- Python 3.9 or higher
- `.env` file with the following variables:
  ```env
  OPENAI_API_KEY=your_openai_api_key
  PHI_API_KEY=your_phi_api_key
  ```

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/divyansh89532/Finance-Agent.git
   cd Finance-Agent
   ```

2. **Install Dependencies**:
   using pip:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the project root and add your API keys.

4. **Run the Application**:
   ```
   python playground.py
   ```

5. Access the Playground:
   Open your browser and navigate to `http://localhost:8000`.

---

## Project Structure

```plaintext
financial-agent-playground/
├── financial_agent.py         # Defines the Financial AI and Web Search agents
├── playground.py              # Hosts the interactive playground app
├── requirements.txt           # Lists Python dependencies
├── .env.example               # Example environment variables file
├── README.md                  # Project documentation
```

---

## Usage

### Financial Analysis
1. Start the application.
2. Use the Financial AI Agent to:
   - Retrieve stock prices.
   - Analyze company fundamentals.
   - Summarize analyst recommendations.
   - Fetch company news.

### Web Search
1. Query the Web Search Agent for information retrieval.
2. Results are always accompanied by sources for reliability.

### Multi-Agent Collaboration
1. Use the multi-agent capability for comprehensive insights.
2. Example query: *"Summarize analyst recommendation and share the latest news for Amazon."*

---

## Technologies Used

### Libraries and Their Purpose

- **phi Framework**: The core framework enabling the creation and management of AI agents, providing an extensible structure for multi-agent collaboration.
- **Groq Model**: An advanced AI model used for natural language processing, supporting detailed financial and web search queries.
- **DuckDuckGo API**: Used for web search functionality, ensuring reliable and source-backed information retrieval.
- **YFinanceTools**: Provides tools for accessing stock prices, financial fundamentals, analyst recommendations, and company news, making it integral to the Financial AI Agent.
- **dotenv**: Simplifies the management of environment variables, ensuring secure handling of API keys and configurations.
- **Playground**: A module from the phi framework that facilitates building an interactive web application for agent experimentation.

---
