# graphrag-for-ollama

Microsoft graphrag library updated to use Ollama for indexing and GLOBAL and **LOCAL** search.
Only two files were changed: llm/openai/openai_embeddings_llm.py and query/llm/oai/embedding.py

# installation

- conda create --name grahrag-for-ollama python=3.10
- conda activate grahrag-for-ollama
- git clone https://github.com/teezeerc/graphrag-for-ollama
- cd graphrag-for-ollama
- pip install poetry
- pip install ollama
- poetry install

From that point follow instructions from original guide: https://microsoft.github.io/graphrag/posts/get_started/
