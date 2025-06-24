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


## 🧰 Tecnologias utilizadas

- **[FastAPI](https://fastapi.tiangolo.com/)**: Framework moderno e rápido para criar APIs em Python, com validações automáticas e documentação gerada automaticamente.
- **[Pytest](https://docs.pytest.org/)**: Ferramenta simples e poderosa para escrever e executar testes em Python.
- **[Poetry](https://python-poetry.org/)**: Gerenciador de dependências e ambientes para projetos Python, com configuração centralizada no `pyproject.toml`.
- **[Taskipy](https://pypi.org/project/taskipy/)**: Automatiza tarefas como testes e linters com comandos curtos definidos no `pyproject.toml`.
- **[Ruff](https://docs.astral.sh/ruff/)**: Linter rápido para manter o código Python limpo e padronizado.


## 🚀 Como executar o projeto

### Pré-requisitos

<p align="justify">Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:</p>

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=git,python,docker,vscode" />
</a>

### Clone o repositório

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