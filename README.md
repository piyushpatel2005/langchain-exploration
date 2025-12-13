# LangChain Exploration

This set of tutorials assume `uv` and `ollama` installed locally. All code can be executed locally.

## Set up

1. Clone the repository:
   ```bash
   git clone https://github.com/piyushpatel2005/langchain-exploration.git
    cd langchain-exploration
    ```

2. Create and activate a virtual environment:
   ```bash
   uv venv
   source .venv/bin/activate
   ```

3. Install the required packages:
   ```bash
   uv sync
   ```

4. Ensure `ollama` is installed and running on your machine. You can download it from [Ollama's official website](https://ollama.com/).
5. Download a local model using Ollama. For example:
   ```bash
   ollama pull gemma3:1b
   ```

## Running Tutorials

Each lesson is contained in a notebook.

```bash
python -m ipykernel install --user --name=langchain-exploration
jupyter notebook
```