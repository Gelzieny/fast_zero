<p align="center">
  <a href="#">
    🔗 <img src="https://github.com/Gelzieny/fast_zero/blob/main/.github/img/fastapi.png?raw=true"  alt="FastApi do Zero" />
  </a>
</p>


Projeto desenvolvido durante o curso [FastAPI do Zero](https://fastapidozero.dunossauro.com/), ministrado por [Rodrigo "Dunossauro"](https://github.com/dunossauro).

## ✨ Sobre

Este projeto tem como objetivo apresentar os fundamentos e boas práticas do desenvolvimento de APIs com **FastAPI**, com foco em:

- Estruturação de projeto
- Rotas e validações
- Testes automatizados com `pytest`
- Execução de tarefas com `taskipy`
- Qualidade de código com `ruff`
- Tipagem e performance


## 🛠 Tecnologias

<p align="justify">Este projeto utiliza um conjunto de tecnologias modernas para garantir uma aplicação eficiente e escalável, incluindo:</p>



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

# Ativar o ambiente virtual criado pelo Poetry para o seu projeto
poetry shell

# Configure as variáveis de ambiente criando um arquivo .env com o seguinte conteúdo:
POSTGRES_URL="postgresql://usuário:senha@host:porta/banco_de_dados"

# Rodar o comando 
docker-compose up -d
````