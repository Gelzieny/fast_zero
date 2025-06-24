<p align="center">
  <a href="#">
    🔗 <img src="https://github.com/Gelzieny/fast_zero/blob/main/.github/img/fastapi.png?raw=true"  alt="FastApi do Zero" />
  </a>
</p>

<p align="center">

Projeto desenvolvido durante o curso [FastAPI do Zero](https://fastapidozero.dunossauro.com/), ministrado por [Rodrigo "Dunossauro"](https://github.com/dunossauro).

</p>
## ✨ Sobre

Este projeto tem como objetivo apresentar os fundamentos e boas práticas do desenvolvimento de APIs com **FastAPI**, com foco em:

- Estruturação de projeto
- Rotas e validações
- Testes automatizados com `pytest`
- Execução de tarefas com `taskipy`
- Qualidade de código com `ruff`
- Tipagem e performance

## 📁 Estrutura do projeto

```bash
.
├── fast_zero
│  └── app.py
├── pyproject.toml
├── README.md
├── docker-compose.yml
├── .env
├── .env.example
├── .gitignore
└── tests
  └── __init__.py
```

## 🛠 Tecnologias

<p align="justify">Este projeto utiliza um conjunto de tecnologias modernas para garantir uma aplicação eficiente e escalável, incluindo:</p>


- **[FastAPI](https://fastapi.tiangolo.com/)**: Framework web moderno e rápido para a criação de APIs com Python baseado em tipo. Permite validações automáticas, geração de documentação interativa e desempenho comparável ao Node.js e Go.
- **[Pytest](https://docs.pytest.org/)**: Framework robusto para testes automatizados em Python. Simples de começar e poderoso o suficiente para testar aplicações complexas, com suporte a fixtures, plugins e relatórios de cobertura.
- **[Poetry](https://python-poetry.org/)**: Ferramenta para gerenciamento de dependências e empacotamento de projetos Python. Substitui o uso do `pip` e `virtualenv` com uma abordagem mais moderna e organizada via `pyproject.toml`.
- **[Taskipy](https://pypi.org/project/taskipy/)**: Utilitário que permite automatizar tarefas usando scripts definidos no `pyproject.toml`. É ideal para encurtar comandos comuns como `test`, `lint`, `run`, entre outros.
- **[Ruff](https://docs.astral.sh/ruff/)**: Linter extremamente rápido escrito em Rust, usado para garantir a qualidade e padronização do código Python. Substitui ferramentas como Flake8 e isort com alta performance.


## 🚀 Como executar o projeto

### Pré-requisitos

<p align="justify">Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:</p>

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=git,python,docker,vscode" />
</a>


````bash
# Clone este repositório
$ git clone <https://github.com/Gelzieny/fast_zero.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd fast_zero

# Poetry para usar uma versão específica do Python
poetry env use 3.13

# Instale as dependências
poetry install

#Comando para instalar uma extensão do Poetry para habilitar o shell
pipx inject poetry poetry-plugin-shell

# Ativar o ambiente virtual criado pelo Poetry para o seu projeto
poetry shell

# Configure as variáveis de ambiente criando um arquivo .env com o seguinte conteúdo:
POSTGRES_URL="postgresql://usuário:senha@host:porta/banco_de_dados"

# Rodar o comando 
docker-compose up -d
````

## 🧠 Aprendizado contínuo

<p align="justify">

Esse projeto faz parte do módulo estável da trilha [FastAPI do Zero](https://fastapidozero.dunossauro.com/estavel/aulas/2025/).
A cada aula, novas funcionalidades são incrementadas seguindo uma abordagem prática.
</p>