# personal-gpt

ChatGPT on your perosonal files.

## Installation

Install [Langchain](https://github.com/hwchase17/langchain) and other required packages.
```
pip install langchain openai chromadb tiktoken unstructured
```
Modify `constants.py.default` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys), and rename it to `constants.py`.

Place your own data into `data/data.txt`.

## Example usage
Test reading `data/data.txt` file.
```

> python chatgpt.py "what is my stage name"
Your stage name is slim shady.
```

Test reading `data/pet.pdf` file.
```
> python chatgpt.py "what is my pet's name"
Your pet's name is Peppa.
```