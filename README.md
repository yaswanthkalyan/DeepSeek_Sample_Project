# DeepSeek Sample Project

## Overview
DeepSeek Code Companion is an AI-powered chatbot built with Streamlit, LangChain, and Ollama. It serves as an AI pair programmer, assisting users with coding, debugging, and documentation.

## Features
- 🧠 AI-Powered Code Assistance
- 🐍 Python Expertise
- 🐞 Debugging Support
- 📝 Code Documentation Generation
- 💡 Solution Design Guidance
- Persistent Chat History for Follow-Up Questions

## Tech Stack
- **Frontend**: Streamlit
- **AI Model**: DeepSeek via LangChain & Ollama
- **Backend Processing**: Python (LangChain & LLM-based responses)

## Installation
### Prerequisites
- Python 3.10+
- Anaconda (recommended for environment management)
- Ollama installed and running locally
- Streamlit installed

### Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-repo/DeepSeek_Sample_Project.git
   cd DeepSeek_Sample_Project
   ```
2. **Create and activate a virtual environment**
   ```bash
   conda create --name deepseek_env python=3.11 -y
   conda activate deepseek_env
   ```
3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the application**
   ```bash
   streamlit run app.py
   ```

## Usage
- Select a model from the sidebar.
- Enter your coding question in the chat input field.
- The AI will generate responses and retain conversation history for context.
- You can ask follow-up questions and receive refined answers.

## Troubleshooting
If you encounter `KeyError: 'Input to ChatPromptTemplate is missing variables {'-1'}`:
- Ensure that message history formatting is correct.
- Modify the `build_prompt_chain()` function to properly format inputs.

## Future Enhancements
- Support for additional programming languages.
- Enhanced debugging capabilities.
- Integration with external APIs for code execution.

## License
MIT License

## Acknowledgments
Built using [Streamlit](https://streamlit.io/), [LangChain](https://python.langchain.com/), and [Ollama](https://ollama.ai/).
