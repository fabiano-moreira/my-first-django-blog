# first_django

Projeto simples em Django.

Fiz também o deploy no Heroku:
[django-first-fabiano](https://django-first-fabiano.herokuapp.com/)

Feito com base no tutorial do rg3915.

Segue o github dele e o video no Youtube:

[rg3915/django-simples](https://github.com/rg3915/django-simples)

[Django: projeto simples ](https://www.youtube.com/watch?v=DEhzECzf7_g&t=305s)

1 - Clone esse repositório;

```
git clone git@github.com:fabiano-moreira/first_django.git

```

2 - Crie um ambiente virtual para instalar os pacotes e não misturar com a estrutura do seu sistema* Ative o virtualenv;

```
$ cd djangogirls
$ python3 -m venv .venv
$ source .venv/bin/activate
```

3 -  Instale as dependências;

```
(.venv)$ pip install -r requirements.txt

```

4 - Rode as migrações:

```
(.venv)$ python manage.py migrate

```
5 - Crie um usuário administrador para o Django:

```
(.venv)$ python manage.py createsuperuser
```

6 - Para rodar o projeto, execute o comando abaixo e acesse o ip e porta informados:

```
(.venv)$  python manage.py runserver
```
