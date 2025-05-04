# Local ChatGPT with thinking UI

This project leverages Qwen3:4B and Streamlit to create a 100% locally running mini-ChatGPT app.

## Installation and setup

**Setup Ollama**:
   ```bash
   # setup ollama on linux 
   curl -fsSL https://ollama.com/install.sh | sh
   # pull the Qwen3:4B model
   ollama pull qwen3:4b 
   ```


**Install Dependencies**:
   Ensure you have Python 3.11 or later installed.
   ```bash
   pip install streamlit ollama
   ```

**Run the app**:

   Run the streamlit app as follows:
   ```bash
   streamlit run app.py -w
   ```

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.
