# Interview Helper

> **Note:** This project is still in progress and I plan to enhance it in the future.

This is a Streamlit web application that provides tailored interview tips using OpenAI's GPT-4o model via LangChain.

## Features
- Enter your target position, company, strengths, and weaknesses.
- Receive personalized interview tips and preparation advice.
- Powered by OpenAI and LangChain.

## Requirements
- Python 3.8+
- [Streamlit](https://streamlit.io/)
- [LangChain](https://python.langchain.com/)
- [langchain-openai](https://python.langchain.com/docs/integrations/llms/openai)
- [python-dotenv](https://pypi.org/project/python-dotenv/)

## Setup
1. **Clone the repository**
2. **Install dependencies:**
   ```bash
   pip install streamlit langchain langchain-openai python-dotenv
   ```
3. **Create a `.env` file** in the project root with your OpenAI API key:
   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   ```
4. **Run the app:**
   ```bash
   streamlit run interview_helper.py
   ```

## Usage
- Fill in your position, company, strengths, and weaknesses.
- The app will display interview tips tailored to your input.
