# 🤖 AI Chatbot (Streamlit + Groq)

A simple AI chatbot built with **Streamlit** and **Groq API**, using the `llama-3.3-70b-versatile` model.

## Features

- Clean chat interface using Streamlit's `st.chat_message`
- Maintains chat history during the session
- Uses Groq's fast LLM inference
- Simple API key input (password field)

## Requirements

- Python 3.9+
- Groq API key ([get one here](https://console.groq.com/keys))

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. (Optional but recommended) Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Running the App

```bash
streamlit run app.py
```

> Replace `app.py` with your actual filename if different.

Then open the local URL shown in the terminal (usually `http://localhost:8501`).

## Usage

1. Enter your Groq API key in the input field at the top.
2. Type your message in the chat box at the bottom.
3. Get instant AI-generated responses.

## Deployment (Streamlit Cloud)

1. Push this repository to GitHub.
2. Go to [share.streamlit.io](https://share.streamlit.io) and connect your repo.
3. Set the main file path (e.g., `app.py`).
4. (Optional) Add your Groq API key as a secret instead of typing it every time:
   - Go to **App settings → Secrets**
   - Add:
     ```toml
     GROQ_API_KEY = "your-api-key-here"
     ```

## Project Structure

```
.
├── app.py               # Main Streamlit app
├── requirements.txt     # Python dependencies
├── .gitignore            # Files/folders excluded from Git
└── README.md             # Project documentation
```

## License

Free to use and modify.
  
