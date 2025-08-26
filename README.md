Modulo VENV

- criar uma ambiente virtual, usando o comando venv chamado .desenv:
python -m venv .venv

- ativando ambiente
.\.venv\Scripts\activate

- Criando requirements
pip freeze > requirements.txt

- Criando um ambiente virtual a partir do requirements
pip install -r requirements.txt
