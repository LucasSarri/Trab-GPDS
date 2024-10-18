# Como rodar o projeto?
- Instalar o Python
- Instale as dependências, executando os seguintes comandos no CMD:
    - pip install django==3.0.5
    - pip install django-widget-tweaks
    - pip install xhtml2pdf
- Rodar os comandos para criar o banco de dados no CMD:
    - py manage.py makemigrations
    - py manage.py migrate
    - py manage.py runserver
    *OBS: Se for no Linux, como é meu caso, vai ser python3 no lugar de py. EX: python3 manage.py makemigrations
- Após isso basta acessar o navegador no caminho: http://127.0.0.1:8000/ ou localhost:8000.

# Rodando da segunda vez em diante
Quando for rodar o projeto novamente após já ter configurado o projeto, basta só executar o comando:
    - py manage.py runserver ou python3 manage.py runserver
- Após isso basta acessar o navegador no caminho: http://127.0.0.1:8000/ ou localhost:8000.