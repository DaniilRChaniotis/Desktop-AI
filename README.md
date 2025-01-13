# Desktop-AI
a simple desktopai
# AI Agent

A simple AI-powered assistant that interacts with users via the terminal. This project uses OpenAI's GPT-3.5-turbo model to generate intelligent responses and a text-to-speech engine for vocal output.

## Features
- **Interactive AI Chat:** Chat with the AI in natural language.
- **Text-to-Speech Integration:** The agent can speak its responses aloud.
- **Customizable Responses:** Modify prompts to change the agent’s behavior.

## Technologies Used
- **Python**: Core programming language.
- **OpenAI API**: For AI-based responses.
- **pyttsx3**: For text-to-speech functionality.
- **dotenv**: For securely storing the OpenAI API key.

## Installation
Follow these steps to set up and run the AI agent on your local machine:

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/ai-agent.git
cd ai-agent
```

### 2. Set Up a Virtual Environment
Create and activate a virtual environment to manage dependencies:

- **Windows:**
  ```bash
  python -m venv venv
  venv\Scripts\activate
  ```

- **macOS/Linux:**
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```

### 3. Install Dependencies
Install the required Python libraries:
```bash
pip install -r requirements.txt
```

### 4. Set Up Your OpenAI API Key
1. Create a `.env` file in the root directory of the project.
2. Add your OpenAI API key to the `.env` file in this format:
   ```
   OPENAI_API_KEY=sk-your-secret-key
   ```

### 5. Run the Agent
Start the AI agent:
```bash
python agent.py
```

## Usage
- The agent will greet you and wait for your input.
- Type your questions or commands, and the agent will respond both in text and speech.
- To exit, type `exit`, `quit`, or `bye`.

## File Structure
```
.
├── agent.py          # Main script for the AI agent
├── .env              # Environment variables (not included in the repo for security)
├── requirements.txt  # List of dependencies
└── README.md         # Project documentation
```

## Requirements
- Python 3.7 or higher
- OpenAI API key

## Dependencies
These are the main dependencies for the project:
- `openai`
- `pyttsx3`
- `python-dotenv`

Install them all using:
```bash
pip install -r requirements.txt
```

## Contributing
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- Thanks to OpenAI for providing the GPT models.
- Inspired by the desire to create interactive AI experiences.

---

Feel free to raise issues or suggest features in the [Issues section](https://github.com/your-username/ai-agent/issues).

