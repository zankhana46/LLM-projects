# Swasthya Chatbot
![Swasthya Logo](logo.png)

## Overview
**Swasthya Chatbot** is a Streamlit-based application designed to facilitate conversations with a medical AI model called **DocBot**. The application also supports querying financial reports with an integrated AI, and potentially analyzing medical images (commented out in the code).

## Features
- **DocBot**: Engage in text-based medical conversations. Ask questions related to health and receive answers from a highly trained medical AI.
- **Chat with Report**: Upload a PDF financial report and ask questions about its contents. The AI model will provide insights and explanations related to budgeting, investments, and personal finance.
- **(Optional) VisionBot**: Analyze and interpret medical images (this feature is currently commented out).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/swasthya-chatbot.git
   cd swasthya-chatbot
2. Install the required dependencies:
  bash
  Copy code
  pip install -r requirements.txt
3. Set up environment variables:
  Create a .env file in the root directory and add your Google API key:
  bash
  Copy code
  GOOGLE_API_KEY=your_google_api_key


Here's a README file based on the provided code:

markdown
Copy code
# Swasthya Chatbot

![Swasthya Logo](logo.png)

## Overview
**Swasthya Chatbot** is a Streamlit-based application designed to facilitate conversations with a medical AI model called **DocBot**. The application also supports querying financial reports with an integrated AI, and potentially analyzing medical images (commented out in the code).

## Features
- **DocBot**: Engage in text-based medical conversations. Ask questions related to health and receive answers from a highly trained medical AI.
- **Chat with Report**: Upload a PDF financial report and ask questions about its contents. The AI model will provide insights and explanations related to budgeting, investments, and personal finance.
- **(Optional) VisionBot**: Analyze and interpret medical images (this feature is currently commented out).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/swasthya-chatbot.git
   cd swasthya-chatbot
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Set up environment variables:
Create a .env file in the root directory and add your Google API key:
bash
Copy code
GOOGLE_API_KEY=your_google_api_key

## Usage
1. Run the Streamlit app:
  bash
  Copy code
  streamlit run app.py
2. Use the sidebar to choose between DocBot and Chat with Report.
  DocBot: Start a medical conversation by typing your question in the chat input.
  Chat with Report: Upload a PDF report and type your question to get financial insights.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
