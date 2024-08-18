# django-simples
Exemplo de um projeto simples com Django
Sites: https://docs.djangoproject.com/en/5.1/intro/tutorial01/ e
       https://pythonclub.com.br/

## Como rodar o projeto?

* Clone esse repositorio
* Crie um virtualenv com Python.
* Ative o virtualenv.
* Instale as dependências.
* Rode as migrações.

git clone https://github.com/wrfrodrigues59/django-simples.git
cd django-simples
python -m venv .venv
.venv/Scripts/Activate
python -m pip install --upgrade pip
pip install django dj-database-url python-decouple django-extensions
pip install -r requirements.txt
python contrib/env_gen.py
python manage.py migrate