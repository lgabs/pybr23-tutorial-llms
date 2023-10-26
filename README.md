## pybr23-tutorial-llms
Este repositório contém o código usado no tutorial de como criar chatbots capazes de responder perguntas fora do contexto onde foram treinados, unindo LLms e Embeddings com o framework [Langchain](https://github.com/langchain-ai/langchain).

## Preparar o ambiente
1. O recomendado é usar um ambiente virtual, seja [pyenv](https://github.com/pyenv/pyenv) (que vamos adotar neste repositório) ou [conda](https://docs.conda.io/projects/conda/en/latest/glossary.html?highlight=environment#conda-environment). No caso do pyenv, crie um ambiente virtual com Python 3.10 e ative-o (mais detalhes sobre pyenv [aqui](https://realpython.com/intro-to-pyenv/)).
2. Com o ambiente ativado, instale o [jupyter notebook](https://jupyter.org/install) com `pip install notebook`.
3. Para usar um ambiente virtual dentro de notebooks, crie um [kernel](https://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/what_is_jupyter.html#kernel) novo com o comando `python -m ipykernel install --user --name <environment_name> --display-name <kernel_name>`.
4. Inicie o jupyter com `jupyter notebook`, abra o(s) notebook(s) deste tutorial e escolha o kernel recém-criado para rodá-los.
```
