# semantic-web-project

A concept normalization system that maps free-text mentions in board game documents to concepts defined in an OWL ontology (`BoardGameOntology-0MI3400805.ttl`). It uses a two-pass LLM pipeline powered by `qwen2.5:14b` via Ollama — the first pass extracts candidate spans, the second normalizes each span to an ontology class or data property with a confidence score. Results are presented as color-coded HTML highlights and a pandas annotation table inside a Jupyter Notebook.

## Running the Project

Installing the [ollama model](https://ollama.com/) is required.

Run 

```sh
pip install -r requirements.txt
```

before starting the project.

Open the Jupyter notebook in your editor of choice and run the cells one after the other.