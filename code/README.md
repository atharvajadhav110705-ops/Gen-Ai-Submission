# Aptitude Question Generator

Practise placement aptitude and reasoning by topic and difficulty.

## Run

Use Python 3.12. Install Ollama, run `ollama pull qwen2.5:1.5b` and keep Ollama running. In this project directory run:

```bash
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

Use the sample menu or enter custom data. For llama.cpp set MODEL_URL to http://127.0.0.1:8080/v1/chat/completions and MODEL_NAME to the served model alias. The prompt and synthetic samples are in project.json. Reports include the observed checks and limits.

Built-in inputs default to reviewed practice questions. Uncheck that option or choose Custom to generate a new question with the model. Check generated answers and explanations before relying on them.
