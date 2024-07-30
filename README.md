# OpenAI + Langchain Agents Workshop

## Running

* You need Python 3.11+ and [Poetry](https://python-poetry.org/) (install it with `pip install poetry`).

* Then, install dependencies with `poetry install`.

* Add your OpenAI and Langsmith (optional) api keys by renaming or copying `.env.example` to `.env` and filling in the missing values.

* Run `poetry run jupyter lab` and open the notebook.

### Optional: language server

If you want to use a language server with your notebook, you need Node.js, run `npm install` and then start Jupyter lab as before, it should be automatically picked up.
