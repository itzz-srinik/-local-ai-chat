# -local-ai-chat A single-file chat interface for local LLMs running in Ollama.
No build step, no dependencies, no data leaves your machine.

## Use
1. Install Ollama and pull a model: `ollama pull llama3.2`
2. Allow browser access: `OLLAMA_ORIGINS=* ollama serve`
3. Open the live page (or `index.html`) and start chatting.

The Ollama URL and model name can be changed at the top of the page.

## Features
- Streaming responses
- Conversation memory within a session
- Works on desktop and mobile browsers