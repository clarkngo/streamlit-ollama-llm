## Run Ollama Server
1. Open New Terminal
2. `curl -fsSL https://ollama.com/install.sh | sh`
3. `ollama serve`

## Pull and Chat with a Large Language Model (LLM) Conversational AI
1. Open New Terminal
2. `ollama pull gemma2:2b`
3. `ollama run gemma2:2b`
4. Type anything in the prompt to test
5. Press CTRL + D to Exit

## Run Chat Interface with Streamlit
1. Open New Terminal
2. `pip install -r requirements.txt`
3. `streamlit run llm_app.py`
4. Open `http://localhost:8501` in the browser
