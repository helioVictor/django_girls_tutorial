# Blog Django Girls
Desenvolvimento de um projeto em Django, feito com base no tutorial do Django Girls.

- [Tutorial Django Girls [pt-BR]](https://tutorial.djangogirls.org/pt/)

## O que é Django?
Django (/ˈdʒæŋɡoʊ/ jang-goh) é um framework para aplicações web gratuito e de código aberto, escrito em Python. Um web framework é um conjunto de componentes que ajuda você a desenvolver sites de forma mais rápida e fácil.

## Primeiros Passos
### Instalação de algumas ferramentas básicas
  - Instalação do Python - Python 3.4 ou maior [[Python Download](https://www.python.org/downloads/)]
  - Instale o editor de Texto de sua preferência, como por exemplo, o Visual Studio Code - [[Visual Studio Code Download](https://code.visualstudio.com/download)]
  
### Preparação do Ambiente virtual
1. Crie um diretório chamado `djangogirls`:  
`$ mkdir djangogirls`
2. Entre no diretório:  
`$ cd djangogirls`
3. Crie a venv chamada:  
`$ python3 -m venv myvenv`
4. Ative a venv:  
`$ source myvenv/bin/activate`
5. Garantir que a última versão do PIP está instalada:  
`(myvenv) ~$ python -m pip install --upgrade pip`
### Instalando Pacotes com requisitos
1. Crie um arquivo chamado `requirements.txt`:  
`djangogirls/requirements.txt`
2. Adicione o seguinte texto nele:  
`Django~=2.2.4`
3. Ao final, execute esse comando:  
`(myvenv) ~$ pip install -r requirements.txt`
### Banco de Dados - SQLite3
1. Execute o seguinte comando para inicializar o SQLite3 (Banco de Dados):  
`(myvenv) ~/djangogirls$ python manage.py migrate`

### Iniciando o Servidor Web  
`(myvenv) ~/djangogirls$ python manage.py runserver`
