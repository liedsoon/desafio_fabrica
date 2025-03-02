# Desafio Fábrica de Software

Este é um projeto Django para avaliação de filmes, permitindo vizualizar detalhes dos filmes, avaliar, editar e excluir reviews.

# Requisitos

Certifique-se de ter os seguintes requisitos instalados:

Python 3.10+

Django

Virtualenv

# Instalação

Clone o repositório:

git clone https://github.com/seu-usuario/desafio.git
cd desafio

Crie e ative um ambiente virtual:

python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate  # Windows

Instale as dependências:

pip install -r requirements.txt

Execute as migrações do banco de dados:

python manage.py makemigrations
python manage.py migrate

Inicie o servidor:

python manage.py runserver

O servidor estará rodando em http://127.0.0.1:8000/

# Rodando o Projeto com Docker

docker build -t filmescore .
docker run -p 8000:8000 filmescore


Autor : José Liedson da Silva
