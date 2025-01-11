# Financial-Agent-With-Phidata 💱🤖

![genaioutput1](https://github.com/user-attachments/assets/93022378-1e8f-489c-ab51-87d0acf2cd66)
<br><br>
![Screenshot 2025-01-06 155600](https://github.com/user-attachments/assets/b6eb63a4-b8c0-4b86-8b2d-80e1854d4785)

##

This project is a multi-agent AI application built using the **Phi** library. It integrates two specialized AI agents:
1. **Web Search Agent**: Searches the web for relevant information and provides concise results with sources.
2. **Finance AI Agent**: Fetches real-time financial data, including stock prices, analyst recommendations, fundamentals, and company news.

The application is designed to demonstrate the power of AI agents in leveraging specialized tools for specific tasks.

## **Features**

### Web Search Agent
- Utilizes **DuckDuckGo** for searching the web.
- Always includes sources in its output.
- Provides clear and concise responses.

### Finance AI Agent
- Leverages **YFinanceTools** for financial data analysis.
- Displays:
  - Real-time stock prices.
  - Analyst recommendations.
  - Stock fundamentals.
  - Latest company news.
- Outputs data in table format for clarity.

### Integrated Playground
- Combines multiple agents in a unified **Phi Playground** for an interactive experience.

## **Requirements**

- **Python** 3.10 or later.
- **Phi** library and its dependencies.
- A valid **Phi API Key**.
- Internet access for web search and financial data.

## **Installation**

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/Multi-Agent-Playground.git
cd Multi-Agent-Playground
2. Set Up a Virtual Environment
```
```bash
python -m venv venv
source venv/bin/activate    # For Linux/Mac
venv\Scripts\activate       # For Windows
```
3. Install Dependencies
Install the required libraries:

```bash
pip install -r requirements.txt
```
4. Configure Environment Variables
Create a .env file in the project root:
```bash
touch .env
```
Add your Phi API key to the .env file:
```env
PHI_API_KEY=your_phi_api_key
```

### Running the Application
Start the application with the following command:

```bash
python app.py
```
Once the application starts, access it in your browser at:
```
http://localhost:8000
```
Project Structure
```bash
Multi-Agent-Playground/
├── app.py               # Main application file
├── requirements.txt     # Python dependencies
├── README.md            # Project documentation
├── .env                 # Environment variables file (not included in the repo)
└── venv/                # Virtual environment directory (not included in the repo)
```

## Agents Overview
1. Web Search Agent
Model: Groq Llama3
Tools: DuckDuckGo for web search.
Special Instructions: Always include sources in the output.

2. Finance AI Agent
Model: Groq Llama3
Tools: YFinanceTools for financial data.

## Customization
### Agent Instructions:
Modify the instructions field for either agent to customize their behavior.
### Add New Agents:
Extend the playground by defining additional agents and tools.
### Modify Playground Settings:
Customize the Playground class to change app behavior or add features.

## License
This project is licensed under the MIT License. Feel free to modify and use it as per your requirements.

## Contributions
Contributions are welcome! Feel free to fork the repository, submit issues, or create pull requests.

### Acknowledgments
- Phi for providing the library and tools.
- DuckDuckGo for web search capabilities.
- Yahoo Finance for financial data insights.
