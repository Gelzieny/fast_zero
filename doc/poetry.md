<h1 align="center"> Gerenciador de Pacotes Poetry</h1>

<p align="justify">
Este projeto utiliza o Poetry como gerenciador de dependências e ambiente virtual. 
O Poetry simplifica o gerenciamento de pacotes em projetos Python, oferecendo uma 
maneira prática de instalar, atualizar e remover dependências.
</p>

## Instalação do Poetry

<p align="justify">
Para instalar o Poetry, utilize o seguinte comando:
</p>

````bash
# Instala o Poetry
$ pipx install poetry

# Verificar versão do Poetry
$ poetry --version

# Criando projeto com Poetry
$ poetry new nome_do_projeto

# Criando o ambiente virtual
$ poetry install

# Habilitar o ambiente virtual
$ poetry shell

# Adicionar dependências
$ poetry add nome_da_dependencia

# Adicionar dependências de desenvolvimento
$ poetry add --dev nome_da_dependencia

#  Remover dependências
$ poetry remove nome_da_dependencia

# Verificar dependências
$ poetry show

# Atualizar dependências
$ poetry update
````