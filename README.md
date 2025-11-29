# Interview Chatbot 💬

An AI-powered interview preparation chatbot built with Streamlit and OpenAI's GPT-4o model. Practice your interview skills by simulating real interview scenarios with AI feedback.

## Features

- **Personalized Interview Experience**: Input your name, experience, and skills to receive tailored interview questions
- **Multiple Job Positions**: Choose from Data Scientist, Data Engineer, ML Engineer, BI Analyst, or Financial Analyst roles
- **Career Level Selection**: Select Junior, Mid-level, or Senior positions
- **Company-Specific Interviews**: Practice for interviews at top companies including Amazon, Meta, Udemy, 365 Company, Nestle, LinkedIn, and Spotify
- **AI-Powered Feedback**: Receive comprehensive feedback with a score (1-10) after completing your interview
- **Interactive Chat Interface**: Engage in a realistic 5-message interview conversation

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
   pip install streamlit openai streamlit-js-eval
   ```

3. Set up your OpenAI API key:
   - Create a `.streamlit/secrets.toml` file (if it doesn't exist)
   - Add your API key:
     ```toml
     OPENAI_API_KEY = "your-api-key-here"
     ```

## Usage

1. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

2. Open your browser and navigate to the URL shown in the terminal (typically `http://localhost:8501`)

3. Fill in your personal information:
   - Enter your name
   - Describe your experience
   - List your skills

4. Select your target position:
   - Choose your career level (Junior, Mid-level, Senior)
   - Select the position you're applying for
   - Pick the company you want to interview for

5. Click "Start Interview" to begin

6. Respond to interview questions (5 messages total)

7. Click "Get Feedback" to receive your performance evaluation

8. Use "Restart Interview" to practice again

## Project Structure

```
interview_chatbot/
├── .gitignore             # Git ignore rules (excludes secrets)
├── .streamlit/
│   └── secrets.toml       # OpenAI API key configuration (not tracked)
├── app.py                 # Main Streamlit application
└── README.md              # This file
```

## Security Note

⚠️ Never commit your API keys to version control. The `.streamlit/secrets.toml` file is already included in the `.gitignore` file to prevent accidental exposure.

## License

This project is open source and available for educational purposes.

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.
