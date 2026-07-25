Installation
Download the course repository

```bash
# Clone the repo, cd to 'python' directory
git clone https://github.com/langchain-ai/lca-langgraph-essentials.git
cd ./lca-langgraph-essentials/python
```

Make a virtual environment and install dependancies
```bash
# Create virtual environment and install dependancies
uv sync
Run notebooks

# Run Jupyter notebooks directly with uv
uv run jupyter lab --allow-root
# Or activate the virtual environment if preferred
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
jupyter lab

# Start Ollama
ollama serve
# Start the model locally
ollama run ornith:35b
```

Update for local running
```bash
uv add langchain-ollama

# and use local version notebook what I modify
```
