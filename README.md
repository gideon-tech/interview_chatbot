# Interview Chatbot 💬

An AI-powered interview practice chatbot built with Streamlit and OpenAI's GPT-4o. This application simulates job interviews for various tech and business positions, helping candidates prepare and receive feedback on their interview performance.

## Features

- **Personalized Interviews**: Enter your name, experience, and skills to receive tailored interview questions
- **Multiple Positions**: Practice for various roles including:
  - Data Scientist
  - Data Engineer
  - ML Engineer
  - BI Analyst
  - Financial Analyst
- **Experience Levels**: Choose from Junior, Mid-level, or Senior positions
- **Company-Specific**: Practice for interviews at companies like Amazon, Meta, LinkedIn, Spotify, and more
- **AI Feedback**: Receive a performance score (1-10) and detailed feedback after completing the interview
- **Interactive Chat Interface**: Natural conversation flow with a GPT-4o powered HR interviewer

## Prerequisites

- Python 3.8+
- OpenAI API key

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/gideon-tech/interview_chatbot.git
   cd interview_chatbot
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:
   
   Create a `.streamlit/secrets.toml` file and add your API key:
   ```toml
   OPENAI_API_KEY = "your-openai-api-key-here"
   ```

## Usage

Run the Streamlit application:

```bash
streamlit run app.py
```

Then follow these steps:
1. Enter your personal information (name, experience, skills)
2. Select the position level, role, and company
3. Click "Start Interview" to begin
4. Respond to the interviewer's questions (5 exchanges)
5. Click "Get Feedback" to receive your performance evaluation

## Dependencies

- `streamlit` - Web application framework
- `openai` - OpenAI API client
- `streamlit-js-eval` - JavaScript evaluation for Streamlit

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
