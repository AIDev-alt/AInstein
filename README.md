# Crypto AInstein

<img src="static/einstein.png" width="200" alt="Einstein AI Assistant"/>

Chat with a crypto-savvy Einstein! Get blockchain and cryptocurrency insights explained through the lens of physics and Einstein's unique perspective.

## Setup

1. Clone this repository:   ```bash
   git clone <repository-url>
   cd <repository-name>   ```

2. Install the required dependencies:   ```bash
   pip install -r requirements.txt   ```

3. Get your Anthropic API key:
   - Go to [console.anthropic.com](https://console.anthropic.com/)
   - Create an account or sign in
   - Generate an API key

## Running the Application

1. Start the Streamlit app:   ```bash
   streamlit run main.py   ```

2. Your default web browser will open automatically with the chatbot interface
   - If it doesn't open automatically, check the terminal for the local URL (usually http://localhost:8501)

3. In the sidebar, enter your Anthropic API key
   - The key will be securely stored for the session
   - You'll need to re-enter it if you refresh the page

## Features

- Clean, simple chat interface
- Real-time responses from Claude
- Message history maintained during the session
- Secure API key handling
- Crypto-focused Einstein personality
- Physics analogies for blockchain concepts


## Project Structure

Components of the project:
- `agents/`: Contains the AI agent logic and personality
- `ui/`: Handles all user interface components
- `static/`: Stores static assets like images
- `main.py`: Orchestrates the application flow

Additional files:
- `.gitignore`: Git ignore rules for Python, API keys, etc.
- `LICENSE`: MIT license file
- `requirements.txt`: List of Python dependencies
- `README.md`: This documentation file

## Note

Make sure to keep your API key secure and never commit it to version control.