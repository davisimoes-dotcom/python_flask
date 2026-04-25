# Lista de comandos 
- Cria o ambiente virtual na pasta venv

```

python -m venv venv
```
-Ativar o ambiente virtual 
```python
venv\Scripts\activate
```
- Instalar todos os pacotes necessários
```python
pip install flask
pip  install flask-wtf
pip  install resquest
pip  install pytest
pip  install pytest-flask
```

- Salva a lista de pacotes instalados 
- no arquivo requiriments.txt
- Isso permite que as outras pessoa instalem as mesmas versões
```python
pip freeze > requeriments.txt
```