# ChatGPT Prompt Engineering for Developers

Experimenting with OpenAI's ChatGPT using the free training
[ChatGPT Prompt Engineering for Developers](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)
by [DeepLearning.AI](https://deeplearning.ai).

# Setup

- Create an account on [OpenAI's platform](https://platform.openai.com/overview)
- If you don't have enough free credits, switch to a paid account
- Create an [API key](https://platform.openai.com/account/api-keys)
- Store the API key in a file called `.env` in the current project using the following format:

```shell
# OpenAI key
OPENAI_API_KEY=sk-…
```

- Run Poetry: `poetry install`

**Note**: The `.env` file is ignored if the `.gitignore` file is configured correctly

# Usage

Either start **Jupyter Notebook** to run the notebooks, or run the Python scripts in a Poetry shell using:

```shell
poetry shell
python prompting.py
```
