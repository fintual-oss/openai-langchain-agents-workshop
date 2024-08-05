# OpenAI + Langchain Agents Workshop

This is the support material used in the workshop that went live on 2024/08/01 [(link to recording)](https://www.youtube.com/watch?v=IJ78ES1K83I).

It's a step-by-step guide to building AI agents with OpenAI and Langchain. As a bonus, there's a final section with an extremely simple prototype chat interface so you can showcase your project with a better UI than a text terminal.

## Running

* You need Python 3.11+ and [Poetry](https://python-poetry.org/) (install it with `pip install poetry`).

* Then, install dependencies with `poetry install`.

* Add your OpenAI and Langsmith (optional) api keys by renaming or copying `.env.example` to `.env` and filling in the missing values.

* Run `poetry run jupyter lab` and open the notebook.

### Optional: language server

If you want to use a language server with your notebook, you need Node.js, run `npm install` and then start Jupyter lab as before, it should be automatically picked up.
