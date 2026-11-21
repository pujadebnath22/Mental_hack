
# Mental Health Support Chatbot

This project is a Mental Health Support Chatbot built using [Streamlit](https://streamlit.io/) and OpenAI's GPT-3.5-turbo model. It provides mental health support through a chat interface, offering sentiment analysis, mood tracking, and personalized coping strategies based on user input.

## Features

- **Chat Interface**: Interact with the chatbot through a user-friendly chat interface.
- **Sentiment Analysis**: Analyze the sentiment of user messages and categorize them into different emotions.
- **Mood Tracking**: Track the user's mood over time based on their messages.
- **Coping Strategies**: Provide personalized coping strategies based on the user's emotional state.
- **Session Summaries**: Summarize the conversation and provide insights at the end of each session.
- **Helpful Resources**: Provide links to mental health support resources.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Vikranth3140/Mental-Health-Support-Chatbot.git
   cd Mental-Health-Support-Chatbot
   ```

2. **Create and activate a virtual environment:**

   ```bash
   python -m venv env
   ```

   On Windows:

   ```bash
   env\Scripts\activate
   ```

   On macOS/Linux:

   ```bash
   source env/bin/activate
   ```

3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Set up your OpenAI API key:**

   - Obtain an API key from the [OpenAI Platform](https://platform.openai.com/api-keys).
   - Configure the key securely using an environment variable named `OPENAI_API_KEY`.
   - Never commit your actual API key to GitHub.

## Usage

1. **Run the Streamlit application:**

   ```bash
   streamlit run app.py
   ```

2. Open the provided URL, typically `http://localhost:8501`, in your web browser.

3. **Start interacting with the chatbot:**
   - Type your message in the input box and press **Send**.
   - The chatbot will respond, analyze sentiment, track mood, and suggest coping strategies as supported by the implementation.

## Project Structure

```text
Mental-Health-Support-Chatbot/
├── app.py
├── requirements.txt
└── README.md
```

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- [Streamlit](https://streamlit.io/)
- [OpenAI](https://openai.com/)
- [TextBlob](https://textblob.readthedocs.io/en/dev/)

## Mental Health Resources

If you need support, consider contacting a qualified mental health professional or a trusted person.

- **United States:** Call or text 988 through the [988 Suicide & Crisis Lifeline](https://988lifeline.org/).
- **International resources:** Visit [Find A Helpline](https://findahelpline.com/) to find support in your country.

> **Disclaimer:** This chatbot is intended for educational and informational purposes only. It is not a substitute for professional mental health advice, diagnosis, or treatment. AI-generated responses and sentiment analysis may be inaccurate.
