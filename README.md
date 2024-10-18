# AgriBot - Your Agricultural Assistant

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-blue.svg)](https://github.com/arastuthakur/agribot)

AgriBot is a web-based chatbot designed to assist users with agricultural queries and provide information about farming practices. Built using Flask for the backend and a responsive front-end interface, AgriBot mimics the functionality of popular chat interfaces, like ChatGPT.

## Features

- **User-Friendly Interface**: An intuitive chat interface that is responsive and resembles modern chat applications.
- **Adaptive Background**: Automatically switches between light and dark themes based on user preferences.
- **Chat History Persistence**: Stores chat history in the browser's local storage, allowing users to retrieve past conversations even after refreshing or closing the page.
- **Markdown Formatting**: The bot's responses can include bold, italic, and line breaks for enhanced readability.

## Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask
- **Vector Database**: FAISS (for document similarity search)
- **AI Models**: Integration with Google Generative AI for generating responses

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/arastuthakur/agribot.git
   cd agribot

2. Install the required dependencies:
```bash
pip install Flask flask-session langchain-google-genai langchain-community
```
4. Set up your Google API Key and any other environment variables as needed.
5. Run the application:
```bash
python app.py
```
7. Open your web browser and navigate to http://127.0.0.1:5000.
## Usage

- Enter your questions in the input box and press "Send" or hit the "Enter" key to receive responses from the AgriBot.
- The bot will provide answers related to agriculture based on predefined logic and integration with AI models.
- Chat history will be saved in your local storage, so you can return to your previous conversations anytime.

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to report issues, feel free to open an issue or submit a pull request.


## Acknowledgments

- [Flask](https://flask.palletsprojects.com/) - A lightweight WSGI web application framework.
- [LangChain](https://langchain.com/) - Framework for developing applications powered by language models.
- [Google Generative AI](https://cloud.google.com/generative-ai) - Provides AI-generated content capabilities.

## Author

Arastu Thakur - [LinkedIn](https://www.linkedin.com/in/arastuthakur) | [GitHub](https://github.com/arastuthakur)
