# Website Teste Python
* 1- Criar ambiente virtual

1. python -m venv ./venv
2. excecutar: ./venv/Scripts/activate.bat

*2- Instalar dependencias
1. python.exe -m pip install --upgrade pip
2. pip install Flask
3. Criar Procfile
    web: gunicorn NOME_ARQUIVO:app
4. pip install gunicorn
5. pip freeze > requirements.txt
